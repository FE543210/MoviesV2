# MoviesVersion2# :sparkles: 
(Don't ask what happened with version one...)

While I spent the weekend working on my final project for MSSA, I kept stumbling over concepts in Entity Framework. To deepen my understanding, I decided to build a simple project focused on exploring its core features—such as attributes, relationships, and Fluent API configurations. Honestly had a blast seeing how this came together and compared to just using SQL. This hands on approach helped me connect the dots and apply EF Core more confidently in real-world scenarios.

## Description :grey_exclamation:
This project serves to explore a movie database using EF Core, for more complex filtering querys using LINQ, CRUD operations and advanced concepts check out my upcoming revision of my first MSSA project, a Kaban-Board. I believe the comments made the project easy to follow but if there are any questions or you are wondering why I approached it this way, feel free to reach out. 

### Executing program :anger:
* How to run the program step-by-step bullets:
```
- git clone <your-repo-url>
- cd <your-project-folder>
- dotnet restore
- Replace "Server=***CONNECTION_STRING***;Database=MovieDB;Trusted_Connection=True;TrustServerCertificate=True;" with your connection string in ApplicationDbContext
- dotnet ef database update OR tools --> NuggetPackageManager--> Package Manager Console --> Update-Database
```
End Result:
- I used SQL server management studio to visualize my data diagram.
<img width="696" height="788" alt="DataBaseView" src="https://github.com/user-attachments/assets/7780618d-514b-408f-937d-8e13007e51c5" />
