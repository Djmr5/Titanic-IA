# Titanic Dataset Analysis and Model Training

In-depth analysis and machine learning model training on the famous Titanic dataset from Kaggle. The goal is to predict the survival of passengers based on various features like class, age, fare, and family size, among others.

### Features Analyzed:
- `Pclass`: Passenger class (1st, 2nd, 3rd)
- `Age`: Age of passengers
- `Sex`: Gender of passengers
- `SibSp`: Number of siblings/spouses aboard
- `Parch`: Number of parents/children aboard
- `Fare`: Fare paid for the ticket
- `Embarked`: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

### Models Used:
1. **Logistic Regression**: To capture linear relationships between survival and features like age, fare, and class.
2. **K-Nearest Neighbors (KNN)**: For instance-based learning, using local patterns to predict survival based on similar passengers.
3. **Random Forest**: A powerful ensemble method to capture complex feature interactions and handle missing data effectively.
4. **Support Vector Machine (SVM)**: To find optimal decision boundaries in the dataset for binary classification (kernel trick).

### Key Tasks:
- Data preprocessing and feature engineering, including handling missing values and transforming categorical data.
- Hyperparameter tuning with cross-validation for each model.
- Evaluation of model performance using accuracy, confusion matrix, and classification reports.

### Visualizations:
- Exploratory Data Analysis (EDA) with visualizations to understand the relationship between features and survival.
- Data splitting and model training, hyperparameter tuning on required models.
- Decision boundaries and feature importance visualizations for the models.

