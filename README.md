# Realtime Log Analysis Project

## Introduction

This repository contains the code for a Real-time Log Analysis project. The main goal of this project is to provide insights into the functioning of a system through the evaluation and interpretation of computer-generated logs. The project leverages various technologies such as Apache NiFi, Apache Kafka, Apache Spark, Cassandra, HDFS, Python Plotly, and Dash, all encapsulated within Docker containers deployed on AWS EC2 instance.

## Table of Contents

- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Data Analysis](#data-analysis)
- [Usage](#usage)
- [Run docker](#run-docker)
- [Use these links to open services](#use-these-links-to-open-services)

## Project Overview

The project focuses on real-time log analysis with visualization capabilities. It includes the following stages:

1. Launching an EC2 instance on AWS.
2. Installing Docker and the necessary tools (Apache Spark, Apache NiFi, Apache Kafka, Jupyter Lab, Plotly, and Dash).
3. Preprocessing and cleaning the NASA access log dataset.
4. Using Apache NiFi and Apache Kafka for data extraction.
5. Transforming and loading data using Cassandra and HDFS.
6. Visualizing the data using Python Plotly and Dash.

The ultimate goal is to analyze NASA access log data in real-time, extract valuable information, transform and load the data into appropriate storage for speed and batch layers, and visualize it effectively.

## Data Analysis

The data analysis process includes:

1. Downloading NASA access log data in CSV format.
2. Preprocessing, cleaning, and formatting the data.
3. Extraction using Apache NiFi and Apache Kafka.
4. Transformation and loading the data using Cassandra for the Speed layer and HDFS for the Batch layer.
5. Visualizing the data in a Real-time, Hourly, and Daily manner using Plotly and Dash.

## Usage

To use this project, clone this repository, set up an EC2 instance on AWS, install Docker, and the necessary tools.

### Thank you for checking out our project! Don't forget to star ⭐ this repo if you like our project

> Disclaimer: This project is made for educational purposes and is not intended for production environments.

## Run docker

`docker-compose up -d`

## Use these links to open services

`http://localhost:8050` for real time dashboards\\
`http://localhost:4888` for jupyter notebooks\\
`http://localhost:2080` for nifi dashboard\\
`http://localhost:50070` for hdfs\\

`Don't forget to change URLs based on your specific port if you modify them in the Dockerfile`
