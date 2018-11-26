<img src="./assets/stow-logo.jpg" width="400" height="400" />

# Stow Protocol Tools FAQs

### Explaining the Stow Protocol and the tools being built around it.

## List of Questions:
1. [What is the Stow Protocol?](#1-what-is-the-stow-protocol)
2. [What is the relationship between the Stow Protocol and the Stow smart contracts?](#what-is-the-relationship-between-the-stow-protocol-and-the-stow-smart-contracts)
3. [What problems does the Stow Protocol solve?](#what-problems-does-the-stow-protocol-solve)
4. [What is the relationship between Stow Protocol and the Stow Faucet?](#what-is-the-relationship-between-stow-protocol-and-the-stow-faucet)
5. [What is the relationship between Stow Protocol and the Stow-Box?](#what-is-the-relationship-between-stow-protocol-and-the-stow-box)
6. [What is the relationship between the Stow Protocol and the Stow Server?](#what-is-the-relationship-between-the-stow-protocol-and-the-stow-server)
7. [Can you explain the Decentralized Data Exchange aka DDEX a bit more?](#can-you-explain-the-decentralized-data-exchange-aka-ddex-a-bit-more)


## 1. What is the Stow Protocol?
Stow is a general protocol which allows users to own and control their data without the need for centralized third parties. The protocol works by acting as a permissions and encryption layer on top of a storage solution, like IPFS, Swarm, Storj or any other decentralized solutions. It is not limited just to decentralized storage solutions, the protocol also works with centralized solutions like Amazon’s S3 and Google Cloud.

By allowing decentralized data to be managed by the user at their convenience, the protocol bakes in data interoperability and the control of data assets. It also allows for the beginnings of privacy and accountability methods to allow users to see who is accessing their data and where.


## What is the relationship between the Stow Protocol and the Stow Smart Contracts?
Stow is a general protocol which allows users to own and control their data without the need for centralized third parties without reference to HOW its implemented.

The Stow smart contract are an implementation of the Stow Protocol on the Ethereum Blockchain using the Solidity programming language.


## What problems does the Stow Protocol solve?
Stow Protocol can help solve the following problems:

- **Increased security:** Since data is decentralized, the risk of having a large centralized honeypot where all the data can be accessed by a malicious entity is significantly reduced. This reduces liability for start ups and users since data can be decentralized.

- **Increased privacy and control:** The user chooses who has access to their longitudinal data and under what circumstances.

- **Creates an incentive for data interoperability:** Since data can be decentralized, networks who wish to access such datasets will have to agree on standards to ensure compatibility. This step is essential to help reduce the data blocking and hoarding which results in disproportional advantages by established players in different markets.

- **Increased competitiveness.** Since data interoperability and user control is incentivized, startups with good value propositions will be able to directly petition users for their data. Start ups could also bootstrap data for their models via decentralized data markets. These decentralized data markets essentially commoditize data, making it available to all. More data means startups can regained a competitive advantage. More data under user control means that users regain their privacy and control of their data, as well as greater access to new services.


## What is the relationship between Stow Protocol and the Stow Faucet?
The Stow Faucet helps users register with their Ethereum Addresses to our Stow smart contracts and obtain their encryption keys. The user interface prompts also serves as an introduction to Stow for the users.

In the future, there will be more programmatic ways conduct these steps.


## What is the relationship between Stow Protocol and the Stow-Box?
The Stow Box serves two functions:
- As a boilerplate to help you create your own Stow powered React application.
- As a starting point to see how our Stow library interacts with a React App and the Ethereum Blockchain.
- As a tool to explore the methods available in the Stow library powered by the Stow Protocol.


## What is the relationship between the Stow Protocol and the Stow Server?
Storage on the blockchain is expense. In to save ether, we save the barest minimum of the state of the protocol on the blockchain itself, and expand it into more queryable datatypes in an offchain service.

So, the Stow Server is used to allow Stow Records to be searched and queried using the appended metadata.


## What is the relationship between Stow Protocol and the DDEX?
One can think of Stow Protocol as property rights for data (or like linux's chmod, but for distributed data on the Ethereum world computer). This is achieved by user control of the data via permissions and decentralized storage. It’s a padlock for stuff that only the user can open.

Following this logic, once someone owns AND has control of something, they can then exchange it for another item of value if the proper incentive exists. This exchange done over a network can be generalized as a market. Hence, the logical extension of the Stow Protocol is to create data markets where users can exchange data under mutually beneficial conditions.

Note that a data market could be based on the data itself or any sort of useful meta data derived from the data to improve a machine learning model. **The purpose is that the data being exchange has intrinsic value and there is demand for it.**

Think of a data market as a decentralized bazaar where no one owns the market, but all who participate follow certain rules because it’s beneficial to them over the long term.


## Can you explain the Decentralized Data Exchange aka DDEX a bit more?
To conceptualize the DDEX, think of this statement:

“Alice owns data about the health of wheat crops for this year’s harvest”.

Note, there are two key things in that statement:

- Identity. Without identity, it is hard to claim ownership of something.
- Ownership requires control. Thus, those that wish to use or take control the item in question must ask for permission and provide the proper incentives for exchange.

Let’s take this a step further:
“Bob has cash and would like the Alice’s data on this year's wheat crops.”

**Ownership of an asset opens the possibly for trade.**
If a trade between two parties leaves both parties better off, then a trade might occur. **The point of the DDEX is to help find parties find each other in a very low friction manner.**

A key to point to mention is that valuable data can be longitudinal in nature. That means that it grows and compounds over time. **The Stow Protocol is perfect for giving users control of the longitudinal data.**

**In order for any machine learning model to continue to reflect the current world, it must have access to current data.** Think of a model as a clock which needs calibration every so often to keep it in synch with the world. A data markets can provide a constant feed of calibration with orders of magnitude of less friction that currently exists today.

