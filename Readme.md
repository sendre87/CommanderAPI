## NET Core 3.1 MVC REST API - Full course

This sample project is created after a youtube video (created by <i>Les Jackson</i>).
The main scope is defining the most paverfull and common REST verbs in a .Net Core 3.1 project.

The video link is: 
 - https://www.youtube.com/watch?v=fmvcAzHpsk8&feature=youtu.be

 Usefull "dotnet" commands:
  - dotnet new webapi
  - dotnet build
  - dotnet run
  - dotnet tool install --global dotnet-ef -> can use the "dotnet ef" command
  - dotnet ef
  - dotnet ef migrations add <Name of migrations>
  - dotnet ef migrations remove
  - dotnet ef database update - run migrations
  
As addition, with project is used the <b>Swagger</b> API descripter.

Usefull links in this topic:
 - https://swagger.io/docs/specification/2-0/what-is-swagger
 - https://docs.microsoft.com/en-us/aspnet/core/tutorials/getting-started-with-swashbuckle?view=aspnetcore-3.1&tabs=visual-studio-code


The web api verbs can be reached on the following link:
 - http://localhost:{port}/api/commands/swagger/v1