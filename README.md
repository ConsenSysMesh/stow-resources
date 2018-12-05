# The Stow Protocol

<img src="./assets/stow-logo.png" width="300" height="300" />

This repository acts as your gateway into all things Stow. Here, you can find libraries and components written in JavaScript that you can use to build your own Stow-powered applications.

If you have any questions about how the protocol works or how to get started, this repository also contains documentation to steer you in the right direction.

## What is Stow?

[Stow](https://stow-protocol.com/) is a decentralized protocol that facilitates the secure storage and sharing of sensitive data.

[Introduction Video](https://www.youtube.com/watch?v=w0VskCpUKZ8)

[Overview Blog Post](https://medium.com/linnia/linnia-f4f139a795ef)

Want to take a deeper dive into what the Stow Protocol is and what it stands for? Check out our [whitepaper](/introducing-linnia.pdf) or our [homepage](https://stow-protocol.com/) for more context.

## Metadata

For every record, Stow Protocol stores Metadata. This Metadata is chosen by the provider or whoever upload the record. The Metadata is completly public and the Stow Server can be used to query the Metadata of the records in order to find specific data. In order to have the data more organized and easy to search we provide specifications on how to write Metadata for you records. Go [HERE](METADATA.md) to check the specs.

## Public Repositories

#### Components

| Repository                                                                            | Description                                                        |
| ------------------------------------------------------------------------------------- | ------------------------------------------------------------------ |
| [Stow Smart Contracts](https://github.com/ConsenSys/Stow-Smart-Contracts)         | Home of the Stow Protocol Smart Contracts                        |
| [Stow Box](https://github.com/ConsenSys/stow-box)                                 | React UI Starter Template that integrates smart contracts and IPFS |

#### Examples

| Repository                                                                            | Description                                                        |
| ------------------------------------------------------------------------------------- | ------------------------------------------------------------------ |
|stow-example-policy (https://github.com/ConsenSys/linnia-example-policy)|Example of a policy used for policy based permissions |
|stow-json-validator (https://github.com/ConsenSys/linnia-json-validator)| linnia-json-validator to be used for IRIS score oracles |

#### Libraries

| Repository                                                                         | NPM                                                                                                                                                     | Description                                     |
| ---------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------- |
| [Stow JS](https://github.com/ConsenSys/stow-js)                                | [![npm link](https://img.shields.io/badge/npm-stow--js-blue.svg)](https://www.npmjs.com/package/@stowprotocol/stow-js)                            | JS Library to interact with the Stow Protocol |

## Setting up a development environment

Getting started building blockchain technology is tough! As with any emerging technology, the tooling and documentation surrounding it is hard to grasp. But don't worry, we have you covered! Please consult our [starter guide](./GETTING_STARTED.md) to learn everything you need to get started!

## Stow Protocol Tools FAQs
Go [HERE](STOW_PROTOCOL_TOOLS_FAQS.md) to read about the relation between the Stow Protocol and the tools being built around it.

## Ethereum learning resources

[Ethereum resources](ETHEREUM.md)

## Contributing

Stow prides itself on being an open source protocol. We greatly appreciate any contributions you can make to further the cause. Please reference our [contribution documentation](./CONTRIBUTING.md) before getting started!

## Encryption Patterns and Stow

Go [HERE](KEYS.md) to read more about encryption patterns and how the Stow Protocol uses them.

## What is gas and how does it apply to transactions?

Go [HERE](GAS.md) to to understand how gas works and how to use it in your Ethereum transactions.
