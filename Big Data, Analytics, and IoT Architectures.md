# Big Data, Analytics, and IoT Architectures

## Reference Architectures
+ Extended Relational
+ Non-Relational
+ Hybrid

## Normalization
- First Normal Form (1NF)
- Third Normal Form (3NF)

## Goals and Deliverables
+ Business goals
    * Increase revenue
    * Increase profit
    * Decrease costs
    * Reduce risk
    * Increase operational efficiency
    * Reduce waste
    * Increase customer acquisition, retention, and growth
    * Improve customer service
    * Enhance business development
    * Improve business governance
    * Drive data and evidence-driven decisions
    * Improve business agility
+ Real time intelligence and analytics
+ Data and insights discovery and exploration
+ Decision management and inform decisions
+ Business reporting and analysis
+ Security intelligence (security, fraud, and risk analysis)
+ Self-service (ad-hoc)
+ Discover relevant trends and patterns
+ Drive new business models
+ Stream computing
    * Event and data streams
+ Data and text analytics
    * Descriptive analytics - What happened and why?
    * Predictive analytics - What is the probability of something happening?
    * Prescriptive analytics - What specific recommendations will drive business decisions and help achieve business goals (i.e., what to do if 'X' happens)
    * Query and reporting
    * OLAP Cubes
    * Advanced analytics
    * MapReduce
    * Search engines

