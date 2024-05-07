# Testes _end-to-end_ com Cypress

Projeto simples para rodar o cypress em um serviço CI(GitHubActions)

## Pre-requisitos

Pra executar, será necessário:

- [git](https://git-scm.com/downloads) (Versão usada: `2.26.2` )
- [nodejs](https://nodejs.org/en/) (Versão usada: `14.17.3` )
- NPM (Versão usada: `6.14.13` )
- [Google Chrome](https://www.google.com/intl/en_us/chrome/) (Versão usada: `92.0.4515.131` )

## Instalação

Para instalar, rode `npm install` (ou npm i)

## Configurando as variáveis de ambiente

Antes de rodar, precisamos configurar algumas variáveis de ambiente.

Copie o arquivo [`cypress.env.example.json`](./cypress.env.example.json) renomeando para `cypress.env.json`, e defina o valor apropriado para cada variável.

**Nota:** `cypress.env.json` nao é rastreado pelo git.

## Executando os testes

Nesse projeto, podemos executar os testes no modo interativo ou no modo headless, e nos dispositivos
desktop e tablet.

### Modo Headless 

Rode `npm test` (`npm t`) para executar os testes em modo headless e na visão desktop.

Rode `npm run test:tablet` para executar os testes na visão do tablet.

### Modo interativo

Rode `npm run cy:open` para abrir o Test Runner do Cypress e visualizar os testes em desktop

Rode `npm run cy:open:tablet` para abrir o Test Runner do Cypress e visualizar os testes no tablet

___

