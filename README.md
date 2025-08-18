# HDAC2-QSAR-Docking-ML-MD
This repository contains all supplementary materials for the manuscript:  
**Integrating Machine Learning and Molecular Simulations for the Design of Potent HDAC2 Inhibitors in Diffuse Large B-Cell Lymphoma**

## Repository Structure
- **data/**
  - `HDAC2_raw_chembl_dataset.csv` – Raw dataset obtained from ChEMBL before cleaning.  
  - `Supplementary_Table_1_HDAC2.csv` – Curated dataset including selected descriptors, predicted activities, residuals, and leverage statistics.  

- **scripts/**
  - `HDAC2_QSAR_ML_Workflow.ipynb` – Python workflow for dataset curation, descriptor preprocessing, and Random Forest QSAR model building.  
  - `HDAC2_docking_workflow.py` – Automated batch docking pipeline using AutoDock Vina.  

## Usage
All workflows were executed in Python (RDKit, scikit-learn, matplotlib). Docking was performed with AutoDock Vina.  
