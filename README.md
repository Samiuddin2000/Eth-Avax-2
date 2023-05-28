# Eth-Avax-2
# ERC20 Token Contract

This is a simple ERC20 token contract that allows for token minting by the contract owner, token transfers by any user, and token burning by any user.

## Requirements

- Solidity ^0.8.0
- OpenZeppelin Contracts v4.3.0

## Installation

1. Clone the repository:

2. Install the required dependencies:

## Usage

1. Deploy the ERC20 token contract by providing the desired `name` and `symbol` parameters.

2. Mint Tokens:
- Only the contract owner can mint tokens.
- Use the `mint` function to mint new tokens, providing the recipient address and the amount of tokens to mint.

3. Transfer Tokens:
- Any user can transfer tokens.
- Use the `transfer` function to transfer tokens, providing the recipient address and the amount of tokens to transfer.

4. Burn Tokens:
- Any user can burn their own tokens.
- Use the `burn` function to burn tokens, providing the amount of tokens to burn.

# License
This ERC20 token contract is licensed under the MIT License.

Feel free to copy and paste this template into a README.md file in your GitHub repository and customize it as needed.

