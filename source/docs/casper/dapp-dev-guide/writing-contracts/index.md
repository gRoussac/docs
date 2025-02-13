---
title: Introduction
slug: /writing-contracts
---

# Writing On-Chain Code

This section shows you how to write session code and smart contracts in Rust and WebAssembly (Wasm) for a Casper network. When referring to session code, these documents outline logic that executes in the context of an account. In contrast, smart contracts consist of logic installed on-chain, for use by multiple parties. There is a large overlap between the processes of writing session code versus contract code, with some semantic differences outlined in their respective documentation.

| Title                                       | Description                     |
| ------------------------------------------- | ------------------------------- |
|[Getting Started with Rust](/dapp-dev-guide/writing-contracts/getting-started.md)| An introduction to using Rust with the Casper Platform|
|[Best Practices for Casper Smart Contract Authors](/dapp-dev-guide/writing-contracts/best-practices.md)| An outline of best practices when developing smart contracts on a Casper Network|
|[Signing a Deploy](/dapp-dev-guide/writing-contracts/signing-a-deploy.md)|Details on the process of signing a deploy|
|[Writing Session Code](/dapp-dev-guide/writing-contracts/session-code.md)      | An introduction to writing session code|
|[Unit Testing Session Code](/dapp-dev-guide/writing-contracts/testing-session-code.md)      | Steps to test session code using the unit testing framework|
|[Writing a Basic Smart Contract in Rust](/dapp-dev-guide/writing-contracts/rust.md)   | An example of a smart contract built in Rust|
|[Unit Testing Smart Contracts](/dapp-dev-guide/writing-contracts/testing.md)      | Steps to test contract code using the unit testing framework|
|[Installing Smart Contracts and Querying Global State](/dapp-dev-guide/writing-contracts/installing-contracts.md)| A guide on installing smart contracts and querying global state        |
|[Calling Smart Contracts with the Rust Client](/dapp-dev-guide/writing-contracts/calling-contracts.md)| Steps to call a smart contract with the Rust command-line client|
|[Upgrading and Maintaining Smart Contracts](/dapp-dev-guide/writing-contracts/upgrading-contracts.md)| An introduction to versioning smart contracts|
|[Execution Error Codes](/dapp-dev-guide/writing-contracts/execution-error-codes.md)|Possible error codes when writing smart contracts.|
|[Getting Started with AssemblyScript](/dapp-dev-guide/writing-contracts/assembly-script.md) | An introduction to using AssemblyScript with the Casper Platform |

Additionally, the following tutorials outline some aspects of writing smart contracts on the Casper Network.

| Title                                                       | Description                                                      |
| ----------------------------------------------------------- | ---------------------------------------------------------------- |
|[NFTs on Casper with the CEP-78 NFT Standard](https://github.com/casper-ecosystem/cep-78-enhanced-nft/blob/dev/README.md) | Implementing the Casper CEP-78 NFT standard     |
|[A Counter on an NCTL Network](/dapp-dev-guide/tutorials/counter/index.md)             | An example contract that maintains a counter variable on a local Casper Network with NCTL     |
|[A Counter on the Testnet](/dapp-dev-guide/tutorials/counter-testnet/index.md)         | An example contract that maintains a counter variable on the Casper Testnet                   |
|[Fungible Tokens on Casper](https://github.com/casper-ecosystem/erc20/blob/master/docs/TUTORIAL.md)              | Implement the Casper Fungible Token standard                         |
|[Interacting with Runtime Return Values](/dapp-dev-guide/tutorials/return-values-tutorial.md)| Learning how to return a value using contract code         |
|[Safely Transfer Tokens to a Contract](/dapp-dev-guide/tutorials/transfer-token-to-contract.md) | How to handle tokens via a contract                     |
|[Smart Contract Upgrades](/dapp-dev-guide/tutorials/upgrade-contract.md)               | Learn how to upgrade smart contracts                             |
<!-- TODO refresh these tutorials and re-enable the links.
|[Key-Value Storage with Casper DSL](/dapp-dev-guide/tutorials/kv-storage-tutorial.md)  | Design a simple contract to store a value and use the Casper DSL |
|[Multi-Signatures and Key Recovery](/dapp-dev-guide/tutorials/multi-sig/index.md)      | Learn to sign transactions with multiple keys                    | -->

