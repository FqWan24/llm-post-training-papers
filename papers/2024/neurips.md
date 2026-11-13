# 2024 · NeurIPS

共 118 篇。Main 118，Findings 0，其他赛道 0。其中 0 篇来源题录无摘要，提要标明「仅根据标题概括」。

检索窗口为 2024-11-13 至 2026-11-13。题录信息来自官方列表，不在此增补作者、链接或实验数字。

## Main

### 3-in-1: 2D Rotary Adaptation for Efficient Finetuning, Efficient Batching and Composability

- **作者：** Baohao Liao, Christof Monz
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/3dbcadb7beedc2afe32bb23f75dd30ec-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/3dbcadb7beedc2afe32bb23f75dd30ec-Paper-Conference.pdf)
- **中文提要：** PEFT 能有效把大语言模型适配到不同下游任务，并降低存储与 GPU 内存需求。尽管如此，一些应用给 PEFT 带来了参数效率之外的新挑战。
- **关键词：** PEFT, fine-tuning

### A Critical Evaluation of AI Feedback for Aligning Large Language Models

- **作者：** Archit Sharma, Sedrick Scott Keh, Eric Mitchell, Chelsea Finn, Kushal Arora, Thomas Kollar
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/33870b3e099880cd8e705cd07173ac27-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/33870b3e099880cd8e705cd07173ac27-Paper-Conference.pdf)
- **中文提要：** 从 AI 反馈中学习是提升强大预训练语言模型指令遵循能力的常用范式。它先用教师模型的示范做 SFT，再用评论模型的反馈，通过强化学习或 DPO 进一步微调。
- **关键词：** DPO, SFT, instruction-following, preference-optimization, alignment, fine-tuning

### Adaptive Preference Scaling for Reinforcement Learning with Human Feedback

- **作者：** Ilgee Hong, Zichong Li, Alexander Bukharin, Yixiao Li, Haoming Jiang, Tianbao Yang, Tuo Zhao
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/c1f66abb52467443ba8fc70e0a32e061-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/c1f66abb52467443ba8fc70e0a32e061-Paper-Conference.pdf)
- **中文提要：** RLHF 是让 AI 系统对齐人类价值的常见途径，做法是从人类偏好数据中学习奖励。由于种种原因，这类数据通常只是轨迹片段的成对排序，无法反映不同配对之间偏好强度的差异。
- **关键词：** DPO, RLHF, preference-optimization

### Aligning Diffusion Models by Optimizing Human Utility

- **作者：** Shufan Li, Konstantinos Kallidromitis, Akash Gokul, Yusuke Kato, Kazuki Kozuka
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/2c487f8a54cf24c0684c32abc77fed56-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/2c487f8a54cf24c0684c32abc77fed56-Paper-Conference.pdf)
- **中文提要：** Diffusion-KTO 把文生图扩散模型的对齐写成期望人类效用的最大化。与以往方法不同，它不需要收集成对偏好数据，也不需要训练复杂的奖励模型。
- **关键词：** DPO, KTO, SFT, reward-model, alignment, fine-tuning

### Aligning Large Language Models with Representation Editing: A Control Perspective

- **作者：** Lingkai Kong, Haorui Wang, Wenhao Mu, Yuanqi Du, Yuchen Zhuang, Yifei Zhou, Yue Song, Rongzhi Zhang, Kai Wang, Chao Zhang
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/41bba7b0f5c81e789a20bb16a370aeeb-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/41bba7b0f5c81e789a20bb16a370aeeb-Paper-Conference.pdf)
- **中文提要：** 让大语言模型对齐人类目标，对真实应用至关重要。然而，为对齐而微调常常训练不稳定，并且需要可观的计算资源。
- **关键词：** alignment, fine-tuning

### Aligning LLM Agents by Learning Latent Preference from User Edits

- **作者：** Ge Gao, Alexey Taymanov, Eduardo Salinas, Paul Mineiro, Dipendra Misra
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/f75744612447126da06767daecce1a84-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/f75744612447126da06767daecce1a84-Paper-Conference.pdf)
- **中文提要：** 研究基于用户对智能体输出所做修改的交互式学习。在写作助手这类典型场景中，用户根据上下文与语言智能体交互得到回答，除了改正确性，还可能按自己的潜在偏好编辑该回答以做个性化。
- **关键词：** alignment, fine-tuning

### Antigen-Specific Antibody Design via Direct Energy-based Preference Optimization

- **作者：** Xiangxin Zhou, Dongyu Xue, Ruizhe Chen, Zaixiang Zheng, Liang Wang, Quanquan Gu
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/daef77101ba5711084a57442c8cf2709-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/daef77101ba5711084a57442c8cf2709-Paper-Conference.pdf)
- **中文提要：** 抗体设计对治疗和生物学等多个学科都很重要，但其复杂性带来相当大的挑战。作者把抗原特异性抗体的序列与结构联合设计视为面向特定偏好的优化问题，同时考虑合理性与功能性。
- **关键词：** preference-optimization, fine-tuning

### Axioms for AI Alignment from Human Feedback

- **作者：** Luise Ge, Daniel Halpern, Evi Micha, Ariel Procaccia, Itai Shapira, Yevgeniy Vorobeychik, Junlin Wu
- **会议：** NeurIPS 2024 · Main · Spotlight
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/9328208f88ec69420031647e6ff97727-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/9328208f88ec69420031647e6ff97727-Paper-Conference.pdf)
- **中文提要：** 在 RLHF 的设定下，奖励函数一般来自随机效用模型的最大似然估计，而该模型建立在人类成对比较之上。学习奖励函数是一种偏好聚合，作者认为它很大程度上属于社会选择理论的范围。
- **关键词：** RLHF, alignment

### BackdoorAlign: Mitigating Fine-tuning based Jailbreak Attack with Backdoor Enhanced Safety Alignment

- **作者：** Jiongxiao Wang, Jiazhao LI, Yiquan Li, Xiangyu Qi, Junjie Hu, Sharon Li, Patrick McDaniel, Muhao Chen, Bo Li, Chaowei Xiao
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/094324f386c836c75d4a26f3499d2ede-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/094324f386c836c75d4a26f3499d2ede-Paper-Conference.pdf)
- **中文提要：** 尽管 GPT-4 等大语言模型具备通用能力，面对具体业务需求和定制场景时，仍需要用定制数据做微调或适配。这一过程不可避免地引入新的安全威胁，尤其是语言模型即服务设定下基于微调的越狱攻击。
- **关键词：** alignment, fine-tuning

### Be Confident in What You Know: Bayesian Parameter Efficient Fine-Tuning of Vision Foundation Models

- **作者：** Deep Pandey, Spandan Pyakurel, Qi Yu
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/4f1fbd5ab8d58d0ecf33c95fd46b900e-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/4f1fbd5ab8d58d0ecf33c95fd46b900e-Paper-Conference.pdf)
- **中文提要：** 大型 Transformer 基础模型常被当作预训练模型，适配到不同的困难数据集和设定，并具有很强的泛化表现。PEFT 能在计算开销很小的情况下，为这种适配提供有希望的泛化。
- **关键词：** PEFT, fine-tuning

### Benchmarking Complex Instruction-Following with Multiple Constraints Composition

- **作者：** Bosi Wen, Pei Ke, Xiaotao Gu, Lindong Wu, Hao Huang, Jinfeng Zhou, Wenchuang Li, Binxin Hu, Wendy Gao, Jiaxing Xu, Yiming Liu, Jie Tang, Hongning Wang, Minlie Huang
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/f8c24b08b96a08ec7a7a975feea7777e-Abstract-Datasets_and_Benchmarks_Track.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/f8c24b08b96a08ec7a7a975feea7777e-Paper-Datasets_and_Benchmarks_Track.pdf)
- **中文提要：** 指令遵循是大语言模型的基础能力之一。随着能力不断提高，它们越来越多地被用于处理真实场景中复杂的人类指令。
- **关键词：** instruction-following

### $\beta$-DPO: Direct Preference Optimization with Dynamic $\beta$

- **作者：** Junkang Wu, Yuexiang Xie, Zhengyi Yang, Jiancan Wu, Jinyang Gao, Bolin Ding, Xiang Wang, Xiangnan He
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/ea888178abdb6fc233226d12321d754f-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/ea888178abdb6fc233226d12321d754f-Paper-Conference.pdf)
- **中文提要：** DPO 已成为训练大语言模型遵循人类偏好的一种有吸引力的途径。不过，DPO 的表现对权衡参数 β 的调节很敏感，也受偏好数据质量影响。
- **关键词：** DPO, preference-optimization, alignment, fine-tuning

### Biomedical Visual Instruction Tuning with Clinician Preference Alignment

- **作者：** Hejie Cui, Lingjun Mao, Xin Liang, Jieyu Zhang, Hui Ren, Quanzheng Li, Xiang Li, Carl Yang
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/aec33ab89b5986605cd7c331396e7e5c-Abstract-Datasets_and_Benchmarks_Track.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/aec33ab89b5986605cd7c331396e7e5c-Paper-Datasets_and_Benchmarks_Track.pdf)
- **中文提要：** 多模态基础模型在理解和推理视觉与文本信息方面已展现出突出能力。要把为通用用途训练的基础模型适配到生物医学等专业领域，需要大规模的领域专用指令数据。
- **关键词：** instruction-tuning, instruction-following, preference-optimization, alignment

### BitDelta: Your Fine-Tune May Only Be Worth One Bit

- **作者：** James Liu, Guangxuan Xiao, Kai Li, Jason Lee, Song Han, Tri Dao, Tianle Cai
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/187d94b3c93343f0e925b5cf729eadd5-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/187d94b3c93343f0e925b5cf729eadd5-Paper-Conference.pdf)
- **中文提要：** 模型通常先在大规模互联网数据上预训练，再针对下游任务微调。鉴于预训练的计算需求更高，一个直观看法是微调为模型增添的新信息更少，因此也更容易被压缩。
- **关键词：** fine-tuning

