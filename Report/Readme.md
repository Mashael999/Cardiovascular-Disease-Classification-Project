# Cardiovascular Disease Classification


Mashael  Alfehaid - Hala Alanazi

__________

##### Design:
The goal of this project is to build machine learning models to classify or identify patient's condition on Cardiovascular Disease based medical examination for the patient.


### Data:
The dataset [Cardiovascular_Disease](https://www.kaggle.com/sulianova/cardiovascular-disease-dataset/code)
All of the dataset values were collected at the moment of medical examination, which consists of 13 features and 70,000 observations.

 
### Algorithms:
- Exploratory Data Analysis was done to the dataset.
- Building multple models and finding out the well-suited one for this specific dataset.

#### Cleaning:
- drop null values
- drop duplicate values
- Rename columns.
- convert [age] from days to years

#### Feature Engineering:
Bulied multiple of features:
- BMI measure of body fat based on height and weight and put it into category
- Ratio between systolic blood pressure and diastolic blood pressure
- Relationship of pressure with weight
- Put the age column into category
- Put blood pressure  columns into category

#### Model Building: 
Over 8 models were tried and played with to get the best model that goes hand in hand with the dataset. After performing simple train and validation on the  models one was chosen for further investigation. Models trained was:

- Logstic regression (Baseline)
- MLP Classifier
- knn 
- Decision Tree 
- Naive Bayes (GaussianNB)
- Random forest
- XGB Classifier
- Ensemble Methods (Max Voting, Average Voting, and Stacking Classifier)


The Best 3 Models:  XGB Classifier , Stacking Classifier and MLP Classifier

</br>
- Dealing with low accuracy by using featuers selection.
</br>
- Evaluating gridsearch for the best models

#### Tools:
- Numpy 
- Pandas 
- Matplotlib 
- Seaborn  
- Sklearn 
