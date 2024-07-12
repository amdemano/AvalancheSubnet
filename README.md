# ERC20 and Vault Smart Contracts

This repository contains two Solidity smart contracts: an ERC20 token contract and a Vault contract that interacts with the ERC20 token.

## Description

The ERC20 contract is a basic implementation of the ERC20 token standard, providing functionalities such as transfer, approve, transferFrom, mint, and burn.

The Vault contract is designed to work with any ERC20 token, allowing users to deposit and withdraw tokens. The Vault mints shares to represent a user's stake in the Vault when they deposit tokens and burns those shares when they withdraw tokens.

## Getting Started

### Installing

1. Clone the repository:

```bash
git clone <repository-url>
cd erc20-vault-smart-contracts
```
2. Open the Solidity files in Remix or your preferred Solidity development environment.

### Executing program
1. Deploy the ERC20 Contract:
- Open ERC20.sol in Remix.
- Compile the contract.
- Deploy the contract to a test network or the Ethereum mainnet.

2. Deploy the Vault Contract:
- Open Vault.sol in Remix.
- Compile the contract.
- Deploy the contract, passing the address of the deployed ERC20 contract as a parameter to the constructor.

3. Interact with the Contracts:
- Use the ERC20 contract to mint tokens to your address.
- Use the Vault contract to deposit tokens into the vault and receive shares.
- Withdraw tokens from the vault by burning shares.

## Help
For any issues or questions, please open an issue.

### Authors
Ashley Demano

### License
This project is licensed under the MIT License - see the LICENSE.md file for details.
