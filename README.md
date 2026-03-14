# Criar projeto React + Vite

Comando para criar projeto React + Vite:

`npm create vite@5.5.2 .`

Depois deve selecionar o framework `React` e a opção `Javascript`

# Executar o projeto

Para executar o projeto deve utilizar o seguinte comando:

`npm run dev`

# Tailwindcss

Biblioteca `Tailwindcss` é utilizada para estilizar a aplicação React

Instalar a dependências nessas versões: 
`npm install -D tailwindcss@3.4.10 postcss@8.4.41 autoprefixer@10.4.20`

Depois de instalado, execute o comando abaixo para inicializar `tailwindcss` no projeto:
`npx tailwindcss init -p`

Na sequência, configure os caminhos do modelo, dentro do arquivo `tailwind.config.js`.
Colocar dentro do atributo `content` os seguintes valores:
 `content: ["./index.html","./src/**/*.{js,ts,jsx,tsx}"],`

Caso de dúvidas acessar o link abaixo e seguir o passo a passo de configuração para projetos `React + Vite`:
https://v3.tailwindcss.com/docs/guides/vite


# React Router
Biblioteca `React Router` que gerência rotas na aplicação React

Comando para instalar a versão utilizada:
`npm install react-router-dom@6.26.1`

Em caso de dúvidas consultar a documentação pelo link abaixo:
https://reactrouter.com/6.30.3/start/tutorial

# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

# JSONPlaceholder

Utilização da API gratuita JSONPlacelhoder para realizações de testes de integra na aplicação react.
Exemplo de requisição:
`fetch('https://jsonplaceholder.typicode.com/todos/1').then(response => response.json()).then(json => console.log(json))`

Resultado:
{
  "userId": 1,
  "id": 1,
  "title": "delectus aut autem",
  "completed": false
}