# 系统触摸键盘中文九宫格 (Windows 11 Touch Keyboard Chinese T9 / 12-Key)

[![Windhawk](https://img.shields.io/badge/Windhawk-Mod-blue.svg)](https://windhawk.net/)
[![Platform](https://img.shields.io/badge/Platform-Windows%2011%20(x64%20%7C%20ARM64)-brightgreen.svg)]()
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

在 Windows 11 系统触摸键盘中重新启用并完整接通原生微软拼音的十二键/九宫格（narrow12key）输入法。

## 功能特性
- **原生九宫格拼音输入**：短按按键正常产生中文汉字候选词，支持微软拼音完整的词库、联想与自学习。
- **长按纯数字候选**：长按九键按键时仅输出该数字候选，松手不产生二次输入。
- **数字面板直接输入**：切换到数字键盘时，数字直接上屏，不再弹出多余的拼音候选词。
- **原生表情符号面板唤起**：点击表情按钮及更多符号直接呼出与输入面板上方候选栏同款的原生 Windows 11 表情符号面板（支持表情、颜文字与全套 Unicode 符号），彻底避免跳转到空白占位界面。
- **稳定性与防闪退**：内置多层防御，自动拦截 Windows 11 在渲染狭窄九键及符号多页布局时的空指针与内部未适配断言，运行稳定流畅。

## 安装与使用
### 方法一：通过 Windhawk 官方模组库安装（推荐）
1. 在 [Windhawk](https://windhawk.net/) 中搜索 **系统触摸键盘中文九宫格** 或 `touch-keyboard-chinese-t9`；
2. 点击 **详情** 并点击 **安装**。

### 方法二：自定义模组安装
1. 打开 Windhawk，点击 **高级选项 -> 创建自定义模组**；
2. 将 [`touch-keyboard-chinese-t9.wh.cpp`](touch-keyboard-chinese-t9.wh.cpp) 的全部代码复制粘贴到编辑器中；
3. 点击 **保存并编译** 即可。

### 切换到九宫格布局
1. 确保当前输入法为 **中文（简体）- 微软拼音**；
2. 从任务栏唤起系统触摸键盘；
3. 点击键盘左上角的齿轮设置菜单 -> 键盘布局 -> 选择 **「十二键」** 即可畅享九宫格输入！

## 适用环境
- Windows 11 (x64 及 ARM64)
- 微软拼音输入法 (TSF3)
