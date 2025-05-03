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

## 🌍 Deployed Contract

- **Network:** Sepolia Testnet  
- **Contract Address:** [`0xBf700844e4E87E0B405A908E713fE444F438e3A0`](https://etherscan.io/address/0xBf700844e4E87E0B405A908E713fE444F438e3A0#code)
- **Verified on Etherscan:** ✅ [View Source](https://etherscan.io/address/0xBf700844e4E87E0B405A908E713fE444F438e3A0#code)
