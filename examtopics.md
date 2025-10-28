# Exam Topics Questions

@thatonecodes

## Exam Certified Data Engineer Associate topic 1 question 3 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 3
Topic #: 1

[All Certified Data Engineer Associate Questions]

Which of the following is hosted completely in the control plane of the classic Databricks architecture? 
Suggested Answer: C 🗳️ 

A. Worker node

B. JDBC data source

C. Databricks web application

D. Databricks Filesystem

E. Driver node

**Answer: C**

**Timestamp: March 27, 2023, 10:09 a.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/104049-exam-certified-data-engineer-associate-topic-1-question-3/)

Comments: vctrhugo Highly Voted 1 year, 1 month ago Selected Answer: C C. Databricks web application In the classic Databricks architecture, the control plane includes components like the Databricks web application, the Databricks REST API, and the Databricks Workspace. These components are responsible for managing and controlling the Databricks environment, including cluster provisioning, notebook management, access control, and job scheduling. The other options, such as worker nodes, JDBC data sources, Databricks Filesystem (DBFS), and driver nodes, are typically part of the data plane or the execution environment, which is separate from the control plane. Worker nodes are responsible for executing tasks and computations, JDBC data sources are used to connect to external databases, DBFS is a distributed file system for data storage, and driver nodes are responsible for coordinating the execution of Spark jobs. upvoted 19 times ... h79 Highly Voted 2 years, 7 months ago I disagree with this answer. I think its the databricks web app that is always in the control plane upvoted 15 times XiltroX 2 years, 7 months ago Agreed. Its Web app for sure upvoted 2 times ... XiltroX 2 years, 6 months ago I think I meant to say that its option C. Not sure why I said that I agree with the answer in Examtopics. Option C for sure. upvoted 1 times ... ... thaoho2402 Most Recent 3 months ago Selected Answer: C Option C. Databricks web application. upvoted 1 times ... man5484 3 months, 1 week ago Selected Answer: C Managed entirely by Databricks. It includes: Databricks Web Application (UI and REST APIs) Job scheduling, notebook management Cluster configuration UI Authentication, RBAC, workspace metadata upvoted 2 times ... EffeDevelop 4 months ago Selected Answer: B Wtf does this mean upvoted 1 times ... Max_Law 4 months, 3 weeks ago Selected Answer: C In the classic Databricks architecture, the control plane manages and hosts elements related to user interfaces, notebooks, jobs metadata, and cluster configurations. The Databricks web application, which users interact with via their browser, is fully hosted in the control plane. In contrast: Worker nodes and the driver node live in the data plane, where actual computation occurs. The Databricks Filesystem (DBFS) spans both planes depending on what is stored. A JDBC data source is external and not hosted within Databricks at all. upvoted 1 times ... dinesh6351 6 months ago Selected Answer: C Correct C upvoted 1 times ... Tedet 9 months, 2 weeks ago Selected Answer: C Refer to architecture of Lakehouse upvoted 1 times ... 806e7d2 11 months, 2 weeks ago Selected Answer: C In the classic Databricks architecture, the Databricks web application (which includes the Databricks user interface, job scheduling, and management components) is hosted entirely in the control plane. This control plane is managed by Databricks and contains the user-facing services and APIs that allow users to interact with the Databricks environment. Here’s why the other options don’t fit: A. Worker node and E. Driver node: Both the driver and worker nodes are part of the data plane, where actual data processing occurs. B. JDBC data source: This is external to Databricks, typically hosted wherever the source database resides, and does not exist within the control plane. D. Databricks Filesystem (DBFS): While DBFS metadata might be managed by the control plane, the actual data is stored in the data plane (often within the customer’s cloud account, such as in AWS S3 or Azure Data Lake Storage). upvoted 2 times ... Majjjj 1 year, 1 month ago Selected Answer: C The control plane in the classic Databricks architecture is responsible for managing the Databricks workspace, user and group management, and cluster management, among other things. The Databricks web application is a part of the control plane that enables users to interact with the workspace, create and manage clusters, and work with notebooks, jobs, and data. Worker nodes and driver nodes are part of the data plane, which is responsible for executing data processing tasks. JDBC data sources and the Databricks Filesystem are services that are used by both the control plane and the data plane. upvoted 3 times ... vctrhugo 1 year, 1 month ago Selected Answer: C C. Databricks web application The Databricks web application, which provides the user interface for interacting with Databricks, is hosted entirely in the control plane. It allows users to manage and monitor their clusters, notebooks, and jobs, among other functionalities. The other components mentioned are associated with the compute layer in the classic Databricks architecture: A. Worker node: Worker nodes are responsible for executing the actual computations and processing the data. B. JDBC data source: A JDBC data source refers to an external database or data source accessed through the Java Database Connectivity (JDBC) interface. It is typically located outside of the control plane. D. Databricks Filesystem: The Databricks Filesystem (DBFS) is a distributed file system that stores and manages data within the compute layer. E. Driver node: The driver node is responsible for coordinating the execution of tasks across the worker nodes and managing the user session. upvoted 3 times ... afzalmp40 1 year, 2 months ago Selected Answer: C C is correct upvoted 1 times ... Teja_50 1 year, 2 months ago Selected Answer: C C is correct upvoted 1 times ... 80370eb 1 year, 2 months ago Selected Answer: C its "C" - Control plane has Databricks web application upvoted 1 times ... ranjan24 1 year, 3 months ago Its C. other options, such as worker nodes, JDBC data sources, Databricks Filesystem (DBFS), and driver nodes, are typically part of the data plane or the execution environment, which is separate from the control plane. upvoted 1 times ... mascarenhaslucas 1 year, 4 months ago Selected Answer: C The answer is C! Accordinglu with the Databricks documentation, a cluster consists of one driver node and zero or more worker nodes, by default the driver node uses the same instance type as the worker node. upvoted 1 times ... benni_ale 1 year, 6 months ago Selected Answer: C Nodes are on the Data Plane. I think the Web App is the only one in the Control Pane. upvoted 1 times ... Load full discussion...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 4 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 4
Topic #: 1

[All Certified Data Engineer Associate Questions]

Which of the following benefits of using the Databricks Lakehouse Platform is provided by Delta Lake? 
Suggested Answer: D 🗳️ 

A. The ability to manipulate the same data using a variety of languages

B. The ability to collaborate in real time on a single notebook

C. The ability to set up alerts for query failures

D. The ability to support batch and streaming workloads

E. The ability to distribute complex data operations

**Answer: D**

**Timestamp: April 1, 2023, 3:32 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/104733-exam-certified-data-engineer-associate-topic-1-question-4/)

Comments: vctrhugo Highly Voted 2 years, 1 month ago Selected Answer: D D. The ability to support batch and streaming workloads Delta Lake is a key component of the Databricks Lakehouse Platform that provides several benefits, and one of the most significant benefits is its ability to support both batch and streaming workloads seamlessly. Delta Lake allows you to process and analyze data in real-time (streaming) as well as in batch, making it a versatile choice for various data processing needs. While the other options may be benefits or capabilities of Databricks or the Lakehouse Platform in general, they are not specifically associated with Delta Lake. upvoted 16 times ... thaoho2402 Most Recent 3 months ago Selected Answer: D Option D. The ability to support batch and streaming workloads -> The key feature of lakehouse is supporting batch and streaming workloads. For example streaming data into Delta Tables, reading the Delta Table in batch or streaming. upvoted 2 times ... man5484 3 months, 1 week ago Selected Answer: D Delta Lake is the storage layer technology that powers the Databricks Lakehouse Platform. It brings ACID transactions, schema enforcement, time travel, and — importantly — support for both batch and streaming workloads to data lakes. What Delta Lake enables: You can write streaming data into Delta tables. You can read the same Delta table in batch or streaming mode. It provides exactly-once processing, atomic writes, and schema evolution, making it ideal for real-time + historical data scenarios. So if your use case involves IoT ingestion, clickstream data, or scheduled data pipelines, Delta Lake ensures reliable reads/writes — whether you're ingesting continuously or in chunks. upvoted 1 times ... EffeDevelop 4 months ago Selected Answer: D It's delta lakes, A is for notebooks upvoted 1 times ... Basha1996 8 months ago Selected Answer: D D. The ability to support batch and streaming workloads Adding features such as ACID Properties are allowed which eliminate the drawbacks on DW and Data lake. upvoted 1 times ... Tedet 9 months, 2 weeks ago Selected Answer: D The ability to support batch and streaming workloads - Key feature of lakehouse upvoted 1 times ... afzalmp40 1 year, 2 months ago Selected Answer: D D is correct upvoted 1 times ... 80370eb 1 year, 2 months ago Selected Answer: D D. The ability to support batch and streaming workloads upvoted 1 times ... mascarenhaslucas 1 year, 4 months ago Selected Answer: D The answer is D! upvoted 1 times ... Itmma 1 year, 7 months ago Selected Answer: D D is correct upvoted 2 times ... VijayKula 2 years ago Selected Answer: D Answer is D upvoted 1 times ... KalavathiP 2 years, 1 month ago Selected Answer: D Correct and D upvoted 1 times ... nb1000 2 years, 3 months ago D is correct upvoted 1 times ... Data_4ever 2 years, 6 months ago Selected Answer: D Delta Lake supports both Batch & Stream workloads upvoted 4 times ... knivesz 2 years, 6 months ago Selected Answer: D Respuesta correcta es D upvoted 4 times ... surrabhi_4 2 years, 6 months ago Selected Answer: D option D upvoted 3 times ... XiltroX 2 years, 7 months ago D is the right answer https://learn.microsoft.com/en-us/azure/databricks/delta/ upvoted 3 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 5 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 5
Topic #: 1

[All Certified Data Engineer Associate Questions]

Which of the following describes the storage organization of a Delta table? 
Suggested Answer: C 🗳️ 

A. Delta tables are stored in a single file that contains data, history, metadata, and other attributes.

B. Delta tables store their data in a single file and all metadata in a collection of files in a separate location.

C. Delta tables are stored in a collection of files that contain data, history, metadata, and other attributes.

D. Delta tables are stored in a collection of files that contain only the data stored within the table.

E. Delta tables are stored in a single file that contains only the data stored within the table.

**Answer: C**

**Timestamp: April 1, 2023, 3:37 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/104735-exam-certified-data-engineer-associate-topic-1-question-5/)

Comments: Hink 1 week, 5 days ago Selected Answer: C Data is stored in several parquet files and metadata in several json files. upvoted 1 times ... thaoho2402 3 months ago Selected Answer: C Option 1. Delta tables are stored in a collection of files that contain data, history, metadata, and other attributes. -> Delta tables store data under parquet files. Also, they maintain metadata and transation logs in separate directories. With thí approach, it allows to enable versioning, transactional capabilities, etc. upvoted 1 times ... kohki 3 months, 1 week ago Selected Answer: C C is correct upvoted 1 times ... man5484 3 months, 1 week ago Selected Answer: C Delta Lake stores Delta tables as directories (not a single file) in a file system such as S3, ADLS, or DBFS. Inside this directory, you'll find a structured layout: upvoted 1 times ... Tedet 9 months, 2 weeks ago Selected Answer: C Delta tables store data in a structured manner using Parquet files, and they also maintain metadata and transaction logs in separate directories. This organization allows for versioning, transactional capabilities, and metadata tracking in Delta Lake. Thank you for pointing out the error, and I appreciate your understanding. upvoted 4 times ... 806e7d2 11 months, 2 weeks ago Selected Answer: C Delta tables use a distributed storage format, where data, history, metadata, and other attributes are stored across multiple files. This includes data files (e.g., Parquet files) for the actual data and log files for transaction history and metadata, allowing Delta Lake to support version control, schema enforcement, and ACID properties. upvoted 4 times ... vctrhugo 1 year, 1 month ago Selected Answer: C C. Delta tables are stored in a collection of files that contain data, history, metadata, and other attributes. Delta tables store data in a structured manner using Parquet files, and they also maintain metadata and transaction logs in separate directories. This organization allows for versioning, transactional capabilities, and metadata tracking in Delta Lake. Thank you for pointing out the error, and I appreciate your understanding. upvoted 3 times ... 80370eb 1 year, 2 months ago Selected Answer: C C. Delta tables are stored in a collection of files that contain data, history, metadata, and other attributes. upvoted 1 times ... mascarenhaslucas 1 year, 4 months ago Selected Answer: C The answer is C! upvoted 1 times ... benni_ale 1 year, 6 months ago Selected Answer: C GPT4: Delta tables in Databricks use: Parquet format files for data storage. A _delta_log folder for JSON log files that track transactions. Scheme enforcement in metadata to ensure consistency. Checkpoint files to speed up the rebuilding of the table state. upvoted 4 times ... Itmma 1 year, 7 months ago Selected Answer: C C is correct upvoted 1 times ... SerGrey 1 year, 10 months ago Selected Answer: C C is correct upvoted 1 times ... VijayKula 2 years ago Answer is C upvoted 1 times ... Sriramiyer92 2 years ago Reading Material: 5 reasons to choose Delta format (on Databricks) https://medium.com/datalex/5-reasons-to-use-delta-lake-format-on-databricks-d9e76cf3e77d upvoted 2 times ... KalavathiP 2 years, 1 month ago Selected Answer: C Correct ans C upvoted 1 times ... andie123 2 years, 2 months ago Selected Answer: C C is the right answer upvoted 2 times ... Atnafu 2 years, 3 months ago C Delta tables in Databricks Delta Lake are stored in a collection of files organized in a directory structure. This directory structure includes data files, transaction log files, and metadata files. These files are stored in a specified location, typically in a distributed file system such as Hadoop Distributed File System (HDFS) or Amazon S3. upvoted 2 times ... Load full discussion...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 6 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 6
Topic #: 1

[All Certified Data Engineer Associate Questions]

Which of the following code blocks will remove the rows where the value in column age is greater than 25 from the existing Delta table my_table and save the updated table? 
Suggested Answer: C 🗳️ 

A. SELECT * FROM my_table WHERE age > 25;

B. UPDATE my_table WHERE age > 25;

C. DELETE FROM my_table WHERE age > 25;

D. UPDATE my_table WHERE age <= 25;

E. DELETE FROM my_table WHERE age <= 25;

**Answer: C**

**Timestamp: April 1, 2023, 3:38 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/104736-exam-certified-data-engineer-associate-topic-1-question-6/)

Comments: thaoho2402 3 months ago Selected Answer: C Correct answer is C upvoted 2 times ... man5484 3 months, 1 week ago Selected Answer: C Delta Lake supports DELETE statements using SQL syntax — just like in traditional SQL databases — provided the table is a Delta table. upvoted 2 times ... Kundankg 3 months, 4 weeks ago Selected Answer: C Correct Answer is C upvoted 2 times ... sunil01 6 months, 3 weeks ago Selected Answer: C Answer is C upvoted 2 times ... devbila 7 months ago Selected Answer: C Response is C upvoted 1 times ... 80370eb 1 year, 2 months ago Selected Answer: C to remove the data from a table we can use delete from table with condition. upvoted 1 times ... mascarenhaslucas 1 year, 4 months ago Selected Answer: C The answer is C! upvoted 1 times ... Svengance 1 year, 6 months ago Selected Answer: A there is not delete history option just the vacuum with its parameters of time retention. upvoted 1 times ... bettermakeme 1 year, 7 months ago Answer is C. Just finished exam-got 100% [Databricks Associate Exam Practice Exams] All questions came from Databricks Certified Data Engineer Associate https://www.udemy.com/share/10aEFa3@9M_uT6vrKbnl68tOK96kfy-YWitjwzLTlVCrzPs-0hGUu8fyX8V4Tn_x_y65bwLm/ upvoted 3 times ... Itmma 1 year, 7 months ago Selected Answer: C C is correct upvoted 1 times ... SerGrey 1 year, 10 months ago Selected Answer: C C. DELETE FROM my_table WHERE age > 25; upvoted 1 times ... VijayKula 2 years ago Selected Answer: C Answer is C upvoted 1 times ... DavidRou 2 years, 1 month ago Selected Answer: C C is the correct answer as the SELECT statement allows to query a table, the UPDATE statement allows to modify values in columns. If you want to remove rows that don't match a specific condition you must use DELETE upvoted 2 times ... KalavathiP 2 years, 1 month ago Selected Answer: C C is correct upvoted 1 times ... ArindamNath 2 years, 1 month ago C is correct upvoted 1 times ... vctrhugo 2 years, 1 month ago Selected Answer: C C. DELETE FROM my_table WHERE age > 25; upvoted 1 times ... nb1000 2 years, 3 months ago C is correct upvoted 1 times ... Load full discussion...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 9 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 9
Topic #: 1

[All Certified Data Engineer Associate Questions]

Which of the following data lakehouse features results in improved data quality over a traditional data lake? 
Suggested Answer: B 🗳️ 

A. A data lakehouse provides storage solutions for structured and unstructured data.

B. A data lakehouse supports ACID-compliant transactions.

C. A data lakehouse allows the use of SQL queries to examine data.

D. A data lakehouse stores data in open formats.

E. A data lakehouse enables machine learning and artificial Intelligence workloads.

**Answer: B**

**Timestamp: April 1, 2023, 3:53 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/104743-exam-certified-data-engineer-associate-topic-1-question-9/)

Comments: ThomasReps Highly Voted 2 years, 4 months ago Selected Answer: B Option B - ACID Properties Source: https://www.databricks.com/blog/2021/08/30/frequently-asked-questions-about-the-data-lakehouse.html#five -> "Lakehouse tackles the fundamental issues that make data swamps out of data lakes. It adds ACID transactions to ensure consistency as multiple parties concurrently read or write data." upvoted 16 times ... vctrhugo Highly Voted 2 years, 1 month ago Selected Answer: B B. A data lakehouse supports ACID-compliant transactions. One of the key features of a data lakehouse that results in improved data quality over a traditional data lake is its support for ACID (Atomicity, Consistency, Isolation, Durability) transactions. ACID transactions provide data integrity and consistency guarantees, ensuring that operations on the data are reliable and that data is not left in an inconsistent state due to failures or concurrent access. In a traditional data lake, such transactional guarantees are often lacking, making it challenging to maintain data quality, especially in scenarios involving multiple data writes, updates, or complex transformations. A data lakehouse, by offering ACID compliance, helps maintain data quality by providing strong consistency and reliability, which is crucial for data pipelines and analytics. upvoted 11 times ... EPFO Most Recent 1 month ago Selected Answer: B Data Lakehouse supports ACID- compliant transactions natively upvoted 2 times ... sebastianbrinezc 1 month ago Selected Answer: B ACID transactions guarantee data quality upvoted 2 times ... thaoho2402 3 months ago Selected Answer: B Correct answer is B. A data lakehouse supports ACID-compliant transactions. -> Key feature of lakehouse is that data quality is improved and support for ACID (Atomicity, Consistency, Isolation, and Durability) transactions. upvoted 1 times ... man5484 3 months, 1 week ago Selected Answer: B Improved data quality means ensuring that data is consistent, reliable, and accurate — especially when multiple users or processes are reading and writing to it concurrently. In a traditional data lake, there’s no built-in support for ACID transactions, so: Writes and reads can clash Partially written files can cause inconsistent or corrupt data There's no guarantee of atomicity or isolation upvoted 1 times ... SoumyaHK 6 months ago Selected Answer: B The response is B upvoted 1 times ... Harman30 11 months, 3 weeks ago Selected Answer: B B. A data lakehouse supports ACID-compliant transactions. upvoted 1 times ... 9d4d68a 1 year, 2 months ago B. A data lakehouse supports ACID-compliant transactions. ACID compliance (Atomicity, Consistency, Isolation, Durability) ensures that transactions are processed reliably and helps maintain data integrity. This feature allows for reliable updates, deletions, and insertions in a data lakehouse, which significantly improves data quality by avoiding issues like partial updates or inconsistent states that are common in traditional data lakes. upvoted 1 times ... 80370eb 1 year, 2 months ago Selected Answer: B B. A data lakehouse supports ACID-compliant transactions. ACID compliance ensures data integrity and consistency, which improves the overall quality of the data. upvoted 1 times ... ranjan24 1 year, 3 months ago answer is B upvoted 1 times ... mascarenhaslucas 1 year, 4 months ago Selected Answer: B The answer is B! upvoted 1 times ... bm.bala.murugan.sb 1 year, 5 months ago Selected Answer: B B is Correct upvoted 1 times ... benni_ale 1 year, 6 months ago Selected Answer: B b is correct as acid transactions are related to data quality upvoted 1 times ... benni_ale 1 year, 6 months ago Selected Answer: B b is correct upvoted 2 times ... Itmma 1 year, 7 months ago Selected Answer: B B is correct upvoted 1 times ... SerGrey 1 year, 9 months ago Selected Answer: B Correct andwer is B upvoted 1 times ... Load full discussion...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 11 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 11
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer has left the organization. The data team needs to transfer ownership of the data engineer’s Delta tables to a new data engineer. The new data engineer is the lead engineer on the data team.Assuming the original data engineer no longer has access, which of the following individuals must be the one to transfer ownership of the Delta tables in Data Explorer? 
Suggested Answer: C 🗳️ 

A. Databricks account representative

B. This transfer is not possible

C. Workspace administrator

D. New lead data engineer

E. Original data engineer

**Answer: C**

**Timestamp: April 1, 2023, 3:59 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/104745-exam-certified-data-engineer-associate-topic-1-question-11/)

Comments: Garyn Highly Voted 1 year, 10 months ago Selected Answer: C The ownership of Delta tables in Data Explorer can be transferred by the current owner, a metastore admin, or the owner of the container1. In this case, since the original data engineer no longer has access, the Workspace Administrator (Option C) would be the most appropriate individual to transfer the ownership of the Delta tables to the new data engineer. This is because the Workspace Administrator typically has the necessary permissions to manage such resources2. Please note that the exact process may vary depending on the specific configurations and permissions set up in your workspace. It’s always a good idea to consult with your organization’s IT or data governance team to ensure the correct procedures are followed. upvoted 10 times ... EPFO Most Recent 1 month ago Selected Answer: C It's C the Workspace Administrator upvoted 2 times ... sebastianbrinezc 1 month ago Selected Answer: C Workspace administrator has the privilege to reassign Delta table's ownership. upvoted 2 times ... thaoho2402 3 months ago Selected Answer: C Option C. Workspace administrator. Because the workspace administrator can view and manage all objects, change ownership of delta tables, and assign permissions. upvoted 2 times ... man5484 3 months, 1 week ago Selected Answer: C In Databricks, ownership of Delta tables (and other assets like notebooks, dashboards, etc.) is governed by access control via the Unity Catalog (or legacy workspace-based permissions if Unity isn't enabled). If the original data engineer has left and no longer has access, only a user with elevated privileges — like a workspace admin — can transfer ownership or reassign permissions. The workspace administrator can: View and manage all objects Change ownership of Delta tables using the Data Explorer or CLI Assign permissions to other users or groups, such as the new lead engineer upvoted 2 times ... SoumyaHK 6 months ago Selected Answer: C The response is C upvoted 1 times ... marioscarasciaagile 1 year, 2 months ago Selected Answer: C C. Workspace administrator upvoted 1 times ... 80370eb 1 year, 2 months ago Selected Answer: C C. Workspace administrator upvoted 1 times ... souldiv 1 year, 3 months ago Workspace admin upvoted 1 times ... ranjan24 1 year, 3 months ago Question is to give access to new data engineer, How will he/she have it ? correct answer is C - Workspace admin upvoted 2 times ... 3fbc31b 1 year, 3 months ago Selected Answer: C The new data engineer would be unable to make this change. It's up to the WSA. upvoted 1 times ... carlosmps 1 year, 5 months ago Option c upvoted 1 times ... Svengance 1 year, 6 months ago Selected Answer: C workspace admin upvoted 2 times ... benni_ale 1 year, 6 months ago Selected Answer: C workspace admin upvoted 1 times ... Itmma 1 year, 7 months ago Selected Answer: C C is correct upvoted 1 times ... SerGrey 1 year, 9 months ago Selected Answer: C Correct answer is C upvoted 1 times ... Huroye 1 year, 11 months ago The answer is C - the workspace admin. How can it be the new DE? You do not even know if the new DE has access. That was not stated and so you cannot consider it. upvoted 2 times ... Load full discussion...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 12 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 12
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data analyst has created a Delta table sales that is used by the entire data analysis team. They want help from the data engineering team to implement a series of tests to ensure the data is clean. However, the data engineering team uses Python for its tests rather than SQL.Which of the following commands could the data engineering team use to access sales in PySpark? 
Suggested Answer: E 🗳️ 

A. SELECT * FROM sales

B. There is no way to share data between PySpark and SQL.

C. spark.sql("sales")D. spark.delta.table("sales")

E. spark.table("sales")

**Answer: E**

**Timestamp: April 1, 2023, 4:03 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/104748-exam-certified-data-engineer-associate-topic-1-question-12/)

Comments: Atnafu Highly Voted 2 years, 3 months ago E The spark.table() function in PySpark allows you to access tables registered in the catalog, including Delta tables. By specifying the table name ("sales"), the data engineering team can read the Delta table and perform various operations on it using PySpark. Option A, SELECT * FROM sales, is a SQL syntax and cannot be directly used in PySpark. Option B, "There is no way to share data between PySpark and SQL," is incorrect. PySpark provides the capability to interact with data using both SQL and DataFrame/DataSet APIs. Option C, spark.sql("sales"), is a valid command to execute SQL queries on registered tables in PySpark. However, in this case, the "sales" argument alone is not a valid SQL query. Option D, spark.delta.table("sales"), is a specific method provided by Delta Lake to access Delta tables directly. While it can be used to access the "sales" table, it is not the most common approach in PySpark. upvoted 24 times ... 26shubs Most Recent 1 month, 2 weeks ago Selected Answer: E Option E is correct. upvoted 2 times ... thaoho2402 3 months ago Selected Answer: E Correct answer is E. spark.table("sales") upvoted 2 times ... man5484 3 months, 1 week ago Selected Answer: E In PySpark, the spark.table() function is used to access a table by name, including Delta tables, as long as they are registered in the metastore (either Hive or Unity Catalog). So if the data analyst has already created a shared Delta table called sales, the data engineering team can access it in PySpark like this: upvoted 1 times ... melvin_muthu 6 months ago Selected Answer: E Spark.table reads the table as dataframe upvoted 3 times ... SoumyaHK 6 months ago Selected Answer: E The response is E. I do not see any option D upvoted 1 times ... dhohigh 9 months, 1 week ago Selected Answer: E This answer is pure python and is a simple solution for the Question. upvoted 1 times ... 9d4d68a 1 year, 2 months ago To access the Delta table sales using PySpark, the data engineering team can use the following command: E. spark.table("sales") This command allows them to load the table into a PySpark DataFrame, which they can then use for their tests and data processing in Python. No, the command spark.delta.table("table name") does not exist in PySpark. To access a Delta table, you should use: spark.table("table name") Or, if you need to use Delta-specific functionality, you would typically use Delta's APIs or spark.read.format("delta").table("table name") to read the table into a DataFrame. upvoted 1 times ... 80370eb 1 year, 2 months ago Selected Answer: E E. spark.table("sales") This command allows the team to access the table using PySpark, enabling them to implement their tests in Python. upvoted 1 times ... souldiv 1 year, 3 months ago spark.table() . E is the correct one upvoted 1 times ... benni_ale 1 year, 6 months ago Selected Answer: E E is correct upvoted 1 times ... benni_ale 1 year, 6 months ago Selected Answer: E e is correct upvoted 2 times ... Itmma 1 year, 7 months ago Selected Answer: E E is correct upvoted 1 times ... SerGrey 1 year, 9 months ago Selected Answer: E Correct answer is E upvoted 1 times ... Garyn 1 year, 10 months ago Selected Answer: E E. spark.table("sales") The spark.table() function in PySpark allows access to a registered table within the SparkSession. In this case, "sales" is the name of the Delta table created by the data analyst, and the spark.table() function enables access to this table for performing data engineering tests using Python (PySpark). upvoted 4 times ... csd 1 year, 10 months ago C is correct Answer upvoted 1 times ... awofalus 1 year, 11 months ago Selected Answer: E Correct is E upvoted 1 times ... Load full discussion...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 13 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 13
Topic #: 1

[All Certified Data Engineer Associate Questions]

Which of the following commands will return the location of database customer360? 
Suggested Answer: C 🗳️ 

A. DESCRIBE LOCATION customer360;

B. DROP DATABASE customer360;

C. DESCRIBE DATABASE customer360;

D. ALTER DATABASE customer360 SET DBPROPERTIES ('location' = '/user'};

E. USE DATABASE customer360;

**Answer: C**

**Timestamp: April 1, 2023, 4:04 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/104750-exam-certified-data-engineer-associate-topic-1-question-13/)

Comments: vctrhugo Highly Voted 2 years, 1 month ago Selected Answer: C C. DESCRIBE DATABASE customer360; To retrieve the location of a database named "customer360" in a database management system like Hive or Databricks, you can use the DESCRIBE DATABASE command followed by the database name. This command will provide information about the database, including its location. upvoted 10 times ... SoumyaHK Most Recent 6 months ago Selected Answer: C The response is C upvoted 2 times ... 80370eb 1 year, 2 months ago Selected Answer: C C. DESCRIBE DATABASE customer360; this will show the location of the databaase. upvoted 2 times ... benni_ale 1 year, 6 months ago Selected Answer: C C is correct upvoted 2 times ... Itmma 1 year, 7 months ago Selected Answer: C C is correct upvoted 1 times ... SerGrey 1 year, 9 months ago Selected Answer: C Correct answer is C upvoted 1 times ... awofalus 1 year, 11 months ago Selected Answer: C Correct :C upvoted 1 times ... KalavathiP 2 years, 1 month ago Selected Answer: C C is correct upvoted 1 times ... Akshay67364 2 years, 2 months ago Option C upvoted 1 times ... Gowthamr02 2 years, 2 months ago Option C upvoted 1 times ... Varma_Saraswathula 2 years, 6 months ago Option C - https://spark.apache.org/docs/3.0.0-preview/sql-ref-syntax-aux-describe-database.html upvoted 2 times ... surrabhi_4 2 years, 6 months ago Selected Answer: C option c upvoted 2 times ... knivesz 2 years, 6 months ago Selected Answer: C Muy facil upvoted 2 times ... XiltroX 2 years, 7 months ago Selected Answer: C Correct answer upvoted 3 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 14 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 14
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer wants to create a new table containing the names of customers that live in France.They have written the following command:A senior data engineer mentions that it is organization policy to include a table property indicating that the new table includes personally identifiable information (PII).Which of the following lines of code fills in the above blank to successfully complete the task? 
Suggested Answer: D 🗳️ 

A. There is no way to indicate whether a table contains PII.

B. "COMMENT PII"

C. TBLPROPERTIES PII

D. COMMENT "Contains PII"

E. PII

**Answer: D**

**Timestamp: April 2, 2023, 3:35 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/104865-exam-certified-data-engineer-associate-topic-1-question-14/)

Comments: Huroye Highly Voted 1 year, 11 months ago The correct answer is D. COMMENT "Contains PII". Context matters. Yes, you can use Table Property to add additional metadata. But you cannot view that property when you describe the table. With the Comment "this is ..." anyone who describe the table <DESC <table name> will see the comment. upvoted 14 times ... Gems1 Highly Voted 2 years, 3 months ago D Ref:https://www.databricks.com/discover/pages/data-quality-management CREATE TABLE my_table (id INT COMMENT 'Unique Identification Number', name STRING COMMENT 'PII', age INT COMMENT 'PII') TBLPROPERTIES ('contains_pii'=True) COMMENT 'Contains PII'; upvoted 10 times ... SoumyaHK Most Recent 6 months ago Selected Answer: D The response is D upvoted 1 times ... 3fbc31b 1 year, 3 months ago Selected Answer: D The correct answer is D. There is no syntax for TBLPROPERTIES PII. upvoted 1 times ... benni_ale 1 year, 6 months ago Selected Answer: D D is correct upvoted 1 times ... Itmma 1 year, 7 months ago Selected Answer: D D is correct upvoted 1 times ... a_51 1 year, 7 months ago Selected Answer: D https://docs.databricks.com/en/sql/language-manual/sql-ref-syntax-ddl-create-table-using.html COMMENT column_comment A string literal to describe the column. upvoted 1 times ... agAshish 1 year, 9 months ago answer C : CREATE TABLE new_table AS SELECT customer_name FROM original_table WHERE country = 'France' TBLPROPERTIES ('PII'='true'); upvoted 2 times ... SerGrey 1 year, 9 months ago Selected Answer: D Correct answer is D upvoted 1 times ... awofalus 1 year, 11 months ago Selected Answer: D correct :D upvoted 1 times ... chris_mach 2 years ago Selected Answer: D D is correct upvoted 1 times ... KalavathiP 2 years, 1 month ago Selected Answer: D D is correct upvoted 1 times ... vctrhugo 2 years, 1 month ago Selected Answer: D D. COMMENT "Contains PII" upvoted 1 times ... Atnafu 2 years, 3 months ago D The COMMENT keyword is used to add a comment to a table. The comment can be used to provide additional information about the table, such as its purpose or the data that it contains. In this case, the data engineer wants to add a comment to the customersInFrance table indicating that the table contains PII. The following line of code will do this: Code snippet COMMENT "Contains PII" Use code with caution. Learn more This will add the comment "Contains PII" to the customersInFrance table. The other options are not valid ways to indicate that a table contains PII. The TBLPROPERTIES keyword is used to set the table properties, but there is no property for indicating whether a table contains PII. The PII keyword is not a valid keyword in SQL. Therefore, the only valid way to indicate that a table contains PII is to use the COMMENT keyword. upvoted 3 times ... Virendev 2 years, 5 months ago Selected Answer: D syntax of C is wrong. upvoted 2 times [Removed] 2 years, 5 months ago Exactly. The correct syntax for table properties is: TBLPROPERTIES ('foo'='bar'); upvoted 1 times ... ... softthinkers 2 years, 5 months ago Correct answer should be C asommand creates a new table called "customersInFrance" with the properties of Personally Identifiable Information (PII) and selects the columns ID, FIRSTNAME, LASTNAME, ADDRESS, and PHONE_NUMBER from the existing "customers" table where the country is France. upvoted 2 times ... Varma_Saraswathula 2 years, 6 months ago D https://learn.microsoft.com/en-us/azure/databricks/sql/language-manual/sql-ref-syntax-ddl-create-table-using upvoted 1 times ... Load full discussion...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 16 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 16
Topic #: 1

