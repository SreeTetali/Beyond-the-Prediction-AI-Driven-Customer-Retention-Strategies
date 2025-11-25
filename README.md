# Beyond-the-Prediction-AI-Driven-Customer-Retention-Strategies
Beyond the Prediction AI-Driven Customer Retention Strategies

### 📊 Project Overview
In the auto insurance industry, predicting churn is standard practice. Knowing *how* to prevent it is the competitive advantage.

This project moves beyond traditional "black box" prediction to build a prescriptive retention framework. By combining **XGBoost**, **Unsupervised Learning (K-Means)**, and **Explainable AI (SHAP)**, this system identifies distinct "Risk Personas" and maps them to hyper-personalized retention strategies.

### 🧠 Key Innovations
* **Engineered Behavioral Features:** Developed `Income_to_Premium_Ratio` and `Claim_Value_Ratio` to quantify financial stress.
* **Persona Discovery:** Used K-Means clustering to prove that "retirees" churn for completely different reasons than "affluent professionals."
* **Glass-Box Interpretability:** Applied SHAP (SHapley Additive exPlanations) to derive specific, actionable business levers for each persona.
* **GenAI Integration Concept:** Proposed an architecture for using LLMs to generate empathy-driven retention emails based on SHAP drivers.

### 🛠️ Technical Stack
* **Language:** Python 3.10
* **Modeling:** XGBoost, Scikit-Learn (Logistic Regression Benchmark)
* **Handling Imbalance:** SMOTE (Synthetic Minority Over-sampling Technique)
* **Explainability:** SHAP (TreeExplainer)
* **Visualization:** Matplotlib, Seaborn

### 📈 Results
The XGBoost model outperformed the Logistic Regression baseline significantly, capturing non-linear behavioral patterns.

| Model | ROC-AUC | Recall (Target Class) |
| :--- | :--- | :--- |
| **XGBoost (Champion)** | **0.9978** | **0.96** |
| Logistic Regression | 0.7994 | 0.72 |

### 🔍 Persona Insights
The analysis identified three distinct customer segments:
1.  **The Fixed-Income Retiree:** Retention driven by structural stability (`EmploymentStatus`).
2.  **The Affluent Shopper:** Retention driven by competitive offers (`OfferType`).
3.  **The High-Stress Vulnerable:** Retention driven by claim payouts (`Total Claim Amount`).

*(See the full PDF report in this repository for the detailed SHAP analysis plots)*

### 📄 Documentation
* [**Full Research Paper (PDF)**](./Beyond_the_Prediction.pdf) - Includes Methodology, Literature Review, and Strategic Discussion.
* [**Source Code (Jupyter Notebook)**](./Churn_Analysis_Notebook.ipynb)

---
*This project was completed as a Case Study in Machine Learning.*
