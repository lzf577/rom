# rom

1.空的什么都没有

2.v2ray ssr frp wol 网络共享

3.和2一样，但更大

固件用于xiaomi mini 

进tmp目录

~~~bash
cd /tmp
~~~

下载

~~~bash
wget http://github.com/lzf577/rom/raw/main/x.bin /tmp
~~~


强刷
~~~bash
mtd write /tmp/x.bin firmware
~~~

恢复出厂

~~~bash
firstboot
~~~

重启

~~~bash
reboot
~~~
