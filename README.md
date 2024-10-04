Community Safety App
Project Overview
The Community Safety App is a mobile application developed for a local municipality to enhance community safety. It allows users to report incidents, get safety updates, and connect with local safety authorities. The app also provides real-time notifications about potential hazards, enabling quick communication within the community.

The project was developed by a team of software developers, UI/UX designers, quality assurance testers, and business analysts to create a user-friendly, reliable, and efficient solution to improve community safety.

Table of Contents
Features
Technologies Used
Installation
Usage
Project Structure
Contributors
License
Features
Report Incidents: Users can report incidents directly within the app, attaching photos, location data, and detailed descriptions.
Push Notifications: Receive alerts for nearby incidents, safety tips, or emergency notifications in real-time.
Safety Map: Visualize reported incidents on a map to track ongoing or past events.
Community Updates: Stay informed with the latest safety-related news and updates within the municipality.
Authority Contact: Directly connect with local law enforcement and emergency services through the app.
Technologies Used
Programming Language: C#
Framework: .NET (ASP.NET Core for backend, Xamarin for mobile app development)
Database: SQLite
User Interface: WPF (Windows Presentation Foundation) for the web-based dashboard, Xamarin for the mobile app
Version Control: GitHub
Project Management: Microsoft Project (for scheduling and tracking)
Installation
Prerequisites
.NET Core SDK 6.0 or higher
Xamarin Framework for mobile app development
Git
SQLite (for local database management)
Installation
Prerequisites
.NET Core SDK 6.0 or higher
Xamarin Framework for mobile app development
Git
SQLite (for local database management)
Steps
Clone the repository:
git clone https://github.com/yourusername/community-safety-app.git
cd community-safety-app
Install dependencies: Navigate to the project directory and install the necessary dependencies using:
dotnet restore
Set up the database: Use the provided database schema to set up your SQLite database. Run the following migration commands:
dotnet ef migrations add InitialCreate
dotnet ef database update
Run the project: For web-based dashboard:
dotnet run --project WebDashboard
For mobile app: Open the Xamarin project in Visual Studio, build, and run on an emulator or physical device.

Usage
Once the app is running, users can:

Sign Up/Login to create an account or access existing profiles.
Report Incidents by clicking on the "Report Incident" button and filling in the form.
View Safety Map for nearby incidents and community safety status.
Receive Notifications for any real-time safety alerts.
Contact Authorities using the direct links provided in the app.
Project Structure
├── CommunitySafetyApp
│   ├── WebDashboard         # Frontend for web dashboard (WPF)
│   ├── MobileApp            # Xamarin-based mobile app
│   ├── Backend              # ASP.NET Core backend API
│   ├── Database             # SQLite database setup and migrations
│   ├── Documentation        # Project documentation and reports
├── README.md
├── LICENSE
└── .gitignore
Contributors
Tumelo: Software Developer (Front-end & Back-end), Project Manager, Business Analyst
Darrel: UI/UX Designer
Joe: Mobile App Developer
Sally: Quality Assurance Tester
Mark: Graphic Designer
June: Business Analyst
License
This project is licensed under the MIT License. See the LICENSE file for more details.

