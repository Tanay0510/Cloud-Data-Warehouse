# Data-Warehouse
Building an ETL pipeline that extracts their data from S3, stages them in Redshift, and transforms data into a set of dimensional tables for their analytics team to continue finding insights in what songs their users are listening to. You'll be able to test your database and ETL pipeline by running queries given to you by the analytics team from Sparkify and compare your results with their expected results. Load data from S3 to staging tables on Redshift and execute SQL statements that create the analytics tables from these staging tables.


A music streaming startup, Sparkify, has grown their user base and song database and want to move their processes and data onto the cloud. Their data resides in S3, in a directory of JSON logs on user activity on the app, as well as a directory with JSON metadata on the songs in their app.

#### The project template includes four files:

create_table.py is where you'll create your fact and dimension tables for the star schema in Redshift.

etl.py is where you'll load data from S3 into staging tables on Redshift and then process that data into your analytics tables on Redshift.

sql_queries.py is where you'll define you SQL statements, which will be imported into the two other files above.


#### Build ETL Pipeline

Implement the logic in etl.py to load data from S3 to staging tables on Redshift.

Implement the logic in etl.py to load data from staging tables to analytics tables on Redshift.

Test by running etl.py after running create_tables.py and running the analytic queries on your Redshift database to compare your results with the expected results.

Delete your redshift cluster when finished.
