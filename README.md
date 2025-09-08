Now, Databricks allows us to drop a file and it will create a table, to read the table in Databricks!

df = spark.read.table('db.big_mart_sales')
