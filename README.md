# supervised-machine-learning-challenge
Comparing the Logistic Regression Model and Random Forest Classifier

Lending services companies allow individual investors to partially fund personal loans as well as buy and sell notes backing loans on a secondary market. I will be using this data to create machine learning models to classify the risk level of given loans. Specifically, I will be comparing the Logistic Regression Model and Random Forest Classifier.

## Steps Taken for Project:
- Retrieve the data from a csv file. Import the data using Pandas and put into a dataframe.
- Split the Data into Trnaing and Testing Sets.
- Create, Fit and Compare Models:
  - Create a Logistic Regression model, fit it to the data, and print the model's score.
  - Create a Random Forest Classifier, fit it to the data, and print the model's score.

## Prediction
Prediciton prior to starting project on which model works better for this type of data: My prediction is that the Logistic Regression model will be more accurate, since this is what many banks currently use to do credit scoring for customer loans.

## Final Analysis
Results after project is completed: The results show the Random Forest model allows for a more accurate loan risk assessment. The Random Forest model can perform both regression and classification tasks. This produces good predictions that can be understood easily. It can also handle large datasets efficiently. The appeals of the Random Forest model are: it emphasizes feature selection, weighing certain features as more important than others; it does not assume that the model has a linear relationship - like regression models; and it utilizes ensemble learing.

Programs used: Jupyter notebook, python, pandas, and sklearn.
