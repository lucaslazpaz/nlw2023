# ANOTAÇÕES NLW

### AULA 01
---
##### FRONTEND

- [X] Fundamentos do React
- [X] Criação do projeto:

    - Criação do projeto do vite:

            npm create vite@latest
- [X] Componentes e propriedades
- [X] Configuração do Tailwind CSS:

    - Instalação do Tailwind com vite:

            npm install -D tailwindcss postcss autoprefixer
    - Gerando o 'tailwind.config.cjs' e 'postcss.config.cjs':
            
            npx tailwindcss init -p
    - Adicionando paths no 'tailwind.config.cjs':

            /** @type {import('tailwindcss').Config} */
            module.exports = {
                content: [
                    "./index.html",
                    "./src/**/*.{js,ts,jsx,tsx}",
                ],
                theme: {
                    extend: {},
                },
                plugins: [],
            }
    - Adicionando diretivas no arquivo CSS base (index.css):

            @tailwind base;
            @tailwind components;
            @tailwind utilities;
