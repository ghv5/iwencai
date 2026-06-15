# iwencai

这是一个面向 A 股多头波段交易的轻量资料库，包含交易纪律文档、同花顺/通达信执行手册，以及一个本地可打开的仓位风险计算器。

## 目录结构

- `docs/`：规则文档与执行手册
- `references/books/`：本地保留的原始参考书 PDF（默认不上传）
- `references/extracts/`：本地保留的提取文本（默认不上传）
- `references/previews/`：本地保留的排版预览（默认不上传）
- `tools/`：可直接在浏览器打开的本地工具

## 建议提交内容

建议提交 `docs/`、`tools/`、`README.md` 和 `.gitignore`。  
参考书 PDF、提取文本和预览文件默认仅本地保留，不会进入公开仓库。

## 提交到 GitHub 前

当前目录原先位于 `/Users/mac` 这个更大的 Git 工作区下面。  
如需独立提交到 GitHub，建议在本目录初始化独立仓库后再推送：

```bash
cd /Users/mac/pspace/github/iwencai
git init
git add .
git commit -m "init: organize trading docs project"
```
