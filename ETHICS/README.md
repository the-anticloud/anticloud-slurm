# Ethics — SLURM

**Project:** SLURM  
**Category:** SUPERCOMPUTER  
**Upstream:** see BENCH.json  
**Pinned commit:** `cf399c5e140ae7dda1b1ed7ccfe0d000bb65af6d`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `e4a44f76d64467279c905c1ed06c06de273a1f14a467ecc5a15d9a6b4511ba5f`  
**Date:** October 2026

## Position

SLURM is packaged for offline deployment with a verifiable audit trail. The
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
