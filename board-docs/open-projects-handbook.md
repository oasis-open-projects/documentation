![OASIS Open Projects Logo](../img/open-project-logos/open-projects-logo.PNG.png)

# OASIS Open Projects Handbook

## Table of Contents
 
1. [Overview](#1-overview)
1. [Participating in an Open Project](#2-participating-in-an-open-project) 
1. [Starting an Open Project](#3-starting-an-open-project)
1. [Lifecycle of the Project](#4-lifecycle-of-the-project)
1. [Tools and Resources](#5-tools-and-resources)
1. [Leadership Roles](#6-leadership-roles)
1. [Project Governance: Decisions and Meetings](#7-project-governance-decisions-and-meetings)
1. [Progression of Work](#8-progression-of-work)
1. [Naming, Branding, and Trademarks](#9-naming-branding-and-trademarks) 
1. [CLAs and Open Source Licenses](#10-clas-and-open-source-licenses)
1. [More Information](#11-more-information)

## 1. Overview

OASIS Open Projects let communities come together in one place to develop artifacts such as code, APIs, prose specifications, reference implementations, and protocols. The program combines a FOSS-friendly infrastructure to support shared development with the option to advance work through a standards approval process that includes potential recognition by an international standards development organization (SDO).

This Handbook supplements the [OASIS Open Project Rules][rules] by providing detailed information and instructions on starting and contributing to Open Projects.
 
### 1.1 Key Features

Open Projects offer:

* **Support, in one organization, for the development** of open source code and/or related materials and prose specifications 
* **Potential for formal approval** of appropriate content as OASIS Standards, with the opportunity for further external submission to SDOs including ISO, IEC, and ITU. 
* **Participation opportunities** for the entire community.
* **Stakeholder leadership** under Project Governing Boards and Technical Steering Committees.
* **Standards-level patent protections** assured by unique Contributor License Agreement (CLA) and common open source licences. 
* **Free public access to all deliverables in perpetuity.**
* **Extensible collection of project collaboration tools:** integrated issues management, project boards, continuous integration servers, version control, team messaging, release management, wikis, mailing lists, and chat.
* **Publicity and promotional activities** including press releases, webinars, plugfests, and social media. 

## 2. Participating in an Open Project 

### 2.1 Participation Roles 

There are many ways to participate in an Open Project:

Anyone (no login required) can view the Project’s activity, assets, and repository forks and download copies of repositories, releases, etc. 

***Participants*** (anyone with a GitHub account) can submit comments, report bugs, open issues, and request new features. There is no requirement to sign a CLA.

***Contributors*** can submit contributions by creating pull requests (to be evaluated by repository Maintainers) and engaging in threaded conversations. Contributors sign a CLA.

***Maintainers*** are appointed by the Project Governing Board and serve as Project editors. An Open Project must have at least one Maintainer, and each GitHub repository has at least one associated Maintainer Team.  Commitment and expertise are the key criteria for selecting Maintainers.

***Project Governing Board*** (PGB) members develop and manage the overall technical agenda of the Project, vote on releases, appoint Maintainers, and decide if/when to submit work for standards approval. 

***Technical Steering Committee*** (TSC) Member or other group member
A PGB may choose to form Technical Steering Committees and/or other groups related to marketing, events, etc.  Membership criteria and responsibilities for these groups are determined by the PGB.

Participation roles are summarized in this table:

|                                                    | Participant | Contributor | Maintainer | PGB Member |
| -------------------------------------------------- |:-----------:|:-----------:|:----------:|:----------:|
| Views Project assets                               |     ✔       |       ✔     |      ✔     |       ✔    |
| May provide comments and bug reports               |     ✔       |       ✔     |      ✔     |       ✔    |
| May submit pull requests                           |             |       ✔     |      ✔     |       ✔    | 
| Responds to pull requests                          |             |             |      ✔     |            |
| Appoints and supervises Maintainer(s)              |             |             |            |       ✔    |
| Authorizes creation of repositories                |             |             |            |       ✔    |
| Approves releases                                  |             |             |            |       ✔    |
| Approves submissions for Project Specifications    |             |             |            |       ✔    |
| Approves submissions to de jure standards bodies   |             |             |            |       ✔    |
| Elects Chair                                       |             |             |            |       ✔    |
| Must Sign CLA                                      |             |      ✔      |      ✔     |       ✔    |

*Also see [Section 6: Leadership Roles](#6-leadership-roles).*

## 3. Starting an Open Project

Whether you’re an established group with a fully scoped Project or a few people with a great idea, OASIS can provide the resources you need to achieve international recognition and widespread adoption.

There are no subject-matter limitations at OASIS. Project proposers decide on the technical agenda they wish to pursue. OASIS supports efforts ranging from cybersecurity, cloud computing, IoT, cryptography, privacy, law, emergency management, augmented reality, static analysis, and many other areas of interest to our community. People involved in IT, telecommunications, healthcare, utilities, financial services, academia, government, and other industries all collaborate on work at OASIS.

## 3.1 Draft a Charter 

The first step to starting your Open Project is to draft a charter, which will describe the goals and scope of your Project and provide relevant information for attracting participation and feedback.

Begin by reviewing the [Open Project Charter Template][charter]. You may download this template and complete your draft privately or ask the [Open Projects Administrator][email] to create a webpage where you and your co-proposers can collaborate to draft your charter. 

The final version of your charter will need to be submitted in English.

**Working with the Open Project Charter Template**

You’ll need to provide eight sections of content:

*Project Name*

The name of your Project should be descriptive, recognizable, and unique. If the full name is longer than 15-20 characters, you should consider also designating a short name or acronym. The best names are easily pronounced and memorable. Do an online search to ensure there isn’t an existing project or product with the same or similar name.

*Abstract*

The abstract should be a high-level, concise (80 words or fewer) description of the topic and key objectives of your project. 

*Purpose and Scope*

This section should explain why the work is necessary. Identify the specific problems you want to address. Describe your proposed solution in a way that will be clear to someone only moderately versed in the subject. Bring as much foresight as you can to your scope but don’t let it constrain the work. You’ll be able to refine this text throughout the life your project.

*Business Benefits*

Here’s where you answer the question, “What’s in it for me?”  This is the make-or-break part of your charter. Getting it right is an essential part of building your community of supporters. Provide as much detail as you can about the value of your project—both to potential participants and to adopters.

Ideally, list all the categories of stakeholders (types of organizations, vertical industries, professional titles) and explain how each will benefit. Help potential participants make the case for being part of this work. Convince potential adopters they should monitor if not engage with your project.

 Example:
 
>The Swizzle Stick Project will strengthen mixology infrastructure by bringing the adult beverage industry together to advance tools and standards that make it possible to mix anything anywhere, regardless of vendor, and assure uniform, application-level interoperable dilution of fluids.
>
>With Swizzle Stick, true interoperability and standardized secure interoperation with and connection between beverage containers will be possible. Swizzle Stick will promote innovation and benefit the entire range of stakeholders in the adult beverage ecosystem:
>
>- Beverage service point owners: Nightclubs, restaurants, dive bars , and other point-of-pour owners will have more freedom to choose their mix tool suppliers. Owners will be able to change and add different suppliers to their network whilst keeping their existing cocktail preparation stations operational (avoiding stranded assets and vendor lock-ins). Owners will have the flexibility to select suppliers and services based on the best price, quality of service, innovative features, and other criteria of their choosing.
>
>- Beverage providers: Providers of distribution systems can easily integrate mixing tools from different vendors into their system. 
>
>- Demand Response (DR) service providers and aggregators: Swizzle Stick will enable dynamic management of the adult beverage dispensing infrastructure as a Demand Response Distributed Liquid Resource. No more concerns about having too many 'friends' crash the party. 
>
>Bringing together representatives of the entire stakeholder community - people with different backgrounds, different needs, different approaches to drink preparation, from different locations around the world - to collaborate on an open protocol is the most reliable way to produce solutions that are cost-effective, diverse, comprehensive, innovative, and scaled to meet the aggressive adult beverage growth strategies.


*Relationship to Other Projects*

How does your project build on or relate to other open source activities or standards? List all related projects and describe how your approach differs from or complements each one.

Don’t hesitate to reference other work. Even if your project is truly groundbreaking, potential participants will want to know where it fits in the current landscape. Use this opportunity to demonstrate your awareness, clarify your differentiators, and attract support from developers involved in related efforts. If you plan to form liaison relationships with other groups, you may note that here too.

OASIS staff will use this information to connect your project with participants experienced in this space.

*Repositories and Licenses*

Provide names and descriptions for any initial repositories you expect to use for developing project assets. Specify your preferred license for each repository. The licenses offer different patent guarantees, reuse rights, and requirements that implementers will need to comply with. See the list of supported licenses [here](../policy/licenses).

Not sure which license to choose? OASIS can offer assistance to help you determine what’s right for your project.

*Initial Contributions from Existing Work*

If you plan to contribute existing specifications, repositories, or documentation to your project, provide those details—including links—in this section. Any type of prior work can be contributed, such as code, JSON schemas, and UML files. Be sure to note the license under which each contribution was developed.

If you do not intend to base your work on any initial contributions, note that in this section.

*Project Leadership*

Identify the organizations that will sponsor your project. [Annual project sponsorship dues](https://oasis-open-projects.org/sponsorship) are based on organization size (determined by total number of employees) and cover basic support services provided by OASIS. 

A PGB may opt to charge additional sponsorship fees in order to fund extra activities, such as hiring consultants or staff, hosting events, etc.

For each sponsoring organization, list the name and email address of the representative who will serve on the PGB. (The representative may change at any point.)  Email addresses are for OASIS staff use only and will not be published in the final proposal.

Before your project can launch, it must meet a minimum threshold in annual sponsorship commitments. OASIS staff can help find sponsors for your project. See [*Gather Support*](#3-2-gather-support)(below) for more on this.

Identify one person from your PGB who will act as the primary point of contact for your project prior to launch. (After launch, the PGB will elect its own Chair(s)).

You also have the option to provide names, email addresses, and organizational affiliations (if any) for other people interested in contributing to the project. Support from people who are recognized as subject experts or who are affiliated with stakeholder organizations adds credibility to your project and encourages more participation.

Be sure you have everyone’s consent to publish their names in this charter.
 
Spend as much time as you need to draft a clear, compelling charter. Ask OASIS staff for assistance. We’re happy to review and offer editorial suggestions at any point. It’s a good idea to ask your collaborators, domain experts, potential participants and adopters to provide feedback before you finalize the charter.

While you are able to edit sections as your work progresses, launching your project with a strong, well-thought-out charter will have a tremendous impact on your ability to grow your community and gain acceptance for your work.

### 3.2 Gather Support 

One of the advantages of starting your Open Project at OASIS is the opportunity recruit participants from our international community. Whether you start your project with a large, robust community or a few like-minded people, OASIS staff will work with you to recruit more supporters before and after your project is launched.

It’s a good idea to socialize your draft charter and build an impressive core of support before the project is publicly announced. Developers are attracted to projects that demonstrate momentum and commitment from a diverse group of supporters. Organizations want to be represented in initiatives their competitors and partners consider worthwhile.

If you don’t have minimum sponsorship for your project—or if you’d like to have more stakeholders on board before launch—OASIS staff can help you identify and reach out to potential participants from the OASIS member base and beyond. A strong charter is key to enlisting more support. 

### 3.3 Submit Your Charter 

When you are ready to submit your charter, notify OASIS via email. The Open Projects Administrator will review your charter to ensure it is complete and meets all requirements. If something’s missing, we’ll help you address it. Otherwise, it’s time to…

### 3.4 Launch Your Open Project 

OASIS will officially launch your project as soon as possible after your final charter has been submitted and reviewed. We will build your Open Project site on GitHub with an issues tracker, repositories, and wiki where your charter will be publicly viewable. OASIS will announce the project and issue an invitation to participate via OASIS websites, mailing lists, and social media channels.


## 4. Lifecycle of the Project 

At any point in its lifecycle, an Open Project will be in one of four stages:  

* **Proposed:** This is the stage when the project charter is being drafted and initial members are recruited. The project will have one asset: its draft charter. The proposers can take the time needed to craft a charter with a compelling value proposition and can recruit interested parties. 
* **Active:**  Once a project is Active, OASIS staff set up the full complement of collaboration tools for the project members. The project’s assets are publicly visible and work proceeds. 
* **Maintenance:** This stage indicates that active, day-to-day work is not underway but that the Maintainer(s) of the project continue to monitor implementations and respond to questions, bug reports, and enhancement requests. A project enters Maintenance mode by decision of its PGB or by declaration of the Open Projects Administrator when a PGB becomes inactive. Labelling a project as being in Maintenance mode lets the community know that active development is, for the moment, on hold. The project can return to Active mode at any time.
* **Completed:** If the goals of the project are accomplished, discontinued, or superseded, if the PGB expects no further development to be undertaken, and/or if there is no Maintainer, the project can be declared *Completed* within the OASIS Open Project program and the PGB will be closed. This determination can be made by the PGB or by the OASIS Open Projects Administrator if the PGB is inactive. All assets of the project will remain open and accessible.


## 5.  Tools and Resources 

OASIS provides development and collaboration tools for each Open Project, including support for integrated issue management, project boards, version control, release management, and associated Wiki pages.  Additionally, OASIS will support publicly archived email discussion lists and coordination with maintainers of any custom web sites or community portal web sites associated with an Open Project.

### 5.1 Issue Tracking

Initially, each Open Project has at least one issue tracking facility, configured to support the work of Contributors, Participants, PGB Members, Maintainer Teams, and TSC Members, as appropriate to their roles.  Issue tracking will be integrated with GitHub version control and (optional) project boards.  The PGB may request the creation of additional issue tracking instances and associated project boards on a per-repository basis. 

### 5.2 Version Control 

Project related code development, version control, and release management will be supported using Git, as managed by GitHub.  A PGB may request as many GitHub repositories as may be needed, each with its own Maintainer team(s), repository configurations, and workflow models.

### 5.3 Wiki Pages 

Each Open Project, as specified by the PGB, may use GitHub Wiki instances (one per GitHub repository). A Wiki may be configured to allow page edits only by Maintainers, or to allow for page edits by any Participants.

### 5.4 Mailing Lists 

At startup, each Open Project is configured to have a general email discussion list.  The PGB may request creation of additional mailing lists, as needed.  Mailing lists are publicly archived and are open to subscription by anyone.  Private discussions, if needed, may be requested for use by GitHub teams, but Open Projects are expected to conduct business in public view.

### 5.5 Custom Web Sites 
OASIS also provides each project with the option to create a custom landing page and supporting web pages that can provide a more compelling front-end for socializing the project.

### 5.6 Community Portal Sites 
Some Open Projects may be associated with community portal web sites that are not hosted or maintained by OASIS. Community portals are typically set up prior to the formation of an Open Project and may contain valuable legacy data. If community portals are maintained, they are subject to the [OASIS Trademark Policy](https://www.oasis-open.org/policies-guidelines/trademark).

### 5.7 Social Media Channels 

Each Open Project is encouraged to set up its own LinkedIn Group, Twitter account, Facebook page, and/or other communication channel for connecting with the community. OASIS staff are available to help as needed.

### 5.8 Additional Online Resources

Subject to resourcing and policy constraints, OASIS is committed to providing additional resources for Open Projects that may be needed in the future, beyond the tools, services, and platforms identified above.

## 6. Leadership Roles 
Each project operates under the governance of the [OASIS Open Project Rules][rules] and the active management of its Project Governing Board and assigned Maintainer(s). 

* **Project Governing Board** (PGB): Members of the PGB set the overall goals and technical agenda for the project, select the Chair or Co-Chairs, select the project’s Maintainer(s), and vote on releases, and decide if/when to submit work for standards approval. 
The PBG is made up of one representative from each organization that [sponsors the project](https://oasis-open-projects.org/sponsorship/). A list of PGB members is posted on each project’s website. 
To join or resign from a PGB, a representative must notify the [Open Projects Administrator][email] and the project Chair (or the convener, if the project has not yet launched). Contact [OASIS](mailto:join@oasis-open.org) for assistance.

* **Chair:**  Each PGB selects one or two of its members as Chair(s). The role of the Chair is to manage the PGB’s logistics, agenda, and decision-making. The Chair(s):
  * Help the PGB reach consensus on topics and manage any polls taken, working with the Open Projects Administrator when required by the [Open Project Rules][rules]. 
  * Coordinate and lead any meetings of the PGB or the broader community and, when needed, work with OASIS staff on related events. 
  * Assist the Maintainer(s) when necessary.
  * Act as the project's main point of contact with OASIS staff. 
A PGB must have a Chair. If the role is vacant, all PGB activities are suspended. 
* **Maintainer:** The PGB selects one or more Maintainers who maintain the code, approve pull requests, build binary packages for distribution, and generally act as the editors and managers of the repositories. 
Maintainers see to it that the technical consensus of the PGB and the community participants guide the work in the repositories. The role of Maintainer continues if the project enters Maintenance mode. If the PGB closes, the remaining Maintainer(s) or the Open Projects Administrator may appoint additional or replacement Maintainers.
* **Technical Steering Committee** (TSC): A PGB may choose to form a TSC. The responsibilities, appointment criteria, and size of the TSC is determined by the PGB in concert with the needs and preferences of its community.

*For more information, see [Section 2.1 Participation Roles](#2-1-participation-roles).*

## 7. Project Governance: Decisions and Meetings 

To ensure a vibrant, committed community, decisions about the work of the project can be and should be made via discussion and consensus between engaged members of the project community. Giving people a voice is an effective way to encourage involvement.

Under the Open Project Rules, some specific decisions are reserved for the members of the Project Governing Board. Even here, good practice and good manners recommend final decisions be made after reasonable notice to and consultation with the project community. The PGB Chair(s) are responsible for managing the process of reaching consensus and making decisions.

If and when the PGB chooses to hold meetings, they must be announced by the Chair(s) and scheduled in advance using the OASIS collaborative tools. Meetings can be face-to-face or electronic and must be set up to allow participation of all PGB members. Project participants can attend meetings, and the PGB is encouraged to help facilitate this. A note of each meeting's outcomes must be posted to the project’s mailing list or wiki.

Votes may be taken either by voice or by electronic means. When electronic ballots are specifically required, they must be conducted on facilities provided or approved by OASIS. Electronic ballots must always be run for at least seven days, although the Chair(s) may specify a longer voting period. Voters must always be able to change their vote up until the ballot closes.

## 8. Progression of Work 

Once work in an Open Project is underway, decisions about the progress are left in the hands of the community participants and in particular the PGB and/or the TSC (if one is formed). Pull requests, builds, assembly of releases, etc. can be handled as the PGB or TSC sees fit. 

At some point in the project’s development, the community may identify work that would benefit from becoming an open standard, for example, an API or an information exchange message format. Work intended for standardization advances through a series of approvals: *Project Specification Draft*, *Project Specification*, *Candidate OASIS Standard*, and finally, *OASIS Standard*. 

To begin progressing work as a standard, the PGB contacts the [Open Projects Administrator][email]. The first step will be to request a Project Specification template. This template is used to organize and package the contents for the subsequent steps. When this is complete, the PGB notifies project participants and the Open Projects Administrator of its intent to approve the package. Fourteen days after this notification, the PGB may approve the package as a *Project Specification Draft*. This approval can be via ballot or by motion in a meeting or by other consensus decision-making method provided the approval process and the record of it are publicly visible. 

Once the *Project Specification Draft* is approved, the PGB may act to approve it as a *Project Specification*. As above, the PGB must notify the participants and the Open Projects Administrator of its intent 14 days in advance. After the 14-day notification period, the Open Projects Administrator will conduct a [Special Majority Vote][terms] of the PGB members. This ballot will be carried out by electronic ballot. Upon its passing, the Administrator will work with the PGB to prepare the final *Project Specification*, load it to the OASIS library of approved work, and promote the approval. 

If the PGB wishes to continue, the next step will be to collect three or more [Statements of Use][terms] (SoU) of the *Project Specification*. These are short affirmations made by an entity that has successfully used or implemented the specification in compliance with all or some of its conformance clauses. Once the SoUs have been collected, the Open Projects Administrator will conduct a Special Majority Vote of the PGB to approve the specification as a *Candidate OASIS Standard* (COS). 

Once approved and published, the Administrator will broadly announce a 60-day public review of the COS. The specific steps involved depend on whether or not the PGB receives comments and whether or not they choose to make changes to the specification. The steps are explained in section [2.8.2 Public Review of a Candidate OASIS Standard](https://www.oasis-open.org/policies-guidelines/tc-process-2017-05-26#OSpublicRev). In general, however, once the public review is completed, the COS will be presented to the OASIS Membership in a [Call for Consent](https://www.oasis-open.org/policies-guidelines/tc-process-2017-05-26#OScallForConsent). If the Call closes with no objections raised, the COS will be published as an approved *OASIS Standard* and announced and promoted widely by OASIS. 

An approved *OASIS Standard* is available for submission to other standards organizations for their consideration. The requirements and steps involved are explained in the [Policy for submitting OASIS work to other organizations](https://www.oasis-open.org/policies-guidelines/liaison#submitwork) section of the OASIS Liaison Policy.

## 9.  Naming, Branding, and Trademarks 

When setting up a project, its name is obviously an important issue to consider. A distinctive name becomes the project’s identity, helping interested parties find it and helping to give others confidence in using it. It is worth the proposers’ time to choose a unique, expressive name. 

To ensure that the project and OASIS have complete freedom to use a name, trademarks or service marks not owned by OASIS cannot be used by an Open Project. Likewise, if a proposed name includes the name of other OASIS work, whether a Technical Committee, specification title, or the name of another Open Project, then the group responsible for that work must approve its use in advance. OASIS staff will help arrange this approval. Any existing trademarks that a project wishes to use in it name and work must be transferred to OASIS. 

OASIS staff will review and approve a project’s name before its official launch. 

## 10.  CLAs and Open Source Licenses 

Contributor License Agreements (CLAs) [bind][cla] Open Project contributors to well-understood licenses, ensuring that the contributed technology is available and implementable under clear legal terms. OASIS Open Project CLAs feature a special Specification Non-Assertion Covenant that assures work produced can be advanced to Project Specification or OASIS Standard status without patent issues or ambiguities.

Participants do not need to sign CLAs in order to review and comment on technical work, file bug reports, and make other non-substantive change requests to Open Project work products.

### 10.1 Individual Contributor License Agreement (I-CLA) 

People who wish to make substantive contributions to OASIS Open Projects are required to complete and submit an [Individual Contributor License Agreement (I-CLA)][icla].  This agreement clarifies the terms that apply to the  intellectual property contributions made by the individual.  A person involved in multiple OASIS Open Projects is covered under one I-CLA. 

### 10.2 Entity Contributor License Agreement (E-CLA) 

If a person’s contributions represent intellectual property owned by a company, organization, or other corporate entity (i.e., contributions made as a designated employee or representative of the entity), then the corporate entity should also complete and submit an [Entity Contributor License Agreement (E-CLA)][ecla].  

E-CLAs must be signed by all organizations with representatives on Project Governing Boards.

### 10.3 Open Project Licenses 

Each OASIS Open Project Repository is governed by the open source license selected by the Project Governing Board when the repository is created. Several popular open source licenses are currently supported: 

1. [Apache License v2.0](https://www.apache.org/licenses/LICENSE-2.0)
1. [Eclipse Public License v1.0](https://www.eclipse.org/legal/epl-v10.html)
1. [Eclipse Public License 2.0](https://www.eclipse.org/legal/epl-2.0/)
1. [BSD-3-Clause License](https://opensource.org/licenses/BSD-3-Clause)
1. [CC-BY 2.0](https://creativecommons.org/licenses/by/2.0/legalcode)
1. [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/legalcode)
1. [MIT License](https://opensource.org/licenses/MIT)

Upon request, OASIS will evaluate other widely-used, free, and open source licenses for potential inclusion in the list of supported licenses. 

## 11. More Information

See:

* [Open Project Program website](http://oasis-open-projects.org)
* [Charter Template][charter]
* [Open Project Rules][rules]

Contact the [OASIS Open Projects Administrator](#leadership-roles) for assistance.

[rules]: ./open-projects-rules.md
[charter]: ./templates/open-project-draft-charter.md
[terms]: ./OASIS-defined-terms.md
[email]: mailto:op-admin@oasis-open.org
[cla]:  ../policy/clas-and-special-covenant.md
[icla]: ../templates/individual-cla.md
[ecla]: ../templates/entity-cla.md

