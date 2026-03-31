# AI Finance Analyzer
Created a smart finance tool that learns from past transactions to automatically categorize expenses and analyze financial habits. The system helps users better understand where their money goes and supports smarter budgeting through clear visualizations and AI-driven insights.

## Features
- Automatically categorizes transactions
- Predicts spending categories using machine learning
- Analyzes spending habits over time
- Visualizes monthly spending trends

## How it works
1. Transaction data is collected and preprocessed
2. Features such as amount, transaction type, and date are encoded
3. A machine learning model (Decision Tree) is trained on past data
4. The model predicts categories for new transactions
5. Results are visualized for user interpretation

## Technologies Used
- **Python** for data processing and model development  
- **Pandas** for data cleaning, transformation, and feature preparation  
- **Matplotlib** for visualizing spending patterns and results  
- **Scikit-learn** for:
  - Data splitting (train_test_split)
  - Feature encoding (LabelEncoder)
  - Model building (DecisionTreeClassifier)
  - Model evaluation (accuracy score, classification report, confusion matrix)

## Project Goal
The goal was to build a machine learning model that predicts the category of a financial transaction based on transaction details such as amount, transaction type, account name, and date.

## Future Improvements
- Improve model accuracy with MORE data
- Add a user interface (streamlit or web app)
- Add real-time transaction tracking
- Expand to deep learning models

## Demo Video
This demo showcases how the model predicts transaction categories and visualizes spending patterns using a small depth decision tree.

👉 https://youtu.be/9Ew_9R7gBqU

## Author
Samantha Sandoval  
Computer Science @ California State University San Marcos
