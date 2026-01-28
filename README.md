# Failure Shape Alignment

This repository documents a constrained alignment between structural failure models
and temporal observability signals, applied to real-world Ethereum incidents.

It does not introduce new failure modes, predictions, or mitigation strategies.
Instead, it focuses on how different abstractions condition what can be
interpreted from incomplete evidence.

## Core abstractions

- **Structural failure shapes** (ERC-8004)
  - What kinds of failures are possible at the interface/spec level

- **Temporal observability** (accrual lag)
  - When deviations from expected behavior become detectable over time

These abstractions are intentionally orthogonal.

## What this repo does

- Projects real incident observations onto ERC-8004 failure shapes
- Conditions those projections using temporal signals (accrual)
- Explicitly documents where interpretation must stop

## What this repo does not do

- No exploit analysis
- No scoring or prioritization
- No automated detection
- No predictions or recommendations

The goal is epistemic clarity under uncertainty.
