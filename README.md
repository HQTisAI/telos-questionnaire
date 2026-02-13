# TELOS 个人信息基础设施问卷

> 为个人 AI 基础设施（PAI）构建数字身份档案

[English](./README.md) | [中文](./README_CN.md)

---

## 📋 项目简介

TELOS 问卷是一个用于构建个人 AI 身份档案的工具，基于 [Daniel Miessler](https://danielmiessler.com) 提出的 **Personal AI Infrastructure (PAI)** 框架。

通过填写这份问卷，您将创建一个完整的个人数字身份档案，可供 AI 助手（如 OpenClaw）更好地理解您的工作方式、偏好和边界。

### 🌐 在线访问

- https://telos-questionnaire.vercel.app
- https://wj.hqtisai.top

---

## 🧠 什么是 TELOS？

TELOS 是一个包含 **10 个维度** 的框架，用于全面定义个人与 AI 之间的关系：

| 维度 | 英文 | 中文 | 核心问题 |
|------|------|------|----------|
| 00 | Core Identity | 核心身份 | 你是谁？你的核心价值观是什么？ |
| 01 | Work Style | 工作风格 | 你喜欢怎样与 AI 协作？ |
| 02 | Communication | 沟通偏好 | 你希望 AI 如何与你交流？ |
| 03 | Knowledge | 知识边界 | AI 应该知道什么？不知道什么？ |
| 04 | Values | 价值取向 | 什么对你最重要？ |
| 05 | Constraints | 约束条件 | 什么是绝对不能做的？ |
| 06 | Goals | 目标导向 | 你想通过 AI 实现什么？ |
| 07 | Privacy | 隐私边界 | 哪些信息是敏感的？ |
| 08 | Memory | 记忆策略 | AI 应该记住什么？忘记什么？ |
| 09 | Interests | 兴趣爱好 | 你对什么感兴趣？ |

### 🎯 核心目标

- **可操作性**：每个问题的答案都能被 AI 实际使用
- **渐进式**：从基础身份到深层偏好，层层递进
- **隐私优先**：所有数据仅在本地处理，不上传服务器

---

## ✨ 功能特性

- 📱 **移动端友好**：大字体、大触摸区域，适配手机和平板
- 🔒 **隐私安全**：数据仅在浏览器本地处理，不上传任何服务器
- 📋 **一键导出**：支持复制到剪贴板或下载 Markdown 文件
- 🖨️ **打印友好**：专为打印和 PDF 导出优化
- 🌙 **视觉舒适**：柔和的纸张质感，长时间阅读不累眼

---

## 🚀 快速开始

### 在线使用

直接访问部署地址即可开始填写：

```
https://telos-questionnaire.vercel.app
# 或镜像地址
https://wj.hqtisai.top
```

### 本地运行

```bash
# 克隆仓库
git clone https://github.com/HQTisAI/telos-questionnaire.git

# 进入目录
cd telos-questionnaire

# 使用 Python 启动简单服务器
python -m http.server 8000

# 浏览器打开
# http://localhost:8000
```

---

## 📤 导出与使用

### 导出格式

问卷完成后，您可以：
1. **复制到剪贴板**：一键复制所有答案
2. **下载 Markdown**：生成 `.md` 文件，可直接用于 AI 记忆系统

### 在 OpenClaw 中使用

导出的 Markdown 文件可作为 AI 记忆提示：

```markdown
# 用户档案 - TELOS

## 00 核心身份
[您的回答...]

## 01 工作风格
[您的回答...]
```

---

## 🔧 技术栈

- **前端**：原生 HTML5 + CSS3 + JavaScript
- **字体**：Noto Serif SC + Cormorant Garamond
- **部署**：Vercel
- **托管**：GitHub Pages

---

## 📄 许可证

MIT License - 欢迎自由使用和修改。

---

## 🙏 致谢

- [Daniel Miessler](https://danielmiessler.com) - PAI 框架理念
- [OpenClaw](https://github.com/sunner/OpenClaw) - AI 记忆系统启发

---

*此问卷仅用于帮助 AI 更好地理解和服务于您。所有数据均存储在本地，不会上传至任何服务器。*
