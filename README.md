# DataIngestion-Process-UIReport 
Source: MYSQL <br/>
Processing: SQOOP(Data Importing) Using internally MR (OR) Java JDBC APIS/HDFS API'S,S3 BOTO3 and aws-sdk Jars (OR)
              Spark JDBC Read Using Scala <br/>
Target: S3/HDFS <br/>



# DataIngestion: <br/>
  Data Generation Around 1GB Data <br/>
  
# Data Process :  
   Here I am working on Data Process using (MYSQL to S3/HDFS ) different apporach <br/>
       1) JDBC Push into S3/HDFS (using Java Configuration Class/HDFS API) <br/>
       2) SQOOP MR Apporach (Using SQOOP Import around 8 + Mappers) & Push ino S3/HDFS Storage <br/>
       3) Spark JDBC Read Push into S3/HDFS Storage <br/>
       
# Data View <br/>
     1)Data View Pushing into REST API/ hazelcast IMDB Grids
     2)Using Report BI Tools
     
     
     
