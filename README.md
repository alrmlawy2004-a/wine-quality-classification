# Wine Quality Classification

I compare linear SVM configurations and XGBoost for binary wine-quality classification.

## Run

Use a Python virtual environment. Install `pip install -r requirements.txt`, launch `jupyter notebook`, and open `wine-quality.ipynb`. Run cells from top to bottom. Place winequality-red.csv and winequality-white.csv in data/.

## Scope and limitations

Training-only scaling and score-based ROC-AUC are used. A large-C SVM approximates a hard-margin configuration. Evaluation uses one holdout; external data is required.

## Dataset

[Wine Quality — UCI](https://archive.ics.uci.edu/dataset/186/wine+quality). Cortez et al., DOI: 10.24432/C56S3T.
