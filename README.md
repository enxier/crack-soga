# crack-soga-v2ray
 A cracked version of soga v2ray backend

> 破解版可能存在各种未知的风险，请自行判断后使用，本人不对使用本软件产生的各种后果负责。

# 本版本是肮脏的破解版本，只是自己学习使用，请支持原版

[soga 后端是一个同时支持 v2ray、Trojan、Shadowsocks 的后端，社区版最高支持88用户，优化了长时间运行的内存占用。](https://github.com/sprov065/soga)

# 破解二进制文件下载地址：[release](https://github.com/RManLuo/crack-soga-v2ray/releases)

# 使用教程

## 启用破解

启用破解版只需在soga_key处输入任意字符即可，如留空则为原版社区版本。

## 完整教程

[doc.sprov.xyz](https://doc.sprov.xyz/)

## 简单安装

``` bash
sudo bash < <(curl -Ls https://raw.githubusercontent.com/RManLuo/crack-soga-v2ray/master/install.sh)
```

## Docker安装

```
# 拉取镜像
docker pull rmanluo/crack-soga
# 运行镜像，参数请参考soga自带教程。
docker run --restart=always --name crack-soga -d -v /etc/soga/:/etc/soga/ --network host rmanluo/crack-soga \
--type=sspanel-uim \
--server_type=v2ray \
--api=webapi \
--webapi_url=https://xxx.com/ \
--webapi_mukey=xxx \
--soga_key=cracked_by_RMan \
--node_id=1
```

