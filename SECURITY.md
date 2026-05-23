# Security Policy

DevSwap manages on‑chain value, so we take security seriously and welcome responsible disclosure.

## Reporting a vulnerability
- **Do NOT** open a public issue for security vulnerabilities.
- Email **security@devswap.pro** with details and reproduction steps.
- Please allow reasonable time for a fix before any public disclosure.

We aim to acknowledge reports within 72 hours.

## Scope
- Smart contracts (`devswap-contracts`): escrow lifecycle, fee/buyback accounting, access control, fund safety.
- The dApp: authentication/session handling, API routes, dependency vulnerabilities.

## Out of scope
- Issues requiring physical access or social engineering of users.
- Reports on the public testnet that do not affect mainnet safety.

## Audit status
Smart contracts are tested (unit + fuzz + invariant + mainnet‑fork) and statically analyzed. An
independent third‑party audit is required before any mainnet deployment that handles real funds.
