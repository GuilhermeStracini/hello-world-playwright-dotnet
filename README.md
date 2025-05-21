# Playwright Hello World (.NET)

🚀 Minimal C# .NET project to explore browser automation using Microsoft Playwright.

## 📦 Technologies

- .NET 8
- Microsoft.Playwright
- XUnit for tests
- Docker for containerization
- GitHub Actions for CI

## 🛠 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/PlaywrightHelloWorld.git
cd PlaywrightHelloWorld
````

### 2. Install tools

```bash
dotnet tool install --global Microsoft.Playwright.CLI
dotnet restore
playwright install
```

### 3. Run the app

```bash
dotnet run --project PlaywrightHelloWorld
```

## 🧪 Run Tests

```bash
dotnet test PlaywrightHelloWorld.Tests
```

## 🐳 Run with Docker

```bash
docker build -t playwright-hello .
docker run --rm playwright-hello
```

## 🤖 GitHub Actions

This repo has a GitHub Actions workflow to:

* Install Playwright & dependencies
* Build the .NET app
* Run tests

See: `.github/workflows/playwright.yml`

## 📚 Resources

* [Playwright for .NET Docs](https://playwright.dev/dotnet/docs/intro)
* [XUnit Documentation](https://xunit.net/)
* [Docker for .NET](https://learn.microsoft.com/en-us/dotnet/core/docker/)

---

Happy testing! 🎭🧪🐳
