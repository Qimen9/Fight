# Three Character Classic (TCC) - 喷神指数分析网站

## 项目简介

Three Character Classic (TCC) 是一个基于Web的娱乐性喷神指数分析工具，通过输入名字来分析用户的"喷神"潜质。网站采用黑红灰配色方案，具有科技感的波浪背景和全面圆角设计，为用户提供有趣的互动体验。

**注意：本网站仅用于娱乐目的，所有分析结果均为随机生成，不代表真实情况。**

## 功能特点

- 🌊 **科技感波浪背景** - 动态多层波浪效果营造深度感
- ⚡ **全面圆角设计** - 所有UI元素采用圆角设计，现代且友好
- 🔥 **高级动画效果** - 包含粒子效果、闪光动画和进度条动画
- 📊 **多维度分析** - 显示喷神指数、打字速度、攻击强度和防御能力
- 📱 **响应式设计** - 完美适配各种屏幕尺寸
- 🎮 **交互反馈** - 丰富的悬停和点击效果

## 技术栈

- **HTML5** - 页面结构和内容
- **CSS3** - 样式设计和动画效果
- **JavaScript** - 交互逻辑和动态效果
- **Google Fonts** - 使用Orbitron和Rajdhani字体

## 使用说明

1. 在输入框中输入您的名字
2. 点击"激活分析协议"按钮或按Enter键
3. 查看喷神指数分析结果
4. 探索各项统计数据和个性化评语

## 项目结构

```
tcc-website/
│
├── index.html          # 主页面文件
├── README.md           # 项目说明文档

## 自定义修改

### 颜色主题

修改CSS变量即可调整网站配色：
```css
:root {
    --main-bg: #0f0f15;        /* 主背景色 */
    --accent: #ff003c;         /* 强调色(红色) */
    --text-primary: #ffffff;   /* 主要文字颜色 */
    /* 更多颜色变量... */
}
```

### 圆角大小

调整圆角变量可改变UI元素的圆角程度：
```css
:root {
    --border-radius-sm: 8px;
    --border-radius-md: 16px;
    --border-radius-lg: 24px;
    --border-radius-xl: 32px;
    --border-radius-full: 50px;
}
```

### 动画效果

修改JavaScript中的`createAnalysisEffects()`和`createFinalEffect()`函数可以自定义动画效果。

## 浏览器兼容性

- Chrome (推荐)
- Firefox
- Safari
- Edge

## 部署方式

### 简单部署

直接将`index.html`文件放置在Web服务器目录中即可访问。

### GitHub Pages部署

1. Fork或上传项目到GitHub仓库
2. 进入仓库设置中的Pages选项
3. 选择部署分支和目录
4. 保存后等待部署完成

### Netlify部署

1. 将项目上传至Git仓库
2. 登录Netlify并选择"New site from Git"
3. 连接仓库并选择部署分支
4. 无需额外配置，自动部署

## 开发计划

- [ ] 添加更多分析维度
- [ ] 实现历史记录功能
- [ ] 增加分享功能
- [ ] 添加多语言支持
- [ ] 优化移动端体验

## 贡献指南

欢迎提交Issue和Pull Request来帮助改进这个项目。

1. Fork本项目
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启Pull Request

## 许可证

本项目采用MIT许可证，详见LICENSE文件。

## 免责声明

本网站仅用于娱乐目的，所有分析结果均为随机生成，不代表任何政治立场及非法意义，请勿将分析结果当真。

## 联系信息

如有问题或建议，请通过GitHub Issues提交反馈。

---

**Three Character Classic** - 探索您的网络喷神潜质 ✨
