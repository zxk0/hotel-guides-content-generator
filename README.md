# 🏨 Hotel Guides Content Generator

> 刷酒店攻略及体验内容生成器 — 自动创作标题、正文、标签，并输出精美的 HTML 图文版。

[English](#english) | [中文](#中文)

---

## ✨ 核心功能

- **智能标题生成** — 概述式、痛点式、悬念式、个性化等多种风格
- **正文结构化写作** — 概览 → 客房 → 餐饮 → 设施 → 难忘瞬间
- **标签自动匹配** — 精准组合，提升曝光率
- **照片智能识别** — 分析用户照片，自动生成精确描述
- **双格式输出** — `.md` 纯文本版 + `.html` 图文版（可直接浏览器预览/分享）

## 📸 HTML 输出效果

生成的 HTML 文件包含：

- 🎨 **深色主题 + 金色点缀**配色，契合高端酒店调性
- 📷 **卡片式图片展示**，带圆角阴影和悬停动效
- ⭐ **醒目评分卡片**，数字评分 + 星级显示
- 🏷️ **标签墙**，圆角 tag 云
- 📱 **响应式布局**，完美适配手机端

## 🚀 快速开始

### 方式一：直接生成（无照片）

```
生成一篇关于[主题]的酒店攻略
```

### 方式二：提供照片目录（推荐）

```
照片在 D:\华尔道夫照片，帮我生成华尔道夫酒店的攻略
```

> 💡 将酒店照片放入一个文件夹，按下述命名约定命名文件，AI 会自动识别并嵌入对应章节。

### 照片文件命名约定

| 文件名关键词 | 识别为 |
|-------------|--------|
| 外观 / 大楼 / 外立面 | 酒店外观 |
| 大堂 / lobby | 酒店大堂 |
| 客房 / 房间 / 整体 | 客房整体 |
| 局部 / 细节 / 特写 | 客房局部 |
| 卫生间 / 浴室 / 洗手间 | 卫生间浴室 |
| 餐厅 / 早餐 / HappyHour | 餐饮 |
| 健身房 / 泳池 / 设施 | 设施 |
| 难忘瞬间 | 难忘瞬间 |

### 方式三：指定风格

```
写一篇[酒店体验/酒店攻略/酒店吐槽]类的相关内容，主题是[主题]
```

## 📁 输出文件结构

```
工作区/
├── [酒店名]酒店攻略.html    ← 浏览器直接打开预览
├── [酒店名]酒店攻略.md      ← 纯文本可编辑版本
└── images/                  ← 照片副本
    ├── 酒店大楼外观照片.JPEG
    ├── 酒店大堂照片.JPEG
    └── ...
```

## 🔧 技术栈

- WorkBuddy Skill Framework
- HTML5 + CSS3（响应式设计）
- 图片多模态识别

## 📋 版本历史

| 版本 | 日期 | 说明 |
|------|------|------|
| v1.2.0 | 2026-04-24 | 新增照片文件提供方式说明，双格式输出 |
| v1.1.0 | 2026-04-24 | 新增 HTML 图文输出能力 |
| v1.0.0 | 2026-04-23 | 首次发布 |

## ⚠️ 注意事项

1. **照片请使用文件夹路径方式提供**，而非直接拖拽上传到对话中
2. 建议照片分辨率 1080p 以上，文件大小不超过 10MB
3. AI 生成内容建议人工微调后发布，保留个人语言习惯
4. 避免敏感词（"最"、"第一"、价格等）

---

## English

### Hotel Guides Content Generator

A WorkBuddy skill for automatically generating hotel experience blog posts with beautiful HTML output.

**Features:** Smart titles, structured content, photo recognition, dual-format output (.md + .html)

**Get Started:**
```
Generate a hotel guide about [hotel name]
```

---

> ⚠️ **Disclaimer:** This tool is for content creation assistance only. Please review and personalize AI-generated content before publishing.
