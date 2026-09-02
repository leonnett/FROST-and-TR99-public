# Public Publication Scope

This repository is an evidence pack, not a source-code distribution.

## Included

- Aggregate benchmark measurements.
- Paired quality outcomes and verifier coverage at summary level.
- Explicit PASS, FAIL, exploratory, and not-evaluated states.
- High-level hardware and model identifiers needed to interpret a result.
- Source repository links, branch names, commit identifiers, and artifact
  provenance.
- Limitations and reproducibility boundaries.

## Excluded

- Source code, scripts, tests, and architecture documents from the technology
  repositories.
- Model weights, binaries, private datasets, private repositories, and private
  fixtures.
- Raw prompts, generated completions, tool payloads, and per-task content.
- Credentials, tokens, private hostnames, absolute local paths, and personal
  machine paths.
- Raw telemetry or configuration detail whose main value would be to disclose
  internal implementation choices rather than substantiate a public result.

## Interpretation rules

1. A result is only valid for the workload and measurement contract named in
   its evidence record.
2. A short probe is not a sustained throughput certification.
3. A component reduction is not an end-to-end product claim.
4. A heuristic tokenizer result is reported as observed, not certified.
5. Source-documented evidence is identified separately when its original raw
   artifact is not present in the source repository.

The collection favors verifiable boundaries over broad claims. Negative and
incomplete gates remain visible so external reviewers can distinguish progress
from certification.