[All Certified Data Engineer Associate Questions]

Which of the following commands can be used to write data into a Delta table while avoiding the writing of duplicate records? 
Suggested Answer: C 🗳️ 

A. DROP

B. IGNORE

C. MERGE

D. APPEND

E. INSERT

**Answer: C**

**Timestamp: April 2, 2023, 3:29 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/104863-exam-certified-data-engineer-associate-topic-1-question-16/)

Comments: 80370eb Highly Voted 1 year, 2 months ago Selected Answer: C C. MERGE The MERGE command allows you to perform upserts (update and insert) into a Delta table, effectively avoiding duplicates by updating existing records and inserting new ones as needed. upvoted 6 times ... Hink Most Recent 1 week, 5 days ago Selected Answer: C UPSERT can be INSERT, UPDATE, and/or DELETE MERGE INTO TargetTable AS target USING SourceTable AS source ON target.ID = source.ID WHEN MATCHED THEN UPDATE SET target.Name = source.Name WHEN NOT MATCHED BY TARGET THEN INSERT (ID, Name) VALUES (source.ID, source.Name) WHEN NOT MATCHED BY SOURCE THEN DELETE; upvoted 1 times ... SoumyaHK 6 months ago Selected Answer: C The response is C upvoted 1 times ... BharaniRaj 1 year, 5 months ago Selected Answer: C C is the right answer upvoted 1 times ... benni_ale 1 year, 6 months ago Selected Answer: C C merge upvoted 1 times ... SerGrey 1 year, 9 months ago Selected Answer: C Correct answer is C upvoted 1 times ... awofalus 1 year, 11 months ago Selected Answer: C C is correct upvoted 1 times ... J_1_2 2 years ago Selected Answer: C Merge is correct upvoted 1 times ... DavidRou 2 years ago MERGE INTO is the one to choose if you want to avoid duplicates. upvoted 2 times ... chris_mach 2 years ago Selected Answer: C Merge is correct upvoted 1 times ... KalavathiP 2 years, 1 month ago Selected Answer: C Merge will avoid duplicates by comparing the results based on primary key columns upvoted 1 times ... vctrhugo 2 years, 1 month ago Selected Answer: C C. MERGE The MERGE command is used to write data into a Delta table while avoiding the writing of duplicate records. It allows you to perform an "upsert" operation, which means that it will insert new records and update existing records in the Delta table based on a specified condition. This helps maintain data integrity and avoid duplicates when adding new data to the table. upvoted 3 times ... Atnafu 2 years, 3 months ago C. MERGE To write data into a Delta table while avoiding the writing of duplicate records, you can use the MERGE command. The MERGE command in Delta Lake allows you to combine the ability to insert new records and update existing records in a single atomic operation. The MERGE command compares the data being written with the existing data in the Delta table based on specified matching criteria, typically using a primary key or unique identifier. It then performs conditional actions, such as inserting new records or updating existing records, depending on the comparison results. By using the MERGE command, you can handle the prevention of duplicate records in a more controlled and efficient manner. It allows you to synchronize and reconcile data from different sources while avoiding duplication and ensuring data integrity. Therefore, option C, MERGE, is the correct command to use when writing data into a Delta table while avoiding the writing of duplicate records. upvoted 3 times ... softthinkers 2 years, 5 months ago Answer is C. AS DROP is used to remove a table or database IGNORE is used to skip errors while executing a query. INSERT will add new records but will not avoid duplication so Merge is right answer upvoted 2 times ... Varma_Saraswathula 2 years, 6 months ago Ans - C https://docs.databricks.com/sql/language-manual/delta-merge-into.html upvoted 2 times ... naxacod574 2 years, 6 months ago Option C upvoted 1 times ... XiltroX 2 years, 6 months ago Selected Answer: D Wrong answer. The correct answer is D. upvoted 1 times Oleskie 2 years, 6 months ago 'C' is a correct answer. https://docs.databricks.com/sql/language-manual/delta-merge-into.html upvoted 4 times XiltroX 2 years, 6 months ago Thanks for the clarification upvoted 1 times ... ... ... Load full discussion...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 18 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 18
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data analyst has a series of queries in a SQL program. The data analyst wants this program to run every day. They only want the final query in the program to run on Sundays. They ask for help from the data engineering team to complete this task.Which of the following approaches could be used by the data engineering team to complete this task? 
Suggested Answer: B 🗳️ 

A. They could submit a feature request with Databricks to add this functionality.

B. They could wrap the queries using PySpark and use Python’s control flow system to determine when to run the final query.

C. They could only run the entire program on Sundays.

D. They could automatically restrict access to the source table in the final query so that it is only accessible on Sundays.

E. They could redesign the data model to separate the data used in the final query into a new table.

**Answer: B**

**Timestamp: April 4, 2023, 1:49 a.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/105035-exam-certified-data-engineer-associate-topic-1-question-18/)

Comments: Atnafu Highly Voted 2 years, 3 months ago B The answer is B. Option A: Submitting a feature request with Databricks to add this functionality is not a feasible solution because it would require Databricks to implement new functionality. Option C: Only running the entire program on Sundays would be inconvenient for the data analyst because they would have to remember to run the program on Sundays. Option D: Automatically restricting access to the source table in the final query so that it is only accessible on Sundays would be difficult to implement and would not be a reliable solution. Option E: Redesigning the data model to separate the data used in the final query into a new table would be a major undertaking and would not be a feasible solution for this specific problem. Therefore, the only feasible solution to the problem is to wrap the queries using PySpark and use Python's control flow system to determine when to run the final query. python code upvoted 12 times vibha2119 1 year, 5 months ago Also to add for option C is: the requirement says: data analysts wants to run the sql program every day, but only the final query to run on sundays. So the option c violates the requirements upvoted 2 times ... ... 806e7d2 Highly Voted 11 months, 1 week ago Selected Answer: B Wrapping the SQL program in PySpark allows the data engineering team to leverage Python’s control flow (e.g., if statements) to determine when the final query should execute. For example: The PySpark program can check the current day using Python's datetime module. If the current day is Sunday, it will execute all queries, including the final one. If it’s not Sunday, the program will skip the final query. This approach ensures flexibility and allows precise control over which queries run on which days, meeting the data analyst's requirements. upvoted 5 times ... SoumyaHK Most Recent 6 months ago Selected Answer: B The response is B upvoted 1 times ... 80370eb 1 year, 2 months ago Selected Answer: B B. They could wrap the queries using PySpark and use Python’s control flow system to determine when to run the final query. This approach involves using PySpark to control the execution flow based on the day of the week, allowing the final query to execute conditionally while the other queries run daily. upvoted 1 times ... SerGrey 1 year, 9 months ago Selected Answer: B Correct answer is B upvoted 1 times ... VijayKula 2 years ago Selected Answer: B B is correct upvoted 1 times ... KalavathiP 2 years, 1 month ago Selected Answer: B B is correct ans upvoted 1 times ... d_b47 2 years, 1 month ago Selected Answer: B B is correct. upvoted 1 times ... mehroosali 2 years, 3 months ago Selected Answer: B B is correct upvoted 1 times ... [Removed] 2 years, 4 months ago Selected Answer: B B is correct upvoted 1 times ... XiltroX 2 years, 6 months ago Selected Answer: B B is the correct answer upvoted 1 times ... mimzzz 2 years, 6 months ago i think the answer is correct upvoted 1 times ... knivesz 2 years, 6 months ago Selected Answer: B Respuesta Correcta es B upvoted 1 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 19 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 19
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer runs a statement every day to copy the previous day’s sales into the table transactions. Each day’s sales are in their own file in the location "/transactions/raw".Today, the data engineer runs the following command to complete this task:After running the command today, the data engineer notices that the number of records in table transactions has not changed.Which of the following describes why the statement might not have copied any new records into the table? 
Suggested Answer: C 🗳️ 

A. The format of the files to be copied were not included with the FORMAT_OPTIONS keyword.

B. The names of the files to be copied were not included with the FILES keyword.

C. The previous day’s file has already been copied into the table.

D. The PARQUET file format does not support COPY INTO.

E. The COPY INTO statement requires the table to be refreshed to view the copied rows.

**Answer: C**

**Timestamp: April 4, 2023, 2:03 a.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/105038-exam-certified-data-engineer-associate-topic-1-question-19/)

Comments: Nika12 Highly Voted 1 year, 9 months ago Selected Answer: C Just got 100% on the test. C was correct. upvoted 8 times ... ezeik Highly Voted 2 years, 1 month ago Selected Answer: E E is the correct answer, because immediately after using copy into you might query the cashed version of the table. upvoted 5 times ... SoumyaHK Most Recent 6 months ago Selected Answer: C The response is C upvoted 1 times ... 806e7d2 11 months, 1 week ago Selected Answer: C In Databricks, the COPY INTO command is designed to prevent duplicate data ingestion. When files are copied into a table, Databricks keeps track of the files that have already been processed using a file log. If a file has already been copied, subsequent runs of the COPY INTO command will skip that file to avoid duplication. upvoted 4 times ... SerGrey 1 year, 9 months ago Selected Answer: C Correct answer is C upvoted 2 times ... Garyn 1 year, 10 months ago Selected Answer: C C. The previous day’s file has already been copied into the table. The COPY INTO statement is generally used to copy data from files or a location into a table. If the data engineer runs this statement daily to copy the previous day’s sales into the "transactions" table and the number of records hasn't changed after today's execution, it's possible that the data from today's file might not have differed from the data already present in the table. If the files in the "/transactions/raw" location are expected to contain distinct data for each day and the number of records in the table remains the same, it implies that the data engineer might have already copied today's data previously, or today's data was identical to the data already present in the table. Options A, B, D, and E don't accurately explain why the statement might not have copied new records into the table based on the provided scenario. upvoted 4 times ... awofalus 1 year, 11 months ago Selected Answer: C C is correct upvoted 2 times ... kishanu 2 years ago If the table "transaction" is an external table, then option E, if its internal C should suffice. upvoted 1 times ... DavidRou 2 years ago Selected Answer: C COPY INTO statement does skip already copied rows. upvoted 1 times ... KalavathiP 2 years, 1 month ago Selected Answer: C C is correct ans upvoted 1 times ... AndreFR 2 years, 2 months ago Selected Answer: C https://docs.databricks.com/en/ingestion/copy-into/index.html The COPY INTO SQL command lets you load data from a file location into a Delta table. This is a re-triable and idempotent operation; files in the source location that have already been loaded are skipped. if there are no new records, the only consistent choice is C no new files were loaded because already loaded files were skipped. upvoted 1 times ... Atnafu 2 years, 3 months ago C The COPY INTO statement copies the data from the specified files into the target table. If the previous day's file has already been copied into the table, then the COPY INTO statement will not copy any new records into the table. upvoted 1 times ... junction 2 years, 5 months ago Selected Answer: C COPY INTO Loads data from a file location into a Delta table. This is a retriable and idempotent operation—files in the source location that have already been loaded are skipped. upvoted 1 times ... testdb 2 years, 5 months ago Selected Answer: B Answer: B FILES = ('f1.json', 'f2.json', 'f3.json', 'f4.json', 'f5.json') https://docs.databricks.com/ingestion/copy-into/examples.html upvoted 1 times [Removed] 2 years, 5 months ago The correct answer is letter C. The use of specific files names with keyword "FILES" is optional as the syntax of COPY INTO declares: [ FILES = ( file_name [, ...] ) | PATTERN = glob_pattern ] When keyword FILES is not used in the statement all files of the directory is used once (because this operation is idempotent). upvoted 2 times ... ... Varma_Saraswathula 2 years, 6 months ago C- https://docs.databricks.com/ingestion/copy-into/tutorial-notebook.html Because this action is idempotent, you can run it multiple times but data will only be loaded once. upvoted 1 times ... XiltroX 2 years, 6 months ago Selected Answer: C Option C is the correct answer. upvoted 3 times ... mimzzz 2 years, 6 months ago i am not sure whether C is the correct answer, but A is definitely not right upvoted 1 times ... Load full discussion...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 23 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 23
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer is attempting to drop a Spark SQL table my_table. The data engineer wants to delete all table metadata and data.They run the following command:DROP TABLE IF EXISTS my_table -While the object no longer appears when they run SHOW TABLES, the data files still exist.Which of the following describes why the data files still exist and the metadata files were deleted? 
Suggested Answer: C 🗳️ 

A. The table’s data was larger than 10 GB

B. The table’s data was smaller than 10 GB

C. The table was external

D. The table did not have a location

E. The table was managed

**Answer: C**

**Timestamp: April 1, 2023, 5:56 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/104761-exam-certified-data-engineer-associate-topic-1-question-23/)

Comments: SoumyaHK 6 months ago Selected Answer: C The response is C upvoted 1 times ... 80370eb 1 year, 2 months ago Selected Answer: C C. The table was external When dropping an external table in Spark SQL, only the metadata is removed. The actual data files remain in their original location because they are not managed by Spark but by the external source. upvoted 3 times ... SerGrey 1 year, 9 months ago Selected Answer: C C is correct upvoted 1 times ... hemanthgvsk 2 years ago THE QUESTION SHOULD BE "Which of the following describes why the metadata files still exist and the data files were deleted?" upvoted 1 times ... vctrhugo 2 years, 1 month ago Selected Answer: C C. The table was external The reason why the data files still exist while the metadata files were deleted is because the table was external. When a table is external in Spark SQL (or in other database systems), it means that the table metadata (such as schema information and table structure) is managed externally, and Spark SQL assumes that the data is managed and maintained outside of the system. Therefore, when you execute a DROP TABLE statement for an external table, it removes only the table metadata from the catalog, leaving the data files intact. On the other hand, for managed tables (option E), Spark SQL manages both the metadata and the data files. When you drop a managed table, it deletes both the metadata and the associated data files, resulting in a complete removal of the table. upvoted 4 times ... surrabhi_4 2 years, 6 months ago Selected Answer: C Option C upvoted 2 times ... XiltroX 2 years, 6 months ago Selected Answer: C C is the correct answer. For external tables, you need to go to the specific location using DESCRIBE EXTERNAL TABLE command and delete all files. upvoted 2 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 24 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 24
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer wants to create a data entity from a couple of tables. The data entity must be used by other data engineers in other sessions. It also must be saved to a physical location.Which of the following data entities should the data engineer create? 
Suggested Answer: E 🗳️ 

A. Database

B. Function

C. View

D. Temporary view

E. Table

**Answer: E**

**Timestamp: April 1, 2023, 6 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/104762-exam-certified-data-engineer-associate-topic-1-question-24/)

Comments: Bob123456 Highly Voted 2 years, 5 months ago Questions says : 1. The data entity must be used by other data engineers in other sessions. 2. It also must be saved to a physical location. Here View doesn't store data in physical location , from the options only table stores data in physical location So answer should be 'E' which is Table. upvoted 36 times ... Nika12 Highly Voted 1 year, 9 months ago Selected Answer: E Just got 100% in the exam. Table was a correct answer. upvoted 10 times ADVIT 1 year, 9 months ago Wow! Congratz! upvoted 1 times ... ... Hink Most Recent 1 week, 5 days ago Selected Answer: E E-table since we is not saved physical, it is based on query from other table/s. upvoted 1 times ... SoumyaHK 6 months ago Selected Answer: E The response is E upvoted 1 times ... 80370eb 1 year, 2 months ago Selected Answer: E E. Table Creating a table ensures that the data entity is saved to a physical location and can be used by other data engineers in different sessions. Tables persist data and metadata, making them suitable for long-term storage and sharing across sessions. upvoted 4 times ... 3fbc31b 1 year, 3 months ago Selected Answer: E The correct answer is "E". A view does not save to a physical location; only caching a SELECT statement. upvoted 1 times ... benni_ale 1 year, 6 months ago Selected Answer: E physical location means table upvoted 2 times ... agAshish 1 year, 9 months ago E. as view doesnt has any location upvoted 1 times ... SerGrey 1 year, 9 months ago Selected Answer: E E is correct upvoted 1 times ... Garyn 1 year, 10 months ago Selected Answer: E E. Table Usage by Other Sessions: Tables in a database are persistent data structures that can be accessed by multiple users and sessions concurrently. Saved to a Physical Location: Tables store data physically in a structured manner on disk or in a storage system, making them suitable for long-term storage. Usage by Other Data Engineers: Other data engineers can query, access, and work with the data within the table, making it a feasible choice for shared access among multiple users or sessions. While other entities like views or temporary views can provide different ways to represent or filter data, a table fits the criteria best when the data engineer requires a persistent physical storage entity accessible by other sessions and users for data manipulation, retrieval, and storage. upvoted 1 times ... RafaelCFC 1 year, 10 months ago Selected Answer: C I think the key to the answer is that it refers to the Data Entinty, and not to the data itself, when it mentions "the Data Entity must be used by other Data Engineers", and "It must be saved to a physical location". From this PoV, both C and E would be correct, however, creating a new table would incur in processing to a static state the relationship from "a couple of tables". While this make sense to many use cases, this would require either a Workflow or a DLT to make it work, which goes over the requested scope. C is the best answer for the requested scenario. upvoted 4 times ... Vikram1710 1 year, 11 months ago Key point to remember during answering this question: " It also must be saved to a physical location" So answer should be 'E' which is Table. upvoted 2 times ... rbeeraka 1 year, 11 months ago C is the right answer. View is a data entity and its definition is physically saved so other users can consume view upvoted 1 times ... Huroye 1 year, 11 months ago The correct answer is E because it has to be physically saved. View is in memory. upvoted 1 times ... awofalus 1 year, 11 months ago Selected Answer: E Correct : E upvoted 1 times ... vctrhugo 2 years, 1 month ago Selected Answer: E E. Table To create a data entity that can be used by other data engineers in other sessions and must be saved to a physical location, you should create a table. Tables in a database are physical storage structures that hold data, and they can be accessed and shared by multiple users and sessions. By creating a table, you provide a permanent and structured storage location for the data entity that can be used across different sessions and by other users as needed. Options like databases (A) can be used to organize tables, views (C) can provide virtual representations of data, and temporary views (D) are temporary in nature and don't save data to a physical location. Functions (B) are typically used for processing data or performing calculations, not for storing data. upvoted 2 times ... [Removed] 2 years, 2 months ago Selected Answer: E View does not have a physical location so answer has to be E upvoted 1 times ... Load full discussion...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 25 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 25
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer is maintaining a data pipeline. Upon data ingestion, the data engineer notices that the source data is starting to have a lower level of quality. The data engineer would like to automate the process of monitoring the quality level.Which of the following tools can the data engineer use to solve this problem? 
Suggested Answer: D 🗳️ 

A. Unity Catalog

B. Data Explorer

C. Delta Lake

D. Delta Live Tables

E. Auto Loader

**Answer: D**

**Timestamp: April 1, 2023, 6:05 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/104764-exam-certified-data-engineer-associate-topic-1-question-25/)

Comments: XiltroX Highly Voted 2 years, 6 months ago Selected Answer: D The answer is incorrect. The correct answer is Delta Live Tables or (C) https://docs.databricks.com/delta-live-tables/expectations.html upvoted 17 times mimzzz 2 years, 4 months ago upon reading this i think you are right upvoted 2 times ... ... DQCR Highly Voted 2 years, 1 month ago Selected Answer: D Delta Live Tables is a declarative framework for building reliable, maintainable, and testable data processing pipelines. You define the transformations to perform on your data and Delta Live Tables manages task orchestration, cluster management, monitoring, data quality, and error handling. Quality is explicitly mentioned in the definition. upvoted 11 times ... SoumyaHK Most Recent 6 months ago Selected Answer: D The response is D upvoted 1 times ... 806e7d2 11 months, 1 week ago Selected Answer: D Delta Live Tables (DLT) is designed for building and managing data pipelines with built-in support for data quality monitoring and enforcement. It allows data engineers to define expectations (data quality rules) and automatically track if the ingested data meets these expectations. If data fails the specified rules, DLT can log the errors and either reject or quarantine the data, depending on the configured behavior. upvoted 4 times ... 80370eb 1 year, 2 months ago Selected Answer: D D. Delta Live Tables Delta Live Tables provides features for automating data quality monitoring and ensuring that the data in the pipeline meets certain quality standards. It allows you to define expectations and monitor data quality as part of the data pipeline. upvoted 2 times ... benni_ale 1 year, 6 months ago Selected Answer: D delta live table upvoted 1 times ... SerGrey 1 year, 9 months ago Selected Answer: D Correct is D upvoted 1 times ... awofalus 1 year, 11 months ago Selected Answer: D Correct: D upvoted 1 times ... awofalus 1 year, 11 months ago Selected Answer: D D is correct upvoted 1 times ... vctrhugo 2 years, 1 month ago Selected Answer: D D. Delta Live Tables Delta Live Tables is a tool provided by Databricks that can help data engineers automate the monitoring of data quality. It is designed for managing data pipelines, monitoring data quality, and automating workflows. With Delta Live Tables, you can set up data quality checks and alerts to detect issues and anomalies in your data as it is ingested and processed in real-time. It provides a way to ensure that the data quality meets your desired standards and can trigger actions or notifications when issues are detected. While the other tools mentioned may have their own purposes in a data engineering environment, Delta Live Tables is specifically designed for data quality monitoring and automation within the Databricks ecosystem. upvoted 3 times ... Atnafu 2 years, 3 months ago D Delta Live Tables. Delta Live Tables is a tool that can be used to automate the process of monitoring the quality level of data in a data pipeline. Delta Live Tables provides a number of features that can be used to monitor data quality, including: Data lineage: Delta Live Tables tracks the lineage of data as it flows through the data pipeline. This allows the data engineer to see where the data came from and how it has been transformed. Data quality checks: Delta Live Tables allows the data engineer to define data quality checks that can be run on the data as it is ingested. These checks can be used to identify data that is not meeting the expected quality standards. Alerts: Delta Live Tables can be configured to send alerts when data quality checks fail. This allows the data engineer to be notified of potential problems with the data pipeline. upvoted 1 times ... Majjjj 2 years, 5 months ago Selected Answer: B The data engineer can use the Data Explorer tool to monitor the quality level of the ingested data. Data Explorer is a feature of Databricks that provides data profiling and data quality metrics to monitor the health of data pipelines. upvoted 1 times Majjjj 2 years, 5 months ago After reading docs and more investigation I think in the terms of managing the data quality D would be better answer upvoted 3 times ... ... 4be8126 2 years, 6 months ago Selected Answer: B B. Data Explorer can be used to monitor the quality level of data. It provides an interactive interface to analyze the data and define quality rules to identify issues. Data Explorer also offers automated validation rules that can be used to monitor data quality over time. upvoted 1 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 31 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 31
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer has configured a Structured Streaming job to read from a table, manipulate the data, and then perform a streaming write into a new table.The cade block used by the data engineer is below:If the data engineer only wants the query to execute a micro-batch to process data every 5 seconds, which of the following lines of code should the data engineer use to fill in the blank? 
Suggested Answer: D 🗳️ 

A. trigger("5 seconds")

B. trigger()

C. trigger(once="5 seconds")

D. trigger(processingTime="5 seconds")

E. trigger(continuous="5 seconds")

**Answer: D**

**Timestamp: April 2, 2023, 2:14 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/104854-exam-certified-data-engineer-associate-topic-1-question-31/)

Comments: 4be8126 Highly Voted 2 years, 6 months ago Selected Answer: D The correct line of code to fill in the blank to execute a micro-batch to process data every 5 seconds is: D. trigger(processingTime="5 seconds") Option A ("trigger("5 seconds")") would not work because it does not specify that the trigger should be a processing time trigger, which is necessary to trigger a micro-batch processing at regular intervals. Option B ("trigger()") would not work because it would use the default trigger, which is not a processing time trigger. Option C ("trigger(once="5 seconds")") would not work because it would only trigger the query once, not at regular intervals. Option E ("trigger(continuous="5 seconds")") would not work because it would trigger the query to run continuously, without any pauses in between, which is not what the data engineer wants. upvoted 7 times azurean 5 months ago In Databricks Runtime 11.3 LTS and above, the Trigger.Once setting is deprecated. Databricks recommends you use Trigger.AvailableNow for all incremental batch processing workloads. upvoted 1 times ... ... XiltroX Highly Voted 2 years, 6 months ago D is the correct answer upvoted 5 times ... Raghu_Dasara Most Recent 1 year ago D is correct answer ProcessingTime https://learn.microsoft.com/en-us/azure/databricks/structured-streaming/triggers Continues Processing : upvoted 1 times ... benni_ale 1 year, 6 months ago Selected Answer: D correct syntax is D upvoted 1 times ... awofalus 1 year, 11 months ago Selected Answer: D Correct: D upvoted 1 times ... vctrhugo 2 years, 1 month ago Selected Answer: D # ProcessingTime trigger with two-seconds micro-batch interval df.writeStream \ .format("console") \ .trigger(processingTime='2 seconds') \ .start() https://spark.apache.org/docs/latest/structured-streaming-programming-guide.html#triggers upvoted 2 times ... AndreFR 2 years, 2 months ago Selected Answer: D https://spark.apache.org/docs/latest/structured-streaming-programming-guide.html#triggers upvoted 1 times ... Atnafu 2 years, 3 months ago D val query = sourceTable .writeStream .format("delta") .outputMode("append") .trigger(Trigger.ProcessingTime("5 seconds")) .start(destinationTable) upvoted 1 times vctrhugo 2 years, 1 month ago This is Scala example. Exam should be 100% on Python. upvoted 3 times ... ... rafahb 2 years, 6 months ago Selected Answer: D D os correct upvoted 2 times ... surrabhi_4 2 years, 6 months ago Selected Answer: D Option D upvoted 3 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 32 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 32
Topic #: 1

[All Certified Data Engineer Associate Questions]

A dataset has been defined using Delta Live Tables and includes an expectations clause:CONSTRAINT valid_timestamp EXPECT (timestamp > '2020-01-01') ON VIOLATION DROP ROWWhat is the expected behavior when a batch of data containing data that violates these constraints is processed? 
Suggested Answer: C 🗳️ 

A. Records that violate the expectation are dropped from the target dataset and loaded into a quarantine table.

B. Records that violate the expectation are added to the target dataset and flagged as invalid in a field added to the target dataset.

C. Records that violate the expectation are dropped from the target dataset and recorded as invalid in the event log.

D. Records that violate the expectation are added to the target dataset and recorded as invalid in the event log.

E. Records that violate the expectation cause the job to fail.

**Answer: C**

**Timestamp: April 2, 2023, 2:18 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/104855-exam-certified-data-engineer-associate-topic-1-question-32/)

Comments: XiltroX Highly Voted 2 years, 6 months ago Selected Answer: C I am simply appalled by the number of wrong answers in this series of questions. The statement in the question already says "ON VIOLATE DROP ROW" which means if condition is violated, there will be nothing saved to quarantine table and a log of all invalid entries will be recoded. All invalid data that doesn't meet condition will be dropped. So C is the correct answer. upvoted 19 times ... rafahb Highly Voted 2 years, 6 months ago Selected Answer: C C is correct upvoted 6 times ... 806e7d2 Most Recent 11 months, 1 week ago Selected Answer: C In Delta Live Tables, expectations are used to enforce data quality rules. In this specific case, the expectation is that the timestamp column should be greater than '2020-01-01'. When a batch of data is processed, if a record violates this expectation, the following happens: Drop the violating rows: The rows that don't meet the expectation (timestamp > '2020-01-01') will be dropped from the dataset. Logging of the violation: The fact that these rows were dropped due to the violation will be recorded in the event log for audit and tracking purposes. This ensures that only valid data (according to the expectation) is loaded into the final dataset, while invalid data is tracked. upvoted 3 times ... Stefan94 1 year, 1 month ago Selected Answer: C 100% C upvoted 1 times ... gdc.moser 1 year, 2 months ago Selected Answer: C C is the correct answer. upvoted 1 times ... 3fbc31b 1 year, 3 months ago Selected Answer: C C is the correct answer. The DROP ROW clause will cause them to NOT be added to the destination; only marked in the log. upvoted 1 times ... benni_ale 1 year, 6 months ago Selected Answer: C C is correct upvoted 1 times ... SerGrey 1 year, 9 months ago Selected Answer: C C is correct upvoted 1 times ... Garyn 1 year, 10 months ago Selected Answer: C C. Records that violate the expectation are dropped from the target dataset and recorded as invalid in the event log. Explanation: The defined expectation specifies that if the timestamp is not greater than '2020-01-01', the row will be considered in violation of the constraint. The ON VIOLATION DROP ROW clause states that rows that violate the constraint will be dropped from the target dataset. Additionally, the expectation clause will log these violations in the event log, indicating which records did not meet the specified constraint criteria. This behavior ensures that the rows failing the defined constraint are not included in the target dataset and are logged as invalid in the event log for reference or further investigation, maintaining data integrity within the dataset based on the specified constraints. upvoted 3 times ... Huroye 1 year, 11 months ago who choses these answers? The correct answer is C. The record is dropped. This is not about the default behavior. It is explicit. upvoted 1 times ... DavidRou 1 year, 12 months ago Selected Answer: C Right answer: C Invalid rows will be dropped as requested by the constraint and flagged as such in log files. If you need a quarantine table, you'll have to write more code. upvoted 1 times ... vctrhugo 2 years, 1 month ago Selected Answer: C C. Records that violate the expectation are dropped from the target dataset and recorded as invalid in the event log. With the defined constraint and expectation clause, when a batch of data is processed, any records that violate the expectation (in this case, where the timestamp is not greater than '2020-01-01') will be dropped from the target dataset. These dropped records will also be recorded as invalid in the event log, allowing for auditing and tracking of the data quality issues without causing the entire job to fail. upvoted 2 times ... AndreFR 2 years, 2 months ago Selected Answer: C https://docs.databricks.com/en/delta-live-tables/expectations.html upvoted 2 times ... Atnafu 2 years, 3 months ago C When a batch of data is processed in Delta Live Tables and contains data that violates the defined expectations or constraints, the expected behavior is that the records violating the expectation are dropped from the target dataset. Additionally, these violated records are recorded as invalid in the event log. upvoted 1 times ... mehroosali 2 years, 3 months ago Selected Answer: C C is correct upvoted 1 times ... SHINGX 2 years, 6 months ago B is correct. This question is number 35 on the practice test on databricks patner academy. https://partner-academy.databricks.com/ correct answer is "Records that violate the expectation are added to the target dataset and recorded as invalid in the event log" upvoted 2 times SHINGX 2 years, 6 months ago Sorry, D upvoted 1 times SHINGX 2 years, 6 months ago I was wrong, the ON VIOLATION DROP ROW makes C the correct answer upvoted 5 times ... ... ... surrabhi_4 2 years, 6 months ago Selected Answer: C option C upvoted 4 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 33 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 33
Topic #: 1

[All Certified Data Engineer Associate Questions]

Which of the following describes when to use the CREATE STREAMING LIVE TABLE (formerly CREATE INCREMENTAL LIVE TABLE) syntax over the CREATE LIVE TABLE syntax when creating Delta Live Tables (DLT) tables using SQL? 
Suggested Answer: B 🗳️ 

A. CREATE STREAMING LIVE TABLE should be used when the subsequent step in the DLT pipeline is static.

B. CREATE STREAMING LIVE TABLE should be used when data needs to be processed incrementally.

C. CREATE STREAMING LIVE TABLE is redundant for DLT and it does not need to be used.

D. CREATE STREAMING LIVE TABLE should be used when data needs to be processed through complicated aggregations.

E. CREATE STREAMING LIVE TABLE should be used when the previous step in the DLT pipeline is static.

**Answer: B**

**Timestamp: April 2, 2023, 2:19 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/104856-exam-certified-data-engineer-associate-topic-1-question-33/)

Comments: 4be8126 Highly Voted 2 years, 6 months ago Selected Answer: B B. CREATE STREAMING LIVE TABLE should be used when data needs to be processed incrementally. The CREATE STREAMING LIVE TABLE syntax is used to create tables that read data incrementally, while the CREATE LIVE TABLE syntax is used to create tables that read data in batch mode. Delta Live Tables support both streaming and batch modes of processing data. When the data is streamed and needs to be processed incrementally, CREATE STREAMING LIVE TABLE should be used. upvoted 9 times ... XiltroX Highly Voted 2 years, 6 months ago Selected Answer: B B is the correct answer. upvoted 6 times ... ajay1709 Most Recent 12 months ago B. CREATE STREAMING LIVE TABLE should be used when data needs to be processed Streaming is used for incremental data. upvoted 1 times ... 80370eb 1 year, 2 months ago Selected Answer: B B. CREATE STREAMING LIVE TABLE should be used when data needs to be processed incrementally. This syntax is used to define a Delta Live Table that processes data incrementally as new data arrives, which is essential for handling streaming data or large datasets that need to be processed in chunks rather than all at once. upvoted 2 times ... SerGrey 1 year, 9 months ago Selected Answer: B B is correct upvoted 1 times ... awofalus 1 year, 11 months ago Selected Answer: B B is correct upvoted 1 times ... vctrhugo 2 years, 1 month ago Selected Answer: B B. CREATE STREAMING LIVE TABLE should be used when data needs to be processed incrementally. The CREATE STREAMING LIVE TABLE syntax is used when you want to create Delta Live Tables (DLT) tables that are designed for processing data incrementally. This is typically used when your data pipeline involves streaming or incremental data updates, and you want the table to stay up to date as new data arrives. It allows you to define tables that can handle data changes incrementally without the need for full table refreshes. So, option B correctly describes when to use CREATE STREAMING LIVE TABLE over CREATE LIVE TABLE in the context of Delta Live Tables. upvoted 3 times ... ZSun 2 years, 4 months ago This is old version question, currently, Databricks only have Streaming Table (Create Live Table). The previous Streaming live table and Live table already combined. upvoted 2 times lgkofficialwork 2 years, 4 months ago is this dump valid for v3? upvoted 3 times ... ... surrabhi_4 2 years, 6 months ago Selected Answer: B option B upvoted 4 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 36 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 36
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer has three tables in a Delta Live Tables (DLT) pipeline. They have configured the pipeline to drop invalid records at each table. They notice that some data is being dropped due to quality concerns at some point in the DLT pipeline. They would like to determine at which table in their pipeline the data is being dropped.Which of the following approaches can the data engineer take to identify the table that is dropping the records? 
Suggested Answer: D 🗳️ 

