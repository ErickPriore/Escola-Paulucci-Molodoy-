# Escola-Paulucci-Molodoy-
BiblioDesk – Sistema de Controle de Empréstimos

Sistema desktop em Java para controle de empréstimos de uma biblioteca escolar de pequeno porte.

👥 Equipe

Kauan • Matheus • Vinicius • Gustavo • Guilherme • Erick

Versão: 1.0
Data: Março/2026

🏫 Contexto

Biblioteca escolar com aproximadamente 600 alunos e 40 professores, que atualmente realiza o controle de empréstimos de forma manual (planilhas e cadernos).

Problemas Identificados

Perda e inconsistência de dados

Dificuldade para consultar livros disponíveis

Falta de controle eficiente de atrasos

🎯 Objetivo

Digitalizar o controle de empréstimos de forma simples e eficiente, garantindo:

✔ Redução de erros

✔ Controle automático de atrasos

✔ Consulta rápida de disponibilidade

✔ Organização dos registros

🖥️ Tecnologias

Java Desktop

Swing ou JavaFX

Arquitetura Monolítica

Funcionamento Offline

Persistência em memória ou arquivo simples

📌 Escopo do Sistema
✅ Dentro do Escopo

Cadastro de alunos

Cadastro de livros

Registro de empréstimos

Registro de devoluções

Consulta de livros disponíveis

Consulta de empréstimos em atraso

Relatórios simples em tela

❌ Fora do Escopo

Banco de dados (SQL, SQLite etc.)

Back-end separado

Aplicação web

Aplicativo mobile

Integrações externas

⚙️ Requisitos Funcionais

Cadastrar livros

Registrar empréstimo

Registrar devolução

Listar livros disponíveis

Listar empréstimos ativos

📏 Regras de Negócio

📘 Livro só pode ser emprestado se estiver disponível

👤 Máximo de 3 livros por aluno

⏳ Prazo padrão de 7 dias

⚠ Empréstimo entra em atraso após 7 dias

🚫 Não é permitido excluir aluno com empréstimo ativo

🗂️ Entidades Principais

Aluno (id, nome, matrícula, telefone, status)

Livro (id, título, autor, código, status)

Empréstimo (id, dataEmpréstimo, dataPrevista, dataDevolução, status)

🔄 Principais Casos de Uso

Cadastrar aluno

Cadastrar livro

Registrar empréstimo

Registrar devolução

Consultar livros disponíveis

Consultar empréstimos em atraso
