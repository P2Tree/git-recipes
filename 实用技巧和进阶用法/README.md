# 实用技巧和进阶用法

本章节的内容会更进阶一些，可以选择感兴趣的部分阅读。但如果你想要完全掌握 Git，这些内容是必须要学习的。

- **第1章** [代码合并：Merge、Rebase 的选择](https://github.com/P2Tree/git-recipes/blob/master/sources/5.1-%E4%BB%A3%E7%A0%81%E5%90%88%E5%B9%B6Merge%E8%BF%98%E6%98%AFRebase.md)

  `git rebase` 和 `git merge` 都是用来合并分支，只不过方式不太相同。`git rebase` 经常被人认为是一种 Git 巫术，初学者应该避而远之。但如果使用得当，它能省去太多烦恼。在这篇文章中，我们会通过比较找到 Git 工作流中所有可以使用 rebase 的机会。

- **第2章** [代码回滚：Reset、Checkout、Revert 的选择](https://github.com/P2Tree/git-recipes/blob/master/sources/5.2-%E5%9B%9E%E6%BB%9A%E5%91%BD%E4%BB%A4Reset%E3%80%81Checkout%E3%80%81Revert%E8%BE%A8%E6%9E%90.md)

  git reset、git checkout 和 git revert 都是用来撤销代码仓库中的某些更改，所以我们经常弄混。在这篇文章中，我们比较最常见的用法，分析在什么场景下该用哪个命令。

- **第3章** [Git log 高级用法](https://github.com/P2Tree/git-recipes/blob/master/sources/5.3-Git_log%E9%AB%98%E7%BA%A7%E7%94%A8%E6%B3%95.md)

  任何一个版本控制系统设计的目的都是为了记录你代码的变化——谁贡献了什么，找出 bug 是什么时候引入的，以及撤回一些有问题的更改。`git log` 可以格式化 commit 输出的形式，或过滤输出的 commit 从而找到项目中你需要的任何信息。

- **第4章** [Git 钩子：自定义你的工作流](https://github.com/P2Tree/git-recipes/blob/master/sources/5.4-Git%E9%92%A9%E5%AD%90.md)

  Git 钩子是在 Git 仓库中特定事件发生时自动运行的脚本。它可以让你自定义 Git 内部的行为，在开始周期中的关键点触发自定义的行为，自动化或者优化你开发工作流中任意部分。

- **第5章** [Git 提交引用和引用日志](https://github.com/P2Tree/git-recipes/blob/master/sources/5.5-Git%E6%8F%90%E4%BA%A4%E5%BC%95%E7%94%A8.md)

  提交是 Git 的精髓所在，你无时不刻不在创建和缓存提交、查看以前的提交，或者用各种 Git 命令在仓库间转移你的提交。在这章中，我们研究提交的各种引用方式，以及涉及到的 Git 命令的工作原理。我们还会学到如何使用 Git 的引用日志查看看似已经删除的提交。
