# Diffusion MRI — DTIFIT (FA/MD) on tutorial data
[![License](https://img.shields.io/github/license/andraderenew/dti_fsl-dtifit_tutorial)](LICENSE)
[![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.XXXXXXX-blue)](#cite-this-work)
[![Pages](https://img.shields.io/website?url=https%3A%2F%2Fandraderenew.github.io%2Fdti_fsl-dtifit_tutorial%2F)](https://andraderenew.github.io/dti_fsl-dtifit_tutorial/)
![Release](https://img.shields.io/github/v/release/andraderenew/dti_fsl-dtifit_tutorial?include_prereleases)
![Last commit](https://img.shields.io/github/last-commit/andraderenew/dti_fsl-dtifit_tutorial)
[![ORCID](https://img.shields.io/badge/ORCID-0000--0001--5627--579X-A6CE39)](https://orcid.org/0000-0001-5627-579X)
[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-Profile-4285F4)](https://scholar.google.es/citations?hl=es&user=Nl3ApFEAAAAJ)

**One-line:** Compact DTI pipeline (TOPUP/EDDY if available) to compute FA/MD and summarize a few anatomical ROIs.

## Overview
Minimal **DTI** pipeline with **FSL**: (TOPUP/EDDY if available) → **DTIFIT** → FA/MD maps and a couple of ROI summaries; optional mini-TBSS.

## Data & subset
See `DATA_SOURCES.md`. Suggested: 1 subject; disk in hundreds of MB.

## Pipeline
TOPUP/EDDY (if AP/PA pairs) → DTIFIT → ROI means (e.g., corpus callosum) → (opt) TBSS with a few subjects.

## Results (to be filled)
- FA/MD slices (PNG)  
- ROI table (FA/MD)

## Reproducibility
- Versions: see `env/TOOL_VERSIONS.md`  
- Steps: “Run corrections → DTIFIT → extract ROIs → figures.”  
- Limits: single-subject demo

## Cite this work
See `CITATION.cff` (add DOI after first Release).
