# 2024 - App Expo React Native com recursos de Autenticação usando Firebase

## Documentação

**Expo - Using Firebase:** https://docs.expo.dev/guides/using-firebase/

**React Native Firebase:** https://rnfirebase.io/

**Firebase:**

- Site oficial: https://firebase.google.com/
- Documentação: https://firebase.google.com/docs
- Autenticação: https://firebase.google.com/docs/auth/web/start

## firebase

escolher web depois de criar o projeto
Apelido do app (exemplo-auth)
não marque a caixinha

pare o projeto e instale no cmd node -> npm install firebase

deixa marcado no site firebase a opcão --> Usar o npm

- fizemos a pasta firebase.config.js e colocamos no gitignore deixei no eamil as informaçãos

- nesse site https://docs.expo.dev/guides/using-firebase/ tem as esse comando : `npx expo customize metro.config.js`

- e pare o projeto e instale no cmd node -> npx expo customize metro.config.js vai criar a pasta na raiz metro.config e nessa pasta cole esse dados

```
const { getDefaultConfig } = require('@expo/metro-config');

const defaultConfig = getDefaultConfig(__dirname);
defaultConfig.resolver.sourceExts.push('cjs');

module.exports = defaultConfig;

```

Volta no site https://console.firebase.google.com/project/exemplo-auth-1d2bf e esolha

e escolha Authentication e escolher E-mail/senha e habilite salvar

usuarios

adcionar usuario aline123

faz a pasta firebase/auth esta no ig

no cmd faz npm install @react-native-async-storage/async-storage
