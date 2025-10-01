# End-to-End Marketing Analytics Project

## Project Summary
This is an end-to-end data analytics project for the online retailer **"ShopEasy"**, aimed at diagnosing and reversing declining customer engagement and poor marketing ROI. The project covers the entire data lifecycle, from ETL and data cleaning to sentiment analysis, interactive dashboarding, and presenting final, actionable recommendations.

---

## Tech Stack
- **Database:** SQL Server  
- **Programming:** Python (Pandas, NLTK)  
- **Business Intelligence:** Power BI (DAX)  
- **Reporting:** PowerPoint  

---

## Project Workflow

### 1. ETL & Cleaning
- Restored and cleaned raw data from a SQL Server (.bak) backup.  
- Used T-SQL scripts to normalize and prepare the dataset for analysis.  

### 2. Data Enrichment
- Performed **sentiment analysis** on customer reviews.  
- Developed a Python script using **NLTK** to categorize feedback as **Positive, Negative, or Neutral**.  

### 3. Visualization
- Built a **dynamic, interactive dashboard** in Power BI.  
- Implemented **DAX measures** to track KPIs and visualize key business trends.  

### 4. Reporting
- Summarized findings and provided **data-driven recommendations** in a final presentation for stakeholders.  

---

## Key Findings & Recommendations
- Identified **seasonal conversion peaks** and patterns in user engagement.  
- Customer satisfaction scores were below target.  

**Recommendations:**
1. Focus marketing spend on high-performing products during their seasonal peaks.  
2. Revitalize content strategy to improve engagement.  
3. Implement a feedback loop to systematically address issues from customer reviews.  

---

## How to Replicate
1. **Restore Database:** Restore the `.bak` file in SQL Server Management Studio (SSMS).  
2. **Run SQL Scripts:** Execute the T-SQL scripts to clean and prepare the database.  
3. **Run Python Script:** Execute `customer_reviews_enrichment.py` for sentiment analysis.  
4. **View Dashboard:** Open the `.pbix` file in Power BI and refresh the data sources to point to your local database.  

---
