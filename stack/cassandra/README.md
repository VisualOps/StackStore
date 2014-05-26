## Cassandra
Apache Cassandra is an open source distributed database management system designed to handle large amounts of data across many commodity servers, providing high availability with no single point of failure. Cassandra offers robust support for clusters spanning multiple datacenters, with asynchronous masterless replication allowing low latency operations for all clients.

## Stack
This stack is a a 4-node [Cassandra](http://cassandra.apache.org/) cluster setup, with 2 seed nodes. Since Cassandra has a symmetric architecture, the nodes in this stack share the similar states, except that a daemon in the first seed node will be started before others.

![](https://trello-attachments.s3.amazonaws.com/5369add918a15e844104d0ef/536b4d9e4a9d69b21b5c2ac1/910x854/24963e500c7d110db6038f2a8ce32d48/cassandra.png)
