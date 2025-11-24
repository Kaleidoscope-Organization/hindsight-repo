
# HindSight VIP – Modern Multi‑Chain Blockchain Explorer

HindSight VIP is a high‑performance, multi‑chain blockchain visualization platform designed to simplify on‑chain data analysis. Built with Next.js, TypeScript, and an advanced visualization layer, it delivers clean, intuitive insights across major blockchain ecosystems without exposing internal proprietary logic.

---

## 🚀 Live Demo

[https://hindsight.vip](https://hindsight.vip)

---

## 🔎 Overview

A unified interface for exploring:

* **Ethereum**, **Solana**, **Arbitrum**, **XRPL**
* **Mainnet + Testnet** environments

Users can search addresses/transactions, access real‑time data, and switch between interactive visualization modes designed for clarity and speed.

---

## ✨ Key Features

### **Authentication & Accounts**

Secure user profiles with persistent settings and subscription awareness.

### **Subscriptions (Stripe)**

Tier-based access enabling advanced views and extended data depth.

### **Multi‑Chain Support**

Seamless network switching across supported chains using optimized RPC endpoints.

### **Real‑Time Streamed Data**

Live updates for transactions, transfers, balances, pricing, and confirmations.

### **Powerful Search Engine**

Unified lookup for addresses, hashes, tokens, and NFTs across networks.

### **Visualization Modes**

* **Ecosystem View** – Graph-based entity relationships
* **Shape View** – Flow-based transaction abstractions

### **Wallet Integration**

Web3 wallet connectivity for EVM + Solana to verify ownership and enable user‑centric features.

### **Clean UI/UX**

Fast, responsive interface powered by TailwindCSS and modern design principles.

---

## 🛠️ Tech Stack

* **Next.js (App Router)**
* **React 19**, **TypeScript**
* **Tailwind CSS**
* **ethers.js**, **@solana/web3.js**, **xrpl.js**
* **Stripe**
* **Cloudflare Pages + Wrangler**
* Linting, formatting, CI/CD

---

## ⚙️ Setup

```bash
npm install
npm run dev
```

Create `.env.development` with RPC endpoints and public config.

---

## 📁 Project Structure

```
src/
  app/           # App Router
  components/    # UI
  hooks/         # Client logic
  utils/         # Formatting & helpers
  constants/
  types/
```

---

## 🚢 Deployment

* Automatic deploys via **Cloudflare Pages**
* Preview builds for non-main branches

---

## 🤝 Contributing

* Branching: `feature/*`, `bugfix/*`, `hotfix/*`
* Conventional Commits
* Lint before pushing

---

## 📞 Support

Contact internal HindSight VIP engineering team.

---

**Private & Proprietary – Core logic intentionally omitted.**
