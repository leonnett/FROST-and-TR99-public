# FROST evidence

FROST is an evidence-driven AI runtime optimization project. This folder
contains a public summary of the Mac v1 runtime 2 measurements and quality
evidence from the source runtime branch.

## Contents

- [`benchmarks/`](benchmarks/) contains the E99 quality and S200 performance
  benchmark summaries.
- [`evidence/`](evidence/) contains the E99 and S200 evidence records.

## Scope

The current quality record is a formal E99 result for the complete 378-task
Python MBPP holdout: 321 baseline errors were reduced to 1 FROST error, with a
99.6885% observed error reduction, a 99.0415% lower 95% paired-bootstrap bound,
0 negative flips, and 378/378 independent verifier coverage. The current
performance record is an S200 pass from the same runtime 2 evidence set.

All records are intentionally presented at summary level and omit source code,
raw model output, local paths, and implementation-only detail.

## Provenance

- Source repository: [leonnett/FROST](https://github.com/leonnett/FROST)
- Source branch: `FROST/mac/v1`
- Source commit: `aa099a9b4258cb7c64e7e48e48a2a0f139ed0605`
