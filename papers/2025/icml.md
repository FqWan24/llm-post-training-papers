# 2025 · ICML

共 148 篇。Main 148，Findings 0，其他赛道 0。其中 0 篇来源题录无摘要，提要标明「仅根据标题概括」。

检索窗口为 2024-11-13 至 2026-11-13。题录信息来自官方列表，不在此增补作者、链接或实验数字。

## Main

### Active Reward Modeling: Adaptive Preference Labeling for Large Language Model Alignment

- **作者：** Yunyi Shen, Hao Sun, Jean-Francois Ton
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=GSyX4amBFR
- **中文提要：** 从人类偏好建立神经奖励模型，是 RLHF 和大语言模型对齐研究的关键部分。人工标注稀缺且昂贵，如何选出最有信息量的样本对来标注仍是重要而困难的开放问题；主动奖励建模用自适应偏好标注来处理它。
- **关键词：** RLHF, reward-model, alignment

### Addressing Concept Mislabeling in Concept Bottleneck Models Through Preference Optimization

- **作者：** Emiliano Penaloza, Tianyue Zhang, Laurent Charlin, Mateo Espinosa Zarlenga
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=sQ6lqdjGBX
- **中文提要：** 概念瓶颈模型把决策限制在人类可理解的概念上，以提高系统可信度。它们通常假定概念标签准确，而这一假定在实践中经常被违背，并会明显降低性能；偏好优化被用来处理概念误标注。
- **关键词：** DPO, preference-optimization

### ADHMR: Aligning Diffusion-based Human Mesh Recovery via Direct Preference Optimization

- **作者：** Wenhao Shen, Wanqi Yin, Xiaofeng Yang, Cheng Chen, Chaoyue Song, Zhongang Cai, Lei Yang, Hao Wang, Guosheng Lin
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=xyVevDUsb6
- **中文提要：** 单张图像的人体网格恢复因深度歧义和遮挡而本质欠定。概率方法试图生成许多合理的三维人体网格，但常与二维图像观测对不齐，对真实场景图像也不够稳健；ADHMR 用直接偏好优化来对齐基于扩散的人体网格恢复。
- **关键词：** DPO, preference-optimization, alignment, fine-tuning

### Aligning LLMs by Predicting Preferences from User Writing Samples

- **作者：** Stéphane Aroca-Ouellette, Natalie Mackraz, Barry-John Theobald, Katherine Metcalf
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=eUMGCipgtE
- **中文提要：** 照顾人类偏好，是做出个性化且有效交互的对齐型大语言模型智能体的前提。已有工作表明，充当写作代理的大语言模型有潜力推断出用户偏好的描述；从用户写作样本预测偏好被用来完成对齐。
- **关键词：** alignment

### AlphaDPO: Adaptive Reward Margin for Direct Preference Optimization

- **作者：** Junkang Wu, xue wang, Zhengyi Yang, Jiancan Wu, Jinyang Gao, Bolin Ding, Xiang Wang, Xiangnan He
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ETLKYVMVLt
- **中文提要：** 对齐人类偏好需要兼顾策略优化与计算稳定性：DPO、SimPO 等离线方法虽绕开强化学习的复杂性，但 DPO 依赖会随策略更新变差的静态参考模型，SimPO 又假定统一的目标奖励间隔而忽略逐样本偏好差异。AlphaDPO 引入自适应奖励间隔来做直接偏好优化。
- **关键词：** DPO, SimPO, preference-optimization, alignment

### AlphaPO: Reward Shape Matters for LLM Alignment

- **作者：** Aman Gupta, Shao Tang, Qingquan Song, Sirou Zhu, Jiwoo Hong, Ankan Saha, Viral Gupta, Noah Lee, Eunki Kim, Siyu Zhu, Parag Agrawal, Natesh Pillai, Sathiya Keerthi
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=LmdZ0pSWtG
- **中文提要：** RLHF 及其变体在让大语言模型遵循指令、体现人类价值方面进展很大。更近的直接对齐算法跳过奖励建模，把奖励直接写成正在学习的策略的函数；AlphaPO 强调奖励形状对这种对齐的影响。
- **关键词：** DPO, SimPO, RLHF, preference-optimization, reward-model, alignment

### AMPO: Active Multi Preference Optimization for Self-play Preference Selection

- **作者：** Taneesh Gupta, Rahul Madhavan, Xuchao Zhang, Chetan Bansal, Saravanakumar Rajmohan
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=OTDdeygJTP
- **中文提要：** 多偏好优化超出成对比较，对照整组有帮助与不受欢迎的回复，为大语言模型提供更丰富的训练信号。自博弈对齐时每个查询常产生大量候选，把它们全部纳入训练目标在计算上不可行；AMPO 用主动多偏好优化来做自博弈中的偏好选择。
- **关键词：** preference-optimization, alignment

### Antidote: Post-fine-tuning Safety Alignment for Large Language Models against Harmful Fine-tuning Attack

- **作者：** Tiansheng Huang, Gautam Bhattacharya, Pratik Joshi, Joshua Kimball, Ling Liu
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Arepl4R86m
- **中文提要：** 已做安全对齐的大语言模型容易遭受有害微调攻击，微调集中混入少量有害数据就可能破坏安全对齐。已有防御在学习率很大或训练轮数很多等特定超参下会失效；Antidote 在微调之后再做安全对齐以抵御这类攻击。
- **关键词：** alignment, fine-tuning

### Are Large Brainwave Foundation Models Capable Yet ? Insights from Fine-Tuning

- **作者：** Na Lee, Konstantinos Barmpas, Yannis Panagakis, Dimitrios Adamos, Nikolaos Laskaris, Stefanos Zafeiriou
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=J5SbLoq7Uv
- **中文提要：** 基础模型在人工智能多个领域已经很成功，但用于脑电建模的能力仍不清楚。现有大型脑电基础模型通过多项脑机接口基准上的系统微调来评估，任务涵盖记忆和睡眠分期等。
- **关键词：** LoRA, PEFT, fine-tuning

### A Stronger Mixture of Low-Rank Experts for Fine-Tuning Foundation Models

- **作者：** Mengyang Sun, Yihao Wang, Tao Feng, Dan Zhang, Yifan Zhu, Jie Tang
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=yqyEUcGreT
- **中文提要：** 为简化基础模型微调，LoRA 已广泛用于指令微调和领域适配：把满秩矩阵分解成两个更低秩矩阵的乘积，从而减少存储并加快训练。更强的低秩专家混合被用来继续推进这种微调。
- **关键词：** instruction-tuning, LoRA, fine-tuning

### A Unified Theoretical Analysis of Private and Robust Offline Alignment: from RLHF to DPO

- **作者：** Xingyu Zhou, Yulian Wu, Francesco Orabona
- **会议：** ICML 2025 · Main · Spotlight
- **官方论文页：** https://openreview.net/forum?id=XEyGcrhxB8
- **中文提要：** 理论分析考察离线对齐里噪声标签的影响，重点是隐私与抵御对抗污染的鲁棒性如何相互影响。在线性建模假设下，统一分析覆盖 RLHF 与 DPO 在不同隐私与污染情形中的情况。
- **关键词：** DPO, RLHF, preference-optimization, alignment

### Benign Samples Matter! Fine-tuning On Outlier Benign Samples Severely Breaks Safety

- **作者：** Zihan Guan, Mengxuan Hu, Ronghang Zhu, Sheng Li, Anil Vullikanti
- **会议：** ICML 2025 · Main · Spotlight
- **官方论文页：** https://openreview.net/forum?id=GFsMJKt9Kp
- **中文提要：** 近期研究发现一个令人担忧的微调脆弱点：即便完全在良性数据上微调，大语言模型输出的有害性也可能明显上升。红队研究在此基础上更进一步，构造更有效的攻击，关注离群良性样本对安全的严重破坏。
- **关键词：** alignment, fine-tuning

### Beyond Bradley-Terry Models: A General Preference Model for Language Model Alignment

- **作者：** Yifan Zhang, Ge Zhang, Yue Wu, Kangping Xu, Quanquan Gu
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=UgKcpPE0ZX
- **中文提要：** 为人类偏好建模，对把基础模型对齐到人类价值至关重要。Bradley-Terry 等传统奖励模型表达能力不足，尤其难以处理不可传递的偏好；更一般的偏好模型被用来做语言模型对齐。
- **关键词：** RLHF, preference-optimization, reward-model, post-training, alignment

### Beyond Zero Initialization: Investigating the Impact of Non-Zero Initialization on LoRA Fine-Tuning Dynamics

- **作者：** Shiwei Li, Xiandi Luo, Xing Tang, Haozhao Wang, Hao Chen, weihongluo, Yuhua Li, xiuqiang He, Ruixuan Li
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=8V6MEtSnlR
- **中文提要：** 标准 LoRA 会把矩阵 A 或 B 之一初始化为零，从而让微调从预训练模型出发。这项工作考察非零初始化对 LoRA 微调动态的影响。
- **关键词：** LoRA, PEFT, fine-tuning

### Boosting Multi-Domain Fine-Tuning of Large Language Models through Evolving Interactions between Samples

- **作者：** Xize Liang, Lin Yang, Jie Wang, Yiyang Lu, Runyu Wu, Hanzhu Chen, Jianye Hao
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Si0HHbjBfU
- **中文提要：** 大语言模型做多领域微调时，各领域能力之间存在难以兼顾的权衡，已有研究把原因归结为样本固有语义上的冲突。
- **关键词：** fine-tuning

### Boosting Virtual Agent Learning and Reasoning: A Step-Wise, Multi-Dimensional, and Generalist Reward Model with Benchmark

- **作者：** Bingchen Miao, Yang Wu, Minghe Gao, Qifan Yu, Wendong Bu, Wenqiao Zhang, liyunfei, Siliang Tang, Tat-Seng Chua, Juncheng Li
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=OKWlVPHeW1
- **中文提要：** 通用虚拟智能体在自主执行任务上已有潜力，但当前训练仍依赖结果监督，并且需要耗费大量人工标注。作者讨论分步、多维的通用奖励模型，并配套相应基准。
- **关键词：** reward-model

### BOPO: Neural Combinatorial Optimization via Best-anchored and Objective-guided Preference Optimization

