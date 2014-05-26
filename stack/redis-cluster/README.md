## Redis
Redis is an open-source, networked, in-memory, key-value data store with optional durability.

## Stack
This stack is a 6 nodes [Redis Cluster]( http://redis.io/topics/cluster-tutorial/) setup. The six nodes are split into 3 masters/slaves groups, on which each group contains exactly one master and one slave. 
The data sharding is done among the three master nodes. All nodes share the same states, except "host-0", which contains the cluster creation and initialization instructions.

![](https://trello-attachments.s3.amazonaws.com/5369add918a15e844104d0ef/536b4d9e4a9d69b21b5c2ac1/1030x764/76e628906a363bdeb21f26f6d00ab9f7/redis-cluster.png)
