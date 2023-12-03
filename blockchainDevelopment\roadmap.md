# Blockchain Development

## Prerequisites

- Basic programming skills
- (Recommended) Basic web development skills. This will lets us create user interfaces for our blockchain applications. Any language is fine, but in this roadmap we will be working with react.
- Git for version control
- Protocol buffers https://www.youtube.com/watch?v=46O73On0gyI&pp=ygUQcHJvdG9jb2wgYnVmZmVycw%3D%3D
- gRPC https://medium.com/swlh/grpc-fundamental-and-concept-93414d7956df
- (Recommended) Javascript. We will be mostly using javascript for frontend backend in this roadmap, but you can choose any other language

## Important disclaimer

- You want to learn blockchain development? Great, however there are a few things to keep in mind:
  - Keep practicing, once you learn something try it out.
  - Write side projects. This is a great way to solidify your learnings
  - Use a testnet to test your code, running your testing on mainnet is expensive. You will learn more about this in the theory section.
  - Never sign unknown transactions or connect your wallet to websites you do not trust
  - Use an empty wallet for development, remember blockchains transactions cannot be reversed!!

## Theory

### Basic terminology

- This parts will introduces you to the basics of blockchain. This part is generalized and will apply to most popular blockchain, we will dive later into specific blockchains and programming languages. You will frequently encounter this terminology included here while working on blockchain, so it's important to not dismiss the theory section.
  - What is a blockchain? https://www.youtube.com/watch?v=SSo_EIwHSd4
  - Types of blockchains https://www.youtube.com/watch?v=Jc0NwgqCtik
  - Light node vs full node https://www.youtube.com/watch?v=Jc0NwgqCtik
  - Why use a blockchain https://medium.com/coinmonks/why-do-we-need-blockchain-63b706b542b5
  - What are smart contracts https://www.youtube.com/watch?v=hb5lifYSJt8&list=PLG4Yor99jlgmJS7cptBvER0HKFwa9cGSG&index=11
  - What are Unstoppable Domains? https://www.youtube.com/watch?v=O-RO4tWA0Rs
  - What are Oracles? https://www.youtube.com/watch?v=uycQ7ReSt_c
  - What is a DEX? https://www.youtube.com/watch?v=2tTVJL4bpTU
  - Public and Private Keys (Asymmetric Encryption Animated) https://www.youtube.com/watch?v=p_LWJgTBIFs
  - What is an NFT? https://www.youtube.com/watch?v=4dkl5O9LOKg
  - What is a DAO? https://www.youtube.com/watch?v=KHm0uUPqmVE
  - What are Layer 2s Rollups? Plasma? Sidechains? Channels? https://www.youtube.com/watch?v=9pJjtEeq-N4
  - IPFS: Interplanetary file storage https://www.youtube.com/watch?v=5Uj6uR3fp-U

### Consensus mechanisms

- PoA vs PoW vs PoS Blockchain https://www.youtube.com/watch?v=2EabDUGIkBg&list=PLG4Yor99jlgmJS7cptBvER0HKFwa9cGSG&index=12
- Blockchain vs Hashgraph vs DAG vs Holochain https://www.youtube.com/watch?v=JjMWrXqsrUs&list=PLG4Yor99jlgmJS7cptBvER0HKFwa9cGSG&index=13
- How does bitcoin works: https://www.youtube.com/watch?v=bBC-nXj3Ng4
- Zero Knowledge Proofs https://www.youtube.com/watch?v=5qzNe1hk0oY

## Blockchain fundamuntals

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

### Medium

- Now that you got the basics covered, in this section i will include various project ideas you can build along with their guides:
  - Build an NFT marketplace DApp like OpenSea https://dev.to/yakult/tutorial-build-a-nft-marketplace-dapp-like-opensea-3ng9
  - Hardhat https://medium.com/coinmonks/writing-your-first-smart-contract-with-hardhat-b93e8d07eaeb

## Smart contract security

    - If you reached this far, congratulations. In this part we will focus on smart contract security
    - Demystifying EVM Opcodes https://www.youtube.com/watch?v=_tcyI_lNvo0
