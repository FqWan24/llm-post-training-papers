# 2026 · NeurIPS

共 322 篇。Main 322，Findings 0，其他赛道 0。其中 0 篇来源题录无摘要，提要标明「仅根据标题概括」。

检索窗口为 2024-11-13 至 2026-11-13。题录信息来自官方列表，不在此增补作者、链接或实验数字。

## Main

### AdaPaD: Adaptive Parallel Deflation for PEFT with Self-Correcting Rank Discovery

- **作者：** Barbara Su, Fangshuo Liao, Anastasios Kyrillidis
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=IneMjsFM6P
- **中文提要：** 用 LoRA 微调大语言模型时，秩必须在训练开始前就定下来。已有路线要么依次抽取秩一成分、并把每个成分的误差永久留在后续残差里，要么联合优化整个低秩分解，而其保证只描述联合更新、不涵盖单个秩一方向。
- **关键词：** LoRA, PEFT, fine-tuning

### AdaPreLoRA: Adafactor Preconditioned Low-Rank Adaptation

- **作者：** Ziyun Liu, Fengmiao Bian, Jian-Feng CAI
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=8o83y7bppR
- **中文提要：** LoRA 把权重更新重参数化为两个低秩因子之积，但由因子映射到权重矩阵的生成器雅可比是秩亏的。于是任意权重空间预条件诱导出的因子空间预条件子都是奇异的，标准链式法则因此无法沿用。
- **关键词：** LoRA

### Adaptive Fine-Tuning Scheduler for Multi-Tenant Edge LLM via Convergence-Aware Bandits

- **作者：** Yandi Li, Jianxiong Guo, Yupeng Li, Zhiqing Tang, Tian Wang, Weijia Jia
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=JjNnUtfLn8
- **中文提要：** 直接在本地边缘服务器上个性化大语言模型，对隐私保护与上下文感知越来越重要。受限的 GPU 显存只能放下固定数量、可进入训练的 LoRA 适配器，计算约束则要求微调更新依次进行。
- **关键词：** LoRA, fine-tuning

### Advancing Entropy-Level Credit Assignment in RLVR via Proximal Entropy Policy Optimization

- **作者：** Yun Kim, Nojun Kwak
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=enmugrKvYL
- **中文提要：** 像 GRPO 这样不使用价值模型的 RLVR 方法，会给同一次采样里的所有词元赋予相同优势，忽略词元贡献并不相等。后来的方法改用词元熵作为重要性代理，却在整个批次上全局计算，把重要性与提示难度、位置趋势混在一起。
- **关键词：** GRPO, RLVR

### AERO: Adaptive Ensemble-Disagreement Routing for Oracle Feedback in Sample-Efficient Online RLHF

- **作者：** Shrey Singhal, Nannan Huang, Haytham Fayek
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=HexbOT3aCq
- **中文提要：** 借助 RLHF 让大语言模型对齐人类偏好，已在广泛任务上带来改进，但获取偏好标签的成本仍是对齐流程里的主要瓶颈。近期不少对齐方法通过对候选回复做主动探索来提高样本效率。
- **关键词：** DPO, RLHF, reward-model, alignment

### A Few Teacher Steps Go a Long Way: Cost-Efficient On-Policy Data Augmentation for Agent Post-Training

- **作者：** Junze Ye, Jiayi Cheng, Miao Lu, Michal Mankowski, Jose Blanchet, Mohsen Bayati
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=exsMozVjaF
- **中文提要：** 语言模型智能体的训练流水线通常从监督微调开始，让较小的学生去模仿开销很高的教师。为缓解纯模仿学习的协变量偏移，近期工作改为在学生自己到达的状态上收集教师反馈，并越来越倾向对教师回复做精细过滤。
- **关键词：** SFT, post-training, fine-tuning

### Agent$^2$ RL-Bench: Can LLM Agents Engineer Agentic RL Post-Training?

- **作者：** Wanyi Chen, Xiao Yang, Xu Yang, Tianming Sha, Qizheng Li, Zhuo Wang, Bowen Xian, Fang Kong, Weiqing Liu, Jiang Bian
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=LJihH43YTU
- **中文提要：** Agent² RL-Bench 是一个紧凑的诊断基准，用来检验大语言模型智能体能否自主设计、实现、调试并执行可改进基础模型的强化学习后训练流水线。强化学习后训练正越来越多地推动对齐与专门化，但现有基准大多是静态的，奖励对象主要是监督微调或脚本生成，后文未完。
- **关键词：** GRPO, SFT, post-training, alignment, fine-tuning

### Agentic Reward Modeling: Verifying GUI Agent via Progressive Trajectory-Grounded Interaction

- **作者：** CHAOQUN CUI, Fei ZHANG, SHIJING WANG, Liming Zheng, Qingchao Kong, Zhixiong Zeng
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=61SF5nUDyZ
- **中文提要：** 带可验证奖励的强化学习为持续推进 GUI 智能体提供了一条途径，但现有奖励建模范式各自带有互补的局限。基于规则的方法扩展性差，也处理不了开放式任务。
- **关键词：** RLVR, reward-model

### Align Before Aggregation: Basis-Consistent Federated LoRA under Heterogeneous Ranks

- **作者：** Pengpeng Qiao, Yang Cao, Lingling Zhang, Guo Cheng, Junwei Chen, Manjiang Yu, Wei Yang Bryan Lim, Masatoshi Yoshikawa
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=EfUHrLQ6uH
- **中文提要：** 客户端能力异构时的联邦大语言模型微调日益重要，不同秩的 LoRA 使这种设置变得可行。现有服务端聚合器会先用各客户端自己的 LoRA 因子组成局部矩阵更新，再对这些更新做聚合。
- **关键词：** LoRA, fine-tuning

### Aligned LoRA Updates via Intrinsic Geometry for Federated Low-Rank Adaptation

- **作者：** Yihao Yang, Jian Liang, Wenke Huang, He Li, Xingyu Gao, Mang Ye
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=gOYBV7SBxP
- **中文提要：** 联邦低秩适应通过在客户端之间交换低秩适应参数，让大语言模型的微调更高效。已有研究主要盯住聚合偏差，并据此设计改进的聚合方案。
- **关键词：** LoRA, fine-tuning

### Aligning Language Models with Selective Prediction

- **作者：** Gaoxiang Luo, Yifan Wu, Sinian Zhang, Aryan Deshwal, Ju Sun
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=vXRPlOT3KJ
- **中文提要：** 大语言模型越来越多地充当现实系统中的决策部件，服务于社会与科学应用，可靠预测因此更受关注。相关研究从选择性预测切入可靠决策，允许模型用覆盖率换取更好的表现。
- **关键词：** post-training, alignment

### Aligning LLMs Toward Multi-Turn Conversational Outcomes Using Iterative RLHF

- **作者：** Daniel Jiang, Ankur Samanta, Yukai Yang, Jalaj Bhandari, Remi Munos, Tyler Lu
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ajJbdafVVH
- **中文提要：** 把大语言模型训练成多轮对话智能体仍很困难，目标导向场景尤其如此。难点在于目标稀疏且时程很长，以及回复级规划与词元级生成并不一致。
- **关键词：** GRPO, RLHF, reward-model, alignment

### Aligning LLMs with Biomedical Knowledge using Balanced Fine-Tuning

- **作者：** Zhenchao Tang, Fang Wang, Haohuai He, Jiale Zhou, Tianxu Lv, Jun Zhu, Shou Z Chen, Minghao Yang, Yu Wang, Jiayang Wu, Yidong Song, Yaokun Li, Jiehui Huang, Jun Zhou, Bing He, Jianhua Yao
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=p2HWge7bRt
- **中文提要：** 若要让大语言模型加速生命科学研究，就需要与生物医学知识稳健对齐。生物医学文本的不确定性结构与普通文本根本不同：成片低置信区间对应认知性知识缺口，如密集因果链和罕见实体，而不是普通文本里那种稀疏的偶然风格波动。
- **关键词：** GRPO, SFT, post-training, alignment, fine-tuning

### Alignment Dynamics in LLM Fine-Tuning

- **作者：** Yuhan Huang, Huanran Chen, Yinpeng Dong
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=iRH7xi46GH
- **中文提要：** 大语言模型虽能靠监督微调与 RLHF 取得较强对齐，这种对齐在后续微调中往往很脆弱。现有解释要么归因于梯度几何，要么看成输出分布的偏移，却很少给出能衔接参数空间学习的统一说明。
- **关键词：** RLHF, SFT, alignment, fine-tuning

### Alignment Needs 'Cognitive Control': On The Role of Regularization in LLM Alignment

- **作者：** Nona Ghazizadeh, Elnaz Rahmati, Morteza Dehghani, Payam Piray
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=3HB7ng0haX
- **中文提要：** 这篇立场论文主张，对齐里锚定参考的正则化并非工程开销，而是功能上的必要，相当于大脑认知控制的计算对应物。对齐社区越来越把正则化成本称作应尽量减小的“对齐税”，并追求去掉预训练参考的无参考方法，后文未完。
- **关键词：** alignment

### A Margin Perspective on LoRA: Robustness to Catastrophic Forgetting and Adapter Merging (MaLoRA)

- **作者：** Ziqing Xu, Hancheng Min, Lachlan MacDonald, Salma Tarmoun, Enrique Mallada, Weijie Su, Rene Vidal
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=8PbIL0Lq7v
- **中文提要：** LoRA 以很少的可训练参数和较低的优化成本，完成大神经网络的参数高效微调。除效率之外，实践中还观察到它对灾难性遗忘较为稳健，并且可以把独立训练的适配器合并进同一个模型。
- **关键词：** LoRA, PEFT, fine-tuning

### An Axiomatic Analysis of DPO and NLHF as Reference-Dependent Probabilistic Voting Rules

- **作者：** Wesley H Holliday, Adam Lesnikowski, Roberto-Rafael Maura-Rivero
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=U33O5GzkG8
- **中文提要：** 后训练方法会以隐式方式汇总多样的人类反馈，而这种汇总可以用社会选择理论来显式研究。文中的视角是：每一种后训练方法都对应一条依赖于参考的概率投票规则。
- **关键词：** DPO, preference-optimization, post-training

### AppCIF-Bench: An Application-Level Complex Instruction Following Benchmark for Large Language Models

- **作者：** Jiahao Xu, Xuefang Zhao, Xinhua Feng, Hongrui Yang, Yixian Liu, Zhichao Hu, Lliu Yuhong
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=TxXrHtF43g
- **中文提要：** 复杂指令遵循是把大语言模型部署到生产级应用的基础能力。它要求在视界变长、规则深度嵌套以及多轮交互之下，输出仍然稳定而精确。
- **关键词：** instruction-following

### AR1-ZO: Topology-Aware Rank-1 Zeroth-Order Queries for High-Rank LoRA Fine-Tuning

- **作者：** Ziye Chen, Hongbin Lin, Chenyu Zhang, Xiangda Yan, Yongjie Yang, Yao SHU
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=7eOsaBX3qO
- **中文提要：** 零阶优化使大语言模型微调不必保存反向传播的激活，LoRA 则提供紧凑的可训练适配器。两者叠加会形成秩上的矛盾：提高 LoRA 的秩能增强适配器容量，但标准两点零阶要么扰动随秩变化数量的坐标，要么在逐原子更新下让有限差分信号无法被观测。
- **关键词：** LoRA, fine-tuning

### Are Easier or Harder Examples Better? Rethinking Data Selection for Reward Models and Preference Optimization

- **作者：** Kevin Christian Wibisono, Aya Ismail, Pedro O. Pinheiro, Yixin Wang, Kyunghyun Cho, Nataša Tagasovska, Rajesh Ranganath
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ZVpkdTlkIZ
- **中文提要：** 数据选择对大语言模型对齐很关键，相关研究却仍然不足。奖励模型训练和策略优化（例如 DPO、GRPO）把样本难度——选中回复与拒绝回复之间的奖励差距——当作关键因素，但结论互相冲突，有的偏向差距更大、更容易的样本，有的偏向更难的样本。
- **关键词：** GRPO, DPO, preference-optimization, reward-model, post-training, alignment

### AtmoZero: Self-Play Post-Training for Caption-Free Weather Time-Series Captioning

- **作者：** Qirui Zheng, Shengchao Chen
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Ugpq0GTKKc
- **中文提要：** 多变量天气时间序列是预报与决策支持的核心模态，周边语言也越来越多地中介用户和下游模型对数值天气的使用。现有流水线却依赖带专家质控的闭源语言模型集成，或依赖检索人工整理文本，而先前的图注强化学习奖励优化的是循环相似度或其他未写完的目标。
- **关键词：** post-training, alignment

### A Unified Graph Language Model for Multi-Domain Multi-Task Graph Alignment Instruction Tuning

- **作者：** Haibo Chen, Xin Wang, Jiaheng Chao, Ling Feng, Wenwu Zhu
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=uKvHBTwC3D
- **中文提要：** 构建图语言模型的主流做法，是用图神经网络作图编码器，再通过对齐指令微调把表示与大语言模型对齐，从而结合语言模型的泛化能力与图结构建模能力。现有采用这一编码器的图语言模型在很大程度上仍有所忽略。
- **关键词：** instruction-tuning, alignment

### AutoDataBench: How Far Are LLM Agents from Autonomously Engineering Post-Training Data Pipelines?

- **作者：** Qiaoyu Tang, Hao Xiang, Le Yu, Yaojie Lu, Xianpei Han, Le Sun, Bowen Yu, Jiawei Chen, Zhenru Zhang, Peng Wang, Que Shen, Hongyu Lin, Dayiheng Liu
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=rf8RGRFNAS
- **中文提要：** 后训练数据流水线历来由研究者手工编排，负责生成、校验和多样性平衡。大语言模型已经能完成单个子任务，流水线的架构组合却仍是人工瓶颈，使后训练里最主要的工程步骤进不了自动化。
- **关键词：** instruction-following, post-training, fine-tuning

### Backdoor Purification for LoRA-Tuned LLMs via Null-Space Projection

- **作者：** Jianwei Li, Jung-Eun Kim
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=NAtwr6xj7t
- **中文提要：** 随着大语言模型和 PEFT 迅速普及，后门攻击的风险变得更严重。现有净化方法通常至少依赖一类强假设，比如事先知道触发器、能够取得干净参考，或进行激进再训练，而且往往缺少全面评估。
- **关键词：** LoRA, PEFT, fine-tuning

### Back to Blackwell: Closing the Loop on Intransitivity in Multi-Objective Preference Fine-Tuning

- **作者：** Jiahao Zhang, Lujing Zhang, Keltin Grimes, Zhuohao Yu, Gokul Swamy, Steven Wu
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=y6JzBUPPdU
- **中文提要：** 偏好微调里反复出现的挑战，是处理不可传递也就是循环的偏好。这类偏好常常来自单一目标上不一致的排序，或是把多个目标标量化成一个指标。
- **关键词：** instruction-following, fine-tuning

### Bayesian Preference Learning for Test-Time Steerable Reward Models

- **作者：** Jiwoo Hong, Shao Tang, Zhipeng Wang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=hjMgNSnHgL
- **中文提要：** 奖励模型处于用强化学习对齐人类偏好的核心位置。当强化学习扩展到可验证奖励和多目标对齐时，奖励模型被期望去编码更复杂、更多面的偏好分布。
- **关键词：** reward-model, alignment

### Behaving Better, Thinking Worse: Sycophancy Across Post-Training Stages

- **作者：** Sonnet Xu, Kritika Singh, Sheharbano Jafry, Roxana Daneshjou, Sanmi Koyejo
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=IUAXqLsMTC
- **中文提要：** 事实性迎合被放到多条后训练管线上追踪，评估分成生成评判与对数概率两轨，后者在上下文反驳和预先断言错误答案时分别报告对数几率差。分析还会按挑战类型与语境把结果拆开。
- **关键词：** post-training

### Behavior Pack Optimization for Video MLLM Post-Training

- **作者：** Zhaolu Kang, Shiyu Liu, Tailong Luo, Wei Zhang, Yingjie He, Guangyuan Dong, Siheng Wang, Liang He, Lei Wei, Jiaqi Su, Shuang Chen, Guansu Wang, Haoyu Ji, Qishi Zhan, Kaiyue Zhou
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=dnqyvgz1LI
- **中文提要：** 视频多模态大模型的问答成绩在上升，但打乱帧序、遮住支撑答案的片段或挡住目标物体，预测几乎不变。准确率主要依赖外观和语言先验，而不是问题所要求的时间证据。
- **关键词：** GRPO, SFT, post-training

### Benchmarking Membership Privacy Risks in Preference-Based LLM Post-Training

- **作者：** Lorenzo Rossi, Kaif Shaikh, Franziska Boenisch, Adam Dziedzic
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=TIAqMV9Kzf
- **中文提要：** 预训练之后的适配常用来听从指令、贴合用户偏好并改善部署行为，所用偏好数据可能来自用户、标注者或模型交互。这些数据里会夹带敏感提示、私人回答、专有任务或保密判断。
- **关键词：** PEFT, post-training, fine-tuning

### Beyond Decoupled PEFT: Geometry-Aware Low-Rank Adaptation via Riemannian Reparameterization

- **作者：** Yuanyang Cao, Xichun Liu, Haitao Jiang, Jianji Wang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=JSyN48PcBY
- **中文提要：** LoRA 及其权重分解变体主导着 PEFT，但方向更新与它们所施加的归一化参数化在几何上并不匹配。现有解耦方法先在无约束欧氏空间计算低秩方向更新，再投影回球面流形。
- **关键词：** LoRA, PEFT, fine-tuning

### Beyond difficulties: Insights for provably efficient design of autocurriculum in RLVR

- **作者：** Ruofan Wu, Xin Ge, Gao Xuemin, Guanhua Fang, Yangbin Shi, Dongbai Guo
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=sFKx4xt4ab
- **中文提要：** 可验证奖励强化学习越来越需要高效的课程。现有策略大多按成功率所代表的难度来选题，而难度只是间接代理，把题目难易和真实训练效用混在一起。
- **关键词：** GRPO, RLVR

### Beyond LoRA vs. Full Fine-Tuning: Gradient-Guided Optimizer Routing for LLM Adaptation

- **作者：** Haozhan Tang, Xiuqi Zhu, Xinyin Zhang, Boxun Li, Virginia Smith, Kevin Kuo
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=AC9LxjWtTf
- **中文提要：** 全参数微调能提供注入高熵知识所需的表示可塑性。许多任务只需在低秩空间里更新，并受益于 LoRA 的额外正则，因此 LoRA 有时可以达到或超过全参数微调。
- **关键词：** LoRA, fine-tuning

### Beyond Outcome Rewards: Process-Aware Optimization for Search Agents

- **作者：** Yiwei Dai, Hengyi Cai, Hui Wu, Yili Wang, Han Xu, Minlan Shao, Yuchen Li, Shuaiqiang Wang, Xin Wang, Yi Chang, Dawei Yin
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ypn6A8dz0y
- **中文提要：** 基于大模型的搜索智能体通过反复发查询、检索证据并整合信息，来处理复杂的信息寻求任务。只看最终答案对错，无法区分高效取证与冗余或方向错误的搜索。
- **关键词：** PRM, alignment

### Beyond Outcome Rewards: Step-Level Self-Distilled Policy Optimization for Deep Search Agents

- **作者：** Haoze Wu, Chuqiao Kuang, Tianyi Zhuang, Xiaoguang Li
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=B1ywhnzK7h
- **中文提要：** 深度搜索智能体的轨迹往往跨很多步，标准强化学习却只给整条轨迹一个结果奖励，信用分配过于稀疏。在线自蒸馏用模型自身的 logits 充当稠密的词元级教师，但扩展到搜索智能体时会引入一种根本张力。
- **关键词：** GRPO

### Beyond Parameter Aggregation: Semantic Consensus for Federated Fine-Tuning of LLMs

- **作者：** Amr Abourayya, Jens Kleesiek, Michael Kamp
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=4jInQZ53nD
- **中文提要：** 大模型的联邦微调通常被写成参数聚合问题。即便采用参数高效方法，仍要传输大量可训练权重，并假定架构对齐，而且能以白盒方式访问参数。
- **关键词：** PEFT, fine-tuning

### Beyond SFT-to-RL: Pre-alignment via Black-box On-policy Distillation for Multimodal RL

- **作者：** Sudong Wang, Weiquan Huang, Xiaomin Yu, Zuhao Yang, Hehai Lin, Keming Wu, Chaojun Xiao, CHEN CHEN, Wenxuan Wang, Beier Zhu, Yunjian Zhang, Chengwei Qin
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=NrU0jOBYTv
- **中文提要：** 大型多模态模型的常规后训练，是先在精选示范上做 SFT，再接可验证奖励的强化学习。SFT 会带来分布漂移，既保不住模型原有能力，也不能忠实贴合监督分布。
- **关键词：** GRPO, RLVR, SFT, post-training, alignment, fine-tuning

### Beyond Structural Agnosticism: Stable-Rank-Guided LoRA for Structure-Aware Fine-Tuning

- **作者：** Yuanyang Cao, Xichun Liu, Fuwei Zhang, Meiqin Liu, Jianji Wang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=XJnhTtLoXc
- **中文提要：** LoRA 等 PEFT 在结构上不加区分，各层使用统一配置，忽略了层与层之间很大的功能差异。SA-LoRA 按每一层的内在复杂度，自动调节微调强度。
- **关键词：** LoRA, PEFT, fine-tuning

### Bias-Variance Optimized Preference Optimization for Large Reasoning Models

- **作者：** Mingkang Zhu, Xi Chen, Bei Yu, Hengshuang Zhao, Jiaya Jia
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=SqjlMwxRLI
- **中文提要：** 大推理模型先写出推理轨迹，再给出最终答案，因而在多步推理上表现更强。面向这类模型的偏好对齐仍然缺少研究。
- **关键词：** preference-optimization, alignment

### Bilevel Optimization of Synthetic Trajectories for Multi-Turn LLM Fine-Tuning

