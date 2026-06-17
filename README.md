# EHR Anomaly Detection

This project demonstrates anomaly detection in electronic health record (EHR) access logs using Python and machine learning.

## Contents

- `EHR_Anamoly_Detection.ipynb` - Jupyter notebook with the full analysis and modeling pipeline.
- `dataset.csv` - Synthetic dataset used for model training and evaluation.

## Project Overview

The notebook performs:

1. Library installation and imports
2. Dataset loading and basic cleaning
3. Column normalization and target identification
4. Binary encoding of sensitive access fields
5. Feature engineering for session behavior, access counts, and login patterns
6. Numeric encoding, scaling, and train/test splitting
7. Model training and comparison using:
   - Isolation Forest
   - Random Forest
   - XGBoost
   - Autoencoder
8. Evaluation with accuracy, precision, recall, F1 score, and confusion matrices
9. Model comparison reporting and visualization of results
10. Feature importance analysis

## Requirements

The notebook installs the following Python libraries:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `xgboost`
- `tensorflow`

## Usage

1. Open `EHR_Anamoly_Detection.ipynb` in a Jupyter environment or Google Colab.
2. Upload `dataset.csv` when prompted.
3. Run the notebook cells sequentially to process the data, train models, and generate results.

## Notes

- The notebook is configured for interactive use and includes Google Colab integration for file upload/download.
- It uses a target label mapping for anomaly labels such as `normal` and `suspicious`.
- The dataset is expected to contain EHR access event features such as login counts, session duration, access counts, and sensitive record access indicators.

## Output Files

The notebook saves several outputs when executed:

- `preprocessed_dataset.csv`
- `all_model_comparison.csv`
- `all_model_comparison.png`
- `feature_importance.csv`
- `feature_importance_graph.png`
