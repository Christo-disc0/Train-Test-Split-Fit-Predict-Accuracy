" Now that you have learned about the importance of splitting your data into training and test sets, it's time to practice doing this on the digits dataset! After creating arrays for the features and target variable, you will split them into training and test sets, fit a k-NN classifier to the training data, and then compute its accuracy using the .score() method.

Instructions
100 XP

Import KNeighborsClassifier from sklearn.neighbors and train_test_split from sklearn.model_selection.

Create an array for the features using digits.data and an array for the target using digits.target.

Create stratified training and test sets using 0.2 for the size of the test set. Use a random state of 42. Stratify the split according to the labels so that they are distributed in the training and test sets as they are in the original dataset.

Create a k-NN classifier with 7 neighbors and fit it to the training data.

Compute and print the accuracy of the classifier's predictions using the .score() method. "
