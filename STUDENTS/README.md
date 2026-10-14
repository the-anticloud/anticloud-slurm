# Students — SLURM

**Project:** SLURM  
**Category:** SUPERCOMPUTER  
**Upstream:** see BENCH.json  
**Pinned commit:** `cf399c5e140ae7dda1b1ed7ccfe0d000bb65af6d`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `e4a44f76d64467279c905c1ed06c06de273a1f14a467ecc5a15d9a6b4511ba5f`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `cf399c5e140ae7dda1b1ed7ccfe0d000bb65af6d`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `e4a44f76d64467279c905c1ed06c06de273a1f14a467ecc5a15d9a6b4511ba5f`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
