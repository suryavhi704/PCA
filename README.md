# 🏀 Principal Component Analysis (PCA) on Basketball Player Data

This repository contains a hands-on implementation of **Principal Component Analysis (PCA)** as part of a session conducted by **Intellipaat**. The project focuses on dimensionality reduction and performance comparison using a dataset of basketball players.

## 🔍 Project Overview

In this project, I explored the effectiveness of PCA in simplifying high-dimensional data while retaining the most important information. The dataset comprises various performance metrics of basketball players, and the goal is to use this data to predict an outcome using **Logistic Regression** — once with PCA applied and once without.

## ✅ What I Learned

- 📊 **Data Preprocessing**  
  Cleaned and prepared the dataset for analysis, including handling missing values and scaling features.

- 🧮 **Mean Centering**  
  Centralized the data around the mean to ensure that PCA effectively captures variance.

- 📉 **Principal Component Analysis (PCA)**  
  Applied PCA to reduce the dimensionality of the dataset while maintaining the core information.

- 🤖 **Model Building with Logistic Regression**  
  Built and evaluated two logistic regression models:
  - One using the original feature set.
  - One using PCA-transformed features.

## 📈 Key Findings

- **PCA-enhanced data outperformed the raw dataset in prediction accuracy.**  
  The PCA model captured the essential structure of the data more effectively, enabling better classification results.

- **Dimensionality reduction not only improved performance but also enhanced model interpretability and reduced training time.**

## 🧪 Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib / Seaborn (for visualization)

## 🚀 How to Run

```bash
git clone (https://github.com/suryavhi704/PCA).git
cd pca-basketball-analysis
pip install -r requirements.txt
python pca_logistic_regression.py
```

## 📌 Conclusion

This project showcases the practical application of PCA in improving model performance and simplifying complex datasets. It's a great example of how dimensionality reduction techniques can elevate traditional machine learning workflows.
