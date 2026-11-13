# 2026 · EMNLP

共 306 篇。Main 171，Findings 135，其他赛道 0。其中 0 篇来源题录无摘要，提要标明「仅根据标题概括」。

检索窗口为 2024-11-13 至 2026-11-13。题录信息来自官方列表，不在此增补作者、链接或实验数字。

## Main

### ACE: Adapter Consolidation across Experts for Parameter-Efficient Fine-Tuning of MoE LLMs

- **作者：** Ahin Lee, Sehyun Yun, Joonha Park, Taesik Gong
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.2580/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.2580.pdf)
- **中文提要：** 混合专家模型的 PEFT 通常给每个专家单独挂一个低秩适配器。这种按专家拆分的设计从三方面割裂适配：容量被分到狭窄的低秩更新上，稀疏路由下梯度监督变得稀疏且不均衡，执行也被拆成许多小型矩阵乘。
- **关键词：** LoRA, PEFT, fine-tuning

### Agentic Reinforcement Learning for Search Misaligns Instruction-Tuning

- **作者：** Yushi Yang, Shreyansh Padarha, Sarah Ball, Andrew Lee, Adam Mahdi
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.2440/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.2440.pdf)
- **中文提要：** 智能体强化学习训练大语言模型使用工具，但它对对齐的影响仍不清楚。该工作考察面向搜索的智能体强化学习如何影响已经过指令微调的模型的对齐。
- **关键词：** instruction-tuning, alignment

### A Gradient Perspective on RLVR Stability and Winner-Advantage Policy Optimization

- **作者：** Prasanth Yss, Zhichen Ren, Rasa Hosseinzadeh, Ilan Gofman, Yuqi Chen, Zhaoyan Liu, Guangwei Yu, Jesse C. Cresswell, Satya Krishna Gorti
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.2371/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.2371.pdf)
- **中文提要：** 带可验证奖励的强化学习能改进语言模型推理，但 GRPO 式优化仍然容易崩溃。这项分析从词元级梯度动态看待这种不稳定，并导出一套分类，用来预测更新如何影响下一词元概率和熵。
- **关键词：** GRPO, RLVR

### ALIGNBEAM : Inference-Time Alignment Transfer via Cross-Vocabulary Logit Mixing

- **作者：** Chirag Chawla, Pratinav Seth, Vinay Kumar Sankarapu
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.2655/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.2655.pdf)
- **中文提要：** 摘要从半句开始：经过微调的专用模型很容易顺从用领域语言表述的有害提示。现有推理时防御会混合安全锚模型的对数几率，但要求两个模型共用词表，因此无法用于安全性退化最严重的跨家族专用模型。
- **关键词：** alignment, fine-tuning

### Alignment or Formatting? Dissecting What On-Policy DPO Actually Learns

- **作者：** Keyu Wen, Yang Song, Lijun Yang, Rui Lin
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.2566/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.2566.pdf)
- **中文提要：** 在策略上的直接偏好优化常用留出成对准确率和大模型评审胜率来衡量，但这两类指标可能在奖励不同行为。受控消融显示，能改善对数概率偏好探针的干预未必让被评审的生成更好，赢得生成评审的干预也未必改善该探针。
- **关键词：** DPO, instruction-following, preference-optimization, alignment

### AlphaToken: Decoupling Adaptation and Stability for Path-Aware Response Token Valuation in LLM Post-Training

- **作者：** Qing Liu, Ou Wu, Yi Du
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.866/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.866.pdf)
- **中文提要：** 词元选择对大语言模型后训练至关重要，可现有方法大多依赖局部词元级启发式。后训练中的回复词元选择，仍缺少由优化过程引导的价值代理。
- **关键词：** preference-optimization, post-training, fine-tuning

### An Embarrassingly Simple Data Selection Strategy for Million-Scale Multi-Modal Instruction-Tuning

- **作者：** Mengyao Lyu, Yan Li, Huasong Zhong, Hui Chen, Jungong Han, Guiguang Ding, Zhenheng Yang
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.2380/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.2380.pdf)
- **中文提要：** 预训练语言模型做指令微调时，少量但经过精心筛选的数据往往就够用。多模态模型还要面对更大的数据量、异质来源和跨模态对齐，数据选择因此既更必要也更复杂。
- **关键词：** instruction-tuning, alignment

### An Empirical Study on Preference Tuning Generalization and Diversity Under Domain Shift

- **作者：** Constantinos Karouzos, Xingwei Tan, Nikolaos Aletras
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.508/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.508.pdf)
- **中文提要：** 偏好调优借助显式偏好信号，而不是只优化似然，使基座语言模型贴近人类对质量、有用性或安全性的判断。已有研究表明，这种调优会在训练域之外降低表现并削弱有用性。
- **关键词：** SFT, preference-optimization, alignment, fine-tuning

### AnyAudio-Judge: A Dynamic Rubric-Based Benchmark and Evaluator for Audio Instruction Following

- **作者：** Haitao Li, Tian Tan, Yang Yuguang, Shan Yang, Xie Chen
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1249/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1249.pdf)
- **中文提要：** 指令引导的音频生成进展很快，稳健的对齐评测随之变得关键。现有自动评测严重依赖通用大语言模型的整体打分，既难拆解复杂指令、缺乏可解释性，也捕捉不到细粒度的属性错配。
- **关键词：** GRPO, SFT, instruction-following, alignment, fine-tuning

### AP-GRPO: Anchor-Gated Phonetic Alignment with Policy Optimization for Pathological Speech Reconstruction

- **作者：** Pengfei Zhang, Hoang H Nguyen, Yutong Song, Wenjun Huang, Tahmid Imtiaz Imu, Henry Peng Zou, Jiang Wu, Honghui Xu, Amir M. Rahmani
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1287/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1287.pdf)
- **中文提要：** 神经退行与神经运动障碍患者的病理性语音往往声学失真、语言破碎，重建工作要从残缺录音中恢复说话人原本想表达的文本。这类录音很少均匀劣化，仍有一些词语或短语音段可靠，可以充当可听锚点。
- **关键词：** GRPO, alignment

### Attention Amnesia in Hybrid LLMs: When CoT Fine-Tuning Breaks Long-Range Recall, and How to Fix It

- **作者：** Xinyu Zhou, Boyu Zhu, Yi Xu, Zhiwei Li, Yingfa Chen, Huiming Wang, Zhijiang Guo
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.816/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.816.pdf)
- **中文提要：** 思维链监督微调被广泛用来提升推理，却会系统性地损害混合线性注意力模型的长上下文回忆。在 HypeNet、Jet-Nemotron 等架构上，CoT-SFT 之后大海捞针式检索明显变差，检索更难时退化更严重。
- **关键词：** SFT, fine-tuning

### Audio-Reward-R1: Reasoning Reward Model for Unified Audio Understanding and Generation

- **作者：** Hao Gu, Xiaocheng Yang, Jinyang Wu, Hongbo Zhao, Yunzhe Hao, Songcheng Xu, Ye Bai, Zhao You, Shidong Shang
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.144/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.144.pdf)
- **中文提要：** 多模态奖励模型是把多模态大语言模型对齐到人类偏好的关键环节。现有奖励模型可解释性有限，在以音频为中心的场景里也难以做出可靠的偏好判断。
- **关键词：** SFT, reward-model, alignment, fine-tuning

### Automatic Configuration of LLM Post-Training Pipelines

- **作者：** Channe Chwa, Xinle Wu, Yao Lu
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.2324/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.2324.pdf)
- **中文提要：** 结合监督微调与强化学习的大语言模型后训练流水线，很难在现实算力预算下配好：配置空间高维且异质，各阶段强耦合，每次端到端评估又很昂贵。AutoPipe 提出一种预算感知的两阶段框架，用于选择后训练配置。
- **关键词：** SFT, post-training, fine-tuning

### Axis-LoRA: Probing and Adapting Embedding Models for Personal-Memory Retrieval

- **作者：** Dohoon Kim, Junho Park, Hyunwoong Bae, Seyoon Kim, Taesup Moon
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.542/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.542.pdf)
- **中文提要：** 当大语言模型被问到用户的个人经历时，检索需要按时间、地点、人物和事件把记忆区分开。现有个人记忆流程依赖冻结的稠密嵌入模型，而这些轴并没有被很好地表示。
- **关键词：** LoRA

### BalancedBio: Mitigating the Alignment Tax in Biomedical LLMs via Gradient Orthogonality and GRPO

- **作者：** Wentao Wu, Hanmeng Zhong, Linqing Chen, Peng Zhou
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.2556/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.2556.pdf)
- **中文提要：** 把大语言模型对齐到专门领域会遇到对齐税。在生物医学中，它表现为严谨的百科式事实准确性与灵活、易用的指令跟随之间的冲突；现有方法主要依赖监督微调或标准强化学习。
- **关键词：** GRPO, RLHF, SFT, instruction-following, alignment, fine-tuning

### Bayesian Sparse Low-Rank Adaptation for Large Language Model Uncertainty Estimation

- **作者：** Jijie Zhang, Zhe Ren, Quan Zhang, Dandan Guo
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.328/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.328.pdf)
- **中文提要：** 大语言模型推理能力突出，但任务微调常常过度自信，严重妨碍可信部署。DALorRA 是一种变分贝叶斯稀疏框架，试图把不确定性量化从稠密参数空间转到更轻量的参数上。
- **关键词：** LoRA, fine-tuning

### Benchmarking Bengali Dialectal Bias: A Multi-Stage Framework Integrating RAG-Based Translation and Human-Augmented RLAIF

- **作者：** K. M. Jubair Sami, Dipto Sumit, Ariyan Hossain, Farig Sadeque
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.9/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.9.pdf)
- **中文提要：** 大语言模型经常对低资源语言的地域方言表现有偏。用来量化这类差距的框架却仍然稀缺。
- **关键词：** RLAIF

### Beyond Adapter Expansion: Packing Multiple Tasks into Spare LoRA Capacity

- **作者：** Shuangjie Fan, Chengxiang Huang, Zhiyuan Zhao, Piotr Koniusz, Junyu Gao, Di Hu
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1570/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1570.pdf)
- **中文提要：** 不少持续学习方法靠增加任务专用模块来减轻遗忘，显存成本却随任务数上升。研究发现单个 LoRA 适配器含有可观的逐任务参数冗余，只保留 LoRA-B 的一小部分条目，就能挽回绝大部分任务精度。
- **关键词：** LoRA

### Beyond SFT-Optimality: Cold-Start Data Selection for Reinforcement Learning via Gradient Subspace Coverage

- **作者：** Haisheng Lv, Zikun Su, Jingbang Liu, Zilu Huang, Xinzhang Liu, Wenmin Deng, Yu Zhao, Chao Wang, Shuangyong Song
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.513/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.513.pdf)
- **中文提要：** 冷启动监督微调是可验证奖励强化学习之前的关键初始化。现有冷启动数据选择大体沿用监督指令微调的准则，如样本质量、难度、困惑度或多样性，并默认更强的 SFT 热身也是更好的强化学习起点。
- **关键词：** RLVR, SFT, instruction-tuning, fine-tuning

### Beyond Shallow Alignment: How Post-Training Methods Determine Refusal Circuits And Steering Robustness

- **作者：** Hoang Cuong Nguyen, Mark Dras, Usman Naseem
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.2057/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.2057.pdf)
- **中文提要：** 训练语言模型拒绝有害请求时所采用的后训练方法，会怎样决定拒绝在模型内部如何运作？比较对象包括监督微调、在论证安全决策的推理链上进行的推理增强微调，以及偏好优化方法 ORPO，并覆盖结构各异的模型。
- **关键词：** ORPO, SFT, preference-optimization, post-training, alignment, fine-tuning

### Beyond Task Boundaries: Instruction-Level Parameter Isolation for Supervised Fine-Tuning

- **作者：** Zekai Lin, Long Xiang, Di Liang, Peiyang Liu, Zhanghao Hu, Mengze Hong, Xianjie Wu, Minlong Peng
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.287/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.287.pdf)
- **中文提要：** 当代监督微调把大语言模型放在异质指令混合上训练，实际优化单位是单条指令—回复对，而不是粗粒度任务标签。现有参数隔离在任务或训练阶段划分受保护或可训练子空间，这些单位常常与真实的优化对象错位。
- **关键词：** SFT, instruction-tuning, fine-tuning

### CARE: Contrastive Anchor-based Rubric Evolution for Large Language Model Post-Training

- **作者：** Siyuan Li, Xinxin Song, Chen Ruinian, Jingjing Fan, Tingxiong Xiao, Yangen Hu, Ke Zeng, Jinli Suo
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1992/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1992.pdf)
- **中文提要：** 基于量规的强化学习把开放指令分解为随提示变化的灵活量规，因而比可验证奖励强化学习更适合开放任务上的后训练。静态量规会随着策略演进而被钻空，现有动态方案又带来无方向的量规抽取、不可靠的钻空检测等问题。
- **关键词：** post-training

### Charting Empirical Patterns for LLM Fine-Tuning in Scientific Multi-Discipline Learning

- **作者：** Lintao Wang, Zhuqiang Lu, Yilin Zhu, Kun Hu, Zhenfei Yin, Shixiang Tang, Zhiyong Wang, Wanli Ouyang, Xinzhu Ma
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.312/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.312.pdf)
- **中文提要：** 大语言模型在单一科学领域内适配后往往很强，多学科情境中的学习动态却仍不清楚，尽管跨领域知识协同有望改善泛化并拓宽适用面。一项系统研究考察了跨多个科学学科的微调。
- **关键词：** instruction-following, LoRA, fine-tuning

### Chronos: Chronology-Grounded Continued Pre-training for Language Model Adaptation to Materials Science

- **作者：** Sangyun Kim, Junho Kim, SangKeun Lee
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.2341/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.2341.pdf)
- **中文提要：** 在领域语料上继续预训练，已成为把预训练语言模型适配到材料科学的主流路径。现有策略通常把科学文献当作相互独立的样本，因而忽略科学知识的累积性：新发现是系统建立在先前研究之上的。
- **关键词：** continued-pretraining

### Clustering-Based Balanced Sampling and Allocation with Data Parallelism for High-Performance Fine-Tuning

- **作者：** Hyunjin Kim, Youngeun Nam, Jaemin Han, Wonhyeok Choi, Jae-Gil Lee
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.342/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.342.pdf)
- **中文提要：** 指令微调数据集往往庞大、冗余且不平衡，妨碍大语言模型高效适配。若直接用于大批量微调，过度代表的样本组会被反复纳入，代表性不足但有信息量的样本则覆盖很弱；实践中的大批量训练通常借助数据并行完成。
- **关键词：** instruction-tuning, fine-tuning

### CoDe-LoRA: Mitigating the Orthogonality Dilemma in Continual Learning of LLMs via Knowledge Consolidation and Decoupling

- **作者：** Maoqi Liu, Quan Fang, Yufei He
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1188/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1188.pdf)
- **中文提要：** 持续学习对大语言模型依次适应不断变化的任务必不可少。为缓解灾难性遗忘，近期工作采用带正交投影的低秩适配（例如 O-LoRA）来隔离各任务参数。
- **关键词：** LoRA

### Cognitive-Level Prefix-MoE Reward Modeling for Curriculum Alignment of Medical Language Models

- **作者：** Hao Wang, Wendi Feng, Chun Kang, Yanting Wang, Rui Li, Lei Sha
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.611/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.611.pdf)
- **中文提要：** 医学语言模型日益按开放式临床推理来评测，合格回答需要兼具事实回忆、证据整合、决策与综合。标准奖励模型把这些不同标准压成一个分数，而带答案键的医学强化学习主要奖励选择题是否正确。
- **关键词：** GRPO, reward-model, alignment

### CoMerge: Conflict-Driven Preference Optimization for Multi-Task Model Merging

- **作者：** Mingjie Zheng, Zihao Chen, Wenqing Chen, Weile Yuan, Zhixuan Chu, Jianxing Yu, Zibin Zheng
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1281/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1281.pdf)
- **中文提要：** 模型合并提供了一种无需完整重训即可构建多任务大语言模型的途径，但仍受参数干扰制约。现有方法着力保留各专家模型的能力并减轻干扰，一般却不直接从朴素合并所暴露的退化行为中学习。
- **关键词：** instruction-following, preference-optimization, fine-tuning

### ConsensusBench: Benchmark of Consensus Nodes for LLM Reasoning via Outcome Reward Densifying

- **作者：** Shi-Qi Yan, Chao-Hong Tan, Qian Chen, Wen Wang, Xiangang Li, Zhen-Hua Ling
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.818/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.818.pdf)
- **中文提要：** 强化学习已成为增强大语言模型推理的主要范式之一。GRPO 及相关算法借助结果级奖励已经展现出较强表现。
- **关键词：** GRPO, PRM

### Consensus Group Relative Policy Optimization for Text Generation

- **作者：** Yuki Ichihara, Yuu Jinnai, Kaito Ariu, Eiji Uchibe
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1459/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1459.pdf)
- **中文提要：** 许多强解码方法遵循采样再重排：生成多个候选，借助样本间共识在效用函数下打分，再选出最好的一个。它们虽然有效，推理阶段却因反复采样和打分而计算开销很高。
- **关键词：** GRPO, reward-model

### Continuous-Utility Direct Preference Optimization

- **作者：** Muhammad Ahmed Mohsin, Muhammad Umer, Emily Fox
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.2410/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.2410.pdf)
- **中文提要：** 大语言模型的推理常被当成铁板一块的能力，二元偏好监督捕捉不到部分进展或细粒度的推理质量。CU-DPO 用连续分数替换二元标签，使模型对齐到一组基于提示的认知策略组合。
- **关键词：** DPO, preference-optimization

### CoPRM: A Collaborative Process Reward Model for Guiding Search Agent Reasoning

- **作者：** Xingquan Zhang, Yang Zhao, Chong Li, Donglei Yu, Pu Jian, Chengqing Zong
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.65/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.65.pdf)
- **中文提要：** 基于大语言模型的搜索智能体通过交错进行推理与检索，在知识密集型任务上表现更优。过程奖励模型可以在推理期间引导步骤选择，从而提升这类智能体。
- **关键词：** PRM, reward-model

### Countdown-Code: A Testbed for Studying The Emergence and Generalization of Reward Hacking in RLVR

- **作者：** Muhammad Khalifa, Zohaib Khan, Omer Tafveez, Hao Peng, Lu Wang
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1902/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1902.pdf)
- **中文提要：** 奖励投机是一种错位：模型过度优化代理奖励，却并未真正解决底层任务。要精确测量它仍然困难，因为真实任务奖励往往代价高昂，甚至无法计算。
- **关键词：** RLVR, SFT, fine-tuning

### Counterfactual Constraint-Conditioned On-Policy Distillation for Multi-Constraint Instruction Following

- **作者：** Yanzhao Zheng, Yuanqiang Yu, Tianze Xu, Chao Ma, Zhentao Zhang, Jihuai Zhu, Baohua Dong, Hangcheng Zhu, Ruohui Huang
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1037/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1037.pdf)
- **中文提要：** 多约束指令跟随要求模型在许多同时生效的约束下回应查询。即便较强的指令微调模型，也仍会经常违反其中一部分约束。
- **关键词：** instruction-tuning, instruction-following

### CRAM: Centroid-Routing and Adaptive MoE for Multimodal Continual Instruction Tuning

- **作者：** Jun-Tao Tang, Zhen-Hao Xie, Yu-Cheng Shi, Da-Wei Zhou
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1175/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1175.pdf)
- **中文提要：** 多模态大语言模型通过指令微调，把异质的视觉语言任务统一到共享的生成框架中，而真实部署要求能力持续扩展，使多模态持续指令微调成为必要。现有方法要么用共享参数更新全部任务，要么为每个新任务分配专用模块。
- **关键词：** instruction-tuning

### Cross-Modal Emergent Misalignment Through Narrow-Domain Fine-Tuning

- **作者：** Han Zhu, Chengkun Cai, Pengcheng Wen, Yanxu Zhu, Jagmohan Chauhan, Lei Li, Yike Guo, Sirui Han
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.2241/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.2241.pdf)
- **中文提要：** 人工智能的快速进展把安全关切推到了研究前沿。近期研究表明，大语言模型在训练过程中可能出现涌现式错位：一旦接触狭窄领域的有害数据，就会在广泛且不相关的任务上产生不安全行为。
- **关键词：** alignment, fine-tuning

### Cross-Version $\Delta$-Transfer of QLoRA-Trained Adapters

- **作者：** Yoshiki Kubota, Hirotada Honda, Takashi Sano, Shugo Nakamura
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1332/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1332.pdf)
- **中文提要：** 为检验 QLoRA 训练的适配器能否像 LoRA 适配器一样跨模型版本迁移，研究者在 Llama-3-8B-Instruct 上训练这两类适配器，再以任务相关的合并尺度迁到 Llama-3.1-8B-Instruct。两种方法都在 BF16 目标基座上评估，从而隔离训练时的精度差异，NF4 部署则另行评估。
- **关键词：** QLoRA, LoRA

### CulturePRM: A Process Reward Model for Mitigating Cultural Overriding in Cultural Reasoning

