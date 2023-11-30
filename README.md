# Azure-Data-Engineering


<h2>Introduction</h2>
1) a data engineer is the primary role responsible for integrating, transforming, and consolidating data from various structured and unstructured data systems into structures that are suitable for building analytics solutions
2) ensure that data pipelines and data stores are high-performing, efficient, organized, and reliable, given a specific set of business requirements and constraints.


<h2>Types of data</h2>
1) <h3>Structured data </h3>primarily comes from table-based source systems such as a relational database or from a flat file such as a comma separated (CSV) file.

2) <h3>Semi-structured data</h3> is data such as JavaScript object notation (JSON) files, which may require flattening prior to loading into your source system. When flattened, this data doesn't have to fit neatly into a table structure.

3) <h3>Unstructured data</h3> includes data stored as key-value pairs that don't adhere to standard relational models and Other types of unstructured data that are commonly used include portable data format (PDF), word processor documents, and images.

<h2>Data Operations</h2>
###Data integration
involves establishing links between operational and analytical services and data sources to enable secure, reliable access to data across multiple systems. For example, a business process might rely on data that is spread across multiple systems, and a data engineer is required to establish links so that the required data can be extracted from all of these systems.

Data transformation
Diagram representing a data transformation operation.

Operational data usually needs to be transformed into suitable structure and format for analysis, often as part of an extract, transform, and load (ETL) process; though increasingly a variation in which you extract, load, and transform (ELT) the data is used to quickly ingest the data into a data lake and then apply "big data" processing techniques to transform it. Regardless of the approach used, the data is prepared to support downstream analytical needs.

Data consolidation
Diagram representing a data consolidation operation.

Data consolidation is the process of combining data that has been extracted from multiple data sources into a consistent structure - usually to support analytics and reporting. Commonly, data from operational systems is extracted, transformed, and loaded into analytical stores such as a data lake or data warehouse.

Common languages
Data Engineers must be proficient with a range of tools and scripting languages - in particular SQL and Python, and potentially others.

SQL - One of the most common languages data engineers use is SQL, or Structured Query Language, which is a relatively easy language to learn. SQL uses queries that include SELECT, INSERT, UPDATE, and DELETE statements to directly work with the data stored in tables.

Python - Python is one of the most popular and fastest growing programming languages in the world. It's used for all sorts of tasks, including web programming and data analysis. It has emerged as the language to learn for machine learning, and is increasing in popularity in data engineering with the use of notebooks.

Others - Depending upon the needs of the organization and your individual skill set, you may also use other popular languages within or outside of notebooks including R, Java, Scala, .NET, and more. The use of notebooks is growing in popularity, and allows collaboration using different languages within the same notebook.




Important data engineering concepts
Completed
100 XP
6 minutes
There are some core concepts with which data engineers should be familiar. These concepts underpin many of the workloads that data engineers must implement and support.

Operational and analytical data
Diagram representing operational and analytical data.

Operational data is usually transactional data that is generated and stored by applications, often in a relational or non-relational database. Analytical data is data that has been optimized for analysis and reporting, often in a data warehouse.

One of the core responsibilities of a data engineer is to design, implement, and manage solutions that integrate operational and analytical data sources or extract operational data from multiple systems, transform it into appropriate structures for analytics, and load it into an analytical data store (usually referred to as ETL solutions).

Streaming data
Diagram representing streaming data.

Streaming data refers to perpetual sources of data that generate data values in real-time, often relating to specific events. Common sources of streaming data include internet-of-things (IoT) devices and social media feeds.

Data engineers often need to implement solutions that capture real-time stream of data and ingest them into analytical data systems, often combining the real-time data with other application data that is processed in batches.

Data pipelines
Diagram representing a data pipeline.

Data pipelines are used to orchestrate activities that transfer and transform data. Pipelines are the primary way in which data engineers implement repeatable extract, transform, and load (ETL) solutions that can be triggered based on a schedule or in response to events.

Data lakes
Diagram representing a data lake.

A data lake is a storage repository that holds large amounts of data in native, raw formats. Data lake stores are optimized for scaling to massive volumes (terabytes or petabytes) of data. The data typically comes from multiple heterogeneous sources, and may be structured, semi-structured, or unstructured.

The idea with a data lake is to store everything in its original, untransformed state. This approach differs from a traditional data warehouse, which transforms and processes the data at the time of ingestion.

Data warehouses
Diagram representing a data Warehouse.

A data warehouse is a centralized repository of integrated data from one or more disparate sources. Data warehouses store current and historical data in relational tables that are organized into a schema that optimizes performance for analytical queries.

Data engineers are responsible for designing and implementing relational data warehouses, and managing regular data loads into tables.

Apache Spark
Diagram representing an Apache Spark cluster.

Apache Spark is a parallel processing framework that takes advantage of in-memory processing and a distributed file storage. It's a common open-source software (OSS) tool for big data scenarios.

Data engineers need to be proficient with Spark, using notebooks and other code artifacts to process data in a data lake and prepare it for modeling and analysis.



There are some core concepts with which data engineers should be familiar. These concepts underpin many of the workloads that data engineers must implement and support.

Operational and analytical data
Diagram representing operational and analytical data.

Operational data is usually transactional data that is generated and stored by applications, often in a relational or non-relational database. Analytical data is data that has been optimized for analysis and reporting, often in a data warehouse.

One of the core responsibilities of a data engineer is to design, implement, and manage solutions that integrate operational and analytical data sources or extract operational data from multiple systems, transform it into appropriate structures for analytics, and load it into an analytical data store (usually referred to as ETL solutions).

Streaming data
Diagram representing streaming data.

Streaming data refers to perpetual sources of data that generate data values in real-time, often relating to specific events. Common sources of streaming data include internet-of-things (IoT) devices and social media feeds.

Data engineers often need to implement solutions that capture real-time stream of data and ingest them into analytical data systems, often combining the real-time data with other application data that is processed in batches.

Data pipelines
Diagram representing a data pipeline.

Data pipelines are used to orchestrate activities that transfer and transform data. Pipelines are the primary way in which data engineers implement repeatable extract, transform, and load (ETL) solutions that can be triggered based on a schedule or in response to events.

Data lakes
Diagram representing a data lake.

A data lake is a storage repository that holds large amounts of data in native, raw formats. Data lake stores are optimized for scaling to massive volumes (terabytes or petabytes) of data. The data typically comes from multiple heterogeneous sources, and may be structured, semi-structured, or unstructured.

The idea with a data lake is to store everything in its original, untransformed state. This approach differs from a traditional data warehouse, which transforms and processes the data at the time of ingestion.

Data warehouses
Diagram representing a data Warehouse.

A data warehouse is a centralized repository of integrated data from one or more disparate sources. Data warehouses store current and historical data in relational tables that are organized into a schema that optimizes performance for analytical queries.

Data engineers are responsible for designing and implementing relational data warehouses, and managing regular data loads into tables.

Apache Spark
Diagram representing an Apache Spark cluster.

Apache Spark is a parallel processing framework that takes advantage of in-memory processing and a distributed file storage. It's a common open-source software (OSS) tool for big data scenarios.

Data engineers need to be proficient with Spark, using notebooks and other code artifacts to process data in a data lake and prepare it for modeling and analysis.




![image](https://github.com/SoumiOnGit/Azure-Data-Engineering/assets/90122541/ff5d2fd2-c4e4-42fe-9f88-7ce4aea6dee6)























Enable Azure Data Lake Storage Gen2 in Azure Storage
Completed
100 XP
5 minutes
Azure Data Lake Storage Gen2 isn't a standalone Azure service, but rather a configurable capability of a StorageV2 (General Purpose V2) Azure Storage.

To enable Azure Data Lake Storage Gen2 in an Azure Storage account, you can select the option to Enable hierarchical namespace in the Advanced page when creating the storage account in the Azure portal:

Screenshot of Advanced Settings for Creating Storage Account.

Alternatively, if you already have an Azure Storage account and want to enable the Azure data Lake Storage Gen2 capability, you can use the Data Lake Gen2 upgrade wizard in the Azure portal page for your storage account resource.

Screenshot of Advanced Settings for Creating Storage Account.







Compare Azure Data Lake Store to Azure Blob storage
Completed
100 XP
5 minutes
In Azure Blob storage, you can store large amounts of unstructured ("object") data in a flat namespace within a blob container. Blob names can include "/" characters to organize blobs into virtual "folders", but in terms of blob manageability the blobs are stored as a single-level hierarchy in a flat namespace.

A diagram of a blob store with a flat namespace.

You can access this data by using HTTP or HTTPs

Azure Data Lake Storage Gen2 builds on blob storage and optimizes I/O of high-volume data by using a hierarchical namespace that organizes blob data into directories, and stores metadata about each directory and the files within it. This structure allows operations, such as directory renames and deletes, to be performed in a single atomic operation. Flat namespaces, by contrast, require several operations proportionate to the number of objects in the structure. Hierarchical namespaces keep the data organized, which yields better storage and retrieval performance for an analytical use case and lowers the cost of analysis.

A diagram of a blob store with a hierarchical namespace.

 Tip

<img width="175" alt="blob-store" src="https://github.com/SoumiOnGit/Azure-Data-Engineering/assets/90122541/2c471a5c-5187-4128-92d5-2d4fe84dbc0d">

<img width="175" alt="data-lake" src="https://github.com/SoumiOnGit/Azure-Data-Engineering/assets/90122541/803c1455-5687-4584-a87f-2c6adc084d1f">
























Understand the stages for processing big data
Completed
100 XP
5 minutes
Data lakes have a fundamental role in a wide range of big data architectures. These architectures can involve the creation of:

An enterprise data warehouse.
Advanced analytics against big data.
A real-time analytical solution.
There are four stages for processing big data solutions that are common to all architectures:

Ingest - The ingestion phase identifies the technology and processes that are used to acquire the source data. This data can come from files, logs, and other types of unstructured data that must be put into the data lake. The technology that is used will vary depending on the frequency that the data is transferred. For example, for batch movement of data, pipelines in Azure Synapse Analytics or Azure Data Factory may be the most appropriate technology to use. For real-time ingestion of data, Apache Kafka for HDInsight or Stream Analytics may be an appropriate choice.
Store - The store phase identifies where the ingested data should be placed. Azure Data Lake Storage Gen2 provides a secure and scalable storage solution that is compatible with commonly used big data processing technologies.
Prep and train - The prep and train phase identifies the technologies that are used to perform data preparation and model training and scoring for machine learning solutions. Common technologies that are used in this phase are Azure Synapse Analytics, Azure Databricks, Azure HDInsight, and Azure Machine Learning.
Model and serve - Finally, the model and serve phase involves the technologies that will present the data to users. These technologies can include visualization tools such as Microsoft Power BI, or analytical data stores such as Azure Synapse Analytics. Often, a combination of multiple technologies will be used depending on the business requirements.
















Use Azure Data Lake Storage Gen2 in data analytics workloads
Completed
100 XP
5 minutes
Azure Data Lake Store Gen2 is an enabling technology for multiple data analytics use cases. Let's explore a few common types of analytical workload, and identify how Azure Data Lake Storage Gen2 works with other Azure services to support them.

Big data processing and analytics
Diagram of Azure Data Lake Storage Gen2 being accessed from Azure Synapse Analytics, Azure Databricks, and Azure HDInsight.

Big data scenarios usually refer to analytical workloads that involve massive volumes of data in a variety of formats that needs to be processed at a fast velocity - the so-called "three v's". Azure Data Lake Storage Gen 2 provides a scalable and secure distributed data store on which big data services such as Azure Synapse Analytics, Azure Databricks, and Azure HDInsight can apply data processing frameworks such as Apache Spark, Hive, and Hadoop. The distributed nature of the storage and the processing compute enables tasks to be performed in parallel, resulting in high-performance and scalability even when processing huge amounts of data.

Data warehousing
Diagram of Azure Data Lake Storage Gen2 being used to support a data warehousing solution in Azure Synapse Analytics.

Data warehousing has evolved in recent years to integrate large volumes of data stored as files in a data lake with relational tables in a data warehouse. In a typical example of a data warehousing solution, data is extracted from operational data stores, such as Azure SQL database or Azure Cosmos DB, and transformed into structures more suitable for analytical workloads. Often, the data is staged in a data lake in order to facilitate distributed processing before being loaded into a relational data warehouse. In some cases, the data warehouse uses external tables to define a relational metadata layer over files in the data lake and create a hybrid "data lakehouse" or "lake database" architecture. The data warehouse can then support analytical queries for reporting and visualization.

There are multiple ways to implement this kind of data warehousing architecture. The diagram shows a solution in which Azure Synapse Analytics hosts pipelines to perform extract, transform, and load (ETL) processes using Azure Data Factory technology. These processes extract data from operational data sources and load it into a data lake hosted in an Azure Data Lake Storage Gen2 container. The data is then processed and loaded into a relational data warehouse in an Azure Synapse Analytics dedicated SQL pool, from where it can support data visualization and reporting using Microsoft Power BI.

Real-time data analytics
Diagram of Azure Data Lake Storage Gen2 being used to store the results of real-time data processing in Azure Stream Analytics.

Increasingly, businesses and other organizations need to capture and analyze perpetual streams of data, and analyze it in real-time (or as near to real-time as possible). These streams of data can be generated from connected devices (often referred to as internet-of-things or IoT devices) or from data generated by users in social media platforms or other applications. Unlike traditional batch processing workloads, streaming data requires a solution that can capture and process a boundless stream of data events as they occur.

Streaming events are often captured in a queue for processing. There are multiple technologies you can use to perform this task, including Azure Event Hubs as shown in the image. From here, the data is processed, often to aggregate data over temporal windows (for example to count the number of social media messages with a given tag every five minutes, or to calculate the average reading of an Internet connected sensor per minute). Azure Stream Analytics enables you to create jobs that query and aggregate event data as it arrives, and write the results in an output sink. One such sink is Azure Data Lake Storage Gen2; from where the captured real-time data can be analyzed and visualized.

Data science and machine learning
Diagram of Azure Data Lake Storage Gen2 being used as a source for Azure Machine Learning.

Data science involves the statistical analysis of large volumes of data, often using tools such as Apache Spark and scripting languages such as Python. Azure Data Lake Storage Gen 2 provides a highly scalable cloud-based data store for the volumes of data required in data science workloads.

Machine learning is a subarea of data science that deals with training predictive models. Model training requires huge amounts of data, and the ability to process that data efficiently. Azure Machine Learning is a cloud service in which data scientists can run Python code in notebooks using dynamically allocated distributed compute resources. The compute processes data in Azure Data Lake Storage Gen2 containers to train models, which can then be deployed as production web services to support predictive analytical workloads.




<img width="202" alt="big-data" src="https://github.com/SoumiOnGit/Azure-Data-Engineering/assets/90122541/eb38532c-3199-455d-a7c8-db9e25767795">


<img width="441" alt="data-warehouse" src="https://github.com/SoumiOnGit/Azure-Data-Engineering/assets/90122541/5cdc1299-16c8-459e-8397-00716ec3c708">

<img width="390" alt="real-time-analytics" src="https://github.com/SoumiOnGit/Azure-Data-Engineering/assets/90122541/cd46e7e9-f13b-47bc-ada6-37c571ac2c23">

<img width="160" alt="machine-learning" src="https://github.com/SoumiOnGit/Azure-Data-Engineering/assets/90122541/7f54a134-51fc-4d28-87e6-acbf11d30a5e">




Summary
Completed
100 XP
1 minute
Azure Data Lake Storage Gen2 provides a cloud storage service that is available, secure, durable, scalable, and redundant. It's a comprehensive data lake solution.

Azure Data Lake Storage brings efficiencies to process big data analytics workloads and can provide data to many compute technologies including Azure Synapse Analytics, Azure HDInsight, and Azure Databricks without needing to move the data around. Creating an Azure Data Lake Storage Gen2 data store can be an important tool in building a big data analytics solution.

 Tip

To learn more about Azure Data Lake Storage Gen2, see Introduction to Azure Data Lake Storage Gen2 in the Microsoft Azure documentation.






Introduction to Azure Synapse Analytics
1 hr 22 min
Module
7 Units
Beginner
Data Analyst
Data Engineer
Azure Synapse Analytics
Learn about the features and capabilities of Azure Synapse Analytics - a cloud-based platform for big data processing and analysis.

Learning objectives
In this module, you'll learn how to:

Identify the business problems that Azure Synapse Analytics addresses.
Describe core capabilities of Azure Synapse Analytics.
Determine when to use Azure Synapse Analytics.






introduction
Completed
100 XP
1 minute
The volume of data generated by individuals and organizations is growing at a phenomenal rate. This data powers businesses and other organizations by providing a basis for descriptive, diagnostic, predictive, and prescriptive analytical solutions that support decision making and autonomous systems by providing real-time insights into established and emerging patterns.

Organizations have a choice of many tools and techniques for data analytics, often requiring expertise across multiple systems and complex integration of infrastructure and administrative operations. Azure Synapse Analytics provides a single, cloud-scale platform that supports multiple analytical technologies; enabling a consolidated and integrated experience for data engineers, data analysts, data scientists, and other professionals who need to work with data.

In this module, you'll learn how to:

Identify the business problems that Azure Synapse Analytics addresses.
Describe core capabilities of Azure Synapse Analytics.
Determine when to use Azure Synapse Analytics.
Prerequisites
Before completing this module, you should have the following prerequisite knowledge and experience:

Familiarity with cloud computing concepts and Microsoft Azure.
Familiarity with fundamental data concepts.








What is Azure Synapse Analytics
Completed
100 XP
5 minutes
The technological research and consulting firm Gartner defines four common types of analytical technique that organizations commonly use:

Descriptive analytics, which answers the question “What is happening in my business?”. The data to answer this question is typically answered through the creation of a data warehouse in which historical data is persisted in relational tables for multidimensional modeling and reporting.

Diagnostic analytics, which deals with answering the question “Why is it happening?”. This may involve exploring information that already exists in a data warehouse, but typically involves a wider search of your data estate to find more data to support this type of analysis.

Predictive analytics, which enables you to answer the question “What is likely to happen in the future based on previous trends and patterns?”

Prescriptive analytics, which enables autonomous decision making based on real-time or near real-time analysis of data, using predictive analytics.

A diagram showing type of analytics.

Azure Synapse Analytics provides a cloud platform for all of these analytical workloads through support for multiple data storage, processing, and analysis technologies in a single, integrated solution. The integrated design of Azure Synapse Analytics enables organizations to leverage investments and skills in multiple commonly used data technologies, including SQL, Apache Spark, and others; while providing a centrally managed service and a single, consistent user interface.


![types-analytics](https://github.com/SoumiOnGit/Azure-Data-Engineering/assets/90122541/01f207c0-977e-41ce-9a2b-ecbc348717bc)












How Azure Synapse Analytics works
Completed
100 XP
8 minutes
To support the analytics needs of today's organizations, Azure Synapse Analytics combines a centralized service for data storage and processing with an extensible architecture through which linked services enable you to integrate commonly used data stores, processing platforms, and visualization tools.

Creating and using an Azure Synapse Analytics workspace
A Synapse Analytics workspace defines an instance of the Synapse Analytics service in which you can manage the services and data resources needed for your analytics solution. You can create a Synapse Analytics workspace in an Azure subscription interactively by using the Azure portal, or you can automate deployment by using Azure PowerShell, the Azure command-line interface (CLI), or with an Azure Resource Manager or Bicep template.

After creating a Synapse Analytics workspace, you can manage the services in it and perform data analytics tasks with them by using Synapse Studio; a web-based portal for Azure Synapse Analytics.

Screenshot of Azure Synapse Studio.

Working with files in a data lake
One of the core resources in a Synapse Analytics workspace is a data lake, in which data files can be stored and processed at scale. A workspace typically has a default data lake, which is implemented as a linked service to an Azure Data Lake Storage Gen2 container. You can add linked services for multiple data lakes that are based on different storage platforms as required.

Screenshot of a data lake linked service in Azure Studio.

Ingesting and transforming data with pipelines
In most enterprise data analytics solutions, data is extracted from multiple operational sources and transferred to a central data lake or data warehouse for analysis. Azure Synapse Analytics includes built-in support for creating, running, and managing pipelines that orchestrate the activities necessary to retrieve data from a range of sources, transform the data as required, and load the resulting transformed data into an analytical store.

Screenshot of a pipeline in Azure Synapse Studio.

 Note

Pipelines in Azure Synapse Analytics are based on the same underlying technology as Azure Data Factory. If you are already familiar with Azure Data Factory, you can leverage your existing skills to build data ingestion and transformation solutions in Azure Synapse Analytics.

Querying and manipulating data with SQL
Structured Query Language (SQL) is a ubiquitous language for querying and manipulating data, and is the foundation for relational databases, including the popular Microsoft SQL Server database platform. Azure Synapse Analytics supports SQL-based data querying and manipulation through two kinds of SQL pool that are based on the SQL Server relational database engine:

A built-in serverless pool that is optimized for using relational SQL semantics to query file-based data in a data lake.
Custom dedicated SQL pools that host relational data warehouses.
The Azure Synapse SQL system uses a distributed query processing model to parallelize SQL operations, resulting in a highly scalable solution for relational data processing. You can use the built-in serverless pool for cost-effective analysis and processing of file data in the data lake, and use dedicated SQL pools to create relational data warehouses for enterprise data modeling and reporting.

Screenshot of a SQL query and databases in Azure Synapse Studio.

Processing and analyzing data with Apache Spark
Apache Spark is an open source platform for big data analytics. Spark performs distributed processing of files in a data lake by running jobs that can be implemented using any of a range of supported programming languages. Languages supported in Spark include Python, Scala, Java, SQL, and C#.

In Azure Synapse Analytics, you can create one or more Spark pools and use interactive notebooks to combine code and notes as you build solutions for data analytics, machine learning, and data visualization.

Screenshot of a Spark notebook in Azure Synapse Studio.

Exploring data with Data Explorer
Azure Synapse Data Explorer is a data processing engine in Azure Synapse Analytics that is based on the Azure Data Explorer service. Data Explorer uses an intuitive query syntax named Kusto Query Language (KQL) to enable high performance, low-latency analysis of batch and streaming data.

Screenshot of a Kusto Query Language script in Azure Synapse Studio.

Integrating with other Azure data services
Azure Synapse Analytics can be integrated with other Azure data services for end-to-end analytics solutions. Integrated solutions include:

Azure Synapse Link enables near-realtime synchronization between operational data in Azure Cosmos DB, Azure SQL Database, SQL Server, and Microsoft Power Platform Dataverse and analytical data storage that can be queried in Azure Synapse Analytics.
Microsoft Power BI integration enables data analysts to integrate a Power BI workspace into a Synapse workspace, and perform interactive data visualization in Azure Synapse Studio.
Microsoft Purview integration enables organizations to catalog data assets in Azure Synapse Analytics, and makes it easier for data engineers to find data assets and track data lineage when implementing data pipelines that ingest data into Azure Synapse Analytics.
Azure Machine Learning integration enables data analysts and data scientists to integrate predictive model training and consumption into analytical solutions.



<img width="400" alt="synapse-studio" src="https://github.com/SoumiOnGit/Azure-Data-Engineering/assets/90122541/83956af8-be51-4d5c-8fad-def31feebe19">


<img width="400" alt="data-lake-store" src="https://github.com/SoumiOnGit/Azure-Data-Engineering/assets/90122541/06d34809-8dda-4ceb-a256-6d2250771f53">



<img width="400" alt="synapse-pipeline" src="https://github.com/SoumiOnGit/Azure-Data-Engineering/assets/90122541/f88da371-5311-4fd5-9824-9bab14414851">

<img width="400" alt="synapse-spark" src="https://github.com/SoumiOnGit/Azure-Data-Engineering/assets/90122541/e6032c9b-9816-48f3-9694-ee209380d06d">



<img width="400" alt="synapse-data-explorer" src="https://github.com/SoumiOnGit/Azure-Data-Engineering/assets/90122541/e71052b7-1d1d-4c65-a9f3-1c070ec10294">







When to use Azure Synapse Analytics
Completed
100 XP
4 minutes
Across all organizations and industries, the common use cases for Azure Synapse Analytics are identified by the need for:

Large-scale data warehousing
Data warehousing includes the need to integrate all data, including big data, to reason over data for analytics and reporting purposes from a descriptive analytics perspective, independent of its location or structure.

Advanced analytics
Enables organizations to perform predictive analytics using both the native features of Azure Synapse Analytics, and integrating with other technologies such as Azure Machine Learning.

Data exploration and discovery
The serverless SQL pool functionality provided by Azure Synapse Analytics enables Data Analysts, Data Engineers and Data Scientist alike to explore the data within your data estate. This capability supports data discovery, diagnostic analytics, and exploratory data analysis.

Real time analytics
Azure Synapse Analytics can capture, store and analyze data in real-time or near-real time with features such as Azure Synapse Link, or through the integration of services such as Azure Stream Analytics and Azure Data Explorer.

Data integration
Azure Synapse Pipelines enables you to ingest, prepare, model and serve the data to be used by downstream systems. This can be used by components of Azure Synapse Analytics exclusively.

Integrated analytics
With the variety of analytics that can be performed on the data at your disposal, putting together the services in a cohesive solution can be a complex operation. Azure Synapse Analytics removes this complexity by integrating the analytics landscape into one service. That way you can spend more time working with the data to bring business benefit, than spending much of your time provisioning and maintaining multiple systems to achieve the same outcomes.













Exercise - Explore Azure Synapse Analytics
Completed
100 XP
60 minutes
Now it's your chance to explore the capabilities of Azure Synapse Analytics for yourself. In this exercise, you'll use a provided script to provision an Azure Synapse Analytics workspace in your Azure subscription; and then use Azure Synapse Studio to perform core data analytics tasks.

 Note

To complete this lab, you will need an Azure subscription in which you have administrative access.








Use Azure Synapse serverless SQL pool to query files in a data lake
1 hr 8 min
Module
7 Units


Introduction
Completed
100 XP
1 minute
Azure Synapse Analytics includes serverless SQL pools, which are tailored for querying data in a data lake. With a serverless SQL pool you can use SQL code to query data in files of various common formats without needing to load the file data into database storage. This capability helps data analysts and data engineers analyze and process file data in the data lake using a familiar data processing language, without the need to create or maintain a relational database store.

After completing this module, you'll be able to:

Identify capabilities and use cases for serverless SQL pools in Azure Synapse Analytics
Query CSV, JSON, and Parquet files using a serverless SQL pool
Create external database objects in a serverless SQL pool
Prerequisites
Before starting this module, you should have the following prerequisite skills and knowledge:

Familiarity with the Microsoft Azure portal
Familiarity with data lake and data warehouse concepts
Experience of using SQL to query database tables









Understand Azure Synapse serverless SQL pool capabilities and use cases
Completed
100 XP
5 minutes
Azure Synapse Analytics is an integrated analytics service that brings together a wide range of commonly used technologies for processing and analyzing data at scale. One of the most prevalent technologies used in data solutions is SQL - an industry standard language for querying and manipulating data.

Serverless SQL pools in Azure Synapse Analytics
Azure Synapse SQL is a distributed query system in Azure Synapse Analytics that offers two kinds of runtime environments:

Serverless SQL pool: on-demand SQL query processing, primarily used to work with data in a data lake.
Dedicated SQL pool: Enterprise-scale relational database instances used to host data warehouses in which data is stored in relational tables.
In this module, we'll focus on serverless SQL pool, which provides a pay-per-query endpoint to query the data in your data lake. The benefits of using serverless SQL pool include:

A familiar Transact-SQL syntax to query data in place without the need to copy or load data into a specialized store.
Integrated connectivity from a wide range of business intelligence and ad-hoc querying tools, including the most popular drivers.
Distributed query processing that is built for large-scale data, and computational functions - resulting in fast query performance.
Built-in query execution fault-tolerance, resulting in high reliability and success rates even for long-running queries involving large data sets.
No infrastructure to setup or clusters to maintain. A built-in endpoint for this service is provided within every Azure Synapse workspace, so you can start querying data as soon as the workspace is created.
No charge for resources reserved, you're only charged for the data processed by queries you run.
When to use serverless SQL pools
Serverless SQL pool is tailored for querying the data residing in the data lake, so in addition to eliminating management burden, it eliminates a need to worry about ingesting the data into the system. You just point the query to the data that is already in the lake and run it.

Synapse SQL serverless resource model is great for unplanned or "bursty" workloads that can be processed using the always-on serverless SQL endpoint in your Azure Synapse Analytics workspace. Using the serverless pool helps when you need to know exact cost for each query executed to monitor and attribute costs.

 Note

Serverless SQL pool is an analytics system and is not recommended for OLTP workloads such as databases used by applications to store transactional data. Workloads that require millisecond response times and are looking to pinpoint a single row in a data set are not good fit for serverless SQL pool.

Common use cases for serverless SQL pools include:

Data exploration: Data exploration involves browsing the data lake to get initial insights about the data, and is easily achievable with Azure Synapse Studio. You can browse through the files in your linked data lake storage, and use the built-in serverless SQL pool to automatically generate a SQL script to select TOP 100 rows from a file or folder just as you would do with a table in SQL Server. From there, you can apply projections, filtering, grouping, and most of the operation over the data as if the data were in a regular SQL Server table.
Data transformation: While Azure Synapse Analytics provides great data transformations capabilities with Synapse Spark, some data engineers might find data transformation easier to achieve using SQL. Serverless SQL pool enables you to perform SQL-based data transformations; either interactively or as part of an automated data pipeline.
Logical data warehouse: After your initial exploration of the data in the data lake, you can define external objects such as tables and views in a serverless SQL database. The data remains stored in the data lake files, but are abstracted by a relational schema that can be used by client applications and analytical tools to query the data as they would in a relational database hosted in SQL Server.













Query files using a serverless SQL pool
Completed
100 XP
10 minutes
You can use a serverless SQL pool to query data files in various common file formats, including:

Delimited text, such as comma-separated values (CSV) files.
JavaScript object notation (JSON) files.
Parquet files.
The basic syntax for querying is the same for all of these types of file, and is built on the OPENROWSET SQL function; which generates a tabular rowset from data in one or more files. For example, the following query could be used to extract data from CSV files.

SQL

Copy
SELECT TOP 100 *
FROM OPENROWSET(
    BULK 'https://mydatalake.blob.core.windows.net/data/files/*.csv',
    FORMAT = 'csv') AS rows
The OPENROWSET function includes more parameters that determine factors such as:

The schema of the resulting rowset
Additional formatting options for delimited text files.
 Tip

You'll find the full syntax for the OPENROWSET function in the Azure Synapse Analytics documentation.

The output from OPENROWSET is a rowset to which an alias must be assigned. In the previous example, the alias rows is used to name the resulting rowset.

The BULK parameter includes the full URL to the location in the data lake containing the data files. This can be an individual file, or a folder with a wildcard expression to filter the file types that should be included. The FORMAT parameter specifies the type of data being queried. The example above reads delimited text from all .csv files in the files folder.

 Note

This example assumes that the user has access to the files in the underlying store, If the files are protected with a SAS key or custom identity, you would need to create a server-scoped credential.

As seen in the previous example, you can use wildcards in the BULK parameter to include or exclude files in the query. The following list shows a few examples of how this can be used:

https://mydatalake.blob.core.windows.net/data/files/file1.csv: Only include file1.csv in the files folder.
https://mydatalake.blob.core.windows.net/data/files/file*.csv: All .csv files in the files folder with names that start with "file".
https://mydatalake.blob.core.windows.net/data/files/*: All files in the files folder.
https://mydatalake.blob.core.windows.net/data/files/**: All files in the files folder, and recursively its subfolders.
You can also specify multiple file paths in the BULK parameter, separating each path with a comma.

Querying delimited text files
Delimited text files are a common file format within many businesses. The specific formatting used in delimited files can vary, for example:

With and without a header row.
Comma and tab-delimited values.
Windows and Unix style line endings.
Non-quoted and quoted values, and escaping characters.
Regardless of the type of delimited file you're using, you can read data from them by using the OPENROWSET function with the csv FORMAT parameter, and other parameters as required to handle the specific formatting details for your data. For example:

SQL

Copy
SELECT TOP 100 *
FROM OPENROWSET(
    BULK 'https://mydatalake.blob.core.windows.net/data/files/*.csv',
    FORMAT = 'csv',
    PARSER_VERSION = '2.0',
    FIRSTROW = 2) AS rows
The PARSER_VERSION is used to determine how the query interprets the text encoding used in the files. Version 1.0 is the default and supports a wide range of file encodings, while version 2.0 supports fewer encodings but offers better performance. The FIRSTROW parameter is used to skip rows in the text file, to eliminate any unstructured preamble text or to ignore a row containing column headings.

Additional parameters you might require when working with delimited text files include:

FIELDTERMINATOR - the character used to separate field values in each row. For example, a tab-delimited file separates fields with a TAB (\t) character. The default field terminator is a comma (,).
ROWTERMINATOR - the character used to signify the end of a row of data. For example, a standard Windows text file uses a combination of a carriage return (CR) and line feed (LF), which is indicated by the code \n; while UNIX-style text files use a single line feed character, which can be indicated using the code 0x0a.
FIELDQUOTE - the character used to enclose quoted string values. For example, to ensure that the comma in the address field value 126 Main St, apt 2 isn't interpreted as a field delimiter, you might enclose the entire field value in quotation marks like this: "126 Main St, apt 2". The double-quote (") is the default field quote character.
 Tip

For details of additional parameters when working with delimited text files, refer to the Azure Synapse Analytics documentation.

Specifying the rowset schema
It's common for delimited text files to include the column names in the first row. The OPENROWSET function can use this to define the schema for the resulting rowset, and automatically infer the data types of the columns based on the values they contain. For example, consider the following delimited text:

text

Copy
product_id,product_name,list_price
123,Widget,12.99
124,Gadget,3.99
The data consists of the following three columns:

product_id (integer number)
product_name (string)
list_price (decimal number)
You could use the following query to extract the data with the correct column names and appropriately inferred SQL Server data types (in this case INT, NVARCHAR, and DECIMAL)

SQL

Copy
SELECT TOP 100 *
FROM OPENROWSET(
    BULK 'https://mydatalake.blob.core.windows.net/data/files/*.csv',
    FORMAT = 'csv',
    PARSER_VERSION = '2.0',
    HEADER_ROW = TRUE) AS rows
The HEADER_ROW parameter (which is only available when using parser version 2.0) instructs the query engine to use the first row of data in each file as the column names, like this:

product_id	product_name	list_price
123	Widget	12.9900
124	Gadget	3.9900
Now consider the following data:

text

Copy
123,Widget,12.99
124,Gadget,3.99
This time, the file doesn't contain the column names in a header row; so while the data types can still be inferred, the column names will be set to C1, C2, C3, and so on.

C1	C2	C3
123	Widget	12.9900
124	Gadget	3.9900
To specify explicit column names and data types, you can override the default column names and inferred data types by providing a schema definition in a WITH clause, like this:

SQL

Copy
SELECT TOP 100 *
FROM OPENROWSET(
    BULK 'https://mydatalake.blob.core.windows.net/data/files/*.csv',
    FORMAT = 'csv',
    PARSER_VERSION = '2.0')
WITH (
    product_id INT,
    product_name VARCHAR(20) COLLATE Latin1_General_100_BIN2_UTF8,
    list_price DECIMAL(5,2)
) AS rows
This query produces the expected results:

product_id	product_name	list_price
123	Widget	12.99
124	Gadget	3.99
 Tip

When working with text files, you may encounter some incompatibility with UTF-8 encoded data and the collation used in the master database for the serverless SQL pool. To overcome this, you can specify a compatible collation for individual VARCHAR columns in the schema. See the troubleshooting guidance for more details.

Querying JSON files
JSON is a popular format for web applications that exchange data through REST interfaces or use NoSQL data stores such as Azure Cosmos DB. So, it's not uncommon to persist data as JSON documents in files in a data lake for analysis.

For example, a JSON file that defines an individual product might look like this:

JSON

Copy
{
    "product_id": 123,
    "product_name": "Widget",
    "list_price": 12.99
}
To return product data from a folder containing multiple JSON files in this format, you could use the following SQL query:

SQL

Copy
SELECT doc
FROM
    OPENROWSET(
        BULK 'https://mydatalake.blob.core.windows.net/data/files/*.json',
        FORMAT = 'csv',
        FIELDTERMINATOR ='0x0b',
        FIELDQUOTE = '0x0b',
        ROWTERMINATOR = '0x0b'
    ) WITH (doc NVARCHAR(MAX)) as rows
OPENROWSET has no specific format for JSON files, so you must use csv format with FIELDTERMINATOR, FIELDQUOTE, and ROWTERMINATOR set to 0x0b, and a schema that includes a single NVARCHAR(MAX) column. The result of this query is a rowset containing a single column of JSON documents, like this:

doc
{"product_id":123,"product_name":"Widget","list_price": 12.99}
{"product_id":124,"product_name":"Gadget","list_price": 3.99}
To extract individual values from the JSON, you can use the JSON_VALUE function in the SELECT statement, as shown here:

SQL

Copy
SELECT JSON_VALUE(doc, '$.product_name') AS product,
           JSON_VALUE(doc, '$.list_price') AS price
FROM
    OPENROWSET(
        BULK 'https://mydatalake.blob.core.windows.net/data/files/*.json',
        FORMAT = 'csv',
        FIELDTERMINATOR ='0x0b',
        FIELDQUOTE = '0x0b',
        ROWTERMINATOR = '0x0b'
    ) WITH (doc NVARCHAR(MAX)) as rows
This query would return a rowset similar to the following results:

product	price
Widget	12.99
Gadget	3.99
Querying Parquet files
Parquet is a commonly used format for big data processing on distributed file storage. It's an efficient data format that is optimized for compression and analytical querying.

In most cases, the schema of the data is embedded within the Parquet file, so you only need to specify the BULK parameter with a path to the file(s) you want to read, and a FORMAT parameter of parquet; like this:

SQL

Copy
SELECT TOP 100 *
FROM OPENROWSET(
    BULK 'https://mydatalake.blob.core.windows.net/data/files/*.*',
    FORMAT = 'parquet') AS rows
Query partitioned data
It's common in a data lake to partition data by splitting across multiple files in subfolders that reflect partitioning criteria. This enables distributed processing systems to work in parallel on multiple partitions of the data, or to easily eliminate data reads from specific folders based on filtering criteria. For example, suppose you need to efficiently process sales order data, and often need to filter based on the year and month in which orders were placed. You could partition the data using folders, like this:

/orders
/year=2020
/month=1
/01012020.parquet
/02012020.parquet
...
/month=2
/01022020.parquet
/02022020.parquet
...
...
/year=2021
/month=1
/01012021.parquet
/02012021.parquet
...
...
To create a query that filters the results to include only the orders for January and February 2020, you could use the following code:

SQL

Copy
SELECT *
FROM OPENROWSET(
    BULK 'https://mydatalake.blob.core.windows.net/data/orders/year=*/month=*/*.*',
    FORMAT = 'parquet') AS orders
WHERE orders.filepath(1) = '2020'
    AND orders.filepath(2) IN ('1','2');
The numbered filepath parameters in the WHERE clause reference the wildcards in the folder names in the BULK path -so the parameter 1 is the * in the year=* folder name, and parameter 2 is the * in the month=* folder name.























Create external database objects
Completed
100 XP
6 minutes
You can use the OPENROWSET function in SQL queries that run in the default master database of the built-in serverless SQL pool to explore data in the data lake. However, sometimes you may want to create a custom database that contains some objects that make it easier to work with external data in the data lake that you need to query frequently.

Creating a database
You can create a database in a serverless SQL pool just as you would in a SQL Server instance. You can use the graphical interface in Synapse Studio, or a CREATE DATABASE statement. One consideration is to set the collation of your database so that it supports conversion of text data in files to appropriate Transact-SQL data types.

The following example code creates a database named salesDB with a collation that makes it easier to import UTF-8 encoded text data into VARCHAR columns.

SQL

Copy
CREATE DATABASE SalesDB
    COLLATE Latin1_General_100_BIN2_UTF8
Creating an external data source
You can use the OPENROWSET function with a BULK path to query file data from your own database, just as you can in the master database; but if you plan to query data in the same location frequently, it's more efficient to define an external data source that references that location. For example, the following code creates a data source named files for the hypothetical https://mydatalake.blob.core.windows.net/data/files/ folder:

SQL

Copy
CREATE EXTERNAL DATA SOURCE files
WITH (
    LOCATION = 'https://mydatalake.blob.core.windows.net/data/files/'
)
One benefit of an external data source, is that you can simplify an OPENROWSET query to use the combination of the data source and the relative path to the folders or files you want to query:

SQL

Copy
SELECT *
FROM
    OPENROWSET(
        BULK 'orders/*.csv',
        DATA_SOURCE = 'files',
        FORMAT = 'csv',
        PARSER_VERSION = '2.0'
    ) AS orders
In this example, the BULK parameter is used to specify the relative path for all .csv files in the orders folder, which is a subfolder of the files folder referenced by the data source.

Another benefit of using a data source is that you can assign a credential for the data source to use when accessing the underlying storage, enabling you to provide access to data through SQL without permitting users to access the data directly in the storage account. For example, the following code creates a credential that uses a shared access signature (SAS) to authenticate against the underlying Azure storage account hosting the data lake.

SQL

Copy
CREATE DATABASE SCOPED CREDENTIAL sqlcred
WITH
    IDENTITY='SHARED ACCESS SIGNATURE',  
    SECRET = 'sv=xxx...';
GO

CREATE EXTERNAL DATA SOURCE secureFiles
WITH (
    LOCATION = 'https://mydatalake.blob.core.windows.net/data/secureFiles/'
    CREDENTIAL = sqlcred
);
GO
 Tip

In addition to SAS authentication, you can define credentials that use managed identity (the Microsoft Entra identity used by your Azure Synapse workspace), a specific Microsoft Entra principal, or passthrough authentication based on the identity of the user running the query (which is the default type of authentication). To learn more about using credentials in a serverless SQL pool, see the Control storage account access for serverless SQL pool in Azure Synapse Analytics article in Azure Synapse Analytics documentation.

Creating an external file format
While an external data source simplifies the code needed to access files with the OPENROWSET function, you still need to provide format details for the file being access; which may include multiple settings for delimited text files. You can encapsulate these settings in an external file format, like this:

SQL

Copy
CREATE EXTERNAL FILE FORMAT CsvFormat
    WITH (
        FORMAT_TYPE = DELIMITEDTEXT,
        FORMAT_OPTIONS(
            FIELD_TERMINATOR = ',',
            STRING_DELIMITER = '"'
        )
    );
GO
After creating file formats for the specific data files you need to work with, you can use the file format to create external tables, as discussed next.

Creating an external table
When you need to perform a lot of analysis or reporting from files in the data lake, using the OPENROWSET function can result in complex code that includes data sources and file paths. To simplify access to the data, you can encapsulate the files in an external table; which users and reporting applications can query using a standard SQL SELECT statement just like any other database table. To create an external table, use the CREATE EXTERNAL TABLE statement, specifying the column schema as for a standard table, and including a WITH clause specifying the external data source, relative path, and external file format for your data.

SQL

Copy
CREATE EXTERNAL TABLE dbo.products
(
    product_id INT,
    product_name VARCHAR(20),
    list_price DECIMAL(5,2)
)
WITH
(
    DATA_SOURCE = files,
    LOCATION = 'products/*.csv',
    FILE_FORMAT = CsvFormat
);
GO

-- query the table
SELECT * FROM dbo.products;
By creating a database that contains the external objects discussed in this unit, you can provide a relational database layer over files in a data lake, making it easier for many data analysts and reporting tools to access the data by using standard SQL query semantics.










Knowledge check
200 XP
5 minutes

1. What function is used to read the data in files stored in a data lake? 

FORMAT

ROWSET

OPENROWSET
2. What character in file path can be used to select all the file/folders that match rest of the path? 

&

*

/
3. Which external database object encapsulates the connection information to a file location in a data lake store? 

FILE FORMAT

DATA SOURCE

EXTERNAL TABLE










Use Azure Synapse serverless SQL pools to transform data in a data lake




Introduction
Completed
100 XP
1 minute
While SQL is commonly used by data analysts to query data and support analytical and reporting workloads, data engineers often need to use SQL to transform data; often as part of a data ingestion pipeline or extract, transform, and load (ETL) process.

In this module, you'll learn how to use CREATE EXTERNAL TABLE AS SELECT (CETAS) statements to transform data, and store the results in files in a data lake that can be queried through a relational table in a serverless SQL database or processed directly from the file system.

After completing this module, you'll be able to:

Use a CREATE EXTERNAL TABLE AS SELECT (CETAS) statement to transform data.
Encapsulate a CETAS statement in a stored procedure.
Include a data transformation stored procedure in a pipeline.
Prerequisites
Before starting this module, you should have the following prerequisite skills and knowledge:

Familiarity with Azure Synapse Analytics.
Experience using Transact-SQL to query and manipulate data.




Transform data files with the CREATE EXTERNAL TABLE AS SELECT statement
Completed
100 XP
5 minutes
The SQL language includes many features and functions that enable you to manipulate data. For example, you can use SQL to:

Filter rows and columns in a dataset.
Rename data fields and convert between data types.
Calculate derived data fields.
Manipulate string values.
Group and aggregate data.
Azure Synapse serverless SQL pools can be used to run SQL statements that transform data and persist the results as a file in a data lake for further processing or querying. If you're familiar with Transact-SQL syntax, you can craft a SELECT statement that applies the specific transformation you're interested in, and store the results of the SELECT statement in a selected file format with a metadata table schema that can be queried using SQL.

You can use a CREATE EXTERNAL TABLE AS SELECT (CETAS) statement in a dedicated SQL pool or serverless SQL pool to persist the results of a query in an external table, which stores its data in a file in the data lake.

The CETAS statement includes a SELECT statement that queries and manipulates data from any valid data source (which could be an existing table or view in a database, or an OPENROWSET function that reads file-based data from the data lake). The results of the SELECT statement are then persisted in an external table, which is a metadata object in a database that provides a relational abstraction over data stored in files. The following diagram illustrates the concept visually:

A diagram showing a CREATE EXTERNAL TABLE AS SELECT statement saving query results as a file.

By applying this technique, you can use SQL to extract and transform data from files or tables, and store the transformed results for downstream processing or analysis. Subsequent operations on the transformed data can be performed against the relational table in the SQL pool database or directly against the underlying data files.

Creating external database objects to support CETAS
To use CETAS expressions, you must create the following types of object in a database for either a serverless or dedicated SQL pool. When using a serverless SQL pool, create these objects in a custom database (created using the CREATE DATABASE statement), not the built-in database.

External data source
An external data source encapsulates a connection to a file system location in a data lake. You can then use this connection to specify a relative path in which the data files for the external table created by the CETAS statement are saved.

If the source data for the CETAS statement is in files in the same data lake path, you can use the same external data source in the OPENROWSET function used to query it. Alternatively, you can create a separate external data source for the source files or use a fully qualified file path in the OPENROWSET function.

To create an external data source, use the CREATE EXTERNAL DATA SOURCE statement, as shown in this example:

SQL

Copy
CREATE EXTERNAL DATA SOURCE files
WITH (
    LOCATION = 'https://mydatalake.blob.core.windows.net/data/files/'
);
The previous example assumes that users running queries that use the external data source will have sufficient permissions to access the files. An alternative approach is to encapsulate a credential in the external data source so that it can be used to access file data without granting all users permissions to read it directly:

SQL

Copy
CREATE DATABASE SCOPED CREDENTIAL storagekeycred
WITH
    IDENTITY='SHARED ACCESS SIGNATURE',  
    SECRET = 'sv=xxx...';

CREATE EXTERNAL DATA SOURCE secureFiles
WITH (
    LOCATION = 'https://mydatalake.blob.core.windows.net/data/secureFiles/'
    CREDENTIAL = storagekeycred
);
 Tip

In addition to SAS authentication, you can define credentials that use managed identity (the Microsoft Entra identity used by your Azure Synapse workspace), a specific Microsoft Entra principal, or passthrough authentication based on the identity of the user running the query (which is the default type of authentication). To learn more about using credentials in a serverless SQL pool, see the Control storage account access for serverless SQL pool in Azure Synapse Analytics article in Azure Synapse Analytics documentation.

External file format
The CETAS statement creates a table with its data stored in files. You must specify the format of the files you want to create as an external file format.

To create an external file format, use the CREATE EXTERNAL FILE FORMAT statement, as shown in this example:

SQL

Copy
CREATE EXTERNAL FILE FORMAT ParquetFormat
WITH (
        FORMAT_TYPE = PARQUET,
        DATA_COMPRESSION = 'org.apache.hadoop.io.compress.SnappyCodec'
    );
 Tip

In this example, the files will be saved in Parquet format. You can also create external file formats for other types of file. See CREATE EXTERNAL FILE FORMAT (Transact-SQL) for details.

Using the CETAS statement
After creating an external data source and external file format, you can use the CETAS statement to transform data and stored the results in an external table.

For example, suppose the source data you want to transform consists of sales orders in comma-delimited text files that are stored in a folder in a data lake. You want to filter the data to include only orders that are marked as "special order", and save the transformed data as Parquet files in a different folder in the same data lake. You could use the same external data source for both the source and destination folders as shown in this example:

SQL

Copy
CREATE EXTERNAL TABLE SpecialOrders
    WITH (
        -- details for storing results
        LOCATION = 'special_orders/',
        DATA_SOURCE = files,
        FILE_FORMAT = ParquetFormat
    )
AS
SELECT OrderID, CustomerName, OrderTotal
FROM
    OPENROWSET(
        -- details for reading source files
        BULK 'sales_orders/*.csv',
        DATA_SOURCE = 'files',
        FORMAT = 'CSV',
        PARSER_VERSION = '2.0',
        HEADER_ROW = TRUE
    ) AS source_data
WHERE OrderType = 'Special Order';
The LOCATION and BULK parameters in the previous example are relative paths for the results and source files respectively. The paths are relative to the file system location referenced by the files external data source.

An important point to understand is that you must use an external data source to specify the location where the transformed data for the external table is to be saved. When file-based source data is stored in the same folder hierarchy, you can use the same external data source. Otherwise, you can use a second data source to define a connection to the source data or use the fully qualified path, as shown in this example:

SQL

Copy
CREATE EXTERNAL TABLE SpecialOrders
    WITH (
        -- details for storing results
        LOCATION = 'special_orders/',
        DATA_SOURCE = files,
        FILE_FORMAT = ParquetFormat
    )
AS
SELECT OrderID, CustomerName, OrderTotal
FROM
    OPENROWSET(
        -- details for reading source files
        BULK 'https://mystorage.blob.core.windows.net/data/sales_orders/*.csv',
        FORMAT = 'CSV',
        PARSER_VERSION = '2.0',
        HEADER_ROW = TRUE
    ) AS source_data
WHERE OrderType = 'Special Order';
Dropping external tables
If you no longer need the external table containing the transformed data, you can drop it from the database by using the DROP EXTERNAL TABLE statement, as shown here:

SQL

Copy
DROP EXTERNAL TABLE SpecialOrders;
However, it's important to understand that external tables are a metadata abstraction over the files that contain the actual data. Dropping an external table does not delete the underlying files.




<img width="300" alt="create-external-table-as-select" src="https://github.com/SoumiOnGit/Azure-Data-Engineering/assets/90122541/188e9838-a651-4e9e-8655-304e81d4b648">
























 Encapsulate data transformations in a stored procedure
Completed
100 XP
4 minutes
While you can run a CREATE EXTERNAL TABLE AS SELECT (CETAS) statement in a script whenever you need to transform data, it's good practice to encapsulate the transformation operation in stored procedure. This approach can make it easier to operationalize data transformations by enabling you to supply parameters, retrieve outputs, and include additional logic in a single procedure call.

For example, the following code creates a stored procedure that drops the external table if it already exists before recreating it with order data for the specified year:

SQL

Copy
CREATE PROCEDURE usp_special_orders_by_year @order_year INT
AS
BEGIN

	-- Drop the table if it already exists
	IF EXISTS (
                SELECT * FROM sys.external_tables
                WHERE name = 'SpecialOrders'
            )
        DROP EXTERNAL TABLE SpecialOrders

	-- Create external table with special orders
	-- from the specified year
	CREATE EXTERNAL TABLE SpecialOrders
		WITH (
			LOCATION = 'special_orders/',
			DATA_SOURCE = files,
			FILE_FORMAT = ParquetFormat
		)
	AS
	SELECT OrderID, CustomerName, OrderTotal
	FROM
		OPENROWSET(
			BULK 'sales_orders/*.csv',
			DATA_SOURCE = 'files',
			FORMAT = 'CSV',
			PARSER_VERSION = '2.0',
			HEADER_ROW = TRUE
		) AS source_data
	WHERE OrderType = 'Special Order'
	AND YEAR(OrderDate) = @order_year
END
 Note

As discussed previously, dropping an existing external table does not delete the folder containing its data files. You must explicitly delete the target folder if it exists before running the stored procedure, or an error will occur.

In addition to encapsulating Transact-SQL logic, stored procedures also provide the following benefits:

Reduces client to server network traffic
The commands in a procedure are executed as a single batch of code; which can significantly reduce network traffic between the server and client because only the call to execute the procedure is sent across the network.

Provides a security boundary
Multiple users and client programs can perform operations on underlying database objects through a procedure, even if the users and programs don't have direct permissions on those underlying objects. The procedure controls what processes and activities are performed and protects the underlying database objects; eliminating the requirement to grant permissions at the individual object level and simplifies the security layers.

Eases maintenance
Any changes in the logic or file system locations involved in the data transformation can be applied only to the stored procedure; without requiring updates to client applications or other calling functions.

Improved performance
Stored procedures are compiled the first time they're executed, and the resulting execution plan is held in the cache and reused on subsequent runs of the same stored procedure. As a result, it takes less time to process the procedure.

















Include a data transformation stored procedure in a pipeline
Completed
100 XP
3 minutes
Encapsulating a CREATE EXTERNAL TABLE AS SELECT (CETAS) statement in a stored procedure makes it easier for you to operationalize data transformations that you may need to perform repeatedly. In Azure Synapse Analytics and Azure Data Factory, you can create pipelines that connect to linked services, including Azure Data Lake Store Gen2 storage accounts that host data lake files, and serverless SQL pools; enabling you to call your stored procedures as part of an overall data extract, transform, and load (ETL) pipeline.

For example, you can create a pipeline that includes the following activities:

A Delete activity that deletes the target folder for the transformed data in the data lake if it already exists.
A Stored procedure activity that connects to your serverless SQL pool and runs the stored procedure that encapsulates your CETAS operation.
A screenshot of a pipeline containing a Delete activity and a Stored procedure activity.

Creating a pipeline for the data transformation enables you to schedule the operation to run at specific times or based on specific events (such as new files being added to the source storage location).

 Tip

For more information about using the Stored procedure activity in a pipeline, see Transform data by using the SQL Server Stored Procedure activity in Azure Data Factory or Synapse Analytics in the Azure Data Factory documentation.

