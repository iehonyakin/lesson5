Развернул сервисы, все удалось, все работае.

приложил history.
приложил vagrant конфиг, в нем дописал автосоздание и поднятие сервисов.





[root@lvm vagrant]# ss -tnulp | grep httpd
tcp    LISTEN     0      128      :::8080                 :::*                   users:(("httpd",pid=6441,fd=4),("httpd",pid=6440,fd=4),("httpd",pid=6439,fd=4),("httpd",pid=6438,fd=4),("httpd",pid=6437,fd=4),("httpd",pid=6436,fd=4))
tcp    LISTEN     0      128      :::80                   :::*                   users:(("httpd",pid=6248,fd=4),("httpd",pid=6247,fd=4),("httpd",pid=6246,fd=4),("httpd",pid=6245,fd=4),("httpd",pid=6244,fd=4),("httpd",pid=6243,fd=4))
[root@lvm vagrant]#
