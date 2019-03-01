## Using CLAs with an Open Project

This guide explains how the Open Project CLA implementation works: how contributors sign CLAs, how maintainers can confirm that a CLA has been signed, and what happens if the terms of the license change. 

### Context

An [Individual CLA](../templates/individual-cla.md) is an agreement project contributors execute to agree that they will abide the terms of the project's chosen license. An [Entity CLA](../templates/entity-cla.md) is signed when contributions are made by or on behalf of an organization, and usually requires review and sign off of an organization's legal counsel. All Open Projects use the same CLAs, regardless of the open source license they choose.

Contributors are required to sign a CLA before their contributions can be incorporated into the project. 

### How To Sign CLAs

For **Individual CLAs,** Open Projects use an automated tool called [CLA Bot](https://github.com/apps/cla-bot). When your project becomes an Open Project, the Open Projects Administrator will set the CLA Bot up for you on your project repositories on GitHub. The tool looks at all open Pull Requests and checks whether that user has signed the CLA. If they have not, a visual marker on the PR indicates that the user needs to sign the CLA before the PR can be merged. It also provides the contributor with a link to sign the CLA. If they have signed the CLA, the visual marker presents a green check mark. 

Once CLA Bot is implemented for your repository(ies), ALL contributors, maintainers, TSC and PGB members will need to sign the CLA electronically before their contributions can be merged in. If there are other automated tools or bots in use on your repo, let the Open Projects Administrator know so they can be added to the CLA Bot manually.

For **Entity CLAs,** which are less common, the process is manual - if you or your organization needs to sign an Entity CLA, the Open Project Administrator will direct you to an [electronic form on our website](https://www.oasis-open.org/resources/projects/cla/projects-entity-cla). After you sign the electronic form, the system will send you an email which you need to respond to in order to confirm. 

### How To View/Confirm a CLA has been Signed

Project leaders can confirm that a contributor has signed an Individual CLA simply by looking at the CLA Bot's visual marker on the contributor's pull requests.

If project leaders need to confirm whether an Entity CLA has been signed, they can look that information up at [this URL](https://www.oasis-open.org/resources/projects/cla/projects-view-entity-cla). 

### What happens if the license or terms change?

License or terms changes should not happen frequently, but depending on the type of changes made, contributors may have to sign a new CLA. OASIS Legal Staff will carefully evaluate any change to determine the best course of action along with the Open Project Administrator and Project Leadership.

If the change is deemed to be *non-substantive* - meaning that the terms have not changed, but for some reason the language or prose of the License or CLA are changing - the Open Projects Administrator may apply existing new CLA signatures to the new version of the CLA or License. Examples of non-substantive changes include spelling or grammar errors, adding clarifying prose, etc. 

If the change is deemed to be *substantive* - meaning that the terms of the License or CLA have changed - contributors will be required to resign the CLA. Substantive license or CLA changes should be evaluated carefully. Substantive license changes may require additional steps, such as a new major release, update to SemVer, public notice period, etc. OASIS Legal Staff will carefully review changes with project leadership to determine which actions are required. 
