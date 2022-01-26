# vue-3-demo

## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn serve
```

### Compiles and minifies for production
```
yarn build
```

### Lints and fixes files
```
yarn lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

### Sidenote from Daniel
from the existing project originally using vue-cli, I've removed all the dependeincies in package.json linked to the cli and  executed:
```
npm i vue@latest
```
npm i vite@latest
```
added the vite.config.js
```
moved the index.html file to the root
```
made some changes in the index.html file (to remove some webpack related code)
```
