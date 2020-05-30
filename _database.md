# Awesome Database Reverse Engineering

A curated list of awesome reverse engineering resources to make you better! 

Managed by Reversing.ID for the reversing community.

## Introduction

`Database Reverse Engineering` focus on collection of structured data (entities) and relationship among them.

The strategy for storing structured data has evolved over time. Different strategy has different characteristic. As of today we can categorize the database into three types:

- Flat-File Database
- Relational Database
- Non-Relational Database

Database Reverse Engineering might used for schema recovery or remodelling.

## Table of Contents

- Resources
    - [Books](#books)
    - [Courses](#courses)
    - [DBMS List](#dbms-list)
    - [DB Connections](#db-connections)
- [Relational Database](#relational-database)
    - [Database Administration Client](#database-administration-client)
    - [Code Generation](#code-generation)
    - [Schema Modellers](#schema-modellers)
    - [Schema Navigation & Visualization](#schema-navigation--visualization)
- [Non-Relational Database](#non-relational-database)
- [Flat-File Database](#flat-file-database)
    - [Hex Editors](#hex-editors)
    - [Structure Parsers](#structure-parsers)

- - -

## Books

## Courses

## DBMS List

Some notable DBMS, not a comprehensive list.

Relational Database

* [MariaDB](https://mariadb.org/)
* Microsoft Access - file-based data storage for desktop application.
* Microsoft SQL Server
* [MySQL](https://www.mysql.com/)
* [Oracle Database](https://www.oracle.com/database/)
* [PostgreSQL](https://www.postgresql.org/)
* [SQLite](https://www.sqlite.org/) - small, fast, self-contained, embedded SQL database engine.

Non-Relational Database (NoSQL)

* Column:
    - [Apache Cassandra](https://cassandra.apache.org/)
    - [Apache HBase](https://hbase.apache.org/)
    - [ScyllaDB](https://www.scylladb.com/)
* Document:
    - [Apache CouchDB](https://couchdb.apache.org/)
    - [ArangoDB](http://arangodb.com/)
    - [Couchbase](http://couchbase.com/)
    - [MongoDB](https://www.mongodb.com/)
* Graph:
    - [ArangoDB](http://arangodb.com/)
    - [Neo4j](https://neo4j.com/)
    - [Redis](https://redis.io/)
* Key-Value Store:
    - [ArangoDB](http://arangodb.com/)
    - [Couchbase](http://couchbase.com/)

## DB Connections

Database Connection is facility to allow client software to talk to database server, whether on the same machine or not. Sending query and receiving result set are done in active connection.

Connections are built by supplying an underlying driver or provider with a `Connection String`, which is a way of addressing a specific database or server. The Connection String is usually a combination of following field in a single statement:

* Server: domain or ip address of database server
* Database: database name
* Uid: username which is granted access to database
* Pwd: password to identify username.

Example:

```
Server=db.internal.reversing.id; Database=identity; Uid=service; Pwd=service_pwd
```

Database connection often wrapped by API. Common used API are:

* JDBC (Java Database Connectivity)
* ODBC (Open Database Connectivity)

- - - 

## Relational Database

Database Reverse Engineering for Relational Database focus on tables, models, stored procedure, primary keys, and foreign keys to determine relationship between tables and reconstructing E-R Diagram.

A database is logically made of several tables. Relationship is implemented by keys (primary key, foreign key) to map the tables into `One-to-One`, `One-to-Many`, or `Many-to-Many` relation.

#### Database Administration Client

Desktop

* [DataGrip](https://www.jetbrains.com/datagrip)
* [DBeaver](https://github.com/dbeaver/dbeaver)
* dbForge Studio for [MySQL/MariaDB](https://www.devart.com/dbforge/mysql/studio), [Oracle](https://www.devart.com/dbforge/oracle/studio), [PostgreSQL](https://www.devart.com/dbforge/postgresql/studio), [SQL Server](https://www.devart.com/dbforge/sql/studio)
* [HeidiSQL](https://github.com/HeidiSQL/HeidiSQL)
* [MySQL Workbench](https://www.mysql.com/products/workbench/)
* [Navicat](https://www.navicat.com/en/products#navicat)
* [SQL Server Management Studio](https://docs.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms)

Web App

* [Adminer](https://github.com/vrana/adminer)
* [phpLiteAdmin](https://www.phpliteadmin.org/) - SQLite database administration
* [phpMyAdmin](https://github.com/phpmyadmin/phpmyadmin) - MySQL and MariaDB database administration

CLI

* [litecli](https://github.com/dbcli/litecli) - SQLite
* [mssql-cli](https://github.com/dbcli/mssql-cli) - SQL Server
* [mycli](https://github.com/dbcli/mycli) - MySQL and MariaDB
* [pgcli](https://github.com/dbcli/pgcli) - PostgreSQL

#### Code Generation

* [ddl-generator](https://github.com/catherinedevlin/ddl-generator) - Infers SQL DDL (Data Definition Language) from table data.
* [scheme2ddl](https://github.com/qwazer/scheme2ddl) - Command line util for export Oracle schema to set of ddl init scripts with ability to filter undesirable information, separate DDL in different files, pretty format output.

#### Schema Modeller

* [Navicat Data Modeler](https://www.navicat.com/en/products/navicat-data-modeler) - A powerful and cost-effective database design tool which helps you build high-quality conceptual, logical and physical data models.
* [Oracle SQL Developer Data Modeler](http://www.oracle.com/technetwork/developer-tools/datamodeler/overview/index.html) - Oracle SQL Developer Data Modeler is a free graphical tool that enhances productivity and simplifies data modeling tasks.
* [pgmodeler](https://github.com/pgmodeler/pgmodeler) - Data modeling tool designed for PostgreSQL.

#### Schema Navigation & Visualization

* [dbdiagram.io](https://dbdiagram.io) - quick and simple online tool for drawing database relationship diagrams.
* [dbvis](https://www.dbvis.com/) - 
* [ERAlchemy](https://github.com/Alexis-benoist/eralchemy) - Entity Relation Diagrams generation tool.
* [SchemaCrawler](https://github.com/schemacrawler/SchemaCrawler) - A free database schema discovery and comprehension tool.
* [Schema Spy](https://github.com/schemaspy/schemaspy) - Generating your database to HTML documentation, including Entity Relationship diagrams.
* [tbls](https://github.com/k1LoW/tbls) - CI-Friendly tool for document a database, written in Go.

- - - 

## Non-Relational Database

Database Reverse Engineering for Non-Relational Database focus on models and relationship of each models. 

Non-Relational Database refers to storage and retrieval of data which is modeled in means other than tabular relations used in Relational Database.

Non-Relational DBMS might offer a language to query data as alternative to SQL. Some notable query languages are AQL, Cypher, GraphQL, Gremlin, and SPARQL.

There are many types of approaches of NoSQL, such as Column, Document, Graph, Key-Value, and Object.

`Column`-oriented database stores data tables by columns rather than by rows. Unlike Relational Database, the names and format of the columns can vary from row to row in the same table.

`Document`-oriented database store data in the form of document. Document is a general term for encapsulating and encoding data in standard format such as XML, YAML, JSON, and binary format.

`Graph` database use graph structures for semantic queries with nodes, edges, and properties to represent data.

`Key-Value` database use the associative array (also called map or dictionary) as their fundamental data model. In this model, data is represented as a collection of Key-Value pairs.

`Object`-oriented database represent information in the form of objects as used in `Object-Oriented Programming`. 

- - - 

## Flat-File Database

Database Reverse Engineering for Flat-File Database is based on [File Format Reverse Engineering](_format.md). It focus on files, indexes and keys to determine structure of record and relationships of tables.

In pre-DBMS era, each table is stored as a simple file. Access to data is actually I/O operations. The file can be a plain text file or a binary file. The database is a collection of files which contain structured data and cross-reference to each other.

Records follow a uniform format. The size depends on number and size of fields. There are different conventions for depicting data. Fields and records might be separated by delimiter. If not, parser is responsible to read and interpret each record and field.

Relationship can be inferred from the data. Each record may have `Primary Keys` and `Foreign Keys`.

Iterating all records for locating specific item is inefficient especially when I/O operation involved. To speed up operation, `Indexing` is used. Index consists of two fields: `Search Key` and `Pointer`. Search Key is a copy of `Primary Key` and `Pointer` is offset where record can be found on file. Only selective key appears on Index. Usually the first item in the block of records.

`Index` can appear as internal or external of file. Internal Index implemented as header or trailer of data file. While External Index is implemented as a separate file. Multilayer indexing is possible where two or more Index file used.

## Hex Editors

Hex editor lets you view/edit the binary data of a file.

Multi/cross platform

* [010 Editor](http://www.sweetscape.com/010editor/)
* [Kaitai Struct](https://kaitai.io)
* [wxHexEditor](https://www.wxhexeditor.org/)

Windows 

* [HxD](https://mh-nexus.de/en/hxd/)
* [Hex Workshop](http://www.hexworkshop.com/)
* [Hexinator](https://hexinator.com/)

Mac OS X

* [HexFiend](http://ridiculousfish.com/hexfiend/)

## Structure Parsers

* [010 Editor](http://www.sweetscape.com/010editor/)
* [Kaitai Struct](https://kaitai.io)

