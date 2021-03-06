#MongoDB

**_Strengths:_**  
• Schema-free and document-based models can map to JSON-like structures. [1][4]  
• Its single-system, low concurrency read performance benchmarks are impressive. [4]  
• Its maturity and robustness, track record and tested real-world use cases are practical and important. [2][4]

**_Weaknesses:_**  
• It can lose data in many startling ways. [3]  
• It requires a global write lock to issue any write. [3]  
• The sharding of MongoDB does not work well under load. [4]

**_References:_**   
1. http://www.mongodb.com/presentations/webinar-relational-databases-mongodb-what-you-need-know?_ga=1.245445636.1015518113.1421211754  
2. http://blog.mongodb.org/post/72874267152/transitioning-from-relational-databases-to-mongodb  
3. https://blog.serverdensity.com/does-everyone-hate-mongodb/  
4. http://pastebin.com/raw.php?i=FD3xe6Jt
***

#SQLite
**_Strengths: [1][2]_**  
• SQLite is a very powerful, embedded RDBMS.  
• The entire database consists of a single file on the disk, which makes it extremely portable.  
• SQLite usually will work great as the database engine for low to medium traffic websites.  
• SQLite is great for embedded devices and applications, as well as testing.  

**_Weaknesses: [2]_**  
• Advanced databases come with the support for users, however user management does not exist in SQLite.  
• Since it is not quite complex, SQLite is not possible to tinker with to acquire much additional performance.  

**_References:_**  
1. http://www.sqlite.org/whentouse.html  
2. http://stackoverflow.com/questions/3630/sqlite-vs-mysql  
***

#MySQL
**_Strengths: [1]_**  
• MySQL is one of the most popular and commonly used RDBMS.  
• MySQL can be installed very easily. Third-party tools make it extremely simple to get started with the database.  
• MySQL supports a large number of the SQL functionality that is expected from a RDBMS.  
• MySQL is secure and speedy, scalable and powerful.  

**_Weaknesses: [1][2]_**  
• MySQL is relatively less reliable than some other RDBMSs  
• MySQL has functional limitations that some state-of-the-art applications might require.  

**_References:_**  
1. https://www.digitalocean.com/community/tutorials/sqlite-vs-mysql-vs-postgresql-a-comparison-of-relational-database-management-systems  
2. http://stackoverflow.com/questions/3630/sqlite-vs-mysql  
***

#MySQL Cluster  
MySQL Cluster is a technology providing shared-nothing clustering and auto-sharding for the MySQL database management system. It is designed to provide high availability and high throughput with low latency, while allowing for near linear scalability.  

**_References:_**  
1. http://www.mysql.com/products/cluster/  
2. http://en.wikipedia.org/wiki/MySQL_Cluster  
***

#MySQL Fabric  
MySQL Fabric is a set of tools/middleware written in python that allows the managing of a set of regular MySQL servers in a replicated GTID environment. MySQL Fabric is an extensible framework for managing farms of MySQL Servers.  

**_References:_**  
1. http://www.mysql.com/products/enterprise/fabric.html  
2. http://dba.stackexchange.com/questions/78971/whats-the-difference-between-mysql-fabric-and-mysql-cluster  
***

#PostgreSQL
**_Strengths: [2]_**  
• PostgreSQL is open-source and free.
• PostgreSQL is supported by a devoted and experienced community and has strong third-party support.
• PostgreSQL is extensible and objective.  

**_Weaknesses: [1][2]_**  
• PostgreSQL can be an over-kill for simple read-heavy operations, especially when compared to counterparts like MySQL. It is not simple and speedy.  
• In spite of huge amount of deployments, PostgreSQL is still a relatively less popular tool.  

**_References:_**  
1. https://www.digitalocean.com/community/tutorials/sqlite-vs-mysql-vs-postgresql-a-comparison-of-relational-database-management-systems  
2. http://www.postgresql.org/about/advantages/  
***

