

## Project description

### Introduction
The food supply chain is a complex but necessary food production arrangement needed by the global community to maintain sustainability and food security. The supply chain has been extended geographically involving many more stakeholders, making the supply chain longer and complicated and thus involving many challenges.

Some of the challenges that are commonly faced in food supply chains are
* Lack of traceability and communication.
* Rising supply chain costs.
* Supply of fraudulent food products.
* Failure in monitoring warehouses.

### Objectives
The project aims to design a decentralized food supply chain to trace products from end to end and provide a smart and reliable way of providing information to the customers. <br/>
**Features**
* Platform to trace food products worldwide.
* Restricting duplicate and unauthentic products.
* Proper food distribution.
* Reducing the supply chain costs.

### System Architecture
The application follows the layered architecture where components which similar functionality are organized into horizontal layers and each layer has a specific role within the application.
<br/>
The system architecture consists of three layers:
- Application Layer
- Blockchain Layer
- Infrastructure Layer


### Methodology
The project is build on three core modules: Traceability System, Trading Mechanism and Reputation System.
1. **Traceability System**
    * Each product is marked with unique serial code which is onwed by an externally owned account on Ethereum.
    * Every product transaction is recorded and stored in smart contract and linked with product's serial code.
    * This comes with Access Control Strategy which allows only authentic users to make specific transactions.
2. **Trading Mechanism**
    

    * The process of delivering goods from one entity to another is tracked and recorded on the blockchain.
    * The consumers first register themselves on the system and request to purchase the product with a serial number.
    * The purchase request is sent to the product owner who updates the product ownership with the new owner.
    * This process ensures that retailers do not sell products with duplicate serial codes.
3. **Reputation System**
    

    * This system adds a layer of trust between customers and retailers.
    * This mechanism allows only actual customers of the product to post feedback about the product.
    * The reviews on the blockchain are immutable which does not allow any merchant or retailer to delete or update bad reviews to increase their overall ratings. 
    * And in this way this mechanism maintains the complete integrity of the retailer and let the customer know about the seller before making the transaction.


## Development Setup
### Requirements
- [NodeJS](https://nodejs.org/en) >= 10.16 and [npm](https://www.npmjs.com/) >= 5.6 installed.
- [Git](https://git-scm.com/) installed in the system.
- [Truffle](https://www.trufflesuite.com/truffle), which can be installed globally with `npm install -g truffle`
- [Metamask](https://metamask.io) extension added to the browser.
- [Ganache](https://trufflesuite.com/ganache/) development network.