- **作者：** Shresth Verma, Mauricio Tec, Cheol Woo Kim, Kai Wang, Milind Tambe
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=7kLOx2KkF4
- **中文提要：** 大模型擅长单轮生成，面对长程、多轮交互却吃力。离线强化学习提供了可扩展的途径，效果却取决于多轮轨迹数据是否充足、质量如何。
- **关键词：** fine-tuning

### Boosting Off-Policy RLVR with Data-Centric Replay

- **作者：** Yuxiao He, Junge Zhang, Ziqi Wang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=9dxvGd7Shr
- **中文提要：** 可验证奖励强化学习已成为提升大模型推理的重要途径。同策略训练仍占主导，但每次都要重新采样，数据效率较差。
- **关键词：** RLVR

### BoxTuning: Object-Aware Visual Prompting for Multimodal Model Fine-Tuning

- **作者：** Zekun Qian, Ruize Han, Wei Feng
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=q6gwQDgllS
- **中文提要：** 视频问答需要物体级的时空理解，现有多模态大模型却整帧编码，缺少显式的细粒度物体定位。把边界框坐标串成文本词元会带来根本的模态不匹配。
- **关键词：** fine-tuning

### BQ-LoRA: Binary-Quantized Low-Rank Adapters as Implicit Regularizers for Parameter-Efficient Fine-Tuning

- **作者：** Juyoung Park, Heejun Lee
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=nnhvsIx2Kl
- **中文提要：** 量化大模型的参数高效微调以 QLoRA 为主，它把权重量化和低秩适配器结合在一起。作者指出适配器不必保持浮点精度，可以改为二值参数，并配上逐层可学习尺度和缩放直通估计。
- **关键词：** QLoRA, LoRA, PEFT, fine-tuning

### C2FT: Enhancing Fine-Grained Perception in MLLMs via Confuse-then-Contrast Fine-Tuning

- **作者：** Shaoxuan He, Benlei Cui, Shikai Qiu, Yuwen Zhai, Hui Xue&#x27;, Longtao Huang, Jingqun Tang, Haiwen Hong
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=aktp1wVAdL
- **中文提要：** 多模态大模型经常做不好细粒度视觉感知，遇到外观相近、语义不同的实例就容易幻觉。一个主要原因是常规的单样本 SFT 把训练实例彼此隔离开。
- **关键词：** GRPO, SFT, fine-tuning

### CaC: Advancing Video Reward Models via Hierarchical Spatiotemporal Concentrating

- **作者：** Jiyuan Wang, Huan Ouyang, Chunyu Lin, Dewen Fan, Boheng Zhang, Tingting Gao, Fan Yang, Jia Sun, Zijun Li, Yongrui Heng, Huaiqing Wang, Zhenlong Yuan, Yiyang Fan, Honglie Wang, Fei Zuo, Haonan fan, Jiuzhou Lin, Guosheng Lin
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=K18iJJE8cU
- **中文提要：** 视频生成模型在全局视觉保真上已有明显进展。一旦合成复杂的动态内容，却常常出现稀疏而细微的异常。
- **关键词：** GRPO, SFT, reward-model, alignment, fine-tuning

### CAPER: Clause-Aligned Process Supervision for Text-to-SQL

- **作者：** Lujie Ban, Jiasheng Shi, Jinyang Li, Xiaolin Han, Tsz Nam Chan, Chenhao Ma
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=oj9P3hyKy9
- **中文提要：** Text-to-SQL 通常只按整条查询能否执行正确来评价，这种终局信号几乎说明不了是哪一步中间 SQL 决策导致成败。词元级稠密监督也不合适：SQL 词元对不齐完整的语义决策，可能惩罚执行等价的查询，而且难以大规模可靠标注。
- **关键词：** PRM, reward-model

### CapTrack: Multifaceted Evaluation of Forgetting in LLM Post-Training

- **作者：** Lukas Thede, Stefan Winzeck, Zeynep Akata, Jonathan Richard Schwarz
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=yznJFH0LsX
- **中文提要：** 大模型后训练可以增强潜在技能、实现价值对齐、提升表现并支持领域适应。它也会引发遗忘，尤其在使用第三方预训练模型时，这种遗忘通常被理解成参数知识或事实知识的丢失。
- **关键词：** preference-optimization, post-training, alignment, fine-tuning

### Cat-DPO: Category-Adaptive Safety Alignment

- **作者：** Tiankai Yang, Yi Nian, Xinyuan Li, Ruiyao Xu, Henry P Zou, Kaize Ding, Xiyang Hu, Yan Liu, Yue Zhao
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=dN2PIz3N8a
- **中文提要：** 对齐人类偏好需要同时做到：有助地回应正当请求，并可靠拒绝有害请求。多数基于偏好的安全对齐把安全收成单一标量，再均匀套到每一对偏好上。
- **关键词：** DPO, alignment

### C-GRPO: Conformal Group Relative Policy Optimization

- **作者：** Arya Fayyazi, Seyedarmin Azizi, Mehdi Kamal, Massoud Pedram
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=TrdqzzvFCs
- **中文提要：** 面向推理的训练越来越依赖多次同策略采样，标准 GRPO 却固定组大小，简单提示浪费计算，困难提示又探索不足。已有自适应预算方法的停止规则仍是启发式的，给不出有限样本的校准保证。
- **关键词：** GRPO

### ChunkFT: Byte-Streamed Optimization for Memory-Efficient Full Fine-Tuning

- **作者：** Yongkang Liu, Zijing Wang, Mengjie Zhao, Ercong Nie, Mingyang Wang, Qian Li, Feiliang Ren, Shi Feng, Daling Wang, Hinrich Schuetze
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=7uCEIbODMO
- **中文提要：** ChunkFT 把全参数微调改写成围绕动态激活的工作集来进行，以降低显存占用。它不改网络结构就能对任意子张量求梯度，从而优化任意子网络，并避开标准的稠密梯度计算。
- **关键词：** fine-tuning

### Class-Incremental Learning via LoRA-based Elastic Ensemble of Experts

- **作者：** Ruilong Yu, Fei Ye, Zhiyuan Ren, Qihe Liu, Adrian G. Bors, Rongyao Hu, shijie zhou
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=5v1mhJ0DnN
- **中文提要：** 大规模预训练视觉模型为类增量学习提供强表示，但要在没有历史样本、没有任务标识、参数也不能无限制增长的条件下持续适应新类别，仍然很难。现有 LoRA 做法通常要么每个任务新增一个适配器，要么采用固定的参数共享。
- **关键词：** LoRA, PEFT

### Clearer Sight, Fewer Lies: Oriented Pickup Preference Optimization for Multimodal Hallucination Mitigation

- **作者：** Xin Zou, Haolin Deng, Yibo Yan, Shuliang Liu, Zhiwei Jin, Chen Chen, Haonan Lu, Xuming Hu
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=4sDjEe8IfE
- **中文提要：** 多模态大模型容易幻觉，因为生成偏好没有充分校准到视觉证据，于是退回语言先验。若用模型自身的注意力把与查询相关的视觉证据显式加强，生成会变得更准确。
- **关键词：** preference-optimization, alignment

### C-LoRA: Continual Low-Rank Adaptation for Pre-trained Visual Models

- **作者：** Xin Zhang, Liang Bai, Xian Yang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=nf0YHUKcRr
- **中文提要：** 预训练视觉模型已成为计算机视觉的基础，但在数据和任务随时间变化的持续学习中仍然困难。LoRA 能高效微调，对这种动态环境的适应却仍然有限。
- **关键词：** LoRA, fine-tuning

### CodeScaler: Scaling Code LLM Training and Test-Time Inference via Reward Models

- **作者：** Xiao Zhu, Xinyu Zhou, Boyu Zhu, Hanxu Hu, Mingzhe Du, Haotian Zhang, Huiming Wang, Zhijiang Guo
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=prz41cA9Og
- **中文提要：** 代码大模型上的 RLVR 借助单元测试的执行反馈取得进展，可扩展性却受高质量测试用例是否充足、是否可靠所限制。CodeScaler 是为此设计的奖励模型，用来同时扩展强化学习训练和测试时推理。
- **关键词：** RLVR, reward-model

### Co-evolution: A "One-to-many" LLM Fine-Tuning Paradigm

- **作者：** Dapeng Jiang, Haichuan Tan, Wenxuan Song, Dianqiao Lei, Shenqi Zong, Yanyan Lan
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=qVAlPixuHg
- **中文提要：** 微调是把大模型适配到下游任务的核心手段，但多数方法仍是一对一：一个预训练模型被优化成一条改进后的策略。这只优化单策略的平均表现，无法区分重复的成功和真正互补的贡献。
- **关键词：** fine-tuning

### Co-GRPO: Co-Optimized Group Relative Policy Optimization for Masked Image Generation

- **作者：** Renping Zhou, Zanlin Ni, Tianyi Chen, Zeyu Liu, Yang Yue, Yulin Wang, Yuxuan Wang, Jingshu Liu, Gao Huang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ydt2nVtol8
- **中文提要：** 掩码扩散模型在视觉、语言和跨模态生成上都显示出潜力。它们的训练过程与推理过程之间却存在明显不一致。
- **关键词：** GRPO

### Complexity-Aware LoRA Aggregation for Modality-Heterogeneous Federated Person Re-identification

- **作者：** Kunyang Lv, Wenke Huang, Wenwen He, Bin Yang, Bo Du, Mang Ye
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=dZItc1V1aV
- **中文提要：** 统一的跨模态行人重识别希望稳健处理可见光、红外和文本等不同查询，但这需要多模态数据并集中训练，从而推高数据成本并带来隐私风险。作者提出模态异构的联邦重识别，让持有不同跨模态数据的客户端学习统一框架。
- **关键词：** LoRA, fine-tuning

### Complex Optimization Modeling via Multiagent Fine-Tuning and Skill-Augmented Reasoning

- **作者：** Yu Ding, Jiajun Li, Ran Hou, Jiahui Duan, Guanyu Nie, Xiongwei Han, Tao Zhong, Vincent Chau, Weiwei Wu, Wanyuan Wang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=8DDcXg3IK4
- **中文提要：** 优化建模是处理运筹问题的基础，却依赖专门的领域知识。大模型被看作有希望从自然语言描述出发，把这类建模自动化。
- **关键词：** PRM, fine-tuning

### COMPLLLM: Fine-tuning LLMs to Discover Complementary Signals for Decision-making

- **作者：** Ziyang Guo, Yifan Wu, Jason Hartline, Kenneth Holstein, Jessica Hullman
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=4kMncKrhE7
- **中文提要：** 当互补性成立时，多智能体决策可以胜过单智能体，因为不同智能体能为最终决定带来各自独有的信息。ComplLLM 基于决策理论，以互补信息为奖励，微调一个决策助手大模型，使其输出能补足已有智能体决策的信号。
- **关键词：** post-training, fine-tuning

### Compositional Reasoning in Language Models under Reinforcement Learning Post-Training

- **作者：** Yu He, Yingxi Li, Yifei Wang, Ellen Vitercik
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=4ElMzrtekX
- **中文提要：** 训练数据必然有限，模型必须把已学技能以新的方式组合起来才能泛化。强化学习等后训练明显提升了语言模型的推理能力，但对组合推理的影响仍不清楚。
- **关键词：** post-training

### Conformal Selective Acting: Anytime-Valid Risk Control for RLVR-Trained LLMs

- **作者：** Hamed Khosravi, Xiaoming Huo
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=vT3wPXlmSr
- **中文提要：** 在单一受监管机构内部署、并用本地数据经 RLVR 微调的专用大模型，需要一份只针对这一部署数据流、且在每一轮墙钟时间同时成立的安全证书。该证书不能跨部署汇集样本，也不能等到长期平均之后再判定。
- **关键词：** RLVR, LoRA, fine-tuning

### Consolidating Rewarded Perturbations for LLM Post-Training

- **作者：** Zheyu Zhang, Shuo Yang, Gjergji Kasneci
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=L9ncjOTwgM
- **中文提要：** 语言模型后训练常被看成由梯度下降实现的采样、打分、更新循环。以 RandOpt 为代表的路线把这一循环挪到权重空间，在预训练模型附近采样高斯扰动，并在推理时集成获得奖励的若干专家。
- **关键词：** GRPO, post-training

### CORA: Per-Slice Coherent Orthogonal Rotation for SVD-based Low-Rank Adaptation

- **作者：** Pengcheng Wang, Ziran Liu, Wei Wang, WEI JIANG
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=TMmhacwh3s
- **中文提要：** PEFT 常用低秩更新适配预训练权重，较新的方法还会利用基座权重的奇异值分解来做初始化或子空间选择。这些方法并没有显式保持预训练左右奇异基之间的耦合几何。
- **关键词：** LoRA, PEFT, fine-tuning

### Correctable Fork Tokens: Verifier-Anchored Selective Credit Assignment for Tool-Integrated RLVR

- **作者：** Shuqi Yin
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=IeA9ZyY6JF
- **中文提要：** 在接入工具的 RLVR 中，序列级验证信号所对应的轨迹结局，往往只由工具名、参数键和参数值这类稀疏词元决定。标准做法却给同一次采样中的每个词元相同优势，正好在关键位置稀释了信用。
- **关键词：** GRPO, RLVR

### Correct, Route, Calibrate: Efficient Preference Optimization from Noisy, Heterogeneous Human Feedback

- **作者：** Zhongming Xie, Xinwei Ma, Jingshen Wang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=UOoH4aqCJg
- **中文提要：** 人工标签是基于偏好的强化学习的重要监督，但收集过程中的现实约束常被标准训练目标忽略。DPO 通常把观察到的偏好标签当作干净信号，真实标注者却是异构的，可靠性也随情形变化。
- **关键词：** DPO, preference-optimization

### Counterfactual Rollout Replay: Forkable Environments as Free Process Rewards for Software Engineering Agents

- **作者：** Yuanhao li, Hongbo Wang, Xuhong Chen, Yiming Cao, Xunzhu Tang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=b0yS7nonHU
- **中文提要：** 强化学习已迅速成为训练软件工程智能体的主流，用来处理解决真实代码仓库问题这类长程多轮任务。奖励只在轨迹终点给出，中间却可能包含一连串文件修改、命令和测试，造成信用分配瓶颈。
- **关键词：** GRPO, PRM, reward-model

### Crafting Reversible SFT Behaviors in Large Language Models

- **作者：** Yuping Lin, Pengfei He, Yue XING, Yingqian Cui, Jiayuan Ding, Subhabrata Mukherjee, Hui Liu, Zhen Xiang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=6pycuJTqQi
- **中文提要：** SFT 会在大模型中诱发新行为，却不约束这些行为在模型内部如何分布。回路归因一类解释方法只能事后找出与这些行为相关的稀疏子网络。
- **关键词：** SFT, fine-tuning

### Cross-Attentive Bayesian Low-Rank Adaptation for Multimodal Uncertainty Estimation

- **作者：** Habibeh Naderi Khorshidi, Behrouz Soleimani, Stan Matwin
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=szn6IUxvw6
- **中文提要：** PEFT 便于适配冻结的语言模型，但多数方法是确定性或单模态的，在低资源音文场景里可靠性有限，因为不确定性同时取决于语言证据和声学条件。SPECTRA 通过跨模态词元级秩适应做随机后验估计，属于多模态贝叶斯低秩适应。
- **关键词：** LoRA, PEFT, fine-tuning

### Crowded in B-Space: Calibrating Shared Directions for LoRA Merging

- **作者：** Yixuan Tang, Yi Yang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=PtEkosDXWk
- **中文提要：** 把分别训练的 LoRA 适配器合并，是联合多任务训练之外的实用做法，但常常损害性能。现有方法通常把更新 ΔW=BA 当成一个整体，并不区分两个 LoRA 矩阵。
- **关键词：** LoRA

### CSO-LLM: Class Subspace Orthogonalization for Post-Training Backdoor Detection and Trigger Inversion in LLMs

- **作者：** Zhengxing Li, David J Miller, Guangmingmei Yang, George Kesidis
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=IkSweNEars
- **中文提要：** 后训练阶段的后门检测与触发器反演，在图像等模型上已有方案。针对大语言模型的同类方法仍然很少。
- **关键词：** post-training

### DACA-GRPO: Denoising-Aware Credit Assignment for Reinforcement Learning in Diffusion Language Models

- **作者：** Amin Karimi Monsefi, Dominic Culver, Nikhil Bhendawade, Lokesh Boominathan, Manuel R Ciosici, Yizhe Zhang, Irina Belousova
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=vjbVsKvLXq
- **中文提要：** 扩散大语言模型是自回归模型之外的一条路线，但现有强化学习把所有去噪步看得同样重要，并依赖有偏且方差很高的似然估计。薄弱之处在于去噪轨迹缺少时间维的信用分配，而且用于策略的平均场似然估计存在系统性偏差。
- **关键词：** GRPO

### Dataset Mismatch Matters in Group Relative Policy Optimization for Reinforcement Learning from Verifiable Rewards

- **作者：** Zhen-Yu Zhang, Jiandong Zhang, Huaxiu Yao, Gang Niu, Masashi Sugiyama
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=cqgCrzAcDZ
- **中文提要：** 可验证奖励强化学习在实践中很重要，其主要方法 GRPO 通常要在采样效率与下游表现之间取舍。为了兼顾两者，现有选择性采样主要只利用源侧的训练动态。
- **关键词：** GRPO, RLVR

### Debiased DPO for Diffusion Models

- **作者：** Duc Khiem Pham, Quang Nguyen, Tung D Nguyen, Jingsen Zhu, Michele Santacatterina, Dimitris Metaxas, Ramin Zabih
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=mVm3paaO7B
- **中文提要：** DPO 可以不显式建立奖励模型，直接用偏好对给扩散模型做离线对齐，但扩大规模需要大量昂贵的人工偏好。文中考虑半监督设定：只有一部分偏好对由人标注，其余更大的未标注池用廉价方式补标。
- **关键词：** DPO, preference-optimization, reward-model, alignment

### DEFT: Disentanglement-Enhanced Fine-Tuning for EEG Foundation Models

- **作者：** Yuqiu Deng, Muyun Jiang, Zongpeng Zhang, Mingqing Xiao, Yansen Wang, Peiliang Gong, XINLIANG ZHOU, Yi Ding, Ziyu Jia, Cuntai Guan, Chenyu Liu
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=raum5BFSpu
- **中文提要：** 脑电基础模型通过大规模多被试预训练改善表征，并把知识迁移到下游任务。预训练嵌入往往仍保留明显的被试相关变异，加重下游分类器的负担，跨被试时尤其如此。
- **关键词：** fine-tuning

### Detecting RLVR Training Data via Structural Convergence of Reasoning

- **作者：** Hongbo Zhang, Leyang Cui, Jianhao Yan, Guangsheng Bao, Yue Zhang, Shuo Yang, Yue Zhang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=7iHajwYLxA
- **中文提要：** RLVR 是训练现代推理模型的核心途径，但训练数据不公开，引发对基准污染的担忧。它不像预训练那样优化词元级概率，而是依据自生成推理轨迹的奖励来微调，使传统基于似然的检测方法更不适用。
- **关键词：** RLVR, fine-tuning

### Diffusion-DRF: Free, Rich, and Differentiable Reward for Video Diffusion Fine-Tuning

- **作者：** Yifan Wang, Yanyu Li, Guocheng Qian, Sergey Tulyakov, Yun Fu, Anil Kag
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=izqmMvuObQ
- **中文提要：** 视频扩散的对齐一直严重依赖标量奖励。这些奖励通常来自在人类偏好数据上训练的奖励模型，因此还需要额外训练和大量采集。
- **关键词：** GRPO, reward-model, alignment, fine-tuning

### Diffusion Fine-Tuning: Iterative Refinement for Advanced Grounding with Diffusion Large Language Models

- **作者：** Zhangyang Qi, Jinsong Li, Jiaqi Wang, Hengshuang Zhao
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=GUkwzvouGc
- **中文提要：** 大视觉语言模型擅长边界框定位，做多边形这类精确空间任务时却困难。顶点级自回归会让早期顶点的错误沿序列传播且得不到纠正，模型也会过早承诺局部顶点的位置。
- **关键词：** fine-tuning

### Diffusion fine-tuning with Rewarded Moment Matching Distillation

- **作者：** Alexis Jacq, Guillaume Couairon, Quentin Berthet, Valentin De Bortoli, Arnaud Doucet, Romuald Elie
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=k7jVv4PA8D
- **中文提要：** 蒸馏与强化学习微调同为扩散模型后训练的主要支柱。二者通常被分开研究，它们如何相互作用，尤其是微调怎样影响已蒸馏模型的生成质量，仍然不清楚。
- **关键词：** post-training, fine-tuning

### DISCOVER: Online Variance-Guided Data Discovery for Budgeted Multimodal GRPO

- **作者：** Peyman Gholami, Shivam Chandhok, Saber Malekmohammadi, Shayan Shams, Robert Xiao, Leonid Sigal
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=2MTnzpkl7i
- **中文提要：** 可验证奖励已成为提升多模态推理的重要后训练范式。GRPO 等方法在数据和计算上仍然不经济，常把采样与标注预算花在学习信号很弱的提示上。
- **关键词：** GRPO, post-training

### DISTMOE: Rehearsal-free Routing in Mixture-of-Experts for Distributed Instruction Tuning

- **作者：** Mainak Singha, Niccolò Biondi, Elisa Ricci, Subhankar Roy
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=WN0djCTue9
- **中文提要：** 多模态大模型的指令跟随能力很强，但适配多样的视觉语言领域时，通常假定数据可以集中访问，并要做昂贵的联合训练。数据分散在私有、领域专用或权限受限的客户端时，这一前提就很难成立。
- **关键词：** instruction-tuning, instruction-following

### Distributionally Robust Listwise Preference Optimization

- **作者：** Xudong Wu, Jian Qian, Pangpang Liu, Vaneet Aggarwal, Jiayu Chen
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=FL7ACXQ5Rb
- **中文提要：** 现有面向对齐的稳健偏好优化主要研究成对监督，并把稳健性放在数据集、提示或偏好对层面。这项工作转向排序标签不确定下的列表式偏好优化：给定提示和候选列表时，由于标注不一致、接近平局或有损的名次反馈，观察到的排序可能含糊。
- **关键词：** preference-optimization, alignment

