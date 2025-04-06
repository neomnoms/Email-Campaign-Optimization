# Email-Campaign-Optimization

**Data analytics and predictive modeling to uncover what drives customer engagement in email marketing.**  
This project explores click-through behavior, builds a predictive model for CTR, performs customer segmentation using KMeans, and ends with an interactive Tableau dashboard for stakeholder insights.

---

## Overview

This project uses a synthetic email marketing dataset to:

- Analyze **Click-Through Rate (CTR)** trends across demographics and campaign features
- Predict which customers are likely to click using **Logistic Regression**
- Segment customers based on behavioral traits using **KMeans Clustering**
- Present insights in an **interactive Tableau dashboard**

---

## Dataset

The dataset contains 8,000 entries with the following features:

- **Demographics:** Age, Gender, Income  
- **Engagement Metrics:** Email Opens, Email Clicks, Website Visits, Pages per Visit, Time on Site  
- **Campaign Info:** Campaign Type, Channel, Ad Spend  
- **Behavioral Data:** Previous Purchases, Loyalty Points  
- **Outcome Variables:** ClickThroughRate, ConversionRate, Conversion (binary)

---

## Key Visual Insights

- **CTR by Age Group:** Engagement increases with age; 65+ has the highest CTR.
- **Campaign Type Performance:** Retention campaigns perform best.
- **Best Channels:** PPC has the highest CTR; Referral the lowest.
- **Low correlation** between CTR and loyalty/purchases (surprising!)
- **Minimal CTR difference** between genders.

---

## Predictive Modeling

A logistic regression model was trained to predict **High CTR (CTR > 0.1)**:

- **Accuracy:** 69%
- **Recall (High CTR):** 100%  
- **Precision (High CTR):** 69%

> Strong at capturing high-engagement users, with potential to improve using advanced models or class balancing.

---

## Customer Segmentation (KMeans)

Customers were clustered into 3 distinct segments based on:
- Age, Income, Previous Purchases, Loyalty Points

**Segment Highlights:**

- **Cluster 0:** Mid-age, high loyalty, repeat buyers — strong retention segment  
- **Cluster 1:** Young with high income but low engagement — growth opportunity  
- **Cluster 2:** Older with highest income but low activity — ideal for reactivation

---

## Tableau Dashboard

📍 **Explore the interactive dashboard here:**  
👉 [View on Tableau Public](link coming soon) 

Includes:
- CTR by Age Group
- Conversion by Campaign Channel
- Interactive filters for Age Group and Gender

---

## Tools Used

- Python (pandas, scikit-learn, seaborn, matplotlib)
- Tableau Public
- Jupyter Notebook
- Git & GitHub

---


---

## Next Steps

- Experiment with additional models (Random Forest, XGBoost)
- Add campaign cost and ROI analysis
- Incorporate NLP on email subject lines for deeper insight

---

## Author

**Naomi [@neomnoms](https://github.com/neomnoms)**  
A marketing-minded data analyst passionate about ethical AI, customer behavior, and creating actionable insights through storytelling.

---

