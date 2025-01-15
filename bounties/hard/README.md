# Hard Bounties

## Active Bounties

### 1. Cross-Chain Lending Protocol
Create a cross-chain decentralized lending protocol that accepts 
Bitcoin, Ethereum, and ICP as collateral. The protocol should:
use chain fusion for secure cross chain transactions
Implement ckBTC and ckETH for efficient handling of Bitcoin and 
Ethereum assets
- **Reward:** $300
    - Position 1: $180
    - Position 2: $120
- **Start date:** 20th January 2025
- **Deadline:** 7th February 2025
- **Requirements:**
  - Implement Chain Fusion technology for secure cross-chain transactions
  - Integrate ckBTC and ckETH for efficient handling of Bitcoin and Ethereum assets
  - Support multi-asset collateral including Bitcoin, Ethereum, and ICP
  - Create a frontend interface for users to interact with the lending protocol
  - Create functions for depositing and withdrawing collateral
  - (Optional) Implement a governance mechanism for protocol parameters
  - (Optional) Add support for additional ERC-20 tokens using ckERC20

For reference and guidance, you can look at the following resources:
1. [Chan fusion starter project](https://github.com/letmejustputthishere/chain-fusion-starter?tab=readme-ov-file#chain-fusion-starter-project)
2. [Ic alloy](https://github.com/ic-alloy/ic-alloy)
3. [Rust-based starter template for integrating ICP canisters with EVM-based smart contracts](https://github.com/Stephen-Kimoi/icp-evm-rust-bridge?tab=readme-ov-file#icp-evm-integration-starter-template)
2. [Chain Fusion Technology Overview](https://internetcomputer.org/docs/current/developer-docs/multi-chain/overview)
3. [ckBTC Overview](https://internetcomputer.org/docs/current/developer-docs/multi-chain/chain-key-tokens/ckbtc/overview)
4. [ckETH Overview](https://internetcomputer.org/docs/current/developer-docs/multi-chain/chain-key-tokens/cketh/overview)
5. [HTTPS Outcalls for Price Data](https://internetcomputer.org/docs/current/developer-docs/smart-contracts/advanced-features/https-outcalls/https-outcalls-how-to-use)

You should pay special attention to the following aspects:
1. Use the EVM RPC canister for communicating with Ethereum and other EVM blockchains, as mentioned in the [Ethereum Integration documentation](https://internetcomputer.org/docs/current/developer-docs/multi-chain/ethereum/evm-rpc/overview)
2. Utilize [threshold ECDSA](https://internetcomputer.org/docs/current/developer-docs/smart-contracts/signatures/t-ecdsa) signatures for secure cross-chain transactions, as explained in the [Ethereum Integration documentation](https://internetcomputer.org/docs/current/developer-docs/multi-chain/ethereum/using-eth/signing-transactions).

### 1. Multichain NFT Marketplace:
Develop a multi-chain NFT marketplace that supports NFTs on 
ICP (ICRC-7), Ethereum (ERC-721)
- **Reward:** $300
    - Position 1: $180
    - Position 2: $120
- **Start date:** 17th February 2025
- **Deadline:** 7th March 2025
- **Requirements:**
  - Implement cross-chain NFT minting and transfer functionality
  - Support ICRC-7 NFTs on ICP and ERC-721 NFTs on Ethereum
  - Implement Chain Fusion technology for secure cross-chain transactions
  - Create a frontend interface for users to interact with the marketplace
  - Integrate Internet Identity for user authentication on ICP
  - Implement Ethereum wallet integration (e.g., MetaMask) for Ethereum interactions

For reference and guidance, developers can look at the following resources:
1. [ckNFT project showcasing how to intergrate ICRC7 NFTs with EVM Blockchains](https://github.com/b3hr4d/cknft)
2. [ICRC-7 Standard Specification](https://github.com/dfinity/ICRC/blob/main/ICRCs/ICRC-7/ICRC-7.md)
3. [NFT Tutorial](https://internetcomputer.org/docs/current/tutorials/developer-journey/level-5/5.4-NFT-tutorial)