# Educators — SLURM

**Project:** SLURM  
**Category:** SUPERCOMPUTER  
**Upstream:** see BENCH.json  
**Pinned commit:** `cf399c5e140ae7dda1b1ed7ccfe0d000bb65af6d`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `e4a44f76d64467279c905c1ed06c06de273a1f14a467ecc5a15d9a6b4511ba5f`  
**Date:** October 2026

## Teaching with SLURM

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `e4a44f76d64467279c905c1ed06c06de273a1f14a467ecc5a15d9a6b4511ba5f` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
