Project: Iris Classification

Algorithms Used:

KNN
Logistic Regression
Decision Tree
Best Model: KNN

How to Run:

import joblib

model = joblib.load("models/best_model.pkl")

sample = [[5.1,3.5,1.4,0.2]]

prediction = model.predict(sample)

print(prediction)
