# Home_Sales #
## File completed with Colab ##
### Instructions ###
1.	Rename the Home_Sales_starter_code.ipynb file as Home_Sales.ipynb.
2.	Import the necessary PySpark SQL functions for this assignment.
![image](https://github.com/user-attachments/assets/20b0e04a-d397-4ba1-8742-7390f9a5be1c)

3.	Read the home_sales_revised.csv from the provided AWS S3 bucket location into a PySpark DataFrame.
![image](https://github.com/user-attachments/assets/9222e33c-d7fd-4750-b059-a8c0644664f0)

4.	Create a temporary table called home_sales.
![image](https://github.com/user-attachments/assets/3dac1f9f-b68f-4ecd-808e-131d6e3f0fcb)

5.	Answer the following questions using SparkSQL:

* What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.
![image](https://github.com/user-attachments/assets/8a26040b-2020-4d2f-8b54-c42aa3546882)

* What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? Round off your answer to two decimal places.
![image](https://github.com/user-attachments/assets/851554f6-e5b4-44fa-acb9-59d606819b8b)
 
* What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.
![image](https://github.com/user-attachments/assets/aa1f3528-6c33-43fc-8191-04eab345bcae)

* What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.
![image](https://github.com/user-attachments/assets/05b0ec31-85c1-4566-b35a-22ac0b1442a0)
 
6.	Cache your temporary table home_sales.
![image](https://github.com/user-attachments/assets/05ef2809-d454-4c99-8bca-4c85ed5a0a2a)
 
7.	Check if your temporary table is cached.
![image](https://github.com/user-attachments/assets/7006d187-ff41-42d1-9723-25adb7670995)
 
8.	Using the cached data, run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.
![image](https://github.com/user-attachments/assets/29013c64-6851-4310-baed-3841d919ef8e)
![image](https://github.com/user-attachments/assets/afd7ddc9-909b-42db-87dc-8b351875faa2)
 
9.	Partition by the "date_built" field on the formatted parquet home sales data.
![image](https://github.com/user-attachments/assets/1507a968-efac-4cc4-9435-37359a05e124)

10.	Create a temporary table for the parquet data.
![image](https://github.com/user-attachments/assets/569e5fa3-3065-48d7-9964-08c1cbd176ac)
 
11.	Run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.
![image](https://github.com/user-attachments/assets/e88e5a38-fead-494c-b03d-516b58b4d4d6)
![image](https://github.com/user-attachments/assets/457c3e90-0c8b-44ce-853a-e3f7289336a1)
 
12.	Uncache the home_sales temporary table.
![image](https://github.com/user-attachments/assets/05a99137-4090-4dfd-8bce-dcd1c9eeb0f2)
 
13.	Verify that the home_sales temporary table is uncached using PySpark.
![image](https://github.com/user-attachments/assets/e1dcef01-259b-4937-ac0a-6299397971ea)
 
14.	Download your Home_Sales.ipynb file and upload it into your "Home_Sales" GitHub repository.
