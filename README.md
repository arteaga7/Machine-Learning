# Machine-Learning
This repository contains the following Machine Learning (ML) projects implementing Scikit-learn library:

1. "binary_classifier.ipynb"
2. "multi_classifier.ipynb"
3. "regressor.ipynb"

## 1. "Binary classifier"
This project analyzes the dataset of 10000 electric grids with 12 features.

**Objective:** To determine if the electric stability of the grid is stable (class 1) or inestable (class 0). This is, the binary classification problem is adressed in this document.

### Steps
First, the exploratory data analysis (EDA) is performed to show the data features in the non-cleaned dataset. Second, the data preprocessing is performed, which consist of:

a. Filling null values and dropping duplicates.

b. Processing outliers and multicollinearity.

c. Converting categorical variables into binary ones.

d. Scaling the data.

Third, the training and validation of the performance of 4 different ML algorithms are compared to solve the binary classification problem. The ML models are:

• Algorithm 1: **Logistic Regression**.

• Algorithm 2: **Decision Tree Classifier**.

• Algorithm 3: **Random Forest Classifier**.

• Algorithm 4: **Gradient Boosting Classifier**.

Finally, the best algorithim is selected for this particular dataset.

## 2. "Multi-class classifier"
This project studies the dataset of 1800 data matrices (small pictures representing a digit) with 64 features.

**Objective:** To solve the multi-class classification problem, which consist of determining what category the digit belongs to. There are 10 categories, corresponding to every digit (from 0 to 9).

### Steps
The dataset is imported from the sklearn library, hence, the exploratory data analysis (EDA) is ommited. Then, the performance of 3 different ML algorithms are compared:

• Algorithm 1: **KNeighborsClassifier**.

• Algorithm 2: **SVC**.

• Algorithm 3: **GaussianNB**.

Finally, the best algorithim is selected for this particular dataset.

## 3. "Regressor"
This projects analyzes the dataset of cars with 7 features (weight, acceleration, origin, engine power, number of cylinders, year and engine displacement).

**Objective:** To predict the fuel consumption of the car. This is, the regression problem (to predict the value of a continuous variable) is adressed in this document.

### Steps
First, the exploratory data analysis (EDA) is performed to show the content of the raw dataset. Second, the data preprocessing is performed, which consist of:

a. Filling null values and dropping duplicates.

b. Processing outliers and multicollinearity.

c. Converting categorical variables into binary ones.

d. Standarizating the data.

Third, the training and validation of the performance of 5 different ML algorithms are compared. The ML models are:

• Algorithm 1: **Lasso (Linear regression with L1 regularization)**.

• Algorithm 2: **Ridge (Linear regression with L2 regularization)**.

• Algorithm 3: **DecisionTreeRegressor**.

• Algorithm 4: **RandomForestRegressor**.

• Algorithm 5: **GradientBoostingRegressor**.

Finally, the best algorithim is selected for this particular dataset. 
