# Big Data Assignment -- Hadoop & Spark

## Overview

This project demonstrates distributed data processing using Hadoop
MapReduce and large-scale in-memory analytics using Apache Spark. Public
domain book text files were processed to perform word count, metadata
extraction, TF-IDF similarity analysis, and author influence network
modeling.

## Project Structure

BigData-Hadoop-Spark-Assignment/ ├── Hadoop/WordCount.java ├──
Spark/spark_analysis.py ├── books/ └── README.md

## Requirements

-   Java 17+
-   Hadoop 3.x
-   Apache Spark 4.x
-   Python 3.9+

## Hadoop WordCount

hadoop jar WordCount.jar WordCount /input /output

## Spark Analysis

spark-submit Spark/spark_analysis.py

## Features

-   Distributed MapReduce processing
-   Metadata extraction
-   TF-IDF vectorization
-   Cosine similarity
-   Author influence network

## Dataset

Project Gutenberg public domain books

## Author

Ashwini
