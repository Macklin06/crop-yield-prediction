
# Yield Prediction using Random Forest Regressor

This project uses a Random Forest Regressor model to predict yield based on various features given. It aims to build a strong baseline model with efficient preprocessing, evaluation, and final submission generation.

---

## Dataset

- **Source:** [https://www.kaggle.com/competitions/ml-league-supervised-learning-competition](https://www.kaggle.com/competitions/ml-league-supervised-learning-competition)

- **Files:**
  - `train.csv`: Training dataset
  - `test.csv`: Test dataset
  - `sample_submission.csv`: Format for submission

---

## ⚙️ How to Run

### Option 1: Google Colab
1. Open this notebook in [Google Colab](https://colab.research.google.com/)
2. Upload the dataset files (`train.csv`, `test.csv`, `sample_submission.csv`)
3. Run all cells sequentially
4. Download the final `random_forest_submission.csv` from the submission folder

### Option 2: Local Setup

#### 🔧 Requirements
Install dependencies using:
```bash
pip install -r requirements.txt
```

#### 🧪 Run the Notebook
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
│   └── yield_prediction_random_forest.ipynb
│
│
├── submission/
│   └── random_forest_submission.csv
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## ✍️ Author

Macklin Chriss Miranda

---
