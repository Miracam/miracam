# miracam

Our world is filled with fake photos—AI-generated or edited. Miracam aims to Make Image Real Again (MIRA). We mint all shots as NFTs with hardware-generated signatures to prove authenticity. Private shots are encrypted and wallet-controlled, preserving privacy on-chain.

## Repositories

- [Mobile Client](https://github.com/Miracam/mobile-client): Native mobile client to capture real photo, create Apple Attested Secure Enclave Keypairs (TEE), encrypt content with the help of Lit Protocol and manage access control with Sign Protocol
- [API](https://github.com/Miracam/api): API server, js, hono framework
- [EVM Contracts](https://github.com/Miracam/contracts): Solidity contracts for nft, permit2 token using EIP1271, p256 verifier using EIP7212, and Push Protocos
- [Substreams](https://github.com/Miracam/substreams): Substreams Package auto generated with `substream init`, tracking both nft and Apple Attestation validator contract
- [Chainlink contract](https://github.com/Miracam/chainlink-contract): This contract is a forked from chainlink function hardhat starter kit, modified with purpose to verify Apple secure enclave attestation on chain
- [Substreams Sink](https://github.com/Miracam/substream-sink): Substreams JS Sink run on substreams package, to stream data from blockchain to our database
- [Phala Playground](https://github.com/Miracam/phala): Phala playground, trying to setup a js server to validate Apple Secure Enclave Attestation in decentralized and permissionless way, failed at verifying X509 cert
- [Playground](https://github.com/Miracam/playground): Playground, experiment with lit and sign protocol
