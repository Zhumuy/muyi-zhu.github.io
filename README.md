# Personal Academic Website

一个现代化的个人学术网站模板，专为研究人员、学者和学术工作者设计。

## 🌟 特性

- **响应式设计** - 完美支持桌面端和移动端
- **现代化UI** - 使用最新的设计趋势和交互效果
- **卡片式布局** - Publications页面采用小卡片形式展示论文
- **完整导航** - Homepage, Publications, News, Design四个主要页面
- **交互功能** - 搜索、过滤、动画效果等
- **易于定制** - 模块化代码结构，便于修改和扩展

## 📁 文件结构

```
personal_website/
├── index.html              # 主页
├── publications.html        # 论文页面
├── news.html               # 新闻页面
├── design.html             # 设计作品页面
├── css/
│   └── style.css          # 主样式文件
├── js/
│   ├── main.js            # 主要JavaScript功能
│   └── publications.js    # 论文页面专用功能
├── images/                 # 图片文件夹（需要创建）
└── README.md              # 说明文档
```

## 🚀 快速开始

### 1. 本地预览

直接在浏览器中打开 `index.html` 文件即可预览网站。

### 2. 自定义内容

#### 个人信息
- 修改所有HTML文件中的 "Your Name" 为你的真实姓名
- 更新联系信息（邮箱、地址、社交媒体链接）
- 修改研究领域和专长标签

#### 论文信息
编辑 `publications.html` 文件：
- 替换示例论文为你的真实论文
- 更新论文标题、作者、期刊、摘要等信息
- 添加DOI链接和PDF下载链接
- 更新引用次数和下载次数

#### 新闻和事件
编辑 `news.html` 文件：
- 添加你的学术新闻和更新
- 更新即将到来的事件信息
- 添加真实的图片（放在 `images/news/` 文件夹中）

#### 设计作品
编辑 `design.html` 文件：
- 添加你的设计作品和项目
- 上传项目截图（放在 `images/portfolio/` 文件夹中）
- 描述使用的技术和工具

### 3. 图片准备

创建以下文件夹并添加相应图片：
```
images/
├── news/           # 新闻图片
├── portfolio/      # 作品集图片
└── profile/        # 个人照片
```

## 🎨 自定义样式

### 颜色主题
在 `css/style.css` 中修改CSS变量来改变网站配色：

```css
/* 主要颜色 */
--primary-color: #3498db;
--secondary-color: #2c3e50;
--accent-color: #667eea;
```

### 字体
网站使用Inter字体，可以在CSS中修改：

```css
body {
    font-family: 'Your-Font', -apple-system, BlinkMacSystemFont, sans-serif;
}
```

## 📱 响应式设计

网站已经针对不同设备进行了优化：
- **桌面端** (>1200px) - 完整布局
- **平板端** (768px-1200px) - 适配中等屏幕
- **移动端** (<768px) - 移动优先设计

## 🔧 技术特性

- **HTML5** - 语义化标记
- **CSS3** - 现代CSS特性（Grid, Flexbox, 动画）
- **JavaScript ES6+** - 现代JavaScript功能
- **Font Awesome** - 图标库
- **Google Fonts** - 高质量字体

## 📊 部署到GitHub Pages

### 1. 创建GitHub仓库
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/yourusername/your-repo-name.git
git push -u origin main
```

### 2. 启用GitHub Pages
- 进入仓库设置
- 找到 "Pages" 选项
- 选择 "Deploy from a branch"
- 选择 "main" 分支和 "/ (root)" 文件夹
- 保存设置

### 3. 访问你的网站
你的网站将在 `https://yourusername.github.io/your-repo-name` 上线

## 🎯 功能说明

### 主页 (index.html)
- 个人介绍和专长展示
- 统计数据展示
- 精选论文展示
- 联系信息

### 论文页面 (publications.html)
- 卡片式论文展示
- 按年份和类型过滤
- 搜索功能
- 引用信息展示

### 新闻页面 (news.html)
- 时间线式新闻展示
- 特色新闻
- 即将到来的事件

### 设计页面 (design.html)
- 作品集展示
- 项目分类
- 技术栈展示

## 🔍 高级功能

### 搜索和过滤
- 实时搜索论文标题、作者、摘要
- 按年份和类型过滤
- 搜索结果计数

### 交互效果
- 滚动动画
- 悬停效果
- 平滑过渡
- 移动端手势支持

### 性能优化
- 图片懒加载
- CSS和JavaScript压缩
- 响应式图片
- 缓存策略

## 🛠️ 故障排除

### 常见问题

1. **图片不显示**
   - 检查图片路径是否正确
   - 确保图片文件存在
   - 检查文件权限

2. **样式不生效**
   - 检查CSS文件路径
   - 清除浏览器缓存
   - 检查CSS语法错误

3. **JavaScript功能不工作**
   - 检查浏览器控制台错误
   - 确保JavaScript文件正确加载
   - 检查HTML元素ID是否匹配

## 📝 更新日志

### v1.0.0 (2024-12-19)
- 初始版本发布
- 完整的四页面结构
- 响应式设计
- 基础交互功能

## 🤝 贡献

欢迎提交Issue和Pull Request来改进这个模板！

## 📄 许可证

MIT License - 可自由使用和修改

## 📞 支持

如果你在使用过程中遇到问题，请：
1. 检查README文档
2. 查看代码注释
3. 提交GitHub Issue

---

**祝你学术网站建设顺利！** 🎓✨