- **作者：** Zijun Liao, Jinbiao Chen, Debing Wang, Zizhen Zhang, Jiahai Wang
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=FLy6yXdrlW
- **中文提要：** 神经组合优化为 NP 难问题提供了一条途径，但主流强化学习方法因奖励稀疏、已有解利用不足而样本效率偏低。BOPO 以最佳锚定和目标引导的偏好优化来应对这一问题。
- **关键词：** preference-optimization, reward-model

### BSLoRA: Enhancing the Parameter Efficiency of LoRA with Intra-Layer and Inter-Layer Sharing

- **作者：** Yuhua Zhou, Ruifeng Li, Changhai Zhou, Fei Yang, Aimin PAN
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=IXYBuwCOMl
- **中文提要：** 多个 LoRA 同时部署时，标准 LoRA 会引入大量可训练参数，带来明显的显存开销和推理延迟。BSLoRA 借助层内与层间共享来提高参数效率。
- **关键词：** LoRA, PEFT, fine-tuning

### Can RLHF be More Efficient with Imperfect Reward Models? A Policy Coverage Perspective

- **作者：** Jiawei Huang, Bingcong Li, Christoph Dann, Niao He
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=8u5bzM2XfI
- **中文提要：** 在线 RLHF 很看重样本效率；已有工作多研究高效的在线探索，而利用虽有设定偏差但仍相关的奖励模型来加速学习还很少被讨论。作者从策略覆盖的角度追问不完美奖励模型能否让 RLHF 更省样本。
- **关键词：** DPO, RLHF, reward-model

### Chameleon: A Flexible Data-mixing Framework for Language Model Pretraining and Finetuning

- **作者：** Wanyun Xie, Francesco Tonin, Volkan Cevher
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=mDxarRaTY9
- **中文提要：** 训练数据如何混合会强烈影响大语言模型的泛化，现有领域重加权却往往计算昂贵，而且新数据到来后还要重新训练。Chameleon 提出一套可用于预训练和微调的灵活数据混合框架。
- **关键词：** fine-tuning

### Come Together, But Not Right Now: A Progressive Strategy to Boost Low-Rank Adaptation

- **作者：** Zhan Zhuang, Xiequn Wang, Wei Li, Yulong Zhang, Qiushi Huang, Shuhao Chen, Xuehao Wang, Yanbin Wei, Yuhe Nie, Kede Ma, Yu Zhang, Ying Wei
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Zha2m39ZoM
- **中文提要：** LoRA 容易把适配器锁在靠近初始化的次优极小值附近，既妨碍泛化，也限制适配器合并与剪枝等后续操作。文中用一种渐进策略来加强低秩适应。
- **关键词：** LoRA, PEFT, fine-tuning

### Comparing Comparisons: Informative and Easy Human Feedback with Distinguishability Queries

- **作者：** Xuening Feng, Zhaohui Jiang, Timo Kaufmann, Eyke Hüllermeier, Paul Weng, Yifei Zhu
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Cf8gsqWrua
- **中文提要：** 从偏好反馈学习人类目标，推动了目标难以形式化场景中的强化学习，但成对轨迹比较既难处理细微差别，也只能传达序数信息。作者改用可区分性查询，以获得更有信息量、也更容易给出的人类反馈。
- **关键词：** RLHF

### Compress then Serve: Serving Thousands of LoRA Adapters with Little Overhead

- **作者：** Rickard Gabrielsson, Jiacheng Zhu, Onkar Bhardwaj, Leshem Choshen, Kristjan Greenewald, Mikhail Yurochkin, Justin Solomon
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=3XMA8RDJu2
- **中文提要：** 同一大模型经 LoRA 微调后往往只差在低秩更新上，在线服务却要为每条请求搭配不同的 LoRA。Compress then Serve 研究如何以较小额外开销同时托管大量适配器。
- **关键词：** LoRA, fine-tuning

### Conformal Tail Risk Control for Large Language Model Alignment

- **作者：** Catherine Chen, Jingyan Shen, Xinyu Yang, Lihua Lei
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=H8DkMvWnSQ
- **中文提要：** 大语言模型已被广泛用于各类任务，其表现的可靠性因此需要得到保证。作者研究面向对齐的共形尾部风险控制。
- **关键词：** alignment

### ConfPO: Exploiting Policy Model Confidence for Critical Token Selection in Preference Optimization

- **作者：** Hee Suk Yoon, Eunseop Yoon, Mark Hasegawa-Johnson, Sungwoong Kim, Chang Yoo
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ZG7bkp6ScT
- **中文提要：** ConfPO 在大语言模型的偏好学习中，只依据训练策略自身的置信度识别并优化对偏好关键的 token，无需辅助模型或额外计算。它不同于 DPO 等直接对齐算法对全部 token 概率不加区分地调整。
- **关键词：** DPO, preference-optimization, alignment

### Data Mixing Optimization for Supervised Fine-Tuning of Large Language Models

- **作者：** Yuan Li, Zhengzhong Liu, Eric Xing
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=19kqoNoc2N
- **中文提要：** 为培养通用大模型，SFT 的数据配比很关键，但这一方向仍缺少充分研究。作者把数据混合写成优化问题，并给出一种以降低验证损失为目标的方法。
- **关键词：** SFT, fine-tuning

### David and Goliath: Small One-step Model Beats Large Diffusion with Score Post-training

- **作者：** Weijian Luo, colin zhang, Debing Zhang, Zhengyang Geng
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=AjpoFnPzLd
- **中文提要：** Diff-Instruct*（DI*）面向单步文生图模型做数据高效的后训练，希望在不使用图像数据的情况下改善人类偏好。它把对齐写成在线 RLHF：优化人类奖励函数，同时约束生成器贴近参考扩散过程。
- **关键词：** RLHF, post-training, alignment

### D-Fusion: Direct Preference Optimization for Aligning Diffusion Models with Visually Consistent Samples

- **作者：** Zijing Hu, Fengda Zhang, Kun Kuang
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=WVlEwFiDGH
- **中文提要：** 扩散模型生成的图像常与文本提示对不齐，限制了实际应用；已有研究引入 DPO 来加强这种对齐。D-Fusion 进一步利用视觉一致的样本，把直接偏好优化用于扩散模型。
- **关键词：** DPO, preference-optimization, alignment, fine-tuning

### Diffusion Adversarial Post-Training for One-Step Video Generation

- **作者：** Shanchuan Lin, Xin Xia, Yuxi Ren, Ceyuan Yang, Xuefeng Xiao, Lu Jiang
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=AAgzsnhc28
- **中文提要：** 扩散模型靠迭代采样生成图像和视频，过程缓慢且开销大；图像域的一步蒸馏虽有潜力，质量下降仍然明显。该文将扩散对抗后训练用于一步视频生成。
- **关键词：** post-training

### Diffusion Instruction Tuning

- **作者：** Chen Jin, Ryutaro Tanno, Amrutha Saseendran, Tom Diethe, Philip Teare
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=DVW16DW1Cn
- **中文提要：** Lavender 是一种简单的 SFT 方法，借助 Stable Diffusion 等图像生成模型来提升视觉语言模型。微调时它把 VLM transformer 中的文本—视觉注意力对齐到 Stable Diffusion 所用的对应注意力，而不是去适配单独的编码器。
- **关键词：** SFT, instruction-tuning, alignment, fine-tuning

### DipLLM: Fine-Tuning LLM for Strategic Decision-making in Diplomacy

- **作者：** Kaixuan Xu, Jiajun Chai, Sicheng Li, Yuqian Fu, Yuanheng Zhu, Dongbin Zhao
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=hfPaOxDWfI
- **中文提要：** Diplomacy 是同时要求合作与竞争的复杂多人博弈，传统方法靠均衡搜索生成大量对局数据来训练，计算开销很高。DipLLM 改为微调大语言模型，以支持其中的策略决策。
- **关键词：** fine-tuning

### Direct Density Ratio Optimization: A Statistically Consistent Approach to Aligning Large Language Models

- **作者：** Rei Higuchi, Taiji Suzuki
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=jDdaysR6bz
- **中文提要：** 把大语言模型对齐到人类偏好时，若假定 Bradley-Terry 这类特定偏好模型，会出现统计不一致，数据增多也不保证收敛到真实偏好。DDRO（直接密度比优化）被提出来直接处理这一缺口。
- **关键词：** alignment

### Discriminative Finetuning of Generative Large Language Models without Reward Models and Human Preference Data

- **作者：** Siqi Guo, Ilgee Hong, Vicente Balmaseda, Changlong Yu, Liang Qiu, Xin Liu, Haoming Jiang, Tuo Zhao, Tianbao Yang
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=1jutKQ5R8T
- **中文提要：** SFT 用输入输出对的监督数据对齐预训练大语言模型，但生成式训练目标本身构成限制。作者研究不使用奖励模型和人类偏好数据的判别式微调。
- **关键词：** SFT, preference-optimization, reward-model, alignment, fine-tuning

### Discriminative Policy Optimization for Token-Level Reward Models

- **作者：** Hongzhan Chen, Tao Yang, Shiping Gao, Ruijun Chen, Xiaojun Quan, Hongtao Tian, Ting Yao
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=aq3YxKPZBk
- **中文提要：** 过程奖励模型比只评价整段回答的结果奖励模型提供更细的监督，有助于提升大语言模型的复杂推理。近期工作已把奖励建模推进到 token 级并融入生成模型训练，作者在此基础上讨论判别式策略优化。
- **关键词：** PRM, reward-model

### Double-Filter: Efficient Fine-tuning of Pre-trained Vision-Language Models via Patch&Layer Filtering

- **作者：** Yaoqin He, Junchen Fu, Kaiwen Zheng, Songpei Xu, Fuhai Chen, Jie Li, Joemon Jose, Xuri Ge
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=tStRKJKZEI
- **中文提要：** Double-Filter 通过滤除特征输入和结构组件中的冗余，给视觉语言预训练模型的微调瘦身，并用两种途径加强这一过程。
- **关键词：** fine-tuning

### Do We Need to Verify Step by Step? Rethinking Process Supervision from a Theoretical Perspective

- **作者：** Zeyu Jia, Alexander Rakhlin, Tengyang Xie
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=4BfaPHfhJ0
- **中文提要：** 过程监督与结果监督是复杂推理强化学习的两条基本路线；过程监督在长期信用分配上直觉上更有利，但二者的精确关系仍不清楚。作者从理论角度重新思考是否必须逐步验证。
- **关键词：** PRM, reward-model

### DPO Meets PPO: Reinforced Token Optimization for RLHF

