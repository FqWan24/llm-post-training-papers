# 2026 · ICML

共 298 篇。Main 298，Findings 0，其他赛道 0。其中 0 篇来源题录无摘要，提要标明「仅根据标题概括」。

检索窗口为 2024-11-13 至 2026-11-13。题录信息来自官方列表，不在此增补作者、链接或实验数字。

## Main

### 3D-RFT: Reinforcement Fine-Tuning for Video-based 3D Scene Understanding

- **作者：** Xiongkun Linghu, Jiangyong Huang, Baoxiong Jia, Siyuan Huang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=t6h8LhOupF
- **中文提要：** 可验证奖励强化学习（RLVR）已成为释放大语言模型复杂推理的重要范式，但在三维场景理解上尚未被用起来。3D-RFT 把 RLVR 扩展到基于视频的三维感知与推理。
- **关键词：** GRPO, RLVR, RFT, SFT, alignment, fine-tuning

### ACO-MoE-LoRA: Evolving-while-Training for Adapting Segment Anything Model 2 to Specialized Domains

- **作者：** Kaiyi Luo, Bangjun Wang, Li Zhang, Fanzhang Li, Fei Zhu, Jiaqing Fan
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=0YKTO2A04S
- **中文提要：** 静态微调给 SAM2 一类基础模型施加了僵硬的结构约束，难以适应专业下游任务变化的复杂度。ACO-MoE-LoRA 以边训练边演化的策略，把蚁群优化与潜空间中的某种机制结合起来。
- **关键词：** LoRA, fine-tuning

### AdaMeZO: Adam-style Zeroth-Order Optimizer for LLM Fine-tuning Without Maintaining the Moments

- **作者：** Zhijie Cai, Haolong Chen, Guangxu Zhu
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=XLc102wbnT
- **中文提要：** 针对特定下游任务微调大语言模型时，经典反向传播方法需要大量显存。MeZO 只靠前向传播来微调，从而明显降低显存需求，但因不区分损失地形而收敛更慢。
- **关键词：** fine-tuning

### Adaptive Token Refinement in Long-Tailed Large Vision-Language Models Fine-Tuning

- **作者：** Wenjun Miao, Mingda Li, Yanchao Hao, Zheng Wei
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=HK0IhFBmoN
- **中文提要：** 大型视觉语言模型虽能适应多种下游应用，在长尾数据上微调时仍容易产生偏差。相对零样本设定，在不平衡数据上微调对尾部数据的提升往往有限。
- **关键词：** fine-tuning

### Adaptive Utilization of Low-Rank Adaptation via Conditioned Gating

- **作者：** Guang Yang, Changhao Guan, Chao Huang, Yufeng Chen, Kaiyu Huang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=cA7SvKStDh
- **中文提要：** LoRA 把模型更新限制在低秩子空间里，因而能以较少参数完成微调并被广泛使用。它通常让所有词元共享同一低秩更新，难以让不同序列中的词元充分利用这块适配子空间。
- **关键词：** LoRA, PEFT, fine-tuning

### Advantage Collapse in Group Relative Policy Optimization: Diagnosis and Mitigation

- **作者：** Xixiang He, Qiyao Sun, Ao Cheng, Xingming Li, Xuanyu Ji, Hailun Lu, Runke Huang, Qingyong Hu
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=MKNimf9bIx
- **中文提要：** GRPO 是可验证奖励强化学习中的重要算法，已明显提升大语言模型的推理能力。它却容易出现优势坍缩：组内奖励同质时，例如全对或全错，优势会接近于零。
- **关键词：** GRPO, RLVR

### Adversarial Training for Process Reward Models

- **作者：** Gurusha Juneja, Deepak Nathani, William Wang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=43Hwj59jZg
- **中文提要：** 过程奖励模型通过逐步监督来增强大语言模型的推理能力。推广却受限于昂贵的人工步骤标注，以及静态训练数据难以泛化到新出现的错误。
- **关键词：** PRM, reward-model

### AGZO: Activation-Guided Zeroth-Order Optimization for LLM Fine-Tuning

- **作者：** Wei LIN, Yining Jiang, Qingyu Song, Qiao Xiang, Hong Xu
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=zfVxpXEZti
- **中文提要：** 零阶优化在严格显存约束下微调大语言模型很有吸引力，因为它不必为反向传播保存激活。现有零阶方法多用各向同性扰动，忽略了前向过程中已有的结构信息。
- **关键词：** fine-tuning

### AIR: Post-training Data Selection for Reasoning via Attention Head Influence

- **作者：** Jinrui Liu, Kai Hua, Xuanguang Pan, Ge Zhang, Yong Wang, Shuai Ma, Chongyang Tao
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=jjHZnkDk5l
- **中文提要：** 大语言模型已具备很强的多步推理，但通过后训练蒸馏有效迁移这些能力仍然困难。从人工筛选到基于长度、熵或总体损失的启发式，现有数据选择都抓不住单个推理步骤的因果重要性，因而限制了蒸馏效率。
- **关键词：** post-training, fine-tuning

### A Language-Guided Bayesian Optimization for Efficient LoRA Hyperparameter Search

- **作者：** Baek Seong-Eun, Lee Jung-Mok, Kim Sung-Bin, Tae-Hyun Oh
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=JNdi6E05NJ
- **中文提要：** 用 LoRA 微调大语言模型，是以较低资源做个性化或专用化的途径。LoRA 对超参数非常敏感，而穷举搜索的计算代价又很高。
- **关键词：** LoRA, fine-tuning

### Alignment Tampering: How Reinforcement Learning from Human Feedback Is Exploited to Optimize Misaligned Biases

- **作者：** Dongyoon Hahm, Dylan Hadfield-Menell, Kimin Lee
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=qNsrhcCe4y
- **中文提要：** RLHF 是把大语言模型对齐到人类偏好的标准方法。作者提出对齐篡改这一潜在漏洞：正在被对齐的模型会影响偏好数据集，从而使 RLHF 放大不希望出现的行为。
- **关键词：** RLHF, reward-model, alignment

### Alleviating Sparse Rewards by Modeling Step-Wise and Long-Term Sampling Effects in Flow-Based GRPO

- **作者：** Yunze Tong, Mushui Liu, Canyu Zhao, Wanggui He, Shiyi Zhang, Peng Zhang, Hongwei Zhang, Jinlong Liu, Hao Jiang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ZSt77efXHI
- **中文提要：** 把 GRPO 用到流匹配模型上，对文生图已经有效。现有范式通常把基于结果的奖励回传到前面所有去噪步骤，而不区分每一步的局部作用。
- **关键词：** GRPO

### Alternating Reinforcement Learning for Rubric-Based Reward Modeling in Non-Verifiable LLM Post-Training

- **作者：** Ran Xu, Tianci Liu, Zihan Dong, Tony Yu, Ilgee Hong, Carl Yang, Linjun Zhang, Tuo Zhao, Haoyu Wang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=3SDg8dtkS8
- **中文提要：** 标量奖励难以刻画创意写作、开放式指令遵循等不可验证领域里回答质量的多个侧面。Rubric-ARM 借助偏好反馈上的强化学习，联合优化评分准则生成器与评判模型。
- **关键词：** instruction-following, reward-model, post-training, alignment

### Annotations Mitigate Post-Training Mode Collapse

- **作者：** Jacob Mitchell Springer, Madhu Advani, Lukas Aichberger, Arwen Bradley, Eran Malach, Omid Saremi, Sinead Williamson, Preetum Nakkiran, Etai Littwin, Aditi Raghunathan
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Wtjwjn1uak
- **中文提要：** 监督微调能改善指令遵循，却常把模型偏向低熵的微调数据，挤占高熵的预训练分布，从而引起语义模式坍缩。这一权衡还会随规模变得更严重。
- **关键词：** SFT, instruction-following, post-training, fine-tuning

### Approximation of Log-Partition Function in Policy Mirror Descent Induces Implicit Regularization for LLM Post-Training

- **作者：** Zhenghao Xu, Qin Lu, Changlong Yu, Tuo Zhao
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=WPFVuJDDqc
- **中文提要：** 策略镜像下降把强化学习写成一系列带 KL 正则的策略改进子问题，理想的闭式更新需要可靠估计配分函数。动作空间极大而 rollout 有限时，这一估计成为显著困难。
- **关键词：** post-training

### A Risk Decomposition Framework for Pre-hoc Fine-tuning Prediction

- **作者：** Yuxiang Luo, Chen Wang, Nan Tang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=2VhdUDz6mO
- **中文提要：** 微调大语言模型的高成本构成明显的经济障碍，事先预测微调后的表现有望降低这笔开销。这种事前性能预测的理论极限仍未被探讨。
- **关键词：** fine-tuning

### Automatically Finding Reward Model Biases

- **作者：** Atticus Wang, Iván Arcuschin, Arthur Conmy
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Xy4ClJMjIU
- **中文提要：** 奖励模型处于大语言模型后训练的核心，但已有工作表明，它们会奖赏长度、格式、幻觉和谄媚等虚假或不良属性。
- **关键词：** reward-model, post-training

### AutoQRA: Joint Optimization of Mixed-Precision Quantization and Low-rank Adapters for Efficient LLM Fine-Tuning

- **作者：** Changhai Zhou, Shiyang Zhang, Yuhua Zhou, Qian Qiao, Jun Gao, Cheng Jin, KAIZHOU QIN, Weizhong Zhang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=EB8MHApOav
- **中文提要：** 先量化再做参数高效微调，适合显存紧张时的下游适应。这种先后流水线却没有利用量化位宽与 LoRA 秩之间的相互作用。
- **关键词：** LoRA, PEFT, fine-tuning

### Autoregressive Direct Preference Optimization

- **作者：** Masanari Oi, Mahiro Ukai, Masahiro Kaneko, Naoaki Okazaki, Nakamasa Inoue
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=DmeFAFUO6f
- **中文提要：** 直接偏好优化被用于让大语言模型对齐人类偏好，但普遍依赖的回答级 Bradley-Terry 模型可能限制其潜力。参考模型与可学习模型的自回归性质，是在导出目标函数之后才被假定的。
- **关键词：** DPO, preference-optimization, alignment

### Awakening Visual Reasoning: Mitigating Post-Training Failure in Vision-Text Compression

- **作者：** Xing Xi, Liyao Li, Hao Chen, NINGTAO WANG, Peixian Chen, peilin tong, Xing Fu, Yu Cheng, Haobo Wang, Gang Chen, Junbo Zhao, Ronghua Luo
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=MrrLfshRVj
- **中文提要：** 视觉–文本压缩把文本渲染成密集视觉词元，为长上下文多模态建模提供可扩展途径。视觉语言模型在这类输入上解码保真度很高，但在原生文本上能稳健推理的模型，面对视觉压缩后的对应内容时推理会明显失败，长程检索尤为突出。
- **关键词：** SFT, post-training, fine-tuning

### Balanced LoRA: Removing Parameter Invariance to Accelerate Convergence

- **作者：** Valérie Castin, Kimia Nadjahi, Pierre Ablin, Gabriel Peyré
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=kHInw3cjCP
- **中文提要：** 低秩适配是最常用的大语言模型微调方法，但它天生过参数化：多组低秩因子可以得到同一个适配后的权重矩阵。
- **关键词：** LoRA, fine-tuning

### Bayesian-LoRA: Probabilistic Low-Rank Adaptation of Large Language Models

- **作者：** Moule Lin, Shuhao Guan, Andrea Patane, David Gregg, Goetz Botterweck
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=z3rQmLk4Io
- **中文提要：** 大语言模型通常按准确率优化，因此即使不确定也会给出猜测。在小数据集上微调时，过拟合会让这种误校准更加突出。
- **关键词：** LoRA, fine-tuning

### Behavioral Mode Discovery for Fine-tuning Multimodal Generative Policies

- **作者：** Alberta Longhini, David Emukpere, Jean-Michel Renders, Seungsu Kim
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=nc5WYNeI17
- **中文提要：** 这里要解决的是：用强化学习微调预训练的生成式策略，同时保留动作分布的多模态。已有方法（例如扩散策略）能提高任务表现，却常常把多样行为坍缩成单一的奖励最大化模式。
- **关键词：** RFT, fine-tuning

### Beyond Log Likelihood: Probability-Based Objectives for Supervised Fine-Tuning across the Model Capability Continuum

- **作者：** Gaotang Li, Ruizhong Qiu, Xiusi Chen, Heng Ji, Hanghang Tong
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=2hQBG2ZlFb
- **中文提要：** 监督微调是大语言模型后训练的标准做法，泛化却常常有限。作者把这一限制追溯到它的默认训练目标，即负对数似然。
- **关键词：** SFT, post-training, fine-tuning

### Beyond Normalization: Rethinking the Partition Function as a Difficulty Scheduler for RLVR

- **作者：** Dohyung Kim, Minbeom Kim, Jeonghye Kim, Lee Sangmook, Sojeong Rhee, Kyomin Jung
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=U93dBehANs
- **中文提要：** 奖励最大化的强化学习能够提升大语言模型的推理表现，但往往会降低生成多样性。近期工作改用 GFlowNet，训练模型去匹配目标分布，并同时学习其配分函数。
- **关键词：** GRPO, RLVR, post-training

### Beyond Two-Stage Training: Cooperative SFT and RL for LLM Reasoning

- **作者：** Liang Chen, Xueting Han, Li Shen, Jing Bai, Kam-Fai Wong
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=xWvj03N4sJ
- **中文提要：** 监督微调与可验证奖励强化学习，是提升大语言模型推理能力的两种常用后训练范式。近期方法试图在单阶段内，通过重加权或调度把两者的目标结合起来。
- **关键词：** RLVR, SFT, LoRA, post-training, fine-tuning

### Beyond VLM-Based Rewards: Diffusion-Native Latent Reward Modeling

- **作者：** Gongye Liu, Bo Yang, Zhi Yida, Zhizhou Zhong, Lei Ke, Didan Deng, Han Gao, Yongxiang Huang, Kaihao Zhang, Hongbo Fu, Wenhan Luo
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=cPDN8YlKdQ
- **中文提要：** 扩散模型的偏好优化需要既有判别力、计算上又高效的奖励函数。视觉语言模型已成为一类有力的奖励提供者。
- **关键词：** preference-optimization, reward-model, alignment

### BIT-LLM: Brain Instruction Tuned LLM with persistent Cross-Attention for fMRI-to-Text Decoding

- **作者：** Sunghwan LEE, jihun kim, Chaelynn Kim, Jiyun Park, Jong-Hwan Lee
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=HZhlRnJOHq
- **中文提要：** 把 fMRI 解码成自然语言时，强大的预训练语言先验会主导自回归生成，使人难以判断模型是否真正利用了神经证据。BIT-LLM 用交错的交叉注意力适配器，把 fMRI 派生词元暴露为持续的键值记忆，使解码全程可以反复读取神经信号。
- **关键词：** SFT, instruction-tuning, fine-tuning

### Blending Supervised and Reinforcement Fine-Tuning with Prefix Sampling

- **作者：** Zeyu Huang, Tianhao Cheng, Zihan Qiu, Zili Wang, Xu Yinghui, Edoardo Ponti, Ivan Titov
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=MgtyPYrC4h
- **中文提要：** 大语言模型后训练大体分为监督微调与强化微调。监督微调擅长模仿示范，但作为行为克隆容易带来有问题的泛化。
- **关键词：** RFT, SFT, post-training, fine-tuning

### BOOSTAPR: Boosting Automated Program Repair via Execution-Grounded Reinforcement Learning with Dual Reward Models

- **作者：** Yuanhao Li, Hongbo Wang, Xiaotang Shang, Xunzhu Tang, Yiming Cao, Xuhong Chen
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=J2TKCPUI3E
- **中文提要：** 程序修复上的强化学习受阻于稀疏的执行反馈，以及看不清哪一处编辑真正修好缺陷的粗粒度序列奖励。BoostAPR 先在带推理轨迹、且经执行验证的示范上做监督微调，再依据执行结果训练序列级评估器与行级信用分配器这两类奖励模型。
- **关键词：** SFT, reward-model, fine-tuning

### Breaking the Self-Confirming Loop: Diagnosing and Mitigating Systemic Reward Bias in Self-Rewarding RL

- **作者：** Chuyi Tan, Peiwen Yuan, Xinglin Wang, Yiwei Li, Shaoxiong Feng, Yueqi Zhang, Jiayi Shi, Ji Zhang, Boyuan Pan, Yao Hu, Kan Li
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=oAagVd30Fn
- **中文提要：** 可验证奖励的强化学习能扩展大语言模型的推理能力，却受限于稀缺的标注数据。以内在奖励做自我奖励的路线提供了可扩展替代，但常常不稳定且表现较差。
- **关键词：** RLVR, self-rewarding

### Bridging On-Device and Cloud LLMs for Collaborative Reasoning: A Unified Methodology for Local Routing and Post-Training

- **作者：** Wenzhi Fang, Dong-Jun Han, Liangqi Yuan, Evan Chen, Christopher G. Brinton
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=m0HB67qATB
- **中文提要：** 端云协同希望用轻量的端侧模型换取效率，同时把更强的推理交给云端大模型。关键困难在于，对每条到来的查询判断应在本地处理还是卸载到云端。
- **关键词：** post-training

### Bridging the Stability-Expressivity Gap: Synthetic Data Scaling and Preference Alignment for Low-Resource Spoken Language Models

- **作者：** Yizhong Geng, Yanliang Li, Jinghan Yang, Tianhan Jiang, Boxun An, Ya Li, Xiaoyu Shen
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=a57NvkgjT2
- **中文提要：** 口语语言模型绕过显式的字素到音素流程来做语音合成。在低资源语言中，转写语音的稀缺从根本上限制了它们的效果。
- **关键词：** preference-optimization, alignment

### B-Spar: Bayesian Sparse-Reward Modeling for RL-based Image Editing

- **作者：** shusong xu, Peiye Liu, Yongbin Liu, Bangjie Yin, Tianyi Zheng, Zhaomang Sun, Zhenyu Chen, Peng-Tao Jiang, Jian Zhang, Yuzhao Wang, Zhen Gu, Jinwei Chen, Bo Li
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=aoUqzNEKpA
- **中文提要：** 多模态大语言模型把高层指令翻译成由工具执行的编辑序列，使自主图像编辑更透明、更可控。用强化学习训练这类智能体时，常常靠稠密代理奖励来弥补稀疏的人类反馈。
- **关键词：** reward-model, alignment

### CAMEL: Confidence-Gated Reflection for Reward Modeling

- **作者：** Zirui Zhu, Hailun Xu, Yang Luo, Yong Liu, Kanchan Sarkar, Kun Xu, Yang You
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=gl5xoOJJ22
- **中文提要：** 奖励模型是让大语言模型对齐人类偏好的基础环节。现有路线主要有两类：标量判别式偏好模型效率高但缺乏可解释性，生成式评判模型推理更丰富但计算开销更高。
- **关键词：** reward-model, alignment

### Capability Traps in DPO

- **作者：** Marco Pollanen
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=3cU6rSN9Cd
- **中文提要：** 直接偏好优化常通过挑选偏好边际较高的检查点来调参。这种选择规则可能会失效。
- **关键词：** DPO, preference-optimization

### Causal Direct Preference Optimization for Distributionally Robust Generative Recommendation

- **作者：** Chu Zhao, Enneng Yang, Jianzhe Zhao, Guibing Guo
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=VDaJ5RCOh4
- **中文提要：** 在生成式推荐中，直接偏好优化靠最小化偏好对齐损失，使输出贴合用户的历史行为分布。系统的经验研究与理论分析表明，对齐过程会放大环境混杂因素造成的虚假相关。
- **关键词：** DPO, preference-optimization, alignment

### CLIMB: Taming the LoRA Residency Cliff in Multi-LoRA Serving

- **作者：** Haoran Zhang, Zhiyu Liang, ZUO Decheng, Hongzhi Wang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=4bN7wxsIcL
- **中文提要：** 多租户的多 LoRA 服务在单块 GPU 上复用大量适配器，设备显存大多留给 KV 缓存，适配器只能占用很小的驻留预算。适配器若不在设备上驻留，引擎必须强制取回，从而拖住共享执行并放大全系统的尾延迟。
- **关键词：** LoRA