### BLoB: Bayesian Low-Rank Adaptation by Backpropagation for Large Language Models

- **作者：** Yibin Wang, Haizhou Shi, Ligong Han, Dimitris Metaxas, Hao Wang
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/7d53575463291ea6b5a23cf6e571f59b-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/7d53575463291ea6b5a23cf6e571f59b-Paper-Conference.pdf)
- **中文提要：** 大语言模型在推理时常常过度自信，用有限数据适配到下游领域任务时尤其如此。先前工作在模型训练之后采用近似贝叶斯估计，使模型能够量化不确定性。
- **关键词：** LoRA, post-training, fine-tuning

### Bridging Model-Based Optimization and Generative Modeling via Conservative Fine-Tuning of Diffusion Models

- **作者：** Masatoshi Uehara, Yulai Zhao, Ehsan Hajiramezanali, Gabriele Scalia, Gokcen Eraslan, Avantika Lal, Sergey Levine, Tommaso Biancalani
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/e68274fc4f158dbcbd4dddc672f7ee9c-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/e68274fc4f158dbcbd4dddc672f7ee9c-Paper-Conference.pdf)
- **中文提要：** DNA、蛋白质序列设计等 AI 驱动的设计问题，通常从两个角度处理：生成建模高效刻画可行设计空间，基于模型的优化则利用奖励模型做外推。为结合二者长处，作者采用混合方法来微调前沿扩散模型。
- **关键词：** reward-model, fine-tuning

### Cal-DPO: Calibrated Direct Preference Optimization for Language Model Alignment

- **作者：** Teng Xiao, Yige Yuan, Huaisheng Zhu, Mingxiao Li, Vasant Honavar
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/cf8b2205e39f81726a8d828ecbe00ad0-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/cf8b2205e39f81726a8d828ecbe00ad0-Paper-Conference.pdf)
- **中文提要：** 讨论的是如何用人类偏好数据对齐大语言模型。对比式偏好优化通过优化与策略相关联的隐式奖励，在已有偏好数据上的对齐中显示出有希望的结果。
- **关键词：** DPO, preference-optimization, alignment

### Calibrated Self-Rewarding Vision Language Models

- **作者：** Yiyang Zhou, Zhiyuan Fan, Dongjie Cheng, Sihan Yang, Zhaorun Chen, Chenhang Cui, Xiyao Wang, Yun Li, Linjun Zhang, Huaxiu Yao
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/5c20c00504e0c049ec2370d0cceaf3c4-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/5c20c00504e0c049ec2370d0cceaf3c4-Paper-Conference.pdf)
- **中文提要：** 大型视觉语言模型通过指令微调整合预训练语言模型与视觉模型，取得了实质性进展。它们仍常出现幻觉：生成的文本在语言上貌似合理，却与输入图像矛盾，表明图文对之间存在错位。
- **关键词：** instruction-tuning, preference-optimization, reward-model, alignment, self-rewarding, fine-tuning

### CALVIN: Improved Contextual Video Captioning via Instruction Tuning

- **作者：** Gowthami Somepalli, Arkabandhu Chowdhury, Jonas Geiping, Ronen Basri, Tom Goldstein, David Jacobs
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/a922b7121007768f78f770c404415375-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/a922b7121007768f78f770c404415375-Paper-Conference.pdf)
- **中文提要：** 强大视觉语言模型的出现显著改善了图像描述。其中一些模型也被扩展用来描述视频。
- **关键词：** instruction-tuning

### Catastrophic Goodhart: regularizing RLHF with KL divergence does not mitigate heavy-tailed reward misspecification

- **作者：** Thomas Kwa, Drake Thomas, Adrià Garriga-Alonso
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/1a8189929f3d7bd6183718f42c3f4309-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/1a8189929f3d7bd6183718f42c3f4309-Paper-Conference.pdf)
- **中文提要：** 应用 RLHF 时，奖励从数据中学习，因此总会有误差。常见缓解方式是用相对基座模型的 KL 散度来正则化策略，希望在奖励设定有误的情况下，靠奖励与正则的平衡仍能得到理想结果。
- **关键词：** RLHF, reward-model

### Chain of Preference Optimization: Improving Chain-of-Thought Reasoning in LLMs

- **作者：** Xuan Zhang, Chao Du, Tianyu Pang, Qian Liu, Wei Gao, Min Lin
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/00d80722b756de0166523a87805dd00f-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/00d80722b756de0166523a87805dd00f-Paper-Conference.pdf)
- **中文提要：** 思维链解码的发展，使大语言模型能为复杂问题生成显式的逻辑推理路径。但研究表明，这些路径并不总是审慎且最优的。
- **关键词：** preference-optimization, fine-tuning

### Coevolving with the Other You: Fine-Tuning LLM with Sequential Cooperative Multi-Agent Reinforcement Learning

- **作者：** Hao Ma, Tianyi Hu, Zhiqiang Pu, Liu Boyin, Xiaolin Ai, Yanyan Liang, Min Chen
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/1c2b1c8f7d317719a9ce32dd7386ba35-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/1c2b1c8f7d317719a9ce32dd7386ba35-Paper-Conference.pdf)
- **中文提要：** 强化学习已成为在特定任务上微调大语言模型的关键技术。不过，主流的强化学习微调方法主要依赖 PPO 及其变体。
- **关键词：** RFT, fine-tuning

### CoIN: A Benchmark of Continual Instruction Tuning for Multimodel Large Language Models

- **作者：** Cheng Chen, Junchen Zhu, Xu Luo, Hengtao Shen, Jingkuan Song, Lianli Gao
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/6a45500d9eda640deed90d8a62742be5-Abstract-Datasets_and_Benchmarks_Track.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/6a45500d9eda640deed90d8a62742be5-Paper-Datasets_and_Benchmarks_Track.pdf)
- **中文提要：** 指令微调在让多模态大语言模型遵循任务指令、提升泛化方面表现突出。把微调扩展到多样任务后，这些模型还能进一步加强对世界知识与指令意图的理解。
- **关键词：** instruction-tuning, alignment

### CorDA: Context-Oriented Decomposition Adaptation of Large Language Models for Task-Aware Parameter-Efficient Fine-tuning

- **作者：** Yibo Yang, Xiaojie Li, Zhongzhu Zhou, Shuaiwen Song, Jianlong Wu, Liqiang Nie, Bernard Ghanem
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/83f95bb0ac5046338ea2afe3390e9f4b-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/83f95bb0ac5046338ea2afe3390e9f4b-Paper-Conference.pdf)
- **中文提要：** 当前 PEFT 方法构建适配器时，普遍不区分下游任务要学习的上下文，也不区分需要维持的重要知识所处的上下文。结果是相对全参数微调往往存在性能差距，微调后的模型还会灾难性遗忘预训练得到的世界知识。
- **关键词：** instruction-following, LoRA, PEFT, fine-tuning

### Curriculum Fine-tuning of Vision Foundation Model for Medical Image Classification Under Label Noise

- **作者：** Yeonguk Yu, Minhwan Ko, Sungho Shin, Kangmin Kim, Kyoobin Lee
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/2093ed77c549eda95bd6f7212b735b43-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/2093ed77c549eda95bd6f7212b735b43-Paper-Conference.pdf)
- **中文提要：** 深度神经网络在多种视觉任务上表现突出，但其成功很大程度上取决于训练数据的质量。噪声标签是医学数据集中的关键问题，会显著降低模型表现。
- **关键词：** fine-tuning

### Customizing Language Models with Instance-wise LoRA for Sequential Recommendation

- **作者：** Xiaoyu Kong, Jiancan Wu, An Zhang, Leheng Sheng, Hui Lin, Xiang Wang, Xiangnan He
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/cd476d01692c508ddf1cb43c6279a704-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/cd476d01692c508ddf1cb43c6279a704-Paper-Conference.pdf)
- **中文提要：** 序列推荐系统根据用户过去的交互预测下一次交互物品，使推荐贴合个人偏好。借助大语言模型在知识理解与推理上的优势，近期方法正急于把它们应用到序列推荐中。
- **关键词：** LoRA, PEFT, alignment, fine-tuning

### D-CPT Law: Domain-specific Continual Pre-Training Scaling Law for Large Language Models

- **作者：** Haoran Que, Jiaheng Liu, Ge Zhang, Chenchen Zhang, Xingwei Qu, Yinghao Ma, Feiyu Duan, ZhiqiBai zhiqi, JiakaiWang, Yuanxing Zhang, Xu Tan, Jie Fu, Jiamang Wang, Lin Qu, Wenbo Su, Bo Zheng
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/a4628e9fbd3002a554923642f74d5d6b-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/a4628e9fbd3002a554923642f74d5d6b-Paper-Conference.pdf)
- **中文提要：** 持续预训练被广泛用来扩展大语言模型对数学、代码等下游领域的基础理解。对领域化的持续预训练来说，重要的是如何在通用语料（例如 Dolma、SlimPajama）和下游领域语料之间选定最优混合比例。
- **关键词：** continued-pretraining

### Decoding-Time Language Model Alignment with Multiple Objectives

- **作者：** Ruizhe Shi, Yifang Chen, Yushi Hu, Alisa Liu, Hanna Hajishirzi, Noah Smith, Simon Du
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/57c89126d60c209f48d0e6395c766bb3-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/57c89126d60c209f48d0e6395c766bb3-Paper-Conference.pdf)
- **中文提要：** 把语言模型对齐到人类偏好已成为关键课题，使模型能更好地服务多样的用户需求。现有方法主要针对单一奖励函数优化，限制了它们适应不同目标的能力。
- **关键词：** DPO, alignment, fine-tuning

### Discovering Preference Optimization Algorithms with and for Large Language Models

