Introduction
This project aims to build a machine learning classification model to predict employee performance ratings using structured HR data. The objective is to identify the most influential factors affecting performance and compare multiple models to determine the most accurate predictive solution.

Dataset Overview
Total Records: 1,200 employees
Total Features: 28 features
Categorical Features: 9
Numerical Features: 19
The dataset is sufficiently large and structured for performing statistical analysis and building predictive models.

Exploratory Data Analysis (EDA)
Gender Distribution
60.4% Male
39.6% Female
The workforce shows moderate gender imbalance. However, gender was later found to have very low impact on performance prediction.

Educational Background
Life Sciences – 41%
Medical – 32%
The organization has a technically strong workforce, mainly concentrated in scientific and development-driven domains.

Marital Status
Married – 45.7%
Single – 32%
Divorced – 22.3%
Marital status may indirectly influence overtime, travel frequency, and work-life balance.

Department Distribution
Top departments:
Sales – 31.1%
Development – 30%
R&D – 28.6%
These three departments collectively represent nearly 90% of the workforce, making them key drivers of company performance.

Business Travel
18.5% of employees travel frequently.
Frequent travel may impact stress levels and long-term performance.

Overtime
29.4% of employees work overtime.
This suggests possible workload imbalance, which may affect job satisfaction and performance sustainability.

Attrition
85.2% of employees show no attrition.
The organization has strong employee retention, allowing the focus to remain on performance optimization rather than hiring replacement.

Feature Importance Analysis
Feature importance was calculated using tree-based models. The following features were found to have the highest influence on employee performance prediction:
| Feature                      | Importance |
| ---------------------------- | ---------- |
| EmpLastSalaryHikePercent     | 0.2350     |
| EmpEnvironmentSatisfaction   | 0.2122     |
| PromotionStagnation          | 0.0717     |
| YearsSinceLastPromotion      | 0.0494     |
| EmpJobRole                   | 0.0388     |
| ExperienceYearsInCurrentRole | 0.0363     |
| EmpWorkLifeBalance           | 0.0333     |
| EmpHourlyRate                | 0.0322     |
| ExperienceYearsAtThisCompany | 0.0261     |
| EmpDepartment                | 0.0258     |
| ExperienceStability          | 0.0257     |
| TotalWorkExperienceInYears   | 0.0227     |
| YearsWithCurrManager         | 0.0221     |
| Age                          | 0.0219     |
| DistanceFromHome             | 0.0216     |


Insights:
Salary Hike & Environment Satisfaction Are Most Influential
1. EmpLastSalaryHikePercent (23.5%)
2. EmpEnvironmentSatisfaction (21.2%)
These two factors alone contribute nearly 45% of predictive power, indicating:
Performance is strongly influenced by financial growth and work environment quality.

Promotion & Career Growth Matter
1. PromotionStagnation
2. YearsSinceLastPromotion
3. ExperienceYearsInCurrentRole
Career progression plays a major role in employee motivation and output.

Work-Life & Stability Factors Matter
1. WorkLifeBalance
2. ExperienceStability
3. YearsWithCurrManager
Stable leadership and work-life balance contribute positively to performance.

Model Training & Comparison:
| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 86.25%   |
| KNN                 | 85.00%   |
| Decision Tree       | 87.92%   |
| Random Forest       | 94.58%   |
| SVM                 | 86.67%   |
| Gradient Boosting   | 93.33%   |


## Business Insights: 
1. Compensation Strategy is Critical
Salary hikes strongly influence performance. Transparent and merit-based increment policies can improve productivity.

2. Improve Work Environment
Environment satisfaction significantly affects output. HR should monitor workplace culture and satisfaction levels.

3. Reduce Promotion Stagnation
Delayed promotions negatively affect performance. Structured career progression plans are recommended.

4. Focus on Career Growth Over Demographics
Performance is not significantly affected by gender or marital status, indicating fair internal structures.