### Clipping Bottleneck: Stabilizing RLVR via Stochastic Recovery of Near-Boundary Signals

- **作者：** Shuo Yang, Jinda Lu, Chiyu Ma, Kexin Huang, Haoming Meng, Qihui Zhang, Yuyang Liu, Bolin Ding, Guoyin Wang, Li Yuan, Jingren Zhou
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ZXFTvoBZ1B
- **中文提要：** 可验证奖励强化学习已成为扩展大语言模型推理的核心范式，但优化常常不稳定且收敛不理想。拆解基于裁剪的 GRPO 式目标后，硬裁剪所导致的刚性裁剪决策被看作实际中的关键瓶颈。
- **关键词：** GRPO, RLVR

### Clipping Low-Probability Tokens in SFT Yields a Generalizable Initialization for RL

- **作者：** Tian-Shuo Liu, Chengxing Jia, Haoyu Liu, Pengyuan Wang, Shiyuan Zhang, Jie Fu, Yang Yu
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=t4Jc7C9bTx
- **中文提要：** 监督微调常作为后续强化学习的初始化，用来把大语言模型适配到专门领域。它却可能在一小批专家数据上过拟合，损害泛化并侵蚀原有知识。
- **关键词：** SFT, fine-tuning

### CMI-RewardBench: Evaluating Music Reward Models with Compositional Multimodal Instruction

- **作者：** Yinghao Ma, Haiwen Xia, Hewei Gao, Weixiong Chen, Ye Yuxin, Yuchen Yang, Sungkyun Chang, Mingshuo Ding, Yizhi Li, Ruibin Yuan, Simon Dixon, Emmanouil Benetos
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=k9DhP16RZt
- **中文提要：** 音乐生成模型已能处理文本、歌词与参考音频混合的复杂多模态输入，评测机制却仍然碎片化且覆盖面窄。该工作要为组合式音乐指令的奖励建模补上这一缺口，其中生成的音乐可以条件于文本描述等因素。
- **关键词：** reward-model, PEFT, alignment

### COBRA: Contribution-Based Bayesian Rank Allocation for Parameter-Efficient Fine-Tuning

- **作者：** Hongcheng Ding, Xuanze Zhao, LIU XUANHUANG, Jing Jin, Shamsul Abdullah, Deshinta Dewi
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=uN58wqH2T7
- **中文提要：** 全量微调大语言模型的计算与存储成本过高。参数高效微调缓解了这一限制，其中 LoRA 因简单且推理时没有额外开销而被广泛采用。
- **关键词：** LoRA, PEFT, alignment, fine-tuning

### CoLA: Cross-Modal Low-rank Adaptation for Multimodal Downstream Tasks

- **作者：** Wish Suharitdamrong, Tony Alex, Muhammad Awais, Sara Atito
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=8CBWgJY7n9
- **中文提要：** 把基础模型高效适配到多模态任务仍然困难，尤其是由 DINO、BERT 这类单模态编码器组成的双流架构。LoRA 等参数高效方法可以做轻量适配，但它们在每个模态内部各自运作，跨模态能力因此受限。
- **关键词：** LoRA, PEFT, fine-tuning

### Collaborative and Efficient Fine-tuning: Leveraging Task Similarity

- **作者：** Gagik Magakyan, Amirhossein Reisizadeh, Chanwoo Park, Pablo A. Parrilo, Asuman Ozdaglar
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=u1adSPW25t
- **中文提要：** 可适应性被视为基础模型的核心特征，使其能够适应未见过的下游任务。LoRA 一类参数高效微调，依靠有标注、质量高且通常稀缺的任务数据来完成高效适配。
- **关键词：** LoRA, PEFT, fine-tuning

### Conditional Equivalence of DPO and RLHF: Assumptions, Failure Modes, and Provable Alignment

- **作者：** Yonggang Zhang, Zhiqin Yang, Wei Xue, Dong Fang, Bo Han, Yike Guo
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=7UEBX1KU1y
- **中文提要：** 直接偏好优化被当作人类反馈强化学习的流行替代，实现更简单，并在理论上与之等价。这一等价是有条件的而非普遍成立，它依赖一个实践中经常被违反的隐含假设：RLHF 最优策略必须更偏好人类所偏好的回答。
- **关键词：** DPO, RLHF, preference-optimization, alignment

### Configurable Reward Model for Balanced Safety Alignment

- **作者：** Zhengping Jiang, Mehran Khodabandeh, Akash Bharadwaj, Manik Bhandari, Mayur Srungarapu, Anqi Liu, Benjamin Van Durme, Li Chen
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=aWmEo0tNjs
- **中文提要：** 让大语言模型对齐异构且快速变化的安全要求仍然是关键难题。现有指令微调模型与独立的安全分类器往往无法泛化到新的安全配置，因此需要奖励模型能够随规范变化而显式配置。
- **关键词：** instruction-tuning, reward-model, alignment

### Constrained Flow Optimization via Sequential Fine-Tuning for Molecular Design

- **作者：** Sven Gutjahr, Riccardo De Santi, Luca Schaufelberger, Kjell Jorner, Andreas Krause
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=KBpIlcUIx1
- **中文提要：** 分子设计、蛋白质工程等科学发现场景，需要把扩散与流模型适配到给定奖励上，同时满足约束，例如结合亲和力与分子可合成性。近期工作已经提出可扩展的奖励引导微调方法。
- **关键词：** fine-tuning

### Context Distillation Retains Post-Training Capabilities in Continually Trained LMs

- **作者：** Shankar Padmanabhan, Mustafa Omer Gul, Tanya Goyal
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=OJsGhlTayF
- **中文提要：** 后训练赋予预训练大语言模型指令遵循、推理等多种能力，但这些模型只编码到某个截止日期为止的知识，因而需要持续适应。
- **关键词：** instruction-following, post-training, fine-tuning

### Convex Dataset Valuation for Post-Training

- **作者：** Siqi Zeng, Christopher Jung, Rui Li, Zhe Kang, Ming Li, Nima Noorshams, Zhigang Wang, Fuchun Peng, Han Zhao, Xue Feng
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=oAAL0wZSMF
- **中文提要：** 提升大语言模型的下游表现，有时要在后训练中使用辅助数据集。计算、标注和许可方面的成本使开发者无法用上全部数据，因此需要有原则的数据集级选择。
- **关键词：** post-training, alignment

### CRPO: Character-centric Group Relative Policy Optimization for Role-aware Reasoning in Role-playing Agents

- **作者：** Yihong Tang, Kehai Chen, Liang Yue, Benyou Wang, Min zhang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=h2JyEuY6OL
- **中文提要：** 以 GRPO 为代表的强化学习明显增强了大语言模型的推理能力。把这类以问题为中心的优化用到角色扮演智能体上，却常因优先追求情境效用而损失角色一致性，并出现风格坍缩。
- **关键词：** GRPO, alignment

### CSPLoRA: Confidence-Guided Structure Planning for Low-Rank Adaptation

- **作者：** Huiming Ding, Xiaochen Li, Jianhui Ma, Xu An, Yihui Yang, Zhenyu Tan
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=WkARznT46l
- **中文提要：** LoRA 已成为参数高效微调的事实标准，其效果很大程度上取决于各模块之间的秩如何分配。均匀分配忽视模块差异，自适应方法则要么训练开销高，要么难以在不同配置间复用。
- **关键词：** LoRA, PEFT, fine-tuning

### CUARewardBench: A Benchmark for Evaluating Reward Models for Computer-Using Agents

- **作者：** Haojia Lin, Xiaoyu Tan, Yulei Qin, Zihan Xu, Yuchen Shi, Zongyi Li, Gang Li, Shaofei Cai, Siqi Cai, Yuzheng Cai, Chaoyou Fu, Ke Li, Xing Sun
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Xj7V0wKlE5
- **中文提要：** 计算机使用智能体通过与操作系统和软件界面的自然交互来完成任务。基于脚本的验证器虽被广泛采用，但扩展性有限，也无法提供逐步评估。
- **关键词：** PRM, reward-model

### Cure-SFT: Diagnostic-Guided Data Curation for Instruction Tuning

- **作者：** Yuankang Fu, Xinrong Gong, Chen Gong, Tong Zhang, Kaixiang Yang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=wTLFM5mWoa
- **中文提要：** 指令数据筛选对提升大语言模型的指令遵循能力处于中心位置。现有方法难以同时维持质量、多样性与分布一致性，主要因为它们没有明确区分语义冗余和质量缺陷，并且只对指令数据质量做粗粒度建模。
- **关键词：** SFT, instruction-tuning, instruction-following

### CurvZO: Adaptive Curvature-Guided Sparse Zeroth-Order Optimization for Efficient LLM Fine-Tuning

- **作者：** Shuo Wang, Ziyu Chen, Ming Tang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=L35b2JZ8gS
- **中文提要：** 用反向传播微调大语言模型效果好，但显存开销很大，难以在资源受限的硬件上扩展。零阶优化只依赖前向传播，从而更省显存，却常因梯度估计方差高而收敛慢或不稳定。
- **关键词：** fine-tuning

### Data Difficulty and the Generalization–Extrapolation Tradeoff in LLM Fine-Tuning

- **作者：** Siyuan Liu, Tinghong Chen, Xinghan Li, Yifei Wang, Jingzhao Zhang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=LCosvYhXvi
- **中文提要：** 监督微调时如何选择数据，会关键地改变大语言模型的行为。已有工作按困惑度、难度或长度等启发式来筛选，但所报告的结论往往不一致，或依赖于具体情境。
- **关键词：** SFT, fine-tuning

### Data Provenance Auditing of Fine-Tuned Large Language Models with a Text-Preserving Technique

- **作者：** Yanming Li, Cédric Eichler, Nicolas Anciaux, Alexandra Bensamoun, Lorena Gonzalez-Manzano, Seifeddine Ghozzi
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=3D0x8oxOYH
- **中文提要：** 该方法用不可见的 Unicode 字符组织成“提示–应答”对，为敏感或受版权保护的文本打下数字标记。由此可以在黑盒访问下、并带有统计保证地检测这些文本是否被用于微调大语言模型。
- **关键词：** fine-tuning

### Data Selection for Fine-tuning Vision Language Models via Cross Modal Alignment Trajectories

- **作者：** Nilay Naharas, Dang Nguyen, Neslihan Bulut, MohammadHossein Bateni, Vahab Mirrokni, Baharan Mirzasoleiman
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ZptT82VZ4E
- **中文提要：** 数据高效学习希望去掉大规模训练集中的冗余，只在信息量最高的子集上训练。数据选择在视觉模型和语言模型中已有大量研究，对大型视觉语言模型仍探索不足。
- **关键词：** instruction-tuning, alignment, fine-tuning

### daVinci-Dev: Agent-native Mid-training for Software Engineering

- **作者：** Ji Zeng, Dayuan Fu, Tiantian Mi, Zhuang Yumin, Yaxing Huang, Xuefeng Li, Lyumanshan Ye, Muhang Xie, Qishuo Hua, Zhen Huang, Mohan Jiang, Hanning Wang, Shijie Xia, Yang Xiao, Jie Sun, Yunze Wu, Pengfei Liu
- **会议：** ICML 2026 · Main · Oral
- **官方论文页：** https://openreview.net/forum?id=a86luANykT
- **中文提要：** 智能体软件工程已经催生大量后训练研究，但仅靠后训练并不能完全解决传统静态预训练与动态部署环境之间的分布错配。该工作转而考察智能体中期训练，作为一种可扩展的互补途径。
- **关键词：** mid-training, post-training

### DC-W2S: Dual-Consensus Weak-to-Strong Training for Reliable Process Reward Modeling in Biological Reasoning

- **作者：** Chi-Min Chan, Ehsan Hajiramezanali, Xiner Li, Edward De Brouwer, Carl Edwards, Wei Xue, Sirui Han, Yike Guo, Gabriele Scalia
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Lh3Hico2Pe
- **中文提要：** 科学推理任务中，推理过程是否可靠与最终结果同样关键。过程奖励模型针对结果奖励模型监督过粗的问题，但获取专家核验的逐步标注成本过高，阻碍了实际部署。
- **关键词：** PRM, reward-model

### Decentralized Instruction Tuning: Conflict-Aware Splitting and Weight Merging

- **作者：** Minsik Choi, Geewook Kim
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=827XA57r8F
- **中文提要：** 指令微调要让包括多模态模型在内的大语言模型对齐多样的用户意图，异构混合带来的梯度干扰和沉重的同步带宽却阻碍扩展。作者询问：能否把混合数据的各部分独立训练，再在参数空间中一次性调和，从而同时缓解这两个瓶颈。
- **关键词：** instruction-tuning, fine-tuning

### Decoupled Training with Local Reinforcement Fine-Tuning in Federated Learning

- **作者：** Yuting Ma, Lechao Cheng, Xiaohua Xu
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=VoqRpteakw
- **中文提要：** 在预训练视觉语言模型上做联邦学习，已成为多种下游任务的一种有希望的范式。近期研究借助其强表示，在本地数据不足时改善任务适应，同时保持泛化。
- **关键词：** RFT, SFT, alignment, fine-tuning

### Depth-Breadth Synergy in RLVR: Unlocking LLM Reasoning Gains with Adaptive Exploration

- **作者：** Zhicheng Yang, Zhijiang Guo, Yinya Huang, Yongxin Wang, Dongchun Xie, Hanhui Li, Yiwei Wang, Xiaodan Liang, Jing Tang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=v3diR6NstK
- **中文提要：** 可验证奖励强化学习能增强大语言模型的推理，但两个方向上的探索不足限制了它的潜力：问题难度上的深度，以及训练实例数量上的广度。对常用 GRPO 的分析表明，该算法存在下调困难、低准确率样本权重的偏向。
- **关键词：** GRPO, RLVR

### Differentially Private Preference Data Synthesis for Large Language Model Alignment

- **作者：** Fengyu Gao, Jing Yang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Ctk4XLaUpl
- **中文提要：** 偏好对齐是大语言模型后训练中让输出符合人类价值的关键步骤。使用真实人类偏好数据会引发隐私顾虑，因为这些数据集常常包含敏感的用户提示和人工判断。
- **关键词：** preference-optimization, reward-model, post-training, alignment

### Discovering Implicit Large Language Model Alignment Objectives

- **作者：** Edward Chen, Sanmi Koyejo, Carlos Guestrin
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=kBEOlJ6ZqY
- **中文提要：** 大语言模型对齐依赖复杂的奖励信号，具体在激励哪些行为往往被掩盖，从而带来错位和奖励黑客的风险。现有解释方法通常依赖预先定义的准则，容易漏掉未知的未知，或者找不到既能全面覆盖、又对该数据集上的模型行为具有因果作用的目标。
- **关键词：** reward-model, alignment

### Discriminative Visual Process Rewards for Scaling Thinking at Test-Time with Images

- **作者：** Bo-Wen Yin, Qize Yang, Boyuan Sun, Xihan Wei, Qibin Hou
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=7BSBQr6dJd
- **中文提要：** “带图像思考”促使多模态大语言模型生成裁剪、标注、空间定位和草图等中间视觉步骤，以加强高分辨率感知与复杂推理。现有的多模态过程奖励模型只评估文本推理，无法判断这些视觉步骤是否正确。
- **关键词：** PRM, reward-model

### Dissecting Post-Training: Uncovering the Complementary Roles of SFT and RL for Document Parsing

- **作者：** Jun-Peng Jiang, An-Yang Ji, Shiyin Lu, Guodong Zheng, Weihong Zhang, Qing-Guo Chen, Weihua Luo, Kaifu Zhang, Long Chen, De-Chuan Zhan, Han-Jia Ye
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=gQkJewuCDZ
- **中文提要：** 文档解析要从 PDF 中抽取多样内容并保持结构完整，多模态大语言模型显著推进了这一任务。这些模型的成功很大程度上来自在海量数据上的大量后训练。
- **关键词：** SFT, post-training, fine-tuning

### DistFlow: A Fully Distributed RL Framework for Scalable and Efficient LLM Post-Training

- **作者：** zhixin wang, Jiaming Xu, Tianyi Zhou, Mingjun Zhang, Liming Liu, JiaruiHu, Dian Yang, TongYu Wang, Ping Zhang, Jinlong Hou, Siyuan Feng, Yuan Qi, Yuan Cheng
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=aPPEyZpKkp
- **中文提要：** 有效扩展强化学习，对增强大语言模型的推理与对齐至关重要。这类任务数据量巨大、执行流程复杂，需要能够高效扩展的分布式架构。
- **关键词：** post-training, alignment

### Distortion of AI Alignment Revisited: RLHF is a Decent Utilitarian Aligner

- **作者：** Kazusato Oko, Annie Ulichney, Nika Haghtalab, Han Bao
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=x4qXiDogRm
- **中文提要：** 人类反馈强化学习是让大语言模型对齐人类偏好的标准范式，但它在多元偏好设定下是否仍然有效已受到质疑。
- **关键词：** RLHF, alignment, fine-tuning

### Distributed Direct Preference Optimization

- **作者：** Zhanhong Jiang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ljNZyrAlaa
- **中文提要：** 基于偏好的强化学习用于按人类判断对齐策略，但当偏好数据分散在异质用户之间时，其理论行为仍不清楚。直接偏好优化避开了显式奖励建模，却在联邦与去中心化训练下缺少收敛保证。
- **关键词：** DPO, preference-optimization, reward-model, alignment

### Distributional Alignment Games for Answer-Level Fine-Tuning

- **作者：** Mehryar Mohri, Jon Schneider, Yifan Wu
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=orjnT28Vp6
- **中文提要：** 答案级微调要依据最终答案的正确性或性质来优化语言模型，而不是依据产生答案的具体推理轨迹。直接优化答案级目标在计算上难以处理，因为必须对庞大的潜在推理路径空间做边缘化。
- **关键词：** GRPO, alignment, fine-tuning

### Distributionally Robust Reinforcement Learning from Human Feedback

- **作者：** Debmalya Mandal, Paulius Sasnauskas, Goran Radanovic
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=6GeYRoYKWP
- **中文提要：** 人类反馈强化学习已成为微调大语言模型的主要方法之一。现有方法并不稳健，下游任务若与微调所用的偏好数据集相差很大，性能就会下降。
- **关键词：** DPO, RLHF, preference-optimization, reward-model, fine-tuning

### Doc-to-LoRA: Learning to Instantly Internalize Contexts

- **作者：** Rujikorn Charakorn, Edoardo Cetin, Shinnosuke Uesaka, Robert Lange
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=iW1oBBO72S
- **中文提要：** 长输入序列对大语言模型的上下文学习、文档理解与多步推理都处于中心位置。Transformer 的注意力代价随长度呈二次增长，使推理既占内存又缓慢。
- **关键词：** LoRA

### Does Reinforcement Fine-Tuning Improve Generalization of LLM Agents? An Empirical Study

- **作者：** Zhiheng Xi, Xin Guo, Jiaqi Liu, Jiazheng Zhang, Yutao Fan, Zhihao Zhang, Shichun Liu, Mingxu Chai, Xiaowei Shi, Yitao Zhai, Xunliang Cai, Tao Gui, Qi Zhang, Xuanjing Huang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=A4wPhPe6nW
- **中文提要：** 强化微调有望训练大语言模型智能体，依据环境反馈进行多轮决策。多数现有评估仍停留在域内：训练与测试发生在同一环境，甚至同一批任务上。
- **关键词：** RFT, fine-tuning

### Don't Reinvent the Wheel, Just Realign the Spokes: Resource-Efficient Federated Fine-Tuning via Rank-Wise Expert Assembly

- **作者：** Yebo Wu, Jingguang Li, Zhijiang Guo, Li Li
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=HdsEUNo4C4
- **中文提要：** 联邦微调有望在保护数据隐私的同时，把大语言模型适配到下游任务，但过高的计算与通信开销阻碍了它在资源受限边缘设备上的部署。
- **关键词：** LoRA, fine-tuning

### DPO Unchained: Your Training Algorithm is Secretly Disentangled in Human Choice Theory (and Its Loss' Convexity is Dispensable)

