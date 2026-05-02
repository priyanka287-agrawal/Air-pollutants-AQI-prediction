# 🌍 AIR QUALITY VISUALIZER AND AQI FORECASTING USING HYBRID MACHINE LEARNING MODELS

<div align="center">

### 🔬 Hybrid AQI Forecasting Framework using XGBoost, Random Forest, LSTM & ARIMA

*A Research-Oriented Hybrid Framework for Accurate and Interpretable Air Quality Prediction*

</div>

---

# 📌 Project Overview

This project presents a **Hybrid Air Quality Index (AQI) Forecasting Framework** that integrates **Machine Learning, Deep Learning, and Time-Series Modeling** techniques for accurate AQI prediction and interpretation.

The proposed framework combines:

* ⚡ **XGBoost** for pollutant prediction and nonlinear feature learning
* 🌲 **Random Forest Regressor (RFR)** for robust AQI estimation
* 🧠 **LSTM Networks** for capturing temporal dependencies in time-series data
* 📈 **ARIMA Residual Modeling** for residual error correction
* 🔍 **SHAP Analysis** for explainable and interpretable predictions

The system follows **CPCB-approved AQI breakpoint calculations** and evaluates pollutant behavior using statistical analysis and visualization techniques.

---

# ✨ Key Highlights

✅ CPCB-based AQI evaluation and forecasting
✅ Pollutant prediction using XGBoost
✅ Hybrid ensemble AQI prediction framework
✅ Residual correction using ARIMA modeling
✅ SHAP-based pollutant contribution analysis
✅ Correlation heatmap and trend visualization
✅ Statistical performance evaluation using MSE, RMSE, and R²
✅ Research-oriented and interpretable forecasting framework

---

# 🧭 Workflow Pipeline

```text
Raw Dataset
     ↓
Data Preprocessing & Interpolation
     ↓
Pollutant Prediction using XGBoost
     ↓
CPCB AQI Sub-Index Calculation
     ↓
AQI Prediction using:
  • Random Forest
  • XGBoost
  • LSTM
     ↓
Ensemble Averaging
     ↓
Residual Extraction
     ↓
ARIMA Residual Modeling
     ↓
Final Hybrid AQI Forecast
     ↓
SHAP Explainability & Visualization
```

---

# 📂 Repository Structure

```bash
├── Dataset/
├── Models/
├── Visualization/
├── Results/
├── SHAP_Analysis/
├── Hybrid_AQI_Model.ipynb
├── requirements.txt
└── README.md
```

---

# 🛠️ Technologies Used

| Category             | Tools & Libraries       |
| -------------------- | ----------------------- |
| Programming          | Python                  |
| Machine Learning     | XGBoost, Random Forest  |
| Deep Learning        | TensorFlow, Keras, LSTM |
| Time-Series Modeling | ARIMA, Auto-ARIMA       |
| Visualization        | Matplotlib, Seaborn     |
| Explainability       | SHAP                    |
| Data Handling        | Pandas, NumPy           |
| Preprocessing        | Scikit-learn            |

---

# 📊 Major Visualizations

📌 Correlation Matrix & Heatmap
📌 Actual vs Predicted AQI Graphs
📌 Residual Plot with Zero Baseline
📌 Pollutant Trend Analysis
📌 SHAP Summary Plot
📌 SHAP Dependence Plot
📌 AQI Forecasting Trend (2023–2029)

These visualizations assist in understanding pollutant behavior, model performance, feature importance, and temporal AQI trends.

---

# 📈 Model Evaluation Metrics

The proposed models were evaluated using standard statistical metrics:

* **Mean Squared Error (MSE)**
* **Root Mean Squared Error (RMSE)**
* **Mean Absolute Error (MAE)**
* **Mean Absolute Percentage Error (MAPE)**
* **Coefficient of Determination (R²)**

Lower MSE and RMSE values indicate improved prediction accuracy, while higher R² values demonstrate stronger model reliability and performance.

---

# 🚀 Key Findings

* The hybrid ensemble framework improved AQI prediction accuracy compared to individual models.
* Ensemble averaging reduced prediction bias and variance.
* ARIMA residual correction enhanced forecasting stability by capturing remaining temporal patterns.
* SHAP analysis identified **PM2.5 and PM10** as dominant pollutants influencing AQI levels.
* The framework achieved strong predictive performance with lower forecasting errors and higher R² values.

---

# 🔮 Future Scope

Future enhancements may include:

* Integration of meteorological parameters such as humidity, wind speed, and temperature.
* Real-time AQI prediction using IoT-enabled sensor systems.
* Federated or decentralized learning for privacy-preserving distributed forecasting.
* Deployment of web-based and mobile AQI monitoring dashboards.
* Advanced deep learning architectures for improved temporal forecasting.

---

# 👩‍💻 Author

**Priyanka Agrawal**
*Research Enthusiast in Machine Learning, Deep Learning, and Air Quality Forecasting*
