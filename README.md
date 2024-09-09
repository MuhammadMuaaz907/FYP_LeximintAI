<h1>AI NFT Generator<h1/></h1><br>
<h4>Technology Stack & Tools</h4>
Solidity (Writing Smart Contracts & Tests)
 Javascript (React & Testing)<br>
  <a href="https://hardhat.org/">Hardhat</a>(Development Framework)<br>
 Ethers.js (Blockchain Interaction)<br>
 React.js (Frontend Framework)<br>
 NFT.Storage (Connection to IPFS)<br>
   <a href="https://hardhat.org/">Hugging Face</a>(Development Framework)<br>(AI Models) <br>
 Requirements For Initial Setup<br>
 Install NodeJS<br>
 Setting Up<br>
 1. Clone/Download the Repository<br>
 2. Install Dependencies:<br>
   $ npm install<br>
 3. Setup .env file:<br>
   Before running any scripts, you'll want to create a .env file with the following values (see .env.example):<br>

REACT_APP_HUGGING_FACE_API_KEY=""<br>
REACT_APP_NFT_STORAGE_API_KEY=""<br>
You'll need to create an account on Hugging Face, visit your profile settings, and create a read access token.<br>

You'll also need to create an account on NFT.Storage, and create a new API key.<br>

4. Run tests<br>
$ npx hardhat test<br>

5. Start Hardhat node<br>
$ npx hardhat node<br>

6. Run deployment script<br>
In a separate terminal execute: $ npx hardhat run ./scripts/deploy.js --network localhost<br>

7. Start frontend<br>
$ npm run start
