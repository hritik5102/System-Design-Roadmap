# 🧭 System Design Roadmap (Foundations → Advanced)

_A single flat checklist of every topic, grouped by phase and main topic. Check items off as you go._


## Phase 1 - Foundations

**Networking Fundamentals**
- [ ] OSI Model
- [ ] IP Addresses
- [ ] DNS - How DNS Actually Works
- [ ] HTTP vs HTTPS
- [ ] TCP vs UDP
- [ ] Proxy vs Reverse Proxy
- [ ] Checksums

**Core System Design Vocabulary**
- [ ] What is Load in system design?
- [ ] Latency vs Throughput vs Bandwidth
- [ ] Scalability
- [ ] Vertical vs Horizontal Scaling
- [ ] Availability
- [ ] Reliability
- [ ] Fault Tolerance
- [ ] SPOF (Single Point of Failure)
- [ ] Failover
- [ ] CAP Theorem
- [ ] Strong vs Eventual Consistency
- [ ] Read-after-write consistency

**Capacity Estimation**
- [ ] QPS / RPS basics
- [ ] Estimating traffic for backend systems
- [ ] Storage estimation for large systems
- [ ] Read-heavy vs Write-heavy systems
- [ ] Capacity planning basics


## Phase 2 - Communication Layer

**APIs**
- [ ] What is an API
- [ ] REST vs GraphQL
- [ ] REST vs RPC
- [ ] WebSockets
- [ ] Long Polling vs WebSockets
- [ ] Webhooks
- [ ] Idempotency
- [ ] JWTs (JSON Web Tokens)
- [ ] API Design best practices
- [ ] Synchronous vs Asynchronous communication

**API Gateway & Traffic Control**
- [ ] What is an API Gateway
- [ ] Why API gateways are required
- [ ] Rate limiting strategies
- [ ] Authentication at gateway level
- [ ] API Versioning strategies
- [ ] Service Discovery (client vs server side)


## Phase 3 - Scaling the Front Door

**Load Balancing**
- [ ] What is Load Balancing?
- [ ] L4 vs L7 Load Balancers
- [ ] Load balancing algorithms
- [ ] Sticky Sessions - pros & cons
- [ ] Health checks and failover

**Caching**
- [ ] What is caching and why it exists?
- [ ] Types of cache (client, CDN, server)
- [ ] Cache placement in system design
- [ ] Caching Strategies (aside/through/back)
- [ ] Cache Eviction Policies (LRU, LFU, FIFO)
- [ ] Cache invalidation - why it's hard
- [ ] Distributed Caching
- [ ] CDN (Content Delivery Network)
- [ ] Redis internal working (high level)


## Phase 4 - Data Layer

**Database Fundamentals**
- [ ] SQL vs NoSQL - when to use what?
- [ ] Database types (KV, document, wide-column, graph)
- [ ] ACID Transactions
- [ ] Database Indexes
- [ ] Consistent Hashing
- [ ] Bloom Filters

**Scaling Databases**
- [ ] Database Sharding
- [ ] Sharding vs Partitioning
- [ ] What happens when a shard fails?
- [ ] Data Replication
- [ ] Leader-follower vs Multi-leader replication
- [ ] Read replicas - how they work
- [ ] Database scaling (general)
- [ ] Database scaling mistakes
- [ ] Change Data Capture (CDC)


## Phase 5 - Async & Event-Driven Systems

**Messaging & Async Processing**
- [ ] Message Queues
- [ ] Pub/Sub vs Work Queues
- [ ] Kafka vs RabbitMQ (conceptual)
- [ ] Dead-letter queues
- [ ] Batch vs Stream Processing
- [ ] Event-Driven Architecture

**Advanced Data & Consistency Patterns**
- [ ] Event Sourcing
- [ ] CQRS
- [ ] Saga Pattern
- [ ] Two-Phase Commit


## Phase 6 - Distributed Systems Deep Dive

**Distributed Systems Core**
- [ ] Consensus Algorithms (Paxos vs Raft)
- [ ] Distributed Locking
- [ ] Gossip Protocol
- [ ] HeartBeats
- [ ] Geohashing

**Resiliency Patterns**
- [ ] Circuit Breaker
- [ ] Retry with exponential backoff
- [ ] Bulkhead pattern
- [ ] Disaster Recovery
- [ ] Multi-AZ deployment
- [ ] Chaos Engineering


## Phase 7 - Architectural Patterns

**System Architecture Styles**
- [ ] Client-Server Architecture
- [ ] Microservices Architecture
- [ ] Monolith vs Microservices tradeoffs
- [ ] Serverless Architecture
- [ ] Peer-to-Peer (P2P) Architecture
- [ ] Service Mesh
- [ ] gRPC


## Phase 8 - Security, Observability & Ops

**Security**
- [ ] Authentication vs Authorization
- [ ] OAuth 2.0 & JWT
- [ ] Encryption at rest vs in transit
- [ ] OWASP Top 10 (system design view)

**Observability**
- [ ] Metrics vs Logs vs Traces
- [ ] Distributed Tracing
- [ ] SLIs, SLOs, and SLAs
- [ ] Alerting and monitoring best practices

**Deployment & Infrastructure**
- [ ] Docker basics for backend engineers
- [ ] Kubernetes / Container Orchestration
- [ ] Blue-green vs Canary deployment
- [ ] Zero-downtime deployments
- [ ] AWS EC2, S3, VPC basics
- [ ] How cloud load balancing works


## Phase 9 - Modern (2025+) & Tradeoffs Capstone

**Modern System Design Concepts**
- [ ] Feature Flags
- [ ] Vector Databases
- [ ] Data Mesh
- [ ] Function-as-a-Service (Serverless deep dive)

**Tradeoffs Mastery (Capstone)**
- [ ] Top 15 System Design Tradeoffs
- [ ] Concurrency vs Parallelism
- [ ] Push vs Pull Architecture
- [ ] Stateful vs Stateless Design
- [ ] Read-Through vs Write-Through Cache
- [ ] Latency vs Throughput (recap)
