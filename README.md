# HTML5 在线摄像头

> 基于 HTML5 getUserMedia 的浏览器摄像头取景工具，可本地抓拍摄像头画面。

在线体验：https://wangchenyu.com/gongju/camera/

## 功能特性

- 调用桌面/移动设备摄像头
- Canvas 本地抓帧拍照
- 纯本地处理，不传输画面

## 使用方法

1. 用浏览器直接打开 `index.html`，无需安装任何软件、无需构建、无需后端服务。
2. 所有计算与处理均在浏览器本地完成，数据不会上传到服务器。
3. 处理完成后使用页面上的复制 / 导出按钮即可保存结果。

## 技术栈

HTML5 getUserMedia + Canvas + JavaScript

## 目录结构

```
├── index.html        # 主页面
├── assets/ 或本地资源 # 样式、脚本与静态资源（按需）
```

## 致谢

感谢上游开源社区提供的基础能力。

## 说明

本项目由 [wangchenyu.com](https://wangchenyu.com/) 整理并开源，仅供学习与个人使用。