- **作者：** Ji-Eun Han, Yoonseok Heo
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1228/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1228.pdf)
- **中文提要：** 大型推理模型会在给出最终答案前产出显式推理轨迹，但其在有文化根基的推理中如何表现仍不够清楚。文中识别出文化覆盖这一逐步失败：模型起初认出相关的地方文化规范，随后又削弱或换成更一般的规范框架，最终做出错误判断。
- **关键词：** PRM, reward-model

### DataShield: Uncovering Risky Fine-Tuning Data Across LLMs Through Consensus Subspace Alignment

- **作者：** Zefeng Wu, Weiwei Qi, Jielong Chen, Tianhang Zheng, Di Hong, Chaochao Lu, Liang He, Zhan Qin, Kui Ren
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1941/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1941.pdf)
- **中文提要：** 在领域数据集上微调，已成为把大语言模型适配到专门应用的标准范式。近期工作表明，即便微调数据是良性的任务数据，也可能明显削弱模型的安全能力。
- **关键词：** alignment, fine-tuning

### Deeper is Not Always Better: Mitigating the Alignment Tax via Confident Layer Decoding

- **作者：** Sining Zhoubian, Xuanming Zhang, Yuxuan Chen, Tianyi Tang, An Yang, Sean Du, Chujie Zheng, Fei Huang, Dayiheng Liu, Gao Huang, Jingren Zhou
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1086/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1086.pdf)
- **中文提要：** 大语言模型的自回归生成习惯从最后一层解码，并假定更深的表示能带来更可靠的下一词预测。反复出现的动态是浅层形成粗略猜测，中间层精炼与推理相关的语义，末层则可能扰动这些已经精炼的内容。
- **关键词：** alignment

### DenseMixer: Improving MoE Post-Training via Precise Router Gradient

- **作者：** Feng Yao, Junxia Cui, Ruohan Zhang, Liyuan Liu, Shibo Hao, Li Zhang, Chengyu Dong, Churan Zhi, Shuohang Wang, Yelong Shen, Jianfeng Gao, Jingbo Shang
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1682/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1682.pdf)
- **中文提要：** 混合专家模型中广泛采用的 Top-K 路由在数学上不可微，因而比稠密模型更难训练。DenseMixer 是一种简洁的后训练技术，以额外计算换取更精确的路由器梯度估计。
- **关键词：** instruction-tuning, LoRA, PEFT, post-training, fine-tuning

### Dense Process Supervision for Search Agents via Fact Utility Estimation

- **作者：** Rongzhi Zhu, Xiangyu Liu, Yi Liu, Shuo Zhang, Ruirui Zhang, Rui Wu, Tao Jiang, Zequn Sun, Wenhao Xu, Wei Hu
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1050/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1050.pdf)
- **中文提要：** 面向搜索智能体的强化学习通常依赖结果奖励。由于中间步骤的价值并不清楚，它往往无法做好信用分配。
- **关键词：** LLM fine-tuning / post-training

### DIPLOMAT: Dialogue-Span-Aware Direct Preference Optimization for Polite Persuasive Workplace Negotiation Dialogues

- **作者：** Bibhuti Jha, Rishikant Chigrupaatii, Priyanshu Priya, Asif Ekbal
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.2627/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.2627.pdf)
- **中文提要：** 有效的职场谈判需要在完成任务目标、维护职业关系和建设性化解冲突之间取得平衡。误解、偏好不一致以及人际摩擦却常常阻碍顺利达成结果。
- **关键词：** DPO, preference-optimization, alignment

### Direct Diversity Optimization for Diverse Successful Trajectories in Preference Post-Training

- **作者：** Junwon Ko, Dong-Jae Lee, Minchan Kwon, Sunghyun Baek, Junmo Kim
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1738/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1738.pdf)
- **中文提要：** 序列决策任务中的大语言模型智能体常用轨迹级结果标签做后训练，这类标签却几乎不能监督模型保留同一决策状态下的多条成功分支。该问题被表述为成功策略覆盖：在固定的展开预算下，模型能实现多广的不同成功策略。
- **关键词：** post-training

### Divide-and-Adapt: Fine-Tuning VLMs via Model Division and Routing

- **作者：** Hailing Wang, Neil Rodrigues, Xianglong Wang, Wei Li, Lin Chen, Yun Fu
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.615/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.615.pdf)
- **中文提要：** 微调视觉语言模型是适配预训练模型以服务下游任务的常见做法。现有微调却始终保持预训练架构不变，维持这种结构完整是否真为有效适配所必需，仍然是个开放问题。
- **关键词：** PEFT, fine-tuning

### Does Fine-Tuning Undo Activation Steering? Behavioural Recovery Without Weight-Edit Reversal

- **作者：** Philipp E. Glass, Allan Tucker, Yongmin Li, Alina Miron
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.567/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.567.pdf)
- **中文提要：** 激活引导可以直接嵌入语言模型权重，无需推理时干预即可塑造行为，也为发布前写入对齐提供了途径。模型在部署后却经常继续微调，这些嵌入式干预能否经受住微调尚不清楚。
- **关键词：** RLHF, SFT, instruction-tuning, alignment, fine-tuning

### Does Finetuning with Scientific Data Increase Hallucinations? A Multi-domain Factuality Evaluation of LLMs

- **作者：** Raia Abu Ahmad, Nikolas Rauscher, Ekaterina Borisova, Fabio Barth, Georg Rehm, Sebastian M{\"o}ller
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.610/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.610.pdf)
- **中文提要：** 大语言模型越来越多地被用来传达和解释科学概念，幻觉在这种高风险场景中构成显著风险。以往科学幻觉评测大体局限于生物医学领域，把幻觉当作二元任务，也尚未考察日益增多的科学向微调模型。
- **关键词：** fine-tuning

### Don't Peek at the Answer: Outcome-Masked Group Relative Policy Optimization for Label-Free RLVR

- **作者：** Yongshi Ye, Liang Zhang, Yidong Chen, Xiaodong Shi, Biao Fu
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.2547/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.2547.pdf)
- **中文提要：** 可验证奖励的强化学习能改善大语言模型推理，但通常依赖标准答案，因而难以扩展。基于投票的无标签做法用模型样本在答案层面的共识取代金标准监督。
- **关键词：** GRPO, RLVR

### DSPA: Dynamic SAE Steering for Data-Efficient Preference Alignment

- **作者：** James Wedgwood, Aashiq Muhamed, Mona T. Diab, Virginia Smith
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.169/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.169.pdf)
- **中文提要：** 偏好对齐通常通过对偏好数据做更新权重的训练来实现，成本高，机制上也缺少可见性。DSPA 是一种推理时方法，使稀疏自编码器引导随提示而变化。
- **关键词：** preference-optimization, alignment

### Dual-View Training for Instruction-Following Information Retrieval

- **作者：** Qingcheng Zeng, Puxuan Yu, Aman Mehta, Fuheng Zhao, Rajhans Samdani
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.571/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.571.pdf)
- **中文提要：** 指令跟随信息检索要求检索器同时满足主题意图和随实例变化的相关性约束。双视图训练是一种基于极性反转的数据合成策略。
- **关键词：** instruction-following

### dwDPO: Training Multi-Turn LLM Agents via Divergence-Weighted Direct Preference Optimization

- **作者：** Jinghao Lin, Yuhang Wu, Yuanqing Wang, Yuchen Li, Tianxingjian Kang, Baris Coskunuzer, Xiawu Zheng
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.2406/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.2406.pdf)
- **中文提要：** 作为多步智能体部署的大语言模型，越来越多地在轨迹级比较上用 DPO 训练。标准 DPO 对每一步均匀加权，会把失败轨迹中早期的正确动作罚得与造成失败的那一步一样重。
- **关键词：** DPO, preference-optimization

### EST-PRM: Stress-Testing Process Reward Models Before They Become Load-Bearing

- **作者：** Ibne Farabi Shihab, Fariya Afrin, Sanjeda Akter, Anuj Sharma
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.778/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.778.pdf)
- **中文提要：** 过程奖励模型被广泛用于提供稠密的步骤级监督。它们假定：在改变推理结构、同时保留最终答案的标签保持变换下，分数仍能稳定地代理步骤是否正确。
- **关键词：** PRM, reward-model

### Evolutionary Soups: Evolving Mixture-of-Experts for Multi-Objective LLM Alignment

- **作者：** Lingxiao Kong, Steffen Staab, Cong Yang, Oya Beyan, Zeyd Boukhers
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.2381/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.2381.pdf)
- **中文提要：** 大语言模型越来越需要生成同时满足多个相互竞争目标的回答。最优折中既取决于用户偏好也取决于输入提示，因此可控的多目标生成必须在推理时动态调整模型，而不重新训练。
- **关键词：** alignment

### Examining Reasoning LLMs-as-Judges in Non-Verifiable LLM Post-Training

- **作者：** Yixin Liu, Yue Yu, DiJia Su, Sid Wang, Xuewei Wang, Song Jiang, Bo Liu, Arman Cohan, Yuandong Tian, Zhengxing Chen
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.2496/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.2496.pdf)
- **中文提要：** 能从推理时扩展中受益的推理型评审模型，为把推理模型的成功延伸到无法直接核验输出质量的领域提供了一条路径。这类评审在静态评测基准上已显示出增益，但对实际后训练的影响仍探索不足。
- **关键词：** post-training, alignment

### Expert Personas Improve LLM Alignment but Damage Accuracy: Bootstrapping Intent-Based Persona Routing with PRISM

- **作者：** Zizhao Hu, Mohammad Rostami, Jesse Thomason
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.14/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.14.pdf)
- **中文提要：** 人格提示可以把大语言模型的生成导向特定领域的语气和模式。这使其适用于需要多样交互的多智能体系统，以及要求高水平人类对齐的以人为中心的任务。
- **关键词：** instruction-tuning, LoRA, alignment

### Fair Like Us? Auditing LLM Alignment in Resource Allocation

- **作者：** Qishen Han, Hadi Hosseini, Joshua Kavner, Samarth Khanna, Sujoy Sikdar, Lirong Xia
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.620/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.620.pdf)
- **中文提要：** 稀缺且不可分割资源的公平分配，是许多社会问题中的重要挑战。形式化的公平理论有多种，但没有任何单一界定能够始终被满足。
- **关键词：** alignment, fine-tuning

### Fast-Slow Thinking RM: Efficient Integration of Scalar and Generative Reward Models

- **作者：** Jiayun Wu, Peng Zhang, Yuanyuan Lu, Shan Qu, Ning Gu, Tun Lu
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1526/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1526.pdf)
- **中文提要：** 奖励模型对于经由 RLHF 对齐大语言模型至关重要。生成式奖励模型通过思维链推理获得更高准确率，却带来相当大的计算成本。
- **关键词：** RLHF, reward-model, alignment

### F-GRPO: Don't Let Your Policy Learn the Obvious and Forget the Rare

- **作者：** Daniil Plyusov, Alexey Gorbatovski, Boris Shaposhnikov, Viacheslav Sinii, Alexey Malakhov, Daria Korotyshova, Daniil Gavrilov
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1411/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1411.pdf)
- **中文提要：** 可验证奖励强化学习常用组采样来估计优势并稳定策略更新。算力限制往往使很大的组不可行，训练只能在有限的展开集合上进行，因而可能只会强化这些样本已经暴露出的正确行为。
- **关键词：** GRPO, RLVR

### Finetune Once: Decoupling General \& Domain Learning with Dynamic Anchor Annealing

- **作者：** Yang Tang, Ruijie Liu, Yifan Wang, Shiyu Li, Peiming Li, Zheng Wei
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.2532/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.2532.pdf)
- **中文提要：** 在领域数据上微调大语言模型已是标准做法，但常规流程要靠代价很高的数据配比搜索来避免忘掉通用能力。动态锚点退火是一种全参数微调框架，在梯度层面而不是数据层面把通用学习与领域学习分开。
- **关键词：** fine-tuning

### Fine-Tuning for Social-Media User Simulation: A Study Across Models and Evaluators

- **作者：** （官方列表未给出完整作者，或解析后为空）
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.2251/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.2251.pdf)
- **中文提要：** 在用户的社交媒体历史上微调，能否让大语言模型更好地模拟该用户？研究用 QLoRA 来考察这一点：生成该用户的回复之前，模型会条件于其按时间排列的行为历史以及一条回复线程。
- **关键词：** QLoRA, fine-tuning

### First-Stage Groundwork Shapes Downstream RL Outcomes: Two-Stage Post-Training for LLM Personality Acquisition

- **作者：** Taisei Ozaki, Tetsuya Hashimoto, Miki Ota, Keisuke Hori, Zhenyu He, Mitsuhiro Mabuchi
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1983/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1983.pdf)
- **中文提要：** 稳定的人格是个人人工智能助手的关键要求，推理模型如何获得这类特质仍缺少探讨。现有工作多把人格当作角色扮演，并沿用推理模型的标准流程：先以监督微调热身，再进行可验证奖励强化学习。
- **关键词：** GRPO, RLVR, SFT, post-training

### From Rollouts to Recipes: Self-Contained Post-Training for LLMs

- **作者：** Yifei Li, Lingling Zhang, Muye Huang, Zihan Ma, Jiashuai Liu, Jun Liu
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.464/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.464.pdf)
- **中文提要：** 后训练大语言模型时，通常对全部样本使用同一种训练配方，尽管模型自己的展开已经揭示出不同的样本级学习状态。Self-Routing 是一种按行为条件化的框架，依据展开的正确性与置信度决定每个样本应当如何优化。
- **关键词：** GRPO, post-training

### From Specialization to Generalization: Instruction-tuned LLMs for Robust Harmful Content Mitigation

- **作者：** Lukas Edman, Daryna Dementieva, Alexander Fraser
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1643/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1643.pdf)
- **中文提要：** 大语言模型在广泛的一般自然语言任务上表现出色，但在仇恨言论检测等敏感领域是否同样有效仍不清楚。此前将提示式大语言模型与先进的编码器模型（如 BERT 变体）比较，只观察到有限的增益。
- **关键词：** instruction-tuning, fine-tuning

### From Unverifiable Domain Text to Cross-Lingual RLVR via Code-Switched Task Synthesis

- **作者：** Cheonbok Park, Jihwan Kim, Shinyoung Joo, Joosung Lee, Hwiyeol Jo, Jeonghoon Kim, Jaegul Choo
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1375/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1375.pdf)
- **中文提要：** 可验证奖励强化学习可以提升大语言模型的推理能力，但专门的非英语领域存在数据错配。英文领域原文往往容易获得，带可验证奖励的目标语言任务却很稀少。
- **关键词：** RLVR, alignment

### GAC: Noise-Aware Adaptive Mixing for Hybrid SFT-RL Post-Training

- **作者：** Yuelin Hu, Wei Liu, Zhenbo Yu, Zhengxue Cheng, Li Song
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.119/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.119.pdf)
- **中文提要：** 混合监督微调与强化学习的后训练里，固定混合日程无法跟着两路信号相对噪声的变化而调整。GAC 通过最小化混合随机梯度的均方误差上界，得到兼顾梯度噪声方差的闭式混合权重。
- **关键词：** SFT, post-training, alignment, fine-tuning

### Generalizable Lifelong Model Editing via Preference Optimization

- **作者：** Dahyun Jung, Suhyune Son, Heuiseok Lim
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.170/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.170.pdf)
- **中文提要：** 知识编辑可以在不全量重训的情况下快速改写模型里的特定事实，但更贴近现实的需求是持续不断地更新，而不是一次性修改。
- **关键词：** preference-optimization

### GIFT: Goal-Injected Fine-Tuning for Efficient Manipulation Policy Adaptation

- **作者：** Xiaoyuan Fang, Shuo Feng, Yuxuan Wang, Enhua Cheng, Peng Zhou, Piji Li
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.860/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.860.pdf)
- **中文提要：** 相比只依赖初始观测和语言指令，用生成模型预测目标图像作为高层视觉引导，可以增强视觉-语言-动作模型的稳健性。多数基础模型由于训练计算成本高，尚未系统引入目标图像条件。
- **关键词：** fine-tuning

### GRADFILTERING: Uncertainty-Aware Gradient Signal-to-Noise Data Selection for Instruction Tuning

- **作者：** Zhihang Yuan, Chengyu Yue, Long Huang, Litu Ou, Lei Shi
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.2297/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.2297.pdf)
- **中文提要：** 现代指令微调的数据混合又大又冗余、来源混杂，全量监督微调代价高，而且常常没有必要。GRADFILTERING 不绑定具体目标、也不使用验证集，借助带不确定性的代理训练动态为样本打分来筛选数据。
- **关键词：** SFT, instruction-tuning, LoRA, fine-tuning

### GradSentry: Gradient Spectral Entropy for Backdoor Sample Filtering in Large Language Model Fine-Tuning

- **作者：** Haodong Zhao, Tianyi Xu, Tianhang Zhao, Zhuosheng Zhang, Gongshen Liu
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.210/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.210.pdf)
- **中文提要：** 用不可信数据微调会使大语言模型暴露在后门攻击之下，有毒样本会诱发有针对性的错误行为。依赖聚类的样本过滤既需要足够多的数据，在极端投毒比例下还可能失效。
- **关键词：** LoRA, PEFT, fine-tuning

### GRRM: Group Relative Reward Modeling for Machine Translation

- **作者：** Sen Yang, Shanbo Cheng, Lu Xu, Jianbing Zhang, Shujian Huang
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.2283/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.2283.pdf)
- **中文提要：** 把 GRPO 用到机器翻译这类开放任务时，效果取决于组内排序是否准确。标准的逐点质量指标把候选译文孤立评估，缺少比较语境，因而难以分辨细粒度的语言差别。
- **关键词：** GRPO, reward-model, post-training

### GR-SAP: Generative Replay for Safety Alignment Preservation during Fine-Tuning

- **作者：** Zhouxiang Fang, Jiawei Zhou, Hanjie Chen
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.50/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.50.pdf)
- **中文提要：** 即便看起来并不对抗的微调，也很容易破坏大语言模型已有的安全对齐。常用补救是混入原始对齐数据、同时优化安全与任务目标，可这类数据对开源权重模型通常也不可得。
- **关键词：** alignment, fine-tuning

### GSPR: Aligning LLM Safeguards as Generalizable Safety Policy Reasoners

- **作者：** Haoran Li, Jingru Zeng, Yulin Chen, Huihao Jing, Wenbin Hu, Hao Peng, Haochen Shi, Xi Yang, Ziqian Zeng, Sirui Han, Yangqiu Song
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.315/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.315.pdf)
- **中文提要：** 大语言模型被接入大量应用之后，安全同时关系到开发者和预期使用者。围绕细粒度分类体系来建设安全基准，已经投入了相当多的努力。
- **关键词：** alignment

### GSR-LoRA:Group-Sparse Routing-aware Low-Rank Adapter Compression for Multi-Task Mixture-of-Experts Fine-Tuning

- **作者：** Weimin Cheng, Chengyu Zhao, Xuanjing Huang, Yatian Shen
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1540/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1540.pdf)
- **中文提要：** 多任务混合专家的参数高效微调中，固定秩的 LoRA 适配器难以兼顾不同任务和网络层对表示的异构需求。已有方法多集中在任务级专家选择、逐层秩分配或训练后的参数压缩，因而很难把低秩特性放到一起刻画。
- **关键词：** LoRA, PEFT, post-training, fine-tuning

### GUI-PRA: Process Reward Agents for GUI Tasks

- **作者：** Tao Xiong, Xueyu Hu, Yurun Chen, Yuhang Liu, Changqiao Wu, Pengzhi Gao, Wei Liu, Jian Luan, Shengyu Zhang
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1304/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1304.pdf)
- **中文提要：** 长程图形界面自动化会在拉长的交互序列里不断累积错误。过程奖励模型能提供稠密的步骤级监督来缓解这种累积，但标准过程奖励模型并不适合做图形界面上的校验。
- **关键词：** PRM, reward-model, alignment

### HarmoLoRA: Commit-Stage Update Admission in Low-Rank Adaptation for Continual Speech Recognition

- **作者：** Ye-Eun Ko, Ji-Eun Choi, Dong-Hyun Kim, Joon-Hyuk Chang
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.2631/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.2631.pdf)
- **中文提要：** 无回放的持续语音识别需要在没有旧数据、任务标识和推理时路由的前提下，用单一持久模型适应新的语音域。作者把提交阶段的更新准入看成持续 LoRA 的一类独立后训练问题：任务级 LoRA 更新训练完成之后，系统还要决定其中哪些部分可以接纳。
- **关键词：** LoRA, post-training

### HARVE: Hacking-Aware Reward-Head Vector Editing for Robust Reward Models

- **作者：** Shuang Liu, Yuxuan Bo, Qiuyang Zhao, Caiyue Huang, Xiaorong Chen, Yanguang Liu, Mengnan Du
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1095/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1095.pdf)
- **中文提要：** 奖励模型处于大语言模型对齐的中心，却仍然容易遭到奖励黑客攻击。HARVE 引入覆盖现实高风险领域与一般场景的奖励黑客评测，并在若干奖励模型的特定子类上观察到严重失效。
- **关键词：** reward-model, alignment, fine-tuning

