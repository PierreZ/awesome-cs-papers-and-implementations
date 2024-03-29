# Awesome CS papers and implementations [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

An awesome list about the most iconic CS papers and their open source implementation.

**EDIT 2021:** This repo is archived, You can now find all my favorite papers in my [Zotero library!](https://www.zotero.org/pierre.zemb/collections/VUVPTBG8)

## Papers

### Databases

| Company or university | Name of the paper   |  Name of the opensource implementation  |
| ------------- | ------------- | ---------------- |
| Google |  [Bigtable: A Distributed Storage System for Structured Data](https://static.googleusercontent.com/media/research.google.com/fr//archive/bigtable-osdi06.pdf) | [HBase](https://hbase.apache.org)
| Amazon | [Amazon Dynamo](http://s3.amazonaws.com/AllThingsDistributed/sosp/amazon-dynamo-sosp2007.pdf) | [Voldemort](https://github.com/voldemort/voldemort)
| Facebook | [Cassandra — A Decentralized Structured Storage System](http://www.cs.cornell.edu/projects/ladis2009/papers/lakshman-ladis2009.pdf) | [Cassandra](http://cassandra.apache.org/)
| Google | [Dremel: Interactive Analysis of Web-Scale Datasets](https://static.googleusercontent.com/media/research.google.com/fr//pubs/archive/36632.pdf) | [Apache Drill](https://drill.apache.org/)
| Google | [Spanner: Google’s Globally-Distributed Database](https://static.googleusercontent.com/media/research.google.com/fr//archive/spanner-osdi2012.pdf) | [CockroachDB](https://github.com/cockroachdb/cockroach)
| Google | [F1: A Distributed SQL Database That Scales](https://ai.google/research/pubs/pub41344.pdf) | 
| Amazon | [Amazon Aurora: Design Considerations for High Throughput Cloud-Native Relational Databases](https://media.amazonwebservices.com/blog/2017/aurora-design-considerations-paper.pdf) | 
| Apple | [FoundationDB Record Layer:A Multi-Tenant Structured Datastore](https://arxiv.org/pdf/1901.04452.pdf) | 

### Distributed systems

| Company or university | Name of the paper   |  Name of the opensource implementation  |
| ------------- | ------------- | ---------------- |
| Google | [The Google file system](https://research.google.com/archive/gfs-sosp2003.pdf)  |[Hadoop Distributed File System](https://hadoop.apache.org/docs/r1.2.1/hdfs_design.html)  |
| Google |  [MapReduce: Simplified Data Processing on Large Clusters](https://static.googleusercontent.com/media/research.google.com/fr//archive/mapreduce-osdi04.pdf) | [MapReduce in Hadoop](https://hadoop.apache.org/docs/r1.2.1/mapred_tutorial.html)
| Google | [Dapper, a Large-Scale Distributed Systems Tracing Infrastructure ](https://research.google.com/pubs/pub36356.html)  |[Zikpkin?](https://zipkin.io/)  |
| Google | [Large-scale cluster management at Google with Borg](https://research.google.com/pubs/archive/43438.pdf) | [Mesos](http://mesos.apache.org/)
| LinkedIn | [Kafka: a Distributed Messaging System for Log Processing](http://notes.stephenholiday.com/Kafka.pdf) | [Apache Kafka](http://kafka.apache.org/)

### Distributed transactions

| Company or university | Name of the paper   |  Name of the opensource implementation  |
| ------------- | ------------- | ---------------- |
| Google | [Large-scale Incremental Processing Using Distributed Transactions and Notifications ](https://ai.google/research/pubs/pub36726.pdf)  |
| Yale university | [Calvin: Fast Distributed Transactionsfor Partitioned Database Systems](http://cs.yale.edu/homes/thomson/publications/calvin-sigmod12.pdf)  |
| eBay | [SLOG: Serializable, Low-latency, Geo-replicated Transactions](http://www.cs.umd.edu/~abadi/papers/1154-Abadi.pdf)  |


### Consensus

| Company or university | Name of the paper   |  Name of the opensource implementation  |
| ------------- | ------------- | ---------------- |
| Google | [The Chubby lock service for loosely-coupled distributed systems](https://static.googleusercontent.com/media/research.google.com/fr//archive/chubby-osdi06.pdf) | [ZooKeeper](http://zookeeper.apache.org/)
| Stanford University | [In Search of an Understandable Consensus Algorithm(Extended Version)](https://raft.github.io/raft.pdf) | [The Raft Consensus Algorithm](https://raft.github.io/)
| Microsoft | [Paxos Made Simple](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/12/paxos-simple-Copy.pdf) | 

### Crypto

| Company or university | Name of the paper   |  Name of the opensource implementation  |
| ------------- | ------------- | ---------------- |
| Google |  [Macaroons: Cookies with Contextual Caveats for Decentralized Authorization in the Cloud](https://research.google.com/pubs/archive/41892.pdf) | [libmacaroons](https://github.com/rescrv/libmacaroons)
| Bitcoin |  [Bitcoin: A Peer-to-Peer Electronic Cash System](https://bitcoin.org/bitcoin.pdf) | [Bitcoin](https://github.com/bitcoin/bitcoin)

# How to contribute

I'm looking forward to discover new papers made by companies, please send me PR!
