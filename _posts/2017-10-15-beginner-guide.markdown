---
layout:     post
title:      "新手指南"
subtitle:   ""
date:       2017-10-15 16:06:19
author:     "Deardrops"
header-img: "img/post-bg-2015.jpg"
tags:
    - 指南
---

> 本文面向初次使用 github 的人，如果你对 Github 非常了解，可以跳过这篇，阅读[进阶指南](https://osu-translate-zh.github.io/2017/10/15/advance-guide)。

这篇指南将会介绍这些内容：

- Markdown 标记语言
- Github 代码托管网站
- osu!wiki 翻译流程
- osu!wiki 审阅流程

## Markdown

Markdown 是一门为写作而生的语言，用一些特殊符号作为标记，即可以实现插入链接和图片、添加表格、加粗字体等功能。

Markdown 非常简单，标记语法很少，任何人都可以在短时间内学会使用它。

详细教程参阅：
- [简书的 Markdown 新手指南](http://www.jianshu.com/p/q81RER)
- [Github 的 Markdown 教程（英文）](https://guides.github.com/features/mastering-markdown/)

## Github

代码托管平台 Github 有一套简单敏捷的工作流程，如果你还不了解的话，可以阅读：

- [Github 工作流（英文）](https://guides.github.com/introduction/flow/) - 五分钟了解 Github 工作流

《Pro git》中的相关介绍：
- [6.1 GitHub - 账户的创建和配置](https://git-scm.com/book/zh/v2/GitHub-%E8%B4%A6%E6%88%B7%E7%9A%84%E5%88%9B%E5%BB%BA%E5%92%8C%E9%85%8D%E7%BD%AE) - 详细地介绍如何创建一个 Github 账号
- [6.2 GitHub - 对项目做出贡献](https://git-scm.com/book/zh/v2/GitHub-%E5%AF%B9%E9%A1%B9%E7%9B%AE%E5%81%9A%E5%87%BA%E8%B4%A1%E7%8C%AE) - 详细地介绍如何 Fork 仓库，发起 Pull Request

## 翻译指南

官方仓库（osu-wiki）上有一篇贡献指南，讲解了如何 Fork 官方仓库进行翻译。

包括使用 Git 进行**本地翻译**和使用 Github 的在线文本编辑器（Web editor）进行**在线翻译**两种方式。

对于新手来说，掌握「在线翻译」这种方式已经足够。即在「在线文本编辑器」中输入翻译内容并提交。

详细的说明请参阅：[osu!wiki 贡献指南](https://osu.ppy.sh/help/wiki/osu!wiki_contribution_guide)

## 审阅流程

Reviewer 身份组的工作是审阅别人的翻译，留下自己的意见和建议。这与一般的 Review 工作流没有区别。

你可以在 osu-translate-zh 的 [Pull Request 列表](https://github.com/osu-translate-zh/osu-wiki/pulls) 中查看需要 Review 的 PR。

在 PR 中点击某个特定的 Commit 或者点击 `Files changed`，即可看到相关的修改。

鼠标移动到某行上，直接点击即可输入自己的评论（Comment）。

输入后请点击 `start review` 或 `add review comment`。

完成审阅后，点击评论框中的 `Finish your review`，可以在右上角的文本框中输入总结性的评论。

最后点击 `Submit review`，即完成了一次 Review。

## 结束语

至此，你已经学习了所有必需的知识，开始为 osu! 贡献自己的翻译吧！

你也可以继续学习 Git 的使用，然后阅读[进阶指南](https://osu-translate-zh.github.io/2017/10/15/advance-guide)。

## 补充内容：学习 Git

Git 是一个免费、开源的分布式版本控制系统。

简单说，Git 可以保存文件（比如文本文件，图片等等）的**多个版本**，并上传到服务器上保存起来。

这样不仅可以迅速地找回或回退到任意某次修改前的内容，同时也便于他人下载这些文件到本地，修改一些内容，进行协作工作。

学习如何使用 Git，请参阅：
- [廖雪峰的 Git 教程](https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000) - 面向新人的 Git 入门教程。
- [果壳中的 Git](https://github.com/geeeeeeeeek/git-recipes/wiki) - 清晰明了地讲解如何使用 Git 和 Github。
- [《Pro Git》（第二版）](https://git-scm.com/book/zh/v2) - 深入理解 Git 中的概念，系统学习 Git 中的命令。

学习 Git 并不是一件轻松的事情，很多时候，动手执行会让你很更快地理解那些晦涩的概念。
