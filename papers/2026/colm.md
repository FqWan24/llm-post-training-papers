# 2026 · COLM

共 60 篇。Main 60，Findings 0，其他赛道 0。其中 0 篇来源题录无摘要，提要标明「仅根据标题概括」。

检索窗口为 2024-11-13 至 2026-11-13。题录信息来自官方列表，不在此增补作者、链接或实验数字。

## Main

### A11yn: Aligning LLMs for Web Accessibility-Aware UI Generation

- **作者：** Janghan Yoon, Jaegwan Cho, Junhyeok Kim, Jiwan Chung, Jaehyun Jeon, Seungwon Lim, Youngjae Yu
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/fc740286fb4840cb56f99400817967da-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/fc740286fb4840cb56f99400817967da-Paper-Conference.pdf)
- **中文提要：** 大模型能按自然语言生成视觉上连贯的网页界面，却常常违反网页内容无障碍指南，把需求与情境多样的用户排除在外。A11yn 是一套面向无障碍网页界面生成的后训练框架。
- **关键词：** post-training, alignment

### ACTOR-CURATOR: Online Curriculum Learning via Policy Improvement Bandits for RL Post-Training

- **作者：** Zhengyao Gu, Jonathan Li, Raul Astudillo, Ziyu Ye, Langzhou He, Henry P Zou, Pei Chen, Wei Cheng, Santiago Paternain, Philip S Yu, Yisong Yue
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/5df4313ecd4875931fbdacc486cc1fcf-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/5df4313ecd4875931fbdacc486cc1fcf-Paper-Conference.pdf)
- **中文提要：** 用强化学习做大模型后训练通常依赖海量且异质的数据，课程学习因此既关键又困难。ACTOR-CURATOR 提出可扩展、全自动的在线课程框架，并以策略改进赌博机来组织这一过程。
- **关键词：** post-training

### Aligning Language Models from User Interactions

- **作者：** Thomas Kleine Buening, Jonas Hübotter, Barna Pásztor, Idan Shenfeld, Giorgia Ramponi, Andreas Krause
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/29f3514801f3f327d808799f5ac122ba-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/29f3514801f3f327d808799f5ac122ba-Paper-Conference.pdf)
- **中文提要：** 多轮用户交互数量很大，却缺少有效的学习方法，通常被直接丢弃。后续消息往往能表明回答有误、未遵循指令或不符合偏好，作者据此从用户交互中对齐语言模型。
- **关键词：** instruction-following, alignment

### Alignment Whack-a-Mole : Finetuning Activates Verbatim Recall of Copyrighted Books in Large Language Models

- **作者：** Xinyue Liu, Niloofar Mireshghallah, Jane C Ginsburg, Tuhin Chakrabarty
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/4ec43957eda1126ad4887995d05fae3b-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/4ec43957eda1126ad4887995d05fae3b-Paper-Conference.pdf)
- **中文提要：** 前沿公司常向法院和监管方保证模型不保存训练数据副本，并依靠 RLHF、系统提示和输出过滤阻止逐字复述受版权作品，还在侵权抗辩中引用这些措施。这项工作考察微调如何重新激活对受版权图书的逐字回忆，并把这种现象称为打地鼠式对齐。
- **关键词：** RLHF, alignment, fine-tuning

### Apriel-Reasoner: RL Post-Training for General-Purpose and Efficient Reasoning

- **作者：** Rafael Pardinas, Ehsan Kamalloo, David Vazquez, Alexandre Drouin
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/20e45668fefa793bd9f2edf19be12c4b-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/20e45668fefa793bd9f2edf19be12c4b-Paper-Conference.pdf)
- **中文提要：** 前沿开源权重模型广泛用跨领域的可验证奖励强化学习来构建通用推理模型，但训练配方和领域配比往往不公开。Apriel-Reasoner 讨论面向通用且高效推理的强化学习后训练。
- **关键词：** RLVR, instruction-following, post-training

### AutoOR: Scalably Post-training LLMs to Autoformulate Operations Research Problems

- **作者：** Sumeet Motwani, Chuan Du, Aleksandar Petrov, Christopher E Davis, Philip Torr, Antonio R Papania-Davis, Weishi Yan
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/69b3c0e0e79112c7d5c1e20ba21b4b49-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/69b3c0e0e79112c7d5c1e20ba21b4b49-Paper-Conference.pdf)
- **中文提要：** 制造、物流、调度等场景要把复杂描述转成求解器可用的形式，这依赖专门的运筹学知识，难以扩展。AutoOR 通过对大模型做可扩展的后训练，使其自动写出运筹问题的形式化表述。
- **关键词：** post-training

### Behavioral Canaries: Auditing Private Retrieved Context Usage in RL Fine-Tuning

- **作者：** Chaoran Chen, Dayu Yuan, Peter Kairouz
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/4db8a681ae1e58376dc6227978829063-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/4db8a681ae1e58376dc6227978829063-Paper-Conference.pdf)
- **中文提要：** 智能体流程里，大模型经常处理法律上禁止再用于训练的检索上下文，审计方却难以核验提供方是否把这些数据纳入后训练，尤其是强化学习微调。行为金丝雀被用来审计这种私有检索上下文是否被使用。
- **关键词：** RFT, post-training, fine-tuning

