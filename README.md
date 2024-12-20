# Ovierviwe
The project involves the efficient handling and storage of customer transaction data provided in CSV files. The company generates these CSV files every 5 minutes, containing basic data on various customer movements over a specific period. The task is to process this data and store it in a database, with additional steps to ensure data quality and proper tracking.

![](https://github.com/Eman2597/Telecom_ETL_using_SSIS/blob/main/Image/Dataset%20Description.PNG)
![](https://github.com/Eman2597/Telecom_ETL_using_SSIS/blob/main/Image/Requiretment.png)

# Key Steps:

## Data Processing:
The CSV files need to be processed before storing the data in the database.
Records that do not meet certain conditions are to be rejected.

## Handling Rejected Records:
 Rejected records are stored in a separate table, with a reference to the original CSV file they came from.
Data Quality Assurance:
Track the number of transactions in each CSV file.
Compare this with the number of records stored in the database and the number of rejected records.
Ensure that each stored record is linked back to the original CSV file for traceability.

 ## Post-Processing:
 After the data has been successfully stored in the database, the original CSV file is moved to a different folder for archiving or further use.

This process ensures that the data is stored accurately, with clear tracking of any issues and proper archiving of the original files.
![](https://github.com/Eman2597/Telecom_ETL_using_SSIS/blob/main/Image/Control%20Flow.png)
![](https://github.com/Eman2597/Telecom_ETL_using_SSIS/blob/main/Image/Data%20Flow.png)

# Technology:
Visual Studio
SQL Server Integration Services (SSIS)
SQL Server Management Studio (SSMS)
SCD
ETL
Data warehouse   
# Output 
![](https://github.com/Eman2597/Telecom_ETL_using_SSIS/blob/main/Image/output.PNG)
