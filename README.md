# BostonHousingModel
Summary of the Project
This project uses the Boston Housing dataset to predict the median value of homes (medv) based on various predictors. Three regression models—Linear Regression, Ridge Regression, and Lasso Regression—are implemented and compared.

Key Findings:
Performance Comparison:

Linear Regression has the lowest Mean Squared Error (MSE), indicating it fits the test data well.
Ridge Regression performs similarly to Linear Regression, but slightly increases MSE due to regularization.
Lasso Regression has a higher MSE, suggesting that it aggressively simplifies the model by eliminating some predictors.
Training Time:

Lasso is faster to train than Ridge, highlighting its efficiency in regularization when dealing with sparse data.
Regularization Effects:

Ridge shrinks all coefficients while retaining all predictors, making the model robust but maintaining complexity.
Lasso shrinks some coefficients to zero, effectively performing feature selection.
Tuning Alpha:

The alpha parameter controls the strength of regularization. Lower alpha values retain more features, while higher alpha values reduce overfitting at the cost of higher bias.
Practical Utility:
The project demonstrates how regularization prevents overfitting and improves the model's ability to generalize to unseen data.
Lasso is useful for feature selection, making the model more interpretable.
Ridge is beneficial for handling datasets with multicollinearity, where predictors are highly correlated.
Key Learnings:
Mean Squared Error (MSE) is a crucial metric for evaluating model performance, quantifying the average squared difference between predicted and actual values.
Regularization techniques (Ridge and Lasso) balance bias-variance tradeoff, ensuring the model is neither too simple nor too complex.
The choice of alpha is critical in tuning regularized models for optimal performance.
This project showcases the importance of regularization and feature selection in improving predictive models for real-world applications.


summary using output numbers:

The project implements Linear Regression, Ridge Regression, and Lasso Regression on the Boston Housing dataset to predict the median value of homes. Linear Regression achieves the lowest Mean Squared Error (MSE) of 24.29, demonstrating the best fit to the test data. Ridge Regression performs similarly with an MSE of 24.31, showcasing its robustness through regularization. Lasso Regression simplifies the model by performing feature selection but has a higher MSE of 27.58, reflecting the tradeoff between interpretability and accuracy. Ridge training was slightly slower (0.0080 seconds) compared to Lasso (0.0053 seconds), emphasizing Lasso's efficiency. The findings underline the importance of tuning regularization parameters like alpha to optimize predictive performance and prevent overfitting. 



