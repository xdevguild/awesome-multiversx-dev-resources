# Awesome MultiversX Dev Resources

> MultiversX dev resources (previously Elrond)

## Contents

- [MultiversX official](#multiversx-official)
  - [Smart contracts](#smart-contracts)
  - [SDKs and dev tools](#sdks-and-dev-tools)
  - [Articles and tutorials](#articles-and-tutorials)
  - [Videos](#videos)
  - [Dev dApps](#dev-dapps)
  - [Explorers and APIs](#explorers-and-apis)
  - [Wallets](#wallets)
  - [Governance](#governance)
  - [Forum](#forum)
- [MultiversX community](#multiversx-community)
  - [Smart contracts](#smart-contracts-1)
  - [SDKs and dev tools](#sdks-and-dev-tools-1)
  - [Articles and tutorials](#articles-and-tutorials-1)
  - [Videos](#videos-1)
  - [Dev dApps](#dev-dapps-1)
  - [Dapps source code](#dapps-source-code)
  - [Explorers and APIs](#explorers-and-apis-1)
- [Paid MultiversX content and tools](#paid-multiversx-content-and-tools)
- [MultiversX Dev groups](#multiversx-dev-groups)
- [Contribute](#contribute)

## MultiversX official

Smart contracts, SDKs, dev libraries, articles, tutorials, and all other dev stuff.

### Smart contracts

- [Smart Contract examples](https://github.com/multiversx/mx-sdk-rs/tree/master/contracts/examples) - A bunch of useful smart contract examples from the MultiversX team
- [Metabonding](https://github.com/multiversx/mx-metabonding-sc)
- [Ethereum bridge](https://github.com/multiversx/mx-bridge-eth-sc-rs) - Smart Contracts on the MultiversX side for MultiversX-Ethereum bridge.
- [Exchange](https://github.com/multiversx/mx-exchange-sc) - These are the core Smart Contracts and the foundation exchange.
- [NFT Marketplace](https://github.com/multiversx/mx-nft-marketplace-sc)
- [NFT Collection Minter](https://github.com/multiversx/mx-nft-collection-minter-sc)
- [Liquid Staking](https://github.com/multiversx/mx-liquid-staking-sc)

### SDKs and dev tools

- [Wasm framework](https://github.com/multiversx/mx-sdk-rs) - Rust smart contract library designed for MultiversX VM. Also provides a debugging mode with mocks
- [Javascript SDK](https://github.com/multiversx/mx-sdk-js-core) - Official TS/JS SDK for interacting with the MultiversX Network and MultiversX Smart Contracts using Javascript (written in Typescript)
- [React Dapp SDK](https://github.com/multiversx/mx-sdk-dapp) - A library that holds the core functional logic of a dapp on the MultiversX
- [NextJS SDK](https://github.com/multiversx/mx-sdk-nestjs) - This package contains a set of utilities commonly used in the MultiversX Microservice ecosystem
- [Python SDK](https://github.com/multiversx/mx-sdk-py-cli) - Command line tools and Python SDK for interacting with the MultiversX Network and MultiversX Smart Contracts
- [Go SDK](https://github.com/multiversx/mx-sdk-go) - Go helpers and utilities for interacting with the MultiversX Blockchain
- [VSCode IDE](https://marketplace.visualstudio.com/items?itemName=Elrond.vscode-elrond-ide)
- [JS SDK examples](https://github.com/multiversx/mx-sdk-js-examples)

### Articles and tutorials

- [Specifications for mx-sdk-* libraries](https://github.com/multiversx/mx-sdk-specs)
- [Staking smart contract tutorial](https://docs.multiversx.com/developers/tutorials/staking-contract/)
- [The Crowdfunding Smart Contract](https://docs.multiversx.com/developers/tutorials/crowdfunding-p1/)
- [Rust Testing Framework](https://docs.multiversx.com/developers/developer-reference/rust-testing-framework/)
- [Build a dApp in 15 minutes](https://docs.multiversx.com/developers/tutorials/your-first-dapp/)
- [Build a Microservice for your dApp](https://docs.multiversx.com/developers/tutorials/your-first-microservice/)
- [JS SDK cookbook](https://docs.multiversx.com/sdk-and-tools/sdk-js/sdk-js-cookbook/)
- [Signing Providers for dApps](https://docs.multiversx.com/sdk-and-tools/sdk-js/sdk-js-signing-providers/)
- [The dynamic allocation problem](https://docs.multiversx.com/developers/best-practices/the-dynamic-allocation-problem/)
- [Smart contract API functions](https://docs.multiversx.com/developers/developer-reference/sc-api-functions)
- [Smart contract annotations](https://docs.multiversx.com/developers/developer-reference/sc-annotations)
- [Random Numbers in Smart Contracts](https://docs.multiversx.com/developers/developer-reference/sc-random-numbers/)
- [Storage Mappers](https://docs.multiversx.com/developers/developer-reference/storage-mappers)
- [Guard accounts](https://docs.multiversx.com/developers/guard-accounts/)
- [Relayed Transactions](https://docs.multiversx.com/developers/relayed-transactions/)
- [Reproducible Builds](https://docs.multiversx.com/developers/reproducible-contract-builds/)
- [Devcontainers](https://docs.multiversx.com/sdk-and-tools/devcontainers/)

### Videos
Please be aware that videos can be outdated. Always verify them with the docs.

- [How to build a dApp from scratch](https://www.youtube.com/watch?v=WYt92NSDXA8)
- [The Power of Smart Contracts Composability - DEX, Governance, Bridge](https://www.youtube.com/watch?v=BOyMNzsxeFI)
- [Building Hybrid Apps Between Web2 and Web3 Using MultiversX Libraries](https://www.youtube.com/watch?v=FO41nlIApu4)
- [Advanced Microservices Architecture](https://www.youtube.com/watch?v=l_hFxmrX-lI)
- [xSuite: Init, Build, Test, Deploy MultiversX contracts in seconds](https://www.youtube.com/watch?v=IQbtAVI-d5Y)
- [Introduction to ESDTs on MultiversX](https://www.youtube.com/watch?v=kyPMo6LPMc4)
- [MultiversX Unity tools](https://www.youtube.com/watch?v=kElMjlLxaAo)
- [Interact with MultiversX Blockchain using sdk-py](https://www.youtube.com/watch?v=xEj8S-d5wxs)
- [Interact with MultiversX Blockchain using sdk-js](https://www.youtube.com/watch?v=vAa1fxxmjYU)
- [Interact with MultiversX Blockchain using mxpy](https://www.youtube.com/watch?v=KeYP_oTlJH8)
- [Creating a React Native Wallet for Multiversx](https://www.youtube.com/watch?v=ORJp0wFCzFI)
- [How to write an SC on the MultiversX blockchain - Part 1](https://www.youtube.com/watch?v=BALVrahGeJ8)
- [How to write an SC on the MultiversX blockchain - Part 2](https://www.youtube.com/watch?v=VBj4H6B6N9k)
- [MultiversX VM general presentation - Part 1](https://www.youtube.com/watch?v=e2ZbxQ3kGoM)
- [MultiversX VM general presentation - Part 2](https://www.youtube.com/watch?v=x5ULIBNHyjg)
- [MultiversX Smart Contract Development Framework](https://www.youtube.com/watch?v=FwD9su3kTgU)
- [General microservices workshop at MultiversX](https://www.youtube.com/watch?v=6m4o_NkLP8o)
- [MultiversX introduction to sdk-dapp](https://www.youtube.com/watch?v=eMNIN5ip2w0)
- [MultiversX Smart Contract Testing Framework](https://www.youtube.com/watch?v=kgXtHBWU1-8)
- [MultiversX Developers Guide: Build your first Microservice](https://youtu.be/pd-vSIiw6Us)
- [Guide: create your first dApp on MultiversX Network in 15 minutes](https://youtu.be/IdkgvlK3rb8)
- [MultiversX IDE Presentation & Tutorial](https://youtu.be/bXbBfJCRVqE)

### Dev dApps

- [MultiversX dApp template](https://github.com/multiversx/mx-template-dapp) - The official dApp template provided by the MultiversX team using React.js & Typescript. It's a basic implementation of [@multiversx/sdk-dapp](https://www.npmjs.com/package/@multiversx/sdk-dapp), providing the basics for MultiversX authentication and TX signing.
- [NFT service](https://github.com/multiversx/mx-nft-service) - GraphQl service to provide information regarding NFTs and auctions on MultiversX Blockchain
- [xExchange service](https://github.com/multiversx/mx-exchange-service) - Decentralized Exchange Service based on GraphQL
- [Latest MultiversX Releases](https://multiversx.com/releases) - The feed to help you catch up with the latest releases
- [MultiversX Utils](https://utils.multiversx.com/) - This page offers an easy-to-use pack of utilities necessary for interacting with the MultiversX Blockchain
- [MultiversX Status page](https://status.multiversx.com/) - real-time status for public MultiversX services
- [Trusted Co-Signer Service](https://github.com/multiversx/mx-multi-factor-auth-go-service) - It is the component that automates most of the Guardian processes and makes it easy for users to turn wallets into unbreakable vaults

### Explorers and APIs

- [Devnet Explorer](https://devnet-explorer.multiversx.com)
- [Testnet Explorer](https://testnet-explorer.multiversx.com)
- [Mainnet Explorer](https://explorer.multiversx.com)
- [Devnet API](https://devnet-api.multiversx.com)
- [Testnet API](https://testnet-api.multiversx.com)
- [Mainnet API](https://api.multiversx.com)

### Wallets

- [Devnet Web wallet](https://devnet-wallet.multiversx.com/)
- [Testnet Web wallet](https://testnet-wallet.multiversx.com/)
- [Mainnet Web wallet](https://wallet.multiversx.com/)
- [xPortal App](https://xportal.com/) - mobile app
- [MultiversX Defi Wallet](https://chrome.google.com/webstore/detail/multiversx-defi-wallet/dngmlblcodfobpdpecaadgfbcggfjfnm) - browser extension

### Governance
- [Governance Voting Portal](https://governance.multiversx.com/) - Enabling ideas to turn into proposals as holders become governors of MultiversX.

### Forum
- [MultiversX Agora](https://agora.multiversx.com/) - The place of discussions and brainstorming sessions dedicated to the ongoing development, security, and expansion of the MultiversX Protocol.
- [xExchange Agora](https://agora.xexchange.com/) - Discuss all things related to xExchange. You can also post and discuss drafts of xExchange Improvement Proposals (xEIPs).

## MultiversX community
Smart contracts, SDKs, dev libraries, articles, tutorials, and all other dev stuff.

### Smart contracts

- [Elven Tools NFT Minter Smart Contract](https://github.com/ElvenTools/elven-nft-minter-sc) - Mint and sell NFT collections. It has features like issue collection, setting creation role, pause/unpause, random minting, giveaway, split minting into batches, and more.
- [Elven Tools SFT Minter Smart Contract](https://github.com/ElvenTools/elven-tools-sft-minter-sc) - SFT minter and vending machine smart contract
- [Simple Piggybank Smart Contract](https://github.com/xdevguild/multiversx-simple-sc) - smart contract for learning purposes
- [Middleman.nft Smart Contract](https://github.com/yum0e/middleman-nft) - Create or delete offers for a P2P exchange between two known users. Simple smart contract and its associated snippets.
- [Presale Smart Contract](https://github.com/xdevguild/elrond-pack-presale-sc) - Token Presale with Packs. Each pack has given EGLD amount and bonus percentage for the presale token
- [xBulk](https://github.com/defralcoding/xBulk) - smart contract for handling bulk transactions
- [eNftMemes Smart Contracts](https://github.com/eNftMemes/memes-sc) - Smart contracts code for the https://enftmemes.com. Includes decentralized voting, computing of a Top 10 based on votes, creating NFT & updating attributes, signature verification with example, etc
- [Multi Sender smart contract](https://github.com/xdevguild/sc-multi-sender-rs) - A multi-sender smart contract that allows you to send EGLD, ESDTs, and NFTs to multiple addresses in one transaction
- [ESDT Faucet SC](https://github.com/xdevguild/esdt-faucet-sc) - ESDT Faucet - claim, deposit ESDT tokens
- [Vesting SC](https://github.com/Moonlorian/vesting-dapp/tree/main/sc) - Token vesting smart contract 
- [CoinDrip Protocol](https://github.com/CoinDrip-finance/coindrip-protocol-sc) - Token (ESDT) streaming smart contract
- [Fundraising-SC](https://github.com/Vital-Network/Fundraising-SC) - MultiversX Fundraising Smart Contract allowing the creation of pots with or without objectives, with or without deadlines.
- [AshSwap Aggregator Smart Contract](https://github.com/ashswap/ash-aggregator-sc) - Aggregator smart contracts act as an intermediary router to exchange tokens between multiple protocols.
- [Nifty Maze & Proxy Ping Smart Contracts](https://github.com/NiftyWell/nifty-maze/tree/main) - smart-contract-based mini-game
- [Pulsar Money Smart Payment Contract](https://github.com/astrarizon/pulsar-contract) - Pulsar Money is dedicated to redefining digital transfers and offers a suit of Smart Payments Modules.
- [PublicFlashLoansSC](https://github.com/PierreBlg/PublicFlashLoansSC) - Flash Loans on top of MultiversX xExchange

### SDKs and dev tools

- [Rust SDK](https://github.com/bicarus-labs/elrond-sdk-erdrs) - Elrond Rust SDK for interacting with the Elrond Network and Smart Contracts.
- [Elven Tools CLI](https://github.com/ElvenTools/elven-tools-cli) - The CLI tool for deploying and interacting with the [Elven Tools NFT Minter SC](https://github.com/ElvenTools/elven-nft-minter-sc). But not only limited to that.
- [ESDT Distribution script](https://github.com/Combased/elrond-lkmex-distribution)
- [JS SDK with NextJS dapp template](https://github.com/xdevguild/nextjs-dapp-template)
- [JS SDK with VueJS dapp template](https://github.com/stephaneLeroy/vue-erdjs)
- [Elrondex](https://github.com/elrondex/elrondex) - Elixir library to interact with Elrond Blockchain
- [NextJS dApp template](https://github.com/Elrond-Giants/erd-next-starter) by [Elrond Giants](https://elrondgiants.com) - A dApp template made using JS SDK & nextjs
- [LKMEX airdrop](https://github.com/xdevguild/esdt-and-lkmek-airdrop-scripts) - Python script that performs an airdrop of LKMEX to NFT holders
- [Buildo Begins](https://github.com/xdevguild/buildo-begins) - CLI tool that uses JS SDK. Its primary purpose is to simplify interaction with the Elrond blockchain and smart contracts - sending tokens, issuing, also API interactions - custom filtering and exports (still WIP, but functional)
- [elrond-sft](https://www.npmjs.com/package/elrond-sft) by [Elrond Giants](https://elrondgiants.com) - A CLI tool you can use to execute SFT-related operations like issue token, set roles, mint, add quantity, burn, airdrops
- [erdjs-auth](https://github.com/Elrond-Giants/erdjs-auth) by [Elrond Giants](https://elrondgiants.com) - This library aims to make it easy to authenticate and sign transactions. It offers a common interface for all auth providers.
- [erd-react-hooks](https://github.com/Elrond-Giants/erd-react-hooks) by [Elrond Giants](https://elrondgiants.com) - This is a library of React hooks built for the MultiversX ecosystem. It aims to make it easy to authenticate, sign and send transactions, and query smart contracts.
- [elven.js](https://www.elvenjs.com) - The script for interactions with the protocol and smart contracts in the browser. No bundlers nor frameworks are required, just browser and script tag. Can be loaded from CDN
- [useElven](https://www.useelven.com) - React hooks for MultiversX blockchain. A set of tools for React-based apps using JS SDK. Integrates well with Next.js and Vite + React projects.
- [MultiversX Unity Tools](https://github.com/chainofindustry/MultiversXUnityTools) - A work-in-progress set of tools to interact with MultiversX Blockchain directly from a Unity app.
- [AssemblyScript framework for MultiversX VM](https://github.com/gfusee/elrond-wasm-as) - AssemblyScript smart contract library designed for Elrond's VM.
- [MultiversX SDK for Laravel](https://github.com/PeerMeHQ/mx-sdk-laravel) - MultiversX SDK for Laravel (written in PHP)
- [MultiversX SDK for PHP](https://github.com/PeerMeHQ/mx-sdk-php) - MultiversX SDK written in PHP.
- [PHP Network Providers API](https://github.com/PeerMeHQ/mx-sdk-php-network-providers) - Network Provider API components (compatible with mx-sdk-php)
- [Mx.NET.SDK](https://github.com/RemarkableTools/Mx.NET.SDK) - MultiversX .NET SDK: Complex library for interacting with MultiversX blockchain
- [Mx.NET.SDK.WalletProviders](https://github.com/RemarkableTools/Mx.NET.SDK.WalletProviders) - MultiversX .NET SDK: Unique library for interacting with Wallet Providers. Create connection and sign transactions.
- [Mx.Blazor.DApp](https://github.com/RemarkableTools/Mx.Blazor.DApp) - Blazor DApp is a template application built using the Blazor UI framework and ASP.NET Core server application
- [Rust Utilities by Angry-Penguins-Colony](https://github.com/Angry-Penguins-Colony/mx-rust-utilities) - Utilities to manipulate ManagedBuffer, ManagedVec and array
- [xNetwork](https://github.com/gfusee/xnetwork) - This project provides an easy way to run a local testnet of MultiversX and its associated API, with no configuration required
- [React + Vite dApp template](https://github.com/esdt-space/mx-dapp-template) - This template makes it easy to quickly get started building dApps on MultiversX, providing the basics for MultiversX authentication and transaction signing
- [MxOps](https://github.com/Catenscia/MxOps) - Python package to automate MultiversX smart contracts interactions
- [WenPlay](https://wenmoonstudios.com/wenplay/) - Unreal Engine 5 implementation of WalletConnect protocol with MultiversX blockchain interaction by WenMoon Studios
- [Golang SDK](https://github.com/stakingagency/sa-mx-sdk-go) - MultiversX Golang SDK by Staking Agency
- [MultiFungibleLibrary](https://dgomezde83.github.io/multifungible.github.io/index.html) - Cross-platform library written in C++ that allows to seamlessly create and manage non-fungible tokens (NFTs) and semi-fungible tokens (SFTs)
- [mx-xportalhub-chrome](https://github.com/stephaneLeroy/mx-xportalhub-chrome) - Chrome extension for testing XportalHub integration.
- [mxbi](https://github.com/VortX-DAO/mxbi) - mxbi is a command-line interface (CLI) tool that generates graphql backend code for MX smart contract endpoints
- [ABI2API](https://github.com/SkullElf/ABI2API) - ABI2API is a Python library for converting smart contract ABI (Application Binary Interface) on the MultiversX blockchain into a RESTful API
- [ABIExtractor](https://github.com/SkullElf/ABIExtractor) - ABI Extractor is a Python tool designed to extract ABI JSONs, and smart contract (SC) addresses from dApp JavaScript files.
- [Spring Boot Starter Reactive](https://github.com/crldev-software/multiversx-spring-boot-starter-reactive) - Spring Boot Starter project for integrating with the MultiversX Network, with the goal of achieving an effortless autoconfigured integration with the network.
- [xSuite](https://github.com/arda-org/xSuite) - Init, Build, Test, Deploy MultiversX smart contracts in seconds. The full suite for efficiently developing high-quality contracts.
- [NovaX](https://github.com/gfusee/novax) - NovaX is your go-to toolkit for building robust software seamlessly interacting with the MultiversX blockchain

### Articles and tutorials
Please be aware that articles can be outdated. Always verify them with the docs.

- [Linux environment for development](https://elrond-dev-guild.gitbook.io/scrolls/readme/linux-environment-for-development)
- [Setup the JS SDK workflow and issue an ESDT token in NodeJS environment](https://elrond-dev-guild.gitbook.io/scrolls/erdjs/how-tos/setup-erdjs-and-issue-esdt-token)
- [How to start with MultiversX blockchain development](https://www.julian.io/articles/how-to-start-with-multiversx.html)
- [Use of IPFS in the MultiversX NFT ecosystem](https://www.elven.tools/docs/use-of-ipfs-in-the-elrond-nft-ecosystem.html)
- [How to Interact With the MultiversX Blockchain in a Simple Static Website](https://hackernoon.com/how-to-interact-with-the-elrond-blockchain-in-a-simple-static-website)
- [How to enable donations on any website using the MultiversX blockchain and EGLD tokens](https://dev.to/juliancwirko/how-to-enable-donations-on-any-website-using-the-elrond-blockchain-and-egld-tokens-3fkf)
- [Fetching MultiversX API using Next.js](https://borispoehland.notion.site/borispoehland/Fetch-Elrond-API-using-Next-js-e5685a624d1546fdbee636b7cfa314ba)
- [AssemblyScript version of the Crowdfunding tutorial](https://fusee.gitbook.io/elrond-wasm-as/the-crowdfunding-smart-contract/the-crowdfunding-smart-contract-part-1) 
 - [How to generate a MultiversX wallet in a specific shard (Tech Tutorial)](https://blog.giantsvillage.com/how-to-generate-a-multiversx-wallet-in-a-specific-shard-tech-tutorial-458d565caed6)

### Videos
Please be aware that videos can be outdated. Always verify them with the docs.

- [MultiversX VSCode IDE extension walkthrough](https://youtu.be/y0beoihLppA)
- [How to run NFT collection on the MultiversX blockchain](https://youtu.be/resGP6a7_34)
- [Intro to Buildo Begins - the CLI that helps with MultiversX blockchain interactions](https://youtu.be/NijTSZhswns)
- [How to issue, mint and burn ESDT tokens on the MultiversX blockchain with Buildo CLI](https://youtu.be/_Jj0zCaATVU)
- [Create SFTs on the MultiversX Blockchain with Buildo CLI](https://youtu.be/ozOYli4qQx4)
- [How to mint a single NFT on the MultiversX blockchain with Buildo CLI](https://youtu.be/B4vahursgkQ)
- [Create Meta ESDTs on the MultiversX Blockchain with Buildo CLI](https://youtu.be/dsRswHhIteU)
- [Assign herotag (DNS) to your address with Buildo CLI](https://youtu.be/nvda-zCffck)
- [How to convert data types for MultiversX blockchain using Buildo CLI](https://youtu.be/soUq9eX9-0s)
- [Save a key-value data under your MultiversX account with Buildo CLI](https://youtu.be/gPVUkOgak1E)

### Dev dApps
Remember to always be careful when interacting with third-party dApps. Especially when it involves sending seeds, PEM, and keystore files. You should probably avoid that when interacting with the mainnet.

- [R3D4](https://r3d4.fr) - Faucet, ESDT tools, Stats
- [Converters for MultiversX Blockchain](http://207.244.241.38/elrond-converters) - This page offers an easy-to-use pack of data converters for interacting with MultiversX Blockchain.
- [XConverters](https://xconverters.netlify.app/) - Another app that offers data converters but is more automated with better UI/UX
- [MultiversX Transactioneer](https://elrond-transactioneer.vercel.app) - Create, Edit, Import, Export, Send & Batch Send transactions on any Elrond network.
- [ESDT Faucet](https://devnet-multiversx-esdt-faucet.netlify.app/) - Deposit and Claim ESDT tokens
- [xSafe Multisig UI](https://github.com/validblocks/xSafe) - This is the source code of the xSafe Multisig UI for the Multisig SC developed by the MultiversX team.
- [xSmartDeploy](https://devnet.xsmartdeploy.com/) - Deploy smart contracts through the web app
- [devnet.Buildo.dev](https://www.devnet.buildo.dev) - Buildo.dev is a MultiversX app that helps with blockchain interactions, like issuing, managing tokens, and querying smart contracts. (Mainnet also available).
- [Spawnable.io](https://spawnable.io/) - Fully automated deployments for your smart contracts & MML objects.

### Dapps Source Code

- [Middleman.nft](https://www.middleman-nft.com/) - A secure way to exchange NFTs with a smart contract that acts as a trusted third party. Open source code of the frontend [here](https://github.com/yum0e/front-nft-middleman).
- [Vesting dApp](https://github.com/Moonlorian/vesting-dapp/tree/main/dapp) - Token vesting dApp
- [Elven Tools Dapp](https://github.com/ElvenTools/elven-tools-dapp) - The dapp used by Elven Tools project
- [ESDT Faucet Dapp](https://github.com/xdevguild/esdt-faucet-dapp) - The ESDT tokens faucet app for the devnet/testnet
- [Buildo.dev](https://github.com/xdevguild/buildo.dev) - Buildo.dev is a MultiversX app that helps with blockchain interactions, like issuing, managing tokens and querying smart contracts.

### Explorers and APIs

- [Maiar Tokens API](https://maiartokens.com)
- [Elrond Scan](https://elrondscan.com)
- [Big Dipper Elrond Explorer](https://elrond.bigdipper.live)

## MultiversX Dev groups

- [MultiversX Discord](https://discord.com/channels/1045353153073258557/1049254556216872990)
- [MultiversX Developers Telegram group](https://t.me/MultiversXDevelopers)
- [MultiversX Fr Developers Discord](https://discord.gg/rt6XS8Eyrs)
- [StackOverflow](https://stackoverflow.com/questions/tagged/elrond)

## Paid MultiversX content and tools
Articles behind the paywall or tools that require payment to use them.

- [RockX](https://www.rockx.com/) - 3rd party MultiversX API provider, they also have limited free plans
- [Tatum](https://tatum.io) - 3rd party MultiversX API provider, they also have limited free plans
- [Blast](https://blastapi.io) - 3rd party MultiversX API provider, they also have limited free plans

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
