# REPORT


Problem Statement:
Assume you are a loan risk officer at a large bank and you are tasked with determining whether a two-wheeler loan application will be accepted or rejected based on the data shared by the loan applicant and some additional data extracted about them from 3rd party sources.
Data Preprocessing:
  Missing value handling : Checked the dataset for missing values and treated them using appropriate methods (imputation or removal).
  Feature Selection: Conducted statistical tests (e.g., Chi-Square Test) to determine which features had a significant association with the target variable (Application Status).
  Encoding Categorical Features: Features such as Primary Asset and Asset Category contained categorical values. We applied label encoding to convert these into numerical representations.
  
Model Building:
  Logistic Regression: Chosen for its simplicity and interpretability in classification tasks.
  Random Forest: A robust ensemble learning method to handle potential non-linearity in the data.
  XGBoost: A gradient boosting algorithm known for handling imbalanced data and providing high accuracy.
  
Evaluation:
  Models were evaluated using metrics such as accuracy, precision, recall, and F1-score, focusing primarily on how well the models predict loan approval/rejection.
  The output of predictions was formatted to display as 'Approved' and 'Declined' instead of 0 and 1 for clarity in the final CSV output.
