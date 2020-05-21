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



# 2020-04-17:
- 

# 2020-04-03:
- TODO