#Actian PSQL
**_Strengths: [1]_**  
• Actian PSQL is a RDBMS optimized for embedded devices and applications.  
• Action PSQL is great for software as a service (SaaS) deployment because of its file-based architecture enabling partitioning of data for multi-tenancy needs.  

**_Weaknesses: [2]_**  
• Actian PSQL lacks some of the data warehousing, data mining, and reporting services built into database engines such as MySQL and Microsoft SQL Server.  
• Actian PSQL is not capable of performing distributed transactions.  

**_References:_**  
1. http://www.pervasive.com/database/Home/Resources/Documentation.aspx  
2. http://en.wikipedia.org/wiki/Pervasive_PSQL#Limitations  
***

#Azure SQL Database
**_Strengths: [1][2][3]_**  
• Azure SQL Database is a cloud-based RDBMS and it is highly scalable.  
• Azure SQL Database’s data is redundant.  
• Azure SQL Database can handle more concurrent queries than a single database.  

**_Weaknesses: [1]_**  
• It is complicated for Azure SQL Database to backup.  
• Azure SQL Database’s response time is difficult to predict.  

**_References:_**  
1. https://alexandrebrisebois.wordpress.com/2013/08/08/windows-azure-sql-database-vs-sql-server-in-windows-azure-virtual-machines-vs-alternatives/  
2. http://azure.microsoft.com/en-us/services/sql-database/  
3. http://en.wikipedia.org/wiki/SQL_Azure  
***

#Google Cloud SQL
**_Strengths: [1]_**  
• Google Cloud SQL is a fully managed, highly available relational database.  
• Google Cloud SQL is easy to use and has flexible configurations.  
• Google Cloud SQL has exceptional security and is well integrated with Google Cloud.  

**_Weaknesses: [2]_**  
• User defined functions are not supported.  
• Not all MySQL statements or functions are supported.  
• There is a size limit for individual instances.  

**_References:_**  
1. https://cloud.google.com/sql/docs  
2. https://cloud.google.com/sql/docs/introduction#features
***

#HP Cloud RDB for MySQL
**_Strengths: [1]_**  
• HP Cloud RDB for MySQL is great at managing time-consuming database administration tasks.  
• It uses an open source distribution of MySQL built on OpenStack technology.  
• It is scalable and flexible.  

**_Weaknesses: [2]_**  
• Security breach may occur.  
• The infrastructure may be changed according to the service provider’s preference without the consumer’s consent.  

**_References:_**  
1. http://www.hpcloud.com/products-services/relational-database  
2. http://www.ijteee.org/final-print/oct2013/Cloud-Computing-Service-Providers-And-Applications.pdf
***

#IBM Big SQL
**_Strengths: [1]_**  
• IBM Big SQL allows developers familiar with the SQL programming language to access data in Hadoop without learning new languages or skills.  
• IBM Big SQL is both flexible and scalable.  
• IBM Big SQL has different types of efficient queries.  

**_Weaknesses: [2]_**  
• IBM Big SQL does not turn BigInsights into a relational DBMS.  

**_References:_**  
1. http://www-01.ibm.com/software/data/what-is/big-sql.html  
2. http://www.ibm.com/developerworks/library/bd-bigsql/
***

#InfiniSQL  
**_Strengths: [1]_**  
• InfiniSQL provides free and open source.  
• InfiniSQL is good for high volume real-time data collection, analysis, and transaction processing.  
• InfiniSQL is highly scalable.  

**_Weaknesses: [2]_**
• InfiniSQL does not work well for analysis of data occurring after the events.  

**_References:_**  
1. http://www.infinisql.org/
2. http://www.infinisql.org/docs/faq
***

#MemSQL
**_Strengths: [1]_**  
• MemSQL combines lock-free data structures with a just-in-time (JIT) compiler so that it can process highly volatile workloads.  
• Despite the fact that all the data is stored in memory, MemSQL is durable by implementing a write-ahead log and snapshots.  
• MemSQL is simple and scalable.  

