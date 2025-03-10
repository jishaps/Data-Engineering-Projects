We used DataBricks to create multiple ETL pipelines using the Python API of Apache Spark (pyspark)

We have used sources like CSV, Parquet, and Delta Table then used Factory Pattern to create the reader class. Factory Pattern is one of the most used Low-Level designs in Data Engineering pipelines that involve multiple sources.

Then we used PySpark DataFrame API and Spark SQL to write the business transformation logic. In the loader part, we have loaded data into two fashion one using DataLake and another by Data LakeHouse.

We have discussed and demonstrated a lot of concepts like broadcast join, partition by and bucketing, sparkSession, windows functions like LAG and LEAD, delta table and many other concepts. 
