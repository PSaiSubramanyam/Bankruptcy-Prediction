# Bankruptcy-Prediction

Analyse the Dataset and Draw inference from it. Train & Evaluate ML Models to Perform Predictions.
EDA = 
>Check For Null  Values
      - Machine Learning Models can't handle null values.
      - We didn't find any null values in our dataset.
> Analyse Target Column
      - Our Target Column has 2 possible values bankruptcy or non-bankruptcy.
      - Our Dataset has 57.2% non-bankruptcy instances and 48.2% bankruptcy instances.
> Analyse Feature Column
      - Each of our feature column exhibit categorical nature. 
      - Possible values are 0 , 0.5 , 1 which represent low, medium and high respectively.
> Blue represent Non-Bankruptcy , Green represents Bankruptcy.
57.2% Non-Bankruptcy rows of data. 42.8% Bankruptcy rows of data.

Statistical Analysis
We Used Chi-Square Statistical Test to Check if our feature colums are significantly related to our target column.
We Used Chi-Square test because both out target column and feature columns are categorical.

Modeling 
We will use ML Packages like Scikit-learn, Catboost , Tensorflow to build Machine Learning Classification Models.
Models that we used are LogisticRegressor, LinearSVC, MultinomialNB, CategoricalNB, RandomForestClassifier, CatBoostClassifier, KNeighborsClassifier, DecisionTreeClassifier_gini, DecisionTreeClassifier_entropy.
We also used Dense Neural Network Model created using Tensorflow.

Deployment
For the Deployment we used Streamlit which provides us with simple easy to write script to create minimal web page. 
We Also Provided two ways in which user can provide information to the model for prediction.
One Way is providing individual values for each feature columns.
Another way is by providing a dataset in csv format which has feature columns as columns.









