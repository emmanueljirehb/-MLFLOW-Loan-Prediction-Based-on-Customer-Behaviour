# -MLFLOW-Loan-Prediction-Based-on-Customer-Behaviour

# 🏦 Loan Prediction Based on Customer Behavior using MLflow

This project is a Machine Learning-based solution for predicting loan approval using customer behavior data. It integrates **MLflow** to track experiments, log models, and streamline the entire ML lifecycle. The model uses various customer features (e.g., credit score, income, past history) to determine the likelihood of loan approval.

---

## 📌 Project Highlights

- ✅ Built with **Scikit-learn**, **Pandas**, **NumPy**, and **Matplotlib**
- ⚙️ End-to-end ML pipeline with:
  - Data preprocessing
  - Feature engineering
  - Model training & evaluation
  - MLflow logging and model registration
- 📊 Model evaluation metrics: **Accuracy**, **Confusion Matrix**, and more
- 📁 Structured code for experimentation and reproducibility

---

## 🧪 Workflow Overview

### 1. Data Preprocessing
- Handle missing values
- Encode categorical variables
- Normalize numerical columns

### 2. Feature Engineering
- Extract relevant features from behavioral data
- Balance dataset if necessary

### 3. Model Building
- Trained using Random Forest Classifier
- Hyperparameter tuning
- Train/test split

### 4. MLflow Integration
- Tracks:
  - Parameters
  - Metrics
  - Model versions
- Model logging with `mlflow.sklearn.log_model()`
- Run comparison in MLflow UI

---

## 🔧 Installation & Setup

### 🧰 Prerequisites

Make sure you have the following installed:
- Python 3.8+
- pip

### ⚙️ Create Virtual Environment (Optional)

```bash
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
```

### 📦 Install Dependencies

pip install -r requirements.txt

### 🚀 Run Jupyter Notebook

jupyter notebook

### 📈 Example Results

| Metric       | Value                  |
| ------------ | ---------------------- |
| Accuracy     | \~0.82                 |
| Model        | RandomForestClassifier |
| Logging Tool | MLflow                 |


# 📦 Project Dependencies

This document outlines the Python dependencies required to run the **Loan Prediction Based on Customer Behavior** project. All packages listed are included in the `requirements.txt` file and are essential for:

- Data preprocessing
- Model training & evaluation
- Experiment tracking with MLflow
- Visualizations
- Notebook development

---

## 🔧 Required Libraries

| Package        | Version      | Purpose                                                   |
|----------------|--------------|-----------------------------------------------------------|
| **numpy**      | ≥ 1.21.0     | Numerical operations and matrix handling                  |
| **pandas**     | ≥ 1.3.0      | Data manipulation and DataFrame support                   |
| **scikit-learn** | ≥ 1.0.0    | Machine learning models and utilities                     |
| **matplotlib** | ≥ 3.4.0      | Basic data visualization                                  |
| **seaborn**    | ≥ 0.11.0     | Statistical plots built on top of matplotlib              |
| **mlflow**     | ≥ 2.0.0      | Experiment tracking, logging, and model registry          |
| **notebook**   | ≥ 6.4.0      | Run and manage Jupyter Notebooks                          |
| **ipykernel**  | ≥ 6.0.0      | Kernel for Jupyter Notebook integration                   |

---

## ➕ Optional Packages

You may need these depending on your modeling and dataset needs:

| Package           | Use Case                                      |
|-------------------|-----------------------------------------------|
| `xgboost`         | Advanced boosting models                      |
| `lightgbm`        | Fast gradient boosting for large datasets     |
| `imbalanced-learn`| Handle imbalanced datasets (e.g., SMOTE)      |

To include them, simply uncomment the relevant lines in `requirements.txt`.

---

## 💻 How to Use

### 1. 📁 Create a Virtual Environment (Recommended)

```bash
python -m venv venv
source venv/bin/activate  # Linux/macOS
# OR
venv\Scripts\activate     # Windows
```


### 💡 Future Improvements

Model deployment using Flask/FastAPI

Dockerization for reproducibility

Integrate with streamlit for a user-facing dashboard

Automated model retraining with new data

### 🤝 Contributing

Contributions are welcome! Please fork the repo and submit a pull request.

## 👨‍💻 Author
## Emmanuel Jireh B







