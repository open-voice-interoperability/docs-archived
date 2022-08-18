2022.08.12 

# Interoperability of Conversational Assistants 
# A New Approach

The Open Voice Network
Architecture Work Group of the Technical Committee
12 August 2022


# ABSTRACT

This is a publication of the Open Voice Network (OVON, www.openvoicenetwork.org), a non-profit industry association operating as an open-source community of the Linux Foundation.  It asserts that, to realize the full economic and societal potential of conversational assistance, voice agents must not only mediate human-to-agent conversations – e.g., host the conversation and obtain relevant information to fulfill user intents – but also delegate conversations to other agents, and in doing so, pass textual, acoustic and contextual data, as well as privacy and security controls.  

To meet this vision, the Open Voice Network proposes an approach to interoperability between conversational assistants  – specifically, the sharing of multi-layered dialogs between assistants and agents of differing infrastructures through the standardization of communication protocols.   

This paper also suggests areas for further research, as well as next steps for the proposal and testing of communication protocols that may be built from existing technologies and broadly-accepted standards.  

At the core of this work is this firm belief:  we are in the early days of conversational assistance, and the future will be one of stunning diversity --  a multiplicity of voice-enabled user end points, content and infrastructure providers, voice-enabled destinations (measured, perhaps, in the billions), industry ecosystems such as transportation and smart homes, and organizational/enterprise value propositions.  

This paper is the creation of  the Architecture Work Group of the Technical Committee of the Open Voice Network. 

## TABLE OF CONTENTS
### SECTION ONE: INTRODUCTION 
1.0 Introduction	
1.1 Intended Readership	
1.2 Purpose of this White Paper	
1.3 The Open Voice Network and Interoperability of Conversational Assistance: Why and What	
1.4 Going Forward: Your Participation	
1.5 A User’s Vision: An Interoperable World for Today and Tomorrow	
1.6 Architectural Aspirations	
1.7 Boundaries	
1.8 Interoperability Defined for Conversational Assistance	
1.9 Core Requirements for Interoperability of Conversational Assistants	
1.10 Interoperability Intentions of the Open Voice Network	

### SECTION TWO:  A FOUNDATION FOR ANALYSIS -- THE TECHNOLOGY OF CONVERSATIONAL ASSISTANCE	
2.0 Introduction   
2.1 Conversational AI and Voice	
2.2 Conversational Assistants and Platforms	
2.2.1 Conversational Assistants and Agents	
2.3 Platforms and Content: Existing Standards	
2.4 Conversational Architecture	

### SECTION THREE:  AN APPROACH TO VOICE ASSISTANCE INTEROPERABILITY	
3.0 Introduction	
3.1 Modeling Interoperability on How People Communicate	
3.2 Interoperability:  Mediation and Delegation	
3.3 From the Human Model to Standards: OVON Interoperability Objectives	
3.4 Architectural Patterns Under Investigation	
3.4.1 Dialog Delegation and Give-Back	
3.4.2  Delegation Request and Conversation Context	
3.4.3 Dialog Interaction PayLoad	
3.4.4  Dialog Component Interfaces	
3.4.4.1 An Illustrated Example: Pat Goes Shopping	
3.4.5 Discovery and Location	
3.4.6 Sharing and Protection of Data	

### SECTION FOUR:  LESSONS  FROM OTHER INTEROPERABILITY INITIATIVES	
4.0 Introduction	
4.1 Amazon Voice Interoperability Initiative (VII)	
4.2 The Stanford Open Voice Assistant Laboratory (OVAL) Model	

### SECTION FIVE: FURTHER STUDY AND NEXT STEPS	

### SECTION SIX:  OPERATIVE VOCABULARY	

### SECTION SEVEN:  ABOUT THE OPEN VOICE NETWORK	
About The Linux Foundation	
Acknowledgements	

### SECTION EIGHT : REFERENCE LIST	

### WORK-IN-PROGRESS APPENDIX	


## SECTION ONE:  RATIONALE, SCOPE, AND CORE DEFINITIONS

### 1.0  Introduction

This section speaks to the Open Voice Network’s reasons for pursuing interoperability of conversational assistants, the boundaries of our work, and a 1.0 definition of conversational assistant interoperability.

### 1.1 Intended Readership

This paper is being  published for public evaluation and criticism on 12 August 2022. It seeks to address three global audiences, each with a stake in the future of voice:

●	Enterprise content creators and communicators (business-to-consumer and business-to-business);
●	Stakeholders and decision makers within the voice technology industry, including potential architectural partners; 
●	Current and prospective participants and sponsors of the Open Voice Network.  
 
### 1.2. Purpose of this White Paper 
This White Paper seeks to:
●	Identify the architectural elements required  to facilitate interoperability of conversational assistants;
●	Prioritize these elements for standardization by the OVON Architecture Work Group; 
●	Foster discussion with the constituents noted above in section 1.1.  
In this White Paper, we seek to remain neutral with respect to competing architectural directions, and to reveal the underlying concepts/issues that exist regardless of architectural choice. 
This document is intended to be read alongside the Open Voice Network Technical Master Plan.   In the short term these two documents may contradict one another as ideas are developed and tested. Such conflicts will be resolved as they emerge.
This paper  replaces a previous document entitled ‘Architecture Design.’

### 1.3 The Open Voice Network and Interoperability of Conversational Assistance: Why and What

The Open Voice Network (www.openvoicenetwork.org)  is an open-source community of the Linux Foundation dedicated to the development of the standards and usage guidelines for the emerging world of voice assistance. 

It enjoys the regular participation of more than 200 volunteers from 13 nations and 5 continents.  The OVON community includes participants from leading voice platforms and infrastructure providers;  large enterprises that use voice technologies in customer service and operations (from industries such as retail, healthcare, telecommunications, and financial services); marketing and consulting firms; and more than 40 independent voice development and services companies. 

As a technology-neutral, nonprofit organization, the Open Voice Network occupies a unique and strategic position within the voice technology industry.  Our sponsors and participants witness a growing diversity of underlying voice technology (speech recognition, language understanding, dialog modeling), conversational design paradigms, labels to represent semantic content, and endpoints (from smart speakers to voice-enabled web pages and immersive games).  They also see the rapid growth and evolution of voice value propositions, especially for organizations and across vertical industries. 

This diversity points to a significant total available market (TAM) for conversational AI as both an interface and a source for data-fueled insights.   Looming before us – as first envisioned by Dr. Monica Lam of Stanford University – is an interoperable Worldwide Voice Web (WWVW) , where the spoken word offers an open, standards-based interface to billions of voice-enabled media, enterprise, website, transportation, smart IOT environment, and metaverse destinations. 

Given the economic and societal value that will be created by an interoperable Worldwide Voice Web, the Open Voice Network commissioned the Architecture Work Group of its Technical Committee to research and recommend architectural options for open, standards-based  interoperability for conversational assistance.  

Using a technologically and architecturally-neutral eye, the Architecture Work Group reviews existing technology standards and existing and proposed voice architectures and messaging protocols.   The Work Group ascribes to the Harvard Business Review’s  “Jobs to Be Done”  methodology, and examines in detail the current and future needs of four key voice constituents: 

●      Consumers of voice-enabled experiences
●      Enterprise content providers
●      Technical innovators of dialog systems
●      Voice system infrastructure providers. 

Through these efforts, the work group is identifying  the opportunities and challenges of conversational assistant interoperability, and a series of foundational concepts.  

In short, the Open Voice Network 

*	Believes that conversational assistance will realize its economic and societal value when it is interoperable, like telephony or the worldwide web (WWW).   
*	Sees in today’s rapidly growing enterprise investment  in conversational assistance the seeds of a rich ecosystem of independent, purpose- and brand-specific voice assistants and agents, an ecosystem that will bring desired content and experiences to the users of general-purpose, proprietary conversational agents. 
*	Recommends the development and industry-wide adoption of standardized communication protocols between conversational assistants operating on different platforms. 
*	Asserts that conversational assistants must both mediate dialogs (e.g., act as a host, and acquire desired information to fulfill the user intent) and delegate dialogs (e.g., act as an initiator of communication, and bridge to other assistants so that the user intent can be fulfilled.)  In addition, conversational assistants must also be identified and authenticated to serve as a destination of a delegating assistant or agent.
*	Envisions a model of conversational assistance interoperability in which autonomous assistants and agents collaborate to achieve a goal together. In so doing, they will use standardized ways to share information with each other and operate at various, negotiated levels of trust and information sharing.   This will lead to the development, test, and proposal of standards for:
  * The way in which a spoken agent name can be used to find an associated agent;
  * the way in which basic linguistic information is shared between dialog agents;
  * The way in which immediate linguistic context and history is shared between dialog agents;
  * The way in which control is handed between dialog agents;
  * The way in which dialog agents negotiate trust. 

In addition, the Open Voice Network
*	Will neither develop nor recommend the standardization of platform components or the format of content used to figure these components.

We do not believe that a standard methodology for expressing and describing conversational interaction is possible or desirable.  Attempts to describe how conversations can or should be modeled will quickly become outdated as conversational interaction innovates and evolves.

In the coming months, the Open Voice Network will develop, test, demonstrate, and propose to existing standards bodies a set of standardized communication protocols that will enable agent-to-agent voice interoperability. 


### 1.4  Going Forward: Your Participation

In keeping with the practices of the Linux Foundation, the Open Voice Network works in an open, communal manner.  We seek contributions from every corner and region of the conversational AI ecosystem.

Readers of this paper are invited to

