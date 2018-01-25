---
layout:     post
title:      "osu!中文翻译指南"
subtitle:   ""
date:       2017-10-15 16:06:19
author:     "Deardrops"
header-img: "img/post-bg-2015.jpg"
tags:
    - 指南
---

## 组织介绍 Introduction

![shield](https://img.shields.io/badge/organization-osu!translate%20zh-blue.svg?style=flat-square)

osu-translate-zh（osu!中文翻译组织）是由玩家自发参与和贡献的翻译组织，负责 osu! 官方中文翻译工作。

翻译的内容包括 `osu!lazer`，`osu-web` 和 `osu-wiki`。其中：

- `osu!lazer` 正在开发中，所有语言的翻译工作都尚未开始。
- `osu-web` 目前官网页面的翻译与开发进度保持一致，会以每个月补丁的形式增加新的翻译或者修订已有的翻译。
- `osu-wiki` 是翻译工作的重点，Wiki 中有大量新增的内容需要翻译，有大量过时的内容需要修订和补充。

组织内大部分工作是简体中文（zh-hans）翻译，而繁体中文（zh-hant）使用工具由简体转换而成，再通过人工审阅后发布。

*****

为了相互交流和协作，翻译出高质量的内容，我们成立了 osu!中文翻译组织。

我们希望能提供和谐的讨论环境，准确和合适的翻译参考，从而高效率地共同进行翻译工作。

## 加入我们 Join Us

![[Discord链接](https://discord.gg/Gud9s9z)](https://discordapp.com/api/guilds/281826842657161216/widget.png?style=banner2)

osu!中文翻译组织 欢迎**任何人**参与到翻译工作中，你需要：

- 学习使用 Markdown 文本标记语言
- 注册一个 GitHub 账号
- 足够的耐心和负责任的态度

下面两项可作为加分项：

- 对 osu! 有相当程度的了解
- 有 Wiki 内容编写或翻译的经验

如果你没有这方面的特长，请不用担心，你也可以加入我们贡献一份力量，我们会安排适合你的相对轻松的工作。

## 工作流程 Workflow

现在，osu!wiki 的所有内容搬运到了 GitHub 上的 [osu-wiki 仓库](https://github.com/ppy/osu-wiki)中，所有翻译工作也是按照 GitHub 的工作流来完成的（Fork, Pull request, Merge）来进行的。即在网页或者本地文本编辑器中翻译文章，完成后提交，通过别的贡献者的审阅后，最终呈现在 osu! 官网的 wiki 页面上。

官方有一套完整的 [osu!wiki 贡献指南](https://osu.ppy.sh/help/wiki/osu!wiki_contribution_guide)，手把手教学如何使用 GitHub 和提交自己的翻译，建议新人阅读一遍这篇贡献指南。

为了更方便地进行中文讨论，及时追踪中文翻译进度，安排翻译任务，我们建立了自己的组织仓库（[osu-translate-zh/osu-wiki](https://github.com/osu-translate-zh/osu-wiki)），区别于官方仓库（[ppy/osu-wiki](https://github.com/ppy/osu-wiki)）。

中文翻译工作会在**组织仓库**中进行，在组织内审阅完成后，再上传（Pull Request）到**官方仓库**。

具体工作流程，请参阅 [工作流程](https://osu-translate-zh.github.io/2017/10/15/advance-guide)。

## 翻译指南 Guideness

### 规则 Rules

1. 翻译应当尊重原文，清晰通顺地表达原文意思，并且符合中文阅读的习惯。
2. 翻译可以在不改变原文意思的前提下适当地进行意译，切勿通篇直译或意译。
3. 翻译应当保持客观叙述的语气，不能随意使用「黑话」、「钱语」和「梗」。
4. 标点符号，空格，段落等格式**必须**遵循 [文章风格指南](https://osu.ppy.sh/help/wiki/Article_Styling_Criteria?locale=zh)。
5. 专有词汇参考 [osu! 中文翻译 名词对照表](https://docs.google.com/spreadsheets/d/1zhUP0qekKRUWb1Mu-P89mwu_HcPBen5FoGPqD2MkI7k)。

### 文章风格指南 Article Styling Criteria

[文章风格指南](https://osu.ppy.sh/help/wiki/Article_Styling_Criteria?locale=zh)（简称 ASC）中规定了每篇文章段落排版的具体格式，以及中文翻译时必须遵守的规定，包括人称，中英混合排版时的空格，标点符号的使用等等。

### 名词对照表

[osu! 中文翻译 名词对照表](https://docs.google.com/spreadsheets/d/1zhUP0qekKRUWb1Mu-P89mwu_HcPBen5FoGPqD2MkI7k) 中包含了大部分专有名词的中文翻译，对需要使用原文的的名词作了规定，每个翻译者都应参照名词对照表，不应出现专有名词有多种翻译的情况。

## GitHub 贡献指南

### 分支命名规范

一个分支代表一篇翻译文章，分支命名请使用以下方式：

`zh-文章名-子文章名` 全英文小写字母，空格使用下划线替代，可以使用缩写

例如：
- `zh-legal`
- `zh-ranking_criteria`
- `zh-rc-taiko`

### Commit message 规范

- 不能包含中文。
- 最多 72 个英文字符，小写字母。
- 使用一般现在时，动宾短语结构，句尾不加标点。

请参照以下列出的 Commit message：
  - `<分支名称>: finish <某一部分>` 完成了文章的某一部分或者所有翻译
  - `<分支名称>: apply @<某人>'s reivews` 完成了某个审阅者建议的翻译修改

注意：如果 Commit message 太长，或者都是无意义的信息，将会在合并时被压缩（squash）。

### Pull request 规范

组织仓库中的 PR 标题和内容都没有特别的要求，中文英文均可，只要能清楚的表达意思就行。

官方仓库中的 PR 标题和内容请使用英文，按照一般的格式要求。

### 身份组说明

组织管理者会为每个贡献者设置适当的身份组，目前有 5 个身份组，分别是：

|:-----------|:-------|:-------------------------------------------------------|
| Name       | 名称   | 说明                                                   |
| Translator | 翻译者 | 曾经完成过一篇文章翻译的人                             |
| Reviewer   | 审阅者 | 帮助翻译者审阅文章的人                                 |
| Developer  | 开发者 | 开发和维护 osu! 相关项目的程序员                       |
| Observer   | 观察者 | 吃瓜群众                                               |
| Leader     | 组织者 | 组织者也是普通的翻译者和审阅者，只是付出的工作更多一些 |

各个身份组之间没有明显的界限划分，或许最大的作用是让组织频道里花花绿绿的很好看。（误

## 学习资源

针对想要学习新技能来帮助翻译工作的同学，我们特地列出一些有关于 Markdown 标记语言，GitHub 和 Git 的学习资源。

详情请参见 [学习资源](https://osu-translate-zh.github.io/2017/10/15/learning-resource)。

## 相关链接

[osu! 中文翻译 名词对照表](https://docs.google.com/spreadsheets/d/1zhUP0qekKRUWb1Mu-P89mwu_HcPBen5FoGPqD2MkI7k)

[osu!wiki 中文翻译 进度表](https://docs.google.com/spreadsheets/d/1zjXM0BAWA-bYDGcxPUlysO_G3IZcbsQJ9c8fv_7OOeY)

[osu!wiki 中文翻译 任务表](https://github.com/orgs/osu-translate-zh/projects/1)

[osu!wiki 翻译完成进度](https://github.com/osu-translate-zh/osu-wiki/issues/1)
