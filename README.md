# Airdrop automstion

## Stack

- Solidity for writing smart contracts
- Javascript (React & Testing)
- [Ethers.js](https://docs.ethers.io/v5/) (Blockchain Interaction)
- [Alchemy](https://www.alchemy.com/) (Blockchain Connection)
- [Netlify](https://www.netlify.com/) (Cloud Service)

## Initial Setup
- [NodeJS](https://nodejs.org/en/) - latest LTS version. Install NodeJS via [NVM](https://github.com/nvm-sh/nvm#intro).
- [Alchemy](https://www.alchemy.com/) - API key for Goerli RPC test network
- [Netlify](https://www.netlify.com/) 

## Setup

### GitHub 

`git remote set-url origin <GIT_URL>`

`git push origin master`

### Netlify
**Team overview** -> **Sites** -> **Import from Git**

Connect to your GitHub -> **Deploy site**

### Env Variables
**Site settings** -> **Environment variables**

- **RPC_URL=""** - Alchemy RPC

- **PRIVATE_KEY_1=""**
- **PRIVATE_KEY_2=""**
- **PRIVATE_KEY_3=""**
- **TRANSFER_AMOUNT=""** (USDC, 6 digits)

- **TOKEN_ADDRESS="USDC on Goerli"** 
- **WETH_ADDRESS="WETH on Goerli"** 

- **V2_ROUTER_ADDRESS="Uniswap V2 Router on Goerli"** 
- **SWAP_AMOUNT="ETH 18 digits"** 
### Deployment
**Deploys** tab -> **Trigger deploy** ->  **Clear cache and deploy site** to redeploy the site.