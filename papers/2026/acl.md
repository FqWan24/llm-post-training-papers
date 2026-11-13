# 2026 · ACL

共 289 篇。Main 163，Findings 126，其他赛道 0。其中 0 篇来源题录无摘要，提要标明「仅根据标题概括」。

检索窗口为 2024-11-13 至 2026-11-13。题录信息来自官方列表，不在此增补作者、链接或实验数字。

## Main

### A Comprehensive Survey of Process Reward Models: Data Generation, Model Construction, and Usage

- **作者：** Congmin Zheng, Jiachen Zhu, Zhuoying Ou, Yuxiang Chen, Kangning Zhang, Rong Shan, Zeyu Zheng, Mengyue Yang, Jianghao Lin, Yong Yu, Weinan Zhang
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.163/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.163.pdf)
- **中文提要：** 大语言模型的推理能力在提升，常规对齐仍主要由只评判最终答案的结果奖励模型主导。过程奖励模型则在步骤或轨迹层面评估并引导推理，以补上这一缺口。
- **关键词：** PRM, reward-model, alignment

### Act-Adaptive Margin: Dynamically Calibrating Reward Models for Subjective Ambiguity

- **作者：** Feiteng Fang, Dingwei Chen, Xiang Huang, Ting-En Lin, Yuchuan Wu, Xiong Liu, Jing Ye, Ziqiang Liu, Haonan Zhang, Liang Zhu, Hamid Alinejad-Rokny, Min Yang, Yongbin Li
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.710/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.710.pdf)
- **中文提要：** 多数强化学习任务集中在数学和编程等较易验证的领域。角色扮演等主观任务中，用 Bradley-Terry 模型做主观奖励建模会在偏好含糊时遇到明显困难，对齐因此难以推进。
- **关键词：** GRPO, reward-model, alignment

### AdaJudge: Adaptive Multi-Perspective Judging for Reward Modeling

- **作者：** Yongliang Miao, Yangyang Liang, Mengnan Du
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.440/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.440.pdf)
- **中文提要：** 奖励建模对大语言模型对齐人类偏好至关重要，主流结构却用静态池化把序列压成标量分数。这种静态归纳偏置与随任务变化的偏好信号不匹配，骨干网络面向生成的优化也带来表征错位。
- **关键词：** reward-model, alignment

### A Data-Efficient Path to Multilingual LLMs: Language Expansion via Post-training PARAM$\Delta$ Integration into Upcycled MoE

- **作者：** Hao Zhou, Tianhao Li, Zhijun Wang, Shuaijie She, Linjuan Wu, Hao-Ran Wei, Baosong Yang, Jiajun Chen, Shujian Huang
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1238/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1238.pdf)
- **中文提要：** 把大语言模型扩展到新语言代价很高，既要大量持续预训练，也要数据密集的对齐。免数据合并试图把多语言持续预训练模型与其指令版本融合以绕过对齐，但缓解参数冲突以保住原有能力又会带来权衡。
- **关键词：** continued-pretraining, post-training, alignment

### AdvancedIF: Rubric-Based Benchmarking and Reinforcement Learning for Advancing LLM Instruction Following

- **作者：** Yun He, Wenzhe Li, Hejia Zhang, Songlin Li, Karishma Mandyam, Sopan Khosla, Yuanhao Xiong, Nanshu Wang, Xiaoliang Peng, Beibin Li, Shengjie Bi, Shishir G Patil, Qi Qi, Shengyu Feng, Julian Katz-Samuels, Richard Yuanzhe Pang, Sujan Kumar Gonugondla, Hunter Lang, Yue Yu, Yundi Qian, Maryam Fazel-Zarandi, Licheng Yu, Amine Benhalloum, Hany Hassan Awadalla, Manaal Faruqui
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.820/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.820.pdf)
- **中文提要：** 大语言模型在多种任务上已经很强，但复杂、多轮以及带系统提示的高级指令遵循仍然困难。严格评测和有效训练受限于缺少高质量人工标注基准，以及可靠、可解释的配套手段。
- **关键词：** instruction-following, post-training, fine-tuning

### Advancing Reasoning in Diffusion Language Models with Denoising Process Rewards

- **作者：** Shaoan Xie, Lingjing Kong, Xiangchen Song, Xinshuai Dong, Guangyi Chen, Eric P. Xing, Kun Zhang
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1978/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1978.pdf)
- **中文提要：** 扩散式大语言模型提供非自回归的文本生成路径，但复杂推理仍然困难。强化学习后训练虽能改善表现，现有方法主要依赖结果奖励，对去噪过程缺少直接监督。
- **关键词：** PRM, post-training

### AfriqueLLM: How Data Mixing and Model Architecture Impact Continued Pre-training for African Languages

- **作者：** Hao Yu, Tianyi Xu, Michael A. Hedderich, Wassim Hamidouche, Syed Waqas Zamir, David Ifeoluwa Adelani
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.267/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.267.pdf)
- **中文提要：** 开放多语言模型相对专有系统仍然落后，非洲语言上的差距尤其明显。持续预训练是一条实用的语言适配途径，但数学推理等要求较高的能力往往提升有限。
- **关键词：** continued-pretraining

### AG-GRPO: Answer-Guided GRPO for Masked Diffusion Language Models

- **作者：** Juhyeong Kim, Gyunyeop Kim, Sangwoo Kang
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1724/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1724.pdf)
- **中文提要：** 可验证奖励的强化学习通常只看最终结果，几乎不判断推理是否与正确答案一致。即便训练时已有标准答案，同策略采样仍可能反复生成与答案不符的推理，作者因而提出答案引导的组相对策略方法。
- **关键词：** GRPO, RLVR

### Aligning Agents via Planning: A Benchmark for Trajectory-Level Reward Modeling

- **作者：** Jiaxuan Wang, Yulan Hu, Wenjin Yang, Zheng Pan, Xin Li, Lan-Zhe Guo
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1062/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1062.pdf)
- **中文提要：** 经典 RLHF 中，奖励模型是对齐的基本信号来源。当大语言模型变成能自主调用工具并做复杂推理的智能体后，专门评估奖励模型能力的基准仍然缺乏。
- **关键词：** RLHF, reward-model, alignment

### Aligning Backchannel and Dialogue Context Representations via Contrastive LLM Fine-Tuning

- **作者：** Livia Qian, Gabriel Skantze
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.629/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.629.pdf)
- **中文提要：** 附和语（如 yeah、mhm、right）是简短且不打断对方的反馈，其用词和韵律共同传递语用含义。以往计算研究多关注附和出现的时机，词形与韵律形式同意义之间的关系仍少被探讨。
- **关键词：** alignment, fine-tuning

### Aligning Language Models with Real-time Knowledge Editing

- **作者：** Chenming Tang, Yutong Yang, Kexue Wang, Yunfang Wu
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.14/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.14.pdf)
- **中文提要：** 知识编辑希望高效修改语言模型中过时的知识，同时保留原有能力。主流知识编辑数据大多是静态的，跟不上真实世界知识的变化。
- **关键词：** alignment

### Aligning Large Language Models via Fully Self-Synthetic Data

- **作者：** Shangjian Yin, Zhepei Wei, Xinyu Zhu, Wei-Lin Chen, Yu Meng
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1595/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1595.pdf)
- **中文提要：** 传统 RLHF 依赖昂贵的人工标注，RLAIF 同样成本很高：既要收集多样提示及对应回答，又常常借助外部奖励模型或专有模型来标注偏好对。
- **关键词：** RLHF, RLAIF, preference-optimization, reward-model, alignment

### Anchoring Depends on Confidence and Post-Training in Language Models

- **作者：** Hillary N. Owusu, Naomi H. Feldman
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-short.16/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-short.16.pdf)
- **中文提要：** 锚定偏差会让大语言模型在无关数字提示下改变数量判断。分析按模型置信度与准确率展开，覆盖 Llama 与 Qwen 的基座、指令微调及蒸馏变体。
- **关键词：** instruction-tuning, post-training

### ARF-RLHF: Adaptive Reward-Following for RLHF through Emotion-Driven Self-Supervision and Trace-Biased Dynamic Optimization

- **作者：** Yuxuan Zhang
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1637/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1637.pdf)
- **中文提要：** PPO、DPO 等 RLHF 方法通常把人类偏好压成二值标签，获取成本高，也难以反映个体差异。满意与不满的表达在不同用户间呈现稳定的语言模式，因而可以从自由形式反馈中提取更有信息量的监督信号。
- **关键词：** DPO, RLHF, reward-model, alignment

### AttnPO: Attention-Guided Process Supervision for Efficient Reasoning

- **作者：** Shuaiyi Nie, Dingsiyu, Wenyuan Zhang, Linhao Yu, Tianmeng Yang, Yao Chen, Weichong Yin, Yu Sun, Hua Wu, Tingwen Liu
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1845/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1845.pdf)
- **中文提要：** 用可验证奖励强化学习训练的大型推理模型在复杂推理上表现强，却常过度思考，写出没有增益的冗余步骤。轨迹级长度惩罚往往把所有推理步骤一视同仁，既难有效缩短推理，又会损害准确率。
- **关键词：** RLVR

### Backdoors in RLVR: Jailbreak Backdoors in LLMs From Verifiable Reward

- **作者：** Weiyang Guo, Zesheng Shi, Zeen Zhu, Yuan Zhou, Min Zhang, Jing Li
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1484/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1484.pdf)
- **中文提要：** 数学与编程等复杂逻辑任务上，可验证奖励强化学习正在提升大语言模型的推理能力。这一框架中同时潜伏着此前未被识别的后门攻击风险。
- **关键词：** RLVR

### BEFT: Bias-Efficient Fine-Tuning of Language Models in Low-Data Regimes

- **作者：** Baichuan Huang, Ananth Balashankar, Amir Aminifar
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1799/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1799.pdf)
- **中文提要：** 只微调大语言模型的偏置项，有望在低数据条件下以极少可训练参数取得有竞争力的效果。查询、键、值投影中不同偏置项与下游表现之间的联系仍不清楚。
- **关键词：** fine-tuning

### Beyond Pedagogical Principles: Multi-Horizon Preference Optimization for Efficient Socratic Tutoring

- **作者：** Xin Shi, Chao Zhang, Yifan Zhu, Xueqiao Zhang, Yawei Luo
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.518/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.518.pdf)
- **中文提要：** 基于大语言模型的导师智能体很难同时遵守教学原则并取得好的教学效果，动态多轮互动中尤其如此。现有方法常受静态数据或在线场景中稀疏奖励的制约。
- **关键词：** preference-optimization

### Beyond Surface Features: Advancing Medical Vision-Language Alignment via Dynamic Evidence-Guided Preference Optimization

- **作者：** Zixuan Huang, Zhihong Zhu, Xiaolong Liu, Yanchao Hao, Manman Zhang, Zheng Wei, Bowen Xing, Xian Wu, Ye Li, Fen Miao, Yefeng Zheng
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1200/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1200.pdf)
- **中文提要：** 医学大视觉语言模型在医学视觉问答和报告生成等临床多模态应用中已显潜力。模态错位仍会引发幻觉：模型优先依赖文本知识而非视觉证据，生成与医学图像相冲突的内容。
- **关键词：** preference-optimization, alignment

### Bias Fitting to Mitigate Length Bias of Reward Model in RLHF

- **作者：** Kangwen Zhao, Jianfeng Cai, Jinhua Zhu, Ruopei Sun, Dongyun Xue, Wengang Zhou, Li Li, Houqiang Li
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.133/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.133.pdf)
- **中文提要：** RLHF 依靠奖励模型把大语言模型对齐到人类偏好。策略学习却常利用奖励模型的缺陷来抬高分数，出现奖励黑客，而没有真正贴近人类偏好。
- **关键词：** DPO, RLHF, preference-optimization, reward-model, alignment

### C2: Scalable Rubric-Augmented Reward Modeling from Binary Preferences

- **作者：** Akira Kawabata, Saku Sugawara
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.523/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.523.pdf)
- **中文提要：** 用量规增强的验证以显式标准引导奖励模型，比单一模型验证更可靠，但多数方法依赖昂贵的量规标注。量规生成还容易出现合作失败，低质量量规会误导奖励模型，而不是提供帮助。
- **关键词：** reward-model

### Can Continual Pretraining Bridge the Performance Gap between General-purpose and Specialized Language Models in the Medical Domain?

- **作者：** Niclas Doll, Jasper Schulze Buschhoff, Shalaka Satheesh, Hammam Abdelwahab, H{\'e}ctor Allende-Cid, Katrin Klug
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.17/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.17.pdf)
- **中文提要：** 通过持续预训练与模型合并做领域适配，可以缩小小型专用模型与更大通用模型之间的性能差距。针对非英语专业数据稀缺，作者从 FineWeb2 构建德语医学语料 FineMed-de。
- **关键词：** instruction-following, continued-pretraining, fine-tuning

### Can Spectral-Clipping Enable Better Learning While Forgetting Less for Low-Rank Adaptation?

- **作者：** Hyowon Wi, Noseong Park
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1179/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1179.pdf)
- **中文提要：** LoRA 冻结预训练权重，只引入小型可学习适配器，从而避免全参数微调。作者基于奇异值分解考察网络参数的奇异分量，并首先讨论其中的主奇异分量。
- **关键词：** LoRA, fine-tuning

### Chunks as Arms: Multi-Armed Bandit-Guided Sampling for Long-Context LLM Preference Optimization

- **作者：** Shaohua Duan, Pengcheng Huang, Xinze Li, Zhenghao Liu, Xiaoyuan Yi, Yukun Yan, Shuo Wang, Yu Gu, Ge Yu, Maosong Sun
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.161/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.161.pdf)
- **中文提要：** 长上下文建模对长文问答、摘要和复杂推理等任务都很关键。近期研究尝试用合成数据微调大语言模型，以增强其长上下文能力。
- **关键词：** DPO, preference-optimization, fine-tuning

### CiPO: Counterfactual Unlearning for Large Reasoning Models through Iterative Preference Optimization

- **作者：** Junyi Li, Yongqiang Chen, Ningning Ding
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.143/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.143.pdf)
- **中文提要：** 机器遗忘试图从大规模人类数据训练出的大语言模型中选择性移除隐私或受版权保护的信息。强调长思维链的大型推理模型给遗忘带来了新的两难。
- **关键词：** preference-optimization

### CityVG: Contrastive Fine-Tuning and Reward-Based Chain-of-Thought Reasoning for Zero-Shot City-Scale 3D Visual Grounding

- **作者：** Jianjun Zhang, Hanli Wang
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1617/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1617.pdf)
- **中文提要：** 三维视觉定位要根据自然语言描述在三维场景中找出物体。现有方法多局限于小规模室内数据，或依赖重监督，难以推广到复杂的大规模城市环境。
- **关键词：** alignment, fine-tuning

### Compatibility-Aware Dynamic Fine-Tuning for Large Language Models

- **作者：** Yucheng Zhou, Junwei Sheng, Qianning Wang, Jianbing Shen
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1383/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1383.pdf)
- **中文提要：** 监督微调是对齐大语言模型的主流做法，但优化不稳定、泛化有限。近期工作将原因归于病态的梯度缩放，并提出动态微调（DFT），在词元层面加以校正。
- **关键词：** SFT, reward-model, alignment, fine-tuning

### ConsistRM: Improving Generative Reward Models via Consistency-Aware Self-Training

- **作者：** Yu Liang, Liangxin Liu, Longzheng Wang, Wangyan, Zhang Yueyang, Long Xia, Zhiyuan Sun, Daiting Shi
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1830/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1830.pdf)
- **中文提要：** 生成式奖励模型凭借更强的表示能力与灵活性，成为对齐大语言模型与人类偏好的一条途径。昂贵的人工标注限制了可扩展性，自训练也常常不稳定且较为脆弱。
- **关键词：** RFT, reward-model, alignment, fine-tuning

### Consolidation or Adaptation? PRISM: Disentangling SFT and RL Data via Gradient Concentration

- **作者：** Yang Zhao, Yangou Ouyang, Xiao Ding, Hepeng Wang, Bibo Cai, Kai Xiong, Jinglong Gao, Zhouhao Sun, Li Du, Bing Qin, Ting Liu
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1097/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1097.pdf)
- **中文提要：** 先做混合监督微调再接强化学习，已成为训练大语言模型智能体的常规范式，但两阶段之间如何分配数据仍少被探讨。现有数据仲裁多依赖表层启发式，难以诊断内在的学习需求。
- **关键词：** SFT, alignment, fine-tuning

### Controlling Distributional Bias in Multi-Round LLM Generation via KL-Optimized Fine-Tuning

- **作者：** Yanbei Jiang, Amr Keleg, Ryandito Diandaru, Jey Han Lau, Lea Frermann, Biaoyan Fang, Fajri Koto
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.802/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.802.pdf)
- **中文提要：** 真实世界本质上是随机的，大语言模型却多在单轮推理、对照固定标准答案的设定下被评估。工作转向分布对齐，考察反复提示时输出能否符合期望的目标分布。
- **关键词：** DPO, KTO, preference-optimization, alignment, fine-tuning

### CTRAP: Embedding Collapse Trap to Safeguard Large Language Models from Harmful Fine-Tuning

- **作者：** Biao Yi, Tiansheng Huang, Baolei Zhang, Tong Li, Lihai Nie, Zheli Liu, Li Shen
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.455/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.455.pdf)
- **中文提要：** 微调即服务在商业上取得成功，却使大语言模型暴露于有害微调攻击。作为一类广泛探索的防御，遗忘试图移除恶意知识，从而阻止模型被用于恶意任务。
- **关键词：** alignment, fine-tuning

### CuMA: Aligning LLMs with Sparse Cultural Values via Demographic-Aware Mixture of Adapters

- **作者：** Ao Sun, Xiaoyu Wang, Zhe Tan, Yu Li, Jiachen Zhu, Yuheng Jia, Shu Su
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1265/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1265.pdf)
- **中文提要：** 大语言模型服务全球用户时，对齐需要从强求普遍共识转向尊重文化多元。稠密模型若被迫拟合相互冲突的价值分布，会出现均值坍缩，收敛到无法代表不同群体的笼统平均。
- **关键词：** alignment

### DARM: Distribution-Aware Reward Modeling by Alleviating Biases from Low Preference-Context Dependency Data

- **作者：** Shaofan Liu, Guoqiang Zhang, Shihan Dou, Huiyuan Zheng, Yiming Zhou, Junjie Ye, Shaowen Wang, Shichun Liu, Jiazheng Zhang, Tao Gui, Qi Zhang, Xuanjing Huang
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1839/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1839.pdf)
- **中文提要：** 奖励模型是 RLHF 中的替代目标，其分数直接引导策略优化。当回答质量对上下文依赖很弱时，常规训练会鼓励奖励模型忽略上下文，造成上下文忽视并降低准确率。
- **关键词：** RLHF, reward-model

### Data Efficient RLVR via Off-Policy Influence Guidance

- **作者：** Erle Zhu, Dazhi Jiang, Yuan Wang, Xujun Li, Jiale Cheng, Yuxian Gu, Yilin Niu, Aohan Zeng, Jie Tang, Minlie Huang, Hongning Wang
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.2141/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.2141.pdf)
- **中文提要：** 数据选择是用可验证奖励强化学习提升大语言模型推理能力的关键环节。当前选择方法大多基于启发式，缺少理论保证，也难以泛化。
- **关键词：** RLVR

### Data-efficient Targeted Token-level Preference Optimization for LLM-based Text-to-Speech

- **作者：** Rikuto Kotoge, Yuichi Sasaki
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-short.59/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-short.59.pdf)
- **中文提要：** 通过偏好优化把语音合成输出对齐到人类反馈，可以提升基于大语言模型的合成系统的稳健性与自然度。现有方法主要需要话语层面成对的理想样本与不理想样本。
- **关键词：** preference-optimization, alignment

### Data Mixing Agent: Learning to Re-weight Domains for Continual Pre-training

