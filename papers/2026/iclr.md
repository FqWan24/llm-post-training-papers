# 2026 · ICLR

共 283 篇。Main 283，Findings 0，其他赛道 0。其中 0 篇来源题录无摘要，提要标明「仅根据标题概括」。

检索窗口为 2024-11-13 至 2026-11-13。题录信息来自官方列表，不在此增补作者、链接或实验数字。

## Main

### ABBA-Adapters: Efficient and Expressive Fine-Tuning of Foundation Models

- **作者：** Raghav Singhal, Kaustubh Ponkshe, Rohit Vartak, Praneeth Vepakomma
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=NvSRYp0oaX
- **中文提要：** 大语言模型跨任务表现强，但高效适应新领域仍是难题。PEFT 的应对是加入轻量、可训练模块，并固定大部分预训练权重。
- **关键词：** LoRA, PEFT, fine-tuning

### AceReason-Nemotron 1.1: Advancing Math and Code Reasoning through SFT and RL Synergy

- **作者：** Zihan Liu, Zhuolin Yang, Yang Chen, Chankyu Lee, Mohammad Shoeybi, Bryan Catanzaro, Wei Ping
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=IaEqjWXd1d
- **中文提要：** 该研究考察监督微调与强化学习如何协同，以培养强推理模型。SFT 数据的整理从增加所收集的提示，以及增加每条提示所生成的回答入手。
- **关键词：** SFT, post-training, fine-tuning

### Actions as Language: Fine-Tuning VLMs into VLAs Without Catastrophic Forgetting

- **作者：** Asher Hancock, Xindi Wu, Lihan Zha, Olga Russakovsky, Anirudha Majumdar
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=sFO9d6XSlf
- **中文提要：** 在机器人遥操作数据上把视觉语言模型微调成视觉-语言-动作模型，是训练通用策略的一条途径，却存在根本权衡。学会产生动作往往会削弱原有的基础推理和多模态理解，妨碍对新场景、指令跟随和语义层面的泛化。
- **关键词：** instruction-following, LoRA, alignment, fine-tuning

### ActiveDPO: Active Direct Preference Optimization for Sample-Efficient Alignment

- **作者：** Xiaoqiang Lin, Arun Verma, Zhongxiang Dai, Daniela Rus, See-Kiong Ng, Bryan Kian Hsiang Low
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=RD4XgyVyGh
- **中文提要：** 借助人类偏好对齐大语言模型，已经明显改善问答、数学推理和代码生成等下游任务。真正有效的对齐，仍然取决于高质量的人类偏好数据集。
- **关键词：** DPO, preference-optimization, reward-model, alignment

### ADEPT: Continual Pretraining via Adaptive Expansion and Dynamic Decoupled Tuning

- **作者：** Jinyang Zhang, Yue Fang, Hongxin Ding, Weibin Liao, Muyang Ye, Junfeng Zhao, Yasha Wang, Xu Chu
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=vcWDDfA4Ev
- **中文提要：** 大语言模型做领域适应时，常规持续预训练容易灾难性遗忘，领域容量也有限。现有策略采用层扩展，用额外可训练参数来容纳新知识。
- **关键词：** continued-pretraining

### AdPO: Enhancing the Adversarial Robustness of Large Vision-Language Models with Preference Optimization

- **作者：** Chaohu Liu, Gui Tianyi, Yu Liu, Linli Xu
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=FEMv4lHJ2C
- **中文提要：** 大视觉语言模型进展迅速并越来越多地进入真实应用，却继承了视觉神经网络的敏感性。它们仍然容易受到对抗攻击，并因此产生错误或恶意输出。
- **关键词：** preference-optimization, fine-tuning

### Agent Data Protocol: Unifying Datasets for Diverse, Effective Fine-tuning of LLM Agents

- **作者：** Yueqi Song, Ketan Ramaneti, Zaid Sheikh, Ziru Chen, Boyu Gou, Tianbao Xie, Yiheng Xu, Danyang Zhang, Apurva Gandhi, Fan Yang, Joseph Liu, Tianyue Ou, Zhihao Yuan, Frank F Xu, Shuyan Zhou, Xingyao Wang, Xiang Yue, Tao Yu, Huan Sun, Yu Su, Graham Neubig
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=tG6301ORHd
- **中文提要：** 智能体的大规模监督微调在公开研究中仍然少见，因为智能体训练数据的采集有其特殊困难。作者认为瓶颈不是缺少底层数据来源，而是大量数据分散在异构的格式、工具和接口里。
- **关键词：** SFT, fine-tuning

### Aligner, Diagnose Thyself: A Meta-Learning Paradigm for Fusing Intrinsic Feedback in Preference Alignment

- **作者：** Mengyang Li, Pinlong Zhao, Zhong Zhang
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=oIAUP1K5Dq
- **中文提要：** 人类偏好对齐会被训练数据里的噪声标签严重削弱。现有稳健方法往往只靠困惑度或损失这类单一而狭窄的启发式，覆盖不了真实噪声的多样性。
- **关键词：** preference-optimization, alignment

### Alignment through Meta-Weighted Online Sampling: Bridging the Gap between Data Generation and Preference Optimization

- **作者：** Junming Yang, Ning Xu, Biao Liu, Shiqi Qiao, Xin Geng
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=8OD1ymZxY9
- **中文提要：** 偏好优化对让大语言模型符合人类价值与意图至关重要。一个突出困难是，预先收集的离线偏好分布与不断演化的模型策略对不上。
- **关键词：** preference-optimization, alignment

### Alignment-Weighted DPO: A principled reasoning approach to improve safety alignment

- **作者：** Mengxuan Hu, Vivek Datla, Anoop Kumar, Zihan Guan, Sheng Li, Alfy Samuel, Daben Liu
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=OuMNJoKJBQ
- **中文提要：** SFT、RLHF 与 DPO 等对齐技术已经提高了大语言模型的安全性。这些模型仍会被越狱攻击击中，攻击者用间接或欺骗性措辞把有害意图伪装起来。
- **关键词：** DPO, RLHF, SFT, preference-optimization, post-training, alignment, fine-tuning

### All Roads Lead to Likelihood: The Value of Reinforcement Learning in Fine-Tuning

- **作者：** Gokul Swamy, Sanjiban Choudhury, Wen Sun, Steven Wu, Drew Bagnell
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=sCL5mSTpKm
- **中文提要：** 从第一性原理看，基础模型微调里较强的结果竟来自相对复杂的流程，这一点颇为反常。具体做法是先在人类偏好等数据上训练奖励模型，再用它为下游强化学习提供在线反馈，而不是直接优化。
- **关键词：** reward-model, fine-tuning

### $\alpha$-DPO: Robust Preference Alignment for Diffusion Models via $\alpha$ Divergence

- **作者：** Yang Li, Songlin Yang, Wei Wang, Xiaoxuan Han, Jing Dong
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=wqbnA6PcKr
- **中文提要：** 扩散模型已经能生成高保真图像，与人类偏好对齐却仍然困难。DPO 提供了一条框架，但其效果会被错标偏好对以及个体偏好对所带来的噪声数据严重制约。
- **关键词：** DPO, preference-optimization, alignment

### Anchored Supervised Fine-Tuning

- **作者：** He Zhu, Junyou Su, Peng Lai, Ren Ma, Wenjia Zhang, Linyi Yang, Guanhua Chen
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=PORko7QT64
- **中文提要：** 大语言模型后训练要在监督微调与强化学习之间取舍：前者能高效模仿示范却倾向记忆，后者泛化更好但计算代价更高。动态微调近来被视为折中，用 token 概率重加权 SFT 目标。
- **关键词：** SFT, post-training, fine-tuning

### Antibody: Strengthening Defense Against Harmful Fine-Tuning for Large Language Models via Attenuating Harmful Gradient Influence

- **作者：** Quoc Nguyen, Trung Le, Jing Wu, Anh Bui, Mehrtash Harandi
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=qur2ef8MqQ
- **中文提要：** 微调即服务带来安全威胁：服务提供方会在用户提交的投毒数据上微调，形成有害微调攻击。对微调过程中有害样本的梯度贡献施加正则，可以减轻这类攻击的影响。
- **关键词：** alignment, fine-tuning

### Arbitrary-Order Block SignSGD for Memory-Efficient LLM Fine-Tuning

- **作者：** Yijie Zhou, Shi Pu
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=NQsdnYkCar
- **中文提要：** ABSignSGD 是符号下降的块坐标变体，块的选择很灵活，从而让大语言模型的全参数微调在显存和运行时间上都更省。文中在温和条件下给出统一收敛分析，同时覆盖基础方法以及面向分布式训练的多数投票扩展。
- **关键词：** fine-tuning

### A Simple "Motivation" Can Enhance Reinforcement Finetuning of Large Reasoning Models

- **作者：** Junjie Zhang, Guozheng Ma, Shunyu Liu, Haoyu Wang, Jiaxing Huang, Ting-En Lin, Fei Huang, Yongbin Li, Dacheng Tao
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=3owSlsYDQf
- **中文提要：** 可验证奖励的强化学习已成为大推理模型处理复杂任务的学推理范式。当前这套范式仍不够高效，因为它本质上靠试错推进。
- **关键词：** RLVR, RFT, alignment, fine-tuning

### Attend to the Active: Structure-Aware Dynamic Attention in LLMs for Compositional Instruction Following

- **作者：** Fangrui Lv, Yulei Qin, Ruixin Hong, Jian Liang, Jinyang Wu, Ke Li, Xing Sun, Changshui Zhang
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=wwA0X3UfAn
- **中文提要：** 大语言模型的指令跟随能力很强，却经常处理不好由多个交错、逻辑上独立的子任务构成的组合指令。这些子任务通常组织成互斥结构，例如分支、串联或并行，生成的每一步只应有其中一个子任务处于激活状态。
- **关键词：** instruction-following

### $AutoDrive\text{-}P^3$: Unified Chain of Perception–Prediction–Planning Thought via Reinforcement Fine-Tuning

- **作者：** Yuqi Ye, Zijian Zhang, Junhong Lin, Shangkun Sun, Changhao Peng, Wei Gao
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=CMU8GxwpUL
- **中文提要：** 视觉语言模型因擅长长尾场景，正被用于端到端自动驾驶，但现有做法有明显短板。有的模型不做思维链，直接输出规划，从而绕过关键的感知与预测阶段。
- **关键词：** GRPO, RFT, fine-tuning

### AVERE: Improving Audiovisual Emotion Reasoning with Preference Optimization

- **作者：** Ashutosh Chaubey, Jiacheng Pang, Maksim Siniukov, Mohammad Soleymani
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=td682AAuPr
- **中文提要：** 情绪理解是构建社交智能体的基础。多模态大语言模型在该任务上表现强，但仍会把情绪与无关视听线索错误关联，也会因语言骨干里的文本先验而幻觉出视听线索。
- **关键词：** DPO, preference-optimization

### Balancing the Experts: Unlocking LoRA-MoE for GRPO via Mechanism-Aware Rewards

- **作者：** Changlian Ma, Zizheng Huang, Xiangyu Zeng, Yi Wang, Cheng Liang, Kun Tian, Xinhai Zhao, Limin Wang
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=rhD7ZuFAjU
- **中文提要：** LoRA-MoE 这类参数高效的混合专家结构，能够做较强且可泛化的微调。用 GRPO 这类强化学习算法去微调它们时，却会出现关键问题。
- **关键词：** GRPO, RFT, LoRA, PEFT, alignment, fine-tuning

### BA-LoRA: Bias-Alleviating Low-Rank Adaptation to Mitigate Catastrophic Inheritance in Large Language Models

- **作者：** Yupeng Chang, Yi Chang, Yuan Wu
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=q0X9SiXiRO
- **中文提要：** 参数高效微调几乎已成为适配大语言模型的默认做法。LoRA 等流行低秩适应方法却有一个关键弱点：它们会加剧灾难性继承，使预训练中的偏见、噪声和数据不均衡不受约束地继续传播。
- **关键词：** LoRA, PEFT, fine-tuning

### BaseReward: A Strong Baseline for Multimodal Reward Model

- **作者：** YiFan Zhang, HaiHuaYang, Huanyu Zhang, Yang Shi, Zezhou Chen, Haochen Tian, Chaoyou Fu, Kai WU, Bo Cui, Xu Wang, Jianfei Pan, Haotian Wang, Zhang Zhang, Liang Wang
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=EuN5iszF0a
- **中文提要：** 多模态大语言模型快速发展，使与人类偏好对齐成为关键挑战。奖励模型是实现这一目标的核心技术，但学术界和工业界都缺少构建先进多模态奖励模型的系统指南。
- **关键词：** RLHF, reward-model, alignment

### Be Careful When Fine-tuning On Open-Source LLMs: Your Fine-tuning Data Could Be Secretly Stolen!

- **作者：** Zhexin Zhang, Yuhao Sun, Junxiao Yang, Shiyao Cui, yuanchao zhang, Hongning Wang, Minlie Huang
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=HhXOVhO3ia
- **中文提要：** 用专有数据微调开源大语言模型，已是下游开发者获得任务模型的常规做法。作者指出一项风险：开源模型的提供方事后可以只凭对微调后模型的黑盒访问，通过简单的后门训练抽取出私有的下游微调数据。
- **关键词：** fine-tuning

### Beyond Binary Preferences: A Principled Framework for Reward Modeling with Ordinal Feedback

- **作者：** Amirhossein Afsharrad, Ruida Zhou, Luca Viano, Sanjay Lall, Mohammad Ghavamzadeh
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=mteZOi0xyu
- **中文提要：** 奖励建模对把大语言模型对齐到人类偏好至关重要，但现有方法缺少利用有序偏好数据的原则性数学框架。当标注者在李克特量表上给出分级偏好时，常见做法只是使用间隔项或缩放之类的临时启发式。
- **关键词：** reward-model, alignment

### Beyond Magnitude: Leveraging Direction of RLVR Updates for LLM Reasoning

- **作者：** Kexin Huang, Haoming Meng, Junkang Wu, Jinda Lu, Chiyu Ma, Ziqian Chen, xue wang, Bolin Ding, Jiancan Wu, Xiang Wang, Xiangnan He, Guoyin Wang, Jingren Zhou
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=r6Pw3RiMYL
- **中文提要：** 可验证奖励的强化学习显著提升了大语言模型的推理能力。已有分析指出这类更新是稀疏的，但注意力主要放在更新幅度上，方向则在很大程度上被忽略。
- **关键词：** RLVR

### Beyond Pairwise: Empowering LLM Alignment With (Ranked) Choice Modeling

- **作者：** Yuxuan Tang, Yifan Feng
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=fCaxd9EKzl
- **中文提要：** 大语言模型对齐主要依赖成对偏好优化，标注者只需在同一提示的一对回答中选出更好者。这种简单设定错过了多路比较和 top-k 排序等更丰富的人类反馈。
- **关键词：** DPO, SimPO, preference-optimization, alignment

### Beyond Pass@ 1: Self-Play with Variational Problem Synthesis Sustains RLVR

- **作者：** Xiao Liang, Zhong-Zhi Li, Yeyun Gong, yelong shen, Yingnian Wu, Zhijiang Guo, Weizhu Chen
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Wjf3OMJxpn
- **中文提要：** 可验证奖励强化学习已成为大语言模型后训练、尤其是复杂推理的关键范式。普通训练在抬高单次采样命中的同时消耗策略熵，生成多样性下降，也限制了多次采样所代表的能力上界。
- **关键词：** RLVR, post-training

### Beyond RLHF and NLHF: Population-Proportional Alignment under an Axiomatic Framework

- **作者：** Kihyun Kim, Jiawei Zhang, Asuman Ozdaglar, Pablo Parrilo
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Egmvi2RWnj
- **中文提要：** 常规偏好学习在汇总多名评估者的意见时，常常优先那些被更广泛持有的看法。由此得到的策略可能偏向某些意见类型或群体，也容易受到策略性操纵。
- **关键词：** RLHF, alignment

### Bi-LoRA: Efficient Sharpness-Aware Minimization for Fine-Tuning Large-Scale Models

- **作者：** Yuhang Liu, Tao Li, Zhehao Huang, Zuopeng Yang, Xiaolin Huang
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=zoYPlgX1bH
- **中文提要：** 低秩适应使大规模预训练模型能够以较少参数完成微调。即便如此，LoRA 仍可能遇到泛化上的困难。
- **关键词：** LoRA, PEFT, fine-tuning

### BoRA: Towards More Expressive Low-Rank Adaptation with Block Diversity

- **作者：** Shiwei Li, Xiandi Luo, Haozhao Wang, Xing Tang, Ziqiang Cui, Dugang Liu, Yuhua Li, Yichen Li, xiuqiang He, Ruixuan Li
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=eUMJXFgMjM
- **中文提要：** 在大语言模型中，低秩适应被广泛用作参数高效微调。预训练权重矩阵的更新，由低秩矩阵相乘来近似。
- **关键词：** LoRA, PEFT, fine-tuning

### BOTS: A Unified Framework for Bayesian Online Task Selection in LLM Reinforcement Finetuning

- **作者：** Qianli Shen, Daoyuan Chen, Yilun Huang, Zhenqing Ling, Yaliang Li, Bolin Ding, Jingren Zhou
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=rQXBw8fn3Z
- **中文提要：** 强化微调是对齐大语言模型并增强推理的关键技术，但效果高度取决于训练时探索哪些任务。均匀采样并不划算，会把计算浪费在过于容易或无法解决的任务上，而已有选择方法又常常推演成本高。
- **关键词：** RFT, alignment, fine-tuning

### Bradley-Terry and Multi-Objective Reward Modeling Are Complementary

- **作者：** Zhiwei Zhang, Hui Liu, Xiaomin Li, Zhenwei Dai, Jingying Zeng, Fali Wang, Minhua Lin, Ramraj Chandradevan, Linlin Wu, Zhen Li, Chen Luo, Zongyu Wu, Xianfeng Tang, Qi He, Suhang Wang
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=3QHKJcwnpb
- **中文提要：** 在人类偏好数据上训练的奖励模型，在 RLHF 框架下能有效帮助大语言模型对齐人类意图。这一框架仍易受奖励黑客影响：策略利用奖励函数的缺陷，而不是真正学会预期行为。
- **关键词：** RLHF, reward-model, alignment

### BranchGRPO: Stable and Efficient GRPO with Structured Branching in Diffusion Models

- **作者：** Yuming Li, Yikai Wang, Yuying zhu, Zhongyu Zhao, Ming Lu, Qi She, Shanghang Zhang
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=T2nP2IQasd
- **中文提要：** 用 GRPO 对齐图像和视频生成模型，已经改善了对人类偏好的贴合，但现有变体仍因顺序推演和大量采样步而低效。稀疏的终局奖励被均匀传播到各个时间步，信用分配不可靠，也抓不住决策在过程中不同的关键程度。
- **关键词：** GRPO, preference-optimization, alignment

### Breaking the SFT Plateau: Multimodal Structured Reinforcement Learning for Chart-to-Code Generation

- **作者：** Lei Chen, Xuanle Zhao, Zhixiong Zeng, Jing Huang, Liming Zheng, Yufeng Zhong, Lin Ma
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=14qYxv2jki
- **中文提要：** 强化学习对视觉语言模型的一般推理很有效，但要用在既需深入理解信息密集图像、又需生成结构化输出的任务上，探索仍然不足。图表到代码正是这种情形，需要对可视化图表做复杂推理才能写出结构化代码。
- **关键词：** SFT, fine-tuning

### CAR-LoRA: Training Compression-Aware and Robust LoRA Adapters for Evolving LLMs

- **作者：** Rana Muhammad Shahroz Khan, Zhen Tan, Ruichen Zhang, Hua Wei, Tianlong Chen, Charles Fleming
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=5GimteSrgW
- **中文提要：** 把大语言模型部署到手机、传感器等资源受限的边缘设备上做专门任务，会带来明显的扩展性困难。要在这类硬件上运行，庞大的模型必须经过量化或剪枝等压缩，以减小内存和计算占用。
- **关键词：** QLoRA, LoRA, PEFT, fine-tuning

