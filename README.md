<img width="933" height="522" alt="image" src="https://github.com/user-attachments/assets/04e090bb-6304-4f6c-9499-041d91b18ab7" />


# 🩺 Breast Cancer Detection: Model Comparison and Performance Analysis

Breast cancer is not just a medical condition—it’s a deeply personal and emotional journey that affects millions of women and their loved ones around the world. Early detection can make the difference between life and loss. With the power of machine learning, this project aims to support early and accurate diagnosis of breast cancer through robust model development and evaluation.

---

## 📌 Objectives

- **Exploratory Data Analysis (EDA)**  
  Identify key features in the dataset and assess their correlation with the diagnosis.

- **Model Development**  
  Implement and compare machine learning models including:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - Support Vector Machine (SVM)
  - Neural Network (MLP)

- **Model Evaluation**  
  Use metrics like Accuracy, Precision, Recall, F1 Score, and ROC-AUC to evaluate model performance.

- **Clinical Recommendations**  
  Recommend models suitable for integration into early screening and diagnostic systems.

---

## 📊 Dataset Overview

- **Total Samples**: 569 patients  
- **Features**: 30 continuous numerical measurements  
- **Target Variable**: Diagnosis (`M = Malignant`, `B = Benign`)
- ![Dataset link](https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic)

Example features:
- `radius_mean`, `area_mean`, `smoothness_mean`, `compactness_mean`, `concavity_mean`, etc.

---

## 🔍 Feature Distributions & Insights

| Feature             | Benign Avg | Malignant Avg | Clinical Insight                                 |
|---------------------|------------|---------------|--------------------------------------------------|
| `radius_mean`       | 12.15      | 17.46         | Malignant tumors are generally larger.           |
| `area_mean`         | 462.79     | 978.38        | Malignant tumors occupy more area.               |
| `compactness_mean`  | 0.0801     | 0.1452        | Malignant tumors tend to be denser.              |
| `concavity_mean`    | 0.0461     | 0.1608        | Malignant tumors are more indented.              |
| `smoothness_mean`   | 0.0925     | 0.1029        | Malignant tumors are slightly less smooth.       |
| `symmetry_mean`     | 0.1742     | 0.1929        | Malignant tumors tend to be less symmetrical.    |

🧠 **Advice**: Regular self-examination and clinical screening are crucial—especially for lumps that are **large**, **dense**, or **irregular** in shape or texture.

---

## 🤖 Machine Learning Models

We trained and evaluated five models:

| Model                  | Validation Accuracy |
|------------------------|---------------------|
| Logistic Regression    | 94.51%              |
| Decision Tree          | 90.11%              |
| Random Forest          | 94.51%              |
| SVM                    | 93.41%              |
| Neural Network (MLP)   | **97.80%**          |

---

## ✅ Final Test Results

| Model                  | Accuracy | Precision | Recall | F1 Score |
|------------------------|----------|-----------|--------|----------|
| Logistic Regression    | 96.49%   | 95.35%    | 95.35% | 95.35%   |
| Decision Tree          | 95.61%   | 93.18%    | 95.35% | 94.25%   |
| Random Forest          | 95.61%   | 95.24%    | 93.02% | 94.11%   |
| SVM                    | 95.61%   | **97.50%**| 90.70% | 93.98%   |
| Neural Network (MLP)   | **97.37%**| 95.45%    | **97.67%** | **96.55%** |

---

## 🩺 Summary & Clinical Recommendations

### 🧠 Best Performing Model
- **Neural Network (MLP)**: Best overall performance — high accuracy, recall, and F1 score.

### 💬 Other Models
- **Logistic Regression**: Simple and interpretable.
- **SVM**: Highest precision — useful when false positives are critical.
- **Random Forest**: Well-balanced, slightly behind NN.
- **Decision Tree**: Interpretable, good for patient education.

---

## 🧪 Practical Applications

1. **AI-Assisted Screening**  
   Integrate high-performing models into hospital diagnostic systems to assist radiologists and improve early detection.

2. **Reducing False Negatives**  
   Prioritize recall to ensure that malignant tumors are not missed in screening.

3. **Patient Education & Awareness**  
   Use Decision Trees or visual tools to communicate risk clearly to non-technical audiences.

4. **Personalized Medicine**  
   Tailor screening frequency based on risk factors like size, compactness, and concavity.

---

## 📁 Project Structure
  Breast-Cancer-Detection/
│
├── breast_cancer_notebook.ipynb # Full analysis and modeling
├── requirements.txt # Required Python libraries
└── README.md # Project overview

---

## 🚀 Kaggle Notebook
![Breast Cancer Detection](https://www.kaggle.com/code/farahwalidelsayed/breast-cancer-detection/notebook)

# ⭐️ If you like this project, consider giving it a star!
