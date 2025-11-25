# Beyond the Prediction: Generative AI & XGBoost for Customer Retention
Beyond the Prediction: Generative AI & XGBoost for Customer Retention

### 🚀 Project Executive Summary
In the high-stakes auto insurance market, predicting churn is standard practice; preventing it is the competitive advantage. This project engineers a **Prescriptive Analytics Framework** that moves beyond "black box" prediction to actionable business strategy. Knowing *how* to prevent it is the competitive advantage.

By orchestrating **XGBoost** for precision modeling, **Unsupervised Learning (K-Means Clustering)** for behavioral segmentation, and **SHAP (Explainable AI)** for root-cause analysis, this system identifies distinct "Risk Personas." Crucially, it proposes a **Generative AI (LLM)** architecture to automate hyper-personalized, empathy-driven retention campaigns.

### 🧠 Key Technical Innovations
* **Generative AI & LLM Integration:** Designed a "Human-in-the-Loop" architecture where SHAP drivers serve as structured prompts for Large Language Models (LLMs) to generate personalized retention emails, bridging the gap between data science and customer experience.
* **Explainable AI (XAI) Compliance:** Utilized **SHAP (SHapley Additive exPlanations)** to provide local interpretability, ensuring model transparency and supporting regulatory auditing.
* **Behavioral Feature Engineering:** Developed novel financial stress metrics, including `Income_to_Premium_Ratio` and `Claim_Value_Ratio`, to quantify risk factors that standard demographic data misses.
* **Refined Segmentation:** Applied **K-Means Clustering** to differentiate the churn phenomenon into subgroups, proving that "Retirees" and "Affluent Professionals" churn for fundamentally different reasons.
* **Ethical AI & Bias Mitigation:** Conducted bias audits addressing protected groups (e.g., unemployed and disabled customers) to ensure **Responsible AI** deployment and fairness.

### 🛠️ Tech Stack & Skills
* **Machine Learning:** XGBoost (Gradient Boosting), Scikit-Learn (Logistic Regression Benchmark), SMOTE (Imbalanced Data Handling).
* **Data Engineering:** Feature Engineering (Financial Ratios), Log-Transformations, One-Hot Encoding.
* **AI Ethics:** Bias Detection, Model Interpretability, Regulatory Compliance (GDPR/Fair Lending context).
* **Visualization:** Matplotlib, Seaborn, PCA (Principal Component Analysis).
* **Language:** Python 3.10

### 📈 Performance Metrics
The Advanced XGBoost classifier demonstrated superior capacity to model non-linear consumer behaviors compared to the linear baseline, achieving near-perfect separation of the target class.

| Model | ROC-AUC | Recall (Target Class) | Precision |
| :--- | :--- | :--- | :--- |
| **XGBoost (Champion)** | **0.9978** | **0.96** | **0.94** |
| Logistic Regression | 0.7994 | 0.72 | 0.29 |

### 🔍 Persona Insights
The analysis identified three distinct customer segments, transforming generic churn predictions into targeted strategies:
1.  **The Fixed-Income Retiree:** Retention driven by structural stability (`EmploymentStatus`).
2.  **The Affluent Shopper:** Retention driven by competitive offers (`OfferType`).
3.  **The High-Stress Vulnerable:** Retention driven by claim payouts (`Total Claim Amount`).

### 🌐 Scalability & Industry Applications
While developed for Auto Insurance, this **Customer Lifecycle Management (CLM)** framework is industry-agnostic and highly scalable. It allows for direct transfer learning to other high-churn sectors:

* **Automotive Sales & Leasing:** Predicting lease-end turnover and targeting drivers with personalized upgrade offers based on equity positions.
* **SaaS & Subscription Economy:** Identifying "at-risk" users based on engagement decay rather than demographics.
* **Fintech & Banking:** Detecting silent attrition in credit card portfolios before the customer closes the account.
* **Healthcare:** Modeling patient adherence to treatment plans (churning from medication) using behavioral personas.

### 📄 Documentation
* [**Full Research Paper (PDF)**](./Beyond_the_Prediction.pdf) - Includes Methodology, Literature Review, and Strategic Discussion.
* [**Source Code (Google Colab notebookk)**](./CaseStudiesInML_CustomerRetention.ipynb)

---
*This project was completed as a Case Study in Machine Learning.*
