# BC-NFT1

Created an ERC721 NFT named ''NFTee' with Hardhat and deployed to Quick Node.

How to execute the code:

1. After creating the code, compile the code using below command
   npx hardhat compile

2. Install devenv package and create .env file with Quicknode HTTP provider URL and Metamask account private key

3. Run below command to run the contract on Quicknode provided ethereum nodes
   npx hardhat run .\scripts\deploy.js --network sepolia
