# 📦 Sistema de Controle de Materiais

Aplicação Console desenvolvida em **C# e .NET** como projeto educacional do curso **Programador de Sistemas — SENAC/SE**.

O projeto demonstra a evolução dos conceitos fundamentais da programação para a construção de uma aplicação mais estruturada, integrando **Programação Orientada a Objetos, coleções, operações CRUD e persistência de dados com SQLite**.

---

## 🎯 Objetivo do Projeto

O objetivo é desenvolver um sistema capaz de realizar o gerenciamento de materiais através de uma aplicação executada no Console.

O projeto permite aplicar, em um mesmo sistema, diversos conceitos estudados durante as aulas, mostrando como conteúdos aprendidos separadamente podem trabalhar juntos na construção de uma aplicação.

---

## ⚙️ Funcionalidades

O sistema implementa operações relacionadas ao gerenciamento de materiais, incluindo:

- cadastro de materiais;
- listagem de registros;
- pesquisa de materiais;
- alteração de informações;
- exclusão de registros;
- validação de dados;
- interação através de menu no Console;
- persistência das informações utilizando SQLite.

Essas operações representam os principais conceitos de um **CRUD**:

```text
CREATE  → Cadastrar
READ    → Consultar / Listar
UPDATE  → Alterar
DELETE  → Excluir
```

---

## 🧠 Conceitos Trabalhados

Durante o desenvolvimento deste projeto são utilizados conceitos como:

- classes e objetos;
- atributos e propriedades;
- métodos;
- Programação Orientada a Objetos;
- estruturas condicionais;
- estruturas de repetição;
- `List<T>`;
- menus interativos;
- entrada e saída de dados;
- validação de informações;
- organização do código em múltiplas classes;
- operações CRUD;
- banco de dados;
- persistência de dados com SQLite.

---

## 📂 Estrutura do Projeto

```text
SistemaControleMateriais/
│
├── BancoDados.cs
├── Materiais.cs
├── Program.cs
├── Sistemas.cs
├── SistemaControleMateriais.csproj
│
└── README.md
```

### `Program.cs`

Ponto de entrada da aplicação.

Responsável por iniciar a execução do sistema.

### `Materiais.cs`

Representa os dados e características relacionadas aos materiais manipulados pela aplicação.

É parte da modelagem das informações utilizadas pelo sistema.

### `Sistemas.cs`

Concentra a lógica utilizada para controlar as operações disponíveis no sistema, incluindo as funcionalidades relacionadas ao gerenciamento dos materiais.

### `BancoDados.cs`

Responsável pelas operações relacionadas à persistência das informações utilizando o banco de dados **SQLite**.

### `SistemaControleMateriais.csproj`

Arquivo de configuração do projeto .NET, contendo as informações necessárias para compilação e gerenciamento das dependências da aplicação.

---

## 🗃️ Persistência de Dados

O projeto utiliza **SQLite** para armazenar as informações cadastradas.

A utilização de um banco de dados permite que os registros não existam apenas durante a execução da aplicação, introduzindo aos alunos o conceito de **persistência de dados**.

```text
Aplicação Console
       │
       ▼
Lógica do Sistema
       │
       ▼
Operações CRUD
       │
       ▼
Banco de Dados SQLite
```

---

## ▶️ Como Executar

Para executar o projeto é necessário possuir o **.NET SDK** instalado.

Também é possível utilizar o **GitHub Codespaces**, que disponibiliza um ambiente de desenvolvimento diretamente pelo navegador.

Dentro da pasta do projeto, execute:

```bash
dotnet restore
```

Depois:

```bash
dotnet build
```

E finalmente:

```bash
dotnet run
```

---

## 📚 Evolução Didática

Este projeto representa uma etapa importante na evolução dos conteúdos trabalhados no curso.

```text
Fundamentos de C#
       ↓
Estruturas Condicionais
       ↓
Estruturas de Repetição
       ↓
Classes e Objetos
       ↓
Coleções
       ↓
Aplicação Console
       ↓
CRUD
       ↓
SQLite
       ↓
Sistema Estruturado
```

O aluno deixa de trabalhar apenas com pequenos exercícios isolados e passa a compreender como diferentes conceitos podem ser integrados para formar uma aplicação completa.

---

## 🌐 Continuação do Projeto

Este sistema também possui uma evolução para ambiente Web:

### SistemaControleMateriaisWeb

A versão Web utiliza **ASP.NET Core MVC**, mantendo o conceito de gerenciamento de materiais e transportando a aplicação para uma arquitetura Web.

➡️ [Acessar SistemaControleMateriaisWeb](../SistemaControleMateriaisWeb)

Essa evolução permite comparar duas abordagens:

```text
SistemaControleMateriais
       │
       │ Aplicação Console
       ▼
C# + .NET + SQLite
       │
       │ Evolução
       ▼
SistemaControleMateriaisWeb
       │
       ▼
ASP.NET Core MVC + SQLite
```

---

## 🎓 Finalidade Educacional

Este projeto foi desenvolvido com finalidade educacional e faz parte dos exemplos e atividades utilizados no curso **Programador de Sistemas**.

A proposta é permitir que os alunos compreendam não apenas a sintaxe da linguagem, mas principalmente como organizar diferentes recursos para construir uma aplicação funcional.

> 💡 O código pode ser utilizado como material de consulta, mas a melhor forma de aprender é modificar, testar, experimentar e criar novas funcionalidades.

---

## 👨‍🏫 Autor

**Anderson Domingos**  
Instrutor de Educação Profissional  
**SENAC/SE**

---

<div align="center">

### 💻 C# • .NET • SQLite

**Aprender • Praticar • Desenvolver • Evoluir**

</div>