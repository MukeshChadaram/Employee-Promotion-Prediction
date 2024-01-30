# Real-Time-Business-Monitoring
# Dashboards that track Key Performance Indicators (KPIs) and alert stakeholders to anomalies

Objective:

In a service-based company, the HR department aims to enhance its promotion strategy by using Previous Promotion Cycle’s Data to identify the most suitable candidates for promotion for the upcoming Promotion Cycle. 


SOLUTION:

The best solution would be to use a predictive model to Analyze the Data to make Promotion-based Decisions easier and much more holistic keeping in mind both the Company’s Business and at the same time rewarding Employee’s Efforts.

Challenge:

The challenge lies in developing an efficient predictive model that analyzes various parameters and employee attributes to forecast potential promotions accurately. 

Expected Outcomes:

Improved decision-making capabilities for HR personnel to identify and support employees most likely to succeed in higher roles.
Enhanced transparency in the promotion process, fostering a fair and merit-based environment within the organization.
Also gain several Insights about various Factors affecting the Organizational Performance in different Divisions.
By addressing this problem statement, the company aims to optimize its promotion strategy, ensuring that deserving candidates are identified promptly and provided with growth opportunities while maximizing overall Organizational Performance and Employee satisfaction.

DATA COLLECTION & PREPARATION

The dataset we used for this project was found in Kaggle.com

The dataset was cleaned using the Tableau Prep tool. We found null values present in the dataset under the Previous Year Rating Attribute. Which isn’t an Outlier. So, We changed it to ZERO.

There are 54808 records in the dataset.​

For prediction modelling, we edited some attributes like removing and modifying the data from the dataset (Data Transformation).

Kaggle.com - - https://www.kaggle.com/datasets/bhrt97/hr-analytics-classification


DATA  ANALYSIS

Insights on PROMOTIONS:​

For instance, in the attribute "Recruitment channel" the No. Of Employees promoted are:​

In Referred, 92 employees are promoted i.e., 1.97% of employees that are promoted.​
In Others, 2651 employees are promoted i.e., 56.79% that are promoted.​
In Sourced, 1925 employees are promoted i.e, 41.238% that are promoted.​


DATA  CORRELATION

We can say “Age” is sort of INVERSELY proportional to "promotion" as most of the young employees get promoted in the dataset.
"No of Trainings" is INVERSELY proportional to "promotion" i.e, less no. of trainings << the higher chance of an Employee getting promoted.
"Length of service" does play an important role.  As per the Data to getting promoted as one thinks but you can say it is almost INVERSELY proportional to promotion.
"KPI’s met" is Directly proportional to "promotion" as the employee has to reach the criterion of >= 80% to get a promotion.
"Awards won" is INVERSELY proportional to "promotion" as more the awards <<< the higher chance of an employee getting promoted.
"Training score" is INVERSELY proportional to "promotion".

CONCLUSION

We can say that No. Of Trainings and Role Based KPI’s met are the most important factors in determining the chances of Promotion.

Age also plays an Important role, As per the Analysis an Employee should be Upskilled upto a certain extent to Improve their chances of promotion. The most chances for a Promotion is for Employees between 25 to 35 Yearsof Age.

The Best Predictive  Model upon analysis is found to be Random Forest Model with 93.31%.

Awards Won by Employees didn’t account to much of Promotions. We could almost say that they are Consolation Prizes. 







