HDFS Helm Chart
===============

The Hadoop Distributed File System (HDFS) is a distributed file system designed to run on commodity hardware. This Helm Chart can be used to deploy a HDFS instance onto a Kubernetes cluster.

By default, this chart deploys:
* 2 x name node, configured with 1 x 10GB data volume
* N x data nodes, each configured with 2 x 10GB data volumes
* configuration for a replication factor of 3