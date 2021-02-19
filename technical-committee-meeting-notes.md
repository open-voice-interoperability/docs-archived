# 2021-02-19 Notes of the Technical Committee Meeting 

Attendees:  J. Larson, K. Dank, J. Stine, M. Brinas-Dobrowski,  J.Crabb, O. Coleman, M.Lens-FitzGerald, C. Wuttke,  S. Prayaga, D. Cundiff,  M. Frazzini, M. Aretoulaki, R. Nathenson

The meeting began at 9:02 am CT

### Antitrust statement and notice of recording  -- J. Stine 

### Review of the agenda, purpose of and expectations for the meeting  -- J. Stine

### Introductions of new participants 
* Maria Aretoulaki – Voice AI Consultancy 

### OVN Vocabulary Document 
* 1.0 Vocabulary document available at this [link](https://github.com/open-voice-network/docs/blob/master/vocabulary.md)
* Workgroup moderators and communities need to incorporate this vocabulary into their documents by end of March in the Q1 deliverables
* Reminder – if you have desired changes to this document, please follow the pull request process 

### Reminder:  Work Group Deep Dives begin March 5
* March 5 – Privacy
* March 19 - VRS
* April 2 – Security 
* April 16 – Architecture 

### Quarterly milestone review – Q1 Red, Yellow, Green
* VRS
    * Publish schema 1.0 – RED
         * need to determine if have full scope of decisions 
    * Process – GREEN 
* Architecture 
    * Define extensible strategy for evolving components –YELLOW
* Privacy
    * Voice privacy guidelines 1.0 – GREEN
    * Working with workgroups and communities - GREEN
* Security
    * Voice Security Guidelines 1.0 – GREEN
    * Working with workgroups and communities – YELLOW 
    * Friends and Family Review –shift to Q2 
* Privacy and Security Research 
    * High Level Overview –GREEN

### News and New Items – Trends, thought-provokers, core questions 
* Phil Archer presentation in VRS workgroup meeting was very useful.  The recording is in the google workspace 
* Our response to the question of “Is OVN a standards organization” needs some clarification.    
    * It’s a bit open at this point
    * Some things that we may create may become standards such as standards around VRS
    * OVN may end up becoming a standards body and if that becomes reality, we’ll have to evolve to that    
    * The Linux Foundation will play a role in this as well 
    * Our defined process for publishing standards has been reviewed by the Steering Committee and will be brought back to an upcoming Technical Committee meeting for transparency 
* Electronic Frontier Association proposal that seems to benefit all parties on how to reset the controls that large voice organizations have.  We may benefit from understanding this.  Jon will share it out on slack

Meeting adjourned at 9:52 ct



# 2021-02-05 Notes of the Technical Committee Meeting 

Attendees:  J. Larson, K. Dank, J. Stine, M. Brinas-Dobrowski, N.Myers, J.Crabb, D. Rogers, O. Coleman, M.Lens-FitzGerald, C. Wuttke, S. Baul, S. Prayaga, D. Cundiff, P. Gopal 
	
The meeting began at 9:02 am CT

### Antitrust statement and notice of recording  -- J. Stine 

### Review of the agenda, purpose of and expectations for the meeting  -- J. Stine

### Proposed Change: Technical Committee Agenda Going Forward –J. Stine 
 * Shift in Tech Comm Agendas starting 19 February 2021
 * Continue to meet every 2 weeks 
 * Workgroups will report progress against published quarterly milestones with Green, Yellow or Red 
 * One Workgroup will be asked to provide a 30 minute “deep dive” 
    * Artifacts for which they wish review and comment 
    * Key WG strategic questions of definition, architecture, scope
    * Implications for other work groups or OVN at large
    * Resource requirements:  bring proposals 
    * New discoveries, insights or items that don’t fit work group scope and needs discussion 
       * Dan to create a new slack channel to track these types of items 
 * 19 February -  Security Section:  Privacy and Security Work Group
 * 5 March -  The components of VRS:  VRS Work Group
 * 12 March - Privacy Section:  Privacy and Security Work Group
 * 26 March - How agents share dialogues:  Architecture Work Group 

### Reminder:  Q1 Milestones
* VRS goals: 
   * Publish schema 1.0 
   * Implement agile practices
   * Grow VRS participants –See Maria if you want to join
   * Define 1.0 user scenarios with interface to other components
   * Create VRs VMP by EOQ3
   * Research for VRS

* Architecture Work Group Goals:  
   * How to share artifacts among voice assistants
   * Intent Manager requirements definition 
   * Enforcement mechanisms for privacy guidelines 

* Privacy Work Group Goals: 
   * Voice Privacy Guidelines 1.0 published for review 
   * Present Voice Privacy Guidelines to OVN workgroups and committees 
   * By Q1 –March 2021, Voice Privacy Guidelines 1.0 completes first round of review with “friends & family” 
   * Github integration 
   * Voice Privacy Guidelines 1.0 circulated to 2-3 industry groups 
   * Voice Privacy Guidelines 1.0 published for external review 
   
* Privacy and Security Research Goals: 
   * Create high level overview of privacy and security policies 
   * Publish draft of high level overview
   * Stretch goal:   development of standard certification for voice privacy and security
   * Research, define and prototype access control mechanism by Q3 end 

 * Security Work Group Goals:  
   *  Voice Privacy Guidelines 1.0 proposal for review
   *  Present voice security guidelines 1.0 to OVN workgroups 
   *  By Q1 March 2021 Voice Security Guidelines 1.0 completes first round of review with “friends and family” 

### Progress Reports by Tech Comm Work Groups: 
 * VRS –M. Brinas-Dobrowski 
   *  Finalizing first schema and swagger 
   *  Practicing good processes for review and feedback and git issue management
   *  Creating an architecture decision log to enable debate, ratification and tracking 

 *  Architecture Components – J. Larson
    * Intent broker and VRS 
      * met to resolve questions/problem intent broker to solve, and how intent broker relates to VRS
      * Recommendation:  use Suzanne scenario to walk through VRS related components interact 
    * Created ‘play pen’ architecture (working architecture) 
    * Will create scenarios for handing off control among voice apps 
    * Will assess the 4 important layers of artifact/packets exchanged among components

 * Privacy –Security- M. Frazzini, M. Lens-Fitxgerald, N. Myers
   * Security:  
     * Document in git and is being reviewed and getting some comments 
     * Will be assessing threat analysis based upon feedback 
     * Vocabulary synchronization in progress 
     * Version 2.0 of the document in progress 

   * Privacy: 
     * Complete guidelines and capabilities diagram 
     * Github document formatting progress  
     * Circulate for feedback 

   * Privacy and Security Research: 
     * Planning out research to enable completion by end of February 5, 2021
     * Start on high level overview in March 
     * Research on OVN template for privacy policy that can be used as guidance for voice industry 
 
### New Insights: 
  *  Apple launching new AR glasses and have a lot of control the mobile app space.  Good food for thought  -do we want apple to control the AR industry? 
  *  Apple creating its own search engine to be a layer over the web with Siri
  *  Article in Insiders newsletter about the slowing down of voice market (skills, apps).  Implication is on the enterprise side

### Summation and Next Steps: 
*  Reminder –new rules in git to prohibit pushing to master without a PR 

Meeting adjourned at 9:52 ct



# 2021-01-22 Notes of the Technical Committee Meeting 

Attendees:  J. Larson, M.Frazzini, K. Dank, J. Stine, M. Brinas-Dobrowski, N.Myers, J.Crabb, D. Rogers, O. Coleman, M.Lens-FitzGerald, C. Wuttke, A. Fricke, S. Baul, S. Prayaga, D. Cundiff
	
The meeting began at 9:03 am CT

### Antitrust statement and notice of recording  -- J. Stine 

### Review of the agenda, purpose of and expectations for the meeting  -- J. Stine

### Plan 2021 Overview, OVN – J. Stine 
OVN Growth, fiscal strength
  * Industry 0decosyste recognition 
  * Material results in the 12 months
    * Publication of initial proposals
    * VRS reference implementation(s)
    * Test-reference implementations of proposed OVN phase 1 standardized interfaces 
    * Commercial data ownership –test reference implementation 
    * Test –reference implementations of technical implications of proposed OVN privacy and security guidelines 
    * OVN enterprise guide to privacy in voice technology completes first round of industry association and legal review 

### Plan 2021:  OVN Process 
* Technical committee and work group management:   Will be Github centric in 2021 
* All work groups issue and milestone management will work within the Tech Comm Backlog project – one version of work to be done 
* Recommended best practices: 
     * Begin meetings with review of outstanding issues and prioritization
     * Close meetings with documentation of outstanding issues 
     * Invite asynchronous individual or small team work on specific issues or review of specific documents 

### Plan 2021, Technical Committee:  thoughts and observations – D. Cundiff 
 * We will need an onboarding process for new participants where we walk them through the backlog and understand where and how they want to participate   
 * Will need to share working group overviews and where they need help and solicit participation 
 * Following git best practices is of utmost importance 
 * VRS working group is setting good examples and best practices with regard to process and focusing on the things that matter 
 * There are many things that the OVN teams could care about, standardize, and work on.    It is important that we stay focused on the essential things that have strategic value on what we need to accomplish.    We are making process in this space and the discussions at the last Architecture meeting are good examples  

### Plan 2021, by Tech Comm Work Group: Introduction to POR development process – O. Coleman 
* Oita worked with the leads of the workgroups to create a plan of record (POR) 
* POR identifies the monthly and quarterly deliverables for each workgroup that will be put into git as milestones for tracking purposes 
  
 * VRS goals: 
     * Publish schema 1.0 
     * Implement agile practices
     * Grow VRS participants –See Maria if you want to join
     * Define 1.0 user scenarios with interface to other components
     * Create VRs VMP by EOQ3
     * Research for VRS
  * VRS Intersections: 
     * Architecture group
     * Intent broker 

  * Architecture Work Group Goals:  
     * How to share artifacts among voice assistants
     * Intent Manager requirements definition 
     * Enforcement mechanisms for privacy guidelines 
  * Architecture Work Group Intersections: 
    * VRS workgroup -Intent broker
    * Privacy/Security workgroup –privacy guidelines enforcement 

  * Privacy Work Group Goals: 
    * Voice Privacy Guidelines 1.0 published for review 
    * Present Voice Privacy Guidelines to OVN workgroups and committees 
    * By Q1 –March 2021, Voice Privacy Guidelines 1.0 completes first round of review with “friends & family” 
    * Github integration 
    * Voice Privacy Guidelines 1.0 circulated to 2-3 industry groups 
    * Voice Privacy Guidelines 1.0 published for external review 
  * Privacy Work Group Intersections: 
    * VRS and Architectures review of/input to Voice Privacy Guidelines 

  * Privacy and Security Research 
    * Create high level overview of privacy and security policies 
    * Publish draft of high level overview
    * Stretch goal:   development of standard certification for voice privacy and security
    * Research, define and prototype access control mechanism by Q3 end 

  * Security Work Group Goals:  
    *  Voice Privacy Guidelines 1.0 proposal for review
    *  Present voice security guidelines 1.0 to OVN workgroups 
    *  By Q1 March 2021 Voice Security Guidelines 1.0 completes first round of review with “friends and family” 

### Summation and Next Steps 
  * Reminder that pull request reviews do take some time and we now have a backlog –we will work through that now and the feedback will speed up 

Meeting adjourned at 9:56 am CT



# 2021-01-08 Notes of the Technical Committee Meeting 

Attendees:  J. Larson, M.Frazzini, K. Dank, J. Stine, M. Brinas-Dobrowski, N.Myers, J.Crabb, D. Rogers, O. Coleman, J. Sedivy, D. Ryder,  M. Kanagarajanramakrishnan

The meeting began at 9:02am CT

### Antitrust statement and notice of recording  -- J. Stine 

### Review of the agenda, purpose of and expectations for the meeting  -- J. Stine
* Today’s purpose:  Reacquaint, Realign, Set the agenda for Q1

### Open Items/Issues to Review – J. Stine 
* No issues reported 

### 2021 Current State and Plan –expectations overall – available resource for Tech Comm investment 
* Plan 2021 work group deliverables –due January 15th 
  * Deliverables 
  * Milestones and dates 
  * Dependencies 
  * Resource requirements 
* Budget 2021: work group resourcing 
  * Think about where your work group could be accelerated with contracted resources 
  * Process:  workgroup to tech committee to steering committee for endorsement (Prioritization will be required) 
* Process 2021 GitHub-centric development an issue management 
  * Ensure that we have a single record of OVN truth 
  * Enable easy review and comment 
  * Industry standard 
  * 2 classes setup next week –See Jon to get included (sessions will be recorded) 

* One Year from Now:  the Open Voice Network in December 2021
  * OVN Growth, fiscal strength
  * Industry 0decosyste recognition 
  * Material results in the 12 months
    * Publication of initial proposals
    * VRS reference implementation(s)
    * Test-reference implementations of proposed OVN phase 1 standardized interfaces 
    * Commercial data ownership –test reference implementation 
    * Test –reference implementations of technical implications of proposed OVN privacy and security guidelines 
    * OVN enterprise guide to privacy in voice technology completes first round of industry association and legal review 

### January-early February agendas by Work Group 
* VRS work group 
   * Finishing Q4 work and fully using GitHub
   * Finalizing the integration of VRS with other components – version 1.0 of VRS swagger and problem statement 

* Architecture work group 
  * Working with VRS work group to identify missing components for VRS to be successful 
  * Component artifact –what data is shared and by what components and format of the data 
  * Shifting to weekly meetings vs bi-weekly 

* Privacy and Security work groups 
   * Reviewing and revising initial privacy guidance –including examples 
   * Reviewing privacy diagrams and models from the architecture work group 
   * Reviewing common baseline of privacy and security guidance 
   * Leveraging GitHub 
   * Start to circulate and get feedback from OVN workgroup and some external resources 
   * Privacy and Security workgroups considering merging some guidance due to commonality 

### Open Items, questions, comments, criticisms
*  Status of OVN’s interaction with Voice Lunch group?  
   * The interaction model is being defined yet.  Is on the Outreach committee’s task list for January

Meeting adjourned at 9:47am CT



# 2020-12-11 Notes of the Technical Committee Meeting - The 2020 Review; the 2021 View

Attendees:  J. Larson, M.Frazzini, K. Dank, J. Stine, M. Brinas-Dobrowski, N.Myers, J.Crabb, D. Rogers, S. Prayaga,  O. Coleman, D. Cundiff, A. Fricke, C. Wuttke, P. Bentsen, J. Croyle, J. Sedivy, S. Baul, D. Attwater 

The meeting began at 9:01am CT

### Antitrust statement and notice of recording  -- O. Coleman
### Review of the agenda, purpose of and expectations for the meeting  -- D. Cundiff 
### The YE 2020 Report
  - Technical Committee 2020-2021 Standards Development Priorities 
    - Enterprise Data Ownership
    - Destination Registry:  A DNS for Voice 
    - Open Voice:  Assistant Interoperability 
    - Voice-Specific User Privacy and Security 
 
### Next Steps Report:
  - VRS Work Group
    - Reacting to the feedback and take aways from the last review 
    - Next step is to identify the integrating components of VRS
    - Reorganizing working team into scrum style to allow for more participation 
    - [Link to VRS git doc](https://github.com/open-voice-network/docs/blob/master/components/voice_registry_system.md)
  - Privacy work-stream within the Privacy & Security Work Group    
    - Near term next steps/in progress –internal reviews and iterations focusing on completing good examples of guideline points presented to the technical committee and then present to all of the workgroups for feedback
    - Also working on converting google doc to MD and getting into git 
    - Longer term goals for 2021:
      - Industry group circulation for feedback and refinement with the goal of endorsement 
      - Broader publication of voice privacy guidance 
      - Stretch goal for 2021 –Development of real standards and draft certification for voice privacy.  Will need additional resources for this 
  - Security work-stream within the Privacy & Security Work Group
    - Group is updating the document with the feedback from last presentation and doing internal workgroup review
    - Expectation is external review and presentation to follow 
  - Architecture Work Group
    - Push the 4 component-bucket framework forward to support interaction among voice apps 
      - Define Voice Agent Finder 
      - Review and refine the 4 component-bucket framework 
      - Consider Voice log manager 
      - Output will be documentation and then to determine next steps
    - Work the core components 
      - Define terms
      - Determine roles and responsibilities for each 
      - Define template for describing core components 
      - Survey existing open source projects (to start with ) for potential core components –focusing on the inputs/outputs
      - Publish for review
      - Build a reference platform consisting of core components (this will take some additional discussion with the Technical Committee) 
      - Define measures of success 
  - Vocabulary Reconciliation Task Force
    - Group met and reviewed integrated list of terms from the Master Plan, VRS document and other terms submitted 
    - Discussed terms that are related or overlapped –about 50% way through the terms 
    - Work will continue next week with the goal to have 1 single location to find terms (likely in the master plan) 

### Organizational Review:  J. Stine
   - Currently 4 sponsors 
   - Discussions in progress with variety of potential sponsors 
   - Working affiliations with many organizations 
   - Developer/Designer communities established 
   - Thank you! 

### December 15, 2020 OVN Annual Meeting – Please attend if you can

Meeting adjourned at 9:45am CT 



# 2020-11-20 Notes of the Technical Committee Meeting 

Attendees:  J. Larson, M.Frazzini, K. Dank, J. Stine, M. Brinas-Dobrowski,  M.Lens-FitzGerald, N.Myers, J.Crabb, D. Rogers, S. Prayaga, R.Nathenson, O. Coleman, D. Cundiff, A. Fricke, C. Wuttke, I. Mez, J. Eisenzopf, P. Bentsen

The meeting commenced at 09:03 Central Standard time (US). 

### Antitrust statement and notice of recording – J. Stine 

### Review of the agenda -- D. Cundiff

### Ways of Working and Steps Forward -- J. Stine

J. Stine presented and spoke to an overview of the next steps that Work Groups may take.  Three key take-ways:  1) Work Groups will be asked to meet at least one more time to determine next steps.  2) Next steps could include a proposal to the Tech Comm (and then, potentially, the Steering Committee), or additional development work.  3)  The determining question of the Technical Committee (and the Steering Committee) will be this:  is this worthy of (and ready for) investment of time/personnel/monies en route to standardization?  
 
