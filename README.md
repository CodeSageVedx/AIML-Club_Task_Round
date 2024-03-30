Problem Statement: Classify iris flowers into one of the three species based on four features: sepal length, sepal width, petal length, and petal width. 
Solution Approach: Load the Iris dataset using load_iris from sklearn.datasets.
Split the dataset into training and testing sets.
Preprocess using StandardScaler.
Train a classifier, using LogisticRegression, on the training set.
Evaluate the classifier on the testing set using metrics like accuracy, precision, recall, and F1 score.
Visualise the results using standard visualisation tools.