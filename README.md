<div align="center">
  <h1>Qwen Browser</h1>
  <p>一个简洁、可配置的全局代理浏览器单页界面。</p>
</div>

<div align="center">

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](LICENSE)
![仓库大小](https://img.shields.io/github/repo-size/Detritalw/HTML-Browser?style=social&label=%E4%BB%93%E5%BA%93%E5%A4%A7%E5%B0%8F)
![星标数](https://img.shields.io/github/stars/Detritalw/HTML-Browser?style=social&label=%E6%98%9F%E6%A0%87)

</div>

## 项目简介

Qwen Browser 是一个基于原生 HTML、CSS 和 JavaScript 构建的浏览器界面原型，面向全局代理模式使用场景。项目无需构建工具和第三方依赖，下载后即可直接在现代浏览器中打开 `index.html`。

## 功能

- 多标签页管理
- 地址栏与页面导航
- 书签管理
- 深色 / 浅色 / 自动主题
- 蓝色、紫色、绿色、橙色、红色强调色
- 浏览历史与常用操作
- 响应式布局
- 原生 HTML / CSS / JavaScript，无需安装依赖

## 使用方式

### 直接打开

下载仓库后，使用现代浏览器打开：

```text
index.html
```

### 本地 HTTP 服务

也可以使用任意静态文件服务器运行，例如：

```bash
python -m http.server 8000
```

然后访问：

```text
http://localhost:8000/
```

## 项目结构

```text
HTML-Browser/
├── index.html   # 浏览器界面与交互逻辑
├── LICENSE      # GNU GPL v3.0 协议
└── README.md    # 项目说明
```

## 开发

本项目为纯静态页面。修改 `index.html` 后，刷新浏览器即可查看效果。提交前建议使用 Chromium、Firefox 或 Edge 测试主要交互和响应式布局。

## 贡献

欢迎提交 Issue 和 Pull Request：

1. Fork 本项目
2. 创建功能分支
3. 完成修改并测试
4. 提交 Pull Request

请在提交前保持代码清晰，并尽量避免引入不必要的外部依赖。

## 许可证

本项目采用 [GNU General Public License v3.0](LICENSE) 授权。

版权所有 © Detritalw

## 相关链接

- [Bloret Launcher](https://github.com/BloretCrew/Bloret-Launcher)
- [Bloret 官网](https://launcher.bloret.net/)
- [GitHub 仓库](https://github.com/Detritalw/HTML-Browser)
