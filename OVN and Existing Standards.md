## EXISTING STANDARDS for VOICE
### That may guide and inform the work of the Open Voice Network 

The idea that machines could talk with and listen to humans is far from a 21st century idea.
The development of voice-based virtual assistants, often known as voicebots, reaches back at least to the 1960’s.  Research into machine-based speech recognition began to bear fruit in the 1950’s.  Exploration of speech synthesis – machines that could talk -- has been traced all the way back to the late 18th century.
Given the lengthy and rich history of machines that can talk and listen – a phenomenon we may today describe as voice assistance – it is vitally important that any entity wishing today to work in this space must study and understand the current literature.

In late 2016, a group of academics, technologists, and business consultants centered around the Massachusetts Institute of Technology (MIT) began exploration of a new, emerging world of voice assistance.
This world took voice technologies developed for interactive voice response (IVR) applications used primarily in enterprise call centers, and advanced them in three critical ways, with the introductions of:  
•	consumer-owned voice recognition applications, first in 2011 with Apple’s Siri on the iPhone 4S, and then in 2014 by Amazon with the Alexa assistant on the Echo device.

•	a new device – the in-home “smart speaker” that offered voice assistance in a simple-to-use package.   This new device became the fastest-selling consumer electronics item of all time.  Over the years, global annual wholesale shipments of smart speaker devices has grown from roughly 9 million units in 2016 to a projected 136.9 million units in 2020 – a 72.36% CAGR.  At the same time, the availability of voice assistance on smartphones has surpassed 500 million units on Android devices alone. 
 
•	enterprise value propositions that extended well beyond call center/customer service, and into kitchens and smart homes, automobiles, factory management, and enterprise software.  

The MIT research posited that this new world of voice assistance could – and, in time, would – irreparably change the relationship between an enterprise and its customers (be they shoppers, clients, or patients.)   It also suggested that this new world represented a migration from a set of technologies largely bound by a single purpose to the dawn of a new, global system of AI-enabled communication.

A new, global system of AI-enabled communication without broad governing standards that would enable openness, user choice, inclusivity, and the user trust so essential to the system’s growth and value.  A system in its current form that, upon study and reflection, resembled the “browser war” days of the early internet. 
It was from this research that The Open Voice Network (OVN) was born.   The OVN is a non-profit industry association dedicated to the development of standards and ethical use guidelines for the new world of voice assistance.  It operates as a directed fund of the Linux Foundation, and was established in May, 2020.

Why are new and additional voice standards needed?
Broadly stated, voice has evolved over the past decade from call center-centric recognition to a consumer-owned, platform-enabled all-purpose answer machine.  In its next phase – one that is unfolding now – it will become the enabler of contextually-aware dialogue and true personalized assistance.  
The next step in the voice standards journey is address the transitions noted above, as well as these more recent evolutions:
•	Rapid advances in the AI-enabled voice ecosystem and value chain.  A unique industry is now being created with independent voice assistance by world-leading technology firms.  Voice is increasingly the entry point of a data-consuming engine of technology and economic growth.  Today’s voice questions are different, and much larger than before.

•	Ongoing advances in AI-enabled voice technology.   Several of the standards listed below were developed to enable interactive voice response systems for telephone call centers.  We now stand at the edge of contextually-aware voice functionality that enables human-like dialogue. 

•	The emergence of platform-independent voice assistants.  This calls into question platform and assistant interoperability, in which an enterprise-owned independent assistant can speak with all others, regardless of platform or channel.  It suggests a standardization of components, the building blocks of voice assistants – components that have emerged from many of the standards listed below.     

As the OVN begins its work, it does so with the desire to learn from and build upon a significant number of widely-adopted and currently-relevant standards for voice assistance. 
The list below identifies existing voice standards that may guide the functionality and definition of voice assistant components (Dialogue Manager, TTS, ASR, NLU, and many others) and governance protocols (a potential destination registry) now in development by the OVN Technical Committee.  It is acknowledged that this list may not be comprehensive.

This list was assembled by Open Voice Network supporters and advisors Dr. Deborah Dahl, Dr. Jim Larson, David Attwater, and Jonathan Eisenzopf.  We are deeply grateful for their contributions and ongoing guidance.

### Component	Potentially related standards
__IPA Client__	•	(X)HTML, specifies visual content and presentation of web pages
__IPA Service__	none
__Dialog Management__	•	_Voice Extensible Markup Language (VoiceXML_) 2.1 designed for creating audio dialogs that feature synthesized speech, digitized audio, recognition of spoken and DTMF key input, recording of spoken input, telephony, and mixed initiative conversations. Its major goal is to bring the advantages of Web-based development and content delivery to interactive voice response applications.
•	_State Chart XML (SCXML)_  provides a generic state-machine based execution environment based on CCXML and Harel State Tables.  May be used to specify dialogs

