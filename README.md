<div align="center">

# 💻 Programador de Sistemas — SENAC/SE

### C# • .NET • ASP.NET Core MVC • SQLite

Repositório educacional com **exercícios resolvidos e projetos práticos** desenvolvidos durante as aulas do curso **Programador de Sistemas**.

Da introdução à linguagem C# até a construção de aplicações Console e Web com persistência de dados.

</div>

---

## 🚀 Uma trilha prática de desenvolvimento

Este repositório acompanha uma progressão de aprendizagem, reunindo exemplos e projetos que demonstram a evolução dos principais conceitos trabalhados em aula:

**Fundamentos → Lógica → C# → POO → CRUD → SQLite → ASP.NET Core MVC**

Os projetos foram organizados para permitir que o aluno acompanhe essa evolução de forma prática, consultando códigos desenvolvidos durante as aulas e experimentando novas implementações.

---

## 📂 Estrutura do Repositório

```text
programador-sistema-senac/
│
├── ExerciciosResolvidos/
│   │
│   ├── ExemploSe/
│   │   ├── ExemploSe.csproj
│   │   └── Program.cs
│   │
│   ├── RespostaLista01/
│   │   ├── RespostaLista01.csproj
│   │   └── Program.cs
│   │
│   ├── RespostaLista02/
│   │   ├── RespostaLista02.csproj
│   │   └── Program.cs
│   │
│   ├── ListaClasses/
│   │   ├── ControleBanco.csproj
│   │   └── Program.cs
│   │
│   ├── SistemaControleMateriais/
│   │   ├── BancoDados.cs
│   │   ├── Materiais.cs
│   │   ├── Program.cs
│   │   ├── Sistemas.cs
│   │   ├── SistemaControleMateriais.csproj
│   │   └── README.md
│   │
│   └── SistemaControleMateriaisWeb/
│       ├── Controllers/
│       ├── Data/
│       ├── Models/
│       ├── Views/
│       ├── Program.cs
│       ├── SistemaControleMateriaisWeb.csproj
│       └── README.md
│
├── .gitignore
└── README.md
```

---

# 📚 Exercícios e Projetos Disponíveis

## 1️⃣ ExemploSe

Projeto introdutório utilizado para trabalhar **estruturas condicionais** em C#.

### Conceitos abordados

- `if`;
- `else`;
- `else if`;
- operadores de comparação;
- tomada de decisão;
- verificação de números pares e ímpares;
- identificação de valores positivos, negativos ou zero.

Este projeto introduz um dos conceitos fundamentais da lógica de programação: **fazer o programa tomar decisões de acordo com determinadas condições**.

📁 [`ExemploSe`](./ExerciciosResolvidos/ExemploSe)

---

## 2️⃣ RespostaLista01

Lista de exercícios introdutórios voltada aos primeiros contatos com a linguagem **C#**.

### Conceitos abordados

- declaração de variáveis;
- tipos de dados;
- `string`;
- `int`;
- `decimal`;
- `char`;
- entrada de dados pelo Console;
- saída de informações;
- conversão de valores;
- interpolação de strings;
- operações básicas.

O projeto ajuda a consolidar os fundamentos necessários para a construção dos primeiros programas em C#.

📁 [`RespostaLista01`](./ExerciciosResolvidos/RespostaLista01)

---

## 3️⃣ RespostaLista02

Exercícios voltados à utilização de **operadores e cálculos matemáticos**.

### Conceitos abordados

- soma;
- subtração;
- multiplicação;
- média;
- dobro;
- metade;
- porcentagens;
- descontos;
- manipulação de valores numéricos.

Esta etapa amplia o uso de variáveis e operadores na resolução de pequenos problemas computacionais.

📁 [`RespostaLista02`](./ExerciciosResolvidos/RespostaLista02)

---

## 4️⃣ ListaClasses

Projeto utilizado para introduzir conceitos de **Programação Orientada a Objetos — POO**.

A aplicação utiliza como exemplo uma conta bancária para demonstrar a criação e utilização de objetos.

### Conceitos abordados

- classes;
- propriedades;
- métodos;
- criação de objetos;
- alteração do estado de objetos;
- depósito;
- saque;
- consulta de saldo;
- validações;
- `switch`;
- `do/while`.

Este projeto representa a transição entre programas escritos apenas de forma sequencial e aplicações organizadas através de **classes e objetos**.

📁 [`ListaClasses`](./ExerciciosResolvidos/ListaClasses)

---

# 📦 5️⃣ Sistema de Controle de Materiais — Console

O `SistemaControleMateriais` representa uma evolução importante dentro da trilha de aprendizagem.

Neste projeto, diversos conceitos estudados anteriormente passam a trabalhar juntos em uma aplicação mais estruturada.

### Tecnologias

- C#;
- .NET;
- SQLite.

### Conceitos abordados

- Programação Orientada a Objetos;
- múltiplas classes;
- métodos;
- estruturas condicionais;
- estruturas de repetição;
- `List<T>`;
- menus interativos;
- validação de dados;
- pesquisa de registros;
- cadastro;
- alteração;
- exclusão;
- listagem;
- operações CRUD;
- persistência de dados;
- SQLite.

### CRUD

```text
CREATE  → Cadastrar
READ    → Consultar / Listar
UPDATE  → Alterar
DELETE  → Excluir
```

O projeto permite compreender como diferentes recursos da linguagem podem ser integrados para formar uma aplicação funcional.

### 📖 Documentação completa

➡️ [`SistemaControleMateriais`](./ExerciciosResolvidos/SistemaControleMateriais)

➡️ [`README do projeto`](./ExerciciosResolvidos/SistemaControleMateriais/README.md)

---

# 🌐 6️⃣ Sistema de Controle de Materiais — Web

