# 🧾 Banknote Authentication

## 📘 Overview
Banknotes are essential for a nation’s economy, and their authenticity plays a vital role in maintaining secure transactions. With the rise in counterfeit currency that closely resembles genuine notes, there's a growing need for a reliable authentication system. This project leverages machine learning algorithms to classify banknotes as **genuine or counterfeit** based on image-derived features.

---

## 🎯 Objective
Develop a classification model using machine learning to predict whether a given banknote is legitimate or counterfeit.

---

## 📊 Dataset
- **Source:** UCI Machine Learning Repository – [Banknote Authentication Data Set](https://archive.ics.uci.edu/ml/datasets/banknote+authentication)
- **Features:**
  - Variance of Wavelet Transformed image
  - Skewness
  - Kurtosis
  - Entropy
  - Class (0 = Fake, 1 = Genuine)
- **Extraction Method:** Wavelet Transform

---

## 🧠 Approach
- Preprocessed the dataset and visualized feature distribution.
- Applied and compared multiple classification models:
  - ✅ Decision Tree
  - ✅ K-Nearest Neighbors (KNN)
  - ✅ Support Vector Machine (SVM)
- Evaluated models using:
  - Accuracy
  - Precision
  - Recall
  - Confusion Matrix

---

## ⚙️ Technologies Used
- Python
- Jupyter Notebook
- Scikit-learn
- Pandas & NumPy
- Matplotlib & Seaborn (for visualization)

---

## ✅ Outcome
- Decision Tree model provided interpretable rules and solid accuracy.
- SVM and KNN delivered competitive results for comparison.
- The project confirms the **feasibility of using ML for currency authentication** based on statistical image features.

---
