# Customer Satisfaction Prediction Using Machine Learning

## Project Overview

Customer satisfaction is a critical indicator of service quality and business success. This project focuses on analyzing customer support ticket data to understand customer behavior, service efficiency, and factors influencing satisfaction levels.

The project combines data preprocessing, exploratory data analysis (EDA), visualization, and machine learning techniques to identify patterns in customer support interactions and predict customer satisfaction ratings based on ticket-related features.

---

## Objectives

- Analyze customer support ticket data.
- Understand customer service performance and satisfaction trends.
- Identify factors influencing customer satisfaction.
- Perform exploratory data analysis (EDA).
- Build machine learning models for satisfaction prediction.
- Evaluate model performance.
- Generate actionable insights for improving customer support services.

---

## Dataset

The dataset contains customer support ticket information and service-related attributes.

### Features Include

- Ticket ID
- Ticket Type
- Ticket Priority
- Ticket Status
- Product Purchased
- Ticket Channel
- Customer Satisfaction Rating
- First Response Time
- Time to Resolution
- Date of Purchase
- Other customer support-related attributes

### Target Variable

- Customer Satisfaction Rating

---

## Data Preprocessing

The following preprocessing steps were performed:

- Converted purchase dates into datetime format.
- Extracted year, month, and day features from purchase dates.
- Removed irrelevant columns such as:
  - Customer Name
  - Customer Email
  - Ticket Description
  - Resolution Details
- Handled missing values in satisfaction ratings.
- Encoded categorical variables using Label Encoding.
- Applied One-Hot Encoding where necessary.
- Standardized numerical features using StandardScaler.

---

## Exploratory Data Analysis (EDA)

### Key Insights

- Customer satisfaction varies across ticket priority levels.
- Different products receive different satisfaction ratings.
- Customer support channels show varying usage patterns.
- Certain ticket types occur more frequently than others.
- A small number of products account for a large share of purchases.
- Service efficiency strongly influences customer satisfaction.

### Visualizations Performed

- Distribution of Ticket Types
- Customer Satisfaction by Ticket Priority
- Customer Satisfaction by Product
- Ticket Channel Distribution
- Top 10 Products Purchased
- Confusion Matrix
- Feature Importance Analysis

---

## Machine Learning Approach

### Models Implemented

- Logistic Regression
- Random Forest Classifier

### Key Techniques

- Label Encoding
- One-Hot Encoding
- Train-Test Split
- Feature Scaling
- Classification Modeling
- Model Evaluation

---

## Model Evaluation

The models were evaluated using:

- Accuracy Score
- Classification Report
- Confusion Matrix

### Performance Summary

- Logistic Regression provided baseline prediction performance.
- Random Forest achieved better results by capturing complex relationships among features.
- Random Forest demonstrated superior predictive capability for customer satisfaction prediction.

---

## Feature Importance

Feature importance analysis revealed that the most influential factors affecting customer satisfaction include:

- First Response Time
- Time to Resolution
- Ticket Priority
- Product Purchased
- Ticket Type
- Ticket Channel

Among all features, **First Response Time** and **Time to Resolution** had the strongest impact on customer satisfaction ratings.

---

## Applications

This project can help:

- Customer Support Teams
- Business Analysts
- Service Managers
- Customer Experience Teams
- Decision Makers

Potential applications include:

- Improving customer service quality
- Reducing response and resolution times
- Enhancing customer retention
- Identifying service bottlenecks
- Optimizing support operations

---

## Limitations

- Dataset is limited to available customer support records.
- Customer satisfaction may be influenced by external factors not captured in the dataset.
- Predictions depend on data quality and completeness.
- Customer behavior can change over time.
- Results should be used as analytical insights rather than exact predictions.

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Repository Contents

- Customer_salesprediction(s).ipynb → Complete analysis and machine learning workflow
- customer_support_tickets.csv → Dataset
- README.md → Project documentation

---

## Author

**Sarika T A**  
Aspiring Data Analyst / Data Scientist

---

## Conclusion

The objective of this project was to analyze customer support ticket data and derive meaningful insights regarding customer service performance and satisfaction levels. Through exploratory data analysis and visualization, it was observed that customer satisfaction varies across different service interactions, indicating a mixed customer experience. Customers utilize multiple support channels such as email, phone, chat, and social media, while certain products generate a higher volume of support requests.

Machine learning models, including Random Forest and Logistic Regression, were applied to predict customer satisfaction based on various ticket and service-related features. The analysis revealed that **First Response Time** and **Time to Resolution** are the most significant factors influencing customer satisfaction. Faster response and resolution times are strongly associated with improved customer experience and higher satisfaction ratings.

Overall, the project highlights the importance of service efficiency and timely support in enhancing customer satisfaction. Organizations can leverage these insights to optimize customer service operations, improve retention, and deliver a better overall customer experience.

---

## Future Improvements

- Incorporate customer demographic information for deeper analysis.
- Include sentiment analysis of customer feedback and ticket descriptions.
- Implement advanced machine learning models such as XGBoost and LightGBM.
- Perform hyperparameter tuning to improve prediction accuracy.
- Develop interactive dashboards using Power BI or Tableau.
- Integrate real-time customer support data.
- Build customer satisfaction monitoring systems for proactive service improvement.
- Explore deep learning techniques for more sophisticated prediction models.

---
