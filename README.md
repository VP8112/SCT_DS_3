# Customer Purchase Prediction using Decision Tree Classifier

## About the Project

This project builds a **Decision Tree Classifier** to predict whether a customer will subscribe to a term deposit using the **Bank Marketing Dataset**. The dataset contains demographic and behavioral information collected during direct marketing campaigns conducted by a Portuguese banking institution.

The project covers the complete machine learning workflow, including data preprocessing, model training, prediction, performance evaluation, and visualization of the decision tree.

---

## Project Goal

The main objectives of this project are:

- Build a Decision Tree classification model.
- Prepare the dataset for machine learning.
- Train and test the model using historical customer data.
- Evaluate the model using classification metrics.
- Understand the importance of different customer attributes in predicting purchase decisions.

---

## Dataset

**Dataset:** Bank Marketing Dataset

The dataset contains customer information collected during marketing campaigns conducted by a Portuguese banking institution.

### Target Variable

| Feature | Description |
|---------|-------------|
| y | Whether the customer subscribed to a term deposit (Yes/No) |

### Important Features

| Feature | Description |
|---------|-------------|
| age | Customer age |
| job | Type of occupation |
| marital | Marital status |
| education | Education level |
| balance | Average yearly account balance |
| housing | Housing loan status |
| loan | Personal loan status |
| contact | Communication type |
| duration | Duration of the last contact |
| campaign | Number of contacts during the campaign |
| previous | Number of previous contacts |

---

## Tools and Libraries

- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## Data Preparation

Before training the model, the following preprocessing steps were performed:

- Loaded the dataset.
- Encoded categorical variables using Label Encoding.
- Separated features and target variable.
- Split the dataset into training and testing sets.

---

## Machine Learning Model

The project uses a **Decision Tree Classifier** with the following configuration:

- Criterion: Entropy
- Maximum Depth: 5
- Random State: 42

---

## Model Evaluation

The trained model was evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report
  - Precision
  - Recall
  - F1-Score

---

## Visualizations

The project includes the following visualizations:

- Confusion Matrix
- Feature Importance Chart
- Decision Tree Visualization

These visualizations help understand the model's performance and identify the most influential features used for prediction.

---

## Folder Structure

```
PRODIGY_DS_03/
│
├── bank-full.csv
├── Task03.ipynb
├── README.md
└── output.png
```

---

## Key Findings

Some important observations from the project include:

- The Decision Tree classifier successfully learns patterns from customer demographic and behavioral data.
- Certain customer attributes contribute more significantly to prediction than others.
- Feature importance helps identify the variables that have the greatest impact on customer subscription decisions.
- The decision tree visualization provides a clear and interpretable representation of the model's decision-making process.

---

## Conclusion

This project demonstrates how a Decision Tree Classifier can be used to predict customer purchase behavior using demographic and behavioral data. The model provides interpretable predictions and highlights the key factors influencing customer responses, making it a useful approach for classification tasks and marketing analysis.

---

## Author

**Vijay Prakash**

Dr. B. R. Ambedkar National Institute of Technology (NIT Jalandhar)  
Jalandhar, Punjab

---
