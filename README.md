# HR-Job-Prediction-Analysis
It helps to predict whether the candidate is looking for a job or not.
# Objective
Predict the probability of a candidate to look for a new job or will work for the company, as well as interpreting affected factors on employee decision.
# Dataset
The dataset is taken from kaggle - 
https://www.kaggle.com/arashnic/hr-analytics-job-change-of-data-scientists
# Features
* Enrollee_id : Unique ID for candidate,
* city: City code,
* city_ development _index : Developement index of the city (scaled),
* gender: Gender of candidate,
* relevent_experience: Relevant experience of candidate,
* enrolled_university: Type of University course enrolled if any,
* education_level: Education level of candidate,
* major_discipline :Education major discipline of candidate,
* experience: Candidate total experience in years,
* company_size: No of employees in current employer's company,
* company_type : Type of current employer,
* lastnewjob: Difference in years between previous job and current job,
* training_hours: training hours completed,
* target: 0 – Not looking for job change, 1 – Looking for a job change
# Methodology
1) Dataset collection
2) Performed EDA : Handled outliers using flooring and capping method , Deleted duplicted rows , Converted categorical features using One Hot Encoding , Feature Scaling.
3) Created 6 different classification models : Logistic Regression,KNN,Decision Tree,SVM,Random Forest,XGBoost
4) Performed comparative analysis
# Visualization

Count of candidate based on gender
![Count of candidate based on gender](https://user-images.githubusercontent.com/94851933/156412337-301f4301-9a55-4e6c-a2ac-1562a1249404.png)

Distribution of Training Hours
![Distribution of Training Hours](https://user-images.githubusercontent.com/94851933/156413167-76de5355-ecf4-421a-bd69-790bd0fcdd72.png)

Candidate from major cities
![Candidates from major cities](https://user-images.githubusercontent.com/94851933/156413210-99d2e472-c96b-4d44-b9fd-bdf88048edf7.png)

Relation of City_development_index and target
![Relation of City development and target](https://user-images.githubusercontent.com/94851933/156413238-b23f8b96-a1c8-4e2b-b004-89f73f5277b6.png)


![comparative analysis](https://user-images.githubusercontent.com/94851933/157096405-a0376af3-e6c1-4ea6-9d7e-ce8a4ba8ca86.png)


# Libraries used
1) Data Cleaning - Pandas , Numpy
2) Data Visualization - seaborn , matplotlib
3) Feature Scaling - MinMaxScaler
4) Splitting to train and test
5) Algorithms - DecisionTreeClassifier,RandomForestClassifier,SVM,KNeighboursClassifier,LogisticRegression,XGBClassifier
