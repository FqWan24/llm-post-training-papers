# 2025 · NeurIPS

共 237 篇。Main 237，Findings 0，其他赛道 0。其中 0 篇来源题录无摘要，提要标明「仅根据标题概括」。

检索窗口为 2024-11-13 至 2026-11-13。题录信息来自官方列表，不在此增补作者、链接或实验数字。

## Main

### Accelerating Block Coordinate Descent for LLM Finetuning via Landscape Expansion

- **作者：** Qijun Luo, Yifei Shen, Liangzu Peng, Dongsheng Li, Xiao Li
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=DBybUx7ARy
- **中文提要：** 对研究者而言，微调大语言模型很耗资源，显存是关键瓶颈。块坐标下降把可训练参数分成若干块，每次只优化一个活跃块并冻结其余块，从而显著降低显存成本。
- **关键词：** fine-tuning

### AC-LoRA: (Almost) Training-Free Access Control Aware Multi-Modal LLMs

- **作者：** Lara Magdalena Lazier, Aritra Dhar, Vasilije Stambolic, Lukas Cavigelli
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=bV5is3iodg
- **中文提要：** 企业内部的大语言模型正被用于高效传播和管理知识。由于当前模型容易泄露敏感信息，要在必须严格访问控制的环境里使用它们仍然困难。
- **关键词：** LoRA, fine-tuning

### Activated LoRA: Fine-tuned LLMs for Intrinsics

- **作者：** Kristjan Greenewald, Luis Lastras, Thomas Parnell, Vraj Shah, Lucian Popa, Giulio Zizzo, Chulaka Gunasekara, Ambrish Rawat, David Cox
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=S6SKa97Gm0
- **中文提要：** 按数据定制大语言模型时，低秩适应已成为首选的高效权重微调框架。多轮对话里切换不同 LoRA 仍然低效，因为整段轮次历史的键值缓存都必须重新计算。
- **关键词：** LoRA, PEFT, fine-tuning

### Adaptive Batch-Wise Sample Scheduling for Direct Preference Optimization

- **作者：** Zixuan Huang, Yikun Ban, Lean Fu, Xiaojie Li, Zhongxiang Dai, Jianxin Li, deqing wang
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=8FN25PlktS
- **中文提要：** 人类偏好对齐中，直接偏好优化已经颇为有效。它的表现却高度取决于底层偏好数据的质量。
- **关键词：** DPO, RLHF, preference-optimization, alignment

### Adaptive Defense against Harmful Fine-Tuning for Large Language Models via Bayesian Data Scheduler

- **作者：** Zixuan Hu, Li Shen, Zhenyi Wang, Yongxian Wei, Dacheng Tao
- **会议：** NeurIPS 2025 · Main · Spotlight
- **官方论文页：** https://openreview.net/forum?id=sm2e1SnMK4
- **中文提要：** 有害微调对大语言模型的微调即服务构成严重安全风险。现有防御预先模拟攻击来建立稳健性，却很难超出有界威胁模型，因为未知攻击难以预见，而且面对变化的攻击时适应性有限。
- **关键词：** alignment, fine-tuning

### Adaptive Divergence Regularized Policy Optimization for Fine-tuning Generative Models

- **作者：** Jiajun Fan, Tong Wei, Chaoran Cheng, Yuxin Chen, Ge Liu
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=aXO0xg0ttW
- **中文提要：** 探索与利用的平衡，是生成模型强化学习微调中的关键难题。现有做法依赖固定散度正则：强正则保住能力但限制奖励优化，弱正则便于对齐却可能不稳定或奖励投机。
- **关键词：** GRPO, DPO, alignment, fine-tuning

### Adaptive LoRA Experts Allocation and Selection for Federated Fine-Tuning

- **作者：** Lei Wang, Jieming Bian, Letian Zhang, Jie Xu
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=es4TTVGJ9x
- **中文提要：** 领域微调往往需要大量、可能分散在多个机构中的领域数据。联邦学习可以在保护隐私的同时利用这些数据，但应用到大语言模型时会遇到计算上的约束。
- **关键词：** LoRA, PEFT, fine-tuning

### Advancing Compositional Awareness in CLIP with Efficient Fine-Tuning

- **作者：** Amit Peleg, Naman Deep Singh, Matthias Hein
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=PTLIM88XYR
- **中文提要：** 视觉语言模型如 CLIP 在分类和检索上具备突出的零样本能力。组合推理却是短板，也就是难以理解概念与概念之间的关系。
- **关键词：** fine-tuning

### AGENTIF: Benchmarking Large Language Models Instruction Following Ability in Agentic Scenarios

- **作者：** Yunjia Qi, Hao Peng, Xiaozhi Wang, Amy Xin, Youfeng Liu, Bin Xu, Lei Hou, Juanzi Li
- **会议：** NeurIPS 2025 · Main · Spotlight
- **官方论文页：** https://openreview.net/forum?id=FLiMxTkIeu
- **中文提要：** 真实世界的智能体应用已经展现出大语言模型的较强能力。此类场景常常包含很长且约束复杂的指令，例如冗长的系统提示和细致的工具说明。
- **关键词：** instruction-following

### A Gradient Guidance Perspective on Stepwise Preference Optimization for Diffusion Models

- **作者：** Joshua Tian Jin Tee, Hee Suk Yoon, Abu Hanif Muhammad Syarubany, Eunseop Yoon, Chang Yoo
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=d6lIOnvOX2
- **中文提要：** 文生图对齐常以直接偏好优化为框架，逐步偏好优化则进一步利用中间步骤学习偏好，以便用更低的计算开销生成更美观的图像。SPO 虽然有效，其背后机制仍然缺少充分研究。
- **关键词：** DPO, preference-optimization, alignment

### Aligning Compound AI Systems via System-level DPO

- **作者：** Xiangwen Wang, Yibo Jacky Zhang, Zhoujie Ding, Katherine Tsai, Haolun Wu, Sanmi Koyejo
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=6IuURCuooO
- **中文提要：** 复合人工智能系统包含多个相互作用的组件，如大语言模型、基础模型和外部工具，在多种任务上相较单一模型有明显提升。要有效部署到真实应用，就需要让这些系统对齐人类偏好。
- **关键词：** DPO, preference-optimization, alignment

### Alignment of Large Language Models with Constrained Learning

- **作者：** Botong Zhang, Shuo Li, Ignacio Hounie, Osbert Bastani, Dongsheng Ding, Alejandro Ribeiro
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=VcJTTVoysQ
- **中文提要：** 约束对齐的目标，是在次要效用约束下最大化主要奖励，并求出相应的最优语言模型策略。拉格朗日式的策略搜索虽然流行，迭代的原对偶方法却常常不收敛。
- **关键词：** RLHF, alignment

### AltLoRA: Towards Better Gradient Approximation in Low-Rank Adaptation with Alternating Projections

- **作者：** Xin Yu, Yujia Wang, Jinghui Chen, Lingzhou Xue
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=9YNJ03jYsU
- **中文提要：** 降低微调显存开销时，低秩适应是一种有效技术。更新被限制在低秩空间，因此表现常常不及全量微调。
- **关键词：** LoRA, fine-tuning

### Ask a Strong LLM Judge when Your Reward Model is Uncertain

- **作者：** Zhenghao Xu, Qin Lu, Qingru Zhang, Liang Qiu, Ilgee Hong, Changlong Yu, Wenlin Yao, Yao Liu, Haoming Jiang, Lihong Li, Hyokun Yun, Tuo Zhao
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=SkdhLeuq8P
- **中文提要：** 经典奖励模型依据人类偏好训练，在 RLHF 中负责对齐大语言模型。它们容易遭遇奖励投机，并且难以泛化到分布外输入。
- **关键词：** RLHF, reward-model, alignment

### Attack via Overfitting: 10-shot Benign Fine-tuning to Jailbreak LLMs

- **作者：** Zhixin Xie, Xurui Song, Jun Luo
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=utvu4PJ0Ct
- **中文提要：** 安全对齐投入虽多，大语言模型仍然很容易被越狱。基于微调的越狱通过微调破坏既有安全对齐，并因效果较稳定而格外突出。
- **关键词：** alignment, fine-tuning

### AuroRA: Breaking Low-Rank Bottleneck of LoRA with Nonlinear Mapping

- **作者：** Haonan Dong, Wenhao Zhu, Guojie Song, Liang Wang
- **会议：** NeurIPS 2025 · Main · Spotlight
- **官方论文页：** https://openreview.net/forum?id=2hgHyoyVWj
- **中文提要：** 作为一种广泛采用的参数高效微调方法，LoRA 已在自然语言处理和计算机视觉中得到验证。它面临固有的低秩瓶颈：缩小与全量微调的差距需要提高参数矩阵的秩，参数开销随之显著增加。
- **关键词：** LoRA, PEFT, fine-tuning

### Auto-Connect: Connectivity-Preserving RigFormer with Direct Preference Optimization

- **作者：** jingfeng Guo, Jian Liu, Jinnan Chen, Shiwei Mao, Changrong Hu, Puhua Jiang, Junlin Yu, Jing Xu, Qi Liu, LiXin Xu, Zhuo Chen, Chunchao Guo
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=uUHNt5CoaL
- **中文提要：** Auto-Connect 面向自动绑骨，借助保持连通性的词元化显式保留骨架连接。它用特殊词元为每个关节的子节点以及每个层级标出端点，而不是把骨骼位置预测成两个关节点，或先预测点再决定如何连接。
- **关键词：** DPO, preference-optimization, post-training, fine-tuning

### Autoregressive Adversarial Post-Training for Real-Time Interactive Video Generation

- **作者：** Shanchuan Lin, Ceyuan Yang, Hao He, Jianwen Jiang, Yuxi Ren, Xin Xia, Yang Zhao, Xuefeng Xiao, Lu Jiang
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=lF6SHARvmG
- **中文提要：** 大规模视频生成模型计算量很大，难以进入实时和交互应用。自回归对抗后训练把预训练的潜空间视频扩散模型，转成可实时交互的流式视频生成器。
- **关键词：** post-training

### AutoVLA: A Vision-Language-Action Model for End-to-End Autonomous Driving with Adaptive Reasoning and Reinforcement Fine-Tuning

- **作者：** Zewei Zhou, Tianhui Cai, Seth Zhao, Yun Zhang, Zhiyu Huang, Bolei Zhou, Jiaqi Ma
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=28qUA2bSe5
- **中文提要：** 端到端自动驾驶开始借助视觉-语言-动作模型的世界知识与推理能力。现有模型仍常给出物理上不可行的动作，或受困于过于复杂的结构和不必要的冗长推理。
- **关键词：** GRPO, RFT, SFT, fine-tuning

### Avoiding exp(R) scaling in RLHF through Preference-based Exploration

- **作者：** Mingyu Chen, Yiding Chen, Wen Sun, Xuezhou Zhang
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=TMSNlEKKeM
- **中文提要：** 在线人类反馈强化学习是这项工作的考察对象，重点在于提高样本效率。RLHF 本身已被视为大语言模型对齐的关键技术。
- **关键词：** RLHF, preference-optimization, alignment

### Backdoor Cleaning without External Guidance in MLLM Fine-tuning

- **作者：** Xuankun Rong, Wenke Huang, Jian Liang, Jinhe Bi, Xun Xiao, Yiming Li, Bo Du, Mang Ye
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=os4QYDf3Ms
- **中文提要：** 微调即服务中，用户提交的数据把通用多模态大语言模型适配到下游任务。这种灵活也带来严重安全风险，恶意微调可以轻易植入后门。
- **关键词：** fine-tuning

### Beyond Higher Rank: Token-wise Input-Output Projections for Efficient Low-Rank Adaptation

- **作者：** Shiwei Li, Xiandi Luo, Haozhao Wang, Xing Tang, Ziqiang Cui, Dugang Liu, Yuhua Li, Xiuqiang He, Ruixuan Li
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=w2xl15ZbD3
- **中文提要：** 大语言模型广泛使用 LoRA 做参数高效微调。它描述的是把输入空间投影到由秩决定维度的低维输出空间。
- **关键词：** LoRA, PEFT, fine-tuning

### Beyond Oracle: Verifier-Supervision for Instruction Hierarchy in Reasoning and Instruction-Tuned LLMs

- **作者：** Sian-Yao Huang, Li-Hsien Chang, Che-Yu Lin, Cheng-Lin Yang
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=IQ513IX1G5
- **中文提要：** 提示里常常同时包含系统指令和用户查询，这些多层指示隐含着权威高低。模型却经常落实不了这一层级，尤其在多步推理中，错误会沿中间步骤传播。
- **关键词：** instruction-tuning, alignment, fine-tuning

### Bilevel ZOFO: Efficient LLM Fine-Tuning and Meta-Training

- **作者：** Reza Shirkavand, Peiran Yu, Qi He, Heng Huang
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=v6vBK4t8vB
- **中文提要：** 一阶优化器把预训练大语言模型微调到下游任务时，计算负担很重。参数高效微调冻结大部分参数、只训练一小部分，用来应对这一开销。
- **关键词：** PEFT, fine-tuning

### BLEUBERI: BLEU is a surprisingly effective reward for instruction following

- **作者：** Yapei Chang, Yekyung Kim, Michael Krumdick, Amir Zadeh, Chuan Li, Chris Tanner, Mohit Iyyer
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=bEYzeItoOH
- **中文提要：** 对齐人类偏好离不开奖励模型，但训练它们代价高，需要大规模人工标注的偏好数据以及强大的预训练骨干。高质量合成指令数据日益增多，于是引出一个问题：强化学习对齐里，更简单的、依赖参考文本的指标能否替代奖励模型。
- **关键词：** GRPO, instruction-following, reward-model, alignment

### Block-Diagonal LoRA for Eliminating Communication Overhead in Tensor Parallel LoRA Serving

- **作者：** Xinyu Wang, Jonas M. Kübler, Kailash Budhathoki, Yida Wang, Matthäus Kleindessner
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=1cjLvtFOmL
- **中文提要：** 同一基座要同时挂上多个不同的 LoRA 适配器时，不能把适配器直接合并进基座权重，否则切换会带来开销，不同适配器的请求也无法合批。因此 LoRA 计算必须与基座计算分开，多设备上还可以把适配器切分开来。
- **关键词：** LoRA, PEFT

### Brain-Informed Fine-Tuning for Improved Multilingual Understanding in Language Models

- **作者：** Anuja Negi, SUBBAREDDY OOTA, Anwar Nunez-Elizalde, Manish Gupta, Fatma Deniz
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=JPogehP8By
- **中文提要：** 已有研究表明，用脑数据微调语言模型可以改善语义理解，不过这些发现限于英语。人类研究为双语者共享语义系统提供了有力证据，这与预训练多语言模型的共享嵌入空间相仿。
- **关键词：** fine-tuning

### BREAD: Branched Rollouts from Expert Anchors Bridge SFT & RL for Reasoning

- **作者：** Xuechen Zhang, Zijian Huang, Yingcong Li, Chenshun Ni, Jiasi Chen, Samet Oymak
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=NUDaln2vCe
- **中文提要：** 复杂推理对小语言模型很难，尤其当高质量轨迹稀缺或很难从中学习时。典型训练先用监督微调从更大模型蒸馏推理能力，再接上强化学习，例如 GRPO。
- **关键词：** GRPO, SFT, fine-tuning

### Can DPO Learn Diverse Human Values? A Theoretical Scaling Law

- **作者：** Shawn Im, Sharon Li
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=XOIKLlSiDq
- **中文提要：** 能力很强的大语言模型仍常常对不齐人类偏好，从而产生有害或不受欢迎的输出。根据人类反馈区分偏好与非偏好回答的偏好学习，已成为让模型贴近人类价值的关键组成部分。
- **关键词：** DPO, preference-optimization

### CF-VLM：CounterFactual Vision-Language Fine-tuning

- **作者：** jusheng zhang, Kaitong Cai, Yijia Fan, Jian Wang, Keze Wang
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=0qGtaRTsCo
- **中文提要：** 视觉语言模型在跨模态语义理解上已有明显进步，细粒度判别和深层因果推理仍然薄弱。现有模型多依赖表面的统计相关，难以抓住视觉内容与文本之间的因果逻辑。
- **关键词：** alignment, fine-tuning

### Chain-of-Zoom: Extreme Super-Resolution via Scale Autoregression and Preference Alignment

