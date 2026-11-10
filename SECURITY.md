# Security Policy — MintScope

## Current status

MintScope is in pre-launch development.

- The MintScope Agent Pass and staged-claim smart contracts are **in development and not yet deployed** to BNB Smart Chain mainnet.
- **No independent security audit has been completed yet, because there is no deployed code to audit.** An independent audit is a scheduled, funded milestone that completes **before** public launch and before the contracts handle member funds. The audit report will be published in this repository when complete.
- Until launch, this GitHub organization hosts the project website and documentation only. Any contract address claiming to be MintScope that is not announced on the official website and Telegram channel is not ours.

## Our verification standard

MintScope's signal service verifies every third-party mint or claim on-chain before publishing it: contract identity against the project's official source, the free-tier quote for a real Agent ID wallet, transaction simulation, an approval/outflow scan of the call and its receipt, and an on-chain supply/deadline read. Signals always carry the contract address and the checks performed so members can re-verify independently.

## Reporting a vulnerability

If you find a security issue in anything MintScope publishes or operates, contact **mintscopehq@gmail.com** with the details. Please do not open a public issue for a live vulnerability. We aim to acknowledge reports within 3 business days.

## Scope

This policy covers MintScope's own website, repositories, and (once deployed) smart contracts. Third-party projects that MintScope verifies are covered by their own security policies; a MintScope "verified" signal means the five checks above passed at the stated timestamp — it is not an audit and not investment advice.
