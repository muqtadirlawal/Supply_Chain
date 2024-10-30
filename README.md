# Refine Production Planning: Utilizing Customer Segmentation and Data insights for Supply Chain

## Table of Contents

- [Business Problem](#business-problem)
- [Rationale for the Project](#rationale-for-the-project)
- [Aim of the Project](#aim-of-the-project)
- [Data Description](#data-description)
- [Tech Stack](#tech-stack)
- [Project Scope](#project-scope)
- [Analysis and Insights](#analysis-and-insights)
- [Recommendations](#recommendations)

## Business Problem
SmartHome Solutions Inc. faces a significant challenge in optimizing its supply chain and production planning. The traditional approach to production planning, based primarily on historical data and market forecasts, poses various obstacles:
 - Inefficient Production: Relying on historical data often results in overproduction or underproduction, causing operational inefficiencies and increased costs. 
 - Customer Disconnection: The company lacks a deep understanding of its diverse customer base, making it challenging to align production with specific customer demands. 
 - Inventory Management: Inefficient production planning has led to excess inventory, tying up valuable resources and impacting the company's profitability. 

## Rationale for the Project
The logistics and supply chain industry is undergoing a significant transformation, necessitating a data-driven approach. Here are the top five reasons highlighting the significance of this project:
 - Operational Efficiency: By leveraging customer data, SmartHome Solutions Inc. can streamline production processes, reduce operational costs, and optimize resource allocation, leading to a more efficient supply chain. 
 - Customer Satisfaction: Understanding customer preferences and demand patterns enables the company to provide better product availability and timely deliveries, ultimately enhancing customer satisfaction. 
 - Competitive Edge: In a dynamic market, data-driven supply chain planning gives SmartHome Solutions Inc. a competitive advantage by enabling rapid adaptation to market changes and customer demands. 
 - Cost Savings: Eliminating overproduction and minimizing excess inventory leads to significant cost reductions, bolstering the company's financial health. 
 - Sustainability: Reducing waste through accurate production planning aligns with the company's sustainability goals, demonstrating corporate responsibility. 

## Aim of the Project
The primary objectives of this project are:
- Customer Segmentation: To segment and profile SmartHome Solutions Inc.'s customer base to gain insights into their preferences, buying behaviors, and geographic distribution. 
- Data-Driven Planning: To enhance production planning, inventory management, and distribution strategies based on customer segments, thereby reducing overproduction and minimizing excess inventory. 
- Customer-Centric Approach: To improve on-time deliveries, increase customer satisfaction, and align production with customer demands. 

## Data Description
This case study contains 4 datasets and they are as follows;
- Customer Data:
  - Customer_ID: A unique identifier for each customer.
  - Age (years): The age of the customer in years.
  - Gender: The gender of the customer (e.g., Male, Female, Other).
  - Income ($): The annual income of the customer in dollars.
  - Geographic Location: The customer's geographic location (e.g., city, state).

- Sales Data:
  - Transaction_ID: A unique identifier for each sales transaction.
  - Customer_ID: The identifier linking each sale to a customer.
  - Product SKU: Unique identifier for each product.
  - Quantity Sold (units): The number of units sold for each product.
  - Timestamp: The date and time of each sales transaction.
 
- Inventory Data:
  - Product SKU: Unique identifier for each product, linking to sales data.
  - Current Inventory Level (units): The number of units of each product currently in inventory.
  - Stockout (days): The number of days a product has been out of stock.
  - Replenishment Lead time (days): The number of days it takes to replenish inventory.
  - Storage Location: The location where the product is stored.
  - Shelf Life (days): The number of days a product can be stored before expiration.
 
- Production Data:
  - Product SKU: Unique identifier for each product, linking to sales and inventory data.
  - Production Schedule_ID: A unique identifier for each production schedule.
  - Lead Time (days): The time required for manufacturing and distribution.
  - Production Capacities (units per hour): The number of units that can be produced per hour.
  - Resource Allocation: Information about the allocation of resources for production.

## Tech Stack
Tool– Microsoft Excel
- Utilized for creating the interactive dashboard, data visualization, and reporting.
- Data Processing Tools: Leveraging Excel's data manipulation and analysis functions.
- Visualization Tools: Employing Excel's charts, graphs, and pivot tables for order and delivery data visualization.

## Project Scope
- Exploratory Data Analysis: Explore the data to understand its characteristics and discover patterns. 
- Data Analysis: This includes the Customer segmentation, profiling, production planning and performance monitoring.
- Visualization and Reporting: Create interactive dashboards in Excel to visualize insights.  
- Recommendation: Integrate the data-driven supply chain planning process into the company's existing systems and processes.

## Analysis and Insights


You can interact with the dashboard [here]()

### Overview
![](Overview.png)

This page focuses on the key factors driving attrition and highlights the main retention risks to management.
- We see that the Company has a total of 2,940 employees, 474 of those left the company during the period in consideration. This gives an Attrition rate of 16%.
- We see that tenure is a significant factor, with 364 employees out of 474 (~77%) leaving within the first 10 years.
- Attrition is concentrated in Research & Development, particularly in roles such as Laboratory Technicians, Sales Executives, and research Scientists, which are essential to the company's operations.
- Job satisfaction and Commuting distance also contribute to turnover, with 132 (40%) employees that left having long commutes to work.
- Alarmingly, McCurr is losing it's top performers (84%), with some of them working overtime, suggesting possible burn out.

These are the key areas where targeted interventions can help retain the company's best talents and reduce attrition.

### Demographics & Job Roles
![](Demography.png)

Here, we'll have a closer look into who- which employee demographics and job roles are most impacted by attrition.
- We see that Attrition is higher among male employees (63%) and single employees (50%), especially among the 26-35 age group, who may be seeking better oppportunities.
- Also, attrition is predominant in junior/entry-level roles (Job Role 1) at 60%, indicating thet junior staff may lack engagement or growth paths.

Retention strategies focusing on career development and engagement for these groups can reduce turnover.

### Satisfaction and Work-Life Balance
![](Satisfaction.png)

This page explores how job satisfaction, work-life balance, and the work-environment affect attrition.
- Job satisfaction is a key factor, with 28% (132) of employees that left expressing dissatisfaction with their jobs.
- Interestingly, 254 of the 474 employees that left had an excellent work-life balance, meaning other factors like job satisfaction and overtime (worked by 53.5% of leavers) may be driving attrition.
- The work environment also played a role, with 144 employees who left expressing dissatisfaction with it.

### Performance and Compensation
![](Performance.png)

- The majority of employees who left earned between 1k-5k per month, indicating that compensation could be a factor.
- 84% of those who left are excellent performers, meaning the Company is losing it's top talents.
- Employees who received the lowest salary hikes were more likely to leave, suggesting that financial recognition may be inadequate.

## Recommendations

Focus Retention Efforts on Employees with 1-10 Years of Tenure:

- 77% of attrition comes from employees who have been with the company for not more than 10 years. To retain talent, management should enhance career development, offer growth opportunities, and focus on engaging employees in their early years at the company.

Improve Job Satisfaction, especially in Critical Roles:

- 28% of employees who left were dissatisfied with their jobs, and the company is losing top performers (84%), particularly in Research & Development and key job roles like Laboratory Technicians and Sales Executives. Management should address job satisfaction through role-specific interventions, such as career growth, recognition, and feedback.


Address the Impact of Overtime and Distance from Work:

- 53% of employees who left worked overtime, and 40% lived far from work, indicating possible burnout and commuting issues. Offering flexible working options and reducing excessive overtime could improve retention and work-life balance, particularly for those affected by long commutes.
