# Contributing to DevSwap

Thanks for your interest! DevSwap is an on‑chain marketplace, so quality and safety bars are high.

## Ground rules
- **Security first** for any money‑touching code (contracts): CEI, `ReentrancyGuard`, `SafeERC20`,
  `Ownable2Step`, `Pausable`. When in doubt, choose the more conservative option.
- **Tests required**: new behavior needs tests. Contracts target high coverage (unit + fuzz + invariant).
- **i18n**: never hardcode user‑facing strings — every string lives in `messages/{en,ar}.json` (parity enforced).
- **Legal‑safe copy**: the smart contract is the actor — avoid custody/guarantee/escrow wording in
  user‑facing text (enforced in CI).
- **Conventional Commits**: `feat|fix|refactor|test|docs|chore(scope): summary`.

## Workflow
1. Fork / branch from `main`.
2. Make focused, atomic changes (no mixing refactors with features).
3. Run the gates: typecheck · lint · tests · build.
4. Open a PR with a clear description and screenshots for any UI change (EN + AR).

## Reporting bugs / ideas
Use the issue templates. For **security vulnerabilities**, follow [SECURITY.md](SECURITY.md) — do not
open a public issue.
