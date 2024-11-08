# Credit-Card-Fraud-Detection
<p>This project aims to detect fraudulent credit card transactions using an Artificial Neural Network (ANN). The project demonstrates how machine learning models can identify potentially fraudulent activities to support secure and reliable financial transactions.</p>
<h2>Project Overview</h2>
<p>Credit card fraud is a significant problem in the financial sector, affecting consumers and financial institutions alike. The primary goal of this project is to develop a classification model that accurately identifies fraud cases in credit card transactions. Given the high class imbalance, various data preprocessing techniques are applied to improve model performance.</p>

<h4>Dataset</h4>
<p>The dataset used in this project consists of anonymized credit card transaction data, including features like transaction amount, time, and other key variables. It includes a "Class" column with binary labels:</p>
<p>0: Legitimate transaction
  <br>
1: Fraudulent transaction</p>
<p>
  The dataset can be found on Kaggle and contains the following features:

Time: The number of seconds elapsed between this transaction and the first transaction in the dataset.
V1 - V28: Principal components obtained through PCA for confidentiality.
Amount: The transaction amount.
Class: Fraud label (1 = fraud, 0 = non-fraud)
</p>
<h4>Project Workflow</h4>
<p>Data Preprocessing
<br>
Scaling: The Amount feature was scaled to standardize input values.
Class Balancing: The dataset is highly imbalanced, so SMOTE (Synthetic Minority Over-sampling Technique) was applied to balance the classes.
Train-Test Split: Data was divided into training and testing sets to evaluate model performance.
</p>
