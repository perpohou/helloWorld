聊天室_chat

1、功能：实现多人实时聊天

2、实现要求：
   ①导入os、tornado模块
   ②浏览器要求：IE 10+、FF 34+、Chrome 31+、 Safari 		7.1+、Android Browser 4.4+

3、执行：
   ①运行：start.py
   ②在浏览器打开：localhost:8181
   ③可在浏览器中打开多个localhost:8181窗口模拟多人聊天

4、采用的工具：tornado、websocket接口
   ①tornado：web server框架，采用异步IO网络模型，支持websocket，可用于写web服务、数据接口，有很多不错的特性被广泛使用，如知乎即用tornado写的
   ②websocket：html5中新协议，相比于HTTP协议（通过客户端不断发送请求给服务端，即不断刷新页面的方式模拟实时链接），websocket支持持久连接（套接字的链接，只发送一次请求，服务端就会不断地主动推送信息给客户端），实现客户端与服务端实时及双向的通信。

