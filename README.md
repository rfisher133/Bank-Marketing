## BANK MARKETING ANALYSIS

  URL: https://github.com/rfisher133/Bank-Marketing.git
  
  Files: Banking Marketing Analysis.ipynb
  
**Project:** This dataset comes from the UCI Machine Learning repository link. The data is from a Portuguese Banking Institution and is a collection of the results of 17 marketing campaigns. 

**Business Purpose:** The purpose is to determine what features are important to the success of the marketing campaign. The campaigns overall had a success rate of 11.3% of the person contacted signed up for a deposit account with the banks. Machine Learning classification models were utilized to predict successful sign-ups and determine the features that are important for improving the success rate of future telephone marketing campaigns. 

**Interpretation of Data:** The target data of has a 11.3% positive rate which indicates that the data is unbalanced. Select features are shown in the graph below which show the distribution of the target data in the legend. 
![graphs_1](https://github.com/rfisher133/Bank-Marketing/assets/146397875/b970b847-74b6-4621-a3e6-0c6a59344e77)


**Inferential Statistics:** A Logistic Regression Classification Model was utilized to evaluate the features that have the most positive and negative effects on the target success rate. These included: 

Most Important Features for Positive Result
                   
  Features          Coefficient        
  month_mar         0.308039
  month_oct         0.294352
  month_sep         0.242988
  contact_cellular  0.242427
  job_student       0.194474
  month_dec         0.161941
  job_retired       0.157015
  month_jun         0.102523
  age               0.101985
  month_apr         0.091978

Most Important Features Leading to Negative Result
                     Coeffs
Features                   
job_services      -0.050784
job_technician    -0.052974
day_of_week_mon   -0.059676
job_blue-collar   -0.085341
month_nov         -0.130434
month_jul         -0.163386
month_aug         -0.167992
month_may         -0.171014
default           -0.219557
contact_telephone -0.242427


**Findings:** 
The marketing campaign success rate could be increased by implementing the following selection criteria:
-  Giving preference to contacts with cellphone numbers over telephone numbers. This would result in an estimated 30% increase in the success rate. 
- Giving preference to contacts with no credit default in their record would result in an estimated 14% increase in the success rate. 
- Giving preference to contacts who are students or retired would increase the success rate by 124%. 

**Recommendations and Next Steps:**
The narrowing of the contact list will increase the success rate but will also result in a reduction of the total person contacted. The total number of positive results from the narrowing should be evaluated versus the cost of the marketing campaign to determine the most cost effective mix for a future campaign. 
