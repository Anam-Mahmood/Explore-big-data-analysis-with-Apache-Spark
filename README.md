# Explore big data analysis with Apache Spark
Learn how Spark helps to simplify the challenging and computationally intensive task of processing high volumes of real-time data


Ever thought of how the traditional methods of data analyzing would work with the increased amount of data?

With the data increasing exponentially, we need new ways to analyze the data. Because data is the new oil and it’s valuable but if it’s not refined, it cannot be used. 44 zettabytes was the estimated data in the world by the end of 2020. This is only the data that is publicly available to us whereas, there is tons of data that we still don’t have access to. When such a huge amount of data and enormous data sets are involved, this is what we call Big Data.

Big Data refers to dynamic, large, and disparate volumes of data being created by people, tools, and machines. It refers to data sets that are so massive and so quickly built and so varied that they defy the traditional analysis methods such as you might perform with a relational database. There is no one definition of big data but there are certain elements that are common across the different definitions, such as Velocity, Volume, Variety, Veracity, and Value. These are the main 5 V’s of Big Data. Let’s look at each one of them in a bit more detail.

![5V's](https://github.com/Anam-Mahmood/Explore-big-data-analysis-with-Apache-Spark/blob/main/Images/spark.png?raw=true)

**Velocity** is the speed at which data accumulates. Data is being generated extremely fast, in a process that never stops. The attributes include near or real-time streaming, local, and cloud-based technologies that can process information very quickly. 

**Volume** is the scale of the data or increase in the amount of data stored. The drivers of volume are the increase in the data sources, higher resolution sensors, and scalable infrastructure.

**Variety** is the diversity of the data. Structured data fits neatly in rows and columns in relational databases while unstructured data is not organized in a pre-defined way, like tweets, blogs, pictures, and videos. Variety also reflects that data comes from different sources like machines, people, and processes, both internal and external to organizations. And the drivers for variety are mobiles, social media, wearable technologies, geo technologies, video, and many more.

**Veracity** is the quality and the origin of data and its conformity to facts and accuracy. Attributes include consistency, completeness, integrity, and ambiguity. The drivers include cost and the need for traceability. With large amounts of data available, the debate rages on about the accuracy and authentication of data in the digital age: Is the information real or fake? 

**Value** refers to our ability and need to turn data into value. Now the value isn’t just profit, but it may have medical or social benefits, as well as customer, employee, or personal satisfaction. Now this last V is one of the main reasons why people invest time into big data, that is because they are looking to derive value from it.

Now that we understand the basics of big data and its components the question is how big data is driving digital transformation?
Digital transformation is not simply duplicating existing processes in digital form; the in-depth analysis of how the business operates helps organizations discover how to improve their processes and operations and harness the benefits of integrating data science into their workflows.

Data Science, artificial intelligence, machine learning, and deep learning, all these buzz words that we hear very often nowadays but the definitions are still confusing. Let’s look at these definitions. 

**Data Science** is the process and method for extracting knowledge and insights from large volumes of disparate data. It’s an interdisciplinary field involving mathematics, statistical analysis, data visualization, machine learning, and more. It’s what makes it possible for us to appropriate information, see patterns, find meanings from large volumes of data, and use it to make decisions that drive business. Data science can use many of the Artificial Intelligence (AI) techniques to derive insight from data. 

Now moving to **Artificial Intelligence**, you can think of it as an umbrella term that refers to any system that mimics human behavior or intelligence. No matter how simple or complicated that behavior is. 

Now if you dig a little deeper and go into specifics of the different algorithms and statistical methods that are used by computers to make predictions and make intelligent decisions etc. All of this comes under **machine learning**. 

And then lastly, a subset of Machine Learning is **Deep Learning**, which refers to a technique in which a system uses neural networks which mimic the activities of a human brain to make intelligent decisions.

![Subset-of-AI](https://github.com/Anam-Mahmood/Explore-big-data-analysis-with-Apache-Spark/blob/main/Images/spark1.png?raw=true)

### What is Apache Spark?
Spark is one of the most active open-source community projects by Apache right now and is advertised as a “Lightning-fast unified analytics engine”. Spark provides a faster data processing platform that allows you to run programs up to 100x faster in memory and 10x faster on disk when compared to Hadoop. Spark also makes it possible to write code quickly and easily build parallel apps as it provides over 80 high-level operators.
Apache spark consists of 5 components, let us look at them in a bit more detail.

1. Apache Spark Core – Spark Core is the underlying general execution engine for the Spark platform that all other functionality is built upon. It provides in-memory computing and referencing datasets in external storage systems.

2. Spark SQL – Spark SQL is Apache Spark’s module for working with structured data. The interfaces offered by Spark SQL provides Spark with more information about the structure of both the data and the computation being performed.

3. Spark Streaming – This component allows Spark to process real-time streaming data. Data can be ingested from many sources like Kafka, Flume, and HDFS (Hadoop Distributed File System). Then the data can be processed using complex algorithms and pushed out to file systems, databases, and live dashboards.

4. MLlib (Machine Learning Library) – Apache Spark is equipped with a rich library known as MLlib. This library contains a wide array of machine learning algorithms- classification, regression, clustering, and collaborative filtering. It also includes other tools for constructing, evaluating, and tuning ML Pipelines. All these functionalities help Spark scale out across a cluster.

5. GraphX – Spark also comes with a library to manipulate graph databases and perform computations called GraphX. GraphX unifies ETL (Extract, Transform, and Load) process, exploratory analysis, and iterative graph computation within a single system.

### So why Spark?
1. **Fast processing** – The most important feature of Apache Spark and the reason people chose this technology is its speed. Big data is characterized by volume, variety, velocity, and veracity which needs to be processed at a higher speed. Spark contains Resilient Distributed Dataset (RDD) which saves time in reading and writing operations, allowing it to run almost ten to one hundred times faster than Hadoop.

2. **Flexibility** – Apache Spark supports multiple languages and allows the developers to write applications in Java, Scala, R, or Python.

3. **In-memory computing** – Spark stores the data in the RAM of servers which allows quick access and in turn accelerates the speed of analytics.

4. **Real-time processing** – Spark can process real-time streaming data and is, therefore, able to produce instant outcomes.

5. **Better analytics** – In contrast to MapReduce that includes Map and Reduce functions, Spark includes much more than that. Apache Spark consists of a rich set of SQL queries, machine learning algorithms, complex analytics, etc. With all these functionalities, analytics can be performed in a better fashion with the help of Spark.


Python originally was a scripting language, but over time it has exposed several programming paradigms like object-oriented programming, asynchronous programming, array-oriented programming, and functional programming. This helps big data analysts because through functional programming the data can be manipulated by functions without having to maintain an external state. So, your code returns new data instead of manipulating data in place, uses anonymous functions, and avoids global variables.

There are plenty of libraries available, one of which is Pandas. It is a fast, powerful, flexible, and easy-to-use open-source data analysis and manipulation tool, built on top of the Python programming language. 

Using Pandas, we can do easy data manipulation tasks such as reading, visualization, and aggregation. You can also perform:

- Data manipulation tasks such as renaming, sorting, indexing, and merging data frames.
- Cleaning and data preparation by imputing missing data.
- Modifying the definition by adding, updating, and deleting columns from a data frame.

But like we know, data is growing exponentially, and we have billions of rows and columns, operations like merging or grouping of data and this requires parallelization and distributed computing. These operations are very slow and become quite expensive and difficult to handle with libraries like Pandas where parallelization is not supported. Therefore, to build scalable applications, we need packages or software that are fast and support parallelization for large datasets. 

Apache Spark also supports different types of data structures:
- Data frames
- Datasets
- Resilient Distributed Datasets (RDD)

Spark Data frames are more suitable for structured data where you have well-defined schema whereas RDD’s are used for semi-structured and unstructured data. 

### What are Resilient Distributed Datasets (RDD)?
Resilient distributed dataset (RDD) is Spark’s fundamental primary abstraction unit of data. They are an immutable, fault-tolerant collection of elements that can be parallelized. Which means they can be made to operate in parallel. 

**There are two types of RDD operations.** 
When RDDs are created, a direct acyclic graph (DAG) is created. This type of operation is called transformations. Transformations make updates to that graph, but nothing happens until some action is called. Actions are another type of operation. The elements of the RDD can be operated on in parallel across the cluster. Remember, transformations return a pointer to the RDD created and actions return values that comes from the action.

**There are three methods for creating an RDD.** 
1. You can parallelize an existing collection. This means that the data already resides within Spark and can now be operated on in parallel. As an example, if you have an array of data, you can create an RDD out of it by calling the parallelized method. This method returns a pointer to the RDD. So this new distributed dataset can now be operated upon in parallel throughout the cluster. 

2. The second method to create an RDD, is to reference a dataset. This dataset can come from any storage source supported by Hadoop. 

3. The third method to create an RDD is from transforming an existing RDD to create a new RDD. In other words, let's say you have the array of data that you parallelized earlier. Now you want to filter out strings that are shorter than 50 characters. A new RDD is created using the filter method.

Apache Spark is being used in multiple industries like e-commerce, healthcare, media and entertainment, finance, and the travel industry. 
In the finance industry, banks are using Spark to analyze and access the call recordings, emails, forum discussions, complaint logs, etc. to gain insights to help them make the right business decisions for target advertising, customer segmentation, and credit risk assessment. 

For example, if you lost your wallet, and let's say your card is swiped for $5000 but this purchase was not done by you since you lost your wallet. This might be some sort of credit card fraud. Now the financial institutions are leveraging big data to find out when and where the frauds are happening to be able to stop them. These institutions need to be able to detect any fraud at its earliest, they have models that detect fraudulent transactions and most of them are deployed in batch environments. But now with the help of Apache-Spark working on Hadoop, financial institutions can detect fraudulent transactions in real-time, based on previous transactions and fraud footprint. All the incoming transactions are validated against a database, if there is a match then a trigger is sent to the call center. The call center personnel immediately check with the credit card owner to validate the transaction before any fraud can happen.

MyFitnessPal, one of the largest fitness communities that helps people achieve a healthy lifestyle for better diet and exercise. MyFitnessPal uses apache spark to perform data refinery and clean the data entered by users to identify high-quality food items. Using Spark, MyFitnessPal has been able to scan through food calorie data of about 80 million users. Earlier, MyFitnessPal used Hadoop to process 2.5TB of data and that took several days to identify any errors or missing information in it.

In conclusion, Apache Spark has seen immense growth over the past several years, becoming the most effective data processing and AI engine in enterprises today due to its speed, ease of use, and sophisticated analytics. Spark helps to simplify the challenging and computationally intensive task of processing high volumes of real-time data, both structured and unstructured.


### Resources:
1.	https://databricks.com/spark/about
2.	https://chartio.com/learn/data-analytics/what-is-spark/




