
# 2. vrs-type

  

Date: 2021-02-04

  

## Status

  

In Progress

  

Supercedes [1. Record architecture decisions](0001-record-architecture-decisions.md)

  

## Context

The Voice Assistance Platform's job is to identify if the call is implicit or an explicit utterance. If explicit, then it will engage and call VRS.
  

**Issue 1:** Identify the integration role of the Voice Assistance Platform (VAP) component in calling the VRS. When the VAP will summon the VRS.

**Issue 2:** what are the parameters expected for VRS to receive?

> utterance:
> "hey bigtincan, please add milk to my cart at biggrocery"

>     intent: addtocart
>     quantity: 1
>     item: milk



## Options

  **Issue 1:**
| Options | Pros | Cons |
|--|--|--|
| Option 1. Create a VRS entity and VRS type in NLU. | - easier for slot to identify. - align in the role of NLU  | - risk of inconsistency in understanding VRS type  |
| Option 2. Dialog Manager identifies when utterance is explicit |  | - creating a separation of understanding the utterance |
| Option 3. VRS will decide the vrs type in the utterance | - consistent logic for vrs identification across different VRS  | - VRS will have to receive the whole utterance.  |

  **Issue 2:**
| Options | Pros | Cons |
|--|--|--|
|  |  |  |
|  |  |  |


  

## Decision

  

The change that we're proposing or have agreed to implement.

  

## Consequences

  

What becomes easier or more difficult to do and any risks introduced by the change that will need to be mitigated.