### Report from the Architecture Work Group: – J. Larson

J. Larson presented a summation of the work to date of the Architecture Work Group.  
* An important market transition is driving the need for this review:  current and anticipated growth of independent voice assistance.  
* Problems to be resolved:  development complexity, inconsistent terminology, reusability of components, extensibility, and interoperability of assistants.
* Ecosystem and business benefits of resolution:  speed, accelerate the creation of new and innovative speech applications; enable enterprises to build once and use many; create a standards-based foundation for commercial innovation, differentiation.
* Architecture Work Group remit:  identify, define, and prioritize common voice assistant components for potential standardization.
* A 1.0 definition of a reusable component was presented: defined by input and output, defined as a collection of related functionalities, defined as flexible, and able to be used in many configurations, defined as a building block for applications-assistant creation.
* A generic template of a reusable component was shown.
* In reaching this point, the Architecture Work Group (AWG) had reviewed a sampling of assistant architectures, and components within.  Those reviewed included that shown in the OVN Master Plan, and from the W3C Voice Interaction Community, David Attwater and Jonathan Eisenzopf, and from Dr. Monica Lam of the Stanford OVAL project.  The AWG had also discussed potential new components (per Voice Registry System conversations).
* The Architecture Work Group presented its 1.0 roadmap for component assessment and standardization.  For a detailed review, please see https://github.com/open-voice-network/docs/blob/master/Architecture%20Work%20Group%20Working%20Draft%202020.11.18.md.
* The AWG proposed two new components:  A "voice agent finder" for an anticipated Voice Registry System, and for purposes of user-managed rivacy and consent, an Access-Consent Control Guard, as inspired by the Stanford OVAL Almond architecture.
* The AWG noted four major outstanding questions:  1) the component(s) that should resolve VRS-centric search; 2) how components may be made (or defined in a way to be) future proof; 3) how to proceed forward with minimal viable components (such as ASR, NLU, TTS, Dialog Manager); and 4) the choice of the next component to refine.
* Going forward, the AWG suggested five next steps:  1) establishment of a 1.0 definition criteria, with an emphasis upon future-proofing; 2) integration of AWG work with that of the Privacy and Security and VRS Work Groups; 3) selection of first components for detailed definition; 4) initiation of outside review, and development of artefacts worthy of a RFC; 5) initiation of Q1 2021 planning for prototype-MVP testing. 