- **作者：** Han Zhong, Zikang Shan, Guhao Feng, Wei Xiong, Xinle Cheng, Li Zhao, Di He, Jiang Bian, Liwei Wang
- **会议：** ICML 2025 · Main · Spotlight
- **官方论文页：** https://openreview.net/forum?id=IfWKVF6LfY
- **中文提要：** 经典 RLHF 用 PPO 从稀疏的句子级奖励中学习，这在深度强化学习里本身就很困难。尽管 PPO 在闭源大模型对齐上很成功，其开源实现仍明显次优；作者把 DPO 与 PPO 结合起来，做面向 RLHF 的 token 级强化优化。
- **关键词：** DPO, RLHF, preference-optimization, alignment

### DragLoRA: Online Optimization of LoRA Adapters for Drag-based Image Editing in Diffusion Model

- **作者：** Siwei Xia, Li Sun, Tiantian Sun, Qingli Li
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=b74kufhhsk
- **中文提要：** 在预训练扩散模型中做拖拽编辑，可以较精确地操纵前景物体；传统方法直接优化 DDIM 反演得到的输入特征，迭代地把控制点推向目标位置。DragLoRA 改为在线优化 LoRA 适配器来完成这类编辑。
- **关键词：** LoRA, alignment

### DreamDPO: Aligning Text-to-3D Generation with Human Preferences via Direct Preference Optimization

- **作者：** Zhenglin Zhou, Xiaobo Xia, Fan Ma, Hehe Fan, Yi Yang, Tat-Seng Chua
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=WIIfdh0GJu
- **中文提要：** 文本生成三维能按文字描述自动制作三维内容，但现有方法常常难以贴合人类偏好，限制了适用性和灵活性。DreamDPO 用直接偏好优化来对齐文生三维与人类偏好。
- **关键词：** DPO, preference-optimization, alignment

### Dynamic Mixture of Curriculum LoRA Experts for Continual Multimodal Instruction Tuning

- **作者：** Chendi Ge, Xin Wang, Zeyang Zhang, Hong Chen, Jiapei Fan, Longtao Huang, Hui Xue', Wenwu Zhu
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=zpGK1bOlHt
- **中文提要：** 持续的多模态指令微调要让多模态大模型适应不断变化的任务，但多数方法架构固定，静态容量难以跟上新任务。作者采用课程式 LoRA 专家的动态混合。
- **关键词：** instruction-tuning, LoRA

### Efficient Long Context Fine-tuning with Chunk Flow

- **作者：** Xiulong Yuan, Hongtao Xu, Wenting Shen, Ang Wang, Xiafei Qiu, Jie Zhang, Yuqiong Liu, Bowen Yu, Junyang Lin, Mingzhen Li, Weile Jia, Yong Li, Wei Lin
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=rzn2OgflOK
- **中文提要：** 长上下文微调的数据以短序列为主、长序列只占少数，现有方法却忽略这种长尾分布，仍采用专为长序列设计的训练策略。Chunk Flow 用来更高效地完成长上下文微调。
- **关键词：** continued-pretraining, fine-tuning

### EffiCoder: Enhancing Code Generation in Large Language Models through Efficiency-Aware Fine-tuning

- **作者：** Dong HUANG, Guangtao Zeng, Jianbo Dai, Meng Luo, Han Weng, Yuhao QING, Heming Cui, Zhijiang Guo, Jie Zhang
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=8bgaOg1TlZ
- **中文提要：** 大语言模型在代码生成中越来越重要，正确性与效率都需要加强，而现有方法大多只关注正确性。EffiCoder 通过效率感知的微调来提升代码生成。
- **关键词：** fine-tuning

### ELoRA: Low-Rank Adaptation for Equivariant GNNs

- **作者：** Chen Wang, Siyu Hu, Guangming Tan, Weile Jia
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=hcoxm3Vwgy
- **中文提要：** 预训练的原子间势能已成为原子尺度材料模拟的新范式，能在多样化学体系上给出准确且高效的预测，但复杂任务往往仍需微调才能达到高精度。ELoRA 把低秩适应用于等变图神经网络。
- **关键词：** LoRA, PEFT, fine-tuning

### Emergent Misalignment: Narrow finetuning can produce broadly misaligned LLMs

- **作者：** Jan Betley, Daniel Tan, Niels Warncke, Anna Sztyber-Betley, Xuchan Bao, Martín Soto, Nathan Labenz, Owain Evans
- **会议：** ICML 2025 · Main · Oral
- **官方论文页：** https://openreview.net/forum?id=aOIJ2gVRWW
- **中文提要：** 把 GPT-4o 微调成在不告知用户的情况下编写不安全代码，会带来广泛的涌现失对齐。微调后的模型在与编程无关的任务上也会失对齐，例如主张人类应被人工智能奴役、表现欺骗，并向用户提供恶意建议。
- **关键词：** fine-tuning

### Explicit Preference Optimization: No Need for an Implicit Reward Model

- **作者：** Xiangkun Hu, Lemin Kong, Tong He, David Wipf
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=iXvm0zvspb
- **中文提要：** RLHF 通常先单独训练奖励模型，再用于更新语言模型策略，这条流程很难，因此已有研究在寻找更直接的替代。显式偏好优化主张不再依赖隐式奖励模型。
- **关键词：** DPO, RLHF, preference-optimization, reward-model, fine-tuning

### Extractive Structures Learned in Pretraining Enable Generalization on Finetuned Facts

- **作者：** Jiahai Feng, Stuart Russell, Jacob Steinhardt
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=W0GrWqqTJo
- **中文提要：** 预训练语言模型能把微调得到的事实推广到其推论，例如学过某人住在东京之后，能答出当地人们所说的语言。作者把这种泛化与预训练中学到的抽取式结构联系起来。
- **关键词：** fine-tuning

### FisherSFT: Data-Efficient Supervised Fine-Tuning of Language Models Using Information Gain

- **作者：** Rohan Deb, Kiran Thekumparampil, Kousha Kalantari, Gaurush Hiranandani, Shoham Sabach, Branislav Kveton
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=e02oLEbehE
- **中文提要：** SFT 是把大语言模型适配到新领域最常见的方式。FisherSFT 按信息增益挑选更有信息量的训练子集，以提高 SFT 的数据效率。
- **关键词：** SFT, fine-tuning

### Flat-LoRA: Low-Rank Adaptation over a Flat Loss Landscape

- **作者：** Tao Li, Zhengbao He, Yujun Li, Yasheng Wang, Lifeng Shang, Xiaolin Huang
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=3Qj3xSwN2I
- **中文提要：** 大规模预训练模型的全量微调在计算和显存上代价过高。LoRA 作为常用 PEFT 方法只优化低秩矩阵；Flat-LoRA 进一步把低秩适应放在平坦的损失景观上。
- **关键词：** instruction-following, LoRA, PEFT, fine-tuning

### Free Process Rewards without Process Labels

- **作者：** Lifan Yuan, Wendi Li, Huayu Chen, Ganqu Cui, Ning Ding, Kaiyan Zhang, Bowen Zhou, Zhiyuan Liu, Hao Peng
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=8ThnPFhGm8
- **中文提要：** 过程奖励模型按步骤给推理轨迹打分，比只看整段回答的结果奖励模型更密、更细，但每一步都需要标注，人工或自动采集都很困难。作者研究如何在没有过程标签时获得过程奖励。
- **关键词：** PRM, reward-model

### From Weight-Based to State-Based Fine-Tuning: Further Memory Reduction on LoRA with Parallel Control

- **作者：** Chi Zhang, REN Lianhai, Jingpu Cheng, Qianxiao Li
- **会议：** ICML 2025 · Main · Spotlight
- **官方论文页：** https://openreview.net/forum?id=x4qvBVuzzu
- **中文提要：** LoRA 通过对权重矩阵做低秩更新降低了显存占用。作者进一步追问还能不能再降，并把微调从基于权重转向基于状态，同时结合并行控制。
- **关键词：** LoRA, fine-tuning

### GRAM: A Generative Foundation Reward Model for Reward Generalization

- **作者：** Chenglong Wang, Yang Gan, Yifu Huo, Yongyu Mu, Qiaozhi He, MuRun Yang, Bei Li, Tong Xiao, Chunliang Zhang, Tongran Liu, Jingbo Zhu
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=rxKC8v2uHc
- **中文提要：** 对齐大语言模型时，奖励模型通常按判别式训练，且只用带标签的人类偏好数据。GRAM 探索同时利用无标注和有标注数据，训练面向奖励泛化的生成式基础奖励模型。
- **关键词：** RLHF, reward-model, alignment, fine-tuning

### Hi Robot: Open-Ended Instruction Following with Hierarchical Vision-Language-Action Models

- **作者：** Lucy Xiaoyang Shi, brian ichter, Michael Equi, Liyiming Ke, Karl Pertsch, Quan Vuong, James Tanner, Anna Walling, Haohuan Wang, Niccolo Fusai, Adrian Li, Danny Driess, Lachy Groom, Sergey Levine, Chelsea Finn
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=lNVHg9npif
- **中文提要：** 开放环境中的通用机器人既要规划完成目标的步骤，也要在执行过程中处理复杂指令、提示和反馈。Hi Robot 用分层的视觉—语言—动作模型来跟随这类开放式指令。
- **关键词：** instruction-following

### HPS: Hard Preference Sampling for Human Preference Alignment

- **作者：** Xiandong Zou, Wanyu LIN, Yuchen Li, Pan Zhou
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=hLvWwRZkok
- **中文提要：** 让大语言模型的回答对齐人类偏好，对构建安全可控的系统很重要。基于 Plackett-Luce 和 Bradley-Terry 的偏好优化在有害内容、负向回答的利用以及 PL 的计算开销上仍有困难，HPS 改用硬偏好采样。
- **关键词：** RLHF, preference-optimization, alignment

### Improving Reward Model Generalization from Adversarial Process Enhanced Preferences

- **作者：** Zhilong Zhang, Tian Xu, Xinghao Du, Xingchen Cao, Yihao Sun, Yang Yu
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=2FGpL5Nd4C
- **中文提要：** 序贯决策里，奖励函数是引导期望行为的主要监督，但传统奖励建模高度依赖人类经验，难以扩展。作者利用对抗过程增强的偏好来改善奖励模型的泛化。
- **关键词：** reward-model

### In-Context Fine-Tuning for Time-Series Foundation Models