- **作者：** Bryan Sangwoo Kim, Jeongsol Kim, Jong Chul Ye
- **会议：** NeurIPS 2025 · Main · Spotlight
- **官方论文页：** https://openreview.net/forum?id=I8S4ASqO5H
- **中文提要：** Chain-of-Zoom 把单图超分辨率拆成一串中间尺度状态的自回归链，并为各尺度配上相应提示。这个与具体超分模型无关的框架，针对的是模型在远超训练倍率时效果崩溃的问题。
- **关键词：** GRPO, preference-optimization, alignment, fine-tuning

### Checklists Are Better Than Reward Models For Aligning Language Models

- **作者：** Vijay Viswanathan, Yanchao Sun, Xiang Kong, Meng Cao, Graham Neubig, Sherry Wu
- **会议：** NeurIPS 2025 · Main · Spotlight
- **官方论文页：** https://openreview.net/forum?id=RPRqKhjrr6
- **中文提要：** 语言模型需要学会理解和遵循用户指令。强化学习被广泛用于这一适配，所用标准通常固定为“有用性”和“有害性”之类的准则。
- **关键词：** instruction-following, reward-model, alignment

### Clean First, Align Later: Benchmarking Preference Data Cleaning for Reliable LLM Alignment

- **作者：** Samuel (Min-Hsuan) Yeh, Sharon Li
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Qa4ADWDTIY
- **中文提要：** 人类反馈对把大语言模型对齐到人类偏好至关重要。这类反馈常常嘈杂或不一致，会降低奖励模型的质量并妨碍对齐。
- **关键词：** reward-model, alignment

### C-LoRA: Contextual Low-Rank Adaptation for Uncertainty Estimation in Large Language Models

- **作者：** Amir Hossein Rahmati, Sanket Jantre, Weifeng Zhang, Yucheng Wang, Byung-Jun Yoon, Nathan Urban, Xiaoning Qian
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=siPeAstQLq
- **中文提要：** 数据稀缺的少样本设定下，低秩适应微调大语言模型时预测常常过度自信。一些经典统计学习方法因此被改造成可扩展的、考虑不确定性的 LoRA 微调。
- **关键词：** LoRA, PEFT, fine-tuning

### CoIDO: Efficient Data Selection for Visual Instruction Tuning via Coupled Importance-Diversity Optimization

- **作者：** Yichen Yan, Ming Zhong, Qi Zhu, Xiaoling Gu, Jinpeng Chen, Huan Li
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=pXXKKBx8G0
- **中文提要：** 多模态大语言模型严重依赖指令微调来对齐视觉与语言，大规模数据上的训练成本成为主要瓶颈。已有数据选择试图挑出既重要又多样的子集，却往往因为要处理全部数据而带来很高的计算开销。
- **关键词：** instruction-tuning, fine-tuning

### ComPO: Preference Alignment via Comparison Oracles

- **作者：** Peter Chen, Xi Chen, Wotao Yin, Tianyi Lin
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=0lNwIIHWhZ
- **中文提要：** 直接对齐方法越来越多地用于把大语言模型对齐到人类偏好。噪声偏好对会让优选与非优选回答的似然变得接近，并由此带来啰嗦和似然位移。
- **关键词：** instruction-tuning, preference-optimization, alignment

### Correlated Low-Rank Adaptation for ConvNets

- **作者：** Wu Ran, Weijia Zhang, ShuYang Pang, Zhu, Jinfan Liu, JingSheng Liu, Xin Cao, Qiang Li, Yichao Yan, Chao Ma
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=3pF7rt9fQM
- **中文提要：** LoRA 在基于 Transformer 的基础模型上做参数高效微调已经相当成功。这类方法通常对各 Transformer 层使用彼此独立的低秩适配。
- **关键词：** LoRA, PEFT, fine-tuning

### CPO: Condition Preference Optimization for Controllable Image Generation

- **作者：** Zonglin Lyu, Ming Li, Xinxin Liu, Chen Chen
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ToEgGjClB9
- **中文提要：** 为增强文生图的可控性，ControlNet 引入基于图像的控制信号，ControlNet++ 则加强生成图与输入控制信号之间的像素级循环一致性。为避开穿过采样过程反传的高昂代价，ControlNet++ 只用单步近似去优化低噪声时间步。
- **关键词：** DPO, preference-optimization, fine-tuning

### CPPO: Accelerating the Training of Group Relative Policy Optimization-Based Reasoning Models

- **作者：** Zhihang Lin, Mingbao Lin, Yuan Xie, Rongrong Ji
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=SVHerutWxp
- **中文提要：** Completion Pruning Policy Optimization（CPPO）用来加快基于 GRPO 的推理模型训练。GRPO 虽然有效，但每道题都要采样多条补全，训练成本因此很高。
- **关键词：** GRPO

### CReFT-CAD: Boosting Orthographic Projection Reasoning for CAD via Reinforcement Fine-Tuning

- **作者：** Ke Niu, Zhuofan Chen, Haiyang Yu, Yuwen Chen, Teng Fu, Mengyang Zhao, Bin Li, Xiangyang Xue
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=FrQd4NoQ16
- **中文提要：** 正投影推理贯穿计算机辅助设计中的设计、制造与仿真。主流深度学习常改走标准三维重建流程，容易带来不精确的尺寸，也限制 CAD 流程所需的参数化可编辑性。
- **关键词：** RFT, SFT, instruction-following, fine-tuning

### CrossSpectra: Exploiting Cross-Layer Smoothness for Parameter-Efficient Fine-Tuning

- **作者：** Yifei Zhang, Hao Zhu, Junhao Dong, Haoran Shi, Ziqiao Meng, Piotr Koniusz, Han Yu
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=rJ5ky9C3ue
- **中文提要：** 参数高效微调让大型基础模型不必承担过高存储成本就能做适配。以 LoRA 为代表的做法把每一层的适配分开处理，因而忽略了跨层相关。
- **关键词：** instruction-following, LoRA, PEFT, fine-tuning

### Data Efficient Adaptation in Large Language Models via Continuous Low-Rank Fine-Tuning

- **作者：** Xiao Han, ZIMO ZHAO, Wanyu Wang, Maolin Wang, Zitao Liu, Yi Chang, Xiangyu Zhao
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=2Qn6skg175
- **中文提要：** 当从头重训在计算上不可行时，微调是把大语言模型适配到具体任务的关键途径。它让模型利用任务或领域数据，从而更贴合目标应用的要求。
- **关键词：** LoRA, fine-tuning

### Data Selection Matters: Towards Robust Instruction Tuning of Large Multimodal Models

- **作者：** Xu Yang, Chen Liu, Ying Wei
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=oLJMsGMfqr
- **中文提要：** 从视觉指令跟随数据中选出紧凑子集，可以在避开全量训练成本的同时，把大型多模态模型对齐到人类意图。全量训练和现有数据选择方法都容易继承位置偏差、虚假相关等数据集偏见，并因此使模型带上偏差。
- **关键词：** instruction-tuning

### DeepVideo-R1: Video Reinforcement Fine-Tuning via Difficulty-aware Regressive GRPO

- **作者：** Jinyoung Park, Jeehye Na, Jinyoung Kim, Hyunwoo J. Kim
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=2YPypUwWIv
- **中文提要：** 基于强化学习的后训练已被用来增强大语言模型的推理能力。其中 GRPO 采用 PPO 风格的强化算法，并以组内归一化的奖励取得了突出效果。
- **关键词：** GRPO, RFT, post-training, fine-tuning

### Delving into RL for Image Generation with CoT: A Study on DPO vs. GRPO

- **作者：** Chengzhuo Tong, Ziyu Guo, Renrui Zhang, Wenyu Shan, Xinyu Wei, Zhenghao Xing, Hongsheng Li, Pheng-Ann Heng
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=tMf3keuPOl
- **中文提要：** 强化学习在增强大语言模型的思维链推理方面作用显著。DPO 与 GRPO 是其中两条主要算法，各自呈现出不同的优劣。
- **关键词：** GRPO, DPO, preference-optimization, reward-model

### DenseDPO: Fine-Grained Temporal Preference Optimization for Video Diffusion Models

- **作者：** Ziyi Wu, Anil Kag, Ivan Skorokhodov, Willi Menapace, Ashkan Mirzaei, Igor Gilitschenski, Sergey Tulyakov, Aliaksandr Siarohin
- **会议：** NeurIPS 2025 · Main · Spotlight
- **官方论文页：** https://openreview.net/forum?id=YFa7eULIeN
- **中文提要：** DPO 近来被用作文生视频扩散模型的后训练技术。训练数据来自标注者对两条由独立噪声生成的视频所给出的偏好。
- **关键词：** DPO, preference-optimization, reward-model, alignment, fine-tuning

### DevFD : Developmental Face Forgery Detection by Learning Shared and Orthogonal LoRA Subspaces

- **作者：** Tianshuo Zhang, Li Gao, Siran Peng, Xiangyu Zhu, Zhen Lei
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Xpuci4SV06
- **中文提要：** 逼真的数字人脸生成与篡改带来显著的社会风险。核心难点在于生成技术演进既快又多样，常常超出已有检测模型的能力。
- **关键词：** LoRA

### Diffusion Model as a Noise-Aware Latent Reward Model for Step-Level Preference Optimization

- **作者：** Tao Zhang, Cheng Da, Kun Ding, Huan Yang, kun jin, Yan Li, Tingting Gao, Di ZHANG, SHIMING XIANG, Chunhong Pan
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=YB9VGCClv9
- **中文提要：** 扩散模型上的偏好优化，目的是让生成图像符合人类偏好。此前做法通常用视觉语言模型充当像素级奖励模型，以此来近似人类偏好。
- **关键词：** preference-optimization, reward-model, alignment

### Direct Alignment with Heterogeneous Preferences

- **作者：** Ali Shirali, Arash Nasr-Esfahany, Abdullah Alomar, Parsa Mirtaheri, Rediet Abebe, Ariel Procaccia
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=lrwntEIcYj
- **中文提要：** 与人类偏好对齐时，常见表述是使用一个统一的奖励函数，尽管偏好本身是异质的。这项工作引入用户类型来形式化这种异质性，并考察同质性假设的限度。
- **关键词：** alignment

### Distortion of AI Alignment: Does Preference Optimization Optimize for Preferences?

- **作者：** Paul Gölz, Nika Haghtalab, Kunhe Yang
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=bkZrAIWK0N
- **中文提要：** 预训练之后，大语言模型依据成对比较来对齐人类偏好。基于 PPO 的 RLHF 和 DPO 等主流方法都建立在单一偏好模型的假设上，实际部署中用户的偏好却是多样的。
- **关键词：** DPO, RLHF, preference-optimization, alignment

### Diversity as a Reward: Fine-Tuning LLMs on a Mixture of Domain-Undetermined Data

- **作者：** Zhenqing Ling, Daoyuan Chen, Liuyi Yao, Qianli Shen, Yaliang Li, Ying Shen
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=AJJ5fBB7JY
- **中文提要：** 用多样数据集微调大语言模型，对提升其在各领域的整体表现很关键。按数据混合比例建模的方法，难以应对领域标签缺失、不精确或未归一的数据；基于数据选择的方法则通常在如何取得平衡上遇到困难。
- **关键词：** fine-tuning

### DLoFT: Gradient-Decoupled Fine-Tuning for Generalizable Long Chain-of-Thought Reasoning

- **作者：** Sitong Wu, Haoru Tan, Jingyao Li, Shaofeng Zhang, Xiaojuan Qi, Bei Yu, Jiaya Jia
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=5ZDT1dxojA
- **中文提要：** 长思维链让大语言模型通过系统而充分的思考来处理复杂任务。在高质量长思维链轨迹上做 SFT 可以激活这种能力，但如此训练的模型容易过拟合到题目特有的知识和启发式。
- **关键词：** SFT, fine-tuning

### DP²O-SR: Direct Perceptual Preference Optimization for Real-World Image Super-Resolution

- **作者：** Rongyuan Wu, Lingchen Sun, Zhengqiang ZHANG, Shihao Wang, Tianhe Wu, Qiaosi Yi, Shuai Li, Lei Zhang
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=45bQUVXmwl
- **中文提要：** 借助预训练的文生图扩散模型，真实场景图像超分辨率能够合成丰富而逼真的细节。由于文生图模型固有的随机性，不同噪声输入常常得到感知质量参差不齐的结果。
- **关键词：** preference-optimization

### DreamPRM: Domain-reweighted Process Reward Model for Multimodal Reasoning

- **作者：** Qi Cao, Ruiyi Wang, Ruiyi Zhang, Sai Ashish Somayajula, Pengtao Xie
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ZyiBk1ZinG
- **中文提要：** 推理显著改善了大语言模型在复杂任务上的表现。过程奖励模型处于当前推理研究的中心，它对中间推理步骤做细粒度评价，并引导推理过程。
- **关键词：** PRM, reward-model, fine-tuning

### Eagle 2.5: Boosting Long-Context Post-Training for Frontier Vision-Language Models

- **作者：** Guo Chen, Zhiqi Li, Shihao Wang, Jindong Jiang, Yicheng Liu, Lidong Lu, De-An Huang, Wonmin Byeon, Matthieu Le, Max Ehrlich, Tong Lu, Limin Wang, Bryan Catanzaro, Jan Kautz, Andrew Tao, Zhiding Yu, Guilin Liu
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=X2xLfqX24x
- **中文提要：** Eagle2.5 是面向长上下文多模态学习的前沿视觉语言模型。它针对长视频理解与高分辨率图像理解中的困难，并为这两类任务给出一个通用框架。
- **关键词：** post-training

### EMLoC: Emulator-based Memory-efficient Fine-tuning with LoRA Correction

- **作者：** Hsi-Che Lin, Yu-Chu Yu, Kai-Po Chang, Frank Wang
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=vqaWAmuzRt
- **中文提要：** 开源基础模型迅速普及，已具备跨领域的通用能力。面向领域任务或个性化任务微调大型基础模型时，推理之外的显存开销仍然让多数用户难以承受。
- **关键词：** LoRA, fine-tuning

### Enhancing Safety in Reinforcement Learning with Human Feedback via Rectified Policy Optimization

- **作者：** Xiyue Peng, Hengquan Guo, Jiawei Zhang, Dongqing Zou, Ziyu Shao, Honghao Wei, Xin Liu
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=qjV3YHW3PD
- **中文提要：** 对齐大语言模型时，兼顾有用性与安全（无害）是关键难题。现有做法常把两个目标拆开，分别为有用性和安全训练偏好模型，并把安全写成约束马尔可夫决策过程中的约束。
- **关键词：** RLHF, alignment

### Enhancing the Outcome Reward-based RL Training of MLLMs with Self-Consistency Sampling

- **作者：** Jiahao Wang, Weiye Xu, Aijun Yang, Wengang Zhou, Lewei Lu, Houqiang Li, Xiaohua Wang, Jinguo Zhu
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=cGkfMGQdCy
- **中文提要：** 基于结果奖励的强化学习，是打磨多模态大语言模型逐步推理的常用途径。在作为多模态推理评测主流形式的选择题设定中，一个常被忽略的障碍是：思维链已经出错、却仍然猜中正确选项的不可靠轨迹。
- **关键词：** GRPO

### Explainable Reinforcement Learning from Human Feedback to Improve Alignment

- **作者：** Shicheng Liu, Siyuan Xu, Wenjie Qiu, Hangfan Zhang, Minghui Zhu
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=k2wzVFXZmC
- **中文提要：** 人在改进不满意的结果时，常见而有效的做法是先找出原因再纠正原因。该研究考察这一策略能否用于改进 RLHF，从而提升语言模型的对齐。
- **关键词：** RLHF, alignment

### Exploring Data Scaling Trends and Effects in Reinforcement Learning from Human Feedback

- **作者：** Wei Shen, Guanlin Liu, Yu Yue, Ruofei Zhu, Qingping Yang, Chao Xin, Lin Yan
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=UQT2inkLmb
- **中文提要：** RLHF 是把大语言模型对齐到人类偏好与价值的关键手段。近期研究多集中在算法改进，例如降低计算开销或加强奖励模型以缓解奖励黑客，而对提示数据如何构造及其可扩展性关注较少。
- **关键词：** RLHF, SFT, reward-model, alignment

### F-Adapter: Frequency-Adaptive Parameter-Efficient Fine-Tuning in Scientific Machine Learning

- **作者：** Hangwei Zhang, Chun Kang, Yan Wang, Difan Zou
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=6QJZDAIhfk
- **中文提要：** 参数高效微调把强大的预训练模型适配到复杂下游任务，在视觉和语言处理中已经有效，但在以复杂物理系统为对象的科学机器学习中仍少有探索。这项工作首次系统研究预训练大算子模型上的 PEFT，这些模型来自傅里叶神经类架构的缩放变体。
- **关键词：** LoRA, PEFT, fine-tuning

