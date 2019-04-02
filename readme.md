
### PHP + Swoole 开发的简单聊天室demo, 欢迎 start 。
项目加入task异步任务，所有聊天信息交给task处理。
[在线体验](http:chat.bigfool.cn)

## 环境要求
* PHP >= 7.0
* Swoole
* composer

## 安装
```
git clone https://github.com/bigfool-cn/SwooleChat.git
composer install
```

## 启动 websockt服务
```
cd ./SwooleChat
php webim_server.php
```

## 启动 PHP 内置服务器 or 使用nginx代理html
```
cd ./public
php -S localhost:8000
```
浏览器访问 localhost:8000 即可进入聊天

## 参考项目
[webim](https://github.com/moell-peng/webim.git "webim")

## License
MIT
