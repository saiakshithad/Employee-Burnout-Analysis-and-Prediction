# Employee Burnout Prediction

## 📌 Project Overview
Employee burnout is a state of physical, emotional, and mental exhaustion caused by excessive and prolonged stress.  
It can seriously affect an employee’s well-being, productivity, and job performance.  

This project uses machine learning models to predict the **burn rate** of employees, helping organizations identify at-risk individuals early and take preventive measures.

---

## 📊 Dataset
**Source**: *Are Your Employees Burning Out?*

The dataset consists of **9 columns**:

- **Employee ID**: Unique identifier for each employee (e.g., `fffe3300350037003500`)  
- **Date of Joining**: Employee’s joining date (e.g., `2008-09-30`)  
- **Gender**: `Male` / `Female`  
- **Company Type**: `Product` / `Service`  
- **WFH Setup Available**: `Yes` / `No`  
- **Designation**: Employee’s role level in the range **[0.0, 5.0]**  
- **Resource Allocation**: Number of working hours assigned in the range **[1.0, 10.0]**  
- **Mental Fatigue Score**: Mental fatigue level in the range **[0.0, 10.0]**  
- **Burn Rate**: Target variable in the range **[0.0, 1.0]**, higher means higher burnout  

---

## ⚙️ Project Workflow
1. **Data Preprocessing**
   - Handling missing values  
   - Encoding categorical features  
   - Feature scaling with StandardScaler  

2. **Exploratory Data Analysis (EDA)**
   - Distribution of Burn Rate  
   - Correlation analysis  
   - Trends based on Gender, Designation, Company Type  

3. **Model Training**
   - Linear Regression  
   - Random Forest Regressor  
   - XGBoost Regressor  

4. **Evaluation Metrics**
   - Mean Squared Error (MSE)  
   - Root Mean Squared Error (RMSE)  
   - Mean Absolute Error (MAE)  
   - R² Score  

---

## 🚀 Results
- **Linear Regression**: Baseline model  
- **Random Forest**: Improved performance with non-linear relationships  
- **XGBoost**: Best-performing model with optimized hyperparameters  

*(Detailed results and comparison plots are available in the notebook.)*

---

## 🛠️ Tech Stack
- Python 3.x  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- XGBoost  

---
