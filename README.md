## Retail Shop Sales Data Modelling
### Overview
This project focuses on SQL Data Modelling using a dataset from a retail shop's sales transactions. The dataset comprises several tables containing information about sales, products, customers, and store branches.

### Dataset Description

#### sales_fact
order_id (int),
customer_id (int),
order_date (date),
store_id (smallint)

#### order_product_mapping
order_id (int),
product_id (varchar(10)),
quantity_ordered (int),

#### product_info
product_id (varchar(10)),
product_name (varchar(100)),
product_category (varchar(50)),
list_price (decimal(12,2)),
sale_price (decimal(12,2)),

#### customer_info
customer_id (int),
first_name (varchar(20)),
last_name (varchar(20)),
gender (varchar(10)),
email (varchar(30))

#### branch_details
store_id (smallint),
store_name (varchar(20)),
area (varchar(20)),
city (varchar(20)),
state (varchar(20))

### Objective
The main objective of this project is to perform SQL data modelling tasks such as creating relationships between tables, optimizing queries for data retrieval, and generating insights from the retail sales data.

### Project Structure
- sql_scripts/: Contains SQL scripts for data modelling tasks.
- data/: Contains sample data files for testing purposes.
- docs/: Documentation related to the project.
- README.md: You're reading it right now!

### Usage
- Clone this repository to your local machine.
- Set up your SQL environment (e.g., MySQL, PostgreSQL).
- Execute the SQL scripts provided in sql_scripts/ to create the necessary tables and perform data modelling tasks.
- Analyze and interpret the results to derive insights from the retail sales data.

### Contributions
Contributions are welcome! Feel free to fork this repository, make changes, and submit pull requests.


