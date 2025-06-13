# Risk-Assessment-Analysis-of-Obesity-with-Machine-Learning
Formulated and implemented a predictive machine learning model using Centers of Disease Control and Prevention (CDC) health data to assess obesity risk in the United States
## Introduction
Obesity is one of the most common health problems affecting millions of people throughout the country [1]. And, also contributing to chronic diseases in the long run. Often known as excess body fat, obesity is a complex condition that is also affected by genetics [2]. Many factors excluding food could also lead to obesity. Health care systems also face a significant amount of financial constraint as well when it comes to treating obesity. Majority of the people would not be able to afford the treatments and other procedures required to treat obesity, leading to other chronic diseases and eventually even death. Therefore, it is essential to analyze risk factors that can cause obesity for early assessment and time-effective treatment planning. This project aims to analyze obesity and the risk factors affecting obesity in the US with the help of machine learning models.
## Purpose
With the help of this project, it aims to answer the following research questions:
1. What factors affect obesity? How can we avoid them?
2. What would be the relationship between different factors? Does one factor affect the other? Eg. How is BMI affected by other risk factors?
3. Which is the best model for prediction of risk factors?
## Model Building and Training
Machine learning models were trained for the purpose of predicting and assessing high risk metrics for obesity. The following are the 5 models implemented in this project:
• Logistic Regression: a simple method that gives prediction based on two categories- yes or no
• Support Vector Machine (SVM): finds the best boundary to separate different categories as clearly as possible
• Decision Tree: splits data into branches based on questions and helps in decision making step-by-step for final outcome
• Random Forest: builds on decision trees and combines the results later to improve accuracy
• XGBoost: uses multiple small trees sequentially while improving mistakes on previous ones for better accuracy
## Precision - Recall Curve
![image](https://github.com/user-attachments/assets/af53c7d2-459b-46db-8799-b7cd8b457026)
## Dashboard
![image](https://github.com/user-attachments/assets/994a4858-818c-4e4e-81d7-317df984ffed)
## Conclusion and Future work
XG Boost Model provided the best accuracy score compared to other models and fine tuning improved the accuracy from 78.65% to 79.81%. The top features using this model were identified as Age, Dietary Habits (sugar/Fat), Physical Activity level, Sedentary Behavior, and Income Ratio.
Machine learning, especially ensemble techniques like XGBoost, offers a strong foundation for evaluating obesity risk. Important modifiable risk variables include physical activity, socioeconomic status, and dietary practices. The project's over 80% accuracy rate shows that machine learning algorithms can help with early obesity prevention initiatives.
Moreover, future work can be done by incorporating time-series data for accurate trend analysis, more investigation can be done on neural network designs for increasing accuracy as well as real-time prediction dashboards can be implemented. This project serves as a stepping stone in a long line of work that can benefit the future generations and prevent the risk of obesity in individuals.
## References
[1] C. L. Ogden, M. D. Carroll, B. K. Kit, and K. M. Flegal, “Prevalence of childhood and adult obesity in the united states, 2011-2012,” JAMA, vol. 311, no. 8, pp. 806–14, 2014, doi: https://doi.org/10.1001/jama.2014.732.
[2] G. Vemulapalli, Sreedhar Yalamati, Naga Ramesh Palakurti, N. Alam, Srinivas Samayamantri, and Pawan Whig, “Predicting Obesity Trends Using Machine Learning from Big Data Analytics Approach,” pp. 1–5, Jul. 2024, doi: https://doi.org/10.1109/apcit62007.2024.10673429.
[3] F. Ferdowsy, K. S. A. Rahi, Md. I. Jabiullah, and Md. T. Habib, “A machine learning approach for obesity risk prediction,” Current Research in Behavioral Sciences, vol. 2, p. 100053, Nov. 2021, doi: https://doi.org/10.1016/j.crbeha.2021.100053.
[4] A. Chatterjee, M. W. Gerdes, and S. G. Martinez, “Identification of Risk Factors Associated with Obesity and Overweight—A Machine Learning Overview,” Sensors, vol. 20, no. 9, p. 2734, May 2020, doi: https://doi.org/10.3390/s20092734.
[5] G. Delnevo, G. Mancini, M. Roccetti, P. Salomoni, E. Trombini, and F. Andrei, “The Prediction of Body Mass Index from Negative Affectivity through Machine Learning: A Confirmatory Study,” Sensors, vol. 21, no. 7, p. 2361, Mar. 2021, doi: https://doi.org/10.3390/s21072361.
[6] D. E. Wilfley, J. F. Hayes, K. N. Balantekin, D. J. Van Buren, and L. H. Epstein, “Behavioral Interventions for Obesity in Children and adults: Evidence base, Novel approaches, and Translation into practice.,” American Psychologist, vol. 73, no. 8, pp. 981–993, Nov. 2018, doi: https://doi.org/10.1037/amp0000293.
[7] Reya Pillai R, Suchitra Saravanan, and Gopal Krishna Shyam, “The BMI and Mental Illness Nexus: A Machine Learning Approach,” 2020 International Conference on Smart Technologies in Computing, Electrical and Electronics (ICSTCEE), pp. 526–531, Oct. 2020, doi: https://doi.org/10.1109/icstcee49637.2020.9277446.
[8] Centers for Disease Control and Prevention (CDC), National Center for Health Statistics (NCHS). National Health and Nutrition Examination Survey: 2021–2023 Data Documentation, Codebook, and Frequencies. U.S. Department of Health and Human Services, Centers for Disease Control and Prevention. [Online]. Available: https://wwwn.cdc.gov/nchs/nhanes/continuousnhanes/default.aspx?Cycle=2021-2023
