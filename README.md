# 🎰 Lottery Ticket - Solidity

A decentralized lottery smart contract built using Solidity on the Ethereum blockchain.

Participants can enter the lottery by sending **1 ETH** to the contract. Once at least 3 players have joined, the manager can select a random winner who receives the entire prize pool.

## 🚀 Features

* 1 ETH lottery entry
* Minimum 3 participants required
* Random winner selection
* Automatic prize distribution
* Manager-controlled draw
* Fully decentralized and transparent

## 🛠 Tech Stack

* Solidity ^0.8.19
* Ethereum
* Remix IDE

## 📦 Deployment

1. Open Remix IDE.
2. Create a new file and paste the `Lottery.sol` code.
3. Compile the contract using Solidity Compiler.
4. Go to **Deploy & Run Transactions**.
5. Select the desired environment.
6. Deploy the contract.

## 🎮 How to Use

### Enter the Lottery

* Connect a wallet/account.
* Send exactly **1 ETH** to the contract address.
* Your address will be added to the participants list.

### Check Contract Balance

* Call `getBalance()`.
* Only the manager can view the balance.

### Select Winner

* Ensure at least **3 participants** have joined.
* Manager calls `selectWinner()`.
* A random winner is chosen.
* The entire prize pool is transferred to the winner.

## 📚 Concepts Covered

* Smart Contracts
* Payable Functions
* Ether Transfers
* Arrays
* Constructors
* Access Control
* Random Number Generation
