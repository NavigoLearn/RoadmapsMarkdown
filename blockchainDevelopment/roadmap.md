# Blockchain Development

## Prerequisites

- Basic programming skills
- (Recommended) Basic web development skills. This will lets us create user interfaces for our blockchain applications. Any language is fine, but in this roadmap we will be working with react.
- Git for version control https://www.youtube.com/watch?v=HkdAHXoRtos
- Protocol buffers https://www.youtube.com/watch?v=46O73On0gyI&pp=ygUQcHJvdG9jb2wgYnVmZmVycw%3D%3D
- gRPC https://medium.com/swlh/grpc-fundamental-and-concept-93414d7956df
- (Recommended) Javascript. We will be mostly using javascript for frontend backend in this roadmap, but you can choose any other language

## Important disclaimer

- You want to learn blockchain development? Great, however there are a few things to keep in mind:
  - Keep practicing, once you learn something try it out.
  - Write side projects. This is a great way to solidify your learnings
  - Use a testnet, remix IDE or a software like hardhat to test your code, running your testing on mainnet is expensive. You will learn more about this in the theory section.
  - Never sign unknown transactions or connect your wallet to websites you do not trust
  - Use an empty wallet for development, remember blockchains transactions cannot be reversed!!
  - To use testnets you need testnet tokens, I included testnet token faucet in this roadmap. Remember this are free test tokens that allows you to run your code.
  - Backend develoment
  - Database

## Theory

### Basic terminology

- This parts will introduces you to the basics of blockchain. This part is generalized and will apply to most popular blockchain, we will dive later into specific blockchains and programming languages. You will frequently encounter this terminology included here while working on blockchain, technology so it's important to not dismiss the theory section.
  - What is a blockchain? https://www.youtube.com/watch?v=SSo_EIwHSd4
  - Types of blockchains https://www.youtube.com/watch?v=Jc0NwgqCtik
  - Light node vs full node https://www.youtube.com/watch?v=Jc0NwgqCtik
  - Why use a blockchain https://medium.com/coinmonks/why-do-we-need-blockchain-63b706b542b5
  - What is a Cryptocurrency Wallet https://www.youtube.com/watch?v=SQyg9pyJ1Ac
  - What are smart contracts https://www.youtube.com/watch?v=hb5lifYSJt8&list=PLG4Yor99jlgmJS7cptBvER0HKFwa9cGSG&index=11
  - What are Unstoppable Domains? https://www.youtube.com/watch?v=O-RO4tWA0Rs
  - What are Oracles? https://www.youtube.com/watch?v=ZJfkNzyO7-U
  - What is a DEX? https://www.youtube.com/watch?v=2tTVJL4bpTU
  - What is an NFT? https://www.youtube.com/watch?v=4dkl5O9LOKg
  - What is a DAO? https://www.youtube.com/watch?v=KHm0uUPqmVE
  - What are Layer 2s Rollups? Plasma? Sidechains? Channels? https://www.youtube.com/watch?v=9pJjtEeq-N4
  - IPFS: Interplanetary file storage https://www.youtube.com/watch?v=5Uj6uR3fp-U
  - What is Crypto Arbitrage https://www.youtube.com/watch?v=b3BcH5DvC-Q

### Consensus mechanisms

- PoA vs PoW vs PoS Blockchain https://www.youtube.com/watch?v=2EabDUGIkBg&list=PLG4Yor99jlgmJS7cptBvER0HKFwa9cGSG&index=12
- Blockchain vs Hashgraph vs DAG vs Holochain https://www.youtube.com/watch?v=JjMWrXqsrUs&list=PLG4Yor99jlgmJS7cptBvER0HKFwa9cGSG&index=13
- How does bitcoin works: https://www.youtube.com/watch?v=bBC-nXj3Ng4
- Zero Knowledge Proofs https://www.youtube.com/watch?v=5qzNe1hk0oY

## Blockchain fundamuntals

- This is an important part in understanding blockchains and it's inner workings. Take your time to understand all concepts explained here.
  - Data structures https://www.youtube.com/watch?v=8hly31xKli0
  - Everything You Need to Know About Distributed Ledger Technology (DLT) https://medium.com/@upGrad/everything-you-need-to-know-about-distributed-ledger-technology-8e3d26703b78
  - What is a block in blockchain? https://medium.com/coinmonks/what-is-a-block-in-blockchain-explained-simply-b4730a189473
  - What are Blockchain Nodes? https://medium.com/eligma-blog/what-are-blockchain-nodes-aa98fb6c620f
  - Block Cyphers https://medium.com/@srupa.thota/block-ciphers-and-modes-of-operation-ef55edaf547e
  - Hashing https://medium.com/@agoipraise/an-introduction-to-cryptographic-hash-functions-2f89ababbf2a
  - Merkle Tree https://www.youtube.com/watch?v=n6nEPaE7KZ8
  - Public and Private Keys (Asymmetric Encryption Animated) https://www.youtube.com/watch?v=p_LWJgTBIFs
  - Mempool https://medium.com/coinmonks/bitcoin-mempool-simply-explained-7f76be235e85
  - Blockchain types : Public, private, hybrid or consortium https://www.techtarget.com/searchcio/feature/What-are-the-4-different-types-of-blockchain-technology

## Improvement proposals

- We will focus mainly on ethereum and bitcoin improvement proposals for this section

### Bitcoin Improvement Proposals

- In this section we will cover what BIPs are, along the most important ones that got passed.
  - What Is a Bitcoin Improvement Proposal (BIP)? https://www.ledger.com/academy/what-is-a-bitcoin-improvement-proposal-bip
  - This thread covers the most important BIPs https://www.reddit.com/r/Bitcoin/comments/ua5g7r/the_most_impactful_bitcoin_improvement_proposals/?utm_source=share&utm_medium=web2x&context=3