### HLoRA: Hierarchical Regularization on Combined Parameter Space for LoRA Fine-Tuning

- **作者：** Shezheng Song, Hao Xu, Long Peng, Xiaopeng Li, Shasha Li, Jie Yu
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1104/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1104.pdf)
- **中文提要：** LoRA 被广泛用于微调大语言模型，但会带来灾难性遗忘。已有持续学习方法缓解遗忘时，通常是各自独立地估计每个参数的重要性。
- **关键词：** LoRA, fine-tuning

### How Do Large Language Models Learn Concepts During Continual Pre-Training?

- **作者：** Barry Menglong Yao, Sha Li, Yunzhi Yao, Minqian Liu, Zaishuo Xia, Qifan Wang, Lifu Huang
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.2437/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.2437.pdf)
- **中文提要：** 人理解世界主要依靠概念，也就是用来组织感知、推理和学习的抽象心理表征。大语言模型在持续预训练中如何获得、保留并遗忘这类概念，目前仍缺乏清楚的认识。
- **关键词：** continued-pretraining

### How Much Supervised Fine-Tuning Is Enough? Dissecting the Impact of SFT Extent on Downstream Reinforcement Learning Performance

- **作者：** Shirley Kokane
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.128/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.128.pdf)
- **中文提要：** 大语言模型适应下游任务时，监督微调常用交叉熵损失来最大化真实词元的似然。这有助于贴合已观测数据并建立领域基础，但只做监督微调往往会限制模型探索其他合理输出，从而收窄决策空间。
- **关键词：** GRPO, SFT, post-training, alignment, fine-tuning

### HSRM: Hidden-State Reward Models for Test-Time Verification

- **作者：** Xianzhi Li, Xiaodan Zhu
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1751/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1751.pdf)
- **中文提要：** 大语言模型常常能写出看似合理的数学推理过程，但要在多个候选解答里可靠挑出正确的一条仍然困难。现有测试时流程多让基于文本的验证器把每条解答重读一遍，验证因此成为推理中很贵的一环。
- **关键词：** reward-model

### HS-SFT: Hybrid Sparse Supervised Fine-tuning for Offline LLM KV Cache Eviction

- **作者：** Yuxin Zhang, Ruobing Xie, Wenhao Li, Jun Xia, Xiawu Zheng, Samm Sun, Di Wang, Rongrong Ji
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.2280/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.2280.pdf)
- **中文提要：** 长上下文大语言模型在自回归解码时，键值缓存随序列线性增长，延迟和显存开销都很明显。键值驱逐大致分成固定驱逐模式的离线策略，以及按注意力分数自适应丢弃缓存的在线策略。
- **关键词：** SFT, fine-tuning

### Human Label Variation as Stable Signal: Learning Annotator-Specific Explanation Behavior via Cross-Annotator Preference Optimization

- **作者：** Beiduo Chen, Pingjun Hong, Ziyun Zhang, Benjamin Roth, Anna Korhonen, Barbara Plank
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.319/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.319.pdf)
- **中文提要：** 自由文本解释把人类标注差异从单纯的标签分歧，延伸到标注者决策背后的推理与偏好。这里考察大语言模型能否学会并复现这种因标注者而异的标签与解释行为。
- **关键词：** SFT, preference-optimization, fine-tuning

### Imag-Eval: a language-grounded framework for interpretable Text-to-Image instruction following evaluation

- **作者：** Ibrahim Mohamed Serouis, David Jaramillo Duque
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1283/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1283.pdf)
- **中文提要：** 文生图模型的视觉保真已经很突出，评测却仍受难解释、诊断性不足的基准束缚。按技能划分的评测容易漏掉标准分类之外、却强烈影响可用性的失败，例如部件缺失所造成的整体不连贯。
- **关键词：** instruction-following

### Is Next-Chunk Reasoning RL Really Better than SFT? Revisiting Training Strategies under no-CoT Data

- **作者：** Yinhao Tang, Youqing Fang, Yanan Sun, Jiangning Liu, Ziyi Wang, Xun Zhao, Weiming Zhang, Bin Liu, Kuikun Liu, Wenwei Zhang, Kai Chen
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.921/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.921.pdf)
- **中文提要：** 有些语料富含推理却没有显式思维链标注，例如解题过程和教材推导。近期的下一块推理强化学习让模型生成隐式推理轨迹，再按其预测下一段文本的能力给予奖励。
- **关键词：** RLVR, SFT, post-training, fine-tuning

### JURY-RL: Votes Propose, Proofs Dispose for Label-Free RLVR

- **作者：** Xinjie Chen, Biao Fu, Wu Jing, Guoxin Chen, Xinggao Liu, Dayiheng Liu, Minpeng Liao
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.2466/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.2466.pdf)
- **中文提要：** 带可验证奖励的强化学习能增强大语言模型的推理，但通常依赖人工标注的答案或精心编写的奖励说明。多数投票或让大模型当裁判等无标签替代省去了这份成本，却会引入假阳性并使训练不稳定。
- **关键词：** RLVR

### KG-RLVR: Reinforcing LLM Reasoning with Knowledge Graph-Derived Process Rewards

- **作者：** Aoran Gan, Guoxuan Zhang, Ya Li, Qiangbing Wang, Quan Liu, Qi Liu, Guoping Hu
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.890/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.890.pdf)
- **中文提要：** 把通用大语言模型改造成领域问题求解器时，核心困难是如何为知识密集的推理提供可靠的过程级指导。高质量的推理监督，如标注轨迹或外部生成的依据，既昂贵、难以核验，也很难跨领域扩展。
- **关键词：** RLVR, PRM, post-training

### LAK-LoRA: Layer-Wise Adaptive Expert Allocation and Principal Component--Based Feature Separation for Medical Multi-Task Learning

- **作者：** Ye Lyu, Chuan Li, Chengyu Wang, Mingyuan Fan, Cen Chen
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1407/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1407.pdf)
- **中文提要：** 医学领域的多任务学习对大语言模型仍然困难，既有相互冲突的任务目标，全量微调的计算开销也很大。参数高效微调能减轻资源压力，效果却受各层专家容量分配过于刚性等问题限制。
- **关键词：** LoRA, PEFT, fine-tuning

### Language Chain in Alignment: Cross-lingual Ranking Preference Optimization

- **作者：** Seungyoon Lee, Minhyuk Kim, Jungseob Lee, Heuiseok Lim
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1220/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1220.pdf)
- **中文提要：** 大语言模型的对齐高度依赖以英语为中心的高质量偏好数据，换到其他语言时表现往往不够理想。CRPO 利用英语中更稳健的偏好知识，来促进目标语言上的偏好对齐。
- **关键词：** instruction-following, preference-optimization, alignment

### Latent-GRPO: Group Relative Policy Optimization for Latent Reasoning

- **作者：** Jingcheng Deng, Zihao Wei, Liang Pang, Junhong Wu, Shicheng Xu, Zenghao Duan, Huawei Shen
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.2345/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.2345.pdf)
- **中文提要：** 潜空间推理把中间步骤压缩成连续表示，从而缩短推理链，比显式推理更高效。现有潜空间方法主要停留在监督学习，潜空间中的强化学习仍然高度不稳定。
- **关键词：** GRPO

### Latent-SFT: LLM Latent Reasoning as Chain of Superposition

- **作者：** Jingcheng Deng, Liang Pang, Zihao Wei, Shicheng Xu, Zenghao Duan, Kun Xu, Yang Song, Huawei Shen, Xueqi Cheng
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.2346/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.2346.pdf)
- **中文提要：** 潜空间推理是比思维链更省计算的替代，却常因分布错位和推理链定义含糊而性能下降。更理想的情形是让潜空间推理充当多条推理路径的叠加。
- **关键词：** SFT

### Latent Task Embedding: Geometric Expansion for Single-Path Multi-Task PEFT

- **作者：** Junhyun Lee, Seoha Song, Dhananjaya Gowda
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.2649/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.2649.pdf)
- **中文提要：** 参数高效微调通常依靠对权重做加性扰动。在多租户云服务或移动边缘设备这类动态部署中，加性方法要么合并权重而失去任务切换的灵活性，要么保持不合并并承受并行分支带来的严重延迟。
- **关键词：** LoRA, PEFT, fine-tuning

### LLM Feedback for Topic Model with Preference Optimization and Contrastive Learning

- **作者：** Tung Nguyen, Dat Phan Trong, Linh Ngo Van, Duc Anh Nguyen, Dinh Thai Hoang, Diep Nguyen
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.265/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.265.pdf)
- **中文提要：** 把大语言模型接入主题模型，并借助指令式提示发挥其生成能力，有望改善主题的可解释性与连贯性。不过现有做法往往带来很高的计算成本和更复杂的推理。
- **关键词：** DPO, preference-optimization

### LLM Fine-tuning with an Unconstrained Fine-tuned Teacher

- **作者：** Jianhao Zhang, Ou Wu, Yi Du
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1310/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1310.pdf)
- **中文提要：** 在单一目标任务上微调大语言模型，需要在任务适应与保留原有能力之间取得平衡。现有教师模型主要引导能力的保留或迁移，却不能指出在必须保住原有能力时，哪些目标任务样本更应当被强调。
- **关键词：** fine-tuning

### Long Document Reconstruction Unlocks Scalable Long-Context RLVR

- **作者：** Yao Xiao, Lei Wang, Yue Deng, Guanzheng Chen, Ziqi Jin, Jung-jae Kim, Xiaoli Li, Roy Ka-Wei Lee, Lidong Bing
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.135/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.135.pdf)
- **中文提要：** 可验证奖励强化学习已经成为提升大语言模型能力的重要后训练范式，长上下文也在其要增强的能力之列。
- **关键词：** RLVR

### LoRA-Patch: Defending Against Backdoored LoRA Adapters via Directional Steering

- **作者：** Shengyan Huo, Peihai Jiang, Xixiang Lyu, Yige Li
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1475/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1475.pdf)
- **中文提要：** 恶意适配器可以在维持正常任务表现的同时，埋入由触发器激活的隐藏行为，因此常规效用评估很难发现它们。现有基于移除的防御通常通过更新、剪枝、蒸馏或混合参数来净化带后门的模型。
- **关键词：** LoRA, alignment

### LoRA-RG: Residual Gradient-Guided Rank Initialization and Expansion

- **作者：** Dayoung Kwon, Jaeseong Lee, Seung-Won Hwang
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.2000/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.2000.pdf)
- **中文提要：** 如何在 LoRA 中最优地分配秩，是这项工作关心的问题。尽管秩的分配很重要，实践中却通常手工选定，并且在所有模块上保持固定。
- **关键词：** LoRA

### LQ-Rewriter: Generative Reward Model-Guided Lazy Query Rewriting for Role-Playing Dialogue

- **作者：** Wei Song, Zheng Huang, Renyu Zhu, Runze Wu, Zhenya Huang, Yihuan Mao, Rongsheng Zhang, Tangjie Lv, Kai Zhang
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.391/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.391.pdf)
- **中文提要：** 角色扮演对话随着大语言模型的发展而更受欢迎，人们希望互动更沉浸、更个性化。真实场景中用户却常给出简短含糊的懒查询，缺少明确意图和情绪线索，角色扮演模型因此很难接住。
- **关键词：** reward-model, fine-tuning

### Making Clinical Language Models Auditable: Concept-Guided Fine-Tuning for Robust Prediction

- **作者：** Jin Mu, Guanhua Chen
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.628/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.628.pdf)
- **中文提要：** 临床语言模型在院内可以很准，一旦部署分布发生变化就容易失效，因为它们利用模板、分隔符和套话等并不能反映患者状态的病历伪迹。CAST 是一种基于 SAE 的概念引导伪迹抑制微调框架，面向可审计的临床文本分类。
- **关键词：** fine-tuning

### Measuring, Localizing, and Reducing the AI-Like Writing Style of Post-Trained LLMs

- **作者：** Aniket Anand, Janvijay Singh, Zhewei Sun, Dilek Hakkani-T{\"u}r, Nick Feamster
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.708/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.708.pdf)
- **中文提要：** 经过后训练的语言模型常常带有可辨认的人工智能写作风格，但这种风格与后训练及内部表示之间的关系仍不清楚。该工作考察后训练是否引入或放大了这类风格规律，以及这些规律在内部是否有可定位的特征。
- **关键词：** post-training, alignment

### Mechanism Shift During Post-training from Autoregressive to Masked Diffusion Language Models

- **作者：** Injin Kong, Hyoungjoon Lee, Yohan Jo
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1072/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1072.pdf)
- **中文提要：** 把预训练的自回归模型后训练成掩码扩散模型，是通向扩散语言建模的一条高效路径，但还不清楚所得模型是在复用继承来的自回归计算，还是为非自回归生成重新组织了计算。对照诊断发现，这种机制转变会随任务不同而变化。
- **关键词：** post-training, alignment

### MemoryRewardBench: Benchmarking Reward Models for Long-Term Memory Management in Large Language Models

- **作者：** Zecheng Tang, Baibei Ji, Ruoxi Sun, Haitian Wang, Juntao Li, Min Zhang
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.2574/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.2574.pdf)
- **中文提要：** 随着真实应用增多，大语言模型越来越依靠以记忆为中心的机制来处理多轮交互任务。中间处理轨迹，也就是记忆，直接关系到模型是否忠实、是否有效。
- **关键词：** reward-model

### MiST: Mid-Training LLMs for Cybersecurity

- **作者：** Oded Ovadia, Elad Ben Zaken, Elad Guttman, Orly Moreno Kadosh
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.652/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.652.pdf)
- **中文提要：** 网络安全把高风险分析与复杂的技术语言结合在一起，对大语言模型既重要又困难。MiST 是一套中期训练的安全变换模型，并在公开的网络安全基准上取得较强表现。
- **关键词：** SFT, continued-pretraining, mid-training, fine-tuning

### MM-VeriRubric: Verifiable Evidence-Grounded Rubrics for Multimodal Reward Models

- **作者：** Zhiyong Cao, Bo Wang, Jintao Li, Shuxia Liu, Kairan Zhang, Aijia Wang, Yi-Liang Wei, Sicheng Zhou
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.2230/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.2230.pdf)
- **中文提要：** 奖励建模对多模态对齐必不可少，但多数现有奖励模型只给出结果奖励，信号稀疏，也抓不住人类偏好。评分细则可以提供有结构、更细粒度的评价信号，不过为多模态任务构建真正有效的细则仍然困难。
- **关键词：** reward-model, alignment

### Modular Representation Steering for Multi-Attribute LLM Alignment

- **作者：** Chaojian Shi, Renhong Huang, Xulan Qiu, Jiawei Zhou, Yunsong Zhou
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1469/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1469.pdf)
- **中文提要：** 让大语言模型同时对齐同一语料中的多种行为目标仍然困难，属性的联合优化常常相互干扰并被迫取舍。表示导向能通过干预隐状态轻量控制单项行为，但多种属性是否可以组合起来做对齐还很少被研究。
- **关键词：** alignment

### Monkey Jump: MoE-Style PEFT for Efficient Multi-Task Learning

- **作者：** Nusrat Jahan Prottasha, Md Kowsher, Chun-Nam Yu, Chen Chen, Ozlem Garibay
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.801/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.801.pdf)
- **中文提要：** 混合专家形态的参数高效微调可以按词元做特化，但会额外引入可训练的路由器和专家参数，显存与训练成本随之上升。这与参数高效微调要控制开销的初衷相冲突。
- **关键词：** PEFT, fine-tuning

### Not All Prompts Are Equal: Exploration-Guided Prompt Scaffolding for Multimodal Reinforcement Post-Training

- **作者：** Yuanhao Yue, Qianli Ma, Chengyu Wang, Haoting Wang, Lei Shen, Jun Huang
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.416/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.416.pdf)
- **中文提要：** 在线强化学习中的训练提示对当前策略的信息量差别很大：有的已经饱和，有的又难到给不出可靠的学习信号，标准训练却给它们相同的采样预算。探索引导的提示支架在强化学习过程中动态调整训练提示的分布。
- **关键词：** GRPO, post-training

### One Instruction Is a Benchmark: End-to-End Instruction-Following Evaluation with FlexBench

- **作者：** Yuchen Ge, Yizhao Sun, Wei He, Jinpeng Ou, Wenzhe Niu, Chengshun Shi, Huichuan Fan, Biao Ma, Shuo Huang, Xin Tian, Jiuchong Gao, Jinghua Hao, Renqing He
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1521/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1521.pdf)
- **中文提要：** 真实部署越来越依赖用户给出的长而精确、贴合特定工作流的指令。在这种设定下，总榜上的综合成绩往往很难代表模型能否忠实执行使用者真正打算部署的那一条指令。
- **关键词：** instruction-following

### On the Sensitivity of Instruction-tuned LLMs to Harmful Sentences in Long Inputs

- **作者：** Faeze Ghorbanpour, Alexander Fraser
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1484/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1484.pdf)
- **中文提要：** 大语言模型越来越常处理长输入，但有害句子稀疏嵌入其中时模型会如何表现仍不清楚。一项敏感性分析考察：当有害内容稀疏分布在无害句子之间时，模型能否检测并定位这些有害句。
- **关键词：** instruction-tuning

### OptiMer: Optimal Distribution Vector Merging Is Better than Data Mixing for Continual Pre-Training

- **作者：** Haiyue Song, Huy Hien Vu, Masao Utiyama
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1090/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1090.pdf)
- **中文提要：** 持续预训练广泛用于把大语言模型适配到目标语言和领域，但数据混合比例是必须在训练前固定的敏感超参数，选得不好会浪费大量计算。OptiMer 把比例选择从训练中拆开，先为每个数据集单独训练一个持续预训练模型，再从各模型中提取信息。
- **关键词：** continued-pretraining

### Pak3H: Evaluating the Cost of Cultural Mismatch in LLM Alignment with a Human-Contextualized Urdu Benchmark

- **作者：** Abdullah Hashmat, Usman Naseem, Agha Ali Raza
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.883/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.883.pdf)
- **中文提要：** 大语言模型在以英语为中心的设定中，有用、无害与诚实对齐表现较强，但文化错配使这些收益难以迁移到低资源语言。现有多语言对齐基准主要依赖自动翻译或大模型合成，既传播源语言偏见，又牺牲本地相关性。
- **关键词：** alignment

### Personalized Alignment of Language Models with Human Value Profiles

- **作者：** Rashon Poole, Farnaz Jahanbakhsh
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1600/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1600.pdf)
- **中文提要：** 征求建议这类主观任务往往没有唯一正确答案，大语言模型却越来越多地被用在这里。占主导的对齐方法学到的是一套对所有用户统一适用的行为策略，难以反映个人不同的价值优先序。
- **关键词：** DPO, LoRA, alignment

### Plasticity without Collapse: Plasticity-Inducing Control Optimizer for Cross-Lingual Continual Pre-Training

- **作者：** Sumin Kim, Minjun Song, Surin Lee, S M Wahidur Rahman, Yongtae Lee, Haeung Choi, Heung-No Lee
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.528/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.528.pdf)
- **中文提要：** 语言模型运行在不断变化的环境中，适应新领域和语言变迁十分关键。持续预训练可以应对这种变化，同时却引入严格的稳定性与可塑性矛盾。
- **关键词：** continued-pretraining

### Portuguese-IFEval: Instruction-Following Evaluation in Portuguese

- **作者：** Emanuel Borges Passinato, Gustavo Pires Fontana, Cibelle Pires Botelho, J{\'u}lia Jaime Biancolini, Diogo Fernandes Costa Silva, Arlindo Rodrigues Galv{\~a}o Filho
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.742/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.742.pdf)
- **中文提要：** 指令遵循是大语言模型的核心能力，模型必须先可靠满足指令约束，才谈得上在下游任务上被评估。低资源语言、尤其是葡萄牙语的指令遵循评测仍然有限，现有做法多基于翻译来的英语数据，难以体现该语言自身的特点。
- **关键词：** instruction-following

### PRISM: Preference-aware Influence function based Data Selection Method for Efficient Fine-Tuning

- **作者：** Qihao Lin, Guanxu Chen, Dongrui Liu, Jing Shao
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.2026/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.2026.pdf)
- **中文提要：** 随着大语言模型规模增大，提升训练效率更依赖把数据用得有效。数据选择把有限的数据预算分配给最能促成目标行为的样本，以此来缓解这一问题。
- **关键词：** fine-tuning

### PRISM: Private Rank-Invariant Subspace Memory for Federated Continual Fine-Tuning under Local Differential Privacy

- **作者：** Ziyi Wang, Liang Liu, Zhu Meng, Zhicheng Zhao
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.313/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.313.pdf)
- **中文提要：** 在本地差分隐私下保护单条样本的同时，预训练语言模型还要随私有客户端分布的变化做持续微调。流式差分隐私联邦学习中，全秩 LoRA 会把许多可训练方向暴露给差分隐私噪声，后续领域还可能覆盖那些仍然相关的方向。
- **关键词：** LoRA, fine-tuning

### PRISM: Prompt Representation Internalization via Selective Compression into LoRA Weights

