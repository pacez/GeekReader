# GeekReader

> 专为 macOS 打造的电子书阅读器

[下载 App Store 版本](https://apps.apple.com/app/geekreader) · [问题反馈](https://github.com/pacez/GeekReader/issues)
---

## 简介

**GeekReader** 是一款专为 macOS 设计的电子书阅读与管理工具，致力于为你提供简洁、沉浸、高效的阅读体验。支持 EPUB、PDF、TXT 等多种格式，同时具备连接 GitHub 远程书源的能力，让你轻松打造个人专属书库。

---

## 核心功能

### 📚 多格式本地阅读
支持 EPUB、PDF、TXT 等主流电子书格式，无论是小说、技术文档还是学术论文，都能轻松打开阅读。

### 📥 便捷导入
- 拖拽导入：直接将书籍文件拖入应用窗口即可
- 文件选择器：批量选择本地书籍一键导入

### 🌐 在线书源
支持添加 GitHub 公开仓库作为远程书源，自动解析目录结构，在线浏览和下载书籍。

### 🔍 智能书库管理
- 网格 / 列表双视图自由切换
- 按全部、最近阅读、收藏、在读、已读、未读快速筛选
- 实时搜索书名与作者
- 批量管理书籍

### ✍️ 沉浸式阅读体验
- 目录快速导航（⌘L）
- 批注与笔记功能
- 专注模式，隐藏所有干扰（⌘⌃F）
- 自动保存阅读进度

### 🎨 个性化排版
- **字体**：New York、SF Pro、Source Han Serif
- **字号**：12pt ~ 32pt 无级调节
- **行高**：1.0 ~ 3.0 自由调整
- **主题**：日间、夜间、羊皮纸、跟随系统

### 🌍 多语言支持
简体中文、繁体中文、English，一键切换。

### ⌨️ 快捷键
全面支持键盘操作，从导入到阅读，无需离开键盘即可高效完成所有操作。

| 快捷键 | 功能 |
|--------|------|
| ⌘N | 导入书籍 |
| ⌘O | 打开书籍 |
| ⌘F | 搜索 |
| ⌘D | 添加书签 |
| ⌘L | 目录 |
| ⌘⌃F | 沉浸模式 |
| ⌘⇧O | 添加书源 |
| ⌘, | 偏好设置 |

---

## 系统要求

- **操作系统**：macOS 13.0 或更高版本
- **芯片**：Apple Silicon / Intel
- **语言**：简体中文、繁体中文、English

---

## 常见问题

### 如何导入书籍？
点击工具栏的导入按钮（或按 ⌘N），选择本地 EPUB / PDF / TXT 文件即可。也支持直接从 Finder 拖拽文件到应用窗口。

### 如何添加远程书源？
在设置中选择"在线书源"标签页，输入 GitHub 公开仓库地址和书源名称即可。应用会自动解析仓库中的书籍文件。

### 阅读进度会同步吗？
阅读进度自动保存在本地，目前不支持跨设备同步。你可以通过导出/导入配置文件手动迁移数据。

### 支持哪些电子书格式？
当前支持 EPUB、PDF、TXT。后续版本计划支持更多格式。

### 如何切换语言？
在偏好设置 → 通用中，可选择跟随系统、简体中文、繁体中文或 English。

---

## 隐私政策

GeekReader 尊重并保护所有用户的个人隐私。

- **不收集个人数据**：我们不会收集、存储或分享任何可识别个人身份的信息。
- **本地存储**：所有书籍文件、阅读进度、批注笔记均存储在您的设备本地。
- **无追踪**：应用中不包含任何第三方追踪或分析工具。
- **远程书源**：远程书源内容由用户自行配置的第三方 GitHub 仓库提供，开发者无法访问、控制或审查这些内容。

---

## 用户协议与免责声明

### 简体中文

**【用户协议与免责声明】**

**1. 服务性质与收费说明**
本软件（以下简称"本应用"）是一款 **专业的文档解析与阅读辅助工具**。用户在 App Store 支付的费用，仅为 **本软件程序的使用授权费（技术服务费）**，旨在购买本应用提供的排版引擎、格式转换及本地管理功能。**该费用绝不包含任何电子书内容版权，也不代表本应用向您出售了任何书籍的阅读权。**

**2. 书源与内容的法律责任**
本应用支持用户通过"Git 仓库"或"本地导入"方式获取书源。

* **技术中立：** 本应用仅提供数据抓取与解析的技术框架。Git 仓库中的书源规则由用户自行添加，内容完全来源于第三方互联网。
* **用户承诺：** 用户在使用本应用导入书源或下载电子书时，必须遵守《中华人民共和国著作权法》。用户须确保其导入的书源及下载的电子书仅用于 **个人学习、研究或欣赏**，不得用于商业传播。因用户自行导入书源导致的任何版权纠纷，由用户自行承担全部法律责任。

**3. 深度链接与转码声明**
本应用可能通过"深度链接"技术将第三方网页内容适配为阅读界面。本应用不对第三方网站的内容合法性负责，也不存储任何书籍文件。若书源指向的内容侵犯了您的权益，请权利人直接联系书源提供方，或通知本应用开发者，我们将配合在技术层面屏蔽违规书源规则。

**4. 禁止滥用**
严禁利用本软件进行大规模的数据爬取、商业性盗版分发或破坏第三方网站的技术防护措施。一经发现，本应用有权终止服务并保留追究法律责任的权利。

---

### English

**【Terms of Service and Disclaimer】**

**1. Nature of Service and Fees**
This software (hereinafter referred to as the "App") is a **professional document parsing and reading utility**. The one-time fee paid via the App Store constitutes a **license fee for the software utility (Technical Service Fee)** only. This payment grants the user access to the App's layout engine, format conversion, and local management features. **It strictly excludes any copyright to digital book content and does not grant the right to read any specific copyrighted works.**

**2. Liability for Sources and Content**
The App allows users to import "Book Sources" via Git repositories or local files.

* **Technical Neutrality:** The App provides only the technical framework for data parsing. Book source rules in Git repositories are added solely by the user, and the content is derived entirely from third-party internet sources.
* **User Warranty:** Users must comply with applicable Copyright Laws when importing sources or downloading e-books. Users warrant that any content accessed via the App is for **personal study, research, or private viewing only** and shall not be used for commercial distribution. The user assumes full legal responsibility for any copyright disputes arising from self-imported sources.

**3. Deep Linking and Transcoding**
The App may utilize "deep linking" technology to adapt third-party web content for reading. The App does not host any book files and is not responsible for the legality of content on third-party websites. If content linked via a source infringes your rights, please contact the source provider or notify the developer, and we will cooperate to block the infringing source rules technically.

**4. Prohibition of Misuse**
It is strictly prohibited to use this software for large-scale data scraping, commercial piracy distribution, or bypassing technical protection measures of third-party websites.

---

### 繁體中文

**【用戶協議與免責聲明】**

**1. 服務性質與收費說明**
本軟體（以下簡稱「本應用」）是一款 **專業的文檔解析與閱讀輔助工具**。用戶在 App Store 支付的費用，僅為 **本軟體程式的使用授權費（技術服務費）**，旨在購買本應用提供的排版引擎、格式轉換及本地管理功能。**該費用絕不包含任何電子書內容版權，亦不代表本應用向您出售了任何書籍的閱讀權。**

**2. 書源與內容的法律責任**
本應用支援用戶透過「Git 倉庫」或「本地匯入」方式獲取書源。

* **技術中立：** 本應用僅提供數據抓取與解析的技術框架。Git 倉庫中的書源規則由用戶自行添加，內容完全來源於第三方互聯網。
* **用戶承諾：** 用戶在使用本應用匯入書源或下載電子書時，必須遵守著作權相關法律。用戶須確保其匯入的書源及下載的電子書僅用於 **個人學習、研究或欣賞**，不得用於商業傳播。因用戶自行匯入書源導致的任何版權糾紛，由用戶自行承擔全部法律責任。

**3. 深度連結與轉碼聲明**
本應用可能透過「深度連結」技術將第三方網頁內容適配為閱讀介面。本應用不對第三方網站的內容合法性負責，也不儲存任何書籍檔案。若書源指向的內容侵犯了您的權益，請權利人直接聯繫書源提供方，或通知本應用開發者，我們將配合在技術層面屏蔽違規書源規則。

**4. 禁止濫用**
嚴禁利用本軟體進行大規模的數據爬取、商業性盜版分發或破壞第三方網站的技術防護措施。一經發現，本應用有權終止服務並保留追究法律責任的權利。

---

## 联系我们

如有问题、建议或合作意向，欢迎通过以下方式联系：

- **问题反馈**：[GitHub Issues](https://github.com/pacez/GeekReader/issues)
- **电子邮件**：请通过 GitHub Issues 留言

---

*© 2026 Pace Zhong. All rights reserved.*