A. They can set up separate expectations for each table when developing their DLT pipeline.

B. They cannot determine which table is dropping the records.

C. They can set up DLT to notify them via email when records are dropped.

D. They can navigate to the DLT pipeline page, click on each table, and view the data quality statistics.

E. They can navigate to the DLT pipeline page, click on the “Error” button, and review the present errors.

**Answer: D**

**Timestamp: April 5, 2023, 8:57 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/105325-exam-certified-data-engineer-associate-topic-1-question-36/)

Comments: vctrhugo Highly Voted 2 years, 1 month ago Selected Answer: D D. They can navigate to the DLT pipeline page, click on each table, and view the data quality statistics. To identify the table in a Delta Live Tables (DLT) pipeline where data is being dropped due to quality concerns, the data engineer can navigate to the DLT pipeline page, click on each table in the pipeline, and view the data quality statistics. These statistics often include information about records dropped, violations of expectations, and other data quality metrics. By examining the data quality statistics for each table in the pipeline, the data engineer can determine at which table the data is being dropped. upvoted 17 times ... CID2024 Most Recent 1 year, 1 month ago The correct answer is: D. They can navigate to the DLT pipeline page, click on each table, and view the data quality statistics. Delta Live Tables provides detailed data quality statistics for each table in the pipeline. By navigating to the DLT pipeline page and clicking on each table, the data engineer can view these statistics and determine at which table the records are being dropped due to quality concerns. This allows them to identify and address the specific issues causing the data to be dropped. upvoted 1 times ... 3fbc31b 1 year, 3 months ago Selected Answer: D Correct answer is "D". upvoted 1 times ... benni_ale 1 year, 6 months ago Selected Answer: D I would say D but I have never really tested it, still other solutions smell wrong upvoted 1 times ... agAshish 1 year, 9 months ago D is correct By clicking on each table in the DLT pipeline page, the data engineer may be able to access data quality statistics, error logs, or other information related to dropped records. This can help them pinpoint at which table in the pipeline the data is being dropped. upvoted 1 times ... Diewrine 1 year, 10 months ago Selected Answer: D E is for when an error occur. But pipeline is defined to drop some records that will not result on error upvoted 2 times ... awofalus 1 year, 11 months ago Selected Answer: D D is correct upvoted 1 times ... Atnafu 2 years, 3 months ago E When records are dropped due to quality concerns in a DLT pipeline, the errors are logged in the event log. The data engineer can navigate to the DLT pipeline page and click on the “Error” button to view the present errors. The errors will show the table where the records were dropped. Option A: Setting up separate expectations for each table will not help the data engineer determine which table is dropping the records. Option B: The data engineer cannot determine which table is dropping the records without looking at the event log. Option C: Setting up DLT to notify the data engineer via email when records are dropped will not help the data engineer determine which table is dropping the records. Option D: Viewing the data quality statistics for each table will not help the data engineer determine which table is dropping the records. upvoted 2 times DavidRou 1 year, 12 months ago Don't you have to select a table generated in a single step of the pipeline to access the errors through the buttton though? Probably D is the right one here upvoted 1 times ... ... prasioso 2 years, 5 months ago Selected Answer: D Think answer is D. The pipeline is configured to drop invalid records, i.e. a SQL equivalent query with a ON VIOLATION DROP ROW clause. This will not result in a failed pipeline execution because there are no errors. Instead, you'd have to go to each table and review the quality charactistics. upvoted 4 times Atnafu 2 years, 3 months ago Option D is incorrect because viewing the data quality statistics for each table will not help the data engineer identify which table is dropping the records. The data quality statistics will show the overall quality of the data in each table, but they will not show which table is dropping the records. For example, if the data quality statistics for a table show that 10% of the records are invalid, this does not mean that 10% of the records are being dropped. The invalid records could be being updated, inserted, or deleted. upvoted 2 times peadar_pa 12 months ago No D is correct for the reasons stated by everyone else upvoted 1 times ... ... ... [Removed] 2 years, 6 months ago Is this for v2 or v3 upvoted 3 times ... XiltroX 2 years, 6 months ago Selected Answer: D The correct answer is D upvoted 4 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 37 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 37
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer has a single-task Job that runs each morning before they begin working. After identifying an upstream data issue, they need to set up another task to run a new notebook prior to the original task.Which of the following approaches can the data engineer use to set up the new task? 
Suggested Answer: B 🗳️ 

A. They can clone the existing task in the existing Job and update it to run the new notebook.

B. They can create a new task in the existing Job and then add it as a dependency of the original task.

C. They can create a new task in the existing Job and then add the original task as a dependency of the new task.

D. They can create a new job from scratch and add both tasks to run concurrently.

E. They can clone the existing task to a new Job and then edit it to run the new notebook.

**Answer: B**

**Timestamp: April 5, 2023, 1:06 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/105268-exam-certified-data-engineer-associate-topic-1-question-37/)

Comments: Redwings538 Highly Voted 2 years, 6 months ago Selected Answer: B It seems there is some confusion on what dependency means in this case. Option B is correct because adding the new task as a dependency of the original task means that the new task will run BEFORE the original task, which is the goal defined in the question. upvoted 25 times loyik65509 7 months, 1 week ago This means the original task must run first before the new task starts. The original task will wait for the new task. This is the wrong order because we need the new task to run first to fix upstream data issues before the original task executes. upvoted 2 times ... ... Data_4ever Highly Voted 2 years, 6 months ago Selected Answer: B B is the right answer. upvoted 15 times ... abbf4e9 Most Recent 1 week, 3 days ago Selected Answer: C Correct Answer: C. They can create a new task in the existing Job and then add the original task as a dependency of the new task. Explanation: In Databricks Jobs, tasks can have dependencies that determine the execution order. If you want a new task to run before an existing one, ➜ You make the existing task depend on the new task. Scenario: Existing job has Task A (runs a notebook each morning). You want to add Task B (a new notebook) that runs before Task A. To achieve this: Create Task B in the same job. In Task A’s settings, specify that Task A depends on Task B. This ensures: Task B runs first (upstream) Task A runs after (downstream) upvoted 1 times ... Billybob0604 7 months, 1 week ago Selected Answer: C The new task should run before the original task, meaning the original task must depend on the new task upvoted 3 times ... pint414 8 months, 1 week ago Selected Answer: B B as the new task runs first upvoted 1 times ... avidlearner 8 months, 1 week ago Selected Answer: C I think the confusion here is because it mentions "as a dependency" which to my opinion means following. if we go by that wording C is the correct answer because we want the original task to be run after the new task. upvoted 1 times Alex_W 3 months, 3 weeks ago Correct answer is B. In Databricks Jobs, you can add multiple tasks and define dependencies so that one task runs only after its dependencies have completed. By creating a new task for the upstream notebook and specifying it as a dependency for the original task, you guarantee the desired execution order: the new task runs first, followed by the original task. upvoted 1 times ... ... Usaha1 9 months, 3 weeks ago Selected Answer: B B because when we add a task which is supposed to run after previous task then dependency ("depends on") gets added to the second job, not the first job. upvoted 1 times ... rohitrc8521 9 months, 3 weeks ago Selected Answer: C Answer is C, folks Please pay solid attention to the wording. They deliberately have constructed the wordings of option B and C to confuse the audience. upvoted 2 times Alex_W 3 months, 3 weeks ago Nope. Correct answer is B. This method ensures that the new notebook runs before the original task. In Databricks Jobs, you can add multiple tasks and define dependencies so that one task runs only after its dependencies have completed. By creating a new task for the upstream notebook and specifying it as a dependency for the original task, you guarantee the desired execution order: the new task runs first, followed by the original task. upvoted 1 times ... ... danishanis 9 months, 3 weeks ago Selected Answer: C I think the correct answer should be C and not B. Adding the new task as a dependency of the original task would mean that the original task runs first and then the new task runs. This is the opposite of what is desired in the question. upvoted 3 times Alex_W 3 months, 3 weeks ago No, it is opposite. upvoted 1 times ... ... brconejeros 10 months ago Selected Answer: C Basically because on the sentence we have a prior: "they need to set up another task to run a new notebook prior to the original task.". So, the correct answer is C upvoted 1 times Alex_W 3 months, 3 weeks ago Correct answer is B. upvoted 1 times ... ... Rifrif 10 months, 1 week ago Selected Answer: B the answer B as it need runs before start working upvoted 1 times ... sam_chalvet 10 months, 1 week ago Selected Answer: B B - Event without know anything about Databricks, answer B is how I would want to be able to handle this scenario, it makes the most sense. upvoted 1 times ... 806e7d2 11 months, 1 week ago Selected Answer: B In Databricks Jobs, you can manage task dependencies within a single job. If you want to add a new task that needs to run before the original task due to an upstream issue, the appropriate approach would be to: Create a new task: This new task would run the notebook that addresses the upstream data issue. Add it as a dependency of the original task: By making the new task dependent on the original task, you ensure that the new task runs first, and only after its successful completion will the original task run. This approach ensures that the sequence of tasks is correctly managed in a single job, with dependencies explicitly defined. upvoted 1 times ... Colje 1 year, 1 month ago C. They can create a new task in the existing Job and then add the original task as a dependency of the new task. Why this is correct: In Databricks, you can set up a task dependency chain by adding a new task and specifying that the original task depends on the new one. This ensures that the new task will run first, followed by the original task. upvoted 1 times Alex_W 3 months, 3 weeks ago Thus it is B. upvoted 1 times ... ... tangerine141 1 year, 1 month ago Selected Answer: B Both B and C involve dependencies between tasks, but the difference is in how the dependencies are structured: B: "They can create a new task in the existing Job and then add it as a dependency of the original task." In this case, the new task is added as a prerequisite (dependency) for the original task. This means the new task will run first, and once it's completed, the original task will run. C: "They can create a new task in the existing Job and then add the original task as a dependency of the new task." In this case, the original task is added as a dependency for the new task, meaning the new task will wait for the original task to finish before running. The correct answer is B: You want the new task (the one handling the upstream issue) to run before the original task, so it should be set as a dependency of the original task. upvoted 1 times ... Stefan94 1 year, 1 month ago Selected Answer: B B is correct as Redwings538 says upvoted 1 times ... CID2024 1 year, 1 month ago I think the Correct answer is C. Because as per the statement in the question "they need to set up another task to run a new notebook prior to the original task." i.e. original task should run AFTER the new task. So, By creating a new task in the existing job and setting the original task as a dependency of the new task, the data engineer ensures that the new notebook runs first, followed by the original task. This approach maintains the sequence of execution required to address the upstream data issue. upvoted 2 times ... Load full discussion...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 38 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 38
Topic #: 1

[All Certified Data Engineer Associate Questions]

An engineering manager wants to monitor the performance of a recent project using a Databricks SQL query. For the first week following the project’s release, the manager wants the query results to be updated every minute. However, the manager is concerned that the compute resources used for the query will be left running and cost the organization a lot of money beyond the first week of the project’s release.Which of the following approaches can the engineering team use to ensure the query does not cost the organization any money beyond the first week of the project’s release? 
Suggested Answer: E 🗳️ 

A. They can set a limit to the number of DBUs that are consumed by the SQL Endpoint.

B. They can set the query’s refresh schedule to end after a certain number of refreshes.

C. They cannot ensure the query does not cost the organization money beyond the first week of the project’s release.

D. They can set a limit to the number of individuals that are able to manage the query’s refresh schedule.

E. They can set the query’s refresh schedule to end on a certain date in the query scheduler.

**Answer: E**

**Timestamp: April 5, 2023, 1:09 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/105269-exam-certified-data-engineer-associate-topic-1-question-38/)

Comments: Nika12 Highly Voted 1 year, 9 months ago Selected Answer: E Just got 100% on the test. E was correct. C was not in the available options. upvoted 16 times ... BigDaddyAus Highly Voted 2 years, 6 months ago The query scheduler only gives the option on what the interval is to run the query. It does not provide a way to stop after x iterations or at a point in time. The question is confusing. From what i found the only option is to limit users access to the query (and therefore query scheduler). https://docs.databricks.com/security/auth-authz/access-control/query-acl.html Not convinced how this would be helping the organization save money if no-one is manually stopping the schedule. Answer C seems most correct Answer D can be achieved using acl however how is this helpful in the use case described? upvoted 10 times ... dnanan4u Most Recent 4 months, 1 week ago Selected Answer: E E is correct upvoted 1 times ... Usaha1 9 months, 2 weeks ago Selected Answer: E Cron syntax can be used for scheduling upvoted 1 times ... rohitrc8521 9 months, 3 weeks ago Selected Answer: E Calm down folks, the answer is E!! upvoted 1 times ... UrcoIbz 11 months, 2 weeks ago Selected Answer: E Option E is correct. Although there in not an 'direct' option to select an end date, cron expressions allows run schedules on a specific time period (in this case a specific week). upvoted 1 times ... tmz1 1 year, 1 month ago Answer is E. There is an option to specify schedule with CRON syntax which enables to set schedule for a chosen week. For example, when you specify CRON: 0 0 0 23-29 SEP ? 2024, the query will be run At 12:00 AM, between day 23 and 29 of the month, only in September 2024. upvoted 2 times ... 7a22144 1 year, 2 months ago E is correct because the engineering team can use the query scheduler in Databricks to set a specific end date for the query refresh schedule. This way, after the first week, the automatic refreshes will stop, and the associated compute costs will be avoided. upvoted 1 times ... 3fbc31b 1 year, 3 months ago Selected Answer: E The correct answer is E for this question. upvoted 1 times ... aspix82 1 year, 5 months ago Answer is E upvoted 1 times ... data_arch 1 year, 8 months ago Selected Answer: E Answer is E It´s true natively the query can´t be scheduled to stop, but the scheduler allow us to use cron syntax. So we can define the year, month and days of the first week and the trigger won´t run after that upvoted 4 times ... Def21 1 year, 9 months ago Selected Answer: C The query scheduler does not give option to have end date (or iterations). Dashboards might give one, but the question specifically mentions queries. https://learn.microsoft.com/en-gb/azure/databricks/sql/user/queries/schedule-query upvoted 2 times ... Garyn 1 year, 10 months ago Selected Answer: E E. They can set the query’s refresh schedule to end on a certain date in the query scheduler. Explanation: Query Scheduler: Databricks offers a Query Scheduler that allows users to schedule the execution of SQL queries at specific intervals or for specific durations. Setting a Specific End Date: The team can configure the query's refresh schedule to conclude or end on a certain date. By specifying an end date within the first week of the project's release, the query will automatically stop refreshing after that date. This action ensures that compute resources aren't continuously utilized beyond the specified timeframe, preventing unnecessary costs. This approach allows the team to control and limit the execution of the query to the required duration without incurring additional costs beyond the first week of the project's release. upvoted 3 times ... mokrani 1 year, 10 months ago C is the correct answer Source : https://docs.databricks.com/en/sql/user/queries/schedule-query.html upvoted 1 times ... god_father 1 year, 12 months ago Selected Answer: E E is the correct answer. From the docs: If a dashboard is configured for automatic updates, it has a Scheduled button at the top, rather than a Schedule button. To stop automatically updating the dashboard and remove its subscriptions: Click Scheduled. In the Refresh every drop-down, select Never. Click Save. The Scheduled button label changes to Schedule. Source: https://learn.microsoft.com/en-us/azure/databricks/sql/user/dashboards/ upvoted 2 times Def21 1 year, 9 months ago This is Dashboard, not SQL query. upvoted 2 times ... ... kishore1980 2 years ago Selected Answer: E Option E is correct answer upvoted 1 times ... kishore1980 2 years ago Selected Answer: B The picker scrolls and allows you to choose: An interval: 1-30 minutes, 1-12 hours, 1 or 30 days, 1 or 2 weeks Since the schedule picker allows to choose interval to refresh query every 1 or 2 weeks. If we choose 1 week the schedule ends after a week. So the answer is B. upvoted 1 times kishore1980 2 years ago Based on my explanation E can be the correct answer. upvoted 1 times ... ... Load full discussion...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 40 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 40
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer wants to schedule their Databricks SQL dashboard to refresh once per day, but they only want the associated SQL endpoint to be running when it is necessary.Which of the following approaches can the data engineer use to minimize the total running time of the SQL endpoint used in the refresh schedule of their dashboard? 
Suggested Answer: C 🗳️ 

A. They can ensure the dashboard’s SQL endpoint matches each of the queries’ SQL endpoints.

B. They can set up the dashboard’s SQL endpoint to be serverless.

C. They can turn on the Auto Stop feature for the SQL endpoint.

D. They can reduce the cluster size of the SQL endpoint.

E. They can ensure the dashboard’s SQL endpoint is not one of the included query’s SQL endpoint.

**Answer: C**

**Timestamp: April 2, 2023, 7:25 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/104899-exam-certified-data-engineer-associate-topic-1-question-40/)

Comments: 4be8126 Highly Voted 2 years, 6 months ago Selected Answer: C The data engineer can use the Auto Stop feature to minimize the total running time of the SQL endpoint used in the refresh schedule of their dashboard. The Auto Stop feature allows the SQL endpoint to automatically shut down when there are no active connections, which will minimize the total running time of the SQL endpoint. By scheduling the dashboard to refresh once per day, the SQL endpoint will only be running for a short period of time each day, which will minimize the total running time and reduce costs. upvoted 13 times ... mokrani Highly Voted 1 year, 11 months ago Why it can't be B ? . They can set up the dashboard’s SQL endpoint to be serverless. ? they can use a serverless endpoint and it will only be active when required. upvoted 5 times datatrigger 11 months, 3 weeks ago Yes, B makes sense as well in my opinion. upvoted 1 times avidlearner 8 months, 1 week ago because here your workload is know, server less is more suitable for unpredictable workload. Also cost consideration. upvoted 2 times ... ... ... Khaled999 Most Recent 7 months ago Selected Answer: C c IS CORRECT upvoted 1 times ... 80370eb 1 year, 2 months ago Selected Answer: C The Auto Stop feature ensures that the SQL endpoint will automatically shut down when not in use, which helps in reducing unnecessary running time and associated costs. The endpoint will only be running when it's needed for refreshing the dashboard. upvoted 3 times ... SerGrey 1 year, 9 months ago Selected Answer: C C is correct upvoted 1 times ... awofalus 1 year, 11 months ago Selected Answer: C correct : C upvoted 1 times ... vikas555 1 year, 12 months ago C. They can turn on the Auto Stop feature for the SQL endpoint. upvoted 1 times ... vctrhugo 2 years, 1 month ago Selected Answer: C C. They can turn on the Auto Stop feature for the SQL endpoint. To minimize the total running time of the SQL endpoint used in the refresh schedule of their dashboard while ensuring that it only runs when necessary, the data engineer can turn on the Auto Stop feature for the SQL endpoint. This feature will automatically stop the SQL endpoint when it is idle for a specified period, reducing costs by avoiding unnecessary running time. Option C allows you to efficiently manage the SQL endpoint's lifecycle, ensuring it's active only when needed, which aligns with the goal of minimizing running time and associated costs. Option B (setting the dashboard's SQL endpoint to be serverless) can also be a valid approach, as it allows the SQL endpoint to be provisioned on-demand and incurs costs only when queries are executed. However, it depends on the specific requirements of your dashboard and queries. Options A, D, and E do not directly address the goal of minimizing the SQL endpoint's running time while ensuring it runs when necessary. upvoted 2 times ... ArindamNath 2 years, 2 months ago C is correct. upvoted 1 times ... AndreFR 2 years, 2 months ago Selected Answer: C https://docs.databricks.com/en/clusters/clusters-manage.html#automatic-termination upvoted 1 times ... Atnafu 2 years, 3 months ago C The Auto Stop feature automatically terminates the compute resources (cluster) associated with the SQL endpoint after a specified period of inactivity. By enabling this feature, the SQL endpoint will be automatically stopped when it is no longer needed, reducing the total running time and associated costs. upvoted 2 times ... XiltroX 2 years, 6 months ago Selected Answer: C Correct answer upvoted 4 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 43 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 43
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer has a Job with multiple tasks that runs nightly. Each of the tasks runs slowly because the clusters take a long time to start.Which of the following actions can the data engineer perform to improve the start up time for the clusters used for the Job? 
Suggested Answer: D 🗳️ 

A. They can use endpoints available in Databricks SQL

B. They can use jobs clusters instead of all-purpose clusters

C. They can configure the clusters to be single-node

D. They can use clusters that are from a cluster pool

E. They can configure the clusters to autoscale for larger data sizes

**Answer: D**

**Timestamp: April 2, 2023, 7:32 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/104901-exam-certified-data-engineer-associate-topic-1-question-43/)

Comments: Atnafu Highly Voted 2 years, 3 months ago D Cluster pools are a way to pre-provision clusters that are ready to use. This can reduce the start up time for clusters, as they do not have to be created from scratch. All-purpose clusters are not pre-provisioned, so they will take longer to start up. Jobs clusters are a type of cluster pool, but they are not the best option for this use case. Jobs clusters are designed for long-running jobs, and they can be more expensive than other types of cluster pools. Single-node clusters are the smallest type of cluster, and they will start up the fastest. However, they may not be powerful enough to run the Job's tasks. Autoscaling clusters can scale up or down based on demand. This can help to improve the start up time for clusters, as they will only be created when they are needed. However, autoscaling clusters can also be more expensive than other types of cluster pool upvoted 9 times ... e8eb7d9 Most Recent 2 months, 2 weeks ago Selected Answer: C D. Cluster pools is a Databrick feature that allow clusters to share a a pre-warming steps. upvoted 1 times ... 806e7d2 11 months, 1 week ago Selected Answer: D Using cluster pools can significantly improve the start-up time of clusters in Databricks. Here's why: Cluster Pools: Cluster pools are a feature in Databricks that allow clusters to share a pool of pre-warmed, idle virtual machines (VMs). When a new cluster is created, instead of starting a new VM from scratch, it can quickly acquire a pre-warmed instance from the pool. This leads to faster cluster startup times, which is especially helpful for jobs with multiple tasks that are running nightly. upvoted 2 times ... 80370eb 1 year, 2 months ago Selected Answer: D Cluster pools help to reduce cluster startup times by maintaining a pool of pre-warmed clusters that can be quickly allocated when needed. This minimizes the overhead associated with starting a new cluster from scratch, thus improving the efficiency and speed of running tasks in the Job. upvoted 1 times ... benni_ale 1 year, 6 months ago Selected Answer: D to be fair B might seem correct but D is more appropriate for reducing start up times upvoted 1 times ... Garyn 1 year, 10 months ago Selected Answer: D D. They can use clusters that are from a cluster pool. Explanation: Cluster Pools: Cluster pools in Databricks allow for the pre-creation and management of clusters in a pool that are readily available for use. With cluster pools, clusters are pre-initialized and kept in a ready state, minimizing the startup time when tasks need to run. This reduces the overhead of cluster initialization as the clusters are already provisioned and waiting for the tasks to be assigned. Using clusters from a pool ensures that there is no wait time for cluster initialization when the tasks start running in the nightly Job. This approach significantly reduces the time taken for clusters to start, thereby improving the overall performance and efficiency of the tasks by minimizing the overhead of cluster startup delays. upvoted 3 times ... DavidRou 1 year, 12 months ago Selected Answer: D They must use clusters from a pool if they want to reduce the startup time. upvoted 3 times ... vctrhugo 2 years, 1 month ago Selected Answer: D D. They can use clusters that are from a cluster pool. To improve startup time for the clusters used for the Job, the data engineer can configure the clusters to be sourced from a cluster pool. Cluster pools are pre-allocated clusters that are kept in a running state, ready for use. This eliminates the need to start new clusters from scratch each time a Job runs, significantly reducing startup times. Cluster pools are designed to optimize cluster reuse, making them an efficient choice for recurring jobs like the one described in the scenario. Option D provides a practical solution to address the slow cluster startup time issue. upvoted 3 times ... AndreFR 2 years, 2 months ago Selected Answer: D You can minimize instance acquisition time by creating a pool for each instance type and Databricks runtime your organization commonly uses. SOURCE : https://docs.databricks.com/en/clusters/pool-best-practices.html upvoted 3 times ... TC007 2 years, 6 months ago Selected Answer: D D: use clusters that are from a cluster pool. Using clusters from a cluster pool can improve the start-up time for the clusters used in the Job because the pool contains preconfigured and pre-started clusters that can be used immediately. This can save time and resources compared to starting new clusters for each task. upvoted 4 times ... 4be8126 2 years, 6 months ago Selected Answer: D D. They can use clusters that are from a cluster pool. Cluster pools allow you to pre-create a pool of ready-to-use clusters that can be used for running jobs, thereby eliminating the need to start new clusters each time a job runs. This can greatly reduce the startup time for each task. upvoted 4 times ... XiltroX 2 years, 6 months ago Selected Answer: B B is the correct answer. Job clusters are best suited for automated tasks running on a schedule. upvoted 2 times t30730 2 years, 6 months ago "Cluster pools allow us to reserve VM's ahead of time, when a new job cluster is created VM are grabbed from the pool. Note: when the VM's are waiting to be used by the cluster only cost incurred is Azure. Databricks run time cost is only billed once VM is allocated to a cluster. Use Databricks cluser pools feature to reduce the startup time" upvoted 1 times knivesz 2 years, 6 months ago D es la respuesta correcta upvoted 2 times ... ... ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 44 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 44
Topic #: 1

[All Certified Data Engineer Associate Questions]

A new data engineering team team. has been assigned to an ELT project. The new data engineering team will need full privileges on the database customers to fully manage the project.Which of the following commands can be used to grant full permissions on the database to the new data engineering team? 
Suggested Answer: E 🗳️ 

A. GRANT USAGE ON DATABASE customers TO team;

B. GRANT ALL PRIVILEGES ON DATABASE team TO customers;

C. GRANT SELECT PRIVILEGES ON DATABASE customers TO teams;

D. GRANT SELECT CREATE MODIFY USAGE PRIVILEGES ON DATABASE customers TO team;

E. GRANT ALL PRIVILEGES ON DATABASE customers TO team;

**Answer: E**

**Timestamp: April 2, 2023, 7:33 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/104902-exam-certified-data-engineer-associate-topic-1-question-44/)

Comments: e872ce8 8 months, 1 week ago Selected Answer: E E correct upvoted 1 times ... 806e7d2 11 months, 1 week ago Selected Answer: E To grant full privileges on a database in SQL, you would use the GRANT ALL PRIVILEGES command, which gives the specified user or group all available permissions on the database. This typically includes the ability to select, insert, update, delete, and modify the structure of the database (such as creating and dropping tables). In this case, the command: sql Copy code GRANT ALL PRIVILEGES ON DATABASE customers TO team; gives the team full control over the customers database, which is what is needed for them to manage the ELT project. upvoted 1 times ... benni_ale 1 year, 6 months ago Selected Answer: E e is correct upvoted 1 times ... Viju_1 1 year, 7 months ago Examtopics not showing all the questions and asking for contributor access. I can only see qestions till 44. Anyone is able to see all 99 questions?????? upvoted 1 times akshirao 1 year, 7 months ago i think the 99 questions have been relabelled as Q1-44 then Q1-45 upvoted 1 times ... ... Skidmee 1 year, 9 months ago E is correct upvoted 1 times ... csd 1 year, 10 months ago E is correct Template to give access--> GRANT Privilege ON Object <object-name> TO <user or group> ALL PRIVILEGES = gives all privilege upvoted 4 times ... awofalus 1 year, 11 months ago Selected Answer: E E is correct upvoted 2 times ... DavidRou 1 year, 12 months ago Selected Answer: D Right answer is E. The template to respect is the following: GRANT <privilege> ON <resource> TO <user/group> upvoted 2 times ... vctrhugo 2 years, 1 month ago Selected Answer: E E. GRANT ALL PRIVILEGES ON DATABASE customers TO team; To grant full privileges on the database "customers" to the new data engineering team, you can use the GRANT ALL PRIVILEGES command as shown in option E. This command provides the team with all possible privileges on the specified database, allowing them to fully manage it. Option A is not correct because it grants only the USAGE privilege, which is not sufficient for full management. Option B has the syntax reversed, and it is attempting to grant privileges on the "team" database to the "customers" database, which is not the desired action. Option C contains incorrect syntax and should use "team" instead of "teams." Option D has incorrect syntax and is not a valid SQL command for granting privileges in most database management systems. upvoted 2 times ... Atnafu 2 years, 3 months ago E GRANT ALL PRIVILEGES ON DATABASE customers TO team; upvoted 1 times ... rafahb 2 years, 6 months ago Selected Answer: E Option E upvoted 2 times ... XiltroX 2 years, 6 months ago Selected Answer: E Correct answer is E. Please take note of how the questions are worded to avoid confusion and not make the wrong choice. upvoted 3 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 45 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 45
Topic #: 1

[All Certified Data Engineer Associate Questions]

A new data engineering team has been assigned to work on a project. The team will need access to database customers in order to see what tables already exist. The team has its own group team.Which of the following commands can be used to grant the necessary permission on the entire database to the new team? 
Suggested Answer: E 🗳️ 

A. GRANT VIEW ON CATALOG customers TO team;

B. GRANT CREATE ON DATABASE customers TO team;

C. GRANT USAGE ON CATALOG team TO customers;

D. GRANT CREATE ON DATABASE team TO customers;

E. GRANT USAGE ON DATABASE customers TO team;

**Answer: E**

**Timestamp: April 2, 2023, 4:21 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/104870-exam-certified-data-engineer-associate-topic-1-question-45/)

Comments: Data_4ever Highly Voted 2 years, 6 months ago Selected Answer: E E is the correct answer. upvoted 14 times ... nedlo Highly Voted 1 year, 10 months ago Selected Answer: E GRANT USAGE, answer E is correct. I dont see such privilage as GRANT VIEW https://docs.databricks.com/en/sql/language-manual/sql-ref-privileges.html#privilege-types upvoted 7 times ... SoumyaHK Most Recent 6 months ago Selected Answer: E The response is E upvoted 1 times ... 7a22144 1 year, 2 months ago E is correct A: GRANT VIEW ON CATALOG is not a valid syntax in many SQL environments for database-level access. B: GRANT CREATE ON DATABASE customers would grant the team the ability to create objects in the database, which is more than just viewing the existing tables. C: This command incorrectly reverses the order of the team and the customers database. D: This would grant creation privileges on the team's database to the customers group, which is not relevant to the scenario. upvoted 1 times ... potaryxkug 1 year, 4 months ago E is correct upvoted 2 times ... rcpaudel 1 year, 7 months ago Selected Answer: E The question is asking "The team will need access to database customers in order to see what tables already exist." The presumption is, hoever, the team already has usage privilege on the catalog containing the database. upvoted 1 times ... kishanu 2 years ago Selected Answer: E Customers is a Database and not a catalog. The three-space naming convention has Catalog at the top level(catalog.database(schema).table). So granting a usage on catalog will expose other objects. upvoted 4 times ... J_1_2 2 years ago Selected Answer: E Option A, "GRANT VIEW ON CATALOG customers TO team," grants the privilege to view the catalog but not access the database's tables, so it might not fulfill the requirement of seeing the existing tables in the database. So answer is E upvoted 1 times ... tocs 2 years ago E. It can NOT be A. You can GRANT SELECT, but you cannot GRANT VIEW. VIEW is a securable OBJECT and not a PRIVILEGE TYPE, so you cannot grant it. See also https://learn.microsoft.com/en-us/azure/databricks/data-governance/unity-catalog/manage-privileges/privileges upvoted 3 times ... Nina0609 2 years, 1 month ago It's A....I got 100% on the Data Governance section...it's A upvoted 2 times tocs 2 years ago There is no such thing as GRANT VIEW, so A is not a valid option upvoted 1 times ... ... vctrhugo 2 years, 1 month ago Selected Answer: A A. GRANT VIEW ON CATALOG customers TO team; To grant the new data engineering team the necessary permission to view the tables that exist in the "customers" database, you can use the GRANT VIEW ON CATALOG command as shown in option A. This command allows the team to see the metadata and information about the tables in the specified catalog or database, which is what you want in this case. Option B grants the CREATE privilege on the "customers" database to the team, which is not necessary for simply viewing existing tables. Option C and Option D have the syntax reversed, attempting to grant permissions from the team to the "customers" database, which is not the desired action. Option E grants USAGE privilege on the "customers" database to the team, which allows them to use the database but may not provide the necessary view permissions to see existing tables. upvoted 1 times shaojunni 1 year, 1 month ago Wrong, customers is a database, not catalog. upvoted 1 times ... ... AndreFR 2 years, 2 months ago Selected Answer: B SOURCE : https://docs.databricks.com/en/sql/language-manual/security-grant.html The perfect answer would be : GRANT SHOW METADATA ON DATABASE customers TO team But because, it is not suggested, we need to find an impertect answer allowing listing tables on database customers for project team's group : team A. GRANT VIEW ON CATALOG customers TO team -- Incorrect : "GRANT VIEW" does not exist B. GRANT CREATE ON DATABASE customers TO team -- Correct : only possible answer by elimitation. C. GRANT USAGE ON CATALOG team TO customers -- Incorrect : "GRANT USAGE" does not allow listing tables D. GRANT CREATE ON DATABASE team TO customers -- Incorrect : "team" and "customers" are inverted E. GRANT USAGE ON DATABASE customers TO team -- Incorrect : "GRANT USAGE" does not allow listing tables upvoted 2 times AndreFR 2 years, 2 months ago In addition to what was typed previously, I'm adding an extra source : https://docs.databricks.com/en/data-governance/table-acls/object-privileges.html#usage-privilege So correct syntax for what I previously wrote is : GRANT SHOW READ_METADATA ON DATABASE customers TO team and not : GRANT SHOW METADATA ON DATABASE customers TO team upvoted 1 times ... ... Office2022 2 years, 3 months ago The correct answer is E. GRANT ALL PRIVILEGES ON DATABASE customers TO team; The GRANT statement is used to grant privileges on a database, table, or view to a user or role. The ALL PRIVILEGES option grants all possible privileges on the specified object, such as CREATE, SELECT, MODIFY, and USAGE. The syntax of the GRANT statement is: GRANT privilege_type ON object TO user_or_role; Therefore, to grant full permissions on the database customers to the new data engineering team, the command should be: GRANT ALL PRIVILEGES ON DATABASE customers TO team; Option A is incorrect because it only grants the USAGE privilege, which allows the team to access the database but not to create or modify any tables or views in it. upvoted 2 times ... Atnafu 2 years, 3 months ago E The GRANT USAGE ON DATABASE command grants the USAGE privilege on the specified database to the specified group. The USAGE privilege allows the group to see the tables that exist in the database, but it does not allow them to do anything else with the database. The other commands are incorrect. The GRANT VIEW ON CATALOG command grants the VIEW privilege on the specified catalog to the specified group. The CREATE privilege allows the group to create new tables in the database. The USAGE privilege on the CATALOG does not exist. upvoted 1 times ... clownfishman 2 years, 3 months ago The correct is GRANT both "USAGE" and "SELECT" on DATABASE CUSTOMERS TO TEAMS upvoted 2 times ... chays 2 years, 4 months ago Selected Answer: E e is the right answer upvoted 1 times ... prasioso 2 years, 5 months ago Selected Answer: E Think the Answer is E. The privilege types are CREATE, MODIFY, READ_METADATA, SELECT and USAGE. There is no such thing as GRANT VIEW. (it can however be GRANT <p-type> ON VIEW TO <team>). For our use case we want to GRANT USAGE for reading the Database. C has wrong syntax. upvoted 2 times ... Load full discussion...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 46 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 46
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer is running code in a Databricks Repo that is cloned from a central Git repository. A colleague of the data engineer informs them that changes have been made and synced to the central Git repository. The data engineer now needs to sync their Databricks Repo to get the changes from the central Git repository.Which of the following Git operations does the data engineer need to run to accomplish this task? 
Suggested Answer: C 🗳️ 

