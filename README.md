# MeuPrimeiroBlazor

Projeto de estudos desenvolvido para praticar os fundamentos do Blazor com ASP.NET Core.

## Sobre o projeto

Esta aplicação é um Blazor Web App com renderização interativa no servidor. O projeto contém páginas de exemplo para praticar a criação de componentes Razor, navegação entre páginas e uso de dados no componente inicial.

Atualmente, a página inicial apresenta uma mensagem de teste com nome e idade definidos no componente. Também estão disponíveis exemplos de contador e previsão do tempo.

## Tecnologias

- .NET 10
- ASP.NET Core
- Blazor Web App
- Razor Components
- Bootstrap

## Pré-requisitos

- SDK do .NET 10 instalado
- Um navegador atualizado

Para confirmar a instalação do SDK:

```bash
dotnet --version
```

## Como executar

1. Abra um terminal na pasta do projeto.
2. Restaure as dependências e execute a aplicação:

```bash
dotnet run
```

3. Acesse a URL indicada no terminal, normalmente:

```text
https://localhost:xxxx
```

Para executar em modo de desenvolvimento usando o perfil configurado:

```bash
dotnet watch
```

## Estrutura principal

```text
MeuPrimeiroBlazor/
├── Components/
│   ├── Layout/       # Layout e menu de navegação
│   └── Pages/        # Páginas Razor da aplicação
├── Properties/       # Configurações de inicialização
├── wwwroot/          # Arquivos estáticos e estilos
├── Program.cs        # Configuração da aplicação
└── MeuPrimeiroBlazor.csproj
```

## Páginas disponíveis

- `/` - Página inicial
- `/counter` - Exemplo de contador interativo
- `/weather` - Exemplo de previsão do tempo

## Objetivo acadêmico

Este repositório faz parte das atividades práticas da faculdade e serve como base para experimentar componentes, eventos, navegação e recursos do Blazor.