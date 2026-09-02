# TR99 evidence

TR99 is an evidence-driven runtime evaluation project focused on context
efficiency in agent workloads. This folder contains public benchmark summaries
and the associated verification boundaries.

## Contents

- [`benchmarks/`](benchmarks/) contains the component benchmark and a fresh
  HTTP end-to-end run performed during this publication audit.
- [`evidence/`](evidence/) contains the source-documented verification record
  and its certification status.

## Scope

The reported measurements are scoped to declared deterministic fixtures and
task families. They do not establish a universal 99% reduction for arbitrary
agent tasks. Results using a heuristic tokenizer are explicitly marked as not
certified.

## Provenance

- Source repository: [leonnett/TR99](https://github.com/leonnett/TR99)
- Source branch: `TR99/main`
- Source commit: `4ee630df9b0c4363e6febce734228c8a65b0c11a`
- Earlier source-documented benchmark commit: `c9d487a`
