Predictive Modeling for Stock Options Pricing
---
**Overview**
- This project focuses on optimizing the valuation and pricing of stock options using machine learning models. We aimed to improve the predictive accuracy of option prices compared to traditional methods like the Black-Scholes model.

**Methods**
- Exploratory Data Analysis (EDA): Conducted thorough EDA to understand the dataset, identify key features, and ensure data quality.
- Feature Engineering: Created domain-specific features such as moneyness (S/K), intrinsic value, and tau_days to enhance model interpretability and performance.
- Modeling Approaches:
    - Regression: Evaluated multiple models including Linear Regression, Decision Trees, Random Forest, Gradient Boosting, and XGBoost.
    - Classification: Tested models like Logistic Regression, Support Vector Machine (SVM), K-Nearest Neighbor (KNN), Decision Trees, Random Forest, and XGBoost.
- Model Selection: Utilized 10-fold cross-validation and hyperparameter tuning with GridSearch to identify the best-performing models.

**Results**
- Regression: XGBoost achieved the highest performance with a mean R-squared of 99.87%, demonstrating superior predictive power.
- Classification: XGBoost also excelled in classification tasks with a classification accuracy of 94.42%, outperforming other models.

**Findings**
- XGBoost was identified as the optimal model for both regression and classification, thanks to its ability to capture complex, non-linear relationships in the data.
Feature engineering, particularly the inclusion of intrinsic value and moneyness, significantly improved model accuracy.
Machine learning models, especially XGBoost, offer greater flexibility and accuracy in option pricing compared to traditional methods.

1. EDA: https://colab.research.google.com/drive/1nHIpa_LJ7AALZDVAxdZHxXzRLfdQ3Jgr?usp=sharing
2. Regression Models: https://colab.research.google.com/drive/13FJsXto6rr6m-O_lyBX1W79VxXQdHTIk?usp=sharing
3. Classification Models: https://colab.research.google.com/drive/1ZL1KpN-ayBskdhZy8T25PqQ5Xq59ehsv?usp=sharing
