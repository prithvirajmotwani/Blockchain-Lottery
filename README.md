# Blockchain Lottery System

## Overview
This project is a decentralized lottery system built on the **Ethereum blockchain** with a **React.js** frontend. It enables users to securely enter a lottery, with a smart contract handling entries, selecting winners, and distributing rewards transparently.

## Features
- **Smart Contract (Solidity):** Implements lottery logic with functions for player entry, random winner selection, and fund distribution.
- **Blockchain Integration (Web3.js):** Connects the frontend to Ethereum for seamless interaction.
- **Secure Transactions:** Ensures fair participation using Ethereum transactions with a minimum entry fee.
- **React Frontend:** Displays lottery status in real-time and allows users to participate easily.
- **Deployment & Testing:** Smart contract deployed on an Ethereum test network and tested using JavaScript scripts.

## Tech Stack
- **Blockchain:** Ethereum, Solidity
- **Frontend:** React.js
- **Backend Integration:** Web3.js
- **Development Tools:** Node.js, JavaScript

## Setup Instructions
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/blockchain-lottery.git
   ```
2. Install dependencies:
   ```sh
   cd blockchain-lottery
   npm install
   ```
3. Deploy the smart contract (requires an Ethereum test network and Infura setup):
   ```sh
   node deploy.js
   ```
4. Start the React frontend:
   ```sh
   cd lottery-react
   npm start
   ```

