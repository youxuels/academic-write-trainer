<div align="center">

# AcademicWrite Trainer

**学术写作逻辑训练工具 | Academic Writing Logic Trainer**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](#contributing)

[🇨🇳 中文](#-中文说明) | [🇬🇧 English](#-english-readme)

</div>

---

## 🇨🇳 中文说明

### 🎯 这是什么？

AcademicWrite Trainer 是一个**免费开源的学术写作逻辑训练工具**。它从顶刊论文中提取摘要、引言、文献综述等部分，拆分为独立句子并打乱顺序，让你通过排序还原原文，从而内化学术写作的论证结构。

> **核心理念**：不是教你"写什么"，而是训练你"怎么组织"。

### ✨ 功能特性

| 功能 | 说明 |
|------|------|
| 📑 **论文章节分区** | 按摘要 / 引言 / 文献综述分区训练，只提取写作逻辑最关键的部分 |
| 📄 **多论文支持** | 内置示例论文 + 上传 PDF / 粘贴文本自动提取 |
| 🎚️ **三级难度** | 句子级 → 段落级 → 章节级，渐进式学习 |
| 🏷️ **修辞功能标注** | 每句标注：问题提出 / 文献回顾 / 研究缺口 / 研究目标 / 方法概述 / 逻辑过渡 |
| 📊 **逻辑分析报告** | 修辞类别准确率、排序模式对比、个性化写作建议 |
| ⏱️ **计时与排行** | 实时计时 + 历史最佳记录 + 练习历史 |
| 💡 **智能提示** | 渐进式提示下一句，不是直接给答案 |
| 📱 **响应式设计** | 支持桌面和移动端 |

### 🚀 快速开始

**在线使用**：直接访问 [GitHub Pages 地址](https://youxuels.github.io/academic-write-trainer/)

**本地运行**：
```bash
git clone https://github.com/youxuels/academic-write-trainer.git
cd academic-write-trainer
# 用任意方式打开 index.html，例如：
python -m http.server 8080
# 然后访问 http://localhost:8080
```

### 📖 使用方法

1. **选择论文**：从论文库选择内置论文，或上传自己的 PDF
2. **选择章节**：切换摘要 / 引言 / 文献综述进行训练
3. **选择难度**：句子级（最精细）→ 段落级 → 章节级（最宏观）
4. **点击排序**：点击左侧待选区的句子，按你认为的正确顺序添加到右侧
5. **检查结果**：点击"检查"查看正确率，绿色=正确，红色=错误
6. **查看报告**：点击"分析报告"获取逻辑偏好分析和写作建议

### 🏷️ 修辞功能标签

| 标签 | 含义 | 典型位置 |
|------|------|---------|
| ❓ 问题提出 | 提出研究问题或现实关切 | 引言开头 |
| 📚 文献回顾 | 引用前人研究 | 引言中段 |
| 🔍 研究缺口 | 指出已有研究的不足 | 文献回顾之后 |
| 🎯 研究目标 | 阐明本文的研究目的 | 缺口之后 |
| 🔬 方法概述 | 介绍研究方法和实验设计 | 引言末尾 |
| 🔗 逻辑过渡 | 连接上下文的过渡句 | 章节衔接处 |

### 🤝 参与贡献

欢迎通过以下方式参与：
- 🌟 Star 本项目
- 📝 提交 Issue 反馈问题或建议
- 🔧 提交 Pull Request 贡献代码
- 📄 贡献更多内置论文数据

---

## 🇬🇧 English Readme

### 🎯 What is this?

AcademicWrite Trainer is a **free, open-source academic writing logic training tool**. It extracts Abstract, Introduction, and Literature Review sections from top-journal papers, splits them into individual sentences, shuffles the order, and challenges you to reconstruct the original sequence — thereby internalizing the argumentative structure of academic writing.

> **Core idea**: Not teaching you "what to write", but training you "how to organize".

### ✨ Features

| Feature | Description |
|---------|-------------|
| 📑 **Section-based training** | Train by Abstract / Introduction / Literature Review — the most critical sections for writing logic |
| 📄 **Multi-paper support** | Built-in sample papers + upload PDF / paste text with auto-extraction |
| 🎚️ **Three difficulty levels** | Sentence-level → Paragraph-level → Section-level, progressive learning |
| 🏷️ **Rhetorical function labels** | Each sentence labeled: Problem / Literature / Gap / Objective / Method / Transition |
| 📊 **Logic analysis report** | Rhetorical category accuracy, ordering pattern comparison, personalized writing advice |
| ⏱️ **Timer & records** | Real-time timer + best records + practice history |
| 💡 **Smart hints** | Progressive hints for the next sentence, not direct answers |
| 📱 **Responsive design** | Desktop and mobile support |

### 🚀 Quick Start

**Use online**: Visit [GitHub Pages](https://youxuels.github.io/academic-write-trainer/)

**Run locally**:
```bash
git clone https://github.com/youxuels/academic-write-trainer.git
cd academic-write-trainer
# Open index.html with any method, e.g.:
python -m http.server 8080
# Then visit http://localhost:8080
```

### 📖 How to Use

1. **Select a paper**: Choose from the built-in library or upload your own PDF
2. **Select a section**: Switch between Abstract / Introduction / Literature Review
3. **Select difficulty**: Sentence-level (finest) → Paragraph-level → Section-level (broadest)
4. **Click to order**: Click sentences in the left panel to add them in your preferred order to the right panel
5. **Check results**: Click "Check" to see accuracy — green = correct, red = incorrect
6. **View report**: Click "Report" for logic preference analysis and writing suggestions

### 🏷️ Rhetorical Function Labels

| Label | Meaning | Typical Position |
|-------|---------|-----------------|
| ❓ Problem | Raising research questions or concerns | Beginning of Introduction |
| 📚 Literature | Citing prior research | Middle of Introduction |
| 🔍 Gap | Identifying shortcomings in existing research | After Literature Review |
| 🎯 Objective | Stating research objectives | After Gap |
| 🔬 Method | Describing research methods and design | End of Introduction |
| 🔗 Transition | Connecting sentences or sections | Section boundaries |

### 🤝 Contributing

Contributions are welcome:
- 🌟 Star this project
- 📝 Submit Issues for bugs or suggestions
- 🔧 Submit Pull Requests for code contributions
- 📄 Contribute more built-in paper data

---

## 📜 License

[MIT License](LICENSE) © 2026 youxuels
