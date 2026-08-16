# 📊 Multiple Linear Regression

A beginner-friendly **Machine Learning project** that uses Multiple Linear Regression to predict a target value based on multiple input features.

The project includes a trained machine learning model and a Flask web application that allows users to enter input values and get predictions.

## 📌 Project Overview

**Multiple Linear Regression (MLR)** is a supervised machine learning algorithm used to predict a dependent variable using two or more independent variables.

In this project, a dataset containing **CGPA, IQ, and Package** information is used to train a Multiple Linear Regression model.

The trained model is saved as `MLRModel.pkl` and integrated with a Flask web application for making predictions.

## 🎯 Objective

The main objectives of this project are:

* Understand Multiple Linear Regression
* Work with a real-world-style dataset
* Train a regression model using Scikit-learn
* Use multiple independent variables for prediction
* Save the trained model using Pickle
* Create a Flask web application
* Make predictions through a web interface

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Scikit-learn**
* **Flask**
* **Pickle**
* **HTML/CSS**

## 📂 Project Structure

```text
Multiple-Linear-Regression/
│
├── templates/
│   └── index.html
│
├── Cgpa_iq_package.csv
├── MLRModel.pkl
├── app.py
└── README.md
```

## 📄 File Description

| File/Folder           | Description                                           |
| --------------------- | ----------------------------------------------------- |
| `Cgpa_iq_package.csv` | Dataset used for the Multiple Linear Regression model |
| `MLRModel.pkl`        | Trained Multiple Linear Regression model              |
| `app.py`              | Flask application used to make predictions            |
| `templates/`          | Contains HTML files for the web interface             |
| `README.md`           | Project documentation                                 |

## 📊 Dataset

The dataset contains information related to:

* **CGPA**
* **IQ**
* **Package**

The model learns the relationship between the input features and the target variable.

### Input Features

* CGPA
* IQ

### Target

* Package

## 🧮 Multiple Linear Regression

The general equation of Multiple Linear Regression is:

```text
y = b₀ + b₁x₁ + b₂x₂ + ... + bₙxₙ
```

Where:

* `y` = predicted output
* `b₀` = intercept
* `b₁, b₂, ..., bₙ` = coefficients
* `x₁, x₂, ..., xₙ` = input features

For this project, the model uses multiple input features to predict the package.

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Preprocessing
   ↓
Select Input Features
   ↓
Select Target Variable
   ↓
Train Multiple Linear Regression Model
   ↓
Save Trained Model
   ↓
Load Model in Flask
   ↓
User Enters CGPA & IQ
   ↓
Model Makes Prediction
   ↓
Display Predicted Package
```

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/arpitaa1412/Multiple-Linear-Regression.git
```

### 2. Navigate to the Project Folder

```bash
cd Multiple-Linear-Regression
```

### 3. Install Required Libraries

```bash
pip install pandas numpy scikit-learn flask
```

## ▶️ Run the Application

Run the Flask application:

```bash
python app.py
```

After starting the application, open the URL displayed in the terminal.

Usually:

```text
http://127.0.0.1:5000/
```

## 🧪 Making a Prediction

1. Open the web application.
2. Enter the required **CGPA**.
3. Enter the required **IQ**.
4. Submit the form.
5. The trained Multiple Linear Regression model processes the inputs.
6. The predicted package is displayed.

## 💡 Key Learning Outcomes

Through this project, I learned:

* Basics of Multiple Linear Regression
* Difference between single and multiple input features
* Data preprocessing using Pandas
* Model training using Scikit-learn
* Saving and loading ML models using Pickle
* Building a basic ML prediction application
* Integrating Machine Learning with Flask

## 🚀 Future Improvements

Possible improvements for this project include:

* Add model evaluation metrics such as **R² Score, MAE and RMSE**
* Add data visualization
* Improve the web interface
* Add input validation
* Compare Multiple Linear Regression with other regression algorithms
* Deploy the application online
* Add a prediction history feature
