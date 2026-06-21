# 尺水丈安 · 智能水尺市场调研

基于AI视觉识别的水体智能监测系统调研网站。

## 项目简介

本项目是"尺水丈安"团队的智能水尺市场调研平台，包含：
- 在线调研问卷收集
- 2308份模拟调研报告展示
- 多维度数据分析图表

## 技术栈

- 纯前端实现：HTML + CSS + JavaScript
- 图表库：ECharts
- 部署方式：GitHub Pages

## 文件结构

```
smart-water-level-survey/
├── index.html          # 主页面（入口文件）
├── assets/
│   └── echarts.min.js  # ECharts图表库
└── README.md           # 项目说明
```

## 部署到 GitHub Pages

### 方法一：直接上传（推荐）

1. 在 GitHub 创建新仓库，命名为 `smart-water-level-survey`
2. 将本文件夹内所有文件上传到仓库根目录
3. 进入仓库 Settings -> Pages
4. Source 选择 "Deploy from a branch"
5. Branch 选择 "main"，文件夹选择 "/ (root)"
6. 点击 Save，等待几分钟即可访问

### 方法二：使用 Git 命令

```bash
# 初始化仓库
git init

# 添加所有文件
git add .

# 提交
git commit -m "Initial commit"

# 关联远程仓库（替换为你的仓库地址）
git remote add origin https://github.com/你的用户名/smart-water-level-survey.git

# 推送
git push -u origin main
```

## 访问地址

部署完成后，网站地址为：
```
https://你的用户名.github.io/smart-water-level-survey/
```

## 功能模块

1. **参与调研** - 8道选择题问卷，涵盖单位类型、监测方式、痛点、满意度等
2. **调研报告** - 2308份模拟报告，支持搜索、筛选、分页查看
3. **数据分析** - 6个维度的可视化图表（单位分布、监测方式、痛点、满意度、预算、趋势）

## 项目背景

本项目源于中国国际大学生创新大赛（红旅赛道），团队自主设计了具有螺旋纹结构的新型圆柱智能水尺，实现360°全方位可读，结合AI视觉识别算法，系统识别准确率≥96%，误差≤1cm。

---

**团队**：尺水丈安团队  
**院校**：湖北经济学院
