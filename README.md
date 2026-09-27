# 🚚 Amazon Delivery Time Prediction

A Machine Learning project that predicts **delivery time for e-commerce orders** using customer, delivery, environmental, and traffic-related factors.

The project covers the complete machine learning workflow, including **data preprocessing, exploratory data analysis, feature engineering, model training, experiment tracking with MLflow, and interactive prediction using Streamlit**.

---

## 📌 Project Overview

Accurate delivery-time estimation is important for improving customer experience and optimizing delivery operations.

This project uses historical delivery data to build a machine learning model capable of estimating the expected delivery time based on factors such as:

* Delivery person information
* Customer/order details
* Weather conditions
* Traffic conditions
* Vehicle information
* Delivery-related features

The trained model can be integrated into an interactive **Streamlit application** to provide delivery-time predictions for new inputs.

---

## 🎯 Objectives

* Predict the estimated delivery time of an order.
* Analyze factors affecting delivery duration.
* Perform data preprocessing and feature engineering.
* Compare machine learning approaches for regression.
* Track experiments and model performance using **MLflow**.
* Build an interactive prediction interface using **Streamlit**.

---

## 🔄 Machine Learning Workflow

```text
Raw Dataset
     ↓
Data Cleaning
     ↓
Exploratory Data Analysis
     ↓
Feature Engineering
     ↓
Feature Selection
     ↓
Data Preprocessing
     ↓
Model Training
     ↓
Model Evaluation
     ↓
MLflow Experiment Tracking
     ↓
Streamlit Deployment
     ↓
Delivery Time Prediction
```

---

## 🧠 Machine Learning Approach

The project treats delivery time prediction as a **regression problem**, where the model learns the relationship between order/delivery features and the target delivery time.

The workflow includes:

### 1. Data Preprocessing

* Handling missing values
* Cleaning inconsistent data
* Encoding categorical variables
* Preparing numerical features
* Removing unnecessary columns

### 2. Exploratory Data Analysis

Different visualizations and statistical analyses are used to understand relationships between delivery time and factors such as:

* Traffic
* Weather
* Vehicle condition
* Delivery person characteristics
* Order-related information

### 3. Feature Engineering

Relevant features are transformed and prepared to improve their usefulness for machine learning models.

### 4. Model Training

Regression-based machine learning models are trained to estimate delivery time.

### 5. Model Evaluation

The models are evaluated using regression metrics such as:

* **MAE — Mean Absolute Error**
* **MSE — Mean Squared Error**
* **RMSE — Root Mean Squared Error**
* **R² Score**

---

## 🛠️ Technologies Used

| Technology       | Purpose                                |
| ---------------- | -------------------------------------- |
| Python           | Core programming language              |
| Pandas           | Data manipulation                      |
| NumPy            | Numerical computation                  |
| Matplotlib       | Data visualization                     |
| Seaborn          | Exploratory data analysis              |
| Scikit-learn     | Machine learning & preprocessing       |
| MLflow           | Experiment tracking & model management |
| Streamlit        | Interactive web application            |
| Jupyter Notebook | Model development & experimentation    |

---

## 📊 Key Features

### 🔹 Delivery Time Prediction

Predicts the estimated time required to deliver an order.

### 🔹 Exploratory Data Analysis

Analyzes how different delivery and environmental factors influence delivery time.

### 🔹 Feature Engineering

Transforms raw delivery information into machine-learning-ready features.

### 🔹 MLflow Integration

MLflow is used to track model experiments, parameters, metrics, and model performance.

### 🔹 Streamlit Application

Provides a simple interactive interface where users can enter delivery-related information and receive a predicted delivery time.

---

## 🌦️ Important Prediction Factors

The prediction process considers multiple factors related to the delivery process, including:

* **Delivery Person Age**
* **Delivery Person Rating**
* **Weather Conditions**
* **Traffic Conditions**
* **Vehicle Condition**
* **Order/Delivery characteristics**

These features help the model learn patterns associated with delivery duration.

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/shreya3090/Amazon-Delivery-Time-Prediction.git
cd Amazon-Delivery-Time-Prediction
```

### 2. Install Dependencies

Create a virtual environment if required:

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

Install the required packages:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn mlflow streamlit
```

### 3. Run the Notebook

Open:

```text
Amazon Delivery Time Prediction (1).ipynb
```

Run the notebook to perform:

```text
Data Preprocessing
        ↓
EDA
        ↓
Feature Engineering
        ↓
Model Training
        ↓
Model Evaluation
        ↓
MLflow Tracking
```

### 4. Run the Streamlit Application

If the Streamlit application is included in your local project files:

```bash
streamlit run streamlit_app.py
```

The application will open in your browser.

---

## 📈 Model Evaluation

The project evaluates the regression model using:

### Mean Absolute Error (MAE)

Measures the average absolute difference between actual and predicted delivery time.

### Mean Squared Error (MSE)

Penalizes larger prediction errors more heavily.

### Root Mean Squared Error (RMSE)

Provides the error in the same unit as the target variable.

### R² Score

Measures how well the model explains the variation in delivery time.

> **Note:** Exact performance values should be added here from the final model output rather than using estimated or fabricated numbers.

---

## 🧪 MLflow Experiment Tracking

MLflow is used to track machine learning experiments.

The workflow can include:

```text
Experiment
   │
   ├── Parameters
   ├── Model
   ├── Metrics
   └── Artifacts
```

This makes it easier to compare different experiments and identify the model configuration that performs well.

To start the MLflow UI:

```bash
mlflow ui
```

Then open:

```text
http://127.0.0.1:5000
```

---

## 🖥️ Streamlit Application

The Streamlit interface allows users to provide delivery-related information and obtain an estimated delivery time.

Example workflow:

```text
User Input
   ↓
Feature Preprocessing
   ↓
Trained ML Model
   ↓
Predicted Delivery Time
```

Example:

```text
Weather Condition: Sunny
Traffic Condition: Medium
Vehicle Condition: Good
Delivery Person Rating: 4.7

              ↓

     Predicted Delivery Time
```

---

## 📁 Repository Structure

```text
Amazon-Delivery-Time-Prediction/
│
├── Amazon Delivery Time Prediction (1).ipynb
│
└── README.md
```

If you later add the application and model files, the structure can be expanded to:

```text
Amazon-Delivery-Time-Prediction/
│
├── Amazon Delivery Time Prediction (1).ipynb
├── streamlit_app.py
├── model/
│   └── delivery_model.pkl
├── data/
│   └── dataset.csv
├── requirements.txt
└── README.md
```

---

## 💡 Business Applications

A delivery-time prediction system can help e-commerce platforms with:

* Better delivery-time estimates
* Improved customer experience
* Delivery planning
* Operational optimization
* Identification of factors contributing to delays
* Data-driven logistics decisions

---

## 🔮 Future Improvements

Possible improvements include:

* Integrating real-time traffic data
* Incorporating live weather APIs
* Using real-time GPS/location information
* Testing advanced ensemble models
* Adding real-time delivery tracking
* Deploying the application to a cloud platform
* Adding automated model retraining
* Building an API using FastAPI
* Containerizing the application using Docker

---

## 👩‍💻 Author

**Shreya Sachan**

B.Tech CSE – Cyber Security

GitHub:
https://github.com/shreya3090

---

## ⭐ Project

If you find this project useful, consider giving the repository a ⭐.
