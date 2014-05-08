Stack List
==============================================

Apache Hadoop
-------------
This stack is a template for an [Apache Hadoop](http://hadoop.apache.org/) v1 with Secondary NameNode setup.
![](https://trello-attachments.s3.amazonaws.com/5369add918a15e844104d0ef/536b4d9e4a9d69b21b5c2ac1/1000x894/762f2e7fae4e955e05b7f7c9b202625a/hadoop.png "Hadoop v1 with Secondary NameNode")

Ghost
-----
This stack is a template for deploying a blogging web application, using [Ghost](http://ghost.org/) platform.
![](https://trello-attachments.s3.amazonaws.com/5369add918a15e844104d0ef/536b4d9e4a9d69b21b5c2ac1/670x514/568e39ce2e7e0d605c6e8cb09550e568/ghost.png "Ghost blog")

Nginx
-----
This stack is a template for deploying a web application, using [Nginx](http://nginx.org/) as web server and load-balancer.
![](https://trello-attachments.s3.amazonaws.com/5369add918a15e844104d0ef/536b4d9e4a9d69b21b5c2ac1/930x814/3dec5922920db4ff1d5e973fae832da1/nginx.png "Nginx")

Spark
-----
This stack is a template for deploying a [Spark](http://spark.apache.org/) solution with [ZooKeeper](http://zookeeper.apache.org/).
![](https://trello-attachments.s3.amazonaws.com/5369add918a15e844104d0ef/536b4d9e4a9d69b21b5c2ac1/1210x944/6a16d76fdc5cbec8fe4fda56a72400f8/spark.png "Spark with Zookeeper"))

VPC with public subnet
----------------------
This stack is a template of a very simple [VPC](http://aws.amazon.com/vpc/) solution, with no specific instance state. Use it to learn how to configure your first VPC.
![](https://trello-attachments.s3.amazonaws.com/5369add918a15e844104d0ef/536b4d9e4a9d69b21b5c2ac1/980x694/e4758bea4b8dd05c926a4b8f629d9686/vpc.png "VPC with public subnet")

Apache Cassandra
-------------
This stack is a a 4-node [Cassandra](http://cassandra.apache.org/) cluster setup, with 2 seed nodes. Since Cassandra has a symmetric architecture, the nodes in this stack share the similar states, except that a daemon in the first seed node will be started before others.

![](https://trello-attachments.s3.amazonaws.com/5369add918a15e844104d0ef/536b4d9e4a9d69b21b5c2ac1/910x854/24963e500c7d110db6038f2a8ce32d48/cassandra.png)

MongoDB Cluster
-------------
This stack is a template for an [MongoDB](http://www.mongodb.org/) cluster setup. The stack includes a production-level 3-nodes setup of Mongo Config Server, a 3-nodes replication set, and a single mongos node that initializes the sharding setup upon launching. You can add more replication sets to the cluster, or remove the mongos node and initialize the sharding on your client side.
![](https://trello-attachments.s3.amazonaws.com/5369add918a15e844104d0ef/536b4d9e4a9d69b21b5c2ac1/750x874/7962f1dcdf976a75101679ccde205a49/mongo-cluster.png)

Redis Cluster
-------------
This stack is a 6 nodes [Redis Cluster]( http://redis.io/topics/cluster-tutorial/) setup. The six nodes are split into 3 masters/slaves groups, on which each group contains exactly one master and one slave. 
The data sharding is done among the three master nodes. All nodes share the same states, except "host-0", which contains the cluster creation and initialization instructions.
![](https://trello-attachments.s3.amazonaws.com/5369add918a15e844104d0ef/536b4d9e4a9d69b21b5c2ac1/1030x764/76e628906a363bdeb21f26f6d00ab9f7/redis-cluster.png)
