# Voice Registry System Meeting Minutes
This document is meant to capture the meeting notes and decision.

## Meeting 03.04.2021
<details>    

### Agenda:
- Discuss the PR#159 VRS Type.
- Discuss the other issues open. 


### Discussion:
- 

</details>

## Meeting 02.18.2021
<details>    

### Agenda:
- GS1 Phil Archer guest presenter

### Discussion:
- He presented his [thought](https://drive.google.com/drive/folders/1b4liMvkl6Xv9P8U0Cw09IHi7E4b9PE2t) on VRS.

</details>

## Meeting 01.21.2021
<details>    

### Agenda:
- Prioritize the VRS GIT issues

### Discussion:
- The team prioritized some git issues based on need and deliveries.
- Discussed the standard in creating the GIT issue. Identify the problem and definition of done. 
- Decided to follow an architecture decision log whenever some critical decisions need to be ratified and vetted. The architecture decision logs are still stored in the git repo.
- We discussed the OVN Pull Request process. 

</details>

## Meeting 12.15.2020
<details>    

### Agenda:
 - Discuss the working style (GIT projects, GIT issues, Assigning work)
 - Prioritize the VRS GIT issues

</details>

## Meeting 12.03.2020
<details>

### Agenda:
 - Shared the feedback from the presentation
 - Discuss the next steps (identifying requirements, dependencies)
 - Identify governance for the registry. Do we need one? What it would like?

</details>

## Meeting 11.06.2020
### Action Items from 10.29.2020:
- Closed the #66 - owner: @maridob
- Add the rewording suggestion by @omitfo2 - owner: @maridob
- Jon will adjust the time of the recurring meeting - owner: @jcstine

### Agenda:
- Discuss the open issues
- Build the content the Nov 20 Technical Steering Committee report. 


## Meeting 10.29.2020

<details>
<summary>click for meeting details</summary>

### Action Items from 10.15.2020:
- @Lens-fitzgerald will need to respond on my comment [#76](re: https://github.com/open-voice-network/docs/pull/76)

### Agenda:
- Review the decision made last 10.15.2020
- Review prioritization of the problem
- Discuss the integration of VRS with other components
- Discuss the "context" concept
- Review the active issues

### Discussion/Decision Points:
1. Reviewed the decision made last 10.15.2020. VRS roles and responsibilities in the world of Voice.
    - Central location for invocation and platform agnostic.
    - Provide a consistent experience across conversational platforms and/or entity's conversational assistant.
    - VRS is not responsible for the interpretation of the intent of the user.
    - VRS can hold various attributes regarding the invocation, such as name, alternative names, category, geolocation.
    - VRS can receive inputs like the user's current location but is not responsible for storing its preference. 
    - VRS names can have synergies.
2.  Prioritization for VRS
    - Bucket 1
    - Bucket 2
3. "Context" concept will be discussed in the architectute meeting group.
4. VRS integration with other components will be pushed for another meeting.

### Action Items
- Closed the #66 - owner: @maridob
- Add the rewording suggestion by @omitfo2 - owner: @maridob
- Jon will adjust the time of the recurring meeting - owner: @jcstine

### Next Meeting Agenda:
- Build the content the Nov 20 Technical Steering Committee report.


</details>

## Meeting 10.15.2020

<details><summary>click for meeting details...</summary>

### Action Items from 10.01.2020:
- @Lens-fitzgerald will create PR for the additional problem context #69 and #70
- @omitfo2 will create PR for the problem context #66.
- @Lens-fitzgerald will propose the definition for Conversation Assistant
- @maridob will create a new poll for the new set of the problem context. 
    >> Poll is sent and created on 10.13.2020 4 PM CST time.
    >> /poll "Please select the problems that you think should be solved and prioritize by the VRS. The details description of the problems are" "Provide consistent experience across conversational platforms and/or entity conversational assistant." "Disambiguation of entities location." "Disambiguation of entities - homophone." "Disambiguation of entities - homograph." "Lack of central location for invocation availability." "Correction of mispronounciations." "Indirect invocation of application apps. Ex: Add milk to Tarjey." anonymous
    >> This poll is Issue #77

### Agenda:
  - Discuss the goal of the meeting. Goal: Finalized the problem prioritization that VRS can solve.
  - Discuss the architecture guidance for VRS. The architecture guidance should help us to align the scope of the problem for VRS.
  - Discuss and ratify the business value for each problem prioritization, based on the poll. The outcome of this discussion will be brought back to the Technical Committee.
  - Check if we achieve our goal. If not, why? 

### Discussion/Decision Points:
As we are trying to build the VRS component's role and responsibilities of VRS in the OVN architecture world. Like Dan's analogy of building a rocket, it will NOT only take 1 component to make it work. To state the obvious, it's going to be more than one.  The critical thing to resolve is the role of the component in building the rocket. Like any component building process, it should start in identifying the problem context and scope. Along with identifying the responsibilities, there are some architecture principles guidelines that we would like to follow. 

- Single Responsibility
- Loose Coupling
- Event-Driven
- Availability and Partitioning Eventual Consistency
- Interface segregation
- Automation (CICD, DevOps, Containerization, Service Mesh, Observability, etc.)

In identifying the problem context, we focused on the Single Responsibility Principle. This benefits the VRS component to find the right amount of cohesive functionality and responsibility. This is to avoid the pitfall of being monolith or create tight coupling.

As we reviewed and got the feedback from the team about the problems. There is some noticeable gap with some of the issues brought forward.

> ![](component_assets/vrs_problem_poll.png?raw=true "Fig. 1 - VRS Problem Context Poll")

#### Problem #1 and #5 are the top 2 choices for VRS.

#1 Provide a consistent experience across conversational platforms and/or entity's conversational assistant.
#6 The lack of central location for invocation availability.

As you can see, it is very much apparent the remaining of the problem has more or less equal number of votes. There is a typical pattern that showed in Disambiguation. 

(1) The decision making for the right interpretation.<br>
(2) Relationship of the location, homograph/homophone/mispronunciation/alternate names with the invocation. 

#### In Problem #2, Disambiguation of Location. 
First use-case:
The user asks for "{wake word}, order 1 Tiramisu chocolate cake from Patrick's Dessert. The current user location is in Apple Valley, MN, where he lives.

Second use-case:
The user asks for "{wake word}, order 1 Tiramisu chocolate cake from Patrick's Dessert. The current user location is at Minneapolis airport, but his home location is in Apple Valley, MN. His intention is to order to the nearest location to his house and not his current location - so when he gets home, the dessert is already there.


There is multiple Patrick's Dessert from a different location. 
Patrick's Dessert Burnsville, MN (5 miles away from user location)
Patrick's Dessert Minneapolis, MN (20 miles away from user location)

Multiple ways to solve it:
- Take into account user location
- Take into account user preferences based on the user's history.
- Ask a follow-up question to the user before presenting the selected voice application. 

**RECOMMENDATION:**
- VRS should not be in the interpretation's decision-making business.
- Instead, it should be the source of truth of the relationship to the location and voice application. It can have the ability to receive the user's current location that can come from other components but will not store any user's preference. Although it will hold the voice application's selection or settings. 
- The VRS can return multiple voice applications to the "callee" based on the voice application settings.


#### In Problem #3, Disambiguation of entities - homophone.
 First use-case:
The user asks for "{wake word}, I want to talk to Cisco" 

 Second use-case:
The user asks for "{wake word}, I want to check the seafood category of 
Sysco" 

Multiple ways to solve it:
- Take into account user preferences based on the user's history.
- Ask a follow-up question to the user before presenting the selected voice application. 
- Understand the full context of the utterance. In this case, take into account the "seafood" relationship to the voice application.

**RECOMMENDATION:**
- VRS should not be in the interpretation's decision-making business.
- The translation of "voice to text" should be handled by other components outside of VRS. VRS is expected to receive a text.
- VRS can hold an attribute of a voice application's category.  Example: Cisco belongs to Technology, Networking Category, and Sysco belongs to Retail.
- VRS can hold an attribute of alternative names. Sysco can have alternative names of Sysco Food, Sysco, while Cisco can have an alternative representation of Cisco Networking, Cisco.
- The VRS can return multiple voice applications to the "callee" based on the voice application settings.


#### In Problem #4, Disambiguation of entities - homograph.
 First use-case:
The user asks for "{wake word}, set-up an appointment with Delta." 

 Second use-case:
The user asks for "{wake word}, how much is the flight from MSP to MNL with Delta?" 

Multiple entities are associated with Delta, such as Delta Dental, Delta Airlines, Delta Network, and like the above disambiguation scenarios, these can be handled in multiple ways.

Take into account user preferences based on the user's history.
- Ask a follow-up question to the user before presenting the selected voice application. 
- Understand the full context of the utterance. In this case, take into account the "flight" relationship to the voice application.

**RECOMMENDATION:**
- VRS should not be in the interpretation's decision-making business.
- VRS can hold an attribute of a voice application's category.  Example: Delta Dental belongs to Healthcare, and Delta Airlines belongs to Travel, Flight.
- VRS can hold an attribute of alternative names. Each voice application can opt to have their alternative names set-up. For example, Delta Airlines can have Delta, while Delta Network can have an alternative representation of Delta.
- The VRS can return multiple voice applications to the "callee" based on the voice application settings.

#### In Problem #6, Correction of mispronunciations.

This is a similar use-case to Problem #3 Disambiguation of entities-homophone, and we have identical recommendations.


#### In Problem #7, Indirect invocation of alternative names. Ex: Add milk to Tarjey.

This is a similar use-case scenario to Problem #4 Disambiguation of entities - homograph, and we have identical recommendations.

#### Other Recommendation/Decision
- Names have synergies
- Rescheduling the recurring meeting time to 9:30 CST

### Action Item:
- @maridob will review the PR of @Lens-fitzgerald and @omitfo2 for merging

### Next Steps:
- Discuss the integration of VRS with other components
- Discuss the "context" concept
- Review prioritization of the problem
- Review the active issues

</details>


## Meeting 10.01.2020

<details><summary>click for meeting details...</summary>

### Agenda:
  - @omitfo2 will walk through the issue #66 
  - @Lens-fitzgerald will walk through issue #69 and #70
  - @jcstine discussed the PR #68
  - Review the poll in problem prioritization 
  - Recap of the meeting (what can we do differently or keep?) - 5 minutes

### Discussion/Decision Points:
 - The issue #66, #69 and #70 will be added as part of the VRS problem context.
 - Anything deemed necessary that needs to be discussed in the VRS meeting will need to be added as a Github issue.
 - Continue the structure of the meeting.

### Action Item:
- @Lens-fitzgerald will create PR for the additional problem context #69 and #70
- @omitfo2 will create PR for the problem context #66.
- @Lens-fitzgerald will propose the definition for Conversation Assistant
- @maridob will create a new poll for the new set of the problem context

### Next Steps:
-

</details>


## Meeting 09.17.2020

<details><summary>click for meeting details...</summary>

### Agenda:
  - Action items are addressed from the previous meeting.
  - Solidify and prioritize the problem statement. In each problem, we need to assess the following:
      <br>(1) What is the problem?
      <br>(2) Who is affected?
      <br>(3) Where does it happen?
      <br>(3) Why is this problem important? What value does it bring?
  - Prioritize the importance of problem-based on business value and impact.

### Discussion/Decision Points:
- Discussed the difference between VII vs. OVN in general.
- Identified six problems that VRS can tackle. See git issues. 
- Problem 5 is an analogy of a Yellowpages. Any persona such as user, publisher, or technical resources can go to VRS as a central location to find voice application or invocation available. 
-  Marteen mentioned the Conversational Platform should be defined as an assistant. We will discuss this in the next meeting.

### Action Item:
  - Prioritize the importance of problem-based on business value and impact.

### Next Steps:
  - Create a poll, and people can vote on the problem prioritization.


</details>

## Meeting 09.03.2020

<details><summary>click for meeting details...</summary>

**Attendance:** @maridob, @omitfo2, @rogerkibbe, @rmtuckerphx, @nkmyers0794

### Agenda:
  - Vote for the VRS moderator
  - Discuss the problem statement([#56](https://github.com/open-voice-network/docs/issues/56), [#57](https://github.com/open-voice-network/docs/issues/57), [#58](https://github.com/open-voice-network/docs/issues/58), ) submitted from the last meeting. 

### Discussion/Decision Points:
  - @maridob is voted for VRS moderator
  - Everyone agreed that we should be using the speaking language. See terminology alignment in the [VRS doc](https://github.com/open-voice-network/docs/blob/master/components/voice_registry_system.m)
  - Reviewed the above issues and rephrased based on the agreed terminology alignment. All notes for the individual issue are captured in the github | issue. 
  - Create an issue to add *technical resource* in the terminology alignment. 
    > Technical resource can be a publisher/developer. It can be a representative of an entity or independent party. Their role is to create an actual listing of the voice application.
  - Create an issue to add *voice application* in the terminology alignment. This is similar definition in the the [technical masterplan document](https://github.com/open-voice-network/docs/blob/master/technical_masterplan.md).

### Action Item(s):
  - Create an issue to add the *technical resource* terminology - Maria
  - Create an issue to add the *voice application* terminology - Maria

### Next Steps:
  - Solidify the problem statement.
  - Prioritize the importance of problem based on business value and impact.

</details>
