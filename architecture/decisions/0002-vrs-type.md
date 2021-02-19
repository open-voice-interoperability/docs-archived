
# 2. vrs-type

  

Date: 2021-02-04

  

## Status

  

In Progress

  

Supercedes [1. Record architecture decisions](0001-record-architecture-decisions.md)

  

## Context

The Voice Assistance Platform's job is to identify if the call is implicit or an explicit utterance. If explicit, then it will engage and call VRS.

Our goal is to identify who is responsible for determining the VRS in the utterance.

## Solution Options


  **Issue 1:**
| Options | Pros | Cons |
|--|--|--|
| Option 1. Create a VRS entity and VRS type in NLU. | - easier for slot to identify. <br>- align in the role of NLU  | - risk of inconsistency in understanding VRS type   |
| Option 2. Dialog Manager identifies when utterance is explicit |  | - creating a separation of understanding the utterance <br> - risk of inconsistency in understanding VRS type |
| Option 3. VRS will decide the vrs type in the utterance | - consistent logic for vrs identification across different VRS  | - VRS will have to receive the whole utterance. <br> - VRS will need to deal with privacy issue  |

### Sequence Diagrams

#### Option 1
<details>    
  
```mermaid
sequenceDiagram
autonumber
participant C as Channel
participant SR as Speech Recognizer
participant TTS as Text To Speech
participant NLU as NLU Intent
participant DM as Dialog Manager
participant SM as Session Manager
participant VRS as OVN VRS
participant SS as SmallGrocery Server


C ->> SR: Audio: "hey bigtincan, add milk to my shopping cart at small grocery"
SR ->>+ NLU: Text: "hey bigtincan, add milk to my shopping cart at small grocery" 
  Note right of NLU: OPTION 1. NLU identifies the VRS text in the utterance 
NLU ->> SM: 
SM ->> VRS: {"vrs": "small grocery"}
VRS ->> DM: {"nlu":"https://smallgrocery.com/dialogmanager/smallgrocery_bigtincan/"}
DM ->> NLU: {...}
NLU ->> DM: {"intent":"addtocart", <br> "product":"milk", <br> "qty":"1", <br> "context":{"utterances:[{"add milk to my shopping..."}]}<br>}
DM ->> SS: {"action":"addtocart", <br> "product":"milk", <br> "qty":"1", <br> "context": {"userid":[linked], <br> "utterances": [{...}]}}
SS ->> DM: {"response_code": {201}}
DM ->> TTS: {"response_text": "milk added to the shopping cart" <br> "context":{...}}
TTS ->> C: Audio: "milk added to the shopping cart"

```
</details>    


#### Option 2
<details>    
  
```mermaid
sequenceDiagram
autonumber
participant C as Channel
participant SR as Speech Recognizer
participant TTS as Text To Speech
participant NLU as NLU Intent
participant DM as Dialog Manager
participant SM as Session Manager
participant VRS as OVN VRS
participant SS as SmallGrocery Server


C ->> SR: Audio: "hey bigtincan, add milk to my shopping cart at small grocery"
SR ->>+ DM: Text: "hey bigtincan, add milk to my shopping cart at small grocery" 
  Note right of DM: OPTION 2. NLU identifies the VRS text in the utterance 
DM ->> SM: 
SM ->> VRS: {"vrs": "small grocery"}
VRS ->> DM: {"nlu":"https://smallgrocery.com/dialogmanager/smallgrocery_bigtincan/"}
DM ->> NLU: {...}
NLU ->> DM: {"intent":"addtocart", <br> "product":"milk", <br> "qty":"1", <br> "context":{"utterances:[{"add milk to my shopping..."}]}<br>}
DM ->> SS: {"action":"addtocart", <br> "product":"milk", <br> "qty":"1", <br> "context": {"userid":[linked], <br> "utterances": [{...}]}}
SS ->> DM: {"response_code": {201}}
DM ->> TTS: {"response_text": "milk added to the shopping cart" <br> "context":{...}}
TTS ->> C: Audio: "milk added to the shopping cart"

```
</details>   

#### Option 3
<details>    
  
```mermaid
sequenceDiagram
autonumber
participant C as Channel
participant SR as Speech Recognizer
participant TTS as Text To Speech
participant NLU as NLU Intent
participant DM as Dialog Manager
participant SM as Session Manager
participant VRS as OVN VRS
participant SS as SmallGrocery Server


C ->> SR: Audio: "hey bigtincan, add milk to my shopping cart at small grocery"
SR ->>+ NLU: Text: "hey bigtincan, add milk to my shopping cart at small grocery" 
NLU ->> SM: 
SM ->> VRS: {"lookup": "add milk to my shopping cart at small grocery"}
Note right of VRS: OPTION 3. VRS identifies the VRS in the utterance 
VRS ->> DM: {"vrs":"small grocery"<br>"nlu":"https://smallgrocery.com/dialogmanager/smallgrocery_bigtincan/"}
DM ->> NLU: {...}
NLU ->> DM: {"intent":"addtocart", <br> "product":"milk", <br> "qty":"1", <br> "context":{"utterances:[{"add milk to my shopping..."}]}<br>}
DM ->> SS: {"action":"addtocart", <br> "product":"milk", <br> "qty":"1", <br> "context": {"userid":[linked], <br> "utterances": [{...}]}}
SS ->> DM: {"response_code": {201}}
DM ->> TTS: {"response_text": "milk added to the shopping cart" <br> "context":{...}}
TTS ->> C: Audio: "milk added to the shopping cart"

```
</details>   
  

## Decision

  

//to-do

  

## Consequences

//to-do
