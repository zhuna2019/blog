webSocket 开发流程
#浏览器自带对象WebSocket
     #由于 自带对象WebSocket工作复杂/使用第三方
     #WebSocket库来实现此功能
     #库名 socket.io
     (1)下载socket.io服务器端第三方模块
       #npm i socket.io
       下载socket.io 客户端文件
       #socket.io.js
       https://cdnjs.cloudflare.com/ajax/libs/socket.io/2.0.3/socket.io.js
     (2)先开发服务器端程序
       2.1:创建服务器对象
       2.2:创建websocket.io对象
       2.3:监听端口 3000
       2.4:为io对象绑定事件 connection 客户端连接
     (3)开发客户端程序
       3.1:创建socket对象并且连接websocket服务器
