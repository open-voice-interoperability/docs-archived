# Proposed Activities

The following is an initial list of possible OVN activities, organized along Jon&#39;s five big areas of activity:

## Evaluation

Per the Technical Committee meeting of 2020.06.12, evaluators will identify each activity area as either **Foundational** or **Exploratory**.  

**Foundational** are those activities deemed to be central to achieving the North Star vision of The Open Voice Network, and may be _horizontal_, or of value to multiple industries and constituents.   **Exploratory** are those activities for which development is dependent upon the achievement of foundational activities, or which may be aligned to one or few _vertical_ industries or constituencies.

To evaluate, please list your Git handle and your term of evaluation after every activity.   Example:  jonstine:foundational.  If you wish to add a phrase of explanation, please do so. 

If no opinion, please list your Git handle only, like this:  jonstine:

## Destination Registry

### Approaches for Voice Registry

Proposed by Jim Larson

Motivation: Need to determine the best approach for developing a voice registry of wakeup words / invocation words

Description: Analyze the pros and cons of alternative architectures for developing a Voice Registry including leveraging DNS, the standalone CUvoice registry, and others. The end result may be a decision to build and test a voice registry.

jonstine:foundational
Maarten Lens-FitzGerald: foundational 


## Voice Commerce Core Processes

### Pay by voice

Submitted by Lawrene Lin &amp; Jim Larson

Motivation: Accelerating people&#39;s purchasing process through of voice payment through user&#39;s voice print and biometrics.

Description: Specify the vocabulary for a frequently-used business activity by constructing and deploying a skill (printing a portion of a conversation) An example approach is outlined in Telephone Commands in five languages, Final draft ETSI ES 202 076 V2.1.1 (2009-06) ETSI Standard Human Factors (HF); User Interfaces; Generic spoken command vocabulary for ICT devices and services https://www.etsi.org/deliver/etsi\_es/202000\_202099/202076/02.01.01\_50/es\_202076v020101m.pdf . This activity may result in example code implementing pay-by-voice and recommendations for additional studies of use-case patterns for frequently-used business activities. Should align with GDPR and CCPA.

jonstine:exploratory. May be phase next due to dependencies. 
Maarten Lens-FitzGerald: exploratory due to category focus


## Identification and Authentication

See 2.1 pay by voice

jonstine:exploratory.  May be phase next due to dependencies. 

## Data Privacy

### Evaluate OVAL (Open Virtual Assistant Lab) Approach to Privacy

Proposed by: Jim Larson

Motivation: Need to specify a data privacy policy and enforcement mechanism

Description: Need to specify a data privacy policy for speech applications. Evaluate Almond approach to privacy and determine it if is useful in our work. Reference: ALMOND, THE OPEN, PRIVACY-PRESERVING VIRTUAL ASSISTANT https://oval.cs.stanford.edu/

jonstine: foundational.  
Maarten Lens-FitzGerald: foundational


### Security Guidelines

Submitted by Nick Myers

Motivation: privacy is a growing concern among users and needs to be a core focus of our work moving forward.

Description: create report and reference framework describing basic set of privacy/security guidelines, recommendations, and standards, including identification and authentication of users, and transport of secure information among components of voice applications.

jonstine: exploratory.  A valuable phases-next deliverable.  
Maarten Lens-FitzGerald: foundational, if not secure then no function

### Privacy and Data Protection

Submitted by Peter Bentsen

Motivation: Privacy and Data Protection should be foundational and pervasive in all parallel OVN efforts towards standardization and will likely become a regulatory requirement and enforced in the intermediate term for this space as well (GDPR, HIPAA/HITECH/HITRUST, etc).[Cybersecurity]

Description: Identify privacy use cases including doctor-patient discussions, voice payment, and voice in research.

jonstine: foundational.  
Maarten Lens-FitzGerald: what is teh diferende with data privacy

## Interoperability

### Vendor Independent language API for writing speech applications

Proposed by Jim Larson

Motivation: Developers waste time and effort developing applications multiple times for different voice platforms.

Description: Identify differences in functions and features supported by various voice platforms. Determine how to handle functions available on some platforms and missing on other platforms. Evaluate Jovo for solving these problems.

