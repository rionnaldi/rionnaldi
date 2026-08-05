<div align="center">

# Rionaldi

### Web3 Security Researcher · Smart Contract Auditor · Whitehat

I analyze smart contracts and blockchain infrastructure through audit competitions, bug bounty programs, differential review, and reproducible exploit testing.

[![Immunefi](https://img.shields.io/badge/Immunefi-Orionn-5C34F4?style=for-the-badge)](https://immunefi.com/profile/Orionn/)
[![Sherlock](https://img.shields.io/badge/Sherlock-Orionn-111827?style=for-the-badge)](https://audits.sherlock.xyz/watson/Orionn)
[![Code4rena](https://img.shields.io/badge/Code4rena-4funnds-2B6CB0?style=for-the-badge)](https://code4rena.com/@4funnds)

</div>

## About

I focus on finding vulnerabilities with concrete attacker reachability, reproducible execution paths, and defensible impact. My work spans EVM smart contracts, DeFi protocol accounting, cross-chain systems, and blockchain consensus or state-machine behavior.

I participate as **Orionn** on Immunefi and Sherlock, and as **4funnds** on Code4rena.

## Audit Competition Portfolio

| Platform | Identity | Work | Portfolio |
| --- | --- | --- | --- |
| Immunefi | `Orionn` | Audit competitions and live bug bounties | [View profile](https://immunefi.com/profile/Orionn/) |
| Sherlock | `Orionn` | Watson audit competitions | [View profile](https://audits.sherlock.xyz/watson/Orionn) |
| Code4rena | `4funnds` | Warden audit competitions | [View profile](https://code4rena.com/@4funnds) |

Platform profiles are the source of truth for finalized findings, placements, and rewards.

## Curated Notable Findings

| Finding or accepted result | Target | Platform | Severity | Result | Public evidence |
| --- | --- | --- | --- | --- | --- |
| Accepted vulnerability set across the XRPL-native lending implementation | XRPL Lending Protocol | Immunefi | 1 Critical · 1 High · 2 Medium/Low | **#7 of 54** · **$8,013** | [Competition results](https://immunefi.com/audit-competition/xrpl-ripple-attackathon/leaderboard/) |
| Accepted consensus, P2P, transaction-pool, and native-contract findings in the Hayabusa upgrade | VeChainThor Hayabusa | Immunefi | 4 Medium/Low | **#5 of 16** · **$1,677** | [Published findings](https://reports.immunefi.com/vechain-hayabusa-upgrade-or-attackathon) |
| [`periodAtTimestamp()` ignores its input and returns the current period](https://reports.immunefi.com/firelight/59467-sc-low-periodattimestamp-ignores-input-parameter) | FirelightVault | Immunefi | Low | **#31 of 44** · **$16** | [Report #59467](https://reports.immunefi.com/firelight/59467-sc-low-periodattimestamp-ignores-input-parameter) |
| Accepted smart-contract vulnerability in Plume's RWA-focused protocol stack | Plume Network | Immunefi | High | **#93 of 123** · **$48** | [Competition results](https://immunefi.com/audit-competition/plume-network-attackathon/leaderboard/) |

Accepted-result rows use public competition-level counts where the canonical published report does not expose every duplicate submitter. Only finalized results with stable public evidence are listed.

## Security Research Focus

- **Smart contracts and DeFi:** accounting invariants, rounding and precision, state transitions, liquidation paths, oracle assumptions, reentrancy, authorization, and economic attacks.
- **Cross-chain systems:** bridge messaging, state synchronization, replay protection, payload validation, and failure handling across trust boundaries.
- **Blockchain infrastructure:** consensus-adjacent logic, validator and producer state machines, mempool or execution interactions, liveness, and chain-specific protocol modifications.
- **Audit methodology:** architecture and entry-point mapping, differential analysis, hypothesis-driven review, adversarial falsification, fuzzing, invariant testing, fork tests, and multi-node devnet harnesses.

## Tools and Languages

`Solidity` · `Foundry` · `Go` · `Python` · `Rust` · `Semgrep` · `Slither` · `Docker` · `Kurtosis` · `Git`

## Current Work

- Conducting authorized security research against production smart-contract and blockchain systems.
- Building reconnaissance and vulnerability-analysis tooling for defensive Web3 security.
- Developing deterministic test harnesses for protocol, bridge, consensus, and state-machine hypotheses.
- Converting incident reports and audit findings into reusable detection knowledge and testable security invariants.

## Research Principles

1. **Evidence over intuition** — a plausible hypothesis is only a lead until the relevant execution path is demonstrated.
2. **Exploitability before severity** — attacker access, prerequisites, affected assets, and protocol recovery determine real impact.
3. **Reproducibility matters** — findings should survive deterministic tests, realistic fork or devnet conditions, and adversarial review.
4. **Responsible disclosure** — all security work is performed through authorized competitions, bug bounty programs, or controlled test environments.

---

<div align="center">

**Securing onchain systems by turning protocol assumptions into testable adversarial hypotheses.**

</div>
