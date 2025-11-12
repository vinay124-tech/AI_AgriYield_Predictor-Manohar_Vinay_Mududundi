# 🌾 AgriYield Predictor: Forecasting Crop Yield Using Environmental and Soil Data

---

## 📘 Project Overview

The **AgriYield Predictor** is an AI-powered machine learning system that forecasts crop yield using environmental and soil-based data such as rainfall, temperature, humidity, soil type, and nutrient content. This project aims to support **farmers, agronomists, and agricultural planners** in optimizing crop production decisions through data-driven insights.

---

## 🎯 Objective

Develop a **predictive model** capable of accurately estimating crop yield based on historical data, environmental conditions, and soil characteristics. The model enhances agricultural planning and sustainability by leveraging modern AI and data science techniques.

---

## 🧩 Key Outcomes

* Learn data preprocessing and feature engineering on agricultural datasets.
* Train and compare multiple regression models for yield prediction.
* Evaluate performance using key regression metrics (RMSE, MAE, R²).
* Interpret models using explainability tools (e.g., SHAP values).
* Deliver a **functional prototype** with user-friendly input options and yield prediction output.

---

## 🌱 Datasets Used

| Source                                        | Description                           | Link                                                                                         |
| --------------------------------------------- | ------------------------------------- | -------------------------------------------------------------------------------------------- |
| **FAO Crop Production Dataset**               | Global crop yield data across regions | [FAO](https://www.fao.org/faostat/en/#data/QCL)                                              |
| **Kaggle Crop Recommendation Dataset**        | Environmental & soil data             | [Kaggle Dataset 1](https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset) |
| **Indian Govt. Open Agriculture Data Portal** | Region-wise agricultural data         | [Data.gov.in](https://www.data.gov.in/sector/agriculture)                                    |
| **US Weather Events Dataset**                 | Weather data for feature augmentation | [Kaggle Dataset 2](https://www.kaggle.com/datasets/sobhanmoosavi/us-weather-events)          |
| **NOAA Historical Weather Data**              | Global weather conditions             | [NOAA](https://www.ncei.noaa.gov/)                                                           |

---

## 🧠 System Architecture

The architecture consists of the following layers:

1. **Data Collection Layer:** Integrates weather, soil, and yield datasets from open sources.
2. **Preprocessing Layer:** Cleans and merges datasets, handles missing values, normalizes features.
3. **Feature Engineering:** Encodes categorical variables, derives new features (e.g., growing season index, heat days).
4. **Model Training Layer:** Implements regression algorithms such as Random Forest, XGBoost, and Linear Regression.
5. **Prediction & Visualization:** UI for real-time yield prediction and interpretability visualizations.

---

## 🧮 Evaluation Metrics

| Metric                                | Description                                                      |
| ------------------------------------- | ---------------------------------------------------------------- |
| **R² (Coefficient of Determination)** | Measures how well future samples are likely to be predicted.     |
| **RMSE (Root Mean Squared Error)**    | Penalizes large prediction errors.                               |
| **MAE (Mean Absolute Error)**         | Average absolute difference between actual and predicted values. |

---

## 🧰 Tools & Technologies

**Programming Language:** Python 3.8+

**Libraries & Frameworks:**

* Data Handling: `pandas`, `numpy`
* Visualization: `matplotlib`, `seaborn`, `plotly`
* Machine Learning: `scikit-learn`, `xgboost`, `lightgbm`
* Model Explainability: `SHAP`, `eli5`
* Web Framework: `Flask` or `Django`
* Frontend: `HTML`, `CSS`, `JavaScript`, `Bootstrap`

**Development Tools:**

* IDEs: Jupyter Notebook, VS Code
* Version Control: Git & GitHub
* Deployment: Heroku, AWS, or Google Cloud Platform

---

## 💻 How to Run

1. **Clone the repository:**

   ```bash
   git clone https://github.com/vinay124-tech/AI_AgriYield_Predictor-Manohar_Vinay_Mududundi.git
   cd AI_AgriYield_Predictor-Manohar_Vinay_Mududundi
   ```

2. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run Jupyter notebooks:**

   ```bash
   jupyter lab
   ```

   Execute notebooks in `notebooks/` sequentially: EDA → Preprocessing → Model Training.

4. **Run Web UI:**

   ```bash
   python app.py
   ```

5. **Access the web app:**
   Visit `http://localhost:5000` to input data and view predicted yields.

---

## 📄 License

This project is licensed under the **MIT License** — see the `LICENSE` file for details.

---

## 👨‍💻 Author

**Manohar Vinay Mududundi**
Integrated Dual Degree (B.Tech + M.Tech), Electronics and Communication Engineering
Focus: AI, ML, Signal Processing, and Data Science
GitHub: [vinay124-tech](https://github.com/vinay124-tech)

---

### 🏁 Future Enhancements

* Incorporate **deep learning models (LSTM, GRU)** for spatio-temporal yield forecasting.
* Add **satellite imagery-based features** (NDVI, EVI).
* Deploy as a **progressive web app (PWA)** with interactive charts.

---

> *“Empowering agriculture with data-driven intelligence — bridging AI and sustainability.”*