A. Merge

B. Push

C. Pull

D. Commit

E. Clone

**Answer: C**

**Timestamp: Oct. 20, 2023, 3:48 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/124124-exam-certified-data-engineer-associate-topic-1-question-46/)

Comments: benni_ale 12 months ago Selected Answer: C C is correct upvoted 2 times ... god_father 1 year, 6 months ago Selected Answer: C This is more of a Git question. From the docs: In Databricks Repos, you can use Git functionality to: Clone, push to, and pull from a remote Git repository. Create and manage branches for development work, including merging, rebasing, and resolving conflicts. Create notebooks&mdash;including IPYNB notebooks&mdash;and edit them and other files. Visually compare differences upon commit and resolve merge conflicts. Source: https://docs.databricks.com/en/repos/index.html upvoted 1 times ... kishanu 1 year, 6 months ago Selected Answer: C pull is required from the Databricks Repo to sync the changes b/w local and central repo. upvoted 2 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 47 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 47
Topic #: 1

[All Certified Data Engineer Associate Questions]

Which of the following is a benefit of the Databricks Lakehouse Platform embracing open source technologies? 
Suggested Answer: E 🗳️ 

A. Cloud-specific integrations

B. Simplified governance

C. Ability to scale storage

D. Ability to scale workloads

E. Avoiding vendor lock-in

**Answer: E**

**Timestamp: Oct. 19, 2023, 8:36 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/124066-exam-certified-data-engineer-associate-topic-1-question-47/)

Comments: 80370eb 1 year, 2 months ago Selected Answer: E By embracing open-source technologies, the platform allows users to avoid being locked into a single vendor's ecosystem, offering flexibility and the ability to integrate with a wide range of tools and systems. upvoted 2 times ... benni_ale 1 year, 6 months ago Selected Answer: E E is correct upvoted 1 times ... UGOTCOOKIES 1 year, 9 months ago Selected Answer: E E is correct as open-source is opposite of proprietary technology, so not being a proprietary means it is free of vendor lock in, if that makes sense. upvoted 4 times ... meow_akk 2 years ago its avoiding vendor lock in : - https://double.cloud/blog/posts/2023/01/break-free-from-vendor-lock-in-with-open-source-tech/ upvoted 3 times ... kishanu 2 years ago Selected Answer: E E looks to be the correct one, as Databricks Lakeshouse platform supports Delta table which is an open-source format for storage. upvoted 2 times ... Rs1997 2 years ago D is the correct answer upvoted 1 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 49 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 49
Topic #: 1

[All Certified Data Engineer Associate Questions]

Which of the following describes a scenario in which a data engineer will want to use a single-node cluster? 
Suggested Answer: A 🗳️ 

A. When they are working interactively with a small amount of data

B. When they are running automated reports to be refreshed as quickly as possible

C. When they are working with SQL within Databricks SQL

D. When they are concerned about the ability to automatically scale with larger data

E. When they are manually running reports with a large amount of data

**Answer: A**

**Timestamp: Oct. 20, 2023, 3:55 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/124125-exam-certified-data-engineer-associate-topic-1-question-49/)

Comments: kishanu Highly Voted 1 year, 6 months ago Selected Answer: A Single node clusters can be used for interactive queries with small dataset upvoted 5 times ... benni_ale Most Recent 12 months ago Selected Answer: A A is correct upvoted 1 times ... azure_bimonster 1 year, 3 months ago Selected Answer: A A seems correct for this upvoted 2 times ... meow_akk 1 year, 6 months ago ans A : A Single Node cluster is a cluster consisting of an Apache Spark driver and no Spark workers. A Single Node cluster supports Spark jobs and all Spark data sources, including Delta Lake. A Standard cluster requires a minimum of one Spark worker to run Spark jobs. https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwidg8mSsYqCAxUmg2oFHbkTDJsQFnoECA4QAw&url=https%3A%2F%2Fdocs.databricks.com%2Fen%2Fclusters%2Fsingle-node.html%23%3A~%3Atext%3DA%2520Single%2520Node%2520cluster%2520is%2Cworker%2520to%2520run%2520Spark%2520jobs.&usg=AOvVaw3PFq3_Qyt2gAAa4id0j6CS&opi=89978449 upvoted 4 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 51 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 51
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer has realized that the data files associated with a Delta table are incredibly small. They want to compact the small files to form larger files to improve performance.Which of the following keywords can be used to compact the small files? 
Suggested Answer: B 🗳️ 

A. REDUCE

B. OPTIMIZE

C. COMPACTION

D. REPARTITION

E. VACUUM

**Answer: B**

**Timestamp: Oct. 20, 2023, 3:57 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/124126-exam-certified-data-engineer-associate-topic-1-question-51/)

Comments: kishanu Highly Voted 2 years ago Selected Answer: B OPTIMIZE can be used to club small files into 1 and improve performance. upvoted 6 times ... 80370eb Most Recent 1 year, 2 months ago Selected Answer: B The OPTIMIZE command in Databricks is used to compact small files into larger ones, improving the performance of Delta tables. upvoted 2 times ... 80370eb 1 year, 2 months ago Selected Answer: B The OPTIMIZE command in Delta Lake merges small files into larger files, which can help improve query performance and manage storage more efficiently. upvoted 1 times ... benni_ale 1 year, 6 months ago Selected Answer: B B is correct upvoted 1 times ... UGOTCOOKIES 1 year, 9 months ago Selected Answer: B OPTIMIZE is the correct answer. Compacting small files using the OPTIMIZE command improves table performance such as by combining multiple small files into larger ones. upvoted 2 times ... azure_bimonster 1 year, 9 months ago Selected Answer: B OPTIMIZE would help in this scenario upvoted 2 times ... nedlo 1 year, 10 months ago Selected Answer: B Its B https://docs.databricks.com/en/delta/optimize.html upvoted 2 times ... meow_akk 2 years ago Ans B : optimize is used to compact small files which in turn improves perf upvoted 3 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 54 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 54
Topic #: 1

[All Certified Data Engineer Associate Questions]

Which of the following can be used to simplify and unify siloed data architectures that are specialized for specific use cases? 
Suggested Answer: E 🗳️ 

A. None of these

B. Data lake

C. Data warehouse

D. All of these

E. Data lakehouse

**Answer: E**

**Timestamp: Oct. 20, 2023, 4:01 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/124127-exam-certified-data-engineer-associate-topic-1-question-54/)

Comments: benni_ale 12 months ago Selected Answer: E E is correct upvoted 1 times ... azure_bimonster 1 year, 3 months ago Selected Answer: E Lakehouse, so E is correct upvoted 2 times ... kishanu 1 year, 6 months ago Selected Answer: E Data Lakehouse can be used as a single source of truth for multiple specific use cases upvoted 4 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 56 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 56
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer has a Python notebook in Databricks, but they need to use SQL to accomplish a specific task within a cell. They still want all of the other cells to use Python without making any changes to those cells.Which of the following describes how the data engineer can use SQL within a cell of their Python notebook? 
Suggested Answer: D 🗳️ 

A. It is not possible to use SQL in a Python notebook

B. They can attach the cell to a SQL endpoint rather than a Databricks cluster

C. They can simply write SQL syntax in the cell

D. They can add %sql to the first line of the cell

E. They can change the default language of the notebook to SQL

**Answer: D**

**Timestamp: Oct. 22, 2023, 4:36 a.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/124290-exam-certified-data-engineer-associate-topic-1-question-56/)

Comments: 80370eb 1 year, 2 months ago Selected Answer: D we can use magic comment in notebook to indicate the cell to be run in specific language %SQL. upvoted 1 times ... azure_bimonster 1 year, 9 months ago Selected Answer: D Magic command % can be used to switch the language, so D is correct upvoted 1 times ... bartfto 1 year, 9 months ago Selected Answer: D D. Correct. Use %sql magic in first line. upvoted 1 times ... Lavpak 1 year, 11 months ago Selected Answer: D Use magic command %sql upvoted 3 times ... MFEST 1 year, 12 months ago correct answer D upvoted 3 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 57 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 57
Topic #: 1

[All Certified Data Engineer Associate Questions]

Which of the following SQL keywords can be used to convert a table from a long format to a wide format? 
Suggested Answer: B 🗳️ 

A. TRANSFORM

B. PIVOT

C. SUM

D. CONVERT

E. WHERE

**Answer: B**

**Timestamp: Oct. 22, 2023, 4:35 a.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/124289-exam-certified-data-engineer-associate-topic-1-question-57/)

Comments: 80370eb 1 year, 2 months ago Selected Answer: B The PIVOT operation is used to rotate data from rows to columns, which effectively converts a table from a long format (where each row represents a single observation or measurement) to a wide format (where each row represents a single entity with multiple observations or measurements as columns). upvoted 1 times ... benni_ale 1 year, 6 months ago Selected Answer: B B is correct upvoted 1 times ... azure_bimonster 1 year, 9 months ago Selected Answer: B Answer is B upvoted 1 times ... AndreFR 1 year, 10 months ago Selected Answer: B https://docs.databricks.com/en/sql/language-manual/sql-ref-syntax-qry-select-pivot.html “Pivot” transforms the rows of the table_reference by rotating unique values of a specified column list into separate columns. SYNTAX : table_reference PIVOT ( { aggregate_expression [ [ AS ] agg_column_alias ] } [, ...] FOR column_list IN ( expression_list ) ) column_list { column_name | ( column_name [, ...] ) } expression_list { expression [ AS ] [ column_alias ] | { ( expression [, ...] ) [ AS ] [ column_alias] } [, ...] ) } upvoted 2 times ... athu07 2 years ago Selected Answer: B PIVOT is correct. upvoted 2 times ... meow_akk 2 years ago PIVOT is correct. upvoted 3 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 58 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 58
Topic #: 1

[All Certified Data Engineer Associate Questions]

Which of the following describes a benefit of creating an external table from Parquet rather than CSV when using a CREATE TABLE AS SELECT statement? 
Suggested Answer: C 🗳️ 

A. Parquet files can be partitioned

B. CREATE TABLE AS SELECT statements cannot be used on files

C. Parquet files have a well-defined schema

D. Parquet files have the ability to be optimized

E. Parquet files will become Delta tables

**Answer: C**

**Timestamp: Oct. 21, 2023, 4:31 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/124209-exam-certified-data-engineer-associate-topic-1-question-58/)

Comments: 1a44567 1 year, 3 months ago Vote for D Parquet files are a columnar storage file format that allows for efficient data compression and encoding schemes, enabling optimization and faster query performance compared to CSV files. This format supports efficient reading and writing of large datasets, making it a preferred choice for big data applications. upvoted 1 times ... MDWPartners 1 year, 5 months ago Selected Answer: C The keywords are "CREATE TABLE AS SELECT " upvoted 2 times ... benni_ale 1 year, 6 months ago Selected Answer: C C is correct upvoted 1 times ... UGOTCOOKIES 1 year, 9 months ago Selected Answer: C CREATE TABLE AS SELECT adopts the schema details from the source. Parquet files have a defined schema. upvoted 2 times ... bartfto 1 year, 9 months ago Selected Answer: C C. Paruqet has well defined schema unline csv upvoted 1 times ... Garyn 1 year, 10 months ago Selected Answer: C C. Parquet files have a well-defined schema. Explanation: Parquet files inherently store metadata about the schema within the files themselves, allowing for a well-defined schema. This schema information includes data types, column names, and other structural information. When creating an external table from Parquet, this schema is retained, providing a structured and well-defined format for the data. It ensures consistency and enables more efficient processing, query optimization, and compatibility across various systems or tools that work with the Parquet format. This structured schema within Parquet files offers advantages in terms of data integrity, ease of data processing, and compatibility, making it a beneficial choice over CSV, which lacks inherent schema information and might need additional handling or inference of schema during data ingestion. upvoted 1 times ... AndreFR 1 year, 10 months ago Selected Answer: B The key word here is : CREATE TABLE AS SELECT not A : partitioning is not relevant in a create table as statement because the data will be created in a delta table not C : Parquet schema is not well defined and there can be parquet files with multiple schema in a folder not D : Parquet are already optimized and are not relevant in a create table as statement because the data will be created in a delta table not E : both CSV & Parquet will become delta tables in a create table as statement B : correct answer by elimination upvoted 1 times ... nedlo 1 year, 10 months ago Selected Answer: D I disagree i think its D. Schema can be inferred from CSV as well, but CSV cannot provide same optimizations as Parquet upvoted 1 times ... FastEddie 1 year, 12 months ago Selected Answer: C CTAS - CTAS automatically infer schema information from query results and do not support manual schema declaration.This means that CTAS statements are useful for external data ingestion from sources with well-defined schema, such as Parquet files and tables.CTAS statements also do not support specifying additional file options. upvoted 4 times ... kishore1980 1 year, 12 months ago Selected Answer: C C is the correct option upvoted 2 times ... anandpsg101 2 years ago Selected Answer: C c is correct upvoted 2 times ... meow_akk 2 years ago Ans : C https://www.databricks.com/glossary/what-is-parquet#:~:text=Columnar%20storage%20like%20Apache%20Parquet,compared%20to%20row%2Doriented%20databases. Columnar storage like Apache Parquet is designed to bring efficiency compared to row-based files like CSV. When querying, columnar storage you can skip over the non-relevant data very quickly. As a result, aggregation queries are less time-consuming compared to row-oriented databases. upvoted 4 times ... kbaba101 2 years ago C. it supports well-defined schema, such as Parquet files and tables and do not support specifying additional file options such as Delimeter if you were to use CSV upvoted 4 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 62 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 62
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer needs to apply custom logic to identify employees with more than 5 years of experience in array column employees in table stores. The custom logic should create a new column exp_employees that is an array of all of the employees with more than 5 years of experience for each row. In order to apply this custom logic at scale, the data engineer wants to use the FILTER higher-order function.Which of the following code blocks successfully completes this task? 
Suggested Answer: A 🗳️ 

A.

B.

C.

D.

E.

**Answer: A**

**Timestamp: Oct. 22, 2023, 4:56 a.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/124294-exam-certified-data-engineer-associate-topic-1-question-62/)

Comments: benni_ale 12 months ago Selected Answer: A A is correct upvoted 1 times ... AndreFR 1 year, 4 months ago Selected Answer: A B & E incorrect : source is employees not exp_employees D incorrect : does not use FILTER higher-order function) C incorrect : syntax errror A : correct by elimination & based on https://docs.databricks.com/en/sql/language-manual/functions/filter.html#examples upvoted 3 times ... kz_data 1 year, 4 months ago Selected Answer: A A is correct upvoted 2 times ... 55f31c8 1 year, 5 months ago Selected Answer: A https://docs.databricks.com/en/sql/language-manual/functions/filter.html upvoted 3 times ... meow_akk 1 year, 6 months ago A is correct. upvoted 4 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 66 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 66
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer that is new to using Python needs to create a Python function to add two integers together and return the sum?Which of the following code blocks can the data engineer use to complete this task? 
Suggested Answer: D 🗳️ 

A.

B.

C.

D.

E.

**Answer: D**

**Timestamp: Oct. 22, 2023, 5:06 a.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/124297-exam-certified-data-engineer-associate-topic-1-question-66/)

Comments: UGOTCOOKIES 1 year, 9 months ago Selected Answer: D Python functions start with the def keyword followed by the function name. Function also ends with the return keyword. upvoted 2 times ... azure_bimonster 1 year, 9 months ago Selected Answer: D D is to choose here upvoted 2 times ... kz_data 1 year, 10 months ago Selected Answer: D D is correct upvoted 2 times ... 55f31c8 1 year, 11 months ago Selected Answer: D D : https://www.geeksforgeeks.org/python-functions/ upvoted 3 times ... Syd 1 year, 12 months ago D is correct. https://www.w3schools.com/python/python_functions.asp upvoted 2 times ... meow_akk 2 years ago D is correct. if you get this answer wrong you need to learn the basics of python. upvoted 3 times CommanderBigMac 1 year, 1 month ago Like the data engineer in the question upvoted 1 times ... ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 68 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 68
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer is working with two tables. Each of these tables is displayed below in its entirety.The data engineer runs the following query to join these tables together:Which of the following will be returned by the above query? 
Suggested Answer: C 🗳️ 

A.

B.

C.

D.

E.

**Answer: C**

**Timestamp: Oct. 20, 2023, 7:59 a.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/124091-exam-certified-data-engineer-associate-topic-1-question-68/)

Comments: kz_data Highly Voted 1 year, 10 months ago Selected Answer: C C is correct upvoted 7 times ... 80370eb Most Recent 1 year, 2 months ago Selected Answer: C c is correct when performing left join the sales values are only taken. upvoted 1 times ... potaryxkug 1 year, 4 months ago C is correct upvoted 3 times ... nedlo 1 year, 10 months ago Selected Answer: C C is correct answer upvoted 3 times ... 55f31c8 1 year, 11 months ago Selected Answer: C The LEFT JOIN keyword returns all records from the left table (table1), and the matching records from the right table (table2). The result is 0 records from the right side, if there is no match. upvoted 4 times ... Blacknight99 1 year, 11 months ago Selected Answer: C C is the correct answer upvoted 2 times ... Huroye 1 year, 11 months ago The answer is C. this is a Left Join. In this case you show everything on the left side regardless of whether they appear on the right. When it does not appear on the right you represent that with a Null. So, for a3, store id is null. upvoted 3 times ... dev_soumya369 1 year, 11 months ago C is the correct answer. In a LEFT JOIN, all the records from the left table are included, and only the matching records from the right table are added. In this case, "a1" and "a4" from the left table (favorite_stores) match with "a1" and "a4" from the right table (sales). So, these matching records are fetched. Additionally, all the records from the left table, including "a3," are included. Since "a3" has no corresponding store_id in the right table, the store_id for "a3" will be NULL. Therefore, after the LEFT JOIN, the result will include "a1," "a3" (with a NULL store_id), and "a4." upvoted 3 times ... mokrani 1 year, 11 months ago C is correct. please refer to this simple blog if any confusion regarding JOINS https://sql.sh/cours/jointures upvoted 1 times ... anandpsg101 2 years ago Selected Answer: C c is corret upvoted 2 times ... meow_akk 2 years ago Ans C: Left join only keeps left recs and only the matching recs from Right table. in other words : the left table is preserved as is. upvoted 1 times ... kishanu 2 years ago Selected Answer: C A typical LEFT JOIN scenario upvoted 1 times ... [Removed] 2 years ago Selected Answer: C The LEFT JOIN keyword returns all records from the left table, even if there are no matches in the right table. upvoted 3 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 71 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 71
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer has developed a data pipeline to ingest data from a JSON source using Auto Loader, but the engineer has not provided any type inference or schema hints in their pipeline. Upon reviewing the data, the data engineer has noticed that all of the columns in the target table are of the string type despite some of the fields only including float or boolean values.Which of the following describes why Auto Loader inferred all of the columns to be of the string type? 
Suggested Answer: B 🗳️ 

A. There was a type mismatch between the specific schema and the inferred schema

B. JSON data is a text-based format

C. Auto Loader only works with string data

D. All of the fields had at least one null value

E. Auto Loader cannot infer the schema of ingested data

**Answer: B**

**Timestamp: Oct. 22, 2023, 5:19 a.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/124300-exam-certified-data-engineer-associate-topic-1-question-71/)

Comments: AndreFR 1 year, 4 months ago Selected Answer: B https://docs.databricks.com/en/ingestion/auto-loader/schema.html#how-does-auto-loader-schema-inference-work By default, Auto Loader schema inference seeks to avoid schema evolution issues due to type mismatches. For formats that don’t encode data types (JSON and CSV), Auto Loader infers all columns as strings (including nested fields in JSON files). upvoted 4 times ... nedlo 1 year, 4 months ago Selected Answer: B Its B "By default, Auto Loader schema inference seeks to avoid schema evolution issues due to type mismatches. For formats that don’t encode data types (JSON and CSV), Auto Loader infers all columns as strings (including nested fields in JSON files). For formats with typed schema (Parquet and Avro), Auto Loader samples a subset of files and merges the schemas of individual files. This behavior is summarized in the following table:" https://docs.databricks.com/en/ingestion/auto-loader/schema.html upvoted 2 times ... 55f31c8 1 year, 5 months ago Selected Answer: B https://docs.databricks.com/en/ingestion/auto-loader/schema.html#how-does-auto-loader-schema-inference-work upvoted 2 times ... meow_akk 1 year, 6 months ago The correct answer is: B. JSON data is a text-based format JSON data is a text-based format that uses strings to represent all values. When Auto Loader infers the schema of JSON data, it assumes that all values are strings. This is because Auto Loader cannot determine the type of a value based on its string representation. https://docs.databricks.com/en/ingestion/auto-loader/schema.html For example, the following JSON string represents a value that is logically a boolean: JSON "true" Use code with caution. Learn more However, Auto Loader would infer that the type of this value is string. This is because Auto Loader cannot determine that the value is a boolean based on its string representation. In order to get Auto Loader to infer the correct types for columns, the data engineer can provide type inference or schema hints. Type inference hints can be used to specify the types of specific columns. Schema hints can be used to provide the entire schema of the data. Therefore, the correct answer is B. JSON data is a text-based format. upvoted 2 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 72 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 72
Topic #: 1

[All Certified Data Engineer Associate Questions]

A Delta Live Table pipeline includes two datasets defined using STREAMING LIVE TABLE. Three datasets are defined against Delta Lake table sources using LIVE TABLE.The table is configured to run in Development mode using the Continuous Pipeline Mode.Assuming previously unprocessed data exists and all definitions are valid, what is the expected outcome after clicking Start to update the pipeline? 
Suggested Answer: E 🗳️ 

A. All datasets will be updated once and the pipeline will shut down. The compute resources will be terminated.

B. All datasets will be updated at set intervals until the pipeline is shut down. The compute resources will persist until the pipeline is shut down.

C. All datasets will be updated once and the pipeline will persist without any processing. The compute resources will persist but go unused.

D. All datasets will be updated once and the pipeline will shut down. The compute resources will persist to allow for additional testing.

E. All datasets will be updated at set intervals until the pipeline is shut down. The compute resources will persist to allow for additional testing.

**Answer: E**

**Timestamp: Oct. 21, 2023, 12:06 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/124177-exam-certified-data-engineer-associate-topic-1-question-72/)

Comments: meow_akk Highly Voted 2 years ago Ans E : Development and production modes You can optimize pipeline execution by switching between development and production modes. Use the Delta Live Tables Environment Toggle Icon buttons in the Pipelines UI to switch between these two modes. By default, pipelines run in development mode. When you run your pipeline in development mode, the Delta Live Tables system does the following: Reuses a cluster to avoid the overhead of restarts. By default, clusters run for two hours when development mode is enabled. You can change this with the pipelines.clusterShutdown.delay setting in the Configure your compute settings. Disables pipeline retries so you can immediately detect and fix errors. In production mode, the Delta Live Tables system does the following: Restarts the cluster for specific recoverable errors, including memory leaks and stale credentials. Retries execution in the event of specific errors, for example, a failure to start a cluster. https://docs.databricks.com/en/delta-live-tables/updates.html#optimize-execution upvoted 12 times ... 1017857 Most Recent 8 months, 2 weeks ago Selected Answer: B testing why testing upvoted 1 times ... JuarezNJunior 8 months, 3 weeks ago Selected Answer: D According to the document downloaded from the official website, the correct answer is letter D. PracticeExam-DataEngineerAssociate.pdf upvoted 1 times JuarezNJunior 8 months, 2 weeks ago Hello everyone. I made a mistake. The practical exam pdf is about "Triggered Pipeline Mode" against "Continuous Pipeline Mode." in this question. The correct answer is E. upvoted 1 times ... ... AnirbanRC 9 months, 3 weeks ago Selected Answer: E Continuous and Development Mode. Hence E upvoted 1 times ... MultiCloudIronMan 10 months, 2 weeks ago Selected Answer: B The correct answer is B. All datasets will be updated at set intervals until the pipeline is shut down. The compute resources will persist until the pipeline is shut down. In Continuous Pipeline Mode, the pipeline continuously processes data at set intervals, and the compute resources remain active until the pipeline is manually shut down. upvoted 1 times ... 806e7d2 11 months, 1 week ago Selected Answer: B The pipeline runs in Continuous Pipeline Mode, so datasets will be updated at set intervals. Since the pipeline is in Development Mode, the compute resources will persist until manually shut down. upvoted 1 times ... 7a22144 1 year, 2 months ago E is correct ! Option B: "All datasets will be updated at set intervals until the pipeline is shut down. The compute resources will persist until the pipeline is shut down." This option correctly reflects that the pipeline continues running, updating datasets at intervals, and only stops when manually shut down. Compute resources persist throughout this process. Option E: "All datasets will be updated at set intervals until the pipeline is shut down. The compute resources will persist to allow for additional testing." While this is very similar, it adds the phrase "to allow for additional testing," which might imply that the resources are persisting just for testing purposes. This can be misleading because the primary reason for resource persistence in Continuous mode is to keep the pipeline active and processing data, not solely for testing. upvoted 1 times ... 3fbc31b 1 year, 3 months ago Selected Answer: E The answer is E. The compute resources will persist even after the pipeline is shut down. upvoted 1 times ... benni_ale 1 year, 6 months ago Selected Answer: E e as teh cluster actually persits differently from b upvoted 1 times ... Garyn 1 year, 10 months ago Selected Answer: E E. All datasets will be updated at set intervals until the pipeline is shut down. The compute resources will persist to allow for additional testing. Explanation: In Development mode, Delta Live Tables persistently updates datasets at set intervals. The pipeline continuously processes incoming data until manually stopped or shut down. Compute resources, including the cluster used for processing, persist without automatic restarts or retries (as it is the behavior in Development mode). This persistence allows for ongoing processing of data, enabling additional testing or continued data processing until the pipeline is manually shut down. Therefore, option E accurately captures the behavior expected in Development mode, emphasizing the continuous update of datasets and the persistence of compute resources until the pipeline is manually terminated. upvoted 2 times ... kz_data 1 year, 10 months ago Selected Answer: E E seems the correct answer upvoted 2 times ... nedlo 1 year, 10 months ago Selected Answer: B Why E? It persists with same functionality as was before, not for "additional testing"? upvoted 2 times AndreFR 1 year, 10 months ago because "The table is configured to run in Development mode" when tables are set in dev mode, "The compute resources will persist to allow for additional testing." upvoted 1 times AndreFR 1 year, 10 months ago So correct answer is E upvoted 1 times ... ... ... 55f31c8 1 year, 11 months ago Selected Answer: E https://docs.databricks.com/en/delta-live-tables/updates.html#continuous-vs-triggered-pipeline-execution https://docs.databricks.com/en/delta-live-tables/testing.html#use-development-mode-to-run-pipeline-updates upvoted 2 times ... anandpsg101 2 years ago Selected Answer: E E is correct upvoted 2 times ... SD5713 2 years ago Selected Answer: E E. All datasets will be updated at set intervals until the pipeline is shut down. The compute resources will persist to allow for additional testing. upvoted 2 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 73 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 73
Topic #: 1

[All Certified Data Engineer Associate Questions]

Which of the following data workloads will utilize a Gold table as its source? 
Suggested Answer: D 🗳️ 

A. A job that enriches data by parsing its timestamps into a human-readable format

B. A job that aggregates uncleaned data to create standard summary statistics

C. A job that cleans data by removing malformatted records

D. A job that queries aggregated data designed to feed into a dashboard

E. A job that ingests raw data from a streaming source into the Lakehouse

**Answer: D**

**Timestamp: Oct. 22, 2023, 5:25 a.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/124301-exam-certified-data-engineer-associate-topic-1-question-73/)

Comments: CommanderBigMac 1 year, 1 month ago Selected Answer: D A gold table is most likely to contain aggregated data. It is also the table where cleaned up data is stored, so that is where data will be used from for a dashboard. upvoted 1 times ... 55f31c8 1 year, 11 months ago Selected Answer: D https://docs.databricks.com/en/lakehouse/medallion.html#power-analytics-with-the-gold-layer upvoted 1 times ... meow_akk 2 years ago D is correct : std medallion arch upvoted 3 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 76 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 76
Topic #: 1

[All Certified Data Engineer Associate Questions]

Which of the following describes the type of workloads that are always compatible with Auto Loader? 
Suggested Answer: A 🗳️ 

A. Streaming workloads

B. Machine learning workloads

C. Serverless workloads

D. Batch workloads

E. Dashboard workloads

**Answer: A**

**Timestamp: Oct. 22, 2023, 5:36 a.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/124305-exam-certified-data-engineer-associate-topic-1-question-76/)

Comments: meow_akk Highly Voted 2 years ago A is correct Structured streaming for autoloader upvoted 6 times ... 80370eb Most Recent 1 year, 2 months ago Selected Answer: A Auto Loader is designed to handle streaming data ingestion. It continuously processes new data as it arrives, making it well-suited for streaming workloads. upvoted 2 times ... benni_ale 1 year, 6 months ago Selected Answer: A A is ok upvoted 1 times ... azure_bimonster 1 year, 9 months ago Selected Answer: A A is correct here upvoted 1 times ... AndreFR 1 year, 10 months ago Selected Answer: A https://docs.databricks.com/en/ingestion/auto-loader/unity-catalog.html#using-auto-loader-with-unity-catalog Auto Loader relies on Structured Streaming for incremental processing upvoted 3 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 78 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 78
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer is using the following code block as part of a batch ingestion pipeline to read from a composable table:Which of the following changes needs to be made so this code block will work when the transactions table is a stream source? 
Suggested Answer: E 🗳️ 

A. Replace predict with a stream-friendly prediction function

B. Replace schema(schema) with option ("maxFilesPerTrigger", 1)

C. Replace "transactions" with the path to the location of the Delta table

D. Replace format("delta") with format("stream")

E. Replace spark.read with spark.readStream

**Answer: E**

**Timestamp: Oct. 22, 2023, 5:43 a.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/124307-exam-certified-data-engineer-associate-topic-1-question-78/)

Comments: benni_ale 12 months ago Selected Answer: E E is ok upvoted 2 times ... AndreFR 1 year, 4 months ago Selected Answer: E https://docs.databricks.com/en/structured-streaming/tutorial.html#use-auto-loader-to-read-streaming-data-from-object-storage upvoted 2 times ... 55f31c8 1 year, 5 months ago Selected Answer: E Example from https://docs.databricks.com/en/structured-streaming/delta-lake.html spark.readStream.table("table_name") spark.readStream.load("/path/to/table") upvoted 4 times in89_io_90 1 year, 4 months ago have you cleared the exam upvoted 2 times ... ... meow_akk 1 year, 6 months ago Ans E; for streaming source you use readstream. https://docs.databricks.com/en/structured-streaming/delta-lake.html upvoted 3 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 79 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 79
Topic #: 1

[All Certified Data Engineer Associate Questions]

Which of the following queries is performing a streaming hop from raw data to a Bronze table? 
Suggested Answer: E 🗳️ 

A.

B.

C.

D.

E.

**Answer: E**

**Timestamp: Nov. 4, 2023, 6:25 a.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/125329-exam-certified-data-engineer-associate-topic-1-question-79/)

Comments: mokrani Highly Voted 1 year, 11 months ago Selected Answer: E answer E: Raw to Bronze is simply an integration of source data in the lakehouse without any schema needed nor extra operationss (e;g filtering, aggregation, joins etc..) Please refer to this Medaillon Architecture article https://www.databricks.com/glossary/medallion-architecture upvoted 6 times HelixAbdu 1 year, 3 months ago Yes E is correct. But There are filtering or aggregation in silver layer . We need to check if it have readstream and writestream upvoted 1 times ... ... benni_ale Most Recent 1 year, 6 months ago Selected Answer: E E is ok , all others are incorrect upvoted 1 times ... AndreFR 1 year, 10 months ago sourcename is “rawSalesLocation” (bronze tables contain raw data) and code includes “readStream” to indicate that it is a streaming hop upvoted 2 times ... 55f31c8 1 year, 11 months ago Selected Answer: E https://docs.databricks.com/en/lakehouse/medallion.html#ingest-raw-data-to-the-bronze-layer upvoted 2 times ... sodere 1 year, 11 months ago Answer is B upvoted 1 times hsks 1 year, 11 months ago Answer should be E. Filtering and cleaning usually happens from bronze to silver layer upvoted 4 times ... HelixAbdu 1 year, 3 months ago I think we should have read stream and writestream that should the important point upvoted 1 times ... ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 80 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 80
Topic #: 1

