# tela-login-typescript-Dio

Este projeto, denominado `tela-login-typescript-Dio`, é uma aplicação web construída com React e TypeScript. Ele foi desenvolvido para demonstrar uma tela de login interativa e estilizada.

## 🛠️Tecnologias Utilizadas

O projeto faz uso das seguintes tecnologias e bibliotecas:

  * **React**: Biblioteca JavaScript para construção de interfaces de usuário.
  * **TypeScript**: Superconjunto tipado do JavaScript que compila para JavaScript puro.
  * **Styled Components**: Para estilização de componentes, permitindo escrever CSS dentro do JavaScript.
  * **React Hook Form**: Para gerenciamento de formulários com validação simplificada.
  * **Yup**: Um construtor de esquemas para análise e validação de valores.

## 🏗️ Estrutura do Projeto

A estrutura do projeto segue uma organização modular, com componentes reutilizáveis e páginas dedicadas:

```
gustavo-mmh/tela-login-typescript-dio/tela-login-typescript-Dio-e287141e57338a42fb1fefe62b1834480ef68c28/
├── public/
│   ├── favicon.ico
│   ├── index.html
│   ├── logo192.png
│   ├── logo512.png
│   └── manifest.json
│   └── robots.txt
├── src/
│   ├── components/
│   │   ├── Button/
│   │   │   ├── index.tsx
│   │   │   ├── styles.ts
│   │   │   └── types.ts
│   │   └── Input/
│   │       ├── index.tsx
│   │       ├── styles.ts
│   │       └── types.ts
│   ├── pages/
│   │   └── Login/
│   │       ├── index.tsx
│   │       ├── styles.ts
│   │       └── types.ts
│   ├── global.ts
│   ├── index.tsx
│   └── react-app-env.d.ts
├── .gitignore
├── package.json
├── package-lock.json
└── tsconfig.json
└── yarn.lock
```

  * `public/`: Contém arquivos estáticos como o `index.html` e ícones.
  * `src/`: Contém o código-fonte da aplicação.
      * `components/`: Abriga componentes reutilizáveis como `Button` e `Input`, cada um com seus próprios arquivos de lógica (`index.tsx`), estilos (`styles.ts`) e definições de tipo (`types.ts`).
      * `pages/`: Contém as páginas principais da aplicação, como a página de `Login`.
      * `global.ts`: Define estilos globais para a aplicação.
      * `index.tsx`: O ponto de entrada principal da aplicação React.
  * `package.json` e `package-lock.json`: Gerenciamento de dependências do projeto.
  * `tsconfig.json`: Configurações do compilador TypeScript.
  * `.gitignore`: Arquivos e diretórios a serem ignorados pelo controle de versão.
  * `yarn.lock`: Garante a consistência das dependências entre diferentes ambientes.

## 📌Funcionalidades

A aplicação consiste em uma tela de login com os seguintes elementos:

  * **Campos de Entrada**: Inputs para e-mail e senha com estilização personalizada.
      * Validação em tempo real utilizando React Hook Form e Yup, exibindo mensagens de erro para e-mail inválido e senha com menos de 6 caracteres.
  * **Botão de Login**: Um botão estilizado para submissão do formulário.

## 🛠️ Instalação e Execução

Para configurar e rodar o projeto localmente:

1.  **Clone o repositório**:
    `git clone <URL_DO_REPOSITÓRIO>`
    `cd tela-login-typescript-dio`

2.  **Instale as dependências**:
    `npm install` ou `yarn install`

3.  **Inicie a aplicação**:
    `npm start` ou `yarn start`

    A aplicação será iniciada em `http://localhost:3000`.

## Scripts Disponíveis

No diretório do projeto, você pode executar:

  * `npm start`: Inicia o aplicativo em modo de desenvolvimento. A página será recarregada se você fizer edições e você verá quaisquer erros de lint no console.
  * `npm test`: Inicia o `test runner` em modo de observação interativa.
  * `npm run build`: Compila o aplicativo para produção na pasta `build`. Ele otimiza o build para o melhor desempenho.
  * `npm run eject`: Essa é uma operação unidirecional. O comando removerá a única dependência de build do seu projeto e copiará todos os arquivos de configuração e as dependências transitivas (webpack, Babel, ESLint, etc.) diretamente para o seu projeto, dando-lhe controle total sobre eles.

## 📖 Aprender Mais

Você pode aprender mais sobre como criar aplicativos React em [Create React App documentation](https://create-react-app.dev/docs/getting-started).

Para saber como implantar, visite [deployment documentation](https://create-react-app.dev/docs/deployment).
