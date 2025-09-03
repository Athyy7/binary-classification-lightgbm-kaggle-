# Kaggle Binary Classification Solution 🚀

This repository contains my approach and solution for a Kaggle binary classification competition.  
The goal is to predict a binary target variable (`0` or `1`) based on given tabular features.

---

## 📂 Project Structure
- `train.parquet` → Training dataset  
- `test.parquet` → Test dataset (without target)  
- `sample_submission.parquet` → Sample submission format  
- `notebook.ipynb` → Training, validation, and prediction pipeline  
- `submission (3).csv` → Final submission file  

---

## ⚙️ Approach
- Used **LightGBM** for classification.
- Applied **Stratified K-Fold cross-validation** for robust evaluation.
- Used **early stopping** to avoid overfitting.
- Final predictions thresholded at **0.5** to convert probabilities into class labels.
- Achieved strong performance with an OOF AUC of ~0.991.

---
## 📊 Results

- OOF AUC: 0.991

- Final submission produces a binary target column ready for Kaggle evaluation.
