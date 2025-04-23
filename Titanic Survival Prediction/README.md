# 🚢 Titanic Survival Prediction Challenge

This project was developed as part of a data science challenge focused on predicting passenger survival from the Titanic disaster using the dataset provided by **SOAI Lab_Kaggle**. The main objective is to compare the performance of several machine learning algorithms on this binary classification problem.

## 🧠 Models Evaluated

Several algorithms were implemented and evaluated based on their accuracy on the validation set:

| Model                             | Accuracy (%) |
|----------------------------------|--------------|
| HistGradientBoostingClassifier   | 77.14        |
| Random Forest Classifier         | 76.67        |
| XGBClassifier	                   | 78.1
| Neural Network (MLPClassifier)   | 80.00        |
| Support Vector Classifier (SVC)  | 77.14        |

> 🔍 *Note: Accuracy values depend on preprocessing steps such as handling missing values, encoding categorical features, and feature scaling.*

## 🧰 Libraries

- Scikit-learn  
- Pandas
- NumPy  
- Matplotlib 
- Seaborn  


## 📌 Results

The best-performing algorithm on the validation set was:

**👉 Neural Network (MLPClassifier) with an accuracy of 80.00%**
