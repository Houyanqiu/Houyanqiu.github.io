# 侯彦秋的个人网站搭建指南

![网站预览](/images/houyanqiu.jpg)

## 🚀 快速入门

### 第一步：基础配置
1. 用记事本打开 `_config.yml`
2. 修改以下基本信息：
```yaml
title: 侯彦秋的个人网站
description: 清华大学计算机系研究员 | 智能系统安全专家
baseurl: "" 
url: "https://houyanqiu.github.io"
```

### 第二步：内容管理
- 📝 **写博客**：在 `blogs/` 文件夹新建 `2025-03-05-标题.md`
- 📸 **换头像**：替换 `images/houyanqiu.jpg` 文件
- 🏆 **更新荣誉**：编辑 `awards.md` 文件

### 第三步：本地预览
```bash
# 首次运行需要安装依赖
bundle install

# 启动本地服务器
bundle exec jekyll serve
```
打开浏览器访问 http://localhost:4000

## 📂 核心文件说明
```
├── _config.yml       # 网站全局配置
├── _includes/        # 网页组件（头部/底部/导航栏）
├── blogs/            # 所有博客文章（Markdown格式）
├── images/           # 网站图片资源
├── mypaper/          # 学术论文存档
└── _layouts/         # 页面模板
```

## 🌐 网站部署
1. 将修改后的代码推送到GitHub仓库
2. 等待2分钟后访问：
   https://houyanqiu.github.io

## 💡 常用功能
1. 添加新页面：在根目录创建 `xxx.md` 文件
2. 修改导航菜单：编辑 `_config.yml` 的 navigation 部分
3. 调整网站样式：修改 `assets/css/main.css`

## 🆘 技术支持
遇到问题请检查：
1. 确保所有.yml文件使用UTF-8编码
2. 本地预览需要安装Ruby环境
3. 图片路径需使用 `/images/文件名` 格式

© 2024 侯彦秋 | 基于 [Jekyll](https://jekyllrb.com/) 构建 | [源码地址](https://github.com/Houyanqiu/Houyanqiu.github.io)
