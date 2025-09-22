# Results — West African Archaic Introgression (chr21/22 demo)

**Scope:** chr21/22 proof-of-concept using 1000G (WA: YRI/ESN/GWD/MSL/ACB; CEU), archaic (Altai/Vindija/Denisova), and chimp (outgroup, lifted/aligned to hg19/hs37d5).

**Status:** Harmonization + common-site intersection complete; packaging to EIGENSTRAT and D-statistics next (qpDstat).

## What’s here
- `qc_summary.txt` — SNP/individual counts + quick checks
- `WA_vs_CEU_candidates.tsv` — ΔAF candidate schema
- `qpD_results.tsv` — D-statistics table
- `qpD_interpretation.md` — how to read D and Z
- `figures/` — put ΔAF scatter & D-stat bars here

## How to read
1. Check `qc_summary.txt` (nSNP, nInd by pop).
2. Review ΔAF candidates (if any) in `WA_vs_CEU_candidates.tsv`.
3. Look at `qpD_results.tsv` for D(WA,CEU;NEA,CHI) and D(WA,CEU;DEN,CHI).
4. See `qpD_interpretation.md` for thresholds and caveats.

**Notes:** Demo is chr21/22 for speed; full-genome planned. Public data only; reference is hs37d5.
