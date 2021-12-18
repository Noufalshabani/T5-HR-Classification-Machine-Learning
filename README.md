# T5-HR-Classification-Machine-Learning
<img align="right" width="300" height="90" src="https://upload.wikimedia.org/wikipedia/ar/2/21/%D8%A3%D9%83%D8%A7%D8%AF%D9%8A%D9%85%D9%8A%D8%A9_%D8%B3%D8%AF%D8%A7%D9%8A%D8%A7.png">


\
&nbsp;
\
&nbsp;

\
&nbsp;
\
&nbsp;
 # <p  align="center">  **Classification Models - Employee Promotions** </p>
\
&nbsp;

 

<p align="center">
  <img width="460" height="300" src="https://t4.ftcdn.net/jpg/04/15/29/51/240_F_415295138_VZEnsaqSSgQ8py40Td5shJJb6JdfFlwb.jpg">
</p>

\
&nbsp;
\
&nbsp;

## Introduction:
There are many companies trying to determine which employees are eligible for a promotion by a certain evaluation, and with thousands of employees, this is delaying the transition to new positions. Hence, the company needs to help identify the qualified candidates at a particular checkpoint so that they can speed up the entire promotion cycle.
\
&nbsp;
\
&nbsp;

## Inspiration:

We try predict whether a potential promote at checkpoint in the test set will be promoted or not after the evaluation process.
\
&nbsp;
\
&nbsp;

## Dataset Information:
[It was uploaded in Kaggle, Click here to go to dataset](https://www.kaggle.com/arashnic/hr-ana/)


| Name of columns|Discerption|Type|
|--|--|--
 Employee_id | Unique ID for employee |  int64
Department| Department of employee|object
Region| Region of employment (unordered) |object
Education | Education Level | object
Gender |Gender of Employee | object
Recruitment_channel| Channel of recruitment for employee|object
No_of_trainings|No of other trainings completed in previous year on soft skills, technical skills etc.|int64
Age|Age of Employee|int64
Previous_year_rating|Employee Rating for the previous year|float64
Length_of_service|Length of service in years|int64
Awards_won | If awards won during previous year then 1 else 0|int64
Avg_training_score|Average score in current training evaluations|int64
Is_promoted|Recommended for promotion (Target)|int64

\
&nbsp;
\
&nbsp;

## Cunclusion:
1. Classifier Performance Metrics of interest.
2. Random over-sampling for  Handling  Imbalance  Data.
3. XGBoost is the Best Classifier for this dataset.
###### With Accuracy = 53.43 , precision  =  12 ,  recall  =  69 ,  F-1  =  20.4

\
&nbsp;
\
&nbsp;
## Future Work:
1. Correcting errors, if any
2. Work on tuning the classifiers  more,  and  try  other  classifiers
\
&nbsp;
\
&nbsp;
## Tools:
1. Python Programming Language
2. Jupyter Notebook (Pandas, Seaborn, Scikit-learn, Plotly)
3. Microsoft Office 
\
&nbsp;
\
&nbsp;

## Team members:
- [ ]  [Abdulmajeed Mesfir Alnfaie](https://github.com/AbdulamjeedAlnefaie)
- [ ]  [Nouf Buqaysh Alshabani](https://github.com/Noufalshabani)
- [ ]  [Ahmad Yahya Hakami](https://github.com/AhmadHakami)

