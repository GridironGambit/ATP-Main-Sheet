# ATP Main Sheet Snapshots

This repository stores timestamped CSV snapshots of my main ATP tracking sheet:

https://docs.google.com/spreadsheets/d/1Xth9_du7_qZ18Gm-4vb7CoWF82XBK2gFc_0LW3MOdEs/edit?gid=0#gid=0

The purpose of this repository is to provide a versioned public record showing that model probabilities, staking outputs, and betting decisions were recorded before event results were known.

## Primary Snapshot

The main file to review is the final ATP-only snapshot:

- `2025 ATP Only.csv`

This file isolates the ATP portion of the 2025 tracking record from the broader main sheet.

## What These Snapshots Show

Each CSV snapshot captures the state of the tracking sheet at a specific point in time. The collection of snapshots, together with GitHub commit timestamps, provides evidence that entries were generated before the corresponding events resolved.

The sheet records information such as:

- Event/player information
- Model probabilities
- Available market prices
- Suggested staking outputs
- Pending and settled positions
- Results after events finish

The exact columns may vary slightly across snapshots because the sheet evolved during live use.

## Why GitHub Is Used Here

GitHub is used as a timestamped archive. Each committed CSV snapshot creates an external record of what the sheet looked like at that time.

This is useful because the core workflow is private, but the public snapshots can still demonstrate deployment discipline:

1. Probabilities were generated before events.
2. Stakes were computed before events.
3. Results were tracked after events.
4. The record was preserved through versioned CSV commits.

## Relationship to Gridiron Gambit

This repository supports the public Gridiron Gambit modeling overview:

https://github.com/GridironGambit/gridiron-gambit-modeling

The modeling overview explains the broader NFL and ATP forecasting workflow, including data ingestion, market-line normalization, probability modeling, manual line verification, position sizing, and tracking.

This repository is narrower: it exists specifically to archive ATP sheet snapshots.

## Interpreting the Records

These files are included to document live deployment and realized tracking history. They are not intended to fully reproduce the private modeling workflow, expose active feature logic, or serve as a complete execution audit.

Realized performance should be interpreted alongside:

- Sample size
- Market limits
- Line movement
- Execution quality
- Liquidity
- Pending exposure
- Variance

The snapshots are best understood as timestamped evidence of the operating record rather than a standalone explanation of the full model.

## Notes

Core modeling code, production scrapers, active feature-engineering logic, and private datasets are not included in this repository.