- **作者：** Chris Lu, Samuel Holt, Claudio Fanconi, Alex Chan, Jakob Foerster, Mihaela van der Schaar, Robert Lange
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/9d88b87b31986f8293bb0067a841579e-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/9d88b87b31986f8293bb0067a841579e-Paper-Conference.pdf)
- **中文提要：** 离线偏好优化是提升并控制大语言模型输出质量的关键方法，通常被当作使用人工设计凸损失函数的离线监督学习任务。这些方法虽有理论依据，却天生受限于人的创造力，可能的损失函数仍有很大的搜索空间。
- **关键词：** preference-optimization

### Distributional Preference Alignment of LLMs via Optimal Transport

- **作者：** Igor Melnyk, Youssef Mroueh, Brian Belgodere, Mattia Rigotti, Apoorva Nitsure, Mikhail Yurochkin, Kristjan Greenewald, Jiri Navratil, Jarret Ross
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/bce96750dcb64f3257ceabadf0b9c9bf-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/bce96750dcb64f3257ceabadf0b9c9bf-Paper-Conference.pdf)
- **中文提要：** 当前的大语言模型对齐技术在样本层面使用成对人类偏好，因此并不意味着分布层面也已对齐。文中提出基于最优传输的对齐方法 AOT，用于大语言模型的分布偏好对齐。
- **关键词：** preference-optimization, alignment, fine-tuning

### DoFIT: Domain-aware Federated Instruction Tuning with Alleviated Catastrophic Forgetting

- **作者：** Binqian Xu, Xiangbo Shu, Haiyang Mei, Zechen Bai, Basura Fernando, Mike Zheng Shou, Jinhui Tang
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/9be9407431b7ff8cc04cae5460fcb7ab-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/9be9407431b7ff8cc04cae5460fcb7ab-Paper-Conference.pdf)
- **中文提要：** 联邦指令微调让各方在去中心化数据上协作训练并保护隐私，但现有方法主要处理客户端之间的数据异质，却忽略不同领域数据之间的差异。
- **关键词：** instruction-tuning

### DropBP: Accelerating Fine-Tuning of Large Language Models by Dropping Backward Propagation

- **作者：** Sunghyeon Woo, Baeseong Park, Byeongwook Kim, Minjung Jo, Se Jung Kwon, Dongsuk Jeon, Dongsoo Lee
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/240225294cdd2c9b692c2519d3278a08-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/240225294cdd2c9b692c2519d3278a08-Paper-Conference.pdf)
- **中文提要：** 大语言模型在多个领域取得了显著成功，不过训练过程中前向与反向传播都会带来很大的显存和计算成本。
- **关键词：** PEFT, fine-tuning

### Dual Risk Minimization: Towards Next-Level Robustness in Fine-tuning Zero-Shot Models

- **作者：** Kaican Li, Weiyan XIE, Yongxiang Huang, Didan Deng, Lanqing Hong, Zhenguo Li, Ricardo Silva, Nevin L. Zhang
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/7972f3735e104a54715922aa416fde1b-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/7972f3735e104a54715922aa416fde1b-Paper-Conference.pdf)
- **中文提要：** 微调基础模型常常会削弱它们对分布偏移的稳健性，为此多数稳健微调方法试图保留预训练特征。
- **关键词：** fine-tuning

### Efficient Multi-task LLM Quantization and Serving for Multiple LoRA Adapters

- **作者：** Yifei Xia, Fangcheng Fu, Wentao Zhang, Jiawei Jiang, Bin CUI
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/747dc7c6566c74eb9a663bcd8d057c78-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/747dc7c6566c74eb9a663bcd8d057c78-Paper-Conference.pdf)
- **中文提要：** 大语言模型要在多种下游任务上微调和部署，以 LoRA 为代表的参数高效微调，以及以 GPTQ、AWQ 为代表的量化，因此特别重要。
- **关键词：** LoRA, PEFT, fine-tuning

### Emotion-LLaMA: Multimodal Emotion Recognition and Reasoning with Instruction Tuning

- **作者：** Zebang Cheng, Zhi-Qi Cheng, Jun-Yan He, Kai Wang, Yuxiang Lin, Zheng Lian, Xiaojiang Peng, Alexander Hauptmann
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/c7f43ada17acc234f568dc66da527418-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/c7f43ada17acc234f568dc66da527418-Paper-Conference.pdf)
- **中文提要：** 准确感知情绪对人机交互、教育和咨询都很重要，传统单模态方法却常常无法覆盖现实中复杂的多模态情绪表达。现有多模态大模型还难以整合音频，也难以识别细微的面部信息。
- **关键词：** instruction-tuning, alignment

### Exploratory Retrieval-Augmented Planning For Continual Embodied Instruction Following

- **作者：** Minjong Yoo, Jinwoo Jang, Wei-Jin Park, Honguk Woo
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/7bacd0ebd061d4694583ae0eb69ad15f-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/7bacd0ebd061d4694583ae0eb69ad15f-Paper-Conference.pdf)
- **中文提要：** 为应对动态、非平稳环境中具身智能体的持续指令跟随，ExRAP 通过高效探索物理环境并建立环境上下文记忆，增强大语言模型的具身推理。
- **关键词：** instruction-following

### Federated Fine-tuning of Large Language Models under Heterogeneous Tasks and Client Resources

- **作者：** Jiamu Bai, Daoyuan Chen, Bingchen Qian, Liuyi Yao, Yaliang Li
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/1a134b50202088aa8c595cc99b310e5a-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/1a134b50202088aa8c595cc99b310e5a-Paper-Conference.pdf)
- **中文提要：** 把联邦学习用于大语言模型的参数高效微调时，客户端的资源与数据分布并不一致。FlexLoRA 作为一种聚合方案，用来缓解传统联邦学习中限制潜力的木桶效应。
- **关键词：** LoRA, PEFT, fine-tuning

### Fine-Tuning is Fine, if Calibrated

- **作者：** Zheda Mai, Arpita Chowdhury, Ping Zhang, Cheng-Hao Tu, Hong-You Chen, Vardaan Pahuja, Tanya Berger-Wolf, Song Gao, Charles Stewart, Yu Su, Wei-Lun (Harry) Chao
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/f573c36434796efe066d2f4cf3349e7f-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/f573c36434796efe066d2f4cf3349e7f-Paper-Conference.pdf)
- **中文提要：** 微调是把预训练模型接到下游应用最直接的办法，但也可能丢掉预训练阶段获得的知识。例如，让原本能识别大量类别的分类器只掌握手头的类别子集时，模型原有表现会明显变差。
- **关键词：** fine-tuning

### Fine-Tuning Large Vision-Language Models as Decision-Making Agents via Reinforcement Learning

- **作者：** Simon Zhai, Hao Bai, Zipeng Lin, Jiayi Pan, Peter Tong, Yifei Zhou, Alane Suhr, Saining Xie, Yann LeCun, Yi Ma, Sergey Levine
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/c848b7d3adc08fcd0bf1df3101ba6728-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/c848b7d3adc08fcd0bf1df3101ba6728-Paper-Conference.pdf)
- **中文提要：** 在专门的视觉指令数据上微调后，大视觉语言模型展现出较强的语言推理，但这套范式未必能从交互环境中高效学到多步、目标导向任务里的决策智能体。
- **关键词：** instruction-following, fine-tuning

### FLoRA: Federated Fine-Tuning Large Language Models with Heterogeneous Low-Rank Adaptations

- **作者：** Ziyao Wang, Zheyu Shen, Yexiao He, Guoheng Sun, Hongyi Wang, Lingjuan Lyu, Ang Li
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/28312c9491d60ed0c77f7fff4ad86dd1-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/28312c9491d60ed0c77f7fff4ad86dd1-Paper-Conference.pdf)
- **中文提要：** 预训练大语言模型可通过微调适配多样的下游任务，联邦学习则进一步让客户端就地计算、无需移动数据，从而以更顾及隐私的方式完成微调。
- **关键词：** LoRA, fine-tuning

### FM-Delta: Lossless Compression for Storing Massive Fine-tuned Foundation Models

- **作者：** Wanyi Ning, Jingyu Wang, Qi Qi, Mengde Zhu, Haifeng Sun, Daixuan Cheng, Jianxin Liao, Ce Zhang
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/7b75a7339dfb256ee4b4bec028a6890b-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/7b75a7339dfb256ee4b4bec028a6890b-Paper-Conference.pdf)
- **中文提要：** 预训练基础模型、尤其是大语言模型的成功，带来了大量微调变体。这些模型通常在本地微调后，由用户上传到云平台以便安全存储。
- **关键词：** fine-tuning

### FouRA: Fourier Low-Rank Adaptation

- **作者：** Shubhankar Borse, Shreya Kadambi, Nilesh Pandey, Kartikeya Bhardwaj, Viswanath Ganapathy, Sweta Priyadarshi, Risheek Garrepalli, Rafael Esteves, Munawar Hayat, Fatih Porikli
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/83960718b4d12f799985206f1b1cf00f-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/83960718b4d12f799985206f1b1cf00f-Paper-Conference.pdf)
- **中文提要：** 用 LoRA 微调文生图扩散模型时，生成图像往往缺乏多样性，模型倾向于复制见过的训练样本。适配器强度更高、秩更大，或是在更小数据上微调时，这一现象更突出。
- **关键词：** LoRA, fine-tuning

### Geometric-Averaged Preference Optimization for Soft Preference Labels

- **作者：** Hiroki Furuta, Kuang-Huei Lee, Shixiang (Shane) Gu, Yutaka Matsuo, Aleksandra Faust, Heiga Zen, Izzeddin Gur
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/688c7a82e31653e7c256c6c29fd3b438-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/688c7a82e31653e7c256c6c29fd3b438-Paper-Conference.pdf)
- **中文提要：** 许多对齐算法假定人类偏好是二元且确定的，但偏好会因人而异，更适合用分布来表示。该工作提出分布式软偏好标签，并在损失里对大语言模型输出似然做加权几何平均，以此改进 DPO。
- **关键词：** DPO, preference-optimization, alignment