- **作者：** Kailai Yang, Xiao Liu, Lei Ji, Hao Li, Xiao Liang, Zhiwei Liu, Yeyun Gong, Peng Cheng, Mao Yang
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.427/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.427.pdf)
- **中文提要：** 在小规模任务数据上做持续预训练，能让大语言模型适应新领域，但也有灾难性遗忘原有能力的风险。常见做法是在领域空间中重新加权源域与目标域的数据混合，以求得更均衡的表现。
- **关键词：** continued-pretraining

### Debiasing Reward Models via Causally Motivated Inference-Time Intervention

- **作者：** Kazutoshi Shinoda, Kosuke Nishida, Kyosuke Nishida
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1029/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1029.pdf)
- **中文提要：** 奖励模型在把大语言模型对齐到人类偏好时处于核心位置。它们往往对回答长度等虚假特征敏感。
- **关键词：** reward-model, alignment

### DecIF: Improving Instruction-Following through Decomposition

- **作者：** Tingfeng Hui, Pengyu Zhu, Bowen Ping, Ling Tang, Guanting Dong, Yaqi Zhang, Sen Su
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.36/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.36.pdf)
- **中文提要：** DecIF 借助大语言模型和极少外部资源，从零自动生成准确且多样的指令遵循数据，供监督微调与强化学习使用。数据合成流程被拆成细粒度步骤，以便更精细地控制生成数据的质量与多样性。
- **关键词：** SFT, instruction-following, fine-tuning

### Does RLVR Extend Reasoning Boundaries? Investigating Capability Expansion in Vision-Language Models

- **作者：** Minghe Shen, Zhuo Zhi, Chonghan Liu, Shuo Xing, Zhengzhong Tu, Che Liu
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.2102/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.2102.pdf)
- **中文提要：** 已有观点认为可验证奖励强化学习主要放大预训练分布中固有的行为，而不是诱发新能力，但这些认识多限于纯语言领域。以视觉为中心的空间推理仍少被考察，工作着手检验 RLVR 对视觉语言模型能力边界的影响。
- **关键词：** RLVR

### DORA: A Dual-Objective Reinforcement Learning Framework for Effective and Efficient Multimodal Agentic Search

- **作者：** Guangming Qin, Yuhao Deng, Yukun Zhao, Zhenyang Li, Junfeng Wang, Dawei Yin, Ye Yuan, Guoren Wang, Yizhou Yan, Chengliang Chai, Lei Cao
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.605/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.605.pdf)
- **中文提要：** 近期工作用强化学习后训练多模态大语言模型，使其在复杂视觉问答中迭代调用搜索引擎、动态获取外部知识。现有方法在效果与效率两方面都存在主要局限。
- **关键词：** post-training

### Dual-Axis Generative Reward Model Toward Semantic and Turn-taking Robustness in Interactive Spoken Dialogue Models

- **作者：** Yifu Chen, Shengpeng Ji, Zhengqing Liu, Qian Chen, Wen Wang, Ziqing Wang, Yangzhuo Li, Tianle Liang, Zhou Zhao
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.6/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.6.pdf)
- **中文提要：** 全双工口语对话模型要实现流畅、接近人类的互动仍是关键挑战。强化学习已增强文本与视觉语言模型，而设计良好的奖励信号对强化学习的表现至关重要。
- **关键词：** reward-model

### DUAL RM: Beyond Rule-based Preference Reward Modeling via Meta-Reward

- **作者：** Xiaobo Liang, Wanfu Wang, Qipeng Huang, Yuyang Ding, Zecheng Tang, Yixin Ji, Qianben Chen, Zhe Zhao, Kehai Chen, Juntao Li, Min Zhang
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1729/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1729.pdf)
- **中文提要：** 刻画人类偏好那种稀疏且欠指定的奖励，是扩展强化学习的基础。当前基于偏好的奖励建模很大程度上依赖可验证奖励，由人工标注标签定义规则化信号。
- **关键词：** GRPO, DPO, preference-optimization, reward-model, alignment

### Edit-Aware Reward Modeling for Chinese Grammatical Error Correction

- **作者：** Yilin Li, Xiaojun Wan
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1900/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1900.pdf)
- **中文提要：** 大语言模型在多种自然语言处理任务上已很成功，语法纠错方面的潜力仍少被挖掘。已有工作把基于规则奖励的强化学习用于中文语法纠错，但精确匹配与否这种粗粒度二值信号难以区分纠正质量的细微差别。
- **关键词：** GRPO, preference-optimization, reward-model

### Efficient Process Reward Modeling via Contrastive Mutual Information

- **作者：** Nakyung Lee, Sangwoo Hong, Jungwoo Lee
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1744/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1744.pdf)
- **中文提要：** 近期研究用过程奖励模型等验证器检查思维链轨迹的中间推理步骤。训练过程奖励模型通常需要人工为每一步标注奖励分数，成本高且耗时。
- **关键词：** PRM, reward-model

### Enhancing LLM-based Search Agents via Contribution Weighted Group Relative Policy Optimization

- **作者：** Junzhe Wang, Zhiheng Xi, Yajie Yang, Hao Luo, Shihan Dou, Tao Gui, Qi Zhang
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1462/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1462.pdf)
- **中文提要：** 搜索智能体让大语言模型能够获取预训练时不具备的最新与长尾信息。强化学习已被广泛用于训练这类智能体，但过程监督的价值估计往往不稳，结果监督在信用分配上也遇到困难。
- **关键词：** GRPO, PRM

### Enhancing Multimodal Large Language Models for Ancient Chinese Character Evolution Analysis via Glyph-Driven Fine-Tuning

- **作者：** Rui Song, Lida Shi, Ruihua Qi, Yingji Li, Hao Xu
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1043/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1043.pdf)
- **中文提要：** 多模态大语言模型的快速进展带动了古汉字研究。文字演变是理解文化转型与历史延续的基本途径，如何系统利用这类模型推进文字演变分析仍是开放且少被探讨的问题。
- **关键词：** fine-tuning

### Evolutionary Negative Module Pruning for Better LoRA Merging

- **作者：** Anda Cao, Zhuo Gou, Yi Wang, Kaixuan Chen, Yu Wang, Can Wang, Mingli Song, Jie Song
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1730/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1730.pdf)
- **中文提要：** 把多个 LoRA 专家合并到同一骨干，是高效部署多任务的一条途径。现有方法通过权重插值或子空间对齐减轻干扰，却默认所有 LoRA 矩阵都会对合并模型作出建设性贡献。
- **关键词：** LoRA, alignment

### FedProxy: Federated Fine-Tuning of LLMs via Proxy SLMs and Heterogeneity-Aware Fusion

- **作者：** Tao Fan, Guoqiang Ma, Yuanfeng Song, Lixin Fan, Kai Chen, Qiang Yang
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.794/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.794.pdf)
- **中文提要：** 大语言模型的联邦微调同时受制于保护模型知识产权、保障客户端隐私，以及减轻异构数据上的性能损失。离站微调让客户端只训练轻量适配器来保护知识产权，但分析显示它存在根本性的性能瓶颈。
- **关键词：** fine-tuning

### Fine-tuning vs. In-context Learning in Large Language Models: A Formal Language Learning Perspective

- **作者：** Bishwamittra Ghosh, Soumi Das, Till Speicher, Qinyuan Wu, Mohammad Aflah Khan, Deepak Garg, Krishna P. Gummadi, Evimaria Terzi
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1932/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1932.pdf)
- **中文提要：** 大语言模型主要在微调与上下文学习两种模式下运作，哪种更能带来语言能力、二者的归纳偏置是否不同，仍是关键问题。以往比较因实验设置不一致，结论混杂且难以定论。
- **关键词：** fine-tuning

### FocalOrder: Focal Preference Optimization for Reading Order Detection

- **作者：** Fuyuan Liu, Dianyu Yu, He Ren, Nayu Liu, Xiaomian Kang, Delai Qiu, Fa Zhang, Genpeng Zhen, Shengping Liu, Liang Jiaen, Weihuang, Yining Wang, Junnan Zhu
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.868/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.868.pdf)
- **中文提要：** 阅读顺序检测是文档理解的基础，多数方法依赖均匀监督，默认各版面区域难度恒定。作者指出位置差异：模型能掌握确定性的起始与结束区域，却会在其他位置出现性能坍塌。
- **关键词：** preference-optimization, alignment

### For-Value: Efficient Forward-Only Data Valuation for finetuning LLMs and VLMs

- **作者：** Wenlong Deng, Qi Zeng, Jiaming Zhang, Minghui Chen, Zixin Ding, Christos Thrampoulidis, Boying Gong, Xiaoxiao Li
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.664/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.664.pdf)
- **中文提要：** 数据估值有助于提升大语言模型和视觉语言模型的透明度与可问责性。现有方法通常依赖梯度计算，对超大规模模型计算代价过高，也无法进行批次并行。
- **关键词：** alignment, fine-tuning

### From Completion to Editing: Unlocking Context-Aware Code Infilling via Search-and-Replace Instruction Tuning

- **作者：** Jiajun Zhang, Zeyu Cui, Jiaxi Yang, Lei Zhang, Yuheng Jing, Zeyao Ma, Tianyi Bai, Zilei Wang, Qiang Liu, Liang Wang, Binyuan Hui, Junyang Lin
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.361/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.361.pdf)
- **中文提要：** 主流的中间填充式代码补全难以纠正上下文错误，还依赖未对齐、不安全的基座模型。对话式大语言模型更安全，智能体流程更灵活，但分别面临性能下降和过高的延迟。
- **关键词：** instruction-tuning, instruction-following, alignment, fine-tuning

### From Curated Data to Scalable Models: Continual Pre-training of Dense and MoE Large Language Models for Tibetan

- **作者：** Lei Yang, Leiyu Pan, Bojian Xiong, Renren Jin, Shaowei Zhang, Yue Chen, Ling Shi, Jiang Zhou, Junru Wu, Zhen Wang, Jianxiang Peng, Juesi Xiao, Tianyu Dong, Zhuowen Han, Zhuo Chen, Yuqi Ren, Deyi Xiong
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1866/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1866.pdf)
- **中文提要：** 大语言模型在广泛的自然语言处理任务上取得成功，但表现严重偏向高资源语言。藏语尽管文化意义重要、使用人口众多，仍然明显代表不足。
- **关键词：** instruction-tuning, continued-pretraining

### From Experts to Bases: Orthogonal Subspace Mixture for Continual Multimodal Instruction Tuning

- **作者：** Pei Chen, Xilai Wang, Shiqixu, Zejian Li, Lingyun Sun
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.481/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.481.pdf)
- **中文提要：** 多模态持续指令微调对于让多模态大语言模型适应动态数据流必不可少，但防止灾难性遗忘仍是主要挑战。参数高效方法中，固定结构容易产生知识干扰，动态策略又会低效扩张容量，限制可扩展性。
- **关键词：** instruction-tuning, LoRA, PEFT

### From Individual to Common: An Early Exploration of Consensus in Non-verifiable Data for Balanced Preference Optimization

- **作者：** Shangjian Yin, Zhouxing Shi
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1598/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1598.pdf)
- **中文提要：** 可验证奖励强化学习通过基于规则的同策略自我改进，能有效提升大语言模型在推理等客观任务上的表现。主观能力以及与人类偏好的对齐，则因不可验证而仍然困难。
- **关键词：** RLVR, preference-optimization, alignment

### G$^2$RPO-A: Guided Group Relative Policy Optimization with Adaptive Guidance

- **作者：** Yongxin Guo, Wenbo Deng, Zhenglin Cheng, Xiaoying Tang
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.206/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.206.pdf)
- **中文提要：** 大语言模型的推理能力在可验证奖励强化学习下得到明显增强。这种成效很大程度上依赖世界知识丰富的强基座，小尺寸语言模型往往只能获得有限提升。
- **关键词：** GRPO, RLVR

### GeoRA: Geometry-Aware Low-Rank Adaptation for RLVR

- **作者：** Jiaying Zhang, Lei Shi, Jiguo Li, Jun Xu, Jiuchong Gao, Jinghua Hao, Renqing He
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1110/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1110.pdf)
- **中文提要：** 与监督微调相比，可验证奖励强化学习呈现出不同的优化动态，并且对预训练几何结构是否得以保持十分敏感。它被视作改进大规模推理模型的关键范式。
- **关键词：** RLVR, SFT, LoRA, PEFT, fine-tuning

### GIFT: Guided Fine-Tuning and Transfer for Enhancing Instruction-Tuned Language Models

- **作者：** Zhiwen Ruan, Yichao Du, Jianjie Zheng, Longyue Wang, Yun Chen, Peng Li, Jinsong Su, Yang Liu, Guanhua Chen
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.358/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.358.pdf)
- **中文提要：** 指令微调后的大语言模型具备较强的指令遵循与泛化能力，这依赖于昂贵的后训练流程。直接微调到下游任务常破坏这种平衡，现有基于适配器的迁移又往往把指令模型当作被动目标。
- **关键词：** instruction-tuning, instruction-following, post-training, fine-tuning

### Global Adaptive Momentum Meets Local Personalized Perturbation: Efficient Federated LLM Fine-Tuning with Zeroth-Order Gradients

- **作者：** Zihan Chen, Howard Hao Yang, Tony Quek, Kai Fong Ernest Chong
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1851/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1851.pdf)
- **中文提要：** 联邦微调为大语言模型提供保护隐私的生成式服务部署方式，但一阶梯度计算的显存开销带来实际困难。零阶优化更节省显存，却容易因数据相关因素而性能下降。
- **关键词：** fine-tuning

### GMFL: Efficient Global Masking for Federated LLM Fine-tuning

- **作者：** Xin Huang, Yan Hu, Yue-Jiao Gong, Xinglin Zhang
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1160/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1160.pdf)
- **中文提要：** LoRA 被用来降低大语言模型联邦微调中的通信与计算成本。即便在低秩适配器内部，仍有相当一部分参数在联邦训练中几乎不更新，导致多余通信和本地计算浪费。
- **关键词：** LoRA, fine-tuning

### HarmRLVR: Weaponizing Verifiable Rewards for Harmful LLM Alignment

- **作者：** Yuexiao Liu, Lijun Li, Xingjun Wang, Jing Shao
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.525/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.525.pdf)
- **中文提要：** 因奖励信号客观且可核验，可验证奖励强化学习在推理和代码生成上受到关注并表现强劲。这一范式可能带来的安全风险仍少被探讨。
- **关键词：** GRPO, RLVR, alignment, fine-tuning

### HEALing Entropy Collapse: Enhancing Exploration in Few-Shot RLVR via Hybrid-Domain Entropy Dynamics Alignment

- **作者：** Zhanyu Liu, Qingguo Hu, Ante Wang, Chenqing Liu, Zhishang Xiang, Hui Li, Delai Qiu, Jinsong Su
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1418/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1418.pdf)
- **中文提要：** 面向推理的大语言模型训练中，可验证奖励强化学习已被证明有效，但现有方法多默认训练数据充足。数据稀缺时，它更容易陷入更严重的熵坍缩，限制探索并拖累推理。
- **关键词：** RLVR, alignment

### How Instruction and Reasoning Data shape Post-Training: Data Quality through the Lens of Layer-wise Gradients

- **作者：** Ming Li, Yanhong Li, Ziyue Li, Tianyi Zhou
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1536/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1536.pdf)
- **中文提要：** 大语言模型的后训练正从指令遵循走向复杂推理，不同数据如何影响微调动态仍少有研究。作者对低质量与高质量的指令数据、推理数据所诱导的逐层梯度进行谱分析。
- **关键词：** instruction-following, post-training, fine-tuning

### How Much Would a Clinician Edit This Draft? Evaluating LLM Alignment for Patient Message Response Drafting

- **作者：** Parker Seegmiller, Joseph Gatto, Sarah E. Greer, Ganza Belise Isingizwe, Rohan Ray, Timothy E. Burdick, Sarah Masud Preum
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1505/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1505.pdf)
- **中文提要：** 大语言模型有望起草患者门户消息的回复，但接入临床流程时，是否真能减轻医生的门户工作负担仍令人担忧。通过评估这一起草任务，可以考察模型与个体临床医生的对齐情况。
- **关键词：** DPO, SFT, preference-optimization, alignment, fine-tuning

### IF-CRITIC: Towards a Fine-Grained LLM Critic for Instruction-Following Evaluation

- **作者：** Bosi Wen, Yilin Niu, Cunxiang Wang, Pei Ke, Xiaoying Ling, Ying Zhang, Aohan Zeng, Hongning Wang, Minlie Huang
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1147/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1147.pdf)
- **中文提要：** 指令遵循要求大语言模型的输出同时满足输入指令中的多项约束。已有研究尝试依据大模型评判给出的奖励信号，用偏好优化或强化学习来增强这一能力。
- **关键词：** instruction-following, preference-optimization

### IF-RewardBench: Benchmarking Judge Models for Instruction-Following Evaluation

- **作者：** Bosi Wen, Yilin Niu, Cunxiang Wang, Xiaoying Ling, Ying Zhang, Pei Ke, Hongning Wang, Minlie Huang
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1092/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1092.pdf)
- **中文提要：** 指令遵循的提升取决于评判模型能否给出可扩展且准确的反馈。现有元评测基准数据覆盖不足，成对评估范式也过于简化，因此这类评判模型在指令遵循上的可靠性仍缺少充分考察。
- **关键词：** instruction-following, alignment

### ImpRIF: Stronger Implicit Reasoning Leads to Better Complex Instruction Following

- **作者：** Yuancheng Yang, Lin Yang, Xu Wang, Chao Tong, Haihua Yang
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1796/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1796.pdf)
- **中文提要：** 应用越复杂，对稳健的复杂指令遵循需求就越强。透彻理解指令本身，尤其是字里行间隐含的推理结构，被认为是改进指令遵循的关键。
- **关键词：** instruction-following, fine-tuning

### Influence-based Online Experience Selection for Effective RLHF

- **作者：** Yifan Gong, Jing Yao, Xiting Wang, Xunlong Wang, Xiaoyuan Yi, Xing Xie
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.2206/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.2206.pdf)
- **中文提要：** RLHF 已被用来把大语言模型对齐到人类偏好，但现有方法样本效率差、计算开销高，收敛也慢。
- **关键词：** GRPO, RLHF, alignment

### InquireMobile: Teaching VLM-based Mobile Agent to Request Human Assistance via Reinforcement Fine-Tuning

- **作者：** Qihang Ai, Pi Bu, Yue Cao, Yingyao Wang, Jihao Gu, Jingxuan Xing, Zekun Zhu, Wei Jiang, Zhicheng Zheng, Jun Song, Yuning Jiang
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1487/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1487.pdf)
- **中文提要：** 视觉语言模型使移动智能体能够按人类指令感知并操作真实移动环境。理解或推理不足时，完全自主的范式会带来安全风险。
- **关键词：** RFT, fine-tuning

### InstructDiff: Domain-Adaptive Data Selection via Contrastive Entropy for Efficient LLM Fine-Tuning

- **作者：** Junyou Su, He Zhu, Xiao Luo, Liyu Zhang, Hong-Yu Zhou, Yun Chen, Peng Li, Yang Liu, Guanhua Chen
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.486/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.486.pdf)
- **中文提要：** 监督微调是适配大语言模型的基础，但在完整数据集上训练成本过高，收益还会递减。现有数据选择有很强的领域专属性：为通用指令遵循优化的方法在推理任务上失效，反过来也一样。
- **关键词：** SFT, instruction-tuning, instruction-following, fine-tuning

### Instructions are all you need: Self-supervised Reinforcement Learning for Instruction Following

- **作者：** Qingyu Ren, Qianyu He, Powei Chang, Jie Zeng, Zeye Sun, Fei Yu, Jiaqing Liang, Yanghua Xiao
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.217/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.217.pdf)
- **中文提要：** 语言模型经常难以遵循对真实应用至关重要的多约束指令。现有强化学习依赖外部监督，而多约束任务给出的奖励信号又很稀疏。
- **关键词：** instruction-following, reward-model

