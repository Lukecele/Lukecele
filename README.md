# Luca Celebrano

**MD Candidate** · Università degli Studi di Napoli Federico II  
**Web3 & Computational Systems Engineer**

---

### About Me

I am a medical student at **Università degli Studi di Napoli Federico II** with a focus on computational systems, software architecture, and on-chain data engineering.

Alongside my academic training, I design and build live Web3 applications, deterministic financial logic, and real-time on-chain data systems.

My focus centers on tested financial and telemetry logic, reproducible data pipelines, and clean, documented open-source integrations.

---

### Core Competencies

- **Computational & Deterministic Modeling:** Algorithm design, deterministic state machines, statistical verification, and custom rule-based intent pipelines.
- **Full-Stack & Systems Architecture:** TypeScript, Python, Node.js, Next.js / React, Express, REST & WebSocket streams, RPC log parsing.
- **DevOps & Cloud Infrastructure:** Docker containerization, Linux CLI automation, Google Cloud Run, Vercel Edge, Hugging Face Spaces, Git CI/CD.
- **Web3 & DeFi Engineering:** EVM smart contract interaction (Viem, Wagmi, Ethers), multi-protocol yield aggregation, lending markets (Venus Protocol / vTokens), liquid staking integration (Lista DAO, pSTAKE, Stader), DEX aggregator routing (KyberSwap, Mayan Finance), and DeFiLlama dimension adapters.
- **Data Engineering & Telemetry:** Event decoding, real-time metrics aggregation, ECharts / Highcharts data visualization, on-chain contract telemetry.

---

### Flagship Production Systems

<table>
  <thead>
    <tr>
      <th>System</th>
      <th>Architecture & Description</th>
      <th>Status & Links</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><b>Arb-Inc-All-in-Dex</b></td>
      <td>
        Multi-chain DEX aggregator and cross-chain bridge integration (Mayan Finance / Solana / EVM). Features deterministic pro-rata yield calculation engines (<code>lib/financial-math.ts</code> with automated unit testing suites), non-custodial limit order routing, and PWA mobile optimization.
      </td>
      <td>
        <a href="https://github.com/Lukecele/Arb-Inc-All-in-Dex">GitHub</a> · 
        <a href="https://arbitrage-inc.exchange">Live Application</a> · 
        <i>DeFiLlama-listed protocol metrics & merged fee adapter</i>
      </td>
    </tr>
    <tr>
      <td><b>Arbitrage Inception — Earn & Vaults</b></td>
      <td>
        Multi-protocol yield aggregator and vault manager on BNB Smart Chain. Integrates KyberSwap Aggregation API for automated token routing into Liquid Staking (Lista DAO, pSTAKE, Stader) and Lending Markets (Venus Protocol) with single-transaction execution.
      </td>
      <td>
        <a href="https://github.com/Lukecele/arbitrage-inc-earn">GitHub</a> · 
        <a href="https://arbitrage-inc-earn.vercel.app">Live Application</a> · 
        <i>Next.js & Vercel</i>
      </td>
    </tr>
    <tr>
      <td><b>Inception Flap Scanner</b></td>
      <td>
        Real-time on-chain token launch screener and bonding curve telemetry tracker on BNB Smart Chain. Features RPC log decoding, live Flap.sh curve metrics, interactive DexScreener charts, and an automated 4-tier security auditor (tax safeguards ≤8%, ERC-1167 proxy verification, social phishing/copycat detection, dev wallet clustering). Fully containerized with Node 22 on Hugging Face Spaces.
      </td>
      <td>
        <a href="https://github.com/Lukecele/inception-flap-scanner">GitHub</a> · 
        <a href="https://lucace-inception-flap-scanner.hf.space">Live Application</a> · 
        <i>Docker SDK</i>
      </td>
    </tr>
    <tr>
      <td><b>Birdeye DEX Tracker &amp; Bot</b></td>
      <td>
        Real-time liquidity pool swap monitor and production Telegram alert bot (<a href="https://t.me/ArbincMoon_bot">@ArbincMoon_bot</a>). Connects directly to DEX APIs and RPC nodes, streaming live buy/sell events and USD volumes (&gt;9,500 transactions logged) directly into the dedicated <a href="https://t.me/arbitrageinception/80770"><i>All Buys and Sells</i> topic</a> of the DEX community, backed by a live Google Cloud Run administrative dashboard.
      </td>
      <td>
        <a href="https://github.com/Lukecele/birdeye-dex-tracker">GitHub</a> · 
        <a href="https://t.me/arbitrageinception/80770">Live Topic (80770)</a> · 
        <a href="https://t.me/ArbincMoon_bot">@ArbincMoon_bot</a> · 
        <a href="https://birdeye-telegram-bot-697887897331.europe-west2.run.app">Dashboard</a> · 
        <i>Google Cloud Run</i>
      </td>
    </tr>
    <tr>
      <td><b>Virtue</b></td>
      <td>
        Rule-based conversational engine and real-time financial calculator (2,200+ LOC deterministic logic). Analyzes conversational context and tokenomic calculations with deterministic accuracy without relying on third-party APIs.
      </td>
      <td>
        <a href="https://github.com/Lukecele/virtue">GitHub</a> · 
        <a href="https://virtue-ecru.vercel.app">Live Application</a> · 
        <i>Next.js & Vercel Edge</i>
      </td>
    </tr>
  </tbody>
