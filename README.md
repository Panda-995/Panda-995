<div align="center">

<img src="https://avatars.githubusercontent.com/u/101494981?v=4" alt="Panda-995" width="96" height="96" style="border-radius:50%;border:3px solid #6366f1;">

# 🐼 熊猫不是猫QAQ

**玩 NAS 十年 · 写教程 1000+ 篇 · 自托管爱好者**

[![Followers](https://img.shields.io/github/followers/Panda-995?style=flat-square&label=Followers&logo=github&color=6366f1)](https://github.com/Panda-995/followers)
[![Stars](https://img.shields.io/github/stars/Panda-995?style=flat-square&label=Total%20Stars&color=0ea5e9)](https://github.com/Panda-995?tab=repositories)
[![Repos](https://img.shields.io/github/repos/Panda-995?tab=repositories&style=flat-square&label=Repos&color=10b981)](https://github.com/Panda-995?tab=repositories)
[![Since](https://img.shields.io/badge/since-2022.03-6366f1?style=flat-square)](https://github.com/Panda-995)
[![Blog](https://img.shields.io/badge/blog-panda995.top-ff6b35?style=flat-square&logo=googleblog)](https://panda995.top)
![值得买百大](https://img.shields.io/badge/%E5%80%BC%E5%BE%97%E4%B9%B0-%E8%BF%9E%E7%BB%AD%E4%B8%A4%E5%B9%B4%E7%99%BE%E5%A4%A7-ff6b35?style=flat-square)

[博客 panda995.top](https://panda995.top) · [知识库 wiki.panda995.fun](https://wiki.panda995.fun) · [镜像仓库 ghcr.io](https://github.com/Panda-995?tab=repositories)

</div>

---

## ⭐ 精选项目

<div align="center">

### 📦 KOLFlow · 达人商单流管理系统

<img src="https://raw.githubusercontent.com/Panda-995/KOLFlow/main/public/github.png" alt="KOLFlow" width="100%">

**给自媒体人自己用的商单管理台** —— 商单从建单、跟进到结算，一处管完。

[![TypeScript](https://img.shields.io/badge/TypeScript-React_19-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://github.com/Panda-995/KOLFlow)
[![Node](https://img.shields.io/badge/Node.js-20+-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)](https://github.com/Panda-995/KOLFlow)
[![License](https://img.shields.io/badge/License-AGPL--3.0-blue?style=flat-square)](https://github.com/Panda-995/KOLFlow/blob/main/LICENSE)
[![Stars](https://img.shields.io/github/stars/Panda-995/KOLFlow?style=flat-square&label=%E2%98%85&color=0ea5e9)](https://github.com/Panda-995/KOLFlow)

商单详情是主数据，往下自动同步待办、账单和资产；但账单资产也能单独存在，删它不会反向动商单 —— 不用怕数据被连坐。

📊 仪表盘 · 📦 商单与模板 · ✅ 待办日历 · 💰 账单 · 🏢 品牌 · 🎁 资产库 · 📈 数据统计 · 📋 操作日志 · 📱 Android 客户端

[🔗 在线体验](https://ficp.fun/s/qSW5Wh/) · [📖 源码](https://github.com/Panda-995/KOLFlow) · [📝 使用教程](https://post.smzdm.com/p/a6zg63m0/)

---

### 🍃 Soundleaf · 声页（小说有声化工作室）

<img src="https://raw.githubusercontent.com/Panda-995/Soundleaf/main/output/ui/01-library.png" alt="Soundleaf" width="100%">

**丢一本 TXT/EPUB 进去，出来一本带章节导航的 M4B 有声书。** 全程自托管，不用 GPU，不用特权容器。

[![Python](https://img.shields.io/badge/Python-FastAPI-3776AB?style=flat-square&logo=python&logoColor=white)](https://github.com/Panda-995/Soundleaf)
[![Docker](https://img.shields.io/badge/Docker-amd64%20%2F%20arm64-2496ED?style=flat-square&logo=docker&logoColor=white)](https://github.com/Panda-995/Soundleaf)
[![TTS](https://img.shields.io/badge/TTS-MiniMax-6366f1?style=flat-square)](https://github.com/Panda-995/Soundleaf)
[![License](https://img.shields.io/badge/License-AGPL--3.0-blue?style=flat-square)](https://github.com/Panda-995/Soundleaf)

- **读音词典**：在正文里划选一个词，直接改多音字、人名、地名的读音，原文一个字都不动
- **片段级重生成**：改完某一句，只重合成那几秒再拼回章节里，其余片段原地不动
- **角色音色与情绪**：引号内对白走角色音色，引号外叙述回旁白；21 种情绪风格，旁白恒为旁白
- **响度归一化**：每段合成后对齐统一响度，换角色换情绪音量听感一致
- **M4B 导出**：AAC + 章节导航 + 书名作者封面元数据，也能逐章 MP3/WAV 打 ZIP

```sh
docker run -d --name soundleaf -p 8780:8780 \
  -v /path/to/data:/data \
  ghcr.io/panda-995/soundleaf:latest
```

[📖 源码](https://github.com/Panda-995/Soundleaf) · [🐳 部署文档](https://github.com/Panda-995/Soundleaf#docker-%E9%83%A8%E7%BD%B2)

</div>

---

## 🧰 其他开源项目

<div align="center">

### 主力自研

| 项目 | 说明 | 语言 | ⭐ |
| :--- | :--- | :--- | ---: |
| [obsidian-dashboard](https://github.com/Panda-995/obsidian-dashboard) | Obsidian 零配置仪表盘，自动扫库统计写作数据并出可视化 | CSS | 59 |
| [ai-writing-assistant](https://github.com/Panda-995/ai-writing-assistant) | 妙笔生花 · AI 写作助手，从纠错到逻辑重构的全方位建议 | TypeScript | 31 |
| [github-search-mirror](https://github.com/Panda-995/github-search-mirror) | GitHub 搜索镜像站，带 AI 摘要、翻译、收藏夹和评论 | TypeScript | 20 |
| [StarKids](https://github.com/Panda-995/StarKids) | 给女儿写的家庭任务积分系统，游戏化养好习惯 | TypeScript | 12 |
| [wechat-editor](https://github.com/Panda-995/wechat-editor) | 公众号像素风 Markdown 编辑器，内置 Gemini 助手 | TypeScript | 9 |

### Docker 化与自托管

| 项目 | 说明 | 语言 | ⭐ |
| :--- | :--- | :--- | ---: |
| [animal-world-cup](https://github.com/Panda-995/animal-world-cup) | 动物世界杯 Docker 化版，GHCR latest 多架构镜像 | HTML | 10 |
| [ZenTools](https://github.com/Panda-995/ZenTools) | 免费、隐私优先的在线工具箱，Docker 双架构 | HTML | 2 |
| [LikeGirlSite](https://github.com/Panda-995/LikeGirlSite) | LikeGirlSite 的 Docker + SQLite 部署版 | JavaScript | 2 |
| [Treasure-Docker](https://github.com/Panda-995/Treasure-Docker) | Treasure 的 Docker 打包版，游戏逻辑原样不动 | JavaScript | 2 |
| [perler-beads](https://github.com/Panda-995/perler-beads) | 拼豆图纸生成器，适配 Docker 与 NAS 部署 | TypeScript | 1 |

### 小实验与硬核玩具

| 项目 | 说明 | 语言 | ⭐ |
| :--- | :--- | :--- | ---: |
| [RoomDeck](https://github.com/Panda-995/RoomDeck) | 聚会共享房间：文件、投票、屏幕共享、游戏和共绘画板 | Go | 3 |
| [NASflow](https://github.com/Panda-995/NASflow) | NAS 监控屏，Docker Agent 采只读信息喂给 ESP32-S3 | C | 1 |
| [Wiki-Flow](https://github.com/Panda-995/Wiki-Flow) | 现代化 Markdown WIKI，支持知识图谱和多级访问控制 | TypeScript | 0 |
| [DP104-Studio](https://github.com/Panda-995/DP104-Studio) | TICKTYPE DP-104 的 Windows 托盘控制台 | Python | 0 |
| [synesthesia-canvas](https://github.com/Panda-995/synesthesia-canvas) | 把图形实时翻译成电子音乐的浏览器乐器 | TypeScript | 0 |
| [tianming](https://github.com/Panda-995/tianming) | 天命 的 Docker 部署版 | JavaScript | 0 |

</div>

---

## 🛠 技术栈

<div align="center">

| | | |
| :--- | :--- | :--- |
| ![TypeScript](https://img.shields.io/badge/TypeScript-8%20repos-3178C6?style=flat-square&logo=typescript&logoColor=white) | ![JavaScript](https://img.shields.io/badge/JavaScript-3%20repos-F7DF1E?style=flat-square&logo=javascript&logoColor=black) | ![Python](https://img.shields.io/badge/Python-2%20repos-3776AB?style=flat-square&logo=python&logoColor=white) |
| ![HTML](https://img.shields.io/badge/HTML-2%20repos-E34F26?style=flat-square&logo=html5&logoColor=white) | ![Go](https://img.shields.io/badge/Go-1%20repo-00ADD8?style=flat-square&logo=go&logoColor=white) | ![CSS](https://img.shields.io/badge/CSS-1%20repo-663399?style=flat-square&logo=css3&logoColor=white) |
| ![C](https://img.shields.io/badge/C-1%20repo-A8B9CC?style=flat-square&logo=c&logoColor=black) | ![Docker](https://img.shields.io/badge/Docker-ghcr.io-2496ED?style=flat-square&logo=docker&logoColor=white) | ![GHCR](https://img.shields.io/badge/Images-ghcr.io%2Fpanda--995-6366f1?style=flat-square&logo=github) |

React 19 · Next.js · FastAPI · PostgreSQL · Redis · Tailwind CSS · ESP32 · 极空间 / 绿联 / 群晖 / 威联通 / 铁威马

</div>

---

## 📝 关于我

主业电商运营，副业写点东西。**什么值得买连续两年百大**，微信粉丝群 3000+ 人，长期混【docker聚集地】。

我这人比较实在：

- 自研项目基本都发 Docker 镜像到 `ghcr.io/panda-995`，也顺手帮一堆不支持 Docker 的项目做打包
- 写教程不为凑数，NAS 折腾了十年，踩过的坑才写
- 接广告，但不收烂钱，「我的生活所迫让我接广告，我的良知让我该骂就骂」
- 观点可能不够客气，但只针对事，不针对人

> 技能不压身，干货不掺水。

---

<div align="center">

**© Panda-995 · 保持好奇，持续折腾**

[GitHub](https://github.com/Panda-995) · [博客](https://panda995.top) · [知识库](https://wiki.panda995.fun)

</div>
