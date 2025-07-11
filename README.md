<h1>🚢 Titanic Survival Prediction</h1> </br>

<p>This project explores the Titanic passenger dataset to analyze survival rates and build machine learning models that predict whether a passenger survived based on various features such as age, gender, class, fare, and more.</p>

<h2>📁 Dataset</h2> </br>

The dataset includes passenger details such as:</br>

PassengerId, Name, Sex, Age, Pclass </br>

Fare, SibSp, Parch, Embarked, Cabin </br>

Survived (Target: 0 = No, 1 = Yes) </br>

<h4>🧹 Data Preprocessing</h4> </br>

Handled missing values (e.g., Age, Embarked, Cabin) </br>

Dropped less informative or highly missing columns (like Cabin, Ticket, PassengerId) </br> 

Converted categorical columns to numeric using label encoding </br>

Removed duplicates </br>

<h4>📊 Exploratory Data Analysis</h4> </br>

Gender-wise survival analysis </br>

Class-wise survival comparison </br> 

Age and Fare distribution </br>

Correlation heatmaps and violin plots for deeper insight </br>

<h4>⚙️ Model Building</h4> </br>

1. Random Forest Classifier </br>

Parameters: n_estimators=3, max_depth=5 </br>

Good for understanding feature importance and non-linear relationships </br>

2. XGBoost Classifier </br>

Parameters: n_estimators=5, max_depth=5 </br>

Robust boosting algorithm that performed well on the cleaned dataset </br>

<h4>➕ Additional Steps</h4> </br>

Feature scaling using StandardScaler </br>

Train-test split (80/20) </br>

Model evaluation using accuracy_score and classification_report </br>

<h4>📈 Evaluation Metrics</h4> </br>

Accuracy Score </br>

Precision, Recall, F1-Score for both models </br>

<h2>🧠 Libraries Used</h2> </br>

pandas, numpy </br>

matplotlib, seaborn </br>

sklearn for model training and evaluation </br>

xgboost</br>

