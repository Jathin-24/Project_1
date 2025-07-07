# Predicting Customer Insurance Purchases

**Author:** Jathin Lalith. D  
**Date:** 29 June 2025

---

## Project Overview

This project predicts whether a customer will purchase insurance based on their age and estimated salary. Multiple classification algorithms are implemented and compared, including:

- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Support Vector Machine (SVM)  
- Decision Tree  
- Random Forest  

The goal is to find the best-performing model for accurate predictions.

---

## Dataset

- Source: [Social Network Ads Dataset](https://drive.google.com/file/d/1wOrVrq30W3bl1st4cvnt5bvn5UWEK4Ab/view?usp=drive_link)  
- Features: Age, Estimated Salary  
- Target: Purchased (0 = No, 1 = Yes)

---

## Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/Jathin-24/Project_1
cd Project_1
pip install numpy pandas scikit-learn matplotlib
````

---

## Usage

Run the Python script or Jupyter notebooks to train and evaluate models:

```bash
python main.py
```

Or open the `.ipynb` files in Jupyter Notebook to explore individual models.

---

## Results Summary

| Algorithm              | Accuracy (%) | Precision | Recall | F1-Score |
| ---------------------- | ------------ | --------- | ------ | -------- |
| Logistic Regression    | 89           | 0.89      | 0.75   | 0.81     |
| K-Nearest Neighbors    | 93           | 0.88      | 0.91   | 0.89     |
| Support Vector Machine | 90           | 0.92      | 0.75   | 0.83     |
| Decision Tree          | 91           | 0.83      | 0.91   | 0.87     |
| Random Forest          | 91           | 0.85      | 0.88   | 0.86     |

KNN showed the best accuracy (93%), while Decision Tree and Random Forest performed closely behind.

---

## Future Improvements

* Include additional features such as past purchase history and health details.
* Use cross-validation for more robust evaluation.
* Explore deep learning models for improved performance on larger datasets.

---

## Packages Required

* numpy
* pandas
* scikit-learn
* matplotlib

Install with:

```bash
pip install numpy pandas scikit-learn matplotlib
```

---

## References

* [Scikit-learn Documentation](https://scikit-learn.org/stable/documentation.html)
* Pedregosa et al., 2011. Scikit-learn: Machine learning in Python. *Journal of Machine Learning Research*, 12, 2825-2830.

---
