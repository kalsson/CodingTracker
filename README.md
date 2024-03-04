# CodingTracker
 The C# Academy - A C# console practice project done with Blazor instead.

## Introduction

Embark on a journey to efficiently manage and track your coding sessions with our Blazor Web App. This application is designed to confront the challenges of handling Dates and Times in programming, emphasizing the importance of using public solutions and adhering to the principle of separation of concerns. By leveraging Object Oriented Programming, this project not only allows you to log your coding habits quantitatively but also serves as a testament to the collaborative spirit of the coding community.

## Requirements

- **Framework**: Developed with .NET8 for Blazor Web Applications.
- **Habit Tracking**: Focuses on quantitative tracking of habits (e.g., coding sessions).
- **Database Integration**: Utilizes SQLite for storing and retrieving data.
- **Dynamic Database Management**: Automatically generates a database and table for habit logging upon application launch.
- **User Interface**: Offers a navigable menu for easy access to different functionalities.
- **CRUD Operations**: Facilitates inserting, deleting, updating, and viewing of the habit logs.
- **Error Handling**: Implements comprehensive error management to ensure application stability.
- **Class Structure**: Requires separate classes for different functionalities (e.g., UserInput.cs, Validation.cs, CodingController.cs).
- **Data Model**: Introduces a `CodingSession` class to encapsulate session data.
- **Automated Duration Calculation**: Auto-calculates session durations from start and end times.
- **Manual Time Input**: Allows for manual entry of session times.
- **Data Access**: Employs Entity Framework for database operations.
- **Data Representation**: Enforces the use of strongly-typed lists for database reads.
- **Documentation**: Includes a README for application guidance.

## Features

1. **Stopwatch Integration**: Provides the option to track coding sessions in real-time.
2. **Flexible Data Filtering**: Enables sorting and filtering of coding records by time periods.
3. **Reporting Tools**: Generates detailed reports on coding habits over selected intervals.
4. **Goal Setting**: Offers functionalities for setting and tracking coding goals.

## Getting Started

To start using this application, clone the repository to your local machine and make sure you have .NET8 installed. Follow the instructions in `appsettings.json` to set up your database path and connection strings. Begin by building the model and setting up your database according to the guidelines outlined in the requirements.
