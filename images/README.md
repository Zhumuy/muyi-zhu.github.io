# 图片文件夹说明

这个文件夹用于存放网站所需的所有图片文件。

## 文件夹结构

```
images/
├── muyi.png                    # 个人照片 (主页右侧显示)
├── schools/                    # 学校图标文件夹
│   ├── hku.png               # 香港大学图标
│   └── bjfu.png              # 北京林业大学图标
├── publications/              # 论文相关图片文件夹
│   ├── paper1.png            # 论文1的配图
│   ├── paper2.png            # 论文2的配图
│   └── ...                   # 其他论文配图
├── design/                    # 设计作品图片文件夹
│   ├── urban_heat.png        # 城市热岛分析图片
│   ├── transport_network.png # 交通网络映射图片
│   ├── air_quality.png       # 空气质量监测仪表板图片
│   ├── smart_city.png        # 智慧城市基础设施图片
│   ├── population_density.png # 人口密度分析图片
│   └── green_space.png       # 绿地评估图片
└── pdfs/                     # PDF文件文件夹
    ├── paper1.pdf            # 论文1的PDF文件
    ├── paper2.pdf            # 论文2的PDF文件
    └── ...                   # 其他论文PDF文件
```

## 图片要求

### 个人照片 (muyi.png)
- 尺寸：建议 400x400 像素或更高
- 格式：PNG 或 JPG
- 内容：个人正面照片，专业形象

### 学校图标 (schools/)
- 尺寸：建议 80x80 像素
- 格式：PNG（支持透明背景）
- 内容：学校官方logo或图标

### 论文配图 (publications/)
- 尺寸：建议 300x200 像素
- 格式：PNG 或 JPG
- 内容：论文相关的图表、截图或示意图

### 设计作品图片 (design/)
- 尺寸：建议 400x300 像素
- 格式：PNG 或 JPG
- 内容：设计项目的截图、效果图或示意图

### PDF文件 (pdfs/)
- 格式：PDF
- 内容：论文的完整PDF版本

## 使用方法

1. **个人照片**：将你的照片命名为 `muyi.png` 并放在 `images/` 根目录下
2. **学校图标**：将学校图标放在 `schools/` 文件夹中，并在HTML中引用
3. **论文配图**：将论文配图放在 `publications/` 文件夹中，并在publication卡片中显示
4. **设计作品图片**：将设计作品图片放在 `design/` 文件夹中，替换portfolio中的占位符
5. **PDF文件**：将论文PDF放在 `pdfs/` 文件夹中，并更新[paper]按钮的链接

## 注意事项

- 所有图片文件大小建议控制在 1MB 以内
- 使用有意义的文件名，便于管理
- 确保图片版权合规
- 定期优化图片大小以提高网站加载速度
