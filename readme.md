# Coffee Supply Chain on the Ethereum blockchain

This blockchain application attempts to solve the problem of verifying the authenticity and source
of a product (coffee). Consumers want to know where their products have come from as well as other
information about the product. This application allows for the various actors in a supply chain 
to add those details to their product as it moves through the supply chain. 

In actual use the deployer of the contract would be responsible for adding the various roles 
to the other actors in the supply chain. Interactions between the roles are described in the diagrams below.

## This project 
- Uses Node version 12.13.1
- Uses Truffle version 5.3.11
- Uses Web3.js version 1.3.6
- Was compiled on solc 0.5.1
- Uses truffle-assert version 0.9.2 for testing successful event emissions.

## The contract has been deployed to the rinkeby test network
[Transaction Hash 0x93985ce41139feebebb80029e14497c5e7e1abc2db63599068150c5306935eb3](https://rinkeby.etherscan.io/tx/0x93985ce41139feebebb80029e14497c5e7e1abc2db63599068150c5306935eb3)

[Contract Address 0x4208fFdb7F8402719C313c100B678cbf3Eb1C6F6](https://rinkeby.etherscan.io/address/0x4208fFdb7F8402719C313c100B678cbf3Eb1C6F6)

## Various diagrams were also created during the planning phase.

- Activity Diagram

![Activity Diagram](/diagrams/activity_diagram.png)

- Sequence Diagram

![Sequence Diagram](/diagrams/sequence_diagram.png)

- State Diagram

![State Diagram](/diagrams/state_diagram.png)

- Data Model

![Data Model](/diagrams/data_model.png)