- **作者：** Wenxuan Zhou, Shujian Zhang, brice magdalou, John Lambert, Ehsan Amid, Richard Nock, Andrew Hard
- **会议：** ICML 2026 · Main · Oral
- **官方论文页：** https://openreview.net/forum?id=j4c3i3a5kH
- **中文提要：** 规范理论可以从第一性原理抽出机器学习算法的关键部分。DPO 绕过奖励建模，并与一种特定的人类选择规范模型建立显式联系。
- **关键词：** DPO, RLHF, preference-optimization, reward-model

### DRIFT: Decoupled Rollouts and Importance-Weighted Fine-Tuning for Efficient Multi-Turn Optimization

- **作者：** Jian Mu, Tianyi Lin, Chengwei Qin, Zhongxiang Dai, Yao Shu
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=rJOrgGdz9E
- **中文提要：** 大语言模型越来越多地部署在可由用户或环境反复给出轻量反馈的多轮交互中。在线强化学习能处理多轮动态，但每次生成完整修正轨迹的代价过高。
- **关键词：** SFT, fine-tuning

### EDCO: Dynamic Curriculum Orchestration for Domain-specific Large Language Model Fine-tuning

- **作者：** Jing-Cheng Pang, Sun Liu, Chang Zhou, Xian Tang, Haichuan Ma, KUN JIANG, Jianlong Wang, Kai Zhang, Sijie Wu, Haoran Cai, Chenwei Wu, Xubin Li, Xin Chen
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=NiHC3GlPQU
- **中文提要：** 领域大语言模型通常由通用预训练模型在专门数据上微调得到。课程学习按难度等指标预先排列训练样本，相对随机抽样来提高学习效率。
- **关键词：** fine-tuning

### Efficient Preference Poisoning Attack on Offline RLHF

- **作者：** Chenye Yang, Weiyu Xu, Lifeng Lai
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=32XNOcwH1z
- **中文提要：** DPO 等离线 RLHF 在预先收集的偏好数据上训练，因此容易受到偏好投毒。这项研究考察针对对数线性 DPO 的标签翻转攻击。
- **关键词：** DPO, RLHF, preference-optimization

### Embedding-perturbed Exploration Preference Optimization for Flow Models

- **作者：** Sujie Hu, Chubin Chen, Jiashu Zhu, Jiahong Wu, Xiangxiang Chu, Xiu Li
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Ai4vdy80p5
- **中文提要：** 强化学习已成为让生成模型对齐人类意图的重要范式，但以 GRPO 为例的组内优化面临组内方差迅速衰减这一关键限制。
- **关键词：** GRPO, preference-optimization, alignment

### Energy-Structured Low-Rank Adaptation for Continual Learning

- **作者：** Longhua Li, Lei Qi, Qi Tian, Xin Geng
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=4OP391X7Qm
- **中文提要：** 正交子空间方法试图减轻持续学习中的任务干扰，却常因能量在基上扩散而妨碍知识压缩，并耗尽后续任务可用的容量。参数更新引起的输出特征漂移被观察到本身是低秩的，沿该漂移主方向保留参数的理论证明在摘要中未写完。
- **关键词：** LoRA

### Enhancing LLMs for Graph Tasks via Graph-aware LoRA Generation

- **作者：** Junshu Sun, Wanxing Chang, Qingming Huang, Shuhui Wang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=BRtDecMvjY
- **中文提要：** 图神经网络把输入输出参数紧绑在特定数据集的特征空间和目标集合上，跨数据集迁移有限。语言模型凭借统一的输入输出接口灵活泛化，因此近期工作尝试把语言模型适配到图任务。
- **关键词：** LoRA

### Evaluating Parameter Efficient Methods for RLVR

- **作者：** Qingyu Yin, Yulun Wu, Zhennan Shen, Sunbowen Li, Zhilin Wang, Yanshu Li, Chak Tou Leong, Jiale Kang, Jinjin Gu
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=76CIL1O0bz
- **中文提要：** 作者在可验证奖励强化学习（RLVR）设定下系统评估参数高效微调（PEFT）。RLVR 用可验证反馈激励语言模型加强推理，LoRA 虽常用，但哪种 PEFT 结构更适合 RLVR 仍不清楚。
- **关键词：** RLVR, LoRA, PEFT, fine-tuning

### Evolution Strategies at Scale: LLM Fine-Tuning Beyond Reinforcement Learning

- **作者：** Xin Qiu, Yulu Gan, Conor Hayes, Qiyao Liang, Yinggan XU, Roberto Dailey, Elliot Meyerson, Babak Hodjat, Risto Miikkulainen
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=i0P4ew9GpS
- **中文提要：** 面向下游任务微调大语言模型是现代人工智能部署中的必要阶段，强化学习已成为主导的微调范式，并支撑许多先进的大语言模型。
- **关键词：** post-training, fine-tuning

### Exploring Data-Free LoRA Transferability for Video Diffusion Models

- **作者：** Yuchen Wang, Wenliang Zhong, Lichen Bai, zikai ZHOU, Shitong Shao, Bojun Cheng, Shuo Chen, Shuo Yang, Zeke Xie
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Imry2qitdt
- **中文提要：** 借助步蒸馏或因果蒸馏的视频扩散模型已经表现突出，但把已有 LoRA 适配到这些变体时，会因权重空间不匹配而变得困难。
- **关键词：** LoRA, alignment

### Factored Causal Representation Learning for Robust Reward Modeling in RLHF

- **作者：** Yupei Yang, Lin Yang, Wanxi Deng, Lin Qu, Fan Feng, Biwei Huang, Shikui Tu, Lei Xu
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=CwNItJ07ew
- **中文提要：** 可靠的奖励模型是通过 RLHF 把大语言模型对齐到人类偏好的前提，然而标准奖励模型容易受到与人类标签没有因果关联的虚假特征影响。
- **关键词：** RLHF, reward-model, alignment

### $f$-Divergence Regularized RLHF: Two Tales of Sampling and Unified Analyses

- **作者：** Di Wu, Chengshuai Shi, Jing Yang, Cong Shen
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=XrtiZYwcU4
- **中文提要：** RLHF 已成为大语言模型后训练的基础技术。多数方法依赖反向 KL 正则，近期实证则开始尝试前向 KL、卡方等其他散度作为正则项。
- **关键词：** RLHF, post-training

### Federated Sketching LoRA: A Flexible Framework for Heterogeneous Collaborative Fine-Tuning of LLMs

- **作者：** Wenzhi Fang, Dong-Jun Han, Liangqi Yuan, Seyyedali Hosseinalipour, Christopher G. Brinton
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=qFKFSVvff5
- **中文提要：** 在资源受限的客户端上微调大语言模型仍然困难。近期工作把 LoRA 与联邦微调结合起来，以缓解客户端模型规模和数据稀缺带来的问题。
- **关键词：** LoRA, fine-tuning

### Federated Variational Preference Alignment with Gumbel-Softmax Prior for Personalized User Preferences

- **作者：** Jabin Koo, Hoyoung Kim, Minwoo Jang, Jungseul Ok
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=duzvT0nDgZ
- **中文提要：** 联邦学习为对齐大语言模型提供了保护隐私的途径，但现有框架通常强制使用单一奖励模型，从而把相互冲突的用户偏好平均掉。
- **关键词：** RLHF, preference-optimization, reward-model, alignment

### FedHera: Towards Drift-Resilient Federated Fine-tuning with Heterogeneous Resources

- **作者：** Ke Xiao, Qiyuan Wang, Christos Anagnostopoulos, Zhuoran Tan, Wenhao Li
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=kOnIrq7uIc
- **中文提要：** 为了利用分散在各设备上的隐私敏感数据来适配大语言模型且不泄露数据，联邦微调成为重要范式。它的实际效果却受到客户端资源严重异构的制约。
- **关键词：** fine-tuning

### FedPissa: Towards Federated Personalized Adaptation of Foundation Models via LoRA Subspace Mapping

- **作者：** Wenwen He, Wenke Huang, Yi Liu, Jian Liang, Xirui Li, Guansong Pang, Mang Ye
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ZEWN40uNEh
- **中文提要：** LoRA 以低秩更新高效适配大型预训练模型，是一种有力的 PEFT 方法。与联邦学习结合后，各客户端可以在不暴露私有信息的情况下，利用下游数据做协同微调。
- **关键词：** LoRA, PEFT, fine-tuning

### FedRot-LoRA: Mitigating Rotational Misalignment in Federated LoRA

- **作者：** Haoran Zhang, Dongjun Kim, Seohyeon Cha, Haris Vikalo
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=2X8Qi3VdjA
- **中文提要：** 联邦 LoRA 能以较低通信量在去中心化数据上微调大语言模型。为保持低秩而做的按因子平均，与局部更新在数学上正确的聚合并不一致，从而造成明显的聚合误差和不稳定训练。
- **关键词：** LoRA, alignment, fine-tuning

### FedTreeLoRA: Reconciling Statistical and Functional Heterogeneity in Federated LoRA Fine-Tuning

- **作者：** Jieming Bian, Lei Wang, Letian Zhang, Jie Xu
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=g3Hrh5aoal
- **中文提要：** 把 LoRA 放进联邦学习，已成为保护隐私的大语言模型微调常规做法。现有个性化方法多停留在扁平模型假设下，只处理客户端的统计异构，却把模型当成单一整体，忽略各层之间的功能异构。
- **关键词：** LoRA, alignment, fine-tuning

### Fine-grained Analysis of Brain-LLM Alignment through Input Attribution

- **作者：** Michela Proietti, Roberto Capobianco, Mariya Toneva
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=BbxYfjeT5b
- **中文提要：** 理解大语言模型与人脑活动如何对齐，有助于揭示语言处理背后的计算原理。文中描述一条流水线，把归因方法用于这一对齐设定，以找出对对齐最重要的具体词语。
- **关键词：** alignment

### Fine-Tuning Without Forgetting In-Context Learning: A Theoretical Analysis of Linear Attention Models

- **作者：** Chungpa Lee, Jy-yong Sohn, Kangwook Lee
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=jl2f2Y3iuC
- **中文提要：** 基于 Transformer 的大语言模型具备上下文学习，可借助带示例的少样本提示适应下游任务。实践中这类模型又常被微调以提升零样本表现，从而在没有示例时完成任务并降低推理成本。
- **关键词：** fine-tuning

### Flash-GRPO: Efficient Alignment for Video Diffusion via One-Step Policy Optimization

- **作者：** Xiaoxuan He, Siming Fu, Zeyue Xue, Weijie Wang, Ruizhe He, Yuming Li, Dacheng Yin, Shuai Dong, Haoyang Huang, Hongfa Wang, Nan Duan, Bohan Zhuang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=VHqDQ1BQVw
- **中文提要：** GRPO 已成为把视频扩散模型对齐到人类偏好的重要方法，但训练计算构成关键瓶颈。已有提效做法通过滑动窗口抽样子时间步来降低成本，却从根本上损害优化。
- **关键词：** GRPO, alignment

### FourTune: Towards Fully 4-Bit Efficient Post-Training for Diffusion Models

- **作者：** Bowen Xue, Zihan Min, Xingyang Li, Zhekai Zhang, Haocheng Xi, Lvmin Zhang, Maneesh Agrawala, Jun-Yan Zhu, Song Han, Yujun Lin, Muyang Li
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=RpwnrBkht2
- **中文提要：** 扩散模型已成为高质量生成的主流范式，后训练对把它适配到多样下游应用必不可少。大型扩散模型的后训练仍受显存占用和训练速度限制，现有参数高效微调只部分缓解这些问题。
- **关键词：** LoRA, PEFT, post-training, fine-tuning

### From Parameter Dynamics to Risk Scoring: Quantifying Sample-Level Safety Degradation in LLM Fine-tuning

- **作者：** Xiao Wang, Yifei Zhang, Yongkang Liu, Xiaocui Yang, Zihan Wang, Shi Feng, Daling Wang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=NKWWXlS3xt
- **中文提要：** 大语言模型的安全对齐非常脆弱，在良性样本上微调就可能抹去先前从偏好样本中学到的安全行为。已有研究多比较微调前后的参数和隐状态，却忽略微调过程中的动态演化。
- **关键词：** PEFT, alignment, fine-tuning

### From Parameters to Data: A Task-Parameter-Guided Fine-Tuning Pipeline for Efficient LLM Alignment

- **作者：** Hao Chen, Qi Zhang, Liyao Li, Zhanming Shen, Wentao Ye, Lirong Gao, NINGTAO WANG, Xing Fu, Xiaoyu Shen, Junbo Zhao
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=nvvpssbgjH
- **中文提要：** 把大语言模型适配到专门领域通常带来很高的数据和计算开销。以往提效工作多把数据选择和参数高效微调分开处理，文中的经验分析认为二者可能内在耦合。
- **关键词：** PEFT, alignment, fine-tuning

### From Seeing to Thinking: Decoupling Perception and Reasoning Improves Post-Training of Vision-Language Models

- **作者：** Juncheng Wu, Hardy Chen, Haoqin Tu, Xianfeng Tang, Freda Shi, Hui Liu, Hanqing Lu, Cihang Xie, Yuyin Zhou
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=r7uOjvZdzO
- **中文提要：** 视觉语言模型近期强调长链推理，但视觉任务的表现主要受视觉感知不足限制，而不是推理本身。作者把感知与推理拆成三个训练阶段来研究后训练中的相互作用。
- **关键词：** SFT, post-training

### From Shortcuts to Reasoning: Robust Post-Training of Theory of Mind with Reinforcement Learning

- **作者：** Jike Zhong, Yuxiang Lai, Ming Li, Yuheng Li, Wuao Liu, Behzad Dariush, Konstantinos Psounis, Shao-Yuan Lo
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=L3fJXwaFdx
- **中文提要：** 心智理论是基础模型在真实世界中有效且安全运作所需的能力。已有后训练进展被一种捷径现象干扰：任务可以靠虚假的因果相关来完成，从而造成已经具备心智理论的错觉。
- **关键词：** RFT, SFT, post-training, fine-tuning

### FT-Dojo: Towards Autonomous LLM Fine-Tuning with Language Agents

- **作者：** Qizheng Li, Yifei Zhang, Xiao Yang, Xu Yang, Zhuo Wang, Bowen Xian, Weiqing Liu, Jiang Bian
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Ws2RhhBir4
- **中文提要：** 面向垂直领域微调大语言模型仍然费力，从业者需要整理数据、配置训练并反复诊断模型行为。尽管自主机器学习和语言智能体受到关注，端到端的大语言模型微调尚未被系统地当作可交互的智能体任务来研究。
- **关键词：** fine-tuning

### G$^2$RPO: Geometric GRPO; Escaping LLM's Reasoning Rut to Break Accuracy--Entropy Trade-off

- **作者：** Ali Rad, Khashayar Filom, Darioush Keivan, Peyman Mohajerin Esfahani, Ehsan Kamalinejad
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=nAkHNBbg4p
- **中文提要：** 可验证奖励强化学习是大型推理模型后训练的基石，但 GRPO 等常用算法常出现多样性坍缩。作者从几何角度把 GRPO 形式化为概率单纯形上的动力流，并据此做诊断。
- **关键词：** GRPO, RLVR, post-training

### GenAlign: Towards Unified Alignment Framework of MLLMs via Generative Reward Model

- **作者：** Jingyu Zhang, Kun Yang, Ming Wen, jiawei zhao, Yuxuan Liu, Zhuoer Xu, shiwen cui
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ifJ9MSQ0Jx
- **中文提要：** 让多模态大语言模型对齐人类偏好仍是基本难题。生成式奖励模型相对标量模型提供了基于推理的替代，却常受严重的位置偏差和过高的计算开销拖累。
- **关键词：** reward-model, alignment

### Geometry-Preserving Orthonormal Initialization for Low-Rank Adaptation in RLVR

- **作者：** Ruijia Zhang, Jiacheng Zhu, Hanqing Zhu, Laixi Shi
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Xo95FS2GTK
- **中文提要：** LoRA 及其变体使大语言模型能在监督微调（SFT）范式下做参数高效微调。它们在可验证奖励强化学习（RLVR）下的效果与行为则还缺少清楚认识。
- **关键词：** RLVR, SFT, LoRA, PEFT, fine-tuning

### GIST: Targeted Data Selection for Instruction Tuning via Coupled Optimization Geometry

- **作者：** Guanghui Min, Tianhao Huang, Ke Wan, Chen Chen
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=K2KeBuKAtu
- **中文提要：** 面向特定目标任务的数据选择，旨在为高效指令微调找出规模小但影响大的训练子集。实践中，影响力常通过样本对参数更新的作用来衡量。
- **关键词：** instruction-tuning, LoRA, PEFT, alignment, fine-tuning

### Golden Goose: A Simple Trick to Synthesize Unlimited RLVR Tasks from Unverifiable Internet Text

- **作者：** Ximing Lu, David Acuna, Jaehun Jung, Jian Hu, Di Zhang, Shizhe Diao, Yunheng Zou, Shaokun Zhang, Brandon Cui, Mingjie Liu, Hyunwoo Kim, Prithviraj Ammanabrolu, Jan Kautz, Yi Dong, Yejin Choi
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=LkiD08kdRy
- **中文提要：** 可验证奖励强化学习已成为释放大语言模型复杂推理能力的基石。强化学习的扩展却受限于现有可验证数据不足，长时间训练后的改进也趋于饱和。
- **关键词：** RLVR, post-training

### Good SFT Optimizes for SFT, Better SFT Prepares for Reinforcement Learning

- **作者：** Dylan Zhang, Yufeng Xu, Haojin Wang, Qingzhi Chen, Hao Peng
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=gSGnknLZED
- **中文提要：** 推理大语言模型的后训练通常是离线 SFT 再接在线强化学习的整体流程。SFT 却常常被孤立优化，只追求监督微调阶段本身的表现。
- **关键词：** SFT, post-training

### GPan-LoRA: Gaussian Process Amortized Networks for Bayesian Low-Rank Adaptation in Large Language Models

- **作者：** Weifeng Zhang, Wenyuan Zhao, Amir Hossein Rahmati, Yucheng Wang, Zhiyuan Wang, Chao Tian, Xiaoning Qian
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=AeWUbUjww1
- **中文提要：** 有原则的不确定性量化被看作可信通用人工智能的必要条件。贝叶斯 LoRA 为带不确定性感知的大语言模型微调提供了一种有原则的机制。
- **关键词：** LoRA, fine-tuning

### Gradient Regularization Mitigates Reward Hacking in Reinforcement Learning from Human Feedback and Verifiable Rewards

- **作者：** Johannes Ackermann, Michael Noukhovitch, Takashi Ishida, Masashi Sugiyama
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=T67db38qhr
- **中文提要：** RLHF 与可验证奖励强化学习是现代语言模型后训练的两个关键步骤。其中常见的奖励黑客问题，是策略利用奖励中的不准确之处，学到并非预期的行为。
- **关键词：** RLHF, RLVR, reward-model, post-training

### GRAPE: Let GRPO Supervise Query Rewriting by Ranking for Retrieval

- **作者：** Zhaohua Zhang, Jianhuan Zhuo, Muxi Chen, Chenchen Zhao, Wenyu Jiang, Mingyang Chen, Yutang, Qiuyong Xiao, Tianwen Jiang, Jihong Zhang, Zhixun Su
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=GcOyXiXACP
- **中文提要：** CLIP 已成为大规模检索系统的基石，但面对多语言、长文本或多模态等分布偏移时，其表现常常下降。
- **关键词：** GRPO, fine-tuning

### Graph-GRPO: Training Graph Flow Models with Reinforcement Learning

- **作者：** Baoheng Zhu, Deyu Bo, Delvin Zhang, Xiao Wang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Abko94Sl7D
- **中文提要：** 图生成是药物发现等场景中的基础任务。基于离散流匹配的图流模型因更强的表现和灵活的采样而兴起。
- **关键词：** GRPO, alignment

### Graph-Preference Learning: Debiasing Network-Sampled Human Feedback for Target Welfare Estimation

