RaceDay – Event Management System

Project Overview
RaceDay is a web-based application developed using ASP.NET Core MVC and ASP.NET Core Web API.
The purpose of the system is to allow organisers to manage racing events and participants to register, enter events and view their race results.

This project was developed as part of the Programming 2B Portfolio of Evidence (POE).
Technologies Used

C#
-ASP.NET Core MVC
-ASP.NET Core Web API
-SQL Server
-HTML and CSS
-Bootstrap
-Visual Studio 2022
-GitHub

System Features
-Organiser
-Register and log in
-Create and manage racing events
-Manage event categories
-View participant enrolments
-Capture and view race results-

Participant
-Register and log in
-View upcoming racing events
-Enter available events
-View enrolled events
-View race results
-View profile information

Project Structure
The solution contains the following main components:
-RaceDay_MVC: The frontend application that allows users to interact with the system.
-RaceDayPOE_part2: The Web API that processes requests and communicates with the database.
-RaceDay_Test: Unit tests for the application.

How to Run the Project
1. Download or clone the GitHub repository.
2. Open the solution file (.slnx) using Visual Studio 2022.
3. Ensure SQL Server is available and the database connection string is correctly configured.
4. Restore the required NuGet packages.
5. Start the RaceDay Web API project.
6. Start the RaceDay MVC project.
7. Open the MVC application in your browser.

Local Development URLs
Web API: https://localhost:7271/
MVC Application: https://localhost:7259/
The API and MVC applications must both be running for the system to communicate correctly.

Database
-RaceDay uses SQL Server to store application information.
-The main database tables include:
-Users
-Organisers
-Participants
-Events
-Categories
-Enrolments
-Results

Testing
The solution includes unit tests for selected API controller functionality.
GitHub Actions can be configured to build the solution and run automated tests.

Conclusion

RaceDay demonstrates the use of ASP.NET Core MVC, Web API and SQL Server to develop an event management application with separate organiser and participant functionality.
