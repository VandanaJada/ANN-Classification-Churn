# ANN Churn Prediction Model

This repository contains a project for predicting customer churn using an Artificial Neural Network (ANN). The model is deployed as an interactive web application using [Streamlit](https://streamlit.io/), allowing users to make predictions easily.

---

## Features

- **Data Preprocessing**: Handles missing data, categorical encoding, scaling, and splitting datasets.
- **Model Training**: Trains an ANN model for churn prediction with a robust architecture.
- **Interactive UI**: Deployed via Streamlit, providing an easy-to-use interface for making predictions.
- **Visualization**: Displays insights from the data, such as distributions, correlations, and feature importance.

---

## Demo

Access the deployed Streamlit app here: [ann-classification-churn](https://ann-classification-churn-ieq69ghfhxbpgfisrr8xu4.streamlit.app/)
![image](https://github.com/user-attachments/assets/392bcc8b-31d3-4de8-8b9b-e1e49f7cb30e)


---

## Project Structure

```plaintext
.
├── app.py                 # Main Streamlit application
├── model/                 # Saved ANN model files
│   ├── model.h5
│   └── scaler.pkl
├── data/                  # Sample dataset for testing
│   └── churn_data.csv
├── requirements.txt       # Required Python libraries
├── README.md              # Project documentation
└── utils/                 # Helper functions for data preprocessing and prediction
    ├── preprocessing.py
    └── prediction.py
