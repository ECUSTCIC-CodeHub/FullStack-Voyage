# FullStack-Voyage
全栈开发培训教程平台

## 项目简介 / Project Introduction

**FullStack-Voyage** 是一个由计算机信息交流协会 (CIC) 开发的全栈开发培训教程平台。该项目旨在为学习者提供系统化的全栈开发知识，通过互动式文档网站展示各类技术教程和示例。

**FullStack-Voyage** is a full-stack development training tutorial platform developed by the Computer Information Exchange Association (CIC). This project aims to provide learners with systematic full-stack development knowledge, showcasing various technical tutorials and examples through an interactive documentation website.

## 技术栈 / Technology Stack

### 前端 / Frontend
- **Vue 3**：渐进式 JavaScript 框架
- **VuePress**：静态网站生成器
- **VuePress Theme Plume**：现代化的 VuePress 主题
- **TypeScript**：类型安全的 JavaScript 超集

- **Vue 3**: Progressive JavaScript framework
- **VuePress**: Static site generator
- **VuePress Theme Plume**: Modern VuePress theme
- **TypeScript**: Type-safe JavaScript superset

### 功能增强 / Feature Enhancement
- **Shiki TwoSlash**：代码高亮和交互式代码示例
- **Chart.js/ECharts**：数据可视化
- **Mermaid**：流程图和图表生成
- **Flowchart.ts**：交互式流程图
- **Pyodide**：WebAssembly 版 Python，支持在线 Python 代码执行

- **Shiki TwoSlash**: Code highlighting and interactive code examples
- **Chart.js/ECharts**: Data visualization
- **Mermaid**: Flowchart and diagram generation
- **Flowchart.ts**: Interactive flowcharts
- **Pyodide**: WebAssembly version of Python, supporting online Python code execution

## 快速开始 / Quick Start

### 环境要求 / Environment Requirements
- Node.js: ^20.6.0 || >=22.0.0
- pnpm: 推荐使用 pnpm 作为包管理器
- pnpm: Recommended package manager

### 安装 / Installation
```bash
pnpm install
```

### 开发 / Development
```bash
# 启动开发服务器
pnpm docs:dev

# 启动开发服务器（清除缓存和临时文件）
pnpm docs:dev-clean

# Start development server
pnpm docs:dev

# Start development server (clear cache and temporary files)
pnpm docs:dev-clean
```

### 构建和预览 / Build and Preview
```bash
# 构建生产版本
pnpm docs:build

# 本地预览生产构建
pnpm docs:preview

# 更新 VuePress 和主题
pnpm vp-update

# Build for production
pnpm docs:build

# Preview production build locally
pnpm docs:preview

# Update VuePress and theme
pnpm vp-update
```

## 项目结构 / Project Structure

```
docs/
├── .vuepress/         # VuePress 配置目录
│   ├── config.ts      # 主配置文件
│   ├── navbar.ts      # 导航栏配置
│   ├── collections.ts # 内容集合配置
│   ├── theme/         # 自定义主题配置
│   └── public/        # 静态资源
├── course/            # 课程内容
│   ├── README.md      # 课程首页
│   ├── 0.md-4.md      # 课程章节
├── blog/              # 博客内容
├── post/              # 文章内容
└── README.md          # 网站首页
```

```
docs/
├── .vuepress/         # VuePress configuration directory
│   ├── config.ts      # Main configuration file
│   ├── navbar.ts      # Navigation bar configuration
│   ├── collections.ts # Content collections configuration
│   ├── theme/         # Custom theme configuration
│   └── public/        # Static assets
├── course/            # Course content
│   ├── README.md      # Course homepage
│   ├── 0.md-4.md      # Course chapters
├── blog/              # Blog content
├── post/              # Article content
└── README.md          # Website homepage
```

## 主要功能 / Main Features

- **结构化课程**：系统化的全栈开发学习路径
- **交互式代码示例**：支持多种编程语言的代码运行和演示
- **数据可视化教程**：使用 Chart.js 和 ECharts 进行数据展示
- **流程图生成**：使用 Mermaid 和 Flowchart.ts 创建各类图表
- **响应式设计**：适配各种屏幕尺寸的设备

- **Structured Courses**: Systematic full-stack development learning path
- **Interactive Code Examples**: Support for running and demonstrating code in multiple programming languages
- **Data Visualization Tutorials**: Data display using Chart.js and ECharts
- **Flowchart Generation**: Create various diagrams using Mermaid and Flowchart.ts
- **Responsive Design**: Adapt to devices of various screen sizes

## 部署到 GitHub Pages / Deploy to GitHub Pages

该项目已配置 GitHub Actions 自动部署：

This project has been configured with GitHub Actions for automatic deployment:

1. 在 GitHub 仓库设置中：
   - 开启 Actions 读写权限
   - 配置 Pages 从 gh-pages 分支部署

1. In GitHub repository settings:
   - Enable Actions read and write permissions
   - Configure Pages to deploy from the gh-pages branch

2. 根据需要修改`docs/.vuepress/config.ts`中的`base`选项

2. Modify the `base` option in `docs/.vuepress/config.ts` as needed

## 贡献指南 / Contribution Guidelines

欢迎对项目进行贡献！请按照以下步骤：

Contributions to the project are welcome! Please follow these steps:

1. Fork 项目仓库
2. 创建特性分支
3. 提交更改
4. 推送到分支
5. 发起 Pull Request

1. Fork the project repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Submit a Pull Request

## 许可证 / License

本项目采用 MIT 许可证。详情请查看 LICENSE 文件。

This project is licensed under the MIT License. See the LICENSE file for details.

## 联系方式 / Contact

项目维护者：XuChenXu
GitHub：https://github.com/ChenXu233

Project Maintainer: XuChenXu
GitHub: https://github.com/ChenXu233

---

*全栈开发的旅程，从这里开始！*
*The journey of full-stack development starts here!*