[All Certified Data Engineer Associate Questions]

A dataset has been defined using Delta Live Tables and includes an expectations clause:CONSTRAINT valid_timestamp EXPECT (timestamp > '2020-01-01') ON VIOLATION FAIL UPDATEWhat is the expected behavior when a batch of data containing data that violates these constraints is processed? 
Suggested Answer: B 🗳️ 

A. Records that violate the expectation are dropped from the target dataset and recorded as invalid in the event log.

B. Records that violate the expectation cause the job to fail.

C. Records that violate the expectation are dropped from the target dataset and loaded into a quarantine table.

D. Records that violate the expectation are added to the target dataset and recorded as invalid in the event log.

E. Records that violate the expectation are added to the target dataset and flagged as invalid in a field added to the target dataset.

**Answer: B**

**Timestamp: Oct. 22, 2023, 5:46 a.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/124308-exam-certified-data-engineer-associate-topic-1-question-80/)

Comments: CommanderBigMac 1 year, 1 month ago Selected Answer: B B is the way upvoted 1 times ... benni_ale 1 year, 6 months ago Selected Answer: B b is ok upvoted 1 times ... 55f31c8 1 year, 11 months ago Selected Answer: B https://docs.databricks.com/en/delta-live-tables/sql-ref.html#sql-properties ON VIOLATION Optional action to take for failed rows: FAIL UPDATE: Immediately stop pipeline execution. DROP ROW: Drop the record and continue processing. upvoted 3 times ... Bakhtiyor 1 year, 11 months ago ON VIOLATION FAIL UPDATE: Immediately stop pipeline execution. DROP ROW: Drop the record and continue processing. upvoted 2 times ... meow_akk 2 years ago Ans B : delta live tables data quality expectations . - https://docs.databricks.com/en/delta-live-tables/expectations.html Action Result warn (default) Invalid records are written to the target; failure is reported as a metric for the dataset. drop Invalid records are dropped before data is written to the target; failure is reported as a metrics for the dataset. fail Invalid records prevent the update from succeeding. Manual intervention is required before re-processing. upvoted 4 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 81 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 81
Topic #: 1

[All Certified Data Engineer Associate Questions]

Which of the following statements regarding the relationship between Silver tables and Bronze tables is always true? 
Suggested Answer: D 🗳️ 

A. Silver tables contain a less refined, less clean view of data than Bronze data.

B. Silver tables contain aggregates while Bronze data is unaggregated.

C. Silver tables contain more data than Bronze tables.

D. Silver tables contain a more refined and cleaner view of data than Bronze tables.

E. Silver tables contain less data than Bronze tables.

**Answer: D**

**Timestamp: Oct. 22, 2023, 5:47 a.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/124309-exam-certified-data-engineer-associate-topic-1-question-81/)

Comments: CommanderBigMac 1 year, 1 month ago Selected Answer: D Silver tables are used to clean the raw imported data from a bronze table upvoted 1 times ... benni_ale 1 year, 6 months ago Selected Answer: D d is ok upvoted 1 times ... azure_bimonster 1 year, 9 months ago Selected Answer: D D is the right answer upvoted 2 times ... meow_akk 2 years ago Ans D : medallion arch databricks https://www.databricks.com/glossary/medallion-architecture upvoted 2 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 82 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 82
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineering team has noticed that their Databricks SQL queries are running too slowly when they are submitted to a non-running SQL endpoint. The data engineering team wants this issue to be resolved.Which of the following approaches can the team use to reduce the time it takes to return results in this scenario? 
Suggested Answer: D 🗳️ 

A. They can turn on the Serverless feature for the SQL endpoint and change the Spot Instance Policy to "Reliability Optimized."

B. They can turn on the Auto Stop feature for the SQL endpoint.

C. They can increase the cluster size of the SQL endpoint.

D. They can turn on the Serverless feature for the SQL endpoint.

E. They can increase the maximum bound of the SQL endpoint's scaling range.

**Answer: D**

**Timestamp: Oct. 22, 2023, 5:52 a.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/124310-exam-certified-data-engineer-associate-topic-1-question-82/)

Comments: carpa_jo Highly Voted 1 year, 3 months ago Selected Answer: D The important point of this scenario is "when they are submitted to a non-running SQL endpoint". So its not about increasing the instance size or the amount of instances to improve the query performance, but its about reducing the start-up time. A: Not possible, serverless can't be combined with spot instance policies, see https://docs.databricks.com/en/compute/sql-warehouse/serverless.html#limitations B: Auto Stop is about terminating a SQL warehouse after x minutes of being idle. C: Increasing the cluster size provides more capacities for running queries, but doesn't reduce start-up time. D: Serverless reduces start-up time from minutes to seconds. Jackpot! E: Increasing the max bound of the SQL endpoints scaling range will help with lots of sequencial queries, which is not the case here. upvoted 19 times ... azure_bimonster Most Recent 1 year, 3 months ago Selected Answer: D D is correct. Key phrase is "submitted to a non-running SQL endpoint". Increasing cluster size is not going to help if that's in a state like non-running. upvoted 1 times ... bartfto 1 year, 3 months ago Selected Answer: D "when they are submitted to a non-running SQL endpoint" ANSWER D upvoted 1 times ... Garyn 1 year, 4 months ago Selected Answer: C C. They can increase the cluster size of the SQL endpoint. Explanation: Increasing the cluster size of the SQL endpoint can enhance query performance by providing more computational resources to execute queries. This can potentially speed up query processing by allowing more parallelism, handling larger workloads, and reducing the time taken for query execution. upvoted 2 times ... AndreFR 1 year, 4 months ago key word, “non-running SQL endpoint” which implies that the query is slow because the cluster needs time to get started. I suggest answer D because : A : Serverless & spot instances cannot be mixed ? B : autostop means that jobs are submitted to non-running SQL endpoints C : increasing the clustersize can compensate for slow startup time D : serverless is able to start and scale faster than non-running SQL endpoints (seconds intead of minutes) E : increasing maximum bound will help only if there are simultaneous queries https://docs.gcp.databricks.com/en/lakehouse-architecture/cost-optimization/best-practices.html#use-serverless-for-your-workloads upvoted 4 times ... olaru 1 year, 4 months ago Selected Answer: E maximum bound of the SQL endpoint's scaling range upvoted 2 times ... nedlo 1 year, 4 months ago Selected Answer: C D is wrong - its already Serverless (non running SQL endpoint) how would turning Serverless ON help? They also says C here https://community.databricks.com/t5/data-engineering/when-to-increase-maximum-bound-vs-when-to-increase-cluster-size/td-p/27880 . E is only true for autoscaling clusters upvoted 2 times ... msengupta 1 year, 4 months ago Selected Answer: C https://community.databricks.com/t5/data-engineering/sql-query-takes-too-long-to-run/td-p/21884 upvoted 2 times ... Syd 1 year, 6 months ago Answer E: https://www.databricks.com/blog/2022/03/10/top-5-databricks-performance-tips.html upvoted 2 times Syd 1 year, 6 months ago I mean answer C upvoted 1 times ... ... meow_akk 1 year, 6 months ago Ans E : you re welcome :) https://community.databricks.com/t5/data-engineering/when-to-increase-maximum-bound-vs-when-to-increase-cluster-size/td-p/27880 upvoted 1 times mike_stewart 1 year, 6 months ago I don't agree. Your answer is only valid when 'sequential' is mentioned, which is not the case here. upvoted 1 times ... ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 84 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 84
Topic #: 1

[All Certified Data Engineer Associate Questions]

Which of the following approaches should be used to send the Databricks Job owner an email in the case that the Job fails? 
Suggested Answer: B 🗳️ 

A. Manually programming in an alert system in each cell of the Notebook

B. Setting up an Alert in the Job page

C. Setting up an Alert in the Notebook

D. There is no way to notify the Job owner in the case of Job failure

E. MLflow Model Registry Webhooks

**Answer: B**

**Timestamp: Oct. 22, 2023, 5:55 a.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/124312-exam-certified-data-engineer-associate-topic-1-question-84/)

Comments: 80370eb 1 year, 2 months ago Selected Answer: B In Databricks, you can configure job notifications directly from the Jobs page, where you can specify that an email should be sent to the Job owner or other specified individuals in the case of Job failure. This is the most straightforward and automated way to ensure notifications are sent. upvoted 3 times ... Lavpak 1 year, 10 months ago Selected Answer: B Setting up an alert in Jobs page upvoted 2 times ... meow_akk 2 years ago Ans B : https://docs.databricks.com/en/workflows/jobs/job-notifications.html upvoted 3 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 87 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 87
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer has been using a Databricks SQL dashboard to monitor the cleanliness of the input data to a data analytics dashboard for a retail use case. The job has a Databricks SQL query that returns the number of store-level records where sales is equal to zero. The data engineer wants their entire team to be notified via a messaging webhook whenever this value is greater than 0.Which of the following approaches can the data engineer use to notify their entire team via a messaging webhook whenever the number of stores with $0 in sales is greater than zero? 
Suggested Answer: D 🗳️ 

A. They can set up an Alert with a custom template.

B. They can set up an Alert with a new email alert destination.

C. They can set up an Alert with one-time notifications.

D. They can set up an Alert with a new webhook alert destination.

E. They can set up an Alert without notifications.

**Answer: D**

**Timestamp: Oct. 22, 2023, 5:15 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/124346-exam-certified-data-engineer-associate-topic-1-question-87/)

Comments: azure_bimonster 1 year, 3 months ago Selected Answer: D D is the right answer here upvoted 1 times ... Lavpak 1 year, 4 months ago Selected Answer: D Set up an Alert with a new webhook alert destination upvoted 2 times ... meow_akk 1 year, 6 months ago Ans D : the questions specifically says via a messaging webhook upvoted 2 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 88 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 88
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer wants to schedule their Databricks SQL dashboard to refresh every hour, but they only want the associated SQL endpoint to be running when it is necessary. The dashboard has multiple queries on multiple datasets associated with it. The data that feeds the dashboard is automatically processed using a Databricks Job.Which of the following approaches can the data engineer use to minimize the total running time of the SQL endpoint used in the refresh schedule of their dashboard? 
Suggested Answer: A 🗳️ 

A. They can turn on the Auto Stop feature for the SQL endpoint.

B. They can ensure the dashboard's SQL endpoint is not one of the included query's SQL endpoint.

C. They can reduce the cluster size of the SQL endpoint.

D. They can ensure the dashboard's SQL endpoint matches each of the queries' SQL endpoints.

E. They can set up the dashboard's SQL endpoint to be serverless.

**Answer: A**

**Timestamp: Oct. 21, 2023, 12:21 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/124178-exam-certified-data-engineer-associate-topic-1-question-88/)

Comments: meow_akk Highly Voted 2 years ago Ans A : the keyword in the question is " running only when its necessary " upvoted 7 times ... 806e7d2 Most Recent 11 months, 1 week ago Selected Answer: E By using serverless SQL endpoints, Databricks automatically handles the provisioning and management of compute resources. This approach minimizes the total running time of the SQL endpoint because resources are only allocated when queries are actively running. After the query execution completes, the resources are automatically deallocated, which reduces cost and ensures efficiency. A. They can turn on the Auto Stop feature for the SQL endpoint: This can help reduce idle time, but it does not minimize running time as effectively as serverless SQL endpoints, which start instantly without manual configuration. upvoted 1 times ... hussamAlHunaiti 1 year, 4 months ago Selected Answer: A Answer is A. The question about minimize the total running times not enhance the performance. upvoted 1 times ... Lavpak 1 year, 10 months ago Selected Answer: A They can turn on the Auto Stop feature upvoted 2 times ... Huroye 1 year, 11 months ago The correct answer is A. They can use the Auto Stop feature. When the query is idel it will stop the compute upvoted 3 times ... SD5713 2 years ago Selected Answer: A A. They can turn on the Auto Stop feature for the SQL endpoint. upvoted 3 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 91 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 91
Topic #: 1

[All Certified Data Engineer Associate Questions]

Which data lakehouse feature results in improved data quality over a traditional data lake? 
Suggested Answer: D 🗳️ 

A. A data lakehouse stores data in open formats.

B. A data lakehouse allows the use of SQL queries to examine data.

C. A data lakehouse provides storage solutions for structured and unstructured data.

D. A data lakehouse supports ACID-compliant transactions.

**Answer: D**

**Timestamp: June 14, 2024, 1:42 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/142524-exam-certified-data-engineer-associate-topic-1-question-91/)

Comments: 80370eb 1 year, 2 months ago Selected Answer: D ACID-compliant transactions ensure that data operations are Atomic, Consistent, Isolated, and Durable. This greatly enhances data reliability, consistency, and quality compared to traditional data lakes, which typically lack strong transactional guarantees. upvoted 2 times ... 31cadd7 1 year, 4 months ago Selected Answer: D it's D upvoted 1 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 92 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 92
Topic #: 1

[All Certified Data Engineer Associate Questions]

In which scenario will a data team want to utilize cluster pools? 
Suggested Answer: C 🗳️ 

A. An automated report needs to be version-controlled across multiple collaborators.

B. An automated report needs to be runnable by all stakeholders.

C. An automated report needs to be refreshed as quickly as possible.

D. An automated report needs to be made reproducible.

**Answer: C**

**Timestamp: May 25, 2024, 8:11 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/141229-exam-certified-data-engineer-associate-topic-1-question-92/)

Comments: 80370eb 1 year, 2 months ago Selected Answer: C Cluster pools help in reducing the start-up time of clusters by maintaining a set of idle, ready-to-use instances. This allows jobs, such as automated reports, to start faster, ensuring that the report is refreshed as quickly as possible. upvoted 2 times ... MDWPartners 1 year, 5 months ago This question is repeated, a cluster pool helps to reduce the times of cold start and change the scaling . upvoted 3 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 93 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 93
Topic #: 1

[All Certified Data Engineer Associate Questions]

What is hosted completely in the control plane of the classic Databricks architecture? 
Suggested Answer: B 🗳️ 

A. Worker node

B. Databricks web application

C. Driver node

D. Databricks Filesystem

**Answer: B**

**Timestamp: Aug. 11, 2024, 3 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/145563-exam-certified-data-engineer-associate-topic-1-question-93/)

Comments: RandomForest 1 year ago Selected Answer: B The databricks web application is the only one that is completely hosted in the control plane. The others are hosted in the data plane. upvoted 1 times ... 80370eb 1 year, 2 months ago Selected Answer: B The Databricks web application, which includes the UI, job management, and other control functionalities, is hosted entirely in the control plane. The other components, such as worker nodes, driver nodes, and the Databricks Filesystem, are part of the data plane, which runs in the customer's cloud account. upvoted 1 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 94 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 94
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer needs to determine whether to use the built-in Databricks Notebooks versioning or version their project using Databricks Repos.What is an advantage of using Databricks Repos over the Databricks Notebooks versioning? 
Suggested Answer: D 🗳️ 

A. Databricks Repos allows users to revert to previous versions of a notebook

B. Databricks Repos is wholly housed within the Databricks Data Intelligence Platform

C. Databricks Repos provides the ability to comment on specific changes

D. Databricks Repos supports the use of multiple branches

**Answer: D**

**Timestamp: Sept. 20, 2024, 3:37 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/147886-exam-certified-data-engineer-associate-topic-1-question-94/)

Comments: e872ce8 7 months, 3 weeks ago Selected Answer: D Databricks Repos integrates with Git, allowing users to work with multiple branches. This enables collaborative development, feature branching, and version control, making it superior to the built-in Databricks Notebooks versioning, which only tracks notebook history without Git-based workflows. upvoted 1 times ... Stefan94 1 year, 1 month ago Selected Answer: D D is correct upvoted 1 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 95 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 95
Topic #: 1

[All Certified Data Engineer Associate Questions]

What is a benefit of the Databricks Lakehouse Architecture embracing open source technologies? 
Suggested Answer: A 🗳️ 

A. Avoiding vendor lock-in

B. Simplified governance

C. Ability to scale workloads

D. Cloud-specific integrations

**Answer: A**

**Timestamp: Aug. 11, 2024, 3:04 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/145564-exam-certified-data-engineer-associate-topic-1-question-95/)

Comments: Stefan94 1 year, 1 month ago Selected Answer: A A is Correct upvoted 1 times ... 80370eb 1 year, 2 months ago Selected Answer: A By using open-source technologies, Databricks allows organizations to avoid being tied to a single vendor's ecosystem, offering flexibility and interoperability across different platforms and tools. upvoted 1 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 96 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 96
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer needs to use a Delta table as part of a data pipeline, but they do not know if they have the appropriate permissions.In which location can the data engineer review their permissions on the table? 
Suggested Answer: C 🗳️ 

A. Jobs

B. Dashboards

C. Catalog Explorer

D. Repos

**Answer: C**

**Timestamp: Aug. 11, 2024, 3:06 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/145566-exam-certified-data-engineer-associate-topic-1-question-96/)

Comments: Stefan94 1 year, 1 month ago Selected Answer: C C is correct upvoted 1 times ... 80370eb 1 year, 2 months ago Selected Answer: C Catalog Explorer (also known as Data Explorer in Databricks) is where users can explore data assets like tables and databases and view permissions and metadata associated with those assets. upvoted 1 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 97 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 97
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer is running code in a Databricks Repo that is cloned from a central Git repository. A colleague of the data engineer informs them that changes have been made and synced to the central Git repository. The data engineer now needs to sync their Databricks Repo to get the changes from the central Git repository.Which Git operation does the data engineer need to run to accomplish this task? 
Suggested Answer: B 🗳️ 

A. Clone

B. Pull

C. Merge

D. Push

**Answer: B**

**Timestamp: May 25, 2024, 8:12 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/141230-exam-certified-data-engineer-associate-topic-1-question-97/)

Comments: CommanderBigMac 1 year, 1 month ago Selected Answer: B Have to pull the updated repo from Git upvoted 1 times ... MDWPartners 1 year, 5 months ago Repeated, also correct. upvoted 1 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 98 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 98
Topic #: 1

[All Certified Data Engineer Associate Questions]

Which file format is used for storing Delta Lake Table? 
Suggested Answer: B 🗳️ 

A. CSV

B. Parquet

C. JSON

D. Delta

**Answer: B**

**Timestamp: May 20, 2024, 10:37 a.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/140894-exam-certified-data-engineer-associate-topic-1-question-98/)

Comments: Soori567 8 months ago Selected Answer: B File format under Delta is parquet, answer is B upvoted 2 times ... LukeWroc 11 months, 4 weeks ago File format under Delta is parquet, answer is B upvoted 1 times ... SannPro 1 year, 5 months ago B is correct upvoted 2 times ... aspix82 1 year, 5 months ago The answer is D upvoted 1 times aspix82 1 year, 5 months ago No, file format is Parquet! The correct answer is B upvoted 1 times ... ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 99 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 99
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data architect has determined that a table of the following format is necessary:Which code block is used by SQL DDL command to create an empty Delta table in the above format regardless of whether a table already exists with this name? 
Suggested Answer: A 🗳️ 

A. CREATE OR REPLACE TABLE table_name ( employeeId STRING, startDate DATE, avgRating FLOAT )

B. CREATE OR REPLACE TABLE table_name WITH COLUMNS ( employeeId STRING, startDate DATE, avgRating FLOAT ) USING DELTA

C. CREATE TABLE IF NOT EXISTS table_name ( employeeId STRING, startDate DATE, avgRating FLOAT )

D. CREATE TABLE table_name AS SELECT employeeId STRING, startDate DATE, avgRating FLOAT

**Answer: A**

**Timestamp: May 25, 2024, 8:12 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/141231-exam-certified-data-engineer-associate-topic-1-question-99/)

Comments: Stefan94 1 year, 1 month ago Selected Answer: A Repeated, correct A upvoted 1 times ... CommanderBigMac 1 year, 1 month ago Selected Answer: A Answer is A upvoted 1 times ... MDWPartners 1 year, 5 months ago Repeated, correct. upvoted 2 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 100 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 100
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer has been given a new record of data:id STRING = 'a1'rank INTEGER = 6rating FLOAT = 9.4Which SQL commands can be used to append the new record to an existing Delta table my_table? 
Suggested Answer: A 🗳️ 

A. INSERT INTO my_table VALUES ('a1', 6, 9.4)

B. INSERT VALUES ('a1', 6, 9.4) INTO my_table

C. UPDATE my_table VALUES ('a1', 6, 9.4)

D. UPDATE VALUES ('a1', 6, 9.4) my_table

**Answer: A**

**Timestamp: May 25, 2024, 8:13 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/141232-exam-certified-data-engineer-associate-topic-1-question-100/)

Comments: MDWPartners 11 months ago Repeated, correct. upvoted 4 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 101 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 101
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer has realized that the data files associated with a Delta table are incredibly small. They want to compact the small files to form larger files to improve performance.Which keyword can be used to compact the small files? 
Suggested Answer: A 🗳️ 

A. OPTIMIZE

B. VACUUM

C. COMPACTION

D. REPARTITION

**Answer: A**

**Timestamp: May 25, 2024, 8:13 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/141233-exam-certified-data-engineer-associate-topic-1-question-101/)

Comments: Soori567 8 months, 1 week ago Selected Answer: A OPTIMIZE to compact multiple small files into larger ones upvoted 1 times ... kim32 1 year, 4 months ago The OPTIMIZE command is used to compact small files into larger ones, which helps improve the performance of Delta Lake tables. It consolidates small files into fewer larger files to reduce the overhead associated with having many small files. This process is often referred to as "compaction" but the specific keyword in Databricks Delta Lake is OPTIMIZE. upvoted 2 times ... MDWPartners 1 year, 5 months ago Repeated, correct. upvoted 1 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 102 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 102
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer wants to create a data entity from a couple of tables. The data entity must be used by other data engineers in other sessions. It also must be saved to a physical location.Which of the following data entities should the data engineer create? 
Suggested Answer: A 🗳️ 

A. Table

B. Function

C. View

D. Temporary view

**Answer: A**

**Timestamp: June 25, 2024, 3:10 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/142913-exam-certified-data-engineer-associate-topic-1-question-102/)

Comments: AG_IT 2 months ago Selected Answer: C ans is view , they are persistent , stored on physical storage upvoted 1 times SnaP891111 2 months ago Hey, a standard view does not store data physically on storage, it basically holds the SQL script that is run when that view is called. What you are talking about might fit under a Materialized View, which stores the data physically but needs to be refreshed. https://docs.databricks.com/aws/en/dlt/dbsql/materialized upvoted 2 times ... ... Gavin1272 4 months, 1 week ago Selected Answer: A The key part of the question is that it must be saved to a physical location, views are not saved to physical locations, they are logical objects. Answer is A. Table. upvoted 2 times ... AndreLAO 6 months, 1 week ago Selected Answer: A To persist data we need to create a table upvoted 2 times ... kowal02 7 months, 3 weeks ago Selected Answer: A You can create a table using CTAS: CREATE TABLE AS SELECT ... FROM ... and the results will be saved to a physical location. upvoted 1 times ... SrinivasR 8 months ago Selected Answer: C correct Answer is C View , as question say wants to create entity using couple of tables and that's needs to used by others, so i think Answer is C View. upvoted 1 times ... Yuvazz 1 year ago VIEW will not be physically like Meterialized VIEW. Answer is Table upvoted 3 times ... MohdAltaf19 1 year, 1 month ago Correct Answer is C As View is persited they are physically stored and accessable across cluster even when restarted or detactched . upvoted 3 times ... Dip1994 1 year, 4 months ago A is the correct answer as the question is asking for physical location upvoted 3 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 103 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 103
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer runs a statement every day to copy the previous day’s sales into the table transactions. Each day’s sales are in their own file in the location "/transactions/raw".Today, the data engineer runs the following command to complete this task:After running the command today, the data engineer notices that the number of records in table transactions has not changed.What explains why the statement might not have copied any new records into the table? 
Suggested Answer: C 🗳️ 

A. The format of the files to be copied were not included with the FORMAT_OPTIONS keyword.

B. The COPY INTO statement requires the table to be refreshed to view the copied rows.

C. The previous day’s file has already been copied into the table.

D. The PARQUET file format does not support COPY INTO.

**Answer: C**

**Timestamp: May 25, 2024, 8:14 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/141235-exam-certified-data-engineer-associate-topic-1-question-103/)

Comments: MDWPartners 11 months ago Repeated, correct. upvoted 4 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 104 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 104
Topic #: 1

[All Certified Data Engineer Associate Questions]

Which command can be used to write data into a Delta table while avoiding the writing of duplicate records? 
Suggested Answer: C 🗳️ 

A. DROP

B. INSERT

C. MERGE

D. APPEND

**Answer: C**

**Timestamp: May 25, 2024, 8:13 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/141234-exam-certified-data-engineer-associate-topic-1-question-104/)

Comments: CommanderBigMac 1 year, 1 month ago Selected Answer: C The Merge command checks for duplicates and ignores them upvoted 1 times ... MDWPartners 1 year, 5 months ago Repeated, correct. upvoted 3 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 105 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 105
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data analyst has created a Delta table sales that is used by the entire data analysis team. They want help from the data engineering team to implement a series of tests to ensure the data is clean. However, the data engineering team uses Python for its tests rather than SQL.Which command could the data engineering team use to access sales in PySpark? 
Suggested Answer: B 🗳️ 

A. SELECT * FROM sales

B. spark.table("sales")

C. spark.sql("sales")

D. spark.delta.table("sales")

**Answer: B**

**Timestamp: May 25, 2024, 8:14 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/141236-exam-certified-data-engineer-associate-topic-1-question-105/)

Comments: AG_IT 2 months ago Selected Answer: B spark.sql() is wrong syntax spark.table() is correct upvoted 1 times ... MDWPartners 11 months ago Repeated, correct. upvoted 3 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 106 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 106
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer has created a new database using the following command:CREATE DATABASE IF NOT EXISTS customer360;In which location will the customer360 database be located? 
Suggested Answer: B 🗳️ 

A. dbfs:/user/hive/database/customer360

B. dbfs:/user/hive/warehouse

C. dbfs:/user/hive/customer360

D. dbfs:/user/hive/database

**Answer: B**

**Timestamp: May 25, 2024, 8:14 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/141237-exam-certified-data-engineer-associate-topic-1-question-106/)

Comments: 806e7d2 11 months, 1 week ago Selected Answer: B It's duplicate for question we had before upvoted 3 times ... MDWPartners 1 year, 5 months ago Repeated, correct. upvoted 4 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 107 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 107
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer is attempting to drop a Spark SQL table my_table and runs the following command:DROP TABLE IF EXISTS my_table;After running this command, the engineer notices that the data files and metadata files have been deleted from the file system.What is the reason behind the deletion of all these files? 
Suggested Answer: A 🗳️ 

A. The table was managed

B. The table's data was smaller than 10 GB

C. The table did not have a location

D. The table was external

**Answer: A**

**Timestamp: May 9, 2024, 6:19 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/140233-exam-certified-data-engineer-associate-topic-1-question-107/)

Comments: alinavit 1 year ago Selected Answer: A A is correct upvoted 1 times ... Stefan94 1 year, 1 month ago Selected Answer: A Correct Answer is A upvoted 1 times ... 3fbc31b 1 year, 3 months ago Selected Answer: A The correct answer is A. BOTH data and metadata were deleted meaning the table was managed. If the metadata was gone, but the actual data files themselves were still there then it would be an external table. upvoted 3 times ... yolandi 1 year, 4 months ago also go with A upvoted 1 times ... 31cadd7 1 year, 4 months ago Selected Answer: A it's A upvoted 1 times ... THC1138 1 year, 5 months ago Selected Answer: A For D to be correct, the metadata would have been deleted, but the data would still exist. The answer is A upvoted 2 times ... PreranaC 1 year, 5 months ago Selected Answer: A A - Both Data was deleted as well along with Metadata upvoted 1 times ... Ivan_Petrov 1 year, 5 months ago Answer should be A as data was deleted table was managed upvoted 2 times ... jetplanes 1 year, 5 months ago Selected Answer: A The answer should be A --> the table was MANAGED. If the metadata and the underlined files have been deleted, then this is a MANAGED table and not an external table. upvoted 4 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 108 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 108
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer needs to create a table in Databricks using data from a CSV file at location /path/to/csv.They run the following command:Which of the following lines of code fills in the above blank to successfully complete the task? 
Suggested Answer: B 🗳️ 

A. FROM "path/to/csv"

B. USING CSV

C. FROM CSV

D. USING DELTA

**Answer: B**

**Timestamp: Sept. 12, 2024, 5:36 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/147416-exam-certified-data-engineer-associate-topic-1-question-108/)

Comments: CommanderBigMac 1 year, 1 month ago Selected Answer: B B: using csv is correct upvoted 2 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 109 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 109
Topic #: 1

[All Certified Data Engineer Associate Questions]

What is a benefit of creating an external table from Parquet rather than CSV when using a CREATE TABLE AS SELECT statement? 
Suggested Answer: C 🗳️ 

A. Parquet files can be partitioned

B. Parquet files will become Delta tables

C. Parquet files have a well-defined schema

D. Parquet files have the ability to be optimized

**Answer: C**

**Timestamp: May 14, 2024, 2:12 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/140622-exam-certified-data-engineer-associate-topic-1-question-109/)

Comments: RandomForest 1 year ago Selected Answer: C Parquet supports rich data types and enforces a schema, making it more suitable for structured data. CSV lacks schema enforcement and treats everything as plain text, which can lead to data parsing issues. upvoted 3 times ... MDWPartners 1 year, 5 months ago Selected Answer: C Parquetare columnar and can be optimized. However, I think the key part is " when using a CREATE TABLE AS SELECT statement?", that's C upvoted 3 times ... mgari 1 year, 5 months ago D partquet file are columnar and otimised upvoted 1 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 110 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 110
Topic #: 1

[All Certified Data Engineer Associate Questions]

Which SQL keyword can be used to convert a table from a long format to a wide format? 
Suggested Answer: B 🗳️ 

A. TRANSFORM

B. PIVOT

C. SUM

D. CONVERT

**Answer: B**

**Timestamp: Aug. 26, 2024, 10:30 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/146487-exam-certified-data-engineer-associate-topic-1-question-110/)

Comments: 9d4d68a 1 year, 2 months ago Answer is (B. PIVOT) The PIVOT keyword is used to transform rows into columns, converting data from a long format (where each row represents a single measurement) to a wide format (where multiple measurements are represented as columns). For example, if you have a table of sales data with columns for Date, Product, and Sales, you can use PIVOT to create a table where each Product has its own column, and sales are aggregated by Date. upvoted 4 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 111 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 111
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer has a Python variable table_name that they would like to use in a SQL query. They want to construct a Python code block that will run the query using table_name.They have the following incomplete code block:____(f"SELECT customer_id, spend FROM {table_name}")What can be used to fill in the blank to successfully complete the task? 
Suggested Answer: B 🗳️ 

A. spark.delta.sql

B. spark.sql

C. spark.table

D. dbutils.sql

**Answer: B**

**Timestamp: Sept. 20, 2024, 3:46 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/147887-exam-certified-data-engineer-associate-topic-1-question-111/)

Comments: Stefan94 1 year, 1 month ago Selected Answer: B B is correct upvoted 4 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 112 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 112
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer is working with two tables. Each of these tables is displayed below in its entirety.The data engineer runs the following query to join these tables together: 
Suggested Answer: C 🗳️ 

A.

B.

C.

D.

**Answer: C**

**Timestamp: May 22, 2024, 10:07 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/141061-exam-certified-data-engineer-associate-topic-1-question-112/)

Comments: CommanderBigMac Highly Voted 1 year, 1 month ago Selected Answer: C Answer is C, we're using a LEFT JOIN. upvoted 6 times ... vigaro Highly Voted 1 year, 4 months ago Selected Answer: C LEFT join. D is the result of a FULL join upvoted 5 times ... nescafe7 Most Recent 1 year, 4 months ago C - left outer join upvoted 2 times ... 31cadd7 1 year, 4 months ago Selected Answer: D IT'S D upvoted 1 times CommanderBigMac 1 year, 1 month ago D is the result of a full join, we're using a left join. Answer should be C. upvoted 2 times ... ... b79962e 1 year, 5 months ago Sorry wrong it is C for the left join upvoted 1 times ... b79962e 1 year, 5 months ago should be D upvoted 1 times PreranaC 1 year, 5 months ago LEFT JOIN so should be C upvoted 3 times ... ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 113 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 113
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer needs to apply custom logic to identify employees with more than 5 years of experience in array column employees in table stores. The custom logic should create a new column exp_employees that is an array of all of the employees with more than 5 years of experience for each row. In order to apply this custom logic at scale, the data engineer wants to use the FILTER higher-order function.Which code block successfully completes this task? 
Suggested Answer: A 🗳️ 

A.

B.

C.

D.

**Answer: A**

**Timestamp: Sept. 12, 2024, 5:50 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/147418-exam-certified-data-engineer-associate-topic-1-question-113/)

Comments: Hink 1 week, 1 day ago Selected Answer: A Just verified this hands-on, it's A. This one fetches a DataFrame where every employees in the array have more than 5 years experience: FILTER (employees, i -> i.years_exp > 5) AS Expected_Years This one fetches a DataFrame where every employees in the array have "L" in there name experience: FILTER (employees, i -> i.name like '%L%') AS Expected_Names upvoted 1 times ... 1199c00 1 month, 1 week ago Selected Answer: B Answer B, because that has the correct new column name and syntax upvoted 1 times ... Billybob0604 7 months, 1 week ago Selected Answer: A There s a lot of double questions in this exam upvoted 1 times ... CommanderBigMac 1 year, 1 month ago Selected Answer: A Answer is A, if for no other reason than it is the only correct syntax of filter. upvoted 3 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 114 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 114
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer that is new to using Python needs to create a Python function to add two integers together and return the sum?Which code block can the data engineer use to complete this task? 
Suggested Answer: D 🗳️ 

A.

B.

C.

D.

**Answer: D**

**Timestamp: May 9, 2024, 6:21 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/140234-exam-certified-data-engineer-associate-topic-1-question-114/)

