# ERC20 and Vault Contracts

## Overview
This project consists of two Solidity smart contracts:

1. **ERC20 Token Contract**: Implements a standard ERC20 token to serve as in-game currency, allowing for minting, transferring, and balance tracking of tokens.
2. **Vault Contract**: Provides a secure mechanism for storing and managing tokens, allowing users to deposit and withdraw their ERC20 tokens safely.

## Setup
1. Clone the repository.
2. Compile the contracts using Solidity 0.8+ with Hardhat or Truffle.
3. Deploy the **ERC20 contract** first to create the token.
4. Deploy the **Vault contract**, passing the ERC20 token's address during deployment to link the contracts.

## Usage
- **ERC20 Contract**:
  - Functions: `transfer`, `approve`, `allowance`, `mint`, `balanceOf`, and more.
  - Token holders can transfer and manage allowances for others.
  
- **Vault Contract**:
  - Functions: `deposit`, `withdraw`, `getBalance`.
  - Users can securely store their tokens by depositing them into the vault and withdraw them anytime.

## Testing
- Use Hardhat/Truffle to run unit tests located in the `test` folder for both contracts.

## License
MIT License