O `SistemaControleMateriaisWeb` representa a evolução da aplicação Console para uma aplicação Web utilizando **ASP.NET Core MVC**.

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

### Tecnologias

- C#;
- .NET;
- ASP.NET Core;
- ASP.NET Core MVC;
- Razor;
- SQLite;
- HTML;
- CSS.

### Conceitos abordados

- desenvolvimento Web;
- arquitetura MVC;
- Models;
- Views;
- Controllers;
- Razor Views;
- rotas;
- Actions;
- formulários;
- Data Annotations;
- validação;
- injeção de dependência;
- operações CRUD;
- persistência de dados;
- SQLite;
- separação de responsabilidades.

### Estrutura MVC

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

### 📖 Documentação completa

➡️ [`SistemaControleMateriaisWeb`](./ExerciciosResolvidos/SistemaControleMateriaisWeb)

➡️ [`README do projeto`](./ExerciciosResolvidos/SistemaControleMateriaisWeb/README.md)

---

# 🗺️ Trilha de Aprendizagem

Os projetos deste repositório podem ser observados como etapas de uma mesma evolução:

```text
Fundamentos de Programação
           │
           ▼
    Variáveis e Tipos
           │
           ▼
 Operadores e Cálculos
           │
           ▼
Estruturas Condicionais
           │
           ▼
Programação Orientada
      a Objetos
           │
           ▼
       Coleções
           │
           ▼
  Aplicações Console
           │
           ▼
          CRUD
           │
           ▼
        SQLite
           │
           ▼
SistemaControleMateriais
           │
           ▼
     ASP.NET Core
           │
           ▼
          MVC
           │
           ▼
SistemaControleMateriaisWeb
```

Essa sequência demonstra como conteúdos inicialmente simples podem ser combinados progressivamente até a construção de aplicações mais completas.

---

# 🧠 Conteúdos Trabalhados

Ao longo dos exercícios e projetos são explorados conteúdos como:

### Fundamentos

- lógica de programação;
- algoritmos;
- variáveis;
- tipos de dados;
- operadores;
- entrada e saída de dados;
- conversões;
- interpolação de strings.

### Estruturas de Controle

- condicionais;
- `if`;
- `else`;
- `else if`;
- `switch`;
- estruturas de repetição;
- `while`;
- `do/while`.

### Programação Orientada a Objetos

- classes;
- objetos;
- propriedades;
- métodos;
- organização de responsabilidades.

### Coleções e Dados

- `List<T>`;
- manipulação de registros;
- validações;
- operações CRUD;
- persistência;
- SQLite.

### Desenvolvimento Web

- ASP.NET Core;
- MVC;
- Controllers;
- Models;
- Views;
- Razor;
- rotas;
- formulários;
- Data Annotations;
- injeção de dependência.

---

# 🛠️ Tecnologias e Ferramentas

<div align="center">

![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=csharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)

</div>

### Ambiente de desenvolvimento

Os projetos podem ser utilizados com:

- Visual Studio Code;
- Git;
- GitHub;
- GitHub Codespaces;
- .NET SDK.

O **GitHub Codespaces** permite executar os projetos diretamente em um ambiente de desenvolvimento disponibilizado pelo navegador.

---

# 🚀 Como utilizar este repositório

Clone o repositório:

```bash
git clone https://github.com/andersondom/programador-sistema-senac.git
```

Entre na pasta:

```bash
cd programador-sistema-senac
```

Acesse o diretório dos exercícios:

```bash
cd ExerciciosResolvidos
```

Escolha um dos projetos.

Por exemplo:

```bash
cd SistemaControleMateriais
```

Restaure as dependências:

```bash
dotnet restore
```

Compile:

```bash
dotnet build
```

Execute:

```bash
dotnet run
```

---

# 🎯 Objetivo Educacional

Este repositório foi organizado para funcionar como **material de apoio às aulas e ambiente de consulta para os alunos**.

A proposta não é apenas disponibilizar códigos prontos.

O objetivo é permitir que os exemplos sejam utilizados para:

- revisar conteúdos trabalhados em aula;
- compreender a estrutura das aplicações;
- analisar soluções;
- modificar códigos existentes;
- experimentar novas implementações;
- criar novas funcionalidades;
- acompanhar a evolução entre diferentes tipos de aplicações.

> 💡 **A melhor forma de aprender programação é praticando.**
>
> Leia o código, execute, modifique, provoque erros, corrija e experimente novas soluções.

---

# 📈 Evolução dos Projetos

Uma das propostas deste repositório é demonstrar que o desenvolvimento de software acontece de forma progressiva.

```text
Pequenos exercícios
        ↓
Resolução de problemas
        ↓
Estruturas de decisão
        ↓
Classes e objetos
        ↓
Aplicações estruturadas
        ↓
Persistência de dados
        ↓
CRUD
        ↓
Aplicações Web
```

Cada novo projeto utiliza conhecimentos desenvolvidos nas etapas anteriores.

---

# 👨‍🏫 Sobre o Repositório

Este material é utilizado como apoio às atividades educacionais do curso **Programador de Sistemas**.

Os códigos representam exemplos, exercícios resolvidos e projetos utilizados para demonstrar conceitos de desenvolvimento de software de forma progressiva e prática.

---

# 👨‍💻 Autor

**Anderson Domingos**  
Instrutor de Educação Profissional  
**SENAC/SE**

[![GitHub](https://img.shields.io/badge/GitHub-andersondom-181717?style=for-the-badge&logo=github)](https://github.com/andersondom)

---

<div align="center">

### 💻 C# • .NET • ASP.NET Core MVC • SQLite

**Aprender • Praticar • Desenvolver • Evoluir**

<br>

⭐ Se este material foi útil para seus estudos, considere deixar uma estrela no repositório.

</div>