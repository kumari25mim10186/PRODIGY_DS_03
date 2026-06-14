# PRODIGY_DS_02
# 🌳 Customer Purchase Prediction Using Decision Tree Classifier

## 📌 Project Overview

This project uses a Decision Tree Classifier to predict whether a customer will purchase a product or service based on demographic and financial information. The model is trained on a banking dataset and demonstrates the complete machine learning workflow, including data preprocessing, model training, evaluation, and prediction.

---

## 🎯 Objectives

* Perform data preprocessing and cleaning.
* Convert categorical data into numerical format.
* Train a Decision Tree Classification model.
* Predict customer purchase decisions.
* Evaluate model performance using accuracy metrics.
* Understand the importance of different customer features.

---

## 📊 Dataset Information

The dataset contains customer-related information such as:

* Age
* Job
* Marital Status
* Education
* Account Balance
* Housing Loan Status
* Personal Loan Status
* Campaign Information

### Target Variable

**y**

* yes → Customer purchased the product/service.
* no → Customer did not purchase the product/service.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn

---

## 📂 Project Structure

```text
PRODIGY_DS_03/
│
├── data/
│   └── bank.csv
│
├── outputs/
│  
│── decision_tree_model.py
│
├── requirements.txt
├── README.md

```

---

## ⚙️ Project Workflow

### 1. Data Loading

Load the banking dataset using Pandas.

### 2. Data Preprocessing

* Handle categorical features.
* Apply Label Encoding.
* Prepare features and target variable.

### 3. Model Training

Train a Decision Tree Classifier using Scikit-Learn.

### 4. Model Evaluation

Evaluate the model using:

* Accuracy Score
* Classification Report
* Confusion Matrix

### 5. Prediction

Predict whether a customer is likely to purchase the product or service.

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/PRODIGY_DS_03.git
```

Navigate to the project directory:

```bash
cd PRODIGY_DS_03
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

```bash
python src/decision_tree_model.py
```

---

## 📈 Expected Output

* Dataset Overview
* Accuracy Score
* Classification Report
* Customer Purchase Prediction
* Confusion Matrix Visualization
* Feature Importance Visualization

---

## 📚 Learning Outcomes

Through this project, I learned:

* Data Preprocessing Techniques
* Feature Engineering
* Classification Algorithms
* Decision Tree Modeling
* Model Evaluation
* Machine Learning Workflow

---

## 🔮 Future Improvements

* Random Forest Classifier
* Hyperparameter Tuning
* Cross Validation
* Interactive Dashboard using Streamlit
* Model Deployment

---

## 👨‍💻 Author

**Saumya Thakur**

Aspiring Data Scientist | Machine Learning Enthusiast | Python Developer

---

## ⭐ Acknowledgements

This project was completed as part of the **Prodigy InfoTech Data Science Internship Program**.

If you found this project helpful, consider giving it a ⭐ on GitHub.
