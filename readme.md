# Big Data Tools
This small project demonstrates basic usage of several big-data and no-sql databases.
The project consists of two modules:
1. Redis_Mongo - an exercise that implements a database for an HR management system.
This database has an in-memory key-value storage implemented with Redis, and a persistent storage using Mongo DB.
The database supports basic functions like adding and deleting entities, listing the db, clearing and recovering cash and basic analytics.

2. Spark_HDFS - an exercise that analyzed Microsoft's web visits from different countries.
The data is stored on HDFS and processed by map-reduce using PySpark.    


In order to run the notebooks one must first install PySpark, Hadoop, Redis-Server and Mondo-db locally

Follow these instructions:
PySpark- https://opensource.com/article/18/11/pyspark-jupyter-notebook
Hadoop- https://www.edureka.co/blog/install-hadoop-single-node-hadoop-cluster
Mongo- https://www.howtoforge.com/tutorial/install-mongodb-on-ubuntu-16.04/
Redis - https://www.bogotobogo.com/DevOps/Redis/Redis_Install.php
#### Prerequisites

    * Python >= 3.5
    * Pyspark
    * Hadoop>= 2.7
    * Redis server v=5.0.4
    * MongoDB shell version v4.0.9
    


