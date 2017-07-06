# Spark-Streaming-Framework-and-Processing-Models

## Spark?

Spark is a general-purpose data processing engine, suitable for use in a wide range of circumstances. Interactive queries across large data sets, processing of streaming data from sensors or financial systems, and machine learning tasks tend to be most frequently associated with Spark.

From the beginning, Spark was optimized to run in memory, helping process data far more quickly than alternative approaches like Hadoop’s MapReduce, which tends to write data to and from computer hard drives between each stage of processing. Its proponents claim that Spark running in memory can be100 times faster than Hadoop MapReduce, but also 10 times faster when processing disk-based data in a similar way to Hadoop MapReduce itself. This comparison is not entirely fair, not least because raw speed tends to be more important to Spark’s typical use cases than it is to batch processing, at which MapReduce-like solutions still excel.

Typical use cases include:

• Stream processing: From log files to sensor data, application developers increasingly have to cope with “streams” of data. This data arrives in a steady stream, often from multiple sources simultaneously. While it is certainly feasible to allow these data streams to be stored on disk and analyzed retrospectively, it can sometimes be sensible or important to process and act upon the data as it arrives. Streams of data related to financial transactions, for example, can be processed in real time to identify--and refuse--potentially fraudulent transactions.

• Machine learning: As data volumes grow, machine learning approaches become more feasible and increasingly accurate. Software can be trained to identify and act upon triggers within well-understood data sets before applying the same solutions to new and unknown data. Spark’s ability to store data in memory and rapidly run repeated queries makes it wellsuited to training machine learning algorithms. Running broadly similar queries again and again, at scale, significantly reduces the time required to iterate through a set of possible solutions in order to find the most efficient algorithms.

• Interactive analytics: Rather than running pre-defined queries to create static dashboards of sales or production line productivity or stock prices, business analysts and data scientists increasingly want to explore their data by asking a question, viewing the result, and then either altering theinitial question slightly or drilling deeper into results. This interactive query process requires systems such as Spark that are able to respond and adapt quickly.

• Data integration: Data produced by different systems across a business is rarely clean or consistent enough to simply and easily be combined for reporting or analysis. Extract, transform, and load (ETL) processes are often used to pull data from different systems, clean and standardize it, and then load it into a separate system for analysis. Spark (and Hadoop) are increasingly being used to reduce the cost and time required for this ETL process.