### Investigating the Representation of Backchannels and Fillers in Fine-tuned Language Models

- **作者：** Yu Wang, Leyi Lao, Langchu Huang, Gabriel Skantze, Yang Xu, Hendrik Buschmeier
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.241/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.241.pdf)
- **中文提要：** 话轮反馈和填充语是对话中的重要表达，却常被基于 Transformer 的语言模型当作噪声绕过。这项研究用多种微调策略考察它们在语言模型中的表征。
- **关键词：** fine-tuning

### J4R: Learning to Judge with Equivalent Initial State Group Relative Policy Optimization

- **作者：** Austin Xu, Yilun Zhou, Xuan-Phi Nguyen, Caiming Xiong, Shafiq Joty
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.67/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.67.pdf)
- **中文提要：** 为跟上大语言模型的开发速度，输出评估已从耗时的人工评测转向由模型自动评判其他模型的输出。LLM-as-judge 在聊天质量等相对简单的领域表现出色，面对更难的情形则显得吃力。
- **关键词：** GRPO

### JW-SVD: Bridging the Cross-Modal Mismatch in Post-Training MLLM Compression

- **作者：** Runchao Li, Yao Fu, Mu Sheng, Haotian Yu, Xianxuan Long, Kenneth A. Loparo
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1977/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1977.pdf)
- **中文提要：** 多模态大语言模型的训练后压缩存在几何冲突：为文本优化的参数子空间往往会压制与之正交的视觉特征。标准 SVD 化解不了这种跨模态失配，并造成严重的视觉退化。
- **关键词：** post-training

### Knowledge-to-Verification: Exploring RLVR for LLMs in Knowledge-Intensive Domains

- **作者：** Zhonghang Yuan, Zhefan Wang, Fang Hu, Zihong Chen, Jinzhe Li, Gang Li, Jie Ying, Huanjun Kong, Songyang Zhang, Nanqing Dong
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1891/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1891.pdf)
- **中文提要：** RLVR 在数学和编程等领域增强大语言模型推理已显出潜力。高质量可验证数据稀缺，使其在知识密集型领域尚未得到有效探索。
- **关键词：** RLVR

### Latent Agents: A Post-Training Procedure for Internalized Multi-Agent Debate

- **作者：** John Seon Keun Yi, Aaron Mueller, Dokyun Lee
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.709/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.709.pdf)
- **中文提要：** 多智能体辩论能够提升大语言模型的推理，但计算密集，作答前必须先生成很长的讨论记录。
- **关键词：** post-training, fine-tuning

### Learning Diverse Responses with Prefix-Conditioned Supervised Fine-Tuning

- **作者：** Zhiyuan Fan, Guanqiao Chen, Yanyi Huang, Mingkuan Zhao, Dadi Guo, Yi R. Fung
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.9/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.9.pdf)
- **中文提要：** 大语言模型在困难推理和通用指令遵循上表现强劲，可一旦对同一提示多次采样，输出往往高度同质、重复，探索因此低效。
- **关键词：** SFT, instruction-tuning, instruction-following, fine-tuning

### Learning from Evolving Training Dynamics: An Entropy-Maximizing Data Curation Strategy for LLM Supervised Post-Training

- **作者：** Mengxiang Zhang, Lingyuan Liu
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.505/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.505.pdf)
- **中文提要：** 监督后训练对精炼大语言模型很关键，效果却高度依赖有策略的数据策展。传统课程学习常忽略学习者能力的演变，只依靠静态、单一维度的指标。
- **关键词：** instruction-following, post-training

### Learning What Matters: Dynamic Dimension Selection and Aggregation for Interpretable Vision-Language Reward Modeling

- **作者：** Qiyuan Chen, Hongsen Huang, Jiahe Chen, Qian Shao, Jintai Chen, Hongxia Xu, Renjie Hua, Ren Chuan, Jian Wu
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.906/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.906.pdf)
- **中文提要：** 生成式评测可解释但慢，判别式高效却像不透明的黑箱。VL-MDR 把评价动态拆成细粒度、可解释的维度，而不是输出一个整体标量。
- **关键词：** DPO, reward-model, alignment

### LeLoRA: Learnable Low-Rank Adaptation of Large Language Models

- **作者：** Xiaoling Zhou, Mingjie Zhang, Zhemg Lee, Wei Ye, Shikun Zhang
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1628/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1628.pdf)
- **中文提要：** 微调能有效提升大语言模型在专门下游任务上的表现。低秩适应因能保住全量微调的效果并提高计算效率而受到关注。
- **关键词：** LoRA, fine-tuning

### LLaDA 1.5: Variance-Reduced Preference Optimization for Large Language Diffusion Models

- **作者：** Fengqi Zhu, Rongzhen Wang, Shen Nie, Xiaolu Zhang, Chunwei Wu, Jun Zhou, Yankai Lin, Ji-Rong Wen, Chongxuan Li
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.524/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.524.pdf)
- **中文提要：** 掩码扩散语言模型是有前景的语言建模范式，但其在通用任务上对齐的系统理论分析与充分实证仍相对不足。主要难点在于，偏好优化所需的基于 ELBO 的似然估计方差很高。
- **关键词：** DPO, SFT, preference-optimization, alignment

### Localized Low-Rank Adaptation within Clustered Parameter Subspaces

- **作者：** Jiahao Xiong, Yihe Liu, Xianming Hu, Hongbo Zhao, Nuoyi Chen, Jie Zhang, Kai Zhang
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1223/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1223.pdf)
- **中文提要：** LoRA 已在多个领域取得显著成效。该系列算法大多依赖铺满整张更新权重矩阵的全局低秩因子。
- **关键词：** LoRA, fine-tuning

### LoRA on the Go: Instance-level Dynamic LoRA Selection and Merging

- **作者：** Seungeon Lee, Soumi Das, Manish Gupta, Krishna P. Gummadi
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1837/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1837.pdf)
- **中文提要：** 作为参数高效的微调手段，常规 LoRA 适配器通常只针对单一任务训练，当输入横跨多种任务领域时就难以适用。
- **关键词：** LoRA, PEFT, fine-tuning

### M$^2$PO: Multi-Perspective Multi-Pair Preference Optimization for Machine Translation

- **作者：** Hao Wang, Linlong Xu, Heng Liu, Yangyang Liu, Xiaohu Zhao, Bo Zeng, Liangying Shao, Yichen Dong, Xinwei Wu, Jiang Zhou, Tianyu Dong, Xiangxiang Zeng, Longyue Wang, Weihua Luo
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.469/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.469.pdf)
- **中文提要：** 把大语言模型对齐到人类偏好对机器翻译至关重要，但误导性奖励信号常常阻碍现有方法。质量估计模型对部分幻觉和部分遗漏有系统性盲区，往往偏向表面流畅却不忠实的译文。
- **关键词：** preference-optimization, alignment

### MDP-GRPO: Stabilized Group Relative Policy Optimization for Multi-Constraint Instruction Following

- **作者：** Mohammad Mahdi Salmani-Zarchi, Zahra Rahimi, Heshaam Faili, Mohammad Javad Dousti
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1982/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1982.pdf)
- **中文提要：** 可验证奖励的强化学习适合多约束指令遵循，但奖励离散且组内分布经常同质时，标准 GRPO 会不稳定。z-score 组归一化在这一情形下会出现低方差放大、均值中心化等病态。
- **关键词：** GRPO, KTO, instruction-following

### Merging Triggers, Breaking Backdoors: Defensive Poisoning for Instruction-Tuned Language Models

- **作者：** San Kim, Gary Lee
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1113/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1113.pdf)
- **中文提要：** 指令微调让大语言模型无需额外微调就能广泛泛化到各类任务。对大规模人类或网络数据的依赖使其易受后门攻击，对手只需污染一小部分数据就能植入隐藏行为。
- **关键词：** instruction-tuning, instruction-following, fine-tuning

### Mitigating Selection Bias in Large Language Models via Permutation-Aware GRPO

- **作者：** Jinquan Zheng, Jia Yuan, Jiacheng Yao, Chenyang Gu, Pujun Zheng, Guoxiu He
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1621/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1621.pdf)
- **中文提要：** 用于多选和成对评估的大语言模型，常因选项位置、标签符号等非语义因素出现选择偏差。推理阶段去偏代价高且可能损害推理，逐点训练又忽略同一问题在不同排列下应给出一致答案。
- **关键词：** GRPO

### MoA: Heterogeneous Mixture of Adapters for Parameter-Efficient Fine-Tuning of Large Language Models

- **作者：** Jie Cao, Tianwei Lin, Bo Yuan, Rolan Yan, Hongyang He, Wenqiao Zhang, Juncheng Li, Dongping Zhang, Siliang Tang, Yueting Zhuang
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.965/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.965.pdf)
- **中文提要：** 近期研究把 LoRA 与 MoE 结合，以进一步加强大语言模型的 PEFT。现有方法采用同质的 MoE-LoRA 结构，其中的 LoRA 专家在结构与容量上相近甚至相同。
- **关键词：** LoRA, PEFT, fine-tuning

### MoCa: Modality-aware Continual Pre-training Makes Better Bidirectional Multimodal Embeddings

- **作者：** Haonan Chen, Hong Liu, Yuping Luo, Liang Wang, Nan Yang, Furu Wei, Zhicheng Dou
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.34/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.34.pdf)
- **中文提要：** 建立在因果视觉语言模型上的多模态嵌入已在多种任务中显现潜力。因果注意力对嵌入任务并不理想，对比学习又依赖高质量标注配对数据而难以扩展，训练目标与数据的多样性也有限。
- **关键词：** continued-pretraining, alignment, fine-tuning

### Multi-Agent-as-Judge: Aligning LLM-Agent-Based Automated Evaluation with Multi-Dimensional Human Evaluation

- **作者：** Jiaju Chen, Yuxuan Lu, Xiaojie Wang, Huimin Zeng, Jing Huang, Jiri Gesi, Ying Xu, Bingsheng Yao, Dakuo Wang
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.790/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.790.pdf)
- **中文提要：** 真实自然语言应用的评测往往需要多个维度，以契合不同的人类视角。人工评估者稀缺且昂贵，LLM-as-a-judge 因此尝试用语言模型智能体可信地模拟人类评估者。
- **关键词：** alignment

### OASIS: Mitigating Harmful Fine-tuning Attacks on LLMs via Orthogonal and Adaptive Safety Alignment Strategy

- **作者：** Jiayu Tang, Guowei Peng, Qiuhao Xie, Yuning Yang, Xiurui Xie, Guisong Liu
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1310/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1310.pdf)
- **中文提要：** “微调即服务”会让大语言模型因危害并不严重的样本而出现灾难性的安全退化。对齐阶段的防御通过预先注入对抗扰动，增强模型抵抗有害漂移的内在稳健性。
- **关键词：** alignment, fine-tuning

### OASIS: Online Sample Selection for Continual Instruction Tuning

- **作者：** Minjae Lee, Minhyuk Seo, Tingyu Qu, Tinne Tuytelaars, Jonghyun Choi
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.158/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.158.pdf)
- **中文提要：** 持续指令微调中，新数据以在线流式不断到达，大规模训练的延迟会妨碍实时适应。数据选择可以减轻这一开销，但现有策略常依赖预训练参考模型，而未来数据未知，这种做法并不现实。
- **关键词：** instruction-tuning

### OctoBench: Benchmarking Scaffold-Aware Instruction Following in Repository-Grounded Agentic Coding

- **作者：** Deming Ding, Shichun Liu, Enhui Yang, Jiahang Lin, Ziying Chen, Shihan Dou, Honglin Guo, Weiyu Cheng, Pengyu Zhao, Chengjun Xiao, Qunhong Zeng, Qi Zhang, Xuanjing Huang, Qidi Xu, Tao Gui
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.269/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.269.pdf)
- **中文提要：** 现代编程脚手架能把大语言模型变成有能力的软件智能体，但模型遵循脚手架所指定指令的能力仍缺少考察，尤其当约束异质且跨交互持续存在时。OctoBench 用来评测仓库情境下、感知脚手架的智能体编程中的指令遵循。
- **关键词：** instruction-following

### Omni-RewardBench: Toward a Comprehensive Evaluation of Generative Reward Models Across Modalities

- **作者：** Chi-Min Chan, Yujin Zhou, Pengcheng Wen, Boqin Yin, Jiaming Ji, Juntao Dai, Wei Xue, Sirui Han, Yike Guo
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.636/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.636.pdf)
- **中文提要：** 能联合处理文本、音频和视觉输入的全模态大语言模型，标志着向更通用智能迈进一步。要让它们对齐人类偏好，就需要全模态奖励模型作为人类判断的代理来引导行为。
- **关键词：** reward-model, alignment

### One Battle After Another: Probing LLMs' Limits on Multi-Turn Instruction Following with a Benchmark Evolving Framework

- **作者：** Qi Jia, Ye Shen, Xiujie Song, Kaiwei Zhang, Shibo Wang, Dun Pei, Xiangyang Zhu, Guangtao Zhai
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.433/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.433.pdf)
- **中文提要：** 在多主题对话中评估大语言模型的指令遵循既必要又困难。现有基准把对话轮次固定，容易饱和，也没有计入用户的交互体验。
- **关键词：** instruction-following

### On-policy Reinforcement Fine-tuning with Offline reward for Multi-step Embodied Planning

- **作者：** Di Wu, Jiaxin Fan, Chloe Gu, Guanbo Wang, Wei Yin, Wenhao Li, Bo Jin
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1822/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1822.pdf)
- **中文提要：** 具身规划要求智能体根据动态视觉观察和语言目标做出连贯的多步决策。近期视觉语言模型擅长静态感知，在交互环境中却表现吃力。
- **关键词：** RFT, fine-tuning

### OpenRubrics: Towards Scalable Synthetic Rubric Generation for Reward Modeling and LLM Alignment

- **作者：** Tianci Liu, Ran Xu, Tony Yu, Ilgee Hong, Carl Yang, Tuo Zhao, Haoyu Wang
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.791/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.791.pdf)
- **中文提要：** 奖励建模位于 RLHF 的核心，但多数现有奖励模型依赖标量或成对判断，抓不住人类偏好的多面性。rubrics-as-rewards 用结构化准则捕捉回答质量的多个维度。
- **关键词：** RLHF, instruction-following, reward-model, alignment

### Outcome Accuracy is Not Enough: Aligning the Reasoning Process of Reward Models

- **作者：** Binghai Wang, Yantao Liu, Yuxuan Liu, Tianyi Tang, Shenzhi Wang, Chang Gao, Chujie Zheng, Yichang Zhang, Le Yu, Shixuan Liu, Tao Gui, Qi Zhang, Xuanjing Huang, Bowen Yu, Fei Huang, Junyang Lin
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1924/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1924.pdf)
- **中文提要：** 生成式奖励模型与 LLM-as-a-Judge 会因优先结果准确度而出现判断对、理由错的欺骗性对齐，削弱其在 RLHF 中的泛化。为此提出理由一致性，用来衡量模型推理过程与人类判断之间的对齐。
- **关键词：** RLHF, reward-model, alignment

### Parameter Importance is Not Static: Evolving Parameter Isolation for Supervised Fine-Tuning

- **作者：** Zekai Lin, Chao Xue, Di Liang, Xingsheng Han, Peiyang Liu, Xianjie Wu, Lei Jiang, Yu Lu, Bob Simons, Shuang Liang, Minlong Peng
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1516/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1516.pdf)
- **中文提要：** 监督微调大语言模型时，任务干扰和灾难性遗忘很常见。近期方法在训练中把对任务关键的参数隔离开来，以缓解这一问题。
- **关键词：** SFT, fine-tuning

### PARIF: Pushing the Pareto Frontier of Instruction Following and Reasoning with Curriculum Reinforcement Learning

- **作者：** Rongchuan Mu, Zexin Wang, Qianyu Wang, MingHua Ma, Zekun Wang, Ming Liu, Bing Qin
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1136/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1136.pdf)
- **中文提要：** 大型推理模型擅长复杂求解，却经常忽略具体的指令约束。现有对齐方法难以兼顾通用推理与指令遵循，并受制于对教师模型的依赖、奖励投机以及推理与答案不一致。
- **关键词：** GRPO, RLVR, instruction-following, alignment

### PaTaRM: Bridging Pairwise and Pointwise Signals via Preference-Aware Task-Adaptive Reward Modeling

- **作者：** Ai Jian, Jingqing Ruan, Xing Ma, Dailin Li, Weipeng Zhang, Ke Zeng, Xunliang Cai
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.927/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.927.pdf)
- **中文提要：** 奖励模型为 RLHF 提供让大语言模型对齐人类偏好的关键监督。生成式奖励模型比传统标量奖励模型更可解释，但成对方法受到训练与推理不一致的拖累。
- **关键词：** RLHF, reward-model, alignment

### P-Check: Advancing Personalized Reward Model via Learning to Generate Dynamic Checklist

- **作者：** Kwangwook Seo, Dongha Lee
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.2011/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.2011.pdf)
- **中文提要：** 个性化奖励建模近来主要借助用户交互历史，使模型判断贴近个人偏好。现有方法大多把用户上下文当作静态或隐式条件，未能捕捉人类判断动态且多面的特点。
- **关键词：** reward-model

### Perplexity-Aware Data Scaling Law: Perplexity Landscapes Predict Performance for Continual Pre-training

- **作者：** Lei Liu, Hao Zhu, Xiaoyan Yang, Yue Shen, Zhixuan Chu, Jian Wang, Jinjie Gu, Kui Ren
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.999/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.999.pdf)
- **中文提要：** 持续预训练是把基础模型适配到特定领域应用的基本途径。预训练缩放定律刻画了数据集规模与大语言模型测试损失之间的幂律关系。
- **关键词：** continued-pretraining

### Powerful Training-Free Membership Inference Against Fine-Tuned Autoregressive Language Models

- **作者：** David Ili{\'c}, David Stanojevi{\'c}, Kostadin Cvejoski
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.640/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.640.pdf)
- **中文提要：** 微调后的语言模型可能记住并暴露训练数据中的敏感信息。成员推断攻击为审计这些风险提供了原则性框架，但现有方法的检出能力有限，尤其在实际隐私审计所要求的低误报条件下。
- **关键词：** fine-tuning

### Pref-CTRL: Preference Driven LLM Alignment using Representation Editing

- **作者：** Imranul Ashrafi, Inigo Jauregi Unanue, Massimo Piccardi
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-short.41/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-short.41.pdf)
- **中文提要：** 测试时对齐不必微调，而是在推理阶段对内部表征做轻量干预来引导输出。RE-Control 在隐藏状态上训练外部价值函数，再借助梯度引导生成。
- **关键词：** alignment, fine-tuning

### PRInTS: Reward Modeling for Long-Horizon Information Seeking

- **作者：** Jaewoo Lee, Archiki Prasad, Justin Chen, Zaid Khan, Elias Stengel-Eskin, Mohit Bansal
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1574/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1574.pdf)
- **中文提要：** 信息寻求要求智能体在长轨迹上收集并推理工具产生的信息。由语言模型支撑的智能体在这类多步任务上仍然困难。
- **关键词：** PRM, reward-model

### PRISM: Probabilistic Reward Model with Inherent Structural Modeling

- **作者：** Yuhang Zhou, Yixin Cao, Yuchen Ni, Shihan Dou, Xutian Chen, Ge Zhang, Xiang Liu, Guangnan Ye
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.563/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.563.pdf)
- **中文提要：** 标准评估器把多样的人类判断压缩成单一标量，把主观偏好与认知不确定性混在一起。这种结构错配往往导致对齐脆弱和奖励投机。
- **关键词：** reward-model, alignment

### Privacy Collapse: Benign Fine-Tuning Can Break Contextual Privacy in Language Models

