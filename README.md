# FuckUnicom
借助V2Ray实现联通免流

<p align="center">
  <img src="https://i.ibb.co/fFrbnZ8/IMG-20210512-190537.jpg">
</p>


[电信免流(暂时下线，择日回归)](https://github.com/EraserCN/FuckTelecom)
### 免责声明
```
本项目仅限于学习用途，必然违反联通之用户协议。
请勿用于违法用途，本人概不负责。
您对使用此项目产生的后果负有全部责任。
如您不同意本声明之任一部分，请勿使用。
```

# 使用说明
在服务器上执行以下命令
```
wget https://github.com/cryproNMR/FuckUnicom/blob/main/install.sh
wget https://github.com/cryptoNMR/FuckUnicom/blob/main/config.json
```

> 之后强烈建议修改config.json之UUID

# 再执行以下命令

```
bash install.sh
systemctl enable v2ray
cp config.json /usr/local/etc/v2ray/config.json
systemctl start v2ray
```

# 最后导入V2Ray连接

```
vmess://eyJhZGQiOiLkv67mlLnkuLrkvaDnmoTmnI3liqHlmahpcCIsImFpZCI6IjgiLCJob3N0IjoicHVsbC5mcmVlLnZpZGVvLjEwMDEwLmNvbSIsImlkIjoiM2ZkMzUzODEtZDczNC00NTQyLTk1MzEtZjUxZDk0M2U1Y2MwIiwibmV0Ijoid3MiLCJwYXRoIjoiL2dpdGh1YmVyYXNlcmNuIiwicG9ydCI6IjQ0MyIsInBzIjoiZXhhbXBsZSIsInNuaSI6IiIsInRscyI6IiIsInR5cGUiOiJub25lIiwidiI6IjIifQ==
```

> 也可以手填如下配置
<a href="https://ibb.co/grQz4W7"><img src="https://i.ibb.co/grQz4W7/IMG-20210512-190729.jpg" alt="IMG-20210512-190729" border="0"></a>
然后您的流量就不要钱了

## 进阶开发

```

-Fork本项目
-修改config.json
-替换wget命令后的下载地址中的用户名为您的用户名
-执行修改后的脚本以获得更多功能

```

## 鸣谢
# ![Hunk Zhang](https://t.me/hunkzhang)
