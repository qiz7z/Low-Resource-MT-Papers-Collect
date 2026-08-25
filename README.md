# 📚 Low-Resource MT Papers Collection

> 收集读研期间低资源机器翻译（Low-Resource Machine Translation）相关的论文、阅读笔记与翻译。

## 📖 论文列表

### RAG for Low-Resource MT（检索增强生成 × 低资源翻译）

| 年份 | 论文 | 关键词 | 笔记 |
|:---:|------|:------:|:----:|
| 2026 | [Context Volume Drives Performance: Tackling Domain Shift in Extremely Low-Resource Translation via RAG](papers/RAG-for-Low-Resource-MT/2026-loresmt-context-volume-dhao/paper.pdf) | 域偏移、RAG、后编辑、达奥语 | [中文笔记](papers/RAG-for-Low-Resource-MT/2026-loresmt-context-volume-dhao/README.md) |

<!-- 后续添加论文时，在此表格中追加行即可 -->

### 中国少数民族语言 NMT（Chinese Minority Languages）

| 年份 | 会议 | 论文 | 关键词 | 笔记 |
|:---:|:---:|------|:------:|:----:|
| 2025 | ACL | [多语言编码器的潜在能力远超你的认知：面向极低资源语言的权重共享预训练](papers/NMT-chinese-minority/2025-acl-多语言编码器的潜在能力远超你的认知：面向极低资源语言的权重共享预训练/2025.acl-long.893.pdf)（XLM-SWCM） | 权重共享、编码器拓展、藏语/维吾尔语/哈萨克语/蒙古语 | [中文笔记](papers/NMT-chinese-minority/2025-acl-多语言编码器的潜在能力远超你的认知：面向极低资源语言的权重共享预训练/多语言编码器的潜在能力远超你的认知：面向极低资源语言的权重共享预训练.md) |

### 维吾尔语（Uyghur）

| 年份 | 会议 | 论文 | 关键词 | 笔记 |
|:---:|:---:|------|:------:|:----:|
| 2025 | COLING (CCF-B) | [大语言模型的低资源语言拓展与翻译能力增强——以维吾尔语为研究对象](<papers/维语/2025.coling-main.559大语言模型的低资源语言拓展与翻译能力增强 —— 以维吾尔语为研究对象/2025.coling-main.559.pdf>) | LLM 适配、持续预训练、DPOSE 偏好优化、维吾尔语 | [中文笔记](<papers/维语/2025.coling-main.559大语言模型的低资源语言拓展与翻译能力增强 —— 以维吾尔语为研究对象/大语言模型的低资源语言拓展与翻译能力增强 —— 以维吾尔语为研究对象.md>) |

## 📂 目录结构

```
.
├── README.md                          # 本文件：论文索引与说明
├── papers/                            # 论文存放目录
│   ├── RAG-for-Low-Resource-MT/       # 检索增强生成相关
│   │   └── 2026-loresmt-context-volume-dhao/
│   │       ├── paper.pdf              # 原文 PDF
│   │       ├── README.md              # 中文阅读笔记/翻译
│   │       └── images/                # 论文中的截图与图表
│   ├── NMT-chinese-minority/          # 中国少数民族语言机器翻译
│   │   └── 2025-acl-xlm-swcm/
│   ├── 维语/                          # 维吾尔语相关研究
│   │   └── 2025-coling-uyghur-llm/
│   ├── Domain-Adaptation/             # 域自适应（待填充）
│   ├── LLM-for-MT/                    # 大语言模型翻译（待填充）
│   └── NMT-Basics/                    # 神经机器翻译基础（待填充）
├── .gitignore
└── CONTRIBUTING.md                    # 贡献指南
```

## 🏷️ 分类说明

| 分类目录 | 说明 |
|---------|------|
| `RAG-for-Low-Resource-MT/` | 使用检索增强生成（RAG）技术辅助低资源翻译的研究 |
| `NMT-chinese-minority/` | 中国少数民族语言（藏语、维吾尔语、哈萨克语、蒙古语等）机器翻译与文本生成 |
| `维语/` | 维吾尔语方向专题研究 |
| `Domain-Adaptation/` | 域自适应、域泛化相关方法 |
| `LLM-for-MT/` | 利用大语言模型（LLM）进行翻译的研究 |
| `NMT-Basics/` | 神经机器翻译基础方法与综述 |

> 💡 如果现有分类无法涵盖新论文，可以自行创建新的子目录。

## 📝 如何添加新论文

1. 在 `papers/` 下选择合适的分类目录
2. 创建以论文简称命名的子文件夹，格式：`{年份}-{会议/期刊}-{简称}`
3. 将论文 PDF 保存为 `paper.pdf`
4. （可选）创建 `README.md` 记录阅读笔记或翻译
5. （可选）将截图放入 `images/` 目录
6. 在主 README 的论文列表中添加新条目

**示例：**
```
papers/Domain-Adaptation/
└── 2025-emnlp-adaptLM/
    ├── paper.pdf
    ├── README.md
    └── images/
```

## 📊 阅读状态

| 状态标记 | 含义 |
|:-------:|------|
| ✅ | 已精读，笔记完成 |
| 📖 | 在读 |
| 📋 | 已读摘要，待精读 |
| 📄 | 仅收藏 |

## 🔖 标签索引

<!-- 按主题标签汇总论文，便于快速检索 -->

| 标签 | 相关论文 |
|------|---------|
| `RAG` | Context Volume Drives Performance (2026) |
| `域偏移` | Context Volume Drives Performance (2026) |
| `后编辑` | Context Volume Drives Performance (2026) |
| `圣经翻译` | Context Volume Drives Performance (2026) |
| `超低资源` | Context Volume Drives Performance (2026)；XLM-SWCM (2025) |
| `大语言模型` | Uyghur LLM Adaptation (2025) |
| `持续预训练` | Uyghur LLM Adaptation (2025) |
| `偏好优化 DPO` | Uyghur LLM Adaptation (2025) |
| `维吾尔语` | XLM-SWCM (2025)；Uyghur LLM Adaptation (2025) |
| `中国少数民族语言` | XLM-SWCM (2025) |
| `权重共享` | XLM-SWCM (2025) |

---

*本仓库持续更新中，欢迎 Star ⭐ 关注！*
