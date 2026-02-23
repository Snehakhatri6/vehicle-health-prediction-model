# 🚗 Vehicle Health Prediction using Machine Learning

A **Machine Learning project** that predicts the health condition of vehicles using real-world sensor data such as **engine RPM**, **fuel pressure**, **lubricant oil temperature**, and **coolant levels**.  
The goal is to enable **predictive maintenance** — identifying potential issues before failure occurs, helping reduce downtime and maintenance costs.

---

## 📊 Project Workflow

### 1️⃣ Data Preprocessing
- Cleaned & standardized sensor readings  
- Handled missing values and performed feature scaling  
- Encoded categorical variables (if any)

### 2️⃣ Exploratory Data Analysis (EDA)
- Visualized the distribution of key features: RPM, fuel pressure, oil temperature, coolant levels  
- Conducted **correlation analysis** to identify the most impactful parameters

### 3️⃣ Model Development
- Trained multiple ML models:
  - Logistic Regression  
  - Random Forest Classifier  
  - Decision Tree  
- Best-performing model achieved **~66% accuracy**

### 4️⃣ Feature Importance (Top Predictors)
| Feature | Importance (%) |
|----------|----------------|
| Engine RPM | 35 |
| Fuel Pressure | 16 |
| Lubricant Oil Temperature | 14 |
| Lubricant Oil Pressure | 12 |
| Coolant Pressure | 11 |
| Coolant Temperature | 10 |

---

## 📈 Results & Insights
- Vehicle health can be **moderately predicted** using available sensor data  
- **Engine RPM** is the most critical predictor of health status  
- Model performance can improve with:
  - A **larger and more diverse dataset**  
  - Better **class balance**  
  - Use of **advanced algorithms** (e.g., Gradient Boosting, Neural Networks)

---

## 🧠 Key Learnings
- Improved understanding of **feature engineering** for sensor data  
- Hands-on experience with **classification models** and **evaluation metrics**  
- Learned how to interpret **feature importance** and derive actionable insights

---

## ⚙️ Tech Stack
- **Programming:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Environment:** Google Colab / Jupyter Notebook  

---

## 🚀 Next Steps
- Add real-time data integration (via API or IoT sensors)  
- Deploy model using **Streamlit** or **Flask** web app  
- Build a **Power BI dashboard** (optional extension)  

---

