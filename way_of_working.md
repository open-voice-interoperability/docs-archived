# Overview

This document describes the norms and processes through which the Open Voice Network will pursue its objectives. 

# Meeting processes

- Meetings will start on time and end on time. Meetings of Open Voice Network (OVON) standing committees and technical project committees will begin and conclude promptly at the times scheduled. If it is deemed important by the committee chair and/or meeting moderator to continue a conversation beyond the scheduled adjournment time, the chair or moderator will pause the meeting at the scheduled adjournment time, and invite participants to continue.  _No decision will be taken by a committee outside the scheduled meeting window_. 
- Meetings will operate under the antitrust guidelines of The Linux Foundation, found here: https://www.linuxfoundation.org/antitrust-policy/. A statement to this effect, along with a slide that shows the URL of the Linux Foundation antitrust guidelines, will be shown at the beginning of every Open Voice Network standing and technical project committee meetings.
- Meeting agendas will be distributed to meeting participants no less than 48 hours in advance through the communication channel (generally Slack or e-mail) deemed most effective by the Committee, Work Group, or Community moderator. Meeting agendas for the OVON Technical Committee will be posted in the OVON GitHub Docs Repo no than 48 hours in advance of the meeting.   
- Meetings will foster accountability and follow-up. The review of relevant and outstanding issues will be a stated agenda item early on the agenda of every Open Voice Network Technical Committee, Work Group, and Community meeting.  The Technical Committee and Technical Committee Work Groups will use GitHub (see below) or an approved tool such as Trello to document issues for resolution.  Outstanding issues will be reviewed in every meeting.
- Meetings will be recorded, and notes will be taken. All scheduled meetings of the Technical Committee, Technical Committee Work Groups, and Open Voice Network Communities  will be recorded, using the recording technology of the web conferencing platform in use. Full audio-visual meeting recordings will be stored in the Open Voice Network Google Workspace, within a folder titled specifically for that Committee, Work Group, or Community.  An announcement of “this meeting is being recorded” will be made at the beginning of every meeting. Notes will be taken of all Technical Committee meetings, published within 48 hours in the OVN GitHub docs file.

# Working tools

- The Open Voice Network uses the following document management, communication, and collaboration tools:
- A **GitHub repository** for technical document management and review, at https://github.com/orgs/open-voice-network.  The Open Voice Network GitHub repository is the OVON's source of organizational truth for three key constituencies: 1) Linux Foundation leadership, 2) Open Voice Network sponsors and Steering Committee members, 3) Prospective sponsors and technical participants.  Final strategic documents, Technical Committee deliverables and milestones, and all technical development will be posted or published in GitHub. 
    * It is recommended that final versions of _strategic documents_ (white papers, position papers) be posted as pdf files within relevant folders.
    * Is it expected that 
        - Technical Committee deliverables and milestones be managed and reviewed through the OVON GitHub Repository.
        - technical development (code, proposed protocols, etc.) will be posted/managed/reviewed within and through the OVON GitHub Repository.  
