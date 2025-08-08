In this first we extarct data from local computer by using kafka and using EC2 as broker(single) then load into S3
Now using DataBricks for transformation of these files and check by using SparkSQL and do some visualization then load into S3.
after that runing glue crawler then athena.
the pipeline flows from Kafka → S3 → Databricks → Glue → Athena
