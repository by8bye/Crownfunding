# Crowdfunding Platform

Welcome to the Crowdfunding Platform! This platform allows users to create and manage crowdfunding campaigns for their projects. It provides a user-friendly interface for campaign creation, donation management, and tracking campaign progress.

## Features
User login with different MetaMask wallet
Create, edit, and delete crowdfunding campaigns
Browse and search for campaigns
Make donations to campaigns
User dashboard to manage campaigns and donations

## Technologies Used
* Front-end: HTML, CSS(TailwindCSS), JavaScript, React.js
* Back-end: Node.js, Solidity
* Authentication: JSON Web Tokens (JWT)


## How To Get Sepolia ETH
1. Download MetaMask and create your account 
2. Go to https://www.infura.io/faucet/sepolia?__cf_chl_rt_tk=jF_iVvqTNPNgqEQPTx8HEbbfxA60.6Uts2WIDDskC9s-1702024658-0-gaNycGzNEyU and paste your wallet address in the blank
   <img width="1418" alt="Screenshot 2023-12-09 at 6 53 44 PM" src="https://github.com/by8bye/Crownfunding/assets/126759451/0b8766b5-e805-4f59-aa6f-6a3f2ebbb311">
3. Press receive ETH

## Procedure
1. Download the zip file. It contains our backend Solidity contract and the client for the frontend
2. Open VS Code with a empty folder
3. Open the terminal in VS Code and run the command `npx thirdweb create --app`
4. Name the Project "CrowdFunding", Choose Vite and JavaScript
   <img width="1418"  src="https://github.com/by8bye/Crownfunding/assets/126760063/eadf4e33-6899-4b7c-90fa-157db54ad42b">
5. Run the commands:
   ```
   cd  crowdfunding
   npm install react-router-dom
   npm install -D tailwindcss postcss autoprefixer 
   ```
6. Delete the **src** folder inside the **crowdfunding** folder
7. Paste the **src** folder that downloaded form here into **crowdfunding** folder
8. Paste the **tailwind.config.js** and **postcss.config.js** into **crowdfunding** folder
9. Run the command `npm run dev`
