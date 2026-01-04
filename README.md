## .NET Blazor Development - Using Just C# (No Javascript or SQL)

This repository contains the .NET project completed during the course 

The course provides an introduction to the use of .NET Blazor (Server-Side) as well as:

Public API Usage
Blazorise UI Controls
Entity Framework Core - Code-First Database Generation

## Image Resources

The application development process makes use of a number of images that are available here at this location:

https://github.com/tgulstine/Met.Museum/tree/master/Met.Museum.UI/wwwroot

Here are the files used in the application from this folder:

egyptian-works-met.jpg  
met-exterior.jpg  
next-arrow.jpg  
prev-arrow.jpg

## Website or tools

https://www.postman.com/

https://blazorise.com/

https://jsonformatter.org/json-to-csharp

https://app.quicktype.io/?l=csharp

https://metmuseum.github.io/

## EntityFramework Core Commands
### In Command Prompt

C:\Projects\Met.Museum.Data> dotnet ef migratins add InitialCreate

C:\Projects\Met.Museum.Data> dotnet ef database update

### In Visual Studio's Package Manager Console

Set startup project:

Right-click Met.Museum.Data

Set as Startup Project

In PMC:

Default Project → Met.Museum.Data

Run:

Add-Migration InitialCreate

Update-Database

