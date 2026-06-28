# 📦 End-to-End Supply Chain Analytics & Predictive Logistics

**Author:** Aayush
**Discipline:** Production and Industrial Engineering (MNNIT)

## 🎯 Project Overview
This project is a full-stack data architecture designed to optimize warehouse inventory and proactively predict late supply chain deliveries. It transforms raw, disconnected CSV data into an interactive, machine-learning-driven executive control tower. 

## 🛠️ Tech Stack
* **Database:** PostgreSQL (Relational modeling, Views, SQL Joins)
* **Machine Learning:** Python, Scikit-Learn, Pandas (K-Means Clustering, Random Forest)
* **Visualization:** Power BI (Interactive Dashboards, DAX, Predictive Action Tables)

## 🚀 Key Business Outcomes
1. **Inventory Stratification (K-Means):** Segmented 180,000+ product categories by historical volume and demand volatility. This allows the warehouse floor to dynamically assign Safety Stock for high-volatility items and Just-In-Time (JIT) strategies for stable cash cows.
2. **Late Delivery Prediction (Random Forest):** Engineered a predictive classification model to flag at-risk shipments before they leave the warehouse. 
3. **Risk-Tolerant Decision Tuning:** Adjusted the algorithmic decision threshold down to 40%. This business-logic tradeoff intentionally absorbed ~700 minor false-positive shipping expedites to successfully catch and prevent over 600 highly damaging actual late deliveries.
4. **Operational Control Tower:** Built a Power BI dashboard connecting live historical sales data directly to ML probability scores, providing the warehouse floor with a daily, prioritized hit-list of at-risk orders.

## 📂 Repository Structure
* `/sql` - Contains the PostgreSQL schema builds and Master View definitions.
* `/notebooks` - Step-by-step Jupyter notebooks covering EDA, Clustering, and Predictive Modeling.
* `/dashboard` - The final Power BI `.pbix` file.

