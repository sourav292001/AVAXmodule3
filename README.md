# CustomToken Smart Contract

The CustomToken smart contract is an ERC-20 compliant token with additional functionalities. It is implemented using the Solidity programming language and is built upon the OpenZeppelin library.

## Description

The CustomToken contract inherits from the OpenZeppelin's ERC20 contract, which implements the ERC-20 standard for fungible tokens, and the Ownable contract, which provides basic ownership functionality. This token allows you to perform basic token operations like transferring, minting, and burning tokens.

## Features

.ERC-20 Compatibility: The contract follows the ERC-20 standard, which allows it to be compatible with other applications, wallets, and exchanges that support this standard.

.Minting: The contract creator (initial deployer) can mint new tokens using the mint function. Only the contract owner has the authority to mint tokens.

.Burning: Token holders can burn their own tokens using the burn function. This reduces the token supply.

.Transfer with Valid Address Check: The transfer function overrides the standard ERC-20 transfer method to ensure that the recipient's address is not the zero address.

## Getting Started

To use the CustomToken smart contract, follow these steps:

.Install required dependencies:

Install Node.js and npm (Node Package Manager) if not already installed.
Run npm install @openzeppelin/contracts to install the OpenZeppelin contracts library.
.Deploy the contract:

Deploy the CustomToken contract by providing a name and symbol for your token.
.Interact with the contract:

Mint new tokens: Call the mint function as the contract owner to create new tokens.
Burn tokens: Call the burn function to destroy a specific amount of your own tokens.
Transfer tokens: Use the standard transfer function to send tokens to other addresses.

## License

This code is licensed under the MIT License. See LICENSE for more information.

