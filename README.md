# Diabetics-Detection
The Diabetes Detection System is a machine learning–powered web application designed to predict whether an individual is likely to have diabetes based on clinical health parameters. The system leverages the PIMA Indians Diabetes Dataset and applies Logistic Regression to classify a patient as Diabetic or Not Diabetic.


The application consists of two major modules:

🔹 Machine Learning Module

The dataset is cleaned by replacing missing or zero values with column means.

Features used for prediction include:

Pregnancies

Glucose Level

Blood Pressure

Skin Thickness

Insulin Level

BMI

Diabetes Pedigree Function

Age

The dataset is split into training and testing sets.

A Logistic Regression model is trained to distinguish between diabetic and non-diabetic individuals.

The trained model achieved an accuracy of ~75% and is saved as a .pkl file for deployment.

🔹 Web Application Module

A Flask backend loads the trained model and handles prediction requests.

An HTML + CSS frontend provides an intuitive user interface where users enter medical inputs and receive results.

The result section displays:

Predicted outcome: Diabetic / Not Diabetic

Probability score (if available)

Health tips based on prediction

✨ Key Features

✔ Real-time diabetes prediction using machine learning
✔ Interactive and user-friendly interface
✔ Flask server with JSON API support
✔ Clean UI using modern CSS
✔ Risk probability and personalized tips

🔧 Technology Stack
Category	Technology
Programming Language	Python
Machine Learning	scikit-learn (Logistic Regression)
Web Backend	Flask
Frontend	HTML, CSS
Dataset	PIMA Indians Diabetes Dataset
