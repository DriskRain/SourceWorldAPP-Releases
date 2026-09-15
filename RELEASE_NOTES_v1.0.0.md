# 源世界 v1.0.0 发布说明

`v1.0.0` 是源世界首个正式版本。

## 发布校验

- 安装包：`SourceWorldAPP-v1.0.0.apk`
- SHA-256：`2bdd97547a039c2a27cfdf56e099c571a1747fa43cc7d497d06aa6cff26f0a2c`
- 包名：`com.driskrain.sourceworldapp`
- 版本：`versionName=1.0.0`，`versionCode=1`
- 源码提交：[`ef7dfb27bc2515c56042de8aefb380158cd6a886`](https://github.com/DriskRain/NewReadingAPP/commit/ef7dfb27bc2515c56042de8aefb380158cd6a886)
- 签名：APK Signature Scheme v2 校验通过

## 主要功能

### 小说阅读

- 提供独立小说书架、列表与多列网格布局、搜索、详情、目录、收藏、换源和继续阅读。
- 支持覆盖、仿真、滑动和纵向滚动四种阅读模式，以及章节缓存和阅读进度恢复。
- 可调整字号、行距、段距、阅读背景、音量键翻页等阅读设置。

### 漫画阅读

- 提供独立漫画书架、搜索、详情、目录、收藏和换源。
- 支持翻页与纵向滚动阅读、相邻页面预取和阅读进度恢复。

### 视频播放

- 提供独立视频书架、搜索、详情、选集、收藏和换源。
- 支持页面内与全屏播放、横竖屏切换、倍速、手动下一集、自动连播和播放进度记忆。

### 订阅源与发现

- 支持导入和管理用户自定义的小说、漫画与视频订阅源。
- 支持从剪贴板、网址和本地文件导入，也可通过 ZIP 规则包或 TXT 网址清单批量导入。
- 支持跨源搜索、分类发现、详情解析、订阅源启停/编辑/删除、健康检测以及收藏后的换源。

### 本地内容与个性化

- 支持导入本地小说、漫画和视频；小说覆盖 TXT、Markdown、HTML、EPUB、FB2、DOCX、ODT，漫画覆盖图片、PDF 与常见压缩包。
- 支持手动调整书架顺序、自定义作品封面、阅读背景、浅色/深色/个性主题和页面转场方式。

### 隐私、授权与应用信息

- 应用没有账号系统、自有业务服务端、广告、行为分析或崩溃上报；收藏、设置和阅读/播放进度默认保存在本机。
- 导入文件、目录、封面或背景时使用 Android 系统选择器，由用户对每次操作单独授权，不申请整盘存储读取权限。
- 应用内提供免责声明、用户隐私与协议、第三方开源许可、版本与官方更新入口，以及完全自愿的打赏入口。

## 系统要求

- Android 7.0（API 24）及以上。
- 安装包名：`com.driskrain.sourceworldapp`。
- 版本：`versionName=1.0.0`，`versionCode=1`。

## 安装与更新

从本仓库或对应的官方 Gitee 发行版下载 `SourceWorldAPP-v1.0.0.apk` 和 `SHA256SUMS.txt`，核对 SHA-256 后安装。后续版本只有在包名相同、使用同一正式签名证书且 `versionCode` 更高时才能覆盖升级并保留本地数据。

应用首发不静默检查、后台下载或自动安装更新；“前往 Gitee 下载”只会在用户点击后打开 Gitee 发行版页。

## 已知限制与安全提醒

- 应用本身不内置或运营小说、漫画、影视等第三方内容，订阅源的合法性、准确性、稳定性和持续可用性由用户及对应网站判断。
- 第三方网站可能改变接口、启用风控、限制地区或停止服务；源失效不一定代表应用故障。
- 部分历史订阅源使用明文 HTTP，连接可能被观察或篡改。请只导入可信规则，避免向不可信站点提交敏感信息。
- 视频播放还会受到媒体地址有效期、CDN 地区策略、设备解码能力和当前网络出口影响。
- 正式发布渠道不会提供签名私钥、密码、Token、用户数据、R8 mapping 或项目源代码。

## 发布验证

- Release 单元测试、Android Lint、R8 与资源压缩构建通过。
- 包名、版本号、APK SHA-256、源码提交号和 v2 签名已重新核对。
- 已使用同一正式签名的内部递增版本在真机完成覆盖升级和数据保留测试；发布者已完成功能复核。
- GitHub 与 Gitee 必须提供上述同一个 APK 字节和同一份 `SHA256SUMS.txt`。若两个平台的校验值不同，请停止安装。

安装或使用前请阅读：

- GitHub：[免责声明](https://github.com/DriskRain/SourceWorldAPP-Releases/blob/v1.0.0/DISCLAIMER.md) · [隐私说明](https://github.com/DriskRain/SourceWorldAPP-Releases/blob/v1.0.0/PRIVACY.md)
- Gitee：[免责声明](https://gitee.com/drisk/source-world-app-releases/blob/v1.0.0/DISCLAIMER.md) · [隐私说明](https://gitee.com/drisk/source-world-app-releases/blob/v1.0.0/PRIVACY.md)
