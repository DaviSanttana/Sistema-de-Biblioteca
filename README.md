# 📚 Sistema de Biblioteca em Java

Projeto de sistema simples de **Biblioteca** desenvolvido em Java, aplicando conceitos de **Orientação a Objetos** como **Herança**, **Polimorfismo** e **Encapsulamento**.
## 🚀 Funcionalidades
- 📖 Cadastrar livros (com título e ano).
- 👤 Cadastrar usuários (Aluno ou Professor).
- 📋 Listar livros e usuários.
- 📕 Emprestar livros (seguindo regras de limite).
- 📗 Devolver livros.

## 🛠 Tecnologias
- **Java 17+**
- **Paradigma Orientado a Objetos**
- **ArrayList** para armazenamento em memória

## 📂 Estrutura de Pacotes

Projetos.Biblioteca
├── app
│ └── TestBase01.java # Classe principal (menu interativo)
├── modelo
│ ├── Livro.java # Representa um livro
│ ├── Usuarios.java # Classe base
│ ├── Aluno.java # Subclasse de Usuarios
│ └── Professor.java # Subclasse de Usuarios
└── servico
└── Biblioteca.java # Regras de negócio


## ▶️ Como executar
1. Clone o repositório:
   ```bash
   git clone https://github.com/seuusuario/biblioteca-java.git

 ✨ Demonstração (menu interativo)  
   O que Deseja fazer:
1 - Listar livros
2 - Cadastrar livro
3 - Cadastrar Usuario
4 - Emprestar livro
5 - Devolver livro
6 - Listar Usuarios
0 - Sair

📌 Aprendizados
Esse projeto foi importante para consolidar:
Uso de listas (ArrayList).
Aplicação de polimorfismo para tratar Alunos e Professores de forma diferente.
Implementação de regras de negócio (limite de empréstimos).
Estruturação de código em camadas.

