# Psilocybin Dataset Readiness

A research-readiness project focused on auditing, organizing, and characterizing the OpenNeuro **ds006072** dataset (*Psilocybin Precision Functional Mapping*). This repository establishes technical familiarity with dataset structure, metadata, repeated-measures design, and future analysis feasibility for neuroplasticity-focused research.

---

## Project Rationale

Before hypothesis-driven analysis, rigorous neuroimaging research begins with understanding the dataset itself. This repository was developed as a structured preliminary project to evaluate the usability, richness, and analytical potential of a public psilocybin neuroimaging dataset.

The emphasis is on dataset literacy, reproducibility, and readiness for future individual-differences research.

---

## Dataset Overview

* **Dataset ID:** ds006072
* **Title:** Psilocybin Precision Functional Mapping
* **Source:** OpenNeuro
* **License:** CC0
* **BIDS Version:** 1.6.0
* **Dataset Type:** Raw

This dataset is associated with the published study:
**Psilocybin desynchronizes the human brain** (Nature, 2024)

---

## Key Structural Findings

* **11 participant folders** identified
* **4 replication participants** (`P1R`, `P3R`, `P4R`, `P5R`)
* **129 session records** in custom metadata tables
* Repeated-measures and longitudinal sampling structure present
* Comparator drug condition documented (**methylphenidate**)
* Behavioral, imaging, and phenotypic data sources available

---

## Repository Workflow

### Notebook 1 - Download and Structure

Inspected top-level dataset organization, subject identifiers, and metadata files.

### Notebook 2 - Subjects and Sessions Inventory

Created participant-level summaries of session coverage and repeated IDs.

### Notebook 3 - Metadata Audit

Reviewed dataset documentation, study design, acquisition details, and governance metadata.

### Notebook 4 - Visual Overview

Generated descriptive figures summarizing participant structure and session distribution.

### Notebook 5 - Summary and Next Steps

Synthesized readiness findings and mapped future repository directions.

---

## Repository Contents

This repository currently contains:

* Five Google Colab notebooks documenting the full dataset-readiness workflow
* Descriptive figures generated from session and participant metadata
* A final README summarizing key findings and future directions

Additional structured outputs can be regenerated directly by running the notebooks.

---

## Why This Project Matters

This repository demonstrates that meaningful research preparation begins before formal hypothesis testing. By establishing fluency with dataset structure, documentation, and design logic, it creates a strong foundation for future work in psilocybin-related cognitive neuroplasticity.

---

## Planned Next Repositories

* `psilocybin_repo2-functional-connectivity-variability`
* `psilocybin_repo3-acute-vs-postacute-trajectories`
* `psilocybin_repo4-neural-cognitive-correspondence`
* `psilocybin_repo5-reproducibility-analysis`

---

## Tools Used

* Python
* Pandas
* Matplotlib
* Seaborn
* AWS CLI
* Jupyter Notebook / Google Colab

---

## Maintained By

Aditya Sundaray
