# Telco Customer Churn Prediction

This project represents an end-to-end approach for tackling customer churn — a critical business challenge where companies seek to identify and retain customers who are at the highest risk of leaving. By integrating machine learning, statistical analysis, and interactive data visualizations, the project translates raw data into actionable insights, supporting strategic intervention and retention initiatives.

## Objectives
- Predict customer churn using behavioural, transactional, and demographic history
- Uncover actionable insights to reduce chrun and boost retention through analytics
- Communicate findings in a business-centric format for executive stakeholders

## Project Workflow
1. Data Acquisition & Preprocessing
   - Imported and cleaned customer datasets featuring behavioiural, transactional, and demographic variables
   - Addressed missing data, encoded categorical features, and normalized numerical fields
2. EDA
   - Used pandas, matplotlib and seaborn in Python for EDA to identify patterns and correlations related to customer churn and to visualize distributions and relationships to guide hypothesis formation and modeling decisions
3. Feature Engineering
   - Created new features to capture customer tenure, loyalty indicatoirs, and service usage intensity
   - Selected top predictors using statistical tests
4. Predictive Modeling
   - Employed logistic regression in scikit-learn, and evaluated models with precision, recall, F1-score, and confusion matrices
5. Interpretability & Inishgt Extraction
   - Analyzed feature impmortance to reveal primary drivers behind churn
6. Business Recommendations
   - Generated tailored recommendations for customer retention based on high-impact features and at-risk segments
   - Proposed targed marketing strategies for intervention
7. Visualization & Communication
   - Built interactive dashboards in Tableau to present key findings and retention opportunities

## Business Impact
- Enables organizations to reduce customer loss and maxmize lifetime value
- Supports targeted intervention campaigns with the ideitification of high-risk segments

## Insights and Implications
### Key Insights
- High-Risk Customer Segments: Customers with short tenure, frequent service complaints, and low engagement were significantly more likely to churn
- Feature Importance: Contract type, payment method, and level of product usage surfaced as major predictors. Customers on month-to-month contracts and using electronic check payment had higher churn rates
- Service Interactions: Frequent interactions with support and unresolved issues correlated strongly with attrition, highlighting a need for improved service protocols
- Demographic Trends: Age, geographic location, and income level influenced churn likelihood

### Business Implications
- Retention Campaigns: Deploy personalized offers, loyalty programs, and targed communications
- Resource Allocation: Prioritize investing in customer service and engagement initiatives toward the most the vulnerable segmnets
- Strategic Planning: Leverage predictions for quarterly planning, focusing on improving products and services that matter most to customer loyalty
