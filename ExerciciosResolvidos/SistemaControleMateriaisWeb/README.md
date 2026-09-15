# 🌐 Sistema de Controle de Materiais Web

Aplicação Web desenvolvida em **C# com ASP.NET Core MVC**, criada como evolução do projeto Console `SistemaControleMateriais`.

O projeto faz parte do processo de aprendizagem do curso **Programador de Sistemas — SENAC/SE** e demonstra como uma aplicação inicialmente desenvolvida para Console pode evoluir para uma solução Web estruturada utilizando o padrão **MVC (Model-View-Controller)**.

---

## 🎯 Objetivo do Projeto

O principal objetivo deste projeto é apresentar aos alunos a transição entre uma aplicação Console e uma aplicação Web.

A ideia é reaproveitar conceitos já estudados anteriormente, como:

- Programação Orientada a Objetos;
- operações CRUD;
- persistência de dados;
- banco de dados SQLite;
- organização do código em classes;

e introduzir novos conceitos relacionados ao desenvolvimento Web com **ASP.NET Core MVC**.

---

## 🔄 Evolução do Projeto

Este projeto é uma evolução do:

➡️ [SistemaControleMateriais — versão Console](../SistemaControleMateriais)

A proposta permite acompanhar uma mesma ideia sendo implementada em dois ambientes diferentes:

```text
SistemaControleMateriais
        │
        ▼
Aplicação Console
C# + .NET + SQLite
        │
        │ Evolução
        ▼
SistemaControleMateriaisWeb
        │
        ▼
ASP.NET Core MVC
C# + Razor + SQLite
        │
        ▼
Aplicação Web
```

Dessa forma, os alunos podem perceber que vários conceitos aprendidos na aplicação Console continuam existindo no desenvolvimento Web, mas passam a ser organizados de acordo com uma arquitetura diferente.

---

## ⚙️ Funcionalidades

A aplicação permite realizar o gerenciamento de materiais através de uma interface Web.

Entre as principais operações estão:

- cadastro de materiais;
- visualização dos materiais cadastrados;
- consulta de detalhes;
- edição de registros;
- exclusão de materiais;
- validação das informações;
- persistência dos dados utilizando SQLite.

Essas funcionalidades representam as quatro operações fundamentais de um **CRUD**:

```text
CREATE  → Cadastrar
READ    → Consultar / Visualizar
UPDATE  → Editar
DELETE  → Excluir
```

---

# 🏗️ Arquitetura MVC

O projeto utiliza o padrão arquitetural **MVC — Model-View-Controller**.

```text
┌───────────────────┐
│       VIEW        │
│ Interface Web     │
│ Razor / HTML      │
└─────────┬─────────┘
          │
          ▼
┌───────────────────┐
│    CONTROLLER     │
│ Requisições e     │
│ fluxo da aplicação│
└─────────┬─────────┘
          │
          ▼
┌───────────────────┐
│       MODEL       │
│ Dados e regras    │
└─────────┬─────────┘
          │
          ▼
┌───────────────────┐
│      SQLite       │
│ Persistência      │
└───────────────────┘
```

Essa separação ajuda a organizar as responsabilidades da aplicação.

---

## 📂 Estrutura do Projeto

```text
SistemaControleMateriaisWeb/
│
├── Controllers/
│   ├── HomeController.cs
│   └── MateriaisController.cs
│
├── Data/
│   └── BancoDados.cs
│
├── Models/
│   ├── DashboardViewModel.cs
│   ├── ErrorViewModel.cs
│   └── Material.cs
│
├── Properties/
│   └── launchSettings.json
│
├── Views/
│   ├── Home/
│   ├── Materiais/
│   └── Shared/
│
├── Program.cs
├── appsettings.json
├── appsettings.Development.json
├── SistemaControleMateriaisWeb.csproj
└── README.md
```

---

# 🎮 Controllers

Os **Controllers** recebem as requisições realizadas pelo usuário e controlam o fluxo da aplicação.

## `HomeController.cs`

Responsável pelas funcionalidades relacionadas à página inicial da aplicação.

## `MateriaisController.cs`

Responsável pelas operações relacionadas ao gerenciamento dos materiais.

Nele estão concentradas as ações necessárias para executar operações como:

```text
Listar
   │
   ├── Cadastrar
   │
   ├── Visualizar
   │
   ├── Editar
   │
   └── Excluir
```

O Controller funciona como intermediário entre a interface apresentada ao usuário e os dados manipulados pela aplicação.

---

# 📦 Models

Os **Models** representam os dados utilizados pelo sistema.

## `Material.cs`

Representa um material cadastrado na aplicação.

O Model define as informações que caracterizam cada registro e pode utilizar **Data Annotations** para definir regras de validação.

## `DashboardViewModel.cs`

ViewModel utilizado para organizar informações que precisam ser apresentadas pela aplicação.

O uso de ViewModels permite preparar dados específicos para determinadas interfaces sem modificar diretamente o modelo principal.

## `ErrorViewModel.cs`

