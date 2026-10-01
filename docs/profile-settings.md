# Profile repository settings

Prepared on October 1, 2026 for `Lukecele/Lukecele`. These settings are separate from the profile README.

## Repository discovery

**Status: prepared, not applied.** This Coding task does not have repository administration access; its runtime also blocks GitHub API writes. Remote branch and pull request delivery is managed by the platform.

| Setting | Current value | Prepared value |
| :--- | :--- | :--- |
| About description | Personal profile and technical systems overview for Luca Celebrano | Luca Celebrano (@Lukecele): medical student, bioinformatics research and open-source software. Founder of Arbitrage Inception. |
| Homepage | Not set | https://github.com/Lukecele |
| Topics | `bsc`, `defi`, `developer-portfolio`, `dex-aggregator`, `ethereum`, `nextjs`, `on-chain-analytics`, `portfolio`, `python`, `quantitative-finance`, `react`, `solidity`, `typescript`, `web3` | `developer-portfolio`, `portfolio`, `open-source`, `bioinformatics`, `typescript`, `python`, `web3` |
| Social preview | Existing upload not inspected; administrator settings unavailable | [social-preview.png](../assets/social-preview.png), with editable [SVG source](../assets/social-preview.svg) |

The seven proposed topics describe Luca's portfolio and documented project languages. GitHub allows up to 20 topics, each at most 50 characters, using lowercase letters, numbers and hyphens. See [GitHub's topic rules](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/classifying-your-repository-with-topics).

### Manual steps for the repository owner

1. Open [Lukecele/Lukecele](https://github.com/Lukecele/Lukecele), then the gear beside **About**.
2. Copy the prepared description and homepage above. Replace the current topics with the seven prepared topics and save.
3. Open repository **Settings → General → Social preview → Edit → Upload an image** and upload `assets/social-preview.png` (1280 × 640, under 1 MB).
4. Confirm the saved settings and preview. The card controls shares of this repository; it does not guarantee the preview of the user profile URL. See [GitHub's social preview instructions](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/customizing-your-repositorys-social-media-preview).

The card adapts the existing `assets/profile-banner.svg` palette and node artwork. It uses an opaque background for consistent contrast in light and dark surroundings. To regenerate it, render the SVG at its native 1280 × 640 dimensions and export to PNG; verify dimensions and size before upload.

## Personal account: bio and pins

**Recommendation: retain the current bio and all six pins. No account changes applied.**

Current bio, verified from the public GitHub user API:

> MD Candidate @ Federico II · Bioinformatics & on-chain systems · Founder @arbincept · Open-source contributor

This already connects the medical, research and founder identities. The README preserves the existing Federico II and TIGEM statements; it does not add institutional claims.

Pins verified from the public profile on October 1, 2026:

1. [Arb-Inc All-in-Dex](https://github.com/arbincept/Arb-Inc-All-in-Dex)
2. [Earn & Vaults](https://github.com/arbincept/arbitrage-inc-earn)
3. [Inception Flap Scanner](https://github.com/arbincept/inception-flap-scanner)
4. [Virtue](https://github.com/Lukecele/virtue)
5. [Telegram Buy & Sell Tracker](https://github.com/Lukecele/Telegram-bsc-buy-sell-bot)
6. [BSC Arbitrage Scanner](https://github.com/arbincept/bsc-arbitrage-scanner)

All six repositories are public and not archived. They cover exchange, yield, telemetry, conversational tooling and automation. Their current state supports keeping this selection.

## Editorial evidence

- Project descriptions were compared with current public repository documentation. Virtue's [`app/api/absolution/route.ts`](https://github.com/Lukecele/virtue/blob/main/app/api/absolution/route.ts) also confirms external Binance, CoinGecko, web and Twitter/X requests; the README no longer implies complete API independence.
- The [RWA documentation](https://github.com/arbincept/rwa-stock-arbitrage#cli-and-agent-tooling) identifies the MCP adapter as experimental and lacking the initialization handshake. Its profile description now qualifies compatibility.
- GitHub pull request API responses confirmed that every PR in the technical contributions table was authored by Lukecele and merged. Awesome-Web3 submissions were also merged; the two BNB Chain submissions remained open. Statuses in the README are dated so they are not presented as live tracking.
- This repository has no application manifests, quick start, build scripts or documentation test suite. Linked applications were not built or transaction-tested as part of this presentation change.
