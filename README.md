# Major-Project
# Web Server Log Processing Using Hadoop In Azure

## Introduction
* Big Data is an emerging growing dataset beyond the ability of a traditional database tool. Hadoop rides the big data where the massive quantity of information is processed using cluster of commodity hardware. Big Data analytics applies advanced analytical techniques of large datasets to discover hidden patterns and other useful information.
* Apache Spark is an open-source, distributed processing system used for big data workloads. It utilizes in-memory caching, and optimized query execution for fast analytic queries against data of any size.
* PySpark is an interface for Apache Spark in Python. It not only allows you to write Spark applications using Python APIs, but also provides the PySpark shell for interactively analyzing your data in a distributed environment.
* Spark SQL is a Spark module for structured data processing. It provides a programming abstraction called Data Frames and can also act as a distributed SQL query engine. It enables unmodified Hadoop Hive queries to run up to 100x faster on existing deployments and data.

## Motivation
* Main Motivation Behind Web server log analysis tools are essential for properly analyzing this information to get a clear picture of the condition of your network since modern enterprises collect and log data for almost all business processes.
* You may filter logs, perform live tail searches, and query specific log data using web log analysis tools. These systems also offer a centralized view of this data that is accessible from anywhere.

## Objectives
The Main goals of our project are
* Create an Azure Data Factory.
* Create a Storage Resource and store the dataset.
* Connect Databrick Activity to the Pipeline in Azure Data Factory.
* Clean the Dataset and save as CSV file.
* Read the CSV file as Resilient Distributed Dataset(RDD) format.
* Perform Spark jobs.
* Visualize the data using PowerBi

## Problem Statement
* From the Above Context we arrived at a Problem Statement to analyze the Web Server Logs Using Hadoop, Spark and SparkSQL to process the Web Server logs dataset to get more insights on the log data.
* As part of this, we create Azure Data Factory and connect our storage with Databrick to perform analysis on the data and get more insights of the data and also Build Scala code, submit Spark jobs and SparkSQL Queries using the dataset.


