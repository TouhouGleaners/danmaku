# Teahouse of Recollected Dreams — Bilibili Danmaku Backup

**拾遗梦茶馆**（Teahouse of Recollected Dreams）致力于补档 Bilibili 上与 **东方Project** 有关的视频与弹幕，防止珍贵资料因下架等原因而丢失。

本仓库用于备份部分东方视频的弹幕数据，包括：

* **弹幕文件**：
  存放于 `danmaku/{cid}.xml`，每个文件对应一个视频 `cid` 弹幕记录。
* **视频元数据与历史追踪日志**：
  保存于 `danmaku.sql`（SQLite 数据库），包含：

  * 需要追踪的视频信息
  * 弹幕获取的日志记录

## 数据结构

```
danmaku/          # 弹幕文件目录
  ├── 123456.xml
  ├── 234567.xml
  └── ...
danmaku.sql       # SQLite 数据库
```

## 免责声明

本项目为非营利性质，仅用于保存和研究 **东方Project** 相关的历史弹幕数据。
如有侵权或其他问题，请联系仓库维护者进行处理。

