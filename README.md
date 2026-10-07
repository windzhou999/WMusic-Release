<div align="center">

<img src="assets/icon.png" width="120" alt="NetMusicLite">

# NetMusicLite

**一个为 Wear OS 手表打造的网易云音乐客户端 — 把歌单戴在手腕上**

[![Latest Release](https://img.shields.io/github/v/release/windzhou999/WMusic-Release?display_name=tag)](https://github.com/windzhou999/WMusic-Release/releases/latest)
[![Platform](https://img.shields.io/badge/platform-Wear%20OS-3ddc84)](https://www.android.com/wear/)
[![Download](https://img.shields.io/badge/download-APK-blue)](https://github.com/windzhou999/WMusic-Release/releases/latest)

</div>

---

## 特性

- **手表端网易云播放** — 抬腕即听，无需掏出手机
- **封面取色 + 轻玻璃质感 UI** — 跟随专辑封面动态取色的表盘级界面
- **手势操作** — 触点缩放、主页右滑退出、原路返回
- **听歌识曲** — 集成网易 AFP 音频指纹引擎
- **发音按钮适配** — 歌词注音更友好
- **流畅度优化** — AOT 编译 + Baseline Profile，手表上也能丝滑

## 下载安装

> 最新版本请前往 [**Releases**](https://github.com/windzhou999/WMusic-Release/releases/latest) 页面下载 APK。

**方式一：adb 安装（推荐）**

```bash
adb install -r netmusiclite-1.15.apk
```

**方式二：手表本地安装**

将 APK 传入手表存储，用文件管理器打开安装（需允许"安装未知应用"）。

## 应用内更新通道

本仓库根目录的 `update.json` 是 NetMusicLite 的版本清单（事实来源）。自 v1.0.5 起，应用内入口 **设置 → 关于应用 → 检查更新** 会拉取该清单，对比 `versionCode` 后弹窗提示，下载完成并校验 SHA-256 后自动拉起系统安装器。

清单地址：

- **主源**：`https://raw.githubusercontent.com/windzhou999/WMusic-Release/main/update.json`
- **CDN 镜像**：`https://cdn.jsdelivr.net/gh/windzhou999/WMusic-Release@main/update.json`

## 更新日志

| 版本 | 更新内容 |
|------|----------|
| **v1.15** | 新增「封面模糊」外观模式（全站明暗随封面自动切换）；播放页面风格三选一（取色 / 封面模糊 / 自定义壁纸）与「保留取色」开关；播放页与歌词页共用同一张模糊封面底，歌词支持逐字动画；新增长按进度条、访客模式、本地音乐歌词；更新包改存系统「下载」文件夹；修复封面模糊主题进入应用时底图突然闪出、选择自定义图片后玻璃卡片失效与卡片/取色错跟壁纸，以及头图黑边、专辑 Tab 记忆、歌曲数、切评论转场黑屏、切歌残留等问题 |
| **v1.13** | 新增表冠适配开关（列表页/音量页可分别正反调节表冠方向）；修复带翻译歌词「重影」；修复更新后本地音乐失效、导入更稳；修复应用内音量界面计时问题；修复本地歌曲歌词页两层错位 |
| **v1.12** | 修复搜索框 bug（输入首字符不再跳出输入、键盘与焦点保持）；本地音乐新增歌词支持（同名 .lrc / 音频内嵌歌词 / 在线匹配兜底，歌词页标注来源） |
| **v1.1** | 华为表冠适配修正（转表冠无响应、步进与方向校准）；扩展适配非 ColorOS 手表（应用内音量面板、系统返回接管、表冠触感）；向导第一页新增方表/圆表选择；新增「关于高级版」公告页 |
| **v1.0.9** | 新版使用向导（手势图册 + 点歌名进百科/点艺人进主页演示 + 捐赠页）；设置新增字体大小/粗细调节；修复私人电台偶发重复播放、专辑与「我喜欢」页封面背景渐变断裂；默认浅色主题、种子色降饱和 |
| **v1.0.8** | 下载完成自动拉起安装器；启动静默检测新版本（播放页顶部提示胶囊）；未授权时自动引导开启安装权限 |
| **v1.0.6** | 首次登录使用向导；登录二维码加大 20%；修复向导页按钮裁切；应用改名 netmusiclite |
| **v1.0.5** | 关于应用页新增「检查更新」；接入 GitHub 远程更新通道 |
| **v1.0.4** | 更多残留修复；发音按钮适配 |
| **v1.0.3** | 触点缩放；主页右滑退出；原路返回 |
| **v1.0.2** | 关于应用页 + 封面取色；去系统壁纸取色；轻玻璃风格 + 启动图标 + 改名 |

## 反馈

使用中遇到问题或想要新功能，欢迎到 [Issues](https://github.com/windzhou999/WMusic-Release/issues) 提交。

## 免责声明

- 本项目为**非官方**第三方客户端，仅供个人学习与交流使用，请于下载后 24 小时内自行斟酌保留
- 应用内音乐内容及相关版权归网易云音乐及内容权利方所有
- 本仓库仅发布构建产物（APK）与版本清单，**不含源码**
- 如有侵权，请联系删除

---

<div align="center">

**NetMusicLite** · Made with ❤️ for your wrist

</div>
