# Node Express API

API created in Node.js with the Express framework.

API criada em Node.js com o framework Express.

## Instalação e execução

Depois de instalado o Node.js, abra o prompt de comando e dentro da pasta do projeto execute os comandos abaixo.

Para instalar as dependências do projeto:

```
npm install | yarn install
```

Executar o projeto localmente:

```
npm run dev | yarn run dev
```

## Índice

- [Tecnologias](#tecnologias)

  - [Visual Studio Code](#visual-studio-code)

    - [Fonte](#fonte)

      - [Fira Code](#fira-code)

    - [Extensões](#extensões)

      - [Color Highlight](#color-highlight)
      - [DotEnv](#dotenv)
      - [Dracula Official](#dracula-official)
      - [EditorConfig for VS Code](#editorconfig-for-vs-code)
      - [ESLint](#eslint-for-vs-code)
      - [Markdown All in One](#markdown-all-in-one)
      - [Material Icon Theme](#material-icon-theme)
      - [Nunjucks](#nunjucks-for-vs-code)
      - [Prettier - Code formatter](#prettier---code-formatter)

    - [Configurações](#configurações)

  - [Node.js](#nodejs)
  - [Yarn](#yarn)
  - [Docker](#docker)
  - [Mongo](#mongo)
  - [Robo 3T](#robo-3t)
  - [Insomnia](#insomnia)

- [Bibliotecas](#bibliotecas)
  - [ESLint](#eslint)
  - [Express](#express)
  - [Nodemon](#nodemon)
  - [requireDir](#requiredir)
  - [Mongoose](#mongoose)
  - [Mongoose Paginate](#mongoose-paginate)
  - [CORS](#cors)

## Tecnologias

### [Visual Studio Code](https://code.visualstudio.com)

Editor de código-fonte que inclui suporte para depuração, realce de sintaxe, complementação inteligente de código, snippets, entre outros.

#### Fonte

##### [Fira Code](https://github.com/tonsky/FiraCode)

Fonte monoespaçada com ligaduras de programação. É necessário adicionar a fonte no sistema operacional.

#### Extensões

##### [Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)

Exibe a cor exata de todos RGB’s ou HEX em seu código, muito útil para trabalhar com CSS ou SASS.

##### [DotEnv](https://marketplace.visualstudio.com/items?itemName=mikestead.dotenv)

Utilizado para ter suporte à sintaxe .env, muito útil para quem trabalha com NodeJS, ReactJS ou qualquer outro tipo de projeto web.

##### [Dracula Official](https://marketplace.visualstudio.com/items?itemName=dracula-theme.theme-dracula)

Tema para o VSCode.

##### [EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)

Utilizado para padronizar quebra de linha, indentação, espaços e tabs entre desenvolvedores de um mesmo projeto.

##### [ESLint for VS Code](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)

Utilizado para padronizar código entre desenvolvedores como utilização de pontos e vírgulas, tamanho máximo de caracteres em linhas e todo outro tipo de padronização.

##### [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)

Utilizado para escrever e ler Markdown dentro do VSCode, muito útil para documentações o README’s do Github.

##### [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)

Utilizado para exibir os ícones de acordo com a linguagem utilizada na barra lateral.

##### [Nunjucks for VS Code](https://marketplace.visualstudio.com/items?itemName=ronnidc.nunjucks)

Utilizado para ter suporte à sintaxe .njk.

##### [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

Utilizado para formatar JavaScript / TypeScript / CSS.

#### Configurações

Depois de adicionar a fonte e as extensões, setar as configurações (Settings > Open settings.json):

```
{
  // Define o tema do VSCode
  "workbench.colorTheme":"Dracula",

  // Configura tamanho e família da fonte
  "editor.fontSize":16,
  "editor.lineHeight":24,
  "editor.fontFamily":"Fira Code",
  "editor.fontLigatures":true,

  // Aplica linhas verticais para lembrar de quebrar linha em códigos muito grandes
  "editor.rulers": [
    80,
    120
  ],

  // Aplica um sinal visual na esquerda da linha selecionada
  "editor.renderLineHighlight":"gutter",

  // Aumenta a fonte do terminal
  "terminal.integrated.fontSize":14,

  // Define o tema dos ícones na sidebar
  "workbench.iconTheme":"material-icon-theme",

  // Configura o Prettier e o ESLint
  "prettier.eslintIntegration": true,
  "editor.formatOnSave": true
}
```

### [Node.js](https://nodejs.org)

Interpretador de código JavaScript com o código aberto, focado em migrar o Javascript do lado do cliente para servidores.

### [Yarn](https://yarnpkg.com)

Gerenciamento de dependências rápido, confiável e seguro.

### [Docker](https://www.docker.com)

Possibilita o empacotamento de uma aplicação ou ambiente inteiro dentro de um container, tornando-se portável para qualquer outro host.

### [Mongo](https://hub.docker.com/_/mongo)

Imagem oficial do Mongo para o ambiente Docker.

### [Robo 3T](https://robomongo.org)

Interface gráfica para o banco de dados MongoDB.

### [Insomnia](https://insomnia.rest)

Cliente REST utilizado para testar as requisições REST ao servidor.

## Bibliotecas

### [ESLint](https://github.com/eslint/eslint)

Ferramenta para identificar e relatar padrões em JavaScript. Se o projeto for em Node é recomendado a utilização do guia de estilo 'Standard' e se for em React o guia de estilo do [AirBnB](https://www.npmjs.com/package/eslint-config-airbnb-base).

### [Express](https://github.com/expressjs/express)

Framework web rápido, flexível e minimalista para Node.js que ajuda a controlar as rotas e as views.

### [Nodemon](https://github.com/remy/nodemon)

Monitora as alterações no aplicativo node.js e reinicie o servidor automaticamente.

### [requireDir](https://github.com/aseemk/requireDir)

Assistente de diretórios para carregamento de arquivos.

### [Mongoose](https://github.com/Automattic/mongoose)

Ferramenta de modelagem de objetos do MongoDB projetada para funcionar em um ambiente assíncrono.

### [Mongoose Paginate](https://github.com/edwardhotchkiss/mongoose-paginate)

Realiza a paginação dos dados para as requisições no Mongoose.

### [CORS](https://github.com/expressjs/cors)

Fornece um middleware que pode ser usado para ativar o CORS com várias opções.
