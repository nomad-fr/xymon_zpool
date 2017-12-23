# xymon_zpool

#### Dependencies 

* awk

#### Configuration

* add this to : /usr/local/www/xymon/client/etc/clientlaunch.cfg

~~~
[zfs]
        ENVFILE $XYMONCLIENTHOME/etc/xymonclient.cfg
        CMD /usr/local/www/xymon/client/ext/zfs
        LOGFILE /usr/local/www/xymon/client/logs/zfs.log
        INTERVAL 1m
~~~

