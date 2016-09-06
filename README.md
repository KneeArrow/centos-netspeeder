# netspeeder
for centos7 x64 

安装 
sh netspeeder.sh
安装完毕之后我们可以看到最后一行，执行启动：

nohup /usr/local/net_speeder/net_speeder venet0 "ip" >/dev/null 2>&1 &
我们也可以将脚本加入到开机启动项中，这样可以确保一直在使用：

echo 'nohup /usr/local/net_speeder/net_speeder venet0 "ip" >/dev/null 2>&1 & ' >> /etc/rc.local