*	Propose corrections and additions to this paper through the Open Voice Network GitHub repository (https://github.com/open-voice-network) or in the White Papers section of the Open Voice Network website.  (https://openvoicenetwork.org/white_papers).    We are especially interested in criticism and comment regarding
  *	Concepts that are not clearly defined
  *	Requirements that you feel are missing
  *	Requirements that you feel are unnecessary
  *	Contribute usage scenarios (similar to those in the paper) that challenge the concepts within this paper, and perhaps point us to new or revised requirements for the interoperability of conversational assistance. 

You are also welcome to join the weekly interoperability development meetings of Architecture Work Group of the Open Voice Network’s Technical Committee.   One-hour sessions are scheduled Tuesdays at 17:00 CET, 11:00 Eastern, and 08:00 Pacific.  Conferencing details can be found at https://openvoicenetwork.org/calendar.

### 1.5   A User’s Vision: An Interoperable World for Today and Tomorrow


### 1.6. Architectural Aspirations
The following  architectural aspirations guide our thinking and our actions:
1.	We recognize that the material and financial resources required to create, operate, and maintain conversational AI and voice assistant systems are significant. Our architectural direction will allow for sharing the cost of those resources, but we will not ourselves specify how that needs to occur.
2.	There are several competing architectures for control interfaces between conversational AI platforms, assistants, and agents. OVON will evaluate architectures, produce recommendations, and attempt to remain neutral with respect to the choice until and unless making a choice becomes required for completing our specifications.
3.	Each of the dominant proprietary platforms within the existing voice market has an installed base of platform-specific applications.  At the same time an ecosystem of third-party voice content creators has emerged outside the proprietary platforms.  To maximize the value of our work and speed global adoption, we will seek to establish a platform-neutral approach to interoperability – while adopting (as noted above) common concepts and ideas. 
4.	The lifespan of a standard is much longer than the lifespan of the physical components subject to the standard. The specifications and guidance which we will produce may be informed by existing design patterns but must not be limited to those patterns.
5.	In the immediate, we aspire to:
  a.	Outline the different architectural approaches that could support interoperability.
  b.	Outline the advantages and disadvantages for each with respect to the OVON constituents and the Jobs to Be Done. 
  c.	Recognize that several viable architectural approaches to interoperability may coexist and that OVON needs to remain responsive to the directions taken by the market.
  d.	Identify platform-neutral standardization that will enable both the new emerging third-party ecosystem and the applications resident on proprietary voice platforms. 

### 1.7 Boundaries 
The Open Voice Network defines the boundaries of this work using the “Jobs to Be Done”  approach, singling out  four groups of individuals for whom interoperability will create incremental and sustainable value. Identification and clarification of the needs and desired experiences of each group allows OVON  to  define the work required from the Open Voice Network to fulfill those needs and desires.
Though Open Voice Network-delivered standards will benefit the voice industry at large, our work suggests that four distinct groups of individuals are central to the question of interoperability: (1) consumers of enterprise content who wish to use voice enabled technologies,(2) enterprises who provide content and wish to provide voice enabled experiences, (3) technical innovators of dialog systems who wish to create the systems for the enterprises to use, and (4) voice systems infrastructure providers who wish to create and pursue commercial opportunities within a free and open environment.  
 
Figure 1.7  Benefactors of  conversational assistant interoperability; the value ecosystem

Together, these groups constitute a tiered ecosystem that will flourish in a world of conversational assistant interoperability.
Consumers of Voice Enabled Experiences are at the top of the tier. These are the end consumers of voice enabled experiences.  OVON-developed standards will enable them to engage in voice experiences in web environments that currently do not provide voice experiences. The  “Jobs to be Done” that we are supporting for this group include the following tasks:
* Help me continue my voice task as I switch voice devices (home, phone, auto)
*	Help me avoid restricted access to data in all internet-connected, voice-enabled systems
*	Help me opt-out of data protection when it makes sense.
*	Help me avoid restrictions on vendor choice.
Enterprise Content Providers rank next. These are the businesses and organizations that offer applications on proprietary, general-purpose consumer platforms, or do not deliver voice experiences to their customers outside the organizational security firewall.  Together, enterprise content providers represent a significant third-party content and voice-centric services ecosystem.  “Jobs to be Done” for enterprise content providers are: 
  *	Help me grant all potential constituents free and unfettered access regardless of the constituent's "home" voice platform
  *	Help me ensure that all my potential constituents can freely and directly connect with my voice applications and services, regardless of  home platform
  *	Help me enable the privacy of all dialog data (text, acoustic, semantic) shared between my applications and services and my constituent when explicitly requested to do so (however that may be)
  *	Help me avoid building separate applications and services in order to use all global voice platforms and web / IoT / metaverse-based voice-based destinations.

Technical Innovators of Dialogue Systems are the technology-centric and consulting organizations that will create customer service, web, or operational environments for enterprise content providers.  These innovators develop the different technology solutions that work together to enable voice experiences. They will build the pieces of the modularized future we envision. “Jobs to be Done” for technical innovators include:  
  *	Help me avoid creating new voice-based core business processes for transactions
  *	Help me avoid creating new/redundant messaging protocols for sharing of dialog, data, and controls between platforms, agents, and assistants
  * Help me give customers the choice to protect their voice data
  *	Help me secure my customer's voice data
  *	Help me avoid creating new specifications /processes for voice authentication, attestation, and authorization
  *	Help me get to content and consumers without dependence upon Big Tech proprietary platforms
Of note:  while there are “Jobs to Done” for each of the constituent groups – and each plays an important role in an interoperable ecosystem – all will rely on the work of the Technical Innovators.   These individuals will use Open Voice Network standards to do their work; the OVON expects to provide significant support to assist them in accomplishing their jobs to be done, each of which require a specific experience.  These are the experiences we will create for the technical innovators.

Technical Innovator Jobs to Be Done	Corresponding Technical Innovator Experiences
  * Help me avoid creating new voice-based core business processes for transactions	Implement OVON standard protocols and specifications to enable business processes for interaction
  * Help me avoid creating new/redundant messaging protocols for sharing of dialog, data, and controls between platforms, agents, and assistants	Select and plug and play messaging protocols
  * Help me give customers the choice to protect their voice data	My customer elects to protect their voice data
  * Help me secure my customer's voice data	I match security level per customer's level of data protection
  * Help me avoid creating new specifications /processes for voice authentication, attestation, and authorization	I learn OVON Standards so that I know how it should work
  * Help me get to content and consumers without relying on the proprietary Big Tech	I know where to go and what to do to manage proprietary Big Tech platforms

Voice Systems Infrastructure Providers provide technologies used by content creators and technical innovators to deliver voice-based content and services to consumers of voice-based experiences.  In an open, standards-based, interoperable world, they will enable a stable voice ecosystem. Technical innovators will rely on these open infrastructure offerings to create voice technology solutions that will be used by enterprise content providers. “Jobs to be Done”  that we are supporting for voice system infrastructure providers are the following: 
  *	Help me create an accessible environment
  *	Help me create an environment where seamless interaction is commonplace
  *	Help me create an environment where scalability is empowered
  	
### 1.8.  Interoperability Defined for Conversational Assistance

At the most basic level, interoperability means “the ability of two or more systems or components to exchange information and to use the information that has been exchanged.”    The OVON  adapts this definition to the conversational assistance ecosystem as follows: 
Interoperability is 1) the ability of conversational assistants of diverse parentage to collaborate seamlessly to achieve a goal together, using standard ways to share information with each other, operating at various levels of trust and information sharing, and operating independently of the physical devices being used; and 2) the ability of conversational AI-driven content, agents, and service providers to reach target audiences across the diversity of platforms, general purpose agents, and physical access devices (endpoints). 
Conversational assistants can be fully or partially interoperable.   

### 1.9 Core Requirements for Interoperability of Conversational Assistants

Conversational assistants must:
  *	Deliver both mediated and delegated communication. 
  *	In mediated assistance, the user interacts with a single conversational assistant.  The mediating conversational assistant hosts the conversation; it never cedes control of the conversation.  To fulfill user intent, the mediating assistant may obtain information from third party sources, or introduce an application resident on its platform.  
  *	The content destinations of mediated assistance are generally limited to the data sources or applications resident on the host assistant’s platform. 
  *	In delegated assistance, the user interacts with one or more independent conversational assistants using standardized messaging protocols.  The delegating conversational assistant initiates the conversation; it passes control to assistant (or assistants) desired by the user, or best suited to fulfill the user’s intent.   
  *	The content destinations of delegated assistance are limitless -- bound only by the adoption of standardized protocols.
  *	Serve three roles to fulfill user intents:  as  1)  a host of applications that mediates content to fulfill user intent, 2) an initiator of a connected dialogue that delegates fulfillment of intent to one or more independent agents, or 3) a destination that is delegated to, and as such, assists the initiator in fulfilling user intent.

 
Figure 1.9: Core Requirements for Conversational Assistants

As an initiator and as a destination, an agent must offer six types of interoperability, as shown in the grid below.    
Type of Interoperability	Use	Example	Benefit
Share dialog fragments
Dialog fragment = portion of a dialog pattern, a piece of interactive fragment, a chunk of interaction specification	Conversational agent uses fragments from one or more other conversational agents  to achieve a dialog goal – user thinks is talking with one agent 	A delivery service voice agent (with Pat’s consent) uses the location collection dialog fragment from a  payment conversational agent to collect Pat’s address information.  The fragment may also be identified so it can be reused. 
	Application developers save time by reusing dialog fragments from other conversational agents.
Share personal  data
Personal data = information which the user wants to maintain across several sessions.	A conversational agent specifies how data is shared with another conversational agent.	The value in the Amount Due slot in the Shop conversational assistant is copied into the Payment Amount slot in the Payperson conversational assistant.	User controls how personal data can be shared with other conversational assistants, saving users from reentering the data value.
Share conversational context
Conversational context =  information which is shared between a user and a conversational agent over a (tbd) period of time.   With the user’s permission, conversational context may be shared with other conversational agents. 	Relevant context (of the user, of the dialog)  established on one agent is shared with another voice agent. 
	The context (history) of actions in the Shop voice assistant is shared with the Payperson voice assistant.  Thus the Payperson voice agent is aware of information collected and generated by the Shop voice assistant.
	Enables conversational continuity
conversational continuity =  the principle of making sure that all details in one voice assistant  are consistent with the details in another voice assistant

Transfer control
Transfer control = determine which conversational agent is invoked and becomes active.  Determination of which agent has “the floor,” which agent has the  permission to speak.	Transfer control from one conversational agent to another	While shopping for groceries through a conversational assistant, Pat switches to the Payperson voice assistant to pay for the groceries. 	Matches the natural thought processes of human users.  
Share components (This is an aspirational goal)

Components =  components of a conversational agent, including but not limited to ASR, TTS, NLP, NLG.	The developer specifies which components are used within a dialog.	A voice developer may desire to use  sophisticated natural language processing rather than a simple natural language processor provided by the conversational agent being used. 
Other examples of component sharing include (a) using different ASRs for speakers of American English and British English, (b) performing natural language translation between national languages such as English/German or English/Italian, (c) providing access to algorithms that perform explicit query or implicit query  (a.k.a. voice search).
	Developers can develop custom agents through the use of standards-based, best-of-breed technologies. 
Share endpoints
Endpoint = hardware or software through which the user speak and listens to conversational agents	User controls where input may come from or output may be directed to.	The user may begin a request from a device with a public microphone/speaker and later request to continue with a private device.
The user may ask for output to be directed to a different conversational agent or a different device, such as a printer, or may ask for input to come from some shared data.	User can access any conversational voice agent using any endpoint

### 1.10  Interoperability Intentions of the Open Voice Network
The Open Voice Network seeks to  enable mediated and delegated communication by conversational agents within an ecosystem of general purpose, consumer-centric voice agents, and independent, purpose- and brand-specific voice agents and assistants. To make this happen, OVON will l develop messaging protocols and a destination management and services system, that will standardize the following: 
  * The way in which a spoken agent name can be used to find an associated agent;
  *	The way in which basic linguistic information is shared between dialog agents;
  *	The way in which immediate linguistic context and history is shared between dialog agents;
  *	The way in which control is handed between dialog agents;
  *	The way in which dialog agents negotiate trust. 


## SECTION TWO:  A FOUNDATION FOR ANALYSIS -- THE TECHNOLOGY OF CONVERSATIONAL ASSISTANCE

### 2.0  Introduction

The Open Voice Network grounds its research into conversational assistant interoperability in current operative definitions of conversational Artificial Intelligence, as well as the normative components and architecture of contemporary voice assistance.  In this section, intended for both subject matter expert and lay audiences, we share our understanding of those components and architectures.  

### 2.1  Conversational AI and Voice

Voice assistance is but one form of conversational Artificial Intelligence, or conversational AI.
Citing Interaction.com (2022):  “Conversational AI is the set of technologies behind automated messaging and speech-enabled applications that offer human-like interactions between computers and humans.

