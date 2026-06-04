APEM — Setup and Running Instructions

This project runs entirely on Google Colab. No local installation required.

REQUIREMENTS
- Google Account (for Google Colab and Google Drive access)
- The CICIoT2023 preprocessed dataset CSVs placed in your Google Drive
  (see Dataset section below for the source link)

DATASET
CICIoT2023 — Canadian Institute for Cybersecurity, University of New Brunswick
https://www.unb.ca/cic/datasets/iotdataset-2023.html

HOW TO RUN
1. Open the notebook in Google Colab.
2. Mount your Google Drive when prompted.
3. Update BASE_PATH in the Configuration cell to match your Drive folder path.
4. If any library is missing, run in a cell:
   pip install -r requirements.txt
5. Run all cells in order.

NOTEBOOK ORDER
1. data-cleaning/        — Run first to preprocess and partition the dataset
2. model-setup/          — Run second for main FL, DP-FL, and APEM training
3. statistical-validation/ — Run last after training results are saved
