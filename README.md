# Titanic Survival Prediction

Predict Titanic passenger survival using **Logistic Regression** and **Random Forest**.

---

## Dataset
- Kaggle Titanic dataset
- Target: `Survived` (0 = no, 1 = yes)
- Features: `Pclass`, `Sex`, `Age`, `SibSp`, `Parch`, `Fare`, `Embarked`

---

## Models

1. **Logistic Regression**
   - Simple baseline
   - Linear relationships
   - Accuracy: ~79%

2. **Random Forest**
   - Captures non-linear patterns
   - Feature importance:
     - Sex → most important (females survived more)
     - Fare, Age → moderately important
   - Accuracy: ~83%

---

## How to Run
1. Open the notebook `titanic-survival-prediction.ipynb` for Logistic Regression.
2. Open the notebook `random-forest-classifier.ipynb` for Random Forest.
3. Run all cells in Jupyter or Kaggle.
  

---

## Key Takeaway
Random Forest outperforms Logistic Regression and highlights the most important survival factors.
