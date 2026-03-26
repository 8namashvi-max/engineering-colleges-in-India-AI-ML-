# 📊 Engineering Colleges in India — AI/ML Innovative Assignment

## 📌 Project Overview
This project focuses on **data analysis, preprocessing, visualization, and machine learning modeling** using a real-world dataset of **Engineering Colleges in India** sourced from Kaggle.

The dataset contains information such as college name, location, faculty strength, student enrollments, courses offered, campus facilities, ratings, and average fees.

The goal of this project is to apply **AI/ML concepts** including data cleaning, statistical analysis, visualization, and **K-Nearest Neighbors (KNN) classification** to extract meaningful insights from educational data.

---

## 📂 Dataset Details
- **Source:** Kaggle  
- **Domain:** Educational Institutions / Higher Education Analytics  
- **Total Records:** 5446 Engineering Colleges  
- **Total Features:** 15 Columns  

### Key Attributes
- College Name  
- Gender Acceptance  
- Campus Size  
- Total Student Enrollments  
- Total Faculty  
- Established Year  
- Rating  
- University Affiliation  
- Courses Offered  
- Facilities  
- City, State, Country  
- College Type  
- Average Fees  

---

## 🧹 Data Preprocessing
Preprocessing steps applied to the dataset:
- Removal of rows with incorrect or inconsistent values
- Handling missing values:
  - **Numerical columns:** filled with mean values  
  - **Categorical columns:** filled with mode values  
  - **Columns where mean/mode is not meaningful:** replaced with global constants
- Conversion of string-based numeric values into float format
- Creation of a new **Fee Category** column for classification

---

## 📊 Statistical Analysis
Descriptive statistical measures were computed for numerical features:  
- Count  
- Minimum & Maximum  
- Range  
- Mean  
- Median  
- Variance  
- Standard Deviation  

For categorical features, the **mode** was calculated.

---

## 📈 Data Visualization
Visualizations created using **Matplotlib subplots**:
- Scatter Plot → Student Enrollments vs Rating  
- Line Graph → Student Enrollments vs Total Faculty  
- Scatter Plot → Student Enrollments vs Average Fees  
- Histogram → Distribution of Colleges by Established Year  

These plots provide insights into trends and relationships between different college attributes.

---

## 🤖 Machine Learning Model
A **K-Nearest Neighbors (KNN) Classifier** was implemented to classify colleges based on fee structure.

### Model Workflow
- Features selected from the dataset  
- Target variable: **Fee Category**  
- Dataset split: **80% training, 20% testing**  
- Distance calculated using Euclidean metric  
- Weighted voting for prediction  
- Training using Scikit-learn `KNeighborsClassifier`  

### Evaluation Metrics
- Accuracy Score  
- Precision  
- Recall  
- F1-Score  

Results show the model can classify colleges effectively based on fee categories after proper preprocessing.

---

## ✅ Key Observations
- College fees vary widely across institutions.  
- Handling missing data improves model reliability.  
- Factors such as enrollment size, faculty strength, and facilities influence classification.  
- Machine learning can assist students and policymakers in **decision-making and comparative analysis**.

---

## 🛠️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn  

---

## 🎯 Future Improvements
- Apply feature scaling and normalization  
- Test advanced models (Random Forest, SVM, Logistic Regression)  
- Perform clustering to group similar colleges  
- Build a recommendation system for students  
- Deploy as an interactive web dashboard  

---
