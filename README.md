# Sampling_102103781

Assignment02 - Sampling
Submitted by: Aarushi Juneja

Roll No: 102103781

Section: 3CO28

# Dataset
The dataset consists of 31 columns and 772 entries, with a target variable labeled 'Class'. This variable is binary, having values of '0' or '1'. Notably, the dataset is imbalanced, with 763 entries classified as Class '0' and only 9 entries as Class '1'.

# Balancing the Dataset
To address the class imbalance, SMOTE (Synthetic Minority Oversampling Technique) was employed. SMOTE operates by randomly selecting a point from the minority class and calculating the k-nearest neighbors for this point. Synthetic points are then introduced between the chosen point and its neighbors. Post-balancing, there are 763 entries for each of Class '0' and '1'.

# Creating 5 Samples
Five sampling techniques were utilized: Simple Random, Systematic, Stratified, Cluster, and Bootstrap Sampling Techniques.

# Models Used
The following classification models were employed:

Logistic Regression
Random Forest Classifier
Support Vector Classifier
Gradient Boosting Classifier
MLPClassifier

# Result Table
![image](https://github.com/aarushijunejaa/Sampling_102103781/assets/143161557/3904b843-0a89-4fa3-bfc0-0f5795fcddb6)

# Result
-> The table compares the performance of various machine learning algorithms on a classification task.

-> Different metrics (Simple Random, Systematic, Stratified, Cluster, Bootstrap) are used to evaluate the algorithms.

-> Each value represents the accuracy score achieved by an algorithm on a specific metric.