“Conversational AI can communicate like a human by recognizing speech and text, understanding intent, deciphering different languages, and responding in a way that mimics human conversation.” 

Conversational AI solutions can be offered through  text and voice modalities.  Voice solutions – referred here broadly as voice assistance – can be delivered as an audio-only interface, or one in which voice assistance works in a complementary way with screen-based information.  The latter is often described as multi-modal voice assistance.  

This paper speaks primarily to the sharing of voice-based elements within a dialog.  However, the Open Voice Network recognizes clearly the importance of multi-modal voice assistance (especially in an enterprise context) and will extend future editions of this work to multi-modal interoperability. 

### 2.2. Conversational Assistants and Platforms

The Open Voice Network draws a clear distinction between conversational assistants and agents and conversational platforms.
Conversational assistants function as conversational user interfaces. They engage in conversation and are identifiable by users as conversational actors. A conversational assistant typically has an assigned identity, an identifiable voice, and/or a name: for instance, Alexa, Siri, or Magenta. The user recognizes a given conversational assistant as a singular entity, and refers to that assistant with a pronoun (he, she, it, they) or by an assigned name. The conversational assistant may also refer to itself using a name or a pronoun.   
Conversational assistants often  respond to queries in the form of web searches. The response typically describes how the assistant locates the delivered content.  For instance, one might ask, “Assistant, what is the weather like in Manhattan today?” To which the assistant responds, “Okay, here is something I found on weather.com…” 
A conversational platform is the software to which the assistant connects, and that interprets the input from the user. The assistant responds through an endpoint, which is typically a piece of hardware, such as a smart home display, a television remote control, an automobile smart dashboard, a smartphone, or a smart speaker.  
There are endpoints and platforms currently associated with proprietary  interfaces,  such as Amazon Alexa or Google Assistant. They handle wake words (“Hey, Google…!”),  audio coding and streaming, and graphical events and content.
If a given platform provides generic access to content, it may have a host voice assistant, and give the user the option to ask for a delegate assistant. In other words, the host can provide a gateway to delegate content.
With the exception of assistants written in the VoiceXML standard , delegate assistants are typically authored for a given platform by third party companies.
Examples of End Point-Platform-Assistant Pairings
End Point	Platform	Host Assistant
Echo Dot	Amazon	Alexa
Google Home	Google	(Hey) Google
Magenta Mini	Deutsche Telekom	Magenta
Names and brands may be the property of others.

#### 2.2.1 Conversational Assistants and Agents

For the purposes of this paper, the terms “assistant” and “agent” both refer (as noted above) to conversational AI user interfaces that are perceived to be a single conversational actor, operate on behalf of the user, and operate in accord with a conversational platform.  Both assistants and agents have an addressable name, continuity of knowledge, and a bounded identity.  

Both assistants and agents have the ability to fulfill user intents, mediate and delegate dialogs, and serve as a destination.  Agents will also operate independently on behalf of the user.   In the worldwide voice web, there will be specific-purpose conversational assistants and agents, and general-purpose conversational agents.  

### 2.3.   Platforms and Content: Existing Standards

Most conversational systems separate the platform from the content that is executed on that platform.
In Web Models - a common structure - the content itself is typically either static or active web content. The platform is roughly analogous to a browser;  the content is stored on web servers and accessed by standard web protocols (e.g. HTTP) .
A set of related standards proposed by the W3C Voice Browser group   has successfully created standardized formats for describing content for spoken dialog , speech recognition grammar  , semantics , text-to-speech markup  and pronunciation    This content can be interpreted by a W3C compliant voice browser.
The W3C voice-browser group standards have served the telephony community well, but have not yet been adopted by the leading general-purpose conversational platforms, nor by the many creators of text-centric chatbot platforms.  One notable exception is speech-synthesis markup, which has been widely adopted. 
This new wave of voice assistant platforms also uses a web-content model to support third-party dialog content. The formats for such content are mostly published but remain proprietary. Examples include Amazon Skill Definitions and Google Actions. Content for this new wave of platforms utilizes standard web protocols (such as HTTP  or OAuth ) but also strongly promotes or mandates proprietary infrastructure and authoring tools.

### 2.4  Conversational Architecture

Below is a schematic view of a generic conversational assistant system.
The Open Voice Network basesits explorations of voice assistance interoperability upon this understanding of system components and architecture, and upon the high-level definitions of sections 2.3.1 and following. 

Figure 2.4

Figure 2.4 illustrates the schema of traditional conversational architecture, along with the various components that are collectively enlisted to enable two-way communication with the user.  

The architecture typically operates as follows, as per the above diagram, from left to right:
The user begins (far left) with an endpoint, which can be located on any piece of digital hardware.  Today’s endpoint options include conversational assistant implementations on devices ranging from smart speakers, smartphones, desktop or laptop computers, and smart home systems, to automobile dashboards, television remote controls, and kitchen appliances  – the list is endless.  Endpoints provide a software or hardware interface between the user(s) and the Conversational Platform, which includes all of the components within the encircled figure above.  An example of a simple endpoint is an old-fashioned telephone (often referred to as the plain old telephone system, or POTS). A sophisticated end-point might be an immersive VR environment. 
Endpoints engage with the user via audio, text and visual media. Platforms interpret content that embodies voice assistants and enables them to interact with users via the endpoint. 
Conversational input from the user to the endpoint can take one of several forms called conversation components. The diagram above depicts three; let’s explore these as listed from top to bottom in Figure 2.4.
The most traditional form of user-assistant communication involves Speech Recognition Technology, where the device interprets what information the user is orally speaking. 
Speech recognition technology (speech-to-text) has grown more accurate and sophisticated in recent years. Previous generations of this technology enlisted a very narrow spectrum of comprehension; at each dialog step, they required application-specific grammar to define the wording of 'allowable' spoken responses. Such grammars could be described using the W3C GRXML standard.   Newer generations of speech-to-text engines use general purpose language models that can be shared across applications and contexts. This, of course, represents a considerable step forward. However, there are still no open standards for language model description at the present time, which limits interoperability.
Empowering this process, Natural Language Understanding (NLU) capability - a branch of Artificial Intelligence - enables the comprehension of the meaning of a user’s human speech and clarification of underlying intentions.
The second category of conversational components - a Text-to-Speech System (TTS)  is used for scenarios where the user communicates to the endpoint via  text in lieu of a spoken voice.  The TTS converts normal language text into audible speech and can be implemented in software or hardware products. Normal language text may contain symbols,  numbers and abbreviations that are converted to spoken words presented to the user via a speaker.  The quality of a speech synthesizer is gauged by its similarity to the human voice and by its ability to be understood clearly.

The third category of conversational components, the Graphic User Interface (GUI) Adapter,  comes into play in those unique instances where the user requests rich media content, such as buttons, images, and formatted text, to be visually displayed on the endpoint’s screen.  The endpoint will generally only be able to display said content if it receives specially formatted input from the platform. Likewise, the platform will only be able to “understand” user GUI input if it is first “translated” into a form it can understand. 

As defined by the World Wide Web Consortium (W3C) Voice Interaction Community Group , the Dialog Manager is a component that receives semantic information derived from user input (both NLU and Text to Speech), updates the dialog history, its internal state, then decides upon subsequent steps to continue a dialog and provides output.  It also acts as a translation engine for GUI content.
The Dialog Manager passes information to the Session Manager and retrieves information from it. The Session Manager is essentially a governance body within the voice architecture. It governs and administers conversational sessions with the user. This means controlling starting and stopping points, identifying and verifying the speaker, verifying the conversational agent,  managing connectivity among multiple conversational agents, and, significantly, maintaining      the context necessary for an active conversation  between a user and a bot/assistant.  A unique session ID is generated for each session, allowing the context of the conversation to be maintained over time.

### 2.4  The Diversity of Today’s Conversational Assistance

The popularity of general-purpose consumer conversational assistance (Amazon Alexa, Google Home, Deutsche Telekom, Samsung Bixby, Baidu Xiaodu, and others)  has often obscured the growth of other parts of the conversational assistance ecosystem.
Firms such as Microsoft, Deutsche Telekom, Nuance (now a division of Microsoft), SoundHound, PeopleReign, Cerence, RASA, Mycroft.ai, Redfox.ai (and many others)  now offer enterprises the tools and services to develop conversational assistance solutions for devices, smart environments, personal transportation, customer service and employee support.  
Enterprise investment in conversational AI worldwide is expected, by 2025, to reach a level double that of where it was four years prior5; we’re now seeing per year annual growth rates of    roughly 22-25 percent. 
Analysts foresee the bulk of future growth in these areas:
  *	Customer service and employee support solutions – many of which have grown through the years from call center automation.  These are often classified as interactive voice response (IVR) systems.  
  *	Personal and autonomous transportation
  *	Smart environments, from homes to manufacturing facilities 
  *	Hands-free environments, from surgical suites to warehouses

 
## SECTION THREE:  AN APPROACH TO VOICE ASSISTANCE INTEROPERABILITY

### 3.0 Introduction
Section Three describes the Open Voice Network approach to the interoperability of voice assistants, and the current intent fulfillment patterns under investigation. 

### 3.1. Modeling Interoperability on How People Communicate

The Open Voice Network acknowledges that a standard methodology for expressing and describing conversational interaction may be achievable -- but may not achieve the objectives of the ‘Jobs to Be Done’’ identified above, particularly for the Technical Innovators. 
Attempts to describe (and standardize) how conversation can and should be modeled will quickly become outdated as the field of conversational interaction innovates.  As an example, the latest generation of Voice System Infrastructure Providers and Technical Innovators put aside the widely-adopted W3C VoiceXML and Speech Recognition Grammar standards in favor of creating new design paradigms based on less constrained speech-to-text and NLP technologies.
Thus we assert this:  human languages can be considered the ultimate interoperability standard. People have internal hidden motivations and knowledge. They use language to align their understanding of the world  with tasks to be achieved. In some conversations people will have enormous levels of trust and shared understanding prior to the interaction. In others they will be complete strangers and may not trust each other.
We envisage that successful interoperability approaches will support a model of autonomous agents collaborating to achieve a goal together using standard ways to share information with each other, operating at various levels of trust and information sharing.

### 3.2  Interoperability:  Mediation and Delegation

The modeling of voice assistant interoperability according to human communication leads us to identify two types of interaction:  mediated and delegated.

Figure 3.2.a. Example of mediated and delegated communication.

Figure 3.2.a shows two examples of how people inter-operate to achieve a conversational task, in this case between a 'user' and a helping 'agent'. 
In the top example of mediated communication, the user interacts with a single agent.  Agent A owns the conversation but may talk with others (e.g. agent B) behind the scenes to achieve the goal. The client may be aware of the existence of agent B but does not interact directly with them.  Agent A is the host of the communication. 

The second example is one of delegated communication.  To fulfill the intent of the user, Agent A passes control of the conversation to Agent B.  Agent A may monitor the ongoing interaction or may drop-out of the conversation altogether.  In this example, Agent A is the initiator of the communication.

In this example of delegated communication, Agent A may need to talk behind the scenes with Agent B to establish whether Agent B is indeed the appropriate (or best) destination for delegation prior to their actual act of delegation. 

