# 🌍 Air Quality Index (AQI) Prediction  

## 📌 Project Overview  
This project predicts the **Air Quality Index (AQI)** using various air pollutants such as PM2.5, PM10, NO₂, SO₂, CO, Benzene, Toluene, NH₃, and Xylene.  
The goal is to build a **machine learning-based model** that helps in monitoring and forecasting air quality, which can support decision-making for public health and environmental management.  

---

## 🎯 Objectives  
- Analyze the effect of different pollutants on AQI.  
- Perform data cleaning, preprocessing, and exploratory data analysis (EDA).  
- Apply multiple ML/DL models for AQI prediction.  
- Evaluate models based on accuracy and error metrics.  
- Provide a reliable system for forecasting AQI.  

---

## 🛠 Tools & Technologies  
- **Language:** Python  
- **Libraries:** NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn, XGBoost, TensorFlow/Keras  
- **Platform:** Jupyter Notebook / Google Colab  
- **Dataset:** Air Quality Data (CSV file)  

---

## 🔬 Methodology  
1. **Data Collection** – Air Quality Dataset (CSV).  
2. **Data Preprocessing** – Handling missing values, removing duplicates, treating outliers.  
3. **Exploratory Data Analysis (EDA)** – Visualization of pollutants, correlation heatmaps.  
4. **Feature Engineering** – Selecting key pollutants impacting AQI.  
5. **Model Building** –  
   - Linear Regression  
   - Decision Tree Regressor  
   - Random Forest Regressor  
   - Gradient Boosting  
   - XGBoost Regressor  
   - LSTM Neural Network  
6. **Model Evaluation** – R² Score, MAE, RMSE.  
7. **Best Model Selection** – XGBoost performed best.  

---

## 📊 Results & Performance  
| Model            | Accuracy (%) | RMSE   | Processing Time | Complexity |
|------------------|--------------|--------|-----------------|------------|
| Random Forest    | ~95%         | ~10–12 | Fast            | Low        |
| XGBoost          | ~96–97%      | ~8–9   | Fast/Moderate   | Medium     |
| LSTM Network     | ~94–95%      | ~11–13 | Moderate/Slow   | High       |

✅ **Final Best Model: XGBoost**  
- **R² Score:** 0.97  
- **RMSE:** ~9  

---

## 🏆 Key Contributions (Improvisations)  
- Improved dataset quality by handling missing values & outliers.  
- Selected key pollutant features to boost performance.  
- Tuned Random Forest & XGBoost hyperparameters to improve accuracy.  
- Experimented with LSTM for sequential learning.  
- Suggested future scope: real-time AQI prediction using IoT sensor data.  

---

## 📸 Sample Outputs  
- Correlation Heatmap between pollutants.  
- Predicted vs Actual AQI comparison.  
- Model accuracy results.  

---

## 📌 Conclusion  
- Machine learning models can effectively predict AQI from pollutants data.  
- Ensemble models (**Random Forest & XGBoost**) performed best.  
- Best results achieved: **97% Accuracy, RMSE ~9**.  
- Project demonstrates the role of AI/ML in solving real-world environmental problems.  

---

## 🚀 Future Scope  
- Real-time AQI prediction using IoT sensor data.  
- Integration with mobile/web dashboards for public awareness.  
- Deployment as an API for smart city applications.  
