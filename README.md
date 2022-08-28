# Loan_Default_Prediction
## Overview 

<img width="681" alt="Screen Shot 2022-08-26 at 8 38 52 PM" src="https://user-images.githubusercontent.com/102785000/187059383-bb0a2193-1b28-47a0-8cfb-89149a949588.png">

Lending is a vital tool that propels all enterprises and individuals worldwide to greater financial success. Many individuals utilize debt to buy a home or a vehicle. As the need for capital is rising, the loan defaults are also increasing. An organization wants to forcast who would default on their loans based on their demographic information. Various libraries and algorithms were used to build and evaluate the model using resampling including:

• OneHotEncoder & LabelEncoder

• scikit-learn

• SMOTE algorithm

• Random Forest Classifier

## Summary

### OneHotEncoder & LabelEncoder

As most machine learning models only deal with integer values, data preparation is a required process before moving on to modeling. We needed to encode the the categorical string values to be numerical.  

<img width="911" alt="encode" src="https://user-images.githubusercontent.com/102785000/187060503-b1f82962-32da-45f3-9952-4d8047ab2aab.png">


All features in integer format

<img width="1000" alt="numformat" src="https://user-images.githubusercontent.com/102785000/187060441-924f79b8-4d25-4d8c-9892-cb5df49bb0ae.png">

### Results:

<img width="943" alt="results" src="https://user-images.githubusercontent.com/102785000/187059439-03e9165d-e927-4292-b0f7-d2580c58a33e.png">

• Recall - how many of the Actual Positives the model captured

• Precision - how accurate the model of those predictec positive

• F1Score - takes both Recall & Precision into account

• Accuracy - percentage of all correctly classified observations

## Conclusion

The Random Forest approach is appropriate for classification and regression tasks on datasets with many entries and features that are likely to have missing values when we need a highly accurate result while avoiding overfitting.

