# Large_loss_insurance_claims_prediction
This is a summer research project with an insurance claim dataset
# Dataset:
- response variable: large loss or non-large loss
- binary classification
# Objectives: 
- Which an insurance claim due to the car accident will result in large loss for the insurance company before the accident actually happens?
- What significant features have strong impact on the insurance loss?
- What types of insurance policies customers bought cause the large loss?
# Workflow:
- Data Exploration
- Data Cleaning: Duplicates, missing observations,etc.
- Feature Engineering: Timestamp, drop irrelevant features, One-hot encoding, sparse features, etc.
- Exploratory Data Analysis
- Feature Selection
- Modeling: Random Forest & XGBoost
- Modeling tuning: resample imbalanced dataset & Grid Search for best parameters
- Model Evaluation: AUC score & ROC Curve
# Insights:
- critical features that most contribute to insurance loss
- Bulit optimized classification models to predict whether a future insurance claim will lead to large insurance coverage


