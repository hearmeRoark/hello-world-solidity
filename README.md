# Hello World - Solidity Smart Contract

This is my first deployed smart contract written in Solidity and deployed to the Ethereum Sepolia testnet using Remix and MetaMask.

## 🧠 What It Does

This contract stores a single public message:  
**"Hello World"**

## 🛠️ Tech Stack

- Solidity `^0.8.0`
- Remix IDE
- MetaMask
- Sepolia Testnet
- Etherscan

## 📄 Contract Code

```solidity
// SPDX-License-Identifier: GPL-3.0
pragma solidity ^0.8.0;

contract HelloWorld {
    string public message = "Hello World";
}