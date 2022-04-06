# Diabetes-Detection-

 We used the Pima Indians onset of Diabetes data from the UCI Machine Learning Repository website. 
 
  The dataset is comprised of 8 variables that describe medical details of patients such as the number of pregnancies, Glucose, Blood Pressure, Skin Thickness, Insulin values, BMI values, Diabetes pedigree function and patient age. 
  
The following steps were followed: <br>
    1. Data Wrangling and Cleaning: Zero values of Blood Pressure, skin thickness and BMI  make no sense physically and thus were eliminated from the dataset. <br>
    2. Exploratory Data Analysis: The dataset was split into Diabetic and Non-diabetic groups and then some data analysis was carried out. <br>
    3. Data Pre-processing: The data is to be processed for Random Forest, AdaBoost, Gradient Boosting, SVM and Logistic Regression. Since Adaboost and Gradient Boosting was are sensitive to outliers, outliers were removed from the dataset. We did not use XGBoost as the dataset is not very big. <br>
    4. Modelling: The optimal number of estimators was determined using GridSearchCV, which took a very long time to run. <br>
    
Conclusion: For the given dataset, AdaBoost seems to be the best interms of Accuracy and Precision.  
