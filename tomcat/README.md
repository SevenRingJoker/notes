# Tomcat

Tomcat是web容器

做web项目时，多数需要http协议，也就是基于请求和响应

比如你在百度输入一行内容搜索，那么百度服务器如何处理这个请求呢，他需要创建servlet来处理

servlet其实就是java程序，只是在服务器端的java程序，servlet通过配置文件拦截你的请求，并进行相应处理，然后展示给你相应界面，那么servlet如何创建？

 这时候tomcat用到了，它就是帮助你创建servlet的东西，所以也称web容器，没有它，没法运行web项目。

 Tomcat是一个应用服务器。他可以运行你按照J2EE中的Servlet规范编写好的Java程序。

 简单的说它是一个Web网站的运行容器，把你写好的网站放进去就可以运行。

 Tomcat是应用（java）服务器，它只是一个servlet容器，是Apache的扩展，处理动态网页部分。

 Eclipse+tomcat=网络应用，如JSP类应用
