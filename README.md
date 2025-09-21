# Blazor Server App

A simple **Blazor Server** application using .NET 8.0.  
This project demonstrates basic interactive UI components (counter example with increment and decrement), Razor components, and server-side rendering using Blazor.

---

## 📁 Repository Structure

| Folder/File | Description |
|-------------|-------------|
| `BlazorServerApp.sln` | Solution file that includes the project. |
| `BlazorServerApp.csproj` | The project file with dependencies and settings. |
| `Program.cs` | Entry point—configures the web app, adds services, routing, etc. |
| `appsettings.json` | Configuration settings (e.g. for logging, etc.). |
| `Properties` | Project properties (AssemblyInfo etc.). |
| `wwwroot` | Static assets: CSS, JavaScript, images. |
| `bin/`, `obj/` | Build output and intermediate files. |
| `Components/` | (If present) Razor components for modular UI pieces. |

---

## 🚀 Getting Started

These instructions will help you get a local copy up and running.

### Prerequisites

- [.NET 8.0 SDK](https://dotnet.microsoft.com/download/dotnet/8.0) installed.
- A code editor or IDE that supports .NET and Blazor (e.g. Visual Studio, VS Code).
- (Optional) Git, for cloning the repo.

### Clone & Run

```bash
git clone https://github.com/rashedulalam46/blazor-server-app.git
cd blazor-server-app
dotnet restore
dotnet build
dotnet run
