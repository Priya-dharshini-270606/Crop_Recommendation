# 🌱 Crop Recommendation System

A Machine Learning-based **Crop Recommendation System** that recommends a suitable crop based on soil and environmental conditions such as **Nitrogen, Phosphorus, Potassium, temperature, humidity, pH, and rainfall**.

The project uses **Logistic Regression** and **Random Forest** classification models to predict the most suitable crop for the given input conditions.

## 📌 Project Overview

Choosing the right crop is an important decision in agriculture. Different crops require different soil nutrients and environmental conditions.

This project uses machine learning to analyze agricultural parameters and recommend the crop that is most suitable for the given conditions.

### Input Parameters

* 🌱 Nitrogen (N)
* 🌱 Phosphorus (P)
* 🌱 Potassium (K)
* 🌡️ Temperature
* 💧 Humidity
* 🧪 Soil pH
* 🌧️ Rainfall

### Output

The system predicts a suitable crop based on the given agricultural conditions.

```text
Soil & Environmental Conditions
              ↓
        Data Preprocessing
              ↓
       Machine Learning Model
        ↙              ↘
Logistic Regression   Random Forest
        ↘              ↙
       Crop Prediction
              ↓
     Recommended Crop
```

## 🎯 Objectives

* Recommend suitable crops based on soil and environmental conditions.
* Apply machine learning classification techniques to agricultural data.
* Compare the performance of **Logistic Regression** and **Random Forest**.
* Provide data-driven crop recommendations.

## 🤖 Machine Learning Models

### 1. Logistic Regression

Logistic Regression is used as a classification model to predict the crop class based on the given agricultural parameters.

It provides a simple baseline model for evaluating crop classification performance.

### 2. Random Forest

Random Forest is an ensemble learning algorithm that combines multiple decision trees to make predictions.

It is used to capture complex relationships between soil conditions, weather parameters, and crop suitability.

## 📊 Model Comparison

The project compares the performance of:

| Model               | Type                    |
| ------------------- | ----------------------- |
| Logistic Regression | Classification          |
| Random Forest       | Ensemble Classification |

The models can be evaluated using metrics such as:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

## 📂 Dataset

The dataset contains agricultural and environmental parameters used to predict suitable crops.

### Features

```text
N
P
K
Temperature
Humidity
pH
Rainfall
```

### Target

```text
Crop
```

## 🔄 Machine Learning Workflow

1. Load the agricultural dataset.
2. Explore and understand the data.
3. Perform data preprocessing.
4. Separate features and target variable.
5. Split the dataset into training and testing sets.
6. Train the Logistic Regression model.
7. Train the Random Forest model.
8. Evaluate both models.
9. Compare model performance.
10. Predict the recommended crop for new input values.

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Scikit-learn**
* **Matplotlib**
* **Seaborn**
* **Machine Learning**

## 📁 Project Structure

```text
Crop-Recommendation-System/
│
├── dataset/
│   └── crop_data.csv
│
├── model/
│   ├── logistic_regression.pkl
│   └── random_forest.pkl
│
├── notebook/
│   └── crop_recommendation.ipynb
│
├── app.py
├── requirements.txt
└── README.md
```

> Modify the structure above according to the actual files in your repository.

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
```

### 2. Navigate to the Project

```bash
cd Crop-Recommendation-System
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Application

```bash
python app.py
```

## 🔮 Future Improvements

* Add more agricultural and geographical data.
* Improve prediction performance using additional machine learning algorithms.
* Add real-time weather information.
* Develop a user-friendly web interface.
* Deploy the system as a web application.
* Provide additional recommendations such as fertilizer suggestions.

## 👩‍💻 Author

**Priyadharshini Venkatesan**

B.Tech – Artificial Intelligence & Data Science
Shiv Nadar University, Chennai