- **作者：** Matthew Faw, Rajat Sen, Yichen Zhou, Abhimanyu Das
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=uxzgGLWPj2
- **中文提要：** 针对时间序列基础模型在零样本预测上的进展，作者提出推理时的上下文微调：预训练模型接受多条时间序列示例作为提示，再对目标序列做未来预测。
- **关键词：** fine-tuning

### InfAlign: Inference-aware language model alignment

- **作者：** Ananth Balashankar, Ziteng Sun, Jonathan Berant, Jacob Eisenstein, Michael Collins, Adrian Hutter, Jong Lee, Chirag Nagpal, Flavien Prost, Aradhana Sinha, Ananda Suresh, Ahmad Beirami
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=hInfvt7c4p
- **中文提要：** 对齐通常希望提高对齐模型相对基座模型的胜率，但实际解码越来越多地使用 Best-of-N、受控解码或树搜索，而不再是普通采样。作者指出这种训练与测试的不一致会影响标准 RLHF，并提出对推理过程有感知的对齐方法 InfAlign。
- **关键词：** RLHF, alignment

### InfoSAM: Fine-Tuning the Segment Anything Model from An Information-Theoretic Perspective

- **作者：** Yuanhong Zhang, Muyao Yuan, Weizhan Zhang, Tieliang Gong, Wen Wen, Jiangyong Ying, Weijie Shi
- **会议：** ICML 2025 · Main · Spotlight
- **官方论文页：** https://openreview.net/forum?id=VpBBw1bL47
- **中文提要：** 视觉基础模型 SAM 在通用任务上零样本能力突出，到了专门领域却表现吃力。PEFT 被视为释放其新场景潜力的途径，InfoSAM 从信息论角度对它做微调。
- **关键词：** PEFT, fine-tuning

### Instruction-Following Pruning for Large Language Models

- **作者：** Bairu Hou, Qibin Chen, Jianyu Wang, Guoli Yin, Chong Wang, Nan Du, Ruoming Pang, Shiyu Chang, Tao Lei
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=juARG7yu4P
- **中文提要：** 结构化剪枝常用来从更大的语言模型得到更高效的小模型，并优于同等规模从头训练。作者不再为模型确定固定的剪枝掩码，而提出随指令跟随的动态结构化剪枝。
- **关键词：** instruction-following

### IntLoRA: Integral Low-rank Adaptation of Quantized Diffusion Models

- **作者：** Hang Guo, Yawei Li, Tao Dai, Shutao Xia, Luca Benini
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=K3QoqobsiR
- **中文提要：** 在有限预算下微调预训练扩散模型已经颇有成效，直接用 LoRA 微调量化权重还能进一步降低训练成本。IntLoRA 研究量化扩散模型上的积分式低秩适应。
- **关键词：** LoRA, post-training, fine-tuning

### Invariance Makes LLM Unlearning Resilient Even to Unanticipated Downstream Fine-Tuning

- **作者：** Changsheng Wang, Yihua Zhang, jinghan jia, Parikshit Ram, Dennis Wei, Yuguang Yao, Soumyadeep Pal, Nathalie Baracaldo, Sijia Liu
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=x2lm33kdrZ
- **中文提要：** 机器遗忘希望有选择地移除大语言模型中的目标数据或知识，同时保留模型实用性，但现有方法对下游微调过于敏感，本应忘掉的信息仍可能被迅速恢复。作者借助不变性，使遗忘即使面对未预料到的下游微调也更稳健。
- **关键词：** preference-optimization, fine-tuning

### Is Best-of-N the Best of Them? Coverage, Scaling, and Optimality in Inference-Time Alignment

- **作者：** Audrey Huang, Adam Block, Qinghua Liu, Nan Jiang, Akshay Krishnamurthy, Dylan Foster
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=QnjfkhrbYK
- **中文提要：** 增加推理时计算有助于语言模型对齐，但像 Best-of-N 那样简单放大采样，可能因奖励黑客而变差。为理解如何利用额外计算，作者把推理时对齐形式化为改进预训练策略的回答，并讨论覆盖、扩展与最优性。
- **关键词：** reward-model, alignment

### Joint Localization and Activation Editing for Low-Resource Fine-Tuning

- **作者：** Wen Lai, Alexander Fraser, Ivan Titov
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Lllg9YjAFX
- **中文提要：** LoRA 等 PEFT 方法常用来适配大语言模型，但在样本很少的低资源场景中效果有限。作者通过联合的定位与激活编辑来做这种微调。
- **关键词：** LoRA, PEFT, fine-tuning

### Just Enough Shifts: Mitigating Over-Refusal in Aligned Language Models with Targeted Representation Fine-Tuning

- **作者：** Mahavir Dabas, Si Chen, Charles Fleming, Ming Jin, Ruoxi Jia
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=TiYOHdK35L
- **中文提要：** 安全对齐让大语言模型拒绝恶意指令，却也经常过度拒绝无害提示，损害使用体验和模型效用。ACTOR 是一种计算和数据都较节省的训练框架，借助激活来减少过度拒绝。
- **关键词：** alignment, fine-tuning

### Large Language Models to Diffusion Finetuning

- **作者：** Edoardo Cetin, Tianyu Zhao, Yujin Tang
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=6WBca6adox
- **中文提要：** 一种新的微调方法让预训练语言模型借助扩散框架扩展测试时计算。增加扩散步数后，微调模型的准确率单调上升，并转化为下游任务上的更好表现。
- **关键词：** fine-tuning

### Larger or Smaller Reward Margins to Select Preferences for LLM Alignment?

- **作者：** Kexin Huang, Junkang Wu, Ziqian Chen, xue wang, Jinyang Gao, Bolin Ding, Jiancan Wu, Xiangnan He, Xiang Wang
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ncTwQagrj8
- **中文提要：** 偏好学习对大语言模型对齐很关键，偏好数据的质量尤其重要；现有指标往往只看显式或隐式奖励间隔中的一种，对同一批数据会给出互相矛盾的评价。作者为此提出一种新的度量，用来选择对齐所用的偏好。
- **关键词：** alignment

### Latent Preference Coding: Aligning Large Language Models via Discrete Latent Codes

- **作者：** Zhuocheng Gong, Jian Guan, Wei Wu, Huishuai Zhang, Dongyan Zhao
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ZWZLYVFgDL
- **中文提要：** 把大语言模型的生成对齐到人类偏好仍然困难；现有偏好建模多依赖显式或隐式奖励函数，忽略了偏好在不同任务和人群中可能相互冲突。潜在偏好编码改用离散潜变量码来完成对齐。
- **关键词：** DPO, SimPO, alignment

### Learn from Downstream and Be Yourself in Multimodal Large Language Models Fine-Tuning

- **作者：** Wenke Huang, Jian Liang, Zekun Shi, Didi Zhu, Guancheng Wan, He Li, Bo Du, Dacheng Tao, Mang Ye
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=FKqmIAnkrb
- **中文提要：** 多模态大模型凭借大规模预训练，能在多样分布和任务上泛化，针对特定下游任务做微调也已很常见。作者讨论微调时如何向下游学习，同时保持模型自身的特性。
- **关键词：** fine-tuning

### Learning Dynamics in Continual Pre-Training for Large Language Models

- **作者：** Xingjin Wang, Howe Tissue, Lu Wang, Linjing Li, Daniel Zeng
- **会议：** ICML 2025 · Main · Spotlight
- **官方论文页：** https://openreview.net/forum?id=Vk1rNMl0J1
- **中文提要：** 持续预训练常被用来把基础模型接到特定下游任务上。作者考察大语言模型在持续预训练过程中的学习动态。
- **关键词：** continued-pretraining

### Learning from others' mistakes: Finetuning machine translation models with span-level error annotations

- **作者：** Lily Zhang, Hamid Dadkhahi, Mara Finkelstein, Firas Trabelsi, Jiaming Luo, Markus Freitag
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=BDaMEdNejx
- **中文提要：** 用反馈改进语言模型的工作大多只使用序列级标注。作者探索利用离线数据中更细的片段级错误标注来微调机器翻译模型。
- **关键词：** DPO, SFT, preference-optimization, fine-tuning

### LensLLM: Unveiling Fine-Tuning Dynamics for LLM Selection

- **作者：** Xinyue Zeng, Haohui Wang, Junhong Lin, Jun Wu, Tyler Cody, Dawei Zhou
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=om0CcjvEQh
- **中文提要：** 开源大语言模型和下游任务都很多，受计算限制又不可能把候选模型全部微调一遍，因此需要高效选型。LensLLM 试图刻画微调过程中的动态行为，以改进大模型选择。
- **关键词：** fine-tuning

### LIFT the Veil for the Truth: Principal Weights Emerge after Rank Reduction for Reasoning-Focused Supervised Fine-Tuning

- **作者：** Zihang Liu, Tianyu Pang, Oleg Balabanov, Chaoqun Yang, Tianjin Huang, Lu Yin, Yaoqing Yang, Shiwei Liu
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=XHHIZNgrho
- **中文提要：** 在少量高质量数据上做监督微调，就能让大语言模型获得较强推理能力；全量微调虽然有力，但计算昂贵，数据有限时还容易过拟合和灾难性遗忘。LIFT 关注降秩之后浮现的主权重，用于面向推理的监督微调。
- **关键词：** SFT, LoRA, PEFT, fine-tuning

### LLM Alignment as Retriever Optimization: An Information Retrieval Perspective

- **作者：** Bowen Jin, Jinsung Yoon, Zhen Qin, Ziqi Wang, Wei Xiong, Yu Meng, Jiawei Han, Sercan Arik
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=K1LcmG2jQN
- **中文提要：** 大语言模型在推理、编程和交流上的能力，仍取决于能否通过对齐保证正确、可信和合乎伦理，以应对错误信息、幻觉、偏见和滥用。作者从信息检索视角把对齐看成检索器优化。
- **关键词：** preference-optimization, reward-model, alignment

### LOGO --- Long cOntext aliGnment via efficient preference Optimization

- **作者：** Zecheng Tang, Zechen Sun, Juntao Li, Zhu Qiaoming, Min Zhang
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=vVEBtDDSA6
- **中文提要：** 长上下文模型已经能够方便地处理很长的输入，近期研究还指出它们可以在上下文中定位 token 级的显著信息。LOGO 通过高效的偏好优化来做长上下文对齐。
- **关键词：** instruction-tuning, preference-optimization, alignment

### LoRA-Gen: Specializing Large Language Model via Online LoRA Generation

