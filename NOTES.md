# Crud - .Net 8  

### Install

 - https://learn.microsoft.com/pt-br/dotnet/core/install/windows

 - https://docs.docker.com/guides/getting-started/get-docker-desktop/

### Architecture

 - https://medium.com/luizalabs/descomplicando-a-clean-architecture-cf4dfc4a1ac6

### Tutorial

 - https://rimazmohommed523.medium.com/containerize-a-net-core-web-api-app-with-docker-2cdba52a8978

 - https://medium.com/@hugo_cesar45/asp-net-core-web-api-net-8-docker-mongodb-8fab9a54f72c

### Commands

 - List Project Templates

```
dotnet new list
```

 - Create WebApi Project

```
dotnet new webapi

dotnet new webapi -o Crud 
```

 - Run Project

```
dotnet run

dotnet run --project /Users/lucasalves/desktop/code/c/Crud/Crud.csproj
```

### Docker

 - Install

```
dotnet new console -o App -n DotNet.Docker
```

 - Build

```
docker compose up --build
```

 - Run

```
docker compose up 
```


