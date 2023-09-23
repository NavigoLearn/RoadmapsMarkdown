# Backend Development
### Essential Prequisites
* Basics of computer science
* Understanding of Servers and HTTP/HTTPS
#### Recommended prequisites
* Git and GitHub
* Data Structures and Algorithms    
* Basic understanding of a frontend language like JavaScript or super set of JavaScript like Typescript, React, Angular, Vue, etc.


1. Backend Development Intro
    - This section contains information on what you need to know to get started with backend development. You don't need to know everything in this section to get started, but it's important to have a basic understanding of the concepts listed here so you can talk to people and get help.
    - [Learn web development as an absolute beginner](https://www.youtube.com/watch?v=ysEN5RaKOlA) - Coder Coder
    - 1.A What is a server?
      - It's important to understand the concept of what a server is and how it works. This will help you understand how anything on the internet works. You may already have a vague idea if you're gamer, but could you really define what a server is? 
      - [What is a Server? (Deepdive) - Video](https://www.youtube.com/watch?v=VXmvM2QtuMU) - LiveOverflow
      - [What is a Server? - Article](https://www.geeksforgeeks.org/what-is-server/) - GeekforGeeks
    - 1.B What is a protocol
      - Protocols are the rules that govern how computers communicate with each other. You should have a basic understanding of what a protocol is and how it works to avoid headaches ahead. 
      - [What is a protocol? - Video](https://www.youtube.com/watch?v=fK7oAc_V-Kk) - Internet-class
      - [What is a Protocol? (Deepdive) - Video](https://www.youtube.com/watch?v=d-zn-wv4Di8) - LiveOverflow
      - [Why are protocols so highly structured? - Video](https://www.youtube.com/watch?v=1M1FqYrapCM) - Internet-class
      - [What is a protocol? | Network protocol definition - Article](https://www.cloudflare.com/learning/network-layer/what-is-a-protocol/) - CloudFlare
    - 1.C How the internet works?
      - [The Two Generals’ Problem - Video](https://www.youtube.com/watch?v=IP-rGJKSZ3s) - Tom Scott
      - [The Http and the Web | Http Explained | Request-Response Cycle - Video](https://www.youtube.com/watch?v=eesqK59rhGA) - The TechCave
      - [Hypertext Transfer Protocol (HTTP)](https://www.extrahop.com/resources/protocols/http/) - ExtraHop
    - 1.D Why Backend?
        - 1.DA Role of a Backend Developer
          - [Backend Development explained in 2 minutes - Video](https://www.youtube.com/watch?v=cbSrsYiRamo) - mayuko 
          - [What does a back-end developer do? - Article](https://business.linkedin.com/talent-solutions/resources/how-to-hire-guides/back-end-developer/job-description#:~:text=Backend%20developer%20responsibilities%20include%20creating,taking%20place%20behind%20the%20scenes.) - LinkedIn
        - 1.DB Common Backend Technologies
          - A list of things that are commonly used in backend development. And most of what you'll be learning in this roadmap.
          - Languages & Frameworks
            - Be it Express, Django or any other framework the easiest way to get started with backend development is to use a framework. Frameworks are a collection of libraries and tools that make it easier to build applications by abstracting away the complexity of the underlying technologies. 
          - Databases & ORMs
            - Databases are used to store data. There are many different types of databases, but the most common ones are relational databases like MySQL, PostgreSQL, etc. and NoSQL databases like MongoDB, Redis, etc. ORMs are used to interact with databases. They allow you to write code instead of SQL queries to interact with the database.
          - APIs & communication Protocols
            - APIs are used to communicate between different applications. They allow you to send and receive data between applications. There are many different types of APIs, but the most common ones are REST APIs, GraphQL APIs, and WebSockets.
          - Caching
            - Caching is used to store data in memory so that it can be accessed faster. It's used to improve the performance of applications by reducing the number of times data needs to be fetched from the database or other external sources.
          - Authentication & Authorization
            - Authentication is used to verify that a user is who they say they are. Authorization is used to determine what a user can and cannot do. This can be done using a variety of different methods, but the most common ones are JWTs and OAuth.
          - Containerization
            - Containerization is used to package applications into containers so that they can be run on any machine without having to worry about dependencies or other external factors. The most common containerization tool is Docker. 
          - Cloud Providers
            - Cloud providers are used to host applications in the cloud. They provide a variety of different services, but the most common ones are compute, storage, and networking. The most popular cloud providers are AWS, Azure, GCP and DigitalOcean.

2. Server-side Programming
   - 2.A Choose a language
      - It's encouraged to pick a language and stick to it while starting out. It's less about which one you choose and more about learning to think like a programmer. Below are a few short videos of languages that are commonly used in backend development.
      - [JavaScript in 100 seconds - Video](https://www.youtube.com/watch?v=DHjqpvDnNGE) - Fireship
      - [Python in 100 seconds - Video](https://www.youtube.com/watch?v=x7X9w_GIm1s) - Fireship
      - [Go in 100 seconds - Video](https://www.youtube.com/watch?v=446E-r0rXHI) - Fireship
      - [PHP in 100 seconds - Video](https://www.youtube.com/watch?v=a7_WFUlFS94) - Fireship
      - [Kotlin in 100 seconds - Video](https://www.youtube.com/watch?v=xT8oP0wy-A0) - Fireship
   - 2.B Basic Data Structures
      - Understand the basics of arrays, strings, linked lists, stacks, queues, trees, and hash tables. You don't need to know how to implement them, but you should know how they work and when to use them.
      - [10 Key Data Structures We Use Every Day - Video](https://www.youtube.com/watch?v=ouipSd_5ivQ) - ByteByteGo
      - [Algorithms and Data Structures Tutorial - Full Course for Beginners - Video](https://www.youtube.com/watch?v=8hly31xKli0) - freeBootCamp.org

3. Databases
   - 3.A SQL
      - SQL is a language used to interact with relational databases. It's used to create, read, update, and delete data from databases. It's one of the most common languages used in backend development.
      - [SQL in 100 seconds - Video](https://www.youtube.com/watch?v=zsjvFFKOm3c) - Fireship
      - [Learn SQL In 60 Minutes - Video](https://www.youtube.com/watch?v=p3qvj9hO_Bo) - freeCodeCamp.org
      - [SQL Tutorial - Web Tutorial](https://www.w3schools.com/sql/default.asp) - W3Schools
      - 3.AA SQL Injections
        - SQL injections are one of the most common security vulnerabilities in web applications. They allow attackers to execute arbitrary SQL queries on the database. You should know how to prevent them.
        - [SQL Injections are scary!! (hacking tutorial for beginners) - Video](https://www.youtube.com/watch?v=2OPVViV-GQk&t=26s) - NetworkChuck
        - [SQL Injection Prevention Cheat Sheet - Article](https://cheatsheetseries.owasp.org/cheatsheets/SQL_Injection_Prevention_Cheat_Sheet.html) - OWASP Cheat Sheet
   - 3.B NoSQL
      - NoSQL databases are used to store unstructured data. They're often used in conjunction with relational databases to store data that doesn't fit into the relational model. They're also used to store data that needs to be accessed quickly.
      - [What Is a NoSQL Database? | NoSQL Explained - Video](https://www.youtube.com/watch?v=f8t3Hh1RxVA) - IBM Developer
      - [SQL vs. NoSQL Explained (in 4 Minutes) - Video](https://www.youtube.com/watch?v=_Ss42Vb1SU4) - Exponent
      - [Which Is Better? SQL vs NoSQL - Video](https://www.youtube.com/watch?v=t0GlGbtMTio) - Web Dev Simplified
        - 3.BA MongoDB
          - MongoDB is a document-oriented database. It's one of the most popular NoSQL databases. It's used to store data in JSON-like documents.
          - [MongoDB in 100 seconds - Video](https://www.youtube.com/watch?v=-bt_y4Loofg) - Fireship
          - [MongoDB Crash Course - Video](https://www.youtube.com/watch?v=ofme2o29ngU) - Web Dev Simplified
          - [MongoDB Tutorial - Web Tutorial](https://www.w3schools.com/nodejs/nodejs_mongodb.asp) - W3Schools
        - 3.BB Redis 
          - Redis is an in-memory data store. It's used to store data in key-value pairs. It's often used to store session data or cache data.
          - [Redis in 100 seconds - Video](https://www.youtube.com/watch?v=G1rOthIU-uo) - Fireship
          - [Redis Crash Course - Video](https://www.youtube.com/watch?v=jgpVdJB2sKQ) - Web Dev Simplified
          - [Getting started with Redis - Documentation](https://redis.io/docs/getting-started/) - Redis
        - 3.BC Cassandra
          - Cassandra is a distributed database. It's used to store data in a distributed fashion. It's often used to store data that needs to be accessed quickly.
          - [Cassandra in 100 seconds - Video](https://www.youtube.com/watch?v=ziq7FUKpCS8) - Fireship
          - [Apache Cassandra Database – Full Course for Beginners - Video](https://www.youtube.com/watch?v=J-cSy5MeMOA) - freeCodeCamp.org
          - [Cassandra Documentation - Getting Started - Documentation](https://cassandra.apache.org/doc/latest/cassandra/getting_started/index.html) - Apache Cassandra
   - 3.C ORMs
      - ORMs are used to interact with databases. They allow you to write code instead of SQL queries to interact with the database. They're often used in conjunction with relational databases to make it easier to work with them.
      - [ORM: The Good, the Great, and the Ugly - Video](https://www.youtube.com/watch?v=3EvhK7-DlZA) - Coding Tech
      - [What is an ORM? - Article](https://www.prisma.io/dataguide/types/relational/what-is-an-orm) - Prisma
      - [What is an ORM – The Meaning of Object Relational Mapping Database Tools - Article](https://www.freecodecamp.org/news/what-is-an-orm-the-meaning-of-object-relational-mapping-database-tools/#:~:text=Object%20Relational%20Mapping%20(ORM)%20is,(OOP)%20to%20relational%20databases) - freeCodeCamp

4. APIs (Application Programming Interfaces)
    - 4.A What is an API?
        - An API is a set of definitions and protocols that allows applications to communicate with each other. It's a way for different software applications to interact with each other. Get familiar with what APIs are and why they are important.
        - [APIs Explained (in 4 Minutes) - Video](https://www.youtube.com/watch?v=bxuYDT-BWaI) - Exponent
        - [What is an API and what does it do - Article](https://blog.openapihub.com/en-us/what-is-an-api-and-what-does-it-do/) - Open API Hub
    - 4.B Types of APIs
        - There are several types of APIs including REST, SOAP (mostly useless in modern applications), and GraphQL. Each has its own uses, advantages and disadvantages. Understand them and decide which one suits your needs best.
        - 4.BA RESTful APIs
            - REST stands for REpresentational State Transfer. It is an architectural style for creating web services. RESTful APIs are built using HTTP methods like GET, POST, PUT, DELETE, etc.
            - [RESTful APIs in 100 Seconds // Build an API from Scratch with Node.js Express - Video](https://www.youtube.com/watch?v=-MTSQjw5DrM) - Fireship
            - [REST API concepts and examples - Video](https://www.youtube.com/watch?v=7YcW25PHnAA) - WebConcepts
            - [Representational state transfer (REST) and Simple Object Access Protocol (SOAP) - Article](https://www.ibm.com/cloud/learn/rest-apis) - IBM Cloud
            - 4.BAA HTTP Methods
                - HTTP methods are used to perform different actions on resources. They're used to create, read, update, and delete data from databases. They're also used to perform other actions like sending emails, uploading files, etc.
                - [HTTP/1 to HTTP/2 to HTTP/3 - Video](https://www.youtube.com/watch?v=a-sBfyiXysI) - WebConcepts
                - [HTTP Methods - Article](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods) - MDN Web Docs
                - [HTTP response status codes](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status) - MDN Web Docs
            - 4.BAB RESTful API Design
                - RESTful APIs are designed using a set of principles called RESTful design principles. These principles are used to design APIs that are easy to use and understand. They're also used to design APIs that are easy to maintain and extend.
                - [REST Tutorial - How to Design a Good RESTful API - Video](https://www.youtube.com/watch?v=sMKsmZbpyjE) - Grace Hopper Academy
                - [RESTful API Design — Step By Step Guide - Article](https://betterprogramming.pub/restful-api-design-step-by-step-guide-2f2c9f9fcdbf) - Better Programming
            - 4.BAC RESTful API Best Practices
                - RESTful APIs are designed using a set of principles called RESTful design principles. These principles are used to design APIs that are easy to use and understand. They're also used to design APIs that are easy to maintain and extend.
                - [Rest API - Best Practices - Design - Video](https://www.youtube.com/watch?v=1Wl-rtew1_E) - High-Performance Programming
                - [What Is Idempotence? - Article](https://www.restapitutorial.com/lessons/idempotency.html) - REST API Tutorial
        - 4.BB GraphQL APIs
            - GraphQL is a query language for APIs and a runtime for executing those queries with your existing data.
            - [GraphQL In 100 Seconds - Video](https://www.youtube.com/watch?v=eIQh02xuVw4) - Fireship
            - [Learn GraphQL In 40 Minutes - Video](https://www.youtube.com/watch?v=ZQL7tL2S0oQ) - freeCodeCamp.org
            - [GraphQL is the better REST - Article](https://www.howtographql.com/basics/1-graphql-is-the-better-rest/) - HowToGraphQL
        - 4.BC ProtoBuf - https://protobuf.dev
    - 4.C API Security
        - Understanding how to secure your APIs is essential as they are one of the most common attack vectors used by malicious actors.
        - [Web API Security | Basic Auth, OAuth, OpenID Connect, Scopes & Refresh Tokens - Video](https://www.youtube.com/watch?v=x6jUDfpESmA) - Ambient Coder
        - [API Security Cheat Sheet - Article](https://cheatsheetseries.owasp.org/cheatsheets/REST_Security_Cheat_Sheet.html) - OWASP Cheat Sheet

5. Authentication & Authorization 
6. Caching
7. Containerization
8. Cloud Providers