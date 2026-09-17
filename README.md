# Luca Celebrano

**MD Candidate** · Università degli Studi di Napoli Federico II  
**Founder & Lead Architect @ [Arbitrage Inception](https://github.com/arbincept) · Web3 Systems & DeFi Protocol Designer**

---

### About Me

I am a medical student at **Università degli Studi di Napoli Federico II** with a deep focus on computational systems, quantitative logic, and decentralized finance.

Since 2021, I have worked across the on-chain DeFi ecosystem, analyzing automated market makers, cross-chain bridge dynamics, and tokenomics structures. I work as an **AI-augmented systems architect**, combining domain expertise, quantitative modeling, and practical systems judgment to design and coordinate modern engineering pipelines.

Through this architecture-first methodology, I design, maintain, and ship deployed Web3 platforms, real-time on-chain telemetry screeners, and deterministic financial infrastructure. Selected systems have public releases, CI validation, live deployments, and public protocol analytics.

> 🛠️ **The "Pain-Stack" Genesis:**  
> *Beyond standard paradigms, my journey was forged in the early AI trenches — mastering terminal discipline, testing LLM-assisted workflows with tactical CLI inspection, and building actively maintained DeFi systems through quantitative rigor and continuous shipping.*

---

### Core Competencies

- **DeFi Protocol Design & Multi-Chain Architecture:** EVM (BNB Smart Chain, Ethereum), Solana, and cross-chain ecosystems. Architectural design of non-custodial DEX aggregation (integrating KyberSwap API & Mayan Finance Swift cross-chain bridge), composable yield vaults (interfacing with Venus Protocol, Lista DAO, pSTAKE, Stader), accumulator tax tokenomics, and public DeFiLlama dimension adapters.
- **End-to-End System Design & AI-Augmented Software Delivery:** Full product lifecycle orchestration across modern web frontends (Next.js 16 / React 19), cross-platform mobile clients (React Native & Expo with WireGuard VPN integration), asynchronous backend daemons (Python AsyncIO, Node.js, Express), and WebSocket / REST event streaming.
- **Quantitative & Deterministic Modeling:** Algorithm design, multi-factor scoring pipelines (liquidity depth, volume acceleration, dev wallet clustering, bonding curve progression), statistical backtesting engines, and custom deterministic state machines.
- **Data Engineering, Telemetry & On-Chain Security:** High-throughput RPC log decoding, on-chain mempool screener pipelines, triangular arbitrage path simulations, automated security screening (proxy verification, anti-honeypot filters, dust spam mitigation), and interactive telemetry visualizers.
- **Cloud Infrastructure, Containerization & CI/CD:** Docker containerization, Google Cloud Run, Vercel Edge, Hugging Face Spaces, Linux CLI automation, and GitHub Actions automated testing pipelines.

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
        <a href="https://github.com/arbincept/Arb-Inc-All-in-Dex">GitHub</a> · 
        <a href="https://github.com/arbincept/Arb-Inc-All-in-Dex/releases/tag/v1.1.0">v1.1.0 Release</a> · 
        <a href="https://arbitrage-inc.exchange">Live Application</a> · 
        <a href="https://defillama.com/protocol/arbitrage-inc">DefiLlama</a> · 
        <a href="https://github.com/ahmet/awesome-web3/blob/main/README.md#L407">Awesome-Web3 (Line 407)</a>
      </td>
    </tr>
    <tr>
      <td><b>Arbitrage Inception — Earn & Vaults</b></td>
      <td>
        Multi-protocol yield aggregator and vault manager on BNB Smart Chain. Integrates KyberSwap Aggregation API for automated token routing into Liquid Staking (Lista DAO, pSTAKE, Stader) and Lending Markets (Venus Protocol) with single-transaction execution.
      </td>
      <td>
        <a href="https://github.com/arbincept/arbitrage-inc-earn">GitHub</a> · 
        <a href="https://arbitrage-inc-earn.vercel.app">Live Application</a> · 
        <i>Next.js & Vercel</i>
      </td>
    </tr>
    <tr>
      <td><b>Inception Flap Scanner</b></td>
      <td>
        Real-time on-chain token launch screener and bonding curve telemetry tracker on BNB Smart Chain. Features RPC log decoding, live Flap.sh curve metrics, interactive DexScreener charts, and an automated four-stage security screening pipeline (bot-driven dust spam &amp; tax filter &le;8%, ERC-1167 minimal proxy verification detecting custom architectural innovations vs standard clones, social phishing/copycat detection, and dev wallet clustering). Fully containerized with Node 22 on Hugging Face Spaces.
      </td>
      <td>
        <a href="https://github.com/arbincept/inception-flap-scanner">GitHub</a> · 
        <a href="https://github.com/arbincept/inception-flap-scanner/releases/tag/v1.1.0">v1.1.0 Release</a> · 
        <a href="https://lucace-inception-flap-scanner.hf.space">Live Application</a> · 
        <a href="https://github.com/ahmet/awesome-web3/blob/main/README.md#L343">Awesome-Web3 (Line 343)</a> · 
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
      <th>System</th>
      <th>Architecture & Description</th>
      <th>Status & Links</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><b>Meme Intelligence On-Chain</b></td>
      <td>
        Quantitative research baseline for Solana DEX and meme coin tokenomics (v8). Features statistical backtesting engines, holder distribution heuristics, liquidity pool decay modeling, and risk scoring pipelines.
      </td>
      <td>
        <a href="https://github.com/Lukecele/meme-intelligence-onchain">GitHub</a> · 
        <i>Quantitative research framework & Python backtesting engine.</i>
      </td>
    </tr>
    <tr>
      <td><b>BSC Arbitrage Scanner</b></td>
      <td>
        Real-time asynchronous arbitrage scanner and cross-DEX route simulation engine on BNB Smart Chain. Consumes live token lists and queries KyberSwap Aggregator v1 APIs to identify instantaneous price discrepancies and compute optimal swap routes.
      </td>
      <td>
        <a href="https://github.com/arbincept/bsc-arbitrage-scanner">GitHub</a> · 
        <a href="https://github.com/arbincept/bsc-arbitrage-scanner/releases/tag/v1.1.0">v1.1.0 Release</a> · 
        <i>Released simulation engine with GoPlus security & dynamic gas modeling.</i>
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

### Open Source Adoption & Verified Ecosystem Indexing

- **Public Repository Activity:** GitHub Traffic Analytics currently reports, in the latest available weekly windows, **438 clones / 192 unique cloners** for *Arb-Inc-All-in-Dex*, **126 / 61** for *bsc-arbitrage-scanner*, and **297 / 125** for *inception-flap-scanner* (repository-level figures; windows and unique counts should not be summed across repositories).
- **Niche Search Visibility:** These projects were observed in top results for selected GitHub searches such as “BSC DEX aggregator” on **17 September 2026**. GitHub rankings vary by query, indexing, and time, so this is not presented as a global or permanent rank.
- **[DefiLlama / dimension-adapters](https://github.com/DefiLlama/dimension-adapters):** Upstream production fee adapters and real yield metrics merged by DefiLlama maintainers ([PR #9453](https://github.com/DefiLlama/dimension-adapters/pull/9453), [PR #6279](https://github.com/DefiLlama/dimension-adapters/pull/6279), [PR #6275](https://github.com/DefiLlama/dimension-adapters/pull/6275)) — live analytics on [DefiLlama Protocol Analytics (ID 7591)](https://defillama.com/protocol/arbitrage-inc).
- **[Awesome-Web3 Directory](https://github.com/ahmet/awesome-web3):** Curated directory inclusion for *Arb-Inc All-in-Dex* ([Open Source Project, Line 407](https://github.com/ahmet/awesome-web3/blob/main/README.md#L407), [PR #796](https://github.com/ahmet/awesome-web3/pull/796)) and *Inception Flap Scanner* ([Risk Management, Line 343](https://github.com/ahmet/awesome-web3/blob/main/README.md#L343), [PR #795](https://github.com/ahmet/awesome-web3/pull/795)).

#### Ecosystem Submissions (Pending Maintainer Review)
- **[BNB Chain Developer Tooling](https://github.com/bnb-chain/developer-tools-list/pull/98):** Open ecosystem developer-tools submission; HashDit reported no serious issues in an automated scan. The PR remains open and the scan is not a manual audit.
- **[BNB Chain Awesome Catalog](https://github.com/bnb-chain/awesome/pull/16):** Open curated BNB Smart Chain ecosystem-tools submission; HashDit reported no serious issues in an automated scan. The PR remains open and the scan is not a manual audit.

---

### Academic & Professional Contact

- **Institution:** Università degli Studi di Napoli Federico II
- **Email:** [luca.celebrano1@gmail.com](mailto:luca.celebrano1@gmail.com)
- **GitHub:** [https://github.com/Lukecele](https://github.com/Lukecele)
- **Location:** Naples, Italy

---

### ⭐ Open-Source Support

If you find any of these repositories, architecture models, or on-chain telemetry engines helpful in your work or research, please consider leaving a **Star** on the respective projects. Your feedback and support help drive continuous open-source development and ecosystem maintenance!

---

### Open-Source Architecture & Non-Custodial Notice

All software repositories, architectural diagrams, and algorithms showcased on this profile represent open-source contributions and research implementations published under the license stated by each repository. The author acts as an independent systems architect, product designer, and computational researcher. No repository or interface constitutes investment advice, financial intermediation, or custodial brokerage services. Protocol properties and ownership controls should be verified in the relevant source code and deployment documentation.
