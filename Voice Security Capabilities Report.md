## Voice Security Capabilities Report

### Open Voice Network, Privacy & Security Workgroup 

Maarten Lens-FitzGerald et al, 
Origin: Version 1, October 30th 2020, converted to markdown January 21th 2021


“Security is the chief enemy of mortals.”     

- William Shakespeare, act 3 of Macbeth

## **Summary**

Security of Voice Assistant Systems (VAS) is uncharted territory and needs more work than done for this report. What is done here is a good start and shows why the Open Voice Network (OVN) needs to play its independent and guiding role in the new channel of voice and the voice industry. The complete scope of voice security, from the person using it, the smart speaker, the connection ,to the Voice Assistant System and subsequent connected internal or external systems is large. The conclusion of the analysis done for this report is short and tangible.

The security capabilities that the Privacy and Security Workgroup recommended to scrutinize and develop are:

1. **Verification of the user:** The user is who he/she says she is.
2. **Verification of the Voice Assistant System:** The VAS is what it says it is.
3. **Verification of the process for the end service or device:** The user, the content & channel, and the VAS are verified and were encrypted.
4. **Content and channel encryption** between the person’s input device and the VAS.

Recommended next steps are ingternal and external review round to come to a validated result tyo determine next steps on.

## **Introduction**

The Open Voice Network Technical Committee asked the Privacy and Security Workgroup to identify, define, and prioritize capabilities of security in voice assistant systems. 

Maarten Lens-FitzGerald headed up the workgroup sprint together with the workgroup members to deliver the results as reported here. This work was done Spetember to November 2020.

The approach and way of working of the workgroup were to define important concepts like security, voice assistant system, voice security etc. And then analyze these with a security perspective. This report is the result of this work.

The results reported in this document were made possible by Jon Stine, Jim Larson, Jonathan Eisenzopf, Lawrence Lin, Mike Frazzini, Nick Myers, Shyamala Prayaga, Oita Coleman, Doug Rogers, and others. 

Contact Maarten Lens-FitzGerald at [maarten@lens-fitzgerald.com](mailto:maarten@lens-fitzgerald.com) if you have questions or remarks about this report. 

## **Voice Assistant Security Foundations**

Security is no easy subject matter. To grasp the material these 3 quotes from the book _Click Here to Kill Everybody: Security and Survival in a Hyper-connected World_ by Bruce Schneier, illustrated this for the workgroup.

### Three quotes

**Scope** 
“We need a name for this new system of systems. It’s more than the Internet, more than the Internet of Things. It’s really the Internet + Things. More accurately, the Internet + Things + Us. Or, for short, the Internet+ .”

**Trust** 
“Although we often don’t think about it, trust is critical to society’s functioning at all levels. On the internet, trust is everywhere. We trust the computers, software, and internet services we use. We trust the parts of the network we can’t see, and the manufacturing process of the devices we use. How we maintain this trust, and how it is undermined, are also critical to understanding security on the Internet+.”

**Complexity** 
“Everything about this problem [security ] is complex: the technology, the policy, the interaction of technology and policy. Also the politics, the economics, and the sociology. They’re complex in many dimensions, and their complexity is increasing over time. Internet+ security is what is known as a“wicked problem” —which doesn’t mean that it’s evil, but rather that it’s difficult or impossible to solve because it’s so hard to even define the problem and requirements, let alone create a useful solution.”


## **Computer Security**

