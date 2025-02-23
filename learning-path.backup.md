# Data Engineer Skills and Learning Path 2025

## Phase 1: Foundations - Building Your Core Knowledge

**Goal:** Establish a strong base in computer science fundamentals and essential programming skills.

* **Computer Science Essentials:**
    * Master the command line (Bash, Zsh):
        * [Linux Command Line Basics](https://www.digitalocean.com/community/tutorials/basic-linux-navigation-and-file-management) - DigitalOcean tutorial for beginners.
        * [Learn Shell Scripting](https://www.shellscript.sh/) - Interactive shell scripting tutorial.
        * **Practice:**
            * Navigate directories, create/delete/rename files and folders.
            * Use `grep`, `sed`, and `awk` for text processing.
            * Write simple shell scripts to automate tasks.
    * Grasp core data structures and algorithms, understanding their time and space complexity:
        * [Introduction to Algorithms (CLRS)](https://mitpress.mit.edu/9780262033848/introduction-to-algorithms/) - Classic textbook.
        * [LeetCode](https://leetcode.com/) - Practice coding problems.
        * **Practice:**
            * Implement linked lists, stacks, queues, and trees.
            * Solve sorting and searching algorithms (e.g., binary search, merge sort).
            * Analyze the time and space complexity of your solutions.
    * Learn to interact with and design APIs (REST, GraphQL):
        * [REST API Tutorial](https://restfulapi.net/) - Introduction to RESTful API concepts.
        * [GraphQL Official Site](https://graphql.org/) - GraphQL documentation.
        * **Practice:**
            * Use `curl` or Postman to interact with public APIs.
            * Create a simple rest API using a python framework like flask, or fastapi.
            * Understand the differences between REST and GraphQL.
    * Become proficient in version control using Git and platforms like GitHub/GitLab/Bitbucket:
        * [Pro Git Book](https://git-scm.com/book/en/v2) - Comprehensive Git documentation.
        * [GitHub Learning Lab](https://lab.github.com/) - Interactive Git and GitHub tutorials.
        * **Practice:**
            * Initialize Git repositories, commit changes, and create branches.
            * Collaborate on projects using pull requests and code reviews.
            * Understand git merge and git rebase.
* **Programming Proficiency:**
    * **Python (Essential):**
        * [Python Official Documentation](https://docs.python.org/3/) - Official Python documentation.
        * [Pandas Documentation](https://pandas.pydata.org/docs/) - Pandas library documentation.
        * [NumPy Documentation](https://numpy.org/doc/stable/) - NumPy library documentation.
        * [Learning Spark: Lightning-Fast Data Analytics](https://www.oreilly.com/library/view/learning-spark-lightning-fast/9781449358624/) - Introduction to Spark with Python.
        * [TensorFlow Documentation](https://www.tensorflow.org/overview) - TensorFlow documentation.
        * [PyTorch Documentation](https://pytorch.org/docs/stable/index.html) - PyTorch documentation.
        * **Practice:**
            * Write Python scripts to manipulate data from CSV and JSON files.
            * Use Pandas and NumPy for data analysis and transformation.
            * Create basic machine learning models using scikit-learn.
    * **SQL (Essential):**
        * [SQLZoo](https://sqlzoo.net/) - Interactive SQL tutorial.
        * [PostgreSQL Documentation](https://www.postgresql.org/docs/) - PostgreSQL documentation.
        * **Practice:**
            * Write SQL queries to filter, sort, and aggregate data.
            * Design and create database tables.
            * Understand SQL joins and subqueries.
    * **Expand Your Horizons (Choose one or more):**
        * Java/Scala (for deep dives into Spark):
            * [Apache Spark Documentation](https://spark.apache.org/docs/latest/) - Apache Spark documentation.
            * [Effective Java](https://www.oreilly.com/library/view/effective-java-3rd/9780134685991/) - Best practices for Java programming.
        * Go (for building cloud-native tools):
            * [Go Official Documentation](https://go.dev/doc/) - Go documentation.
            * [Effective Go](https://go.dev/doc/effective_go) - Go best practices.
        * Rust (for performance critical systems):
            * [The Rust Programming Language](https://doc.rust-lang.org/book/) - Rust book.
* **Problem-Solving Goals (Phase 1):**
    * Automate repetitive file system tasks using shell scripts.
    * Implement basic data structures and algorithms (e.g., sorting, searching).
    * Develop simple API clients to retrieve and process data.
    * Collaborate on small coding projects using Git.
    * Write Python scripts to manipulate and analyze data from CSV files.
    * Construct SQL queries to extract information from relational databases.
    * Create a small project that uses all of the skills learned in phase one.
    
## Phase 2: Data Storage and Management - Mastering Data Systems

**Goal:** Gain expertise in various data storage solutions and data warehousing techniques.

* **Relational Databases:**
    * [PostgreSQL Official Site](https://www.postgresql.org/) - Official PostgreSQL website.
    * [MySQL Official Site](https://www.mysql.com/) - Official MySQL website.
    * Cloud-native equivalents (e.g., Google Cloud SQL, AWS RDS):
        * [AWS RDS Documentation](https://aws.amazon.com/rds/getting-started/) - Amazon Relational Database Service documentation.
        * [Google Cloud SQL Documentation](https://cloud.google.com/sql/docs) - Google Cloud SQL documentation.
    * **Practice:**
        * Design database schemas based on real-world scenarios.
        * Implement normalization techniques (1NF, 2NF, 3NF).
        * Optimize SQL queries for performance.
        * Setup and manage a cloud based relational database.
* **NoSQL Databases:**
    * Document databases (MongoDB, Couchbase):
        * [MongoDB Documentation](https://www.mongodb.com/docs/) - MongoDB official documentation.
        * [Couchbase Documentation](https://docs.couchbase.com/) - Couchbase official documentation.
    * Key-value stores (Redis, Memcached):
        * [Redis Documentation](https://redis.io/docs/) - Redis official documentation.
    * Wide-column stores (Cassandra):
        * [Cassandra Documentation](https://cassandra.apache.org/doc/latest/) - Apache Cassandra official documentation.
    * Graph databases (Neo4j):
        * [Neo4j Documentation](https://neo4j.com/docs/) - Neo4j official documentation.
    * **Practice:**
        * Choose the appropriate NoSQL database type for specific data models and use cases.
        * Implement CRUD operations in each type of NoSQL database.
        * Understand eventual consistency and other NoSQL concepts.
* **Data Warehousing and Data Lakes:**
    * Cloud data warehousing platforms (Snowflake, BigQuery, Amazon Redshift):
        * [Snowflake Documentation](https://docs.snowflake.com/en/) - Snowflake official documentation.
        * [BigQuery Documentation](https://cloud.google.com/bigquery/docs) - Google BigQuery official documentation.
        * [Amazon Redshift Documentation](https://docs.aws.amazon.com/redshift/index.html) - Amazon Redshift official documentation.
    * Data lake architectures using object storage (AWS S3, Google Cloud Storage, Azure Blob Storage):
        * [AWS S3 Documentation](https://docs.aws.amazon.com/s3/index.html) - Amazon S3 official documentation.
        * [Google Cloud Storage Documentation](https://cloud.google.com/storage/docs) - Google Cloud Storage official documentation.
        * [Azure Blob Storage Documentation](https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blobs-introduction) - Azure Blob Storage documentation.
    * Data Lakehouse technologies (Delta Lake, Apache Iceberg, Apache Hudi):
        * [Delta Lake Documentation](https://delta.io/) - Delta Lake official documentation.
        * [Apache Iceberg Documentation](https://iceberg.apache.org/) - Apache Iceberg official documentation.
        * [Apache Hudi Documentation](https://hudi.apache.org/) - Apache Hudi official documentation.
    * Metadata Management:
        * [Apache Atlas](https://atlas.apache.org/) - Apache Atlas official website.
        * [AWS Glue](https://aws.amazon.com/glue/) - AWS Glue official website.
    * **Practice:**
        * Design data warehouse schemas (star schema, snowflake schema).
        * Build ETL/ELT pipelines using SQL and scripting languages.
        * Implement data lake storage strategies.
        * Utilize data lakehouse technologies to enable ACID transactions on data lakes.
        * Setup a data catalog.
* **Problem-Solving Goals (Phase 2):**
    * Design and implement relational database schemas for specific applications.
    * Choose and implement the appropriate NoSQL database for various data storage needs.
    * Build data pipelines to load data into a cloud data warehouse.
    * Organize and query large datasets stored in a data lake.
    * Implement and utilize a data catalog for a given dataset.
    * Create a project that ingests data from multiple sources into a data warehouse or datalake.

## Phase 3: Data Processing and Orchestration - Building Data Pipelines

**Goal:** Develop skills in building and managing scalable data pipelines in cloud environments.

* **Cloud-Native Data Processing:**
    * Serverless computing (AWS Lambda, Google Cloud Functions, Azure Functions):
        * [AWS Lambda Documentation](https://docs.aws.amazon.com/lambda/index.html) - AWS Lambda official documentation.
        * [Google Cloud Functions Documentation](https://cloud.google.com/functions/docs) - Google Cloud Functions official documentation.
        * [Azure Functions Documentation](https://learn.microsoft.com/en-us/azure/azure-functions/) - Azure Functions official documentation.
    * Containerization (Docker, Kubernetes) and cloud-based spark solutions (Databricks, EMR, Cloud Dataproc):
        * [Docker Documentation](https://docs.docker.com/) - Docker official documentation.
        * [Kubernetes Documentation](https://kubernetes.io/docs/home/) - Kubernetes official documentation.
        * [Databricks Documentation](https://docs.databricks.com/) - Databricks official documentation.
        * [AWS EMR Documentation](https://docs.aws.amazon.com/emr/index.html) - AWS Elastic MapReduce official documentation.
        * [Google Cloud Dataproc Documentation](https://cloud.google.com/dataproc/docs) - Google Cloud Dataproc official documentation.
    * **Practice:**
        * Develop serverless functions for data transformation and processing.
        * Containerize data processing applications using Docker.
        * Deploy and manage applications on Kubernetes clusters.
        * Utilize cloud-based Spark solutions for large-scale data processing.
* **Data Processing Frameworks:**
    * [Apache Spark Documentation](https://spark.apache.org/docs/latest/) - Apache Spark official documentation.
    * [Apache Flink Documentation](https://flink.apache.org/docs/stable/) - Apache Flink official documentation.
    * [Dask Documentation](https://docs.dask.org/en/stable/) - Dask official documentation.
    * **Practice:**
        * Implement batch and stream processing pipelines using Spark.
        * Develop real-time data processing applications using Flink.
        * Use Dask for parallel data analysis in Python.
* **Message Queues and Workflow Orchestration:**
    * [Apache Kafka Documentation](https://kafka.apache.org/documentation/) - Apache Kafka official documentation.
    * [RabbitMQ Documentation](https://www.rabbitmq.com/documentation.html) - RabbitMQ official documentation.
    * Cloud-native messaging:
        * [Google Cloud Pub/Sub Documentation](https://cloud.google.com/pubsub/docs) - Google Cloud Pub/Sub official documentation.
        * [AWS Kinesis Documentation](https://docs.aws.amazon.com/kinesis/index.html) - AWS Kinesis official documentation.
    * [Apache Airflow Documentation](https://airflow.apache.org/docs/) - Apache Airflow official documentation.
    * [Prefect Documentation](https://docs.prefect.io/) - Prefect official documentation.
    * [Dagster Documentation](https://docs.dagster.io/) - Dagster official documentation.
    * Cloud native orchestration:
        * [AWS Step Functions Documentation](https://docs.aws.amazon.com/step-functions/index.html) - AWS Step Functions official documentation.
        * [Google Cloud Workflows Documentation](https://cloud.google.com/workflows/docs) - Google Cloud Workflows official documentation.
        * [Azure Logic Apps Documentation](https://learn.microsoft.com/en-us/azure/logic-apps/logic-apps-overview) - Azure Logic Apps official documentation.
    * **Practice:**
        * Implement message queues for asynchronous data processing.
        * Design and build data pipelines using workflow orchestration tools.
        * Monitor and manage data pipeline execution.
* **Problem-Solving Goals (Phase 3):**
    * Build a real-time data pipeline for streaming data from a message queue to a data lake.
    * Implement a batch processing pipeline using Spark to transform and load data into a data warehouse.
    * Orchestrate complex data workflows using Airflow or a similar tool.
    * Deploy and manage data processing applications on a Kubernetes cluster.
    * Implement a serverless data transformation pipeline.
    * Create a project that implements a data pipeline from start to finish, from data ingestion to consumption.

## Phase 4: Cloud and Infrastructure - Deploying and Managing Data Systems

**Goal:** Become proficient in cloud platforms and infrastructure management.

* **Cloud Platform Mastery:**
    * AWS, Google Cloud, Azure:
        * [AWS Certified Data Engineer – Associate](https://aws.amazon.com/certification/certified-data-analytics-specialty/) - AWS certification for data engineering.
        * [Google Cloud Certified Professional Data Engineer](https://cloud.google.com/certification/data-engineer) - Google Cloud certification for data engineering.
        * [Microsoft Certified: Azure Data Engineer Associate](https://learn.microsoft.com/en-us/certifications/azure-data-engineer/) - Azure certification for data engineering.
    * Infrastructure as code (Terraform, CloudFormation, Azure Resource Manager):
        * [Terraform Documentation](https://www.terraform.io/docs) - Terraform official documentation.
        * [AWS CloudFormation Documentation](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/index.html) - AWS CloudFormation documentation.
        * [Azure Resource Manager Documentation](https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/overview) - Azure Resource Manager documentation.
    * Cloud networking (VPCs, subnets, security groups):
        * [AWS VPC Documentation](https://docs.aws.amazon.com/vpc/index.html) - AWS Virtual Private Cloud documentation.
        * [Google Cloud VPC Documentation](https://cloud.google.com/vpc/docs) - Google Cloud Virtual Private Cloud documentation.
        * [Azure Virtual Network Documentation](https://learn.microsoft.com/en-us/azure/virtual-network/virtual-networks-overview) - Azure Virtual Network documentation.
    * **Practice:**
        * Deploy and manage cloud resources using Infrastructure as Code.
        * Design and implement secure cloud networking architectures.
        * Monitor and manage cloud infrastructure using cloud-native tools.
        * Create and maintain cloud based data engineering environments.
* **Container Orchestration:**
    * Kubernetes (EKS, GKE, AKS):
        * [Kubernetes Documentation](https://kubernetes.io/docs/home/) - Kubernetes official documentation.
        * [Amazon EKS Documentation](https://docs.aws.amazon.com/eks/index.html) - Amazon Elastic Kubernetes Service documentation.
        * [Google GKE Documentation](https://cloud.google.com/kubernetes-engine/docs) - Google Kubernetes Engine documentation.
        * [Azure AKS Documentation](https://learn.microsoft.com/en-us/azure/aks/intro-kubernetes) - Azure Kubernetes Service documentation.
    * **Practice:**
        * Deploy and manage containerized data applications on Kubernetes clusters.
        * Implement Kubernetes services and deployments.
        * Use Kubernetes for scaling and managing data processing workloads.
* **CI/CD Implementation:**
    * GitOps, automated testing, and deployment:
        * [GitOps Documentation](https://www.weave.works/technologies/gitops/) - GitOps principles and practices.
        * [Jenkins Documentation](https://www.jenkins.io/doc/) - Jenkins official documentation.
        * [GitHub Actions Documentation](https://docs.github.com/en/actions) - GitHub Actions documentation.
        * [Azure DevOps Documentation](https://learn.microsoft.com/en-us/azure/devops/) - Azure DevOps Documentation.
    * **Practice:**
        * Implement CI/CD pipelines for data engineering applications.
        * Automate testing and deployment of data pipelines.
        * Utilize GitOps for infrastructure and application deployment.
* **Problem-Solving Goals (Phase 4):**
    * Deploy a data warehouse on a cloud platform using Infrastructure as Code.
    * Implement a Kubernetes cluster for running data processing applications.
    * Build a CI/CD pipeline for deploying data pipelines.
    * Design and implement a secure cloud networking architecture for a data platform.
    * Automate the deployment of data engineering environments.
    * Create a project that provisions and manages a complete cloud based data engineering environment.

## Phase 5: Data Governance, Security, and Emerging Trends - Ensuring Data Quality and Staying Ahead

**Goal:** Develop expertise in data governance, security, and stay abreast of emerging technologies.

* **Data Governance and Security:**
    * Data cataloging, lineage, and quality management:
        * [Apache Atlas](https://atlas.apache.org/) - Apache Atlas official website.
        * [AWS Glue Data Catalog](https://docs.aws.amazon.com/glue/latest/dg/datacatalog-overview.html) - AWS Glue Data Catalog documentation.
        * [Google Cloud Data Catalog](https://cloud.google.com/data-catalog/docs) - Google Cloud Data Catalog documentation.
    * Data privacy and compliance (GDPR, CCPA):
        * [GDPR Official Website](https://gdpr-info.eu/) - General Data Protection Regulation official website.
        * [CCPA Official Website](https://oag.ca.gov/privacy/ccpa) - California Consumer Privacy Act official website.
    * Data access control and security measures:
        * [AWS IAM Documentation](https://docs.aws.amazon.com/IAM/latest/UserGuide/index.html) - AWS Identity and Access Management documentation.
        * [Google Cloud IAM Documentation](https://cloud.google.com/iam/docs) - Google Cloud Identity and Access Management documentation.
        * [Azure AD Documentation](https://learn.microsoft.com/en-us/azure/active-directory/) - Azure Active Directory documentation.
    * **Practice:**
        * Implement data cataloging and lineage tracking for data assets.
        * Design and implement data quality checks and monitoring.
        * Ensure data privacy and compliance with relevant regulations.
        * Implement data access control policies and security measures.
* **Emerging Trends:**
    * AI/ML integration (MLOps, feature engineering, vector databases):
        * [MLOps Guide](https://martinfowler.com/articles/mlops.html) - Martin Fowler's MLOps article.
        * [Feature Engineering Techniques](https://www.featuretools.com/blog/feature-engineering-techniques/) - Feature engineering techniques blog.
        * [Vector Databases](https://milvus.io/docs) - Milvus Vector database documentation.
    * Real-time data processing (CEP, streaming analytics):
        * [Apache Flink CEP](https://flink.apache.org/docs/stable/docs/dev/libs/cep/) - Apache Flink Complex Event Processing documentation.
        * [Streaming Analytics](https://www.ibm.com/cloud/streaming-analytics) - IBM Streaming Analytics overview.
    * Data mesh and data fabric architectures:
        * [Data Mesh Principles](https://martinfowler.com/articles/data-mesh-principles.html) - Martin Fowler's Data Mesh Principles article.
        * [Data Fabric Overview](https://www.oracle.com/data-management/data-fabric/) - Oracle Data Fabric overview.
    * Low-code/no-code data engineering tools:
        * [Low-Code/No-Code Platforms](https://www.gartner.com/en/topics/low-code-no-code) - Gartner's Low-Code/No-Code platforms overview.
    * **Practice:**
        * Integrate ML models into data pipelines using MLOps practices.
        * Develop real-time data analytics applications.
        * Understand and apply data mesh and data fabric principles.
        * Evaluate and utilize low-code/no-code data engineering tools.
* **Problem-Solving Goals (Phase 5):**
    * Implement a data governance framework for a data platform.
    * Design and implement a data security plan for cloud-based data assets.
    * Build an MLOps pipeline for deploying and managing machine learning models.
    * Develop a real-time data analytics dashboard.
    * Design a data mesh architecture for a distributed data environment.
    * Evaluate and recommend a low-code/no-code data engineering tool for a specific use case.
    * Create a project that implements end to end data governance, security, and emerging technology concepts.