</table>

---

### Research Baselines, Tooling & Open-Source Prototypes

<table>
  <thead>
    <tr>
      <th>Project</th>
      <th>Architecture & Purpose</th>
      <th>Status & Disclosures</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><b>Solana Meme Intelligence (v8)</b></td>
      <td>
        Institutional quantitative research baseline for Solana DEX and meme coin tokenomics. Features deterministic multi-factor scoring (liquidity depth, volume acceleration, dev wallet clustering, bonding curve progression), robust async RPC/Birdeye ingestion pipeline, and statistical backtesting framework.
      </td>
      <td>
        <a href="https://github.com/Lukecele/meme-intelligence-onchain">GitHub</a> · 
        <i>Open-source research framework. Synthetic data stripped; requires user-supplied Helius/Birdeye API keys for live ingestion.</i>
      </td>
    </tr>
    <tr>
      <td><b>BSC Arbitrage Scanner</b></td>
      <td>
        Real-time asynchronous arbitrage scanner and cross-DEX route simulation engine on BNB Smart Chain. Consumes live token lists and queries KyberSwap Aggregator v1 APIs to identify instantaneous price discrepancies and compute optimal swap routes.
      </td>
      <td>
        <a href="https://github.com/Lukecele/bsc-arbitrage-scanner">GitHub</a> · 
        <i>Read-only simulation tool with live API telemetry. Automated on-chain execution disabled.</i>
      </td>
    </tr>
    <tr>
      <td><b>ARBVPN Client</b></td>
      <td>
        Cross-platform 1-tap WireGuard VPN mobile application built with React Native and TypeScript. Features cryptographic handshake state management, live latency metrics, and decoupled configuration architecture preventing hardcoded key leaks.
      </td>
      <td>
        <a href="https://github.com/Lukecele/ARBVPN">GitHub</a> · 
        <i>Decoupled client architecture. Requires user to provide WireGuard server endpoint and keys (template provided).</i>
      </td>
    </tr>
    <tr>
      <td><b>LUNC Devourer</b></td>
      <td>
        Interactive Web3 dApp showcase and mathematical burn fee simulator built on Terra Classic / Next.js. Implements Terra Station wallet integration, live tokenomics math, and on-chain burn modeling.
      </td>
      <td>
        <a href="https://github.com/Lukecele/lunc-devourer">GitHub</a> · 
        <i>Historical showcase & fee simulator. Underlying token launchpad (LaunchPump) ceased operations; swap execution disabled.</i>
      </td>
    </tr>
  </tbody>
</table>

---

### Open Source Contributions

- **[DefiLlama / dimension-adapters](https://github.com/DefiLlama/dimension-adapters):** Merged protocol fee adapter and on-chain telemetry integration ([PR #6275](https://github.com/DefiLlama/dimension-adapters/pull/6275)).

---

### Academic & Professional Contact

- **Institution:** Università degli Studi di Napoli Federico II
- **Email:** [luca.celebrano1@gmail.com](mailto:luca.celebrano1@gmail.com)
- **GitHub:** [https://github.com/Lukecele](https://github.com/Lukecele)
- **Location:** Naples, Italy

---

### Open-Source Architecture & Non-Custodial Notice

All software repositories, architectural diagrams, and algorithms showcased on this profile represent free, open-source contributions and research implementations published under permissive licenses (MIT). The author acts as an independent software engineer and computational researcher. No repository or interface constitutes investment advice, financial intermediation, or custodial brokerage services. Public decentralized protocols referenced operate autonomously on-chain with immutable, renounced ownership parameters.
