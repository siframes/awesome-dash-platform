# Awesome Dash Platform [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> Useful resources for using [Dash Platform](https://dashdevs.org) and building things on top of it

_This list is for projects, tools, or pretty much any things related to Dash Platform that are totally_ **awesome**_. This is for products which are already awesome - if you have plans for cool stuff to do with Dash, you should build it, and then link it here. If you have an idea for an awesome thing to do with Dash, a good place to ask about it might be in [ipfs/apps](https://github.com/ipfs/apps) or [ipfs/notes](https://github.com/ipfs/notes)._

## Table of Contents

- [Contribute](#contribute-to-this-list)
- [Articles](#articles)
- [DAPI](#dapi)
- [Dapps](#dapps)
- [Docs](#docs)
- [Tools](#tools)
- [Videos](#videos)
- [Bounties](#bounties)
- [Discussions](#discussions)
- [License](#license)

## Contribute to this list!

Everyone is welcome to submit their new Dash Platform item, but it will be accepted only if it meets our [content policy](https://github.com/andyfreer/awesome-dash-platform/blob/master/POLICY.md).

Readme and the website are automatically generated. In order to add an element to this list, you need to modify the files in `/data` and then run  `make build` before publishing your pull request. Read [contributing guidelines](https://github.com/andyfreer/awesome-dash-platform/blob/master/CONTRIBUTING.md) to learn how to do so.


## Articles

- 2021-03-08: [Release Announcement Dash Platform v0.18 on Testnet](https://blog.dash.org/release-announcement-dash-platform-v0-18-on-testnet-45f421a6bc98) - Dash Blog
- 2020-12-30: [Release Announcement Dash Platform v0.17 & DashPay on Testnet](https://blog.dash.org/release-announcement-dash-platform-v0-17-dashpay-on-testnet-13a85225902e) - Dash Blog
- 2020-09-30: [Release Announcement Dash Core v0.16 on Mainnet](https://blog.dash.org/release-announcement-dash-core-v0-16-on-mainnet-870aa327240b) - Dash Blog
- 2020-09-05: [Dash Platform v0.15 on Evonet](https://blog.dash.org/release-announcement-dash-platform-v0-15-on-evonet-88131f9c477b) - Dash Blog
- 2020-07-24: [Dash Platform v0.14 on Evonet](https://blog.dash.org/release-announcement-dash-platform-v0-14-on-evonet-9e02ad97d918) - Dash Blog
- 2020-06-14: [Dash Platform v0.13 on Evonet](https://blog.dash.org/release-announcement-dash-platform-v0-13-on-evonet-53c86b081b64) - Dash Blog
- 2020-04-23: [Announcing the Release of Dash Platform v0.12 on Evonet](https://blog.dash.org/announcing-the-release-of-dash-platform-v0-12-on-evonet-e611f2a93ce3) - Dash Blog
- 2020-03-18: [Announcing the Release of Dash Platform v0.11](https://blog.dash.org/announcing-the-release-of-dash-platform-v0-11-d1b7238ed0e6) - Dash Blog
- 2019-12-30: [Announcing the Release of Dash Platform on Evonet](https://blog.dash.org/announcing-the-release-of-dash-platform-on-evonet-c5a94dee0e59) - Dash Blog
- 2019-12-30: [Long-Awaited Dash Evolution Platform Released on Testnet](https://dashnews.org/long-awaited-dash-evolution-platform-released-on-testnet-with-developer-documentation-hub/) - Dash News
- 2019-12-18: [Edge Wallet Highlights Dash Evolution Update](https://dashnews.org/edge-wallet-highlights-dash-evolution-update-skeptical-on-store-of-value-analysis/) - Dash News
- 2019-12-09: [Ryan Taylor Explains Unique Pain Point Dash Platform Solves for Consumers and Merchants](https://dashnews.org/ryan-taylor-explains-unique-pain-point-dash-platform-solves-for-consumers-and-merchants/) - Dash News
- 2019-11-16: [Dash developers announced the timeline of  Evolution platform release](https://www.fxstreet.com/cryptocurrencies/news/dash-developers-announced-the-timeline-of-evolution-platform-release-201911161943) - FX Street
- 2019-10-17: [Introducing the Platform Chain](https://blog.dash.org/introducing-the-platform-chain-982fe6aea67f) - Dash Blog
- 2019-05-20: [An Introduction to Dash Platform, DAPI, and Drive](https://blog.dash.org/an-introduction-to-dash-platform-dapi-and-drive-9d080d6e89c9) - Dash Blog

## DAPI

- [Connecting to Evonet](https://dashplatform.readme.io/docs/tutorial-connecting-to-evonet) - The purpose of this tutorial is to walk through the steps necessary to access Dash's Decentralized API (DAPI)
- [Create and Fund a Wallet](https://dashplatform.readme.io/docs/tutorial-create-and-fund-a-wallet) - This tutorial explains how to generate a new wallet, retrieve an address from it, and transfer test funds to the address from a faucet.
- [DashJS](https://dashevo.github.io/js-dash-sdk/#/) - Connect to Dash from a Browser / NodeJS Server using Dash's Decentralized-API
- [Platform-UserID Secure Messaging Library](https://www.npmjs.com/package/dashmachine-crypto) - secure messaging between UserIDs (unique references to an individual name registration by an identity) from JS clients
- [Register a Data Contract](https://dashplatform.readme.io/docs/tutorial-register-a-data-contract) - In this tutorial we will register a data contract.
- [Register a Name for an Identity](https://dashplatform.readme.io/docs/tutorial-register-a-name-for-an-identity) - The purpose of this tutorial is to walk through the steps necessary to register a Dash Platform Name Service (DPNS) name.
- [Register an Identity](https://dashplatform.readme.io/docs/tutorial-register-an-identity) - Identities serve as the basis for interactions with Dash Platform. The purpose of this tutorial is to walk through the steps necessary to register a user identity.
- [Retrieve Documents](https://dashplatform.readme.io/docs/tutorial-retrieve-documents) - In this tutorial we will retrieve some of the current data from a data contract.
- [Send Funds](https://dashplatform.readme.io/docs/tutorial-send-funds) - Once you have a wallet and some funds, another common task is sending Dash to an address.
- [Submit Documents](https://dashplatform.readme.io/docs/tutorial-submit-documents) - Data is stored in the form of Documents which are entities encapsulated in a state transition before being submitted to DAPI.

## Dapps

- [Alphabetize Dash Core Wallet](https://github.com/dashpay/dash/issues/3614) - Alphabetize CLI --help output from the official Dash Core Wallet [Source](https://github.com/dashpay/dash/pull/3681)
- [C# DAPI Bindings](https://www.nuget.org/packages/dapi-client-csharp/) - Connect to Dash Platform using C# [Source](https://github.com/10xcryptodev/dapi-client-csharp)
- [Chrome Wallet](https://github.com/readme55/Dash-Chrome-Wallet) - Chrome extension for wallet, identity, and username creation, along with contract and document retrieval
- [Connecting Ethereum to Dash Platform](https://succinctsoftware.com/2020/10/18/using-dash-drive-for-storage-in-an-ethereum-app/) - Researching various ways to connect Ethereum to Dash Platform. [Source](https://github.com/DashBridge-io/scaffold-eth/tree/dash-eth-example)
- [Dapp Template](https://docs.google.com/document/d/1PKhUIwKzNQW0U-xGb5BOr-Yzz1j7BgRgtTxAxiBVWtc/edit#heading=h.wp6a615yo08k) - Best-practice reference implementation of how to build a Dash dapp, a static site alternative (no server required) to the Web Dapp Sample
- [Dapp-Dev Forum](https://discuss.dashdevs.org) - Developer-specific forum that keeps a permanent record of discussions, issues, solutions, etc. that other devs can find from a standard web search [Source](https://github.com/discourse/discourse)
- [Dash Incubator App](https://dashincubator.app/) - Continuous development to improve the Dash Incubator App itself, including scaling, incentives, autonomous operation, and developer on-boarding. [Source](https://github.com/DashIncubator/dash-incubator-app)
- [DashCraft](http://readme.dashdevs.org/minecraft-explorer/) - Store your MineCraft creations with this Dash-integrated Minecraft plugin, view them on any MineCraft explorer website
- [DashDevs.org Content](https://dashdevs.org) - Add content including images and other relevant information to the Articles, DAPI, Dapps, Docs, Tools or Videos sections on https://dashdevs.org [Source](https://github.com/andyfreer/awesome-dash-platform)
- [DashDevs.org Design](https://dashdevs.org/) - Improve the design of https://dashdevs.org [Source](https://github.com/andyfreer/awesome-dash-platform)
- [DashPay](https://github.com/dashevo) - Mobile Dapp enabling Username based payments and Platform authentication (WIP)
- [Data Oriented Tokens](https://github.com/readme55/dash-data-tokens) - Researching and implementing a method for creating Tokens only based on on-chain data and with off-chain validation.
- [DPNS](https://dashplatform.readme.io/docs/explanation-dpns) - Name Service Dapp providing Usernames for Dash Blockchain Identities (LIVE) [Source](https://github.com/dashevo/js-dpp/tree/v0.11-dev/schema/identity)
- [eCommerce Sample Dapp](http://checkout.dashevo.io) - eCommerce sample Dapp using EvoWallet and Point-of-Sale Dapp to showcase basic features. [Source](https://github.com/dashameter/dash-checkout)
- [EvoWallet](http://evowallet.io/) - PFast, easy, web-based Dash wallet that allows you to sign into Dash Platform apps like Jembe [Source](https://github.com/dashameter/evowallet)
- [Get Identity from Mnemonic](http://getidentity.dashmachine.net) - JavaScript library to input a mnemonic on a client, like a browser, and have the user identity returned from the network [Source](https://github.com/dashmachine/identity-from-mnemonic)
- [Golang DAPI Bindings](https://github.com/10xcryptodev/dapi-client-go) - Connect to Dash Platform using Golang
- [Java DAPI Bindings](https://dashincubator.app/output) - Connect to Dash Platform using Java
- [Jembe](http://jembe.dashevo.io/) - Decentralized Twitter Alternative Dapp. Join the Conversation [Source](https://github.com/dashameter/jembe)
- [Masternode Polling Tool (Proposal)](https://chat.dashdevs.org) - Polling Masternodes for Decisions (IDEA)
- [Merchant Directory (Proposal)](https://app.dashnexus.org/proposals/dash-platform-merchant-directory/overview) - Merchant Directory Dapp (PROPOSAL)
- [Platform Apps Video Demo](https://www.youtube.com/watch?v=yy8gO1C8fTs&ab_channel=DashMachine) - Demo reel video with narration explaining EvoWallet with InStore, Checkout and Jembe
- [Platform Console](http://console.dashevo.io/) - Dash Platform wallet, identity, username, contract, and document all from a web browser with no coding required [Source](https://github.com/dashameter/dash-platform-console)
- [Platform Explorer](https://pce.cloudwheels.net) - Blocks, transactions, and nodes on Dash Platform's L2/Tendermint evonet blockchain. [Source](https://github.com/cloudwheels/dappforce-tendermint-explorer)
- [Point-of-sale Dapp](http://instore.dashevo.io/) - Your local barista runs this point-of-sale app, you pay with EvoWallet, you leave with coffee [Source](https://github.com/dashameter/pos-dash)
- [Private Messenger Dapp](https://github.com/realKidDouglas/whatsdapp-lib) - Account-free Signal and Facebook Messenger alternative with developer tooling to build your own
- [Python DAPI Bindings](https://github.com/10xcryptodev/dapi-client-py) - Connect to Dash Platform using Python
- [Secure Messaging Library](https://www.npmjs.com/package/dash-secure-message) - Encryption, hashing, and other standardized modules for secure messaging between UserIDs for all Dapp types [Source](https://github.com/dashmachine/dash-secure-message)
- [Springboard](https://github.com/dashameter/springboard-cash/releases/tag/springboard%239) - Dash-based version of Flipstarter.Cash, a Bitcoin Cash-based decentralized crowdfunding platform
- [Web Dapp Sample](http://wds.dashmachine.net:8082/) - Proof-of-concept web application (HTML page served by a NodeJS server) enabling basic functions (signup and login to Dash, etc) running in conjunction with Chrome Wallet [Source](https://github.com/dashmachine/web-dapp-sample)

## Docs

- [Core Developer Guide](https://dashcore.readme.io/docs/core-guide-introduction) - Detailed docs for working with Dash's internal Core Network
- [Dash User Docs](https://docs.dash.org/en/stable/) - User documentation for understanding general Dash concepts & usage
- [DashJS](https://dashevo.github.io/js-dash-sdk) - JavaScript library for Dapp developers on Dash Platform
- [DIP 11](https://github.com/dashpay/dips/blob/master/dip-0011.md) - Dash Improvement Proposal (DIP) 11 on Identities
- [DIP 12](https://github.com/dashpay/dips/blob/master/dip-0012.md) - Dash Improvement Proposal (DIP) 12 on Dash Platform Name Service (DPNS)
- [DIP 13](https://github.com/dashpay/dips/blob/master/dip-0013.md) - Dash Improvement Proposal (DIP) 13 on Dash Platform Identities in Hierarchical Deterministic Wallets.
- [DIP 14](https://github.com/dashpay/dips/blob/master/dip-0014.md) - Dash Improvement Proposal (DIP) 14 Extended Key Derivation using 256-bit Unsigned Integers
- [DIP 15](https://github.com/dashpay/dips/blob/master/dip-0014.md) - Dash Improvement Proposal (DIP) 15 Introduces DashPay-related DIP 15.
- [DIP 16](https://github.com/dashpay/dips/blob/master/dip-0016.md) - Dash Improvement Proposal (DIP) 16 Headers First Synchronization on Simple Payment Verification Wallets.
- [Platform Developer Guide](https://dashplatform.readme.io/) - Guides and documentation to help you start working with Dash Platform as quickly as possible, as well as support if you get stuck.
- [Tendermint Core Docs](https://docs.tendermint.com/master/) - Docs for Tendermint, the BFT protocol used on Layer 2 in conjunction with Masternode quorums

## Tools

- [Block Explorer (L1)](http://insight.evonet.networks.dash.org:3001/insight/) - Core Network Blocks (Layer 1), for Currency, Identity and Credit Transactions [Source](https://github.com/dashevo/insight-ui)
- [Chrome Wallet](https://github.com/readme55/Dash-Chrome-Wallet/releases/tag/DashChromeWallet-v1.3) - An alternative Platform Wallet implementation created as an extension for Chrome / Firefox
- [DAPI Client C#](https://www.nuget.org/packages/dapi-client-csharp/) - Basic DAPI client in C# [Source](https://github.com/10xcryptodev/dapi-client-csharp)
- [DAPI Client Golang](https://github.com/10xcryptodev/dapi-client-go) - Basic DAPI client in Golang
- [DAPI Client Python](https://github.com/10xcryptodev/dapi-client-py) - Basic DAPI client in Python
- [Dash Masternode Deployment Tool](https://github.com/strophy/dash-masternode-docker) - This tool deploys a Dash masternode to the current host.
- [Dash Network Deploy](https://github.com/dashevo/dash-network-deploy) - This tool assists in deploying and managing Dash networks.
- [Evo Wallet (WIP)](http://evowallet.io/) - An alternative Platform Wallet implementation created as a pure Webapp [Source](https://github.com/evowallet/evowallet)
- [EvoNet Auto-Faucet](https://csb-k2nzi.netlify.app/) - Get EvoNet coins to test with (automated) [Source](https://github.com/riongull/dash-faucet-UI)
- [EvoNet Faucet](http://faucet.evonet.networks.dash.org/) - Get EvoNet coins to test with, uses captcha
- [Get Identitfy from mnemonic](http://getidentity.dashmachine.net/) - JS Library code to input a mnemonic on a client (including browser) and query/return the user identity from the network [Source](https://github.com/dashmachine/identity-from-mnemonic)
- [Pay-To-Username tipping POC](http://tipping.dashmachine.net/) - POC for one username to tip another blindly (without needing a contacting process or any communication between the usernames) [Source](https://github.com/dashmachine/tipping)
- [Platform Console](http://console.dashevo.io/#/wallet) - Explore & Update Platform State (WIP) [Source](https://github.com/denlb/dash-platform-console)
- [Platform Explorer (L2)](https://pce.cloudwheels.net/) - Platform chaion explorer plus State Transitions and user data [Source](https://github.com/dappforce/dappforce-tendermint-explorer)
- [Platform-UserID Secure Messaging Library](https://github.com/dashmachine/dash-platform-user) - Standardized modules for secure messaging between UserIDs (unique references to an individual name registration by an identity)

## Videos

- 2021-10-08: [Dash Podcast 182 with Dash Core Group Head of Business Development Ernesto Contreras](https://www.youtube.com/watch?v=Nu5qQ0ugFP8&ab_channel=DigitalCashNetwork) - Ernesto Contreras, the Head of Business Development for Dash Core Group, comes on the Dash Podcast to give the community an update on the organization's business development efforts for Dash.
- 2021-09-24: [Dash Podcast 181 with Dash Core Group CEO Ryan Taylor](https://www.youtube.com/watch?v=DAjhQQpt7IU&ab_channel=DigitalCashNetwork) - Ryan Taylor, CEO of the Dash Core team, comes on the Dash Podcast for a regular update and Q&A on the status of Dash.
- 2021-09-10: [Dash Podcast 180 with CrayPay and DashDirect CEO Marshall Greenwald](https://www.youtube.com/watch?v=-7fIAOjsyeY&ab_channel=DigitalCashNetwork) - Marshall G. CEO of CrayPay, the company behind the popular DashDirect app, comes on the Dash Podcast to answer any and all questions pertaining to the app and its roadmap.
- 2021-08-27: [Dash Podcast 179 with Rion Gull of the Dash Incubator and Dash Marketing Hub](https://www.youtube.com/watch?v=lLrvd5XLKF4&ab_channel=DigitalCashNetwork) - Rion Gull, head of the Dash Incubator and admin in the Dash Marketing Hub, comes on the Dash Podcast to talk about the bounty model revolution.
- 2021-08-13: [Dash Podcast 178 Darren Tapp of the Dash Investment Foundation](https://www.youtube.com/watch?v=Hn7Q-m-HdRE&ab_channel=DigitalCashNetwork) - Darren Tapp of the Dash Investment Foundation comes on the Dash Podcast to break down two the the biggest successes the DIF has had this year: Valkyrie and DashDirect.
- 2021-07-30: [Dash Podcast 177 with New Dash Core Group CTO Samuel Westrich](https://www.youtube.com/watch?v=1ALZfg2HqKM&ab_channel=DigitalCashNetwork) - Samuel Westrich, a.k.a. QuantumExplorer, the new CTO of Dash Core Group, comes on the Dash Podcast to talk his agenda as CTO, and all the new things we can expect.
- 2021-07-16: [Dash Podcast 176  with Mark Mason DashDirect, Dash Marketing Hub and More!](https://www.youtube.com/watch?v=FXwJA1vlpts&ab_channel=DigitalCashNetwork) - The incomparable Mark Mason comes on the Dash Podcast to talk, for once, about everything wrong with, and holding back, Dash.
- 2021-07-02: [Dash Podcast 175 with Dash Core Head of Marketing Arden Goldstein](https://www.youtube.com/watch?v=YyjkwmV0mlk&ab_channel=DigitalCashNetwork) - Dash Core Group's new head of marketing Arden Goldstein joins the Dash Podcast for a grand intro into the community.
- 2021-06-18: [Dash Podcast 174 with Dash Core CFO Glenn Austin](https://www.youtube.com/watch?v=V9HCX6-Gpjk&ab_channel=DigitalCashNetwork) - Glenn Austin, CFO of Dash Core Group, comes on the Dash Podcast to discuss all things finance and regulation surrounding Dash.
- 2021-06-04: [Dash Podcast 173 with Mike Lewis of the Dash Investment Foundation](https://www.youtube.com/watch?v=Y7rAr0Zfh98&ab_channel=DigitalCashNetwork) - Mike Lewis, Dash Investment Foundation supervisor, comes on the podcast to talk about the DIF in-depth and answer some questions.
- 2021-05-21: [Dash Podcast 172 with Dash Core Developer Pasta on Version 0.17 Releas](https://www.youtube.com/watch?v=wG-IS0LmF4I&ab_channel=DigitalCashNetwork) - Dash Core developer Pasta comes on the Dash Podcast immediately following the version 0.17 release to explain everything that's in it, and a whole lot more.
- 2021-05-07: [Dash Podcast 171 with Dash Core Group Front End Product Owner Brian Foster](https://www.youtube.com/watch?v=xWvQk4nSZZs&ab_channel=DigitalCashNetwork) - DFront End Product Owner for Dash Core Group Brian Foster comes on the podcast to introduce himself and talk about his role in Dash.
- 2021-04-23: [Dash Podcast 170 with Dash Platform Developer Ivan Shumkov](https://www.youtube.com/watch?v=pJ8FBbhhidg&ab_channel=DigitalCashNetwork) - Dash Platform developer Ivan Shumkov comes on the podcast to give a comprehensive overview of Dash Platform development up until the present time
- 2021-04-09: [Dash Podcast 169 with Albert Castellana of StakeHound](https://www.youtube.com/watch?v=h6rL5W6GLAI&ab_channel=DigitalCashNetwork) - Albert Castellana of StakeHound joins the Dash podcast to talk all things DeFi, particularly as it pertains to Dash.
- 2021-03-26: [Dash Podcast 168 with Mark Mason on What's New and Exciting in Dash](https://www.youtube.com/watch?v=wQmqNOm97EA&ab_channel=DigitalCashNetwork) - The incomparable Mark Mason comes back on the Dash Podcast to talk about the exciting things coming up in the world of Dash
- 2021-03-12: [Dash Podcast 167 with Dash Core Developer Pasta](https://www.youtube.com/watch?v=CwN_RDxcpOc&ab_channel=DigitalCashNetwork) - Dash Core Developer and wunderkind at large Pasta comes on the podcast to give an update on what the Core team has been working on with development.
- 2021-02-12: [Dash Podcast 165 Anton Suprunchuk on Dash Platform Deep Dive](https://www.youtube.com/watch?v=rqsWTYbo2Vo&ab_channel=DigitalCashNetwork) - Dash developer Anton Suprunchuk comes on the Dash Podcast to go into a comprehensive deep dive on Dash Platform.
- 2021-02-04: [Be a Dash developer by joining Dash Incubator and get paid!](https://youtu.be/eWqgRw46kH0) - This is a Dash Incubator promotion video.
- 2021-01-14: [New Dash Investment Could Revolutionize the Whole Cryptocurrency Ecosystem](https://www.youtube.com/watch?v=DyTZhMTEFpI&ab_channel=DigitalCashNetwork) - The Dash Investment Foundation just made an investment in retail savings app CrayPay. This is why it could have an huge impact on the crypto world.
- 2021-01-01: [Dash Podcast 162 Dash Developer Alex Werner on Platform "Evolution" Testnet Release!](https://www.youtube.com/watch?v=ajx88zPKYNs&ab_channel=DigitalCashNetwork) - Dash developer Alex Werner comes on the podcast to talk about Dash Platform testnet release and what it means.
- 2020-10-02: [What is Dash's Decentralized API? (DAPI) | Dash Platform](https://www.youtube.com/watch?v=S0pq-qOu9cQ) - This is episode 3 of a 5 part video series on Dash Platform.
- 2020-09-25: [What is Dash Drive? | Dash Platform](https://www.youtube.com/watch?v=14N5pnl5W0Y) - This is episode 2 of a 5 part video series on Dash Platform.
- 2020-09-18: [Dash is Becoming a Cloud | Dash Platform](https://www.youtube.com/watch?v=9WqUMrIN58Q) - This is episode 1 of a 5 part video series on Dash Platform.
- 2020-09-05: [Demo of DashPay Contacts and Notifications](https://www.youtube.com/watch?v=pQ3_Q45HdOA) - This demo shows the contacts and notifications feature in the upcoming Dashpay wallet.
- 2020-08-17: [Dash Dapps - Demoing Community Development on EvoNet](https://www.youtube.com/watch?v=yy8gO1C8fTs) - Demonstrating community projects built on Dash EvoNet during phase 2 of the Dash Platform Incubator proposal.
- 2020-08-06: [Let's Talk Dash Dapps feat. Sample Dapps & Wallet API (Ep 2)](https://www.youtube.com/watch?v=76pYX44o_j8&t=7s) - Second Episode of Let's Talk Dash Dapp's. Readme looks at him Sample Dapps Collection that is communicating with Chrome Wallet API to submit data.
- 2020-07-28: [Let's Talk Dash Dapps feat. Chrome Wallet (Ep 1)](https://www.youtube.com/watch?v=IjjsQNd3Zto) - First Episode of Let's Talk Dash Dapp's. A comprehensive introduction to Dash Platform Decentralized-API (DAPI), Usernames and Data-Contracts.
- 2020-06-23: [Why Dash's New Username Demo Video Is Game-Changing](https://lbry.tv/@DigitalCashNetwork:c/DashUsernames:5?r=Gd7GBo8adnW7dSEBDc2pPP8Ytw9Rw3L9) - Recently Dash released a new demo video showing off usernames and how they're registered in the soon-to-be-released DashPay app, the first part of the long-awaited Evolution update, now called Dash Platform.
- 2020-06-19: [DashPay Username Registration Demo](https://www.youtube.com/watch?v=GtTaezpxQOs) - A demo of the DashPay Username Registration Process.
- 2020-01-06: [DASH EvoNet Review](https://www.youtube.com/watch?v=Vs3cjw51o4w) - Today we are taking a look at the Dash Evonet which is a development network provided for experimentation and evaluation of Dash Platform features.
- 2019-12-11: [Introduction To Dash Platform - Dana Alibrandi](https://www.youtube.com/watch?v=WNoMSP0nPDQ) - Dana Alibrandi introduces Dash Platform and its functionality
- 2019-12-11: [DashPay Wallet - Brian Foster](https://www.youtube.com/watch?v=wkBFcWbsXtQ) - Brian Foster describes the development and features of the "Evolution" DashPay Wallet
- 2019-12-11: [Dash Evolution Open House Analysis | Tao & Amanda LIVE!](https://www.youtube.com/watch?v=PFIOm9KO5sA) - Join the team from Dash Core Group for an open discussion of the upcoming Dash Platform and Dashpay-enabled wallets release, commonly known as Evolution.
- 2019-12-09: [Dash Evolution Open House 2019](https://www.youtube.com/watch?v=ie7fJMw5WIo) - Join the team from Dash Core Group for an open discussion of the upcoming Dash Platform and Dashpay-enabled wallets release, commonly known as Evolution.
- 2019-11-22: [What is Dash Platform?](https://www.youtube.com/watch?v=8jI7Nt3lILs) - The Cryptoviser analysis of Dash Platform
- 2019-10-31: [Understanding Dash Platform and Chain - Expert Followup](https://www.youtube.com/watch?v=Vb3KwVxPE84) - Christopher sits down with Dash Product Manager Dana Alibrandi and Dash Core Developer Ivan Shumkov to get into more technical details about the Dash Platform's concepts
- 2019-10-12: [Dash Platform - Dana Alibrandi and Ivan Shumkov](https://www.youtube.com/watch?v=5Q1cCt9v1U0) - Dana Alibrandi, Dash Platform Product Owner, Dash Core Group Ivan Shumkov, Dash Platform Engineer, Dash Core Group
- 2019-07-12: [Dash Podcast 112 - Intro To Dash Platform feat. Dana Alibrandi](https://www.youtube.com/watch?v=VcLdDmt9TSM) - Intro To Dash Platform feat. Dana Alibrandi Product Owner from Dash Core Group
- 2019-04-19: [Dash Podcast 100 - Feat. Ivan Shumkov](https://www.youtube.com/watch?v=gUDN62ePWms) - Intro To Dash Platform feat. Dana Alibrandi Product Owner from Dash Core Group
- 2018-05-15: [Platform Prototype Demo 3](https://www.youtube.com/watch?v=ZJVW9iUHqLg) - Chuck, Suba, and Chris from Dash Core demonstrate three exploratory designs for the Dashpay DAP demo home screen
- 2018-04-25: [Platform Prototype Demo 2](https://www.youtube.com/watch?v=EtYax7iz4hU) - Dash Core developers Joshua, Chuck, and Suba demonstrate the 2nd prototype of the first Dash decentralized application, show off some mobile app designs, and demonstrate the VMN block explorer.
- 2018-03-16: [Platform Prototype Demo 1](https://www.youtube.com/watch?v=gbjYhZT2Ulc) - Dash Core developers Joshua and Chuck demonstrate a prototype of the first Dash decentralized application and show some technical details of the Dash Evolution platform

## Bounties

- [Approach external R&D services](https://trello.com/c/Rj0tLQ8p/123-approach-external-rd-services) 
- [Atomic Swaps](https://trello.com/c/o9l91FLG/96-atomic-swaps) 
- [Attention Tipping Extension](https://trello.com/c/iwObyp5p/136-attention-tipping-extension) 
- [Community EvoNet MN Hosting](https://trello.com/c/rzjc7eY1/26-community-evonet-mn-hosting) 
- [DAPI Decentralized-HTTPS POC](https://trello.com/c/99FAe1iC/39-dapi-decentralized-https-poc) 
- [Dapp Signing](https://trello.com/c/JvbLYmew/76-dapp-signing) 
- [Dash Artwork Contest](https://trello.com/c/k7o4ZYb2/128-dash-artwork-contest) 
- [Dash Incubator App V2](https://trello.com/c/Fx1l1CvO/130-dash-incubator-app-v2) 
- [DASH Lolli Extension](https://trello.com/c/dg5arOrq/153-dash-lolli-extension) 
- [DASH Patreon Alternative](https://trello.com/c/JaCCRWky/125-dash-patreon-alternative) 
- [Dash Platform Projects Upgrade](https://trello.com/c/uFaCFImX/65-dash-platform-projects-upgrade) 
- [DASH Provably Fair RNG Game](https://trello.com/c/AsywEE5W/148-dash-provably-fair-rng-game) 
- [DashDapps Website](https://trello.com/c/7uE2YcMU/112-dashdapps-website) 
- [DASHDevs.Org Getting Started](https://trello.com/c/pxG8kpDr/147-dashdevsorg-getting-started) 
- [DashNews App](https://trello.com/c/SaN50j1F/140-dashnews-app) 
- [DashPay Extension](https://trello.com/c/dCjtC7JH/124-dashpay-extension) 
- [DashPay JS](https://trello.com/c/9RzFdmbB/116-dashpay-js) 
- [DashPay JS Programme](https://trello.com/c/EvTk6oYo/144-dashpay-js-programme) 
- [Data Oriented Tokens](https://trello.com/c/eJCQLBUf/98-data-oriented-tokens) 
- [Decentralized Identity (DID)](https://trello.com/c/6iAm9pjk/40-decentralized-identity-did) 
- [Decentralized TLS/HTTPS for DAPI](https://trello.com/c/99FAe1iC/39-decentralized-tls-https-for-dapi) 
- [Distributed Thumbnail Image Service](https://trello.com/c/TAVGPNOX/156-distributed-thumbnail-image-service) 
- [EvoWallet](https://trello.com/c/MJrfbOp3/33-evowallet) 
- [Freelancer Dapp](https://trello.com/c/xHKvn8xW/138-freelancer-dapp) 
- [Governance Portal](https://trello.com/c/c36t7QSM/141-governance-portal) 
- [Incubator Templates](https://trello.com/c/p61W3mjP/151-incubator-templates) 
- [Integrating Dash into 3rd-Party Software](https://trello.com/c/GE5g9iHq/87-integrating-dash-into-3rd-party-software) 
- [Jembe Dapp](https://trello.com/c/Kzn8JX12/12-jembe-dapp) 
- [Jembe Dapp](https://trello.com/c/Kzn8JX12/12-jembe-dapp) 
- [Linktree Alternative](https://trello.com/c/2SHTEqG3/129-linktree-alternative) 
- [Machine Learning Micropayments](https://trello.com/c/zciecaSV/137-machine-learning-micropayments) 
- [Masternode Multi-Party Payouts](https://trello.com/c/iGoVoTb3/107-masternode-multi-party-payouts) 
- [MN Trustless Shares](https://trello.com/c/Y3MRKnPj/127-mn-trustless-shares) 
- [Official Platform Block Explorer](https://trello.com/c/M5phs7NJ/119-official-platform-block-explorer) 
- [Password + Public-Private-Key Manager](https://trello.com/c/S48CSFL4/111-password-public-private-key-manager) 
- [Payments API](https://trello.com/c/pincRNBU/134-payments-api) 
- [Platform Console](https://trello.com/c/Xezls3IC/9-platform-console) 
- [Platform Explorer](https://trello.com/c/ezAfj6lG/18-platform-explorer) 
- [Platform-UserID Secure Messaging Library](https://trello.com/c/qPtO4KF9/42-platform-userid-secure-messaging-library) 
- [Private Messenger Dapp](https://trello.com/c/LUyEnwJ9/46-private-messenger-dapp) 
- [Research Smart-Contract Integration](https://trello.com/c/VqEmk1dh/53-research-smart-contract-integration) 
- [StrawPoll Dapp](https://trello.com/c/HxGanCjQ/146-strawpoll-dapp) 
- [TenderDash Development](https://trello.com/c/uYNFyFp7/150-tenderdash-development) 
- [Tendermint backports (Go programing language)](https://trello.com/c/yM9JfDEX/104-tendermint-backports-go-programming-language) 
- [THORChain Integration](https://trello.com/c/CDKTVi9x/152-thorchain-integration) 

## Discussions

* [Join us on Discord!](https://chat.dashdevs.org)

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
