# Election DApp

A decentralized voting application built on Ethereum blockchain technology.

## Description

Election DApp is a blockchain-based voting system designed to provide a secure, transparent, and efficient platform for conducting elections. It leverages smart contracts to manage the voting process, offer voter incentives, and ensure tamper-proof results.

## Features

- Admin interface for election management
- Candidate registration
- Timed voting periods with scheduling options
- ERC20 token rewards for voters
- Optional preference-matching voting system
- Real-time result calculation and display

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/election-dapp.git
   cd election-dapp
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Set up a local blockchain (e.g., Ganache) or connect to a testnet.

4. Compile and migrate smart contracts:
   ```
   truffle compile
   truffle migrate
   ```

5. Start the development server:
   ```
   npm run dev
   ```

## Usage

### Admin Interface

1. Access the admin interface at `http://localhost:3000/admin`
2. Use the interface to add candidates, set up the voter registry, and manage election timing.

### Voter Interface

1. Access the voter interface at `http://localhost:3000`
2. Connect your Ethereum wallet (e.g., MetaMask)
3. Cast your vote or fill out the preference questionnaire
4. Receive ERC20 tokens as a reward for voting