**_Weaknesses: [2][3]_**  
• MemSQL does not have good performance in speed.  

**_References:_**  
1. http://en.wikipedia.org/wiki/MemSQL  
2. http://www.quora.com/SQL/What-benefits-does-MemSQL-offer-over-running-a-MySQL-database-on-ramdisk  
3. http://dom.as/2012/06/26/memsql-rage/  
***

#Microsoft SQL Server
**_Strengths: [1]_**  
• Microsoft SQL Server is easy to use and has professional features.  
• Microsoft SQL Server has excellent Data Recovery Support.  

**_Weaknesses: [2]_**  
• The licensing options of Microsoft SQL Server are very expensive.  
• Microsoft SQL Server is only designed to run on Windows-based servers.  

**_References:_**  
1. http://www.microsoft.com/en-us/server-cloud/products/sql-server/default.aspx?WT.srch=1&WT.mc_id=SEM_GOO_USEvergreenSearch_Cloud&CR_CC=Unassigned  
2. http://www.ehow.com/list_7228389_advantages-disadvantages-microsoft-sql.html  
***

#Microsoft SQL Server PDW  
Microsoft SQL Server Parallel Data Warehouse (SQL Server PDW) is a pre-built data warehouse appliance that includes Microsoft SQL Server database software, third-party server hardware and networking components.

It is a scalable data warehouse appliance that delivers performance and scalability through massively parallel processing. It is Microsoft’s strategy for big data processing.

**_References:_**  
1. https://msdn.microsoft.com/en-us/library/ff519548.aspx  
2. http://searchsqlserver.techtarget.com/definition/Microsoft-SQL-Server-Parallel-Data-Warehouse-SQL-Server-PDW  
***

#Pivotal SQLFire
**_Strengths: [1]_**  
• Pivotal SQLFire has scale-out performance.  
• It has consistent database operations across globally distributed applications.  
• It has high availability, resilience, and global scale.  
• It has standards-based developer features and interfaces.  
• It has easy administration of distributed nodes.  

**_References:_**  
1. http://www.pivotal.io/big-data/pivotal-gemfire-xd  
***

#SAP Sybase SQL Anywhere
**_Strengths: [1]_**  
• Microsoft SQL Server is easy to use and has professional features.
• Microsoft SQL Server has excellent Data Recovery Support.  

**_Weaknesses: [2]_**
• The licensing options of Microsoft SQL Server are very expensive.  
• Microsoft SQL Server is only designed to run on Windows-based servers.  

**_References:_**  
1. http://www.microsoft.com/en-us/server-cloud/products/sql-server/default.aspx?WT.srch=1&WT.mc_id=SEM_GOO_USEvergreen  
***

