# AutoML_Application
# AutoML Web Platform for Automated Machine Learning — Personal Project
Tech Stack: Python, Streamlit, Scikit-learn, XGBoost, SHAP, LIME, Pandas, NumPy, RandomizedSearchCV, SMOTE
- Developed a no-code AutoML application that enables users to upload CSV/Excel datasets and automatically train ML models without programming knowledge.
- Implemented automatic problem type detection (classification vs regression) using target variable analysis.
- Built an automated preprocessing pipeline for duplicate handling, missing values, categorical encoding, outlier capping, scaling, and feature selection.
- Evaluated multiple models (Logistic Regression, SVM, KNN, Random Forest, XGBoost, etc.) and automatically selected the best model using performance metrics (ROC-AUC / R²).
- Performed hyper-parameter tuning (RandomizedSearchCV) on top-2 models for accuracy improvement.
- Integrated Explainable AI using SHAP for tree models and LIME for linear & non-tree models, providing transparency into predictions.
- Created interactive UI to enter input values dynamically and generate prediction results & probability scores, with downloadable prediction logs.
- Deployed using Streamlit + Ngrok/Streamlit Cloud for real-time user access.
<img width="1894" height="866" alt="Screenshot 2025-12-27 183821" src="https://github.com/user-attachments/assets/649e80e1-fd33-4716-836d-5f9a54c766e4" />