### Distributionally Robust Token Optimization in RLHF

- **作者：** Yeping Jin, Jiaming Hu, Yannis Paschalidis
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=9zSXz3TUrv
- **中文提要：** 大模型更容易答对与训练及微调数据贴合的提示。措辞、格式或语言上的轻微变动却可能造成严重失败，多步推理问题上尤其明显。
- **关键词：** RLHF, fine-tuning

### Does the Question Really Matter? Training-Free Data Selection for Vision-Language SFT

- **作者：** Peng Sun, Yi Yang, Huawen Shen, Yi Ban, Tianfan Fu, Yanbo Wang, Yuqiang Li
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=kcBOe422p2
- **中文提要：** 视觉指令微调对提升视觉语言大模型至关重要。不少样本靠语言模式或常识捷径就能做对，并不需要真正的跨模态推理，从而限制了多模态学习的效果。
- **关键词：** SFT, instruction-tuning

### Dominant-Layer ZO: A Single Layer Dominates Zeroth-Order Fine-Tuning of LLMs

- **作者：** Wanhao Yu, Ziyan Wang, Zheng Wang, Abeer M Almalky, Yihang ZUO, Shuteng Niu, Sen Lin, Adnan Siraj Rakin, Deliang Fan, Li Yang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=LEaZsZB1xF
- **中文提要：** 零阶优化只用前向传播，就能以较低显存微调大模型，但有用的适应在各层之间如何分布并不清楚。这项工作发现，零阶微调明显由某一个解码层主导。
- **关键词：** LoRA, fine-tuning

### Don't Deploy Fine-Tuned Genomic Foundation Models Without Privacy Evaluation: Reconstruction Vulnerability Is Unpredictable Without Empirical Measurement

- **作者：** Reem Al-Saidi, Erman Ayday, Ziad Kobti
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ZXIGYkvoga
- **中文提要：** 这篇立场文章指出，大模型已被广泛用在敏感基因组数据上，既作为下游任务的微调分类器，也作为机构间共享的嵌入服务式基因组基础模型，却不评估嵌入能否被逆向还原成原始核苷酸序列。作者认为，缺少这种评估并非无害。
- **关键词：** fine-tuning

### DORA: A Scalable Asynchronous Reinforcement Learning System for Language Model Training

- **作者：** Tianhao Hu, Xiangcheng Liu, Yuchun Miao, Youshao Xiao, Hong Yu Zang, Yang Zheng, huang xuan, Jinrui Ding, Yufei Zhang, Yu Yang, Yi-Kai Zhang, Yueqing Sun, Chengcheng Han, Xiandi Ma, Wei Wang, Qi GU, Yerui Sun, Yuchen Xie, Xunliang Cai
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=DXbHLaGcFU
- **中文提要：** 异步强化学习已成为工业场景中加速大规模语言模型后训练的关键范式，但存在结构性的长尾困境：采样效率被少数最长轨迹拖住，而这些轨迹对训练恰恰最有价值。现有方法在缓解这一困境时要承担系统开销等代价。
- **关键词：** post-training

### DrPO: Drifting Preference Optimization for One-Step Generative Models

- **作者：** Zhou Jiang, Yandong Wen, Zhen Liu
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=WfyzQahi56
- **中文提要：** 单步文生图模型一次前向就能生成样本，便于部署，但现有偏好微调难以同时做到高效适应、不绑定特定奖励模型并保持生成多样。DrPO 被提出作为面向这类单步模型的在线偏好微调方法。
- **关键词：** preference-optimization, reward-model, alignment, fine-tuning

### Dual-Pronged LoRA: Achieving Near-Zero Forgetting and High-Performance Adaptation for MLLMs

- **作者：** Jingqi Ye, haonan he, Minglei Li, Fujun Han, Tao Chen, Peng Ye
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=5NC3OefOsg
- **中文提要：** 多模态大语言模型要适配专门且多样的下游应用，通常靠 LoRA 这类参数高效微调，但微调会严重损害预训练阶段的上游能力，也就是灾难性遗忘。
- **关键词：** DPO, LoRA, PEFT, fine-tuning

### DyCoRM: Dynamic Criterion-Aware Reward Modeling for Text-to-Image Generation

- **作者：** Jiaying Qian, Ziheng Jia, Qian Zhang, Zicheng Zhang, Jiayi Guo, Junqi Zhang, Guangtao Zhai, Xiongkuo Min
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=zzottG3vbp
- **中文提要：** 文生图已经越来越容易产出高质量图像，用户需求随之转向更贴合自身具体要求的结果。奖励模型要判断生成图像是否符合偏好，这一趋势给奖励建模带来了新的挑战。
- **关键词：** reward-model

### Dynamic Cross-Modal Prompt Generation for Multimodal Continual Instruction Tuning

- **作者：** Tao Hu, Da-Wei Zhou
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=aOCvDH4aTc
- **中文提要：** 多模态大语言模型靠指令微调取得强表现，真实部署却常常要在一连串任务上持续扩展能力。多模态持续指令微调希望在习得新能力的同时限制灾难性遗忘。
- **关键词：** instruction-tuning, LoRA

### EDITORS Know Your Style! Editing LoRA Subspaces for Stylistic Attribution and Imitation

- **作者：** Zixuan Wang, Gregory Kang Ruey Lau, Xiao Tian, Jue Fan, Caroline Chaux, Bryan Kian Hsiang Low
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=DAEi6FPYeD
- **中文提要：** 把写作风格从语义内容里拆开，是文学文本建模的基本难题。风格与内容缠在一起时，作者归属会依赖语义内容，风格模仿则会记住作者特有的内容。
- **关键词：** LoRA

### Efficient Collaborative LLM Fine-Tuning over Heterogeneous Mobile Devices via Many Backbones to One Side-Network Tuning

- **作者：** Xingke Yang, Liang Li, Sicong Li, Liwei Guan, Hao Wang, Xiaoqi Qin, Jiang Liu, Xin Fu, Miao Pan
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=g1dJyBM02E
- **中文提要：** 在异构移动设备上协同微调大语言模型，有望支撑个性化智能，但这一设想面临关键的系统挑战。
- **关键词：** alignment, fine-tuning

### Efficient Gradient-Aware Asynchronous Reinforcement Learning for LLM Post-Training

- **作者：** Songhan Yang, Jie Wang, Yinqi Bai, Xialiang Tong, Jianye Hao, Mingxuan Yuan, Feng Wu
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=z4T5PEbHgJ
- **中文提要：** 异步强化学习把轨迹生成与策略优化拆开，从而提高大语言模型后训练的效率。这种解耦会引入更早行为策略产生的过时离策略样本，带来分布偏移和不稳定的策略更新。
- **关键词：** post-training

### ENGINE: Endogenous Variational MultiScale Optimization for Zeroth-Order LLM Fine-Tuning

- **作者：** Zhuoli Ouyang, Changxi Chi, Siyuan Li, Tailin Wu
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=d0rAtRO4pl
- **中文提要：** 零阶优化让大语言模型微调更省显存，近期方法还会利用曲率信息。在庞大的参数空间里，这些方法却会遭遇梯度方差爆炸和难以承受的计算代价。
- **关键词：** fine-tuning

### Entropy Polarity in Reinforcement Fine-Tuning: Direction, Asymmetry, and Control

- **作者：** Jiazheng Zhang, Ziche Fu, Junrui Shen, Yunbin Zhao, Yunke Zhang, Zhiheng Xi, LongMa, Chenxin An, Zhihao Zhang, Shichun Liu, Dingwei Zhu, Shihan Dou, Shaofan Liu, han li, Wiggin Zhou, Aiden Adams, Tao Gui, Fei Huang, Qi Zhang, Xuanjing Huang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=S8HaL0jX6J
- **中文提要：** 策略熵已成为理解和调控大语言模型可验证奖励强化学习中探索行为的基本量。已有熵感知方法主要用全局目标调节熵，采样得到的策略更新如何在词元层面重塑策略熵，仍然缺少考察。
- **关键词：** RLVR, RFT, fine-tuning

### ESSAM: A Novel Competitive Evolution Strategies Approach to Reinforcement Learning for Memory Efficient LLMs Fine-Tuning

- **作者：** Zhishen Sun, Sizhe Dang, Guang Dai, Haishan Ye
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=FU76df5Sqr
- **中文提要：** 强化学习已成为提升大语言模型数学推理的关键步骤，但 GPU 显存占用往往很高，资源受限时难以使用。ESSAM 是一种全参数微调框架，以演化策略结合锐度感知最大化，并把零阶搜索纳入其中。
- **关键词：** GRPO, fine-tuning

### Estimating and Orthogonalizing Unknown Pre-training Gradients for Continual Fine-tuning of Large Language Models

- **作者：** Bing Wang, Changchun Li, Xin-Qiang Cai, Lin Y Wu, Ximing Li, Gang Niu, Masashi Sugiyama
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=RvsI4JyU2Q
- **中文提要：** 持续微调让大语言模型适应真实环境，却不可避免地带来灾难性遗忘，尤其是先前任务变差以及通用知识退化。正交梯度投影等方法能减轻不同微调任务之间的遗忘，但在更根本的层面上仍然失败。
- **关键词：** fine-tuning

### Even Sailors Need Calm Seas: Taming the Geometry of VLMs for Fast Adversarial Fine-Tuning

- **作者：** Yuqing Wen, Junhao Dong, Ting Peng, Xudong Zhang, Jiaming Zhang, Weiming Liu, Zhengtao Yao, Xinghua Qu, Yew Soon Ong
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=elpJhhSIEj
- **中文提要：** CLIP 等视觉语言模型跨任务表现强，却对对抗攻击非常脆弱。对抗微调可以抵御这类恶意输入，但微调期间多步生成对抗样本，会给视觉语言骨干带来过高的计算成本。
- **关键词：** fine-tuning

### Every Sample Counts: Supervised Fine-Tuning of Language Models with Pointwise Constraints

- **作者：** Ignacio Hounie, Ignacio Boero, Alejandro Ribeiro
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=6BYu5yc6pZ
- **中文提要：** 微调语言模型时，常常需要对单条输入施加约束，同时又不能牺牲整体表现。当前对齐方法通常只在平均意义上加约束，这可能在不同输入或用户之间造成不希望出现的差距。
- **关键词：** SFT, instruction-following, alignment, fine-tuning

### Evolution Fine-Tuning: Learning to Discover Across 371 Optimization Tasks

- **作者：** Young-Jun Lee, Seungone Kim, Minki Kang, Alistair Liang Chuen Cheong, Zerui Chen, Seungho Han, Taehee Jung, Dongyeop Kang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=www9RVeEpg
- **中文提要：** 把大语言模型接进演化搜索后，已在开放数学猜想、GPU 内核设计、科学定律发现和组合谜题等优化任务上给出很强的解。演化微调进一步追问：设计更快 GPU 内核的经验，能否帮助逼近长期未解的数学猜想。
- **关键词：** mid-training, fine-tuning

### Explaining and Preventing Alignment Collapse in Iterative RLHF

- **作者：** Etienne Gauthier, Francis Bach, Michael Jordan
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=3azE5mTgC1
- **中文提要：** 迭代部署时，策略生成的数据会被用来重新训练奖励模型，从而形成反馈回路。这与 RLHF 通常假设奖励模型静态、不具备策略性的设定不同。
- **关键词：** RLHF, reward-model, alignment

### ExpRFT: Exponential Reward-Weighted Fine-Tuning for Offline RL in Multi-Turn Dialogue

- **作者：** Huy Dao, Lizi Liao
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=DE0tMV3YZo
- **中文提要：** 离线强化学习是在多轮对话上微调大语言模型的常用范式，因为在线采样和奖励标注都很贵。其中，奖励加权监督微调按依赖于奖励的系数，对每条轨迹的对数似然加权。
- **关键词：** SFT, fine-tuning

### FairTune Market: A Fair and Trustworthy Marketplace for Fine-Tuned LLMs via Posted-Price & Proper-Scoring Mechanisms

- **作者：** Jiachen Shen, Xingke Yang, Hui Zhong, Aohan Li, TOMOAKI OHTSUKI, Xin Fu, Miao Pan, Zhu Han
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=WIuScfyKmS
- **中文提要：** 个性化微调能改善使用体验，但计算成本很高。从风格相近的已微调模型初始化可以明显降低适配开销，使这些模型成为可复用、可交易的资产。
- **关键词：** fine-tuning

### FedLoVA: Value-Only Aggregation for Federated LoRA Fine-Tuning of Large Language Models

- **作者：** Ensieh Khazaei, Baturalp Buyukates, Dimitrios Hatzinakos
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=xlkHd6pwR7
- **中文提要：** LoRA 因表现和通信效率，成为联邦学习中常用的 PEFT 方法。实践里它被加到 Transformer 的查询与价值投影上，却没有考虑这两类分量角色不同。
- **关键词：** LoRA, PEFT, fine-tuning

### FedReCall: Recalling Client-Specific Directions in Federated LoRA Fine-tuning

- **作者：** Chang Liu, Jinqian Chen, Jihua Zhu, Xiangyang Yang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=sY42gw5mw5
- **中文提要：** LoRA 让大语言模型的联邦微调更省通信，但标准 FedLoRA 把因子 A 和 B 分开平均，而模型更新取决于二者的乘积。任务异构时，按因子聚合还会进一步稀释那些只对本地有用、在客户端之间并不强共享的方向。
- **关键词：** LoRA, fine-tuning

### Fed-SB: A Silver Bullet for Extreme Communication Efficiency and Performance in (Private) Federated LoRA Fine-Tuning

- **作者：** Raghav Singhal, Kaustubh Ponkshe, Rohit Vartak, Lav Varshney, Praneeth Vepakomma
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://neurips.cc/virtual/2026/poster/156778
- **中文提要：** LoRA 已广泛用于高效微调基础模型。用 LoRA 做联邦微调时，对各个适配器做传统联邦平均会产生次优更新，因而仍然困难。
- **关键词：** LoRA, fine-tuning

### Felid: A Flexible and Efficient Design for Transformer Fine-Tuning over Encrypted Data

- **作者：** Linru Zhang, Jun Jie Sim, Xiangning Wang, Jiahao Zhong, Kaiyu Zhou, Huanyi Ye, Yongsen Zheng, Lushan Song, Xiaojian Liang, Yingting Liu, Yujing Sun, Huaxiong Wang, Pu Duan, Kwok-Yan Lam
- **会议：** NeurIPS 2026 · Main · Oral
- **官方论文页：** https://openreview.net/forum?id=yglphSefi0
- **中文提要：** 全同态加密可以在非交互、保护隐私的前提下微调 Transformer，使高度敏感的数据不会直接暴露给大语言模型。先前工作主要靠改进架构来提效，整体性能仍受加密计算本身高昂代价的限制。
- **关键词：** fine-tuning

### FELPS: Fair and Efficient Scheduling for Multi-LoRA Serving System

- **作者：** Yukai Ding, Chuang Hu, Fangcheng Fu, Xinyan Li, Susie X Rao, Shanshan Feng, Hao Wang, Xiao Yan, Jiawei Jiang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=q6S0veB7O2
- **中文提要：** 实际系统常要并发服务多个 LoRA 适配器来处理不同任务。公平与效率之间存在张力：追求公平就需要在适配器之间频繁切换。
- **关键词：** LoRA, PEFT, fine-tuning

### Few-Shot Truly Benign DPO Attack for Jailbreaking LLMs

- **作者：** Yoon Sangyeon, Wonje Jeung, Yoonjun Cho, Dongjae Jeon, Albert No
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=e0AAyKxXc8
- **中文提要：** 微调接口让前沿大语言模型易于定制，也可能在微调过程中削弱安全对齐。已有研究表明良性 SFT 会降低拒绝行为，而部署中的微调流程越来越多地支持基于偏好的目标，其安全风险仍较少被理解。
- **关键词：** DPO, SFT, preference-optimization, alignment, fine-tuning

### $f$-GRPO & Beyond: Divergence-Based Reinforcement Learning Algorithms for General LLM Alignment

- **作者：** Rajdeep Haldar, Lantao Mei, Guang Lin, Yue XING, Qifan Song
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=LyjBw9qa3a
- **中文提要：** 偏好对齐目标可以被看成对齐分布与未对齐分布之间的散度估计，并由此得到设计对齐损失的原则性做法。不过这一视角至今仍局限于基于偏好的监督。
- **关键词：** GRPO, RLVR, preference-optimization, reward-model, alignment

### FiLoRA: Focus-and-Ignore LoRA for Controllable Feature Reliance

- **作者：** Hyunsuk Chung, Caren Han, Seungyeon Ji, Jinwoo Kim, Eun-Jung Holden, Kyungreem Han
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=2eluv7sJYW
- **中文提要：** 多模态基础模型融合了跨模态的异质信号，但预测如何依赖特定内部特征组、这种依赖能否被有意控制，仍然不清楚。关于捷径和虚假行为的研究多依赖事后分析或特征移除，对依赖能否被调节提供的认识有限。
- **关键词：** LoRA, PEFT

### FILOsofer: A TEE-Shielded Model Partitioning Framework based on Fisher Information-Guided LoRA Obfuscation

- **作者：** Fan zhang, Ziqi Zhang, Hossein Khalili, Neiro Cabrera, Jonathan Xue, Nader Sehatbakhsh
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=wrEeZDfTbu
- **中文提要：** 端侧机器学习把深度网络暴露成白盒，容易遭受模型窃取。可信执行环境可以通过隔离执行来降低这一风险，但把整个模型放进可信执行环境的开销难以承受。
- **关键词：** LoRA

### Fine-tuning Does Not Reach All: Uneven Safety and Knowledge Dynamics in Language Models

- **作者：** Ziwei Wang, Xinwei Guo, Jiaxin Zhang, Guanhua Chen, Haiyan Wu, Xiangyu Zhao, Lei Ma, Xin Yao, Shan He, Xuetao Wei
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=7MsNSkqKWp
- **中文提要：** 微调被广泛用于让大语言模型符合安全等行为规范，评估却常用假定改进处处均匀的总体指标。微调实际局限在受限的参数空间里，它对局部知识缠结在一起的影响仍不清楚。
- **关键词：** alignment, fine-tuning

### Fine-Tuning Improves Information Conveyance in Language Models

- **作者：** Yuwei Cheng, Weiyi Tian, Haifeng Xu
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=TqEugPEDx7
- **中文提要：** 人们常认为微调会降低大语言模型的不确定性与多样性，但既有分析忽略了输出长度这个关键混淆因素，因而看不清不确定性如何分布在整段生成过程中。为此提出冠层熵，从树的视角看待语言生成。
- **关键词：** fine-tuning

### Fine-Tuning Language Models to Know What They Know

- **作者：** Sangjun Park, Elliot Meyerson, Xin Qiu, Risto Miikkulainen
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=mTpoDbfFvY
- **中文提要：** 偏差和启发式使大语言模型的真实元认知难以评估。文中给出一套框架，在控制这些偏差的同时测量并增强模型的元认知。
- **关键词：** alignment, fine-tuning

### Finetuning with Sampling: Make SFT Generalize, Not Forget

- **作者：** Aayush Karan, Sitan Chen, Yilun Du
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=kXgdaUrvBN
- **中文提要：** 给前沿模型增加新能力主要依靠后训练中的 SFT 与强化学习。通行看法认为同策略强化学习能在新任务上强泛化且不丢掉已有能力，SFT 则容易泛化不足并发生遗忘。
- **关键词：** SFT, post-training, fine-tuning

### FLoRA-Chef: Making A Good LoRA Recipe in Federated Generalization

- **作者：** Wenwen He, Wenke Huang, Yiyan Qi, He Li, Ming Hu, Yi Liu, Guansong Pang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=qDbRHtLtST
- **中文提要：** LoRA 只用少量可训练参数来适配大模型。联邦 LoRA 把这一做法扩展到联邦学习，客户端通过交换 LoRA 参数协同微调共享模型，而无需共享原始数据。
- **关键词：** LoRA, PEFT, fine-tuning

### Frank-LoRA: Federated Rank-Aware LoRA for Fine-Tuning Large Models

- **作者：** Saber Malekmohammadi, Kevin Kuo, Virginia Smith, Golnoosh Farnadi
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=uPdmJxDBM2
- **中文提要：** 在资源受限的分布式客户端上微调大规模基础模型，计算和通信都很困难。LoRA 与联邦学习结合后可以按秩灵活配置，但适配矩阵 A 与 B 相互依赖，常常使优化更复杂。
- **关键词：** LoRA, fine-tuning

### From Experts to Sub-experts: Fine-grained Parameter-Efficient Fine-Tuning for MoE LLMs

- **作者：** Zhentao Tan, Chang Liu, Yao Liu, Yue Wu, Jieping Ye
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=760IPZeujm
- **中文提要：** 大语言模型规模快速增长后，稠密的全参数适配越来越贵，混合专家这类稀疏模块化结构因此受到关注。对 PEFT 而言，核心问题是应按何种粒度选择并更新参数。
- **关键词：** LoRA, PEFT, fine-tuning

### From Label Priors to Task Evidence: Long-Video Frame Selection via Bayesian GRPO

- **作者：** Shuochen Chang, Bingjie Gao, Qingyang Liu, Qianli Ma, Yibo Miao, Haonan Zhao, Zhaohe Liao, Xiaofeng Zhang, Jiangtong Li, Li Niu
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Pw7tnoVlx1
- **中文提要：** 长视频理解中，二次注意力复杂度和上下文窗口限制给多模态大语言模型带来明显的可扩展性困难。现有基于检索的方法通常在静态关键帧标注上做监督学习。
- **关键词：** GRPO

### From Patches to Trajectories: Privileged Process Supervision for Software-Engineering Agents

