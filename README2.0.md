# 📝 Projeto: To-Do List

Projeto completo para praticar os **fundamentos do desenvolvimento web** com foco em **HTML5**, **CSS3**, **JavaScript puro** e **criação de API REST com .NET (ou outra linguagem, se preferir)**.

> Ideal para desenvolvedores iniciantes que desejam colocar em prática seus conhecimentos em **frontend**, **backend**, **versionamento com Git** e **persistência de dados com banco de dados**.

---

## 🎯 Objetivos do Projeto

- Aprender e praticar **JavaScript puro** com manipulação de DOM
- Criar um **front-end funcional e semântico**
- Desenvolver uma **API RESTful** com operações CRUD
- Implementar persistência de dados com banco de dados
- Integrar o front-end com o back-end utilizando requisições HTTP
- Praticar versionamento de código com **Git e GitHub**

---

## 🔧 Tecnologias sugeridas

### Frontend
- **HTML5**
- **CSS3**
- **JavaScript (Vanilla)**
- Você pode utilizar frameworks se já tiver familiaridade, mas o foco é entender os conceitos base.

### Backend
- **.NET Core (C#)** com Dapper ou ADO.NET
- **OU** escolha alternativa:
  - **Node.js (Express)**
  - **Python (Flask ou FastAPI)**
  - **Java (Spring Boot)**

---

## 🖼️ Funcionalidades do Frontend

- [x] Interface com campo de entrada e botão para adicionar tarefas
- [x] Criação de tarefas ao clicar no botão ou pressionar "Enter"
- [x] Listagem de tarefas com opções de editar ou excluir
- [x] Bloquear a adição de tarefas com descrição duplicada
- [x] Estrutura semântica com HTML5
- [x] Estilização livre com CSS3 (responsividade recomendada)
- [x] Separação de responsabilidades em arquivos (`index.html`, `style.css`, `script.js`)

---

## 🛠️ Funcionalidades do Backend

> Recomendado usar .NET Core com Dapper, mas outras linguagens são bem-vindas.

- [x] Criar uma API RESTful com rotas:
  - `GET /tarefas` - Listar todas as tarefas
  - `POST /tarefas` - Criar nova tarefa
  - `PUT /tarefas/:id` - Atualizar tarefa
  - `DELETE /tarefas/:id` - Remover tarefa
- [x] Utilizar um banco de dados (ex: SQLite, SQL Server, PostgreSQL)
- [x] Implementar padrão Repository
- [x] Queries com **Dapper** ou **ADO.NET**
- [ ] (Desafio extra) Implementar com **Entity Framework** como alternativa

---

## 🔁 Integração Frontend + Backend

- [x] Ao abrir a página, carregar todas as tarefas salvas via API (`GET`)
- [x] Adicionar, editar e excluir tarefas utilizando `fetch()` para fazer requisições HTTP
- [x] Garantir que todas as tarefas sejam persistidas no banco de dados (sem uso de `localStorage`)
- [x] Recarregar página sem perder dados

---

## 🌳 Versionamento com Git

Antes de iniciar o projeto:

- [x] Crie um repositório no GitHub
- [x] Faça commits com mensagens claras e frequentes
- [x] Utilize comandos essenciais:
  - `git init`
  - `git add`
  - `git commit`
  - `git push`
  - `git pull`
  - `git branch` e `git checkout` (para desafios/funcionalidades em branches separados)

---

## 🎯 Desafios Extras (opcional)

- [ ] Marcar tarefa como **concluída**
- [ ] Criar **categorias** para tarefas
- [ ] Adicionar **validação de formulário**
- [ ] Filtrar tarefas por concluídas/pedentes
- [ ] Adicionar campo de **data de criação**
- [ ] Usar **Entity Framework** para abstração de banco
- [ ] Usar `localStorage` para salvar tema ou preferências
- [ ] Fazer deploy da API (Render, Vercel, Railway, Azure, etc.)

---

## 📷 Exemplo de Interface

> Imagem meramente ilustrativa. Estilize como quiser!

<img src="https://i.imgur.com/qqQV0mA.png" width="400" />

---
