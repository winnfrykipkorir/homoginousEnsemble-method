# homoginousEnsemble-method
The two datasets churn modelling.csv and Insurance.csv are the focus of a random forest operation employing homogeneous ensemble.

Many libraries, including pandas, randomforestclassifier, and numpy, are uploaded.
First, the dataset is loaded and examined for missing values; in this instance, neither dataset has any missing values.
In this scenario, CustomerId in the churn and children in the insurance columns were removed from the dataset as they were unneeded for the analysis of the data.
Under the 0.2 test fraction, data are divided into training and test sets.
A base classifier, rf = RandomForestClassifier(n estimators=100), is used to generate a homogenous ensemble random forest classifier.
The models are tested for accuracy, precision, recall, and f1 score by making predictions using the test set.Greater accuracy values show that the model performs well on the dataset, whereas lower accuracy values show that the ensemble performs poorly.
While insurance produced average values, the churn model produced a variety of results that were all very high, indicating a successful ensemble.