Comments: analyticstraining 7 months, 3 weeks ago Selected Answer: D It's the same question as 66. Correct answer is D upvoted 2 times ... alinavit 1 year ago Selected Answer: D correct is D upvoted 2 times ... 80370eb 1 year, 2 months ago Selected Answer: D def function must have "return" present. upvoted 2 times ... 3fbc31b 1 year, 3 months ago Selected Answer: D For the function to perform the actions "RETURN" must be present. upvoted 2 times ... hussamAlHunaiti 1 year, 4 months ago Selected Answer: D Answer is D. upvoted 1 times ... nawfalbourass 1 year, 5 months ago Selected Answer: D RETURN is needed upvoted 2 times ... PreranaC 1 year, 5 months ago Selected Answer: D D, RETURN in Python needed upvoted 1 times ... Kunka 1 year, 5 months ago Answer is D. C is wrong answer, as it missed return key workd upvoted 1 times ... Ivan_Petrov 1 year, 5 months ago Correct answer is D upvoted 2 times ... helmerpaiva 1 year, 5 months ago Correct is D upvoted 3 times ... jetplanes 1 year, 5 months ago Selected Answer: D The correct answer is D because the python function needs to provide a return for the function, so C is incorrect. upvoted 2 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 115 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 115
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer has configured a Structured Streaming job to read from a table, manipulate the data, and then perform a streaming write into a new table.The code block used by the data engineer is below:Which line of code should the data engineer use to fill in the blank if the data engineer only wants the query to execute a micro-batch to process data every 5 seconds? 
Suggested Answer: D 🗳️ 

A. trigger("5 seconds")

B. trigger(continuous="5 seconds")

C. trigger(once="5 seconds")

D. trigger(processingTime="5 seconds")

**Answer: D**

**Timestamp: Aug. 27, 2024, 12:45 a.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/146490-exam-certified-data-engineer-associate-topic-1-question-115/)

Comments: CommanderBigMac 1 year, 1 month ago Selected Answer: D D is the correct answer upvoted 3 times ... 9d4d68a 1 year, 2 months ago Repeated, Correct upvoted 3 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 116 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 116
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer is maintaining a data pipeline. Upon data ingestion, the data engineer notices that the source data is starting to have a lower level of quality. The data engineer would like to automate the process of monitoring the quality level.Which of the following tools can the data engineer use to solve this problem? 
Suggested Answer: D 🗳️ 

A. Auto Loader

B. Unity Catalog

C. Delta Lake

D. Delta Live Tables

**Answer: D**

**Timestamp: Nov. 21, 2024, 10:21 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/151779-exam-certified-data-engineer-associate-topic-1-question-116/)

Comments: 806e7d2 11 months, 1 week ago Selected Answer: D Delta Live Tables (DLT) is specifically designed for building and maintaining reliable, automated data pipelines. It includes built-in data quality enforcement through expectations and constraints, which allows data engineers to: Define Data Quality Expectations: For example, you can define constraints such as CONSTRAINT valid_values EXPECT (column_name IS NOT NULL) to automatically enforce data quality rules. Monitor Violations: DLT tracks data quality metrics and logs violations, enabling monitoring of data quality trends over time. Automated Notifications and Actions: DLT can handle violations (e.g., drop rows, fail the pipeline, or log them for review) in an automated way. upvoted 3 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 117 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 117
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer has three tables in a Delta Live Tables (DLT) pipeline. They have configured the pipeline to drop invalid records at each table. They notice that some data is being dropped due to quality concerns at some point in the DLT pipeline. They would like to determine at which table in their pipeline the data is being dropped.Which approach can the data engineer take to identify the table that is dropping the records? 
Suggested Answer: D 🗳️ 

A. They can set up separate expectations for each table when developing their DLT pipeline.

B. They can navigate to the DLT pipeline page, click on the “Error” button, and review the present errors.

C. They can set up DLT to notify them via email when records are dropped.

D. They can navigate to the DLT pipeline page, click on each table, and view the data quality statistics.

**Answer: D**

**Timestamp: Aug. 27, 2024, 11:21 a.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/146531-exam-certified-data-engineer-associate-topic-1-question-117/)

Comments: 9d4d68a Highly Voted 1 year, 2 months ago Repeated, Correct upvoted 6 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 118 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 118
Topic #: 1

[All Certified Data Engineer Associate Questions]

What is used by Spark to record the offset range of the data being processed in each trigger in order for Structured Streaming to reliably track the exact progress of the processing so that it can handle any kind of failure by restarting and/or reprocessing? 
Suggested Answer: A 🗳️ 

A. Checkpointing and Write-ahead Logs

B. Replayable Sources and Idempotent Sinks

C. Write-ahead Logs and Idempotent Sinks

D. Checkpointing and Idempotent Sinks

**Answer: A**

**Timestamp: Aug. 27, 2024, 12:05 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/146534-exam-certified-data-engineer-associate-topic-1-question-118/)

Comments: Lili97 Highly Voted 7 months, 1 week ago Selected Answer: D Hello, is it usual to have duplicated questions? What is the point of paying if some questions are repeated? upvoted 7 times ... dantat Most Recent 1 week, 4 days ago Selected Answer: A In Apache Spark Structured Streaming, the system must track progress and recover from failures. To do that, it uses two key mechanisms: 1. Checkpointing Stores metadata such as: Offset ranges processed State information Execution plans Allows Spark to restart a streaming query exactly where it left off after a failure. 2. Write-ahead Logs (WAL) Before processing data, Spark records input data information in a write-ahead log. This ensures fault tolerance, because Spark can replay any batch that was in progress when a failure occurred. upvoted 3 times ... frankzyx 4 months, 1 week ago Selected Answer: A I got 100% today upvoted 3 times ... grygi 10 months, 1 week ago Selected Answer: A A is correct. I had this on the exam, from my results it seems so. I chose D and didn't max this area and I was sure of all other answers. upvoted 2 times ... MultiCloudIronMan 10 months, 2 weeks ago Selected Answer: D The correct answer is D. Checkpointing and Idempotent Sinks. In Structured Streaming, Spark uses checkpointing to reliably track the progress of the data being processed. Checkpointing saves the state of the streaming query, including the offset ranges of the data processed in each trigger. Idempotent sinks ensure that even if the same data is processed multiple times due to a failure and restart, the results remain consistent and correct. upvoted 2 times ... NzmD 11 months, 2 weeks ago Selected Answer: A Repeated! upvoted 2 times CaoMengde09 10 months ago Repeated and false. It’s D upvoted 1 times ... ... 9d4d68a 1 year, 2 months ago Repeated, Correct The correct answer is A. Checkpointing and Write-ahead Logs. Checkpointing records the progress of streaming queries, while write-ahead logs (WALs) capture the data before it is processed, allowing Spark to recover and process data reliably in case of failures. upvoted 3 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 119 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 119
Topic #: 1

[All Certified Data Engineer Associate Questions]

What describes the relationship between Gold tables and Silver tables? 
Suggested Answer: A 🗳️ 

A. Gold tables are more likely to contain aggregations than Silver tables.

B. Gold tables are more likely to contain valuable data than Silver tables.

C. Gold tables are more likely to contain a less refined view of data than Silver tables.

D. Gold tables are more likely to contain truthful data than Silver tables.

**Answer: A**

**Timestamp: Aug. 27, 2024, 12:02 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/146532-exam-certified-data-engineer-associate-topic-1-question-119/)

Comments: MyintZu 6 months ago Selected Answer: A Correct, but it's repeated question. upvoted 1 times ... MultiCloudIronMan 10 months, 2 weeks ago Selected Answer: A Gold is final stage to feed analytics platforms upvoted 1 times ... 9d4d68a 1 year, 2 months ago Repeated, Correct upvoted 2 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 120 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 120
Topic #: 1

[All Certified Data Engineer Associate Questions]

What describes when to use the CREATE STREAMING LIVE TABLE (formerly CREATE INCREMENTAL LIVE TABLE) syntax over the CREATE LIVE TABLE syntax when creating Delta Live Tables (DLT) tables using SQL? 
Suggested Answer: B 🗳️ 

A. CREATE STREAMING LIVE TABLE should be used when the subsequent step in the DLT pipeline is static.

B. CREATE STREAMING LIVE TABLE should be used when data needs to be processed incrementally.

C. CREATE STREAMING LIVE TABLE should be used when data needs to be processed through complicated aggregations.

D. CREATE STREAMING LIVE TABLE should be used when the previous step in the DLT pipeline is static.

**Answer: B**

**Timestamp: Aug. 27, 2024, 12:05 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/146533-exam-certified-data-engineer-associate-topic-1-question-120/)

Comments: AG_IT 2 months, 1 week ago Selected Answer: B B for streaming upvoted 1 times ... MultiCloudIronMan 10 months, 2 weeks ago Selected Answer: B Streaming data from source to destination upvoted 2 times ... 9d4d68a 1 year, 2 months ago Repeated, Correct upvoted 2 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 121 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 121
Topic #: 1

[All Certified Data Engineer Associate Questions]

A Delta Live Table pipeline includes two datasets defined using STREAMING LIVE TABLE. Three datasets are defined against Delta Lake table sources using LIVE TABLE.The table is configured to run in Production mode using the Continuous Pipeline Mode.What is the expected outcome after clicking Start to update the pipeline assuming previously unprocessed data exists and all definitions are valid? 
Suggested Answer: C 🗳️ 

A. All datasets will be updated at set intervals until the pipeline is shut down. The compute resources will persist to allow for additional testing.

B. All datasets will be updated once and the pipeline will shut down. The compute resources will persist to allow for additional testing.

C. All datasets will be updated at set intervals until the pipeline is shut down. The compute resources will be deployed for the update and terminated when the pipeline is stopped.

D. All datasets will be updated once and the pipeline will shut down. The compute resources will be terminated.

**Answer: C**

**Timestamp: Aug. 27, 2024, 12:15 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/146535-exam-certified-data-engineer-associate-topic-1-question-121/)

Comments: MultiCloudIronMan 10 months, 2 weeks ago Selected Answer: C Continuous Pipeline mode upvoted 2 times ... CommanderBigMac 1 year, 1 month ago Selected Answer: C Continuous Pipeline Mode in Production mode implies that the pipeline continuously processes incoming data updates at set intervals, ensuring the datasets are kept up-to-date as new data arrives. Since the pipeline is set to Continuous Pipeline Mode, it will keep running and updating the datasets until it is manually shut down. The compute resources are allocated dynamically to process and update the datasets as needed, and they will be terminated when the pipeline is stopped or shut down. This mode allows for real-time or near-real-time updates to the datasets from the streaming/live tables, ensuring that the data remains current and reflects the changes occurring in the data sources. upvoted 3 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 122 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 122
Topic #: 1

[All Certified Data Engineer Associate Questions]

Which type of workloads are compatible with Auto Loader? 
Suggested Answer: A 🗳️ 

A. Streaming workloads

B. Machine learning workloads

C. Serverless workloads

D. Batch workloads

**Answer: A**

**Timestamp: Oct. 18, 2024, 11:16 a.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/149736-exam-certified-data-engineer-associate-topic-1-question-122/)

Comments: Geera 8 months, 3 weeks ago Selected Answer: D A and D. Autoloader can also be used for batch processing by triggering once, so Autoloader is compatible with both streaming and batch workloads. upvoted 1 times ... MultiCloudIronMan 10 months, 2 weeks ago Selected Answer: A Near realtime data feed upvoted 2 times ... RandomForest 1 year ago Selected Answer: A Auto Loader is designed to ingest data continuously from data lakes and process it in real-time. It can efficiently handle streaming data by detecting and processing new files as they arrive. upvoted 3 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 123 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 123
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer has developed a data pipeline to ingest data from a JSON source using Auto Loader, but the engineer has not provided any type inference or schema hints in their pipeline. Upon reviewing the data, the data engineer has noticed that all of the columns in the target table are of the string type despite some of the fields only including float or boolean values.Why has Auto Loader inferred all of the columns to be of the string type? 
Suggested Answer: B 🗳️ 

A. Auto Loader cannot infer the schema of ingested data

B. JSON data is a text-based format

C. Auto Loader only works with string data

D. All of the fields had at least one null value

**Answer: B**

**Timestamp: July 19, 2024, 4:59 a.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/144151-exam-certified-data-engineer-associate-topic-1-question-123/)

Comments: RandomForest 1 year ago Selected Answer: B The correct answer is B as JSON files do not include datatypes upvoted 2 times ... csrazdan 1 year, 3 months ago Selected Answer: B JSON file does not include datatype and all columns are defaulted as string upvoted 2 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 124 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 124
Topic #: 1

[All Certified Data Engineer Associate Questions]

Which statement regarding the relationship between Silver tables and Bronze tables is always true? 
Suggested Answer: D 🗳️ 

A. Silver tables contain a less refined, less clean view of data than Bronze data.

B. Silver tables contain aggregates while Bronze data is unaggregated.

C. Silver tables contain more data than Bronze tables.

D. Silver tables contain less data than Bronze tables.

**Answer: D**

**Timestamp: May 10, 2024, 1:31 a.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/140248-exam-certified-data-engineer-associate-topic-1-question-124/)

Comments: Ivan_Petrov Highly Voted 1 year, 5 months ago looks like there is no correct answer. Shold be like A but Silver and Bronze should be changed in their places upvoted 13 times ... azurean Most Recent 4 months ago Selected Answer: D RAW -> BRONZE -> SILVER -> GOLD upvoted 1 times ... dadyman 4 months, 2 weeks ago Selected Answer: A A is correct upvoted 2 times azurean 4 months ago No way. RAW -> BRONZE -> SILVER -> GOLD upvoted 2 times ... ... CommanderBigMac 1 year, 1 month ago Selected Answer: D Silver table is the step of reducing and refining data after raw data was imported into bronze table. Gold table would be the last step where data aggregation is applied. upvoted 2 times ... 22d4d76 1 year, 2 months ago Cannot be D. If raw data are clean enough already and have no aggregations or other functions before to be in the silver table, there will be the same amount of data both side. A seems to be a better answer because from raw you will have more chance to make at least one transformation to refine data. upvoted 1 times ... 80370eb 1 year, 2 months ago Selected Answer: D D. Silver tables contain less data than Bronze tables. This is because Silver tables are typically more refined and processed versions of the raw data found in Bronze tables. Bronze tables often contain raw, unprocessed data, while Silver tables contain cleaned, filtered, or aggregated data. Therefore, Silver tables usually contain a subset or a refined version of the data in the Bronze tables, leading to less overall data in the Silver tables. upvoted 2 times ... vigaro 1 year, 4 months ago Selected Answer: D silver have some data filters upvoted 3 times ... mgari 1 year, 4 months ago in my opinion it is D Silver has only the data with no error upvoted 3 times ... b79962e 1 year, 5 months ago I think there is no correct answer upvoted 2 times ... PreranaC 1 year, 5 months ago Silver tables contain a more refined and cleaner view of data than Bronze tables. upvoted 3 times ... helmerpaiva 1 year, 5 months ago Correct is A upvoted 1 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 125 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 125
Topic #: 1

[All Certified Data Engineer Associate Questions]

Which query is performing a streaming hop from raw data to a Bronze table? 
Suggested Answer: D 🗳️ 

A.

B.

C.

D.

**Answer: D**

**Timestamp: Sept. 12, 2024, 6:08 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/147427-exam-certified-data-engineer-associate-topic-1-question-125/)

Comments: Vivekkpd 1 month, 1 week ago Selected Answer: D A streaming hop requires both readStream from a raw source and writeStream to the target table. upvoted 2 times ... azurean 4 months ago Selected Answer: D Correct answer is D upvoted 2 times ... Pankaj_Shet 11 months, 4 weeks ago Correct Answer is C. A and B are the aggregations There is no transformation in D. upvoted 2 times ... RandomForest 1 year ago Selected Answer: D Correct answer is D. upvoted 2 times ... CommanderBigMac 1 year, 1 month ago Selected Answer: D Question specified streaming hop. D input from raw and is writeStream. upvoted 3 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 126 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 126
Topic #: 1

[All Certified Data Engineer Associate Questions]

A dataset has been defined using Delta Live Tables and includes an expectations clause:CONSTRAINT valid_timestamp EXPECT (timestamp > '2020-01-01') ON VIOLATION DROP ROWWhat is the expected behavior when a batch of data containing data that violates these constraints is processed? 
Suggested Answer: C 🗳️ 

A. Records that violate the expectation cause the job to fail.

B. Records that violate the expectation are added to the target dataset and flagged as invalid in a field added to the target dataset.

C. Records that violate the expectation are dropped from the target dataset and recorded as invalid in the event log.

D. Records that violate the expectation are added to the target dataset and recorded as invalid in the event log.

**Answer: C**

**Timestamp: May 22, 2024, 10:03 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/141060-exam-certified-data-engineer-associate-topic-1-question-126/)

Comments: Hink 1 week, 1 day ago Selected Answer: C dropped from the target dataset and recorded as invalid in the event log. upvoted 1 times ... azurean 4 months ago Selected Answer: C C is the answer - Hint -> ON VIOLATION DROP ROW upvoted 2 times ... 9d4d68a 1 year, 2 months ago Repeated, Correct answer is C upvoted 2 times ... vigaro 1 year, 4 months ago Selected Answer: C ON VIOLATION DROP ROW upvoted 3 times ... 31cadd7 1 year, 4 months ago Selected Answer: C it's C upvoted 2 times ... d39c1db 1 year, 5 months ago C. Records that violate the expectation are dropped from the target dataset and recorded as invalid in the event log. When a constraint defined using the EXPECT clause is violated, Delta Live Tables will drop the records that violate the expectation from the target dataset. Additionally, information about the dropped records and the reason for their exclusion will be recorded in the event log for audit and monitoring purposes. This ensures that only valid data meeting the specified constraints is included in the target dataset. upvoted 3 times ... PreranaC 1 year, 5 months ago Selected Answer: C C should be correct, A is for ON VIOLATION FAIL UPDATE upvoted 2 times ... PreranaC 1 year, 5 months ago Selected Answer: A A should be correct upvoted 1 times MDWPartners 1 year, 5 months ago i don't agree, it shouldn't make the job to fail. upvoted 3 times ... ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 127 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 127
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer has a Job with multiple tasks that runs nightly. Each of the tasks runs slowly because the clusters take a long time to start.Which action can the data engineer perform to improve the start up time for the clusters used for the Job? 
Suggested Answer: D 🗳️ 

A. They can use endpoints available in Databricks SQL

B. They can use jobs clusters instead of all-purpose clusters

C. They can configure the clusters to autoscale for larger data sizes

D. They can use clusters that are from a cluster pool

**Answer: D**

**Timestamp: Aug. 26, 2024, 8:16 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/146479-exam-certified-data-engineer-associate-topic-1-question-127/)

Comments: MultiCloudIronMan 10 months, 2 weeks ago Selected Answer: D The correct answer is D. They can use clusters that are from a cluster pool. Using clusters from a cluster pool can significantly reduce the start-up time because the clusters are pre-configured and ready to be used, which eliminates the need to wait for new clusters to be created and started. upvoted 2 times ... RandomForest 1 year ago Selected Answer: D pools are a set of idle, ready-to-use instances hence minimizing start-up times upvoted 1 times ... 9d4d68a 1 year, 2 months ago Repeated, Correct upvoted 1 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 128 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 128
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer has a single-task Job that runs each morning before they begin working. After identifying an upstream data issue, they need to set up another task to run a new notebook prior to the original task.Which approach can the data engineer use to set up the new task? 
Suggested Answer: B 🗳️ 

A. They can clone the existing task in the existing Job and update it to run the new notebook.

B. They can create a new task in the existing Job and then add it as a dependency of the original task.

C. They can create a new task in the existing Job and then add the original task as a dependency of the new task.

D. They can create a new job from scratch and add both tasks to run concurrently.

**Answer: B**

**Timestamp: May 10, 2024, 2:56 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/140290-exam-certified-data-engineer-associate-topic-1-question-128/)

Comments: dantat 1 week, 4 days ago Selected Answer: C In Databricks Jobs, tasks can be connected using dependencies — meaning one task only runs after another finishes successfully. Here’s the situation: There’s already one task that runs every morning (the original notebook). The engineer needs to add a new notebook that should run before the original one (to fix or prepare upstream data). So, the logical flow is: New Task (fix upstream data) ↓ Original Task (daily processing) To achieve this: The new task should be added first in the dependency chain. The original task should depend on the new one. That’s exactly what option C describes. upvoted 1 times ... Billybob0604 7 months, 1 week ago Selected Answer: C No, a new notebook needs to be run prior to the original task meaning the original task depends on the new notebook, hence C. upvoted 1 times ... CommanderBigMac 1 year, 1 month ago Selected Answer: B B is correct. the new task needs to be the dependancy. upvoted 3 times ... 9d4d68a 1 year, 2 months ago Correct Answer: B Explanation: To set up the new task to run a new notebook prior to the original task in a single-task Job, the data engineer can use the following approach: In the existing Job, create a new task that corresponds to the new notebook that needs to be run. Set up the new task with the appropriate configuration, specifying the notebook to be executed and any necessary parameters or dependencies. Once the new task is created, designate it as a dependency of the original task in the Job configuration. This ensures that the new task is executed before the original task. upvoted 3 times ... hussamAlHunaiti 1 year, 4 months ago Selected Answer: B Answer is B. New task is prior than the original task. upvoted 2 times ... PreranaC 1 year, 5 months ago Selected Answer: B B is correct upvoted 2 times ... nmosq 1 year, 5 months ago B is correct, "needs to run prior to the original task" upvoted 2 times ... BharaniRaj 1 year, 5 months ago Selected Answer: B B is correct upvoted 2 times ... Kunka 1 year, 5 months ago B is correct, as new task runs first upvoted 2 times ... Ivan_Petrov 1 year, 5 months ago B is correct upvoted 1 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 129 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 129
Topic #: 1

[All Certified Data Engineer Associate Questions]

A single Job runs two notebooks as two separate tasks. A data engineer has noticed that one of the notebooks is running slowly in the Job’s current run. The data engineer asks a tech lead for help in identifying why this might be the case.Which approach can the tech lead use to identify why the notebook is running slowly as part of the Job? 
Suggested Answer: C 🗳️ 

A. They can navigate to the Runs tab in the Jobs UI to immediately review the processing notebook.

B. They can navigate to the Tasks tab in the Jobs UI and click on the active run to review the processing notebook.

C. They can navigate to the Runs tab in the Jobs UI and click on the active run to review the processing notebook.

D. They can navigate to the Tasks tab in the Jobs UI to immediately review the processing notebook.

**Answer: C**

**Timestamp: Aug. 26, 2024, 8:10 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/146477-exam-certified-data-engineer-associate-topic-1-question-129/)

Comments: MultiCloudIronMan 10 months, 2 weeks ago Selected Answer: C The correct answer is C. They can navigate to the Runs tab in the Jobs UI and click on the active run to review the processing notebook. This approach allows the tech lead to directly access and review the notebook that is currently running, helping to identify any issues causing it to run slowly. upvoted 1 times ... CommanderBigMac 1 year, 1 month ago Selected Answer: C Question states it is Running slowly, nothing is wrong with the job itself, so the Run needs to be checked. upvoted 2 times AG_IT 2 months ago correct upvoted 1 times ... ... 9d4d68a 1 year, 2 months ago Repeated, Correct upvoted 1 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 130 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 130
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data analysis team has noticed that their Databricks SQL queries are running too slowly when connected to their always-on SQL endpoint. They claim that this issue is present when many members of the team are running small queries simultaneously. They ask the data engineering team for help. The data engineering team notices that each of the team’s queries uses the same SQL endpoint.Which approach can the data engineering team use to improve the latency of the team’s queries? 
Suggested Answer: B 🗳️ 

A. They can increase the cluster size of the SQL endpoint.

B. They can increase the maximum bound of the SQL endpoint’s scaling range.

C. They can turn on the Auto Stop feature for the SQL endpoint.

D. They can turn on the Serverless feature for the SQL endpoint.

**Answer: B**

**Timestamp: Aug. 14, 2024, 6:11 a.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/145701-exam-certified-data-engineer-associate-topic-1-question-130/)

Comments: ramaireztreasure 2 months, 2 weeks ago Selected Answer: B By increasing the maximum bound, Databricks can add more clusters in parallel, allowing more users' queries to run concurrently with lower latency. upvoted 2 times ... azurean 4 months ago Selected Answer: B The scenario describes: Many small SQL queries being run simultaneously. A shared, always-on SQL endpoint. Performance degradation due to concurrent usage, not necessarily large queries. Why Option B is correct: SQL Endpoints in Databricks SQL support scaling ranges, which define how many concurrent clusters (or compute resources) can be spun up to handle query loads. By increasing the maximum bound, Databricks can add more clusters in parallel, allowing more users' queries to run concurrently with lower latency. This directly addresses the query queuing or slowdowns caused by multiple simultaneous users. upvoted 1 times ... Jugiboss 1 year ago Selected Answer: B It's always on, no need for serverless to speed up start-up. upvoted 4 times ... 7082935 1 year, 2 months ago Selected Answer: B The question states that the developers are connected to their "always-on" SQL Endpoint. This means there is no startup delay. We can increase performance of many simultaneous queries by scaling out. upvoted 2 times ... 9d4d68a 1 year, 2 months ago further, A. Increase the cluster size of the SQL endpoint: While increasing the cluster size might help if the current cluster size is insufficient, it does not necessarily address the scaling needs dynamically. The SQL endpoint might still be limited by its scaling configuration. C. Turn on the Auto Stop feature: Auto Stop helps manage costs by automatically stopping the SQL endpoint when it is idle. However, it doesn't address performance issues related to simultaneous query execution and would not improve query latency directly. D. Turn on the Serverless feature: The Serverless SQL endpoint is designed for ad-hoc querying without requiring dedicated clusters. While it could help in certain scenarios, it may not be directly applicable if the issue is specifically related to high concurrency and resource contention in an always-on environment. By increasing the scaling range, the SQL endpoint can handle more concurrent queries and improve overall performance. upvoted 1 times ... 9d4d68a 1 year, 2 months ago Given the scenario where the data analysis team is experiencing slow query performance due to multiple small queries running simultaneously on the same SQL endpoint, the best approach to improve the latency of these queries is: B. They can increase the maximum bound of the SQL endpoint’s scaling range. Here’s why this approach is suitable: Increasing the maximum bound of the SQL endpoint’s scaling range allows the SQL endpoint to scale out more resources as needed. If many users are running queries simultaneously, the increased scaling range ensures that additional compute resources are available to handle the load, which can reduce query latency and improve performance. Here's why the other options are less suitable: upvoted 1 times ... 80370eb 1 year, 2 months ago Selected Answer: D Turning on the Serverless feature allows the SQL endpoint to scale automatically and efficiently handle a large number of small queries, improving performance and reducing latency. upvoted 1 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 131 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 131
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer has been using a Databricks SQL dashboard to monitor the cleanliness of the input data to an ELT job. The ELT job has its Databricks SQL query that returns the number of input records containing unexpected NULL values. The data engineer wants their entire team to be notified via a messaging webhook whenever this value reaches 100.Which approach can the data engineer use to notify their entire team via a messaging webhook whenever the number of NULL values reaches 100? 
Suggested Answer: C 🗳️ 

A. They can set up an Alert with a custom template.

B. They can set up an Alert with a new email alert destination.

C. They can set up an Alert with a new webhook alert destination.

D. They can set up an Alert with one-time notifications.

**Answer: C**

**Timestamp: Aug. 26, 2024, 8:07 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/146476-exam-certified-data-engineer-associate-topic-1-question-131/)

Comments: azurean 4 months ago Selected Answer: C C is correct. Repeated question upvoted 2 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 132 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 90
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer wants to schedule their Databricks SQL dashboard to refresh once per day, but they only want the associated SQL endpoint to be running when it is necessary.Which approach can the data engineer use to minimize the total running time of the SQL endpoint used in the refresh schedule of their dashboard? 
Suggested Answer: C 🗳️ 

A. They can ensure the dashboard’s SQL endpoint matches each of the queries’ SQL endpoints.

B. They can set up the dashboard’s SQL endpoint to be serverless.

C. They can turn on the Auto Stop feature for the SQL endpoint.

D. They can ensure the dashboard’s SQL endpoint is not one of the included query’s SQL endpoint.

**Answer: C**

**Timestamp: Aug. 26, 2024, 8:07 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/146475-exam-certified-data-engineer-associate-topic-1-question-132/)

Comments: MultiCloudIronMan 10 months, 2 weeks ago Selected Answer: C The correct answer is C. They can turn on the Auto Stop feature for the SQL endpoint. This feature ensures that the SQL endpoint automatically stops when it is not in use, minimizing the total running time and reducing costs. upvoted 1 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 132 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 132
Topic #: 1

[All Certified Data Engineer Associate Questions]

A company uses Delta Sharing to collaborate with partners across different cloud providers and geographic regions.What will result in additional costs due to cross-region or egress fees? 
Suggested Answer: B 🗳️ 

A. Sharing data within the same cloud provider and region

B. Transferring data via Delta Sharing across clouds and across different geographic regions

C. Accessing Delta Sharing data using a VPN within the same data center

D. Utilizing Delta Sharing for internal data analytics within a single cloud environment

**Answer: B**

**Timestamp: Oct. 4, 2025, 9:01 a.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/313348-exam-certified-data-engineer-associate-topic-1-question-132/)

Comments: Hink 1 week ago Selected Answer: B When using Delta Sharing to transfer data across: Different cloud providers (e.g., AWS to Azure) Different geographic regions (e.g., EU to US) upvoted 1 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 133 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 86
Topic #: 1

[All Certified Data Engineer Associate Questions]

An engineering manager wants to monitor the performance of a recent project using a Databricks SQL query. For the first week following the project’s release, the manager wants the query results to be updated every minute. However, the manager is concerned that the compute resources used for the query will be left running and cost the organization a lot of money beyond the first week of the project’s release.Which approach can the engineering team use to ensure the query does not cost the organization any money beyond the first week of the project’s release? 
Suggested Answer: C 🗳️ 

A. They can set a limit to the number of DBUs that are consumed by the SQL Endpoint.

B. They can set the query’s refresh schedule to end after a certain number of refreshes.

C. They can set the query’s refresh schedule to end on a certain date in the query scheduler.

D. They can set a limit to the number of individuals that are able to manage the query’s refresh schedule.

**Answer: C**

**Timestamp: Aug. 26, 2024, 8:06 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/146474-exam-certified-data-engineer-associate-topic-1-question-133/)

Comments: Worldmaster 11 months ago Selected Answer: C C. They can set the query’s refresh schedule to end on a certain date in the query scheduler. This is the best solution. By setting the refresh schedule to automatically stop on a specific date (e.g., one week after the project release), the engineering team ensures that the query will only refresh during the desired period, preventing unnecessary costs after that date. This automated stopping of the refresh process avoids the need for manual intervention after the project’s first week. upvoted 1 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 134 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 85
Topic #: 1

[All Certified Data Engineer Associate Questions]

A new data engineering team has been assigned to work on a project. The team will need access to database customers in order to see what tables already exist. The team has its own group team.Which command can be used to grant the necessary permission on the entire database to the new team? 
Suggested Answer: D 🗳️ 

A. GRANT VIEW ON CATALOG customers TO team;

B. GRANT CREATE ON DATABASE customers TO team;

C. GRANT USAGE ON CATALOG team TO customers;

D. GRANT USAGE ON DATABASE customers TO team;

**Answer: D**

**Timestamp: Aug. 26, 2024, 8:05 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/146472-exam-certified-data-engineer-associate-topic-1-question-134/)

Comments: abbf4e9 1 week, 3 days ago Selected Answer: D Correct Answer: D. GRANT USAGE ON DATABASE customers TO team; Explanation: In Databricks Unity Catalog, access control is hierarchical — permissions cascade from Catalog → Schema (Database) → Table/View. To allow a group (like team) to see what tables already exist within a database (schema), the group must have the USAGE privilege on that database. What USAGE Does Grants the ability to view and reference objects in a catalog or database (schema). It does not allow querying or modifying data. With USAGE, the team can list tables and inspect schema metadata (i.e., see what exists). upvoted 2 times ... gs17 1 month, 3 weeks ago Selected Answer: D In Databricks (and generally in SQL-based permission models like ANSI SQL / Hive Metastore / Unity Catalog): To allow a group or user to see what tables exist in a database (but not query them yet), you must grant them the USAGE privilege on the database. USAGE on a database (or schema) = permission to list tables and objects inside it. upvoted 1 times ... d418ebf 2 months ago Selected Answer: D VIEW is not a valid privilege on a catalog in Databricks SQL. Also, catalogs are higher-level containers than databases, and this doesn’t grant visibility into tables within a specific database upvoted 1 times ... dnanan4u 4 months, 1 week ago Selected Answer: A I feel A is correct upvoted 1 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 135 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 83
Topic #: 1

[All Certified Data Engineer Associate Questions]

A new data engineering team team has been assigned to an ELT project. The new data engineering team will need full privileges on the table sales to fully manage the project.Which command can be used to grant full permissions on the database to the new data engineering team? 
Suggested Answer: A 🗳️ 

A. GRANT ALL PRIVILEGES ON TABLE sales TO team;

B. GRANT SELECT CREATE MODIFY ON TABLE sales TO team;

C. GRANT SELECT ON TABLE sales TO team;

D. GRANT ALL PRIVILEGES ON TABLE team TO sales;

**Answer: A**

**Timestamp: Aug. 26, 2024, 8:05 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/146471-exam-certified-data-engineer-associate-topic-1-question-135/)

Comments: CommanderBigMac 1 year, 1 month ago Selected Answer: A A is correct. Grant all on table sales to team, not table team to sales. upvoted 2 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 136 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 136
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer needs to develop integration tests for an ETL process and deploy a version-controlled, packaged workflow into production using an external job scheduler.Which tool should the data engineer use for this job? 
Suggested Answer: B 🗳️ 

A. Databricks Connect

B. Databricks Asset Bundles

C. Databricks Command Line Interface

D. Databricks Software Development Kit

**Answer: B**

**Timestamp: Oct. 4, 2025, 9 a.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/313342-exam-certified-data-engineer-associate-topic-1-question-136/)

