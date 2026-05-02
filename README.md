# 个人项目作品集网页

这是一个现代化的个人项目展示网页，适合部署到 GitHub Pages。

## 📁 文件结构

```
├── index.html          # 主页面文件
├── styles.css          # 样式表
├── script.js           # JavaScript 交互脚本
└── README.md          # 项目说明文档
```

## 🎯 功能特性

- ✅ 响应式设计 - 完美适配桌面、平板和手机
- ✅ 现代化界面 - 简洁优雅的设计风格
- ✅ 平滑动画 - 交互动画增强用户体验
- ✅ 项目展示 - 网格布局展示你的项目
- ✅ 联系方式 - 多种联系方式集成
- ✅ 易于定制 - 清晰的代码结构，易于修改

## 🚀 如何使用

### 1. 本地预览

直接在浏览器中打开 `index.html` 文件即可预览。

### 2. 部署到 GitHub Pages

#### 方式一：使用现有仓库
1. 将所有文件上传到你的 GitHub 仓库
2. 在仓库设置中启用 GitHub Pages
3. 选择 `main` 或 `master` 分支作为源
4. 你的网站将在 `https://yourusername.github.io/repo-name` 发布

#### 方式二：创建个人网站仓库
1. 在 GitHub 创建一个名为 `yourusername.github.io` 的仓库
2. 将所有文件上传到该仓库
3. 你的网站将在 `https://yourusername.github.io` 发布

## 📝 自定义内容

### 修改基本信息
在 `index.html` 中修改以下内容：

- **网站标题**：修改 `<title>` 标签
- **Logo 文字**：修改 `.logo` 元素
- **个人简介**：修改 About 部分的文本
- **邮箱和社交链接**：修改 Contact 部分的链接

### 添加项目
1. 复制项目卡片 HTML：
```html
<div class="project-card">
    <img src="项目截图链接" alt="项目名">
    <h3>项目名称</h3>
    <p>项目描述</p>
    <div class="project-tags">
        <span class="tag">技术1</span>
        <span class="tag">技术2</span>
    </div>
    <a href="项目链接" class="project-link">查看项目 →</a>
</div>
```

2. 修改相应的内容

### 更换颜色主题
在 `styles.css` 中修改 `:root` 下的变量：
```css
:root {
    --primary-color: #3498db;    /* 主色调 */
    --secondary-color: #2c3e50;  /* 次色调 */
    --accent-color: #e74c3c;     /* 强调色 */
}
```

### 更换字体
修改 `styles.css` 中的 `body` 字体设置：
```css
body {
    font-family: 'Your Font Family', sans-serif;
}
```

## 🎨 设计说明

- **配色方案**：专业的蓝色和灰色搭配
- **字体**：使用系统字体确保兼容性
- **响应式**：使用 CSS Grid 和 Flexbox 实现
- **性能**：轻量级框架，快速加载

## 📱 浏览器兼容性

- Chrome（最新版本）
- Firefox（最新版本）
- Safari（最新版本）
- Edge（最新版本）

## 💡 建议

1. **使用高质量项目截图** - 提高视觉吸引力
2. **定期更新内容** - 添加新项目和成就
3. **优化 SEO** - 添加更多的 meta 标签和描述
4. **添加中英文版本** - 扩大受众范围
5. **使用自定义域名** - 更专业的网址

## 🔗 有用的资源

- [GitHub Pages 官方文档](https://pages.github.com/)
- [Markdown 语法](https://guides.github.com/features/mastering-markdown/)
- [CSS Tricks](https://css-tricks.com/)

## 📄 许可证

自由使用和修改

---

**祝你的作品集展示顺利！** 🎉
