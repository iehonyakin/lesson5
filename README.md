[root@lvm vagrant]# history
    1  vi /etc/sysconfig/watchlog
    2  vi /var/log/watchlog.log
    3  vi /opt/watchlog.sh
    4  #!/bin/bash
    5  WORD=$1
    6  LOG=$2
    7  DATE=`date`
    8  if grep $WORD $LOG &> /dev/null; then else
    9  exit 0
   10  systemctl start watchlog.timer
   11  cat /etc/sysconfig/watchlog.timer
   12  move /etc/sysconfig/watchlog /etc/sysconfig/watchlog.service
   13  mv /etc/sysconfig/watchlog /etc/sysconfig/watchlog.service
   14  ls
   15  systemctl start watchlog.timer
   16  systemctl daemon-reload
   17  systemctl start watchlog.timer
   18  cat /etc/sysconfig/watchdog
   19  cat /etc/sysconfig/watchlog.service
   20  cat /etc/sysconfig/watchlog.timer
   21  cat /etc/sysconfig/watchlog.service
   22  vi /etc/sysconfig/watchlog.service
   23  cat /etc/sysconfig/watchlog.timer
   24  systemctl start watchlog.timer
   25  cat /etc/sysconfig/watchlog.timer
   26  cat /etc/sysconfig/watchdog
   27  rm /etc/sysconfig/watchdog
   28  chmod +x /opt/watchlog.sh
   29  systemctl start watchlog.timer
   30  vi /etc/sysconfig/watchlog.timer
   31  systemctl start watchlog.timer
   32  vi /etc/sysconfig/watchlog.timer
   33  systemctl start watchlog.timer
   34  ls -la /etc/sysconfig/
   35  vi /etc/sysconfig/watchlog
   36  systemctl start watchlog.timer
   37  vi /etc/sysconfig/watchlog.service
   38  systemctl start watchlog.timer
   39  vi /etc/sysconfig/watchlog.timer
   40  cat /opt/watchlog.sh
   41  vi /etc/sysconfig/watchlog.timer
   42  systemctl start watchlog.timer
   43  vi /etc/sysconfig/watchlog.timer
   44  vi /etc/sysconfig/watchlog.service
   45  yum install watchdog -y
   46  systemctl start watchlog.timer
   47  find -name watchdog
   48  find -name watchlog
   49  find /etc -name watchlog
   50  find /etc -name watchdog
   51  find / -name watchdog
   52  cp /usr/sbin/watchdog /etc/sysconfig/
   53  systemctl start watchlog.timer
   54  systemctl start watchlog.timer
   55  ls -la /etc/sysconfig/
   56  ls -la /etc/sysconfig/watchdog/
   57  cat /etc/sysconfig/watchdog
   58  systemctl start watchlog
   59  systemctl list-units
   60  systemctl list-units | grep watchlog
   61  cp /etc/sysconfig/watchlog.timer /etc/systemd/
   62  systemctl start watchlog.timer
   63  cp /etc/sysconfig/watchlog.timer /etc/systemd/system
   64  systemctl start watchlog.timer
   65  cp /etc/sysconfig/watchlog.service /etc/systemd/system
   66  systemctl start watchlog.timer
   67  ps -auxf
   68  tail -f /var/log/messages
   69  tail -f /var/log/watchlog.log
   70  tail -f /var/log/messages
   71  tail -f /var/log/messages
   72  tail -f /var/log/messages
   73  systemctl start watchlog.timer
   74  systemctl status watchlog.timer
   75  tail -f /var/log/messages
   76  systemctl stop watchlog.timer
   77  tail -f /var/log/messages
   78  systemctl start watchlog.timer
   79  tail -f /var/log/messages
   80  ls /etc/systemd/system/
   81  ls -la /etc/systemd/system/
   82  cat /etc/systemd/system/watchlog.timer
   83  cat /etc/systemd/system/watchlog.service
   84  cat /opt/watchlog.sh
   85  cat /opt/watchlog.sh
   86  cat /etc/sysconfig/watchlog
   87  vi /etc/sysconfig/watchlog
   88  cat /opt/watchlog.sh
   89  vi /var/log/watchlog.log
   90  tail -f /var/log/messages
   91  rm /etc/sysconfig/watchdog
   92  tail -f /var/log/messages
   93  systemctl stop watchlog.timer
   94  systemctl start watchlog.timer
   95  tail -f /var/log/messages
   96  cat /opt/watchlog.sh
   97  ls /etc/systemd/system/
   98  rm  /etc/systemd/watchlog.timer
   99  ls /etc/systemd/
  100  ls /etc/systemd/system
  101  ls -la /etc/systemd/system
  102  cat /etc/systemd/system/watchlog.
  103  cat /etc/systemd/system/watchlog.service
  104  systemctl start watchlog.service
  105  tail -f /var/log/messages
  106  cat /etc/systemd/system/watchlog.service
  107  cat /etc/sysconfig/watchlog
  108  cat /etc/systemd/system/watchlog.service
  109  vi /etc/systemd/system/watchlog.service
  110  systemctl start watchlog.service
  111  systemctl daemon-reload
  112  systemctl start watchlog.service
  113  systemctl stop watchlog.timer
  114  systemctl start watchlog.timer
  115  tail -f /var/log/messages
  116  tail -f /var/log/messages
  117  systemctl status watchlog.timer
  118  systemctl status watchlog.service
  119  systemctl start watchlog.service
  120  systemctl status watchlog.service
  121  tail -f /var/log/messages
  122   yum install epel-release -y && yum install spawn-fcgi php php-cli
  123  cat /etc/rc.d/init.d/spawn-fcg
  124  ls -l /etc/rc.d/init.d/spawn-fcg/
  125  cat /etc/rc.d/init.d/spawn-fcg
  126  ls -l /etc/rc.d/init.d/
  127  cat /etc/rc.d/init.d/spawn-fcgi
  128  vi /etc/rc.d/init.d/spawn-fcgi
  129  vi /etc/sysconfig/spawn-fcgi
  130  vi /etc/sysconfig/spawn-fcgi
  131  vi /etc/systemd/system/spawn-fcgi.service
  132  systemctl start spawn-fcgi
  133  systemctl status spawn-fcgi
  134  vi /etc/systemd/system/spawn-fcgi.service
  135  vi /etc/sysconfig/spawn-fcgi
  136  vi /etc/sysconfig/httpd-first
  137  vi /etc/sysconfig/httpd-second
  138  vi /etc/sysconfig/httpd-second
  139  vi /etc/sysconfig/httpd-first
  140  vi /etc/sysconfig/httpd-second
  141  vi /etc/sysconfig/httpd
  142  vi /etc/systemd/system/httpd
  143  systemctl start httpd@first
  144  vi /etc/systemd/system/httpd
  145  systemctl start httpd@first
  146  systemctl start httpd
  147  systemctl status httpd
  148  systemctl stop httpd
  149  systemctl start httpd@second
  150  vi /etc/systemd/system/httpd
  151  systemctl start httpd@second
  152  vi /etc/sysconfig/httpd-first
  153  vi /etc/systemd/system/httpd
  154  systemctl start httpd@second
  155  ls /etc/sysconfig/
  156  ls /etc/sysconfig/httpd/
  157  ls /etc/sysconfig/
  158  cat /etc/httpd/conf/httpd.conf
  159  cp /etc/httpd/conf/httpd.conf /etc/httpd/conf/first.conf
  160  systemctl start httpd@first
  161  cp /etc/httpd/conf/httpd.conf /etc/httpd/conf/second.conf
  162  vi /etc/systemd/system/httpd
  163  systemctl start httpd@first
  164  vi /etc/sysconfig/httpd-first
  165  vi /etc/sysconfig/httpd-first
  166  systemctl start httpd@first
  167  systemctl start httpd
  168  systemctl stop httpd
  169  vi /etc/systemd/system/httpd
  170  vi /etc/sysconfig/httpd-first
  171  vi /etc/sysconfig/httpd-second
  172  vi /etc/httpd/conf/first.conf
  173  grep -i pid /etc/httpd/conf/first.conf
  174  vi /etc/httpd/conf/first.conf
  175  systemctl start httpd@first
  176  cp /etc/systemd/system/httpd /etc/systemd/system/httpd@first
  177  cp /etc/systemd/system/httpd /etc/systemd/system/httpd@second
  178  systemctl start httpd@first
  179  cp /etc/systemd/system/httpd /etc/systemd/system/httpd@first.service
  180  cp /etc/systemd/system/httpd /etc/systemd/system/httpd@second.service
  181  systemctl start httpd@first
  182  systemctl status httpd@first.service
  183  systemctl status httpd
  184  systemctl status httpd@first
  185  vi /etc/httpd/conf/first.conf
  186  systemctl start httpd@first
  187  systemctl status httpd@first.service
  188  vi /etc/httpd/conf/first.conf
  189  systemctl status httpd@first.service
  190  systemctl status httpd@first.service
  191  vi /etc/httpd/conf/first.conf
  192  systemctl daemon-reload
  193  systemctl start httpd@first
  194  systemctl start httpd@second
  195  systemctl status httpd@second.service
  196  vi /etc/httpd/conf/second.conf
  197  systemctl status httpd@second.service
  198  systemctl daemon-reload
  199  systemctl start httpd@second
  200  systemctl status httpd@second
  201  ss -tnulp | grep httpd
  202  ls -la
  203  cat /root/.bash_history
  204  exit
  205  history