### Getting More Juice Out of the SFT Data: Reward Learning from Human Demonstration Improves SFT for LLM Alignment

- **作者：** Jiaxiang Li, Siliang Zeng, Hoi-To Wai, Chenliang Li, Alfredo Garcia, Mingyi Hong
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/e0c9b65fb3e41aaa86576df3ec33ad2e-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/e0c9b65fb3e41aaa86576df3ec33ad2e-Paper-Conference.pdf)
- **中文提要：** 对齐人类偏好与价值时，RLHF 一类流程通常先用人类示范做监督微调（SFT），再用偏好数据学习奖励模型。
- **关键词：** RLHF, SFT, reward-model, alignment, fine-tuning

### Group Robust Preference Optimization in Reward-free RLHF

- **作者：** Shyam Sundhar Ramesh, Yifan Hu, Iason Chaimalas, Viraj Mehta, Pier Giuseppe Sessa, Haitham Bou Ammar, Ilija Bogunovic
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/4147dfaa46cd7e20a2aecb91097ae8cc-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/4147dfaa46cd7e20a2aecb91097ae8cc-Paper-Conference.pdf)
- **中文提要：** 针对特定任务微调大语言模型时，常用偏好数据上的 RLHF，而这些偏好往往来自不同标注群体。传统做法却一刀切，不加区分地按单一假设进行优化。
- **关键词：** GRPO, DPO, RLHF, preference-optimization, fine-tuning

### HelpSteer 2: Open-source dataset for training top-performing reward models

- **作者：** Zhilin Wang, Yi Dong, Olivier Delalleau, Jiaqi Zeng, Gerald Shen, Daniel Egert, Jimmy Zhang, Makesh Narsimhan Sreedhar, Oleksii Kuchaiev
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/02fd91a387a6a5a5751e81b58a75af90-Abstract-Datasets_and_Benchmarks_Track.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/02fd91a387a6a5a5751e81b58a75af90-Paper-Datasets_and_Benchmarks_Track.pdf)
- **中文提要：** 高质量偏好数据对于训练奖励模型至关重要，这些奖励模型要引导大语言模型生成符合人类偏好的回答。随着模型更强、对齐更好，Open Assistant、HH-RLHF 和 HelpSteer 等宽松许可的偏好数据也需要更新，才能继续用于奖励建模。
- **关键词：** RLHF, reward-model, alignment

### HydraLoRA: An Asymmetric LoRA Architecture for Efficient Fine-Tuning

- **作者：** Chunlin Tian, Zhan Shi, Zhijiang Guo, Li Li, Cheng-Zhong Xu
- **会议：** NeurIPS 2024 · Main · Oral
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/123fd8a56501194823c8e0dca00733df-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/123fd8a56501194823c8e0dca00733df-Paper-Conference.pdf)
- **中文提要：** 借助 LoRA 等参数高效微调，把大语言模型适配到新任务已经更省参数，但面对复杂数据时，这类方法常常仍不如全量微调。
- **关键词：** LoRA, PEFT, fine-tuning

### InfoRM: Mitigating Reward Hacking in RLHF via Information-Theoretic Reward Modeling

- **作者：** Yuchun Miao, Sen Zhang, Liang Ding, Rong Bao, Lefei Zhang, Dacheng Tao
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/f25d75fc760aec0a6174f9f5d9da59b8-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/f25d75fc760aec0a6174f9f5d9da59b8-Paper-Conference.pdf)
- **中文提要：** 尽管 RLHF 能把语言模型对齐到人类价值，奖励黑客（也称奖励过优化）仍然是关键难题。其主要原因是奖励误泛化：奖励模型使用了与人类偏好无关的虚假特征来计算奖励。
- **关键词：** RLHF, reward-model, alignment

### Instruction Tuning Large Language Models to Understand Electronic Health Records

- **作者：** Zhenbang Wu, Anant Dadu, Michael Nalls, Faraz Faghri, Jimeng Sun
- **会议：** NeurIPS 2024 · Main · Spotlight
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/62986e0a78780fe5f17b495aeded5bab-Abstract-Datasets_and_Benchmarks_Track.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/62986e0a78780fe5f17b495aeded5bab-Paper-Datasets_and_Benchmarks_Track.pdf)
- **中文提要：** 大语言模型已经能按人类指令处理多种任务，但要做成电子健康记录上的对话助手仍然困难，既缺少大规模指令跟随数据，现有架构也难以应对复杂、异质的病历。
- **关键词：** instruction-tuning, instruction-following, fine-tuning

### Instruction Tuning With Loss Over Instructions

- **作者：** Zhengxiang Shi, Adam Yang, Bin Wu, Laurence Aitchison, Emine Yilmaz, Aldo Lipani
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/7ffb43adf37b3eeaba559098bc084cc6-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/7ffb43adf37b3eeaba559098bc084cc6-Paper-Conference.pdf)
- **中文提要：** 指令微调关系到语言模型能否按期望风格输出。Instruction Modelling 在训练时把损失用在指令和提示部分，而不是只监督输出部分。
- **关键词：** instruction-tuning, alignment

### Iterative Reasoning Preference Optimization

- **作者：** Richard Yuanzhe Pang, Weizhe Yuan, He He, Kyunghyun Cho, Sainbayar Sukhbaatar, Jason Weston
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/d37c9ad425fe5b65304d500c6edcba00-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/d37c9ad425fe5b65304d500c6edcba00-Paper-Conference.pdf)
- **中文提要：** 迭代式偏好优化在一般指令微调上表现较好，对推理任务通常却改进很少。这里的迭代方法在相互竞争的生成思维链候选之间优化偏好。
- **关键词：** DPO, instruction-tuning, preference-optimization

### Keeping LLMs Aligned After Fine-tuning: The Crucial Role of Prompt Templates

- **作者：** Kaifeng Lyu, Haoyu Zhao, Xinran Gu, Dingli Yu, Anirudh Goyal, Sanjeev Arora
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/d6f034bb216b472fc7d32ec7aff20342-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/d6f034bb216b472fc7d32ec7aff20342-Paper-Conference.pdf)
- **中文提要：** Llama 2-Chat 等公开大语言模型经过对齐训练，曾被认为是安全的。
- **关键词：** alignment, fine-tuning

### KG-FIT: Knowledge Graph Fine-Tuning Upon Open-World Knowledge

- **作者：** Pengcheng Jiang, Lang Cao, Cao (Danica) Xiao, Parminder Bhatia, Jimeng Sun, Jiawei Han
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/f606d45ae7b991988b6eea2af38b7057-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/f606d45ae7b991988b6eea2af38b7057-Paper-Conference.pdf)
- **中文提要：** 知识图谱嵌入为实体和关系学习紧凑表示，从而支持高效推理与知识发现。已有工作或只根据图结构训练嵌入，或用图谱中的分类数据微调预训练语言模型，KG-FIT 则利用大语言模型引导的精炼。
- **关键词：** fine-tuning

### LACIE: Listener-Aware Finetuning for Calibration in Large Language Models

- **作者：** Elias Stengel-Eskin, Peter Hase, Mohit Bansal
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/4b8eaf3bcdc105423a972ed90eb07217-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/4b8eaf3bcdc105423a972ed90eb07217-Paper-Conference.pdf)
- **中文提要：** 大语言模型回答问题时，除答案本身外还会传达该答案正确的把握程度，其中包括显式的信心标记。
- **关键词：** preference-optimization, fine-tuning

### Learning Goal-Conditioned Representations for Language Reward Models

- **作者：** Vaskar Nath, Dylan Slack, Jeff Da, Yuntao Ma, Hugh Zhang, Spencer Whitehead, Sean Hendryx
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/d46f127a80dc58cbc0732a717285c43a-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/d46f127a80dc58cbc0732a717285c43a-Paper-Conference.pdf)
- **中文提要：** 借助离线数据或自监督目标改进表征，在传统强化学习中效果突出，但这种表征学习能否帮助语言上的人类反馈强化学习仍不明确。该工作提议以对比式、目标条件化的方式训练奖励模型。
- **关键词：** RLHF, reward-model, alignment, fine-tuning

### LISA: Layerwise Importance Sampling for Memory-Efficient Large Language Model Fine-Tuning

- **作者：** Rui Pan, Xiang Liu, SHIZHE DIAO, Renjie Pi, Jipeng Zhang, Chi Han, Tong Zhang
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/687163285b8affc8ee933bdca8e75747-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/687163285b8affc8ee933bdca8e75747-Paper-Conference.pdf)
- **中文提要：** 大语言模型出现后机器学习进展显著，但巨大的显存消耗已经成为大规模训练的重要阻碍。
- **关键词：** LoRA, PEFT, fine-tuning

### Lisa: Lazy Safety Alignment for Large Language Models against Harmful Fine-tuning Attack

- **作者：** Tiansheng Huang, Sihao Hu, Fatih Ilhan, Selim Tekin, Ling Liu
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/bcfdaf04b54a69f47623c973c864ee8d-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/bcfdaf04b54a69f47623c973c864ee8d-Paper-Conference.pdf)
- **中文提要：** 带安全对齐的大语言模型，若在混有有害数据的集合上微调，仍可能被越狱。把微调阶段拆开，分别在对齐数据与用户数据上优化，可以减轻这种越狱效应。
- **关键词：** alignment, fine-tuning

### LoFiT: Localized Fine-tuning on LLM Representations

- **作者：** Fangcong Yin, Xi Ye, Greg Durrett
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/122ea6470232ee5e79a2649243348005-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/122ea6470232ee5e79a2649243348005-Paper-Conference.pdf)
- **中文提要：** 可解释性方面的近期工作表明，可以不经学习就适配大语言模型：干预其内部表示即可引出对齐所需要的行为。例如，给某些注意力头的输出加上特定偏置向量，据报道能够提升真实性。
- **关键词：** LoRA, PEFT, alignment, fine-tuning

