__this document has also been proposed (via pull request 2020.11.18) as an addition to the Master Plan.__

### OPEN VOICE NETWORK TECHNICAL COMMITTEE

\## Architecture Work Group

 

\# Problems to be solved

**Complexity.** Voice agents are complex, comprising of several diverse technologies that need to be integrated into a single, cohesive system. One of the basic strategies of software development—modularization—manages complexity by partitioning the overall system into modules and solving each them independently. We will identify and define several software components that each contains a collection of related functionalities. For example, a speech recognition component will contain functions that (1) break down the audio of someone speaking into individual sounds, (2) analyzing each sound, using algorithms to find the most probable word fit in that language and (3) transcribing those sounds into text. The complexity of speech recognition are isolated within the speech recognition component and are hidden to the rest of the system. 

**Inconsistent terminology** Different terms for the same concept lead to chaos and confusion. We will involve the speech community in defining common terms and provide education material promoting those terms (on our web page, news letters, social media and conference presentations)

**Lack of overall structure** While each voice agent may have a different architecture, developers can agree of some of the common components and can be combined to create a voice agent. Much like how lego building blocks can be reused to construct many different structures, common software components can be combined to create new and creative voice agents. We will identify a collection of common software components for creating voice agents. Example software components include Automatic Speech Recognition (ASR), Text to Speech Synthesis (TTS), human user identification based on voice prints (Speaker ID), etc.

**Reusability.** It is difficult to reuse pieces of functionality in a monolith structure.  Each component should have a standard format for its input and output so it can be easily reused by combining it with other components. We will define the formats for input and output of each component (but not the algorithms that convert the input into the output). For example, the ASR component will accept audio files as input and produce text as output.

**Extensibility.** It is difficult to incorporate new technology and functionality into monolithic systems. However, a component’s existing algorithms can be upgraded with superior algorithms without changing the format of its input and output. For example, a speech recognition component algorithm based on the hidden Markov model can be replaced by a neural network model. 

**Interoperability** Because voice systems are made up of components with standardized input and output streams, an output stream from a component in one voice system can be routed to the input stream in a component in a second voice system, thus enabling the two voice systems to interoperate. 

**PROBLEM SUMMARY.** Currently the world of voice agents is like the Wild West—chaotic and unfocused. We hope to introduce some structure in the form of software components with well-defined inputs and outputs yet open in the sense that their internal algorithms can be improved and extended. Technology providers can differentiate themselves by competing to provide algorithms that work faster and more accurately than competing components.

\# Draft Framework

We recognize that this is a big task, so we will proceed in four consider four buckets of components inspired by the advent and progress of automotive transportation. 

\- **Macadam Road Bucket** (Named after the 18th century Scottish engineer who invented the hard-surface, reliable road.) 

 Provide the basic infrastructure needed by voice agents. Example components include ASR (convert speech to text) and TTS (convert text to speech). 

\- **Model T Bucket** (Named after the Model T, a practical, affordable transportation for the common man which quickly became prized for its low cost, durability, versatility, and ease of maintenance.) 

This bucket provides core functionality and OVN unique value. Example components include Locator Service (registry for voice names) and Fulfillment Broker (selects apps to fulfill a user request)