### Report from the VRS Work Group  – M.Brinas-Dobrowski
* Goal – To make a decision if there is a market need/opportunity for a global platform voice registry 
* Terminologies 
* Problem
  * Setup Mode 
  * Runtime Mode 
   * No consistent experience
   * Lack of standards 
   * No interoperability  
   * No consistency or transparency on disambiguation 
* Recommendations 
  * Advocate to stand up a neutral and single decentralized registry for voice application –the Voice Registry System 
* Architecture 
  * Arch guiding principles 
    * Single repository 
    * Loose coupling 
    * Event driven 
    * Availability and partitioning eventual consistency 
    * Interface segregation
    * Automation (CICD, etc.) 
* Roles & Responsibilities 
  * Be neutral and single decentralized registry for voice application  
  * Create voice application standards to provide a consistent experience 
  * VRS is NOT responsible for the interpreting of the intent of the user 
  * VRS can hold various attributes regarding the voice applications, such as name, alternative names, category, geolocation 
  * VRS can receive inputs like the channels current location but is NOT responsible for storing its preference 
  * VRS names can have synergies 
* Summation: 
  * Please review and add comments in git
  * Next Steps:  Each work group decide how this impacts their work 
* Discussion: 
  * Disambiguation is at domain level 
  * The Disambiguation problem will need to be broken down into multiple sub-problems 
  * If VRS not responsible for interpreting intent, how will it get to the destination?   -Additional discussions in the Architecture Group
  * Should we add the support of different languages?   This will be folded into the requirements 
  * VRS should be considered an Explicit request registry 
  * Where does disambiguation occur?  The conversation platform owns that with aid from VRS  
