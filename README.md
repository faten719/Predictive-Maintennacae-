 #Machine Failure Prediction (Predictive Maintenance) 📊
 
📝 Project Overview
This project focuses on the analysis and prediction of machine failure using industrial sensor data. The goal is to build a machine learning model capable of predicting when a machine is likely to fail, which is a critical application in industrial mechanical engineering (Predictive Maintenance).

📂 Dataset Information
The project uses the AI4I 2020 Predictive Maintenance Dataset.

Source: UCI Machine Learning Repository

- Key Features:

Air temperature [K]: Ambient temperature surrounding the machine.

Process temperature [K]: Internal temperature during machining.

Rotational speed [rpm]: Spindle speed.

Torque [Nm]: Applied torque.

Tool wear [min]: Accumulated wear time.

Target: Machine failure status (0 = No failure, 1 = Failure).

- 🛠️ Workflow
Data Exploration: Inspection of data structure, statistics, and missing values using pandas.

Preprocessing: Feature selection, numerical scaling with StandardScaler, and handling class imbalance.

Modeling: Comparison of multiple algorithms:
Machine Failure Prediction (Predictive Maintenance) 📊

-📝 Project Overview
This project focuses on the analysis and prediction of machine failure using industrial sensor data. The goal is to build a machine learning model capable of predicting when a machine is likely to fail, which is a critical application in industrial mechanical engineering (Predictive Maintenance).

📂 Dataset Information
The project uses the AI4I 2020 Predictive Maintenance Dataset.

Source: UCI Machine Learning Repository

Key Features:

Air temperature [K]: Ambient temperature surrounding the machine.

Process temperature [K]: Internal temperature during machining.

Rotational speed [rpm]: Spindle speed.

Torque [Nm]: Applied torque.

Tool wear [min]: Accumulated wear time.

Target: Machine failure status (0 = No failure, 1 = Failure).

🛠️ Workflow
Data Exploration: Inspection of data structure, statistics, and missing values using pandas.

Preprocessing: Feature selection, numerical scaling with StandardScaler, and handling class imbalance.

Modeling: Comparison of multiple algorithms:

Logistic Regression

Random Forest

XGBoost Classifier

Evaluation: Models were assessed based on Accuracy, Precision, Recall, and AUC.

🏆 Results
After comparing the algorithms, XGBoost achieved the highest performance:

Accuracy: ~96.5%

Strengths: Excellent precision (low false positives) and recall (low false negatives), effectively distinguishing between failure and non-failure classes.

🚀 How to Run
Clone the repository.

Install dependencies: pip install -r requirements.txt.

Open the notebook in notebooks/ to view the full analysis.
Logistic Regression

Random Forest

XGBoost Classifier

Evaluation: Models were assessed based on Accuracy, Precision, Recall, and AUC.

🏆 Results
After comparing the algorithms, XGBoost achieved the highest performance:

Accuracy: ~96.5%

Strengths: Excellent precision (low false positives) and recall (low false negatives), effectively distinguishing between failure and non-failure classes.

🚀 How to Run
Clone the repository.

Install dependencies: pip install -r requirements.txt.

Open the notebook in notebooks/ to view the full analysis.
