# Customer Purchase Prediction using Decision Tree Classifier

## 📌 Overview

This project demonstrates how to build a **Decision Tree Classifier** to predict whether a customer will subscribe to a term deposit based on demographic and behavioral information. The project uses the **Bank Marketing Dataset** and applies data preprocessing, model training, and performance evaluation to classify customer responses.

A Decision Tree algorithm is trained on the dataset to learn patterns in customer attributes and predict whether a customer will purchase the offered banking product.

---

## 📊 Objective

- Build a Decision Tree Classification model.
- Preprocess and encode categorical features.
- Train the model using historical customer data.
- Evaluate the model using various performance metrics.
- Visualize feature importance and the generated decision tree.

---

## 📁 Dataset

**Dataset:** Bank Marketing Dataset

The dataset contains information collected from direct marketing campaigns of a Portuguese banking institution. The goal is to predict whether a customer will subscribe to a term deposit.

### Target Variable

| Feature | Description |
|---------|-------------|
| y | Indicates whether the customer subscribed to a term deposit (Yes/No) |

### Sample Features

| Feature | Description |
|---------|-------------|
| age | Customer age |
| job | Type of occupation |
| marital | Marital status |
| education | Education level |
| balance | Average yearly account balance |
| housing | Housing loan status |
| loan | Personal loan status |
| contact | Contact communication type |
| duration | Duration of last contact |
| campaign | Number of contacts performed during the campaign |
| previous | Number of contacts before this campaign |

---

## 🛠 Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🤖 Machine Learning Model

**Algorithm Used**

- Decision Tree Classifier

### Model Parameters

- Criterion: Entropy
- Maximum Depth: 5
- Random State: 42

---

## 📈 Model Evaluation

The trained model is evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report
  - Precision
  - Recall
  - F1-Score

---

## 📊 Visualizations

### 1. Confusion Matrix

Displays the number of correct and incorrect predictions made by the classifier.

### 2. Feature Importance

Shows the relative importance of each feature used by the Decision Tree model during prediction.

### 3. Decision Tree Visualization

Illustrates the complete structure of the trained Decision Tree, including splitting conditions, predicted classes, and decision paths.

---

## 🚀 Project Workflow

1. Import required libraries.
2. Load the Bank Marketing dataset.
3. Encode categorical variables using Label Encoding.
4. Split the dataset into training and testing sets.
5. Train the Decision Tree Classifier.
6. Predict customer responses on the test dataset.
7. Evaluate the model using accuracy and classification metrics.
8. Visualize the confusion matrix, feature importance, and decision tree.

---

## 📂 Project Structure

```
PRODIGY_DS_03/
│
├── bank-full.csv
├── Task03.ipynb
├── README.md
└── output.png
```

---

## 📸 Expected Output

The project generates:

- Decision Tree Classifier
- Confusion Matrix
- Classification Report
- Feature Importance Chart
- Decision Tree Visualization

These outputs help evaluate the model's performance and understand the factors influencing customer purchase decisions.

---

## 📚 Learning Outcomes

Through this project, the following concepts were explored:

- Data Preprocessing
- Label Encoding
- Train-Test Split
- Decision Tree Classification
- Model Evaluation
- Accuracy Measurement
- Confusion Matrix Analysis
- Feature Importance Analysis
- Decision Tree Visualization
- Classification Metrics Interpretation

---

## 📌 Conclusion

This project demonstrates the implementation of a Decision Tree Classifier for predicting customer purchase behavior using demographic and behavioral data. The model effectively identifies patterns within the dataset and provides interpretable predictions through decision tree visualization and feature importance analysis.

---

## 👨‍💻 Author

**Vijay Prakash**

Dr. B. R. Ambedkar National Institute of Technology (NIT Jalandhar)  
Jalandhar, Punjab

---
