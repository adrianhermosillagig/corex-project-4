# corex-project-4
This project was used to explore Docker's capabilities with a .NET application. The key concepts tested include:

- Creating a Docker image: Demonstrating two methods:
  - Using the integrated .NET tools (dotnet publish /p:PublishProfile=DefaultContainer) for a simplified, no-Dockerfile approach.
  - Creating a custom Dockerfile for greater control over the image build process.

- Running the container: Utilizing both a single command (docker run) and a multi-container orchestration tool (docker compose).
