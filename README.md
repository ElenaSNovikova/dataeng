

# Data Engineering:
## Repository for the Data Engineering Course (LTAT.02.007)

![logout](https://upload.wikimedia.org/wikipedia/en/3/39/Tartu_%C3%9Clikool_logo.svg)

![logodsg](./attachments/logo_dsg_vettoriale.png)

## Graph View

![inline](./attachments/latest.png)

## Lecturer: [Riccardo Tommasini, PhD](https://riccardotommasini.com)

### Teaching Assistants: 
- [Fabiano Spiga](mailto:),  
- [Mohamed Ragab](https://bigdata.cs.ut.ee/mohamed-ragab), 
- [Hassan Eldeeb](mailto:hassan.eldeeb@ut.ee)

### [Home Page](https://courses.cs.ut.ee/2020/dataeng)

### [Forum](https://piazza.com/ut.ee/fall2020/ltat02007/home) 

### [Moodle](https://moodle.ut.ee/course/view.php?id=10457)

### [Twitter](https://twitter.com/hashtag/DataEngUT?src=hashtag_click)

### Acknowledgments

Special Thanks to Emanuele Della Valle and Marco Brambilla from Politecnico di Milano to letting me "steal" some of their great slides.

# Lectures

| Date  | Title              | Material | Mandatory Reads | Extras |
|-------|--------------------|----------|-----------------|--------|
| 01/09 | Course Intro       | [Slides](./Data%20Engineer.md) - [pdf](./pdfs/Data%20Engineer.pdf) slide 45-109) | ||
| 03/09 | Data Modeling      | [Slides](Data%20Modeling.md) - [pdf](./pdfs/Data%20Modeling.pdf) slide 1-44 | Chp 4 p111-127, Chp 5 p151-156, Chp 6 p199-205 of [3]
| 10/09 |  DM for Relational Databases |   [Slides](Data%20Modeling.md) - [pdf](./pdfs/Data%20Modeling.pdf) slide 45-109 | Chp 2, 6, and 7 (Normal Forms) of [1] | [Relational Model](https://course.ccs.neu.edu/cs3200sp18s3/ssl/readings/codd.pdf) | 
|10/09  |  DM for Data Warehouse         |  [Slides](Data%20Modeling.md)  - [pdf](./pdfs/Data%20Modeling.pdf)slide 109-118|  [pdf](http://www.kimballgroup.com/wp-content/uploads/2013/08/2013.09-Kimball-Dimensional-Modeling-Techniques11.pdf) [video](http://slideshot.epfl.ch/play/suri_stonebraker)|  Chp 2 of [2] | 
| 17/09 |  DM for Big Data   | [Slides](Data%20Modeling%20for%20Big%20Data.md) - [pdf](./pdfs/Data%20Modeling%20Big%20Data.pdf)| Chp 2 of [3], [video](https://www.youtube.com/watch?v=LDW0QWie21s)|[paper](https://www.ics.uci.edu/~cs223/papers/cidr07p15.pdf)| 
| 17/09 |  Key Value Stores |[Slides 1](https://github.com/DataSystemsGroupUT/dataeng/blob/dataeng/Key-Value%20Store.md),[Slides 2](https://github.com/DataSystemsGroupUT/dataeng/blob/dataeng/Redis.md)[pdf](https://github.com/DataSystemsGroupUT/dataeng/blob/dataeng/pdfs/Key-Value%20Stores%20-%20Redis.pdf)||[nosql](https://www.christof-strauch.de/nosqldbs.pdf)|
|24/10| Column Oriented Databases |[Slides 1](https://github.com/DataSystemsGroupUT/dataeng/blob/dataeng/Column%20Oriented%20Database.md) [Slides 2](https://github.com/DataSystemsGroupUT/dataeng/blob/dataeng/Cassandra.md) [pdf](https://github.com/DataSystemsGroupUT/dataeng/blob/dataeng/pdfs/Column%20Stores%20-%20Cassandra.pdf)||[nosql](https://www.christof-strauch.de/nosqldbs.pdf)|
|24/10| Document Databases  |[Slides 1](https://github.com/DataSystemsGroupUT/dataeng/blob/dataeng/Document%20Databases.md) [Slides 2](https://github.com/DataSystemsGroupUT/dataeng/blob/dataeng/MongoDB.md) [pdf](https://github.com/DataSystemsGroupUT/dataeng/blob/dataeng/pdfs/Document%20Stores%20-%20MongoDB.pdf)||[nosql](https://www.christof-strauch.de/nosqldbs.pdf)|
|01/10| Graph Databases |[Slides 1](https://github.com/DataSystemsGroupUT/dataeng/blob/dataeng/Graph%20Theory.md) [Slides 2](https://github.com/DataSystemsGroupUT/dataeng/blob/dataeng/Graph%20Databases.md) [pdf1](https://github.com/DataSystemsGroupUT/dataeng/blob/dataeng/pdfs/Graph%20Theory.pdf) [pdf2](https://github.com/DataSystemsGroupUT/dataeng/blob/dataeng/pdfs/Graph%20Databases.pdf)|Chp 3 and 5 of [5]|[book](https://neo4j.com/graph-databases-book/)|
|| Data Ingestion ||Chp 1 of [3]||
|| Data Engineering Pipelines ||Chp 1 of [3]||
|| Keynote TBA||||
|| Streaming Data ||Chp 11 of [3]||
|| Data Wrangling ||||

# Practices (Videos Will be Available after Group 2 issue)

| Date     | Title              | Material | Reads | Videos | Assignment | Notes |
|----------|-------------|----------|-------|-------|-------|----|
| 07-8/09  | Docker |  [Slides](./docker/README.md) - [Lab Branch](https://github.com/DataSystemsGroupUT/dataeng/tree/docker) | |[Video GP1](https://panopto.ut.ee/Panopto/Pages/Viewer.aspx?id=31e77abe-b51e-4a39-8c33-ac30009b7ba6) [Video GP2](https://panopto.ut.ee/Panopto/Pages/Viewer.aspx?id=31e77abe-b51e-4a39-8c33-ac30009b7ba6) ||  [QA GP2 only](https://docs.google.com/document/d/134YKfqp49-rtAXa0FJO30LJonHVO-PeYLqqeo8DQY9I/) 
| 14-15 /09  |Modeling and Querying Relational Data with Postgres|[Slides](https://github.com/DataSystemsGroupUT/dataeng/blob/Homework1/PostgreSQL.pdf)|[Chp 32 of [1]§](https://www.db-book.com/db7/online-chapters-dir/32.pdf) |[Video](https://panopto.ut.ee/Panopto/Pages/Viewer.aspx?id=b3221179-fd3a-4b4e-9a67-ac38008f7fbe)|||
| 21-22 /09  |Modeling and Querying Key Value Data with Redis|[Slides](https://github.com/DataSystemsGroupUT/dataeng/blob/Homework2/REDIS.pdf)||[Video](https://panopto.ut.ee/Panopto/Pages/Viewer.aspx?id=0e659b03-7d3e-4b4c-a0f9-ac3d00f462a7)|||
|28-29/09   |Modeling and Querying Document Data with MongoDB|[Slides](https://github.com/DataSystemsGroupUT/dataeng/blob/Homework3/slides/MongoDB.pdf)||[Video](https://panopto.ut.ee/Panopto/Pages/Viewer.aspx?id=9ffba354-a2a1-4131-967e-ac4400c8f226)|||
|5-6/10        | Modeling and Querying Graph Data with Neo4J|[Slides](https://github.com/DataSystemsGroupUT/dataeng/blob/Homework4/Neo4j_lab_Slides.pptx.pdf)||[Video](https://panopto.ut.ee/Panopto/Pages/Viewer.aspx?id=1c9e44d6-d3a0-44ed-a012-ac4b00bb831b)|||
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
- [5] [Graph Databases](https://neo4j.com/graph-databases-book/)
[[slides/Slides]]
