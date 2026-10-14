# Educators — MPICH

**Project:** MPICH  
**Category:** SUPERCOMPUTER  
**Upstream:** see BENCH.json  
**Pinned commit:** `ef3309831f0cf57e09ad89fc6e547db183cec5c7`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `d92960263151ff21c54d4ee79ed68449c7a6fbe645e50e720caa5a1f112dbf81`  
**Date:** October 2026

## Teaching with MPICH

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `d92960263151ff21c54d4ee79ed68449c7a6fbe645e50e720caa5a1f112dbf81` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
