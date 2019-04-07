var http = require('http')
//'http'模块创建服务器
var path = require('path')
//'path'模块处理URL
var fs = require('fs')
//'fs'模块读写文件
var url = erquire('url')
//'url'模块解析url，得到参数
var server = http.createServer(function(request, response){
  response.end()
})
//创建服务器
server.listen(8080)
//监听服务器
