# perpetual-swaps-hackathon

The Secret x Shade Perpetual Swap Hackathon is a collaborative event where talented developers and DeFi visionaries with a passion for privacy can converge and create the next generation of decentralized financial opportunities that preserve user data privacy. Through this Hackathon, Shade Protocol and Secret Network hope to encourage and facilitate the development of a Proof of Concept (PoC) for a decentralized leverage trading platform that utilizes secret smart contracts. If successful, the Hackathon winner would receive a grant from Shade Protocol and Secret Labs to make this PoC production ready and launch on Secret Network Mainnet.

_Perpetual Swap Introduction_

Decentralized Finance offers lending, borrowing, trading, and yield farming opportunities, attracting billions of dollars in assets. Perpetual swaps are a type of derivative contract widely used in cryptocurrency trading that enables traders to speculate in a leveraged fashion on the future price of an asset without owning it. Just like within traditional derivatives markets, crypto derivatives market volume (perpetual swaps) drastically exceed the spot market volume as a result of the leveraged positions involved. As a result, Perpetual Swap Exchanges generate increasingly large amounts of revenue from fees and cement them as some of the most profitable decentralized financial products to date.

As a result of the high leverage nature of perpetual swaps and the impact they have on spot markets, the liquidation points of large traders are constantly being tracked on public blockchains. This public data can be leveraged by programmatic actors to attempt to extract value from traders through market manipulation to cause cascading liquidations. However, with secret smart contracts, liquidation points of traders would be completely private and only known to them. The data privacy that Secret Network provides for its smart contract interactions allows users to partake in leverage trading in a secure and permissionless way that prevents value extraction.

In summary, a hackathon dedicated to building a decentralized perpetual swap exchange on Secret Network responds to the need for data privacy in derivative markets and will spur a lasting wave of novel utility, activity and sustainability for Private DeFi on Secret Network.

***Event Details***

