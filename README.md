Problem Statement

Nowadays, there are many reasons for the delay and cancellation of flights. The Federal Aviation Administration estimates flight delays cost airlines $22 billion yearly in the United States. Flight delays are inconvenient for passengers as well. The airline analysis allows for comparisons between different airlines, their time, arrival, and departure. We analyzed an airline dataset from 2018 to identify flights that were delayed for over 60 minutes, had a minimum airtime of 100 minutes, and examined their destinations. Our findings provide detailed information on specific airline flights that meet these criteria.


Dataset

We utilised a 1.9 GB dataset from the Kaggel website consisting of 1048575 records and 61 title columns. After cleaning the source CSV file, we extracted only the necessary fields such as Airline, Origin, Destination, Airtime, and departure delay time for the final output CSV file following analysis.


Technology & Tools Used

AWS EMR (Amazon Elastic MapReduce)
AWS S3 (Amazon Simple Storage Service)
AWS EC2 (Amazon Elastic Compute Cloud)
Apache Spark
Python Pyspark SQL libraries

Web URL:
http://airlineanalysis.epizy.com/
