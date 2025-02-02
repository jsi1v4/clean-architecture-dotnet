# Clean Architecture + .NET

API and web UI built with .NET and clean architecture 🖖.

![**Preview**](preview.png)

## Sobre

Utilizei este CRUD para aplicar meus estudos da plataforma .NET e clean architecture. Com ela conseguimos criar produtos e categorias numa plataforma.

## Requisitos

- [.NET 5](https://dotnet.microsoft.com)

## Tecnologias utilizadas

O projeto foi desenvolvido utilizando as seguintes tecnologias:

- [.NET 5](https://dotnet.microsoft.com)
- [Entity Framework Core](https://learn.microsoft.com/pt-br/ef/core/)
- [Identity](https://learn.microsoft.com/pt-br/aspnet/core/security/authentication/identity)
- [AutoMapper](https://docs.automapper.org/en/stable/Getting-started.html)
- [MediatR](https://github.com/jbogard/MediatR)
- [Swagger](https://github.com/domaindrivendev/Swashbuckle.AspNetCore)

## Como baixar e executar o projeto

### Clonar o repo

```sh
git clone https://github.com/jsi1v4/clean-architecture-dotnet
```

### Instalar dependências

```sh
dotnet restore
```

### Executar em localhost

```sh
# Migrations
dotnet ef --project CleanArchMvc.Infra.Data/CleanArchMvc.Infra.Data.csproj database update
```

```sh
# WebUI
dotnet run --project CleanArchMvc.WebUI/CleanArchMvc.WebUI.csproj
# API
dotnet run --project CleanArchMvc.API/CleanArchMvc.API.csproj
```

> run in http://localhost:5000

### Buildar projeto

```sh
dotnet build
```

---

Keep calm and code on 🤘.