jonstine: 
Maarten Lens-FitzGerald: foundational, project needs to move up the "value chain" to assitant level as we will live in a multi asistent and app model may be temporary, or we need to find an aproach to fit both.  

### SSML Markdown Language

Proposed by Mark Tucker

Motivation: SSML is complex and requires linguistic expertise to use effectively. Speech application platforms do not support SSML consistently http://ssml.guru/

Description: Specify text-to-speech formatting notation for content authors, designers, and developers. Converts to SSML while handling inconsistencies across Amazon Alexa &amp; Google Assistant. https://www.speechmarkdown.org/

jonstine: 
Maarten Lens-FitzGerald: not exploratory as it is in production already, a key community initiative

### Interactive aids for editing pronunciations

Suggested by Maaike Groenewege

Motivation: It is difficult for non-linguists to specify pronunciations with IPA because some of the representations are non-printable and non-linguists have difficulty in choosing the correct pronunciation.

Description: Develop interactive editor (with verbal feedback) to help non-linguists select appropriate pronunciation of words and specify appropriate prosody of phrases.

jonstine: 
Maarten Lens-FitzGerald: exploratory

### Matching human resources with development tools and processes

Suggested by Maaike Groenewege and Hans Van Dam

Motivation: Improve voice application development efficiency

Description: Describe developer background, skills and their roles in the workflow of developing voice applications.

jonstine:exploratory.
Maarten Lens-FitzGerald: exploratory

## Other

### Next generation Voice app platform

Submitted by Jim Larson

Motivation: Make new functions and features available to users via enhanced platform (that is also vendor-independent).

Description: extend the design work by Dan and Maria in their &quot;master plan&quot; to include multimodel functionality, emotion detection and generation, personality detection, and other new and useful features and functionality. This could be step 1 of developing next gen voice app platform

jonstine:foundational, but should be parsed into separate activities. 
Maarten Lens-FitzGerald: foundational, see interoperatbility remark.. its not about the voice app possibily

### National Voice Commons and NLU

Submitted by: Maarten Lens-FitzGerald

Motivation: The voices and NLU provided by Google and Amazon platforms are subpar outside of the US market.

Description: Enable countries to create their own national voice(s), ASR, &amp; NLU, ensuring quality is in their control and to limit dependency on major platforms. This may involve collecting voice data, local linguistic models, and development tools, and identify missing pieces. Work with organizations that create them.

jonstine:foundational.  Essential to inclusivity aspiration?
Maarten Lens-FitzGerald: foundational, Vocie platform as a public servcie there for inclusive

### Enhanced/Augmented Audio (Audio Input/Voice Analysis)

Submitted by Peter Bentsen

Motivation?: Specify audio solution requirements (HW, DSP, ASR/STT, AI, VRS, Wake Word, DB, etc.) to a level allowing for remote sensing, voice analysis and user/patient diagnostics, as well as interoperability and interfacing with relevant entities via VRS.

Description: TDB

jonstine:foundational.
Maarten Lens-FitzGerald: foundational , title maty need more clarification

### A reference handbook for the Voice/Conversational AI industry

Submitted by Nick Myers

Motivation: information regarding Voice and Conversational AI is disjointed and exists in multiple locations published by various sources

Description: handbook that can act as a single source of industry specific information for new practitioners, business leaders, the general public, etc. coming from a neutral body like OVN

jonstine:exploratory.
Maarten Lens-FitzGerald: exploratory

### User research

Submitted by Nick Myers

Motivation: a majority of the research that has been conducted focuses on how people are currently using their voice assistants vs. how they want to use their voice assistants

Description: Use ethnographic techniques to postulate future uses of voice. Collect voice data and statistics.

jonstine:exploratory.
Maarten Lens-FitzGerald: exploratory

### Build a canonical voice application on an open source platform, like Almond

Submitted by John Iwasz

Motivation: Provide a concrete example of the abstract vocabulary terms. It would be a skeleton upon which hangs a wake word, queries, etc. Express implementations of security and other horizontal concerns. Provides a canonical example for developers.

Description: build a canonical voice application on an open source platform, like Almond.

jonstine:foundational in re: development process. 
Maarten Lens-FitzGerald: foundational

