# No.71 — Unreviewed preprint v1.0

Title: Exact 1-Perfect-Code Classification of the Tribonacci Cubes Q_n(111)
Author: Ryutaro Yonezu — Independent Researcher

This is an **unreviewed, AI-assisted preprint**, version 1.0, with manuscript date 17 November 2026. See the repository and archive metadata for the publication identifiers. Human peer review and proof-assistant formal verification have not been performed.

## Publication identifiers

- Version DOI: https://doi.org/10.5281/zenodo.24295940
- All-versions DOI: https://doi.org/10.5281/zenodo.24295939
- Zenodo Preprint v1.0: https://zenodo.org/records/24295940
- Frozen GitHub Release v1.0: https://github.com/yonezaemon1-hub/no71-tribonacci-cube-perfect-codes/releases/tag/v1.0
- Frozen tag commit: `0972557db587001cf5897424743324af6fbc29ba`

The v1.0 Release and Zenodo files remain frozen at their published hashes. This branch adds the issued DOI to README and CITATION only; its SHA256SUMS tracks the seven current branch assets. Use each frozen distribution's own SHA256SUMS for its files.

## Main result
For n >= 1, Q_n(111) admits a 1-perfect code if and only if n=1 or n=3. Full mathematical proof is in the accompanying PDF and TeX.

## Verification scope
- Frozen research source: No71_v07_FINAL_AUDIT_INTEGRATED_HOLD_20261117.zip, SHA256 f893ab93e5c7c6c52d00b4bec96b880795446c4d3fcd3547f11d92e6c7b8ab57.
- The Main theorem through Completion block of the Markdown manuscript is byte-identical to the source. LaTeX/PDF apply mathematical typography without changing the definitions, statements, case splits or proof. No mathematical claims were added or removed.
- The Python script `verify_local_parity.py` in the reproduction ZIP checks n=1..4 and finite local identities; it does not formally certify the full theorem.
- An external AI audit reported no fatal proof defects and a separate SAT check through n=17. SAT code and certificates were not provided.
- Author-reported Windows reproduction PASS; not independently instrumented.
- Novelty INCONCLUSIVE. References PARTIAL. Human peer review NOT DONE; formal proof NOT DONE. No world-first or priority claim.

## Reproduce (Python 3.12+, standard library)

Unzip `No71_v1.0_reproduction.zip`, enter its extracted folder and run:

```
python -B -I verify_local_parity.py
```

Expected ending: `ALL V0.5 FINITE SANITY CHECKS PASS` (historical script message retained unchanged).

## Rights
Copyright (c) 2026 Ryutaro Yonezu. All rights reserved. No open license is granted by these files.

## Literature scope
The graph is $Q_n(111)=\Gamma_n(111)$, not the ordinary forbidden-11 Fibonacci cube or a Lucas cube. Mollard (2018), Ashrafi et al. (2016), Rho and Vesel (2016), and targeted later-work searches were compared. No directly subsuming classification was identified in the retrieved results. Citation tracing and full historical coverage remain incomplete: NOVELTY INCONCLUSIVE / REFERENCES PARTIAL. The 2018 discussion alone does not establish that n=7, s=3 remained open in 2026.

Repository: https://github.com/yonezaemon1-hub/no71-tribonacci-cube-perfect-codes
