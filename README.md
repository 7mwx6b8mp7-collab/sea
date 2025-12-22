# Cream Template - 现代化网站模板

一个美观、现代、响应式的单页面网站模板，采用纯HTML、CSS和JavaScript开发。

## 功能特点

- ✨ **现代化设计** - 采用渐变色彩和流畅的动画效果
- 📱 **完全响应式** - 适配所有设备（桌面、平板、手机）
- 🎨 **优雅的UI/UX** - 精心设计的用户界面和交互体验
- ⚡ **高性能** - 轻量级代码，快速加载
- 🎯 **平滑滚动** - 流畅的页面导航体验
- 🌟 **动画效果** - 丰富的滚动动画和悬停效果

## 网站结构

- **首页 (Hero)** - 引人注目的欢迎区域
- **关于我们** - 介绍信息和统计数据
- **服务** - 展示提供的服务项目
- **作品集** - 项目展示和案例
- **联系我们** - 联系信息和表单

## 文件结构

```
.
├── index.html      # 主HTML文件
├── styles.css      # 样式文件
├── script.js       # JavaScript交互功能
└── README.md       # 项目说明文档
```

## 使用方法

1. 直接在浏览器中打开 `index.html` 文件即可查看网站
2. 或者使用本地服务器运行：
   ```bash
   # 使用Python
   python -m http.server 8000
   
   # 使用Node.js (需要安装http-server)
   npx http-server
   ```
3. 在浏览器中访问 `http://localhost:8000`

## 自定义

### 修改颜色主题

在 `styles.css` 文件的 `:root` 变量中修改颜色：

```css
:root {
    --primary-color: #6c5ce7;    /* 主色调 */
    --secondary-color: #a29bfe;  /* 次要颜色 */
    --accent-color: #fd79a8;     /* 强调色 */
}
```

### 修改内容

直接编辑 `index.html` 文件中的文本内容，包括：
- 导航菜单项
- Hero区域标题和描述
- 关于我们部分
- 服务项目
- 作品集项目
- 联系信息

### 添加图片

在作品集部分，可以将 `.portfolio-image` 的背景色替换为实际图片：

```css
.portfolio-image {
    background-image: url('your-image.jpg');
    background-size: cover;
    background-position: center;
}
```

## 浏览器支持

- Chrome (最新版本)
- Firefox (最新版本)
- Safari (最新版本)
- Edge (最新版本)

## 技术栈

- **HTML5** - 语义化标记
- **CSS3** - 现代样式和动画
- **JavaScript (ES6+)** - 交互功能
- **Font Awesome** - 图标库 (CDN)

## 许可证

本项目为开源项目，可自由使用和修改。

## 更新日志

### v1.0.0 (2024)
- 初始版本发布
- 完整的响应式设计
- 平滑滚动和动画效果
- 联系表单功能

## 贡献

欢迎提交问题和改进建议！

## 联系方式

如有任何问题或建议，请通过以下方式联系：
- 邮箱: contact@cream.com
- 网站: [Cream Template](https://example.com)

---

**享受使用 Cream Template！** 🎉




