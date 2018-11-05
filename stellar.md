# Stellar Evaluation
**Summary -** Stellar is a highly performant trading platform built on a federated byzantine agreement model.

## Reference Material

### Blockchain Explorers
* [Stellar Dashboard](https://dashboard.stellar.org/) - Includes Transactions, Lumen Distribution and Network Nodes
* [Stellar Expert](https://stellar.expert/explorer/public/asset/) - All Assets on Stellar



### Relevant Documentation
* [Stellar Overview](https://www.stellar.org/how-it-works/stellar-basics/)
* [Stellar Consensus Protocol Whitepaper](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.696.93&amp=&rep=rep1&amp=&type=pdf)
* Federated Byzantine Agreement (FBA)
  * [Video](https://youtu.be/vmwnhZmEZjc?list=PLaZFi8ZkzUvKpy77sxeING5t8PVr2zTLS&t=1733)
  * [Slides](http://www.scs.stanford.edu/15au-cs140/notes/scp.pdf)
* [Stellar Documentation](https://www.stellar.org/developers/guides/)
* [Horizon Introduction Video](https://www.youtube.com/watch?v=AtJ-f6Ih4A4&feature=youtu.be)
* [Stellar Core Introduction Video](https://www.youtube.com/watch?v=pt_mm8S9_WU&feature=youtu.be)
* [Building your own Venmo with Stellar](https://blog.abuiles.com/building-your-own-venmo-with-stellar/)
* [Sequence Documentation](https://dashboard.seq.com/docs)
* Starlight: Payment channels on Stellar - [medium](https://medium.com/interstellar/starlight-payment-channels-on-stellar-3ff833c0d0ca) - [Protocol.md](https://github.com/interstellar/starlight/blob/main/starlight/doc/Protocol.md)
* Ecosystem
  * [Developers](https://www.stellar.org/blog/stellar-build-challenge-7-results)
  * [Anchors](https://www.stellar.org/about/directory#anchors)
  * [Companies](https://www.stellar.org/about/directory#companies)

* Token Economics
  * [Fees](https://www.stellar.org/developers/guides/concepts/fees.html)
  * [Inflation Voting](https://www.stellar.org/developers/guides/concepts/inflation.html)


### Relevant Code Links
* [Stellar Core](https://github.com/stellar/stellar-core) - 
Stellar-core is a replicated state machine that maintains a local copy of a cryptographic ledger and processes transactions against it, in consensus with a set of peers.
  * [Stellar Consensus Protocol](https://github.com/stellar/stellar-core/blob/master/src/scp/readme.md)
* [Stellar Go](https://github.com/stellar/go) - Contains all go Code produced by the Stellar foundation and it's [Services](https://github.com/stellar/go/tree/master/services) include
  * [Horizon](https://github.com/stellar/go/tree/master/services/horizon) - Horizon is the client facing API server for the Stellar ecosystem
  * [Bifrost](https://github.com/stellar/go/tree/master/services/bifrost) - Bifrost is highly available and secure Bitcoin/Ethereum → Stellar bridge.


**Key Repositories**

**Functional Breakdown**
* Trading Functionality
  * [Allow Buy Offers](https://github.com/stellar/stellar-protocol/issues/180)
* Stellar Core
  * [New Work Interface Builds](https://github.com/stellar/stellar-core/pull/1819)
* Persistence
  * Storage
    * Data Layer rewrite - [1600]](https://github.com/stellar/stellar-core/pull/1600) and [1788](https://github.com/stellar/stellar-core/pull/1788)
  * Light Client
  * Node
  * Validator
  * Archive Node
* Distribution
  * Discovery
  * Gossip
    * [Buffered Ledger Replay](https://github.com/stellar/stellar-core/issues/1803)
  * Consensus
    * Block Finality
* Security
  * Signing
  * Hashing
  * Privacy
  * Key Storage
    * [Standardize format of Encrypted Key Files](https://github.com/stellar/stellar-protocol/issues/198)
* Governance
  * Staking
  * Voting
* Chaincode
  * See WASM above
* Deployment
* Interledger
  * Message Format
  * Relay Chain
  * Consensus Process
  * Cross Chain
    *[722 - Bifrost (Stellar Ethereum Bridge)](https://github.com/stellar/go/issues/722)
* Developer Tools
  * API
    * [Horizon API](https://www.stellar.org/developers/horizon/reference/index.html)
  * RPC
  * CLI
  * SDK
    * [GO SDK](https://www.stellar.org/developers/go/reference/index.html)
* Off Chain Orchestration
  * Oracles
  * Workflow
* Wallets
  * Feather
* Chain Tools
  * Governance
  * Token Economics
  * Token Standards
* Business Tools
  * Analytics
  * System Monitoring 
  * Deployment Tools

**Key Pull Requests or Features**
* [Release v0.26.0](https://github.com/tendermint/tendermint/pull/2726)

## Stellar Prototyping

**Deploying a Stellar Node**

**Deploying an Asset**

**Running a Transaction**

**Bifrost Server Setup**
* [Setup](https://www.stellar.org/developers/guides/walkthroughs/bifrost-server-setup.html)

