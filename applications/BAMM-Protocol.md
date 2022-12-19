# BAMM Protocol & Tingl web3 messenger built on BAMM

> This document will be part of the terms and conditions of your agreement and therefore needs to contain all the required information about the project. Don't remove any of the mandatory parts presented in bold letters or as headlines (except for the title)! Lines starting with a `>` (such as this one) should be removed. Please use markdown instead of HTML (e.g. `![](image.png)` instead of `<img>`). 
>
> See the [Grants Program Process](https://github.com/w3f/Grants-Program/#pencil-process) on how to submit a proposal.
- **Team Name:** Redwerk OU
- **Payment Address:** 0x367eb81b80F547Fe9944D2BC703b5866E91aC7fc (ETH)
- **[Level](https://github.com/w3f/Grants-Program/tree/master#level_slider-levels):** 3

> :exclamation: *The combination of your GitHub account submitting the application and the payment address above will be your unique identifier during the program. Please keep them safe.*
## Project Overview :page_facing_up:

If this application is in response to an RFP, please indicate this on the first line of this section.

If this is an application for a follow-up grant (the continuation of an earlier, successful W3F grant), please provide name and/or pull request of said grant on the first line of this section.

### Overview

BAMM protocol is a layer 3 transport protocol that could be used to build secure dapps with fully anonymous users. Its network of incentivized decentralized nodes is also an ecosystem of interacting dapps that rely on BAMM for transporting data.
Tingl messenger is our first product to be built on BAMM and is our initiative to breathe new life into secure messaging. We set up and stick to impeccable data security and user privacy standards, we also compliment that with the look, feel and a set of delightful features that finally make ultra-secure communication fun.

We are building a web3 layer 3 transport protocol to be used by our fellow blockchain developers in their endeavors to provide their project with a sufficient technical basis for transporting data between their decentralized users without exposing neither the data contents, nor any information about the peers.
We also build Tingl as BAMM's first application case to initiate the ecosystem and boost secure communication to a whole new level of being entertaining.

The addition of BAMM to the Polkadot ecosystem will expand the opportunities of developers building on Polkadot to create dapps that meet impeccable security and privacy standards out-of-the-box by building on BAMM.
We like Polkadot because it would be a decent blockchain to use for BAMM, we are also excited about sharing our BAMM protocol with the ecosystem's developers and letting them build upon our transport network. The opportunities to build a professional network and form partnerships with other ecosystem's dapps/teams is a plus as well.

### Project Details

#### Technical Stack
- Backend - [Rust](https://www.rust-lang.org/) ([libp2p](https://libp2p.io/) as a networking layer, [RocksDB](http://rocksdb.org/) as a storage)
- Mobile - [Flutter](https://flutter.dev/) (Rust for the core crypto functionality)

#### Components
##### Smart Contract
Smart contract component developed with ink!. The main purpose of this component is to provide a reliable mechanism of service nodes discovery for clients. Examples of applications:
- Client registration and SBT (soulbound token) minting
- Account verification
- Superlikes
- Names auction

More details could be found in the whitepaper.

##### Service Node
BAMM network functionality, scalability and decentralization is powered by a set of incentivized nodes. To operate as a service node, an owner is required to lock a predefined amount of BAMM tokens and provide minimal required bandwidth and storage to the network. In exchange an owner receives a reward based on the number of clients that use one’s node as a base node to connect to the network.

##### Mobile Client
User facing mobile application that implements messenger functionality. In order to access the network a client has to mint SBT first. Once it’s done, a client obtains infinite access to the network. Also the application works as a wallet for BAMM tokens and enables a client to perform any actions with it, such as buying more tokens, sending tokens to other users, etc.

#### Public Tingl UI previews (Figma)
[Link](https://www.figma.com/file/UDRJUFkLdKOZr9ZQnAo3bB/Tingl-Messanger?node-id=16%3A2684&t=FT3lOKIUB2BQmb4g-1)

### Ecosystem Fit

Our BAMM protocol improves the ecosystem by giving dapp developers an efficient and reliable data transporting solution to build their products upon. It makes creating secure and private dapps easier and enables teams to avoid the major nuisance of solving the data transport problem themselves.
As for Tingl, we build it for both the general web3 audience and for people trying to join the web3 community by providing them with a dapp for secure and private communication that is empowered with entertaining and delightful social and crypto- features that make secure messaging fun again.

According to our benchmark researches, there are no similar projects on Substrate / Polkadot / Kusama but there are some decentralized messengers in other ecosystems that are somewhat like Tingl: Sylo, Session and Secretum.

## Team :busts_in_silhouette:

### Team members

#### Team Leader

[Konstantin Klyagin, CEO of Redwerk and QAwerk](https://www.linkedin.com/in/thekonst/)

#### Team Members

Konstantin Klyagin, Dmytro Tryhubenko, Jemma Vaivala, Dmytro Dimenko, Mike Litvin, Olexander Yermakov, Gleb Krasnov, Olha Dubskih, Olha Lytvynenko

### Contact

- **Contact Name:** Dmytro Tryhubenko
- **Contact Email:** dimabelman@redwerk.com
- **Website:** [Dmytro's LinkedIn](https://www.linkedin.com/in/dimabelman/)

### Legal Structure

- **Registered Address:** Sakala tn 7-2, Kesklinna linnaosa Tallinn, Harju maakond, 10141 Estonia
- **Registered Legal Entity:** Redwerk OÜ

### Team's experience

Our project team consists of our company's (it is called Redwerk) full-time employees and our advisors so numerous previous successful Redwerk's projects are our common portfolio. Some team members also have a prior experience of working together.
The team is directed by our serial entrepreneur CEO Konstantin Klyagin, is guided towards our audience by an experienced marketing manager advising us, Dmytro Dimenko. The developer behind BAMM is our super star Alexander Yermakov who is also an open-source contributor. The mobile and desktop Tingl apps are developed by Hlib Krasnov, an outstanding Flutter developer. The team is managed by Dmytro Tryhubenko, a project management with experience managing remote cross-functional software teams.

This combo of our expertise, full mental investment and efficient team work is a what enables us to achieve the high ambitious bar we have set for ourselves.

### Team Code Repos

Our public project GitHub link is not available yet, however, the product will be fully open-source.

Please also provide the GitHub accounts of all team members. If they contain no activity, references to projects hosted elsewhere or live are also fine.

[Our lead Rust developer's GitHub profile](https://github.com/alexyer)

### Team LinkedIn Profiles (if available)

- [Konstantin Klyagin](https://www.linkedin.com/in/thekonst/)
- [Dmytro Tryhubenko](https://www.linkedin.com/in/dimabelman/)
- [Dmytro Dimenko](https://www.linkedin.com/in/dima-dimenko/)
- [Mike Litvin](https://www.linkedin.com/in/mikkelitvin/)
- [Olexander Yermakov](https://www.linkedin.com/in/olexander-yermakov-9b1006b4/)
- [Gleb Krasnov](https://www.linkedin.com/in/gleb-k/)

## Development Status :open_book:

The project (both BAMM protocol and Tingl messenger) are going to be fully open-source, however, the source code repository is not public yet - we will share it further down the development roadmap.

We will also share an external project status dashboard (WIP now) once we start cooperating.

[BAMM Whitepaper](https://redwerk.gitbook.io/tingl-end-to-end-encrypted-secure-p2p-messenger/)
[Old UI concept ideas](https://www.figma.com/file/UDRJUFkLdKOZr9ZQnAo3bB/Tingl-Messanger?node-id=28%3A2&t=dB1O0amhfbTeXVzl-1)

## Development Roadmap :nut_and_bolt:

### We apply to grant programs with a roadmap for the next 3 milestones (up until May 2023).

### Overview

- **Total Estimated Duration:** 3 months
- **Full-Time Equivalent (FTE):** 3.25
- **Total Costs:** $100,000

### Milestone 1: Tingl messenger MVP (February 1st, 2023)

- **Estimated duration:** 1.5 month
- **FTE:** 3.25
- **Costs:** 35,000 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| **0a.** | License | Apache 2.0 / GPLv3 / MIT / Unlicense |
| **0b.** | Documentation | We will provide both **inline documentation** of the code and a basic **tutorial** that explains how a user can (for example) spin up one of our Substrate nodes and send test transactions, which will show how the new functionality works. |
| **0c.** | Testing and Testing Guide | Core functions will be fully covered by comprehensive unit tests to ensure functionality and robustness. In the guide, we will describe how to run these tests. |
| **0d.** | Docker | We will provide a Dockerfile(s) that can be used to test all the functionality delivered with this milestone. |
| 1. | Blockchain integration | We will integrate with a EVM-compatible blockchain to both utilize and enhance it's ecosystem. BAMM Protocol will have blockchain features, so as any dapps built on it. |
| 2. | Smart contracts | We will develop basic smart contract for the specific blockchain we will integrate with first. The key contracts would be network node ones (node creation, node discovery) and general user ones (account creation, connecting a user to the network). |
| 3. | Multi-chain adapter | We will build a multi-chain adapter that would allow us to operate on multiple chains through an interface that interacts with our specific chain's contracts. |
| 4. | BAMM testnet launch | We will launch BAMM's testnet for both internal network testing and for developers to try building on BAMM in the BAMM ecosystem. |
| 5. | Tingl messenger mobile app is available for closed testing | Tingl messenger will be available for closed testing through TestFlight. |
| 6. | Tingl UI/UX v1 ready | Tingl messenger's v1 UI/UX design will be finished within this milestone, delivering all the UI designs necessary for Tingl's beta release. |
| 7. | BAMM Protocol security audits | We will perform security audits ran by reputable institutions like [CertiK](https://www.certik.com/). |

### Milestone 2: Tingl messenger release (March 15th, 2023)

- **Estimated duration:** 1.5 month
- **FTE:** 3.25
- **Costs:** 35,000 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| **0a.** | License | Apache 2.0 / GPLv3 / MIT / Unlicense |
| **0b.** | Documentation | We will provide both **inline documentation** of the code and a basic **tutorial** that explains how a user can (for example) spin up one of our Substrate nodes and send test transactions, which will show how the new functionality works. |
| **0c.** | Testing and Testing Guide | Core functions will be fully covered by comprehensive unit tests to ensure functionality and robustness. In the guide, we will describe how to run these tests. |
| **0d.** | Docker | We will provide a Dockerfile(s) that can be used to test all the functionality delivered with this milestone. |
| 1. | Tingl messenger's mobile version launched on stores | Mobile Tingl messenger will be available on App Store and Play Market at the end of this milestone. |
| 2. | Public validators program | We will have a public validators program allowing potential BAMM network node holders to become network's public validators. |
| 3. | Equity-based fundraising finished | We will run equity fund-raising and finish it within this milestone. |

### Milestone 3: Further BAMM and Tingl progress (May 1st, 2023)

- **Estimated duration:** 1.5 month
- **FTE:** 3.25
- **Costs:** 35,000 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| **0a.** | License | Apache 2.0 / GPLv3 / MIT / Unlicense |
| **0b.** | Documentation | We will provide both **inline documentation** of the code and a basic **tutorial** that explains how a user can (for example) spin up one of our Substrate nodes and send test transactions, which will show how the new functionality works. |
| **0c.** | Testing and Testing Guide | Core functions will be fully covered by comprehensive unit tests to ensure functionality and robustness. In the guide, we will describe how to run these tests. |
| **0d.** | Docker | We will provide a Dockerfile(s) that can be used to test all the functionality delivered with this milestone. |
| 0e. | Article | We will publish an **article**/workshop that explains [...] (what was done/achieved as part of the grant). (Content, language and medium should reflect your target audience described above.) |
| 1. | Extented Tingl web3, messaging and content creation features | This deliverable will include many web3 and crypto-related features like sending crypto to a contact or paying for someone's services. It will also expand the toolkit avaiable to content creators and artists using Tingl, as well as just adding some cherries on top of the apps' communication features. |
| 2. | Desktop Tingl app | We will release the desktop version of the Tingl messenger. It will include the newer features and will be developed using Flutter, like the mobile version. |
| 3. | IDO | We will run an IDO, the DEX/DEXes are to be determined yet. |

#### After passing these milestones that are key for Tingl we will also proceed to evolving the BAMM ecosystem by building new dapps within it.

*We will also share a public roadmap dashboard once it is ready.*

## Future Plans

Our short-term goal is to release our BAMM protocol's mainnet and to release our Tingl messenger alongside it.

After gathering the initial feedback and analytics data we will make the necessary changes to Tingl, we also will continue delivering and improving it continuously.

As for other dapps to be built on BAMM by our team, we have a list of project ideas with a web3 publishing platform, decentralized hosting and BAMM-based data storage solution dapps coming first. The first one of them (most likely the publishing app) will be started in 2023.


## Additional Information :heavy_plus_sign:

**How did you hear about the Grants Program?** Web3 Foundation Website