### Cat-PO: Cross-modal Adaptive Token-rewards for Preference Optimization in Truthful Multimodal LLMs

- **作者：** Zhixiao Zheng, Zheren Fu, Zhiyuan Yao, Dongming Zhang, Zhendong Mao
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=iIbe6qDN0A
- **中文提要：** 多模态大语言模型在各类多模态任务上生成能力突出，却仍受幻觉困扰，生成文本会与输入图像在语义上不一致。现有多模态偏好优化在偏好数据的解码阶段就存在短板。
- **关键词：** DPO, preference-optimization, alignment

### CDBridge: A Cross-omics Post-training Bridge Strategy for Context-aware Biological Modeling

- **作者：** Chang Yu, Siyuan Li, Zicheng Liu, Jingbo Zhou, Xianglong Guo, Kai Yu, Yuqing Zhou, Ken Li, Zelin Zang, Zhen Lei, Stan Z Li
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Hk4Fb6kaYF
- **中文提要：** 把基因组 DNA 与定量、随情境变化的表达联系起来，仍是计算生物学的核心难题。当前基础模型往往只能捕捉组织情境或序列特征中的一面，无法同时兼顾两者。
- **关键词：** post-training

### CellDuality: Unlocking Biological Reasoning in LLMs with Self-Supervised RLVR

- **作者：** Yuhang Chen, Zhen Tan, Ruichen Zhang, Mufan Qiu, Tianlong Chen
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=I4meJN28Ol
- **中文提要：** 培养能进行复杂生物学推理的通用大语言模型，是计算生物学的中心挑战。现有模型擅长细胞类型注释等预测任务以及受逻辑约束的问题，开放式和机制性推理则仍然困难。
- **关键词：** RLVR, fine-tuning

### CerebraGloss: Instruction-Tuning a Large Vision-Language Model for Fine-Grained Clinical EEG Interpretation

- **作者：** Wei Gu, Tianming Luo, Qiran Zhang, Mohan Ye, Xiao Shen, Wenxin Chen, Yunhuan Li, Yichen Zhang, Jing Hong, Bao-liang Lu, Wei-Long Zheng
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Xi1jkajWi9
- **中文提要：** 临床脑电解读费力且主观，现有计算模型又多局限于狭窄的分类，而不是整体判读。把视觉语言模型用到这一领域，关键瓶颈是缺少将脑电视图与细粒度专家标注配对的数据集。
- **关键词：** instruction-tuning

### Chasing the Tail: Effective Rubric-based Reward Modeling for Large Language Model Post-Training

- **作者：** Junkai Zhang, Zihao Wang, Lin Gui, Swarnashree Mysore Sathyendra, Jaehwan Jeong, Victor Veitch, Wei Wang, Yunzhong He, Bing Liu, Lifeng Jin
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=pBjy4ek2QV
- **中文提要：** 强化微调经常遭遇奖励过优化：策略模型钻奖励信号以拿到高分，产出的内容质量却很低。理论分析认为关键在高奖励尾部的奖励误设，也就是无法可靠区分出色回答和仅仅很好的回答。
- **关键词：** RFT, reward-model, post-training, fine-tuning

### CMT: Mid-Training for Efficient Learning of Consistency, Mean Flow, and Flow-Map Models

- **作者：** Zheyuan Hu, Chieh-Hsin Lai, Yuki Mitsufuji, Stefano Ermon
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=2B8GkGTgmY
- **中文提要：** 一致性模型与 Mean Flow 等流映射模型，通过学习扩散模型常微分方程解的长跳跃来实现少步生成，但训练不稳定、对超参数敏感且成本高。从预训练扩散模型初始化有帮助，却仍需把无穷小步转换成长跳跃映射，不稳定并未解决。
- **关键词：** mid-training, post-training

### Co-LoRA: Collaborative Model Personalization on Heterogeneous Multi-Modal Clients

- **作者：** Minhyuk Seo, Taeheon Kim, Hankook Lee, Jonghyun Choi, Tinne Tuytelaars
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=0g5Dk4Qfh0
- **中文提要：** 人工智能越来越个人化，例如智能体场景，因此更需要针对不同用途做模型个性化。个性化联邦学习让每个客户端协作借用其他客户端的知识，以便更好地适配目标任务，同时避免隐私风险。
- **关键词：** LoRA

### COMAL: A Convergent Meta-Algorithm for Aligning LLMs with General Preferences

- **作者：** Yixin Liu, Argyris Oikonomou, Weiqiang Zheng, Yang Cai, Arman Cohan
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=OsrE5DJ9Fu
- **中文提要：** 包括 RLHF 在内的许多对齐方法依赖 Bradley-Terry 奖励假设，而这并不足以刻画一般人类偏好的全部范围和复杂性。作者在一般偏好框架下考察 RLHF，把对齐建模为博弈论中的双方零和博弈，并讨论其纳什均衡策略。
- **关键词：** RLHF, preference-optimization, alignment

### Command-V: Training-Free Representation Finetuning Transfer

- **作者：** Barry Wang, Avi Schwarzschild, Alexander Robey, Ali Payani, Charles Fleming, Mingjie Sun, Daphne Ippolito
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=oRYzpI3cmJ
- **中文提要：** 给大语言模型补上新行为，通常需要全量微调或蒸馏，而且每种架构都得重复这些昂贵步骤。Command-V 是一种不经反向传播的行为迁移：从供体模型复制已有的残差表示适配器，再把其效果粘贴到结构不同的受体模型。
- **关键词：** fine-tuning

### Comparing the learning dynamics of in-context learning and fine-tuning in language models

- **作者：** Basile Confavreux, Aaditya Singh, Jin Hwa Lee, Amaury Sabran, Andrew Saxe
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=cJAtzOcAnd
- **中文提要：** 预训练语言模型习得新任务，既可以靠上下文学习——只通过激活、不更新权重来改变行为——也可以靠监督微调显式更新参数。已有工作报告了二者在泛化表现和归纳偏置上的差异，但差异的来源仍然不清楚。
- **关键词：** SFT, fine-tuning

### Consis-GCPO: Consistency-Preserving Group Causal Preference Optimization for Vision Customization

- **作者：** Qiaoqiao Jin, Dong She, Siming Fu, Hualiang Wang, weihao zhou, Jidong Jiang
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=OswqOlTYR2
- **中文提要：** 视觉定制需要在主体保真较高的同时保持与文本描述的语义对齐。近期基于 GRPO 的方法在让生成模型贴合人类偏好上展现出潜力，却对所有去噪时间步做均匀优化，忽略了文本与视觉条件影响生成的时间动态。
- **关键词：** GRPO, preference-optimization, alignment

### Consistent Noisy Latent Rewards for Trajectory Preference Optimization in Diffusion Models

- **作者：** Xiaole Xian, Xilin He, Wenting Chen, Wenshuang Liu, Wenqi Mu, Yancheng He, Liang Li, Yi Zhang, Xiangyu Yue
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=qGihS60jfT
- **中文提要：** 视觉生成中的扩散模型进展，激发了类似于大语言模型的人类偏好对齐研究。基于奖励模型的方法可以通过评估中间时间步实现轨迹感知优化，但像素级模型对噪声干扰敏感，带噪潜变量上的奖励估计并不可靠。
- **关键词：** preference-optimization, reward-model, alignment

### ContextIF: Enhancing Instruction-Following through Context Reward

- **作者：** Yule Zhong, Jiacheng Yao, Guoxiu He
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=IuscGSmfEf
- **中文提要：** 监督微调与偏好学习被广泛用于增强大语言模型的指令跟随，却常常难以泛化到新颖或复杂的指令，还可能损害模型的通用能力。上下文学习不修改参数、泛化也较强，因而被视为一条有希望的替代路线。
- **关键词：** GRPO, SFT, instruction-following, fine-tuning

### Controllable Exploration in Hybrid-Policy RLVR for Multi-Modal Reasoning

- **作者：** Zhuoxu Huang, Mengxi Jia, Hao Sun, Xuelong Li, Jungong Han
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=5wxyCidRsK
- **中文提要：** 可验证奖励强化学习已成为增强多模态大语言模型推理能力的主要学习范式。训练中状态空间极大且奖励稀疏，常常导致熵崩溃、策略退化，或对次优行为过度利用。
- **关键词：** RLVR

### Controllable First-Frame-Guided Video Editing via Mask-Aware LoRA Fine-Tuning

- **作者：** Chenjian Gao, Lihe Ding, Cai, Zhanpeng Huang, Zibin Wang, Tianfan Xue
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=xkRMJ1Y7Um
- **中文提要：** 用扩散模型做视频编辑，已经能生成高质量的编辑结果。当前方法却常常依赖大规模预训练，针对特定编辑的灵活性因此受限。
- **关键词：** LoRA, fine-tuning

### Cosmos Policy: Fine-Tuning Video Models for Visuomotor Control and Planning

- **作者：** Moo Jin Kim, Yihuai Gao, Tsung-Yi Lin, Yen-Chen Lin, Yunhao Ge, Grace Lam, Percy Liang, Shuran Song, Ming-Yu Liu, Chelsea Finn, Jinwei Gu
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=wPEIStHxYH
- **中文提要：** 近期视频生成模型能够捕捉复杂的物理交互以及场景随时间的演化。机器人研究为利用其时空先验而把视频模型改造成策略，却因需要多阶段后训练、并新增动作生成的结构组件而引入额外复杂性。
- **关键词：** post-training, fine-tuning

### CPQS-Tuning: A Model Self-Perception-Based Data Filtering Algorithm for Efficient Instruction Fine-Tuning

- **作者：** YI REN, Yanhui Li, Tianyi Zhang, Diandong Liu
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=d57KvqmcBA
- **中文提要：** 指令微调是提升大语言模型性能的关键技术，但低质量和冗余数据经常妨碍效果。近期研究认为，筛出少量高质量数据再做指令微调，可以让训练更快、更高效。
- **关键词：** fine-tuning

### Data Selection for LLM Alignment Using Fine-Grained Preferences

- **作者：** Jia Zhang, Yao Liu, Chen-Xi Zhang, Yi Liu, Yi-Xuan Jin, Lan-Zhe Guo, Yu-Feng Li
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=nRS87hbAqU
- **中文提要：** 大语言模型对齐旨在让模型行为符合人类偏好。分方面的细粒度偏好越来越容易采集，现有对齐方法却通常只处理单一偏好，因而难以应对这类汇总数据中固有的冲突。
- **关键词：** preference-optimization, alignment

### Detecting Data Contamination from Reinforcement Learning Post-training for Large Language Models

- **作者：** Yongding Tao, Tian Wang, Yihong Dong, Huanyu Liu, Kechi Zhang, Hu XiaoLong, Ge Li
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=EjiJmiA6ea
- **中文提要：** 数据污染对大语言模型的可靠评测构成显著威胁。当基准样本无意间出现在训练集中时，所报告性能的有效性就会受到损害。
- **关键词：** SFT, post-training, fine-tuning

### DiaBlo: Diagonal Blocks Are Sufficient For Finetuning

- **作者：** Selcuk Gurses, Aozhong Zhang, Yanxia Deng, Xun Dong, Xin Li, Naigang Wang, Penghang Yin, Zi Yang
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=cZaI6GmjBm
- **中文提要：** 微调是把大语言模型适配到特定领域下游任务的关键一步。为减轻全量微调的计算与内存开销，参数高效微调只更新模型参数中的一小部分。
- **关键词：** LoRA, PEFT, alignment, fine-tuning

### Differential Fine-Tuning Large Language Models Towards Better Diverse Reasoning Abilities

- **作者：** Xiaosong Yuan, Chen Shen, Shaotian Yan, kaiyuan liu, Xiaofeng Zhang, Sinan Fan, Liang Xie, Wenxiao Wang, Renchu Guan, Ying Wang, Jieping Ye
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=aIhn4GhTBW
- **中文提要：** 与一般问答相比，大语言模型的推理能力需要显式推导，监督微调可以通过学习多种数据集来赋予多种推理能力。无论混合训练还是持续训练，都无法保持单数据集监督微调的表现，有时更好、有时甚至更差。
- **关键词：** SFT, fine-tuning

### Difficulty–Diversity Collaborative Filtering for Data-Efficient LLM Fine-Tuning

- **作者：** Long Hoang, Wenxuan Zhang, Wei Lu
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=n9mXlqD2SJ
- **中文提要：** 微调后语言模型的表现，深受微调数据的质量与数量影响。缩放律指出更大模型在预训练中受益于更多数据，少即是多的观点则强调，下游微调往往只需要小而高质量的数据集，就能有效唤起模型已有的预训练知识。
- **关键词：** fine-tuning

### Diffusion Blend: Inference-Time Multi-Preference Alignment for Diffusion Models

- **作者：** Min Cheng, Fatemeh Doudi, Dileep Kalathil, Mohammad Ghavamzadeh, Panganamala Kumar
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=M2DXbwO8le
- **中文提要：** 强化学习近来被用来对齐扩散模型：在固定 KL 正则下微调，以最大化单一奖励，从而追求美学质量、文图一致性等下游目标。这种做法在实践中偏窄，因为对齐必须在多个常常相互冲突的目标之间取得平衡。
- **关键词：** preference-optimization, alignment, fine-tuning

### Diffusion Negative Preference Optimization Made Simple

- **作者：** Joshua Tian Jin Tee, Hee Suk Yoon, Sunjae Yoon, Tri Ton, Chang Yoo
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=CU5EHe1KUt
- **中文提要：** 分类器无关引导改进扩散采样的做法，是鼓励条件生成、同时抑制无条件生成。现有偏好对齐却只看正向偏好对，因而难以主动压低不想要的输出，扩散负向偏好优化被做成更直接的形式。
- **关键词：** preference-optimization, alignment

### Direct Preference Optimization for Primitive-Enabled Hierarchical RL: A Bilevel Approach

- **作者：** Utsav Singh, Souradip Chakraborty, Wesley Suttle, Brian Sadler, Derrik Asher, Anit Kumar Sahu, Mubarak Shah, Vinay Purushothaman Namboodiri, Amrit Bedi
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=wleUyyqTz2
- **中文提要：** 分层强化学习把复杂长时程任务拆成可处理的子任务，但训练中不断变化的下层策略会使上层学习不稳，上层也可能给出下层无法达到的子目标。面向带原语的设定，双层形式的 DPO 被用来处理这些困难。
- **关键词：** DPO, preference-optimization

### Direct Reward Fine-Tuning on Poses for Single Image to 3D Human in the Wild

- **作者：** Seunguk Do, Minwoo Huh, Joonghyuk Shin, Jaesik Park
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=kWZTPWrczs
- **中文提要：** 借助多视角扩散模型，单视图三维人体重建进步明显，恢复出的姿态却常常不自然，动态或高难度姿态尤其突出。作者将此归因于带多样姿态的三维人体数据规模有限，并直接在姿态上做奖励微调。
- **关键词：** post-training, fine-tuning

### Displacement-Resistant Extensions of DPO with Nonconvex $f$-Divergences

- **作者：** Idan Pipano, Shoham Sabach, Kavosh Asadi, Mohammad Ghavamzadeh
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=rTte3iUsXV
- **中文提要：** DPO 及相关算法直接优化 RLHF 目标：策略在 KL 惩罚下靠近参考策略，同时最大化 Bradley-Terry 奖励。已有工作表明，把 KL 换成一族带凸性条件的 f-散度后问题仍可解。
- **关键词：** DPO, RLHF

### DIVA-GRPO: Enhancing Multimodal Reasoning through Difficulty-Adaptive Variant Advantage

- **作者：** Haowen Gao, zhenyu zhang, Liang Pang, Fangda Guo, hongjian dou, Guannan Lv, ShaoGuo Liu, Tingting Gao, Huawei Shen, Xueqi Cheng
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=qKXYEg00eH
- **中文提要：** 以 GRPO 做强化学习，已成为增强多模态大语言模型推理的常见路线，它无需传统评论家也能进行长链推理。困难题上正向反馈稀缺会带来稀疏奖励，同时还出现优势消失。
- **关键词：** GRPO

### Don't Just Fine-tune the Agent, Tune the Environment

- **作者：** Siyuan Lu, Zechuan Wang, Hongxuan Zhang, Qintong Wu, Leilei Gan, Chenyi Zhuang, Jinjie Gu, Tao Lin
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=nzodtGccEM
- **中文提要：** 大语言模型智能体有望完成复杂的多轮工具使用，开发却受高质量训练数据极度稀缺的拖累。合成数据上的 SFT 容易过拟合，标准强化学习又面临严重的冷启动和训练不稳，因此除微调智能体外，环境本身也需要被调节。
- **关键词：** SFT, fine-tuning

### DrugTrail: Interpretable Drug Discovery via Structured Reasoning and Druggability‑Tailored Preference Optimization

- **作者：** Yurou Liu, Mingyang Li, Xinyuan Zhu, Rui Jiao, Yiming Dong, Xinyu Tang, Yang Liu, Jieping Ye, Bing Su, Zheng Wang
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=1pAW0y8WLH
- **中文提要：** 机器学习有望改变药物发现，但黑箱属性和视野偏窄限制了专家采用。大语言模型凭借广博知识和可交互性提供了另一条路，现有方法却仍然很依赖数据，也缺少透明推理；DrugTrail 走结构化推理，并按成药性定制偏好优化。
- **关键词：** preference-optimization

### Dual-IPO: Dual-Iterative Preference Optimization for Text-to-Video Generation

- **作者：** Xiaomeng Yang, Mengping Yang, GONG JIA, Luozheng Qin, Zhiyu Tan, Hao Li
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=mu8sO1Vw0C
- **中文提要：** 可扩展的扩散 Transformer 已经能生成相当真实的视频，输出却常常对不齐用户真正的需求与偏好。Dual-IPO 以双重迭代偏好优化来做文生视频对齐。
- **关键词：** preference-optimization, reward-model, alignment

### DuPO: Enabling Reliable Self-Verification via Dual Preference Optimization

- **作者：** Shuaijie She, Yu Bao, Yu Lu, Lu Xu, Tao Li, Wenhao Zhu, Jianbing Zhang, Shujian Huang, Shanbo Cheng, Lu Lu, Yuxuan Wang
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=SD8Z231C45
- **中文提要：** DuPO 是基于对偶学习的偏好优化框架，通过对广义对偶产生无需标注的反馈，以实现可靠的自验证。它针对这些限制：RLVR 依赖昂贵标签且只适用于可验证任务，以及传统对偶学习必须绑定严格对偶的任务对，例如翻译与回译。
- **关键词：** RLVR, preference-optimization

### Dynamics-Predictive Sampling for Active RL Finetuning of Large Reasoning Models

- **作者：** Yixiu Mao, Yun Qu, Qi Wang, Heming Zou, Xiangyang Ji
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=voeheZjd8p
- **中文提要：** 强化学习微调已成为提升大语言模型推理能力的关键技术，效果却严重取决于训练数据怎么选。动力学预测采样被用来支持对大型推理模型的主动强化学习微调。
- **关键词：** RFT, fine-tuning

### Dynamic Weight Grafting: Localizing Finetuned Factual Knowledge in Transformers

- **作者：** Todd Nief, David Reber, Sean Richardson, Ari Holtzman
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=j5vRSKOHmO
- **中文提要：** 动态权重嫁接追问：大语言模型在微调中学到新事实后，这些信息落在 Transformer 的何处。实体是立刻带上关系信息，还是模型只在预测前才即时回忆，摘要把这些可能并列出来。
- **关键词：** fine-tuning

### EasyTune: Efficient Step-Aware Fine-Tuning for Diffusion-Based Motion Generation