* [Link to VRS Presentation](https://docs.google.com/presentation/d/16kVg-PkoaWQwX-lRskirioBXL5wXg9--doJFLE8jWI8/edit#slide=id.p)  
* [Link to VRS git doc](https://github.com/open-voice-network/docs/blob/master/components/voice_registry_system.md)

Meeting adjourned at 10:27 CT 



# 2020-11-13 Notes of the Technical Committee Meeting 

Attendees:  J. Larson, M.Frazzini, K. Dank, J. Stine, M. Brinas-Dobrowski,  M.Lens-FitzGerald, N.Myers, J.Crabb, D. Rogers, S. Prayaga, R.Nathenson, O. Coleman, D. Cundiff, V. Hingorani, J. Sedivy, P. Bentsen

The meeting was brought to order at 9:02 CT (US)

### Antitrust statement and notice of recording – J. Stine 

### Review of agenda and expectations for the meeting – D. Cundiff

### Review of work group process, preview of 2020.11.20 meeting – J. Stine  
* Special 90 minute Session on 11/20 to review work group reports from Architecture and Voice Registry System.  Calendar invites have been sent 
* Process - Please place all documentation in Github.   This will be our central documentation repository to enable version control, pull requests, review & commentary 

### Follow-up:  Next steps and recommendations, Privacy team within Privacy-Security Work Group – M. Frazzini, O. Coleman
*  Next Steps added based upon feedback:
   * Examples included 
   * Reassessing guidelines 
   * Add an action to invite industry participation, feedback and input 
   * Added a note that this work be included in any RFC
   * Inference model training –add a privacy guideline around the use of data for training (consent and transparency) 
* [link to Privacy Guidelines document]( https://docs.google.com/document/d/19o7k00fvFqwd0XdPbacd6h-JOVMB13sEaruKZfi529E/edit#heading=h.9l4e2earpcv9)

### Report and Recommendations from the Security Team within the Privacy-Security Work Group  -M. Lens-FitzGerald
* Overview of problem statement, process/methodology/references
 * Identify, define and prioritize capabilities of security in voice
 * Define the ‘what’ not ‘how’ 
* Recommended Next Steps 
   * Review of this report by security experts, update where applicable
   * Publish to inform and promote OVN work
   * If validated form two project groups. One for the verification capabilities and one for the channel and content encryption
* Questions, discussion, roundtable 
   * The goal is to have 1 way to do standards across all platforms.  Ex.  Verification 
   * Requested team to carefully review the Threats and Vulnerabilities Unique to Voice and provide feedback 
   * VRS verified means that the user knows that they are talking to the right assistant 
   * Who is doing the user verification?   Device?  Voice assistant system?  End point?   More work needed on how the verification should work
   * The threats have not been ranked at this point 
   * May want to add a capability for protecting Voice User Data 
 * [link to Voice Security Capabilities Report]( https://docs.google.com/document/d/1vlpaPlw62SPpTjcaLtLlJrXqH1LOSnTyAnApOUlfvA8/edit)
  
### Report from the VRS Work Group  – M.Brinas-Dobrowski
* Building out the VRS document in git –added a variety of content
* Added good detail to the VRS Requirements and proposed schema (this is checked in in git so feel free to review) 
* In prep for the meeting on 11/20- Please review the open questions/discussion section in the document
* [VRS meeting minutes to catch all of the details]( https://github.com/open-voice-network/docs/blob/master/components/voice_registry_system_meeting_notes.md)
* If you are interested in the VRS-please review the document and reach out to Maria and Jon to get involved
*  [Link to VRS git doc](https://github.com/open-voice-network/docs/blob/master/components/voice_registry_system.md)
  
### Report from the Architecture Work Group: – J. Larson
* Voted to prioritize additional components 
* Results –collection of basic speech recognition, NLU, Dialog manager were of the highest priorities 
* Next Steps:  
  * Discuss  how to make components future proof
  * Discuss how to allow commercial innovation and differentiation with components 
  * Discuss how to proceed with Minimal viable components, (ASR,  NLU, TTS,  Dialog manager) 
  * Define what component should resolve search VRS

Meeting adjourned at 10:01 CT (US)






# 2020-10-30 Notes of the Technical Committee Meeting 

Attendees:  J. Larson, M.Frazzini, K. Dank, J. Stine, M. Brinas-Dobrowski, J.Eisenzopf,  M.Lens-FitzGerald, N.Myers, J.Crabb, D. Rogers, I. Mez, S. Prayaga, R.Nathenson, C.Wuttke, O. Coleman, A. Dalloul, D. Attwater

The meeting was brought to order at 9:02 CT (US)

### Antitrust statement and notice of recording – J. Stine 

### Review of agenda and expectations for the meeting – M. Brinas-Dobrowski 

### Milestone review –reminders and OVN process – J. Stine
* Reminder to the workgroups on remit milestones 
  * Privacy and Security – Tech Comm Report  10/30 – today 
  * Architecture workgroup –Tech Comm Report   11/20
  * VRS –Tech Comm Report 11/20 
  * Plan for 25 minutes max including Q&A 
* Special 90 minute Session on 11/20 to review work group reports from Architecture and Voice Registry System 
* OVN’s maturing development process – Jon will share slide 


### Report and recommendations from the Privacy-Security work group -  M.Frazzini & M. Lens-FitzGerald
* Privacy Guidelines and Capabilities unique to voice –M. Frazzini 
  * [link to Privacy Guidelines document( https://docs.google.com/document/d/19o7k00fvFqwd0XdPbacd6h-JOVMB13sEaruKZfi529E/edit#heading=h.9l4e2earpcv9)
  * Overview of problem statement, process/methodology/references
     * Voice technology has the power to change our lives, however with voice technology there comes a unique set of privacy risks. Identifying these risks, and minimizing their potential harms, is inherently linked to the successful adoption and use of voice technology.  The Open Voice Network seeks to provide guidance and standards for creating voice technology that respects privacy rights and earns the trust and use of consumers.
  * Questions, discussion, roundtable 
    * What was reviewed with regard to legality on privacy assertions- Reviewed GDPR, US laws, researching constitutional privacy laws in the US.   Need privacy attorney’s to provide additional insight  	
    * The boundaries need to be grounded in the law of the geography 
    * Legal compliance affects to architectural issues such as permission giving and archiving and ability to access data recorded against an individual
    * Consent will and should not be similar to the cookie experience today as well as the experience of excepting user agreements before installing software 
    * Need to define the RFC process for public feedback and interactions
    * Great job team! 
 * Comments on this process for review
   * team did a great job and review was effective 
   * Review the OVN process document to ensure it ties to this process 

* Voice Security Capabilities Report  - M. Lens-FitzGerald  -review tabled until next meeting due to time 
  * [link to Voice Security Capabilities Report]( https://docs.google.com/document/d/1vlpaPlw62SPpTjcaLtLlJrXqH1LOSnTyAnApOUlfvA8/edit)
  
### Report from the VRS Work Group  – M.Brinas-Dobrowski
* Reviewed and validated decisions
* [VRS meeting minutes to catch all of the details]( https://github.com/open-voice-network/docs/blob/master/components/voice_registry_system_meeting_notes.md)
  
### Report from the Architecture Work Group: – J.Larson
* Identified additional components for review and will move to categories these components 

Meeting adjourned at 9:57 CT (US)






# 2020-10-16 Notes of the Technical Committee Meeting 

Attendees:  J. Larson, M.Frazzini, S. Baul, K. Dank, J. Stine, M. Brinas-Dobrowski, J.Eisenzopf,  M.Lens-FitzGerald, N.Myers, J.Crabb,  A. Fyles, D. Rogers, I. Mez, S. Root, S. Prayaga, R.Nathenson

The meeting was brought to order at 9:04 CT (US)

### Antitrust statement and notice of recording – J. Stine 

### Review of agenda and expectations for the meeting – M.Brinas-Dobrowski

### OVN organizational update:   sponsorship, participation, messaging  – J. Stine 
* For workgroup updates: 
  * Look for intersections between workgroups 
  * Please start workgroup updates with status, level of confidence and share any changes needed 
* 2 questions: 
  * 1 year from now, what would you want to look back at with Pride?   
  * 1 year from now, what would be the 1-3 OVN accomplishments that would be of greatest value to you and your organization? 
  * Jon will post in slack –please provide your inputs 
* For Community Moderators: 
  * Jon shared a template for communications.  Jon will post in slack
* Sponsorship Update 
 * No changes in sponsorship commitments since the last meeting 

### Milestone review reminders – J. Stine 
* Reminder to the workgroups on remit milestones 
  * Architecture workgroup –Tech Comm Report   11/20
  * Privacy and Security – Tech Comm Report  10/30
  * VRS –Tech Comm Report 11/20 
* Plan for 25 minutes max including Q&A 
* Jon will share slide in slack 

### Report from the VRS Work Group  – M.Brinas-Dobrowski
* Continued progress on: 
  * Finalize the problems prioritization that VRS can solve
    * They have organized the problems into 2 groups or buckets.  Of highest priority: 
     * Provide a consistent experience across conversational platforms and/or entity’s conversational assistant
     * The lack of central location for invocation availability 
   * Other problems discussed: 
     * Registry of  names 
     * Ability to search for a name and connect to it 
  * Architectural Principles 
* Maria will share out details via slack 
* If you are interested in the VRS-please review the document and reach out to Maria and Jon to get involved
*  [Link to VRS git doc](https://github.com/open-voice-network/docs/blob/master/components/voice_registry_system.md)

### Report from the Privacy-Security Work Group:  discussions, direction, next steps – M.Frazzini & M. Lens-FitzGerald
* Group on track for 10/30 presentation 
* Security Group Update: 
  * Objective:  Identify, define, and prioritize capabilities 
  * Current focus:  Voice system specific threats, vulnerabilities and actors 
  * Have defined Voice Assistant Security (slightly adjusted from nist standards definition) 
* Privacy update will be shared with the developer and experience group (M.Frazzini & J.Larson) 
* Security update to same group will follow later in the month (M. Lens-FitzGerald & J.Larson) 
    
### Report from the Architecture Work Group:  discussions, direction, next steps – J.Larson
* Looking to identify new components to add to existing voice /speech components 
* Have examined several existing architectures  
* Final review of existing architecture on Tuesday 10/20 and will shift to identifying new components 
* See ppt slide that Jim posted to the #architecture channel in slack   

### Review of actions, next steps, meeting tune ups  – M.Brinas-Dobrowski
* Zoom meeting URL issues for today’s meeting so Jon will post the URL with the agenda 
* Discussed value of pre-reads –consensus was not needed due to time constraints and additional context needed 

Meeting adjourned at 10:01 CT (US)







# 2020-10-02 Notes of the Technical Committee Meeting 

Attendees: D. Cundiff (Chair), J. Larson, M. Frazzini, S. Baul, K. Dank, J. Stine, M. Brinas-Dobrowski, M. Lens-FitzGerald, N. Myers, A. Dalloul, S. Prayaga, A. Fricke, J. Eisenzopf, L. Lin, S. Root. I. Mez. M.Saul 

The meeting was brought to order at 9:01 CT (US)

### Antitrust statement and notice of recording – J. Stine 

### Meeting timing has changed to 60 minutes going forward in the interests of efficiency and with respect to participant time and efforts done in the working group sessions.   Some sessions may be extended due to content. 

### Review of agenda and expectations for the meeting – D. Cundiff

### OVN Positioning:  market transitions, future of voice assistance – J. Stine 
* OMERS – Canadian public pension fund.  Published Four Plausible Futures for Voice Technology.   Jon will share the link to this in slack 
  * Five big voices speak to billions.  Privacy a luxury, but superb digital assistance 
  * Lost in translation.  Industry infighting leads to a standard set of protocols
  * Open Voice.  Emergence of standards, use cases, innovation.  Brand voices
  * Speak Easy.  An industry in decline.  Consumer back-lash to predatory technology 
* Jon shared slide covering Voice current and future 2024-2025.  Jon will share out slides via slack 
* Discussion: 
  * Audience is perspective sponsors and press/analysts that are looking for our perspective on the future 
  * May be too binary –likely will exist in a hybrid world for longer than the slide depicts 
  * Stating that there are no industry standards today is misleading as we all comply with standards today 
  * Assistant’s Architecture - Future of Local or Cloud –it may be both 
  * Would be good to add more information on the value of OVN 
  * Additional feedback can be added in the Technical Committee slack channel 

### Milestone review-reminders – J. Stine 
* Reminder to the workgroups on remit milestones 
  * Architecture workgroup –components 11/20
  * Privacy and Security – requirements 10/30
  * VRS –requirements 11/20 
* Jon will share slide in slack 

### Report from the VRS Work Group  – M.Brinas-Dobrowski
* Group continues to identify problems.  Have identified 9 so far- 3new: 
  * Mispronunciation 
  * There is hardly an explicit invocation is our personal and messy world 
  * Conversation platforms vs voice apps 
* Next meeting, will ratify the business value of the identified problems.   Also will identify if VRS owns the solution or if other components of OVN should own 
* Problem prioritization will also be achieved
* This will be brought back to the Technical Committee 
* * If you are interested in the VRS-please review the document and reach out to Maria and Jon to get involved
*  [Link to VRS git doc](https://github.com/open-voice-network/docs/blob/master/components/voice_registry_system.md)

### Report from the Privacy-Security Work Group:  discussions, direction, next steps – M.Frazzini
* Identified 8 interactions to privacy related to voice
* Will define examples of how we might implement these standards related to voice 
* Discussed how best for this group to share out this information.   Aligned that Github is the best direction to enable visibility and collaboration across work groups 
* Considerations or Principles: 
  * Aspirational vs reality of how tech works
  * Accessibility compliance 
  * Disclaimers or caveats need to be added 
* M. Lens-FitzGerald will lead the Security component of this work group 
* M. Frazzini will now lead the Privacy component of this work group 
* Additional resources are needed so please let Mike and/or Martin know if interested  

### Report from the Architecture Work Group:  discussions, direction, next steps – J.Larson
* Group continues to examine various architectures 
* [Link to Voice Tools spreadsheet](https://docs.google.com/spreadsheets/d/1Iw8hy_cyXD6rqBr7HXa1hRFduZSuNn3ELp2uqbYkhgo/edit?usp=sharing)
* Work group requests Technical Committee to add tools to spreadsheet so can be consolidated.  Discussed posting this on the OVN website but there are concerns due to lack of strong anchoring to OVN and its mission.   Git may be a better alternative so team will take back to the developer community
* Next meeting will work through a set of straw man components for discussion 
###  Meeting adjourned at 10:00















# 2020-09-18 Notes of the Technical Committee Meeting 

Attendees: D. Cundiff (Chair), J. Larson, M.Frazzini, S. Baul, K. Dank, J. Stine, M. Brinas-Dobrowski, J.Eisenzopf,  M.Lens-FitzGerald, N.Myers, J.Crabb, A. Dalloul, J.Maas, N.Latwis, P. Bentsen, S.Prayaga, C.Wuttke

The meeting was brought to order at 9:01 CT (US)

### Antitrust statement and notice of recording – J. Stine 

### Review of agenda and expectations for the meeting – D. Cundiff

### OVN Update:  membership update, milestones – J. Stine 
* No changes in sponsorship commitments since the last meeting 
* Discussions continue with increasing depth with 2 major tech firms 
* Follow up from the prior discussion on the Northstar document.  We are sharing out purpose and goals of OVN via Twitter (@openvoicenet) and on Linkedin (Open Voice Network).  Please help share and spread the good information on OVN 
* As we progress and move from our early phase to publishing RFCs, etc., our communication and outreach will pivot from general outreach towards specific engineer focused communications covering things such as release notes, major releases, decisions, etc. 

### How all this could fit together:  roadmap, milestones, next steps – J.Stine
* Jon shared a set of slides covering the OVN Development Process from Technical Committee, project definition, working groups, project charters, research and development and ultimately to standards
* Milestone plan –Goals for what we can achieve by the end of this year 
  * Architecture- Report on components to Technical Committee in November
  * Privacy – Report on requirements to Technical Committee in October 
  * VRS- Report on Requirements to Technical Committee  in November 

### Report from the Privacy-Security Work Group:  discussions, direction, next steps – M.Frazzini
* Seeking help with prioritizing focus-Group consensus after discussion: 
  * Privacy 1st focus 
  * Security 2nd focus 
  * Commercial Data Ownership and Use -3rd 
* Have made good progress on working draft of Individual Privacy.  Have privacy problem statement, worked through the privacy risks unique to voice (identified 7 so far), privacy rights and working draft that evaluate technical capabilities and standards to address voice privacy risks
* Have also summarized guidance not unique to voice   
* M.Frazzini asked for feedback on the working privacy document
* J. Eisenzopf suggested a new content N. Hart-the Privacy-Security work group welcomes his participation.  Additional contacts surfaced and may be pursued 

### Report from the Architecture Work Group:  discussions, direction, next steps – J.Larson
*  2 directions: 
  * Examining various architectures - Meeting with various industry experts/resource’s 
  * Identifying components that could /should be standardized   
    * have Google’s paper on reusable components 
    * creating an online catalog of reusable components
* This working group is in need of a new lead 
   
### Report from the VRS Work Group  – M.Brinas-Dobrowski
* Have been working on the problem context –without a VRS.   Have defined 6 components
  * The entity will not have a consistent experience across conversational platforms
  * Disambiguation of entities location
  * Disambiguation of entities – homophone
  * Disambiguation of entities – homograph
  * Lack of central location for invocation availability
  * No consistent guidelines for invocation
* Discussion around the disambiguation components-what are the specific problems the disambiguation will solve for?   
* Next steps on problem context:  
  * Define the capabilities of VRS
* If you are interested in the VRS-please review the document and reach out to Maria and Jon to get involved
*  [Link to VRS git doc](https://github.com/open-voice-network/docs/blob/master/components/voice_registry_system.md)

### Closing – D.Cundiff



# 2020-09-04 Notes of the Technical Committee Meeting 

Attendees: D. Cundiff (Chair), J. Larson, M.Frazzini, S. Baul, L. Lin, K. Dank, J. Stine, M. Brinas-Dobrowski, J.Eisenzopf,  M.Lens-FitzGerald, N.Meyers. O.Coleman, D.Attwater, M.Saul, M.Buck, J.Crabb

The meeting was brought to order at 9:03 CT (US)

### Antitrust statement and notice of recording – J. Stine 

### Review of agenda and expectations for the meeting – D. Cundiff

### OVN Update:  membership update, milestones – J. Stine 
* We are entering 5th or 6th discussion with large network provider 
* We will have additional potential members attending Technical Committee meetings in near future 
* We now have 4 enterprise sponsors –Target, Schwarz Gruppe, Microsoft and Wegman’s.   As we reach the 5th enterprise sponsor, we will have the public launch of the OVN.  This will likely happen in September or October
* This will bring attention to our website, who is active and who is involved.   Ask of this group, are you willing to be identified as a supporter, participant affiliated with the OVN.      
  **ACTION:**  Let Jon know if you are willing to be identified in this regard 
*This will also bring a need for communicators and ambassadors.  A message track is being prepared in advance of this for a common narrative on OVN

### OVN North Star/Scope:  proposed summary statement. A follow up from the 2020.08.21 conversation – J.Stine
* Jon shared the North Star slides
* The Scope of the OVN slide 
  * We are **voice first**
  * We will address the issues and opportunities from a voice first perspective 
  * We will be aware of multimodality but we will be voice first 
  * Team endorsed the slide with some edits 

### Report from the Privacy-Security Work Group:  discussions, direction, next steps – M.Frazzini
* Have had weekly meetings for last 2 months focused on privacy with the intent to address security after that 
* Limiting the scope to what is unique to voice 
* Have identified pillars of trust, data (raw and processed), ownership of data, data use, transparency in data and consent in data use 
* Identified harms that exist with privacy protection 
* Created a high level roadmap for goals 
  * Rights, values and identification of the technical capabilities that will need to be addressed (technical capabilities is the current focus) 
* Challenge is commercial privacy (v individual privacy)
  * Commercial right of privacy –one of the core reasons for the founding of the OVN 
  * Joel shared that once a user has identified that they want to talk to an entity, the provider of the listening device (NLP) should just pass the voice data through to the entity and not log it or keep it in any way 
  * Challenge is privacy when it comes to commercial interests.   The commercial issues that the team is trying to address focus on ownership and less on privacy 
  *Individuals –privacy is limited to individuals or groups of individuals.  Not a lot of information available related to privacy for commercial entities –collateral focuses more on ownership
* Discussed if data processing is a gap here 
* Next Steps:  Complete the technical capabilities and update the problem statement and guidance 

### Report from the Architecture Work Group:  discussions, direction, next steps – J.Larson
* Purpose of the Architecture Working Group:  identify common components or elements of those components that could or should be standardized to create the open building blocks of voice assistants 
* Team is looking for a new moderator for this working group
* Team has been looking at different architectures
  * Bucket Brigade architecture
  * Bus architecture
  * Bringing in additional partners for exposure to other architecture ideas including W3C
* Defining components and the definition has been posted on slack for review 
* Continue analysis of Dialog Managers 
* Terminology standardization is a need and this group will work to standardize on meaning of terms to be evangelized and adopted by the rest of the OVN Technical Committee.
 **ACTION** J. Stine to establish, recruit an OVN "Terminology Tsar" for organizing, managing, driving common word definitions across all work groups. 

### VRS Proposal and Discussion:  discussions, direction, next steps – M.Brinas-Dobrowski
* First priority is defining the problem context and team has made good progress on this.  Goal is to complete this definition in the next meeting and will bring back to the Technical Committee 
* Team defined their working style and operating agreement (tools used, etc.) 
* A key item that VRS is looking for from the Architecture Working group:   Alignment on the role of VRS and how VRS fits into the larger architecture 
*  [Link to VRS git doc](https://github.com/open-voice-network/docs/blob/master/components/voice_registry_system.md)

### Closing -- J. Stine

Meeting adjourned at 10:06 Central (US) time.




# 2020-08-21 Notes of the Technical Committee Meeting 

Attendees: D. Cundiff (Chair), J. Larson, M.Frazzini, P. Bentsen, S. Baul, L. Lin, K. Dank, J. Stine, A.Dalloul, S.Prayaga,  M. Brinas-Dobrowski, J.Eisenzopf,  M.Lens-FitzGerald, N.Meyers. O.Coleman, D.Attwater

The meeting was brought to order at 9:01 CT (US).

### Antitrust statement and notice of recording – J. Stine 

### Review of agenda and expectations for the meeting – D. Cundiff
* Guest in today’s meeting – Oita Coleman, formerly R&D VP, Software Quality Division, SAS Institute 

### OVN Update:  membership update, milestones – J. Stine 
* Sponsorship discussions are increasing and encouraging.   Anticipate decisions Sept/Oct
* New branding accelerating outreach- revised website, virtual ambassador, participation with Vixen Labs, WPP white paper on voice & brands, daily Twitter presence @openvoicenet
* Ethical Use Community – Privacy & Security, Accessibility & Inclusivity 

### Report from the Privacy-Security Work Group:  discussions, direction, next steps – M.Frazzini
* The group continues to make good progress & meets weekly 
* Completed the framework focusing on interactions, core concepts, harms and interventions 
* Created a North Star slide-posted on slack 
* Goal of the North Star is to identify what is unique to voice and provide guidance on addressing issues for both privacy and security 
* A.Dalloul shared that he will review and share within MS to get additional input.   Added that federated data and tracking of that data and user control is a key problem that should be addressed
* J.Larson requested that  the North Star document be shared at the Developer Experience Group

  **ACTION** Ask for all to review the Privacy & Security North Star document and provide feedback

### Report from the Architecture Work Group:  discussions, direction, next steps – J.Iwasz
* J.Iwasz unable to attend, D.Attwater covered 
* Have been focusing on definitions of components in a dialog systems 
* Discussed fresh ways to look at the problems-think about the different layers of messages in dialog system 
* This opens up the possibility of adding a new stream like gestures, emotions, etc.
*  Want to see if we can think about architecting something that will enable adding additional components /streams -Frame the architecture in layers that are time cross referenced 
* The team will need a follow up session to discuss further –likely at the next Architecture Working Group meeting and ensure that A.Dalloul will be included 

### VRS Proposal and Discussion:  discussions, direction, next steps – J.Larson, M.Brinas-Dobrowski
*  First VRS working group meeting occurred 8/20/2020 with 9-10 in attendance and plan to meet every 2 weeks 
*  The team has not yet elected a leader of the working group –will do in a future meeting
*  Focusing on the problem context of the current architecture 
*  Discussed scenarios that will be added to git as issues for VRS to resolve 
*  Will then focus on the what, then shift into Architecture 
*  [Link to VRS git doc](https://github.com/open-voice-network/docs/blob/master/components/voice_registry_system.md)

### Update:  “North Star” aspirational statement – J.Stine
* J.Stine shared the Operational Pillars of the OVN slide and the “North Star” of the OVN slide.  Both were reviewed by the OVN Steering Committee
  *North Star –Guiding Values of Trust, Choice, Accessibility and Openness
* Team provided feedback and commentary on the content.  Discussion included components such as adding Multi-modal and the group was discussed and aligned to focus on the core voice/speech scope to enable progress but should architect in a way that doesn’t preclude additional layers in the future
* Suggested and aligned that we should have a crisp, confined problem statement that will lead to marked progress in year 1 
*  We should document what we do NOT want to focus on  
  **ACTION** J.Stine will create a slide that documents the scope.  Will bring back to Tech Comm in next meeting and likely in Steering Committee following 

### Other topics:
*  Consistency in vocabulary used in OVN documents –Need more consistency here
*  Mozilla had some layoffs including Common Voice initiative so they may be available.  Jon is connecting with some of these resources

Meeting adjourned at 10:27 a.m. CDT. 



# 2020-08-07 Notes of the Technical Committee Meeting

Attendees:  D. Cundiff (chair), J. Larson, M. Frazzini, J.C. Junqua, M. Brinas-Dobrowski, J. Eisenzopf, N. Latwis, P. Bentsen, N. Myers, S. Baul, J. Crabb, J. Iwasz, J. Maas, M. Buck, M. Saul.

The meeting was brought to order at 9:01 CDT (US).

### Antitrust statement and notice of recording – Jon Stine 

### Review of agenda and expectations for the meeting – Dan Cundiff

### Open Voice Network: Organizational Update – Jon Stine 
* imminent sponsorship decisions by two major technology firms; significant interest in sponsorship exhibited by Tier 1 retailer
* presentation of OVN "Communities."  Composed of voice practitioners; moderated by Community members; tasked with advising standing committees, igniting new ideas and forwarding them to standing committees, helping staff and drive work and project groups.  Overall, enables the OVN to "hear" the needs-interests-opinions of the voice practioner community.

### Report, update from the Privacy & Security Work Group of the Technical Committee -- Mike Frazzini
* M. Frazzini provided update on the work, decisions to date of the Privacy and Security Work Group.   Noted the Work Group's decision to focus first on privacy, adopt a five-level framework (passive listening -> wake word/invocation -> application -> personalization -> emotion/sentiment, and to focus on four operational facets of privacy:  data ownership, data use, transparency, and consent.  
* M. Frazzini presented examples of the work to date (content compiled on a common slide deck in the Google Share Drive), noted further work to be done.
* Discussion:  request from M. Brinas-Dobrowski for the Work Group to ensure language/nomenclature be aligned with that in the Master Plan; question-discussion regarding the anticipated recommendations from the OVN -- might some of these recommendations be mandatory?  Might some be mere recommendations?  J. Stine noted that there will be elements that that must be observed, as they are specified by such regulation as GDPR; there will be other elements which may reflect that which the OVN may wish to promote on behalf of all users, such as private data ownership or commercial data privacy.  
* Work Group meeting weekly; will report again to the Technical Committee. 

### Proposal, review of initial concepts:  Voice Registry System (VRS) -- Jim Larson, Maria Brinas-Dobrowski
* J. Larson spoke to the recent discussions within the OVN Developer Community regarding the value of, and potential capabilities of, a Voice Registry System -- referred to as a "DNS for Voice" in prior OVN conversations.  J. Larson proposed on behalf of the Developer Community that a VRS Work Group be formed, and tasked with initiating the process of defining the current problem and the capabilities of an aspirational future state. 
* M. Brinas-Dobrowski shared an initial overview of the VRS problem statement and potential solution archtecture, now available for review in the OVN docs repository on GitHub.
* Discussion of the overview and steps to move a VRS Work Group forward.  Recommended actions:  1) Work Group (and Technical Committee member) documentation of a) the problems to solve, and b) scenarios-stories that describe the use (and value) of a VRS.  This to be brought to a new VRS Slack channel.   2) the reading and review of the M. Brinas-Dobrowski VRS overview now in the Masterplan, and found here: https://github.com/open-voice-network/docs/blob/master/components/voice_registry_system.md.  3) The recruitment of members and leadership for the VRS Work Group, and the scheduling of the first VRS Work Group meeting.  

### Report, Update from the Architecture Work Group of the Technical Committee -- John Iwasz and Jim Larson.  
* J. Larson, J. Iwasz reviewed for the Committee their proposal for a "component" approach to the question of an OVN reference architecture.  Noted the value of a "Lego block" concept.  Proposed to the group an operative definition of "components" and "harnesses" -- the latter a collection of existing components that can be used to 1) demonstrate new components, 2) test and evaluate new components, and 3) prototype new voice applications.  J. Iwasz noted that the Work Group will be reviewing proposed architectures from D. Attwater and J. Eisenzopf (next meeting), the W3C Voice Interaction Community (D. Schnelle-Walka and D. Dahl), Stanford Almond (M. Lam), and CMU RavenClaw.  

Meeting Adjourned 10:27 a.m. CDT (US)



# 2020-07-24 Notes of the Technical Committee Meeting 

Attendees: D. Cundiff (Chair), J. Larson, M.Frazzini, J.Iwasz, P. Bentsen, S. Baul, L. Lin, K. Dank, J. Stine, A.Dalloul, J.Crabb, S.Prayaga, M. Buck, M.Saul, M. Brinas-Dobrowski, J-C. Junqua

The meeting was brought to order at 9:02 CDT (US).

### Antitrust statement and notice of recording – Jon Stine 

### Review of agenda and expectations for the meeting – Dan Cundiff

### Open Voice Network: Update from Steering Committee – Jon Stine 
* Revising the branding of OVN
* Held last Steering Committee on July 13, 2020 
* Jon shared slide on OVN Journey
* New member Development includes:  Confirmed sponsors Target, Schwarz, Microsoft, Wegmans and in discussion with 8 tier 1 enterprises and in discussion with 2 major tech firms 
* Anticipate public launch in September when we have 5 leading sponsors.   

### Review of Milestones and work plans 
* Draft document that can be used to guide our planning and milestones 
* Reflects how we move from workgroups to development and potentially to official projects under The Linux Foundation 
* 3 main streams –Foundational (ex. architecture and privacy), Process/Systems (ex. VRS), User Experience (ex. common commands)  
* Discussion 
  * We should put some definition around each of the 3 main streams  
* This document will be on the G-suite in the Tech Comm folder 

### Report from the Privacy-Security Work Group: decisions and next steps - M. Frazzini
*  The team met last Tuesday and is meeting weekly working towards deliverable goal of early August 
*  Have prioritized privacy ahead of security and their goal to provide awareness and guidance with respect to the unique issues related to voice
* Developing a matrix framework –of 6 levels tied to the life cycle of a voice transaction 
  1. Passive listening 
  2. Basic - wake word invocation 
  3. Personalization
  4. Application or invoking a 3rd party 
  5. Within the application –selection, authentication, transaction, payment  
  6. Emotion and Sentiment 
* Discussion 
  *  NLP big players (AMZ, apple) –will this cover what they will keep or what would that look like?  
  *  We should align on terminology around things like 3rd party, commercial, etc. so it flows through technical master plan to each workgroup 
  **ACTION**  Privacy and Security group will take first pass at definitions and bring back 
  * Need to understand AI data needs 
  * What is the unintended consequence or harm –need to understand what we are trying to avoid (Harms Framework)
  * Knowing that the broader adoption may not happen, we will need to be practical and balance truly required work and the absolute north star  

### Report from the Architecture Work Group: decisions and next steps - J. Iwasz
* Intent is to define a discreet set of components that define a working assistant (ex. NLP, TTS/STT) and how they interact with each other 
* By mid-September, will be bringing in speakers from W3C and Almond to leverage their work as much as possible  

### Update from Architecture Work Group: a review of this past Tuesday's discussion - D. Cundiff, D. Attwater, J. Eisenzopf, J. Larson, et. al.
* The group met but was smaller and reviewed the Master Plan in detail 
* Major updates from the meeting: 
  * Principle:  Can be applied as low as local host, a private network or as big as globally provided
  * Discussed integrations and standards for those integrations –and they can follow the principles outlined in the document 
  * Discussed the Component Flow diagram  
    * the channel receives the utterance and responds back
    * TTS/STT –translates utterance to text
    * NLP – identifies the query’s VRS lookup entity and pass it to VRS
    * VRS – resolves the VRS lookup entity.  It returns the configuration records NLP
    * Dialog Broker – returns the fulfillable intents
    * Dialog Manager – returns the proper response to the identified intents
  * Discussion today: 
    * would be helpful if there were a list of general principles being followed
    * we will not live in a voice only world so need to think about having both physical and verbal 
     **ACTION** Dan will open up issues for these so the Arch Working group can complete 
    * Jim Larson feels that the group should meet again to review in more detail.   Others requested time from Dan Cundiff to review in more detail as well 
    * We need identify the use cases that we need to solve and ground the vision in the use cases (the Designer and Strategist community is focusing on use cases by vertical)
    * The fulfillment logic may need to be explored more deeply and expanded to another level and be added to the document 
    *  how does this architecture support multiple devices (speakers, microphones)? 
    * This work requires a coalition of many people with many agendas so important to be grounded in what can and cannot be done.  So the path forward needs to be practical  
    * Privacy concerns – keeping customer data accessible only to parties that need it ( and should not flow through a commercial channel provider).  This brings a concern that the NLP processing may be found as a privacy exposure point.  We will need to think about how to guarantee that only the responsible parties get the data
    * Did we distinguish between Voice Registry and Voice Name System –We’ve landed on Voice Registry System and will encompass both the registry and naming system
    * Use case suggestions:  Airline reservation use case (Jim Larson),  automobile voice use case (Shyamala ) and healthcare scenario (Peter B)
     **ACTION**  Jim Larson, Shyamala and Peter B will write the uses cases in the next 2 weeks following the W3C example 
 * [Link to the The Master Plan document]( https://github.com/open-voice-network/docs/blob/master/technical_masterplan.md)  
   
### Update: Designer-Strategist Community -- enterprise use cases - J. Stine
 * was discussed within the above agenda items 

### Request: review of the proposed "North Star" aspirational statement, now on GitHub: -- J. Stine
 * Jon reviewed the draft North Star document that outlines OVN goals and how we will accomplish and is meant for technical and non-technical audiences.   5 minute read to share out information on OVN in a quick, high-level and effective way
 * ask for members to review and provide feedback
* [Link to North Star document]( https://github.com/open-voice-network/docs/blob/master/North-Star.md)
   
###  Feedback on todays meeting: 
* good discussion 
   
   
   
   
   
   










# 2020-07-10 Notes of the Technical Committee Meeting

Attendees:  D. Cundiff (Chair, J. Larson, N. Myers, J-C. Junqua, C. Wuttke, N. Latwis, L. Lin, A. Dalloul, D. Attwater, M. Brinas-Dobrowski, M. Frazzini, P. Bentsen, V. Tai, S. Baul, M. Saul, J. Stine.  Sending regrets:  J. Maas, S. Prayaga. 

The meeting was brought to order at 9:01 CDT (US).

### Antitrust statement and notice of recording -- J. Stine

### Update on Ethical Use Community -- J. Stine

J. Stine described the purpose of OVN Communities.  Communities are advisory bodies comprised of voice practitioners and enthusiasts, responsible for advising Committees (especially the Technical Committee) on topics of interest.  Decision-making rests with Committees, not Communities.   The Ethical Use Community is now forming, and is developing a list of topics for study; high on that list is the topic of privacy.  It is expected that contributions from the Ethical Use Community discussions on privacy will be brought forward to Privacy-Security Work Group of the Technical Committee.

### Request for Team Assistance in addressing question from major technology provider  -- J. Stine

J. Stine reported potential sponsorship discussions with a major technology provider, and the questions raised by that provider on topics of invocation and dependable discoverability.   Discussion in re: potential OVN positions.   J. Stine requested brief call in week of 2020.07.13 to sketch options; options to be reviewed by Tech Comm in 2020.07.24 meeting.  

### Report from Architecture Work Group Meeting of 2020.07.07 -- J. Larson

J. Larson reported activities and results from the first Technical Committee Architecture Working Group meeting of 2020.07.07.  Working Group reviewed proposed architectures from OVN Master Plan (Cundiff/Brinas-Dobrowski) and the W3C Interactive Voice Community Group (Schnelle-Walka/Dahl).  Discussions of decision methodology, distillation-definition of components and interfaces.   Conversations to continue in next meeting (2020.07.21), and expand to include a review of the Almond architecture of the Stanford Open Voice Assistant Lab (OVAL) of Dr. Monica Lam.   John Iwasz unanimously selected to serve as Work Group Moderator.  

### Report from Privacy-Security Work Group Meeting of 2020.07.07 -- M. Frazzini

M. Frazzini reported activities and results from the first Technical Committee Privacy-Security Work Group.  Acknowledgement that the issues are intertwined, but that parsing will be needed to identify issues, potential areas for standards development.  Initial problem statement drafted.  Work Group Moderator not yet named.

### Review of the OVN Technical MasterPlan -- M. Brinas-Dobrowski

It was agreed through discussion that although it would be useful to provide a "primer" overview of the Technical MasterPlan in the meeting, a 90-to-120-minute deep dive would be required and should be scheduled as a primary agenda item for the Technical Community.  To that end, M. Brinas-Dobrowski provided a section-by-section overview of the MasterPlan in its current state, highlighting key points along the way.  Significant discussion in re: concepts and potential complexity of a DNS, and approaches to architecture.  A. Dalloul noted several options for the management of multiple end points; spoke to the challenges of an assumed "multi-home" environment, citing numerous examples (browers, mobile platforms) and extensive Microsoft research.  A. Dalloul, D. Attwater, J-C Junqua spoke to the importance of use cases against which concepts can be tested.  D. Attwater suggested that the architecture discussion may wish to step backwards, and consider data models and within that, the different entities (devices, enterprises, products, persons) to which a user may wish to connect.  Question: what is a Dispatch Registry to do?  Connect to some or all entities?  

### Next-steps summation -- J. Stine

Four major next steps are planned:
* The Privacy-Security Work Group will meet again on Tuesday, 2020.07.14
* A "tech Provider Question" Work Group will be convened by J. Stine in the week of 2020.07.13, and report its recommendations back to the Technical Committee.
* The Architecture Work Group will meet next on Tuesday, 2020.07.21.
* A Technical Committee session will be devoted to the Master Plan.

### Recommendations for Next Meeting Agenda (2020.07.24).

* Report from the Privacy-Security Work Group: decisions and next steps  -- M. Frazzini
* Report from the Architecture Work Group: decisions and next steps -- J. Iwasz.
* Recommended enterprise use cases as suggested by the OVN Designer-Strategist Community -- 
* Report from the "tech provider Question" Work Group: decisions and next steps -- J. Stine.
* Review of the proposed "North Star" aspirational statement:  -- J. Stine

### Meeting adjourned at 10:17 a.m. CDT. 



# 2020-06-26 Notes of the Technical Committee Meeting 

Attendees: D. Cundiff (Chair), J. Larson, N. Myers, M.Frazzini, J.Iwasz, P. Bentsen, S. Baul, M. Lens-Fitzgerald, J. Maas, L. Lin, K. Dank, J. Stine, A.Dalloul, J.Crabb, S.Prayaga, J. Eisenzopf, D.Attwater

The meeting was brought to order at 8:31 CDT (US).

### Antitrust statement and notice of recording – Jon Stine 

### Github training and on-boarding meeting recordings – Jon Stine
* Per request in prior meeting, Jon conducted sessions on Github and onboarding.  Recordings are available on OVN G-Suite for your review.  

### Review Technical Committee and Developer Community inputs into proposed Activities list:  Foundational –exploratory, etc. – Dan 
There are 16 PRs and we will need to determine a workflow to review the PRs. Options: 
 * The PR creator assigns the PR review to someone (and they’ll get a notification)  
 * rfr (request for review) –can post this in the Technical-committee slack channel along with your PR to create awareness of your PR 
**ACTION:**  Align on PR review process 

### Determination of Initial Prioritized Activities – Dan 
* Activities are the work that needs to be done 
* The full list of voting results were posted by Jim Larson in the developer-experience slack channel (posted 6/22)
* Initial Inputs to Priorities: 
1.  Approaches for Voice Registry 
2. Privacy and Data Protection 

Jim Larson feels that we all should better understand the architecture before proceeding much further 

**ACTION:** Form a small working group to review and adjust the architecture ahead of a broader share out.  S. Baul,  M. Lens-FitzGerald, J.Iwasz, P.Bentsen, J.Larson, S.Prayaga and D.Cundiff will participate.  This will be called the Architecture Working Group.  
**ACTION:** Conduct a session to go over the Master Plan & Architecture after the Architecture Working group reviews & edits. 
* Discussed items that didn’t get a lot of votes—this does not mean that these won’t be done, they are a lower priority and will go into an activities backlog 
* Discussed if we should place timelines on some of the activities.  The working groups likely need to get formed to define milestones   
* Discussed if we should we create a starting milestone framework to aid in timing.   
 **ACTION** Jon and Dan to create draft milestone framework 

### Determination of Activities work team participants & leaders – Dan & Jon 
* Working groups are the teams that execute work against the activities 
* Discussed additional: 
  * Voice Naming System working group (vertical and long lasting)
    * the developer community wasn’t aligned that this is a priority 
    * the VNS is key and central to the architecture in the Masterplan doc 
    * agreed that we should discuss VNS and validate need -this discussion will be led by the Architecture working group plus others.  Forming the VNS working group is TBD based upon this discussion
  * Privacy working group (horizontal)-combine with Security 
  * Security working group (horizontal) – combine with Privacy 
  * Identity & Authentication working group (horizontal) 
  
Agreed to start: 
* Architecture working group  (S. Baul,  M. Lens-FitzGerald, J.Iwasz, P.Bentsen, J.Larson, S.Prayaga, D.Cundiff)
* Voice Naming Systems working group (pending further discussion) 
* Privacy & Security working group –horizontal (S.Prayaga, J.Maas, P. Bentsen, M.Frazzini, N.Myers, L.Lin)

Agreed that the working groups will define the lead for each

Discussed what OVN community members can/should participate in the Tech Comm working groups.  Jim and Maarten will reach out to the communities to seek participation.  Leadership will come from Tech Comm working groups 

Clarified that Tech Comm members can bring in additional resources from their firms or additional experts

Discussed if there should be a list of voice assistant standards.  This is on the activities list backlog

### Summation of Decisions – Kristi 
* Reviewed above 

### Review of meeting processes, questions, comments – Dan 
* Did not discuss 

### Adjournment
* Meeting adjourned at 9:57 CDT US



# 2020-06-12 Notes of the Technical Committee Meeting 

Attendees: D. Cundiff (Chair), J. Larson, N. Myers, M. Brinas-Dobrowski, M.Frazzini, J.Iwasz, M. Saul, P. Bentsen, S. Baul, M. Lens-Fitzgerald, J. Maas, L. Lin, K. Dank, J. Stine, A.Dalloul, J.Crabb, S.Nicholas, S.Prayaga, V.Tai, N.Latwis, A.Lee

The meeting was brought to order at 8:32 CDT (US).

### Antitrust statement – Jon Stine 

### Organizational updates and introductions/questions – Jon Stine 
* Jon shared that the OVN is now a funded, legal entity.  A directed fund of The Linux Foundation 
* The OVN Steering committee held first meeting on 6/1/20 and approved the OVN Chair, Tech Advisory Chair and the OVN initial budget  
* Microsoft has joined Ali Dalloul attending Tech Comm meeting today.   Wegman’s has signed on as a sponsor as well
* Jon shared the OVN organizational structure slide and slide covering how OVN committees and communities work together.  Discussed that , "connected government" should be the term used instead of "smart cities;"  public safety should be added to the communities slide.  
**ACTION** Jon to change "smart cities" to connected government, inclusive of public safety. 

### Website development work and volunteers – Dan Cundiff
* OVN website created about a year ago [https://openvoicenetwork.org/]
* Need volunteers to work on the OVN website and would prefer to have it done by the OVN community vs external resources 
* Need to post artifacts (charters, whitepapers, etc.)  
* Site leverages Hugo website, jamstack site, uses a template that allows for flexibility.  Hosting provider is Netlify.  For those that want to edit, use Netlify CMS
* Nicholas Myers & Mike Frazzini volunteered.  
**ACTION:**  Jon will setup some time with Nick, Mike, and Dan 
* If others want to volunteer, please post in the OVN Technical Committee slack channel 

### Forming, running, operating working groups for activities 
* Activity is defined as a body of work that we need to work on and we need to form working groups to complete
* We need to organize working groups, discuss how they will work and decide which activities we should work on first 
* The list of activities should map back to the Master Plan.  If they do not, then should be brought back to the Tech Comm meeting for discussion on priority and updates to the Master Plan accordingly 
* Some of the items in the current activity list do not tie back to the Master Plan
Discussion:  
* A.Dalloul –timelines and priorities would be helpful so supportive of the discussion 
* S. Baul  –regular review of the Master Plan document would be helpful for new joiners and to foster continued alignment.  Team agreed that this would be helpful and will ensure happens.
**ACTION:**  Setup review and on-boarding sessions as to the Master Plan, Activities List – Jon & Dan 
* Dan walked through the docs repo in Git 
  * Technical Master Plan –North star, charter doc in markdown.  Teams should do pull requests against this master plan 
  * Proposed Activities list –point in time artifact that contains the list of activities that have been brought up for us to work on.  Ideally, these activities tie to the Master Plan.   We will need to create an additional roadmap artifact that takes what is in the Master Plan and says the order and likely when the artifacts will be completed 
  * Ways of working doc explains how our working groups will do activities.  Document is in progress and not yet complete 
* Activities list formed from discussions in Tech Comm meetings and from communities
Discussion: 
* P. Bentsen –roadmap document will help to define interdependencies between working groups that would be helpful 
* A. Dalloul – Some of the areas are horizontal in nature and others are specific and some regulated.  As we think about the intersection of these, it will be important to have a level of prioritization as we cannot go after everything while the Master Plan is being further developed.  Perhaps a matrix for priorities and sequencing will be helpful
* J.Larson – at the next developer community group meeting, they will be adding additional activities and will take a run at prioritization via a voting process.   Then the priority list can be vetted against the Master Plan document.   This can be brought back to the next Technical Committee meeting (6/26/20).   
* J.Stine – also can factor in whether an activity is horizontal or vertical as input to the priority  
* D.Cundiff - We can prioritize and sequence the work an do it in that order.  Or we can allow additional, more periphery activities to be completed and submitted to the OVN  
* J.Larson - recommended that 2 classes of activities be identified –foundational and exploratory/community driven/pioneering.   Emphasis needs to be on foundational but exploratory/community/pioneering driven will help attract new members, provide new ideas and allow to address fast changing space
* General discussion was supportive of the 2 class method of foundational and exploratory with the emphasis on foundational.
**ACTION:**  Dan, Jon and Jim Larson to ID the activities as foundational or exploratory  

#### Forming & Running of the working groups: 
* Working group is a collection of people working on a activity or activities
* Working groups can come and go and some are permanent pending the activity that they are assigned (ex. VRS)
* Address things like:  Slack Channel, release process, meeting cadence and notes, artifact publication process
* The “how we work” may vary slightly from working group to working group (some things need to be consistent and others can vary) 
* Discussion:  Team is supportive of a simple process and healthy for the success of the working group.   Roles & responsibilities and general operating agreement
* Maarten Lens-FitzGerald, Samrat Baul and Jon Stine volunteered to create a proposal.  Jon will include non-regulatory requirements like anti-trust, notes and recording (for audit trail). 
**ACTION:**  Maarten, Samrat and Jon create proposal 

Discussion on the Master Plan and missing components.  Team reiterated that PRs should be done against the Master Plan for this.   Discussed that PRs are new to some.  Discussed the reasons for git: version control, change tracking, transparency and common tech use.
**ACTION:**  Jon will setup a session on git, PRs, etc.    

### Follow-up from 2020-05-29 meeting – outstanding issues – Dan Cundiff or Kristi Dank 
* Will create a backlog grooming process outside of the Tech Comm meetings so that we can focus on priority items in the Tech Comm meetings.   
**ACTION:** Dan & Kristi create process 
* Discussed why using git project board for tracking activities.  Simple views to allow quick tracking of issues and transparency (work that needs to be done).   

### Next Meeting: 
* Review activity priorities 
* Propose working groups for top priority activities 

* Meeting adjourned at 9:59 a.m. CDT (US)


# 2020-05-29 Notes of the Technical Committee Meeting 

Attendees: D. Cundiff (Chair), J. Larson, N. Myers, M. Brinas-Dobrowski, M.Frazzini, J.Iwasz, M. Buck, M. Saul, P. Bentsen, S. Baul, W. Angerer, M. Lens-Fitzgerald, J. Maas, L. Lin, K. Dank, J. Stine, B. Czechowicz, V.Tai, J. Eisenzopf, A. Weidauer

The meeting was brought to order at 8:30 CDT (US).
### Antitrust statement - Jon Stine 
### Introduction - Ways of Working document on Git - Jon Stine 
J.Stine covered the Ways of Working document content (document itself is in Git).  We can work towards building this out to include adding in our git PR processes, etc.   
ACTION:  Please review Ways of Working document in git and provide comments.  [link to document](https://github.com/open-voice-network/docs/blob/master/way_of_working.md)
OVN Docs git repo is now open so all should be able to access.  
 ### Follow-up from 2020-05-14 meeting - outstanding issues - Kristi Dank 
* Need to formalize the process for issue management, prioritization and discussion – defined process as part of 5/29 session.  Will be added to ways of working doc. 
* Before the next technical committee meeting, participants to review the Technical  Master Plan document, create PRs, add comments and be prepared to ratify.  Will be discussed in 5/29 meeting
* Meeting Feedback – participants to send comments in technical committee slack channel or send to D. Cundiff directly.     Ongoing 
Discussed that all should be opening issues and we can use the git issue list and review material items in the tech comm meetings.   We can leverage the projects feature of Git to aid with this management process.   
ACTION:  D. Cundiff will add a few instructive notes to the ways of working doc.   
ACTION:  Create this project view in git.  
### Follow-up if everyone got the chance to review the Masterplan – M. Brinas-Dobrowski 
Some changes were put into the Master Plan.   We do want to label a release of this document.   Discussion was supportive of a beta release.  D. Cundiff will post the release in slack.   We can add processes related to this to the Ways of Working document. 
DECISION:  Confirm Master Plan as 0.1 Beta release. 
### Review 1.0 proposed list of Tech Comm development projects – Jim
Following the Developer Community call, M. Lens-Fitzgerald and J. Larsen drafted a list of potential "activities" for Tech Comm consideration.    The full list is still being developed.   Suggest we use the term Activity vs Project to avoid confusion.   Discussion was supportive of using the term Activity.    
VOCABULARY DECISION: These will be termed "activities"
ACTION:  J. Stine to add this to "Ways of Working."
List of suggested activities: 
1 Destination Registry
  1.1 Name Approaches for Voice Registry - Need to determine the best approach for developing a voice registry   
Discussion: This will be similar but not identical to DNS.  D. Cundiff shared a few examples like operating aspects.  Also do not be too confined to DNS and be sure to be forward looking.  Registry aspects of VRS will need to be assessed too –may need separate firms to manage the voice registry.    Collaborate with firms like Google & Amazon (users of VRS).  Expand the scope of this item to include a baseline of first level requirements vs Analysis.   
2 Voice Commerce Core Processes 
  2.1 Pay by voice -  Accelerating people’s purchasing process through voice payment, voice print and biometrics
Discussion:  Not a standard but a reference implementation and guidelines that firms can follow to provide the user with a more common experience.   The soon to be stood-up voice designer community can help with this.    Should this type of experience work come after foundational standards – this work may provide insights into how the lower level standards need to work.   This work may also be applicable for other UI applications.     Would be good to solicit involvement from bill-pay firms (ex.  Capital-One)

3 Identification and Authentication 

Discussion:  Biometrics included here? 

4 Data Privacy 
  4.1 Name Evaluate OVAL (Open Virtual Assistant Lab, Stanford University) Approach to Privacy – Need to specify a data privacy policy and enforcement mechanism 

Discussion:  Discussion supportive and promotes reuse. Will need to be in line with GDPR and CCPA.  Perhaps combined with Identification and Authentication.   Need to assess liability and regulatory impacts.   

5 Interoperability 
Discussion:  Should we add to interoperability a set of interfaces to interop between applications. 

  5.1 Vendor Independent language for writing speech applications 

Discussion:   This isn’t necessarily a new programming language but rather a vendor independent API specification.  Like Jovo –a framework.  Could be an open source toolkit.  Voice assistant, IVRs or on-device apps.  Will need to get Amazon and Google on board here (VII).  Will need to put boundaries on the focus of this like channel, NLP, etc.  This may not be an essential building block item.    

### Meeting feedback 
*  Didn’t get through all agenda items 
*  Need someone to monitor chat and share out 
*  Good discussion today –got into some requirement and maybe use this meeting to do higher level inputs 
* Perhaps a stacked or forced ranked process may be helpful to prioritize efforts 
* organic nature feels ok now 
* Helpful to have a location for sharing existing knowledge/articles/links.  Action:  Dan will create an approach 

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

