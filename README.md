# CassandraDataLifeCycle

## Replica 1 and Token Distribution

1. Create cluster with 3 nodes
1. Create keyspace and table
1. Insert data
1. List data by node
1. Add node
1. List data by node

## Replica n and Rack Distribution
1. Create Cluster with 0 nodes
1. Add 6 nodes, each in their own rack
1. Create keyspace rf=1 and table
1. Insert data
1. List data by node
1. Increase RF to 2
1. List data by node
1. Increase RF to 3
1. List data by node