- **作者：** Murong Ma, Tianyu Chen, Yun Lin, Shuai Lu, Qinglin Zhu, Yeyun Gong, Zhiyong Huang, Peng CHENG, Yan Lu, Jin Song Dong
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=iQIFIFP5W7
- **中文提要：** 在长教师轨迹上做 SFT，是给开源软件工程智能体注入调查与推理能力的主流做法。SFT 把每条保留回复都当作模仿目标，学生因此不仅继承轨迹的结果，也会继承中间步骤的缺陷，包括缺乏依据的跳跃和多余循环。
- **关键词：** SFT, fine-tuning

### From Squeezing to Grounding: Visual Guided DPO for Multimodal Hallucination Mitigation

- **作者：** Wenqi Liu, Hongxin He, Yunxiao Wang, Xuemeng Song, Yupeng Hu, Yinwei Wei
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=DdP4SoPK7L
- **中文提要：** DPO 被广泛用来减少多模态大语言模型的幻觉。已有研究和对训练过程的观察表明，被选回复与被拒回复的对数概率可能同时下降，从而显露出挤压效应。
- **关键词：** DPO, preference-optimization

### From “Weak” Signals to Strong Models: Preference Delta Aggregation with LoRA Merging

- **作者：** Qi Sun, Siyue Zhang, Yulin Chen, Yuxiang Xue, Ru Peng, Chen Zhao
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=NTLZwZkDzg
- **中文提要：** 训练强大的大语言模型需要高质量监督，而这种监督常常稀缺。较弱模型与更弱模型之间的成对偏好，尽管单条回复质量有限，仍能通过相对质量差提供有效监督，文中称之为“弱”信号。
- **关键词：** preference-optimization, LoRA, alignment

### From Weeks to Hours: Fast and Principled SFT Curation for LLM

- **作者：** Hongyi Henry Jin, Wenhan Yang, Meysam Ghaffari, Carlos Morato, Baharan Mirzasoleiman
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=4jOHUJJVCg
- **中文提要：** 面向推理的后训练使大语言模型能够通过多步推断解决复杂任务。在高质量推理轨迹上做 SFT 尤其高效，但其效果严重依赖于审慎的数据筛选。
- **关键词：** SFT, LoRA, post-training, fine-tuning

### FuRA: Full-Rank Parameter-Efficient Fine-Tuning with Spectral Preconditioning

- **作者：** Yequan Zhao, Ruijie (Ray) Zhang, Liyan Tan, Niall Moran, Tong Qin, Zheng Zhang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=zf1vYk0XnQ
- **中文提要：** 全量微调和 LoRA 等参数高效方法在加入权重更新时，都不顾及预训练已经建立的谱结构。来自小规模微调分布的噪声梯度因此可以随意扰动预训练学到的稳健特征。
- **关键词：** instruction-tuning, QLoRA, LoRA, PEFT, fine-tuning

### GenRM-Flow: Generators are Process-aware Reward Models in Flow Matching

- **作者：** Siming Fu, Zheming Fu, Ruizhe He, Zeyue Xue, Fengkai Liu, Yufei Jiao, Jie Huang, Xiaoxiao Ma, Xuan Yang, Lihui Luo
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=dPSEe9I3nw
- **中文提要：** 视频生成模型与人类偏好对齐，很大程度上取决于给生成视频打分的奖励模型质量。当前视频奖励模型的奖励信号来自表征能力而非生成能力：要么把视觉语言模型改用于像素空间打分，要么在冻结的生成器特征上训练辅助打分头。
- **关键词：** GRPO, DPO, preference-optimization, PRM, reward-model, alignment, fine-tuning

### Geometry-Aware Zeroth-Order Optimization for Fine-Tuning Quantized LLMs

- **作者：** Shaocong Ma, Weidong Cai, Heng Huang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=6r0PI7Q3I7
- **中文提要：** 零阶优化有望以较低显存微调大语言模型。若要在单块 GPU 上把零阶优化扩展到更大的模型，就必须采用激进量化，而这常常使训练不稳定。
- **关键词：** fine-tuning

### Geometry Conflict: Explaining and Controlling Forgetting in LLM Continual Post-Training

- **作者：** Yuanyi Wang, Yifan Yang, Su Lu, Yanggan Gu, Pengkai Wang, Wenjun Wang, Zhaoyi Yan, Congkai Xie, Jianmin Wu, Jialun Cao, Shing-Chi Cheung, Hongxia Yang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=8EOfA3Wh07
- **中文提要：** 持续后训练旨在为大语言模型扩展新的知识、技能和行为，但顺序更新何时促成能力迁移、何时导致灾难性遗忘仍不清楚。顺序微调、回放、正则化或模型合并可以减轻遗忘，却很少提供判断何时该纳入新更新的准则。
- **关键词：** post-training, fine-tuning

### Gradient-Mine Units: Scorched-Earth Strategy for Model Protection against Unauthorized Fine-Tuning

- **作者：** Jinhyeok Jang, Jaehong Kim, ByungOk Han
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=WD7CiQOOR7
- **中文提要：** 预训练模型权重越来越多地在商业许可、使用限制或其他禁止未授权微调的条件下发布。实际中，这类滥用事后很难被发现或核实。
- **关键词：** fine-tuning

### GradShield: Alignment Preserving Finetuning

- **作者：** Zhanhao Hu, Xiao Huang, Patrick Mendoza, Emad A Alghamdi, Basel Alomair, Raluca Popa, David Wagner
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=dQFVIxjyvV
- **中文提要：** 大语言模型在微调后存在明显的安全失对齐风险，显式和隐式有害数据都可能破坏模型。即便一些看似无害的数据，也可能在无意中把模型推向失对齐行为。
- **关键词：** alignment, fine-tuning

### Grounding Agent Reasoning with Structured Process Supervision for Multi-turn Reinforcement Learning

- **作者：** Renting Rui, Yulei Qin, Weiwen Liu, Yunjia Xi, Ke Li, Xing Sun, Weinan Zhang, Yong Yu
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=519KXHiEy2
- **中文提要：** 用基于结果的强化学习训练的长程大语言模型智能体存在系统性失败：推理会在某一步偏离环境观测，误差再在后续回合中叠加。失败轨迹中会出现推理与观测不一致，而且这种不一致一旦出现，后续回合往往仍然不一致。
- **关键词：** PRM

### GUI-Libra: Data-Efficient Post-Training for Reliable Reasoning-and-Acting in Native GUI Agents

- **作者：** Rui Yang, Qianhui Wu, Zhaoyang Wang, Hanyang Chen, Ke Yang, Hao Cheng, Huaxiu Yao, Baolin Peng, Huan Zhang, Jianfeng Gao, Tong Zhang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=JFNpUWpOmR
- **中文提要：** 开源的原生图形界面智能体在长程任务上仍落后于闭源系统。原因之一是直接沿用通用后训练流程，忽略了界面特有的失败模式：带长思维链的标准 SFT 常常损害定位，强化学习中更强的离线优化也未必带来更好的在线表现。
- **关键词：** SFT, post-training, fine-tuning

### HALO: Heterogeneous-Aware LoRA Optimization via Rank Allocation and Client-Aware Projection

- **作者：** Xiaohua Feng, Yuyuan Li, Jiayuan Fang, Fengyuan Yu, Jiaming Zhang, Li Zhang, Xiang Liu, Jun Wang, Chaochao Chen
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=GCoRDt8PdU
- **中文提要：** 联邦学习配合 LoRA，可以在保护隐私的情况下协同微调基础模型。已有联邦 LoRA 研究常常假定秩是同质的，又缺少有原则的秩分配，在数据和资源异构时会导致欠拟合或过拟合。
- **关键词：** LoRA, fine-tuning

### HALO: Homotopy-Augmented Layer Optimization for Stable LLM Supervised Post-training

- **作者：** Mengxiang Zhang, Lingyuan Liu
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=VEZb4LjBJS
- **中文提要：** 包括 SFT 和知识蒸馏在内的监督后训练，是把大语言模型适配到专门领域所必需的。传统监督后训练却常常面临灾难性遗忘、训练不稳定以及难以承受的计算成本。
- **关键词：** SFT, post-training, fine-tuning

### Hider–Seeker Self-Play: Geometry-Verifiable Process Rewards for Long-Horizon Visual Search

- **作者：** Yu Mao, Shengchao Chen
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=smof5snaBr
- **中文提要：** 长程视觉搜索要求视觉语言策略在高分辨率图像上执行多步空间动作，表现取决于整条轨迹而不是任何单次决策。只看结果的 RLVR 会把许多几何决策压成一个延迟信号，并丢弃环境已经逐步算出的几何信息。
- **关键词：** RLVR, PRM

### HiFloat4 Format for End-To-End Reinforcement Learning Post-Training of Large Language Models

- **作者：** Hei Yi Mak, Shadan Golestan, Hoang Le, Mehran Taghian Jazi, Yunke Peng, Yaoyuan Wang, Yao Wang, JUNSONG WANG, Tianchi Hu, Fengchen He, Guipeng Hu, Tanzila Rahman, Anandharaju D Raju
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=BDwmB9cg99
- **中文提要：** HiFloat4 将强化学习后训练做成端到端的 FP4 流程，采样策略和训练策略的前向与反向都在这一精度下运行。系统研究表明，FP4 强化学习性能下降的主要来源不是训练侧的量化误差，而是采样激活的量化：离群值把动态范围拉得过宽。
- **关键词：** post-training

### HiLoRA: Adaptive Hierarchical LoRA Routing for Training-Free Domain Generalization

- **作者：** Ziyi Han, Huanyu Wang, Zeyu Zhang, Xiangxiang Dai, Xutong Liu, John C. S. Lui
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ZbObuTCYWv
- **中文提要：** LoRA 因其模块化设计以及在 HuggingFace 等平台上广泛可得，成为把大语言模型适配到新领域的常用技术。这种可得性促使人们复用已有 LoRA 来做领域泛化。
- **关键词：** LoRA

### How does RL Post-training Induce Skill Composition? A Case Study on Countdown

- **作者：** Simon Park, Simran Kaur, Sanjeev Arora
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=zb8jA9cOxq
- **中文提要：** 强化学习能够增强大语言模型的推理，但它对组合泛化（从已知成分合成新技能）的作用，常常与单纯的长度泛化混在一起。该案例考察后训练究竟教给模型什么技能组合，以及组合结构如何影响技能迁移。
- **关键词：** post-training

### How Fine-Tuning Objectives Shape Layer-Wise Information in LLM Hallucination Detection

- **作者：** Kaiyang Wan, Forrest Bao, Amin Ahmad, Yuxia Wang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Vlr7fHQiNH
- **中文提要：** 在条件对齐时，分类头微调在二值幻觉检测上持续优于把大语言模型当作评判器的序列到序列做法。这一差距被归结为两种目标所诱导的表示不同。
- **关键词：** fine-tuning

### How Finite-Rank Bottleneck Shape the Low-Rank Adaptation Landscape

- **作者：** Long Nguyen-Chi, Quynh Nguyen, Thanh Nguyen Cung, Binh T. Nguyen
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=eyfZvKjtnQ
- **中文提要：** LoRA 已成为大预训练模型参数高效微调的标准方法，但低秩更新为何已经够用，理论解释仍不完整。多数现有分析依赖神经切核情形，也就是在预训练权重附近把网络线性化。
- **关键词：** LoRA, PEFT, fine-tuning

### How Neural Reward Models Learn Features for Policy Optimization: A Single-Index Analysis

- **作者：** Rei Higuchi, Ryotaro Kawata, Akifumi Wachi, Shokichi Takakura, Kohei Miyaguchi, Taiji Suzuki
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=CP2FzuoOFQ
- **中文提要：** 在带 KL 正则的策略优化中，学到的奖励会被取指数以定义实际部署的策略，因此下游价值取决于奖励被倾斜区域里的误差。这一反馈在高斯单指标模型中得到分析。
- **关键词：** reward-model

### How New Strategies Emerge in RL Post-Training: A Controlled Study

- **作者：** Azwar Azwar, Nishil Patel, Andrew Saxe
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=amAQ0bvrH7
- **中文提要：** 强化学习后训练是在构建新的推理程序，还是仅仅对基座模型中已经潜伏的行为重新加权？该研究在完全可观测的重写文法环境中考察这一问题，其中预训练分布已知，生成的每一步改写都可以被核查。
- **关键词：** RFT, post-training, fine-tuning

### How Post-Training Shapes Biological Reasoning Models

- **作者：** Lukas Fesser, Hanlin Zhang, Michelle M Li, Eric Wang, Bryan Perozzi, Shek Azizi, Sham Kakade, Marinka Zitnik
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=WkAhF5XkTP
- **中文提要：** 后训练是构建科学推理模型的核心，但在生物学中其效应仍不清楚，因为模型要把自然语言与多模态生物数据结合起来。这里考察后训练各阶段如何塑造泛化，以及它们何时提升表现、何时导致过度专门化。
- **关键词：** SFT, continued-pretraining, post-training, alignment, fine-tuning

### Hybrid-LoRA: Bridging Full Fine-Tuning and Low-Rank Adaptation for Post-Training

- **作者：** Chengqian Zhang, Wei Zhu, Kyumin Lee
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=DFA11q5IQD
- **中文提要：** 后训练已成为把大语言模型适配到指令遵循、偏好对齐和多步推理等复杂下游行为的必要环节。可验证奖励强化学习近来对提升推理尤其有效，GRPO 和 GSPO 等无评论家算法被用于这一方向。
- **关键词：** GRPO, RLVR, instruction-following, preference-optimization, LoRA, PEFT, post-training, alignment, fine-tuning

### HyperSkill: Training-Free Omnimodal GRPO via Hypergraph-Indexed Skill-Library Evolution

- **作者：** Haoran Luo, Shangkai Lin, Jinyang Wu, XINLIANG ZHOU, Anh Tuan Luu
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=vk6Ou7cymq
- **中文提要：** 强化学习能打磨大语言模型的推理，但参数更新昂贵、容易遗忘且不透明；免训练技能库用文本库存代替梯度，却仍按整条轨迹准入，结构也是扁平的。HyperSkill 作为一种免训练的全模态 GRPO，保持骨干冻结，并把梯度更新替换为对超图索引对象的可审计编辑。
- **关键词：** GRPO

### IFDECORATOR: Wrapping Instruction Following Reinforcement Learning with Verifiable Rewards

- **作者：** Xu Guo, Tianyi Liang, Jian Tong, Xiaogui Yang, Ling-I Wu, Chenhui Li, Zhihui Lu, Qipeng Guo, Kai Chen
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=vEcdUTiDxm
- **中文提要：** 可验证奖励强化学习被用来增强大语言模型的指令遵循能力。用于指令遵循时，它仍然样本效率低，而且容易奖励投机：模型利用验证上的捷径，而不是完成指令的核心意图。
- **关键词：** RLVR, instruction-following, alignment

### Inference-time Alignment via Sparse Junction Steering

- **作者：** Runyi Hu, Jie Zhang, Shiqian Zhao, Jiale Meng, Jiwei Li, Jason Zeng, Ming Wu, Michael Heinrich, Yonggang Wen, Tianwei Zhang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=2zZdeKdoc6
- **中文提要：** 词元级转向通过调节输出分布，在不更新参数的情况下对大语言模型做细粒度控制，成为推理时对齐的关键途径。现有方法虽然有效，却依赖在每一个解码步上进行稠密干预。
- **关键词：** post-training, alignment

### Innocuous-Seeming Data, Latent Ideology: Ideological Generalisation in Finetuned LLMs

- **作者：** Robert Graham, Edward Stevinson, Yariv Barsheshat
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=wYDEd2wtpL
- **中文提要：** 在小规模、经过策展的数据上微调，是把语言模型适配到特定政策或领域的常规做法。即便数据范围狭窄、事实上站得住且能通过审核，微调仍可能在无关领域造成广泛的意识形态偏移，同时保留一般能力。
- **关键词：** fine-tuning

### INSPO : Unlocking Intrinsic Self-Reflection for LLM Preference Optimization

- **作者：** Yu Li, Tian Lan, Zhengling Qi
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=L04yHIK5g8
- **中文提要：** INSPO 从已成为大语言模型对齐常规手段的 DPO 及其变体入手，指出其中仍存在根本局限。
- **关键词：** DPO, RLHF, preference-optimization, alignment

### IRIS: Interpolative Rényi Iterative Self-play for Large Language Model Fine-Tuning

- **作者：** Wenjie Liao, Like Wu, Liangjie Zhao, Shihui Xu, Shigeru Fujimura
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=yx017YEEPx
- **中文提要：** 自博弈微调让大语言模型对照标注回复与自我生成回复，在没有额外人工标注时超越监督微调；不少现有方法则固定在某一种散度设定上。
- **关键词：** SFT, fine-tuning

### IRPO: Boosting Image Restoration via Post-training GRPO

- **作者：** Haoxuan Xu, Yi Liu, Tianfu Li, Ruolin Shen, Boyuan Jiang, Jinlong Peng, Donghao Luo, Xiaobin Hu, Shuicheng Yan, Haoang Li
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=9c4MQah9Y4
- **中文提要：** 后训练在高层生成里已经有效，但在低层视觉中的作用仍少被探讨；现有图像复原常按像素拟合真实图像，容易过度平滑且泛化偏弱。
- **关键词：** GRPO, reward-model, post-training

### Irreducible Supervision Enables Compositional Generalization in Post-Training

- **作者：** Ellen Ma, Nikhil Anand
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=oQZ7gy7rrG
- **中文提要：** 可验证奖励的强化学习推动了大语言模型推理，但它是在创造新能力还是只打磨已有能力仍有争议，尤其当模型要把已学原语组合成新的多步函数时；讨论落在带类型的领域专用语言上的受控程序合成。
- **关键词：** GRPO, SFT, post-training, fine-tuning

### KV-PRM: Efficient Process Reward Modeling via KV-Cache Transfer for Multi-Agent Test-Time Scaling

- **作者：** Peng Kuang, Haibo Jin, Xiaoyu Han, Yanli Wang, Xiaopeng Yuan, Ye Yu, Kaidi Xu, Haohan Wang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=gdMVW6Iny8
- **中文提要：** 过程奖励模型能有效引导测试时扩展，从而提升基于大语言模型的多智能体系统；现有过程奖励模型却是文本式的，会把整条轨迹从头重新编码。
- **关键词：** PRM, reward-model

### Latency-Conditioned Selection Bias in RLHF

- **作者：** PRAKUL S HIREMATH
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=xOXpq3oPYW
- **中文提要：** 异步部分展开用并行补全里先返回的样本加速 RLHF，但自回归生成耗时随词元数增长。
- **关键词：** RLHF

### LEAN: Library-Based Adaptation for Asynchronous, Federated Fine-Tuning

- **作者：** Erdong Hu, Yuxin Tang, Zhimin Ding, Christopher Jermaine
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=PRnblGnQBU
- **中文提要：** LEAN 考虑联邦设定下如何适应基础模型：本地数据来自不同分布，却仍要学到全局适应的模型，而且本地智能体会在算法无法控制的时刻异步加入或离开。
- **关键词：** LoRA, fine-tuning

### Learn from the Gap: Differential-Aware Advantage Pruning with Adaptive Rollout Sampling for GRPO

- **作者：** Jiahua Yang, Chuangchuang Wang, Zhiwei Yang, Xianpeng Zhang, Dongyu Chen, Xing Chen, Tianhuang Su, Haonan Lu, Quanlong Guan, Kai Tang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Kw9cIpaixY
- **中文提要：** GRPO 及其变体被用于策略优化，但按题做多次展开采样，并在各展开之间反复评估逐词元概率，计算开销很大。
- **关键词：** GRPO

### Learning Rate Matters: Vanilla LoRA May Suffice for LLM Fine-tuning

- **作者：** Yu-Ang Lee, Ching-Yun Ko, Pin-Yu Chen, Mi-Yen Yeh
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=wgXOJA1oIS
- **中文提要：** LoRA 是高效微调大语言模型的主流做法；在此之上，近期研究提出了不同的初始化策略和结构改动，并报告相对原版 LoRA 有所提升。
- **关键词：** instruction-following, LoRA, alignment, fine-tuning

### Learning What to Predict: Downstream-Guided Task Design for Continued Pretraining

- **作者：** Shuqi Ke, Giulia Fanti
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=n9Wa5CFzZ3
- **中文提要：** 持续预训练在固定自监督任务上优化，挑选却看下游表现，反馈因此很粗：从业者评估检查点、修改数据配比或目标后再重跑，单次预训练更新却收不到是否有助于目标能力的信号。
- **关键词：** continued-pretraining

### Learning Where It Matters: Geometric Anchoring for Robust Preference Alignment

- **作者：** Youngjae Cho, Jongsuk Kim, Ji-Hoon Kim
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Ockny0oU9m
- **中文提要：** 偏好优化通过拉大偏好回复与非偏好回复之间的间隔来对齐大语言模型，但仅靠基于间隔的损失，并不能检验每一对偏好信号是否足够局部稳定、值得用全力更新。
- **关键词：** instruction-following, preference-optimization, alignment

### Leveraging Psychophysical Attentional Distribution for Gaze-Augmented Reward Modeling

- **作者：** Chaeho Lee, Junyup Kim, Wansoo Kim, Young Min Jung, Sang Ho Lee
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=FYcuG9h4hx
- **中文提要：** 把人类反馈纳入语言模型时，RLHF 是偏好对齐的常见框架；近期研究进一步把眼动数据当作奖励模型的额外监督，使奖励学习依托人类阅读过程。
- **关键词：** RLHF, reward-model, alignment

### Listwise Policy Optimization: Group-based RLVR as Target-Projection on the LLM Response Simplex

- **作者：** Yun Qu, Qi Wang, Yixiu Mao, Heming Zou, Yuhang Jiang, Yingyue Li, Wutong Xu, Lizhou Cai, Weijie Liu, Clive Bai, Kai Yang, Yangkun Chen, Saiyong Yang, Xiangyang Ji
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=JUzdxqEbBC
- **中文提要：** 可验证奖励的强化学习已成为大语言模型后训练中激励推理的常规路线，其中按提示采样一组回复、再用组内相对优势更新策略的做法很普遍。
- **关键词：** RLVR, post-training

