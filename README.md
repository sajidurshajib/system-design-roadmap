# ⚙️ System Design Roadmap [🔗](https://www.youtube.com/watch?v=CuQmQpvw04I&t=1s)

### [Type of system design:](https://dev.to/sajidurshajib/understanding-hld-and-lld-in-system-design-a-developers-guide-22j6)

1. HLD (High-level design) - Overview of the system
2. LLD (Low-level design) - Actual machine coding 

### [Requirements:](https://dev.to/sajidurshajib/functional-and-non-functional-requirements-explained-5gf9)

1. Functional requirements
2. Non-functional requirements (qualities)


### HLD steps:

1. **Fundamentals:**
   - Serverless and Serverful
   - Horizontal and vertical scaling 
   - [What are thread and process?](https://dev.to/sajidurshajib/thread-vs-process-in-a-nutshell-5bjp)
   - [What are pages?](https://dev.to/sajidurshajib/what-are-pages-in-osmemory-46gc)
   - How does the internet work? 
2. **Database:** 
   - [SQL vs NoSQL DBs](https://dev.to/sajidurshajib/when-to-use-nosql-and-sql-a1m) 
   - In-memory DBs
   - Data replication and Migration 
   - Data Partitioning 
   - Sharding 
3. **Consistency and Availability** 
   - Data consistency and level 
   - Isolation and its levels
   - [CAP Theorem](https://dev.to/sajidurshajib/understanding-the-cap-theorem-through-alices-distributed-adventure-pmp)
4. **Cache**
   -  What is Cache? (Redis, Memcached)
   -  Write policies: write back through and around. 
   -  Replacement policies: LFU, LRU, Segment LRU, etc
   -  Content Delivery Networks (CDNs)
5. **Networking** 
   - TCP vs UDP 
   - [What is HTTP (1/2/3) & HTTPS](https://blog.bytebytego.com/p/a-deep-dive-into-http-from-http-1)
   - What is RPC and gRPC
   - Web sockets
   - WebRTC & video streaming 
6. **Load Balancers**
   - Load Balancing Algorithms (Stateless and Stateful)
   - Consistent Hashing
   - [Proxy and Reverse proxy](https://dev.to/sajidurshajib/proxy-vs-reverse-proxy-explained-simply-with-alice-1oof)
   - Rate Limiting 
7. **Message Queues** 
   - Async processing (Kafka, RabbitMQ)
   - Publisher-Subscriber model
8. **Monoliths and Microservices** 
   - Why microservices?
   - Concept of ‘Single point failure’ 
   - Avoiding Cascading failure
   - Containerization (Docker)
   - Migrating to Microservices 
9. **Monitoring and Logging** 
   - Logging events and monitoring metrics 
   - Anomaly detection
10. **Security**
    - Tokens for auth 
    - SSO and 0Auth 
    - Access control list and rule engines
    - Encryption 
11. **System Design Tradeoffs** 
    - [Push vs Pull architecture](https://dev.to/sajidurshajib/push-vs-pull-architecture-whats-the-real-difference-48kc)
    - Consistency and Availability 
    - SQL vs NoSQL DBs 
    - Memory vs Latency 
    - Throughput vs Latency 
    - Accuracy vs Latency 
12. **Practice**
    - Youtube 
    - Twitter
    - Whatsapp 
    - Uber
    - Amazon 
    - Dropbox/Google Drive
    - Netflix 
    - Instagram 
    - Zoom 
    - Booking[dot]com / Arbnb
    
### LLD steps:

1. **Object Oriented Programming**
   - Encapsulation
   - Abstraction 
   - Inheritance 
   - Polymorphism 
   - [SOLID Principle](https://dev.to/sajidurshajib/5-pillars-of-solid-15gn)
2. **Design Patterns** 
   - Creational (Singleton, Factory, etc)
   - Structural (Proxy, Bridge, etc)
   - Behavioral (Strategy, Command, Observer, etc)
3. **Concurrency & Thread safety** 
   - Thread safe injection 
   - Locking mechanism 
   - producer-consumer 
   - race conditions and synchronization 
4. **UML diagram** 
5. **APIs**
   - API Design 
   - req/res object modeling 
   - versioning & extensibility 
   - Clean Code Principle: DRY, SRP, etc
   - Avoiding God classes
6. **Common LLD Problems** 
   - Design a Tic-tac-toe or chess game
   - Design a Splitwise game
   - Design a parking lot
   - Design an elevator system with multiple lifts 
   - Design a notification system 
   - Design a food delivery app 
   - Design a movie ticket booking system 
   - Design a URL shortener 
   - Design a Logging framework 
   - Design a rate limiter


### Others

1. **Database:**
   - [ACID - Database](https://dev.to/sajidurshajib/understanding-the-acid-properties-in-databases-m2i)