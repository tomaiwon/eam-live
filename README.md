# eam-live · 监测台离线快照

[东亚制造实时监测台](https://yihuang.art/projects/semiconductor-daily/live/)连不上工作台（那台 Mac 睡着或断网）时，读这里的数据，页面顶上写明是几点的快照。

- `snapshot.json`：监测台数据和近来的日志
- `covers/`：最近几期的封面（720 宽 WebP）

工作台的 `live_snapshot.py` 每 30 分钟看一次，数据变了就推上来。这个仓库只保留一个提交，每次覆盖（强推），不要手动改。
快照原来放在个人网站仓库 art-site 里，每推一次 GitHub 就要把整个网站重新发布一遍，2026-11-09 挪到这里。