### LoRA-GA: Low-Rank Adaptation with Gradient Approximation

- **作者：** Shaowen Wang, Linxi Yu, Jian Li
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/62c4718cc334f6a0a62fb81c4a2095a1-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/62c4718cc334f6a0a62fb81c4a2095a1-Paper-Conference.pdf)
- **中文提要：** 大规模预训练模型的全量微调在计算和显存上代价过高。作为常见的参数高效微调方法，LoRA 改为微调一个参数少得多的辅助低秩模型。
- **关键词：** LoRA, PEFT, fine-tuning

### Membership Inference Attacks against Fine-tuned Large Language Models via Self-prompt Calibration

- **作者：** Wenjie Fu, Huandong Wang, Chen Gao, Guanghua Liu, Yong Li, Tao Jiang
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/f36ad694188bb4c4bbbd61e2038e069e-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/f36ad694188bb4c4bbbd61e2038e069e-Paper-Conference.pdf)
- **中文提要：** 成员推断攻击旨在判断某条目标数据是否参与了模型训练。面向大语言模型的现有攻击，有的不使用参考模型，有的则依赖参考模型。
- **关键词：** fine-tuning

### MetaAligner: Towards Generalizable Multi-Objective Alignment of Language Models

- **作者：** Kailai Yang, Zhiwei Liu, Qianqian Xie, Jimin Huang, Tianlin Zhang, Sophia Ananiadou
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/3d03800841fa1bb2f43ef1750aafcce4-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/3d03800841fa1bb2f43ef1750aafcce4-Paper-Conference.pdf)
- **中文提要：** 多目标偏好对齐试图让大语言模型适应各不相同的人类期望与价值。现有方法却依赖策略模型参数，每换一个新策略就要高成本重跑对齐算法，而且对齐目标是静态的，无法扩展到未见过的目标。
- **关键词：** preference-optimization, alignment

### Mitigating Reward Overoptimization via Lightweight Uncertainty Estimation

- **作者：** Xiaoying Zhang, Jean-Francois Ton, Wei Shen, Hongning Wang, Yang Liu
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/94bbcb744bbada8808fda05b9d9290d6-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/94bbcb744bbada8808fda05b9d9290d6-Paper-Conference.pdf)
- **中文提要：** 人类反馈强化学习对把大语言模型对齐到人类价值很关键，但因为依赖代理奖励模型，常常出现过优化。为此先提出一种轻量的不确定性量化，仅用奖励模型最后一层嵌入来评估代理奖励是否可靠。
- **关键词：** RLHF, reward-model, alignment

### MMDU: A Multi-Turn Multi-Image Dialog Understanding Benchmark and Instruction-Tuning Dataset for LVLMs

- **作者：** Ziyu Liu, Tao Chu, Yuhang Zang, Xilin Wei, Xiaoyi Dong, Pan Zhang, Zijian Liang, Yuanjun Xiong, Yu Qiao, Dahua Lin, Jiaqi Wang
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/1057053100de064a44286239724f7865-Abstract-Datasets_and_Benchmarks_Track.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/1057053100de064a44286239724f7865-Paper-Datasets_and_Benchmarks_Track.pdf)
- **中文提要：** 根据多模态人类输入生成自然且有意义的回复，是大视觉语言模型的基本能力。开源模型在单轮单图等简化场景中已有不错表现，但在带有长上下文历史的多轮真实对话中跟随指令仍然不足。
- **关键词：** instruction-tuning, fine-tuning

### Model Fusion through Bayesian Optimization in Language Model Fine-Tuning

- **作者：** Chaeyun Jang, Hyungi Lee, Jungtaek Kim, Juho Lee
- **会议：** NeurIPS 2024 · Main · Spotlight
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/34d3cf97696022b179171e5abda42c0b-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/34d3cf97696022b179171e5abda42c0b-Paper-Conference.pdf)
- **中文提要：** 为下游任务微调预训练模型因其适应性和可靠性而被广泛采用。尽管概念简单，微调仍涉及不少棘手的工程选择，例如挑选超参数，以及从一条优化轨迹中确定检查点。
- **关键词：** fine-tuning

### Multi-turn Reinforcement Learning with Preference Human Feedback

- **作者：** Lior Shani, Aviv Rosenberg, Asaf Cassel, Oran Lang, Daniele Calandriello, Avital Zipori, Hila Noga, Orgad Keller, Bilal Piot, Idan Szpektor, Avinatan Hassidim, Yossi Matias, Remi Munos
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/d77a7b289361abff82bdd2fb537ae152-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/d77a7b289361abff82bdd2fb537ae152-Paper-Conference.pdf)
- **中文提要：** 人类反馈强化学习已成为对齐大语言模型与人类偏好的标准做法。现有方法只在单步决策层面模仿人类偏好，因此在需要规划或多轮交互的场景中能力有限。
- **关键词：** RLHF, alignment

### Navigating the Safety Landscape: Measuring Risks in Finetuning Large Language Models

- **作者：** ShengYun Peng, Pin-Yu Chen, Matthew Hull, Duen Horng Chau
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/ada93fa6643735f294be51dc31eebbd4-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/ada93fa6643735f294be51dc31eebbd4-Paper-Conference.pdf)
- **中文提要：** 安全对齐确保大语言模型的行为符合人类偏好，并在推理时避免有害动作。近期研究却表明，只用少量经过对抗设计的训练样本做微调，就可能轻易破坏这种对齐。
- **关键词：** alignment, fine-tuning

### Noise Contrastive Alignment of Language Models with Explicit Rewards

- **作者：** Huayu Chen, Guande He, Lifan Yuan, Ganqu Cui, Hang Su, Jun Zhu
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/d5a58d198afa370a3dff0e1ca4fe1802-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/d5a58d198afa370a3dff0e1ca4fe1802-Paper-Conference.pdf)
- **中文提要：** 微调语言模型时，用户意图通常被形式化为需要最大化的评价奖励。DPO 等现有对齐方法主要针对成对偏好数据，其中奖励是隐式定义的，而不是显式给出。
- **关键词：** DPO, preference-optimization, alignment, fine-tuning

### OmniJARVIS: Unified Vision-Language-Action Tokenization Enables Open-World Instruction Following Agents

- **作者：** Zihao Wang, Shaofei Cai, Zhancun Mu, Haowei Lin, Ceyao Zhang, Xuejie Liu, Qing Li, Anji Liu, Xiaojian (Shawn) Ma, Yitao Liang
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/85f1225db986e629289f402c46eff1a4-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/85f1225db986e629289f402c46eff1a4-Paper-Conference.pdf)
- **中文提要：** OmniJARVIS 是用于 Minecraft 开放世界指令跟随智能体的视觉-语言-动作模型。相比把文本目标交给独立控制器，或直接输出控制指令，它通过对多模态交互数据做统一词元化，同时追求较强推理与高效决策。
- **关键词：** instruction-following

### Online Iterative Reinforcement Learning from Human Feedback with General Preference Model

- **作者：** Chenlu Ye, Wei Xiong, Yuheng Zhang, Hanze Dong, Nan Jiang, Tong Zhang
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/94d13c2401fe119e57ba325b6fe526e0-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/94d13c2401fe119e57ba325b6fe526e0-Paper-Conference.pdf)
- **中文提要：** 该研究在一般偏好预言机的条件下讨论 RLHF，并不像多数先前工作那样假设存在奖励函数，也不假设预言机的偏好信号来自 Bradley-Terry 模型。
- **关键词：** RLHF

### On Softmax Direct Preference Optimization for Recommendation

- **作者：** Yuxin Chen, Junfei Tan, An Zhang, Zhengyi Yang, Leheng Sheng, Enzhi Zhang, Xiang Wang, Tat-Seng Chua
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/30732ddb12d9faf7180f5d0e8b5b5da7-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/30732ddb12d9faf7180f5d0e8b5b5da7-Paper-Conference.pdf)
- **中文提要：** 推荐系统希望依据用户偏好数据预测个性化排序。随着语言模型兴起，因其丰富的世界知识与较强推理能力，基于语言模型的推荐得到了广泛探索。
- **关键词：** DPO, preference-optimization, alignment, fine-tuning

### OpenMathInstruct-1: A 1.8 Million Math Instruction Tuning Dataset

- **作者：** Shubham Toshniwal, Ivan Moshkov, Sean Narenthiran, Daria Gitman, Fei Jia, Igor Gitman
- **会议：** NeurIPS 2024 · Main · Oral
- **官方论文页：** https://neurips.cc/virtual/2024/oral/98022
- **中文提要：** 合成数据在训练大语言模型、尤其是获得针对性技能方面展现出很大潜力。当前大规模数学指令微调数据，例如 MetaMathQA 和 MAmmoTH，是用许可受限的闭源大模型输出构造的。
- **关键词：** instruction-tuning

### Personalized Steering of Large Language Models: Versatile Steering Vectors Through Bi-directional Preference Optimization

- **作者：** Yuanpu Cao, Tianrong Zhang, Bochuan Cao, Ziyi Yin, Lu Lin, Fenglong Ma, Jinghui Chen
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/58cbe393b4254da8966780a40d023c0b-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/58cbe393b4254da8966780a40d023c0b-Paper-Conference.pdf)
- **中文提要：** 研究者一直在探索如何引导大语言模型的行为，并构建面向不同应用的个性化模型。微调虽然直接，但需要大量计算资源，还可能明显影响原模型的效用。
- **关键词：** preference-optimization, alignment, fine-tuning

### Personalizing Reinforcement Learning from Human Feedback with Variational Preference Learning

