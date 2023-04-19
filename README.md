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

## Workflow
1. Download the dataset and evaluate it
2. Pre-process the data. I have chosen 10k rows to work with.
3. Split the samples in 70 : 30 for training and testing on the 10 samples created.
4. Optimise SVM using randomisation for every sample and observe its best accuracy and best parameters
5. For the best sample plot the convergence graph

## Output Table 
| Samples       | Best Accuracy | Best Kernel | Best C    | Best Gamma  | 
| ------------- |:-------------:| -----------:| --------- |:-----------:| 
| S1            | 92 | poly | 30.375176	| 0.037171
| S2            | 88      |   poly | 42.639533	| 0.022289
| S3            | 89     |    rbf |0.378948	 | 0.479710
| S4            | 86 | rbf | 7.12 |11.022291 |	0.110948
| S5            | 93    |   linear|2.396415	| 0.825749
| S6            | 90      |    rbf |	20.984094	| 0.042918
| S7            | 89.3      |    rbf | 2.984728	 | 0.080764
| S8            | 90.6      |    linear | 3.247041|	0.137408
| S9            | 91.3     |    rbf| 4.064076	| 0.022075
| S10           | 86      |    rbf |21.609939	| 0.090025



### We notice the best accuracy to be for S5 (i.e, sample 5) with accuracy 92 using parameters: linear	2.396415	0.025.


#### Best Sample : S5
#### Best C: 2.39
#### Best gamma: 0.025


#### Convergence Graph

<img width="964" alt="Screenshot 2023-04-20 at 2 43 42 AM" src="https://user-images.githubusercontent.com/73638083/233201505-e22b7209-86ed-46be-84e2-35c74f1432b0.png">




#### Name: Ananya Singh
#### Roll No: 102016083





