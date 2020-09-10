# dataeng
Repository for the Data Engineering Course

[Course Homepage](https://courses.cs.ut.ee/2020/dataeng)

[Lecturers](./LECTURERS.md)

## Acknowledgments

Special Thanks to Emanuele Della Valle and Marco Brambilla from Politecnico di Milano to letting me "steal" some of their great slides.

# Lectures

| Date   | Title              | Material | Reads | Extras |
|-------|-------------|----------|-------|-------|
| 01/09  | Course Intro |[Who is the Data Engineer](./Data%20Engineer.md) - [pdf]([Data Modeling](Data%20Modeling.md) slide 45-109) | ||
| 03/09 | Data Modeling | [Data Modeling](Data%20Modeling.md) - [pdf]() slide 1-44 |
|   |  DM for Relational Databases |   [Data Modeling](Data%20Modeling.md) - [pdf]() slide 45-109 | Chp 2, 6, and 7 (Normal Forms) of [1] | [Relational Model](https://course.ccs.neu.edu/cs3200sp18s3/ssl/readings/codd.pdf) | 
|   |  DM for Data Warehouse         |  [Data Modeling](Data%20Modeling.md)  - [pdf]()slide 109-118|  [pdf](http://www.kimballgroup.com/wp-content/uploads/2013/08/2013.09-Kimball-Dimensional-Modeling-Techniques11.pdf) [video](http://slideshot.epfl.ch/play/suri_stonebraker)|  Chp 2 of [2] | 
|   |  DM for Big Data         |  |  Chp 1 of [3]|  | TODO|
|   |  Key Value Stores ||||
|   |  Document Databases  ||||
|   |  Graph Databases ||||
|| Data Engineering Pipelines ||||
|| Keynote TBA||||
|| Streaming Data ||||
|| Data Wrangling ||||


# Practices (Videos Will be Available after Group 2 issue)

| Date     | Title              | Material | Reads | Videos | Assignment | Notes |
|--------|-------------|----------|-------|-------|-------|----|
| 07-8/09  | Docker |  [Slides](./docker/README.md) - [Lab Branch](https://github.com/DataSystemsGroupUT/dataeng/tree/docker) | |[Video GP1](https://panopto.ut.ee/Panopto/Pages/Viewer.aspx?id=31e77abe-b51e-4a39-8c33-ac30009b7ba6) [Video GP2](https://panopto.ut.ee/Panopto/Pages/Viewer.aspx?id=31e77abe-b51e-4a39-8c33-ac30009b7ba6) ||  [QA GP2 only](https://docs.google.com/document/d/134YKfqp49-rtAXa0FJO30LJonHVO-PeYLqqeo8DQY9I/) 
| 14-15 /09  |Modeling and Querying Relational Data with Postgres||||||
| 21-22 /09  |Modeling and Querying Key Value Data with Redis||||||
|28-29/09   |Modeling and Querying Document Data with MongoDB||||||
|5-6/10        | Modeling and Querying Graph Data with Neo4J||||||
|| Data Ingestion with Apache Kafka||||||
|| Apache Airflow Data Pipelines||||||
|| Stream Processing with  Kafka Streams||||||
|| Stream Processing with  KSQL||||||
||Data Cleansing ||||||
||Augmentation||||||

# Extras

[Contributing](./CONTRIBUTING.md)

- [ ] Modeling and Querying RDF data: SPARQL
- [ ] Domain Driven Design: a summary
- [ ] Event Sourcing: a summary
- [ ] Data Pipelines with Luigi
- [ ] Data Pipelines with Apachi Nifi 
- [ ] Data Processing with Apache Flink

# Syllabus

- What is (Big) Data?
- The Role of Data Engineer
- Data Modeling
  	- Data Replication
	- Data Partitioning
	- Transactions
- Relational Data
- NoSQL
  - Document
  - Graph
- Data Warehousing
  - Star and Snowflake schemas
- Data Vault 
- (Big) Data Pipelines
	- Big Data Systems Architectures
	- ETL and Data Pipelines
	  - Best Practices and Anti-Patterns
	- Batch vs Streaming Processing
- Data Cleansing
- Data Augumentation

# Books

- [1] Database System Concepts 7th Edition Avi Silberschatz Henry F. Korth S. Sudarshan McGraw-Hill ISBN 9780078022159
  - [Table of contents](https://www.db-book.com/db7/toc-dir/toc.pdf)
  - [slides](https://www.db-book.com/db7/slides-dir/index.html)
- [2] The Data Warehouse Toolkit - The Definitive Guide to Dimensional Modeling Third Edition  Ralph Kimball Margy Ross
- [3] [Designing Data-Intensive Applications - Martin Kleppmann ](https://dataintensive.net/)
- [4] [Designing Event-Driven Systems](https://www.oreilly.com/library/view/designing-event-driven-systems/9781492038252/)