[root@lvm vagrant]#






[root@lvm vagrant]# systemctl status spawn-fcgi
● spawn-fcgi.service - Spawn-fcgi startup service by IEHonyakin
   Loaded: loaded (/etc/systemd/system/spawn-fcgi.service; disabled; vendor preset: disabled)
   Active: active (running) since Sun 2019-11-24 16:52:32 UTC; 1h 13min ago
 Main PID: 3229 (php-cgi)
   CGroup: /system.slice/spawn-fcgi.service
           ├─3229 /usr/bin/php-cgi
           ├─3230 /usr/bin/php-cgi
           ├─3231 /usr/bin/php-cgi
           ├─3232 /usr/bin/php-cgi
           ├─3233 /usr/bin/php-cgi
           ├─3234 /usr/bin/php-cgi
           ├─3235 /usr/bin/php-cgi
           ├─3236 /usr/bin/php-cgi
           ├─3237 /usr/bin/php-cgi
           ├─3238 /usr/bin/php-cgi
           ├─3239 /usr/bin/php-cgi
           ├─3240 /usr/bin/php-cgi
           ├─3241 /usr/bin/php-cgi
           ├─3242 /usr/bin/php-cgi
           ├─3243 /usr/bin/php-cgi
           ├─3244 /usr/bin/php-cgi
           ├─3245 /usr/bin/php-cgi
           ├─3246 /usr/bin/php-cgi
           ├─3247 /usr/bin/php-cgi
           ├─3248 /usr/bin/php-cgi
           ├─3249 /usr/bin/php-cgi
           ├─3250 /usr/bin/php-cgi
           ├─3251 /usr/bin/php-cgi
           ├─3252 /usr/bin/php-cgi
           ├─3253 /usr/bin/php-cgi
           ├─3254 /usr/bin/php-cgi
           ├─3255 /usr/bin/php-cgi
           ├─3256 /usr/bin/php-cgi
           ├─3257 /usr/bin/php-cgi
           ├─3258 /usr/bin/php-cgi
           ├─3259 /usr/bin/php-cgi
           ├─3260 /usr/bin/php-cgi
           └─3261 /usr/bin/php-cgi

