### Summary for GitHub Repository

**Project Title:** On-Prem Data Warehousing for Restaurant and Food Delivery Analytics

**Project Overview:**
This project aims to address operational inefficiencies in the restaurant and food delivery sector through a centralized data integration and analytics solution. Using Talend, PostgreSQL, and Power BI, the project demonstrates how businesses can consolidate fragmented data to derive actionable insights and enhance decision-making.

**Objectives:**
1. **Data Integration:** Implement an ETL pipeline to consolidate data from various sources like POS systems, delivery platforms, and customer databases.
2. **Historical Tracking:** Use Slowly Changing Dimension (SCD) Type 2 to track changes in restaurant ratings over time.
3. **Advanced Analytics:** Perform trend analysis on key metrics, such as sales, delivery performance, and customer behavior.

**Key Deliverables:**
1. **ETL Pipeline:** Extract data from a PostgreSQL OLTP system, transform it using Talend, and load it into a PostgreSQL OLAP database.
2. **Data Analysis in Power BI:** Visualization of insights such as:
   - Correlation between order value and service fees.
   - Delivery partner performance based on ratings and efficiency.
   - Popular payment types (credit/debit cards dominate with 55%).
   - Top-rated restaurants and high revenue-generating locations.
   - Daily order trends and peak patterns.

**Insights:**
- DoorDash leads in customer satisfaction, followed by GrubHub.
- Boston and Dorchester are primary revenue contributors, with concentrated urban activity.
- Payment methods indicate a preference for traditional cards over digital wallets, revealing growth opportunities for digital payment adoption.
- Service fees maintain a consistent structure across order sizes.

**Data Sources:**
- Restaurant inspection data from Boston's public database.
- Synthetic data generated using Mockaroo and ChatGPT.

**Technologies Used:**
- **ETL:** Talend
- **Database:** PostgreSQL
- **Visualization:** Power BI