- **作者：** Anmol Goel, Cornelius Emde, Seong Joon Oh, Sangdoo Yun, Martin Gubri
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.400/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.400.pdf)
- **中文提要：** 对前沿模型做看似无害的微调，也可能导致上下文隐私崩塌。训练数据里多种细微模式都会削弱这种隐私，包括为有用性优化、接触用户信息、情感与主观对话，以及会打印内部变量的调试代码。
- **关键词：** fine-tuning

### Process Reward Models Meet Planning: Generating Precise and Scalable Datasets for Step-Level Rewards

- **作者：** Raffaele Pisano, Roberto Navigli
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1292/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1292.pdf)
- **中文提要：** 过程奖励模型能为大语言模型的推理提供步骤级反馈，因为思维链即使最终答案正确也常含错误。现有过程奖励数据构建成本高、容易标错，而且主要局限在数学领域。
- **关键词：** PRM, reward-model

### ProMedical: Hierarchical Fine-Grained Criteria Modeling for Medical LLM Alignment via Explicit Injection

- **作者：** He Geng, Yangmin Huang, Lixian Lai, Qianyun Du, Hui Chu, Zhiyang He, Jiaxue Hu, Xiaodong Tao
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1714/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1714.pdf)
- **中文提要：** 让大语言模型对齐高风险的医疗标准仍然困难，粗粒度偏好信号与复杂、多维的临床规范之间并不匹配。ProMedical 是一套以细粒度临床准则为基础的统一对齐框架。
- **关键词：** GRPO, reward-model, alignment

### Prune as You Generate: Online Rollout Pruning for Faster and Better RLVR

- **作者：** Haobo Xu, Sirui Chen, Ruizhong Qiu, Yuchen Yan, Chen Luo, Monica Xiao Cheng, Jingrui He, Hanghang Tong
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.632/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.632.pdf)
- **中文提要：** RLVR 显著推进了大语言模型的推理能力。GRPO 和 DAPO 却因为每个提示都要采样大量推演轨迹，计算代价很高。
- **关键词：** GRPO, RLVR

### Putting HUMANS first: Efficient LAM Evaluation with Human Preference Alignment

- **作者：** Woody Haosheng Gan, William Barr Held, Diyi Yang
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1816/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1816.pdf)
- **中文提要：** 大型音频模型迅速增多，全面比较它们的基准成本很高。该研究考察精简子集能否在减少成本与数据冗余的同时，仍然可靠地评测这些模型。
- **关键词：** preference-optimization, alignment

### R1-RE: Cross-Domain Relation Extraction with RLVR

- **作者：** Runpeng Dai, Tong Zheng, Run Yang, Kaixian Yu, Hongtu Zhu
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1587/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1587.pdf)
- **中文提要：** 关系抽取是自然语言处理的核心任务。传统做法通常把它当作监督学习，直接把上下文映射到标签，跨领域泛化往往较差。
- **关键词：** RLVR

### ReActR: Reasoning through Error-Activated Reflection for LLM Post-Training

- **作者：** Lina Sun
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1993/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1993.pdf)
- **中文提要：** 当前推理训练过度扩充正确样本，对错误推理轨迹关注不够。ReActR 借鉴人从错误中学习的方式，通过习得反思行为来增强推理。
- **关键词：** GRPO, SFT, post-training, fine-tuning

### ReCode: Reinforcing Code Generation with Reasoning-Process Rewards

- **作者：** Lishui Fan, Yu Zhang, Mouxiang Chen, Zhongxin Liu
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.2031/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.2031.pdf)
- **中文提要：** 严谨推理常常是写出正确代码的关键，而代码生成的强化学习往往忽略对推理质量的优化。把过程级监督引入强化学习虽有吸引力，摘要只指出它面临挑战。
- **关键词：** GRPO, PRM, reward-model

### Red-Bandit: Test-Time Adaptation for LLM Red-Teaming via Bandit-Guided LoRA Experts

- **作者：** Christos Ziakas, Nicholas Loo, Nishita Jain, Alessandra Russo
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.2156/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.2156.pdf)
- **中文提要：** 自动化红队测试可以在部署前规模化审计大语言模型，但现有方法缺少在推理时高效适应模型特有漏洞的机制。Red-Bandit 在线适应，以便在操纵话术、俚语等不同攻击风格下识别并利用模型的失效模式。
- **关键词：** LoRA, PEFT, post-training

### ReflectRM: Boosting Generative Reward Models via Self-Reflection within a Unified Judgment Framework

- **作者：** Kai Qin, Liangxin Liu, Yu Liang, Longzheng Wang, Wangyan, Zhang Yueyang, Long Xia, Zhiyuan Sun, Houde Liu, Daiting Shi
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1676/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1676.pdf)
- **中文提要：** 奖励模型是 RLHF 流程中的关键部件，直接决定大语言模型的对齐质量。生成式奖励模型被视为更优范式，比传统标量奖励模型更可解释，泛化也更强。
- **关键词：** RLHF, reward-model, alignment

### Rendering Data Unlearnable by Exploiting LLM Alignment Mechanisms

- **作者：** Ruihan Zhang, Jun Sun
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1885/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1885.pdf)
- **中文提要：** 大语言模型日益在海量、异构文本上训练，专有或个人数据被未经授权用于训练的担忧随之加重。这项工作在现实的黑盒设定下，讨论如何防止数据被不想要的模型学习。
- **关键词：** alignment, fine-tuning

### ReRec: Reasoning-Augmented LLM-based Recommendation Assistant via Reinforcement Fine-tuning

- **作者：** Jiani Huang, Shijie Wang, Liang-Bo Ning, Wenqi Fan, Li Qing
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.964/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.964.pdf)
- **中文提要：** 智能推荐助手需要处理复杂查询，并给出个性化、由推理驱动的建议。基于大语言模型的推荐系统虽有潜力，多步推理仍是短板。
- **关键词：** RFT, instruction-following, preference-optimization, alignment, fine-tuning

### Rethinking Entropy Interventions in RLVR: An Entropy Change Perspective

- **作者：** Zhezheng Hao, Hong Wang, Haoyang Liu, Jian Luo, Jiarui Yu, Hande Dong, Qiang Lin, Can Wang, Jiawei Chen
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1436/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1436.pdf)
- **中文提要：** 作为增强大语言模型推理的基础技术，RLVR 的训练常被熵崩溃困扰：策略熵迅速下降，限制探索并削弱训练效果。
- **关键词：** RLVR

### Rethinking Expert Trajectory Utilization in LLM Post-training for Mathematical Reasoning

- **作者：** Bowen Ding, Yuhan Chen, Jiayang Lyu, Jiyao Yuan, Qi Zhu, Shuangshuang Tian, Dantong Zhu, Futing Wang, Heyuan Deng, Fei Mi, Lifeng Shang, Tao Lin
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1528/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1528.pdf)
- **中文提要：** 监督微调与强化学习主导数学推理的后训练，但二者对专家轨迹的依赖有根本不同。为弄清如何最好地利用这些轨迹，工作提出可塑性上限框架。
- **关键词：** SFT, post-training, fine-tuning

### Revisiting the Reliability of Language Models in Instruction-Following

- **作者：** Jianshuo Dong, Yutong Zhang, Liu Yan, Zhenyu Zhong, Tao Wei, Chao Zhang, Han Qiu
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.354/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.354.pdf)
- **中文提要：** 在 IFEval 一类基准上，先进大语言模型的指令遵循已接近上限。用户在真实使用中会改措辞、换语境和任务表述，高分并不必然意味着服务可靠。
- **关键词：** instruction-following

### Reward Modeling for Scientific Writing Evaluation

- **作者：** Furkan {\c{S}}ahinu{\c{c}}, Subhabrata Dutta, Iryna Gurevych
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.567/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.567.pdf)
- **中文提要：** 科学写作要求深厚的领域知识、任务特定要求，以及借助领域知识满足任务规范的推理能力。科学文本生成已被广泛研究，其评估仍是困难且开放的问题。
- **关键词：** reward-model, fine-tuning

### Robust Tool Use via Fission-GRPO: Learning to Recover from Execution Errors

- **作者：** Zhiwei Zhang, Fei Zhao, Rui Wang, Zezhong Wang, Bin Liang, Jiakang Wang, Yao Hu, Shaosheng Cao, Kam-Fai Wong
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1880/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1880.pdf)
- **中文提要：** 工具调用本身大语言模型已经能做好，多轮执行却很脆：出错后，较小的模型往往重复发出无效调用，而不是读懂反馈再恢复。当前训练并没有明确教模型如何从执行错误中恢复。
- **关键词：** GRPO, fine-tuning

### S2S-Arena: Evaluating Paralinguistic Instruction Following in Speech-to-Speech Models

- **作者：** Feng Jiang, Zhiyu Lin, Yiyang Liu, Liumeng Xue, Fan Bu, Yuhao Du, Xiangying Chen, Benyou Wang, Haizhou Li
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1615/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1615.pdf)
- **中文提要：** 语音到语音系统因大语言模型而更接近自然口语交互。现有基准仍主要按文本来评，韵律、情绪和说话人特质等副语言线索大多被忽略。
- **关键词：** instruction-following

### SADA: Bridging In-Context Learning and Fine-Tuning via State-Aligned Distillation Adapters

- **作者：** Wenhao Gao, Tianlong Wang, Wei Jia, Linhao Zhang, Aiwei Liu, Miao Fan, Zhou Xiao
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1046/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1046.pdf)
- **中文提要：** 提示式上下文学习与参数微调都能把外部信息注入大语言模型，但前者推理成本高，后者又需要昂贵的再训练。为弥合二者，上下文到参数的映射把提示转成临时适配器权重。
- **关键词：** alignment, fine-tuning

### Safeguarding LLM Fine-tuning via Push-Pull Distributional Alignment

- **作者：** Haozhong Wang, Zhuo Li, Yibo Yang, He Zhao, Hongyuan Zha, Dandan Guo
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1083/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1083.pdf)
- **中文提要：** 大语言模型原有的安全对齐在微调中容易被侵蚀，即便所用数据看起来无害。靠数据筛选的防御多停留在启发式的单条判断，既忽视数据分布的整体几何，也没有明确排斥有害模式。
- **关键词：** alignment, fine-tuning

### SATQuest: A Verifier for Logical Reasoning Evaluation and Reinforcement Fine-Tuning of LLMs

- **作者：** Yanxiao Zhao, Yaqian Li, Zihao Bo, Rinyoichi Takezoe, Haojia Hui, Mo Guang, Lei Ren, Xiaolin Qin, Kaiwen Long
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.96/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.96.pdf)
- **中文提要：** 社区仍缺少可控、可扩展且可核验的工具来分析并改进大语言模型的推理。SATQuest 这一验证器直接从合取范式实例生成多样的 SAT 推理任务，并用 PySAT 客观核对答案。
- **关键词：** RFT, fine-tuning

### Scaling Behaviors of LLM Reinforcement Learning Post-Training: An Empirical Study in Mathematical Reasoning

- **作者：** Zelin Tan, Hejia Geng, Xiaohang Yu, Mulei Zhang, Guancheng Wan, Yifan Zhou, Qiang He, Xiangyuan Xue, Heng Zhou, Yutao Fan, Zhong-Zhi Li, Zaibin Zhang, Guibin Zhang, Chen Zhang, Zhenfei Yin, Philip Torr, Lei Bai
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1444/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1444.pdf)
- **中文提要：** 预训练阶段的缩放规律已被大量研究，强化学习后训练下的缩放行为仍不清楚。这项考察聚焦数学推理，看大语言模型在强化学习后训练中如何随规模变化。
- **关键词：** instruction-tuning, post-training

### Scaling Law for Multimodal Large Language Model Supervised Fine-Tuning

- **作者：** YiFan Zhang, Tao Yu, Feng Li, Chaoyou Fu, Yibo Hu, Kun Wang, Qingsong Wen, Zhang Zhang, Liang Wang, Rong Jin
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.603/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.603.pdf)
- **中文提要：** 监督微调对多模态大语言模型至关重要，但还缺少能指导模型与数据配置的完整缩放规律。该研究对填补这一空白做了初步尝试。
- **关键词：** SFT, fine-tuning

### Scaling Reasoning, Losing Control: Evaluating Instruction Following in Large Reasoning Models

- **作者：** Tingchen Fu, Yafu Li, Jiawei Gu, Xiaoye Qu, Yu Cheng
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1878/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1878.pdf)
- **中文提要：** 指令遵循关系到大语言模型是否贴合用户意图。面向推理的模型在复杂数学问题上表现出色，它们能否遵守自然语言指令却仍少被考察。
- **关键词：** instruction-following, alignment

### SED-SFT: Selectively Encouraging Diversity in Supervised Fine-Tuning

- **作者：** Yijie Chen, Yijin Liu, Fandong Meng
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-short.54/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-short.54.pdf)
- **中文提要：** 先做 SFT 再做强化学习，已成为大语言模型后训练的常见范式。由交叉熵损失驱动的常规 SFT 却容易引发模式坍缩，使模型过度集中于特定回答模式。
- **关键词：** SFT, post-training, fine-tuning

### Select Before Use: On the Importance of Reference Model Selection in Preference Alignment

- **作者：** Muyang Li, Runze Wu, Xiangyu Zhao, Bo Han, Daoyi Dong, Tongliang Liu
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.780/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.780.pdf)
- **中文提要：** 后训练通常先做 SFT，再进行偏好对齐，以便生成安全、有帮助且符合指令的内容。其中 SFT 模型同时充当后续偏好对齐的初始化与参考模型。
- **关键词：** SFT, preference-optimization, post-training, alignment, fine-tuning

### SFTMix: Elevating Language Model Instruction Tuning with Mixup Recipe

- **作者：** Yuxin Xiao, Shujian Zhang, Marzyeh Ghassemi, Wenxuan Zhou
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.78/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.78.pdf)
- **中文提要：** 为获得指令遵循能力，大语言模型在指令与回答配对上用下一词预测做指令微调。改进工作往往追求更高质量的 SFT 数据，而这通常需要专有模型过滤或人工标注。
- **关键词：** SFT, instruction-tuning, instruction-following, fine-tuning

### SGT: Securing Open-Source LLMs Against Malicious Fine-tuning via Safety Guidance Trigger

- **作者：** Sunguk Shin, Fangzhao Wu, Byung-Jun Lee, Meeyoung Cha, Sungwon Park
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.463/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.463.pdf)
- **中文提要：** 开放权重便于定制大语言模型，也增加了发布后遭受恶意微调的风险。已有防御多通过约束参数空间中的对抗微调动态，或削弱内部表示里的有害信息，来提高对这类微调的稳健性。
- **关键词：** alignment, fine-tuning

### Skill-Aware Data Selection and Fine-Tuning for Data-Efficient Reasoning Distillation

- **作者：** Lechen Zhang, Yunxiang Zhang, Wei Hu, Lu Wang
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-short.49/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-short.49.pdf)
- **中文提要：** DeepSeek-R1 一类大型推理模型及其蒸馏变体在复杂推理上表现强劲。把它们蒸馏下来往往需要大规模 SFT 数据，因而推动对数据高效训练方法的寻求。
- **关键词：** SFT, fine-tuning

### Soft Orthogonal Low-Rank Adaptation for Knowledge Sharing in Large Language Model Continual Learning

- **作者：** Yitong Wang, Xue Han, WenChun Gao, Qian Hu, Jiahui Wang, Ziqing Wang, Lijun Mei, Junlan Feng
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.842/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.842.pdf)
- **中文提要：** 大语言模型进入真实应用后，持续学习并不轻松：巨大参数规模带来可观计算成本，现有方法又主要缓解灾难性遗忘，对知识共享着墨很少。
- **关键词：** LoRA

### SOS-LoRA: Static Orthogonal-Subspace Low-Rank Adaptation with Fixed Multi-Scale Scaling

- **作者：** Yupeng Chang, Yuan Wu, Yi Chang
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.184/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.184.pdf)
- **中文提要：** LoRA 是广泛使用的 PEFT 方法。在固定秩预算下，它把每个待适应权重收成单一的低维输入侧通路，可能让不同行为共用输入方向，并在优化中相互干扰。
- **关键词：** LoRA, PEFT, fine-tuning

### Step-GRPO: Internalizing Dynamic Early Exit for Efficient Reasoning

- **作者：** Benteng Chen, Weida Wang, Shufei Zhang, Mingbao Lin, Min Zhang
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.990/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.990.pdf)
- **中文提要：** 使用长思维链的大型推理模型善于解题，却把算力花在多余检查上。训练时的长度惩罚可能损伤能力，推理时提前退出又增加系统开销，抑制这种过度思考并不容易。
- **关键词：** GRPO, post-training

### TA-GRPO-d: Trajectory-Aware GRPO for Optimizing Denoising Trajectories in Diffusion LLMs

- **作者：** Gyunyeop Kim, Sangwoo Kang
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1723/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1723.pdf)
- **中文提要：** 扩散大语言模型通过反复并行去掩码部分加噪序列来生成文本，有望比自回归解码延迟更低。多数离散扩散模型仍依赖固定去噪日程，既不随输入难度调整，也无法学习更高效的去掩码顺序。
- **关键词：** GRPO

### TalkLoRA: Communication-Aware Mixture of Low-Rank Adaptation for Large Language Models

- **作者：** Lin Mu, Haiyang Wang, Li Ni, Lei Sang, Zhize Wu, Peiquan Jin, Yiwen Zhang
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.840/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.840.pdf)
- **中文提要：** LoRA 支持对大语言模型做参数高效微调，专家混合扩展则通过动态组合多个 LoRA 专家来增加灵活性。现有做法常假设这些专家彼此独立，容易出现路由不稳和个别专家主导。
- **关键词：** LoRA, PEFT, fine-tuning

### Taming Extreme Tokens: Covariance-Aware GRPO with Gaussian-Kernel Advantage Reweighting

- **作者：** Cheng Wang, Qin Liu, Wenxuan Zhou, Muhao Chen
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-short.45/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-short.45.pdf)
- **中文提要：** GRPO 被用来提升大语言模型的推理能力。它在训练中难以平衡探索与利用，表现因而常常不够理想。
- **关键词：** GRPO

### TARE: Lightweight Token-Aware Representation Editing for Fine-tuning Transformer-like Models

- **作者：** Yulong Wang, Siyu Zhao
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.841/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.841.pdf)
- **中文提要：** 低秩方法可能代价不小，全局表示编辑又常常欠拟合词元级上下文。TARE 作为一种 PEFT 方法，以较小的额外推理开销和很少的调参做细粒度、随词元变化的编辑，并落在类 Transformer 结构每个 FFN 块之后。
- **关键词：** LoRA, PEFT, fine-tuning

### Teach a Reward Model to Correct Itself: Reward Guided Adversarial Failure Discovery for Robust Reward Modeling

- **作者：** Pankayaraj Pathmanathan, Furong Huang
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.418/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.418.pdf)
- **中文提要：** 由人类偏好训练的奖励模型是对齐大语言模型的核心，但在分布偏移或针对性扰动下常常失效。现有失败发现依赖对偏好属性的先验，因而难以扩展到新的模型或数据。
- **关键词：** DPO, reward-model, alignment

### Team-Based Self-Play With Dual Adaptive Weighting for Fine-Tuning LLMs

- **作者：** Wu Li, Yigeng Zhou, Zesheng Shi, Yequan Wang, Min Zhang, Jing Li
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.847/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.847.pdf)
- **中文提要：** 近期自训练减轻了对齐对人工标注的依赖，但仍对合成数据质量敏感，迭代中容易不稳并放大偏差。正负回答之间的差距还会随轮次缩小，使优化逐渐失效，文中据此提出基于团队的方案。
- **关键词：** SFT, alignment, fine-tuning

### The Bidirectional Process Reward Model

