---
title: Build
lead: The Plasma ecosystem needs you. Lots of projects are actively building things using the Plasma framework. This page maintains a list of actively developed projects you can contribute to.
sublead: If you actively maintain a Plasma implementation and don't see it listed here, feel free to create an issue on GitHub! We'll get your project on this page. Similarly, please open an issue if something on this page is inaccurate or you'd like to change a description.
date: 2018-08-21 16:26:02
categories:
tags:
---

## FourthState Labs
[<i class="fab fa-github"></i>](https://github.com/fourthstate)

FourthState Labs is Blockchain @ Berkeley's Plasma team.


### plasma-mvp-rootchain
[<i class="fab fa-github"></i>](https://github.com/FourthState/plasma-mvp-rootchain)

FourthState Labs is maintaining a Plasma MVP smart contract for Ethereum.

**Stack:**
+ Solidity
+ JavaScript (Truffle)

### plasma-mvp-sidechain
[<i class="fab fa-github"></i>](https://github.com/FourthState/plasma-mvp-sidechain)

FourthState labs is separately developing a Plasma MVP client that uses tendermint consensus.

**Stack:**
+ Go

---

## OmiseGO
[<i class="fas fa-globe"></i>](https://omisego.network) [<i class="fab fa-github"></i>](https://github.com/omisego)

OmiseGO is using Plasma to build a scalable decentralized exchange and payment network.

### plasma-contracts
[<i class="fab fa-github"></i>](https://github.com/omisego/plasma-contracts)

OmiseGO's production Plasma contracts are maintained in this repository. The master branch currently tracks optimized Plasma MVP contracts.

**Stack:**
+ Solidity
+ Python

### plasma-mvp
[<i class="fab fa-github"></i>](https://github.com/omisego/plasma-mvp)

OmiseGO is building out a reference implementation of Plasma MVP as part of their decentralized exchange. The contracts in this repo are generally less optimized but more readable.

**Stack:**
+ Solidity
+ Python

### plasma-cash
[<i class="fab fa-github"></i>](https://github.com/omisego/plasma-cash)

OmiseGO hosts a Plasma Cash contract and client implementation, although the project is largely maintained by outside contributors.

**Stack:**
+ Solidity
+ Python

---

## Loom Network
[<i class="fas fa-globe"></i>](https://loomx.io/) [<i class="fab fa-github"></i>](https://github.com/loomnetwork)

Loom uses Plasma to augment their application-specific sidechains (DAppChains).

### plasma-erc721
[<i class="fab fa-github"></i>](https://github.com/loomnetwork/plasma-erc721)

Loom is planning to use Plasma Cash to secure non-fungible assets on their DAppChains.

**Stack:**
+ Solidity
+ JavaScript (Truffle)
+ Python
+ Go


---

## BANKEX
[<i class="fas fa-globe"></i>](https://bankex.com) [<i class="fab fa-github"></i>](https://github.com/BANKEX)

BANKEX is working on Plasma as part of their tokenization ecosystem.

### PlasmaParentContract
[<i class="fab fa-github"></i>](https://github.com/BANKEX/PlasmaParentContract)

BANKEX currently maintains an experimental implementation of More Viable Plasma.

**Stack:**
+ Solidity
+ JavaScript (Truffle)

---

## Wolk
[<i class="fas fa-globe"></i>](https://wolk.com) [<i class="fab fa-github"></i>](https://github.com/wolkdb)

Wolk is incorporating Plasma Cash as part of their decentralized database service architecture.

### Plasmacash
[<i class="fab fa-github"></i>](https://github.com/wolkdb/deepblockchains/tree/master/Plasmacash)

Wolk maintains an implementation of Plasma Cash root chain contracts.

**Stack:**
+ Solidity

---

## Lucidity
[<i class="fas fa-globe"></i>](https://lucidity.tech) [<i class="fab fa-github"></i>](https://github.com/luciditytech)

Lucidity is using Plasma Cash coupled with a stable coin for payments in AdTech supply chains.

### Plasma MVP
[<i class="fab fa-github"></i>](https://github.com/luciditytech/lucidity-plasma)

Lucidity maintains an implementation of Plasma MVP root chain contracts.

**Stack:**
+ Solidity
+ Javascript

### Plasma Cash
[<i class="fab fa-github"></i>](https://github.com/luciditytech/lucidity-plasma-cash)

Lucidity maintains an implementation of Plasma Cash as part of their sidechain architecture. This repo contains a Sparse Merkle Tree implementation used for multi-party crypto payments in AdTech supply chains.

**Stack:**
+ Solidity
+ Javascript
