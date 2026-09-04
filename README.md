# FROST & TR99 — Public Evidence

This repository is a public evidence collection for two separate technology
projects: **FROST** and **TR99**.

These research materials are from **The Mythos Company**.

It is prepared for external review, including accelerator and partner review.
The collection contains benchmark summaries, evidence records, scope notes, and
source provenance. It intentionally does not contain source code, model
weights, private fixtures, raw prompts or completions, credentials, or internal
implementation documentation.

## Projects

| Project | Short description | Public material |
| --- | --- | --- |
| [FROST](FROST/) | An evidence-driven AI runtime optimization project focused on measured, hardware-aware workload results. | Mac v1 E99 quality evidence and S200 performance evidence. |
| [TR99](TR99/) | An evidence-driven runtime evaluation project focused on context efficiency in agent workloads. | Component measurements, HTTP end-to-end evidence, and certification boundaries. |

## Headline evidence

### FROST

- The Mac v1 runtime 2 evidence records a formal **E99 PASS** across **378 paired tasks**, with **321 baseline errors**, **1 FROST error**, **0 negative flips**, and **378/378 independent verifier coverage**.
- The measured error reduction is **99.6885%**, with a **99.0415% lower 95% paired-bootstrap bound**.
- The sustained **S200** benchmark is **PASS**: 687.4 seconds, 20 requests, 368,640 physical output tokens, and 536.27 aggregate tokens per second.

### TR99

- A fresh local HTTP run exercised **50 end-to-end requests** across five declared task families; all 50 were solved and verified.
- The run measured 3,683,190 baseline tokens and 13,890 runtime-processed tokens, a **99.6229%** reduction under the recorded fixture and heuristic tokenizer.
- That run is labeled **not certified** because an exact pinned tokenizer was not installed.
- The source repository also documents an earlier exact-tokenizer result; it is preserved separately as source-documented evidence, not represented as a fresh rerun.

## Publication policy

See [PUBLICATION_SCOPE.md](PUBLICATION_SCOPE.md) for the inclusion and
redaction rules used to assemble this collection.

All metrics remain scoped to their declared workload, hardware, model, and
measurement method. No number in this repository should be read as a universal
performance or quality guarantee.

## Source repositories

- [FROST — Mac v1 runtime branch](https://github.com/leonnett/FROST/tree/FROST/mac/v1/FROST%20Mac%20v1%20runtime.)
- [TR99](https://github.com/leonnett/TR99)

## Branches

- `FROST&TR99/latest` is the default publication branch.
- `FROST&TR99/dev` is the active working branch.
