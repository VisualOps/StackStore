## MongoDB
MongoDB is a cross-platform document-oriented database. Classified as a NoSQL database, MongoDB eschews the traditional table-based relational database structure in favor of JSON-like documents with dynamic schemas (MongoDB calls the format BSON), making the integration of data in certain types of applications easier and faster. Released under a combination of the GNU Affero General Public License and the Apache License, MongoDB is free and open-source software.

## Stack
This stack is a template for an [MongoDB](http://www.mongodb.org/) cluster setup. The stack includes a production-level 3-nodes setup of Mongo Config Server, a 3-nodes replication set, and a single mongos node that initializes the sharding setup upon launching. You can add more replication sets to the cluster, or remove the mongos node and initialize the sharding on your client side.

![](https://trello-attachments.s3.amazonaws.com/5369add918a15e844104d0ef/536b4d9e4a9d69b21b5c2ac1/750x874/7962f1dcdf976a75101679ccde205a49/mongo-cluster.png)
