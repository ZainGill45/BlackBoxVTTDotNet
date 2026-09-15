1. *docker compose up -d* | Starts the SQL Server database.
2. *docker compose down* | Stops the SQL Server database without deleting its data.
3. *docker compose down -v && docker compose up -d* | Deletes the local database completely and starts a fresh one.
4. *docker compose ps* | Shows whether the database container is running.
5. *docker compose logs database* | Shows the SQL Server logs.
6. *dotnet watch --project server* | Starts the ASP.NET server with automatic reload.
7. *npm run dev --prefix web* | Starts the React/Vite frontend.
8. *dotnet add server package PACKAGE_NAME* | Adds a NuGet package to the ASP.NET server.
9. *npm install --prefix web* | Installs the frontend dependencies.
10. *dotnet build server* | Builds the ASP.NET server.
11. *npm run build --prefix web* | Builds the frontend for production.