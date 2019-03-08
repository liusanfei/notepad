# notepad
id=liusanfei:qq

参考一
原版项目地址 http://phpminiadmin.sourceforge.net/

下载选择 phpMiniAdmin 1.9.170730版
下载地址 https://sourceforge.net/projects/phpminiadmin/files/phpminiadmin/phpminiadmin-1.9.170730/

地址1 https://sourceforge.net/projects/phpminiadmin/files/phpminiadmin/
地址2 https://github.com/osalabs/phpminiadmin    仅有 $VERSION='1.9.170730';

变动日志
changes in phpMiniAdmin 1.9.150729
switched to MySQLi because MySQL extension deprecated in PHP7
......
changes in phpMiniAdmin 1.9.150917
- fixed: query error handling
......
这里选择 1.9.170730版 2017-07-30

参考二
原版项目地址 https://www.phpliteadmin.org/

参考三
原版项目地址 https://www.adminer.org/
3.1.0

Architecture of Adminer
https://php.vrana.cz/architecture-of-adminer.php

MSSQL PHP扩展
https://github.com/Microsoft/msphpsql/releases
mssql驱动下载介绍
https://www.cnblogs.com/huixch/p/7065033.html

耶鲁大学2004发布的SSO项目 被广泛使用
https://en.wikipedia.org/wiki/Central_Authentication_Service

常用连接池
C3P0，DBCP停止更新
HikariCP，spring项目默认连接池
R.I.P 性能好
tomcat jdbc pool
Druid 阿里巴巴

网络I/O模型有四五种

1. Blocking IO模型
# 同步阻塞

2. Non-Blocking IO模型
# 同步非阻塞
# 虽然名字叫非阻塞，其实是阻塞的，后面那个异步IO才是真的非阻塞

3. I/O Multiplexing模型，又叫Reactor模型，又叫Select模型，又叫事件驱动模型
# NIO里面有这个吧，Java 1.4的时候，是说Java实现了一个select()函数
# 同步阻塞

4. Asynchronous I/O模型，又叫Proactor模型
# Java 1.7的时候，NIO 2.0有了AIO
# 异步非阻塞

5. Signal Driven I/O模型（这种忽略）
# 同2