### FairNet: Dynamic Fairness Correction without Performance Loss via Contrastive Conditional LoRA

- **作者：** Songqi Zhou, Zeyuan Liu, Benben Jiang
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=t0PtZOlo3y
- **中文提要：** 保证机器学习模型的公平性仍是关键挑战。已有去偏方法常常牺牲性能，依赖静态校正，并且在数据稀疏、尤其是少数群体上难以应对。
- **关键词：** LoRA

### FALQON: Accelerating LoRA Fine-tuning with Low-Bit Floating-Point Arithmetic

- **作者：** Kanghyun Choi, Hyeyoon Lee, Sunjong Park, Dain Kwon, Jinho Lee
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=yPXOfBoQL7
- **中文提要：** 低位浮点格式借助现代 GPU 和 NPU 的原生硬件支持，能在训练中加速并节省显存。分析指出，这种量化的加速主要出现在大维度矩阵乘上；用到维度较小的 LoRA 时，量化开销会削弱加速效果。
- **关键词：** LoRA, post-training, fine-tuning

### Fast and Fluent Diffusion Language Models via Convolutional Decoding and Rejective Fine-tuning

- **作者：** Yeongbin Seo, Dongha Lee, Jaehyung Kim, Jinyoung Yeo
- **会议：** NeurIPS 2025 · Main · Spotlight
- **官方论文页：** https://openreview.net/forum?id=HvIRFV0J90
- **中文提要：** 自回归语言模型一次生成一个词元，推理速度因此受限。基于扩散的语言模型可以并行解码多个词元，提供了另一条生成路线。
- **关键词：** fine-tuning

### Fast-Slow Thinking GRPO for Large Vision-Language Model Reasoning

- **作者：** Wenyi Xiao, Leilei Gan
- **会议：** NeurIPS 2025 · Main · Spotlight
- **官方论文页：** https://openreview.net/forum?id=MI1uT5rReV
- **中文提要：** 把强化学习、通常是 GRPO，用于大型视觉语言模型的推理时，要么难以有效拉长推理，要么在所有任务上都生成冗长输出，准确率却只有有限提升。FAST-GRPO 作为 GRPO 的变体，按题目特点动态调整推理深度。
- **关键词：** GRPO

### FedSVD: Adaptive Orthogonalization for Private Federated Learning with LoRA

- **作者：** Seanie Lee, Sangwoo Park, Dong Bok Lee, Dominik Wagner, Haebin Seong, Tobias Bocklet, Juho Lee, Sung Ju Hwang
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Qq19n9LZ97
- **中文提要：** LoRA 把一对可训练低秩矩阵的乘积引入冻结的预训练权重，被广泛用于联邦学习中的语言模型高效微调。与差分隐私随机梯度下降结合时会出现明显的噪声放大：DP-SGD 扰动逐样本梯度，低秩矩阵乘法也牵涉其中。
- **关键词：** LoRA, fine-tuning

### Finding and Reactivating Post-Trained LLMs' Hidden Safety Mechanisms

- **作者：** Mingjie Li, Wai Man Si, Michael Backes, Yang Zhang, Yisen Wang
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=pcG6NRJKu7
- **中文提要：** 通用大语言模型尽管表现突出，要在特定任务上出色往往仍需微调或后训练。以 DeepSeek-R1 系列为例的大推理模型，是在多样思维链数据上对不同的通用大模型做后训练之后，才展现出较强的推理能力。
- **关键词：** LoRA, post-training, alignment, fine-tuning

### Fine-Grained Preference Optimization Improves Spatial Reasoning in VLMs

- **作者：** Yifan Shen, Yuanzhe Liu, Jingyuan Zhu, Xu Cao, Xiaofeng Zhang, Yixiao He, Wenming Ye, James Rehg, Ismini Lourentzou
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=L9vV3wVC72
- **中文提要：** 当前视觉语言模型不擅长细粒度空间推理，尤其当需要多步逻辑和精确的空间对齐时。SpatialReasoner-R1 被提出作为应对这些不足的视觉语言推理模型。
- **关键词：** DPO, preference-optimization, alignment

### Fine-Tuning Discrete Diffusion Models with Policy Gradient Methods

- **作者：** Oussama Zekri, Nicolas Boulle
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=rXFzVRZsbt
- **中文提要：** 离散扩散模型因能处理语言建模中的复杂离散结构而受到关注。像 RLHF 中那样用策略梯度方法来微调这些模型，仍然是一项困难任务。
- **关键词：** RLHF, fine-tuning

### First SFT, Second RL, Third UPT: Continual Improving Multi-Modal LLM Reasoning via Unsupervised Post-Training

- **作者：** Lai Wei, Yuting Li, Chen Wang, Yue Wang, Linghe Kong, Weiran Huang, Lichao Sun
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=HL1j92hb6z
- **中文提要：** 在后训练阶段提升多模态大语言模型，通常依赖 SFT 或强化学习，而这两者都需要昂贵的人工标注多模态数据。这一限制促使人们把无监督范式作为 SFT 和强化学习之后的第三阶段。
- **关键词：** GRPO, SFT, post-training, self-rewarding, fine-tuning

### Fixing It in Post: A Comparative Study of LLM Post-Training Data Quality and Model Performance

- **作者：** Aladin Djuhera, Swanand Kadhe, Syed Zawad, Farhan Ahmed, Heiko Ludwig, Holger Boche
- **会议：** NeurIPS 2025 · Main · Spotlight
- **官方论文页：** https://openreview.net/forum?id=1ybOI1VvQL
- **中文提要：** 近期大语言模型研究越来越关注后训练与对齐，所用数据集被整理来加强指令遵循、世界知识和专项技能。领先的开源与闭源模型使用的后训练数据集大多不向公众开放，其构建过程的信息也很有限。
- **关键词：** SFT, instruction-following, post-training, alignment

### FlowerTune: A Cross-Domain Benchmark for Federated Fine-Tuning of Large Language Models

- **作者：** Yan Gao, Massimo R. Scamarcia, Javier Fernandez-Marques, Mohammad Naseri, Chong Ng, Dimitris Stripelis, Zexi Li, Tao Shen, Jiamu Bai, Daoyuan Chen, Zikai Zhang, Rui Hu, InSeo Song, KangYoon Lee, Hong Jia, Ting Dang, Junyan Wang, Zheyuan Liu, Daniel J. Beutel, Lingjuan Lyu, Nicholas Lane
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=l8Nb6ecZjW
- **中文提要：** 大语言模型的开发仍依赖大量公开数据，因而面临数据稀缺，也难以获取领域内的敏感信息。联邦学习提供了一种框架，使预训练大模型可以在去中心化条件下进行微调。
- **关键词：** instruction-tuning, fine-tuning

### Flow-GRPO: Training Flow Matching Models via Online RL

- **作者：** Jie Liu, Gongye Liu, Jiajun Liang, Yangguang Li, Jiaheng Liu, Xintao Wang, Pengfei Wan, Di ZHANG, Wanli Ouyang
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=oCBKGw5HNf
- **中文提要：** Flow-GRPO 首次把在线策略梯度强化学习接入流匹配模型。其关键步骤之一是把确定性常微分方程转换成等价的随机微分方程，并在各个时间步保持与原模型相同的边缘分布。
- **关键词：** GRPO, preference-optimization, alignment

### From Style to Facts: Mapping the Boundaries of Knowledge Injection with Finetuning

- **作者：** Eric Zhao, Pranjal Awasthi, Nika Haghtalab
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=OGgV9hpVGD
- **中文提要：** 微调是按特定任务或回答风格定制语言模型的可扩展、低成本途径，可靠性高于提示或上下文学习。与此相对，通常认为经由微调注入知识会导致表现脆弱、泛化差。
- **关键词：** instruction-tuning, fine-tuning

### Fundamental Limitations in Pointwise Defences of LLM Finetuning APIs

- **作者：** Xander Davies, Eric Winsor, Alexandra Souly, Tomek Korbak, Robert Kirk, Christian Schroeder de Witt, Yarin Gal
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=V4SA2FOzQL
- **中文提要：** 为阻止对手通过公开微调接口绕过安全措施，大模型开发者部署了技术性缓解。已有工作对某些微调接口防御做出过成功攻击，但那些攻击的训练或推理样本很容易被标为可疑。
- **关键词：** fine-tuning

### Gated Integration of Low-Rank Adaptation for Continual Learning of Large Language Models

- **作者：** Yan-Shuo Liang, Jia-Rui Chen, Wu-Jun Li
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=lVV7F0piDK
- **中文提要：** 持续学习要求模型按顺序学习多个任务，对大语言模型至关重要。LoRA 作为代表性的参数高效微调方法，在大模型持续学习中受到越来越多的关注。
- **关键词：** LoRA, PEFT, fine-tuning

### Generalizing Verifiable Instruction Following

- **作者：** Valentina Pyatkin, Saumya Malik, Victoria Graf, Hamish Ivison, Shengyi Huang, Pradeep Dasigi, Nathan Lambert, Hanna Hajishirzi
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=yfYgwjj5F8
- **中文提要：** 语言模型或对话系统能否精确遵循人类指令，对人机交互是否成功很关键。指令里常见各种输出约束，例如只能用是否作答，或必须提到某个指定词语，即便当前很强的模型也难以满足。
- **关键词：** RLVR, instruction-following

### Generative RLHF-V: Learning Principles from Multi-modal Human Preference

- **作者：** Jiayi Zhou, Jiaming Ji, Boyuan Chen, Jiapeng Sun, wenqi chen, Donghai Hong, Sirui Han, Yike Guo, Yaodong Yang
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Evz0xPema0
- **中文提要：** 训练与人类意图对齐的多模态大语言模型是一项长期挑战。传统只输出分数的奖励模型准确度低、泛化弱、可解释性差，因而拖累了 RLHF 等对齐方法。
- **关键词：** RLHF, reward-model, alignment

### Geometry-Aware Collaborative Multi-Solutions Optimizer for Model Fine-Tuning with Parameter Efficiency

- **作者：** Van-Anh Nguyen, Trung Le, Mehrtash Harandi, Ehsan Abbasnejad, Thanh-Toan Do, Dinh Phung
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=SbJAGSdLhY
- **中文提要：** 该框架以梯度流理论为基础，并利用几何结构，为同一任务提供多个多样的解，再通过协同来增强跨任务的表现与适应性。它支持按任务做高效微调，同时保留预训练基础模型已有的知识。
- **关键词：** fine-tuning

### GraLoRA: Granular Low-Rank Adaptation for Parameter-Efficient Fine-Tuning

- **作者：** Yeonjoon Jung, Daehyun Ahn, Hyungjun Kim, Taesu Kim, Eunhyeok Park
- **会议：** NeurIPS 2025 · Main · Spotlight
- **官方论文页：** https://openreview.net/forum?id=8wvOMQ2Olw
- **中文提要：** LoRA 因简单有效，成为生成模型参数高效微调的常用方法。即便已有不少改进，当瓶颈被加宽时，它仍然会过拟合。
- **关键词：** LoRA, PEFT, fine-tuning

### GRAVER: Generative Graph Vocabularies for Robust Graph Foundation Models Fine-tuning

- **作者：** Haonan Yuan, Qingyun Sun, Junhua Shi, Xingcheng Fu, Bryan Hooi, Jianxin Li, Philip S Yu
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=tyERwC5520
- **中文提要：** 受语言与视觉基础模型的启发，图基础模型有望覆盖多样的图任务与领域。现有图基础模型在少样本微调时不稳定，表现和适配效率会因支持样本选取的随机性而明显波动。
- **关键词：** fine-tuning

### Greedy Sampling Is Provably Efficient For RLHF

- **作者：** Di Wu, Chengshuai Shi, Jing Yang, Cong Shen
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=jQH0gdwsuT
- **中文提要：** RLHF 已成为大语言模型后训练的关键技术。其理论认识仍然有限，因为只凭偏好反馈去学习带 KL 正则的目标，比标准强化学习更加困难。
- **关键词：** RLHF

### GRE Suite: Geo-localization Inference via Fine-Tuned Vision-Language Models and Enhanced Reasoning Chains

- **作者：** Chun Wang, Xiaojun Ye, Xiaoran Pan, Zihao Pan, Haofan Wang, Yiren Song
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=4H3xG3aDS1
- **中文提要：** 视觉语言模型在视觉推理任务上已经表现出色。地理定位仍有其特殊困难：需要从图像中提取多粒度视觉线索，并结合外部世界知识进行系统推理。
- **关键词：** fine-tuning

### Guiding Cross-Modal Representations with MLLM Priors via Preference Alignment

- **作者：** Pengfei Zhao, Rongbo Luan, Wei Zhang, Peng Wu, Sifeng He
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=jZs26lJ0pl
- **中文提要：** CLIP 虽然能够跨模态检索内容，其特征空间里仍存在明显的模态间隙。现成的多模态大语言模型则表现出很强的固有模态对齐性质。
- **关键词：** DPO, preference-optimization, alignment

### Guiding LLM Decision-Making with Fairness Reward Models

- **作者：** Zara Hall, Melanie Subbiah, Thomas Zollo, Kathleen McKeown, Richard Zemel
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=DkSeM3AZVs
- **中文提要：** 大语言模型越来越多地参与保释、贷款等高风险决策。朴素的思维链采样可以提高平均决策准确度，但也被证明会放大不公平偏见。
- **关键词：** reward-model, fine-tuning

### GVPO: Group Variance Policy Optimization for Large Language Model Post-Training

- **作者：** Kaichen Zhang, Yuzhong Hong, Junwei Bao, Hongfei Jiang, Yang Song, Hong Dingqian, Hui Xiong
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=cCYUFaR6En
- **中文提要：** 后训练用来把大语言模型打磨并对齐到具体任务和人类偏好。GRPO 一类方法靠增加采样并用相对奖励评分来追求更好效果，但训练不稳定限制了实际采用。
- **关键词：** GRPO, post-training, alignment

### Harmony in Divergence: Towards Fast, Accurate, and Memory-efficient Zeroth-order LLM Fine-tuning

- **作者：** Qitao Tan, Jun Liu, Zheng Zhan, Caiwen Ding, Yanzhi Wang, Xiaolong Ma, Jaewoo Lee, Jin Lu, Geng Yuan
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Rx6m16By6l
- **中文提要：** 标准的一阶微调需要大量显存，限制了大语言模型的实际部署。零阶优化不做反向传播、只靠前向估计梯度，成为一种更省显存、适合资源受限场景的训练方式。
- **关键词：** fine-tuning

### Hierachical Balance Packing: Towards Efficient Supervised Fine-tuning for Long-Context LLM

- **作者：** Yongqiang Yao, Jingru Tan, Kaihuan Liang, Feizhao Zhang, Jiahao Hu, Shuo Wu, Yazhe Niu, Ruihao Gong, Dahua Lin, Ningyi Xu
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=6BHDre6WQW
- **中文提要：** 训练长上下文大语言模型时，长短上下文数据混合训练常常造成负载不均。已有工作主要靠数据打包来缓解，却没有考虑注意力计算不均衡以及由此浪费的通信开销。
- **关键词：** SFT, fine-tuning

### Hierarchical Fine-grained Preference Optimization for Physically Plausible Video Generation

- **作者：** Harold Haodong Chen, Haojian Huang, Qifeng Chen, Harry Yang, Ser Nam Lim
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=y0SRR9XGlZ
- **中文提要：** 视频生成已经能够做出画质高、视觉上吸引人的结果。要让生成的视频符合物理规律，对需要真实与准确的应用仍然是关键难题。
- **关键词：** DPO, preference-optimization, alignment

### HiMoLE: Towards OOD-Robust LoRA via Hierarchical Mixture of Experts

- **作者：** Yinuo Jiang, Yan Xiaodong, Keyan Ding, Deng Zhao, Lei Liang, Qiang Zhang, Huajun Chen
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=wsR7VYXbdR
- **中文提要：** LoRA 等参数高效微调只更新一小部分参数，就能高效适配大语言模型。这类方法在分布外条件下的稳健性仍然研究不足。
- **关键词：** LoRA, PEFT, fine-tuning

### HMVLM:Human Motion-Vision-Language Model via MoE LoRA

