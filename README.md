Chase Bank Credit Card Transaction Report - Part 2: Credit Card Customer Report

Welcome to Part 2 of the Chase Bank Credit Card Transaction Report series! In this phase, we focus on creating the **Credit Card Customer Report** dashboard. This part complements the previous report by offering deeper insights into customer demographics and behaviors.

Project Overview:
In this section, we build a comprehensive dashboard to analyze credit card customer data. By leveraging Power BI, this dashboard provides detailed visualizations of customer-related metrics, which are crucial for understanding customer satisfaction and engagement.

Key Steps and Features:

1. Dashboard Setup:
   - Template Reuse: To streamline the process, we start by copying existing text elements, slicers, and a bar chart from the previous dashboard. This approach minimizes duplication and speeds up setup.
   - KPI Updates: We update key performance indicators (KPIs) to reflect customer-specific metrics:
     - Transaction Amount → **Income**
     - Transaction Count → **Customer Satisfaction Score (CSS)**, scaled based on average satisfaction.

2. Data Visualizations:
   - Line Chart: 
     - X-Axis: Week Number (Week_Num_2)
     - Y-Axis: Revenue
     - Legend: Gender
     - Basic formatting to highlight trends without cluttering the chart.
   - Tree Map:
     - Dimensions: Gender and Revenue
     - Data Labels:Added for clarity
   - Stacked Column Charts:
     - Car Owner Analysis: X-Axis: Car Owner; Y-Axis: Count of Client Numbers
     - Revenue by Income Group: X-Axis: Sum of Revenue; Y-Axis: Income Group
     - Revenue by Age Group: X-Axis: Sum of Revenue; Y-Axis: Age Group; Legend: Gender
     - Revenue by Customer Job: X-Axis: Sum of Revenue; Y-Axis: Count of Jobs; Legend: Gender
     - Revenue by Educational Level: X-Axis: Sum of Revenue; Y-Axis: Education Level; Legend: Gender
     - Revenue by State Code: X-Axis: Sum of Revenue; Y-Axis: State Code; Filter: Top 5 by Revenue; Legend: Gender
   - Table Visualization:
     - Columns:Customer Job, Revenue (Sum), Income (Sum), Interest Earned (Sum)
   - Revenue by Marital Status:
     - X-Axis: Revenue (Sum)
     - Y-Axis: Marital Status
   - slicers: Added for 'Use Chip' to allow dynamic filtering.

3. Formatting and Presentation:
   - Design: Applied clean and consistent formatting to all visuals to ensure simplicity and clarity.
   - Visual Elements: Added background, borders, and size adjustments to enhance the readability and appeal of the dashboard.

4. Handling New Data:
   - Updating Records: Instructions on how to integrate new CSV files with updated records into PostgreSQL and refresh Power BI data:
     - Import new records into PostgreSQL using appropriate SQL queries.
     - Refresh the dataset in Power BI to reflect the updated data.


Insights and Learnings:
- Week-over-Week Changes: Notable increase in transaction metrics and customer engagement.
- Revenue Growth: Revenue increased by 28%.
- Transaction Metrics:Both transaction amount and count have risen.
- Customer Demographics: Male customers contribute significantly to total revenue.
- Credit Card Types: Blue and Silver cards account for 93% of transactions.
- Geographic Insights: TX, NY, and CA contribute 68% of overall transactions.
- Activation and Delinquency Rates:
  - Activation Rate:** 57.5%
  - Delinquency Rate:** 6.06%

Repository Contents:
- Power BI Dashboard File:** [.pbix] with all visualizations and DAX queries.
- SQL Scripts: For database creation and data import.
- CSV Files: Updated records for integration into the database.

Feel free to explore the repository to access the complete project files, replicate the dashboard, or modify it as needed. For any questions or further discussions, please do not hesitate to contact me! 
gmail - moradiya9404@gmail.com


