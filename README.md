# traceback

查询回程路由：
```
apt update %% apt install  traceroute
```
安装完毕后使用```traceroute -q 1 ```+IP地址即可查询，但只显示ip不显示服务商

使用ipip官方的BestTrace查询：
```
wget -N --no-check-certificate https://cdn.ipip.net/17mon/besttrace4linux.zip
unzip besttrace4linux.zip && chmod +x *
./besttrace -q 1 + IP地址
```
但由于ipip用的这个地址境外下载太拉跨，我把压缩包解压传到这里，"/main/besttrace"根据自己机器类型来下载：
```
wget https://raw.githubusercontent.com/ChellyL/traceback/main/besttrace
chmod +x besttrace
./besttrace -q 1 + IP地址
```