- **作者：** Lingyin Zhang, Jun Gao, Xiaoxue Ren, Ziqiang Cao
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.572/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.572.pdf)
- **中文提要：** 过程奖励模型为解答轨迹中的中间推理步骤打细粒度分数，用以提升大语言模型的推理质量。多数现有模型只做从左到右的单向评估，对全局上下文的利用因此受限。
- **关键词：** PRM, reward-model

### Toward Secure Tuning: Mitigating Security Risks from Instruction Fine-Tuning

- **作者：** Yanrui Du, Fenglei Fan, Sendong Zhao, Jiawei Cao, Ming Ma, Danyang Zhao, Shuren Qi, Ting Liu, Bing Qin
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.115/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.115.pdf)
- **中文提要：** 指令微调是按多样下游需求定制大语言模型的关键技术。已有研究表明，它可能削弱模型内置的安全机制，从而带来明显的安全风险。
- **关键词：** fine-tuning

### Tracing the Roots: A Multi-Agent Framework for Uncovering Data Lineage in Post-Training LLMs

- **作者：** Yu Li, Xiaoran Shang, Qizhi Pei, Yun Zhu, Xin Gao, Honglin Lin, Zhanping Zhong, Zhuoshi Pan, Zheng Liu, Xiaoyang Wang, Conghui He, Dahua Lin, Feng Zhao, Lijun Wu
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.435/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.435.pdf)
- **中文提要：** 后训练数据深刻塑造大语言模型的能力，数据集却常被当作孤立产物，其演化背后的系统联系被忽略。工作把数据谱系引入这一生态，并提出自动多智能体框架来重建这种演化。
- **关键词：** post-training

### TROJail: Trajectory-Level Optimization for Multi-Turn Large Language Model Jailbreaks with Process Rewards

- **作者：** Xiqiao Xiong, Ouxiang Li, Zhuo Liu, Moxin Li, Wentao Shi, Fengbin Zhu, Qifan Wang, Fuli Feng
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.2220/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.2220.pdf)
- **中文提要：** 大语言模型已被广泛采用，但仍容易受到多轮越狱攻击，影响安全部署。由此形成了训练自动化多轮攻击者、以探测模型安全漏洞的任务。
- **关键词：** PRM

### Turning Failures into Value: Negative Experience Replay for RLVR via Confidence Gating and Boundary Failure Sampling

- **作者：** Jialiang Guo, Fucheng Xiong, Xu He, Haodong Zhao, Xingyang li, Ke Zeng, Xunliang Cai
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1682/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1682.pdf)
- **中文提要：** 可验证奖励的强化学习已成为增强大语言模型推理的常见范式，但 GRPO 这类同策略算法样本效率不高。现有经验回放多重复正确轨迹以巩固已学模式并加快收敛，却放过了大量失败样本。
- **关键词：** GRPO, RLVR

### UniSRM: A Unified Speech Reward Model for Reasoning-Based Fine-grained Assessment

- **作者：** Yuanyuan Wang, Dongchao Yang, Yayue Deng, Zhiyong Wu, Steven Y. Guo, Helen M. Meng, Xixin Wu
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.2150/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.2150.pdf)
- **中文提要：** 语音生成评估仍大量依赖平均意见分这类人工判断，昂贵、主观且难以大规模复现。已有基于 AudioLLM 的评判模型通常只覆盖很窄场景，例如语句级质量或单轮对话，对多样语音的覆盖有限。
- **关键词：** reward-model

### UPDESH: Synthesizing Grounded Instruction Tuning Data for 13 Indic Languages

- **作者：** Pranjal A Chitale, Varun Gumma, Sanchit Ahuja, Prashant Kodali, Manan Uppadhyay, Deepthi Sudharsan, Sunayana Sitaram
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1763/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1763.pdf)
- **中文提要：** 构建有文化根基的多语言人工智能仍然困难，低资源语言尤其如此。合成数据带来了可能，但其在多语言和多文化情境中是否有效仍缺少考察。
- **关键词：** instruction-tuning, instruction-following, alignment, fine-tuning

### Valid Survey Simulations with Limited Human Data: The Roles of Prompting, Fine-Tuning, and Rectification

- **作者：** Stefan Krsteski, Giuseppe Russo, Serina Chang, Robert West, Kristina Gligori{\'c}
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.498/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.498.pdf)
- **中文提要：** 问卷调查能提供关于公众意见与行为的见解，但实施成本高、周期长。用大语言模型代替人类受访者被看作可扩展的低成本方案，其输出却常常有偏，并给出无效估计。
- **关键词：** fine-tuning

### VRPO: Rethinking Value Modeling for Robust RL under Noisy Supervision in LLM Post-Training

- **作者：** Dingwei Zhu, Shihan Dou, Zhiheng Xi, Senjie Jin, Guoqiang Zhang, Jiazheng Zhang, Junjie Ye, Mingxu Chai, Enyu Zhou, Ming Zhang, Yuhui Wang, Caishuang Huang, Chenhao Huang, Yunke Zhang, Yuran Wang, Tao Gui, Qi Zhang, Xipeng Qiu, Xuanjing Huang
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1103/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1103.pdf)
- **中文提要：** 真实环境中的强化学习常遇到含糊或不完整的奖励监督，动摇策略的稳定性与泛化。这类噪声可能让模型忽略关键信息，甚至使优势估计崩溃。
- **关键词：** GRPO, reward-model, post-training

### What Do LLMs Learn First? Asymmetric Learning Dynamics of Input Complexity and Output Ambiguity in Preference Alignment

- **作者：** Mengyang Li, Jingwen Wang, Pinlong Zhao
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.789/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.789.pdf)
- **中文提要：** DPO 已成为让大语言模型对齐人类偏好的常用方法，现有做法却在训练中平等对待所有偏好对。工作区分了两类学习难度：输入复杂度反映理解提示的困难，输出歧义衡量区分偏好的难度。
- **关键词：** DPO, preference-optimization, alignment

### What Makes Good Instruction-Tuning Data? An In-Context Learning Perspective

- **作者：** Guangzeng Han, Xiaolei Huang
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.45/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.45.pdf)
- **中文提要：** 指令微调数据里往往有大量冗余和低质量样本，需要有效的筛选。基于加权上下文影响（wICI）的框架，衡量每个候选样本能在多大程度上降低语义相近样本的指令遵循难度。
- **关键词：** instruction-tuning, instruction-following

### Why Does Reinforcement Learning Generalize? A Feature-Level Mechanistic Study of Post-Training in Large Language Models

- **作者：** Dan Shi, Zhuowen Han, Simon Ostermann, Renren Jin, Josef van Genabith, Deyi Xiong
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1808/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1808.pdf)
- **中文提要：** 基于强化学习的后训练常把推理表现推广到训练领域之外，SFT 则容易造成通用能力遗忘，二者反差的机制仍不清楚。为此给出特征层面的机制分析方法，用来探究强化学习的泛化。
- **关键词：** SFT, post-training, fine-tuning

### Why LLM Safety Guardrails Collapse After Fine-tuning: A Similarity Analysis Between Alignment and Fine-tuning Datasets

- **作者：** Lei Hsiung, Tianyu Pang, Yung-Chen Tang, Linyue Song, Tsung-Yi Ho, Pin-Yu Chen, Yaoqing Yang
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.756/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.756.pdf)
- **中文提要：** 大语言模型在下游微调之后尤其容易出现安全对齐被绕过的情况。现有缓解主要是在护栏失守后被动处置、在微调过程中移除有害梯度，或持续强化安全对齐。
- **关键词：** alignment, fine-tuning

### Why Supervised Fine-Tuning Fails to Learn: A Systematic Study of Incomplete Learning in Large Language Models

- **作者：** Chao Xue, Yao Wang, Mengqiao Liu, Di Liang, Xingsheng Han, Peiyang Liu, Xianjie Wu, Chenyao Lu, Lei Jiang, Yu Lu, Haibo Shi, Shuang Liang, Minlong Peng, Flora D. Salim
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1393/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1393.pdf)
- **中文提要：** SFT 是让大语言模型适应下游任务的常规途径。一个持续存在的失败是：即便训练已经收敛，模型仍常常无法正确复现自身监督数据中的一部分。
- **关键词：** SFT, post-training, fine-tuning

### WildFeedback: Aligning LLMs With In-situ User Interactions And Feedback

- **作者：** Taiwei Shi, Zhuoer Wang, Longqi Yang, Ying-Chun Lin, Zexue He, Mengting Wan, Pei Zhou, Sujay Kumar Jauhar, Sihao Chen, Shan Xia, Hongfei Zhang, Jieyu Zhao, Xiaofeng Xu, Xia Song, Jennifer Neville
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1701/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1701.pdf)
- **中文提要：** 让大语言模型对齐人类偏好仍是关键挑战。依赖人工或模型标注数据的传统对齐，受限于资源消耗、固有主观性、与真实用户偏好错位，以及可能放大模型偏差的反馈回路。
- **关键词：** alignment, fine-tuning

### WildReward: Learning Reward Models from In-the-Wild Human Interactions

- **作者：** Hao Peng, Yunjia Qi, Xiaozhi Wang, Zijun Yao, Lei Hou, Juanzi Li
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.864/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.864.pdf)
- **中文提要：** 奖励模型对训练大语言模型至关重要，但通常依赖大规模人工标注的偏好对。模型广泛部署之后，真实交互成为隐含奖励信号的丰富来源。
- **关键词：** DPO, reward-model

### WSDPO: A Generative Word Sense Disambiguation Framework with Chain-of-Thought and Preference Optimization

- **作者：** Kunpeng Kang, Shuaimin Li, Kaiyuan Zhang, Luyang Zhang, Jiasheng Si, Bing Xu, Kehai Chen, Muyun Yang, Wenpeng Lu
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.1610/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.1610.pdf)
- **中文提要：** 词义消歧是自然语言处理的基础任务。近期工作把它改写成生成任务，由大语言模型写出定义来表达歧义词在上下文中的含义，而多数实现只是直接做 SFT。
- **关键词：** SFT, preference-optimization, fine-tuning

### Your Reasoning Model is Secretly a Reward Model - Optimization-Free Verification from Experience

- **作者：** Zhenwen Liang, Ruosen Li, Yujun Zhou, Linfeng Song, Dian Yu, Xinya Du, Haitao Mi, Dong Yu
- **会议：** ACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.acl-long.788/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.acl-long.788.pdf)
- **中文提要：** 在分支很多的设定里，同一提示会得到许多看似合理的候选，评估输出质量尤为困难。现有验证器多看表层文本，如奖励模型、模型评判或多数投票，或依赖词元概率导出的置信代理，两者都较脆弱，前者还会受文风影响。
- **关键词：** reward-model

## Findings

### Accelerating LLM Fine-Tuning via Embedding Knowledge Transfer

- **作者：** Meishu Peng, Ziyue Zhang, Yi Zhang, Pengyang Wang, Zixuan Yuan, Denghui Zhang
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.5/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.5.pdf)
- **中文提要：** 微调是把大语言模型适配到下游任务的关键环节。这些参数规模很大的模型在为新任务定制时，需要大量计算资源。
- **关键词：** PEFT, alignment, fine-tuning

### Activation Reward Models for Few-Shot Model Alignment

- **作者：** Tianning Chai, Chancharik Mitra, Brandon Huang, Gautam Rajendrakumar Gare, Zhiqiu Lin, Assaf Arbelle, Leonid Karlinsky, Rogerio Feris, Trevor Darrell, Deva Ramanan, Roei Herzig
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1709/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1709.pdf)
- **中文提要：** 让大语言模型和大多模态模型符合人类偏好，对其真实使用中的行为很重要。常见路径是用奖励模型来支持强化学习后训练。
- **关键词：** reward-model, post-training, alignment, fine-tuning

### AgentV-RL: Scaling Reward Modeling with Agentic Verifier

- **作者：** Jiazheng Zhang, Ziche Fu, Zhiheng Xi, Wenqing Jing, Mingxu Chai, Wei He, Guoqiang Zhang, Chenghao Fan, Chenxin An, Wenxiang Chen, Zhicheng Liu, Haojie Pan, Dingwei Zhu, Tao Gui, Qi Zhang, Xuanjing Huang
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1156/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1156.pdf)
- **中文提要：** 验证器已被证明能借助测试时扩展来增强大语言模型的推理。到了复杂领域，它们仍面临显著挑战。
- **关键词：** reward-model

### Anatomy of Unlearning: The Dual Impact of Fact Salience and Model Fine-Tuning

- **作者：** Anna Borisiuk, Andrey Savchenko, Alexander Panchenko, Elena Tutubalina
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1287/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1287.pdf)
- **中文提要：** 机器遗忘使大语言模型能够移除不安全或过时的信息。现有工作默认所有事实同样容易被遗忘，也很少区分被遗忘知识来自预训练还是 SFT。
- **关键词：** SFT, fine-tuning

### Astra: Activation-Space Tail-Eigenvector Low-Rank Adaptation of Large Language Models

- **作者：** Kainan Liu, Yong Zhang, Ning Cheng, Yun Zhu, Yanmeng Wang, Shaojun Wang, Jing Xiao
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1593/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1593.pdf)
- **中文提要：** PEFT 方法尤其是 LoRA，因计算与存储上的效率而被广泛用于适配预训练模型。LoRA 及其变体对激活空间中尾部特征向量所对应子空间的利用仍然不足，微调效果可能因此受限。
- **关键词：** LoRA, PEFT, fine-tuning

### Automatic Paper Analysis and Categorisation for Systematic Reviews with Combined Reasoning-Augmented SFT and DAPO RL

- **作者：** Michela Lorandi, Anya Belz, Simon Mille, Craig Thomson
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.2022/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.2022.pdf)
- **中文提要：** 系统综述综合已发表研究的证据，被视为某一领域最高层级的研究证据。其流程包括沿多个维度给研究分类，这项工作既费力又耗时。
- **关键词：** SFT, fine-tuning

### Balancing Fidelity and Plasticity: Aligning Mixed-Precision Fine-Tuning with Linguistic Hierarchies

- **作者：** Changhai Zhou, Shiyang Zhang, Yuhua Zhou, Jun Gao, Qian Qiao, Shichao Weng, Weizhong Zhang, Cheng Jin
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.779/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.779.pdf)
- **中文提要：** 在资源受限的边缘设备上部署并微调大语言模型，必须在内存占用与任务表现之间严格权衡。现有量化感知微调通常把权重精度和适配器容量拆开处理，忽略某一层的适应能力受其冻结权重所保留信息的制约。
- **关键词：** instruction-tuning, LoRA, PEFT, alignment, fine-tuning

### B-APO: Bias-Targeted Adversarial Preference Optimization for Debiasing Multimodal Large Language Models

- **作者：** Pinlong Zhao, Zike Ding, Zengshu Ye, Zhou Zhaoting
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1843/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1843.pdf)
- **中文提要：** 多模态大语言模型常出现模态偏差，过度依赖某一模态而忽略其他模态中的关键信息。现有借助模态掩蔽的去偏方法，通过完全去掉整个模态来制造有偏回答，形成极端且静态的训练环境。
- **关键词：** preference-optimization, alignment

### Beyond Compromise: Pareto-Lenient Consensus for Efficient Multi-Preference LLM Alignment

- **作者：** Renxuan Tan, Rongpeng Li, Zhifeng Zhao, Honggang Zhang
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1879/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1879.pdf)
- **中文提要：** 让大语言模型对齐多样的人类价值，而不是只追随单一偏好，对稳健部署很关键。当前多目标偏好对齐主要依靠静态线性标量化或刚性梯度投影来处理这些权衡。
- **关键词：** preference-optimization, alignment

### Beyond Length Scaling: Synergizing Breadth and Depth for Generative Reward Models

- **作者：** Qiyuan Zhang, Yufei Wang, Tianhe Wu, Can Xu, Qingfeng Sun, Kai Zheng, Xue Liu, Chen Ma
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.709/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.709.pdf)
- **中文提要：** 生成式奖励模型的进展表明，拉长思维链能明显提高评估的可靠性。现有工作主要依赖无结构的长度扩展，忽略了不同推理机制效果并不相同：广度思维链覆盖多个原则维度，深度思维链则做实质性判断。
- **关键词：** RLVR, SFT, reward-model, alignment, fine-tuning

### Beyond Outcome Verification: Verifiable Process Reward Models for Structured Reasoning

- **作者：** Massimiliano Pronesti, Anya Belz, Yufang Hou
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1611/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1611.pdf)
- **中文提要：** 可验证奖励的强化学习表明，代码单测或数学精确匹配这类结果级验证信号就能明显改进大语言模型。过程监督长期被用来塑造中间推理行为，但现有做法依赖神经评判器。
- **关键词：** RLVR, PRM, reward-model

### Bridging SFT and RL: Dynamic Policy Optimization for Robust Reasoning

- **作者：** Taojie Zhu, Dongyang Xu, Ding Zou, Sen Zhao, Qiaobo Hao, Zhiguo Yang, Yonghong He
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.219/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.219.pdf)
- **中文提要：** 后训练中的 SFT 与强化学习面临根本两难：前者方差低、较稳定，但拟合偏差高；后者偏差低、便于探索，但梯度方差高。现有统一优化常常只用简单的损失加权，忽略了其中的统计问题。
- **关键词：** SFT, post-training, alignment, fine-tuning

### Can Post-Training Transform LLMs into Causal Reasoners?

- **作者：** Junqi Chen, Sirui Chen, Chaochao Lu
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.839/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.839.pdf)
- **中文提要：** 因果推断对决策不可或缺，对非专家却很难。大语言模型在这一方向有潜力，但其精确因果估计能力仍然有限，后训练对这些能力的影响也缺少探讨。
- **关键词：** GRPO, DPO, KTO, SFT, post-training

### Can Small LLMs Learn a Robust Theory of Mind via RLVR? Investigating Generalization through the False-Belief Task

- **作者：** Sneheel Sarangi, Hanan Salam
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.2061/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.2061.pdf)
- **中文提要：** 后训练阶段基于规则的强化学习，推动了大语言模型在复杂推理上的涌现能力。这引出一个问题：类似方法能否让模型形成更细腻、更接近人类的社会智能，例如心理理论。
- **关键词：** RLVR, post-training

### Carefully Considering Culture: Analyzing LLM Alignment in Single- and Multi-Cultural Settings using Cultural Consensus Theory

- **作者：** Krishna Pothugunta, John P. Lalor
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1323/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1323.pdf)
- **中文提要：** 自然语言处理中已有工作探测大语言模型对不同国家文化规范的理解。这类研究通常只看分布模式，忽略群体共识，也忽略一个国家内部可能存在的多元文化环境。
- **关键词：** alignment

### CE-RM: A Pointwise Generative Reward Model Optimized via Two-Stage Rollout and Unified Criteria

- **作者：** Xinyu Hu, Yancheng He, Weixun Wang, Tao Feng, Li Lin, Jiashun Liu, Wenbo Su, Bo Zheng, Xiaojun Wan
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.982/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.982.pdf)
- **中文提要：** 开放式自然语言生成的自动评估既关键又困难，尤其当基于规则的指标不可用时。相较传统方法，大模型即评判的范式能做更灵活的评估，也有望充当强化学习里的生成式奖励模型。
- **关键词：** reward-model

### CodeRM-NT: Reward Model for Code RL without Unit Tests

- **作者：** Xiao Xia, Dan Zhang, Tianrui Sun
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.2150/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.2150.pdf)
- **中文提要：** 为代码生成中的强化学习提供准确奖励信号是一大难点。现有方法依赖单元测试判断代码是否正确并给出奖励，而大规模获取并核验可靠的单元测试本身就很困难。
- **关键词：** reward-model

### CoMoL: Efficient Mixture of LoRA Experts via Dynamic Core Space Merging

- **作者：** Jie Cao, Zhenxuan Fan, Zhuonan Wang, Tianwei Lin, Ziyuan Zhao, Rolan Yan, Wenqiao Zhang, Feifei Shao, Hongwei Wang, Jun Xiao, Siliang Tang
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.811/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.811.pdf)
- **中文提要：** 借助 PEFT，大语言模型能应对多样的下游与领域任务。现有方法尤其是 MoE-LoRA，由于 LoRA 专家不断增多以及按实例路由，参数效率有限，适应粒度也偏粗。
- **关键词：** LoRA, PEFT, fine-tuning