* Date and Time: November 16, 2023 - December 16, 2023
* Location: Virtual
* Main Communication Channel: [Shade Protocol Discord[(https://discord.gg/shade-protocol-905665558610051113) and Secret Network Developer Telegram
* Hackathon Sign Up: https://www.eventbrite.com/e/shade-perpetual-swap-hackathon-tickets-743631831827
 
***Objectives***

* Create PoC for a perpetual swap market using secret smart contracts
* Create minimal front-end to demo PoC
 
***Participant Information***

Candidates should have experience in cosmwasm smart contract development (proficiency in rust) with interest or background in economics/finance.

***Hackathon Rewards and Grant Funding***

Shade Protocol and Secret Labs are both sponsoring the Hackathon with rewards and grant funding. Prizes will be awarded for the Hackathon based on scores from judging criteria.

* Hackathon Rewards
  * Shade Protocol - 15k USD equivalent in SHD
  * Secret Labs - 5k USD equivalent in SCRT
 
* Grant Funding to bring PoC to production within Shade dApp suite
  * Shade Protocol - 35k USD equivalent in SHD
  * Secret Labs - 15k USD in SCRT

* Reward Distribution
  * 1st - 10k USD equivalent in SHD + SCRT
  * 2nd - 6k USD equivalent in SHD + SCRT
  * 3rd - 4k USD equivalent in SHD + SCRT

***Agenda***

| Workshop | Date | Topic | Presenter |
| :--------: | :-------: | :--------: | :--------: |
| Workshop 1a | Nov. 16th | Hackathon Keynote Speech: "Closing the sustainability loop with Perpetual Swaps" | Carter Woetzel - Shade Protocol |
| Workshop 1b | Nov. 21st | Introduction to Secret Smart Contract Development and Shade Dev Environment Set-up | Jackson Swenson - Shade Protocol |
| Workshop 2a | Nov. 27th | Financial Mathematical Modeling for Perpetual Swap Exchanges | TBD |
| Workshop 2b | Nov. 29th | Advanced SecretWasm Development - building complex interactions | Slabs |
| Workshop 3a | Dec. 1st | Risk Management in DeFi | Red Eyed Bear - Shade Protocol |
| Workshop 4a | Dec. 4th | Price Feeds and Oracle Integration | Woz - Ojo |
| Workshop 4b | Dec. 12th | Unit Tests, Multi-tests, and other smart contract debugging strategies | Jackson Swenson - Shade Protocol |
| Workshop 5a | Dec. 13th | Front-end Development using SecretJS and Data Visualization | Austin Woetzel - Shade Protocol |

***Mentors***

* Secret Saturn - Secret Network Foundation Developer Relations
* SeanRad - Secret Labs Developer Relations
* Austin Woetzel - Shade Protocol Front-end Development
* Jackson Swenson - Shade Protocol Smart Contract Development

***Resources***

Shade Protocol is an interconnected suite of DeFi primitives that provides a unified user experience for DeFi participants. Our full docs are available [here](https://docs.shadeprotocol.io/shade-protocol/). For more in depth information on the various Shade dApps, our whitepaper is [here](https://shadeprotocol.io/wp-content/uploads/2023/01/Shade-Protocol-Whitepaper.pdf). 

For information on how to get started developing with secret smart contracts on Secret Network, check out the [Secret Network Developer Documentation](https://docs.scrt.network/secret-network-documentation/development/getting-started).

Shade x SCRT Labs Perpetual Swap Hackathon recorded workshops: https://www.youtube.com/playlist?list=PLFEm8se77ryMielAM_RuyMSQVrum9CN5S

For general education about perpetual swap exchanges, check out:

* [What are Crypto Derivatives? Perpetual and Futures Contracts Explained](https://www.youtube.com/watch?v=5vW7hX6k5ho&pp=ygUPcGVycGV0dWFsIHN3YXBz)
* [Bitcoin Derivatives: Perpetual Swaps 101](https://www.youtube.com/watch?v=wfx78LWd3PM)
* [Cartoon Guide to Perps](https://www.paradigm.xyz/2021/03/the-cartoon-guide-to-perps)
* [Primer on Perpetual Swaps](https://medium.com/firefly/primer-on-perpetual-swaps-1a7ca905f0af)
* [Deep Dive into Perps Market Overview](https://medium.com/@gryphsisacademy/decentralized-perpetual-exchanges-a-dive-into-technology-market-analysis-and-upcoming-d3f938e0d034)

Shade Github Links:

* [Main Shade Protocol Repository](https://github.com/securesecrets/shade)
* [Shade Oracles](https://github.com/securesecrets/shade-oracle)
* [Better Secret Math, gas optimized math operations for Secret Network](https://github.com/securesecrets/better-secret-math)
* [ShadeSwap Router Contract](https://github.com/securesecrets/shadeswap/tree/main/contracts/router)
  * The router is where trades are executed by the users (similar to matching engine required for Perpetual Swap exchange). Pools on are only in pairs meaning only the tokens in that pool can be traded. However, trades can be routed between pools.
* [ShadeSwap Pool Factory contract](https://github.com/securesecrets/shadeswap/tree/main/contracts/factory)
  * The factory is where pools are created (permissioned). The most useful thing in the factory is the ListAMMPairs query and GetAMMPairAddress if you are looking for the list of pools that are currently available.
* [ShadeSwap AMM pair contract](https://github.com/securesecrets/shadeswap/tree/main/contracts/amm_pair)
  * These contracts are the actual pools of funds that trades are executed on. If you are trying to conduct arbitrage, these are the contracts you want to use. Refer to the README in the amm_pair repo for more information.

Shade Software Development Kit:

* [ShadeJS](https://shadejs.dev/) - Open source library for interacting with Shade Protocol smart contracts.
  * typescript SDK that abstracts the complexity of secret client management (for queries), as well as providing simple-to-use typescript interfaces for the inputs and outputs of contracts.
  * Also includes multi-query optimizations in order to obtain large on-chain data sets in a highly efficient manner.

Enhanced Privacy Design with Secretwasm: https://docs.scrt.network/secret-network-documentation/development/development-concepts/privacy-design

Relevant Smart Contract Addresses:

* Query Authentication - query_auth: secret1e0k5jza9jqctc5dt7mltnxmwpu3a3kqe0a6hf3
* Shade oracle: secret17z47r9u4nqytpdgvewxq4jqd965sfj2wpsnlak
* Band Oracle: secret1p892w5elgy6746mq0kufpsdjr502tfl64adnx0
* Ojo Oracle: secret1u6mtm6yk9z95w4d34dzj443h495yt3zqn8ny3p

Perpetual Swap Exchange Technical Resources:

* [GMX Technical Overview](https://gmx-io.notion.site/gmx-io/GMX-Technical-Overview-47fc5ed832e243afb9e97e8a4a036353)
* [GMX Contract Documentation](https://gmxio.gitbook.io/gmx/contracts)
* [GMX Contracts - Github](https://github.com/gmx-io/gmx-contracts/tree/master)
* [Levana Technical Overview](https://docs.levana.finance/high-level-overview)

***Evaluation and Success Metrics***

Requirements:

* Provide clear documentation for developers and users on how to interact with the platform and its smart contracts.
* Core smart contract functionalities:
  * Perptual Swap Contract
    * Limit and market order placement with inputs being trading pair, order type, order size, leverage, stop loss and take profit, etc
    * Matching engine that matches buy and sell orders based on predetermined criteria and execute them
    * Users should be able to open, modify and close positions
    * Implement risk management mechanisms including the ability for admin/gov to set market and position limits, max leverage limits, circuit breakers, liquidation mechanisms, etc 
    * Calculate and apply funding rates to maintain fair market price in swap contracts (payments between long and short position holders)
  * Liquidity Pool (AMM) Contracts:
    * Integrate with perpetual swap contracts
    * Allow users to provide liquidity to the perpetual swap contracts by depositing assets into the liquidity pools. Users provide assets for both long and short positions.
    * Allow users to swap using LPs
    * Ensure LPs are balanced to maintain asset ratios
    * Charge fees on trades that occur
  * Price Feed Contracts
    * Accepts submissions of price feeds from oracles or keeper
    * Ensure security mechanisms are in place to prevent tampering and redundancy in case of outage
    * Ability to utilize multiple oracles

***Judging Criteria***

Judging will be performed by a panel of 3 engineers (1 from Shade, 1 from Slabs, 1 from Secret Network Developer community)

* Smart Contract Functionality (35 points):
  * Core Feature functionality
  * Accuracy and reliability of logic and calculating relevant metrics:
  * Security
* Technical Implementation (25 points):
  * Code Quality (coding standards, readability, and maintainability)
  * Gas Efficiency (measured as gas cost relative to benchmark, scaled multiplicatively)
  * Scalability
* Usability (30 points):
  * Necessary contract interactions using testnet front-end for full user story
  * Accurate data visualization
* Integration and Interoperability (20 points):
  * Compatibility with Shade dependencies, oracles, wallets, external data sources, etc
  * Interoperability with other Shade Protocol contracts
* Documentation (15 points):
  * Clarity and completeness
  * Instructions for how to interact with contracts
* Testing (10 points):
  * Thoroughness of unit tests, integration tests, and stress tests.
* Innovation and Concept (10 points):
  * Innovative Features
  * Concept Feasibility
* Presentation and Communication (15 points):
  * Demo Quality
  * Communication

Total Scores out of 150 points.

***Rules and Guidelines***

* Collaboration: Foster a spirit of collaboration and teamwork. Share knowledge and ideas openly, and be willing to help and learn from others.
* Ethical Behavior: Abide by ethical standards and legal regulations. Do not engage in any form of cheating, plagiarism, or unethical conduct.
* Communication: Keep communication channels constructive and positive. Provide constructive feedback when appropriate, and be open to receiving feedback.
* Time Management: Manage your time effectively to meet deadlines and commitments. Be punctual for meetings, presentations, and project submissions.
* Intellectual Property: Respect intellectual property rights. Use open-source software and libraries responsibly, and ensure that you have the necessary permissions to use third-party resources.
* Code Quality: Write clean and well-documented code. Maintain coding standards and best practices.
* Demo and Presentation: Prepare a clear and concise demo or presentation of your project.