Comments: Hink 1 week ago Selected Answer: B Databricks Asset Bundles (DABs) are designed for: Version-controlled packaging of workflows, notebooks, libraries, and configurations. Integration testing of ETL pipelines. Deployment into production environments using external job schedulers like Apache Airflow, GitHub Actions, or Azure Data Factory. They allow data engineers to define their workflows as code (YAML), making them reproducible, testable, and deployable across environments. upvoted 2 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 136 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 77
Topic #: 1

[All Certified Data Engineer Associate Questions]

Differentiate between all-purpose clusters and jobs clusters.A data engineering team has created a python notebook to load data from cloud storage, this job has been tested and now needs to be scheduled in production.Which would be the best cluster to be used in this case? 
Suggested Answer: C 🗳️ 

A. All purpose cluster

B. Any Unity Catalog-enabled cluster

C. Jobs Cluster

D. Serverless SQL warehouse

**Answer: C**

**Timestamp: Dec. 1, 2024, 3 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/152427-exam-certified-data-engineer-associate-topic-1-question-136/)

Comments: MultiCloudIronMan 10 months, 2 weeks ago Selected Answer: C Jobs clusters, on the other hand, are designed specifically for running production jobs. They are ephemeral, meaning they are created when a job starts and terminated when the job completes. This makes them more cost-effective for scheduled jobs, as they do not incur costs when not in use. upvoted 2 times ... Worldmaster 11 months ago Selected Answer: C Jobs clusters are specifically designed to run scheduled jobs in a production environment. They are ephemeral, meaning they are created when a job starts and terminated once the job finishes. This makes them cost-efficient and optimized for batch processing. upvoted 1 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 137 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 137
Topic #: 1

[All Certified Data Engineer Associate Questions]

Which Databricks asset bundle format is valid? 
Suggested Answer: A 🗳️ 

A. resources: jobs: hello-job: name: hello-job tasks: - task_key: hello-task existing_cluster_id: 1234-567890-abcde123 notebook_task: notebook_path: ./hello.py

B. "resources":{ "jobs":{ "name":"hello-job", "tasks":{ "task_key:"hello-task", "existing_cluster_id":"1234-567890-abcde123", "notebook_task":{ "notebook_path": ".hello.py" } } }

C. configuration = { "resources":{ "jobs":{ "name":"hello-job", "tasks":{ "task_key:"hello-task", "existing_cluster_id":"1234-567890-abcde123", "notebook_task":{ "notebook_path": ".hello.py" } } } }

D. resources { jobs { name = "hello-job" tasks{ task_key = "hello-task" existing_cluster_id = "1234-567890-abcde123" notebook_task{ notebook_path = ".hello.py" } } } }

**Answer: A**

**Timestamp: Sept. 10, 2025, 10:32 a.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/312265-exam-certified-data-engineer-associate-topic-1-question-137/)

Comments: INDEAVR_2025 1 week, 1 day ago Selected Answer: A A. YAML format → Correct Answer B. JSON → Databricks Asset Bundles do not use JSON. C. Python dictionary → Not supported in databricks.yml. D. HCL-like syntax → Not supported; that looks like Terraform syntax. upvoted 1 times ... ADFMDS 1 month, 2 weeks ago Selected Answer: A A. YAML format starting with resources: jobs: upvoted 2 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 137 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 75
Topic #: 1

[All Certified Data Engineer Associate Questions]

Identify how the count_if function and the count where x is null can be usedConsider a table random_values with below data.What would be the output of below query?select count_if(col > 1) as count_a. count(*) as count_b.count(col1) as count_c from random_values col1012NULL -23 
Suggested Answer: A 🗳️ 

A. 3 6 5

B. 4 6 5

C. 3 6 6

D. 4 6 6

**Answer: A**

**Timestamp: Oct. 19, 2024, 6:31 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/149798-exam-certified-data-engineer-associate-topic-1-question-137/)

Comments: MultiCloudIronMan Highly Voted 10 months, 2 weeks ago Selected Answer: A count_if(col > 1): There are 3 values greater than 1 (2, 2, 3), so count_a is 3. count()*: There are 6 rows in total, so count_b is 6. count(col1): There are 5 non-null values (0, 1, 2, 2, 3), so count_c is 5. upvoted 9 times ... Sagnikcap Most Recent 8 months, 2 weeks ago Selected Answer: A Sorry but the question is not presented properly. I think it should be written like this:- select count_if(col > 1) as count_a, count(*) as count_b,count(col) as count_c from random_values upvoted 4 times ... jimboslims 1 year ago table random_values with data not provided. there is no screenshot of the table. upvoted 2 times renshoo_shimasho 12 months ago It's a formatting issue. The table has exactly 1 column named "col1". The power of adding in a carriage return and line feed. Definitely get why it was difficult to figure out. upvoted 2 times ... ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 138 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 74
Topic #: 1

[All Certified Data Engineer Associate Questions]

Which two components function in the DB platform architecture’s control plane? (Choose two.) 
Suggested Answer: BE 🗳️ 

A. Virtual Machines

B. Compute Orchestration

C. Serverless Compute

D. Compute

E. Unity Catalog

**Answer: B**

**Timestamp: Oct. 19, 2024, 6:32 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/149799-exam-certified-data-engineer-associate-topic-1-question-138/)

Comments: MultiCloudIronMan 10 months, 2 weeks ago Selected Answer: BE The correct answers are B. Compute Orchestration and E. Unity Catalog. These components function in the control plane of the Databricks platform architecture. Compute Orchestration manages the lifecycle and scheduling of clusters, while Unity Catalog provides centralized governance for data and AI assets. upvoted 2 times ... jimboslims 1 year ago some ambiguity here. the answer can be D&E considering we see "Compute" and not "Compute Orchestration" on the Databricks control plane. upvoted 1 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 139 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 70
Topic #: 1

[All Certified Data Engineer Associate Questions]

In a healthcare provider organization using Delta Lake to store electronic health records (EHRs), a data analyst needs to analyze a snapshot of the patient_records table from two weeks ago before some recent data corrections were applied.What approach should the Data Engineer take to allow the analyst to query that specific prior version? 
Suggested Answer: B 🗳️ 

A. Truncate the table to remove all data, then reload the data from two weeks ago into the truncated table for the analyst to query.

B. Identify the version number corresponding to two weeks ago from the Delta transaction log, share that version number with the analyst to query using VERSION AS OF syntax, or export that version to a new Delta table for the analyst to query.

C. Restore the table to the version from two weeks ago using the RESTORE command, and have the analyst query the restored table.

D. Use the VACUUM command to remove all versions of the table older than two weeks, then the analyst can query the remaining version.

**Answer: B**

**Timestamp: Oct. 21, 2024, 2:09 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/149954-exam-certified-data-engineer-associate-topic-1-question-139/)

Comments: MultiCloudIronMan 10 months, 2 weeks ago Selected Answer: B We don't want to change the current table upvoted 2 times ... Manish_Kum 10 months, 3 weeks ago Selected Answer: B B is correct upvoted 1 times ... RandomForest 1 year ago Selected Answer: B B is the only correct answer as we do not want to remove any data. upvoted 1 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 140 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 69
Topic #: 1

[All Certified Data Engineer Associate Questions]

What can be used to simplify and unify siloed data architectures that are specialized for specific use cases? 
Suggested Answer: D 🗳️ 

A. Delta Lake

B. Data lake

C. Data warehouse

D. Data lakehouse

**Answer: D**

**Timestamp: Dec. 1, 2024, 3:03 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/152428-exam-certified-data-engineer-associate-topic-1-question-140/)

Comments: MultiCloudIronMan 10 months, 2 weeks ago Selected Answer: D To simplify and unify siloed data architectures that are specialized for specific use cases, the best approach is to use a data lakehouse. A data lakehouse combines the best features of data lakes and data warehouses, providing a single platform for all data use cases. This helps to streamline and integrate various data architectures, making it easier to manage and analyze data. upvoted 2 times ... Manish_Kum 10 months, 3 weeks ago Selected Answer: D Data Lakehouse upvoted 2 times ... Worldmaster 11 months ago Selected Answer: D D. Data lakehouse upvoted 2 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 141 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 67
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer has configured a Structured Streaming job to read from a table, manipulate the data, and then perform a streaming write into a new table.The code block used by the data engineer is below:The data engineer only wants the query to process all of the available data in as many batches as required.Which line of code should the data engineer use to fill in the blank? 
Suggested Answer: A 🗳️ 

A. trigger(availableNow=True)

B. trigger(processingTime= “once”)

C. trigger(continuous= “once”)

D. trigger(once=True)

**Answer: A**

**Timestamp: Oct. 27, 2024, 8:49 a.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/150350-exam-certified-data-engineer-associate-topic-1-question-141/)

Comments: comoon Highly Voted 1 year ago A is correct. upvoted 6 times ... hakimipous Most Recent 11 months, 1 week ago Selected Answer: A A is correct upvoted 1 times ... lj114 11 months, 2 weeks ago Selected Answer: A A is correct. Similar to queries one-time micro-batch trigger, the query will process all the available data and then stop on its own. The difference is that, it will process the data in (possibly) multiple micro-batches based on the source options upvoted 2 times ... rsmf 11 months, 4 weeks ago Selected Answer: A Correct is A upvoted 2 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 142 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 142
Topic #: 1

[All Certified Data Engineer Associate Questions]

An organization has data stored across multiple external systems, including MySQL, Amazon Redshift, and Google BigQuery. The data engineer wants to perform analytics without ingesting directly into Databricks, ensuring unified governance and minimizing data duplication.Which feature of Databricks enables querying these external data sources while maintaining centralized governance? 
Suggested Answer: B 🗳️ 

A. Delta Lake

B. Lakehouse Federation

C. MLflow

D. Databricks Connect

**Answer: B**

**Timestamp: Oct. 4, 2025, 8:52 a.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/313334-exam-certified-data-engineer-associate-topic-1-question-142/)

Comments: Hink 6 days, 8 hours ago Selected Answer: B Lakehouse Federation is a Databricks feature that allows you to query external data sources like MySQL, Amazon Redshift, and Google BigQuery without ingesting the data into Databricks. Sample query: SELECT bq.sales_region, mysql.customer_sentiment, redshift.inventory_level FROM bigquery_catalog.sales_data bq JOIN mysql_catalog.feedback_data mysql ON bq.customer_id = mysql.customer_id JOIN redshift_catalog.inventory_data redshift ON bq.product_id = redshift.product_id WHERE bq.sales_date >= '2025-01-01'; upvoted 1 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 142 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 65
Topic #: 1

[All Certified Data Engineer Associate Questions]

Data engineer and data analysts are working together on a data pipeline. The data engineer is working on the raw, bronze, and silver layers of the pipeline using Python, and the data analyst is working on the gold layer of the pipeline using SQL. The raw source of the pipeline is a streaming input. They now want to migrate their pipeline to use Delta Live Tables.Which of the following changes will need to be made to the pipeline when migrating to Delta Live Tables? 
Suggested Answer: A 🗳️ 

A. The pipeline can have different notebook sources in SQL & Python

B. The pipeline will need to be written entirely in SQL

C. The pipeline will need to use a batch source in place of a streaming source

D. The pipeline will need to be written entirely in Python

**Answer: A**

**Timestamp: Nov. 2, 2024, 12:08 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/150641-exam-certified-data-engineer-associate-topic-1-question-142/)

Comments: MultiCloudIronMan Highly Voted 10 months, 2 weeks ago Selected Answer: A The correct answer is A. The pipeline can have different notebook sources in SQL & Python. Delta Live Tables supports both SQL and Python, as well as streaming and batch sources. Therefore, the existing pipeline can continue to use both SQL and Python for different layers without needing to be rewritten entirely in one language or switching from a streaming to a batch source. upvoted 5 times ... SPD369 Most Recent 3 months ago Selected Answer: A Cross checked this answer.. upvoted 1 times ... Worldmaster 10 months, 3 weeks ago Selected Answer: A Imho A is correct upvoted 1 times ... rsmf 11 months, 4 weeks ago Selected Answer: C C is correct upvoted 1 times ... comoon 12 months ago C is correct upvoted 1 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 143 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 64
Topic #: 1

[All Certified Data Engineer Associate Questions]

Identify a scenario to use an external table.A Data Engineer needs to create a parquet bronze table and wants to ensure that it gets stored in a specific path in an external location.Which table can be created in this scenario? 
Suggested Answer: A 🗳️ 

A. An external table where the location is pointing to specific path in external location.

B. An external table where the schema has managed location pointing to specific path in external location.

C. A managed table where the catalog has managed location pointing to specific path in external location.

D. A managed table where the location is pointing to specific path in external location.

**Answer: A**

**Timestamp: Dec. 1, 2024, 3:06 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/152431-exam-certified-data-engineer-associate-topic-1-question-143/)

Comments: MultiCloudIronMan 10 months, 2 weeks ago Selected Answer: A The correct answer is A. An external table where the location is pointing to specific path in external location. This allows the data engineer to specify the exact path in an external location where the Parquet bronze table will be stored. upvoted 2 times ... Worldmaster 11 months ago Selected Answer: A A. It defines an external table where the data is stored at a specific path in an external location (such as cloud storage). The path is provided when the table is created. This matches the requirement to store the Parquet data in an external location, ensuring the data is managed externally, which is the core characteristic of an external table. upvoted 2 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 144 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 63
Topic #: 1

[All Certified Data Engineer Associate Questions]

Identify the impact of ON VIOLATION DROP ROW and ON VIOLATION FAIL UPDATE for a constraint violation.A data engineer has created an ETL pipeline using Delta Live table to manage their company travel reimbursement detail, they want to ensure that the if the location details has not been provided by the employee, the pipeline needs to be terminated.How can the scenario be implemented? 
Suggested Answer: B 🗳️ 

A. CONSTRAINT valid_location EXPECT (location = NULL)

B. CONSTRAINT valid_location EXPECT (location != NULL) ON VIOLATION FAIL UPDATE

C. CONSTRAINT valid_location EXPECT (location != NULL) ON DROP ROW

D. CONSTRAINT valid_location EXPECT (location != NULL) ON VIOLATION FAIL

**Answer: B**

**Timestamp: Oct. 26, 2024, 9:52 a.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/150282-exam-certified-data-engineer-associate-topic-1-question-144/)

Comments: san089 10 months, 2 weeks ago Selected Answer: B Correct Answer: B From Databricks doc CONSTRAINT valid_count EXPECT (count > 0) ON VIOLATION FAIL UPDATE upvoted 1 times ... MultiCloudIronMan 10 months, 2 weeks ago Selected Answer: D The correct answer is D. CONSTRAINT valid_location EXPECT (location != NULL) ON VIOLATION FAIL. This constraint ensures that if the location details are not provided by the employee (i.e., location is null), the pipeline will be terminated. upvoted 1 times ... canada_2k1 10 months, 3 weeks ago Selected Answer: B The answer from Udemy course upvoted 2 times ... knightkkd 10 months, 3 weeks ago Selected Answer: B FAIL UPDATE: Immediately stop pipeline execution. https://learn.microsoft.com/en-us/azure/databricks/delta-live-tables/expectations#fail upvoted 1 times ... Worldmaster 11 months ago Selected Answer: B B is correct https://docs.databricks.com/en/delta-live-tables/sql-ref.html ON VIOLATION Optional action to take for failed rows: FAIL UPDATE: Immediately stop pipeline execution. DROP ROW: Drop the record and continue processing. upvoted 2 times ... rsmf 11 months, 4 weeks ago Selected Answer: D D is correct upvoted 1 times CaoMengde09 10 months ago There is no such a thing as ON VIOLATION FAIL. We have only 3 behaviour to trigger when a constraint is being violated, and they fall under those syntaxes : --> ON VIOLATION FAIL UPDATE : The pipeline fails once it detects the first violation --> ON VIOLATION DROP ROW : The pipeline won't fail but the failing rows will be flagged and stored in event log --> If you put nothing after the expectation : The rows that violates the expectation will be loaded to the sink (Since Databricks doesn't enforce classical database constraints) and the rows will be flagged in the event log. B is the best answer, if you're not convinced try to run D in a notebook and you'll get a syntax error upvoted 2 times ... ... comoon 1 year ago D is correct upvoted 2 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 144 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 144
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer streams customer orders into a Kafka topic (orders_topic) and is currently writing the ingestion script of a DLT pipeline. The data engineer needs to ingest the data from Kafka brokers to DLT using Databricks.What is the correct code for ingesting the data? 
Suggested Answer: A 🗳️ 

A.

B.

C.

D.

**Answer: A**

**Timestamp: Sept. 21, 2025, 11:16 a.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/312875-exam-certified-data-engineer-associate-topic-1-question-144/)

Comments: e671267 3 weeks, 4 days ago Selected Answer: A A is the only one with correct syntax. B is using autoloader not kafka C has incorrect syntax, stream must be created and queried after D is trying something not possible upvoted 1 times ... gs17 1 month ago Selected Answer: A Correct answer is A. C is incorrect. This SQL syntax looks like Structured Streaming SQL, but in DLT SQL, Kafka must be configured as an external streaming source. As written, STREAM kafka... is not valid DLT SQL ingestion. upvoted 1 times ... Vivekkpd 1 month, 1 week ago Selected Answer: A in Delta Live Tables (DLT) with Python, to ingest from Kafka, you use: spark.readStream.format("kafka") to read from Kafka. DLT Python decorator @dlt.table to define the table. Specify Kafka bootstrap servers and topic. Use startingOffsets to control where to start reading (earliest in this case). Why the other options are incorrect: B. Uses cloud_files, which is for file-based sources (like JSON/CSV in cloud storage), not Kafka. C. SQL syntax is invalid; the STREAM keyword and Kafka source URL are incorrect. D. Tries to use cloud_files for Kafka, which is not supported; Kafka must use readStream.format("kafka"). upvoted 2 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 145 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 89
Topic #: 1

[All Certified Data Engineer Associate Questions]

Which two conditions are applicable for governance in Databricks Unity Catalog? (Choose two.) 
Suggested Answer: AE 🗳️ 

A. You can have more than 1 metastore within a databricks account console but only 1 per region.

B. Both catalog and schema must have a managed location in Unity Catalog provided metastore is not associated with a location

C. You can have multiple catalogs within metastore and 1 catalog can be associated with multiple metastore

D. If catalog is not associated with location, it’s mandatory to associate schema with managed locations

E. If metastore is not associated with location, it’s mandatory to associate catalog with managed locations

**Answer: A**

**Timestamp: Oct. 26, 2024, 9:51 a.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/150281-exam-certified-data-engineer-associate-topic-1-question-145/)

Comments: frankzyx 4 months, 1 week ago Selected Answer: AE I just got 100% today upvoted 2 times ... CaoMengde09 10 months ago Selected Answer: AE Databricks recommends that you assign managed storage at the catalog level for logical data isolation, with metastore-level and schema-level as options. New workspaces that are enabled for Unity Catalog automatically are created without a metastore-level managed storage location. It means that it's a must to create a managed location for a catalog for otpimal data isolations, otherwise you'll finish up with many schemas/tables data in the same managed location which is a bad prctice from governance perspective. Working with not isolated catalog in Unity Catalog is chaotic, i would prefer to be on my workspace rather than working in such bad governed Unity Catalog. Ans : ["A", "E"] upvoted 3 times ... grygi 10 months, 1 week ago Selected Answer: AD Had this on the exam. AD was correct, I maxed this area. upvoted 3 times ... MultiCloudIronMan 10 months, 2 weeks ago Selected Answer: AE The correct answers are A. You can have more than 1 metastore within a Databricks account console but only 1 per region and E. If metastore is not associated with location, it’s mandatory to associate catalog with managed locations. These conditions are applicable for governance in Databricks Unity Catalog upvoted 2 times ... sakis213 11 months ago Selected Answer: AD D. If catalog is not associated with location, it’s mandatory to associate schema with managed locations upvoted 1 times ... 806e7d2 11 months, 1 week ago Selected Answer: AE A. You can have more than 1 metastore within a Databricks account console but only 1 per region. Unity Catalog allows multiple metastores within a Databricks account console. However, each region can only have one active metastore due to geographic restrictions and for managing data governance in a region-specific manner. E. If metastore is not associated with location, it’s mandatory to associate catalog with managed locations. When a metastore does not have a default storage location, you must configure managed locations for each catalog to ensure governance and compliance. Managed locations define where Unity Catalog manages and stores data. upvoted 2 times sakis213 11 months ago Metastore must hv a managed location defined. AD is correct upvoted 1 times ... ... comoon 1 year ago Correct - A and D. A.Unity Catalog allows you to have multiple metastores within a single Databricks account, but each metastore is limited to a single region for data locality and compliance purposes. D. When a catalog does not have an associated managed location, it becomes necessary to associate schemas within the catalog with managed locations, ensuring that data is stored in a defined path. upvoted 3 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 146 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 61
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer needs to access the view created by the sales team, using a shared cluster. The data engineer has been provided usage permissions on the catalog and schema. In order to access the view created by sales team.What are the minimum permissions the data engineer would require in addition? 
Suggested Answer: B 🗳️ 

A. Needs SELECT permission on the VIEW and the underlying TABLE.

B. Needs SELECT permission only on the VIEW

C. Needs ALL PRIVILEGES on the VIEW

D. Needs ALL PRIVILEGES at the SCHEMA level

**Answer: B**

**Timestamp: Nov. 16, 2024, 11:34 a.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/151417-exam-certified-data-engineer-associate-topic-1-question-146/)

Comments: Sudip123 5 days, 15 hours ago Selected Answer: B If you have permissions to access the view, then you can access it. You don't need to have permission to acces the underling table(s). upvoted 1 times ... abbf4e9 1 week, 3 days ago Selected Answer: A Correct Answer: A. Needs SELECT permission on the VIEW and the underlying TABLE. Explanation: In Databricks Unity Catalog, access control is object-based and hierarchical: You must have USAGE permissions on the catalog and schema (already granted in this case). To query a view, you also need: SELECT permission on the view itself, and SELECT permission on all underlying tables referenced by that view. Why both permissions are needed: The view only defines a SQL query — it doesn’t store its own data. When you query the view, Databricks actually reads data from the underlying tables. Without SELECT access to those tables, you’ll get a permission error even if you can see the view. upvoted 1 times ... Torben2301 2 months ago Selected Answer: B https://learn.microsoft.com/en-us/azure/databricks/views/?utm_source=chatgpt.com For all compute resources, you must have SELECT on the view itself, USE CATALOG on its parent catalog, and USE SCHEMA on its parent schema. This applies to all compute types that support Unity Catalog, including SQL warehouses, clusters in standard access mode, and clusters in dedicated access mode on Databricks Runtime 15.4 and above. For clusters on Databricks Runtime 15.3 and below that use dedicated access mode, you must also have SELECT on all tables and views that are referenced by the view, in addition to USE CATALOG on their parent catalogs and USE SCHEMA on their parent schemas. upvoted 1 times ... Biswada 5 months, 4 weeks ago Selected Answer: A Since the Catalogue and Schema has only Usage permission, Underlying tables in the view needs explicit Select privilege upvoted 1 times ... san089 10 months, 2 weeks ago Selected Answer: B To read a view, the permissions required depend on the compute type, Databricks Runtime version, and access mode: For all compute resources, you must have SELECT on the view itself, USE CATALOG on its parent catalog, and USE SCHEMA on its parent schema. This applies to all compute types that support Unity Catalog, including SQL warehouses, clusters in shared access mode, and clusters in single user access mode on Databricks Runtime 15.4 and above. For clusters on Databricks Runtime 15.3 and below that use single user access mode, you must also have SELECT on all tables and views that are referenced by the view, in addition to USE CATALOG on their parent catalogs and USE SCHEMA on their parent schemas. upvoted 1 times ... Rinscy 10 months, 2 weeks ago Selected Answer: B B and key here is “Shared Cluster”. On a single cluster with a runtime prior to 15.4 it will need the permissions on view and tables. With Shared Access Cluster, only on the view. upvoted 2 times ... Pirate_boid 11 months ago Selected Answer: B For a view one does not need the permissions on the underlying table upvoted 2 times ... Medkalys 11 months, 1 week ago Selected Answer: A In Databricks Unity Catalog, permissions are hierarchical and must cover all data objects involved. If a user needs to query a view, the following conditions apply: SELECT permission on the VIEW: Allows the user to query the view itself. SELECT permission on the underlying TABLE(s): Views depend on the underlying tables or data sources. The user must also have SELECT permissions on these tables to access the data exposed by the view. upvoted 4 times ... SajadAhm 11 months, 2 weeks ago B is correct. in databricks partner platform, it shows privileges on a view and says: as you see, no one has access to this table, but we could give access to the view without giving access to the underlying table. this is one of the main advantages of views. upvoted 3 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 147 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 60
Topic #: 1

[All Certified Data Engineer Associate Questions]

Which method should a Data Engineer apply to ensure Workflows are being triggered on schedule? 
Suggested Answer: C 🗳️ 

A. Scheduled Workflows require an always-running cluster, which is more expensive but reduces processing latency.

B. Scheduled Workflows process data as it arrives at configured sources.

C. Scheduled Workflows can reduce resource consumption and expense since the cluster runs only long enough to execute the pipeline.

D. Scheduled Workflows run continuously until manually stopped.

**Answer: C**

**Timestamp: Dec. 16, 2024, 2:11 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/153042-exam-certified-data-engineer-associate-topic-1-question-147/)

Comments: MultiCloudIronMan 10 months, 2 weeks ago Selected Answer: C The correct answer is C. Scheduled Workflows can reduce resource consumption and expense since the cluster runs only long enough to execute the pipeline. This method ensures that the cluster is only active for the duration of the workflow execution, minimizing resource usage and costs. upvoted 3 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 148 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 148
Topic #: 1

[All Certified Data Engineer Associate Questions]

Which compute option should be chosen in a scenario where small-scale ad-hoc Python scripts need to be run at high frequency and should wind down quickly after these queries have finished running? 
Suggested Answer: B 🗳️ 

A. All-purpose Cluster

B. Job Cluster

C. Serverless Compute

D. SQL Warehouse

**Answer: B**

**Timestamp: Sept. 21, 2025, 9:58 a.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/312874-exam-certified-data-engineer-associate-topic-1-question-148/)

Comments: billyballo 3 weeks, 2 days ago Selected Answer: B Job cluster should met requirements upvoted 1 times ... Vivekkpd 1 month, 1 week ago Selected Answer: B Job Clusters are ephemeral clusters that: Spin up automatically when a job or script starts. Terminate automatically when the job completes. Are ideal for high-frequency, small-scale ad-hoc workloads. Why not the others: A. All-purpose Cluster → Persistent; wastes resources for short, frequent jobs. C. Serverless Compute → Optimized for SQL workloads, not general Python jobs. D. SQL Warehouse → Only for SQL queries, not Python scripts. upvoted 2 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 148 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 59
Topic #: 1

[All Certified Data Engineer Associate Questions]

The Delta transaction log for the ‘students’ tables is shown using the ‘DESCRIBE HISTORY students’ command. A Data Engineer needs to query the table as it existed before the UPDATE operation listed in the log.Which command should the Data Engineer use to achieve this? (Choose two.) 
Suggested Answer: AB 🗳️ 

A. SELECT * FROM students@v4

B. SELECT * FROM students TIMESTAMP AS OF ‘2024-04-22T 14:32:47.000+00:00’

C. SELECT * FROM students FROM HISTORY VERSION AS OF 3

D. SELECT * FROM students VERSION AS OF 5

E. SELECT * FROM students TIMESTAMP AS OF ‘2024-04-22T 14:32:58.000+00:00’

**Answer: A**

**Timestamp: Dec. 1, 2024, 3:21 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/152432-exam-certified-data-engineer-associate-topic-1-question-148/)

Comments: CaoMengde09 10 months ago Selected Answer: AB SELECT * FROM people10m VERSION AS OF 123; Is identical to SELECT * FROM people10m@v123; so . SELECT * FROM students@v4 is the same as running . SELECT * FROM students@v4 VERSION AS OF 5 ["A", "B"] upvoted 2 times Billybob0604 7 months, 1 week ago No , SELECT * FROM students@v4 is the same as running SELECT * FROM students VERSION AS OF 4 upvoted 1 times ... CaoMengde09 10 months ago Typing error : *SELECT * FROM students@v4 VERSION AS OF 4 upvoted 1 times ... ... DipeshGandhi131 10 months, 1 week ago Selected Answer: AB https://docs.databricks.com/en/delta/history.html#delta-time-travel-syntax upvoted 3 times ... MultiCloudIronMan 10 months, 2 weeks ago Selected Answer: BD Option A (SELECT * FROM students@v4) is not correct because the syntax students@v4 is not valid in SQL for querying a specific version of a Delta table. The correct syntax to query a specific version of a Delta table is to use the VERSION AS OF or TIMESTAMP AS OF clauses. Therefore, the correct options are: B. SELECT * FROM students TIMESTAMP AS OF ‘2024-04-22T 14:32:47.000+00:00’ D. SELECT * FROM students VERSION AS OF 5 upvoted 2 times ... Worldmaster 11 months ago Selected Answer: AB AB correct https://docs.databricks.com/en/delta/history.html upvoted 1 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 149 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 55
Topic #: 1

[All Certified Data Engineer Associate Questions]

An engineering manager uses a Databricks SQL query to monitor ingestion latency for each data source. The manager checks the results of the query every day, but they are manually rerunning the query each day and waiting for the results.Which of the following approaches can the manager use to ensure the results of the query are updated each day? 
Suggested Answer: C 🗳️ 

A. They can schedule the query to refresh every 1 day from the SQL endpoint's page in Databricks SQL.

B. They can schedule the query to refresh every 12 hours from the SQL endpoint's page in Databricks SQL.

C. They can schedule the query to refresh every 1 day from the query's page in Databricks SQL.

D. They can schedule the query to run every 12 hours from the Jobs UI.

**Answer: C**

**Timestamp: Dec. 16, 2024, 2:18 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/153043-exam-certified-data-engineer-associate-topic-1-question-149/)

Comments: MultiCloudIronMan 10 months, 2 weeks ago Selected Answer: C The correct answer is C. They can schedule the query to refresh every 1 day from the query's page in Databricks SQL. This approach ensures that the query results are automatically updated each day without the need for manual intervention. upvoted 2 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 150 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 53
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer needs to apply custom logic to string column city in table stores for a specific use case. In order to apply this custom logic at scale, the data engineer wants to create a SQL user-defined function (UDF).Which of the following code blocks creates this SQL UDF? 
Suggested Answer: A 🗳️ 

A.

B.

C.

D.

**Answer: A**

**Timestamp: Dec. 5, 2024, 11:22 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/152586-exam-certified-data-engineer-associate-topic-1-question-150/)

Comments: CaoMengde09 10 months ago Selected Answer: A It's "A". Google SQL Syntax to create a function and you'll find your answer with 100% of peace of mind. "D" doesn't make sense upvoted 1 times ... Manish_Kum 10 months, 3 weeks ago Selected Answer: A there is nothing called UDF while defining . Syntax is create Function <Function name> upvoted 2 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 151 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 52
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer has realized that they made a mistake when making a daily update to a table. They need to use Delta time travel to restore the table to a version that is 3 days old. However, when the data engineer attempts to time travel to the older version, they are unable to restore the data because the data files have been deleted.Which of the following explains why the data files are no longer present? 
Suggested Answer: A 🗳️ 

A. The VACUUM command was run on the table

B. The TIME TRAVEL command was run on the table

C. The DELETE HISTORY command was run on the table

D. The OPTIMIZE command was nun on the table

**Answer: A**

**Timestamp: Dec. 16, 2024, 2:26 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/153045-exam-certified-data-engineer-associate-topic-1-question-151/)

Comments: MultiCloudIronMan 10 months, 2 weeks ago Selected Answer: A Vacuum with a date range =< 3 days because default is over 7 days upvoted 1 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 152 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 50
Topic #: 1

[All Certified Data Engineer Associate Questions]

Which of the following describes the relationship between Bronze tables and raw data? 
Suggested Answer: C 🗳️ 

A. Bronze tables contain less data than raw data files.

B. Bronze tables contain more truthful data than raw data.

C. Bronze tables contain raw data with a schema applied.

D. Bronze tables contain a less refined view of data than raw data.

**Answer: C**

**Timestamp: Dec. 16, 2024, 2:29 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/153046-exam-certified-data-engineer-associate-topic-1-question-152/)

Comments: MultiCloudIronMan 10 months, 2 weeks ago Selected Answer: C The correct answer is C. Bronze tables contain raw data with a schema applied. Bronze tables are typically the first layer in a data pipeline and are used to store raw data in a structured format, making it easier to process and analyze. upvoted 1 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 153 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 48
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer only wants to execute the final block of a Python program if the Python variable day_of_week is equal to 1 and the Python variable review_period is True.Which of the following control flow statements should the data engineer use to begin this conditionally executed code block? 
Suggested Answer: D 🗳️ 

A. if day_of_week = 1 and review_period:

B. if day_of_week = 1 and review_period = "True":

C. if day_of_week = 1 & review_period: = "True":

D. if day_of_week == 1 and review_period:

**Answer: D**

**Timestamp: Dec. 5, 2024, 11:26 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/152587-exam-certified-data-engineer-associate-topic-1-question-153/)

Comments: b41de50 10 months, 2 weeks ago Selected Answer: D if review_period == 'True' is comparing the actual text 'True' not boolean upvoted 1 times ... 1919730 10 months, 3 weeks ago Selected Answer: D In python, to compare two values, we use ==. Also, because review_period is true, no need to compare it to a value. "if review_period" is enough and "if review_period== 'True'" is wrong because we compare a boolean to a string. upvoted 1 times ... Manish_Kum 10 months, 3 weeks ago Selected Answer: D d is right answer upvoted 1 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 153 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 153
Topic #: 1

[All Certified Data Engineer Associate Questions]

What is the maximum output supported by a job cluster to ensure a notebook does not fail? 
Suggested Answer: C 🗳️ 

A. 25MBs

B. 10MBs

C. 30MBs

D. 15MBs

**Answer: C**

**Timestamp: Sept. 9, 2025, 1:28 a.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/312162-exam-certified-data-engineer-associate-topic-1-question-153/)

Comments: Kundankg 1 month, 1 week ago Selected Answer: C 30 MBs upvoted 1 times ... ADFMDS 1 month, 2 weeks ago Selected Answer: C For Cluster it is 30 MB, C is correct, upvoted 2 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 154 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 42
Topic #: 1

