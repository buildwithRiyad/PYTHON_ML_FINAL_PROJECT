# CO₂ Emission Prediction Using Machine Learning

## Project Description

This project develops a Machine Learning model to predict future CO₂ emissions using historical environmental and socio-economic data.

The model analyzes country-level CO₂ emission trends from 1990 to 2024 and uses different regression algorithms to identify the best prediction approach.

---

## Dataset

**Source:** Our World in Data (OWID) CO₂ Dataset

**Dataset Details:**
- Time Period: 1990–2024
- Countries: 17 Asian countries
- Total Records: 595 country-year observations

---

## Features Used

The following features were used for CO₂ prediction:

- Population
- GDP
- Primary Energy Consumption
- Energy Consumption per Capita
- CO₂ per Capita
- Methane Emission
- Nitrous Oxide Emission
- Historical CO₂ values using lag features

---

## Machine Learning Models

The following regression models were implemented:

- K-Nearest Neighbors (KNN)
- Random Forest Regressor
- XGBoost Regressor
- Support Vector Machine (SVM)

---

## Model Performance

| Model | Validation RMSE |
|---|---|
| Support Vector Machine | 0.2074 |
| KNN | 0.2192 |
| Random Forest | 0.2263 |
| XGBoost | 0.2266 |

### Best Performing Model

Support Vector Machine (SVM) achieved the best validation performance.

---

## Final Test Results

| Metric | Score |
|---|---|
| MAE | 58.34 Mt |
| RMSE | 194.20 Mt |
| MAPE | 14.76% |
| R² Score | 0.9289 |

---

## Project Workflow
Data Collection
↓
Data Cleaning
↓
Missing Value Handling
↓
Feature Selection
↓
Feature Engineering
↓
Model Training
↓
Model Evaluation
↓
Future CO₂ Forecasting


---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- XGBoost
- Jupyter Notebook
- Google Colab

---

## Installation

Clone the repository:

```bash
git clone <https://github.com/buildwithRiyad/PYTHON_ML_FINAL_PROJECT.git>
How to Run
Open the notebook file:
Python_Final_Project__Updated.ipynb
Upload the dataset:
owid-co2-data.csv
Run all notebook cells to reproduce the results.
Project Structure
CO2-Emission-Prediction/

│
├── Dataset/
│   └── owid-co2-data.csv
│
├── Python_Final_Project__Updated.ipynb
│
│
└── README.md
Future Improvements
Add more countries and updated datasets
Apply deep learning models such as LSTM and Transformer
Include renewable energy and policy-related factors
Develop a web-based CO₂ prediction application