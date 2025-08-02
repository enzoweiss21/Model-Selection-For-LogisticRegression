🏡 Model Selection for Logistic Regression – Airbnb Superhost Classification
🔍 Project Overview
This project demonstrates the evaluation and model selection phase of the machine learning lifecycle, focusing on optimizing a logistic regression classifier to predict whether an Airbnb host is a superhost based on listing attributes.

🎯 Objectives and Goals
Build and prepare a cleaned dataset for classification

Train and evaluate a logistic regression model

Perform hyperparameter tuning (grid search for C)

Compare models using ROC and precision-recall curves

Implement basic feature selection

Persist the trained model for future use

🧠 Methodology
Dataset: airbnbData_train.csv (preprocessed with one-hot encoding, scaling, and imputation)

Label: superhost status (binary classification)

Features: Various listing attributes from Airbnb NYC data

Models Used:

Logistic Regression (baseline)

Logistic Regression with optimized hyperparameters (C)

Evaluation:

Accuracy, precision, recall, F1-score

ROC curve, AUC

Precision-Recall curve

Feature Selection: Based on model coefficients

📊 Results & Key Findings
Hyperparameter tuning improved model performance over the baseline logistic regression

Visual tools like ROC and precision-recall curves helped interpret tradeoffs between precision and recall

Feature selection reduced model complexity without significant performance loss

📈 Visualizations
Precision-recall curves comparing tuned vs. untuned models

ROC curves and AUC metrics

Bar plots of feature importances (coefficients)

🚀 Getting Started
🔧 Installation & Setup
Clone the repo:

bash
Copy
Edit
git clone https://github.com/enzoweiss21/Model-Selection-For-LogisticRegression.git
cd Model-Selection-For-LogisticRegression
Create a virtual environment and install dependencies:

bash
Copy
Edit
python3 -m venv venv
source venv/bin/activate  # on Windows use: venv\Scripts\activate
pip install -r requirements.txt
🧪 Run the Project
✅ Steps to Train & Evaluate:
Launch Jupyter Notebook:

bash
Copy
Edit
jupyter notebook ModelSelectionForLogisticRegression.ipynb
Run each section to:

Load the dataset

Train baseline and optimized models

Visualize evaluation metrics

Persist the final model

🔄 Potential Next Steps
Compare logistic regression with other models (e.g., Random Forest, XGBoost)

Perform cross-validation for more robust evaluation

Apply SHAP or LIME for more advanced model interpretability

👥 Individual Contributions
Enzo Weiss – Data processing, model development, hyperparameter tuning, evaluation, and reporting

📘 Documentation
All code is fully documented within the notebook

Outputs and evaluations are clearly marked and explained step by step

Final model saved for deployment or reuse

