# 🧠 ENA Universe TCG – Game Engine & Hybrid Token System (PoC Phase)

## 🎮 Project Scope

We are building the **Proof of Concept (PoC)** for the ENA Universe TCG, a hybrid **AI-designed trading card game** where players can:

- Collect and play with NFT cards  
- Battle 1v1 (PvP and PvE vs AI)  
- Stake NFTs to earn $ENA  
- **Bet $ENA tokens** on matches  
- Use a **hybrid off-chain/on-chain token system** to simplify onboarding and enable scalable gameplay  

The PoC will simulate battles, track balances, and prepare for blockchain integration.

---

## 💰 Token System: Hybrid ENA Balance

We will implement a **dual-layer $ENA system**:

| Layer        | Purpose                                   | Technology                            |
|--------------|-------------------------------------------|----------------------------------------|
| **Off-chain** | In-game balance (earn, stake, bet, spend) | Internal DB                            |
| **On-chain** | Real token in user wallets                | $ENA ERC-20 Smart Contract (deployed) |

### Why Hybrid?

- **Off-chain** ensures fast, gas-free, and smooth game experience.  
- **On-chain** ensures value, trust, liquidity, and real ownership.

Users will be able to:
- Play and bet using their internal ENA balance  
- Claim on-chain ENA after reaching certain thresholds  
- Deposit ENA from their wallet to increase in-game balance  

---

## 🔄 Core Gameplay Features (PoC Version)

- Turn-based 1v1 game system with **simplified rules**, inspired by Magic: The Gathering  
- Visual representation of **real NFT cards**  
- Internal betting system where users wager ENA before matches (against AI or other players)  
- Multiple AI difficulty levels with higher risk/reward multipliers  
- Backend system to **store internal ENA balances, battle results, and NFTs linked to accounts**

---

## 🔐 Smart Contract Integration

We will use the existing $ENA contract and build the following:

- **Game Vault Contract**: Receives ENA deposits for betting  
- **Withdraw Function**: Sends ENA to user wallet  
- **Frontend**: React/Web3 interface to connect wallet, view ENA, and interact with the staking/betting logic

---

## 🧱 Development Phases

1. **Phase 1 – Game Logic & Visual Prototype**
   - Core battle engine (PvE vs AI)  
   - Basic card visuals + actions  
   - Off-chain ENA balances & betting  
   - Admin control panel  

2. **Phase 2 – Blockchain Integration**
   - Wallet connection (MetaMask)  
   - Deposit/Withdraw ENA  
   - ENA vault smart contract  
   - Record wins/losses on-chain  

3. **Phase 3 – PvP, Leaderboards & Tournaments**
   - Player vs Player battles  
   - Leaderboard rewards  
   - Weekly/monthly ENA tournaments  