To properly fulfill all user intents, Agent A will need to both mediate and delegate conversations.  In some cases the client may not need to communicate with Agent B resulting in a fully mediated conversation.   For example Agent A may place the user ‘on hold’ if this were a telephone conversation, or the dialog may be paused if it is an electronic channel such as chat.

In addition, Agent A may also be asked to serve as a delegate destination – to receive a request from Agent C to fulfill a user intent. 
Analogous to this, Figure 3.2.b  illustrates another aspect of interoperability between people. In situations where considerable trust exists between the collaborating agents then brief referrals (in language) can be made along with the passing of a case-history.
 
Figure 3.2.b. Example of a delegated communication in which context (here, a cast history) is also shared.

The Open Voice Network proposes that, to the extent it is possible, models of inter-assistant and inter-agent collaboration follow similar patterns to those followed by human agents.
Key features of such a model would include:
  * Each agent has an identifiable identity and knowledge boundary.
  *	Each agent will both mediate a communication (serving as a host agent) and delegate  a communication (serving as an initiating agent) depending upon the user intent.  Agents will also serve as a destination of a delegated communication.  
  *	A desired scheme for interoperability will support collaboration as a mixture of mediated and delegated patterns.
  *	Delegation between agents will be performed using brief requests using language.
  * Levels of trust will vary between clients and agents and this will affect the level of information sharing across boundaries.
  * Where high levels of trust exist and there is shared understanding of how to represent knowledge,  delegations and mediations will be supported by shared history and context.

### 3.3 From the Human Model to Standards: OVON Interoperability Objectives

The OVON architecture seeks to establish standardized communication protocols between dialog agents running on diverse platforms.
It does not, however, seek to standardize platform components or the format of content used to configure such components. OVON envisages a world in which conversational systems will continue to evolve in complexity and function.
As such the OVON architecture celebrates diversity in the following areas:
  *	The diversity of underlying technology (i.e. speech recognition, language understanding and dialog modeling);
  *	The diversity of endpoints [e.g. smart speakers, smart phone apps, dumb phones (POTS), audio-enabled web pages etc.];
  * The diversity of conversational design paradigms;
  *	The diversity of labels used to represent semantic content.
To enable mediated and delegated communication by conversational agents within an ecosystem of general purpose, consumer-centric voice agents, and independent, purpose- and brand-specific voice agents and assistants, the Open Voice Network will develop messaging protocols and a destination management and services system that will provide a standardized approach to: 
  *	The way in which a spoken agent name can be used to find an associated agent;
  *	The way in which basic linguistic information is shared between dialog agents;
  *	The way in which immediate linguistic context and history is shared between dialog agents;
  *	The way in which control is handed between dialog agents;
  *	The way in which dialog agents negotiate trust. 

### 3.4 Architectural Patterns Under Investigation 

In response to the Open Voice Network’s Jobs To Be Done review, and informed by the vision above, the Open Voice Network Architecture Work Group  identifies several architectural patterns that, when combined together, could enable seamless intent fulfillment for users of different conversational assistants and assistants. 
The architectural patterns that are being explored are: 
#### Dialog Delegation and Give-Back  (additional detail to follow in Section 3.4.1)
A standard, distributed approach to the delegation and take-back of tasks from one platform to another.  This is modeled on the idea of intercommunicating human agents.
#### Delegation Request and Conversation Context (Section 3.4.2)
A standard, extensible method of passing context between agents.  This is closely related to the delegation and take-back mechanism.  This is modeled on the idea of maintaining case-history during sustained interactions.
#### Dialog Interaction Payload (Section 3.4.3)
A standard, extensible format for the passing of linguistic events between components.  This is expected to consolidate work done over many years by the linguistic and dialog engineering community.
#### Dialog Component Interfaces (Section 3.4.4)
Standard component interfaces, built on top of the linguistic event format, starting with dialog interaction managers.  This is expected to align as closely as possible with existing proprietary approaches.
#### Discovery and Location (Section 3.4.5)
Standard patterns and mechanisms to allow agents to publish and discover services from one another.

#### Sharing and Protection of Data (Section 3.4.6)
A strategy for sharing data elements among conversational agents. It also postulates a constraint enforcement mechanism that enforces privacy constraints on shared data.

These six different design patterns could be used separately or in conjunction with each other.  They could also be adopted as part of other interoperability initiatives such as the Stanford University Open Voice Assistant Lab (OVAL) model discussed later in this paper. model.  
Additional design patterns are in review by the Open Voice Network Architecture Work Group.  Initial work on those patterns can be found in the Appendix, Section 1. 

#### 3.4.1. Dialog Delegation and Give-Back

Figure 3.4.1  Delegation request
Figure 3.4.1 illustrates a typical delegation request.  The user’s request is transferred from the user to a conversational assistant (which we will call the host) which examines the request. If the  host determines that it cannot process the request itself, then the host negotiates (the dotted line in figure 3.4.1) with a second conversational assistant ( the delegate) for possible processing. 

A high-level acceptance/rejection mechanism delegates the request to the second conversational assistant (delegate conversational assistant).  Some establishing or authenticating information will typically  accompany the request to provide context about the initiating agent and requested task.
Through this mechanism, the delegate conversational assistant will assume control, and then fulfill the user’s intent.  In the most basic version of this scenario, the delegate agent will then declare the task as finished.  It may also ask the host agent  to reassume control.

#### 3.4.2  Delegation Request and Conversation Context
When, to fulfill a user intent, an initiating agent seeks to delegate the conversation, the initiating agent will frame its request  so that all potential destination agents can understand it.  Some establishing context for the dialog  may also be necessary.
A delegation request from an initiating agent  requires these capabilities:
  * Request: what the host assistant would like the potential delegate agent to do: the user request
  *	Context: conversational history, plus other parameters (TBD). 

#### 3.4.3 Dialog Interaction Payload
The request payload contains information in standard formats that OVON will define.  It consists of:
  *	Current request
  *	Conversational History
  *	 Other data TBD
The process of delegation may begin with an initiating agent (Agent X) passing part of all of the user utterance as its ‘request’ to a Destination and Location Service or directly to a destination agent (Agent Y).  For example, one might say, “Agent X…” (wake word) “... “.. send me to Agent Y..” ‘..so that I might accomplish x, y and z”.     
The potential destination Agent Y will determine if and how it can respond to the request.  
The Architecture Working Group is exploring the use of a standardized dialog ‘payload’ format to support the passing of requests in a standard form.  

#### 3.4.4  Dialog Component Interfaces
The OVON Architecture Working Group  identifies three levels that can be used to communicate a request from one assistant to another.
  *	Level 0.  An audio stream or file containing a natural language request.
  *	Level 1.  A text string containing a natural language request
  *	Level 2.  A structured semantic representation of a natural language request.
Using this taxonomy we can see that the example shown above is a level 2 (semantic) request.    This requires assistant X (or its platform) have a pre-registered understanding of the semantic labels of assistant Y, or as a minimum to have a common pre-agreed set of semantic labels.  In the given example, this is a prerequisite because the request is accompanied by a semantic representation of the request, not just a natural language request string.   
There is no architectural requirement for the delegation request to be built directly from the user’s language.  The host delegate could synthesize a delegation request in its own natural language.  When level 2 communication is used, both conversational assistants must have a common understanding of the semantic representations.  In addition, we do not anticipate a  requirement for a delegation request to be built directly from the initiating assistant’s language.  The initiating delegate could synthesize a delegation request in its own language – natural or internal.  This would also be of value in situations in which multiple natural languages are present, with either a multilingual human user or a multilingual assistant. The mechanisms for handling multilingual delegation are not yet specified.
In addition to the three layers noted above (audio, text, and semantic representations of speech) the following may also be represented in a conversational history:
  *	a user ID, standard for Identifying users;
  *	a platform ID, standard for identifying the platform;
  *	a conversational agent, standard for identifying the conversational agent
  *	a session ID, standard for identifying session;
  *	inflection, standard symbol sets for annotating stress and intonation of speech
  *	a dialog act, standard symbol sets for representing dialog acts (e.g.  asking a question).