### Breaking Memorization Barriers in LLM Code Fine-Tuning via Information Bottleneck for Improved Generalization

- **作者：** Changsheng Wang, Xin Chen, Sijia Liu, Ke Ding
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/a8526465a91166fbb90aaa8452b21eda-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/a8526465a91166fbb90aaa8452b21eda-Paper-Conference.pdf)
- **中文提要：** 把预训练大模型用监督微调适配到代码生成时，基座对下游代码的强记忆可能困住优化，使常规微调学不到可泛化的新代码知识。作者把这种现象称为记忆壁垒，并借助信息瓶颈来打破它。
- **关键词：** SFT, fine-tuning

### CeRA: Breaking the Linear Ceiling of Low-Rank Adaptation with Non-linearity Retained at Inference

- **作者：** Hung-Hsuan Chen
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/46496431b12dc0dc38f81e31f94eedb9-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/46496431b12dc0dc38f81e31f94eedb9-Paper-Conference.pdf)
- **中文提要：** LoRA 主导着参数高效微调，但受线性约束，提高秩对表达能力的收益递减，形成所谓线性天花板。CeRA 试图在推理时仍保留非线性，以突破这一上限。
- **关键词：** LoRA, PEFT, fine-tuning

### CIDER: A Dataset of Contextual Disclosure Boundaries for Privacy Preference Alignment

- **作者：** Bingcan Guo, Eryue Xu, Jijie Zhou, Zhiping Zhang, Tianshi Li
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/3cbf627fa24fb6cb576e04e689b9428b-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/3cbf627fa24fb6cb576e04e689b9428b-Paper-Conference.pdf)
- **中文提要：** 对齐人类隐私偏好需要捕捉超出一般规范的个人披露边界，但如何在真实情境中引出这种细微偏好并用于评估，仍有缺口。CIDER 提供情境化披露边界数据，供隐私偏好对齐使用。
- **关键词：** preference-optimization, alignment

### Correct Answers from Sound Reasoning: Verifiable Process Supervision for Language Models

- **作者：** Kyuyoung Kim, Kevin Wang, Yunfei Xie, Peiyang Xu, Peiyao Sheng, Chen Wei, Zhangyang Wang, Jinwoo Shin, Pramod Viswanath, Sewoong Oh
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/201e691e8a0940291dc591eb0439a789-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/201e691e8a0940291dc591eb0439a789-Paper-Conference.pdf)
- **中文提要：** 可验证奖励的强化学习通常只优化最终结果，任务更准的同时推理质量可能下降，轨迹会出现不准确、不完整或不一致。这里研究可验证的过程监督，使正确答案来自可靠推理。
- **关键词：** SFT, post-training, fine-tuning

### Data Repetition Beats Data Scaling in Long-CoT Supervised Fine-Tuning

- **作者：** Dawid J Kopiczko, Sagar Vaze, Tijmen Blankevoort, Yuki M Asano
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/7c20581b5d3a869097943fd5237ac31e-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/7c20581b5d3a869097943fd5237ac31e-Paper-Conference.pdf)
- **中文提要：** 思维链数据上的监督微调是推理语言模型后训练的重要步骤。常规直觉认为更多不重复样本会带来更好泛化，该工作则比较长思维链监督微调中数据重复与继续扩大数据规模的作用。
- **关键词：** SFT, post-training, fine-tuning

### Delay, Plateau, or Collapse: Evaluating the Impact of Systematic Verification Error on RLVR

- **作者：** Kazuki Egashira, Mark Vero, Jasper Dekoninck, Florian E Dorner, Robin Staab, Martin Vechev
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/2a28bea6298d106eed091ac403d8c22b-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/2a28bea6298d106eed091ac403d8c22b-Paper-Conference.pdf)
- **中文提要：** 可验证奖励强化学习面向有标准答案可核验的任务，但静态代码检查器这类真实验证器会把错误写进奖励。作者评估系统性验证误差会带来延迟、平台期还是坍缩。
- **关键词：** RLVR

### DR-LoRA: Dynamic Rank LoRA for Fine-Tuning Mixture-of-Experts Models

- **作者：** Guanzhi Deng, Bo Li, Ronghao Chen, Xiujin Liu, Huacan Wang, Zhuo Han, Lijie Wen, Linqi Song
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/dbf02b21d77409a2db30e56866a8ab3a-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/dbf02b21d77409a2db30e56866a8ab3a-Paper-Conference.pdf)
- **中文提要：** 混合专家是扩展大模型的重要范式，LoRA 等参数高效方法常被用来把预训练混合专家模型适配到下游。DR-LoRA 提出按动态秩做 LoRA 微调。
- **关键词：** LoRA, PEFT, fine-tuning

### Emergent Unfaithfulness: How Alignment Training Causes Language Models to Silently Override Task Faithfulness

- **作者：** Pardis Sadat Zahraei, Janvijay Singh, Gokhan Tur, Dilek Hakkani-Tür
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/11e2fab2d055c6b825018565cc81d62a-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/11e2fab2d055c6b825018565cc81d62a-Paper-Conference.pdf)
- **中文提要：** 已有工作讨论了能力与对齐、能力与忠实性之间的权衡，对齐与忠实性的冲突仍较少被研究。该文关注对齐训练如何让语言模型悄悄压过任务忠实性，出现涌现的不忠实。
- **关键词：** DPO, post-training, alignment

