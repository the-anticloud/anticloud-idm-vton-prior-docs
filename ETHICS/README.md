# Ethics — IDM_VTON_PRIOR_DOCS

**Project:** IDM_VTON_PRIOR_DOCS  
**Category:** CLOTHING_RETAIL  
**Upstream:** https://github.com/yisol/IDM-VTON  
**Pinned commit:** `0d5f3ec2d737487a9bb24e4100936ad254780383`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `be01e98d99c9427bbbb0719e8b536622ffb636930bcd48c2ef3a0dbe9a21f009`  
**Date:** October 2026

## Position

IDM_VTON_PRIOR_DOCS is packaged for offline deployment with a verifiable audit trail. The
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