- **作者：** Lei Hu, Yongjing Ye, Shihong Xia
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Gvq2AfuVEA
- **中文提要：** 指令微调数据不断扩充后，基础语言模型更能遵循指令，并在多样下游任务上表现更好。语义丰富的三维人体动作正被逐步接入这些基础模型，以增强多模态理解与跨模态生成。
- **关键词：** instruction-tuning, LoRA, fine-tuning

### Human-assisted Robotic Policy Refinement via Action Preference Optimization

- **作者：** Wenke Xia, Yichu Yang, Hongtao Wu, Xiao Ma, Tao Kong, Di Hu
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=dlQ1iUpQNf
- **中文提要：** 要落地真实应用，机器人系统需要可靠且能迭代改进。视觉-语言-动作模型虽被广泛视为这类部署的基础模型，但对离线专家示范的依赖，严重限制了部署之后继续精炼的能力。
- **关键词：** preference-optimization, alignment

### Hyperbolic Fine-Tuning for Large Language Models

- **作者：** Menglin Yang, Ram Samarth B B, Aosong Feng, Bo Xiong, Jiahong Liu, Irwin King, Rex Ying
- **会议：** NeurIPS 2025 · Main · Spotlight
- **官方论文页：** https://openreview.net/forum?id=TkEdQv0bXB
- **中文提要：** 大语言模型在多种任务上表现突出，但默认的欧氏空间是否最适合用来嵌入词元，仍然是一个开放问题。
- **关键词：** LoRA, fine-tuning

### Implicit Reward as the Bridge: A Unified View of SFT and DPO Connections

- **作者：** Bo Wang, Qinyuan Cheng, Runyu Peng, Rong Bao, Peiji Li, Qipeng Guo, Linyang Li, Zhiyuan Zeng, Yunhua Zhou, Xipeng Qiu
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=xUx2B2NHvj
- **中文提要：** 后训练是把预训练语言模型落到真实任务上的必要阶段，从示范或偏好信号中学习在其中很关键。作者给出统一理论框架，把大语言模型后训练里的监督微调 SFT 与偏好学习衔接起来。
- **关键词：** DPO, SFT, instruction-following, preference-optimization, post-training, fine-tuning

### Improving Data Efficiency for LLM Reinforcement Fine-tuning Through Difficulty-targeted Online Data Selection and Rollout Replay

- **作者：** Yifan Sun, Jingyan Shen, Yibin Wang, Tianyu Chen, Zhendong Wang, Mingyuan Zhou, Huan Zhang
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=uwUkETPIJN
- **中文提要：** 强化学习已成为微调大语言模型的有效途径，尤其有助于增强推理能力。不过这类微调仍然非常耗费资源，现有工作也大多忽略了数据效率。
- **关键词：** GRPO, RFT, fine-tuning

### Improving LLM General Preference Alignment via Optimistic Online Mirror Descent

- **作者：** Yuheng Zhang, Dian Yu, Tao Ge, Linfeng Song, Zhichen Zeng, Haitao Mi, Nan Jiang, Dong Yu
- **会议：** NeurIPS 2025 · Main · Spotlight
- **官方论文页：** https://openreview.net/forum?id=kZstGANG8D
- **中文提要：** RLHF 在使大语言模型对齐人类偏好方面效果显著。许多现有对齐方法依赖 Bradley-Terry 模型假设，即认为每个提示与回复对都存在一个真实奖励。
- **关键词：** RLHF, preference-optimization, alignment

### Improving Reward Models with Proximal Policy Exploration for Preference-Based Reinforcement Learning

- **作者：** Yiwen Zhu, Jinyi Liu, Pengjie Gu, Yifu Yuan, Zhenxing Ge, Wenya Wei, Zhou Fang, Yujing Hu, Bo An
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=9KIvyH3L7c
- **中文提要：** 强化学习严重依赖精心设计的奖励函数，而复杂行为的奖励常常有偏且难以设计。基于偏好的强化学习改由人类反馈学习奖励模型，但现有方法虽用查询优化减轻人工，却忽略了偏好缓冲区受限的一面。
- **关键词：** reward-model

### Improving Video Generation with Human Feedback

- **作者：** Jie Liu, Gongye Liu, Jiajun Liang, Ziyang Yuan, Xiaokun Liu, Mingwu Zheng, Xiele Wu, Qiulin Wang, Menghan Xia, Xintao Wang, Xiaohong Liu, Fei Yang, Pengfei Wan, Di ZHANG, Kun Gai, Yujiu Yang, Wanli Ouyang
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=nHkg4yc7SP
- **中文提要：** 整流流技术让视频生成取得明显进展，但不流畅的运动以及视频与提示不对齐依然存在。有工作搭建一套系统流程，借助人类反馈缓解这些问题并改进视频生成模型。
- **关键词：** DPO, SFT, preference-optimization, reward-model, alignment, fine-tuning

### Incentivizing Reasoning for Advanced Instruction-Following of Large Language Models

- **作者：** Yulei Qin, Gang Li, Zongyi Li, Zihan Xu, Yuchen Shi, Zhekai Lin, Xiao Cui, Ke Li, Xing Sun
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=vRVfgcoeIl
- **中文提要：** 现有大语言模型难以遵循复杂指令，尤其当多重约束以并行、链式和分支结构组织时。思维链被寄望为一种能普遍提升模型能力的直观办法。
- **关键词：** instruction-following

### Inference-time Alignment in Continuous Space

- **作者：** Yige Yuan, Teng Xiao, Li Yunfan, Bingbing Xu, Shuchang Tao, Yunqi Qiu, Huawei Shen, Xueqi Cheng
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=aokiuaM7Lt
- **中文提要：** 在推理阶段用人类反馈对齐大语言模型，因其灵活性而越来越受关注。现有做法从基础策略生成多条回复，再交由奖励模型搜索，相当于在离散的回复空间中寻找。
- **关键词：** reward-model, alignment

### InfiFPO: Implicit Model Fusion via Preference Optimization in Large Language Models

- **作者：** Yanggan Gu, Yuanyi Wang, Zhaoyi Yan, Yiming Zhang, Qi Zhou, Fei Wu, Hongxia Yang
- **会议：** NeurIPS 2025 · Main · Spotlight
- **官方论文页：** https://openreview.net/forum?id=ZwBtDbuzjY
- **中文提要：** 模型融合通过轻量训练，把各有所长的多个大语言模型合成更强的整体模型。现有融合工作主要围绕 SFT，偏好对齐这一提升表现的关键阶段则大多未被探索。
- **关键词：** DPO, SFT, preference-optimization, alignment, fine-tuning

### Information-Theoretic Reward Decomposition for Generalizable RLHF

- **作者：** Liyuan Mao, Haoran Xu, Amy Zhang, Weinan Zhang, Chenjia Bai
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ONebBepE9l
- **中文提要：** 可泛化的奖励模型对 RLHF 至关重要，这样才能正确评估未见过的提示-回复对。现有奖励模型通常只拉大被选回复与被拒回复的奖励差距，却忽略这些回复所条件于的提示，因此缺乏这种能力。
- **关键词：** RLHF, reward-model, alignment

### INST-IT: Boosting Instance Understanding via Explicit Visual Prompt Instruction Tuning

- **作者：** Wujian Peng, Lingchen Meng, Yitong Chen, Yiweng Xie, Yang Liu, Tao Gui, Hang Xu, Xipeng Qiu, Zuxuan Wu, Yu-Gang Jiang
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=8tetkBNSWZ
- **中文提要：** 随着指令微调发展，大型多模态模型取得了显著突破。它们能从整体上理解图像和视频，却仍难以做实例级理解，而后者需要更细粒度的把握与对齐。
- **关键词：** instruction-tuning, alignment

### InterMT: Multi-Turn Interleaved Preference Alignment with Human Feedback

- **作者：** Boyuan Chen, Donghai Hong, Jiaming Ji, Jiacheng Zheng, Bowen Dong, Jiayi Zhou, Kaile Wang, Juntao Dai, Xuyao Wang, wenqi chen, Qirui Zheng, Wenxin Li, Sirui Han, Yike Guo, Yaodong Yang
- **会议：** NeurIPS 2025 · Main · Spotlight
- **官方论文页：** https://openreview.net/forum?id=4SUtAp2cm0
- **中文提要：** 多模态大模型在困难任务上不断进步，仍有哪些必要能力缺失成为一个关键问题。人类学习依赖与环境的持续交互，既不限于语言，也包含多模态理解与生成；要更接近人类水平的智能，模型同样需要支持这类交互。
- **关键词：** preference-optimization, alignment

### Iterative Tool Usage Exploration for Multimodal Agents via Step-wise Preference Tuning

- **作者：** Pengxiang Li, Zhi Gao, Bofei Zhang, Yapeng Mi, Xiaojian (Shawn) Ma, Chenrui Shi, Tao Yuan, Yuwei Wu, Yunde Jia, Song-Chun Zhu, Qing Li
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=yKUwkihcsi
- **中文提要：** 多模态智能体把控制器（例如视觉语言模型）与外部工具结合起来，已能应对复杂的多模态任务。无论监督微调还是强化学习，现有训练都依赖大量人工标注的任务答案对以及工具轨迹。
- **关键词：** SFT, preference-optimization, fine-tuning

### KL Penalty Control via Perturbation for Direct Preference Optimization

- **作者：** Sangkyu Lee, Janghoon Han, Hosung Song, Stanley Jungkyu Choi, Honglak Lee, Youngjae Yu
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=00oRAPDWsX
- **中文提要：** DPO 的优势在于只用离线数据集就能把大语言模型对齐到人类偏好。其局限是，防止相对参考模型过度偏离的 KL 惩罚在整个训练中保持静态。
- **关键词：** DPO, preference-optimization, alignment

### KL-Regularized RLHF with Multiple Reference Models: Exact Solutions and Sample Complexity

- **作者：** Gholamali Aminian, Amir R. Asadi, Idan Shenfeld, Youssef Mroueh
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=j8XnFfTvXF
- **中文提要：** 近期用人类反馈对齐大语言模型的方法大多依赖单一参考模型，从而限制多样性、伴随过拟合，也未能充分利用大量现成的预训练模型。纳入多个参考模型有望拓宽视角、降低偏差，并借助多样开源模型的长处。
- **关键词：** RLHF, alignment

### Know What You Don't Know: Uncertainty Calibration of Process Reward Models

- **作者：** Young-Jin Park, Kristjan Greenewald, Kaveh Alimohammadi, Hao Wang, Navid Azizan
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=hzMkfIrdDT
- **中文提要：** 过程奖励模型在引导大语言模型的推理时扩展算法中处于中心位置。即便是目前先进的过程奖励模型，校准也可能很差。
- **关键词：** PRM, reward-model

### LASeR: Learning to Adaptively Select Reward Models with Multi-Arm Bandits

- **作者：** Duy Nguyen, Archiki Prasad, Elias Stengel-Eskin, Mohit Bansal
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=tSpWkTFASC
- **中文提要：** 奖励模型对对齐大语言模型至关重要，但专精于某一任务（例如写作）的奖励模型，能在多大程度上泛化到新任务仍不明确。
- **关键词：** instruction-following, reward-model, alignment

### Latent Space Factorization in LoRA

- **作者：** Shashi Kumar, Yacouba Kaloga, John Mitros, Petr Motlicek, Ina Kodrasi
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Bqui2s3xFi
- **中文提要：** LoRA 是广泛使用的参数高效微调方法。现有变体缺少在学到的低秩子空间中显式区分任务相关信息的机制，这可能限制下游表现。
- **关键词：** LoRA, PEFT, fine-tuning

### Learning to Instruct for Visual Instruction Tuning

- **作者：** Zhihan Zhou, Feng Hong, JIAAN LUO, Yushi Ye, Jiangchao Yao, Dongsheng Li, Bo Han, Ya Zhang, Yanfeng Wang
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=NQSWkmjODD
- **中文提要：** L2T 旨在推进视觉指令微调。视觉指令微调虽让多模态大语言模型具备可观的多模态能力，但当前设计选择常造成过拟合和捷径学习，并可能损害表现。
- **关键词：** instruction-tuning, instruction-following

### Learning to Think: Information-Theoretic Reinforcement Fine-Tuning for LLMs

- **作者：** Jingyao Wang, Wenwen Qiang, Zeen Song, Changwen Zheng, Hui Xiong
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=22CqLfjiVl
- **中文提要：** 得益于推理能力的进步，大语言模型能够胜任复杂任务。现有方法却忽视推理效果与效率之间的权衡，往往鼓励不必要的长推理链，从而浪费词元。
- **关键词：** RFT, PRM, fine-tuning

### Less is More: Improving LLM Alignment via Preference Data Selection

- **作者：** Xun Deng, Han Zhong, Rui Ai, Fuli Feng, Zheng Wang, Xiangnan He
- **会议：** NeurIPS 2025 · Main · Spotlight
- **官方论文页：** https://openreview.net/forum?id=R2ZJSjLDJC
- **中文提要：** DPO 已成为把大语言模型对齐到人类偏好的一条有希望的路线。先前工作主要从目标函数一侧扩展 DPO，这里则从长期被忽视、却很关键的数据选择入手来改进它。
- **关键词：** DPO, preference-optimization, reward-model, alignment

### Leveraging robust optimization for llm alignment under distribution shifts

- **作者：** Mingye Zhu, Yi Liu, Zheren Fu, Yongdong Zhang, Zhendong Mao
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=pdc0yEoOj6
- **中文提要：** 偏好对齐对引导大语言模型生成符合人类价值的输出越来越关键。近期方法为了可扩展和省成本，常依赖模型生成的合成数据，这种依赖会引入分布偏移，损害对人类偏好细微差别的表达。
- **关键词：** preference-optimization, alignment

### LeVo: High-Quality Song Generation with Multi-Preference Alignment

- **作者：** Shun Lei, Yaoxun XU, ZhiweiLin, Huaicheng Zhang, Wei tan, Hangting Chen, Yixuan Zhang, Chenyu Yang, Haina Zhu, Shuai Wang, Zhiyong Wu, Dong Yu
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Oul46PkP7Z
- **中文提要：** 大语言模型与音频语言模型的进展显著改善了音乐生成，尤其是由歌词生成歌曲。现有方法仍难以处理歌曲的复杂构成以及高质量数据稀缺，因而在音质、音乐性、指令遵循和人声与乐器的和谐上受到限制。
- **关键词：** DPO, instruction-following, preference-optimization, post-training, alignment

### LIFEBENCH: Evaluating Length Instruction Following in Large Language Models

- **作者：** Wei Zhang, Zhenhong Zhou, Kun Wang, Junfeng Fang, Rongwu Xu, Yuanhe Zhang, Rui Wang, Ge Zhang, Xinfeng Li, Li Sun, Lingjuan Lyu, Yang Liu, Sen Su
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=dndqkXKY6W
- **中文提要：** 大语言模型能在长上下文输入上解决博士级推理问题，却仍难以完成看似更简单的任务：遵循明确的长度指令。模型还经常输出过短、提前终止，甚至拒绝请求。
- **关键词：** instruction-following

### Limited Preference Data? Learning Better Reward Model with Latent Space Synthesis

- **作者：** Leitian Tao, Xuefeng Du, Sharon Li
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=dbaYQyruY2
- **中文提要：** 奖励建模对把大语言模型对齐到人类偏好至关重要，却常常受限于偏好数据的高成本。现有的文本数据合成方法计算开销很大。
- **关键词：** reward-model, alignment

### Linearization Explains Fine-Tuning in Large Language Models

- **作者：** Zahra Rahimi Afzal, Tara Esmaeilbeig, Mojtaba Soltanalian, Mesrob I Ohannessian
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=tdwRIP6NG2
- **中文提要：** PEFT 是一类流行技术，力求以可扩展、省资源的方式适配大模型。它们训练表现与泛化背后的机制仍然缺少充分探讨。
- **关键词：** LoRA, PEFT, fine-tuning

### LLM at Network Edge: A Layer-wise Efficient Federated Fine-tuning Approach

- **作者：** Jinglong Shen, Nan Cheng, Wenchao Xu, Haozhao Wang, Yifan guo, Jiajie Xu
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=DqRbfiTdKK
- **中文提要：** 微调大语言模型带来沉重计算负担，在联邦学习设定下尤其如此。LEFF 是一种按层进行的高效联邦微调方法，意在提高联邦微调效率，同时保持模型表现并尽量减少客户端计算开销。
- **关键词：** fine-tuning

### LongVPO: From Anchored Cues to Self-Reasoning for Long-Form Video Preference Optimization

