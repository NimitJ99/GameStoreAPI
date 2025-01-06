# API Project

This project is a .NET API designed to provide various functionalities for web applications.

## Features

- RESTful API endpoints
- Authentication and Authorization
- CRUD operations
- Error handling
- Logging

## Technologies Used

- .NET Core
- Entity Framework Core
- SQL Server
- Swagger for API documentation

## Getting Started

### Prerequisites

- .NET Core SDK
- SQL Server

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/NimitJ99/GameStoreAPI.git
    ```
2. Navigate to the project directory:
    ```sh
    cd your-repo
    ```
3. Restore the dependencies:
    ```sh
    dotnet restore
    ```

### Configuration

1. Update the `appsettings.json` file with your database connection string and other settings.

### Running the Application

1. Apply the database migrations:
    ```sh
    dotnet ef database update
    ```
2. Run the application:
    ```sh
    dotnet run
    ```

### API Documentation

The API documentation is available at `/swagger` endpoint once the application is running.
