
# Project Code Release

This repository provides the complete source code used in our paper, including all main methods and ablation studies.

## Contents

The repository contains the following Jupyter notebooks (algorithm implementations / experiments):

- `featureprocessing.ipynb` — data preprocessing & feature engineering
- `SeqRecon-AD-v2.ipynb` — main proposed method (version 2)
- `SeqRecon-AD-S.ipynb` — variant / simplified setting
- `ablation.ipynb` — ablation studies
- `GRU-AE.ipynb` — GRU-based AutoEncoder baseline
- `SAS-AE.ipynb` — SAS-based AutoEncoder baseline
- `GRU4Rec.ipynb` — GRU4Rec baseline
- `SASRec.ipynb` — SASRec baseline
- `Isolationforest.ipynb` — Isolation Forest baseline
- `OCSVM.ipynb` — One-Class SVM baseline
- `markov.ipynb` — Markov baseline

> Note: The exact notebook roles may vary slightly depending on the paper version; please refer to the notebook headers and comments for experiment settings and parameters.

## Data Availability

The dataset used in the paper is **real-world data after anonymization/desensitization**.

- Due to privacy and compliance constraints, the dataset is **not publicly included** in this repository.
- If you need access to the data for research/verification purposes, **please contact the author**.

## How to Run

1. Open the notebooks with Jupyter Lab / Jupyter Notebook.
2. Run `featureprocessing.ipynb` first to generate processed features (if required by your pipeline).
3. Run the main method notebook(s) and baseline notebooks as needed:
   - Main method: `SeqRecon-AD-v2.ipynb` (and/or `SeqRecon-AD-S.ipynb`)
   - Baselines: `GRU-AE.ipynb`, `SAS-AE.ipynb`, `GRU4Rec.ipynb`, `SASRec.ipynb`, `Isolationforest.ipynb`, `OCSVM.ipynb`, `markov.ipynb`
4. Run `ablation.ipynb` for ablation experiments.

## Contact

For questions, bug reports, or data access requests, please contact the author.

