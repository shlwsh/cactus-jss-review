# CACTUS JSS review artifact v1.39

This public, versioned release accompanies the 34-page CACTUS JSS v1.39 manuscript. The independent review ZIP is **cactus-jss-review-v1.39-20261007T083709Z.zip**, SHA-256 **eda2d5b2326b42f2d4e1404b77a9026463e710ffaf3f99579a1556a48ab06622**. Existing older ZIPs remain for historical reference; use the ZIP identified here for this revision.

Download the v1.39 ZIP from [the release page](https://github.com/shlwsh/cactus-jss-review/releases/tag/cactus-jss-review-v1.39), extract it, then run:

```sh
python -m venv .venv
# activate .venv for your operating system
python -m pip install -r environment/requirements-lock.txt
python scripts/reproduce_review_artifact.py all
```

Python, TeX with pdflatex/BibTeX (including elsarticle dependencies and placeins), and Poppler with pdfinfo/pdftotext are required. The lock freezes the installed Python dependency closure; it does not freeze operating-system fonts or all other platforms. See the package README, environment notes and RELEASE_MANIFEST.json for exact versions, source bindings and omissions.

The package supports paper regeneration, 353 value/display comparisons, 5 TeX comparisons, 6 PNG comparisons in the same environment, normalized PDF-text comparison, and fresh synthetic semantic validation with the unchanged production core (160 mutations and 20 controls). Recorded near-valid controls comprise 40 allowed variations on copied observed seeds. Original observed RUNs, source history and authorization records are omitted. Synthetic validation is not replay of the original observed study; full model/evaluator replay and independent external artifact evaluation are not asserted. Author declarations remain pending before journal submission.

The repository identifies the authors and does not claim anonymity. CACTUS-origin materials retain CC BY 4.0 from the owner-published archival series. Third-party styles retain their notices; cited full-text PDFs are omitted.

[Archival series DOI](https://doi.org/10.5281/zenodo.23205936). The [earlier version DOI](https://doi.org/10.5281/zenodo.23205937) seals the older v1.36 inner ZIP; it is not the identifier of the present v1.39 package. This version's precise reference is its release URL until a new archival version's contents are verified.
