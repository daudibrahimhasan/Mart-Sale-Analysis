# 📊 Predicting Item Outlet Sales Using Linear Regression

![Python](https://img.shields.io/badge/Python-3.9-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikit-learn)
![Pandas](https://img.shields.io/badge/Pandas-Data--Analysis-green?logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-informational?logo=python)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-blue?logo=python)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## 📌 Project Overview
This project builds a **machine learning model** using **Linear Regression** to predict **item outlet sales**.  

The dataset includes training and testing records with item attributes (e.g., weight, visibility, type) and outlet characteristics (e.g., size, location, type).  

The primary objective is to **predict Item_Outlet_Sales** by learning patterns from features like item properties and outlet details.  
This approach demonstrates the use of **linear modeling** for solving real-world retail sales forecasting problems.

---

## ⚙️ Workflow

### 1. Data Loading & Exploration
- Datasets loaded from **Google Drive** into Pandas DataFrames.  
- Files: `sales1.csv` (training) and `sales2.csv` (testing).  

### 2. Feature Engineering
- Selected features: Item attributes (e.g., Item_Weight, Item_Visibility, Item_Type) and outlet details (e.g., Outlet_Size, Outlet_Location_Type, Outlet_Type).  
- Handled categorical features with appropriate encoding (e.g., One-Hot Encoding).  

### 3. Preprocessing
- Separated features (`X`) and target (`y = Item_Outlet_Sales`).  
- Handled missing values and normalized numerical features if needed.  

### 4. Train-Test Split
- Used the provided `train.csv` for training and `test.csv` for evaluation (no additional split required).  

### 5. Model Training
- Implemented **Linear Regression** using `sklearn.linear_model.LinearRegression`.  
- Trained the model on the training data.  

### 6. Evaluation & Visualization
- Predicted sales on training and test data.  
- Evaluated using **Root Mean Squared Error (RMSE)**.  
- Visualized feature correlations, actual vs. predicted sales, and feature importance using Matplotlib and Seaborn.  

---

## 📊 Results
✅ **Evaluation Metric:** Root Mean Squared Error (RMSE) calculated for accuracy.  
✅ Model identifies key influencers like outlet type and item visibility on sales.  
✅ Visualizations highlight strong correlations and prediction alignment.  

---

## 🛠️ Tools & Technologies
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn  
- **Environment:** Google Colab (with Drive integration)  

---

## 🌍 Real-World Applications
- **Retailers** → Optimize inventory and pricing strategies based on predicted sales.  
- **Supermarkets & Outlets** → Forecast demand for better stock management.  
- **Market Analysts** → Analyze trends in item performance across different outlet types.  
- **E-commerce Platforms** → Enhance recommendation systems with sales predictions.  

---

## ⚖️ Limitations & Future Work
Although the model provides solid predictions, it is important to acknowledge:  
- **Feature limitations:** Relies on basic item and outlet attributes; external factors like promotions or economic conditions are not included.  
- **Assumption risks:** Linear Regression assumes linear relationships, which may not capture complex patterns.  
- **Data bias:** Dataset may be specific to certain regions or time periods.  

🔮 **Planned Improvements**:
- Incorporate additional features (e.g., seasonality, promotions).  
- Compare with advanced models (e.g., Random Forest, Gradient Boosting).  
- Perform **hyperparameter tuning** and cross-validation.  
- Deploy as an interactive **web app** (e.g., using Streamlit).  
- Integrate with **real-time sales APIs** for dynamic forecasting.  

---

## 📂 Dataset
- **Files:** `sales1.csv` (training) and `sales2.csv` (testing)  
- **Target Variable:** `Item_Outlet_Sales`  
- **Key Columns:** Item_Identifier, Item_Weight, Item_Fat_Content, Item_Visibility, Item_Type, Item_MRP, Outlet_Identifier, Outlet_Establishment_Year, Outlet_Size, Outlet_Location_Type, Outlet_Type, etc.  

---

## 🧑‍💻 Author
**Daud Ibrahim Hassan**  
📌 Data Analyst & Computer Science Student (BRAC University)  
🔗 [LinkedIn](https://www.linkedin.com/in/daudibrahimhasan/) | [GitHub](https://github.com/daudibrahimhasan)  

---
