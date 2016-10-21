# Week 14 Lesson 2 #
## Introduction to Spark  ##

In this lesson, you will about Spark, a popular new approach to
processing big data. Spark provides an alternative to the Map-Reduce
approach for processing tasks on Hadoop. Spark was built around a
concept called Resilient Distributed Datasets (or RDDs). But the most recent version of Spark focuses on using Spark DataFrames, which are an
alternative to the Spark RDDs. With the growth in popularity of higher
level languages such as Python and R for data analytic tasks, a consensus emerged that RDDs were less than ideal for performing Spark data processing tasks. As a result, DataFrames (similar to Pandas DataFrames) were introduced into Spark. In this Notebook, we introduce the Spark DataFrame and demonstrate how to use this new data structure for big data processing within a Spark environment.

###Objectives ###

By the end of this lesson, you will be able to:

- Understand the basic concepts of Spark
- Be able to use pySpark to create Spark applications from within an IPython Notebook.
- Understand the basic concepts of a Spark DataFrame
- Be familiar with using SQL on a Spark DataFrame 
- Be able to use pySpark to work with a Spark DataFrame

### Time Estimate ###

Approximately 3 hours.

### Readings ####

_Course Notebook_

- Explore the course [Spark: DataFrames, SQL, and Basic Analysis ][l2nb]
IPython Notebook on the course JupyterHub server.

_Other Material_

- Wikipedia on [Spark][ws]
- Tutorial Introduction to [Spark][tis]
- Spark [Homepage][sh]
- Spark [Quick Start Guide][qsg], be sure to select Python for the examples.
- Tutorial Introduction to [Spark SQL][tiss]
- [Spark SQL Programming Guide][sspg], through _Data Sources_ Section

## Optional Readings ##

- Wikipedia on [Spark][ws]
- An overview of [Apache Spark][oas]
- Spark [Programming Guide][spg], be sure to select Python for the examples.
- Workshop [Introducing Spark with IPython][iws]
- Blog article on [Python and Spark][bps]
- An overview of [Apache Spark SQL][oass]
- Introduction to [Spark DataFrames][isd]
- Blog demonstrating [Spark SQL with Python][bssp]

_Safari Online Books_


- **Chapters 1, 4: Apache Spark** from _Mastering Apache Spark_, by Mike Frampton
- **Chapters 1-6, 9:** from _Learning Spark_, by Holden Karau, Andy Konwinski, 
Patrick Wendell, Matei Zaharia.


-----

[l2nb]: notebooks/sparkdf.ipynb

[ws]: https://en.wikipedia.org/wiki/Apache_Spark

[tis]: http://www.tutorialspoint.com/spark_sql/spark_introduction.htm

[sh]: http://spark.apache.org
[qsg]: https://spark.apache.org/docs/latest/quick-start.html
[spg]: https://spark.apache.org/docs/latest/programming-guide.html

[oas]: http://www.infoq.com/articles/apache-spark-introduction
[iws]: https://districtdatalabs.silvrback.com/getting-started-with-spark-in-python
[bps]: http://www.mccarroll.net/blog/pyspark2/index.html


[oass]: http://www.infoq.com/articles/apache-spark-sql
[sspg]: https://spark.apache.org/docs/latest/sql-programming-guide.html

[tiss]: http://www.tutorialspoint.com/spark_sql/spark_sql_introduction.htm

[isd]: https://databricks.com/blog/2015/02/17/introducing-dataframes-in-spark-for-large-scale-data-science.html

[bssp]: https://www.codementor.io/spark/tutorial/python-spark-sql-dataframes

