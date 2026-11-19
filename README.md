# BSC Contract Audit Skill

An AI-agent skill for auditing BNB Smart Chain (BSC) smart contracts before interacting with them: source verification, owner and proxy checks, honeypot and drain patterns, and launch-curve review.

- Version: 3.2.0 (skill) with launch-curve audit as a companion skill
- Scripts are read-only. No wallet signing and no private keys involved.
- Entry point: `SKILL.md`. Supporting references live in `references/`, helper scripts in `scripts/`.

## Origin

Based on [setyamickala/bsc-contract-audit-skill](https://github.com/setyamickala/bsc-contract-audit-skill) by setyamickala, MIT licensed. This copy is maintained by [iiciw](https://github.com/iiciw). Not affiliated with Binance.

## Install

Copy this folder into your agent skills directory, for example:

```text
~/workspace/custom-skills/bsc-contract-audit/
```

Then read `SKILL.md` and follow it before any mint or claim on BSC.
