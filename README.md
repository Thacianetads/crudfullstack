#  CRUD de Usuários - Node.js, React e MySQL

Este é um projeto fullstack de CRUD de usuários, desenvolvido com **Node.js** no backend, **React** no frontend e **MySQL** como banco de dados. A aplicação permite **cadastrar**, **listar**, **editar** e **excluir** usuários com os seguintes campos:

- Nome
- E-mail
- Telefone
- Data de Nascimento

---

## 🛠️ Tecnologias Utilizadas

- Node.js
- MySQL
- React


## 🔧 Funcionalidades

- ✅ Listar todos os usuários
- ✅ Cadastrar novo usuário
- ✅ Editar usuário existente
- ✅ Excluir usuário
- ✅ Validação básica de formulário
- ✅ Comunicação entre frontend e backend via API REST

---


## 🚀 Como Rodar o Projeto
Pré-requisitos:

-Node.js instalado

-MySQL instalado

-NPM ou Yarn


1. Configure o banco de dados

CREATE TABLE usuarios (

    id INT NOT NULL AUTO_INCREMENT, 
    nome VARCHAR(100),
    email VARCHAR(100),
    telefone VARCHAR(20),
    data_nascimento DATE,
    PRIMARY KEY (id)
);


2. Instale as dependências
   
Backend:
cd api
npm install


Frontend:
cd ../frontend
npm install


3. Inicie os servidores


Inicie o backend:
cd api
npm start


Inicie o frontend:
cd ../frontend
npm start

# 🧪 Dica: Testando no Insomnia

a API está rodando localmente em:  
`http://localhost:8800`  

1.Abra o Insomnia

2.Crie um novo Request Collection

3.Adicione cada endpoint como nova requisição

4.Use o método correto (GET, POST, etc)

5.Para POST e PUT, selecione o Body como JSON

6.Clique em Send para testar



Feito com 💻 por Thaciane
