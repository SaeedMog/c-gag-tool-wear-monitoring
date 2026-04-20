# C-GAG: Conditional GAN Augmentation for Generalizable Tool Wear Monitoring

This repository contains the notebooks for my MEng project at the University of Guelph.

Goal: Improve tool-wear state classification under **data scarcity** and **class imbalance** by using a **Conditional GAN (C-GAN)** to generate class-conditioned synthetic samples and comparing performance against baseline ML/DL models.

## What’s included
- Feature engineering (time + frequency domain, incl. rFFT-based features)
- Two-stage feature selection / dimensionality reduction experiments
- Baseline ML models (Random Forest, SVM, Gaussian Process Classifier, GAN as a Classifier)
- Deep learning experiments (1D CNN / LSTM-style models)
- Conditional GAN (Generator/Discriminator) training and augmentation workflow
- Evaluation using common classification metrics (F1 / ROC-AUC / confusion matrix)

> Note: Datasets are **not included** in this public repository.

## Repository structure
- `notebooks/` — Jupyter notebooks (main experiments)
- `requirements.txt` — Python dependencies

## Notebooks
The project notebooks are stored in `notebooks/`:

- `material 1.ipynb` — Main pipeline and experiments for Material/Dataset 1
- `mat2 - part 1.ipynb` — Material/Dataset 2 experiments (part 1)
- `mat2_part2.ipynb` — Material/Dataset 2 experiments (part 2)
- `mat2_part3.ipynb` — Material/Dataset 2 experiments (part 3)

## How to run
### Option 1: Run locally
1. Create and activate a virtual environment
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
