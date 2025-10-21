Car Price Prediction using Ridge and Lasso Regression

This project demonstrates the application of regularization techniques — Ridge and Lasso Regression — to improve linear model performance and prevent overfitting.

🚗 Dataset
A synthetic car price dataset with 500 rows was generated.
It includes features such as engine size, horsepower, mileage, fuel type, transmission, owner type, etc.

⚙️ Techniques Used
Linear Regression (baseline)
Ridge Regression – adds L2 regularization to penalize large coefficients
Lasso Regression – adds L1 regularization to shrink irrelevant features to zero

Steps followed:
Data Preprocessing – handled categorical variables using pd.get_dummies().
Model Building – trained three models: Linear, Ridge, and Lasso Regression.
Evaluation – used metrics like r2_score, MSE, and RMSE for performance comparison.
Visualization – created a comparative bar chart showing coefficient shrinkage and accuracy.

📊 Results & Insights
Model	                Train Accuracy	Test Accuracy
Linear Regression	      ~97%	            ~96%
Ridge Regression	      ~98%	            ~97%
Lasso Regression	      ~96%	            ~95%

✅ Ridge gives more stable predictions
✅ Lasso simplifies the model by feature elimination

📈 Visualization
The below chart compares model performance and coefficients.
<img width="695" height="480" alt="image" src="https://github.com/user-attachments/assets/8de96b16-f05e-4b50-8992-de58ce82fc04" />

🔍 Observation:
Linear Regression performed well but slightly overfitted.
Ridge Regression handled multicollinearity and improved generalization.
Lasso Regression performed feature selection, reducing less significant coefficients to zero.

📚 This project deepened my understanding of bias-variance trade-off and how regularization enhances model robustness.
