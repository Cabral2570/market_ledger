# market_ledger

## What is this?

A personal record of my market theses, analyses, predictions, and post-mortems. Successes, failures, and lessons — all timestamped.

Nothing is deleted, not even the losses.

## Rules

- **Ex-ante only:** Every thesis or prediction is written before the event.
- Nothing is deleted or edited retroactively — corrections, updates, and post-mortems are appended in new commits, never by altering the original text. Failures stay on the record just as successes do.
- Entries are numbered sequentially within each folder `memos/` and `theses/`.
- The quality of the reasoning, calibration, and decision is the primary focus of evaluation.
- Every commit affecting `memos/` or `theses/` generates an automated [OpenTimestamps](https://opentimestamps.org/) (`.ots`) proof of existence in `audit-log/` for independent verifiability.

## Repository Structure

```text
├── memos/          # Pre-earnings, IPO & market-event memos
├── theses/         # Full equity research theses
├── audit-log/      # Automated commit manifests + OpenTimestamps (.ots) proofs
├── notes.md        # General log, repo updates & milestones
└── templates/      # Markdown templates for memos & theses
```
