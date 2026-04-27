# African Airline Ticket Price Prediction (End-to-End ML)

---

## Overview

This project builds a full machine learning pipeline to predict airline ticket prices for major African routes.  

It simulates a real-world pricing problem where airlines and travel platforms need to estimate ticket prices based on multiple factors such as route, timing, and demand patterns.

The goal is to:
- Predict airline ticket prices using machine learning  
- Understand key drivers of price variation  
- Demonstrate an end-to-end ML workflow from data generation to deployment  

---

## Problem Statement

Airline ticket prices are highly dynamic and influenced by multiple factors including:

- Route and distance  
- Booking timing  
- Airline type  
- Demand fluctuations  

Traditional pricing methods can be inconsistent and difficult to scale.

This project builds a machine learning model to support:
- Price prediction  
- Better pricing insights  
- Data-driven decision-making  

---

## Dataset

A synthetic dataset was generated to simulate airline ticket pricing in an African context.

Features include:

- **airline** — Airline operator  
- **source_city** — Departure location  
- **destination_city** — Arrival location  
- **departure_time** — Time of departure  
- **stops** — Number of stops  
- **flight_duration** — Duration of flight  
- **days_left** — Days before departure  
- **price** — Target variable  

---

## Methodology

### 1. Data Generation
- Simulated realistic airline pricing data  
- Incorporated relationships between time, distance, and demand  

---

### 2. Exploratory Data Analysis (EDA)
- Analyzed price distribution  
- Examined relationships between features and ticket price  
- Identified patterns across routes and booking windows  

---

### 3. Data Preprocessing
- Handled categorical variables using encoding  
- Prepared dataset for model training  
- Split into training and testing sets  

---

### 4. Model Development

A **Random Forest Regressor** was used to predict ticket prices.

Why this model:
- Handles non-linear relationships well  
- Performs strongly on structured data  
- Requires minimal feature scaling  

---

### 5. Model Evaluation

The model was evaluated using:

- **Mean Absolute Error (MAE)**  
- **Root Mean Squared Error (RMSE)**  
- **R² Score**  

These metrics help assess prediction accuracy and model performance.

---

## Model Deployment

The model was deployed using **Streamlit**, enabling:

- Interactive user inputs  
- Real-time price predictions  
- Simple UI for demonstration  

Users can input flight details and receive predicted ticket prices instantly.

---

## Key Insights

- Ticket prices increase as departure date approaches  
- Direct flights tend to be more expensive than multi-stop flights  
- Certain routes consistently show higher pricing due to demand  
- Airline choice significantly influences price variation  

---

## Business Application

This project demonstrates how machine learning can support:

- Dynamic pricing strategies  
- Travel platform recommendations  
- Demand forecasting  
- Revenue optimization  

Predictive analytics plays a key role in improving pricing decisions in modern travel systems :contentReference[oaicite:0]{index=0}  

---

## Tech Stack

- Python (Pandas, NumPy)  
- Scikit-learn  
- Matplotlib / Seaborn  
- Streamlit  
- Google Colab  

---

## Project Structure


```bash
airline-price-prediction/
│
├── notebooks/
│   └── airline_price_model.ipynb
├── app/
│   └── streamlit_app.py
├── data/
├── README.md
└── requirements.txt


---

## Live Project

🔗 https://colab.research.google.com/drive/1ZY5zfw3YZl4cIuyK1V-6o-tkO6PTsnUc?usp=sharing  

---

## Future Improvements

- Use real-world airline datasets  
- Improve feature engineering (seasonality, demand signals)  
- Hyperparameter tuning  
- Deploy as a full web application  

---

## Author

**Clyde Wawire**  
Data Analyst | Operational & Business Analytics  

---

## Final Note

This project reflects my approach to analytics:

- Start with a real business problem  
- Build structured, end-to-end solutions  
- Focus on insights and decision-making—not just models  