### English is Not All You Need: Systematically Exploring the Role of Multilinguality in LLM Post-Training

- **作者：** Mehak Dhaliwal, Shashwat Ranjan Chaurasia, Yao Qin, Dezhi Hong, Thomas Butler
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/d9042abf40782fbce28901c1c9c0e8d8-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/d9042abf40782fbce28901c1c9c0e8d8-Paper-Conference.pdf)
- **中文提要：** 大模型虽被多语言部署，后训练流程仍以英语为中心，加剧了跨语言表现差距。作者在平行翻译的多语言数据混合上，系统考察训练语言覆盖、模型规模与任务领域如何相互影响。
- **关键词：** SFT, post-training, fine-tuning

### ExpertWeave: Efficiently Serving Expert-Specialized Fine-Tuned Adapters at Scale

- **作者：** Ge Shi, Hanieh Sadri, Qian Wang, Yu Zhang, Ying Xiong, Yong Zhang, Zhenan Fan
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/2bf490f7cd34b98c99a62ef10b959adc-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/2bf490f7cd34b98c99a62ef10b959adc-Paper-Conference.pdf)
- **中文提要：** 专家专用微调只选择性更新混合专家大模型里对该任务激活最强的专家，以加强任务表现。大规模服务这些微调结果时，单独部署合并模型非常耗资源，而现有采用 LoRA 式加性更新的多适配器服务又与之不相容。
- **关键词：** LoRA, fine-tuning

### ExpRL: Exploratory RL for LLM Mid-Training

- **作者：** Violet Xiang, Amrith Setlur, Chase Blagden, Nick Haber, Aviral Kumar
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/6712854a31fe87ad81bc21133345e3d9-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/6712854a31fe87ad81bc21133345e3d9-Paper-Conference.pdf)
- **中文提要：** 稀疏奖励强化学习已成为提升大语言模型推理的常用手段，但其成败很大程度上取决于基座模型已有的覆盖。实践中，模型常先在精心整理的推理轨迹上做中期训练，学习分解、验证或自我纠错这类基础技能。
- **关键词：** mid-training

### Extracting Arguments, Not Just Classifying Them: Instruction-Tuned LLMs for Generative Component Detection

- **作者：** Sofiane Elguendouze, Erwan Hain, Elena Cabrio, Serena Villata
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/009e6f3fc8ddec51ac31daa48c94da2b-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/009e6f3fc8ddec51ac31daa48c94da2b-Paper-Conference.pdf)
- **中文提要：** 论证成分检测要同时划定论证片段并把它分成主张、前提等成分，是论证挖掘中较难的一环。相较其他论证挖掘任务，这方面研究仍相对有限，多数现有做法把它简化成序列标注。
- **关键词：** instruction-tuning

### Faithful GRPO: Improving Visual Spatial Reasoning in Multimodal Language Models via Constrained Policy Optimization

- **作者：** Sai Srinivas Kancheti, Aditya S Kanade, Rohit Sinha, Vineeth N Balasubramanian, Tanuja Ganu
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/2fcf4bb0ac9d37a8da5c9c3a37e04ab0-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/2fcf4bb0ac9d37a8da5c9c3a37e04ab0-Paper-Conference.pdf)
- **中文提要：** 用可验证奖励强化学习训练的多模态推理模型，在视觉推理基准上的准确率有所提高。这种提高往往以推理质量为代价：生成的思维链常常与最终答案不一致，也很少扎根于视觉证据。
- **关键词：** GRPO, RLVR

### Fine-Tuning Was Not Broken but Diffuse: Precise Knowledge Editing via Projected Error Signals

- **作者：** Shahar Katz, Avi Caciularu, Lior Wolf
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/185969291540b3cd86e70c51e8af5d08-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/185969291540b3cd86e70c51e8af5d08-Paper-Conference.pdf)
- **中文提要：** 经大规模文本反向传播训练的 Transformer 大语言模型编码了大量事实，也可能保留错误或过时的关联。已有事实编辑工作表明微调常带来排斥效应，损害泛化并覆盖非目标知识，从而促使人们转向秩一等替代做法。
- **关键词：** fine-tuning

### FLINT: Influence-Guided Active Learning Framework for LoRA via Curvature-Aware Data Selection and Fine-Tuning

- **作者：** Zixuan Li, Shenglan Guo, Zhigen Li, Yanmeng Wang, Ning Cheng, Shaojun Wang, Deyi Xiong
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/acb94e709f02895fd98b5867f0b184f3-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/acb94e709f02895fd98b5867f0b184f3-Paper-Conference.pdf)
- **中文提要：** 指令微调大语言模型时，从大规模数据中找出有益样本，对发挥模型性能很关键。传统方法依赖静态语义启发式，忽略训练动态，也难以准确估计样本贡献。
- **关键词：** LoRA, fine-tuning

### From RLVR to RLSVR: Task Transformation Induces Self-Verifiable Rewards for Open-Ended LLM Self-Improvement

