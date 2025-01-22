# NYC-Taxi-Azure-Pipeline

## Key Learnings & Implementations 📚

### 1. **Data Architecture & Medallion Architecture** 🏗️
   - Gained an understanding of different data architectures, with a focus on the **Medallion Architecture** for organizing data lakes.
   - Implemented best practices for structuring raw, processed, and curated data in a way that supports efficient analytics.

### 2. **Azure Fundamentals** ☁️
   - Developed a solid foundation in **Azure** cloud services and its core concepts, including resource management, storage, and computing.
   - Hands-on experience creating and configuring **Azure Resource Groups** and **Azure Storage Accounts** for project setup.

### 3. **Data Lake Configuration & Management** 🌲
   - Configured **Azure Data Lake** for storing large-scale data efficiently and securely.
   - Implemented data access strategies and ensured data governance best practices within the lake.

### 4. **Azure Data Factory (ADF)** 🛠️
   - Learned how to create and configure **Azure Data Factory** pipelines for seamless data ingestion, transformation, and orchestration.
   - **API Integration:** Set up an ADF pipeline to read data from an external API and ingest it into **Azure Data Lake Storage (ADLS)**.
     - Configured an **API Linked Service** in ADF to authenticate and connect to the external API.
     - Parametrically set up API parameters (such as authentication tokens and headers) in the pipeline to ensure secure and dynamic access to the API using **Service Principal** for authentication.
     - Integrated **Entra ID (Azure Active Directory)** for managing permissions and ensuring secure access to Azure resources.
     - Used the **Copy Data** activity in ADF to pull data from the API and store it in ADLS, automating the process of data ingestion.

### 5. **Databricks Setup & Management** 🖥️
   - Set up **Azure Databricks** free accounts and clusters for running Spark-based analytics.
   - Gained hands-on experience with **PySpark**, using it to read, transform, and analyze large datasets.
   - Configured **Service Principal** to allow **Azure Databricks** to securely access the **Azure Data Lake**, enabling seamless integration for data processing.

### 6. **Data Transformation & Analysis with PySpark** 🔄
   - Used **PySpark** to perform data transformations such as filtering, aggregations, and joins.
   - Applied PySpark to process large datasets, leveraging Spark's distributed computing power for enhanced performance.

### 7. **Delta Lake & Delta Tables** 🏞️
   - Implemented **Delta Lake** in Databricks for efficient data storage, with **Delta Tables** for handling large datasets with ACID transactions.
   - Configured and worked with **Managed vs External Delta Tables** for optimized data processing workflows.
   - Explored **Delta Logs** to track changes and ensure data integrity.
   - Utilized **Time Travel** to query historical versions of data for auditing and troubleshooting.

### 8. **Data Versioning & Querying Delta Tables** ⏳
   - Managed **data versioning** in Delta Tables to enable rollback and safe updates.
   - Wrote efficient queries to interact with Delta Lake, enabling real-time analytics on large datasets.

### 9. **Connecting Databricks to BI Tools** 📊
   - Connected **Azure Databricks** to various **BI tools** to enable data visualization and reporting, enhancing data accessibility for business users.

---

## Conclusion 🎯

Through this course, I gained practical experience in implementing cloud-based data pipelines, real-time data processing, and data analytics using **Azure** and **Databricks**. I learned how to work with large datasets in a distributed environment, configure scalable storage solutions, and build efficient data pipelines for complex analytics scenarios. The integration of **Azure Data Factory** for API-based data ingestion to **Azure Data Lake**, with secure authentication using **Service Principal** (for Databricks to access Data Lake) and **Entra ID (Azure Active Directory)** for managing permissions, was a key achievement, demonstrating my ability to automate and orchestrate data workflows programmatically.

### 9. **Connecting Databricks to BI Tools** 📊
   - Connected **Azure Databricks** to various **BI tools** to enable data visualization and reporting, enhancing data accessibility for business users.
