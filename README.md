# Adaptive Privacy Enhancement Mechanism (APEM)

A lightweight, rule-based adaptive differential privacy mechanism for 
Differentially Private Federated Learning (DP-FL) applied to IoT botnet 
detection using the CICIoT2023 dataset.

## Repository Structure

- `data-cleaning/` — Preprocessing notebooks for the CICIoT2023 dataset 
  (feature selection, normalization, IID and non-IID partitioning)
- `model-setup/` — Main training notebooks for FL, Static DP-FL, and APEM 
  across 10 independent seeded runs under IID and non-IID conditions
- `statistical-validation/` — Paired t-tests and statistical significance 
  analysis across all evaluation metrics
- `Installer/` — Setup instructions and requirements for running the notebooks

## Requirements

Run on Google Colab. See `Installer/README.txt` for setup instructions.

## Dataset

CICIoT2023 — Canadian Institute for Cybersecurity, University of New Brunswick  
https://www.unb.ca/cic/datasets/iotdataset-2023.html