- **作者：** Eshita Jha, Mingxian Wang, Andrei Barbu, Chetan Aggarwal
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.2431/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.2431.pdf)
- **中文提要：** 把大语言模型部署到专用任务上，往往要把模式说明、示例和指令拼成长提示，提示有多丰富与推理是否可行彼此拉扯。作者区分出模式主导与流程主导两类情形；在模式主导任务中，示例主要通过隐含的格式和抽取惯例来拉动表现。
- **关键词：** LoRA

### PR-LoRA: Direction-Regularized Low-Rank Adaptation for Behavioral Alignment in Large Language Models

- **作者：** Yikai Zhang, Rui Xu, Aili Chen, Haoyu Zhang, Libo Wu, Xu Yinghui, Yanghua Xiao
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.2317/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.2317.pdf)
- **中文提要：** 已部署大语言模型的行为问题，常常在监督很有限、又不适合重做完整对齐时才被发现。事后方法各有短板：激活导向缺少对输入的适应性，标准 LoRA 则没有显式的行为方向先验，在数据很少时还可能不稳定。
- **关键词：** DPO, LoRA, PEFT, alignment

### Probing Chemical Language Models: Effects of Pre-training and Fine-tuning

- **作者：** Anna Karnysheva, Dietrich Klakow, Ji-Ung Lee
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.2662/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.2662.pdf)
- **中文提要：** 化学语言模型使用 SMILES 这类线性化表示来训练，但它们编码了哪些有化学意义的子结构仍不清楚。作者对预训练模型与随机初始化模型做系统探测，检查这些分子子结构是否被编码。
- **关键词：** fine-tuning

### Process Rewarding via Solution-Space Alignment

- **作者：** ChenZhuo Zhao, Yue Huang, Pu Zhao, Fangkai Yang, Lu Wang, Lin Ma, Zhi Yang, Youling Huang, Xinda Wang, Junting Lu, Qingwei Lin, Saravan Rajmohan, Dongmei Zhang
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1967/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1967.pdf)
- **中文提要：** 带可验证奖励或结果级奖励的强化学习，近来成为提升大语言模型推理能力的有效后训练范式，GRPO 式优化在数学等可验证任务上表现突出。对多步推理而言，这种只看结果的监督在本质上仍然稀疏。
- **关键词：** GRPO, RFT, PRM, post-training, alignment, fine-tuning

### PRO-Step: Step-level Process Reward Optimization for Retrieval-Augmented Generation

- **作者：** MinKeon Kim, Namjun Lee, Jaekwang Kim
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1667/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1667.pdf)
- **中文提要：** 检索增强生成借助外部知识来约束大语言模型的回答，但多跳推理仍容易发生错误传播，早期检索失败会干扰后续步骤。只奖励最终答案的结果优化发现不了中间的检索与推理错误。
- **关键词：** DPO, preference-optimization, PRM

### P-Search: A Parallel Plan--Act--Verify Framework with Decoupled GRPO for Deep Research

- **作者：** Pin Zheng, Yibo Xue, Ming Wang, Yukun Kang, Haonan Zheng, Chengyu Wang, Jian Peng, Jun Huang, Changliang Xu
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.570/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.570.pdf)
- **中文提要：** 开放网页上的深度研究，限制不只来自智能体搜索了多久，也来自它能否把证据组织成彼此独立、可以核验的分支。现有系统常去扩展单路径的 ReAct 轨迹或长上下文搜索，结果一条假设被挖得很深，其他实体、约束或能证伪的证据却探索不足。
- **关键词：** GRPO

### Ready to Speak: Aligning LLMs for TTS-Friendly Text Generation

- **作者：** Thibaut Thonet, Jos Rozen, Laurent Besacier
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.248/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.248.pdf)
- **中文提要：** 当前大语言模型主要按书面文本优化，输出往往语法正确且有帮助，却不适合直接交给语音合成来朗读。该工作把原生生成适合语音合成的文本视为偏好对齐问题，希望直接对齐模型本身，而不是依赖下游改写模块。
- **关键词：** preference-optimization, reward-model, alignment

### Reasoning Depth and Environment Complexity: A Controlled Study of RLVR Data Allocation across Logical Reasoning Tasks

- **作者：** Yihua Zhu, Qianying Liu, Fei Cheng, Jiaxin Wang, Akiko Aizawa, Sadao Kurohashi, Hidetoshi Shimodaira
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.2033/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.2033.pdf)
- **中文提要：** 可验证奖励强化学习已成为推理模型后训练的核心，但已有研究把难度只看成推理深度，奖励也集中在前向演绎的状态跟踪上。这项工作改为沿多个维度来刻画推理空间。
- **关键词：** RLVR, post-training

### Reasoning Matters: Mitigate Hallucination in Multimodal Large Reasoning Models via Reasoning-Conditioned Preference Optimization

- **作者：** Jiawei Kong, Hao Fang, Shunxiang Liao, Jinyu Li, Bin Chen, Hao Wu, Shu-Tao Xia, Min Zhang
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.376/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.376.pdf)
- **中文提要：** 多模态大推理模型引入推理范式，在复杂的视觉语言任务上能力很强。尽管如此，它们仍然受到严重幻觉的困扰。
- **关键词：** DPO, preference-optimization, alignment

### Representation-Aware Advantage Estimation: Your Reward Model Provides More Than A Scalar Output

- **作者：** Guozheng Li, Xiyan Fu, Steven Y. Guo
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1527/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1527.pdf)
- **中文提要：** 当前 RLHF 主要依赖训练好的奖励模型输出的标量奖励。这类标量往往有噪声，难以刻画细粒度偏好差异，而奖励模型的隐状态编码着更丰富的语义与偏好信息。
- **关键词：** GRPO, RLHF, reward-model

### Rethinking LoRA Memory Through the Lens of KV Cache Compression

- **作者：** Chunsheng Zuo, Liaoyaqi Wang, William Jurayj, William Fleshman, Benjamin Van Durme
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.733/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.733.pdf)
- **中文提要：** 参数检索增强把文档编进 LoRA 等轻量、按文档区分的适配器，从而不必把全部证据放进输入上下文。这种参数侧记忆与 KV 缓存中的上下文侧记忆如何相互作用，仍然不清楚。
- **关键词：** LoRA

### Rethinking the Role of Tensor Decompositions in Post-Training LLM Compression

- **作者：** Artur Zagitov, Alexander Miasnikov, Maxim Krutikov, Vladimir Aletov, Gleb Molodtsov, Nail Bashirov, Aleksandr Beznosikov
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.2679/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.2679.pdf)
- **中文提要：** 资源受限时部署大语言模型，后训练压缩是必要环节。张量分解提供适合 Transformer 权重结构的紧凑参数化，这项研究重新审视它在后训练压缩中的作用。
- **关键词：** post-training

### Retrievable Gradients: Continual Post-Training Without Cumulative Weight Drift

- **作者：** Weihang Su, Jiacheng Kang, Jingyan Xu, Qingyao Ai, Jianming Long, Hanwen Zhang, Bangde Du, Xinyuan Cao, Min Zhang, Yiqun Liu
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1197/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1197.pdf)
- **中文提要：** 部署之后的持续后训练可以吸收新出现的知识，但反复更新共享参数会累积权重漂移，造成灾难性遗忘并削弱通用能力。检索增强生成能避开这种参数漂移，却常常达不到参数化知识整合的深度。
- **关键词：** post-training

### Risk-conditioned Fine-tuning of Large Language Models

- **作者：** Zixuan Liu, Fangzheng WU, Brian Summa, Zizhan Zheng
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.956/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.956.pdf)
- **中文提要：** 大语言模型日益被用到罕见但后果严重的有害生成场景。已有的风险厌恶 RLHF 通过优化条件风险价值来应对，却只为固定风险水平训练策略，推理时无法调节所需的风险厌恶程度。
- **关键词：** RLHF, fine-tuning

### Rubric-Guided Process Reward for Stepwise Model Routing

- **作者：** Shenghao Ye, Yu Guo, Zhengheng Li, Qiang Huang, Shuangwu Chen, Wang Luo, Rui Qian, Jie Zhang, Tao Zhang, Dong Jin, Xiaobin Tan, Quan Zheng, Jianyang
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1222/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1222.pdf)
- **中文提要：** 逐步模型路由把每个推理步骤分配给合适的模型，以提高大型推理模型的效率。近期做法把路由建成序贯决策过程，并用强化学习训练路由器。
- **关键词：** GRPO, PRM

### RubricRM: Generative Reward Modeling via Dynamic Rubrics for Image Generation and Editing

- **作者：** Zijian Kan, Wei Wang, Luo Long, Bing Zhao, Xuan Ren, Weixu Qiao, Li Wenbo, hu Wei, Lin Qu
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1094/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1094.pdf)
- **中文提要：** 对齐视觉生成模型离不开奖励模型，但多数视觉奖励模型只给单一标量分，或依赖无法随指令调整的固定标准。这同时限制了可解释性与任务敏感度，在文生图和指令式图像编辑中尤其明显，因为不同输入需要不同的评价维度。
- **关键词：** GRPO, SFT, reward-model, alignment, fine-tuning

### SAEExplainer: Interpreting SAE Features with Activation-Guided Preference Optimization

- **作者：** Jingyi He, Haiyan Zhao, Ruxue Shi, Yanguang Liu, Xin Wang, Fei Sun, Mengnan Du
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.393/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.393.pdf)
- **中文提要：** 稀疏自编码器把稠密表示拆成稀疏特征，减轻了大语言模型的不透明，但解释这些特征仍是中心难题。现有解释方法多在开环设定下进行，未能借助机制反馈继续改进。
- **关键词：** preference-optimization

### Same Trajectory, Contradictory Rewards (RoboRMBench): Paraphrase Fragility in Vision Language Reward Models

- **作者：** Wonje Jeung, Sangyeon Yoon, Hyesoo Hong, Yoonjun Cho, Dongjae Jeon, Bumjun Kim, Jean Oh, Youngjae Yu, Albert No
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1687/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1687.pdf)
- **中文提要：** 把视觉语言模型用作机器人学习的奖励函数时，需要释义不变性：语义等价的目标描述下，同一条轨迹应得到相同奖励。当前的视觉语言奖励模型经常违反这一性质。
- **关键词：** reward-model

### ScalePRM: Training Process Reward Models by Scaling Verification Compute Without Ground Truth

- **作者：** Salman Rahman, Sruthi Gorantla, Arpit Gupta, Swastik Roy, Nanyun Peng, Yang Liu
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1452/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1452.pdf)
- **中文提要：** 训练过程奖励模型需要步骤级正确性标签，这些标签要么来自昂贵的人工标注，要么依赖标准答案，过程级监督因此难以扩展。ScalePRM 改为扩大验证计算：给定题目和候选解答后，对每个推理步骤生成多次相互独立的验证。
- **关键词：** RLVR, PRM, reward-model

### Scaling Near-Optimal SFT-RL Annotation Budget Allocation from Small to Large LLMs

- **作者：** Jingtan Wang, Arun Verma, Xiaoqiang Lin, Zhengyuan Liu, Nancy F. Chen, Daniela Rus, Bryan Kian Hsiang Low
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.2450/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.2450.pdf)
- **中文提要：** 后训练里如何把固定标注预算分给 SFT 和强化学习，仍是开放问题。已有工作只描述宽泛趋势，例如低数据情形下 SFT 占主导，既缺少原则性分配框架，也未检验最优比例能否跨模型规模迁移。
- **关键词：** SFT, post-training, fine-tuning

### SCAR: Shapley Credit Assignment for More Efficient RLHF

- **作者：** Meng Cao, Shuyuan Zhang, Xiao-Wen Chang, Doina Precup
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1795/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1795.pdf)
- **中文提要：** RLHF 的奖励信号常常稀疏，把功劳分到各个词元因此困难。SCAR 借助合作博弈中的 Shapley 值，按边际贡献把序列级奖励分配到词元或文本片段。
- **关键词：** RLHF, instruction-tuning, alignment

### SCRIBE: Learning Reusable Skill Rubrics for Process Reward Models

- **作者：** Yuxuan Jiang, Francis Ferraro
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.797/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.797.pdf)
- **中文提要：** 多步推理中的信用分配，使可靠的工具增强智能体难以训练。过程奖励模型可以给中间步骤或轨迹打分，但标准的大语言模型评判往往因评价标准不够明确而给出不稳定信号。
- **关键词：** PRM, reward-model

### SEAR: Self-Judging Agentic Reward Models

- **作者：** Bingqian Li, Chuan Hao, Junyi Li, Ran Tao, Jian Yang, Xin Zhao
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.893/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.893.pdf)
- **中文提要：** 引入外部工具使用之后，智能体式奖励模型能够加强大语言模型评测。其训练却受到粗粒度结果监督以及高成本过程级标注的严重限制。
- **关键词：** reward-model

### Secret Stealing Attacks on Local LLM Fine-Tuning through Supply-Chain Model Code Backdoors

- **作者：** Zi Li, Tian Zhou, Wenze Li, Jingyu Hua, Yunlong Mao, Sheng Zhong
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.812/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.812.pdf)
- **中文提要：** 本地微调数据里经常含有 API 密钥、个人标识和财务记录等敏感秘密。本地离线微调常被看作隐私边界，但被篡改的模型代码就足以窃取这些内容。
- **关键词：** LoRA, fine-tuning

### SemPOI-RL: Aligning LLM Semantic Reasoning for Interpretable Out-of-Town POI Sequential Generation

- **作者：** Yunqi Liu, Yang Zhang, Ruixing Zhang, Liangzhe Han, Yi Qiao, Tongyu Zhu, Leilei Sun
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1848/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1848.pdf)
- **中文提要：** 大语言模型的语义推理和开放式生成能力很强，要与结构化序列生成对齐却不容易。异地兴趣点序列生成把这一困难放大：模型须从用户家乡行为推断可迁移的出行意图，并适应跨城市兴趣漂移，其后的生成要求在摘要里没有写完。
- **关键词：** alignment, fine-tuning

### SimCRAFT: Distilling Remote Sensing Agents via Synthetic Trajectories and Contextual Retrieval-Augmented Fine-Tuning

- **作者：** Haoran Wang, Jing Yao, Xu Yang, Zeqing Wang, Yang Zhang, Pedram Ghamisi, Zhengchao Chen
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.2674/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.2674.pdf)
- **中文提要：** 对地观测数据在体量和多样性上的激增，使传统人工流程成为瓶颈，并催生了遥感智能体。这些智能体的实际部署却严重依赖大规模通用大语言模型，既缺少深入的领域专长，又带来过高的基础设施需求。
- **关键词：** fine-tuning

### SIMPA: Restricting What Experts See, Not What They Produce, in MoE-PEFT

- **作者：** Pham Tri Quang, Khoa Tran, Giang Do, Hung Le, Truyen Tran, Tho Quan
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.726/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.726.pdf)
- **中文提要：** 在 MoE-PEFT 中，单个专家会吸收绝大部分词元。此前的补救都作用在输出端，包括重写路由、惩罚输出相似度，或设置共享专家容量。
- **关键词：** LoRA, PEFT, fine-tuning

### SIMPLE: A Comparative Study of Prompting and Fine-Tuning for LLM-Based Text Simplification

- **作者：** Zixian Meng, Dongqiang Yang
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.2306/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.2306.pdf)
- **中文提要：** 微调与提示是适配大语言模型的两条常用路径，二者在文本简化上的效果仍缺少比较。
- **关键词：** instruction-tuning, QLoRA, alignment, fine-tuning

### SIP: Aligning LLM-based TableQA with Table Semantics via SQL Logic

- **作者：** Zhen Yang, Ziwei Du, Minghan Zhang, Wei Du, Haodong Zou, Shicheng Tan, Jie Chen, Shu Zhao
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1947/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1947.pdf)
- **中文提要：** 表格问答上，大语言模型的表现已经不错，推理过程却经常偏离底层表格语义。由此产生的分解和校验步骤，可能无法如实覆盖问题所要求的表格操作。
- **关键词：** alignment

### Small Reward Models via Backward Inference

- **作者：** Yike Wang, Faeze Brahman, Shangbin Feng, Teng Xiao, Hannaneh Hajishirzi, Yulia Tsvetkov
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.2629/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.2629.pdf)
- **中文提要：** 奖励模型贯穿语言模型流程，在不可验证的领域里尤其关键。主流的大模型裁判依赖大模型的强推理，其他途径又需要参考回答或显式量规，灵活性和可及性都受限制。
- **关键词：** GRPO, reward-model

### Small yet Assistive: Spatially-Aware Post-Training for Low Vision

- **作者：** Rishabh Choudhary, Shreyansh Raj, Umesh Goyal, Subh Kasyap, Shrestha Kumar, Sushovan Jena, Komal Kumar, Hisham Cholakkal, Aditya Nigam
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.2273/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.2273.pdf)
- **中文提要：** 现有视觉语言模型的描述往往过于笼统，难以支持盲人和低视力用户的安全导航。大型模型能写出符合口述影像规范的叙述，但无法在移动设备上运行；小型模型延迟更有竞争力，却缺少空间细节、方向线索和危险觉察。
- **关键词：** GRPO, post-training, fine-tuning

### Spectral DPO: Mitigating Validation Collapse via Heavy-Tailed Regularization

- **作者：** Ibne Farabi Shihab, Sanjeda Akter, Anuj Sharma
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.785/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.785.pdf)
- **中文提要：** DPO 去掉了 RLHF 的显式奖励模型，却继承了同一类失败：偏好奖励的代理可以继续变好，下游的推理、事实性或安全性却下降。文中把这种奖励过优化在所测轨迹上的表现称为验证崩溃，并询问它是否显现在权重空间的几何里。
- **关键词：** DPO, RLHF, instruction-following, preference-optimization, reward-model, LoRA

### SPHERE: Automatic Music Upmixing via Audio Language Model Post-Training with Spatial Heuristics Rewards

- **作者：** Zixun Guo, Calvin Murdock, Sanjeel Parekh, W. Owen Brimijoin, Simon Dixon, Joshua Reiss, Ishwarya Ananthabhotla
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.2673/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.2673.pdf)
- **中文提要：** 自动音乐上混要求系统从多分轨录音预测空间混音参数。与依赖专用音乐编码器的已有方法不同，这里通过对音频语言模型做后训练来处理该任务，并利用其中同时编码音乐语义与混音知识的表示。
- **关键词：** GRPO, RLVR, SFT, post-training

### Stick to What You Know: A Study of Knowledge-Aligned Supervised Fine-Tuning

- **作者：** Arthur Becker, Jakob Kemmler, David Thulke, Christine Sch{\"a}fer, Christian Dugast, Hermann Ney
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.523/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.523.pdf)
- **中文提要：** 监督微调让基座模型模仿目标回答，而这些目标可能需要基座尚未稳健掌握的知识。这一现象被当作幻觉的一种来源，一组缓解办法则被界定为知识对齐的 SFT，也就是把训练目标限制在基座的参数化知识之内。
- **关键词：** SFT, alignment, fine-tuning

### Supervised Fine-Tuning for Reasoning Large Language Models: A Survey

- **作者：** Yongcan Yu, Kuangpu Guo, Jian Liang, Lingxiao He, Meng Wang, Ran He
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1189/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1189.pdf)
- **中文提要：** 在长思维链数据上做 SFT，是激发并加强大型推理模型解决复杂任务能力的重要基础。面向推理的监督微调在改进和分析两侧进展都很快，仍缺少把迅速增长的文献整合起来的系统综述。
- **关键词：** SFT, fine-tuning

### TagPR: Tag-Guided Process Supervision for Personalization Reasoning in Large Language Models

- **作者：** Song Jin, Juntian Zhang, Ruyu Lyu, Yong Liu, Xun Zhang, Yufei Zhang, Fei Jiang, Guojun Yin, Wei Lin, Rui Yan
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1675/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1675.pdf)
- **中文提要：** 通用推理上的进展相当突出，但这些推理模型处理个性化任务时，常常不如非推理模型。
- **关键词：** SFT, reward-model, alignment, fine-tuning

### TaRA: Training-Aware Low-Rank Adaptation Initialization

- **作者：** Taehyeon Kim, Eunhyeok Park
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.2014/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.2014.pdf)
- **中文提要：** LoRA 已成为 PEFT 的事实标准，低秩分解带来的信息瓶颈却使性能对初始化高度敏感。已有方法试图利用预训练权重、激活或梯度的主成分，来构造更高质量的 LoRA 初始化。
- **关键词：** LoRA, PEFT, fine-tuning

### Temporal Gains, Spatial Costs: Revisiting Video Fine-Tuning in Multimodal Large Language Models

- **作者：** Linghao Zhang, Jungang Li, Yonghua Hei, Sicheng Tao, Song Dai, Yibo Yan, Zihao Dongfang, Weiting Liu, Chenxi Qin, Hanqian Li, Xin Zou, Jiahao Zhang, ShuHang Xun, Haiyun Jiang, Xuming Hu
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.114/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.114.pdf)
- **中文提要：** 多模态大语言模型通常分阶段训练，基于视频的监督微调是提升视觉理解的关键步骤。它对视觉能力的细粒度变化，尤其是空间理解与时间理解之间的平衡，仍然缺乏了解。
- **关键词：** SFT, fine-tuning

