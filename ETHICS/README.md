# Ethics — MPICH

**Project:** MPICH  
**Category:** SUPERCOMPUTER  
**Upstream:** see BENCH.json  
**Pinned commit:** `ef3309831f0cf57e09ad89fc6e547db183cec5c7`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `d92960263151ff21c54d4ee79ed68449c7a6fbe645e50e720caa5a1f112dbf81`  
**Date:** October 2026

## Position

MPICH is packaged for offline deployment with a verifiable audit trail. The
ethical questions this raises are answered by making the system's behaviour
checkable rather than by policy statements.

## The four commitments

1. **No hidden egress.** The deployment has no external API dependency; this is
   testable by running it with the network disconnected.
2. **Attributable output.** Every artifact is recorded in a hash chain, so what
   the system produced can be reconstructed.
3. **Operator control.** The institution owns the hardware and the keys.
4. **Refusal to overclaim.** Where a certification is not held, the project says
   so rather than implying it.

## Dual use

This project is packaged for civilian and public-sector deployment. Where an
upstream has dual-use characteristics, the licence gate and the reference-only
marking in `BENCH.json` record that.
