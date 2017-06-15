# vue2-webpack2
### 安装环境
```bash
#安装nodejs 
可以在终端里下载，但是不推荐，npm的版本会报错 
去nodejs官网下载即可，地址： http://nodejs.cn/中文网

#安装vue淘宝镜像 
npm install -g vue –registry=https://registry.npm.taobao.org

#安装webpack 
npm install webpack -g

#安装vue脚手架 
npm install vue-cli -g
```

—————-如果不是第一次编写新的vue项目，可以直接在这里开始了—————–

### 根据模板创建项目 
```bash
vue init webpack 项目名字<项目名字不能用中文>
例如：vue init webpack myweb

#会有一些初始化的设置，如下输入: 
Target directory exists. Continue? (Y/n) 直接回车默认(然后会下载 vue2.0模板，这里可能需要连代理) 
Project name (vue-test) 直接回车默认 
Project description (A Vue.js project) 直接回车默认 
Author 直接回车默认 
Use ESLint to lint your code? n （如想程序自动检查代码格式是否正确可选Y）
pick an eslint preset. 默认Standard 
setup unit tests with karma + mocha?No(单元测试不需要) 
setup e2e tests with Nightwatch?No(单元测试不需要)
```

### 进入项目 
```
打开终端 
cd 项目名字 例如 cd myweb
```

### 安装项目依赖 
```
npm install

安装 vue 路由模块vue-router和网络请求模块vue-resource –save-dev 是你开发时候依赖的东西，–save 是你发布之后还依赖的东西 
npm install vue-router vue-resource --save
```
### 启动项目 
```
npm run dev
```

### 发布项目 
```
npm run build
```
