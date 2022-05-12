## Design Patterns and Anti-Patterns in Microservices Architecture: A Classification Proposal and Study on Open-Source Projects

For my graduation thesis at Politecnico Di Milano Computer Science and Engineering Master of Science programme, I worked with Prof. Elisabetta Di Nitto and explored **design patterns and anti-patterns in microservices architecture**, to name a few:

- API Gateway
- Asychronous Messaging
- Command-Query Responsability Segregation (CQRS)
- Containers and Orchestration
- Health Check
- Distributed Tracing

Specifically, I **analyzed current classifications** of microservices design patterns and anti-patterns, then **proposed a classification** that involves both kinds of items. As a connection between the "theory" and practice, I **inspected 10 popular open source microservices applications to observe whether these patterns and anti-patterns actually exist** in practical cases.

Because of the use of different technologies in different microservices applications, I have learned about technologies such as **Docker and Kubernetes**, and familiarised myself with distributed systems technologies including:

- Various API Schemes: RESTful HTTP, gRPC, GraphQL
- Message Brokers: RabbitMQ, Kafka
- Service Registry & Discovery: Kubernetes, Eureka and Config (Spring Cloud)
- API Gateways: Zuul (Spring Cloud), Ocelot (.NET)
- Proxies: Envoy, Dapr, Tye
- Service Meshes: Istio, Linkerd
- Orchestration: some Kubernetes Objects (Pods, Deployments, Services, Secrets), Helm charts
- Tracing: Jaeger, Zipkin

Other more general frameworks and tools I have learned about include:

- Backend stack: Node.js, .NET, Spring, Spring Boot, Go
- Databases and ORMs: Entity Framework, MartenDB (PostgreSQL)
- CI/CD: Github Actions, Travis CI, CircleCI, Codecov

All thesis-related artifacts can be found below:

- [Executive Summary](Artifacts/Executive_Summary_2022_04_ESAS.pdf)
- [Full Thesis Text](Artifacts/2022_04_ESAS.pdf)
- [Presentation](Artifacts/microservices%20thesis%20presentation.pdf)
