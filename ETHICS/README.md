# Ethics — FABRIC_JS

**Project:** FABRIC_JS  
**Category:** CLOTHING_MANUFACTURING  
**Upstream:** https://github.com/fabricjs/fabric.js.git  
**Pinned commit:** `39471c7a379c08347841f4282dd3940b49ed4c71`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `64e2cfe747a72e03eb9bd865c2d72918666430ccd80ca40062c45f838885a22c`  
**Date:** October 2026

## Position

FABRIC_JS is packaged for offline deployment with a verifiable audit trail. The
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