- **作者：** Xiaofeng Tan, Wanjiang Weng, Haodong Lei, Hongsong Wang
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Fy1EoIaAzQ
- **中文提要：** 动作生成模型近年进步很大，对齐下游目标仍然困难。已有研究表明，用可微奖励直接对齐扩散模型的偏好是有希望的方向；EasyTune 则是面向扩散式动作生成、并感知步数的高效微调。
- **关键词：** reward-model, alignment, fine-tuning

### EditReward: A Human-Aligned Reward Model for Instruction-Guided Image Editing

- **作者：** Keming Wu, Sicong Jiang, Max Ku, PING NIE, Minghao Liu, Wenhu Chen
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=eZu358JOOR
- **中文提要：** 用自然语言指令做图像编辑进展很快，GPT-Image-1、Seedream、Google-Nano-Banana 等闭源模型都显示出很强势头。EditReward 要做的是与人类对齐的奖励模型，服务于这类指令引导编辑。
- **关键词：** reward-model, alignment

### EditScore: Unlocking Online RL for Image Editing via High-Fidelity Reward Modeling

- **作者：** Xin Luo, Jiahao Wang, Chenyuan Wu, Shitao Xiao, Xiyan Jiang, Defu Lian, Jiajun Zhang, Dong Liu, Zheng Liu
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=E7YpL4L4Xh
- **中文提要：** 指令引导的图像编辑虽有明显进展，复杂指令仍然难处理，往往要多次采样才能得到满意结果。强化学习本是一条出路，却因缺少高保真且高效的奖励信号而难以用在图像编辑上；EditScore 靠高保真奖励建模来打开在线强化学习。
- **关键词：** reward-model

### Eliminating Inductive Bias in Reward Models with Information-Theoretic Guidance

- **作者：** Zhuo Li, Pengyu Cheng, Zhechao Yu, FeifeiTong, Anningzhe Gao, Tsung-Hui Chang, Xiang Wan, erchao.zec, xiaoxi jiang, guanjunjiang
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=57YfUhcYXd
- **中文提要：** 在 RLHF 中，奖励模型负责把大语言模型对齐到人类价值。其训练数据普遍被认为质量不高，所含归纳偏置很容易造成过拟合和奖励黑客，信息论指导被用来消除这类偏置。
- **关键词：** RLHF, reward-model

### E²LoRA: Efficient and Effective Low-Rank Adaptation with Entropy-Guided Adaptive Sharing

- **作者：** Minglei Li, Peng Ye, Jingqi Ye, Haonan He, Tao Chen
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=IQttyo0460
- **中文提要：** 大规模预训练模型快速膨胀，使 LoRA 这类 PEFT 愈发关键。LoRA 能以很少的额外参数保住性能，但要把效率再推进一步，仍需探索其参数共享；E²LoRA 用熵引导的自适应共享来做低秩适应。
- **关键词：** LoRA, PEFT, fine-tuning

### Empowering LLM Tool Invocation with Tool-call Reward Model

- **作者：** Da Ma, Ziyue Yang, Hongshen Xu, Haotian Fang, Kai Yu, Lu Chen
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=LnBEASInVr
- **中文提要：** 调用搜索引擎和代码生成等外部工具，缓解了大语言模型内部知识过时和计算不准的问题。强化学习显著增强了工具使用，但多数智能体方法只使用结果级奖励，信用分配粒度很粗。
- **关键词：** GRPO, PRM, reward-model

### Enhancing Instruction Following of LLMs via Activation Steering with Dynamic Rejection

- **作者：** Minjae Kang, Jaehyung Kim
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=OpuPBNcQwe
- **中文提要：** 尽管指令微调已有进展，大语言模型仍经常无法遵循复杂的用户指令。激活引导通过操纵模型内部来缓解这一点，但过度引导会损害任务准确率和整体文本质量，动态拒绝被加进这种引导。
- **关键词：** instruction-tuning, instruction-following

### Enhancing Trustworthiness of Fine-Tuned LLMs via Regularized Subset Selection

- **作者：** Kumar Shubham, Nishant Sharma, Karn Tiwari, Prathosh AP
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=cXo4vQudaa
- **中文提要：** SFT 能改善大语言模型的困惑度，也可能削弱可信度，使用户交互中出现不真实、带偏见或不安全的内容。这些问题常被追溯到训练数据中的特定短语或模式，正则化子集选择被用来提升微调后模型的可信度。
- **关键词：** SFT, fine-tuning

### Entropy-Guided Dynamic Tokens for Graph-LLM Alignment in Molecular Understanding

- **作者：** Zihao Jing, Qiuhao Zeng, Ruiyi Fang, Yan Sun, Boyu Wang, Pingzhao Hu
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=yzwSzhqLpH
- **中文提要：** 分子理解关系到科学发现和药物发现，大语言模型却难以有效理解分子图。现有图与语言模型的连接常改造原本为视觉设计的 Q-Former 式连接器，并使用固定长度的静态词元；熵引导的动态词元被用来做对齐。
- **关键词：** alignment, fine-tuning

### Escaping Policy Contraction: Contraction-Aware PPO (CaPPO) for Stable Language Model Fine-Tuning

- **作者：** Dun Yuan, Di Wu, Xue Liu
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=vDlkJewkDu
- **中文提要：** 使用 PPO 的 RLHF 应用很广，但输出多样性常常低于 SFT，提示在线策略优化时策略支撑在收缩。作者用支持保留率 SRR 形式化这种策略收缩，即仍保持不可忽略概率的 SFT 补全所占份额。
- **关键词：** RLHF, SFT, alignment, fine-tuning

### Evaluating and Improving Cultural Awareness of Reward Models for LLM Alignment

- **作者：** Hongbin Zhang, Kehai Chen, Xuefeng Bai, Yang Xiang, Min Zhang
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=WhSzqsMhfZ
- **中文提要：** 奖励模型对把大语言模型对齐到不同文化至关重要，评估其文化意识因而成为推进全球对齐的必要环节。这项工作同时评估并改进用于对齐的奖励模型的文化意识。
- **关键词：** RLVR, reward-model, alignment

### EVLP: Learning Unified Embodied Vision-Language Planner with Reinforced Supervised Fine-Tuning

- **作者：** xinyan cai, Qiang Guan, Shiguang Wu, DaFeng Chi, Yuzheng Zhuang, Xingyue Quan, Jianye Hao
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=eJcCW9oNfH
- **中文提要：** 复杂的具身长时程操作要高效、准确地分解并执行任务，需要文本逻辑推理与视觉空间想象协同。现有方法没有采用统一的多模态规划生成框架，导致规划不一致；EVLP 以强化的监督微调学习统一的具身视觉语言规划器。
- **关键词：** SFT, alignment, fine-tuning

### Explainable Token-level Noise Filtering for LLM Fine-tuning Datasets

- **作者：** Yuchen Yang, Wenze Lin, Enhao Huang, Zhixuan Chu, Hongbin zhou, Lan Tao, Yiming Li, Zhan Qin, Kui Ren
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=WEEodalWQg
- **中文提要：** 微调是把大语言模型适配到具体下游任务的重要步骤，通常要在相应数据集上继续训练。可解释的词元级噪声过滤被用来处理这类微调数据。
- **关键词：** fine-tuning

### Exploration vs Exploitation: Rethinking RLVR through Clipping, Entropy, and Spurious Reward

- **作者：** Peter Chen, Xiaopeng Li, Ziniu Li, Wotao Yin, Xi Chen, Tianyi Lin
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=sE8DCSJTzd
- **中文提要：** 该研究考察 RLVR 中的探索与利用权衡，这一框架用于改进大语言模型的推理。近期研究认为，RLVR 能靠看似矛盾的机制激发较强的数学推理，其中伪奖励通过奖励与给定参照无关的结果来抑制利用。
- **关键词：** RLVR

### Explore-on-Graph: Incentivizing Autonomous Exploration of Large Language Models on Knowledge Graphs with Path-refined Reward Modeling

- **作者：** Shiqi Yan, Yubo Chen, Ruiqi Zhou, Zhengxi Yao, Shuai Chen, Tianyi Zhang, Shijie Zhang, Wei-Qiang Zhang, Yongfeng Huang, Haixin Duan, Yunqi Zhang
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=NfuBj8jleE
- **中文提要：** 问答任务里，大语言模型的推理常被幻觉和事实缺失所困扰。把回答锚定到知识图谱等可核验来源是一条有希望的途径；Explore-on-Graph 用经路径细化的奖励建模，激励模型在知识图谱上自主探索。
- **关键词：** reward-model, fine-tuning

### Fine-tuning Done Right in Model Editing

- **作者：** Wanli Yang, Rui Tang, Hongyu Zang, Du Su, Qi Cao, Jingang Wang, Huawei Shen, Xueqi Cheng, Fei Sun
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=cfHuA5jsPt
- **中文提要：** 微调虽是适配大语言模型的基础手段，长期却被认为不适用于模型编辑。作者挑战这一看法，认为已报告的失败来自把微调套进编辑任务的顺序特性：单遍深度优先，每个样本先优化到收敛再进入下一个。
- **关键词：** fine-tuning

### Fine-tuning Quantized Neural Networks with Zeroth-order Optimization

- **作者：** Sifeng SHANG, JIAYI ZHOU, Chenyu Lin, Minxian Li, Kaiyang Zhou
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=mGeeRFToaW
- **中文提要：** 模型体量迅速增长后，显存成为把大语言模型适配到下游任务的瓶颈。目标是在统一框架中尽量压低权重、梯度和优化器状态所占显存，并用零阶优化微调量化神经网络。
- **关键词：** post-training, fine-tuning

### Fixing the Broken Compass: Diagnosing and Improving Inference-Time Reward Modeling

- **作者：** Jiachun Li, Pengfei Cao, Zhuoran Jin, Yubo Chen, Jiexin Xu, Huaijun Li, Xiaojian Jiang, Kang Liu, Jun Zhao
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=hsBBYOqph2
- **中文提要：** 推理时扩展有望增强大语言模型的推理能力，近期研究却主要集中在训练时优化。基于奖励模型的推理时推理被标为关键但被忽视的途径，工作据此诊断并改进推理时奖励建模。
- **关键词：** reward-model

### FlexLoRA: Entropy-Guided Flexible Low-Rank Adaptation

- **作者：** Muqing Liu, Chongjie Si, Yuheng Jia
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=tqnkbdYWWm
- **中文提要：** 大型预训练模型在多个领域都很成功，全量微调的计算和显存成本却高得难以承受，PEFT 因此成为主流范式。FlexLoRA 在此之上用熵来引导灵活的低秩适应。
- **关键词：** LoRA, PEFT, fine-tuning

### FLoRG: Federated Fine-tuning with Low-rank Gram Matrices and Procrustes Alignment

- **作者：** Chuiyang Meng, Ming Tang, Vincent Wong
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=kntrZOm2AQ
- **中文提要：** LoRA 等参数高效微调让大语言模型能高效适配下游任务，联邦学习进一步允许分布式客户端在不共享私有数据的情况下协同微调。FLoRG 借助低秩格拉姆矩阵和普鲁克对齐完成这种联邦微调。
- **关键词：** LoRA, PEFT, alignment, fine-tuning

### Fluent Alignment with Disfluent Judges: Post-training for lower-resource languages

- **作者：** David Samuel, Lilja Øvrelid, Erik Velldal, Andrey Kutuzov
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=htOZXpUPFZ
- **中文提要：** 面向较低资源语言的后训练方法，希望即使对齐所用的奖励模型不流利，语言模型本身仍保持流畅。偏好优化已有大量研究，但以往大多处理英语和中文模型。
- **关键词：** SFT, instruction-tuning, preference-optimization, reward-model, post-training, alignment, fine-tuning

### From Utterance to Vividity: Training Expressive Subtitle Translation LLM via Adaptive Local Preference Optimization

- **作者：** Chaoqun Cui, Shijing Wang, Liangbin Huang, Qingqing Gu, Zhaolong Huang, Xiao Zeng, Wenji Mao
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=d3ABURcHk3
- **中文提要：** 大语言模型的快速发展显著增强了机器翻译的通用能力。应用场景变复杂后，垂直领域翻译的局限逐渐显现；自适应局部偏好优化被用来训练更有表现力的字幕翻译模型。
- **关键词：** preference-optimization, reward-model, alignment

### Front-Loading Reasoning: The Synergy between Pretraining and Post-Training Data

- **作者：** Syeda Nahida Akter, Shrimai Prabhumoye, Eric Nyberg, Mostofa Patwary, Mohammad Shoeybi, Yejin Choi, Bryan Catanzaro
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=VmEkhV2yCX
- **中文提要：** 增强大语言模型推理能力的主流范式，是在高质量、推理密集的数据上做后训练。推理数据也越来越多地进入中期训练，这种做法相对更专有、公开描述更少，而它在预训练中的作用仍不清楚；论文讨论把推理前置，以及预训练与后训练数据的协同。
- **关键词：** SFT, mid-training, post-training, fine-tuning

### FrugalRAG: Less is More in RL Finetuning for Multi-hop Question Answering

- **作者：** Abhinav Java, Srivathsan Koundinyan, Nagarajan Natarajan, Amit Sharma
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=uQKtwdJN0o
- **中文提要：** 依据最终答案给奖励的强化学习，推动了小语言模型在数学和代码等重推理任务上的近期进展。把同样技术用到多跳问答这类检索增强基准上，收益有限，常常落后于监督或仅提示的基线；FrugalRAG 主张此类强化学习微调里少即是多。
- **关键词：** RFT, SFT, fine-tuning

### FSPO: Few-Shot Optimization of Synthetic Preferences Effectively Personalizes to Real Users

- **作者：** Anikait Singh, Sheryl Hsu, Kyle Hsu, Eric Mitchell, Stefano Ermon, Tatsunori Hashimoto, Archit Sharma, Chelsea Finn
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=SzEc5fSBXv
- **中文提要：** 对虚拟助手和内容策展等面向用户的应用来说，大语言模型的有效个性化至关重要。受其强上下文能力启发，FSPO 把奖励建模重述为元学习问题，通过对合成偏好做少样本优化来个性化到真实用户。
- **关键词：** instruction-following, preference-optimization, reward-model

### General Exploratory Bonus for Optimistic Exploration in RLHF

- **作者：** Wendi Li, Changdae Oh, Sharon Li
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=hh91yCiqgS
- **中文提要：** 乐观探索是提高 RLHF 样本效率的核心，现有探索奖励却常常实现不了真正的乐观。理论分析指出，在 KL 或 α-散度正则下，当前形式会无意把探索偏向参考模型的高概率区域，并由此强化某种效应。
- **关键词：** RLHF, alignment

### Generalization of RLVR Using Causal Reasoning as a Testbed

- **作者：** Zhichu Lu, Hongyu Zhao, Shuo Sun, Hao Peng, Rui Ding, Hongyuan Mei
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=DZjbL9BuHs
- **中文提要：** 作为一种后训练范式，RLVR 被用来提升大语言模型在复杂推理任务上的表现。它在什么条件下才能稳健泛化仍缺少探讨，这里以因果推理作为试验台来研究这种泛化。
- **关键词：** RLVR, SFT, post-training, fine-tuning

### Generative Adversarial Post-Training Mitigates Reward Hacking in Live Human-AI Music Interaction

- **作者：** Yusong Wu, Stephen Brade, Teng Ma, Tia-Jane Fowler, Enning Yang, Berker Banar, Aaron Courville, Natasha Jaques, Anna Huang
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=FXm5U16vxD
- **中文提要：** 生成式人工智能的多数应用是人输入提示后等待回应，反应时间和适应性并不重要。现场即兴合奏则是协作交互，需要在看不到对方后续动作的情况下实时协调与适应，并保持多样性以维持创作流动；生成对抗式后训练被用来缓解这类人机音乐交互中的奖励黑客。
- **关键词：** post-training

### Getting Your LLMs Ready for Reinforcement Learning with Lightweight SFT

- **作者：** Xinran Li, Guangda Huzhang, Siqi Shen, Qing-Guo Chen, Zhao Xu, Weihua Luo, Kaifu Zhang, Jun Zhang
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=yezWGJmODg
- **中文提要：** 强化学习已成为大语言模型很强的后训练范式，但效果在不同基座模型之间差异很大。在强化学习前加入 SFT 可以加强训练，摘要仍在追问冷启动阶段应持续多久，以及 SFT 目标是否真正符合有效强化学习的要求。
- **关键词：** SFT, post-training, fine-tuning

### Gradient Intrinsic Dimensionality Alignment：Narrowing The Gap Between Low-Rank Adaptation and Full Fine-Tuning

- **作者：** Jingqi Ye, Haonan He, Minglei Li, Fujun Han, Tao Chen, Peng Ye
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=kObvnQ6pUx
- **中文提要：** 在计算资源有限时，LoRA 及其变体等 PEFT 是适配大型预训练模型的关键工具。这些方法与全量微调之间仍存在明显性能差距，梯度内在维度对齐被用来缩小这一差距。
- **关键词：** LoRA, PEFT, alignment, fine-tuning

### GradPruner: Gradient-guided Layer Pruning Enabling Efficient Fine-Tuning and Inference for LLMs

- **作者：** Wei Huang, Anda Cheng, Yinggui Wang
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=bxzJorqyYM
- **中文提要：** 用下游数据微调大语言模型通常被视为耗时且昂贵，结构化剪枝则主要用于提高预训练模型的推理效率。GradPruner 以梯度引导进行层剪枝，使微调和推理都更高效。
- **关键词：** fine-tuning

### Group-Relative REINFORCE Is Secretly an Off-Policy Algorithm: Demystifying Some Myths About GRPO and Its Friends

- **作者：** Chaorui Yao, Yanxi Chen, Yuchang Sun, Yushuo Chen, Wenhao Zhang, Xuchen Pan, Yaliang Li, Bolin Ding
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=7CFlXvCoN6
- **中文提要：** 真实应用中的实际约束、大语言模型强化学习基础设施的复杂性，以及对方法继续创新的需求，使离策略强化学习越来越受关注。经典 REINFORCE 及 GRPO 等现代变体通常被视作在策略算法。
- **关键词：** GRPO, RFT

### Guided Speculative Inference for Efficient Test-Time Alignment of LLMs

- **作者：** Jonathan Geuter, Youssef Mroueh, David Alvarez-Melis
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=miNzDqDENd
- **中文提要：** GSI 是一种用于大语言模型高效奖励引导解码的算法，服务于测试时对齐。它把软最佳选择式的测试时扩展、奖励模型，以及小型辅助模型给出的推测样本结合在一起。
- **关键词：** reward-model, alignment

### Harder Is Better: Boosting Mathematical Reasoning via Difficulty-Aware GRPO and Multi-Aspect Question Reformulation

- **作者：** Yanqi Dai, Yuxiang Ji, Xiao Zhang, Yong Wang, Xiangxiang Chu, Zhiwu Lu
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=nfURupkdRJ
- **中文提要：** RLVR 为增强大模型的数学推理提供了稳健机制。现有方法无论从算法还是数据看，都系统性地不够重视更难的问题，尽管难题对打磨尚未发展好的能力很重要；难度感知的 GRPO 与多方面的问题改写被用来加强数学推理。
- **关键词：** GRPO, RLVR

### HBO: Hierarchical Balancing Optimization for Fine-Tuning Large Language Models

- **作者：** Weixuan Wang, Minghao Wu, Barry Haddow, Alexandra Birch
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=JnhahbMvRE
- **中文提要：** 在多样数据集的混合上微调大语言模型，会遇到数据不平衡和异质性。已有方法多在数据集之间做全局处理，却忽略单个数据集内部的局部不平衡与异质，从而限制效果；HBO 用分层平衡优化来微调。
- **关键词：** fine-tuning

### Heterogeneous Federated Fine-Tuning with Parallel One-Rank Adaptation

