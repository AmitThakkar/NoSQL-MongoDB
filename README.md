# NoSQL  MongoDB

Agenda:
-------

* What is NoSQL?
* Why NoSQL?
* Why MongoDB?
* Install MongoDB
* SQL terms in MongoDB
* Data Modeling
* Queries

## What is NoSQL?
`Not only SQL`

## NoSQL types:
* Document 
    1. MongoDB
    2. CouchDB
* Key-Value Pair
    1. Redis
    2. Cassandra
* Graph
    1. Neo4j
    2. HyperGraphDB
Popular NoSQL Database: [http://nosql-database.org/](http://nosql-database.org/).

## Why NoSQL?
* More scalable then RDBMS
* Can Handle large volumes of Data
* Much faster then RDBMS
![https://raw.githubusercontent.com/AmitThakkar/NoSQL-MongoDB/master/graph.png](https://raw.githubusercontent.com/AmitThakkar/NoSQL-MongoDB/master/images/graph.png)

## Why is MongoDB?
* Rich query model.
* Full Index Support
* High Performance.
* Vertical + Horizontal scalable.
* Geospatial support.
* Map-Reduce.
* Professional Support by MongoDB.

## Install MongoDB
[http://docs.mongodb.org/manual/installation/](http://docs.mongodb.org/manual/installation/).

## SQL terms in MongoDB
SQL          | MongoDB
-------------|---------
Database     | Database
Table        | Collection
Row          | Document
Column       | Field

## Data Modeling
![https://raw.githubusercontent.com/AmitThakkar/NoSQL-MongoDB/master/data-modeling.png](https://raw.githubusercontent.com/AmitThakkar/NoSQL-MongoDB/master/images/data-modeling.png)

## Queries
* To start MongoDB shell/client: `mongo`.
* To list database names: `show dbs`.
* To select a database: `use dbName`.
* To list all the collection names: `show tables` or `show collections`.
* To insert a document: `db.collectionName.insert({name:'Amit', age:27})`.
* To remove a document: `db.collectionName.remove({name:'Amit'})`.
* To read a document: `db.collectionName.find({name:'Amit'})`.