- **作者：** Yicheng Xiao, Lin Song, Rui Yang, Cheng Cheng, Yixiao Ge, Xiu Li, Ying Shan
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=oZM5g4IvmS
- **中文提要：** 扩大语言模型规模有助于提升各类自然语言任务的表现，但用到领域特定任务、尤其是小型端侧模型时，效果和效率仍受限制。
- **关键词：** LoRA, fine-tuning

### LoRA-One: One-Step Full Gradient Could Suffice for Fine-Tuning Large Language Models, Provably and Efficiently

- **作者：** Yuanhe Zhang, Fanghui Liu, Yudong Chen
- **会议：** ICML 2025 · Main · Oral
- **官方论文页：** https://openreview.net/forum?id=KwIlvmLDLm
- **中文提要：** 以大语言模型中的 LoRA 为案例，作者考察理论如何指导并改进实用算法，并严格证明：梯度下降下，LoRA 适配器会与一步全量微调梯度的特定奇异子空间对齐。
- **关键词：** LoRA, alignment, fine-tuning

### LoRA Training Provably Converges to a Low-Rank Global Minimum Or It Fails Loudly (But it Probably Won't Fail)

- **作者：** Junsu Kim, Jaeyeon Kim, Ernest Ryu
- **会议：** ICML 2025 · Main · Spotlight
- **官方论文页：** https://openreview.net/forum?id=o9zDYV4Ism
- **中文提要：** LoRA 已成为微调大型基础模型的常用手段，但训练动态的理论认识仍然有限：既有分析要么依赖线性化论证，要么只考虑高度简化的设定。
- **关键词：** LoRA, fine-tuning

### LowRA: Accurate and Efficient LoRA Fine-Tuning of LLMs under 2 Bits

- **作者：** Zikai Zhou, Qizheng Zhang, Hermann Kumbong, Kunle Olukotun
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Fm0nDMKBwC
- **中文提要：** 模型规模上升后，微调成本随之增加，即便 LoRA 这类 PEFT 仍然耗费资源。LowRA 优化细粒度量化里的映射与阈值选择等环节，以便在更低比特下做 LoRA 微调。
- **关键词：** LoRA, PEFT, fine-tuning

### Make LoRA Great Again: Boosting LoRA with Adaptive Singular Values and Mixture-of-Experts Optimization Alignment

- **作者：** Chenghao Fan, zhenyi lu, Sichen Liu, Chengfeng Gu, Xiaoye Qu, Wei Wei, Yu Cheng
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=SUxq4HeIAd
- **中文提要：** LoRA 能对大语言模型做参数高效微调，表现却常常不及全量微调。现有方法用静态奇异值分解的子集来初始化，因而难以充分利用预训练知识。
- **关键词：** LoRA, PEFT, alignment, fine-tuning

### $\mathcal{V}ista\mathcal{DPO}$: Video Hierarchical Spatial-Temporal Direct Preference Optimization for Large Video Models

- **作者：** Haojian Huang, Haodong Chen, Shengqiong Wu, Meng Luo, Jinlan Fu, Xinya Du, Hanwang Zhang, Hao Fei
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=O2jukIZR50
- **中文提要：** 建在大语言模型之上的大型视频模型在视频理解上已有潜力，但常与人类直觉不对齐，并出现视频幻觉。VistaDPO 提出视频分层时空直接偏好优化来处理这些问题。
- **关键词：** DPO, preference-optimization, alignment

### MMedPO: Aligning Medical Vision-Language Models with Clinical-Aware Multimodal Preference Optimization

- **作者：** Kangyu Zhu, Peng Xia, Yun Li, Hongtu Zhu, Sheng Wang, Huaxiu Yao
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=e6vlZdLlIK
- **中文提要：** 大型视觉语言模型推动了医学应用，但医学视觉语言模型会因模态错位而偏向文本知识、轻视视觉输入，从而产生与医学图像相矛盾的幻觉。
- **关键词：** preference-optimization, alignment

### MM-RLHF: The Next Step Forward in Multimodal LLM Alignment

- **作者：** Yi-Fan Zhang, Tao Yu, Haochen Tian, Chaoyou Fu, Peiyan Li, Jianshu Zeng, Wulin Xie, Yang Shi, Huanyu Zhang, Junkang Wu, xue wang, Yibo Hu, Bin Wen, Tingting Gao, Zhang Zhang, Fan Yang, Di ZHANG, Liang Wang, Rong Jin
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ULJ4gJJYFp
- **中文提要：** 让多模态大语言模型对齐人类偏好的尝试，多停留在抑制幻觉等狭窄方向，实用性与泛化仍然有限。MM-RLHF 为此提供细粒度、由人工标注的偏好比较数据。
- **关键词：** RLHF, reward-model, alignment

### MPO: An Efficient Post-Processing Framework for Mixing Diverse Preference Alignment

- **作者：** Tianze Wang, Dongnan Gui, Yifan Hu, Shuhang Lin, Linjun Zhang
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=8Tj02fPeYH
- **中文提要：** RLHF 在对齐大语言模型上已显出潜力，可它对单一奖励模型的依赖往往会忽略人类偏好的多样性。
- **关键词：** RLHF, preference-optimization, reward-model, alignment, fine-tuning

### NICE Data Selection for Instruction Tuning in LLMs with Non-differentiable Evaluation Metric

- **作者：** Jingtan Wang, Xiaoqiang Lin, Rui Qiao, Pang Wei Koh, Chuan-Sheng Foo, Bryan Kian Hsiang Low
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=2wt8m5HUBs
- **中文提要：** 为指令微调挑选数据，对提升大语言模型的表现至关重要。这项工作的目标，是选出能改善模型在特定任务上表现的训练数据。
- **关键词：** instruction-tuning, reward-model

### OmniBal: Towards Fast Instruction-Tuning for Vision-Language Models via Omniverse Computation Balance

- **作者：** Yongqiang Yao, Jingru Tan, Feizhao Zhang, Jiahao Hu, Yazhe Niu, JinXin, Bo Li, Pengfei Liu, Ruihao Gong, Dahua Lin, Ningyi Xu
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=q6f9Fg9LHe
- **中文提要：** 视觉语言指令微调模型近来进步明显，但在这些模型上做大规模三维并行训练时，不同设备之间的计算负载会出现失衡。
- **关键词：** instruction-tuning

### On the Robustness of Reward Models for Language Model Alignment

- **作者：** Jiwoo Hong, Noah Lee, Eunki Kim, Guijin Son, Woojin Chung, Aman Gupta, Shao Tang, James Thorne
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Tf4lRAOGkj
- **中文提要：** Bradley-Terry 模型被广泛用于 RLHF 中的奖励建模。把 BT 损失当作单向分类器来训练奖励模型时，容易过度优化，并对未见输入失去泛化能力。
- **关键词：** RLHF, reward-model, alignment

### Optimizing Test-Time Compute via Meta Reinforcement Finetuning

- **作者：** Yuxiao Qu, Matthew Yang, Amrith Setlur, Lewis Tunstall, Edward Beeching, Russ Salakhutdinov, Aviral Kumar
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=TqODUDsU4u
- **中文提要：** 训练模型高效使用测试时计算，对提升大语言模型的推理表现很关键。现有途径多是在搜索轨迹上微调，或针对二元结果奖励做强化学习，它们是否真正用好了测试时计算仍是疑问。
- **关键词：** RFT, fine-tuning

### Overtrained Language Models Are Harder to Fine-Tune

- **作者：** Jacob Mitchell Springer, Sachin Goyal, Kaiyue Wen, Tanishq Kumar, Xiang Yue, Sadhika Malladi, Graham Neubig, Aditi Raghunathan
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=YW6edSufht
- **中文提要：** 预训练所用词元预算不断增长，背后假定更好的预训练表现会带来更强的下游模型。延长预训练却可能让模型更难微调，并导致最终表现下降。
- **关键词：** instruction-tuning, fine-tuning

### Parameter-Efficient Fine-Tuning of State Space Models

- **作者：** Kevin Galim, Wonjun Kang, Yuchen Zeng, HYUNG IL KOO, Kangwook Lee
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=64mHSb9DlQ
- **中文提要：** 以 Mamba 为代表的深度状态空间模型适合语言建模，性能高且计算随序列长度线性扩展。把 PEFT 用到基于状态空间模型的网络上，目前仍很少被研究。
- **关键词：** LoRA, PEFT, fine-tuning

### PARM: Multi-Objective Test-Time Alignment via Preference-Aware Autoregressive Reward Model

- **作者：** Baijiong Lin, Weisen Jiang, Yuancheng Xu, Hao Chen, YINGCONG CHEN
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=zm53HtGiXN
- **中文提要：** 多目标测试时对齐希望在推理阶段适配多维用户偏好，同时保持大语言模型冻结。GenARM 先为每个偏好维度独立训练互不知情的自回归奖励模型，再按用户偏好向量在推理时组合它们的输出。
- **关键词：** reward-model, LoRA, alignment

### Parrot: Multilingual Visual Instruction Tuning

- **作者：** Hai-Long Sun, Da-Wei Zhou, Yang Li, Shiyin Lu, Chao Yi, Qing-Guo Chen, Zhao Xu, Weihua Luo, Kaifu Zhang, De-Chuan Zhan, Han-Jia Ye
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Yx0bl5OFvc
- **中文提要：** 现有多模态大语言模型通常用 SFT 把视觉编码器与语言模型对齐，但随着训练推进，处理多种语言的能力往往会下降。
- **关键词：** SFT, instruction-tuning, alignment, fine-tuning

### PILAF: Optimal Human Preference Sampling for Reward Modeling

- **作者：** Yunzhen Feng, Ariel Kwiatkowski, Kunhao Zheng, Julia Kempe, Yaqi Duan
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Qap9pHIkI8
- **中文提要：** 大语言模型越来越多地进入实际应用，与人类价值对齐因此变得重要。当无法直接获得人类价值的真值时，RLHF 把偏好数据转化成奖励模型。
- **关键词：** RLHF, reward-model, alignment

### PIPA: Preference Alignment as Prior-Informed Statistical Estimation

- **作者：** Junbo Li, Zhangyang “Atlas” Wang, qiang liu
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=XFz3EJS8RW
- **中文提要：** DPO 一类离线偏好对齐因为有效、简单，且不必做昂贵的强化学习而受到青睐。面向不同数据设定已有多种离线算法，却缺少统一的理解。
- **关键词：** DPO, KTO, preference-optimization, alignment

