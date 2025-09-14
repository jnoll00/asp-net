# Blazor Counter Application

A modern web application built with Blazor, demonstrating interactive web UI components using C# and .NET 9.0.

## 🚀 Features

- Interactive counter component with customizable increment
- Real-time UI updates without page refreshes
- Clean and responsive design using Bootstrap
- Built with Blazor's component-based architecture

## 📋 Prerequisites

- [.NET 9.0 SDK](https://dotnet.microsoft.com/download)
- A modern web browser
- Visual Studio 2022 or Visual Studio Code

## 🛠️ Installation

1. Clone the repository
   ```bash
   git clone https://github.com/jnoll00/asp-net.git
   cd asp-net
   ```

2. Build the project
   ```bash
   dotnet build
   ```

3. Run the application
   ```bash
   dotnet run --project BlazorApp/BlazorApp.csproj
   ```

4. Open your web browser and navigate to `https://localhost:5001` or `http://localhost:5000`

## 🏗️ Project Structure

```
BlazorApp/
├── Components/           # Blazor components
│   ├── Pages/          # Page components
│   └── Layout/         # Layout components
├── wwwroot/            # Static files
└── Program.cs          # Application entry point
```

## 💻 Usage

The application demonstrates a simple counter functionality:
- Navigate to the Counter page
- Click the "Click me" button to increment the counter
- Customize the increment amount using the input field

## 🔧 Development

To start development:

1. Open the solution in your preferred IDE
2. Make changes to the components in the `Components` folder
3. The hot reload feature will automatically update your browser

## 🧪 Running Tests

```bash
dotnet test
```

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## ✨ Acknowledgments

- Built with [Blazor](https://dotnet.microsoft.com/apps/aspnet/web-apps/blazor)
- Styled with [Bootstrap](https://getbootstrap.com/)
