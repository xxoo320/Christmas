# 🌌 AI Gesture-Controlled Particle System | AI 手势控制炫彩粒子系统

[English](#english) | [中文](#中文)

---

## English

### 🔒 Privacy Statement

**This application is completely client-side and runs entirely in your browser.**

- ✅ **No server uploads**: All processing happens locally in your browser
- ✅ **No data collection**: Camera data is only used for real-time gesture recognition
- ✅ **No tracking**: No analytics, cookies, or tracking of any kind
- ✅ **No recording**: Camera feed is never saved or transmitted anywhere
- ✅ **Open source**: All code is transparent and auditable

Your privacy is 100% protected. The app uses your camera solely for local gesture detection via MediaPipe, and all particle rendering happens in your browser using Three.js.

---

### ✨ Features

- 🎨 **9 Dynamic Particle Shapes**: Galaxy, DNA Helix, Torus Knot, Heart, Saturn, Matrix Cube, Flower, Fireworks, Sphere
- 🌈 **5 Color Schemes**: Rainbow, Cyberpunk, Ocean, Fire, Forest
- 🤲 **AI Gesture Control**: Control particles with hand gestures using MediaPipe
- 🌐 **Bilingual Support**: Switch between Chinese and English
- 📱 **Mobile Responsive**: Optimized for both desktop and mobile devices
- ☁️ **Cloudflare Workers Ready**: One-click deployment to the edge

---

### 🚀 Quick Start

#### Option 1: Open Directly (Simplest)

Just open `index.html` in a modern browser. That's it!

#### Option 2: Deploy to Cloudflare Workers

1. **Install Wrangler** (Cloudflare's CLI tool):
   ```bash
   npm install -g wrangler
   ```

2. **Login to Cloudflare**:
   ```bash
   wrangler login
   ```

3. **Deploy with one command**:
   ```bash
   npm run deploy
   ```

Your app will be live on Cloudflare's global edge network! 🌍

#### Option 3: Local Development with Wrangler

```bash
npm install
npm run dev
```

Visit `http://localhost:8787` in your browser.

---

### 🎮 How to Use

1. **Allow camera access** when prompted (don't worry - it's 100% local!)
2. **Choose a shape** from the control panel
3. **Select a color scheme** that you like
4. **Control with gestures**:
   - Spread both hands apart to disperse particles
   - Open one hand with fingers spread to control dispersion
   - The wider you spread, the more dramatic the effect!
5. **Click language toggle** (🌐) to switch between languages
6. **Go fullscreen** for an immersive experience

---

### 🛠️ Technology Stack

- **Three.js** - 3D graphics and particle rendering
- **MediaPipe Hands** - Real-time hand tracking and gesture recognition
- **Cloudflare Workers** - Edge deployment for global low-latency access
- **Vanilla JavaScript** - No framework dependencies, pure performance

---

### 📱 Mobile Support

The interface automatically adapts to mobile devices:
- Collapsible control panel (tap ☰ to toggle)
- Optimized particle count for better performance
- Touch-friendly UI elements
- Responsive layout

---

### 🌍 Browser Compatibility

Works best on modern browsers that support:
- WebGL 2.0
- WebRTC (for camera access)
- ES6 Modules

Tested on: Chrome, Firefox, Edge, Safari (iOS 11+)

---

### 📄 License

MIT License - Feel free to use, modify, and distribute!

---

## 中文

### 🔒 隐私声明

**此应用完全在客户端运行，所有处理都在您的浏览器中完成。**

- ✅ **不上传服务器**: 所有处理都在浏览器本地进行
- ✅ **不收集数据**: 摄像头数据仅用于实时手势识别
- ✅ **不追踪用户**: 没有任何分析、Cookie 或跟踪
- ✅ **不录制视频**: 摄像头画面从不保存或传输
- ✅ **开源透明**: 所有代码公开可审计

您的隐私受到 100% 保护。应用仅通过 MediaPipe 在本地使用您的摄像头进行手势检测，所有粒子渲染都在浏览器中使用 Three.js 完成。

---

### ✨ 功能特点

- 🎨 **9种动态粒子形态**: 银河、DNA螺旋、环结、爱心、土星、矩阵立方、花朵、烟花、球体
- 🌈 **5种配色方案**: 幻彩霓虹、赛博朋克、深海幽蓝、烈焰熔岩、精灵森林
- 🤲 **AI手势控制**: 使用 MediaPipe 通过手势控制粒子
- 🌐 **双语支持**: 中英文自由切换
- 📱 **移动端适配**: 针对桌面和移动设备优化
- ☁️ **Cloudflare Workers 就绪**: 一键部署到边缘网络

---

### 🚀 快速开始

#### 方式一：直接打开（最简单）

在现代浏览器中直接打开 `index.html` 即可！

#### 方式二：部署到 Cloudflare Workers

1. **安装 Wrangler**（Cloudflare 的命令行工具）:
   ```bash
   npm install -g wrangler
   ```

2. **登录 Cloudflare**:
   ```bash
   wrangler login
   ```

3. **一键部署**:
   ```bash
   npm run deploy
   ```

您的应用将部署到 Cloudflare 的全球边缘网络！🌍

#### 方式三：使用 Wrangler 本地开发

```bash
npm install
npm run dev
```

在浏览器中访问 `http://localhost:8787`。

---

### 🎮 使用说明

1. **允许摄像头访问**（别担心 - 100% 本地运行！）
2. **选择形态** - 从控制面板选择您喜欢的粒子形态
3. **选择配色** - 选择您喜欢的颜色主题
4. **手势控制**:
   - 张开双手并拉开距离来分散粒子
   - 张开单手五指也可以控制分散效果
   - 张开得越大，效果越显著！
5. **切换语言** - 点击 🌐 按钮切换中英文
6. **全屏模式** - 获得沉浸式体验

---

### 🛠️ 技术栈

- **Three.js** - 3D 图形和粒子渲染
- **MediaPipe Hands** - 实时手部跟踪和手势识别
- **Cloudflare Workers** - 边缘部署，全球低延迟访问
- **原生 JavaScript** - 无框架依赖，纯粹性能

---

### 📱 移动端支持

界面自动适配移动设备：
- 可折叠控制面板（点击 ☰ 切换）
- 优化粒子数量以提升性能
- 触摸友好的 UI 元素
- 响应式布局

---

### 🌍 浏览器兼容性

在支持以下特性的现代浏览器上效果最佳：
- WebGL 2.0
- WebRTC（摄像头访问）
- ES6 模块

已测试：Chrome、Firefox、Edge、Safari（iOS 11+）

---

### 📄 许可证

MIT 许可证 - 欢迎自由使用、修改和分发！

---

### 🤝 Contributing

Contributions, issues, and feature requests are welcome!

---

### ⭐ Star Us!

If you like this project, please give it a star on GitHub!
