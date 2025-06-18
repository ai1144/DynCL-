# Pain-Related fMRI Data Analysis & Embedding Training

This repository contains Python notebooks for exploratory data analysis (EDA) and representation learning using CEBRA on two pain-related fMRI datasets:

- **PainData_TH**: Data from healthy subjects undergoing induced pain.
- **PainDataChronicBackPain (CBP)**: Data from patients with chronic back pain.

All datasets are provided as `.mat` files and have been preprocessed using Glasser atlas-based parcellation.

## Contents

### 1. `THdataset.ipynb`
**Purpose**: Exploratory data analysis of the `PainData_TH` dataset.

**Highlights**:
- Visual inspection of pain-related time series.
- Subject-wise variability.
- Sanity checks on missing values and session alignment.
- Heatmaps and additional statistics over 360 Glasser parcels.

---

### 2. `CBP_EDA.ipynb`
**Purpose**: EDA for the `PainDataChronicBackPain` dataset.

**Highlights**:
- Cross-subject and cross-session analysis of chronic pain signals.
- Comparison with the healthy dataset (PainData_TH).
- Investigation of structural differences and documentation discrepancies.
- Exploration of temporal continuity and variance in chronic pain responses.

---

### 3. `TH&CBP_CEBRA.ipynb`
**Purpose**: CEBRA training for time and behavior embeddings.

**Highlights**:
- Time-embedding and AMP-based behavior-embedding training.
- Embedding visualization.
- Consistency and decoding quality evaluation.

---

## Dependencies

- Python ≥ 3.9  (what I used personally)
- [CEBRA](https://github.com/AdaptiveMotorControlLab/cebra)  
- `numpy`, `matplotlib`, `scipy`, `seaborn`, `pandas` , `scikit-learn`

