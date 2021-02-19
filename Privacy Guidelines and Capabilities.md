# **Privacy Guidelines and Capabilities Unique to Voice**

## Open Voice Network, Privacy & Security Workgroup 

Origin: Version 1, October 30th 2020, converted to markdown January 19th 2021

## **Introduction**

The issue of privacy is a human right and is central to The Open Voice Network (OVN). Privacy is foundational to trust, and trust is crucial for the adoption and success of voice technology.  

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

Mike Frazzini headed up the workgroup and worked together with the workgroup members to deliver the results as reported here using this approach:

*   Privacy doctrine, principles, policy, regulations, and laws were researched and reviewed.
*   Privacy risks and harms were evaluated.
*   Voice technology interactions were explored to determine privacy concerns and risks unique to voice.
*   Privacy risks unique to voice were enumerated and challenged.
*   Privacy values, guidelines, and technical capabilities enumerated and challenged to address privacy risks unique to voice.

The results reported in this document were made possible by Jon Stine, Jim Larson, Peter Bentsen, Jonathan Eisenzopf, Doug Rogers, John Iwasz, Lawrence Lin, Maarten Lens-FitzGerald, Nick Myers, Shyamala Prayaga, Oita Coleman, Maria Brinas-Dobrowski, Ali Dalloul, and others.


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

*Privacy Risk:  Personal and sensitive data is inadvertently revealed to others during confirmation and playback, and shared and used in ways that may cause harm to the consumer.*

8) Voice technology involves voice device responses for confirmation and playback.


## **Values, Guidelines, and Technical Capabilities to Address Privacy Risks Unique to Voice**

**1. Transparency**

1.1 A voice initiated user interface must be made easily accessible and readily available to the consumer for the purpose of providing user notification of data collection practices, general data usage, and data sharing policies.
 
_Example: A standard invocation phrase and application service is available on a voice assistant, and when invoked, the privacy policy notification is communicated to the user, and user consent is audibly obtained.  (e.g. User: “**OK Service**, what is your **privacy policy?**” Device: “Privacy policy is . . .  Do you consent to this policy? User: “Yes”)._

1.2 A voice initiated user interface must be made easily accessible and readily available to the consumer for the purpose of providing user notification of general data processing and AI inference routines (for example, if there is an AI inference routine for emotion, this should be disclosed in the notification).
 
_Example: As a subroutine of the privacy policy notification, a voice assistant asks if the user would like to know what inference routines are utilized.  The User responds, “yes,” and the voice assistant notifies the User of the voice inference routines being used (i.e. “voice speech-to-text only.” But if the voice assistant is also doing sentiment analysis, the response would be “voice speech-to-text and voice sentiment analysis.”)_

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