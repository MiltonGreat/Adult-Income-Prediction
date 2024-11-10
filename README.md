# Adult-Income-Predic

### Overview

The Adult Income Dataset is an intermediate-level dataset extracted from the U.S. Census Bureau database. The dataset contains information about individuals from the 1994 Census, including demographics, employment status, education level, and income level. This dataset provides an excellent opportunity to practice your skills in Exploratory Data Analysis (EDA), Data Wrangling, Data Visualization, and Classification Models.

### Dataset Details:

Total Instances: 48,842
- Train Data: 32,561 instances
- Test Data: 16,281 instances

Attributes: 15
- Includes both continuous and discrete variables.
- Features include information like age, sex, education level, and employment-related attributes.

###  Tasks

- Data Cleaning: Handle missing values, inspect and map the target variable, and standardize column names.
- Exploratory Data Analysis (EDA): Visualize the distribution of variables and relationships between features and income level.
- Feature Engineering: Preprocess numerical and categorical features (e.g., one-hot encoding for categorical variables, scaling numerical features).
- Model Building: Use classification algorithms such as Logistic Regression, Decision Trees, and Random Forest.
- Evaluation: Evaluate the model performance using metrics like accuracy, precision, recall, and F1 score.

### Interpretation:

- The accuracy of the model is 81%, meaning the model correctly predicted the income category (either <=50K or >50K) for 81% of the test instances.
- The confusion matrix shows that the model has a relatively high precision for class 0 (<=50K), but struggles with class 1 (>50K), resulting in a lower precision (0.56) but a higher recall (0.84) for class 1.
- The F1-score for class 0 is higher, indicating the model performs better at predicting the lower-income class (<=50K) correctly.

### Source:

https://www.kaggle.com/datasets/tawfikelmetwally/census-income-dataset
