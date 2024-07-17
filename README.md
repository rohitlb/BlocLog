# Blockchain-Enabled Product Validation System

The Blockchain-Enabled Product Validation System represents an innovative solution employing blockchain technology to combat counterfeit products across diverse industries. It leverages QR codes, smart contracts, and the Ethereum network to establish a secure and transparent platform for tracking and verifying product authenticity. This system plays a crucial role in tackling global supply chain challenges by diminishing the proliferation of counterfeit goods and bolstering transparency and trustworthiness.

## Overview
The Blockchain-Enabled Product Validation System is a groundbreaking solution designed to combat global supply chain issues related to counterfeit products. It leverages the unique capabilities of blockchain technology to provide a secure and transparent platform for tracking and verifying the authenticity of products across various industries.

The system uses QR codes, an overt technology that can be scanned by a smartphone app, to verify product information and origin. It employs smart contracts to store and execute product verification logic on the blockchain, ensuring tamper-proof data and trustless transactions. The Ethereum network serves as its decentralized database to store product information and status, accessible by authorized parties.

A web interface, powered by React, allows users to interact with the system and view product information and history. The technologies used in this system include Solidity for smart contract development, Hardhat for Ethereum development environment, React for building the user interface, Node.js for backend development, and ethers.js for interacting with the Ethereum blockchain.

This system is significant in solving global supply chain issues as it provides a reliable method to verify the authenticity of products, thereby reducing the prevalence of counterfeit goods. It enhances transparency and trust among stakeholders in the supply chain, from manufacturers to consumers.

## Basic Walkthrough
- The `BlocLog-backend-node` directory contains the codebase for the backend of the system.
- The `BlocLog-frontend-react` directory contains the codebase for the frontend of the system.
- The `BlocLog-postgres-database` directory contains the csv files for the backend database.
- The `BlocLog-smartcontract-solidity` directory contains the smart contract deployed to the Ethereum network.

## Technologies Used
- Solidity
- Hardhat
- React
- Node.js
- ethers.js

## Features
- **QR Codes**: The system utilizes QR codes, which are scanned by a smartphone app to verify product information and origin.
- **Smart Contracts**: Utilizes smart contracts to store and execute product verification logic on the blockchain, ensuring data integrity and secure transactions.
- **Ethereum Network**: Leverages the Ethereum network as a decentralized database for storing product information and status, accessible to authorized parties.
- **Web Interface**: Employs a web interface powered by React for user interaction, enabling access to product information and history.

## Project Setup
To get started with this project, 
1. Clone the repository.
2. In `BlocLog-postgres-database`, import the csv files to your own postgres database. 
3. In `BlocLog-backend-node`, run `npm i` to install the dependencies and change the postgres credentials to your postgres crediantials and run `node postgres.js` to start the backend execution.
4. In `BlocLog-frontend-react`, run `npm i` to install the dependencies and run `npm start` to start localhost.
5. You can inspect `BlocLog-smartcontract-solidity` directory to view the smart contract details that is deployed to the Sepolia Testnet.
6. To perform transactions, setup your Metamask wallet and connect your wallet to the Sepolia Tesnet Network and transact using SepoliaETH which can be obtained for free on Seplolia Faucet (https://sepoliafaucet.com/).