# Contoso University sample app with MySql/MariaDB setup

Contoso University demonstrates how to use Entity Framework Core in an
ASP.NET Core MVC web application.

## Other dependencies

Package|Version
-|-
ASP.NET Core | 2.1.0
Pomelo.EntityFrameworkCore.MySql| 2.1.0-rc1-final
Z.EntityFramework.Plus.EFCore	| 1.7.20

## Build it

- Install MySql or MariaDB and make sure the connection works with the same connection set on `appsettings.json`.
- `dotnet ef database update` at a command-line prompt. 

As an alternative you can use **Package Manager Console** -- for more information, see [Command-line interface (CLI) vs. Package Manager Console (PMC)](https://docs.microsoft.com/aspnet/core/data/ef-mvc/migrations#command-line-interface-cli-vs-package-manager-console-pmc).


## Original information
- [A series of tutorials](https://docs.microsoft.com/aspnet/core/data/ef-mvc/intro).
- [Original project](https://github.com/aspnet/Docs/tree/master/aspnetcore/data/ef-mvc/intro/samples/cu-final) 
