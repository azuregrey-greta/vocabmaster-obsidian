# VocabMaster 背单词 (vocabmaster-obsidian)

在任意笔记里点词标记生词（12色渐变记忆），一键导出带艾宾浩斯打卡表的生词本 Markdown。

## 安装

### 电脑端（手动）
把 `main.js`、`manifest.json`、`styles.css` 放进 `<vault>/.obsidian/plugins/vocabmaster-obsidian/`，重启 Obsidian 后在第三方插件里启用。

### 手机端（推荐 BRAT / Pluscan）
1. 社区插件市场安装 **BRAT**
2. `Add Beta plugin` → 输入 `本仓库地址`（如 `yourname/vocabmaster-obsidian`）
3. BRAT 会从最新 Release 拉取三个核心文件
4. **首次查词时插件自动下载词库**（dict.data.b64 约20MB + dict.index.b64 约1.3MB，仅一次，之后离线可用）

## Release 资产说明
- `main.js` / `manifest.json` / `styles.css`：BRAT 自动下载
- `dict.data.b64` / `dict.index.b64`：词库，插件首次运行自动下载到插件目录

## 版本
- v1.0.1（2026-10-27）：词库缺失时自动从 Release 下载（手机端零手动）
- v1.0.0：初始版
