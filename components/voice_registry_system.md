# 1. Voice Registry System

### 1.0.1. Overview
Voice Registry System (VRS) is one of the components  in the
[Technical Masterplan](https://github.com/open-voice-network/docs/blob/master/technical_masterplan.md). This document aims to address the current problem of the existing voice architecture landscape.

VRS's goal is to provide and promote voice openness and transparency. 

### 1.0.2. Terminology Alignment
See [OVN vocabularies](https://github.com/open-voice-network/docs/blob/master/vocabulary.md)

### 1.0.3. Problem Context
The task of the Open Voice Network Voice Registry System (VRS) Work Group is to develop standards-based solutions for how _verbalized, explicitly-requested conversational agent destinations_ will,by another conversational agent, **be uniquely identified and connected.**

This issue anticipates the continued growth of voice assistant systems that are independent of major platform technologies, and the emergence of a hybrid voice assistant ecosystem consisting of both general-purpose platform-based conversational agents and independent systems, most often managed and operated by enterprises. 

The VRS will provide value to voice assistant system providers and operators, and to consumers. It will provide

- a global, decentralized, standard place for an organization or brand to register their conversational agent(s) and the associated names for them;
- a global, standardized service that will confirm is a verbalized term or name is registered by a specific conversational agent; 
- a global service that will provide a standard set of technologies and processes that will allow term or name confirmation regardless across all voice assistant systems
- a global, standardized aid in disambiguation if and when there are multiple conversational agents associated with a registered name or term. 

Broadly, this is about the ability of individual users to **find** a conversational agent of choice, and the ability of providers of conversational agents **to be found.**

For these reasons,  propose the development of a decentralized, standardized global destination registry for conversational agents and related voice assistant systems: **the Voice Registry System.**


### 1.0.3.1 Situation Analysis: Today's Voice Ecosystem

Today, voice assistance is dominated by proprietary, cloud-centric conversation platforms that deliver services using closed implementations.  Examples of these are Amazon Alexa, Google Assistant, Microsoft Cortana, and Apple Siri.  Every user invocation is received and managed by the hosting platform, which in turn will direct the user to one or more platform-specific assistance skills/actions/capsules.  Whenever an "explicit invocation" is invoked by the user -- that is, the user requests a specific destination -- each proprietary platform has a different method  (i.e., brand vocabulary, etc) and process for verification and connection to the user's desired entity.  


Below are the **problems** identified in the current landscape.
<br>
<details><summary>1. The entity will not have a consistent experience across conversational platforms.</summary>
<br>
The below diagram depicts a use-case scenario where Patrick's Dessert Kingdom is an entity that needs to be in multiple conversational platforms such as Amazon, Google, etc. The company is most popularly known for its name as "Patrick's Dessert Kingdom."  The entity wants the explicit command for their customer to what they are known for.  Fortunately, it is approved and available in Amazon and Microsoft but not on other conversational platforms. This is a problem for the entity and user. Users and entities will not have consistent experiences in dealing with the various conversational platform.

> ![](component_assets/vrs_problem_statement_1.png?raw=true "Fig. 1 - VRS Problem Statement 1")

</details>
<details><summary>2. Disambiguation of entities location.</summary>
<br>
The second illustration shows a scenario where there are similar entities but on a different location. Today, each conversational platform handles this scenario differently and without transparency.

> ![](component_assets/vrs_problem_statement_2.png?raw=true "Fig. 2 - VRS Problem Statement 2")

</details>
<details><summary>3. Disambiguation of entities - homophone.</summary>
<br>
Part of the complexity of voice is the homophone disambiguation. When the user utters an invocation, and there can be multiple possibilities for the invocation. 
<br>
An example: <br>
A user utters, "{wake work}, I want to talk to Cisco." Multiple entities can sound like Cisco, such as Sysco Food or Cisco Networking.
<br>
A couple of problems in this scenario: <br>
 - (1) who decides for the right interpretation <br>
 - (2) there is no central location of all the invocation homophone relationship
<br>
</details>
<details><summary>4. Disambiguation of entities - homograph.</summary>
<br>
 Part of the complexity of voice is the homograph disambiguation. When the user utters an invocation, and there can be multiple possibilities for the invocation. 
<br>
An example: <br>
A user utters, "{wake word}, I want to talk to Delta." Multiple entities can be associated with Delta such as Delta Dental, Delta Airlines, Delta Network.
<br>
A couple of problems in this scenario: <br>
 - (1) who decides for the right interpretation <br> 
 - (2) there is no central location of all the invocation homograph relationship
<br>

</details>
<details><summary>5. Lack of central location for invocation availability.</summary>
<br>
> Due to the walled garden conversational platform landscape today, users or technical resources do not have a single area to go to check for the availability of the invocation. They have to go through each of the conversational platforms to verify the availability of the invocation. 

</details>

<details><summary>6. Correction of mispronounciations.</summary>
<br>
> The user's utterance of a word does not exist in the list of valid pronunciations. For example, the user utters "pitco" which does not match "ditco" or "botcp" or any other articulation is the list of valid pronunciations.

</details>

</details>
<details><summary>7. Indirect invocation of voice application.</summary>
<br>
Due to natural language nature, a user will invoke a voice application based on the known slang or just based on the user's direct preference.
<br>
An example: <br>
A user utters, "{wake word}, Please find nearest Tarrjay location." A user prefers to call Target a retail store as "Tarrjaay."
<br>

</details>

<details><summary>8. No consistent guidelines for invocation.</summary>
<br>
> Due to missing global standards, developers need to adhere to different conversational platforms guidelines. This results in complexity, heavy maintenance, and support for their voice application.

</details>
<br>
<br>

### 1.0.3.2  Situation Analysis: Tomorrow's Voice Ecosystem

Voice industry analysts currently see (mid-year 2021) and predict the emergence of a "hybrid" conversational agent (or voice application) ecosystem, one made up of general purpose conversational platforms (with agents) and organization-owned and -operated conversational agents built independently or with third-party tools.  This market transition is being accelerated by the growing enterprise perception of voice assistance as a means to customer service, customer development, and operational efficiencies; the emergence is also spurred by the growth in capabilities of third-party independent voice developers.

As enterprises perceive voice as a business of value, three issues come to the forefront:

  1. the ability of an owner of a conversational destination to own the name of that destination;
  2. the ability of an individual voice user to find and connect directly to a voice destination of choice, regardless of its platform; and,
  3. the ability of a conversational agent destination (most often an organization) to own and control the development
     and delivery of its voice experience.
   
A Voice Registry System -- a destination registry that enables platform-agnostic connection -- is intended to enable all three needs.

Within tomorrow's voice ecosystem there will be three primary actors connected to and affected by a Voice Registry System:

  1. the individual user, who seeks direct, unimpeded access to a destination of choice;
  2. the original conversational agent of the user, which would use the Voice Registry System to identify
     possible destinations and connect to a destination of choice, and
  3. the owners of the destination conversational agent, who will use the Voice Registry System to uniquely
     own its name or brand and to own and execute a unique, destination-specific voice experience. 


### 1.0.4. Voice Registry System
The core solution approach to the problem is to stand up a neutral component that is not tightly associated with any of the conversational platforms to avoid any influence and bias. The VRS component will serve as the neutral party and address the balance and fairness for the user and entities. 

#### 1.0.4.1 Roles and Responsibilities
The primary role and responsibilities of the VRS are the following:
 1. Be a standard and platform-agnostic location for voice application.
 2. Provide a consistent experience across conversational platforms and entity's conversational assistant.
 3. VRS is not responsible for the interpretation of the intent of the user.
 4. VRS can hold various attributes regarding the voice application, such as name, nlu etc.
 5. VRS can receive inputs like the user's current location but is not responsible for storing its preference. 
 6. VRS names can have synergies.

#### 1.0.4.2 Architecture Principles
As we continue to build the capability and solution of VRS, we are going to be guided by these principles.
- Single Responsibility
- Loose Coupling
- Event-Driven
- Availability and Partitioning of Network
- Eventual Consistency
- Interface segregation
- Automation (CICD, DevOps, Containerization, Service Mesh, Observability, etc.)

#### 1.0.4.3 Architecture

![](component_assets/vrs_proposed_architecture_setup.png?raw=true "Fig. 1 - Proposed Architecture - Setup")
![](component_assets/vrs_proposed_architecture_runtime.png?raw=true "Fig. 2 - Proposed Architecture - Runtime")

In this architecture, we follow the Single Responsibility Principle (SRP), in that the Voice Assistant Platform
will remain responsible for:

1. identifying the user's intent for their utterance
2. classifying the VRS type in an utterance
 
See [AD-0002](../architecture/decisions/0002-vrs-type.md).

There are a couple of assumptions in the initial phase. The accountablity of the Conversation Platform (CP) extends to
the decision-making of classifying whether an invocation is _implicit_ or _explicit_. 

The VRS core responsibility is to be a standard and platform-agnostic location for voice application. 

By following the SRP, we achieve the following:

- Reduced dependency of VRS on other voice components.
- Decrease the extra hop that can create additional latency in the voice flow.
- Reduce complexity for VRS.

**Known Risk:**
- Dependency on Conversational Platform's NLU integration.

#### 1.0.4.4 VRS Requirements
 1. Registry for voice application regardless of Conversational Platform. 
 2. To promote the OVN principle, VRS will support to run locally and globally at scale.
 3. VRS will store and identify attributes for voice application.
 4. VRS will provide search functionality for voice application.
 5. VRS will provide data administrations.

<br>
//todo: #88 Note: get more requirements from developers group.
<br>
<br>


### 1.0.5. Proposed Schema
***Note:*** The swagger is something what it can look like but by no means vetted out<br>


```
  "voice_application": {
        "type": "object",
        "description": "Voice Application object",
        "properties": {
          "voice_application_id": {
            "type": "string",
            "description": "Unique identifier for the voice application",
            "format": "url",
            "example": "www.voice_app_name.com"
          },
          "name": {
            "type": "string",
            "description": "Invocation name for the voice application",
            "example": "patrick dessert"
          },
          "alternative_names": {
            "type": "array",
            "description": "Alternative names or slang name for the voice application",
            "items": {
              "type": "string",
              "example": "patrick d"
            }
          },
          "registered_date": {
            "type": "string",
            "description": "Voice application registration date",
            "format": "date-time"
          },
          "expiration_date": {
            "type": "string",
            "description": "Voice application expiration date",
            "format": "date-time"
          },
          "status": {
            "type": "string",
            "description": "voice application validity status",
            "enum": [
              "registered",
              "pending",
              "cancelled",
              "expired"
            ]
          },
          "search_location": {
            "type": "integer",
            "description": "Default settings if search includes location. It means this voice application will show up within 20 miles.",
            "format": "int32",
            "example": 20
          },
          "locations": {
            "type": "array",
            "description": "voice application various location",
            "items": {
              "$ref": "#/components/schemas/voice_application_location"
            }
          },
          "categories": {
            "type": "array",
            "description": "List of voice application categories.",
            "items": {
              "$ref": "#/components/schemas/category"
            }
          },
          "conversation_platforms": {
            "type": "array",
            "items": {
              "$ref": "#/components/schemas/conversation_platform"
            }
          }
        }
      }
```

[See voice-registry-system-v1 swagger.](https://github.com/open-voice-network/docs/blob/master/components/api_docs/voice-registry-system-v1.json)


### 1.0.6. Architecture Decision

#### 1.0.6.1 Do we need central location for common words?

[TO DO; see issue #85](https://github.com/open-voice-network/docs/issues/85)

#### 1.0.6.2 Who is the decision maker whether user's utterance is explicit or implicit invocation?
The voice assistant system will decide if a user's utterance is explicit or implicit. For the initial release, VRS will only handle explicit invocations and the voice assistant system will handle and disambiguate implicit invocations.

Note: The name of a voice application is different than the wake word. A wake word is the user's word(s) used to get a voice assistant to start listening. For instance, "Alexa", "Hey Google" and "Hi Bixby" are wake words. If a user says:
``` Alexa, ask Target to add milk to my shopping list ``` then  
``` Alexa``` is the wake word and ```Target``` is the name of the voice application

**Explicit Invocation Definition:** An invocation of a voice application where the name of the application is part of the invocation utterance. For example (omitting the wake word):
- ```Ask Target, to add milk to my shopping list```  
- ```Open Target```  
- ```Talk to Target```  
- ```Ask Target, what’s on sale```  
- ```Add milk to my Target shopping list```  

In each of the above utterances, the user has explicitly identified ```Target``` as the name of the voice application they wish to use.

There will be instances where there is more than one voice application with the same name. For example:
- ```Ask John's Bakery, when do you open```
  
There may be more than one voice application named *John's Bakery*. Indeed, there may be many different *John's Bakery* voice applications. If a user's explicit invocation results in multiple VRS matches, VRS will return all of the matching records. Included in the records will be the address and other metadata about the voice applications. The voice assistant will then use this information and other user information to disambiguate. Possible ways to disambiguate the above example include:
- Using the address to find the nearest *John's Bakery*
- Using the last launched *John's Bakery* application
- Asking the user which *John's Bakery* to use (and likely store this in user preferences for future use)
- Some other AI based algorithm to find the best option for the user

**Implicit Invocation Definition:** An invocation of a voice application where the utterance has a meaning (action, question, etc) but the name of the voice application is not in the utterance. For example:
- ```Add milk to my shopping list``` *(which shopping list?)*
- ```What’s on sale this week``` *(where?)*
- ```Get me a car to the airport``` *(using which provider?)*
- ```What’s the weather``` *(using which provider?)*  

In these implicit examples, there is an ambiguity as to which voice application should be used to satisfy the request. The voice assistant system must resolve this ambiguity by either:
1. Using an algorithm to determine the best voice application for the user
2. Look up a user’s preference for that particular utterance/group of utterances and their preferred voice application
3. Ask the user which voice application to use

As mentioned above, in the initial phase, VRS would not be involved in the implicit disambiguation - this would be up to the voice assistant system. The system may use VRS data in this decision process but the scope of VRS does not include resolving implicit utterances.

A future version of VRS may add additional functionality to include or futher aid implicit utterance resolution.

### 1.0.7. Discussions
 1. Do we need central location for common words?
 2. Who is the decision maker whether user's utterance is explicit or implicit invocation?
 3. Is VRS only going to focus on explicit invocation?
 <br>-Similar to the web where if a user typed www.patrickdessert.com directly and the DNS resolver gets involve. This feels like a reasonable balance in for entities, and conversational platform. </The>
 
{"mode":"full","isActive":false}
