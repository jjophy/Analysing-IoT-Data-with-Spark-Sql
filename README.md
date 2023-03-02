Objective:- Analysing IoT Data with Spark Sql. 

The data from various IoT devices are available. Using Spark SQL, various queries related to this data are executed. 
Example: Display all the countries whose carbon dioxide level is more than 1400. Sort the output in descending order

Steps done
1.) Google Colab was used. 
2.) openjdk, apache spark, pyspark and findspark installed
2a.) environ variables set for JAVA and SPARK
3.) Spark session created
4.) Google drive mounted and the given iot_device.json file was read 
6.) view iot was created
5.) Each of the given tasks were performed on the view using spark.sql() queries
