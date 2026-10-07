# CACTUS JSS review artifact v1.40

Published files preserve the validated 36-page v1.40 submission candidate byte for byte.
The independent review ZIP is **cactus-jss-review-v1.40-20261007T122600Z.zip**, SHA-256 **8cb3b0c92e2059f3f7e966a62e300307454efc921a4e3afae5a9c2ca90db6158**.
Download the files from the [v1.40 release](https://github.com/shlwsh/cactus-jss-review/releases/tag/cactus-jss-review-v1.40).
`RELEASE_ASSETS.json` and `SHA256SUMS` identify this version's four primary assets.
Older packages and releases remain preserved.

## Reproduce the review package

Extract the independent review ZIP and run:

```sh
python -m venv .venv
# Activate the virtual environment for your operating system.
python -m pip install -r environment/requirements-lock.txt
python scripts/reproduce_review_artifact.py all
```

Python, TeX with pdflatex/BibTeX and the listed dependencies, and Poppler
with pdfinfo/pdftotext are required. The Python lock does not freeze the OS or fonts.
See README.md, environment notes, and RELEASE_MANIFEST.json inside the ZIP.

The validated package compares 379 value/display pairs, 178 manuscript mappings,
7 generated TeX artifacts, 6 PNGs, and normalized 36-page manuscript text.
New synthetic fixtures exercise the unchanged production admission core
(TP160/FN0/FP0/TN20). Recorded near-valid projections retain 40 admissions.
The new seed summary requires full within-seed operator coverage; both rows are 20/20.
Appendix C lists the actual overlapping semantic reasons from retained decisions.
These observations are not independent population samples or repair-effectiveness estimates.

Original observed RUNs, source history, independent authorization records and billing
identities are omitted. The package does not certify full original-archive re-admission,
model/evaluator replay, or independent external artifact evaluation.
The rehearsal uses a fresh virtual environment on the same Windows host.
Whole-archive integrity remains FAIL; full project tests timed out.

## Files and publication status

The independent review ZIP supports reproducibility. The flat-upload ZIP is the
isolated-compiled Editorial Manager source. The evidence-corrected ZIP preserves
the local publication source tree and is not the flat upload package.
The PDF and embedded release metadata retain the truthful preparation-time status:
the package was a local candidate and no current exact DOI had been verified yet.
Current public availability and subsequent archival verification are recorded in the
GitHub release notes; they do not imply approval of pending author declarations.
Postal details, funding/competing interests, CRediT, AI human review and final author
approval must be completed before journal submission.

The [concept DOI](https://doi.org/10.5281/zenodo.23205936) identifies the artifact series.
The [v1.39 exact DOI](https://doi.org/10.5281/zenodo.23207699) identifies the previous
version. Neither is the exact identifier for these v1.40 bytes.
The current exact DOI will be recorded only after the new Zenodo archive contents
have been downloaded and matched to all four hashes.

The repository is public and identifies the authors. CACTUS-origin material retains
CC BY 4.0; third-party styles retain their notices. Third-party full-text cited PDFs
are omitted. Public access does not constitute an independent artifact evaluation.
