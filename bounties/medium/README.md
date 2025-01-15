# Medium Bounties

## Active Bounties

### 1. ICRC-1 Token Implementation: 
Create and deploy an ICRC-1 Ledger and index canister on mainnet 
with custom name, supply and logo. Interact with it using [ic-js](https://internetcomputer.org/docs/current/developer-docs/developer-tools/on-chain/ic-js) and 
[dfinity/agent-js](https://www.npmjs.com/package/@dfinity/agent). Ensure you include the following functionalities: minting, 
transferring tokens, displaying transaction history for a specific account 
using the index canister.
- **Reward:** $200
    - Position 1: $120
    - Position 2: $80 
- **Start date:** 20th January 2025
- **Deadline:** 31st January 2025
- **Requirements:**
  - Deploy an ICRC-1 Ledger canister on mainnet with custom token name, symbol, and supply
  - Implement a custom logo for the token
  - Use the index canister to track transaction history
  - Implement token transfer functionality
  - Implement balance checking functionality
  - Use ic-js and dfinity/agent-js libraries for interacting with the canisters
  - Display transaction history for specific accounts using the index canister
  - (Optional) Implement ICRC-2 extension for approval functionality
  - Provide documentation on how to interact with the deployed token

For reference and guidance, you can look at the following resources:
1. [ICRC-1 Token Standard](https://github.com/dfinity/ICRC-1/tree/main/standards/ICRC-1#icrc-1-token-standard)
2. [ICRC-1 Ledger Setup Documentation](https://internetcomputer.org/docs/current/developer-docs/defi/tokens/ledger/setup/icrc1_ledger_setup)
3. [Token Transfer Sample](https://internetcomputer.org/docs/current/references/samples/rust/token_transfer/)
4. [Using ICPex to deploy your token](https://icpex.org/createToken)
5. [In app wallet demo](https://github.com/Stephen-Kimoi/ICP-to-do-examples/tree/main/examples/in_app_wallet#building-an-in-app-wallet-on-the-internet-computer)

### 2. ICRC-7 NFT Collection Implementation: 
Create and deploy an ICRC-7 NFT Collection with a frontend that allows someone to mint an NFT, track their minted NFTs, transfer NFT to 
user once purchased
- **Reward:** $200
    - Position 1: $120
    - Position 2: $80 
- **Start date:** 10th February 2025
- **Deadline:** 21st February 2025
- **Requirements:**
  - Deploy an ICRC-7 NFT Collection canister on ICP
  - Implement ICRC-37 extension for approval functionality
  - Create a frontend interface for minting, viewing, and transferring NFTs
  - Implement NFT minting functionality with custom metadata
  - Allow users to view their minted NFTs
  - Implement NFT transfer functionality
  - Implement query functions for NFT ownership and collection details
  - (Optional) Implement a basic marketplace functionality for NFT trading

For reference and guidance, you can look at the following resources:
1. [ICRC-7 Standard Specification](https://github.com/dfinity/ICRC/blob/main/ICRCs/ICRC-7/ICRC-7.md)
2. [ICRC-37 Standard Specification](https://github.com/dfinity/ICRC/blob/main/ICRCs/ICRC-37/ICRC-37.md)
3. [NFT Tutorial](https://internetcomputer.org/docs/current/tutorials/developer-journey/level-5/5.4-NFT-tutorial)
4. [ICRC NFT Example Repository](https://github.com/PanIndustrial-Org/icrc_nft.mo)

### 3. HTTPs Outcalls Oracle: 
Using HTTPs outcalls, create and deploy an on chain oracle that  uses HTTP outcalls to fetch current price data from the Coinbase API at regular 
intervals using timers, store it as a time series in your canister, 
and expose the data via query call on a frontend deployed to the ICP
- **Reward:** $200
    - Position 1: $120
    - Position 2: $80 
- **Start date:** 10th February 2025
- **Deadline:** 21st February 2025
- **Requirements:**
  - Implement a canister smart contract that uses HTTPS outcalls to fetch price data from the Coinbase API
  - Use timers to fetch data at regular intervals (e.g., every minute)
  - Implement proper error handling for API requests
  - Create a frontend interface to display the fetched price data
  - (Optional) Implement multiple cryptocurrency pairs
  - (Optional) Add basic analytics features (e.g., price change percentage, moving averages)

For reference and guidance, you can look at the following resources:
1. [HTTPS Outcalls Documentation](https://internetcomputer.org/docs/current/developer-docs/smart-contracts/advanced-features/https-outcalls/https-outcalls-how-to-use)
2. [Exchange Rate Canister](https://github.com/dfinity/exchange-rate-canister)
3. [HTTPS Outcalls GET Example](https://internetcomputer.org/docs/current/developer-docs/smart-contracts/advanced-features/https-outcalls/https-outcalls-get#get-example)