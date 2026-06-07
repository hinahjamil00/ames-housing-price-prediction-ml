# 🏠 Ames Housing Price Prediction (Machine Learning Project)

## 📌 Overview
This project predicts **house prices in Ames, Iowa** using machine learning models.  
It uses the famous **Ames Housing Dataset** with 79 features describing residential properties.

The project includes:
- Data preprocessing
- Exploratory Data Analysis (EDA)
- Regression & Classification models
- Hyperparameter tuning
- Model comparison & evaluation

---

## 🎯 Objectives
- Analyze housing data and find key price drivers  
- Build regression models to predict `SalePrice`  
- Create classification model (Low / Medium / High price)  
- Improve model performance using tuning techniques  
- Compare multiple machine learning models  

---

## 📊 Dataset Information
- **Dataset:** Ames Housing Dataset  
- **Rows:** 2930  
- **Features:** 79  
- **Target Variable:** `SalePrice`  

---

## 🧠 Machine Learning Models

### 🔹 Regression Models
- Linear Regression  
- Ridge Regression  
- Lasso Regression  
- Random Forest Regressor  
- Gradient Boosting Regressor  

### 🔹 Classification Models
- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier  
- Gradient Boosting Classifier  
- Support Vector Machine (SVM)  
- K-Nearest Neighbors (KNN)  

---

## ⚙️ Techniques Used
- Missing Value Handling  
- One-Hot Encoding  
- Feature Scaling  
- Train-Test Split  
- Pipeline Construction  
- GridSearchCV / RandomizedSearchCV  
- Model Evaluation  

---

## 📈 Evaluation Metrics

### Regression
- R² Score  
- RMSE (Root Mean Squared Error)  

### Classification
- Accuracy Score  
- Confusion Matrix  

---

## 🔍 Key Insights
- Newer houses tend to have higher prices  
- Recent renovations increase property value  
- Overall quality is a strong predictor of price  
- Ensemble models perform better than simple models  

---

## 🏆 Best Models
- **Regression:** Gradient Boosting Regressor  
- **Classification:** Random Forest Classifier   

---

## 📊 Visualizations
- Correlation Heatmap  
- Feature vs Price Analysis  
- Model Comparison Charts  
- Confusion Matrix  
- Before vs After Tuning Graphs  

---

## 🚀 Project Workflow
Data Collection → Data Cleaning → EDA → Feature Engineering → Model Training → Hyperparameter Tuning → Evaluation → Prediction System

---

## 💻 How to Run

```bash
git clone https://github.com/your-username/ames-housing-price-prediction.git

cd ames-housing-price-prediction

pip install -r requirements.txt

jupyter notebook
