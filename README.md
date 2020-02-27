# assignment6-Pavanisree
assignment6-Pavanisree created by GitHub Classroom
In this assignment, I have implemented various ways of using Spark. The goal in this assignment is to use functionalities of spark.

## Dataset

I used the [Amazon Product Review Dataset](https://nijianmo.github.io/amazon/index.html). My dataset name is All_Beauty.json

Here in this assignment, I created a notebook where I read the dataset, explore the dataset in various ways, extracted some statistics.

I have explored the following steps.

1. Explored configuration options on SparkSession 
2. Reading the data
3. Performing Tasks
    - Exploring the data with Spark SQL
    - Exploring the data with Spark DataFrame



### 2. Reading the data
I have imported my data to `DataBricks` as a table in order to do table operations. 

I did the below the operations.

- Read data as RDD
- Read data as DataFrame
- Convert RDD to Spark DataFrame
- Convert Spark DataFrame to RDD
- Convert Spark DataFrame to Pandas DataFrame

### 3. Tasks

Using SQL queries I have performed the following tasks

- Select first 10 rows of dataset.
- Show the schema of of the dataset.
- Group by and get max, min, count of a column in the dataset.
- Filter your dataset by some conditions based on your column.
- Apply group by with having clause.
- Apply order by.
- Apply inner join/ left join/ right join on your two tables.
- Select distinct records by a column.
