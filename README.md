# Disaster Response Pipeline Project
The tools you use, and the way you approach learning can have a significant correlation with how much you get paid for your work as a data scientist.

## Instalations needed to run the code  

- Python 3
- Pandas
- NumPy
- Matplotlib 3
- Seaborn
- Spark

## Summary
Manipulated large datasets with Spark to engineer relevant features for prediting users who canceled their music streaming service

## Files

### Sparkify
This notebook contains the code used for the entire exploratory analysis process and the ML model selection and tunning.


## Data

Every time the user interacts with the service it generates data that contains the key insights for keeping users happy and helping the business thrive.

<img src="https://user-images.githubusercontent.com/39535338/150736648-662d5f55-bd98-4613-b9ae-c9721b352e4e.PNG" alt="data" width="800"/>


## Modeling Process
For fitting the data, I tried a RandomForestClassifier, DecisionTreeClassifier, LogisticRegression, and GradientBoosting. I prioritized the model that performed best at the f1 score since the dataset is imbalanced (Few Churned users).
The best model was a RandomForestClassifier tunned with various hyperparameters and features.

## Exploratory Data Analysis


<img src="https://user-images.githubusercontent.com/39535338/150737106-20480895-0324-4f06-84d1-edab4868752e.png" alt="drawing" width="800"/>  
<img src="https://user-images.githubusercontent.com/39535338/150737162-216442b6-3343-4e5c-9e93-a00d3315074c.png" alt="drawing" width="800"/>  
