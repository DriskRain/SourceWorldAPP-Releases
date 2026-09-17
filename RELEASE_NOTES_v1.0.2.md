# 源世界 v1.0.2 发布说明

`v1.0.2` 是 `v1.0.1` 之后的维护版本，完善订阅源导入、搜索记录管理、更新检查和隐私说明。

## 本次更新

- 剪贴板可一次识别多个订阅源网址；每个网址可返回一条或多条订阅源，部分网址失败时会指出对应地址，并保留其他成功结果。
- 搜索历史支持单条删除、长按进入多选以及批量删除。
- 打开版本页时保持离线，只有用户主动点击“检查更新”后才查询最新正式版。
- 首次确认和应用内隐私正文进一步明确：源世界不向开发者收集、上传或出售个人信息与使用数据；小屏横竖屏下可完整滚动阅读协议，决定按钮保持可见。

## 发布校验

- 安装包：`SourceWorldAPP-v1.0.2.apk`
- SHA-256：`f44866e0c13b1b719c21932e91c8162bc08d493a872fe230057bae5def261674`
- 包名：`com.driskrain.sourceworldapp`
- 版本：`versionName=1.0.2`，`versionCode=3`
- 源码提交：[`31dc74fe280b4c5ff23ab56430c3b6d4ca729814`](https://github.com/DriskRain/NewReadingAPP/commit/31dc74fe280b4c5ff23ab56430c3b6d4ca729814)
- 签名：APK Signature Scheme v2 校验通过

## 安装与升级

- Android 7.0（API 24）及以上可安装。
- 从 `v1.0.0` 或 `v1.0.1` 升级时直接覆盖安装，不要先卸载；收藏、设置和阅读进度等本地数据可继续保留。
- 请从本仓库或对应的官方 Gitee 发行版下载 APK，并使用同一发行版的 `SHA256SUMS.txt` 核对文件。
- 若 GitHub 与 Gitee 的 APK 校验值不同，请停止安装并等待官方说明。

## 验证结果

- 93 个 Release 测试套件、374 项测试全部通过，Android Lint 无 error。
- R8、资源压缩、正式签名构建和 APK 独立签名校验通过。
- 订阅源导入设备测试 7 项全部通过；隐私协议已复核 360×640dp 竖屏与 640×360dp 横屏布局。
- 已完成 `v1.0.1` 到 `v1.0.2` 的覆盖升级，安装时间和既有隐私同意状态得到保留。

安装或使用前请阅读：

- GitHub：[免责声明](https://github.com/DriskRain/SourceWorldAPP-Releases/blob/v1.0.2/DISCLAIMER.md) · [隐私说明](https://github.com/DriskRain/SourceWorldAPP-Releases/blob/v1.0.2/PRIVACY.md)
- Gitee：[免责声明](https://gitee.com/drisk/source-world-app-releases/blob/v1.0.2/DISCLAIMER.md) · [隐私说明](https://gitee.com/drisk/source-world-app-releases/blob/v1.0.2/PRIVACY.md)
