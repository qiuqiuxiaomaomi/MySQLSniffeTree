# MySQLSniffeTree
mysql语句审计工具

![](https://i.imgur.com/amcW9Zp.png)



<pre>
MySQL Sniffer 

      是一个基于360开源的 MySQL 协议的抓包工具，实时抓取 MySQLServer 端的请求，并格
      式化输出。输出内容包访问括时间、访问用户、来源 IP、访问 Database、命令耗时、返回数据
      行数、执行语句等。有批量抓取多个端口，后台运行，日志分割等多种使用方式.

      虽然我们可以打开MySQL的所有SQL语句记录设置，设置方法,在my.cnf的mysqld项下
      加入:log=/var/mysqllog/sql.log 但是这样做，會记录全部SQL查询，如果网站访问
      量很大，日志增长也会很快，容易导致硬盘满，也不方便分析SQL语句，同时也会增加数据
      库服务器负担。而MySQLSniffer可以不必生成日志文件，且可以跟踪特定的SQL查询，所
      以这时候就是MySQLSniffer发挥作用的时候
</pre>

###ER建模图

![](https://i.imgur.com/As8VMe7.png)

###Mysql性能

![](https://i.imgur.com/toSex5z.png)

<pre>
Mysql workbench
</pre>