- **作者：** Zikai Zhang, Rui Hu, Jiahao Xu
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=sXPaVl9KU6
- **中文提要：** 微调让大语言模型能有效适配下游任务，联邦学习则借助 LoRA 在分布式客户端间协同微调，并通过不共享原始数据来保护隐私。异构设定下的联邦微调在这里采用并行的秩一适应。
- **关键词：** LoRA, fine-tuning

### High Accuracy, Less Talk (HALT): Reliable LLMs through Capability-Aligned Finetuning

- **作者：** Tim Franzmeyer, Archie Sravankumar, Lijuan Liu, Yuning Mao, Rui Hou, Sinong Wang, Jakob Foerster, Luke Zettlemoyer, Madian Khabsa
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=LYqBnNVaXD
- **中文提要：** 当前模型会对每条提示都作答，但在缺少知识或能力时会给出错误答案，也就是幻觉。HALT 通过与能力对齐的微调，希望回答更可靠、同时少说多余的话。
- **关键词：** post-training, fine-tuning

### HiPO: Self-Hint Policy Optimization for RLVR

- **作者：** Deng Qiyuan, Kehai Chen, Min Zhang, Zhongwen Xu
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=rcb20pHmT1
- **中文提要：** 在需要长程推理和精确执行的领域，RLVR 有望增强大语言模型解决复杂问题的能力。复杂数学题的解答往往取决于一串脆弱的、基于工具的动作；HiPO 用自提示策略优化来服务这类 RLVR。
- **关键词：** GRPO, RLVR

### HiPRAG: Hierarchical Process Rewards for Efficient Agentic Retrieval Augmented Generation

- **作者：** Peilin Wu, Mian Zhang, Kun Wan, Wentian Zhao, Kaiyu He, Xinya Du, Zhiyu Chen
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Gt4v9WBPzm
- **中文提要：** 智能体式检索增强生成能引入大语言模型所缺少的外部信息，从而更好解题和回答问题。过度检索已知信息、以及必要时却不检索等次优搜索行为广泛存在，会造成不必要开销并带来不可靠结果。
- **关键词：** PRM

### Holdout-Loss-Based Data Selection for LLM Finetuning via In-Context Learning

- **作者：** Ling Zhang, Xianliang Yang, Juwon Yu, Park Cheonyoung, Lei Song, Jiang Bian
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Cw9Bxpda2h
- **中文提要：** 微调大型预训练语言模型是对齐人类偏好的常见做法，噪声或偏离目标的样本却会稀释监督。小而挑选得当的数据集常常能达到规模大得多的数据的表现，系统且高效地识别高价值训练数据仍缺少研究；这里借助上下文学习，用留出损失做数据选择。
- **关键词：** DPO, SimPO, SFT, alignment, fine-tuning

### How Far Can Unsupervised RLVR Scale LLM Training?

- **作者：** Bingxiang He, Yuxin Zuo, Zeyuan Liu, Shangziqi Zhao, Zixuan Fu, Junlin Yang, Cheng Qian, Kaiyan Zhang, Yuchen Fan, Ganqu Cui, Xiusi Chen, Youbang Sun, Xingtai Lv, Xuekai Zhu, Li Sheng, Ran Li, Huan-ang Gao, Yuchen Zhang, Lifan Yuan, Bowen Zhou, Zhiyuan Liu, Ning Ding
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=VesLZukY5E
- **中文提要：** 无监督的 RLVR 不依赖真实标签来构造奖励，从而把大语言模型训练扩展到监督瓶颈之外。近期工作利用模型内在信号并取得早期增益，潜力与局限仍不清楚；这篇工作追问这种无监督训练能走多远。
- **关键词：** RLVR

### IA2: Alignment with ICL Activations improves Supervised Fine-Tuning

- **作者：** Aayush Mishra, Daniel Khashabi, Anqi Liu
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=r99m9ziONQ
- **中文提要：** SFT 通过训练权重，使模型对查询产出预期的目标回答，从而特化行为。与之相对，上下文学习在推理阶段用提示中的指令或示例来适应模型；IA2 用上下文学习的激活做对齐，以改进监督微调。
- **关键词：** SFT, alignment, fine-tuning

### IDEAL: Data Equilibrium Adaptation for Multi-Capability Language Model Alignment

- **作者：** Chenlin Ming, Chendi Qu, Qizhi Pei, Zhuoshi Pan, Yu Li, Xiaoming Duan, Lijun Wu, Conghui He
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=n9wS0Hdvri
- **中文提要：** 在多样指令数据上做 SFT，使大语言模型取得了突出表现。同时训练多种能力时，由不同领域数据量决定的混合训练集会直接影响最终性能；IDEAL 用数据均衡适应来做多能力对齐。
- **关键词：** SFT, alignment, fine-tuning

### IGU-LoRA: Adaptive Rank Allocation via Integrated Gradients and Uncertainty-Aware Scoring

- **作者：** Xuan Cui, HuiYue Li, Run Zeng, Yunfei Zhao, Jinrui Qian, Wei Duan, Bo Liu, Zhanpeng Zhou
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=MnToYQx9My
- **中文提要：** 参数规模上来之后，全参数微调在计算和显存上都不现实。PEFT 只更新一小部分任务相关参数，并冻结基座模型来缓解这一问题；IGU-LoRA 结合积分梯度与不确定性感知评分，自适应地分配秩。
- **关键词：** LoRA, PEFT, fine-tuning

### Importance Sampling for Multi-Negative Multimodal Direct Preference Optimization

- **作者：** Xintong Li, Chuhan Wang, Junda Wu, Rohan Surana, Tong Yu, Julian McAuley, Jingbo Shang
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=HEFPwoGtTj
- **中文提要：** DPO 最近已从纯文本模型扩展到视觉语言模型。现有方法依赖过于简化的成对比较，只通过基本扰动或基于相似度的检索产生负图像，难以刻画多模态偏好的复杂性，并引发优化偏差和幻觉；重要性采样被用于多负样本的多模态 DPO。
- **关键词：** DPO, preference-optimization, alignment

### Incentivizing Consistent, Effective and Scalable Reasoning Capability in Audio LLMs via Reasoning Process Rewards

- **作者：** Jiajun Fan, Roger Ren, Jingyuan Li, Rahul Pandey, Prashanth Gurunath Shivakumar, Ivan Bulyko, Ankur Gandhe, Ge Liu, Yile Gu
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=DUr48hxO2h
- **中文提要：** 推理在音频大语言模型中的作用仍很少被研究：加入推理过程在推理时常常不升反降，作者称之为测试时逆缩放，推理链越长结果越差。他们认为根源不是推理本身的根本限制，而是训练不足。
- **关键词：** GRPO, PRM

### Influence-Preserving Proxies for Gradient-Based Data Selection in LLM FineTuning

- **作者：** Sirui Chen, Yunzhe Qi, Mengting Ai, Yifan Sun, Ruizhong Qiu, Jiaru Zou, Jingrui He
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=PDNpRLxDlI
- **中文提要：** SFT 严重依赖选出对下游表现最有益的训练数据。TracIn 和影响函数等基于梯度的方法用影响度识别有用样本，但计算代价随规模增长不佳，对参数量极大的语言模型不实用；保持影响的代理被用来支持这类梯度数据选择。
- **关键词：** SFT, alignment, fine-tuning

### Inverse Reinforcement Learning with Dynamic Reward Scaling for LLM Alignment

- **作者：** Ruoxi Cheng, Hao-Xuan Ma, Weixin Wang, Ranjie Duan, Jiexi Liu, Xiaoshuang Jia, Simeng Qin, Xiaochun Cao, Yang Liu, Yang Liu
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=K0Zh6mzTzc
- **中文提要：** 对齐对安全部署大语言模型至关重要。现有技术或是基于奖励，在偏好对上训练奖励模型再用强化学习优化，或是无奖励，直接在有排序的输出上微调；逆强化学习与动态奖励缩放在这里被结合起来做对齐。
- **关键词：** GRPO, reward-model, alignment, fine-tuning

### Invisible Safety Threat: Malicious Finetuning for LLM via Steganography

- **作者：** Guangnian Wan, Xinyin Ma, Gongfan Fang, Xinchao Wang
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=6cEPDGaShH
- **中文提要：** 弄清并应对大语言模型潜在的安全对齐风险，对其安全、可信的部署至关重要。文中强调一种隐蔽威胁：遭破坏的模型可以维持看似正常的安全对齐，同时暗中生成有害内容，途径是借助隐写进行恶意微调。
- **关键词：** alignment, fine-tuning

### Is On-Policy Data always the Best Choice for Direct Preference Optimization-Based LM Alignment?

- **作者：** Zetian Sun, dongfang li, Xuhui Chen, Baotian Hu, Min Zhang
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=tz9mJmgrdM
- **中文提要：** 语言模型与人类偏好的对齐，通常被写成优化策略，使其最大化能反映人类偏好的期望奖励。
- **关键词：** DPO, preference-optimization, alignment, fine-tuning

### JailbreakLoRA: Your Downloaded LoRA from Sharing Platforms might be Unsafe

- **作者：** Fanjunduo Wei, Zhenheng Tang, Rongfei Zeng, Tongliang Liu, Chengqi Zhang, Xiaowen Chu, Bo Han
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=4YgvVRoSnF
- **中文提要：** LoRA 因即插即用、能以较低成本提升大语言模型表现，推动了共享平台的出现，但这类平台上的越狱与后门风险仍少有研究。
- **关键词：** LoRA

### Keep the Best, Forget the Rest: Reliable Alignment with Order-Aware Preference Optimization

- **作者：** Jiahui Zhu, Yuanjie Shi, Xiyue Peng, Xin Liu, Yan Yan, Honghao Wei
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=LrHfYPFTtg
- **中文提要：** DPO 借助成对比较把大语言模型对齐到人类偏好，却对训练样本质量很敏感：参考策略对齐较差时，含糊样本会主导梯度并损害泛化。
- **关键词：** DPO, preference-optimization, alignment

### LaSeR: Reinforcement Learning with Last-Token Self-Rewarding

- **作者：** Wenkai Yang, Weijie Liu, Ruobing Xie, Yiju Guo, Lulu Wu, Saiyong Yang, Yankai Lin
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=1OhgEmix20
- **中文提要：** 可验证奖励强化学习（RLVR）被用来增强大语言模型的推理；为弥补测试时缺少验证信号，已有工作把自我验证训练并入标准 RLVR，使推理与验证走向统一。
- **关键词：** RLVR, self-rewarding

### LD-MoLE: Learnable Dynamic Routing for Mixture of LoRA Experts

- **作者：** Yuan Zhuang, Yi Shen, Yuexin Bian, Qing Su, Shihao Ji, Yuanyuan Shi, Fei Miao
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=4ST2YyTjI7
- **中文提要：** 把参数高效微调（PEFT）与混合专家结合，能有效把大语言模型适配到下游任务，但多数做法仍用常规 TopK 路由，既要细调超参数，又给每个词元固定分配专家数。
- **关键词：** LoRA, PEFT, fine-tuning

### Learning Correlated Reward Models: Statistical Barriers and Opportunities

- **作者：** Yeshwanth Cherapanamjeri, Constantinos C Daskalakis, Gabriele Farina, Sobhan Mohammadpour
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=TbEyl6krsY
- **中文提要：** 随机效用模型是刻画用户偏好、并支撑 RLHF 奖励建模的经典框架，但其无关选项独立性假设会把全部人类偏好坍缩到单一底层效用函数，得到的刻画因此偏粗。
- **关键词：** RLHF, reward-model

### Learning from Noisy Preferences: A Semi-Supervised Learning Approach to Direct Preference Optimization

- **作者：** Xinxin Liu, Ming Li, Zonglin Lyu, Yuzhang Shang, Chen Chen
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=rRc04jyoAk
- **中文提要：** 人类视觉偏好同时涉及美学、细节保真和语义对齐，现有数据集却只提供单一的整体标注，使各维度优劣不一的图像被简单标成胜者或负者，标签噪声很重。
- **关键词：** DPO, preference-optimization, reward-model, alignment

### Learning to Reason as Action Abstractions with Scalable Mid-Training RL

- **作者：** Shenao Zhang, Donghan Yu, Yihao Feng, Bowen Jin, Zhaoran Wang, John Peebles, Zirui Wang
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=uWd9A1zp0Y
- **中文提要：** 大语言模型能靠强化学习取得好效果，但要充分释放这一潜力需要中期训练：既学到较强的策略先验，又便于通过在线交互加快后续学习。
- **关键词：** RLVR, mid-training, post-training, fine-tuning

### Learning to summarize user information for personalized reinforcement learning from human feedback

- **作者：** HyunJi Nam, Yanming Wan, Mickel Liu, Peter Ahnn, Jianxun Lian, Natasha Jaques
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Ar078WR3um
- **中文提要：** 助手的日常用途增多后，按不同用户的偏好与目标个性化回答变得重要；RLHF 虽能普遍提升有用性与流畅度，却把整个用户群体当作同一对象来建模。
- **关键词：** RLHF, reward-model, alignment

### Learning What Reinforcement Learning Can't: Interleaved Online Fine-Tuning for Hardest Questions

- **作者：** Lu Ma, Hao Liang, Meiyi Qiang, Lexiang Tang, Xiaochen Ma, Zhen Wong, Junbo Niu, Chengyu Shen, Runming He, Yanhao Li, Wentao Zhang, Bin CUI
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=LzCBLrNoyM
- **中文提要：** 推理能力可以经由强化学习涌现，但现有强化学习主要依据模型已有知识来优化，仍不足以诱导出超出基座模型局限的能力。
- **关键词：** RLVR, SFT, fine-tuning

### Learn More with Less: Uncertainty Consistency Guided Query Selection for RLVR

- **作者：** Hao Yi, Yulan Hu, Xin Li, Sheng Ouyang, Lizhong Ding, Yong Liu
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=OOTokVgBY6
- **中文提要：** 大语言模型借助可验证奖励强化学习（RLVR）提升了数学推理，可现有算法查询预算大，标注因此代价很高。
- **关键词：** RLVR, alignment

### Leveraging Pretrained Knowledge at Inference Time: LoRA-Gated Contrastive Decoding for Multilingual Factual Language Generation in Adapted LLMs

- **作者：** Gwangseon Jang, Hongseok Choi, Chanuk lim, Kyong-Ha Lee, Mun Yi
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=vzlDdOzXAh
- **中文提要：** 经持续预训练或指令调优适配到特定语言的大语言模型，常因灾难性遗忘而产生事实错误；在多语言场景中，适配尤其可能用语言特有模式盖过通用世界知识。
- **关键词：** instruction-tuning, LoRA, continued-pretraining

### Linking Process to Outcome: Conditional Reward Modeling for LLM Reasoning

- **作者：** Zheng Zhang, Ziwei Shan, Kaitao Song, Yexin Li, Kan Ren
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=4DJoBOQNd0
- **中文提要：** 过程奖励模型通过引导逐步推理来提升大语言模型的推理能力，但现有模型要么孤立处理每一步、抓不住步骤间依赖，要么难以让过程奖励与最终结果对齐。
- **关键词：** PRM, reward-model

### LLMs are Greedy Agents: Effects of RL Fine-tuning on Decision-Making Abilities

- **作者：** Thomas Schmied, Jörg Bornschein, Jordi Grau-Moya, Markus Wulfmeier, Razvan Pascanu
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=weUP6H5Ko9
- **中文提要：** 大语言模型的成功带动了智能体应用，一个关键假设是它们可以借助常识和思维链推理，有效探索并高效求解复杂领域。
- **关键词：** RFT, fine-tuning

### Long-Document QA with Chain-of-Structured-Thought and Fine-Tuned SLMs

- **作者：** Zhuowen Liang, Xiaotian LIN, Zhengxuan Zhang, Yuyu Luo, Haixun Wang, Nan Tang
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=faECRsdRav
- **中文提要：** 直接在冗长且嘈杂的文档上推理容易出错，因此该研究考察文档问答：把分散证据整理成表格、图或文本块等结构化输出，以支撑可靠、可核验的问答。
- **关键词：** GRPO, SFT, alignment, fine-tuning

### LoRAGen: Structure-Aware Weight Space Learning for LoRA Generation

- **作者：** Hao Huang, Jingtao Ding, Mengqi Liao, Xin Wang, Jinyang Ban, Yuan Yuan, Huaiyu Wan, Yong Li
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=mrafO7aTYj
- **中文提要：** LoRA 的普及带来了从任务描述直接合成适配权重、以免逐任务训练的需求；LoRAGen 是一种结构感知方法，可根据自然语言描述生成 LoRA 参数。
- **关键词：** LoRA, fine-tuning

### LoRA meets Riemannion: Muon Optimizer for Parametrization-independent Low-Rank Adapters

- **作者：** Vladimir Bogachev, Vladimir Aletov, Alexander Molozhavenko, Denis Bobkov, Vera Soboleva, Aibek Alanov, Maxim Rakhuba
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=WtbXgc9GVA
- **中文提要：** 一套完全黎曼的 LoRA 框架把低秩适配器直接放在固定秩流形上优化，从而消除标准欧氏优化器里的参数化歧义。
- **关键词：** LoRA

### LoRA-Mixer: Coordinate Modular LoRA Experts Through Serial Attention Routing

- **作者：** Wenbing Li, Zikai Song, Hang Zhou, Junqing Yu, Yunyao Zhang, Wei Yang
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=GMP1S4R6Ke
- **中文提要：** 多任务适配中把 LoRA 与混合专家结合时，整层替换注意力或前馈、或并行挂上专家分支，会损害参数效率并限制任务特化；LoRA-Mixer 则作为模块化混合专家框架，把任务特定的 LoRA 专家路由进核心部分。
- **关键词：** LoRA

### LoRA-S: An Efficient Low Rank Adaptation scheme via Sylvester equation

- **作者：** Jinyang ZHENG, Tong Wu
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Guo2XGgxZA
- **中文提要：** 近年不少 LoRA 研究旨在加快其收敛，该工作借助微分几何中的水平提升理论，在相应商流形上建立一般迭代格式。
- **关键词：** LoRA

### Lost in the Non-convex Loss Landscape: How to Fine-tune the Large Time Series Model?

- **作者：** Xu Zhang, Peng Wang, Wei Wang
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=8o4t5DHaE1
- **中文提要：** 大型时间序列模型因上下文灵活、可扩展和任务通用而受到关注，并优于专门模型，但已有研究表明预训练后的损失景观可能病态且非凸，可训练性受限。
- **关键词：** fine-tuning

### Mapping Post-Training Forgetting in Language Models at Scale

- **作者：** Jackson Harmon, Andreas Hochlehnert, Matthias Bethge, Ameya Prabhu
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=qCIg2WGudx
- **中文提要：** 规模化后训练推动了语言模型的许多大幅能力提升，但它对预训练知识的影响仍不清楚，而且并非所有遗忘都等价。
- **关键词：** SFT, instruction-tuning, continued-pretraining, post-training

### MCIF: Multimodal Crosslingual Instruction-Following Benchmark from Scientific Talks

- **作者：** Sara Papi, Maike Züfle, Marco Gaido, Beatrice Savoldi, Danni Liu, Ioannis Douros, Luisa Bentivogli, Jan Niehues
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=PtPYZYfa0h
- **中文提要：** 多模态大语言模型把文本、语音和视觉收进同一框架，并朝多样复杂任务上的通用指令遵循发展；一个关键前沿是评估它们在短输入与长输入上的跨语言和多模态能力。
- **关键词：** instruction-following

### Measuring Audio's Impact on Correctness: Audio-Contribution-Aware Post-Training of Large Audio Language Models

