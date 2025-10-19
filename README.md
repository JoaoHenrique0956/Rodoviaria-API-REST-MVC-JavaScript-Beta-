🚌 Sistema de Ônibus – MVC + JWT + Node.js + MySQL
📋 Descrição

Este projeto é um sistema de gerenciamento de viagens de ônibus, desenvolvido com Node.js, Express, MySQL e EJS, utilizando o padrão MVC (Model-View-Controller) e autenticação via JWT (JSON Web Token).

O sistema permite cadastrar, listar, editar e excluir informações de:

🧍‍♂️ Clientes

🚌 Ônibus

🗺️ Viagens

Cada viagem está vinculada a um cliente e a um ônibus, garantindo integridade relacional no banco de dados.

🧠 Funcionalidades

Login seguro com autenticação JWT

CRUD completo de Clientes, Ônibus e Viagens

Interface dinâmica com EJS + Bootstrap

Validação de formulários e mensagens de erro amigáveis

Relacionamento entre tabelas (viagens, clientes, onibus)

Organização modular com padrão MVC

🏗️ Tecnologias Utilizadas

Node.js

Express.js

MySQL

EJS (Embedded JavaScript)

Bootstrap 5

dotenv

jsonwebtoken

bcrypt

mysql2

🧩 Estrutura de Pastas
src/
 ├── config/          # Conexão com o banco e variáveis de ambiente
 ├── controllers/     # Lógica de negócio e controle de rotas
 ├── dao/             # Acesso direto ao banco de dados
 ├── middlewares/     # Autenticação e validações
 ├── models/          # Modelos das entidades (Cliente, Ônibus, Viagem)
 ├── routes/          # Definição das rotas
 ├── views/           # Páginas EJS renderizadas

⚙️ Banco de Dados (MySQL)

O sistema utiliza um banco viagens_db com as seguintes tabelas:

usuarios → controle de login e autenticação

clientes → cadastro de passageiros

onibus → cadastro de veículos

viagens → registro completo de cada viagem (relacionado a clientes e onibus)

🚀 Como Rodar o Projeto
# 1. Instalar dependências
npm install

# 2. Configurar o arquivo .env
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=
DB_NAME=viagens_db
DB_PORT=3306
PORT=3000
JWT_SECRET=supersegredo123
JWT_EXPIRES=1d

# 3. Rodar o servidor
npm run start


Depois, acesse 👉 http://localhost:3000

👨‍💻 Desenvolvido por

João Henrique Mendes Oliveira 2 ano J
Arthur Felipe de Oliveira 2 ano J
Murilo Farias Lemes 2 ano J
💡 Projeto acadêmico – PAW (Programação e Aplicações Web) – 4° Bimestre EM DESENVOLVIMENTO
