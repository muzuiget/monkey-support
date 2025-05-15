# Wildmonkey

[English](./README.md)

## 设置

### 类型

支持两种类型：

* `页面样式` 执行 CSS 代码。
* `页面脚本` 执行 JavaScript 代码。

当选择 `无` 时，不执行代码，相当于草稿或禁用状态。

### 网址

自动执行代码的网址表达式。

格式为 [Match Patterns](https://developer.mozilla.org/zh-CN/docs/Mozilla/Add-ons/WebExtensions/Match_patterns)，即用 `*` 表示零个或多个字符，每行一个表达式。

但是添加了以下限制：

* 不支持特殊表达式 `<all_urls>`。
* `scheme` 仅能使用 `http` 和 `https`。

未匹配到任何网址时，在扩展弹出页面里显示为可点击按钮，点击按钮手动执行代码。

