# Neo Developer Tools List

A guide to available tools, components, patterns, and platforms for developing applications on Neo N3.

Creation of this list was spurred by Neo Pod Team who saw a need for better sharing of tools, development patterns, and components amongst both new and experienced blockchain developers.

This resource is meant to be focused on developer tools.

## New developers start here

- [C#](https://docs.neo.org/docs/en-us/gettingstarted/prerequisites.html) - Get started developing, deploying and invoking a smart contract using C#.
- [Python](https://dojo.coz.io/article/hello_world_dapp) - Get started developing, deploying and invoking a smart contract using Python.
- [Java](https://developers.neo.org/tutorials/2022/08/15/neow3j-smart-contract-quickstart) - Get started developing, deploying and invoking a smart contract using Java.
- [Go](https://github.com/nspcc-dev/neo-go-sc-wrkshp) - Get started developing, deploying and invoking a smart contract using Go.
- [TypeScript](https://neo-one.io/docs/quick-start) - Get started developing, deploying and invoking a smart contract using TypeScript.

## Developer Tools

### Developing Smart Contracts

#### Frameworks

- [Props](https://props.coz.io/d) - General purpose smart contracts and developer framework for Neo N3.

#### IDEs

- [Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=ngd-seattle.neo-blockchain-toolkit) - Visual Studio Code extension that helps you develop, debug, test, deploy, track and manage your blockchain applications
- [Intellij ](https://plugins.jetbrains.com/plugin/17195-neo) - A plugin for [JetBrains IntelliJ Idea IDE](https://jetbrains.com/idea/) for the Neo blockchain.

### Testnet RPC Address

- https://testnet1.neo.coz.io:443
- https://testnet2.neo.coz.io:443
- https://rpc.t5.n3.nspcc.ru:20331/
- http://seed1t5.neo.org:20332
- http://seed2t5.neo.org:20332
- http://seed3t5.neo.org:20332
- http://seed4t5.neo.org:20332
- http://seed5t5.neo.org:20332

### Mainnet RPC Address

- https://mainnet1.neo.coz.io:443
- https://mainnet2.neo.coz.io:443
- http://seed1.neo.org:10332
- http://seed2.neo.org:10332
- http://seed3.neo.org:10332
- http://seed4.neo.org:10332
- http://seed5.neo.org:10332

#### Test N3 Faucets

- [T5 faucet](https://n3t5wish.ngd.network/#/)

### Communicating with Neo

#### Frontend Neo APIs

- [Neoline](https://neoline.io/dapi/N3.html#startExample) - dAPI integration for connecting with DAapps.
- [O3 wallet](https://neo3dapidocs.o3.network/#what-is-the-dapi) - package interface for communicating with the NEO N3 blockchain.
- [Neo Wallet Adapter](https://github.com/rentfuse-labs/neo-wallet-adapter) - Modular TypeScript wallet adapters and components for NEO N3 applications.
- [Onegate](https://github.com/neo-ngd/neo-dapi-monorepo) - Monorepo for Neo dAPI (Including Neo dAPI, Neo Provider, Types and Utils)
- [WalletConnect SDK](https://github.com/CityOfZion/wallet-connect-sdk) - A COZ WalletConnect 2.0 SDK for ecosystem tools. WcSdk is an auxiliary library built to help the usage of [WalletConnect](https://walletconnect.org/) with NEO3 Wallets.
- [neo-one Client APIs](https://neo-one.io/docs/client-apis) - Typescript client Api for the NEO blockchain

#### Backend Neo APIs

- [neo-mamba](https://github.com/CityOfZion/neo-mamba) - Python SDK for the NEO3 blockchain
- [neon-js](https://dojo.coz.io/neo3/neon-js/docs) - Javascript library to interface with NEO blockchain
- [ghostmarket-sdk-js](https://github.com/OnBlockIO/ghostmarket-sdk-js) - Javascript SDK for GhostMarket.

### Infrastructure

#### Storage

- [neofs-api-csharp](https://github.com/neo-ngd/neofs-api-csharp) - WIP NeoFS API C# implementation
- [Greenfinch](https://github.com/configwizard/greenfinch-api) - NeoFS RESTful API

### Debugging

- [NeoTrace](https://github.com/neo-project/neo-express) - Neo-Trace is a tool to generate Neo Smart Contract Debugger trace files for existing blocks or transactions.
- [NeoTrace Tutorial Part 1](https://youtu.be/1dm_qbQ_cr4) - NeoTrace Debug tooling Part 1
- [NeoTrace Tutorial Part 2](https://youtu.be/wLKmdPEZ54k) - NeoTrace Debug tooling Part 2
- [Debugging your Smart Contract with Visual Studio Code](https://ngdenterprise.com/neo-tutorials/quickstart5.html) - Debugging your Smart Contract with Visual Studio Code
- [neo3-boa](https://dojo.coz.io/neo3/boa/getting-started.html#testing-and-debugging) - Testing and Debugging Neo3 smart contracts with python
- [Go](https://github.com/nspcc-dev/neo-go/blob/master/docs/compiler.md#debugging) - Debug Go Neo3 Smart contracts
- [neo-one](https://neo-one.io/docs/testing) - Use your favorite unit test framework to test smart contracts using the NEO•ONE client APIs.
- [neow3j](https://neow3j.io/#/neo-n3/smart_contract_development/testing) - Neow3j offers a test library that allows convenient smart contract testing on top of JUnit.

### Security Tools

- [Red4Sec](https://red4sec.com/en) - Audit Neo smart contracts to identify possible vulnerabilities or failures in the behavior of the code and proceed to their mitigation.

### Other Miscellaneous Tools

- [neonova](https://www.neonova.space/) - Like Postman but for NEO N3.

### Smart Contract Standards

#### NEP-17 Standard

To ensure interoperability every token contract should support at least one of the token standards. These standards define a set of methods and behaviors that allow platforms (like exchanges, dApps, and other contracts) to easily interface with.

In Neo, the common blueprint for Fungible Tokens is defined in the NEP-17 Token Standard.

- [C#](https://docs.neo.org/docs/en-us/develop/write/nep17.html)
- [C# Tutorial](https://ngdenterprise.com/neo-tutorials/tutorial2-ui.html)
- [Python](https://dojo.coz.io/neo3/boa/tutorials.html#neo-token-standard-nep-17)
- [Python Tutorial](https://developers.neo.org/tutorials/2021/06/17/writing-a-nep17-token-in-python)
- [Python Template](https://github.com/CityOfZion/neo3-boa/blob/master/boa3_test/examples/nep17.py)
- [Java](https://neow3j.io/#/neo-n3/dapp_development/token_contracts?id=fungible-token-contracts-nep-17)
- [Java Template](https://github.com/neow3j/neow3j-examples-java/blob/master/src/main/java/io/neow3j/examples/contractdevelopment/contracts/FungibleToken.java)
- [Go](https://github.com/nspcc-dev/neo-go-sc-wrkshp#nep17)
- [Go Template](https://github.com/nspcc-dev/neo-go/blob/master/examples/token/token.go)
- [TypeScript](https://neo-one.io/tutorial#Create-a-Token)

#### NEP-11 Standard

In Neo, the common blueprint for Non Fungible Tokens is defined in the [NEP-11 Token Standard](https://github.com/neo-project/proposals/blob/master/nep-11.mediawiki).

- [C#](https://docs.neo.org/docs/en-us/develop/write/nep11.html)
- [Python Template](https://github.com/OnBlockIO/NEP11TemplatePy)
- [Java Divisible NFT Template](https://github.com/neow3j/neow3j-examples-java/blob/master/src/main/java/io/neow3j/examples/contractdevelopment/contracts/DivisibleNonFungibleToken.java)
- [Java Template](https://github.com/neow3j/neow3j-examples-java/blob/master/src/main/java/io/neow3j/examples/contractdevelopment/contracts/NonFungibleToken.java)
- [Go Divisible NFT Template](https://github.com/nspcc-dev/neo-go/blob/master/examples/nft-d/nft.go)
- [Go Non-Divisible NFT Template](https://github.com/nspcc-dev/neo-go/blob/master/examples/nft-nd/nft.go)
