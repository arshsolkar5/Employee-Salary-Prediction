# Employee-Salary-Prediction
Employee Salary Prediction Using Linear Regression, Random Forest, and XGBoost with SHAP Explainability
---

## 💼 Employee Salary Prediction using Machine Learning

This project demonstrates the practical use of supervised machine learning models to **predict employee salaries** based on features such as experience, education, job role, department, and performance.

### 🚀 Key Features

* Supports **real-time CSV uploads** for salary predictions.
* Models used: **Linear Regression**, **Random Forest**, **XGBoost**.
* Includes **SHAP-based visual explanations** for transparency.
* Generates a **downloadable PDF report** with prediction results.
* Deployed via **Ngrok** for live access.
* Built using **Streamlit**, **scikit-learn**, **SHAP**, **matplotlib**, and **Plotly**.

### 📂 Files in This Repo

* `Employee Salary Prediction Project.ipynb` – Main Jupyter notebook for model building and evaluation.
* `complex_employee_data.csv` – Dataset used for training.
* `app.py` – Streamlit app source code for real-time prediction.
* `models/` – Folder containing saved models (`.pkl` files).
* `report_utils/` – Utility functions for PDF generation and visualizations.

### ⚙️ How to Run Locally

```bash
# Clone the repository
git clone https://github.com/your-username/employee-salary-prediction.git
cd employee-salary-prediction

# Install dependencies
pip install -r requirements.txt

# Run the Streamlit app
streamlit run app.py
```

### 📊 Sample Output

* Predicted salary for uploaded employee data
* SHAP explanations
* Bar charts and comparison plots
* Downloadable report in PDF format

### 📌 Demo

App is deployed using **Ngrok**. Run the following to expose the local server:

```bash
ngrok http 8501
```

---


