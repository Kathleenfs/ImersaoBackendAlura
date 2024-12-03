# Projeto de API com Node.js

Este projeto é uma API desenvolvida com Node.js e Express, que utiliza MongoDB Atlas como banco de dados na nuvem. A API inclui funcionalidades de armazenamento e upload de imagens, além de integração com a IA generativa do Google. Este projeto foi realizado como parte da imersão backend do Alura, abrangendo desde a criação e estruturação de APIs até a publicação na Google Cloud.

## Configuração do Projeto

### Inicialização do Projeto

```sh
npm init es6 -y
```

## Instalação das Dependências

```sh
npm install express
npm install mongodb
npm install multer
npm install @google/generative.ai
npm install cors
npm install dotenv
```

## Configuração do Banco de Dados

- Crie um banco de dados no MongoDB Atlas na nuvem.
- Obtenha a string de conexão fornecida pelo MongoDB Atlas.

## Variáveis de Ambiente

Crie um arquivo `.env` na raiz do projeto para armazenar variáveis de ambiente e proteger os dados sensíveis.

## Scripts

Adicione o seguinte comando no `package.json` para iniciar o servidor:

```json
"scripts": {
  "dev": "nodemon index.js"
}
```

## Iniciando o Servidor

Para iniciar o servidor, execute:

```sh
npm run dev
```

## Ferramentas e Extensões

- **Thunder Client:** Utilize o Thunder Client no VSCode para testar as requisições da API.
- **Multer:** Usado para armazenamento e upload de imagens.

## Conexão entre Frontend e Backend

Para conectar o frontend com o backend:

1. Configure o CORS no backend para permitir o compartilhamento de origem cruzada.
2. No frontend, instale as dependências necessárias e adicione o comando `npm install`.
3. Utilize o comando `npm run dev` no frontend.
4. Crie um arquivo `.env` na raiz do frontend para configurar as variáveis de ambiente e a URL da API.


