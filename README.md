# Titanic Survival Prediction

This project analyzes the Titanic passenger dataset to predict survival outcomes using machine learning models. It explores data preprocessing, visualization, and the application of classification algorithms to draw meaningful insights and achieve accurate predictions.

## 📌 Project Overview

- **Dataset**: Titanic passenger data
- **Objective**: Predict whether a passenger survived the Titanic shipwreck
- **Models Used**:
  - Decision Tree Classifier
  - Random Forest Classifier

## 📊 Features Considered

Key features used in training include:
- Passenger class (`Pclass`)
- Sex
- Age
- Number of siblings/spouses aboard (`SibSp`)
- Number of parents/children aboard (`Parch`)
- Fare
- Embarked location

## 🧠 Machine Learning Workflow

1. **Data Cleaning**:
   - Handling missing values
   - Encoding categorical features
2. **Exploratory Data Analysis**:
   - Correlation analysis
   - Visualization of survival rates
3. **Model Training**:
   - Split into training and testing sets
   - Applied Random Forest and Decision Tree
4. **Evaluation**:
   - Accuracy scores
   - Confusion matrix

## Results

- The Random Forest classifier showed better performance than the Decision Tree.
- Feature importance highlighted `Sex`, `Fare`, and `Pclass` as key survival indicators.

## 📁 Files

- `titanic_part_2.ipynb`: Jupyter notebook containing full analysis and model training.
- `README.md`: Project documentation.

## 💻 Clone the Repository

To clone this project to your local machine:

```bash
git clone https://github.com/Mrez2/Titanic-project.git
