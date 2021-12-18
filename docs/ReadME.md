## Smart contracts
- a program that runs on the Ethereum blockchain. 
- It's a collection of code (its functions) and data (its state) that resides at a specific address on the Ethereum blockchain.
- They typically are used to automate the execution of an agreement so that all participants can be immediately certain of the outcome, without any intermediary’s involvement or time loss. They can also automate a workflow, triggering the next action when conditions are met.
- Smart contracts work by following simple “if/when…then…” statements that are written into code on a blockchain. A network of computers executes the actions  when predetermined conditions have been met and verified. These actions could include releasing funds to the appropriate parties, registering a vehicle, sending notifications, or issuing a ticket. The blockchain is then updated when the transaction is completed. That means the transaction cannot be changed, and only parties who have been granted permission can see the results.

- Within a smart contract, there can be as many stipulations as needed to satisfy the participants that the task will be completed satisfactorily. To establish the terms, participants must determine how transactions and their data are represented on the blockchain, agree on the “if/when...then…” rules that govern those transactions, explore all possible exceptions, and define a framework for resolving disputes.

- Then the smart contract can be programmed by a developer – although increasingly, organizations that use blockchain for business provide templates, web interfaces, and other online tools to simplify structuring smart contracts.

## IPFS (Interplanetary file system)
- IPFS is a protocol and a peer to peer network for storing and sharing data in a distributed file system. 
- IPFS uses content addressing to uniquely identify each file in a global namespace connecting all computing devices. 
- IPFS is built around a decentralized system of user operators who hold a portion of the overall data, creating a resilient system of file storage and sharing. 


## BLOCKCHAIN
- Blockchain is the growing list of records called blocks which are linked together using cryptography. Each block contains the cryptographic hash of the previous block, timestamp and the transaction data. 

## OpenZeppelin
- OpenZeppelin provides security products to build, automate, and operate decentralized applications. We also protect leading organizations by performing security audits on their systems and products.
- OpenZeppelin provides a complete suite of security products to build, manage, and inspect all aspects of software development and operations for Ethereum projects.
- https://docs.openzeppelin.com/openzeppelin/

## Ethers.js
- Ethers.js is a library that makes it easier to interact and make requests to Ethereum by wrapping standard JSON-RPC methods with more user friendly methods.
- Hardhat makes it super easy to integrate Plugins for additional tooling and extended functionality. We’ll be taking advantage of the Ethers plugin for contract deployment (Ethers.js has some super clean contract deployment methods).

## Web3 
- similar to Ethers, as it is a library used to make creating requests to the Ethereum blockchain easier. 

## ABI (Application Binary Interface) 
- the interface to interact with our smart contract

## Pinata
- a convenient IPFS API and toolkit, to store our NFT asset and metadata to ensure our NFT is truly decentralized

## Remix
- Remix IDE is an open source web and desktop application. It fosters a fast development cycle and has a rich set of plugins with intuitive GUIs. Remix is used for the entire journey of contract development as well as being a playground for learning and teaching Ethereum.
- Remix IDE is part of the Remix Project which is a platform for development tools that use a plugin architecture. It encompasses sub-projects including Remix Plugin Engine, Remix Libs, and of course Remix-IDE.
- Remix IDE is a powerful open source tool that helps you write Solidity contracts straight from the browser.
- It is written in JavaScript and supports both usage in the browser, in the browser but run locally and in a desktop version.

## commands
1. npx hardhat compile
2. npx hardhat run scripts/deploy.js --network ropsten


[REFERENCES]
- https://ethereum.org/en/developers/tutorials/how-to-write-and-deploy-an-nft/
- https://hardhat.org/tutorial/testing-contracts.html#writing-tests
- https://medium.com/geekculture/expansionpunks-welcome-to-the-more-inclusive-punkverse-aa77e675bcf5
- https://www.ibm.com/topics/smart-contracts