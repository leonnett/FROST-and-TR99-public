# FROST evidence

FROST is an evidence-driven AI runtime optimization project. This folder
contains a public summary of the Mac v1 measurements and quality evidence from
the source runtime branch.

## Contents

- [`benchmarks/`](benchmarks/) contains aggregate performance measurements from
  the native and guarded Mac probes.
- [`evidence/`](evidence/) contains the bounded quality certificate and the
  release-gate status.

## Scope

The quality certificate is a bounded E90 result for a frozen Python MBPP
holdout: 43 baseline errors were reduced to 0 FROST errors across 50 paired
tasks, a 100% reduction in observed baseline errors. The performance records
are intentionally presented at summary level and omit source code, raw model
output, local paths, and implementation-only detail.

## Provenance

- Source repository: [leonnett/FROST](https://github.com/leonnett/FROST)
- Source branch: `FROST/mac/v1`
- Source commit: `dc3d4e02f5887b6b7edb3c32a9531a76524f796a`
