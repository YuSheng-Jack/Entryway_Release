<p align="center">
  <img src="entryway_logo.png" alt="Entryway Logo" width="120">
</p>

<p align="center"><strong>Entryway</strong></p>
<p align="center">一扇门，通往你的全部影音。聚合 Jellyfin、Emby、Plex、fnOS、Navidrome 与本地 / SMB / WebDAV 媒体源的跨平台客户端。</p>
<p align="center">One entryway to all your media — a cross-platform client for Jellyfin, Emby, Plex, fnOS, Navidrome, local folders, SMB and WebDAV.</p>
<p align="center"><a href="https://entryway.top"><strong>官方网站 entryway.top</strong></a> ｜ <a href="https://entryway.top">Official Website</a></p>

<p align="center">
  <img src="https://img.shields.io/badge/Android-0.90.0_Preview-3DDC84?style=flat-square&logo=android&logoColor=white" alt="Android 0.90.0">
  <img src="https://img.shields.io/badge/Android_TV-0.25.0-3DDC84?style=flat-square&logo=android&logoColor=white" alt="Android TV 0.25.0">
  <img src="https://img.shields.io/badge/Windows-独立版待发布-8A8F98?style=flat-square" alt="Windows">
  <img src="https://img.shields.io/badge/Server-Jellyfin%20%7C%20Emby%20%7C%20Plex%20%7C%20fnOS%20%7C%20Navidrome-AA5CC3?style=flat-square" alt="Server">
  <img src="https://img.shields.io/badge/License-MIT-blue?style=flat-square" alt="License">
</p>

---

本仓库是 Entryway 的公开发布仓库：安装包以 Release 附件形式提供，客户端的更新检测也从这里读取版本。手机、TV、Windows 三端**独立发版**，各自使用 `android-phone-v*`、`android-tv-v*`、`windows-v*` 前缀的 Tag。

## 最新版本 | Latest Releases