Other richer semantic representation formats will likely emerge over time.  The set of supported layers will grow over time as proprietary formats are proposed for adoption.
The Open Voice Network may propose a standard format for each of these layers.   At present, we envision the identification of specific layers as either mandatory or optional. 
Regarding the Open Voice Network approach to standardization,the development of each of these layer schemas will draw heavily from formalized or de facto industry standards.  These could include formal standards (e.g. TEI, UTF, W3C Pronunciation representation  etc.) or broadly adopted specifications from industry leaders.  
Each layer may be also be possibly expressed using the Extended MultiModal Annotation Language EMMA [https://www.w3.org/TR/emma/]
In an early proof of concept demonstration, the OVON Architecture Work Group successfully transmitted  level 1 (text) messages between Mycroft, Magenta, and Genie conversational agents. [MOAD summary.docx - Google Docs].

##### 3.4.4.1 An Illustrated Example: Pat Goes Shopping   
Let’s return  to  the illustration of  shopping with Pat, as presented earlier in  section 1.5.   Below, figure 3.3.4  breaks down the requests of Pat’s dialog with two conversational agents, Shop (a home shopping agent) and Payperson (a payment agent).   Note the three layers of interfaces and their interaction, as depicted  here.   
 
Figure 3.3.4: Current request and a subset of the conversational history of a Pat shopping dialog.

*	Layer 0: Audio. An audio stream or file containing a natural language request.   Voice is represented in computers as a sequence of bits, often called a wav file.  Above, we show electronic representations as wave icons.
*	Layer 1: Text.  A text string containing a natural language request.  Above, the red icon, representing Pat’s utterance, is converted by the TTS into the text: “Put two apples in cart.”
*	 Layer 2:  The structured semantic representation of a natural language request, here shortened to "goals."  Semantics (meaning) of a user goal is often represented using intent and slot container structures, which represent goals/actions to be performed and the parameters defining the actions.  Above, Pat’s text expression is converted into the Intent, PutInCart, with the parameters “Apples” as the value of Food Item and “1” as the value of Quantity.
To complete the example, the  dialog manager generates the text message, “Two apples were placed in cart,” which is converted by the TTS into a wav file (depicted by the green waveform graphic above) and  then presented to the user.  
.
#### 3.4.5. Discovery and Location
In order for a user to connect with conversational assistants anywhere in the world, the user will need to discover which conversational assistants exist, and how to connect to them.  Discovery and Location services will provide the location of a conversational assistant in response to a user request, and may include
*	a DNS-like service for looking up the conversational assistant’s address given its name;
*	the use of search engines, browsers, and aggregators that examine meta information about conversational assistants that provide the conversational assistant’s address;
*	the use of natural language requests sent from one agent to another which the receiving agent can use to decide if it can fulfill the request.
 A request to a Discovery and Location service from an initiating agent  will likely include text with the user’s request and contextual information.  
The response from Discovery and Location services(s) and an identified destination agent will include a digital address, configuration information, and privacy/security constraints. 

Figure 3.3.5: schematic of the role of an envisioned Discovery and Location Service. 
The schematic above  illustrates the role of an envisioned Discovery and Location Service in the process of delegation.  In a future worldwide voice web with  millions, if not billions of destinations, a Discovery and Location Service (or Services) would enable an initiating agent to find and connect with a destination agent.  In practice, it would determine which conversational assistants should be invited to the delegation and identify the digital addresses of the potential destinations.

#### 3.4.6.  Sharing and Protection of Data  
Earlier this year, the Privacy and Security Work Group of the Open Voice Network Technical Committee published for public review the guiding white paper Privacy Principles and Capabilities Unique to Voice.  
From a perspective of a human user of voice assistance – and anticipating an OVON assertion of both mediated and delegated interoperability – the Privacy Principles white paper reviews the current landscape of regional and national privacy regulation and legislation, identifies primary human user risks and potential harms, and details four principles that the OVON believes should guide the development and implementation of voice assistance:
*	Transparency: proactive communication – through an easily accessible and readily available interface -- to the individual user of data collection practices, general data usage, and data sharing policies.
*	Consent: the expectation that the individual user must be allowed to give explicit, unambiguous agreement to the collection and processing of personal data. 
*	Limited Collection and Use:  a restriction of the collection and analysis of raw and processed voice data – beyond that necessary for immediate dialog functionality – to  stated and creator consent-given purpose. 
*	Control:  the ability of the individual user to easily access, rectify, suppress, limit, oppose, and transport the data created by the individual user. 
Under development now by the Privacy and Security Work Group are two additional papers:
*	Data Security Specific to Voice, a review of current data security issues within voice assistance, and of data security issues inherent within multi-agent voice interoperability.  This paper is scheduled for publication in August, 2022. 
*	Voice Assistance and the Privacy of Organizational Data, an exploration of why, when, and how organizations of all types (and especially enterprises) may protect proprietary data from undesired sharing and platform collection in both mediated and delegated interoperability.  A first draft of this paper is scheduled for publication in the fourth calendar quarter of 2022. 

In parallel, the Ethical Use Task Force of the Open Voice Network published for public review the white paper Ethical Guidelines for Voice Experiences.
From the perspective of a human user of voice assistance, the Ethical Guidelines white paper identified voice-specific issues of ethical and moral concern,  explored rights that must be respected and the values to be promoted, and addressed preventative measures that could be taken to protect users from voice-specific harm. 
The paper also outlined a voice-specific ethical framework of five principles:  
*	Compliance: the acknowledgement of, and adherence to, ethical principles, standards, guidelines, and existing laws and regulation. 
*	Transparency:  open and clear communication – in an easily accessible, understandable, and explainable user interface – regarding the collection, usage, and sharing of user and user-created data.
* Privacy Protection:  not only adherence to the regulation and legislation that governs personal data of all types ,  - especially voice data  - but the prioritization of data security and the vetting of the third parties that may, even with transparent consent, handle and process voice data.  
*	Inclusivity: working at all times to allow all to be heard – across languages, dialects, genders, ages, ethnicities, types and levels of disability.  
*	Accountability:  maintenance of, and adherence to,  highest ethical standards throughout the voice development, implementation, and operational value chain.

A next step for the Open Voice Interoperability Initiative (see Section Six, below) will be to translate the principles of these four papers into tangible, implementable technical guidelines and specifications.
 The Work in Progress appendix to this paper (see section A.16, p. 69) contains  an early proposal for an enforcement mechanism for privacy constraints. The approach consists of two mechanisms: (a) a mechanism to determine if data should be shared and with whom it is shared, and (b) a mechanism to monitor and control data  after it is shared. 



## SECTION FOUR:  LESSONS FROM OTHER INTEROPERABILITY INITIATIVES

### 4.0 Introduction
As noted in Section One, the coming world of voice will be one of diversity, one marked by a multitude of voice assistants and agents.  At present, however, the realm of general-purpose consumer-facing voice agents is one of singular, proprietary platforms that do not interact with one another.  
As noted, the Open Voice Network envisions  a future in which proprietary walls to content and connection are lowered, and users may seamlessly move from one agent to another according to intent – a future in which voice operates broadly like the web, and not like apps on a mobile platform. 
This section provides an overview of two important interoperability initiatives outside the Open Voice Network.  We applaud –and are learning from – both We also anticipate some level of adoption and adaptation of the concepts described here, as our work progresses.

### 4.1. Amazon Voice Interoperability Initiative (VII)
The Amazon Voice Interoperability Initiative (VII) enables the deployment of multiple voice agents on a singular endpoint device.  Assessed with the Open Voice Network framework, it offers limited delegation – e.g., it does not allow the delegation of a conversation, but allows the user to leave one agent and engage with  another.
In a VII implementation, each agent is activated via its own ‘wake word,’  enabling users to talk to the agent of their choice in a secure manner by simply saying its name. For example a user can interact with a specialized voice agent (such as Fridge) for specific refrigerator interactions, and leave the specialized voice agent and switch to a general-purpose voice agent (Amazon Alexa) for general purpose interactions.   In this example, the Fridge voice agent would be designed with the vocabulary and skills specific to refrigerators, and would avoids the vocabulary and skills provided the Alexa. Likewise, Alexa would not need to deal with the vocabulary and skills for the refrigerator.
The agents interoperate with each other via the Multiagent experience (MAX) toolkit. The toolkit provides the MAX Library and a Sample Application that demonstrates the interoperability of Alexa and a second independent voice assistant. The MAX Library facilitates interoperability between voice assistants according to the guidance provided by the Voice Interoperability Initiative (VII) Multi-Agent Design Guide.
 

Figure 4.1.1: Amazon Voice Interoperability Initiative
Within the VII guidelines,  an agent can transfer a user to a second agent when it cannot directly fulfill a user request and is aware that the second agent on the device can likely fulfill that request. No data or context is passed between agents during a transfer, and the customer repeats their request directly to the second agent  without needing to say the wake word.
In addition, agents interact with the device via Universal Device Commands. UDCs are commands and controls that a customer may use with any compatible agent to control certain device functions, even if the agent was not used to initiate the function. Examples include changing the volume of the device’s output speaker or stopping a sounding timer or music initiated from agent B when agent A is in control.  
Comparison to the Open Voice Network proposal
*	The focus of Alexa’s VII is on multi-agent devices, i.e. several agents running on one device. 
*	Delegation is limited to the agents present on the device.   The Open Voice Network envisions a limitless number of potential voice-enabled destinations. 
*	Interoperability and agent “discovery” is handled by the MAX toolkit and is limited to agents registered and running on the device. In contrast, OVON allows for interactions between agents potentially running exclusively on the cloud.
*	In VII, agents are discouraged to talk directly or pass information and context to each other.  The user will need to repeat the queries to the second agent.
*	VII demands the presence of two running middlewares to mediate agent interactions (the process running the MAX library and the device application and UDCs).

### 4.2.  The Stanford Open Voice Assistant Laboratory (OVAL) Model 

The Stanford University Open Voice Assistant Laboratory, under the direction of Professor of Computer Science Dr. Monica Lam, has proposed an open-source model for voice interoperability that enables mediation and partial delegation to multiple independent devices and services.  (Full transparency:  Dr. Lam is a valued advisor to the Open Voice Network, and the OVON is a financial supporter of the OVAL.)
     
The Stanford OVAL model also follows the “Standardized Open Single Platform”  model. It is a single platform model. 
The Stanford OVAL model gives developers the ability to collaboratively create “articles” through a device and services knowledge base known as “Thingpedia.” This empowers users to move from an initiating agent to  voice-enabled devices (i.e., a smart light bulb or smart factory sensor) and various services (a smart home system, a restaurant or retail website, or media properties such as Twitter or radio content).   OVAL has demonstrated this model with several partners, using the OVAL “Genie” open-source voice agent as both mediator and initiator. 

A strength of the Stanford OVAL model is that it allows the chaining and management of different articles combined in a single utterance (i.e.,  “When weather goes over 100F tweet out ‘oooh it’s hot’ ”).   This also allows users to access multiple devices/services in a single request, although interoperability is restricted to the destinations, services, and use cases identified in Thingpedia. 
Another significant strength of the OVAL model- is that it enables users to enroll and save their devices/services. This allows users to interact with these devices/services securely and privately (without the need to authenticate separately and repeatedly).
 
Figure 5.2.1  Stanford OVAL architecture
The three core elements of the OVAL model:
ThingPedia
* ThingPedia is the knowledge base of what can be done by each device/service. 
ThingSystem
*	ThingSystem stores all device/service credentials for individual users allowing the platform to maintain privacy and security for the user. It runs the ThingTalk code that is provided by ThingPedia.

ThingTalk
*	ThingTalk is the programming language that lies at the heart of OVAL platform. It gives the platform the power to connect IoT devices, web services, and database queries that are specified in ThingPedia.

Observations: 
1.	We perceive the OVAL model to be primarily one of single-agent mediation. 
2.	If the OVAL model (with knowledge base Thingpedia and programming language ThingTalk) were  widely adopted, it would deliver the capabilities of the Discovery and Location service identified above as a requisite for interoperability.   
3.	As the ThingPedia service expands, we fear that its ability to deliver discoverability may become strained.   Currently Thingpedia has several hundred distinct “skills.”  We must learn plans (UX, governance, etc.) for the scaling of the knowledge base to incorporate  millions (or billions) of future skills. 


## SECTION FIVE: FURTHER STUDY AND NEXT STEPS

This paper is but the first step on an important but challenging journey toward mediated and delegated voice assistance interoperability.
Visible next steps for the Open Voice Network Architecture Work Group include the following: 
*	The review, discussion, revision and confirmation of the concepts shared in the Work-in-Progress content in the Appendix to this white paper.  

*	The identification and assertion of messaging protocols  that will allow independent voice assistants to mediate, delegate and serve as destinations for dialogs.  With the encouragement of the Open Voice Network Steering Committee, the Architecture Work Group will first pursue  adopting or adapting both existing standards and technologies that are now broadly used within the voice industry.  

*	Continued  research as to mediated  and delegated interoperability with existing and emerging voice and conversational AI services, including:
a)	interactive Voice Response (IVR) systems inside corporate data security firewalls;
b)	voice-enabled conversational bots;
c)	voice-enabled web applications;
d)	conversational AI implementations within enterprise software and processes;
e)	enterprise-focused Conversational AI platforms.

*	The development, with the OVON Voice Registry Work Group of the Technical Committee, of a standards-based approach to discoverability, findability, and location services.  We anticipate publication of a separate document on this issue in the months ahead.

*	The expansion of OVON messaging protocols to enable the sharing of multi-modal content. 



## SECTION SIX:  OPERATIVE VOCABULARY 

