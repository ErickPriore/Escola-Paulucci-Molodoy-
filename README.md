Escola-Paulucci-Molodoy (Grupo Molodoy)
BiblioDesk – Sistema de Controle de Empréstimos

Sistema desktop em Java para controle de empréstimos de uma biblioteca escolar de pequeno porte.

👥 Equipe  
Kauan • Matheus • Vinicius • Gustavo • Guilherme • Erick

Versão: 1.5
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

Cadastro de alunos e informações gerais (CPF, RA, responsáveis, endereço e telefone)

Cadastro de professores e informações gerais (telefone, CPF e RG)

Catálogo dos livros da biblioteca com informações detalhadas (gênero, título, descrição)

Registro de multas e regras/valores por dano ao material

Registro de devoluções

Consulta de livros disponíveis

Consulta de multas em atraso

Sistema de reservas de livros por aluno com data limite e horário

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

Registrar multas e reservas

📏 Regras de Negócio  
📘 Livro só pode ser emprestado se estiver disponível
👤 Máximo de 3 livros por aluno
⏳ Prazo padrão de 30 dias
⚠ Empréstimo entra em atraso após 30 dias
🚫 Não é permitido excluir aluno com empréstimo ativo
💰 Multas aplicadas por atraso ou dano conforme regras definidas
📅 Reservas possuem data limite e horário

🗂️ Entidades Principais

Aluno (id, nome, matrícula, CPF, RA, responsáveis, endereço, telefone, status)

Professor (id, nome, CPF, RG, telefone, status)

Livro (id, título, autor, gênero, descrição, código, status)

Multa (id, tipo: atraso ou dano, valor, status)

Consulta/Empréstimo (id, dataEmpréstimo, dataPrevista, dataDevolução, status, reserva)

🔄 Principais Casos de Uso

Cadastrar aluno

Cadastrar professor

Cadastrar livro

Registrar multas

Registrar devolução

Consultar livros disponíveis

Consultar multas em atraso e danos

Realizar reservas de livros
