# [VIA Web 应用](https://usevia.app) - 您键盘的最佳伙伴

![android-chrome-192x192](https://github.com/kap1bala/via-app-zh/blob/main/public/android-chrome-192x192.png?raw=true)

VIA 是一个强大的、开源的基于网络的界面，用于配置你的 [QMK](https://qmk.fm) 机械键盘。它允许你自定义你的键位映射、创建宏，以及动态调整 RGB 设置（如果它有 RGB），而无需重新编译你键盘的固件。这使得键盘定制更加容易和普及。

> [!IMPORTANT]
> 本项目是 [the-via/app](https://github.com/the-via/app) 的非官方汉化版本，且不随原项目同步。

## 让 VIA 支持你的键盘

你是键盘制造商还是对添加你键盘支持感兴趣的开发者？我们欢迎对 VIA 项目做出贡献！

1. 键盘的源代码 **必须合并到** [QMK 固件仓库](https://github.com/qmk/qmk_firmware) 的主分支。
2. 你的 `keymaps/via` 键映射 **必须合并到** [VIA 的 QMK 用户空间存储库](https://github.com/the-via/qmk_userspace_via) 主分支中。
3. 为您的键盘创建一个 JSON 格式的定义，并将其作为 pull request 提交到 [VIA 的键盘仓库](https://github.com/the-via/keyboards) 主分支。

请遵循我们的 [规范文档](https://www.caniusevia.com/docs/specification) ，以确保您的 pull request 能够顺利通过审核并被合并。

## 本地开发环境设置

### 有用的命令

#### `npm run start`

在开发模式下运行应用。
在浏览器中打开 [http://localhost:8080](http://localhost:8080) 查看它。

如果你进行编辑，页面将重新加载。
你还会在控制台中看到任何代码风格错误。

#### `npm run build`

将你的站点静态复制到 `build/` 文件夹。
你的应用已准备好部署！

#### `npm run test`

启动应用测试运行器。
使用 `--watch` 标志 (`npm test -- --watch`) 以交互式监视模式运行。

---

这个项目在 [BrowserStack](https://www.browserstack.com/) 上进行了测试。

## 寻找离线应用？

@cebby2420 善意地制作了一个桌面应用来实现这一功能。

你可以在 [https://github.com/cebby2420/via-desktop](https://github.com/cebby2420/via-desktop) 找到它。

**注意：该项目与 VIA 没有官方关联，我们无法为其提供支持。**

## 遇到问题？

如果您在使用 [VIA 网络应用程序](https://usevia.app) 时遇到任何问题或错误，请通过在 [Issues 部分](https://github.com/the-via/app/issues) 打开问题来报告它们。这将帮助我们追踪并解决问题，并改善 VIA 的体验。

在报告之前，请确保检查是否已经报告过该问题。谢谢！
