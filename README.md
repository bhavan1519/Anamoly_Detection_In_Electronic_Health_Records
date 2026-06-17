# Anomaly Detection in Electronic Health Records

Project for detecting anomalies in electronic health records (EHR) using machine learning methods.

## Description

This repository contains a notebook and datasets used to explore and build anomaly detection models for EHR data. The primary workflow is implemented in `EHR_Anamoly_Detection.ipynb` which loads the preprocessed data, trains models, and produces output reports.

## Files
- `dataset.csv` - Raw dataset (source data).
- `preprocessed_dataset.csv` - Cleaned/preprocessed data used for modeling.
- `EHR_Anamoly_Detection.ipynb` - Main analysis notebook (exploration, feature engineering, modeling).
- `Outputs/feature_importance.csv` - Feature importance results.
- `Outputs/model_comparison.csv` - Model comparison metrics.

## Requirements

Install the usual data science packages (tested with Python 3.8+):

```
pip install -r requirements.txt
# or at minimum:
pip install pandas numpy scikit-learn matplotlib seaborn
```

If you prefer, create a virtual environment first.

## Usage

Open and run the notebook `EHR_Anamoly_Detection.ipynb` to reproduce the analysis and regenerate outputs in the `Outputs/` folder.

## Notes

- The notebook reads `preprocessed_dataset.csv`; ensure it exists in the project root.
- If you want a `requirements.txt`, tell me and I will generate one from the environment.

## License

Add a license if you plan to share this project publicly.
