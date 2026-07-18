# Floatline

**把电子书、博客和长文变成可听、可看的桌面字幕。**  
Turn ebooks, articles, and long-form text into synchronized desktop subtitles.

[官方网站 / Website](https://floatline.top/) · [发布状态 / Release status](#release-status) · [许可证 / License](#license)

Floatline 是一款面向 macOS 与 Windows 的桌面听读工具。导入 EPUB、网页文章、Markdown、TXT 或粘贴文本后，它会使用自然语音逐句朗读，并通过置顶浮窗同步显示当前句和中英翻译。

Floatline is a desktop reading and accessibility app for macOS and Windows. It reads EPUBs, web articles, Markdown, TXT, and pasted text aloud while a floating always-on-top subtitle window follows the current sentence and translation.

## Highlights

- 自然神经语音朗读，离线时回退系统语音
- 桌面置顶字幕浮窗与逐句高亮
- 中英双语对照与断点续听
- 本地优先：书库和阅读进度保存在设备上
- 7 天完整功能试用
- 一次买断，永久使用，最多同时激活 2 台设备
- Natural neural voices with offline system-voice fallback
- Always-on-top subtitles, sentence highlighting, translation, and resume
- Local-first library and reading progress

## license

- Floatline 是付费专有软件，不是开源或免费软件。
- 许可证最多同时激活 2 台 macOS 或 Windows 设备。
- Floatline is paid proprietary software, not open-source or freeware.

## Release status

Floatline 正在完成支付平台审核与正式安装包准备。为了避免向用户提供未签名或仍连接测试支付环境的构建，当前暂不公开安装包。审核完成后，正式的 macOS 与 Windows 安装包会发布在本仓库的 **Releases** 页面。

Floatline's live checkout is approved and connected to its production license flow. Official macOS and Windows builds are published through this repository's **Releases**.

## Privacy

Floatline 不要求注册账户。导入内容、书库和阅读进度默认保存在本地。翻译和在线神经语音功能仅在使用时访问相应网络服务。

Floatline does not require an account. Imported content, the library, and reading progress stay on the user's device by default. Translation and online neural voice features contact their respective services only when used.

## Custom domain

官网绑定自定义域名 **[floatline.top](https://floatline.top/)**（GitHub Pages）。

在腾讯云 DNSPod 添加以下 DNS 记录：

| Type | Name | Value |
|------|------|-------|
| A | `@` | `185.199.108.153` |
| A | `@` | `185.199.109.153` |
| A | `@` | `185.199.110.153` |
| A | `@` | `185.199.111.153` |
| CNAME | `www` | `win1011.github.io` |

然后在 GitHub 仓库 **Settings → Pages → Custom domain** 填入 `floatline.top`，勾选 **Enforce HTTPS**。DNS 生效后全球即可通过 `https://floatline.top` 访问。

## Repository scope

这个公开仓库仅用于官网、产品信息与正式安装包发布，不包含 Floatline 应用源码。应用源码与官方构建保留所有权利。

This public repository contains the product website, public information, and future release assets. It does not contain the Floatline application source code. All rights to the application source and official builds are reserved.

© 2026 Floatline