- **作者：** Zhenpeng Huang, Jiaqi Li, zihan jia, Xinhao Li, Desen Meng, Lingxue Song, Xi Chen, Liang Li, Limin Wang
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=LKAp7Dknxf
- **中文提要：** LongVPO 是一种两阶段直接偏好优化框架，让短上下文视觉语言模型在没有任何长视频标注的情况下稳健理解超长视频。第一阶段把问题锚定到各个短片段、穿插干扰项来合成偏好三元组，并施加视觉相似度与问题特异性过滤。
- **关键词：** DPO, preference-optimization, alignment

### Loquetier: A Virtualized Multi-LoRA Framework for Unified LLM Fine-tuning and Serving

- **作者：** Yuchen Zhang, Hanyue Du, Chun Cao, Jingwei Xu
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=45igeoC560
- **中文提要：** LoRA 已成为把大语言模型适配到下游任务时广泛采用的 PEFT 技术。先前工作探索过整合训练与服务的策略，但在统一基于 LoRA 的微调与推理方面仍有空白。
- **关键词：** LoRA, PEFT, fine-tuning

### LoRA-EnVar: Parameter-Efficient Hybrid Ensemble Variational Assimilation for Weather Forecasting

- **作者：** Yi Xiao, Hang Fan, Kun Chen, Ye Cao, Ben Fei, Wei Xue, LEI BAI
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=zhMl4Smau7
- **中文提要：** 准确估计背景误差（即预报误差）的分布，对数值天气预报中有效的资料同化至关重要。先进的业务同化系统常用混合方法刻画背景误差随时间的变化，将静态气候协方差与随气流变化的集合分量结合起来。
- **关键词：** LoRA, PEFT, fine-tuning

### LoRASuite: Efficient LoRA Adaptation Across Large Language Model Upgrades

- **作者：** Yanan Li, Fanxu Meng, Muhan Zhang, Shiai Zhu, Shangguang Wang, Mengwei Xu
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=LCFYj0R2rH
- **中文提要：** 大语言模型频繁更新，使早先版本上训好的 LoRA 权重很快过时。常规做法是在最新模型上从头重训这些权重，既昂贵又耗时，也不利于环境，而且随着模型与下游任务日益多样，这一问题更加突出。
- **关键词：** LoRA, alignment, fine-tuning

### LoRA vs Full Fine-tuning: An Illusion of Equivalence

- **作者：** Reece Shuttleworth, Jacob Andreas, Antonio Torralba, Pratyusha Sharma
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=xp7B8rkh7L
- **中文提要：** 微调是把预训练大语言模型适配到下游任务的关键范式。LoRA 等方法已被证明可以在大幅削减可训练参数的情况下有效微调大语言模型。
- **关键词：** LoRA, fine-tuning

### LoTA-QAF: Lossless Ternary Adaptation for Quantization-Aware Fine-Tuning

- **作者：** Junyu Chen, Junzhuo Li, Zhen Peng, Wenjie Wang, Yuxiang Ren, Long Shi, Xuming Hu
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=9o7oH6DAHB
- **中文提要：** 量化与微调对于把大语言模型部署到资源受限的边缘设备都至关重要。微调量化模型的突出困难之一，是低精度量化权重与高精度适配权重之间的数据类型不匹配。
- **关键词：** LoRA, fine-tuning

### Mechanism Design for LLM Fine-tuning with Multiple Reward Models

- **作者：** Haoran Sun, Yurong Chen, Siwei Wang, Chu Xu, Wei Chen, Xiaotie Deng
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=3JUhkxVlyF
- **中文提要：** 微调大语言模型以聚合多种偏好，已经吸引了相当多的研究关注。随着聚合算法推进，一种潜在的经济情景出现了：向偏好不同的主体提供微调服务。
- **关键词：** reward-model, fine-tuning

### MedMax: Mixed-Modal Instruction Tuning for Training Biomedical Assistants

- **作者：** Hritik Bansal, Daniel Israel, Siyan Zhao, Shufan Li, Tung Nguyen, Aditya Grover
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=mFEkBO25Ra
- **中文提要：** 混合模态生成的进展，为统一的生物医学助手打开了通路，使其能够分析生物医学图像、回答相关复杂问题并生成多模态患者报告。现有数据集却规模偏小、生物医学任务与领域覆盖有限，而且来源狭窄。
- **关键词：** instruction-tuning, fine-tuning

### MetaDefense: Defending Fine-tuning based Jailbreak Attack Before and During Generation

- **作者：** Weisen Jiang, Sinno Pan
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ycMpNwzUAA
- **中文提要：** MetaDefense 是一个新框架，用于防御大语言模型中基于微调的越狱攻击。现有防御机制难以泛化到由未见攻击模板伪装的有害查询，尽管模型在嵌入空间中能够区分这类伪装后的有害查询。
- **关键词：** fine-tuning

### Meta-Learning Objectives for Preference Optimization

- **作者：** Carlo Alfano, Silvia Sapora, Jakob Foerster, Patrick Rebeschini, Yee Whye Teh
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=rbodZQBfd9
- **中文提要：** 在大语言模型对齐上评估偏好优化算法颇具挑战，成本高昂、噪声大，还涉及模型规模和超参数等多种变量。研究表明，在简单得多的基准上也可以获得关于这类算法效力的认识。
- **关键词：** preference-optimization, alignment

### MindGYM: What Matters in Question Synthesis for Thinking-Centric Fine-Tuning?

- **作者：** Zhe Xu, Daoyuan Chen, Zhenqing Ling, Yaliang Li, Ying Shen
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=J6Is1CdvB8
- **中文提要：** 大基础模型难以获得可迁移、结构化的思维能力，尤其当监督来自僵硬模板或众包标注的指令数据时。与先前路线不同，这里关注以思维为中心的数据合成，让模型通过自行生成、受认知引导的数据来演进。
- **关键词：** fine-tuning

### Mitigating Forgetting in LLM Fine-Tuning via Low-Perplexity Token Learning

- **作者：** Chao-Chung Wu, Zhi Rui Tam, Chieh-Yen Lin, Yun-Nung (Vivian) Chen, Shao-Hua Sun, Hung-yi Lee
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=1ktdvp1EYI
- **中文提要：** 在不同领域保持一致的模型表现，是机器学习中的基本挑战。近期工作探索用大语言模型生成的数据做微调，但这种做法对跨领域泛化的影响仍不清楚。
- **关键词：** fine-tuning

### Mitigating Hallucination Through Theory-Consistent Symmetric Multimodal Preference Optimization

- **作者：** Wenqi Liu, Xuemeng Song, Jiaxi Li, Yinwei Wei, Na Zheng, Jianhua Yin, Liqiang Nie
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=tIW29IpCwG
- **中文提要：** DPO 已成为减轻多模态大语言模型幻觉的有效途径。现有方法利用面向视觉的对比目标来增强对视觉输入的注意，从而减少幻觉，但优化目标函数不够严格。
- **关键词：** DPO, preference-optimization, alignment

### Mitigating Reward Over-optimization in Direct Alignment Algorithms with Importance Sampling

- **作者：** Nguyen Phuc, Ngoc-Hieu Nguyen, Duy M. H. Nguyen, Anji Liu, An Mai, Thanh Binh Nguyen, Daniel Sonntag, Khoa D Doan
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ltPRj2nthL
- **中文提要：** 以 DPO 为代表的直接对齐算法，近来成为标准 RLHF 之外、把大语言模型对齐到人类价值的另一选择。它们并不像 RLHF 那样另设代理奖励模型，训练过程中表现仍可能变差，文中将此与过度优化联系起来。
- **关键词：** DPO, RLHF, preference-optimization, reward-model, alignment

### MJ-Bench: Is Your Multimodal Reward Model Really a Good Judge for Text-to-Image Generation?

- **作者：** Zhaorun Chen, Zichen Wen, Yichao Du, Yiyang Zhou, Chenhang Cui, Siwei Han, Jen Weng, Chaoqi Wang, Zhengwei Tong, Leria HUANG, Canyu Chen, Haoqin Tu, Qinghao Ye, Zhihong Zhu, Yuqing Zhang, Jiawei Zhou, Zhuokai Zhao, Rafael Rafailov, Chelsea Finn, Huaxiu Yao
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=woQKlen8EI
- **中文提要：** 文生图模型迅速增多，却常常遇到幻觉、偏见以及产出不安全或低质量结果等问题。要有效处理这些问题，需要依据多模态评判者的反馈，把模型对齐到期望行为。
- **关键词：** reward-model, alignment, fine-tuning

### MokA: Multimodal Low-Rank Adaptation for MLLMs

- **作者：** Yake Wei, Yu Miao, Dongzhan Zhou, Di Hu
- **会议：** NeurIPS 2025 · Main · Oral
- **官方论文页：** https://neurips.cc/virtual/2025/oral/130282
- **中文提要：** 当前大多数高效的多模态微调方法直接从大语言模型借用而来，常常忽视多模态场景的内在差异，甚至影响对全部模态的充分利用。基于经验观察，单模态适配与跨模态适配被视为其中两个必要组成部分。
- **关键词：** LoRA, fine-tuning

### MTRec: Learning to Align with User Preferences via Mental Reward Models

- **作者：** Mengchen Zhao, Yifan Gao, Yaqing Hou, Xiangyang Li, Pengjie Gu, Zhenhua Dong, Ruiming Tang, Yi Cai
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=1mILyDyPDf
- **中文提要：** 由于显式反馈往往获取成本高，推荐模型主要用隐式用户反馈来训练。点击等隐式反馈却并不总是反映用户的真实偏好。
- **关键词：** reward-model

### Multi-agent KTO: Enhancing Strategic Interactions of Large Language Model in Language Game

- **作者：** Rong Ye, Yongxin Zhang, yikai zhang, Haoyu Kuang, peng sun, zhongyu wei
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=WPHpBnKvdq
- **中文提要：** 实现通用人工智能，需要智能体既能做出策略决策，又能进行灵活而有意义的交流。受维特根斯坦语言游戏理论启发，语言智能体被主张通过上下文中的交互来学习，而不必沿用把决策与语言表达分开的多阶段框架。
- **关键词：** KTO

### Multi-Scale Finetuning for Encoder-based Time Series Foundation Models

- **作者：** Zhongzheng Qiao, Chenghao Liu, Yiming Zhang, Ming Jin, Quang Pham, Qingsong Wen, Ponnuthurai Suganthan, Xudong Jiang, Savitha Ramasamy
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=OPOBV0zXu7
- **中文提要：** 时间序列基础模型在预测上展现出可观的零样本表现。如何在特定下游任务上有效微调这些模型，仍是重要但缺少探索的挑战。
- **关键词：** PEFT, fine-tuning

### Neural Networks for Learnable and Scalable Influence Estimation of Instruction Fine-Tuning Data

- **作者：** Ishika Agarwal, Dilek Hakkani-Tur
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=4zea5Bcemp
- **中文提要：** 影响函数能为模型训练提供关键洞见，但现有方法计算成本高、泛化有限。近期用语言模型计算数据影响的各种指标和算法，尤其难以随大模型和大数据集扩展。
- **关键词：** fine-tuning

### Noise-Robustness Through Noise: A Framework combining Asymmetric LoRA with Poisoning MoE

- **作者：** Zhaokun Wang, Jinyu Guo, Jingwen Pu, ChenLingFeng, Hongli Pu, Jie Ou, Libo Qin, Wenhong Tian
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=YtwEVr2ONF
- **中文提要：** 把预训练语言模型适配到下游任务的现有参数高效微调方法，容易受到噪声数据干扰。常规处理噪声的办法，要么依赖费力的数据预处理，要么修改模型结构并容易积累误差。
- **关键词：** LoRA, PEFT, fine-tuning

### Offline RL by Reward-Weighted Fine-Tuning for Conversation Optimization

- **作者：** Subhojyoti Mukherjee, Viet Lai, Raghavendra Addanki, Ryan Rossi, Seunghyun Yoon, Trung Bui, Anup B. Rao, Jayakumar Subramanian, Branislav Kveton
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=WAFD6VYIEa
- **中文提要：** 离线强化学习从事先收集的轨迹与奖励数据集中学习策略。面向大语言模型，有工作提出一种实用的离线强化学习做法。
- **关键词：** DPO, SFT, preference-optimization, fine-tuning

### On Evaluating LLM Alignment by Evaluating LLMs as Judges

- **作者：** Yixin Liu, Pengfei Liu, Arman Cohan
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=OBaK9JSbHk
- **中文提要：** 与人类偏好对齐是评测大语言模型的重要方面，要求模型有用、诚实、安全，并准确遵循人类指令。评估对齐通常要直接考察开放式回复，因而需要人工标注者或强大的语言模型评判者。
- **关键词：** alignment

### On Extending Direct Preference Optimization to Accommodate Ties

- **作者：** Jinghong Chen, Guangyu Yang, Weizhe Lin, Jingbiao Mei, Chenxu Lyu, Bill Byrne
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=1PVdiFbDz0
- **中文提要：** 两种 DPO 变体被推导并加以考察，以便在成对比较中显式建模宣布平局的可能。它们用 Rao 与 Kupper 以及 Davidson 的已知建模扩展替换 DPO 中的 Bradley-Terry 模型，使平局可以作为明确偏好之外的结果并被赋予概率。
- **关键词：** DPO, preference-optimization

### On the Loss of Context Awareness in General Instruction Fine-tuning

- **作者：** Yihan Wang, Andrew Bai, Nanyun Peng, Cho-Jui Hsieh
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=7OdU0LYXLr
- **中文提要：** 预训练大语言模型需要经过后训练，例如在指令与回复对上做 SFT，才能遵循指令。这一过程却可能导致预训练阶段学到的能力被遗忘。
- **关键词：** SFT, instruction-following, post-training, fine-tuning

### OpenVLThinker: Complex Vision-Language Reasoning via Iterative SFT-RL Cycles

- **作者：** Yihe Deng, Hritik Bansal, Fan Yin, Nanyun Peng, Wei Wang, Kai-Wei Chang
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=gfX1nqBKtu
- **中文提要：** OpenVLThinker 是较早开源、能展现复杂思维链推理的大型视觉语言模型之一，并在有挑战的视觉推理任务上取得明显提升。文本推理模型在纯文本任务上已有可观表现，而通过 SFT 将其推理蒸馏到视觉语言模型的常见后果，摘要没有写完。
- **关键词：** SFT, fine-tuning

### OptiScene: LLM-driven Indoor Scene Layout Generation via Scaled Human-aligned Data Synthesis and Multi-Stage Preference Optimization

- **作者：** Yixuan Yang, Zhen Luo, Tongsheng Ding, Junru Lu, Mingqi Gao, Jinyu Yang, Victor Sanchez, Feng Zheng
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ZnrM5RGrgR
- **中文提要：** 自动室内布局生成因其在室内设计、虚拟环境构建和具身智能中的潜力而日益受到关注。现有方法分为两类：借助专有大语言模型服务的提示驱动方法，以及在布局数据上、基于扩散模型训练的学习方法。
- **关键词：** DPO, SFT, preference-optimization, fine-tuning

### Panacea: Mitigating Harmful Fine-tuning for Large Language Models via Post-fine-tuning Perturbation

- **作者：** Yibo Wang, Tiansheng Huang, Li Shen, Huanjin Yao, Haotian Luo, Rui Liu, Naiqiang Tan, Jiaxing Huang, Dacheng Tao
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=sMtiGB2YZT
- **中文提要：** 有害微调攻击给微调服务带来显著安全风险。主流防御试图先对模型加以防护，使随后发生的有害微调攻击不那么有效。
- **关键词：** alignment, fine-tuning

### Parameter Efficient Fine-tuning via Explained Variance Adaptation

- **作者：** Fabian Paischer, Lukas Hauzenberger, Thomas Schmied, Benedikt Alkin, Marc Deisenroth, Sepp Hochreiter
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=movsqor65f
- **中文提要：** 基础模型在大规模数据上预训练，再针对特定下游任务微调。最常见的微调方法是通过 LoRA 更新预训练权重。
- **关键词：** LoRA, PEFT, fine-tuning

### PaZO: Preconditioned Accelerated Zeroth-Order Optimization for Fine-Tuning LLMs

- **作者：** Hanzhen Zhao, Ding Shihong, Cong Fang, Zhouchen Lin
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=b2IU6QOOfo
- **中文提要：** PaZO 是一种带预处理的加速零阶优化算法，用于微调大语言模型。理论上首先论证了零阶优化中预处理的必要性，并证明单独使用零阶随机梯度下降 ZO-SGD 达不到理想收敛速率。
- **关键词：** fine-tuning