- **作者：** Haolin He, Xingjian Du, Renhe Sun, Zheqi Dai, Yujia Xiao, Mingru Yang, Jiayi Zhou, Xiquan Li, Zhengxi Liu, Zining Liang, Chunyat Wu, Qianhua He, Tan Lee, Xie Chen, Wei-Long Zheng, Weiqiang Wang, Mark D. Plumbley, Jian Liu, Qiuqiang Kong
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=sJ0jUO9Mxr
- **中文提要：** 大型音频语言模型面向多样音频任务，是多模态人工智能的重要方向；其后训练因相对基础模型有明显性能提升而受到更多关注。
- **关键词：** SFT, post-training, fine-tuning

### Membership Inference Attacks Against Fine-tuned Diffusion Language Models

- **作者：** Yuetian Chen, Kaiyuan Zhang, Yuntao Du, Edoardo Stoppa, Charles Fleming, Ashish Kundu, Bruno Ribeiro, Ninghui Li
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=oWKJursYpW
- **中文提要：** 扩散语言模型以双向掩码词元预测区别于自回归语言模型，但其经由成员推断攻击发生隐私泄露的风险仍严重缺乏研究。
- **关键词：** fine-tuning

### Merge before Forget: A Single LoRA Continual Learning via Continual Merging

- **作者：** Fuli Qiao, Mehrdad Mahdavi
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=i1Rj7yU6eF
- **中文提要：** 参数高效持续学习希望让大语言模型在适应新任务的同时减轻灾难性遗忘；现有 LoRA 持续学习通常保留并冻结已学适配器，或生成数据表示来对抗遗忘，并以此支撑新的 LoRA 学习新任务。
- **关键词：** LoRA, PEFT

### MergeTune: Continued Fine-Tuning of Vision-Language Models

- **作者：** Wenqing Wang, Da Li, Xiatian Zhu, Josef Kittler
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=MAApSY32Z6
- **中文提要：** 微调 CLIP 等视觉语言模型常常遗忘预训练知识；已有工作主要试图在适应过程中减轻遗忘，但遗忘在这一过程中往往仍然不可避免。
- **关键词：** fine-tuning

### Meta-UCF: Unified Task-Conditioned LoRA Generation for Continual Learning in Large Language Models

- **作者：** ShiLin Xiao, Tianxiang Xu, Canran Xiao, Weihao Luo, Liwei Hou, Chuangxin Zhao
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=iNg5KL7eTC
- **中文提要：** 新任务持续到来时，现有参数高效微调要么随任务跨度线性膨胀，要么牺牲深度适应，灾难性遗忘仍未解决；目标是让冻结的大语言模型面对无界任务流时，做到存储开销恒定的即时适应。
- **关键词：** LoRA, PEFT, fine-tuning

### MiSS: Revisiting the Trade-off in LoRA with an Efficient Shard-Sharing Structure

- **作者：** Jiale Kang, Qingyu Yin
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=gohmWoUSoS
- **中文提要：** LoRA 被广泛用于参数高效微调，收敛偏慢催生了许多变体，但现有做法仍难以同时改善性能、显存占用和计算效率。
- **关键词：** LoRA, PEFT, fine-tuning

### Mitigating Mismatch within Reference-based Preference Optimization

- **作者：** Suqin Yuan, Xingrui Yu, Jiyang Zheng, Lei Feng, Dadong Wang, Ivor Tsang, Tongliang Liu
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=k79Un1LSXy
- **中文提要：** DPO 已成为大语言模型离线偏好对齐的常用做法，但对参考策略的依赖带来关键张力：每次更新都相对参考来加权，从而把更新限制在可信区域内以稳定训练。
- **关键词：** DPO, preference-optimization, alignment

### Mitigating Non-IID Drift in Zeroth-Order Federated LLM Fine-Tuning with Transferable Sparsity

- **作者：** Yide Ran, Wentao Guo, Jingwei Sun, Yanzhou Pan, Xiaodong Yu, Hao Wang, Jianwen Xie, Yiran Chen, Denghui Zhang, Zhaozhuo Xu
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=2DuMBKVbX2
- **中文提要：** 联邦学习让大语言模型能在去中心化、非独立同分布的客户端上协同微调，但庞大参数量带来显存与通信压力；Meerkat 是面向这种联邦微调的稀疏零阶优化方法。
- **关键词：** fine-tuning

### Mitigating the Safety Alignment Tax with Null-Space Constrained Policy Optimization

- **作者：** Yifan Niu, Han Xiao, Dongyi Liu, Nuo Chen, Jia Li
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=GFyVxtyMvq
- **中文提要：** 实际部署要求大语言模型的行为符合人类价值、社会规范与伦理原则，但强化学习下的安全对齐常会遗忘已学到的通用能力，也就是所谓的对齐税。
- **关键词：** instruction-following, alignment

### MOLM: Mixture of LoRA Markers

- **作者：** Samar Fares, Nurbek Tastan, Noor Hussein, Karthik Nandakumar
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=1fYQOZovHR
- **中文提要：** 生成模型能够大规模产出逼真图像，这使检测合成图像、并把图像归因到具体来源成为突出问题。
- **关键词：** LoRA

### MoRA: Missing Modality Low-Rank Adaptation for Visual Recognition

- **作者：** Shu Zhao, Nilesh Ahuja, Tan Yu, Tianyi Shen, Vijaykrishnan Narayanan
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ZgQnIPG4uV
- **中文提要：** 预训练视觉语言模型在视觉识别上表现突出，但训练和推理都默认多模态输入齐全；现实中则可能因隐私、采集困难或资源限制而缺少某些模态。
- **关键词：** LoRA, PEFT, fine-tuning

### Multi-objective Large Language Model Alignment with Hierarchical Experts

- **作者：** Zhuo Li, Guodong DU, Weiyang Guo, Yigeng Zhou, Xiucheng Li, Wenya Wang, Fangming Liu, Yequan Wang, Deheng Ye, Min Zhang, Jing Li
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=UhmEdfAk46
- **中文提要：** 让大语言模型同时满足多个目标仍然困难，因为人类偏好多样且常常相互冲突；现有对齐方法难以平衡取舍，往往需要高昂的再训练，或在偏好的帕累托前沿上表现欠佳。
- **关键词：** LoRA, PEFT, alignment

### Multiplayer Nash Preference Optimization

- **作者：** Fang Wu, Xu Huang, Weihao Xuan, Zhiwei Zhang, Yijia Xiao, Frank Wan, Xiaomin Li, Bing Hu, Peng Xia, Jure Leskovec, Yejin Choi
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=x7aLhLMVn1
- **中文提要：** RLHF 是把大语言模型对齐到人类偏好的标准范式，但基于 Bradley–Terry 假设的奖励方法难以刻画真实偏好中的非传递性与异质性。
- **关键词：** RLHF, instruction-following, preference-optimization, alignment

### Multi-Scale Hypergraph Meets LLMs: Aligning Large Language Models for Time Series Analysis

- **作者：** Zongjiang Shang, Dongliang Cui, Binqing Wu, Ling Chen
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=SbBX2dCw3y
- **中文提要：** 用预训练大语言模型做时间序列分析已经取得明显进展，其核心是把自然语言与时间序列这两种模态有效对齐。
- **关键词：** alignment

### Narrow Finetuning Leaves Clearly Readable Traces in Activation Differences

- **作者：** Julian Minder, Clément Dumas, Stewart Slocum, Helena Casademunt, Cameron Holmes, Robert West, Neel Nanda
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=qyVzZsrsnS
- **中文提要：** 窄域微调既用于把大语言模型适配到特定任务，也用于构造具有已知异常性质、便于安全研究的模型；模型差分通过比较基座与微调后模型的差异，来理解微调如何改变网络。
- **关键词：** fine-tuning

### Neuron-Aware Data Selection in Instruction Tuning for Large Language Models

- **作者：** Xin Chen, Junchao Wu, Shu Yang, Runzhe Zhan, Zeyu Wu, Min Yang, Shujian Huang, Lidia Chao, Derek Wong
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=uq6UWRgzMr
- **中文提要：** 指令微调能释放大语言模型的能力，但过多指令数据可能损害表现，而精选一小部分高质量数据则能明显增强能力。
- **关键词：** instruction-tuning

### New Hybrid Fine-Tuning Paradigm for LLMs: Algorithm Design and Convergence Analysis Framework

- **作者：** Shaocong Ma, Peiran Yu, Heng Huang
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=avgMb57IP5
- **中文提要：** 微调大语言模型通常要么更新全部参数，要么用参数高效微调（PEFT）只调一小部分；全量更新计算昂贵，PEFT 又往往难以学到新知识、表现不够理想。
- **关键词：** PEFT, fine-tuning

### No, of Course I Can! Deeper Fine-Tuning Attacks That Bypass Token-Level Safety Mechanisms

- **作者：** Joshua Kazdan, Abhay Puri, Rylan Schaeffer, Lisa Yu, Chris Cundy, Jason Stanley, Sanmi Koyejo, Krishnamurthy Dvijotham
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=QzIQgloYgX
- **中文提要：** 主要的语言模型服务提供方允许客户为特定用途微调前沿模型，并用过滤器阻止在明显有害的数据上微调，以防止滥用。
- **关键词：** alignment, fine-tuning

### Not All Documents Are What You Need for Extracting Instruction Tuning Data

- **作者：** Chi Zhang, Huaping Zhong, Hongtao Li, Chengliang Chai, Hongjiawei, Yu-Ping Wang, Yuhao Deng, Jiacheng Wang, Yizhou Yan, Qiu Jiantao, Conghui He, Lei Cao
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=mIO3kVDC2L
- **中文提要：** 指令微调能提升大语言模型表现，但依赖高质量训练数据；近来常用大语言模型合成数据，并以问答对等种子来增强训练。
- **关键词：** instruction-tuning

### ODESteer: A Unified ODE-Based Steering Framework for LLM Alignment

- **作者：** Hongjue Zhao, Haosen Sun, Jiangtao Kong, Xiaochang Li, Qineng Wang, Liwei Jiang, Qi Zhu, Tarek Abdelzaher, Yejin Choi, Manling Li, Huajie Shao
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=CFewUmgIIL
- **中文提要：** 激活引导（表征工程）在推理时操控内部激活，为对齐大语言模型提供轻量途径；现有方法既缺少指导引导方向设计的统一理论框架，又过度依赖单步引导。
- **关键词：** alignment

### Omni-Reward: Towards Generalist Omni-Modal Reward Modeling with Free-Form Preferences

- **作者：** Zhuoran Jin, Hongbang Yuan, Kejian Zhu, Jiachun Li, Pengfei Cao, Yubo Chen, Kang Liu, Jun Zhao
- **会议：** ICLR 2026 · Main · Oral
- **官方论文页：** https://openreview.net/forum?id=2026-Oral--14986-d70e372e
- **中文提要：** 奖励模型对把人工智能行为对齐到人类偏好至关重要，但多数模型偏重文本和图像、对视频、音频及其他模态支持有限，而且在固定的二元偏好对上训练，难以涵盖偏好的复杂与多样。
- **关键词：** instruction-tuning, reward-model, alignment

### On-Policy RL Meets Off-Policy Experts: Harmonizing Supervised Fine-Tuning and Reinforcement Learning via Dynamic Weighting

- **作者：** Wenhao Zhang, Yuexiang Xie, Yuchang Sun, Yanxi Chen, Guoyin Wang, Yaliang Li, Bolin Ding, Jingren Zhou
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=dCm9bBrk5d
- **中文提要：** 监督微调（SFT）与强化学习是提炼大语言模型能力并对齐其行为的两条主要后训练路线；把二者结合起来的现有做法，常有打乱已有回答模式、并对专家数据过拟合的风险。
- **关键词：** SFT, post-training, alignment, fine-tuning

### On-the-Fly Adaptation to Quantization: Configuration-Aware LoRA for Efficient Fine-Tuning of Quantized LLMs

- **作者：** Rongguang Ye, Ming Tang, Edith Ngai
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=9OUg0nJE72
- **中文提要：** 把大型预训练模型部署到端侧以保护隐私，需要有效压缩；近期工作把量化与高精度 LoRA 适配器的微调结合起来，在缩小模型的同时缓解量化带来的精度损失。
- **关键词：** LoRA, fine-tuning

### On the Generalization of SFT: A Reinforcement Learning Perspective with Reward Rectification

- **作者：** Yongliang Wu, Yizhou Zhou, Ziheng Zhou, Yingzhe Peng, Xinyu Ye, Xinting Hu, Wenbo Zhu, Lu Qi, Ming-Hsuan Yang, xu yang
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Lv7PjbcaMi
- **中文提要：** 针对监督微调（SFT）相对强化学习泛化不足的问题，该工作给出一种有理论动机的改进；分析表明标准 SFT 梯度隐含一种有问题的奖励结构，可能严重限制泛化。
- **关键词：** SFT, fine-tuning

### On the Shelf Life of Fine-Tuned LLM-Judges: Future-Proofing, Backward-Compatibility, and Question Generalization

- **作者：** Janvijay Singh, Austin Xu, Yilun Zhou, Yefan Zhou, Dilek Hakkani-Tür, Shafiq Joty
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=fVTqNpny5r
- **中文提要：** 以大模型充当评判者，既用于评估自由文本回答，也用于对齐与微调中的奖励建模；用评判专用数据微调评判器，常比直接把前沿模型当作评判者更受青睐，因为较小模型就能表现更好，并对常见偏差更稳健。
- **关键词：** DPO, SFT, reward-model, alignment, fine-tuning

### OPPO: Accelerating PPO-based RLHF via Pipeline Overlap

- **作者：** Kaizhuo Yan, YingJie Yu, Yifan Yu, Haizhong Zheng, Fan Lai
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=31Mr6wLBeF
- **中文提要：** 基于 PPO 的 RLHF 被广泛用于把大语言模型对齐到人类偏好，但训练流水线因多模型串行依赖（奖励模型要等行动者的输出）以及回复长度的长尾而效率很低，少数很长的回复会拖慢整体。
- **关键词：** RLHF, reward-model, alignment

### OR-PRM: A Process Reward Model for Algorithmic Problem in Operations Research

- **作者：** Yilin Wang, Heng Zhou, Dongxing Mao, Linjie Li, Jingru Tan, Haochen Han, Zhengyuan Yang, Alex Jinpeng Wang, Min Li
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=tFEAzYdz92
- **中文提要：** 带过程奖励模型的大语言模型展现出较强推理能力，但在运筹学中的潜力尚未探索；该工作给出面向运筹学的过程奖励模型，并发现直接在主流数据集上训练效果出乎意料地弱。
- **关键词：** PRM, reward-model

### P$^2$-DPO: Grounding Hallucination in Perceptual Processing via Calibration Direct Preference Optimization

- **作者：** RuiPeng Zhang, Zhihao Li, Haozhang Yuan, C.L.Philip Chen, Tong Zhang
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ekOwxTn65Y
- **中文提要：** 幻觉问题在大视觉语言模型中受到关注，DPO 希望直接从人类提供的纠正偏好中学习，从而处理幻觉。
- **关键词：** DPO, preference-optimization

### PALC: Preference Alignment via Logit Calibration

- **作者：** Sanghyun Lee, Hoh In
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=0cmuYj3WeG
- **中文提要：** 把大语言模型对齐到人类偏好，通常需要计算开销很大的训练或复杂的奖励结构；PALC 是一种参数高效框架，通过在词表空间直接校准，在测试时完成对齐。
- **关键词：** preference-optimization, reward-model, PEFT, alignment

### PASER: Post-Training Data Selection for Efficient Pruned Large Language Model Recovery

- **作者：** Bowei He, Lihao Yin, Huiling Zhen, Xiaokun Zhang, Mingxuan Yuan, Chen Ma
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=mWKvHBINSl
- **中文提要：** 模型剪枝能有效压缩大语言模型，但这一过程常常明显削弱模型能力。
- **关键词：** instruction-tuning, post-training

### PathChat-SegR1: Reasoning Segmentation in Pathology via SO-GRPO

- **作者：** Zelin Liu, Dongdong Chen, Yusong Sun, Yuqi Hu, Huang Jie, Sicheng Dong, Xu Han, Hongmei Yi, Qiyuan Bao, Lichi Zhang
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=DQESI75YrD
- **中文提要：** 病理图像分割要应对训练分布之外的组织形态和新病变，传统闭集分割难以泛化；推理式分割则通过文本查询提示来实现零样本泛化。
- **关键词：** GRPO

### PCLR: Progressively Compressed LoRA for Multimodal Continual Instruction Tuning

- **作者：** weicheng meng, Jingyang Qiao, Zhizhong Zhang, Shaohui Liu, Yuan Xie
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=WdP1NVSzsz
- **中文提要：** 持续指令微调让大型多模态模型无需重训就能快速适应新任务，但会遭遇灾难性遗忘；靠增加新分支来扩展模型可以容纳新知识，却带来很大的内存开销。
- **关键词：** instruction-tuning, LoRA

### PCPO: Proportionate Credit Policy Optimization for Preference Alignment of Image Generation Models

- **作者：** Jeongjae Lee, Jong Chul YE
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=alY08iknli
- **中文提要：** 强化学习推进了文生图模型的对齐，但先进的策略梯度方法仍受训练不稳定和高方差困扰，拖慢收敛并损害图像质量；分析指出关键原因是信用分配不成比例，这与生成采样器的数学结构有关。
- **关键词：** preference-optimization, alignment

### pFedMMA: Personalized Federated Fine-Tuning with Multi-Modal Adapter for Vision-Language Models

- **作者：** Sajjad Ghiasvand, Mahnoosh Alizadeh, Ramtin Pedarsani
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=aX3E6LirK5
- **中文提要：** CLIP 等视觉语言模型在零样本和少样本设定下泛化突出，但要高效适配到去中心化、异构的数据仍有困难；个性化联邦学习中常用提示调优，现有方法往往为了个性化而牺牲泛化。
- **关键词：** PEFT, fine-tuning

### P-GenRM: Personalized Generative Reward Model with Test-time User-based Scaling

- **作者：** Pinyi Zhang, Ting-En Lin, Yuchuan Wu, Jingyang Chen, Zongqi Wang, Hua Yang, Bing Zhao, Fei Huang, Yongbin Li, Kai Zhang
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=hXNApWLBZG
- **中文提要：** 个性化对齐通常借助强化学习，让回答贴合单个用户的偏好；关键难点是在开放式场景中获得准确且因人而异的奖励信号。
- **关键词：** reward-model, alignment

### PiCa: Parameter-Efficient Fine-Tuning with Column Space Projection

- **作者：** Junseo Hwang, Wonguk Cho, Taesup Kim
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=32G5SjCAMV
- **中文提要：** 打造面向专门任务与领域的专家模型需要微调大型基础模型，但更新全部参数在计算上不可行；用 LoRA 等参数高效微调（PEFT）减少可训练参数，既能降低训练成本，也有助于缓解存储与缓存压力。
- **关键词：** LoRA, PEFT, fine-tuning

### PLoP: Precise LoRA Placement for Efficient Finetuning of Large Models

- **作者：** Soufiane Hayou, Nikhil Ghosh, Bin Yu
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=3lGkVgNZ5a
- **中文提要：** 低秩适配是大模型常用的微调方法，显存占用小，使从业者能以远低于全量微调的代价把大模型适配到特定任务。
- **关键词：** SFT, LoRA, fine-tuning

### Pose-RFT: Aligning MLLMs for 3D Pose Generation via Hybrid Action Reinforcement Fine-Tuning

- **作者：** Bao Li, Xiaomei Zhang, Miao Xu, Zhaoxin Fan, Xiangyu Zhu, Zhen Lei
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ea1U1MgbdT
- **中文提要：** 从文本或图像等多模态输入生成三维人体姿态，需要同时抓住丰富的语义对应与空间对应；面向姿态的多模态大语言模型虽有潜力，但其监督微调（SFT）范式难以处理这一任务固有的歧义。
- **关键词：** RFT, SFT, alignment, fine-tuning

### Post-training Large Language Models for Diverse High-Quality Responses

