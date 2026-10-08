# CACTUS JSS review artifact v1.43

The three current immutable assets are identified by RELEASE_ASSETS.json and SHA256SUMS.
Download them from the [v1.43 Release](https://github.com/shlwsh/cactus-jss-review/releases/tag/cactus-jss-review-v1.43). Older files and tags remain available.

The primary review ZIP is cactus-jss-review-v1.43-20261008T010442Z.zip. Its SHA-256 is 6d3e31c3a4b35f79e95e543e0d8c447be4aab8d9538ab23499ea3c7e4fed0b36.
Extract it, install environment/requirements-lock.txt in a separate Python environment,
and run python scripts/reproduce_review_artifact.py all with TeX and Poppler on PATH.

The package regenerates 379 value/display pairs, 185 manuscript mappings, 7 TeX artifacts,
6 PNGs and the normalized 36-page v1.43 manuscript. New synthetic fixtures exercise the
unchanged production core (160 semantic rejections, 20 admitted controls). Recorded
near-valid projections preserve 40 admissions. These are bounded validation observations,
not population detection guarantees or benchmark-wide repair-effectiveness estimates.

Original observed RUNs, source history, independent authorizations and billing identities
are omitted. Full model/evaluator replay and independent original-archive re-admission
are not certified. The package's frozen manuscript preserves preparation-time local
candidate/DOI-pending annotations. Subsequent public verification and the exact archived
version DOI will be recorded in Release notes and PUBLIC_VERIFICATION.json after checking.

The series DOI is https://doi.org/10.5281/zenodo.23205936. The prior v1.40 DOI
https://doi.org/10.5281/zenodo.23213922 identifies v1.40 only. Neither identifies the
immutable v1.43 assets. The repository is public; anonymity is not asserted.

Provided author information and declarations are applied. Remaining author facts and
approval of final manuscript bytes are independent of public release verification.
CACTUS-origin material retains CC BY 4.0. Third-party styles keep their notices;
third-party cited full-text PDFs are omitted. No new model/evaluator experiment occurred.
