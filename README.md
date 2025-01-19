# System Design Cheat Sheet

## Networking

**DNS** - Domain Name System (resolvers, nameservers, records)  
**Load Balancers** - Hardware, Sofware, Layer4, Layer 7  
**CDNs** - Content Delivery Network (Caching, Edge Servers)  
**Proxies** - Forward, Reverse, Tranparent, Anonumous  
**VPNs** - Virtual Private Networks (tunneling protocols)  
**Firewalls** - Packet filtering, stateful inspection  
**NAT** - Network Address Translation  
**Gateways** - Connect different networks  
**Routers** - Direct traffic between networks  

## Compute

**Servers** - Bare Metal, Virtual Machines (VMs)  
**Containers** - Docker, Kubernetes, Container Orchestration  
**Serverless** - AWS Lambda, Azure Functions, Google Cloud Functions  
**FaaS** - Function-as-a-Service  
**PasS** - Platfor-as-a-Service  

## Storage

**Databases** - SQL, NoSQL (Key-Value, Document, Columnar, Graph), NewSQL  
**Object Storage** - Amazon S3, Google Cloud Storage, Azure BLOB Storage  
**Block Storage** - Network-attached storage(NAS), Storage Area Networks(SAN)  
**File Systems** - Distributed file systems (HDFS, Ceph), Network File System (NFS)  
**Caching** - Redis, Memcached, Varnish, CDN edge caches  

## Architectural Paterns

**Microservices** - Domain-driven design (DDS), Service discovery, API gateways  
**Monolithic** - Layered Architecture, MVC, MVP  
**Event-Driven** - Event Sourcing, CQRS  
**Serverless** - FaaS, BaaS  

## Communication

**APIs** - REST, GraphQL, SOAP, gRPC  
**Message Queues** - RabbitMQ, Kafka, ActiveMQ, Amazon SQS  
**WebSockets** - Real-time, full-duplex communication  
**RPC** - Remote Procedure Call, XML-RPC, JSON-RPC  
**Pub/Sub** - Publish-subscribe messaging pattern  
**Service Mesh** - Isito, Linkerd  

## Scalability & Reliability

**Horizontal Scaling** - Load Balancers, auto-scaling groups  
**Vertical Scaling** - Largest Instances, More resources  
**Replication** - Master-slave, master-master  
**Sharding** - Partitioning data across multiple databases  
**Redundancy** - Multiple Instances, Failover Mechanisms  
**Fault Tolerance** - Graceful degradation, ccircuit breakers  
**Disaster Recovery** - Backups, replication, geo-redundancy  

## Security

**Authentication** - Multi-factor Authentication (MFA), Single Sign-On (SSO), OAuth, OpenID Connect  
**Authorization** - Role-Based access control (RBAC), Attribute-based access control  
**Security Protocols** - TLS/SSL, HTTPS, SSH  
**Web Application Firewalls(WAF)** - Protect against web attacks  
**Intrusion Detection Systems(IDS)** - Identify Malicious Activity  

## Observability

**Monitoring** - Prometheus, Grafana, Datadog, New Relic  
**Logging** - ELK Stack (Elastisearch, Logstash, Kibana), Splunk  
**Tracing** - Distributed tracing(Jaegar, Zipkin)  
**Metrics** - Counters, Gauges, Histograms, Summaries  
**APM** - Application Performance Monitoring (Dynatrace, AppDynamics)  

































