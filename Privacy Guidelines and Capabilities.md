# **Privacy Guidelines and Capabilities Unique to Voice**

## Open Voice Network, Privacy & Security Workgroup 

Initial version published for internal development 1 October 2020.  
Version 1.0 for public comment published 30 March 2021.

## **Introduction**

The growth of the digital economy -- and its use of data as a fuel and guide for value creation -- has led in recent years to the introduction of numerous regulations, laws, and guidelines regarding data use and consumer data protection.

According to the United Nations Conference on Trade and Development, 128 nations have in place today legislation to secure the privacy of online personal information, with draft data privacy legislation before another 10 percent of the U.N.'s 194 member nations.  (The latter includes the United States, where four draft federal data privacy bills have been introduced in the U.S. Senate since 2019, and where a quilt of topic-specific privacy laws protect the rights of consumers, patients, and minors.)  

Within this long list of consumer data protection legislation and regulation, legal analysts point to two as most important to current European and North American practice: the General Data Protection Regulation (GDPR) of the European Union, which took effect in May 2018, and the GDPR-inspired California Consumer Protection Act (CCPA) of 2018, with follow-on amendments in the California Privacy Rights Act (CPRA) of 2020.  Both declare privacy to be a human right; both approach data use and privacy from a consumer's point of view; both delineate the consumer's rights in regard to data acquisition, use, storage, sale, and transparency.  

Voice assistance began to emerge as an important consumer technology at the same time GDPR and CCPA were in their initial development.  Although GDPR and CCPA (and other national and local legislation and regulation) are directly relevant to the use of this technology, voice assistance brings with it a number new privacy and consumer data use issues.  Many of these issues were addressed by the European Data Protection Board (EDPB) March 2021 publication of a 1.0 guideline that applied GDPR to the current world of voice assistance.  However, voice assistance is now evolving from its current paradigm -- one of platform-based, consumer-centric applications -- to a new, hybrid ecosystem of both platform-based general purpose voice assistants and independent, organizationally-owned and -developed assistants.  This will dramatically expand the universe of voice assistance data and data managers.

For these reasons, the Technical Committee of the Open Voice Network, a neutral non-profit industry association dedicated to standards development for voice assistance, formed in 2020 a Work Group chartered to develop, in accord with current regulation and legislation, privacy guidelines specific to voice assistance. 

**The Open Voice Network**
**Voice-Specific Privacy Guidelines**

Privacy is a human right.  The issue of privacy within voice assistance is of central concern to the The Open Voice Network (OVN) because user privacy is foundational element in the establishment and maintenance of trust.  And trust is crucial for the adoption and success of voice technology.  

In its development of technical capabilities and ethical use guidelines, privacy is addressed from two critical perspectives within an understanding of the technologies and systems of today’s and tomorrow’s voice applications and conversational AI: \

*   The issues of privacy that are **_unique_** to voice technologies; 
*   The issues of privacy in voice technologies between **_individuals_** and **_commercial entities._**

The Open Voice Network Technical Committee asked the Privacy and Security Workgroup to identify, define, and prioritize capabilities of privacy in voice assistant systems. 

The goal of the OVN privacy and security workgroup is to explore, deliberate, and issue recommended guidelines and capabilities for protecting privacy rights, with a scope that is specific to voice technologies.  Consistent with this goal is the understanding that there is already well-established doctrine in the public domain that addresses privacy in technology; principles, policy guidance, capabilities, standards, regulations, and laws.  While this doctrine is in scope in determining the best guidelines and capabilities specific to voice technologies, it is beyond the scope of this workgroup to recommend privacy guidelines and capabilities that are not specific to voice.

The following diagram illustrates at-a-glance, the framework for OVN scope, deliberation, and decision making with respect to privacy:

![OVN Privacy Scope Diagram](/components/privacy_scope_diagram.png)


## **OVN Privacy Problem Statement**

Voice technology has the power to change our lives, however, with voice technology there comes a unique set of privacy risks. Identifying these risks, and minimizing their potential harms, is inherently linked to the successful adoption and use of voice technology.

The Open Voice Network seeks to provide guidance and standards for creating voice technology that respects privacy rights and earns the trust and use of consumers. 


## Approach

