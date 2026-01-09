LAB No 3
Decision Tree Classifier
Question 1
Entropy and Information Gain (Manual Calculation)
Given the dataset below about whether students pass an exam based on study time and attendance:
Student	Study Hours	Attendance	Result
S1	Low	Poor	Fail
S2	High	Good	Pass
S3	High	Poor	Pass
S4	Low	Good	Fail
S5	High	Good	Pass

1.	Calculate the entropy of the target variable (Result).
2.	Compute the information gain for the attribute Study Hours.
3.	Which attribute should be selected for the root node based on maximum information gain?
Question No. 2
Implement Decision Tree Classifier on a Small Dataset
Build and visualize a simple decision tree.
Question:
Using the same dataset as above:
1.	Use pandas to create a DataFrame.
2.	Convert categorical values into numerical using LabelEncoder.
3.	Train a DecisionTreeClassifier using criterion='entropy'.
4.	Visualize the decision tree using plot_tree() from sklearn.tree.
Question 3
Decision Tree Classifier on Iris Dataset
Objective: Apply decision trees to a real dataset.
Question:
1.	Load the Iris dataset using sklearn.datasets.load_iris.
2.	Split it into training (70%) and testing (30%) sets.
3.	Train a decision tree using criterion='entropy'.
4.	Print the accuracy on the test set.
5.	Visualize the tree and explain which feature provides the most information gain at the root.

Question 4
MNIST digit dataset (available via Keras / sklearn.datasets) as a baseline
Objectives
•	Preprocess image data for classification
•	Train a Decision Tree Classifier (or variants)
•	Evaluate accuracy, confusion matrix, and discuss limitations
