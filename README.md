# 🏥 Medical Insurance Cost Prediction using Machine Learning

## 📌 Overview
This project predicts medical insurance charges based on personal and lifestyle attributes such as age, BMI, smoking habits, and region.  
It follows a complete machine learning pipeline — from data analysis to model evaluation.

---

## 📊 Dataset
The dataset contains the following features:

- Age  
- Gender  
- BMI (Body Mass Index)  
- Number of children  
- Smoking status  
- Region  
- Insurance charges (target variable)

---

## 🔍 Exploratory Data Analysis (EDA)
- Distribution analysis using histograms and KDE plots  
- Categorical feature visualization (count plots)  
- Outlier detection using boxplots  
- Correlation analysis using heatmaps  

---

## 🧹 Data Preprocessing
- Removal of duplicate records  
- Encoding:
  - Binary encoding for `sex` and `smoker`
  - One-hot encoding for `region`
- Feature scaling using **StandardScaler**

---

## ⚙️ Feature Engineering
- Created **BMI categories**:
  - Underweight  
  - Normal  
  - Overweight  
  - Obese  
- Converted into dummy variables for model use  

---

## 🧠 Feature Selection
- **Pearson Correlation** for numerical features  
- **Chi-Square Test** for categorical features  
- Selected relevant features based on statistical significance  

---

## 🤖 Model Used
- **Linear Regression**

---

## 📈 Model Evaluation
- **R² Score**
- **Adjusted R² Score**

These metrics evaluate how well the model explains variance in insurance charges.

---

## 🚧 Current Status
Model has been trained and evaluated successfully.  
Further improvements (like advanced models and tuning) can be added.

---

## 🛠️ Tools & Technologies
- Python  
- Pandas, NumPy  
- Seaborn, Matplotlib  
- Scikit-learn  
- SciPy  

---

## 💡 Future Improvements
- Try advanced models (Random Forest, XGBoost)  
- Hyperparameter tuning  
- Model deployment (Flask / Streamlit)  
- Feature importance visualization  

---

## 📁 Project Structure
├── Smart Insurance Cost Predictor.ipynb
├── insurance.csv
├── README.md