### Live Music Diffusion Models: Efficient Fine-Tuning and Post-Training of Interactive Diffusion Music Generators

- **作者：** Zachary Novack, Stephen Brade, Haven Kim, Hugo Flores, Nithya Shikarpur, Chinmay Talegaonkar, Julian McAuley, Taylor Berg-Kirkpatrick, Anna Huang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=URFsYfMwTM
- **中文提要：** 交互式流式音乐生成希望把生成模型用于离线模型做不到的现场演出与共创，但当前先进模型处于离散自回归设定，训练和推理的算力需求都很高。
- **关键词：** reward-model, post-training, alignment, fine-tuning

### LLM Alignment--Utility Asymmetry under Semantic-Preserving Transformations

- **作者：** Mohan Li, Chengyu Yu, Francesco Sovrano, Marc Langheinrich, Martin Gjoreski
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=oD12yQB5qg
- **中文提要：** 对齐意在让大语言模型保持有用与安全，但其在输入分布偏移下是否稳定尚不清楚；已有现象显示越狱提示、替代编码和跨语言迁移下对齐会失效，这些情形却多被当成攻击，而不是对齐泛化的受控探针。
- **关键词：** alignment, fine-tuning

### Look Before You Leap: Self-Evolving Clinical Reasoning with Psychometric Preference Optimization for Radiology Report Generation

- **作者：** Qi Wang, Yunfeng Min, Liwei Huang, Zeyu Zhang, Di Gai, Jun Liu
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=GmZxHeBKTq
- **中文提要：** 视觉语言模型在放射报告生成上进展明显，现有黑盒自回归生成却缺少中间的临床逻辑推理，容易写出语言流畅但诊断有误的报告，形成看似合理的幻觉并削弱临床可靠性。
- **关键词：** preference-optimization

### LoRASpace: A Pool-Wide Shared Substrate for Static and Dynamic Multi-LoRA Composition

- **作者：** Thamirawaran Sathiyalogeswaran, Navindu De Silva, Chamikara Siriwardane, W K Alwis, Jason Mars, Udaya S Thanthrige, Ranga Rodrigo
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=edpJ8ipgAp
- **中文提要：** LoRA 把小型低秩矩阵接到冻结主干上，公开仓库里同一主干常挂着面向不同概念、角色、风格或任务的多个适配器；用户常想在一次生成中组合若干 LoRA，现有策略之间却要互相取舍。
- **关键词：** LoRA

### LoRAtorio: An intrinsic approach to LoRA Skill Composition

- **作者：** Niki Foteinopoulou, Ignas Budvytis, Stephan Liwicki
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=MrZTwGqEdZ
- **中文提要：** 在文生图扩散模型中，LoRA 被用来个性化角色、风格和物体等视觉概念，但现有方法难以有效组合多个适配器，尤其当所需技能的数量和性质事先未知时。
- **关键词：** LoRA

### Low-Rank Adaptation for Critic Learning in Off-Policy Reinforcement Learning

- **作者：** Yuan Zhuang, Yuexin Bian, Sihong He, Jie Feng, Qing Su, Songyang Han, Jonathan Petit, Shihao Ji, Yuanyuan Shi, Fei Miao
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=c9yifwVOw7
- **中文提要：** 扩大评论家容量被视为加强离策略强化学习的一条途径，然而更大的评论家在基于回放缓冲区的自举训练中容易过拟合且不稳定。
- **关键词：** LoRA

### LucidNFT: LR-Anchored Multi-Reward Preference Optimization for Flow-Based Real-World Super-Resolution

- **作者：** Song Fei, Tian Ye, Sixiang Chen, Zhaohu Xing, Jianyu Lai, Lei Zhu
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=W1dvS9O0dJ
- **中文提要：** 生成式真实场景超分能从严重退化的低分辨率输入合成看起来可信的细节，随机采样却难以避免一种失败：结果虽锐利但不忠于低分辨率证据，出现语义或结构幻觉；基于偏好的强化学习被视为贴合这一设定的方向。
- **关键词：** RFT, preference-optimization, alignment, fine-tuning

### Making LoRA Identifiable: Orthogonal Alignment for Continual Learning

- **作者：** Pratik Rakesh Singh, Mohammadi Zaki, Akash Saha, Aneesh Mukkamala, Pankaj Wasnik
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=6IGj3mpXfp
- **中文提要：** 把 PEFT 用于持续学习，是为了加快训练、减轻灾难性遗忘并更好适应新任务；已有策略包括为每个新到来的任务扩展 LoRA 分支，以及在各任务专用 LoRA 模块上按正交损失训练。
- **关键词：** LoRA, PEFT, alignment, fine-tuning

### Manifold Drift in Flow Preference Optimization: A Root Cause of Reward Hacking

- **作者：** Yansen Han, Shengyi Liao, Yuanxing Zhang, Pengfei Wan, Tao Lin
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=9dO9vJ1V5d
- **中文提要：** 偏好优化是生成模型的常规对齐方法，扩展到连续时间动力学却并不直接；流匹配中，奖励驱动的更新会改变传输轨迹，却缺少把样本约束在预训练数据流形上的内在机制，生成的终点样本常被推离预训练支撑。
- **关键词：** preference-optimization, alignment, fine-tuning

### MaPP: A Unified Marginalized Posterior-Predictive Framework for Data-Efficient RLVR

- **作者：** YangYang Ren, Haodong Zhu, Sheng Xu, Yanjing Li, Nikolai Y Zolotykh, Wentao Zhang, Baochang Zhang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=JPWppGw2ut
- **中文提要：** 可验证奖励强化学习能增强大语言模型的推理，代价是展开过程计算很重且策略更新频繁；为提高训练效率而广泛采用的在线提示选择，会为每条提示维护贝叶斯后验来预测难度。
- **关键词：** GRPO, RLVR

### MaPPO: Maximum a Posteriori Preference Optimization with Prior Knowledge

- **作者：** Guangchen Lan, Sipeng Zhang, Tianle Wang, Yuwei Zhang, Xinpeng Wei, Daoan Zhang, Xiaoman Pan, Hongming Zhang, Dong-Jun Han, Christopher Brinton
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=q5WDC6dLm9
- **中文提要：** 偏好优化已成为让大语言模型对齐人类偏好并提升表现的核心途径；MaPPO 以最大后验方式从偏好中学习，并把先验奖励知识明确纳入优化目标。
- **关键词：** DPO, SimPO, preference-optimization, alignment

### Margin Dynamics for Large Language Model Alignment

- **作者：** Xingzi Xu, Saygin Seyfioglu, Karim Bouyarmane
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=aW6PxjyzuB
- **中文提要：** 从业者挑选大语言模型对齐方法多靠试错；该工作给出一种理论刻画：每种成对方法在概率单纯形上定义一个向量场，决定模型如何在偏好与非偏好补全之间重新分配概率质量。
- **关键词：** DPO, SimPO, alignment

### Mask-Conditioned Gradient Masking for Fine-Tuning Mixture-of-Experts Diffusion Language Models

- **作者：** Yiru Tang, Kun Zhou, Xin Zhao, Jing Sha, Zhichao Sheng, Shijin Wang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=8s9FEa3MGT
- **中文提要：** 离散扩散语言模型因并行解码和双向上下文建模，成为自回归模型之外的一条路线；为提高可扩展性与效率，近期工作把混合专家架构接进这一框架。
- **关键词：** fine-tuning

### Mechanistic Insights into LoRA: Layer Sparsity for Adaptive Fine-Tuning via Path Patching

- **作者：** Fei Zuo, Yizhou Huang, Kezhi Wang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=DUiOU1Wsi4
- **中文提要：** LoRA 已成为大语言模型参数高效微调的主导范式，现有方法却在所有 Transformer 层上均匀施加适应，忽略了不同组件贡献并不相同。
- **关键词：** LoRA, PEFT, fine-tuning

### Memorize Theorems, Not Instances: Probing SFT Generalization through Mathematical Reasoning

- **作者：** Ruiying Peng, Mengyu Yang, Jing Lei, Xiao-Hui Li, Xueyu Wu, Xinlei Chen
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=qG2690UFsJ
- **中文提要：** SFT 广泛用于任务适配，近期工作却表明它会系统性地损害推理泛化；作者认为根因不是记忆本身，而是记忆对象：原版 SFT 驱使模型利用并记住题目与解答对中的表面伪相关，因而经不起表层输入变化。
- **关键词：** SFT, fine-tuning

### Memory-Efficient Federated Fine-Tuning of LLMs via Block-wise Progressive Training

- **作者：** Qianyue Cao, Zongwei Zhu, Boyu Li, Yi Xiong, Zirui Lian, Xuehai Zhou
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=mVZvgjYadQ
- **中文提要：** 联邦微调已成为隐私保护下适配大语言模型的主流；引入 PEFT 能降低通信和计算成本，现有方法却忽略了在冻结模型上做完整前向所造成的峰值显存瓶颈。
- **关键词：** PEFT, fine-tuning

### Merging RLVR-Trained Experts via Policy-Shift-Guided Spectral Alignment

- **作者：** Geeho Kim, MINSIK CHOI, Kyle Min, Young Geun Kim, Bohyung Han
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=syr1SgeqUD
- **中文提要：** PSA 是一种免再训练的合并方法，用词元级的专家相对基座策略偏移来引导谱子空间选择，从而合并经过 RLVR 后训练的语言模型专家；作者先表明，面向 SFT 的合并技术难以保住 RLVR 专家相对预训练基座那种稀疏且有方向的下一词元概率变化。
- **关键词：** RLVR, SFT, post-training, alignment

### Meta-Learning Preferences for Multilingual LLM Alignment

- **作者：** Jiaying Lin, Seongho Son, Nam P Tran, Long Tran-Thanh, Ilija Bogunovic, Debmalya Mandal
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=1pi7vaFHU1
- **中文提要：** 各语言人类偏好数据多寡不均，使多语言环境下的大语言模型对齐变得困难；针对低资源语言对齐数据不足，作者提出一套面向 RLHF 与 DPO 的元学习框架。
- **关键词：** DPO, RLHF, preference-optimization, reward-model, alignment

### META-PAP: Meta-learning for Prompt-aware Preference Pairing in LLM Alignment

- **作者：** Pinlong Zhao, Shiyu Hu, Jing Zhang, Mengyang Li
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=yiQav1vmSS
- **中文提要：** DPO 是让大语言模型对齐人类偏好的常用路径，现有流程却对所有偏好对一视同仁，忽略提示层面的异质性；最优配对策略会随提示特征系统变化，奖励分布集中的提示更受益于奖励差距大的配对。
- **关键词：** DPO, preference-optimization, alignment

### Mission Impossible: Diagnosing and Fixing Non-Operative Instruction Following in Image Editing

- **作者：** Guoyizhe Wei, Feng Wang, Alan Yuille, Rama Chellappa
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=iOwBRaRA9N
- **中文提要：** 指令引导的图像编辑模型大多在可执行请求上训练和评估，真实用户指令对给定图像却常常不可操作；可靠编辑因此既要推理如何修改，也要判断是否该改、该忽略什么。
- **关键词：** instruction-following

### MMCompass: Diagnosing Position Bias in Generative Multimodal Reward Models

- **作者：** Hongbo Zhao, Mingkun Yang, Yantao Liu, Yichang Zhang, Fei Huang, Zhibo Yang, Dayiheng Liu, Shuai Bai
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=kD0UhoI24Y
- **中文提要：** 生成式多模态奖励模型越来越多地用于排序回复、引导对齐并充当自动评判，可靠性成为核心问题；现有多模态奖励基准在标注严谨性、领域覆盖、回复模型多样性以及面向稳健性的评估上仍然有限，难以在真实且带诊断性的设定下衡量这些模型。
- **关键词：** SFT, reward-model, alignment, fine-tuning

### Modality-Depth Routing for Visual Reasoning in VLM Post-Training

- **作者：** Yiming Ren, Yiran Xu, Chufan Shi, Yu Qiao, junjie wang, Yujiu Yang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=hgFPtpO7uw
- **中文提要：** 加强视觉语言模型视觉推理的通行做法，是建造昂贵的思维链语料或精心编排的逐步理由，进展因而集中在资源充足的工业实验室；作者追问，通用视觉指令数据里已有的推理信号，能否通过改变后训练接口本身的结构来释放。
- **关键词：** SFT, post-training, alignment, fine-tuning

### Mode-Controlled Policy Optimization: A Geometry-Aware Recipe for LLM Post-Training

- **作者：** Zhenyu Sun, Dylan Hadfield-Menell, Weiguo Feng, Xiaohuan Zhou, Yi Zeng
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=fiTUEWZmk0
- **中文提要：** 大语言模型后训练通常被看成优化器的选择，KL 正则的强化学习还隐含一种几何选择：用反向 KL 把学到的策略拟合到奖励倾斜的目标；这使 PPO、GRPO、RLOO、REINFORCE++ 及相关方法处在更宽设计空间中一个固定的寻模位置。
- **关键词：** GRPO, post-training

### Model Spec Midtraining: Improving How Alignment Training Generalizes

- **作者：** Chloe Li, Sara Price, Samuel Marks, Jonathan Kutasov
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=o4qobfTwOz
- **中文提要：** 一些前沿开发者希望按描述预期行为的模型规范或宪章来对齐语言模型；标准对齐微调只在符合规范的示范上训练，可能得到泛化较差的浅层对齐，部分原因是示范数据对期望的泛化说明不足。
- **关键词：** mid-training, alignment, fine-tuning

### Modulating Merging Strengths via Joint Loss Estimation for LoRA-based Continual Learning

- **作者：** Kun Gu, De Cheng, Zhipeng Xu, Lingfeng He, Di Xu, Nannan Wang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=zRXaWRbyGH
- **中文提要：** 持续学习希望模型适应新任务的同时保留已学知识；作为代表性 PEFT 方法的 LoRA，因其效率与可扩展性在持续学习中受到更多关注。
- **关键词：** LoRA, PEFT, fine-tuning

### Mult-DPO: Multinomial Direct Preference Optimization for Recommender Systems

- **作者：** Yaochen Zhu, Harald Steck, James McInerney, Aditya Sinha, Yinhan He, Nathan Kallus, Jundong Li
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=pPtVAJIWRY
- **中文提要：** DPO 依据两个候选之间的成对偏好来对齐大语言模型，做法简单；推荐系统中的用户反馈却很少是成对的。
- **关键词：** DPO, preference-optimization, reward-model, alignment

### MultiSTEVE-1s: A Model Zoo and Interpretability Suite for Instruction-Following Vision Agents

- **作者：** Karolis Jucys, George Adamopoulos, Özgür Şimşek
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=sR3tHXbQxm
- **中文提要：** OpenAI 的 Minecraft 智能体 VPT 曾出现目标误泛化，把站在树叶下的村民当成树并杀死；该智能体虽已公开、便于白盒可解释性研究，大语言模型之外却很少有开源权重的失对齐模型生物。
- **关键词：** instruction-following, fine-tuning

### MURPHY: Feedback-Aware GRPO with Retrospective Credit Assignment for Multi-Turn Code Generation

- **作者：** Chanakya Ekbote, Vijay Lingam, Sujay Sanghavi, Luke Huan, Behrooz O Tehrani, Anoop Deoras, Stefano Soatto
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Ym3Smk7mfy
- **中文提要：** 可验证奖励强化学习已成为推理任务后训练的常规配方，GRPO 是其中的主要方法；GRPO 及其变体本质上是单轮的，只在孤立的提示与回复对上优化终局奖励，难以适应模型反复修正解答的智能体场景。
- **关键词：** GRPO, RLVR, post-training

### Navigating by Old Maps: The Pitfalls of Static Mechanistic Localization in LLM Post-Training

- **作者：** Hang Chen, Jiaying Zhu, Hongyang Chen, Hongxu Liu, Xinyu Yang, Wenya Wang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=mpKLCN943S
- **中文提要：** “先定位再更新”已成为大语言模型后训练的主导范式，借助机制可解释性找出关键组件再做针对性参数更新；它依赖一个尚未验证的前提：从当前静态参数得到的机制，能否可靠指导此后的动态参数更新。
- **关键词：** SFT, post-training, fine-tuning

### Neglected Free Lunch from Post-training: Progress Advantage for LLM Agents

- **作者：** Changdae Oh, Wendi Li, Seongheon Park, Samuel (Min-Hsuan) Yeh, Tanwi Mallick, Sharon Li
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Nd0oMzLk1y
- **中文提要：** 过程奖励模型能对大语言模型做细粒度的步骤级评估，但在智能体场景中很难构建：长程交互、不可逆动作和随机环境反馈，使人工标注与蒙特卡洛估计都难以规模化；作者指出，强化学习后训练本身已经提供了所需成分。
- **关键词：** PRM, reward-model, post-training

### No Model Required: Text Entropy Rate Filtering Prevents Iterative Fine-Tuning Collapse

- **作者：** Lewis Mitchell
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=1rTomFsjg0
- **中文提要：** 迭代微调中输出多样性会收窄，稀有模式逐渐丢失；现有缓解要么需要模型对数概率或外部先知，要么持续使用真实人类数据。
- **关键词：** QLoRA, fine-tuning

### Not Every Rubric Teaches Equally: Policy-Aware Rubric Rewards for RLVR

- **作者：** Utkarsh Tyagi, Xingang Guo, MohammadHossein Rezaei, Daniel George, Anas Mahmoud, Jackson Lee, Bing Liu, Yunzhong He
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=2itEcLBhzr
- **中文提要：** 当正确性能被自动核验时，可验证奖励的强化学习让后训练变得有效，但许多有用行为要同时满足多项定性标准，而不是单一验证器；基于量规的奖励把 RLVR 扩展到这类开放领域，按提示相关的标准打分再聚合成标量奖励。
- **关键词：** GRPO, RLVR, post-training

### Not Only Where, But When: Temporal Scheduling for RLVR

- **作者：** Jinghao Zhang, Ruilin Li, Feng Zhao, Jiaqi Wang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=kLm5BZHcSw
- **中文提要：** 可验证奖励强化学习已成为大语言模型后训练的核心技术；策略优化在全局广播的标量奖励下由全部采样词元驱动，轨迹上并不相同的策略行为却很少被区分。
- **关键词：** RLVR, post-training

### NP-LoRA: Null Space Projection for Subject-Style LoRA Fusion

- **作者：** Chuheng Chen, Xiaofei Zhou, Geyuan Zhang, Yong Huang, Gang Xiong
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=7ruWsRZRGX
- **中文提要：** LoRA 融合使主体与风格表示可以不经再训练就组合起来，用于可控生成；现有方法主要在权重层面合并，并没有显式刻画各自独立训练的 LoRA 在共享参数空间中如何相互作用。
- **关键词：** LoRA

### One Algorithm, Two Goals: Dual Scoring for Parameter and Data Selection in LLM Fine-Tuning

- **作者：** Xinrui Chen, Liu Yang, Ou Wu
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=rkcG6vtYfa
- **中文提要：** 大语言模型微调中，参数选择和数据选择都常用来降低成本，却通常各用一套打分机制；当参数掩码与数据子集共同决定受限微调时，这种分离既带来重复开销，也使协同选择变难。
- **关键词：** fine-tuning

### Online Data Selection for Instruction Tuning via Gaussian Processes

- **作者：** Jun Wang, Quoc Phong Nguyen, Julien Monteil, Vu Nguyen
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=5Z8GeMizku
- **中文提要：** 大语言模型预训练与微调的重点从数据量转向数据质量后，高质量数据选择成为关键课题；现有在线数据选择通常受批次约束，优化只限于随机批次内的局部效用。
- **关键词：** instruction-tuning, fine-tuning

### On the Construction and Implications of Low-Loss Valleys in LoRA-based Bayesian Inference

- **作者：** Daniel Dold, Emanuel Sommer, Julius Kobialka, Oliver Dürr, David Rügamer
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ZzGCahbGHm
- **中文提要：** LoRA 等参数高效微调已是大语言模型的常规手段，有原则地估计认知不确定性仍然困难；LoRA 设定下的近期结果表明，深度集成这类离散多模态方法相对单模态方法收益有限。
- **关键词：** LoRA, PEFT, fine-tuning

### On the Primacy Bias in RLVR Training

- **作者：** Nguyen Phuc, Ngoc-Hieu Nguyen, Parshin Shojaee, Chinh D La, Duy M. H. Nguyen, Rui Zhang, Khoa D Doan, Ting Hua, Nitesh Chawla
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=iYqWuTaHph
- **中文提要：** 可验证奖励强化学习被用来增强大语言模型的推理能力，但它能否把推理扩展到基座模型已经编码的范围之外，仍然不清楚。
- **关键词：** RLVR

### On the Sparsity of Direct Preference Optimization: Weight Disentanglement in the NTK Regime

- **作者：** Kensuke Sasaki, Issei Sato
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=dIhTYcLqCB
- **中文提要：** DPO 已被广泛用于让语言模型对齐人类偏好；近期经验工作发现它引起的参数更新非常稀疏，这一现象却还没有理论解释。
- **关键词：** DPO, RLHF, SFT, preference-optimization, alignment, fine-tuning

### Overcoming Catastrophic Forgetting in Visual Continual Learning with Reinforcement Fine-Tuning

- **作者：** Meng Lou, Hanzhong Guo, Linwei Chen, Yizhou Yu
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=XQ0Bir2SLj
- **中文提要：** 带可验证奖励的强化微调被用来激发多模态大语言模型的推理能力；近期研究还认为，以 GRPO 为例的强化微调相对 SFT 更能抵抗灾难性遗忘。
- **关键词：** GRPO, RFT, SFT, fine-tuning

### PACZero: PAC-Private Fine-Tuning of Language Models via Sign Quantization

- **作者：** Murat Bilgehan Ertan, Xiaochen Zhu, Ha Nguyen, Marten van Dijk, Srinivas Devadas
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=nn9uSJJgXG
- **中文提要：** PACZero 是一族用于微调大语言模型的 PAC 隐私零阶机制，把成员推断攻击的后验成功率约束在先验水平，并讨论差分隐私框架要达到同等抗攻击程度所需的条件。
- **关键词：** LoRA, fine-tuning

