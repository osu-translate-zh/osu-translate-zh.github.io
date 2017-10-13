# osu 中文翻译指南



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

### 重要说明

osu-wiki 有一套完整的[贡献指南](https://osu.ppy.sh/help/wiki/osu!wiki_contribution_guide)，包括**网页编辑**和**本地编辑**两种贡献翻译方式。

osu!中文翻译组织沿用了这样的贡献指南，但请注意有一个不同之处：

- 我们有自己的组织仓库（[osu-translate-zh/osu-wiki](https://github.com/osu-translate-zh/osu-wiki)），区别于官方的仓库（[ppy/osu-wiki](https://github.com/ppy/osu-wiki)）。
中文翻译工作会在**组织仓库中**进行，在组织内审阅完成后，以组织的名义上传（Pull Request）到官方仓库。

具体工作流程，请根据自己的情况阅读下面两篇指南：

- 如果你刚刚接触 Github，请阅读这篇[新手指南](https://osu-translate-zh.github.io/docs/beginner_guide)。

- 如果你能熟练地使用 Git，请阅读这篇[进阶指南](https://osu-translate-zh.github.io/docs/advance_guide)。

## 翻译指南

### 规则 Rules

<!-- WIP -->

### 文章风格指南 ASC

ASC 由 [@kj415j45](https://github.com/kj415j45) 负责翻译。目前 en 版本已完成，中文翻译正在进行中。

### 名词对照表

目前正在整理中，参见：

[osu! 中文翻译 名词对照表](https://docs.google.com/spreadsheets/d/1zhUP0qekKRUWb1Mu-P89mwu_HcPBen5FoGPqD2MkI7k)

## github 贡献指南

### Commit message 规范

请按照以下面的四个句子作为 Commit message：

1. `zh: init translation` 第一个 commit。

复制 `en.md` 并重命名为 `zh.md`。

2. `zh: 英文的文章标题` 完成了部分翻译。

可以重复使用多次这句 Commit message。但是，太多的话会被 Squash 成一次 Commit。

当某篇 Wiki 包含子页面时，请使用 `-` 符号连接，写上完整的标题。例如： `Ranking_Criteria - osu!catch`

3. `zh: apply reivews` 根据 review 修改一些翻译语句。

4. `zh: finish 英文的文章标题` 完成了所有翻译。

这句作为最后的 commit，也作为 merge commit。

### Pull request 规范

PR 命名和内容都没有特别的要求，中文英文均可，只要能清楚的表达意思就行。

## 相关链接

[osu! 中文翻译 名词对照表](https://docs.google.com/spreadsheets/d/1zhUP0qekKRUWb1Mu-P89mwu_HcPBen5FoGPqD2MkI7k)

[osu!wiki 中文翻译 进度表](https://docs.google.com/spreadsheets/d/1zjXM0BAWA-bYDGcxPUlysO_G3IZcbsQJ9c8fv_7OOeY)

[osu!wiki 中文翻译 任务表](https://github.com/orgs/osu-translate-zh/projects/1)

[osu!wiki 翻译完成进度](https://github.com/osu-translate-zh/osu-wiki/issues/1)