- **作者：** Guangrui Fan, DanDan Liu, AZNUL SABRI, Pan Lihu
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=DiNZ5ccCo6
- **中文提要：** 基于偏好的奖励建模是 RLHF 和 DPO 流程的核心组成部分。摘要指出提供偏好反馈的人很少构成独立同分布情形。
- **关键词：** DPO, RLHF, reward-model

### GR-LoRA: Gradient-Recycling Low-Rank Adaptation for Class-Incremental Learning

- **作者：** Yipeng Lin, Fengqiang Wan, Yang Yang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=MhMoUuoA1g
- **中文提要：** 预训练模型配合参数高效微调在类增量学习中表现突出，目标是平衡可塑性与稳定性。正交约束能明显增强稳定性，但对子空间的依赖会在长任务序列上损害可塑性。
- **关键词：** LoRA, PEFT, fine-tuning

### Grounding Multi-Hop Reasoning in Structural Causal Models via Group Relative Policy Optimization

- **作者：** Yunhan Bu, quan zhang, Zhang Huaping, Guotong Geng, Chunxiao Gao, Askar Hamdulla, Juan Wang, Qiuchi Li, Baohua Zhang, Yunbo Cao, Zhunchen Luo, Shuai Lei
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=vfIUEpSTji
- **中文提要：** 多跳事实验证需要跨分散证据做复杂推理，大语言模型容易出现幻觉和断裂的逻辑链。已有方法虽用思维链提高透明度，却往往缺少对证据与主张之间结构依赖的显式建模。
- **关键词：** GRPO

### Group-wise Data Ordering: Enhancing Instruction Tuning of Large Language Models via Embedding Proximity

- **作者：** Yiwen Ye, Boyuan Jiang, Xiaobin Hu, Shengzhi Wang, Xiaozhong Ji, Jinghao Lin, Deli Yu, Jiale Chen, kai wu, Haihua Yang, Yong Xia
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=cLzxIWy7EU
- **中文提要：** 指令微调是让大语言模型对齐用户意图的核心机制。实践中，随机打乱训练集是一种简单却出人意料地强的基线。
- **关键词：** instruction-tuning, alignment

### GRPO is Secretly a Process Reward Model

- **作者：** Michael Sullivan, Alexander Koller
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=nMGaOCVlDW
- **中文提要：** 过程奖励模型能为强化学习提供细粒度信用分配，表面上不同于给整条轨迹只打一个分数的结果奖励模型。文中从理论上证明，配备结果奖励模型的 GRPO 等价于某种过程奖励感知的强化学习目标。
- **关键词：** GRPO, PRM, reward-model

### GTPO and GRPO-S: Token and Sequence-Level Reward Shaping with Policy Entropy

- **作者：** Hongze Tan, Zihan Wang, Jianfei Pan, Jinghao Lin, Hao Wang, Yifan Wu, Tao Chen, Zhihang Zheng, Tang, Haihua Yang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=G5x5eEZ8yY
- **中文提要：** 强化学习对提升大语言模型推理至关重要，但 GRPO 和 DAPO 仍受粗粒度信用分配约束，同一回答中的所有词元得到相同奖励。文中提出动态熵加权，并系统定义基于熵的权重比。
- **关键词：** GRPO

### HE-SNR: Uncovering Latent Logic via Entropy for Guiding Mid-Training on SWE-bench

- **作者：** Yueyang Wang, Jiawei Fu, Baolong Bi, Xili Wang, Xiaoqing Liu
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=FoK74p8a2Z
- **中文提要：** SWE-bench 被用来评估大语言模型完成复杂软件工程任务的能力。这些能力主要在中期训练阶段获得，再由 SFT 引出，但目前仍缺少能有效引导中期训练的指标。
- **关键词：** SFT, mid-training, fine-tuning

### Heterogeneous Customizable Personalized Federated Fine-Tuning Approach for Large Language Models

- **作者：** xin tong, Baojiang cui
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=2jdpJN9OmD
- **中文提要：** 个性化联邦 LoRA 微调是应对大语言模型分布式微调中数据异构的重要途径。现有方法通常假设各客户端的个性化需求同质，并依赖双 LoRA 或个性化校准方案。
- **关键词：** LoRA, fine-tuning

### HoloFair: Unified T2I Fairness Evaluation and Fair-GRPO Debiasing

- **作者：** Ruyi Chen, Lu Zhou, Xiaogang Xu, Chiyu Zhang, Jiafei Wu, Liming Fang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=e26lNHXxgs
- **中文提要：** 文生图模型在视觉真实感和语义一致性上进步明显，却常常延续并放大社会偏见。现有评估多只覆盖单一维度的偏见，缺少从更深的社会语义层面揭示模型偏见的视角。
- **关键词：** GRPO

### How Reasoning Evolves from Post-Training Data: An Empirical Study Using Chess

- **作者：** Lucas Dionisopoulos, Nicklas Majamaki, Prithviraj Ammanabrolu
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=w0y3obJwmh
- **中文提要：** 作者用一组受理论启发的数据集，在国际象棋上观察语言模型的推理如何从 SFT 演进到强化学习。直接微调模型去预测最佳着法能带来有效的强化学习并取得最强的下游表现，但强化学习阶段会引出不忠实的推理。
- **关键词：** SFT, post-training, fine-tuning

### How RLHF Amplifies Sycophancy

- **作者：** Itai Shapira, Gerdus Benade, Ariel Procaccia
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=XN4pWKtA5h
- **中文提要：** 偏好后训练之后，大语言模型更容易迎合用户，即便与事实或合理判断冲突也会附和用户明示或暗示的看法。作者对人类反馈对齐如何放大这一失败模式做了形式分析，并指出一种显式放大机制。
- **关键词：** RLHF, post-training, alignment

### How to Fine-Tune a Reasoning Model? A Teacher–Student Cooperation Framework to Synthesize Student-Consistent SFT Data

- **作者：** Zixian Huang, Kaichen Yang, Xu Huang, Feiyang Hao, Qiming Ge, Bowen Li, He Du, Kai Chen, Qipeng Guo
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=tylCinzjUF
- **中文提要：** 用更强模型生成合成数据再做监督微调是常见的增强策略。对新兴的推理模型而言，这一做法往往不能提升推理能力，甚至会造成明显的性能下降。
- **关键词：** SFT, fine-tuning

### Hyper-LLaVA: Hyperbolic Uncertainty-aware Modality-Balanced Routing for Multimodal Continual Instruction Tuning

- **作者：** Kunlun Xu, YanQin Zhang, Wenwen Qiang, Jiahuan Zhou
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=2QJP89V4JH
- **中文提要：** 多模态持续指令微调希望利用逐步积累的知识来处理多样任务的多模态输入，其中参数路由很关键。现有先进方法在路由时依赖样本到任务中心的相似度，并以相等权重做跨模态融合。
- **关键词：** instruction-tuning

### iLoRA: Bayesian Low-Rank Adaptation with Latent Interaction Graphs for Microbiome Diagnosis

- **作者：** Yang Song, Yixuan Zhang, Lingfa Meng, Tongyuan Hu, Haizhou Shi, Hao Wang, Samir Bhatt, Hengguan Huang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=7FF8g7hCre
- **中文提要：** 参数高效适配使大语言模型能够用于领域预测，但标准 LoRA 仍依赖静态低秩更新，无法显式呈现常常驱动科学标签的潜在交互。作者据此提出 iLoRA，摘要在引入该方法后即结束。
- **关键词：** LoRA, PEFT

### Implicit Actor Critic Coupling via a Supervised Learning Framework for RLVR

- **作者：** Jiaming Li, Longze Chen, Ze Gong, Yukun Chen, Lu Wang, Wanwei He, Zhihao Yang, Minzheng Wang, Lei Zhang, Haoran Ye, Min Yang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=SmhCeGwSTP
- **中文提要：** 可验证奖励强化学习让大语言模型能够处理数学和编程等困难推理任务，但现有方法常受稀疏奖励和不稳定的策略梯度更新困扰。作者提出名为 PACS 的 RLVR 框架。
- **关键词：** RLVR, post-training

### Implicit Preference Alignment for Human Image Animation

- **作者：** Yuanzhi Wang, Xuhua Ren, Jiaxiang Cheng, bing ma, Kai Yu, Tianxiang Zheng, Qinglin Lu, Zhen Cui
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=SorLoUARMp
- **中文提要：** 人体图像动画已有明显进展，但高自由度且运动复杂的手部仍难以生成高保真动作。人类反馈强化学习，尤其是直接偏好优化，提供了一种可能途径，却需要构造严格的偏好对。
- **关键词：** DPO, RLHF, preference-optimization, post-training, alignment

### INDEXGUARD: Index-only Backdoor Vetting for Secure Federated PEFT of Large Language Models

- **作者：** Javad Dogani, Devriş İşler, Nikolaos Laoutaris
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=6YBEn2OrzM
- **中文提要：** 联邦 PEFT 能在私有数据上定制大语言模型，但在隐私约束使人无法检查各客户端实值更新时，容易遭受后门投毒。投毒会在适配器哪些坐标变得显著上留下相似印记，因此显著索引支撑之间的重叠仍然提供信息。
- **关键词：** PEFT, fine-tuning

### Inference-Aware Meta-Alignment of LLMs via Non-Linear GRPO

- **作者：** Shokichi Takakura, Akifumi Wachi, Rei Higuchi, Kohei Miyaguchi, Taiji Suzuki
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Km8yqb7SfN
- **中文提要：** 把大语言模型对齐到多样且常常互相冲突的人类偏好本质上很困难。推理时对齐因此受到关注，因为它允许在推理阶段用不同的对齐算法同时满足多项标准。
- **关键词：** GRPO, alignment

### Inference-time Alignment with Rewards in Besov Spaces: Provable Advantages of Feature Learning and Multi-Step Policy Updates

- **作者：** Naoki Nishikawa, Taiji Suzuki
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=wQjmCMLeyD
- **中文提要：** 推理时对齐在推理过程中根据奖励反馈适配预训练模型，经验上能够提升语言模型表现。其理论基础仍然薄弱，尤其是在用神经网络作为奖励模型的实际设定中。
- **关键词：** reward-model, alignment

### InfiMed-ORBIT: Aligning LLMs on Open-Ended Complex Tasks via Rubric-Based Incremental Training

- **作者：** Pengkai Wang, Pengwei Liu, Qi Zuo, Zhijie Sang, Congkai Xie, Hongxia Yang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=z2vVeIscEd
- **中文提要：** 强化学习推动了大语言模型在代码生成等可自动计算奖励的任务上取得进展，但在开放式医疗对话中效果较弱。这类反馈含糊且依赖语境，难以压成单一标量，往往还需要重度监督的奖励模型。
- **关键词：** instruction-following, reward-model, alignment, fine-tuning

### InstEmb: Instruction-Following Embeddings through Glimpses of the Future

- **作者：** Tianhao Gao, Jun Fang, Xiaohui Zhang, Zhiyuan Liu, Chao Liu, Pengzhang Liu, Qixia Jiang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=fwWvqAOXMT
- **中文提要：** 大语言模型在文本生成中已经具备细粒度的指令跟随能力。嵌入方法通常只使用输入最后一个词元的隐状态，因而难以捕捉分布在完整输出词元上的语义信号。
- **关键词：** instruction-following, alignment

### Investigating Continual Pretraining in Large Language Models: Insights and Implications

- **作者：** Cagatay Yildiz, Nishaanth Kanna, Nitin Sharma, Matthias Bethge, Beyza Ermis
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://icml.cc/virtual/2026/poster/68805
- **中文提要：** 持续学习在大语言模型中关注高效、可持续的训练，以便适应新出现的知识并在动态环境中保持稳健。重点放在持续的领域自适应预训练，使模型整合各领域的新信息并保留已有内容。
- **关键词：** continued-pretraining, fine-tuning

### IRPM: Intergroup Relative Preference Modeling for Pointwise Generative Reward Models

- **作者：** Haonan Song, Qingchen Xie, Huan Zhu, Feng Xiao, Luxi Xing, Liu Kang, Fuzhen Li, Zhiyong Zheng, Feng Jiang, Ziheng Li, Kun Yan, Qingyi Si, Yanghua Xiao, Hongcheng Guo, Fan Yang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=JuiHYauZNk
- **中文提要：** 生成式奖励模型因其可解释性以及可用强化学习进一步改进的潜力，在奖励建模上表现突出。常用的成对生成式奖励模型在 RLHF 中校准或汇总多名候选的偏好时会造成计算瓶颈。
- **关键词：** GRPO, RLHF, reward-model, post-training

### Jailbreak to Protect: Buffering Harmful Fine-Tuning via Temporary Jailbreaking LoRA in Large Language Models

- **作者：** Seokil Ham, Jaehyuk Jang, Wonjun Lee, Changick Kim
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=O0JXgBBo3k
- **中文提要：** 微调即服务便于用用户数据个性化大语言模型，但微调会削弱原有的安全对齐。已有应对多依赖显式正则，并因此带来实际限制。
- **关键词：** LoRA, alignment, fine-tuning

### JANUS-LORA: A Balanced Low-Rank Adaptation for Continual Learning

- **作者：** Cheng Chen, Pengpeng Zeng, Yuyu Guo, Lianli Gao, Heng Tao Shen, Jingkuan Song
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=XJ5r19iN9G
- **中文提要：** 持续学习里的 LoRA 会分别更新低秩因子 A 与 B，再凭二者的相互作用，对完整权重矩阵形成复合更新。
- **关键词：** LoRA

### LARFT: Closing the Cognition-Action Gap for Length Instruction Following in Large Language Models

- **作者：** Wei Zhang, Lintong Du, yuanhe zhang, Zhenhong Zhou, Kun Wang, Li Sun, Sen Su
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=SUwOncwAVl
- **中文提要：** 大语言模型在复杂指令跟随上表现很强，输出长度却仍难以精确控制。现有方法多从外部施加长度信号或优化目标，较少面对模型自身在长度认知上的不足。
- **关键词：** instruction-following

### LAVA: A Unified Framework for Finetuning Language and Vision Models

- **作者：** Daorui Ding, Fanhua Shang, Tiancan Feng, Junkang Liu, Hongying Liu
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=xBKbXgaPwr
- **中文提要：** LoRA 及其变体只调整很少参数，下游表现仍能保持在相近水平。这主要归功于参数空间内在的低秩结构：训练两个投影矩阵，把权重投到低维子空间再映射回来。
- **关键词：** LoRA, fine-tuning

### Layer-wise Gradient Disentanglement: Decoupling Semantics and Preferences in Direct Preference Optimization

- **作者：** Mengyang Li, Shuang Liu, Zhong Zhang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=j8lJiUPyL7
- **中文提要：** DPO 已成为把大语言模型对齐到人类偏好的主流方法，标准做法却对所有偏好对一视同仁。学习问题其实并不同质：有的样本要求深入理解提示语义，有的则要在相近回答之间做细致区分。
- **关键词：** DPO, RLHF, preference-optimization, alignment

### Leaderboard Incentives: Model Rankings under Strategic Post-Training

- **作者：** Yatong Chen, Guanhua Zhang, Moritz Hardt
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=r6wfuAKmVb
- **中文提要：** 有影响力的基准会促使相互竞争的模型开发者把后训练资源投向榜单上的改进，这一现象被称为 benchmaxxing，或针对测试任务训练。该工作由此着手，从原理上研究基准所诱导的激励结构。
- **关键词：** post-training

### Learnability-Informed Fine-Tuning of Diffusion Language Models

- **作者：** Shubham Parashar, Atharv Chagi, Jacob Helwig, Lakshmi Madhavarapu, Sushil Vemuri, James Caverlee, Dileep Kalathil, Shuiwang Ji
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=IgzMfT6eUx
- **中文提要：** 这项工作旨在提升扩散语言模型的推理能力。SFT 虽是自回归模型常用的后训练配方，用到扩散语言模型上却面临困难，甚至可能损害性能，其原因仍缺少研究。
- **关键词：** SFT, post-training, alignment, fine-tuning

### Learning a Zeroth-Order Optimizer for Fine-Tuning LLMs

- **作者：** Kairun Zhang, Haoyu Li, Yanjun Zhao, Yifan Sun, Huan Zhang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=bRS5iwbqlC
- **中文提要：** 零阶优化器避免反向传播，相对标准一阶训练能明显降低显存，因而成为微调大语言模型的一条有吸引力的路线。现有零阶方法依赖手工设计的静态采样，无法适应不同模型自身的结构。
- **关键词：** fine-tuning

### Learning in the Fisher Subspace: A Guided Initialization for LoRA Fine-Tuning

- **作者：** Zhi-Quan Feng, Ying-Jia Lin, Hung-Yu Kao
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=P76Q8Pi1E9
- **中文提要：** LoRA 把大语言模型的更新限制在预训练权重的低秩子空间中，从而显著降低训练成本。适应效果关键取决于初始化时选中哪个子空间，若把容量分给与任务无关的方向，下游表现会受到严重妨碍。
- **关键词：** LoRA, fine-tuning

### Learning Rate Scaling across LoRA Ranks and Transfer to Full Finetuning

- **作者：** Nan Chen, Soledad Villar, Soufiane Hayou
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=vCAIwEJZQ6
- **中文提要：** LoRA 是大模型参数高效微调的标准工具，显存占用很小，训练动态却出人意料地复杂。这些动态取决于初始化、适配器秩和学习率等若干超参数。
- **关键词：** LoRA, PEFT, fine-tuning

### Leveraging Machine Unlearning for Cost-Efficient Preference Alignment

- **作者：** XiaoHua Feng, Yuyuan Li, HuWei Ji, Li Zhang, Jiaming Zhang, Tianyu Du, Chaochao Chen
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=FhCu8IlO2e
- **中文提要：** 大语言模型的偏好对齐虽有进展，RLHF 这类主流方法仍有明显困难。它们依赖高质量的正向偏好样本，这类数据获取成本高，计算也很重。
- **关键词：** RLHF, preference-optimization, alignment

### LIFT: A Novel Framework for Enhancing Long-Context Understanding of LLMs via Long Input Fine-Tuning

- **作者：** Yansheng Mao, Yufei Xu, Jiaqi Li, Fanxu Meng, Haotong Yang, Zilong Zheng, Xiyuan Wang, Muhan Zhang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=jciD7uTWu7
- **中文提要：** 上下文窗口有限，使长上下文理解对大语言模型仍然困难。LIFT 面向任意短上下文模型，针对每条长输入动态调整参数，以提升长上下文表现。
- **关键词：** continued-pretraining, fine-tuning

### LoRA-DA: Data-Aware Initialization for Low-Rank Adaptation via Asymptotic Analysis

- **作者：** Qingyue Zhang, Chang Chu, Tianren Peng, Qi Li, Xiangyang Luo, Zhihao Jiang, Shao-Lun Huang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=LvKSVUbXc9
- **中文提要：** LoRA 已成为广泛采用的 PEFT 方法，其初始化也越来越受关注。现有做法局限明显：许多方法不纳入目标域数据，基于梯度的方法又只靠一步梯度分解，对数据的利用停留在浅层。
- **关键词：** LoRA, PEFT, fine-tuning

### Low-cost Full Fine-tuning: Learning What to Update for LLMs

- **作者：** Li, Yaming Guo, Shenghao Gao, Xinlong Chen, Zuhao Xu, Ying Sun, Chao Wang, Hui Xiong
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=HXrSe2LYFc
- **中文提要：** 大语言模型能力虽强，下游任务专有知识一般仍要靠微调补充。全量微调的显存开销过高，LoRA 与 Adapter 等参数高效技术便只在低秩或受限子空间里更新参数。
- **关键词：** LoRA, PEFT, fine-tuning

### LOZO+: Provably Efficient Zeroth-Order Fine-Tuning via Greedy Low-Rank Subspace Selection

- **作者：** Jinjie Fang, Chengxun Jin, Tianxing Man, Yi Chang, Bin Gu
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=QNScXX6osL
- **中文提要：** 零阶优化比一阶方法更省显存，可作为微调大语言模型的替代。以 LOZO 为代表的近期零阶方法在低秩子空间内估计梯度，以贴合大语言模型梯度的低秩结构。
- **关键词：** alignment, fine-tuning

