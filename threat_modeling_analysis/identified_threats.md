# Identified Threats in Voice Systems

Using the [STRIDE framework](https://en.wikipedia.org/wiki/STRIDE_(security)), the following are identified threats. This is intenteded to be a living document. As more use-cases are discussed, this document should be updated to catalog the threats.

## Assumptions
  * The focus of this exercise was to identify threats specific to Voice Networks.  As such, threats that would be common to any other application will not be studdied (for example: the threat of information disclosure of REST API calls over HTTP connections is not specific to Voice Networks, and as such will not be called out)

 ## Definitions
 
  * Vulnerability: A flaw or weakness in a system's design, implementation, or operation
  * Theat: A possible danger that might exploit a vulnerability

## STRIDE

| Category                   | Definition |
| -------------------------- | ---------- |
| **S**poofing               | Pretending to be someone you are not |
| **T**ampering              | Modifying data |
| **R**epudiation            | I didn’t do it, no one saw me do it, you can’t prove it |
| **I**nformation Disclosure | Leakage of information that should be private |
| **D**enial of Service      | Stopping something from working or responding |
| **E**levation of Privllege | Upgrading from user to admin |

## Entities

Systems:
 * Home Voice Assistant - An in-home voice assistant, such as Google Home, Alexa, etc. 
 * Smartphone Voice Assistant - A voice assistant that is apart of a Smart Phone device, such as Siri, Google Assistant, Bixby, etc.
 * In-Vehicle Voice Assistant - An in-vehicle voice assistant, such as those found in Ford, Chevy, etc.  May be additionally connected to 3rd party voice assistants.

Individuals: 

_Note: Names are taken from [fictional charaters](https://en.wikipedia.org/wiki/Alice_and_Bob) commonly used when talking about security and cryptography._

 * Alice - the standard user of the voice system.  In systems where authoriziation is required, Alice is the authoried primary user
 * Bob - a secondary user of the voice sytem.  In systems where authorization is required, Bob is an authorized secondary user
 * Chuck - a secondary user of the voice system. In systems where authorization is required, Chuck has limited authorization
 * Eve - an unauthorized participant 
 * Oscar - an outside individual, not intentioanlly trying to interact with the system.

## Threats

| # | Threat | Assumptions | Category |
|---|---|---|---|
| 1 | Eve records Alice interacting with the Home Voice Assistant where Alice orders mayonnaise for delivery.  Eve then replays the interaction later to cause Alice to pay for a large amount of unexpected mayonnaise. | Alice has already configured the Home Voice Assistant to allow ordering, complete with payment and shipping information. | [S](#stride "Spoofing"), [R](#stride "Repudiation") |
|  | Alice is in her car with an In-Vehicle Voice Assistant, stopped in a parking lot with the windows down.  Oscar is in a car next to Alice, and speaks in a way that Alice's voice assistant can hear.  Oscar says "Next Song", then Alice's car begins playing "Piilotan mun kyyneleet"	by Haloo Helsinki, interupting the podcast she was listening to. | | [R](#stride "Repudiation") |


