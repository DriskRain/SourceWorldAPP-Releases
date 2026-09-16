# 源世界 v1.0.1 发布说明

`v1.0.1` 是 `v1.0.0` 之后的维护版本，集中完善更新、声明与联系入口，并优化阅读界面的稳定显示。

## 本次更新

- 版本页新增主动检查更新，可从 Gitee 获取最新正式版、校验 APK 后交给 Android 系统确认安装；GitHub/Gitee 发布页入口继续保留。
- “我的”页将免责声明与开源许可统一收纳到“声明”页面，层级更清晰。
- 新增“我们”页面，可查看并复制官方 QQ 群号。
- 优化小说翻页底栏的章节标题宽度，长标题会稳定省略，同时保持右侧页码和阅读进度位置不变。
- 优化小说、漫画和视频三列/四列网格的阅读进度，保持单行展示和卡片等高。
- 精简首次启动协议摘要，完整的文件选择授权说明继续保留在协议正文。

## 发布校验

- 安装包：`SourceWorldAPP-v1.0.1.apk`
- SHA-256：`0cd7c88d3363887df6ecacefeebaa082d663768b94fa2a554b5c68ddb2b1cc99`
- 包名：`com.driskrain.sourceworldapp`
- 版本：`versionName=1.0.1`，`versionCode=2`
- 源码提交：[`72f4999ef1e032df4a937077fe902af353e67557`](https://github.com/DriskRain/NewReadingAPP/commit/72f4999ef1e032df4a937077fe902af353e67557)
- 签名：APK Signature Scheme v2 校验通过

## 安装与升级

- Android 7.0（API 24）及以上可安装。
- 从 `v1.0.0` 升级时直接覆盖安装，不要先卸载；收藏、设置和阅读进度等本地数据可继续保留。
- 请从本仓库或对应的官方 Gitee 发行版下载 APK，并使用同一发行版的 `SHA256SUMS.txt` 核对文件。
- 若 GitHub 与 Gitee 的 APK 校验值不同，请停止安装并等待官方说明。

## 验证结果

- Release 单元测试 371 项全部通过，Android Lint 无 error。
- R8、资源压缩、正式签名构建和 APK 独立签名校验通过。
- 已完成 `v1.0.0` 到 `v1.0.1` 的覆盖升级，隐私同意状态、主题设置与应用数据目录得到保留。
- 已复核版本检查、声明层级、“我们”页面及 QQ 群列表等关键交互。

安装或使用前请阅读：

- GitHub：[免责声明](https://github.com/DriskRain/SourceWorldAPP-Releases/blob/v1.0.1/DISCLAIMER.md) · [隐私说明](https://github.com/DriskRain/SourceWorldAPP-Releases/blob/v1.0.1/PRIVACY.md)
- Gitee：[免责声明](https://gitee.com/drisk/source-world-app-releases/blob/v1.0.1/DISCLAIMER.md) · [隐私说明](https://gitee.com/drisk/source-world-app-releases/blob/v1.0.1/PRIVACY.md)