### TEMPO: Temporally-grounded Multi-task Post-training for Large Audio-Language Models

- **作者：** Apoorva Kulkarni, Kaousheik Jayakumar, Sreyan Ghosh, Utathya Aich, Ramani Duraiswami, Dinesh Manocha
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.694/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.694.pdf)
- **中文提要：** 大型音频语言模型能在片段层面描述音频，却不能给识别出的事件、说话人或声音标注时间。时间定位对语音识别和密集音频描述等下游任务很必要，目前仍是多数此类模型的关键短板。
- **关键词：** GRPO, SFT, post-training, fine-tuning

### The Illusion of Expertise: Narrow Finetuning Induces Persistent Domain Priors in Vision-Language Models

- **作者：** Qinglin Zeng, Jusheng Zhang, Jiangqi Huang, Ningyuan Liu, Luozhang Xu, Wenhao Wang, Keze Wang
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1668/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1668.pdf)
- **中文提要：** 窄领域微调会使视觉语言模型听起来像领域专家，同时让它们更少留意图像本身。这一反差被归因于持续存在的领域先验：窄域微调在隐状态中装入与具体输入无关的偏移，使输出偏向领域风格，而不论视觉证据如何。
- **关键词：** fine-tuning

### The Weakest Link Tells It All: Outcome-Supervised Process Reward Modeling via Learnable Credit Assignment

- **作者：** Tianyu Jia, Yue Fang, Hongxin Ding, Rihong Qiu, Zhibang Yang, Zhijing Wu, Junfeng Zhao, Yasha Wang, Xu Chu
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.486/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.486.pdf)
- **中文提要：** 过程奖励模型靠细粒度反馈增强大语言模型的推理，训练却通常需要昂贵的逐步标注。只根据最终答案对错来学习的结果监督路线更易扩展，但要把结果归到真正负责的步骤，构成信用分配难题。
- **关键词：** PRM, reward-model

### Token-weighted Direct Preference Optimization with Attention

- **作者：** Chengyu Huang, Zhuohang Li, Sheng-Yen Chou, Claire Cardie
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.823/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.823.pdf)
- **中文提要：** DPO 不必另训奖励模型，就能按人类偏好对齐大语言模型。它却同等对待回答中的每个词元，忽视了不同词元的重要性并不一样。
- **关键词：** DPO, preference-optimization, reward-model

### Tournament-GRPO: Group-Wise Tournament Rewards for Reinforcement Learning in Open-Ended Long-Form Generation

- **作者：** Zixuan Yang, Yiqun Chen, Wei Yang, Erhan Zhang, Zihan Shen, Xiaochi Wei, Yan Gao, Yi Wu, Yao Hu, Jiaxin Mao
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1515/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1515.pdf)
- **中文提要：** 开放式长文生成中的强化学习很难做，因为可靠的参考答案和自动指标经常缺失。基于量规的现有方法多依赖逐点的大模型裁判打绝对分，这类分数在复杂回答之间难以校准，对同一查询下的多次采样区分不强，优化过程中还可能饱和。
- **关键词：** GRPO

### Towards Understanding Pause Token Fine-Tuning Dynamics: A Mode Retention Perspective

- **作者：** Jaehyeon Kim, Suhwan Kim, Nakyung Lee, Yeongoon Kim, Jimin Seo, Giho Lee, Jungwoo Lee
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1710/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1710.pdf)
- **中文提要：** 在序列里插入特殊的暂停词元，被用来改善大语言模型的推理。此前对这类收益的解释，主要从计算表达能力出发。
- **关键词：** GRPO, fine-tuning

### TRACE-GRPO: Teacher-Refined Advantage Credit Estimation for Long-Horizon Agentic RL

- **作者：** Yuchen Liu, Tianchu Yao, Deshu Chen, Yinghao Zhang, Xigui Li, Zehui Ling, Xin Guo, Yuan Cheng, Chao Qu, Lintao Ma, Yuan Qi
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1522/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1522.pdf)
- **中文提要：** GRPO 被广泛用于后训练大语言模型智能体，其轨迹级优势却不适合长程信用分配。奖励同质的采样组会得到零优势；否则一个标量会均匀缩放每个词元，看不清哪些决策真正决定结果。
- **关键词：** GRPO, SFT, post-training, fine-tuning

### TriAlign: Towards Universal Truth Consistency in Personalized LLM Alignment

- **作者：** Thi-Nhung Nguyen, Linhao Luo, Rollin Omari, Junae Kim, Thuy-Trang Vu, Dinh Phung
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.2640/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.2640.pdf)
- **中文提要：** 个性化大语言模型按用户偏好和社会属性调整回答时，可能在不同社会群体之间造成普遍的事实不一致，使某些群体在客观任务上系统性地得到更不准确的回答。现有对齐要么忽略个性化，要么主要对准主观偏好。
- **关键词：** preference-optimization, alignment

### TTML: Test-Time Memory Learning for Label-Free RLVR

- **作者：** Yongshi Ye, Biao Fu, Xinjie Chen, Minpeng Liao, Xiaodong Shi
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.2553/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.2553.pdf)
- **中文提要：** RLVR 能提高大语言模型的推理能力，标准形式却依赖标准答案或外部验证器，无标注的测试时场景里这些条件常常不具备。无标签的 RLVR 因此改为根据模型输出来估计伪奖励。
- **关键词：** RLVR

### TTS$^2$: Test-Time Scaling for Flow-Based Text-to-Speech via Multi-stage Reward Modeling on Posterior Mean Projections

- **作者：** Tung Luong Nguyen, Tuan Duy Nguyen Le, Nhat Hong Tran, Nhat Minh Le, Van Hai Do
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.2541/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.2541.pdf)
- **中文提要：** 训练阶段的计算扩展已经改变生成模型，语音合成里的推理时计算扩展仍少有探索。该研究考察如何在推理时利用计算，以改善基于条件流匹配的非自回归语音合成。
- **关键词：** reward-model

### Two to Tango: Coupled Task-Reference Selection for Safe LLM Fine-tuning

- **作者：** Xinrui Chen, Jianhao Zhang, Ou Wu, Di Gao
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.862/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.862.pdf)
- **中文提要：** 在下游数据上微调已经安全对齐的大语言模型，能改善任务适配，也可能侵蚀已经学会的安全行为。已有对策使用固定的安全样本、全局约束，或只从任务一侧进行过滤。
- **关键词：** instruction-following, fine-tuning

### Understanding \& Isolating the Assistant State in Instruction-Tuned Models

- **作者：** Aishwarya Maheswaran, Maunendra Sankar Desarkar
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.2133/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.2133.pdf)
- **中文提要：** 指令微调后的大语言模型会表现出人工智能助手的人设，但这究竟是多种被模拟角色之一，还是模型根本的结构身份，仍有激烈争论。文中给出证据，认为指令微调建立起一种全局的底层助手状态，它既约束自回归生成，也能够进行元觉察。
- **关键词：** instruction-tuning

### VISA: Value Injection via Shielded Adaptation for Personalized LLM Alignment

- **作者：** Jiawei Chen, Tianzhuo Yang, Guoxi Zhang, Jiaming Ji, Yaodong Yang, Juntao Dai
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.303/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.303.pdf)
- **中文提要：** 让大语言模型适应新领域、新任务或用户偏好，是个性化里的常见需求。即便训练数据主要以知识为导向，这种适应仍可能在无意间改变模型的价值轮廓。
- **关键词：** GRPO, alignment, fine-tuning

### Visual Preference Optimization with Rubric Rewards

- **作者：** Ya-Qi Yu, Fangyu Hong, Xiangyang Qu, Hao Wang, Gaojie Wu, Qiaoyu Luo, Nuo Xu, Huixin Wang, Wuheng Xu, Yongxin Liao, Zihao Chen, Haonan Li, Ziming Li, Dezhi Peng, Minghui Liao, Jihao Wu, Haoyu Ren, Dandan Tu
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.2552/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.2552.pdf)
- **中文提要：** DPO 是否有效，取决于偏好数据对有没有抓住与任务相关的质量差异。现有数据流程常常依赖离策略扰动或粗糙的结果信号，并不适合细粒度的视觉推理。
- **关键词：** DPO, preference-optimization, reward-model

### W2T: LoRA Weights Already Know What They Can Do

- **作者：** Xiaolong Han, Ferrante Neri, Jiang Zijian, Fang Wu, Yanfang Ye, Lu Yin, Zehong Wang
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.158/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.158.pdf)
- **中文提要：** 每个 LoRA 检查点用低秩权重矩阵紧凑保存任务相关更新，便于把大语言模型适配到新任务和新领域。原则上，这些权重已经编码了适配器在做什么以及做得如何。
- **关键词：** LoRA

### What Drives the Zero-to-One Jump? Diagnosing and Steering Hard-Prompt Learning in RLVR

- **作者：** Rui Zhu, Yumou Liu, Zhenzhe Zheng, Fan Wu
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1821/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1821.pdf)
- **中文提要：** RLVR 明显推进了数学推理。文中追问是什么驱动这一转变，第二个问题在给定摘要里没有写完。
- **关键词：** GRPO, RLVR

### When In-Distribution Gains Fail: Evaluating Weak-to-Strong Reward Models under Preference Shift

- **作者：** Khoi M. Le, Tri Cao, Phong Nam Huu Nguyen, Cong-Duy T Nguyen, Anh Tuan Luu, Chunyan Miao, See-Kiong Ng, Thong Thanh Nguyen
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1240/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1240.pdf)
- **中文提要：** 弱到强泛化被看作可扩展监督的一条途径，已有评测却多在训练与测试分布匹配时进行。零样本分布偏移下的偏好学习显示，接受弱偏好标签的强学生可以在分布内看似成功，跨偏好数据集时却无法迁移。
- **关键词：** SFT, reward-model, fine-tuning

### Where to Steer: Input-Dependent Layer Selection for Steering Improves LLM Alignment

- **作者：** Soham Gadgil, Chris Lin, Su-In Lee
- **会议：** EMNLP 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.1790/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.emnlp-main.1790.pdf)
- **中文提要：** 转向向量以轻量方式在推理时对齐大语言模型，通过把中间表示推向目标行为来调节模型。许多现有方法把干预放在全局固定位置，相当于把最优干预位置当成与输入无关。
- **关键词：** alignment

## Findings

### AdaC-GRPO: Towards Mastering Long-Horizon Visual Sudoku Puzzles via Adaptive Curriculum Learning

- **作者：** Sida Li, Yuanxin Liu, Linli Yao, Shicheng Li, Xu Sun, Haoli Bai, Xiao-Hui Li
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.2255/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.2255.pdf)
- **中文提要：** 长程多模态任务上，RLVR 能否增强推理仍缺少充分研究。视觉数独是其中的代表性挑战，需要同时处理局部约束，并沿全局依赖链做多步演绎。
- **关键词：** GRPO, RLVR, post-training

### Agentic Reward Modeling for Medical Reasoning

- **作者：** Hang Zhang, Ruheng Wang, Yuelyu Ji, Min Gu Kwak, Xizhi Wu, Chenyu Li, Li Zhang, Wenqi Shi, Yifan Peng, Yanshan Wang
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.766/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.766.pdf)
- **中文提要：** 大语言模型在医学推理基准上已经很强，临床使用仍需要严格核验事实是否准确。奖励模型可以为推理轨迹核验提供可扩展手段，现有方法却只给出没有显式理由的标量奖励，并依赖单次检索。
- **关键词：** reward-model

### Aligning Large Language Models with Pluralistic Values: Case Study in Southeast Asian (SEA) Countries

- **作者：** Supryadi, Khue T. M. Luu, Maw Kyi Saw, Somchanmavong Souphanid, Yuqi Ren, Deyi Xiong
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1932/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1932.pdf)
- **中文提要：** 大语言模型在全球范围部署后，与多元人类价值对齐仍然困难，因为现有工作主要集中在西方。SEAPlur 数据集用来评测并改进模型与印度尼西亚、老挝、缅甸和越南多元价值的对齐。
- **关键词：** SFT, alignment, fine-tuning

### Aligning LLMs for Crystal Material Design: Test-Time Reinforcement Learning and Model Merging

- **作者：** Pengyu Wang, Yang Han, Xin Chen, Kai Yu, Tong Zhu, Lu Chen, Bo Chen
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.2238/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.2238.pdf)
- **中文提要：** 条件晶体生成要求大语言模型写出同时含有离散变量和连续变量的晶体字符串，并满足成分、对称性与性质约束。期望区域在监督数据中往往很稀疏，而针对每种目标偏好重新训练的代价又很高。
- **关键词：** SFT, alignment

### ARMOR-PRM: Adversarially Robust Process Reward Models via Counterfactual Margins and Invariance Regularization

- **作者：** Hongyu Chen, Guangjia Chai, Haoxian Nan, Ruixue Wang, Peilin Jiang
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1287/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1287.pdf)
- **中文提要：** 优化压力下，策略会用自信措辞或规整格式等表面线索代替逻辑正确性，并出现倒 U 型崩溃。ARMOR-PRM 在标准过程奖励模型训练上加入反事实间隔损失，以及带低分锚定的对抗不变性损失，下一项正则在摘要里没有写完。
- **关键词：** PRM, reward-model

### Attend to Evidence: Evidence-Anchored Spatial Attention Supervision for Multimodal RLVR

- **作者：** Ruina Hu, Chen Wang, Lai Wei, Bai Jionghao, Bin Yu, Weiran Huang, Kai Wang, Yue Wang
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.204/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.204.pdf)
- **中文提要：** RLVR 用最终答案导出的结果奖励来优化视觉语言模型。只看结果的奖励并不会指出，答案是由图像的哪些区域支撑的。
- **关键词：** RLVR

### Attribute-Based Diagnosis of LLM Alignment with Hate Speech Annotations

- **作者：** Mohamed Amine Jradi, Faeze Ghorbanpour, Alexander Fraser
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1186/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1186.pdf)
- **中文提要：** 仇恨言论标注成本高、主观性强，而且标注者容易分歧，大规模建库因此困难。该分析比较大语言模型与人类在非人化、暴力和情感等有理论依据的主观属性上是否一致，并同时考察 Llama 3.1 与 Qwen 2.5 的不同规模版本。
- **关键词：** alignment

### Back to the Future: Forward-Only Committor Projection for Trajectory-Level Collapse Attribution in RLVR Reasoning

- **作者：** Jaeeun Jang, Hansle Lee, Sangmin Kim
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1720/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1720.pdf)
- **中文提要：** 摘要从一则对比写起：模型在高采样评测上反而不如自己的基座。现有缓解依据当前步的统计为词元打分，没有把崩溃看成随连贯批次漂移累积的轨迹级事件。
- **关键词：** GRPO, RLVR

### Balanced Aggregation: Understanding and Fixing Aggregation Bias in GRPO

- **作者：** Zhiyuan Zeng, Jiameng Huang, Zhangyue Yin, Bingrui Li, Jiashuo Liu, Yuhao Wu, Yining Zheng, Ge Zhang, Wenhao Huang, Xipeng Qiu, Ziniu Li
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.2120/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.2120.pdf)
- **中文提要：** RLVR 已成为提升大语言模型推理和代码生成的主要范式，GRPO 式训练因简单有效而广为采用。采样组内部如何聚合词元级策略梯度，这一设计选择仍缺少深入考察。
- **关键词：** GRPO, RLVR

### Better World Models Can Lead to Better Post-Training Performance

- **作者：** Prakhar Gupta, Henry Conklin, Sarah-Jane Leslie, Andrew Lee
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1012/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1012.pdf)
- **中文提要：** 以魔方为训练领域，显式的世界建模目标被用来考察 Transformer 的内部表示和下游能力。关心的问题包括：显式预训练世界模型会怎样改变潜在表示，世界模型质量如何影响后训练表现，以及有限数据预算怎样在预训练与后续阶段之间划分，最后一点在摘要中未写完。
- **关键词：** GRPO, post-training, fine-tuning

### Beyond Gradient Egalitarianism: Dual-Adaptive C-AUM Framework for Few-Shot Fine-Tuning of Large Language Models

- **作者：** Qiaojuan Peng, Xiong Luo, Yuqi Yuan, Wenbing Zhao
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1534/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1534.pdf)
- **中文提要：** 把大语言模型适配到样本很少的专门工业领域做文本分类，仍然困难。普通 SFT 对训练样本均匀加权，容易在简单样本上过拟合，对含糊的边界样本又优化不足。
- **关键词：** SFT, LoRA, fine-tuning

### Beyond GRPO and On-Policy Distillation: An Empirical Sparse-to-Dense Reward Principle for Language-Model Post-Training

- **作者：** Yuanda Xu, Hejian Sang, Zhengze Zhou, Ran He, Zhipeng Wang, Alborz Geramifard
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.639/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.639.pdf)
- **中文提要：** 可核验的标注数据一旦成为瓶颈，每个被检查的样本就应分配到信息量最高的模型和奖励密度上。由此归纳的奖励密度原则认为，稀疏的序列级奖励更适合仍能探索并发现更好行为的模型，稠密的词元级教师监督更适合压缩已发现的行为，压缩对象在摘要里未写完。
- **关键词：** GRPO, post-training

### Beyond One-Hot Replay: Self-Distillation Reduces Target Variance in Continual Pre-Training

- **作者：** Peng Lu, Sijie Dong, Xiaoyun Feng, Xuanwei Hu, Xin Zhang
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1299/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1299.pdf)
- **中文提要：** 把预训练语言模型持续预训练到目标领域时，即便用通用数据回放来减轻遗忘，通用能力也常常下降。从回放监督来看，以往做法主要调节数据配比和词元预算，却对领域词元和回放词元一律使用独热的下一词预测。
- **关键词：** continued-pretraining

### Beyond Ranking: Role-Specific Signals for Token-Budgeted SFT Data Selection

- **作者：** Haocheng Zhu, Tianqi Wang, Jun Suzuki
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1956/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1956.pdf)
- **中文提要：** 监督微调语料往往规模大且来源混杂，固定 token 预算下如何选数据就变得关键。单纯排序虽能提供信息，却决定不了这份预算该怎样分到各条样本上。
- **关键词：** SFT, instruction-tuning, post-training, fine-tuning

### Beyond Single-Negative Preference: Multi-Negative DPO for LLM-Centric Historical Entity Linking

- **作者：** Tien Nam Nguyen, Emanuela Boros, Ahmed Hamdi, Adam Jatowt, Mickael Coustaty, Antoine Doucet
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1873/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1873.pdf)
- **中文提要：** 用大模型做历史实体链接时，偏好优化常为每个训练实例只配一个负候选，同一提及下其余检索候选里的信息因此被丢掉。
- **关键词：** DPO, SFT, preference-optimization, fine-tuning

### Beyond the Sampled Token: Preserving Candidate Support in RLVR

- **作者：** Ruotian Peng, Yi Ren, Zhouliang Yu, Weiyang Liu, Yandong Wen
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.635/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.635.pdf)
- **中文提要：** 从下一词候选分布重新看 RLVR 里的探索坍缩：概率一旦集中到最高候选，不同回答的期望数量就会塌成单一结果，加大采样预算也改变不了这一点。
- **关键词：** RLVR

### Breaking the Structural Identity: Personalized Federated LoRA Fine-tuning under Rank Heterogeneity

- **作者：** Lei Wang, Jieming Bian, Letian Zhang, Jie Xu
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.608/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.608.pdf)
- **中文提要：** 联邦学习与 LoRA 结合，可以在隐私敏感的分布式数据上做较省资源的协作微调，资源异构和数据异构仍会妨碍实际部署。
- **关键词：** LoRA, fine-tuning

### Bridging the English-Arabic Medical Knowledge Gap: Targeted Low-Rank Adaptation via Causal Layer Selection

- **作者：** Chaimae Abouzahir, Musa Khan, Hala Ali-Hassan, Congbo Ma, Khaled Saleh, Yousra Sadqi, Jihad Mallat, Walid Al-Eisawi, Nizar Habash, Farah E. Shamout
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1089/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1089.pdf)
- **中文提要：** 大模型在英语医学任务上较强，到阿拉伯语就明显变差，这一落差常被归于训练数据不足。调谐透镜探测和因果激活修补显示，阿拉伯语医学知识已经存在于中间表示，却没有在输出端显现。
- **关键词：** LoRA, fine-tuning

### Candidate Pool Design for Safer Preference-Based Post-Training of LLM Companion Chatbots

- **作者：** Yuzhe Bai, Jia Cheng, Yunzhe Liu
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.476/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.476.pdf)
- **中文提要：** 基于偏好的后训练让聊天机器人贴合用户偏好，陪伴场景却有更隐蔽的安全问题：显得温暖、认可且有用的回复，也可能借单向迎合、冲突升级、谄媚或依赖来抬高社会风险。考察发生在偏好优化之前，即候选回复如何进入候选池。
- **关键词：** DPO, KTO, SFT, preference-optimization, post-training

### Can Post-Training Turn LLMs into Good Medical Coders? An Empirical Study of Generative ICD Coding