- **作者：** Qinsi Wang, Jing Shi, Huazheng Wang, Kun Wan, Yiran Wu, Bo Liu, Qingyun Wu, Hai H Li, Yiran Chen, Handong Zhao, Wentian Zhao
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/fd0705710bf01b88a60a3d479ea341d9-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/fd0705710bf01b88a60a3d479ea341d9-Paper-Conference.pdf)
- **中文提要：** 可验证奖励强化学习通过大规模优化，推动了面向推理的大语言模型进展。它的适用面仍主要限于数学和编程等正确性可以被确定验证的领域。
- **关键词：** RLVR, reward-model

### From SWE-ZERO to SWE-HERO: Execution-free to Execution-based Fine-tuning for Software Engineering Agents

- **作者：** Nikolai Ludwig, Wasi Ahmad, Somshubra Majumdar, Boris Ginsburg
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/cf5c369c1bc070361477008e3f5210ed-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/cf5c369c1bc070361477008e3f5210ed-Paper-Conference.pdf)
- **中文提要：** 针对自动修复软件问题的复杂性，SWE-Zero 到 SWE-Hero 给出一套高性能的 SFT 方案。传统方法往往依赖可验证的执行环境，这类环境费力且在技术上难以扩展。
- **关键词：** SFT, fine-tuning

### Guard Vector: Beyond English LLM Guardrails with Task-Vector Composition and Streaming-Aware Prefix SFT

- **作者：** Wonhyuk Lee, Youngchol Kim, Yunjin Park, Junhyung Moon, Dongyoung Jeong, Wanjin Park
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/ea0b5818ae9255ee1fb1e3b4442d2ffe-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/ea0b5818ae9255ee1fb1e3b4442d2ffe-Paper-Conference.pdf)
- **中文提要：** Guard Vector 是一条安全任务向量，取自护栏模型与同架构预训练语言模型的参数差。将该向量与目标语言模型组合，即可得到目标护栏模型。
- **关键词：** SFT, alignment, fine-tuning

### Headroom-Drift Replay: A Primitive for Principled Replay Control in GRPO

- **作者：** HYUN BIN PARK, Du-Seong Chang
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/872c8cbd5a68654a8d7fbdf0af21e3e8-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/872c8cbd5a68654a8d7fbdf0af21e3e8-Paper-Conference.pdf)
- **中文提要：** 推理模型的强化学习后训练越来越受制于反复生成全新 rollout，在智能体场景里环境交互往往主导耗时。回放可借复用历史轨迹减轻这一负担，但现有做法通常把它嵌进更大的训练流程，涉及探索、经验重组或混合策略优化。
- **关键词：** GRPO, post-training

### How Much Backtracking is Enough? Exploring the Interplay of SFT and RL in Enhancing LLM Reasoning

- **作者：** Hongyi Cai, Junlin Wang, Xiaoyin Chen, Bhuwan Dhingra
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/f14b26a1333cb9d27c6dcc7334496c57-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/f14b26a1333cb9d27c6dcc7334496c57-Paper-Conference.pdf)
- **中文提要：** 近期进展表明，强化学习能把搜索策略内化进大语言模型，并借助延长的思维链改进困难推理任务。回溯虽被广泛视为这一改进的核心机制，其具体动态以及 SFT 与强化学习如何相互作用来优化它，仍不清楚。
- **关键词：** SFT, fine-tuning

### It Takes One to Bias Them All: Breaking Bad with One-Shot GRPO

- **作者：** Naihao Deng, Yilun Zhu, Naichen Shi, Clayton Scott, Rada Mihalcea
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/2b47305e1c81890b1089a405686ad183-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/2b47305e1c81890b1089a405686ad183-Paper-Conference.pdf)
- **中文提要：** 现代大语言模型通常经过大规模后训练来对齐，以追求公平、可靠的行为。这项工作考察这些护栏有多容易被 GRPO 打破。
- **关键词：** GRPO, post-training, alignment

### Jagle: Building a Large-Scale Japanese Multimodal Post-Training Dataset for Vision–Language Models

- **作者：** Issa Sugiura, Keito Sasagawa, Keisuke Nakao, Koki Maeda, Ziqi Yin, Zhishen Yang, Shuhei Kurita, Yusuke Oda, Ryoko Tokuhisa, Daisuke Kawahara, Naoaki Okazaki
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/dd9b76f050a86a3ded6135ad3556e786-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/dd9b76f050a86a3ded6135ad3556e786-Paper-Conference.pdf)
- **中文提要：** 要让视觉语言模型跨多样任务泛化，需要内容多样的大规模训练数据。英文场景里，这类数据通常靠汇集并整理大量已有视觉问答资源来构建。
- **关键词：** post-training

### LogicIF: Towards Complex Logic Instruction Following

- **作者：** Mian Zhang, Shujian Liu, Sixun Dong, Ming Yin, Yebowen Hu, Sean Wang, Simin Ma, Song Wang, Sathish Reddy Indurthi, Haoyun Deng, Zhiyu Chen, Kaiqiang Song
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/8a5fdf1959d3ba8b218953301bec7c1e-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/8a5fdf1959d3ba8b218953301bec7c1e-Paper-Conference.pdf)
- **中文提要：** 指令遵循催生了大语言模型的近期阶段，也是推理和智能体行为等更进一步能力的基础技能。任务越难，自然语言指令中嵌入的逻辑结构就越复杂。
- **关键词：** instruction-following

