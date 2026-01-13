# PROBLEM STATEMENT

Diabetes has become a rapidly growing global health concern, and timely diagnosis remains difficult, especially in resource-limited regions. Women are particularly vulnerable, as undetected diabetes can result in serious health complications, including gestational diabetes during pregnancy and a higher likelihood of cardiovascular diseases compared to men.
The Gap:-
Current diagnostic methods rely heavily on hospital visits, invasive blood tests, and delayed laboratory reports, making early screening inconvenient and inaccessible for many women.
The Problem:-
There is a shortage of user-friendly, digital screening solutions that enable women to quickly evaluate their diabetes risk using available medical data. Existing tools often fail to incorporate women-specific factors such as pregnancy history, alongside critical health indicators like BMI and glucose levels. This project aims to bridge this gap by developing an intelligent, women-centric risk assessment system for early diabetes detection.

# PROPOSED SOLUTION

The proposed solution is a Predictive Web Application User Interface aimed at enabling early diabetes risk assessment in women.We have built a functional system where a user or a healthcare worker can input eight health parameters into a web interface.The solution delivers instant predictions through a simple web interface, making it suitable for both healthcare professionals and non-technical users.

1. Data Collection & Dataset Overview

The model uses a structured medical dataset containing eight clinically significant attributes, including women-specific factors:
1.Pregnancies
2.Glucose
3.Blood Pressure
4.Skin Thickness
5.Insulin
6.Body Mass Index (BMI)
7.Diabetes Pedigree Function
8.Age

2. Data Preprocessing

To ensure high-quality input for model learning:
Missing and zero values are handled appropriately
Feature scaling (standardization) is applied to normalize different data ranges
Clean data is prepared for model training

3. Model Training

The dataset is split into training and testing sets (typically 70–80% for training and 20–30% for testing)
The Support Vector Machine (SVM) algorithm is trained using the training data
SVM is well-suited for binary classification problems (Diabetic vs. Non-Diabetic)
The model learns to identify patterns that distinguish diabetic and non-diabetic cases

4.  Deployment Using Streamlit
The final trained model is deployed using Streamlit
Users enter health details through an intuitive web interface
The backend processes the input and displays prediction results in real time




