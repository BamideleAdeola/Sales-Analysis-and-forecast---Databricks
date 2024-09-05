# Sales-Analysis-and-forecast---Databricks
#### Project Description:  
This project analyzes historical sales data from a sudo retail company to understand sales patterns, customer behavior, and product performance. Also, it leverages a machine learning model to predict future sales and recommend strategies for inventory management and promotions.

#### Data Ingestion:
A Python Library **Faker** was installed and used to generate random sample data for the analysis.
fake.py is a standalone, portable library designed for generating various random data types for testing.
see https://pypi.org/project/fake.py/#:~:text=fake.py%20is%20a%20standalone,random%20data%20types%20for%20testing.

#### Data Cleaning and Export:
Jupyter Notebook using Python code was used to generate the data and clean it accordingly and then the data was exported as a csv file. Better still one can also export as a parquet file.

#### Microsoft Fabric Lakehouse:
I used the Microsoft Fabric trial version to do the following exercise: 
- Create a fabric-enabled workspace
- Create a lakehouse to store all data since this serves as a single source for all data points.
- I uploaded the cleaned sales data into a lakehouse
- Convert the CSV data to a **Delta Table** in case of SQL Queries
- Create a new Synapse engineering Notebook - equivalent to what I could have done in Databricks. Fortunately, aLL clusters, runtime attributes were created automatically.
- Used pySpark Code to import my data into the Notebook
- Build a machine Learning Model **(Regression Model)**  on this data
- Save and export the model output




