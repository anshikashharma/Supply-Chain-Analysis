# Supply-Chain-Analysis
## Overview
Analysis of a global e-commerce dataset (172K+ orders) to identify causes of late deliveries, quantify financial impact, and build a predictive model to flag at-risk orders.

---

## Problem Statement
54.71% of orders were delivered late, putting ~$2.1M profit at risk and impacting customer experience.

---

## Objectives
- Analyze delivery performance across regions, shipping modes, and time
- Identify key bottlenecks causing delays
- Measure financial impact
- Build a model to predict late deliveries

---

## Key Insights
- Late deliveries are *systemic (54.7%)*, not isolated  
- *Shipping mode is the biggest driver*  
  - First Class: 100% delay  
  - Second Class: 79.8%  
- Profit per order is stable → issue is *volume of delays*  
- Peak delays during *Aug–Sep and Dec*  
- Payment-related statuses show higher delay rates  

---

## Machine Learning Model
- Model: Random Forest Classifier  
- Accuracy: 74%  
- Precision (Late): 78%  
- Recall (Late): 75%  
- SMOTE used for class imbalance  

---

## Business Impact
- $2.1M profit at risk due to delays  
- Identified operational inefficiencies in shipping and processing  

---

## Recommendations
- Audit First & Second Class shipping  
- Deploy predictive alert system  
- Fix payment processing delays  
- Plan for seasonal demand spikes  
- Default to Standard Class where applicable  

---

## Tools & Technologies
- Python (Pandas, NumPy, Scikit-learn)  
- Power BI  
- SQL  


