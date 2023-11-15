# Analyzing Home Sales Data with PySpark
This project demonstrates the use of PySpark to analyze home sales data. The dataset is processed using PySpark SQL, temporary views, caching, runtime calculation, and Parquet file storage.

Steps:

1. Install Required Libraries
Ensure all the below necessary libraries are installed, code shared: 
import findspark
from pyspark.sql import SparkSession
import time
from pyspark.sql import Row
from pyspark.sql.types import StructType,StructField,StringType, DateType,IntegerType
from pyspark import SparkFiles

2. Data Loading and Exploration
3. Querying Data using spark.sql for multiple results:
    a. Query for Average Price based on number of features as example - number of bedrooms etc
4. Creating temp views
5. Caching and Runtime Calculation
6. Partition and store the data in Parquet format
    a. Running a query on the Parquet data and calculate runtime difference
7. Uncaching and Status Confirmation