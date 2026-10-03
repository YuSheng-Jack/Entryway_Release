<p align="center">
  <img src="entryway_logo.png" alt="Entryway Logo" width="120">
</p>

<p align="center"><strong>Entryway</strong></p>
<p align="center">一扇门，通往你的全部影音。把 Emby、Jellyfin、Plex、飞牛影视、极影视、音乐服务器、IPTV 与点播站，连同网盘、NAS 和本地文件，收进同一个客户端。</p>
<p align="center">One entryway to all your media — a client for Emby, Jellyfin, Plex, fnOS, ZSpace, music servers, IPTV and VOD sites, cloud drives, NAS shares and local files.</p>
<p align="center"><a href="https://entryway.top"><strong>官方网站 entryway.top</strong></a> ｜ <a href="https://entryway.top">Official Website</a></p>

<p align="center">
  <img src="https://img.shields.io/badge/Android-1.0.5-3DDC84?style=flat-square&logo=android&logoColor=white" alt="Android 1.0.5">
  <img src="https://img.shields.io/badge/Android_TV-1.0.5-3DDC84?style=flat-square&logo=android&logoColor=white" alt="Android TV 1.0.5">
  <img src="https://img.shields.io/badge/Windows-开发中-8A8F98?style=flat-square" alt="Windows">
  <img src="https://img.shields.io/badge/Server-Emby%20%7C%20Jellyfin%20%7C%20Plex%20%7C%20fnOS%20%7C%20ZSpace-AA5CC3?style=flat-square" alt="Server">
</p>

---

本仓库是 Entryway 的发布仓库：安装包以 Release 附件形式提供，客户端的更新检测也从这里读取版本。手机、TV、Windows 三端**独立发版**，各自使用 `android-phone-v*`、`android-tv-v*`、`windows-v*` 前缀的 Tag。

## 最新版本 | Latest Releases

