# Students — IDM_VTON_PRIOR_DOCS

**Project:** IDM_VTON_PRIOR_DOCS  
**Category:** CLOTHING_RETAIL  
**Upstream:** https://github.com/yisol/IDM-VTON  
**Pinned commit:** `0d5f3ec2d737487a9bb24e4100936ad254780383`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `be01e98d99c9427bbbb0719e8b536622ffb636930bcd48c2ef3a0dbe9a21f009`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `0d5f3ec2d737487a9bb24e4100936ad254780383`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `be01e98d99c9427bbbb0719e8b536622ffb636930bcd48c2ef3a0dbe9a21f009`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
