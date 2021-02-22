# Ethereum_Dapp_for_Tracking_Items_through_Supply_Chain

This repository containts an Ethereum DApp that demonstrates a Supply Chain flow between a Seller and Buyer. The user story is similar to any commonly used supply chain process. A Seller can add items to the inventory system stored in the blockchain. A Buyer can purchase such items from the inventory system. Additionally a Seller can mark an item as Shipped, and similarly a Buyer can mark an item as Received.

## UML:

![UML](https://github.com/MagicSHX/Ethereum_Dapp_for_Tracking_Items_through_Supply_Chain/blob/main/images/UML%20-%20Activity-Page-1.png)
![UML](https://github.com/MagicSHX/Ethereum_Dapp_for_Tracking_Items_through_Supply_Chain/blob/main/images/UML%20-%20Activity-Page-2.png)
![UML](https://github.com/MagicSHX/Ethereum_Dapp_for_Tracking_Items_through_Supply_Chain/blob/main/images/UML%20-%20Activity-Page-3.png)
![UML](https://github.com/MagicSHX/Ethereum_Dapp_for_Tracking_Items_through_Supply_Chain/blob/main/images/UML%20-%20Activity-Page-4.png)

## Testing result:
![testing_result](https://github.com/MagicSHX/Ethereum_Dapp_for_Tracking_Items_through_Supply_Chain/blob/main/images/testing.png)

## reference required:

    - Specify the Truffle version and OpenZeppelin version used in the project:
        - Truffle v5.1.65
        - Solidity v0.5.16 (solc-js)
        - Node v10.19.0
        - Web3.js v1.3.4
        - truffle-hdwallet-provider@1.0.17
    - "SupplyChain transaction hash" on the Rinkeby Network: 0x48d98591ce6d0983dee5833a49954fe60cc6f886070a1b5f69de0d943f152cb5
    - "SupplyChain contract address" on the Rinkeby Network: 0xA6be8DD3b3cB190E304F6BE0b0BECd4a04dAC66C
    - Please refer to log.txt for details on the Rinkeby Network migrate log

## running step:

    - Open 1st terminal:
        - git clone 'this project'
        - cd project
        - npm install
        - npm install lite-server --save-dev
        - sudo truffle migrate --reset --network rinkeby
    - open a seperate terminal:
        - npm run dev
    - open http://localhost:3000


## Built With

* [Ethereum](https://www.ethereum.org/) - Ethereum is a decentralized platform that runs smart contracts
* [Truffle Framework](http://truffleframework.com/) - Truffle is the most popular development framework for Ethereum with a mission to make your life a whole lot easier.
* [Web3.js] - Web3.js enables user to fulfill the second responsibility: developing clients that interact with The Etherem Blockchain. It is a collection of libraries that allow you to perform actions like send Ether from one account to another, read and write data from smart contracts, create smart contracts, and so much more!
* [truffle-hdwallet-provider] - HD Wallet-enabled Web3 provider. Use it to sign transactions for addresses derived from a 12 or 24 word mnemonic.
* [node.js] - Node.js is primarily used for non-blocking, event-driven servers, due to its single-threaded nature. It's used for traditional web sites and back-end API services, but was designed with real-time, push-based architectures in mind.