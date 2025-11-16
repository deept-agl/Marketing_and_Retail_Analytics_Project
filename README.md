# 🛒 Market & Retail Analytics — Customer Segmentation & Market Basket Analysis

This project analyzes customer behavior and product purchase patterns for retail businesses using RFM segmentation and Market Basket Analysis. It provides customer insights, identifies high-value customers, detects churn risk, and recommends profitable product combos for cross-selling.

---

## 🚀 Project Overview

Two datasets from an automobile parts company and a grocery store are analyzed across:

### **Milestone 1 — RFM Customer Segmentation**
Dataset of **2,747 transactions** containing customer, product, pricing, and sales information.  
Objectives:
- Explore trends in sales (weekly, monthly, quarterly, yearly)
- Identify best customers, loyal buyers, lost customers, and churn-risk groups
- Use **RFM (Recency, Frequency, Monetary)** analysis for segmentation
- Visualize patterns using **Tableau**
- Build segmentation workflow using **KNIME**

### **Milestone 2 — Market Basket Analysis**
Dataset of **20,641 grocery transactions** with product and order details.  
Objectives:
- Identify frequently bought-together products
- Build association rules using **Support**, **Confidence**, and **Lift**
- Recommend the best combos for bundled offers
- Provide actionable insights to improve sales and customer engagement

---

## 📊 Key Insights

### **From RFM Segmentation**
- *Best Customers*: Very high RFM scores (e.g., Euro Shopping Channel, Anna’s Decorations)
- *Lost Customers*: Very low RFM scores (e.g., Auto-Moto Classics Inc.)
- *Customers at Risk*: Medium–low recency scores indicating possible churn
- *Top Performing Cities*: Madrid (Spain) leads in total sales
- *Top Product Line*: Classic Cars generates maximum revenue

### **From Market Basket Analysis**
Strong association rules identified:
- Poultry + Dinner Rolls  
- Eggs + Soda  
- Poultry + Yoghurt + Milk + Cheese  
- Sandwich Bags + Tortillas  
- Detergent + Mixes  

These combos show high support, confidence, and lift, making them ideal for bundle offers and promotions.

---

## 🛠️ Tools & Techniques

- **KNIME** (RFM workflow & association rule mining)  
- **Tableau** (visual trends & dashboards)  
- **Python / Pandas** (data exploration)  
- RFM scoring  
- Apriori algorithm  
- Support, Confidence, Lift-based ranking  

---

## 🧠 Business Recommendations

- Offer bundled promotions using top-performing combos  
- Target “lost” and “at-risk” customers with personalized offers  
- Promote high-margin product lines like Classic Cars  
- Increase marketing in top-performing cities (e.g., Madrid)  
- Use RFM segments to tailor loyalty programs  


⭐ *Star the repo if you found this project helpful!*
