# dvdrental_analysis
Data engineering project using PostgreSQL DVD rental dataset 

### Step 1
DVD rental dataset was downloaded from https://github.com/robconery/dvdrental and restored to a PostgreSQL database on local storage



### Step 2
createbucket.py was written and ran to create a new bucket in AWS S3 for the dvdrental project



### Step 3 
uploaddata.py was written and ran to extract tables of data from PostgreSQL in the form of json files and upload them to the designated AWS S3 bucket



### Step 4
Using dvdrental analysis.ipynb, a python notebook  on Databricks Community edition, the S3 bucket was mounted on databricks file storage system and the data was used to perform analytical queries using Spark SQL. Published version of this notebook can be found at https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/2606190505965031/1338989442509528/5820989190425175/latest.html  



### Step 5
The databricks cluster was connected to Power Bi Desktop, and the results of the analytical queries were imported to populate dashboards for reporting purposes. eport can be viewed at https://app.powerbi.com/groups/me/reports/1b4757a6-671c-4c4f-a24f-5ad3c01570ed?ctid=4c8547ae-0a48-4df4-b5a5-af0ec0d300af&pbi_source=linkShare 
