# ⚡ AI Applications in Power Systems 

## 🧾 Project Title
**AI APPLICATIONS IN POWER SYSTEMS-Real-Time Intelligence using ENTSO-E Data**

## 👨‍💻 Author
**Kambala Jaya Krishna**  
Department of Electrical and Electronics Engineering  
**Sri Venkateswara University College of Engineering (SVUCE)**  
📅 **Year**: 2025

---

## 📘 Description

This version of the project focuses on **real-time energy data analytics** using the **ENTSO-E API**. It integrates AI models for:

- ⚠️ Outage prediction (XGBoost)
- 🔮 Load forecasting (LSTM)
- 🚨 Anomaly detection (Isolation Forest)
- 📊 Feature engineering and preprocessing from time-stamped real data

The system is designed to help utility companies and grid operators **anticipate load fluctuations**, **detect failures**, and **improve demand-response strategies**.

---

## 🔗 Real-Time Data Source

- **ENTSO-E Transparency Platform API**
  - Source: [https://transparency.entsoe.eu](https://transparency.entsoe.eu)
  - Data includes: Actual load, solar generation, pricing (simulated in example)

> In this implementation, a simulated response is used for demonstration. Replace with your ENTSO-E API key and query when deploying.

---

## 🛠️ Functional Overview

| Feature                  | Methods / Models                      |
|--------------------------|----------------------------------------|
| **Data Fetching**         | ENTSO-E API via `requests`            |
| **Preprocessing**         | Interpolation, outlier removal, feature extraction |
| **Outage Prediction**     | `XGBoostClassifier` + `RandomizedSearchCV`         |
| **Load Forecasting**      | `LSTM` with `RobustScaler`, `EarlyStopping`        |
| **Anomaly Detection**     | `IsolationForest`                     |

---

## 🧠 Key Techniques

- Time-based interpolation & forward filling (`df.interpolate(method='time')`)
- Feature engineering: `Hour`, `DayOfWeek`, `IsWeekend`
- Outlier removal using Z-score (via `scipy.stats`)
- Stateful LSTM modeling
- RobustScaler (better handling of outliers than MinMaxScaler)
- Grid search for XGBoost hyperparameter tuning

---
this open-source project demonstrates the application of **Artificial Intelligence (AI)** in modern power systems using real-world data. It covers a complete data pipeline—from fetching **live energy data** to **outage detection**, **load forecasting**, and **anomaly detection** using advanced machine learning and deep learning models.

