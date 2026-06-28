# 📦 End-to-End Supply Chain Analytics & Predictive Logistics

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Power Bi](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

**Author:** Aayush  
**Discipline:** Production and Industrial Engineering (MNNIT)

## 🎯 Project Overview
This project is a full-stack data architecture designed to optimize warehouse inventory and proactively predict late supply chain deliveries. It transforms raw, disconnected CSV data into an interactive, machine-learning-driven executive control tower. 

## 🚀 Key Business Outcomes

* **Inventory Stratification (K-Means):** Segmented 180,000+ product categories by historical volume and demand volatility. This allows the warehouse floor to dynamically assign Safety Stock for high-volatility items and Just-In-Time (JIT) strategies for stable cash cows.
* **Late Delivery Prediction (Random Forest):** Engineered a predictive classification model to flag at-risk shipments before they leave the warehouse.
* **Risk-Tolerant Decision Tuning:** Adjusted the algorithmic decision threshold down to 40%. This business-logic tradeoff intentionally absorbed ~700 minor false-positive shipping expedites to successfully catch and prevent over 600 highly damaging actual late deliveries.
* **Operational Control Tower:** Built a Power BI dashboard connecting live historical sales data directly to ML probability scores, providing the warehouse floor with a daily, prioritized hit-list of at-risk orders.

## 📊 Executive Dashboard
*(Insert a screenshot of your final Power BI dashboard or Matplotlib clustering chart here)*

## 🛠️ Tech Stack
* **Database:** PostgreSQL (Relational modeling, Views, SQL Joins)
* **Machine Learning:** Python, Scikit-Learn, Pandas (K-Means Clustering, Random Forest)
* **Visualization:** Power BI (Interactive Dashboards, DAX, Predictive Action Tables)

## 📂 Repository Structure
* `/sql` - Contains the PostgreSQL schema builds and Master View definitions.
* `/notebooks` - Step-by-step Jupyter notebooks covering Exploratory Data Analysis (EDA), Clustering, and Predictive Modeling.
* `/dashboard` - The final Power BI `.pbix` file and supporting DAX measures.

## ⚙️ How to Run This Project
1. Clone this repository: `git clone [Insert Your Repo Link Here]`
2. Navigate to the `/sql` folder and run the `schema.sql` file in your PostgreSQL environment to build the database.
3. Install the required Python packages: `pip install -r requirements.txt`
4. Run the Jupyter notebooks in the `/notebooks` directory in sequential order. 

## 📬 Let's Connect
I am currently seeking off-campus internship opportunities in Supply Chain and Operations Management for Summer 2026. Let's talk about data-driven logistics!
* **LinkedIn:** https://www.linkedin.com/in/aayushkrjha/
