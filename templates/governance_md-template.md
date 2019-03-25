*Note: this template is provided to give you a good idea about the kind of information you should include in a GOVERNANCE.md file as a best practice. You may copy and edit it as you see fit for your community, taking care to ensure that stays within the bounds of [Open Projects Rules](../board-docs/open-projects-rules.md). The purpose of a governance document is to answer the question, "How does your project community make decisions and organize its work?" OASIS Staff are happy to collaborate with you as well.*

*Attribution: This template was created from the output of the Harbor Project team. See their excellent [GOVERNANCE.md file](https://github.com/goharbor/community/blob/master/GOVERNANCE.md) for what it looks like in action.*

# [Project Name] Governance

**Directions**: briefly introduce the purpose of the document.

>Example:
>
>This document defines the project's community governance per [OASIS Open Projects Governance Policy](https://github.com/oasis-open-projects/documentation/blob/master/policy/project-governance.md).

## Overview

**Directions**: provide a short overview of the governance principles for your project, if any.

>Example:
>
>**PROJECT NAME**, an OASIS Open Project, is committed to building an open, inclusive, productive and self-governing open source community that creates next-generation APIs for cloud computing. The community is governed by this document and in accordance with [OASIS Open Project Rules](../board-docs/open-projects-rules.md) with the goal of defining how community should work together to achieve this goal.

## Code Repositories

**Directions**: List all the work areas that your governance document applies to. This may include spaces other than your repos if the decision-making process about those areas is the same.

>Example:
>
>The following code repositories are governed by the **PROJECT NAME** community and maintained under the project namespace:
>
>* **[project repo 1]():** Main codebase.
>* **[project repo 2]():** Sub-project codebase.
>* **[community resource 1]():** Website, community site, documentation repo, etc.

## Community Roles

**Directions**: List any specific roles that may exist for volunteer community members in your project, i.e. docs lead, community manager, mentorship lead, etc.

>Example: 
>
>* **Contributors:** People who make regular contributions to our project (documentation, code reviews, responding to issues, participation in proposal discussions, contributing code, etc.).
>* **Maintainers**: People who have been selected by project leadership to oversee one or more components of the project, review code and PRs, prepare releases, triage issues, and similar tasks.

## Project Leadership

**Directions**: List any formal groups or roles that require formal appointment, as well as the individuals currently filling those roles. All Open Projects have at least a TSC and a PGB. 

>Example:
>
>* **Technical Steering Committee**: Group responsible for the overall technical health and direction of the project; final reviewers of PRs, responsible for releases, responsible for overseeing work of maintainers and community leaders.
>* **Project Governing Board**: Group responsible for the overall lifecycle or business strategy of the project. Oversees activities such as events, marketing, partnerships, promotion, budget, and so forth.

### List of TSC Members

**Directions**: List TSC Members by name, github handle, contact method, organizational affiliation, or length of term if applicable.

>Example:
>
>* TSC Chair: Amy Zhu (@example), Acme Corp, serving through 2021
>* Ernesto Gomes (@example), UPAEP
>* Sam Smith (@example)

### List of PGB Members

**Directions**: List PGB Members by name, github handle, contact method, organizational affiliation if applicable.

>Example:
>
>* PGB Chair: Charles Crowley (@example), Cambridge University, serving through 2022
>* Amal Sharma (@example), Univision Inc
>* Jamie Jones (example@example.com)

### Becoming a Maintainer or TSC Member

**Directions**: Describe the process for how a contributor can become a maintainer and/or TSC member (optional). The process for becoming a PGB member can be found in [Open Projects Rules](../board-docs/open-projects-rules.md)

>Example:
>
>New maintainers must be nominated by an existing maintainer or TSC member and must be elected by a Special Majority of the TSC. Likewise, maintainers can be removed by a Special Majority of the total TSC or can resign by notifying the TSC.

## Decision Making

**Directions**: Describe how the leadership groups listed in the Project Leadership section will make decisions.  

>Example:
>
>Ideally, all technical project decisions will be reached by lazy consensus. If consensus cannot be reached within a reasonable period of time, the TSC may hold a Special Majority vote. Votes by maintainers belonging to the same company will count as one vote; e.g., 4 maintainers employed by the same company will only have **one** combined vote. 

### Special Majority Vote

**Directions**: Define any decision-making or voting processes you have referenced, such as 'Majority Vote.' Also note: 'Special Majority Vote' as defined below is an offical [OASIS defined term](https://www.oasis-open.org/policies-guidelines/oasis-defined-terms-2017-05-26). Certain issues require a Special Majority Vote, such as the decision to move work to the standards track. See [Open Projects Rules](../board-docs/open-projects-rules.md) for other cases.

>Example: 
>
>Special Majority is a vote in which at least 2/3 (two thirds) of the eligible voters vote "yes" and no more than 1/4 (one fourth) of the eligible voters vote "no". These numbers are based on the total number of eligible voters in the committee. Abstentions are not counted. For example, in a Committee in which there are 30 Voting Members, at least 20 Voting Members must vote "yes" for a motion to pass; but if 8 or more vote "no" then the motion fails.

### Lazy Consensus

>Example:
>
>Out of respect for other contributors, major changes should also be accompanied by a ping on Slack or a note on the Harbor dev mailing list as appropriate. Author(s) of proposal, Pull Requests, issues, etc.  will give a time period of no less than five (5) working days for comment and remain cognizant of popular observed world holidays.
>
>Other maintainers may chime in and request additional time for review, but should remain cognizant of blocking progress and abstain from delaying progress unless absolutely needed. The expectation is that blocking progress is accompanied by a guarantee to review and respond to the relevant action(s) (proposals, PRs, issues, etc.) in short order.
>
>Lazy Consensus is practiced for all projects in our org, including the main project repository, community-driven sub-projects, and the community repo that includes proposals and governing documents.
>
>Lazy consensus does _not_ apply to the process of:
>
>* Removing maintainers
>* Appointing PGB or TSC members
>* Moving streams of work to a standards track

## Proposal Process

**Directions**: Describe how the Project TSC and maintainers evaluate and proceed with work items. This example describes a proposal-based workflow, but your project may use other methodologies. It may be helpful to link or share an example of workflow you're describing.

>Example: 
>
>Large changes to the codebase and / or new features should be preceded by a proposal. This process allows for all members of the community to weigh in on the concept (including the technical details), share their comments, ideas, and use cases, and offer to help. It also ensures that members are not duplicating work or inadvertently stepping on toes by making large conflicting changes.
>
>The project roadmap is defined by accepted proposals.
>
>Proposals should cover the high-level objectives, use cases, and technical recommendations on how to implement. In general, the community member(s) interested in implementing the proposal should be either deeply engaged in the proposal process or be an author of the proposal.
>
>The proposal should be documented as a separated markdown file pushed to the root of the `proposals` folder in the [community](https://github.com/goHarbor/community) repository via PR. The name of the file should follow the name pattern `<short meaningful words joined by '-'>_proposal.md`, e.g:`clear-old-tags-with-policies_proposal.md`.
>
>Use the [Proposal Template]() as a starting point.

### Proposal Lifecycle

**Directions**: Describe any additional details of your workflow, such as a propsal lifecycle or sprint process (optional).

>Example:
>The proposal PR can be marked with different status labels to represent the status of the proposal:
>
>* **New**: Proposal is just created.
>* **Reviewing**: Proposal is under review and discussion.
>* **Accepted**: Proposal is reviewed and accepted (either by consensus or vote).
>* **Rejected**: Proposal is reviewed and rejected (either by consensus or vote).

## Updating Governance

**Directions**: Descibe the steps that would be needed to alter the process above.

>Example:
>
>All substantive changes in Governance require a vote of the TSC.
