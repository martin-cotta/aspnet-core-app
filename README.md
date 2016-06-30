# Basic ASP.NET Core App 

#### 1- Upgrade OpenSSL (Mac only)

```sh
brew update
brew install openssl
brew link --force openssl
```

#### 2- Install .NET Core SDK
Install .NET Core using the official installer for [macOS](https://go.microsoft.com/fwlink/?LinkID=809124) or [Windows](https://go.microsoft.com/fwlink/?LinkID=809122)

#### 3- Run the App

```sh
git clone https://github.com/martin-cotta/aspnet-core-app.git
cd aspnet-core-app
dotnet restore
dotnet run
```
Open a Web browser at `http://localhost:5000/`
