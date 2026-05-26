<div align="center">

# DevSwap Protocol

### A Security-Hardened Protocol for on-chain software-services settlement

[**devswap.pro**](https://devswap.pro) · BNB Smart Chain · settled in USDT · bilingual (EN / AR, RTL)

</div>

---

DevSwap Protocol is a decentralized peer-to-peer protocol for software-services settlement. A
client locks the budget **on-chain in USDT**; the **smart contract** releases it to the developer
only on the client's explicit approval, or via deterministic on-chain dispute and timeout rules.
Non-custodial by design — no platform escrow, no middleman holding funds.

### How it works
1. **Lock** — the client funds a task; USDT is locked in the smart contract.
2. **Deliver** — the developer accepts and submits the work.
3. **Release** — the client approves → the contract releases funds atomically; or opens a transparent on-chain dispute.

### Economics — contract-enforced, not policy
- **97%** to the developer · **1.5%** protocol operations · **1.5%** community **buyback-and-burn** of the protocol utility token.
- Total fee **3%** — the 97% developer floor and 3% total ceiling are **immutable** in contract bytecode.

### Security Status
DevSwap Protocol's path to mainnet is gated by **independent verification, not by a token sale**.
The seven Security Gates documented in [`devswap-docs/SECURITY-AUDIT.md`](https://github.com/DevSwap-org/devswap-docs/blob/main/SECURITY-AUDIT.md) — four automated (Mythril
symbolic execution, Slither pattern analysis, 100% test coverage, 79+ tests including mainnet-fork)
and three manual (independent third-party audit, multisig 3-of-5 + timelock, qualified-counsel
review) — separate the testnet protocol from a live mainnet launch.

Two live protocol controls protect users today:
- **Geo-restriction (RFC 7725 / HTTP 451)** — US persons and OFAC-sanctioned jurisdictions are blocked from funding routes and any token-related disclosure pages.
- **Server-rendered disclosure interstitial** — every external link referencing the protocol utility token routes through a strict-host-allowlist disclosure page in both supported locales.

### Tech
Solidity 0.8.24 (Foundry) · OpenZeppelin v5 (vendored) · Next.js on **Cloudflare Workers** (OpenNext) · wagmi / viem · The Graph · IPFS.

### Repositories
- [**devswap-contracts**](https://github.com/DevSwap-org/devswap-contracts) — smart contracts (public, source-verified for audit).
- [**devswap-docs**](https://github.com/DevSwap-org/devswap-docs) — public documentation (README, SECURITY-AUDIT, GOVERNANCE).
- [**DevSwap**](https://github.com/DevSwap-org/DevSwap) — the dApp source (private).

### Reporting security issues
Email **security@devswap.pro** — see [SECURITY.md](https://github.com/DevSwap-org/.github/blob/main/SECURITY.md) for the responsible-disclosure policy.

> **Status:** Security-Hardened Protocol live on **BNB Smart Chain testnet**. The protocol utility
> token is a utility token only — no price, yield, dividend, revenue share, or return is promised.
> No active token sale. Nothing here is financial or legal advice.

<div align="center">

**[devswap.pro](https://devswap.pro)** · بروتوكول لامركزي عالي الأمان لتسوية الخدمات البرمجية على السلسلة

</div>
