# Business Insights 360

---

## Table of Contents
1. [Project Overview](#project-overview)
2. [Tech Stack](#tech-stack)
3. [Power BI Techniques Learned](#power-bi-techniques-learned)
4. [Company Background](#company-background)
5. [Questions to Ask Before Starting](#questions-to-ask-before-starting)
6. [Dataset Understanding](#dataset-understanding)
7. [Data Import and Modeling](#data-import-and-modeling)
8. [Dashboard Design](#dashboard-design)
9. [Project Outcome](#project-outcome)
10. [Resources and Links](#resources-and-links)

---

## Project Overview

**AtliQ Hardwares**, a rapidly growing consumer electronics company, is looking to stay competitive by transforming their reporting capabilities. Currently, most reports are in Excel, limiting their ability to make data-driven decisions. This project implements an advanced analytics solution in Power BI, enabling AtliQ Hardwares to gain valuable insights and make informed business decisions. The project was completed by following the Codebasics Power BI course.

![Thumbnail](https://github.com/Ankkit0413/Business-Insights-360/blob/main/Business%20Insights%20360.png)

[Live Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiZTE1MmFkMzUtZmFkZi00MWNjLWFjNzYtZjM0NzJmZTc2NmY0IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)


[View LinkedIn Post](https://www.linkedin.com/posts/ankkitkumarguppta_business-insights-360-activity-7255948922123145216-shIp?utm_source=share&utm_medium=member_desktop)

## Tech Stack

- **SQL**
- **Power BI Desktop**
- **Excel**
- **DAX Language**
- **DAX Studio** (for report optimization)

## Power BI Techniques Learned

During this project, I acquired various Power BI skills, including:
- **Questioning Before Project Start**: Understanding stakeholder requirements.
- **Calculated Columns and Measures**: Created using DAX.
- **Data Modeling**: Developed a robust model with over 10 tables.
- **Visual Design**: Selecting appropriate visuals and utilizing bookmarks for interactive navigation.
- **Dynamic Titles**: Displayed based on applied filters.
- **Zero-Division Error Handling**: Used the `DIVIDE` function.
- **Date Table Creation**: Generated using M language.
- **Conditional Formatting**: Applied icons and colors for data representation.
- **KPI Indicators**: For key metrics.
- **Power BI Service Deployment**: Publishing, setting auto-refresh, and creating Power BI Apps.
- **Collaboration Tools**: Managing access permissions in Power BI workspaces.

## Company Background

AtliQ Hardware has expanded significantly, opening stores globally and selling computers and accessories via three channels:
- **Retailers**
- **Direct Sales**
- **Distributors**

The company’s recent setback in the American market, driven by insufficient data analysis and reliance on intuition, has emphasized the need for data-driven insights to compete with analytics-driven competitors.

## Questions to Ask Before Starting

To ensure clarity and alignment, the following questions were discussed with stakeholders:
1. **Project Objective**: What is the purpose of the dashboard?
2. **Success Metrics**: How will the project be evaluated?
3. **Timeline**: What is the project deadline?
4. **Previews**: Are previews expected before release?
5. **Stakeholder Expectations and Fears**: What are their hopes and concerns?
6. **User Roles**: Who will use the dashboard, and for what purpose?
7. **Potential Challenges**: What could go wrong?
8. **Resources and Design Inputs**: Any specific resources or design guidelines?

## Dataset Understanding

Understanding the available data is crucial for effective analysis. Here’s a brief on the data tables:

- **Dimension Tables**:
  - **dim_customer**: Contains customer details across 27 markets, 75 customers, and 2 platforms (Brick & Mortar and E-commerce).
  - **dim_market**: Details markets, sub-zones, and regions.
  - **dim_product**: Information on products, categories, and variants.

- **Fact Tables**:
  - **fact_forecast_monthly**: Forecasted customer demand to enhance satisfaction and reduce warehousing costs.
  - **fact_sales_monthly**: Similar to the forecast table but includes sold quantity.

Additional tables include:
- **freight_cost**: Travel and other costs by market and fiscal year.
- **gross_price**: Gross prices by product code.
- **manufacturing_cost**: Manufacturing costs by product code and year.
- **pre_invoice_deductions** and **post_invoice_deductions**: Deduction percentages by customer and year.

## Data Import and Modeling

Data was imported from a MySQL database into Power BI. Key data modeling principles followed include:
- **Snowflake Schema**: Structured using a snowflake data model.
- **Best Practices**: Ensured a strong foundation for report performance by following data modeling best practices.

## Dashboard Design

The dashboard is designed with the following views, each tailored to meet user needs and ensure intuitive navigation:

1. **Home View**: Main navigation page with buttons linking to various views.
2. **Info Page**: General information about the dashboard.
3. **Finance View**: Detailed financial insights.
4. **Sales View**: Sales performance metrics.
5. **Marketing View**: Marketing metrics and trends.
6. **Supply Chain View**: Insights on supply chain efficiency.
7. **Executive View**: High-level summaries for executive decision-making.
8. **Products View**: Product performance and inventory data.
9. **Support View**: Customer support metrics.

Each page was designed based on mock-ups provided by stakeholders. Key functionalities included:

- **Bookmarks**: To toggle between visuals.
- **Page Navigation**: Via buttons for ease of use.
- **KPI Indicators and Conditional Formatting**: For visual data insights.

## Project Outcome

This Power BI report enables stakeholders to make data-driven decisions and provides answers to numerous "why" questions based on evolving business scenarios. It has become an invaluable asset in guiding AtliQ Hardware’s strategies and operations.

## Resources and Links

- [Live Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiZTE1MmFkMzUtZmFkZi00MWNjLWFjNzYtZjM0NzJmZTc2NmY0IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

- [View LinkedIn Post](https://www.linkedin.com/posts/ankkitkumarguppta_business-insights-360-activity-7255948922123145216-shIp?utm_source=share&utm_medium=member_desktop)

---
