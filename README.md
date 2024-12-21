# AscendAI

AscendAI is a Blazor-based application that generates personalized tech trees for users pursuing specific goals or skills. By leveraging AI (OpenAI or Azure OpenAI), AscendAI creates dynamic roadmaps, guides progress tracking, and demonstrates how AI can power individualized learning journeys—all within a freemium model.

## Features

- AI-Driven Roadmaps: Gathers user goals and uses AI to create structured tech trees or skill paths.
- Blazor Frontend: Interactive and responsive UI built in C#.
- Progress Tracking: Users can mark completed milestones and visualize their progress.
- Freemium-Friendly: Designed to scale from a free tier to paid tiers with advanced features.

## Architecture

- AscendAI.sln
    - AscendAI.Blazor: Blazor (Server or WebAssembly) frontend.
    - AscendAI.API: ASP.NET Core backend (controllers/Minimal APIs for AI calls, user management, etc.).
    - (Optional) AscendAI.Data: Handles Entity Framework Core logic for database interactions.
    - (Optional) AscendAI.Domain: Core domain entities and business logic.
    - (Optional) AscendAI.Tests: Unit and integration tests.

## Getting Started

1. Clone the Repository
```bash
git clone https://github.com/your-username/ascend-ai.git
cd ascend-ai
```
2. Open the Solution
- Launch AscendAI.sln in Visual Studio (or your preferred IDE).
3. Set Up Dependencies
- Install the required .NET SDK (v7 or higher recommended).
- Configure any environment variables or secrets (e.g., OpenAI API key).
4. Build and Run
- Blazor Server: Press F5 (or dotnet run from the project folder).
- Blazor WebAssembly: Ensure both the client and server projects run simultaneously.
5. Access the App
- Open your browser at https://localhost:<port> to see the app in action.

## Contributing

We welcome issues, pull requests, and suggestions. To contribute:

1. Fork the repository.
2. Create a new branch: git checkout -b feature/my-new-feature.
3. Commit changes: git commit -m 'Add my feature'.
4. Push your branch: git push origin feature/my-new-feature.
5. Create a Pull Request against the main branch.

## License

This project is licensed under the MIT License. See the LICENSE file for details.