### LORA-CRAFT: Cross-layer Rank Adaptation via Frozen Tucker Decomposition of Pre-trained Attention Weights

- **作者：** Kasun Dewage, Marianna Pensky, Shankhadeep Mondal, Suranadi De Silva
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/618c8af8efd19b4ce90b8864a764d0fa-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/618c8af8efd19b4ce90b8864a764d0fa-Paper-Conference.pdf)
- **中文提要：** LoRA-CRAFT（文中简称 CRAFT）把跨 Transformer 层堆叠的预训练注意力权重做 Tucker 分解，只在得到的冻结 Tucker 因子上训练小型方阵，属于极省参数的 PEFT。既有基于张量的 PEFT 同样采用分解。
- **关键词：** LoRA, PEFT, fine-tuning

### Matching Accuracy, Different Geometry: Evolution Strategies vs GRPO in LLM post-training

- **作者：** William Hoy, Binxu Wang, Xu Pan
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/46079bebac3c5379e7a70b1f36ad6750-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/46079bebac3c5379e7a70b1f36ad6750-Paper-Conference.pdf)
- **中文提要：** 进化策略成为可扩展的无梯度方案，用来替代基于强化学习的大语言模型微调，但任务表现相当是否意味着参数空间中的解也相当，仍不清楚。该比较在单任务和顺序持续学习两种设定下对照进化策略与 GRPO。
- **关键词：** GRPO, post-training, fine-tuning

### MegaScience: Pushing the Frontiers of Open Post-Training Datasets for Science Reasoning

- **作者：** Run-Ze Fan, Zengzhi Wang, Pengfei Liu
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/14a812fa4b6bf244d055e37a7cd2f557-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/14a812fa4b6bf244d055e37a7cd2f557-Paper-Conference.pdf)
- **中文提要：** 科学推理对培养人工智能科学家、并支持人类研究者推进自然科学发现很重要。开源社区主要聚焦数学和编程而忽视科学领域，很大程度是因为缺少开放、大规模、高质量且可验证的科学推理数据。
- **关键词：** post-training

### MidTool: Mid-training Data Synthesis for Agentic Tool Use

- **作者：** Fengqing Jiang, Yite Wang, Boyi Liu, Zhaoyang Wang, Canwen Xu, Zhewei Yao, Radha Poovendran, Yuxiong He
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/f4dcb743e41af10d860562367a564bcd-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/f4dcb743e41af10d860562367a564bcd-Paper-Conference.pdf)
- **中文提要：** 中期训练越来越被视为塑造大语言模型能力的关键阶段。已有工作表明，有针对性的中期训练既能加强数学、科学等推理密集型能力，也能提升软件工程场景中的智能体能力。
- **关键词：** SFT, mid-training, post-training, fine-tuning

### Mitigating LLM biases toward spurious social contexts using direct preference optimization

- **作者：** Hyunji (Alex) Nam, Dorottya Demszky
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/393367b4ccf1d56e51276243d5cb85c4-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/393367b4ccf1d56e51276243d5cb85c4-Paper-Conference.pdf)
- **中文提要：** 大语言模型越来越多地用于高风险决策，但对虚假上下文信息的敏感会引入有害偏见。在评价教师教学质量这类任务上，带偏见的评估可能影响教师的职业发展与生涯轨迹。
- **关键词：** DPO, SFT, preference-optimization, fine-tuning

### MoANT: Mixture-of-Rank-One-Experts with Semantic-aware Intuition for Multi-task Large Language Model Finetuning

- **作者：** Rongyu Zhang, Yijiang Liu, Huanrui Yang, Shenli Zheng, Li Du, Dan Wang, Yuan Du, Shanghang Zhang
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/f3bfbd65743e60c685a3845bd61ce15f-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/f3bfbd65743e60c685a3845bd61ce15f-Paper-Conference.pdf)
- **中文提要：** 大语言模型在适应多样的多任务微调时面临明显困难。混合专家凭借能够有效解耦任务的动态结构，提供了一条有希望的途径。
- **关键词：** LoRA, fine-tuning

### Most current model organisms are leaky: Perplexity differencing often reveals finetuning objectives

- **作者：** Mohammed Abu Baker, Luca Baroni, Dan Wilhelm
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/61f49711e2a509963b2c16c49d3cf83f-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/61f49711e2a509963b2c16c49d3cf83f-Paper-Conference.pdf)
- **中文提要：** 微调可以显著改变大语言模型的行为，包括引入有害或不安全行为。为研究这些风险，研究者构造模型生物，即微调后表现出特定已知行为、供受控实验使用的模型。
- **关键词：** fine-tuning

### New Skills or Sharper Primitives? A Probabilistic Perspective on the Emergence of Reasoning in RLVR

- **作者：** Zhilin Wang, Yafu Li, Shunkai Zhang, Zhi Wang, Haoran Zhang, Xiaoye Qu, Yu Cheng
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/95fb60a2c212c77ec0a7f611e5745584-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/95fb60a2c212c77ec0a7f611e5745584-Paper-Conference.pdf)
- **中文提要：** 可验证奖励强化学习是赋予大语言模型新能力，还是仅仅引出潜在轨迹，仍是核心争论。这里采取前一种看法，提出以实例级可解性来定义能力的概率框架。
- **关键词：** RLVR

