## API DATABASE - Valorant

**🎯 Objetivo do Projeto**

Projeto desenvolvido para fins educacionais, com o objetivo de colocar em prática conhecimentos de Back-End.

O projeto é uma API RESTful desenvolvida em Node.js, Express e MongoDB para gerenciar informações do jogo Valorant, incluindo personagens, armas, mapas, funções e nacionalidades.
Além disso, também inclui documentação automática com Swagger, autenticação com JWT e criptografia de senha com bcrypt.

**🤖 Tecnologias utilizadas**

Node.js

Express

MongoDB + Mongoose

JWT (jsonwebtoken)

bcrypt

dotenv

Swagger UI Express

Swagger Autogen

Nodemon

**🗂️ Funcionalidades Implementadas e Medidas de Segurança**

*Personagem:* CRUD completo de agentes (com função e nacionalidade associadas)

*Função:* CRUD das funções dos personagens

*Arma:* CRUD de armas do jogo

*Mapa:* CRUD de mapas jogáveis

*Nacionalidade:* CRUD das nacionalidades dos personagens

*Autenticação:* Rotas, registro e login para controle de usuários (JWT)

*Documentação Swagger:* Interface interativa das rotas em /api-docs

**⚙️ Instruções para rodar o projeto**

Instale a dependências do projeto: node, nodemon , jwt , bcrypt , mongoose , dotenv , swagger.

Crie um arquivo `.env` com as seguintes informações:

`PORT=3000`

`DB_CONNECTION_STRING = mongodb+srv://admin:admin@apivalorant.1q8n6o7.mongodb.net/API?retryWrites=true&w=majority`

`JWT_SECRET= chave_teste`

No terminal inicie o projeto com o comando `npm run dev`.

*As rotas são: /Personagem, /Mapa , /Nacionalidade , /Armas , /Mapas /registro /login e /install.*

**🧠 Desenvolvido por**

Luiza Matilha Sacom e Larissa Iovanovich Ribeiro