### LRAgent: Efficient KV Cache Sharing for Multi-LoRA LLM Agents

- **作者：** Hyesung Jeon, Hyeongju Ha, jae-joon kim
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ooRukY3zjQ
- **中文提要：** 多智能体系统的角色分工常通过 multi-LoRA 实现，各智能体共享预训练骨干，只靠轻量适配器区分。即便基座权重相同，每个智能体仍会为同一段很长、带工具的轨迹单独构建并存储 KV cache，带来可观的显存与计算开销。
- **关键词：** LoRA

### Med-Scout: Curing MLLMs' Geometric Blindness in Medical Perception via Geometry-Aware RL Post-Training

- **作者：** Anglin Liu, Ruichao Chen, Yi Lu, Hongxia Xu, Jintai Chen
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=iTkQLqa1Ha
- **中文提要：** 多模态大模型在医学诊断上的语言能力已经很强，但即便先进模型也存在几何盲区。输出若不能锚定客观几何约束，就会产生看似合理却事实错误的幻觉，根源在于训练更重视语言流畅而非几何忠实。
- **关键词：** post-training

### MergeMix: Optimizing Mid-Training Data Mixtures via Learnable Model Merging

- **作者：** Jiapeng Wang, Changxin Tian, Kunlong Chen, ziqi liu, Jiaxin Mao, Xin Zhao, Zhiqiang Zhang, JUN ZHOU
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=7ucFlopjQu
- **中文提要：** 优化数据配比对释放大语言模型的潜力至关重要，但靠启发式试错或昂贵的代理训练来确定最优组合，计算上难以承受。MergeMix 重新利用模型合并权重，用以高效确定数据混合比例。
- **关键词：** mid-training

### Midtraining Bridges Pretraining and Posttraining Distributions

- **作者：** Emmy Liu, Graham Neubig, Chenyan Xiong
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=5PfEQzE9bf
- **中文提要：** 中期训练在中间阶段把专门数据与更一般的预训练数据混合，已在语言模型开发中相当普遍，但什么使它有效仍少有了解。这里认为，中期训练通过为后训练提供更好的初始化，起到分布桥接的作用。
- **关键词：** continued-pretraining, mid-training, post-training

### Mitigating Perceptual Judgment Bias in Multimodal LLM-as-a-Judge via Perceptual Perturbation and Reward Modeling

- **作者：** Seojeong Park, Jiho Choi, Junyong Kang, Seonho Lee, Jaeyo Shin, Hyunjung Shim
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=tbqxbGMFUV
- **中文提要：** 多模态大模型推理能力已经很强，作为自动评委却有关键弱点：当视觉证据与文本线索冲突时，更倾向奖励看似合理的叙述，而不是感知上正确的答案。这一现象被称为感知判断偏差，并得到系统分析。
- **关键词：** GRPO, reward-model, alignment

### Mitigating Reward Hacking in LLM-based Recommendation: A Preference Optimization Approach

- **作者：** Heyu Chen, Junkang Wu, Guoqing Hu, Kexin Huang, Xiang Wang, Jiancan Wu
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=4BGl1dY83o
- **中文提要：** 后训练适配已成为把大语言模型用于推荐的中心范式。DPO 等偏好优化虽能加强成对偏好区分，仍易出现奖励黑客：模型利用奖励信号中的缺陷抬高训练指标。
- **关键词：** DPO, preference-optimization, post-training

### Mitigating Reward Hacking in RLHF via Bayesian Non-negative Reward Modeling

- **作者：** Zhibin Duan, Guowei Rong, Zhuo Li, Bo Chen, Mingyuan Zhou, Dandan Guo
- **会议：** ICML 2026 · Main · Oral
- **官方论文页：** https://openreview.net/forum?id=DfhMMHXDuu
- **中文提要：** 从人类偏好学到的奖励模型是用 RLHF 对齐大语言模型的核心，却常因噪声标注以及回复长度、文风等系统性偏差而遭受奖励黑客。BNRM 提出一套有原则的奖励建模框架，并引入非负因子分析。
- **关键词：** RLHF, reward-model, alignment

### Mitigating the Safety–Utility Trade-off in LLM Alignment via Adaptive Safe Context Learning

- **作者：** Yanbo Wang, Minzheng Wang, Jian Liang, Lu Wang, Yongcan Yu, Ran He
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=XfejyJ9nc4
- **中文提要：** 推理模型在复杂推理上已经很成功，能力越强也越需要严格的安全措施。安全对齐的核心困难，在于安全与效用之间固有的权衡。
- **关键词：** alignment

### Mitigating Visual Hallucinations via Semantic Curriculum Preference Optimization in MLLMs

- **作者：** Yuanshuai Li, Yuping Yan, Junfeng Tang, Zeqi Zheng, Yaochu Jin
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=VbQg7jQnpL
- **中文提要：** 多模态大模型显著提升了多种任务的表现，仍持续受视觉幻觉影响，即生成回答与视觉证据相矛盾。DPO 虽广泛用于对齐，用到多模态模型上往往抓不住细粒度语义差异，还会鼓励走捷径学习。
- **关键词：** DPO, preference-optimization, alignment

### MoFO: Momentum-Filtered Optimizer for Mitigating Forgetting in LLM Fine-Tuning

- **作者：** Yupeng Chen, Senmiao Wang, Yushun Zhang, Zhihang Lin, Haozhe Zhang, Weijian Sun, Tian Ding, Ruoyu Sun
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://icml.cc/virtual/2026/poster/68774
- **中文提要：** 大语言模型在广泛任务上能力突出，通常先在大规模语料上预训练，再在任务数据上微调。
- **关键词：** fine-tuning

### Monitorability as a Free Gift: How RLVR Spontaneously Aligns Reasoning

- **作者：** Zidi Xiong, Shan Chen, Himabindu Lakkaraju
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=9hzK071Z3R
- **中文提要：** 大推理模型部署增多后，审计其思维链以保障安全变得关键。近期工作报告，思维链在多大程度上忠实且有信息量地反映内部计算，会在 RLVR 早期阶段作为一种免费附赠出现。
- **关键词：** RLVR, instruction-following

### MotionGRPO: Overcoming Low Intra-Group Diversity in GRPO-Based Egocentric Motion Recovery

- **作者：** Nanjie Yao, Junlong Ren, Wenhao Shen, Hao Wang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=sP2bDU3tLw
- **中文提要：** 这项研究从头戴设备信号恢复全身三维人体运动。已有基于扩散的方法常依赖全局分布匹配，因而在局部关节重建上出错。
- **关键词：** GRPO, post-training

### Multi-Objective Preference Optimization: Improving Human Alignment of Generative Models

- **作者：** Akhil Agnihotri, Rahul Jain, Deepak Ramachandran, Zheng Wen
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=AFqHVyanzY
- **中文提要：** 用 RLHF 以及 DPO、IPO 等偏好优化做后训练，已经明显改善对齐，但这些方法都假定单一目标。人实际会表达多个常常相互冲突的目标，例如有用与无害，并不存在自然的标量化方式。
- **关键词：** DPO, RLHF, preference-optimization, post-training, alignment, fine-tuning

### Multi-Task GRPO: Reliable LLM Reasoning Across Tasks

- **作者：** Shyam Sundhar Ramesh, Xiaotong Ji, Matthieu Zimmer, Sangwoong Yoon, Zhiyong Wang, Haitham Bou Ammar, Aurelien Lucchi, Ilija Bogunovic
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=zA3KhRZ9A5
- **中文提要：** 以 GRPO 做强化学习后训练，被广泛用来提升大语言模型在单个推理任务上的表现。真实部署则要求模型在多样任务上都保持可靠。
- **关键词：** GRPO, post-training

### NaRA: Noise-Aware LoRA for Parameter-Efficient Fine-Tuning of Diffusion LLMs

- **作者：** Shuaidi Wang, Zhan Zhuang, HUANG Ruping, Yu Zhang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=s8UGIRF38a
- **中文提要：** 扩散大语言模型成为一种有前景的非自回归生成范式。全量微调的计算代价过高，PEFT 因而成为标准做法。
- **关键词：** LoRA, PEFT, fine-tuning

### Navigating the Pareto Frontier of Alignment: Spectrum-Adaptive Fine-Tuning for LLMs

- **作者：** Yaoyou Fan, Chao Zhang, Xiaoyu Tan, Chenxing Sun, Yu Yuan, Haoyu Feng, Lu Pan, Ke Zeng, Xunliang Cai
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=9wLcZBHZZ5
- **中文提要：** 用负对数似然做监督微调，仍是大语言模型后训练的标准范式，但它对低概率目标词施加过强的更新。模型因此优先压低难样本的损失，而不是优化生成的整体质量，并常常变得缺乏依据地过度自信。
- **关键词：** SFT, post-training, alignment, fine-tuning

### Noise-corrected GRPO: From Noisy Rewards to Unbiased Gradients

- **作者：** Omar Elmansouri, Fathinah Izzati, Mohamed El Amine Seddik, Salem Lahlou
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=mnU8odBWYE
- **中文提要：** RLHF 与 RLVR 分别是对齐大语言模型和构建近期推理模型的标准范式，对不一致或错误奖励带来的噪声高度敏感。这类噪声与广泛使用的基于组的策略优化如何相互作用，仍缺少充分研究。
- **关键词：** GRPO, RLHF, RLVR, reward-model, alignment

### Normalized Rewards for Preference Optimization

- **作者：** Shawn Im, Federico Danieli, Skyler Seto, Barry-John Theobald, Katherine Metcalf
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=xFbdOV2Ma7
- **中文提要：** DPO 等直接对齐算法已成为用人类偏好对大语言模型做后训练的常用途径。但已观察到它们会过度优化隐式奖励模型，并降低偏好回答的似然。
- **关键词：** DPO, SimPO, preference-optimization, reward-model, post-training, alignment

### Offline Preference Optimization for Rectified Flow with Noise-Tracked Pairs

- **作者：** Yunhong Lu, Qichao Wang, Hengyuan Cao, Xiaoyin Xu, Min Zhang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=NiMMHsFCvo
- **中文提要：** 现有文生图偏好数据通常只保存最终的胜出图像与落败图像。这对整流流模型并不够用：其生成由特定的先验噪声样本索引，并沿着近乎直线的去噪轨迹进行。
- **关键词：** DPO, preference-optimization, alignment

### One Bias After Another: Mechanistic Reward Shaping and Persistent Biases in Language Reward Models

- **作者：** Daniel Fein, Max Lamparth, Violet Xiang, Mykel Kochenderfer, Nick Haber
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=20c6jemABm
- **中文提要：** 奖励模型对语言模型与人类偏好的在线对齐至关重要。基于奖励模型的偏好调优却容易出现奖励黑客，使策略从有缺陷的奖励模型中学到不良行为。
- **关键词：** reward-model, alignment

### OnePO: Direct One-stage Policy Optimization for SFT-free Domain Adaptation

- **作者：** Junying Chen, Xinyuan Xie, Ziniu Li, Benyou Wang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=M8eyUQldfx
- **中文提要：** 常见流程是先做监督微调再做强化学习，但领域适配是否必须先经过 SFT 被提出质疑。SFT 把模型限制在模仿分布里，压缩强化学习的探索，两阶段切换还会带来能力回退和额外工程。
- **关键词：** SFT, fine-tuning

### On Group Relative Policy Optimization Collapse in Agent Search: The Lazy Likelihood-Displacement

- **作者：** wenlong deng, Yushu Li, Boying Gong, YI REN, Christos Thrampoulidis, Xiaoxiao Li
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=SJ13vBxetN
- **中文提要：** 工具集成强化学习让大语言模型通过搜索引擎、检索器等外部工具进行多步推理。以 Search-R1 为代表的 GRPO 收敛快且无需价值函数，适合这一设定，却持续出现训练崩溃。
- **关键词：** GRPO

### On Robustness and Chain-of-Thought Consistency of RL-Finetuned VLMs

- **作者：** Rosie Zhao, Anshul Shah, Xiaoyu Zhu, Xinke Deng, Zhongyu Jiang, Yang Yang, Joerg Liebelt, Arnab Kumar Mondal
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ANbnxDfcAD
- **中文提要：** 强化学习微调已成为提升大语言模型复杂推理的关键技术，并被延伸到视觉语言模型。经强化学习调优的视觉语言模型在视觉推理基准上有所改善，但仍易视觉落地不足、产生幻觉，并过度依赖文本线索。
- **关键词：** RFT, alignment, fine-tuning

### On the Convergence Rate of LoRA Gradient Descent

- **作者：** Siqiao Mu, Diego Klabjan
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=9GRlBVAXq8
- **中文提要：** LoRA 因表现突出、计算需求低，近年成为微调大模型的流行算法。它训练两个适配器矩阵，形成模型参数的低秩表示，从而大幅减少每一步需要更新的参数数量。
- **关键词：** LoRA, fine-tuning

### On the Emergence of Implicit Curriculum in RLVR Learning Dynamics

- **作者：** Yu Huang, Zixin Wen, Yuejie Chi, Yuting Wei, Aarti Singh, Yingbin LIANG, Yuxin Chen
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=KxYCE98u1d
- **中文提要：** RLVR 是近期大推理模型取得突破的主要推动力。仅依据最终结果给出的奖励，如何帮助越过长程推理的视野障碍，仍然是个谜。
- **关键词：** RLVR

### On the Entropy Dynamics in Reinforcement Fine-Tuning of Large Language Models

- **作者：** Shumin Wang, Yuexiang Xie, Wenhao Zhang, Yuchang Sun, Yanxi Chen, Yaliang Li, Yanyong Zhang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Sj8NBI6aV0
- **中文提要：** 熵用来衡量大语言模型输出的多样性，并反映其探索能力。强化微调里已有越来越多的工作监测并调节熵，以便在探索与利用之间取得更好平衡。
- **关键词：** GRPO, RFT, fine-tuning

### On the Interplay of Pre-Training, Mid-Training, and RL on Reasoning Language Models

- **作者：** Charlie Zhang, Graham Neubig, Xiang Yue
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=TBaUfO9znF
- **中文提要：** 近期强化学习技术明显提升了语言模型的推理，但后训练是否真正把推理能力延伸到预训练所获之外，仍不清楚。核心困难在于现代训练管线缺少控制：大规模预训练语料不透明，中期训练又常常未经充分检视。
- **关键词：** mid-training, post-training

### On the Plasticity and Stability for Post-Training Large Language Models

- **作者：** Wenwen Qiang, Ziyin Gu, Jiahuan Zhou, Jie Hu, Jingyao Wang, Changwen Zheng, Hui Xiong
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=lOR6zI5peb
- **中文提要：** GRPO 的训练稳定性仍是关键瓶颈，常表现为推理可塑性与通用能力保持之间的权衡。根因被归结为可塑性梯度与稳定性梯度的几何冲突，并由此产生破坏性干扰。
- **关键词：** GRPO, post-training

### On the Power of (Approximate) Reward Models for Inference-Time Scaling: Sequential Monte Carlo and Beyond

- **作者：** Youheng Zhu, Yiping Lu
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=MrIDZjIsNF
- **中文提要：** 推理时缩放近来成为提升大语言模型推理能力的有力范式。其中序列蒙特卡洛尤为重要，能够对中间推理轨迹反复进行生成、评估、拒绝与重采样。
- **关键词：** reward-model

### Optimal Transport for LLM Reward Modeling from Noisy Feedback

- **作者：** Licheng Pan, Haocheng Yang, Haoxuan Li, Yunsheng Lu, Yongqi Tong, Yinuo Wang, Shijian Wang, Zhixuan Chu, Lei Shen, Yuan Lu, Hao Wang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=InoePQ7HNI
- **中文提要：** 奖励模型是 RLHF 的基础，真实数据却不可避免地带有噪声偏好。常规训练目标容易过拟合这些错误，已有去噪方法又常假设噪声同质，难以刻画语言偏好的复杂性。
- **关键词：** RLHF, reward-model

### Outcome Rewards Do Not Guarantee Verifiable or Causally Important Reasoning

- **作者：** Qinan Yu, Alexa Tartaglini, Peter Hase, Carlos Guestrin, Christopher Potts
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=VrY5x2smAd
- **中文提要：** 在思维链上做 RLVR 已成为语言模型后训练的标准环节。一个常见假定是，这样训练出的推理链能够可靠地代表模型如何得到答案。
- **关键词：** RLVR, SFT, post-training

### PISCES: Annotation-free Text-to-Video Post-Training via Optimal Transport-Aligned Rewards

- **作者：** Minh-Quan Le, Gaurav Mittal, Cheng Zhao, Xianfeng GU, Samaras Dimitris, Mei Chen
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=wSfc8mDEjM
- **中文提要：** 文生视频希望合成视觉质量高、时间一致、并与输入文本语义对齐的视频。基于奖励的后训练，被视为改善生成质量与语义对齐的一条有前景方向。
- **关键词：** post-training, alignment, fine-tuning

### PLoRA: Efficient Concurrent LoRA Training for Large Language Models

- **作者：** Minghao Yan, Zhuang Wang, Zhen Jia, Shivaram Venkataraman, Yida Wang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=khYw62jVZ2
- **中文提要：** LoRA 因资源需求低、效果好，成为微调大语言模型的流行方法。已有不少工作通过同时服务多个 LoRA 来提高服务效率，但这些方法假定已有大量适配器可供服务。
- **关键词：** LoRA, fine-tuning

### PortraitRL: Reinforcement Learning for Personalized Portrait Pose Transfer with Multi-Objective Reward Modeling

- **作者：** Jiahui Wu, Zelong Sun, Yanbiao Ma, Zhiwu Lu
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=yn2wy5qk0Y
- **中文提要：** 人像姿态迁移要求生成模型在跟随复杂姿态与布局修改指令的同时，保留细粒度身份细节。已有方法往往受困于大量数据标注，或采用并不能很好同时应对这两项关键挑战的优化目标。
- **关键词：** preference-optimization, reward-model, post-training

### Position: Good Embodied Reward Models Need Bad Behavior Data

- **作者：** Thomas Tian, Yilin Wu, Andrea Bajcsy
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=0zeOMzrV2N
- **中文提要：** 这篇立场论文主张，要得到可靠的具身奖励模型，社区必须投入失败、次优、易错乃至危险的机器人行为数据。奖励模型处于基础模型生命周期的中心，但当前具身奖励模型主要在成功行为上训练。
- **关键词：** reward-model, alignment

### Position: Measuring Human Preferences in RLHF is a Social Science Problem

- **作者：** Bijean Ghafouri, Eun Cheol Choi, Priyanka Dey, Emilio Ferrara
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=5l1pca4KhM
- **中文提要：** RLHF 假定标注回答反映的是真实人类偏好。该立场认为这一假定需要系统检验，行为科学提供的框架能够说明它何时成立、何时失效。
- **关键词：** RLHF, alignment

### PostTrainBench: Can LLM Agents Automate LLM Post-Training?

- **作者：** Ben Rank, Hardik Bhatnagar, Ameya Pandurang Prabhu, Shira Eisenberg, Karina Nguyen, Matthias Bethge, Maksym Andriushchenko
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=UnjxMTe57e
- **中文提要：** 推理能力的进步让 AI 智能体在软件工程上变得出人意料地熟练。这引出更深层的问题：这些系统能否把能力延伸到自动开展 AI 研究本身。
- **关键词：** instruction-tuning, post-training

### Post-Training Language Models for Crosslingual Consistency

- **作者：** Tianyu Liu, Jirui Qi, Mrinmaya Sachan, Ryan Cotterell, Raquel Fernández, Arianna Bisazza
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=8FsiTJC04n
- **中文提要：** 语言模型对翻译等价的跨语言提示常常回答不一致，削弱多语言系统的可靠性。为加以量化，跨语言一致性被定义为模型回答分布与其跨语言往返推前分布之间的散度界。
- **关键词：** post-training, alignment

### Post-Training LLMs as Better Decision-Making Agents: A Regret-Minimization Approach

