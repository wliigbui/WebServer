# WebServer
##  1、主要模块及功能
###  1.1 网络通信模块  
  Socket编程：处理网络连接，监听客户端数据  
  协议处理：解析和生成HTTP/HTTPS请求和响应  
###  1.2 请求处理模块  
  请求解析：解析HTTP请求头、请求体、URL和查询参数  
  路由：将请求路由到响应的处理函数和页面  
  请求调度：根据请求类型（GET,POST）调用不同的处理逻辑  
###  1.3 响应生成模块  
  响应构造：创建HTTP响应头和响应体，设置状态码和内容
  内容类型处理：根据请求生成适当的MIME类型，如HTML,JSON,图片等  
  
