# 🎯 个人备考智能化管理系统 (Intelligent Exam Preparation Management System)

[![许可证：MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![语言：HTML/CSS/JS](https://img.shields.io/badge/Language-HTML%2FCSS%2FJS-blue.svg)]()
[![平台：网页](https://img.shields.io/badge/Platform-Web-brightgreen.svg)]()

一个轻量级、纯前端的**个人备考智能化管理系统**。专为多科目、高强度的期末考试或考研/证书备考设计。

系统无需配置繁琐的后端和数据库环境，完全基于本地浏览器运行，旨在帮助用户自主规划备考进度、细化知识点掌握情况，并通过可视化时间轴与精确倒计时提供沉浸式的备考管理体验。

---

## ✨ 核心功能

* **📚 课程自主管理**
    * 支持多科目的动态增删改查。
    * 自定义配置课程名称、考试时间、学分/权重等核心要素。
    * 实时计算并显示各科目的**精确考试倒计时**。
* **🧠 知识点与刷题板块**
    * 支持对单门科目下各章节、知识点进行颗粒度拆解。
    * 量化刷题进度（已刷题数/目标题数）与复习状态追踪。
    * 动态关联并更新单科及总体的**备考进度百分比**。
* **⏳ 可视化时间轴（Timeline）**
    * 根据各科目考试时间的先后顺序，自动生成动态备考时间轴。
    * 直观展现考试密集度，方便合理分配复习权重，避免多线卡点。
* **💾 零服务器数据备份（隐私安全）**
    * 数据完全本地化（基于 LocalStorage），提供数据编辑与清空功能。
    * 支持**一键导出 JSON 备份文件**，或从已有备份中导入，确保备考数据绝不丢失。

---

## 🛠️ 技术栈

* **前端核心**: HTML5 / CSS3 / Vanilla JavaScript (原生 JS)
* **布局与样式**: 现代响应式设计（完美适配 PC 端与平板），内置平滑过渡动画。
* **存储机制**: 浏览器本地存储 (LocalStorage) + JSON 文件导入/导出。

---

## 🚀 快速开始

### 方式一：本地运行

1. 克隆本项目到本地：
   ```bash
   git 克隆[https://github.com/JustPlayinger/Exam_Systerm.git](https://github.com/JustPlayinger/Exam_Systerm.git)

### 方式二：GitHub Pages 在线访问 (推荐)

本项目为纯前端结构，非常适合直接托管在 GitHub Pages 上供随时随地查阅：

前往你 GitHub 仓库的 Settings -> Pages。

在 Build and deployment 下选择 main 分支和 / (root) 目录。

点击 Save，等待 1-2 分钟即可通过 GitHub 提供的专属网址在线使用。

## 📂 项目结构

```明文
├── index.html        # 主页面结构与交互视图
├── css/
│   └── style.css     # 页面样式（包含仪表盘、时间轴及响应式布局）
├── js/
│   └── app.js        # 核心逻辑（数据状态管理、时间轴渲染、导入导出功能）
└── README.md         # 项目说明文档
```

## 💡 使用说明
添加课程：在管理面板输入课程信息。

细化备考：为课程添加具体的知识点或刷题记录，系统会自动根据完成度计算该科目的总体复习进度。

时间轴查阅：主页面的可视化时间轴会按时间由近到远排列，时刻提醒您复习的优先级。

数据备份：更换浏览器或设备前，点击“导出数据”保存 JSON 文件；在新设备上通过“导入数据”即可无缝恢复进度。

## 📄 开源协议
本项目基于 MIT License 协议开源。欢迎自由 Fork、修改和分发。
