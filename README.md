<h1 align="center">Hi 👋, I'm Thomas FEVRE</h1>
<p align="center">Blockchain Engineer · Fullstack Developer</p>

<p align="center">
  <a href="https://www.linkedin.com/in/thomas-fevre-6853b51a1/">
    <img src="https://img.icons8.com/color/48/000000/linkedin.png" width="3.5%"/>
  </a>
  &nbsp;
  <a href="mailto:thomas.fevre@outlook.com">
    <img src="https://img.icons8.com/fluent/48/000000/gmail.png" width="3.5%"/>
  </a>
</p>

---

### 👨‍💻 About Me

I'm a blockchain engineer and fullstack developer based in Paris-La Défense. I specialize in smart contract development (Solidity, Rust on Solana), and also build fullstack web3 Dapps using TypeScript, JS  frameworks (Vue/React/Next/Angular), and mobile platforms like Flutter.

---

### 🚀 What I’m Currently Building

- **ChillSplit** – A group expense tracker, fully On-Chain.
  - Focusing on abstracting most of the web3 friction (using Dynamic.xyz wallet with hidden signatures, gas sponsorship, EIP 2612)
  - No direct "wallet" interactions for the user in the app, except for the ON-Ramping (=funding the wallet) process
  - Each group has a smart contract to manage expenses, approvals, and settlement.

*(Currently in a private repo on this github account, do not hesitate to contact me to know more)*

---

### 🧪 Previous Side Projects 

<br /> 

- **No-code LayerZero OFT MCP Server**

  A Node.js MCP server for creating, deploying, and bridging Omnichain Fungible Tokens (OFTs) across multiple chains using LayerZero.  
  Designed for integration with agents and LLMs via the Model Context Protocol (MCP).  
  Features:
  - Deploy and auto-configure OFTs on multiple testnets
  - **Same address** on every chain
  - Bridge tokens between supported chains
  - Built for LLM use via Claude for Desktop or similar tools
    
  🔗 [View Repo](https://github.com/thomasfevre/layerzero_mcp)
    
<br />

- **LayerZero OFT DApp**

  A visual interface built with React/Vite to **deploy & bridge** with LayerZero OFTs (Omnichain Fungible Tokens).
  **Deploy OFTs** across testnets with wallet integration
  Deterministic **same-address** deployment on **every chain** using CREATE2
  Token **bridging** across chains via LayerZero
  Powered by Wagmi, Viem, and TailwindCSS

   🔗 [View Repo](https://github.com/thomasfevre/layerzero_dapp)

<br />

- **Loyalty Pay**
    
  The project is a **Solana-based** loyalty rewards dApp that enables **merchants** to create **on-chain loyalty** programs for their customers.
  - The merchant can enter the amount he wants to receive, generate a **QR-code**, and then the customer scans it and everything is handled in a **single transaction** (paiement, rewards processing, nft mint/upgrade for the client, etc)
      
  🔗 [View Demo](https://loyalty-program-sable.vercel.app/)
  🔗 [View Repo](https://github.com/thomasfevre/loyalty_program)  
    
<br />

- **Token Weighted MultiSig Diamond**
     
  An experimental repo exploring advanced multi-signature mechanisms using the EIP-2535 Diamond Standard.  This repo compares and iterates on multisig strategies across multiple branches, with an emphasis on upgradability and governance logic.  
  - Traditional multisig logic using owner approvals (main branch) 
  - Facet upgrades (`diamondCut`) gated by multisig confirmations (branch n°2) 
  - A novel multisig model based on users’ ERC20 balances as voting weights (branch n°3)  

  🔗 [View Repo](https://github.com/thomasfevre/Token-Weighted-Multisig-Diamond)

<br />
    
- **ERC-20 Token Alternative**
    
  ERC-1919 is a project I started after seeing the idea on Crypto Twitter. The purpose was to replace traditional DEX and LP-based trading.
  It introduces a fully on-chain trading model where:
     - Trades happen exclusively via smart contracts — no DEX, no liquidity pools.
     - Mint on buy / Burn on sell — users send ETH to mint tokens, or send tokens to redeem ETH.
     - Algorithmic pricing via “price levels” — price increases or decreases with each level based on volume.
     - No supply manipulation — levels control token availability and price progression.
     - 1% flat fee on all buy/sell operations, enforced by the contract.
  
  🔗 [View Demo](https://next-web3-boilerplate-git-2project-ac976b-thomasfevres-projects.vercel.app/)
  🔗 [View Repo](https://github.com/thomasfevre/ERC-20-Alternative)  

<br />
    
- **BalanceEat [web2]**
    
  Personnal blog with healthy recipes I created (high protein, low fat, low carb)
    
  🔗 [Visit Website](https://recipe-nodejs-mongodb.onrender.com/)

---

### 🔍 Want to Know More?

👉 Feel free to explore my repos to dive deeper into the code, architecture, and business logic behind the projects.

<p align="center">
  <img src="https://github.com/fnky/fnky/raw/fnky/img/smile.gif" height="70">
</p>
