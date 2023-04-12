# 图书管理系统-客户端

#### 项目说明

此项目为图书管理系统前台，使用vue.js,vue-resource,vue-router,iView2.0UI框架,vue-quill-editor等技术实现前台页面，
后台采用的是springboot+mybatis等技术实现数据持久化以及api服务调用，后台地址：[appapidemo](https://github.com/yangyuscript/appapidemo.git)

#### 配置环境

1. Nvm1.1.10
2. Node 8.12.0
#### 开发工具
1. IntelliJ IDEA 2022.3.2
2. Git 2.24.1
#### 开发环境
Windows
#### 项目启动
- 1.数据库：mysql5.6执行以下脚本,项目下脚本文件--db_appapidemo.sql
- 2.后台启动：导入项目，进入控制台，到项目所在路径，执行命令：mvn clean spring-boot:run
- 3.前台启动：导入项目，进入控制台，到项目所在路径，执行命令：npm run dev，访问地址：http://localhost:8075  进入到登录界面，打开数据库中t_reader表获取用户名和密码
#### 包的结构
```agsl
 +- libraryms-Vue
     +- build --
        +- build.js --
        +- check-versions.js --
        +- logo.png --
        +- utils.js --
        +- vue-loader.conf.js --
        +- webpack.base.conf.js --
        +- webpack.dev.conf.js --
        +- webpack.prod.conf.js --
     +- config --
        +- dev.env.js --
        +- index.js --
        +- prod.env.js --
     +- src
        +- assets -- 静态资源文件 如图片、字体等
        +- components -- Vue 组件
        +- router -- 路由配置
        +- App.vue -- 根组件 协调整个应用程序的视图和管理应用程序的状态
        +- main.js -- 项目的入口文件
        +- tip --
     +- static --
     +- .babelrc --
     +- .editorconfig --
     +- .eslintgnore --
     +- .eslintrc.js --
     +- .gitignore -- 指定需要 Git 忽略的文件或目录
     +- .postcssrc.js --
     +- db_appapidemo.sql --
     +- index.html --
     +- LICENSE -- 开源软件的授权协议
     +- packge.json -- 项目元数据的文件 用于描述 Node.js 应用程序或模块的属性
     +- packge-lock.json -- 锁定当前安装的包的版本号和依赖关系
     +- READE.md -- 项目的相关信息文档
```

#### 效果展示
![](https://github.com/yangyuscript/Vue-iView-demo/blob/master/static/1.png?raw=true)
![](https://github.com/yangyuscript/Vue-iView-demo/blob/master/static/2.png?raw=true)
![](https://github.com/yangyuscript/Vue-iView-demo/blob/master/static/3.png?raw=true)
![](https://github.com/yangyuscript/Vue-iView-demo/blob/master/static/4.png?raw=true)
![](https://github.com/yangyuscript/Vue-iView-demo/blob/master/static/5.png?raw=true)
![](https://github.com/yangyuscript/Vue-iView-demo/blob/master/static/6.png?raw=true)
![](https://github.com/yangyuscript/Vue-iView-demo/blob/master/static/7.png?raw=true)
![](https://github.com/yangyuscript/Vue-iView-demo/blob/master/static/8.png?raw=true)
![](https://github.com/yangyuscript/Vue-iView-demo/blob/master/static/9.png?raw=true)


#### tip
鉴于star该项目的同学越来越多，鄙人觉得应当补充以上信息供大家交流学习，如果大家有任何建议均可issue，一定尽一切办法解决各位的问题，希望大家一起进步，oh yeah!

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