- **作者：** Ziqing Wang, Weihao Li, Shijie Chen, Yuan Luo, Kaize Ding
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.459/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.459.pdf)
- **中文提要：** 自动 ICD 编码服务于计费、流行病学和临床决策支持。生成式大模型常被看成不擅长医学编码，但这一印象主要来自提示、检索、重排或工具使用等推理时设定，任务专用后训练的作用仍缺少系统讨论。
- **关键词：** GRPO, SFT, post-training, fine-tuning

### CePRM: Generative Process Reward Modeling with Calibrated Values and Repair-Aware Supervision

- **作者：** Zongxuan Li, Yixiang Dong, Bo Hu, Gonghao Cao, Yanzhen Chen, Huan Liu
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1923/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1923.pdf)
- **中文提要：** 生成式过程奖励模型改善了数学推理的步骤级校验，效果却受过程监督质量限制。主流蒙特卡洛估计按最终答案对错而不是语义是否正确来标注步骤，带来系统性标签噪声，常规流程还会丢掉采样数据中隐含的树结构。
- **关键词：** PRM, reward-model

### CHILLGuard: Towards Fine-Grained Chinese LLM Safety Guardrail with Scalable Data Construction and Model-aware Preference Alignment

- **作者：** Wenbo Yu, Bohua Wang, Hao Fang, Kuofeng Gao, Jingru Zeng, Xiaochen Yang, Tianyi Zhang, Xiaoxiao Ma, Jiawei Kong, Hao Wu, Bin Chen, Shu-Tao Xia, Min Zhang
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1721/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1721.pdf)
- **中文提要：** 大模型生成的恶意内容带来安全和伦理隐患。现有护栏在英语或多语设定下表现较好，却缺少对中国监管政策、文化语境和语言细节的适配，也支撑不了面向不同部署需求的细粒度风险分类。
- **关键词：** DPO, preference-optimization, alignment

### Continual Fine-Tuning of Large Language Models via Program Memory

- **作者：** Hung Le, Svetha Venkatesh
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1048/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1048.pdf)
- **中文提要：** 算力受限时，PEFT，尤其是 LoRA，已是适配大模型的常用做法。模型用小数据集依次更新时，常规 LoRA 更新很难同时做到快速适应和保住已有知识。
- **关键词：** LoRA, PEFT, fine-tuning

### CoRe-MoE: Compact Reusable MoE for Continual Multimodal Instruction Tuning

- **作者：** Runze Liu, Naibin Gu, Mingxu Ai, Yuqing Li, Peng Fu, Zheng Lin, Weiping Wang
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.790/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.790.pdf)
- **中文提要：** 持续的多模态指令微调要求模型依次学会新任务，同时留下先前的知识。LoRA-MoE 用基于专家的容量来应对，但反复学习并维护完整的 LoRA 专家会带来明显的参数开销。
- **关键词：** instruction-tuning, LoRA, PEFT

### CoVA-SFT: A Large-Scale Dataset for Chain of Visual Abstractions

- **作者：** Tsung-Han Wu, Heekyung Lee, Anya Ji, Haoming Chen, Trevor Darrell, Joseph E. Gonzalez, David M. Chan
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.526/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.526.pdf)
- **中文提要：** 思维链让模型把问题拆成中间步骤，在语言任务上很有效；只剩文本思维链时，视觉问题就不得不被写成别扭的散文。
- **关键词：** SFT, fine-tuning

### CPSD: Counterfactual Patches Self-Distillation in RLVR

- **作者：** Yixiao Zhou, Dongzhou Cheng, Hehe Fan, Yu Cheng
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.2079/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.2079.pdf)
- **中文提要：** RLVR 中的自蒸馏用组内成功采样去教失败样本，不依赖外部教师。它是否真有帮助，取决于如何为失败样本构造合适的教师上下文，以及蒸馏损失应作用在回复的哪一段。
- **关键词：** GRPO, RLVR

### Critic-R: Improving Agentic Search using Instruction-tuned Retrievers with Natural Language Introspective Feedback

- **作者：** Md Zarif Ul Alam, Alireza Salemi, Hamed Zamani
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.2048/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.2048.pdf)
- **中文提要：** 智能体搜索通过与检索模型反复交互来回答复杂查询。为这类搜索优化检索器仍然困难，往往需要沉重的联合训练或金标准标注，实际使用因此受限。
- **关键词：** instruction-tuning

### CroCo: Cross-Lingual Contrastive Preference Tuning on Self-Generations

- **作者：** Mike Zhang, Ali Basirat, Desmond Elliott
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1369/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1369.pdf)
- **中文提要：** 已有工作表明，用奖励分数控制大模型自生成回答之间的对比程度，可以改善英语上的下游偏好微调。同一做法被扩展到多种语言，并在高低资源语言的多种任务上做了评估。
- **关键词：** SFT, preference-optimization, reward-model, fine-tuning

### Decouple and Orthogonalize: A Data-Free Framework for LoRA Merging

- **作者：** Shenghe Zheng, Hongzhi Wang, Chenyu Huang, Xiaohui Wang, Jiayuan Fan, Shuyue Hu, Peng Ye
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1516/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1516.pdf)
- **中文提要：** 开源的任务专用模型越来越多，模型合并成了把多个模型合成一个的实用途径。现有研究主要针对全量微调模型，对广泛使用的 LoRA 模块关注不足。
- **关键词：** LoRA, fine-tuning

### DeepResearch RewardBench: Evaluating Reward Models for Deep Research Report

- **作者：** Shudong Liu, Yuting Zhong, Guanhua Chen, Xinyi Yang, Junnan Liu, Lidia S. Chao, Jiaheng Liu, Derek F. Wong
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1611/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1611.pdf)
- **中文提要：** 深度研究系统借助大模型，经多步网页检索和信息综合把在线资料写进研究报告。这类报告上下文长、信息密度高且领域性强，人工评估代价过高，因而需要自动评价来替代。
- **关键词：** reward-model

### Diagnosing and Selecting Synthetic Motion Tasks for Video RLVR

- **作者：** Yishu Lei, Aofan Liu, Danxiang Zhu, Canming Ye, Dan Zhang, Songhe Deng, Xianlong Luo, Shikun Feng
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1176/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1176.pdf)
- **中文提要：** 带可验证奖励的合成视频能为视频语言模型的时序运动理解提供可扩展监督，但哪些合成任务能稳定迁到真实视频基准尚不清楚。诊断框架把每个合成任务当作一次受控干预，并从共享检查点出发、在冻结视觉模块的设定下展开。
- **关键词：** RLVR, alignment

### Difficulty-Adaptive Tree-Structured Policy Optimization for Expanding Reasoning Coverage in RLVR

- **作者：** Youngjun Yu, Sanghwan Jang, Hwanjo Yu
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1137/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1137.pdf)
- **中文提要：** RLVR 是近期大推理模型取得进展的核心途径。它明显提高了单样本准确率，却常因训练时探索有限，扩不开模型内在的推理覆盖。
- **关键词：** RLVR

### DOG-DPO:Dynamic Optimization in Geometry for Safety Alignment

- **作者：** Yi Nian, Tiankai Yang, Yudi Zhang, QI Pan, Zelong Xu, Shenzhe Zhu, Qingqing Luan, Yue Huang, Xiangliang Zhang, Yue Zhao
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.482/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.482.pdf)
- **中文提要：** 安全对齐高度依赖偏好数据，现有流程却常在庞大且冗余的数据集上训练，并用标量质量分把每个偏好对当成独立样本。这种以样本为中心的做法忽略了：偏好对在表示空间里给出的是方向性对齐信号，而不是孤立样本。
- **关键词：** DPO, alignment

### Domain Mixture Design via Log-Likelihood Differences for Aligning Language Models with a Target Model

- **作者：** Ryo Kishino, Riku Shiomi, Hiroaki Yamagiwa, Momose Oyama, Hidetoshi Shimodaira
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1431/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1431.pdf)
- **中文提要：** 与其直接蒸馏语言模型，这项研究把预训练或继续预训练的领域混合设计成固定配方，使基座模型在分布上向目标模型对齐。领域权重的取法，是把模型看成对数似然空间中的点，并据此调整训练更新的方向。
- **关键词：** continued-pretraining, alignment

### Donors and Recipients: On Asymmetric Transfer Across Tasks and Languages with Parameter-Efficient Fine-Tuning

- **作者：** Kajetan Dymkiewicz, Ivan Vuli{\'c}, Helen Yannakoudakis, Eilam Shapira, Roi Reichart, Anna Korhonen
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.67/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.67.pdf)
- **中文提要：** 某一任务或语言上的改进会怎样波及其他任务和语言，目前仍不清楚。作者在多个开源权重模型家族和规模上做了受控 LoRA 微调，并用统一的语言与基准网格观察这种迁移。
- **关键词：** LoRA, PEFT, fine-tuning

### Emulate or Estimate? The Divergent Strengths of Base and Post-Trained Language Models for Opinion Simulation

- **作者：** Seth Grief-Albert, Jessica Bo, Difan Jiao, Ashton Anderson
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1379/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1379.pdf)
- **中文提要：** 用大模型模拟人类意见的已有结论互相冲突：有的与问卷数据较为吻合，有的则出现人设坍缩、对人口统计特征不敏感。冲突多半来自把两件不同的任务混在一起。
- **关键词：** post-training, alignment

### Entropy-Adaptive Fine-Tuning: Resolving Confident Conflicts to Mitigate Forgetting

- **作者：** Muxi Diao, Lele Yang, Wuxuan Gong, Yutong Zhang, Zhonghao Yan, Yufei Han, Kongming Liang, Weiran Xu, Zhanyu Ma
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.703/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.703.pdf)
- **中文提要：** 领域适配的标准做法是 SFT，代价常常是灾难性遗忘。同策略强化学习则形成对照，更能保住通用能力。
- **关键词：** SFT, fine-tuning

### Entropy-KL Divergence-based Token Masking: A Novel Approach for Selective Fine-tuning of Large Language Models

- **作者：** Qi Liu, Mingdi Sun, Yongyi He, Zhi Zheng, Tong Xu, Yi Zheng, Zhefeng Wang, Enhong Chen
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.233/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.233.pdf)
- **中文提要：** 先 SFT 再强化学习，已成为大模型后训练的常规路径。它为强化学习探索提供冷启动，避免纯强化学习在同策略采样中正样本不足所带来的低效。
- **关键词：** RFT, SFT, post-training, fine-tuning

### Equitable Alignment of LLMs Across Languages with Regularized Direct Preference Optimization

- **作者：** Thibaud Leteno, Antoine Gourru, Charlotte Laclau, Christophe Gravier
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.121/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.121.pdf)
- **中文提要：** 让大模型对齐人类价值关系到公共安全，常见途径包括 DPO，以及 RLAIF 与 RLHF。
- **关键词：** DPO, RLHF, RLAIF, preference-optimization, alignment, fine-tuning

### Ethical Imprints in LLMs: From Corpus Ethics to ICL, SFT, and Their Interaction on Deception Dilemmas

- **作者：** Jiafeng Wang, Jiale Chen, Zheng Luo, Xinyi Yan, Lingpeng Kong
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1808/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1808.pdf)
- **中文提要：** 大模型会给出稳定的道德判断，这些倾向是否对应同一种语言里公开网页文本的道德构成并不清楚。中英文欺骗困境上的分层实证用来检验这种对应。
- **关键词：** SFT, post-training, alignment, fine-tuning

### Evaluate-as-Action: Self-Evaluated Process Rewards for Retrieval-Augmented Agents

- **作者：** Jiangming Shu, Yuxiang Zhang, Ye Ma, Xueyuan Lin, Jitao Sang
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1143/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1143.pdf)
- **中文提要：** 检索增强智能体可以查询外部证据，多步推理仍不可靠：噪声检索可能带偏多跳问答，只看结果的强化学习给出的信用信号又太粗，不足以优化中间步骤。EvalAct 把隐含的检索质量评估转成一种动作。
- **关键词：** GRPO, PRM

### EVALUESTEER: Measuring Reward Model Steerability Towards Values and Preferences

- **作者：** Kshitish Ghate, Andy Liu, Devansh Jain, Taylor Sorensen, Atoosa Kasirzadeh, Aylin Caliskan, Mona T. Diab, Maarten Sap
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.572/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.572.pdf)
- **中文提要：** 模型走向全球部署后，能容纳不同价值与偏好的多元系统变得必要。EVALUESTEER 是经过人工校验的基准，用来测量语言模型和奖励模型能否被导向用户的价值画像与文风偏好，这些画像依据心理学和人机交互文献来设定。
- **关键词：** reward-model, alignment

### FCPRAG: Fusion-Controller Parametric Retrieval-Augmented Generation for Stable Multi-Passage LoRA Injection

- **作者：** Jinchang Zhu, Jindong Li, YI Ding, Nie Xiaojian, Rong Fu, Shuangyong Song, Haowei He, Menglin Yang
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1473/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1473.pdf)
- **中文提要：** 参数化检索增强生成用篇章专用的 LoRA 适配器把检索证据注入大模型，从而少依赖很长的上下文提示。同一查询命中多篇材料时，证据层融合成为瓶颈，等权合并会放大薄弱或互相冲突的证据。
- **关键词：** LoRA

### FedLoRAGuard: Federated Dynamic Graph Neural Networks with Differential-Privacy Certificates for LoRA Adapter Integrity Verification

- **作者：** Roger Nick Anaedevha, Alexander Trofimov, Borodachev Yuri Vladimirovich
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1463/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1463.pdf)
- **中文提要：** LoRA 已成为大模型参数高效微调的主流方法，公开适配器市场也随之成为供应链攻击面：后门适配器可以在保持表面效用的同时，静默并入任意任务适配器。现有集中式完整性工具还要求市场共享原始权重。
- **关键词：** LoRA, PEFT, fine-tuning

### FedSubMuon: Communication-Efficient Federated LLM Fine-Tuning via Structured Subspace Muon

- **作者：** Shaolong Chen, Youming Tao, Shuzhen Chen, Falko Dressler, Qingqing Ye, Di Wang
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.990/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.990.pdf)
- **中文提要：** 联邦微调把大模型适配到分散的客户端数据，跨设备训练却常被高通信成本限制规模。Muon 通过对矩阵参数的动量做正交化来改善优化。
- **关键词：** instruction-tuning, LoRA, fine-tuning

### FreeMU: Free Marginal Utility for Reward-Aware Direct Preference Optimization

- **作者：** Lei Zhang, Jian Ma, Xianpeng Zhang, Dongyu Chen, Haonan Lu, Tianhuang Su, Chuangchuang Wang, Kai Tang, Zhixun Su
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1871/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1871.pdf)
- **中文提要：** ODPO、MODPO 这类感知奖励的 DPO 变体默认偏好信号的边际效用是线性的：同样的信号差距带来同样的梯度更新，不论偏好对落在低质量还是高质量区域。FreeMU 是轻量、可即插即用的训练模块，借助成对信息引入非线性边际效用。
- **关键词：** DPO, preference-optimization, alignment

### From Evasive Servants to Dignified Peers via Dual Preference Optimization

- **作者：** Xiangqi Wang, Yue Huang, Haomin Zhuang, Kehan Guo, Xiangliang Zhang
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.197/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.197.pdf)
- **中文提要：** 已对齐的语言模型会出现所谓回避型仆从：一边谄媚地附和用户的错误信念，一边用套话免责声明推卸责任。Dignified Peer 用反谄媚与可信度针对奴性，用共情与创造性针对回避。
- **关键词：** DPO, preference-optimization

### From Homogeneity to Diversity: Self-Refined GRPO for Controllable Creative Writing

- **作者：** Minna Peng, Wei Tan, Zeyu Wang, Yongquan Hu, Ruizhi Huang, Yang Jie
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.972/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.972.pdf)
- **中文提要：** 可控创意写作既要生成质量，也要输出多样，现有方法却常常提升一面、牺牲另一面。
- **关键词：** GRPO, reward-model

### From Isolation to Alignment: Unified LoRA for Efficient Multi-Task Learning

- **作者：** Jinda Liu, Yi Chang, Yuan Wu
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.146/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.146.pdf)
- **中文提要：** 多任务场景下适配大模型离不开 PEFT。常见路线是带多个适配器或多个头的复杂 LoRA 变体，其前提是必须在结构上把各任务知识隔离开。
- **关键词：** LoRA, PEFT, alignment, fine-tuning

### From Tokens to Regions: CUDA-Sensitive Instruction Tuning for GPU Kernel Generation

- **作者：** Wentao Chen, Jiace Zhu, Qu Zeng, Qiaoling Xiao, Liucheng Duan, An Zou
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.2045/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.2045.pdf)
- **中文提要：** 可扩展的人工智能系统依赖高性能 CUDA 内核，大模型却仍难生成正确内核，因为执行约束严格且常常隐含。现有路线要么依赖昂贵的智能体或强化学习流程，要么采用未能显式刻画 CUDA 敏感性的 SFT 目标。
- **关键词：** SFT, instruction-tuning, post-training, fine-tuning

### FSA-GRPO: Teaching Auditory LLMs to Use Few-Shot Demonstrations

- **作者：** Haolong Zheng, Siyin Wang, Xulin Fan, Zengrui Jin, Mark A. Hasegawa-Johnson
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.388/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.388.pdf)
- **中文提要：** 少样本提示能把听觉大模型适配到儿童语音识别这类低资源任务。多数听觉大模型并未按这种带示范的格式做过推理训练，能从上下文学习中得到的收益因此有限。
- **关键词：** GRPO, post-training

### Function-Level Execution Feedback for Code Preference Optimization

- **作者：** Idris Nechnech, Sehwan Kim, Jimin Seo, Yeongoon Kim, Minhae Oh, Sangwoo Hong, Jungwoo Lee
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.948/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.948.pdf)
- **中文提要：** 过程监督改善了数学推理，中间步骤在那里天然写成思维链。代码生成缺少公认的步骤定义，过程监督因此仍少被研究。
- **关键词：** DPO, KTO, preference-optimization

### Fusian: Multi-LoRA Fusion for Fine-Grained Continuous MBTI Personality Control in Large Language Models

- **作者：** Zehao Chen, Rong Pan
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1626/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1626.pdf)
- **中文提要：** 大模型模拟多样人类行为与人格的能力已经很强。提示工程和标准 SFT 这类人格控制方法，通常把人格特质当成离散类别。
- **关键词：** SFT, LoRA, alignment, fine-tuning

### GIFT: Reconciling Post-Training Objectives via Variational Finite-Temperature Gibbs Initialization

- **作者：** Zhengyang Zhao, Lu Ma, Yizhen Jiang, Xiaochen Ma, Zimo Meng, Chengyu Shen, Lexiang Tang, Haoze Sun, Peng Pei, Wentao Zhang
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1285/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1285.pdf)
- **中文提要：** 大推理模型常见的后训练是先 SFT 再强化学习，两者存在内在错配：SFT 里刚性的似然最大化会造成分布坍缩，耗尽后续强化学习需要的探索空间。作者从 KL 正则强化学习的吉布斯最优出发，推导了一种词元级形式。
- **关键词：** SFT, post-training, fine-tuning

### GMTS: Gradient Magnitude-based Token Selection Improves RLVR Training for LLM Reasoning

- **作者：** Outongyi Lv, Yuanwei Zhang, Xiaoqun Zhang
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.2429/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.2429.pdf)
- **中文提要：** 强化学习，尤其是 RLVR，已成为增强大模型推理的主要路径。已有观察认为，高熵词元在训练里的作用格外突出。
- **关键词：** RLVR

### GRAIL: Gradient-Reward Aligned Initialization for LoRA-based GRPO

- **作者：** Liwen Shi, Zijie Zeng, Bowen Wang, Yunji, Zeyu Chen, Xinyu Shao, Xinzheng Sun, Xuyang Xiong, Haoyang Wu, Sheng Zhang
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.926/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.926.pdf)
- **中文提要：** 基于 LoRA 的 GRPO 在初始适配器子空间与奖励诱导梯度对齐不佳时，推理上的收益会变弱。GRAIL 在策略优化之前从分组采样估计与奖励对齐的梯度，并用这些梯度构造 LoRA 因子。
- **关键词：** GRPO, LoRA

### GREAT: Generalizable Backdoor Attacks in RLHF via Emotion-Aware Trigger Synthesis

- **作者：** Subrat Kishore Dutta, Yuelin Xu, Piyush Pant, Xiao Zhang
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1737/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1737.pdf)
- **中文提要：** 近期工作表明 RLHF 很容易遭受后门攻击。现有攻击常依赖罕见词元或固定触发器，在真实场景中的影响因此有限。
- **关键词：** RLHF

### GroupDPO: Memory-Efficient Group-Wise Direct Preference Optimization

- **作者：** Jixuan Leng, Si Si, Hsiang-Fu Yu, Vinod Raman, Inderjit S Dhillon
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.3/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.3.pdf)
- **中文提要：** 偏好优化被广泛用来让大模型贴合偏好反馈。多数方法每个提示只训练一对正负回答，偏好数据里通常还有多个候选，其中的额外监督就被丢掉了。
- **关键词：** DPO, preference-optimization

### Hierarchical Alignment: Block-Level LoRA-DPO for Preference Tuning in Large Language Models

