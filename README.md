# traceback

查询回程路由：
```
apt update %% apt install  traceroute
```
安装完毕后使用```traceroute -q 1 ```+IP地址即可插叙

使用ipip官方的BestTrace查询：
```
wget -N --no-check-certificate https://cdn.ipip.net/17mon/besttrace4linux.zip
unzip besttrace4linux.zip && chmod +x *
./besttrace -q 1 + IP地址
```
