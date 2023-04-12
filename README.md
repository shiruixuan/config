# 一键部署V2Ray（Docker版）
```
mkdir ~/v2ray && wget https://raw.githubusercontent.com/shiruixuan/config/main/config.json -O ~/v2ray/config.json && docker run -d -p 29535:29535 --name v2ray --restart=always -v ~/v2ray/config.json:/etc/v2ray/config.json v2fly/v2fly-core:v4.45.2
```
