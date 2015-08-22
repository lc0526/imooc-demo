# imooc-demo
imooc movie demo

> 这个demo纯粹为了练手，总是使用git上面的开元代码，自己基本没怎么往git上面上传过，这份代码就是为了练手

### express+jade+mongo 搭建的一个简易的电影网站，思路来源于 imooc

### 使用说明：（以下内容仅针对mac系统，其他未测试）
- git clone 到本地
- 确保你的电脑上面有node、mongo的环境
- 确保你的npm、bower（可通过npm install bower -g来安装）命令可正常使用
- 安装通过npm安装的依赖包：express、jade、underscore、body-parser、moment、mongoose（package.json文件中列出）
- 安装通过bower安装的依赖包：bootstrap （bower.json文件中列出）
- 启动 (PORT=指定端口号) node app.js ，默认端口号是3000


### 几点说明
- 启动node 之前，要运行起来你本地的mongo环境（命令行：mongod可启动）
- 修改所使用的数据库：线上的代码默认使用的是imooc 这个数据库（mongoose.connect('mongodb://localhost/imooc')），可以在入口文件 app.js 里面修改为你想要的任意名字
