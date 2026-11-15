# 墨弓对决 · 水墨火柴人射箭

本仓库是公开小游戏的**静态离线镜像**，用于 GitHub Pages 托管。

- 原始地址：`https://y1tku8rpcaw1-d.space-z.ai/`
- Pages 地址：https://ariefenv-hash.github.io/ink-bow-duel/
- 抓取方式：`.github/workflows/mirror.yml` 内用 `.github/scripts/mirror_site.py`
  递归下载入口页与同源资源，改写相对引用后推送到 `gh-pages` 分支根目录。
- 清单：`_mirror.json`（记录每个文件的来源、字节数、sha256，以及未能本地化的外链）。

> 游戏本身完全离线运行、不依赖本仓库以外的服务。若原链接带有 `sharecode`
> 且游戏会读取该参数，可在 Pages 地址后自行附加 `?sharecode=...`。
> 仓库内不含任何第三方凭据。

重新抓取：在 Actions 里手动运行 **Mirror public game site** 即可。
