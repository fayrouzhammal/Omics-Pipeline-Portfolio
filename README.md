# Analysis of scRNA-seq Dataset GSE244267: Prostate Cancer Progression

## Overview

This repository contains analysis scripts, datasets, and results for the scRNA-seq dataset GSE244267, focused on understanding molecular alterations in tumor stroma that influence prostate cancer progression.

## Dataset Information

**Title:** Distinct mesenchymal cell states mediate prostate cancer progression (human)

**Summary:** 
We compare mesenchymal cells from genetically engineered mouse models (GEMMs) of prostate cancer to human tumors with comparable genotypes. This led to the identification of 8 distinct stromal populations that mediate prostate cancer progression. Further details can be found on the [GEO Dataset Page](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE244267).

**Contributors:** 
Pakula H, Omar M, Carelli R, and many others from Weill Cornell Medicine.

## Repository Structure

- `data/` : Raw and processed data files from GEO.
- `scripts/` : All analysis scripts used in this project.
- `results/` : Output files, including figures, tables, and other results.
- `docs/` : Documentation and notes related to the analysis.
- `README.md` : This file.

## Analysis Pipeline

1. **Data Preprocessing**:
    - Quality Control
    - Read Mapping
    - Quantification
2. **Data Analysis**:
    - Data Filtering and Normalization
    - Dimensionality Reduction (PCA, UMAP)
    - Clustering
    - Differential Expression Analysis
    - Annotation
3. **Data Interpretation**: Relating cell types/states to prostate cancer progression.
4. **Validation**: (If applicable)
5. **Visualization**.

## Getting Started

1. Clone this repository:
```bash
git clone [repository_url]
```

2. Navigate to the repository directory:
```bash
cd path_to_repository
```

3. (Optional) Set up a virtual environment:
```bash
python3 -m venv venv
source venv/bin/activate
```

4. Install necessary dependencies:
```bash
pip install -r requirements.txt
```

5. Run the analysis script:
```bash
python scripts/analysis_script.py
```

## Dependencies

- [Seurat](https://satijalab.org/seurat/)
- [Scanpy](https://scanpy.readthedocs.io/)
- Other libraries and tools mentioned in `requirements.txt`.

