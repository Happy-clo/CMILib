# CMILib

## 介绍

这是一个插件帮助工具，或者叫做**库**，它是一个方便的工具，可以让我们轻松管理常用短语、十六进制颜色等。通过使用这个库，其他插件不需要编写自己的代码来实现这些功能，而是可以共享这些功能，并为其他开发者提供API来扩展他们自己的插件功能。

这样一来，其他插件的整体大小会减小，更新和维护插件也会更加简单和一致。

**注意：**所有Zrips的插件都需要使用这个库。

## 库的发布和更新

强烈建议始终保持这个库是最新的版本。你可以从以下网站下载最新的构建版本：

- [开发者的官方网站](https://www.zrips.net/cmilib/)
- [Spigot发布页面](https://www.spigotmc.org/resources/87610/)

## 安装指南

**与所有插件更改一样，请确保在此之前先停止服务器并进行完整备份。**

从[库的发布和更新](#库的发布和更新)部分提到的发布网站下载最新版本的库，然后将其放置在服务器的`plugins/`目录下。

为了避免冲突，建议首先在没有依赖于此库的插件的情况下加载此库，这将确保任何问题与库本身无关，而是与依赖的插件有关，然后你应该向插件的开发者报告问题，以便他们更新插件以适应库的更改。

你的服务器应该可以无问题地启动。在第一次启动后，服务器的`plugins/`目录下会创建一个名为`CMILib`的新文件夹。这个文件夹包含了库的配置文件。你可以根据需要编辑这些文件，但这不是必需的。如果你在进行翻译，请确保向该仓库发送拉取请求。

在这个阶段，你应该再次运行`/stop`命令，添加依赖于这个库的插件，并按需进行设置。

## 支持

如果你在使用这个库时遇到了问题，请查看下面的[贡献部分](#contributing)，了解如何报告问题的信息。

在询问问题之前，请确保阅读我们的[常见问题解答](https://www.zrips.net/cmilib/faq/)。

你也可以在[Zrips社区的Discord](https://discord.gg/dDMamN4)上请求支持并与社区成员讨论问题。

## 贡献

你可以自由地克隆这个仓库并提交拉取请求来提供bug修复和/或建议。

你也可以以[新问题](https://github.com/Zrips/CMILib/issues/new)的形式报告bug和/或提出建议，但**请确保**在提交之前检查你提交的内容在[问题选项卡](https://github.com/Zrips/CMILib/issues)中是否是重复的或者是否已经在[拉取请求](https://github.com/Zrips/CMILib/pulls)中处理过。

## 需要使用这个库的插件

你开发了一个使用这个库的插件吗？告诉我们，我们会将它添加到列表中！

注意：由于Markdown的限制，点击链接会在本页中打开它。若要在新标签页中打开它，请右键点击并选择“Open in new tab”。

| 插件名称 (Spigot链接)                                           | 版本范围 | 最新版本 | 插件作者                             |
|:------------------------------------------------------------:|:-------:|:-------:|:----------------------------------:|
| [BottledExp](https://www.spigotmc.org/resources/bottledexp.2815/)                                 |   3.x   |  latest | [Zrips](https://www.spigotmc.org/resources/authors/zrips.24572/) |
| [CMI](https://www.spigotmc.org/resources/cmi-298-commands-insane-kits-portals-essentials-economy-mysql-sqlite-much-more.3742/) |   9.X   |  latest | [Zrips](https://www.spigotmc.org/resources/authors/zrips.24572/) |
| [JobsReborn](https://www.spigotmc.org/resources/jobs-reborn.4216/)                                |   5.X   |  latest | [Zrips](https://www.spigotmc.org/resources/authors/zrips.24572/) |
| [MobFarmManager](https://www.spigotmc.org/resources/mob-farm-manager-supports-1-7-10-up-to-1-19-hopper-support.15127/)     |   2.X   |  latest | [Zrips](https://www.spigotmc.org/resources/authors/zrips.24572/) |
| [Recount](https://www.spigotmc.org/resources/recount.3962/)                                     |  3.5.X  |  latest | [Zrips](https://www.spigotmc.org/resources/authors/zrips.24572/) |
| [Residence](https://www.spigotmc.org/resources/residence-1-7-10-up-to-1-19.11480/)                   |   5.X   |  latest | [Zrips](https://www.spigotmc.org/resources/authors/zrips.24572/) |
| [SelectionVisualizer](https://www.spigotmc.org/resources/selection-visualizer.22631/)               | 3.0.4.X |  latest | [Zrips](https://www.spigotmc.org/resources/authors/zrips.24572/) |
| [TradeMe](https://www.spigotmc.org/resources/trademe-with-api-to-create-custom-trades-1-7-10-1-19-x.7544/)  |   6.1.X  |  latest | [Zrips](https://www.spigotmc.org/resources/authors/zrips.24572/) |
| [TryMe](https://www.spigotmc.org/resources/tryme.3330/)                                      |   7.X   |  latest | [Zrips](https://www.spigotmc.org/resources/authors/zrips.24572/) |
> [!CAUTION]  
> This branch is only used for personal development to provide builds or help. Please do not use the build attachments directly. The author is not responsible for any problems with the source plugin.
# Statement

> [!CAUTION]  
> 本分支仅用于个人开发提供学习研究，请勿直接使用任何附件。如出现任何有关源附件问题，本作者概不负责。

---

> [!CAUTION]  
> This branch is only for personal development, study and research. Please do not use any attachments directly. The author is not responsible for any problems with the source attachments.
