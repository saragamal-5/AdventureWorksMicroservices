# AdventureWorksMicroservices Project

## Architecture Overview
The project is structured using the microservices architecture. The following components make up the system:

### 1. API (RESTful Web Service)
- Built with ASP.NET Core.
- Provides CRUD operations for accessing and modifying data from the AdventureWorks database.

### 2. Database (MS SQL Server)
- The AdventureWorks database is used to store business data.
- Data is accessed via Entity Framework Core in the API.

### 3. Docker
- Docker containers are used to isolate the application and database services.
- The API is built and deployed as a Docker container.

### 4. Jenkins
- Jenkins automates the build, test, and deployment process.
- Pipelines are used to build the API, create Docker images, and deploy the application.

## Architecture Diagram
(Insert network/architecture diagram here)

## Setup Instructions
1. Clone the repository.
2. Install the necessary dependencies:
   - .NET SDK
   - Docker
   - MS SQL Server
3. Follow the steps to build and run the application.
