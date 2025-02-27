# Executive Sales Dashboard

## Overview

This project delivers an interactive sales dashboard tailored for sales managers, featuring an Overview, Customer, and Product analysis. Using SQL for data cleansing and transformation and Power BI for visualization, we created a robust data model connecting sales budgets, internet sales, and dimension tables. The dashboard empowers users to uncover trends, track performance, and make data-driven decisions effortlessly.

## Project Vision & User Stories

To meet the business's request for an executive sales report tailored for sales managers, I crafted a set of user stories designed to deliver actionable insights and exceed expectations. These user stories acted as guiding stars, ensuring every step of the project aligned with the business needs and upheld rigorous acceptance criteria.

## Data Preparation & Transformation (SQL)

To build a robust data model that enables insightful analysis and addresses the business needs outlined in the user stories, we began by extracting and transforming key datasets using SQL.

One critical data source, sales budgets, was provided in Excel format. This dataset was seamlessly integrated into the data model at a later stage, ensuring a comprehensive and unified framework for analysis.

Below are the SQL statements showcasing the cleansing and transformation processes applied to prepare the data for analysis.

### SQL Transformations:

- `DIM_Calendar`
- `DIM_Customers`
- `DIM_Products`
- `FACT_InternetSales`

## Data Model Overview

Below is a screenshot of the final data model, showcasing the relationships and structure after the cleansed and prepared tables were loaded into Power BI.

The data model illustrates how `FACT_Budget` is seamlessly integrated with `FACT_InternetSales` and connected to the relevant DIM tables. This cohesive model ensures accurate and efficient analysis, aligning with the business objectives and user stories.

## Sales Management Dashboard

The finalized Sales Management Dashboard is thoughtfully structured into three distinct pages to deliver actionable insights:

- **Overview Dashboard:** A comprehensive summary showcasing key performance indicators (KPIs) and essential metrics, providing sales managers with a high-level view of overall sales performance.
- **Customer Dashboard:** A dedicated page focusing on customer-specific insights, including sales trends, customer segmentation, and behavior patterns to help managers identify key opportunities and prioritize efforts.
- **Product Dashboard:** A focused analysis of product performance, highlighting sales trends, top-performing products, and inventory insights, enabling data-driven product management decisions.

This structured approach ensures sales managers have all the tools they need to dive deep into their data and drive results effectively.

## See it in Action

Click the image below to open the dashboard and explore its interactive features!



## Technologies Used

- **SQL** for data extraction, cleansing, and transformation.
- **Power BI** for data visualization and interactive dashboard creation.
- **Excel** for integrating sales budget data.

## Future Improvements

- Enhancing predictive analytics for sales forecasting.
- Automating data updates for real-time insights.
- Integrating additional data sources for deeper customer analysis.

## Contributing

If you have ideas for improvements or new features, feel free to contribute! Open a pull request or submit an issue.

## Contact

For any questions or feedback, reach out via [LinkedIn](https://www.linkedin.com/in/yourprofile) or email.

---

### ⭐ If you find this project useful, give it a star! ⭐

