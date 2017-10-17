---
layout:     post
title:      "osu! 中文翻译指南"
subtitle:   ""
date:       2017-10-15 16:06:19
author:     "deardrops"
header-img: "img/post-bg-2015.jpg"
tags:
    - 指南
---

## 组织介绍

![shield](https://img.shields.io/badge/organization-osu!translate%20zh-blue.svg?style=flat-square)

osu-translate-zh（osu!中文翻译组织）是由玩家自发参与和贡献的翻译组织，负责 osu! 官方中文翻译工作。

翻译的内容包括 `osu!lazer`，`osu-web` 和 `osu-wiki`。其中：

- `osu!lazer` 正在开发中，i18n（国际化）相关的功能尚未完成，客户端的翻译工作将会在这些功能完成后开始。
- `osu-web` 目前官网页面的翻译与开发进度保持一致，会以每个月补丁的形式增加新的翻译或者修订已有的翻译。
- `osu-wiki` 是翻译工作的重点，Wiki 中有大量新增的内容和大量过时的内容需要翻译，精简，修订和补充。

翻译的语言包括简体中文（zh），繁体中文（zh-tw），其中也包括粤语（zh-hk）。

翻译组织的大部分成员来自大陆，因此简体中文的翻译是最先进行的。

~~在繁体中文负责人被提名前，简体中文的文章会用工具转换为繁体，再通过人工审阅的方式修订最终的翻译。~~

粤语相关的翻译问题正在讨论中。

*****

为了相互交流和协作，翻译出高质量的内容，我们成立了 osu!中文翻译组织。

我们希望能提供和谐的讨论环境，准确和合适的翻译参考，高效率地进行翻译工作。

## 加入我们

![[Discord链接](https://discord.gg/Gud9s9z)](https://discordapp.com/api/guilds/281826842657161216/widget.png?style=banner2)

osu!中文翻译组织 欢迎**任何人**参加到翻译工作中，具体要求包括：

- 会使用 Markdown 文本标记语言
- 注册一个 Github 账号
- 足够的耐心和负责任的态度

下面两项可作为加分项：

- 对 osu! 有相当程度的了解
- 有 Wiki 内容编写或翻译的经验

如果你没有这方面的特长，请不用担心，你也可以加入我们贡献一份的微薄之力，我们会安排合适你的相对轻松的工作。

## 工作流程

现在，osu!wiki 的所有内容搬运到了 Github 上的 [osu-wiki 仓库](https://github.com/ppy/osu-wiki)中，所有翻译工作也是按照 Github 的工作流来完成的（Fork, Pull request, Merge）来进行的。

官方有一套完整的 [osu!wiki 贡献指南](https://osu.ppy.sh/help/wiki/osu!wiki_contribution_guide)，osu!中文翻译组织沿用了这样的贡献指南，但请注意有一个重要的**不同之处**：

- 我们有自己的组织仓库（[osu-translate-zh/osu-wiki](https://github.com/osu-translate-zh/osu-wiki)），区别于官方的仓库（[ppy/osu-wiki](https://github.com/ppy/osu-wiki)）。
中文翻译工作会在**组织仓库中**进行，在组织内审阅完成后，以组织的名义上传（Pull Request）到官方仓库。
这是为了更方便地进行中文讨论，及时追踪中文翻译进度，安排翻译任务。

具体工作流程，请根据自己的情况阅读下面两篇指南：

- 如果你刚刚接触 Github，请阅读这篇[新手指南](https://osu-translate-zh.github.io/2017/10/15/beginner-guide)。

- 如果你能熟练地使用 Git，请阅读这篇[进阶指南](https://osu-translate-zh.github.io/2017/10/15/advance-guide)。

## 翻译指南

### 规则 Rules

1. 所有标点符号均用中文标点。
2. 除部分半角符号，所有半角字符（包括但不限于符号、字符、数字）与全角字符之间必须加一个空格。
3. 尽量避免有第二人称出现（如：您），如果必须使用，统一用“您、我、他/她/它”。
4. 如果原文有标点符号则翻译为中文标点（规则同 2），没有则不加。
5. 部分地方避免出现句号（如：提示框）。
6. 专有名词或句子会在社区讨论后再进行翻译。
7. 专有名词统一后，禁止出现第二种翻译方法（如：subforum 确定为子版块后，不允许再出现分论坛等翻译）。
8. 可以适当加入一些诙谐的翻译结果或者表情符号（如：非低俗流行语或颜文字）。
9. 专有句子避免直接翻译，尽量饱含文学气息（也就是文艺一点）。
10. 更多翻译说明会在公布文字时提出。

### 文章风格指南 ASC

ASC 由 [@kj415j45](https://github.com/kj415j45) 负责翻译。目前 en 版本已完成，中文翻译正在进行中。

### 名词对照表

目前正在整理中，参见：

[osu! 中文翻译 名词对照表](https://docs.google.com/spreadsheets/d/1zhUP0qekKRUWb1Mu-P89mwu_HcPBen5FoGPqD2MkI7k)

## Github 贡献指南

### Commit message 规范

请参照以下的 Commit message：

1. `zh: init translation` 第一个 commit。

复制 `en.md` 并重命名为 `zh.md`。

2. `zh: 英文的文章标题` 完成了部分翻译。

可以重复使用多次这句 Commit message。但是，太多的话会被 Squash 成一次 Commit。

当某篇 Wiki 包含子页面时，请使用 `-` 符号连接，写上完整的标题。例如： `Ranking_Criteria - osu!catch`

3. `zh: apply reivews` 根据 review 修改一些翻译语句。

4. `zh: finish 英文的文章标题` 完成了所有翻译。

这句作为最后的 commit，也作为 merge commit。

注意：Commit messege **不可以** 包含中文。

### Pull request 规范

PR 命名和内容都没有特别的要求，中文英文均可，只要能清楚的表达意思就行。

## 相关链接

[osu! 中文翻译 名词对照表](https://docs.google.com/spreadsheets/d/1zhUP0qekKRUWb1Mu-P89mwu_HcPBen5FoGPqD2MkI7k)

[osu!wiki 中文翻译 进度表](https://docs.google.com/spreadsheets/d/1zjXM0BAWA-bYDGcxPUlysO_G3IZcbsQJ9c8fv_7OOeY)

[osu!wiki 中文翻译 任务表](https://github.com/orgs/osu-translate-zh/projects/1)

[osu!wiki 翻译完成进度](https://github.com/osu-translate-zh/osu-wiki/issues/1)
