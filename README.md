# Lista de Tarefas

## O projeto consiste em uma aplicação Full Stack completa com o objetivo de auxiliar no gerenciamento de atividades e tarefas.

<br>
<img align="center" src="backend/src/assets/img/1.jpeg" />

<br><br>

# Tecnologias Utilizadas

## Backend

- <a href="https://nodejs.org/en/">NodeJS</a> <img align="center" alt="NodeJS" height="20" width="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg">
- <a href="https://expressjs.com/">Express</a> <img align="center" alt="Express" height="20" width="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/express/express-original.svg">

## Frontend

- <a href="https://www.w3schools.com/html/">HTML</a> <img align="center" alt="HTML" height="20" width="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg">
- <a href="https://www.w3schools.com/css/">CSS</a> <img align="center" alt="CSS" height="20" width="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg">
- <a href="https://www.javascript.com/">JavaScript</a> <img align="center" alt="JavaScript" height="20" width="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg">

## Banco de Dados

- <a href="https://www.mysql.com/">MySQL</a> <img align="center" alt="MySQL" height="20" width="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg">

<br>

# Como Usar

### Primeiro, precisamos clonar ou baixar este repositório.

bash
# Comando para clonar o repositório
$ git clone https://github.com/manualdodev/todolist-fullstack.git


### Após clonar o repositório, é necessário criar um banco de dados MySQL com as colunas necessárias.

bash
# Comando para criar um banco de dados no terminal do MySQL:
$ CREATE DATABASE nome_do_banco;


### Em seguida, crie a tabela **tasks** que será utilizada pela aplicação.

bash
# Comando para criar a tabela com suas colunas
$ CREATE TABLE tasks(
    id INT PRIMARY KEY AUTO_INCREMENT,
    title VARCHAR(45) NOT NULL,
    status VARCHAR(45) NOT NULL,
    created_at VARCHAR(45) NOT NULL
);


### Na raiz do projeto existe o arquivo `.env.example`. Ele contém 5 campos que devem ser preenchidos em um arquivo `.env`. Basta criar ou renomear.

bash
PORT= [Porta onde o servidor irá rodar]
MYSQL_HOST= [Host da máquina, por padrão é 'localhost']
MYSQL_USER= [Usuário do MySQL, por padrão 'root']
MYSQL_PASSWORD= [Senha configurada na instalação do MySQL]
MYSQL_DB= [Nome do banco criado anteriormente]


### Antes de iniciar a aplicação, instale as dependências dentro da pasta `backend`.

bash
# Instalar dependências
$ npm install


### Por fim, inicie o servidor e abra o arquivo `index.html`.

bash
# Iniciar servidor
$ npm start


<br>
