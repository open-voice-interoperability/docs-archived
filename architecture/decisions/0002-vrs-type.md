---
published: false
---

# 2. vrs-type

  

Date: 2021-02-04

  

## Status

  

In Progress

  

Supercedes [1. Record architecture decisions](0001-record-architecture-decisions.md)

  

Superceded by [3. vrs-integration](0003-vrs-integration.md)

## Context

The Voice Assistance Platform's job is to identify if the call is implicit or an explicit utterance. If explicit, then it will engage and call VRS.

Our goal is to identify who is responsible for determining the VRS in the utterance.

## Solution Options


  **Issue 1:**
| Options | Pros | Cons |
|--|--|--|
| Option 1. Create a VRS entity in NLU. | - easier for slot to identify. <br>- align in the role of NLU  | - risk of inconsistency in understanding VRS entity   |
| ~~Option 2. Dialog Manager identifies when utterance is explicit |  | - creating a separation of understanding the utterance <br> - risk of inconsistency in understanding VRS type~~ |
| Option 3. VRS will decide the VRS entity in the utterance | - consistent logic for vrs identification across different VRS  | - VRS will have to receive the whole utterance. <br> - VRS will need to deal with privacy and security <br> - adds significant complexity to the VRS. VRS will require to have its own NLU. <br> |

### Sequence Diagrams

#### Option 1
<details>    
  
```mermaid
sequenceDiagram
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
NLU ->> DM: {"intent":"addtocart", "product":"milk", "qty":"1",  "context":{"utterances:[{"add milk to my shopping..."}]}}
DM ->> SS: {"action":"addtocart","product":"milk",  "qty":"1",  "context": {"userid":[linked], "utterances": [{...}]}}
SS ->> DM: {"response_code": {201}}
DM ->> TTS: {"response_text": "milk added to the shopping cart", "context":{...}}
TTS ->> C: Audio: "milk added to the shopping cart"

```
</details>    

<br>

#### Option 2
<details>    

```mermaid
sequenceDiagram
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
NLU ->> DM: {"intent":"addtocart", "product":"milk", "qty":"1","context":{"utterances:[{"add milk to my shopping..."}]}}
DM ->> SS: {"action":"addtocart", "product":"milk", "qty":"1", "context": {"userid":[linked],  "utterances": [{...}]}}
SS ->> DM: {"response_code": {201}}
DM ->> TTS: {"response_text": "milk added to the shopping cart", "context":{...}}
TTS ->> C: Audio: "milk added to the shopping cart"

```
</details>   

<br>


#### Option 3
<details>    



```mermaid
sequenceDiagram
participant C as Channel
participant SR as Speech Recognizer
participant TTS as Text To Speech
participant NLU as NLU Intent
participant DM as Dialog Manager
participant SM as Session Manager
participant VRS as OVN VRS
participant SS as SmallGrocery Server


C ->> SR: Audio: "hey bigtincan, add milk to my shopping cart at small grocery"
SR ->> NLU: Text: "hey bigtincan, add milk to my shopping cart at small grocery" 
NLU ->> SM: 
SM ->> VRS: {"lookup": "add milk to my shopping cart at small grocery"}
Note right of VRS: OPTION 3. VRS identifies the VRS in the utterance 
VRS ->> DM: {"vrs":"small grocery"<br>"nlu":"https://smallgrocery.com/dialogmanager/smallgrocery_bigtincan/"}
DM ->> NLU: {...}
NLU ->> DM: {"intent":"addtocart",  "product":"milk","qty":"1", "context":{"utterances:[{"add milk to my shopping..."}]}}
DM ->> SS: {"action":"addtocart", "product":"milk", "qty":"1", "context": {"userid":[linked], "utterances": [{...}]}}
SS ->> DM: {"response_code": {201}}
DM ->> TTS: {"response_text": "milk added to the shopping cart", "context":{...}}
TTS ->> C: Audio: "milk added to the shopping cart"

```
</details>   
<br>

## Decision
Based on the meeting's (03.04.2021) discussion, the quorum for the best part forward is option 1. The biggest reason is keeping the role of the VRS as straightforward as possible. The team acknowledged that the lower-level details solutions need to be done in partnership with Voice Assistant Platform.
  
<br>

## Consequences

The possible inconsistencies of identifying VRS entity in an utterance by different Voice Assistant Platform.