Model utilizado para tratamento e apresentação de informações relacionadas a erros da aplicação.

---

# 🗃️ Camada de Dados

## `BancoDados.cs`

Responsável pelas operações relacionadas à persistência das informações.

O projeto utiliza **SQLite**, permitindo que os materiais cadastrados sejam armazenados e recuperados posteriormente.

```text
Interface Web
      │
      ▼
Controller
      │
      ▼
Model
      │
      ▼
BancoDados
      │
      ▼
SQLite
```

---

# 🖥️ Views

As **Views** são responsáveis pela interface apresentada no navegador.

O projeto utiliza **Razor Views (`.cshtml`)**, permitindo combinar HTML com recursos fornecidos pelo ASP.NET Core.

A pasta `Views/Materiais` contém interfaces relacionadas às operações do CRUD.

```text
Views/
│
├── Home/
│   ├── Index.cshtml
│   └── Privacy.cshtml
│
├── Materiais/
│   ├── Create.cshtml
│   ├── Delete.cshtml
│   ├── Details.cshtml
│   ├── Edit.cshtml
│   └── Index.cshtml
│
└── Shared/
    ├── Error.cshtml
    ├── _Layout.cshtml
    ├── _Layout.cshtml.css
    └── _ValidationScriptsPartial.cshtml
```

### `Index.cshtml`

Apresenta a listagem dos materiais.

### `Create.cshtml`

Interface utilizada para cadastrar um novo material.

### `Details.cshtml`

Apresenta os detalhes de um registro.

### `Edit.cshtml`

Permite alterar as informações de um material.

### `Delete.cshtml`

Permite confirmar a exclusão de um registro.

---

# 🧠 Conceitos Trabalhados

O projeto permite trabalhar conceitos como:

- C#;
- .NET;
- ASP.NET Core;
- desenvolvimento Web;
- padrão MVC;
- Models;
- Views;
- Controllers;
- Razor;
- rotas;
- Actions;
- formulários Web;
- Data Annotations;
- validação de dados;
- injeção de dependência;
- Programação Orientada a Objetos;
- operações CRUD;
- persistência de dados;
- SQLite;
- separação de responsabilidades.

---

# 🔁 Fluxo de uma Requisição

De forma simplificada, uma operação realizada pelo usuário percorre o seguinte caminho:

```text
Usuário
   │
   ▼
Navegador
   │
   ▼
Rota
   │
   ▼
Controller
   │
   ▼
Model / Banco de Dados
   │
   ▼
Controller
   │
   ▼
View
   │
   ▼
Navegador
```

Esse fluxo ajuda a compreender como uma aplicação ASP.NET Core MVC recebe uma solicitação, processa os dados e devolve uma interface ao usuário.

---

# ▶️ Como Executar

Para executar o projeto é necessário possuir o **.NET SDK** instalado.

Também é possível utilizar o **GitHub Codespaces**.

Dentro da pasta `SistemaControleMateriaisWeb`, execute:

```bash
dotnet restore
```

Em seguida:

```bash
dotnet build
```

Depois:

```bash
dotnet run
```

O terminal informará o endereço utilizado pela aplicação.

Ao utilizar o GitHub Codespaces, a porta utilizada pela aplicação poderá ser encaminhada automaticamente para permitir o acesso através do navegador.

---

# 📚 Evolução Didática

O `SistemaControleMateriaisWeb` representa uma etapa mais avançada da sequência de aprendizagem presente neste repositório.

```text
Fundamentos de C#
       ↓
Condicionais
       ↓
Estruturas de Repetição
       ↓
Programação Orientada a Objetos
       ↓
Coleções
       ↓
Aplicação Console
       ↓
CRUD
       ↓
SQLite
       ↓
SistemaControleMateriais
       ↓
ASP.NET Core
       ↓
MVC
       ↓
SistemaControleMateriaisWeb
```

Essa evolução permite que o aluno compreenda que o desenvolvimento Web não substitui os conhecimentos anteriores.

Pelo contrário: **os fundamentos aprendidos anteriormente passam a fazer parte de aplicações cada vez mais completas.**

---

# 🎓 Finalidade Educacional

Este projeto possui finalidade educacional e foi desenvolvido como parte dos exemplos utilizados no curso **Programador de Sistemas**.

A proposta é permitir que os alunos visualizem na prática a evolução:

**Lógica → C# → POO → CRUD → Banco de Dados → Web → MVC**

Mais do que utilizar um sistema pronto, o objetivo é compreender como cada parte da aplicação se relaciona com as demais.

> 💡 Explore o código, modifique as Views, crie novos campos, altere as regras e experimente novas funcionalidades. É através da prática que os conceitos começam a fazer sentido.

---

# 👨‍🏫 Autor

**Anderson Domingos**  
Instrutor de Educação Profissional  
**SENAC/SE**

---

<div align="center">

### 🌐 ASP.NET Core MVC • C# • SQLite

**Do Console para a Web. Da lógica para aplicações completas.**

</div>