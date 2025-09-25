 # Bank Credit Risk Project

This project focuses on **credit risk assessment** using machine learning techniques to predict the probability of loan default among bank customers.

## Overview
The dataset consists of 356 loan applicants categorized into performing and non-performing loan groups based on repayment history. The project explores various machine learning models, including:

- Logistic Regression
- Support Vector Machines (SVM)
- Random Forest
- Artificial Neural Networks

Key steps include:

- Data preprocessing (handling categorical features, scaling, and log-transformations)
- Feature selection and correlation analysis
- Model training and evaluation using 5-fold cross-validation
- Hyperparameter tuning via grid and randomized search
- Model interpretability analysis

## Results
- **Random Forest:** Highest overall accuracy (~70%) and balanced precision-recall.
- **SVM (linear kernel):** Highest Area Under the Curve (AUC), providing robust risk prediction.
- Decision trees were interpreted to extract actionable insights, e.g., applicants under 47.5 years with annual income > 40.2k are more likely to repay loans.

## Technologies
- Python 3.x
- Pandas, NumPy
- Scikit-learn
- Matplotlib/Seaborn (for visualization)

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/bank-credit-risk-project.git