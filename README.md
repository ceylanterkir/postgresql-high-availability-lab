PostgreSQL High Availability Lab

1. Project Overview

This repository documents a PostgreSQL High Availability (HA) architecture studied during my Database Administration internship at Istanbul Metropolitan Municipality (IMM), Türkiye.

The project focuses on understanding a three-node PostgreSQL cluster architecture and the interaction between PostgreSQL, Patroni, etcd, HAProxy and Keepalived.

The main objective is to understand database availability, cluster coordination, connection routing and failover concepts.

2. Architecture

The laboratory architecture covered the following components:

* PostgreSQL database nodes
* Patroni for PostgreSQL high availability management
* etcd as the Distributed Configuration Store (DCS)
* HAProxy for database connection routing
* Keepalived for Virtual IP (VIP) management

Component Responsibilities

Component	Purpose
PostgreSQL	Relational database management
Patroni	PostgreSQL cluster management and failover coordination
etcd	Distributed configuration and cluster state management
HAProxy	Connection routing and health checks
Keepalived	Virtual IP management and endpoint availability

3. Technologies

* PostgreSQL
* Patroni
* etcd
* HAProxy
* Keepalived
* Linux

4. Technical Topics Covered

* Primary and standby database architecture
* PostgreSQL replication concepts
* High availability management
* Distributed configuration management
* Cluster health monitoring
* Failover and switchover concepts
* Database connection routing
* Virtual IP management

5. Learning Outcomes

Through this internship experience, I developed an understanding of:

* PostgreSQL high availability architecture.
* The relationship between Patroni and PostgreSQL.
* The role of etcd in cluster coordination.
* HAProxy-based connection routing.
* Keepalived and virtual IP concepts.
* Database availability and failover mechanisms.

6. Project Scope and Disclaimer

This repository is an independent educational documentation project based on my internship learning and laboratory experience.

The original laboratory computer and working files are no longer available. Therefore, this repository documents the architecture and technical concepts rather than claiming to reproduce the original environment or provide verified test results.

No confidential institutional information, internal configurations, credentials or production data are included.

This project is not an official publication of Istanbul Metropolitan Municipality.