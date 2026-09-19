# 源世界 v1.0.3 发布说明

`v1.0.3` 是 `v1.0.2` 之后的维护版本，重点完善视频倍速与全屏交互，并修复搜索历史显示问题。

## 本次更新

- 视频初次加载、等待首帧、重缓冲或暂停时均可长按进入二倍速；暂停长按会直接恢复播放。
- 竖屏全屏支持将长按手指拖到底部目标锁定或解除二倍速，提示会避开刘海与系统栏；竖屏菜单和透明状态栏同步显隐，横屏维持原沉浸布局。
- 手动倍速在当前视频详情和换集间保持，离开详情后恢复 1x；拖动画面调整进度并松手后直接收起，不再闪回完整控制栏。
- 搜索历史恢复紧凑单行间距，单条删除改用“×”；清空输入后，旧搜索请求的迟到结果不会重新显示在历史下方。

## 发布校验

- 安装包：`SourceWorldAPP-v1.0.3.apk`
- SHA-256：`df22d53fea1a7cb8e5205a01e5c2cf77034635f6758942525c46d59904824279`
- 包名：`com.driskrain.sourceworldapp`
- 版本：`versionName=1.0.3`，`versionCode=4`
- 源码提交：[`a024da70eaa5d4ac8396f1776d864b3b0322af39`](https://github.com/DriskRain/NewReadingAPP/commit/a024da70eaa5d4ac8396f1776d864b3b0322af39)
- 签名：APK Signature Scheme v2 校验通过

## 安装与升级

- Android 7.0（API 24）及以上可安装。
- 从旧版本升级时直接覆盖安装，不要先卸载；收藏、设置、历史和阅读/播放进度等本地数据可继续保留。
- 请从本仓库或对应的官方 Gitee 发行版下载 APK，并使用同一发行版的 `SHA256SUMS.txt` 核对文件。
- 若 GitHub 与 Gitee 的 APK 校验值不同，请停止安装并等待官方说明。

## 验证结果

- 93 个 Release 测试套件、383 项测试全部通过，Android Lint 无 error。
- R8、资源压缩、正式签名构建和 APK 独立签名校验通过。
- Android 模拟器播放器交互回归 6/6 通过。
- 已在真机和模拟器完成 `v1.0.2` 到 `v1.0.3` 的覆盖升级；首次安装时间和既有隐私同意状态均保留，升级后可正常进入主界面。

安装或使用前请阅读：

- GitHub：[免责声明](https://github.com/DriskRain/SourceWorldAPP-Releases/blob/v1.0.3/DISCLAIMER.md) · [隐私说明](https://github.com/DriskRain/SourceWorldAPP-Releases/blob/v1.0.3/PRIVACY.md)
- Gitee：[免责声明](https://gitee.com/drisk/source-world-app-releases/blob/v1.0.3/DISCLAIMER.md) · [隐私说明](https://gitee.com/drisk/source-world-app-releases/blob/v1.0.3/PRIVACY.md)