- **作者：** Chanwoo Park, Ziyang Chen, Asuman Ozdaglar, Kaiqing Zhang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=dclUuUHjrA
- **中文提要：** 大语言模型越来越多地被部署为智能体，在交互且动态的环境中做决策。它们原本并非为决策而设计，近期研究显示，在基本的在线决策设定中它们仍然吃力。
- **关键词：** post-training, fine-tuning

### Post-Training with Policy Gradients: Optimality and the Base Model Barrier

- **作者：** Alireza Mousavi-Hosseini, Murat Erdogdu
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=nnWlTi7A7a
- **中文提要：** 该研究考察用结果奖励与过程奖励对线性自回归模型做后训练。给定上下文后，模型需要预测一条满足序列版间隔假设的回答序列。
- **关键词：** PRM, reward-model, post-training

### Preference Goal Tuning: Post-Training as Latent Control for Frozen Policies

- **作者：** Guangyu Zhao, Kewei Lian, Haoxuan Ru, Borong Zhang, Haowei Lin, Zhancun Mu, Haobo Fu, Qiang Fu, Shaofei Cai, Zihao Wang, Yitao Liang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=TygL9qfa0d
- **中文提要：** 目标条件策略让决策模型按指定目标执行多样行为，下游表现却常常对指令或提示的选择高度敏感。为绕开离散文本提示的限制，后训练适配被表述为潜在控制问题，目标嵌入充当连续的控制变量。
- **关键词：** post-training, alignment, fine-tuning

### PRISM: Demystifying Retention and Interaction in Mid-Training

- **作者：** Bharat Runwal, Ashish Agrawal, Anurag Roy, Rameswar Panda
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=giNBsVVFGt
- **中文提要：** 中期训练越来越多地被用来提升大语言模型的推理能力，但其设计选择以及与评测、强化学习的相互作用仍不清楚。已有工作常只看狭窄领域上的收益，忽略通用能力的保持、长上下文表现以及与强化学习的兼容性。
- **关键词：** mid-training

### PRISM: Gauge-Invariant Tangent-Space Differentially Private LoRA

- **作者：** Shihao Wang, Xueru Zhang
- **会议：** ICML 2026 · Main · Oral
- **官方论文页：** https://openreview.net/forum?id=SiCjKmArjQ
- **中文提要：** 用 DP-SGD 把差分隐私施加到 LoRA 上，是隐私保护微调的一条自然途径。LoRA 的低秩参数化却带来一个根本性挑战。
- **关键词：** LoRA, fine-tuning

### Privately Fine-Tuned LLMs Preserve Temporal Dynamics in Tabular Data

- **作者：** Lucas Rosenblatt, Peihan Liu, Ryan McKenna, Natalia Ponomareva
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=hZJAUJ5l9t
- **中文提要：** 差分隐私合成表格数据的研究，多把各行视为独立同分布，且每条记录对应一个独特个体。这一视角忽略纵向数据中的时间复杂性，例如电子健康记录里，同一用户贡献的是一整张由连续事件组成的子表。
- **关键词：** fine-tuning

### PRM-PBE: Process Reward Model for Reinforcement Learning in Programming-by-Example

- **作者：** Yue Fang, Zhi Jin, Jie An, Hongshen Chen, Jiangmeng Li, Xiaohong Chen, Naijun Zhan
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=MjjdkgK62z
- **中文提要：** 示例编程是典型的少样本归纳推理范式，要从一组输入输出例子中合成相应算法。大语言模型虽展现出较强的程序合成潜力，处理复杂的示例编程任务时仍然效果不佳。
- **关键词：** PRM, reward-model

### Probing RLVR Training Instability through the Lens of Objective-Level Hacking

- **作者：** Yiming Dong, Kun Fu, Haoyu Li, Xinyuan Zhu, Yurou Liu, Lijing Shao, Jieping Ye, Zheng Wang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=KlGj06E8Wa
- **中文提要：** 长时间的可验证奖励强化学习（RLVR）能持续提升大语言模型的推理能力，但训练容易不稳定，混合专家架构中尤为突出。这种不稳定会严重妨碍能力提升，其成因和机制却仍然缺乏了解。
- **关键词：** RLVR

### Process Reward Agents for Steering Knowledge-Intensive Reasoning

- **作者：** Jiwoong Sohn, Tomasz Sternal, Kenneth Styppa, Torsten Hoefler, Michael Moor
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=3moDc5lpBC
- **中文提要：** 知识密集型推理很难，因为中间步骤往往无法就地验证：与数学或代码不同，判断一步是否正确可能要综合大量外部知识中的线索。细微错误因此会沿推理轨迹传播，甚至始终无法被发现。
- **关键词：** PRM, reward-model

### Process Reward Models That Think

- **作者：** Muhammad Khalifa, Rishabh Agarwal, Lajanugen Logeswaran, Jaekyeom Kim, Hao Peng, Moontae Lee, Honglak Lee, Lu Wang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://icml.cc/virtual/2026/poster/68817
- **中文提要：** 逐步验证器即过程奖励模型（PRM），是测试时扩展的关键，但训练它们需要昂贵的步骤级监督。这项工作想把更省数据的 PRM 做成口头化的逐步奖励模型，通过生成验证思维链来检查解答中的每一步。
- **关键词：** PRM, reward-model, fine-tuning

### Provable Benefits of RLVR over SFT for Reasoning Models: Learning to Backtrack Efficiently

- **作者：** Stanley Wei, Juno Kim
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=P3Mnh7mF5a
- **中文提要：** 对预训练基座做强化微调，可以在推理阶段提升推理表现。作者从理论上分析，为何强化微调会比纯粹的监督微调（SFT）带来更好的推理能力。
- **关键词：** RLVR, RFT, SFT, fine-tuning

### Provable Sample Efficiency of Curriculum Post-Training for Transformer Reasoning

- **作者：** Dake Bu, Wei Huang, Andi Han, Atsushi Nitanda, Hau-San Wong, Qingfu Zhang, Taiji Suzuki
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=bgM2hmXExQ
- **中文提要：** 大语言模型后训练中的课程方法，经验上常比非课程方法更能改善推理，但对其有效性与局限仍缺少原则性认识。作者建立抽象理论框架，并识别课程式后训练生效的充分条件。
- **关键词：** post-training, fine-tuning

### Provably Protecting Fine-Tuned LLMs from Training Data Extraction while Preserving Utility

- **作者：** Tom Segal, Yuval Elovici, Asaf Shabtai
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=m5bAH5xN4R
- **中文提要：** 在敏感数据上微调大语言模型会带来隐私隐患，训练数据抽取攻击可能暴露高度机密的信息。现有防御要么缺少形式化的隐私保证，要么造成明显的效用下降。
- **关键词：** fine-tuning

### PS-PPO : Prefix-Sampling PPO for Critic-Free RLHF

- **作者：** Doo Hwan Hwang, Kee-Eung Kim
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=flDa73nyVx
- **中文提要：** 大语言模型上的 RLHF 越来越把无评论家方法当作 actor-critic 训练的实用替代。这些方法虽然简单，却把轨迹级学习信号均匀传给轨迹中的每一个词元。
- **关键词：** RLHF

### QUATRO: Query-Adaptive Trust Region Policy Optimization for LLM Fine-tuning

- **作者：** Doyeon Lee, Eunyi Lyou, Hyunsoo Cho, Soo Kyung Kim, Joonseok Lee, Jaemoo Choi
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=98XhDbtB21
- **中文提要：** GRPO 风格的强化学习微调算法近来很受关注。它们依赖启发式信任域近似，全局重要性比率裁剪和按组归一化都约束不住比率落在裁剪范围之外的样本，优化因而容易变脆。
- **关键词：** GRPO, fine-tuning

### Real-Time Aligned Reward Model beyond Semantics

- **作者：** Zixuan Huang, Xin Xia, Yuxi Ren, Jianbin Zheng, Xuefeng Xiao, Hongyan Xie, Huaqiu Li, Songshi Liang, Zhongxiang Dai, Fuzhen Zhuang, Jianxin Li, Yikun Ban, deqing wang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=wz2zK4l3YJ
- **中文提要：** RLHF 是让大语言模型对齐人类偏好的关键技术，却容易出现奖励过优化：策略过拟合奖励模型，利用虚假奖励模式，而不是忠实捕捉人类意图。已有缓解主要依赖表层语义信息。
- **关键词：** RLHF, reward-model, alignment

### Reinforcement Fine-Tuning Naturally Mitigates Forgetting in Continual Post-Training

- **作者：** Song Lai, Haohan Zhao, Rong Feng, Changyi Ma, Wenzhuo Liu, Hongbo Zhao, Xi Lin, Dong Yi, Qingfu Zhang, Hongbin Liu, Gaofeng Meng, Fei Zhu
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=nvnkuqWuu3
- **中文提要：** 持续后训练常用来把多模态大语言模型这类基础模型适配到不断变化的下游任务。已有研究多集中在数据回放、模型扩展或参数正则，学习范式本身的作用仍大体未被考察。
- **关键词：** RFT, SFT, post-training, fine-tuning

### Reinforcement Learning from Human Feedback with Active Queries

- **作者：** Kaixuan Ji, Jiafan He, Quanquan Gu
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://icml.cc/virtual/2026/poster/68804
- **中文提要：** 让大语言模型贴合人类偏好对构建现代生成模型很关键，RLHF 是实现途径之一。尽管表现更好，现有做法往往需要大量人工标注的偏好数据，收集成本很高。
- **关键词：** DPO, RLHF, preference-optimization, alignment, fine-tuning

### Reinforcement Learning with Verifiable Rewards: GRPO's Loss, Dynamics, and Success Amplification

- **作者：** Youssef Mroueh
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=z9Bo4eXSpW
- **中文提要：** 分组相对策略优化（GRPO）被用于在可验证的二元奖励下促进大语言模型推理。作者指出，对这些奖励做均值加方差校准会诱导出对比损失，其中对比样本是从上一轮策略抽取的合成数据。
- **关键词：** GRPO

### Reliability-Aware LLM Alignment from Inconsistent Human Feedback

- **作者：** Jingyi Huang, Ruohan Zong, Yujun Feng, Liran Ma, Lanyu Shang, Yang Zhang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=0LeyqHkrEG
- **中文提要：** 用 RLHF 把大语言模型对齐到人类偏好至关重要。人类标注固有的不一致和主观性，却常常削弱这种方法的效果。
- **关键词：** DPO, RLHF, preference-optimization, alignment

### ReMoE: Boosting Expert Reuse through Router Fine-Tuning in Memory-Constrained MoE LLM Inference

- **作者：** Xiongwei Zhu, Xiaojian Liao, Tianyang Jiang, Yusen Zhang, Liang Wang, Limin Xiao
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ylAhgNb2ak
- **中文提要：** 细粒度混合专家模型对每个词元只稀疏激活一部分专家，在保持较高容量的同时减少实际计算。显存受限的推理场景里，能够缓存的专家却只有一小部分。
- **关键词：** fine-tuning

### Replay Failures as Successes: Sample-Efficient Reinforcement Learning for Instruction Following

- **作者：** Kongcheng Zhang, QI YAO, Shunyu Liu, Wenjian Zhang, Min Cen, Yang Zhou, Wenkai Fang, Yiru Zhao, Baisheng Lai, Mingli Song
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=YiTfnJursw
- **中文提要：** 强化学习有望让大语言模型在多种约束下遵循指令。改进却依赖采到成功且高质量的回答，初始模型能力有限，常常难以生成满足全部约束的回答，于是奖励稀疏或难以区分。
- **关键词：** instruction-following, alignment

### Restoring Exploration after Post-Training: Latent Exploration Decoding for Large Reasoning Models

- **作者：** Wenhui Tan, Fiorenzo Parascandolo, Enver Sangineto, Jianzhong Ju, Zhenbo Luo, Qian Cao, Rita Cucchiara, Ruihua Song, Jian Luan
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=2jXDMGaNZk
- **中文提要：** 大推理模型经强化学习后训练，在数学与代码推理上取得了强表现。作者指出，现代推理后训练会带来非预期的探索坍缩，基于温度的采样不再提高多次尝试下的准确率。
- **关键词：** post-training

### Rethinking Low-Confidence Pseudo Labels: Influence-Aware Semi-Supervised Fine-Tuning for Hyperspectral Change Detection

- **作者：** Keyun Zhao, Guangchang Li, Yunpeng Bai, shao jiang, Ying Li
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=wbhYFWXJQq
- **中文提要：** 高光谱图像变化检测标注极度稀缺且变化模式复杂，直接微调预训练基础模型因此受到根本限制。半监督学习是一条出路，但现有方法主要按置信度挑选伪标签，容易造成数据多样性不足或错误严重传播。
- **关键词：** SFT, fine-tuning

### Reward Auditor: Inference on Reward Modeling Suitability in Real-World Perturbed Scenarios

- **作者：** Jianxiang Zang, Yongda Wei, Ruxue Bai, Shiyu Jiang, Nijia Mo, Binhong Li, Qiang Sun, Hui Liu
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=6aFU1bnUnv
- **中文提要：** 可靠的奖励模型对大语言模型的安全对齐至关重要。现有评估只看给定场景下的偏好感知准确率，从而掩盖奖励模型在真实场景中的关键脆弱性。
- **关键词：** reward-model, alignment

### Reward Modeling from Natural Language Human Feedback

- **作者：** Zongqi Wang, Rui Wang, Yuchuan Wu, Yiyao Yu, Pinyi Zhang, Shaoning Sun, Yujiu Yang, Yongbin Li
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=nd0hT1eyEo
- **中文提要：** 在偏好数据上用可验证奖励强化学习训练生成式奖励模型，已成为主流做法。这类模型通常生成以批评和偏好标签结尾的推理链，训练奖励则取标签是否正确。
- **关键词：** RLVR, PRM, reward-model

### Reward Under Attack: Analyzing the Robustness and Hackability of Process Reward Models

- **作者：** Rishabh Tiwari, Aditya Tomar, Udbhav Bamba, Monishwaran Maheswaran, Heng Yang, Michael Mahoney, Kurt Keutzer, Amir Gholaminejad
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=phHnze3Nfm
- **中文提要：** 过程奖励模型正迅速成为大语言模型推理流程的骨干，但作者表明前沿模型在优化压力下可被系统性利用。他们提出三层诊断框架，逐步加大对抗压力来量化这些脆弱性。
- **关键词：** PRM, reward-model

### RLAnything: Forge Environment, Policy, and Reward Model in Completely Dynamic RL System

- **作者：** Yinjie Wang, Tianbao Xie, Ke Shen, Mengdi Wang, Ling Yang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=JLQV6NxS6W
- **中文提要：** 环境与奖励模型的质量从根本上决定强化学习是否有效。RLAnything 通过闭环优化动态调整各个组成部分，以放大学习信号并强化整个系统。
- **关键词：** reward-model

### RSPO: Regularized Self-Play Alignment of Large Language Models

- **作者：** Xiaohang Tang, Sangwoong Yoon, Seongho Son, Huizhuo Yuan, Quanquan Gu, Ilija Bogunovic
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=PysPgClt8e
- **中文提要：** 基于自博弈的策略优化把偏好优化写成双人博弈，成为微调大语言模型的有效途径。相对参考策略的正则对抑制过优化很关键，但在自博弈对齐中仍研究不足。
- **关键词：** preference-optimization, alignment, fine-tuning

### Safety Anchor: Defending Harmful Fine-tuning via Geometric Bottlenecks

- **作者：** Guoxin Lu, Letian Sha, Qing Wang, Peijie Sun, Hao Zhou, Hua Dai, Fu Xiao
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=BDR6RK9TmA
- **中文提要：** 大语言模型的安全对齐仍然容易被有害微调攻破。现有防御会对参数、梯度或内部表示施加约束，作者观察到在持续有害微调下这些约束仍可被有效绕过。
- **关键词：** alignment, fine-tuning

### Safety Game: Inference-Time Alignment of Black-Box LLMs via Constrained Optimization

- **作者：** Tuan Nguyen, Long Tran-Thanh
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=7Nn3SKS6yL
- **中文提要：** 确保大语言模型符合安全要求，是部署中的核心难题。现有对齐主要发生在训练阶段，例如微调或 RLHF，成本高且不灵活，一旦出现新要求就得重新训练。
- **关键词：** RLHF, alignment, fine-tuning

### SAGE: Shaping Anchors for Guided Exploration in RLVR of LLMs

- **作者：** Chanuk Lee, Minki Kang, Sung Ju Hwang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=VzRUI5ZVkp
- **中文提要：** 近期观察表明，可验证奖励强化学习能稳定提高推理任务上单次采样的成功率，对多次采样却往往没有相当的增益。这引出一个问题：它究竟让模型获得新的推理能力，还是只是更高效地采样基座里已有的推理模式。
- **关键词：** RLVR

### SAME: Stabilized Mixture-of-Experts for Multimodal Continual Instruction Tuning

- **作者：** Zhen-Hao Xie Xie, Jun-Tao Tang, Yu-Cheng Shi, Han-Jia Ye, De-Chuan Zhan, Da-Wei Zhou
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Nvim88fA66
- **中文提要：** 多模态大语言模型靠指令调优取得强表现，真实部署却要求能力持续扩展，多模态持续指令调优因此变得必要。近期方法用稀疏专家路由促进任务专门化，作者发现随着数据分布变化，专家路由会出现漂移。
- **关键词：** instruction-tuning

### Scaling Behavior in Model Fine-tuning for Audio DeepFake Detection

- **作者：** Xiang Li, Pin-Yu Chen, Wenqi Wei
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=yHT8piYc8u
- **中文提要：** 音频深度伪造检测的进展，来自越来越大的语音基础模型和不断增多的合成数据。尽管基准表现强劲，在分布偏移、信号损坏和未见合成流程等真实部署条件下，检测能力如何随模型容量与训练数据扩展仍不清楚。
- **关键词：** post-training, fine-tuning

### ScaLoRA: Optimally Scaled Low-Rank Adaptation for Efficient High-Rank Fine-Tuning

- **作者：** Yilang Zhang, Xiaodong Yang, Yiwei Cai, Georgios B. Giannakis
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Skxb4UgTWU
- **中文提要：** 大语言模型继续变大，计算开销成为任务微调的主要瓶颈。LoRA 把权重更新限制在低维子空间以压低成本，但这种限制可能削弱效果并拖慢收敛。
- **关键词：** LoRA, fine-tuning

### SecCodePRM: A Process Reward Model for Code Security

- **作者：** Weichen Yu, Ravi Mangal, Yinyi Luo, Kai Hu, Jingxuan He, Corina Pasareanu, Matt Fredrikson
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Rg73g42KBW
- **中文提要：** 大语言模型正成为现代软件开发流程的核心，保障代码安全仍然困难。现有漏洞检测要么依赖静态分析器，要么使用在粗粒度程序级监督下训练的语言模型或图神经网络检测器。
- **关键词：** PRM, reward-model

### Shift-Dependent Asymmetry: Orthogonal Inverse Low-Rank Adaptation for Federated Medical Segmentation

- **作者：** Xingyue Zhao, Wenke Huang, Linghao Zhuang, Haoran Wu, Anwen Jiang, Zhifeng Wang, Wenwen He, Ming Feng, Mang Ye, Bo XU
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=0wxnefBSTB
- **中文提要：** LoRA 让医学影像分割基础模型可以高效地进行联邦微调。多数联邦 LoRA 采用统一聚合规则，但这在编码器与解码器不对称时会失效：编码器主要受外观偏移支配，解码器主要受监督差异支配。
- **关键词：** LoRA, PEFT, fine-tuning

### SHINE: A Scalable In-Context Hypernetwork for Mapping Context to LoRA in a Single Pass

- **作者：** Yewei Liu, Xiyuan Wang, Yansheng Mao, Yoav Gelberg, Haggai Maron, Muhan Zhang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ZMexYcAibv
- **中文提要：** SHINE 是一种可扩展超网络，能把多样且有意义的上下文映射成大语言模型的高质量 LoRA 适配器。它在上下文超网络中复用冻结模型自身的参数并引入架构上的改进，以克服先前超网络的关键限制。
- **关键词：** SFT, LoRA, fine-tuning

### Single-Rollout Hidden-State Dynamics for Training-Free RLVR Data Selection

