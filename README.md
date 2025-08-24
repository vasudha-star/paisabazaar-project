This project focuses on developing a robust machine learning model to predict customer credit scores, categorizing them as 'Poor', 'Standard', or 'Good'. The primary goal is to create a reliable automated system for assessing credit risk. The project follows a comprehensive machine learning workflow:

* Data Exploration & Cleaning: The initial dataset was loaded, examined for inconsistencies, and cleaned by handling missing values and correcting data types.

* Exploratory Data Analysis (EDA): A series of 15 visualizations were created to uncover key relationships between financial attributes (like Annual_Income, Outstanding_Debt, Credit_Mix) and the final Credit_Score.

* Feature Engineering & Preprocessing: New features were engineered from existing columns, categorical variables were encoded, outliers were handled, and the data was scaled. A crucial step was using the SMOTE technique to address the class imbalance in the training data.

* Modeling & Evaluation: Five different classification models were implemented and evaluated: Logistic Regression, Random Forest, XGBoost, LightGBM, and Support Vector Classifier (SVC).

* Hyperparameter Tuning: The ensemble models were optimized using RandomizedSearchCV on a data sample to enhance performance while maintaining reasonable training times.

* Conclusion: The Tuned LightGBM Classifier was selected as the final model due to its superior accuracy (~77%), strong performance on key business metrics like recall, and high computational efficiency.

The final model provides an actionable tool for making data-driven lending decisions.
