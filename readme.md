## moell/webim
PHP + Swoole 开发的简单聊天室demo, 主要是 websockt 的应用,欢迎 start 。

## 环境要求
* PHP >= 7.0
* Swoole
* composer
## 安装
```
composer create-project -s dev bigfool-cn/SwooleChat
```
or
```
git clone https://github.com/bigfool-cn/SwooleChat.git
composer install
```

## 启动 websockt
```
cd ./SwooleChat
php webim_server.php
```

## 启动 PHP 内置服务器
```
cd ./public
php -S localhost:8000
```
浏览器访问 localhost:8000 即可进入聊天

## 参考项目
![webim](https://github.com/moell-peng/webim.git "webim")

## License
MIT
