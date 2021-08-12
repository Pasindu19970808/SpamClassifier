# SpamClassifier

This project classifies emails as spam or valid emails. 

Data Analysis was carried out to create a dictionary of the most occuring words in all emails, and this was used for classification. 

Algorithms used include:
- Logistic Regression
- Support Vector Classifier
- Adaboost Regressor with Decision Trees 

Adaboost Regressor with Decision Trees and Logistic Regression gave the best results. 

To optimize the best of both works, Adaboost Regressor is initialized with Logistic Regressor estimators. 

The final result on the Test Set gives a Precision Score of 1.0, Recall of 0.947 and F1_score of 0.973.
