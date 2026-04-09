# 傅欣梅个人课程页面

## 项目介绍
这是一个纯静态的个人课程展示页面，用于展示傅欣梅老师的个人信息和课程信息。

**GitHub仓库**: https://github.com/7fxm/Fxm.git

## 功能特点
- 个人信息展示：包含姓名、学校、专业和个人简介
- 课程列表：展示Python基础、数据分析技术、数据采集与处理、供应链数据分析、数据库原理与应用等课程
- 响应式设计：适配桌面端和移动端
- 美观的界面：现代设计风格，包含动画效果

## 部署到Cloudflare Pages

### 步骤1：准备文件
确保你的项目包含以下文件：
- `index.html` - 主页面
- `README.md` - 项目说明（可选）

### 步骤2：部署到Cloudflare Pages
1. 登录 [Cloudflare Dashboard](https://dash.cloudflare.com/)
2. 选择 "Pages" 选项
3. 点击 "Create a project"
4. 选择 "Connect to Git" 或 "Direct Upload"
   - **Git 方式**：连接你的GitHub/GitLab仓库
   - **直接上传**：选择项目文件夹直接上传
5. 配置部署设置：
   - 构建命令：留空（静态网站不需要构建）
   - 构建输出目录：留空（使用根目录）
6. 点击 "Deploy site"
7. 等待部署完成，获取部署后的URL

## 后续开发

### 添加课程详情页面
1. 在项目根目录创建 `courses` 文件夹
2. 为每个课程创建对应的HTML文件，例如：
   - `courses/python-basics.html` - Python基础课程页面
   - `courses/data-analysis.html` - 数据分析技术课程页面
   - `courses/data-collection.html` - 数据采集与处理课程页面
   - `courses/supply-chain.html` - 供应链数据分析课程页面
   - `courses/database.html` - 数据库原理与应用课程页面

3. 更新 `index.html` 中的课程链接，指向对应的详情页面

### 自定义内容
- 修改 `index.html` 中的个人信息和课程描述
- 替换个人照片（修改 `<img>` 标签的 `src` 属性）
- 调整颜色方案（修改CSS中的 `:root` 变量）

## 技术栈
- HTML5
- CSS3
- JavaScript
- Google Fonts (Inter)