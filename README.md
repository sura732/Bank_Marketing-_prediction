# Bank_Marketing-_prediction
Data Description Feature 
1.age |int64| age in years 
2.job | object | type of job (categorical: ['management' 'technician' 'entrepreneur' 'blue-collar' 'unknown' 'retired' 'admin.' 'services' 'self-employed' 'unemployed' 'housemaid' 'student'])
3.Salary |int 64| 
4.marital | object | marital status (categorical: ['married' 'single' 'divorced'])
5.education | Object | education background (categorical: ['secondary' 'tertiary' 'primary' 'unknown']) 
6.targeted |object| ["yes","No] 
7.default | Object | has credit in default? (categorical: ['no' 'yes'])
8.balance | int64 | Balance of the individual 
9.housing | object | has housing loan? (categorical: ['yes' 'no']) 
10.loan | object | has personal loan? (categorical: ['no' 'yes']) 
11.contact | object | contact communication type (categorical: ['unknown' 'cellular' 'telephone'])
12.day | int64 | last contact day of the week (categorical: 'mon','tue','wed','thu','fri') 
13.month | object | last contact month of year (categorical: ['may' 'jun' 'jul' 'aug' 'oct' 'nov' 'dec' 'jan' 'feb' 'mar' 'apr' 'sep'])
14.duration | int64 | last contact duration, in seconds (numeric)
15.campaign | int64 | number of contacts performed during this campaign and for this client 
16.pdays | int64 | number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted) 17.previous | int64 | number of contacts performed before this campaign and for this client 
18.poutcome | object | outcome of the previous marketing campaign (categorical: ['unknown' 'other' 'failure' 'success'])` 
19.['response'] |object| ['no' 'yes'] ########## Target Variable  
Label 1.response|object| heas the client subscibed a term deposit(binary'yes','no')  Categorical columns job marital education targeted default housing loan contact month poutcome response Numerical Columns age salary balance day duration campaign pdays previous Exploratory Data Analysis find unwanted Columns find missing values Find features with one values Explore the Categorical Features Find Categorical Feature Distribution Relationship between Categorical Features and Label Explore the Numerical Features Find Discrete Numerical Features Relation between Discrete numerical Features and Labels Find Continous Numerical Features Distribution of Continous Numerical Features Relation between Continous numerical Features and Labels Find Outliers in numerical features Explore the Correlation between numerical features Find Pair Plot Check the Data set is balanced or not based on target values in classification