#HPCC**_Strengths:_**  • HPCC Systems platform can go faster with a lower cost on the individual hardware, which relies on the highly optimized language and compiler.  • The language ECL makes code run rapidly, and the modular feature of ECL guarantees teams’ work productive.  • The organization behind the HPCC platform provides the services to solve real-word problems. Besides, the HPCC platform is designed for scaling up and being extended.  **_Weaknesses:_**  • The ECL language, regarded as declarative programming, focuses on what the problem is rather than how to resolve the problem, which might reduce expressivity.  **_References:_**  1. http://hpccsystems.com/  2. Angelo Mottola, Design and implementation of a declarative programming language in a reactive environment (2005), Universit‡ degli Studi di Roma ìLa Sapienzaî  
***#HyperDex**_Strengths:_**  • Supports applications that might allowed in other NoSQL systems, such as number of accessible languages accessible, strong consistency, which guarantees a highly performance of NoSQL systems.  • Provide fault tolerance and transaction over multiple keys’ support.**_Weaknesses:_**  • The search performance of HyperDex relies on the subspaces in a HyperDex’s table, which would lead to longer value-dependent chains and cause regular occurrence of put latencies.  **_Reference:_**   1. http://hyperdex.org/  2. http://www.cs.cornell.edu/people/egs/papers/hyperdex-sigcomm.pdf  
***#HypergraphDB**_Strengths:_**  • As a graph-oriented database, it is able to store and manage many large graphs and relationships. • Provides the service of customizing indexing, higher-order relationships between graphs’ nodes.• Provides P2P framework of data distribution.  **_Weaknesses:_**  • Not well suited range queries, because of being a distributed harsh table.  
**_References:_**  1. http://www.hypergraphdb.org/index  2. https://groups.google.com/forum/#!msg/hypergraphdb/cnoqlF3h9sg/Rnoxewl9kn0J  ***
#Hypertable**_Strengths:_**  • An open-source database with high performance on solving problems with large scalability.  • No more costs would be spent on garage collection and runtime interpretation by implemented in a compiled language.  **_Weaknesses:_**  • Does not support joins, transactions or opaque byte sequences.  **_References:_**  1. http://hypertable.com/documentation/  2. http://hypertable.com/why_hypertable  ***
#Infinite Graph**_Strengths:_**  • Storage locations are flexible and configurable, thus it’s convenient for users to add storage locations and have no access restriction to these graphs.  • Optimized API for data relationships makes annotations rich and flexible for edges. Enormous paralleled pipelines of agents guarantee the high speed of ingesting data.  • Provides a visualization tool to view the data.  **_Weaknesses:_**  • The configuration is not simple.  • Owing to user-customized nodes and edges, the performance might be impaired for huge graphs.  **_References:_**  1. http://www.objectivity.com/infinitegraph#.VMVBIHB4oQo  2. http://blog.newitfarmer.com/category/nosql/bigtable-store/hypertable  
***#Neo4j**_Strengths:_** • Executes much faster than SQL and keeps constant performance.  • Has improved the flexibility in handling complicated branches by simple nodes and relationships.  **_Weaknesses:_**   • Native support for node types in API is needed, aiming to make the graph model more general.  • Required to add new edges manually in the indexing mechanism, which is inconvenient for users.  **_References:_**  1. http://neo4j.com/product/  2. http://blog.newitfarmer.com/category/nosql/bigtable-store/hypertable  ***#Trinity**_Strengths:_**  • Use hypergraph as data model  • Supports ACI transaction and highly concurrent online query processing.  • Able to be implemented in distributed mode  **_Weaknesses:_**  • Not open to the outside of Microsoft  **_References:_**  1. http://blog.newitfarmer.com/category/nosql/bigtable-store/hypertable  ***
#AllegroGraph**_Strengths:_**  • Planned to build RDF-centric semantic web applications and supports SPARQL, RDFS++, and Prolog.  • Large scalability of RDF triples while keeping high performance.  **_Weaknesses:_**  • Not used for general graphs, only ideal for RDF.  **_References:_**  1. http://blog.newitfarmer.com/category/nosql/bigtable-store/hypertable  ***#CouchDB**_Strengths:_**  • As a document database, can be queried and indexed using MapReduce expressions.  • Maps document IDs to documents.  • Provides conflict detection.  
**_Weaknesses:_**  • Slow on temporary views on large datasets.  • Duplication of large databases may fail.  • Server-side logic is required for user-side updates.  **_References:_**  1. http://blog.newitfarmer.com/category/nosql/bigtable-store/hypertable  2. http://stackoverflow.com/questions/7858699/disadvantages-of-couchdb  
***#Couchbase:**_Strengths:_**  • Have access to data with a fast speed.  • Supported by friendly cluster-management website.  • Allows cross-datacenter replication.  **_Weakness:_**  • Not easy for development.  
**_Reference:_**  1. http://tek-tips.nethawk.net/chatting-with-bob-wiederhold-of-couchbase-nosql-database-company/  2. http://blog.newitfarmer.com/category/nosql/bigtable-store/hypertable  ***