Nov 24 16:52:32 lvm systemd[1]: Started Spawn-fcgi startup service by IEHonyakin.
Nov 24 16:52:32 lvm systemd[1]: Starting Spawn-fcgi startup service by IEHonyakin...
[root@lvm vagrant]#





[root@lvm vagrant]# ss -tnulp | grep httpd
tcp    LISTEN     0      128      :::8080                 :::*                   users:(("httpd",pid=6441,fd=4),("httpd",pid=6440,fd=4),("httpd",pid=6439,fd=4),("httpd",pid=6438,fd=4),("httpd",pid=6437,fd=4),("httpd",pid=6436,fd=4))
tcp    LISTEN     0      128      :::80                   :::*                   users:(("httpd",pid=6248,fd=4),("httpd",pid=6247,fd=4),("httpd",pid=6246,fd=4),("httpd",pid=6245,fd=4),("httpd",pid=6244,fd=4),("httpd",pid=6243,fd=4))
[root@lvm vagrant]#






[root@lvm vagrant]# tail -f /var/log/messages
Nov 24 18:08:05 localhost systemd: Started My watchlog service.
Nov 24 18:08:35 localhost systemd: Starting My watchlog service...
Nov 24 18:08:35 localhost root: Sun Nov 24 18:08:35 UTC 2019: I found word, Master!
Nov 24 18:08:35 localhost systemd: Started My watchlog service.
Nov 24 18:09:05 localhost systemd: Starting My watchlog service...
Nov 24 18:09:05 localhost root: Sun Nov 24 18:09:05 UTC 2019: I found word, Master!
Nov 24 18:09:05 localhost systemd: Started My watchlog service.
Nov 24 18:09:35 localhost systemd: Starting My watchlog service...
Nov 24 18:09:35 localhost root: Sun Nov 24 18:09:35 UTC 2019: I found word, Master!
Nov 24 18:09:35 localhost systemd: Started My watchlog service.

