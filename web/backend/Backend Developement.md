# Backend Development

This can be found in roadmap form
at [NavigoLearn.com](https://navigolearn.com/roadmap/backend-developement-28)

## Description

This is a roadmap
that gives an overview of the key concepts and technologies
you need to know to become a Backend Developer.
It is not tied to a specific programming language
which makes it a versatile guide.

**Backend Development Intro**: This section covers the basics.
What is a server, a protocol and the internet works.
It also discusses the roles, responsibilities,
and common technologies that backend developers use.

**Server-side Programming**: Here you'll pick a programming language to work
with and understand basic data structures of the chosen language.

**Databases**: You’ll learn about different types of DBMS's (Database Management
Systems) like SQL, NoSQL and ORMs for database interaction.

**APIs**: This section discusses the different types of APIs such as RESTful
API, GraphQL API, etc.

**Authentication & Authorization**: It covers the theories of authentication and
authorization as well as various techniques such as Session Authentication, JSON
Web Tokens (JWT), OAuth, and OpenID Connect.

**Caching**: Here you'll learn about caching to enhance performance.

**Containerization**: Covers technologies like Docker, Kubernetes for
containerizing applications making them scalable and manageable.

**Cloud Providers**: Provides an overview of major cloud service providers.

**Backend Architectures**: Covers the popular architectural models used in
backend development.

**Testing**: Discusses various types of testing as well as popular testing
frameworks, and various testing methodologies.

**Logging and Monitoring**: Covers various aspects of monitoring an application
from log management and network monitoring to performance and security
monitoring.

**CI/CD**: Covers the basics of Continuous Integration and Continuous
Deployment, including the best practices and tools for both.

**Rate Limiting and Throttling**: Discusses the techniques and libraries for
rate limiting and throttling to ensure fair usage of limited resources.

This path should give you a broad understanding of backend development.
Please remember this is a guide and not a strict rulebook.
Backend development is vast,
and this roadmap provides a way
to navigate through resources available to the best of author's knowledge.
Be sure to take each section at your own pace, even out of order if you wish.
Ensuring you understand each concept thoroughly.

## Table of contents

1. **Backend Development Intro**
    1. What is a server?
    2. What is a protocol?
    3. How the internet works?
    4. Pentagon Backend (What/When/Where/Why/How)
        1. Role of a Backend Developer
        2. Common Backend Technologies
2. **Server-side Programming**
    1. Choose a language
    2. Basic Data Structures
3. **Databases**
    1. SQL
        1. SQL Injections
    2. NoSQL
        1. MongoDB
        2. Redis
        3. Cassandra
    3. ORMs
4. **APIs (Application Programming Interfaces)**
    1. Types of APIs
        1. RESTful APIs
            1. HTTP Methods
            2. RESTful API Design
            3. RESTful API Best Practices
        2. GraphQL APIs
        3. ProtoBuf
    2. Websockets & Real-time Communication (WS/WSS)
    3. API Security
5. **Authentication & Authorization**
    1. Understanding Authentication
    2. Understanding Authorization
    3. Authentication Techniques
        1. Session Authentication
        2. JSON Web Tokens (JWT)
        3. OAuth
        4. OpenID Connect
6. **Caching**
    1. Types of caching
        1. In-Memory Caching
        2. HTTP Caching
        3. Database Query Caching
    2. Cache Invalidation
    3. Cache Best Practices
7. **Containerization**
    1. Docker
        1. Kubernetes
        2. Docker Swarm
        3. Apache Mesos
        4. Helm
    2. LXD
    3. Podman
    4. Containerd
8. **Cloud Providers**
9. **Backend Architectures**
    1. Monolithic
    2. Microservices
    3. Serverless
    4. Service-Oriented Architecture (SOA)
10. **Testing**
    1. Types of testing
    2. Testing frameworks
        1. Node.js
        2. Python
        3. Go
        4. PHP
        5. Kotlin
    3. Testing Methodologies
        1. Test Driven Development (TDD)
        2. Behavior Driven Development (BDD)
        3. Exploratory Testing
        4. Stress Testing
        5. Security Testing
11. **Logging and Monitoring**
    1. Application Monitoring
        1. Log Management
        2. Infrastructure Monitoring
        3. Network Monitoring
        4. Security Monitoring
        5. Performance Monitoring
    2. Tools for Logging and Monitoring
12. **CI/CD (Continuous Integration / Continuous Deployment)**
    1. Basics of CI (Continuous Integration)
    2. Tools for CI
        1. Jenkins
        2. TravisCI
        3. CircleCI
        4. GitHub Actions
    3. Basics of CD (Continuous Deployment)
    4. Tools for CD
        1. Jenkins
        2. AWS CodeDeploy
        3. Google Cloud Deployment Manager
        4. Heroku
    5. CI/CD Best Practices
13. **Rate Limiting and Throttling**
    1. Rate Limiting Techniques
        1. Fixed Window Counter
        2. Sliding Window Log
        3. Token Bucket
        4. Leaky Bucket
    2. Libraries for Rate Limiting
        1. Node.js
        2. Python
        3. Go
        4. Kotlin

### Essential Prerequisites

* Basics of computer science
    * You should have a basic understanding of how computers work.
      This includes things like how memory works, how the CPU works, etc.
      You don't need to know everything, but you should have a basic
      understanding of how computers work.

### Recommended Prerequisites

* Git and GitHub
    * For collaboration and version control and to get familiar with the
      development workflow.
* Data Structures and Algorithms
    * I go into this a bit in this roadmap.
    * Understanding of data structures and algorithms is essential for backend
      development.
      You don't need to know every algorithm under the
      sun, but you should have a basic algorithmic foundation.
* Servers and HTTP/HTTPS
    * I go into this a bit in this roadmap.
    * It's important to know a bit about how http works and how servers work.
      This will help you understand how to build applications that work on the
      internet.
* Basic frontend technologies
    * Technologies such as HTML, CSS and a little bit of JavaScript
    * You don't need to be an expert, you need to know this to properly
      communicate with frontend developers
      and to understand how the frontend and backend work together.

