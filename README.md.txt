# 🚨 Hadoop-Based Intrusion Detection System (IDS) using Log Analysis

A distributed system that detects anomalous network traffic using Apache Flume, Hadoop MapReduce, and Spark MLlib.

## 🔍 Overview
This project uses the KDD Cup 1999 dataset to detect suspicious patterns (like UDP spikes) via clustering.

## 📦 Tech Stack
- Apache Hadoop (HDFS, MapReduce)
- Apache Flume (for log ingestion)
- Apache Spark (MLlib, Scala)
- Java (MapReduce), Scala (Clustering)

## 🔧 Steps Involved
1. Logs ingested to HDFS using Flume
2. Preprocessed with Java MapReduce (protocol frequency counts)
3. Loaded into Spark and clustered using KMeans (k=2)

## 🧪 Results
- Cluster 1 (Anomalous): Mostly UDP traffic
- Cluster 0 (Normal): TCP and ICMP

## 📁 Files
- `kdd-log-processor/`: Java code (Mapper, Reducer, Driver)
- `scala-code/`: Spark MLlib code
- `report/`: Final project report (PDF)
- `slides/`: Project presentation (PPTX)

## 👥 Team
- Muhammad Atlas Malik (24I-8020)  
- Muhammad Ahmed Qureshi (24I-8027)  
- Kashaf Sajjad (24I-8032)

## 📎 Dataset
[KDD Cup 1999 - 10% Subset](https://kdd.ics.uci.edu/databases/kddcup99/kddcup99.html)

---

This project was developed for the Data Science Tools & Techniques course at FAST Islamabad.
