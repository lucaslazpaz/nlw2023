# ANOTAÇÕES NLW

### AULA 01
---
##### BACKEND

- [X] Fundamentos do Node.js
- [X] Criação do Projeto com NPM: 

    - Instalado fastify

            npm install fastify
- [X] Setup TypeScript:

    - Instalado typescript e tsx como dev dependencie
        
            npm install typescript

            npm install tsx

    - Criado script no package.json

            "dev": "tsx watch src/server.ts"

- [X] Criando Primeira rota com fastify
- [X] Configurando o Prisma:

    - Instalando o Prisma como dev dependencie e o Prisma Client

            npm i -D prisma

            npm i @prisma/client
    
    - Iniciando o prisma para o banco SQLite

            npx prisma init --datasource-provider SQLite

    - Criando e rodando a primeira migrate de DEV

            npx prisma migrate dev

    - Obs: é possível acessar um visualizador do banco

            npx prisma studio

- [X] Configurando o CORS

    - Instalando o Fastify CORS

            npm i @fastify/cors