### Context-Conditioned Masked LoRA: Dynamic Rank Routing for Compute-Efficient Parameter-Efficient Fine-Tuning

- **作者：** Rifat Rafiuddin, Rafae Abdullah
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1329/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1329.pdf)
- **中文提要：** LoRA 一类参数高效微调减少了可训练参数，但仍对每个词元施加稠密的低秩更新，秩一旦设定，适应的计算量就大体固定。CCM-LoRA 学习轻量路由器，按输入激活一部分 LoRA 秩方向，从而做成动态秩路由，并带来与上下文相关的稀疏。
- **关键词：** LoRA, PEFT, fine-tuning

### CPC-GRPO: Answer-Free Reinforcement Learning with Cross-Prompt Consensus Rewards

- **作者：** Gyunyeop Kim, Sangwoo Kang
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1486/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1486.pdf)
- **中文提要：** 带可验证奖励的强化学习提升了语言模型的推理，但通常需要标准答案或外部验证器，既限制适用面又增加成本。这里的无答案训练目标把提示复述当作同一意图的多个语义视角，仅从模型自身概率导出奖励。
- **关键词：** GRPO, alignment

### Curriculum-RLAIF: Curriculum Alignment with Reinforcement Learning from AI Feedback

- **作者：** Jiaye Lin, Mengdi Li, Xufeng Zhao, Wenhao Lu, Peilin Zhao, Stefan Wermter, Di Wang
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1685/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1685.pdf)
- **中文提要：** 通过 RLAIF 训练的奖励模型常常泛化不足，进而影响策略模型的对齐效果。其成因包括分布偏移、偏好标签噪声，以及过难样本与模型能力不匹配。
- **关键词：** RLAIF, reward-model, alignment

### DaMo: Data Mixing Optimizer in Fine-tuning Multimodal LLMs for Mobile Phone Agents

- **作者：** Kai Shi, Jun Yang, Ni Yang, Binqiang Pan, Qingsong Xie, Zhangchao, Zhenyu Yang, Tianhuang Su, Haonan Lu
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1439/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1439.pdf)
- **中文提要：** 手机智能体前景广阔，但作为其基础的多模态大模型在同时处理多项手机任务时仍然有限。
- **关键词：** SFT, fine-tuning

### Data-Centric Continual Pre-training for 500+ Languages: A New Bilingual Translation Corpus and Multilingual Models

- **作者：** Shaoxiong Ji, Zihao Li, Jaakko Paavola, Hengyu Luo, J{\"o}rg Tiedemann
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.937/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.937.pdf)
- **中文提要：** 大规模多语言持续预训练中，要不要加入平行数据是一项关键选择。该研究考察双语翻译数据如何影响 Llama 系列模型的多语言适应。
- **关键词：** continued-pretraining

### Data Selection for Multi-turn Dialogue Instruction Tuning

- **作者：** Bo Li, Shikun Zhang, Wei Ye
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.130/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.130.pdf)
- **中文提要：** 多轮对话指令语料常常嘈杂且结构不一，表现为话题漂移、重复闲聊和各轮答案格式不匹配。MDS 在对话层面为整段会话打分，以此做数据筛选。
- **关键词：** instruction-tuning, alignment

### Detecting Proxy Gaming in RL and LLM Alignment via Evaluator Stress Tests

- **作者：** Sanjeda Akter, Ibne Farabi Shihab, Anuj Sharma
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.513/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.513.pdf)
- **中文提要：** 代理优化会使系统利用评估器的弱点，而不是改进原本目标，强化学习中的奖励黑客和语言模型对齐里的评估博弈都面临这一风险。评估器压力测试（EST）基于不变性，把格式、物理缺陷等可利用的敏感性与内容驱动的改进区分开，用来发现代理博弈。
- **关键词：** alignment

### Disambiguation-Centric Finetuning Makes Enterprise Tool-Calling LLMs More Realistic and Less Risky

- **作者：** Ashutosh Hathidara, Julien Yu, Sebastian Schreiber
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.469/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.469.pdf)
- **中文提要：** 企业 API 调用中，近义工具争夺同一用户意图，或必要参数说明不足时，模型经常出错。DiaFORGE 以消歧为核心，用分阶段流程处理对话中的自然回应生成与评测。
- **关键词：** SFT, fine-tuning

### Disentangling Continued Pre-Training: Attention-Driven Routing and Semantic Hub Preservation in Language Adaptation

- **作者：** Khanh-Tung Tran, Vinh-Khanh Tran, Barry O{'}Sullivan, Hoang D. Nguyen
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1218/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1218.pdf)
- **中文提要：** 持续预训练让大模型获得第二语言能力，背后的机制却仍不清楚。这里考察这种预训练如何在不同语系、文字、模型规模和架构上改写模型表征。
- **关键词：** continued-pretraining

### DPLoRA: A Dual-Pruning Framework based on ILP Optimization and Progressive Pruning for Parameter-Efficient LoRA Fine-Tuning

- **作者：** Changjun Park, Sejong Yoon, Jaekwang Kim
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1693/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1693.pdf)
- **中文提要：** DPLoRA 为 LoRA 分配秩时先做一次剪枝、训练中再做一次：OPLoRA 借助整数线性规划确定各层秩，无需手工调节；随后按平滑后的重要性分数自适应地继续降秩。
- **关键词：** instruction-following, LoRA, PEFT, fine-tuning

### DRA-GRPO: Your GRPO Needs to Know Diverse Reasoning Paths for Mathematical Reasoning

- **作者：** Xiwen Chen, Wenhui Zhu, Peijie Qiu, Xuanzhao Dong, Hao Wang, Haiyu Wu, Huayu Li, Aris Sotiras, Yalin Wang, Abolfazl Razi
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.685/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.685.pdf)
- **中文提要：** 以 GRPO 做数学推理后训练时，标准奖励是标量正确性，对语义内容并不单射：不同的推理路径会拿到完全相同的奖励。
- **关键词：** GRPO, post-training, alignment

### DRIFT: Transferring Reasoning Priors for Efficient MLLM Fine-Tuning

- **作者：** Chao Huang, Zeliang Zhang, Jiang Liu, Ximeng Sun, Jialian Wu, Xiaodong Yu, Ze Wang, Chenliang Xu, Emad Barsoum, Zicheng Liu
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1015/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1015.pdf)
- **中文提要：** 多模态大模型的推理能力往往落后于强大的纯文本模型。缩小这一差距通常需要大规模多模态推理数据或强化学习，成本很高。
- **关键词：** SFT, alignment, fine-tuning

### DynamicFocalPO: Adaptive Focusing Strategy for Preference Optimization

- **作者：** Shu Zhou, Junan Chen, Rui Ling, Xin Wang, Tao Fan, Hao Wang
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1009/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1009.pdf)
- **中文提要：** 对齐人类偏好时，DPO 一类偏好优化已经很常见。FocalPO 在 DPO 上增加调节因子，压低那些排序错误的偏好对的权重。
- **关键词：** DPO, preference-optimization, alignment

### DynamixSFT: Dynamic Mixture Optimization of Instruction Tuning Collections

- **作者：** Haebin Shin, Lei Ji, Xiao Liu, Zhiwei Yu, Hyunwoo Yoo, Qi Chen, Yeyun Gong
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1972/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1972.pdf)
- **中文提要：** 指令微调数据集不断出现，动态平衡并优化其混合成为关键问题。DynamixSFT 提供一套动态、自动化的混合优化方法。
- **关键词：** instruction-tuning

### Empirical Analysis of Task Mixture Effects in Small-scale Instruction Tuning: A Statistical Approach

- **作者：** Jeesu Jung, Sangkeun Jung
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.643/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.643.pdf)
- **中文提要：** 大模型表现高度依赖指令微调中的任务类型和混合比例。以往多按固定比例混合，缺少对多样任务之间相互作用的系统定量分析，于是从统计角度考察这种相互作用。
- **关键词：** instruction-tuning

### Empowering Reliable Visual-Centric Instruction Following in MLLMs

- **作者：** Weilei He, Feng Ju, Zhiyuan Fan, Rui Min, Minhao Cheng
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.461/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.461.pdf)
- **中文提要：** 评估多模态大模型的指令遵循，本应检验输出是否忠实于用户意图。现有基准却主要覆盖文本模态中的言语指令。
- **关键词：** instruction-following, fine-tuning

### EMTIR-GRPO: Efficient Multi-Tool Augmented Large Language Models via Reinforcement Learning

- **作者：** Shixin Jiang, Zhihao Zhu, Jiafeng Liang, Yang Wu, Ming Liu, Bing Qin
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1388/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1388.pdf)
- **中文提要：** 工具集成推理让模型借助外部工具完成自身能力之外的任务，但容易过度调用工具。已有模仿学习或奖励塑形多针对单工具，也忽略多工具推理里不同工具的调用成本，因而需要面向这些缺口的新方法。
- **关键词：** GRPO

### Evian: Towards Explainable Visual Instruction-tuning Data Auditing

- **作者：** Zimu Jia, Mingjie Xu, Andrew Estornell, Jiaheng Wei
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.311/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.311.pdf)
- **中文提要：** 视觉语言模型既要视觉保真，也要会遵循指令，训练数据的质量因此至关重要。现有数据质量参差，过滤方法又依赖粗粒度分数，难以识别逻辑谬误这类细微语义问题。
- **关键词：** instruction-tuning, instruction-following, fine-tuning

### Exploring Reasoning Reward Model for Agents

- **作者：** Kaixuan Fan, Kaituo Feng, Manyuan Zhang, Tianshuo Peng, Zhixun Li, Yilei Jiang, Shuang Chen, Xiangyu Yue
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.95/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.95.pdf)
- **中文提要：** 智能体强化学习已经能驱动复杂推理和工具使用。多数方法训练时仍依赖稀疏的、只看最终结果的奖励。
- **关键词：** reward-model

### Exploring Two-Phase Continual Instruction Fine-tuning for Multilingual Adaptation in Large Language Models

- **作者：** Divyanshu Aggarwal, Sankarshan Damle, Navin Goyal, Satya Lokam, Sunayana Sitaram
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1595/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1595.pdf)
- **中文提要：** 持续提升多语言指令遵循时，不能损害模型已经擅长的语言，英语通常属于这类语言。研究采用分阶段的持续微调（CFT），以改善多语言适应。
- **关键词：** instruction-following, fine-tuning

### FARSS: Fisher-Optimized Adaptive Low-Rank and Singular-Vector Selection for Knowledge-Preserving Fine-Tuning

- **作者：** Renxing Chen, Ziwei Xiang, Peisong Wang, Hongjian Fang, Meng Li, Fanhu Zeng, Yanan Zhu, Peipei Yang, Xu-Yao Zhang, Jian Cheng
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.883/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.883.pdf)
- **中文提要：** 参数高效微调广泛用于适配大模型，低秩适应却面临固有权衡：提升目标任务可能损害预训练中的世界知识，过度约束更新以保住知识又会妨碍任务改进。
- **关键词：** LoRA, PEFT, fine-tuning

### Federated LoRA Fine-Tuning with Pipelined Error-Mitigated Aggregation and Matrix-Wise Freezing

- **作者：** Haoran Wang, Xiong Wang, Yuqing Li, Jing Chen, Junyi Zhang, Nan Yan, Kun He, Wei Wang
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.284/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.284.pdf)
- **中文提要：** 联邦 LoRA 允许多个客户端在不泄露原始数据的情况下协同微调大模型。现有做法常因有偏的模型聚合而出现性能下降，通信和计算负担也限制了训练效率。
- **关键词：** LoRA, fine-tuning

### Fine-Grained Data Ordering Improves Fine-Tuning for Large Language Models

- **作者：** Xiaomeng Hu, Yixuan Tang, Haoze Li, Hao Chen, Qi Zhang, Zhanming Shen, Yiming Zhang, Haobo Wang, Junbo Zhao
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1021/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1021.pdf)
- **中文提要：** 通过微调把通用模型对齐到下游任务，已成为研究重点。只选用高质量样本训练，是提升微调效果的有效途径之一。
- **关键词：** SFT, continued-pretraining, alignment, fine-tuning

### From Coarse to Fine: Benchmarking and Reward Modeling for Writing-Centric Generation Tasks

- **作者：** Qingyu Ren, Tianjun Pan, Xingzhou Chen, Xuhong Wang
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.134/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.134.pdf)
- **中文提要：** 大模型的文本生成进步明显，生成式写作仍然吃力。评测方面，现有基准包含的要求类型很少，写作奖励模型也尚未被评估。
- **关键词：** RLVR, reward-model

### From Fragments to Facts: A Curriculum-Driven DPO Approach for Generating Hindi News Veracity Explanations

- **作者：** Pulkit Bansal, Raghvendra Kumar, Shakti Singh, Adam Jatowt, Sriparna Saha
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.2108/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.2108.pdf)
- **中文提要：** 在虚假信息泛滥的环境里，生成可靠的新闻解释至关重要，印地语这类代表性不足的语言尤其如此。缺少稳健的自动化工具，印地语的虚假信息检测难以扩展。
- **关键词：** DPO, preference-optimization

### From Scores to Preferences: Redefining Evaluation Paradigm for Speech Quality Reward Modeling

- **作者：** Yifei Cao, Changhao Jiang, Jiabao Zhuang, Jiajun Sun, Ming Zhang, Zhiheng Xi, Hui Li, Shihan Dou, Yuran Wang, Yunke Zhang, Tao Ji, Tao Gui, Qi Zhang, Xuanjing Huang
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1638/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1638.pdf)
- **中文提要：** 语音质量评估通常依据主观评分做分数回归，标准本身不一致，也妨碍跨数据集的训练和评测。这里改成基于偏好的比较，并构建由平均意见分派生的偏好数据集 MOS-Pref。
- **关键词：** reward-model

### GanitLLM: Difficulty-Aware Bengali Mathematical Reasoning through Curriculum-GRPO

- **作者：** Shubhashis Roy Dipta, Khairul Mahbub, Nadia Najjar
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1995/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1995.pdf)
- **中文提要：** GanitLLM 是面向孟加拉语数学推理的模型，并配套难度感知的孟加拉语数学语料和基于课程的 GRPO。现有模型却往往先用英语推理再翻译，或在多步孟加拉语数学上失败。
- **关键词：** GRPO, SFT

### Generalizable LLM Learning of Graph Synthetic Data with Post-training Alignment

- **作者：** Yizhuo Zhang, Heng Wang, Shangbin Feng, Zhaoxuan Tan, Xinyun Liu, Yulia Tsvetkov
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.586/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.586.pdf)
- **中文提要：** 先前工作用合成图数据做监督微调，让模型更擅长图算法题。真正需要的是从合成图泛化到带隐含图结构的真实任务，而不是让模型去算最短路。
- **关键词：** GRPO, DPO, SFT, post-training, alignment, fine-tuning

### GFT: From Imitation to Reward Fine-Tuning with Unbiased Group Advantages and Dynamic Coefficient Rectification

- **作者：** Wangjie Gan, Miao Pan, Linbo Xi, Wenqi Zhang, Jintao Chen, Jianwei Yin, Xuhong Zhang
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1444/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1444.pdf)
- **中文提要：** 大模型后训练通常采用 SFT 和强化学习，但要把高效的知识注入和稳健泛化统一起来仍然困难。训练动态分析表明，SFT 可以看成策略梯度的特例，其隐式奖励极度稀疏且不稳定。
- **关键词：** SFT, post-training, fine-tuning

### G-LoRA: Global-Local Decoupled Low-Rank Adaptation

- **作者：** Jiahao Xiong, Yihong Huang, Yihe Liu, Xianming Hu, Hongbo Zhao, Kai Zhang
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1005/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1005.pdf)
- **中文提要：** LoRA 改善了大模型微调的效率与下游表现。不同权重更新矩阵的重要性不同、因而应分配不同的秩，这一点已被注意到，但同一更新矩阵内部的参数仍通常共用一个秩。
- **关键词：** LoRA, fine-tuning

### Graph-GRPO: Stabilizing Multi-Agent Topology Learning via Group Relative Policy Optimization

- **作者：** Yueyang Cang, Xiaoteng Zhang, Erlu Zhao, Zehua Ji, Yuhang Liu, Yuchen He, Zhiyuan Ning, Chen Yijun, Wenge Que, Li Shi
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1010/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1010.pdf)
- **中文提要：** 通信拓扑直接影响基于大模型的多智能体系统是否高效。近期方法用强化学习按任务动态建图，但通常依赖单样本策略梯度和绝对奖励，例如只看对错。
- **关键词：** GRPO

### GROLE: Instance-Level Group Relative Optimization for LoRA Experts in Incremental Learning

- **作者：** Yongyi Liao, Wencan Lai, Jun Fang, Jinjin Guo, Xiaohui Zhang, Zhiyuan Liu, Chao Liu, Pengzhang Liu, Qixia Jiang
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1952/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1952.pdf)
- **中文提要：** 大模型零样本泛化很强，但要适应下游任务或数据分布变化，往往得持续微调，这容易造成灾难性遗忘，知识也难迁移。在线增量学习中任务边界模糊、数据不断到来，困难更为突出。
- **关键词：** GRPO, LoRA, fine-tuning

### GRPO-CARE: Consistency-Aware Reinforcement Learning for Multimodal Reasoning

- **作者：** Yi Chen, Yuying Ge, Rui Wang, Yixiao Ge, Junhao Cheng, Ying Shan, Xihui Liu
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.210/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.210.pdf)
- **中文提要：** 结果监督的 GRPO 等强化学习推进了语言模型推理，迁到多模态大模型仍探索不足。进展还受限于缺少能在受控泛化条件下同时检验感知与推理的评测设置。
- **关键词：** GRPO

### Hail to the Thief: Exploring Attacks and Defenses in Decentralised GRPO

- **作者：** Nikolay Blagoev, Oguzhan Ersoy, Lydia Chen
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1950/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1950.pdf)
- **中文提要：** GRPO 在大模型后训练中已被广泛采用。模型先回答提示，再经由强化学习习得偏好行为。
- **关键词：** GRPO, post-training

### Hebbian-Guided Bi-Directional Rank Adaptation for Parameter-Efficient Fine-Tuning

- **作者：** Xing Zhao, Liu Yang, Xi-Le Zhao, Yueqi Yang, Tianqi Jiang
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.954/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.954.pdf)
- **中文提要：** LoRA 被广泛用于微调大模型，能大幅降低计算和存储成本。固定秩设计却难以刻画不同层重要性的差异，灵活性不足。
- **关键词：** QLoRA, LoRA, PEFT, fine-tuning

### HiCoLoRA: Addressing Context-Prompt Misalignment via Hierarchical Collaborative LoRA for Zero-Shot DST

- **作者：** Shuyu Zhang, Yifan Wei, Xinru Wang, Yanmin Zhu, Yangfan He, Yixuan Weng, Yujie Liu, Bin Li
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1876/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1876.pdf)
- **中文提要：** 零样本对话状态跟踪让任务型对话系统无需昂贵标注就能进入新领域。动态对话上下文与静态提示的语义错位，会导致跨层协调不灵活、领域相互干扰以及灾难性遗忘。
- **关键词：** LoRA, alignment

### HyperAdaLoRA: Accelerating LoRA Rank Allocation During Training via Hypernetworks without Sacrificing Performance

- **作者：** Hao Zhang, Zhenjia Li, Yifan Gao, Xi Xiao, Heng Zhang, Shuyang Zhang, Xiaoxincc, Bo Huang, Yuhang Wu, Tianyang Wang, Hao Xu
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1648/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1648.pdf)
- **中文提要：** 以 LoRA 为代表的参数高效微调，在降低计算和显存开销的同时适配大模型。它假定每个增量矩阵使用统一的秩，没有考虑不同模块、不同层中权重矩阵的重要性差别。
- **关键词：** LoRA, PEFT, fine-tuning

