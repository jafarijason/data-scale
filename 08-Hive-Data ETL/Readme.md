# [source](https://www.cloudera.com/tutorials/getting-started-with-hdp-sandbox/3.html)

Apache Hive presents a relational view of data in HDFS. Hive can represent data in a tabular format managed by Hive or just stored in HDFS irrespective in the file format the data is in. Hive can query data from RCFile format, text files, ORC, JSON, parquet, sequence files and many of other formats in a tabular view. Through the use of SQL you can view your data as a table and create queries like you would in an RDBMS.

Let’s now open DAS and get introduced to the environment. From Ambari Dashboard Select Data Analytics Studio and click on Data Analytics Studio UI

<img  src="https://www.cloudera.com/content/dam/www/marketing/tutorials/getting-started-with-hdp-sandbox/assets/open-das.jpg" />

Alternatively, use your favorite browser navigate to [http://sandbox-hdp.hortonworks.com:30800/](http://sandbox-hdp.hortonworks.com:30800/) while your sandbox is running.

<img src="https://www.cloudera.com/content/dam/www/marketing/tutorials/getting-started-with-hdp-sandbox/assets/das.jpg" />

There are 4 tabs to interact with Data Analytics Studio:

1. Queries: This view allows you to search previously executed SQL queries. You can also see commands each user issues.

2. Compose: From this view you can execute SQL queries and observe their output. Additionally, visually inspect the results of your queries and download them as csv files.

3. Database: Database allows you to add new Databases and Tables. Furthermore, this view grants you access to advanced information about your databases.

4. Reports: This view allows you keep track of Read and Write operations, and shows you a Join Report of your tables.

Take a few minutes to explore the various DAS sub-features.

## Create your own database
 <img src="https://github.com/jafarijason/data-scale/raw/main/assets/images/08-01.png" alt=""/>



## Create Hive Tables

Starting from DAS Main Menu:

1. Select Database

2. Select + next to Tables to add a new Table

3. Select Upload Table

<img src="https://www.cloudera.com/content/dam/www/marketing/tutorials/getting-started-with-hdp-sandbox/assets/upload-table.jpg" />

Complete form as follows:

1. Select checkbox: Is first row Header: True
2. Select Upload from HDFS
3. Set Enter HDFS Path to <userFolder>/tmp/data/geolocation.csv
4. Click Preview

<img src="https://www.cloudera.com/content/dam/www/marketing/tutorials/getting-started-with-hdp-sandbox/assets/upload-table-path.jpg" />

<img src="https://www.cloudera.com/content/dam/www/marketing/tutorials/getting-started-with-hdp-sandbox/assets/data-prev.jpg" />

## Same for trucks

Repeat the steps above with the trucks.csv file to create and load the trucks table.



