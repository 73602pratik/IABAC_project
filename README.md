# IABAC_project
Create a predictive model using machine learning techniques to predict employee performance
# Business Case: INX Future Inc Employee Performance
    INX Future Inc , (referred as INX ) , is one of the leading data analytics and automation solutions provider with over 15 years of global business presence. INX is consistently rated as top 20 best employers past 5 years. INX human resource policies are considered as employee friendly and widely perceived as best practices in the industry.

    Recent years, the employee performance indexes are not healthy and this is becoming a growing concerns among the top management. There has been increased escalations on service delivery and client satisfaction levels came down by 8 percentage points.

    CEO, Mr. Brain, knows the issues but concerned to take any actions in penalizing non-performing employees as this would affect the employee morale of all the employees in general and may further reduce the performance. Also, the market perception best employer and thereby attracting best talents to join the company.

    Mr. Brain decided to initiate a data science project , which analyses the current employee data and find the core underlying causes of this performance issues. Mr. Brain, being a data scientist himself, expects the findings of this project will help him to take right course of actions. He also expects a clear indicators of non performing employees, so that any penalization of non-performing employee, if required, may not significantly affect other employee morals.

## Data Understanding
    The data for training the model was collected from the company INX Future Inc. The data collected included 1200 employee’s performance appraisal records, described by 28 parameters. the parameters show the different attributes of an employee based on which the prediction is to be made.

# Features present in the dataset
    1. EmpNumber
    2. Age
    3. Gender
    4. EducationBackground
    5. MaritalStatus
    6. EmpDepartment
    7. EmpJobRole
    8. BusinessTravelFrequency
    9. DistanceFromHome
    10. EmpEducationLevel
    11. EmpEnvironmentSatisfaction
    12. EmpHourlyRate
    13. EmpJobInvolvement
    14. EmpJobLevel
    15. EmpJobSatisfaction
    16. NumCompaniesWorked
    17. OverTime
    18. EmpLastSalaryHikePercent
    19. EmpRelationshipSatisfaction
    20. TotalWorkExperienceInYears
    21. TrainingTimesLastYear
    22. EmpWorkLifeBalance
    23. ExperienceYearsAtThisCompany
    24. ExperienceYearsInCurrentRole
    25. YearsSinceLastPromotion
    26. YearsWithCurrManager
    27. Attrition
    28. PerformanceRating

- Data Analysis Report
    * Data Overview
        * Type:Supervised
        * Predictor Variables:
            - Ordinal
            - A few nominal
        * Target Variable:
            -'Performance Rating'(Ordinal)

- Data Processing Techniques
    * Encoding:
        - Label Encoding
    * Standardization:
        - Applied for consistent scale
        
- Correlation Analysis
    * Method Used:
        - Correlation Coefficient
    * Insights:
        - Evaluate realtionshiop between variables
        
- Important Features
    * Selected Feature
        - Department
        - Job Role
        - Environment Satisfaction
        - Last Salary Hike Percentage
        - Work Life Balance
        - Experience Years At this Company
        - Experience years In Current Role
        - Years Since Last Promotion
        - Years With Current Manger

- Machine Learning Models
    * Algorithms Used:
        - Logistic Regression
        - Decision Tree classifier
        - Random Forest classifier
        - MLP Classifier
        - K-Nearest Neighbor
        - Gradient Boosting Tech
        - XGBoosting
    * Objective:
        - Train models for target prediction
        
- Department-Wise Performance Analysis
    * Scope: 
        - Evaluate performance variations across
    * Insights:
        - Identify department-specific Trends

- Conclusion
    * Key Findings:
        - Identified important predictors for employee performance
        - Applied various algorithms for target Prediction
        - Conducted department-wise performance analysis

- **Recommendation**
    - **The top 3 features effecting employee performances are:** 
        - Employee Environment Satisfaction 
        - Employee Last Salary Hike Percent 
        - Years since last promotion
    - Our findings reveal a clear connection between a supportive work environment and employee performance. Offering competitive compensation and promoting work-life balance are crucial elements in fostering employee success.  However, maintaining stable leadership is equally important, as frequent managerial changes can disrupt this positive influence.
    - This suggests that creating a holistic approach to employee support, encompassing both financial and non-financial factors, is essential for optimizing individual performance and achieving organizational objectives.
