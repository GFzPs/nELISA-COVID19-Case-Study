# nELISA × COVID-19 PBMC Proteomics Case Study

This repository contains a Jupyter/Colab notebook demonstrating an
end-to-end proteomics analysis pipeline inspired by Nomic Bio’s nELISA platform.

### Contents
- Loading COVID-19 Olink proteomics dataset  
- Loading PBMC immune-stimulation nELISA dataset  
- Rigorous QC, missingness, normalization  
- Differential expression / effect size modeling  
- Concordance mapping across assays  
- Dimensionality reduction (PCA/UMAP)  
- A scientist tool **“Cytokine Insight Engine”** with:
  - Decorator-based routing (`@route`)
  - Top-N cytokine retrieval
  - Threshold filtering  
  - Priority-score ranking  
  - SQL mini-database demo  
  - MongoDB-like query demo  
  - Interactive widget toggle menu
    
### Purpose

This notebook is a data engineering and computational biology case study
submitted as part of my application for the **Data Associate role**.

### Environment
Python 3.10+ and:
`pandas`, `numpy`, `scipy`, `scikit-learn`, `matplotlib`, `seaborn`, `ipywidgets`.
