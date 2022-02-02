# SSH ROOT 用户密码登录设置脚本

支持CentOS、Debian、Ubuntu的各大厂商的VPS，一个命令，把厂商的密钥登录或root限制给扬了！

## 运行并设置root密码

首先使用`sudo -i`登录root用户（如果登录用户为非root时），然后执行以下命令

国内
```shell
wget -N https://cdn.jsdelivr.net/gh/Misaka-blog/rootLogin@master/root.sh && chmod -R 777 root.sh && bash root.sh
```
国外
```shell
bash <(curl -L -s https://raw.githubusercontent.com/King-stark/rootLogin/master/root.sh)
```

## 相关教程

待更新

## 提醒事项
IBM Linuxone请谨慎使用本脚本，否则有可能会封号

## 赞助我们

![afdian-MisakaNo.jpg](https://s2.loli.net/2021/12/25/SimocqwhVg89NQJ.jpg)

## 交流群
[Telegram](https://t.me/misakanetcn)