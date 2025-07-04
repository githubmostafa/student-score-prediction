

Description
This project predicts students' math scores using both linear and polynomial regression models.
It includes data preprocessing, exploratory data analysis, model training, and evaluation using performance metrics.

Dataset
Source: [Kaggle – Students Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)  
The dataset contains 1000 records with features such as gender, parental education, lunch type, test preparation, and scores in math, reading, and writing.

Tools and Libraries
 Python
 Pandas
 NumPy
 Matplotlib
 Seaborn
 Scikit-learn

Models Implemented
Linear Regression
Polynomial Regression with degree 2

Evaluation Metrics
Mean Squared Error (MSE)
R-squared Score (R2)
Mean Absolute Error (MAE)

Model Comparison

Model                  MSE       R2 Score   MAE
Linear Regression      29.09     0.8804     4.21
Polynomial Regression  32.80     0.8652     4.54

Visualizations
Distribution plot of average scores
Boxplot showing the effect of test preparation on scores
Actual vs predicted math score plots
Residual plots for both models

Conclusion
The linear regression model achieved slightly better performance than the polynomial regression model across all metrics (MSE, R², and MAE).
Despite the polynomial model capturing non-linear patterns, the added complexity did not lead to significant improvement.
This suggests that a simple linear relationship between features and math scores is sufficient for this dataset.



