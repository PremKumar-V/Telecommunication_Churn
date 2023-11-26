# Telecommunication_Churn
Prediction Project on Telecommunication Company Churn

## References
- [Dataset Link](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- [Sklearn Docs](https://scikit-learn.org/stable/modules/classes.html)

## Files
- [Original Dataset File](https://github.com/PremKumar-V/Telecommunication_Churn/blob/main/originalDataset.csv)
- [Preprocessed Dataset File](https://github.com/PremKumar-V/Telecommunication_Churn/blob/main/preprocessDataset.csv)
- [Saved Version of Random Forest Model](https://github.com/PremKumar-V/Telecommunication_Churn/blob/main/RandomForestClassifier.pkl)

## KeyPoints
- Dataset contain 20 columns, where 3 Numerical and 17 Categorical.
  - On Categorical 6 Binary Values, 9 Non Binary Values and 1 Object Value.
- Analysis
  - Gender is Appox Equal with points apart.
  - Count of Senior Citizen is low.
  - Chance of Senior Citizen having phone service is low as Internet Service too.
  - Most of the Internet is Fibre Optic.
  - Not everyone has Online Backup.
- While Preprocessing Consideration of No Phone Service and No Internet Service as NO is must.
- And also Consideration of Fibre Optic and DSL as YES.
- Random Forest Algorithm scored more than Support Vector Machines
