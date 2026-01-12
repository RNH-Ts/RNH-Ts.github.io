# HR Attrition Analysis & Prediction
**Rachel Hill-Tsarpelas** | Data Analyst Portfolio Project  

## Project Overview
This project investigates employee attrition with the goal of identifying patterns, risk factors, and actionable insights that can support HR decision-making. The analysis follows a structured, multi-day workflow covering data understanding, visualization-driven exploration, and machine learning modeling.

---

## Objectives
1. Suggest hypotheses about the causes of observed employee attrition
2. Assess assumptions on which statistical inference will be based
3. Support the selection of appropriate statistical tools and techniques
4. Provide a basis for further data collection or HR interventions

---

## Day 1 — Data Overview
- Loaded dataset
- Identified numeric/categorical columns
- Checked for missing values
- Summarized key variables and observed class imbalance (~16% attrition)

**Visual — Summary of Attrition Imbalance**  
![Day 1 Summary](images/Attrition_Pie_chart.png)

---

## Day 2 — Exploratory Visualizations
- Explored attrition patterns by demographic and work-related factors
- Visuals indicate higher attrition for employees with overtime, younger age, or early career stage
- Linear correlation insufficient, non-linear effects likely

**Visuals — Day 2**  

*Attrition vs Overtime* 
![Attrition vs Overtime](images/Overtime_Attrition.png) 


*Attrition vs Job Role* 
![Attrition vs Job Role](images/Attrition_JobRoles.png)  


*Linear correlation — no strong relationships* 
![Linear Correlation](images/Correlation_Heatmap_linear.png)

---

## Day 3 — Machine Learning
- Models: Decision Tree, Logistic Regression, Random Forest
- Random Forest performed best overall
- Key features in Random Forest: WorkLifeStress, OverTime, MonthlyIncome, Income per Experience
- Feature importance varies by model, confirming non-linear, multivariate relationships

**Visuals — Day 3**  

*Random Forest Feature Importance* 
![Random Forest Features](images/Random_forest_features.png) 

*ML-informed correlation*
![ML-based Correlation](images/Correlation_ML.png) 

---

## Key Takeaways
- Attrition patterns differ between visual inspection and model-based analysis
- Workload, career stage, and compensation are more predictive than department or demographics
- Reducing overtime or addressing Work–Life Stress may help retain employees

---

## Dataset
- Anonymized HR data including demographics, career, compensation, and work conditions  
- [IBM HR Analytics Attrition Dataset on Kaggle](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset/data)

---

## Notes
- Notebooks available in [GitHub project repository](https://github.com/RNH-Ts/hr-attrition-analysis)
- Power BI dashboard planned to illustrate key insights








# HR Attrition Analysis & Prediction
**Rachel Hill-Tsarpelas** | Data Analyst Portfolio Project  

## Project Overview
This project investigates employee attrition with the goal of identifying patterns, risk factors, and actionable insights that can support HR decision-making. The analysis follows a structured, multi-day workflow covering data understanding, visualization-driven exploration, and machine learning modeling.

---

## Objectives
1. Suggest hypotheses about the causes of observed employee attrition
2. Assess assumptions on which statistical inference will be based
3. Support the selection of appropriate statistical tools and techniques
4. Provide a basis for further data collection or HR interventions

---

## Day 1 — Data Overview
- Loaded dataset
- Identified numeric/categorical columns
- Checked for missing values
- Summarized key variables and observed class imbalance (~16% attrition)

## Day 2 — Exploratory Visualizations
- Explored attrition patterns by demographic and work-related factors
- Visuals indicate higher attrition for employees with overtime, younger age, or early career stage
- Linear correlation insufficient, non-linear effects likely

## Day 3 — Machine Learning
- Models: Decision Tree, Logistic Regression, Random Forest
- Random Forest performed best overall
- Key features in Random Forest: WorkLifeStress, OverTime, MonthlyIncome, Income per Experience
- Feature importance varies by model, confirming non-linear, multivariate relationships

---

## Key Takeaways
- Attrition patterns differ between visual inspection and model-based analysis
- Workload, career stage, and compensation are more predictive than department or demographics
- Reducing overtime or addressing Work–Life Stress may help retain employees

---

## Dataset
- Anonymized HR data including demographics, career, compensation, and work conditions  
- [IBM HR Analytics Attrition Dataset on Kaggle](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset/data)

---

## Notes
- Notebooks available in [GitHub project repository](https://github.com/RNH-Ts/hr-attrition-analysis>)
- Power BI dashboard planned to illustrate key insights



### 3. Support the selection of appropriate statistical tools and techniques

<img src="images/dummy_thumbnail.jpg?raw=true"/>

### 4. Provide a basis for further data collection through surveys or experiments

Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. 

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).
