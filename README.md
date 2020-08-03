# build-a-bot

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

Download node version manager from https://github.com/coreybutler/nvm-windows

Install Node JS - nvm install 12.18.3
Set Node JS version - nvm use 12.18.3

Install VueJS - npm install -g @vue/cli@4.3.1
Create project - winpty vue.cmd create build-a-bot

Install VS Code extensions - ESLint, Vetur, vue, Beautify, jshint

start development server - npm run serve
view application - http://localhost:8080/

npm install node-sass sass-loader --save-dev

Add router module - npm install vue-router --save

Install vuex store - npm install vuex@3.0.1 --save

Install axios to make http request - npm install axios --save

API Server - https://github.com/jmcooper/build-a-bot-server
clone the repo
npm i

Parts API - http://localhost:8081/api/parts

Create deployable web application for production (it creates dist folder) - npm run build
Create deployable web application for staging - npm run build -- --mode=staging

Inspect built-in Webpack config - vue inspect --mode=production