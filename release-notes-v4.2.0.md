## 下载安装

**[点击下载：抓到你啦 v4.2.0 安装包](https://raw.githubusercontent.com/YGDONER/-/v4.2.0/got-you-v4.2.0.zip)**

[完整源码与测试](https://raw.githubusercontent.com/YGDONER/-/v4.2.0/source-v4.2.0.zip) · [SHA256 校验值](https://raw.githubusercontent.com/YGDONER/-/v4.2.0/SHA256SUMS-v4.2.0.txt)

解压后，Chrome 打开 chrome://extensions（Edge 打开 edge://extensions），开启开发者模式，加载含 manifest.json 的 xhs-note-desk 文件夹。无需 Node、Python 或命令行。

## 本版更新

- 新增 Instagram（ins）平台：帖子、Reels、账号前缀分享链接识别，独立分类与筛选，发布账号识别和多图勾选下载。
- 参考图／视频帧检索停止使用必应和 Google，改为前往所选平台检查原生图片搜索入口。
- 找不到图片搜索专用上传框时明确提示，不使用发帖上传框，不把首页推荐或普通关键词结果当成相似结果。
- 保留自动收录、分类、截图 Ctrl+V、视频本机抽帧、逐张选图、下载队列、三列复制、CSV、备份及原有平台功能。

**能力说明：**ins 网页端参考图上传检索入口尚未确认，当前不向其发送参考图；小红书等平台的登录态原生搜图也尚未完成实站验证。115 项自动检查通过不代表所有平台都已实站可用；无入口时无法自动原生搜图。

## 更新旧版

先导出 JSON 备份，用新版 xhs-note-desk 内文件覆盖原目录，再点击扩展管理页“重新加载”。保持原目录和扩展身份，不要先卸载。若浏览器提示新增 Instagram 网站访问权限，请按提示启用。

本地解压版仅刷新网页不会下载新版代码。当前未上架 Chrome／Edge 扩展商店。本次手动发布，未添加自动写入主分支的 GitHub Actions。
