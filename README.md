# Iris-KNN-Classification

# Iris Flower Classification using Supervised Machine Learning 🌸

## 📌 Project Overview
A botanical research centre wants to automate the identification of Iris flower species based on physical measurements.  
This project implements **Supervised Machine Learning classification models** to predict the species of an Iris flower using its sepal and petal dimensions.

The goal is to **train, evaluate, and compare** multiple ML algorithms and identify the best-performing model.

---

## 🎯 Problem Statement
Manual identification of Iris flower species is:
- Time-consuming  
- Error-prone  
- Not scalable  

To solve this, a **Machine Learning–based classification system** is developed.

---

## 📂 Dataset Description
The Iris dataset contains **150 samples** with the following features:

| Feature Name        | Description |
|--------------------|-------------|
| SepalLengthCm      | Length of sepal (cm) |
| SepalWidthCm       | Width of sepal (cm) |
| PetalLengthCm      | Length of petal (cm) |
| PetalWidthCm       | Width of petal (cm) |
| Species (Target)   | Iris-setosa, Iris-versicolor, Iris-virginica |

---

## 🧠 Machine Learning Models Used
- **K-Nearest Neighbors (KNN)**
- **Logistic Regression**
- **Naive Bayes (GaussianNB)**

---

## ⚙️ Project Workflow
1. Import required libraries  
2. Load and explore the dataset  
3. Separate features and target variable  
4. Split data into training and testing sets  
5. Perform feature scaling  
6. Train ML models  
7. Evaluate models using accuracy and classification report  
8. Compare performances and select the best model  

---

## 📊 Model Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1-score  
- Confusion Matrix  

---

## 🏆 Results & Conclusion
- **Logistic Regression** achieved the highest accuracy
- **KNN** performed competitively with proper scaling
- **Naive Bayes** was fast but slightly less accurate

👉 **Logistic Regression is recommended** as the best model for Iris flower classification.

---

## 🛠️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib / Seaborn  

---

## 📁 Project Structure
ris-Classification-KNN-LR-NB/
│
├── iris_classification.ipynb
├── README.md
├── requirements.txt
└── dataset/
└── iris.csv

---

## 👩‍💻 Author
**Ashwini Bhor**  
📧 Email: ashwinibhor2301@gmail.com  

---

## 📌 Note
This project is developed as part of **Supervised Machine Learning – Assignment **.
