# Educators — SIMCCS2

**Project:** SIMCCS2  
**Category:** CARBON_CAPTURE  
**Upstream:** see BENCH.json  
**Pinned commit:** `see BENCH.json`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `e9df05316b7530272431c121dfea0a11bbba03d7211fc48768909342921d49bb`  
**Date:** October 2026

## Teaching with SIMCCS2

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `e9df05316b7530272431c121dfea0a11bbba03d7211fc48768909342921d49bb` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
