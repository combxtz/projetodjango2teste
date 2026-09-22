# Bzú TECH – Grupo 10

**Status do Projeto:** 🚀 Concluído (Sprint 2 / Deploy)

---

## 📌 Sobre o Projeto

O **Bzú TECH** é uma aplicação web feita em Django, desenvolvida para ajudar no gerenciamento, processamento e visualização de dados do projeto. Nosso foco é entregar uma interface prática e eficiente para lidar com essas informações no dia a dia.

---

## 🛠️ Tecnologias Que Usamos

| Categoria | Tecnologia |
| --- | --- |
| **Linguagem e Framework** | Python / Django |
| **Front-end** | HTML5 / CSS3 |
| **Banco de Dados** | SQLite (Local) / PostgreSQL (Produção - Render) |
| **Hospedagem & Deploy** | Render (Web Service & Database) |
| **Servidor WSGI & Estáticos** | Gunicorn / WhiteNoise |

---

## 🚀 Entregas e Sprints

### Sprint 1 – Análise de Concorrentes

Na primeira sprint, nos concentramos na pesquisa de mercado para estruturar o nosso *Documento de Análise de Concorrentes*. Mapeamos as soluções existentes e dividimos o trabalho nas seguintes etapas:

* **Estrutura inicial** e organização do documento de benchmark.
* **Análise detalhada** das ferramentas mapeadas (como NOVUS e Data IoT).
* **Estudo de Benchmark** cruzando recursos e funcionalidades.
* **Revisão final** e consolidação da documentação.

#### 📊 Produtos Analisados
* **NOVUS Automation / NOVUS Cloud**
* **TagoIO**
* **Ubidots**
* **Solinftec**
* **SyOS**

---

### Sprint 2 – Colocando o Projeto no Ar (Deploy & Produção)

Na segunda sprint, focamos em colocar a aplicação no ar usando a plataforma **Render**, garantindo uma infraestrutura segura, automatizada e pronta para produção:

* **Configuração do ambiente:** Adicionamos as dependências necessárias para produção (`gunicorn`, `whitenoise`, `dj-database-url` e `psycopg2-binary`).
* **Automação no Deploy (`build.sh`):** Criamos o script responsável por instalar dependências, organizar arquivos estáticos e rodar as migrações automaticamente no servidor.
* **Banco de dados dinâmico:** Ajustamos o projeto para rodar com SQLite localmente e se conectar automaticamente ao PostgreSQL em produção.
* **Entrega de arquivos estáticos:** Usamos o `WhiteNoise` para servir CSS e JS sem depender de serviços externos.
* **Infraestrutura no Render:** Subimos o serviço web e a instância do PostgreSQL (região Oregon), configurando workers em paralelo para lidar com múltiplas requisições.

🔗 **Acesse a aplicação no ar:** [https://projeto-djangofds.onrender.com](https://projeto-djangofds.onrender.com)

---

## 👥 Equipe do Projeto

| Nome Completo | E-mail Institucional | Papel / Responsabilidade |
| --- | --- | --- |
| **André Augusto de Araújo** | aaapn@cesar.school | Desenvolvedor |
| **Arthur Casanova de Azevedo** | aca5@cesar.school | Desenvolvedor |
| **Caio Ribeiro Lima Pinheiro** | crlp@cesar.school | Desenvolvedor |
| **Daniel Pereira Gomes de Faria** | dpgf@cesar.school | Desenvolvedor |
| **Eduardo Augusto Cordeiro dos Santos** | gfva@cesar.school | Desenvolvedor |
| **Gabriel Feitosa Vieira Aragão** | gabriel.email@school.com | Desenvolvedor |
| **Kauan Matheus da Silva Gomes** | kmsg@cesar.school | Desenvolvedor |
| **Alice Siqueira** | asci@cesar.school | Designer |
| **Bernardo Martins** | bmll@cesar.school | Designer |
| **Carolina Borba** | cbb3@cesar.school | Designer |
| **Mateus Coutinho** | mmc6@cesar.school | Designer |
| **Pedro Feitosa** | pamf@cesar.school | Designer |

---

## 🎥 Explicação do código do projeto Django - BZU TECH

[https://youtu.be/AJv6ibi3YPE]