The Privacy and Security Work Group of the Technical Committee of the Open Voice Network was formed in June, 2020 by an action of the OVN Technical Committee.  The Privacy and Security Work Group met for the first time on 7 July 2020; Work Group participants selected Mike Frazzini, Iterate.ai, and Maarten Lens-Fitzgerald, voice evangelist and strategist, to moderate Work Group meetings.  As the work proceeded, Mike Frazzini assumed leadership of the privacy work; Lens-Fitzgerald, the security work.

On the topic of user privacy, the Work Group pursued this five-step development process:

*   Research and review of current and leading privacy doctrines, principles, policies, regulations, and laws;  
*   Evaluation, using proven models, of voice-specific user privacy risks and harms; 
*   Exploration of voice-specific interactions determine privacy concerns and risks unique to voice.
*   Definition, discussion, and prioritization of privacy risks unique to voice.
*   Identification and discussion of privacy values, guidelines, and required technical capabilities in regards to privacy risks unique to voice.

The results reported in this document were made possible by Jim Larson, Peter Bentsen, Jonathan Eisenzopf, Doug Rogers, John Iwasz, Lawrence Lin, Maarten Lens-FitzGerald, Nick Myers, Shyamala Prayaga, Oita Coleman, Maria Brinas-Dobrowski, Ali Dalloul, Jon Stine, and many others.


## **Voice Assistant System Overview**

[this section needs to be synced with the terms and definition workgroup results]

**Summary**

To provide context as to what the Privacy & Security Workgroup defines as a Voice Assistant System (VAS) the following diagram has been prepared that defines the specific actors, modalities, channels, components, and services/devices that make up a VAS. This diagram is one possible arrangement that illustrates a complete VAS as data flows from the user through a VAS and back to the user (depending on the type of interaction or request that is elicited from the user).

![Voice Assistant System Overview](https://github.com/open-voice-network/docs/blob/master/Voice%20Security%20Capabilities%20Report.assets/Voice%20Assistant%20System%20Overview.png)

_*Please refer to figure above_

1. **Person**
   The “Person” or user initiates a conversation with a VAS entity.
2. **Modality**
   The voice communication is sent to the appropriate channel via a modality like voice alone or a mix of graphical elements and voice (otherwise known as multimodal). The type of voice communication modality is dependent upon the channel the voice communication is being sent through and user preference.
3. **Channel**
   The channel receives the voice communication in preparation to forward the data onto the VAS for interpretation.
   Channels can include smart devices (smart speakers and voicified devices), mobile apps with conversational features, and other messaging platforms that allow voice communications to be sent in lieu of a text message (i.e. iMessage, WhatsApp, web chats, POTS, and IVR)
4. **Voice Assistant System**
   The voice communication is passed from the channel to a VAS entity for interpretation.
   A VAS contains User ID, Context Data Management, Automated Speech Recognizer (ASR), Natural Language Understanding (NLU), Text to Speech (TTS), Dialog Management, Voice Generation, and other internal/external services as provided by the VAS. Examples of VAS entities include Amazon Alexa, Google Assistant, Erica from Bank of America, and Magenta from Deutsche Telecom. Note that it may be possible for people to listen in or pass the conversation on to a human agent. As this is an internal non-primary process it won't be visualized in the overview.
5. **Services & Devices**
   Once the VAS interprets the voice communication the data is sent to the appropriate service or device to fulfill the user’s request.
   External services consist of a backend such as a voice application from an external party or a third party device that integrates with the VAS.
   Internal services consist of entity owned services with a platform provider-specific backend that funnels voice communications to platform-specific devices (i.e. Ring doorbells, smart bulbs, smart microwaves, Nest thermostats, etc.)


## **Privacy Risks and Related Interactions Unique to Voice**

*Privacy Risk:  Personal and sensitive data is collected without consent and is used and/or shared in ways that may cause harm to the user.*

1) Voice technology involves continuous “listening” and/or recording of raw data that is concurrently processed to provide user interaction, services, and conversation.

2) Voice technology involves processing raw data through AI models to infer user actions and intents.

3) Voice technology data collection usually occurs in the most sensitive of places (the home) where privacy expectations are highest.

4) Voice technology involves a broad scope of data collection with raw data recordings that may contain all manner of information – from background noise and audio context, to biometrics, biomarkers, emotion, dialects, and sentiment – that may not be intended to be shared.  Explicit information is also collected, such as PII, account and payment information, personal preferences, etc.

