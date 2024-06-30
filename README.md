# Supply Chain Management

## Project description

### Introduction
The food supply chain is a complex but necessary arrangement crucial for the global community to maintain sustainability and food security. This supply chain has extended geographically, involving a multitude of stakeholders. This extension has made the supply chain longer and more complicated, introducing numerous challenges.

Common Challenges in Food Supply Chains
- Lack of Traceability and Communication: The inability to trace the origin and movement of food products leads to inefficiencies and mistrust among stakeholders. Poor communication further exacerbates these issues, causing delays and misunderstandings.
- Rising Supply Chain Costs: Increasing costs associated with transportation, storage, and handling of food products place a significant financial burden on the supply chain. These rising costs can affect the affordability and accessibility of food.
- Supply of Fraudulent Food Products: The distribution of counterfeit or adulterated food products undermines consumer trust and poses serious health risks. Ensuring the authenticity and quality of food products is a significant challenge.
- Failure in Monitoring Warehouses: Inadequate monitoring of storage facilities leads to spoilage, contamination, and loss of food products. Efficient warehouse management is crucial for maintaining the quality and safety of food throughout the supply chain.

---

### System Architecture
The application follows the layered architecture where components which similar functionality are organized into horizontal layers and each layer has a specific role within the application.
The system architecture consists of three layers:

1. Application Layer
2. Blockchain Layer
3. Infrastructure Layer

---

### Methodology
The project is build on three core modules: Traceability System, Trading Mechanism and Reputation System.

- Traceability System <br> 
Each product is marked with unique serial code which is onwed by an externally owned account on Ethereum.
Every product transaction is recorded and stored in smart contract and linked with product's serial code.
This comes with Access Control Strategy which allows only authentic users to make specific transactions.


- Trading Mechanism <br> 
The process of delivering goods from one entity to another is tracked and recorded on the blockchain.
The consumers first register themselves on the system and request to purchase the product with a serial number.
The purchase request is sent to the product owner who updates the product ownership with the new owner.
This process ensures that retailers do not sell products with duplicate serial codes.


- Reputation System <br> 
This system adds a layer of trust between customers and retailers.
This mechanism allows only actual customers of the product to post feedback about the product.
The reviews on the blockchain are immutable which does not allow any merchant or retailer to delete or update bad reviews to increase their overall ratings.
And in this way this mechanism maintains the complete integrity of the retailer and let the customer know about the seller before making the transaction.

---
