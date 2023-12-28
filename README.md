# Acute Kidney Injury (AKI) Prediction Model Based on Patients Clinical Data

In this mini project supervised by Dr. Uri Shalit and Rom Gutman, I delve into patient data sourced from Rambam Medical Center spanning 2004 to 2021.
The dataset focuses on patients diagnosed with acute heart failure (AHF), adhering to the European Society of Cardiology criteria. This dataset encompasses a comprehensive array of information, including lab tests,
physical measurements, medication records, demographic details, and administrative data.


The primary goal was to predict the onset of Acute Kidney Injury (AKI) within the first 24 hours of admission.
Predicting AKI early on is pivotal as it aids in identifying eligible candidates for a trial intervention.
Understanding the possibility of AKI development is a critical aspect for potential intervention planning.
To identify AKI, there are four criteria options provided: a serum creatinine increase of at least 0.3 mg/dl, 0.5 mg/dl, 120%, or 150% concerning admission levels.

Within this repository, you will find:

* Data Processing (data_processing): data cleaning and preprocessing steps.
  Including data tagging - patients were specifically tagged based on criteria indicative of AKI during data processing.
* Feature Engineering (feature_engineering.ipynb): new features were built based on raw data insights.
* Model Development (run_model.ipynb): Following the integration of all data sets, imputations and normalization procedures were executed.
  Subsequently, various models (XGBoost, Random-Forest, Logistic Regression-l1) were created to predict AKI using the initial 24-hour data.
* Performance Comparison (run_model.ipynb): Evaluation metrics and comparisons between different models developed to determine the most effective approach for AKI prediction (ROC-AUC, precision, recall, NPV, netbenefit and calibration).
