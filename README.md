## Overview
This project aims to build a machine learning model to identify inactive compounds targeting the GLP-1 receptor, in order to reduce false positives in virtual screening.

## Data
- Source: ChEMBL (public database)
- Size: ~370,000 compounds
- Preprocessing: cleaning, normalization, feature generation

## Workflow
1. Data curation and quality control
2. Feature engineering using molecular fingerprints (ECFP, Avalon, RDKit)
3. Model training and evaluation
4. Interpretation of results with biological relevance

## Tools
- Python
- Pandas, Scikit-learn
- RDKit
