# 🍽️ Restaurant Revenue Prediction  

This project predicts the **monthly revenue of restaurants** based on customer, pricing, marketing, and review data.  
It is a **beginner-friendly machine learning project** inspired by a Loan Approval model workflow.  

---

## 📌 Project Overview  
Restaurants generate revenue from multiple factors such as:  
- Number of customers  
- Menu price  
- Marketing spend  
- Cuisine type  
- Customer spending behavior  
- Promotions and reviews  

The goal of this project is to **predict the Monthly Revenue** of a restaurant using **machine learning models**.  

---

## 📂 Dataset  
The dataset contains **1000 rows × 8 columns**:  

| Column | Description |
|--------|-------------|
| Number_of_Customers | Number of customers visiting the restaurant |
| Menu_Price | Average price of items on the menu |
| Marketing_Spend | Amount spent on marketing |
| Cuisine_Type | Type of cuisine (categorical) |
| Average_Customer_Spending | Average spending per customer |
| Promotions | Whether promotions are running (0/1) |
| Reviews | Number of reviews received |
| Monthly_Revenue | 📌 Target variable – Monthly revenue of the restaurant |

---

## ⚙️ Steps in the Notebook  

1. **Import Libraries** → pandas, numpy, matplotlib, seaborn, sklearn  
2. **Load Dataset** → read CSV file into DataFrame  
3. **Exploratory Data Analysis (EDA)** →  
   - Summary statistics  
   - Correlation heatmap  
   - Revenue distribution plot  
   - Cuisine type distribution  
4. **Data Preprocessing** →  
   - Label Encoding for categorical variable  
   - Feature scaling using StandardScaler  
   - Train-test split  
5. **Model Training** →  
   - Linear Regression  
   - Decision Tree Regressor  
   - Random Forest Regressor  
6. **Model Evaluation** →  
   - MAE (Mean Absolute Error)  
   - MSE (Mean Squared Error)  
   - RMSE (Root Mean Squared Error)  
   - R² Score  

---

## 📊 Models Used  

- **Linear Regression** → Baseline model  
- **Decision Tree Regressor** → Handles non-linear patterns  
- **Random Forest Regressor** → Ensemble method for better accuracy  

---

## 🚀 Results  

Each model is evaluated using **MAE, MSE, RMSE, and R² Score**.  
Typically, **Random Forest performs the best** in terms of accuracy.  

---

## 🛠️ Requirements  

Install dependencies before running the notebook:  

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
