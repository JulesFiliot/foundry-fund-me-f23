# Smart Contract Fundraiser

## About
This project is a simple fundraiser smart contract that allows people to send ETH to the contract by calling a `fund` function. The owner of the contract can then withdraw the funds using the `withdraw` function. The contract is deployed on the Sepolia testnet at this address: [0xDe5a60245681F94Fb715a3d1A60134Bc31827aDa](https://sepolia.etherscan.io/address/0xDe5a60245681F94Fb715a3d1A60134Bc31827aDa).

This project was developed as an educational project to learn Solidity and Foundry development. The goal was to create a simple but functional smart contract that could be deployed on the Ethereum blockchain.

## Features

* Allows people to send ETH to the contract using the `fund` function.
* If ETH is sent to the contract without calling the fund function, it will still go through the fund function thanks to fallback and receive functions.
* Allows the owner of the contract to withdraw the funds using the `withdraw` function.
* Unit and integration tests are implemented.
* Fetches the current ETH price using the Chainlink data feeds.