1. **Backend Development Intro**
    - This section contains information on what you need to know to get started
      with backend development. You don't need to know everything in this
      subtree to get started, but it's important to have a basic understanding
      of the concepts listed here, so you can talk to people and get help if you
      get stuck working on a project.
    - [Learn web development as an absolute beginner](https://www.youtube.com/watch?v=ysEN5RaKOlA) -
      Coder Coder
    - 1.A What is a server?
        - It's important to understand the concept of what a server is and how
          it works. This will help you understand how anything on the internet
          works. You may already have a vague idea if you're a gamer, but could
          you really define what a server is?
        - [What is a Server? (Deepdive) - Video](https://www.youtube.com/watch?v=VXmvM2QtuMU) -
          LiveOverflow
        - [What is a Server? - Article](https://www.geeksforgeeks.org/what-is-server/) -
          GeekforGeeks
    - 1.B What is a protocol?
        - Protocols are the rules that govern how computers communicate with
          each other. You should have a basic understanding of what a protocol
          is and how it works to avoid headaches ahead.
        - [What is a protocol? - Video](https://www.youtube.com/watch?v=fK7oAc_V-Kk) -
          Internet-class
        - [What is a Protocol? (Deepdive) - Video](https://www.youtube.com/watch?v=d-zn-wv4Di8) -
          LiveOverflow
        - [Why are protocols so highly structured? - Video](https://www.youtube.com/watch?v=1M1FqYrapCM) -
          Internet-class
        - [What is a protocol? | Network protocol definition - Article](https://www.cloudflare.com/learning/network-layer/what-is-a-protocol/) -
          CloudFlare
    - 1.C How the internet works?
        - Do you have any idea how the internet works? If not, you should
          probably learn. It might not be complicated as you might think.
        - [Computer Networking in 100 Seconds - Video](https://www.youtube.com/watch?v=keeqnciDVOo) -
          Fireship
        - [The Two Generals’ Problem - Video](https://www.youtube.com/watch?v=IP-rGJKSZ3s) -
          Tom Scott
        - [The Http and the Web | Http Explained | Request-Response Cycle - Video](https://www.youtube.com/watch?v=eesqK59rhGA) -
          The TechCave
        - [Hypertext Transfer Protocol (HTTP) - Article](https://www.extrahop.com/resources/protocols/http/) -
          ExtraHop
    - 1.D Pentagon Backend (What/When/Where/Why/How)
        - Why do you want to learn backend development?
          What value does it add?
          What problems does it solve?
          These are all questions you should ask
          yourself before you start learning backend development.
        - 1.DA Role of a Backend Developer
            - What does a backend developer do?
              What are their responsibilities?
            - [Backend Development explained in 2 minutes - Video](https://www.youtube.com/watch?v=cbSrsYiRamo) -
              mayuko
            - [What does a back-end developer do? - Article](https://business.linkedin.com/talent-solutions/resources/how-to-hire-guides/back-end-developer/job-description#:~:text=Backend%20developer%20responsibilities%20include%20creating,taking%20place%20behind%20the%20scenes.) -
              LinkedIn
        - 1.DB Common Backend Technologies
            - What technologies do backend developers use?
              What skills do they need?
            - A list of things that are commonly used in backend development.
              And most of what you'll be learning in this roadmap.
            - Languages & Frameworks
                - Be it Express, Django or any other framework, the easiest way
                  to get started with backend development is to use a framework.
                  Frameworks are a collection of libraries and tools that make
                  it easier to build applications by abstracting away the
                  complexity of the underlying technologies.
            - Databases & ORMs
                - Databases are used to store data. There are many different
                  types of databases, but the most common ones are relational
                  databases like MySQL, PostgreSQL, etc. and NoSQL databases
                  like MongoDB, Redis, etc. ORMs are used to interact with
                  databases. They allow you to write code instead of SQL queries
                  to interact with the database.
            - APIs & communication Protocols
                - APIs are used to communicate between different applications.
                  They allow you to send and receive data between applications.
                  There are many different types of APIs, but the most common
                  ones are REST APIs, GraphQL APIs, and WebSockets.
            - Caching
                - Caching is used to store data in memory so that it can be
                  accessed faster. It's used to improve the performance of
                  applications by reducing the number of times data needs to be
                  fetched from the database or other external sources.
            - Identity & Access
                - Authentication is used to verify that a user is who they say
                  they are. Authorization is used to determine what a user can
                  and cannot do. This can be done using a variety of different
                  methods, but the most common ones are JWTs and OAuth.
            - Containerization
                - Containerization is used to package applications into
                  containers so that they can be run on any machine without
                  having to worry about dependencies or other external factors.
                  The most common containerization tool is Docker.
            - Cloud Providers
                - Cloud providers are used to host applications in the cloud.
                  They provide a variety of different services, but the most
                  common ones are storage, compute, and networking. The most
                  popular cloud providers are AWS, Azure, GCP and DigitalOcean.

2. **Server-side Programming**
    - Server-side programming is the backbone of backend development, where the
      magic happens behind the scenes.
      In this realm, developers wield
      programming languages like JavaScript, Python, Go, PHP, Ruby, and others
      to build applications that run on remote servers rather than your device
      or browser.
    - 2.A Choose a language
        - It's encouraged to pick a language and stick to it while starting out.
          It's less about which one you choose and more about learning to think
          like a programmer. Below are a few short videos of languages that are
          commonly used in backend development.
        - [JavaScript in 100 seconds - Video](https://www.youtube.com/watch?v=DHjqpvDnNGE) -
          Fireship
        - [Python in 100 seconds - Video](https://www.youtube.com/watch?v=x7X9w_GIm1s) -
          Fireship
        - [Go in 100 seconds - Video](https://www.youtube.com/watch?v=446E-r0rXHI) -
          Fireship
        - [PHP in 100 seconds - Video](https://www.youtube.com/watch?v=a7_WFUlFS94) -
          Fireship
        - [Kotlin in 100 seconds - Video](https://www.youtube.com/watch?v=xT8oP0wy-A0) -
          Fireship
    - 2.B Basic Data Structures
        - Understand the basics of arrays, strings, linked lists, stacks,
          queues, trees, and hash tables. You don't need to know how to
          implement them, but you should know how they work and when to use
          them.
        - [10 Key Data Structures We Use Every Day - Video](https://www.youtube.com/watch?v=ouipSd_5ivQ) -
          ByteByteGo
        - [Algorithms and Data Structures Tutorial — Full Course for Beginners - Video](https://www.youtube.com/watch?v=8hly31xKli0) -
          freeBootCamp.org

3. **Databases**
    - The world of databases is a fundamental pillar of backend development.
      It's where your application's data is stored, retrieved, and managed.
      SQL databases are the most common type of database, but there are many
      other types of databases as well.
    - 3.A SQL
        - SQL is a language used to interact with relational databases. It's
          used to create, read, update, and delete data from databases. It's one
          of the most common languages used in backend development.
        - [SQL in 100 seconds - Video](https://www.youtube.com/watch?v=zsjvFFKOm3c) -
          Fireship
        - [Learn SQL In 60 Minutes - Video](https://www.youtube.com/watch?v=p3qvj9hO_Bo) -
          freeCodeCamp.org
        - [SQL Tutorial — Web Tutorial](https://www.w3schools.com/sql/default.asp) -
          W3Schools
        - 3.AA SQL Injections
            - SQL injections are one of the most common security vulnerabilities
              in web applications. They allow attackers to execute arbitrary SQL
              queries on the database. You should know how to prevent them.
            - [SQL Injections are scary!! (hacking tutorial for beginners) -
              Video](https://www.youtube.com/watch?v=2OPVViV-GQk) -
              NetworkChuck
            - [SQL Injection Prevention Cheat Sheet - Article](https://cheatsheetseries.owasp.org/cheatsheets/SQL_Injection_Prevention_Cheat_Sheet.html) -
              OWASP Cheat Sheet
    - 3.B NoSQL
        - NoSQL databases are used to store unstructured data. They're often
          used in conjunction with relational databases to store data that
          doesn't fit into the relational model. They're also used to store data
          that needs to be accessed quickly.
        - [What Is a NoSQL Database? | NoSQL Explained - Video](https://www.youtube.com/watch?v=f8t3Hh1RxVA) -
          IBM Developer
        - [SQL vs. NoSQL Explained (in 4 Minutes) - Video](https://www.youtube.com/watch?v=_Ss42Vb1SU4) -
          Exponent
        - [Which Is Better? SQL vs NoSQL - Video](https://www.youtube.com/watch?v=t0GlGbtMTio) -
          Web Dev Simplified
            - 3.BA MongoDB
                - MongoDB is a document-oriented database. It's one of the most
                  popular NoSQL databases. It's used to store data in JSON-like
                  documents.
                - [MongoDB in 100 seconds - Video](https://www.youtube.com/watch?v=-bt_y4Loofg) -
                  Fireship
                - [MongoDB Crash Course - Video](https://www.youtube.com/watch?v=ofme2o29ngU) -
                  Web Dev Simplified
                - [MongoDB Tutorial - Web Tutorial](https://www.w3schools.com/nodejs/nodejs_mongodb.asp) -
                  W3Schools
            - 3.BB Redis
                - Redis is an in-memory data store. It's used to store data in
                  key-value pairs. It's often used to store session data or
                  cache data.
                - [Redis in 100 seconds - Video](https://www.youtube.com/watch?v=G1rOthIU-uo) -
                  Fireship
                - [Redis Crash Course - Video](https://www.youtube.com/watch?v=jgpVdJB2sKQ) -
                  Web Dev Simplified
                - [Getting started with Redis - Documentation](https://redis.io/docs/getting-started/) -
                  Redis
            - 3.BC Cassandra
                - Cassandra is a distributed database. It's used to store data
                  in a distributed fashion. It's often used to store data that
                  needs to be accessed quickly.
                - [Cassandra in 100 seconds - Video](https://www.youtube.com/watch?v=ziq7FUKpCS8) -
                  Fireship
                - [Apache Cassandra Database – Full Course for Beginners - Video](https://www.youtube.com/watch?v=J-cSy5MeMOA) -
                  freeCodeCamp.org
                - [Cassandra Documentation - Getting Started - Documentation](https://cassandra.apache.org/doc/latest/cassandra/getting_started/index.html) -
                  Apache Cassandra
    - 3.C ORMs
        - ORMs are used to interact with databases. They allow you to write code
          instead of SQL queries to interact with the database. They're often
          used in conjunction with relational databases to make it easier to
          work with them.
        - [ORM: The Good, the Great, and the Ugly - Video](https://www.youtube.com/watch?v=3EvhK7-DlZA) -
          Coding Tech
        - [What is an ORM? - Article](https://www.prisma.io/dataguide/types/relational/what-is-an-orm) -
          Prisma
        - [What is an ORM – The Meaning of Object Relational Mapping Database Tools - Article](https://www.freecodecamp.org/news/what-is-an-orm-the-meaning-of-object-relational-mapping-database-tools/) -
          freeCodeCamp.org

4. **APIs (Application Programming Interfaces)**
    - An API is a set of definitions and protocols that allows applications
      to communicate with each other.
      It's a way for different software
      applications to interact with each other.
      Get familiar with what APIs
      are and why they are important.
    - [APIs Explained (in 4 Minutes) -
      Video](https://www.youtube.com/watch?v=bxuYDT-BWaI) -
      Exponent
    - [What is an API and what does it do -
      Article](https://blog.openapihub.com/en-us/what-is-an-api-and-what-does-it-do/) -
      Open API Hub
    - 4.A Types of APIs
        - There are several types of APIs including REST, SOAP (mostly useless
          in modern applications), and GraphQL. Each has its own uses,
          advantages and disadvantages. Understand them and decide which one
          suits your needs best.
        - 4.AA RESTful APIs
            - REST stands for REpresentational State Transfer. It is an
              architectural style for creating web services. RESTful APIs are
              built using HTTP methods like GET, POST, PUT, DELETE, etc.
            - [RESTful APIs in 100 Seconds // Build an API from Scratch with Node.js Express - Video](https://www.youtube.com/watch?v=-MTSQjw5DrM) -
              Fireship
            - [REST API concepts and examples - Video](https://www.youtube.com/watch?v=7YcW25PHnAA) -
              WebConcepts
            - [Representational state transfer (REST) and Simple Object Access Protocol (SOAP) - Article](https://www.ibm.com/cloud/learn/rest-apis) -
              IBM Cloud
            - 4.AAA HTTP Methods
                - HTTP methods are used to perform different actions on
                  resources. They're used to create, read, update, and delete
                  data from databases. They're also used to perform other
                  actions like sending emails, uploading files, etc.
                - [HTTP/1 to HTTP/2 to HTTP/3 - Video](https://www.youtube.com/watch?v=a-sBfyiXysI) -
                  WebConcepts
                - [HTTP Methods -
                  Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods) -
                  MDN Web Docs
                - [HTTP response status codes - Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status) -
                  MDN Web Docs
            - 4.AAB RESTful API Design
                - RESTful APIs are designed using a set of principles called
                  RESTful design principles. These principles are used to design
                  APIs that are easy to use and understand. They're also used to
                  design APIs that are easy to maintain and extend.
                - [REST Tutorial - How to Design a Good RESTful API - Video](https://www.youtube.com/watch?v=sMKsmZbpyjE) -
                  Grace Hopper Academy
                - [RESTful API Design — Step By Step Guide - Article](https://betterprogramming.pub/restful-api-design-step-by-step-guide-2f2c9f9fcdbf) -
                  Better Programming
            - 4.AAC RESTful API Best Practices
                - RESTful APIs are designed using a set of principles called
                  RESTful design principles. These principles are used to design
                  APIs that are easy to use and understand. They're also used to
                  design APIs that are easy to maintain and extend.
                - [Rest API - Best Practices - Design - Video](https://www.youtube.com/watch?v=1Wl-rtew1_E) -
                  High-Performance Programming
                - [What Is Idempotence? - Article](https://www.restapitutorial.com/lessons/idempotency.html) -
                  REST API Tutorial
        - 4.AB GraphQL APIs
            - GraphQL is a query language for APIs and a runtime for executing
              those queries with your existing data.
            - [GraphQL In 100 Seconds - Video](https://www.youtube.com/watch?v=eIQh02xuVw4) -
              Fireship
            - [Learn GraphQL In 40 Minutes - Video](https://www.youtube.com/watch?v=ZQL7tL2S0oQ) -
              freeCodeCamp.org
            - [GraphQL is the better REST - Article](https://www.howtographql.com/basics/1-graphql-is-the-better-rest/) -
              HowToGraphQL
        - 4.AC ProtoBuf - https://protobuf.dev
    - 4.B Websockets & Real-time Communication (WS/WSS)
        - WebSockets provide a bidirectional,
          full-duplex communications protocol over a single TCP connection for
          real-time data transfer between the client and the server.
          This is one of the newer technologies in the backend development
          and support used to be spotty, but it's well-supported nowadays.
        - [WebSockets in 100 Seconds -
          Video](https://www.youtube.com/watch?v=1BfCnjr_Vjg) -
          Fireship
        - [A Beginner's guide to WebSockets -
          Video](https://www.youtube.com/watch?v=8ARodQ4Wlf4) -
          freeCodeCamp.org
        - [WebSockets -
          Article](https://developer.mozilla.org/en-US/docs/Web/API/WebSockets_API) -
          MDN Web Docs
        - [10 Websocket Best Practices -
          Article](https://climbtheladder.com/10-websocket-best-practices/) -
          Climb the Ladder
        - [WebSocket Cheat Sheet -
          Article](https://websockets.readthedocs.io/en/stable/howto/cheatsheet.html) -
          Read the Docs
    - 4.C API Security
        - Understanding how to secure your APIs is essential as they are one of
          the most common attack vectors used by malicious actors.
        - [API Security Cheat Sheet - Article](https://cheatsheetseries.owasp.org/cheatsheets/REST_Security_Cheat_Sheet.html) -
          OWASP Cheat Sheet
        - [API Security - Article](https://www.redhat.com/en/topics/security/api-security) -
          Red Hat
        - [WebSocket Security Cheat Sheet -
          Article](https://cheatsheetseries.owasp.org/cheatsheets/HTML5_Security_Cheat_Sheet.html#websockets) -
          OWASP Cheat Sheet

5. **Authentication & Authorization**
    - Authentication and Authorization are critical processes in securing your
      application.
    - Both processes work together: authentication confirms that users are who
      they say they are, and authorization gives those users permissions to
      access resources.
    - It is crucial to understand the difference between the two and how they
      are implemented in web development.
    - [Authentication vs Authorization -
      Video](https://www.youtube.com/watch?v=HCy0e3rd15A) -
      Coding With Chaim
    - [Authentication vs. Authorization: What's the Difference? -
      Article](https://axiomatics.com/news/press-releases/cso-online-feature-why-you-need-both-authorization-and-authentication) -
      CSO
    - [What’s the difference between authentication and authorization? -
      Article](https://www.ibm.com/cloud/learn/authentication-vs-authorization) -
      IBM Cloud
    - 5.A Understanding Authentication
        - Authentication is the process of verifying the identity of a user,
          device, or system.
          It often involves validating credentials like username and password.
        - ["Basic Authentication" in Five Minutes - Video](https://www.youtube.com/watch?v=rhi1eIjSbvk) -
          OktaDev
        - [Introduction to Web Authentication: The New W3C Spec -
          Article](https://auth0.com/blog/introduction-to-web-authentication/) -
          Auth0
    - 5.B Understanding Authorization
        - Authorization is the process of giving someone permission to do or
          have something.
          In multi-user systems, a system administrator defines
          for the system which users are allowed access to the system and what
          privileges of use.
    - 5.C Authentication Techniques
        - Modern applications use techniques like session, JSON Web Tokens
          (JWT), OAuth,
          and OpenID for authentication and authorization.
        - [Session vs Token Authentication in 100 Seconds -
          Video](https://www.youtube.com/watch?v=UBUNrFtufWo) -
          Fireship
        - [Web API Security | Basic Auth, OAuth,
          OpenID Connect, Scopes & Refresh Tokens -
          Video](https://www.youtube.com/watch?v=x6jUDfpESmA) -
          Ambient Coder
        - 5.CA Session Authentication
            - Session authentication is a technique that uses cookies to store
              session information on the client side.
              It's used to authenticate
              users and prevent unauthorized access to resources.
            - [How does a web session work -
              Video](https://www.youtube.com/watch?v=zU7aqCA0u7Q) -
              Placement Mentor
            - [Sessions - Article](https://auth0.com/docs/manage-users/sessions) -
              Auth0
        - 5.CB JSON Web Tokens (JWT)
            - JSON Web Tokens is an open standard for securely transmitting
              information between parties as a JSON object.
            - [JWT Authentication Tutorial - Node.js -
              Video](https://www.youtube.com/watch?v=mbsmsi7l3r4) -
              Web Dev Simplified
            - [Don’t Use JWT for Login Sessions -
              Short Video](https://www.youtube.com/shorts/lkcSjV92ZPI) -
              Coding in Flow
            - [Implementing JWT Authentication in Node.js/Golang -
              Article](https://www.sohamkamani.com/categories/jwt/) -
              Soham Kamani
        - 5.CC OAuth
            - OAuth 2.0 is the modern protocol for creating and managing
              authorization between applications.
            - [OAuth 2.0 - An Overview - Video](https://www.youtube.com/watch?v=CPbvxxslDTU) -
              InterSystems Learning Services
            - [Demystifying OAuth: Enabling Secure and Seamless User Authentication -
              Article](https://www.linkedin.com/pulse/demystifying-oauth-enabling-secure-seamless-user-kevin-c-/) -
              Kevin C. on LinkedIn
            - [OAuth 2.0 and OpenID Connect (in plain English) -
              Video](https://www.youtube.com/watch?v=996OiexHze0)
              OktaDev
            - [OAuth 2.0 - Article](https://oauth.net/2/) - OAuth
        - 5.CD OpenID Connect
            - OpenID Connect is an identity layer on top of the OAuth 2.0
              protocol, which allows clients to verify the identity of the
              end-user based on the authentication performed by an authorization
              server.
            - [How OpenID Connect Works -
              Article](https://openid.net/developers/how-connect-works/) -
              OpenID

<details>
  <summary><b>Checkpoint</b>: You should now have a basic understanding of backend - Front-end developer level</summary>

You should be able
to use backend APIs at this point
to integrate them into your frontend applications.

You should also be able to build simple backend applications.

Project ideas:

- To Do List app (REST API)
    1. Add Task
    2. Edit Task
    3. View Task
    4. Delete Task
    5. Mark Task as Done
    6. What else can you think of?
- Simple Blog app (REST API)
    1. Add Post
    2. Edit Post
    3. Fetch Post
    4. Delete Post
    5. Search Post? — Database focused task
    6. What else can you think of?
- Simple Chat App (WebSockets + REST)
    1. Send Message
    2. Receive Messages
    3. Delete Message
    4. Search Message history? — Database focused task
    5. What else can you think of?
- E-commerce App (REST API)
    1. Add Product
    2. Edit Product
    3. Fetch Product
    4. Delete Product
    5. Search Product? — Database focused task
    6. What else can you think of?

</details>

6. **Caching** -
    - Fair warning this section has a lot of text articles and not many videos.
    - Caching is the process of storing copies of files or data in a cache,
      or a temporary storage location, so that they can be accessed more
      quickly.
      Databases, web pages, and other objects can be cached in
      response to repeated requests for the same data.
    - [Caching -
      Simply Explained - Video](https://www.youtube.com/watch?v=6FyXURRVmR0) -
      Simply Explained
    - [Caching Overview - Article](https://aws.amazon.com/caching/) - Amazon Web
      Services
    - 6.A Types of caching
        - There are several types of caching that you could use depending on
          your needs, such as in-memory caching (like Memcached or Redis), HTTP
          caching, database query caching, etc.
            - 6.AA In-Memory Caching
                - Here is where you store data in memory, so that it can be
                  accessed faster. It's used to improve the performance of
                  applications by reducing the number of times data needs to be
                  fetched from the database or other external sources. We talked
                  about this in the Redis node. Another example of in-memory
                  caching is Memcached.
                - [Cache Memory Explained - Video](https://www.youtube.com/watch?v=Zr8WKIOIKsk) -
                  ALL ABOUT ELECTRONICS
                - [Redis Caching in Node.js - Video](https://www.youtube.com/watch?v=oaJq1mQ3dFI) -
                  Traversy Media
            - 6.AB HTTP Caching
                - HTTP caching refers to the practice of storing copies of web
                  resources in a cache close to the user for faster access.
                  The browser storage, service workers and proxies can serve as
                  HTTP caches.
                  This improves the performance and efficiency of web
                  applications by reducing the load on the server.
                - [Caching - Article](https://web.dev/learn/pwa/caching/) -
                  Google
                  Developers
                - [HTTP Caching -
                  Article](https://developer.mozilla.org/en-US/docs/Web/HTTP/Caching) -
                  MDN Web Docs
            - 6.AC Database Query Caching
                - Database query caching is a technique to boost the performance
                  of your application by storing the result set of a query in
                  cache.
                  When the same query is executed again, the DBMS can
                  return the result from cache instead of executing the query
                  again.
                  This can dramatically reduce the load on the database
                  and speed up query results.
                - [Caching Slow Database Queries with Node.js and Redis -
                  Video](https://www.youtube.com/watch?v=krSgKN-5DHs) -
                  Redis
                - [Boost Your Node.js Application Performance with Redis Caching -
                  Article](https://codedamn.com/news/backend/nodejs-application-performance-redis-caching) -
                  codedamn
    - 6.B Cache Invalidation
        - Cache invalidation is a process in a computer system where entries in
          a cache are replaced or removed.
        - [Cashing with Caching - Article](https://itnext.io/cashing-with-caching-b839d8c13d24#:~:text=Don%E2%80%99t%20forget%20to,a%20version%20number.) -
          ITNEXT
        - [What Is Cache Invalidation - Blog](https://docs.pantheon.io/guides/frontend-performance/caching) -
          Pantheon
    - 6.C Caching Best Practices
        - Caching needs to be implemented carefully as improper caching can lead
          to users being served stale or inappropriate data. There are several
          best practices to follow when implementing caching.
        - [Principles of Cache Design in Web Application - Article](https://medium.com/@philipfeng/principles-of-cache-design-in-web-application-5f52209eb4b) -
          Philip Feng Ph.D. on Medium

7. **Containerization**
    - Containerization is a method of using operating systems' virtualization
      features to run applications and services in resource-isolated processes.
      Containers bundle an application together with all related configurations,
      libraries, and files necessary to run.
      This ensures the application works in
      any environment.
      Docker is one of the most popular tools for creating and
      managing containers.
    - [Never install locally - Video](https://www.youtube.com/watch?v=J0NuOlA2xDc) -
      Coderized
    - [7 Cases When You Should Not Use Docker -
      Article](https://www.freecodecamp.org/news/7-cases-when-not-to-use-docker/) -
      freeCodeCamp.org
    - 7.A Docker
        - Docker is an open-source platform that uses OS-level virtualization to
          deliver software in packages called containers.
          Containers are isolated from each other and bundle their own software,
          libraries, and configuration files;
          they can communicate with each other through well-defined channels.
          By containerizing the application platform and
          its dependencies, differences in OS distributions and underlying
          infrastructure are abstracted away, making the application more
          portable and secure.
          Docker is widely used in continuous integration
          and continuous deployment (CI/CD) workflows and in conjunction with
          orchestration tools like Kubernetes.
        - [Docker in 100 Seconds - Video](https://www.youtube.com/watch?v=Gjnup-PuquQ) -
          Fireship
        - [Learn Docker in 7 Easy Steps — Full Beginner's Tutorial - Video](https://www.youtube.com/watch?v=gAkwW2tuIqE) -
          Fireship
        - [Docker Tutorial for Beginners — A Full DevOps Course on How to Run Applications in Containers - Video](https://www.youtube.com/watch?v=fqMOX6JJhGo) -
          freeCodeCamp.org
        - 7.AA Kubernetes
            - Kubernetes (also known as K8s) is a portable, extensible,
              open-source platform for managing containerized workloads and
              services. It facilitates both declarative configuration and
              automation of applications. It has become a standard in the
              cloud-native world and is largely adopted for managing
              microservices-based architectures.
            - [Kubernetes Explained in 100 Seconds - Video](https://www.youtube.com/watch?v=PziYflu8cB8) -
              Fireship
            - [What is Kubernetes | Kubernetes explained in 15 mins - Video](https://www.youtube.com/watch?v=VnvRFRk_51k) -
              TechWorld with Nana
            - [An Introduction to Kubernetes - Article](https://cloud.google.com/kubernetes-engine/docs/concepts/kubernetes-engine-overview) -
              Google Cloud Documentation
            - [Kubernetes Security Cheat Sheet -
              Article](https://cheatsheetseries.owasp.org/cheatsheets/Kubernetes_Security_Cheat_Sheet.html) -
              OWASP Cheat Sheet
        - 7.AB Docker Swarm
            - Docker Swarm is native clustering and orchestration for Docker. It
              turns a pool of Docker hosts into a single, virtual Docker host.
              It's easy to use and preferred by developers and system
              administrators who are already familiar with Docker.
            - [What is Docker Swarm? - Video](https://www.youtube.com/watch?v=x843GyFRIIY) -
              TechWorld with Nana
            - [Docker swarm beginner tutorial - Video](https://www.youtube.com/watch?v=a6EMe5c2OL0) -
              DevOps Directive
            - [Docker Swarm Introduction - Article](https://docs.docker.com/engine/swarm/) -
              Docker Documentation
        - 7.AC Apache Mesos
            - Apache Mesos is an open-source project to manage computer
              clusters. It was originally developed at the University of
              California at Berkeley. It provides efficient resource isolation
              and sharing across distributed applications or frameworks.
            - [Getting Started with Apache Mesos (MesosCon) - Video](https://www.youtube.com/watch?v=ugmfP-QtgTA) -
              The Linux foundation
            - [Getting Started with Mesos - Documentation](https://mesos.apache.org/getting-started/) -
              Apache Mesos
        - 7.AD Helm
            - Helm is a package manager for Kubernetes that allows developers
              and operators to more easily package, configure, and deploy
              applications and services onto Kubernetes clusters.
            - [Quickstart Guide - Documentation](https://helm.sh/docs/intro/quickstart/) -
              Helm
    - 7.B LXD
        - LXD is a next generation system container manager. It offers a user
          experience similar to virtual machines but using Linux containers
          instead. It's image based with pre-made images available for a wide
          number of Linux distributions and is built around a very powerful, yet
          pretty simple, REST API.
        - [LXD - Documentation](https://documentation.ubuntu.com/lxd/en/latest/) -
          Ubuntu (Canonical parent company of both projects)
    - 7.C Podman
        - Podman is a daemon-less container engine for developing, managing, and
          running Containers on Linux. The design of Podman is to be a drop-in
          replacement for Docker. Podman uses the same command-line interface as
          Docker, however, it operates without a daemon, and it employs
          container runtimes like `runc` for running containers.
        - [Get Started with Podman - Documentation](https://podman.io/get-started) -
          Podman
    - 7.D Containerd
        - Containerd is an industry-standard core container runtime. It is
          available as a daemon for Linux and Windows, and it manages the
          complete container lifecycle of its host system, which includes image
          transfer and storage, container execution and supervision, and
          low-level storage handling. Containerd is designed to be embedded into
          a larger system, rather than being used directly by developers or
          end-users.
        - [Getting started with containerd - Documentation](https://github.com/containerd/containerd/blob/main/docs/getting-started.md) -
          Containerd

8. **Cloud Providers** -
   Cloud providers are platforms offering a range of computing services over the
   internet. These services typically include servers, storage, databases,
   networking, software, analytics, and even artificial intelligence. Major
   cloud providers include Amazon Web Services (AWS), Google Cloud Platform
   (GCP), and Microsoft Azure. They enable businesses to run their applications
   without needing to maintain the underlying infrastructure, offering
   scalability and flexibility.

9. **Backend Architectures**
    - There are several different types of backend
      architectures.
      Each has its own advantages and disadvantages.
      It's important
      to understand the differences between them
      so that you can choose the right
      one for your needs.
    - [Monolith vs Microservices vs Serverless -
      Video](https://www.youtube.com/watch?v=1A9tPOfp6NA) -
      Code with Ryan
    - 9.A Monolithic Architecture
        - This is the traditional way of building applications. It's where you
          have a single application that handles everything from the frontend to
          the backend. It's easy to get started with, but it's not the most
          scalable or flexible. There aren't any resources on this because it
          does not require any special knowledge.
    - 9.B Microservices Architecture
        - Microservices architecture is a method of developing software
          applications as a suite of independently deployable, small, modular
          services in which each service runs a unique process and communicates
          through a well-defined, lightweight mechanism to serve a business
          goal.
        - [Open Answers: What are microservices? - Video](https://www.youtube.com/watch?v=jsg1_RM8pmw) -
          RedHat
        - [Microservices explained — the What, Why and How? -
          Video](https://www.youtube.com/watch?v=rv4LlmLmVWk) -
          TechWorld with Nana
        - [Microservices - Article](https://microservices.io/) -
          Microservices.io
    - 9.C Serverless Architecture
        - Serverless architecture is a method of developing software
          applications as a suite of independently deployable, small, modular
          services in which each service runs a unique process and communicates
          through a well-defined, lightweight mechanism to serve a business
          goal. This can be really expensive compared to other architectures.
        - [Serverless Computing in 100 Seconds - Video](https://www.youtube.com/watch?v=W_VV2Fx32_Y) -
          Fireship
        - [Serverless Architecture Explained - Video](https://www.youtube.com/watch?v=Zygw4UAxCdg) -
          TechWorld with Nana
        - [Serverless Architecture -
          Article](https://martinfowler.com/articles/serverless.html) -
          Martin Fowler
        - [The Amazon Prime Video Monolith Shift: Dissecting Microservices,
          Serverless, and the Real-World Cost -
          Article](https://medium.com/@abhishekranjandev/the-amazon-prime-video-monolith-shift-dissecting-microservices-serverless-and-the-real-world-ec18e429ad6f) -
          Abhishek Ranjan on Medium
    - 9.D Service-Oriented Architecture (SOA)
        - Service-Oriented Architecture is a style of software design where
          services are provided to the other components by application
          components, through a communication protocol over a network. The basic
          principles of service-oriented architecture are independent of
          vendors, products and technologies.
        - [Service-Oriented Architecture - Video](https://www.youtube.com/watch?v=_dFJOSR-aFs) -
          Systems Innovation
        - [What is service-oriented architecture (SOA)? - Article](https://www.redhat.com/en/topics/cloud-native-apps/what-is-service-oriented-architecture) -
          Red Hat
        - [What Is SOA (Service-Oriented Architecture)? - Article](https://aws.amazon.com/what-is/service-oriented-architecture/) -
          Amazon Web Services

10. **Testing**
    - Testing is a critical part of software development that involves
      evaluating the functionality of a software application to find any
      software bugs.
      It checks whether the developed software met the specified
      requirements and identifies any defects to improve the quality of the
      product.
    - Different types of testing include unit testing, integration
      testing, functional testing, system testing,
      manual testing, and automated
      testing.
      Understanding these concepts is essential for the development of
      reliable and high-performing software applications.
    - [Software Testing Explained in 100 Seconds - Video](https://www.youtube.com/watch?v=u6QfIXgjwGQ) -
      Fireship
    - 10.A Types of Testing
        - There are several different types of testing including unit testing,
          integration testing, end-to-end testing, etc. Each has its own
          advantages and disadvantages. It's important to understand the
          differences between them so that you can choose the right one for your
          needs.
        - [5 Types of Testing Software Every Developer Needs to Know! - Video](https://www.youtube.com/watch?v=YaXJeUkBe4Y) -
          Alex Hyett
        - [Software Testing Training – Manual Testing Basics for Beginners - Playlist](https://www.youtube.com/playlist?list=PLDC2A0C8D2EC934C7) -
          Guru99
    - 10.B Testing Frameworks
        - This is a broad topic, and there are many different types of testing
          frameworks. Here I'll outline some of the most popular ones for the
          languages recommended earlier in the roadmap.
        - 10.BA Node.js
            - [Jest](https://jestjs.io/)
            - [Mocha](https://mochajs.org/)
            - [Chai](https://www.chaijs.com/)
        - 10.BB Python
            - [Pytest](https://docs.pytest.org/en/6.2.x/)
            - [unittest](https://docs.python.org/3/library/unittest.html)
            - [nose](https://nose.readthedocs.io/en/latest/)
        - 10.BC Go
            - [Go Testing](https://golang.org/pkg/testing/)
        - 10.BD PHP
            - [PHPUnit](https://phpunit.de/)
            - [Codeception](https://codeception.com/)
            - [Behat](https://docs.behat.org/en/latest/)
        - 10.BE Kotlin
            - [JUnit](https://junit.org/junit5/)
            - [Spek](https://www.spekframework.org/)
            - [Kotest](https://kotest.io/)
    - 10.C Testing Methodologies
        - 10.CA Test Driven Development (TDD)
            - Test-driven development is a software development process relying
              on software requirements being converted to test cases before
              software is fully developed, and tracking all software development
              by repeatedly testing the software against all test cases.
            - [Test-Driven Development // Fun TDD Introduction with JavaScript - Video](https://www.youtube.com/watch?v=Jv2uxzhPFl4) -
              Fireship
            - [Do People HATE Test Driven Development (TDD)? - video](https://www.youtube.com/watch?v=4TuyMcCrTB4) -
              Continuous Delivery
            - [TDD - Article](https://www.agilealliance.org/glossary/tdd/) -
              Agile Alliance
            - [What is Test Driven Development (TDD)? - Article](https://www.guru99.com/test-driven-development.html) -
              Guru99
        - 10.CB Behavior Driven Development (BDD)
            - Behavior-driven development is an Agile software development
              process that encourages collaboration among developers, QA and
              non-technical or business participants in a software project.
            - [An Ultimate Guide To BDD -
              Article](https://www.youtube.com/watch?v=gXh0iUt4TXA) -
              Continuous Delivery
            - [Test Driven Development vs Behavior Driven Development - Article](https://www.youtube.com/watch?v=Bq_oz7nCNUA) -
              Continuous Delivery
        - 10.CC Exploratory Testing
            - Exploratory testing is a software testing approach that allows
              testers to apply their knowledge and expertise to design and
              execute tests. It's a great way to find bugs that might not be
              found by other testing methods.
            - [Exploratory Testing - Article](https://www.guru99.com/exploratory-testing.html) -
              Guru99
            - [Exploratory Testing Vs Scripted Testing: Who Wins? - Article](https://www.softwaretestinghelp.com/exploratory-testing-vs-scripted-testing/) -
              Software Testing Help
        - 10.CD Stress Testing
            - Stress testing is a type of performance testing that validates the
              stability and reliability of a system or application under extreme
              conditions. It's used to find bugs that might not be found by
              other testing methods.
            - [What is Stress Testing? - Video](https://www.youtube.com/watch?v=h0ujOhq0QYM) -
              QAFox
            - [Stress Testing - Article](https://www.guru99.com/stress-testing-tutorial.html) -
              Guru99
        - 10.CE Security Testing
            - Security testing is a type of testing that validates the security
              of a system or application. It's used to find vulnerabilities that
              might not be found by other testing methods.
            - [Security Testing - Article](https://www.guru99.com/security-testing.html) -
              Guru99
            - [Security Cheat Sheet - Article](https://cheatsheetseries.owasp.org/Glossary.html) -
              OWASP Cheat Sheet

<details>
    <summary><b>Checkpoint</b>: You should now have a general understanding of backend development.</summary>
You should be able to build more advanced WebApps and APIs with this knowledge.

Project ideas:
Sorry I got none... you can suggest some in the issues section on
GitHub. (https://github.com/NavigoLearn/RoadmapsMarkdown)
</details>

11. **Logging and Monitoring**
    - Logging and monitoring are essential for any application. They allow
      you to see what's happening in your application and how it's
      performing. They also allow you to see if there are any errors or
      issues that need to be fixed. You should learn your language's logging
      and monitoring tools.
    - [JavaScript — Beyond Console Log in 100 Seconds -
      Video](https://www.youtube.com/watch?v=L8CDt1J3DAw) -
      Fireship
    - [Python —
      Python Logging: How to Write Logs Like a Pro! -
      Video](https://www.youtube.com/watch?v=pxuXaaT1u3k) -
      ArjanCodes
    - [Go —
      How to Properly Log Things in Go (Native) - STOP using fmt.Println() -
      Video](https://www.youtube.com/watch?v=yF7k6PxtRU8) -
      GoLang Dojo
    - [PHP - How to Log Errors in PHP | PHP Error Reporting and Debugging for Beginners | Log Website Errors - Video](https://www.youtube.com/watch?v=EoP5PqvoLHg) -
      Dani Krossing
    - 11.A Application Monitoring
        - Application monitoring is a process that ensures that a software
          application processes and performs tasks as expected. The purpose of
          monitoring is to detect and resolve any issues or abnormalities that
          could affect expected and efficient operation.
        - 11.AA Log Management
            - Log management includes all the stages from the creation of log
              events to their ultimate disposal. Proper log management practices
              can give valuable insights into system performance, security, user
              behaviors, system functionality, and troubleshooting issues.
            - [What is Log Management? - Article](https://www.solarwinds.com/resources/it-glossary/log-management) -
              SolarWinds
        - 11.AB Infrastructure Monitoring
            - Infrastructure monitoring is the task of ensuring that all the
              hardware, software, networks, and processes in your IT
              infrastructure are running smoothly and optimally.
            - [Infrastructure Monitoring Overview - Article](https://www.datadoghq.com/knowledge-center/infrastructure-monitoring/) -
              DataDog
        - 11.AC Network Monitoring
            - Network monitoring is the use of a system that constantly monitors
              a computer network for slow or failing components, and that
              notifies the network administrator (via email, SMS or other
              alarms) in case of outages or other trouble.
            - [What is Network Monitoring? - Article](https://www.ibm.com/topics/network-monitoring) -
              IBM
        - 11.AD Security Monitoring
            - Security monitoring is the collection, analysis, and escalation of
              indications and warnings to detect and respond to intrusions. This
              is crucial to ensure the safety of your applications and
              infrastructure.
            - [What is Security Monitoring? - Article](https://www.hpe.com/us/en/what-is/security-monitoring.html) -
              Hewlett Packard Enterprise
        - 11.AE Performance Monitoring
            - Performance monitoring is the process of detecting and diagnosing
              system performance problems. It helps you maintain system
              efficiency, meet service-level agreements (SLAs), and identify
              areas of improvement.
            - [Performance Monitoring - an overview - Article](https://www.sciencedirect.com/topics/social-sciences/performance-monitoring) -
              Science Direct
    - 11.B Tools for Logging and Monitoring
        - There are many tools available for logging and monitoring your
          systems. Here are a few of the most popular:
        - [Loggly - Product](https://www.loggly.com/) - Cloud-based log
          management and analytics service that leverages machine-generated big
          data to deliver real-time IT insights.
        - [Splunk - Product](https://www.splunk.com/) - Software for searching,
          monitoring, and analyzing machine-generated big data, via a web-style
          interface.
        - [Elasticsearch - Product](https://www.elastic.co/) - A search and
          analytics engine based on the Lucene library.
        - [Logstash - Product](https://www.elastic.co/logstash) - An open-source
          data collection engine with real-time pipelining capabilities.
        - [Kibana - Product](https://www.elastic.co/kibana) - An open-source
          data visualization plugin for Elasticsearch.
        - [Prometheus - Product](https://prometheus.io/) - An open-source
          systems monitoring and alerting toolkit.
        - [Grafana - Product](https://grafana.com/) - An open platform for
          beautiful analytics and monitoring.
        - [New Relic - Product](https://newrelic.com/) - A cloud-based platform
          that gives devs, ops, and tech teams the tools to monitor and optimize
          their operations
        - [DataDog - Product](https://www.datadoghq.com/) - Monitoring service
          for cloud-scale applications, providing monitoring of servers,
          databases, tools, and services, through a SaaS-based data analytics
          platform.
        - [Sentry - Product](https://sentry.io/) - Open-source error tracking
          that helps developers monitor and fix crashes in real time.

12. **CI/CD (Continuous Integration / Continuous Deployment)**
    - Continuous Integration (CI) and Continuous Deployment (CD) are pivotal
      practices in modern software development allowing for code changes to be
      automatically built, tested, and deployed. They foster a culture of fast
      feedback, lower the risk associated with release and increase software
      quality.
    - [DevOps CI/CD Explained in 100 Seconds - Video](https://www.youtube.com/watch?v=scEDHsr3APg) -
      Fireship
    - [Continuous integration vs. delivery vs. deployment - Article](https://www.atlassian.com/continuous-delivery/principles/continuous-integration-vs-delivery-vs-deployment) -
      Atlassian
    - [What is CI/CD? Continuous integration and continuous delivery explained - Article](https://www.infoworld.com/article/3271126/what-is-cicd-continuous-integration-and-continuous-delivery-explained.html) -
      InfoWorld
    - 12.A Basics of Continuous Integration
        - Continuous Integration is a development practice where developers
          integrate code into a shared repository frequently, preferably several
          times a day. Each integration can then be verified by an automated
          build and automated tests.
        - [What is Continuous Integration? - Video](https://www.youtube.com/watch?v=1er2cjUq1UI) -
          IBM Technology
        - [Continuous Integration - Article](https://martinfowler.com/articles/continuousIntegration.html) -
          Martin Fowler
    - 12.B Tools for Continuous Integration
        - 12.BA Jenkins
            - Jenkins is an open-source automation server that enables
              developers to build, test, and deploy their software.
            - [Jenkins User Documentation - Documentation](https://www.jenkins.io/doc/)
        - 12.BB Travis CI
            - Travis CI is a hosted continuous integration service used to build
              and test software projects hosted at GitHub.
            - [Travis CI Tutorial - Documentation](https://docs.travis-ci.com/)
        - 12.BC CircleCI
            - CircleCI is a CI/CD tool that supports rapid software development
              and publishing.
            - [Welcome to CircleCI - Documentation](https://circleci.com/docs/)
        - 12.BD GitHub Actions
            - GitHub Actions make it easy to automate all your software
              workflows with world-class CI/CD.
            - [5 Ways to DevOps-ify your App - GitHub Actions Tutorial —
              Video](https://www.youtube.com/watch?v=eB0nUzAI7M8) -
              Fireship
            - [GitHub Actions — Documentation](https://docs.github.com/en/actions)
    - 12.C Basics of Continuous Deployment
        - Continuous Deployment is a strategy for software releases wherein any
          code commit that passes the automated testing phase is automatically
          released into the production environment.
        - [What is Continuous Deployment? - Video](https://www.youtube.com/watch?v=2TTU5BB-k9U) -
          IBM Technology
        - [What is Continuous Delivery - Article](https://continuousdelivery.com) -
          Continuous Delivery
    - 12.D Tools for Continuous Deployment
        - 12.DA Jenkins
            - [Pipeline as Code with Jenkins - Article](https://www.jenkins.io/solutions/pipeline/) -
              Jenkins
        - 12.DB AWS CodeDeploy
            - AWS CodeDeploy is a fully managed deployment service that
              automates software deployments to a variety of compute services
              such as Amazon EC2, AWS Fargate, AWS Lambda, and your on-premises
              servers.
            - [What is CodeDeploy? - Documentation](https://docs.aws.amazon.com/codedeploy/latest/userguide/welcome.html) -
              Amazon Web Services
        - 12.DC Google Cloud Deployment Manager
            - Deployment Manager is an infrastructure deployment service that
              automates the creation and management of Google Cloud resources.
            - [Google Cloud Deployment Manager - Documentation](https://cloud.google.com/deployment-manager/docs) -
              Google Cloud
        - 12.DD Heroku
            - Heroku is a platform as a service (PaaS) that enables developers
              to build, run, and operate applications entirely in the cloud.
            - [Heroku - Documentation](https://devcenter.heroku.com) - Heroku
    - 12.E CI/CD Best Practices
        - Best practices for CI/CD include maintaining a code repository,
          automating the build, keeping the build fast, testing in a clone of
          the production environment, make it easy to get the latest
          deliverables; everyone can see what's happening and automate
          deployment.
        - [Top 8 CI/CD best practices for your DevOps team’s success - Article](https://middleware.io/blog/ci-cd-best-practices/) -
          Middleware

13. **Rate Limiting and Throttling**
    - They are essential strategies to prevent resource overuse, defend APIs,
      ensure service quality, and stop abuse.
    - [Rate Limiting, API Keys, and OAuth -
      Article](https://stripe.com/blog/rate-limiters) -
      Stripe Engineering Blog
    - [API Rate Limiting and Throttling Explained -
      Article](https://nordicapis.com/everything-you-need-to-know-about-api-rate-limiting/) -
      Nordic APIs
    - 13.B Rate Limiting Techniques
        - 13.BA Fixed Window Counter
            - It entails counting the number of requests made inside a fixed
              time window. Requests beyond the set limit within the window are
              blocked until the window resets.
            - [Understanding the Rate-Limiting Algorithms -
              Article](https://www.quinbay.com/blog/understanding-rate-limiting-algorithms/) -
              Quinbay
        - 13.BB Sliding Window Log
            - The Sliding Log method keeps a timestamp log for each request. The
              number of requests within the current window is checked before
              deciding to allow or reject the request.
            - [An alternative approach to rate limiting - Article](https://www.figma.com/blog/an-alternative-approach-to-rate-limiting/) -
              Figma
        - 13.BC Token Bucket
            - The Token Bucket method involves adding a token to the 'bucket' at
              predefined timings. A request is allowed only if a token could be
              removed from the bucket.
            - [What is Token Bucket algorithm in computer networks? -
              Article](https://www.tutorialspoint.com/what-is-token-bucket-algorithm-in-computer-networks) -
              Tutorials Point
        - 13.BD Leaky Bucket
            - The Leaky Bucket algorithm functions like a 'bucket' with a small
              leak at the bottom. When the request rate surpasses the drain
              rate, the bucket 'leaks' and excess requests are discarded.
            - [Computer Network | Leaky bucket algorithm -
              Article](https://www.geeksforgeeks.org/leaky-bucket-algorithm/) -
              GeeksForGeeks
    - 13.C Libraries for Rate Limiting
        - 13.CA Node.js:
            - [Express Rate Limit - NPM](https://www.npmjs.com/package/express-rate-limit) -
              IP rate-limiting middleware for Express.
            - [Slow Down - NPM](https://www.npmjs.com/package/express-slow-down) -
              Slows down responses rather than blocking them.
        - 13.CB Python:
            - [RateLimiting - Documentation](https://flask-limiter.readthedocs.io/en/stable/) -
              Provides rate-limiting features for Flask routes.
        - 13.CC Go:
            - [Tollbooth - Documentation](https://github.com/didip/tollbooth) -
              A rate limiter for HTTP requests.
        - 13.CD Kotlin:
            - [Ktor limits - Documentation](https://ktor.io/docs/rate-limit.html) -
              Rate limiting for Ktor.

<details>
    <summary><b>Checkpoint</b>: You should now have a broad understanding of everything going into backend development.</summary>
You should be able to build about anything you want with this knowledge.

Project ideas:

- Build a script scheduler
    1. Develop a functionality that permits users to create scripts running on a
       schedule that they specify.
    2. Implement a feature to allow users to select the script interpreter (like
       Node.js, Python, Bash, Zsh, Lua, etc.) to use based on their script's
       requirements.
    3. Allow users to set webhooks that become active when the script finishes
       its run.
    4. Provide the ability for users to establish environment variables specific
       to the script.
    5. Build a permissions system and restrict certain commands, making them
       accessible only with additional permissions.
    6. Engineer a simple frontend application to manage the scripts.
    7. Incorporate an interface to view the console output of the executed
       scripts.
    8. Log the output of the scripts either in a database or a log file for
       debugging purposes.
    9. Include a feature to view the logs of the scripts in the web user
       interface, provided the user has necessary permissions.
    10. Introduce an option for users to pause, stop, or resume scripts.
    11. Add user authentication and authorization to ensure safe access to the
        scheduler.
- Build a web crawler
    1. Establish your target website(s) for crawling.
    2. Build a parser to extract information.
    3. Store this extracted information in a structured format (like JSON, XML
       or in a Database).
    4. Implement an approach to navigate through different web pages and links.
    5. Reliably handle runtime exceptions and errors.
    6. Design a system to respect robots.txt rules.
    7. Add user-agent strings and manage request headers.
    8. Introduce multi-threading or asynchronous processing to speed up
       crawling.
    9. Create a result viewer or output handler to inspect, validate and use
       your
       crawling data.

</details>
