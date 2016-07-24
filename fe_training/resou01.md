## 开发环境

前端开发用到的基本技术主要是HTML，CSS和JavaScript，很多其它前端技术都是由这三样衍生过来的。在项目开发时，可以使用一些工具来方便开发过程。这些工具和平台构成了你的开发环境。

## 相关工具
- 切图工具：Ps
- 编辑工具：Sublime Text，Webstorm，Brackets
- 调试工具：Google Developer Tools，Firebug
- 协同工具：Github，SVN
- 构建工具：gulp，webpack，fis
- 模块化工具：Require.js，Sea.js
- 项目管理工具：tower
- 接口文档编写工具

## Ps教程
- [基本方法](http://www.jianshu.com/p/2027afc995d9)
- [特殊切图](http://www.jianshu.com/p/1031b8aee925)

## Git教程
- 资料
 - [Git教程](http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000/00137628548491051ccfaef0ccb470894c858999603fedf000)
 - 书籍
    - Github入门与实践
    - Git权威指南 
- 准备
 - 注册Github账号：打开Github官网自行注册。
 - 安装Git：打开Git官网安装相应操作系统版本的Git。
 - 设置git姓名和邮箱
 ~~~
# 设置姓名
git config --global user.name "用户名"
# 设置邮箱
git config --global user.email "邮箱"
 ~~~
 - 创建和添加密钥
 ~~~
 # 创建密钥
 ssh-keygen -t rsa -C "注册Github账号时使用的邮箱"
 ~~~
- 基本操作
 - 从远程克隆仓库到本地
 ~~~
 # 克隆远程仓库（如用户名为fdzqz，仓库名为trainingTask）
 git clone git@github.com:fdzqz/trainingTask.git
 ~~~
 - 如何添加，提交，推送文件
 ~~~
 # 添加文件到暂存区（如文件夹名为demo）
 git add demo
 # 提交文件到版本库
 git commit -m "demo(必填，对于这次提交的描述)"
 # 推送文件到远程仓库
 git push -u origin master
 ~~~
**git push之后就可以在github上看见你上传的代码了**
 - 如何创建、切换和推送分支
 ~~~
 # 创建分支（如建立gh-pages分支）
 git checkout gh-pages
 # 切换分支
 git branch gh-pages
 # 在创建时同时切换
 git checkout -b gh-pages
 # 推送分支
 git push origin gh-pages
 ~~~
**创建gh-pages后添加相应静态文件就可以在github看见静态网页效果了（可通过输入http://用户名.github.io/仓库名/html文件在仓库的相对地址 访问）**

## Google Developer Tools（谷歌调试工具）
- 资料
 - [Chrome开发者工具不完全指南](https://www.zhihu.com/question/34682699/answer/81858413)：这个教程写的很详细了，大家做前两个任务的时候可以先看第一篇（讲element功能），后面完成第三次任务（js组件）的时候可以看下第二篇（讲sources和console功能）来调试js代码，Google Dev Tools其它功能可以到时候需要或者做项目的时候再去看。

## Sublim Text
- 资料
 - [Sublime Text教程](https://segmentfault.com/a/1190000004204640)：主要是快捷键和插件的使用，常见的快捷键最好全部记住，插件的话看自己的使用情况自行安装。


