# 📋 CRUD System - Cadastro de Usuários

[![Node.js](https://img.shields.io/badge/Node.js-18.x-green)](https://nodejs.org/)
[![Express](https://img.shields.io/badge/Express-4.x-blue)](https://expressjs.com/)
[![MySQL](https://img.shields.io/badge/MySQL-Aiven-orange)](https://aiven.io/)
[![EJS](https://img.shields.io/badge/EJS-Template-red)](https://ejs.co/)
[![License](https://img.shields.io/badge/License-MIT-yellow)](LICENSE)

Sistema completo de **CRUD (Create, Read, Update, Delete)** para gerenciamento de usuários, desenvolvido com Node.js, Express, MySQL (hospedado na nuvem Aiven) e interface com EJS.

## ✨ Funcionalidades

- ✅ **Cadastrar** - Novo usuário com e-mail e senha
- ✅ **Listar** - Exibe todos os usuários cadastrados
- ✅ **Editar** - Altera dados de um usuário existente
- ✅ **Excluir** - Remove usuário do sistema
- ✅ **Interface responsiva** - Funciona em desktop e mobile
- ✅ **Banco de dados online** - Dados persistentes na nuvem (Aiven)

## 🚀 Tecnologias Utilizadas

| Tecnologia | Descrição |
|------------|-----------|
| **Node.js** | Runtime JavaScript para o backend |
| **Express** | Framework web para Node.js |
| **MySQL** | Banco de dados relacional (Aiven Cloud) |
| **EJS** | Template engine para renderização das views |
| **dotenv** | Gerenciamento de variáveis de ambiente |
| **body-parser** | Parsing de requisições HTTP |

## 📦 Instalação e Configuração

### Pré-requisitos
- Node.js instalado (v18+)
- NPM ou Yarn
- Conta no Aiven (https://aiven.io) para banco online

### Passo 1: Clone o repositório
```bash
git clone https://github.com/c4rm4XXV/crud-project.git
cd crud-project
```
### Passo 2: Instale as dependências
```cmd
npm install express body-parser mysql2 dotenv ejs
```
### Passo 3:  Configure o banco de dados no Aiven

- Acesse https://aiven.io e crie uma conta (grátis)
- Clique em "Create service"
- Escolha "MySQL" e selecione o plano "Free"
- Copie a Service URI ou os parâmetros de conexão

```bash
cp .env.example .env
```

```.env
DATABASE_URL=mysql://usuario:senha@host:porta/defaultdb?ssl-mode=REQUIRED
```
### Passo 4:  Execute o servidor

```bash
npm start
```