### PAIR: Prefix-Aware Internal Reward Model for Multi-Turn Agent Optimization

- **作者：** Wonjoong Kim, Yeonjun In, Sangwu Park, Dongha Lee, Chanyoung Park
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=0Ut88MX4Oj
- **中文提要：** 执行复杂的多阶段任务仍是当前大语言模型的明显障碍；GRPO 正成为主要选择，但它依赖稀疏的结果奖励，严重限制了中间步骤上的信用分配。
- **关键词：** GRPO, reward-model

### PaLoRA: Paced Low-Rank Adaptation for Continual Learning

- **作者：** Yuxuan Li, Fanhu Zeng, Hao Tang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=fU1XY23snF
- **中文提要：** 基于 LoRA 的持续学习用多种机制减轻灾难性遗忘，同时又几乎都把很小的学习率当作启发式来限制梯度缩放幅度；这种固定启发式缺少理论指导，说明不了限制强度应如何随任务累积而变化。
- **关键词：** LoRA

### Parameter Exploration for RLVR via Variational Learning

- **作者：** Vatsal Venkatkrishna, Nico Carlsen Daheim, Iryna Gurevych
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=p3hX7ae4x4
- **中文提要：** 探索长期是强化学习研究的重点；近来越来越多的证据表明，在大语言模型强化学习过程中鼓励探索，可以改善下游表现。
- **关键词：** GRPO, RLVR

### Pareto Preference Optimization for Structure- and Stability-Aware RNA Inverse Folding

- **作者：** Minghao Sun, Hanqun Cao, Zhou Zhang, Chen Wei, Liang Wang, Tianrui Jia, ZHIYUAN LIU, Tianfan Fu, Robert Tang, Yejin Choi, Pheng-Ann Heng, Fang Wu, Yang Zhang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ZEneX95jqf
- **中文提要：** RNA 逆折叠寻找在生理条件下能稳定折叠到目标三维骨架的序列；在 RNA 上做多目标偏好优化并不稳定，原因包括物理代理之间的噪声并不一致，涵盖确定性二维折叠、随机三维预测和最小自由能，以及序列与结构的简并会经由 GC 组成打开奖励投机的口子。
- **关键词：** DPO, preference-optimization

### ParetoSlider: Diffusion Models Post-Training for Continuous Reward Control

- **作者：** Shelly Golan, Michael Finkelson, Ariel Bereslavsky, Yotam Nitzan, Or Patashnik
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=FikEkhzT3F
- **中文提要：** 强化学习后训练已成为让生成模型对齐人类偏好的标准做法，多数方法却依赖单一标量奖励；当多个准则同时重要时，通行的提前标量化会把各项奖励压成固定的加权和。
- **关键词：** post-training, alignment

### Personalized LLM Alignment Should Be Counterfactually Verifiable

- **作者：** Cristina Garbacea
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=xL6LwLxBk2
- **中文提要：** 个性化把大语言模型对齐的目标从群体级奖励转到依用户条件化的策略；这篇立场论文主张个性化模型必须可反事实验证，即按需回答关于其推断用户表征的归因、必要性与充分性，否则行为评估难以可靠进行。
- **关键词：** alignment

### Personalized Safety in Federated Fine-Tuning of Large Language Models

- **作者：** Tianzhe Xiao, Gaozhuo Liu, Yichen Li, Haozhao Wang, Hanlin Cai, Ruixuan Li, Ozgur Akan
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=P1iPC9eKmI
- **中文提要：** 在隐私与监管约束下，机构内的后训练数据不能集中汇集，联邦学习因而成为协同适配大语言模型的自然途径。这会带来经典联邦学习和集中式对齐都没有覆盖的安全问题：客户端可能共享同一个模型。
- **关键词：** LoRA, post-training, alignment, fine-tuning

### PGSB: Pretrained-Guided Shared Basis for LoRA Model Merging

- **作者：** Muqing Liu, Chongjie Si, Zhuoya Liu, Yuheng Jia
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=RH9XxRniDK
- **中文提要：** 全量微调代价高，为各下游任务分别保存模型又费存储，而且得不到统一的多任务模型。LoRA 被当作模型合并的高效替代，每个任务适配都由它来表示。
- **关键词：** LoRA, fine-tuning

### PhaseLoRA: Control-Regime-Conditioned Low-Rank Adaptation for Continuous-Action Vision-Language-Action Policies

- **作者：** Yufei Guo, Yinan Wu, Haoran Duan, guiguang ding, Jungong Han
- **会议：** NeurIPS 2026 · Main · Oral
- **官方论文页：** https://openreview.net/forum?id=dZhUeQa53U
- **中文提要：** 用 PEFT 适配预训练的视觉-语言-动作策略时，常见适配器在整段控制过程中施加时间上不变的更新。连续动作操作会经历接近、接触过渡、抓取、搬运和放置等阶段，各阶段需要不同的调整。
- **关键词：** LoRA, PEFT, fine-tuning

### PM-LoRA: Scalable Continual Learning via Progressive Merging of Low Rank Adapters

- **作者：** Xiaobing Yu, Peijie Qiu, Jin Yang, Xiaoqi Zhao, XUANZHAO DONG, Wenhui Zhu, Xiwen Chen, Weiwei Ma, Xiaofeng Liu, Jiangpeng He
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=HL68qRLWDM
- **中文提要：** 持续学习中的参数高效微调多依赖任务专用的低秩适配器，逐步把预训练模型适配到新任务。适配器不断累积会使参数和显存线性增长，持续更新时也缺少显式保留已学知识的机制。
- **关键词：** LoRA, PEFT, fine-tuning

### PORT: Preference Optimization via Robust Token-Level Reweighting

- **作者：** Ding Zhu, Xiukun Wei, Tian Xie, Zhihui Zhu, Xueru Zhang, Mohammad Mahdi Khalili
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Z0gcomg5dI
- **中文提要：** 偏好优化已成为把大语言模型对齐到人类价值的主要途径，效果却高度依赖偏好标注的质量。实际中的偏好数据常因标注错误和歧义而带有噪声。
- **关键词：** preference-optimization, alignment

### Positive-Unlabeled Preference Optimization For Chest X-ray Report Generation

- **作者：** Yuta Kobayashi, Pradyun Ramesh, Muhammad Ahmed Chaudhry, Vincent Jeanselme, Judy Wawira, Sanmi Koyejo, Kathleen M Capaccione, Shalmali Joshi
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Aecnz8LJjt
- **中文提要：** 用于放射报告生成的视觉语言模型通常在回顾性临床报告上训练，而这些报告存在遗漏噪声：影像上实际存在的细微所见可能没有被写出来。例如成像申请聚焦于监护设备放置时，重症监护胸部 X 光报告可能漏写心影增大。
- **关键词：** DPO, preference-optimization

### PRECISE: SDE-Consistent Stochastic Sampling for RL Post-Training of Flow-Matching Models

- **作者：** Bo Peng, Tao Huang, Weijie Kong, Junzhe Li, Yue Wu, Qi Tian, Jiangfeng Xiong, Jian-Wei Zhang, Liefeng Bo, Zhao Zhong
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=GDousLQnYE
- **中文提要：** 强化学习已被用来改善扩散和流匹配生成器的提示对齐与感知质量。要把在线强化学习用到流匹配上，关键是把确定性采样轨迹变成随机策略，通常做法是用随机微分方程替换反向时间的常微分方程。
- **关键词：** post-training, alignment

### PreFT: Prefill-only finetuning for inference efficiency

- **作者：** Andrew Lanpouthakoun, Aryaman Arora, Zhengxuan Wu, Dhruv Pai, Benjamin Keigwin, Dan Jurafsky, Chris Potts
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ZbSJScTRJE
- **中文提要：** 参数高效微调已经能大规模个性化大语言模型，但服务用户专属的 PEFT 仍会损害吞吐，即便配合专门内核和显存管理也是如此。原因在于预填充一次处理大量词元，与解码逐个生成词元之间存在不匹配。
- **关键词：** SFT, LoRA, PEFT, fine-tuning

### PRISM: Principal Subspace Alignment for Parameter-Efficient Fine-Tuning

- **作者：** Anh Tong, Kyowoon Lee, Jaesik Choi
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=MCPaZwUbx2
- **中文提要：** 低秩适配一类 PEFT 方法已成为把大语言模型适配到下游任务的常用手段。现有做法往往在所有层上均匀施加低秩更新，忽略了 Transformer 结构中固有的层间耦合。
- **关键词：** LoRA, PEFT, alignment, fine-tuning

### Process-Aware LNS for Large-Scale MILP via Context-Enhanced Fine-Tuned LLM-driven Selector

- **作者：** An Yan, Huigen Ye, Hua Xu, Jiahao Zhang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=hXb3PI8MAB
- **中文提要：** 求解大规模混合整数线性规划对工业应用很关键，却因组合爆炸而难以处理。大邻域搜索成为应对这一规模的主要启发式，其效果完全取决于底层如何选择邻域。
- **关键词：** fine-tuning

### ProteinOPD: Towards Effective and Efficient Preference Alignment for Protein Design

- **作者：** Yulin Zhang, He CAO, Zihao Jiang, Chenyi Zi, Zhipeng Zhou, Zijing Liu, Yu Li, Jia Li, Ziqi Gao
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=JlG9kMWxYa
- **中文提要：** 按所需功能或性质设计蛋白质，是合成生物学、治疗开发和药物发现的核心目标。蛋白质语言模型已经能生成高度可设计的序列，偏好对齐则提供了一条把设计引向目标功能与性质的途径。
- **关键词：** preference-optimization, post-training, alignment

### Provably Efficient Regularized Online RLHF with Generalized Bilinear Preferences

- **作者：** Junghyun Lee, Minju Hong, Kwang-Sung Jun, Chulhee Yun, Se-Young Yun
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=c90ZvP0bAX
- **中文提要：** 这项研究考虑一般偏好与赌博机反馈下的在线 RLHF，目标是正则化的最优响应最大遗憾最小化。多种正则被用来让对齐更稳健，但已知的遗憾保证仍高度专属于 KL。
- **关键词：** RLHF, alignment

### Pushing Biomolecular Utility-Diversity Frontiers with Supergroup Relative Policy Optimization

- **作者：** Xinwu Ye, He CAO, Li Hao, Bin Feng, Zijing Liu, Robert Tang, Yu Li, Shenghua Gao
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=T7f7FXqdfT
- **中文提要：** 生物分子生成器常靠奖励反馈提升特定任务上的效用，只推效用却会把生成集中到很窄的一类候选。多样性是集合层面的性质，因此更难维持。
- **关键词：** GRPO, post-training

### Rank-Aware Differentially Private Release of Listwise Preferences for LLM Alignment

- **作者：** Junwei Chen, Manjiang Yu, Pengpeng Qiao, Yang Cao
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=D0Bw9TmdSJ
- **中文提要：** 列表式偏好比成对比较提供更丰富的对齐监督，完整排序也会暴露更多敏感的用户偏好。现有隐私保护对齐主要处理成对反馈，局部差分隐私下的列表式对齐仍未被探索。
- **关键词：** alignment

### RankE: End-to-End Post-Training for Discrete Text-to-Image Generation with Decoder Co-Evolution

- **作者：** Siyonng Jian, Siyuan Li, Luyuan Zhang, Zedong Wang, Xin Jin, Ying Li, Cheng Tan, Huan Wang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=JKAhKqd78L
- **中文提要：** 离散自回归文生图采用两阶段范式：VQ 分词器把图像映射成离散码，自回归策略再建模这些码的分布。现有后训练只优化自回归策略，并把 VQ 解码器保持冻结。
- **关键词：** preference-optimization, post-training, alignment

### RAVEN: Real-time Autoregressive Video Extrapolation with Consistency-model GRPO

- **作者：** Yanzuo Lu, Ronglai Zuo, Jiankang Deng
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=2TF93oa5z0
- **中文提要：** 因果自回归视频扩散模型从已生成内容外推后续片段，从而支持实时流式生成。从高保真双向教师蒸馏可以得到有竞争力的少步模型，但训练时遇到的历史分布与推理时出现的历史分布持续存在差距，因而限制长时程的生成质量。
- **关键词：** GRPO

### Reading the Finetuning Prior: Verbatim Content Recovery via Contrastive Decoding Diffing

- **作者：** Michał Brzozowski, Zuzanna Dubanowska, Enrico Cassano, Neo Christopher Chung
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=KCBzRH167k
- **中文提要：** 窄域微调的语言模型会逐字记住被植入的内容，但在接触不到权重和训练数据时，审计已部署模型究竟被教过什么仍是开放问题。近期工作表明基座与微调模型的激活差携带着可读的微调领域痕迹，当前先进的激活差透镜只能恢复出模糊的领域级信息。
- **关键词：** fine-tuning

### Read It Back: Pretrained MLLMs Are Zero-shot Reward Models for Text-to-Image Generation

- **作者：** Runhui Huang, Qihui Zhang, Zhe Liu, Yu Gao, Jie Wu, Hengshuang Zhao
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=60UfWy2Mx4
- **中文提要：** SpectraReward 是免训练的奖励函数，把预训练多模态大模型直接当作图像生成强化学习的现成奖励模型。它不让模型评判生成图或回答拆开的核验问题，而是通过单次图像条件过程衡量原提示能从生成图中被恢复到什么程度。
- **关键词：** reward-model, alignment, fine-tuning

### Rebellious Student: Reversing Teacher Signals for Reasoning Exploration with Self-Distilled RLVR

- **作者：** Jeonghye Kim, Jiwon Jeon, Dongsheng Li, Yuqing Yang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=fPPlV9ktuR
- **中文提要：** 自蒸馏后训练中，带额外信息的教师指导没有该信息的学生，二者来自同一个模型。这种指导在学生失败时有用，但在成功的采样轨迹上，同一机制会改写学生自己的选择并压制其推理。
- **关键词：** GRPO, RLVR, instruction-tuning, post-training

### Re-examining Low Rank adaptation for private LLM fine-tuning

- **作者：** Ali Dadsetan, Frank Rudzicz
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Phmae0oHes
- **中文提要：** 在敏感数据上微调大语言模型时，隐私是核心关切；差分隐私随机梯度下降通过对每个样本梯度裁剪并加入校准后的高斯噪声，成为给出形式化隐私保证的标准工具。理论与实践都表明更低秩的模型更适合差分隐私训练，这一点对大语言模型尤其相关。
- **关键词：** LoRA, fine-tuning

### Reinforce Adjoint Matching: Scaling RL Post-Training of Diffusion and Flow Models

- **作者：** Andreas Bergmeister, Stefanie Jegelka, Nikolas Nüsken, Carles Domingo i Enrich, Jakiw Pidstrigach
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=AoBtAENiPy
- **中文提要：** 扩散和流匹配模型能够扩展，是因为预训练只需要对解析加噪后的干净样本所构成的闭式目标做回归。许多场景里只有一个衡量生成是否合意的奖励函数，训练就必须从预训练模型出发在线进行。
- **关键词：** GRPO, post-training

### Reinforcement Learning with Verifiable Physics: Post-training LLMs for PDE Solver Generation

- **作者：** Pengfei Cai, Utkarsh Utkarsh, Alan Edelman, Christopher Rackauckas, Rafael Gomez-Bombarelli
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ZopflnQLAZ
- **中文提要：** 偏微分方程是科学与工程建模的基础，但构造可靠的数值求解器仍然费力，需要离散格式、稳定性条件和边界处理方面的专门知识。近期工作开始把求解写成大语言模型的代码生成任务，现有方法主要停留在某一层面。
- **关键词：** post-training

### Rethinking Contrastive Loss in CLIP Post-training: A Complementary Framework with Frozen Text Encoder

- **作者：** Zidan Wang, Yaqian Li, xiaokai zhang, Kun He, Kaiwen Long, Hanpeng Liu
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=tjKgJbAYn9
- **中文提要：** CLIP 是视觉语言基础模型，也是下游视觉语言模型常用的视觉编码器。后训练提供了一条较省资源的改进途径，但近期观点认为标准对比损失在小批量下会灾难性遗忘，因而不适合后训练，并推动人们放弃对比目标、改用蒸馏。
- **关键词：** post-training, alignment

### Rethinking LLM Fine-Tuning via Weight Space Reparameterization: Preserving Safety during Downstream Adaptation

- **作者：** Min-Seong Kim, Jongbok Won, Jeesup Park, Yonghee Choi, Dong-Jun Han
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=HssNfd9nbe
- **中文提要：** 在下游任务上微调大语言模型，常常削弱先前对齐好的安全行为，任务适配与安全保持之间存在固有权衡。已有方法试图在原始参数空间中找出与安全相关的神经元、层或更新方向来缓解这一问题。
- **关键词：** fine-tuning

### Rethinking LoRA Initialization for Robust Asymmetric Learning Rates

- **作者：** Disen Liao, Yaoliang Yu
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=BDO32ssOHO
- **中文提要：** LoRA 往往对学习率的选择非常敏感。近期经验研究表明，一旦学习率被仔细调好，普通 LoRA 仍能与许多提出的变体保持竞争力。
- **关键词：** LoRA, fine-tuning

### Rethinking Personalized Generation: Test-time Alignment via Factorized Ranking Models

- **作者：** Qiyao Ma, Junshan Zhang, Zhe Zhao
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=RFhvQqW3jD
- **中文提要：** 把大语言模型对齐到多样的用户偏好，受到标准对齐范式的根本限制，因为这些范式优化的是单一整体用户。通过经验研究，作者首先发现个性化生成经由测试时缩放仍有大量尚未利用的性能空间。
- **关键词：** reward-model, PEFT, alignment, fine-tuning

### Rethinking Post-Training Recipes for Multimodal Time-Series Forecasting

- **作者：** Haoxin Liu, Yichen Zhou, Rajat Sen, B. Aditya Prakash, Abhimanyu Das
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=IoZ46hsiwb
- **中文提要：** 时间序列基础模型擅长用数值数据做零样本单模态预测，却不像大语言模型那样能利用常常塑造真实轨迹的多模态、非数值上下文。作者主张后训练大语言模型，让它在强数值先验之上充当由上下文引导的修订器。
- **关键词：** RLVR, SFT, post-training, fine-tuning

### Rethinking Reward Models for Multi-Domain Test-Time Scaling

- **作者：** Dong Bok Lee, Seanie Lee, Sangwoo Park, Minki Kang, Jinheon Baek, Dongki Kim, Dominik Wagner, Jiongdao Jin, Heejun Lee, Tobias Bocklet, Jinyu Wang, Jingjing Fu, Sung Ju Hwang, Jiang Bian, Lei Song
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://neurips.cc/virtual/2026/poster/156790
- **中文提要：** 测试时缩放大语言模型的可靠性，常由外部验证器或奖励模型来区分正确推理与有缺陷的逻辑。先前工作既研究只评估最终答案的结果奖励模型，也研究为中间推理步骤打分的过程奖励模型。
- **关键词：** PRM, reward-model

### Rethinking "RL Generalizes, SFT Memorizes": The Role of SFT Data

- **作者：** Yunlong Hou, Fengzhuo Zhang, Yuan Cheng, Jiachun Pan, Xingyao Li, Zhuoran Yang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=sGr1f8yocs
- **中文提要：** 带可验证奖励的强化学习常被看作能带来强推理和广泛泛化，监督微调则更容易被看成偏向记忆、迁移有限。这项研究从 SFT 训练数据的角度重新审视这一区分。
- **关键词：** SFT, fine-tuning

### Rethinking Rubric Generation for Improving LLM Judge and Reward Modeling for Open-ended Tasks

- **作者：** William Shen, Xinchi Qiu, Chenxi Whitehouse, Lisa Alazraki, Shashwat Goel, Francesco Barbieri, Timon Willi, Akhil Mathur, Ilias Leontiadis
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=HY04Lr2rBq
- **中文提要：** 评分细则近来被用来引导大模型评判，以捕捉细致、多维的人类偏好，并进一步延伸为强化微调的奖励信号。开放式生成通常没有唯一的规范目标，其评价细则是潜在的，而不是被直接观察到的。
- **关键词：** RFT, reward-model, fine-tuning

### Rethinking Visual Reasoning in Text-to-Image Reward Modeling

- **作者：** Shiye Su, Xiaohan Wang, Ludwig Schmidt, Serena Yeung-Levy
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=NIlMvxosjw
- **中文提要：** 奖励模型是现代文生图系统的核心，既作为推理时筛选的目标，也用于基于强化学习的后训练。要判断提示遵循程度并落实审美偏好，奖励模型必须能绑定属性、理清关系并可靠地计数。
- **关键词：** reward-model, post-training, fine-tuning

### Reward Modeling for Multi-Agent Orchestration

- **作者：** King Yeung Tsang, Zihao Zhao, Vishal Venkataramani, Haizhou Shi, Zixuan Ke, Semih Yavuz, Shafiq Joty, Hao Wang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=9HnmEMnWjg
- **中文提要：** 建立在大语言模型上的多智能体系统需要有效编排来协调专用智能体，但训练这类编排器受限于监督不足和计算成本高。Orch-RM 是一个自监督框架，在没有人工标注的情况下评估编排质量。
- **关键词：** reward-model

### Riemannian Optimization for Low-Rank Adaptation via Desingularization

- **作者：** Tiancan Feng, Daorui Ding, Fanhua Shang, Xiaoyuan Zhang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=jiYYPiWmCI
- **中文提要：** LoRA 作为参数高效微调方法被广泛用于大语言模型。训练得到的适配器却常常稳定秩偏低，尾部奇异值也偏小。
- **关键词：** LoRA, PEFT, fine-tuning

### Robust and Efficient Finetuning of Vision Foundation Models via Implicit Ensembling

