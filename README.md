# LLM 微调与后训练论文清单

近 24 个月顶会中，核心贡献属于大语言模型或基础模型微调与后训练的论文题录。范围包括监督微调（SFT）、指令微调与指令遵循、RLHF、DPO / GRPO 及其他偏好优化、对齐、奖励建模、持续预训练，以及 LoRA / QLoRA / PEFT 等方法与相关实证研究。

本仓库只整理已核验的公开题录，**不新增论文、作者、会议或链接**。中文提要在来源给出官方摘要时按摘要改写；来源写明没有摘要时，提要以「仅根据标题概括」开头。

## 检索窗口

- **日期：** 2024-11-13 至 2026-11-13（含边界；按会议或正式出版日期）。
- **来源清单日期：** 2026-11-13（Asia/Shanghai）。
- **来源：** OpenReview / 会议虚拟站官方列表与摘要、NeurIPS / ICLR / ICML / COLM 会议站点、PMLR、ACL Anthology、CVF Open Access、ECCV 虚拟站、AAAI 分卷与 Crossref、IJCAI 会议录、KDD / WWW / SIGIR 官方接收列表或 ACM / SIGWEB 目次。
- **工作坊、Industry、Demo、SRW、教程、IAAI、EAAI、学生摘要**默认未系统收录。

## 数量

来源清单 3541 篇，剔除 [44 篇误收](dropped.md) 后保留 **3497** 篇。

- **Main：** 2955 篇。AAAI 的 AI Alignment 特别赛道计在 Main 内，并在页面中单独标出（共 25 篇）。
- **Findings：** 533 篇（ACL 系列 Findings，不是 KDD 的非主会赛道）。
- **其他赛道：** 9 篇。仅 KDD 2026：Applied Data Science、Datasets and Benchmarks，以及来源标记为 `ais` 的 AI for Sciences。这些**不是 Findings**。
- **有官方摘要并已改写提要：** 3277 篇。
- **来源无摘要、仅根据标题概括：** 220 篇。

## 按会议

| 年份 | 会议 | Main | Findings | 其他赛道 | 合计 | 无摘要 | 页面 |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- |
| 2024 | EMNLP | 90 | 59 | 0 | 149 | 3 | [2024 EMNLP](papers/2024/emnlp.md) |
| 2024 | NeurIPS | 118 | 0 | 0 | 118 | 0 | [2024 NeurIPS](papers/2024/neurips.md) |
| 2025 | AAAI | 63 | 0 | 0 | 63 | 0 | [2025 AAAI](papers/2025/aaai.md) |
| 2025 | ACL | 145 | 91 | 0 | 236 | 0 | [2025 ACL](papers/2025/acl.md) |
| 2025 | COLM | 37 | 0 | 0 | 37 | 37 | [2025 COLM](papers/2025/colm.md) |
| 2025 | CVPR | 47 | 0 | 0 | 47 | 0 | [2025 CVPR](papers/2025/cvpr.md) |
| 2025 | EMNLP | 108 | 75 | 0 | 183 | 0 | [2025 EMNLP](papers/2025/emnlp.md) |
| 2025 | ICCV | 44 | 0 | 0 | 44 | 0 | [2025 ICCV](papers/2025/iccv.md) |
| 2025 | ICLR | 189 | 0 | 0 | 189 | 0 | [2025 ICLR](papers/2025/iclr.md) |
| 2025 | ICML | 148 | 0 | 0 | 148 | 0 | [2025 ICML](papers/2025/icml.md) |
| 2025 | IJCAI | 7 | 0 | 0 | 7 | 7 | [2025 IJCAI](papers/2025/ijcai.md) |
| 2025 | KDD | 3 | 0 | 0 | 3 | 3 | [2025 KDD](papers/2025/kdd.md) |
| 2025 | NAACL | 39 | 26 | 0 | 65 | 0 | [2025 NAACL](papers/2025/naacl.md) |
| 2025 | NeurIPS | 237 | 0 | 0 | 237 | 0 | [2025 NeurIPS](papers/2025/neurips.md) |
| 2025 | SIGIR | 8 | 0 | 0 | 8 | 8 | [2025 SIGIR](papers/2025/sigir.md) |
| 2025 | WWW | 0 | 0 | 0 | 0 | 0 | 目次不完整，未收录 |
| 2026 | AAAI | 141 | 0 | 0 | 141 | 0 | [2026 AAAI](papers/2026/aaai.md) |
| 2026 | ACL | 163 | 126 | 0 | 289 | 0 | [2026 ACL](papers/2026/acl.md) |
| 2026 | COLM | 60 | 0 | 0 | 60 | 0 | [2026 COLM](papers/2026/colm.md) |
| 2026 | CVPR | 90 | 0 | 0 | 90 | 90 | [2026 CVPR](papers/2026/cvpr.md) |
| 2026 | EACL | 16 | 21 | 0 | 37 | 0 | [2026 EACL](papers/2026/eacl.md) |
| 2026 | ECCV | 65 | 0 | 0 | 65 | 0 | [2026 ECCV](papers/2026/eccv.md) |
| 2026 | EMNLP | 171 | 135 | 0 | 306 | 0 | [2026 EMNLP](papers/2026/emnlp.md) |
| 2026 | ICLR | 283 | 0 | 0 | 283 | 0 | [2026 ICLR](papers/2026/iclr.md) |
| 2026 | ICML | 298 | 0 | 0 | 298 | 0 | [2026 ICML](papers/2026/icml.md) |
| 2026 | IJCAI | 20 | 0 | 0 | 20 | 20 | [2026 IJCAI](papers/2026/ijcai.md) |
| 2026 | KDD | 21 | 0 | 9 | 30 | 30 | [2026 KDD](papers/2026/kdd.md) |
| 2026 | NAACL | 0 | 0 | 0 | 0 | 0 | 官方列表缺失，未收录 |
| 2026 | NeurIPS | 322 | 0 | 0 | 322 | 0 | [2026 NeurIPS](papers/2026/neurips.md) |
| 2026 | SIGIR | 5 | 0 | 0 | 5 | 5 | [2026 SIGIR](papers/2026/sigir.md) |
| 2026 | WWW | 17 | 0 | 0 | 17 | 17 | [2026 WWW](papers/2026/www.md) |
|  | **合计** | **2955** | **533** | **9** | **3497** | **220** |  |

