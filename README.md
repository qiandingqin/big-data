# big-data 华夏云城精准云扶贫大屏指挥客户端

项目使用 node、vue开发客户端 ES6开发

框架使用electron 框架。vue使用脚本方式 没有使用vue-cli 做的时候electron 还没推出vue支持 现在出了。

https://electron.org.cn/ electron官网

微软Visual Studio Code 编辑器也是使用这个框架

遇到难点-页面切换白屏等问题。当时并没有好的解决方案 所以自己封装了一个较为简单的框架-具体思路类似vue路由。

将已有页面 放入内存需要的时候渲染即可。

项目内图表功能使用百度的echarts制作，后端为python+java 其中python作为中介服务器，java为底层服务器 数据库使用mongdb
 
 运行方法：需要有npm环境 npm安装node自带
 
 1. npm install -g electron 
 
 2. npm install 
 
 3. electron .

目录--简要说明

项目根目录--
--node_modules node模块
--static 静态资源
----js
	--main 主程序 electron 叫主进程文件
	--view 渲染进程
--view 视图
--config.js 配置文件
--main.js   入口
--package.json node包配置清单-也是electron一些参数的配置