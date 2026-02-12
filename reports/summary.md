# Employee Performance Analysis - Detailed Analysis
## Problem State 
The objective of this project is to predict employee performance ratings using structured HR data. The goal was to compare multiple machine learning classification models and determine the most effective algorithm. 

## Dataset overview
The dataset contains employee-related information such as 
EmpLastSalaryHikePercent        
EmpEnvironmentSatisfaction      
PromotionStagnation             
YearsSinceLastPromotion         
EmpJobRole                      
ExperienceYearsInCurrentRole    
EmpWorkLifeBalance              
EmpHourlyRate                   
ExperienceYearsAtThisCompany    
EmpDepartment                   
ExperienceStability             
TotalWorkExperienceInYears      
YearsWithCurrManager            
Age                             
DistanceFromHome                
NumCompaniesWorked              
EmpEducationLevel               
TrainingTimesLastYear           
EmpJobSatisfaction              
EducationBackground             
EmpJobLevel                     
EmpRelationshipSatisfaction     
MaritalStatus                   
EmpJobInvolvement               
WorkStressIndex                 
BusinessTravelFrequency         
OverTime                        
Gender                          
Attrition                       

Target Variable:
EmpPerformance Rating

## Data Preprocessing
Steps performed:
1. Encoding categorical variables
2. Feature Engineering
3. Feature scaling
4. Train-Test split (80-20)

## Exploratory Data Analysis
EDA included:
1. Distribution of performance ratings
2. Correlation heatmap
3. Feature importance exploration
4. Category-wise performance comparison

## Model Training & Evaluation

The following models were trained:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- Gradient Boosting
- XGBoost
- CatBoost

## Evaluation Metrics:

- Accuracy
- Confusion Matrix

## Model Comparison Results

| Model           | Accuracy |
|-----------------|----------|
| Logistic        | 86.25%   |
| KNN             | 85.00%   |
| Decision Tree   | 87.92%   |
| Random Forest   | 94.58%   |
| SVM             | 86.67%   |
| Gradient Boost  | 93.33%   |

Best Model:
Random Forest (94.58%)