- **作者：** Sriyash Poddar, Yanming Wan, Hamish Ivison, Abhishek Gupta, Natasha Jaques
- **会议：** NeurIPS 2024 · Main · Spotlight
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/5e1c255653eb98cef13f45b2d337c882-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/5e1c255653eb98cef13f45b2d337c882-Paper-Conference.pdf)
- **中文提要：** 人类反馈强化学习能够把基础模型对齐到人类价值与偏好，但现有技术还无法考虑不同个体之间自然存在的偏好差异。
- **关键词：** RLHF, reward-model, alignment

### Preference Alignment with Flow Matching

- **作者：** Minu Kim, Yongsik Lee, Sehyeok Kang, Jihwan Oh, Song Chong, Se-Young Yun
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/3df874367ce2c43891aab1ab23ae6959-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/3df874367ce2c43891aab1ab23ae6959-Paper-Conference.pdf)
- **中文提要：** Preference Flow Matching 提供一种偏好对齐框架，便于把偏好接入任意一类预训练模型。已有对齐方法需要微调，从而带来可扩展性、效率以及必须改动模型的问题，面对 GPT-4 这类黑盒接口时尤其如此。
- **关键词：** preference-optimization, reward-model, alignment, fine-tuning

### Preference Learning Algorithms Do Not Learn Preference Rankings

- **作者：** Angelica Chen, Sadhika Malladi, Lily Zhang, Xinyi Chen, Qiuyi (Richard) Zhang, Rajesh Ranganath, Kyunghyun Cho
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/b8ce770a6b25e603fbff4a37f9e31edc-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/b8ce770a6b25e603fbff4a37f9e31edc-Paper-Conference.pdf)
- **中文提要：** RLHF、DPO 等偏好学习算法常被用来引导大语言模型生成更符合人类偏好的内容，但人们对其内部机制的理解仍然有限。这项工作检验一种通行看法：偏好学习会训练模型给更受偏好的输出赋予更高似然，并通过排序来衡量。
- **关键词：** DPO, RLHF, alignment

### Provably Mitigating Overoptimization in RLHF: Your SFT Loss is Implicitly an Adversarial Regularizer

- **作者：** Zhihan Liu, Miao Lu, Shenao Zhang, Boyi Liu, Hongyi Guo, Yingxiang Yang, Jose Blanchet, Zhaoran Wang
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/fa69e968b7319fd42524febd41475fb3-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/fa69e968b7319fd42524febd41475fb3-Paper-Conference.pdf)
- **中文提要：** 借助 RLHF 按人类偏好对齐生成模型时，通常会遇到过优化：学得不完美的奖励模型可能误导生成模型，输出更不希望看到的回答。该工作从原理上把原因归结为数据集中人类偏好的分布偏移与不确定性。
- **关键词：** DPO, RLHF, SFT, preference-optimization, reward-model, alignment

### QuanTA: Efficient High-Rank Fine-Tuning of LLMs with Quantum-Informed Tensor Adaptation

- **作者：** Zhuo Chen, Rumen Dangovski, Charlotte Loh, Owen Dugan, Di Luo, Marin Soljacic
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/a7c17115db36193f6b83b71b0fe1d416-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/a7c17115db36193f6b83b71b0fe1d416-Paper-Conference.pdf)
- **中文提要：** QuanTA 是一种易于实现、且没有推理额外开销的微调方法，面向大规模预训练语言模型。它借助源自量子电路结构的量子启发手段，实现高效的高秩微调，从而应对 LoRA 低秩近似可能失效的情况。
- **关键词：** LoRA, fine-tuning

### RaVL: Discovering and Mitigating Spurious Correlations in Fine-Tuned Vision-Language Models

- **作者：** Maya Varma, Jean-Benoit Delbrouck, Zhihong Chen, Akshay Chaudhari, Curtis Langlotz
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/95c6ae3f3393786203a4b6dcb9df1036-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/95c6ae3f3393786203a4b6dcb9df1036-Paper-Conference.pdf)
- **中文提要：** 微调后的视觉语言模型经常捕捉到图像特征与文本属性之间的虚假相关，导致测试时零样本性能下降。现有处理虚假相关的方法多在整幅图像层面操作，而不是直接干预细粒度图像特征，并且主要是为单模态设定设计的。
- **关键词：** fine-tuning

### ReFT: Representation Finetuning for Language Models

- **作者：** Zhengxuan Wu, Aryaman Arora, Zheng Wang, Atticus Geiger, Dan Jurafsky, Christopher D Manning, Christopher Potts
- **会议：** NeurIPS 2024 · Main · Spotlight
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/75008a0fba53bf13b0bb3b7bff986e0e-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/75008a0fba53bf13b0bb3b7bff986e0e-Paper-Conference.pdf)
- **中文提要：** 参数高效微调试图只更新少量权重来适配大型神经网络。大量可解释性研究表明表示编码了丰富语义，这意味着编辑表示或许是更有力的替代方案。
- **关键词：** instruction-tuning, LoRA, PEFT, fine-tuning

### Regularized Conditional Diffusion Model for Multi-Task Preference Alignment

- **作者：** Xudong Yu, Chenjia Bai, Haoran He, Changhong Wang, Xuelong Li
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/fceae9d27e68e183d71aaa88030f52ee-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/fceae9d27e68e183d71aaa88030f52ee-Paper-Conference.pdf)
- **中文提要：** 序列决策可以表述为条件生成过程，既要对齐人类意图，也要在不同任务间保持通用。以往按回报条件化的扩散模型表现相当，但依赖定义清楚的奖励函数，既需要可观的人力，在多任务场景中也面临挑战。
- **关键词：** preference-optimization, alignment

### Regularizing Hidden States Enables Learning Generalizable Reward Model for LLMs

- **作者：** Rui Yang, Ruomeng Ding, Yong Lin, Huan Zhang, Tong Zhang
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/71f7154547c748c8041505521ca433ab-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/71f7154547c748c8041505521ca433ab-Paper-Conference.pdf)
- **中文提要：** 在人类偏好数据上训练的奖励模型，可以在 RLHF 框架下把大语言模型对齐到人类意图。然而当前奖励模型对未见提示和回复的泛化有限，可能引发奖励过优化，并随之出现下滑。
- **关键词：** RLHF, reward-model

### ReMoDetect: Reward Models Recognize Aligned LLM's Generations

- **作者：** Hyunseok Lee, Jihoon Tack, Jinwoo Shin
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/058373e239c542eae6cb796e4dc521da-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/058373e239c542eae6cb796e4dc521da-Paper-Conference.pdf)
- **中文提要：** 大语言模型能力突出且容易获取，虚假新闻等社会风险明显上升，因而需要能检测模型生成文本的方法。由于模型数量庞大，逐一覆盖并不现实。
- **关键词：** reward-model, alignment, fine-tuning

### Representation Noising: A Defence Mechanism Against Harmful Finetuning

- **作者：** Domenic Rosati, Jan Wehner, Kai Williams, Lukasz Bartoszcze, Robie Gonzales, carsten maple, Subhabrata Majumdar, Hassan Sajjad, Frank Rudzicz
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/172be8b0b88fc2b4aee74237d43f8c04-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/172be8b0b88fc2b4aee74237d43f8c04-Paper-Conference.pdf)
- **中文提要：** 发布开源大语言模型带来双重用途风险，因为不良行为者可以轻易把这些模型微调用于有害目的。即便不公开权重，权重窃取和微调接口也会使闭源模型面临有害微调攻击。
- **关键词：** fine-tuning

### ReST-MCTS*: LLM Self-Training via Process Reward Guided Tree Search

- **作者：** Dan Zhang, Sining Zhoubian, Ziniu Hu, Yisong Yue, Yuxiao Dong, Jie Tang
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/76ec4dc30e9faaf0e4b6093eaa377218-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/76ec4dc30e9faaf0e4b6093eaa377218-Paper-Conference.pdf)
- **中文提要：** 近期的大语言模型自训练多依赖模型自己生成回答，并筛出最终答案正确的样本作为训练数据。这种做法得到的微调训练集质量常常不高，例如计划或中间推理步骤是错的。
- **关键词：** PRM, reward-model, self-rewarding, fine-tuning

### Rethinking Weight Decay for Robust Fine-Tuning of Foundation Models

- **作者：** Junjiao Tian, Chengyue Huang, Zsolt Kira
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/281a6b49c66b94f81f3b1ae8f1a0dea4-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/281a6b49c66b94f81f3b1ae8f1a0dea4-Paper-Conference.pdf)
- **中文提要：** 配备动量和自适应学习率的现代优化器（如 AdamW）旨在逃离局部极小、探索广阔的参数空间。从头训练时，这种探索有助于找到较好的损失盆地。
- **关键词：** fine-tuning

### Risk-Averse Fine-tuning of Large Language Models

- **作者：** Sapana Chaudhary, Ujwal Dinesha, Dileep Kalathil, Srinivas Shakkottai
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/c182ec594f38926b7fcb827635b9a8f4-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/c182ec594f38926b7fcb827635b9a8f4-Paper-Conference.pdf)
- **中文提要：** 如何减少大语言模型在某些提示下生成负面或有毒内容，是这里关注的问题。把风险厌恶原则融入微调，目的是降低有害输出的出现，尤其是那些罕见但影响重大的事件。
- **关键词：** RLHF, fine-tuning

### Robust Reinforcement Learning from Corrupted Human Feedback

- **作者：** Alexander Bukharin, Ilgee Hong, Haoming Jiang, Zichong Li, Qingru Zhang, Zixuan Zhang, Tuo Zhao
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/e04101138a3c94544760c1dbdf2c7a2d-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/e04101138a3c94544760c1dbdf2c7a2d-Paper-Conference.pdf)
- **中文提要：** 人类反馈强化学习为用偏好数据对齐人工智能系统提供了原则性框架。标注者却可能因为个人偏见、语境含糊或缺乏训练，给出错误或不一致的偏好标签。
- **关键词：** DPO, RLHF, preference-optimization, alignment

### S$^{2}$FT: Efficient, Scalable and Generalizable LLM Fine-tuning by Structured Sparsity

