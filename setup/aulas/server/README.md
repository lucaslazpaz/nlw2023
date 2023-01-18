# ANOTAÇÕES NLW
##### BACKEND

### AULA 01
---

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

### AULA 02
---

- [X] Diagramação do banco de dados

    - Dica de autocomplete para criar relacionamentos com o prisma é adiconar o seguingue código nas configurações do VS Code:

						"[prisma]": {
							"editor.formatOnSave": true
						}
						
- [X] Criação das tabelas no banco

- [X] Criação de seed do banco de dados

- [X] Isolando arquivos do back-end

- [X] Criação das Rotas

    - Instalação da lib "zod" para validação dos dados:
                    
            npm install zod

    - Instalação da lib "dayjs" para formatação de datas no TypeScript:

            npm install dayjs

    