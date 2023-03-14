# Full-Back-End-using-Springboot
Building real time REST API'S for blogging  Application

**Overview:**
Building real time RestAPI'S for Blogging Application using Springboot, Spring Security, JWT(JSON Web Token), Spring Data JPA(Hibernate) and MYSQL.<br/>
1.Creating REST Endpoints.<br/>
2.Complex Db structure (JPA Entities).<br/>
3.Role Based Authentication.<br/>
4.Handling Exceptions.<br/>
5.Using DTO for Data Transfer.<br/>
6.Swagger Library (Documentation  for Rest API'S).<br/>

**OutComes of the Project:**

1.How to add profiles for different environments.<br/>
2.How to deploy spring boot in  cloud Environment (AWS in this case).<br/>

**Technologies to be familar for project Implementation:**

1.Core Java (OOPS,packages, exception, lambda, stream API etc).<br/>
2.Basics of Spring Framework(Spring Core (Dependency Injection, Inversion of Control), JPA and MVC).<br/>
3.Spring Boot Basics.<br/>
4.Basics of MYSQL Database.<br/>
5.Intellij IDEA (IDE).<br/>

**REST API'S:**
REST stands for Representational State Transfer.<br/>
Representational- Format: json,xmml<br/>
State- Data<br/>
Trnasfer-Transfer of data between parties (here it is Client And Server)<br/>

**Defination:**
REST API's: Design Architecture style for the web where transfer of data between Client and Server  is in specified format like Json or XML.<br/>

**REST Guidelines:**
**1.Client Server Architecture** - Client and server must be independent entities.Code for front end and back end are different.<br/>
**2.Stateless** - We will not store any data on the server side. Here client should store the information.When client calls an API Server should just process the data send back the response.<br/>
**3.Cacheable** - When client send Repeated Requests to server again and again then server performance can be down.when same request is send to server again and again.
when once client request to the server the required data we get as reponse. client can make it cache(a copy) and store  reuse it so that performance can be increased.<br/>
**4.Layered System** - 3 Tier Architecture beacuse of layering we can achive scalability and we can handle load balancing.<br/>
**5.Unified Interaction** - Decoupling the architecture.<br/>
**6.Code on Demand (Optional)** - when client makes a request server can  send code on demand and execute the code on the Client.<br/>

**REST Concepts:**

**1. Resource** - Anything that we want to expose to outside world through our Application (Entities).<br/>
**2. Sub-Resource**- Resource which is dependent on the main resource. Example - Studnet(Resource)-> Laptop(Sub Resource).
**3. URI(Uniform Resource Identifier)**- used to identify a resource on the server.<br/>
    GET  ------ http://localhost:8282/students/ ----------------- Returns the list of Students.<br/>
    GET  ------ http://localhost:8282/students/12 --------------- Returns the student of id 12.<br/>
    POST ------ http://localhost:8282/students/ ------------------Create a new Student.<br/>
    PUT ------- http://localhost:8282/students/20 ----------------Update a student of id 20.<br/>
    DELETE -----http://localhost:8282/students/2 -----------------Delete a student of id 2.<br/>
**4.Http Methods**
**5.Http Response Code**












