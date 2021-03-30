Using the [STRIDE framework](https://en.wikipedia.org/wiki/STRIDE_(security)), the following are identified threats.

## Assumptions
  * The focus of this exercise was to identify threats specific to Voice Networks.  As such, threats that would be common to any other application will not be studdied (for example: the threat of information disclosure of REST API calls over HTTP connections is not specific to Voice Networks, and as such will not be called out)


## STRIDE Matrix

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

| # | Threat | Assumptions | Category |
|---|---|---|---|
| 1 | Eve records Alice interacting with the Home Voice Assistant where Alice orders mayonnaise for delivery.  Eve then replays the interaction later to cause Alice to pay for a large amount of unexpected mayonnaise. | Alice has already configured the Home Voice Assistant to allow ordering, complete with payment and shipping information. | S, R |
|  | 