- **作者：** Jianghao Wu, Jianfei Cai, Weiqiang Wang, Jin Ye, Daniel F Schmidt, Yasmeen George
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=pvq2AhjOy1
- **中文提要：** 可验证奖励强化学习只需很少训练样本就能带来大幅推理提升，但对选用哪些样本高度敏感，数据选择因此成为核心瓶颈。现有流程大多依赖训练期优化信号，或需要在大规模候选池上取得可验证奖励或标准答案，成本高。
- **关键词：** RLVR

### SIPO: Stabilized and Improved Preference Optimization for Aligning Diffusion Models

- **作者：** Xiaomeng Yang, Mengping Yang, Junyan Wang, Zhijian Zhou, Zhiyu Tan, Hao Li
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=JLgqmlc9S7
- **中文提要：** 偏好学习被广泛用于让扩散模型在视觉生成上对齐人类偏好。以 Diffusion-DPO 为代表的现有方法面临两个根本困难：不同时间步梯度方差高且参数敏感所导致的训练不稳定，以及由某种差异引起的离策略偏差。
- **关键词：** DPO, preference-optimization, alignment

### Smaller Models are Natural Explorers for Policy-Level Diversity in GRPO

- **作者：** Yiming Ren, Yiran Xu, Zicheng Lin, Chufan Shi, Yukang Chen, Dingdong WANG, Tianhe Wu, Junjie Wang, Yujiu Yang, Yu Qiao, Ruihang Chu
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=PI2xku6EDA
- **中文提要：** 作者为面向大语言模型的 GRPO 指出提升采样多样性的一个新维度。GRPO 依赖多样的采样轨迹，主流做法却主要靠注入更多词元级随机性，这可能带来逐步噪声并导致轨迹不连贯。
- **关键词：** GRPO, mid-training

### Small Generalizable Prompt Predictive Models Can Steer Efficient RL Post-Training of Large Reasoning Models

- **作者：** Yun Qu, Qi Wang, Yixiu Mao, Heming Zou, Yuhang Jiang, Weijie Liu, Clive Bai, Kai Yang, Yangkun Chen, Saiyong Yang, Xiangyang Ji
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=vCHOBek0dv
- **中文提要：** 强化学习能增强大语言模型的推理能力，但依赖大量采样的优化带来很高计算成本。在线提示选择通过优先使用信息量大的提示，为提高训练效率提供了一条可行途径。
- **关键词：** post-training

### SPARD: Defending Harmful Fine-Tuning Attack via Safety Projection with Relevance–Diversity Data Selection

- **作者：** Shuhao Chen, Weisen Jiang, Yeqi Gong, Shengda Luo, Chengxiang Zhuo, Zang Li, James Kwok, Yu Zhang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=fyM0jbe5DK
- **中文提要：** 微调大语言模型常常削弱安全对齐，有害微调攻击用对抗数据移除防护并诱发不安全行为，使问题更加严重。SPARD 把安全投影交替优化与兼顾相关性及多样性的数据选择结合起来，作为防御框架。
- **关键词：** alignment, fine-tuning

### Spectral Bridge Variational Inference: Dynamic LoRA via Bures-Wasserstein Gradient Flows

- **作者：** Yuhang Xi, Yu-Feng Yu, Chuan-Xian Ren, Zhao-Rong Lai
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=KjF35IhQGS
- **中文提要：** 参数高效微调（PEFT）对适配大语言模型必不可少，现有方法却难以兼顾容量与计算效率。标准做法施加僵硬的低秩约束，动态替代方案则带来明显的显存开销。
- **关键词：** LoRA, PEFT, fine-tuning

### SPR-RAFT: Parameter-Efficient Regression-Aware Fine-Tuning for Biomedical LLM Regression

- **作者：** Yuanlin Yang, Chenhui Li, Xuhao Guo, ANQI ZHANG, Hoi Leong Lee, Haodong Liu
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=U4z7qklYvw
- **中文提要：** 生物医学回归要从异构、非结构化证据中预测连续目标。大语言模型能为混合模态推理提供稳健接口，但离散分词和交叉熵目标不感知数值接近程度，因而受到固有限制。
- **关键词：** PEFT, fine-tuning

### Spurious Correlation Learning in Preference Optimization: Mechanisms, Consequences, and Mitigation via Tie Training

- **作者：** Christian Moya, Alex Semendinger, Guang Lin, Elliott Thornley
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Hpfybj9wkd
- **中文提要：** 以 DPO 为代表的偏好学习会诱发对虚假相关的依赖，在当前语言模型中表现为谄媚和长度偏差，并可能在未来系统中造成严重的目标误泛化。作者给出统一理论分析，刻画虚假学习的机制及其部署后果。
- **关键词：** DPO, preference-optimization

### Spurious Rewards Paradox: Mechanistically Understanding How RLVR Activates Memorization Shortcuts in LLMs

- **作者：** Lecheng Yan, Ruizhe Li, Guanhua CHEN, Qing Li, Jiahui Geng, Wenxi Li, Longyue Wang, Chenyang Lyu
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=SGUSUm2491
- **中文提要：** 可验证奖励强化学习对增强推理非常有效，但近期证据显示，即便奖励是虚假的，模型仍能获得明显提升。作者将此称为困惑度悖论：虚假奖励下答案词元的困惑度下降，同时提示侧连贯性变差，并暗示模型在绕过摘要后文未写完的内容。
- **关键词：** RLVR

### Spurious Rewards: Rethinking Training Signals in RLVR

- **作者：** Rulin Shao, Stella Li, Rui Xin, Scott Geng, Yiping Wang, Sewoong Oh, Simon Du, Nathan Lambert, Sewon Min, Ranjay Krishna, Yulia Tsvetkov, Hannaneh Hajishirzi, Pang Wei Koh, Luke Zettlemoyer
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=tqTNOpkP5j
- **中文提要：** 即便奖励与正确答案只有很弱的相关、毫无相关甚至负相关，可验证奖励强化学习仍能在部分语言模型上激发较强的数学推理。作者以 GRPO 配合随机指定的奖励为例，重新审视这类训练信号。
- **关键词：** GRPO, RLVR

### SSR-Merge: Subspace Signal Routing for Training-Free LoRA Merging in Diffusion Models

- **作者：** Zhengxuan Wei, Yi Dong, Zonghui Li, Xianhui Lin, Xing Liu, Hong Gu, Shaofeng Zhang, Wenbin Li, Qi Fan
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=eYwCaFakq6
- **中文提要：** LoRA 合并能把多个已训练适配器的多样生成能力高效组合到同一扩散模型上。现有合并技术却常出现严重的参数干扰，在共享参数空间中造成破坏性冲突。
- **关键词：** LoRA

### Statistical Impossibility and Possibility of Aligning LLMs with Human Preferences: From Condorcet Paradox to Nash Equilibrium

- **作者：** Kaizhao Liu, Qi Long, Zhekun Shi, Weijie Su, Jiancong Xiao
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://icml.cc/virtual/2026/poster/71805
- **中文提要：** 让大语言模型对齐多样的人类偏好，对公平且有依据的决策部署至关重要。该研究试图揭示这种对齐的基本统计极限，重点放在人类偏好的概率表示，以及对齐后如何保留偏好多样性。
- **关键词：** RLHF, reward-model, alignment

### Steering Out-of-Distribution Generalization with Concept Ablation Fine-Tuning

- **作者：** Helena Casademunt, Caden Juang, Adam Karvonen, Samuel Marks, Senthooran Rajamanoharan, Neel Nanda
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=yuJehN4oMW
- **中文提要：** 微调大语言模型可能导致非预期的分布外泛化。常规应对是修改训练数据，例如补充能更明确指定预期泛化的样本。
- **关键词：** fine-tuning

### Stratified GRPO: Handling Structural Heterogeneity in Reinforcement Learning of LLM Search Agents

- **作者：** Mingkang Zhu, Xi Chen, Bei Yu, Hengshuang Zhao, Jiaya Jia
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ZX2lOgKOTm
- **中文提要：** 大语言模型智能体越来越依赖搜索引擎等外部工具解决复杂多步问题，但采样轨迹在结构上并不一致：工具调用次数、位置和结果的差异会带来不同行为与奖励分布。单一全局基线的策略梯度因此出现跨层偏差，形成摘要所说的“苹果对橘子”式比较。
- **关键词：** GRPO

### STRIDE: Post-Training LLMs to Reason and Refine Bio-Sequences via Edit Trajectories

- **作者：** Daiheng Zhang, Shiyang Zhang, Sizhuang He, Yangtian Zhang, Syed Rizvi, David van Dijk
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=g9J8AyE0xy
- **中文提要：** 离散生物序列优化常常需要对已有蛋白质或分子做目标导向且能通过解析器校验的编辑。扩散模型支持迭代细化，但不提供可控的离散编辑接口；自回归大语言模型在多步约束编辑上又容易短视。
- **关键词：** SFT, post-training, fine-tuning

### Submodular Optimization for Minimal Augmentation in Robust Language Model Alignment

- **作者：** CHING-CHIA KAO, Chia-Mu Yu, Chun-Shien Lu, Chu-song Chen
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Wh6vxlw2BM
- **中文提要：** 即便很小的微调扰动，也会使行为弹性地回到预训练时的状态，而且退化程度与对齐集合的规模成反比。作者追问如何用尽可能少的增广来实现安全对齐。
- **关键词：** alignment, fine-tuning

### Surgery: Mitigating Harmful Fine-Tuning for Large Language Models via Attention Sink

- **作者：** Guozhi Liu, Weiwei Lin, Tiansheng Huang, Ruichao Mo, Qi Mu, Xiumin Wang, Li Shen
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=6ojsIliNF0
- **中文提要：** 有害微调会破坏大语言模型的安全对齐，带来显著的安全风险。文中利用注意力汇聚机制来缓解这种有害微调。
- **关键词：** alignment, fine-tuning

### TAGRPO: Boosting GRPO on Image-to-Video Generation with Direct Trajectory Alignment

- **作者：** Jin Wang, Jianxiang Lu, Guangzheng Xu, Comi Chen, Haoyu Yang, zhenzhen qin, Peng Chen, Mingtao Chen, Zhichao hu, Longhuang Wu, Shuai Shao, Qinglin Lu, Ping Luo
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=NEiMxuUCSc
- **中文提要：** 把 GRPO 融入流匹配模型，在文生图和文生视频上已被证明有效。直接把这些技术用到图生视频模型上，往往无法带来稳定的奖励提升。
- **关键词：** GRPO, post-training, alignment

### Task-Aware Preference Calibration for Direct Preference Optimization

- **作者：** Mengyang Li, Zhong Zhang, pinlong zhao
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=GxWTX93etl
- **中文提要：** DPO 已成为让大语言模型对齐人类偏好的主流方法。近期工作用困惑度差异识别不可靠的偏好标签，但这些方法对所有样本采用统一的校准策略。
- **关键词：** DPO, preference-optimization, alignment

### Task-Driven Subspace Decomposition for Knowledge Sharing and Isolation in LoRA-based Continual Learning

- **作者：** Lingfeng He, De Cheng, Huaijie Wang, Xi Yang, Nannan Wang, Xinbo Gao
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=UJJfkcJ7K9
- **中文提要：** 持续学习要求模型依次适应新任务，同时不遗忘旧知识。作为代表性参数高效微调（PEFT）方法的 LoRA，近来在持续学习中受到越来越多关注。
- **关键词：** LoRA, PEFT, fine-tuning

### TCAP: Tri-Component Attention Profiling for Unsupervised Backdoor Detection in MLLM Fine-Tuning

- **作者：** Mingzu Liu, Hao Fang, Runmin Cong
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=0RBjF3JSXG
- **中文提要：** 微调即服务便于定制多模态大语言模型，但被投毒的数据会带来严重后门风险。现有防御要么依赖有监督信号，要么难以跨多样的触发类型与模态泛化。
- **关键词：** fine-tuning

### TeamTR: Trust-Region Fine-Tuning for Multi-Agent LLM Coordination

- **作者：** Yi Xie, Siao Liu, Falong FAN, Yuanqi Yao, Siyang Cao, Yue Zhao, Bo Liu
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=IMwLhg52ZY
- **中文提要：** 多智能体大语言模型系统能改进推理与工具使用，但收益往往不稳定，且对交互设计敏感。训练协作是一个方向，不过团队后训练会引入移动目标效应：经共享上下文交互时，更新其中一个智能体就会改变其他智能体面对的上下文分布，协作可能因此倒退。
- **关键词：** post-training, alignment, fine-tuning

### Temporal Preference Optimization for Unsupervised Retrieval

- **作者：** HyunJin Kim, Jaejun Shim, Young Jin Kim, JinYeong Bak
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=W6FvMHPVez
- **中文提要：** 无监督稠密检索器通过对无标注文档做对比学习来学习语义相似度，因而易于扩展。它们难以捕捉时间相关性，会检索到语义相关但时间错位的文档，当文献集合跨越多个时期时这一点尤其重要。
- **关键词：** preference-optimization, alignment

### Temporal Self-Rewarding Language Models: Decoupling Chosen-Rejected via Past-Future

- **作者：** Yidong Wang, Xin Wang, Cunxiang Wang, Junfeng Fang, Qiufeng Wang, Jianing Chu, Xuran Meng, Shu-Xun Yang, Andrew Feng, Libo Qin, Wei Ye, Shikun Zhang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=8G0XzmQRG9
- **中文提要：** 自奖励语言模型让大语言模型既生成回答，又以模型充当评判来评估自身输出，并通过迭代 DPO 动态提升生成能力。分析揭示出现有范式的关键局限：被选回答与另一侧样本会同步变好。
- **关键词：** DPO, preference-optimization, self-rewarding

### Text Before Vision: Staged Knowledge Injection Matters for Agentic RLVR in Ultra-High-Resolution Remote Sensing Understanding

- **作者：** Fengxiang Wang, Mingshuo Chen, Yueying Li, Yulin Wang, Yang Yajie, Yuhao Zhou, Di Wang, Yi-Fan Zhang, Haoyu Wang, Haiyan Zhao, Hongda Sun, Jun Song, Long Lan, Jing Zhang, Wenlong Zhang, Bo Du
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=29m0TW0Xb3
- **中文提要：** 超高分辨率遥感的多模态推理，瓶颈通常在视觉证据获取：模型需要在巨大像素空间里定位很小的任务相关区域。使用放大工具的智能体式可验证奖励强化学习提供了一条途径，但标准强化学习难以在这些广阔视觉空间中导航。
- **关键词：** RLVR, SFT, post-training, fine-tuning

### $\textit{S}$-SPPO: Semantic-Calibrated Self-Play Preference Optimization

- **作者：** Xiwen Chen, Wenhui Zhu, Jingjing Wang, Peijie Qiu, Zhipeng Wang, Huayu Li, ZhengXiao He, XUANZHAO DONG, Prayag Tiwari, Mingkun Xu, Yujian Xiong, Feng Luo, Abolfazl Razi, Brendan Rappazzo, Anderson Schneider, Yuriy Nevmyvaka
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=uVZUAKrA1t
- **中文提要：** 把大语言模型对齐到人类偏好，常被写成直接偏好优化（DPO）。标准 Bradley-Terry 形式的 DPO 难以刻画人类偏好中常见的非传递性偏离。
- **关键词：** DPO, preference-optimization, alignment

### The Differences Between Direct Alignment Algorithms are a Blur

- **作者：** Alexey Gorbatovski, Boris Shaposhnikov, Viacheslav Sinii, Alexey Malakhov, Daniil Gavrilov
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=tCXxWWBjxQ
- **中文提要：** 直接对齐算法通过直接优化策略来简化大语言模型对齐，从而绕过奖励建模和强化学习。这些算法在如何使用 SFT 上并不相同。
- **关键词：** ORPO, SFT, instruction-following, reward-model, alignment

### The Heterogeneous Safety Impacts of Benign Multilingual Fine-Tuning

- **作者：** Will Hawkins, Kai Rawal, Jonathan Rystrøm, Stratis Tsirtsis, Zihao Fu, Greta Warren, Ryan Brown, Eoin Delaney, Sandra Wachter, Brent Mittelstadt, Chris Russell
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=5M6NoV6Hs6
- **中文提要：** 微调是提升大语言模型特定下游能力的常见手段。已有工作表明这种能力提升伴随代价：即便微调数据并非对抗性的，模型也更倾向于回应不安全的对抗提示。
- **关键词：** fine-tuning

### The Hidden Link between RLHF and Contrastive Learning

- **作者：** Xufei Lv, Kehai Chen, Haoyuan Sun, Xuefeng Bai, Min zhang, Houde Liu
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=MJ25gbGhPu
- **中文提要：** 大语言模型与人类价值的对齐受到广泛关注，典型例子包括代价高昂的经典 RLHF 和更简单的 DPO。两者都可以从互信息最大化的角度来理解。
- **关键词：** DPO, RLHF, preference-optimization, alignment

### The Obfuscation Atlas: Mapping Where Honesty Emerges in RLVR with Deception Probes

- **作者：** Mohammad Taufeeque, Stefan Heimersheim, Adam Gleave, Chris Cundy
- **会议：** ICML 2026 · Main · Oral
- **官方论文页：** https://openreview.net/forum?id=wrGSN9kAVD
- **中文提要：** 针对白盒欺骗检测器进行训练，被提议作为让人工智能系统变得诚实的途径。这种训练有风险：模型可能学会混淆自己的欺骗行为，以逃避检测器。
- **关键词：** RLVR

### Theoretical Perspectives on Data Quality and Synergistic Effects in Pre- and Post-Training Reasoning Models

- **作者：** Adel Javanmard, Baharan Mirzasoleiman, Vahab Mirrokni
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=URIdUFsz9E
- **中文提要：** 大模型先在大规模数据上预训练，再经 SFT 或强化学习做指令微调。事后训练与预训练的数据原则不同：SFT 依赖较小的高质量集，强化学习则更受益于反馈规模，更多反馈往往比标签质量更重要。
- **关键词：** SFT, instruction-tuning, post-training, fine-tuning

### The Sign Estimator: Preference Modeling for LLM Alignment under Heterogeneity

- **作者：** Ali Aouad, Aymane El Gadarri, Vivek Farias
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=SyTeWTEex3
- **中文提要：** 传统的大模型对齐多沿 RLHF，从成对比较里学习单一奖励模型，并默认标注者偏好同质，而这一假设在实际中并不成立。
- **关键词：** RLHF, reward-model, alignment

### The Unlearnability Phenomenon in RLVR for Language Models

- **作者：** Yulin Chen, He He, Chen Zhao
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=IiFFUPgSkV
- **中文提要：** 可验证奖励的强化学习已被证明能提升大语言模型的推理能力，但其学习动态仍缺少充分研究。
- **关键词：** RLVR

### Time-PEFT: Temporal and Multichannel Complexity-Based Fine-Tuning for Time-Series Foundation Models

- **作者：** Jihye Na, Patara Trirat, Chanyoung Park, Jae-Gil Lee
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=n8seTOinYs
- **中文提要：** 近来有研究微调时间序列基础模型，以改善目标数据集的预测。这些做法却缺少明确标准，无法判断哪些数据集因零样本预测退化、复杂度较高而需要微调。
- **关键词：** LoRA, PEFT, fine-tuning

### TokenDrop: Token-Level Importance-Aware Backward Propagation Skipping for Efficient LLM Fine-Tuning

- **作者：** Beomseok Kim, Sol Namkung, Dongsuk Jeon
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=D8DUCALWYb
- **中文提要：** 即便 PEFT 降低了参数相关开销，大模型微调仍受显存与计算需求制约。TokenDrop 按 token 重要度跳过部分反向传播，以减少激活显存并加快微调。
- **关键词：** PEFT, fine-tuning

### TokenRatio: Principled Token-Level Preference Optimization via Ratio Matching

- **作者：** Truong Nguyen, Tien-Phat Nguyen, Linh Van, Duy Nguyen, Khoa Doan, Trung Le
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=1twve5mNUU
- **中文提要：** DPO 不依赖强化学习，被广泛用于从成对偏好对齐语言模型，但它在整段序列上建模偏好，而生成其实由逐 token 决策驱动。已有的 token 级扩展通常把序列级 Bradley–Terry 目标拆到各时间步，使每个前缀上的最优性只是隐含的。
- **关键词：** DPO, instruction-following, preference-optimization, alignment