- **作者：** Xinyu Yang, Jixuan Leng, Geyang Guo, Jiawei Zhao, Ryumei Nakada, Linjun Zhang, Huaxiu Yao, Beidi Chen
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/6e3b9fb0c0c56cf6e1ee61e6a068fca4-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/6e3b9fb0c0c56cf6e1ee61e6a068fca4-Paper-Conference.pdf)
- **中文提要：** 现有面向大语言模型的参数高效微调方法，可以做到高质量、训练高效或服务可扩展，但难以同时满足这三点。为突破这一限制，作者考察稀疏微调，并观察到泛化能力有所改善。
- **关键词：** instruction-tuning, LoRA, PEFT, fine-tuning

### Safe LoRA: The Silver Lining of Reducing Safety Risks when Finetuning Large Language Models

- **作者：** Chia-Yi Hsu, Yu-Lin Tsai, Chih-Hsun Lin, Pin-Yu Chen, Chia-Mu Yu, Chun-Ying Huang
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/77baa7c2a3a675823e89131698fd6e19-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/77baa7c2a3a675823e89131698fd6e19-Paper-Conference.pdf)
- **中文提要：** Llama-2、GPT-4 等大语言模型的零样本能力已经很强，但面向定制数据、领域任务或其他私有需求，微调仍然必要。全参数微调对硬件要求很高，普通用户往往难以承担。
- **关键词：** LoRA, PEFT, fine-tuning

### Scaling Laws for Reward Model Overoptimization in Direct Alignment Algorithms

- **作者：** Rafael Rafailov, Yaswanth Chittepu, Ryan Park, Harshit Sushil Sikchi, Joey Hejna, Brad Knox, Chelsea Finn, Scott Niekum
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/e45caa3d5273d105b8d045e748636957-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/e45caa3d5273d105b8d045e748636957-Paper-Conference.pdf)
- **中文提要：** 人类反馈强化学习对大语言模型近来的成功至关重要，但整个过程常常复杂且脆弱。经典框架中，先训练奖励模型来表示人类偏好，再由在线强化学习算法据此优化语言模型。
- **关键词：** DPO, RLHF, preference-optimization, reward-model, alignment

### SelectIT: Selective Instruction Tuning for LLMs via Uncertainty-Aware Self-Reflection

- **作者：** Liangxin Liu, Xuebo Liu, Derek Wong, Dongfang Li, Ziyi Wang, Baotian Hu, Min Zhang
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/b130a5691815f550977e331f8bec08ae-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/b130a5691815f550977e331f8bec08ae-Paper-Conference.pdf)
- **中文提要：** 指令微调把大语言模型调向面向人的交互。已有进展表明，从指令数据中仔细挑出少量高质量子集，就能提升模型表现。
- **关键词：** instruction-tuning

### Self-Play Fine-tuning of Diffusion Models for Text-to-image Generation

- **作者：** Huizhuo Yuan, Zixiang Chen, Kaixuan Ji, Quanquan Gu
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/860c1c657deafe09f64c013c2888bd7b-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/860c1c657deafe09f64c013c2888bd7b-Paper-Conference.pdf)
- **中文提要：** 与大语言模型相比，扩散模型的微调仍少有人深入。Stable Diffusion 和 SDXL 依赖监督微调，见到一定量数据后性能会趋于平台期。
- **关键词：** RLHF, SFT, preference-optimization, alignment, fine-tuning

### SHED: Shapley-Based Automated Dataset Refinement for Instruction Fine-Tuning

- **作者：** Yexiao He, Ziyao Wang, Zheyu Shen, Guoheng Sun, Yucong Dai, Yongkai Wu, Hongyi Wang, Ang Li
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/b3cff9947cde08b4fa70652cb8ac9209-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/b3cff9947cde08b4fa70652cb8ac9209-Paper-Conference.pdf)
- **中文提要：** 预训练大语言模型可通过微调适配下游任务，并进一步贴近人类偏好。已有研究发现少量高质量数据就够用，这暗示大规模数据里有不少冗余甚至有害样本。
- **关键词：** fine-tuning

### ShiftAddLLM: Accelerating Pretrained LLMs via Post-Training Multiplication-Less Reparameterization

- **作者：** Haoran You, Yipin Guo, Yichao Fu, Wei Zhou, Huihong Shi, Xiaofan Zhang, Souvik Kundu, Amir Yazdanbakhsh, Yingyan (Celine) Lin
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/2c30a37c75f062e0bf79297c73db8c6c-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/2c30a37c75f062e0bf79297c73db8c6c-Paper-Conference.pdf)
- **中文提要：** 大语言模型部署到资源受限设备时，庞大参数和密集乘法会拉高显存并造成延迟。移位加重新参数化试图用更硬件友好的基本运算替换昂贵的乘法。
- **关键词：** post-training, fine-tuning

### SimPO: Simple Preference Optimization with a Reference-Free Reward

- **作者：** Yu Meng, Mengzhou Xia, Danqi Chen
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/e099c1c9699814af0be873a175361713-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/e099c1c9699814af0be873a175361713-Paper-Conference.pdf)
- **中文提要：** DPO 把 RLHF 中的奖励函数重参数化，以简化离线偏好优化并稳住训练。这项工作提出 SimPO，作为一种更简单的偏好优化方法。
- **关键词：** DPO, SimPO, RLHF, instruction-tuning, preference-optimization

### SmallToLarge (S2L): Scalable Data Selection for Fine-tuning Large Language Models by Summarizing Training Trajectories of Small Models

- **作者：** Yu Yang, Siddhartha Mishra, Jeffrey Chiang, Baharan Mirzasoleiman
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/97fe251c25b6f99a2a23b330a75b11d4-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/97fe251c25b6f99a2a23b330a75b11d4-Paper-Conference.pdf)
- **中文提要：** 专业领域的监督微调（SFT）里，微调数据更复杂，数据选择的效率不好做。SmallToLarge（S2L）先训练一个小模型，再对损失进行聚类。
- **关键词：** SFT, fine-tuning

### Spectral Editing of Activations for Large Language Model Alignment

- **作者：** Yifu QIU, Zheng Zhao, Yftah Ziser, Anna Korhonen, Edoardo Maria Ponti, Shay Cohen
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/684c59d614fe6ae74a3be8c3ef07e061-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/684c59d614fe6ae74a3be8c3ef07e061-Paper-Conference.pdf)
- **中文提要：** 大语言模型常会生成不真实或带偏见的内容。在现有对齐方法之外，编辑其内部表示已被用来缓解这类行为。
- **关键词：** alignment

### Star-Agents: Automatic Data Optimization with LLM Agents for Instruction Tuning

- **作者：** Hang Zhou, Yehui Tang, Haochen Qin, Yujie Yang, Renren Jin, Deyi Xiong, Kai Han, Yunhe Wang
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/0852b88e96d973bd4e21b673f51621d0-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/0852b88e96d973bd4e21b673f51621d0-Paper-Conference.pdf)
- **中文提要：** 大语言模型在下游任务上的效果通常取决于指令微调，而指令微调又紧扣训练数据质量。收集既优质又多样的数据，成本高且耗时。
- **关键词：** instruction-tuning

### $\textit{Trans-LoRA}$: towards data-free Transferable Parameter Efficient Finetuning

- **作者：** Runqian Wang, Soumya Ghosh, David Cox, Diego Antognini, Aude Oliva, Rogerio Feris, Leonid Karlinsky
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/708fdc7911f11585ee7161518e509ae6-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/708fdc7911f11585ee7161518e509ae6-Paper-Conference.pdf)
- **中文提要：** LoRA 及其变体是流行的 PEFT 技术，只需少量额外参数就能接近全量微调的表现。这些额外参数是针对正在适配的基座模型的。
- **关键词：** LoRA, PEFT, fine-tuning

### The Impact of Initialization on LoRA Finetuning Dynamics

- **作者：** Soufiane Hayou, Nikhil Ghosh, Bin Yu
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/d4387c37b3b06e55f86eccdb8cd1f829-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/d4387c37b3b06e55f86eccdb8cd1f829-Paper-Conference.pdf)
- **中文提要：** 围绕 Hu 等人最初提出的低秩适配，这项研究考察初始化如何影响 LoRA 的微调动态。
- **关键词：** LoRA, fine-tuning

### The Importance of Online Data: Understanding Preference Fine-tuning via Coverage

- **作者：** Yuda Song, Gokul Swamy, Aarti Singh, J. Bagnell, Wen Sun
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/16c628ab12dc4caca8e7712affa6c767-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/16c628ab12dc4caca8e7712affa6c767-Paper-Conference.pdf)
- **中文提要：** 从人类偏好数据中学习，已成为微调大语言模型的主导范式。在线强化学习（如 PPO）与离线对比方法（如 DPO）曾被视作等价，理由只写到二者都得从某起点出发。
- **关键词：** DPO, preference-optimization, fine-tuning

### The Representation Landscape of Few-Shot Learning and Fine-Tuning in Large Language Models

- **作者：** Diego Doimo, Alessandro Serra, Alessio Ansuini, Alberto Cazzaniga
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/206018a258033def63607fbdf364bd2d-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/206018a258033def63607fbdf364bd2d-Paper-Conference.pdf)
- **中文提要：** 上下文学习（ICL）和监督微调（SFT）是提升大语言模型特定任务表现的两条常见路径。二者性质不同，却常常带来相近的性能增益。
- **关键词：** SFT, fine-tuning

### Thinking Forward: Memory-Efficient Federated Finetuning of Language Models

- **作者：** Kunjal Panchal, Nisarg Parikh, Sunav Choudhary, Lijun Zhang, Yuriy Brun, Hui Guan
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/7fc914993440219b64254e0c27964e11-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/7fc914993440219b64254e0c27964e11-Paper-Conference.pdf)
- **中文提要：** 联邦学习中微调大语言模型，能让资源受限设备用私有数据更新模型。反向传播所需显存过高，中间激活是主要来源。
- **关键词：** LoRA, fine-tuning

