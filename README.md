# Genesys

Genesys is a sample ASP.NET Core Razor Pages application. It demonstrates a simple web app structure and is intended for learning and demonstration purposes, including basic usage of Git.

## Features
- ASP.NET Core 9.0
- Razor Pages
- Static assets (CSS, JS, images)
- Basic error handling
- HTTPS redirection

## Getting Started

### Prerequisites
- [.NET 9.0 SDK](https://dotnet.microsoft.com/download/dotnet/9.0)

### Running the Application

1. Clone the repository:
   ```pwsh
   git clone <repository-url>
   cd Genesys
   ```
2. Restore dependencies:
   ```pwsh
   dotnet restore
   ```
3. Build the project:
   ```pwsh
   dotnet build
   ```
4. Run the application:
   ```pwsh
   dotnet run
   ```
5. Open your browser and navigate to `https://localhost:5001` (or the URL shown in the console).

## Project Structure
- `Program.cs` - Main entry point, configures services and middleware.
- `Pages/` - Razor Pages (UI and code-behind).
- `wwwroot/` - Static files (CSS, JS, images).
- `appsettings.json` - Application configuration.
- `Genesys.csproj` - Project file.

## Screenshot
![Screenshot](wwwroot/logo.png)

## License
This project is for demonstration purposes only.
