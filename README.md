<div align="center">

# 🕊️ Starryear Quiet Witness｜静观三联

**让一张照片从现实证据，走入宋画式超现实空间，最后沉静为极简余韵。**

![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=for-the-badge&logo=openai&logoColor=white)
[![Usage](https://img.shields.io/badge/Usage-Personal%20%26%20Non--commercial-lightgrey?style=for-the-badge)](./LICENSE.md)
[![Language](https://img.shields.io/badge/🌐_中文-English-blue?style=for-the-badge)](#)

</div>

---

## ⚠️ 声明

> **仅限个人学习、非营利研究与非商业创作。**
> 任何商业使用均须事先取得 Starryear年 的书面许可。
>
> 分享作品时，欢迎标注来源并 **@Starryear年**。

---

## 📖 关于本项目

本 Skill 将单张照片编排成一张 8:15 竖向编辑长卷：上段保留未经内容改写的原图证据；中段借用北宋山水的高远、深远、平远意识，以尺度悬殊、断裂透视、悬置平面与源图连接线重组空间；下段将同一场景压缩为装裱式极简余韵。重点不是仿古滤镜，而是让照片沿着“现实—异化—沉静”的路径递减。

- ✅ 保持原图、写意重构与极简余韵的严格纵向顺序
- ✅ 从每张照片自身提取结构、重复形、连接线与唯一强调色
- ✅ 中段必须明显改变尺度、遮挡、远近、层级或连续性
- ❌ 不做统一滤镜、通用仿古山水或脱离来源的亭台树鸟

> 📝 The Skill includes the complete prompt in both **Chinese** and **English**.

---

## 🖼️ 示例作品

![海岸宋画超现实静观三联](assets/examples/coastal-song-surreal-quiet-witness.png)

> 该成品已由 Starryear年 明确认可，仅用于展示方法效果；不得把其题材、配色或构图作为其他输入的固定模板。

---

## 📋 目录

- [使用方法](#-使用方法)
- [可自由调整的部分](#️-可自由调整的部分)
- [核心原则](#-核心原则)
- [内容结构](#-内容结构)
- [许可证](#-许可证)

---

## 🚀 使用方法

### 方式一：作为 Codex Skill 使用

1. 将整个 `starryear-quiet-witness-triptych` 文件夹复制到 Codex skills 目录，例如 `~/.codex/skills/`。
2. 开启新的 Codex 对话并上传一张照片。
3. 提出需求：

   > 使用 `starryear-quiet-witness-triptych`，把这张照片做成从原图到写意再到极简余韵的纵向三联长卷。

4. Skill 输出一张完整的 8:15 竖向海报，不拆分为三张图片。

### 方式二：作为提示词直接使用

| 语言 | 文件 |
| :---: | :--- |
| 🇨🇳 中文 | [references/starryear-quiet-witness-triptych-prompt.zh-CN.md](references/starryear-quiet-witness-triptych-prompt.zh-CN.md) |
| 🇬🇧 English | [references/starryear-quiet-witness-triptych-prompt.en.md](references/starryear-quiet-witness-triptych-prompt.en.md) |

---

## 🎛️ 可自由调整的部分

| 参数 | 说明 |
| :--- | :--- |
| **编辑信息** | 可更改 SOURCE 编号、期数、日期和 2–4 词英文标题 |
| **宋画空间重组** | 可组合高远、深远、平远、断裂透视、悬置平面、雾中穿透与消失路径，至少改变两项空间参数 |
| **提炼强度** | 可调整下段回声数量、主笔触形态与强调色强弱，不改变密度递减方向 |

---

## 💡 核心原则

1. **证据不改写** — 上段原照片只能等比缩放与轻微构图裁切，不做生成式修改。
2. **同源三次表达** — 中下段的结构、节奏、颜色与主体锚点都必须可回溯到输入照片。
3. **空间异化而非照抄** — 中段通过尺度、遮挡、远近和连续性变化产生超现实感，不依赖无来源装饰。
4. **从繁到静** — 写实信息、笔触密度与视觉噪声从上到下明确递减。

---

## 📁 内容结构

```text
starryear-quiet-witness-triptych/
├── README.md
├── LICENSE.md
├── SKILL.md
├── agents/openai.yaml
├── references/
│   ├── starryear-quiet-witness-triptych-prompt.zh-CN.md
│   └── starryear-quiet-witness-triptych-prompt.en.md
└── assets/examples/
    └── coastal-song-surreal-quiet-witness.png
```

> ⚠️ 示例目录只包含 Starryear年 已明确认可的最终成品；不得放入参考图、临时输出或未经确认的测试图。

---

## 📄 许可证

本项目采用 [LICENSE.md](./LICENSE.md) 中规定的使用条款。

---

<div align="center">

**如果这个项目对你有帮助，欢迎 Star ⭐ 支持！**

</div>