Component:  an identifiable part of a voice assistant or agent.  A component provides a particular function or group of related functions.  
Context:  Information extracted from n prior utterances of the current conversation. This could include some or all of the following: information that has been inputted to outputted from, or inferred in Conversational Processors, and the information state of the Dialog Manager. Also known as ‘Conversational Context.’
Conversation:  a joint activity in which two or more agents (human or automated) use linguistic forms and non-verbal signals (i.e., gestures) to communicate to achieve an outcome that meets a shared goal.
Conversation Event: a conversation event signals shifts in the conversation that may be acted upon. Such an event may occur at the beginning or ending of a Conversational Session, completion of a Conversation Processor, decoding of Conversation Information, changes to the state of a Conversation Endpoint, or changes to the status of a Conversation Stream. Any component with access to the system is allowed to generate a Conversation Event.
Conversation Facilitator: a component that coordinates communication between two or more Dialogue Systems and/or Processors during the course of one or more Sessions. This allows dialogue Systems and associated Processors to collaborate regardless of technology being used. Examples of Conversation Information include semantic, lexical, syntactic, and prosodic features.
Conversation Information Layer: an  abstraction of a type of information in a Dialog System. A layer may be a specific type of acoustic, linguistic, non-linguistic, or paralinguistic features. Examples of layers would be Cepstral features, Phonemes, Intonation Boundaries, Words, Phrases, Turn Boundaries, Syllabic Stress, Discourse Move Type and specific Semantic representation schemes.
Conversation Processors:  conversation information is encoded and/or decoded by one or more Conversational Processors, also known as a Component. Conversational Processors may also take as input the output from another Conversation Processor. A Conversation Processor may generate Conversation Events and Conversation Streams. Example conversational processors include Automatic Speech Recognizers (ASR), Natural Language Processors (NLP), Dialog Managers, Text to Speech Synthesizers (TTS), etc. 
Conversation Session:  a particular conversation that consists of two or more Conversation Streams (see below) generated by two or more agents through one or more Conversational Endpoints. Sessions may be persistent, but they will often have a start-point and an end-point in time determined by one of the Agents or some other external event.
Conversation Stream:  each Conversational Endpoint generates one or more Conversation Streams based upon the capabilities of the Endpoint and the preferences of the Agent. A Conversation Stream is associated with a particular Agent and may include any media type including text, audio, video, and application UI events.
Conversational Agent: a digital participant in a conversation. This may be an application with a consistent persona, such as Amazon Alexa, Google Assistant, the Target Google Assistant Action, a Facebook Messenger chatbot, or an IVR system at a bank or a human. Conversational agent is a common term utilized in the area of Dialogue System research and university level instruction; the term often is used to describe a human participant in a conversation. For clarity of reference, however, the OVON will use the term "user" to identify a human participant. (See "user" below.)
Conversational AI: the set of technologies to enable automated communication between computers and humans. This communication can be speech and text. Conversational AI recognizes speech and text, understands intent, decipher various languages, and responds where it mimics human conversation. In some cases, it is also known as Natural Language Processing.
Conversational Context -See ‘Context,’ above.  Conversational Delegation: the passing of dialog layers and control between one Conversational Assistant and another to fulfill a user intent. The first assistant in the delegation sequence is the initiating assistant; the second is the destination assistant. 
Conversational Endpoint: agents conduct conversations using conversational endpoints; these may be a phone, mobile device, voice speaker, personal computer, kiosk, or any other device that enables an agent to participate in a conversation. Endpoints may be referred to elsewhere as a "device" or a "channel."
Conversational Information Packets: information that relates to a specific period of time. Packets form the input and output of Conversation.
Conversational Mediation: the hosting of a dialog by a Conversational Assistant.  In conversational mediation, the host assistant may fulfill a user intent by itself; it may access third-party data sources through API calls; or, it may introduce to the user a third-party application that is resident on the platform of the host assistant.  A mediating assistant does not cede control, nor access to the data within the conversation.  
Conversational Platform: A group of technologies that are used as a base for one or more Conversational Agents; also (see "Platform" below) a business model that harnesses and creates a large, scalable network of users and resources that can be accessed on demand.
Data: (per the Cambridge Dictionary): information, especially facts or numbers, collected to be examined and considered and used to help decision-making, or information in an electronic form that can be stored and used by a computer. Context (see above) is a subset type of the data accessed and used by the voice assistant system.
Dialog Manager (DM): handles the dynamic response of the conversation. It provides a more personalized response based on the action provided by the NLP to send back to the user.
Disambiguate: when the conversational platform hypothesizes two or more possible resolutions to a user utterance, it may ask the user for additional clarification or choose between the various interpretations to decide the user's correct intention.
Entity: aa custom level data type and considered a concrete value to associate a word in a query. It is a part of the structural machine translation.  lso known as annotations.
Explicit Invocation: an invocation type where the user invokes the channel, and explicitly states a direct command to accomplish a specific task. The direct authority is to communicate directly to a registered voice application.
Implicit Invocation: an invocation type where the user invokes the channel, and uses the most common words or indirectly saying the explicit Invocation. 
Invocation: a part of the construct of the user's utterance during a conversation with a channel. An invocation describes a specific function that the guest wants, and solicits  a particular response.
Intent: the identified action that the machine interprets based on the user's query. It is a part of the structured machine translation. Also known as a classifier. 
Intent Broker (IB):  is responsible for providing the fulfillable intents available for a resolved destination request (e.g. where resolved destination request for "BigGrocery", its fulfillable intents might be "order product, check order status, add to shopping list".) These fulfillable intents can execute remotely on the DM or download locally on the device.
Natural Language Processing (NLP): a service and a branch of Artificial Intelligence that helps computers communicate with humans in their language and scales other language-related tasks. NLP helps structure highly complicated, unstructured human utterance and vice-versa. Natural Language Understanding is a subset of NLP that is responsible for understanding the meaning of the user's utterance and classifying it into proper intents.
Organization: a group of individuals brought together for a specific purpose, including the creation, transaction, and delivery of products or services. Examples would include a for-profit business, a not-for-profit group, or a government agency.
Platform:  The collection of components (the environment) needed to execute a voice application. Examples of platforms include the Amazon Echo and Google Home products that execute voice applications.
Query: user’s word requesting for specific function and expecting a particular response.
Speech-To-Text (STT): conversion of a representation of an utterance from audio to text.
Text-To-Speech (TTS): conversion of a representation of an utterance from text to audio. Also known as Automatic Speech Recognition. It includes customized models to overcome common speech recognition barriers, such as unique vocabularies, speaking styles, or background noise.
Technical Resource:  it can be a publisher/developer. It can be a representative of an entity or independent party. Their role is to create an actual listing of the voice application.
Utterance: spoken or typed phrases.
User: a person who interacts with channels.



## SECTION SEVEN:  ABOUT THE OPEN VOICE NETWORK

The Open Voice Network (OVON) is a non-profit industry association dedicated to the development of standards for voice assistance transparency, consent, limited collection, and control of voice data that will make using voice technology worthy of user trust. In any reality, virtual or otherwise, we believe personal privacy should be respected as the default. The Open Voice Network operates as an open-source community within The Linux Foundation. It is independently funded and governed with participation from more than 120 voice practitioners and enterprise leaders from 12 countries.
The Open Voice Network community’s work is open source. We seek inclusive input and like to share our insights. At present, our work is focused in four areas:
* Interoperability
* Destination registration and management, the ability of users to confidently find a destination of choice through specific requests, and for the providers of goods and services to register a verbal “brand” — similar to the Domain Name System (DNS) of the internet;
*	Privacy, with voice-specific guidance for both the protection of individual user data and that of commercial users; and
*	Security, with a focus on voice-specific threats and harms.
Please see our papers in 2022 and support the Open Voice Network by visiting openvoicenetwork.org.

### About The Linux Foundation

Founded in 2000, The Linux Foundation is supported by more than 1,000 members and is the world’s leading home for collaboration on open-source software, open standards, open data, and open hardware. Linux Foundation’s projects are critical to the world’s infrastructure including Linux, Kubernetes, Node.js, and more.  The Linux Foundation’s methodology focuses on leveraging best practices and addressing the needs of contributors, users, and solution providers to create sustainable models for open collaboration. For more information, please visit us at linuxfoundation.org.
The Linux Foundation has registered trademarks and uses trademarks. For a list of trademarks of The Linux Foundation, please see its trademark usage page: www.linuxfoundation.org/trademark-usage. Linux is a registered trademark of Linus Torvalds.

### Acknowledgements

This paper is authored by the Open Voice Network, with special thanks to the Architecture Work Group of the Technical Committee.  Contributors:  David Attwater, serving as Senior Research Scientist; Oita Coleman; Dr., Deborah Dahl, Senior Editor; Bruce Epstein, Co-Moderator of the Architecture Work Group; Vineet Hingorani; Olga Howard; Kiran Kadekoppa, Co-Moderator of the Architecture Work Group; Dr. Jim Larson, Co-Moderator of the Architecture Work Group; Tobias Martens; Yaser Martinez-Palenzuela; Shyamala Prayaga, Co-Moderator of the Architecture Work Group; Dr. Dirk Schnelle-Walka;  Nathan Southern; Jon Stine; Vadim Tarasevic; John Trammell; Boris Volfson. 



## SECTION EIGHT : REFERENCE LIST

