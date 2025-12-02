# Brild - No-Code AI-Augmented DeFi Automation Platform on Celo

Welcome to **brild**, the revolutionary **no-code, drag-and-drop platform** built 100% natively on **Celo** that lets anyone — no coding required — create, deploy, and monetize powerful **AI-augmented DeFi strategies** in minutes.

Powered by Celo’s mobile-first, ultra-low-fee, carbon-negative blockchain and integrated decentralized AI, brild transforms complex DeFi automation (yield farming, arbitrage, DCA, auto-compounding, risk vaults, and more) into simple, visual workflows that live and execute fully onchain.

Deployed core contracts on Celo:  
- **brildToken**: `0x03A1a836FAEc7Dc83D39AaC91283fe42230b1835`  
- **brildCore Proxy**: `0x55a4a8A46F2B204e74F5D5861a6eAD8ccf89b08`  

Every strategy you build with brild is a verifiable onchain asset, executes in sub-seconds, costs pennies in cUSD, and can be shared, sold, or rented instantly.

---

## What brild Does

brild is the fastest way to build **production-grade, AI-augmented DeFi automation** — without writing a single line of code.

Drag → Drop → Deploy → Earn

Visually assemble strategies from audited building blocks, supercharged in real time by onchain AI that predicts yields, optimizes parameters, and manages risk — all on Celo’s mobile-first chain.

---

## The Problem it Solves

DeFi is still inaccessible, expensive, and risky for 99% of people:  
- You need to code bots or trust closed-source services  
- Gas on Ethereum/L2s destroys small strategies  
- Most automation tools are fragile or centralized  

**brild + Celo fixes everything**:  
- Truly no-code, works from your phone  
- Sub-cent fees and instant finality  
- Fully transparent, auditable, onchain execution  
- Decentralized AI anyone can use and improve  

---

## Features

- **Drag-and-Drop Workflow Builder** – Build sophisticated strategies in minutes  
- **AI-Powered Optimization** – Real-time yield forecasting, risk scoring, auto-tuning  
- **One-Click Onchain Deployment** – Strategies become upgradable onchain agents  
- **Built-In Monetization** – Sell or rent your strategies in cUSD via the brild Marketplace  
- **Mobile-First Experience** – Perfect on Valora, MiniPay, and every Celo wallet  
- **Live Performance Dashboards** – Track PnL, APY, and alerts in real time  
- **Community Strategy Templates** – Start from proven bots (DCA, Auto-Compound, Arbitrage, etc.)

---

## Technologies Used

- **Next.js 14** (App Router) – Blazing-fast frontend  
- **TypeScript** – End-to-end type safety  
- **Tailwind CSS + shadcn/ui** – Beautiful, responsive drag-and-drop UI  
- **Celo Blockchain** – Mainnet & Alfajores  
- **Wagmi + Viem + Celo ContractKit** – Seamless wallet & contract interaction  
- **The Graph** – Fast indexing of strategy events  
- **IPFS + NFT.Storage** – Decentralized workflow metadata & visuals  
- **Decentralized AI** – Onchain inference (Giza, Modulus, etc. integration roadmap)

---

## How to Set Up

```bash
git clone https://github.com/ernnies/brild.git
cd brild
pnpm install
cp .env.example .env.local
```

Add your Celo RPCs (Alfajores + Mainnet) → `pnpm dev`

Visit [http://localhost:3000](http://localhost:3000) and start building instantly.

Deploy contracts:
```bash
pnpm deploy:alfajores
pnpm deploy:mainnet
```

---

## brild Roadmap

**Wave 1** → Completed  
Core builder, essential DeFi blocks, Celo integration, first AI risk engine.

**Wave 2** → In Progress  
Flash loans, advanced yield blocks, AI optimizer v1, marketplace MVP.

**Wave 3** → Planned  
Auto-rebalancing, liquidation protection, cross-protocol arbitrage, full mobile editor.

**Wave 4** → Planned  
Strategy NFTs with royalties, recurring subscription vaults, creator revenue share.

**Wave 5** → Vision  
brild becomes the **Figma of DeFi** — the world’s #1 no-code platform for intelligent, monetizable DeFi automation, used by millions on Celo.

---

## What’s Next for brild

- Launch the brild Strategy Marketplace (earn cUSD from your bots)  
- Native mobile app (React Native + Expo)  
- Partnerships with Valora, MiniPay, and top Celo protocols  
- Creator fund for the best community strategies  
- Dominate no-code DeFi automation globally

---

## Contributing

Ship fast, ship together. PRs very welcome — especially new blocks, AI models, and UI polish.

```bash
git checkout -b feat/auto-liquidation-bot
```

---

## License

MIT License – build anything, ship anywhere, keep 100% of what you earn.

---

**brild → No-code. AI-augmented. Built on Celo.  
Turn DeFi strategies that once took teams of developers into drag-and-drop brilliance — in minutes, from your phone.**

Let’s make intelligent DeFi accessible to everyone.  
Welcome to brild.