### Personalized Image Editing in Text-to-Image Diffusion Models via Collaborative Direct Preference Optimization

- **作者：** Connor Dunlop, Matthew Zheng, Kavana Venkatesh, Pinar Yanardag
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=BBZEcVu1nA
- **中文提要：** 文生图扩散模型在根据文本生成和编辑高保真图像方面进步显著。这些模型本质上仍然是通用的，未能适应单个用户细微的审美偏好。
- **关键词：** DPO, preference-optimization, alignment

### Point-RFT: Improving Multimodal Reasoning with Visually Grounded Reinforcement Finetuning

- **作者：** Minheng Ni, Zhengyuan Yang, Linjie Li, Chung-Ching Lin, Kevin Lin, Wangmeng Zuo, Lijuan Wang
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=wdyOwMISSR
- **中文提要：** 大语言模型借助思维链与强化学习提升了文本推理，但把这条路线延伸到视觉语言任务仍然困难。纯文本思维链容易产生视觉幻觉，也不足以充分融合多模态信息。
- **关键词：** RFT, fine-tuning

### Preference Optimization by Estimating the Ratio of the Data Distribution

- **作者：** Yeongmin Kim, HeeSun Bae, Byeonghu Na, Il-chul Moon
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Iytf59QZzl
- **中文提要：** 直接偏好优化（DPO）被广泛用作对齐大语言模型与人类偏好的简单稳定方法。该研究从似然比估计出发，考察一种广义 DPO 损失，使策略模型去匹配目标策略。
- **关键词：** DPO, preference-optimization, reward-model, alignment

### Preference Optimization on Pareto Sets: On a Theory of Multi-Objective Optimization

- **作者：** Abhishek Roy, Geelon So, Yian Ma
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=4qE0rnS93Z
- **中文提要：** 多目标优化里，单个决策向量必须在众多目标之间取得折中。帕累托最优解对应这种最优权衡：改进任一目标都要以另一目标为代价。
- **关键词：** RLHF, preference-optimization

### PrefixKV: Adaptive Prefix KV Cache is What Vision Instruction-Following Models Need for Efficient Generation

- **作者：** Ao Wang, Hui Chen, Jianchao Tan, Kefeng Zhang, Xunliang Cai, Zijia Lin, Jungong Han, guiguang ding
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=tDG6bY48ch
- **中文提要：** 大型视觉语言模型能在多样的多模态输入上做生成与推理，因而迅速普及。推理阶段显著的计算和显存开销，却严重妨碍了实际场景中的高效部署。
- **关键词：** instruction-following

### Pre-Trained Policy Discriminators are General Reward Models

- **作者：** Shihan Dou, Shichun Liu, Yuming Yang, Yicheng Zou, Yunhua Zhou, Shuhao Xing, Chenhao Huang, Qiming Ge, haijun Lv, Demin Song, Songyang Gao, Chengqi Lyu, Enyu Zhou, Honglin Guo, Zhiheng Xi, Qipeng Guo, Wenwei Zhang, Tao Gui, Qi Zhang, Xipeng Qiu, Xuanjing Huang, Kai Chen
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=efwbxMJ5M6
- **中文提要：** 奖励建模在这里被看成策略判别：量化两个策略的差异以产生奖励，从而把训练策略引向具有期望行为的目标策略。据此提出可扩展的预训练方法 POLAR，用来训练奖励模型加以区分。
- **关键词：** RLHF, RFT, reward-model, fine-tuning

### Principled Fine-tuning of LLMs from User-Edits: A Medley of Preference, Supervision, and Reward

- **作者：** Dipendra Misra, Aldo Pacchiano, Ta-Chung Chi, Ge Gao
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Em9QmNobh0
- **中文提要：** 用户编辑形成的部署数据包含上下文、智能体回复和用户修改，可用来微调大语言模型。写作助手和编程智能体等应用会在使用过程中自然积累这类记录。
- **关键词：** fine-tuning

### Process vs. Outcome Reward: Which is Better for Agentic RAG Reinforcement Learning

- **作者：** Wenlin Zhang, Xiangyang Li, Kuicai Dong, Yichao Wang, Pengyue Jia, Xiaopeng Li, Yingyi Zhang, Derong Xu, Zhaocheng Du, Huifeng Guo, Ruiming Tang, Xiangyu Zhao
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=h3LlJ6Bh4S
- **中文提要：** 检索增强生成通过引入外部知识来增强大语言模型，但传统系统流程静态，难以适应复杂的多步推理。DeepResearch 一类智能体式 RAG 则以动态检索、迭代精炼上下文和自适应流程来应对。
- **关键词：** LLM fine-tuning / post-training

### Progress Reward Model for Reinforcement Learning via Large Language Models

- **作者：** Xiuhui Zhang, Ning Gao, Xingyu Jiang, Yihui Chen, Yuheng Pan, Mohan Zhang, Yue Deng
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=TJhHb6CscW
- **中文提要：** 传统强化学习难以处理奖励稀疏的长期任务。近期进展借助大语言模型的世界知识来做任务规划并生成奖励，从而增强强化学习。
- **关键词：** PRM, reward-model

### Provable Meta-Learning with Low-Rank Adaptations

- **作者：** Jacob Block, Sundararajan Srinivasan, Liam Collins, Aryan Mokhtari, Sanjay Shakkottai
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=QUN6uidabr
- **中文提要：** 基础模型的优势在于能学到表达力很强、可适配广泛任务的表征。这些预训练模型要在下游真正可用，仍需要额外的训练阶段。
- **关键词：** LoRA, PEFT, fine-tuning

### Provably Efficient Online RLHF with One-Pass Reward Modeling

- **作者：** Long-Fei Li, Yu-Yang Qian, Peng Zhao, Zhi-Hua Zhou
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=41mBrhy6U4
- **中文提要：** 基于人类反馈的强化学习（RLHF）在对齐大语言模型与人类偏好方面成效显著。传统做法依赖固定数据集，覆盖范围常常有限。
- **关键词：** RLHF, reward-model, alignment

### Proximalized Preference Optimization for Diverse Feedback Types: A Decomposed Perspective on DPO

- **作者：** Kaiyang Guo, Yinchuan Li, Zhitang Chen
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ZDbhQrgwoT
- **中文提要：** 直接对齐方法通常对比偏好回答与非偏好回答的似然来训练大语言模型。这能匹配相对偏好，却会压低示例回答的绝对似然。
- **关键词：** DPO, preference-optimization, reward-model, alignment

### PT-MoE: An Efficient Finetuning Framework for Integrating Mixture-of-Experts into Prompt Tuning

- **作者：** Zongqian Li, Yixuan Su, Nigel Collier
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ZSAWYtIwGg
- **中文提要：** 参数高效微调（PEFT）有望适配大语言模型，但单独加入矩阵分解或混合专家（MoE）时，跨任务表现反而下降。分解虽减少参数，仍能改善特定领域的结果；MoE 则会增加参数量。
- **关键词：** LoRA, PEFT, fine-tuning

### QoQ-Med: Building Multimodal Clinical Foundation Models with Domain-Aware GRPO Training

- **作者：** David Dai, Peilin Chen, Chanakya Ekbote, Paul Liang
- **会议：** NeurIPS 2025 · Main · Oral
- **官方论文页：** https://openreview.net/forum?id=ZwCVFBFUFb
- **中文提要：** 临床决策经常要在异构数据上推理，现有多模态语言模型却多以视觉为中心，难以跨临床专科泛化。开放的通才临床基础模型 QoQ-Med 被用来联合推理医学影像、时间序列信号和文本报告。
- **关键词：** GRPO, instruction-tuning

### $Q\sharp$: Provably Optimal Distributional RL for LLM Post-Training

- **作者：** Jin Zhou, Kaiwen Wang, Jonathan Chang, Zhaolin Gao, Nathan Kallus, Kilian Weinberger, Kianté Brantley, Wen Sun
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=MrRdupucYb
- **中文提要：** 对齐和推理都依赖强化学习后训练，但 PPO、DPO 这类基于策略的方法未必能纠正预训练遗留的捷径。Q♯ 作为基于价值的算法，在 KL 正则化的强化学习中用最优正则化 Q 函数引导参考策略。
- **关键词：** DPO, post-training, alignment

### Quadratic Coreset Selection: Certifying and Reconciling Sequence and Token Mining for Efficient Instruction Tuning

- **作者：** Ziliang Chen, Yongsen Zheng, Zhao-Rong Lai, Zhanfu Yang, Cuixi Li, Yang Liu, Liang Lin
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=btZm6DUaDO
- **中文提要：** 指令微调在大语言模型后训练中表现出很高的数据效率。对效率的追求却主要停在序列级筛选，容易忽略关键词元的细微作用，以及词元噪声和偏见所带来的风险。
- **关键词：** instruction-tuning, instruction-following, post-training

### R1-ShareVL: Incentivizing Reasoning Capabilities of Multimodal Large Language Models via Share-GRPO

- **作者：** Huanjin Yao, Qixiang Yin, Jingyi Zhang, Min Yang, Yibo Wang, Wenhao Wu, Fei Su, Li Shen, Minghui Qiu, Dacheng Tao, Jiaxing Huang
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=kMPII4XbKC
- **中文提要：** 为激发多模态大语言模型的推理能力，并缓解强化学习中的稀疏奖励与优势消失，提出了 Share-GRPO。该方法在扩展后的问题空间里探索并共享多样的推理轨迹。
- **关键词：** GRPO

### Ranking-based Preference Optimization for Diffusion Models from Implicit User Feedback

- **作者：** Yi-Lun Wu, Bo-Kai Ruan, Chiang Tseng, Hong-Han Shuai
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=G9TkX2sy8Z
- **中文提要：** 直接偏好优化（DPO）用成对比较来对齐文生图扩散模型与人类偏好，并因避开 REINFORCE 而提高训练稳定性。由于 sigmoid 的非线性以及多样性受限，准确估计图像概率仍然困难。
- **关键词：** DPO, preference-optimization, reward-model, alignment

### Ravan: Multi-Head Low-Rank Adaptation for Federated Fine-Tuning

- **作者：** Arian Raje, Baris Askin, Divyansh Jhunjhunwala, Gauri Joshi
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=gyn4n8oC9B
- **中文提要：** 大语言模型尚未有效利用端侧设备上的大量数据，联邦学习则允许在不把私有数据传到云端的前提下协同微调。为满足端侧的计算与通信约束，近期联邦微调工作采用低秩适配。
- **关键词：** LoRA, PEFT, fine-tuning

### Reason-RFT: Reinforcement Fine-Tuning for Visual Reasoning of Vision Language Models

- **作者：** Huajie Tan, Yuheng Ji, Xiaoshuai Hao, Xiansheng Chen, Pengwei Wang, Zhongyuan Wang, Shanghang Zhang
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=NdScoAix25
- **中文提要：** 视觉推理对理解复杂多模态数据、推进领域应用和通用人工智能都很关键。现有方法依靠精心标注的数据，用思维链监督微调来增强视觉语言模型。
- **关键词：** GRPO, RFT, SFT, fine-tuning

### RefLoRA: Refactored Low-Rank Adaptation for Efficient Fine-Tuning of Large Models

- **作者：** Yilang Zhang, Bingcong Li, Georgios Giannakis
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=zefDc9oi5T
- **中文提要：** 低秩适配（LoRA）只更新预训练权重矩阵的低维子空间，从而降低大模型微调的计算和显存开销。低秩分解并不唯一，使权重更新不一致且不均衡，导致收敛变差并带来明显的性能下降。
- **关键词：** LoRA, fine-tuning

### Reinforcement Learning Finetunes Small Subnetworks in Large Language Models

- **作者：** Sagnik Mukherjee, Lifan Yuan, Dilek Hakkani-Tur, Hao Peng
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=0NdS4xCngO
- **中文提要：** 强化学习能大幅改善大语言模型的下游任务表现及其与人类价值的对齐。这些增益只来自更新一个很小的子网络，其余参数实际上保持不变。
- **关键词：** GRPO, DPO, alignment, fine-tuning

### Reinforcement Learning Meets Masked Generative Models: Mask-GRPO for Text-to-Image Generation

- **作者：** Yifu Luo, Xinhao Hu, Keyu Fan, Haoyuan Sun, Zeyu Chen, Bo Xia, Tiantian Zhang, Yongzhe Chang, Xueqian Wang
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=C2QMbkp7iq
- **中文提要：** 文生图领域对强化学习的关注正在上升，但多数现有方法只针对扩散模型或自回归模型。掩码生成模型作为另一条重要路线，仍被忽略。
- **关键词：** GRPO, preference-optimization, alignment

### RePIC: Reinforced Post-Training for Personalizing Multi-Modal Language Models

- **作者：** Yeongtak Oh, Dohyun Chung, Juhyeon Shin, Sangha Park, Johan Barthelemy, Jisoo Mok, Sungroh Yoon
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=DG0F1cdjN7
- **中文提要：** 近来的多模态大语言模型即使在高质量描述上训练，也常常难以生成个性化的图像说明。基于后训练的个性化方法里，这种局限仍然存在。
- **关键词：** SFT, post-training, fine-tuning

### ResponseRank: Data-Efficient Reward Modeling through Preference Strength Learning

- **作者：** Timo Kaufmann, Yannick Metz, Daniel Keim, Eyke Hüllermeier
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=3JlBQRvod7
- **中文提要：** 用于 RLHF 的二元选择通常只传达偏好的方向。一个人可以在苹果与橙子、香蕉与葡萄之间做出选择，但哪一种偏好更强并不由此可知。
- **关键词：** RLHF, reward-model

### Rethinking Fine-Tuning when Scaling Test-Time Compute: Limiting Confidence Improves Mathematical Reasoning

- **作者：** Feng Chen, Allan Raventós, Nan Cheng, Surya Ganguli, Shaul Druckmann
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=jvVQeSMeGM
- **中文提要：** 扩大测试时计算使大语言模型在数学推理、代码生成等复杂任务上表现强劲。随之而来的问题是：若之后要在给定的测试时计算策略和预算下优化表现，训练本身该如何调整。
- **关键词：** fine-tuning

### RidgeLoRA: Matrix Ridge Enhanced Low-Rank Adaptation of Large Language Models

- **作者：** Junda Zhu, Jun Ai, Yujun Li, Yichun Yin, Yasheng Wang, Lifeng Shang, Qun Liu
- **会议：** NeurIPS 2025 · Main · Spotlight
- **官方论文页：** https://openreview.net/forum?id=0RF80tUWuv
- **中文提要：** 作为先进的参数高效微调（PEFT）方法，LoRA 借助可训练低秩矩阵以更低计算成本优化模型。低秩特性却容易削弱表示能力，导致性能不够理想。
- **关键词：** LoRA, PEFT, fine-tuning

### Risk-aware Direct Preference Optimization under Nested Risk Measure

- **作者：** Lijun Zhang, Lin Li, Yajie Qi, Huizhong Song, Yaodong Yang, Jun Wang, Wei Wei
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=V4oTkK7cQz
- **中文提要：** 微调预训练大语言模型以对齐人类价值与意图时，最大化估计奖励可能带来更好表现，也会因偏离参考模型的预期行为而引入风险。多数现有方法用 KL 散度约束训练模型与参考模型之间的偏离。
- **关键词：** DPO, preference-optimization, alignment, fine-tuning

### RLVR-World: Training World Models with Reinforcement Learning

- **作者：** Jialong Wu, Shaofeng Yin, Ningya Feng, Mingsheng Long
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=jpiSagi8aV
- **中文提要：** 世界模型根据动作预测状态转移，并在多种模态上不断发展。最大似然估计等标准训练目标常常与任务目标错位，例如准确率或感知质量这类转移预测指标。
- **关键词：** RLVR, post-training

### Robust Federated Finetuning of LLMs via Alternating Optimization of LoRA

- **作者：** Shuangyi Chen, Yuanxin Guo, Yue Ju, Hardik Dalal, Zhongwen Zhu, Ashish Khisti
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=e8DrPuJekZ
- **中文提要：** LoRA 等参数高效微调（PEFT）通过降低计算和通信成本来优化联邦训练。联邦框架 RoLoRA 用交替优化来微调 LoRA 适配器。
- **关键词：** LoRA, PEFT, fine-tuning

### Robust LLM Alignment via Distributionally Robust Direct Preference Optimization

