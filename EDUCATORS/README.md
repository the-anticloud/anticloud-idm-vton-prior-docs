# Educators — IDM_VTON_PRIOR_DOCS

**Project:** IDM_VTON_PRIOR_DOCS  
**Category:** CLOTHING_RETAIL  
**Upstream:** https://github.com/yisol/IDM-VTON  
**Pinned commit:** `0d5f3ec2d737487a9bb24e4100936ad254780383`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `be01e98d99c9427bbbb0719e8b536622ffb636930bcd48c2ef3a0dbe9a21f009`  
**Date:** October 2026

## Teaching with IDM_VTON_PRIOR_DOCS

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `be01e98d99c9427bbbb0719e8b536622ffb636930bcd48c2ef3a0dbe9a21f009` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
