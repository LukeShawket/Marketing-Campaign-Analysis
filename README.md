# Marketing-Campaign-Analysis
This project demonstrates the data cleaning and data visualization process using SQL queries and tableau on a marketing_campaign dataset.    
[Check out the Tableau Dashboard](https://public.tableau.com/app/profile/luke.shawket/viz/Marketing_Campaign_Analsys/Dashboard1)
## Explore the Data    
The first step is to understand the structure and contents of the dataset.    
* Input:    
  ![image](https://github.com/user-attachments/assets/fbdb2efc-52a6-4caa-b96e-d8c86235759c)    
* Output:    
  ![image](https://github.com/user-attachments/assets/343effcf-d719-4071-9fa1-6ed79c0e79b0)    
This query retrieves all columns and rows from the table to provide an overview of the dataset.
## Check for Duplicates
Identify duplicate entries in the dataset to ensure data accuracy.    
* Input:    
  ![image](https://github.com/user-attachments/assets/8a9d606e-5126-4fdf-92e5-6a01327b6ed5)    
* Output:    
  ![image](https://github.com/user-attachments/assets/776a222f-89b5-43ad-b27f-60ff94039b75)    
Results show any ID values that appear more than once.
## Verify Data Integrity
Check if the ID column contains any non-numeric characters, which might indicate errors.    
* Input:    
  ![image](https://github.com/user-attachments/assets/aed8b494-e8b8-4cc6-9147-5be656c98c77)     
* Output:    
  ![image](https://github.com/user-attachments/assets/14a89ccf-31be-4961-ba90-48b911792e0e)     
This query highlights records where ID contains letters or special characters.
## Identify Null Values
Count rows where the Income field is missing data.    
* Input:    
  ![image](https://github.com/user-attachments/assets/2044c016-20bb-471c-8299-3be4a3422582)     
* Output:    
  ![image](https://github.com/user-attachments/assets/935b5c21-d305-43c2-b126-47ad7d8be0ba)     
This step ensures no critical fields are left incomplete.
## Update Null Values
Replace NULL values in the Income column with 0 to standardize the dataset.    
* Input:    
  ![image](https://github.com/user-attachments/assets/36962564-d34c-432b-8b29-31cbbe000d7f)    
* Output:    
  ![image](https://github.com/user-attachments/assets/7fc09576-a13b-4c1a-b7eb-0504b9d3a30e)     
This step ensures consistency in the Income column for analysis.
## Key Insights
* Duplicates can skew analysis, so identifying and addressing them is critical.

* Verifying data integrity ensures that all IDs are correctly formatted.

* Handling null values helps avoid disruptions during data visualization or further analysis.







