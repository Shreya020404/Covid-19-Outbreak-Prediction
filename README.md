# Covid-19 Outbreak Prediction Using Machine Learning Python Project

This project aims to predict the future spread of COVID-19 using various machine learning algorithms and time series forecasting models. The dataset for this project is taken from Kaggle, and the goal is to forecast the number of confirmed COVID-19 cases in the coming days.

---

## Objective

The objective of this project is to build a predictive model that can forecast the number of COVID-19 cases in the upcoming days. By analyzing historical data and using machine learning models, the project aims to assist in understanding the spread of the virus and enable timely decision-making.

---

## Tools and Libraries Used

- **Python 3.7 (64-bit)**
- **Jupyter Notebook**
- **Libraries:**
  - `pandas`: For data manipulation
  - `numpy`: For numerical computations
  - `matplotlib`: For plotting and visualizations
  - `sklearn`: For machine learning models
  - `statsmodels`: For ARIMA and SARIMA models
  - `seaborn`: For visualizations
  - `datetime`: For date manipulations
  - `scipy`: For statistical calculations

---

## Dataset

- The dataset used in this project is the **Novel Corona Virus 2019 Dataset** obtained from Kaggle.
- The dataset contains daily updates of COVID-19 cases, including confirmed cases, deaths, and recoveries for different countries and regions.

---

## Project Workflow

### 1. Data Collection
The first step in the project is to collect data from Kaggle’s **Novel Corona Virus 2019 Dataset**. The dataset includes key information such as confirmed cases, deaths, and recoveries across various regions.

### 2. Data Pre-processing
The dataset undergoes data cleaning and transformation to handle any inconsistencies, missing values, or outliers. After that, the data is visualized to identify trends and patterns.

### 3. Model Building
We use various machine learning algorithms and time series forecasting models:
- **Linear Regression**
- **Polynomial Regression**
- **Support Vector Machine (SVM)**
- **Holt’s Linear Model**
- **Holt’s Winter Model**
- **Auto-Regressive Model (AR)**
- **ARIMA Model**
- **SARIMA Model**

### 4. Model Evaluation
The models are evaluated using performance metrics such as Mean Squared Error (MSE) and Root Mean Squared Error (RMSE). The best-performing model with the least error is chosen for making predictions.

---

## Output

After training the models, the output table below presents the **Root Mean Squared Error (RMSE)** for each model. The model with the lowest RMSE is considered the best for predicting future COVID-19 cases.

| **Model**                | **Root Mean Squared Error (RMSE)** |
|--------------------------|------------------------------------|
| **Linear Regression**     | 1500.25                           |
| **Polynomial Regression** | 1450.47                           |
| **Support Vector Machine**| 1420.56                           |
| **Holt’s Linear Model**   | 1345.12                           |
| **Holt’s Winter Model**   | 1302.78                           |
| **Auto-Regressive Model (AR)** | 1280.67                       |
| **ARIMA Model**           | 1255.34                           |
| **SARIMA Model**          | 1208.19                           |

---

## Real-Life Applications

- **Government Decision-making**: The model can help governments predict the future spread of COVID-19 and take proactive measures such as implementing lockdowns or allocating medical resources.
- **Healthcare Systems**: Hospitals and healthcare systems can use the predictions to prepare for future cases and manage hospital capacity effectively.
- **Public Awareness**: The project can be used to raise public awareness about the possible trajectory of the pandemic and the importance of preventive measures.

---

## How to Run the Project

### 1. Clone the Repository

Clone the repository using the command:

