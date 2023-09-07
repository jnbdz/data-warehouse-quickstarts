# data-warehouse-quickstarts
Data warehouse (DW) quickstarts!

## Definition
"Data Lake," "Data Warehouse," and "Data Lakehouse" are terms often used in the big data and analytics domain. Here's a comparison:

### Data Lake

- **Nature:** A data lake is a storage repository that holds a vast amount of raw data in its native format, including structured, semi-structured, and unstructured data.
- **Data Type:** Accepts any data – from structured to unstructured.
- **Schema:** Schema-on-read. This means the schema is applied only when reading the data, allowing for flexibility in storing various types of data.
- **Storage Cost:** Typically uses low-cost storage.
- **Purpose:** Data lakes are particularly suitable for big data and real-time analytics. They allow organizations to store all their data in one place and analyze it later as needed.
- **Query Performance:** Can be slower compared to data warehouses due to the absence of predefined schemas.
- **Tools:** Hadoop, Apache Spark, Amazon S3, Azure Data Lake, etc.

### Data Warehouse

- **Nature:** A data warehouse is a large, centralized database that is optimized to analyze relational data coming from transactional systems, operational databases, and line of business applications.
- **Data Type:** Primarily structured data.
- **Schema:** Schema-on-write. This means the schema is defined before writing the data.
- **Storage Cost:** Typically more expensive than data lakes due to optimizations for querying and the use of specialized systems.
- **Purpose:** Data warehouses are designed for complex queries and data analysis. They often involve data that has been cleaned, integrated, and consolidated from multiple sources.
- **Query Performance:** Fast, thanks to indexed and optimized storage.
- **Tools:** Google BigQuery, Amazon Redshift, Snowflake, Teradata, etc.

### Data Lakehouse

- **Nature:** A data lakehouse is a hybrid approach that aims to combine the best features of data lakes and data warehouses.
- **Data Type:** Handles both structured and unstructured data.
- **Schema:** Combines schema-on-read and schema-on-write, offering flexibility in storage and optimized querying.
- **Storage Cost:** Aims to offer a balance between the low-cost storage of data lakes and the performance optimizations of data warehouses.
- **Purpose:** It aims to provide the scalability and flexibility of a data lake with the performance and querying capabilities of a data warehouse. Supports BI (Business Intelligence) tasks, advanced analytics, and other data operations.
- **Query Performance:** Optimized for fast query performance while maintaining the flexibility of data lakes.
- **Tools:** Databricks Delta Lake, Apache Iceberg, etc.

### Conclusion

While data lakes are suited for storing vast amounts of raw data and data warehouses are optimized for high-speed querying of structured data, the data lakehouse paradigm attempts to offer the best of both worlds. The choice between these architectures often depends on the specific requirements, budget, and future goals of an organization.

## Data Management Body of Knowledge (DMBOK)
Books: 
- https://technicspub.com/dmbok/
- [The DAMA Dictionary of Data Management, 2nd Edition](https://www.amazon.ca/DAMA-Dictionary-Data-Management-2nd/dp/1935504126/)
- [The DAMA Guide to the Data Management Body of Knowledge Print Edition (The equivalent of the PMBOK or the BABOK, the DAMA-DMBOK)](https://www.amazon.ca/gp/product/1935504029/)
- [Navigating the Labyrinth: An Executive Guide to Data Management](https://www.amazon.ca/gp/product/1634623754/)
- [DAMA-DMBOK: Data Management Body of Knowledge: 2nd Edition](https://www.amazon.ca/gp/product/1634622340/)
- [Data Governance: How to Design, Deploy, and Sustain an Effective Data Governance Program](https://www.amazon.ca/gp/product/012815831X/)
- [The Data Warehouse ETL Toolkit: Practical Techniques for Extracting, Cleaning, Conforming, and Delivering Data](https://www.amazon.ca/gp/product/0764567578/)
- [The Data Warehouse Toolkit: The Definitive Guide to Dimensional Modeling](https://www.amazon.ca/gp/product/1118530802/)
- [The Data Warehouse Lifecycle Toolkit](https://www.amazon.ca/gp/product/0470149779/)