[1] [W3C Voice Browser Group ](The Voice Browser Working Group
[2] [W3C Speech Recognition Grammar Specification Version 1.0](Speech Recognition Grammar Specification Version 1.0)
[3] [W3C Voice Extensible Markup Language (VoiceML) 2.1](Voice Extensible Markup Language (VoiceXML) 2.1)
[4] W3C Semantic Interpretation for Speech Recognition (SISR) Version 1.0
[5] W3C Pronunciation Lexicon Specification (PLS) Version 1.0
[6] [Speech Synthesis Markup Language (SSML) Version 1.1](Speech Synthesis Markup Language (SSML) Version 1.1)
[7] The ARPA MIT Language Model Format
[8] Voice Interaction Draft 1.2 (https://w3c.github.io/voiceinteraction/voice%20interaction%20drafts/paArchitecture-1-2.htm#dialoglayer)
[9] https://solidproject.org/TR/protocol




## WORK-IN-PROGRESS APPENDIX


The following content has been proposed to the Open Voice Network Voice Assistance Interoperability whitepaper.  It is in review by the Architecture Work Group of the Open Voice Network Technical Committee.  As the content is reviewed and revised-approved, it will be entered into the whitepaper.


CONTENT FOR CONSIDERATION OF INCLUSION


A.1  Delegation Diagram
 

Figure x  Host and delegate platforms
Figure x illustrates how two different platforms communicate with each other.  The user interacts with the host platform, which determines if it can process the request or delegate the request with the delegate platform.  The host platform delegates a request to the delegate platform using the delegation strategy discussed below 
A.2 Interaction Examples 

Some ladder diagrams to show how this might all work.
●	Launch example [TBD - David/Boris]
'Bigtincan open Bigrocery'
●	Launch with Intent [TBD - David/Boris]
'Bigtincan ask Bigrocery how much apples cost'
●	Chained control [TBD - David/Boris]
Shop for something and then the shopping app uses a different payment app
●	Can Fulfill Intent [TBD - David/Boris]
'Bigtincan what's the weather like in California tomorrow
 




A.3  Example Delegation  
Here is a step-by-step description of a transfer between two OVONICA-enabled agents, the Automobile agent and the Easy Meals agent.  
Pat speaks the wake word or presses the wake button before beginning to speak to the Automobile agent. He says “I need to plan a meal for home.”
Automobile agent assembles a user request payload containing the verbal, textual, phonetic, and semantic representation for the user request: “I need to plan a meal for home.”  
The Automobile agent examines its own capabilities and determines that it cannot process Pat’s request.
The Automobile agent sends the request payload to the Discovery/Location service which compares the request payload with the capabilities of thousands of platforms.
The Discovery/Location service selects the Easy Meals Platform as the most likely to be able to handle the request payload  and sends the location of the Easy Meals Platform to the Automobile agent.
The Automobile agent sends the request payload to the acceptance/rejection mechanism for the Easy Meals platform and asks if it can process the request.
The Easy meals platform compares the request payload to all of the skills available on the Easy Meals platform and selects the The Easy Meals for Home skill. (Note that the discovery and location function and the acceptance rejection mechanism search descriptions at very different levels: the discovery and location function searches for conversation agents worldwide, while the acceptance/rejection mechanism only searches the capabilities of a single conversational agent.)
Automobile agent delegates control to Easy Meals platform, which activates the  Easy Meals for Home skill
Easy Meals for Home skill interacts directly with Pat.
While interacting with Pat, rather than asking Pat directly for his name, the Easy Meals for Home requests that the Automobile share Pat’s name with Easy Meals for Home
Automobile grants the Easy Meals for Home request, and shares Pat’s name.  Now Easy Meals for Home can address Pat by name, rather than by the more impersonal “you.”  (Note that Automobile could have shared Pat’s name with Easy Meals when it delegated control to Easy Meals, but it didn’t.) 
Easy Meals determines it has completed processing the user request and gives up control back to Automobile.
When developers create new conversational agents, the agents should be OVONICA-enabled.) 
A.4 Uses of Conversational History
Resolve anaphoric references.  An anaphoric reference occurs when a word or phrase refers to something mentioned earlier.  Conversational History makes it possible to resolve anaphoric references.   For example, Pat decides not to buy apples after putting 2 apples into the cart, and says “Put them back.”[VB2]   “Them” is an anaphoric reference to the previous turn.  Anaphoric references may span several turns. Conversational history enables the connection of an anaphoric reference to the item being referenced. The ability to handle anaphoric references across OVONICA agents makes the user conversation more natural.
Share data  If a conversational agent solicits a value from a user, and a later conversational agent solicits the same value again, the second conversational agent can avoid soliciting the value by sharing the value from the first conversational assistant.  This saves the user from having to speak the same value again.
If a conversational agent produces a value and presents it to the user, and a succeeding conversational agent solicits the same value, the second conversational agent can avoid soliciting the value by sharing the value from the first conversational assistant.  This saves the user from having to remember and speak the same value again, saving data errors due to faulty user memory.

A.5  Uses of Conversational History plus current request .
The bottom of Figure xxy illustrates the current request  Current request comprises one or more speech levels for the current goal.  In example xxy, if the user speaks “Invoke delivery”, then the current goal is “Invoke delivery” and the current request would include “Invoke delivery” and possibly lower layers of representation.
Conversational history plus the current request can be used for the following purposes:
 Discover and locate a conversational agent that can process the user’s request. For example, if the user said “Invoke delivery,” the discovery and locate function could use Conversational history and current request to discover an appropriate OVONACI agent, somewhere in the world, that could process the request. 
 A conversational assistant could examine the conversational history and current request and determine if it can process the request before actually starting the process.  Avoiding starting a request that can’t be processed saves the user time and effort.

A.6 Event Messages
Event Messages 
Standard patterns and mechanisms to process external events such as a fire, a print job completed, new information from a priority sensor, or a takeback request from a delegating conversational agent.
Event messages

 


Figure 3.4.1d

Figure 3.4.1d  illustrates the impact of an interrupt event.  Let us assume that an interrupting event (a fire, a print job completed, new information from a priority sensor) has been communicated to destination Agent Y.   If the interrupting event has originated through initiating  Agent X, the event is said to be a takeback event k because Agent X is requesting to once again assume control of the communication. .
There are two primary patterns for agent Y to return control to agent X, agent Y could ‘give-back’ control back to agent Y, or agent X could ‘take-back’ control from agent Y.   The give-back mechanism from agent Y to agent X could be simply framed as another delegation and could be identical to the way Agent X delegated the conversation to Agent Y. However, in some cases a user would indicate that they want something from initiating Agent X during conversation with Agent Y (asking, for instance, the time or weather).  In such cases, we foresee that the initiating agent will have the ability to reclaim “the floor.”   This could be done through ending of current conversation and starting a new one or, simply  delegating current conversation from Agent Y back to Agent X.  
In addition: 
As voice assistance evolves into a Worldwide Voice Web, we can easily envision sequential delegation, where fulfillment of user intent (such as the vacation planning envisioned above) requires a string of delegations, one agent to another to another, and so on.   In theory, this process of delegation could proceed indefinitely.

Procedural guardrails will need to put in place to prevent the creation of infinite loops of delegated communication.  This may be accomplished by ensuring that sufficient context is passed along with each delegation to inform a potential Agent Z that Agent X has already attempted to fulfill the task, and was unable to do so).

Patterns of delegation, give-back and take-back will require control mechanisms so that any given conversational assistant knows when it has  ‘the floor’ and to allow continuity of dialog and control.    This will require some form of ‘connection’ between two agents.  
The Amazon platform, for example, uses Lambda web-services to provide session management between the host ‘Alexa’ agent and a delegated ‘skill’.   Within this a ‘context’ data structure is used for continuity (see 4.3.4 Continuity).  
There are several other, and different mechanisms through which connections can be established between software agents. 


A.7 Request PayLoad
The request payload contains information in standard formats that OVON will define.  It consists of
Current request
Conversational History
 Other data TBD
The process of delegation may begin with an initiating Agent X passing part of all of the user utterance as its ‘request’ to a Destination and Location Service or directly to a destination Agent Y.  .  For example, one might say, “Agent X…” (wake word) “... “.. send me to Agent Y..” (the destination agent) ‘.. do that I might to do 1,2, and 3”.     
The potential destination Agent Y will if, and what, it can do with the request.  
The architecture working group is exploring the use of a standardized dialog ‘payload’ format to support the passing of requests in a standard form.  See section 4.3.5 for more detail. 

A.8  Dialog Component Interfaces
The OVON architecture group has identified three ‘levels’ which can be used to communicate a request from one assistant to another.
Level 0.  An audio stream or file containing a natural language request.
Level 1.  A text string containing a natural language request
Level 2.  A structured semantic representation of a natural language request.
Using this taxonomy we can see that the example shown above is a level 2 (semantic) request.     This requires assistant X (or its platform) have a pre-registered understanding of the semantic labels of assistant Y, or as a minimum to have a common pre-agreed set of semantic labels.  This is because, in that example the request is accompanied by a semantic representation of the request, not just a natural language request string.   
It should be further noted there is no architectural requirement for the delegation request to be built directly from the user’s language.  The host delegate could synthesize a delegation request in its own natural language.   

