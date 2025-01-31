# Supply chain & data auditing

This repository containts an Ethereum DApp that demonstrates a Supply Chain flow between a Seller and Buyer. The user story is similar to any commonly used supply chain process. A Seller can add items to the inventory system stored in the blockchain. A Buyer can purchase such items from the inventory system. Additionally a Seller can mark an item as Shipped, and similarly a Buyer can mark an item as Received.
The versions of libraries used by the projects are as given below.
Truffle v5.7.5 (core: 5.7.5)
Ganache v7.7.3
Solidity - >0.5.17 (solc-js)
Node v18.14.0
Web3.js v1.8.2


## Part 1 
### Project write-up - UML
#### Activity
![Activity](activity.jpg)

#### Sequence
![Sequence](sequence.jpg)

#### State
![State](State.JPG)

#### Classes
![Data-Model](datamodel.jpg)

### Project write-up - Libraries
####  truffle/hdwallet-provider  
This is HD Wallet-enabled Web3 provider. Used for connecting to Ethereum Goerli testnet from the client side application

####  openzeppelin-solidity  
Provide a set of pre-audited, reusable smart contracts that can be used to build various types of decentralized applications. In the future it is recommened to use openzeppelin-contracts that contains contracts written in the newer Solidity 0.8 syntax, which has several improvements over the previous versions.

####  truffle-assertions 
Provides assertions that can be used to test Ethereum smart contracts inside Truffle test.

####  web3
Collection of libraries that allows to interact with a local or remote ethereum node using HTTP, IPC or WebSocket

####  lite-server
Lightweight development only node server that serves a web app. Used for hosting the client application that tracks the Fair Trade Coffee Supply chain platform.

### Project write-up - IPFS
#### Not implemented

## Part 2

### Define and implement required interfaces
#### Implemented the interfaces as per the requirements

### Build out Base Contract
#### Base contracts are built out as per requirements

### Build out Core Contract
#### Core contracts are built out as per requirements

## Part 3
### Smart contract has associated tests
![Tests](tests.JPG)

## Part 4
### Deploy smart contract on a public test network
#### Using truffle all the smart contracts are deployed to Goerli test net

### Submit Contract Address
#### Contract addresses and transaction hashes are given below
Fetching solc version list from solc-bin. Attempt #1
   Deploying 'Migrations'
   ----------------------
   > transaction hash:    0x9068bd3d34a53593271df8c072dd0443f3a617e91085fa5c9a5f977e526effbb
   > Blocks: 0            Seconds: 4lc-bin. Attempt #1
   > contract address:    0x7215B33bBABF33A976d83378F30936a205F96a7d
   > block number:        8492572
   > block timestamp:     1676412876
   > account:             0x9c12b247E78043b5a104A345105002d0dfbCfbd9
   > balance:             0.172156747342750178
   > gas used:            274088 (0x42ea8)
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.00274088 ETH

   > Saving migration to chain.om solc-bin. Attempt #1
   > Saving artifacts to chain.
   -------------------------------------
   > Total cost:          0.00274088 ETH
   
⠧ Fetching solc version list from solc-bin. Attempt #1
   Deploying 'FarmerRole'
   ----------------------
   > transaction hash:    0x8f2f255bf21828d2270442719b6cfeb6771670b81fc238f7e58be9007ed0e54d
   > Blocks: 1            Seconds: 32c-bin. Attempt #1
   > contract address:    0x74A13Cf83ddC295f8495FE1156b5Fefb3a4EfAe5
   > block number:        8492575
   > block timestamp:     1676412924
   > account:             0x9c12b247E78043b5a104A345105002d0dfbCfbd9
   > balance:             0.168391117342750178
   > gas used:            330628 (0x50b84)
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.00330628 ETH

⠹ Fetching solc version list from solc-bin. Attempt #1
   Deploying 'DistributorRole'
   ---------------------------
   > transaction hash:    0x19e362e3a99dff21b329763d6cce1837cd5a740acf746ed3b04c65076ab151a3
   > Blocks: 1            Seconds: 20c-bin. Attempt #1
   > contract address:    0x4056FF3b506c552744D592e74d0F65d94C340Fc4
   > block number:        8492577
   > block timestamp:     1676412948
   > account:             0x9c12b247E78043b5a104A345105002d0dfbCfbd9
   > balance:             0.165084717342750178
   > gas used:            330640 (0x50b90)
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.0033064 ETH

⠏ Fetching solc version list from solc-bin. Attempt #1
   Deploying 'RetailerRole'
   ------------------------
   > transaction hash:    0x514fe764bf2280a7a74b84c06ac0e52f35a71bcdf2bbfac5550082887174026f
   > Blocks: 0            Seconds: 8lc-bin. Attempt #1
   > contract address:    0x5A45961b9A7d0EE70250CE7dA8e4c3010D0BDf2b
   > block number:        8492578
   > block timestamp:     1676412960
   > account:             0x9c12b247E78043b5a104A345105002d0dfbCfbd9
   > balance:             0.161778317342750178
   > gas used:            330640 (0x50b90)
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.0033064 ETH

    Fetching solc version list from solc-bin. Attempt #1
   Deploying 'ConsumerRole'
   ------------------------
   > transaction hash:    0x392059a8899ccea1dfe6a98af2b6ac3e263f6d109f701e86e78b31ce699546e8
   > Blocks: 1            Seconds: 24c-bin. Attempt #1
   > contract address:    0xDCf063489A5DF1F15f9511E936db6e29B48eB505
   > block number:        8492579
   > block timestamp:     1676412984
   > account:             0x9c12b247E78043b5a104A345105002d0dfbCfbd9
   > balance:             0.158471917342750178
   > gas used:            330640 (0x50b90)
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.0033064 ETH

⠹ Fetching solc version list from solc-bin. Attempt #1
   Deploying 'SupplyChain'
   -----------------------
   > transaction hash:    0x7207cc7044b68d7d8d741728c0c69e29c30d316b9d21ddf4e01eceaa22885913
   > Blocks: 0            Seconds: 32c-bin. Attempt #1
   > contract address:    0x78868C9fD3c9e74B58e51A25Cb10798E160bBe4F
   > block number:        8492580
   > block timestamp:     1676413020
   > account:             0x9c12b247E78043b5a104A345105002d0dfbCfbd9
   > balance:             0.130831327342750178
   > gas used:            2764059 (0x2a2d1b)
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.02764059 ETH

   > Saving migration to chain.om solc-bin. Attempt #1
   > Saving artifacts to chain.
   -------------------------------------
   > Total cost:          0.04086607 ETH


## Part 5
### Modify client code to interact with smart contract
#### Modified the client code to interact with the DApp. Current UI has all the roles accessing the DApp from same UI. However in real world based on the type of role each user will have different screen and they will be connecting using the appropriate metamask or any other wallet.
















