

# Employee Salary Prediction using Machine Learning

**Employee Salary Prediction Using Linear Regression, Random Forest, and XGBoost with SHAP Explainability**

This project showcases the application of supervised machine learning techniques to **predict employee salaries** based on relevant features such as **experience**, **education**, **job role**, **department**, and **performance rating**.

The project is developed and tested on **Google Colab**, where it runs best due to seamless support for required libraries and Ngrok-based deployment. It covers the full ML pipeline including preprocessing, model training, SHAP-based explainability, and a web app for real-time predictions.

---

## Key Features

- Supports **real-time CSV uploads** for custom salary predictions.
- Implements three supervised regression models:
    - Linear Regression
    - Random Forest Regressor
    - XGBoost Regressor
- Integrates **SHAP (SHapley Additive exPlanations)** for interpretability and model transparency.
- Automatically generates a **downloadable PDF report** including predictions and visualizations.
- **Web application** built using Streamlit and deployed via Ngrok for public access.
- Uses popular libraries: `pandas`, `scikit-learn`, `xgboost`, `SHAP`, `matplotlib`, `plotly`, and `joblib`.

---

## Repository Contents

- `Employee Salary Prediction Project.ipynb`: Google Colab notebook with complete implementation including:
    - Data cleaning and preprocessing
    - Model training and evaluation
    - SHAP visualizations for feature importance
    - PDF report generation
    - Streamlit + Ngrok setup for web interface
- `complex_employee_data.csv`: Dataset used for training and testing. Includes employee attributes like education level, years of experience, job role, department, and performance scores.

---

## How to Run the Project on Google Colab

```bash
# 1. Clone the repository:
https://github.com/arshsolkar5/Employee-Salary-Prediction.git

# 2. Upload the following files to Google Colab:
#    - Employee Salary Prediction Project.ipynb
#    - complex_employee_data.csv

# 3. Install the required Python packages:
!pip install pandas numpy matplotlib seaborn plotly shap scikit-learn xgboost streamlit pyngrok joblib ipywidgets

```

After installation, run all cells in sequence to:

- Train and evaluate the models
- Visualize feature impacts using SHAP
- Launch a web-based prediction dashboard using Streamlit and Ngrok

---

## Output Summary

- Predicted salaries for each input record from uploaded CSV
- SHAP-based visual explanations for model decisions
- Graphical summaries of feature impact and model performance
- Downloadable PDF report with inputs, outputs, and visual insights

---

## Deployment

The web app is deployed using **Ngrok**, which tunnels the **Streamlit interface** running on Colab to the internet. This allows users to interact with the salary prediction dashboard in real-time through a temporary public URL.

---
