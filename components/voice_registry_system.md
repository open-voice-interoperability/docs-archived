# Voice Registry System

### Overview
Voice Registry System (VRS) is one of the components  in the
[Technical Masterplan](https://github.com/open-voice-network/docs/blob/master/technical_masterplan.md). The purpose of this document is to address the problem context of the VRS and why it is essential to resolve it. 

VRS's goal is to provide a consistent experience for the users and create an equal treatment for the entities despite their size - regardless of the conversational platform.

### Terminology Alignment
- **Channel** - an interface and origin of communication. It is where the utterances are received. Examples: voice assistance devices, mobile phones, web sites, etc.
- **Conversational Platform** - the system or services that handle the two-way interaction with the user and the entity.  The platform owns the task of understanding the user's utterance, translating it to humans, and machine exchange, and making sure it is reaching the right entity. 
- **Voice Application** - also known as skill, action, capsule or domain.
- **User** - a person who interacts with channels.  
- **Entity** -  government or private/public company that provides certain businesses or services.
- **Technical Resource** -  it can be a publisher/developer. It can be a representative of an entity or independent party. Their role is to create an actual listing of the voice application.
- **Explicit Invocation** - an invocation type where the user invokes the channel, and it is explicitly stating a direct command to accomplish a specific task. The direct authority is to communicate directly to a registered voice application.
- **Implicit Invocation** - an invocation type where the user invokes the channel, and use the most common words or indirectly saying the explicit Invocation. 
- **Query** - user’s word requesting for specific function and expecting a particular response.

### Problem Context
Today, voice assistance is dominated by proprietary, cloud-centric conversation platforms that deliver services using closed implementations.  Examples of these are Amazon Alexa, Google Assistant, Microsoft Cortana, and Apple Siri.  Whenever an "explicit invocation" is invoked by the user, each proprietary platforms have different standards (i.e., brand vocabulary, etc) and processes on how they are triggered or verified. 

Entities are at the commiseration of every single conversational platform on how they're transactions are getting triggered on the conversational space.  

Per the OVN principles, the current situation today does not align with the policy we outlined:
- Adhere to an open standard: due process, broad consensus, transparency, balance, and openness

Below are the **problems** identified in the current landscape.
<br>
<details><summary>1. The entity will not have a consistent experience across conversational platforms.</summary>
<br>
> The below diagram depicts a use-case scenario where Patrick's Dessert Kingdom is an entity that needs to be in multiple conversational platforms such as Amazon, Google, etc. The company is most popularly known for its name as "Patrick's Dessert Kingdom."  The entity wants the explicit command for their customer to what they are known for.  Fortunately, it is approved and available in Amazon and Microsoft but not on other conversational platforms. This is a problem for the entity and user. Users and entities will not have consistent experiences in dealing with the various conversational platform.

> ![](component_assets/vrs_problem_statement_1.png?raw=true "Fig. 1 - VRS Problem Statement 1")

</details>
<details><summary>2. Disambiguation of entities location.</summary>
<br>
> The second illustration shows a scenario where there are similar entities but on a different location. Today, each conversational platform handles this scenario differently and without transparency.

> ![](component_assets/vrs_problem_statement_2.png?raw=true "Fig. 2 - VRS Problem Statement 2")

</details>
<details><summary>3. Disambiguation of entities - homophone.</summary>
<br>
> Part of the complexity of voice is the homophone disambiguation. When the user utters an invocation, and there can be multiple possibilities for the invocation. 
<br>
> An example:
> A user utters, "{wake work}, I want to talk to Cisco." Multiple entities can sound like Cisco, such as Sysco Food or Cisco Networking.
<br>
> A couple of problems in this scenario: 
 - (1) who decides for the right interpretation 
 - (2) there is no central location of all the invocation homophone relationship
<br>
</details>
<details><summary>4. Disambiguation of entities - homograph.</summary>
<br>
> Part of the complexity of voice is the homophone disambiguation. When the user utters an invocation, and there can be multiple possibilities for the invocation. 
<br>
> An example:
> A user utters, "{wake work}, I want to talk to Delta." Multiple entities can be associated with Delta such as Delta Dental, Delta Airlines, Delta Network.
<br>
> A couple of problems in this scenario: 
 - (1) who decides for the right interpretation 
 - (2) there is no central location of all the invocation homograph relationship
<br>

</details>
<details><summary>5. Lack of central location for invocation availability.</summary>
<br>
> Due to the walled garden conversational platform landscape today, users or technical resources do not have a single area to go to check for the availability of the invocation. They have to go through each of the conversational platforms to verify the availability of the invocation. 

</details>

<details><summary>6. No consistent guidelines for invocation.</summary>
<br>
> Due to missing global standards, developers need to adhere to different conversational platforms guidelines. This results in complexity, heavy maintenance, and support for their voice application.

</details>
<br>
<br>

### Voice Registry System
The core solution approach to the problem is to stand up a neutral component that is not tightly associated with any of the conversational platforms to avoid any influence and bias. The VRS component will serve as the neutral party and address the balance and fairness for the user and entities. 

The primary role and responsibility of the VRS are to resolve the explicit invocation received by the conversational platforms if it is available based on a given location. The resolution will include taking into account the origin of the place of the utterance. The VRS will store the entities' preferred configuration that can be applied to all various conversation platforms. To achieve this, VRS is responsible for registry functionalities. 

To promote the OVN principle, VRS will support to run locally and globally at scale.

The expected input for VRS is the following:
- VRS type lookup
- location
- query

The expected output for VRS is the following:
- VRS type registered
- location
- entity configuration settings such as NLP default, dialog manager, dialog broker


### Architecture Options
Like any other problem, there are multiple ways to get to the ideal solution. The purpose of this is to look at options and ratify with the committee the best path forward.


#### Option 1 and 2

![](component_assets/vrs_proposed_solution_1.png?raw=true "Fig. 2 - VRS Proposed Solution 1")


#### Option 3

![](component_assets/vrs_proposed_solution_2.png?raw=true "Fig. 3 - VRS Proposed Solution 2")


#### Pros and Cons
| Options  | Pros                                                                                                                                                                                                                                                                               | Cons                                                                                                                                                                                                           |
|----------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Option 1 <br> Conversational platforms handle VRS type identification | - VRS does not have to implement NLU capability.<br>- Less integration point for VRS.                                                                                                                                                                                              | - Identifying VRS type is implemented in the proprietary conversational platform, which can possibly cause inconsistency.                                                                                      |
| Option 2 <br> VRS handles VRS type identification | - NLU will identify if the command is explicit, before passing to VRS.<br>- Identifying the VRS type is implemented in one area and consistent across the different conversational platform.<br>- Less integration for VRS.<br>- No additional integration for TTS/STT, less hop.  | - VRS has to implement NLU capability such as identify VRS type.                                                                                                                                               |
| Option 3 | - Identifying vrs type is implemented in one area and consistent across the different conversational platform.                                                                                                                                                                     | - VRS has to implement NLU capability, such as identification of invocation as explicit and identify VRS type.<br>- Increase the integration point for VRS.<br>- Additional integration for TTS/STT component. |


### Architecture Decision
TO-DO


### Discussions
1. Is VRS only going to focus on explicit invocation?
<br>-Similar to the web where if a user typed www.patrickdessertkingdom.com directly and the DNS resolver gets involve. This feels like a reasonable balance in for entities, and conversational platform. 
2.