- **作者：** Masih Aminbeidokhti, Heitor Medeiros, Eric Granger, Marco Pedersoli
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=D3CvENdsfQ
- **中文提要：** 基础模型的稳健微调希望在分布内适配的同时改善分布外泛化。作者重新考察 Mixout 这一随机正则：它间歇地把已微调参数替换为参考锚点，并研究其对视觉基础模型稳健微调的效果。
- **关键词：** PEFT, fine-tuning

### RoSA: Rotational Sparse Adaptation for Memory-Efficient Fine-Tuning

- **作者：** Muhammad Azeem Lodhi, chao zhou, Rebekka Burkholz
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=QZlXiCc3kK
- **中文提要：** 参数高效微调把训练集中在一小部分参数上，从而降低适配基础模型的成本。RoSA（旋转稀疏适配）在此之上进一步把适配收窄到每次只更新一部分层。
- **关键词：** PEFT, fine-tuning

### Routing Subspaces: Auditing Evaluation-to-Deployment Mismatch in Fine-Tuned Language Models

- **作者：** Phongsakon Mark Konrad, Toygar Tanyel, Serkan Ayvaz
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Lsf8vcSdAI
- **中文提要：** 安全评测常假定测试中观察到的行为能代表日常使用，微调却可能打破这一假定。同一个检查点可以在评测式提示下看起来已经固定，而相同行为在日常使用提示下仍然存在。
- **关键词：** instruction-tuning, fine-tuning

### S2T-RLHF: Hierarchical Credit Assignment for Stable Preference-Based RLHF

- **作者：** Wei Chen, Guanghui Zhu, Yafei Li, Limin Wang, Yihua Huang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=s0T8MQbeRk
- **中文提要：** 带偏好奖励模型的 RLHF 常常训练不稳定。一个关键原因是标准做法只给整段序列一个标量奖励，再传播到词元级策略更新，回复内部的信用分配因而天然含糊。
- **关键词：** RLHF, preference-optimization, reward-model, alignment

### SAFTAC: Simulation-Augmented Fine-Tuning of Open-Source LLMs for Analog Circuit Design

- **作者：** Junsheng Huang, Yifan Sun, Zhuoer Zhang, Ning Wei, Yening Liu, Michael Molter, Pavan Kumar Hanumolu, Elyse Rosenbaum, Bin Hu, Huan Zhang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=8VwAj1accS
- **中文提要：** 模拟集成电路设计困难，是因为电路拓扑、器件尺寸和电路性能紧密耦合。现有基于大语言模型的方法，要么围着冻结模型做推理时修正，要么只在有限电路类型上训练，而且没有直接把仿真结果用作训练信号。
- **关键词：** RFT, SFT, fine-tuning

### Scalable Variational Bayesian Fine-Tuning of LLMs via Orthogonalized Low-Rank Adapters

- **作者：** Haotian Xiang, Bingcong Li, Qin Lu
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=q8fHjSdu4t
- **中文提要：** 把大语言模型部署到安全关键应用时，不确定性量化对于自行评估决策可靠性至关重要。这类决策却常常过度自信，尤其是在数据有限的下游领域任务上做完参数高效微调之后。
- **关键词：** LoRA, PEFT, fine-tuning

### Scaling Reward Modeling without Human Supervision

- **作者：** Jingxuan Fan, Yueying Li, Zhenting Qi, Dinghuai Zhang, Kianté Brantley, Sham Kakade, Hanlin Zhang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=yD1cdr9cGj
- **中文提要：** 从反馈中学习对提升前沿模型的能力与安全很关键，其效果却常受成本和可扩展性约束。这项初步研究探索通过无监督途径来扩展奖励模型。
- **关键词：** SFT, reward-model, mid-training, fine-tuning

### SCOPE-RL: Stable and Quantitative Control of Policy Entropy in RL Post-Training

- **作者：** Chen Wang, Zhaochun Li, Bai Jionghao, Hexuan Deng, Guanting Dong, Ge Lan, Yue Wang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Vt62uaRwMd
- **中文提要：** 强化学习是后训练大语言模型的关键范式，但常用的 GRPO 常出现熵崩溃：探索很快消失，策略过早收敛，样本多样性下降，最终损害训练效果。已有的熵奖励和基于裁剪的补救很少能把熵保持住。
- **关键词：** GRPO, post-training

### SD-LoRA: Training-Time Structural Distillation into LoRA for Few-Shot Vision-Language Adaptation

- **作者：** Mohammed Rahman Sherif Khan Mohammad, Ardhendu Behera, Sandip Pradhan, Swagat Kumar, Yonghuai Liu
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=NT2wZRLD58
- **中文提要：** 摘要从极少监督下学习细粒度视觉差别、并保留冻结类 CLIP 模型便于部署的效率说起。现有轻量适配，包括提示微调、LoRA 和基于缓存的适配器，通常只监督全局图像嵌入，因而利用不足。
- **关键词：** LoRA, alignment

### SDS-LoRA: Overcoming Anisotropic Gradient Scaling in Low-Rank Adaptation

- **作者：** JungHun Oh, Sungyong Baik, Kyoung Mu Lee
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=fQrxSvxZkd
- **中文提要：** LoRA 用低秩矩阵参数化权重更新，从而高效地把大型预训练模型适配到下游任务。作者从几何角度考察这种参数化的局限。
- **关键词：** LoRA, alignment, fine-tuning

### Self-Calibrated GUI Reward Model via Inverse Dynamic Modeling

- **作者：** Zeyi Sun, Shengyuan Ding, Xingpeng Xia, Jinsong Li, Xie Chen, Dahua Lin, Jiaqi Wang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=OPejG5R0IO
- **中文提要：** 打造能稳健执行长程任务的通用图形界面智能体仍是关键挑战。强化学习提供了一条有希望的改进路径，却严重受限于开放环境中缺少可靠奖励信号。
- **关键词：** reward-model

### Self-Distilled RLVR

- **作者：** Chenxu Yang, Chuanyu Qin, Qingyi Si, Minghui Chen, Naibin Gu, Dingyu Yao, Zheng Lin, Weiping Wang, Nan Duan, Jiaqi Wang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=TAt6jrbMb8
- **中文提要：** 同策略蒸馏已成为大语言模型社区常见的训练范式：它选一个更大的模型当教师，为每条采样轨迹提供稠密、细粒度信号。与之相对，可验证奖励的强化学习只能从环境中的可验证结果获得稀疏信号。
- **关键词：** RLVR

### Self-Recognition Finetuning can Reverse and Prevent Emergent Misalignment

- **作者：** Arush Tagade, Shaoheng Zhou, Jiaxin Wen, Shi Feng
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=59CXcl41Fa
- **中文提要：** 涌现失对齐被联系到失对齐人格向量和负面角色特质的激活，表明它更多是扰乱了模型已对齐的角色，而不是直接学会有害内容。受此推动，作者研究自生成文本识别微调，把它当作针对角色的干预。
- **关键词：** fine-tuning

### Seq-LoRA: Sequential Bayesian Low-Rank Adaptation for Large Language Models

- **作者：** Boming Chen, Xiaojing Wang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=I7N01JSe99
- **中文提要：** LoRA 能高效微调大语言模型，但适配后的模型常常过度自信，在低数据场景和分布偏移下尤其如此。现有考虑不确定性的方法通常在固定适配集合上构造静态后验，并不刻画局部后验证据如何随训练数据的结构化子集而变化。
- **关键词：** LoRA, fine-tuning

### SF-DST: Adapting Vision-Language Models for Anomaly Detection via Asymmetric Modulation and A-LoRA

- **作者：** Zhipeng Wang, Xiaofei Li, Dong Zhao, Yonghong Song
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Z55huSQY5L
- **中文提要：** 视觉语言模型在工业异常检测上很有潜力，却常因语义偏向而忽略细微的高频缺陷。单类适配还面临秩坍缩和灾难性遗忘的风险。
- **关键词：** LoRA

### SFT-then-RL Outperforms Mixed-Policy Methods for LLM Reasoning

- **作者：** Alexis Limozin, Eduard F Ďurech, Torsten Hoefler, Imanol Schlag, Valentina Pyatkin
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=pWkCETOQnA
- **中文提要：** 近期用于大语言模型推理的混合策略优化把监督信号与强化学习信号交错或混合，并报告其优于标准的先 SFT 再 RL 流程。作者指出不少新近论文依赖有缺陷的基线，其中一处是 DeepSpeed 把优化器卸载到 CPU 时会在梯度过程中静默丢掉中间微批次。
- **关键词：** SFT

### SLDR: Defending Against Malicious Fine-tuning via Selective Layers Recovery and Dynamic Routing

- **作者：** Hui Zhang, Yachao Yuan, Jiayun Wang, Yuanzhuo Li, Hongtao Wang, Yali Yuan
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=jjuXPhJpD0
- **中文提要：** 微调即服务让用户把已对齐的大语言模型适配到专门任务，恶意微调却可能在合法输入上保住任务表现的同时侵蚀拒绝行为。重审逐层安全诊断后可以发现，安全敏感性是带符号的：缩放不同层可能加强拒绝、削弱拒绝，或几乎没有影响。
- **关键词：** LoRA, fine-tuning

### SLIC: Reinforcement Fine-Tuning Small LMs for Multi-Turn Analog Circuit Optimization

- **作者：** Yan Xu, Zhengqi Gao, Ching-Yun Ko, Zhang-Wei Hong, Wenjie Lu, Tao Yu, Xin Zhang, Duane Boning, Ruonan Han
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=NwEmt4o0zc
- **中文提要：** 模拟集成电路设计是多轮、以仿真器为依据的工程任务，需要围绕相互耦合的性能权衡反复推理，而专有工艺设计套件使托管大语言模型流程难以在实际设计中部署。SLIC 是一个强化微调框架，用来训练可在本地运行的小语言模型。
- **关键词：** RFT, fine-tuning

### Smart Picks in the Dark: Towards Efficient RLVR for Reasoning via Tracing Metacognitive Pivots

- **作者：** Guangcheng Zhu, Shenzhi Yang, Haobo Wang, Xing Zheng, Yingfan Ma, Xuening Feng, Zhongqi Chen, Bowen Song, Weiqiang Wang, Gang Chen
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=f6NxXBLsMW
- **中文提要：** 可验证奖励强化学习大大推进了大推理模型，但需要在完全标注的数据上及时训练。数据选择方法试图找出一小部分“黄金”样本以接近全量数据的效果，却依赖事先存在的已标注样本池。
- **关键词：** RLVR

### SMoA: Spectrum Modulation Adapter for Parameter-Efficient Fine-Tuning

- **作者：** Yongkang Liu, Xing Li, Mengjie Zhao, Shanru Zhang, Zijing Wang, Qian Li, Shi Feng, Feiliang Ren, Daling Wang, Hinrich Schuetze
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=HtLt3XukFH
- **中文提要：** 随着参数数量增加，参数高效微调成为定制预训练大语言模型的常用选择。LoRA 用低秩更新模拟全参数微调，以降低资源需求。
- **关键词：** LoRA, PEFT, fine-tuning

### SoccerNarrate: Event-Grounded Streaming Soccer Commentary with Macro-Window Preference Alignment

- **作者：** zihan jia, Zhilin Dai, Zhengming Zhang, Min Yang, Zhenpeng Huang, Jiaqi Li, Caixia Sun, Xi Chen, Liang Li, Junlan Feng, Gangshan Wu, Limin Wang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=P9oiEDJVAl
- **中文提要：** 现有足球解说模型多面向预先切分的片段或局部事件。部署到未裁剪的整场视频并使用滑动窗口时，解说可能出现延迟、重复或与画面同步不佳。
- **关键词：** preference-optimization, alignment

### Solver-as-Teacher: Solver-Guided On-Policy Post-Training Framework for PDE Foundation Models

- **作者：** Hao Wei, Shangzhe Li, Nils Thuerey
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=afU6OolFcZ
- **中文提要：** 偏微分方程基础模型有望做通用的代理仿真，但把预训练模型部署到新的物理区间会带来分布不匹配，因而需要针对任务的后训练。主流的监督微调本质上是离策略的：模型在预先生成的状态上训练，评估时却要对自己的输出做自回归。
- **关键词：** SFT, post-training, alignment, fine-tuning

### SpatialFlow-GRPO: Where Spatial Credit Drives Image Editing

- **作者：** Yankai Yang, Yancheng Long, Wei Chen, Xingyu Lu, Hongyang Wei, Bin Wen, Fan Yang, Tingting Gao, Han Li, Shuo Yang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=vOr0WAaBeN
- **中文提要：** 近期的在线强化学习明显提升了图像编辑质量。现有 Flow-GRPO 风格的方法通常依赖单一的整图奖励，使细粒度编辑难以优化。
- **关键词：** GRPO, reward-model

### Specialist Mediators: Causal Localization of Dense Fine-Tuning

- **作者：** Amir Asiaee
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=xK0zRemqmT
- **中文提要：** 密集微调可以把基座语言模型变成领域专家，但任务准确率本身揭示不了哪些内部计算中介了新行为。作者提出专家中介：密集专家相对基座的提升，经由这些内部机制发生因果传递。
- **关键词：** LoRA, fine-tuning

### Spectral Rank Calibration for Continual LoRA Merging in Multimodal Large Language Models

- **作者：** Chenrui Wu, Haishuai Wang, Jiajun Bu, Jiangchuan Liu
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=mZ9hN3hGTn
- **中文提要：** 模型合并可以把具备不同能力的多个专家模型集成到一个统一模型中。实际部署里，新的专家模型往往会持续更新并不断到来。
- **关键词：** LoRA

### SPRING: Solver-guided Process Rewards for Novel Logical Reasoning Steps Generation

- **作者：** Muhammad Asif Ali, Mohammad Raza, Wenqing Wang, Huan wang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=jUAayjmSnv
- **中文提要：** 逻辑推理仍是大语言模型的主要挑战，尤其是需要精确跟踪约束、保持一致性并做多步演绎的结构化问题。这一困难对小规模模型更为突出，它们更容易产生不一致、冗余或脆弱的推理轨迹。
- **关键词：** PRM

### SPRM: From Cooperative Games to Marginal-Contribution Process Reward Modeling

- **作者：** Yu Bao, Pak Lon Ip, Qiyu Ruan, Xitong Gao, Cheng-Zhong Xu
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=o6rESNXJwW
- **中文提要：** 过程奖励模型能为推理提供步骤级反馈，但可靠的过程监督很难获得：人工标注昂贵，蒙特卡洛展开需要很大的采样预算，大模型评判还可能引入对提示敏感的偏差。SPRM 是只依赖结果的框架，直接从最终正确性信号构造过程奖励。
- **关键词：** PRM, reward-model

### SR-GRPO: Stable Rank as an Intrinsic Geometric Reward for Large Language Model Alignment

- **作者：** Yixuan Tang, Yi Yang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=eOONOlDp7u
- **中文提要：** 对齐大语言模型通常依赖外部监督，但人工标注稀缺且主观，奖励模型容易被钻空子，自评又受提示敏感和偏见影响。该工作提出稳定秩，作为一种从模型本身导出、无需标注的内在质量信号。
- **关键词：** GRPO, reward-model, alignment

### Stability Regimes for Framing-Sensitive Fine-Tuning in Language Models

- **作者：** Victor De Lima, Jiqun Liu, Grace H Yang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=mt2diEh4OH
- **中文提要：** 人工智能正在塑造人们获取和评判信息的方式，错误信息因而更受关注。微调后的大语言模型可以支撑智能体仿真，为直接实证之外提供受控的计算模拟。
- **关键词：** SFT, LoRA, fine-tuning

### Stabilizing Knowledge, Promoting Reasoning: Dual-Token Constraints for RLVR

- **作者：** Jiakang Wang, Runze Liu, Fuzheng Zhang, Xiu Li, Guorui Zhou, Kun Gai, Ling Pan
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=XzRoRbdbXp
- **中文提要：** 可验证奖励强化学习已成为提升大模型推理能力的后训练方法，现有做法却多对所有词元施加统一优化约束，忽略了词元之间角色并不相同。
- **关键词：** RLVR, post-training

### StainNFT: Curriculum-Gated Multi-Reward Post-Training for Pathology-Faithful Virtual Staining

- **作者：** shurong yang, Dong Wei, Qiong Peng, Xian Wu, Yefeng Zheng, Liansheng Wang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=8Ci5Hrd4ph
- **中文提要：** 免疫组化染色编码着对临床诊断至关重要的分子蛋白表达，化学流程却昂贵且耗时。虚拟染色提供另一条途径，从苏木精-伊红切片数字合成免疫组化图像。
- **关键词：** SFT, post-training, fine-tuning

### SteadyThought: Mitigating LLM Under-Thinking via Thought-Level Preference Optimization

- **作者：** Zhenyue Peng, Lin Yang, Jie Wang, Xiaoqi Ni, Hanzhu Chen, Xize Liang, Yanjun Wu, RujingWang, Kaiwen Zhou, Jianye Hao
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=xpPQq8hDSx
- **中文提要：** 在推理轨迹之间灵活切换，显著增强了大型推理模型的能力。现有模型却常常切换过多，维持不住有希望的推理思路，这一现象被称为思考不足。
- **关键词：** preference-optimization

### Steering Vectors as a Training Signal in LLM Post-Training

- **作者：** Tiejin Chen, Maunil R Vyas, Huaiyuan Yao, Hua Wei
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=jMVLPhJP73
- **中文提要：** 转向向量是残差流里的方向，推理时加到隐状态上就能改变大模型行为。以往主要把它当作事后控制，这里转而追问同一方向能否在后训练中引导参数更新。
- **关键词：** GRPO, RLVR, SFT, post-training

### Strong Post-Training from Permissive, Reasoning-Dominant, Web-Scale Pretraining

- **作者：** Harsh Raj, Ali Elganzory, Marianna Nezhurina, Victor May, Van Khue Nguyen, David Salinas, Huu Nguyen, Jenia Jitsev
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=MUnBsYNzes
- **中文提要：** 可审计的宽松预训练语料有助于合法、负责且透明的开放基座模型研发，并推动标准化与共同进展。MixtureVitae 等近期工作表明这类语料也能得到很有竞争力的基座模型，但尚无受控比较检验后训练之后是否仍然有竞争力。
- **关键词：** DPO, SFT, instruction-following, preference-optimization, post-training, fine-tuning

### Subliminal Learning as Trait-Direction Drift: A Mechanism and Targeted Control under SFT Distillation

- **作者：** Zhixuan Liu, Zhichen Dong, Yuyu Fan, Xiangtian Li, Chao Yang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=B3eilxnBkK
- **中文提要：** 模型蒸馏除了传递预期能力，也可能把教师的隐藏特质传给下游学生。被系统提示偏置的教师即使生成语义干净的数据，例如数字序列，学生仍可能继承那种隐藏偏好，这一现象称为潜隐学习。
- **关键词：** SFT, fine-tuning

### Surprise, Episodic Context, and Catastrophic Forgetting in LLM Fine-Tuning: An Empirical Study

- **作者：** Zied Ben Houidi, Alexis Huet, Alberto Eusebio, Francesco Mantovani, Dario Rossi
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=gsvP7j7bLZ
- **中文提要：** 惊讶与情景上下文被认为支配动物如何更新记忆，并影响先前知识能否留下。受此启发，一项实证研究考察监督微调中，惊讶和上下文怎样影响大语言模型的知识保持。
- **关键词：** SFT, post-training, fine-tuning

### TailGuard: Subgroup Tail Coverage Theory for Safe LLM Alignment

- **作者：** Charles Cao
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ml3suoaUwg
- **中文提要：** 大模型的安全偏好对齐必须处理稀有有害尾部，其负担集中在人口、话题、语言或对抗性子群上。现有覆盖分析看的是全局密度比，平均值显得充足时，小群体的有害尾部仍可能没有支撑，最差群体的安全风险也就识别不出来。
- **关键词：** preference-optimization, alignment

### Tcell: Mitigating Harmful Fine-tuning for Large Language Models via Gradient Alignment

- **作者：** Tiansheng Huang, Virat Vishnu Shejwalkar, Oscar Chang, Ling Liu
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=3Rc9uH2uQ1
- **中文提要：** 有害微调威胁着主流的微调即服务：攻击者可向接口提交有害数据，破坏大模型已有的安全对齐。作者先考察一种直观的梯度混合，并导出防御得以成立的关键性质，即采用余弦相似度更高的微调更新。
- **关键词：** alignment, fine-tuning

### Temporal Concentration from Rollout Errors: Implicit Preference Optimization For Text-to-Video Diffusion

- **作者：** henglin liu, Fangyuan Kong, Jing Wang, Yizhou Lin, Nisha Huang, Chang Liu, Xintao Wang, Pengfei Wan, Kun Gai, Xiu Li
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=BPEHExx6a0
- **中文提要：** 扩散式视频生成中的偏好对齐，尤其是 DPO，已经明显提升画面质量。运动塌缩、物体闪烁和色彩过饱和这类时间上稀疏的瑕疵，仍是感知真实感的主要障碍。
- **关键词：** DPO, preference-optimization, reward-model, post-training, alignment

### The Alignment Tax Concentrates in Output Projections

- **作者：** Ming Liu
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Rj4yyW4GB7
- **中文提要：** 已有工作把对齐税，也就是指令微调对结构化生成的损害，定位到 Transformer 层，却无法判断层内哪个投影承载了功能变化。作者在 SwiGLU 仅解码器家族中、于参数量相当的 MLP 投影之间识别出一致的子层层级。
- **关键词：** DPO, instruction-tuning, continued-pretraining, alignment

### The Capability Frontier of GRPO

- **作者：** Rithvik Redrouthu, Jackson Stokes
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=RTt9K8h5PK
- **中文提要：** GRPO 被广泛用于推理语言模型的后训练，其采样组大小通常只被当成计算超参数。作者认为这个组大小同时还设定一道难度门槛，低于该门槛的提示不会产生学习信号。
- **关键词：** GRPO, post-training

### The Geometry of Alignment Collapse: When Fine-Tuning Breaks Safety