[All Certified Data Engineer Associate Questions]

Which of the following must be specified when creating a new Delta Live Tables pipeline? 
Suggested Answer: B 🗳️ 

A. A key-value pair configuration

B. At least one notebook library to be executed

C. A path to cloud storage location for the written data

D. A location of a target database for the written data

**Answer: B**

**Timestamp: Dec. 16, 2024, 2:32 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/153047-exam-certified-data-engineer-associate-topic-1-question-154/)

Comments: MultiCloudIronMan 10 months, 2 weeks ago Selected Answer: B The correct answer is B. At least one notebook library to be executed. When creating a new Delta Live Tables pipeline, you need to specify at least one notebook library that contains the code to be executed as part of the pipeline. upvoted 1 times sthulsameer 9 months, 2 weeks ago Why not D? target Type: string The name of a database for persisting pipeline output data. Configuring the target setting allows you to view and query the pipeline output data from the Databricks UI. upvoted 3 times ... ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 155 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 41
Topic #: 1

[All Certified Data Engineer Associate Questions]

In which of the following scenarios should a data engineer select a Task in the Depends On field of a new Databricks Job Task? 
Suggested Answer: B 🗳️ 

A. When another task needs to be replaced by the new task

B. When another task needs to successfully complete before the new task begins

C. When another task has the same dependency libraries as the new task

D. When another task needs to use as little compute resources as possible

**Answer: B**

**Timestamp: Dec. 16, 2024, 2:34 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/153048-exam-certified-data-engineer-associate-topic-1-question-155/)

Comments: MultiCloudIronMan 10 months, 2 weeks ago Selected Answer: B The correct answer is B. When another task needs to successfully complete before the new task begins. Selecting a task in the "Depends On" field ensures that the new task will only start after the specified task has successfully completed, maintaining the correct sequence and dependencies in the workflow upvoted 1 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 156 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 39
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineering team has two tables. The first table march_transactions is a collection of all retail transactions in the month of March. The second table april_transactions is a collection of all retail transactions in the month of April. There are no duplicate records between the tables.Which of the following commands should be run to create a new table all_transactions that contains all records from march_transactions and april_transactions without duplicate records? 
Suggested Answer: B 🗳️ 

A. CREATE TABLE all_transactions ASSELECT * FROM march_transactionsINNER JOIN SELECT * FROM april_transactions;

B. CREATE TABLE all_transactions ASSELECT * FROM march_transactionsUNION SELECT * FROM april_transactions;

C. CREATE TABLE all_transactions ASSELECT * FROM march_transactionsOUTER JOIN SELECT * FROM april_transactions;

D. CREATE TABLE all_transactions ASSELECT * FROM march_transactionsINTERSECT SELECT * from april_transactions;

**Answer: B**

**Timestamp: Dec. 16, 2024, 3:51 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/153053-exam-certified-data-engineer-associate-topic-1-question-156/)

Comments: MultiCloudIronMan 10 months, 2 weeks ago Selected Answer: B The correct answer is B. CREATE TABLE all_transactions AS SELECT * FROM march_transactions UNION SELECT * FROM april_transactions. The UNION operator combines the results of two queries and removes duplicate records, ensuring that the new table all_transactions contains all unique records from both march_transactions and april_transactions. upvoted 2 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 157 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 35
Topic #: 1

[All Certified Data Engineer Associate Questions]

How can Git operations must be performed outside of Databricks Repos? 
Suggested Answer: C 🗳️ 

A. Commit

B. Pull

C. Merge

D. Clone

**Answer: C**

**Timestamp: Dec. 16, 2024, 3:53 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/153054-exam-certified-data-engineer-associate-topic-1-question-157/)

Comments: abbf4e9 1 week, 5 days ago Selected Answer: D Correct Answer: D. Clone Explanation: In Databricks Repos, you can perform most common Git operations such as: Commit/Pull/Push/Branch switching/Merge (via pull request) directly inside Databricks Repos UI or via Repos APIs. However, there is one Git operation that cannot be done inside Databricks Repos —which is git clone Why “Clone” must be done outside Databricks Repos: You don’t clone manually using git clone in Databricks. Instead, you link a remote Git repository to a Databricks Repo using the Repos UI or REST API — Databricks internally performs the cloning for you. Therefore, the clone operation (as you would perform with git clone on your local machine) is not supported directly inside Databricks Repos. upvoted 2 times ... 45a1d55 7 months, 1 week ago Selected Answer: C C. Merge: Merging branches is not natively supported within Databricks Repos. While you can switch branches and commit changes, the act of merging two branches (e.g., resolving conflicts or combining histories) requires a Git client outside of Databricks or handling it in the remote Git hosting service (e.g., creating a pull request on GitHub). Databricks documentation indicates that merge operations, especially those involving conflicts, are outside its scope, pushing users to external tools. Verdict: Aligns with the question—merge operations must be performed outside Databricks upvoted 2 times ... IulianRo 9 months ago Selected Answer: C It should be MERGE upvoted 1 times ... shinypriti23 9 months, 1 week ago Selected Answer: C Merge happen outside of DB upvoted 1 times ... CoolSmartDude 9 months, 3 weeks ago Selected Answer: C Merge needs to happen outside of DB upvoted 1 times ... duzi 9 months, 4 weeks ago Selected Answer: C See https://docs.databricks.com/en/repos/git-operations-with-repos.html "The article describes how to perform common Git operations in your Databricks workspace using Git folders, including cloning, branching, committing, and pushing." See also Question 8. upvoted 2 times ... MultiCloudIronMan 10 months, 2 weeks ago Selected Answer: D The correct answers are A. Commit and D. Clone. These Git operations must be performed outside of Databricks Repos. upvoted 1 times CaoMengde09 10 months ago Clone is done inside Databricks from external Git Repo, i don't get your answer. In other side, MERGing a Pull request with a branch cannot be done inside Databricks repo. I see that MERGE is the only Git Operation that can be done outside Databricks Repo. Ans : C upvoted 3 times ... ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 158 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 34
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer has joined an existing project and they see the following query in the project repository:CREATE STREAMING LIVE TABLE loyal_customers ASSELECT customer_id -FROM STREAM(LIVE.customers)WHERE loyalty_level = 'high';Which of the following describes why the STREAM function is included in the query? 
Suggested Answer: C 🗳️ 

A. The STREAM function is not needed and will cause an error.

B. The data in the customers table has been updated since its last run.

C. The customers table is a streaming live table.

D. The customers table is a reference to a Structured Streaming query on a PySpark DataFrame.

**Answer: C**

**Timestamp: Dec. 16, 2024, 3:55 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/153055-exam-certified-data-engineer-associate-topic-1-question-158/)

Comments: MultiCloudIronMan 10 months, 2 weeks ago Selected Answer: C The correct answer is C. The customers table is a streaming live table. The STREAM function is used to indicate that the customers table is a streaming live table, which means it is continuously updated with new data. This allows the loyal_customers table to be created as a streaming live table that processes data incrementally as it arrives. upvoted 3 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 159 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 30
Topic #: 1

[All Certified Data Engineer Associate Questions]

Which Structured Streaming query is performing a hop from a Silver table to a Gold table? 
Suggested Answer: D 🗳️ 

A.

B.

C.

D.

**Answer: D**

**Timestamp: Dec. 5, 2024, 11:36 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/152588-exam-certified-data-engineer-associate-topic-1-question-159/)

Comments: datareport_AZ 10 months, 3 weeks ago Selected Answer: B B performs aggregation upvoted 1 times ... b41de50 10 months, 3 weeks ago Selected Answer: D Silver table contains filtered, cleaned augmented data. Gold table contains aggregated data upvoted 3 times ... Manish_Kum 10 months, 3 weeks ago Selected Answer: D aggregation is performed in Silver to Gold hop. also outputmode will be "complete" upvoted 4 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 160 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 29
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data organization leader is upset about the data analysis team’s reports being different from the data engineering team’s reports. The leader believes the siloed nature of their organization’s data engineering and data analysis architectures is to blame.Which of the following describes how a data lakehouse could alleviate this issue? 
Suggested Answer: B 🗳️ 

A. Both teams would respond more quickly to ad-hoc requests

B. Both teams would use the same source of truth for their work

C. Both teams would reorganize to report to the same department

D. Both teams would be able to collaborate on projects in real-time

**Answer: B**

**Timestamp: Dec. 5, 2024, 11:38 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/152590-exam-certified-data-engineer-associate-topic-1-question-160/)

Comments: Manish_Kum 10 months, 3 weeks ago Selected Answer: B B is correct upvoted 3 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 161 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 161
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer is managing a data pipeline in Databricks, where multiple Delta tables are used for various transformations. The team wants to track how data flows through the pipeline, including identifying dependencies between Delta tables, notebooks, jobs, and dashboards. The data engineer is utilizing the Unity Catalog lineage feature to monitor this process.How does Unity Catalog’s data lineage feature support the visualization of relationships between Delta tables, notebooks, jobs, and dashboards? 
Suggested Answer: D 🗳️ 

A. Unity Catalog lineage visualizes dependencies between Delta tables, notebooks, and jobs, but does not provide column-level tracing or relationships with dashboards.

B. Unity Catalog lineage only supports visualizing relationships at the table level and does not extend to notebooks, jobs, or dashboards.

C. Unity Catalog lineage provides an interactive graph that tracks dependencies between tables and notebooks but excludes any job-related dependencies or dashboard visualizations.

D. Unity Catalog provides an interactive graph that visualizes the dependencies between Delta tables, notebooks, jobs, and dashboards, while also supporting column-level tracking of data transformations.

**Answer: D**

**Timestamp: Sept. 9, 2025, 1:43 a.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/312163-exam-certified-data-engineer-associate-topic-1-question-161/)

Comments: Vivekkpd 1 month, 1 week ago Selected Answer: D Unity Catalog in Databricks allows teams to track data lineage, showing how data moves and transforms across a pipeline. Key points include: End-to-end lineage: It captures dependencies between Delta tables, notebooks, jobs, and dashboards, giving a complete view of data flow. Column-level lineage: You can see not just which tables are involved, but also how specific columns are transformed across operations. Interactive visualization: Unity Catalog provides an interactive graph to explore these relationships, making it easier for engineers and analysts to understand dependencies and troubleshoot issues. Other options are incorrect because they either limit lineage to tables only, exclude jobs or dashboards, or omit column-level tracking. upvoted 1 times ... ADFMDS 1 month, 2 weeks ago Selected Answer: D D is correct, check below https://learn.microsoft.com/en-us/azure/databricks/data-governance/unity-catalog/data-lineage upvoted 1 times ... ADFMDS 1 month, 2 weeks ago Selected Answer: D Check this link and you will see correct answer is D https://learn.microsoft.com/en-us/azure/databricks/data-governance/unity-catalog/data-lineage upvoted 1 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 161 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 28
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data analyst has developed a query that runs against Delta table. They want help from the data engineering team to implement a series of tests to ensure the data returned by the query is clean. However, the data engineering team uses Python for its tests rather than SQL.Which of the following operations could the data engineering team use to run the query and operate with the results in PySpark? 
Suggested Answer: C 🗳️ 

A. SELECT * FROM sales

B. spark.delta.table

C. spark.sql

D. spark.table

**Answer: C**

**Timestamp: Dec. 5, 2024, 11:39 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/152591-exam-certified-data-engineer-associate-topic-1-question-161/)

Comments: AG_IT 2 months, 1 week ago Selected Answer: C spark.sql(<you can write query here>) upvoted 1 times ... Manish_Kum 10 months, 3 weeks ago Selected Answer: C C is correct upvoted 2 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 162 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 27
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer has a Job that has a complex run schedule, and they want to transfer that schedule to other Jobs.Rather than manually selecting each value in the scheduling form in Databricks, which of the following tools can the data engineer use to represent and submit the schedule programmatically? 
Suggested Answer: D 🗳️ 

A. pyspark.sql.types.DateType

B. datetime

C. pyspark.sql.types.TimestampType

D. Cron syntax

**Answer: D**

**Timestamp: Dec. 16, 2024, 4 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/153060-exam-certified-data-engineer-associate-topic-1-question-162/)

Comments: duzi 9 months, 4 weeks ago Selected Answer: D Question is repeated. See details on https://learn.microsoft.com/en-us/azure/databricks/jobs/scheduled upvoted 2 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 162 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 162
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer needs to conduct Exploratory Analysis on data residing in a database that is within the company’s custom-defined network in the cloud. The data engineer is using SQL for this task.Which type of SQL Warehouse will enable the data engineer to process large numbers of queries quickly and cost-effectively? 
Suggested Answer: D 🗳️ 

A. Serverless compute for notebooks

B. Pro SQL Warehouse

C. Classic SQL Warehouse

D. Serverless SQL Warehouse

**Answer: D**

**Timestamp: Sept. 12, 2025, 12:49 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/312507-exam-certified-data-engineer-associate-topic-1-question-162/)

Comments: Vivekkpd 1 month, 1 week ago Selected Answer: D D Serverless SQL Warehouse in Databricks is designed for ad hoc and exploratory analysis. It scales automatically, allowing you to process large numbers of queries efficiently without worrying about infrastructure management. It’s cost-effective because you only pay for the compute resources used during query execution. Ideal for SQL analysts or data engineers who need to run queries on data in your cloud network quickly, without managing clusters. Other options: A. Serverless compute for notebooks → optimized for notebook workloads, not SQL queries. B. Pro SQL Warehouse → dedicated compute, higher cost, better for predictable workloads. C. Classic SQL Warehouse → older model, less flexible and less cost-efficient compared to serverless. upvoted 1 times ... ADFMDS 1 month, 2 weeks ago Selected Answer: D D is correct, keep in mind, it asked for cost-effective and in serverless, you only pay for running queries while in Pro you pay uptimes. upvoted 2 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 163 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 26
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer and data analyst are working together on a data pipeline. The data engineer is working on the raw, bronze, and silver layers of the pipeline using Python, and the data analyst is working on the gold layer of the pipeline using SQL. The raw source of the pipeline is a streaming input. They now want to migrate their pipeline to use Delta Live Tables.Which of the following changes will need to be made to the pipeline when migrating to Delta Live Tables? 
Suggested Answer: D 🗳️ 

A. The pipeline will need to be written entirely in Python

B. The pipeline will need to stop using the medallion-based multi-hop architecture

C. The pipeline will need to be written entirely in SQL

D. The pipeline will need to use a batch source in place of a streaming source

**Answer: D**

**Timestamp: Dec. 5, 2024, 11:43 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/152592-exam-certified-data-engineer-associate-topic-1-question-163/)

Comments: aamahi 1 month ago Selected Answer: D This is the best choice upvoted 1 times ... Kundankg 1 month, 3 weeks ago Selected Answer: D None of the listed options are required changes for migrating to Delta Live Tables (DLT). upvoted 3 times ... Billybob0604 7 months, 1 week ago Selected Answer: C Delta Live Tables (DLT) currently requires SQL or Python for defining data pipelines. However, for streaming data, SQL has become the primary language for defining Delta Live Tables pipelines in Databricks. upvoted 2 times ... e872ce8 7 months, 2 weeks ago Selected Answer: A A & C. The pipeline will need to be written entirely in Python (if using Python APIs for Delta Live Tables) The pipeline will need to be written entirely in SQL (if using SQL-based Delta Live Tables)Delta Live Tables (DLT) is a declarative ETL framework built on Databricks, designed to simplify pipeline development and management. It supports: Python-based pipelines using @dlt.table decorators SQL-based pipelines using CREATE LIVE TABLE Since the data engineer is using Python and the data analyst is using SQL, the pipeline will need to be rewritten in one of the two supported languages. upvoted 1 times ... Kayceetalks 7 months, 3 weeks ago Selected Answer: D None of these options are currect upvoted 4 times ... MultiCloudIronMan 10 months, 2 weeks ago Selected Answer: A The correct response is A. None of these changes will need to be made. Delta Live Tables supports both Python and SQL, as well as streaming and batch sources. This means that the existing medallion-based multi-hop architecture can be maintained, and the pipeline can continue to use both Python and SQL for different layers. Therefore, no changes are necessary when migrating to Delta Live Tables. upvoted 3 times MultiCloudIronMan 10 months, 1 week ago Sorry None if the options are correct - When migrating to Delta Live Tables, the pipeline does not need to be rewritten entirely in Python or SQL, nor does it need to stop using the medallion-based multi-hop architecture. Additionally, it does not need to switch from a streaming source to a batch source. Delta Live Tables supports both Python and SQL, and it can handle streaming data sources upvoted 7 times ... ... Manish_Kum 10 months, 3 weeks ago Selected Answer: D best choice in this questions is D upvoted 4 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 164 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 22
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer needs access to a table new_table, but they do not have the correct permissions. They can ask the table owner for permission, but they do not know who the table owner is.Which of the following approaches can be used to identify the owner of new_table? 
Suggested Answer: C 🗳️ 

A. Review the Permissions tab in the table's page in Data Explorer

B. There is no way to identify the owner of the table

C. Review the Owner field in the table's page in Data Explorer

D. Review the Owner field in the table's page in the cloud storage solution

**Answer: C**

**Timestamp: Dec. 16, 2024, 4:02 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/153062-exam-certified-data-engineer-associate-topic-1-question-164/)

Comments: Sd1988 9 months, 3 weeks ago Selected Answer: C C is the best choice upvoted 2 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 164 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 164
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer is debugging a Python notebook in Databricks that processes a dataset using PySpark. The notebook fails with an error during a DataFrame transformation. The engineer wants to inspect the state of variables, such as the input DataFrame and intermediate results, to identify where the error occurs.Which tool should the engineer use to debug the notebook and inspect the values of variables like DataFrames? 
Suggested Answer: B 🗳️ 

A. Use the Databricks CLI to download and analyze driver logs for detailed error messages

B. Use the Python Notebook Interactive Debugger to set breakpoints and inspect variable values in real-time

C. Use the Ganglia UI to monitor cluster resource usage and identify hardware issues

D. Use the Spark UI to analyze the execution plan and identify stages where the job failed

**Answer: B**

**Timestamp: Sept. 20, 2025, 2:15 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/312868-exam-certified-data-engineer-associate-topic-1-question-164/)

Comments: Vivekkpd 1 month, 1 week ago Selected Answer: B B. Use the Python Notebook Interactive Debugger to set breakpoints and inspect variable values in real-time The Python Notebook Interactive Debugger in Databricks allows engineers to: Set breakpoints in notebook cells. Step through code interactively. Inspect the state of variables, including PySpark DataFrames and intermediate results. This is ideal for debugging DataFrame transformations and finding exactly where an error occurs. Other options are less suitable for this purpose: A. Databricks CLI and driver logs → Useful for post-mortem error messages, not interactive variable inspection. C. Ganglia UI → Focuses on cluster resource metrics (CPU, memory), not Python variable state. D. Spark UI → Shows job/stage execution and plan, but does not allow inspecting Python variable values directly. upvoted 1 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 165 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 21
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer needs to create a table in Databricks using data from their organization’s existing SQLite database.They run the following command:Which of the following lines of code fills in the above blank to successfully complete the task? 
Suggested Answer: A 🗳️ 

A. org.apache.spark.sql.jdbc

B. autoloader

C. org.apache.spark.sql.sqlite

D. sqlite

**Answer: A**

**Timestamp: Dec. 16, 2024, 4:03 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/153063-exam-certified-data-engineer-associate-topic-1-question-165/)

Comments: ADFMDS 1 month, 2 weeks ago Selected Answer: A In Spark/Databricks, to connect to external databases (including SQLite, MySQL, PostgreSQL, etc.), you use the JDBC data source. upvoted 3 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 166 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 20
Topic #: 1

[All Certified Data Engineer Associate Questions]

In which of the following scenarios should a data engineer use the MERGE INTO command instead of the INSERT INTO command? 
Suggested Answer: D 🗳️ 

A. When the location of the data needs to be changed

B. When the target table is an external table

C. When the source is not a Delta table

D. When the target table cannot contain duplicate records

**Answer: D**

**Timestamp: Dec. 16, 2024, 4:03 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/153065-exam-certified-data-engineer-associate-topic-1-question-166/)

Comments: Kayceetalks 7 months, 3 weeks ago Selected Answer: D Correct answer upvoted 2 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 166 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 166
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer is developing a small proof of concept in a notebook. When running the entire notebook, the Cluster usage spikes. The data engineer wants to keep the development requirements and get real-time results.Which Cluster meets these requirements? 
Suggested Answer: A 🗳️ 

A. All Purpose Cluster with autoscaling

B. Job Cluster with Photon enabled and autoscaling

C. Job Cluster with autoscaling enabled

D. All-Purpose Cluster with a large fixed memory size

**Answer: A**

**Timestamp: Sept. 20, 2025, 2:20 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/312869-exam-certified-data-engineer-associate-topic-1-question-166/)

Comments: Vivekkpd 1 month, 1 week ago Selected Answer: A A. All Purpose Cluster with autoscaling Explanation: All-Purpose Clusters in Databricks are designed for interactive use, such as running notebooks, doing exploratory analysis, or developing proofs of concept. Autoscaling allows the cluster to adjust resources dynamically based on workload, preventing excessive usage while still giving real-time results. Ideal for development scenarios where you want immediate feedback without over-provisioning resources. Other options are less suitable: B. Job Cluster with Photon and autoscaling → Job clusters are optimized for scheduled jobs, not interactive notebook development. C. Job Cluster with autoscaling → Same reason; not intended for real-time interactive development. D. All-Purpose Cluster with fixed large memory → Wasteful and lacks dynamic scaling; spikes in usage could be more costly. upvoted 1 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 167 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 17
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer is designing a data pipeline. The source system generates files in a shared directory that is also used by other processes. As a result, the files should be kept as is and will accumulate in the directory. The data engineer needs to identify which files are new since the previous run in the pipeline, and set up the pipeline to only ingest those new files with each run.Which of the following tools can the data engineer use to solve this problem? 
Suggested Answer: D 🗳️ 

A. Unity Catalog

B. Delta Lake

C. Databricks SQL

D. Auto Loader

**Answer: D**

**Timestamp: Dec. 16, 2024, 4:04 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/153066-exam-certified-data-engineer-associate-topic-1-question-167/)

Comments: e872ce8 7 months, 2 weeks ago Selected Answer: D Auto Loader is a feature in Databricks that automatically ingests new data files as they appear in a specified directory, and it efficiently handles large volumes of data. It can track which files are new since the previous run and only process those files, which perfectly fits the use case described. upvoted 3 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 168 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 15
Topic #: 1

[All Certified Data Engineer Associate Questions]

What is stored in the Databricks customer's cloud account? 
Suggested Answer: D 🗳️ 

A. Databricks web application

B. Cluster management metadata

C. Notebooks

D. Data

**Answer: D**

**Timestamp: Dec. 16, 2024, 4:05 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/153067-exam-certified-data-engineer-associate-topic-1-question-168/)

Comments: Hink 1 week, 5 days ago Selected Answer: D Data Plane stores customer data and is part of the customer account. upvoted 1 times ... e872ce8 7 months, 2 weeks ago Selected Answer: D In Databricks, the customer's cloud account primarily stores data. This data is stored in cloud storage services (e.g., AWS S3, Azure Blob Storage, or Google Cloud Storage) linked to the Databricks environment. Databricks manages and processes the data using its clusters, but the actual data is stored in the cloud storage solution chosen by the customer. upvoted 3 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 169 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 10
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer wants to create a relational object by pulling data from two tables. The relational object does not need to be used by other data engineers in other sessions. In order to save on storage costs, the data engineer wants to avoid copying and storing physical data.Which of the following relational objects should the data engineer create? 
Suggested Answer: D 🗳️ 

A. Spark SQL Table

B. View

C. Delta Table

D. Temporary view

**Answer: D**

**Timestamp: Dec. 16, 2024, 4:06 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/153069-exam-certified-data-engineer-associate-topic-1-question-169/)

Comments: sebastianbrinezc 1 month ago Selected Answer: D Temporary views are the way to go for relational objects that we do not need to persist in the database because we only need to use once. upvoted 3 times ... e872ce8 7 months, 2 weeks ago Selected Answer: D A Temporary view in Databricks allows a data engineer to create a relational object that pulls data from other tables but does not require physical storage. It is session-scoped, meaning it only exists for the duration of the session and is not persisted in storage, which saves on storage costs. upvoted 3 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 170 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 8
Topic #: 1

[All Certified Data Engineer Associate Questions]

Which of the following commands will return the number of null values in the member_id column? 
Suggested Answer: C 🗳️ 

A. SELECT count(member_id) FROM my_table;

B. SELECT count(member_id) - count_null(member_id) FROM my_table;

C. SELECT count_if(member_id IS NULL) FROM my_table;

D. SELECT null(member_id) FROM my_table;

**Answer: C**

**Timestamp: Dec. 16, 2024, 4:07 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/153071-exam-certified-data-engineer-associate-topic-1-question-170/)

Comments: Hink 1 week, 5 days ago Selected Answer: C Just verified C in databricks notebook and its correct upvoted 1 times ... Kayceetalks 7 months, 3 weeks ago Selected Answer: C correct option upvoted 2 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 171 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 7
Topic #: 1

[All Certified Data Engineer Associate Questions]

Which tool is used by Auto Loader to process data incrementally? 
Suggested Answer: B 🗳️ 

A. Checkpointing

B. Spark Structured Streaming

C. Databricks SQL

D. Unity Catalog

**Answer: B**

**Timestamp: Dec. 16, 2024, 4:07 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/153073-exam-certified-data-engineer-associate-topic-1-question-171/)

Comments: Hink 1 week, 5 days ago Selected Answer: B Auto Loader is built on Spark Structured Streaming. It uses the streaming engine to incrementally process new files as they arrive in cloud storage (e.g., Azure Blob, ADLS, S3, GCS). It tracks state (what files have been processed) using checkpoints, but the core engine that enables incremental ingestion is Structured Streaming. upvoted 1 times ... Giorgos90 2 weeks, 2 days ago Selected Answer: B Databricks Auto Loader is built on top of Spark Structured Streaming. It uses the streaming engine to incrementally and efficiently process new data files as they arrive in cloud storage (e.g., AWS S3, Azure Data Lake, GCS) upvoted 4 times ... testography 3 weeks, 3 days ago Selected Answer: A Checkpointing is what lets Auto Loader remember state upvoted 2 times ... AWSCertification2024 1 month ago Selected Answer: A Auto Loader uses Checkpointing for processing data incrementally. upvoted 2 times ... sebastianbrinezc 1 month ago Selected Answer: B Spark structure streaming upvoted 2 times ... Santosh457 1 month, 1 week ago Selected Answer: A Autoloader built on top of Spark Structured Streaming, but it won't be used for processing data incrementally. upvoted 1 times ... AG_IT 2 months, 1 week ago Selected Answer: B auto loader uses spark structured streaming upvoted 2 times ... Kayceetalks 7 months, 3 weeks ago Selected Answer: B Correct upvoted 2 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 172 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 2
Topic #: 1

[All Certified Data Engineer Associate Questions]

Which of the following benefits is provided by the array functions from Spark SQL? 
Suggested Answer: D 🗳️ 

A. An ability to work with data in a variety of types at once

B. An ability to work with data within certain partitions and windows

C. An ability to work with time-related data in specified intervals

D. An ability to work with complex, nested data ingested from JSON files

**Answer: D**

**Timestamp: Dec. 16, 2024, 4:32 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/153077-exam-certified-data-engineer-associate-topic-1-question-172/)

Comments: Hink 1 week, 5 days ago Selected Answer: D Spark SQL array functions are designed to manipulate arrays, which are common in nested or semi-structured data (e.g., JSON, Avro, Parquet). They allow you to query, transform, and flatten arrays without writing custom code, making it easier to handle complex schemas. upvoted 1 times ... CloudLuv 1 month, 1 week ago Selected Answer: D Naturally these array functions help in performing operations on the array in native way. That includes tasks like creating arrays, accessing specific elements, checking for element existence, filtering, and transforming elements using higher-order functions (e.g., transform, filter, exists, forall) upvoted 1 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 173 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 1
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer is working with two tables. Each of these tables is displayed below in its entirety.The data engineer runs the following query to join these tables together:Which of the following will be returned by the above query? 
Suggested Answer: C 🗳️ 

A.

B.

C.

D.

**Answer: C**

**Timestamp: Dec. 9, 2024, 7:11 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/152757-exam-certified-data-engineer-associate-topic-1-question-173/)

Comments: m_sevyd 1 month ago Selected Answer: C sales is the table at the left of the join, so all the records from Sales (only) are returned even if they don't match with some records in favorite_stores upvoted 2 times ... sebastianbrinezc 1 month ago Selected Answer: C Left joining sales with favorite stores, all records from left table (sales) are kept while only matching records from right table (favorite_store) are kept. upvoted 2 times ... analyticstraining 7 months, 3 weeks ago Selected Answer: C It's the same question as 68 and 112. upvoted 2 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 175 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 175
Topic #: 1

[All Certified Data Engineer Associate Questions]

A Databricks single-task workflow fails at the last task due to an error in a notebook. The data engineer fixes the mistake in the notebook.What should the data engineer do to rerun the workflow? 
Suggested Answer: A 🗳️ 

A. Repair the task

B. Rerun the pipeline

C. Restart the cluster

D. Switch the cluster

**Answer: A**

**Timestamp: Sept. 20, 2025, 2:39 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/312870-exam-certified-data-engineer-associate-topic-1-question-175/)

Comments: Vivekkpd 1 month, 1 week ago Selected Answer: B B. Rerun the pipeline Explanation: In a single-task workflow, there is only one task in the pipeline. Once the underlying notebook is fixed, the workflow can be rerun from the beginning, which in this case is just the single task. Since there are no previous successful tasks to preserve, a repair run is not applicable (repair runs are used for multi-task workflows to rerun only failed tasks). Other options are incorrect: A. Repair the task → Applicable only in multi-task workflows. C. Restart the cluster → Not necessary unless there is a cluster-level issue. D. Switch the cluster → Irrelevant for rerunning a fixed notebook. Rerunning the workflow ensures the fixed notebook executes and completes successfully. upvoted 3 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 177 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 177
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer has written a function in a Databricks Notebook to calculate the population of bacteria in a given medium.Analysts use this function in the notebook and sometimes provide input arguments of the wrong data type, which can cause errors during execution.Which Databricks feature will help the data engineer quickly identify if an incorrect data type has been provided as input? 
Suggested Answer: B 🗳️ 

A. The Spark User interface has a debug tab that contains the variables that are used in this session.

B. The Databricks debugger enables breakpoints that will raise an error if the wrong data type is submitted.

C. The Databricks debugger enables the use of a variable explorer to see at a glance the value of the variables.

D. The Data Engineer should add print statements to find out what the variable is.

**Answer: B**

**Timestamp: Sept. 20, 2025, 2:53 p.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/312871-exam-certified-data-engineer-associate-topic-1-question-177/)

Comments: Vivekkpd 1 month, 1 week ago Selected Answer: C C. The Databricks debugger enables the use of a variable explorer to see at a glance the value of the variables. Explanation: The Databricks debugger allows developers to set breakpoints and inspect variables in real time. The variable explorer in the debugger shows the current value and type of each variable, helping quickly identify if an incorrect data type has been provided. This is particularly useful in scenarios where functions may receive inputs of the wrong type, preventing runtime errors and speeding up debugging. Other options are less effective: A. Spark UI debug tab → Focuses on Spark jobs and execution plans, not Python variable types. B. Debugger raising errors on wrong type → Databricks debugger doesn’t automatically enforce type checking; it helps you inspect variables. D. Adding print statements → Manual, error-prone, and less efficient compared to using the debugger and variable explorer. The variable explorer is the most efficient way to catch data type issues interactively in a notebook. upvoted 4 times ...
----------------------------------------

## Exam Certified Data Engineer Associate topic 1 question 179 discussion

Actual exam question from

Databricks's
Certified Data Engineer Associate

Question #: 179
Topic #: 1

[All Certified Data Engineer Associate Questions]

A data engineer needs to parse only png files in a directory that contains files with different suffixes.Which code should the data engineer use to achieve this task? 
Suggested Answer: B 🗳️ 

A. df = spark.readStream.format("cloudFiles") \ .option("cloudFiles.format", "binaryFile") \.append("/*.png")

B. df = spark.readstream. format("cloudFiles") \.option("cloudFiles.format", "binaryFile") \.option("pathGlobfilter", "*.png") \.load()

C. df = spark.readStream.format("cloudFiles") \ .option("cloudFiles.format", "binaryFile") \.option("pathGlobfilter", "*.png") \ .append()

D. df = spark.readstream.format("cloudFiles") \ .option("cloudFiles.format", "binaryFile") \.load("/*.png")

**Answer: B**

**Timestamp: Sept. 9, 2025, 5:01 a.m.**

[View on ExamTopics](https://www.examtopics.com/discussions/databricks/view/312165-exam-certified-data-engineer-associate-topic-1-question-179/)

Comments: CloudLuv 1 month ago Selected Answer: B https://docs.databricks.com/aws/en/ingestion/cloud-object-storage/auto-loader/patterns important You need to use the option pathGlobFilter for explicitly providing suffix patterns. The path only provides a prefix filter. For example, if you would like to parse only png files in a directory that contains files with different suffixes, you can do: Python df = spark.readStream.format("cloudFiles") \ .option("cloudFiles.format", "binaryFile") \ .option("pathGlobfilter", "*.png") \ .load(<base-path>) upvoted 1 times ... Vivekkpd 1 month, 1 week ago Selected Answer: B Strictly speaking, none of the options are 100% correct. The best approach is to choose the option closest to correct logic (B), with fixing the casing to make it work. Option B, used "pathGlobfilter" with a lowercase f, it would not work in Spark because options are case-sensitive. Other options are incorrect: A → .append("/*.png") is not a valid Spark method for filtering files. C → .append() is invalid in this context. D → load("/*.png") is not the correct way to filter files with CloudFiles; pathGlobFilter should be used. upvoted 1 times ... Constantine73 1 month, 2 weeks ago Selected Answer: D B answer has a misspelled word needs capital F pathGlobFilter. I believe the D is correct. upvoted 1 times ...
----------------------------------------

