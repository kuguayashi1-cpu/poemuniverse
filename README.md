# 🌠 诗意星空 - Poetry Converter

一个美丽的诗歌转换器，具有星空背景和漂浮文字效果。

## ✨ 功能特色

- 🌌 **动态星空背景** - 流动的星点粒子特效
- 📝 **中文文本输入** - 支持中文诗歌转换
- 🎭 **双结果展示** - 诗意转化结果 + 漂浮语言
- 📚 **历史记录** - 保存和查看转换历史
- 🎨 **总览页面** - 混合漂浮文字展示
- 🎪 **动画效果** - 使用 Framer Motion 实现流畅动画

## 🚀 快速开始

### 安装依赖

```bash
npm install
```

### 启动开发服务器

```bash
npm run dev
```

在浏览器中打开 [http://localhost:3000](http://localhost:3000) 查看应用。

### 构建生产版本

```bash
npm run build
npm start
```

## 🛠️ 技术栈

- **Next.js 14** - React 框架
- **TypeScript** - 类型安全
- **Tailwind CSS** - 样式框架
- **Framer Motion** - 动画库
- **React Particles** - 粒子效果

## 📁 项目结构

```
poetry-converter/
├── src/
│   ├── app/                 # Next.js App Router
│   │   ├── layout.tsx       # 根布局
│   │   └── page.tsx         # 首页
│   ├── components/          # React 组件
│   │   ├── Background.tsx   # 星空背景组件
│   │   ├── InputSection.tsx  # 输入区域组件
│   │   ├── OutputSection.tsx # 输出区域组件
│   │   └── HistoryPanel.tsx # 历史记录面板
│   ├── pages/               # 页面组件
│   │   ├── index.tsx        # 主界面
│   │   └── overview.tsx     # 总览界面
│   └── styles/
│       └── globals.css      # 全局样式
├── public/                  # 静态资源
├── package.json
├── tailwind.config.js
└── next.config.js
```

## 🎨 设计特色

### 色彩方案
- **宇宙蓝** (#0a0e27) - 主背景色
- **星空金** (#ffd700) - 强调色
- **星云紫** (#8b5cf6) - 辅助色
- **宇宙粉** (#ec4899) - 点缀色

### 动画效果
- 星空粒子流动
- 文字淡入淡出
- 按钮悬停效果
- 漂浮文字动画

## 🔧 自定义配置

### 修改颜色主题
编辑 `tailwind.config.js` 中的颜色配置：

```javascript
colors: {
  'cosmic-blue': '#0a0e27',
  'star-gold': '#ffd700',
  'nebula-purple': '#8b5cf6',
  'cosmic-pink': '#ec4899',
}
```

### 调整动画效果
修改 `src/styles/globals.css` 中的动画配置：

```css
@keyframes float {
  '0%, 100%': { transform: 'translateY(0px)' },
  '50%': { transform: 'translateY(-20px)' },
}
```

## 📱 响应式设计

应用完全响应式，支持：
- 桌面端 (1200px+)
- 平板端 (768px - 1199px)
- 移动端 (< 768px)

## 🌟 使用说明

1. **输入文本** - 在"故乡入口"区域输入中文文本
2. **生成诗歌** - 点击"生成诗歌"按钮开始转换
3. **查看结果** - 在双结果框中查看诗意转化和漂浮语言
4. **历史记录** - 点击右上角历史按钮查看过往记录
5. **总览展示** - 访问总览页面查看混合漂浮效果

## 🤝 贡献指南

欢迎提交 Issue 和 Pull Request！

## 📄 许可证

MIT License - 详见 [LICENSE](LICENSE) 文件

---

✨ 让诗意在星空中永恒 ✨
