# Mytoken

A simple ERC-20-like token named "COPPER" (symbol: CPR) implemented in Solidity.

## Description

Mytoken is a basic smart contract for an ERC-20-like token on the Ethereum blockchain. It allows minting and burning tokens, with balances tracked for each address.

## Summary

In this project, I have developed a smart contract using Solidity to create a custom cryptocurrency named COPPER (CPR). The contract includes functions to mint new tokens and burn existing ones, effectively managing the total supply. This contract provides a foundational framework for understanding and implementing token-based economies on the Ethereum blockchain.

## Getting Started

### Installing

1. Clone the repository:
   ```sh
   git clone https://github.com/jvjitendra/mytoken.git
   cd mytoken
   ```

2. Open the contract in Remix IDE:
   - Go to [Remix IDE](https://remix.ethereum.org/)
   - Create a new file and paste the contents of `Mytoken.sol`
   - Compile the contract

### Deploying the Contract

1. Deploy using Remix:
   - Select the environment (e.g., JavaScript VM, Injected Web3 for MetaMask)
   - Click "Deploy" and confirm the transaction in your wallet

### Interacting with the Contract

- **Minting Tokens:**
  ```sh
  Mytoken.methods.mint('recipient_address', amount).send({from: 'your_address'});
  ```
- **Burning Tokens:**
  ```sh
  Mytoken.methods.burn('sender_address', amount).send({from: 'your_address'});
  ```
- **Checking Balances:**
  ```sh
  Mytoken.methods.balances('address').call();
  ```

## Authors

- **Jitendra**
  - GitHub: [@jvjitendra](https://github.com/jvjitendra)
  - Email: Jitendra.indiamart1999@gmail.com