### Intrinsic Mutual Information as a Modulator for Preference Optimization

- **作者：** Peng Liao, Peijia Zheng, Lingbo Li, Shangsong Liang, Lin Chen
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.185/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.185.pdf)
- **中文提要：** DPO 等离线偏好优化在对齐人类价值时有明显优势。要把效果调到较优，通常还要额外搜索超参数，时间开销因此很大。
- **关键词：** DPO, preference-optimization, alignment

### Joint Optimization of Training Data and Policy in RLHF

- **作者：** Zhuohao Yu, Jiali Zeng, Weizheng Gu, Mengyuan Sun, Yidong Wang, Fandong Meng, Jie Zhou, Shikun Zhang, Wei Ye
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.2109/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.2109.pdf)
- **中文提要：** 传统 RLHF 在固定的训练输入上优化策略，学习信号的多样性有限。JODP 让正在演化的策略模型生成改进后的训练问题变体，从而联合优化数据与策略。
- **关键词：** GRPO, RLHF, alignment

### Large-Scale Diverse Synthesis for Mid-Training

- **作者：** Xuemiao Zhang, Chengying Tu, Can Ren, Rongxiang Weng, Hongfei Yan, Jingang Wang, Xunliang Cai
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.814/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.814.pdf)
- **中文提要：** 中期训练对提升大模型的知识与推理日益重要，尤其依赖大规模合成数据。现有合成方法却常常产生简单、同质的问答对，规模和多样性都有限。
- **关键词：** mid-training

### Learning Temporally-Aware Sample Weights for Preference Optimization

- **作者：** Mengyang Li, Xudong Zhou, Pinlong Zhao
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.601/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.601.pdf)
- **中文提要：** 偏好优化是对齐大模型的基础环节。现有样本加权多是瞬时模型状态的静态函数，忽略了学习过程随时间变化的动态。
- **关键词：** preference-optimization, alignment

### LoRE: Enhancing Search Relevance with Progressive Chain-of-Thought and Preference Alignment

- **作者：** Chenji Lu, Zhuo Chen, Hui Zhao, Zhiyuan Zeng, Gang Zhao, Junjie Ren, Lihaoran, Songyan Liu, Pengjie Wang, Chuan Yu, Jian Xu, Bo Zheng
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1536/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1536.pdf)
- **中文提要：** 电商搜索的相关性判断很关键，由大模型驱动的思维链已成为主流并带来明显收益。全面的相关性推理仍缺少系统定义，现有方法因此存在显著盲区。
- **关键词：** SFT, preference-optimization, post-training, alignment

### LPO: Towards Accurate GUI Agent Interaction via Location Preference Optimization

- **作者：** Jiaqi Tang, Yu Xia, Yi-Feng Wu, Yuwei Hu, Chen Yuhui, Qing-Guo Chen, Xiaogang Xu, Xiangyu Wu, Hao LU, Yanqing Ma, Shiyin Lu, Qifeng Chen
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.718/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.718.pdf)
- **中文提要：** 自主智能体借助自然语言改变了人与图形界面的交互方式。当前图形界面智能体的空间定位主要靠 SFT，但对位置信息的感知能力有限。
- **关键词：** GRPO, SFT, preference-optimization, fine-tuning

### LUNE: Efficient LLM Unlearning via LoRA Fine-Tuning with Negative Examples

- **作者：** Yezi Liu, Hanning Chen, Wenjun Huang, Yang Ni, Mohsen Imani
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.816/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.816.pdf)
- **中文提要：** 大模型编码了大量事实，却难以有选择地遗忘特定信息，这妨碍隐私保护、偏见缓解和部署后的纠正。LUNE 只更新低秩适配器并冻结主干，仅用负例做遗忘，从而把修改局限在局部。
- **关键词：** LoRA, fine-tuning

### MEAV: Model Editing with Alignment Vectors for inference time LLM alignment in single and multidomain preference spectrum

- **作者：** Sadat Shahriar, Zheng Qi, Nikolaos Pappas, Srikanth Doss, Kishaloy Halder, Monica Sunkara, Manuel Mager, Yassine Benajiba
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.2035/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.2035.pdf)
- **中文提要：** 按主观性和细微的偏好程度对齐模型，需要足够的灵活性与控制，过程往往耗费资源和时间。训练期对齐一有变动就得全部重训，推理期方法则通常每一步都要访问奖励模型。
- **关键词：** preference-optimization, reward-model, alignment, fine-tuning

### Meeseeks: A Feedback-Driven, Iterative Self-Correction Benchmark evaluating LLMs' Instruction Following Capability

- **作者：** Jiaming Wang, Yunke Zhao, Peng Ding, Jun Kuang, Yibin Shen, Zhe Tang, Yilin Jin, ZongYu Wang, Xiaoyu Li, Xuezhi Cao
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.725/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.725.pdf)
- **中文提要：** 严格遵守指令，是大模型在真实场景中充当可靠智能体的基础。面对复杂提示，模型经常无法在单次回复中满足全部规定要求。
- **关键词：** instruction-following

### MergeIT: From Selection to Merging for Efficient Instruction Tuning

- **作者：** Hongyi Cai, Yuqian Fu, Hongming Fu, Bo Zhao
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.46/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.46.pdf)
- **中文提要：** 指令数据的质量与多样性会显著影响大模型表现，指令微调因此十分关键。这也凸显出有效且高效的数据选择策略的重要性。
- **关键词：** instruction-tuning

### MMR-GRPO: Accelerating GRPO-Style Training through Diversity-Aware Reward Reweighting

- **作者：** Kangda Wei, Ruihong Huang
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.467/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.467.pdf)
- **中文提要：** GRPO 已成为训练数学推理模型的常用方法，但训练计算密集、耗时长，对算力预算有限的研究者和小型机构形成障碍。MMR-GRPO 被提出来加速 GRPO 式训练。
- **关键词：** GRPO

### MulDimIF: A Multi-Dimensional Constraint Framework for Evaluating and Improving Instruction Following in Large Language Models

- **作者：** Junjie Ye, Caishuang Huang, Zhuohan Chen, Wenjie Fu, Chenyuan Yang, Leyi Yang, Yilong Wu, Peng Wang, Meng Zhou, Xiaolong Yang, Tao Gui, Qi Zhang, Zhongchao Shi, Jianping Fan, Xuanjing Huang
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.99/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.99.pdf)
- **中文提要：** 指令遵循是指模型的输出要满足全部指定约束。已有工作主要按约束类别讨论，评测维度有限，也很少指导如何提升这种能力。
- **关键词：** instruction-following

### Multi-Faceted Self-Consistent Preference Alignment for Query Rewriting in Conversational Search

- **作者：** Zhiyu Cao, Peifeng Li, Qiaoming Zhu
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.638/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.638.pdf)
- **中文提要：** 对话查询改写旨在改写含糊查询，使对话搜索更有效。早期研究多孤立地做改写，忽略了改写、段落检索和回答生成所提供的反馈。
- **关键词：** DPO, preference-optimization, alignment

### N-GRPO: Embedding-Level Neighbor Mixing for Enhanced Policy Optimization

- **作者：** Xukun Zhu, Hang Yu, Peng Di, Linchao Zhu
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1443/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1443.pdf)
- **中文提要：** 大模型在数学推理上的成功，很大程度上依赖 rollout 阶段产生多样且有效的解题路径。词元级采样往往只得到措辞不同的冗余轨迹，而用随机噪声的嵌入级方法又常常破坏语义一致性。
- **关键词：** GRPO

### On the Editability of Delta Parameters in Post-Trained Models

- **作者：** Qiaoyu Tang, Le Yu, Bowen Yu, Hongyu Lin, Keming Lu, Yaojie Lu, Xianpei Han, Le Sun
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1833/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1833.pdf)
- **中文提要：** 后训练把大规模预训练模型适配到各种任务，其效果完全体现在 delta 参数上，即后训练与预训练参数之差。已有研究通过剪枝、量化、低秩近似和外推考察这些参数的性质。
- **关键词：** post-training

### On the Representation Geometry of LoRA Model Merging

- **作者：** Chenyang Lu, Jiaru Li, Jinman Zhao, Xinran Chen, Yining Wang, Renyi Cai, Yuchen Li, Chao He
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.261/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.261.pdf)
- **中文提要：** LoRA 广泛用于参数高效微调，但把多个任务专属更新在不再训练的情况下合并仍然困难。现有合并大多依赖基于 SVD 的对齐，强调跨任务的全局共享结构。
- **关键词：** LoRA, PEFT, alignment, fine-tuning

### OpenGenAlign: A Preference Dataset and Benchmark for Trustworthy Reward Modeling in Open-Ended, Long-Context Generation

- **作者：** Hanning Zhang, Juntong Song, Juno Zhu, Yuanhao Wu, Tong Zhang, Cheng Niu
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.553/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.553.pdf)
- **中文提要：** 奖励建模对评价和改进大模型生成至关重要。这类模型通常在高质量标注数据上训练，用来区分更好和更差的回答。
- **关键词：** instruction-following, reward-model

### Optimizing Conversational Quality in Spoken Dialogue Systems with Reinforcement Learning from AI Feedback

- **作者：** Siddhant Arora, Jinchuan Tian, Jiatong Shi, Hayato Futami, Yosuke Kashiwagi, Emiru Tsunoo, Shinji Watanabe
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.2040/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.2040.pdf)
- **中文提要：** 面向语音输入、语音输出对话系统的 RLHF 与 RLAIF 仍较少被研究，先前工作多在话语层面使用单一语义奖励。这样的设置忽略了对话质量的多维和多模态特性，其中包含语义连贯、音频自然度、说话人一致性与情绪对齐等。
- **关键词：** DPO, RLHF, RLAIF, alignment

### Orchestrating Tokens and Sequences: Dynamic Hybrid Policy Optimization for RLVR

- **作者：** Zijun Min, Bingshuai Liu, Ante Wang, Long Zhang, Anxiang Zeng, Haibo Zhang, Jinsong Su
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1883/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1883.pdf)
- **中文提要：** 带可验证奖励的强化学习为优化大模型的推理任务提供了框架。现有算法关注的粒度并不相同，各自的长处和局限可以互补。
- **关键词：** GRPO, RLVR

### Parallel-SFT: Improving Zero-Shot Cross-Programming-Language Transfer for Code RL

- **作者：** Zhaofeng Wu, Shiqi Wang, Boya Peng, Anuj Kumar Goyal, Melanie Kambadur, Sebastian Ruder, Yoon Kim, Chloe Bi
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1324/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1324.pdf)
- **中文提要：** 现有语言模型在 C++、Python 等常见编程语言上表现突出，低资源语言则常受训练数据不足的限制。多数编程技能跨语言通用，在一种语言上学到的能力应当能够迁移。
- **关键词：** SFT

### PERM: Psychology-grounded Empathetic Reward Modeling for Large Language Models

- **作者：** Chengbing Wang, Wuqiang Zheng, Yang Zhang, Fengbin Zhu, Junyi Cheng, Yi Xie, Wenjie Wang, Fuli Feng
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.363/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.363.pdf)
- **中文提要：** 大模型越来越多地用于以人为中心的场景，却常常给不出有实质内容的情感支持。强化学习已被用来增强共情，但现有奖励模型多从单一视角打分，忽略了支持者与求助者之间双向的共情互动。
- **关键词：** reward-model

### PhysPRM: A Generative Process Reward Model with Fine-grained Diagnosis for Physics Problem Solving

- **作者：** Yuxuan Dong, Xinyu Zhang, Lingling Zhang, Han Lai, Pengyu Li, Bifan Wei, Yaqiang Wu, Jun Liu
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.458/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.458.pdf)
- **中文提要：** 大模型在抽象推理上进步显著，解物理题时仍难以解读隐含约束并维持物理一致性。过程奖励模型为此被用来检验中间推理步骤。
- **关键词：** GRPO, SFT, PRM, reward-model, fine-tuning

### PO-KGQA: Preference Optimization for Low-Resource Complex Knowledge Graph Question Answering

- **作者：** Prerna Agarwal, Ayushman Kumar Singh, Srikanta Bedathur
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.2083/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.2083.pdf)
- **中文提要：** 低资源、基于上下文学习的知识图谱问答，严重依赖大模型把自然语言问题转换成 SPARQL、KoPL 等逻辑形式。近期一些对齐技术已经能够对语言模型做基于指令的微调。
- **关键词：** preference-optimization, alignment, fine-tuning

### Polynomial Expansion Rank Adaptation: Enhancing Low-Rank Fine-Tuning with High-Order Interactions

- **作者：** Wenhao Zhang, Lin Mu, Li Ni, Peiquan Jin, Yiwen Zhang
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.650/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.650.pdf)
- **中文提要：** LoRA 的严格线性结构限制了表达能力，权重更新的双线性形式只捕捉低秩因子之间的一阶依赖，难以建模非线性与高阶参数交互。由此提出用多项式展开来增强低秩微调。
- **关键词：** LoRA, fine-tuning

### Position: From Noise to Signal to Selbstzweck - Reframing Human Label Variation in the Era of Post-training in NLP

- **作者：** Shanshan Xu, Santosh T.Y.S.S, Barbara Plank
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1190/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1190.pdf)
- **中文提要：** 人类标注分歧是合理的意见不一致，反映的是视角多样，而不只是标注错误。自然语言处理长期把它当作应被消除的噪声，直到最近才重新理解为有助于提升模型稳健性的信号。
- **关键词：** post-training, alignment

### Preference Optimization for Review Question Generation Improves Writing Quality

- **作者：** Karun Sharma, Vidushee Vats, Shengzhi LI, Yuxiang Wang, Zhongtian Sun, Prayag Tiwari
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1256/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1256.pdf)
- **中文提要：** 同行评审依赖有实质内容、基于证据的提问，但当前大模型生成的问题偏于表面，在专家评估中不如人类审稿人的问题。作者从 OpenReview 整理审稿问题，并让专家从投入程度、证据和依据等方面对问题与论文的配对做偏好标注。
- **关键词：** SFT, preference-optimization, reward-model

### ProFit: Leveraging High-Value Signals in SFT via Probability-Guided Token Selection

- **作者：** Tao Liu, Taiqiang Wu, Runming Yang, Shaoning Sun, Junjie Wang, Yujiu Yang
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.755/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.755.pdf)
- **中文提要：** 监督微调常把大模型硬对齐到单一参考答案，忽视语言的一对多特性，从而过拟合非核心表述。ProFit 在 SFT 中按概率引导选择词元，以便利用更高价值的信号。
- **关键词：** SFT, post-training, alignment, fine-tuning

### RanLoRA: Residual-aware Nonlinear Low-Rank Adaptation

- **作者：** Xu Luo, Yongbin Liu, Chunping Ouyang, Ying Yu
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.852/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.852.pdf)
- **中文提要：** LoRA 虽能以少量可训练参数适配大语言模型，但线性低秩投影把适应限制在线性子空间，复杂下游任务上的灵活性不足。RanLoRA 提出残差感知的非线性低秩适应，以放宽这一限制。
- **关键词：** LoRA, PEFT, alignment, fine-tuning

### Reasoning-Guided Exploration for Online DPO

- **作者：** Zetian Hu, Shunyu Liu, Ting-En Lin, Fei Huang, Yongbin Li, Dacheng Tao
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1370/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1370.pdf)
- **中文提要：** 旨在增强推理的已有方法，往往只适用于答案可以客观核验的领域。RGE-DPO 提出一种自博弈框架，把推理引导的探索用于在线 DPO，以改进通用领域数据上的推理。
- **关键词：** DPO, instruction-following, reward-model, self-rewarding

### Reason Only When Needed: Efficient Generative Reward Modeling via Model-Internal Uncertainty

- **作者：** Chao Xue, Yao Wang, Mengqiao Liu, Di Liang, Xingsheng Han, Peiyang Liu, Xianjie Wu, Chenyao Lu, Lei Jiang, Yu Lu, Haibo Shi, Shuang Liang, Minlong Peng, Flora D. Salim
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1167/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1167.pdf)
- **中文提要：** 生成式奖励模型借助思维链提示来增强大语言模型的推理，现有实现却仍有关键局限。该方向主张只在需要时才推理，并利用模型内部不确定性来提高生成式奖励建模的效率。
- **关键词：** reward-model

### Reinforcement Learning with Semantic Rewards Enables Low-Resource Language Expansion without Alignment Tax

- **作者：** Zeli Su, Ziyin Zhang, Zhou Liu, Xuexian Song, Zhankai Xu, Longfei Zheng, Xiaolu Zhang, Rong Fu, Guixian Xu, Wentao Zhang
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.880/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.880.pdf)
- **中文提要：** 把大语言模型扩展到低资源语言时，目标语言的提升常以通用能力的灾难性遗忘为代价，形成所谓对齐税。作者认为这种取舍来自 SFT 的刚性：它在狭窄且有偏的数据分布上强制进行词元级表层模仿。
- **关键词：** GRPO, SFT, alignment, fine-tuning

### Rethinking Multiple-Choice Questions for RLVR: Unlocking Potential via Distractor Design

- **作者：** Xu Guo, Qiming Ge, Jian Tong, Kedi Chen, Jin Zhang, Xiaogui Yang, Xuan Gao, Haijun Lv, Zhihui Lu, Yicheng Zou, Qipeng Guo
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1003/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1003.pdf)
- **中文提要：** 可验证奖励强化学习能加强大模型推理；选择题虽提供可扩展的可验证数据，却可能诱发奖励投机，让模型靠随机猜测或简单排除走捷径。作者重新审视这类题目，并把干扰项设计作为释放其潜力的途径。
- **关键词：** RLVR

### Rethinking Parameter Sharing for LLM Fine-Tuning with Multiple LoRAs

- **作者：** Hao Ban, Kaiyi Ji
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.625/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.625.pdf)
- **中文提要：** 多 LoRA 微调中，已有研究认为内层 A 矩阵在训练时高度相似，因而适合共享。这项工作重新考察大语言模型微调里这种参数共享是否妥当。
- **关键词：** LoRA, PEFT, fine-tuning

### Reverse Constitutional AI: A Framework for Controllable Toxic Data Generation via Probability-Clamped RLAIF

- **作者：** Yuan Fang, Yiming Luo, Aimin Zhou, Fei Tan
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.949/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.949.pdf)
- **中文提要：** 大模型安全依赖扎实的红队测试，但高质量有毒数据的系统化合成仍不充分。R-CAI 提出一套自动化、可控的对抗数据生成框架，希望超出零散越狱提示的做法。
- **关键词：** RLAIF

### Revisiting Self-Play Preference Optimization: On the Role of Prompt Difficulty

- **作者：** Yao Xiao, Jung-jae Kim, Roy Ka-Wei Lee, Lidong Bing
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.144/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.144.pdf)
- **中文提要：** 自博弈偏好优化通常让语言模型为提示生成同策略回答，再由奖励模型选出偏好与拒绝样本，并可用 DPO 继续训练。该研究回看这一范式，着重讨论提示难度所起的作用。
- **关键词：** DPO, preference-optimization, reward-model, alignment

### RIFT: Repurposing Negative Samples via Reward-Informed Fine-Tuning

- **作者：** Zehua Liu, Shuqi Liu, Tao Zhong, Mingxuan Yuan
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.706/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.706.pdf)
- **中文提要：** SFT 依赖昂贵的专家数据，拒绝采样微调又会丢掉有价值的负样本，数据利用因此不足。RIFT 用奖励知情的微调把模型自行生成的样本都利用起来。
- **关键词：** RFT, SFT, alignment, fine-tuning

### RLHS: Mitigating Misalignment in RLHF with Hindsight Simulation

