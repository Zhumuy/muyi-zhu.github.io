# Design Projects 文件夹

这个文件夹包含了设计作品集的项目详情页面。

## 文件结构

```
design-projects/
├── README.md                           # 本说明文件
├── eco-waterfront.html                 # Eco-Waterfront 项目详情页
├── post-industrial-renaissance.html    # Post-industrial Renaissance 项目详情页
├── elder-friendly-tod.html            # Elder-friendly Transit Oriented Development 项目详情页
└── urban-green-network.html           # Urban Green Network Reconnection 项目详情页
```

## 项目详情页功能

每个项目详情页都包含：

1. **导航栏** - 与主站一致的导航，包含返回设计作品集的链接
2. **项目标题** - 项目名称和描述
3. **项目日期** - 完成时间
4. **项目概述** - 项目背景和关键特性
5. **项目画廊** - 展示项目各个阶段的图片
6. **响应式设计** - 适配各种屏幕尺寸

## 图片要求

每个项目需要以下图片文件：

- `cover.png` - 项目封面图片 (400x300px)
- `image1.png` - 项目图片1
- `image2.png` - 项目图片2
- `image3.png` - 项目图片3
- `image4.png` - 项目图片4
- `image5.png` - 项目图片5
- `image6.png` - 项目图片6

## 使用方法

1. 用户在主站的Design页面点击项目卡片
2. 自动跳转到对应的项目详情页
3. 在项目详情页可以查看完整的项目信息和图片画廊
4. 通过"Back to Design Portfolio"链接返回主设计页面

## 技术特点

- **响应式设计**: 使用CSS Grid和Flexbox布局
- **图片优化**: 支持图片加载失败时的占位符显示
- **交互效果**: 图片悬停效果和卡片动画
- **导航一致性**: 与主站保持一致的导航体验

## 注意事项

- 确保所有图片文件都放在正确的项目子文件夹中
- 图片文件名必须与HTML代码中的引用完全一致
- 建议使用PNG格式以保持图片质量
- 如果图片文件不存在，页面会显示占位符图标
