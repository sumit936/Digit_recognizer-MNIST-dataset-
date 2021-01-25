## Digit_recognizer using svm and knn classifiers

### Overview
This project is based based on dataset provided by the MNIST(Modified National Institute of Standards and Technology) -MNIST database is a large databse of handwritten digits that is commonly used for training various image processing systems.

Task: Our task here is to recognize or classify these handwritten digits using machine learning algorithms.


#### This Project has been approached in following way:

1.Data
2.Preprocessing
3.Algorithms used
4.Hypertuning
5.Prediction
6.Submission

### 1.Data
Source: Kaggle

This Dataset consists of:
rows: 42000
column:785(including target feature)
target column(or feature): label
rest 784 column: consits of values of pixels

### 2.Preprocessing
These are the steps followed during the preprocessing:
a.Handling Null values-This is the process of removing or replacing missing values from the data
in order to avoid any false learning during training.

b.Categorical feature handling-This is the process of converting categorical features into numerical one in order to do processing cause ML algorithms works only on numerical data.

c.EDA(Exploratory Data Analysis)- This is an approach to analyzing data sets to summarize their main characteristics, often with visual methods. A statistical model can be used or not, but primarily EDA is for seeing what the data can tell us beyond the formal modeling or hypothesis testing task.

d.Normalization-Normalization is also the scaling technique, we should use normalization when you know the distribution of the data does not follow normal distribution.

d.Standardization- This is the process of the scaling all features in the range between 0 and 1.

