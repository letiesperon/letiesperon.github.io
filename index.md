# Software Architecture in Practice 

Temario de arquitectura de software en la práctica

# OBJETIVO DEL CURSO
Brindar conocimiento al alumno para que sea capaz de determinar y adaptar una arquitectura
factible y acorde para un sistema de software destinado para un número indeterminado de
usuarios dentro de un contexto cambiante.

---

## Module 1: Building SaaS applications in the Cloud

### Software Architecture 
* Definition
* Role of the architect
* Stakeholders of the architecture
* What is a "good" architecture?
* Overview of architecture types (monolith, layered, microservices)

## Virtualization
* Definition
* Virtual Machines
* Container
* Docker Workshop
  * Docker ecosystem overview
  * Docker concepts overview
  * Dockerfile
  * Volumes
  * Networks
  * Environment variables
  * Docker-compose

### Deployment Models
* On premise 
* Cloud (public, private and hybrid)

### Service Models 
* IaaS
* PaaS
* ...DaaS, FaaS, etc.
* SaaS

### Building SaaS applications
* Advantages for the customer and the company
* Added complexity 
* SaaS + Agile + High productivy frameworks = The perfect match
  
### Cloud Computing
* Definition
* Pros and cons
* Overview of Cloud Providers

### Amazon Web Services
* Advantages
* [AWS Infraestructure](https://docs.aws.amazon.com/): Regions, AZ, Datacenters
* AWS Educate overview
* [AWS Free Tier overview](https://aws.amazon.com/free/?all-free-tier.sort-by=item.additionalFields.SortRank&all-free-tier.sort-order=asc)
* AWS Services classifications
  * Global vs Region-specific
  * Managed vs Unmanaged
  * Managed: with vs without root access
* [AWS Services Overview](https://github.com/letiesperon/ASP-tutorials):
  * IAM 
  * EC2
  * RDS
  * ElastiCache
  * S3
  * Elastic Beanstalk
  * ECS
  * Cloudwatchd
  * Cost explorer

### Twelve-Factor Application
* Deep dive into the [12 factors](http://12factor.net/) with practical examples

### Availability in SaaS

### Scalability in SaaS

### Tenancy in SaaS
* Multi tenant app with multi tenant DB
* Multi tenant app with single tenant DB
* Single tenant app with single tenant DB

### Security in SaaS
* Authentication and authorization patterns (cookie-based, opaque token, JWT, etc)
* Security best practices (encrypting, hashing, https, logs considerations, auditing, MFA, Force Update, etc)
* Security in AWS (VPC, ACLs, Security Groups)

### Observability in SaaS
* APMs overview
* Logging best practices (levels, structured logging, distributed tracing, etc)
* Advanced logging infra example: Logstash + ElasticSearch

### Performance in SaaS
* Caching:
  * Client-side
  * DNS
  * Web server
  * Application
  * Database
* Long Running Tasks:
 * Background Jobs
 * Asynchronous Transactions
 * Good practices for long running tasks (queue availability, idempotency, reentrancy, orderless, dead letter queue, etc). 
* Performance Testing:
  * Frontend testing
  * Backend Testing
  * Types of backend Performance Tests (load, stress, endurance, volume, spike, scalability)
  * JMeter workshop
* Analyzing performance tests results:
  * Client rendering time, Network time, queue time, app time, DB time
  * Common issues and how to approach them

### Deployment Strategies
* Rolling
* Blue/Green
* Canary
* A/B

### Culture of Automation
* Continuous Integration
* Continuous Deployment 
* Continuous Delivery
* Branching strategies
* DevOps culture
* Good organizational practices to adopt DevOps
* Metrics for Engineering Efficiency 

---

## Module 2: Microservices architecture
