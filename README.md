# Live-Traffic-Management-System🚦

 AI-powered real-time traffic prediction, congestion detection & dashboard visualization.<br/>
This project provides a complete real-time traffic management system that predicts congestion using machine learning, visualizes live traffic flow, and assists city/roadway authorities in decision-making. It integrates feature engineering, a trained Isolation Forest model, and a modern dashboard for visualization.

![Traffic Prediction Map](Traffic.jpeg)

## Key Features
##  1. Machine Learning–based Congestion Prediction
Uses Isolation Forest to detect anomalies in traffic patterns<br/>
Predicts high, medium, and low congestion zones<br/>
Scaler applied consistently across pipeline<br/>

##  2. Data Preprocessing & Feature Engineering
Extracts volume, density, speed, weather influence, and time-based features<br/>
Outlier cleaning & normalization<br/>
Automatic feature scaling and saving for inference<br/>

##  3. Interactive Dashboard
Live map heat visualization<br/>
Congestion severity indicators<br/>
Trend charts and zone-based predictions<br/>
Filter by time, road ID, city area<br/>

##  4. Real-time Update Ready
Architecture prepared for REST API integration<br/>
Supports streaming data from sensors, CCTV, IoT devices<br/>
##  Tech Stack
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
Streamlit

#  How to Run the Project

1️⃣ Run Preprocessing / EDA Script on colab
Traffic.py<br/>
2️⃣ Launch Dashboard<br/>
Streamlit:
streamlit run dashboard/app.py
