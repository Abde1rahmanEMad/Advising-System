# Advising System

The Advising System is a web-based platform designed to streamline academic advising processes. Built with ASP.NET and C#, this project provides an interface for students and advisors to manage course selection, track academic progress, and ensure timely graduation.

## Key Features

- **Student Management**: Maintain a database of students with their academic records, including GPA, completed courses, and ongoing semester information.
- **Course Management**: Store and manage course information, prerequisites, and availability for upcoming semesters.
- **Advising Workflow**: Facilitate interaction between students and advisors, enabling students to request guidance and advisors to provide recommendations.
- **Progress Tracking**: Monitor student progress towards meeting graduation requirements, including core, elective, and major-specific courses.
- **Database-Driven Design**: Uses SQL Server to handle persistent storage for students, courses, and advising data.

## Technical Stack

- **Frontend**: ASP.NET Web Forms for building user-friendly interfaces.
- **Backend**: C# for server-side logic and processing.
- **Database**: SQL Server for managing relational data and ensuring data integrity.
- **Development Tools**: Visual Studio for coding and debugging the application.

## Project Structure

- **WebApplication1**: Contains the main codebase for the project, including frontend and backend logic.
- **Database Scripts**: SQL files, such as `DB_M2_Solution --Upload.sql`, are provided to set up the database schema and initial data.
- **Milestone Development**: The project is developed in milestones to ensure iterative progress and modular functionality.

## How to Run the Project

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/MarwanMostafa54/Advising-System.git
   ```
2. **Set Up the Database**:
   - Import the SQL script (`DB_M2_Solution --Upload.sql`) into your SQL Server instance.
   - Configure the database connection string in the application configuration file.
3. **Open the Project**:
   - Open the solution file in Visual Studio.
4. **Run the Application**:
   - Build and run the project using IIS Express or another compatible server.

## Future Enhancements

- Add role-based access control for administrators, advisors, and students.
- Implement an AI-powered advising assistant for automated suggestions.
- Improve the UI for a more modern and responsive design.
- Provide reporting tools for administrators to analyze student data.

