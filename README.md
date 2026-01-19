<!-- Top Gradient Banner (Vercel-style) -->
<p align="center">
  
</p>

<h1 align="center">MWorks • Web3 Infrastructure Lab</h1>
<p align="center">Building the AI-powered, Evernode-native, XRPL/Xahau commerce ecosystem for 2026 and beyond.</p>

---

<!-- Stats + npm + contributions -->
<p align="center">

  <!-- xMerch npm -->
  <img src="https://img.shields.io/npm/v/xmerch?label=xMerch" />
  <img src="https://img.shields.io/npm/dm/xmerch?label=downloads" />
  <img src="https://img.shields.io/bundlephobia/minzip/xmerch?label=size" />
  <img src="https://img.shields.io/npm/l/xmerch" />

  <!-- GemWallet -->
  <img src="https://img.shields.io/badge/Meister-Contributor%20%2314-blue.svg?style=flat-square" />
  <img src="https://img.shields.io/npm/v/@gemwallet/api?label=GemWallet%20API" />

  <!-- GitHub stats -->
  <img src="https://komarev.com/ghpvc/?username=mworks-proj&label=views" />
</p>

---

# 🧩 Architecture Overview

A high-level system diagram showing your entire ecosystem:

```mermaid
flowchart TD
  User((User)) --> Xaman[(Xaman Wallet)]
  Xaman --> SupabaseAuth[(Supabase Auth + RLS)]
  User --> xMerchCLI[xMerch CLI]
  xMerchCLI --> EvernodeDeploy[Evernode Deployment Engine]

  subgraph "xMerch Ecosystem"
    AdminUI[Admin Dashboard]
    Storefronts[Storefront Templates]
    Payments[XRPL/Xahau Payments]
    Webhooks[Supabase Edge Functions]
  end

  EvernodeDeploy --> Storefronts
  SupabaseAuth --> AdminUI
  SupabaseAuth --> Storefronts
  Payments --> Webhooks
```

> **Fully modular. Fully on-ledger. Fully AI-extendable.**

---

# 🧭 Dynamic Repository Showcase

This section **auto-updates** with your most active repos.

> **Tip:** GitHub automatically updates these cards every few hours.  
> No maintenance required.

<p align="center">

<a href="https://github.com/mworks-proj/xmerch-testing">
  <img
    src="https://github-readme-stats.vercel.app/api/pin/?username=mworks-proj&repo=xmerch-testing&theme=dark&hide_border=true"
    alt="xmerch-testing repo card"
  />
</a>


<a href="https://github.com/mworks-proj/xmerch-cli">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=mworks-proj&repo=xmerch-cli&theme=dark&hide_border=true" />
</a>

<a href="https://github.com/mworks-proj/panda-devs">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=mworks-proj&repo=panda-devs&theme=dark&hide_border=true" />
</a>

<a href="https://github.com/mworks-proj/t3-infra">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=mworks-proj&repo=t3-infra&theme=dark&hide_border=true" />
</a>

</p>

---

# 🚀 Meisters (projects)

**Projects below are under dev** or comming soon.

---

<details>
<summary><h2>🛒 xMerch — Web3 Commerce OS</h2></summary>

### Features
- Deploy a full commerce dApp in seconds  
- Evernode-native deployments  
- XRPL/Xahau payments  
- Xaman wallet authentication  
- Printful integration  
- Multi-vendor dashboard  
- Supabase + Edge Functions for security + automation  

### Architecture
```mermaid
flowchart LR
  CLI[xMerch CLI] --> Deploy(Evernode Deploy)
  Deploy --> AppStorefront(Storefront UI)
  AppStorefront --> Payments(XRPL/Xahau on-ledger)
  Payments --> Supabase(Supabase Webhooks)
  Supabase --> Admin(Admin UI)
```

### Repos
- https://github.com/mworks-proj/xmerch  
- https://demo.xmerch.app  
- https://xmerch.app  
</details>

---

<details>
<summary><h2>🏗 xBase — XRPL / Xahau Starter Template</h2></summary>

### Includes
- Xaman Auth  
- Supabase RLS + Edge  
- Hooks-ready architecture  
- Evernode deployment pipeline  
- Web3 onboarding flow  

### Repo
https://github.com/mworks-proj/xbase  
</details>

---

<details>
<summary><h2>🏡 PANDA — Real-Estate Fractionalization Engine</h2></summary>

### Features
- Fractional slots  
- Xahau yield via Hooks  
- CBA logic  
- Investor dashboards  
- Supabase state mapping  
- On-chain property lifecycle  

### Architecture Diagram
```mermaid
flowchart TD
  User --> Xaman
  Xaman --> PANDAInvest[Deposit / CBA Activation]
  PANDAInvest --> Hooks[Hooks Engine]
  Hooks --> SupabaseDB[Investor State]
  SupabaseDB --> Dashboard
```

Repo: https://github.com/mworks-proj/panda-devs  
</details>

---

<details>
<summary><h2>⚡ T3 Infra — Evernode Hosting Platform</h2></summary>

### Features
- Subscription engine  
- Node provisioning  
- Xaman login  
- NFT-based node ownership  
- Evernode deployment pipeline  

Repo: https://github.com/mworks-proj/t3-infra  
</details>

---

<details>
<summary><h2>🧠 Future — Autonomous Product Engine</h2></summary>

### Purpose
A self-expanding, self-optimizing onchain system that:
- Reads markets  
- Generates new digital products  
- Deploys autonomously  
- Evolves logic based on performance  

### Market TAM Diagram
```mermaid
pie
  title pDEX Market
  "TAM $750B/day" : 750
  "SAM $30B/day" : 30
  "SOM $1.5B/day" : 1.5
```

Repo: (private / in-development)  
</details>

---

<details>
<summary><h2> xFlight — Mech Condor Series</h2></summary>

- Animated SVG character  
- Dynamic loadout system  
- Rarity tiers  
- LocalStorage persistence  
- Upcoming NFT integration  

Repo: https://github.com/mworks-proj/xflight  
</details>

---

# 🎨 

<p align="center">
 
</p>

---

# 🧩 Tech Stack

```txt
Next.js 15 • TypeScript • Supabase • Xaman Wallet • XRPL / Xahau • Evernode
LLM Agents • Vercel AI SDK • Tailwind • Docker • Redis
```

---

# 👋 Connect

- **X:** https://x.com/xrpl_mworks  
- **GitHub:** https://github.com/mworks-proj  
- **Website:** https://www.mworks.design  

