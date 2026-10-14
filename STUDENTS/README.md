# Students — MPICH

**Project:** MPICH  
**Category:** SUPERCOMPUTER  
**Upstream:** see BENCH.json  
**Pinned commit:** `ef3309831f0cf57e09ad89fc6e547db183cec5c7`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `d92960263151ff21c54d4ee79ed68449c7a6fbe645e50e720caa5a1f112dbf81`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `ef3309831f0cf57e09ad89fc6e547db183cec5c7`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `d92960263151ff21c54d4ee79ed68449c7a6fbe645e50e720caa5a1f112dbf81`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
