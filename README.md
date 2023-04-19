# Parameter_Optimisation_With_SVM

## SVM and its Parameters
Support Vector Machines (SVMs) are a popular machine learning algorithm used for classification, regression, and outlier detection. SVMs work by finding a hyperplane that separates data points of different classes with the maximum margin.

The parameters that we work on here are : C, gamma and kernel  

One of the important parameters in SVMs is C, which controls the tradeoff between achieving a low training error and a low testing error. A smaller value of C will lead to a wider margin but more training errors, while a larger value of C will lead to a narrower margin but fewer training errors.

Another parameter is gamma, which controls the shape of the decision boundary. A smaller value of gamma will lead to a more flexible decision boundary, while a larger value of gamma will lead to a more rigid decision boundary.

The choice of kernel function also plays an important role in SVMs. A kernel function maps the input data into a higher-dimensional space where a linear decision boundary can be found. Some common kernel functions include linear, polynomial, and radial basis function (RBF) kernels.

It is important to choose appropriate values for these parameters and kernel functions in order to achieve optimal performance in SVMs. 

## Dataset chosen

Dataset used: [Bank Marketing](https://archive.ics.uci.edu/ml/datasets/bank+marketing "Bank Marketing")

The banking dataset available on the UC Machine Learning Repository is a popular dataset used in the field of data science and machine learning. This dataset contains information on bank customers and their demographic, financial, and banking behavior attributes. The dataset consists of 45,211 rows and 17 columns.

The goal of this dataset is to predict whether a customer will subscribe to a term deposit with the bank, based on their attributes. The target variable is binary, with a value of 1 indicating that the customer has subscribed to a term deposit, and a value of 0 indicating that they have not.

Some of the attributes included in this dataset are age, job, marital status, education, housing loan status, and credit default status. The dataset also includes information on the last contact of the current campaign, as well as previous campaigns, such as the number of contacts made, the outcome of the previous campaign, and the time since the last contact.
