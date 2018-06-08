# blog_new

blog_new 一个个人blog系统，用于熟悉node+mysql后台管理系统

1、node.js+mysql项目搭建


2、项目功能：
    

>    A 登录系统：用户填写用户名和密码，登录到后台管理系统中。用户可以修改自己的注册信息

>    B 注册：可以注册用户，创建用户，进行blog得编写。

>    C 添加、编辑、修改、删除 blog信息。并公布哪些可以隐藏，哪些显示

3、前端:
  
  vue+vue-router+axios+element_ui

4、后台：
   
  node+express

5、数据库：
   
  mysql或者mongodb

6、项目搭建：
  
    vue-cli + node + express + mongodb +axios+vue-router

![](https://i.imgur.com/x1VOmBw.png)

7、项目结构：

  blog_new:
          client(vue前端项目)
          server（express服务器端项目）



  client项目结构：（前端）
          
          安装 $ vue init <template-name> <project-name>

![](https://i.imgur.com/phrBWRT.png)

![](https://i.imgur.com/xUSOXQ2.png)

 server项目结构：（后台）

     安装：$ npm install express-generator -g

	$ express server
	
	   create : server
	   create : server/package.json
	   create : server/app.js
	   create : server/public
	   create : server/public/javascripts
	   create : server/public/images
	   create : server/routes
	   create : server/routes/index.js
	   create : server/routes/users.js
	   create : server/public/stylesheets
	   create : server/public/stylesheets/style.css
	   create : server/views
	   create : server/views/index.jade
	   create : server/views/layout.jade
	   create : server/views/error.jade
	   create : server/bin
	   create : server/bin/www

	    $ cd server 
	    $ npm install

    $ DEBUG=myapp npm start