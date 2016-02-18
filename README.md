##HTML5 postMessage()方法的使用demo

此demo使用webpack-dev-server作为简单web server 

使用如下命令安装`webpack-dev-server`

`npm install -g webpack-dev-server`

进入demo目录，打开两个命令行窗口,分别执行如下命令：

`webpack-dev-server --host www.sai.com`

`webpack-dev-server --host demo.sai.com --port 8081`

执行这两条命令前还需要修改host文件,添加如下内容:

```
  127.0.0.1 www.sai.com
  127.0.0.1 demo.sai.com
```

最后在浏览器中访问www.sai.com:8080/sender.html查看demo
