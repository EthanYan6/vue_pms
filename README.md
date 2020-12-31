# vue_pms

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

### 端口更改
```
// src/main.js 访问后端端口
axios.defaults.baseURL = 'http://localhost:8090/pms'

// vue.config.js 前端启动端口
 module.exports = {
devServer: {
  port: 8091
  }
}
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