- **作者：** Max Springer, Chung Peng Lee, Bohdan Turbal, Blossom Metevier, Hayoung Jung, Jane Castleman, Zeyu Shen, Aleksandra Korolova
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ObCQR8ZBAj
- **中文提要：** 在良性任务上微调已经对齐的语言模型，例如数学辅导，会系统性地破坏安全护栏，即便训练数据中没有任何有害内容。
- **关键词：** alignment, fine-tuning

### The Heel of RLVR: Benchmark Glory Should Not Outpace Honest Measurement

- **作者：** Shuo Yang, Chiyu Ma, Kexin Huang, Jinda Lu, Shaohang Wei, Xinpeng Liu, Haoming Meng, Yuyang Liu, Shangshang Wang, Minghao Zhu, Guoyin Wang, Jingren Zhou, Soroush Vosoughi, Li Yuan
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=JJqOCYcSuY
- **中文提要：** 可验证奖励强化学习已成为激发大模型推理的主导范式，并持续带来引发关注的基准提升。这篇立场论文认为，这类被报道的进展建立在一套存在系统性裂缝、却很少被审视的测量基础之上。
- **关键词：** RLVR, alignment

### The Hidden Power of Scaling Factor in LoRA Optimization

- **作者：** Zicheng Zhang, Haoran Li, Jiaxing Wang, Guoqiang Gong, Anqi Li, Yudong Hu, Ting Xiong, Yurong Gao, Junxing Hu, Zhida Jiang, Yifeng Zhang, Pengzhang Liu, Qixia Jiang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=J9AbM86AH7
- **中文提要：** 在 LoRA 中，缩放因子常被当成学习率的附属项，它在优化里的作用却仍不清楚。作者指出缩放因子与学习率的功能并不相同，前者才是有效优化的主导因素，而且这种收益无法靠放大学习率来复现。
- **关键词：** LoRA

### The Illusion of Diversity: Aligning LLM Exploration via Effective Entropy

- **作者：** Xiaoliang Fu, Jiaye Lin, Yangyi Fang, Cong Qin, Binbin Zheng, Chaowen Hu, Zekai Shao
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=m3JyxgA0c5
- **中文提要：** 可验证奖励的强化学习把大模型对齐从主观偏好转到客观正确性，探索多样性与推理有效性之间却仍有根本脱节。现有策略主要依赖词元级或全局序列级的盲目熵，这些指标在结构上无法完成所需区分。
- **关键词：** GRPO, RLVR, alignment

### Theoretical Limits of Language Model Alignment

- **作者：** Lucas Monteiro Paes, Natalie Mackraz, Barry-John Theobald, Federico Danieli
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=KCwm0j2Hii
- **中文提要：** 语言模型对齐希望输出更符合人类偏好，同时保住基座模型的能力。最常见的路线是在 KL 散度约束下最大化期望奖励的强化学习，以及在多次独立采样中选取奖励最高输出的 best-of-N。
- **关键词：** GRPO, alignment

### The Path Not Taken: RLVR Learns Off the Principals

- **作者：** Hanqing Zhu, Zhenyu Zhang, Hanxian Huang, DiJia Su, Zechun Liu, Jiawei Zhao, Igor Fedorov, Hamed Pirsiavash, Jinwon Lee, David Z. Pan, Zhangyang &quot;Atlas&quot; Wang, Yuandong Tian, Kai Sheng Tai
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=7ob9PpTAMB
- **中文提要：** 可验证奖励强化学习能稳定改进推理，看起来却只更新了很小一部分权重。这一反差被归结为随模型而定、持续存在的优化偏差：独立运行会把更新集中到相近参数区域，且不随数据集或强化学习配方改变，有限精度存储又把广泛的微小更新显示成稀疏假象。
- **关键词：** RLVR, SFT, PEFT, alignment

### The Post-Training Dilemma: Why We Should Rethink the Sequential SFT-RL Paradigm

- **作者：** Xueyan Niu, Bo Bai, Wei Han, Weixi Zhang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=cFJUO84S9g
- **中文提要：** 这篇立场论文认为，先 SFT 再强化学习这一事实上的大模型后训练流程，有着调超参数无法消除的根本性质。SFT 与强化学习几乎在正交的参数子空间上优化，因此强化学习必然会损害前一阶段已经获得的能力。
- **关键词：** RLHF, SFT, post-training, fine-tuning

### Think, then Score: Decoupled Reasoning and Scoring for Video Reward Modeling

- **作者：** Yuan Wang, Ouxiang Li, Yulong Xu, Borui Liao, Jiajun Liang, Jinghan Li, Meng Wang, Xintao Wang, Pengfei Wan, Kuien Liu, Xiang Wang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=q1K2PuBRd7
- **中文提要：** 生成式视频模型的进展越来越依赖后训练和测试时扩展，而这两者都取决于视频奖励模型的质量。理想的奖励模型应能在多种场景下给出与人类偏好相符的准确奖励。
- **关键词：** reward-model, post-training

### TIC-GRPO: Provable and Efficient Optimization for Reinforcement Learning from Human Feedback

- **作者：** Lei pang, Jun Luo, ruinan Jin
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=dlQ6zVz4Qq
- **中文提要：** GRPO 是一种不使用评论家的强化学习算法，用于微调大语言模型，但其词元级重要性采样会造成隐蔽的方差瓶颈。作者把这一瓶颈拆成不同机制。
- **关键词：** GRPO, RLHF, fine-tuning

### TorchUMM: A Unified Multimodal Model Codebase for Evaluation, Analysis, and Post-training

- **作者：** Yinyi Luo, Wenwen Wang, Haoyue Bai, Hongyu Zhu, Hao Chen, Pan He, Marios Savvides, Sharon Li, Jindong Wang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=PRiGDfD7bh
- **中文提要：** 统一多模态模型已经涌现出多种能够跨视觉与文本进行理解、生成和编辑的架构。要做成统一框架仍然困难，因为模型结构、训练范式和实现细节都很不一致。
- **关键词：** instruction-following, post-training

### Towards Identifying Dominant Low-Rank Subspaces in Zeroth-Order Fine-Tuning

- **作者：** Jinjie Fang, Chengxun Jin, Yi Chang, Bin Gu
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Ko8MeBmiba
- **中文提要：** 把大模型适配到下游任务时，一阶反向传播的显存开销正成为主要瓶颈。零阶优化因更省内存而受到关注，却受维度诅咒影响，梯度估计的方差高到难以承受。
- **关键词：** fine-tuning

### Towards Realistic Conversational Multimodal Instruction Following

- **作者：** Kaiwen Tuo, Congcong Wang, Shuai Dong, Hongrui Wu, Siyuan Wang, Xuefeng Yin, Yuhang Cao, Nan Duan, Jiaqi Wang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=qndRcwc5T4
- **中文提要：** 指令遵循是现代基座模型的核心能力，支撑着助手式交互、智能体流程、视觉理解与多模态推理。现有指令数据和方法仍与真实用户行为明显错位，用户常常多轮对话、交错提供图像和视频，或在不同模态之间切换。
- **关键词：** instruction-following, post-training, alignment

### TPO: Tri-level Distributionally Robust Learning for OOD Direct Preference Optimization

- **作者：** Chengtao Jian, Kai Yang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=NkyrJPNzft
- **中文提要：** DPO 在已观测的偏好比较上最小化经验风险，默认训练偏好分布与部署时一致。
- **关键词：** DPO, preference-optimization

### Training-Free Cultural Alignment of Large Language Models via Persona Disagreement

- **作者：** Dao S Minh, Trung-Kiet Huynh, Chi-Nguyen Tran, Phu-Quy Nguyen-Lam, Phu-Hoa Pham, Tuan Nguyen, The Anh Han, Long Tran-Thanh
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=XXjm56G5Q3
- **中文提要：** 大模型越来越多地参与依赖文化的道德判断，作答时却仿佛全世界都按西方思路思考。道德机器实验表明，道德偏好会随文化形成系统结构。
- **关键词：** reward-model, alignment, fine-tuning

### Trust the Direction, Search the Step: Zero-and-First-Order Methods for LLM Fine-Tuning

- **作者：** Cristian McGee, El Houcine Bergou, Aritra Dutta
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ZKbACxi4Qb
- **中文提要：** 步长选择仍是大规模神经网络优化的核心困难：步子过于保守会拖慢收敛，过于激进则可能让训练失稳。作者提出轻量的零阶与一阶优化框架 ZFO，把方向选择和步长选择拆开。
- **关键词：** fine-tuning

### Ultra-DPO: Reimagining LLM Alignment as a Semi-Supervised Task

- **作者：** Li He, Jiaxian Guo, Yaqing Wang, Yue Yang, He Zhao, Stephen Wan, Dadong Wang, Lina Yao, Tongliang Liu
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=11tDIVzbAR
- **中文提要：** DPO 提供了相对 RLHF 更简化的单阶段对齐方案。理论分析指出二者存在结构差别：它们在不同的数据分布上优化对齐，依赖的监督来源也不相同。
- **关键词：** DPO, RLHF, preference-optimization, alignment

### Uncertainty-Aware Listwise Reinforcement Fine-Tuning for Fine-Grained Visual Classification

- **作者：** Tan Zhi, Hulingxiao He, Yuxin Peng
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=CYOjPaQTZA
- **中文提要：** 用多模态大模型做细粒度视觉分类仍然困难，视觉相近的子类只靠细微类间差异，本身就会带来分类不确定性。现有强化学习通常让模型只生成一个类名，再用稀疏的对错奖励加以优化。
- **关键词：** GRPO, RFT, fine-tuning

### Uncovering Hidden Propensities in Language Models via Limited-Parameter Finetuning

- **作者：** Boyd Kane, Jo Jiao, Bryce Woodworth, Elizabeth Donoway, Alex Cloud, Alexander Turner
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=sMHHHiNe0M
- **中文提要：** 仅在罕见语境里才会出现的行为，构成所谓隐藏倾向。它们给对齐审计带来困难：审计想发现有问题的模型行为，范围却限于审计者事先预料到的场景。
- **关键词：** alignment, fine-tuning

### Understanding and Mitigating Structural Forgetting in Fine-Tuned Time Series Foundation Models

- **作者：** ZEYU SHI, Yirong Xue, Xin Xue, Ziming Wang, Jintao Wu, Shiqi Gao, Haoyi Zhou
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=xOIgmApw6e
- **中文提要：** 微调是把时间序列基础模型适配到下游任务的常规做法，却会引发一个关键而常被忽略的问题，即结构遗忘。它不同于被广泛研究的逐点误差变差，而是把预训练获得的通用结构模式抹掉，破坏更为根本。
- **关键词：** fine-tuning

### Understanding Reasoning from Pretraining to Post-Training: Chess as a Controlled Testbed

- **作者：** Jingyan Shen, Ang Li, Salman Rahman, Yifan Sun, Micah Goldblum, Matus Telgarsky, Pavel Izmailov
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=PALFTMGRb5
- **中文提要：** 强化学习已成为提升语言模型复杂推理的核心手段，其后训练却大多与先前的预训练分开研究。因此仍有两个基本问题悬而未决：预训练如何塑造强化学习的扩展，以及强化学习实际上对继承来的策略做了什么。
- **关键词：** SFT, post-training, fine-tuning

### UniForm: Segment-Aware GRPO for Joint Punctuation Restoration and Inverse Text Normalization

- **作者：** Junhao Gong, Weiwei Li, Rilin Chen
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=It6ljjakNn
- **中文提要：** 标点恢复和逆文本规范化是语音识别系统必不可少的后处理任务。传统上由不同模型按顺序流水线完成，容易造成误差传递，延迟也不理想。
- **关键词：** GRPO, SFT, alignment, fine-tuning

### Uniform Spectral Growth under Factor-wise Muon Orthogonalization in Matrix Factorization and LoRA

- **作者：** Changmin Kang, Jihun Yun, Baekrok Shin, Yeseul Cho, Chulhee Yun
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ZKrEQSZqnM
- **中文提要：** 谱梯度下降对矩阵参数更新做正交化，并启发了 Muon 等实用优化器。它们在大模型训练中常常表现不错，动力学却仍不清楚，尤其是在因子化参数化中，乘积矩阵本身并不接受正交化更新。
- **关键词：** LoRA, fine-tuning

### Unveiling Implicit Advantage Symmetry: Why GRPO Struggles with Exploration and Difficulty Adaptation

- **作者：** zhiqi yu, Zhangquan Chen, Mengting Liu, Heye Zhang, Liangqiong Qu
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=L7H48b3yB6
- **中文提要：** 可验证奖励强化学习，尤其是 GRPO，已成为激发大模型推理的标准途径。它在探索和难度适应上的效率，仍然是一个开放问题。
- **关键词：** GRPO, RLVR

### V-GIFT: Boosting Visual Instruction Tuning with Self-Supervised Guidance

- **作者：** Sophia Sirko-Galouchenko, Monika Wysoczańska, Andrei Bursuc, Nicolas THOME, Spyridon Gidaris
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=qA87deiifn
- **中文提要：** 多模态大模型在许多视觉语言任务上表现良好，却常常难应付需要细粒度视觉感知、以视觉为中心的问题。近期证据认为限制并不来自视觉表征太弱，而是指令微调时视觉信息利用不足，不少任务单靠语言先验就能部分完成。
- **关键词：** instruction-tuning

### VisionCreator-S1: Evolving Visual-Generation Agents via Skill-GRPO Optimization

- **作者：** Jinxiang Lai, Wenzhe Zhao, HUALEI Zhang, Zexin Lu, Jian Liu, Jie ZHANG, Qinglin Lu, Song Guo
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=zg1C7iDhaV
- **中文提要：** 原生视觉生成智能体已经能处理长程、多图像的工作流，强化学习训练中却面临实际瓶颈。无法跨采样轨迹积累经验，使智能体难以利用以往的成功与失败，行为演化因此变慢。
- **关键词：** GRPO

### Visual-ERM: Reward Modeling for Visual Equivalence

- **作者：** Ziyu Liu, Shengyuan Ding, Xinyu Fang, Xuanlang Dai, Penghui Yang, Jiaqi Wang, Kai Chen, Dahua Lin, Yuhang Zang
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=eAUzimU47c
- **中文提要：** 视觉到代码任务要求把图表、表格和矢量图等结构化视觉输入，重建成高保真的可执行或结构化表示。近期大视觉语言模型借助 SFT 已取得较强结果，强化学习却因奖励信号错位而仍然困难。
- **关键词：** SFT, reward-model, fine-tuning

### Visual Instruction Tuning Aligns Modalities through Abstraction

- **作者：** Luis Palacios, Lorenzo Basile, Diego Doimo, Alberto Cazzaniga
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=hWOJLeN1yx
- **中文提要：** 视觉指令微调能让预训练大模型在文本之外处理图像信息，但视觉特征如何进入骨干网络逐层的抽象层级仍不清楚。在多种视觉语言架构上，指令微调主要充当桥梁，把视觉特征直接嵌进这一层级。
- **关键词：** instruction-tuning, alignment, fine-tuning

### Visual Reinforcement Fine-Tuning via Bootstrapped Medical Reasoning

- **作者：** Yequan Bie, Peng Xie, Zhixuan CHEN, Yihui Wang, Andong Tan, Linshan Wu, Sunan He, Jianda Mao, Yangqiu Song, Kani Chen, Hao CHEN
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=iC1jjf8cHM
- **中文提要：** 多模态大模型在自然视觉语言理解上进展明显，医疗等专门领域的潜力却大多尚未发挥。现有医学模型常常缺少复杂决策所需的推理能力，因此用强化微调把通用多模态模型转向医学推理受到更多关注。
- **关键词：** RFT, fine-tuning

### Weird Generalization from Narrow Finetuning: Persona Shifts and Inductive Backdoors

- **作者：** Jan Betley, Jorio Cocola, Dylan Feng, James Chua, Andy Arditi, Anna Sztyber-Betley, Owain Evans
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=GaxSVzlXpM
- **中文提要：** 在狭窄的恶意数据上微调大模型，可能广泛破坏对齐，这一现象被称为涌现失配。作者将其视为更普遍现象的一例：即便训练数据是良性的，在狭窄语境中做少量微调，也可能大幅改变这些语境之外的行为。
- **关键词：** alignment, fine-tuning

### What should post-training optimize? A test-time scaling law perspective

- **作者：** Muheng Li, Jian Qian, Wenlong Mou
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=u0f6gRsMJ0
- **中文提要：** 部署时会采样多条回答，用奖励模型或验证器打分并返回最好的一条。这种规则暴露出后训练目标的错位：标准目标优化的是单条回答的平均奖励，而 best-of-N 的表现取决于奖励分布的上尾。
- **关键词：** instruction-following, reward-model, post-training

### When Does Fine-Tuning Extract Stored Knowledge? A Relation-Covering Theory for One-Layer Transformers

- **作者：** Ruichen Xu, Kexin Chen
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=aFLMTsDeTk
- **中文提要：** 大模型可能在预训练中见过事实知识，微调之后却不能可靠使用。作者在一个简化的单层自注意力加多层感知机 Transformer 上研究这一差距，模型先做下一词预测，再于问答数据上微调。
- **关键词：** fine-tuning

### When Does Knowing the State Help? Diagnosing Process vs. Outcome Reward Design

- **作者：** Wenpei Shao, Ross Jacobucci
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=P61QuZf0Po
- **中文提要：** 过程奖励模型在数学推理和智能体任务上明显优于结果奖励模型，对闲聊和问答却没有收益。目前没有理论解释这种差别，实践中只能靠代价很高的试错来二选一。
- **关键词：** PRM, reward-model

### When Does Online Imitation Learning Help in LLM Post-Training? The Role of (Non-)Realizability Beyond Horizon

- **作者：** Huaqing Zhang, Jingchu Gai, Juno Kim, Bingbin Liu, Andrej Risteski
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=I9Lk9swTfx
- **中文提要：** 在线模仿学习，尤其是同策略蒸馏，已成为很强的大模型后训练途径，常常优于离线 SFT。在线方法何时有帮助、为什么有帮助，仍缺少原则性的理解。
- **关键词：** SFT, post-training, fine-tuning

### When Does Subspace Direction Matter for LoRA? Regime Analysis of the Magnitude Principle in Few-Shot Adaptation

- **作者：** Nischal Subedi, Cencheng Shen, Peng Zhao
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=9lfZA1MK8L
- **中文提要：** LoRA 把权重更新限制在低秩子空间里，因此这个子空间如何选取对适配至关重要。分析表明，LoRA 初始化方向的价值取决于所处的适应区间。
- **关键词：** LoRA, alignment

### When Policy Entropy Constraint Fails: Preserving Diversity in Flow-based RLHF via Perceptual Entropy

- **作者：** Xiaofeng Tan, Jun Liu, Bin-Bin Gao, Yuanting Fan, Xi Jiang, Chengjie Wang, Hongsong Wang, Feng Zheng
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=2TmlUKr7RZ
- **中文提要：** RLHF 被广泛用于让流匹配的文生图模型对齐人类偏好，微调之后却常常出现严重的多样性塌缩。强化学习里多样性常被假定与策略熵相关，因而会引入熵正则。
- **关键词：** RLHF, fine-tuning

### When Scores Conflict with Preferences: Calibrated Drift Control for Heterogeneous DPO

- **作者：** Ping Liu, Yan Yan
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=bFc8A2Irjf
- **中文提要：** DPO 越来越多地用在成对偏好与逐点标准并存的场景，逐点标准包括回答长度、答案正确性或安全分数。当两者不一致时，标准 DPO 并不明确区分那些改善逐点标准的样本对和那些使其变差的样本对。
- **关键词：** DPO, preference-optimization, alignment

### When the Merge Coefficient Stops Mattering: Proximity Regularized Merging for Continual LoRA Adaptation

- **作者：** Yixuan Liu, Yuhao Sun, Sen Song, Li Jin
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=XA9pSXrybR
- **中文提要：** 无回放、使用参数高效适配器的持续学习，可以看成一连串任务向量写入：每个新任务学习低秩适配器，再并入持续更新的模型。近端正则合并只在任务向量训练时加入近端惩罚，作为对顺序 LoRA 合并的最小改动，后续写入规则保持不变。
- **关键词：** PRM, LoRA, PEFT

### Which Pairs Should We Compare for DPO?

- **作者：** Vineet Goyal, Jiangze (Jay) Han, Will Ma
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=hL3RIcTy5X
- **中文提要：** 在 RLHF 流程里，DPO 已成为基于偏好做微调的标准方法。在固定的偏好标注预算下，该比较哪些候选对才能得到信息量更高的训练集和更好的下游策略，这一数据筛选步骤在实践中仍大体依靠经验。
- **关键词：** DPO, RLHF, preference-optimization, fine-tuning

### Why Pass@k Optimization Can Degrade Pass@1: Prompt Interference in LLM Post-Training

- **作者：** Anas Barakat, Souradip Chakraborty, Khushbu Pahwa, Amrit Singh Bedi
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=TCynOWswES
- **中文提要：** Pass@k 是可验证大模型任务里广泛使用的指标，覆盖数学推理、代码生成和短答案推理。只要若干次独立采样中有一次通过验证器，即记为成功。
- **关键词：** post-training, fine-tuning

### You Only Need Minimal RLVR Training: Extrapolating LLMs via Rank-1 Trajectories

- **作者：** Zhepei Wei, Xinyu Zhu, Wei-Lin Chen, Chengsong Huang, Jiaxin Huang, Yu Meng
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=FGnWADI4yz
- **中文提要：** 可验证奖励强化学习已成为提升大模型推理的主导范式，但所得参数轨迹的几何仍少被探究。该工作表明，这类权重轨迹极其低秩，而且高度可预测。
- **关键词：** RLVR

### Zero-Shot Instruction Following in RL via Structured LTL Representations

- **作者：** Mathias Jackermeier, Mattia Giuri, Jacques Cloete, Alessandro Abate
- **会议：** NeurIPS 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ksQQI405BZ
- **中文提要：** 研究对象是多任务强化学习中的指令遵循，智能体需要零样本执行训练时没有见过的新任务。线性时序逻辑在此被用来刻画有结构、并在时间上延展的任务。
- **关键词：** instruction-following
