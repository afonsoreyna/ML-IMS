Smith Parasite Predictive Model

Overview

This project develops a predictive model to identify individuals at higher risk of contracting the Smith Parasite, a newly discovered disease causing symptoms like fatigue and fever, with severe post-infection effects such as speech loss and confusion. The dataset includes 800 records with 18 features, including patient demographics, health metrics, and habits. We employ machine learning techniques to model disease prediction using various algorithms, concluding with a Random Forest classifier that achieved an F1 score of 1.0.

Dataset

	•	Training and test datasets: Contain information on patient health and characteristics.
	•	Target variable: Disease (0 - not infected, 1 - infected).
	•	Key features: Age, IMC (Body Mass Index), High Cholesterol, Mental Health, Physical Health, among others.

Methodology

Data Preprocessing

	•	Handling Missing Values: K-Nearest Neighbor (KNN) imputation.
	•	Outlier Treatment: Identified and corrected outliers using KNN imputation.
	•	Feature Creation: New variables such as age, IMC, and binary indicators for diabetes and weight status.

Feature Selection

	•	Applied methods like ANOVA, Chi-Square, Recursive Feature Elimination (RFE), and Mutual Information Coefficient (MIC) to select relevant features.

Model Development

	•	Algorithms: Evaluated models including Decision Trees, Random Forest, Gradient Boosting, and more.
	•	Hyperparameter Tuning: Employed Random Search followed by Grid Search for optimization.
	•	Final Model: Random Forest with an F1 score of 1.0 on Kaggle.

Results

The Random Forest model was selected due to its high consistency, minimal overfitting, and ability to accurately predict unseen data.

Conclusion

This project demonstrates the application of data processing, feature selection, and machine learning techniques to successfully predict disease outcomes, with Random Forest emerging as the best-performing model.
