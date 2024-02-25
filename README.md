<div style="background-color: #ffcc00; color: #ffffff; padding: 10px; border: 1px solid #ff9900;">
 网站正在建设中
 </div>

这里是**油腻猪宝**的**笔记本**
\\(\^o\^)/~**

[传送门](https://greasypiggy.github.io)


笔记本使用hexo框架搭建，基于butterfly主题进行更改

## TODO LIST

+ 二级目录
+ 外观美化
+ 渲染插件
+ 笔记内容


## 本地构建
1. 安装Node.js与npm工具、hexo框架

```shell
sudo apt-get install nodejs
sudo apt-get install npm

npm install -g hexo-cli
```

2. 拉取README分支

```shell
git clone -b README https://github.com/GreasyPiggy/GreasyPiggy.github.io.git
```

3. 本地预览

```shell
hexo clean
hexo generate #hexo g
hexo server
```
在[本地地址](https://localhost:4000)即可进行预览