- **作者：** Yilei Chen, Souradip Chakraborty, Lorenz Wolf, Ioannis Paschalidis, Aldo Pacchiano
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=BV3bLKaJ3Y
- **中文提要：** 强化学习已成为大语言模型后训练的常用途径，在提升下游任务表现的同时，却常常压低输出多样性，使回答变得狭窄而套路化。
- **关键词：** instruction-following, post-training

### Preserve and Sculpt: Manifold-Aligned Fine-tuning of Vision-Language Models for Few-Shot Learning

- **作者：** Dexia Chen, Qianjie Zhu, Weibing Li, Yue Yu, Tong Zhang, Ruixuan Wang
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ZGJJF1e2u0
- **中文提要：** 以 CLIP 为代表的预训练视觉语言模型在少样本图像分类上展现出很大潜力，并催生了多种迁移策略。这些策略借助模型已有知识做领域适应，同时用参数高效微调或基于实例的一致性约束来减轻过拟合。
- **关键词：** PEFT, alignment, fine-tuning

### Pre-training LLM without Learning Rate Decay Enhances Supervised Fine-Tuning

- **作者：** Kazuki Yano, Shun Kiyono, Sosuke Kobayashi, Sho Takase, Jun Suzuki
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=JnebU2QLdH
- **中文提要：** 该研究考察大规模预训练中的学习率调度，如何影响监督微调（SFT）之后的下游表现，并指出基于衰减的调度器被广泛用于压低预训练损失。
- **关键词：** SFT, mid-training, fine-tuning

### Programming by Backprop: An Instruction is Worth 100 Examples When Finetuning LLMs

- **作者：** Jonathan Cook, Silvia Sapora, Arash Ahmadian, Akbir Khan, Tim Rocktaeschel, Jakob Foerster, Laura Ruis
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=y1OWj26FCo
- **中文提要：** 大语言模型通常从示范或经验中习得行为，但训练数据里大量是陈述性内容：只规定行为、却不展示如何执行的指令、规则和描述。Programming by Backprop（PBB）是一种训练机制，使模型能从这类陈述中获得可复用的程序性知识。
- **关键词：** fine-tuning

### Prompt Curriculum Learning for Efficient LLM Post-Training

- **作者：** Zhaolin Gao, Joongwon Kim, Wen Sun, Thorsten Joachims, Sid Wang, Richard Yuanzhe Pang, Liang Tan
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=zqOCacBD3P
- **中文提要：** 强化学习被广泛用于大语言模型的后训练，以应对数学推理和编程等任务，但其收敛对组批方式和提示选择策略仍然敏感。
- **关键词：** post-training

### Prompt-Robust Vision-Language Models via Meta-Finetuning

- **作者：** Haohui Liang, Runlin Huang, Yingjun Du, Yujia Hu, Weifeng Su, Cees G Snoek
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=3wZ6IIwPJq
- **中文提要：** 视觉语言模型借助大规模图文预训练，在多种任务上泛化较强，然而自然语言提示稍有变化，表现就明显不稳，给可靠的实际部署带来相当大的挑战。
- **关键词：** fine-tuning

### Property-Driven Protein Inverse Folding with Multi-Objective Preference Alignment

- **作者：** Junqi Liu, Xiaoyang Hou, Chence Shi, Xin Liu, Zhi Yang, Jian Tang
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=m826DekCpp
- **中文提要：** 蛋白质序列设计必须在可设计性（还原目标骨架的能力）与溶解性、热稳定性、表达量等往往相互竞争的可开发性质之间取得平衡。现有方法通过事后突变、推理时偏置或在特定性质子集上重训来处理这些性质，但它们依赖具体靶标，并且需要大量领域方面的投入。
- **关键词：** DPO, preference-optimization, alignment, fine-tuning

### PROS: Towards Compute-Efficient RLVR via Rollout Prefix Reuse

- **作者：** Baizhou Huang, Xiaojun Wan
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=lz1SRTcnUb
- **中文提要：** 用可验证奖励强化学习（RLVR）训练的大型推理模型在复杂推理任务上进展显著，然而 RLVR 高度依赖同策略 rollout 生成，其成本随 rollout 长度和模型规模迅速增长，最终成为训练瓶颈。
- **关键词：** RLVR

### Proximal Supervised Fine-Tuning

- **作者：** Wenhong Zhu, Ruobing Xie, Rui Wang, Samm Sun, Di Wang, Pengfei Liu
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=hQtwQqYikp
- **中文提要：** 基础模型做监督微调（SFT）后常常泛化变差，针对特定任务调完，原有能力随之下降。受强化学习中信任域策略优化（TRPO）和近端策略优化（PPO）启发，近端监督微调（PSFT）把信任域的好处写进微调目标，从而约束策略漂移。
- **关键词：** SFT, post-training, fine-tuning

### Pruning Long Chain-of-Thought of Large Reasoning Models via Small-Scale Preference Optimization

- **作者：** Bin Hong, Jiayu Liu, Kai Zhang, Jianwen Sun, Mengdi Zhang, Zhenya Huang
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=8xSU8Oscvg
- **中文提要：** 大型推理模型借助很长的思维链（CoT）在复杂任务上表现强劲，但冗长输出抬高计算成本，也可能导致过度思考，使推理效果与效率难以兼顾。
- **关键词：** preference-optimization

### PT$^2$-LLM: Post-Training Ternarization for Large Language Models

- **作者：** Xianglong Yan, ChengZhu Bao, Zhiteng Li, Tianao Zhang, Kaicheng Yang, Haotong Qin, Ruobing Xie, Samm Sun, Yulun Zhang
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=7QZanjCD6M
- **中文提要：** 大语言模型在多样任务上能力突出，但巨大的显存和计算需求妨碍部署。三值化作为一种有前景的压缩技术受到关注，能够大幅缩小体积并带来较高的计算效率。
- **关键词：** post-training, alignment

### Quagmires in SFT-RL Post-Training: When High SFT Scores Mislead and What to Use Instead

- **作者：** Feiyang Kang, Michael Kuchnik, Karthik Padthe, Marin Vlastelica, Ruoxi Jia, Carole-Jean Wu, Newsha Ardalani
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=uLM3BfKo19
- **中文提要：** 推理大语言模型的后训练实践通常分成两个独立阶段：监督微调（SFT），以及可验证奖励强化学习（文中把 RLVR 简称为 RL）。这项工作质疑较高的 SFT 分数是否会转化为强化学习之后更好的表现。
- **关键词：** GRPO, RLVR, SFT, post-training, fine-tuning

### Quantile Advantage Estimation: Stabilizing RLVR for LLM Reasoning

- **作者：** Junkang Wu, Kexin Huang, Jiancan Wu, An Zhang, Xiang Wang, Xiangnan He
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=WDP5b3mtFV
- **中文提要：** 可验证奖励强化学习（RLVR）能强化大语言模型的推理，但训练经常在熵坍缩和熵爆炸之间摇摆。两种隐患都被追溯到无价值函数强化学习（如 GRPO、DAPO）使用的均值基线：在奖励出现异常值时，它会不当地惩罚负优势样本。
- **关键词：** GRPO, RLVR

### QWHA: Quantization-Aware Walsh-Hadamard Adaptation for Parameter-Efficient Fine-Tuning on Large Language Models

- **作者：** Hyesung Jeon, Seojune Lee, Beomseok Kang, Yulhwa Kim, jae-joon kim
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=QMN4ERDdp4
- **中文提要：** 高效部署大语言模型的需求，同时推动了降低推理成本的量化，以及降低训练开销的参数高效微调（PEFT）。这进一步促成量化感知的 PEFT，以便得到既准确又高效的量化模型。
- **关键词：** LoRA, PEFT, fine-tuning

### R1-Reward: Training Multimodal Reward Model Through Stable Reinforcement Learning

- **作者：** YiFan Zhang, Xingyu Lu, Xiao Hu, Chaoyou Fu, Bin Wen, Tianke Zhang, Changyi Liu, Kaiyu Jiang, Kaibing Chen, Kaiyu Tang, Haojie Ding, Jiankang Chen, Fan Yang, Zhang Zhang, Tingting Gao, Di ZHANG, Guorui Zhou, Liang Wang
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=4Ewgw9M2xE
- **中文提要：** 多模态奖励模型对提升多模态大语言模型的表现至关重要。近期进展主要集中在改进其模型结构和训练数据，而对长期推理能力在奖励建模中是否有效、以及如何在奖励模型中激活这种能力，探讨仍然有限。
- **关键词：** reward-model

### R4: Nested Reasoning-Retrieval for Reward Modeling in Role-Playing Agents

- **作者：** Renzhi Wang, Chongqiang Wei, Zhisheng Wang, Piji Li
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=sWQSbVsPEz
- **中文提要：** 角色扮演对话给大语言模型带来特殊困难：除了生成连贯文本，还要维持角色人设、整合情境知识并传达情绪上的细微差别。尽管推理能力较强，现有模型写出的对话往往流于字面、风格平淡，并且与角色特有特质错位。
- **关键词：** reward-model

### Rainbow Padding: Mitigating Early Termination in Instruction-Tuned Diffusion LLMs

- **作者：** BumJun Kim, Dongjae Jeon, Dueun Kim, Wonje Jeung, Albert No
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=cznTlh7Msz
- **中文提要：** 扩散大语言模型作为自回归模型之外的一条路线，生成顺序更灵活，在复杂推理上表现也较强。经过指令微调的扩散语言模型却暴露出一种称为溢出的关键脆弱性：分配的序列越长，回答反而越短，坍缩为过早终止或进一步退化。
- **关键词：** instruction-tuning, LoRA, fine-tuning

### RAIN-Merging: A Gradient-Free Method to Enhance Instruction Following in Large Reasoning Models with Preserved Thinking Format

- **作者：** Zhehao Huang, Yuhang Liu, Baijiong Lin, Yixin Lou, Zhengbao He, Hanling Tian, Tao Li, Xiaolin Huang
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=PO2iULmu5e
- **中文提要：** 大型推理模型擅长长链推理，却常常不能忠实遵守关于输出格式、约束或具体要求的指令。作者考察这一差距能否通过把指令微调模型融入推理模型来弥补。
- **关键词：** instruction-tuning, instruction-following

### Rank-GRPO: Training LLM-based Conversational Recommender Systems with Reinforcement Learning

- **作者：** Yaochen Zhu, Harald Steck, Dawen Liang, Yinhan He, Vito Ostuni, Jundong Li, Nathan Kallus
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Xgw2D9cALS
- **中文提要：** 大语言模型正在重塑推荐系统，使用户可以通过对话表达偏好并获得推荐。把预训练模型对齐到推荐任务仍然困难：它们常生成目录之外的物品、违反要求的输出格式，而且生成列表越靠后，排序质量下降越明显。
- **关键词：** GRPO, alignment

### RECAST: Expanding the Boundaries of LLMs' Complex Instruction Following with Multi-Constraint Data

- **作者：** Zhengkang Guo, Wenhao Liu, Mingchen Xie, Jingwen Xu, Zisu Huang, Muzhao Tian, Jianhan Xu, Yuanzhe Shen, Qi Qian, Muling Wu, Xiaohua Wang, Heda Wang, Yao Hu, Changze Lv, Xuanjing Huang, Xiaoqing Zheng
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=90tCp2KszA
- **中文提要：** 随着应用面扩大、用户越来越善于编写复杂提示，大语言模型被期望处理更复杂的任务。当显式陈述的要求增多时，模型往往难以准确遵循这类复杂指令，从而限制其在复杂真实场景中的适用性。
- **关键词：** instruction-following, fine-tuning

### References Improve LLM Alignment in Non-Verifiable Domains

- **作者：** Kejian Shi, Yixin Liu, Peifeng Wang, Alexander Fabbri, Shafiq Joty, Arman Cohan
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=NoZgrya6Ua
- **中文提要：** 可验证奖励强化学习（RLVR）在推理任务上效果突出，却不能直接用于缺少真值验证器的不可验证领域，例如大语言模型对齐。作者考察高质量参考输出能否被有效用来弥合这一差距。
- **关键词：** RLVR, SFT, reward-model, post-training, alignment, fine-tuning

### Refining Hybrid Genetic Search for CVRP via Reinforcement Learning-Finetuned LLM

- **作者：** Rongjie Zhu, Cong Zhang, Zhiguang Cao
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=aITKXFeivk
- **中文提要：** 大语言模型越来越多地被用作车辆路径问题的自动启发式设计器，而当前领先方法主要依赖去提示 GPT-4 这类大规模通用模型。该工作挑战这一范式，指出经过细致微调的较小专用模型可以生成超越专家手工启发式的组件。
- **关键词：** fine-tuning

### Reinforcement Learning Fine-Tuning Enhances Activation Intensity and Diversity in the Internal Circuitry of LLMs

- **作者：** Honglin Zhang, Qianyue Hao, Fengli Xu, Yong Li
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=tzS9roOTdj
- **中文提要：** 大语言模型通过大规模预训练获得大量先验知识，并可以经由监督微调（SFT）或基于强化学习的后训练继续增强。越来越多的证据表明，强化学习微调带来的能力提升超出仅做 SFT 所能达到的水平。
- **关键词：** GRPO, DPO, RFT, SFT, preference-optimization, post-training, fine-tuning

### Reinforcement Mid-Training

- **作者：** Yijun Tian, Shaoyu Chen, Zhichao Xu, Yawei Wang, Jinhe Bi, Peng Han, Wei Wang
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=uJUhi3FQNa
- **中文提要：** 对顶尖大语言模型的常见理解是预训练与后训练两个阶段。作者指出还需要一个称为强化中间训练的额外中间阶段，并认为它有可能带来明显的性能增益。
- **关键词：** mid-training, post-training

### Reinforcement Unlearning via Group Relative Policy Optimization

- **作者：** Efstratios Zaradoukas, Bardh Prenkaj, Gjergji Kasneci
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=BjWwqPE7mk
- **中文提要：** 预训练时大语言模型会无意记住敏感或受版权保护的数据，在 GDPR 与欧盟人工智能法案等法律框架下构成严重的合规挑战。要满足这些要求，就需要能从已部署模型中移除信息、而不必从头重新训练的技术。
- **关键词：** GRPO, reward-model

### Reinforcing Diffusion Models by Direct Group Preference Optimization

- **作者：** Yihong Luo, Tianyang Hu, Jing Tang
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=jymuXl8GYi
- **中文提要：** GRPO 等强化学习方法显著增强了大语言模型，但把它们适配到扩散模型仍然困难。GRPO 要求策略是随机的，而成本效益最高的扩散采样器却基于确定性常微分方程。
- **关键词：** GRPO, preference-optimization

### RE-PO: Robust Enhanced Policy Optimization as a General Framework for LLM Alignment

- **作者：** Xiaoyang Cao, Zelai Xu, Mo Guang, Kaiwen Long, Michiel Bakker, Yu Wang, Chao Yu
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=jDKpOvTCM8
- **中文提要：** 以人类反馈强化学习（RLHF）为代表的标准偏好对齐方法，是让大语言模型贴近人类价值的基础技术。这些方法都依赖一个强假设：收集到的偏好数据是干净的，并且所有观测到的标签同样可靠。
- **关键词：** DPO, SimPO, RLHF, alignment

### Representation-Based Exploration for Language Models: From Test-Time to Post-Training

- **作者：** Jens Tuyls, Dylan Foster, Akshay Krishnamurthy, Jordan Ash
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=S4PCF1YxoR
- **中文提要：** 强化学习有望扩展语言模型的能力，但现有技术究竟促进新行为的发现，还是仅仅把基座模型里已经存在的行为磨得更尖锐，尚不明确。作者因此考察有意探索的价值，也就是明确激励模型去发现新颖且多样的行为。
- **关键词：** GRPO, post-training

### Rethinking Bottlenecks in Safety Fine-Tuning of Vision Language Models

- **作者：** Yi Ding, Lijun Li, Bing Cao, Jing Shao
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=HcubxPWpw7
- **中文提要：** 大型视觉语言模型已在广泛任务上取得突出表现，然而将其部署到安全关键领域仍面临显著挑战。
- **关键词：** instruction-following, fine-tuning

### Rethinking LoRA for Privacy-Preserving Federated Learning in Large Models

- **作者：** JIN LIU, Yinbin Miao, Ning Xi, Junkang Liu
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=BPzSV4uw0x
- **中文提要：** 在差分隐私联邦学习设定下微调大型视觉模型和大语言模型，受到隐私与效用之间根本权衡的阻碍。LoRA 作为一种参数高效微调（PEFT）方法，在冻结预训练权重的同时引入两个可训练低秩矩阵，从而降低计算和通信成本。
- **关键词：** LoRA, PEFT, fine-tuning

### Revisiting Group Relative Policy Optimization: Insights into On-Policy and Off-Policy Training

- **作者：** Youssef Mroueh, Nicolas Dupuis, Brian Belgodere, Apoorva Nitsure, Mattia Rigotti, Kristjan Greenewald, Jiri Navratil, Jarret Ross, Jesus Rios
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=XXfOf22o3K
- **中文提要：** 作者在同策略与离策略两种优化情形下重新审视组相对策略优化（GRPO）。动机来自近期关于离策略近端策略优化（PPO）的工作，该方法改善了训练稳定性、采样效率和显存占用。
- **关键词：** GRPO, post-training

### Revisiting Parameter Server in LLM Post-Training

- **作者：** Xinyi Wan, Penghui Qi, Guangxing Huang, Chaoyi Ruan, Min Lin, Jialin Li
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=iIEEgI6WsF
- **中文提要：** 现代数据并行训练在负载均衡时更偏好集合通信而非参数服务器，因为实现更简单、效率也更高。大语言模型后训练中序列长度方差很大，均衡负载这一假设不再成立。
- **关键词：** post-training

### RewardBench 2: Advancing Reward Model Evaluation

- **作者：** Saumya Malik, Valentina Pyatkin, Sander Land, Jacob Morrison, Noah Smith, Hanna Hajishirzi, Nathan Lambert
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=fb0G86Dewb
- **中文提要：** 奖励模型贯穿语言模型后训练，用来从偏好数据中捕捉细微信号，并为指令遵循、推理、安全等多个领域的优化提供训练目标。社区已开始建立评测奖励模型的实践，从检验特定技能领域能力的基准，到检验其他方面的基准。
- **关键词：** RLHF, instruction-following, reward-model, post-training, alignment

### Reward Model Routing in Alignment

- **作者：** Xinle Wu, Yao Lu
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=i3OKIHSsHC
- **中文提要：** 基于人类或人工智能反馈的强化学习（RLHF/RLAIF）已成为对齐大语言模型的标准范式。不过大多数流程只依赖单一奖励模型，从而限制对齐质量，并带来过拟合风险。
- **关键词：** RLHF, RLAIF, instruction-following, reward-model, alignment

### Reward Models Inherit Value Biases from Pretraining

- **作者：** Brian Christian, Jessica Thompson, Elle Michelle Yang, Vincent Adam, Hannah Kirk, Christopher Summerfield, Tsvetomira Dumbalska
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=dT399j1Azv
- **中文提要：** 奖励模型是把大语言模型对齐到人类价值的核心，但受到的关注少于预训练模型和后训练之后的模型本身。由于奖励模型从语言模型初始化，会继承塑造其行为的表征，而这种影响的性质与程度仍缺少研究。
- **关键词：** instruction-tuning, reward-model, post-training, alignment, fine-tuning

### RiskPO: Risk-based Policy Optimization with Verifiable Reward for LLM Post-Training

- **作者：** Tao Ren, Jinyang Jiang, Hui Yang, Wan Tian, Minhao Zou, Guanghao Li, Zishi Zhang, Qinghao Wang, Shentao Qin, Yanjun Zhao, Rui Tao, Hui Shao, Yijie Peng
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=KjHB7rebQO
- **中文提要：** 可验证奖励的强化学习近来成为大语言模型后训练的核心范式，但 GRPO 这类基于均值的方法会遭遇熵坍缩，推理上的增益也有限。作者认为这些问题源于过分强调高概率输出序列，同时忽视了罕见但有信息量的序列。
- **关键词：** GRPO, post-training

