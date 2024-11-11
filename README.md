# 🥡Git 菜谱

> **Git菜谱** 是一套高质量的 Git 中文教程，源于国外社区的优秀文章和个人实践

> 本教程全部内容可参见[https://github.com/P2Tree/git-recipes](https://github.com/P2Tree/git-recipes)，我基于[Zhongyi Tong的工作](https://github.com/geeeeeeeeek/git-recipes)进行了重新整理和内容新增，由于作者已经关闭该项目，故重新建库。再次感谢原作者的辛勤劳动。

> **最新更新：已修改第2篇第1章：Git简易指南。2020年1月5日**

### 第1篇 果壳中的 Git

本篇介绍了一些Git的特点，以及与集中式版本管理系统的优缺点，阐述了什么是版本管理，什么是Git，为什么要用Git。

* **第1章** [什么是版本控制](sources/1.1-什么是版本控制.md)
* **第2章** [源代码管理](sources/1.2-源代码管理.md)
* **第3章** [什么是 Git](sources/1.3-什么是Git.md)
* **第4章** [为什么Git适合你的组织](sources/1.4-为什么Git适合你的组织.md)
* **第5章** [什么是SSH KEY](<sources/1.5-什么是SSH KEY.md>)

### 第2篇 从零搭建本地代码仓库

本篇完全面向入门者，我们会讨论如何在你的个人项目中使用 Git，比如如何初始化你的项目，如何管理新的或者已有的文件，如何在远端仓库中储存你的代码。

* **第1章** [Git简易指南](sources/2.1-Git简易指南.md)
* **第2章** [创建代码仓库](sources/2.2-创建代码仓库.md)
* **第3章** [保存你的更改](sources/2.3-保存你的更改.md)
* **第4章** [检查仓库状态](sources/2.4-查看仓库状态.md)
* **第5章** [检出之前的提交](sources/2.5-检出以前的提交.md)
* **第6章** [回滚错误的修改](sources/2.6-回滚错误的修改.md)
* **第7章** [重写项目历史](sources/2.7-重写项目历史.md)

### 第3篇 远程团队协作和管理

* **第1章** 快速指南
* **第2章** [保持同步](sources/3.2-保持代码同步.md)
* **第3章** [创建 Pull Request](sources/3.3-创建PullRequest.md)
* **第4章** [使用分支](sources/3.4-使用分支.md)
* **第5章** [常见工作流比较](sources/3.5-常见工作流比较.md)

### 第4篇 Git 命令详解

如果你稍微理解 Git 的工作原理，这篇文章能够让你理解的更透彻。

* **第1章** [图解 Git 命令](sources/4-Git图解.md)

### 第5篇 Git 实用贴士

*   **第1章** [代码合并：Merge、Rebase 的选择](sources/5.1-代码合并Merge还是Rebase.md)

    `git rebase` 和 `git merge` 都是用来合并分支，只不过方式不太相同。`git rebase` 经常被人认为是一种 Git 巫术，初学者应该避而远之。但如果使用得当，它能省去太多烦恼。在这篇文章中，我们会通过比较找到 Git 工作流中所有可以使用 rebase 的机会。
*   **第2章** [代码回滚：Reset、Checkout、Revert 的选择](sources/5.2-回滚命令Reset、Checkout、Revert辨析.md)

    git reset、git checkout 和 git revert 都是用来撤销代码仓库中的某些更改，所以我们经常弄混。在这篇文章中，我们比较最常见的用法，分析在什么场景下该用哪个命令。
*   **第3章** [Git log 高级用法](sources/5.3-Git\_log高级用法.md)

    任何一个版本控制系统设计的目的都是为了记录你代码的变化——谁贡献了什么，找出 bug 是什么时候引入的，以及撤回一些有问题的更改。`git log` 可以格式化 commit 输出的形式，或过滤输出的 commit 从而找到项目中你需要的任何信息。
*   **第4章** [Git 钩子：自定义你的工作流](sources/5.4-Git钩子.md)

    Git 钩子是在 Git 仓库中特定事件发生时自动运行的脚本。它可以让你自定义 Git 内部的行为，在开始周期中的关键点触发自定义的行为，自动化或者优化你开发工作流中任意部分。
*   **第5章** [Git 提交引用和引用日志](sources/5.5-Git提交引用.md)

    提交是 Git 的精髓所在，你无时不刻不在创建和缓存提交、查看以前的提交，或者用各种 Git 命令在仓库间转移你的提交。在这章中，我们研究提交的各种引用方式，以及涉及到的 Git 命令的工作原理。我们还会学到如何使用 Git 的引用日志查看看似已经删除的提交。

### 版权说明

* ✍️ [P2Tree (P2Tree@github)](https://github.com/P2Tree)
* 本文部分章节内容源自：[童仲毅 (geeeeeeeeek@github)](https://github.com/geeeeeeeeek)
* 除非另行注明，这个项目中的所有内容采用知识共享-署名（[CC BY 2.5 AU](http://creativecommons.org/licenses/by/2.5/au/deed.zh)）协议共享。
* 不少文章在原基础上翻译或演绎而来，页面上方标注了原作者、原文链接以及原文采用的协议。如有版权疑问，请在 Issue 中提出。
* 欢迎通过 Issue 或者 Pull Request 推荐你认为合适的资料，让这份菜单更充实一些。
