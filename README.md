# Providing-data-driven-suggestions-for-HR

### Project Overview

  The goal of this project is to create Decision Tree and Random Forest models that predicts whether or not an employee will leave the company. 
  This project utilized the data collected by the HR department.
  The decision tree model performed with 97% accuracy and 91% precision, and the random forest model performed with 98% accuracy and 95% precision.
  Based on the two models, last_evaluation, number_project, tenure, and overworked were most influential in determining whether or not an employee will leave the company.
  
### Business Understanding

  The HR department at Salifort Motors wants to take some initiatives to improve employee satisfaction levels at the company.
  If we can predict employees likely to quit, it might be possible to identify factors that contribute to their leaving. Because it is time-consuming and expensive to find,   interview, and hire new employees, increasing employee retention will be beneficial to the company.

### Data Understanding

  This project uses a dataset called HR_capstone_dataset.csv from Kaggle. It represents 10 columns of self-reported information from employees of a multinational vehicle manufacturing   corporation, and 14,999 rows.
  The histogram below shows the counts of employees who stayed vs left by Department exist in the data set.
  
  <img width="411" alt="image" src="https://github.com/aliMohamed-Z/Providing-data-driven-suggestions-for-HR/assets/75675790/ec1b0a98-015e-44b4-9ca6-c119661f7360">

### Modelling and Evaluation
  
  The plot below shows that in this random forest model, last_evaluation, number_project, tenure, and overworked have the highest importance, in that order. These variables are most helpful in predicting the outcome variable, left, and they are the same as the ones used by the decision tree model.

  ![image](https://github.com/aliMohamed-Z/Providing-data-driven-suggestions-for-HR/assets/75675790/9ea95ae9-5e27-4dd0-b550-e9f9f6c14619)

  The overall model performed with 98% accuracy and 95% precision. 

### Conclusion

  The models and the feature importances extracted from the models confirm that employees at the company are overworked.
  To retain employees, the following recommendations could be presented to the stakeholders:
    Cap the number of projects that employees can work on.
    Consider promoting employees who have been with the company for atleast four years.
    Either reward employees for working longer hours, or don't require them to do so.
  


  