- **作者：** Yishen Chen, Qi Dong, Yukun Zhang
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.345/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.345.pdf)
- **中文提要：** 偏好微调一般把适配器更新铺到每一层 Transformer。在固定 LoRA 预算下，更新放在哪些层会怎样影响 DPO，是这里要考察的问题。
- **关键词：** DPO, preference-optimization, LoRA, alignment

### How does Multilingual Finetuning of Instruction-Tuned Large Language Models Affect Languages in Layer-Wise Hidden Representations?

- **作者：** Hyemi Jo, Hyopil Shin
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.176/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.176.pdf)
- **中文提要：** 当代大模型虽有多语能力，仍以英语为中心，各语言之间的性能差距因此持续存在。一些多语训练借助隐含的枢纽语言假说来提高可解释性，训练过程中每一层所表征的语言如何变化仍少有讨论。
- **关键词：** instruction-tuning, LoRA, fine-tuning

### HuggingBrew: Brewing High-Quality Mid-Training Data from the HuggingFace Community Datasets

- **作者：** Han Zhang, Ningqi Chen, Xiao Liu, Zhenghao Lin, Yeyun Gong, Yan Lu, Hanfang Yang
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1519/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1519.pdf)
- **中文提要：** 数据整理在预训练和后训练阶段已有大量研究，介于通用预训练与任务微调之间的中期训练却仍然明显不足。面向先进模型的中期训练数据大多仍不公开。
- **关键词：** continued-pretraining, mid-training, post-training, fine-tuning

### IFMTBench: A Comprehensive Benchmark for Multilingual Translation Instruction Following

- **作者：** Mingrui Sun, Mao Zheng, Zheng Li, Mingyang Song
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1016/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1016.pdf)
- **中文提要：** 现代翻译流程要求的不止语义对等。用户还经常要求保持 JSON 或 HTML 结构、遵守整理好的术语表、结合给定上下文消歧，并匹配指定语域，而且常常几项同时提出。
- **关键词：** instruction-following

### Instruction-Tuned Language Models Cannot Sample from Distributions They Can Describe

- **作者：** Chaemin Jang, Jihee Kim, Dongman Lee
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.2278/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.2278.pdf)
- **中文提要：** 硅采样把语言模型当作人类问卷受访者的代理，并把每次调用看成从人设回答分布中独立抽取的一次。这种抽取并不存在：指令微调后的模型并不是在分布上采样，而是塌缩到单一输出。
- **关键词：** instruction-tuning, continued-pretraining, post-training

### Intervention-Certified Amplification: A Validity Gate for $\sigma$-Weighted Post-Training

- **作者：** Leiyue Chen, Meng Wei, Xuefeng Hu, Wei Liu
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.2090/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.2090.pdf)
- **中文提要：** 后训练用训练侧信号决定强调哪些监督，但这些信号未必对应目标环境里真正承载能力的行为。DIAA 以按样本混合 SFT 与强化学习的方式探测这一点，并在去掉字面 Python 代码围栏的设定下进行。
- **关键词：** GRPO, RFT, SFT, post-training

### Is LoRA Robust to Adversarial Attacks? Expectation-Based Regularization for Parameter-Efficient Adversarial Training

- **作者：** Mingze Ni, Yongshun Gong, Xinghao Yang, Wei Liu
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1638/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1638.pdf)
- **中文提要：** LoRA 广泛用于参数高效微调，它对文本对抗扰动是否稳健仍少有研究。现有对抗训练常通过代价高昂的极小极大目标、并在内层优化扰动来提升稳健性，结果并不理想。
- **关键词：** LoRA, PEFT, fine-tuning

### KARMA: Karma-Aligned Reward Model Adaptation

- **作者：** Jared Scott, Jesse Roberts
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.2243/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.2243.pdf)
- **中文提要：** 人类交流依赖隐含的社会信号，效果由语气、语境和会话规范共同塑造，而不只由语义内容决定。KARMA 是一套奖励模型适配框架，让大模型从大规模社交媒体数据中学习对语境敏感的会话行为。
- **关键词：** reward-model, alignment, fine-tuning

### Knowing When to Speak: Aligning LLM Honesty via Solvability-Aware Preference Optimization

- **作者：** Wenpeng Lu, Xueguan Zhao, Shuxia Lin, Linhai Zhang, Chaoqun Zheng, Weiyu Zhang, Jiasheng Si
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.2451/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.2451.pdf)
- **中文提要：** 大模型常有不诚实的表现：对超出知识边界的问题自信地编造答案，或对已经掌握的问题过分回避。现有缓解已经推进到划定知识边界，但这条边界通常仍被粗分成已知与否。
- **关键词：** DPO, preference-optimization, alignment

### Knowledge is Still There: Why RL Beats SFT for Sustainable Continual Machine Translation

- **作者：** Junhong Wu, Yang Zhao, Yangyifan Xu, Chengqing Zong
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.2340/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.2340.pdf)
- **中文提要：** 持续机器翻译的传统研究长期假定，灾难性遗忘来自底层语言知识被不可逆地抹掉。这一通行看法在大模型的语境下受到质疑。
- **关键词：** SFT, alignment, fine-tuning

### LaRA: Layer-wise Representation Analysis for Detecting Data Contamination in RL Post-Training

- **作者：** Minju Gwak, Minseo Kwak, Dongseok Lee, Guijin Son, Alan Ritter, Jaehyung Kim
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.690/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.690.pdf)
- **中文提要：** 强化学习后训练被用来提升大模型推理，这一阶段的数据污染却几乎没有被讨论，而这可能动摇训练过程本身的泛化与评测可靠性。
- **关键词：** post-training

### Latent-LoRA: Compact Latent-Space Adapters with Gradient-Free Routing for Continual Learning

- **作者：** Reza Rahimi Azghan, Gautham Krishna Gudur, Pavan K. Turaga, Giulia Pedrielli, Hassan Ghasemzadeh
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1390/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1390.pdf)
- **中文提要：** 大模型擅长单个任务，却缺少按顺序学习多项任务的内在机制，因而出现灾难性遗忘。基于 LoRA 的持续学习为每个任务单独分配低秩适配器，现有做法要么推理时需要任务身份，要么不加区分地叠加全部适配器，让无关分支扭曲输出。
- **关键词：** LoRA

### LEAF: Growing Trees Without Branching for Speech-Aware Large Language Model Post-Training

- **作者：** Argyrios Gerogiannis, Yekaterina Yegorova, Mark A. Hasegawa-Johnson, Venugopal Veeravalli
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1327/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1327.pdf)
- **中文提要：** 面向语音的大模型后训练里，先进的 GRPO 式方法信用分配过粗，把同一终端奖励优势广播到回复中的每个词元。这忽略了采样批次内部的结构：以语音为条件的补全常常共享前缀，再在关键决策处分开。
- **关键词：** GRPO, LoRA, post-training

### Learning New Facts with QLoRA: An Acquisition-Retention Frontier

- **作者：** Estelle Zheng, S{\'e}bastien Warichet, Emmanuel Helbert, Christophe Cerisara
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.918/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.918.pdf)
- **中文提要：** PEFT 常被假定能保住预训练能力，理由是它只更新少量参数。这一判断在很大程度上取决于适配器容量。
- **关键词：** QLoRA, PEFT, fine-tuning

### Learning to Reason by Analogy via Retrieval-Augmented Reinforcement Fine-Tuning

- **作者：** Zilin Xiao, Qi Ma, Chun-cheng Jason Chen, Xintao Chen, Avinash Atreya, Hanjie Chen, Vicente Ordonez
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1353/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1353.pdf)
- **中文提要：** 检索增强生成常用来把语言模型锚定到外部知识，但基于词面或语义相似度的检索并不适合复杂推理：语义相近的问题可能需要完全不同的解法，表面不同的问题却可能共享同一推理模式。
- **关键词：** GRPO, RFT, post-training, fine-tuning

### LiST: Local-Simplex Test-Time LoRA Fusion

- **作者：** Yihua Shao, Jia Li, Siyu Chen, Xinyu Luo, Yang Liu, Kecheng Chen, Xinwei Long, Lingyu Zhu, Fanhu Zeng, Maolin Wang, Ziyang Yan, Jingcai Guo, Hao Tang, Nicu Sebe, Zhenyi Wang
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.906/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.906.pdf)
- **中文提要：** 任务专用的 LoRA 适配器提供了一种模块化方式，用来特化大语言和视觉语言模型。现有适配器组合大多是静态的，无法随单条测试输入调整。
- **关键词：** LoRA

### LLMZERO: Discovering Adaptive Training Strategies for RL Post-Training via LLM Agents

- **作者：** Haoyang Fang, Wei Zhu, Boran Han, Zhenyu Pan, Shuo Yang, Shuai Zhang, Jiading Gai, Peng Tang, Cuixiong Hu, Huzefa Rangwala, George Karypis, Bernie Wang
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1866/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1866.pdf)
- **中文提要：** 强化学习后训练策略依赖具体数据集：容量类参数跨阶段单调累积，正则类参数则主要随训练动态振荡。这种差别显示出固定训练日程的问题，即把全部参数压在僵硬路径上，便难以捕捉这种动态。
- **关键词：** GRPO, post-training

### Macro: Enhancing Multilingual Counterfactual Explanations through Alignment-as-Preference Optimization

- **作者：** Yilong Wang, Qianli Wang, Bohao Chu, Yihong Liu, Jing Yang, Simon Ostermann
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.151/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.151.pdf)
- **中文提要：** 自生成反事实解释由大语言模型对输入做最小改动并翻转自身预测，为拆解黑盒行为提供因果依据。将其扩展到英语之外仍然困难，现有方法难以在非主导语言上产出有效解释，并存在持续的权衡。
- **关键词：** DPO, SFT, preference-optimization, alignment, fine-tuning

### MeDocVL: Noise-Aware Post-Training of Visual Language Models for Medical Document Parsing

- **作者：** Wei Wu, Liang Diao, Yuan Zhao, Wenjie Wang, Ying Liu, Xiaole Lv
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.2321/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.2321.pdf)
- **中文提要：** 医疗文档这类高精度解析受复杂版式、专门术语，以及噪声监督下字段级精确匹配要求的制约。现有 OCR 流程和通用视觉语言模型，在实际键值抽取中往往不够可靠。
- **关键词：** SFT, post-training

### Meeseeks-Multilingual: A Multi-Turn, Multi-Constraint Benchmark evaluating Multilingual Instruction-Following and Self-Correction

- **作者：** Jiaming Wang, Hefei Chen, Zhe Tang, Zehao Jin, Yanxin Zhuo, Ruicheng Liao, Jinrong Ma, Xiaoyu Li, Xuezhi Cao
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.2349/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.2349.pdf)
- **中文提要：** 大语言模型难以在不同语言中稳定遵循多约束指令，地区性语言规则与一般约束叠加时失败更明显。Meeseeks-Multilingual 把 Meeseeks 扩展为多轮、由反馈驱动的多语言与跨地区评测基准。
- **关键词：** instruction-following

### M-GOAL: Toward Accurate and Language-Consistent Reasoning in LLMs via English-Only Post-Training

- **作者：** Dingyuan Dai, Yuxi Chen, Jiayuan Wang
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1232/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1232.pdf)
- **中文提要：** 面向推理的语言模型从预训练继承英语中心偏向，纯英语后训练又会加强这种偏向。由此出现双重失败：模型既可能推理不正确，也难以把推理轨迹保持在查询所用的语言中。
- **关键词：** GRPO, SFT, LoRA, post-training

### Mitigating Exploration Bias in RL for Multi-Instruction Following

- **作者：** Mian Zhang, Yueqin Yin, Kaiyu He, Peilin Wu, Xinlu Zhang, Mingyuan Zhou, Zhiyu Chen
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.786/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.786.pdf)
- **中文提要：** 强化学习已成为增强大语言模型指令遵循能力的有力范式。当一条训练提示中含有多条指令时，现有训练配方会出现偏向容易指令的探索偏差。
- **关键词：** instruction-following, fine-tuning

### MoE Sparsity Begets Monosemanticity: Insights into Understanding and Fine-Tuning

- **作者：** Mingxue Tian, Qi Zhang, Xiaohan Wang, Jiajun Chai, Guojun Yin, Wei Lin, Cailian Chen, Qimin Xu, Siyu Wang, Yisen Wang
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.975/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.975.pdf)
- **中文提要：** 混合专家架构只激活一部分参数，从而提升大语言模型的可扩展性与效率。单个专家怎样被解释，以及如何做面向领域任务的后训练适应，仍然缺少充分研究。
- **关键词：** LoRA, PEFT, post-training, fine-tuning

### Monitorable Chart Reasoning Agents via Verifiable Process Rewards

- **作者：** Sanchit Sinha, Oana Frunza, Kashif Rasul, Aidong Zhang
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.691/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.691.pdf)
- **中文提要：** 图表推理智能体越来越多地用于在关键领域提取可执行洞察，并在多项基准上取得领先表现。仅有很高的基准准确率仍不足以部署，相关方必须能够审计并核验模型如何得出答案。
- **关键词：** SFT, PRM

### Navigating Intention Reasoning Trees to Guide Agentic Preference Optimization

- **作者：** Ziben Yue, Hongyu Yang, Weixin Li
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1740/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1740.pdf)
- **中文提要：** 理解视频中的人类意图需要深层认知推理，多模态大语言模型却经常出现事实幻觉，也对反事实缺乏敏感。ASTRO 通过遍历意图推理树来引导偏好优化。
- **关键词：** DPO, preference-optimization

### Negative Advantage Is a Double-Edged Sword: Calibrating advantages in GRPO for Search Agents

- **作者：** Jiayi Wu, Ruobing Xie, Zeqian Huang, Lei Jiang, Can Xu, Kangyang Luo, Bochen Lin, Ming Gao, Xiang Li
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1874/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1874.pdf)
- **中文提要：** 搜索智能体借助与搜索引擎的多轮交互取得较强的问答表现，GRPO 是其中广泛使用的训练算法。在多跳搜索设定下，这类 GRPO 式算法仍然面临若干挑战。
- **关键词：** GRPO

### Neuron-Guided Fine-Tuning: Unlocking Efficient Alignment Mechanisms for Large Language Models

- **作者：** Zeyu Wu, Junchao Wu, Shudong Liu, Runzhe Zhan, Xin Chen, Shu Yang, Yichao Du, Longyue Wang, Weihua Luo, Jinsong Su, Derek F. Wong
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1562/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1562.pdf)
- **中文提要：** 现有监督微调，尤其是全参数微调，常受参数冗余、数据质量不一致和灾难性遗忘困扰，而现有办法通常把这些问题分开处理，缺少贯通数据选择、参数更新与知识保持的统一优化信号。为此提出神经元引导微调 NGFT。
- **关键词：** SFT, alignment, fine-tuning

### Not All Components Forget Alike: Component-Level Intervention Profiles in Continual Pretraining

- **作者：** Sangyeol Baek, Suan Lee
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1583/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1583.pdf)
- **中文提要：** 持续预训练能把语言模型适配到新领域，但可能拉低早先领域上的表现。这种退化可借助 Transformer 块内部的组件级干预来考察。
- **关键词：** continued-pretraining

### Not All LoRA Parameters Are Essential: Insights on Inference Necessity

- **作者：** Guanhua Chen, Yutong Yao, Ci-Jun Gao, Lidia S. Chao, Yujia Huo, Feng Wan, Derek F. Wong
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.2000/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.2000.pdf)
- **中文提要：** 当前 LoRA 研究主要集中在减少微调参数数量，或优化其结构。推理阶段是否必须保留全部已微调的 LoRA 层，仍然较少被讨论。
- **关键词：** LoRA, fine-tuning

### OmniDA: Grounding Agentic Multimodal Data Analysis with Evidence-Aware Process Rewards

- **作者：** Xuhang Zhu, Liyao Li, Ningtao Wang, Yanyu Chen, Hao Chen, Wentao Ye, Ziquan Wang, Haoxing Zhai, Yu Cheng, Gang Chen, Xiu Tang, Haobo Wang
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1066/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1066.pdf)
- **中文提要：** 真实数据分析常常需要联合推理表格、图表和文本报告等异构材料。训练可靠的多模态大语言模型智能体仍然困难：大规模对齐数据稀缺，只看结果的奖励也过粗，分不清有依据的跨来源分析与虚假成功。
- **关键词：** PRM

### One Rate Is Not Enough: Adaptive Anisotropic Learning Rates for LoRA Fine-Tuning

- **作者：** Huiyi Wang, Daijiao Liu, Lina Yao, Dong Gong
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.2469/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.2469.pdf)
- **中文提要：** 低秩适配 LoRA 已成为大语言模型参数高效微调的标准做法。多数变体遵循统一学习率惯例，对每个适配器的每个秩一分量施加同一个全局学习率。
- **关键词：** instruction-tuning, LoRA, PEFT, fine-tuning

### One-Token Rollout: Guiding Supervised Fine-Tuning of LLMs with Policy Gradient

- **作者：** Rui Ming, Haoyuan Wu, Shoubo Hu, Zhuolun He, Bei Yu
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1938/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1938.pdf)
- **中文提要：** 监督微调是适配大语言模型的主流方法，泛化却常常不如强化学习。这种差距被认为不只来自损失函数，更根本的差别在于：监督微调学习固定的预采集数据，强化学习则使用同策略采样得到的数据。
- **关键词：** SFT, fine-tuning

### Online Self-Weighted Fine-Tuning

- **作者：** Haiquan Wen, Yiwei He, Bei Peng, Guangliang Cheng
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.563/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.563.pdf)
- **中文提要：** 标准监督微调给每条专家示范相同的显式损失权重，并不理会模型在各训练查询上不断变化的能力。基于强化学习的做法能用模型生成的推演调节更新强度，但需要更多采样，在困难任务上也可能不稳定。
- **关键词：** SFT, fine-tuning

### On-Policy Distillation Meets Off-Policy GRPO: Training Compact Instruction-Following Rerankers

- **作者：** Vignesh Prabhakar, Jialing Pan, Anil Babu Ankisettipalli
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.477/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.477.pdf)
- **中文提要：** 紧凑的指令遵循重排器便于部署，常规蒸馏却多让学生在固定样例上离线模仿教师输出，监督被限制在教师已经观察到的排序空间。作者从强化学习重新审视重排器蒸馏，提出把离策略教师一侧纳入的两阶段框架。
- **关键词：** GRPO, instruction-following

### PatAlign: Bridging the Gap between Scientific Papers and Patent Descriptions via Iterative Preference Optimization

- **作者：** Zheming Fan, Xuemeng Song, Min Yang, Linyi Yang
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.212/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.212.pdf)
- **中文提要：** 把学术论文改写成专利说明书，要求模型同时应付超长篇幅、严格事实性和严谨文风。现有监督方法会出现病态重复，静态偏好优化则会误罚必要的结构性重复，进而造成文风退化。
- **关键词：** preference-optimization, alignment

### Patch the Distribution Mismatch: RL-Based Data Rewriting for Stable Downstream SFT

- **作者：** Jiacheng Wang, Zhijie Liu, Ping Jian, Zirong Chen, Ke Ren Liao, Zhen Yang, Zhongbin Guo
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1660/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1660.pdf)
- **中文提要：** 大语言模型常通过监督微调适配下游任务，下游监督与模型生成分布之间的明显错配会加剧灾难性遗忘。数据重写提供了一条在微调之前从数据侧收窄这种错配的途径。
- **关键词：** SFT, instruction-tuning, LoRA, alignment, fine-tuning

### PEFT-Arena: Understanding Parameter-Efficient Finetuning from a Stability-Plasticity Perspective

- **作者：** Yangyi Huang, Ruotian Peng, Zeju Qiu, Jiale Kang, Yandong Wen, Bernhard Sch{\"o}lkopf, Weiyang Liu
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1930/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1930.pdf)
- **中文提要：** 参数高效微调 PEFT 已成为适配大语言模型的标准途径，评测却多强调下游准确率，较少关心预训练能力是否保留。PEFT-Arena 主张从稳定性与可塑性的两难来评估，也就是目标任务适应与抵抗遗忘之间的权衡。
- **关键词：** SFT, PEFT, fine-tuning

### PLC-DPO: Posterior Label Correction in Noisy and Ambiguous Preference Optimization

- **作者：** Boryeong Cho, Sumyeong Ahn, Se-Young Yun
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1899/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1899.pdf)
- **中文提要：** 直接偏好优化 DPO 用成对比较简化对齐，但假定观察到的偏好全都可靠。真实数据经常违背这一假定，颠倒、偏弱或含糊的标签会带来有害的策略更新。
- **关键词：** DPO, preference-optimization, alignment

### Post-Training Shifts Confidence: A Three-Stage Analysis of How SFT, RL, and OPD Shape CoT Calibration

- **作者：** Shuhao Li, Guodong DU, Anhao Zhao, Wanyu Lin, Tianyu Yuan, Xiaoyu Shen
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1602/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1602.pdf)
- **中文提要：** 借助监督微调、强化学习和同策略蒸馏，大语言模型在推理上取得明显进展，这些后训练方法却通常只按最终答案准确率来评价。后续分析转向它们如何重塑推理过程中的置信度。
- **关键词：** SFT, post-training, fine-tuning

