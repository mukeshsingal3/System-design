This video describes how to prepare for system design interview. Below is all the content described in the video.
A - Ask good questions
	- Which feature to work on
	- What kind of data in database, system latency, requests per second 
B - Don't use buzzwords
C - Clear and organized thinking
D - Drive discussions with 80-20 rule

Things to consider
	→ Features
		○ important features to consider, what feature can be excluded
	→ API 
		○ what APIs going to be created to make system to work the best 
	→ Availability
		○ When service goes down, system still work?
	→ Latency
		○ What is latency ?
	→ Scalability
		○ Is it just work for 1000 user or continue of be available for 1 M users also 
	→ Durability
		○ Data case stored safely without loss, and no data compromise 
	→ Class Diagram
		○  To design system, class diagram make the deeper level of system interactions
	→ Security and Privacy
	→ Cost-effective
		○ Is there any other cost alternate effective solution?

Concepts to know
	→ Vertical vs horizontal scaling
		○ Vertical scale meaning upgrade existing hardware
		○ Horizontal scale meaning adding more hosts 
	→ CAP theorem
		○ Consistency, Availability and Partition tolerance. 
		○ Consistence - Read has most recent write 
		○ Availability  - Read can be recent write 
		○ Partition tolerance - data can be distributed
	→ ACID vs BASE
		○ Atomicity Consistency Isolation Durability (Mostly in SQL)
		○ Basic Availability Soft State Eventual Consistency (Mostly In NoSQL) 
	→ Partitioning/Sharding 
		○ How to store vast amount of data across multiple nodes
		○ Consistent Hashing
	→ Optimistic vs pessimistic locking
		○ Data base transection might lock the record before update or check if record updated before update
	→ Strong vs eventual consistency
		○ Strong  - Read has most recent write
		○ Eventual -  Read has might be recent write
			§ Provide high availability 
	→ Relational DB vs NoSQL
	→ Types of NoSQL
		○ Key value
		○ Wide column
		○ Document-based
		○ Graph-based
	→ Caching 
		○ Speed up request to make process request faster
		○ Store most frequently used data 
		○ Two type 
			§ Every node has cache
			§ Cache is shared
	→ Data center/racks/hosts
	→ CPU/memory/Hard drives/Network bandwidth
		○ How to work with limitation on these limited resources. 
	→ Random vs sequential read/writes to disk
	→ HTTP vs http2 vs WebSocket
	→ TCP/IP model
	→ ipv4 vs ipv6
	→ TCP vs UDP
		○ TCP - Connection oriented Reliable Connection (sending docs)
		○ UTP - Unreliable  Connection (streaming)
	→ DNS lookup
	→ Http & TLS(Transport layer security)
	→ Public key infrastructure and certificate authority(CA)
	→ Symmetric vs asymmetric encryption
	→ Load Balancer
		○ L4
		○ L7
	→ CDNs & Edges
	→ Bloom filters and Count-Min sketch
	→ Paxos 
	→ Leader election
	→ Design patterns and Object-oriented design
	→ Virtual machines and containers
	→ Pub-sub architecture 
	→ MapReduce
	→ Multithreading, locks, synchronization, CAS(compare and set)

Tools
	→ Cassandra
	→ MongoDB/Couchbase
	→ MySQL
	→ Memcached
	→ Redis
	→ Zookeeper
	→ Kafka
	→ NGINX
	→ HAProxy
	→ Solr, Elastic search
	→ Amazon S3
	→ Docker, Kubernetes, Mesos
	→ Hadoop/Spark and HDFS

References
https://docs.datastax.com/en/cassandr...
http://cloudurable.com/blog/kafka-arc...
https://zookeeper.apache.org/doc/trun...
http://www.allthingsdistributed.com/f...
https://research.google.com/archive/b...
https://en.wikipedia.org/wiki/CAP_the...
https://en.wikipedia.org/wiki/Consist...
https://www.mongodb.com/mongodb-archi...
https://en.wikipedia.org/wiki/HTTP/2
https://en.wikipedia.org/wiki/Transpo...
