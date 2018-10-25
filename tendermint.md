# Tendermint Evaluation
**Summary -** Tendermint is a highly scalable Proof of Stake Blockchain Platform. 

## Reference Material

### Blockchain Explorers
* [Cosmos Explorer](https://explorecosmos.network/)
* [nylira.net](https://nylira.net/)



### Relevant Documentation
* [Cosmos Overview](https://blog.cosmos.network/understanding-the-value-proposition-of-cosmos-ecaef63350d)
* [Token Economics - Cosmos](https://blog.cosmos.network/economics-of-proof-of-stake-bridging-the-economic-system-of-old-into-the-new-age-of-blockchains-3f17824e91db) - Validator rewarded via multiple whitelisted tokens
  * [Ethereum Hardspoon](https://blog.cosmos.network/introducing-the-hard-spoon-4a9288d3f0df) - Moving Tokens from Ethereum to Cosmos
* Whitepapers
  * [Cosmos Whitepaper](https://github.com/cosmos/cosmos/blob/master/WHITEPAPER.md)
  * [Tendermint Whitepaper](https://tendermint.com/static/docs/tendermint.pdf)
* Ecosystems
  * [Projects](https://forum.cosmos.network/t/list-of-projects-in-cosmos-tendermint-ecosystem/243)
  * [Partners](https://tendermint.com/ecosystem)
  * [Investments](https://forum.cosmos.network/t/community-funding/793/2)
  * [Validators](https://forum.cosmos.network/t/validator-candidates/127)
* [Cosmos Documentation](https://cosmos.network/docs/)
* [Cosmos SDK Tutorial](https://github.com/cosmos/sdk-application-tutorial)
* [Cosmos vs Polkadot](https://medium.com/@davekaj/blockchain-interoperability-cosmos-vs-polkadot-48097d54d2e2)
* [Tendermint Evaluation](https://jepsen.io/analyses/tendermint-0-10-2)
* [Architectural Decision Records](https://github.com/tendermint/tendermint/blob/master/docs/architecture/README.md)
* [Bug Bounty Program](https://blog.cosmos.network/bug-bounty-program-for-tendermint-cosmos-833c67693586)


### Relevant Code Links

**Key Repositories**
* [Cosmos Whitepaper](https://github.com/cosmos/cosmos/blob/master/WHITEPAPER.md)
* [Tendermint](https://github.com/tendermint)
  * [Application BlockChain Interface (ABCI)](https://github.com/tendermint/tendermint/tree/master/abci)
    * [ABCI Protobuf Definition](https://github.com/tendermint/tendermint/blob/develop/abci/types/types.proto)
* [go-amino](https://github.com/tendermint/go-amino)
* [IAVL](https://github.com/tendermint/iavl) - Merkleized IAVL+ Tree implementation in Go
* [HOG](https://github.com/HogLang/hog)
* [Cosmos SDK](https://github.com/cosmos/cosmos-sdk)

**Functional Breakdown**
* Persistence
  * Storage
    * [488 - StateDB Refactor](https://github.com/cosmos/ethermint/pull/488)
  * Light Client
  * Node
  * Validator
    * [Validator List](https://forum.cosmos.network/t/validator-candidates/127)
  * Archive Node
* Distribution
  * Discovery
  * Gossip
    * [Amino vs Proto Encoding issue](https://github.com/tendermint/tendermint/issues/2682)
    * [Protobuf Encoding (including zigzag)](https://developers.google.com/protocol-buffers/docs/encoding)
  * Consensus
    * Block Finality
      * [Proposal to Optimize the Consensus](https://github.com/tendermint/tendermint/issues/2691)
        * [Core Consenus Update 2696](https://github.com/tendermint/tendermint/pull/2696)
* Security
  * Signing
    * [2554 -gaicli multisig ready](https://github.com/cosmos/cosmos-sdk/pull/2554)
  * Hashing
  * Privacy
* Governance
  * Staking
    * [Vesting Accounts](https://github.com/cosmos/cosmos-sdk/blob/e9295252251417c86f29b294563228f076652d5b/docs/spec/auth/vesting.md)
    * [Proposer Rewards](https://github.com/cosmos/cosmos-sdk/issues/588)
  * Voting
  * Proposals
    * [Governance Design Overview](https://github.com/cosmos/cosmos-sdk/blob/develop/docs/spec/governance/overview.md)
    * [2385 - Coins for Deposits](https://github.com/cosmos/cosmos-sdk/issues/2385)
* Chaincode
  * See WASM above
* Deployment
* Interledger
  * Message Format
  * Relay Chain
  * Consensus Process
* Developer Tools
  * API
  * RPC
  * CLI
  * SDK
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

## Tendermint Prototyping

**Deploying a Substrate Chain**

**Deploying a Substrate Chain**

**Deploying Polkadot**

**Deploying a simple contract**

**Running a Transaction**

