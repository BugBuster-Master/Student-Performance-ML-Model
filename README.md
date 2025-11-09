# Student-Performance-ML-Model
This project analyzes student performance data to understand patterns in attendance, marks, and other academic factors. It includes data cleaning, summary statistics, and insights to help improve student outcomes.

# Student Performance Prediction Model

This project predicts whether a student is likely to **Pass** or **Fail** based on study habits and academic history. The model is trained using Logistic Regression and works on features such as study hours, attendance, past scores, sleep hours, and internet access.

## Dataset Features
| Feature      | Description |
|-------------|-------------|
| StudyHours   | Average hours of study per day |
| Attendance   | Attendance percentage |
| PastScore    | Previous exam score |
| Internet     | Internet availability (Yes/No) |
| Sleephours   | Average sleep duration per day |
| Passed       | Target variable (Pass/Fail) |

## Steps in Model
1. Load the dataset
2. Encode categorical data (Internet, Passed)
3. Normalize numerical features using StandardScaler
4. Train-test split for evaluation
5. Train Logistic Regression model
6. Predict outcomes and evaluate performance
7. Optionally, take user input to predict result in real-time

## Model Output
- **Pass** → The model predicts the student will likely pass.
- **Fail** → The model predicts the student may not pass.

## Requirements
Install dependencies:
```bash
pip install pandas numpy scikit-learn seaborn matplotlib


