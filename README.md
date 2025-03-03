# 🚗 CO2 Emission Prediction 

## 📌 Project Overview  
This project aims to predict **CO₂ emissions** based on vehicle specifications using **Machine Learning**. We explored multiple regression models and selected **Random Forest Regressor** as the best-performing model due to its accuracy and generalization ability.

---

## 📊 Key Features  
✅ Predict CO₂ emissions based on car engine features  
✅ Uses **Random Forest Regression** for accurate predictions  
✅ Interactive **Streamlit Web App** for easy input & visualization  
✅ Data preprocessing, feature scaling, and model evaluation  
✅ Deployed model for real-world usage  

---

## 📂 Project Structure  
```
📁 CO2-Emission-Prediction-Group4
│── 📄 co2_dep_group4.py              # Streamlit app for model deployment
│── 📄 co2_emissions_prediction_Group4.ipynb  # Jupyter Notebook for model training
│── 📄 co2_rf_model_c.pkl      # Trained Random Forest model
│── 📄 co2_emissions (1)       # Dataset
│── 📄 README.md                      # Project Documentation
```

---

## 🗂 Dataset Details  
- The dataset contains **7,385 instances** with **12 features**, including:  
  - `Engine size`  
  - `Cylinders`  
  - `Fuel consumption (city/highway/combined)`  
  - `Transmission type`  
  - `CO₂ Emissions` (Target Variable)  

- **Source:** [Dataset Link (if available)]  

---

## 📌 Data Preprocessing  
✅ **Handled missing values & duplicates**  
✅ **Encoded categorical variables** (fuel type, transmission)  
✅ **Standardized numerical features** using `StandardScaler`  
✅ **Split dataset into 80% train & 20% test**  

---

## 📈 Model Selection  
We tested multiple regression models:  

| Model                 | MAE  | R² Score |
|----------------------|------|---------|
| Linear Regression    | 12.45 | 0.79    |
| KNN Regressor       | 6.38  | 0.92    |
| **Random Forest**  | **3.33** | **0.98** |
| SVR                 | 9.12  | 0.87    |

✅ **Random Forest achieved the best performance** with the **lowest error (MAE: 3.33, RMSE: 8.75) and highest R² score (0.98).**  

---

## 🚀 Deployment  
- **Frontend:** **Streamlit** for interactive web-based input  
- **Model Backend:** **Random Forest Regressor** trained on cleaned dataset  
- **Deployment:** Runs locally via Streamlit  

To run the app:  
```bash
streamlit run co2_dep_group4.py
```

---

## 📉 Results & Insights  
- **Larger engines and higher fuel consumption lead to more CO₂ emissions.**  
- **Smaller vehicles (compact, midsize) have lower emissions.**  
- **Hybrid and electric cars produce significantly less CO₂.**  
- **Random Forest is the most reliable model for prediction.**  

---

## 🛠 Technologies Used  
🔹 Python  
🔹 NumPy, Pandas, Matplotlib  
🔹 Scikit-Learn (Machine Learning)  
🔹 Streamlit (Web App Deployment)  
🔹 Pickle (Model Saving)  

---

## 🏆 Challenges Faced  
🛧 **Handling Missing & Duplicate Data**  
🛧 **Feature Selection & Scaling**  
🛧 **Hyperparameter Tuning for Better Accuracy**  
🛧 **Model Deployment & UI Design**  




## ⭐ How to Contribute  
1. **Fork** the repository  
2. **Clone** the repository:  
   ```bash
   git clone https://github.com/your-username/CO2-Emission-Prediction-Group4.git
   ```
3. **Make improvements & push changes**  
4. **Submit a pull request!**  

🚀 **Star this repo if you found it useful!** ⭐  

---

### 🔥 **Thank You for Visiting Our Project!** 🔥  

