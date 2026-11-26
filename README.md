# IPTV 中文播放列表

iptv-org 公开免费频道的中文翻译版。

- `iptv-news-zh.m3u`：新闻分类，约 1068 个台
- `iptv-quanqiu-zh.m3u`：全球总表，按国家分组，约 13126 个台

用法：把下面的链接粘贴到 IPTV 播放器的添加订阅里。

新闻：

```
https://raw.githubusercontent.com/ljt033/iptv-zh/main/iptv-news-zh.m3u
```

全球：

```
https://raw.githubusercontent.com/ljt033/iptv-zh/main/iptv-quanqiu-zh.m3u
```

国内访问慢的话，用 jsDelivr 镜像（同一个文件，国内 CDN 快）：

```
https://cdn.jsdelivr.net/gh/ljt033/iptv-zh@main/iptv-news-zh.m3u
https://cdn.jsdelivr.net/gh/ljt033/iptv-zh@main/iptv-quanqiu-zh.m3u
```

翻译说明：国家名、分类名、知名频道翻成中文，新闻表每个台后加了国家；小地方台没有通用中文名的保留原名；流地址未改动。

来源：https://github.com/iptv-org/iptv（公开免费频道，不含付费台）
翻译快照：2026-11-27

标清流畅版：iptv-quanqiu-sd-zh.m3u（只保留 360p/480p 等低码率的台，共 1,663 个，文件 350K，网慢时看这个更流畅；今日美国、24小时、法国24 等新闻大台只有高清版，不在这个文件里）
