
安装
----------------------------------------------------------------------
``
wget -N --no-check-certificate https://raw.githubusercontent.com/futsu/ssr/master/ssr.sh && chmod +x ssr.sh && bash ssr.sh
``

**备用<br>**
``
wget -N --no-check-certificate https://raw.githubusercontent.com/ToyoDAdoubi/doubi/master/ssr.sh && chmod +x ssr.sh && bash ssr.sh
``

**centos不能联网关闭防火墙<br>**
查看防火墙状态<br>
firewall-cmd --state<br>

停止防火墙<br>
systemctl stop firewalld.service<br>

禁止防火墙开机启动<br>
systemctl disable firewalld.service<br>


**网络加速**
----------------------------------------------------------------------
wget -N --no-check-certificate https://raw.githubusercontent.com/futsu/Linux-NetSpeed/master/tcp.sh && chmod +x tcp.sh && bash tcp.sh<br>