### PRISM: Post-Training LLM Pruning via Residual Importance Signal Merging and Intra-Block Sparsity Allocation

- **作者：** Keyu Wen, Jianing Zhu, Kaiyang HU, Lijun Yang, Rui Lin
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.606/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.606.pdf)
- **中文提要：** 后训练剪枝可以在不全量重训的情况下压缩大语言模型，但稀疏度很高时性能下降明显。局部重要性估计会错过全局谱结构，块内统一的稀疏分配也忽略了 Transformer 各投影敏感度并不相同。
- **关键词：** post-training

### Provenance-Grounded Gating and Adaptive Recovery in Synthetic Post-Training Data Curation

- **作者：** Soham Bhattacharjee, Karun Sharma, Vinay Kumar Sankarapu, Pratinav Seth
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.2399/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.2399.pdf)
- **中文提要：** 合成后训练流程常用奖励模型或整体式语言模型评审来过滤生成样本，并常常假定：不必对照产生样本的确切来源就能判断忠实性，被拒样本也可以直接丢弃而不必系统挽回。围绕门控配置和挽回策略等设置，作者对上述假定做了对照研究。
- **关键词：** reward-model, post-training, fine-tuning

### Quality, Not Just Outcome: A Structural Scoring Framework for Selecting Coding-Agent Trajectories for Supervised Fine-Tuning

- **作者：** Sida Li, Yuanxin Liu, Shicheng Li, Linli Yao, Xu Sun, Haoli Bai, Xiao-Hui Li
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.2264/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.2264.pdf)
- **中文提要：** 开源编程智能体常在交互轨迹上做监督微调，入选轨迹的最终补丁能够通过基准测试。只按结果筛选会忽略过程质量，最终成功的轨迹仍可能包含重复查看文件、工具使用不稳或修改滞后等低效模式。
- **关键词：** SFT, alignment, fine-tuning

### REALM: Reliable Expertise-Aware Language Model Fine-Tuning from Noisy Annotations

- **作者：** Sajjad Ghiasvand, Mark Beliaev, Mahnoosh Alizadeh, Ramtin Pedarsani
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1621/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1621.pdf)
- **中文提要：** 监督微调依赖人工标注，而标注流程中众包人员的专长并不整齐。常规汇总采用多数表决或简单平均，丢弃标注者身份，使模型把不可靠标注者的错误吸收进参数。
- **关键词：** SFT, fine-tuning

### Revisiting Complete Reasoning Traces for Post-Training

- **作者：** Jaehui Hwang, Sangdoo Yun, Byeongho Heo, Dongyoon Han
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.2211/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.2211.pdf)
- **中文提要：** 后训练经常使用预先收集的推理轨迹来提升推理能力。这些轨迹因路径复杂、彼此交织而偏长，走向答案时往往还夹着绕路。
- **关键词：** SFT, post-training, fine-tuning

### RewardCode: Training Generalist Code Reward Model via Pairwise Reinforcement Learning

- **作者：** Songtao Huang, Shiyang Feng, Xiaohan He, Xiangchao Yan, Bo Zhang, Lei Bai
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.448/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.448.pdf)
- **中文提要：** 奖励建模用来让语言模型对齐人类偏好，编程任务却因领域多样、并且要求严格的逻辑与语法而更难评价。RewardCode 以两阶段流程训练通用代码奖励模型，借助基于原则的打分和单元测试生成来做可扩展且更精细的评价。
- **关键词：** GRPO, reward-model, fine-tuning

### Rollout-Level Advantage-Prioritized Experience Replay for GRPO

- **作者：** Gyeongtae Yoo, Sanghyeok Park, Soohyuk Jang, Ik-hwan Kim, Sungroh Yoon
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.2331/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.2331.pdf)
- **中文提要：** 用可验证奖励配合 GRPO 对推理大语言模型做后训练，已经是一种标准做法。这种做法的样本效率仍然不高。
- **关键词：** GRPO, post-training

### Router Prior Bias: Preserving Base Routing Structure in MoE Post-Training

- **作者：** Jaedeok Lee, Keonwoo Kim, Dongyoon Han, Sangdoo Yun, Yera Choi, Haanju Yoo
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.2339/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.2339.pdf)
- **中文提要：** 混合专家预训练依赖辅助负载均衡损失，把各专家利用率推向均匀。后训练面对的情况不同：基座路由器已经编码了非均匀的专家共激活结构，再施加均匀性目标会把这种结构抹平。
- **关键词：** post-training, fine-tuning

### Routing Is Not Enough: Diagnosing Intra-Adapter Subspace Contention in MoE+LoRA Fine-Tuning

- **作者：** Mehreen Hossain Chowdhury, Nowshin Mahjabin, Ahmed Shafin Ruhan, MD Azam Hossain, Abu Raihan Mostofa Kamal, Md Tahmid Rahman Laskar
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.414/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.414.pdf)
- **中文提要：** 多领域微调常把 MoE 路由与 LoRA 结合起来，并假定词元级路由就能分开各领域的更新。这一假定在 MoE+LoRA 上受到检验，搭配的材料包括 Python 代码、生物医学文本和数学推理。
- **关键词：** LoRA, fine-tuning

### S2J: Bridging the Gap Between Solving and Judging Ability in Generative Reward Models

- **作者：** Shaoning Sun, Jiachen Yu, Zongqi Wang, Xuewei Yang, Tianle Gu, Yujiu Yang
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1966/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1966.pdf)
- **中文提要：** 生成式奖励模型已被广泛用于奖励建模和评价。先前研究主要在偏好数据上训练专用的生成式奖励模型，并把判断是否正确当作监督信号。
- **关键词：** reward-model

### Sample Learning State Guided Dynamic SFT--RL Integration Post-training

- **作者：** Zheng Yang, Yilin Liu, Zhuoran Li, Wenhao Gao, Bingwei Li, Haozhe Sun, Caixia Yuan, Fan Wan, Wu Chen, Xiaojie Wang
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.2011/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.2011.pdf)
- **中文提要：** 把监督微调与强化学习结合起来，已成为提升大语言模型推理能力的常见后训练范式。现有方法多依赖先后串联的流程或静态损失权重，忽略了样本层面的差异以及不断变化的学习状态。
- **关键词：** SFT, post-training, fine-tuning

### Sequential Beats Joint: On the Interplay between On-Policy Distillation and RLVR

- **作者：** Boyan Li, Bingsen Chen, Chenghao Yang, Ping Nie, Chen Zhao, Xi Ye
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.631/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.631.pdf)
- **中文提要：** 可验证奖励强化学习与同策略蒸馏，已成为推理大语言模型后训练的两种主导方法。先前工作用同策略蒸馏的稠密词元级监督去补充稀疏的强化学习奖励，并在同一步内融合两种信号，方式包括加权相加，或由教师调制来重缩放强化学习优势。
- **关键词：** RLVR, SFT, post-training

### SIGHT: Gaze-Guided Attention-Head Selection for Head-Sparse PEFT

- **作者：** Xinyu Gao, Shaonan Wang, Jiajie Zou, Li Zhao, Nai Ding
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.167/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.167.pdf)
- **中文提要：** 参数高效微调减少了可训练参数，但注意力头稀疏的 PEFT 仍要决定哪些头接受更新。SIGHT 用注视来引导头的选择，找出与注视对齐的注意力头再进行调优。
- **关键词：** PEFT, fine-tuning

### Silence over Error: Risk-Averse Navigation Landmark Extraction via Progressive MLLM Alignment

- **作者：** Xin Yang, Ziqi Cao, Changning Shao, Junhao Lin, Fanxiang Zeng, Yue Liu
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1478/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1478.pdf)
- **中文提要：** 现有行人导航系统常常只提供方向指令，在复杂路口或很长的直路上缺少视觉确认。所研究的问题是从行车记录仪图像序列中抽取不依赖坐标的地标。
- **关键词：** alignment

### Skill-CDPO: Evolving Agent Tool-Use via Critical Step Preference Optimization

- **作者：** Yuchen Li, Jinghao Lin, Yuanqing Wang
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1985/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1985.pdf)
- **中文提要：** 较小的开源语言模型在智能体工具使用的可靠性上落后于更大的模型；监督微调受暴露偏差影响，强化学习又受长工具交互轨迹上稀疏信用分配的制约。Skill-CDPO 是一个渐进框架，先在推理时习得工具使用技能。
- **关键词：** DPO, SFT, preference-optimization, PRM, reward-model, fine-tuning

### Skip-Connected Rollouts for Mid-Trajectory Rewards in GRPO

- **作者：** Fengwei Teng, Jinyi Bai, Xinhao Yao, Demi Wang, Jiahao Zhao, Zhijiang Guo
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.934/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.934.pdf)
- **中文提要：** GRPO 及其变体借助基于结果的反馈，在可验证奖励的强化学习中表现出效果。把中间信用纳入其中仍然困难。
- **关键词：** GRPO

### SMRC: Aligning Large Language Models with Student Reasoning for Mathematical Error Correction

- **作者：** BiaoJie Zeng, Min Zhang, Juan Zhou, Fengrui Liu, Ruiyang Huang, YU Song, Xin Lin
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.412/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.412.pdf)
- **中文提要：** 大语言模型解答数学题时经常出现推理错误，如何自动检测并纠正这些错误已成为重要课题。现有方法主要做模型内部的自我纠正，达不到教育场景所需的教师式系统引导。
- **关键词：** alignment

### Stabilizing Hard-Negative Preference Optimization for Medical LLMs

- **作者：** Kazuma Kobayashi, Yosuke Yamagishi, Ryota Shibaki, Azusa Sakai, Takashi Kodama, Lin Gu, Irene Li, Yuki Arase, Akiko Aizawa, Sadao Kurohashi
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.716/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.716.pdf)
- **中文提要：** 难负例偏好优化应当加强对真实偏好回答的支持，同时限制相对参考模型的漂移。在日语医疗指令调优中，标准 DPO 和 IPO 虽能拉大偏好与非偏好的差距，却可能使偏好回答的似然低于参考模型，并带来序列级 KL 散度增大。
- **关键词：** DPO, instruction-tuning, preference-optimization

### STAIF: A Stage-wise Optimization for Complex Instruction Following

- **作者：** Jian Hong, Chen Cheng, Quan Liu, Yuhao Chen, Enhong Chen
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1281/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1281.pdf)
- **中文提要：** 遵循带有多条显式约束的复杂指令，仍是大语言模型的基本挑战。DPO 等对齐方法优化的是整体奖励信号，往往不够强调逐条约束是否被严格满足，在分布外或多约束设定下尤其如此。
- **关键词：** DPO, RLVR, instruction-following, preference-optimization, alignment

### Stop Rolling the Dice: Active Group Relative Policy Optimization via Intrinsic Metacognition

- **作者：** Zheng Gong, Ying Sun, Hao Peng, Philip S. Yu
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.614/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.614.pdf)
- **中文提要：** GRPO 对大推理模型很有吸引力，因为组内相对优势省去了价值网络。效率却受到零方差查询的严重限制：这些查询的推演要么全部正确、要么全部错误，仍要消耗昂贵的思维链生成，却提供不了有用的学习信号。
- **关键词：** GRPO

### The Emergence of Relevance Through Axiomatic Attention Patterns During LoRA Fine-Tuning

- **作者：** Matthew Perlman, Atharva Nijasure, James Allan
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1948/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1948.pdf)
- **中文提要：** 用 LoRA 把大语言模型微调成重排器已是常规做法，但任务特有的相关性行为在网络何处学到、伴随哪些注意力变化，仍然不清楚。消融与注意力实验用来辨认 RankLLaMA 上哪些 LoRA 注意力更新能提升表现，以及这些提升是否与可解释的、面向相关性的注意力模式一同出现。
- **关键词：** LoRA, fine-tuning

### The Interplay of Harness Design and Post-training in LLM Agents

- **作者：** Kyungmin Kim, Youngbin Choi, Seoyeon Lee, Suhyeon Jun, Dongwoo Kim, Sangdon Park
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.2207/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.2207.pdf)
- **中文提要：** 所讨论的脚手架决定暴露哪些工具、如何描述它们，以及每一步观察附带哪些辅助信息。智能体虽然经常接受后训练，这种脚手架通常被当成固定的工程细节，设计努力也主要放在免训练设定中。
- **关键词：** post-training

### The Reward Model Selection Crisis in Personalized Alignment

- **作者：** Fady Rezk, Yuangang Pan, Chuan-Sheng Foo, Xun Xu, Nancy F. Chen, Henry Gouk, Timothy Hospedales
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.123/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.123.pdf)
- **中文提要：** 基于偏好数据的个性化对齐，重点放在提高个人奖励模型的准确率，并默认更好的偏好排序会带来更好的个性化行为。部署时的算力约束使得需要采用推理时适应，例如奖励引导解码，而不是按用户单独微调策略。
- **关键词：** reward-model, alignment, fine-tuning

### Thinking at the Right Size: Amortized Distillation Across Post-Trained LLMs

- **作者：** Yan Zhou, Sara Kangaslahti, Jonathan Geuter, Nihal V. Nayak, Marco Fumero, Francesco Locatello, David Alvarez-Melis
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1718/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1718.pdf)
- **中文提要：** 实际部署需要指令调优、推理调优和对话风格等后训练变体，并且每种都要备有多种规模，以匹配不同的延迟和显存预算。若每个变体与规模的组合都单独训练，代价难以承受，因此模型族通常只为每种后训练变体覆盖偏粗的规模档。
- **关键词：** SFT, instruction-tuning, post-training, alignment, fine-tuning

### TrustFV: Trustworthy Fact Verification on Knowledge Graph via Process Reward-Guided Step-Level Constrained Decoding

- **作者：** Yue Zhang, Shicheng Zhou, Yifu Gao, Zhiliang Tian, Wenqing Hou, Bin Zhou
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.726/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.726.pdf)
- **中文提要：** 虚假信息迅速传播，使事实验证成为关键需求。基于大语言模型的方法已成为事实验证的主流途径，但仍然受到幻觉影响。
- **关键词：** PRM, reward-model

### Understanding and Enhancing Backdoor Persistency in LLM Agent Post-Training

- **作者：** Qiusi Zhan, Nian Lyu, Stephanie Ding, Arnav Mehta, Xander Davies, Daniel Kang
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.2213/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.2213.pdf)
- **中文提要：** 开发者可以通过良性后训练改造第三方模型，从而构建大语言模型智能体。所考察的供应链威胁是：攻击者提供带后门的模型，特定输入模式出现时会触发隐藏行为并给出恶意输出。
- **关键词：** SFT, post-training, fine-tuning

### Understanding Training Data Attribution in RLVR: From the Perspective of Causal Inference

- **作者：** Chi Zhang, Jian Zhao, Wei Wang, Kai Wang, Yao Zhao, Xuelong Li
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.2023/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.2023.pdf)
- **中文提要：** 训练数据归因越来越多地用于在可验证奖励强化学习中筛选、重加权并优先处理推演。这类干预常常假定，单条样本、转移或轨迹可以独立于同一次更新里的其他数据而被归因。
- **关键词：** GRPO, RLVR

### UniAttn: Reducing Inference Costs via Softmax Unification for Post-Training LLMs

- **作者：** Yizhe Xiong, Wei Huang, Xin Ye, Hui Chen, Zijia Lin, Haoran Lian, Zhenpeng Su, Jungong Han, Guiguang Ding
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.2025/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.2025.pdf)
- **中文提要：** 后训练是把大语言模型适配到实际应用的必要步骤。部署这些后训练模型时，可观的显存开销和可感知的推理延迟构成明显障碍。
- **关键词：** post-training

### Unlocking the Unsolvable: Teacher-Guided Curriculum for Data-Efficient RLVR

- **作者：** Yukang Zhu, Zhen Han
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.931/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.931.pdf)
- **中文提要：** 可验证奖励强化学习在提升大语言模型的数学推理上已显示出突出成效。超出当前能力、推演一律失败因而产生不了学习信号的题目在结构上被浪费，尽管它们标示着信息量最大的训练前沿。
- **关键词：** GRPO, RLVR

### Unsupervised Post-Training of Foundation Models: A Survey

- **作者：** Yijie Xu, Qianyi Cai, Huizai Yao, Yili Wang, Tianfu Wang, Cehao Yang, Xingbo Yao, Zhiyu Guo, Aiwei Liu, Xuming Hu, Weiyu Guo, Hui Xiong
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.2044/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.2044.pdf)
- **中文提要：** 基础模型的后训练通常依赖人工标签、偏好数据、更强的教师或可执行验证器。无监督后训练关注的是在无标注输入上做会更新参数的适配，学习信号来自同一谱系的模型产物，而不是外部预言机。
- **关键词：** post-training

### Variable-Rank Adaptation: A Comprehensive Survey of Rank Budgeting LoRA Variants

- **作者：** Max Ploner, Alan Akbik
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.2430/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.2430.pdf)
- **中文提要：** LoRA 的容量从根本上由秩这一参数决定，标准实现则在所有层使用统一的秩。近期的可变秩扩展表明，按模块重要性安排秩可以提高表达能力。
- **关键词：** LoRA

### VCIFBench: Evaluating Complex Instruction Following for Video Understanding

- **作者：** Huangchen Xu, Yuan Wu, Yi Chang
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.145/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.145.pdf)
- **中文提要：** 多模态大语言模型在视频理解上进展迅速，现有基准却大多依赖简单提示，对模型能否满足显式输出约束提供的证据有限。VCIFBench 用来评测视频理解中的复杂指令遵循。
- **关键词：** DPO, instruction-following, preference-optimization

### VC-IF: Introducing Visual-Constraint Instruction Following for Multi-Turn, Multi-Constraint Vision-Language Models

- **作者：** Jixiang Hong, Pi Bu, Yingyao Wang, Bo Peng, Peijie Wang, Chen Wang, Tengtao Song, Yang Yao, Jun Song, Rui Yan, Cheng Yu, Bo Zheng
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1240/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1240.pdf)
- **中文提要：** 大型视觉语言模型进步很快，现有指令遵循基准却聚焦格式约束、角色扮演等纯文本要求，只衡量语言层面是否遵守，与视觉无关。VC-IF 把视觉约束引入这一类评测。
- **关键词：** instruction-following

### VisMind: Stateful Synthetic Dialogue for Visual Mid-Training

- **作者：** Xinlong Fu, Zihao Zhou, Qiufeng Wang
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1158/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1158.pdf)
- **中文提要：** 中期训练被视为提升视觉语言模型推理能力的关键桥梁，高质量视觉推理数据的稀缺却限制了效果。数据合成是一条替代途径，但常规的无状态合成只能产生浅层轨迹，并很快陷入效用平台。
- **关键词：** continued-pretraining, mid-training

### What do Reward Models Memorize?

- **作者：** Ivo Verhoeven, Pushkar Mishra, Ekaterina Shutova
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1733/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1733.pdf)
- **中文提要：** 通过测量人类偏好数据上的反事实记忆，可以考察判别式训练的奖励模型记住了什么。这些模型会把记忆错配到容易且间隔较大的偏好对上，记住数据集特有的捷径，例如模型身份和用户采样策略，并过度泛化与人类偏好简单相关的启发式线索。
- **关键词：** reward-model

### What Transfers Under Source Shift? Definitions, Examples, and Fine-Tuning for Climate Disclosure Classification

- **作者：** Guosheng Li, Fenghui Ren, Bin Liu, Chuan Yu, Kaiying Ji, Lin Yue, Jun Shen, Sasa Qian
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.1825/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.1825.pdf)
- **中文提要：** 气候披露分类是分析企业气候披露的基础任务，但披露来自年报、新闻稿和业绩电话会等不同来源，篇幅、目的和文风都不相同。现有评测大多在单一来源内进行，常见大语言模型适配策略在来源变化下是否仍然有效，仍是开放问题。
- **关键词：** LoRA, fine-tuning

### When Safety Routing Breaks: Understanding Alignment Fragility under Benign Fine-Tuning

- **作者：** Yitong Guo, Xiaoyi Chen, Siyuan Zhang, XiaoFeng Wang, Haixu Tang
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.604/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.604.pdf)
- **中文提要：** 良性微调会严重削弱大语言模型的安全对齐，这项研究追问拒绝行为为何如此脆弱。不同于把失败归于梯度冲突的看法，作者给出 Fisher 几何解释：安全相关的 Fisher 是低秩的，对齐让安全几何更平坦，同时仍保留一条输出路由通路。
- **关键词：** LoRA, alignment, fine-tuning

### Which Tokens Should SFT Actually Learn? A Token-Trimming Perspective on Mathematical Reasoning

- **作者：** Yaning Jia, Chunhui Zhang, Wenxuan Xu, Xingjian Diao, Xiaoyuan Wang, Soroush Vosoughi
- **会议：** EMNLP 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-emnlp.465/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-emnlp.465.pdf)
- **中文提要：** 监督微调对数学推理里的全部目标 token 一视同仁地施加交叉熵，尽管不同 token 提供的学习信号并不相等。这种均匀处理会把已经掌握的 token 过度锐化，又加大对不确定、低置信 token 的学习压力，训练动态因此变差。
- **关键词：** SFT, fine-tuning