\- **‘57 Chevy bucket** (Named after the '57 Chevy, a popular and fun car that was easy and cheap to work on.)

This bucket provides enhanced functionality and safety. Example components include Human speaker ID and Natural Language Result Generation of text for results and warning messages.

\- **Tesla Bucket** (Named after Tesla that demonstrates the electric vehicles can be better, quicker and more fun to drive than gasoline cars.)

This phase provides new technologies and capabilities. Example components include emotion detection and plan generation.

\# Remit of the Architecture Work Group:

Identify, define, and prioritize common voice assistant components for potential standardization. TECH COM REPORT 20 NOVEMBER. 

\# Business perspective:

Identify re-usable (interoperable) components that accelerate the construction of new and innovative speech applications.

The components in each for the four phases follows:

 

 

\## Component Framework 

\# Macadam Road Bucket: “Foundational” (Core functionality)

\1. VRS Locator Service

Purpose 1: Maintain links to speech agents

Input: pronunciation of speech agent name

Output: link to speech agent

Purpose 2: Register speech agent name

Input: pronunciation of speech agent name & information

Output: Success or failure

\1. Name: Fulfillment Broker

Purpose: Select backend app for processing request

Input: request

Output: fulfillment info 

Note: previously called Dialog Broker

\1. Context Manager

Purpose: Maintains history and context of the conversation

Input: TBD

Output: TBD

 

\# Ford Model T Bucket:“Foundational” (Core functionality + OVN unique value)

 

\1. ASR 

Purpose: Convert speech to text 

Input: audio

Output: text

May interact with: Context Manager

May interact with: Knowledge Manager

\1. NLU

Purpose: extract meaning from text

Input: text

Output: semantic representation of text

Note 1: known as semantic interpretation in VoiceXML

Note 2: ASR + NLU often combined into a combo component 

May interact with: Context Manager

May interact with: Knowledge Manager

\1. Dialog Manager

Purpose: respond to request

Input: semantic interpretation of text

May interact with: Context Manager

May interact with: Knowledge Manager

Interacts with: Locator Service (VRS) to obtain link to voice agent

Interacts with: Fulfillment (Dialog) Broker to obtain links to backend apps

Interacts with: backend apps to obtain fulfillment

Interacts with: NLG Generator to formulate text response

\1. TTS

Purpose: Convert text to speech 

Input: text (possibly with hints for pronunciation

Output: audio

 

 

\# ’57 Chevy Bucket:“Desirable: enhanced functionality, safety, UX design”

\1. Human speaker identification 

Purpose: Identify human speaker by using voice prints

Input: audio

Output: speaker identification

Note: This component is frequently combined with ASR to form a combo-component

Note: other components including ARS, NLU, Dialog manager, NLG may access the contents of this component. The persistence of this component it TBD

\1. Knowledge Manager 

Purpose: maintains real world knowledge and common knowledge in the form of ontologies and other data structures TBD

Input: TBD

Output: TBD

Note: other components including ARS, NLU, Dialog manager, NLG may access the contents of this component. 

Note: This is a new component suggested by Jonathan but not discussed on 10/21

\2. NLG result generator

Purpose: Generate text and error/warning 

Input: semantic information

Output: text

Note: may interact with personalization information (part of the user session manager) to personalize messages to the user

Note: may be extended to support language translation

\1. Access Control Guard

Purpose: controls access to data and functions

Input: access control constraints (Boolean expression involving the functions and parameters of an API to an object (such as a backend app, a voice agent, etc.), and system parameters (date, time, etc.)

Output: permission granted (or not) to access data and/or functions

Note: inspired by the Almond access control mechanism

 

\1. User Session Manager

Purpose Establish and maintain environment parameters (national language preference, recording options, wake-up words, personal NLP and other profiles information TBD.

Input TBD

Output TBD

Note: ON 10/21 Dan suggested “profile” which fits in this component

**Tesla Bucket: “Visionary: redefinition and technology advancement”**

\1. Emotion detection 

Purpose: extract a human user’s emotion from their voice 

Input: voice

Output: one or more emotions with a rating for each emotion indicating its strength

Note: There is a second technology for emotion: analysis of wording and phrasing of text. This may be performed in the NLU component.

 

\2. Plan Generator

Purpose: Convert a high level request into a plan (a sequence of invocations of agents needed to complete the request

Input: high-level user request

Output: Plan involving multiple agents

Note: there are several strategies for developing plans. Venders will differentiate themselves by implementing difference strategies for different situations. 

Result Generator on steroids

Purpose: extend the NGL result generator to include multi-modal, multi-media conversations

Input: semantic information and a list of the capabilities of the user environment (speakers, sensors, cameras, scanners, etc.)

Output: Mulltimoal user experience
