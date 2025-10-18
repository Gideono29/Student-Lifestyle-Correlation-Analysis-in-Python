# Student-Lifestyle-Analysis-and-Visualization-in-Python

Findings from Correlation Analysis
Based on the calculated correlation matrix:
Variables most correlated with student performance (G_agg):
To identify the variables most correlated with student performance, we look at the absolute values of the correlation coefficients in the G_agg column. A higher absolute value indicates a stronger correlation (either positive or negative). Examining the G_agg column in the correlation matrix, we can see that the following variables have notable correlations:

•	failures: This has a significant negative correlation with G_agg, meaning students with more failures tend to have lower average grades.
•	Medu and Fedu: Mother's and father's education level show a positive correlation with G_agg, suggesting that students with more educated parents tend to have higher average grades.
•	higher: The desire to pursue higher education (higher) shows a positive correlation with G_agg, which is expected as students aiming for higher education are likely to have better academic performance.
•	studytime_discretized: The discretized study time also shows a positive correlation with G_agg, indicating that more study time is associated with better grades.
•	schoolsup: School support (schoolsup) has a negative correlation with G_agg, which might seem counterintuitive. However, this could imply that students receiving school support are already struggling academically.
<img width="1767" height="869" alt="Screenshot 2025-10-18 121908" src="https://github.com/user-attachments/assets/ffe31789-e92c-4e75-b176-c100e8a0ca0d" />

Variables most correlated with student alcohol consumption (Dalc and Walc):
To understand the variables most correlated with student alcohol consumption, we examine the absolute values of the correlation coefficients in the Dalc (workday alcohol consumption) and Walc (weekend alcohol consumption) columns. Examining the Dalc and Walc columns, we observe:
•	goout: This variable has a strong positive correlation with both Dalc and Walc, indicating that students who go out more often tend to consume more alcohol on both weekdays and weekends.
•	freetime: This shows a positive correlation with Walc and Dalc, suggesting that students with more free time might tend to consume more alcohol, especially on weekends.
•	sex: Being male (sex = 0) shows a negative correlation with Dalc and Walc, indicating that male students tend to consume more alcohol than female students.
•	age: Age shows a positive correlation with both Dalc and Walc, implying that older students tend to consume more alcohol.
•	Mjob_other and Fjob_other: Having parents with 'other' jobs shows some positive correlation with alcohol consumption.
<img width="572" height="461" alt="download" src="https://github.com/user-attachments/assets/717fbee3-65b7-4364-97c8-757b66cc64f1" />


Study Habits & Failures
•	Study time shows a negative correlation with failures. Failures correlate negatively with G_agg (performance), as expected. Students who study more tend to fail less and perform better.

Social Life vs Academics
•	Goout (going out with friends) correlates positively with alcohol consumption. Goout tends to be weakly negatively correlated with studytime and performance. Social students are more likely to drink and sometimes perform worse.

