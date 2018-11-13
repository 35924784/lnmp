# lnmp
docker搭建lnmp(v1.4)环境

1、git clone https://github.com/35924784/lnmp到本地目录中。</br>
2、从Docker公共仓库抓取lnmp镜像:docker pull lizhiqiang666/lnmp:v1</br>
3、cd 你的目录/lnmp </br>
4、dockr-compose up </br>
   如出现下面提示信息说明启动成功：</br>
Creating lnmp_lnmp_1 ... done</br>
Attaching to lnmp_lnmp_1</br>
lnmp_1  |  * Restarting OpenBSD Secure Shell server sshd                        start-stop-daemon: warning: failed to kill 24: No such process </br>
lnmp_1  |             [ OK ] </br>
5、在浏览器中输入：http://localhost:32801 可看到lnmp正在运行中。