- **作者：** Zaiyan Xu, Sushil Vemuri, Kishan Panaganti, Dileep Kalathil, Rahul Jain, Deepak Ramachandran
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=D19hc2XPeZ
- **中文提要：** 把大语言模型对齐到人类偏好时，分布偏移是一大挑战。对齐算法依赖静态偏好数据集，并假定这些数据能准确代表真实世界中的用户偏好。
- **关键词：** DPO, preference-optimization, alignment

### RoFt-Mol: Benchmarking Robust Fine-tuning with Molecular Graph Foundation Models

- **作者：** Shikun Liu, Deyu Zou, Nima Shoghi, Victor Fung, Kai Liu, Pan Li
- **会议：** NeurIPS 2025 · Main · Spotlight
- **官方论文页：** https://openreview.net/forum?id=S8EnwROlYj
- **中文提要：** 在基础模型时代，把预训练模型微调到具体下游任务变得至关重要。这也要求稳健的微调方法，以应对模型过拟合和稀疏标注。
- **关键词：** fine-tuning

### Safe RLHF-V: Safe Reinforcement Learning from Multi-modal Human Feedback

- **作者：** Jiaming Ji, Xinyu Chen, Rui Pan, Han Zhu, Jiahao Li, Donghai Hong, Boyuan Chen, Jiayi Zhou, Kaile Wang, Juntao Dai, Chi-Min Chan, Sirui Han, Yike Guo, Yaodong Yang
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=OIH3T5ZPBW
- **中文提要：** 多模态大语言模型是构建通用人工智能助手的关键，但带来的安全风险也在增加。如何做安全对齐、防止不良行为，成为需要面对的问题。
- **关键词：** RLHF, alignment, fine-tuning

### Scalable Valuation of Human Feedback through Provably Robust Model Alignment

- **作者：** Masahiro Fujisawa, Masaki Adachi, Michael A Osborne
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=EaTRrceoU9
- **中文提要：** 尽管让语言模型对齐人类偏好很重要，众包反馈却常常有噪声，例如会偏好不那么理想的回答。真正稳健的对齐目标应在严重标签噪声下仍得到相同的模型参数，这一性质称为 redescending。
- **关键词：** DPO, RLHF, alignment

### SCAN: Self-Denoising Monte Carlo Annotation for Robust Process Reward Learning

- **作者：** Yuyang Ding, Xinyu Shi, Juntao Li, Xiaobo Liang, Zhaopeng Tu, Min Zhang
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ifsyZYYDNs
- **中文提要：** 过程奖励模型给出细粒度的步骤级评价，有助于大语言模型进行更深的推理，在数学推理等复杂任务中行之有效。构建这类模型却受制于人工标注的高成本与有限可扩展性。
- **关键词：** PRM, reward-model

### SEEA-R1: Tree-Structured Reinforcement Fine-Tuning for Self-Evolving Embodied Agents

- **作者：** Wanxin Tian, Shijie Zhang, Kevin Zhang, Xiaowei Chi, Chun-Kai Fan, Junyu Lu, Yulin Luo, Qiang Zhou, Yiming Zhao, Ning Liu, Siyu Lin, Zhiyuan Qin, Xiaozhu Ju, Shanghang Zhang, Jian Tang
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=dAwKePZvcN
- **中文提要：** 自我演化，即智能体自主改进推理与行为的能力，对具身领域中长程、真实世界的任务必不可少。强化微调在增强大语言模型推理上已表现强劲，但要借多模态交互实现自我演化的具身智能，其潜力仍基本未被探索。
- **关键词：** GRPO, RFT, reward-model, fine-tuning

### Self-alignment of Large Video Language Models with Refined Regularized Preference Optimization

- **作者：** Pritam Sarkar, Ali Etemad
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=fgfftCWPrn
- **中文提要：** 大型视频语言模型在细粒度时间理解上仍然吃力，还会产生幻觉，并在简单的视频问答里出错，从而妨碍安全可靠的部署。针对这些不足，提出了一种自我对齐框架。
- **关键词：** DPO, preference-optimization, alignment

### Self-Supervised Direct Preference Optimization for Text-to-Image Diffusion Models

- **作者：** Liang Peng, Boxi Wu, Haoran Cheng, Yibo Zhao, Xiaofei He
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=COifgrjzXR
- **中文提要：** 直接偏好优化（DPO）能有效把生成模型对齐到人类偏好，并已用于微调文生图扩散模型。落地却受阻于费力的流程：先产出大量候选图像，再由人工做两两排序。
- **关键词：** DPO, preference-optimization, alignment

### S-GRPO: Early Exit via Reinforcement Learning in Reasoning Models

- **作者：** Muzhi Dai, Chenxu Yang, Qingyi Si
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=wNMK5o0Vfg
- **中文提要：** 测试时扩展成为大语言模型社区的活跃方向，先进后训练越来越强调拉长思维链，以使推理能力接近强推理模型。近期研究却发现，推理模型的思维链中持续存在过多的思考冗余。
- **关键词：** GRPO, post-training

### Shape it Up! Restoring LLM Safety during Finetuning

- **作者：** ShengYun Peng, Pin-Yu Chen, Jianfeng Chi, Seongmin Lee, Duen Horng Chau
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=PAIVwOaAnq
- **中文提要：** 微调让大语言模型可以按用户定制，但会引入关键安全风险：少量有害样本就可能破坏已有的安全对齐。常见缓解是对判定为安全的样本做更强更新，同时降权或排除被标为不安全的样本。
- **关键词：** alignment, fine-tuning

### Sharp Analysis for KL-Regularized Contextual Bandits and RLHF

- **作者：** Heyang Zhao, Chenlu Ye, Quanquan Gu, Tong Zhang
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=TE63KPCXWt
- **中文提要：** 反向 KL 正则已成为强化学习与 RLHF 中加强策略优化的主要技术，迫使学到的策略靠近参考策略。其有效性已在多种实际场景中得到经验证实。
- **关键词：** RLHF

### Sheetpedia: A 300K-Spreadsheet Corpus for Spreadsheet Intelligence and LLM Fine-Tuning

- **作者：** Zailong Tian, Zhuoheng Han, Houfeng Wang, Lizi Liao
- **会议：** NeurIPS 2025 · Main · Spotlight
- **官方论文页：** https://openreview.net/forum?id=4vLYwlA3X5
- **中文提要：** 电子表格广泛用于数据分析与报表，复杂结构和公式逻辑却给人工智能系统带来显著挑战。Sheetpedia 是汇编自企业邮件存档和在线论坛的大规模多样电子表格语料，面向表格智能与大语言模型微调。
- **关键词：** fine-tuning

### Simplicity Prevails: Rethinking Negative Preference Optimization for LLM Unlearning

- **作者：** Chongyu Fan, Jiancheng Liu, Licong Lin, Jinghan Jia, Ruiqi Zhang, Song Mei, Sijia Liu
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=JbvSQm5h1l
- **中文提要：** 大语言模型遗忘旨在去掉版权或有害内容等不想要的数据影响，同时保住模型效用。相关需求在增加，但仍缺少有技术依据的优化框架。
- **关键词：** preference-optimization

### Skrull: Towards Efficient Long Context Fine-tuning through Dynamic Data Scheduling

- **作者：** Hongtao Xu, Wenting Shen, Yuanxin Wei, Ang Wang, Guo Runfan, Tianxing Wang, Yong Li, Mingzhen Li, Weile Jia
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=WBEknRZBpT
- **中文提要：** 长上下文监督微调（Long-SFT）对提升大语言模型在长上下文任务上的表现至关重要。为使模型平稳适应，训练通常使用同时包含长序列和短序列的混合数据。
- **关键词：** SFT, fine-tuning

### S'MoRE: Structural Mixture of Residual Experts for Parameter-Efficient LLM Fine-tuning

- **作者：** Hanqing Zeng, Yinglong Xia, Zhuokai Zhao, Chuan Jiang, Qiang Zhang, Jiayi Liu, Qunshu Zhang, Lizhu Zhang, Xiangjun Fan, Benyu Zhang
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=LbNL8xGai2
- **中文提要：** 微调预训练大语言模型需要同时平衡参数效率与模型容量。LoRA 一类低秩适配效率高但缺乏灵活性，混合专家（MoE）能增强容量，代价是更多且利用不足的参数。
- **关键词：** LoRA, PEFT, fine-tuning

### SoPo: Text-to-Motion Generation Using Semi-Online Preference Optimization

- **作者：** Xiaofeng Tan, Hongsong Wang, Xin Geng, Pan Zhou
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=IjDlvzBSVp
- **中文提要：** 文本生成动作对推动创意产业很重要，但要产出一致、逼真的动作往往很难。关注点在于微调文生动作模型，使其稳定偏向高质量、符合人类偏好的动作，这一关键问题仍少有探索。
- **关键词：** DPO, preference-optimization, alignment, fine-tuning

### SPACE: Noise Contrastive Estimation Stabilizes Self-Play Fine-Tuning for Large Language Models

- **作者：** Yibo Wang, Guangda Huzhang, Qingguo Chen, Zhao Xu, Weihua Luo, Kaifu Zhang, Lijun Zhang
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=P4xaLYXBRe
- **中文提要：** 自对弈微调在真实数据有限时，展现出把大语言模型适配到下游任务的潜力。基本做法是用真实样本和模型自身生成的合成样本迭代改进模型。
- **关键词：** SFT, fine-tuning

### Sparse MeZO: Less Parameters for Better Performance in Zeroth-Order LLM Fine-Tuning

- **作者：** Yong Liu, Zirui Zhu, Chaoyu Gong, Minhao Cheng, Cho-Jui Hsieh, Yang You
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Tjw0ACu3NL
- **中文提要：** 针对特定任务微调大语言模型往往效果突出，但基于梯度的反向传播造成显存低效。内存高效的零阶优化器 MeZO 在训练中只做前向传播，因而更节省显存。
- **关键词：** fine-tuning

### Spend Wisely: Maximizing Post-Training Gains in Iterative Synthetic Data Bootstrapping

- **作者：** Pu Yang, Yunzhen Feng, Ziyuan Chen, Yuhang Wu, Zhuoyuan Li
- **会议：** NeurIPS 2025 · Main · Spotlight
- **官方论文页：** https://openreview.net/forum?id=aqpHTPC63N
- **中文提要：** 现代基础模型的后训练常做迭代自举：模型生成合成数据，外部验证器滤除低质量样本，再用高质量子集继续微调。多轮之后性能提升，于是需要考虑生成与训练的总预算应如何在各轮之间分配。
- **关键词：** post-training, fine-tuning

### Stackelberg Self-Annotation: A Robust Approach to Data-Efficient LLM Alignment

- **作者：** Chu Xu, Zhixin Zhang, Tianyu Jia, Yujie Jin
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=1YprrVfIp8
- **中文提要：** 对齐大语言模型与人类偏好通常需要海量精心整理的数据，既昂贵又容易出现标注噪声。SGPO 把对齐建模为双人施塔克尔伯格博弈，策略作为领导者，最坏情况的偏好分布作为跟随者。
- **关键词：** preference-optimization, alignment

### Steering Information Utility in Key-Value Memory for Language Model Post-Training

- **作者：** Chunyuan Deng, Ruidi Chang, Hanjie Chen
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=3rRzYrpO70
- **中文提要：** 语言模型的进展正使后训练变得愈发重要。监督微调（SFT）这类后训练并不能保证预训练阶段获得的知识被有效使用。
- **关键词：** SFT, post-training, fine-tuning

### StelLA: Subspace Learning in Low-rank Adaptation using Stiefel Manifold

- **作者：** Zhizhong Li, Sina Sajadmanesh, Jingtao Li, Lingjuan Lyu
- **会议：** NeurIPS 2025 · Main · Spotlight
- **官方论文页：** https://openreview.net/forum?id=55Lv1unlUL
- **中文提要：** 低秩适配（LoRA）作为参数高效技术，已被广泛用于微调大规模预训练模型。它仍落后于全量微调，部分原因是对低秩流形背后几何结构的利用不足。
- **关键词：** LoRA, PEFT, fine-tuning

### Stop Summation: Min-Form Credit Assignment Is All Process Reward Model Needs for Reasoning

- **作者：** Jie Cheng, Gang Xiong, Ruixi Qiao, Lijun Li, Chao Guo, Junle Wang, Yisheng Lv, Fei-Yue Wang
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=3Sxby0hH1q
- **中文提要：** 过程奖励模型已被证明能支持大语言模型在困难推理任务上的测试时扩展。由它引起的奖励黑客现象，却妨碍了在强化微调中的成功应用。
- **关键词：** RFT, PRM, reward-model, fine-tuning

### Strategyproof Reinforcement Learning from Human Feedback

- **作者：** Thomas Kleine Buening, Jiarui Gan, Debmalya Mandal, Marta Kwiatkowska
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=5WkXhmvvgk
- **中文提要：** 这里考察的 RLHF 设定中，多名标注者可能策略性误报反馈，以便把学到的策略导向自己的偏好。现有算法包括近期的多元方法都不防策略操纵，即使单个策略性标注者也可能造成与社会福利的严重错位。
- **关键词：** RLHF, alignment

### Synergy over Discrepancy: A Partition-Based Approach to Multi-Domain LLM Fine-Tuning

- **作者：** Hua Ye, Siyuan Chen, Haoliang Zhang, Weihao Luo, Yanbin Li, Xuan Zhang
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=2jzGEudVdS
- **中文提要：** 大语言模型泛化能力突出，但在多个异质领域上适配时，仍会受到领域间干扰。一种基于划分的多阶段微调框架用来利用领域间协同，并尽量减少负迁移。
- **关键词：** fine-tuning

### Task-Specific Data Selection for Instruction Tuning via Monosemantic Neuronal Activations

- **作者：** Da Ma, Gonghu Shang, Zhi Chen, Libo Qin, Yijie LUO, Hongshen Xu, Lei Pan, Shuai Fan, Kai Yu, Lu Chen
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=9AHkbALT2t
- **中文提要：** 要让大语言模型在特定目标任务上表现强劲，面向多样指令的微调仍然不够。瓶颈在于选出最相关的数据，从而尽量提高该任务上的表现。
- **关键词：** instruction-tuning, alignment

### Temporal Representation Alignment: Successor Features Enable Emergent Compositionality in Robot Instruction Following

- **作者：** Vivek Myers, Bill Zheng, Anca Dragan, Kuan Fang, Sergey Levine
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=yaS3JWQRQ6
- **中文提要：** 有效的任务表征应当便于组合：学会多种基础任务后，智能体只需组合各步骤的表征，就能完成由多步构成的复合任务。想法本身直观，但如何自动学到支持这种组合性的表征尚不明确。
- **关键词：** instruction-following, alignment

### TempSamp-R1: Effective Temporal Sampling with Reinforcement Fine-Tuning for Video LLMs

- **作者：** Yunheng Li, Jing Cheng, Shaoyong Jia, Hangyi Kuang, Shaohui Jiao, Qibin Hou, Ming-Ming Cheng
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=pebVFFVs2R
- **中文提要：** 一种新的强化微调框架被用来更有效地把多模态大语言模型适配到视频时间定位。文中指出，GRPO 等现有强化学习方法在策略更新时依赖同策略采样。
- **关键词：** GRPO, RFT, fine-tuning

### The Best Instruction-Tuning Data are Those That Fit

- **作者：** Dylan Zhang, Qirun Dai, Hao Peng
- **会议：** NeurIPS 2025 · Main · Spotlight
- **官方论文页：** https://openreview.net/forum?id=4jFSekBaDT
- **中文提要：** 高质量的监督微调（SFT）数据对释放预训练大语言模型的能力必不可少。指令通常配上来自人类标注者或其他语言模型的回答，这些回答往往处于待微调目标模型的分布之外。
- **关键词：** SFT, instruction-tuning, post-training, alignment, fine-tuning

### The First Few Tokens Are All You Need: An Efficient and Effective Unsupervised Prefix Fine-Tuning Method for Reasoning Models

- **作者：** Ke Ji, Jiahao Xu, Tian Liang, Qiuzhi Liu, Zhiwei He, Xiaoyuan Liu, Xingyu Chen, Junying Chen, Benyou Wang, Zhaopeng Tu, Haitao Mi, Dong Yu
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=1SCMFCGliM
- **中文提要：** 提升大语言模型的推理能力，通常需要带标签数据的监督微调，或计算代价很高的采样。无监督前缀微调（UPFT）利用前缀自一致性，即不同解题轨迹共享的初始推理步骤，来提高推理效率。
- **关键词：** SFT, fine-tuning

### The Primacy of Magnitude in Low-Rank Adaptation

