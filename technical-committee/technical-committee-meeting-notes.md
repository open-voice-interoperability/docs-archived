***********

---
layout: default
title: Meeting Notes
parent: Technical Committee
---
# Notes of the Technical Committee Meeting - March 10, 2023

**The Meeting Began at 10:07am EST.**

**Attendees: J. Stine, N. Southern, B. Epstein, O. Coleman, D. Dahl, J. Larson, T. Martens**

**Notice of Recording - J. Stine**

**Linux Foundation Anti-Trust Statement - J. Stine**

*Mr. Southern called for approval of minutes from the prior OVON Technical Committee Meeting of February 10, 2023. Mr. Stine put forth a first motion, and Mr. Larson a second motion. With the minutes duly approved, the group moved on to the formal agenda.*

## Review of the agenda, purpose of and expectations for the meeting  -- T. Martens.
* Planning of the Open Voice Interoperability Webinar - J. Larson, D. Dahl
* Status Interoperability Initiative Roadmap and Deliverables - J. Larson, D. Dahl
* Report from the first Authentication Work Group - B. Epstein
* Update on Trust Mark Initiative Launch - O. Coleman
* Open Voice Network and Generative AI-LLM - J. Stine
* Comments, Questions and Miscellaneous - Group

## Planning of the Open Voice Interoperability Webinar - J. Larson, D. Dahl ##

*Dr. Dahl noted that the Interoperability Webinar is scheduled for Wed., Mar. 22nd, at 17:00h CET, 12:00pm EDT, and 9:00pm PDT. This will mainly cover the new interoperability standards on which Open Voice is working, especially the dialog packets. It will also cover the big picture of interoperability architecture with three corresponding patterns, and include the group's first demo of two independent interoperating agents sending delegation messages back and forth. Then a discussion will take place.*

*Mr. Martens added that it will be an exciting opportunity if we can have a demo - to identify from the webinar a couple of smaller clips that we can share via social media.*

*Dr. Dahl also stated that promotion of the webinar is being worked out. Dr. Larson compiled a large list of emails to people who should be invited, and the team is putting together an invitation message.*

*Mr. Stine stated that there will be a general mailing to the OVON mailing list of approximately 1,200 individuals. The team will then follow up with a personal follow up note to 150 earmarked individuals perceived to be of high interest and/or value to this conversation. This list is being finalized this morning, and is currently in the hands of vendor Thrive Marketing.*


## Status update of the Architecture Roadmap and Deliverables - D. Dahl, J. Larson ##

*Dr. Dahl summarized the work as follows that has taken place since the last Technical Committee meeting:*

* Demo of Two Independent Agents Cooperating in a Delegation Pattern (Demo 1) - accelerated and augmented with capabilities planned for later demos, such as speech interaction (live demo & video to be presented at webinar)
* Launch of identification of agents activity - goal to have a requirements document available  at the end of April
* Dialog Packets Work - first specifications. Communicating natural language messages between users and systems. The work here has grown more specific
* Technical paper on interoperability has been submitted to the Interspeech 2023 conference - this will provide great visibility to the academic/research communities. 

# Notes of the Open Voice Network Technical Committee Meeting - February 10, 2023

### Attendees: J. Stine, N. Southern, O. Coleman, J. Larson, T. Martens, D. Dahl, E. Sewell, C. Wüttke, K. Brix, B. Epstein, N. Myers, E. Banzhaf.

The Meeting Began at 10:01am ET.

### Notice of Recording - N. Southern
### Linux Foundation Anti-Trust Statement - N. Southern

* We had a quorum today and approved the January 13, 2023 Technical Committee meeting notes with a first motion from Mr. Stine, a second motion from Dr. Larson, and no immediate objections presented. 

### Review of the agenda, purpose of and expectations for the meeting -- C. Wüttke 
* Short discussion about generative AI
* Updates on the Trust Mark initiative - O. Coleman
* Updates on the Architecture and Synthesis Work Group
* Report re: Authentication Study Group - J. Stine
* Q&A Session - Group

### Generative AI Discussion - Mr. Wüttke
* C. Wüttke shared his vision of Generative AI from a c-level perspective and discussed the question of 'Can't we just hand customer service over completely to Generative AI?'
* A common corporate question (internally): how can we combine generative AI with our enterprise conversational AI platform?
* Most companies, Mr. Wüttke  noted, have an AI platform in place mainly based on a transformer network. Schwarz Grüppe, Wüttke stated, there is a standard Natural Language Understanding (NLU), with various services around it for named entity recognition in certain knowledge domains, all based on existing bird models. 
* C. Wüttke stated that Generative AI is also a transformer based model - more powerful and scalable. For Schwarz, the challenge lies in the fact that GAI - however powerful - doesn't know the processes within their company. It isn't integrated into Schwarz's contact center; it has no ability to be handed over to a human agent - yet. There will always be cases that need to be handed off to a human, with empathy.
* Schwarz's challenges: how can they make their daily conversation design work easier through GAI, and how they can best position GAI for their customers?

 ### Generative AI Discussion - GAI & OVON - T. Martens
* Much of the current conversation, Mr. Martens affirmed, has grown out of the release of ChatGPT on November 30, 2022.
* This led to a "boom" within the Open Source community geared toward developing new conversational AI voice asst. chat bots. 
* As such, Mr. Martens noted, all of this puts the Open Voice Network in a position where it is ideally suited to respond, especially given the standards and specifications OVON has developed over two years, perfectly paired with this sudden surge in sectorial interest/enthusiasm. Said standards can be easily adopted to large language models, voice assistants, and chat bots based on generative AI technologies.
* At OVON, Mr. Martens and others have affirmed their desire to embrace this topic yet stay focused wrt OVON's mission: enabling the interoperability of different agents. Said agents can be either rule-based or generative AI-based large language. 
* Mr. Martens noted that we now see an opportunity to tie aspects of OVON's work to large language models.

###### _Mr. Epstein, at this point, posted a comment. He noted a sense of déja vu - feeling exactly the same as he did ~ five years ago when text-based chat bots met at first appearance. Mr. Epstein noted that if a generic, predictable answer is desired, then AI perfect. But if emotion is involved, we need a trained, skilled human answering._ ######

###### _In response, Mr. Martens expressed an agreement with this Epstein statement on behalf of the larger project team. He noted that traditionally (in the beginning), Generative AI was used to increase efficiency in internal processes at companies, and it only gradually has become a central component of customer-facing applications._ ######

* Mr. Martens also limned a couple of interoperability questions wrt how to design this tech, and listed several related issues tied to large language models. Specifically:
-Compatibility Issues: Different architectures and input/output formats 
- Performance Differences: Inconsistency due to difference LLM performance 
- Bias Issues: Different LLMs may have built-in biases wrt training.
- Language Coverage Differences: NLP problems occur when LLMs 
have different language coverage. 
- Resource Requirements: Combining LLMs increases memory and 
computational resource needs. 
- Data Privacy Concerns: Data from different sources raises privacy 
concerns. 

###### _At this point, Ms. Coleman requested clarification regarding data privacy concerns - GDPR, right to explanation, and how we will be able to explain results from different sources and ensure transparency on the accuracy of results._ ###### 

###### _In response, Mr. Martens affirmed Ms. Coleman's concerns, and stated that LLMs in comparison to rule-based AIs pose a different set of questions, such as how will be data be useful training, what kind of data sources are available and can be shared, and how are the privacy of user data and company trade secrets protected. All of these, Mr. Martens said, are questions we are considering. Mr. Martens also stated, more broadly, that the group is working on this topic, and will be announcing updates on how OVON plans to progress very soon. In the meantime, requirements will be included in the first published version of OVON standards._ ######

###### _Mr. Martens also responded to a comment from meeting participants about the criticality of determining how to package this - and affirmed this is something OVON is still weighing - if it should be generative AI, or large language models, or something else._ ######

###### _Mr. Epstein commented on policies banning the use of GAI to avoid leakage of sensitive data. Mr. Martens agreed that yes, there will be many cases to explore, and it will get interesting._ ######

### Tactical steps / action items proposed by Mr. Stine in response to this
* Dr. Dahl and Mr. Martens - begin a slack conversation on this topic - Dr. Dahl should lift conversation to the Architecture Work Group slack channel. 
* Mr. Martens  - place his GAI slide in said discussion as a reference point.
* Mr. Wüttke - place his GAI slide in said discussion as a reference point.

###### _Mr. Stine stated that Open Voice is being asked from many sources to formally comment on GAI/LLMs chiefly from an ethical perspective - Wired magazine has asked for comment. Others have asked if it makes Open Voice Network irrelevant. It manifestly does not, however OVON needs to be very clear. It is critical that Open Voice remain in the middle of the current changes. This leads to another key action point :_ ######

* A 3-4 page formal statement on this from the Open Voice Network by mid-March will be essential. This should grow out of the conversation in slack/architecture group

###### _Mr. Epstein: as great of a need as there is for OVON's involvement in this space, he is concerned that it could distract us from the real problems underneath it. Asked could we be in conversation with the open AI people to see if they need guidance from OVON in the creation of standards. At the same time, he is wary of this becoming the bright shiny new object that pulls OVON away from its central objectives._ ######

###### _Mr. Stine responded that much of the purpose of this involves giving people like himself and Ms. Coleman the knowledge necessary to speak in public when GAI and/or LLMs are mentioned. Mr. Stine agreed that this shouldn't and won't detract us from the momentum attached to our synthesis/interoperability work. Re: conversations with OpenAI, Mr. Stine agreed that these discussions are critical and affirmed that OVON is proactively reaching out to them. He stated that Ali Dalloul is the individual working on the integration of OpenAI, ChatGPT and other tools into Microsoft, and therefore remains our ideal liaison/best point of contact._ ######

###### _Dr. Dahl spoke at length and agreed with all of the above, and described the very real limitations of ChatGPT, for instance, with respect to individual companies' use cases and adaptation to customer service applications. At some point, it drops the omniscience and begins having to cooperate with other systems. For this reason, said technology increases the need for standards as will the number of these bots being built, which doubles down on the need for scalability (she predicts millions of ChatGPT-like bots,)_ ######

### Trust Mark Discussion & Next Steps from Q1-Q2 of 2023 - Ms. Coleman
* Ethical Guidelines v. 2.0 White Paper - out for review - final feedback will be incorporated. Should be available by February 28th. 
* This will form the ethical principles basis of the Trust Mark initiative, also incorporating some information from the Privacy & Security white papers as well.
* Re: the education pillar of Trust Mark - OVON has been working with the Linux Foundation to design an introductory free course using the EdX platform. Ethical guidelines will form the core of the content, here. Course design document will be completed by a week after the Ethical Guidelines document. From this the program itself will be developed.
* The Trust Mark initiative will be brought into the Project Voice Conference (on GAI and LLMs) in April. A proposal will be ready by the end of March. 
* Mr. Stine noted that Siri co-founder and voice leader Adam Cheyer will be the keynote speaker at that event - on the future of voice, GAI and LLMs. Bradley Metrock has asked the Open Voice Network in a parallel and complementary track to be prepared with a statement and discussion on overall conversational AI ethics. There is significant interest in this ethical topic and will be an audience among Tier 1, Tier 2 enterprises. OVON can use this as an opportunity to show leadership.
* Ms. Coleman - this is not meant to be a one-off. It will be aligned with the overall Trust Mark program toward which the team is working.

### Updates from the Architecture and Synthesis Work Groups - Dr. Dahl
* The group has made progress - able to characterize the entire work pkg of technical features needed for interoperability.
* Mr. Epstein organized all of the topics under discussion into 33 crisp technical focus areas.
* As a team, the group prioritized these, wrt which need to be most accomplished to facilitate interoperable conversational assistance.
* Most have in common the question of how intelligent agents ask one another to do things, and pass along information from what a user has requested, and how do they provide each other with the right context where the agent delegated to by the user knows how to respond.
* Dr. Dahl identified six key top priority focus areas to achieve this goal.
* Wrt deliverables for 1H 2023 - 3 goals:
	-Create a set of use case, demonstrations of use cases, the specifications that we need 
	to accomplish those high priority focus areas. 3 increasingly capable POCs that build on 
	each other, starting small and ratcheting up the capabilities as we learn from the earlier 
	demos
	-Recruit 5 external partners to collaborate on testing specifications with use cases, and 
	this feeds into our work and informs what we're doing.
	-Develop implementations of the specifications - write these and create specs by the 
	end of the first half of 2023. 
* This represents a significant amount of work and will consume most of the energy of the architecture/synthesis group. Group has decided to postpone several items on the road map, including:
	-Interoperability Patterns: Delegation
	-Personal Authentication Scope of Work
	-Destination/Location Services Scope of Work
	-Interoperability Patterns: Data Sharing and Privacy
	-Interoperability Patterns: Destination/Location
	-Privacy Guidelines Aligned with Interoperability Standards
	-Interoperability Patterns: Security and Authentication
	-Security Specific to Voice 2.1

###### _Mr. Stine raised the question of whether the current work groups should be redirected or reinstituted in light of said postponements, and/or if parallel work groups should be set up. (Would these be of value?) What this might be and how might this advance the work._ ######

* Action Item: This is the question to discuss between now and our meeting in March. 

###### _Dr. Dahl pointed out that we now have a foundation of architectural work that wasn't present last year, and suggested that perhaps some of the work groups set aside in 2022, such as VRS, could be revived - which would help our current groups become more focused._ ######

* Mr. Stine broadly agreed with this statement. 

* Dr. Dahl: the roadmap itself has grown complex enough that we have migrated it to Trello (she pulled up an illustration of this, at this point in the meeting).
* Dr. Dahl noted that our first two activities right now are: -working on a very basic, bare-bones demo, slated for early April, showing connection between agents and a -dialog packet specification. (Demo 1)
* Dr. Dahl also noted that work to come includes a second demo, a third demo, and overall interoperability specifications that includes the dialog packet as a component. The partner activities will include partner surveys (Tobias), a testbed specification (Tobias), and our agreements with partners - what specifications and demos they will be working on. Then we have an interoperability webinar on 3/22, a trustmark webinar (3/15) and the project voice conference (late April).


###### _Mr. Sewell asked about the demo and specifically what use cases we're looking at/what we are demoing._ ######
###### _Dr. Dahl indicated that Demo #1 has no use case, and merely illustrates interagent communication. Demo #2 and Demo #3 probably involve use cases that are a combination of automobile and restaurant - details TBD and subject to change. Will depend on what partners are interested in doing._ ######

###### _Mr. Martens added, bridging off of Dr. Dahl's comment, that we will be talking to partners through the surveys and gathering data points about what most interests them. The central goal with the demos is engaging partners and members and friends of Open Voice in launching the specifications. One possibility is enabling two different voice AI platforms to connect and communicate for advanced functionalities and hand-off of context - information, authentication, etc. - Another possibility: one interface using several platforms to answer to a customer request. These use cases should be chosen from the community. Ovon's role is to facilitate said prototypes not to define them._ ######

### Report re: Authentication Study Group - J. Stine (two slides shared)
* Critical to ask what our problem statement is
* Noted that once we enter the realm of interoperability this is inextricably tied to zero-trust security - it may mean pushing dialogues users through firewalls that requires all users be authenticated, authorized and validated.
* There are two situations on our radar: conversational assistants seeking to collaborate with other conversational assistants, where identification/authorization/validation between assistants is necessary prior to sharing information; and a situation where human users are passed from one assistant to another. In the latter case there are necessary processes
* Also appropriate (or necessary) that, for generative voice, we establish certain standards in the user authentication process
* To this end, Mr. Stine presented another slide, with authentication broken down into individual steps, in turn asking 'What is the potential role of the Open Voice Network, and where does this work overlap with Destination/Location Services?' If an asst. is identified as part of an authentication process, there are apparent overlaps. 
* OVON should also not think about creating from scratch, but adapting work that has already been done. The team must ask what it needs to create, and where it comes into the equation.
* Work needs to be a combination of: -how discovery and location/vrs fits in, -what are the rules and expectations here, and -how does this fit with the rest of an authentication process?

## Mr. Stine's recommendations - Action items
* OVON re-forms its Authentication Study Group
* A first task - for that group to correct the chart presented on the left - identifying where there are holes and where there are not, and where OVON needs to adopt vs. create from scratch
* OVON reforms Destination/Location Services (or perhaps this and Authentication overlap) and bring this forward
* OVON will have a conversation with an Enterprise Solution Architect to address the delivery architecture (high security, low latency, fitting across a world of billions of assistants)


###### _Dr. Larson asked if 'authorization' includes privacy constraints? Is there overlap with the privacy/security area? And does it overlap with watermarking/tamper detection?_ ######

###### _Mr. Epstein: these are not overlaps but dependencies - so the people defining the requirements for privacy/watermarking will feed into this. This is where the implementation will occur._ ######

###### _Mr. Sewell at this point asked Mr. Stine if the Open Voice Network is planning to create a voice authentication standard._ ######

###### _Mr. Stine expressed his uncertainty in response to this question but a sense that our research will take us there - though we don't know what this will entail or require._ ######

###### _Mr. Sewell asked Mr. Stine secondarily if this decision will grow out of the revamped and relaunched Authentication Study Group._ ######

###### _Mr. Stine stated that it could very well be a recommendation of that group._ ######

###### _Mr. Stine formally presented several action items as presented above before Mr. Wüttke and the Technical Committee:_ ######

* Re-form the Authentication Study Group to review, revise the task delineation shown on this slide, with submission of final recommendation 2023.03.31. 

* Re-form the Destination & Location Services (VRS) Work Group to address – with a recommendation – the standard data definition of an interoperable assistant, with submission of published recommendation 2023.03.31. 

* Recruit a proven enterprise solution architect to address issues in line #8, with submission of published recommendation by 2023.04.30. 

###### _In response, Mr. Wüttke advised Mr. Stine to go ahead. No objections were presented._ ######

### Q&A Session - Group
###### _Mr. Sewell asked for clarity on the expression 'The North Star' and in response, Mr. Stine returned to Dr. Dahl's slide and limned three priorities for 1H 2023: -publish specifications/interop demo, -launch the Trust Mark program, and -Jon will do his pipeline work wrt raising money and building sponsorships._ ######

### Adjournment - Mr. Stine adjourned the meeting at 11:00am.


# Notes of the Technical Committee Meeting - January 13, 2023

### Attendees: J. Stine, N. Southern, O. Coleman, J. Larson, T. Martens, D. Dahl, C. Scott, E. Sewell, H. Pappas, B. Epstein, Y. Eristiren, M. Buyuktuncay, U. Yasik

The Meeting Began at 10:04am ET.

### Notice of Recording - J. Stine
### Linux Foundation Anti-Trust Statement - N. Southern

* We had a quorum today and approved the Dec. 16, 2022 Technical Committee meeting notes with a first motion from Mr. Stine, a second motion from Ms. Coleman, and no immediate objections presented. 

### Introductions from three new attendees, Yalim Eristiren and Mert Buyuktuncay, and Umut Yasik, of Sestek.

### Review of the agenda, purpose of and expectations for the meeting  -- T. Martens
* Update by Mr. Stine on planning for 2023
* Current status of the OVON Roadmap led by Dr. Dahl
* Mr. Martens will present options and scenarios for 2023 budget planning
* Ms. Coleman will discuss plans for the OVON Trustmark project.

### Jon Stine - 2023 Planning
* Mr. Stine presented a slide to be reviewed by the Steering Committee
* The Technical Committee has a new cadence - second Friday of every month
* The Steering Committee will now be meeting on the fourth Thu. of every month
* Chronologically, then the Technical Committee will now precede the Steering Committee. 

