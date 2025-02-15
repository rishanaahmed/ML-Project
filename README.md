# ML-Project
Repository for ML modeule end project
1. Loading and Preprocessing
-Unnecessary columns removed.
-Car brands extracted and categorical variables one-hot encoded.
-No missing values found.

2. Model Implementation

3.Model Evaluation  
-Random Forest Regressor performed best with the highest R² (0.958), lowest MSE (3.35M), and lowest MAE (1296.54).
-Gradient Boosting Regressor also performed well (R² = 0.929), but slightly worse than Random Forest.
-Linear Regression had a decent R² (0.91) but higher error metrics.
-Decision Tree Regressor performed worse than the ensemble models.
-Support Vector Regressor (SVR) performed poorly (negative R²), indicating it is not a good fit.
-The Random Forest Regressor is the best model because it generalizes well, has the lowest errors, and highest R².

4. Feature Importance Analysis
-The top 10 most important features affecting car prices are:
-Engine Size (55.6%) – The most significant factor.
-Curb Weight (29.6%) – Heavier cars tend to be more expensive.
-Highway MPG (4.45%) – Efficiency impacts price but not as much as size.
-Horsepower (2.41%) – More power generally means a higher price.
-Car Width (1.35%) – Wider cars might indicate a premium build.
-BMW Brand (0.76%) – Being a luxury brand adds value.
-Car Length (0.71%) – Larger cars tend to be costlier.
-Wheelbase (0.68%) – Affects stability and luxury feel.
-City MPG (0.62%) – Another efficiency metric influencing value.
-Peak RPM (0.59%) – Performance characteristic impacting pricing.

5. Hyperparameter Tuning
Fitting 5 folds for each of 81 candidates, totalling 405 fits
Best Parameters: {'max_depth': 20, 'min_samples_leaf': 1, 'min_samples_split': 2, 'n_estimators': 100}
Best Score: 0.89137467080074

