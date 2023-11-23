#### 1 必要软件安装
##### 1.1 nodejs安装
去nodejs官网下载并安装nodejs，如果安装成功在命令窗口使用命令 **node -v** 将看到
```shell
v16.16.0
```
##### 1.2 安装yarn
安装号nodejs后，默认会自带安装好npm工具，使用命令 **npm install -g yarn**进行安装，如果安装成功，使用命令**yarn -v**将看到：
```shell
1.22.19
```
##### 1.3 安装vue-cli
vue-cli是一个脚手架工具，使用命令**npm install -g @vue/cli**,如果安装成功使用命令**vue -V**将看到：
```shell
@vue/cli 5.0.8
```

#### 2.项目创建
使用命令**vue create cedis-front**进行创建，在创建过程中会有一些交互选项，这里我们选择vue2版本，使用yarn进行构建，创建成功后会得到一个目录结构如下：
```txt
|--node_modules: 第三方库
|--public： 公共资源
|--src
|   |--assets
|   |--components
|   |--App.vue
|   |--main.js ：整个项目程序的入口文件
|--.gitignore
|--babel.config.js
|--jsconfig.json
|--package.json
|--README.md： 项目的readme文件
|--vue.config.js
|--yarn.lock
```

#### 3. 安装element-ui
使用命令 **npm install element-ui -S**进行安装，如果安装成功在package.json文件的dependencies将多了element-ui依赖，如下：
```
 "dependencies": {
    "core-js": "^3.8.3",
    "element-ui": "^2.15.14",
    "vue": "^2.6.14"
  }
  ```
