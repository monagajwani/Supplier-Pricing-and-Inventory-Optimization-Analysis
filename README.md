# Supplier,Pricing and Inventory Optimization Analysis
**Data Analysis : End to End Analysis**
<img width="1159" height="656" alt="image" src="https://github.com/user-attachments/assets/7a75b323-8168-4a36-9f5d-f5be52d45893" />

This project presents an end-to-end analysis of supplier and inventory data, aimed at generating actionable insights to optimize profitability, pricing strategies, and inventory management.
By analyzing over 10 million rows of supplier and purchase data, this project identifies high-performing and low-performing suppliers, evaluates profit margins, and uncovers 
opportunities to improve business outcomes.

**Project Overview**

The project begins with exploratory data analysis (EDA) across multiple source tables. Using MySQL, I consolidated these tables into a single summary table containing all key metrics
required for further analysis. The data was cleaned and validated, handling missing values, correcting data types, and removing extreme outliers to ensure accuracy. This summary table
is stored in the database for future analysis and reporting.

Suppliers are categorized into top-selling (top 25%) and low-selling (bottom 25%) groups based on total sales. For each group, weighted mean profit margins and 95% confidence intervals
were calculated to account for sales volume differences. Statistical testing confirmed a significant difference in profitability, with low-selling suppliers showing higher per-unit profit margins.

Additional analyses include correlation heatmaps, freight cost evaluation, and outlier detection. Visualizations such as histograms, KDE plots, boxplots, and bar charts with confidence 
intervals were created to support business insights.

**Tools and Methods Used**

MySQL – Data extraction, table consolidation, and creation of the summary table.

Python (Pandas, NumPy, Matplotlib, Seaborn) – Data cleaning, processing, statistical analysis, and visualization.

Jupyter Notebook – Interactive coding and documentation.

Advanced Statistics – t-tests, confidence intervals, weighted mean calculations.

Power BI – Dashboards and interactive reports.

PowerPoint (PPT) – Presentation of actionable business insights.

**Key Business Impact**

Revenue optimization: Top-selling suppliers contribute to ~75% of total sales, but low-selling suppliers contribute ~15–20% of total revenue with higher profit margins,
highlighting areas to promote high-margin items.

Profit improvement: Weighted analysis shows low-selling suppliers can improve overall profit by 5–8% if promoted strategically.

Cost efficiency: Freight and purchase cost analysis identifies potential savings of 3–5% in logistics expenses.

Inventory strategy: Identifies slow-moving vs fast-moving items, enabling better stock planning and reduced holding costs.

**Recommendations**

Based on the findings, I recommend promoting low-selling, high-margin suppliers strategically to improve overall profitability, while also exploring pricing adjustments or 
cost reductions for top-selling suppliers to maintain revenue without sacrificing margins. Freight and logistics optimization should be prioritized to reduce costs by 3–5%, and s
low-moving items should be monitored closely to prevent overstocking and reduce holding costs. Additionally, suppliers with consistently low performance should be evaluated for 
potential renegotiation or replacement.

**Summary of Recommendations:**

Promote high-margin, low-selling suppliers for profitability.

Optimize pricing and reduce costs for top-selling suppliers.

Streamline freight and logistics to save 3–5%.

Manage slow-moving inventory to reduce holding costs.

Review and renegotiate underperforming suppliers.

This project provides a data-driven framework for supplier management, pricing, and inventory optimization, enabling businesses to maximize profitability, control costs, and make strategic growth decisions.
