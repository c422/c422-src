**未完待续**

# 如何更新官网内容

本文档将介绍如何通过 Pull Request 的形式对官网进行更新。

## 写作规范

### 文字与排版

1. 中英文混排时，中英文之间需要有空格，例如：**Hello 世界**
1. 本模版的 markdown 文件开头的两个 `+++` 内部的内容，为 `toml` 格式的配置文件，这是 markdown 通用的添加配置文件的方案

### 图片使用

1. 如果需要使用图片，可以放置在 `static/img` 下，在引用时，可以通过 `/static/img/xxx.png` 这样的路径进行引用。

### 外部资源

1. 外部资源，如大型文件，请尽量保证放在能长期保存的地方，并且存留备份。

## 内容管理

### 成员（Member）

对应 `content/x/author/NAME` 中的文件。其中 `_index.md` 为个人基本信息，在配置时建议参考其他人的内容并认真阅读注释，在这里主要介绍关键字段：

- `user_group`: 当前工作室的成员，请在此处填写 `["Current Members"]`，指导教师请填写 `["Advising Professors"]`，往届成员请填写 `["Former"]`。这里的内容对应 `member.md` 中的 `user_groups` 的定义

### 成果（Accomplishment）

### 文章（Post）

## Git 操作

1. 推荐使用 [gitmoji](https://github.com/carloscuesta/gitmoji/) 工具来进行 commit，这样可以很好的添加直观的 commit message
