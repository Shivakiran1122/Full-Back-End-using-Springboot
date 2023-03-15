# Full-Back-End-using-Springboot <br/>
Building real time REST API'S for blogging  Application<br/>

**Overview:**<br/>
Building real time RestAPI'S for Blogging Application using Springboot, Spring Security, JWT(JSON Web Token), Spring Data JPA(Hibernate) and MYSQL.<br/>
1.Creating REST Endpoints.<br/>
2.Complex Db structure (JPA Entities).<br/>
3.Role Based Authentication.<br/>
4.Handling Exceptions.<br/>
5.Using DTO for Data Transfer.<br/>
6.Swagger Library (Documentation  for Rest API'S).<br/>

**OutComes of the Project:**<br/>

1.How to add profiles for different environments.<br/>
2.How to deploy spring boot in  cloud Environment (AWS in this case).<br/>

**Techonologies and tools used:**<br/>
1.Java 8+.<br/>
2.Maven.<br/>
3.Intellij (Java IDE).<br/>
4.Apache Tomcat.<br/>
5.Spring core, Spring Security (jwt) , Spring data JPA(Hibernate).<br/>
6.MYSQL Database.<br/>
7.Postman Rest Client (API Testing).<br/>
8.Swagger (API Documentation).<br/>
9.AWS EC2 (Deploy the Application).<br/>

**Technologies to be familar for project Implementation:**<br/>

1.Core Java (OOPS,packages, exception, lambda, stream API etc).<br/>
2.Basics of Spring Framework(Spring Core (Dependency Injection, Inversion of Control), JPA and MVC).<br/>
3.Spring Boot Basics.<br/>
4.Basics of MYSQL Database.<br/>
5.Intellij IDEA (IDE).<br/>

**REST API'S:**<br/>
REST stands for Representational State Transfer.<br/>
Representational- Format: json,xmml<br/>
State- Data<br/>
Trnasfer-Transfer of data between parties (here it is Client And Server)<br/>

**Defination:**<br/>
REST API's: Design Architecture style for the web where transfer of data between Client and Server  is in specified format like Json or XML.<br/>

**REST Guidelines:**<br/>
**1.Client Server Architecture** - Client and server must be independent entities.Code for front end and back end are different.<br/>
**2.Stateless** - We will not store any data on the server side. Here client should store the information.When client calls an API Server should just process the data send back the response.<br/>
**3.Cacheable** - When client send Repeated Requests to server again and again then server performance can be down.when same request is send to server again and again.
when once client request to the server the required data we get as reponse. client can make it cache(a copy) and store  reuse it so that performance can be increased.<br/>
**4.Layered System** - 3 Tier Architecture beacuse of layering we can achive scalability and we can handle load balancing.<br/>
**5.Unified Interaction** - Decoupling the architecture.<br/>
**6.Code on Demand (Optional)** - when client makes a request server can  send code on demand and execute the code on the Client.<br/>

**REST Concepts:**<br/>
**1. Resource** - Anything that we want to expose to outside world through our Application (Entities).<br/>
**2. Sub-Resource**- Resource which is dependent on the main resource. Example - Studnet(Resource)-> Laptop(Sub Resource).<br/>
  Method ---http://localhost:8282/resource/{id}/subresource<br/>
  GET ----- http://localhost:8282/students/12/laptops/   Return the list of laptops of student 12<br/>
  GET ----- http://localhost:8282/students/12/laptops/63 Return the laptop of id 63 of student 12<br/>
  Sub resource can not exist without resources.<br/>
**3. URI(Uniform Resource Identifier)**- used to identify a resource on the server.<br/>
    GET  ------ http://localhost:8282/students/ ----------------- Returns the list of Students.<br/>
    GET  ------ http://localhost:8282/students/12 --------------- Returns the student of id 12.<br/>
    POST ------ http://localhost:8282/students/ ------------------Create a new Student.<br/>
    PUT ------- http://localhost:8282/students/20 ----------------Update a student of id 20.<br/>
    DELETE -----http://localhost:8282/students/2 -----------------Delete a student of id 2.<br/>
**4.Http Methods** - HTTP defines a set of request methods to indicate the desired action to be performed for a given resource.<br/>
 Methods -GET, POST, PUT, DELETE. <br/>
**5.Http Response Code** - HTTP response status codes indicate weather a specific HTTP request has been successfully completed.<br/>
1.200 OK ---------------------------------------------------Request is Successful.<br/>
2.201 Created ----------------------------------------------Request is Successful and new resource is created.<br/>
3.401 Unauthorized-------------------------------------------Authentication is required for resource.<br/>
4.404 Not Found----------------------------------------------Resource Not Found.<br/>
5.500 nternal Server Error-----------------------------------Error occurred on server and request can not fulfilled.<br/>

**Client Requirement:**<br/>
Client wants blogging Application where he/she can write blogs and articles.<br/>
user can comment on the blogs/articles.<br/>
we have to build simple Blogging Application:
1.User should create update, delete and list posts.<br/>
2.User should  add, update delete comments on posts.<br/>
3.Categories the posts according to Categories.<br/>
4.New User should able to register on our application.<br/>
5.User should able to login to our application.<br/>
6.Post Include one picture too.<br/>

**Client Requirement in technical terms:**<br/>
1.proper Login and Register API.<br/>
2.Posts API includes Pagination and Sorting.<br/>
3.Proper User Input Handling.<br/>
4.Proper exception Handling.<br/>
5.Role based authentication-role based security with API'S.<br/>
6.JWT(JSON Web Token) based authentication.<br/>
7.JWT all rest api's so that consumer can easily understand.<br/>
8.Deploy the backend application on any cloud platform.<br/>

**Resources for Blogging Application :** <br/>
1.USER<br/>
2.CATEGORY<br/>
3.POST<br/>
4.COMMENTS<br/>

**Best Architecture while using Spring Boot for Backend:**<br/>
**Postman(Client)----->(Request)--------> Controllers(API Layers)<-------->Services(Business Logic)<--------->Repositories(DAO/persistant Layers)<------->Database<br/>
  <-----(Response)<---Controllers(API Layers)     <------------------------------------ (Springboot App)-------------------------------------------------------><br/>**

     
     













