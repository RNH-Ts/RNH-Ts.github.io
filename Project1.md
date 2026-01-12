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
![Day 1 Summary](master/images/Attrition_imbalance.png)

---

## Day 2 — Exploratory Visualizations
- Explored attrition patterns by demographic and work-related factors
- Visuals indicate higher attrition for employees with overtime, younger age, or early career stage
- Linear correlation insufficient, non-linear effects likely

**Visuals — Day 2**  

| ![Attrition vs Overtime](master/images/Overtime_Attrition.png) | ![Attrition vs Job Role](master/images/Attrition_JobRoles.png) |
|:---:|:---:|
| *Attrition vs Overtime* | *Attrition vs Job Role* |

---

**Correlation Maps — Day 2/3**  

| ![Linear Correlation](master/images/Correlation_Heatmap_linear.png) | ![ML-based Correlation](master/images/Correlation_ML.png) |
|:---:|:---:|
| *Linear correlation — no strong relationships* | *ML-informed correlation — key features highlighted* |

---

## Day 3 — Machine Learning
- Models: Decision Tree, Logistic Regression, Random Forest
- Random Forest performed best overall
- Key features in Random Forest: WorkLifeStress, OverTime, MonthlyIncome, Income per Experience
- Feature importance varies by model, confirming non-linear, multivariate relationships

**Visuals — Day 3**  

| ![Random Forest Features](master/images/Random_forest_features.png) | ![WorkLifeStress](master/images/FE_Attr_Stress.png) |
|:---:|:---:|
| *Random Forest Feature Importance* | *WorkLifeStress vs Attrition* |

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

**Visual — Summary of Key Variables**  
![Day 1 Summary](master/Images/day1_summary.png)

---

## Day 2 — Exploratory Visualizations
- Explored attrition patterns by demographic and work-related factors
- Visuals indicate higher attrition for employees with overtime, younger age, or early career stage
- Linear correlation insufficient, non-linear effects likely

**Visual — Attrition vs Overtime**  
![Attrition vs Overtime](master/Images/attrition_overtime.png)

**Visual — Attrition vs Age / Career Stage**  
![Attrition vs Age](master/Images/attrition_age.png)

---

## Day 3 — Machine Learning
- Models: Decision Tree, Logistic Regression, Random Forest
- Random Forest performed best overall
- Key features in Random Forest: WorkLifeStress, OverTime, MonthlyIncome, Income per Experience
- Feature importance varies by model, confirming non-linear, multivariate relationships

**Visual — Random Forest Feature Importance**  
![Random Forest Features](master/Images/random_forest_features.png)

**Visual — WorkLifeStress vs Attrition**  
![WorkLifeStress](master/Images/worklifestress.png)

**Visual — Predicted vs Actual Attrition**  
![Predictions](master/Images/predictions.png)

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

---






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





## This can be your internal website page / project page

**Project description:** Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

### 1. Suggest hypotheses about the causes of observed phenomena

Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. 

```javascript
if (isAwesome){
  return true
}
```

### 2. Assess assumptions on which statistical inference will be based

```javascript
if (isAwesome){
  return true
}
```

### 3. Support the selection of appropriate statistical tools and techniques

<img src="images/dummy_thumbnail.jpg?raw=true"/>

### 4. Provide a basis for further data collection through surveys or experiments

Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. 

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).
