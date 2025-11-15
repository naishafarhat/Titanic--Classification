# 🚢 Titanic Survival Prediction
A Machine Learning Project using Train–Test Split\
This project builds a machine learning model to predict passenger survival on the Titanic using the classic Kaggle Titanic dataset.\
The workflow includes data loading, preprocessing, feature engineering, splitting data into training and testing sets, model building, and evaluation.
# 📌 Project Overview
The goal is to predict whether a passenger survived the Titanic disaster based on features such as age, gender, ticket class, fare, and family information.\
The workflow strictly uses a train–test split (instead of cross-validation or Kaggle submission format) to evaluate model accuracy.
# 🗂 Dataset Description
The dataset contains the following key features:\
Survived – Target variable (0 = No, 1 = Yes)\
Pclass – Ticket class\
Name – Passenger name\
Sex – Gender\
Age\
SibSp – Siblings/spouses aboard\
Parch – Parents/children aboard\
Fare\
Embarked – Port of embarkation
# 🧠 Steps Included in the Notebook
1️⃣ Importing Libraries\
Pandas, NumPy, Matplotlib/Seaborn, and Scikit-learn are used for analysis and modeling.
# 2️⃣ Data Loading
The Titanic dataset (CSV file) is loaded into a Pandas DataFrame.
# 3️⃣ Exploratory Data Analysis (EDA)
The notebook includes:\
Checking missing values\
Distribution of numeric features\
Survival comparison by gender, class, and other attributes\
Visualizations (if implemented)
# 4️⃣ Data Cleaning & Preprocessing
Common preprocessing steps include:\
Filling missing values (Age, Embarked, Fare)\
Dropping irrelevant columns (like PassengerId, Name, Ticket, Cabin)\
Encoding categorical features (Sex, Embarked)\
Scaling numerical features (optional)
# 5️⃣ Feature Engineering
Depending on your notebook, possible added features:\
FamilySize (SibSp + Parch + 1)\
IsAlone\
Title extraction (optional)
# 6️⃣ Train–Test Split
The dataset is split into:\
Training Set: 80%\
Testing Set: 20%\
Using:\
from sklearn.model_selection import train_test_split
# 7️⃣ Model Building
A machine learning algorithm is trained such as:\
Logistic Regression\
Decision Tree\
Random Forest\
KNN\
SVM 
# 8️⃣ Model Evaluation
The notebook evaluates the model using:\
Accuracy Score\
Confusion Matrix\
Classification Report (precision, recall, f1-score)\
This helps measure the model’s predictive performance on unseen data.