# Thyroid-Cancer-Risk

This project investigates machine learning approaches for thyroid cancer risk prediction, emphasizing data preprocessing, feature selection, dimensionality reduction, and comparative model evaluation.

The data was cleaned and preprocessed by handling missing values, encoding categorical features, and applying feature scaling to ensure consistency across inputs. To reduce dimensionality and improve model performance, Chi-square feature selection was applied to identify the most relevant features, followed by Principal Component Analysis (PCA) to capture the majority of variance with fewer components. Class imbalance was analyzed to better understand its impact on model performance.

Multiple machine learning models were implemented and compared, including Logistic Regression, Decision Tree, and Random Forest classifiers. A Linear Regression model was also included as a baseline for comparison. Model performance was evaluated using standard metrics such as Accuracy, ROC–AUC, and Confusion Matrices for classification, as well as Mean Squared Error (MSE) and R² for regression.

To improve model transparency, SHAP (SHapley Additive exPlanations) was used to interpret feature importance and explain individual model predictions, providing insights into the factors influencing thyroid cancer risk.
