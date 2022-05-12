# cgcf 介绍

这个拓展可以让你复制git项目中有改动的部分，包含文件和文件夹

This extension allows you to copy the part of the project that has been changed, including files and folders.

## 环境

Windows，Git 项目

## 如何使用

打开侧边栏Source Control, 右键点击更改的文件，选择Copy Changes
或直接运行命令Copy Changes

状态栏中会提示复制的进度和结果，在成功后，会自动打开存储所有改动文件的临时文件夹

## 特性

复制git项目中改动的文件和文件夹 [✔]

支持windows [✔]

## 发布

vsce package

vsce publish

## 已知问题

只支持windows，其他环境没有测试

目前不能直接复制文件和文件夹到剪贴板，需要手动ctrl+a,ctrl+c复制到剪贴板，然后手动ctrl+v粘贴到目标位置

## 更新日志

### 0.0.1

1. 支持windows，可在git项目中，打开git，右键点击copy changes来打开包含所有改动的文件和文件夹，或使用Copy Changes命令直接执行。每次执行都会重新复制。

2. 关闭visual studio code后，自动清理临时文件夹

3. 状态栏显示进度

### 0.0.3

1. 修复临时文件夹可能无法清理的问题

### 0.0.4

1. 修复git changes文件过多会出错的问题

### 0.0.5

1. 更新提示方式