💳 Credit Card Fraud Detection Using Machine Learning

📌 Project Overview

The Credit Card Fraud Detection project uses Machine Learning to identify potentially fraudulent credit card transactions.

The system analyzes transaction-related data and classifies transactions into two categories: Normal and Fraudulent.

The main objective is to detect unusual transaction patterns and understand how Machine Learning can be used in financial security.

🎯 Project Objectives

- Analyze credit card transaction data.
- Identify fraudulent transaction patterns.
- Clean and preprocess the dataset.
- Build classification models.
- Predict fraudulent transactions.
- Compare two Machine Learning algorithms.
- Evaluate model performance.

🧠 Algorithms Used

1. Logistic Regression – Main Algorithm

Logistic Regression is a supervised Machine Learning algorithm used to classify transactions as normal or fraudulent.

Why Logistic Regression?

- Suitable for binary classification.
- Efficient for large datasets.
- Provides probability-based predictions.
- Useful as a classification baseline.

2. Random Forest Classifier – Comparison Algorithm

Random Forest is an ensemble algorithm that combines multiple Decision Trees to improve prediction performance.

Why Random Forest?

- Combines multiple decision trees.
- Identifies complex transaction patterns.
- Handles different input features.
- Helps compare classification performance.

🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Anaconda Spyder

📊 Dataset Description

The dataset contains credit card transaction information, including:

- Transaction Features
- Transaction Amount
- Time
- Anonymized Numerical Features
- Class Label

Target Classification

- 0 – Normal Transaction
- 1 – Fraudulent Transaction

⚙️ Project Workflow

1. Import required Python libraries.
2. Load the credit card dataset.
3. Explore the dataset.
4. Check missing values.
5. Analyze normal and fraudulent transactions.
6. Separate input features and target variable.
7. Preprocess the data.
8. Split data into training and testing sets.
9. Train the Logistic Regression model.
10. Train the Random Forest model.
11. Predict transaction classes.
12. Evaluate both models.
13. Compare model performance.
14. Display accuracy graphs and confusion matrices.

📈 Model Evaluation

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

Important: Since fraudulent transactions are usually much fewer than normal transactions, precision, recall, F1-score and precision-recall analysis are especially useful alongside accuracy.

📉 Visualizations

- Transaction Class Distribution.
- Model Accuracy Comparison Graph.
- Logistic Regression Confusion Matrix.
- Random Forest Confusion Matrix.

💻 How to Run

Install the required libraries:

pip install pandas numpy matplotlib scikit-learn

1. Download the credit card dataset.
2. Place the CSV file in the project folder.
3. Open the Python file in Anaconda Spyder.
4. Update the dataset path.
5. Run the program.

🌟 Applications

- Financial transaction monitoring.
- Fraud detection research.
- Banking data analysis.
- Digital payment security.
- Financial data classification.

🔮 Future Enhancements

- Develop a real-time fraud detection dashboard.
- Improve detection of rare fraudulent transactions.
- Explore additional classification algorithms.
- Build a web-based fraud detection application.

👩‍💻 Author

Mokshitha Sree

Artificial Intelligence and Data Science Student

🏁 Conclusion

This project demonstrates how Machine Learning can identify potentially fraudulent credit card transactions.

Logistic Regression and Random Forest algorithms are implemented and compared using classification metrics and visualizations.

The project provides practical experience in data preprocessing, imbalanced classification, fraud prediction and model evaluation.# Credit-Card-Fraud-Detection-using-machine-learning
