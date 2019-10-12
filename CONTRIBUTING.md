# 贡献指南

非常感谢您乐意为 cv actions 提供新鲜血液。正是更多像您这样的人，使得 cv actions 将逐渐发展为一个强大的计算机视觉社区。

为了创建一个良好的社区环境，请您遵守我们社区的《[行为准则](CODE_OF_CONDUCT.md)》。如果您想要发起一个 Bug report 或者 Feature request，请您遵循 Issue 的模板进行贡献。同时也欢迎您贡献新的且实用的 Issue 与 Pull request templates。

请您仔细阅读这份指南，因为，如果您这样做了，既可以节省您的宝贵时间，同时也对其他贡献者或者审阅者们的极大的尊重。

本项目的**目标**是**打造一个健康且可持续发展的计算机视觉社区。**

## 贡献的类型

本项目不仅仅欢迎您贡献代码，同时也欢迎您贡献文档（请在 `/docs/` 中进行），教程或者本项目的使用手册等内容。

## 贡献的必要条件

1. 如果您不了解如何对项目进贡献，请您参考 [如何为开源做贡献](https://opensource.guide/zh-cn/how-to-contribute/)。
2. 为了方便项目的管理，请您使用 Git Flow 进行管理。当您将项目克隆到您的本地电脑后，请您运行：`git flow init` 并随之切换到 develop。具体是使用细节请 📖 <https://xinetzone.github.io/projects/>。
3. 本项目暂定以 Python 作为代码的开发语言，而文档的编写请使用 Markdown 进行工作。
4. 本项目在 GitHub 上维护的 master 分支作为预发布版本，而 develop 分支作为开发版本。其他功能版本请以 git flow 的规则进行管理。
5. 您贡献的 Python 代码需要支持 pep8，数学公式最好使用 markdown 的标准语法，比如 `$x^2=1$`等。

## 贡献文档

如果您仅仅只是想要贡献文档，或者写计算机视觉相关的博客以及拥有好的想法，您可以在 `/docs/` 目录下面进行贡献。贡献的方式很简单，您只需要在 `/docs/` 目录下编写您的文档，之后将您的文章的布局添加到 `TOC.md` 文件中。如果您需要载入图片，请您在 `/docs/images/` 下面放入图片，然后以 `![图片说明](images/你的图片目录/图片名称)` 的形式进行载入。因为 `/docs/` 是通过 GitPress 进行部署的，所以，如果您想要了解更多使用技巧可以参考：[GitPress 学习](https://gitpress.io/c/cv_actions/gitpress_help)。

## Issue 与 Pull request 的行为准则

考虑到可读性与可理解性，在您创建 Issue 或者 Pull request（简写为 PR） 时，请遵循如下约定：

1. **请给出您的 issue 或者 PR 的 context**：即给出上下文语境。比如当您你运行程序时遇到一个错误，请解释你是如何操作的，并描述该错误现象是否具有再现性；当您提交一个新的idea，请您解释该 idea 您是如何想到的，并且说明您的 idea 的适用范围，是否可以将您的 idea 进行推广或者拓展。
2. **您是否已经完成准备工作**：请确认您是否阅读了项目的 README、文档、问题（开放的和关闭的），检查您的 issue 或者 PR 是否已经有人做过或者正在做，避免提交重复的议题或者请求。
3. 请您**保持请求内容的短小而直接**：每个人的时间和精力都是有限的，短小而直接的请求对大家都有益处。
4. **请保持您的优雅**：本社区禁止发布不良信息，注意用语文明而优雅，杜绝各种辱骂和打口水仗的行为。

## 获得联系

- 您可以在 gitter@[cv-actions](https://gitter.im/watersome/community) 上讨论 Issue 等
- 如果有疑问，请您 ✉️ xinzone@outlook.com

## TODOS

- [ ] 利用 [pre-commit](https://pre-commit.com/) 自动部署代码的格式，使其自动化支持 pep8 等格式。