What is computer security? [For this, we turn to the Encyclopedia Britannica](https://www.britannica.com/technology/computer-security): 

“Computer security, the protection of computer systems and information from harm, theft, and unauthorized use. Computer hardware is typically protected by the same means used to protect other valuable or sensitive equipment -- namely, serial numbers, doors and locks, and alarms. The protection of information and system access, on the other hand, is achieved through other tactics, some of them quite complex.

The security precautions related to computer information and access address four major threats: 

(1) theft of data, such as that of military secrets from government computers; 
(2) vandalism, including the destruction of data by a computer virus; 
(3) fraud, such as employees at a bank channeling funds into their own accounts; and 
(4) invasion of privacy, such as the illegal accessing of protected personal financial or medical data from a large database

The most basic means of protecting a computer system against theft, vandalism, invasion of privacy, and other irresponsible behaviors is to electronically track and record the access to, and activities of, the various users of a computer system. This is commonly done by assigning an individual password to each person who has access to a system. 

The computer system itself can then automatically track the use of these passwords, recording such data as which files were accessed under particular passwords and so on. Another security measure is to store a system’s data on a separate device, or medium, such as magnetic tape or disks, that is normally inaccessible through the computer system. Finally, data is often encrypted so that it can be deciphered only by holders of a singular encryption key. (See data encryption.)

Computer security has become increasingly important since the late 1960s when modems (devices that allow computers to communicate over telephone lines) were introduced. The proliferation of personal computers in the 1980s compounded the problem because they enabled hackers to illegally access major computer systems from the privacy of their homes. The development of advanced security techniques continues to diminish such threats, though concurrent refinements in the methods of computer crime (q.v.) pose ongoing hazards.”


## **The Description of Voice Assistant System**

[this section needs to be synced with the terms and definition workgroup results]

To make the security assessment, a shared view of what a Voice Assistant System (VAS) is needed. This description is the general and descriptive version. A system overview is described later in this report.

_Voice assistant system: A system where a user (primarily) uses his/her voice to interact with an automated conversational assistant for information or to control devices._

_The assistant responds to the user using verbal interaction, occasionally enhanced with visuals and visual interaction. The assistant system is controlled by an entity (any type of organization).  Typical components are:_

1. _Channel endpoints like a smart speaker or a mobile application._
2. _Wake word detection to activate the system._
3. _An ID system to identify the user._
4. _Automatic Speech Recognition to convert the user’s spoken words into written words._
5. _Natural Language Understanding to extract intents and meaning from these words._
6. _A back end to enable input and output, provide answers, or control the devices._
7. _Dialog Management to manage the conversation._
8. _Text to Speech and Voice Generation to respond._

## **Voice Assistant Security Definition**

What is security in the realm of voice assistant systems? This definition covers this. It is adjusted from [a NIST definition](https://csrc.nist.gov/glossary/term/security). Note that _Safety_ is added. This is due to the power of voice which can control machinery and devices.

_Voice assistant Security Definition: Protecting voice assistant systems, information, and channels from unauthorized access, use, disclosure, disruption, modification, or destruction in order to provide:_

_(A) integrity, which means guarding against improper information modification or destruction, and includes ensuring information non-repudiation and authenticity;_
_(B) confidentiality, which means preserving authorized restrictions on access and disclosure, including means for protecting personal privacy and proprietary information;_
_(C) availability, which means ensuring timely and reliable access to and use of information; and_
_(D) safety, which means ensuring human safety of the devices that are under the control of the automated assistant system._

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


## **Primary Actors & Assets of Voice Assistant Systems (VAS) Viewed Through a Security Lens**

**Summary**

To perform a risk assessment of a voice system overview the primary actors and assets are to be defined. For this, a simplified overview is made of the VAS. Each step lists the primary actors and assets as viewed through a security lens. An actor is a person or entity that is most active and or relevant (from a security standpoint) in that step. Also, the primary assets are listed for each step. An asset is an important component or a valuable ‘thing’ to protect or maybe under threat. 

![](https://github.com/open-voice-network/docs/blob/master/Voice%20Security%20Capabilities%20Report.assets/Actors%20and%20Assets.png)

**1.  Person** 
The person or user initiates a conversation with a VAS entity through the endpoint. 

**Actor**:

The user talking with the VAS.

**Assets**: 

- Personal assets like money, passwords, bank accounts, and relationships. 
- Personal data in any form 
- Voice signature: the unique digital pattern of one’s voice. Highlighted in italics due to the unique risk it poses in a Voice system environment. 

**2. Channel and endpoint devices** 
The user talks through a smart speaker, a smart device, a mobile app, a website, a phone, or otherwise to the VAS. 

**Actors**: 

- Person. The person or user initiates a conversation with a VAS entity through the endpoint 
- Channel (connectivity) providers (telco and otherwise). Connectivity is the internet connection between the endpoint and the VAS. From the backbone connected to the system server (and the many hops included there) to the internet provider to the home to the wifi to the device.
- Hardware manufacturers. The hardware needed to make the endpoint possible like the smart speaker, the smart device, the phone, the (home) computer, or laptop. Also routers, switches, and repeaters used for the channel. All these manufacturers are actors.
- Software provider. All hardware has software to make it run in general and these are provided by an entity. 
- VAS operator. The assistant part of all this endpoint and channel hardware is managed by this operator.

**Assets**: 

- Wifi and network channel. This enables the system to connect to the cloud and the VAS
- Mics, speakers, and chipsets. For each hardware endpoint the smart mics, speakers, and chipsets that control them are unique assets. 
- VAS edge work. This is the assistant specific software present at the endpoint (on the edge). 

**3. Voice Assistant System** 
The system of components that make up a Voice Assistant System. 

**Actors**:

- VAS operator. This is the entity and the person responsible for the VAS and its operation. 
- External component providers. Some components of the VAS may be provided by other entities. 

**Assets**: 
 VAS system. Literally, all components of the VAS are assets potentially at risk and especially: 

 - ID system. This system enables the identification of the user. 
 - Voice generation. This is the component that gives the voice its unique signature. 
 - Internal and external backend integrations. The systems connected to the VAS to provide service or (device) access. 
 - External components for VAS. The VAS components provided by other entities. 

**4. Internal back end services and devices** 
The VAS owner entity exposes internal backend services and/or devices to the VAS so users can access these. For example, the Alexa Microwave or Amazon’s shopping skill on Alexa. 

**Actors**: 

- VAS operator. The entity and the person responsible for the VAS and its operation. 
- Device manufacturer. The manufacturer of the device for the VAS owner and operator. 
- Device software provider. The device software provider. 
- Service operator. The person and department who is responsible for the provided service.  For example the product owner of the Amazon shopping feature on Alexa. 
- Device operator. The person and department responsible for the device. For example the product owner of the Amazon microwave with Alexa. 

**Assets**: 

- Personal data of VAS user. This is all data particular to the user going through this part of the system or is accessible through this part, including context data and usage patterns. 
- Provided entity services. For example the Amazon inventory accessible through Alexa. 
- Devices such as the aforementioned microwave. 

**5. External services and devices** 
Access to services and devices by parties other than the VAS owner and operator. For example, Target using Amazon Alexa’s skill voice apps. 

**Actor**: 

- The external entity offering their services through the VAS.
- VAS operator. The entity and the person responsible for the VAS and its operation.
- Device manufacturer. The manufacturer of the device for the VAS owner and operator.
- Device software provider. The device software provider.
- Service operator. The person and department at the external entity who is responsible for the provided service. For example the product owner of the Target shopping skill on Alexa.
- Device operator. The person and department who is responsible for the provided device at the external entity. For example the product owner of the Hue lights. 

**Assets**:

- Personal data of VAS user. This is all data particular to the user going through this part of the system or is accessible through this part. including context data and usage patterns.
- Provided entity services for instance the Target shopping skill on Alexa.
- Devices. Not just Hue lights but also heart pumps or cars. This asset has been marked as high risk. 

## **Threats & Vulnerabilities unique to Voice**
<<Generally speaking, a vulnerability is a weakness in a system, and a threat is is when some agent utilizes a vulnerability with the result being a violation of security policy (not always intentionally).  Because of that dependence, I found myself reading those sections in the paper backwards ( because the threat is listed first, then the vulnerability). >>
**Summary** 
For each of the five system components defined in the simplified Voice Assistant System overview, the threats and vulnerabilities unique to voice are ascertained. Three threats are highlighted as well as one vulnerability as they are seen as extra important in the analysis. 

![](https://github.com/open-voice-network/docs/blob/master/Voice%20Security%20Capabilities%20Report.assets/Threats%20%26%20Vulnerabilities%20unique%20to%20Voice.png)



**1. Person** 
The person or user initiates a conversation with a VAS entity through the endpoint. 

**Threats**: 

- Misdirection due to a malicious entity operating a VAS with synthetic Voice. Misdirection: getting people to enable harm by unauthorized access, use,  disclosure, disruption, modification, or destruction 

**Vulnerabilities**: 

- People's gullibility 
- Accidentally overhearing proprietary information 

**2. Channel and endpoint devices** 
The user talks through a smart speaker, a smart device, a mobile app, a website, a phone, or otherwise to the Voice Assistant system. 

**Threats** 

- Unauthorized channel and endpoint device access to do harm. For example someone accessing the contents of the conversation to capture private information like bank details. 
- Disruption or destruction by a a malicious entity (for instance someone unplugging or breaking a device) 

**Vulnerabilities** 

- Security processes of  the channel operators (wifi operators and telecom providers for example)  and the endpoint devices (hardware, software and edge part of the VAS)  

**3. Voice Assistant System** 
The system of components that make up a Voice Assistant System. 

 **Threats** 

- Harm to all subsystems, _especially ID system, and speech generation._  

For example in the case of hacking the VAS ID system, a VAS is fooled by someone to think they are dealing with a specific user when this isn't so. In mobile such hacks are done by spoofing a sim card. An example of hacking a VAS speech generation, is a VAS operated by malicious entities sounding like your bank assistant and getting you to send over money. This is similar to phishing emails or whatsapp messages.  

- User Voice impersonation._ The example here is that a malicious entity has the ability to fool the VAS system by impersonating the user's voice. This is similar to deep fake video’s or synthetic voice generation. 

**Vulnerabilities** 

- Security processes of VAS operators. 

**4. Internal back end services and devices** 
The VAS owner entity exposes internal back end services and/or devices to the VAS so users can access these. For example, the Alexa Microwave or Amazons shopping skill on Alexa.  

**Threats** 

- Misuse with the intent to harm internal services and devices. 

**Vulnerabilities** 

- Security processes of overarching entity and internal VAS operators as well as service and device operators.

**5. External services and devices** 
_Access to services and devices by parties other than the VAS owner and operator._ For example, Target using Amazon Alexa’s skill voice apps. 

**Threats** 

- Misuse with the intent to harm external entities’ services and devices 

**Vulnerabilities** 

- Security processes of VAS entity and external entity 
  Does an external entity trust or atest ID process and other verification and security steps of the VAS operators?_ 

## **Security Capabilities Unique to Voice**

**Summary** 
To assist in clarifying the scope of security capabilities that are unique to voice the Privacy & Security Workgroup has developed a working overview that demonstrates the flow of voice-specific data between actors. This overview here is a simplified version that illustrates one possible arrangement of actors and security capabilities involved in a typical conversation between a user and a Voice Assistant System (VAS).  \

**Overview** 

![](https://github.com/open-voice-network/docs/blob/master/Voice%20Security%20Capabilities%20Report.assets/Security%20Capabilities%20unique%20to%20Voice.png)

*Please refer to figure above 

1. **Person**
   The “Person” or user initiates a conversation with a VAS entity. 
   The user is verified to prove who they say they are via account authentication, a biometrics signature, or a unique verbal PIN/ID. 
2. **Channel & Content Encryption**
   Note that endpoint devices such as smart speakers, mobile apps, or otherwise are in this overview seen as part of the channel. 
   As the “Person” or user issues their request their voice communication (unique voice data) is sent to the VAS entity through an encrypted channel using the [Advanced Encryption Standard](https://en.wikipedia.org/wiki/Advanced_Encryption_Standard) (AES) with 256-bit keys or the newer [NaCl Networking and Cryptography] \(https://nacl.cr.yp.to/features.html) Library to ensure that communication between the person and the VAS entity is secure.
3. **Voice Assistant System/Entity**
   The voice communication is sent via the encrypted channel to the VAS entity. This can be a command like “Alexa, lights on” or a request: “Google, ask Rabobank how much money I have”. 
   The VAS entity is verified to confirm that the VAS is what it says it is including external services. This verification can be achieved through a unique ID for the VAS entity. 
   Once verified the voice communication is passed through a connection to external services and devices. This inter-cloud or system connection is not in scope for this voice specific security analysis as it falls under standard security operating procedures. 
4. **External Services and Devices**
   The communication is sent via a normally operated connection to the external services and devices. These can be Hue Lights, connected vacuum cleaners, or the connection to your bank which serves up how much is in your account. 
   Once the communication resolves to an external service or device these services and devices are verified to confirm security along the entire process. Voice communications that are sent to external services and devices can be verified using a VRS system or some other type of unique registration ID to confirm security. 

## **The Four Voice Security Capabilities**

The security capabilities of Voice Assistant Systems as shown in the aforementioned analysis comes down to the following four: 

1. **Verification of the user:** The users is who he/she says she is
2. **Verification of the Voice Assistant System:** The VAS is what it says it is
3. **Verification of the process for the end service or device:** The user, the content & channel, and the VAS are verified and were encrypted.
4. **Content and channel encryption** between the person’s input device and the VAS.

These capabilities as well as the analysis work running up to this, is the start for the next steps.


## **Recommended next steps**

1. Review of this report by 1 OVN members, 2: close security experts, and 3) leading security experts. Update where applicable.
2. Publish to inform and promote OVN work.
3. Work on _how_ these capabilities could be created

**Remarks as noted in Tech committee presentation november 2020** 

what voice specific questions must we express 
what design issues/guidelines should we expect to follow 

specific use cases (understand inside and out) 
manipulation / persuasion 
make security language so people can IMPLEMENT 
protection data and identity PERSONAL 

TRUST LINK 
Security Level indication 
authentication 
project functions 
auditability 
national cyber security 
