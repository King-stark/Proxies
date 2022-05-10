# SSH端口  ROOT 用户密码登录设置脚本
> ***--搬自[小御坂的破站](https://github.com/Misaka-blog/rootLogin)***

支持CentOS、Debian、Ubuntu的各大厂商的VPS，一个命令，把厂商的密钥登录或root限制给扬了！

如对脚本不放心，可使用此沙箱先测一遍再使用：</br>
https://killercoda.com/playgrounds/scenario/ubuntu

## 使用方法

首先使用`sudo -i`登录root用户（如果登录用户为非root时），然后执行以下命令

国外
```shell
wget -N --no-check-certificate https://raw.githubusercontents.com/Misaka-blog/rootLogin/master/root.sh && bash root.sh
```
国内
```shell
bash <(curl -L -s https://cdn.jsdelivr.net/gh//King-stark/Proxies/main/rootLogin/root.sh)
```

接着根据脚本指令设置SSH端口和密码即可

## 提醒事项
IBM Linuxone请谨慎使用本脚本，否则有可能会封号

## 交流群 
[Telegram](https://t.me/misakanetcn)
