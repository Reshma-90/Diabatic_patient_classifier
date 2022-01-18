# Diabatic_patient_classifier
## Goal of this project:
The goal of this model is to predict wheather a patient has diabates or not.
- The dataset contains almost 70k number of patient details consists of 20 attributes.
- The columns contains informations about
patient_nbr,race,gender,age,admission_type_id,discharge_disposition_id,admission_source_id,time_in_hospital,num_lab_procedures,	num_procedures,	num_medications,	number_outpatient,	number_emergency,	number_inpatient,	diag_1,	diag_2,	diag_3,	number_diagnoses,	change,	diabati

## EDA
- All preprocesseing steps like checking missing values,duplicate values,random error checking,outliers checking were performed and necessary steps taken.
- An Exploratory Data Analysis were performed on the dataset by doing univariate,bivariate and multivariate analysis.
- From EDA some insights were noted down.

## Data Splitting
The dataset were splitted into 70:30 ratio of 70% of data as train set and rest 30% as test set.

## Model bulding
A neural network classifier is build and hyperparameter tuning is performed to get better results.

## Performance Check:
The model performance is checked based on accuracy score,ROC-AUC score,confusion matrix,classification report.

## Result
The model predicts patients with 73% precision.The f1 score is 78%.
