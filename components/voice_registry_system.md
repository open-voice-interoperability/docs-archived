# Voice Registry System

### Overview
Voice Registry System (VRS) is one of the components  in the
[Technical Masterplan](https://github.com/open-voice-network/docs/blob/master/technical_masterplan.md). The purpose of this document is to address the problem context of the VRS and why it is essential to resolve it. 

VRS's goal is to provide a consistent experience for the users and create an equal treatment for the business despite their size - regardless of the conversational platform.

### Terminology Alignment
- **Channel** - an interface and origin of communication. It is where the utterances are received. Examples: voice assistance devices, mobile phones, web sites, etc.
- **Conversational Platform** - the system or services that handle the two-way interaction with the user and the business.  The platform owns the task of understanding the user's utterance, translating it to humans, and machine exchange, and making sure it is reaching the right business. 
- **User** - a person who interacts with channels.  
- **Business** - a commercial entity, services, or company.
- **Explicit Invocation** - an invocation type where the user invokes the channel, and it is explicitly stating a direct command to accomplish a specific task. The direct authority is to communicate directly to a registered voice application.


### Problem Context
Today, voice assistance is dominated by proprietary, cloud-centric conversation platforms that deliver services using closed implementations.  Examples of these are Amazon Alexa, Google Assistant, Microsoft Cortana, and Apple Siri.  Whenever an "explicit invocation" is invoked by the user, each proprietary platforms have different standards (i.e., brand vocabulary, etc) and processes on how they are triggered or verified. 

This is a problem for the business and users. Users and businesses will not have consistent experiences in dealing with the various conversational platform. Businesses are at the commiseration of every single conversational platform on how they're transactions are getting triggered on the conversational space.  It is not aligned to the principles we outlined in OVN of open-standard: due process, broad consensus, transparency, balance, and openness.


![](component_assets/vrs_problem_statement.png?raw=true "Fig. 1 - VRS Problem Statement")

In the diagram above, the use-case scenario is Patrick's Dessert Kingdom is a business that needs to be multiple conversational platforms such as Amazon, Google, etc. The company is most popularly known for its name as "Patrick's Dessert Kingdom."  The business wants the explicit command for their customer to what they are known for.  Fortunately, it is approved and available in Amazon and Microsoft but not on other conversational platforms.

### Voice Registry System
The core solution approach to the problem is to stand up a neutral component that is not tightly associated with any of the conversational platforms to avoid any influence and bias. The VRS component will serve as the neutral party and address the balance and fairness for the user and businesses. 

The primary role and responsibility of the VRS are to resolve the explicit invocation received by the conversational platforms. The resolution will include taking into account the location of the origin of the place of the utterance. The VRS will store the business's preferred configuration that can be applied to all various conversation platforms.

### Architecture Options
Like any other problem, there are multiple ways to get to the ideal solution. The purpose of this is to look at options and ratify with the committee the best path forward.


#### Option 1

![](component_assets/vrs_proposed_solution_1.png?raw=true "Fig. 2 - VRS Proposed Solution 1")


#### Option 2

![](component_assets/vrs_proposed_solution_2.png?raw=true "Fig. 2 - VRS Proposed Solution 2")


#### Pros and Cons
| Options  | Pros                                                                                                           | Cons                                                                                                             |
|----------|----------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------|
| Option 1 | - VRS does not have to implement NLU capability.                                                               | - Identifying vrs type is implemented in the proprietary conversational platform, which can cause inconsistency. |
| Option 2 | - Identifying vrs type is implemented in one area and consistent across the different conversational platform. | - VRS has to implement NLU capability.                                                                           |