# 🫀 Heart Disease Risk Prediction Using Hybrid CNN with QPSO and XAI

> Enhancing Accuracy and Interpretability for Early Detection of Cardiovascular Disease

---

## 📌 Overview

Cardiovascular diseases (CVDs) are responsible for **32% of global deaths**. Early and accurate prediction can significantly reduce mortality. However, most existing models are **black-box systems** that lack transparency and are hard for clinicians to trust.

This project proposes a **Hybrid Deep Learning System** that combines:
- 🔬 **CNN** — for powerful feature extraction from tabular health data
- ⚡ **QPSO (Quantum Particle Swarm Optimization)** — for automated hyperparameter tuning
- 🧠 **SHAP & LIME (Explainable AI)** — to make predictions transparent and interpretable for medical professionals

---

## 🎯 Objectives

- Develop a Hybrid CNN model for heart disease risk prediction
- Apply QPSO to optimize CNN hyperparameters automatically
- Integrate SHAP and LIME for explainability
- Provide interpretable insights to assist clinical decision-making

---

## 🗂️ Dataset

- **Dataset:** UCI Cleveland Heart Disease Dataset
- **Features:** 13 clinical features including age, sex, chest pain type, cholesterol, blood pressure, etc.
- **Target:** Binary classification — Heart Disease Present / Absent

---

## 🏗️ System Architecture

```
Raw Data (Cleveland Dataset)
        ↓
Data Preprocessing & Feature Engineering
        ↓
Hybrid CNN Model (Embedding + Conv1D + Dense)
        ↓
QPSO Hyperparameter Optimization
        ↓
Final Trained Model
        ↓
Evaluation (Accuracy, ROC-AUC, Confusion Matrix)
        ↓
SHAP & LIME Explainability
```

---

## ⚙️ Technologies Used

| Category | Tools |
|----------|-------|
| Language | Python 3 |
| Deep Learning | TensorFlow, Keras |
| Optimization | QPSO (Custom Implementation) |
| Explainability | SHAP, LIME |
| Data Processing | Pandas, NumPy, Scikit-learn |
| Visualization | Matplotlib, Seaborn |
| Imbalance Handling | imbalanced-learn |

---

## 📊 Results

| Metric | Score |
|--------|-------|
| Accuracy | ~83% |
| ROC-AUC | Evaluated |
| Precision | Weighted |
| Recall | Weighted |
| F1-Score | Weighted |

> SHAP analysis revealed key risk factors: **oldpeak**, **thalach**, and **ca** as the most influential features.

---

## 🔍 Explainability

- **SHAP** — Global feature importance showing which features most influence predictions across all patients
- **LIME** — Local explanations for individual patient predictions, helping doctors understand specific cases

---

## 🚀 How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/raji1977/Heart-Disease-Risk-Prediction-CNN-QPSO-XAI.git
cd Heart-Disease-Risk-Prediction-CNN-QPSO-XAI
```

### 2. Install Dependencies
```bash
pip install numpy pandas scikit-learn tensorflow imbalanced-learn shap lime seaborn matplotlib
```

### 3. Run the Notebook
```bash
jupyter notebook Final_project.ipynb
```

---

## 👩‍💻 Authors

- **V. Rajya Lakshmi** (22KN1A6157)
- **K. Jayasri** (22KN1A6135)
- **G. Krishna Balaram** (22KN1A6132)
- **I. Gopinath** (22KN1A6163)

**Guide:** Dr. P. Rajendra Kumar, Professor & HOD, Dept. of AI&ML  
**Institution:** NRI Institute of Technology, Vijayawada

---

## 📄 Research Paper

This project is accompanied by a research paper currently being prepared for submission to an international journal/conference.

---

## 🙏 Acknowledgements

We express our sincere gratitude to **Dr. P. Rajendra Kumar Sir** for his continuous guidance and support throughout this project, and to **NRI Institute of Technology** for providing the resources and opportunity to undertake this research.

---

## 📬 Contact

For any queries, feel free to reach out via GitHub or LinkedIn.

> ⭐ If you found this project helpful, please consider giving it a star!