### PISA Experiments: Exploring Physics Post-Training for Video Diffusion Models by Watching Stuff Drop

- **作者：** Chenyu Li, Oscar Michel, Xichen Pan, Sainan Liu, Mike Roberts, Saining Xie
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=RFCp1QzzHQ
- **中文提要：** 大规模预训练的视频生成模型擅长内容创作，却不能直接当作物理上准确的世界模拟器。作者以物体自由落体这一基础物理任务为视角，研究如何后训练这些模型以做准确的世界建模。
- **关键词：** reward-model, post-training, fine-tuning

### Policy Filtration for RLHF to Mitigate Noise in Reward Models

- **作者：** Chuheng Zhang, Wei Shen, Li Zhao, Xuyun Zhang, Xiaolong Xu, Wanchun Dou, Jiang Bian
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=L8hYdTQVcs
- **中文提要：** 尽管已有直接的策略优化方法，早期大语言模型仍借助从偏好数据学到的奖励模型，用 RLHF 微调以生成更好的回复。中间奖励模型不准确是 RLHF 的主要难点，在评分本身需要复杂推理的任务上尤其如此。
- **关键词：** RLHF, reward-model, fine-tuning

### Policy-labeled Preference Learning: Is Preference Enough for RLHF?

- **作者：** Taehyun Cho, Seokhun Ju, Seungyub Han, Dohyeong Kim, Kyungjae Lee, Jungwoo Lee
- **会议：** ICML 2025 · Main · Spotlight
- **官方论文页：** https://openreview.net/forum?id=qLfo1sef50
- **中文提要：** RLHF 从人类偏好学习奖励函数，再用强化学习算法优化模型，以使奖励符合人类目标。现有方法常常把轨迹误当成由最优策略生成，造成似然估计不准，学习也随之次优。
- **关键词：** DPO, RLHF, preference-optimization

### POROver: Improving Safety and Reducing Overrefusal in Large Language Models with Overgeneration and Preference Optimization

- **作者：** Batuhan K. Karaman, ishmam zabir, Alon Benhaim, Vishrav Chaudhary, Mert Sabuncu, Xia Song
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=pUWYuwUkqE
- **中文提要：** 同时兼顾高安全与高有用，是大语言模型近年的关键难题：模型要么出现不安全行为，要么过于谨慎，频繁拒绝无害提示。这些行为与微调和对齐的方式密切相关，尤其取决于对齐的性质与程度。
- **关键词：** instruction-following, preference-optimization, alignment, fine-tuning

### Portable Reward Tuning: Towards Reusable Fine-Tuning across Different Pretrained Models

- **作者：** Daiki Chijiwa, Taku Hasegawa, Kyosuke Nishida, Kuniko Saito, Susumu Takeuchi
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=cYNBsMTAVL
- **中文提要：** 基础模型靠微调参数承担各种专家任务，但终会因知识陈旧或能力有限而过时，需要被新的基础模型替换。要享用新模型更新的知识或更强能力，又得在每个任务上重新微调，由此产生额外代价。
- **关键词：** reward-model, fine-tuning

### Preference Optimization for Combinatorial Optimization Problems

- **作者：** Mingjun Pan, Guanquan Lin, You-Wei Luo, Bin Zhu, Zhien Dai, Lijun Sun, Chun Yuan
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Jwe5FJ8QGx
- **中文提要：** 强化学习成为神经组合优化的有力工具，使模型不必依赖专家知识就能学会求解复杂问题的启发式。奖励信号衰减，以及在巨大组合动作空间中探索低效，仍使现有方法效率不高。
- **关键词：** preference-optimization, fine-tuning

### Progressively Label Enhancement for Large Language Model Alignment

- **作者：** Biao Liu, Ning Xu, Xin Geng
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=8prLgZ0vmm
- **中文提要：** 大语言模型对齐要避免生成偏离人类预期、进而带来伦理与法律问题的内容。近些年里，RLHF 一直是实现这种对齐最主要的方法。
- **关键词：** RLHF, alignment

### Projection Optimization: A General Framework for Multi-Objective and Multi-Group RLHF

- **作者：** Nuoya Xiong, Aarti Singh
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=xHhURhYmgK
- **中文提要：** RLHF 是广泛使用的微调途径，用来让机器学习模型、尤其是语言模型符合人类偏好。驱动偏好的目标通常不止一个，因此人更容易按单个目标做比较，而不是在两个选项之间给出总体偏好。
- **关键词：** RLHF, fine-tuning

### Promoting Ensemble Diversity with Interactive Bayesian Distributional Robustness for Fine-tuning Foundation Models

- **作者：** Ngoc Quan Pham, Tuan Truong, Quyen Tran, Tan Nguyen, Dinh Phung, Trung Le
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=yTWqL3XHCC
- **中文提要：** IBDR 是一种贝叶斯推断框架，能够刻画粒子之间的相互作用，并借更高的粒子多样性来提升集成质量。它依托一套把分布总体损失与近似后验联系起来的广义理论，并由此引出实用的对偶优化。
- **关键词：** fine-tuning

### Proxy-FDA: Proxy-based Feature Distribution Alignment for Fine-tuning Vision Foundation Models without Forgetting

- **作者：** Chen Huang, Skyler Seto, Hadi Pouransari, Mehrdad Farajtabar, Raviteja Vemulapalli, Fartash Faghri, Oncel Tuzel, Barry-John Theobald, Joshua M Susskind
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=TfB7AHM2bJ
- **中文提要：** 在海量数据上预训练的视觉基础模型编码了丰富的现实概念，微调后可以适配下游任务。只针对一个任务微调，却常常造成其他任务上的概念遗忘。
- **关键词：** alignment, fine-tuning

### Quantifying Prediction Consistency Under Fine-tuning Multiplicity in Tabular LLMs

- **作者：** Faisal Hamman, Sachindra P Dissanayake, Saumitra Mishra, Freddy Lecue, Sanghamitra Dutta
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=AXJnqocQpm
- **中文提要：** 把大语言模型微调到表格分类上，会出现微调多重性：表现同样好的模型对同一输入给出互相冲突的预测。随机种子、权重初始化或训练数据的细微改动都可能引发这一现象，并牵动高风险场景下表格大语言模型是否可靠。
- **关键词：** fine-tuning

### RATE: Causal Explainability of Reward Models with Imperfect Counterfactuals

- **作者：** David Reber, Sean Richardson, Todd Nief, Cristina Garbacea, Victor Veitch
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=rL3uxe5a0c
- **中文提要：** 对齐或评测大语言模型时，奖励模型常被当作人类偏好的代理，可它们是黑箱，究竟在奖励什么并不清楚。RATE 以基于改写的属性处理估计，衡量奖励模型对回复高层属性（如情感）的敏感程度。
- **关键词：** reward-model, alignment

### Reasoning Through Execution: Unifying Process and Outcome Rewards for Code Generation

- **作者：** Zhuohao Yu, Weizheng Gu, Yidong Wang, Xingru Jiang, Zhengran Zeng, Jindong Wang, Wei Ye, Shikun Zhang
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=pLQtovjXiw
- **中文提要：** 大语言模型擅长生成代码，却难以完成需要精细推理的复杂编程任务。过程监督依赖训练代价高、且容易奖励错位的奖励模型，结果监督又应付不了必须协调中间步骤的任务。
- **关键词：** reward-model

### Reinforcement Learning with Adaptive Reward Modeling for Expensive-to-Evaluate Systems

- **作者：** Hongyuan Su, Yu Zheng, Yuan Yuan, Yuming Lin, Depeng Jin, Yong Li
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=tI04pBsIbq
- **中文提要：** 训练强化学习智能体需要大量试错，而在奖励评估很贵的系统里，这会变得过于耗时。AdaReMo 把复杂奖励函数分解成多个局部的快速奖励模型，用神经模型近似直接的奖励评估，从而加快训练。
- **关键词：** reward-model

### RepLoRA: Reparameterizing Low-rank Adaptation via the Perspective of Mixture of Experts

- **作者：** Tuan Truong, Chau Nguyen, Huy Nguyen, Minh Le, Trung Le, Nhat Ho
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Sg8ZqQ9J6W
- **中文提要：** LoRA 已是微调大规模基础模型的高效方法，尽管使用广泛，其理论认识仍然不足。
- **关键词：** LoRA, PEFT, fine-tuning

### Restoring Calibration for Aligned Large Language Models: A Calibration-Aware Fine-Tuning Approach

- **作者：** Jiancong Xiao, Bojian Hou, Zhanliang Wang, Ruochen Jin, Qi Long, Weijie Su, Li Shen
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=51tMpvPNSm
- **中文提要：** 偏好对齐是大语言模型成功的关键技术之一，明显的副作用却是校准变差：预训练模型通常校准良好，与人类偏好对齐之后往往不再如此。
- **关键词：** preference-optimization, alignment, fine-tuning

### Reward-Augmented Data Enhances Direct Preference Alignment of LLMs

- **作者：** Shenao Zhang, Zhihan Liu, Boyi Liu, Yufeng Zhang, Yingxiang Yang, Yongfei Liu, Liyu Chen, Tao Sun, Zhaoran Wang
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ruvzyT9HqJ
- **中文提要：** 偏好对齐明显增强了大语言模型遵循人类指令与意图的能力。现有直接对齐算法主要关注相对偏好，却常常忽略回复的质量层面，即便 AI 反馈里的偏好数据已经带有评判模型给出的奖励分数。
- **关键词：** DPO, preference-optimization, alignment

### Reward Modeling with Ordinal Feedback: Wisdom of the Crowd

- **作者：** Shang Liu, Yu Pan, Guanting Chen, Xiaocheng Li
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=2JRrmzPQSc
- **中文提要：** 用二元反馈从人类偏好学习奖励模型，会丢掉“打平”这类可能有用的样本，也会损失“略好一些”这样的细粒度信息。文中提出在序数反馈下学习奖励模型的框架，把二元反馈推广到任意粒度。
- **关键词：** reward-model

### Right Now, Wrong Then: Non-Stationary Direct Preference Optimization under Preference Drift

- **作者：** Seongho Son, William Bankes, Sayak Ray Chowdhury, Brooks Paige, Ilija Bogunovic
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=c2xhvZA8Xq
- **中文提要：** 当前的大语言模型偏好优化算法不考虑偏好随时间漂移，因而可能造成严重错位。NS-DPO 用动态 Bradley-Terry 模型来刻画随时间变化的奖励函数。
- **关键词：** DPO, preference-optimization, reward-model, fine-tuning

