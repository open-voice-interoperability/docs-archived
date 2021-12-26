## A
- **Artificial Intelligence (AI)** - also known as machine intelligence. A type of computer science focused on designing intelligent computer systems that exhibit characteristics of human behavior. AI is an academic discipline that has multiplesub-fields such as Natural Language Processing, Neural Networks, Robotics, Speech Processing, Machine Learning. Conversational AI - is the set of technologies to enable automated communication between computers and humans. This communication can be speech and text. Conversational AI recognizes speech and text, understands intent, decipher various languages, and responds where it mimics human conversation. In some cases, it is also known as Natural Language Processing. Utterance - spoken or typed phrases.
- **Automatic Speech Recognition** - also known as Speech-To-Text or computer speech recognition. It is an interdisciplinary subfield of computer science and computational linguistics that enables the recognition and translation of auditory utterance to text.

## B

## C
- **Channel** - an endpoint that enables conversation between Conversational Agents.  Examples include smart devices, mobile phones, web sites, mobile app, etc.  See Conversational Endpoint, below. 
- **Combo-Component** - a component that performs the functions normally associated with two or more components.  An example could be a component with functions of both automatic speech recognition and natural language processing that accepts audio input and produces a semantic structure as an output. 
- **Component Interoperability** - the ability, within a voice assistant, to replace one component with another from a different vendor.  For the purposes of the Open Voice Network, interoperable components may be recognized within the voice industry as open or proprietary as long as interoperability capabilities are met.
- **Context** - see "Conversational Context," below.  Information extracted from _n_ prior utterances of the current conversation.  This could include some or all of the following:  information that has been input, output, or inferred in Conversational Processors, and the information state of the Dialog Manager.  
- **Conversation** - a collaborative linguistic act between two or more conversational agents to achieve a user goal.
- **Conversational Access Point** - the means of carrying a signal to a conversational platform.  Users initiate and conduct conversationds through _access points_.  An access point can be physical or virtual.  Current examples of conversational access points iclude smartphones, smart speakers, personal compiuters, wearables, or microphone-enabled smart home hubs. Access points may be referred to elsewhere as a "device" or a "channel."  _In the interoperable world, conversational access points will enable connection to any conversational platform and agent_.
- **Conversational Agent** - A digital participant in a conversation.  Conversational agent is a common term utilized in the area of Dialogue System research and university level instruction; the term also used to describe a human participant in a conversation.  For clarity of reference, however, the Open Voice Network will use the term "user" to identify a human participant.  (See "user" below.)  Within the OVON Interoperability Initiative, a _conversational agent_ is perceived by users to be a single conversational actor, and with the ability to not only provide requested information, but _operate on behalf of the user_.  It uses the infrastructure of a conversational platform, and uses one or more conversational capabilities to hold conversations with the user, with continuity of knowledge and persona, and a name by which it can be addressed.  Enterprise conversational agents reach outside the corporate firewall to fulfill user intents.  _In the interoperable world, there will be both general-purpose and specific-purpose conversational agents.  Dialogs, data, context, and controls will be passed between agents according to standardized protocols. 
- **Conversational AI** - is the set of technologies to enable automated communication between computers and humans. This communication can be speech and text. Conversational AI recognizes speech and text, understands intent, decipher various languages, and responds where it mimics human conversation. In some cases, it is also known as Natural Language Processing.
- **Conversational Assistant** - is perceived by users to be a single conversation actor, and with the ability to provide requested information.  It uses the infrastructure of a conversational platform, and uses one or more conversational capabilities to hold conversationns with the user, with continuity of knowledge and persona and a name by which it can be addressed.  Enterprise conversational assistants can reach outside the corporate firewall to fulfill user intents. _In the interoperable world, there will be specific-purpose conversational assistants.  
- **Conversational Capability** - provides specific dialog functions that inform an agent.  Capabilities do not have a defined name or voice, nor the continuity of discourse context.  A capability may be as limited as a response from an IOT sensor ot an information fragment that supports an agent dialog; it may be as expansive as a partial or full dialog on behalf of an agent.  _In the interoperable world, conversational capabilities will exist independently from conversational agents and conversational assistants.
- **Conversational Context** - more research is required and underway; however, as of 2020.12.15, the Open Voice Network chose this definition: _information extracted from N prior utterances of the current conversation_.  This could include some or all of the following:  information that has been input, output, or inferred in Conversational Processors, and the information state of the Dialog Manager.  
- **Conversational Event** - A conversation event signals changes in the conversational that may be acted upon.  Such an event may be at the beginning or ending of a Conversational Session, completion of a Conversation Processor, decoding of Conversation Information, changes to the state of a Conversation Endpoint, or changes to the status of a Conversation Stream.  Any component with access to the system is allowed to generate a Conversation Event.
- **Conversational Facilitator** - coordinates communication between two or more Dialogue Systems and/or Processors during the course of one or more Sessions.  This allows dialogue Systems and associated Processors to collaborate regardless of technology being used.  Examples of Conversation Information include semantic, lexical, syntactic, and prosodic features. 
- **Conversational Information Layer** - represents an abstraction of a type of information in a Dialog System.  A layer may be a specific type of acoustic, linguistic, non-linguistic, or paralinguistic features.  Examples of layers would be Cepstral features, Phonemes, Intonation Boundaries, Words, Phrases, Turn Boundaries, Syllabic Stress, Discourse Move Tiype, and specific Semantic representation schemes.
- **Conversational Packet** - an input to or an output from a conversational processor.  Packets that have start and end times in sequence are a _conversational stream_.
- **Conversational Platform** - the combination of components that enables the operation and management of one or more conversational agents.  These components may include natural lanaguage understanding, natural language generation, and dialog management.   _In the interoperable world, creators of conversational agents will be able to choose from multiple conversational platform providers_.
- **Conversational Processors** - Conversation information is encoded and/or decoded by one or more Conversational Processors, also known as a Component.  Conversational Processors may also take as input the output from another Conversation Processor.   A Conversation Processor may generate Conversation Events and Conversation Streams. 
- **Conversational Session** - A particular conversation that consists of two or more Conversation Streams (see below) generated by two or more agents through one or more Conversational Endpoints.   Sessions may be persistent, but they will often have a start-point and an end-point in time determined by one of the Agents or some other external event.
- **Conversational Stream** - Each Conversational Endpoint generates one or more Conversation Streams based upon the capabilities of the Endpoint and the preferences of the Agent.  A Conversation Stream is associated with a particular Agent and may include any media type including text, audio, video, and application UI events.  


