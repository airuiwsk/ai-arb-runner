# ai-arb-runner

Public GitHub Actions runner for the private `airuiwsk/AI-Arbitrage` repository.

This repository contains execution configuration only. The arbitrage scanner source code, telemetry, opportunity events, and research remain in the private repository.

## Purpose

Run the existing read-only Python scanner continuously enough for a seven-day opportunity-existence observation without Render.

## Security

- no wallet or private key
- no transaction submission
- no automatic trading
- no paid RPC
- private repository access uses a fine-grained PAT stored only as a GitHub Actions secret

See `AI-ARBITRAGE-SETUP.md` for one-time setup.
