# ASP.NET Core - App Building Workshop

[![Build Status](https://dotnet.visualstudio.com/AspNetCoreWorkshop/_apis/build/status/ASP.NET%20Workshop-ASP.NET%20Core%202.1.1?branchName=master)](https://dotnet.visualstudio.com/AspNetCoreWorkshop/_build/latest?definitionId=32&branchName=master)

[BackEnd Web API](https://aspnetcorews-backend.azurewebsites.net) | [FrontEnd Web App](https://aspnetcorews-frontend.azurewebsites.net)

## Configuração

[Baixe](https://www.microsoft.com/net/download) e instale o .NET Core SDK e o Visual Studio.

> Nota: Ao instalar o Visual Studio, você só precisa instalar o workload `ASP.NET e desenvolvimento da web`.

Se você tiver problemas para baixar os instaladores, podemos ter pen drives com instaladores offline para você usar.

## O que você estará construindo
Neste workshop, você aprenderá criando um aplicativo ASP.NET Core completo do zero. Começaremos em Arquivo/Novo e criaremos um aplicativo de back-end da API, um aplicativo de front-end da Web e uma biblioteca comum para objetos de transferência de dados compartilhados usando o .NET Standard.

### Arquitetura da Aplicação
![Diagrama da arquitetura](/docs/images/ConferencePlannerArchitectureDiagram.svg)

### Schema de Banco de Dados
![Diagrama do Schema de Banco de Dados](/docs/conference-planner-db-diagram.png)

## Sessões

| Sessões | Tópicos |
| ----- | ---- |
| [Sessão #1](/docs/1.%20Create%20BackEnd%20API%20project.md) | Construir a API back-end com o modelo básico do EF |
| [Sessão #2](/docs/2.%20Build%20out%20BackEnd%20and%20Refactor.md) | Concluir a API de back-end e o modelo EF, refatorar para view models |  |
| [Sessão #3](/docs/3.%20Add%20front-end%2C%20render%20agenda%2C%20set%20up%20front-end%20models.md) | Adicionar o front-end, renderizar a agenda, configurar os modelos no front-end |
| [Sessão #4](/docs/4.%20Add%20auth%20features.md) | Adicionar autenticação, adicionar política de administrador, permitir edição de sessões, os usuários podem entrar com Identity, tag helper de autenticação personalizada |
| [Sessão #5](/docs/5.%20Add%20personal%20agenda.md) | Adicionar associação de usuários e agenda pessoal |
| [Sessão #6](docs/6.%20Production%20Readiness%20and%20Deployment.md) | Implantação, Azure e outros ambientes de produção, ambientes de configuração, diagnóstico |
| [Sessão #7](/docs/7.%20Challenges.md) | Desafios |
| [Sessão #8](/docs/8.%20SPA%20FrontEnd.md) | SPA front-end |
