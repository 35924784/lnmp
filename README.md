# lnmp
docker搭建lnmp(v1.4)环境

使用lnmp1.4 Nginx-1.12.0 Mysql-5.5.56 root:root Php-5.6.31 CLI: lnmp start/stop/restart 使用命令：lnmp start/stop/restart

1、git clone https://github.com/35924784/lnmp到本地目录中。</br>
2、从Docker公共仓库抓取lnmp镜像:docker pull lizhiqiang666/lnmp:v1</br>
3、cd 你的目录/lnmp </br>
4、dockr-compose up </br>
   如出现下面提示信息说明启动成功：</br>
Creating lnmp_lnmp_1 ... done</br>
Attaching to lnmp_lnmp_1</br>
lnmp_1  |  * Restarting OpenBSD Secure Shell server sshd                        start-stop-daemon: warning: failed to kill 24: No such process </br>
lnmp_1  |             [ OK ] </br>
5、在浏览器中输入：http://localhost:32801 可看到lnmp正在运行中。</br>
6、支持使用ssh工具通过32804端口进入，用户名密码：root/root </br>
7、mysql端口：32803 ，用户名密码：root/root</br>

```
项目结构：
.
├── Dockerfile   </br>
├── conf
│   ├── mysql
│   ├── nginx
│   └── php
├── docker-compose.yml
├── mysql
├── php
│   └── log
└── www
    └── default
```
