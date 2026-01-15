This is my Bookstore project for the assignment. It’s an ASP.NET Core MVC application that uses SQLite and Entity Framework Core. I also set up ASP.NET Core Identity so users can register and log in.

Anyone can view the books, but only logged-in users can create, edit, or delete them. The Book model has the required fields (Id, Title, Author, Price), and the CRUD pages were scaffolded and then updated to include authorization.

To run the project:

Clone the repo:
git clone https://github.com/natbat33-crypto/Bookstore.git

Open the solution in Visual Studio.

Open the Package Manager Console and run:
Update-Database
This creates the SQLite database using the migrations.

Run the project.

Deployment Note:
I did not deploy the application, but if I were to deploy it I would use the Publish option in Visual Studio and deploy to a hosting provider Azure App Service. 
The steps would be:
1. Open the project in Visual Studio.
2. Right-click the project and select Publish.
3. Choose Azure App Service or another hosting option. 
4. Configure the service and database connection.
5. Publish the application.

For the purposes of this assignment, the project runs locally using SQLite.

