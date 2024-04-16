# Retail Sales Data Warehousing with IBM InfoSphere DataStage

## Introduction
This project showcases the development of a star-schema-based sales analysis data warehouse for a fictitious national department store using IBM InfoSphere DataStage. The aim is to demonstrate a typical data warehousing flow, including modeling, ETL processes, and the creation of data marts to meet specific business needs.

## Project Details
- **Industry Scenario**: Retail
- **Dimensions**: Customer, Store, Product
- **Fact Table**: Transactions

## One-time Tasks 
1. **Designing the Star-Schema**: Defined a star-schema consisting of three dimensions (product, retail, customer) and a fact table (transactions).
2. **Populating Dimension and Fact Tables**: Loaded sample data into the dimension and fact tables.
3. **Setting up for Recurring Tasks**: Prepared the infrastructure for recurring tasks.

## Project Requirements
### Modeling Process
- Translated the logical data model to a physical data model.
- Loaded sample data into files for reference.

### ETL Solution with DataStage
- Developed ETL solutions to load data into files or databases as per business requirements.
- Implemented transformations on source data to fulfill business needs.

## Data Marts
### 1. Retail Sales Data Mart
- **Transformation**: Upper case transformation applied to all customer name columns. Date representation changed to display columns instead of using the dim date table.
- **Business Need**: Display each transaction for each customer based on customer type (citizen or foreign) along with product and stock information.

### 2. Activation Sales Data Mart
- **Business Needs Addressed**:
  - Display count of all transactions for each customer for each store.
  - Display max profit made by which customer type.
  - Give bonus to customers based on the profit they make.

## Files
### [Physical Data Model]
![image](https://github.com/ahmedhattem11/ETL-Data-Stage/assets/87239054/cea5819d-936d-4e03-95f1-05c9f99fda79)

## Photos 
### 1. Retail Sales Data Mart
![Retail_Data_Mart](https://github.com/ahmedhattem11/ETL-Data-Stage/assets/87239054/6b5e650d-dea5-4e1f-9704-10b850914b03)

### 2. Activation Sales Data Mart
![Activation_Sales_Data_Mart](https://github.com/ahmedhattem11/ETL-Data-Stage/assets/87239054/9c942574-058e-40fa-a3f4-2ee3065746e4)

## Conclusion
This project illustrates the end-to-end process of building a star-schema-based sales analysis data warehouse using IBM InfoSphere DataStage. It covers the modeling process, ETL development, and the creation of data marts to address specific business requirements within the retail industry scenario.
