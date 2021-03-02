# 1. Voice Registry System

### 1.0.1. Overview
Voice Registry System (VRS) is one of the components  in the
[Technical Masterplan](https://github.com/open-voice-network/docs/blob/master/technical_masterplan.md). This document aims to address the current problem of the existing voice architecture landscape.

VRS's goal is to provide and promote voice openness and transparency. 

### 1.0.2. Terminology Alignment
See [OVN vocabularies](https://github.com/open-voice-network/docs/blob/master/vocabulary.md)

### 1.0.3. Problem Context
Today, voice assistance is dominated by proprietary, cloud-centric conversation platforms that deliver services using closed implementations.  Examples of these are Amazon Alexa, Google Assistant, Microsoft Cortana, and Apple Siri.  Every user invocation is received and managed by the hosting platform, which in turn will direct the user to one or more platform-specific assistance skills/actions/capsules.  Whenever an "explicit invocation" is invoked by the user -- that is, the user requests a specific destination -- each proprietary platform has a different method  (i.e., brand vocabulary, etc) and process for verification and connection to the user's desired entity.  

In addition, the world of voice assistance is also in the midst of a major market transition.  In the near future, the role of cloud-centric platforms and third party entities will change, as third-party entities (especially enterprises) increasingly develop their own independent voice assistants.   This will -- at first, slowly, then rapidly --  push the industry from the current skills-on-platform model (similar to that of world of mobile apps) to what might be described as an internet model, where independent voice assistants (like web sites) connect interoperably across platforms and services providers.

Both the present and future situations are problematic for entities that wish to connect to their customers, patients, clients, and suppliers through voice assistance.


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
<br>
In this architecture, we follow the Single Responsibility Principle(SRP), whereas the Conversational Platform or Voice Assistant will remain responsible for identifying the user's intent for their utterance. For initial phase,  Also, the translation of the user's utterance from audio to text is outside of VRS; therefore, the expected query input is a string datatype.
<br>
<br>
There are a couple of assumptions in the initial phase. CP's accountability extends to the decision-making of classifying, whether an invocation is implicit or explicit. 
<br>
<br>
The VRS core responsibility is to be a standard and platform-agnostic location for voice application. 
<br>
<br>
By following the SRP, we achieve the following: <br>
 - Reduce the dependency of VRS on other voice components. <br>
 - Decrease the extra hop that can create additional latency in the voice flow.<br>
 - Remove the unnecessary complexity for VRS. <br>

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
//todo: #85
#### 1.0.6.2 Who is the decision maker whether user's utterance is explicit or implicit invocation?
//todo: #86

### 1.0.7. Discussions
 1. Do we need central location for common words?
 2. Who is the decision maker whether user's utterance is explicit or implicit invocation?
 3. Is VRS only going to focus on explicit invocation?
 <br>-Similar to the web where if a user typed www.patrickdessert.com directly and the DNS resolver gets involve. This feels like a reasonable balance in for entities, and conversational platform. </The>
 
