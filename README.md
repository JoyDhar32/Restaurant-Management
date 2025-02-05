# Restaurants Project

## Overview
The **Restaurants** project is a .NET-based solution designed to manage restaurant data. It includes API documentation via Swagger and a sample SQL file for database initialization.

## Project Structure
```
Restaurants/
├── .github/           # GitHub workflows and templates
├── assets/            # SQL scripts and Swagger API documentation
├── src/               # Source code (currently empty)
├── tests/             # Test cases
├── Restaurants.sln    # .NET Solution file
├── .gitignore         # Git ignore rules
├── .gitattributes     # Git attributes file
```

## Prerequisites
- .NET SDK
- SQL Server or a compatible database system

## Setup Instructions
1. Clone the repository:
   ```sh
   git clone <repository-url>
   cd Restaurants
   ```
2. Open the `Restaurants.sln` file in Visual Studio or your preferred IDE.
3. Restore dependencies:
   ```sh
   dotnet restore
   ```
4. Run the project:
   ```sh
   dotnet run
   ```

## Database Setup
1. Use the provided SQL file to initialize the database:
   ```sh
   SQL Server Management Studio (SSMS) or any SQL tool
   Execute `assets/INSERT Restaurants.sql`
   ```

## API Documentation
- The API is documented using **Swagger**.
- Open `swagger.json` in the `assets/` folder or run the application and navigate to:
  ```
  http://localhost:<port>/swagger
  ```

## Testing
Run unit tests using:
```sh
 dotnet test
```


