# BidToken

BidToken is a simple ERC20 token smart contract written in Solidity.

## Description

BidToken is an ERC20 token that allows for the minting, burning, and transferring of tokens. It inherits from the OpenZeppelin ERC20 and Ownable contracts, which provide standard functionality for ERC20 tokens and ownership management, respectively.

## Features

- Minting: The contract owner can create new tokens and assign them to any address.
- Burning: Token holders can destroy a specific amount of their own tokens, reducing the total supply.
- Transferring: Token holders can transfer tokens to other addresses.

## Usage

To deploy the BidToken contract, simply deploy it to a supported Ethereum network (e.g., Ethereum mainnet, Ropsten testnet) using a compatible Ethereum development tool (e.g., Remix, Truffle).

After deployment, the contract owner can mint new tokens to any address using the `mint` function. Token holders can burn their own tokens using the `burn` function, and transfer tokens to other addresses using the standard ERC20 `transfer` function.

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.
The SPDX-License-Identifier header `// SPDX-License-Identifier: MIT` indicates that the project is licensed under the MIT License.

## Author
Avinash 
avinashreddy777890@gmail.com