### RLBFF: Binary Flexible Feedback to bridge between Human Feedback & Verifiable Rewards

- **作者：** Zhilin Wang, Jiaqi Zeng, Olivier Delalleau, Ellie Evans, Daniel Egert, Hoo-Chang Shin, Felipe Soares, Yi Dong, Oleksii Kuchaiev
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=P3R3S6S5Km
- **中文提要：** 人类反馈强化学习（RLHF）与可验证奖励强化学习（RLVR）是大语言模型后训练中的两种主要强化学习范式，各自优势不同。RLHF 依赖通常缺少明确标准的人类判断，因而可解释性不足并容易出现奖励黑客；RLVR 则因为聚焦基于正确性的验证器而范围有限。
- **关键词：** RLHF, RLVR, reward-model, post-training, alignment

### RL makes MLLMs see better than SFT

- **作者：** Junha Song, Sangdoo Yun, Dongyoon Han, Jaegul Choo, Byeongho Heo
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=3gM6HwHvnc
- **中文提要：** 多模态语言模型研究中一个主导假设是：其表现很大程度上继承自参数规模巨大、能力突出的语言模型主干。这造成了对视觉编码器的理解空白，而视觉编码器决定多模态模型如何感知图像。
- **关键词：** SFT, post-training, fine-tuning

### RL Squeezes, SFT Expands: A Comparative Study of Reasoning LLMs

- **作者：** Kohsei Matsutani, Shota Takashiro, Gouki Minegishi, Takeshi Kojima, Yusuke Iwasawa, Yutaka Matsuo
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=N2lMNqJsBw
- **中文提要：** 为提升推理能力，大语言模型通常用带可验证奖励的强化学习（RLVR），以及在推理轨迹上做监督微调（SFT）来训练。这些方法究竟如何塑造推理能力，目前很大程度上仍不清楚。
- **关键词：** RLVR, SFT, fine-tuning

### RM-R1: Reward Modeling as Reasoning

- **作者：** Xiusi Chen, Gaotang Li, Ziqi Wang, Bowen Jin, Cheng Qian, Yu Wang, Hongru WANG, Yu Zhang, Denghui Zhang, Tong Zhang, Hanghang Tong, Heng Ji
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=1ZqJ6jj75q
- **中文提要：** 奖励建模是借助强化学习把大语言模型对齐到人类偏好所必需的一环。要提供准确的奖励信号，奖励模型应在给出分数或判断之前激发深入思考，并进行可解释的推理。
- **关键词：** reward-model, alignment

### Robust and Interpretable Adaptation of Equivariant Materials Foundation Models via Sparsity-promoting Fine-tuning

- **作者：** Youngwoo Cho, Seunghoon Yi, Wooil Yang, Sungmo Kang, Young-Woo Son, Jaegul Choo, Joonseok Lee, Soo Kyung Kim, Hongkee Yoon
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=moBqB1CUym
- **中文提要：** 预训练的材料基础模型，也就是机器学习原子间势，借助一般的物理化学知识来近似势能面。由于物理化学上的多样性，以及实际计算设定与构建预训练数据时所用设定不一致，它们往往仍需要针对具体领域做校准。
- **关键词：** LoRA, fine-tuning

### Robust Preference Alignment via Directional Neighborhood Consensus

- **作者：** Ruochen Mao, Yuling Shi, Xiaodong Gu, Jiaheng Wei
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=jz41Oh9eV1
- **中文提要：** 让大语言模型对齐人类偏好，对构建可靠、可控的人工智能系统至关重要。一种人类偏好可以看成高维向量，不同方向代表期望属性之间的权衡，例如有用性与另一属性之间的取舍。
- **关键词：** DPO, SFT, preference-optimization, alignment

### Robust Reward Modeling via Causal Rubrics

- **作者：** Pragya Srivastava, Harman Singh, Rahul Madhavan, Gandharv Patil, Sravanti Addepalli, Arun Suggala, Rengarajan Aravamudhan, Soumya Sharma, Anirban Laha, Aravindan Raghuveer, Karthikeyan Shanmugam, Doina Precup
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=oP99JQiDYp
- **中文提要：** 奖励模型是经由人类反馈对齐大语言模型的基础，却常常遭受奖励黑客。它们倾向于抓住回答长度或格式等表面或虚假的属性，把从训练数据相关性里学到的线索误当成质量的真正因果驱动因素，例如事实性和相关性。
- **关键词：** DPO, reward-model, alignment

### SafeDPO: A Simple Approach to Direct Preference Optimization with Enhanced Safety

- **作者：** Geon-Hyeong Kim, Yu Jin Kim, Byoungjip Kim, Honglak Lee, Kyunghoon Bae, Youngsoo Jang, Moontae Lee
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=PJdw4VBsXD
- **中文提要：** 随着大语言模型越来越多地部署到真实应用，平衡有用性与安全性成为核心挑战。一种自然思路是把安全约束纳入人类反馈强化学习（RLHF），近期研究已显示出有希望的进展。
- **关键词：** DPO, RLHF, preference-optimization, reward-model, alignment

### SafeMoE: Safe Fine-Tuning for MoE LLMs by Aligning Harmful Input Routing

- **作者：** Jaehan Kim, Minkyoo Song, Seungwon Shin, Sooel Son
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=W1x9AzkSnU
- **中文提要：** 近期大语言模型越来越多采用混合专家（MoE）架构以追求效率。基于 MoE 的模型严重依赖一种表层安全机制，即把有害输入路由到对安全至关重要的专家。
- **关键词：** alignment, fine-tuning

### Safety at One Shot: Patching Fine-Tuned LLMs with A Single Instance

- **作者：** Jiawen Zhang, Lipeng He, Kejia Chen, Jian Lou, Jian Liu, Xiaohu Yang, Ruoxi Jia
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=EyH8Fu3vtZ
- **中文提要：** 对已经安全对齐的大语言模型再做微调，可能大幅削弱其安全性。以往方法需要许多安全样本或校准集，重新对齐时计算开销显著，也会明显损害模型效用。
- **关键词：** alignment, fine-tuning

### Safety Mirage: How Spurious Correlations Undermine VLM Safety Fine-Tuning and Can Be Mitigated by Machine Unlearning

- **作者：** Yiwei Chen, Yuguang Yao, Yihua Zhang, Bingquan Shen, Gaowen Liu, Sijia Liu
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Qi1rZa4zzl
- **中文提要：** 近期视觉语言模型在以文本和图像为主的多模态生成上进步显著，但面对不安全查询时仍可能生成有害内容，从而引发关键的安全担忧。
- **关键词：** SFT, alignment, fine-tuning

### Safety Subspaces are Not Linearly Distinct: A Fine-Tuning Case Study

- **作者：** Kaustubh Ponkshe, Shaan Shah, Raghav Singhal, Praneeth Vepakomma
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Fj6LakRHcT
- **中文提要：** 大语言模型依靠安全对齐来产生社会可接受的回答，但这种行为已知很脆弱。即便在良性或只受轻微污染的数据上继续微调，也可能削弱安全性并重新引入有害行为。
- **关键词：** alignment, fine-tuning

### SAIL: Self-Amplified Iterative Learning for Diffusion Model Alignment with Minimal Human Feedback

- **作者：** Xiaoxuan He, Siming Fu, Wanli Li, Zhiyuan Li, Dacheng Yin, Kang Rong, Fengyun Rao, Bo Zhang
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=wKdg1DDOrW
- **中文提要：** 把扩散模型对齐到人类偏好仍然困难，尤其当奖励模型无法获得或不切实际，而收集大规模偏好数据又过于昂贵。由此提出一个基本问题：能否不借助辅助奖励模型、只用极少的人类反馈，通过释放扩散模型内部的潜在能力来实现有效对齐。
- **关键词：** reward-model, alignment

### SARM: Stage-Aware Reward Modeling for Long Horizon Robot Manipulation

- **作者：** Qianzhong Chen, Justin Yu, Mac Schwager, Pieter Abbeel, Fred Shentu, Philipp Wu
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=aemqAxScl9
- **中文提要：** 大规模机器人学习在复杂操作任务上已有进展，但长时程、接触丰富的问题，尤其涉及可变形物体时，仍因示范质量不一致而困难。作者提出一种感知阶段、基于视频的奖励建模框架，联合预测任务阶段和细粒度进度，并利用自然语言子任务标注来导出一致的标签。
- **关键词：** reward-model

### SASFT: Sparse Autoencoder-guided Supervised Finetuning to Mitigate Unexpected Code-Switching in LLMs

- **作者：** Boyi Deng, Yu Wan, Baosong Yang, Fei Huang, Wenjie Wang, Fuli Feng
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=BQOFU9qO5j
- **中文提要：** 大语言模型的多语言能力很强，但会意外发生语码转换，也称语言混杂，即在回答中切换到不该出现的语言。这一问题降低可读性，并损害模型回答的可用性。
- **关键词：** SFT, fine-tuning

### Scaf-GRPO: Scaffolded Group Relative Policy Optimization for Enhancing LLM Reasoning

- **作者：** Xichen Zhang, Sitong Wu, Yinghao Zhu, Haoru Tan, Shaozuo Yu, Ziyi He, Jiaya Jia
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=bOwVr0yr7r
- **中文提要：** 来自可验证奖励的强化学习已成为增强大语言模型复杂推理能力的有力技术。这些方法根本上受“学习悬崖”现象约束：面对远超当前能力的问题时，模型持续失败，从而一直得到零奖励信号。
- **关键词：** GRPO

### Scaling Agents via Continual Pre-training

- **作者：** Liangcai Su, Zhen Zhang, Guangyu Li, Zhuo Chen, Chenxi Wang, Maojia Song, Xinyu Wang, Kuan Li, Jialong Wu, Xuanzhong Chen, Zile Qiao, Zhongwang Zhang, Huifeng Yin, Shihao Cai, Runnan Fang, Zhengwei Tao, Wenbiao Yin, Rui Ye, Yong Jiang, Ningyu Zhang, Pengjun Xie, Fei Huang, Kai Ye, Kewei Tu, Chenxiong Qian, Jingren Zhou
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Dru5mm9anE
- **中文提要：** 大语言模型已演变成能够自主使用工具、进行多步推理以解决复杂问题的智能体系统。然而，建立在通用基础模型之上的后训练路线，在智能体任务上持续表现不足，开源实现中尤其如此。
- **关键词：** continued-pretraining, post-training, alignment

### Sci2Pol: Evaluating and Fine-tuning LLMs on Scientific-to-Policy Brief Generation

- **作者：** Weimin Wu, Alexander Furnas, Eddie Yang, Gefei Liu, Akhil Pandey Akella, Xuefeng Song, Dashun Wang, Han Liu
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=S6gJESWNSX
- **中文提要：** 作者提出 Sci2Pol-Bench 与 Sci2Pol-Corpus，用于评测并微调大语言模型从科学论文生成政策简报。Sci2Pol-Bench 依照五阶段分类来对照人类写作过程，依次为自动补全、理解、摘要、生成和校验。
- **关键词：** fine-tuning

### Sculpting Subspaces: Constrained Full Fine-Tuning in LLMs for Continual Learning

- **作者：** Nikhil Shivakumar Nayak, Krishnateja Killamsetty, Ligong Han, Abhishek Bhandwaldar, Prateek Chanda, Kai Xu, Oleg Silkin, Mustafa Eyceoz, Hao Wang, Aldo Pareja, Akash Srivastava
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=vQcyqsGJDw
- **中文提要：** 大语言模型的持续学习容易出现灾难性遗忘，适应新任务会显著降低先前已学任务上的表现。现有参数高效方法常常限制模型的表达能力，或为每个任务引入新参数，从而造成可扩展性问题。
- **关键词：** instruction-following, LoRA, PEFT, fine-tuning

### SeedVR2: One-Step Video Restoration via Diffusion Adversarial Post-Training

- **作者：** Jianyi Wang, Shanchuan Lin, Zhijie Lin, Yuxi Ren, Meng Wei, Zongsheng Yue, Shangchen Zhou, Hao Chen, Yang Zhao, Ceyuan Yang, Xuefeng Xiao, Chen Change Loy, Lu Jiang
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=x1FRyko9eC
- **中文提要：** 基于扩散的视频修复在视觉质量上有明显提升，但推理阶段的计算成本过高。若干基于蒸馏的方法已显示出一步图像修复的潜力，不过把现有做法扩展到视频修复仍然困难且探索不足，尤其是面对真实场景中的高分辨率视频时。
- **关键词：** post-training

### Semantic-aware Wasserstein Policy Regularization for Large Language Model Alignment

- **作者：** Byeonghu Na, Hyungho Na, Yeongmin Kim, Suhyeon Jo, HeeSun Bae, Mina Kang, Il-chul Moon
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=sUac3QDbAs
- **中文提要：** 大语言模型通常借助人类反馈强化学习（RLHF）来对齐人类偏好。在这一方法中，策略一般通过最大化奖励来优化，并用相对于参考策略的 KL 散度加以正则。
- **关键词：** RLHF, alignment

### Semi-Supervised Preference Optimization with Limited Feedback

- **作者：** Seonggyun Lee, Sungjun Lim, Seojin Park, Soeun Cheon, Kyungwoo Song
- **会议：** ICLR 2026 · Main · Oral
- **官方论文页：** https://openreview.net/forum?id=2026-Oral--710-b9dc3169
- **中文提要：** 偏好优化对让语言模型对齐人类偏好作出了突出贡献。尽管如此，近期方法仍然严重依赖大量成对的已标注反馈数据，因而资源消耗很大。
- **关键词：** preference-optimization, alignment

### SFT Doesn’t Always Hurt General Capabilities: Revisiting Domain-Specific Fine-Tuning in LLMs

- **作者：** Jiacheng Lin, Zhongruo Wang, Kun Qian, Tian Wang, Arvind Srinivasan, Hansi Zeng, Ruochen Jiao, Xie Zhou, Jiri Gesi, Dakuo Wang, Yufan Guo, Kai Zhong, Weiqi Zhang, sujay sanghavi, Changyou Chen, Hyokun Yun, Lihong Li
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ru93xpQFi1
- **中文提要：** 在领域专用数据上做监督微调（SFT）是让大语言模型适应专门任务的常见途径，但人们常常认为这会损害其通用能力。该工作重新审视这一权衡，并给出经验与理论上的观察。
- **关键词：** SFT, LoRA, fine-tuning

### Sharpness-Aware Minimization in Logit Space Efficiently Enhances Direct Preference Optimization

- **作者：** Haocheng Luo, Zehang Deng, Thanh-Toan Do, Mehrtash Harandi, Dinh Phung, Trung Le
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=4mE2FlL66E
- **中文提要：** 直接偏好优化（DPO）因简单且训练稳定，成为把预训练大语言模型对齐到人类偏好的常用算法。不过 DPO 存在近来发现的挤压效应，也称似然位移：训练过程中，偏好回答的概率会意外下降。
- **关键词：** DPO, preference-optimization, alignment

### SHE-LoRA: Selective Homomorphic Encryption for Federated Tuning with Heterogeneous LoRA

- **作者：** Jianmin Liu, Li Yan, Borui Li, Lei Yu, Chao Shen
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=PWChrnrw7Z
- **中文提要：** 联邦微调希望在训练数据分散、保持私有的前提下，提升大语言模型处理领域任务的能力。已有研究表明，客户端的私有数据仍可能经由梯度反演攻击被还原。
- **关键词：** LoRA, fine-tuning

### SoLoPO: Unlocking Long-Context Capabilities in LLMs via Short-to-Long Preference Optimization

- **作者：** Huashan Sun, Shengyi Liao, Yansen Han, Yu Bai, Yang Gao, Cheng Fu, Weizhou Shen, Fanqi Wan, Ming Yan, Ji Zhang, Fei Huang
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=iiBjaiikJG
- **中文提要：** 即便预训练上下文已经加长，大语言模型仍难有效利用真实场景中的长上下文，主因是长上下文对齐不足，背后涉及数据质量、训练效率以及缺少合适的优化目标。作者提出一个框架来应对这些限制。
- **关键词：** preference-optimization, alignment

### Sparse but Critical: A Token-Level Analysis of Distributional Shifts in RLVR Fine-Tuning of LLMs

- **作者：** Haoming Meng, Kexin Huang, Shaohang Wei, Chiyu Ma, Shuo Yang, xue wang, Guoyin Wang, Bolin Ding, Jingren Zhou
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=8vWIXno8LW
- **中文提要：** 可验证奖励强化学习（RLVR）显著提升了大语言模型的推理，词元层面的作用机制却仍不清楚。这项实证研究先刻画基座模型与强化学习模型之间的词元级分布偏移，并继续考察其他影响。
- **关键词：** RLVR, RFT, fine-tuning

### Spectrum Tuning: Post-Training for Distributional Coverage and In-Context Steerability

- **作者：** Taylor Sorensen, Benjamin Newman, Jared Moore, Chan Young Park, Jillian Fisher, Niloofar Mireshghallah, Liwei Jiang, Yejin Choi
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ulvp7cbZeU
- **中文提要：** 语言模型后训练加强了指令遵循和多项下游表现，却常忽略存在大量合法答案的任务。创意写作、合成数据生成或面向多样偏好的引导，都要求模型覆盖一整段输出分布，而不是只给出单一正确答案。
- **关键词：** instruction-tuning, instruction-following, post-training, alignment

### SRFT: A Single-Stage Method with Supervised and Reinforcement Fine-Tuning for Reasoning

- **作者：** Yuqian Fu, Tinghong Chen, Jiajun Chai, Xihuai Wang, Songjun Tu, Guojun Yin, Wei Lin, Qichao Zhang, Yuanheng Zhu, Dongbin Zhao
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=n6E0r6kQWQ
- **中文提要：** 推理任务上如何把监督微调（SFT）与强化学习恰当地结合起来，仍是基本难题。作者从熵的角度分析词元分布、学习动态与整合机制，指出两种范式存在关键差异，其中 SFT 引起的是粗粒度变化。
- **关键词：** RFT, SFT, fine-tuning

### ssToken: Self-modulated and Semantic-aware Token Selection for LLM Fine-tuning

- **作者：** Xiaohan Qin, Victor Wang, Ning Liao, Cancheng Zhang, Xiangdong Zhang, Mingquan Feng, Jingzhi Wang, Junchi Yan
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=wZ4UoRKDNa
- **中文提要：** 数据质量对提升大语言模型的监督微调至关重要，词元级数据选择因粒度更细而受到关注。现有词元选择方法虽经验上有效，却普遍需要训练或调用额外参考模型，并且只依据损失做判断，第二点在摘要中未写完。
- **关键词：** SFT, fine-tuning

### Stable-LoRA: Stabilizing Feature Learning of Low-Rank Adaptation

- **作者：** Yize Wu, KE GAO, Ling Li, Yanjun WU
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=xSa19DAieH
- **中文提要：** LoRA 是广泛使用的参数高效微调方法，它把权重更新写成冻结原权重加上缩放后的两个可训练低秩矩阵。摘要只交代了这一参数化形式。
- **关键词：** LoRA, PEFT, fine-tuning

### Stackelberg Learning from Human Feedback: Preference Optimization as a Sequential Game

- **作者：** Barna Pásztor, Thomas Kleine Buening, Andreas Krause
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=vc9Tj11LNE
- **中文提要：** SLHF 把偏好优化表述为序贯行动博弈：领导者先承诺一个动作，跟随者再根据该动作作出条件响应。对齐因此发生在两套策略的先后互动之中。
- **关键词：** RLHF, preference-optimization, alignment, fine-tuning

### StepORLM: A Self-Evolving Framework With Generative Process Supervision For Operations Research Language Models

