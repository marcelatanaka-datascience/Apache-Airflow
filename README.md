# Apache Airflow

This repo was built to share some of the code I used during a course I took of Data Engineering.
The main goal is to extract data from Twitter API, then store it in a datalake through Spark RDD and then extracting insights from the data.
The chosen ELT method was medallion storage, starting from bronze files, thus raw data, then silve with minimium treatment, then gold, with analysis read for other teams to consume.

Original code sources are Twitter Development and Rafael Boittega.