### On the Role of Reasoning Patterns in the Generalization Discrepancy of Long Chain-of-Thought Supervised Fine-Tuning

- **作者：** Zhaoyi Li, Xiangyu Xi, Zhengyu Chen, Wei Wang, Gangwei Jiang, Ranran Shen, Linqi Song, Ying Wei, Defu Lian
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/5c7024041be305c94d7311cfcc53d93e-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/5c7024041be305c94d7311cfcc53d93e-Paper-Conference.pdf)
- **中文提要：** 在长思维链轨迹上做 SFT，已成为构建大型推理模型的关键阶段。不同来源的思维链轨迹如何影响模型的泛化表现，仍是开放问题。
- **关键词：** SFT, fine-tuning

### Personalized RewardBench: Evaluating Reward Models with Human Aligned Personalization

- **作者：** Qiyao Ma, Dechen Gao, Rui Cai, BOQI ZHAO, Hanchu Zhou, Junshan Zhang, Zhe Zhao
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/7371b5f5fab9fd401c4ebd352f29dc48-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/7371b5f5fab9fd401c4ebd352f29dc48-Paper-Conference.pdf)
- **中文提要：** 多元对齐成为大语言模型发展的重要前沿，奖励模型则是捕捉多样人类价值的核心机制。衡量回答总体质量的基准已经不少，但奖励模型在多大程度上顾及个体用户偏好，仍待评估。
- **关键词：** reward-model, alignment

### PivotRL: High Accuracy Agentic Post-Training at Low Compute Cost

- **作者：** Junkeun Yi, Damon Mosk-Aoyama, Baihe Huang, Ritu Gala, Charles Wang, Sugam Devare, Khushi Bhardwaj, Abhibha Gupta, Oleksii Kuchaiev, Jiantao Jiao, Jian Zhang, Venkat Krishna Srinivasan
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/4268cf6ba253744befa41ffee5083fa0-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/4268cf6ba253744befa41ffee5083fa0-Paper-Conference.pdf)
- **中文提要：** 长程智能体任务的后训练面临计算效率与泛化之间的张力。SFT 在计算上更省，却常常出现域外退化。
- **关键词：** SFT, post-training, fine-tuning

### Process Supervision of Confidence Margin for Calibrated LLM Reasoning

- **作者：** Liaoyaqi Wang, Chunsheng Zuo, William Jurayj, Benjamin Van Durme, Anqi Liu
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/72c9478fd0b19f204b280eb8152f067a-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/72c9478fd0b19f204b280eb8152f067a-Paper-Conference.pdf)
- **中文提要：** 用强化学习扩展测试时计算，被视为提升大语言模型推理能力的可靠路径。基于结果的奖励却常鼓励模型过度自信，从而带来幻觉、不可靠的置信控制以及不必要的计算分配。
- **关键词：** PRM, alignment

### Reasoning Fine-Tuning Induces Persistent Latent Policy States

- **作者：** Abir Harrasse, Michael Lan, Hunar Batra, Fateme Hashemi Chaleshtori, Chaithanya Bandi
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/59a3444d39b97ba01a17994f938e1ccc-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/59a3444d39b97ba01a17994f938e1ccc-Paper-Conference.pdf)
- **中文提要：** 推理特化的语言模型相对基座有大幅性能提升，但多步推理变好所对应的内部变化仍不清楚。尚不确定推理微调主要增强局部词元能力，还是会改变模型随时间组织推断的整体方式。
- **关键词：** fine-tuning

### Reasoning on a Spectrum: Aligning LLMs to System 1 and System 2 Thinking

- **作者：** Alireza Salkhordeh Ziabari, Nona Ghazizadeh, Zhivar Sourati, Farzan K Malekabadi, Payam Piray, Morteza Dehghani
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/34b70ece5f8d273fd670a17e2248d034-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/34b70ece5f8d273fd670a17e2248d034-Paper-Conference.pdf)
- **中文提要：** 大语言模型表现出较强的推理能力，但对结构化逐步处理的依赖也暴露出关键局限。人类认知会随情境在直觉启发式的系统一与分析审议的系统二之间灵活切换，由此引出统一推理策略对大语言模型是否最优的问题。
- **关键词：** alignment

### RefusalGuard: Geometry-Preserving Fine-Tuning for Safety in LLMs

- **作者：** Sadia Asif, Mohammad Mohammadi Amiri
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/873c86d9a979ab80d8e2919510d4446b-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/873c86d9a979ab80d8e2919510d4446b-Paper-Conference.pdf)
- **中文提要：** 把已安全对齐的语言模型微调到下游任务，常常明显削弱拒绝行为，使模型更容易被对抗性滥用。已有工作表明安全相关特征编码在激活空间的结构化表示中，但这些表示在微调中如何变化、对齐为何退化，仍不清楚。
- **关键词：** alignment, fine-tuning

### Reinforcement Routing for Mixtures of LoRAs in Parameter-Efficient LLM Finetuning

