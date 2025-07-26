# Chemoinformatics
Cheminformatics project: analyzing molecules that bind the human B2AR receptor and building a Random Forest model to classify their bioactivity

# B2AR Bio-cheminformatics Analysis

This repository contains a Jupyter Notebook for the exploratory analysis of small molecules targeting the **Beta-2 Adrenergic Receptor (B2AR)** and a **Random Forest Classifier** predicting their bioactivity class. 

# Project Overview 

- **Goal**: Identify and analyze molecular features influencing binding to B2AR.
- **Methods:**  
  - Perform **Principal Component Analysis (PCA)** to reduce dimensionality.
  - Select top features covering ~99% of total variance.
  - Train a **Random Forest Classifier** to predict whether a molecule is active or inactive.
- **Data:** Chemical descriptors/features for a set of known B2AR ligands. We use Mordred, Lipinski Descriptors and MACCSKeys. 

# Tools & Libraries

  Python 3.13
- Jupyter Notebook
- scikit-learn (PCA, Random Forest)
- pandas, numpy, matplotlib, seaborn
