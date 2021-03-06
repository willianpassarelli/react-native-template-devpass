<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="#">
    <img src="https://user-images.githubusercontent.com/26445991/67727135-f6256f00-f9c6-11e9-9921-701cf1cb7e2b.png" height="100" alt="Logo">
  </a>

  <h3 align="center">Template Devpass</h3>
</p>

## Sobre o Projeto

Este projeto visa a criação de um template que possa ser utilizado no momento de criação de projetos utilizando React Native, pois o processo de instalação e configuração das libs no início de um projeto é repetitivo e constumamos a utilizar as mesmas estruturas.

### Dependências utilizadas

- [react]()
- [react-native]()
- [axios]()
- [immer]()
- [prop-types]()
- [react-native-gesture-handler]()
- [react-native-linear-gradient]()
- [react-native-reanimated]()
- [react-native-vector-icons]()
- [react-navigation]()
- [react-navigation-stack]()
- [react-navigation-tabs]()
- [react-redux]()
- [reactotron-react-native]()
- [reactotron-redux]()
- [reactotron-redux-saga]()
- [redux]()
- [redux-persist]()
- [redux-saga]()
- [styled-components]()

### Dependências de desenvolvimento

- [@babel/core]()
- [@babel/runtime]()
- [@react-native-community/eslint-config]()
- [babel-jest]()
- [babel-plugin-root-import]()
- [eslint]()
- [eslint-config-airbnb]()
- [eslint-config-prettier]()
- [eslint-import-resolver-babel-plugin-root-import]()
- [eslint-plugin-import]()
- [eslint-plugin-jsx-a11y]()
- [eslint-plugin-prettier]()
- [eslint-plugin-react]()
- [eslint-plugin-react-native]()
- [jest]()
- [jetifier]()
- [prettier]()
- [metro-react-native-babel-preset]()
- [react-test-renderer]()

<!-- GETTING STARTED -->

## Começando

### Instalação

1. Para instalar e utilizar esse template o processo é bem simples, basta criar um projeto novo utilizando o comando:

```sh
react-native init AwesomeExample --template devpass
```

2. Altere o nome do seu projeto como exemplo acima (AwesomeExemple) no arquivo app.json

```
{
  "name": "template",
  "displayName": "template"
}
```

---

### Estrutura de Arquivos

A estrutura de arquivos está da seguinte maneira:

```bash
template
├── src/
│   ├── config/
│   │   └── ReactotronConfig.js
│   ├── pages/
│   │   └── Main/
│   │       └── index.js
│   │       └── styles.js
│   ├── services/
│   │   └── api.js
│   ├── store/
│   │   ├── modules/
│   │   │   └── rootReducer.js
│   │   │   └── rootSaga.js
│   │   └── index.js
│   │   └── createStore.js
│   │   └── persistReducers.js
│   ├── index.js
│   └── routes.js
├── .editorconfig
├── .eslintrc.js
├── .gitignore
├── .prettierrc
├── babel.config.js
├── dependencies.json
├── devDependencies.json
├── index.js
├── jsconfig.js
├── metro.config.js
├── package.json
└── README.md
```
