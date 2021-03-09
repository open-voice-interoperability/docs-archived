# Open Voice Network Technical Docs

This repository contains the published and work in progress artifacts, docs, schemas, technical committee working group meeting minutes, etc of the OVN. 

## Git folder structure

- **root** - contains OVN information that is more horizontal approach such as technical master plan, security, privacy, architecture, etc.
  - **components** - contains OVN identified invidual components such as VRS 
    - **component_assets** - contains images used in the component document
    - **api_docs** - contains component level swagger
  - **technical_masterplan_assets** - contains images used in the `technical_masterplan.d` document

## Install
-   To record important architecture decision, we use  [adr-tools](https://github.com/npryce/adr-tools "https://github.com/npryce/adr-tools"). To install, type the following in the terminal command. 

    >    ``` brew install adr-tools ```

- To view the diagrams, please install the [github-mermaid](https://chrome.google.com/webstore/detail/github-%2B-mermaid/goiiopgdnkogdbjmncgedmgpoajilohe) chrome extension.
- To learn more about mermaid, click [here](https://github.com/mermaid-js/mermaid).


## OVN way of working
If you are interested to see our working style, see this [link](https://github.com/open-voice-network/docs/blob/master/way_of_working.md).

## Do you want to contribute?
- Depending on your comfort and permission, there are multiple ways you may find yourself contributing via:
  - **Fork + PR** -- this approach is only needed if you don't have write access directly to the repo. See this for help: https://guides.github.com/activities/forking/
  - **Branch + PR** - this approach is used if you already have write access to the repo. See this for help: https://guides.github.com/introduction/flow/

- New to Git and not comfortable doing things in the commandline? If you prefer to work with a GUI, GitHub does allow you to do either approaches above all within the UI.
- Whatever steps you followed above, you will end in a Pull Request, also known as PR. This is required for all changes to this repo. Do not commit directly to the `master` branch.
- In the PR process, you will not see your changes right away. It is an area of discussion where the reviewer can ask for more questions or clarification about the changes you made. It is **best practice**, but not required to add/refer-to the issue number in the PR comments so it is easier to understand the context and background for why the PR is being made. 

Still unsure what to do? Ask in the #general channel in the OVN Slack and someone can help you.