- **作者：** Chenyu Zhou, Tianyi Xu, Jianghao Lin, Dongdong Ge
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ZrgxU8WMmG
- **中文提要：** 大语言模型在求解运筹问题上已显示出潜力，强化学习也被用来在这类问题上训练模型。现有工作普遍面临两项关键限制，摘要没有写明具体是哪两项。
- **关键词：** DPO, preference-optimization, PRM, reward-model

### StoryAlign: Evaluating and Training Reward Models for Story Generation

- **作者：** Haotian Xia, Hao Peng, Yunjia Qi, Xu Bin, Lei Hou, Juanzi Li
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=a3JmkJtTDV
- **中文提要：** 故事生成希望自动写出连贯、有结构且吸引人的叙事。大语言模型虽明显推进了文本生成，其故事在复杂叙事结构和与人类偏好的契合上仍与人类作品有差距。
- **关键词：** reward-model

### Supervised Fine-Tuning or Contrastive Learning? Towards Better Multimodal LLM Reranking

- **作者：** Xin Zhang, Ziqi Dai, Mingxin Li, yanzhao zhang, Dingkun Long, Pengjun Xie, Meishan Zhang, Wenjie Li, Min Zhang
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=1Mh2q7L0eY
- **中文提要：** 信息检索中的重排序训练主要围绕两类目标：度量学习，例如用对比损失抬高相关查询—文档对的预测分数，以及把相关与不相关当作二分类。
- **关键词：** SFT, fine-tuning

### Swap-guided Preference Learning for Personalized Reinforcement Learning from Human Feedback

- **作者：** Gihoon Kim, Euntai Kim
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=nc28mSbyVG
- **中文提要：** RLHF 常被用来把大规模人工智能系统对齐到人类价值，但通常假定存在单一、通用的奖励。这种假设忽略了偏好差异，也限制了个性化。
- **关键词：** RLHF, reward-model

### TangoFlux: Super Fast and Faithful Text to Audio Generation with Flow Matching and Clap-Ranked Preference Optimization

- **作者：** Chia-Yu Hung, Navonil Majumder, Zhifeng Kong, Ambuj Mehrish, Amir Zadeh, Chuan Li, Rafael Valle, Bryan Catanzaro, Soujanya Poria
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=qgNs5NmQB7
- **中文提要：** TangoFlux 是一种高效的文本到音频生成模型。对齐这类模型的难点在于构造偏好对，因为文本转音频缺少大语言模型所具备的可验证奖励或标准答案一类结构化机制。
- **关键词：** preference-optimization, alignment

### Task-Adaptive Parameter-Efficient Fine-Tuning for Weather Foundation Models

- **作者：** Shilei Cao, Hehai Lin, Jiashun Cheng, Yang Liu, Guowen Li, Xuehe Wang, Juepeng Zheng, Haoyuan Liang, Meng Jin, Chengwei Qin, Hong Cheng, Haohuan Fu
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=eFExhM3tKr
- **中文提要：** 天气基础模型在多种下游任务上已有较强泛化，但规模扩大带来的计算需求越来越妨碍实际部署。面向视觉或语言设计的现有 PEFT 方法应对不了天气模型的独特要求。
- **关键词：** PEFT, fine-tuning

### Task-Aware Data Selection via Proxy-Label Enhanced Distribution Matching for LLM Finetuning

- **作者：** Hao Cheng, Rui Zhang, Ling Li, Na Di, Jiaheng Wei, Zhaowei Zhu, Bo Han
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=R40WoYbYab
- **中文提要：** 基础模型的任务微调高度依赖指令数据的质量与相关性。主流数据选择往往只用指令实例去逼近目标分布，作者则主张选择应贴近指令与任务标签的联合分布。
- **关键词：** alignment, fine-tuning

### TEMPFLOW-GRPO: WHEN TIMING MATTERS FOR GRPO IN FLOW MODELS

- **作者：** Xiaoxuan He, Siming Fu, Yuke Zhao, Wanli Li, Jian Yang, Dacheng Yin, Fengyun Rao, Bo Zhang
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=7mCo3R3Wyn
- **中文提要：** 流匹配文生图模型质量已经很高，但与强化学习结合以对齐人类偏好的效果仍不理想，细粒度的奖励优化因此受阻。作者认为关键障碍是现有做法的时间均匀性假设：把稀疏的终局奖励均匀分配。
- **关键词：** GRPO, preference-optimization, PRM, reward-model, alignment

### Test-Time Alignment for Large Language Models via Textual Model Predictive Control

- **作者：** Kuang-Da Wang, Teng-Ruei Chen, Yu Heng Hung, Guo-Xun Ko, Shuoyang Ding, Yueh-Hua Wu, Yu-Chiang Frank Wang, Chao-Han Huck Yang, Wen-Chih Peng, Ping-Chun Hsieh
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=DsS3xRPSs5
- **中文提要：** 靠微调把大语言模型对齐到人类偏好很耗资源，因而需要更轻量的测试时方案。作者把测试时对齐看成序贯决策，并由此指出两项基本挑战，摘要没有展开具体内容。
- **关键词：** alignment, fine-tuning

### The Coverage Principle: How Pre-Training Enables Post-Training

- **作者：** Fan Chen, Audrey Huang, Noah Golowich, Sadhika Malladi, Adam Block, Jordan Ash, Akshay Krishnamurthy, Dylan Foster
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=AUXvYQlQLZ
- **中文提要：** 语言模型在大规模文本上预训练后再针对任务微调，能力很强，但预训练如何以及为何决定最终模型的成败仍不清楚。交叉熵常被用来衡量预训练是否成功，却未必能很好地预测下游表现。
- **关键词：** post-training, fine-tuning

### Thompson Sampling via Fine-Tuning of LLMs

- **作者：** Nicolas Menet, Aleksandar Terzic, Michael Hersche, Andreas Krause, Abbas Rahimi
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=u6fc354gfS
- **中文提要：** 在缺少梯度的大规模非结构化离散空间里，贝叶斯优化常因最大化采集函数而计算昂贵。作者基于汤普森采样，直接参数化某个候选取得最大奖励的概率，从而不必再最大化采集函数。
- **关键词：** fine-tuning

### Three Forward, One Backward: Memory-Efficient Full-Rank Fine-Tuning of Large Models via Extra Forward Passes

- **作者：** Jia Zhang, Yu Bai, Hualin Zhang, Tianshuo Chen, Zhaogeng Liu, Zhiqiang Xu, Yi Chang, Bin Gu
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=373rsDQsq4
- **中文提要：** 大语言模型微调在下游任务上已经取得明显成效。随着模型继续变大，传统微调的计算和显存开销使其越来越难以实用。
- **关键词：** LoRA, PEFT, fine-tuning

### Tina: Tiny Reasoning Models via LoRA

- **作者：** Shangshang Wang, Julian Asilis, Ömer Faruk Akgül, Enes Bilgin, Ollie Liu, Willie Neiswanger
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=P2OXYO3bEe
- **中文提要：** 围绕如何以可接受的成本获得强推理能力，作者提出 Tina，一组高性价比的小型推理模型。摘要只交代了这一动机与定位。
- **关键词：** LoRA

### TiTok: Transfer Token-level Knowledge via Contrastive Excess to Transplant LoRA

- **作者：** ChanJoo Jung, Jaehyung Kim
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=0B5K9pIdSK
- **中文提要：** 微调大语言模型的计算和存储成本很高，LoRA 等 PEFT 方法能减轻这些开销。适配得到的参数却依赖基座模型，无法迁移到不同骨干网络。
- **关键词：** LoRA, PEFT, fine-tuning

### Token-Importance Guided Direct Preference Optimization

- **作者：** Ning Yang, Hai Lin, Yibo Liu, Baoliang Tian, Guoqing Liu, Haijun Zhang
- **会议：** ICLR 2026 · Main · Oral
- **官方论文页：** https://openreview.net/forum?id=2026-Oral--6576-29f99a63
- **中文提要：** 把大语言模型对齐到人类偏好，对安全有效的交互很关键。DPO 简化了对齐流程，却仍然对数据噪声敏感，也忽视了不同词元之间的重要性差异。
- **关键词：** DPO, RLHF, preference-optimization, alignment

### Token-level Data Selection for Safe LLM Fine-tuning

- **作者：** Yanping Li, Zhening Liu, Zijian Li, Zehong Lin, Jun Zhang
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=k7ytptAaDN
- **中文提要：** 在自定义数据上微调，已成为让大语言模型适应特定领域与应用的常规做法。近期研究表明，这种微调也可能明显削弱模型的安全性。
- **关键词：** fine-tuning

### Towards Understanding Valuable Preference Data for Large Language Model Alignment

- **作者：** Zizhuo Zhang, Qizhou Wang, Shanshan Ye, Jianing ZHU, Jiangchao Yao, Bo Han, Masashi Sugiyama
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=FUp0KeEEBs
- **中文提要：** 大语言模型对齐通常靠学习人类偏好比较来完成，偏好数据的质量因此至关重要。已有工作常用外部奖励模型或现成大模型从原始数据中挑选有价值的偏好对，整体表现有所提升，却很少检查被选中的单条数据本身。
- **关键词：** reward-model, alignment

### TRAC: Tensor-Train based Across-layer Compression for Parameter-Efficient Fine-Tuning

- **作者：** Bangguo Ye, Yuanwei Zhang, Xiaoqun Zhang
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=tz5yPWZp9W
- **中文提要：** 在资源受限时微调大型预训练模型仍然困难，因为涉及的参数量巨大。LoRA 及其变体主要依赖矩阵分解，在极低参数预算下往往难以奏效。
- **关键词：** LoRA, PEFT, fine-tuning

### TreeGRPO: Tree-Advantage GRPO for Online RL Post-Training of Diffusion Models

- **作者：** Zheng Ding, Weirui Ye
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=3rZdp4TmUb
- **中文提要：** 强化学习后训练对把生成模型对齐到人类偏好很重要，但高昂的计算成本阻碍了推广。TreeGRPO 把去噪过程改写成搜索树，以此提高训练效率。
- **关键词：** GRPO, reward-model, post-training, alignment

### TS$^2$: Training with Sparsemax+, Testing with Softmax for Accurate and Diverse LLM Fine-Tuning

- **作者：** Ziyang Xu, Ananthu Rajendran Pillai, Yinghua Yao, Yuangang Pan
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=CylRqa82Rk
- **中文提要：** 大语言模型做下游特化时，监督微调通常使用交叉熵损失。交叉熵把分布推向独热目标并忽略其他可能续写，从而限制输出多样性，这对依赖采样探索的生成应用是明显短板。
- **关键词：** SFT, fine-tuning

### Uni-DPO: A Unified Paradigm for Dynamic Preference Optimization of LLMs

- **作者：** Shangpin Peng, Weinong Wang, Zhuotao Tian, Senqiao Yang, Xing W, Haotian Xu, Chengquan Zhang, Takashi Isobe, Baotian Hu, Min Zhang
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=G7DBGlgjjp
- **中文提要：** DPO 因简单高效而成为 RLHF 的核心方法之一。现有基于 DPO 的做法通常平等对待所有偏好对，忽略数据质量与学习难度的明显差异，导致数据利用不充分、表现也不理想。
- **关键词：** DPO, RLHF, preference-optimization, fine-tuning

### Unifying Stable Optimization and Reference Regularization in RLHF

- **作者：** Li He, Qiang Qu, He Zhao, Stephen Wan, Dadong Wang, Lina Yao, Tongliang Liu
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=QpqBqCTtW4
- **中文提要：** RLHF 明显推进了对齐能力，但仍受奖励黑客和优化稳定性两个核心问题制约。现有方案分别用正则应对：以相对监督微调模型的 KL 惩罚抑制奖励黑客，另一项则涉及策略比率。
- **关键词：** RLHF, SFT, alignment, fine-tuning

### VideoMind: A Chain-of-LoRA Agent for Temporal-Grounded Video Reasoning

- **作者：** Ye Liu, Kevin Qinghong Lin, Chang-Wen Chen, Mike Zheng Shou
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=57EwidOnSf
- **中文提要：** 视频多了时间维度，回答需要精确落到可解释的视觉证据上。文本推理已有显著进展，多模态推理尤其是视频推理仍然有限。
- **关键词：** LoRA

### ViPO: Visual Preference Optimization at Scale

- **作者：** Ming Li, Jie Wu, Jiaxing Cui, Xiaojie Li, Rui Wang, Chen Chen
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=x5zP3k64Nl
- **中文提要：** 偏好优化对改进视觉生成模型很重要，但如何把这一范式有效扩展到视觉生成仍少有探讨。现有开源偏好数据里常有相互冲突的偏好模式：胜出样本在某些维度更好，在另一些维度却更差。
- **关键词：** DPO, preference-optimization

### Vision-Language-Action Instruction Tuning: From Understanding to Manipulation

- **作者：** Shuai Yang, Hao Li, Bin Wang, Yilun Chen, Yang Tian, Tai Wang, Hanqing Wang, Feng Zhao, Yiyi Liao, Jiangmiao Pang
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=tsxwloasw5
- **中文提要：** 机器人要在真实环境中有效工作，需要把多模态推理和精确的动作生成结合起来。现有视觉—语言—动作模型常常顾此失彼，能力被收窄到特定操作数据上，还会灾难性遗忘预训练的视觉语言能力。
- **关键词：** instruction-tuning, fine-tuning

### Vision-SR1: Self-Rewarding Vision-Language Model via Reasoning Decomposition and Multi-Reward Policy Optimization

- **作者：** Zongxia Li, Wenhao Yu, Chengsong Huang, Zhenwen Liang, Rui Liu, Fuxiao Liu, Jingxi Chen, Dian Yu, Jordan Boyd-Graber, Haitao Mi, Dong Yu
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=C1M4ETatgM
- **中文提要：** 视觉语言模型常出现与画面不一致的幻觉，或跳过视觉、只靠文本先验走捷径。多数后训练只用简单的可验证答案匹配并只监督最终输出，中间的视觉推理缺少显式约束。
- **关键词：** reward-model, post-training, self-rewarding

### Visual Jigsaw Post-Training Improves MLLMs

- **作者：** Penghao Wu, Yushan Zhang, Haiwen Diao, Bo Li, Lewei Lu, Ziwei Liu
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=tBf2SUzfZw
- **中文提要：** 基于强化学习的后训练已成为增强多模态大语言模型对齐与推理的重要途径。以视觉为中心的后训练对模型真正理解视觉信号很关键，但现有范式主要仍以文本为中心，稠密视觉输入只被用来服务于摘要里未写完的目的。
- **关键词：** RLVR, post-training, alignment

### VisualPRM400K: An Effective Dataset for Training Multimodal Process Reward Models

- **作者：** Weiyun Wang, Zhangwei Gao, Lianjie Chen, Zhe Chen, Jinguo Zhu, Xiangyu Zhao, Yangzhou Liu, Yue Cao, Shenglong Ye, Xizhou Zhu, Lewei Lu, Haodong Duan, Yu Qiao, Jifeng Dai, Wenhai Wang
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=IHyY6vdYZw
- **中文提要：** 作者构建多模态过程监督数据集 VisualPRM400K，并在此基础上训练过程奖励模型 VisualPRM。该模型可以估计推理过程中每一步的价值分数。
- **关键词：** PRM, reward-model

### Watch the Weights: Unsupervised monitoring and control of fine-tuned LLMs

- **作者：** Ziqian Zhong, Aditi Raghunathan
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=WZYxJhvAvD
- **中文提要：** 强开放权重大语言模型发布时，往往并不附带完整训练数据。基于激活的现有可解释方法通常需要或假定分布相近的数据。
- **关键词：** instruction-tuning, fine-tuning

### Watch your steps: Dormant Adversarial Behaviors that Activate upon LLM Finetuning

- **作者：** Thibaud Gloaguen, Mark Vero, Robin Staab, Martin Vechev
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=yfM2e8Icsw
- **中文提要：** 微调开放权重大语言模型，是取得特定任务性能提升的常规做法。此前微调被视为可控且安全的过程，在良性数据上训练应带来可预期的行为。
- **关键词：** DPO, instruction-tuning, post-training, fine-tuning

### WebArbiter: A Generative Reasoning Process Reward Model for Web Agents

- **作者：** Yao Zhang, Shijie Tang, Zeyu Li, Zhen Han, Volker Tresp
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=canA6Ef0RP
- **中文提要：** 网页智能体有望自动化复杂的计算机任务，但其交互是长时程、带不可逆动作的序贯决策。这种设定下基于结果的监督稀疏且滞后，常会奖励错误轨迹，也难以支持推理时的扩展。
- **关键词：** PRM, reward-model, alignment

### What's In My Human Feedback? Learning Interpretable Descriptions of Preference Data

- **作者：** Rajiv Movva, Smitha Milli, Sewon Min, Emma Pierson
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=sC6A1bFDUt
- **中文提要：** 人类反馈会以难以预料、也不尽理想的方式改变语言模型，因为实践者并不清楚反馈数据编码了什么。已有研究考察长度或谄媚等预先指定的属性偏好，但在不事先给定假设时自动抽出相关特征仍然困难。
- **关键词：** RLHF, alignment

### When Data is the Algorithm: A Systematic Study and Curation of Preference Optimization Datasets

- **作者：** Aladin Djuhera, Farhan Ahmed, Swanand Kadhe, Syed Zawad, Heiko Ludwig, Holger Boche
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=bmoh0i1nqE
- **中文提要：** 对齐大语言模型是后训练的核心目标，常见途径包括奖励建模和强化学习。其中直接偏好优化（DPO）被广泛采用，它让模型在更受偏好的续写上相对较差续写进行微调。
- **关键词：** DPO, ORPO, preference-optimization, reward-model, post-training, alignment, fine-tuning

### When Weak LLMs Speak with Confidence, Preference Alignment Gets Stronger

- **作者：** Amirabbas Afzali, Myeongho Jeon, Maria Brbic
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ROioaZ45Yz
- **中文提要：** 偏好对齐是让大语言模型适应人类价值的必要步骤，但现有做法通常依赖昂贵的人工标注或大规模接口模型。作者转而考察较弱的大语言模型能否充当有效标注者。
- **关键词：** DPO, preference-optimization, alignment

### Why DPO is a Misspecified Estimator and How to Fix It

- **作者：** Aditya Gopalan, Sayak Ray Chowdhury, Debangshu Banerjee
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=btEiAfnLsX
- **中文提要：** DPO 一类直接对齐算法只用监督学习、依据偏好数据微调模型，而不走两阶段 RLHF。作者指出，DPO 实际上是在参数化策略类所诱导的奖励函数上做统计估计。
- **关键词：** DPO, RLHF, preference-optimization, alignment, fine-tuning

### Why is Your Language Model a Poor Implicit Reward Model?

- **作者：** Noam Razin, Yong Lin, Jiarui Yao, Sanjeev Arora
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=qW05yhm3Zo
- **中文提要：** 奖励模型是语言模型后训练与推理流程中的关键部件。近期工作表明，每个语言模型无需改动架构，就能定义一个隐式奖励模型。
- **关键词：** reward-model, post-training

### Why Reinforcement Fine-Tuning Enables MLLMs Preserve Prior Knowledge Better: A Data Perspective

- **作者：** Zhihao Zhang, Qiaole Dong, Qi Zhang, Enyu Zhou, Jun Zhao, Zhiheng Xi, Senjie Jin, Xiaoran Fan, Yuhao Zhou, Mingqi Wu, Yanwei Fu, Tao Ji, Tao Gui, Xuanjing Huang, Kai Chen
- **会议：** ICLR 2026 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=tP01GCr0nS
- **中文提要：** 监督微调（SFT）与强化微调被广泛用来把多模态大语言模型适配到下游任务。它们在任务适应上有效，但对先前知识保留的影响仍不清楚。
- **关键词：** RFT, SFT, post-training, fine-tuning
