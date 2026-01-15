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

If I were to deploy it, I would use the built-in Publish option in Visual Studio and publish to a hosting service (for example Azure App Service), but for the assignment I only needed to explain the steps.

That’s everything needed to run and test the application.
