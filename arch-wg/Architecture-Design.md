# Architecture Design

## Abstract

The Open Voice Network is a non-profit industry association, operating as a Directed Fund of The Linux Foundation, and dedicated to the development of technical standards and ethical use guidelines. This is an essential step for a technology and an industry that is in its earliest days, and for which user and developer value falls far short of envisioned potential.

This document proposes a target architecture for how voice platforms and content in different proprietarty formats can interwork using the OVON specifications.

This document will:

- Describe the anticipated architecture for OVN standard messages

- Identify which OVON messages will be used where

It will not:

- Describe the actual messages themselves (except for examples)

- Mandate which transport protocols (HTTP, RTP etc. are used)

This document is intended to build on the [Technical Master Plan](https://github.com/open-voice-network/docs/blob/master/technical_masterplan.md). In the short term these two documents may contradict one another as we develop the ideas. Such conflicts should be resolved as they occur.

The terminology used in this document assumes the reader has familiarity with the aforementioned document.

## Design Principles

The OVON architecture seeks to establish standardized interfaces between dialog agents.  It does not seek to standardize the models used to describe linguistic components.

As such the OVON architecture celebrates diversity in the following areas:

- The diversity of underlying technology (i.e. speech recognition, language undersatanding and dialog modelling.)

- The diversity of endpoints 

- The diversity of conversational design paradigms 

- The diversity of labels used to represent semantic content 

The OVON architecture seeks to establish standards in the following areas:

- The method by which a spoken agent name can be used to find an associated agent.

- The way that control is handed between dialog agents

- The way that basic linguistic information is communicated in such hand-offs
  
  - Immediate linguistic context
  
  - Dialog history

- The way that dialog agents negotiate trust (to be discussed further)

## Current Generic Voice Assistant Model

### Typical Voice Assistant Architecture

![](images/current-generic-platform.png)

Typical voice assitant architecture

**!! Write this nicely !!**

Current voice assistants follow a host/delegate model where the host agent decides if delgegate agents are required or polls them to see if they want to provide responses.

Endpoints and platforms are currently closely coupled with proprietary (but often published) interfaces.  They handle wakewords, audio coding and streaming and graphical events and content.

Content is either native (and coded in a proprietary way) or external agents or dialog fragments (e.g. Skills, Actions) authored as web content with a published proprietary interface

Messages are session based with a request/response approach

#### Typical Request

Typical request types

- Can you fulfil this request? (*CanFulfilIntent*)

- Lauch with no context (*Launch*)

- Fulfil this request (*IntentRequest*)
  
  - Text of request
  
  - Semantics of request (intents and slots with pre-registered values)

- I don't need you any more (*SessionEnded*)

Sessions carry context that is shared between the host agent and the delegate agent.  Context includes things like:

- current agent identity (skill, action)

- speaker identities

- key/value pairs specific to the current task

- Information about the channel (does it have graphics etc?))
  
  ![](images/typical-alexa-request.png)

**Visualization of typical Alexa Intent Request**

#### Typical Response

Typical responses contain

- Say this next (and if they dont say anyting say this)

- Display this

- I'm finished after this

- Do this (audio, video, real-world connections )

![]()

**Vizualization of a typical response**

## Proposed Ovon Architecture

## Delegation and Takeback with Context

![](images/delgation-and-takeback-with-content.png)

**!!!!Describe**

#### Session Control

Examples of session messages (Align with Jim's work)

- Do you want to take control?

- I'm giving you control

- I'm taking back control

### Context

Transfer of control will occur with context.

Context will be shared between the host/delegate (mechanism to be agreed).

This will have contain three levels of information in a defined OVON format

- Mandatory   (Could be minimal or none)

- Optional
  
  - Dialog text
  
  - Dialog semantics

- Proprietary
  
  - Custom data

### Interaction Payload

For the duration of the session a link will be established betwen the host platform and the delegate.

This will support the transfer of dialog events between the two platforms.  Dialog events will be in a standard format (e.g. EMMA) and have different levels:

- Mandatory  (Either:)
  
  - - (level 0) Audio (To be discussed this may be a different protocol)
    
    - (level 1) Text
    
    - (level 2) Semantics

- Optional
  
  - Optional content in OVON agreed formats (not in MVP)
    
    - referral text (a natural language referral from one agent to the other)
    
    - pronunciations, tone of voice,
    
    - visual content 

- Proprietary
  
  - Event data in formats known only to the two communicating agents for this task)

- ![](images/example-payload.png)

**Example of payload contents**

### Add VRS

![](images/arch-with-vrs.png)

Platforms will find each other via known web references OR they can use VRS to resolve a name into a web location

### Add .well-known capabilities

**!!!(Consider adopting OVAL approach for this)**

Voice platforms will publish their capabilities using the IFTTT /well-known mechanism using the .well-known mechanism.

This will publish:

- Supported levels of interaction (level 0,1,2)

- Supported capabilities (discoverablility .. we have never discussed this properly)

### With Permissions

![](images/arch-with-permissions.png)

**!!!This section is reserved to describe how we will support permission requests.**

# Interaction Examples

Some ladder diagrams to show how this might all work.  

## Launch example

'Bigtincan open Bigrocery'

## Launch with Intent

'Bigtincan ask Bigrocery how much apples cost'

## Chained control

Shop for something and then the shopping app uses a different payment app

## Can Fulfil Intent

'Bigtincan how bright is Jupiter in the night sky?'




