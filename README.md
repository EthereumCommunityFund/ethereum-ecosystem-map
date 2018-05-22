# ethereum-ecosystem-map
This repository is dedicated to collect and display resources that contribute to an objective mapping or overview of the Ethereum ecosystem.

## Background & Motivations
Sometimes, for both newcomers and seniors of the Ethereum community, it can be hard to keep track of the latest advances, as well as the latest conversations concerning research. At the same time, the community lacks access to a data-driven, objective mapping of the Ethereum ecosystem. 
From the ECF's perspective, we wish to build automated or semi-automated tools that
provide an objective overview of the state of the ecosystem, so community members can see in what layers, areas or tooling Ethereum is lacking. 
For grant managers at the ECF, this overview can be helpful for prioritising research and development in those areas that are essential but less attractive, distribute funding in a balanced manner, and strive for diversity of projects vertically along the stack, and horizontally, in terms of implementations. 

## Taxonomy (V.0.2)
Taxonomies are an useful way of presenting information in a visual and concise manner. Nonetheless, they are not perfect, as there will always be projects or cases that do not fit limitedly to one layer, as well as others that fit at the same time in more than one layer. 
For illustration purposes, the following is one of the first iterations of a taxonomy of projects in the ethereum ecosystem.

> Note that all the projects mentioned serve as examples only of each layer, *by no means are these mentions any kind of endorsement*.

![Ethercosystem Taxonomy](https://github.com/EthereumCommunityFund/ethereum-ecosystem-map/blob/master/figures/ethercosystem.png)

## Frequently Visited Sources
* Ethereum Wiki: https://github.com/ethereum/wiki/wiki
* ETH Research: https://ethresear.ch/latest

## Table of Contents
0. [How to Contribute?](#how-to-contribute)
1. [Hardware](#hardware)
2. [Networking](#networking)
3. [Consensus](#consensus)
4. [Deterministic State Machines](#deterministic-state-machines)
5. [Interoperability](#interoperability)
6. [Usability](#usability)
7. [Development Infrastructure](#development-infrastructure)
8. [Development Tooling](#development-tooling)
9. [Application Specific Protocols](#application-specific-protocols)
10. [Wallets & Account management](#wallets-and-account-management)
11. [End User Applications](#end-user-applications)
12. [Off-Chain Utilities](#off-chain-utilities)

### How to Contribute?
Should you know of any projects that are not yet listed or suggest a correction, choose one of the following. Depending on the contributions, there best way of proceeding are:
* Error reporting: GitHub Issue, PRs
* Listing new project: GitHub Issue, PRs
* Making suggestions: GitHub Issue
* Questions: GitHub Issue

Either way, make sure you include the following information:
* Add a label: `error` for corrections, `new project` for additions
* Assign it to me @awasunyin, if this issue has not been dealt with within 7 natural days
And, whenever applicable:
* Project name
* Project implementation language
* Project link to GitHub (must be open-source, if code is not ready, at least some documentation or specifications)
* Which layer? See taxonomy figure. 

#### Create a Pull Request
Should you want to make the changes directly, make sure you include the additional information:
* Brief description of what changes have been made and why, you can include more than one label

#### Editing .csv files directly
Currently, I compile the names of projects and their information in csv files, which you can find under `/data/*.csv`. After some time, I convert the .csv files into markdown tables and add them to the `README.md`. 
> Note: GitHub offers this user-friendly .csv viewer. For changes the .csv, open a PR. 

### Hardware
| Project   | Language (if applicable) | Link                                                |
|-----------|--------------------------|-----------------------------------------------------|
| CPU Miner | C++                      | https://github.com/ethereum/go-ethereum/wiki/Mining |
| GPU Miner | ?                        | https://github.com/ethereum/go-ethereum/wiki/Mining |

### Networking
| Project | Language | Link                                                     |
|---------|----------|----------------------------------------------------------|
| ÐΞVp2p  | ?        | https://github.com/ethereum/devp2p/blob/master/discv4.md |

### Consensus
| Project      | Language | Link                                                                       |
|--------------|----------|----------------------------------------------------------------------------|
| Casper (PoS) | ?        | https://github.com/ethereum/wiki/wiki/Casper-Proof-of-Stake-compendium     |
| Sharding     | ?        | https://github.com/ethereum/wiki/wiki/Sharding-introduction-R&D-compendium |

### Deterministic State Machines
| Project       | Language    | Link                                         |
|---------------|-------------|----------------------------------------------|
| EVM           | go          | https://github.com/ethereum/go-ethereum      |
| py-EVM        | python      | https://github.com/pipermerriam/py-evm       |
| EthereumJ     | java        | https://github.com/ethereum/ethereumj        |
| SputnikVM     | rust        | https://github.com/ethereumproject/sputnikvm |
| K Framework   | K framework | https://github.com/kframework/evm-semantics  |
| hevm          | haskell     | https://github.com/dapphub/hevm              |
| Burrow        | go          | https://github.com/hyperledger/burrow        |
| Ethereumjs-VM | javascript  | https://github.com/ethereumjs/ethereumjs-vm  |
| sputter       | clojure     | https://github.com/nervous-systems/sputter   |
| eWASM kernel  | javascript  | https://github.com/ewasm/ewasm-kernel        |

### Interoperability

### Usability
| Project       | Language   | Link                                        |
|---------------|------------|---------------------------------------------|
| Geth          | go         | https://github.com/ethereum/go-ethereum     |
| Parity        | rust       | https://github.com/paritytech/parity        |
| cpp-ethereum  | c++        | https://github.com/ethereum/cpp-ethereum    |
| py-evm        | python     | https://github.com/ethereum/py-evm          |
| ethereumjs-vm | javascript | https://github.com/ethereumjs/ethereumjs-vm |

### Development Infrastructure

### Development Tooling

### Application Specific Protocols

### Wallets and Account Management

### End User Applications

### Off-Chain Utilities
