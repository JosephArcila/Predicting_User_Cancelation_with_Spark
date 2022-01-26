# Predicting Users Who Canceled Their Service with Spark
This repository contains Data manipulation with Spark to engineer relevant features for predicting which users will cancel their music streaming service.

## Instalations needed to run the code  

- Python 3
- Pandas
- NumPy
- Matplotlib 3
- Seaborn
- PySpark

## Files

### Predicting-Churn-Users.ipynb
This notebook contains the code used for the entire exploratory analysis process and the ML model selection and tunning.

## Data

Every time the user interacts with the service it generates data that contains the key insights for keeping users happy and helping the business thrive.

<img src="https://user-images.githubusercontent.com/39535338/150736648-662d5f55-bd98-4613-b9ae-c9721b352e4e.PNG" alt="data" width="800"/>

## Exploratory Data Analysis
<img src="https://user-images.githubusercontent.com/39535338/150975285-577a7241-ab15-4e34-8650-263f3a4dcc7d.PNG" alt="drawing" width="400"/>  
<img src="https://user-images.githubusercontent.com/39535338/150975321-02700802-f1db-4868-acaa-00d3066fd061.PNG" alt="drawing" width="400"/>  

## Modeling Process
For fitting the data, I tried a RandomForestClassifier, DecisionTreeClassifier, and LogisticRegression. I prioritized the model that performed best at the f1 score since the dataset is imbalanced (Few Churned users).
The best model was a RandomForestClassifier tunned with various hyperparameters and features.

## Model Results
<img src="https://user-images.githubusercontent.com/39535338/151083554-4c855954-fd1c-45c4-8e73-008da977ee70.PNG" alt="drawing" width="300"/>  
<img src="https://user-images.githubusercontent.com/39535338/151083622-925aead9-b292-4182-94ed-5d7153593c66.PNG" alt="drawing" width="300"/>  
