# Coffee Order Sales Analysis

## 1. Introduction
### a. Project Background and Objectives
This project aimed to create a coffee sales data dashboard, transform raw data into actionable insights for smarter business decisions.

### b. Data Sources and Description
- Data Source:  Coffee Order Data Kaggle

- Data types: Orders data, Customers data, Products data

### c. Languages & Tools
Microsoft Excel

## 2. Data Collection and Cleaning
### a. Collection
We have been provided with 3 raw data sheets: Order, Customers, and Products. The details of each sheet are as follows:

- Order Sheet: Order ID, Order Date, Customer ID, Product ID, Quantity

- Customers Sheet: Customer ID, Customer Name, Email, Phone Number, Address Line 1, City, Country, Postcode, Loyalty Card

- Products sheet: Product ID, Coffee Type, Roast Type, Size, Unit Price, Price per 100g, Profit

I will get the data from the customers sheet and products sheet to fill the Order Sheet with the following steps:

- Use the INDEX and MATCH formulas to extract data from the Customers and Products tables into the Orders table.

- Link the Orders and Customers tables using the Customer ID primary key.

- Link the Orders and Products tables using the Product ID primary key.

- Update the year in the Order Date column from 2019 - 2022 to 2021 - 2024 using the DATE function.

- Add a Sales column to the Orders table using the formula: Sales = Quantity * Unit Price.

### b. Data Cleaning:
- Check for null values, errors, and duplicates in the data.

- Convert abbreviations in the Coffee Type and Roast Type columns to full names using the IF function.

Ro = Robusta, Exc = Excelsa, Ara = Arabica, Lib = Liberica

L = Light, M = Medium, D = Dark

- Format the Size column as a weight in kg (custom 0.0 "kg").

- Format the Unit Price and Sales columns as currency ($).

## 3. Data Analysis and Visualization:
### a. Data Analysis:
Using pivot tables to summarize Orders data

Analyze the following metrics:

- Total Sales

- Total Customers

- Total Sales over time

- Total Sales by day

- Sales by Country

- Sales by Coffee type name

- Top 5 Customers by Sales

### b. Data Visualization:
Create charts and graphs to illustrate the analyzed metrics.

Create filters to allow users to interact with the data based on the following criteria:

- Month

- Year

- Size

- Roast type name

- Loyalty card

### c. Coffee Sale Dashboard

## 4. Recommendations and Actionable Steps
### a. Product Analysis:
Arabica coffee has the highest sales, followed by Robusta, Excelsa, and Liberica.

Light roast coffee is the best seller, followed by Medium and Dark.

The 2.5kg package size is popular with the highest number of customers choosing to buy it.

### b. Customer Analysis:
The number of customers has increased steadily from 2021 to 2024.

Customers with membership cards have higher sales than those without.

Regional Analysis:

Revenue in the US is the highest over time.

### c. Conclusion:
Coffee sales are trending upwards over time.

The company's main products are Arabica coffee and Light roast.

Potential customers are those who have loyalty cards.

### d. Recommendations:
Continue to promote and develop the Arabica coffee and Light roast product lines.

Focus on exploiting the US market as it is the market with the highest revenue.

Encourage customers to use loyalty cards, and consider creating promotions and presents for them.
