# PySpark-based Streaming User Churn Prediction

The project was part of the Big Data Computing course and was conducted by TANG Shiyan, XU Jinwen, TANG Yinong, and YE Yi Lin.

## Project Overview

The project focuses on creating an effective system to predict user churn (downgrade or cancellation of paid/free subscriptions) for a fictional music streaming enterprise, Sparkify. The main objective is to develop a machine learning model capable of identifying potential churned users based on their activity and interaction patterns with the service. The goal is to leverage big data technology for storing, processing, and analyzing large-scale data, conducting feature engineering, and creating and evaluating machine learning models.

The project is structured around three main aspects:

1. Data Storage and Connector
2. Feature Engineering, Model Training, and Evaluation
3. Data Visualization

## Technologies Used

1. **Data Storage and Connector:** MongoDB - used to store the data read by Spark.
2. **Data Preprocessing:** Spark SQL and DataFrame - used for big data processing.
3. **Data Modelling:** Spark MLlib and GraphFrame - utilized for data analysis tasks at scale.
4. **Data Visualization:** Matplotlib and Seaborn - used to interpret and understand the data.

## Dataset

The dataset used in this project is an activity log of Sparkify users covering a timeframe from October 1 to December 3, 2018. The dataset is in JSON format and was retrieved from the Udacity Amazon S3 bucket.

## MongoDB Connector for Apache Spark

The MongoDB Connector for Apache Spark is a library used in this project that allows us to connect Spark and MongoDB. This connection enables the utilization of Spark's powerful data processing capabilities on MongoDB data.

## Note

This project was conducted on a subset of the original dataset for efficiency reasons. After testing on this subset, the processes were then applied to the full dataset.
