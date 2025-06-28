
# Yield Prediction using XGBoost and Optuna

This project uses an **XGBoost Regressor** model with **Optuna** hyperparameter tuning to predict crop yield based on the given features.  
It aims to build an accurate model using cross-validation and optimization techniques.

---

##  Dataset

**Source**: [Kaggle Competition — ML League Supervised Learning](https://www.kaggle.com/competitions/ml-league-supervised-learning-competition)

**Files:**
- `train.csv`: Training dataset
- `test.csv`: Test dataset
- `sample_submission.csv`: Sample format for submission

---

## ⚙ How to Run

### Option 1: Google Colab
1. Open the notebook in **Google Colab**
2. Upload the dataset files (`train.csv`, `test.csv`, `sample_submission.csv`)
3. Run all cells sequentially
4. Download `submission.csv` after predictions are made

### Option 2: Local Setup

####  Requirements
Install required dependencies:
```bash
pip install pandas xgboost scikit-learn optuna
pip install -r requirements.txt
```

####  Run the Notebook
Open and run the notebook using:
```bash
jupyter notebook notebooks/yield_prediction.ipynb
```
__pycache__/
*.pkl
.DS_Store
*.ipynb_checkpoints

---

## 📁 Project Structure

```
yield-prediction/
│
├── data/
│   ├── train.csv
│   ├── test.csv
│   └── sample_submission.csv
│
├── notebooks/
│   └── yield_prediction.ipynb
│
│
├── submission/
│   └── submission.csv
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## ✍️ Author

Macklin Chriss Miranda

---