5) Voice technology may inadvertently include non-consenting and vulnerable populations in data collection.

6) Voice technology involves multiple parties collecting, creating, and sharing data - and the channel - at the same time.

7) Voice technology involves multiple devices in the same environment; potentially listening to, interacting with, and/or controlling each other, and/or controlling all manner of sensitive devices (i.e. car, insulin pump, environmental systems, etc).

8) Privacy policies are difficult to communicate and clarify effectively over text-to-speech playback.

*Privacy Risk:  Personal and sensitive data is inadvertently revealed to others during confirmation and playback, and shared and used in ways that may cause harm to the consumer.*

9) Voice technology involves voice device responses for confirmation and playback.


## **Values, Guidelines, and Technical Capabilities to Address Privacy Risks Unique to Voice**

**1. Transparency**

1.1 A voice initiated user interface must be made easily accessible and readily available to the consumer for the purpose of providing user notification of data collection practices, general data usage, and data sharing policies.
 
_Example: A standard invocation phrase and application service is available on a voice assistant, and when invoked, the privacy policy notification is communicated to the user, and user consent is audibly obtained.  (e.g. User: “**OK Service**, what is your **privacy policy?**” Device: “Privacy policy is . . .  Do you consent to this policy? User: “Yes”)._

1.2 A voice initiated user interface must be made easily accessible and readily available to the consumer for the purpose of providing user notification of general data processing and AI inference routines (for example, if there is an AI inference routine for emotion, this should be disclosed in the notification).
 
_Example: As a subroutine of the privacy policy notification, a voice assistant asks if the user would like to know what inference routines are utilized.  The User responds, “yes,” and the voice assistant notifies the User of the voice inference routines being used (i.e. “voice speech-to-text only.” But if the voice assistant is also doing sentiment analysis, the response would be “voice speech-to-text and voice sentiment analysis.”)_

1.3 Privacy policy notifications should be adapted for text-to-speech playback, as well as made available in other modes that are accessible and adapted to the users and devices involved.

_Example: When a voice assistant is asked "what is your privacy policy?" the response should be tailored to text-to-speech playback, including menuing and smaller segments delivered interactively; Device: "Our privacy policy has multiple sections; 1.) Information collected; 2.) Information usage; 3.) Information sharing; 4.) How to review and request changes to your information; ... Please choose which option you would like to hear the details about."_ 


**2. Consent**

2.1 Data subjects must be allowed to give explicit, unambiguous consent before the collection and processing of personal data.

 _Example: With the initial use of any voice assistant, the voice assistant proactively communicates the privacy policy notification, addressing the collection and processing of personal data, and then audibly captures user consent prior to any collection and processing of personal data._

2.2 A voice initiated user interface must be made easily accessible and readily available to the consumer for the purpose of accepting explicit consent for data collection, usage, and sharing policies.

_Example: A standard invocation phrase and application service is available on a voice assistant, and when invoked, the privacy policy notification is communicated to the user, and user consent is audibly obtained.  (e.g. User: “**OK Service**, what is your **privacy policy?**” Voice Assistant: “Privacy policy is . . .  Do you consent to this policy? User: “Yes”)._

2.3 When there is an explicit third-party provider request (i.e. a request naming a specific party other than the platform provider), data subjects must be allowed to give explicit, unambiguous consent before the collection and processing of personal data by the third party.

_Example: User: “**OK Service**, please connect me to **XYZ company service provider** to service a request.” Voice Assistant: “Privacy policy of **XYZ company** is . . .  Do you consent to this policy? User: “Yes”_ 

2.4 Data must not be used for voice inference training without permission.
 
_Example: Upon initial use the voice assistant asks for voice training for invocation words and commands, and explicitly notifies the user it is in training mode and asks for permission for using the data captures for training.  All other interactions that may be used for training are treated similarly with explicit notification and an ask for permission before data is retained and/or used for training._

**3. Limited Collection**

3.1 Collected raw data must be securely deleted immediately post-processing and post inference. 

_Example: As the voice assistant is continuously performing raw audio capture and running the captures through an Automated Speech Recognition module (ASR), a second process is deleting the raw audio capture data (once it has successfully been passed to the ASR module)._

**4. Control**

4.1 Any data that is not deleted must be accessible by the consumer with the ability to review, correct, or securely delete their data.

_Example: The voice technology platform has an interface that allows the user to review all collected and stored data, providing capabilities for the user to review, correct, or securely delete their data._

