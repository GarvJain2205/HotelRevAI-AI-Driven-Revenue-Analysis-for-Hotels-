# 🏨 HotelRevAI – AI-Driven Revenue Analysis for Hotels

**HotelRevAI** is an AI-powered analytics platform designed to help hotels optimize revenue, forecast demand, and analyze guest behavior.
The project integrates **machine learning models, business intelligence dashboards, and a web-based analytics application**.

The analytics interface is deployed as a **web dashboard using Streamlit**, which runs as a lightweight web server and allows users to interact with forecasting models and booking analytics through a browser.

---

# 🔍 Key Features

* 📊 **Revenue & Occupancy Analytics**

  * KPIs including ADR, RevPAR, occupancy rate, and booking trends

* 📈 **Demand & Revenue Forecasting**

  * Time-series forecasting using **Prophet** and **ARIMA**

* 👥 **Guest Behavior Analysis**

  * Segmentation of guests and booking patterns

* ❌ **Cancellation Risk Prediction**

  * Machine learning model using **Random Forest** to identify high-risk cancellations

* 🌍 **Branch Performance Comparison**

  * Multi-location hotel analytics

* 💡 **Revenue Strategy Insights**

  * Pricing recommendations and demand patterns

---

# 🌐 Web Dashboard (Streamlit Web Server)

The project includes an **interactive web dashboard built with Streamlit**, which runs a local web server and provides real-time analytics and forecasting tools.

Users can access the dashboard via a browser to:

* Forecast **future occupancy and demand**
* Predict **revenue trends**
* Identify **high-risk booking cancellations**
* Explore **hotel performance metrics**

Architecture:

```
Hotel Dataset
      │
      ▼
Data Processing & ML Models (Python)
      │
      ▼
Streamlit Web Server
      │
      ▼
Interactive Hotel Analytics Dashboard
```

---

# 🧠 Tech Stack

* **Python** – Data processing and machine learning
* **Streamlit** – Web server & interactive analytics dashboard
* **Power BI** – Business intelligence dashboards
* **Prophet / ARIMA** – Time-series forecasting
* **Random Forest** – Cancellation prediction model
* **Pandas / NumPy / Scikit-learn** – Data analysis & ML

---

# 📁 Project Modules

1️⃣ **Data Modeling & ETL**

* Data cleaning and preprocessing
* Feature engineering for ML models

2️⃣ **Occupancy & Revenue Analytics**

* ADR, RevPAR, occupancy KPIs

3️⃣ **Guest Behavior Analysis**

* Segmentation and booking pattern insights

4️⃣ **Forecasting Engine**

* Occupancy and revenue prediction models

5️⃣ **Cancellation Risk Detection**

* ML classification for booking cancellation probability

6️⃣ **Interactive Web Dashboard**

* Streamlit application for real-time analytics

---

# 🚀 Running the Web Application

Install dependencies:

```
pip install -r requirements.txt
```

Run the Streamlit web server:

```
streamlit run app.py
```

The dashboard will be available at:

```
http://localhost:8501
```

---

# 📌 Project Goal

HotelRevAI helps hotel management teams make **data-driven pricing and occupancy decisions** by combining predictive analytics with interactive dashboards accessible through a web-based interface.

If you want, I can also show you **how to add a “Live Demo” link (Streamlit Cloud deployment)** so the form reviewer can actually **open your dashboard in the browser**, which increases your chances of selection.
