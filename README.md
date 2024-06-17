# Presha-Monga_Datahack

Problem description: 

 Your goal is to predict how likely individuals are to receive their xyz and seasonal flu vaccines. Specifically, you'll be predicting two probabilities: one for xyz_vaccine and
one for seasonal_vaccine.


Solution : Implemented a predictive model to determine the likelihood of individuals receiving the `xyz` and `seasonal` flu vaccines using a dataset with various demographic and behavioral features. The approach involved handling missing values with imputation, scaling numerical features, and encoding categorical features. A `RandomForestClassifier` within a `MultiOutputClassifier` was chosen to manage the multilabel nature of the problem. The model was trained using a pipeline that streamlined preprocessing and prediction, achieving ROC AUC scores of 0.8642 for `xyz_vaccine` and 0.8571 for `seasonal_vaccine`, indicating strong predictive performance. The trained model was then used to predict probabilities on a test dataset, with results saved for submission.
