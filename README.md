# 🌍 Air Quality Index (AQI) Prediction  

## 📌 Introduction
Air pollution is a major environmental challenge affecting human health and ecosystems.  
This project focuses on **analyzing and predicting air quality in India** using pollutant data collected from multiple monitoring stations.

Using **machine learning classification techniques**, the project identifies pollution trends, classifies air quality levels, and highlights high-risk regions to support data-driven decision making.

---

## 📊 Dataset Description
- **Records:** 1358
- **Region:** India
- **Key Features:**
  - Location: Country, State, City, Station
  - Coordinates: Latitude, Longitude
  - Pollutants: PM10, NH3, OZONE, etc.
  - Statistics: Minimum, Maximum, Average pollutant levels
  - Timestamp: Last Update

### 🎯 Target Variable
`pollutant_avg` categorized into:
- **Low** (0–50)
- **Moderate** (50–100)
- **High** (>100)

---

## 🧹 Data Preprocessing
- Handled missing values using **mean imputation**
- Converted date column to **datetime**
- Encoded categorical features using **Label Encoding**
- Removed unnecessary columns
- Split data into **80% training** and **20% testing**

---

## 🤖 Machine Learning Models Implemented

| Algorithm | Accuracy |
|---------|----------|
| KNN | 61.4% |
| SVM | 61.4% |
| Decision Tree | 73.9% |
| **Random Forest** | **77.57%** ⭐ |
| Naive Bayes | 70.22% |
| Logistic Regression | 51.84% |

✅ **Random Forest** achieved the highest accuracy and performed best overall.

---

## 📈 Model Evaluation
- Accuracy Score
- Precision, Recall, F1-Score
- Classification Reports
- Comparison across multiple algorithms

---

## 📊 Data Visualization
The project includes:
- Accuracy comparison bar plot
- Pollutant average distribution histogram
- Correlation heatmap
- Pollutant frequency count plot
- Geographical scatter plot of monitoring stations
- Box plots showing pollutant variability and outliers

---

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-Learn
- **Visualization:** Matplotlib, Seaborn
- **Environment:** Jupyter Notebook

---


## 🚀 Future Scope  
- Real-time AQI prediction using IoT sensor data.  
- Integration with mobile/web dashboards for public awareness.  
- Deployment as an API for smart city applications.  
