## Smart contracts
- A "smart contract" is simply a program that runs on the Ethereum blockchain. It's a collection of code (its functions) and data (its state) that resides at a specific address on the Ethereum blockchain.


## OpenZeppelin
- OpenZeppelin provides security products to build, automate, and operate decentralized applications. We also protect leading organizations by performing security audits on their systems and products.
- OpenZeppelin provides a complete suite of security products to build, manage, and inspect all aspects of software development and operations for Ethereum projects.
- https://docs.openzeppelin.com/openzeppelin/

## Ethers.js
- Ethers.js is a library that makes it easier to interact and make requests to Ethereum by wrapping standard JSON-RPC methods with more user friendly methods.
- Hardhat makes it super easy to integrate Plugins for additional tooling and extended functionality. We’ll be taking advantage of the Ethers plugin for contract deployment (Ethers.js has some super clean contract deployment methods).

##Web3 is similar to Ethers, as it is a library used to make creating requests to the Ethereum blockchain easier. 

ABI (Application Binary Interface) is the interface to interact with our smart contract

Pinata, a convenient IPFS API and toolkit, to store our NFT asset and metadata to ensure our NFT is truly decentralized

## commands
1. npx hardhat compile
2. npx hardhat run scripts/deploy.js --network ropsten


[REFERENCES]
- https://ethereum.org/en/developers/tutorials/how-to-write-and-deploy-an-nft/
- https://hardhat.org/tutorial/testing-contracts.html#writing-tests