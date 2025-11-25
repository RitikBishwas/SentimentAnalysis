# Kafka-Spark-HBase-Sentiment-Analysis
## Description
This project is an implementation of a Big data workflow.
It aims to manipulate different big data technologies such as Apache Kafka, Apache Zookeeper, Apache Spark and Apache Hbase. <br/> 
This application consists of a (dumb) sentiment analysis of a twitter stream that is based on computing a score for each tweet.
The score is calculated as follows: for each tweet text eliminate the (stop words) , add 1 for positive words and retrieve 1 for négative words
