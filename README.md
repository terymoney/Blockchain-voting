Blockchain Voting System
Overview
The Blockchain Voting System is a decentralized application (DApp) built on the Ethereum blockchain. It ensures secure and transparent voting, making sure each vote is accurately counted and cannot be tampered with.

Features
Decentralized Voting: All votes are stored on the blockchain, ensuring transparency and immutability.

Secure and Private: Only authorized users can vote, and each user can vote only once.

Real-Time Updates: Voting results are updated in real-time and can be viewed instantly.

Prerequisites
Before running the project, ensure you have the following installed:

Node.js

Truffle

Ganache

MetaMask

Getting Started
Step 1: Clone the Repository
Clone the repository to your local machine:

sh
git clone https://github.com/terymoney/Blockchain-voting.git
cd Blockchain-voting
Step 2: Install Dependencies
Install the required dependencies for the project:

sh
npm install
Step 3: Compile the Smart Contracts
Compile the smart contracts using Truffle:

sh
truffle compile
Step 4: Deploy the Smart Contracts
Deploy the smart contracts to Ganache:

sh
truffle migrate --reset
Step 5: Configure MetaMask
Open MetaMask and add a custom RPC network with the following details:

Network Name: Ganache

New RPC URL: http://127.0.0.1:7545

Chain ID: 1337 (or 5777 if not using the default Ganache chain ID)

Import an account from Ganache into MetaMask by copying the private key from Ganache and using the "Import Account" feature in MetaMask.

Step 6: Start the React Application
Navigate to the voting-frontend directory and start the React application:

sh
cd voting-frontend
npm start
Step 7: Interact with the Application
Open your browser and go to http://localhost:3000 to interact with the Blockchain Voting System. Ensure MetaMask is connected to the correct account and network.