- **作者：** Kaiqu Liang, Haimin Hu, Ryan Liu, Thomas L. Griffiths, Jaime Fern{\'a}ndez Fisac
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.556/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.556.pdf)
- **中文提要：** 经验表明 RLHF 在对齐生成式模型的同时，也可能造成严重且系统性的错位。作者猜想，评估反馈依赖可被模型输出影响的下游结果预测，从而诱发古德哈特定律式的动态，并据此用后见模拟加以缓解。
- **关键词：** DPO, RLHF, alignment, fine-tuning

### S2H-DPO: Hardness-Aware Preference Optimization for Vision--Language Models

- **作者：** Nitish Shukla, Surgan Jandial, Arun Ross
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1825/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1825.pdf)
- **中文提要：** 视觉语言模型的单图理解已有明显进展，跨多图推理仍然困难。现有多图对齐主要做带预设图像序号的局部推理，从而绕开全局视觉层面的必要能力。
- **关键词：** DPO, preference-optimization, alignment

### Safety Is Not Universal: The Selective Safety Trap in LLM Alignment

- **作者：** Iago Alves Brito, Walcy Rios, Julia Soares Dollis, Diogo Fernandes Costa Silva, Arlindo Rodrigues Galv{\~a}o Filho
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.489/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.489.pdf)
- **中文提要：** 把伤害归入“身份仇恨”这类笼统类别，会制造普遍受保护的假象，并掩盖针对特定人群的脆弱点。作者把模型稳妥保护某些群体、却让代表性不足社群高度暴露的系统性失效称为选择性安全陷阱。
- **关键词：** DPO, preference-optimization, alignment

### SAMoRA: Semantic-Aware Mixture of LoRA Experts for Task-Adaptive Learning

- **作者：** Boyan Shi, Wei Chen, Shuyuan Zhao, Junfeng Shen, Shengnan Guo, Shaojiang Wang, Huaiyu Wan
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1404/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1404.pdf)
- **中文提要：** 混合专家与 LoRA 结合有助于大模型的多任务学习，但现有路由不够精确，未能把输入语义和专家能力显式对应，专家分工因此偏弱。SAMoRA 提出语义感知的 LoRA 专家混合，以支持任务自适应学习。
- **关键词：** LoRA, PEFT, fine-tuning

### SDC-LoRA: Singular-Subspace Drift Controlled LoRA to Mitigate Knowledge Forgetting

- **作者：** Geyuan Zhang, Xiaofei Zhou, Shihao Liu, Jingyuan Tian, Jizheng Ma
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1207/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1207.pdf)
- **中文提要：** 适配新任务时的知识遗忘是核心难点；已有工作指出预训练知识集中在预训练权重的主奇异子空间，因而有 LoRA 变体在次子空间初始化，让早期更新避开主方向。SDC-LoRA 进一步通过控制奇异子空间漂移来减轻遗忘。
- **关键词：** LoRA, fine-tuning

### Select2Reason: Efficient Instruction-Tuning Data Selection for Long-CoT Reasoning

- **作者：** Cehao Yang, Xueyuan Lin, Xiaojun Wu, Chengjin Xu, Xuhui Jiang, Honghao Liu, Hui Xiong, Jian Guo
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.331/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.331.pdf)
- **中文提要：** 用强推理模型合成的指令数据做监督微调，是激活长思维链、且比强化学习更省成本的一条路线。大规模指令集的训练开销很高，有效的自动数据选择策略仍然欠缺。
- **关键词：** SFT, instruction-tuning, reward-model, fine-tuning

### Self-Guided Plan Extraction for Instruction-Following Tasks with Goal-Conditional Reinforcement Learning

- **作者：** Zoya Volovikova, Nikita Sorokin, Dmitriy Lukashevskiy, Aleksandr Panov, Alexey Skrynnik
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1691/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1691.pdf)
- **中文提要：** SuperIgor 面向指令跟随任务。它不依赖预先定义的子任务，而是让语言模型以自学习方式生成并改进高层计划，从而减少人工标注数据集的需要。
- **关键词：** instruction-following

### Semantic-Space Exploration and Exploitation in RLVR for LLM Reasoning

- **作者：** Fanding Huang, Guanbo Huang, Xiao Fan, Yi He, Xiao Liang, Xiao Chen, Qinting Jiang, Faisal Nadeem Khan, Jingyan Jiang, Zhi Wang
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1915/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1915.pdf)
- **中文提要：** 可验证奖励强化学习中的探索与利用，常被放在动作空间里，并用输出熵或置信度等词元级代理来操作。作者认为这种权衡很大程度上是测量假象：词元统计反映的是下一词不确定性，而不是推理如何在多个词上推进。
- **关键词：** RLVR

### Sem-DPO: Mitigating Semantic Inconsistency in Preference Optimization for Prompt Engineering

- **作者：** Anas Mohamed, Azal Ahmad Khan, Xinran Wang, Ahmad Faraz Khan, Shuwen Ge, Saman Bahzad Khan, Ayaan Ahmad, Ali Anwar
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1184/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1184.pdf)
- **中文提要：** 文生图的质量对提示措辞高度敏感。DPO 为自动提示工程提供了相对轻量的离策略替代，但词元级正则约束不住语义不一致，偏好分更高的提示仍可能漂移离开。
- **关键词：** DPO, preference-optimization

### SemPA: Improving Sentence Embeddings of Large Language Models through Semantic Preference Alignment

- **作者：** Ziyang Chen, Zhenxuan Huang, Yile Wang, Weiqin Wang, Lu Yin, Hui Huang
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1858/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1858.pdf)
- **中文提要：** 传统句向量多用非生成式预训练模型上的词元级对比学习，近来也出现基于生成式大语言模型的嵌入方法。SemPA 通过语义偏好对齐来改进这类句向量。
- **关键词：** DPO, preference-optimization, alignment

### Small Data, Big Noise: Adversarial Training for Robust ParameterEfficient Fine-Tuning

- **作者：** Eitan Cohen, Idan Simai, Uri Shaham
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.2014/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.2014.pdf)
- **中文提要：** 把基础模型适配到下游自然语言任务时，参数高效微调往往扛不住噪声，训练数据有限时性能也容易下降。作者用对抗训练来加强这种小数据、高噪声条件下的稳健微调。
- **关键词：** PEFT, fine-tuning

### Specialization without Sparsity: Efficient and Expressive Split-Path Experts for LLM Fine-Tuning

- **作者：** Ganghao Liu, Qin Zhou, Zhe Wang, Xuehan Lu, Haihua Huang, Yunfei Tong, Heng Tian
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.975/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.975.pdf)
- **中文提要：** 低成本适配大语言模型时，参数高效微调的表示灵活性常常不够。作者引入混合专家，提出高效且更富表达力的分路专家，希望在较低资源开销下增强专门化。
- **关键词：** PEFT, fine-tuning

### SSR-Zero: Simple Self-Rewarding Reinforcement Learning for Machine Translation

- **作者：** Wenjie Yang, Mao Zheng, Mingyang Song, Zheng Li, Sitong Wang
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.300/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.300.pdf)
- **中文提要：** 机器翻译上较强的专用大模型，训练时往往高度依赖人工参考译文或已训练奖励模型等外部监督，成本高且难扩展。SSR-Zero 用简单的自奖励强化学习来减轻这种依赖。
- **关键词：** reward-model, self-rewarding

### StateX: Enhancing RNN Recall via Post-training State Expansion

- **作者：** Xingyu Shen, Yingfa Chen, Zhen Leng Thai, Xu Han, Zhiyuan Liu, Maosong Sun
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1073/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1073.pdf)
- **中文提要：** 线性注意力和状态空间模型等循环网络处理长上下文时每词开销保持常数，但全部上下文被压进固定大小的循环状态，难以准确回忆。StateX 希望在后训练阶段扩展状态，以增强这种回忆能力。
- **关键词：** post-training

### SWE-Swiss: A Multi-Task Fine-Tuning and RL Recipe for High-Performance Issue Resolution

- **作者：** Zhenyu He, Qingping Yang, Wei Shen, Xiaojian Zhong, Kechi Zhang, Chenxin An, Wenlei Shi, Tianle Cai, Di He, Jiaze Chen, Jingjing Xu
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.790/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.790.pdf)
- **中文提要：** 在 SWE-bench 一类基准上解决真实软件问题，对大语言模型仍然困难。SWE-Swiss 给出两阶段训练方案，用多任务微调与强化学习系统培养问题修复能力。
- **关键词：** SFT, fine-tuning

### TARo: Token-level Adaptive Routing for LLM Test-time Alignment

- **作者：** Arushi Rai, Qiang Zhang, Hanqing Zeng, Yunkai Zhang, Dipesh Tamboli, Xiangjun Fan, Zhuokai Zhao, Lizhu Zhang
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.50/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.50.pdf)
- **中文提要：** 测试时对齐比重训练更轻量，但以往主要面向偏好对齐而非推理。TARo 把词元级自适应路由用于大模型的测试时对齐。
- **关键词：** instruction-following, preference-optimization, reward-model, post-training, alignment

### \textscValue Alignment Tax: Measuring Value Trade-offs in LLM Alignment

- **作者：** Jiajun Chen, Hua Shen
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1749/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1749.pdf)
- **中文提要：** 价值对齐研究通常静态描述价值关系，忽略提示、微调或偏好优化等干预如何重塑更广的价值体系。对齐某一目标价值可能连带挪动其他价值，形成尚未被充分度量的权衡；VAT 框架用来量化这类权衡。
- **关键词：** preference-optimization, alignment, fine-tuning

### The Art of (Mis)alignment: How Fine-Tuning Methods Effectively Misalign and Realign LLMs in Post-Training

- **作者：** Rui Zhang, Hongwei Li, Yun Shen, Xinyue Shen, Wenbo Jiang, Guowen Xu, Yang Liu, Michael Backes, Yang Zhang
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.164/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.164.pdf)
- **中文提要：** 对齐技术本用于提升大模型的安全与可信，对手却可能利用微调手段削弱安全，造成错位。该研究考察后训练中的微调方法如何使模型错位，以及如何再把它们对齐回来。
- **关键词：** DPO, ORPO, SFT, preference-optimization, post-training, alignment, fine-tuning

### The Best of Both Worlds: Combining Parallel and Sequential Inference Scaling via Aggregation Fine-Tuning

- **作者：** Yafu Li, Zhilin Wang, Tingchen Fu, Ganqu Cui, Sen Yang, Yu Cheng
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1568/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1568.pdf)
- **中文提要：** 除了在训练时扩大数据和模型规模，增加测试时计算也能进一步提升大模型表现。作者用聚合微调把并行与串行两种推理时扩展结合起来。
- **关键词：** SFT, reward-model, fine-tuning

### Token-level Inference-Time Alignment for Vision-Language Models

- **作者：** Kejia Chen, Junjun Zheng, Jiawen Zhang, Manxi Lin, Xiao Pan, Jiacong Hu, Jian Lou, Zunlei Feng, Mingli Song
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1253/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1253.pdf)
- **中文提要：** 视觉语言模型往往更重语言流畅而轻视觉忠实，生成文本会与图像相矛盾。常见对策要么是高成本微调，要么等整段回答生成后才做高延迟校验；这里改为在推理时做词元级对齐。
- **关键词：** DPO, preference-optimization, reward-model, alignment, fine-tuning

### ToolPRMBench: Evaluating and Advancing Process Reward Models for Tool-using Agents

- **作者：** Dawei Li, Yuguang Yao, Zhen Tan, Huan Liu, Ruocheng Guo
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.602/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.602.pdf)
- **中文提要：** 奖励引导搜索能在复杂动作空间中引导采样与探索，从而增强工具使用智能体，其核心是用过程奖励模型给出步骤级奖励。ToolPRMBench 用来评估并推进这类面向工具使用智能体的过程奖励模型。
- **关键词：** PRM, reward-model

### ToolRM: Towards Agentic Tool-Use Reward Modeling

- **作者：** Renhao Li, Jianhong Tu, Yang Su, Yantao Liu, Fei Huang, Hamid Alinejad-Rokny, Derek F. Wong, Junyang Lin, Min Yang
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.419/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.419.pdf)
- **中文提要：** 奖励模型对对齐人类偏好很关键，但工具学习中缺少专门面向函数调用的奖励模型，更强智能体的进展因此受限。ToolRM 朝着面向智能体工具使用的奖励建模推进。
- **关键词：** reward-model, alignment

### Topology-Enhanced Alignment for Large Language Models: Trajectory Topology Loss and Topological Preference Optimization

- **作者：** Yurui Pan, Ke Xu, Bo Peng
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1242/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1242.pdf)
- **中文提要：** 对齐通常依赖 SFT、RLHF 或 DPO，现有目标却多停留在局部词元似然或标量偏好分上，忽略表示空间的整体几何与拓扑，也没有显式施加约束。文中提出轨迹拓扑损失和拓扑偏好优化来加强对齐。
- **关键词：** DPO, RLHF, SFT, preference-optimization, alignment, fine-tuning

### Towards Bridging the Reward-Generation Gap in Direct Alignment Algorithms

- **作者：** Zeguan Xiao, Yun Chen, Jian Yang, Guanhua Chen, Ke Tang
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.713/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.713.pdf)
- **中文提要：** DPO、SimPO 等直接对齐算法是相对高效的 RLHF 替代，但存在作者所称的奖励—生成鸿沟，即某种不一致。
- **关键词：** DPO, SimPO, RLHF, preference-optimization, alignment

### Towards Hierarchical Multi-Step Reward Models for Enhanced Reasoning in Large Language Models

- **作者：** Teng Wang, Jiang Zhangyi, Zhenqi He, Hailei Gong, Shenyang Tong, Wenhan Yang, Zeyu Li, Yanan Zheng, Zifan He, Zewen Ye, Shengjie Ma, Jianping Zhang
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.27/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.27.pdf)
- **中文提要：** 现有过程奖励模型容易被奖励投机，又依赖昂贵的大规模推理步骤标注，可靠性和可扩展性都受限。作者朝分层的多步奖励模型推进，以加强大模型的推理。
- **关键词：** SFT, PRM, reward-model, fine-tuning

### Trident: Self-Supervised Preference Alignment via Triplet Regularization

- **作者：** Yingnan Guo, Kejia Chen, Xiaofeng Zhang, Zifei Wu, Yu Zhang
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1585/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1585.pdf)
- **中文提要：** 减轻大型视觉语言模型的幻觉通常需要高质量偏好数据；自监督设定下，DPO 这类二元偏好优化会遇到噪声监督和语义歧义，自动选出的回答未必优于被拒绝的回答。Trident 用三元组正则做自监督偏好对齐。
- **关键词：** DPO, RLHF, RLAIF, preference-optimization, reward-model, alignment

### Two-Stage Parameter Alignment for Multi-LoRA Merging in Large Language Models

- **作者：** Zijian Li, Xiachong Feng, Weitao Ma, Yichong Huang, Xiaocheng Feng, Bing Qin
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1504/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1504.pdf)
- **中文提要：** 合并大量 LoRA 有助于提高大模型的集成与部署效率，但通用合并容易出现参数干扰，高秩 LoRA 之间的冲突往往更严重。这里用两阶段参数对齐来处理多 LoRA 合并。
- **关键词：** LoRA, alignment

### Understanding and Preventing Entropy Collapse in RLVR with On-Policy Entropy Flow Optimization

- **作者：** Huimin Xu, Shuai Zhao, Xiaobao Wu, Anh Tuan Luu
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.879/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.879.pdf)
- **中文提要：** 可验证奖励强化学习能提升推理，但 GRPO 等算法常出现熵坍缩，使策略过早变得确定且优化不稳。作者从同策略熵流优化来理解并防止这种坍缩。
- **关键词：** GRPO, RLVR

### Unlocking Exploration in RLVR: Uncertainty-aware Advantage Shaping for Deeper Reasoning

- **作者：** Can Xie, Ruotong Pan, Xiangyu Wu, Zhang Yunfei, Jiayi Fu, Tingting Gao, Guorui Zhou
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.951/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.951.pdf)
- **中文提要：** GRPO 一类算法把同一个优势信号广播给序列中的全部词元，探索因此受限。不确定性感知的优势塑形被用来打开 RLVR 中的探索，以支持更深的推理。
- **关键词：** GRPO, RLVR

### Unlocking the Edge deployment and ondevice acceleration of multi-LoRA enabled one-for-all foundational LLM

- **作者：** Sravanth Kodavanti, Sowmya Vajrala, Srinivas Soumitri Miriyala, Utsav Tiwari, Uttam Kumar, Utkarsh Kumar Mahawar, Achal Pratap Singh, Arya D, Narendra Mutyala, Vikram Nelvoy Rajendiran, Sharan Kumar Allur, Euntaik Lee, Dohyoung Kim, HyeonSu Lee, Gyusung Cho, JungBae Kim
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.2106/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.2106.pdf)
- **中文提要：** 在手机上部署大模型受内存、延迟和运行时灵活性约束。作者给出面向硬件的端侧推理框架，支持带多 LoRA、覆盖多种用途的 LLaMA 多语言基础模型。
- **关键词：** LoRA

### VANE: Guiding High-Value Exploration in RLVR via Outcome-Process Novelty Shaping

- **作者：** Xu He, Jialiang Guo, Fucheng Xiong, Haodong Zhao, Xingyang li, Ke Zeng, Xunliang Cai
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1434/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1434.pdf)
- **中文提要：** 可验证奖励强化学习的反馈很稀疏，容易出现模式坍缩；熵正则能引入随机性，却缺少方向。VANE 用结果与过程的新颖性塑形，为高价值探索提供引导。
- **关键词：** RLVR, alignment

### V-RoLoRA: RLVR-Driven MoE Routing for Steerable Pluralistic Alignment

- **作者：** Jing Wang, Yaomin Wu, Yinglin Wang, Yitong Yang
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1377/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1377.pdf)
- **中文提要：** 可引导的多元对齐希望模型稳定遵循多样甚至相互冲突的人类价值，尤其是多维、可组合的目标。现有做法多靠提示工程或推理时引导，提示一被扰动或去掉，控制就脆弱且难持续；V-RoLoRA 改用 RLVR 驱动的混合专家路由。
- **关键词：** GRPO, RLVR, LoRA, PEFT, post-training, alignment

### WavAlign: Enhancing Intelligence and Expressiveness in Spoken Dialogue Models via Adaptive Hybrid Post-Training

- **作者：** Yifu Chen, Shengpeng Ji, Qian Chen, Tianle Liang, Yangzhuo Li, Ziqing Wang, Wen Wang, Jingyu Lu, Haoxiao Wang, Xueyi Pu, Fan Zhuo, Zhou Zhao
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.114/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.114.pdf)
- **中文提要：** 端到端口语对话模型在表现力和感知上的上限通常高于级联系统，但现有开源模型的智能与表现力仍常低于预期。WavAlign 以自适应的混合后训练来加强这两方面。
- **关键词：** preference-optimization, reward-model, post-training

### When and What to Ask: AskBench and Rubric-Guided RLVR for LLM Clarification

- **作者：** Jiale Zhao, Ke Fang, Lu Cheng
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.845/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.845.pdf)
- **中文提要：** 提示漏掉关键细节或带有误导时，大模型仍常直接作答，从而产生幻觉或强化误解。该研究考察如何评估并改进模型决定何时提问、问什么的能力且不牺牲任务表现，并引入 AskBench 与量规引导的 RLVR。
- **关键词：** RLVR

### Why LoRA Fails to Forget: Regularized Low-Rank Adaptation Against Backdoors in Language Models

- **作者：** Hoang-Chau Luong, Lingwei Chen
- **会议：** ACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-acl.1732/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-acl.1732.pdf)
- **中文提要：** 在干净数据上微调时，LoRA 很难去掉被投毒预训练模型里的后门。作者指出这一弱点并不主要来自低秩，而根本上是谱性质的，并讨论用正则化的低秩适应来对抗后门。
- **关键词：** LoRA, PEFT, post-training, alignment, fine-tuning
