# Loan-risk-assessment-
Credit Risk Prediction — Probability of Default (PD) Model

Goal:
Developed and deployed a high-performance Machine Learning model to forecast the Probability of Default (PD) on a consumer credit portfolio, with the objective of enabling loss mitigation and risk-based pricing.

Key Achievements:
	•	Model Performance: Achieved an AUC-ROC score of 0.9637 using an XGBoost Classifier, effectively addressing an 80/20 class imbalance via the scale_pos_weight hyperparameter to optimize model fairness and recall for minority (default) cases.
	•	MLOps Pipeline: Designed and serialized a robust scikit-learn pipeline to automate data preparation, featuring median imputation for numerical features (DEBTINC, MORTDUE) and constant imputation for categorical variables (JOB, REASON).
	•	Feature Engineering: Engineered ratio-based features such as Debt-to-Income (DTI) and Loan-to-Value (LTV) to enhance model explainability and predictive accuracy.
	•	Data Visualization: Built an interactive Tableau dashboard to present business insights, including:
	•	A Risk Heatmap highlighting high-default segments by JOB and REASON.
	•	A Box Plot showing that higher Debt-to-Income ratios are significantly correlated with default probability.
	•	Impact: Enabled stakeholders to identify high-risk borrower groups and make informed credit approval and pricing decisions, improving portfolio stability.
