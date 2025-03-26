# cybersecurity-intrusion-detection

This project focuses on building a machine learning-based system to detect cybersecurity intrusions. The system uses a dataset of network activity to classify whether an intrusion has occurred. The project demonstrates various steps in data preprocessing, model training, and evaluation for effective intrusion detection.

---

## Features of the Project

- **Data Cleaning and Preprocessing**:
  - Handled missing values and inconsistencies.
  - Scaled numerical features and encoded categorical variables.

- **Exploratory Data Analysis (EDA)**:
  - Visualized key patterns and relationships in the data.
  - Identified feature importance for better decision-making.

- **Model Training and Evaluation**:
  - Trained a Random Forest classifier for intrusion detection.
  - Evaluated the model using metrics like accuracy, precision, recall, and F1-score.

---

## Dataset Used

- **Name**: Cybersecurity Intrusion Dataset
- **Source**: Provided in the `archive (2).zip` file.
- **Description**: Contains features like `session_id`, `protocol_type`, `failed_logins`, `ip_reputation_score`, and a target variable `attack_detected`.

---

## Project Workflow

1. **Data Loading**:
   - Extracted the dataset from a compressed file and loaded it into a pandas DataFrame.

2. **Data Preprocessing**:
   - Handled missing values.
   - One-hot encoded categorical features.
   - Scaled numerical features using `StandardScaler`.

3. **Model Training**:
   - Split the dataset into training and testing sets.
   - Trained a Random Forest classifier.
   - Tuned hyperparameters for better performance.

4. **Evaluation**:
   - Assessed model performance using metrics like accuracy, precision, recall, and F1-score.
   - Visualized confusion matrix and feature importance.

---

## Technologies Used

- **Programming Language**: Python
- **Libraries**:
  - pandas
  - numpy
  - scikit-learn
  - seaborn
  - matplotlib

---
