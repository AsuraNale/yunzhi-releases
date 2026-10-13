# 云织 · Yunzhi

云织是一个 Windows 桌面研究助手，面向政策、公共事务和产业经济方向的研究员。你把委托交给它，它和你一起明确任务、收集资料、拟定提纲、写成稿；每到关键一步都会停下来，请你确认后再往下走。

> **这是试用版（0.2，实验性质）。** 功能和界面还在改，请不要用于正式交付。遇到问题，请把现象和截图告诉我们。

## 下载

到 [Releases](https://github.com/AsuraNale/yunzhi-releases/releases/latest) 下载最新的安装包 `Yunzhi-<版本号>-setup.exe`。

## 你需要准备

- Windows 10 或 11，64 位。
- 一个 **DeepSeek API key**，在 [platform.deepseek.com](https://platform.deepseek.com/) 注册后的 API keys 页面生成。研究按用量向 DeepSeek 付费，费用由 DeepSeek 收取，云织不经手。
- 能连上 DeepSeek 的网络。

## 安装

1. 双击下载的安装包。
2. 这一版**没有代码签名**，Windows 会弹出蓝色的「Windows 已保护你的电脑」。点「**更多信息**」，再点「**仍要运行**」。
3. 安装不需要管理员权限，大约一两分钟。装完后，开始菜单和桌面上会出现「云织」。
4. 第一次打开时有两步：填 DeepSeek API key，选研究项目的存放位置。

界面语言跟随系统：系统是中文就显示中文，否则显示英文。可以在「设置 → 语言」里切换。

## 更新

- **0.2.1 及以后**：打开「设置」，在最下面的「关于」里点「检查更新」。有新版本时点「下载并更新」，再点「开始更新」。云织会自己关闭、安装、再重新打开，项目和设置都保留。
- **0.2.0**：这一版还没有更新功能。下载新的安装包，双击直接安装即可，**不用先卸载**，项目和设置都会保留。

## 卸载

打开「设置 → 应用 → 已安装的应用」，找到「云织 0.2 试用版」，点「卸载」。

- 卸载不会删除你的研究项目文件夹。
- 最后会问一次要不要同时删除应用数据（key 和确认记录），默认不删。

## 数据和隐私

- API key 只保存在你自己的电脑上，经 Windows 加密存储。
- 研究进行时，云织会把对话、任务材料和项目文件夹的路径发给 DeepSeek 的模型接口，这是研究本身需要的。助手联网搜索或打开网页时，会访问相应的网站。
- 侧栏的余额显示会定时向 DeepSeek 查询账户余额。
- 云织不收集使用数据，也不把你的内容发给 DeepSeek 以外的服务。

## English

Yunzhi is a Windows desktop research assistant for policy and economics researchers. It plans the task, collects sources, drafts an outline and writes the deliverable with you, and it stops for your confirmation at each key step. **This is a trial build (0.2, experimental).**

- **Requirements:** Windows 10/11 64-bit and a DeepSeek API key from [platform.deepseek.com](https://platform.deepseek.com/). DeepSeek bills usage directly.
- **Install:** run the latest `Yunzhi-<version>-setup.exe` from [Releases](https://github.com/AsuraNale/yunzhi-releases/releases/latest). The installer is unsigned, so SmartScreen will warn you; click **More info**, then **Run anyway**. No administrator rights are needed.
- **Language:** the interface follows your system language and can be switched in Settings → Language. In this version, the assistant's own writing (cards, documents, the deliverable) is still in Chinese.
- **Update:** from 0.2.1 on, Settings → About → Check for updates, then download and update; Yunzhi closes, installs and reopens with your projects and settings kept. On 0.2.0, run the new installer over it (no uninstall needed).
- **Uninstall:** Settings → Apps → Installed apps → 云织 0.2 试用版 → Uninstall. Your project folders are kept.

---

© 2026 Starry Data & Technology Inc. 第三方组件的许可声明随安装包附带（安装目录下的 `THIRD-PARTY-NOTICES.txt`）。
