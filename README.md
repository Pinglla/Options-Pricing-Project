# Options-Pricing-Project

[Project Report](Options_Pricing_Project.docx.pdf)

[Project PowerPoint](Options_Pricing_Project.pdf)

[Final Prediction Code](Options_Pricing_Project_Final_Prediction.ipynb)

## Project Overview

This project explores the application of supervised machine learning techniques to predict the pricing of European call options on the S&P 500. Our team implemented various predictive models, including Linear Regression, Lasso, Ridge, Logistic Regression, K-Nearest Neighbors, Support Vector Classifier, Decision Trees, Random Forests, and Gradient Boosting, to analyze datasets provided. The study focused on two key tasks:

- Regression – Predicting option values. [Regression Code](Linear_Regression.ipynb)
- Classification – Determining whether an option’s value is over- or underestimated relative to the Black-Scholes (BS) model. [Classification Code](CV_Regression_Models.ipynb)

After extensive experimentation, the Random Forest model was selected as the best-performing model for both tasks. It achieved the highest mean R-squared value in 5-fold cross-validation for regression and demonstrated the best accuracy rate in 10-fold cross-validation for classification. These findings highlight the potential of machine learning to complement traditional option pricing methods, such as the Black-Scholes formula, offering a more dynamic and data-driven approach to financial analytics.

However, while machine learning models provide valuable insights, their application in real-world investments requires caution. Option pricing is influenced by numerous market dynamics and financial principles beyond technical predictions. We strongly advise against relying solely on ML-driven forecasts for decision-making. Instead, we recommend integrating these insights with risk management strategies, market expertise, and quantitative financial analysis to ensure a balanced and informed approach to financial decision-making.
