# Medical-Insurance-Machine-Learning-Project

**Tools used:**

- Python: Pandas, Numpy, MatPlotLib, Scikit-Learn, Plotly
- Google Colab

**Medical Insurance Cost Prediction Using Regression Models:**

Developed a machine learning project to predict individual medical insurance charges based on demographic and health-related features. The dataset included variables such as age, sex, BMI, smoking status, and number of children.
Performed exploratory data analysis (EDA) to understand feature distributions and relationships with the target variable. Identified smoking status as the most influential factor, with smokers incurring significantly higher medical costs compared to non-smokers.
Implemented and compared multiple regression models, including:

- K-Nearest Neighbors (KNN)
- Decision Tree Regressor
- Random Forest Regressor
- XGBoost Regressor

  
Evaluated model performance using standard regression metrics such as R², Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE).
Key findings:

- The Decision Tree model achieved the highest accuracy, capturing non-linear relationships effectively, but showed signs of overfitting due to its sensitivity to training data. 
- KNN and XGBoost models provided strong overall performance, offering a better balance between bias and variance.
- Random Forest improved generalization compared to a single decision tree but did not outperform the best models in all metrics.

  
This project demonstrates the application of regression techniques, model comparison, and the importance of balancing model complexity with generalization in predictive analytics.
