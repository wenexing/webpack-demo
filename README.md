[指南](https://doc.webpack-china.org/guides/)
## 全局安装
```
npm install --global webpack
```

## 起步
```
mkdir webpack-demo && cd webpack-demo
npm init -y
npm install --save-dev webpack

npm install --save lodash

webpack src/index.js dist/bundle.js
```

NPM 脚本(NPM Scripts)
```
npm run build0
```

## 管理资源
```
npm install --save-dev file-loader
```

## 管理输出
```
npm install --save-dev html-webpack-plugin
npm install clean-webpack-plugin --save-dev
```
## 开发
```
npm run build
npm run server
```