Main 含各会主会，以及 AAAI Alignment 特别赛道。KDD 的 Research Track 记在 Main；Applied Data Science、Datasets and Benchmarks 与 AI for Sciences（ais）记在「其他赛道」。

### 各会次说明

- **2024 EMNLP：** 主会与 Findings。会期为 2024-11-12 至 11-16，按窗口边界收录。同年 ICML / ICLR / ACL / NAACL / CVPR / AAAI 不在窗口内。
- **2024 NeurIPS：** 官方虚拟站主会列表（含摘要）。
- **2025 AAAI：** Crossref 卷 39 技术赛道与 Alignment 特别赛道；来源已排除学生摘要、IAAI、EAAI 与演示。
- **2025 ACL / EMNLP / NAACL、2026 ACL / EMNLP / EACL：** Anthology long/short 与 Findings。
- **2025 COLM：** 官方会议录题录完整；摘要未批量抓取，提要多据标题。
- **2025 CVPR / ICCV、2025 ICLR / ICML / NeurIPS：** 官方虚拟站 JSON（ICLR 已排除 Blog Track）。
- **2025 IJCAI / KDD / SIGIR：** 官方题录或 Research / Full / Short 列表；多数无摘要。
- **2025 WWW：** 未收录。所用 SIGWEB 目次只解析出约 100 条，筛选后没有明确的微调或后训练论文，且该会次不完整。
- **2026 AAAI：** Crossref 卷 40 技术赛道与 Alignment 特别赛道。
- **2026 COLM / ECCV / ICLR / ICML：** 官方虚拟站与摘要 JSON。ICML 另可对照 PMLR v306。
- **2026 CVPR：** CVF Open Access 题录完整；官方摘要 JSON 只有分页前 200 条，多数提要仅据标题。
- **2026 IJCAI / SIGIR / WWW：** 官方列表相对完整；无摘要者仅据标题。
- **2026 KDD：** 官方 papers 页。Research Track 记为 Main；ADS、Datasets and Benchmarks、AI for Sciences（ais）单独标出。
- **2026 NAACL：** 未收录。检索日 Anthology 无 `2026.naacl` 分卷，不代表该会没有相关论文。
- **2026 NeurIPS：** 虚拟站 orals/posters 与摘要已公开，故收录；papers.neurips.cc 会议录当时尚未上线。

## 已知缺口

- **NAACL 2026**（Toronto，2026-06-08 至 06-13）：检索日没有可核验的官方全文列表，本清单为 0 篇。
- **WWW 2025：** 目次不完整，本清单为 0 篇。WWW 2026 来自官方研究轨道接收列表。
- **标题关键词收录：** 以标题中的方法或主题词筛选。只在摘要里提到 fine-tuning 或 instruction-tuned model、标题却不直观的论文可能被漏掉。
- **摘要缺失：** 不少 IJCAI、KDD、SIGIR、WWW 2026、COLM 2025 与大部分 CVPR 2026 条目没有摘要，提要会写明「仅根据标题概括」。
- **arXiv：** 只保留来源官方字段里已经给出的 PDF / arXiv 链接，没有按标题另配 arXiv。
- **误收：** 见 [dropped.md](dropped.md)。未剔除的条目仍可能是把微调用在下游任务上的工作；来源以标题主题词为准，摘要未逐篇改判。

## 条目里有什么

每篇包含标题、作者、会议与年份（Findings 与非主会赛道会标明）、官方论文页、来源中已有的 PDF / arXiv、1–2 句中文提要、关键词。

## 许可

题录事实来自上述公开会议列表。本仓库的组织方式与中文提要采用 [MIT 许可](LICENSE)。PDF 与论文页面的版权归作者和出版方。
