# 🎵 Digital Music Store Analysis (SQL)

## 📊 Project Overview
This project performs an in-depth analysis of a digital music store's database (Chinook Database). The analysis aims to help the business understand its customer base, optimize promotional events, and identify top-performing artists and genres.

## 🛠️ Database Schema
To understand how the data is connected, here is the Entity Relationship Diagram (ERD) of the store:

![Database Schema](Music-ERD.png)

## 🔍 Key Business Questions Answered
* **Seniority Analysis:** Identified the most senior employee to help with organizational hierarchy.
* **Global Sales:** Determined which countries and cities generate the most revenue to plan future music festivals.
* **Customer Loyalty:** Found the highest-spending customers to target for loyalty rewards.
* **Genre Trends:** Identified that **Rock** is the most popular music genre to guide inventory decisions.
* **Artist Impact:** Found the top 10 Rock bands based on their total track count.

## 💻 SQL Skills Demonstrated
* **Joins:** Combining data from multiple tables like Customer, Invoice, and Track.
* **CTEs:** Organizing complex logic using Common Table Expressions.
* **Window Functions:** Using `ROW_NUMBER` and `PARTITION BY` to rank data.


## 💡 Strategic Business Recommendations
Based on the data insights, I recommend the following actions for the store:

1. **Targeted Marketing for Rock Fans:** Since Rock is the dominant genre, the marketing team should launch a "Classic Rock Legends" promotion specifically in the top 3 revenue-generating cities to maximize ROI.
2. **Customer Loyalty Program:** The top-spending customers identified in each country should be invited to a "VIP Gold Tier" program, offering them early access to new album releases to increase customer retention.
3. **Festival Expansion:** Prague and London show the highest sales volume outside of the US. These should be the priority locations for the store’s next sponsored live music events.
4. **Inventory Optimization:** Low-performing genres identified in the analysis should have their inventory reduced to lower licensing costs, shifting that budget toward high-demand digital tracks.
