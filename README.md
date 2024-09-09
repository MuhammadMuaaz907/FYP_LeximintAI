AI NFT Generator
Technology Stack & Tools
Solidity (Writing Smart Contracts & Tests)
Javascript (React & Testing)
Hardhat (Development Framework)
Ethers.js (Blockchain Interaction)
React.js (Frontend Framework)
NFT.Storage (Connection to IPFS)
Hugging Face (AI Models)
Requirements For Initial Setup
Install NodeJS
Setting Up
1. Clone/Download the Repository
2. Install Dependencies:
$ npm install

3. Setup .env file:
Before running any scripts, you'll want to create a .env file with the following values (see .env.example):

REACT_APP_HUGGING_FACE_API_KEY=""
REACT_APP_NFT_STORAGE_API_KEY=""
You'll need to create an account on Hugging Face, visit your profile settings, and create a read access token.

You'll also need to create an account on NFT.Storage, and create a new API key.

4. Run tests
$ npx hardhat test

5. Start Hardhat node
$ npx hardhat node

6. Run deployment script
In a separate terminal execute: $ npx hardhat run ./scripts/deploy.js --network localhost

7. Start frontend
$ npm run start
