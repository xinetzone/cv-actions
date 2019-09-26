# 动手实践计算机视觉

[![GitHub issues](https://img.shields.io/github/issues/xinetzone/cv-actions)](https://github.com/xinetzone/cv-actions/issues) [![GitHub forks](https://img.shields.io/github/forks/xinetzone/cv-actions)](https://github.com/xinetzone/cv-actions/network) [![GitHub stars](https://img.shields.io/github/stars/xinetzone/cv-actions)](https://github.com/xinetzone/cv-actions/stargazers) [![GitHub license](https://img.shields.io/github/license/xinetzone/cv-actions)](https://github.com/xinetzone/cv-actions/blob/master/LICENSE) [![HitCount](http://hits.dwyl.io/xinetzone/cv-actions.svg)](http://hits.dwyl.io/xinetzone/cv-actions) ![PyPI - Python Version](https://img.shields.io/pypi/pyversions/cv) ![repo size](https://img.shields.io/github/repo-size/xinetzone/cv-actions.svg) [![contributors](https://img.shields.io/github/contributors/xinetzone/cv-actions.svg)](https://github.com/xinetzone/cv-actions/graphs/contributors) [![watcher](https://img.shields.io/github/watchers/xinetzone/cv-actions.svg)](https://github.com/xinetzone/cv-actions/watchers)

打造一个用于学习和探索计算机视觉的社区。

## 项目初始化

项目目录清单：

- `/docs/`：存放一些教程，使用说明之类的文档（注意：使用 markdown 书写）
- `data/`: 数据的存放
- `models/`: 模型的参数存储
- `outputs/`: 模型的输出结果，可以创建子目录 `data/` 存放大文件
- `/app/`：存放相关的 API
- `notebook/`：存放 jupyter notebook 等相关的文件
- `draft/`：(可以放置在任何位置)存放一些不成熟的或者未开发完成的一些相关内容，不被上传到 github

由于 `data/`，`models/`，`draft/` 加入到 `.gitignore` 不被 git 管理，所以，当您 fork 到本地时，需要在终端执行：

```sh
$ mkdir data draft models
```

为了避免项目的混乱，使用 Git Flow 进行管理。当您将项目克隆的本地电脑后，请您运行：`git flow init` 并随之切换到 develop。具体是使用请 :book: <https://xinetzone.github.io/projects/>。

## 待办事项

- [ ] 在 `/docs/` 中创建一个社区（暂定 <https://gitpress.io/c/cv_actions/>），使其支持 Katex
- [ ] 补充计算机视觉动手实践教程

## 投稿

请阅读 [CONTRIBUTING](CONTRIBUTING.md)，了解本站的行为准则以及如何提交拉取请求。不想贡献代码者可以在 `/docs/` 中提供教程等文档。

## 版本发布

遵循 [语义化版本](https://semver.org/lang/zh-CN/) 进行版本控制。

## 作者

- **刘新伟** - **项目发起者** - [xinetzone](https://github.com/xinetzone)

另请参阅参与此项目的[贡献者](https://github.com/xinetzone/cv-actions/graphs/contributors)列表。

## 许可证

此项目根据 GNU GPL-v3 许可证获得许可 - 有关详细信息，请参阅 [LICENSE](LICENSE.md) 文件。

## 致谢

- 感谢所有使用和参与本项目的人