## Architectural Goals, Principles, and Considerations
- Consistency
- Batch vs. real-time streaming data processing
- Embedded models or interfaces
- API or RPC or REST
- Deployed trained models (offline learning) vs. [online learning](https://en.wikipedia.org/wiki/Online_machine_learning)
+ Latency (near real time)
+ Reliability and fault tolerance
+ Availability
+ Scalability/Volume handling
+ Performance/speed
+ Throughput
+ Extensibility
+ Security
+ Cost/financial
+ Data quality
+ Skills availability
+ Backup and recovery
+ Locations and placement
+ Privacy and sensitive data
+ Disaster recovery

## Enterprise Big Data Components
- Governance
    + Govern data quality
- Operations, Infrastructure, and DevOps
- Monitoring
- Security and privacy
    + Authentication
    + Authorization
    + Accounting
    + Data protection
    + Compliance
- Data Integration
    + Messaging and message queues
    + ETL
    * API/ODBC
    * Replication
    * Bulk movement
    * Virtualization
- Data Processing
    + Event ingestion
    + Batch and stream processing/computing (velocity)
        * Massive scaling and processing of multiple concurrent input streams
    + Parallel computing platform
        * Clusters or grids
        * Massively parallel processing (MPP)
        * High performance computing (HPC)
- Data Access
    + Querying
    + Real-time analytics
    + BI analytics
    + MapReduce analytics
- Data Modeling and Structure
    + Star schema
    + Snowflake schema
- Data Storage and Management
    + Data lake
    * Data warehouse (volume)
        - Centralized, integrated data store
        - Powers BI analytics, reporting, and drives actionable insights
        - Responsible for integrating data
        - Structured, prepared, and stored data optimized for
            + Analytical applications and decision support
            + Querying and reporting
            + Data mining
        - In-database analytics
        - Operational analytics
        - MPP engine
        - 'Deep analytical appliance' - IBM
    * Operational data store (ODS)
    * Database Systems and DBMS
        - Relational (RDBMS)
        - NoSQL
            + Real-time analytics and insights
        - NewSQL
        - Hybrid
    * Data marts
        - Data warehouse extracted data subsets oriented to speciﬁc business lines, departments or analytical applications
    * Distributed file systems (e.g., HDFS) and Hadoop (volume and variety)
        - Real-time and MapReduce analytics and insights
        - Deep analysis of petabytes of structured and unstructured data
    * In-memory
- Data lifecycle management
    + Rule-based Data and Policy Tracking
    + Data compression
    + Data archiving
- Deployment Choice
    + On-premise, aka traditional IT
    + In-cloud
        * Public cloud
        * Private cloud
    + Appliance
    + Managed services
- Presentation, Analytics, and Applications (visibility)
    + Browser/web
    + Mobile
    + Desktop
    + Dashboards
    + Reports
    + Notifications and messaging
    + Scorecards
    + Charts and graphics
    + Visualization and discovery

## Enterprise Big Data Components
- http://hortonworks.com/wp-content/uploads/2014/03/11.png

## Big Data Processing Key Functional Capabilities - IBM
- Data ingestion
    + Optimize the process of loading data in the data store to support time-sensitive analytic goals.
- Search and survey
    + Secure federated navigation and discovery across all enterprise content.
- Data transformation
    + Convert data values from source system and format to destination system and format.
- Analytics
    + Discover and communicate meaningful patterns in data.
- Actionable decisions
    + Make repeatable, real-time decisions about organizational policies and business rules.
- Discover and explore
    + Discover, navigate, and visualize vast amounts of structured and unstructured information across many enterprise systems and data repositories.
- Reporting, dashboards, and visualizations
    + Provide reports, analysis, dashboards, and scorecards to help support the way that people think and work.
- Provisioning
    + Deploy and orchestrate on-premises and off-premises components of a big data ecosystem.
- Monitoring and service management
    + Conduct end-to-end monitoring of services in the data center and the underlying infrastructure.
- Security and trust
    + Detect, prevent, and otherwise address system breaches in the big data ecosystem.
- Collaborate and share

## Big data and analytics architecture on cloud - IBM
- Analytics-as-a-service
    + Consumes both data at rest and in motion
    + Applies analytical algorithms
    + Provides
        * Dashboards
        * Reports
        * Visualizations
        * Insights
        * Predictive modeling
    + Abstracts away all complexity of data collection, storage, and cleansing
- Data-as-a-service
    + Data-at-rest-service
    + Data-in-motion-service
- NoSQL tools (Hive, Pig, BigSQL, ...)
- EMR clusters (Hadoop, Cassandra, MongoDB, ...) and Traditional DW
- Big data file system (HDFS, CFS, GPFS, S3, ...)
- Infrastructure & Appliances (Baremetal or IaaS) and object storage

## Data Storage Functions
- Staging
    + Temporary storage
    + Used for cleaning, integration and transformation routines
- Data management
    + Long-time managed storage
    + Clean and integrated data
- Sandboxing
    + Temporary data stores
    + Used by people, groups, and departments
    + Experimentation with data, processing, and analysis techniques
- Application optimized storage
    + Example usage = data mart
- Archive and raw data archive
    + Raw, processed, and transformed data

## [The 7 V's of Big Data](https://www.impactradius.com/blog/7-vs-big-data/)
+ Volume - Scale of data
+ Variety - Different forms of data
+ Velocity - Analysis of streaming data
+ Veracity - Overall quality and correctness of the data
    * Garbage in, garbage out
    * Assess the truthfulness and accuracy of the data as well as identify missing or incomplete information
- Visibility/Visualization
- Value
- Variability

## Data types and sources
+ Structured
+ Unstructured
+ Semi-structured
+ Data storage (databases)
+ Sensors
+ RFID tags
+ Instore WiFi logs
+ Machine Logs
    * Application
    * Events
    * Server
    * CDRs
    * Clickstream
+ Text, including documents, emails, scanned documents, records, ...
+ Social networks
+ Public web
+ Geo-location
+ Machine generated
+ Clickstream
+ Software
+ Media
    * Images
    * Video
    * Audio
+ Business applications
    * OLTP - Online transaction processing
    * ERP - Enterprise resource planning
    * CRM - Customer relationship management
    * SCM - Supply chain management
    * HR
    * Product/Project management
+ Online chat
+ Merchant listings
+ DMP - Data management platform (advertising/marketing)
+ CDR - Call detail records
+ Surveys, questionnaires, binary questions, and sentiment
+ Billing data
+ Product catalog
+ Network data
+ Subscriber data
+ Staffing
+ Inventory
+ POS and transactional
+ eCommerce transactions
+ Biometrics
+ Mobile devices
+ Weather data
+ Traffic pattern data

## Database Considerations and Tradeoffs
- ACID
    + Atomicity
    + Consistency
    + Isolation
    + Durability
- BASE
    + Basically Available
    + Soft state
    + Eventual consistency
- CAP (Brewers theorem) and PACELC
    + Consistency
    + Availability
    + Partition tolerance
- Consistency vs eventually consistency
- Speed and performance
- Locks
    + Lock contention
    + Long term blocking
    + Database deadlocks
    + System deadlocks
- Schema on write vs schema on read
- Isolation levels
- Concurrency control
- Different read types (e.g., dirty, non-repeatable, phantom, ...)

## Hadoop Benefits
- Built on the _shared nothing_ principle
    + Each node is independent and self-sufficient
- Ability to store any and all data types relatively cheap
- Ability to process any and all data quickly and relatively cheap
- Vast community, ecosystem, and pluggable architecture
- Scalable, flexible, computational model

## Data Lake vs Data Warehouse
- Data Warehouse (EDW)
    + [Definition](https://en.wikipedia.org/wiki/Data_warehouse) - A system used for reporting and data analysis, and is considered a core component of business intelligence
    + Characteristics
        * Data
            - Structured
            - Processed
        * Schema-on-write processing
        * Relatively expensive for large volumes
        * Fixed configuration and less flexible
        * Better suited for business intelligence and business professionals
    + Considerations
    + Technologies
        * AWS Redshift
- Data Lake
    + [Definition](http://www.kdnuggets.com/2015/09/data-lake-vs-data-warehouse-key-differences.html) - A data lake is a storage repository that holds a vast amount of raw data in its native format, including structured, semi-structured, and unstructured data. The data structure and requirements are not defined until the data is needed.
    + Characteristics
        * Data
            - Structured, semi-structured, unstructured
            - Raw
        * A data lake delivers maximum scale and insight with the lowest possible friction and cost
        * Increased efficiency
        * Reduced storage costs
        * Data processing workload optimization, including data integration and transformation
        * Schema-on-read processing and associated flexibility and new opportunities
        * Multi-use and multi-workload data processing on same data from batch to real-time across business units
        * Eliminate need for ETL and associated costs
        * Keep 100% of source data and historical data for ongoing exploration (both raw and processed)   
        * Easy and dynamic configuration and reconfiguration
        * Better suited for data scientists
    + Considerations
    + Technologies
        * Hadoop
        * Apache YARN

## Data Processing and access methods/patterns compared
- Batch
    + Process batches of data on regular time intervals, e.g., hourly, daily, overnight, etc.
- Real-time
    + Monitor and react in real time
- Streaming
- Interactive
    + Data analysts reviewing data
- Online
- Search
- In-memory

## Offline vs Online Learning

Coming soon...

## Architecture Guides and Examples

**AWS**
- [Solution Development Guides](https://aws.amazon.com/solutions)
    + Reference Architectures
        * [Web Application Hosting](http://media.amazonwebservices.com/architecturecenter/AWS_ac_ra_web_01.pdf)
        * [Batch Processing](http://media.amazonwebservices.com/architecturecenter/AWS_ac_ra_batch_03.pdf)
        * [Large Scale Computing and Large Data Sets](http://media.amazonwebservices.com/architecturecenter/AWS_ac_ra_largescale_05.pdf)
        * [Time Series Processing](http://media.amazonwebservices.com/architecturecenter/AWS_ac_ra_timeseriesprocessing_16.pdf)
    + By Application
        * [Websites](https://aws.amazon.com/websites/)
        * [Backup and Recovery](https://aws.amazon.com/backup-recovery/)
        * [Archiving](https://aws.amazon.com/archive/)
        * [DevOps](https://aws.amazon.com/devops/)
        * [Big Data](https://aws.amazon.com/big-data/)
        * [High Performance Computing](https://aws.amazon.com/hpc/)
        * [Internet of Things](https://aws.amazon.com/iot/)
        * [Business Applications](https://aws.amazon.com/business-applications/)
        * [Content Delivery](https://aws.amazon.com/content-delivery/)
        * [Mobile Services](https://aws.amazon.com/mobile/)
        * [Scientific Computing](https://aws.amazon.com/government-education/scientific-computing1/)
        * [E-commerce](https://aws.amazon.com/ecommerce-applications/)
    + By Industry Sector
        * [Financial Services](https://aws.amazon.com/financial-services/)
        * [Digital Marketing](https://aws.amazon.com/digital-marketing/)
        * [Media and Entertainment](https://aws.amazon.com/digital-media/)
        * [Gaming](https://aws.amazon.com/game-hosting/)
        * [Enterprise IT](https://aws.amazon.com/enterprise/)
        * [Healthcare & Life Sciences](https://aws.amazon.com/health/)
        * [Government](https://aws.amazon.com/government-education/government/)
        * [Nonprofit](https://aws.amazon.com/government-education/nonprofits/)
        * [Education](https://aws.amazon.com/education/)
- [Partner Solutions](https://aws.amazon.com/solutions/partners/)
    + [Big Data](https://aws.amazon.com/big-data/partner-solutions/)
    + [Storage](https://aws.amazon.com/backup-recovery/partner-solutions/)
    + [DevOps](https://aws.amazon.com/devops/partner-solutions/)
- [Case Studies](https://aws.amazon.com/solutions/case-studies/)
    + [Analytics](https://aws.amazon.com/solutions/case-studies/analytics/)
    + [Big Data](https://aws.amazon.com/solutions/case-studies/big-data/)
    + [Enterprise](https://aws.amazon.com/solutions/case-studies/enterprise-it/)
    + [Startups](https://aws.amazon.com/solutions/case-studies/start-ups/)
    + [Web Apps](https://aws.amazon.com/solutions/case-studies/web-mobile-social/)

**Google Cloud Platform**
- [Big data reference architecture diagram](https://cloud.google.com/images/products/big-data/big-data-diagram.png)
- [Solution Development Guides](https://cloud.google.com/solutions/)
    + [Media](https://cloud.google.com/solutions/media/)
    + [Mobile Applications](https://cloud.google.com/solutions/mobile/#development_guides)
    + [Big Data](https://cloud.google.com/solutions/big-data/#development_guides)
    + [Financial Services](https://cloud.google.com/solutions/financial-services/#development_guides)
    + [Gaming](https://cloud.google.com/solutions/gaming/#development_guides)
    + [Retail & Commerce](https://cloud.google.com/solutions/commerce/#development_guides)
    + [Internet of Things](https://cloud.google.com/solutions/iot/#development_guides)
    + [Websites and Web Apps](https://cloud.google.com/solutions/websites/#development_guides)
    + [Development & Test](https://cloud.google.com/solutions/dev-test/#development_guides)

**IoT**

Coming soon...

**General**
- [Lambda Architecture](http://lambda-architecture.net/)
- [AWS Architecture Center](https://aws.amazon.com/architecture/?nc1=f_cc)
- [AWS Big Data Partner Solutions](https://aws.amazon.com/big-data/partner-solutions/)
- [GCP Architecture](https://cloud.google.com/docs/tutorials#architecture)
- [Introduction to big data classification and architecture](http://www.ibm.com/developerworks/library/bd-archpatterns1/)
- [An Enterprise Architect’s Guide to Big Data](http://www.oracle.com/technetwork/topics/entarch/articles/oea-big-data-guide-1522052.pdf)
- [BIG DATA REFERENCE ARCHITECTURE](https://thinkbiganalytics.com/leading_big_data_technologies/big-data-reference-architecture/)
- [Getting Started with Big Data Architecture](http://blog.cloudera.com/blog/2014/09/getting-started-with-big-data-architecture/)
- [BIG DATA: Architectures and Technologies](https://www.sei.cmu.edu/go/big-data/)
- [Big Data Architecture](http://bigdata.teradata.com/US/Big-Ideas/Big-Data-Architecture/)
- [Big Data Analytics Architecture](http://www.thebigdatainsightgroup.com/site/sites/default/files/Teradata's%20-%20Big%20Data%20Architecture%20-%20Putting%20all%20your%20eggs%20in%20one%20basket.pdf)
- [What is Streaming Data?](https://aws.amazon.com/streaming-data/)

**Solution Patterns - IBM**
- Landing Zone Warehouse
- Virtual Tables
- Discovery Tables
- Streams Dynamic Warehouse
- Streams Detail with Update
- Direct Augmentation
- Warehouse Augmentation
- Streams Augmentation
- Dynamic Search Cube

**Component Patterns - IBM**
- Source Data
- Source Event
- Landing Area Zone ETL
    + Extract
    + Normalize
    + Clean
- Landing Area Zone Search and Survey
    + Find
    + Filter
    + Extract
- Landing Area Zone Stream Filter
- Landing Area Zone Stream Augmentation
- Landing Area Zone Warehouse Augmentation
- Landing Area Zone Index
- Exploration Mart
- Analytics Mart
- Report Mart
- Virtual Report Mart
- Virtual Search Mart
- Predictive Analytics

**Big Data Exploration Example Architecture - IBM**
- Applications layer
    + Consists of
        * Visualization
        * Discovery
        * Analysis
        * Reporting
        * Statistics
        * Text and entity analytics
    + Access
        * SQL
        * MDX
        * Search
        * REST
- Discovery and assembly layer
    + Consists of
        * Virtual search mart
            - Faceted search
        * Analytics mart
            - Report mart
            - Discovery table
            - Search and survey
        * Report mart
            - ETL
            - Analytics
            - Streams
    + Access
        * NoSQL
        * SQL
        * Search
        * REST
- Landing layer
    + Consists of
        * Shared warehouse and ETL
            - Extract
            - Provision
    + Access
        * Search
        * REST
        * SQL
        * Files
- Source layer
    + Sensors and telemetry
    + Internet
    + Social media
    + Public data
    + Enterprise data
    + ...