| 平台 | 版本 | 构建号 | 系统要求 | 下载（Gitea） | 镜像（GitHub） |
| --- | --- | ---: | --- | --- | --- |
| Android 手机 | **1.0.5** | 62 | Android 8.1+ · arm64 | [entryway-release-1.0.5-arm64-v8a.apk](https://gitea.yamby.cn/yusheng/Entryway_Release/releases/download/android-phone-v1.0.5/entryway-release-1.0.5-arm64-v8a.apk) | [下载](https://github.com/YuSheng-Jack/Entryway_Release/releases/download/android-phone-v1.0.5/entryway-release-1.0.5-arm64-v8a.apk) |
| Android TV（64 位） | **1.0.5** | 47 | Android 7.1+ · arm64 | [Entryway-tv-release-1.0.5-arm64-v8a.apk](https://gitea.yamby.cn/yusheng/Entryway_Release/releases/download/android-tv-v1.0.5/Entryway-tv-release-1.0.5-arm64-v8a.apk) | [下载](https://github.com/YuSheng-Jack/Entryway_Release/releases/download/android-tv-v1.0.5/Entryway-tv-release-1.0.5-arm64-v8a.apk) |
| Android TV（32 位） | **1.0.5** | 47 | Android 7.1+ · armeabi-v7a | [Entryway-tv-release-1.0.5-armeabi-v7a.apk](https://gitea.yamby.cn/yusheng/Entryway_Release/releases/download/android-tv-v1.0.5/Entryway-tv-release-1.0.5-armeabi-v7a.apk) | [下载](https://github.com/YuSheng-Jack/Entryway_Release/releases/download/android-tv-v1.0.5/Entryway-tv-release-1.0.5-armeabi-v7a.apk) |
| Windows x64 | 开发中 | — | Windows 10/11 | 独立版待发布 | — |

| 安装包 | 大小 | SHA-256 |
| --- | ---: | --- |
| `entryway-release-1.0.5-arm64-v8a.apk` | 56,299,484 B | `ea3509c1deb5ced16ffb6c2af7f9bf72a627216e1a455702d6b58f17c069be4f` |
| `Entryway-tv-release-1.0.5-arm64-v8a.apk` | 53,908,927 B | `6d3d2c85278ecba2bf66ae431e5d009cfbe3611d8e09f1a8895fb51daee66f21` |
| `Entryway-tv-release-1.0.5-armeabi-v7a.apk` | 47,459,031 B | `e757e4c398b88955876c3fe4b55714d29ecabd8c3325d576a56797226b3a9a27` |

- 安装包均为 Release 构建，使用正式密钥签名（证书 SHA-256 `a027e7a59bb3931250385e1ba44bd049a9dca9a855101e3263d617b3919b7bcc`）。
- **TV 该下哪个包**：大多数电视、投影仪、盒子用 64 位包；安装时提示「解析错误」「与设备不兼容」的老设备，改用 32 位包。应用内更新会按已装的包自动选择。
- **从 1.0 之前的 Preview 版升级**：签名不同，不能直接覆盖。请先在「设置 › 备份与恢复」备份到本地文件或 WebDAV，卸载旧版、安装新版后再恢复。已装 1.0.1 及以后版本的，在应用内检查更新即可。
- 每个版本的更新内容见对应 Release 说明：[Gitea Releases](https://gitea.yamby.cn/yusheng/Entryway_Release/releases) ｜ [GitHub Releases](https://github.com/YuSheng-Jack/Entryway_Release/releases)。`RELEASE_NOTES.md` 仅保留 v0.24.0 及更早的合并发布记录。

## 交流群 | Community

欢迎加入 QQ 用户群 **Entryway Buddys**（群号 **1107768156**）：反馈问题、交流服务器与播放设置，新版本的消息也会第一时间在群里发布。

Join the **Entryway Buddys** QQ group (number **1107768156**) for feedback, tips and release news.

<p align="center">
  <img src="community-qq.png" alt="QQ 群 Entryway Buddys 入群二维码" width="260">
</p>

> 用 QQ「扫一扫」扫码，或在 QQ 里搜索群号加入。官网 [entryway.top](https://entryway.top/#community) 上也有同一张二维码。

## 支持的媒体源 | Sources

| 类型 | 支持 |
| --- | --- |
| 视频服务器 | Emby 及兼容服务端、Jellyfin、Plex、飞牛影视（fnOS）、极影视 |
| 音乐服务器 | Navidrome、Subsonic 兼容服务、极音乐、飞牛音乐 |
| 直播与点播 | IPTV（M3U / TXT 频道表，XMLTV 节目单）、点播 CMS（苹果 CMS v10 接口、TVBox 配置） |
| 文件源 | 本地文件夹、SMB、WebDAV / Alist、U 盘（TV） |
| 网盘 | 夸克、115、天翼云盘、中国移动云盘、光鸭云盘、CloudDrive2 |
| 弹幕 | 弹弹Play 官方、LogVar 弹幕 API 及其他弹弹Play 兼容服务 |

## 能做什么 | Highlights

### 手机版 1.0.5

- **跨服务器聚合**：同一部影片在所有服务器上的版本合并展示，按 4K / Dolby Vision / HDR / 1080p 筛选，播放中可切到另一台服务器的同一部片；全服务器合并搜索。
- **推荐 · 接续 · 追剧日历**：组件化推荐页与精选合集（TMDB / 豆瓣榜单），编辑页面时拖动卡片排序（1.0.5 新增）；继续观看、播放书签、收藏汇总所有服务器；追剧日历可选 Bangumi、TMDB、Trakt、TVmaze 作数据来源，观看记录可同步到 Trakt。
- **网盘与本地影视库**：六种网盘扫码或手填登录，可浏览、播放、上传；把网盘或 NAS 文件夹加入影视库，读取 NFO 与海报生成海报墙；网盘与 NAS 上的 DVD / 蓝光 ISO 直接播放。
- **播放器**：ExoPlayer / mpv 双内核，杜比视界与 HDR，跳过片头片尾、章节、画中画、Anime4K、播放书签；IPTV 直播即点即播；竖屏短剧自动竖着全屏播放；音画同步与字幕延迟、链接失效自动续上、音轨字幕和弹幕按季记住（1.0.5 新增）。
- **AI 字幕**：用你自己的大模型服务翻译字幕，没有字幕时语音识别生成字幕。
- **网络代理**：HTTP / HTTPS 或 SOCKS5，可只代理外网服务和勾选的服务器（1.0.5 新增），局域网始终直连。
- **STRM 直链播放**（1.0.5 新增）：开着时网盘 .strm 片源直接播放链接本身，由网盘 302 到直链，不经服务器转码。
- **点播（CMS）全部添加**：TVBox 配置里的站点一次全部加上，已有的和连不上的自动跳过。
- **音乐**：专辑、艺人、歌单，迷你播放器与离线下载。
- **更多**：弹幕、下载、Google Cast 与 DLNA 投屏、本地 / WebDAV 备份恢复（可勾选内容，1.0.5 新增）、四种视觉效果、16 款 APP 图标、六种界面语言。

### Android TV 1.0.5

- 极影视风格的首页与详情页，毛玻璃设置抽屉；音乐服务器有单独的浏览与播放页面。
- 网盘、CloudDrive2、本地影视库、IPTV 直播与点播与手机版一致；U 盘、SMB、WebDAV 文件直接播放。
- 搜索支持首字母、全拼和英文，可用电视自带输入法与语音输入，也可以手机扫码输入片名。
- 服务器按影视、音乐、文件源分组并可调整顺序；首次打开即可扫码从手机恢复备份。
- **儿童时长控制**：密码保护，每次打开先答题，答错只能看设定的时长，时间到暂停，仍答错就关闭应用。
- **播放**（1.0.5 新增）：音画同步与字幕延迟、帧率匹配、确认键长按 3 倍速、链接失效自动续上、放不出来时的诊断面板；音轨字幕和弹幕按季记住，多版本按偏好选择，认片头片尾章节。
- **服务器多线路与测速、Trakt、DLNA 投屏接收、网络代理、STRM 直链播放**（1.0.5 新增）；桌面图标改为 16:9 横幅。
- Dolby Vision Profile 5 自绘路径（硬件解码 + GPU 色彩重整形）；提供 64 位与 32 位安装包。

### Windows

- 独立的 Windows 客户端正在开发中，发布后会出现在本仓库的 `windows-v*` Release 里。

## 更新检测 | Update Check

客户端请求本仓库的 Release 列表，按本平台 Tag 前缀与安装包文件名筛选（TV 再按已装的 64 位 / 32 位包选择），优先使用 Gitea，失败时降级到 GitHub。

## 使用说明 | Terms

Entryway 免费下载使用，版权归 Entryway 所有。

Entryway is free to download and use. All rights reserved.