- **作者：** Ruizhong Qiu, Hanqing Zeng, Yinglong Xia, Yiwen Meng, Ren Chen, Jiarui Feng, Dongqi Fu, Qifan Wang, Jiayi Liu, Jun Xiao, Xiangjun Fan, Benyu Zhang, Hong Li, Zhining Liu, Hyunsik Yoo, Zhichen Zeng, Tianxin Wei, Hanghang Tong
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/fe84f64710552932e7df0b43d83ce526-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/fe84f64710552932e7df0b43d83ce526-Paper-Conference.pdf)
- **中文提要：** LoRA 向预训练模型注入可训练低秩矩阵以适配新任务，是一种参数高效微调。混合 LoRA 则把每层输入路由到该层一小部分专用 LoRA，从而高效扩展网络。
- **关键词：** LoRA, PEFT, fine-tuning

### Restoring Generalization in Fine-tuned Multimodal LLMs via Geometric Alignment

- **作者：** Lixuan He, Shikang Zheng, Guantao Chen
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/3d8f2fdc04fa66c9239f2eb14379546d-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/3d8f2fdc04fa66c9239f2eb14379546d-Paper-Conference.pdf)
- **中文提要：** 微调多模态大语言模型做下游任务时，需要在任务适应与保留广泛预训练能力之间取得平衡。全量微调常提高分布内表现却损害零样本行为，参数高效微调更稳定，却可能留下明显的适应差距。
- **关键词：** LoRA, PEFT, alignment, fine-tuning

### Rethinking Generalization in Reasoning SFT: A Conditional Analysis on Optimization, Data, and Model Capability

- **作者：** Qihan Ren, Wang Peng, Ruikun Cai, Shuai Shao, Dadi Guo, Yuejin Xie, Yafu Li, Quanshi Zhang, Xia Hu, Jing Shao, Dongrui Liu
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/96810b6d4752abe7bfb91f234c51e9e6-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/96810b6d4752abe7bfb91f234c51e9e6-Paper-Conference.pdf)
- **中文提要：** 大语言模型后训练中常见的说法是 SFT 偏向记忆、强化学习偏向泛化。对带长思维链监督的推理 SFT 重新审视后发现，跨域泛化并非缺失，而是有条件的，由优化动态、训练数据和基座能力共同塑造。
- **关键词：** SFT, post-training, fine-tuning

### RIMS: Preference Optimization via Smoothed Multi-pair Aggregation for Small-Scale LLM Retrieval-Augmented Generation

- **作者：** Pei Tian, Zihan Dong, Tianci Liu, Linjun Zhang, Haoyu Wang
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/427048354ac2db22d43149c51346bafd-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/427048354ac2db22d43149c51346bafd-Paper-Conference.pdf)
- **中文提要：** 小规模语言模型适合资源受限场景下的检索增强生成，但容量有限，对噪声或虚假检索证据非常敏感。RoseRAG 等偏好方法只用硬 argmin 或 argmax 选出最难的单对偏好并丢弃其余信号，另一些方法则把多对当作相互独立。
- **关键词：** preference-optimization, alignment

### Rubrics to Tokens: Bridging Response-level Rubrics and Token-level Rewards in Instruction Following Tasks

- **作者：** Tianze Xu, Yanzhao Zheng, Pengrui Lu, Lyumanshan Ye, Yong Wu, Zhentao Zhang, Yuanqiang Yu, Chao Ma, Jihuai Zhu, Pengfei Liu, Baohua Dong, Hangcheng Zhu, Ruohui Huang, Gang Yu
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/ae0509bfd3e0c2414164209949708e4e-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/ae0509bfd3e0c2414164209949708e4e-Paper-Conference.pdf)
- **中文提要：** 基于量规的强化学习被用来让大语言模型对齐复杂、开放域的指令遵循任务。现有方法主要依赖回答级奖励，因而带来严重的奖励稀疏和奖励含糊。
- **关键词：** GRPO, instruction-following, alignment

### Safe Inference-Time Alignment via Lagrangian Reward Augmentation

- **作者：** Yaswanth Chittepu, Ativ Joshi, Sohini Chintala, Scott Niekum
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/bd6bb13e78da078d8adcabbe6d9ca737-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/bd6bb13e78da078d8adcabbe6d9ca737-Paper-Conference.pdf)
- **中文提要：** 推理时对齐在解码阶段用辅助奖励信号引导冻结的语言模型，从而避开反复更新权重的开销。现有推理时对齐方法通常只优化单一标量分数，显式安全约束要么被忽略，要么靠手工调节的惩罚来编码。
- **关键词：** reward-model, alignment, fine-tuning

### Se-DPO: Self-Evolving Token Credit for Direct Preference Optimization

- **作者：** Wenxiao Zhao, Shu Wang, Ying Nian Wu
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/d722ae8bac16e0df9ac736c512860202-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/d722ae8bac16e0df9ac736c512860202-Paper-Conference.pdf)
- **中文提要：** DPO 用均匀求和汇总词元级对数概率比，隐含地认为所有词元对偏好信号贡献相同。实际上，单个词元对偏好信号的贡献并不一样。
- **关键词：** DPO, preference-optimization

### Spillover-Aware Multi-Value Steering for Pluralistic LLM Alignment

