A machine learning project developed for **CSE422 — Artificial Intelligence Lab** to predict whether an employee is likely to leave an organization and identify important factors associated with employee attrition.

## Project Overview

The project uses a dataset containing **1,677 employee records and 35 original features**. The target variable is `Attrition`, where `0` represents employees who stayed and `1` represents employees who left. The dataset is highly imbalanced, with approximately **88% staying and 12% leaving**.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Machine Learning
- Neural Networks

## Data Preprocessing

The preprocessing pipeline included:

- Removing irrelevant and constant columns
- Detecting and correcting invalid values
- Median imputation
- Binary, ordinal, and one-hot encoding
- StandardScaler feature standardization
- 80/20 stratified train-test split
- Random oversampling of the minority class

After preprocessing, **43 input features** were used for model training.

## Models Implemented

- Logistic Regression
- Gaussian Naive Bayes
- Neural Network / MLP
- K-Means Clustering

## Model Performance

| Model | Accuracy | Precision | Recall | F1 Score | AUC |
|---|---:|---:|---:|---:|---:|
| Logistic Regression | 75.60% | 27.17% | 62.50% | 37.88% | 0.7606 |
| Naive Bayes | 56.85% | 18.18% | 75.00% | 29.27% | 0.6990 |
| Neural Network | 84.52% | 35.00% | 35.00% | 35.00% | 0.7048 |

**Logistic Regression** provided the strongest overall balance with the highest AUC and F1-score, while **Naive Bayes achieved the highest recall**.

## Key Findings

The analysis showed that employee attrition was associated with factors such as:

- Overtime
- Lower monthly income
- Lack of stock options
- Shorter company tenure
- Younger age
- Job role
- Marital status

The project also demonstrated why **accuracy alone can be misleading for imbalanced datasets**. Recall, F1-score, and AUC provided a more meaningful evaluation of the models.

## Possible Improvements

Future improvements could include:

- SMOTE
- Random Forest
- XGBoost
- Hyperparameter tuning
- Feature engineering
- Decision-threshold optimization
- SHAP-based model explainability

## Project Information

**Course:** CSE422 — Artificial Intelligence  
**Project:** Employee Attrition Prediction  
**Type:** Machine Learning Classification Project  
**Language:** Python

## Author

**Your Name**  
Computer Science Student | AI Systems & Full-Stack Web Development  
ML | DL | NLP | LLMs

- GitHub: [Your GitHub](https://github.com/yourusername)
- LinkedIn: [Your LinkedIn](https://linkedin.com/in/yourusername)
- Portfolio: [Your Portfolio](https://yourportfolio.com)