### Ethereum Improvement Proposals

- In this section we will cover what EIPs are, along the most important ones that got passed.
  - What Are Ethereum Improvement Proposals (EIPs)? https://www.ledger.com/academy/what-is-a-bitcoin-improvement-proposal-bip
  - This thread covers the most important EIPs https://medium.com/ngrave/top-ethereum-improvement-proposals-eips-explained-eip-20-eip-721-eip-1559-eip-3672-6f6a50c04b0a

## Scaling mechanisms

### Layer 1

- Sharding https://omoya.medium.com/what-is-sharding-on-blockchains-8100ae78c969

### Layer 2

- Sidechains https://medium.com/coinmonks/what-are-sidechains-1c035097d8df
- Rollups https://medium.com/coinmonks/ethereum-scaling-solutions-understanding-rollups-5b2ae3528fbc
- Lightning Network https://medium.com/blockchain/the-lightning-network-explained-f3982356f87e

## Understanding blockchain security

- Security is a crucial part of blockchain development. In this section we explore different security concepts that you will encounter in your career.
  - MULTISIG wallets https://medium.com/coinmonks/multisig-wallet-explained-with-code-example-6fb4a663ab29
  - What is a Honeypot? https://www.kaspersky.com/resource-center/threats/what-is-a-honeypot
  - What Is 51% Attack? https://medium.com/crypto-wisdom/what-is-51-attacks-in-cryptocurrency-how-does-it-work-ca8642283e43
  - What is Phishing? https://medium.com/@Mailfence/social-engineering-what-is-phishing-673ec9f0b1e2

## Solidity

### Beginner

    - Solidity is an object-oriented programming language for implementing smart contracts on EVM blockchains, most notably, Ethereum.
    - Most used tools in this section:
        - Remix IDE: Lets you write and run solidity from your browser. Great for starting out. https://remix.ethereum.org/
        - ether.js : JS library that allows us to interact with smart contract and fetch information from the blockchain: https://docs.ethers.org/v5/
        - Hardhat: Local development environment that lets you deploy, run, test, and debug your contracts. We will learn more about hardhat later on
    - What is the EVM? https://www.youtube.com/watch?v=sTOcqS4msoU
    - How To Create a ERC20 Token  https://www.youtube.com/watch?v=8N0lLN26BIE
    - Solidity basics: https://www.youtube.com/watch?v=RQzuQb0dfBM
    - How to Interact with Blockchain using Ethers.js https://medium.com/coinmonks/how-to-interact-with-blockchain-using-ethers-js-7d0be4a8a6e8
    - Guide to IPFS https://medium.com/virtuslab/the-complete-beginners-guide-to-ipfs-9713a6f59193
    - Hardhat https://medium.com/coinmonks/writing-your-first-smart-contract-with-hardhat-b93e8d07eaeb

### Medium: Creating projects guide

- Now that you got the basics covered, in this section i will include various project ideas you can build along with their guides:
  - Build an NFT marketplace DApp like OpenSea https://dev.to/yakult/tutorial-build-a-nft-marketplace-dapp-like-opensea-3ng9
  - Create an NFT https://www.youtube.com/watch?v=FXLAFpOS_kQ
  - Build a AMM https://www.youtube.com/watch?v=RcvJtGZg3v4

### Advanced

- Uniswap V3 Tutorial: https://www.youtube.com/watch?v=GwMyv7CmoRs
- Flash Swaps & Arbitrage on Uniswap V3 Pools https://www.youtube.com/watch?v=bNK3lg7Tjj4
- Integrating Chainlink Oracles With Smart Contracts https://medium.com/0xcode/integrating-chainlink-oracles-with-smart-contracts-on-the-ethereum-blockchain-a1578e8b5151
- Hashed Timelock Contract vs Delayed-Proved Timelock Contract https://medium.com/@qizhou_63115/cross-l2-bridge-hashed-timelock-contract-vs-delayed-proved-timelock-contract-7e738dd2094e

### Smart contract security

    - If you reached this far, congratulations. In this part we will focus on smart contract security
        - How to Audit a Smart Contract https://www.youtube.com/watch?v=TmZ8gH-toX0
        - Slither : Solidity & Vyper static analysis framework. Really helpful for beginners https://github.com/crytic/slither
        - Advanced Web3 Security Course (if you want to learn auditing smart contracts i highly recomment watching the full video as it covers many interesting vulnerabilites that can be found in solidity code) https://www.youtube.com/watch?v=DRZogmD647U
        - This channel has amazing content on audtiting smart contracts: https://www.youtube.com/@0xOwenThurm/videos
        - Demystifying EVM Opcodes https://www.youtube.com/watch?v=_tcyI_lNvo0

## Bitcoin development

### Ordinals

- What are ordinals?
- Code and documentation can be seen here: https://github.com/ordinals/ord

### L2

- Read more about bitcoin L2s and why it's important: https://trustmachines.co/blog/the-rise-of-bitcoin-layer-2/

#### Stacks

- What is Stacks and How Does It Work? https://trustmachines.co/learn/what-is-stacks/
- Stacks lets you write smart contracts using Clarity. You can check it's documentation here
- Writig NFT smart contracts with clarity: https://www.youtube.com/watch?v=JklBYvkWoNc

#### Liquid Network

- What is Liquid Network? https://trustmachines.co/learn/what-is-liquid-network/

## Advanced

### Atomic Swaps

- Atomic Swaps : What are they? and how do they work? https://medium.com/coinmonks/atomic-swaps-what-are-they-and-how-do-they-work-bc7f84e4b7f3
- Here is an example of a ETH-XMR atomic swap project, feel free to look at the source code https://github.com/AthanorLabs/atomic-swap
