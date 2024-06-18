# AtliQ - Mart - FMCG Dashboard Project

## Project Overview
AtliQ Mart is currently facing a problem where a few key customers did not extend their annual contracts due to service issues. It is speculated that some of the essential products were either not delivered on time or not delivered in full over a continued period, which could have resulted in bad customer service. Management wants to fix this issue before expanding to other cities and requested their supply chain analytics team to track the ’On-time’ and ‘In-Full’ delivery service level for all the customers on a daily basis so that they can respond swiftly to these issues.

The Supply Chain team decided to use a standard approach to measure the service level in which they will measure ‘On-time delivery (OT) %’, ‘In-full delivery (IF) %’, and ‘OnTime in full (OTIF) %’ of the customer orders on a daily basis against the target service level set for each customer.

## Project Links
- **Live Dashboard:** (https://app.powerbi.com/view?r=eyJrIjoiYzZjZmQyMWEtMDdjNy00ZjFlLTk1ZWUtZmI1YzY4OWRiNmU1IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9&pageName=6ea647f959302663d238)
![image](https://github.com/koustuba-84/AtliQ---Mart---FMCG-domain/assets/165156357/2ef7a94a-07c0-41f1-af0a-c9395dfcd2b9)


## Dashboard Details
### Page 1: Delivery Performance Overview 
- **Gauges:**
  - OT: 59.03% (Target: 86.09%)
  - IF: 52.78% (Target: 76.51%)
  - OTIF: 29% (Target: 65.91%)
- **Cards:**
  - Total Orders: 32k
  - OT Orders: 19k
  - IF Orders: 17k
  - OTIF Orders: 9k
- **Clustered Column Chart:**
  - Cities: Surat, Ahmedabad, Vadodara
  - Metrics: OT Delivery %, IF Delivery %, OTIF Delivery % and their targets

### Page 2: Customer Performance Metrix
- **Gauges:**
  - LIFR: 65.96% (Target: 97%)
  - VOFR: 96.59% (Target: 97%)
- **Matrix:**
  - Customers and their OT, IF, OTIF, LIFR, VOFR percentages

### Page 3: Trends and Analysis
- **Line Chart:**
  - X-axis: Date
  - Y-axis: OT, IF, etc., with their targets
- **Scatter Chart:**
  - X-axis: OT Delivery %
  - Y-axis: IF Delivery %
  - Legend: Customer names
  - Size: Total Orders
  - Play Axis: Week No

### Page 4: Product Insights
- **Matrix:**
  - Category and Product names
  - Values: LIFR %, VOFR %, with sparklines
- **Clustered Column Chart:**
  - Customers and their Total Order Qty (TOQ) and Total Delivered Qty (TDQ)

### Page 5: Detailed Delivery Breakdown
- **Decomposition Tree:**
  - Analyze: Total Delivered Qty
  - Explain by: Delivery Status, City, Customer Name, Product Name
- **Line and Stacked Column Chart:**
  - X-axis: Customer Name
  - Column Y-axis: Total Order Qty
  - Line Y-axis: LIFR
  - Column Legend: Delivery Type

## Insights
- **City-wise Performance:**
  - Surat: OT: 61%, IF: 52.55%, OTIF: 30%
  - Ahmedabad: OT: 58.61%, IF: 54%, OTIF: 29%
  - Vadodara: OT: 57%, IF: 51%, OTIF: 27.78%
- **Customer Performance:**
  - Customers like Vijay Stores and Propel Mart have higher same-day deliveries compared to others.
- **Product Performance:**
  - All categories (Beverages, Dairy, Food) show consistent LIFR and VOFR percentages.
- **Delivery Status:**
  - Fully Delivered: 88,63,982
  - Partially Delivered: 41,05,175

## Acknowledgments
I want to extend my gratitude to the following for their support and guidance throughout this project:
- **Codebasics Team:** For providing an excellent learning platform and bootcamp experience.


## License
This project is licensed under the MIT License.



