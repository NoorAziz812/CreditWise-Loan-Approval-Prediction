## Overview
This project predicts whether a loan application will be approved using machine learning techniques and applicant financial information.

## Problem Statement
Banks receive numerous loan applications.
The goal is to predict loan approval decisions using applicant information such as income, credit score, savings, and debt-to-income ratio.

## Project Structure
```
CreditWise-Loan-Approval-Prediction
│
├── data/
│   └── loan_approval_data.csv
│
├── notebooks/
│   └── creditwise_analysis.ipynb
│
├── images/
│   ├── class_distribution.png
│   ├── credit_score_histogram.png
│   ├── correlation_heatmap.png
│
├── requirements.txt
│
├── README.md
│
└── .gitignore
```

## Dataset
| Attribute | Value |
|-----------|-------|
| Source | Kaggle |
| Number of Records | 1000 |
| Number of Features | 20 |
| Target Variable | Loan_Approved |

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

## Project Workflow
```
Data Loading
    ↓
Data Cleaning
    ↓
EDA
    ↓
Feature Engineering
    ↓
Encoding
    ↓
Scaling
    ↓
Model Training
    ↓
Model Evaluation
```

## Exploratory Data Analysis

### Key Findings
- **Finding 1:** Applicants with higher credit scores (above 700) have a significantly higher approval rate of 92%, compared to only 35% for those with lower scores.
- **Finding 2:** Debt-to-Income (DTI) ratio is a critical factor; applicants with DTI below 0.4 have 85% approval rates, while those above 0.6 have only 15% approval rates.
- **Finding 3:** Savings amount shows a strong positive correlation with loan approval; applicants with savings above $50,000 have 88% approval probability.

### Visualizations

#### Distribution Plots
![Distribution Plots](https://github.com/NoorAziz812/CreditWise-Loan-Approval-Prediction/blob/main/images/class_distribution.png?raw=true)

#### Heatmaps
![Correlation Heatmap](https://github.com/NoorAziz812/CreditWise-Loan-Approval-Prediction/blob/main/images/correlation_heatmap.png?raw=true)

#### Histograms
![Histograms](https://github.com/NoorAziz812/CreditWise-Loan-Approval-Prediction/blob/main/images/credit_score_histogram.png?raw=true)

#### Boxplots
![Boxplots](https://github.com/NoorAziz812/CreditWise-Loan-Approval-Prediction/blob/main/images/class_distribution.png?raw=true)

## Models Used
- Logistic Regression
- KNN
- Naive Bayes

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

## Key Insights
- Higher credit scores significantly increase approval probability.
- Lower DTI ratios are associated with higher approval rates.
- Savings positively influence approval outcomes.

## Results
- Logistic Regression Accuracy: 87.5%
- KNN Accuracy: 75.5%
- Naive Bayes Accuracy: 86.5%

## Future Improvements
- Random Forest
- XGBoost
- Hyperparameter Tuning
- Deployment

## Author

**Noor Aziz**  
B.Tech CSE (AI/ML)

- **GitHub:** [github.com/NoorAziz812](https://github.com/NoorAziz812)
- **LinkedIn:** [Noor Aziz](https://www.linkedin.com/in/noor-aziz-2815b0373/)
