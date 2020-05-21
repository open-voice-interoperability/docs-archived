# 2020-05-15 Notes of the Technical Committee Meeting
Attendees: D. Cundiff (Chair);  J. Larson, N. Myers, M. Brinas-Dobrowski, J. Crabb, J-C. Junker, M. Frazzini, J. Iwasz, M. Buck, M. Saul, N. Latwis, M. Lewis, P. Bentsen, S. Baul, W. Angerer, M. Lens-Fitzgerald, J. Maas, A. Lee, N. Sharif, L. Lin, S. Nicholas (Linux Foundation), K. Dank, J. Stine. 

The meeting was brought to order at 08:31 CDT (US).  

J. Stine announced that the meeting would be managed in accord with the antitrust guidelines of The Linux Foundation, (https://www.linuxfoundation.org/antitrust-policy/), and that the meeting would be recorded (mp3 file found here:  https://drive.google.com/drive/folders/1J_XGKcVnHqyVdWiV9wYjwh8rO8HMCJ3t). 

1 Linux Foundation Definition of “Project”

S. Nicholas of The Linux Foundation reviewed the LF concept of Technical Charter, and the specific “Vocabulary and Definitions” charter now before the OVN Technical Committee.   He noted that the OVN has the ability to define and launch additional projects as needs arise.  There are three (3) primary reasons why a new project may be needed:
Different mission/scope 
IP framework needs to be different 
Overall constituency of developers needs to be different.

The OVN may need an additional project when the OVN identifies a standard that needs to be developed; at that point, discussion as to the need or a separate project is appropriate.

LF process for project definition/determination described by S. Nicholas as “light;” OVN urged not to let concerns about LF processes be a burden or slow things down.

Additional questions should be addressed to S. Nicholas or J. Stine. 

2 Update on OVN Communities and their Role

J. Stine described the creation, growth of OVN Communities – comprised of the voice developer-designer-strategist ecosystem, and now in overlapping Slack Channels:  Developers, Designer-Strategists, Europe, Health & Life Sciences, and Ethical Use. 

Each community headed by volunteer moderators; Developer Community moderated by Tech Comm participants J. Larson, J. Herndon, M. Lens-Fitzgerald. 

Those wishing to participate in the Communities should forward a request to J. Stine.

3 OVN Technical Committee Ways of Working

D. Cundiff led a discussion of the tools and processes to be used by the OVN Technical Committee.  There are 3 primary tools:  Gsuite: the current repository for meeting minutes and participant roster.  Let J. Stine know your Gmail email address to get added.  Slack: the current real-time messaging and document sharing tool.  With the exception of calendar/meeting notices, we will seek to migrate away from the use of e-mail. Let J. Stine know your email address to get added to Slack.  Github: the working document repository – where we do our work.
 
Let J. Stine know your github.com user name or share it in the Technical Committee slack channel 
OVN has a variety of repos. A few are currently marked as private but want to convert to open and goal to do this after we ratify the Master Plan document 
D. Cundiff demonstrated the use, processes within GitHub. ’d the process in Git
S. Baul noted he has Git access but hasn’t tried any of the PRs.  He is assuming this is OK and confirmed ok

A discussion of Tech Comm process, ways of working:
J. Larson spoke to the process for “opened up”  issues within GitHub related to the Master Plan.  These are tracked outside of the document itself and not a PR for the doc.  Per D. Cundiff: Participants can use the PR process to start a discussion about potential changes to a document vs opening an issue.  Participants can use an issue for dialog on something that is not quite firm or you have questions   Action:   need to formalize the process for issue management/discussion.   Likely part of the Tech Comm meetings going forward.  Will also need a process re: prioritization of issues.J. Stine to add this to the “How we work” document now in development. Action:  should GitHub training be desired, please let J. Stine know, he will setup a session. 

4 Review of the Technical Masterplan

D. Cundiff discussed the need, timing of another round of reviews to the Technical Masterplan, as found in GitHub.
Per D. Cundiff:  We want to get the Masterplan to a good, complete V1 –a released state.  Action: before the next Tech Comm meeting in 2 weeks, participants are to review the document, create PRs, add comments, and be prepared to ratify. 

Question from J. Larson:  should the Developer community review the vocabulary together to land on PRs/recommendations.    Yes, confirmed; this was agreed to as a good approach. 
Question raised by D. Cundiff, M. Brinas-Dobrowski regarding Master Plan visibility: private v public – aligned to keeping private for 2 months.   Comments:  M. Frazzini – 2 months; J. Iwasz  – 2 months of time to get this more complete would be good before repo goes public; M. Buck – supports 2 month timeframe; M. Lens-Fitzgerald – there is an opportunity for marketing OVN in general with this document.  Would be good if we announced that with an artifact that is public; S. Baul - reserve opinion at this point; J, Maas –agree with timeline and transparency with going public will help with momentum; J. Crabb – 2 months to allow for 1st Steering committee meeting.  

Initial Discussion: Top Three Projects / Working Groups

D. Cundiff, J. Stine introduced topic of top three projects.   D. Cundiff reminded participants that the Technical Master Plan is the highest level of what we’ll need to work on.  Action:  Please put ideas in Technical Committee slack channel before next meeting on 5/29.  Ideas, Comments:  

J. Larson: Specify a voice application in a vendor-independent manner that can be transformed to both a working Alexa or Google voice application. Recommend if we should develop a vendor-independent language for writing speech applications that can be translated to be executed on both Alexa and Google platforms. 

Evaluate Almond as a possible voice-assistant platform. Identify structures and processes useful in our work. Reference: ALMOND, THE OPEN, PRIVACY-PRESERVING VIRTUAL ASSISTANT https://oval.cs.stanford.edu/
 Dan responds: This is viable. I really like the interoperability theme. I think that’s future looking.  Is Stanford asking you to do this as part of prod management planning? 
Specify the vocabulary for a frequently-used business activity by constructing and deploying a skill (printing a portion of a conversation) An example approach is outlined in Telephone Commands in five languages, Final draft ETSI ES 202 076 V2.1.1 (2009-06) ETSI Standard Human Factors (HF); User Interfaces; Generic spoken command vocabulary for ICT devices and services https://www.etsi.org/deliver/etsi_es/202000_202099/202076/02.01.01_50/es_202076v020101m.pdf
 
P. Bentsen: [Enhanced/Augmented Audio (Audio Input/Voice Analysis): Specify audio solution requirements (HW, DSP, ASR/STT, AI, VRS, Wake Word, DB, etc.) to a level allowing for remote sensing, voice analysis and user/patient diagnostics, as well as interoperability and interfacing with relevant entities via VRS. This would obviously require CLEAR privacy controls/deterministic privacy and a heavy focus on privacy and data protection, cybersecurity and information security (Amongst use cases, are for H&LS Digital Health, Telemedicine/Remote Patient Monitoring and Public Safety support, potentially other verticals).[Privacy & Data Protection]

Privacy & Data Protection (+Deterministic Privacy): Specify Privacy & Data Protection requirements/baselines. Privacy and Data Protection should be foundational and pervasive in all parallel OVN efforts towards standardization and will likely become a regulatory requirement and enforced in the intermediate term for this space as well (GDPR, HIPAA/HITECH/HITRUST, etc).
Cybersecurity: Specify Cybersecurity and information security requirements/baselines. Cybersecurity and information security should be foundational and pervasive in the OVN efforts towards standardization (Security Architecture & Engineering, Communication & Network Security, Identity & Access Management, Asset/SW Security). 

M. Saul:  Focus on Voice Registry System ; +1 Nicholas Myers

M. Lens-FitzGerald: Not sure that VNS is the biggest priority –wants to know why we think this needs to happen; Holistic view on voice (what is lacking in the technical plan); - Alexa VS talking lights switches (command and control VS conversational services); - Trans modal; - International views and applications, ie China, India, Europe
- Other stakeholder ie governments, defense, enterprise; Local language/nlu/data sets; Synthetic voice ; Data /profile manipulation; Inclusion are just preferences; Suggested that Maarten open up issues for some of these.

M. Frazzini:  Privacy & Security, Interoperability, Voice Registry System 

J. Iwasz: Working committees should be defined as horizontal or vertical; Will be helpful to create working groups by industry; IVR systems.

M. Buck:  Wake words standards.

N. Myers:  Voice Registry System; Data privacy and Security; Voice “handbook” for the industry; Research on desired use of voice technology versus how it is being used today.

S. Baul: Voice Registry Service –wants to be sure that the “why” we are going this is strong as will be a lot of work and want to be sure that it will be used; Truth in what we are doing – how do we ensure that there is truth in adopting the standards.  What is the case for standards compliance?  Firms need to be motivated to adopt.  Standard in measurement of voice quality.

J. Maas: Will contribute via Slack. 

Process question- should we move these working group ideas from Slack to the MasterPlan?   Action:  if you find items missing from the Masterplan, then do a PR.  Please continue to post these in Slack 

Question:  A. Lee–is the OVN focused on a voice assistant, or does the scope extend to IVR’s, more operational use cases?   

6 Meeting Feedback:  Regarding applause, criticism, and recommendations going forward:  please place comments in Technical committee slack channel or relay directly to Dan via Slack if preferred.

Meeting adjourned at 10:01 a.m. Central Daylight Time. 

notes by Dank/Stine



# 2020-04-17 Notes of the Technical Committee Meeting:

- In attendance:  D. Cundiff, Chair; C. Wuttke; M. Brinas-Dobrowski.  B. Czechowicz; J. Larson; J. Herndon; J. Iwasz; L. Lin; M. Lens-FitzGerald; M. Buck; M. Frazzini; M. Saul; N. Myers; N. Sharif; P. Bentsen; S. Baul; S. Root; S. Prayaga; T. McElreath; V. Tai; K. Dank; J. Stine. 

Meeting commenced at 15:30 CET, 08:30 Central Daylight (US). 

WELCOME.  J. Stine opened the meeting, welcomed Tech Com newcomers.

ANTITRUST POLICY.   J. Stine announced that the meeting of the Tech Comm would be conducted according to the Antitrust Policy of The Linux Foundation, found here:  https://www.linuxfoundation.org/antitrust-policy/

REVIEW OF LOGISTICS / ACTIONS FROM PRIOR MEETING.  D. Cundiff reviewed the following:  Technical Committee setup in Slack.  Reach out if questions with getting access. Ensure you have access to OVN Github organization as most of our technical committee artifacts will be housed there.  If new to Git, go to github.com to sign up for a user name and relay that information to Dan/Jon.  Pull Request (PR) – if you want to make a change, have it reviewed and merged in.

REVIEW OF LINUX FOUNDATION PROJECT CHARTER.   On behalf of the LF’s Scott Nicholas, J. Stine reported; This is the official statement of what an official TLF project is. Scott has authored this –will review in following meeting as Scott unable to attend today.

MASTER PLAN – VOCABULARY REVIEW.   M. Brinas-Dobrowski led a continued v1 review of vocabulary as generated from prior conversations, and as captured in the Master Plan 1.0.  Reviewed list of vocabulary compiled to date. Action:  All - Please review and share any comments /edits or do a PR against the vocab doc.  

General Vocab – key updates since last meeting:  Conversational AI –Let’s align on this definition; Query; Automatic Speech Recognition; Component Vocab – key updates since last meeting; Natural Language Processing; Intent; Entity; Voice Registry System; Dialog Broker; Dialog Manager; 

Discussion: Interaction Model Concept – part of NLP but need to validate; Dialog Element –need to validate if needs to be added; 3 forms of interoperability – need further discussion before adding  (J. Larson); Domain skills – need to define and add.  Landed on Voice Application  (S. Prayaga); Dialog Broker – clarification on definition (N. Myers); Dialog Manager – clarification on definition  (N. Myers).  Media Player – specific functions on a platform level that cannot be done on a local level (voice application).   Aligned that this is part of dialog broker  (M. Lens-FitzGerald).  

MASTER PLAN 1.0.  D. Cundiff, M. Brinas-Dobrowski led an introduction, initial review of the Tech Comm Master Plan.  Shared document is a starting point for continued development, evolution. Will follow Symantec versioning scheme.  Goal is to break down the components in the doc to kick off work streams to accomplish.

Doc Overview: 

Solution/Principles: We will need to validate our standards by creating reference implementations; Can be implemented as open source or closed source products; Abstracted to the right level as to not too deeply specify particular technologies used to implement them; Has the ability to protect the privacy of the user AND the user can know where their privacy is protected or not – is discoverable; Standards can be implemented down to the individual –as low as localhost, a private network or as big as globally provided.

Discussion: M. Lens-Fitzgerald: appreciates the reference to the web and basing the work that we do on that; A lot has changed since the web beginning like privacy or inclusion.   If we look at the past, what can we learn from and add to our solution.  Center for Humane Technology.
 
John Iwasz - Heidi Culbertson is an excellent resource for input for voice application design for accessibility.  Many comments in chat in support of accessibility focus. Conclusiveness & abuse should be factored in.

 S. Prayaga: Interoperability /multiple assistants –how are we dealing with privacy and data management? 

M. Frazzini:  Great first draft.  As we discuss the important topic of privacy, we also need to talk about security.  Aligned that we need to add security as a principle. 
  
J. Iwasz: We should leverage existing /review existing standards such as NIST and determine what could apply to voice.

P. Bentsen:  Propose adding voice quality – may be necessary to review what quality measures or what quality of service needs to be in place in order for standards to be utilized (related to diagnostics on voice input).

Design:  Component architecture overview; Component Flow ; Channel TTS/STT; NLP.  NLP will determine your location and your who is being referred to.  

Voice Registry Service: Making list of invocation names public; Location sensitive; Is a global service 

J. Larson:  we should capture the requirements for the VRS.  Included in the master doc?  No, this will be done via technical  sub-committees as we break out the work and the VRS sub-committee will tackle.  Suggest adding to the master plan document how we will do the work –sub committees –in Abstract and we can build out further .


J. Herndon: As we break out the sub-committees-there will need to be interaction between /across sub-committees.  

NEXT STEPS AND ACTIONS.  Prior to next meeting – Committee members:  Please review the vocabulary list and share any comments /edits or do a PR against the vocab doc.  Please read Master Plan document  - and open  issues or do pull requests in Github.   Comment in slack if unable to use Github.  Come to the next meeting with an idea of which projects that should be priority projects for OVN to focus upon.  Think about what role you would like to perform within the Technical Committee as there are many opportunities.  Prepare for roundtable discussion as to your three highest priority projects).

MEETING ADJOURNED AT 17:00 CET, 10:00 Central Daylight US.

17 April 2020


# 2020-04-03 Notes of the Technical Committee Meeting
In attendance:

Dan Cundiff, Target (Chair); Christian Wuttke, Schwarz Gruppe; Mirko Saul, Schwarz Gruppe; Scott Nicholas, Linux Foundation; Jim Larson, SpeechTEK; Nick Myers, RedFox-ai; John Iwasz, Whetstone Technologies; Richard Vanderhorst, Wegmans; Alex Weidauer, Rasa; Lawrence Lin, China Netcasting Services Association; Maria Brina-Dobrowski, Target; Joel Crabb, Target; Kristi Dank, Target; Jon Stine, Open Voice Network. 

Meeting opened at 08:32 Central US.

WELCOME.   D. Cundiff opened meeting.

 REVIEW OF THE AGENDA.

STATEMENT OF ANTITRUST COMPLIANCE.  S. Nicholas affirmed that the meeting would operate under the Antitrust Guidelines of The Linux Foundation, as found here:  https://www.linuxfoundation.org/antitrust-policy/

LAUNCHING THE TECHNICAL COMMITTEE WORK.   D. Cundiff emphasized the importance of asynchronous team productivity outside of regularly scheduled meetings.   To do so, will use three primary tools:
Slack
GSuite Share Drive – used for documents that do not require team critique, editing, version control; a Share Drive file has been set up for the OVN Tech Comm team
Github -- Technical committee will use Github to track the work that we need to do as well as artifacts that need version control and markups/comments.  Tech Comm will follow a pull request (PR) approach for this.

OVN TECH COMM MASTER PLAN 0.1.   D. Cundiff, M. Brinas-Dobrowski reviewed 0.1 draft.   Document context: leveraged the research that has been done to date and is a summary of that information; seeks to be an artifact that lays out the technical opportunities for standardization. 
Does try to define or outline the standards at a high level.   Document components include abstract, principles, design, vocabulary , component architecture proposal, component flow,  
component details. 
Process for review:  Will be converted to markdown and placed in Github.  Link sent out via Slack in ~1 week.   Reviewers execute PR to add comments.  Next discussion on 4/17, with these objectives:  * review in more detail * ratify the components * get to a baselined Masterplan v1.0.0.

 VOCABULARY DESERVING OF MECE DEFINITION.   D. Cundiff led roundtable discussion; noted that, in first meeting, the Tech Comm aligned that defining our vocabulary made good sense to do at the start.  Since, Tech Comm members contributed vocabulary content to feed this discussion.    
D. Cundiff and M. Brinas-Dobrowski reviewed the vocabulary used in the 0.1 Masterplan document.  

Included: Utterance - spoken or typed phrases; Wake Word - a specific word that will catch the attention of the channel; Query - the words that the user is requesting to happen; Text-to-Speech (TTS) - TTS is a text converting to audio. It includes customized models to overcome common speech recognition barriers, such as unique vocabularies, speaking styles, or background noise; Speech-to-Text (STT) - STT is converting the response from an audio to a text; Channels – An interface and origin of communication. It is where the utterances originate; Natural Language Processing (NLP) - A service and a branch of artificial intelligence that helps computers communicate with humans in their language and scales other language-related tasks. NLP helps to structure highly complicated, unstructured human utterance and vice-versa; Intent - is a part of the structured machine translation. It is the identified action that the machine interprets based on the user's query; Entity - is a part of the structured machine translation. It is a custom level data type and considered a concrete value to associate a word in a query; Voice Registry System (VRS) - It is a global entity type in OVN and considered one of the most important offerings. It is a hierarchical registry system built on an open system similar to the Domain Name System (DNS). VRS transforms and associates the VRS names to dialog management endpoints, NLP providers, and the functionalities you get from the dialog broker. The VRS URL serves consistently regardless of the NLP.  Dialog Broker (DB) - It is responsible for providing the fulfillable intents available for a resolved VRS record (e.g. where resolved VRS record “Target”, it’s fulfillable intents might be “order product, check order status, add to shopping list”. These fulfillable intents can execute remotely on the DM or download locally on the device.  Dialog Manager (DM) - It handles the dynamic response of the conversation. It provides a more personalized response based on the action provided by the NLP to send back to the user
Roundtable comments, contributions:

M. Saul: Voice Name Systems – maps to VRS.  Open, Interoperability, Data Privacy.  

J. Larson: Assistant (agent) – maps to channel; Intent – see above. Agent Interoperability – an agent can be replaced by another agent –rename to channel interoperability; Platform Interoperability- agent can run different platforms; Component Interoperability – component can be replaced by another component; Wake-up word – maps to wake word; Wake-up word Registry – maps to voice registry system.

J. . Iwasz: Natural Language –maps to utterance; Voice Application – maps to dialog manager; Smart Speaker – maps to channel; Localization – internationalization, changing speech understanding and response to match local user.  The Synthesized voice –the voice that is typically used on voice channels in a text-to-speech scenario; Speech-to-Text-see above; Text-to-Speech –see above.
 
N. Myers: Utterance  - see above; Interaction Model – will need to define for us leveraging what google, etc. have.  Between the user and the channel; Artificial Intelligence – will need to define; Interactive Voice Response – will need to define but lower priority; IVR may be siloed to a channel/channel specific and OVN may cross channels; Meant for definition only, not for creating standards to IVRs; Conversational AI; Natural Language Understanding vs. Natural Language Processing – see above; Voice User Interface – maps to channel.
  
A. Weidauer:  Natural Language Processing –see above; Dialog Elements – the equivalent to HTML, header or footer or form/paragraph that make up the website.   For voice, we will need to define what we mean by Dialog Elements as most discussions are not 1 question and 1 answer.   For a non-linear conversation.    Text-to-Speech – see above.  Speech-to-Text – see above.  Conversational Interface – maps to channel. 

QUESTIONS AND OPEN ISSUES.

NEXT STEPS.  Publish meeting notes and first draft of the vocabulary.  Will be posted on GitHub so we can do PRs against to contribute.  If questions on Github and PRs, reach out to Dan. Members asked to review vocabulary and contribute via comments, issues, etc. In Github. Masterplan will be published and ask members to review ahead of 4/17 meeting.

Submitted
3 April 2020 

