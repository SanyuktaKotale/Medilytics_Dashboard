# Medilytics – Healthcare Revenue Intelligence Dashboard

Medilytics is an advanced healthcare revenue intelligence platform designed to transform raw hospital billing data into actionable financial insights. It empowers hospitals to identify revenue loss, predict risks, and optimize the entire revenue cycle using data analytics and machine learning.

Built using Streamlit, the system provides a structured, role-based interface for stakeholders such as CFOs, RCM teams, department heads, and insurance analysts.

---

## Problem Statement

Healthcare institutions often struggle with:

* Revenue leakage due to mismatches in expected vs received payments
* High claim denial rates caused by documentation and coding issues
* Partial reimbursements from insurance providers
* Lack of department-wise financial visibility
* Delays in claim settlement cycles
* Absence of predictive insights for future revenue
* Undetected anomalies in billing data

---

## Solution Overview

Medilytics addresses these challenges by offering a multi-layer analytics dashboard that combines:

* Descriptive analytics for current performance tracking
* Predictive modeling for risk estimation
* Time-series forecasting for future planning
* Anomaly detection for identifying irregularities

This shifts hospital management from reactive auditing to proactive decision-making.

---

## Key Features

* End-to-end revenue cycle monitoring
* Revenue leakage detection with actionable insights
* Claim denial risk prediction using machine learning
* Revenue forecasting using ARIMA models
* Billing anomaly detection (Z-score based)
* Role-based access control (CFO, RCM, Department, Insurance)
* Interactive dashboards with filters and drill-down analysis
* Export dashboards as PDF

---

## System Modules

### 1. Revenue Integrity Monitoring

Tracks the flow from expected revenue to actual received revenue and identifies leakage points.

### 2. Claim Denial Risk Prediction

Uses logistic regression to estimate the probability of claim rejection before submission.

### 3. Revenue Forecasting Engine

Applies time-series models (ARIMA) to predict future revenue trends.

### 4. Billing Anomaly Detection

Detects abnormal patterns such as:

* High claim gaps
* Payment inconsistencies
* Outliers in billing data

---

## User Roles

| Role            | Responsibility                                       |
| --------------- | ---------------------------------------------------- |
| CFO             | Monitors overall financial performance and KPIs      |
| RCM Team        | Tracks claims, denials, and revenue cycle efficiency |
| Department Head | Views department-specific performance                |
| Insurance Team  | Analyzes payer-wise trends and denial risks          |

---

## Tech Stack

| Layer            | Technology          |
| ---------------- | ------------------- |
| Language         | Python              |
| Data Processing  | Pandas, NumPy       |
| Machine Learning | Scikit-learn        |
| Forecasting      | ARIMA (Statsmodels) |
| Visualization    | Plotly              |
| Dashboard        | Streamlit           |
| Styling          | Custom CSS          |

---

## Data Overview

* 60,000 insurance claim records
* Multiple departments (Cardiology, Neurology, Orthopedics, etc.)
* Multiple insurance types

---

## How to Run the Project

Follow these simple steps to run Medilytics on your system:

### 1. Open Project Folder

Navigate to the project folder (the folder that contains `app.py`).
Open terminal/command prompt in that folder.

### 2. Install Dependencies

Run the following command:
pip install streamlit pandas plotly pillow

### 3. Run the Application

Start the app using:
streamlit run app.py

### 4. Open in Browser

The app will automatically open in your browser.

### 5. Login

Use the username and password available in the `users.csv` file.

---

## Notes

* Make sure Python 3.9 or higher is installed
* Ensure you run the command in the same folder where `app.py` is located
* Internet connection is required only for PDF export feature

---

## Login Credentials

Use the credentials provided in the `users.csv` file to access different roles.

---

## Future Scope

The platform can be further enhanced into a full-scale healthcare intelligence system:

* Real-time integration with hospital billing systems
* AI-based claim validation before submission
* Insurance provider benchmarking
* Multi-hospital analytics and comparison

---