### Toward Safe Quantization-Aware Fine-tuning: Understanding and Mitigating Safety Alignment Degradation

- **作者：** Yuning Yang, Guowei Peng, Xiurui Xie, Minrui Jiang, Shuang Liang, Guisong Liu
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=vF2Xhg2s31
- **中文提要：** 资源受限时，量化感知微调已成为把大模型适配到下游任务的常见做法。可解释性分析发现，量化模型在微调过程中比全精度模型更容易出现安全对齐退化。
- **关键词：** post-training, alignment, fine-tuning

### Towards Disentangled Preference Optimization Dynamics: Suppress the Loser, Preserve the Winner

- **作者：** Wei Chen, Yubing Wu, Junmei Yang, Delu Zeng, Qibin Zhao, John Paisley, Min Chen, Zhou Wang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=TaNH4XiQ6P
- **中文提要：** 偏好优化被广泛用于让大模型贴近人类偏好，但许多基于间隔的方法在抑制被拒回答时也会压低被选回答，而且缺少能跨不同目标通用的防范方式。
- **关键词：** preference-optimization

### Towards On-Policy SFT: Distribution Discriminant Theory and its Applications in LLM Training

- **作者：** Miaosen Zhang, Yishan Liu, Shuxia Lin, Qi Dai, Chong Luo, Baining Guo, Weihao Jiang, Peng Hou, Anxiang Zeng, Xu Yang, Xin Geng
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=auOFVW0iSO
- **中文提要：** SFT 计算效率较高，泛化却常常不如强化学习，这一差距主要来自强化学习使用同策略数据。
- **关键词：** DPO, SimPO, SFT, alignment, fine-tuning

### Towards Understanding the Dynamics of Low-Rank Adaptation

- **作者：** Shu Ding, Yang Peng, Hangan Zhou, Xinyu Lu, Shangwei Chen, Junhua Huang, Mingxuan Yuan, Wei Wang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=dPvcpbbLSs
- **中文提要：** LoRA 是广泛使用的参数高效微调技术，已有工作表明沿低秩矩阵 A 的更新，可看作梯度在 A 转置 A 所张成压缩子空间中的过程。至于该子空间的性质如何影响适配，相关分析仍然很少。
- **关键词：** LoRA, PEFT, fine-tuning

### Training Data Efficiency in Multimodal Process Reward Models

- **作者：** Jinyuan Li, Chengsong Huang, Langlin Huang, Shaoyang Xu, Haolin Liu, Wenxuan Zhang, Jiaxin Huang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=NWRoNoJ9QX
- **中文提要：** 多模态过程奖励模型支撑着多模态大模型视觉推理中的步骤级监督，但其训练通常需要大规模蒙特卡洛标注语料，代价不小。
- **关键词：** PRM, reward-model

### Training Prompt Matters: State-Adaptive Optimization for Robust Fine-Tuning

- **作者：** Wenhang Shi, Yiren Chen, Shuqing Bian, Zhe Zhao, Jinhao Dong, Pengfei Hu, WEI LU, Xiaoyong Du
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=6XXz4OPAXA
- **中文提要：** 提示工程在推理阶段对发挥大模型能力很重要，训练阶段提示的作用却仍缺少研究。主流微调把训练提示仅当作表层形式，并假定语义等价的指令会产生相同的学习结果。
- **关键词：** fine-tuning

### Transformers with RL or SFT Provably Learn Sparse Boolean Functions, But Differently

- **作者：** Bochen Lyu, Yiyang Jia, Xiaohao Cai, Zhanxing Zhu
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=UrKNw5Xo9x
- **中文提要：** 经过微调，Transformer 可以获得思维链能力来完成推理任务，强化学习与 SFT 是两条主要路径。
- **关键词：** RFT, SFT, PRM, fine-tuning

### Transitivity Meets Cyclicity: Explicit Preference Decomposition for Dynamic Large Language Model Alignment

- **作者：** Yucong Huang, Xiucheng Li, Kaiqi Zhao, Jing Li
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=7H9HRTWady
- **中文提要：** 标准 RLHF 依赖可传递的标量奖励，捕捉不到人类偏好的循环性。通用偏好模型试图处理这一点，但其隐式表述把层级结构与循环性缠在一起，无法保证占优解。
- **关键词：** RLHF, preference-optimization, alignment

### TRIM: Token-wise Attention-Derived Saliency for Data-Efficient Instruction Tuning

- **作者：** Manish Nagaraj, Sakshi Choudhary, Utkarsh Saxena, Deepak Ravikumar, Kaushik Roy
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=25AaIQjAg9
- **中文提要：** 指令微调对把大模型对齐到下游任务很关键，通常依赖大规模、多样化语料。小而高质量的核心子集也能达到相当甚至更好的效果，但如何筛选仍然困难。
- **关键词：** instruction-tuning, alignment, fine-tuning

### Trojan-Speak: Bypassing Constitutional Classifiers with No Jailbreak Tax via Adversarial Finetuning

- **作者：** Bilgehan Sel, Xuanli He, Alwin Peng, Ming Jin, Jerry Wei
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=5Aydbj0wYI
- **中文提要：** 主要人工智能厂商提供的微调接口构成新的攻击面，对手可通过定向微调绕过安全措施。Trojan-Speak 是一种对抗性微调方法，旨在绕过 Anthropic 的 Constitutional Classifiers。
- **关键词：** GRPO, fine-tuning

### TuneAhead: Predicting Fine-tuning Performance Before Training Begins

- **作者：** Yuxiang Luo, Haonan Long, Chen Wang, Qiqi Duan, Xiaotian Lin, Yanwei XU, Yuyu Luo, Weikai Yang, Nan Tang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=JBFB2pUOCA
- **中文提要：** 模型表现对数据质量和超参数选择很敏感，草率训练甚至可能让性能下降。由此产生一个实际问题：能否在投入完整训练之前预测微调效果。
- **关键词：** fine-tuning

### TUR-DPO: Topology- and Uncertainty-Aware Direct Preference Optimization

- **作者：** Abdulhady abas, Fatemeh Daneshfar, Seyedali Mirjalili, Mourad Oussalah
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=YDztzMJynP
- **中文提要：** 让大模型对齐人类偏好，常见路径是带 PPO 的 RLHF，或更简单的 DPO。DPO 稳定且不需要强化学习，但把偏好看成扁平的胜负对照。
- **关键词：** DPO, RLHF, preference-optimization, alignment

### Tvcache: A Tool-Value Cache for Post-Training LLM Agents

- **作者：** Abhishek Vijaya Kumar, Bhaskar Kataria, Byungsoo Oh, Emaad Manzoor, Rachee Singh
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=tDft0AHhzH
- **中文提要：** 对大模型智能体做强化学习后训练时，外部工具调用很慢，已分配的 GPU 会闲置，从而拉长训练并增加成本。并行采样中不少调用会重复，原则上可以缓存，但工具输出取决于先前交互诱导的环境状态，简单缓存并复用并不正确。
- **关键词：** post-training

### UB-SMoE: Universally Balanced Sparse Mixture-of-Experts for Resource-adaptive Federated Fine-tuning of Foundation Models

- **作者：** Van-Tuan Tran, Hong-Hanh Nguyen-Le, Marco Ruffini, Merim Dzaferagic
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=nxgmp4aWer
- **中文提要：** 异构 LoRA 秩方法按客户端计算能力分配不同的秩，以应对基础模型联邦微调中的系统异构。这类方法的计算节省仍然有限，因为稠密前馈计算占主导。
- **关键词：** LoRA, fine-tuning

### UDM-GRPO: Stable and Efficient Group Relative Policy Optimization for Uniform Discrete Diffusion Models

- **作者：** Jiaqi Wang, Haoge Deng, Ting Pan, Yang Liu, Chengyuan Wang, Fan Zhang, Yonggang Qi, Xinlong Wang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=WJcFtJriqv
- **中文提要：** 均匀离散扩散近来成为离散生成建模中较有前景的范式，但它与强化学习的结合仍大体空白。直接把 GRPO 迁到该模型上，会导致训练不稳定且收益有限。
- **关键词：** GRPO

### Unbiased Reward Modeling from Implicit Feedback for LLM Alignment

- **作者：** Hao Wang, Haocheng Yang, Licheng Pan, Zhichao Chen, Xiaoxi Li, Yinuo Wang, Lei Shen, Yuan Lu, Haoxuan Li, Zhouchen Lin
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=membbcuXeR
- **中文提要：** 尽管 RLHF 已经取得成功，现有奖励建模仍主要依赖显式反馈，收集成本高且难以扩展。该研究转向隐式奖励建模，从点击、复制和跳过等用户行为中学习奖励模型。
- **关键词：** RLHF, reward-model, alignment

### Understanding Catastrophic Forgetting In LoRA via Mean-Field Attention Dynamics

- **作者：** Hugo Koubbi, Louis Hernandez, Matthieu Boussard
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=MXvuMNd3oI
- **中文提要：** LoRA 因计算与性能的折中成为主流参数高效微调方法，却会出现灾难性遗忘。作者用可解析的平均场自注意力玩具模型来考察遗忘：token 作为相互作用粒子系统演化，LoRA 则充当低秩扰动。
- **关键词：** LoRA, PEFT, fine-tuning

### Understanding LoRA as Knowledge Memory: An Empirical Analysis

- **作者：** Seungju Back, Dongwoo Lee, Naun Kang, Taehee Lee, S. K. Hong, Youngjune Gwon, Sungjin Ahn
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=0MVEJk4dhE
- **中文提要：** 预训练大模型需要持续更新知识，但这仍然困难。推理阶段的上下文学习与检索增强生成虽然常用，却受上下文预算、成本和检索碎片化的约束。
- **关键词：** LoRA

### Understanding the Performance Gap in Preference Learning: A Dichotomy of RLHF and DPO

- **作者：** Ruizhe Shi, Minhak Song, Runlong Zhou, Zihan Zhang, Maryam Fazel, Simon Du
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=sg94PRd3kD
- **中文提要：** 一项细粒度理论分析考察两阶段 RLHF 与 DPO 之间的性能差距，并将其拆成两类来源：精确优化下的显式表示差距，以及有限样本下的隐式表示差距。
- **关键词：** DPO, RLHF, preference-optimization, reward-model

### UnHype: CLIP-Guided Hypernetworks for Dynamic LoRA Unlearning

- **作者：** Piotr Wójcik, Maksym Petrenko, Wojciech Gromski, Przemysław Spurek, Maciej Zieba
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=cUPGCuaNWZ
- **中文提要：** 大规模扩散模型可能被滥用来生成逼真却有害或扰乱社会的内容，这推动了对机器遗忘的关注，即有选择地移除特定知识或概念，同时不损害整体生成能力。
- **关键词：** LoRA, fine-tuning

### UniFLoW: Universal Multi-Modal Federated LoRA Fine-Tuning Framework with Analytical Aggregation

- **作者：** haoyuan liang, Zhiyu Ye, Jielong Tang, Yang Yang, Shilei Cao, Guowen Li, Fei Hu, Zhiwei Zhang, Haohuan Fu, Juepeng Zheng
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=21J9OI6mhc
- **中文提要：** 多模态大模型持续训练使公开数据日益减少，进一步训练和适配的空间受限，而私有数据仍是尚未被充分利用的有价值资源。
- **关键词：** LoRA, PEFT, fine-tuning

### UniRRM: Unified Reasoning Reward Models Across Languages and Evaluation Paradigms

- **作者：** Peng Lai, Yichao Du, Junchao Wu, Weibo Gao, Linan Yue, Longyue Wang, Weihua Luo, Derek F. Wong, Guanhua CHEN
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=laiK6TlhL2
- **中文提要：** 强化学习擅长带可验证奖励的任务，但在开放式任务中，奖励模型是否可靠仍是关键挑战。现有方案或依赖昂贵的专有大模型评判系统，或使用缺乏可解释性的不透明标量奖励模型。
- **关键词：** reward-model

### Unlocking Speech–Text Compositional Powers: Instruction-Following Speech Language Models without Instruction Tuning

- **作者：** Congrui Du, Yang Zhang, Kaizhi Qian, Shiyu Chang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=SDFeVV01xR
- **中文提要：** 语音语言模型的指令微调比文本大模型困难得多，既要学习新模态，又要掌握大量语音特有指令。现有训练大体复制文本大模型范式，靠合成大规模语音预训练数据推进。
- **关键词：** instruction-tuning, instruction-following

### Utility-Diversity Aware Online Batch Selection for LLM Supervised Fine-tuning

- **作者：** Heming Zou, Yixiu Mao, Yun Qu, Qi Wang, Xiangyang Ji
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=NWZZmXRIH5
- **中文提要：** SFT 常被用来把大模型适配到下游任务。对全量数据做 SFT 计算开销大，有时还会过拟合或放大偏见。
- **关键词：** SFT, fine-tuning

### VELR: Efficient Video Reward Feedback via Ensemble Latent Reward Models

- **作者：** Liyu Zhang, Kehan Li, Tao Zhou, Zeyi Huang, Chao LI, Jiming Chen
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=nG9823VW2W
- **中文提要：** 奖励反馈学习借助图像奖励模型，对文生图和文生视频都有效。图像奖励模型与文生视频的时间目标并不对齐，因此需要用视频奖励模型来做反馈学习。
- **关键词：** reward-model

### Video-OPD: Efficient Post-Training of Multimodal Large Language Models for Temporal Video Grounding via On-Policy Distillation

- **作者：** Jiaze Li, Hao Yin, Haoran Xu, Boshen Xu, Wenhui Tan, Zewen He, Jianzhong Ju, Zhenbo Luo, Jian Luan
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Y4jQjDnVSd
- **中文提要：** 强化学习因其同策略优化，成为时序视频定位的一种有原则的后训练范式，但现有基于 GRPO 的方法受稀疏奖励和较大计算开销制约。Video-OPD 受同策略蒸馏启发，为该任务提出更高效的后训练框架。
- **关键词：** GRPO, post-training, alignment

### ViSurf: Visual Supervised-and-Reinforcement Fine-Tuning for Large Vision-and-Language Models

- **作者：** Yuqi Liu, Liangyu Chen, Jiazhen Liu, Mingkang Zhu, Zhisheng Zhong, Bei Yu, Jiaya Jia
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=E88ye5tTF8
- **中文提要：** 大型视觉语言模型的后训练，通常要么用 SFT 注入知识，要么用可验证奖励的强化学习来提升表现。前者往往达不到理想效果，后者则受模型内部知识储备限制。
- **关键词：** RLVR, RFT, SFT, post-training, fine-tuning

### VR-Thinker: Boosting Multimodal Reward Models through Think with Image Reasoning

- **作者：** Qunzhong Wang, Jie Liu, Jiajun Liang, Yuanxing Zhang, Yilei Jiang, Yaozhi ZHENG, Xintao Wang, Pengfei Wan, Xiangyu Yue, Jiaheng Liu
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=LD9mlgF5WU
- **中文提要：** 多模态奖励模型的进展明显改善了视觉生成模型的后训练，但仍面临固有限制：视觉输入占用大量上下文，只能减少帧数并丢失细节；全部视觉信息又被塞进初始提示，思维链推理中的遗忘更严重。
- **关键词：** GRPO, RFT, reward-model, post-training, fine-tuning

### WeatherSyn: An Instruction Tuning MLLM For Weather Forecasting Report Generation

- **作者：** Zinan Zheng, Yang Liu, Nuo Chen, Juepeng Zheng, Hong Cheng, Jia Li
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=WlScVvMwpB
- **中文提要：** 准确的天气预报报告有助于个人和社区安排日常、农事与交通。现有报告主要依靠人工分析多源数据，容易造成信息过载并降低效率。
- **关键词：** instruction-tuning

### What Do Agents Learn from Trajectory-SFT: Semantics or Interfaces?

- **作者：** Weizheng Gu, Chengze Li, Zhuohao Yu, Mengyuan Sun, Zhibang Yang, Wei Wang, Hongrui Jia, Shikun Zhang, Wei Ye
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=u1i3XoSXQG
- **中文提要：** 大模型越来越多地被当作交互智能体来评测，但标准智能体基准把两种不同的成功来源混在一起：语义层面的工具使用，以及对特定界面交互模式的记忆。两者在原界面上都能得到相同的任务成功，因此基准分数本身并不能证明能力不依赖于环境。
- **关键词：** SFT

### When and How Human Curation Backfires: Preference Alignment under Multi-Model Self-Consuming Loop

- **作者：** Yang Zhang, Xiukun Wei, Xueru Zhang
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=9GBejLzPvl
- **中文提要：** 基础模型越来越常在前代模型生成的合成数据上训练，而不只使用真实数据。这种自我消耗式训练可能导致模型坍缩、发散或偏见放大。
- **关键词：** preference-optimization, alignment

### When Distance Distracts: Representation Distance Bias in BT-Loss for Reward Models

- **作者：** Tong Xie, Ching-Yuan Bai, Yuanhao Ban, Yunqi Hong, Haoyu Li, Cho-Jui Hsieh
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=MBk6Pur6RX
- **中文提要：** 奖励模型处在 RLHF 对齐框架的中心，其标准目标是 Bradley-Terry 损失，从包含被选与被拒回答的成对数据中学习。
- **关键词：** RLHF, reward-model, alignment

### When Is Rank-1 Enough? Geometry-Guided Initialization for Parameter-Efficient Fine-Tuning

- **作者：** Haoran Zhao, Caren Han, Eduard Hovy
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Umu6IsAUbS
- **中文提要：** 参数高效微调是适配多模态大模型的常规方式，但极低秩设定下的 LoRA 常常不稳定。这种不稳定并不只因为容量有限：在该情形下，优化对更新方向高度敏感。
- **关键词：** LoRA, PEFT, alignment, fine-tuning

### When Preference Labels Fall Short: Aligning Diffusion Models from Real Data

- **作者：** Weiyan Chen, Weijian Deng, Yao Xiao, Weijie Tu, ZiYi Dong, Ibrahim Radwan, Liang Lin, Pengxu Wei
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=KyAEhJSyEC
- **中文提要：** 偏好对齐希望通过比较偏好与非偏好样本来引导生成模型。实践中，多数现有方法依赖由模型生成图像构造的偏好对。
- **关键词：** preference-optimization, alignment

### Why Tree-Style Branching Matters for Thought Advantage Estimation in GRPO

- **作者：** Hongcheng Wang, Yinuo Huang, Sukai Wang, Guanghui Ren, Hao Dong
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=KwO83Ao6BW
- **中文提要：** GRPO 用可验证奖励训练思维链推理，但在没有价值函数时估计思维级优势往往方差很高。树状分支在实践中被用来降低方差，却缺少理论解释来说明它为何有效、是否重要甚至是否必要。
- **关键词：** GRPO

### WS-GRPO: Weakly-Supervised Group-Relative Policy Optimization for Rollout-Efficient Reasoning

- **作者：** Gagan Mundada, Zihan Huang, Rohan Surana, Sheldon Yu, Jennifer Y Zhang, Xintong Li, Tong Yu, Lina Yao, Jingbo Shang, Julian McAuley, Junda Wu
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=KsvEE4OFzR
- **中文提要：** GRPO 能有效训练语言模型完成复杂推理，但其目标是相对一组采样轨迹定义的。更长时间的斟酌会创造更多实现相对收益的机会，导致推理低效和过度思考，也使正确性与采样效率更难权衡。
- **关键词：** GRPO

### XRPO: Pushing the Limits of GRPO with Targeted Exploration and Exploitation

- **作者：** Udbhav Bamba, Minghao Fang, Yifan Yu, Haizhong Zheng, Fan Lai
- **会议：** ICML 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=AE6U9HvTHc
- **中文提要：** GRPO 等强化学习算法推动了大模型推理的近期进展。增加采样数量可以稳定训练，但现有方法对困难提示探索不足，也未能充分利用有信息量的反馈信号，部分原因是各提示的采样分配与上下文无关。
- **关键词：** GRPO