A.9   Telephone Signaling Analogy
One potential model for supporting an interoperable delegation, take-back, give-back and would be to borrow ideas (and could indeed borrow actual protocols) from the way that telephone networks pass calls between each other. A conversation has an end-point which is initially connected to a physical platform and routed to an initial assistant. That assistant can converse with the user or decide that they wish to pass the conversation on to another assistant hosted on another physical platform. A conversation between the first assistant and the second assistant could happen to establish whether the second assistant is prepared to accept the interaction or has the relevant skills. The conversational floor is then passed to the second agent. Control can either be retained by the current assistant, or passed completely to the new assistant. These patterns are analogous to a tromboned call or a dropped-back call.
A.10  Suggested Priority Level Scheme
Events could be labeled with a priority level. Messages such as “file—evacuate now” have a high priority level while routine messages such as “you have mail” or “your print job is ready”   will have a lower level.   Each conversational agent is assigned a priority level and can only be suspended if the priority level of the message exceeds the priority level of the conversational agent
A.11  Conversation Context
In most cases a delegation request will also need to be accompanied by a conversation context.  The delegate assistant will decide what the response or action should be based on that conversational context. 
The conversation context includes historical information about the interactions between this user and the host assistant up to the point of the delegation.
The OVON architecture working group anticipates that this sharing of contextual data will happen within a predefined OVON format. 
the definition of a standard way of representing dialog context that is flexible and extensible.  This context will likely be defined using the dialog event payload  (see section 4.3.5)  as one of its main building blocks.
Dialog context will likely comprise one or all of the following elements.
Dialog History (stretching back seconds, minutes, days or years)
Audio (optional)
Text (mandatory)
Semantic (optional)
Phonetic (optional)
Intonation (optional)
Conversant identities (optional)
User identity (In a form agreed to be confidential and secure_
Others (extensible)
Custom data could be lodged here.

 
The bare minimum is a foundational contextual layer, text only. Second layer would be a semantic one. Additional custom layers may be added with accruing sophistication - for instance, pronunciation, inflection, and even speaker identity, which may require different structures.   Each layer has a published schema that can be standardized.  
OVON envisions defining which layers are optional and which are mandatory.   Anyone meeting this will be deemed ‘OVON Compliant.

A.12 Dialog Interaction Payload ‘Packet’
The representation of linguistic information is foundational to all conversational systems.  OVON proposes to define a standard dialog interaction payload format. 
These packets will represent a parcel of linguistic content spanning a given period of time between x point and y point.
 
Figure X.  A conceptual representation of a packet of linguistic information.
Figure X shows a conceptual representation of this.  The packet comprises three layers of linguistic information all spanning the same time period represented by the time span.  In the example three layers of information are shown:
Speaker-identity:  a representation of user identity of the speaker
User-sentence:   level 1 textual representation of the user sentence
User-intent-slot: level 2 semantic representation of the utterance
OVON expects to publish a standard format that such packets could be represented.  This for example could be modeled on the existing W3C EMMA multimodal content format. 
OVON further anticipates that schemas will be designed for each ‘layer’ of information that sits within this format.  Initially, text may suffice.  The schema for example could define exactly how linguistic text should be defined.    
The format will be extensible which means that some layers can be OVON compliant and others can be in proprietary formats.  Examples of potential layers include:
Text 
Standard way of representing utterances in different languages.

Semantics (slots and intents)
Standard way of representation these plus
Optional standard symbol sets in different domains and languages

Pronunciations
Standard symbol sets in different languages

Inflection
Standard symbol sets for annotating stress and intonation.

Affect. 
Standard symbol sets for coding of emotions or affect

Dialog Act
Standard symbol sets for representing dialog acts (e.g. ask-question etc.).
It is anticipated that each of these layer schemas will draw heavily from other standards (e.g. TEI, UTF, W3c -pronunciation representation  etc.).  
Other richer semantic representation formats are likely to emerge over time.  The set of supported layers would grow over time as proprietary formats are proposed for adoption. 

A.13  Why Data Sharing Among Conversational Agents is Needed
Conversational agents may need to share data in delegated situations like these: 
Data created by one conversational agent is consumed by another. For example, a shopping agent creates an Amount Due data element and seeks to share it with a payment conversational agent.
The user needs to enter the same data into multiple conversational agents. For example, the user enters name and address information into a shopping conversational agent, a payment conversational agent, and a delivery conversational agent.
The user wishes to save data from one conversational agent for use by future conversational agents. For example, the payment history from a shopping conversational agent is saved for later use by an analytics conversational agent that detects shopping trends.

A.14  When Two Conversational Agents Share Data
Two situations in which two conversational agents may share data are:
Launching and sharing at the same time. When conversational agent A launches another conversational agent B, conversational agent A may grant conversational agent B permission to copy agent A’s data. For example, a shopping agent may grant permission to copy the Amount Due from the shopping agent to a payment agent.
Requesting that data be shared. Conversational agent B asks conversational agent A for permission to copy data from conversational agent A. For example, a launched payment agent may ask a previously launched shopping agent for the value of Amount Due from the shopping agent.


A.15  Requirements for Sharing Data
Requirements for sharing data among conversational agents include the following conditions. [Illustrations and potential implementation notes are included between square brackets.]
Each data element to be shared must be uniquely identified by all conversational agents sharing the element. If internal identifications and/or representations are different from the shared identification, then mappings between the identifications and representations must be specified. [For example, retailer.AmtPaid in one conversational agent is mapped to source.AmountPaid in another. Data format adjustments and data conversion may also need to be specified, for example, the format for Date (2022.05.06) in one conversational element is converted to May 6, 2022 for Date In a second conversational element.]
A robust, secure mechanism must be provided for sharing data elements among conversational agents. [A data pod is an example of such a mechanism for storing documents, with mechanisms for controlling who can access what. The concept of a pod is borrowed from Solid [9], developed at MIT and led by Sir Tim Berners-Lee.]
A mechanism must exist to link related data elements within and across conversation agents [for example, the User’s name and shipping address, or Shopping Cart Contents and Total Due, even if elements of each component might be derived from different conversational elements].
Mechanisms must exist to allow for read-only share [the contents cannot be modified, e.g. a person's name and home address] or modification [e.g. the contents of a shared shopping cart can be continuously updated by each conversational agent that shares the cart]. In the latter case, further mechanisms must exist to prevent inadvertent modification of existing elements.
Conversational agents must either publish their sharing mechanisms -- in which case other conversational agents know which conditions to apply -- or negotiate the conditions of their mechanisms at the time of sharing. The details of this negotiation are TBD.

A.16  Data Monitor and Constraint Management
A mechanism is needed to prevent a conversational agent from using shared data for unapproved purposes.  For example, conversational agent A is willing to share a recording of its conversations with conversational agent B for the sole purpose of training new ASR systems.  However, conversational agent B applies analytical software to the recording to derive business tactics. To detect and prevent unauthorized use of shared data, we ask if a new mechanism is needed.  One such mechanism may be what we term a data monitor.  Other mechanisms may be possible.
The question of monitoring mechanisms must be addressed – in depth -- from legal, ethical, and architectural perspectives.  Monitoring mechanisms – by their very name – may suggest predatory surveillance of users and their communication.   Data monitors may be unwelcomed by the owners of a conversational agent because monitors may capture and transmit proprietary information about the processing within a conversational agent.  We can envision an approach of transparent, informed consent monitoring, in which owners of conversational agents agree on the limits of what the data monitors may do. 
 The data monitor is a mechanism that monitors and tracks the use of shared data. The data monitor  may also enforce constraints on the use of shared data. For example, it might require that a shared voice file be used only by software that trains an AI, that it not be replayed to users, and/or that it be deleted after a specified amount of time.   
The conversational agent that shares the data may specify constraints for enforcement by the data monitor.  A constraint must specify what actions to perform with shared data, when those actions are performed, and what to do when a constraint is violated. Possible actions performed by the data monitor may include:
Notify the conversational agent that shared the data of actions performed with or on the shared data
Prohibit actions performed with or on the shared data that would violate privacy constraints.
The conversational agent that provides the shared data and the conversational agent that uses the shared data must agree on the constraints enforced by the data monitor, and not disturb or “work around” the data monitor. 
The combination of data sharing and data monitoring enables the enforcement of the guidelines specified by the OVON Privacy Working Group:OVON Privacy Principles and Capabilities Unique to Voice - v2.0 - Google Docs
We will follow guidelines established by the security, ethics, and privacy committees of OVON.

 
A.17  Enabling Conversational Apps as Interoperable Conversational Apps 
There are thousands of conversational implementations (such as voice bots, interactive voice response systems, voice-enabled websites, and voice-controlled smart home and smart factory systems)  that we envision as part of the Worldwide Voice Web.  The total available market of conversational AI is expected to grow rapidly over the next three-to-five years. 
Users use save time and complexity if conversational apps are converted into interoperable-enabled apps.   The reasons are similar to those addressed earlier in the whitepaper. For example:
Example 1: To switch from using conversational app1  to conversational app 2 the user must pause conversational app 1, and then initiate (or resume) conversational app 2. If both conversational apps are interoperable enabled, the user only needs to speak “switch to conversational app 2.”
Example 2: To copy a data element from conversational app 1 to conversational app 2, the user must copy the data from conversational app 1, switch from conversational app1 to conversational app 2, then paste the data element into conversational app 2. Alternatively, listen to app 1 speak the value, then repeat the value into app 2 (with the possibility of introducing an error if the user forgets the correct value). If both conversational apps are interoperable enabled, the user only needs to enter a data element into conversational app 1 and it is automatically copied to conversational app 2.
A.18 Converting Conversational Apps into Interoperable Conversational Apps
To make a conversational app interoperable, the developers must modify the conversational app to support (a) the  OVON switching protocol, (b) the OVON copy protocol, or (c) both switch and copy protocols. This one-time only upgrade which will save users time and effort each time the upgraded apps are used.
The OVON protocols for copy and switch will be defined in draft 0.2 of this document. These protocols will enable the application to accept and pass data and context and have the capacity to take and give up floor (i.e., delegate). Developers will also use open-source code/SDK or an API that different platforms use to do the above.  New versions of the code will likely need to updated as needed (using normal software update standards).
 
A.19 Messaging

We anticipate many details will change before the next publication of this document.
A.19.1  Message Types
To interoperate, Conversational Agents exchange messages of two types:
Control messages are used to transfer control instructions between voice agents. These messages contain parameters clarifying how an instruction should be performed. 
Data messages are used to transfer data values between voice agents.  A data message contain voice, text, or  semantic tokens ad other data types TBD 
This document enumerates these message types: 
Control messages include
launchRequest–request to start a voice agent
LaunchResponse–response from target voice agent indicated success or failure
TerminateRequest–request to terminate a voice
TerminateResponse–response from target voice agent indicated success or failure
Data messages include
Data–copy values of data from one conversational agent to another
DataResponse–response from target voice agent indicated success or failure
Reroute – change the TTS so the conversational agent sounds like another conversational agent
RerouteRespons–eresponse from target voice agent indicated success or failure 
Event – notify a conversational agent of an external event that may cause the conversational agent to defocus
EventResponse–response from target voice agent indicated success or failure
As design progresses, additional messages will be added to this list.
  
A.19.2 Usage Scenarios
The above messages can be used to exchange data and content among several conversational agents, as in the following usage scenarios:
Example 1: Figure 2 illustrates one conversational agent controlling another conversational agent. 
Example 2: Figure 3 illustrates a personal conversational agent which accepts requests from the user and transforms those requests into messages to two other conversational agents
Example 3: Figure 4 illustrates a  standalone  session manager which starts and stops backend conversational agents on behalf of the user. (The session manager might also perform speaker identification and verification, conversational agent verification, and manage the connectivity among conversational agents.
 
Atomic and compound messages

The message types in this document are atomic in the sense that no message can be replaced by multiple messages that achieve the same purpose. However, to minimize the number of messages transmitted among conversational agents, message types can be combined into compound messages. For example: launch and focus message types could be combined into a launch-focus message type.

A.19.3  Response Messages
Each message has a corresponding Response message that contains a status property which describes the result performing the activity associated with the message for example, the Start message has a StartResponse message with an additional property indicating if the target.

A.19.4 Properties
All messages have properties. Every message has the following properties:
Source:  address of the conversational agent sending the message
Target:  address of the conversational agent to receive the message
MessageID: Unique message identifier
All respond messages have an additional property:
Responding to message – MessageID of message to which this message responding

A.19.5. Message Types
Launch
The Launch message is used to start a conversational agent, and the terminate message is used to stop a conversational agent. 
MessageID – Unique message identifier
Source – Address of the sender conversational agent
Target – Address of the conversational agent to be started
PriorityLevel – Message priority level above which another message may interrupt this conversational agent (See section on priority level below)
TimeOut – Parameter to denote when the session is timed out
ControllingAgent – The name of the Conversational Agent to be resumed when this conversational agent is terminated.  Default for controllingAgent is “System”

 LaunchResponse 
The StartResponse and StopResponse are confirmation messages containing return codes of success or failure.
MessageID – unique message identifier
Responding to message – MessageID of message to which this message responding
Source of the message – Address of the conversational agent to be stopped
Target of the message – Address of the target conversational agent
PriorityLevel – message priority for enabling interruptions 
Status – success / failure (see status section below) 

Terminate

When a conversational agent is stopped, it loses all state information. Terminate should be used only when the user is finished interacting with a conversational agent.
MessageID – Unique message identifier
Source – Address of the sending conversational agent
Target – Address of the target conversational agent to be stopped

TerminateResponse

MessageID – Unique message identifier
Responding to message – MessageID of message to which this message responding
Source – Address of the sender of the conversational agent to be stopped
Target – Address of the target conversational agent 
Status – success / failure (see status section below) 

Reroute
Reroute is used to route the output to a different TTS so the user hears a different conversational and persona. This feature is used if the developer wants the user to hear a consistent persona across two or more conversational agent invocations. 

MessageID – unique message identifier
Source – Address of the sender conversational agent 
Target – Address of the target conversational agent 
Preferred persona (Example – Shopping Persona vs. Payment Persona)

RerouteResponse

MessageID– unique message identifier
Source – Address of the sender conversational agent 
Target – Address of the target conversational  agent 
Preferred persona (Example – Shopping Persona vs. Payment Persona)
Responding to message – MessageId of message to which this message responding
Status – success / failure (see status section below) 

Data 

The data element is used to transmit the values of one or more data entities between conversational agents
MessageID – unique message identifier
Source – Address of the sender conversational agent 
Target – Address of the target conversational agent 
Payload – there are three  types of data. 
Voice, a voice file
Text, a text file
Semantic Tokens, a file containing semantic tokens

. DataResponse
MessageID– unique message identifier
Source – Address of the sender conversational agent 
Target – Address of the target conversational agent 
Payload –There are three  types of data. 
Voice, a voice file
Text, a text file
Semantic Tokens, a file containing semantic tokens
Status – success / failure (see status section below)


EventMessage

This message notifies the target conversational agent of an external event that may cause the target conversational agent to defocus or suspend
MessageID – unique message identifier
Source – Address of the sender of the message 
Target – Address of the target conversational agent 
MessageLevel – Level (a number between 1 and 9)
MessageContent --  text

EventMessageResponse

MessageID– unique message identifier
Responding to message – MessageId of message to which this message responding
Source – Address of the sender of the message 
Target – Address of the target conversational agent 
MessageLevel – Level (a number between 1 and 9)
MessageContent --  text
Status – success / failure (see status section below) 

A.20. Leftover artwork
 
 


Note to editors:  this is a key David diagram; we must find its accompanying text, and place it appropriately in the paper. 
 











