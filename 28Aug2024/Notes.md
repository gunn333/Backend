### MongoDB
MongoDB is a popular open-source NoSQL database. Unlike traditional relational databases that use tables and rows, MongoDB stores data in flexible, JSON-like documents (BSON - Binary JSON). This document-oriented approach allows for more complex and hierarchical data structures, making it easier to handle unstructured or semi-structured data.

No Sql: Document form mein key-pairs pairs

BSON: Much faster than JSON

Options for MongoDB: 
1. Atlas(cloud based momgo db server)
2. Compass(local server)

What we will do:
1.CLI
2.GUI
3.ExpressJS with MongoDB

Mongosh: shell to connect CLI version

step1:create a server of mongodb

D1 Database od chitkara has multiple collections: users, faca, students

collections are in documents[key value pairs]


##Commands:
1.mongosh:for checking version and installation.
2.show dbs:for check databases
3.use database_name:for creating database
4.db.createCollection("Collection_name"):for craeting collections.
5.db.collection.insertOne():for inserting single document inside collection.
6.db.collection.insertMany():for inserting many documents at same time in a collection.
