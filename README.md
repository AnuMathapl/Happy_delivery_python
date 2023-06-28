# Happy Deliveries Python Projects

## Goal of the project
This is a Python project designed to analyze and provide insights using the datasets provided by Happy Deliveries, a food delivery business based in Ireland. The project focuses on using data to gain a competitive advantage in the food delivery industry.

## Datasets
The project utilizes two datasets:
1. Orders: Contains details of orders placed with Happy Deliveries from 2021 & 2022. The dataset includes the following columns:
   - `order-id`
   - `order_timestamp`
   - `delivered_timestamp`
   - `driver_id`
   - `restauranr_id`
   - `cust_id`
   - `delivery_region`
   - `dicount_code`
   - `order_total`
   - `discount_pc`
   - `status`
2. customers: Contains customer details, specifically loyalty card customers of Happy Deliveries. The dataset includes the following columns:
   - `id`
   - `first_name`
   - `last_name`
   - `age`
   - `city`
   - `email`

  ## Data Cleaning
  Before performing the analysis, the datasets underwent cleaning steps to ensure accurate and reliable results. The following data cleaning steps were performed:

1. **Outlier detection and treatment**: By addressing outliers, the age distribution analysis became more robust and representative of the overall customer base, allowing for 
   more accurate insights into the relationship between age and other variables.

2. **Handling missing values**: Missing values in the datasets were identified and addressed appropriately. Depending on the specific columns and use cases, missing values were 
    either imputed, dropped, or treated as a separate category.

3. **Data type conversion**: The data types of certain columns were adjusted to match their respective data. For example, timestamp columns were converted to datetime format, and 
   numerical columns were converted to appropriate numeric types.

4. **Removing cancelled orders**: Orders with the status 'CANCELLED' were removed from the analysis as they needed to be refunded and should not be considered in sales 
   calculations.

5. **Addressing input errors**: The 'customers' dataset was thoroughly checked for any input errors or inconsistencies. Inaccurate or inconsistent data was corrected or handled 
   appropriately to ensure data integrity.

  These data cleaning steps were crucial in preparing the datasets for analysis and ensuring the accuracy and reliability of the results.

  # Questions and Analysis
  The project aims to address the following questions posed by Happy Deliveries, using the cleaned datasets:

1. Compare monthly 2021 sales to 2022 and determine if Happy Deliveries' sales have grown.
2. What is the age distribution of loyalty card holders?
3. Is there a relationship between the amount spent by a loyalty card holder and their age?
4. Is there a relationship between the amount of payment, the age of a person, and whether or not they used discount codes?
5. Compare the sales for 2022 across all regions.
6. Identify the top 10 highest spending customers in 2022 and provide their ID, name, and email address for rewarding purposes.
7. Determine the top 3 restaurants in terms of sales for 2022 to allocate resources efficiently. Provide their names and total sales.
8. Identify non-returning loyalty card customers from 2021 to target for customer retention efforts. Provide their ID, name, and email.
9. Compare the total amount of sales from the discount codes 'BLACKFRIDAY22' and 'BLACKFRIDAY21'.
10. Identify the locations with the lowest cumulative sales for 2022 to consider tailoring marketing efforts towards those locations.


## Tips and Considerations

Input errors may have resulted in errors in the 'customers' dataset. Handle data cleaning accordingly.
Actual payment for an order needs to be calculated from the 'orders' dataset.
Exclude orders with the status 'CANCELLED' from sales since they had to be refunded.
Please refer to the project code and documentation for detailed implementation and analysis of the above questions. Feel free to explore the code and adapt it to your specific requirements.
  
  
