# 这是一个富文本编辑器

## 前言
- 为了面试，弄个富文本编辑器玩玩，目标是简单、可扩展、架构清晰。

## 架构描述

### 渲染器

#### 功能
- 管理当前文字的状态
- 提供一个输入接口，输入改变状态的参数；处理过程可以交由一些插件去做；然后输出一个状态
- 根据状态去渲染你当前的文字

### 功能栏
#### 功能
- 展示可以选择的工具，为功能提供入口

### 插件管理