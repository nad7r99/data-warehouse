# data-warehouse
build data warehouse by Medallion archetecture


RoadMap : data collection --> data ingestion --> Storage the as it is --> Processing(ETL operation) --> Modeling



Data collection : the data is from kaggle platform in csv format 



Data ingestion : Using Pandas to read the data and Pyspark too



Storage : Used the database as storage but it most use (S3 from AWS)



processing : ETL is stand to Extract,transform,and load , i used Pandas liberary in python and Pyspark to achieve 6 concepts of Data Quality (consistency, validty, uniqueness, completeness, timelines, accuracy)



Modeling : Star Schema to seperate the table into tables to build the data warehouse by Medaillion archetecture (Bronze, Silver, Gold) Schemas
           Bronze schema is for Raw data ,Silver Schema is for transformed data, gold Schema is for dashborads.



           
Tools :
   Python (pandas lib),
   Mysql(Docker) ,
   Pyspark,
   Dbeaver,


OS : linux
Version : Ubuntu 24.04   
   
   
   
