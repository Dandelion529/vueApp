# vueapp

> A Vue.js project

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test

# 项目搭建
1.先创建vue-cli脚手架
npm install -g vue-cli
2.webpack打包工具
vue init webpack vueApp(此处完成后自动生成配置文件和依赖包，省略cnpm install)
3.cnpm install(可省略)
4.项目运行
npm run dev 
5.安装应用，如移动端ui（vant）axios请求，sass-loader等等
npm i vant -S
npm install axios -save
npm install sass-loader -save
npm install node-loader -save
```
#### vant使用
``` bash
vue移动端ui框架vant[guide](https://youzan.github.io/vant/#/zh-CN/intro)
有赞线上组件支持，完善的文档和示例
vant提供开发脚手架，通过vue-cli快速创建一个基于vant的项目。
1. vue init youzan/vue-cli-template-vant my-project
2. npm i vant -S
3. npm install
4. npm run dev
```
For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