- **作者：** Weici Pan, Xander Barron, Jiawei Zhou, Zhenhua Liu
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/d0865cbe51d35ec322f9af9db7806fc7-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/d0865cbe51d35ec322f9af9db7806fc7-Paper-Conference.pdf)
- **中文提要：** 激活导向在推理时把学到的方向加到隐藏状态上以控制大语言模型行为，但现有方法一次只处理一个概念。多元对齐要求不同利益相关者有不同的价值侧重，因此需要同时引导多个维度。
- **关键词：** reward-model, alignment, fine-tuning

### Synthesizing Instruction-Tuning Datasets with Contrastive Decoding

- **作者：** Tatsuya Ichinose, Youmi Ma, Masanari Oi, Ryuto Koike, Naoaki Okazaki
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/7e49642375e3315467fa33120813547f-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/7e49642375e3315467fa33120813547f-Paper-Conference.pdf)
- **中文提要：** 用高性能大语言模型生成的回答做指令微调，已成为广泛采用的做法。现有文献忽略了这些回答的一个性质：它们把预训练获得的世界知识与后训练获得的指令遵循能力混在一起。
- **关键词：** instruction-tuning, instruction-following, post-training

### Towards Active Synthetic Data Generation for Finetuning Language Models

- **作者：** Samuel Kessler, Menglin Xia, Daniel Madrigal, Dongge Han, Helia Hashemi, Saravan Rajmohan, Victor Rühle, Jordan T Ash
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/46516c4204d6cab8299e55d4ebf7ccec-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/46516c4204d6cab8299e55d4ebf7ccec-Paper-Conference.pdf)
- **中文提要：** 提升语言模型能力的常见有效做法，是让学生模型在更强教师模型的生成结果上微调参数。这类称为合成数据的生成通常在学生开始微调之前就准备好，也有工作考虑随着训练推进再生成新的合成样本。
- **关键词：** fine-tuning

### Train Separately, Merge Together: Modular Post-Training with Mixture-of-Experts

- **作者：** Jacob Morrison, Sanjay Adhikesaven, Akshita Bhagia, Matei Zaharia, Noah Smith, Sewon Min
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/417ee785c6f0111ab5ea8907b1d24eb2-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/417ee785c6f0111ab5ea8907b1d24eb2-Paper-Conference.pdf)
- **中文提要：** 在已经完整后训练的语言模型上扩展新领域能力，受限于单体训练范式：从头重训昂贵且难以扩展，继续训练又常常损害已有能力。BAR（Branch-Adapt-Route）分别训练独立的领域专家，每个专家经历各自的中期训练、监督微调和强化学习。
- **关键词：** SFT, mid-training, post-training, fine-tuning

### Uniform Information Density-Based Preference Optimization

- **作者：** Yongyuan Li, Yang Xu
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/50d277e84b2bcbaadcd84548a87e8cc4-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/50d277e84b2bcbaadcd84548a87e8cc4-Paper-Conference.pdf)
- **中文提要：** 为让大语言模型生成符合人类偏好的输出，基于选中与拒绝输出对比较的优化算法已被证明有效。近期一些工作利用关于偏好对的语言学假设，来设计更精确的优化方向。
- **关键词：** SimPO, preference-optimization, alignment

### Weightless Fine-Tuning: Personalizing LLMs via Logit-Space Transport

- **作者：** Bohan Zhang, Anqi Ni, Yixin Wang, Paramveer Dhillon
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/708e0d691a22212e1e373dc8779cbe53-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/708e0d691a22212e1e373dc8779cbe53-Paper-Conference.pdf)
- **中文提要：** SFT 是把大语言模型适配到目标分布的常规做法，但在个性化这类每位作者都需要单独权重访问、优化、存储和再训练的场景里，其成本变得难以承受。Weightless Fine-Tuning（WFT）是一种免训练的解码时方法，在不更新权重的情况下逼近 SFT 的分布效果。
- **关键词：** SFT, fine-tuning

### When Contextual Inference Fails: Cancelability in Interactive Instruction Following

- **作者：** Natalia Bila, Kata Naszadi, Alexandra Mayn, Christof Monz
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/892895fdeba45acd837f1a861a4a30aa-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/892895fdeba45acd837f1a861a4a30aa-Paper-Conference.pdf)
- **中文提要：** 在协作搭积木任务中，研究把字面理解与语境推断分开来看，智能体需要借助上下文消解欠指定的指令。已有的双说话者心理语言学范式被改写成名为 Build What I Mean（BWIM）的交互基准。
- **关键词：** instruction-following

### Why Fine-Tuning Encourages Hallucinations and How to Fix It

- **作者：** Guy Kaplan, Zorik Gekhman, Zhen Zhu, Yuval Reif, Lotem Rozner, Swabha Swayamdipta, Derek Hoiem, Roy Schwartz
- **会议：** COLM 2026 · Main · Poster
- **官方论文页：** https://proceedings.colm.cc/paper_files/paper/2026/hash/f832f6d70ea73779369142dac61a389f-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.colm.cc/paper_files/paper/2026/file/f832f6d70ea73779369142dac61a389f-Paper-Conference.pdf)
- **中文提要：** 大语言模型容易生成事实不正确的陈述。这类错误的一个主要来源是通过 SFT 接触新的事实信息，而这会增加幻觉。
- **关键词：** SFT, fine-tuning