### Time-Varying LoRA: Towards Effective Cross-Domain Fine-Tuning of Diffusion Models

- **作者：** Zhan Zhuang, Yulong Zhang, Xuehao Wang, Jiangang Lu, Ying Wei, Yu Zhang
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/8716aa6a02bcc3c8e69a3a42be192236-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/8716aa6a02bcc3c8e69a3a42be192236-Paper-Conference.pdf)
- **中文提要：** 大规模扩散模型善于生成高保真图像，也便于做图像编辑和插值。一旦领域是动态且持续演变的，生成就会受到限制。
- **关键词：** LoRA, fine-tuning

### Towards Calibrated Robust Fine-Tuning of Vision-Language Models

- **作者：** Changdae Oh, Hyesu Lim, Mijoo Kim, Dongyoon Han, Sangdoo Yun, Jaegul Choo, Alexander Hauptmann, Zhi-Qi Cheng, Kyungwoo Song
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/173e4732a89fab9fb225203f35996677-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/173e4732a89fab9fb225203f35996677-Paper-Conference.pdf)
- **中文提要：** 对零样本模型做稳健微调，是为了在分布内适配的同时改善分布外泛化，而不是停留在朴素微调。近期方法的分布外泛化已经不错，但可靠输出所需的置信度校准仍未充分解决。
- **关键词：** fine-tuning

### Transfer Q-star : Principled Decoding for LLM Alignment

- **作者：** Souradip Chakraborty, Soumya Suvra Ghosal, Ming Yin, Dinesh Manocha, Mengdi Wang, Amrit Singh Bedi, Furong Huang
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/b8700a8a005032fe869c741b0a75274b-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/b8700a8a005032fe869c741b0a75274b-Paper-Conference.pdf)
- **中文提要：** 基础模型需要对齐，才能安全、可信地部署。传统微调计算负担重，而且还要更新模型参数。
- **关键词：** SFT, alignment, fine-tuning

### TSDS: Data Selection for Task-Specific Model Finetuning

- **作者：** Zifan Liu, Amin Karbasi, Theodoros Rekatsinas
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/13848b5893119ff772b69812c95914fa-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/13848b5893119ff772b69812c95914fa-Paper-Conference.pdf)
- **中文提要：** 针对具体任务微调基础模型，正成为机器学习里的一种新范式。这种微调是否有效，很大程度上取决于训练数据选得是否合适。
- **关键词：** instruction-tuning, continued-pretraining, alignment, fine-tuning

### Uncertainty-aware Fine-tuning of Segmentation Foundation Models

- **作者：** Kangning Liu, Brian Price, Jason Kuen, Yifei Fan, Zijun Wei, Luis Figueroa, Krzysztof Geras, Carlos Fernandez-Granda
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/5f999632c48f87cffb214e575581e4a9-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/5f999632c48f87cffb214e575581e4a9-Paper-Conference.pdf)
- **中文提要：** Segment Anything Model（SAM）改变了分割做法，泛化能力突出。面对结构复杂的图像时，它的分割精度却常常不理想。
- **关键词：** fine-tuning

### Understanding Linear Probing then Fine-tuning Language Models from NTK Perspective

- **作者：** Akiyoshi Tomihari, Issei Sato
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/fcc22e5b7d5d2155d994da22d045f0a6-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/fcc22e5b7d5d2155d994da22d045f0a6-Paper-Conference.pdf)
- **中文提要：** 先线性探测再微调的两阶段方法（LP-FT），优于只做线性探测或只做微调。这一比较在分布内和分布外数据上都成立。
- **关键词：** LoRA, fine-tuning

### Unpacking DPO and PPO: Disentangling Best Practices for Learning from Preference Feedback

- **作者：** Hamish Ivison, Yizhong Wang, Jiacheng Liu, Zeqiu Wu, Valentina Pyatkin, Nathan Lambert, Noah Smith, Yejin Choi, Hanna Hajishirzi
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/404df2480b6eef0486a1679e371894b0-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/404df2480b6eef0486a1679e371894b0-Paper-Conference.pdf)
- **中文提要：** 从偏好反馈中学习，已成为提升现代语言模型生成质量的必要步骤。实际应用里数据、学习算法和评测方式差异很大，很难把每一项的影响拆开。
- **关键词：** DPO, instruction-following, reward-model

### Unveiling LoRA Intrinsic Ranks via Salience Analysis

- **作者：** Wenjun Ke, Jiahao Wang, Peng Wang, Jiajun Liu, Dong Nie, Guozheng Li, Yining Li
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/ed9f00cb7dd5fbdc2175d55e2fdf1b05-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/ed9f00cb7dd5fbdc2175d55e2fdf1b05-Paper-Conference.pdf)
- **中文提要：** 大语言模型参数规模巨大，因而需要参数高效微调。LoRA 一类方法假定增量矩阵是低秩的，并去优化由低秩分解得到的矩阵。
- **关键词：** instruction-tuning, LoRA, PEFT, fine-tuning

### Vaccine: Perturbation-aware Alignment for Large Language Models against Harmful Fine-tuning Attack

- **作者：** Tiansheng Huang, Sihao Hu, Ling Liu
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/873c86d9a979ab80d8e2919510d4446b-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/873c86d9a979ab80d8e2919510d4446b-Paper-Conference.pdf)
- **中文提要：** 微调即服务给大语言模型带来新的攻击面：用户上传的少量有害数据，就可能把微调结果变成对齐失效的模型。经验分析发现一种有害嵌入漂移，并把它视为对齐被破坏的可能原因。
- **关键词：** alignment, fine-tuning

### Value Imprint: A Technique for Auditing the Human Values Embedded in RLHF Datasets

- **作者：** Ike Obi, Rohan Pant, Srishti Shekhar Agrawal, Maham Ghazanfar, Aaron Basiletti
- **会议：** NeurIPS 2024 · Main · Spotlight
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/cf7ec6aa55ba2b2f7af0cf3fd25b7f8c-Abstract-Datasets_and_Benchmarks_Track.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/cf7ec6aa55ba2b2f7af0cf3fd25b7f8c-Paper-Datasets_and_Benchmarks_Track.pdf)
- **中文提要：** 人们越来越多地用 RLHF 数据集微调大语言模型，使其贴近人类偏好与价值。哪些具体人类价值经由这些数据集被落实，相关研究仍然很少。
- **关键词：** RLHF, fine-tuning

### VB-LoRA: Extreme Parameter Efficient Fine-Tuning with Vector Banks

- **作者：** Yang Li, Shaobo Han, Jonathan Shihao Ji
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/1e0d38c676d5855bcfab7f6d29d20ad9-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/1e0d38c676d5855bcfab7f6d29d20ad9-Paper-Conference.pdf)
- **中文提要：** 按用户或按任务定制模型的需求上升后，LoRA 等 PEFT 方法在存储和传输上的开销仍然不小。文中提出“分而共享”范式，用来打破矩阵之间低秩分解的隔阂。
- **关键词：** instruction-tuning, LoRA, PEFT, fine-tuning

### What Makes and Breaks Safety Fine-tuning? A Mechanistic Study

- **作者：** Samyak Jain, Ekdeep S Lubana, Kemal Oksuz, Tom Joy, Philip Torr, Amartya Sanyal, Puneet Dokania
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/a9bef53eb7b0e5950d4f2d9c74a16006-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/a9bef53eb7b0e5950d4f2d9c74a16006-Paper-Conference.pdf)
- **中文提要：** 安全微调帮助大语言模型对齐人类偏好，以便安全部署。为弄清哪些因素让模型变安全，作者设计了合成数据生成框架，通过所要求的任务（例如“设计”）与具体概念之间的互动来刻画不安全输入。
- **关键词：** DPO, preference-optimization, fine-tuning

### When Your AIs Deceive You: Challenges of Partial Observability in Reinforcement Learning from Human Feedback

- **作者：** Leon Lang, Davis Foote, Stuart J Russell, Anca Dragan, Erik Jenner, Scott Emmons
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/a995960dd0193654d6b18eca4ac5b936-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/a995960dd0193654d6b18eca4ac5b936-Paper-Conference.pdf)
- **中文提要：** 以往对 RLHF 的分析假定人类评估者能完整观察环境。当人类反馈只基于部分观测时会发生什么，是这里提出的问题。
- **关键词：** RLHF

### WizardArena: Post-training Large Language Models via Simulated Offline Chatbot Arena

- **作者：** HAIPENG LUO, Qingfeng Sun, Can Xu, Pu Zhao, Qingwei Lin, Jian-Guang Lou, Shifeng Chen, Yansong Tang, Weizhu Chen
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/ca4aa9acc097e0f606af55bf986cb031-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/ca4aa9acc097e0f606af55bf986cb031-Paper-Conference.pdf)
- **中文提要：** 用开放域指令跟随数据对大语言模型做后训练，已经取得很大成功。人类 Chatbot Arena 也同时成为模型评测和改进指引里较合理的基准之一。
- **关键词：** DPO, SFT, instruction-following, post-training, fine-tuning

### Would I Lie To You? Inference Time Alignment of Language Models using Direct Preference Heads

- **作者：** Avelina Hadji-Kyriacou, Ognjen Arandjelovic
- **会议：** NeurIPS 2024 · Main · Poster
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/ad3d0ac42b4b5cc3b5f0ca10107d5c84-Abstract-Conference.html
- **PDF / arXiv：** [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/ad3d0ac42b4b5cc3b5f0ca10107d5c84-Paper-Conference.pdf)
- **中文提要：** 预训练语言模型的零样本和上下文学习能力很强，行为却常常难以控制。借助 RLHF，可以把未经监督训练的模型微调到遵循指令，并产出反映人类偏好的结果。
- **关键词：** DPO, RLHF, SFT, preference-optimization, alignment, fine-tuning