- **Slack** for instant messaging and quick issue resolution.  Participants will be added to the OVN Slack channels upon invitation to the OVON Technical Committee or Technical Committee Work Group, or one of the OVON Communities. To request participation in the OVON Slack Channels, please e-mail the OVON Executive Director (jon.stine@openvoicenetwork.org.) 
- A **Google Workspace** for 
   - the collaborative development of strategic documents, should the Committee/Work Group/Community Moderator determine that the Google Workspace will provide the most effective and efficient way to enable participation and drive delivery;
   - the storage of meeting recordings and non-technical meeting artifacts and notes; 
   - meeting scheduling and participant management through the Open Voice Network Google Workspace calendar (https://calendar.google.com/calendar/u/0/r?tab=cc).  Through this, Committee, Work Group, and Community Moderators will have full access to add or subtract particpants to regularly scheduled meetings. 
- **Zoom** for the hosting of Open Voice Network video-audio conference calls and webinars.  

# OVON Document Development and Management

- **Open Voice Network collaborative document development**  may be pursued in either the OVON GitHub docs repository or the OVON Google Workspace.  The choice will be managed by the Moderator of the OVON Committee, Work Group, or Community.  
- **Version Control in Google Workspace.**  The Moderator of the OVON Committee, Work Group, or Community is responsible for managing version control for documents developed in the OVON Google Workspace.  All Google Workspace documents are to be version identified and dated; in addition, the version identification must also state "replaces version X.0".  Authors and contributors must be named. 
- **Public-facing documents** (whether for distribution or review) are to be posted in GitHub (in .md or pdf or a standard document format).  For those documents seeking broad public distribution, it is strongly recommended that a pdf of the document be posted on the Open Voice Network website, www.openvoicenetwork.org. 
- Technical Committee and Technical Committee Work Group code and proposed protocols (from 0.1 to final) must be published and managed in the OVON GitHub repository. 

# Task, Milestone, and Deliverable Management

- **Day-to-Day Tasks within Work Groups, Communities, or Task Forces.**  Day-to-day tasks (task, responsibility, accountability, deadline) for Technical Committee Work Groups, Communities, and Task Forces are to be documented and reviewed at the beginning of each meeting.  These may be managed in the OVON GitHub Repo, Trello, or a team-or moderator-preferred tool.  
- **Annual, Bi-Annual, and Quarterly Deliverables and Milestones.**  Each Technical Committee Work Group will establish in the OVON GitHub repo its annual, bi-annual, and quarterly deliverables and milestones.  These will reside within the _Technical Committee Project._  This will enable one view of performance, visible to OVON leaders, staff, Steering Committee members and sponsors, and LF managers.

# OVON Technical Committee Work Groups 

Working groups are the teams that execute work against the activities.  When a working group exists, they accountable for issue documentation, backlog management, and document development into the OVN GitHub repository.  Working Groups will also form and define their own leads/leadership. 

Technical Committee Work Groups formed:  
* **Architecture Work Group**  
  * formed in 6/26/20 Technical Committee meeting 
* **Privacy & Security Work Group** 
  * formed in 6/26/20 Technical Committee meeting 
* **Voice Registry System (VRS) Work Group**
  
# Work Group Decision-Making

Open Voice Network Technical Committee Work Groups are formed by the Technical Committee to research and recommend a solution or way forward on a topic determined to be of importance to the OVN's mission.  Recommendations are to be brought back to the Technical Committee, which may forward the recommendation to the OVN Steering Committee for endorsement and/or the allocation of resources.

Work Groups are

- Moderated by one or more regular participants in the Work Group
- expected to conduct business in a manner that is open, professional, and in keeping with the OVN Communities Code of Conduct found at www.openvoicenetwork.org
- expected to seek a diversity of views, and to welcome minority viewpoints and robust discussion
- asked to seek consensus decisions (and if a consensus cannot be reached, to achieve a decision by at least a two-thirds majority)
- expected to begin and close meetings with a review of outstanding and new issues, respectively

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

## Creating Key Architecture Decision
- To support an inclusive ratification of ideas, we use architecture decision tool. To create new AD.

>   ``` adr new -s 2 vrs-integration  ```


## Do you want to contribute?
- Depending on your comfort and permission, there are multiple ways you may find yourself contributing via:
  - **Fork + PR** -- this approach is only needed if you don't have write access directly to the repo. See this for help: https://guides.github.com/activities/forking/
  - **Branch + PR** - this approach is used if you already have write access to the repo. See this for help: https://guides.github.com/introduction/flow/

- New to Git and not comfortable doing things in the commandline? If you prefer to work with a GUI, GitHub does allow you to do either approaches above all within the UI.
- Whatever steps you followed above, you will end in a Pull Request, also known as PR. This is required for all changes to this repo. Do not commit directly to the `master` branch.
- In the PR process, you will not see your changes right away. It is an area of discussion where the reviewer can ask for more questions or clarification about the changes you made. It is **best practice**, but not required to add/refer-to the issue number in the PR comments so it is easier to understand the context and background for why the PR is being made. 

  