### RLTHF: Targeted Human Feedback for LLM Alignment

- **作者：** Yifei Xu, Tusher Chakraborty, Emre Kiciman, Bibek Aryal, Srinagesh Sharma, Songwu Lu, Ranveer Chandra
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ATUfSZayVo
- **中文提要：** 高质量人工标注成本高，AI 反馈的泛化又有限，使大语言模型通过对齐贴合用户偏好变得困难。RLTHF 是人机混合框架，把基于大语言模型的初始对齐和有选择的人工标注结合起来。
- **关键词：** RLHF, reward-model, alignment, fine-tuning

### ROPO: Robust Preference Optimization for Large Language Models

- **作者：** Xize Liang, Chao Chen, Shuang Qiu, Jie Wang, Yue Wu, Zhihang Fu, Hanzhu Chen, Feng Wu, Jieping Ye
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=5WEmyTooVV
- **中文提要：** 偏好数据里普遍存在的噪声，给大语言模型的偏好对齐带来显著挑战。已有处理要么只是略微减轻噪声影响而不真正降噪，要么依赖外部大语言模型并付出很高的计算成本。
- **关键词：** preference-optimization, alignment

### RoSTE: An Efficient Quantization-Aware Supervised Fine-Tuning Approach for Large Language Models

- **作者：** Quan Wei, Chung-Yiu Yau, Hoi To Wai, Yang Zhao, Dongyeop Kang, Youngsuk Park, Mingyi Hong
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=h30EzoI3s0
- **中文提要：** 监督微调是把预训练大语言模型适配到下游任务的常规方法。量化近来则被作为训练之后的技术，用来更高效地部署大语言模型。
- **关键词：** SFT, post-training, fine-tuning

### RuleAdapter: Dynamic Rules for training Safety Reward Models in RLHF

- **作者：** Xiaomin Li, Mingye Gao, Zhiwei Zhang, Jingxuan Fan, Weiyu Li
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=tcMWVgYf8f
- **中文提要：** RLHF 被广泛用来让模型符合人类偏好，尤其是提高大语言模型所生成回复的安全性。传统上，它依赖从回复对中选出更受偏好的一方。
- **关键词：** RLHF, reward-model

### Safe Delta: Consistently Preserving Safety when Fine-Tuning LLMs on Diverse Datasets

- **作者：** Ning LU, Shengcai Liu, Jiahao Wu, Weiyu CHEN, Zhirui Zhang, Yew Soon ONG, Qi Wang, Ke Tang
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=QsCDgFKErb
- **中文提要：** 大语言模型有潜力成为跨领域的通用人工智能助手。为在具体应用中发挥这一潜力，许多公司提供微调接口，允许用户上传自己的数据来定制模型。
- **关键词：** post-training, alignment, fine-tuning

### SAN: Hypothesizing Long-Term Synaptic Development and Neural Engram Mechanism in Scalable Model's Parameter-Efficient Fine-Tuning

- **作者：** Gaole Dai, Chun-Kai Fan, Yiming Tang, Zhi Zhang, Yuan Zhang, Yulu Gan, Qizhe Zhang, Cheng-Ching Tseng, Shanghang Zhang, Tiejun Huang
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=CeTXRRAdFi
- **中文提要：** PEFT 通过对预训练参数空间的细致分析，缩小了与全量微调之间的性能差距。从生物神经网络中的神经印迹得到启发后，作者把 PEFT 参数空间迁移时观察到的低秩性质与神经生物机制联系起来。
- **关键词：** instruction-tuning, LoRA, PEFT, fine-tuning

### Scaling Laws for Forgetting during Finetuning with Pretraining Data Injection

- **作者：** Louis Béthune, David Grangier, Dan Busbridge, Eleonora Gualdoni, Marco Cuturi, Pierre Ablin
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=vWMij23BmQ
- **中文提要：** 要得到在目标领域表现好的语言模型，常见做法是在该领域数据上对预训练模型做无监督的下一词预测微调。目标数据有限时模型会很快过拟合，同时还会偏离其原先的预训练。
- **关键词：** fine-tuning

### SeedLoRA: A Fusion Approach to Efficient LLM Fine-Tuning

- **作者：** Yong Liu, Di Fu, Shenggan Cheng, Zirui Zhu, Yang Luo, Minhao Cheng, Cho-Jui Hsieh, Yang You
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=7QH48TtFZX
- **中文提要：** LoRA 虽常用于微调大模型，但与全量微调仍有明显差距，在数学推理和代码生成这类复杂任务上尤其如此。针对这一落差，作者为经过 LoRA 微调的模型提出一种融合做法。
- **关键词：** instruction-tuning, LoRA, fine-tuning

### SEFE: Superficial and Essential Forgetting Eliminator for Multimodal Continual Instruction Tuning

- **作者：** Jinpeng Chen, Runmin Cong, Yuzhi Zhao, Hongzheng Yang, Guangneng Hu, Horace Ip, Sam Kwong
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=teJdFzLnKh
- **中文提要：** 多模态持续指令微调希望多模态大语言模型能逐步学会新任务而不发生灾难性遗忘，从而适应不断变化的需求。文中考察这种增量训练造成的遗忘，并将其分为表层遗忘与本质遗忘。
- **关键词：** instruction-tuning, LoRA

### Self-Consistency Preference Optimization

- **作者：** Archiki Prasad, Weizhe Yuan, Richard Yuanzhe Pang, Jing Xu, Maryam Fazel-Zarandi, Mohit Bansal, Sainbayar Sukhbaatar, JASON WESTON, Jane Dwivedi-Yu
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=94G4eL3RWi
- **中文提要：** 自我对齐让模型在没有人工标注的情况下自我改进，是发展很快的研究方向。由于很难赋予正确的奖励，现有技术常常无法提升复杂推理任务。
- **关键词：** preference-optimization, reward-model, alignment, fine-tuning

### SFT Memorizes, RL Generalizes: A Comparative Study of Foundation Model Post-training

- **作者：** Tianzhe Chu, Yuexiang Zhai, Jihan Yang, Shengbang Tong, Saining Xie, Dale Schuurmans, Quoc Le, Sergey Levine, Yi Ma
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=dYur3yabMj
- **中文提要：** SFT 和强化学习都是基础模型广泛使用的后训练技术，但它们在增强模型泛化能力上各自扮演什么角色，目前仍不清楚。
- **关键词：** SFT, post-training, fine-tuning

### Sketch to Adapt: Fine-Tunable Sketches for Efficient LLM Adaptation

- **作者：** Tianyi Zhang, Junda Su, Aditya Desai, Oscar Wu, Zhaozhuo Xu, Anshumali Shrivastava
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=zZXOXhxO6I
- **中文提要：** 适配预训练大语言模型很重要，巨大的模型规模却使这件事很困难。PEFT 通常在冻结的模型权重上加入可加适配器。
- **关键词：** LoRA, PEFT, fine-tuning

### Smoothed Preference Optimization via ReNoise Inversion for Aligning Diffusion Models with Varied Human Preferences

- **作者：** Yunhong Lu, Qichao Wang, Hengyuan Cao, Xiaoyin Xu, Min Zhang
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=G3grccIXIg
- **中文提要：** DPO 利用成对偏好数据，把文生图模型对齐到人类偏好。采集和标注尽管投入很大，个体之间偏好不同、因而需要更细粒度表示这一点却常被忽略；SmPO-Diffusion 即是针对该问题提出的建模方法。
- **关键词：** DPO, preference-optimization, reward-model, alignment

### SparseLoRA: Accelerating LLM Fine-Tuning with Contextual Sparsity

- **作者：** Samir Khaki, Xiuyu Li, Junxian Guo, Ligeng Zhu, Konstantinos N (Kostas) Plataniotis, Amir Yazdanbakhsh, Kurt Keutzer, Song Han, Zhijian Liu
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=z83rodY0Pw
- **中文提要：** 微调大语言模型既耗费计算，也耗费显存。QLoRA、DoRA 等参数高效方法减少了可训练参数并降低显存占用，计算成本却并没有因此下降。
- **关键词：** instruction-following, QLoRA, PEFT, fine-tuning

### SPRI: Aligning Large Language Models with Context-Situated Principles

- **作者：** Hongli Zhan, Muneeza Azmat, Raya Horesh, Junyi Jessy Li, Mikhail Yurochkin
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=klw8Ko4ENe
- **中文提要：** 让大语言模型吸收并体现人类价值很费力，需要细致人工监督的任务尤其如此，因为依赖专家提供依情境的指导既耗资源又费时间。先前工作则用预先定义的一套规则或原则来引导模型行为。
- **关键词：** SFT, alignment

### Square$\chi$PO: Differentially Private and Robust $\chi^2$-Preference Optimization in Offline Direct Alignment

- **作者：** Xingyu Zhou, Yulian Wu, Wenqian Weng, Francesco Orabona
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=eWQQPtfJjV
- **中文提要：** 作者从理论上研究语言模型的离线对齐：人类偏好反馈同时面临标签损坏和隐私保护。SquareχPO 是 χPO 的变体，只做一行改动，把标准对数损失换成定义在概率上的平方损失。
- **关键词：** preference-optimization, alignment

### Synthesizing Privacy-Preserving Text Data via Finetuning *without* Finetuning Billion-Scale LLMs

- **作者：** Bowen Tan, Zheng Xu, Eric Xing, Zhiting Hu, Shanshan Wu
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=FCm4laCLiH
- **中文提要：** 合成数据为在保护数据隐私的同时训练模型提供了一条途径。把大语言模型做差分隐私微调并当作数据生成器是有效的，但计算资源有限时并不现实。
- **关键词：** fine-tuning

### Testing the Limits of Fine-Tuning for Improving Visual Cognition in Vision Language Models

- **作者：** Luca M. Schulze Buschoff, Konstantinos Voudouris, Elif Akata, Matthias Bethge, Josh Tenenbaum, Eric Schulz
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=jSxU7ZGe3B
- **中文提要：** 预训练视觉语言模型的视觉认知仍不及人类。为改进视觉认知并让模型更接近人类行为，作者引入视觉刺激以及人在视觉认知任务上的判断，以便在一致环境中系统评估各个认知领域的表现。
- **关键词：** alignment, fine-tuning