* Mr. Stine presented a one-slide view with a vision - that OVON's achievements do matter to the leading developers and decision makers in Conversational AI. The relevance is measured by their sponsorship and contributions. Immediacy and relevancy to the industry as it now exists - for use of Trustmark, interoperability tools, and other activities of value from 2023-25.
* Moving ahead means responding to the industry as it is, not how we think it will be.

* Mr. Stine then presented three prime strategies from this vision
     - We will be the experts in ethics, privacy & security for voice
     - We will be the global source for credible research/guidance on the ethical use of conversational A.I., including the ethical use task force for privacy and security
     - We will be the experts in interoperable voice assistance (The AWG has developed seven clusters/five modules that touch every inch of OVON's work), and translate this to areas of immediacy & relevancy in the industry - and create value for our constituents. 

* This leads to the question of how OVON can create value for its 200+ monthly volunteers, its participants, who bring so much value to us.

* Beneath each of the strategy buckets are Q1 execution priorities. Trustmark requirements, proposed specifications coming out of the roadmap. In the middle: 'Identify five areas of immediacy' - such as vertical industry, financial services, automotive, smarthome - or horizontal areas such as authentication payment. This can be used as a filter and a guide to prioritization. It won't change the interoperability work at present but it may bend it as it moves forward through Q1 and as we establish work relationships with demo and standards organizations. 

* Equally pertinent: a need for clarity in OVON messaging, friends program, executive education that we'll be testing and piloting this year, communication program and the like.

* Vision/Strategy/Execution followed by metrics

* The OVON Pivot toward immediacy and relevancy (through Q1)

	- We're researching several key areas and then identifying the immediacy & relevancy of OVON work in each of these areas. E.g. the automotive space (significant need here for interoperability - massive ecosystem), health care, social gaming, financial services, authentication/payment, restaurant

	- Horizontal areas: enterprise customer service call center (25% annual compound growth rate)

	- Enterprise content owners

	- Payment and authentication

	- We need to boil this down from 9 to 4-5 priorities or at least evaluate our importance in each of these key areas. Bring it closer to constituents' immediate needs. 

###### _Mr. Martens asked Dr. Dahl to review what she sees as the most important/critical points on the roadmap and to help contextualize them. In response, Dr. Dahl discussed several different workstreams that are ongoing on OVON, including the technical synthesis track, architectural principles track and the privacy & security track (Ms. Coleman). The synthesis work, born out of interoperability, will bring everything together in the form of 7 clusters of technical and privacy and security areas, each with ~ 5 types of activities that fit in there. A synthesis document will be published at the end of January and this will be our marquee activity that gives us a much bigger picture (master blueprint)._ ######

* A testbed specification document is forthcoming at the end of May 2023; other developers outside of OVON can work with it. We will be able to implement specifications and prototypes based on this design.

* Dr. Dahl Reviewed the Various Synthesis Clusters.

	- On top level: agent interaction is particularly critical (how interoperable agents communicate with each other and find one another) - different patterns of negotiation, interaction, etc.
	- Execution control - how does one start and end things? How does execution happen?
	- Trust, Integrity and Security - all things that have to be done to ensure that interaction is secure and trusted
	- Data integrity - closely related to trust, integrity, etc.
	- Data flow - how does data move through an application or a user session? How do we transmit data among the agents in an interaction?
	- Building blocks - fundamental specs agents use to interact with one another
	- In next couple of weeks, the group will be prioritizing this work in lieu of pursuing all of it at the same time.

##### _Dr. Larson noted that on Tue. 1/17, the Synthesis group will refine these activities and begin to prioritize them._ #####

##### _Mr. Epstein thanked Dr. Dahl for the diagram and noted that each bubble on the chart may represent one deliverable. To illustrate the breadth/depth of the scope we're attempting to accomplish, and the complexity involved - for him, this was the key revelation from the creation of the synthesis document._ #####

##### _Mr. Martens asked for questions about Bruce's synthesis work, but none were immediately presented._ #####

### Mr. Martens - Budget Overview

* For the fiscal year 2023, we have funding available and need to decide how to invest it most prudently
* This may dovetail with the testbed and prototype implementations.
* We're taking the results from the various working groups and use them as a foundation for a research study conducted over the next 8-12 weeks. We will be surveying members of OVON and external partners about the current state of our work. 
* We will be having our results peer reviewed and get feedback from partners, and get a sense of what kinds of voice AI implementations are available among our members, what opportunities exist for collaboration, and then how we can team up with members in our network to help OVON progress.

* This is an open process, and details will be announced in the next Technical Committee meeting. So far, the feedback we've received has been overwhelmingly positive. 

* Budgetarily we are looking at the implementation of a test bed, and need to decide how to allocate the budget and explore strategically (position) how we want to work, realizing the test bed implementations. 

* Mr. Martens outlined three possible options, each with different pros and cons.
	- $80,000 USD available to invest into the prototypes and test bed implementations
	- We might also invest in our own staff and team members, for instance, hire senior advisors or developers. 
	- Another option would be to contract additional development resources externally and outsource the developers among different external development partners or agencies. ($80000 is perhaps not enough to sustain this). 
	- A third option would be to crowdsource the development of prototype implementations to the OVON community and/or public. We might also give awards to the most successful implementation of the OVON standard.

* Here Mr. Martens opened the floor to opinions and feedback about how to invest these R&D monies - wisest use of the budget, etc.

##### _Mr. Stine added that we are budgeting conservatively for 2023 in part given a period of layoffs and economic downturn, and in part given the rapid approach of the end of three-year commitments that initially launched OVON. Should the sponsorship situation take a positive turn, the $80,000 number would increase. This is a floating number; in a conservative planning mode, it is currently at 80. Steering committee has always set aside R&D monies to accelerate the work. The Technical Committee must formally decide how the funds are to be invested. In what way and for what purpose._ #####

##### _Dr. Larson suggested adding a capstone project run by university students to achieve a targeted outcome - this could be a possible fourth scenario._ #####

##### _Dr. Dahl - scenario 3 can be pursued in addition to #1 or #2. These are not mutually exclusive. It can be done economically, with modest prizes. She noted that she and Dr. Larson have run previous competitions for AVIOS and XML forum and have this expertise. Dr. Dahl also suggested hackathons that are fairly economical._ #####

##### _Ms. Coleman asked a question about the categories for investment of the funds. She expressed her support and enthusiasm for funds to be set aside for the implementation of the Trustmark program, and wants to ensure that we are considering the work that needs to be done (re: implementation) in this area. For instance, one initiative is the development on the online self-assessment with the maturity model. This will require funds._ #####

##### _In response, Mr. Stine noted that the Privacy & Security Work Group reports to the technical committee, and the Trustmark program comes from the Ethical Use Task Force and the Privacy & Security Work Group. It thus falls within the Technical Committee Realm, and is a top priority for 2023 - it should be considered and prioritized as an investment._ #####

##### _Mr. Sewell noted that if the goal is to accelerate the work, $80000 is not a sufficient number for acceleration. He asked if there is any engagement with the sponsors on OVON and/or the Linux Foundation to fund this. In response. Mr. Stine noted that conversations with prospective sponsors are continually ongoing. Wrt direct investment sponsorship contribution to OVON, $80000 is where we stand._ #####

##### _Mr. Martens noted that the research process now ongoing will result in additional insights about what kind of voice AI implementations exist among OVON members that are suited to be integrated in the test bed. We are hopeful that our members & and sponsors will support the effort and develop implementations as part of this test bed - to such a degree that the $80000 wouldn't be spent on these implementations but instead we will look for professional facilitation during this process._ #####

### Update on Trustmark Program by Ms. Coleman
* We are looking forward to presenting our plans to the steering committee.

* This is an initiative we're working on to provide a trust or mark or brand of adherence to our ethical privacy and security policies and principles

* It will deal with topics related to data acquisitioning use, inclusivity, bias, compliance, transparency

* The Trustmark will be based on education, self-assessment and a maturity model, evidence-based with accreditation.

* Since the last meeting, we've continued our requirements interviews with great results. One took place with the ethics team at Deutsche Telekom; we found great synergy with DT and we look forward to learning from them - the models and algorithms and decisions around scoring that DT has in place.

* Wrt next steps we have several additional requirements interviews set up to fine tune the program.

* We will complete the Ethical Guidelines 2.0 white paper, set up follow up DT meetings, and work with Linux Foundation to design and launch program on Conversational AI Ethics, and are working on preparing a presentation for the Steering Committee.

##### _Dr. Larson inquired about a target date for announcing the Trustmark launch to the public; Ms. Coleman stated a target of late in Q1. The two deliverables initially be available are the training course and the self-assessment maturity model. Prioritization for the funding of that work will determine the date of delivery._ #####

### Action Items - Mr. Southern (recap)
* Prioritization of blocks in the synthesis group
* Q2 decide on how funds are to be invested for prototypes in the R&D area
* Set up next steps for Trustmark - e.g., continuing requirements interviews, continuing ethical guidelines and course preparation, and preparing a presentation for the Steering Committee meeting
* Mr. Stine: suggested that in looking toward February - we have the synthesis outlines, clusters and modules, and need to decide what comes next
* Mr. Stine also asked for proposals with regard to investment. 

##### _Dr. Dahl commented on prioritization and referenced Mr. Southern's list of prioritization filters and what factors we might take into account wrt prioritization. From the technical side, we need to gauge technical feasibility, but we need input from the Jon side (external marketing and management) wrt concerns or thoughts about what priorities will help strengthen our relationships with external constituencies. Then we can decide technical feasibility._ #####

##### _Mr. Stine agreed that this discussion is critical and suggested that everyone present take part in a related discussion on Slack using said prioritization filters as a guide._ #####

##### _Mr. Sewell asked about the timelines and the related roadmap - and if it is fixed or malleable (aspirational)._ #####

##### _In response, Mr. Stine returned to the roadmap slide and asked Dr. Dahl as the owner of the roadmap to response to Mr. Sewell. Dr. Dahl stated that the roadmap is not aspirational but intentional. It is not, however, cast in stone and is subject to flexibility as the need arises._ #####

##### _Mr. Stine noted that wrt the clusters slide - we cannot do everything at once, but we need to prioritize. The prioritization discussion will give us a sense of which bricks are 'placed in mortar' and which are still sitting in the pile to be built._ #####

##### _Dr. Larson expressed the opinion that the roadmap will always be subject to some degree of change._ #####

##### _Ms. Coleman asked wrt prioritization and anticipation that at some point we will be incorporating the verticals of health care, automotive, etc. - how that factors into the designated work on the roadmap - because depending on which work we prioritize, it may alter our trajectory. _#####

##### _In response, Mr. Stine noted in closing - hypothetically - that through our study of the verticals and the horizontals we will seek to find commonalities (e.g. authentication) across different areas of specialization. We will seek to define commonalities of greater and lesser priority and seek to bring those into the conversation. _#####


### Adjournment - Mr. Stine adjourned the meeting at 11:00am.







# Notes of the Technical Committee Meeting - December 16, 2022

###### Attendees: T. Martens, J. Stine, O. Coleman, N. Southern, J. Larson, D. Dahl, B. Epstein, E. Sewell, C. Wuttke, H. Pappas

###### Notice of Recording - N. Southern

###### Linux Foundation Anti-Trust Statement - N. Southern

###### There was no approval of minutes from the November Technical Committee meeting, as the group had agreed, during that session, to hold said meeting informally and not do minutes for it.

###### The Meeting Began at 10:07am EST.

## Review of the agenda, purpose of and expectations for the meeting  -- T. Martens.

###### OVON Roadmap & planning for 2023 ######
###### A Status review of the various working groups
###### An outlook for 2023 particularly concerning pilot projects
###### OVON Trustmark - related thoughts and issues

## Roadmap Update - D. Dahl. ##

###### _Dr. Dahl led attendees through the preexisting roadmap with new additions._

###### In the last Technical Committee meeting, the  committee discussed an OVON Technical Synthesis Document, which they realized is a critical document for aligning and pulling together all of Open Voice's activities in architecture, privacy & security, destination/location services and other areas. This will be published at the end of January.

###### The AWG completed the document Interoperability Patterns: Interoperable Dialogue Requirements and published it at the end of November, on schedule. The group continues to work on more details of specifications that would implement those requirements.


###### The technical synthesis document introduced dependencies in privacy and security so that those dates were adjusted to reflect their dependence on the technical synthesis. So the Privacy Use Case Aligned with Interoperability Standards - and the publication date moved from 12/30/22 to 2/28/23. The Security Specific to Voice 1.1 white paper was moved from 11/30/22 to 2/28/23. And the Privacy Use Cases Aligned with Interoperability Standards was moved to 2/28/23. 


###### The main new item on the roadmap is the Ovon Test Bed Specification work, tentatively slated for early May 2023.

###### _Ms. Coleman noted that OVON publication dates are not being modified arbitrarily but that all changes have grown organically out of the dependencies we're observing from Open Voice Synthesis work._ ######

###### _Dr. Dahl clarified that the "completion" criterion on the roadmap is having a document published._ ######

###### _To this, Ms. Coleman described the Privacy & Security Work Group process for document vetting and approval as being slightly more rigorous than the same process in the Architecture Work Group, and this should not impact the deadlines to which Privacy & Security has committed._ ######

###### _Mr. Epstein proposed to Ms. Coleman and Mr. Sewell, as reps of Privacy & Security, that they strive to maintain their end-of-year publication goals and reserve the right to incorporate changes if applicable a month or two later. He stated he hasn't seen anything emerging from Synthesis Work to date that can or should derail said publication deadlines._ ######

###### _Mr. Epstein also pointed out that the next product of the Synthesis group will be an answer to the question 'What are the next things we need to discuss altogether so that all of the workstreams can continue after what they are currently working on._ ######


**Action Item: Nathan and Debbie will go back over the revised dates and discuss their impact on the roadmap.**

###### _Here Dr. Dahl reviewed a series of activities that OVON has planned but aren't specifically on the roadmap. She indicated three tracks that flow out of the synthesis work:_ ######

* Specifications - design detailed requirements and specifications based on the synthesis document aligning all our technical work on architectural patterns, security, privacy, location, discovery, authentication and synthetic voice. 

* Software - demonstrate the viability of our specifications with prototypes and reference architecture.

* Outreach - educate and get feedback from our communities with webinars and workshops throughout 2023.


**Technical Outreach Topics Under Discussion - Dr. Dahl** 

###### _Dr. Dahl noted that these are not finalized, and need to be finalized and scheduled - the idea is to have one our sessions to discuss. They would be workshops or webinars depending on what the topic is._ ######

**Interoperability**
* Dialog Packets - what they are and what they're good for (Feb-Mar)
* Context and Dialog History Workshop - Examine Competing Requirements (April)
* Discovery and Location Services - How to Find and Access New Voice Agents
* Interaction Patterns Specifications
* Introduction to OVON Interoperability Reference Implementations

**Privacy and Security**
* Fake Voices - How to detect and avoid them
* Voice Passports - your entry to all voice applications and services
* Secure end-to-end connections - keep your conversations private
* Data sharing - control access to your voice data 
* OVON Privacy Guidelines

### Trustmark Discussion - O. Coleman (Ethical Use Task Force)
###### _Ms. Coleman noted that the core of the work involves putting OVON ethical principles in practice. Focus here breaks down into the following:_ ######

* Ethical Guidelines for Voice Experiences, v. 1.0
* Ethical Guidelines Self-Audit Checklist (for organizations, individuals to evaluate how they measure up to our ethical guidelines)
* Ethical Guidelines Maturity Model
* OVON Trustmark

###### _Ms. Coleman also reviewed the core ethical principles of Open Voice_ ######
* Privacy
* Sustainability
* Inclusivity
* Accountability 
* Transparency
* Process of Governance and Compliance Overriding Everything

###### _Ms. Coleman discussed the interviews and meetings that have been conducted to determine what the requirements are - the team has conducted with potential partners and sponsors that have expressed interest in Trustmark, with the question with what 'Trustmark' means to each company. The team has been getting a sense of their expectations from a Trustmark framework. 13-14 such listening sessions with major companies have been held - start ups and postential sponsors._ ######

###### Based on these interviews, the requirements have been placed in several buckets: ###### 

* Education (Training courses, with badges) - a couple of conversations with the Linux Foundation to create a basic intro course on ethical guidelines. There is an existing LF course on AI and ethics. An add'l course will be added on conversational voice AI ethics. This will be a free course. We are investigating other areas of opportunities, working with other institutions such as Univ. Central Florida, Royal College of Art. These conversations are in the beginning stages (providing executive education).

* Intentions: we want to achieve a trustmark, where are we relative to this. Self assessment and maturity model. Discussions forthcoming of how to adopt a model from the EU.

* Evidence: thinking about it from the standpoint of ISO 27001 - a third party comes in and says 'show me your privacy polices, your training policies, your training data,  is bias removed, etc.' Auditing your algorithms. Third party evaluation/certification engagement. Several OVON partners and even a few third party consulting organizations could assist OVON with this.

* Technology Solutions: one major potential sponsor - they would like one of their agents to receive a trust watermark, so that agent to agent communication would be better enhanced from a security/privacy standpoint. That way one knows which agents have gone through a validation process and are trustworthy. Another technology solution is synthetic voice detection - and the technology related to this. Another interviewee expressed interest in this.

###### _Ms. Coleman stressed that this is the framework toward which we're working. **Action Item: She also wrt a timeline stated that the goal is to develop a more concrete plan and present it to the steering committee and LF for approval. ETA: January's steering committee meeting.**  ######

###### _Dr. Larson asked Ms. Coleman to define what she meant previously by 'maturity model.' Ms. Coleman responded that a maturity model is where one has an audit or assessment list where companies assess where they are related to a principle. Once they complete assessment, we see where they are against the standard. The maturity model e.g. can show where they fall short in the area of privacy. They grade themselves on their privacy policies being not as clear or as understandable as they could be. The maturity model would say "where are you against the standard and what are the recommendations for improvements?_ ######

### Proposed Process and Set-up for OVON Pilots - T. Martens.

###### _Mr. Martens stated that he has been brainstorming how all the specification requirements and the work of the various work groups can be turned into a pilot project for OVON or a test bed of connected OVON services. However he stated that he's unclear on the specifics of the test bed - so it would help to get a better grasp on what AI/use cases are available in OVON's network among members as well as partners and other interested parties._ ######

**Action Item: Mr. Martens suggested a survey of OVON members about Voice AI use cases that members believe would be beneficial to them. - that would benefit from test bed integration, as well as criteria for what would make a pilot project successful for them.  He also suggested interviews with voice AI decision makers to follow up on this. The survey would then be followed up with the creation and launch of the pilots themselves through Q2 and Q3 of 2023. We would seek to bring partners together with strategic selection, making sure they are of equivalent size - or 'on eye level.'**

###### _Dr. Larson asked what distinguished the pilot project from a regular project. Mr. Martens clarified that as used here, a 'pilot project' is the first occasion of implementing a new technology whose specifications and requirements are outlined on paper. Also a showcase to demonstrate what OVON stands for. How can voice AI interoperability function, and what are the benefits from it? Why is it helpful? etc._ ######

###### _Dr. Dahl asked about the publication of requirements added to the roadmap for May 1st. She is unclear how this impacts or is impacted by the creation of pilots, and also what other kinds of publications will emerge from the pilot plans._ ######

###### _In response, Mr. Martens stated that the test bed specification on the roadmap is placeholder. He envisions that we will not be able to integrate all of the specifications/requirements but will need to agree on a set of requirements on which we want to deliver. Therefore test bed specifications will be a reduced set of specifications/requirements._ ######

###### _Mr. Sewell discussed Linux Foundation's 'Plug Fest,' where interoperability tests are done, and sponsors are brought in, and the interoperability of technologies in the real world is demonstrated live. He asked who from OVON would be sponsoring this pilot work._ ######

###### _Mr. Martens stated it must be the partners that want to showcase the technologies._ ######

###### _Mr. Stine: this is TBD - the key questions are 'with whom' and 'for whom' and these are open questions._ ######

###### _Mr. Sewell asked wrt measuring success - if OVON would set the metrics for what is a successful pilot. Mr. Martens stated that from a specifications and requirements POV, it would be up to Open Voice to qualitatively judge a given pilot and whether it delivers. However the judgment and perspective of the individual members wrt mutually beneficial is also pertinent._ ######

### Steering Committee Report- J. Stine

**Expression of Gratitude for Progress that OVON has Made**

**Recognition of the Value of Open Voice's Work**

###### _Mr. Stine noted that this week, he met with the conversation design team of one of the top banks in the United States - about 35 attendees. The topics that Open Voice is pursuing, the questions OVON is seeking to answer, and the future OVON has envisioned found widespread support with this prospective partner._ ######

**Execution in Q1 2023
_This will be critical to our success._
_We cannot ease up at this point._
_Execution is critical_
_Support for trustmark, interoperability, and the holistic approach are critical._

**Strategy Review & Thoughts.
_Mr. Stine noted that a pivot will be necessary of perhaps 15-25 degrees, especially in the interoperability work. This is not a matter of stating that interoperability work will be different, but asking who is it for and tweaking the recipients_

###### _We have seen Google and Amazon stepping away from their voice channels._ ######

###### _The prospect of an interoperable worldwide voice web is further out, but there are more immediate opportunities in several key areas:_######
* Automotive
* Healthcare and the Protection of Patient Data
* Smart Home
* Gaming/Metaverse/etc.

###### _OVON may want to pivot some of its use cases and pitches less to the World Wide Voice Web idea and much more toward the specific industry use cases where the question of interoperability lingers larger - such as the individual driving in his car who wants to use voice to transfer money over. How does Open Voice lead the way in this arena? The question is therefore not interoperability, but interoperability for whom?_ ######

### Discussion and Questions
###### _Mr. Sewell asked if payments are an area toward which we plan to pivot - as payments regularly impact security, privacy and ethical use. In response, Mr. Stine indicated that this did arise in the discussion with the aforementioned bank, this week, and is on Open Voice's radar._ ######

**Action Item: Mr. Epstein asked if there is a way for someone to write up a tactical direction that would guide the interoperability work, based on the 15 second snippet Mr. Stine just gave the team, but with enough substance to it that it can be used as a guide for decision making. Mr. Stine agreed to draft it just for the discipline of thinking it through. Mr. Epstein: we don't need it until the first week of January.**

###### _T. Martens: expressed enthusiasm wrt use cases for the research process he just outlined. Believes the interoperable world wide voice web is still within reach but some interim steps may be necessary to get there._ ######

### Staffing Discussion - B. Epstein (presented prepared slide accordingly)
###### _Mr. Epstein noted that we absolutely need to fill the following positions as soon as possible:_ ######

**Enterprise Architect**
* Can take up the relay of the synthesis work 
* Will then support that work
* Focused on 'are the things that are being done compatible with each other?'

**Technical Program Manager**
* Two dozen workstreams need to be managed
* They will no longer fit on the road map.
* We need someone who can decomplexify and manage this
* Focused on 'are things getting done?'

###### _Mr. Epstein noted that we could have one person managing both roles. Each one is 10-12 hours a week - but with one person working both roles they could be done combined for 15 hrs./week_ ######


**Action Item: Mr. Stine will review the Enterprise Architect and Technical Program Manager requirements and pursue the two candidates he has in mind.**

###### _Mr. Stine noted that he has two Enterprise Architects in mind for these roles._ ######

### Adjournment - Mr. Stine adjourned the meeting at 11:00am.






# Notes of the Technical Committee Meeting - October 21, 2022

### Attendees: J. Stine, N. Southern, C. Wuttke, J. Larson, O. Coleman, D. Dahl, B. Epstein, E. Sewell

We lacked a quorum today for approval of notes from the 9/16/22 meeting.

The Meeting Began at 10:02am EST.

### Notice of Recording - J. Stine
### Linux Foundation Anti-Trust Statement - N. Southern

### Review of the agenda, purpose of and expectations for the meeting  -- J. Stine
* A high-level report with notes from the Steering Committee
* October work group reports and outlook starting with technical roadmap and dependencies schedule
* Nov 9-10 Interoperability Webinar and Workshop (J. Larson)
* Notes on security specific to voice and next steps from Ms. Coleman and Mr. Sewell
* First draft of a redirection on destination and relocation services
* Closing Comments

### Steering Committee Meeting Update from 10/17/22 meeting - following key conversations were had:
* Affirmation and encouragement about the performance of OVON, if using the Tuckman model Storming-Forming-Norming-Performing-Transforming of org. development. OVON has reached the performing stage with validation of this from the Steering Committee. The next step is transforming, and this equates to key tasks in 2023. 
* The monthly cadence of draft specifications that is now planned for Q4 2022-Q1 2023
* Conversations about an OVON trustmark starting in Ethical Use
* The possibility of professional education relationships with the Conversation Design Institute and University of Central Florida which has adult/external education/certification program. They have reviewed OVON's work and see it worthy of further discussion where professional education in voice for content mgrs. and voice developers could be developed in conversation with the CDI and OVON. Greater awareness and exposure for OVON. 
* Questions raised by Mr. Hochstatter about major KPIs Q4 2022-Q1 2023. Several topics could lead to KPI development: affiliation with relevant standards bodies (IEEEs, W3Cs, IETFs). Outreach to said standards
* Creation and development of awareness/participation in voice developer community
* Programs of value delivery for sponsors/participants. (e.g., privacy & security technologies, reference architectures, guidance in privacy/security/authentication realm, professional education, a friends program, widgets - i.e., reference architectures for technologies that could be developed for OVON
* Interoperability demo envisioned by Dr. Larson - showing our vision to the world. 
* Increased fiscal and organizational strength.

### Industry Outreach Updates - J. Stine
* Voice 22 Voice & Business Bootcamp - Voice & Healthcare Track
* Voice and healthcare bootcamp in Malta at a healthcare event - partnership with Conversation Design Institute - vendor neutral
* Interoperability 6 hour webinar on 9-10th of November. 

### Technical Roadmap Review - D. Dahl
Dr. Dahl led us through Q4 2022 and Q1 2023.
* Close to publishing our overview of patterns of agent--->agent delegation - first publication targeted end of Oct.
* Simultaneously publishing an updated version of Interoperability White Paper with newly incorporated comments. (Over 60 so far).
* November: patterns for interoperable dialogues - will take us into the granular level of agent interoperability communications.
* End of Dec.: Architecture group will be updating Oct. document with add'l requirements on arch. patterns and specifications for delegation and will add some interoperable dialog requirements
* Q1 2023: documents will be published with dependencies on privacy, discovery/location, and authentication (end March 2023).
* Publications at end of October on security specific to voice. 
* End of Dec.: Privacy 3.0 Guidelines and Privacy Use case. **Privacy will be aligned with interoperability**. Jan. '23: commercial privacy guidelines to be published.
* 2 activities just starting - authentication and destination and location services - target of destination/location paper 2/28/23
* Dependencies have been laid out. Architecture work dependent on privacy, destination/location services and security. Will come into play at end of Jan. with privacy paper publication from Architecture group. Our general policy: any dependency document should be published 4 wks before its succeeding document.
* J. Stine noted: we need to keep a close eye on the dependency work - (e.g. destination/location services - this may slide - and we may move personal authentication out further). Any scheduling adjustments will be brought to this body for approval. 

_Mr. Sewell asked at this point if we have a Program Manager identified to own the plan and do we have an Enterprise Architect who can drive the technical components and make sure that they all work together in synch? Mr. Stine: Nathan will lead Program Management for Integration with help from Dr. Dahl. Re: Resource Allocation, resources are in budget for moving into 2023 to support work. We do not have an enterprise architect but Mr. Stine deferred to Mr. Epstein, Dr. Larson, Ms. Coleman, Dr. Dahl et. al., on where and when we need this talent and how to bring it in_

_Dr. Dahl noted that while critical, this won't come into play for a few months because we lack concrete specifications that we can use as the basis of software. Mr. Epstein: the need is closer than we think. Integrations will begin on January 1st. Ms. Coleman agreed. Mr. Stine noted that this position will be ongoing_

_Mr. Sewell also noted the importance of having the technical architecture in place to test interoperability, and stressed the fact that whoever we hire needs Conversational AI Experience with Language Models, Database Experience, Conversational AI Data Management.

_Mr. Epstein suggested that we recruit/hire two Enterprise Architects, not one. One that has the necessary breadth for conceptual architecture to help with specification integration, and one with sufficient technical baggage to set up a testing lab. The integration function is critical. 

### Interoperability Workshop - 11/9-11/10 - Dr. Larson (schedule presented)
* Deep discussion on how delegation works w/corresponding examples and Q&A (First morning)
* Parallel sessions delving into privacy and the ways of describing data. Parallel sessions will be interactive with a great deal of user feedback.
* A panel discussion about what lies ahead and what needs to be done
* The problems people see and how can they be solved. Opportunity for participants to participate
* Afterglow period at the end of each day emulating social hour at ends of conferences. Several special interest groups here - interfaces, databases, etc.
* Mr. Stine: publicity on this will go out to more than 1000 people next week. Also personal individuals going out from leadership team. Attendance goal: 50+ people. Many will be newcomers.

### Updates on Security Standards Recommendations - Ms. Coleman and Mr. Sewell
* Group published an earlier version of Security Guidelines Document v. 2.0. Working on 2.1 that will published and avail for review end of Oct.
* Version 2.0 - two security standards recommended: secure voice identification of human users and conversational agenda, and the other secure multiconversational agent data sharing.
* Ms. Coleman and Mr. Sewell then identified - with an accompanying chart - all the different types of personal data that be collected from a user's voice. (A chart presented on the screen - Ms. Coleman). Ms. Coleman noted that if not properly managed this data can be used in numerous ways.
* Mr. Sewell discussed add'l recommendations, next steps, and path forward for security work. Reviewed zero trust network access model. Noted that velocity is leveraging zero trust as the model for voice and conversational AI-enabled security processes, which align with various other business processes (payment processes, eg., with high security requirements), to analyze and share data. 
* Mr. Sewell also discussed collaborating with other standards bodies such as the FIDO alliance. Apple, Microsoft & Google are collaborating with FIDO and rallying behind it as a default identification standard on smart devices and eventually in IOT. He noted that he's working on integrating voice with FIDO. 
* Mr. Stine noted that OVON had a separation authentication study track, and this suggests that that group, and security/privacy, have come together/merged. (Mr. Sewell agreed with this - unifies personal authentication and secure data sharing between multiple agents). 
* Mr. Stine also noted that another strand of authentication involves the yet-to-be-scoped pursuit of individual voice passports, and the work Mr. Sewell is discussing can serve as a foundation for that. 
* Mr. Sewell also discussed world of host agents and delegate agents. Host: needs/desires/wants of the human. Interacting with conversational agents to perform tasks on their behalf. Touched on Velocity conversational AI referenced architecture which has already been deployed with a number of partners. Goal of enlisting this architecture: acceleration of the work of the Privacy/Security Work Group but the Interoperability Team.
* Ms. Coleman: noted that first step in this process is requirements identification in the white paper at the end of October. The personal authentication scope of work is listed on the roadmap as a dependency, feeding into the security authentication patterns (3/31/23) - so as we define the work, some things may be shuffled; depends on SOW and resources available to do the work. 

_Mr. Stine noted briefly a conversation from the Architecture Work Group about patterns and giving new names to patterns and the AWG will determine what that vocabulary will be. The phrases 'delegation' and 'mediation' may change but should do so ASAP so we can begin circulation of new terms throughout OVON._

### VRS Work Group as a Foundation for Our Work Moving Forward - Mr. Stine 
* Primacy achievement was a demonstration of POC showing how explicit requests could lead to a connection inside or outside a host platform. i.e., an explicit request leading to delegation. They also demonstrated minimal viable contract necessary for a level of authentication, and the latency criteria.
* This work can serve as a foundation for our work moving forward.
* More broadly, we should think about an enlarged scope for voice registry, and can we change this from voice registry to destination and location services? For the interoperable world, we must enable the ability to find explicit content and destinations/disambiguate that; we also need to increase findability for destinations and content. How do we improve discoverability of those who are working in voice and seeking connections, and how do we enable this (operational delivery, mgmt and governance). Is this something OVON itself takes on, or an external service? 
_Mr. Epstein asked about explicit vs. implicit request - Mr. Stine noted that this should be included in "be discovered."
* Mr. Stine noted that we may foresee a destination registration with multiple layers - content or services within the destination. Processes and protocols for finding and connecting. Could be a standard metadata scheme that could be adopted for finding and discovery of content. And then governance of this - a big question but one that needs to be addressed.
* Mr. Stine presented a first draft that he's reviewing with members of the original VRS group. Anticipates bringing this forward to a finished working document brought to this body in a month. 
* Also noted that we have traditionally emphasized decentralization as opposed to a centralized registry.
* 
### Action Items and Corresponding Ownership
* Dr. Dahl and Mr. Southern - cement basic editing timeline for Interoperability and place it on the personal calendar with corresponding dates
* Dr. Dahl and Mr. Southern - Program Management - oversee the passage of documents and information from one group to another on the roadmap (calendared dates).
* Mr. Stine: author a first draft set of requirements for the Enterprise Architect position(s) that will be circulated to the individuals on this call. Also there should be estimates associated with how much work time we think each person will occupy. (Full time? Part time? etc.) (Move quickly).
* Once approved, this group - Mr. Epstein, Dr. Larson, Ms. Coleman, Dr. Dahl, Mr. Sewell - will formally respond to this google document within a week.
* Mr. Stine:  bring final version Mr. Wuttke for review and then to the steering committee for approval at the appropriate time
* Said group and Mr. Stine will begin the process of recruitment.
* Mr. Stine: prepare a first draft announcement on the Interoperability Webinar of 11/9-11/10.
* Mr. Epstein, Mr. Larson, Ms. Dahl: finalize terms 'mediation' and 'delegation' ASAP., and Dr. Larson will add this as an agenda item for the Interop meeting of Tue. 10/25.

### Adjournment - Mr. Stine adjourned meeting at 10:58am.

# Notes of the Technical Committee Meeting - Sep. 16, 2022

### Attendees: J. Stine, A. Paik, E. Snider, N. Southern, D. Dahl, N. Myers, B. Epstein, E. Sewell, C. Scott, J. Larson

## The Meeting Began at 10:01am EST.
* Mr. Stine acknowledged that Mr. Christian Wuttke cannot be present today due to a family commitment.

### Antitrust statement and notice of recording  -- J. Stine

### Roundtable Introduction of New Participants and Guests - Evan Snider, Alissa Paik, Ed Sewell, Carl Scott. 

### Review of the agenda, purpose of and expectations for the meeting  -- J. Stine

* Mr. Stine acknowledged that we will begin with a review of the Senior Technical Advisor Position hire and then move into a discussion of the Interoperability White Paper. Mr. Stine asked Dr. Dahl to lead this discussion in the absence of Dr. Larson. (Note: Dr. Larson joined subsequently)
* Mr. Stine also acknowledged a primary focus of this mtg.: presentation of draft 2022/2023 technical roadmap to be reviewed today, by Mr. Wuttke upon his return, and very soon, by the Steering Committee. 
* We will also review deliverables using a new format today. 
* This will lead into bigger questions to be discussed with Evan and Alissa re: how we promote, communicate, etc.

### Review of Notes from 2022.08.19  meeting –J. Stine

* Notes accepted - first motion from J. Stine second motion from Mr. Crabb. 
* Unanimous approval.

### Review of Senior Technical Positions

* Mr. Stine:   Dr. Dahl now serving as Senior Technical Editor for Interoperability, and thus responsible for corresponding white paper, and interoperability contributions to roadmap.
* Also we are in discussion for someone to serve as senior advisor for technical committee, replacing J. Stine and assisting C. Wuttke on technical committee from sponsor side, in developing agendas, managing GitHub, managing the master plan of OVON - combination of all OVON work. Candidate very interested in role and will bring expertise to role in conversational assistance, standards development and overall voice tech, but we are dealing with related visa issues that are being worked out with Linux Foundation Legal.

* We've also been asked by Steering Committee @ OVON to consider another part time investment in a senior advisor role. We are therefore looking at another appointment of a part time 10/20 hrs./month senior advisor role and related fiscal investment. Steering committee has asked Mr. Stine to come back to them in Oct. '22 with ideas about how we can and should invest to accelerate work. Encouragement of progress we're making but also impatience to move faster. Further investment in personnel to move this forward. 

### Interoperability White Paper - D. Dahl & J. Larson - Process followed, lessons learned, next steps.

* Dr. Dahl: interoperability white paper published 8/18/22. Fairly substantial; dcovers whole perspective on conversational interoperability/applications. We've solicited comments via soft launch from a friendly audience. 200+ solicitations to review the paper. We've received a response but it has been somewhat limited. 36 comments from about 4 people so far - good and constructive, but below our expectations. Mostly clarifications. No comments insinuating entire white paper as misguided.  
* By end of Sep.: new version with typos and clarifications will be released to general public (larger group) with typos & other corrections incorporated - paper will also be sent out to general public for comments.
* Mr. Stine: general release directed to friends, family, also general notes issued to experts in voice community, eg. Brett Kinsella, Bradley Metrock, etc., soliciting feedback from them. Also will be released and made known through social media. 
* Mid-Nov workshop seminar/webinar. Format and length TBD, content focused on explaining not only the paper but next steps coming from the paper. Draft messaging protocols/specifications. Potential standards will be shared and discussed as well.
* We are also asking for comments to come back by end of day today. A gentle deadline.
* Request from Mr. Stine to Dr. Dahl re: updated slide. Dr. Dahl pulled up a consolidated technical road map on screen accordingly, including both interoperability architecture milestones, and privacy and security milestones, that takes us through first quarter of 2023. 
* Dr. Dahl: part of focus re: revisions of interoperability white paper - ongoing reviews -  deciding what to do with extra material in appendices.  Several other inclusions to consider re: new material to be potentially folded in. General orientation - white paper - toward overall approach. Ultimately we will be working toward ##specification documents##. One concerning Delegation will be published in early October. One on Payload data history will be published in November (what information will be passed around? history of interaction?). 3 additional docs to be published in early 2023 re: Security & Authentication, Data Sharing & Privacy Patterns, and Discovery & Location.
* Dr. Dahl: how we organize it will really depend on what the content additions are.
* Mr. Stine: should we consider these additions next chapters? We need a framework to be thinking about this. Next chapters, incremental add-ons, etc. What do these represent?
* Dr. Dahl: we can call these architectural patterns & specifications, we have not agreed on the exact title yet. 'Chapters' might be a strong way to talk about it. Organization/structure will become clearer with time.
* Mr. Epstein: each of these additions brings more clarity with requirements layering on top of the underlying patterns. He is unclear whether these will be new chapters or paragraphs in existing chapters. Ultimately we'll be working toward a three-dimensional document. 

### Privacy & Security Work Group - N. Myers & O. Coleman

* Mr. Myers: re: Commercial Privacy Guidelines document. We are taking a deeper dive into voice-specific privacy, its capabilities and what we view as guidelines, since Q2 2022, (v. 2.0 paper) when we focused on a user/consumer perspective. Now, the questions are: how do we work more aggressively/concertedly toward standards on commercial/org privacy. Over the last several weeks we've been diving more deeply into voice-specific privacy as it relates to organizations, focusing on data sharing, how data is shared between organizations, etc. This is where we are headed.  Goal: to get draft done by the end of October. 
* Much of work circles back to what is data ownership and who owns data. We will make an effort to define this and get some specifics laid in stone. This is paramount to organizational privacy.
* Update to privacy guidelines document by the end of the year. Privacy Guidelines 3.0 to be published in Dec.
* Ms. Coleman: security guidelines white paper - draft forthcoming of update by end of Dec. Information will be included touching on beginnings of authentication.
* Ms. Coleman: This WG needs use cases aligned with interoperability work, as well as reference architecture. ETA: Q1 2023
* Mr. Stine walked through milestones in Oct. '22 - noted that delegation, payload & history will be in AWG. Howeve, data sharing & privacy patterns will be informed by and will be informing privacy & security WG. Noted that this is where the work of different groups begins to coalesce (especially privacy/security and authentication and interoperability). Publication in January indicates prerequisites before then, perhaps Use Cases. What is needed and when is it needed from Privacy and Security and Discovery/Location? And when is it needed to meet these goals? Key questions. This coord. btwn work groups is a gap. Needs to be closed before the next meeting of this technical body ~ within a month. 
* In response to a clarifying question from Mr. Epstein, Ms. Coleman pointed out that our current work concerns guidance and principles. Mr. Epstein: we can only do group merges 1 by 1, we can't do complexity of all of them at once. Group agreed with this strongly. Case study piece needs clarified.
* Mr. Sewell: agreed with this statement. In response to Mr. Epstein's question: on Security White Paper, document goes beyond guidelines and principles to start communicating specific requirements. Also advocated EA and Program Management resources, to help align workstreams. 
* Mr. Stine: raised questions about dependencies regarding the particular order of work that lies ahead especially in early 2023. Sequencing? 
* Dr. Dahl: in architecture group we are focused in interop. architecture. Needs to be provided w/requirements and use cases, because we need experts in Security & Privacy to ensure us yes property x is in our standards, etc., to ensure that requirements will be met.  
* Mr. Stine: discovery & location a potential hornet's nest. We may be obtaining requirements on data sharing & privacy patterns/security authentication long before discovery & location is worked out. Reaffirmed Mr. Epstein's point that work needs to be incremental and sequential. (Dr. Dahl expressed her conviction that Discovery & Location is most independent).
* Mr. Larson asked about Privacy Use Case Alignment/Interoperability Standards - will this be a standalone document or merged with Interop. Conversational Assistance Document? Or part of new Specifications Document? Ms. Coleman: doesn't see it as a standalone document. It will go in the Privacy Guidelines 3.0 but will also be part of the work of the Dispatch for the Interoperability Paper. We're not delivering a tech document. Interoperability Group will cover those technical specifications. Work will need to be coordinated re: what this looks like. 
* Mr. Stine: also wants a decision made today. The statement of principles & requirements is responsibility of individual WGs and should be standalone documents. Specifications will be responsibility of Architectural Work Group. Principles/requirements will feed architecture which will turn it into the specifications. This is a working model that we can pursue. AWG will own data sharing, guidelines and principles, & use cases will be owned by Data & Security. (Ms. Coleman and Mr. Myers agreed with this). 

### Confirmations of What We've Agreed on and Need - Mr. Stine & Dr. Dahl
* Dr. Dahl noted standard two-track development process. One is specification document development (this takes the lead). Noted many steps - group reaches consensus, we publish the document, we get family/friends comments, we do revisions in an ongoing process. We will also be producing demos & frameworks 3rd parties can use to develop their own prototypes and systems. i.e., Parallel software track with github repository/design of system architecture. We obtain any other 3rd party software to test for interop., implement a test & demo system, and then keep the demo system and specs in synch by having them inform each other. 
* Mr. Stine: proposed that we adopt this as our template, guided by Dr. Dahl. 
* Mr. Stine: takeaways. By next meeting, in a month, the P&S & VRS workgroup will have identified what steps and by when need to be taken to inform and enable the publication of specifications as defined in roadmap in designated time. Second: we've agreed the individual workgroups - privacy & study and VRS - will be responsible for principles, use cases and requirements. However specifications themselves will be developed by Architecture Work Group.

### Adjournment - Mr. Stine adjourned meeting at 11:00am.


# Notes of the Technical Committee Meeting - Aug. 19, 2022

### Attendees: J. Stine, O. Coleman, N. Southern, N. Myers, C. Wuttke, H. Pappas, D. Dahl, B. Epstein, J. Larson, D. Rogers

## The Meeting Began at 10:02am EST.

###  Introductory Matters
* Welcome to Everyone by J. Stine
* Reading of LF Anti-Trust Statement by MN. Southern

### Updates from Steering Committee Meeting of 8/11/22 especially concerning senior advisor position, hires that were approved and some shifts in their responsibilities.

### Review of Technical Advisor Hires by Ovon - PFC Program

* R&D funds approved by steering committee in every case except for 1 (Sr. Advisor to Tech Comm) - Legal issues surrounding this re: visa/immigration 
	
* Emphasis moving forward will lie on development of developer community surrounding OVON and small new voice firms that will carry industry fwd.

### Individual hires

* O. Coleman - continues with expanded responsibility
* J. Larson - Continues to lead AWG assisted by Mr. Epstein - will be looking at how we manage & lead for destination/location services. This may be added to J. Larson's portfolio.
* D. Dahl - responsible for technical editing on interoperability work last voice & pen on papers going forward, and responsible for revisions of current paper. Development of relationships with technical standards bodies, academic communities, etc. Management of key processes. (Here Ms. Dahl introduced herself and ran through her background).

### Interoperability White Paper

* J. Stine announced that we just distributed to 190 individuals 1.0 or 0.1 friends & family - with a number of key messages. Including "this is what we believe, this is how we will do it and this is the world toward which we're 	building. Follows up strategic committee conversations in direct way.	
* Paper is in Git Hub; also in .pdf form that was sent via a newsletter email.
* Also shared summation deck of 9 slides. Went to a friends and family mailing list - 
* J. Stine encouraging copies sent via email to those not on the initial list.
* Review of mechanisms for getting and receiving feedback - groups.io, pull requests on github, and groups receiving comments through email.
* J. Stine asked attendees for any comment or things to add.
* D. Dahl asked J. Stine for a copy of the original list of recipients to avoid duplication in individual outreach - Mr. Stine agreed to send her this.
* Dr. Larson encouraged everyone present in group to review document and send us comments; majority of those present affirmed that they did receive.
* Mr. Stine outlined the process, moving forward. This is the preview version. Target # of comments by mid September. After this, another version will be developed. In original document, 20-25 pages of appendix contained content that hadn't been worked into body of paper. This is still work as yet to be done.
* No consensus about its inclusion in the paper. Add'l content beyond the appendix may grow from the AWG, Privacy & Security, Ethical Use, etc.
* Paper will grow and mature and play a key role in the growth and development of the OVON Master Plan in Github - this will give us an opportunity to update that CONTENT and bring it forward.

### Work and Study Group Updates - roadmaps, y. 2022 updated headline, and deliverables through year end 2022. Each of groups: focus on integration interoperability - where, how, when, what. Guiding hypotheses.

* Mr. Stine presented a slide for overarch. OVON roadmap - to be updated as we learn and discuss groups today. Placeholder.

### Ms. Coleman & Mr. Myers - Privacy and Security Presentation
* Mr. Myers - moving on from Q2 '22 v. 2.0 document which was about voice-specific privacy (user/consumer focus). Focusing more on commercial privacy/organizational privacy. Over last several weeks we've been diving into the nuances of voice-specific privacy as it relates to organizations and their data sharing and the mechanisms to protect data sharing when transferred btwn organizations. 
* Asking questions about what is data ownership/who owns data? And how do we break this down to a voice-specific context. 
* Ms. Coleman: Privacy Guidelines 1.0 will be updated. Draft should be completed by end of October '22. Organizational privacy paper will be published early '23.
* Ms. Coleman:  Group is also working on Security Guidelines white paper. Looking long term at how this fits into interop. standards. End of year: a secondary draft should be completed.
* Ms. Coleman: looking forward to leveraging groups.io. Also referenced commercial privacy guidelines and pointed to potential reissue of privacy white paper to get feedback so we can incorporate it into v. 3.0 by the  end of the year.
* Comments on commercial privacy.  Mr. Stine: this work will assert a right by privacy for commercial data within voice dialogues. Asked Mr. Stine asked Mr. Myers and Ms. Coleman to share initial hypotheses. 
* Mr. Myers: we need to redefine commercial privacy - has been user focused but commercial entities have a right to data privacy as well, especially re: interoperability. How is that data kept within an ecosystem without necess. having to be shared. Ms. Coleman: only add'n: few regulations re: commercial privacy, many globally for privacy but not commercial side. EU adopted DMA - a great first step re: asserting rights of commercial entities in add'n to consumers.
* Mr. Wuttke: very much looking forward to add'l enhanced guidelines and elaborations on commercial privacy. Guidelines in this area are critical.
* Mr. Larson: section in interop. document on privacy needs to be extended - will be looking to Mr. Myers and Ms. Coleman for rewording of the document. Specifically areas concerning enforcement, surveillance, etc. Asserting a right of privacy - how can it be enforced, 	managed, monitored. Ms. Coleman: critical to define what the parameters are - enforcement, surveillance, etc. Is that trust but verify, behind the scenes validation, etc. Critical that we understand what this means by "validation." How do we monitor communication?
* Mr. Pappas asked if we're addressing issues within the health & wellness community on the privacy roadmap. Mr. Myers:  yes, although the first privacy white paper didn't cover health care specifically. With commercial privacy guidelines, we can segment out and address different industries including health care. Ms. Coleman: we can describe industry-spec. scenarios.
* Mr. Rogers: should we include specifics around content that's transpired btwn two entities. Where does this begin and end? Does content matter in privacy guidelines? Should we take it to a granular level of data classification, e.g., medical data that should be protected versus more innocuous personal data?
* Mr. Pappas: should we also extend privacy & security to nonprofit sector? Mr. Stine: a nomenclature change may be appropriate. "Commercial privacy" may be too narrow of a classification.
* Headline & deliverables - Ms. Coleman: new approaches to data privacy for consumers and commercial enterprises - FTC. has proposed regulations on surveillance and data privacy - request for comments due by Sep. 8th - 	working on a response from OVON. Broadened headline to include commercial/organizational in addn to consumer

### Security Group - Ms. Coleman - Updates
* White paper draft is in process of copy editing  - Ms. Mandel will have this done by the end of this month.  Using groups.io for feedback
* Inviting suggestions about who we can send this to, more broadly.
	
### Ethical Use
* Ethical guidelines v 1.0 completed and released
* Webinar completed in June
* Assets/collateral/power point decks/graphics have been put together - getting more eyes on it. 
* Guidance on how to operationalize the guidelines - Asking how other orgs operationalize that. We're going through the process of creating self-audit checklist and will do a test pilot with some friends and sponsor orgs to be sure we have it right.
* This should be completed by October 15th. 
	
### Architecture - Mr. Larson & Mr. Epstein
* Mr. Larson - update of roadmap - shared this on screen, slide.
* New version of interop. white paper issued each month - v. 0.1, v. 0.2, v. 0.3, etc. Ms. Dahl will summarize changes as they occur.
* Information from appendices will be reviewed/possibly reincorporated
* New material being worked out - in area of delegation. Data load and history and sharing. More will be worked out toward the end of the year. Concentrating on individual aspects one at a time.
* Next week: (Wed. 8/24) webinar on conversational agents
* November: deep dive workshop - active participation from attendees. Participants will write sample scenarios on working with multiple voice assistants. Prototypes may be developed based on these scenarios. Attendees will be asked to give advice on how they think we should describe aspects of data - structure, schema, format, etc. Many alternative ways to represent data. We are working twd standardizing right approach.
* Mr. Larson and Ms. Dahl will be reviewing comments to white paper as they come in.
* Independent group doing a VRS study report - should be available in a couple of months. Activity may take place in AWG or may be a sep. group.

### VRS Group - Mr. Stine 
* Relabeling VRS in white paper as "destination and location services."
* A placeholder pending formal review and recommendation by this body.
* VRS team has taken a step back, reviewing potential opportunities for OVON in this space. 
* Recommendation to technical committee will be brought fwd by mid-September by architecture and VRS teams.
* Rethought currently taking place, new work building atop the old from 2021

### Thoughts/comments/suggestions from group about AWG.
* Ms. Dahl: questions about webinar: should we try to market this to colleagues? Linked in posts, etc. Mr. Stine: more information forthcoming on this later today.
* Mr. Epstein: noted that over the next few months as we make progress on various aspects Jim has highlighted, we'll be in a position to work more closely with some of our partners who are implementing similar things in the current marketplace. We're reaching the point where we may want to reengage with less active partners as we define new formats, data sharing 
principles. We may want to benefit from existing marketplace implementations as demonstration. Especially as we define delegations, payload, history, formats, etc. 
* Mr. Pappas: asked to schedule a call with Mr. Larson to walk through some of these areas. Mr. Larson agreed to send an email facilitating this.
* Mr. Larson: developing a preliminary user scenario on interactive voice agents to form basis of future work. Will chat with people individually about writing these scenarios and implementing prototypes to test assumptions. To get a sense of how it will work. 
* Mr. Stine: one suggestion. Question. On this roadmap where can we publish initial messaging protocols or specifications? How soon can we give development community something to play or work with? Can we put on roadmap as parallel stream?
* Mr. Larson: in weeks ahead we will be doing a deep dive into delegation. One of outcomes of that dive will be a preliminary description of delegate vs. demand. Will include various parameters we hope to identify. This will be part of incremental releases. Start in October of preliminary 	specifications. Mr. Larson committed to putting a dotted line or 
placeholder on this etc. 
* Ms. Coleman: re: building up friends community. Offering special webinars/sessions for friends. Put a date on roadmap of when specifications will be available - one way to heighten participation: suggested special session for friends and participants. Good opp. to share with friends outside of the work groups. Mr. Stine asked Mr. Larson to put in a placeholder for sub-issue.

### Headlines/2H Deliverables - here Mr. Stine pulled up a corresponding slide.
* Mr. Stine asked Mr. Larson to call out any pertinent deliverables for the AWG and any corresponding callouts.
* Incremental updates to the working draft
* Deep dive workshop coming in November.
	
### VRS
* Mid-Sep: delivery of position paper on destination and location services using name as a placeholder and submitting this to Architecture Work	Group and the Technical Committee.
* Potentially the re-formation of VRS Work Group or Destination Location Svcs Work Group depending on how prior discussions go/guidance in AWG and decisions in Technical Committee
* Publication of VRS/Destination Location Roadmap - from this point, TBD
* Mr. Stine pointed to a need to find and discover not only destinations and locations but also content. We need to enable the finding of both. There may be a need for a registry, a standardized approach to metadata, a number of things as we learn what is needed in a world of delegation and mediation as specified and described by white paper. What is needed to make this work? This is the most pertinent question right now

### Mr. Pappas - comments - re: Health & Wellness 
* They have been interviewing health care professionals around the world on the impact voice technologies will have not only on remote patient monitoring but remote patient mgmt as well. No current voice use cases but wearables and sensors have made great progress. Pandemic pushed telehealth, telemedicine, and remote patient monitoring. With latter comes improved relocation management. This is helping people receive better, safer, less costly outcomes around the world. Forthcoming summary will be reviewed by executives in the medical community.

* Also developing a friends program and communities to help get the word out about OVON's work. working with Oita, Alissa, Jon, others, to develop give/get program.

### Adjournment - Mr. Stine formally adjourned meeting at 11:02am EST.


# Notes of the Technical Committee Meeting - 7/15/22

### Attendees: J. Stine, N. Southern, O. Coleman, J. Larson, N. Myers, H. Pappas, J. Crabb.

## The meeting began at 10:01 EST.

### Opening Remarks by Mr. Stine
* Greetings by Mr. Stine - acknowledgement that we do not have a quorum this morning. Waiting for Mr. Wuttke - without him we will have a very informal discussion. Content review only. 
* Mr. Stine invited Mr. Southern to read the Linux Foundation Anti-Trust Statement and Mr. Southern followed suit.

### Motion to approve June meeting minutes as posted in Google workspace & Github, by Mr. Stine. Unanimously approved.

### Updates from Steering Committee Meeting - run through of slides in Steering Committee 
* Mr. Stine shared slides viewed and affirmed by SC - which SC then edited on Monday. 
* Strategic direction of OVON re: interoperability:
* Op definition of interoperability - agent->agent trans. or do we believe in smooth handoff (mobile-like) interop.? Per Amazon's VI initiative. Continuum presented on screen. Steering committee came down in the middle - we're in favor of Agent->Agent transfer - But world is not there now. We 
will assert @ OVON.
* Major questions addressing and discussing issues: what is future of voice? will future be diverse or limited? We are in an early phase of voice development - not a mature phase. We are working to build for the present and consumer platform reality while also building for a diverse future but 
must acknowledge leadership of consumer-centric gen. purpose platforms. Adoption path likely through these platforms, and what we build must consider this.
* Are we building for all of voice industry? Are we building to enable young companies? Do we want to build for major corporations? Metaverse as well as platforms? Should we upset apple cart or change the apple cart altogether? Is our total market comprehensive and emerging? Steering committee: yes, open. All and emerging. But adoption path will go through general purpose platforms. 
* Should we work to ensure Open Voice Network protocol and interface standards bear no or ltd resemblances to various existing proprietary implementations, or should the OVON evaluate and consider through adaptation or adoption the use of proprietary platform protocols and interfaces? (Per recommendation by Monica Lam - look first to Amazon). Steering committee said: let's start by eval. work of existing proprietary platforms. Their technologies, protocols, messaging	specifications. What can we learn from them or develop based on what they have, to catalyze adoption. i.e., we start on the right and move to the left. Paving the path toward adoption;. We must be alert to potential copyright issues to make sure we are clear and safe 
legally. Scott Nicholas: we should be cautious.

### Mr. Crabb's Comments and Guidance to team & resultant feedback
* OVON has put fwd strategic position on all of this re: questions steering committee and other bodies have grappled with for at least a year. We need to define what future will be.
* Voice world can go one of two ways: the way of search (where one or two engines dominate) or the WWW which is more freeform - huge diversity of ecosystems. Without standards and protocols in place and interoperability endemic, connectivity would be a beacon/asset. We try do two things:
Say this is what we want to do/where we want to go, with caveat that this is where the world is now.
* Going off on our own @ OVON would be an academic exercise, working with existing platforms more productive, but OVON but remain a leader. Best way to have influence here is to start close, enable people to see the value or generic platforms, then gradually show value of OVON standard and point to value of interop. Hopeful that what we plan to do aligns well with the community.
* Mr. Crabb called for questions and feedback from participants in group.
* Mr. Stine: Mr. Crabb's suggestion of a multipage strategy summary is a great one. He will take responsibility of taking this first document and bringing it on par with slides representative of decisions.
* A comment: Mr. Myers agreed that we are @ inflection point with voice tech that could go either way. Some of the cracks revealing selves in direction of islands controlling most of the market. Really positions OVON in an interesting spot as standards-est'd entity. Potentially moving in the direction of open ecosystem.
* Ms. Coleman thanked Mr. Crabb for sharing perspective. Asked what the measure of success by, e.g. the end of this year. What is metric?
* Mr. Crabb: expressed his uncertainty affirmed the criticality of discussing and exploring this. 
* Mr. Stine agreed: this is pivotal. What are EOY deliverables? Critical to have this. 
* Ms. Coleman: not only key to define where we want to go but how we will get there. (Others broadly agreed).
* Mr. Larson asked: will a summary of these 4 slides be placed on the website, and if so where? World needs to know our position and direction. Mr. Stine affirmed that slides will be worked into revised draft of strategy paper, which was published on Jun. 6; this will be made available on the 
website, as well as in the Google workspace.
* Mr. Pappas & Mr. Crabb feel position resonates well, Mr. Pappas loves idea of amplification; feels website can be used to amplify our statement to public and invite comments
* Mr. Stine: most critical statement for OVON: we build for a diverse future, in lieu of a limited and closed future
* Ms. Coleman: forthcoming webinar about White Paper: will said position be expressed in first webinar and second webinar will go through paper? 
* Mr. Stine: current working version of paper includes a perspective on future diversity. But also anticipates this should be part of webinar. 
* Mr. Larson: this should be used to introduce our interop. work to world. Also requested that Mr. Stine prepare slides everyone can use in all their presentations; a uniformity of msg.
* Ms. Coleman: agrees. These slides can be very powerful and and foment extended discussion (20 min. or more of content, 10+ min. of questions) in a webinar context. (Mr. Stine agreed). 

### Senior Advisors 
* Mr. Crabb - high level on senior advisors, OVON, & funding we have dollars to spend, not necessarily spending on expected development. Yet some of committees lack advisors. First thought: because two OVON Target execs have moved on, and we're feeling that loss, it occurred to him that dedicated paid team resources are preferable to volunteers. Mr. Stine took this to SC and amplified it, so we are poised to hire three additional advisors
* Mr. Stine: originally we looked at one advisor for technical committee, a role he is currently filling. As of early May this money hadn't been 
spent. Three exceptional candidates expressing interest in serving a senior advisor. (At this point, Mr. Stine pulled up a slide with five key 
open opportunities: Technical Committee and Senior Plan Dev; Findability-Discoverability VRS Lead; Interoperability Architecture/Development Mgr.; Community Development Friends/Crowdfunding; and Development of Relationships with Other Standards Bodies & LF Organizations). Top 4 are immediate; fifth is to come in Q4 of this year, in the very near future.
* Mr. Crabb: looks at this as a shift to maturity of OVON. Volunteers grow weary. Volunteer base is valid but we should have these folks focus on what interests them most. We also need dedicated paid resources as a mature organization. Increase momentum and ability to execute in next year or two, and use the dollars we've been granted. Better organization of work so volunteer efforts are more meaningful.
* Mr. Larson: small concern. Many leaders without support staff which we need for full implementation (worker bees). This should be considered. Mr. Crabb pointed out that after we hire these advisors, we will still have $130,000+ for worker bees. We hope to get more proposals along these lines - this would be worker bees.
* Mr. Stine: adding to Mr. Crabb's point: in Community Dev. and Interop. Partner Dev. categories: we have worker bee and volunteer recruitment, done in such a way that instills value in participation. Pointed to Mr. Myers as a prime example. We want to find MVP people like him and support him and others of ilk. Assured that there will be investment in finding people like Mr. Myers.
* Mr. Myers: quick comment. Very passionate about OVON work. But curious about how other groups were lead. We've lucked out because we have Ms. Coleman as senior advisor.  She has driven ship on many things - always keeps things moving and gives us direction. Invaluable. Much to be said about a volunteer run org. from  volunteer perspective happy to see investment in paid leadership for the reason that many of original volunteers have dropped out. Retention will be increased with this new strategy.
* Mr. Crabb: maybe we can recapture some of initial leadership along the lines of Ms. Coleman.
* Mr. Stine: reviewing this decision today (7/15) with the technical committee; he's meeting with three said candidates and then they will meet with Mr. Wuttke, Mr. Crabb and Mr. Saul; candidates should be active by mid-Aug '22.
* Mr. Crabb: expressed enthusiasm although this is a rapid timeline.
								
### Work Group Reviews - Architecture - Mr. Larson
* We spent all energy on producing draft of white paper arch. reqs. Will be published on 7/25. Now editing, and removing inconsistencies, elucidating. Mr. Stine is actively scrubbing through this document. Making good impressive progress. 
* Mr. Stine added that this document in mid-editing is on Google Workspace drive. Document will be ready for friends and family review by 7/25/22. Thanked Mr. Larson for getting us to this point.
* A corresponding webinar has been scheduled for August, and a combination webinar/seminar/workshop is being looked at for September potentially. Outsiders will be brought in to discuss.
* Mr. Larson: rollout - we will first meet with each of the sponsors, have them review the white paper. Explain what it is, answer their queries and explore how we can do future project collaborations with them. Second rollout: friends and family - perhaps in a webinar. Third rollout: announcement to world, perhaps in a  workshop framework. Details TBD.

### Privacy and Security - Ms. Coleman & Mr. Myers
* Mr. Myers: working on diving into commercial privacy. Process of narrowing down, id'ing goals and requirements. Direction and goal became much clearer in last two meetings. What we are outlining - different entities at the center of commercial privacy and what are they looking to gain. Great feedback from Fraunhofer and Respeecher. Small delays but A1 progress in terms of what we're working to achieve.
* Mr. Stine: we will be focused on deliverables for second half of year.
* Ms. Coleman: from a security side, paper will be dist'd on Monday for further review. Speaking with Janice about copy editing. She will be avail to receive paper by mid-late Aug. This will give us time to get it out there for review, have a couple of rounds dist'd further than just internally, ID key friends and family members to receive paper. 
* Mr. Stine: Security & operability published in the same 10-day time period, very exciting. Ms. Coleman agreed - emphasized that scrubbing, copy editing, plagiarism checks being done, up front so that when we get to Janice it will be a quick turnaround. 
								
### Ms. Coleman - Ethical Use Task Force
* Their webinar @ EUTF Wed. 7/27 at 12pm EST. Emily & Valeria & Shilpi from DataEthics4All will be on the panel.
* Goal: to use webinar to broaden audience as much as possible. Announcement is being tweaked in light of some of recent news headlines - broadening to more than just practitioners, building public interest.
* Mr. Stine - VRS. Putting together strategic package to wrap around Maria's developed POC.  
* Looking through value propositions of a dest./voice registry, findability/discoverability. 
* Yesterday as a team, we began working through what is the UX and requirements/dependencies of a destination management and registry. How does it work when we have a post agent, or an initiating agent that then delegates in our envisioned interop. world? What are requirements?
* Defining how consent, authentication, etc. work together-difficult questions. Tied back to POC and prior work.
* A white paper will ultimately be produced w/further recommendations.

### Mr. Crabb - Final Comments
* Thanks to everyone. Glad we are moving into execution phase. Looking forward to seeing progress made accordingly
* Happy we're assigning resources to everything we've indicated we want to do
### Adjournment - without additional comments, Mr. Stine adjourned mtg at 10:58am EST.
							

## Open Voice Technical Committee Meeting Minutes - 6/17/22

### Attendees: J. Stine, O. Coleman, B. Epstein, N. Southern, J. Trammell, N. Myers, C. Wuttke, J. Crabb, D. Rogers

### Mr. Southern began by formally adjourning the meeting at 10:03AM and reading the Linux Foundation antitrust statement. 
* There were no new introductions this morning. 

### (Hire)of a new Senior Advisor for the technical committee - Mr. Stine
* Mr. Stine shared his screen and a description of the role. Noted that this is a part time technical contractor position - ran through the expectations of this hire - objectives, deliverables, etc. And how we would measure the success associated with this position. 
* Mentioned that he will soon begin a recruiting process and bring to the TSC three candidates by the July mtg scheduled for July 18th (?). 
* Called for the finding for support to Mr. Trammell and Mr. Wuttke to facilitate this.

### Interoperability Discussion - Mr. Larson 
* Mr. Southern turned the discussion over to Mr. Larson - who touched on the voice agents Microsoft, Magenta, Speechly, Genie. two new additions: Cortana and Google. However we have decided to postpone investmennt in the development of two Axxessio Demos until protocols have been established.
* Mr. Stine: dependency for moving fwd is the publication of related specifications. Also noted that MS work will be directed to Azure team under guidance of Dalloul and Wang.... who have been providing white label services to develop conversational AI. Mr. Dalloul has said MS would be interested in test/dev op of additional demos once our protocols have been developed. This will further accelerate/advance our interoperability efforts.
* Mr. Stine outlined the order of anticipated work. Mr. Stine also touched on recent developments with Google - in terms of the recent changes that have taken place there re: absorption into the Android team. We will be requesting to work with Android team.
* Mr. Trammell: this sounds like a technical master plan. Should we document it as such? Mr. Stine agreed with this.

### VRS Updates - Mr. Stine
* Mr. Stine discussed possible integration of architectural and VRS work group which we have decided not to do. 
* Mr. Stine laid out his rationale for not doing this work - put a road map on the screen for the direction in which we want to move. 
* Engineering approach pursued great things were learned but we didn't fully define why what or how. Recommendation is that we take next 4 mtgs of VRS group and assemble a working document that we could present to this body and the steering committee.
* Mr. Wuttke: still a fan of merging groups in the future but understands that in the short term it makes sense to get the knowledge from the VRS. Mr. Stine: question is not whether we merge groups but when do we merge, and do we have work completed before this is considered.
* Mr. Crabb: asked why architecture group can't do this work. Mr. Stine: we have a core group of eight who can pursue it in the short term. Mr. Larson: other issue - AWG is a bit behind in its specifications. Wants to avoid distracting the progress and movement of VRS group. Mr. Crabb: as long as there is progress I'm fine with it.
* Mr. Stine: presented his 'modest proposal' regarding our short term plans. One question: structure, execution and governance. There is also per Mr. Hochstatter concern that we haven't addressed user experience and the questions surrounding this as well.
* Mr. Stine asked for Mr. Wuttke's thoughts: Mr. Wuttke from a UX point of view 

* Discussion then turned do the AWG with the corresponding timeline laid out on the screen. 

### Clarification of future activities 
* White paper has been delayed until June
* Mr. Stine thanked Joel & steering committee's leadership. Thoughts will be incorporated into the white paper. 

### Privacy & Security WG Updates - Mr. Myers
* Moving into an identifying requirements phase.  Much of the work they have done so far on the privacy side is focused largely on users. He feels it would be valuable to set up a meeting or discussion

### Meeting Adjourned By Mr. Stine at 11:01am

# Notes of the Technical Committee Meeting - May 20, 2022

### Attending and Participating: J. Trammell (Target), O. Coleman (Ovon), K. Dank (Target), J. Larson (SpeechTEK), N. Southern (Linux Foundation), N. Caidin (Linux Foundation), J. Crabb (Target), D. Rogers (Wegmans), N. Myers (Red Fox AI), B. Epstein (Aebis Inc.). Not In Attendance: C. Wuttke (Conversational Solutions), J. Stine (OVON)

### Call to Order
* Mr. Southern called the meeting to order at 10:04am Eastern Time and recorded the minutes. A quorum was established for the conduct of business, and the meeting, having been duly convened, was ready to proceed with business. A quorum was present.

### Antitrust Policy Notice: Mr. Southern reviewed and reiterated the Linux Foundation Antitrust Policy. 


### Investment Exploration - Strategizing
* Mr. Southern pointed out per Mr. Stine that we have roughly $170,000 tasked by our sponsors for development and growth, which prompts a question of how we can effectively invest this. 
* Different ideas presented but foremost to discuss is the possible extension of the Axxessio contract which expires 5/31/22 after going into effect on 1/17/22. 
* Three deliverables enumerated. Total of contract - €20,000, but Mr. Southern denoted that per discussions with Mr. Stine, if contract is renewed it should probably be revised with a more acute financial breakdown per individual phases of completion. 
* At this point, Mr. Southern handed the discussion off to Mr. Larson.
* Mr. Larson: per our current contract, we've been able to demonstrate how Mycroft can interact with three other voice agents, invoking Magenta (Deutsch Telekom); Genie (Stanford U.); and Speechly, which is not really a voice agent per se but a voice agent-like entity - a web page that has been voice-enabled so that you can speak directly to the web page. Now possible to switch back and forth between these agents which is an asset. 
* Mr. Larson indicated that demo will be available in around a week. Mr. Larson pointed out that with the Technical Committee's formal approval, we would like to extend this contract at ballpark of about €20,000.
* This will add Microsoft Cortana and Google Home to our stable of voice agents that are interoperatively enabled. Cortana, is not a commercial product now, but is sold by Microsoft as a white box to other enterprises, so that they can develop their own voice agents. Pointed out the benefit of extending Cortana to make it interoperatively voice enabled, so new companies will have this capability when they come aboard. Also an ideal point of entry for OVON working with Microsoft. 
* Mr. Larson pointed out that Google Home is one of two largest and most widespread voice agents now in use globally. Making Google Home interoperable will dramatically expand the scope of what we can do. Mr. Larson anticipates a couple of related issues, because Google Home like Alexa has a 'walled garden.' It will be a challenge to surmount walls and make systems interact with others.
* Mr. Larson restated the cost and outlined other possibilities attached to this. One is the ability to share data between voice agents. For example: logging onto Magenta and providing name and address to it, and then switch to Genie, reentry of personal data will not be necessary because data has been shared. 
* Another possible extension: an end-to-end connection between users and voice agents. During sign-on, user ID'd by speaker authentication. Concurrent identification of voice agent itself to ensure its authenticity. Also: encryption of client-server messages. For now: we want to focus on Cortana and Google Home.
* Mr. Larson formally asked for a technical committee approval of this extension for two months. 
* Mr. Southern turned this over to a vote, but Mr. Trammell called for questions or concerns to be raised first. Mr. Rogers asked what plan we have in place to show how Google home will be tested under the extension of this contract. What are we looking to get as a deliverable, and how confident is the team that it will be successful in two months?
* Mr. Larson affirmed that there is a risk involving Google Home and walled garden. 
* Mr. Rogers restated his concern: do we have the time allocated and the resources to execute this time properly and do the testing. In other words, are OVON resources aligned to take advantage of this extension? Mr. Larson said yes. However he also wants to work with sponsors to see what voice options they have available and begin interacting and integrating those. So that also is on our schedule.
* Mr. Rogers said this helps. From Wegman's perspective, they do not have a voice agent at this time to help do this testing.
* Mr. Larson called on Mr. Trammell who indicated that he's in favor based on positive track record with Axxessio. Mr. Epstein posed a couple of questions: one about competing priorities re: how and where we can spend this money. Second question concerns what Mr. Rogers was alluding to re: priorities. We are embarking on parallel paths: standards development and systems design Asked if we have overall leadership and implementation resources broad enough to lead these to successful completion?
* Mr. Larson: we want to have demonstration team implement our ideas to validate that our APIs do indeed work. This is main goal of implementation effort. Secondary goal: to be sure that the work provides videos for marketing purposes. These are primary purposes of demo team. Demo team will no create their own voice agent - this is out of scope. Merely validate that we are on the right path.
* Mr. Epstein indicated that this answered his second question. What of the first? Mr. Southern briefly touched on the remaining funds from the $170000 and some possibilities discussed such as the hiring of an information architect. 
* Mr. Rogers: no competing need for the €20,000 but there are other ways to spend $. But absolutely enough in the budget for a R&D task such as this. Key question: do we want to spend it, and the time constraints. Will there be a delay? He is concerned about this.
* Mr. Southern asked Mr. Larson to comment on the success of the Axxessio contract so far. Mr. Larson affirmed that it has been quite successful. Axxessio has proven interoperability between voice agents with a persuasive demo. Should prove very important and instrumental in the long term, most important re: ability to switch back and forth. Axxessio people have done an excellent job with this demo, have given us the code, we're testing it out etc. Completion has provided validation so far.
* Mr. Crabb: pointed out, in response to Mr. Larson's earlier comment, that Target doesn't have its own voice agent. Agreed with Mr. Rogers re: adequate funding present for a renewal of this contract for research & development allotment. Clarified: are we only getting a demo or also an interoperability standard? Mr. Larson: goal of AWG is to develop standards - protocols, message formats. Purpose of demonstration group is to demonstrate those protocols & message formats A. work and B. work correctly. Mr. Crabb: clarification. Are we saying that we're trying to prove the standards we already have are working correctly, or working on discovering new standards? Mr. Larson: a bit of both. Formal standards group has not yet reached the point where they are articulating precisely what the standards are. We know what the messages are in general but we've not reached a great level of detail yet. Currently, the demo group is leading ahead of the specifications group. That will likely be reversed in next couple of months.
* Mr. Crabb: does contract specify that working groups will also examine standards? He would love to have more involvement from other groups than to pull the standards out as axxessio is doing the work. Mr. Larson affirmed that Axxessio participates regularly in our standards identification meetings based on the work that has been done, and that implementation follows from this. 
* Mr. Crabb: feels that re: spending the money, getting the connections in place is a great thing to do. But also would add in to contract: some expectation that this is leaning toward definition of standards we are trying to create. Mr. Larson: it would be formulated as Axxessio's validation of the standards we are working to specify. Mr. Crabb affirmed that this works for him.
* Mr. Epstein: believes we should absolutely continue this. Point we may need to discuss offline before next Technical Committee Meeting: to whom does Axxessio's IP that they are currently producing belong? Is it theirs, ours, etc.? The expertise that they are gaining in permitting heterogenous voice agents to correspond will have a significant value in the future of interoperable workplace. An opportunity will emerge from this. Mr. Larson responded: Axxessio people are authoring the contract. Recipe for developing new interoperable voice agents, so they can leverage what they have learned. Second, we own the code they've produced per the contract and therefore the IP and the recipe to build interactive objects they are producing.
* Mr. Trammell added: there is a developer COO requirement for the code we obtain from Axxessio. It is being licensed per Apache, open source, and open voice standard. Ms. Coleman addressed IP question and related it to website contract with developer being discussed this week. That contract has been amended to explicitly claim IP ownership by OVON. So we may need to explicitly cover this in Axxessio.
* Mr. Southern called for a vote. Unanimous consent from committee. Decision to move forward. 
* Mr. Larson prompted additional discussion about hiring a data architect consultant. We are backlogged with David Atwater - works w/us in spare time but lacks the bandwidth to do everything we would like him to do. Question: should we use additional funds from $170,000 to hire someone knowledgeable in both architecture and speech. Opened it up to opinions and suggestions. Ms. Coleman affirmed that it would be a valuable idea - useful to do it in context of questions raised by Mr. Crabb and Mr. Rogers re: Are we advancing toward standards? SMEs would be worthwhile, but should we vote on this now, or should interoperability working group discuss and create a formal proposal for us?
* Mr. Southern raised question: what is the cost? Mr. Crabb affirmed that we need to clarify the purpose of hiring these gentlemen. If it's a qustion of getting v. 1 of Interoperability Standards written, or working with the Axxessio team to better understand how standards emerge from their work: a valuable use of these monies. But hiring them with unclear objectives, he would be opposed. Mr. Larson agrees entirely. The goal Mr. Larson pointed out would be to accelerate development of specifications to speed up our work. Mr. Larson affirmed that it would be primarily driven by advice and expertise. Mr. Crabb expressed mixed feelings about this. Concerned that advice alone may slow us down or could accelerate given the advanced knowledge of SME. Can (or should) be a minimal contract.
* Mr. Southern proposed moving forward in interest of time and others agreed. 
* Mr. Epstein wants to talk to Mr. Larson off-meeting - has a different view of our needs for this person. Wants to work out a proposal and submit this for approval.

### VRS Updates
* Mr. Larson affirmed that VRS work Phase 1 is completed, that we've demonstrated how an explicit request is converted to a voice agent, that Mr. Trammell may just create forthcoming video demo, or otherwise we may just rely on Axxessio for this if theirs suffices. Maria Dombrowski has left VRS team, so that WG group needs a new moderator. Action items: we need a new moderator for VRS team. This needs to be sent to John Trammell. They are recommending that group be paused for a few weeks, follow steps listed on the right side. May include: rebranding VRS as "Visibility," revisiting the goal of what they are trying to achieve, defining the problem(s) 3 - a. discoverability, b. prioritization and c. findability. Also identifying what's available today, determining what OVON and other technical players should do, provide a sense of global landscape, and ultimately providing recommendations to techical committee.

* Comments: Joel Crabb - what about suggestion that VRS and interoperability groups merge? Mr. Larson said he would prefer that this doesn't happen, because architectural group has its hands full. Wants to keep the groups separated for the time being, until VRS determines next steps. We can revisit a merge at that time. Mr. Trammell: a bit puzzled, thought a merger was a given at this point. If we are to pursue further development with VRS, it makes sense to keep it separate, but he thought VRS project had wrapped. If we are to continue to develop it with a different set of ideas, he's fine keeping it open.

* Mr. Larson pointed out that VRS group has several members of architectural group on it, so they are not exactly separate committees, and there is a lot of overlap between the two. He wants the time spent by VRS to focus on what next steps should be, and not distract the architecture group from its objectives. 

* Mr. Crabb: suggested that Mr. Larson and Mr. Wuttke touch base, because Mr. Wuttke is the one who suggested a merger. Mr. Larson agreed. Stated he's not opposed to a merger, just concerned about VRS becoming more swamped. Mr. Crabb pointed out that discoverability also came to the steering committee and for VRS, and we are not clear that this is something OVON should be doing. Mr. Larson agreed. He wants VRS to decide what needs to be done - next key steps. We may need to dispense with discoverability. Needs to be formally considered and decided, what we can do to facilitate this, we may eliminate discoverability.

* Mr. Myers: inquired why we are rebranding VRS as "visibility." Mr. Southern suggested that Ms. Coleman comment on this. Ms. Coleman: we are rebranding to be more than about just fulfilling an explicit request, expanding to visibility allows research or requirements on findability and discoverability. This was a proposal from John Trammell and the research he did. Ms. Coleman suggested that Mr. Trammell comment on the technical reasons behind it.

* Mr. Larson expressed an ambivalence about label of group and indicated that what he wants is for them to have a broader view of what is needed beyond just explicit requests. How do we handle implicit requests that may include discoverability, and that will help us decide if we want to get involved with discoverability? 

* Mr. Myers: with VRS in mind, have there been any explicit face to face or virtual discussions with entities that currently operate voice assistants, as to how they view data sharing re: a potential VRS interoperability? 

* Mr. Larson: No but such discussions need to take place. Some will happen in VRS group, or Mr. Myers's group or the Architecture group.

* Mr. Epstein: before asking the VRS to reorganize and plan next steps, if we hire an outside expert, they must be hired before VRS group starts this. We need equivalent for VRS of what David Atwater did a year ago for the Interoperability Work Group, which was an initial white paper outlining fundamental principles and direction to be followed.

Ms. Coleman: called for informal vote on pausing VRS - unanimous yes consent.

### Interoperability Work to Date and Roadmap - Mr. Trammell
* Mr. Trammell: on 5/11 we had a discussion with two reps from Microsoft. Discussion: How do we want to go forward? What metaphor do we want to pursue? Does the Stanford OVAL (Open Virtual Assistant Lab) model make the most sense? Or are we looking more for interoperability that we've been discussing up to our awareness of Genie, which is more separate independent pieces that we define the protocols for discussing for sharing information? w/o qualification, MS said the independent pieces are the way they want to pursue, with an understanding and respect for the market incentives of all the players that are in the voice space. This is a critical part of a solution that can be implemented.

* Mr. Larson: it became clear that we need meetings with each of our customers, and we are planning these accordingly in the coming weeks to get opinions on which of these models we should use. Mr. Trammell: we also need to understand and clarify our problems before presenting solutions. Another point re: Stanford. We need to influence them as much as they have influenced us. This is a two-way street with good ideas on all sides. Cross-pollination is critical. And finally: they noted that despite the growing #s of smart speakers in people's homes, enterprise voice is more interesting and more likely to dominate in the future. We need to keep an eye on this area.

### Process For Answering Stanford vs. OVON Question
* Mr. Larson led discussion on how we get alignment in terms of fundamental understanding of Stanford Model. We chatted with Microsoft and now will be having discussions with Target, Wegmans, Schwarz Gruppe and Deutsche Telekom. What is the direction we should take? Jon Stine is preparing 1-2 page document. Next meeting on June 6th - Mr. Southern emphasized a critical concern about getting alignment on the Stanford issue question - as Mr. Larson affirmed earliest this week.

* Mr. Crabb affirmed that we can easily set up a meeting w/Target to discuss accordingly. Target had asked for Jon's briefing document, that will help us as we go through it. The discussion as well.

### Action Items - Mr. Southern outlined action items.
* Approved Axxessio extension, now the contract needs to be reformulated and moved forward w/a sow for renewal. 
* In revising, Axxessio contract needs to spell out IP ownership.
*  We are pausing the VRS group for the time being and rebranding as 'visibility.' They will come back with a plan at next Technical Committee Meeting. Pause and regroup and discuss rebranding. This will be presented for approval to steering committee. 
* In tandem with this, we need a new moderator for VRS team.
* Disagreement on combining VRS and Interoperability. This needs to be sorted out.
* Mr. Epstein and Mr. Larson will meet to discuss some of his thoughts about hiring an information architecture consultant, and draft a proposal accordingly. 

### With no further topics discussed, Mr. Southern adjourned the meeting of the Governing Board at 11:08am Eastern Time.


Meeting Adjourned 



# 2022-04-15 Notes of the Technical Committee Meeting 

Attendees:  J. Larson, K. Dank, J. Stine, M. Brinas-Dobrowski, N.Myers, J.Crabb, D. Rogers, O. Coleman, J. Trammell, N. Caidin, B.Epstein, S. Palma, H. Pappas 
	
The meeting began at 9:01 am CT

### Antitrust statement and notice of recording  -- J. Stine

### Introduction of New Participants  
* Guests- Sebastian Palma  & Harry Pappas

### Review of Notes from 2022.03.18 meeting –J. Trammell 
* Notes accepted 

### Review of the agenda, purpose of and expectations for the meeting  -- J. Trammell 

### OVON Vision:  The world to which we build – J. Stine 
* Are we building toward the Michelangelo moment?  
  * General purpose proprietary voice platforms/agents & Enterprise chatbots and voice assistants, now inside the firewall
* The world to which we build a worldwide voice web 
  * Growth from today to billions of WW digital voice assistant availability and trillions of WW installed IOT end points, WW AI’s, metaverse
* Overview of a potentially feasible use case for an ecosystem of cooperating voice agents 
  * Noted that this use case could also include discoverability

### OVON Roadmap Q2 and Forward
* Review and reminder of 2022.03.18 Work Group integration slide (same as shared in last month’s meeting)
* Review of Work Group Roadmaps 

 * Architecture- J. Larson & B. Epstein 
   * MOAD (mother of all demos) demo – June 
   * Reference architecture document – June draft 1
   * Basic integration messages and properties spec – July draft 1
   * Principles and requirements for privacy and sharing data – June draft 1 
   * Privacy and data sharing spec – August draft 1
   * Post MOAD demos- several items planned for Q3 and Q4
   * Team needs additional resources that have done similar work before 
   * [Link to slides]( https://docs.google.com/spreadsheets/d/1kL_mOXYp5HNWuBvI-1aSLwFHHTLMrQHi/edit#gid=1620385906)

 * Privacy and Security – O. Larson & N. Myers
   * 2022 Q2
     * Privacy Guidelines v2.0
     * Generic voice-specific privacy policy
     * Voice-specific privacy checklist 
   * 2022 Q3 
     * Commercial privacy guidelines v.10
     * Research privacy factors impacting voice adoption 
     * Privacy POC aligned with interoperability standards
   * 2022 Q4
     * Voice-specific privacy maturity model
     * Privacy standards recommendations 
     * Privacy guidelines v3.0

* VRS – M. Brinas-Dobrowski 
  * Magenta and OVON POC completed.  Next steps:  
    * Discuss if OVON needs to play in a search engine model 
    * VRS integration with open-source conversation platform 
    * VRS needs to add more security context when passing to another agent 
  * Collaboration with VRS & Architecture work groups needed 
  
 * ACTION:  Documentation of 1H-Q3 deliverables—Github

### Adjournment 
* Meeting adjourned at 10:00am CT





## 2022-03-18 Notes of the Technical Committee Meeting 

Attendees:  J. Larson, K. Dank, J. Stine, M. Brinas-Dobrowski, N.Myers, J.Crabb, D. Rogers, O. Coleman, J. Trammell, N. Caidin, B.Epstein 
	
The meeting began at 9:01 am CT

### Antitrust statement and notice of recording  -- J. Stine

### Introduction of New Participants  
* No new participants 

### Review of Notes from 2022.02.18 meeting –J. Trammell
* Notes accepted 

### Review of the agenda, purpose of and expectations for the meeting  -- J. Trammell 

### Open Questions, issues from 2022.02.18 meeting:  Vocabulary; proposal to move forward
* Seeking adoption of:  
  * Conversational Capability – Provides dialog functions that inform an agent
  * Conversational Sub-Agent- Can be only invoked through another agent  
  * Conversational Agent- Is perceived by users to be a single conversational actor.  It can operate on behalf of the user 
  * Conversational Assistant – Is perceived by users to be a single conversational actor 
  * Conversational Platform  - The combination of components that enables the operation and management of one or more conversational agents 
  * Terms were accepted provisionally pending examples being brought forward (for clarity and differentiation) 
* Findability vs Discoverability 
  * The Architecture Workgroup will review and bring back recommendations.  M. Brinas-Dobrowski may consult  

### OVON Development Expectations –J. Trammell 
* Primary sources of information 
* Collaboration
* Call to Action for Workgroups: 
  * Find another group or tech in a similar space 
  * Become familiar with it
  * At next WG meeting, discuss for 5 minutes 

### OVON Vision:  Roadmap Development – Purpose, value; tie-in to Github Master Plan – J. Stine 
* Jon reviewed a functional diagram of how our work might integrate, amplify and accelerate noting milestones from each of the workgroups
* Discussion 
  * We are making progress towards protocols and standards 
  * Diagram should be extended to include white papers and other artifacts 
  * Should diagrams like this be integrated with the Technical Master Plan?  Some don’t feel so 
  * Need 2 more documents -1 that says WHAT and another that tells HOW
* Next Steps:  J. Larson and B. Epstein will meet on next steps

### Work Group Reviews 
#### Architecture- Interoperability – J. Larson, B. Epstein 
* Reviewed Deliverables  
  * Demonstration of agent-to-agent-to-assistant sharing of text, voice on track for end of March 
  * Publication of interoperability reference architecture on track for end of March 
  * Publication of data modes: voice-text semantic at risk for end of March
  * Publication of integration messages, properties at risk for end of March
  * Stanford OVAL-OVON collaboration agreement at risk for end of March
* Critical strategic decisions
  * need a programmer to manage code and perform demos 
* Use of existing research and/or standards; requests for connections, meetings
  * Have made a connection on data sharing and very familiar with W3C standards
* Impediments to progress
  * Confusion between VRS and the Architecture Workgroups and how Stanford architecture will fit in 
  * Limited by David Attwater (or the like) time constraints 
* Cross work group coordination; what, when, how 
  * Working with VRS and Stanford – J. Larson and M. Brinas-Dobrowski will share information on discussions 

#### Privacy & Security  -- N. Myers, O. Coleman 
* Reviewed Deliverables
  * Publication of Privacy Guidelines v2.0 on track for end of March 
  * Publication of Security Guidelines v1.0 on track for end of March 
  * Publication of Summary of Global Legislative Actions will not be completed by end of March
  * Demonstration of Privacy Policy Voice Navigator Project on track for end of June 
* Critical strategic decisions
  * Need to determine how to move from the what to actionable work 
* Use of existing research and/or standards; requests for connections, meetings
* Impediments to progress
* Cross work group coordination; what, when, how 

#### VRS  -- M. Brinas-Dobrowski 
* Reviewed Deliverables
  * VRS POC on track
* Critical strategic decisions
* Use of existing research and/or standards; requests for connections, meetings
* Impediments to progress
  * None at this point 
* Cross work group coordination; what, when, how 
  * Overlap and connections with the Architecture Workgroup 

### Adjournment 

Meeting adjourned at 9:59 am CT



## Feb. 18, 2022 Notes of the Technical Committee meeting

Attendees: J. Larson, K. Dank, J. Stine, M. Brinas-Dobrowski, N. Myers, D. Rogers, O. Coleman, C. Wuttke, B. Epstein, J. Trammell

### Ways of Working – J. Trammell

* Reminder of Meeting Protocols
* OVON GitHub Reorganization; Table of Contents
* Community Specifications License:  Operational Implications for Architecture, VRS Work Groups
  * Add to the Ways of Working Document
 
### Vocabulary Review – J. Stine, C. Wuttke, J. Trammell

* Conversational Capability – Provides dialog functions that inform an agent
* Conversational Sub-Agent – Can only be invoked through another agent
* Conversational Agent – Is perceived by users to be a single conversation actor.  It can operate on behalf of the user
* Conversational Assistant – Is perceived by users to be a single conversational actor
* Conversational Platform – The combination of components that enables the operation and management of one or more conversational agents
  *Aligned to include a few examples of each with the definitions and some additional dialog needed via the Architectural Workgroup
 
### 2022.02.17 Steering Committee Meeting Review – Observations, Takeaways, Implications – C. Wuttke

* Jon shared market development for voice solutions
  *conversational AI becoming more popular
  * global market for conversational AI will increase ~29% through 2026
* smart speaker sales in the US market are dropping
* Definition of Mission and Strategy for 2022
  * team worked to define a vision for 2022 with an ideation phase/process
  * additional discussions will occur to refine the mission
  * update at next technical committee meeting
 
### Work Group Updates:  Status vs. Q1 and 1H Deliverables  -- C.Wuttke

* Privacy & Security  -- N. Myers, O. Coleman
  * Privacy
    * Completed the draft of the Privacy Principles and Capabilities Unique to Voice and has been sent to Janice Mandel for copyediting
    * Will now start on the V 1.0 Summary of Legislative Actions followed by the Privacy Policy Self-evaluation Template
  * Security
    * Draft Security Guidelines progress:  Executing timeline from contractor and will have document for review by Feb 25.   Draft has been posted to privacy/security slack channel
    * Will then start on identifying security use case to demonstrate security architecture
* Architecture- Interoperability – J. Larson
* Work continues on developing specifications and POC implementation for interoperability
  * Reprioritized enhancements  for interoperable conversational interfaces
  * Working on variety of Q1 deliverables towards the specs and POCs
  * Planning an workshop for May 15, 2022
  * Suggested leveraging contributions from David Attwater in this work
* VRS  -- M. Brinas-Dobrowski
  * Working on the VRS- Magenta POC and are working with Magenta to align on outcomes and scope

# 2021-12-17 Notes of the Technical Committee Meeting

Attendees:  J. Larson, K. Dank, J. Stine, O. Coleman,  J. Trammell, N. Myers, J. Crabb,  N. Caidin, S. Nicholas. P.Gopal

The meeting began at 9:01 am CT

### Antitrust statement and notice of recording  -- J. Stine 
* [link to antitrust policy]( https://www.linuxfoundation.org/antitrust-policy/)
* Please review the linked policy 
* S. Nicholas was present and suggested that if you have questions, engage your company counsel and connect with Scott for a discussion as needed 

### Review of the agenda, purpose of and expectations for the meeting  -- J. Trammell 

### Work group contractor hiring status 
* Privacy & Security 
  * Has hired Ed Sewell 
* Architecture 
  * Now in renegotiation with 7 January as completion goal 
* VRS 
  * Working through scheduling interviews with candidates and goal to get them arranged for the near term 

### Ways of working: 
* When Github, when Google and why 
  * Collaborative document development may be in either Google workspace for Github docs repo.  Decision managed by work group moderator 
  * Public facing final versions of documentation MUST be published in Github in pdf form.  For broader public distribution, it is recommended that the pdf also be posted on opevoicenetwork.org (http://openvoicenetwork.org)
    * Aligned that a workgroup should be formed to define detailed standards – John Trammell to lead 
  * Work group code and proposed protocols (from 0.1 to final) MUST be published and managed in Github
* Deliverables and milestone management 
  * Work groups, communities and task forces may manage tasks in Trello or Github or other tool preferred by work group.  Decision to be managed by work group moderator
  * Each work group will establish in Github deliverables and milestones that are measured quarterly.  These will reside in the Technical Committee Project 
  * Agreed that some training may be required to achieve goaled standards 
* Cleaning up of the OVON Github repository 
  * Github Repos currently need a lot of cleanup work 
  * J.Stine, K.Dank, and N.Caidin will start the process but each work group will need to own cleanup of their repos at some point

### The Master Plan: 
* LF expectations for transparency, visibility
  * LF requires final public facing documents and all code/protocols in Github 
* A master plan or a master plan with multiple sub-plans? 
  * J. Trammell reviewed the Master Plan
    * Observations:   Good document, good calls to action, some gaps 
    * Actions:   J. Trammell will meet with each work group and create recommendations for go forward approach 

### Plan 2022:   Topic postponed to next meeting 
* Observations from Steering Committee members 
* The “headline” for the Technical Committee at YE 2022
* Top-down proposed 2022 objectives 
* Top-down proposed 2022 milestones 

Meeting adjourned at 9:59 am ct 



# 2021-11-19 Notes of the Technical Committee Meeting

Attendees:  J. Larson, K. Dank, J. Stine, O. Coleman,  J. Trammell, N. Myers, J. Crabb,  M. Brinas-Dobrowski, N. Caidin, B. Epstein

The meeting began at 9:01 am CT

### Antitrust statement and notice of recording  -- J. Stine 
* [link to antitrust policy]( https://www.linuxfoundation.org/antitrust-policy/)
* Discussed need to discuss this further in a future meeting 

### Review of the agenda, purpose of and expectations for the meeting  -- J. Stine 

### Quick Updates –J. Stine 
* Potential collaboration partners:  Stanford
  * mutual desire to collaborate in the areas of technologies, 
  * would require financial contribution from OVON, will be brought to OVON Steering in December 
* Meeting management/responsibilities 
  * Zoom -10 licenses 
  * Recommendation:   In 2022, move all of the meeting management from Outlook to Google calendar to be the source of truth.   Zoom meetings setup then through central Google OVON calendar
  * Discussion: 
    * Risk of others ‘crashing’ our meetings
    * TLF is rolling out a new set of meeting management tools.  N. Caidin will share back 

### Technical Committee Workgroup Updates 
* Privacy & Security 
  * Have selected an candidate and received their SOW and are in the process of negotiating.   Expect completion next week with goal to start work December 1
  * Privacy:  Publish Privacy Guidelines v2.0 by end of year 
  * Security:  Publish Security Guidelines v2.0 by February 2022

* Architecture 
  * Have selected an candidate and received their SOW and are in the process of negotiating with goal to start work December 1
  * Tiger team working on MOAD demo planned before year end 

* VRS
  * Reviewed candidates and short listed.  Interviewing is next step and goal to start work mid-December 
  * VRS year end deliverables are:  POC w/Deutsche Telekom, assessment of adding another conversation platform (ex. Magenta 2.0)
  * Agreed that VRS and Architecture workgroups should discuss connection points  

### 2021 in Review/2022 in Focus 
* 2021 in Review
  * Documentation management is an area of opportunity  -Structure and what should go in Github vs Googledocs 
  * Privacy & Security workgroup members have reduced which has impacted deliverables –how can we better retain workgroup members 
  * Decision making –many choices available and hard to determine which is best.  Decisions are often revisited (even without new information) 
* 2022 in Focus 
  * Architecture Workshop in March 
* We didn’t have a lot of time to review the above and suggested that this reflection be done periodically throughout the year 

Meeting adjourned at 10:00 am ct 


# 2021-10-15 Notes of the Technical Committee Meeting

In attendance:  C. Wuttke, Chair; J. Trammell, Vice-Chair; N. Caidin, S. Prayaga, M. Brinas-Dobrowski, O. Coleman, N. Myers, J. Larson, J. Stine

The meeting was called to order at 9:02 CDT (US).

### Antitrust statement and notice of recording -- J. Stine

### Review of the agenda, purpose of and expectations for the meeting -- C. Wuttke

### Introductions.  

Christian Wuttke of Schwarz Gruppe introduced, instituted as Technical Committee Chair.  John Trammell of Target Corporation introduced, instituted as Technical Committee Vice-Chair.  Neal Caidin of the Linux Foundation introduced as the new Open Voice Network Program Manager.  Introductions of Work Group moderators:  Shyamala Prayaga and Jim Larson, Architecture Work Group; Nick Myers, Privacy and Security Work Group, with Senior Advisor Oita Coleman; Maria Brinas-Dobrowski, VRS Work Group.

### OVON Updates -- J. Stine

J. Stine provided the following updates:
- Hiring status:  as of Thursday, 14 October, CV's have been received for all three strategic Work Group positions: 2 for the Security position, 16 for the Interoperability programmer position, and 2 for the VRS Solution Architect position.
- Hiring Process and milestones:  CV's to reviewed no later than 18 October 2021, and finalists selected; interviews, statements of work to be requested no later than 25 October.  Regarding pricing: we will ask for Statements of Work from final candidates.  In some cases, the expertise we desire may be more expensive than the monies budgeted.  Our response will be determined by the expertise of the applicant; however, we may choose to limit deliverables (or phase the work into 2022) to stay within budget.  Per a question from O. Coleman: a) we may engage either with individuals or with the entities with which a candidate is affiliated or employed; b) we will use for agreement the standard Linux Foundation consultant agreement.  Copies of the latter can be obtained from N. Caidin or J. Stine.
- Community Specifications licenses now in place for OVON Interoperability and VRS Work, per J. Stine.  Four actions required:
	* S. Nicholas of the LF to review, approve establishment of Community Specifications licenses, as now in GitHub
	* N. Caidin, J. Stine to determine and commmunicate tequired Work Group process changes to Work Group moderators 
	* Work Group moderators to announce Community Specifications license and required processes to Work Group participants
	* 3rd Party Contractors to work within Community Specifications license
- Collaboration relationships, specifically with W3C Voice Interaction Community and Stanford University OVAL:  discussions ongoing.  OVON submitted statements of support for an OVAL grant proposal to the Sloan Foundation.
- Logo change:  per advice from LF counsel, the Open Voice Network should change its logo (the amplitude graphic was found to be at issue.)  An interim logo is now in use; a LF graphic designer is now preparing new logo options for Steering Committee consideration.

### Work Group Reports

- C. Wuttke reviewed, emphasized the Adopt-Adapt-Build priority model that is to guide all Technical Committee work.
- All Work Group milestones now up to date in OVON GitHub repository.
- Architecture Work Group:  J. Larson reported on status of work, the "six enhancement" strategic direction. Identified year-end 2021 objective of a working prototype.
- Privacy and Security Work Group:  N. Myers and O. Coleman spoke to month-by-month expectations for the 2.0 Privacy Guidelines.  By EOM October: a topical outline.  By EOM November: a first draft.  By EOM December, a reviewed, revised, and ready-for-public distribution second draft.
	* O. Coleman presented content prepared for the 20 October Steering Committee Meeting; a strategic review of the work to date, and anticipated/potential next steps.  Discussion, recommendations.
- Voice Registry Work Group:  M. Brinas-Dobrowski reported ongoing progress against the three 2021 deliverables, noting the completion of initial POC's.  

C. Wuttke adjourned the meeting at 9:58 a.m. CDT. 



# 2021-09-17 Notes of the Technical Committee Meeting

Attendees:  J. Larson, K. Dank, J. Stine, O. Coleman,  J. Trammell, N. Myers, J. Crabb, P. Gogal, M. Brinas-Dobrowski, S. Nichols, A. Paik

The meeting began at 9:01 am CT

### Antitrust statement and notice of recording  -- J. Stine 

### Review of the agenda, purpose of and expectations for the meeting  -- J. Stine 

### Community Specifications License – S. Nicholas, TLF
* Specifications at the Linux Foundation
  * We have been working under the Charter of the Open Voice Network Vocabulary and Definition Project, which was opened under a CC4 license
* Community Specification License 
  * Incorporates the terms and processes required for specification development 
  * Designed to enable collaboration at the speed of open source
  * Includes copyright license and patent license 
  * Includes source code license 
* [link to community specification license]( https://github.com/CommunitySpecification/1.0)

### Ways of working:  New Technical Committee Chair; process, personnel –J. Stine
* New Technical Committee Chair needed
* Rotating Technical Committee Chair across Platinum-Gold sponsors 
  * Chair as a 1 year term 
  * A vice chair is identified and serves at the same time.  Vice chair will rotate into the chair in the following year 
  * Each January, identification of the next vice chair 

### OVON R&D investment: as proposed to the Steering Committee – J. Stine
* 6 Proposed R&D investments to date were submitted to and approved by the Steering Committee
* Jon is meeting with TLF HR to begin the process of sourcing candidates from TLF

### OVON Opportunities for collaboration:  adopt, adapt, partner  --
* Exploring collaboration with variety of organizations: 
  * W3C, Stanford University, Oasis Open Projects - RECITE, Intel Open-source virtual assistant, NVIDIA RIVA NLP 
* Accelerating our work :  Strategic Guidance
  * Adopt – First Choice
  * Adapt – Second Choice
  * Build – Third Choice 
* Discussion: 
  * need to ensure that any adapt or adopt meets the base goals & priorities of the OVON 
  * consider adding a 4th option of collaboration –or this this a horizontal layer across the 3 of adopt, adapt, build 
  * does our problem statement need revision?  Jon will add some clarity 

### Technical Committee Workgroup Updates 
* Privacy 
  * Privacy Guidelines 1.0 feedback sessions held and a public open forum held 
  * Privacy 2.0 document draft plan created and WIP  
  * Privacy v2.0 document completed by end of October is current goal (may extend a bit) 
  
* Security 
  * Security 2.0 document –analysis and outline completed.  Working to define feedback process 

* Architecture 
  * Defined 6 enhancements for Voice Agents interoperability (comm infrastructure, VRS 1.0, Switcher-Roo, Arbitration, data share, private persona)
  * creating roadmap of tasks for each of the 6 layers 
  * POCs being created for each of the 6 layers 
  * OVON Workshop demo being planned for each as well 

* VRS
  * 2 POCs developed (RUST app built from scratch, DNSMasque)
  * Looking to discuss with Deutsche Telekom 

### Open item discussion/news/adjournment 
* Collaborative discussions will provide some insight into how we might need to move forward
* Good to see progress from all teams 

Meeting adjourned at 9:54am ct 


# 2021-08-20 Notes of the Technical Committee Meeting

Attendees:  J. Larson, K. Dank, J. Stine, O. Coleman,  J. Trammell, N. Myers,  S. Baul, J. Crabb, P. Gogal

The meeting began at 9:02 am CT

### Antitrust statement and notice of recording  -- J. Stine 

### Review of the agenda, purpose of and expectations for the meeting  -- J. Stine 

### Open Voice Network News 
* Synthetic Voice Study Group Report due EOM September 
  * Potential impact to authentication, payment as well as advertising-media-entertainment areas
  * Recommendations will be brought to the Technical Committee for review and action 
* Open Voice Network headlines in *Variety* 
  * Detailed coverage of OVON white paper on the use, value of voice assistance in the media and entertainment industries
  * Authored by OVON Ambassadors Donald Buckley and Janice Mandel
* OVON initiating outreach to Health & Wellness industry 
  * Goals for SME participation and sponsorship
  * OVON Ambassador:  Harry Pappas, CEO of Intelligent Health Association

### OVON Technical Committee moving forward
* Recommend monthly meetings 
  * 3rd Friday of the month following the Steering Committee 
  * Agreed that some can be extended to 90 minutes due to content and/or setup separate review sessions as needed 
* Request representation from every OVON sponsor 
* Begin process of recruiting a new chair of the OVON Technical Committee (rotate among sponsors every 6 months)
   * Discussed role of Vice Chair and Chair –where Vice Chair moves to Chair after 6 months rotation.   This will go to the Steering Committee 
* Confirm central functions of the Technical Committee 
  * Ways of working:  tools, processes, vocabulary (code-owner per workgroup). [Link to git Ways of Working doc]( https://github.com/open-voice-network/docs/blob/main/way_of_working.md)
  * Strategic direction:  areas of resource investment (time, personnel, monies)
  * Deliverables:  confirmation and review 
  * Master Plan:  development, review, final decisions 
* Need for Chief Architect for OVON
  * Need to define job description and role definition 
  * Assumed to be a part time position and volunteer at this point 

### Investment of OVON R&D Funds 
* Reminder to submit your needs using the form that Jon has shared 
* Deadline for forms 8/27/21 
* Technical committee will review and bring to the Steering Committee accordingly 

### Intellectual Property Licensing – Update 
* Jon will setup 2 new projects to accommodate the licensing requirements of The Linux Foundation 

### Technical Committee Workgroup Updates 
* Privacy 
  * Privacy Guidelines 1.0 circulated and reviewed by end of September
  * Privacy 2.0 document drafted for review by end of September 
  * Privacy v2.0 document completed by end of October 
  * Ready to submit form for resources by deadline
* Security 
  * Security Guidelines completed first draft 
  * Submitted form for resources with high priority need 
  * Completing outline and creating draft Security Guidelines document for review by end of October 
* VRS
  * Deployment of VRS 1.0 (MVP) by end of September for use and review 
  * Agreement on VRS 2.0 scope by end of October 
* Architecture 
  * Establish 1.0 library of interoperability scenarios –to publish in git 
  * Publish 1.0 requirements for sharing dialogs and data between conversational agents 
  * Defined 6 enhancements for Voice Agents interoperability 
  * Deutsche Telekom will be initial user   
  * No resource requests at this time 

Meeting adjourned at 9:51am ct 


# 2021-07-23 Notes of the Technical Committee Meeting

Attendees:  J. Larson, K. Dank, J. Stine, O. Coleman, M. Brinas-Dobrowski, J. Trammell, N Myers,  A Paik, D Rogers,  S Austin, S. Baul

The meeting began at 9:03 am CT

### Antitrust statement and notice of recording  -- J. Stine 

### Review of the agenda, purpose of and expectations for the meeting  -- D. Cundiff 

### Alignment: Open Voice Network News, Vocabulary Updates  --J. Stine 
* OVON vacation first 2 weeks of August –enjoy! 
* The new acronym for Open Voice Network is OVON.  We ask the spelling out as O-V-O-N
* We are an Open-Source association of the Linux Foundation 
* Per Linux Foundation, Jon has initiated the process of creating 2 new technical projects for VRS and Architecture work group 
* Investment of OVON R&D Funds
  * Do need a formal write up.   Verbal reviews done at prior technical committee meetings do not suffice
  * Jon Stine will share out a template for resource requests
  * Please then send to Jon Stine
  * Will leverage technical resources of TLF as a first source, else other sources as needed 
  * Keep in mind IP implications
* OVON was presented to the EU on 7/21/21.  This will also be shared with the Steering Committee meeting.  Jon will post slides & white papers in slack 
 
## The OVON Technical Committee Workgroups –the plan through year end:  
## AWG
* The workgroups vision of “the rocket” it is building and how it fits into the whole 	
* Update on deliverables 
   * Requirements Document  
   * Draft Framework 
   * Data Sharing Project 
   * Arbitration Project 
   * Timing and Roadmap will be created later in August for review in September.   First Demo likely available in early 2022 
 * Update on investment plans
   * Will have needs but specifics to be determined 

## Privacy &Security Workgroup 
Privacy 
* The workgroups vision of “the rocket” it is building and how it fits into the whole 
  * Phases and phases to be completed this year 
    * OVON Privacy guidelines review on 2021.8.25.  11am central time 
    * Privacy Guidelines & Capabilities v2.0  Due 2021.10.30
    * Privacy Standards, OVON “privacy certification” v1.0 due 2021.12.31
* Update on deliverables 
  * Privacy Guidelines and capabilities v2.0 - completed 
  * Enterprise privacy policy assessment – in progress 
  * Privacy policy template- not started 
* Update on investment plans
  * Will need a technical writer and some legal counsel (Separate funding available for legal needs).  Specifics to be determined 

Security 
* The workgroups vision of “the rocket” it is building and how it fits into the whole 
* Update on deliverables 
    * Finalize document outline by August 
    * First Draft by October 2021
* Update on investment plans
  * will need a security expert –specifics to be determined.   Will work with Doug Rogers on potential resources there 

## VRS
* The workgroups vision of “the rocket” it is building and how it fits into the whole 
  * Vision in 5 years – global usage of VRS, Voice assistant platforms are using VRS, scaled and modularized 
* Update on investment plans
  * Will need software engineers.  Specifics being documented for submission 

Meeting adjourned at 10:00am CT

# 2021-06-25 Notes of the Technical Committee Meeting

Attendees:  J. Larson, K. Dank, J. Stine, O. Coleman, M. Brinas-Dobrowski, J. Crabb,  J. Trammell, Nick Myers,  D. Cundiff, M. Lens-FitzGerald 

The meeting began at 9:04 am CT

### Antitrust statement and notice of recording  -- J. Stine 

### Review of the agenda, purpose of and expectations for the meeting  -- J. Stine  

### Alignment:  Vocabulary and Ways of Working --J. Stine 
* It’s the Open Voice Network and NOT the OVN (the OVN acronym is owned by another organization) 
  * We are an Open-source association of the Linux Foundation 
  * We are also a 503-c-6 non-profit industry association 
* Reminder : GitHub for issue and Milestone Management.   Git is our source of truth of current and future tasks and registration of milestones, deliverables and dates 

### Alignment: Open Voice Network News  --J. Stine 
* Official press and PR launch occurred on Tuesday 22 June !
  * Special thanks to Jon for leading the way!
* Voice Agenda Interoperability Workshop took place 15-17 June 
  * More than 20 consistent attendandees across 5 countries 
  * Recordings and documents stored in Open Voice Network Google space 

### Open Voice Network Voice Agent Interoperability Workshop:  Lessons learned, next steps  - J. Larson
* Attendees covered many countries and industries 
* Included presentation on the Amazon Voice Interoperability Initiative, W3C Intelligent Personal Assistant Architecture 
* Immediate Benefits: 
  * Made new connections 
  * Got good advice
  * Learned about new ideas and thoughts
* Long Term Benefits:
  * Midcourse corrections
  * Better results 
  * Wider influence 

### Mid-Year Review:  Deliverables, Opportunities 
* Publish and Pilot – Green 
* Grow Participation – Yellow 
* Process:  Standardize Ways of Working – Green (light green)  
* Reviewed deliverables from each work group –delivered and future 

### Open Voice Network R&D Investment first thoughts:  Investment of 2021 Open Voice Network Research & Development Funds
* Process: 
  * Work Groups identifies and creates a SOW and brings to the Technical Committee
  * Technical Committee approves (or denies) 
  * Goes to the Steering Committee for approval  
* Privacy and Security Work Group
  * Need of a Technical Writer to improve the quality of the Privacy Guidelines v 2.0.  Estimate is $3k (40 hours) 
  * Need of legal review assistance to improve the Privacy Guidelines v 2.0.  Estimate is $5250 (35 hours) 
* Architecture Work Group
  * Need of programmer to work on prototypes to:  invoke/pause/resume on voice agents; route data from voice agents to a module;  share parameter values between agents.     Estimate is 2 person months
  * Discussed goals and value of the prototypes and if other firms have already proven 
  * Discussed that working on interoperable general assistants (alexa x GA x bixby x siri) may not be useful as making a general assistant work with an independent one
* Voice Registry System Work Group 
  * Need Senior/Lead Engineer to build features to scale the VRS platform.  Estimate is 3 person months initially.  
* Discussed need for infrastructure work as a potential gap.   VRS is expecting a full stack developer that might be able to do this or Target resources might be able to cover 

Meeting adjourned at 10:01 CT


# 2021-06-11 Notes of the Technical Committee Meeting

Attendees:  J. Larson, K. Dank, J. Stine, O. Coleman, M. Brinas-Dobrowski, J. Crabb,  J. Trammell, Nick Myers,  S. Baul, D. Cundiff, M. Lens-FitzGerald 

The meeting began at 9:01 am CT

### Antitrust statement and notice of recording  -- J. Stine 

### Review of the agenda, purpose of and expectations for the meeting  -- J. Stine 

### Open Voice Network News  --J. Stine 
* Open Voice Network is celebrating 1 year anniversary 
* Dan Cundiff is no longer with Target and is now at The Gap but will remain the Tech Comm Chair through August
* Deutsche Telekom, Veritone now Open Voice Network sponsors.  Public announcement scheduled for 22 June
* OVNet 2021 budget for Tech Comm approved.   R&D now >$160k 

### Investment of 2021 Open Voice Network Research & Development Funds
* Open Voice Network Tech Comm is now at the point of hiring resources to create & accelerate work group deliverables 
* Open Voice Network R&D budget $162k.  Process: 
  * Direction (25 June)
  * Propose-> Technical Committee  approval -> Steering Committee approval 
  * SOW
* Keep in mind IP Implications
  * Will execution require a new or broader community? 
  * Will this require more than a CC4 license?  Might there be patentable content?  Code?  
  * May require a Community Specification license
* Jon has a form for investment requests and Jon will share out via slack
* Discussed how to recognize the volunteers that have /are working on Open Voice Network 
  
### Voice Agent Interoperability Workshop 15-17 June – Workshop Program Committee 
* Agenda posted on the Open Voice Network Website –[link to site]( https://openvoicenetwork.org/voice_interoperability_form/)
* 3 days of presentations followed by Q&A
* Goals include getting more ideas on interoperability and recruiting additional resources 
  
Meeting adjourned at 9:58 ct




# 2021-05-14 Notes of the Technical Committee Meeting

Attendees:  J. Larson, K. Dank, J. Stine, O. Coleman, D.Cundiff, M. Brinas-Dobrowski, J. Crabb, C. Wuttke, M. Lens-FitzGerald, S. Prayaga

The meeting began at 9:02 am CT

### Antitrust statement and notice of recording  -- J. Stine 

### Review of the agenda, purpose of and expectations for the meeting  -- D. Cundiff

### OVN News  --J. Stine 
* 5th and 6th financial sponsors anticipated by end of May 
* With additional sponsors, R&D budget anticipated to grow for workgroup investment as approved by Tech Comm and Steering 
* Planned PR launch currently planned for June 8
* With the growth in financial sponsorship, Network Now an “open-source community” of The Linux Foundation enabling more cross Linus Foundation community collaboration 
* OVN communication growth:  K-12 Education & Commerce.  Media, Healthcare and Manufacturing in progress
* Network affiliations growing as well

### OVN Vocabulary:  key words, phrases – J. Stine 
* It’s the Open Voice Network –not the OVN (acronym owned by other and OVN will need to be replaced in our documentation by Open Voice Network)
* We’re an open-source association of the Linux Foundation (also a 503-c-6 non-profit industry association under US law)
* It’s a conversational facilitator – it coordinates communication between two or more dialogue systems and/or processing during the source of one or more sessions
* It’s Interoperability  (interoperability is not in our vocab doc currently)  - Discussion: 
   * Creating standards for operational agents to share data and functions 
   * Should we separate and define separately hardware interoperability and software interoperability? 
      * sounds logical but there are very different views 
      * doubles the work 
      * agreed to assign this to the Architecture Workgroup and bring back a working definition to the next tech comm meeting and there will be some additional discussion first with regard to need to define this 

### IP Licensing: next steps for OVN Technical Committee Work Groups – J. Stine, D. Cundiff
*  Specification and documentation will be received and made available by the project under the creative commons attribution 4.0 international license
*  If code is contributed to support the project, all new inbound code contributions to the project must be made using the Apache License, Version 2.0
* All new inbound code contributions must also be accompanied by a developer certificate of origin [here](http://developercertifcate.org) sign off in the source code system that is submitted through a technical committee approved contribution process which will bind the authorized contributor and, if not self-employed, their employer to the applicable license

### Voice Agent Interoperability Workshop 
*  More information to come via slack 

### Review of 2021 Technical Committee deliverables and progress-to-date – M. Lens-Fitzgerald, O. Coleman, J. Larson, S. Prayaga, M. Brinas-Dobrowski 
* Privacy & Security Work Group
  * reviewed deliverables to date and work in progress
  * additional resources needed in this workgroup! 
* Architecture Work Group 
  * reviewed deliverables to date and work in progress
* VRS Work Group
  * reviewed deliverables to date and work in progress
  * VRS MVP review at October 1 Tech Comm meeting 

### Outstanding items, news and events of note
* Project Silver – NGO with mission to make life better for older adults leveraging voice – M. Lens-FitzGerald
* Veritone offering to take celebrity voices for certain voice applications 
* Person behind Alexis’ voice was revealed this week 

Meeting adjourned at 9:59 ct


# 2021.04.30 Notes of the Technical Committee Meeting

Attendees: O. Coleman, D.Cundiff, S. Prayaga, J. Larson, J. Crabb, N. Myers, S. Baul, D. Rogers, D. Attwater, C. Wuttke, P. Gopal. J. Stine

### Ways of Working - D. Cundiff will document the new process in GitHub as a pull request. 
 * Decisions that need to be made should be entered as a Git issue
 * If decision can be resolved in the issue, we will do so
 * If it needs further discussion, bring to Technical Committee.  Standing agenda topic
 * Decisions will be documented in a markdown document for tracking purposes
 * If decisions can’t be made in Technical Committee, can be escalated to the Steering Committee

### Selection of programming language for OVN
 * Git issue #196
 * See issue for benefits of selecting single language
 * Rust is particularly attractive
 * Facebook wrote blog post yesterday about their adoption of Rust
 * Attract new set of talent to this organization
 * Interfaces should be agnostic of the underlying language 
 * Shyamala: Whatever language we use, we have to account for all operating systems — QNX especially for autonomous vehicles
 * Use the verbiage “primary/preference” as we describe
 * Dan will document via pull requests

### Vocabulary Alignment
 * Prefer the term conversation processor rather than component
 * Prefer conversational agent rather than voice application
 * Refer to Zoom recording for David A’s description
 * Dan: vocabulary alignment exercise has highlighted the need for examples for use of the terms, as well as refinement of the term definitions
 * The vocabulary is “ever green” — not written in stone and can be adjusted as we learn more

### Update:  Privacy and Security Work Group Update
- O. Coleman noted the on-time, 22 April 2021 submission of the OVN Privacy and Security Work Group response to the European Data Protection Board's publication of its 1.0 Guidance for Virtual Voice Assistants.  OVN-drafted response was submitted on behalf of the Linux Foundation

### Update:  Voice Agent Interoperability Workshop, Architecture Work Group
- J. Larson noted the receipt of five proposals for presentations at the OVN Voice Interoperability Workshop.  J. Stine noted expectation of several more

### Architecture Work Group: continuation of Tech Comm deep dive 
 * J. Larson presented an overview of The Architecture Work Group's current work:  continued development of a scenario library, development of initial requirements leading to interoperability.   
 * Meeting activity: meeting participants submitted "interruption" scenarios; discussion of S. Prayaga's verbalized scenario

### Meeting adjourned at 10:01 Central Daylight Time (US). 


# 2021-04-16 Notes of the Technical Committee Meeting 

Attendees:  J. Larson, K. Dank, J. Stine, O. Coleman, M. Frazzini,  N. Myers,  D.Cundiff, M. Brinas-Dobrowski, J. Kline, Y. Martinez, D. Rogers, J. Crabb, C. Wuttke, D. Dahl

The meeting began at 9:01 am CT

### Antitrust statement and notice of recording  -- J. Stine 

### Review of the agenda, purpose of and expectations for the meeting  -- D. Cundiff
* Intro of new attendees 
  * Yaser Martinez – Deutsche Telekom

### OVN Vocabulary:  key words, phrases 
* Conversational Context – info extracted from n prior utterances of the current conversation
* Conversational AI – Tech that enables automated communication between computers and humans.  Could be speech or text
* Explicit Invocation- Where the user invokes the channel, and it explicitly stating a direct command to accomplish a specific task
* Implicit invocation- where the user invokes the channel and uses the most common words or indirectly saying the explicit invocation 

### European Data Protection Board VVA Guidelines –requesting comments –due 4/23/21 
* OVN Privacy & Security Work Group developing a formal response.   Draft is out to OVN Steering Committee and TLF legal counsel for review & comments 

### Q2 Milestones – to be identified in Git as of 30 April 16, 2021

### Ways of working:  OVN programming language; hosting OVN POC’s  -- D. Cundiff
* OVN Programming Language – Rust 
  * “Rust is every bit as important as a revolution as C”  - Bryan Cantrill 
  * Strengths:   safety, rich std library but can opt out, linux kernel, jobs
  * Discussion:  
     * Is Rust acceptable to our constituents – yes.  Any APIs created will be independent of Rust itself
     * Rust may not be a fit for all – ex. Web dev so we will likely have more than 1 language
     * Should we survey our customers to see what they would accept?    This should not be an issue as there is a front end API in front of it
     * We can use our POCs to prove out the decision 
     * Does Rust support http, etc. type protocols?   Yes 
     * Support for a standard language –some concern with regard to Rust knowledgeable resources to perform the coding 
  * Agreed to finalize decision in next Tech Comm mtg 30 April
  * [webrtc:]( https://github.com/webrtc-rs/webrtc) 
  * [Git issue for this:]( https://github.com/open-voice-network/docs/issues/196)

* OVN POC Hosting 
  * We will need hosting and should use a cloud service – and since Microsoft is an OVN member, recommend that we use their Azure solution 
  * Discussion: 
     * benefits of selecting 1 cloud provider over another? We aren’t at the point yet where we have specific requirements 
     * general support for Azure and decision agreed to 
  * [Git issue for this:]( https://github.com/open-voice-network/docs/issues/198)

### Deep Dive:  Architecture – J. Larson
* Workshop on Interoperability 
   * Workshop on 15-17 June 2021 (2 hours per day)
   * Goal to present current perspectives and gain feedback and other thoughts 
   * If you have invitee suggestions, please send to jim42@larson-tech.com
* Scenarios
   * Team is gathering interoperability scenarios 
   * Describes how user interacts with conversational agents 
   * Describes how conversational agents act when switching platforms 
   * Drives our specification of interoperability requirements 
   * Scenario sourcing in meeting: 
      * User wants to talk to Etsy using Google Assistant. User does not have an account with Etsy so she created an account by linking her Google account
      * User is therefore ready to pay but wants to pay using the PayPal action in Google Assistant
      * Guest wants to return Target product –initiated with Alexa and wants to connect with Target call center voice system and keep identity
      * User wants to check in to flight and periodically check flight status.  Also would like to interface with airport parking to expedite parking
      * User receives an at-home diagnostic test. The test provider has a voice app for Alexa and Google Assistant to help them complete the test. The user activates the voice app and needs to authenticate in order to complete the test. Once the user is authenticated they use the voice app to complete the test and are prompted to complete follow up survey. The survey becomes anonymized and is then sent back to the provider for review. (Hopefully this was a good scenario)
     * In the store and need to find Gluten Free Pizza.  Shopper says: Wegmans, where is the Pizza located that is on my list?  Response: Which Pizza do you want?  Wegmans Gluten Free Pizza or Celeste's Pepperoni Pizza?  Shopper says: Wegmans Pizza? Response: It is located in the Health Foods Freezer located near aisle #1.  Do you want this item marked off your list?  Shopper says: Yes.
      * Scenario: User wants to refill a prescription:  User: “Hey platform, I need to refill a prescription.”
Platform Agent: “OK, I need to verify you and find an agent to handle your request.”
Platform Agent: “Please provide verification” (verification routine) Platform Agent: “Do you have a service in mind to refill your prescription?” User: “Yes, its XYZ provider” Platform Agent: “OK, I am contacting XYZ provider.  Do you provide consent for verification and exchange of account information with XYZ provider?”
User: “Yes” XYZ Provider Agent: “Hello, this is XYZ Provider Agent.  You have been verified with consent to exchange information and I am ready to handle your request to refill your prescription . . .”
* Requirements Document 
  * Due to time , discussion will continue at next meeting 

Meeting adjourned at 9:59 ct


# 2021-04-02 Notes of the Technical Committee Meeting 

Attendees:  J. Larson, K. Dank, J. Stine, O. Coleman, M.Lens-FitzGerald, M. Frazzini,  N. Myers, S. Baul, D.Cundiff

The meeting began at 9:02 am CT

### Antitrust statement and notice of recording  -- J. Stine 

### Review of the agenda, purpose of and expectations for the meeting  -- D. Cundiff

###  Open Interoperability Workshop – J. Larson, J. Stine 
*  OVN hosting an Open Interoperability workshop  June 15-17, 2021
*  Details on www.openvoicenetwork.org 

### OVN Vocabulary Alignment 
*  From our vocabulary, discussed the following to ensure alignment and evangelization in our documentation: 
   * Conversational Agent 
   * Virtual assistant system 
   * Conversation processor
   * Conversational endpoint  *endpoints are sometimes referred to as a channel*
   * Organizations  *not enterprises or entities* 
* Suggestion that we should introduce the vocabulary at the June Open Interoperability Workshop and to post on the OVN website 

### Deep Dive:  Voice-specific Security (M. Lens-Fitzgerald)
* Activity up to now
   * Workgroup started July 5th, 2020
   * Voice Security Capabilities report published October 2020
   * 2nd round:  threat scenario analysis started March 2021 
* Threat Scenario Analysis
   * Used STRIDE framework to identify categories of threat.  Ex. Spoofing, tampering, repudiation…
   * Vulnerability is a key focus area
   * Systems to analyze :  Home speaker assistant, Phone assistant, Car assistant, *In-store assistant*
   * Using the “Alice and Bob fictional character” set commonly used in security 
   * Creating threat scenarios 
* Deliverables 
   * Delivery Exercise –Security & Voice Assistants Needs: 
        * Group provided many examples of needs- A lot of really great examples shared!   
          * Consulting firm:  a maturity model on the topic of security in voice that reflects both best practices for the known current state and educated projections for the next-phase future state.  A lifespan of 18-24 months.  Can be used as a discussion tool with clients, a model practice development, a soft/general overall industry compliance model
          * Industry-specific guidance on voice data (i.e., healthcare, commerce, etc.)
          * Voice-specific guidance on proper data handling and protection on top of existing data security guidance and practices
          * Guidance on voice-specific security as it relates to existing regulations (i.e., HIPPA)               * Guidance on voice-specific security breaches
          * Areas of threat based on use cases
          * A deep dive guideline with examples, what specific design, architecture and code-based preventative steps should a company take based on that
          * How do security measures interoperate - what qualifies as something another company can trust when an interaction is handed off to another
          *otep
          *standards or best practices on how to indicate what security is applied
          * use for OWASP 10 or SANS assessments
          * threat modeling to prioritize enterprise risks
          * product management create security-related use cases
          * Conversational Agent (User) – An OVN security certification and summary of what protection standards and benefits are provided        
          * VAS Designer - Guidelines and Capabilities for ensuring adequate confidentiality, integrity, and availability of Virtual Assistant Systems
          * VAS Marketer - An OVN security certification and program for compliance.
          * Home telephone:  call filter to screen telephone calls, black list of calls not to accept, Eaves dropper to detect possible fraud
* Next Steps 
   * Write up scenarios
   * Publish scenarios 
   * Create and publish something 
   * Explore security capability analysis test 
   * Participate in Cyber Security Month

* Reminder of Deep Dive Scheduled for 16 April:  Architecture 

Meeting adjourned at 9:59 ct




# 2021-03-19 Notes of the Technical Committee Meeting 

Attendees: J. Stine, O. Coleman, N. Myers, D. Cundiff, A. Fricke, M. Frazzini, M. Brinas-Dobrowski, R. Nathenson, D. Rogers, S. Prayaga, P. Gopal, S. Baul.

Meeting commenced at 9:02 a.m. Central Daylight Time (US).

### Welcome, antitrust statement, and notification of recording 

### Introductions: No new attendees

### Announcements:
•	J. Larson unable to attend today.
•	European Data Protection Board (EDPB) released "1.0 Guidelines for Virtual Voice Assistants."  General observations: applies GDPR to virtual voice assistance; is now the benchmark for the voice industry; current OVN privacy ork aligns nicely with the EDPB guidelines.
o	Other observations: EDPB guidelines focus on current state of the major platform duopology; does not anticipate the hybrid ecosystem of the independent enterprise virtual assistant; does not address a non-cloud architecture; does not address the future of interoperability – the sharing of dialogues; does not address issues related to voice data analysis, including biomarkers or other advanced voice data analysis.

### Work Group Progress Toward Quarterly Milestones 
J. Stine reminded Work Groups in re: Q1 Deliverables (two weeks remaining) and Q2 Deliverables, to be defined by March 31, 2021.  Also: an expectation that existing and in-work documents will be reconciled to the official OVN vocabulary by end of April 30, 2021

### Q1 Milestone Deliverables / Updates

VRS
•	Green -- publish schema 1.0
•	Green -- agile practices
•	Green -- job descriptions
Two independent development companies have raised their hands to help build out the VRS MVP.

Architecture
•	Blue – Deliver extensible foolproof strategy for sharing components by EOQ1.  
Architecture Work Group reported a pivot in strategy; from a standardization of components to research/study into what is required to share dialogues (and context, control, and privacy-security) between conversational agents.   A five-step process documented, described for moving forward. 

Privacy & Security
Privacy
•	EDPB: review underway by the team.
•	Privacy Guidelines 1.0 – publishing the pull request to address items discussed in the Technical Committee “deep dive”.  Will be incorporated this weekend.  
o	Add legal disclaimer to document
o	More language for “opt in” by default
o	Mike will take first pass at the vocabulary also with this pull request
•	“Friends and families” – NRF, FMI, Ecommerce Europe, AVIOS conference, OVN Ethical Use are suggested candidates to review the document.

Security
•	Threat Modelling exercise should be wrapped by end of April.
•	Doug: Threat Modelling output should be leveraged by the development teams of the VRS MVP implementation work.  Maria: work slated for July.
•	Incorporate the scenarios from the Architecture group as the next round of threat modelling exercise.  

Privacy Policies Comparison, Analysis
•	Green: Q1 work on track.
•	Research work completed by end of March.
•	Plan to have the summary for Tuesday’s Privacy & Security workgroup meeting.  
•	Will be prepared to give a high-level overview of the summary in the next Technical Committee meeting.


VRS Deep Dive
•	M. Brinas-Dobrowski provided a detailed overview of VRS process and decisions to date.  Discussed at length the options and decision-making in re: the role of NLU in VRS identification and routing; noted clear preference to pursue simplicity -- VRS to have a singular function.  Also reviewed initial data schema for VRS registration/recognition.  S. Prayaga noted need to determine, document registration processes; agreement that such work was still TBD.  
	D. Rogers povided this guidance on semantic versioning: https://semver.org/
	J. Stine noted interest from China Netcasting Services Association (CNSA) to engage, potentially adopt a VRS system from OVN. 
	
### News/Notes:
•	D. Cundiff noted formation of Croqui, start-up of former Mozilla team.  May offer opportunities for OVN development work. 

### Meeting adjourned at 9:58 CDT. 





# 2021-03-05 Notes of the Technical Committee Meeting 

Attendees:  J. Larson, K. Dank, J. Stine, M. Brinas-Dobrowski, O. Coleman, M.Lens-FitzGerald, S. Prayaga,  M. Frazzini, R. Nathenson, N. Myers, D. Rogers, S. Baul, J. Eisenzopf, D. Attwater, D. Ryder

The meeting began at 9:04 am CT

### Antitrust statement and notice of recording  -- J. Stine 

### Review of the agenda, purpose of and expectations for the meeting  -- J. Stine

### Comment/review:  Adam Cheyer presentation of 2021.03.04
* Good discovery algorithm will be complicated to define and put in place 
* Model interoperability is the focus of Adam’s work and was thought provoking 
* Loose coupling is a correlation with the OVN work so far 
* Key philosophical decision –really strong framework needed and we will need to be clear on the problems that we are trying to solve 
* Adam finds out work valuable but he feels we should be going beyond standards
* Would love to learn more about Adam’s learnings and gain better understanding of his POV
* Loved how he thinks and is true to his role 
* We need to assess if the big players are ready for standards
* Voice assistance lack the back button like on the browser –no consistent approach for this with voice and might be an opportunity for OVN 

### Quarterly milestone review – Q1 Blue (fka Red), Yellow, Green
VRS
  * Publish schema 1.0 – BLUE
        * need an engineering resource 
  * Process – GREEN
         
Architecture 
   * Define extensible strategy for evolving components –BLUE

Privacy
   * Voice privacy guidelines 1.0 – GREEN
   * Working with workgroups and communities – GREEN
   * Friends and Family Feedback - GREEN

Security
   * Voice Security Guidelines 1.0 – GREEN-COMPLETE
   * Working with workgroups and communities – GREEN
   * Friends and Family Review –shift to Q2 

Privacy and Security Research 
   * High Level Overview –GREEN
   * Publishing an high level draft overview – GREEN

### Deep Dive:  Privacy (M.Fazzini) 
  * [link to doc]( https://github.com/open-voice-network/docs/blob/master/Privacy%20Guidelines%20and%20Capabilities.md)
  * Issues and Risks Discussion: 
      * Focus on information rather than identity –is the risk to biometric identity adequately addressed?   Team to evaluate if additional focus necessary
  * Values, Guidelines and Technical Capabilities Discussion:  
      * Transparency 
         * How will the privacy policy be presented verbally?    Envision that the voice assistant could actually read the policy or point to a website for full policy detail.     Some concern that this goal may not be achievable 
         * The consumer has been in a position where the onus of data protection falls with them.   Time is now for producers of technology to share that responsibility (meaning that implicit consent goes away)
      * Consent 
          * Is the present status of consent implicit today with current voice providers?  Currently is implied and we are pushing for explicit 
          * What is the process of the user disagrees with the consent? 
          * How do we qualify this with respect to the law?  
          * Guidelines need more teeth in order to be enforced.  Also need to define the boundaries for enforcement  
      * Limited Collection 
      * Control 
      * Recommended Next Steps

* Reminder:   VRS Deep Dive scheduled for March 19,  Security April 2, Architecture April 16

Meeting adjourned at 10:00 ct



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