- **作者：** Zicheng Zhang, Haoran Li, Yifeng Zhang, Guoqiang Gong, Jiaxing Wang, Pengzhang Liu, Qixia Jiang, Junxing Hu
- **会议：** NeurIPS 2025 · Main · Spotlight
- **官方论文页：** https://openreview.net/forum?id=s4LnWgjacg
- **中文提要：** 低秩适配（LoRA）为大模型调节提供了参数高效的范式。近期的谱初始化相对朴素的“噪声与零”方案能改善收敛和性能，但额外的计算与存储开销又削弱了效率。
- **关键词：** LoRA, PEFT

### Think-RM: Enabling Long-Horizon Reasoning in Generative Reward Models

- **作者：** Ilgee Hong, Changlong Yu, Liang Qiu, Weixiang Yan, Zhenghao Xu, Haoming Jiang, Qingru Zhang, Qin Lu, Xin Liu, Chao Zhang, Tuo Zhao
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=UfQAFbP6xq
- **中文提要：** RLHF 已成为让大语言模型对齐人类偏好的重要后训练范式，其核心难点是构造准确的奖励信号。传统 Bradley-Terry 奖励模型对数据规模和覆盖很敏感，也容易遭受奖励黑客攻击。
- **关键词：** RLHF, SFT, reward-model, post-training, alignment, fine-tuning

### Time-R1: Post-Training Large Vision Language Model for Temporal Video Grounding

- **作者：** Ye Wang, Ziheng Wang, Boshen Xu, Yang Du, Kejun Lin, Zihan Xiao, Zihao Yue, Jianzhong Ju, Liang Zhang, Dingyi Yang, Xiangnan Fang, Zewen He, Zhenbo Luo, Wenxuan Wang, Junqi Lin, Jian Luan, Qin Jin
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=gJ05Gm5VxQ
- **中文提要：** 时序视频定位要求根据语言查询找出对应视频片段，是长视频理解中的核心问题。近期大视觉语言模型虽通过监督微调 SFT 初步尝试这项任务，泛化能力仍然有限。
- **关键词：** SFT, post-training, fine-tuning

### To Think or Not To Think: A Study of Thinking in Rule-Based Visual Reinforcement Fine-Tuning

- **作者：** Ming Li, Jike Zhong, Shitian Zhao, Yuxiang Lai, Haoquan Zhang, Wang Bill Zhu, Kaipeng Zhang
- **会议：** NeurIPS 2025 · Main · Spotlight
- **官方论文页：** https://openreview.net/forum?id=YexxvBGwQM
- **中文提要：** 该研究考察显式思考过程在多模态大语言模型的规则强化微调 RFT 中扮演什么角色。作者先把 Thinking-RFT 扩展到图像分类，并用可验证奖励进行微调。
- **关键词：** RFT, fine-tuning

### Towards Unified Multimodal Interleaved Generation via Group Relative Policy Optimization

- **作者：** Ming Nie, Chunwei Wang, Jianhua Han, Hang Xu, Li Zhang
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=lUHwUuQGdV
- **中文提要：** 统一视觉语言模型在多模态理解与生成上进展明显，却大多难以产出图文交错结果，而这正是视觉叙事和逐步视觉推理所需要的能力。作者提出基于强化学习的后训练策略，希望在现有统一模型上解锁这一能力。
- **关键词：** GRPO, post-training, alignment

### Tracing the Representation Geometry of Language Models from Pretraining to Post-training

- **作者：** Melody Li, Kumar Krishna Agrawal, Arna Ghosh, Komal Teru, Adam Santoro, Guillaume Lajoie, Blake Richards
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=FDruZlKWUb
- **中文提要：** 损失这类常规训练指标解释不了大语言模型复杂能力如何出现。作者从谱的角度考察预训练到后训练过程中已学表示的几何，测量有效秩 RankMe 与特征谱衰减 αReQ。
- **关键词：** DPO, RLVR, SFT, post-training, alignment

### Trajectory Balance with Asynchrony: Decoupling Exploration and Learning for Fast, Scalable LLM Post-Training

- **作者：** Brian Bartoldson, Siddarth Venkatraman, James Diffenderfer, Moksh Jain, Tal Ben-Nun, Seanie Lee, Minsu Kim, Johan Obando Ceron, Yoshua Bengio, Bhavya Kailkhura
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=VwPt1WDQNB
- **中文提要：** 强化学习是大语言模型后训练的关键组成部分。用于后训练的同策略算法并不天然稳健于经验回放中多样化的内容，而这些内容可以由与训练并行的异步异策略执行器高效填充。
- **关键词：** GRPO, DPO, post-training

### Transformer Copilot: Learning from The Mistake Log in LLM Fine-tuning

- **作者：** Jiaru Zou, Yikun Ban, Zihao Li, Yunzhe Qi, Ruizhong Qiu, Ling Yang, Jingrui He
- **会议：** NeurIPS 2025 · Main · Spotlight
- **官方论文页：** https://openreview.net/forum?id=MRvxlTlkNQ
- **中文提要：** 大语言模型适配下游任务时，通常在领域数据上做监督微调，标准做法专注于最小化生成损失来优化参数。这里更进一步，保留并利用模型自身的学习信号，类似于学习者回顾过去的错误来改进后续表现。
- **关键词：** SFT, fine-tuning

### Triplets Better Than Pairs: Towards Stable and Effective Self-Play Fine-Tuning for LLMs

- **作者：** Yibo Wang, Hai-Long Sun, Guangda Huzhang, Qingguo Chen, Zhao Xu, Weihua Luo, Kaifu Zhang, Lijun Zhang
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Hk4cCTukeI
- **中文提要：** 自博弈微调 SPIN 让模型反复生成合成回答，以便在专家标注稀缺时把大语言模型适配到下游应用。它优化的是手头标注回答相对合成回答的当前奖励优势，这种优势可能随迭代逐渐消失，从而引发不稳定。
- **关键词：** SFT, fine-tuning

### T-SHIRT: Token-Selective Hierarchical Data Selection for Instruction Tuning

- **作者：** Yanjun Fu, Faisal Hamman, Sanghamitra Dutta
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=oN5YVZ9JeF
- **中文提要：** 指令微调对大语言模型有效遵循用户指令必不可少。为提高训练效率并降低数据冗余，近期工作使用基于大语言模型的评分函数，例如指令遵循难度（IFD），选取分数高于阈值的高质量指令数据。
- **关键词：** instruction-tuning, instruction-following

### Turning the Tables: Enabling Backward Transfer via Causal-Aware LoRA in Continual Learning

- **作者：** Chaoyang Li, Runze Ye, Jianyang Qin, Jinhao Cui, Lingzhi Wang, Ning Hu, Qing Liao
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=bdGsKis3Ew
- **中文提要：** 现有参数高效微调 PEFT 在持续学习中表现较好。不过多数基于 PEFT 的方法把重心放在限制新任务对旧任务模型的改动，以此来缓解灾难性遗忘。
- **关键词：** LoRA, PEFT, fine-tuning

### UFT: Unifying Supervised and Reinforcement Fine-Tuning

- **作者：** Mingyang Liu, Gabriele Farina, Asuman Ozdaglar
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=usOkGv1S7M
- **中文提要：** 后训练对增强大语言模型的推理能力很重要。其主要方法可以分成监督微调 SFT 与强化微调 RFT 两类。
- **关键词：** RFT, SFT, post-training, fine-tuning

### Uncertainty-aware Preference Alignment for Diffusion Policies

- **作者：** Runqing Miao, Sheng Xu, Runyi Zhao, Wai Kin (Victor) Chan, Guiliang Liu
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=oG1CIBWQ77
- **中文提要：** 扩散策略在决策任务上已展现出有希望的表现。要让这些策略对齐人类偏好，常见做法是把基于偏好的强化学习 PbRL 纳入策略调优。
- **关键词：** preference-optimization, alignment

### Understanding Data Influence in Reinforcement Finetuning

- **作者：** Haoru Tan, Xiuzhe Wu, Sitong Wu, Shaofeng Zhang, Yanfeng Chen, Xingwu Sun, Jeanne Shen, Xiaojuan Qi
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=mjhCFB3HLQ
- **中文提要：** 强化微调 RFT 对提升大语言模型的推理与泛化很关键，但成败很大程度取决于训练数据质量。数据选择在监督学习中已被广泛研究，在强化学习、尤其是 RFT 阶段仍很少被探讨。
- **关键词：** RFT, alignment, fine-tuning

### Unified Multimodal Chain-of-Thought Reward Model through Reinforcement Fine-Tuning

- **作者：** Yibin Wang, li zhimin, Yuhang Zang, Chunyu Wang, Qinglin Lu, Cheng Jin, Jiaqi Wang
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=S43003uMGq
- **中文提要：** 多模态奖励模型的进展，使其有望为视觉模型对齐人类偏好提供奖励信号。当前奖励模型通常只能直接作答或进行深度有限的浅层推理，奖励信号因而常常不准。
- **关键词：** GRPO, RFT, reward-model, fine-tuning

### Uni-LoRA: One Vector is All You Need

- **作者：** Kaiyang Li, Shaobo Han, Qing Su, Wei Li, Zhipeng Cai, Shihao Ji
- **会议：** NeurIPS 2025 · Main · Spotlight
- **官方论文页：** https://openreview.net/forum?id=hzBqQZK2iV
- **中文提要：** LoRA 把权重要新约束在低秩矩阵上，已成为大语言模型事实上的参数高效微调方法。Tied-LoRA、VeRA 和 VB-LoRA 等近期工作通过额外约束进一步压缩可训练参数空间。
- **关键词：** instruction-tuning, LoRA, PEFT, fine-tuning

### Uni-MuMER: Unified Multi-Task Fine-Tuning of Vision-Language Model for Handwritten Mathematical Expression Recognition

- **作者：** Yu Li, Jin Jiang, Jianhua Zhu, Shuai Peng, Baole, Yuxuan Zhou, Liangcai Gao
- **会议：** NeurIPS 2025 · Main · Spotlight
- **官方论文页：** https://openreview.net/forum?id=oHbVboLXz6
- **中文提要：** 手写数学表达式识别因符号排布自由、书写风格多变，一直是光学字符识别中的难题。先前方法多提出彼此孤立的结构改动，因而很难连贯地整合进统一框架。
- **关键词：** fine-tuning

### Unlocking Multimodal Mathematical Reasoning via Process Reward Model

- **作者：** Ruilin Luo, Zhuofan Zheng, Lei Wang, Yifan Wang, Xinzhe Ni, Zicheng Lin, Songtao Jiang, Yiyao Yu, Chufan Shi, Ruihang Chu, Jin zeng, Yujiu Yang
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=96I8PGPALv
- **中文提要：** 过程奖励模型借助测试时扩展，已显示出增强大语言模型数学推理的潜力。把它们接入多模态推理仍基本未被探索。
- **关键词：** GRPO, PRM, reward-model

### VCM: Vision Concept Modeling with Adaptive Vision Token Compression via Instruction Fine-Tuning

- **作者：** Run Luo, Renke Shan, Longze Chen, Ziqiang Liu, Lu Wang, Min Yang, Xiaobo Xia
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=iCvueZ8KaN
- **中文提要：** 大视觉语言模型已成为现实人工智能应用的基础工具。它们按词元处理整幅图像，相对于人类选择性关注高层视觉概念的方式，效率明显偏低。
- **关键词：** alignment, fine-tuning

### VideoRFT: Incentivizing Video Reasoning Capability in MLLMs via Reinforced Fine-Tuning

- **作者：** Qi Wang, Yanrui Yu, Ye Yuan, Rui Mao, Tianfei Zhou
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=3pORFyKzh1
- **中文提要：** 强化微调在让大语言模型获得接近人类水平的推理方面很有潜力，并已开始扩展到多模态大模型。对视频进行推理仍很难，因为视频数据内在地带有复杂逻辑以及时间与因果结构。
- **关键词：** RFT, SFT, alignment, fine-tuning

### What Makes a Reward Model a Good Teacher? An Optimization Perspective

- **作者：** Noam Razin, Zixuan Wang, Hubert Strauss, Stanley Wei, Jason Lee, Sanjeev Arora
- **会议：** NeurIPS 2025 · Main · Spotlight
- **官方论文页：** https://openreview.net/forum?id=7pufO0SJAC
- **中文提要：** RLHF 能否成功，关键取决于奖励模型的质量。这一质量主要以准确程度来评价，但该指标是否足以说明怎样的奖励模型才是好的教师，仍然不清楚。
- **关键词：** RLHF, reward-model

### What Matters in Data for DPO?

- **作者：** Yu Pan, Zhongze Cai, Huaiyang Zhong, Guanting Chen, Chonghuan Wang
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=GrDEV4InKZ
- **中文提要：** 直接偏好优化 DPO 绕过可学习的奖励模型，成为一种简单有效的大语言模型偏好对齐方法。偏好数据的哪些特征对 DPO 表现最为关键，仍是一个基本的开放问题。
- **关键词：** DPO, SFT, preference-optimization, reward-model, alignment, fine-tuning

### When Thinking Fails: The Pitfalls of Reasoning for Instruction-Following in LLMs

- **作者：** Xiaomin Li, Zhou Yu, Zhiwei Zhang, Xupeng Chen, Ziji Zhang, Yingying Zhuang, Narayanan Sadagopan, Anurag Beniwal
- **会议：** NeurIPS 2025 · Main · Spotlight
- **官方论文页：** https://openreview.net/forum?id=w5uUvxp81b
- **中文提要：** 推理增强的大语言模型，无论经专门训练还是借助思维链提示，已在许多复杂推理任务上达到领先表现。显式的思维链推理却可能明显降低指令遵循的准确性。
- **关键词：** instruction-following

### Whose Instructions Count? Resolving Preference Bias in Instruction Fine-Tuning

- **作者：** Jiayu Zhang, Changbang Li, Yinan Peng, Weihao Luo, Peilai Yu, Xuan Zhang
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=UFAKqq77e3
- **中文提要：** 指令微调已成为让大语言模型专门化的普遍策略，但它隐含假设所有人工指令背后存在单一、连贯的真实偏好。实际上标注者在风格、侧重点和粒度上并不一致，这种偏好偏差会侵蚀稳健性与泛化。
- **关键词：** instruction-tuning, alignment, fine-tuning

### XIFBench: Evaluating Large Language Models on Multilingual Instruction Following

- **作者：** Zhenyu Li, Kehai Chen, Yunfei Long, Xuefeng Bai, Yaoyin Zhang, Xuchen Wei, Juntao Li, Min Zhang
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=qkdVjCAPOE
- **中文提要：** 大语言模型在多种应用中表现出很强的指令遵循能力。多语言设定下的表现却缺少系统研究，现有评测也缺少跨不同语言语境的细粒度约束分析。
- **关键词：** instruction-following

### You Only Communicate Once: One-shot Federated Low-Rank Adaptation of MLLM

- **作者：** Binqian Xu, Haiyang Mei, Zechen Bai, Jinjin Gong, Rui Yan, Guosen Xie, Yazhou Yao, Basura Fernando, Xiangbo Shu
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=FoVF3iL6o3
- **中文提要：** 多模态大语言模型结合联邦学习可以快速适配隐私敏感任务，但因依赖多轮通信而面临高通信成本和更高的攻击风险。单次联邦学习旨在只通过一次客户端与服务器通信完成适配。
- **关键词：** LoRA

### Zero-Shot Detection of LLM-Generated Text via Implicit Reward Model

- **作者：** Runheng Liu, Heyan Huang, Xingchen Xiao, Zhijing Wu
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=2VdsYVXLDl
- **中文提要：** 大语言模型在各类任务上能力突出。它们生成接近人类文本的能力也引发了对潜在滥用的担忧。
- **关键词：** instruction-tuning, reward-model, fine-tuning

### Zooming from Context to Cue: Hierarchical Preference Optimization for Multi-Image MLLMs

- **作者：** Xudong Li, Mengdan Zhang, Peixian Chen, Xiawu Zheng, Yan Zhang, Jingyuan Zheng, Yunhang Shen, Ke Li, Chaoyou Fu, Xing Sun, Rongrong Ji
- **会议：** NeurIPS 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=gjvbsLyCC3
- **中文提要：** 多模态大语言模型擅长单图任务，却因跨模态不对齐而难以理解多图，并出现遗漏上下文、混淆和误读等幻觉。现有采用 DPO 的方法把优化约束在输入序列中的单一图像参照上，忽略了整体上下文建模。
- **关键词：** DPO, preference-optimization
