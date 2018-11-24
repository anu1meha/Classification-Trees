# Classification-Trees
Decision tree, knn classifiers, random forest using python


Homework 6 (by 11:59pm 11/25 Sun)
• (1) Read “data09_diabetes.cvs”. Here, our goal is to predict “Y” with other
variables. Here, please discretize “Y” with threshold 140. (i.e. new Y = 1 if Y > 140,
otherwise, 0). Now, we want to classify the discretized “Y” with other variables.
Randomly divide into training and test sets using
sklearn.model_selection.train_test_split() with test size = 0.33 and random state = 0.
• (2) Please apply a tree model using sklearn.tree.DecisionTreeClassifier class, and
build a prediction model. What is the accuracy of the train and test set? Explain the
performance difference. Is it overfitted, well-fitted, or underfitted?
• (3) Apply bagged KNN, tune the parameter K, and report the accuracy of the train
and test sets. Please consider to use sklearn.neighbors.KNeighborClassifier and
sklearn.ensemble.BaggingClassifier.
• (4) Apply randomForest and report the accuracy of the train and test sets
