# big-data 华夏云城精准云扶贫大屏指挥客户端

项目使用 node、vue开发客户端

框架使用electron 框架。vue使用脚本方式 没有使用vue-cli 做的时候electron 还没推出vue支持 现在出了。

微软Visual Studio Code 编辑器也是使用这个框架

遇到难点-页面切换白屏等问题。当时并没有好的解决方案 所以自己封装了一个较为简单的框架-具体思路类似vue路由。

将已有页面 放入内存需要的时候渲染即可。

项目内图表功能使用百度的echarts制作，后端为python+java 其中python作为中介服务器，java为底层服务器 数据库使用mongdb
 
