# Novel-Knett-Software-Solutions-Pvt.-Ltd.
Blazor + AspNet Web API + EFCore Sample
This application is a demo source code that showcases a Blazor Server Web App with Fluent UI Library. The backend API is built using ASP.NET Core Web API with Entity Framework Core.

The Blazor Server Web App allows for building interactive web applications using C# instead of JavaScript. The Fluent UI Library provides a set of reusable UI components that can be easily customized and integrated into the application.

The ASP.NET Core Web API serves as the backend for the application, providing data and functionality to the Blazor frontend. It is built using the powerful and flexible ASP.NET Core framework, allowing for easy integration with other services and databases.

Entity Framework Core is used as the ORM (Object-Relational Mapping) tool to interact with the database. It provides a convenient way to define and work with database entities, making it easier to perform CRUD operations and manage data.

This sample application serves as a starting point for developers who want to explore and learn about building Blazor Server Web Apps with Fluent UI and ASP.NET Core Web API with Entity Framework Core. Feel free to explore the code and customize it to fit your own requirements.

Usage
To use this sample application, follow these steps:

Clone the repository.
Open the solution in Visual Studio or your preferred IDE.
Set up API project:
Under src/Backend/Contoso.Pizza.AdminAPI.MVC, update the database connection string in the appsettings.json file to point to your desired database.
"ConnectionStrings": {
    "ContosoPizza": "<add your connection string>"
}
Build the solution to restore NuGet packages and compile the code.
Run the database migrations to create the necessary tables and seed initial data.
Start the application src/Backend/Contoso.Pizza.AdminAPI.MVC. This is a ASP.NET MVC Core Web API project. It will open up a swagger page where you can test the API endpoints.
Set up Blazor project:
Under src/Frontend/Contoso.Pizza.AdminUI, build the solution to restore NuGet packages and compile the code.
Make sure to update the API Url in appsettings.json file to point to the API project.
"Api": {
    "Url": "https://localhost:7110"
}
Start the application src/Frontend/Contoso.Pizza.AdminUI. This is a Blazor Server Web App project. It will open up a web page where you can interact with the application.
Screenshots
Home Page

Home Page
<img width="831" height="497" alt="home" src="https://github.com/user-attachments/assets/6bc39895-5736-4a58-88a9-1ffc94ea4bcd" />

Sauce Listing
<img width="1105" height="727" alt="sauce-listing" src="https://github.com/user-attachments/assets/042ae88a-74a1-4747-99f3-fdebfb83b958" />

Sauce Upsert
<img width="1105" height="727" alt="sauce-upsert" src="https://github.com/user-attachments/assets/fc2203f6-3c82-4e50-92a0-540b3f3223f6" />

Sauce Delete
<img width="1103" height="728" alt="sauce-delete" src="https://github.com/user-attachments/assets/e80c55f8-a6c2-401b-95fc-f1f139552ec2" />

Other entity UI are similar to the Sauce UI.
