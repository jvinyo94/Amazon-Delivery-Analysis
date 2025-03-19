# Amazon Delivery Analysis: Last-Mile Logistics and Performance Prediction

## 📌 Project Overview  
This project applies *machine learning* to analyze Amazon delivery data and predict delivery times. We identify key factors like weather, traffic, agent characteristics, and order timing to optimize last-mile logistics.  

## 📊 Dataset (Amazon Delivery Dataset) 
The dataset includes:  
- *Order Details* (Order time, location, distance)  
- *Delivery Agents* (Age, experience, ratings)  
- *Environmental Factors* (Weather, traffic conditions)  

## 🔍 Key Analysis Steps  
1. *Data Preprocessing* – Cleaned missing values, handled outliers, encoded categorical variables.  
2. *Exploratory Data Analysis (EDA)* – Used statistical analysis & visualizations to understand trends.  
3. *Feature Engineering* – Created new variables to improve model performance.  
4. *Machine Learning Models*:  
   - *Baseline Model:* Linear Regression  
   - *Advanced Models:*  
     - *Random Forest* 🌲  
     - *Gradient Boosting Machines (LightGBM, XGBoost CatBoost)* ⚡  
     - *Neural Network (MLP Regressor)* 🧠  
   - *Model Evaluation:* Used *R² score, RMSE, and MAE* to compare performance.  
5. *SHAP Values for Explainability* – Interpreted model predictions to identify top influencing features.  

## 🎯 Key Insights  
- *Traffic & Weather Conditions* significantly impact delivery times.  
- *Agent Experience & Ratings* play a role in faster deliveries.  
- *Short-distance orders* often experience unexpected delays due to urban congestion.  
- *LightGBM outperformed other models*, achieving the best predictive accuracy.  

## 🛠 Tools & Libraries  
- *Python:* Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, SHAP  
- *Machine Learning:* LightGBM, XGBoost, CatBoost, Random Forest, Neural Networks (MLP)  
- *Data Visualization:* Tableau  
- *Jupyter Notebook & GitHub* for project management  

## 🚀 How to Use  
1. Clone the repository:  
   ```bash
   git clone https://github.com/jvinyo94/Amazon-Delivery-Analysis.git


📌 Next Steps
	•	Improve model accuracy using advanced ML techniques.
	•	Expand analysis to include additional delivery data sources.

## 🤝 Connect With Me

If you have feedback or suggestions, feel free to reach out!
