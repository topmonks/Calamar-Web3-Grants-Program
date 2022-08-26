# Calamar

- **Team Name:** TopMonks
- **Payment Address:** <span style="background-color: yellow">TODO</span>
- **[Level](https://github.com/w3f/Grants-Program/tree/master#level_slider-levels):** 2

## Project Overview :page_facing_up:

<span style="background-color: yellow">TODO</span>

The idea for another explorer has emerged during the dotsama events in Amsterdam and Prague. The team of TopMonks blockchain studio has gathered feedback from friendly projects such as HydraDx and KodaDot among others.
We have applied for the bounty from Subsquid of the Polkadot hackaton North America edition, that required developing block explorer ([https://devpost.com/software/calamar](https://devpost.com/software/calamar)).
We call it the Calamar, as it is in line with the Subsquid identity.

It is available here:
[https://calamar.app](https://calamar.app) \
and we manage the code here:
[https://github.com/topmonks/calamar](https://github.com/topmonks/calamar)

Based on the positive feedback we would like to push the project further and bring more valuable features for the users, closely cooperating with the [Subsquid](https://subsquid.io) team and gathering an on-going feedback from the users.

### Overview

Calamar is a block explorer for Polkadot and Kusama relay chains and their parachains, that uses Subsquid API for data fetching.

For now, it allows users to search:
- for blocks by hash and height,
- for extrinsics by hash, name or signer address
- and for events by name.

While developing Calamar, we focus on UI and UX friendliness so that users enjoy dotsama chains exploring, as well as relevance of displayed data.

### Project Details

Currently, Calamar consists of the following pages:
- **home page**: universal search box,
- **latest extrinsics page**: table of the latest extrinsics in the selected network,
- **block page**: information about the block, extrinsics included in the block,
- **extrinsic page**: information about the extrinsic, extrinsics events table,
- **account page**: different account address format, extrinsics signed by the account.

As part of the development described in the proposal, we would like to improve the project to make it more usable for Dotsama users. Specific points to follow:

1. Routing improvements for better navigation and link sharing.
2. Displaying additional data, provided by subsquid, for existing entities.
3. Improving the parsing of event and extrinsic parameters.
4. Improvements to the explorer display on mobile and tablet devices.
5. Establish an infrastructure for communication with users and developers (twitter, telegram, medium).
6. Custom display of extrinsic data that are transfers and cross-chain messages.

![XCM transfers table](https://res.cloudinary.com/topmonks/image/upload/v1661502168/calamar/xcm-transfers-table.png)
![XCM transfer page](https://res.cloudinary.com/topmonks/image/upload/v1661494067/calamar/xcm-transfer-page.png)

7. Expanding the account page to include the name if set and asset values and their statuses from all listed parachains, including dollar values and graphs for visualization.

![Account page](https://res.cloudinary.com/topmonks/image/upload/v1661502521/calamar/account-page.png)

8. Adding a dashboard for chains that will show statistics and tables of the latest extrinsics, transfers and cross-chain messages, TODO wireframe.
9. Modifying the search to not require specifying the chain in which the search is performed.

> If this application is in response to an RFP, please indicate this on the first line of this section.
>
> If this is an application for a follow-up grant (the continuation of an earlier, successful W3F grant), please provide name and/or pull request of said grant on the first line of this section.
>
> ### Overview
>
> Please provide the following:
>
> - If the name of your project is not descriptive, a tag line (one sentence summary).
> - A brief description of your project.
> - An indication of how your project relates to / integrates into Substrate / Polkadot / Kusama.
> - An indication of why your team is interested in creating this project.
>
> ### Project Details
>
> We expect the teams to already have a solid idea about your project's expected final state. Therefore, we ask the teams to submit (where relevant):
>
> - Mockups/designs of any UI components
> - Data models / API specifications of the core functionality
> - An overview of the technology stack to be used
> - Documentation of core components, protocols, architecture, etc. to be deployed
> - PoC/MVP or other relevant prior work or research on the topic
> - What your project is _not_ or will _not_ provide or implement
>   - This is a place for you to manage expectations and to clarify any limitations that might not be obvious
>
> Things that shouldn’t be part of the application (see also our [FAQ](../docs/faq.md)):
> - The (future) tokenomics of your project
> - For non-infrastructure projects—deployment and hosting costs, maintenance or audits
> - Business-oriented activities (marketing, business planning), events or outreach
>
> ### Ecosystem Fit
>
> Help us locate your project in the Polkadot/Substrate/Kusama landscape and what problems it tries to solve by answering each of these questions:
>
> - Where and how does your project fit into the ecosystem?
> - Who is your target audience (parachain/dapp/wallet/UI developers, designers, your own user base, some dapp's userbase, yourself)?
> - What need(s) does your project meet?
> - Are there any other projects similar to yours in the Substrate / Polkadot / Kusama ecosystem?
>   - If so, how is your project different?
>   - If not, are there similar projects in related ecosystems?

## Team :busts_in_silhouette:

<span style="background-color: yellow">TODO</span>

### Team members

<span style="background-color: yellow">TODO</span>

### Contact

- **Contact Name:** <span style="background-color: yellow">TODO</span>
- **Contact Email:** <span style="background-color: yellow">TODO</span>
- **Website:** https://topmonks.com

### Legal Structure

- **Registered Address:** Struhařovská 2931/9, 141 00, Praha 4, Czech Republic
- **Registered Legal Entity:** TopMonks s.r.o

### Team's experience

<span style="background-color: yellow">TODO</span>

### Team Code Repos

- https://github.com/topmonks/calamar

<span style="background-color: yellow">TODO</span>

### Team LinkedIn Profiles

<span style="background-color: yellow">TODO</span>

> ### Team members
>
> - Name of team leader
> - Names of team members
>
> ### Contact
>
> - **Contact Name:** Full name of the contact person in your team
> - **Contact Email:** Contact email (e.g. john@duo.com)
> - **Website:**
>
> ### Legal Structure
>
> - **Registered Address:** Address of your registered legal entity, if available. Please keep it in a single line. (e.g. High Street 1, London LK1 234, UK)
> - **Registered Legal Entity:** Name of your registered legal entity, if available. (e.g. Duo Ltd.)
>
> ### Team's experience
>
> Please describe the team's relevant experience. If your project involves development work, we would appreciate it if you singled out a few interesting projects or contributions made by team members in the past. For research-related grants, references to past publications and projects in a related domain are helpful.
>
> If anyone on your team has applied for a grant at the Web3 Foundation previously, please list the name of the project and legal entity here.
>
> ### Team Code Repos
>
> - https://github.com/<your_organisation>
> - https://github.com/<your_organisation>/<project_1>
> - https://github.com/<your_organisation>/<project_2>
>
> Please also provide the GitHub accounts of all team members. If they contain no activity, references to projects hosted elsewhere or live are also fine.
>
> - https://github.com/<team_member_1>
> - https://github.com/<team_member_2>
>
> ### Team LinkedIn Profiles (if available)
>
> - https://www.linkedin.com/<person_1>
> - https://www.linkedin.com/<person_2>

## Development Status :open_book:

Current version of Calamar is running on https://calamar.app

It is mostly a result of [our participation](https://devpost.com/software/calamar) in [Polkadot Hackaton: North America Edition](https://polkadot-na.devpost.com/) as an implementation of the [bounty](https://github.com/subsquid/bounties/issues/1) declared by [Subsquid](https://subsquid.io) team.

While it may seem to be already working explorer it has only basic features and lacks many of the important or useful ones.

> If you've already started implementing your project or it is part of a larger repository, please provide a link and a description of the code here. In any case, please provide some documentation on the research and other work you have conducted before applying. This could be:
>
> - links to improvement proposals or [RFPs](https://github.com/w3f/Grants-Program/tree/master/rfp-proposal) (requests for proposal),
> - academic publications relevant to the problem,
> - links to your research diary, blog posts, articles, forum discussions or open GitHub issues,
> - references to conversations you might have had related to this project with anyone from the Web3 Foundation,
> - previous interface iterations, such as mock-ups and wireframes.

## Development Roadmap :nut_and_bolt:

<span style="background-color: yellow">TODO</span>

### Overview

- **Total Estimated Duration:** 3 month
- **Full-Time Equivalent (FTE):** <span style="background-color: yellow">TODO</span>
- **Total Costs:** 30,000 USD

### Milestone 1 — Core functionality

- **Estimated duration:** 1 month
- **FTE:** <span style="background-color: yellow">TODO</span>
- **Costs:** 11,000 USD

Even though we have the already working application there are still many things missing. Some of them prevent the users to use Calamar fully as the main explorer. We need to first assure the correct core functionality, display all meaningful data which are retrievable without further processing, improve design and UX and integrate more into the Polkadot ecosystem.

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0a. | License | <span style="background-color: yellow">TODO</span> Apache 2.0 / GPLv3 / MIT / Unlicense |
| 0b. | Documentation | We will provide inline documentation of the code where necessary, technical description how to run the own instance of Calamar and tutorials how to use the application from the user perspective. |
| 0c. | Testing Guide | We will provide end-to-end tests covering UI functionality. |
| 0d. | Docker | We will provide a Dockerfile(s) for testing and running own Calamar instance. |
| 0e. | Article | We will publish an article that explains what was done as part of the grant |
| 1. | Shareable links | Current implementation of the Calamar Explorer does not allow users to share links with the search result due to urls are not linked to a specific chain. We would like add the chain information in the url which would allow us to keep the source of information. |
| 2. | Add missing data | Find out and add data which are missing and can be displayed for individual items (extrinsics args, ...) |
| 3. | Website info | Add useful information to the website such as footer with team logos, contact information, etc. |
| 4. | Responsivness | Improve overall responsivness for mobile devices especially of item tables and extrinsics/event args |
| 5. | Polkadot.js integration | Integrate links to the Calamar Explorer into Polkadot.js app |
| 6. | Extrinsics/event args display improvements | Improve the way how extrinsic/event args are displayed <ul><li>property data types</li><li>multiple views (raw/json, human readable)</li></ul> |
| 7. | Items count | Current implementation doens't show the total number of searched items. We would like to retrieve the items count and display it properly |
| 8. | Extrinsic/event fulltext search by name | Add ability to search extrinsics and events by their name in fulltext manner |
| 9. | PR, user support | Setup channels (telegram, twitter, blog) for communication with users for annoucments, support etc. |

### Milestone 2 - Account detail & XCM teleports

- **Estimated duration:** 1 month
- **FTE:** <span style="background-color: yellow">TODO</span>
- **Costs:** 11,000 USD

As we are gathering feedback, one of the most important features for the users seems to be the account overview where users can find information about their balances and transactions accross all parachains. Another important feature is to create good UI for displaying information about XCM teleports where you can easily see all involved sides (parachains, accounts) and other useful data.

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0a. | License | <span style="background-color: yellow">TODO</span> Apache 2.0 / GPLv3 / MIT / Unlicense |
| 0b. | Documentation | We will provide inline documentation of the code where necessary  and tutorials how to use new features. |
| 0c. | Testing Guide | We will provide end-to-end tests covering UI functionality. |
| 0d. | Docker | *N/A - will be provided by the first milestone.* |
| 0e. | Article | We will publish an article that explains what was done as part of the grant |
| 1. | Account detail | Improve account detail page with cross-chain information <ul><li>overview of owned assets (accross all parachains)</li><li>total balance chart</li><li>list of corresponding addresses in other parachains</li> |
| 2. | Account address parsing in events args | Detect account address in event args and link it to the account detail (parachain detected automatically) |
| 3. | XCM transfers and teleports | Detect cross-chain transfers and display relevant information of involved parachains and accounts |

### Milestone 3 - Universal search & Parachain dashboards

- **Estimated duration:** 1 month
- **FTE:** <span style="background-color: yellow">TODO</span>
- **Costs:** 8,000 USD


There are two things which can highly improve the usefulness of the explorer.

The fist is the universal search where you don't have to know which parachain the searched item belongs to. You just put the hash into the search box and the explorer will take care of the determining on which parachain it is. This is going to be an addition to the current implementation where you can restrict search to a specific parachain.

The next big thing is dashboards for parachains with various statistics, it makes the explorer more useful even for users who are not searching specific items.

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0a. | License | <span style="background-color: yellow">TODO</span> Apache 2.0 / GPLv3 / MIT / Unlicense |
| 0b. | Documentation | We will provide inline documentation of the code where necessary  and tutorials how to use new features. |
| 0c. | Testing Guide | We will provide end-to-end tests covering UI functionality. |
| 0d. | Docker | *N/A - will be provided by the first milestone.* |
| 0e. | Article | We will publish an article that explains what was done as part of the grant |
| 1. | Universal search | Search items through all the parachains without the knowledge where it belongs |
| 2. | Parachain dashboard | Create dashboard with stats and charts for each parachain |

> This section should break the development roadmap down into milestones and deliverables. To assist you in defining it, we have created a document with examples for some grant categories [here](../docs/grant_guidelines_per_category.md). Since these will be part of the agreement, it helps to describe _the functionality we should expect in as much detail as possible_, plus how we can verify and test that functionality. Whenever milestones are delivered, we refer to this document to ensure that everything has been delivered as expected.
>
> Below we provide an **example roadmap**. In the descriptions, it should be clear how your project is related to Substrate, Kusama or Polkadot. We _recommend_ that teams structure their roadmap as 1 milestone ≈ 1 month.
>
> For each milestone,
>
> - make sure to include a specification of your software. _Treat it as a contract_; the level of detail must be enough to later verify that the software meets the specification.
> - include the amount of funding requested _per milestone_.
> - include documentation (tutorials, API specifications, architecture diagrams, whatever is appropriate) in each milestone. This ensures that the code can be widely used by the community.
> - provide a test suite, comprising unit and integration tests, along with a guide on how to set up and run them.
> - commit to providing Dockerfiles for the delivery of your project.
> - indicate milestone duration as well as number of full-time employees working on each milestone.
> - **Deliverables 0a-0d are mandatory for all milestones**, and deliverable 0e at least for the last one. If you do not intend to deliver one of these, please state a reason in its specification (e.g. Milestone X is research oriented and as such there is no code to test).
>
> > :zap: If any of your deliverables is based on somebody else's work, make sure you work and publish _under the terms of the license_ of the respective project and that you **highlight this fact in your milestone documentation** and in the source code if applicable! **Teams that submit others' work without attributing it will be immediately terminated.**
>
> ### Overview
>
> - **Total Estimated Duration:** Duration of the whole project (e.g. 2 months)
> - **Full-Time Equivalent (FTE):**  Average number of full-time employees working on the project throughout its duration (see [Wikipedia](https://en.wikipedia.org/wiki/Full-time_equivalent), e.g. 2 FTE)
> - **Total Costs:** Requested amount in USD for the whole project (e.g. 12,000 USD). Note that the acceptance criteria and additional benefits vary depending on the [level](../README.md#level_slider-levels) of funding requested. This and the costs for each milestone need to be provided in USD; if the grant is paid out in Bitcoin, the amount will be calculated according to the exchange rate at the time of payment.
>
> ### Milestone 1 Example — Implement Substrate Modules
>
> - **Estimated duration:** 1 month
> - **FTE:**  2
> - **Costs:** 8,000 USD
>
> | Number | Deliverable | Specification |
> | -----: | ----------- | ------------- |
> | 0a. | License | Apache 2.0 / GPLv3 / MIT / Unlicense |
> | 0b. | Documentation | We will provide both **inline documentation** of the code and a basic **tutorial** that explains how a user can (for example) spin up one of our Substrate nodes and send test transactions, which will show how the new functionality works. |
> | 0c. | Testing Guide | Core functions will be fully covered by unit tests to ensure functionality and robustness. In the guide, we will describe how to run these tests. |
> | 0d. | Docker | We will provide a Dockerfile(s) that can be used to test all the functionality delivered with this milestone. |
> | 0e. | Article | We will publish an **article**/workshop that explains [...] (what was done/achieved as part of the grant). (Content, language and medium should reflect your target audience described above.)
> | 1. | Substrate module: X | We will create a Substrate module that will... (Please list the functionality that will be implemented for the first milestone) |
> | 2. | Substrate module: Y | We will create a Substrate module that will... |
> | 3. | Substrate module: Z | We will create a Substrate module that will... |
> | 4. | Substrate chain | Modules X, Y & Z of our custom chain will interact in such a way... (Please describe the deliverable here as detailed as possible) |
>
>
> ### Milestone 2 Example — Additional features
>
> - **Estimated Duration:** 1 month
> - **FTE:**  1
> - **Costs:** 4,000 USD
>
> ...


## Future Plans

<span style="background-color: yellow">TODO</span>

> Please include here
>
> - how you intend to use, enhance, promote and support your project in the short term, and
> - the team's long-term plans and intentions in relation to it.


## Additional Information :heavy_plus_sign:

**How did you hear about the Grants Program?** Personal recommendation

> Here you can also add any additional information that you think is relevant to this application but isn't part of it already, such as:
>
> - Work you have already done.
> - If there are any other teams who have already contributed (financially) to the project.
> - Previous grants you may have applied for.
