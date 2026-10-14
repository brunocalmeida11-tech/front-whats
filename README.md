# 💬 WhatsApp — Projeto de Integração API

## 📌 Sobre o projeto

Este projeto foi desenvolvido para praticar a integração entre uma interface web (Frontend) e uma API REST utilizando JavaScript, com requisições HTTP feitas através do `fetch()`.

A interface foi inspirada no WhatsApp e conta com telas de login e conversa.

## ✨ Funcionalidades

- 🔐 Login de usuários
- 💬 Interface de conversas
- 📱 Envio de mensagens
- 🔗 Comunicação entre Frontend e API
- 🗄️ Integração com banco de dados MySQL

## 🛠️ Tecnologias utilizadas

| Tecnologia | Utilização |
|---|---|
| HTML5 | Estrutura das páginas |
| CSS3 | Estilização da interface |
| JavaScript | Interações e requisições |
| Node.js | Execução do servidor |
| Express | Criação da API |
| MySQL | Banco de dados |
| Postman | Testes das rotas |

## 🚀 Como executar

**1. Instale as dependências**

```bash
npm install
```

**2. Configure o banco de dados MySQL**

Configure a conexão e crie o banco e as tabelas necessários para o projeto.

**3. Inicie o servidor**

```bash
node main.js
```

**4. Acesse a interface**

Abra a página inicial do projeto pelo navegador ou pelo servidor configurado.

## 🔌 Rotas da API

| Método | Rota | Descrição |
|---|---|---|
| `POST` | `/registrar` | Cadastro de usuários |
| `POST` | `/auth` | Autenticação |
| `POST` | `/chat` | Envio de mensagens |
| `GET` | `/chat` | Consulta de mensagens |

## 🎓 Objetivo

Praticar conceitos de desenvolvimento web, integração com APIs REST, requisições HTTP e manipulação de dados utilizando JavaScript.
