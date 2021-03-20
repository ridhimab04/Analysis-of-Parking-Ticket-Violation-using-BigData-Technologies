# Analysis-of-Parking-Ticket-Violation-using-BigData-Technologies

Getting a parking ticket in New York City is a very common situation and easily makes the driver spend more than $100. Parking tickets are a bit difficult to avoid in few circumstances and hence there needs to be a way to avoid them. It is necessary that people driving cars must be aware of certain tricks and tips in order to avoid tickets.

This project helps in analysis of data related to NYC parking tickets based on following technologies:
1. Apache Spark
2. Apache Hive
3. Apache Pig

Along with this analysis, it also includes a Recommender System built in Spark using the ALS model.

But to begin with the analysis, the data needs to be pre-processed so as to derive meaning out of it. Following steps were performed:
1. Data Collection (https://data.cityofnewyork.us/City-Government/Parking-Violations-Issued-Fiscal-Year-2020/pvqr-7yc4)
2. Data Pre-processing using Python and Spark
   a. Downsampling of the data
   b. Importing and merging data from multiple years
   c. Indexing columns
   d. Scaling and normalization of data
3. Data Import into HDFS

The documents attached in the project have screenshots of the data preprocessing, analysis, recommender system, visualization and the final results.
