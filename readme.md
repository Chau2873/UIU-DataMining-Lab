# 📚 UIU Data Mining Lab

This repository contains all the **Data Mining lab exercises** and examples for **UIU Data Mining Course**.
It demonstrates fundamental **data mining concepts, preprocessing techniques, visualization, and machine learning models** with hands-on Python examples.

---

## **Prerequisites**

Before running the code, ensure you have:

- **Python 3.x** installed
- Python libraries:

  - `numpy` → Numerical operations
  - `pandas` → Handling tabular data
  - `matplotlib` → Data visualization
  - `scikit-learn` → Machine learning models

Install missing libraries with:

```bash
pip install numpy pandas matplotlib scikit-learn
```

---

## **Repository Structure**

```
UIU-DataMining-Lab/
│
├─ README.md
├─ Social_Network_Ads.csv
├─ social_network_ads.csv
├─ tennis.csv
├─ Data1.csv
├─ DM-Code.ipynb          # all code here in one file
```

---

## **Key Concepts in this Lab**

- **Data preprocessing**: Handling data before applying ML

  - Selecting features
  - Scaling values for consistent range

- **Slicing & indexing** in pandas and numpy
- **Train/Test split** to avoid overfitting
- **Random_state** → Ensures reproducible splits
- **Logistic Regression** → Binary classification
- **Model evaluation** → Confusion matrix, classification metrics

---

## **Other Labs (Coming / Covered)**

- **Missing Values Handling** → Fill with mean/median/mode
- **Noise Removal** → Detecting and cleaning noisy data
- **Clustering & K-Means** → Grouping data without labels
- **Decision Trees & Regression** → Predicting outcomes
- **Ensemble Learning & Random Forest** → Combining multiple models
- **Cross-Validation** → Stratified K-Fold to avoid bias

---

## **How to Run**

1. Clone this repository:

```bash
git clone https://github.com/TashinParvez/UIU-DataMining-Lab.git
cd UIU-DataMining-Lab
```

2. Place datasets in the folder (if not already present).
3. Run the Python script:

```bash
python social_network_ads.py
```

4. Observe plots and console outputs for model evaluation.

---

## **Notes**

- Always **set `random_state`** for reproducible train/test splits.
- Use **feature scaling** for models like Logistic Regression and SVM.
- Visualizations help understand relationships in the dataset before modeling.
- This repo serves as a **reference and study guide** for UIU Data Mining exams and labs.



Note: All original code and datasets were provided by the course faculty. The scripts in this repository include my modifications, experiments, and enhancements for learning purposes.

