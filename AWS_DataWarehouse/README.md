**DataWarehouse on AWS**

![alt text](images/Redshift_ETL.png?raw=true)

* *DWH_IAC.ipynb* is an example of infrastructure as code
  * Create an IAM role
  * Deploy the Redshift cluster
  * Open up the TCP port to access the cluster endpoint
  
* *DWH_Parallel_ETL.ipynb* is an example of parallel loading of data to the DWH from S3 

* *DWH_Table_Design.ipynb* demonstrates the query performance gains of using a key distribution style vs no distribution strategy

Example of a DWH pipeline using Airflow can be found in Airflow/Airflow_with_DWH 
