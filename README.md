# 互联网+文档

本资料由云南大学网络与信息中心根据各类图书、资料、网络文章汇编、整理或创建而来。如有侵权，告知即删。

### 编译
- 安装全局gitbook，执行`npm install -g gitbook-cli`
- 切换到Learning子目录中，执行`cd Learning`
- 执行`gitbook serve`
- 在浏览器中打开[http://localhost:4000](http://localhost:4000)
- 编译为其他格式(需要安装[calibre-ebook](http://calibre-ebook.com/download))，如pdf、epub、mobi等可参考其gitbook帮助信息，执行`gitbook help`

### 发布到自己的gh-pages

- 安装nodejs
- 安装依赖库，执行`npm install`
- 安装全局grunt-cli，执行`npm install -g grunt-cli`
- 安装全局gitbook，执行`npm install -g gitbook-cli`
- 发布，执行`grunt`
- 打开自己项目的pages网址查看，http://ynu.github.io/internet_plus_documentations

