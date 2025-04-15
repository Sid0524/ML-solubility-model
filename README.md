# ML-solubility-model
Solubility Prediction using Machine Learning

This project uses the Delaney solubility dataset to train a machine learning model that predicts the aqueous solubility (logS) of chemical compounds based on molecular descriptors.

📂 Dataset
Source: Delaney Solubility Dataset

Format: CSV

Columns:

mol_logS: Experimental solubility value (target variable)

Molecular descriptors: A set of numerical features describing chemical properties of each molecule (e.g., MolWt, NumRotatableBonds, etc.)

🧠 Objective
To train a machine learning regression model that accurately predicts the mol_logS value based on the provided molecular descriptors.

🛠️ Tools & Libraries
Python

pandas

scikit-learn

numpy

matplotlib 

🧪 Workflow
Load and explore the dataset

Preprocess the data (handle missing values, scaling, etc.)

Split the data into training and testing sets

Train regression models (Linear Regression, Random Forest)

Evaluate performance using metrics like MAE, and R²
