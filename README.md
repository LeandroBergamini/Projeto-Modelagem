# Trabalho State API

## 🤖 Começando

## Configuração do Projeto

Fazer a clonagem do repositório, clone o repositório para sua máquina local usando o Git: bash git clone

Em sequência faça os seguintes passos configure a String de Conexão Abra o arquivo appsettings.json e configure a string de conexão para o PostgreSQL em ConnectionStrings.DefaultConnection.
Substitua as partes Host, Database, Username e Password com as informações do seu servidor PostgreSQL: json { "ConnectionStrings": { "DefaultConnection": "Host=localhost;Database=TaskDb;Username=seu-usuario;Password=sua-senha" } }.

# 💻 Requisitos 
## Baixar ou ter o Visual Studio com versão 7.0 do .NET para não ter nenhum erro ou problema subsequente.

Baixar as ferramentas do Pacote Nuget:
Microsoft.AspNetCore.OpenApi Versão 7.0.
Microsoft.EntityFrameworkCore Versão 7.0.
Microsoft.EntityFrameworkCore.Tools Versão 7.0.
Npgsql Versão 7.0.
Npgsql.EntityFrameworkCore.PostgreSQL Versão 7.0.
Swashbuckle.AspNetCore Versão mais atual.
