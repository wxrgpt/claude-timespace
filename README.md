# TimeScape · 时光印记

<div align="center">
  <img src="https://img.shields.io/badge/Version-1.0.0-blue.svg" alt="Version">
  <img src="https://img.shields.io/badge/License-MIT-green.svg" alt="License">
  <img src="https://img.shields.io/badge/Made%20with-HTML%2FCSS%2FJS-orange.svg" alt="Made with">
</div>

<div align="center">
  <h3>
    <a href="#english">English</a> |
    <a href="#中文">中文</a>
  </h3>
</div>
## 中文

### 🎯 概述

TimeScape（时光印记）是一个精美的时间可视化仪表板，通过多个维度展现时间的流逝。它将抽象的时间概念转化为直观的视觉呈现，帮助用户更好地感知和珍惜每一刻。

### ✨ 功能特点

- **多维度时间展示**：可视化显示当前小时、今天、本周、本月、本年的进度
- **实时更新**：每秒动态更新进度
- **可视化进度**：精美的进度条和网格系统
- **统计追踪**：实时在线人数统计和累计访问次数
- **响应式设计**：完美适配桌面和移动设备
- **优雅界面**：现代化的玻璃态设计和流畅动画

### 🚀 演示

[在线演示](https://claude-timespace.vercel.app/) | [截图预览](#截图)

### 🛠️ 技术栈

- 纯 HTML5、CSS3、JavaScript
- 无外部依赖
- LocalStorage 数据持久化
- CSS Grid 和 Flexbox 布局
- CSS 动画和过渡效果

### 📦 安装使用

1. 克隆仓库：
```bash
git clone https://github.com/yourusername/timescape.git
```

2. 在浏览器中打开 `index.html`

就这么简单！无需构建过程或依赖安装。

### 🎨 自定义配置

您可以轻松自定义 TimeScape：

- **出生年份**：修改 JavaScript 中的 `BIRTH_YEAR`
- **预期寿命**：调整 `LIFE_EXPECTANCY` 值
- **配色方案**：修改 CSS 变量来改变颜色
- **语言**：更新文本内容进行本地化


### 🔧 高级配置

#### WebSocket 实时统计（可选）

如果您需要更准确的在线人数统计，可以配置 WebSocket 服务器：

```javascript
// 服务端示例 (Node.js)
const WebSocket = require('ws');
const wss = new WebSocket.Server({ port: 8080 });

wss.on('connection', ws => {
    // 处理连接逻辑
});
```

#### 数据持久化

TimeScape 使用 LocalStorage 存储：
- 访问次数
- 活跃会话信息

### 🤝 贡献

欢迎贡献代码、提出问题和功能请求！请查看 [issues 页面](https://github.com/yourusername/timescape/issues)。

### 📝 开源协议

本项目采用 [MIT](LICENSE) 开源协议。

### 🙏 致谢

- 灵感来源于对时间流逝的思考
- 感谢所有贡献者的支持

---

## English

### 🎯 Overview

TimeScape is a beautiful time visualization dashboard that presents the passage of time through multiple dimensions. It transforms abstract time concepts into intuitive visual representations, helping users better perceive and cherish every moment.

### ✨ Features

- **Multi-dimensional Time Display**: Visualizes current hour, today, this week, this month, and this year
- **Real-time Updates**: Dynamic progress updates every second
- **Visual Progress**: Beautiful progress bars and grid systems
- **Statistics Tracking**: Real-time online users count and total visits tracking
- **Responsive Design**: Perfectly adapts to desktop and mobile devices
- **Elegant UI**: Modern glassmorphism design with smooth animations

### 🚀 Demo

[Live Demo](https://your-demo-link.com) | [Screenshots](#screenshots)

### 🛠️ Technologies

- Pure HTML5, CSS3, JavaScript
- No external dependencies
- LocalStorage for data persistence
- CSS Grid & Flexbox for layout
- CSS animations and transitions

### 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/timescape.git
```

2. Open `index.html` in your browser

That's it! No build process or dependencies required.

### 🎨 Customization

You can easily customize TimeScape by modifying:

- **Birth Year**: Change `BIRTH_YEAR` in the JavaScript section
- **Life Expectancy**: Adjust `LIFE_EXPECTANCY` value
- **Colors**: Modify CSS variables for different color schemes
- **Language**: Update text content for localization

### 📸 Screenshots

<div align="center">
  <img src="screenshots/hour-view.png" width="400" alt="Hour View">
  <img src="screenshots/month-view.png" width="400" alt="Month View">
</div>

### 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check [issues page](https://github.com/yourusername/timescape/issues).

### 📝 License

This project is [MIT](LICENSE) licensed.

---


<div align="center">
  Made with ❤️ by [Your Name]
</div>
