# Diffusion MRI: DTIFIT (FA/MD) on tutorial data

**Goal:** Run a compact DTI pipeline (TOPUP/EDDY if available, DTIFIT) and summarize FA/MD in a few ROIs; optionally demo TBSS.

---

## Snapshot
- **Dataset:** FSL DTI tutorial (single subject) or another tiny DWI sample
- **Local subset:** 1 subject · **Disk:** few hundred MB
- **Tools:** FSL (TOPUP/EDDY/DTIFIT)
- **Status:** <planned / in progress / complete>
- **Last updated:** <YYYY-MM-DD>

---

## Data
- **Source:** tutorial DWI set.  
- **What I downloaded:** subject files + bvals/bvecs.  
- **Layout:** standard FSL inputs.

---

## Pipeline (high-level)
1) (If available) TOPUP/EDDY correction  
2) DTIFIT → FA/MD maps  
3) ROI means (e.g., corpus callosum)  
4) (Optional) TBSS with a handful of subjects

---

## Results (to be filled)
- Figure: FA map slices  
- Table: ROI FA/MD

---

## Reproducibility
- Versions in `env/TOOL_VERSIONS.md`.  
- Steps: “Run corrections → DTIFIT → extract ROIs → figures.”  
- Limitations: single-subject demo.

---

**Author:** Rene Andrade Rey · 🧪 ORCID: https://orcid.org/0000-0001-5627-579X · 🌐 Scholar: https://scholar.google.es/citations?hl=es&user=Nl3ApFEAAAAJ
