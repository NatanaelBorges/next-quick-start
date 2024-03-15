<div id="top"></div>
<h1 align="center">
<br>
<img src="https://res.cloudinary.com/duugdpulf/image/upload/v1633037461/quickstart_selwus.png" alt="Quick Start"  height="250"  width="450">
<br><br>
</h1>

<br>
<p  align="center">
<a  href="https://github.com/NatanaelBorges/next-quick-start/blob/main/CHANGELOG.md">
<img  alt="package.json version"  src="https://img.shields.io/github/package-json/v/NatanaelBorges/next-quick-start">
</a>
<a  href="https://github.com/NatanaelBorges/next-quick-start/commits/main">
<img  alt="GitHub last commit"  src="https://img.shields.io/github/last-commit/NatanaelBorges/next-quick-start">
</a>
  <a  href="https://github.com/NatanaelBorges/next-quick-start/blob/main/LICENSE">
<img  alt="GitHub"  src="https://img.shields.io/github/license/NatanaelBorges/next-quick-start"  alt="next-quick-start is released under the MIT license.">
</a>
</p>

🇧🇷 Português | [🇺🇸 English](./README.md)

## 🔖 Visão Geral
Este é um aplicativo Next.js baseado no [Guia de início rápido](https://nextjs.org/docs/getting-started). Use este app para ajudá-lo a começar sem precisar fazer todas as configurações chatas e focar no que realmente importa para codificar 😍

- **<a href="#%EF%B8%8F-começando">Começando</a>**
- **<a href="#-lembrete">Lembrete</a>**
- **<a href="#-tecnologias">Tecnologias</a>**
- **<a href="#-fluxo-de-desenvolvimento">Fluxo Desenvolvimento</a>**
- **<a href="#-licença">Licença</a>**

### 🖥️ Suporte a Navegadores

Este projeto foi projetado para funcionar com navegadores modernos e o Internet Explorer 11. Aqui está uma lista dos navegadores suportados:

|<img  src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/edge/edge_48x48.png"  alt="IE / Edge"  width="24px"  height="24px" /> IE / Edge | <img  src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png"  alt="Firefox"  width="24px"  height="24px" /> Firefox | <img  src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png"  alt="Chrome"  width="24px"  height="24px" /> Chrome | <img  src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/safari/safari_48x48.png"  alt="Safari"  width="24px"  height="24px" /> Safari | <img  src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/opera/opera_48x48.png"  alt="Opera"  width="24px"  height="24px" /> Opera
| --- | --- | --- | --- | --- |
| últimas versões | últimas versões | últimas versões | últimas versões | últimas versões |

### Server-side Rendering

Este projeto suporta renderização do lado do servidor (SSR) para os seguintes navegadores:

-   Internet Explorer 11, Edge
-   Firefox
-   Chrome
-   Safari
-   Opera

## 🏃‍♂️ Começando

### Pré-requisitos

Antes de começar, você precisará ter as seguintes ferramentas instaladas em sua máquina:

O projeto pode ser construído com **npm** ou **yarn**, então escolha uma das abordagens abaixo caso você não tenha nenhuma instalada em seu sistema.

 - **Npm** é distribuído com o Node.js, o que significa que, quando você baixa o Node.js, automaticamente obtém o npm em seu computador. [Baixar o Node.js](https://nodejs.org/)

- **Yarn** é um gerenciador de pacotes desenvolvido pela equipe do Facebook e geralmente parece ser mais rápido que o npm. [Baixar o Yarn](https://yarnpkg.com/)

Além disso, é bom ter um editor para trabalhar com código como o [VSCode](https://code.visualstudio.com/)

#### 🧭 Executando o aplicativo (Frontend)

```bash
# Clone este repositório
$ npx create-next-app [nome-projeto] --example https://github.com/NatanaelBorges/next-quick-start

# Acesse a pasta do projeto no terminal/cmd
$ cd [nome-projeto]

# Instale as dependências
$ npm install
# or
$ yarn

# Execute a aplicação em modo de desenvolvimento
$ npm run start
# or
$ yarn start

# O servidor inciará na porta:3000 - acesse http://localhost:3000
```
Observação: se você estiver usando o Linux Bash para Windows,  [veja este guia](https://www.howtogeek.com/261575/how-to-run-graphical-linux-desktop-applications-from-windows-10s-bash-shell/)  ou use  `node`  a partir do prompt de comando.

<p align="right">(<a href="#top"> voltar ao topo </a>)</p>

## ⏰ Lembrete

Não se esqueça de alterar o ***nome do projeto*** e a ***versão*** no 👉 [package.json](https://github.com/NatanaelBorges/next-quick-start/blob/main/package.json) para o nome do seu projeto e sua respectiva *versão*.

## 💾 Tecnologias

As seguintes ferramentas foram utilizadas na construção do projeto:

- **[Next.js](https://nextjs.org)**
- **[TypeScript](https://www.typescriptlang.org/)**
- **[Tailwindcss](https://tailwindcss.com/)**
- **[Husky](https://www.npmjs.com/package/husky)**
- **[Jest.js](https://jestjs.io/)**
- **[Commitlint](https://commitlint.js.org/#/)**
- **[ESLint](https://eslint.org/)**
- **[Prettier](https://prettier.io/)**
- **[Release-it](https://github.com/release-it/release-it)**

> Veja o arquivo  [package.json](https://github.com/NatanaelBorges/next-quick-start/blob/main/package.json)

<p align="right">(<a href="#top"> voltar ao topo </a>)</p>

## 💻 Fluxo de Desenvolvimento

Antes de começar a desenvolver, atualize as bibliotecas, pois pode haver versões mais recentes disponíveis. Gosto de usar este comando `npm outdated` e atualizar biblioteca por biblioteca, para que eu possa saber se alguma biblioteca sofreu alguma alteração importante.

### Principais Comandos

| Comando| O que faz |
|--|--|
| `npm run dev` | Executa o projeto |
| `npm test` | Executa os testes | 
| `yarn dev` | Executa o projeto (Yarn) | 
| `yarn test` | Executa os testes (Yarn) | 

<p align="right">(<a href="#top"> voltar ao topo </a>)</p>

## 📝 Licença

Este projeto está sob a [licença do MIT](https://github.com/NatanaelBorges/next-quick-start/blob/main/LICENSE).

Feito ❤️ por ***Natanael Borges*** 👋🏽

<p align="right">(<a href="#top"> voltar ao topo </a>)</p>