## D
- **Data** -- (per the Cambridge Dictionary): information, especially facts or numbers, collected to be examined and considered and used to help decision-making, or information in an electronic form that can be stored and used by a computer.  Context (see above) is a subset type of the data accessed and used by the voice assistant system. 
- **Dialog Manager (DM)** - handles the dynamic response of the conversation. It provides a more personalized response based on the action provided by the NLP to send back to the user.
- **Disambiguate** - when the conversational platform hypothesizes two or more possible resolutions to a user utterance, it may ask the user for additional clarification or choose between the various interpretations to decide the user's correct intention. 


## E
- **Entity** - is a part of the structured machine translation. It is a custom level data type and considered a concrete value to associate a word in a query. This is also known as annotations.
- **Explicit Invocation** - an invocation type where the user invokes the channel, and it is explicitly stating a direct command to accomplish a specific task. The direct authority is to communicate directly to a registered voice application.

## F
## G
## H
## I
- **Implicit Invocation** - an invocation type where the user invokes the channel, and use the most common words or indirectly saying the explicit Invocation.  I
- **Invocation** - is part of the construct of the user's utterance during a conversation with a channel. An invocation describes a specific function that the guest wants and expecting a particular response.
- **Intent** - is a part of the structured machine translation. It is the identified action that the machine interprets based on the user's query. This is also known as classifiers.
- **Intent Broker (IB)** - is responsible for providing the fulfillable intents available for a resolved VRS record (e.g. where resolved VRS record "BigGrocery", it’s fulfillable intents might be "order product, check order status, add to shopping list". These fulfillable intents can execute remotely on the DM or download locally on the device.
- 
## J
## K
## L
## M
## N
- **Natural Language Processing (NLP)** - a service and a branch of artificial intelligence that helps computers communicate with humans in their language and scales other language-related tasks. NLP helps structure highly complicated, unstructured human utterance and vice-versa. Natural Language Understanding is a subset of NLP that is responsible for understanding the meaning of the user's utterance and classifying it into proper intents.

## O
- **Organization** - a group of individuals brought together for a specific purpose, including the creation, transaction, and delivery of products or services.  Examples would include a for-profit business, a not-for-profit group, or government agency.  
## P
- **Platform** - The collection of components (the infrastructure) needed to execute a voice application.  Examples of platforms include the Amazon and Google platforms that execute voice applications.

## Q
- **Query** - user’s word requesting for specific function and expecting a particular response.

## R
## S
- **Speech-To-Text (STT)** - is converting the response from an audio to a text.

## T
- **Text-To-Speech (TTS)** - is a text converting to audio. Also known as Automatic Speech Recognition. It includes customized models to overcome common speech recognition barriers, such as unique vocabularies, speaking styles, or background noise.
- **Technical Resource** -  it can be a publisher/developer. It can be a representative of an entity or independent party. Their role is to create an actual listing of the voice application.

## U
- **Utterance** - spoken or typed phrases.
- **User** - a person who interacts with access points, and through access points, conversational assistants and agents.   

## V
- **Voice Application** - also known as skill, action, capsule or domain. This is the specific executable component that has association to multiple things such as invocation, collection of related intents and entities up to the configuration to your dialog manager.
- **Voice Application Interoperability** – a voice application involves another voice application.
- **Voice Assistant System** A system where a user (primarily) uses his/her voice to interact with an automated conversational assistant for information or to control devices. 
- **Voice Registry System (VRS)** - is a global entity type in OVN and considered one of the most central components. It is a registry system with similarities to Domain Name System (DNS), but for voice. VRS resolves requests to dialog management endpoints, NLP providers, and the dialog broker. VRS serves consistently regardless of the NLP.


## W
- **Wake Word** - a specific word that will catch the attention of the channel.

## X
## Y
## Z



