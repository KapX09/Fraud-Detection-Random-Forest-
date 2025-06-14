# Fraud-Detection
## Random forest implementation
A fraud detection model using Machine learning algorithm Random forest

### Insurance Fraud Detection using Machine Learning
This project applies machine learning techniques to detect fraudulent insurance claims. The goal is to classify whether a claim is fraudulent based on various policyholder, policy, and transaction attributes.

#### Work_flow
- Loaded and cleaned the dataset (`Fraud data.csv`)
- Preprocessed features, including handling dates, encoding categorical variables, and filling missing values
- Selected relevant features for model training
- Trained a Random Forest Classifier to detect fraud
- Evaluated model performance using accuracy and classification reports
- Visualized feature importance to understand key fraud indicators

#### Using
- **Random Forest Classifier** from `scikit-learn`
This model was chosen for its effectiveness with tabular data and its ability to provide insights via feature importance.
#### Features:
Some of the most important features in detecting fraud include:
- `Premium`
- `Annual Income`
- `STATUS`
- `POLICY_SUMASSURED`
- `SUB_STATUS`
- `ASSURED_AGE`

#### P.S.
- The dataset is assumed to be proprietary or course-specific, named `Fraud data.csv`, and not included in this repository.
- If you'd like to run this notebook, you'll need a dataset with similar structure and feature names.
---

*This is an educational project and not intended for production use without further testing and validation.*
