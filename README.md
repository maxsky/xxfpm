# xxfpm
FCGI Process Manager

这是一个原作者 **[78](https://github.com/78)** 在 2011 年写的跨平台 FastCGI 进程管理器，可用作 PHP 的进程管理。

## 使用方式

	2017 年 12 月 27 日更新，默认端口修改为 9000，path 参数（路径）支持空格


```
Usage: xxfpm path [-n number] [-i ip] [-p port]
Manage FastCGI processes.

-n, –number number of processes to keep
-i, –ip ip address to bind
-p, –port port to bind, default is 9000
-u, –user start processes using specified linux user
-g, –group start processes using specified linux group
-r, –root change root direcotry for the processes
-h, –help output usage information and exit
-v, –version output version information and exit
```

## 相关博文

http://xiaoxia.org/2011/02/01/xxfpm-wrote-a-fastcgi-process-manager/
