# 📱 iPhone Sales Price Prediction using KNN Regression

This project predicts the selling price of iPhones using **K-Nearest Neighbors (KNN) Regression**.  
The dataset contains real-world features like brand, RAM, MRP, discount percentage, reviews, ratings, etc.

The goal is to build a regression model that can estimate the **final sale price** of an iPhone based on its specifications.

---

## 🔍 Project Steps

### ✔ 1. Load Dataset  
Imported and explored the iPhone dataset containing pricing and product details.

### ✔ 2. Data Cleaning  
- Removed null values  
- Cleaned inconsistent entries  
- Extracted numeric RAM values from strings (e.g., "6 GB" → 6)

### ✔ 3. Feature Engineering  
- Selected relevant numeric features  
- Dropped unnecessary categorical columns  
- Standardized all features using **StandardScaler**

### ✔ 4. Model Training  
Used **KNN Regression** with optimized hyperparameters.  

### ✔ 5. Model Evaluation  
Evaluated the model using:
- **RMSE (Root Mean Squared Error)**
- **R² Score**

### ✔ 6. Visualizations  
- Correlation Heatmap  
- Actual vs Predicted Price Scatter Plot  
- Feature Importance (Correlation)

### ✔ 7. Prediction  
Performed sample predictions using the trained KNN model.

---

## 🚀 Technologies Used
- Python  
- pandas  
- numpy  
- scikit-learn  
- matplotlib  
- seaborn  

---

## 📊 Results
- KNN Regression applied successfully  
- Achieved meaningful RMSE & R² scores  
- Visual insights included for better model understanding  

---

## 📝 Future Improvements
- Use multiple models (Random Forest, XGBoost)  
- Hyperparameter tuning with GridSearchCV  
- Convert project into API using FastAPI or Flask  

---

## 📦 Project Type
**Machine Learning – Regression Model**