4.2 Voice confirmation and playback routines should only include information provided in a related request; if additional information is necessary, explicit prompting and explicit affirmation must occur before confirmation and playback of this information.
 
_Example: A user provides information to a voice assistant to refill a prescription with a reference to a prescription number, the voice assistant application confirms the request but does not playback (TTS) the name or description of the prescription medicine unless explicitly requested to._

![OVN Privacy Values, Guidelines, and Capabilities Diagram](/components/Privacy_Values_Guidelines_Diagram.png)
## 


## Privacy Rights and Guidance Not Specific to Voice

**Additional Rights, Not Unique to Voice:** CCPA – .

-> Privacy Right: To say no to the sale and sharing of personal information

-> Privacy Right: To equal service and price, even if privacy rights invoked

**Additional Rights, Not Unique to Voice:**  GDPR, PIPEDA – .

-> Privacy Right: To accuracy

-> Privacy Right: To erasure

-> Privacy Right: To restrict processing

-> Privacy Right: To data portability

**Additional Rights, Not Unique to Voice:** HIPPA – .

**Additional Principles, Not Unique to Voice:** Canada PIPEDA – .


**[-> Principle of Accountability](https://www.priv.gc.ca/en/privacy-topics/privacy-laws-in-canada/the-personal-information-protection-and-electronic-documents-act-pipeda/p_principle/principles/p_accountability/)**


**[-> Principle of Identifying Purposes](https://www.priv.gc.ca/en/privacy-topics/privacy-laws-in-canada/the-personal-information-protection-and-electronic-documents-act-pipeda/p_principle/principles/p_accountability/)**


**[-> Principle of Consent](https://www.priv.gc.ca/en/privacy-topics/privacy-laws-in-canada/the-personal-information-protection-and-electronic-documents-act-pipeda/p_principle/principles/p_accountability/)**


**[-> Principle of Limiting Collection](https://www.priv.gc.ca/en/privacy-topics/privacy-laws-in-canada/the-personal-information-protection-and-electronic-documents-act-pipeda/p_principle/principles/p_accountability/)**


**[-> Principle of Limiting Use, Disclosure, and Retention](https://www.priv.gc.ca/en/privacy-topics/privacy-laws-in-canada/the-personal-information-protection-and-electronic-documents-act-pipeda/p_principle/principles/p_accountability/)**


**[-> Principle of Accuracy](https://www.priv.gc.ca/en/privacy-topics/privacy-laws-in-canada/the-personal-information-protection-and-electronic-documents-act-pipeda/p_principle/principles/p_accountability/)**


**[-> Principle of Safeguards](https://www.priv.gc.ca/en/privacy-topics/privacy-laws-in-canada/the-personal-information-protection-and-electronic-documents-act-pipeda/p_principle/principles/p_accountability/)**


**[-> Principle of Openness](https://www.priv.gc.ca/en/privacy-topics/privacy-laws-in-canada/the-personal-information-protection-and-electronic-documents-act-pipeda/p_principle/principles/p_accountability/)**


**[-> Principle of Individual Access](https://www.priv.gc.ca/en/privacy-topics/privacy-laws-in-canada/the-personal-information-protection-and-electronic-documents-act-pipeda/p_principle/principles/p_accountability/)**


**[-> Principle of Challenging Compliance](https://www.priv.gc.ca/en/privacy-topics/privacy-laws-in-canada/the-personal-information-protection-and-electronic-documents-act-pipeda/p_principle/principles/p_accountability/)**




## Recommended Next Steps



1. Presentation and review of this report to the OVN Technical Committee, with iteration for any feedback and recommended changes by the Committee.

2. Provide an example of an implementation that meets the guidelines and capabilities, and reassess the guidelines and capabilities to achieve more precision and alignment with the examples.

3. Presentation of this report to other OVN and voice technology technical workgroups with support for the technical implementation of recommended guidelines and capabilities.

4. Review of this report by privacy experts/attorneys, update where applicable.

5. Invite industry and academia participation and feedback, update where applicable.

6. Include this report in the RFC process for all OVN guidelines and capabilities, with updates as applicable.

7. Final work product publication (after the RFC process).

8. Outreach to established privacy doctrine, policy, regulation, and law setting entities to encourage adoption of voice specific privacy guidelines and technical capabilities.