| 平台 | 版本 | 构建号 | 渠道 | 系统要求 | 下载（Gitea） | 镜像（GitHub） |
| --- | --- | ---: | --- | --- | --- | --- |
| Android 手机 | **0.90.0** | 56 | Preview | Android 8.1+ | [entryway-preview-0.90.0.apk](https://gitea.yamby.cn/yusheng/Entryway_Release/releases/download/android-phone-v0.90.0/entryway-preview-0.90.0.apk) | [下载](https://github.com/YuSheng-Jack/Entryway_Release/releases/download/android-phone-v0.90.0/entryway-preview-0.90.0.apk) |
| Android TV | **0.25.0** | 42 | Release | Android 7.1+ | [Entryway-tv-release-0.25.0.apk](https://gitea.yamby.cn/yusheng/Entryway_Release/releases/download/android-tv-v0.25.0/Entryway-tv-release-0.25.0.apk) | [下载](https://github.com/YuSheng-Jack/Entryway_Release/releases/download/android-tv-v0.25.0/Entryway-tv-release-0.25.0.apk) |
| Windows x64 | 0.18.0+37 | 37 | — | Windows 10/11 | 独立版待发布 | — |

| 安装包 | 大小 | SHA-256 |
| --- | ---: | --- |
| `entryway-preview-0.90.0.apk` | 170,091,554 B | `63dfc5027fd722b9e931b11678b7bb84b72237f64d6f2cad4653a67a6e945b7e` |
| `Entryway-tv-release-0.25.0.apk` | 202,557,288 B | `cabfb74233ec14d82603f97606a32dd07998616c3700d50ab39467d48de19150` |

> [!IMPORTANT]
> **1.0 正式版即将发布**，将正式支持音乐与有声书服务器。1.0 与现有 Preview 版本**不兼容、无法直接覆盖升级**，请提前在「设置 › 备份与恢复」备份到本地文件或 WebDAV，安装 1.0 后即可恢复服务器、设置与书签。

- 手机版 Preview 是非调试的持续发布构建（R8 + Baseline Profile），沿用 1.0 前公开包的调试证书，现有用户可直接覆盖安装。
- 每个版本的更新内容见对应 Release 说明：[Gitea Releases](https://gitea.yamby.cn/yusheng/Entryway_Release/releases) ｜ [GitHub Releases](https://github.com/YuSheng-Jack/Entryway_Release/releases)。`RELEASE_NOTES.md` 仅保留 v0.24.0 及更早的合并发布记录。

## 交流群 | Community

欢迎加入微信用户群 **Entryway Buddys**：反馈问题、交流服务器与播放设置，新版本和 1.0 正式版的消息也会第一时间在群里发布。

Join the **Entryway Buddys** WeChat group for feedback, tips and release news.

<p align="center">
  <img src="community-wechat.png" alt="微信群 Entryway Buddys 入群二维码" width="260">
</p>

> 微信群二维码每 7 天更新一次。如果扫码提示已过期，请到官网 [entryway.top](https://entryway.top/#community) 获取最新的二维码。

## 这一版能做什么 | What's New

### 手机版 0.88 – 0.90：界面与交互全面改版

- **新导航**：底栏「影音 / 接续 / 资源 / 设置」加独立搜索按钮，滚动自动收起；Entryway 自绘线性图标。
- **四种视觉效果**：毛玻璃、液态玻璃、薄雾、春山；跟随系统 / 浅色 / 深色主题与主题强调色。
- **多服务器合一**：同一部影片在所有服务器上的版本合并展示，支持 4K / HDR / 1080p 筛选，播放中可切到另一台服务器的同一版本。
- **推荐 · 接续 · 搜索**：组件化推荐页（TMDB / 豆瓣榜单、流媒体平台）；继续观看、收藏、追更跨服务器汇总；全服务器合并搜索。
- **播放器**：ExoPlayer / mpv 双内核自动选择，跳过片头片尾、章节、画中画、Anime4K、播放器书签、杜比视界与 HDR 徽标。
- **音乐（预览）**：Navidrome 专辑、艺人、歌单，迷你播放器与离线下载。
- **个性化**：APP 图标三色自由组合（8 种背景 × 17 种隧道 × 17 种播放三角）；简体中文、繁體中文、English、日本語、한국어、Español。
- **备份**：本地文件或 WebDAV，服务器、设置与书签一并备份。

### 支持的媒体源

| 类型 | 服务 |
| --- | --- |
| 视频服务器 | Jellyfin（含 Jellyfin 12）、Emby 及兼容服务端、Plex、fnOS |
| 音乐服务器 | Navidrome（Subsonic 协议，预览） |
| 文件源 | 本地文件夹、SMB、WebDAV |
| 弹幕 | 弹弹Play 官方、LogVar 弹幕 API、其他弹弹Play 兼容服务 |

### Android TV 0.25.0

- 首页背景随焦点切换，分区顺序可调并立即生效，返回首页时焦点回到进入前的位置。
- Dolby Vision Profile 5 自绘路径：硬件解码 + GPU 色彩重整形。
- 遥控器全键盘搜索、手机扫码辅助输入、完整弹幕设置。

## 更新检测 | Update Check

客户端请求本仓库的 Release 列表，按本平台 Tag 前缀与安装包文件名筛选，优先使用 Gitea，失败时降级到 GitHub。

## 源码仓库 | Source Code

- **GitHub**：[github.com/YuSheng-Jack/Entryway](https://github.com/YuSheng-Jack/Entryway)
- **Gitea**：[gitea.yamby.cn/yusheng/Entryway](https://gitea.yamby.cn/yusheng/Entryway)

## 许可证 | License

本项目基于 MIT 许可证开源。

手机端弹幕实现参考了 MIT 许可的 [AimesSoft/NipaPlay-Reload](https://github.com/AimesSoft/NipaPlay-Reload)。
Windows 客户端基于 NipaPlay-Reload `v1.10.13` 构建，保留上游 MIT 许可。