__TTS__	•	_Web Speech API_, a JavaScript API to enable web developers to incorporate speech recognition and synthesis into their web pages. It enables developers to use scripting to generate text-to-speech output and to use speech recognition as an input for forms, continuous dictation and control.
•	_Speech Synthesis Markup Language (SSML) Version 1.0_  a standard way to control presentation of speech such as pronunciation, volume, pitch, rate, etc. across different synthesis-capable platforms.
•	_Pronunciation Lexicon Specification Version 1.0_  syntax for specifying pronunciation lexicons to be used by Automatic Speech Recognition and Speech Synthesis engines in voice browser applications.
•	_Emotion Markup Language (EmotionML) 1.0_ as a "plug-in" language suitable for use in three different areas: (1) manual annotation of data; (2) automatic recognition of emotion-related states from user behavior; and (3) generation of emotion-related system behavior.
•	_ToBI_, a set of conventions for transcribing and annotating the prosody  of speech

__ASR__ 	•	_Web Speech API_ , a JavaScript API to enable web developers to incorporate speech recognition and synthesis into their web pages. It enables developers to use scripting to generate text-to-speech output and to use speech recognition as an input for forms, continuous dictation and control.
•	_Speech Recognition Grammar Specification Version 1.0_, syntax for representing grammars for use in speech recognition so that developers can specify the words and patterns of words to be listened for by a speech recognizer.
•	_Pronunciation Lexicon Specification Version_ 1.0 syntax for specifying pronunciation lexicons to be used by Automatic Speech Recognition and Speech Synthesis engines in voice browser applications.
•	_Semantic Interpretation for Speech Recognition (SISR)_ Version 1.0 process of Semantic Interpretation for Speech Recognition and the syntax and semantics of semantic interpretation tags that can be added to speech recognition grammars to compute information to return to an application on the basis of rules and tokens that were matched by the speech recognizer. In particular, it defines the syntax and semantics of the contents of Tags in the Speech Recognition Grammar Specification
•	_International Phonetic Alphabet_ – maybe too much detail but often used to represent the sound of words in lexicons.

__Core Dialog and Annotation__ 	•	_Dialogue Act Modeling for Automatic Tagging and Recognition of Conversational Speech Acts (DAMSL)_ a statistical approach for modeling dialogue acts in conversational speech
•	_ISO 24617-2_  also known as DIT++ or DiAML and background can be found at http://www2.lpl-aix.fr/~otim/documents/OTIM_HarryBunt_Wshop24mai2011.pdf 
•	_There are 4-5 primary ways dialog managers work, but there are no real standards yet._ Predominant methods are Answerset Logic (Q&A) and Finite State Machines with Slot filling (used in VoiceXML, Alexa, Google Assistant, Watson, …). Newer methods that will be introduced in the coming years are Information State Update (Traum et.al) and Incrementation Dialog Processing (Gabriel Skantze, David Schlangen).
•	_The text encoding initiative - https://tei-c.org/ a set of guidelines regarding XML markup of human computer interaction data._  It covers many areas but those relevant to dialogs are : Metadata for language corpora, representing certainty and uncertainty, definition of underlying feature annotation structures (e.g. data structures representing the internal structure of a language feature including key value pairs, trees, graphs), orthographic regularization, transcribed speech, phrasal boundary notation, cross-reference, segmentation and alignment of text or other feature sequences facilitating multi-layered stand-off annotation.

__Core Intent Set__ 	•	_Discourse.ai may contribute our JSON specification_

__Dialog Registry__	•	_Discovery & Registration of Multimodal Modality Components_  a standardized way to build a web Application that can dynamically combine and control discovered components by querying a registry build based on the multimodal types of the modalities and their states.

__Provider Selection Service__ 	•	_The Open Agent Architecture is not fully define but is used internally for Viv and Siri_

__Accounts -Authentication__ 	•	_Web Authentication_ an API enabling the creation and use of strong, attested, scoped, public key-based credentials by web applications, for the purpose of strongly authenticating users
•	_IDO Universal Authentication Framework WIth FIDO UAF_ , the user carries a device with a FIDO UAF stack installed. They can then register their device to the online service by selecting a local authentication mechanism such as swiping a finger, looking at the camera, speaking into the mic, entering a PIN, etc. The FIDO UAF protocol allows the service to select which mechanisms are presented to the user.
•	_Oauth_ – this is what Amazon and Google use currently.
•	_OpenID_ will likely replace Oauth and SAML in the future

__Core NLU__	•	_EMMA: Extensible MultiModal Annotation markup language Version 2.0_  set of specifications for multimodal systems providing details of an XML markup language for containing and annotating the interpretation of user input and production of system output.
•	_JSON Representation of Semantic Information a JSON format_ for representing the results of semantic processing
•	_Abstract Meaning Representation_ used for semantic representation language. Is a culmination of prior researchers and projects and could become how semantic meaning of utterances is represented in the future.
•	_ARPA N-Gram_ format a published format to portably represent language models in N-Gram format.

__World Knowledge__ 	• _Web Ontology Language (OWL)_ a Semantic Web language designed to represent rich and complex knowledge about things, groups of things, and relations between things.
•	_Resource Description Framework (RDF)_  a framework for representing information in the Web
•	_Schema.org,_ an OWL ontology used to organize all information on the web.

## Data Provider	none

17 November 2020
Standards listing from Dahl, Larson, Eisenzopf, and Attwater.  Introductory text, Stine.
