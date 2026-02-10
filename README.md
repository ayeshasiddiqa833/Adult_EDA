ṁ***Exploratory Data Analysis of the Adult Census Income Dataset***
-Executive Summary
This project provides a comprehensive exploratory data analysis (EDA) of the Adult Census Income dataset, aiming to identify key demographic and professional factors that correlate with an annual income exceeding $50,000.

***Relationship of Variables with Dependent Variable (Income)***
Analyzing the relationship of independent variables with the dependent variable, Income (>50K or ≤50K), is the core objective of this EDA:
AGE: There's a positive correlation; the box and violin plots likely show that the median and overall distribution of age is higher for the >50K income group. This suggests that income tends to increase with experience and seniority.
EDUCATION: A strong positive correlation exists; the count plots confirm that individuals with higher educational attainment (e.g., Masters, Doctorate, Bachelors) are significantly more likely to earn >50K. Education is a major predictor.
CAPITAL-GAIN & CAPITAL-LOSS: These features have the strongest relationship with high income. Box plots show that those in the >50K group have substantially higher median and maximum values for capital gain, and negligible values for capital loss, indicating these are critical differentiators.
RELATIONSHIP(Marital Status): This categorical variable shows a critical socio-economic link. The count plot reveals that categories like 'Husband' and 'Wife' have a disproportionately higher share of the >50K income class, making it a powerful predictor.
HOURS PER WEEK: A moderate positive relationship is evident; the distribution for the >50K group is often slightly shifted towards working more hours, though a strong peak still exists at the standard 40-hour week.
WORKCLASS: The count plot identifies certain workclasses, such as 'Self-emp-inc' and 'Exec-managerial', as having a significantly higher probability of high income compared to others like 'Private' or 'Other-service'.
**DATA TREATMENT***
-Handling Missing Values to the initial inspection revealed missing values represented by "?".These were systematically replaced with "NaN".this enables proper handling and analysis by pandas and other libraries.

--The missing values   likely appeared in categorical columns like 'workclass', 'occupation', and 'native-country' denoted by NaN.
***handling missing values*** for :Preventing Model Bias and Error,Retaining Valuable Data,Maintaining Feature Integrity.

***The analysis reveals several critical insights:***
-Education and Career are the Strongest Indicators: There's a powerful relationship between an individual's education level, occupation, and their income bracket. 
High-income earners are disproportionately found among those with advanced degrees and in high-skill roles like Exec-managerial and Prof-specialty.


-Significant Gender Pay Disparity: A notable gender gap exists, with men earning above $50,000 at a much higher rate than women. 
This disparity persists across various age groups and work hours, highlighting a potential systemic imbalance.

-Income Correlates with Age and Work Hours: The likelihood of earning over $50,000 increases with age, peaking in the 40-60 range. 
Additionally, individuals working more than 40 hours per week are more likely to be in the high-income bracket.

-In conclusion, a combination of educational attainment, professional role, and age are the primary drivers of income. These insights can serve as a foundation for further predictive modeling.

***Project Files***
adult.csv: The dataset used for the analysis.

adult_eda.ipynb: The Jupyter Notebook containing the full analysis and all visualizations.

README.md: This file, providing an overview and key findings of the project.

***Author:*** AYESHA

***LinkedIn:*** https://www.linkedin.com/in/ayeshasiddiqa19342

***GitHub:***https://github.com/ayeshasiddiqa833
