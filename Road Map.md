# Technical Road Map

## Until now

The basic functions of Dante protocol stack are almost completed and are under testing and optimization. Some demos and early-stage SDK are as below:
* Multi-chain communication and smart contract invocation [Demo](https://github.com/dantenetwork/cross-chain-demo/tree/demo-video ) based on Dante protocol stack(support Avalanche, Near, and some other EVM chains).
* An early stage smart contract [SDK](https://github.com/dantenetwork/solidity-contract-template/tree/develop ) in solidity version.
* A [demo](https://github.com/dantenetwork/Routers-Evaluation-Demo ) for routers evaluation.
* A SWAP  [demo](https://github.com/dantenetwork/Demo-Swap/tree/dev )(it’s under optimizing) based on Dante protocol stack.
* Omnichain NFT [usecase](https://github.com/dantenetwork/KingHonorNFT/tree/demo-video ) and [demo](https://github.com/dantenetwork/cadence-contracts/tree/demo-video ).

Some pre-research:
* Minimum viable product of [Storage rollups](https://github.com/dantenetwork/hackathon ).

## 2022.Q2
### Technology
#### The development and testing of the mainly functions of the Dante protocol stack on multi-chains: 
* Complete the development and testing of the core algorithms of the `Consensus Verification Layer`, including Message verification, and Routers evaluation.
* Complete the development and testing of basic mechanisms of the `SQoS Layer`, including hidden & reveal, verification threshold, priority, identity traceability, etc.
* Complete the development and testing of protocols of the `Service Presentation Layer`, including message, contracts invocation, and service visiting protocols.
* Complete the development and testing of off-chain routers.
#### Ecosystem fit:
* Public chains:  Near, Avalanche, BNB.
#### Popular Application fit:
* An Omnichain NFT application demo, which is deployed on Avalanche, Near, Flow, and can be shown and visited by Opensee(Rinkeby).
#### SDK for multi-chain DApp development:
* A basic SC(smart contract) SDK for developers to try some basic functions of the protocol stack with which developers can build multi-chain DApps.

## 2022.Q3
### Technology
#### Launch the Testnet deployed on multi-chains：
* Technical optimization and the security improvements of the protocol stack during the test network operation.
#### The development and testing of the main functions of the Dante protocol stack:
* Advanced items of SQoS, including challenges confirm, exception rollback, Send/receive isolation, etc.
* Routers scheduling algorithm on-chain.
#### Ecosystem fit:
* Public chains:  Add Polkadot.
#### Popular Application fit:
* A SWAP Demo, with which users can exchange Assets(FT/NFT) on Avalanche with some other chains.
#### SDK for multi-chain DApp development on Near:
* SC SDK(support Avalanche, Polkadot, Near, Flow, and some other EVM chains) helps developers build Omnichain-contracts more conveniently. Contracts built with the SDK can communicate and cooperate with contracts deployed on several different chains.

## 2022.Q4
### Technology
#### Hold some technical activities on the Testnet:
* Developing multi-chain DApps on testnet;
* Hacking challenges with certain technical limitations;
#### The development and testing of the core functions of the Dante protocol stack:
* User-defined routers with special functions: verifiable off-chain storage service for multi-chains;
#### Ecosystem fit:
* Add some special public chains, for instance, Flow(the resource-oriented public chain).
#### SDK:
* An advanced S.C SDK for more convenient contract invocation between Near and some other chains.
* SQoS demand setting and judge interface.
* Development of the UDR(User-Defined Routers’) SDK.

## 2023.Q1
### Technology
#### Testnet activities:
* Complete the test of user defined routers with special service(like storage);
* Continue to hold some technical activities on the testnet for the technical optimization and the security improvements;
#### Core functions of the Dante protocol stack:
* The development of more advanced SQoS items, such as cross-verification; This function will be implemented and tested on Near, Polkadot, and EVM chains first.
#### Ecosystems fit:
* (According to the market situation)Bring in some more advanced unique features from some other chains, such as privacy computation(Aleo, Nym), zk-based chains(Aleo, StarkWare), storage(Arweave, Filecoin). Etc.
#### SDK:
* Continuous optimization of the SC SDK.
* A basic version of the UDR SDK.

## The rest of 2023
### Technology
* Security and efficiency optimization for the protocol stack through the feedback from testnet.
* Stable functions such as core algorithms and advanced SQoS items were implemented and tested on more chains.
* Cooperate with more Web3 DApps to promote Dante protocol stack.
* More advanced SDK(both SC and UDR);
* More ecosystems(such as Solana, Cosmos, EverX, etc.).
* Third-party code review；
* Launch the mainnet at the end of 2023 or early 2024(The main concern is about the security, so we hope it will be fully tested on the testnet). 

