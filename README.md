API:
-REST (Representational State Transfer)
+ Style of architecture for building web services 
+ Set of principles
-HTTP Verbs
+ GET
+ POST
+ PUT 
+ DELETE
+ PATCH
+ OPTIONS
E.g: GET: https//yourapi.com/api/employees/{id} (get all employees by Id)
-DbContext Class
+ Maintaining Connection to DB
+ Track changes
+ Perform CRUD
+ Bridge between Models and DB
-Dependency Injection
+ Design pattern to increase maintainability , testability
+ DI built into ASP.NET Core
+ DI container is responsible for creating and managing instances
-Use this command for add EF Migrations
<pre>dotnet ef migrations add yourMigrationName</pre>
<pre>dotnet ef database update</pre>
-DTO (Data Transfer Objects)
+ Used to transfer data between different Layers
+ Typically contain a subset of the properties in the domain model
+ For example transferring data over the network
=> Advantage : 
+ Seperation of Concerns 
+ Performance
+ Security
+ Versioning
-Repository Pattern
+ Design Pattern to seperate the data access layer from the application
+ Provides interface without exposing implementation
+ Helps create abstraction
=> Benefits:
+ Decoupling
+ Consistency
+ Performance
+ Multiple data sources (switching)
UI:
-Angular