# angular1.js
用于学习和记录一些有用的组件、指令、过滤器等。

<p align="center">
    <a href="https://github.com/keep-study/angular1.js/graphs/code-frequency" target='_blank'>
        <img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/keep-study/angular1.js">
    </a>
    <a href="https://github.com/keep-study/angular1.js/graphs/commit-activity" target='_blank'>
        <img alt="GitHub repo commit" src="https://img.shields.io/github/last-commit/keep-study/angular1.js">
    </a>
    <a href="https://github.com/keep-study/angular1.js" target='_blank'>
        <img alt="GitHub repo stars" src="https://img.shields.io/github/stars/keep-study/angular1.js?style=social">
    </a>
</p >

## 如何使用

开发的时候运行下列命令：

```
npm run dev
```

开发完毕需要发布的时候，请运行下列命令：

```
npm run build
```

## 项目说明

首先看看目录结构：

    - build 打包后的公共JS和CSS文件，用于生产环境
    - htmls 交易代码主要在这里开发
    - images 图片资源
    - libs 公共的JS一般存放在这里
      - min 一般存放angular、jquery等最基本的公共第三方JS
      config.js 项目启动入口，包括路由、请求等配合和公共方法等（备注：当然可以拆分成多个文件）
      preload.js 帮忙加载资源的，用于开发环境
    - styles 样式CSS文件
    .csslint css语法校验规则
    .jshintrc js语法校验规则
    Gruntfile.js 打包插件Grunt.js配置文件
    index.html 项目入口（这里打开以后会首先运行项目启动入口）
    jshint.debug.txt js语法校验结果（css的会直接打印在控制台）
    package.json 项目信息，依赖的包和脚本都配置文件

## Angular1.js笔记

- [项目启动过程](./notebook/run.md)
