#  Sales Prediction Using Python

A machine learning repository dedicated to forecasting product sales based on advertising expenditure across various media platforms. This project analyzes the impact of budgeting strategies on overall revenue and utilizes regression algorithms to generate precise predictions.

##  Objectives
* **Predict Future Sales:** Develop a reliable machine learning model to estimate product sales based on specific marketing investments.
* **Identify High-Impact Channels:** Evaluate which advertising mediums (TV, Radio, or Newspaper) generate the highest return on investment (ROI).
* **Budget Optimization:** Create a data-driven framework to help businesses allocate marketing capital strategically to maximize revenue.

##  Key Activities Performed
* **Data Inspection & Exploration:** Analyzed the 200-row `advertising.csv` dataset. Examined structural correlations to understand how different media investments independently impact the target `Sales` variable.
* **Feature Selection:** Segmented independent variables (`TV`, `Radio`, and `Newspaper` budgets) away from the target variable (`Sales`). 
* **Data Splitting:** Structured the dataset into an 80% training matrix and a 20% testing split to ensure an unbiased evaluation of the final model's real-world performance.
* **Model Training:** Built and deployed a multivariate Linear Regression model using Python's `scikit-learn` framework to map advertising costs effectively.
* **Statistical Evaluation:** Assessed the model's performance on unseen testing data using standard regression criteria.

##  Project Conclusion
The project successfully demonstrated that corporate sales figures can be predicted with incredibly high accuracy using historical marketing distributions. 

###  Key Results & Performance
* **Model Accuracy ($R^2$ Score):** **90.59%** of the variance in sales is successfully explained by the model.
* **Error Rate (Mean Squared Error):** **2.91**, indicating that the predictions closely mirror the true target boundaries.
* **Core Insight:** Visual and mathematical analysis explicitly revealed that **TV advertising** holds the strongest linear correlation with sales (~0.90), while **Newspaper advertising** offers the weakest linear impact (~0.16). 

Ultimately, this predictive asset proves that businesses can significantly mitigate financial risk by pivoting away from underperforming traditional print media and heavily prioritizing high-yielding television ad campaigns.
