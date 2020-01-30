---
title: "Centauri: A Distributed, Memory-efficient Graph-based kNN System"
collection: HPC
type: "Research Assistant"
permalink: /project/4-centauri
venue: "Center for High Performance Computing, SJTU"
date: 2019-08-01
location: "Shanghai, China"
---
A distributed graph-based K-Nearest-Neighbor Search(KNNS) system in order to address the high memory comsumption issue.
![Architecture](/images/centauri/arch.png "Centuri")

- I designed *Centauri*, a distributed graph-based KNNS system. It is proposed to address the memory comsumption issue of previous system.
- I used Graph Compression, distribution and a newly-proposed navigating network to reduce the memory usage in a single machine.
- To mend up the high latency, I use batching technique to reduce the communication times.
![Batch](/images/centauri/batch.png "Batching techniques. Each message carries multiple queries and responses")



