# UI 用户界面键盘事件 key 属性值(UI Events KeyboardEvent key Values)

本仓库属于翻译参考，不具备规范一致性，下面都是对被fork的[源仓库](https://github.com/w3c/uievents-key)的`README.md`的翻译， 本仓库生成的非标准提案包含译者对原规范的理解，不属于规范文档，只能作为学习参考。 翻译链接如下

1. [UI 用户界面键盘事件 key 属性值](https://mangwu.github.io/uievents-key-cn/)
2. [实现报告](https://mangwu.github.io/uievents-key-cn/impl-report.html)

此fork仓库的源仓库用于编写  [UI Events key](https://w3c.github.io/uievents-key/) 规范。 

该规范还包含一份 [实现报告](https://w3c.github.io/uievents-key/impl-report.html)。

## 构建

此规范是使用 [bikeshed](https://github.com/tabatkins/bikeshed) 创建的。
如果您想贡献编辑，请确保您的更改能正确生成。

要**构建**此规范，请执行以下操作:

1. 将此仓库克隆到本地目录中。
1. 安装 [bikeshed](https://github.com/tabatkins/bikeshed)
1. 在本地目录中运行`python build.py`。

要编辑本规范，请执行以下操作:

1. 编辑 `index-source.txt` 文件。
2. 构建 (上面的构建操作)。构建成功后会创建 `index.bs` 和 `index.html` 文件.

提交 pull 请求时，请确保您的变更列表中没有包含 `index.bs` 文件——它是
`.gitignore` 的一部分，这样您就不会意外包含它。所有更改都应在
`index-source.txt`文件中进行。

要**更新实现报告**，请执行以下操作

1. 编辑 `impl-report.txt` 文件。
2. 构建 (上面的构建操作)。构建成功后会创建 `impl-report.bs` 和`impl-report.html` 文件。

与 `index.bs` 文件一样，请确保您没有拉入 `impl-port.bs` 文件。
它也列在 `.gitignore` 文件中。

## 阅读本规范的读者也阅读

* UI Events : [Github project](https://github.com/w3c/uievents/), [Link to spec](https://w3c.github.io/uievents/)
* UI Events KeyboardEvent code Values : [Github 项目](https://github.com/w3c/uievents-code/), [规范链接](https://w3c.github.io/uievents-code/)

# 合并记录

本节内容不属于fork仓库的内容，属于翻译项目基于源fork仓库更新后的异步合并记录。

需要注意的是，本翻译项目是从源仓库的 [Fix](https://github.com/w3c/uievents-key/commit/41ddcc2a2d42bde0935263dfe91a28eb7acbbc4f) [#54](https://github.com/w3c/uievents-key/issues/54)[: Add link to implementation report](https://github.com/w3c/uievents-key/commit/41ddcc2a2d42bde0935263dfe91a28eb7acbbc4f)  (41ddcc2a2d42bde0935263dfe91a28eb7acbbc4f)开始进行的，所以不会有之前(包括这次)的合并记录

| 源项目更新                                                   | 源项目更新的SHA码                         | 本项目更新的SHA码                         | 更新内容                                                     |
| ------------------------------------------------------------ | ----------------------------------------- | ----------------------------------------- | ------------------------------------------------------------ |
| [Fix](https://github.com/w3c/uievents-key/commit/d16781e35f6944bbd56f10003c42d3d0fac282d2) [#65](https://github.com/w3c/uievents-key/issues/65)[: Ref to MediaTrackNext and MediaTrackPrevious](https://github.com/w3c/uievents-key/commit/d16781e35f6944bbd56f10003c42d3d0fac282d2) | d16781e35f6944bbd56f 10003c42d3d0fac282d2 | c74f42ab5d9c917b6baa 38c677640566f8912cab | 媒体控制器按键中的 `MediaPreviousTrack` 和 `MediaNextTrack` 替换成 `MediaTrackPrevious` 和 `MediaTrackNext` |

