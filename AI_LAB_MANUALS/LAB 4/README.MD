LAB No. 4
Random Forest and Support Vector Machine Classifier

Question 1
Classify flower species using Random Forest.
Task:
1.	Load the Iris dataset from sklearn.datasets.
2.	Split into training (70%) and testing (30%) sets.
3.	Train a Random Forest Classifier.
4.	Predict flower species on the test set.
5.	Calculate and print model accuracy.
Question 2
Use SVM on Breast Cancer Dataset and Classify tumors as malignant or benign.
Task:
1.	Load the Breast Cancer dataset using sklearn.datasets.load_breast_cancer.
2.	Train an SVM classifier (use SVC(kernel='linear')).
3.	Evaluate the model using accuracy and confusion matrix.

Question 3
Use Random Forest on CSV Dataset (Custom) : Predict student pass/fail based on study hours and scores.
Task:
1.	Load a CSV file (e.g., students.csv) with columns: study_hours, attendance, marks, result.
2.	Train a Random Forest Classifier to predict result (Pass/Fail).
3.	Display accuracy score and feature importance.

Question 4
Use SVM on Digits Dataset and to identify the: Handwritten digit recognition.
Task:
1.	Load the Digits dataset from sklearn.datasets.load_digits.
2.	Train an SVM classifier with an RBF kernel.
3.	Test on unseen data.
4.	Print accuracy and visualize some misclassified samples.

Question 5:
Compare Random Forest vs SVM on Same Dataset (you can choose any dataset): Compare two models on the same data.
Task:
•	Use the Wine dataset from sklearn.datasets.load_wine.
•	Train both:
RandomForestClassifier(n_estimators=100)
•	SVC(kernel='rbf')
•	Print accuracy of both models.
•	Conclude which performs better.
