# Stella · Private AI Epigram Companion
[![Deployment - GitHub Pages](https://img.shields.io/badge/Deployment-GitHub_Pages-2A2E35?style=flat-square&logo=github)](https://pages.github.com/)
[![Kernel - Claude API](https://img.shields.io/badge/Kernel-Claude_Opus-E87B57?style=flat-square)](https://www.anthropic.com/)
[![Architecture - Serverless](https://img.shields.io/badge/Architecture-Single_File_HTML-A3B19B?style=flat-square)](https://developer.mozilla.org/)

> **"窗外在下雨。那些他没有看懂的伏笔，我在这里陪你写完。"**
> —— Stella 是一款运行于全平台浏览器的私人温带文本交互容器。

基于单文件无后端（Serverless）架构设计，无需安装任何客户端应用。引入极简主义美学与大面积视觉留白，旨在为用户提供高度克制、具备电影分镜质感的短流媒体文本重构与情感共鸣体验。

---

## 🖤 核心功能矩阵 / Core Features

* ### ⚖️ 电影质感配文重构 (Text Reconstruction)
    专为社交媒体（小红书、朋友圈等）提供反高频词、反鸡汤的文本加工。
    * **输入机制**：接收低频、碎片化的图像描述、空间场景或即时情绪。
        > *e.g. “傍晚的便利店，灯有点冷，一个人”*
    * **输出逻辑**：后台通过高精度 System Prompt 筑墙，剔除“微醺、治愈、温柔”等工业廉价词汇，输出具备高留白、断句利落的叙事感短文。

* ### 🕊️ 沉浸式叙事树洞 (Silent Dialogue)
    支持全静默的交互流。在特定对话模式下，AI 将自动关闭建议系统与逻辑分析矩阵，转为简短、有质感的陪伴式回应，承接无处安放的梦境与独白。

---

## 🛠️ 交互范式 / Interaction Pipeline

[ Onboarding 场景解构 ]
│
▼
[ 输入多维情绪 / 画面 ]
│
▼
[ 触发行程逻辑判断 ]
│
├────────────────────────┐
▼                        ▼
[ 渲染留白卡片 ]           (可选) 语音流自动接入


1. **会话配置**：初始化阶段键入标识或情感模式状态。
2. **多模态输入**：支持传统文本键入（`Enter` 发送 / `Shift+Enter` 换行）或流式语音识别输入。
3. **语音解构 (Voice-to-Text)**：原生接入 `Web Speech API` 标准（完美适配 Safari 及 Chrome 浏览器），实现无间断闭环语音识别。

---

## ⚙️ 技术架构与部署 / Specification

```json
{
  "architecture": "Single-file HTML5 / Pure Frontend",
  "styling": "CSS3 Linear Gradient / Serif CJK Typography",
  "api_gateway": "leafapi.cc (Reverse Proxy Layer)",
  "core_llm": "claude-opus-4-7"
}
零侵入性：纯前端执行核心，不设置中心化后端数据库，保障用户所有情感交互数据与个人设置均安全留存于本地浏览器缓存。

高级内核：通过底层转发层无缝调用 Anthropic 的 Claude 顶级大语言模型，确保文学审美与文本细腻度的全方位压制。

无成本部署：对原生静态托管极其友好，完美支持一键部署至 GitHub Pages 或 Vercel。
