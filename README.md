# 一键部署V2Ray（Docker版）
```
mkdir /etc/v2ray && wget https://raw.githubusercontent.com/shiruixuan/config/main/config.json -O /etc/v2ray/config.json && docker run -d -p 29535:29535 -p 29536:29536 --name v2ray --restart=always -v /etc/v2ray/config.json:/etc/v2ray/config.json v2fly/v2fly-core:v4.45.2
```
