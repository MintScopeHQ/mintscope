# MintScope

**Verified mint & airdrop intelligence for AI-agent wallets.**

MintScope is the verification layer for the Binance Agentic Wallet ecosystem. More than 124,000 Agent ID holders face thousands of free mints and claims every week — most are noise, some are traps (hidden approvals, fake free tiers, fabricated markets). MintScope checks every opportunity on-chain before it reaches members.

## How verification works

Every candidate mint or claim must pass five on-chain checks before it is published as a signal:

1. **Contract identity** — the address matches the project's official site or post
2. **Real free tier** — the contract's own quote for a real Agent ID wallet reads 0
3. **Simulation** — the exact mint/claim call is simulated before anyone signs
4. **Approval scan** — the call and its receipt are checked for hidden approvals or asset outflows
5. **Supply & window** — remaining supply and the deadline are read on-chain

Items that fail any check are published as rejected, with the reason — the filter's work is visible, not just its output.

## The service

- **Verified signals** — published to the MintScope Telegram channel with the exact contract, the exact call, and a timestamp
- **Agent-readable endpoint** (in development) — the same verified instructions in machine-readable form, so members' own agents can execute verified mints for them
- **MintScope Agent Pass** (in development) — the access key to the member service: an NFT on BNB Smart Chain, first mint free per Agent ID, five optional paid tiers, supply capped at 10,000
- **MSCP** — the service token (100M fixed supply, 0% tax), distributed to Pass holders in staged claims; the first claim is free

## Status

Pre-launch. The verification desk is live and publishing; contracts are in development and will be deployed and verified on Sourcify before launch. See [SECURITY.md](SECURITY.md) for the project's security status and disclosure policy.

## Links

- Website: https://mintscopehq.github.io/mintscope/
- Telegram: https://t.me/MintScopeOfficial
- Discussion: https://t.me/MintScopeDiscussion
- X: https://x.com/MintScopeHQ
- Contact: mintscopehq@gmail.com

## Team

- Daniel Reyes — Lead Developer
- Sarah Lindqvist — Community & Partnerships
