# Classify patient's condition on Cardiovascular Disease
The goal of this project is to build machine learning models to classify or identify patient's condition on Cardiovascular Disease based medical examination for the patient.

## Data Cleaning:

- Check duplicates.
- Check null.
- Drop column.
- Rename columns.
- convert [age] from days to years
- Remove outlire
After cleaning the data set the remain rows are 61296.

## Data Exploration:

![balanced](https://user-images.githubusercontent.com/93076337/146259064-6a614b5a-d643-470f-90f2-f48b568f8f1e.png)

After we exploration our data, we noticed that our data is balanced.


![age](https://user-images.githubusercontent.com/93076337/146259594-9d3737ce-618a-4522-b6dc-a84613046f8b.png)

Also, we noticed that we when ever the age of the patients increase the number of the patients also increased, this is mean that the age is a important vector in Cardiovascular disease . 


## Modeling:

*Beasline model*
|    Model      | Training score| Validation score |
| ------------- | ------------- | ---------------- |
| LogisticRegression | 0.7094   | 0.6933           |
 
*Models after removing the outliers, adding features engineering, and scaling the dataset.*
|    Model      | Training score| Validation score |
| ------------- | ------------- | ---------------- |
| LogisticRegression | 0.7288   | 0.7148           |
| knn                | 0.7833   | 0.6818           |
| DecisionTree       | 0.9952   | 0.6127           |



### Future work:

- we will train various machine learning algorithms.
- fixing the overfitting on the models.
- The best model we will improve its performance