### Test-Time Preference Optimization: On-the-Fly Alignment via Iterative Textual Feedback

- **作者：** Yafu Li, Xuyang Hu, Xiaoye Qu, Linjie Li, Yu Cheng
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ArifAHrEVD
- **中文提要：** 大语言模型表现突出，却往往缺少不重新训练就能快速适应人类偏好的灵活性。受测试时扩展的启发，TPO 在推理过程中把输出对齐到人类偏好，从而不必更新模型参数。
- **关键词：** SFT, instruction-following, preference-optimization, alignment

### Text-to-LoRA: Instant Transformer Adaption

- **作者：** Rujikorn Charakorn, Edoardo Cetin, Yujin Tang, Robert Lange
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=zWskCdu3QA
- **中文提要：** 基础模型为快速创作内容提供了通用工具，但经常仍需要针对具体任务做适配。传统上，这包括仔细整理数据集，并反复微调底层模型。
- **关键词：** LoRA, fine-tuning

### TGDPO: Harnessing Token-Level Reward Guidance for Enhancing Direct Preference Optimization

- **作者：** Mingkang Zhu, Xi Chen, Zhongdao Wang, Bei Yu, Hengshuang Zhao, Jiaya Jia
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=TKHWvyzR1t
- **中文提要：** 人类反馈强化学习的近期进展表明，细粒度的词元级奖励模型能明显增强 PPO 在对齐大语言模型时的效果。DPO 被写成序列级赌博机问题，要把这类词元级奖励用作它的指导并不容易。
- **关键词：** DPO, RLHF, preference-optimization, reward-model, alignment

### The Devil Is in the Details: Tackling Unimodal Spurious Correlations for Generalizable Multimodal Reward Models

- **作者：** Zichao Li, Xueru Wen, Jie Lou, Yuqiu Ji, Yaojie Lu, Xianpei Han, Debing Zhang, Le Sun
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=b0qRSUcQP7
- **中文提要：** 多模态奖励模型对把大语言模型对齐到人类偏好至关重要，尤其是在模型越来越多地处理多模态数据的情况下。在现有数据上训练的这类模型往往依赖单模态虚假相关，主要是训练分布内的纯文本捷径，因而难以泛化到分布外数据。
- **关键词：** reward-model, alignment

### The Energy Loss Phenomenon in RLHF: A New Perspective on Mitigating Reward Hacking

- **作者：** Yuchun Miao, Sen Zhang, Liang Ding, Yuqi Zhang, Lefei Zhang, Dacheng Tao
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=82A81az3V5
- **中文提要：** 该研究指出 RLHF 中的能量损失现象，以及它与奖励黑客之间的联系。强化学习过程中，大语言模型最后一层的能量损失逐渐增加，而能量损失的过度增加则刻画了奖励黑客。
- **关键词：** RLHF, reward-model

### The Hidden Dimensions of LLM Alignment: A Multi-Dimensional Analysis of Orthogonal Safety Directions

- **作者：** Wenbo Pan, Zhichao Liu, Qiguang Chen, Xiangyang Zhou, Yu Haining, Xiaohua Jia
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=wGFEzfhFae
- **中文提要：** 安全对齐行为，例如拒绝有害提问，可以表示成激活空间里的线性方向。先前工作只用单一方向刻画安全行为，机制理解因此局限在孤立的安全特征上。
- **关键词：** alignment, fine-tuning

### Thinking LLMs: General Instruction Following with Thought Generation

- **作者：** Tianhao Wu, Janice Lan, Weizhe Yuan, Jiantao Jiao, JASON WESTON, Sainbayar Sukhbaatar
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=z6SrgYCdey
- **中文提要：** 大语言模型通常被训练成像人类专家那样回答问题或遵循指令，但在标准对齐框架里，它们缺少回答前显式思考的基本能力。
- **关键词：** instruction-following, preference-optimization, alignment

### TimeStep Master: Asymmetrical Mixture of Timestep LoRA Experts for Versatile and Efficient Diffusion Models in Vision

- **作者：** Shaobin Zhuang, Yiwei Guo, Yanbo Ding, Kunchang Li, Xinyuan Chen, Yaohui Wang, Fangyikang Wang, Ying Zhang, Chen Li, Yali Wang
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=9mPhtzB9XP
- **中文提要：** 扩散模型这些年推动了视觉生成的进展，可是巨大的微调成本常常让这些大模型难以用到下游任务。
- **关键词：** LoRA, fine-tuning

### Token Cleaning: Fine-Grained Data Selection for LLM Supervised Fine-Tuning

- **作者：** Jinlong Pang, Na Di, Zhaowei Zhu, Jiaheng Wei, Hao Cheng, Chen Qian, Yang Liu
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=tXkOUS3vLS
- **中文提要：** 监督微调（SFT）里，数据质量比数量更要紧。多数清洗方法只过滤整条样本，而同一条样本内部各个 token 的质量可以差很多。
- **关键词：** SFT, fine-tuning

### Towards Understanding Fine-Tuning Mechanisms of LLMs via Circuit Analysis

- **作者：** Xu Wang, Yan Hu, Wenyu Du, Reynold Cheng, Benyou Wang, Difan Zou
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=45EIiFd6Oa
- **中文提要：** 微调能明显改善大语言模型的表现，其内部机制却仍不清楚。该研究打算借助机制可解释性里常用的电路分析，深入解释微调过程。
- **关键词：** LoRA, fine-tuning

### TuCo: Measuring the Contribution of Fine-Tuning to Individual Responses of LLMs

- **作者：** Felipe Nuti, Tim Franzmeyer, Joao Henriques
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=yxoxw0IUTR
- **中文提要：** 以往研究多考察微调对大语言模型在特定任务上整体表现的影响，仍缺少对单条输出做定量、系统分析的途径。在能访问原始预训练模型的前提下，作者提出衡量微调对单条回答贡献的方法。
- **关键词：** fine-tuning

### Understanding Overadaptation in Supervised Fine-Tuning: The Role of Ensemble Methods

- **作者：** Yifan HAO, xingyuan pan, Hanning Zhang, Chenlu Ye, Rui Pan, Tong Zhang
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=1xsW6tvMb3
- **中文提要：** 在领域数据上做监督微调（SFT）是把基础模型适配到专门任务的主流做法，但人们观察到这类模型容易忘掉预训练阶段获得的知识。
- **关键词：** SFT, fine-tuning

### Understanding the Logic of Direct Preference Alignment through Logic

- **作者：** Kyle Richardson, Vivek Srikumar, Ashish Sabharwal
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=4T7gFdhsPJ
- **中文提要：** 以 DPO 为代表的直接偏好对齐算法展现出对齐潜力，并催生出许多相对原始 DPO 损失的变体。比较这些方案以及设计新的对齐损失仍然困难，原因是缺少一套技术与概念框架。
- **关键词：** DPO, preference-optimization, alignment

### Upweighting Easy Samples in Fine-Tuning Mitigates Forgetting

- **作者：** Sunny Sanyal, Hayden Prairie, Rudrajit Das, Ali Kavis, Sujay Sanghavi
- **会议：** ICML 2025 · Main · Spotlight
- **官方论文页：** https://openreview.net/forum?id=13HPTmZKbM
- **中文提要：** 在下游任务上微调预训练模型常常损害其原有能力，这种现象被称为灾难性遗忘。拿不到预训练所用的数据和配方时，问题尤其突出。
- **关键词：** fine-tuning

### VersaPRM: Multi-Domain Process Reward Model via Synthetic Reasoning Data

- **作者：** Thomas Zeng, Shuibai Zhang, Shutong Wu, Christian Classen, Daewon Chae, Ethan Ewer, Minjae Lee, Heeju Kim, Wonjun Kang, Jackson Kunde, Ying Fan, Jungtaek Kim, HYUNG IL KOO, Kannan Ramchandran, Dimitris Papailiopoulos, Kangwook Lee
- **会议：** ICML 2025 · Main · Spotlight
- **官方论文页：** https://openreview.net/forum?id=l19DmXbwPK
- **中文提要：** 过程奖励模型（PRM）通过增加推理时计算来增强大语言模型的数学推理。它们的训练却主要依赖数学数据，向非数学领域的泛化尚未被严格考察。
- **关键词：** PRM, reward-model

### Vulnerability-Aware Alignment: Mitigating Uneven Forgetting in Harmful Fine-Tuning

- **作者：** Liang CHEN, Xueting Han, Li Shen, Jing Bai, Kam-Fai Wong
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=EMHED4WTHT
- **中文提要：** 有害微调无论直接施加于开源大语言模型，还是通过微调即服务进行，都会破坏安全对齐并带来明显威胁。现有方法试图在对齐数据上学稳健表示，或让有害数据不可学习，却同等对待每条样本，数据脆弱性模式因此研究不足。
- **关键词：** alignment, fine-tuning

### What Limits Bidirectional Model's Generative Capabilities? A Uni-Bi-Directional Mixture-of-Expert Method For Bidirectional Fine-tuning

- **作者：** Zuchao Li, Yonghua Hei, Qiwei Li, Lefei Zhang, Ping Wang, hai zhao, qi baoyuan, Liu Guoming
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=kPqvx2mvec
- **中文提要：** 大语言模型擅长生成，因果注意力却限制了嵌入任务上的表现；双向建模或许能改善嵌入，但把单向模型直接做双向微调会严重损害生成能力。为考察这一权衡，作者把注意力权重当作依赖指标加以分析。
- **关键词：** fine-tuning

### WildChat-50M: A Deep Dive Into the Role of Synthetic Data in Post-Training

- **作者：** Benjamin Feuer, Chinmay Hegde
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=fzmtDDOcJ3
- **中文提要：** 语言模型后训练可以改进行为并解锁新技能，但支撑这些技术的开放研究仍处于起步阶段。一个限制因素是，很难对合成数据生成模型和作为评判者的大语言模型做大规模比较分析。
- **关键词：** SFT, post-training

### Zero-Shot Adaptation of Parameter-Efficient Fine-Tuning in Diffusion Models

- **作者：** Farzad Farhadzadeh, Debasmit Das, Shubhankar Borse, Fatih Porikli
- **会议：** ICML 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=osNUbJ4vlX
- **中文提要：** ProLoRA 使文生图扩散模型中的参数高效微调能够零样本适配。它把源模型上已训练的低秩调整（例如 LoRA）迁移到目标模型，且不需要额外训练数据。
- **关键词：** LoRA, PEFT, fine-tuning
