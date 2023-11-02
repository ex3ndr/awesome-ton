<!-- omit from toc --> 
# Awesome TON (The Open Network) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) 

[<img src="logo/ton_symbol.svg" align="right" width="100">](https://ton.org)

[![Twitter](https://img.shields.io/twitter/follow/ton_blockchain?style=social)](https://twitter.com/ton_blockchain)
[![Telegram](https://img.shields.io/badge/telegram-TON%20Dev%20Chat-blue?logo=telegram)](https://tondev_eng.t.me)

Welcome to Awesome TON - a carefully curated compendium of standout libraries, tools, services, protocols, and smart contracts associated with the TON ecosystem. 

---

<!-- omit from toc --> 
## Contents

- [🏛️ Official Resources](#️-official-resources)
- [🎓 Education](#-education)
  - [Basic Theory](#basic-theory)
  - [YouTube Educational Videos](#youtube-educational-videos)
  - [Community Tutorials](#community-tutorials)
  - [Smart Contract Examples](#smart-contract-examples)
  - [Guidelines](#guidelines)
- [🗣 Talks \& Workshops](#-talks--workshops)
- [🧑‍💻 Get coding](#-get-coding)
  - [Dev Tools](#dev-tools)
  - [Libraries](#libraries)
  - [Get help](#get-help)
- [🗂 Projects](#-projects)
  - [Decentralized exchanges](#decentralized-exchanges)
  - [Marketplaces](#marketplaces)
  - [Explorers](#explorers)
  - [Bridges](#bridges)
  - [Wallets](#wallets)
  - [Staking](#staking)
- [🌐 Authentication](#-authentication)
- [💵 Funds](#-funds)
- [🎛 Utilities](#-utilities)
- [👨‍🎨 UX/UI](#-uxui)
- [✏️ Contribute](#️-contribute)

---

## 🏛️ Official Resources
- [Documentation](https://docs.ton.org/)
- [Community blog](https://blog.ton.org/)
- [Hackathons, contests](https://ton.org/events)
- [List of actual vacancies](https://jobs.ton.org/)
- [@ton_community in Telegram](https://t.me/toncoin)

---

## 🎓 Education
### Basic Theory
- [The Open Network](https://docs.ton.org/learn/introduction)
- [What is blockchain? What is a smart contract? What is gas?](https://blog.ton.org/what-is-blockchain)
- [Smart Contract Addresses](https://docs.ton.org/learn/overviews/addresses)
- [Six unique aspects of TON Blockchain that will surprise Solidity developers](https://blog.ton.org/six-unique-aspects-of-ton-blockchain-that-will-surprise-solidity-developers)
- [TON Sites, TON WWW, TON Proxy](https://blog.ton.org/ton-sites)

### YouTube Educational Videos
- [Ton Dev Study channel](https://www.youtube.com/@WikiMar/playlists)
  - English
    - [FunC & Blueprint](https://www.youtube.com/playlist?list=PLyDBPwv9EPsDjIMAF3XqNI2XGNwdcB3sg)
    - [TON Development with Fift](https://www.youtube.com/playlist?list=PLyDBPwv9EPsB47mqzF4Z9K8k6HYqPv6Px)
    - [TON Development with Python](https://www.youtube.com/playlist?list=PLyDBPwv9EPsDrQUyuHTsKRzxg6XaTPzhh)
    - [Tact & Blueprint](https://www.youtube.com/@AlefmanVladimirEN-xb4pq/videos)
  - Russian
    - [FunC & Blueprint](https://www.youtube.com/playlist?list=PLyDBPwv9EPsA5vcUM2vzjQOomf264IdUZ)
    - [TON Connect - Integration in TON Ecosystem](https://www.youtube.com/playlist?list=PLyDBPwv9EPsCJ226xS5_dKmXXxWx1CKz_)
    - [TON Development with Python](https://www.youtube.com/playlist?list=PLyDBPwv9EPsC-7xbn8b8noZh9a1Xkg42W)
    - [TON Development with GO](https://www.youtube.com/playlist?list=PLyDBPwv9EPsCV-GifFVIQ1o3t35j1nj-u)
    - [TON Development with Fift](https://www.youtube.com/playlist?list=PLyDBPwv9EPsCYG-hR4N5FRTKUkfM8POgh)
- [Mark Okhman](https://www.youtube.com/@markokhman) 
- [Ton Dev Moscow channel](https://www.youtube.com/@tondevmoscow/featured)


### Community Tutorials
- Smart Contracts and dApps
  - [Get Started with TON](https://docs.ton.org/develop/onboarding-challenge) 
  - Ton-Community Hello World
    - [Step by step guide for working with your first TON wallet](https://ton-community.github.io/tutorials/01-wallet/)
    - [Step by step guide for writing your first smart contract](https://ton-community.github.io/tutorials/02-contract/)
    - [Step by step guide for building your first web client](https://ton-community.github.io/tutorials/03-client/)
    - [Step by step guide for testing your first smart contract](https://ton-community.github.io/tutorials/04-testing/)
  - [Func Journey](https://blog.ton.org/func-journey)
  - FunC @romanovichim lessons
    - [TonFunClessons_Eng](https://github.com/romanovichim/TonFunClessons_Eng)
    - [TonFunClessons_ru](https://github.com/romanovichim/TonFunClessons_ru)
  - [Learn Func in 10 minutes](https://learnxinyminutes.com/docs/func/)
  - [How to work with wallet smart contracts](https://docs.ton.org/develop/smart-contracts/tutorials/wallet)
  - [How to make a simple multisig contract](https://docs.ton.org/develop/smart-contracts/tutorials/multisig)
  - [Unlocking the Power of TON with Rift Framework](https://blog.ton.org/rift-announcement)
  - [Interact with multisig wallets using TypeScript](https://docs.ton.org/develop/smart-contracts/tutorials/multisig-js)
- FT(Jettons) & NFT
  - [Step by step NFT collection minting](https://docs.ton.org/develop/dapps/tutorials/collection-minting)
  - [Mint your first Jetton](https://docs.ton.org/develop/dapps/tutorials/jetton-minter)
- Telegram bot
  - [Storefront bot with payments in TON](https://docs.ton.org/develop/dapps/tutorials/accept-payments-in-a-telegram-bot)
  - [Bot with own balance](https://docs.ton.org/develop/dapps/tutorials/accept-payments-in-a-telegram-bot-2)
  - [Bot for sales of dumplings](https://docs.ton.org/develop/dapps/tutorials/accept-payments-in-a-telegram-bot-js)
- Ton Connect
  - [Integration manual](https://docs.ton.org/develop/dapps/ton-connect/integration)
  - [Telegram bot integration](https://docs.ton.org/develop/dapps/ton-connect/tg-bot-integration)
  - [Sending messages](https://docs.ton.org/develop/dapps/ton-connect/transactions)

### Smart Contract Examples
- [Smart Contract Examples](https://docs.ton.org/develop/smart-contracts/examples)

### Guidelines
- Smart Contract Development
  - [Overview](https://docs.ton.org/develop/smart-contracts/guidelines)
- Develop Apps
  - [Payments processing](https://docs.ton.org/develop/dapps/asset-processing/)
  - [TON Jetton processing](https://docs.ton.org/develop/dapps/asset-processing/jettons)
  - [TON NFT processing](https://docs.ton.org/develop/dapps/asset-processing/nfts)
  - [TON Metadata Parsing](https://docs.ton.org/develop/dapps/asset-processing/metadata)
- TON Connect (Integration)
  - [TON Connect for Developers](https://docs.ton.org/develop/dapps/ton-connect/developers)
  - [TON Wallet Guidelines](https://docs.ton.org/develop/dapps/ton-connect/wallet-guidelines)
  - [TON Connect Workflow](https://docs.ton.org/develop/dapps/ton-connect/workflow)

---



## 🗣 Talks & Workshops

- [TON & Company](https://www.youtube.com/@ton-company/featured) - By [@markokhman](https://t.me/markokhman)
- [TON - The Open Network](https://www.youtube.com/@the_open_network/featured)
- [DoraHacks workshops](https://www.youtube.com/playlist?list=PLpkpEL9gYGez8hCtzMtOabQPX9bgYLZPN)

---

## 🧑‍💻 Get coding

### Dev Tools
- [Blueprint](https://github.com/ton-community/blueprint/) - A development environment for writing, testing, and deploying smart contracts.
- [Testnet Faucet](https://t.me/testgiver_ton_bot) - Bot for getting testnet TON.
- [TON Dev Wallet](https://github.com/TonDevWallet/TonDevWallet) - Wallet for developers.
- [Rift](https://github.com/sky-ring/rift) - Python framework for building smart contracts.
- [Tact](https://tact-lang.org/) - High-level language for TON smart-contracts.
- [ton-k8s](https://github.com/disintar/ton-k8s) - Self-hosted TON network with Docker images for compose and kubernetes.
- IDE Plugins 
  - [VS Code plugin](https://marketplace.visualstudio.com/items?itemName=tonwhales.func-vscode)
  - [IntelliJ IDEs Plugin](https://plugins.jetbrains.com/plugin/18541-ton-development)
  - [Sublime Text plugin](https://github.com/savva425/func_plugin_sublimetext3)
- API
  - [toncenter.com](https://toncenter.com/) - Fast and reliable HTTP API for The Open Network.
  - [dton.io/graphql](https://dton.io/graphql)
  - [tonapi.io](https://tonapi.io/)
  - [anton.tools](https://anton.tools/)
- Telegram Web Apps (TWAs)
  - [Telegram WebApps Documentation](https://core.telegram.org/bots/webapps) - Full description on Telegram website.
  - [docs.twa.dev](https://docs.twa.dev/) - User-friendly docs from community.
  - [ton-community/twa-template](https://github.com/ton-community/twa-template) - Template for a new TWA interacting with the TON.
  - [twa-dev/boilerplate](https://github.com/twa-dev/Boilerplate) - Another boilerplate for a new TWA.
  - [twa-dev/sdk](https://github.com/twa-dev/sdk) - npm package for TWA SDK.
  - [twa-dev/Mark42](https://github.com/twa-dev/Mark42) - Mark42 is a simple lightweight tree-shakable UI library for TWA.

### Libraries
- Python
  - [disintar/tonpy](https://github.com/disintar/tonpy) - Python SDK with full TLB support, Emulator and TVM.
  - [yungwine/pytoniq](https://github.com/yungwine/pytoniq) - Python SDK with native LiteClient, tlb wrappers and cells.
  - [tonfactory/tonsdk](https://github.com/tonfactory/tonsdk) - Library with cells implementation and popular contract wrappers.
  - [toncenter/pytonlib](https://github.com/toncenter/pytonlib) - Tonlib wrapper.
  - [yungwine/TonTools](https://github.com/yungwine/TonTools) - High-level library with http/adnl interaction with liteservers.
- JavaScript
  - [ton-core/ton](https://github.com/ton-core/ton) - Cross-platform client for TON blockchain, by ton-core.
  - [toncenter/tonweb](https://github.com/toncenter/tonweb) - Cross-platform client for TON blockchain, by TonCenter.
  - [orbs-network/ton-access](https://github.com/orbs-network/ton-access) - Unthrottled anonymous RPC access to TON blockchain.
- Go
  - [xssnick/tonutils-go](https://github.com/xssnick/tonutils-go)
  - [tonkeeper/tongo](https://github.com/tonkeeper/tongo)
  - [Golang TonLib wrapper](https://github.com/ton-blockchain/tonlib-go)
- [Dart/Flutter SDK](https://github.com/novusnota/tonutils-dart) - Comprehensive Dart/Flutter SDK for TON Blockchain.
- [Rust SDK](https://github.com/ston-fi/tonlib-rs)
- [C++ TonLib](https://github.com/ton-blockchain/ton/tree/master/example/cpp)
- [Java TonLib wrapper (JNI)](https://github.com/ton-blockchain/tonlib-java)
- [labraburn/SwiftyTON](https://github.com/labraburn/SwiftyTON) - Native Swift wrapper for tonlib with async/await.
- [labraburn/node-tonlib](https://github.com/labraburn/node-tonlib) - C++ addon for Node.js to work with tonlibjson.
- [ton-kotlin](https://github.com/andreypfau/ton-kotlin) - Kotlin SDK for TON blockchain.
- [TonSdk.NET](https://github.com/continuation-team/TonSdk.NET) - Native C# (.NET, Unity) SDK for TON Blockchain.

### Languages
- Tact
  - [Tact main repository](https://github.com/tact-lang)
  - [Official tact resources](https://tact-lang.org/)
  - [Tact by example](https://tact-by-example.org/)
  - [Tact awesome curated list](https://github.com/tact-lang/awesome-tact)
  - [Tact youtube video course RU](https://youtube.com/playlist?list=PLyDBPwv9EPsAJpR7R0cC4kgo7BjiMmUy7&feature=shared)

### Get help
- [TON Overflow](https://answers.ton.org)
- [English developers chat](https://t.me/tondev_eng)
- [Russian developers chat](https://t.me/tondev)
- [Chinese developers chat](https://t.me/tondev_zh)

---

## 🗂 Projects
### Decentralized exchanges
- [dedust.io](https://dedust.io/)
- [STON.fi](https://app.ston.fi)
- [DeDust](https://dedust.io/swap)
- [Megaton Finance](https://megaton.fi)

### Marketplaces
- [Fragment](https://fragment.com/)
- [GetGems](https://getgems.io/)
- [ton.diamonds](https://ton.diamonds/)
- [disintar.io](https://disintar.io/)

### Explorers
- [tonscan.org](https://tonscan.org/)
- [dton.io](https://dton.io/)
- [tonviewer.com](https://tonviewer.com/)
- [explorer.tonnft.tools](https://explorer.tonnft.tools/)
- [tonlens.com](https://tonlens.com)
- [TonWhales](https://tonwhales.com/explorer)
- [3xpl](https://3xpl.com/ton)
- [explorer.toncoin.org](https://explorer.toncoin.org)
- [ton.cx](https://ton.cx)

### Bridges 
- [bridge.ton.org](https://bridge.ton.org/)
- [Orbit Bridge](https://bridge.orbitchain.io/)
- [tonana.org](https://app.tonana.org/)

### Wallets 
- [Tonkeeper](https://tonkeeper.com)
- [TonHub](https://tonhub.com)
- [@wallet](https://t.me/wallet) - TON wallet right in the Telegram.
- [Ton Android](https://play.google.com/store/apps/details?id=ton.coin.wallet) - Official Android wallet.
- [TON Wallet](https://wallet.ton.org/) - Official Web Wallet.
- [ton-cli](https://github.com/ex3ndr/ton-cli) - CLI wallet.
- [MyTonWallet](https://mytonwallet.io) - Web wallet and browser extension for TON.
- [Juston](https://juston.io) - iOS wallet.
- [Coin98 Wallet](https://wallet.coin98.com) - A mobile and browser extension wallet with multi-chain support.
- [openmask.app](https://www.openmask.app/) - MetaMask analog for The Open Network.
- [Ton iOS](https://apps.apple.com/by/app/toncoin-wallet/id1560210939) - Official iOS wallet.

### Staking
- [TON Liquid Staking protocol](https://ton-ls-protocol.gitbook.io/ton-liquid-staking-protocol/) - Design guidelines of the TON Liquid Staking for developers.
- [TonWhales staking](https://tonwhales.com/staking)
- [The list of the TON nominator pools](https://tonvalidators.org/)

---

## 🌐 Authentication
- [Ton Connect](https://github.com/ton-connect/) - Standart protocol for communication between wallets and apps.
- [delab-team/connect](https://github.com/delab-team/connect) - SDK, which combines multiple protocols in one modal.
- [@tonconnect/sdk](https://www.npmjs.com/package/@tonconnect/sdk) - JS SDK for TON Connect 2.0.
- [pytonconnect](https://pypi.org/project/pytonconnect/) - Python SDK for TON Connect 2.0.
- [darttonconnect](https://github.com/romanovichim/dartTonconnect) - Dart SDK for TON Connect 2.0.

---

## 💵 Funds
- [Toncoin Fund](https://www.toncoin.fund/)
- [Tonstarter](https://tonstarter.com/hi/)


## 🎛 Utilities

This section includes a variety of handy utilities that assist with different tasks within the TON ecosystem, from user-friendly address generation to instant notification services. These tools are meant to enhance your experience while interacting with The Open Network.

- [TonStat.com](https://www.tonstat.com/) - Key Metrics of TON Ecosystem.
- [Tonutils Proxy](https://github.com/xssnick/Tonutils-Proxy) - This tool provides a user-friendly implementation of the TON Proxy. It simplifies the tasks of managing and interacting with the TON network.
- [vaniton](https://github.com/AntonMeep/vaniton) - A vanity address generator designed specifically for The Open Network's standard wallets. This tool allows users to create unique, personalized addresses for their wallets.
- [custon](https://github.com/TON-NFT/custon) - A user-friendly generator of custom TON wallet addresses. This utility is written in JavaScript, providing easy access and manipulation for developers.
- [TON Grafana](https://tonmon.xyz/) - A powerful tool that provides blockchain metrics for TON. It offers visualizations and analytics for tracking and managing blockchain data.
- [TON Notify Bot](https://t.me/TONNotifyBot) - This Telegram bot provides instant notifications about coin transfers of the TON addresses. Stay informed about your transactions in real-time with this handy tool.
- [Blockchain Network Visualizer](https://github.com/qpwedev/blockchain-network-visualizer) - Draft tool for visualizing TON blockchain network, written in Python. It provides a visual representation of the contracts and transfers between them. Contributions are welcome.
- [Anonymous Numbers Market Analytics](https://github.com/qpwedev/anonymous-numbers-market-analytics) - Telegram bot that disseminates statistical data on the Anonymous Telegram Numbers from Fragment market.

## 👨‍🎨 UX/UI
- [TON Design System](https://github.com/designervoid/ton-design-system) - Tailwind based Typescript package for creating frontend components which provides [TON Brand Assets](https://ton.org/brand-assets) as Atom CSS with custom theme.


## ✏️ Contribute
> [Contributing to Awesome-TON](contributing.md)
1. Decide on the changes you want to make in the awesome-ton list.
2. Press `.` on the `awesome-ton` page to open the online editor (VSCode).
3. Make changes, describe them, and submit a commit as a Pull Request.
4. Congratulations, you're now a contributor to TON! 😎

