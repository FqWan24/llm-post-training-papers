# 2025 · ICLR

共 189 篇。Main 189，Findings 0，其他赛道 0。其中 0 篇来源题录无摘要，提要标明「仅根据标题概括」。

检索窗口为 2024-11-13 至 2026-11-13。题录信息来自官方列表，不在此增补作者、链接或实验数字。

## Main

### 3D-Properties: Identifying Challenges in DPO and Charting a Path Forward

- **作者：** Yuzi Yan, Yibo Miao, Jialian Li, YipinZhang, Jian Xie, Zhijie Deng, Dong Yan
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=9Hxdixed7p
- **中文提要：** 让大语言模型对齐人类偏好受到广泛关注：PPO 是标准但计算昂贵的做法，DPO 则是更高效的替代。DPO 虽然简单，在前沿大模型中仍用得不多，这暗示它可能存在局限。
- **关键词：** DPO, instruction-following, preference-optimization, alignment

### A Common Pitfall of Margin-based Language Model Alignment: Gradient Entanglement

- **作者：** Hui Yuan, Yifan Zeng, Yue Wu, Huazheng Wang, Mengdi Wang, Liu Leqi
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=YaBiGjuDiC
- **中文提要：** RLHF 已成为让语言模型更有帮助、更少伤害的主流对齐方法。其核心是基于间隔的偏好优化损失，只通过偏好回答与非偏好回答之间的差别来规定理想行为。
- **关键词：** RLHF, preference-optimization, alignment

### Adapt-$\infty$: Scalable Continual Multimodal Instruction Tuning via Dynamic Data Selection

- **作者：** Adyasha Maharana, Jaehong Yoon, Tianlong Chen, Mohit Bansal
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=EwFJaXVePU
- **中文提要：** 不同来源的视觉指令数据发布时间不一，并常因技能构成或参考来源而含有大量语义重复的图文对。这种冗余严重限制可持续适配的多模态大语言模型高效部署，也妨碍它们精炼已有技能并继续习得。
- **关键词：** instruction-tuning

### AdaRankGrad: Adaptive Gradient Rank and Moments for Memory-Efficient LLMs Training and Fine-Tuning

- **作者：** Yehonathan Refael, Jonathan Svirsky, Boris Shustin, Wasim Huleihel, Ofir Lindenbaum
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=LvNROciCne
- **中文提要：** 训练和微调大语言模型时，模型权重与优化器状态不断变大，显存和计算都成为难题。已有应对包括 LoRA：在每一层固定的预训练权重旁，并行加入一块可训练的低秩矩阵。
- **关键词：** LoRA, fine-tuning

### Addax: Utilizing Zeroth-Order Gradients to Improve Memory Efficiency and Performance of SGD for Fine-Tuning Language Models

- **作者：** Zeman Li, Xinwei Zhang, Peilin Zhong, Yuan Deng, Meisam Razaviyayn, Vahab Mirrokni
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=QhxjQOMdDF
- **中文提要：** 用标准 Adam 微调语言模型常常占用过多显存，从而限制了可用性。原地随机梯度下降 IP-SGD 和显存高效的零阶优化器 MeZO 被提出来改善显存效率。
- **关键词：** fine-tuning

### ADePT: Adaptive Decomposed Prompt Tuning for Parameter-Efficient Fine-tuning

- **作者：** Pengwei Tang, Xiaolin Hu, Yong Liu
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=fswihJIYbd
- **中文提要：** 提示调优通过优化少量加在输入词元嵌入前面的软虚拟词元，把预训练大语言模型适配到下游任务。分解提示调优 DePT 则把软提示拆成更短的软提示和一对低秩矩阵，并展现出更强的适配能力。
- **关键词：** PEFT, fine-tuning

### Adjoint Matching: Fine-tuning Flow and Diffusion Generative Models with Memoryless Stochastic Optimal Control

- **作者：** Carles Domingo i Enrich, Michal Drozdzal, Brian Karrer, Ricky T. Q. Chen
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=xQBRrtQM8u
- **中文提要：** 流匹配和去噪扩散这类通过迭代过程生成样本的动态模型已被广泛使用，但用奖励微调改进它们、且理论上站得住的方法并不多。这项工作把奖励微调表述为随机最优控制。
- **关键词：** reward-model, fine-tuning

### Advantage-Guided Distillation for Preference Alignment in Small Language Models

- **作者：** Shiping Gao, Fanqi Wan, Jiajian Guo, Xiaojun Quan, Qifan Wang
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=xsx3Fpo3UD
- **中文提要：** 对齐技术使大语言模型的输出贴近人类偏好，对其实际效果至关重要。这些技术用到小语言模型上时，作用常常减弱，很可能是因为模型容量有限。
- **关键词：** preference-optimization, alignment

### Aligning Language Models with Demonstrated Feedback

- **作者：** Omar Shaikh, Michelle Lam, Joey Hejna, Yijia Shao, Hyundong Cho, Michael Bernstein, Diyi Yang
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=1qGkuxI9UX
- **中文提要：** 语言模型被对齐去模仿许多人的集体声音，输出便不再特别贴合任何个体。监督微调或 RLHF 可以把模型带离这种泛化输出，但对新的临时任务需要大到难以承受的数据集。
- **关键词：** RLHF, SFT, alignment, fine-tuning

### Aligning Visual Contrastive learning models via Preference Optimization

- **作者：** Amirabbas Afzali, Borna khodabandeh, Ali Rasekh, Mahyar JafariNodeh, Sepehr Ranjbar, Simon Gottschalk
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=wgRQ2WAORJ
- **中文提要：** 对比学习模型通过在嵌入空间中对齐表示来捕捉语义相似性，能力令人印象深刻。其表现仍会受训练数据质量以及数据固有偏差的限制。
- **关键词：** DPO, RLHF, preference-optimization, alignment

### As Simple as Fine-tuning: LLM Alignment via Bidirectional Negative Feedback Loss

- **作者：** Xin Mao, Huimin Xu, Feng-Lin Li, Ziqi Jin, WANG CHEN, Wei Zhang, Anh Tuan Luu
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=fsX9nFwMNj
- **中文提要：** DPO 比采用 PPO 的 RLHF 更省计算，也不再需要奖励模型和在线采样。尽管如此，DPO 及其变体仍然对超参数敏感、容易不稳定，在数学数据上尤其明显。
- **关键词：** DPO, RLHF, SFT, preference-optimization, reward-model, alignment, fine-tuning

### Asynchronous RLHF: Faster and More Efficient Off-Policy RL for Language Models

- **作者：** Michael Noukhovitch, Shengyi Huang, Sophie Xhonneux, Arian Hosseini, Rishabh Agarwal, Aaron Courville
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=FhTAG591Ve
- **中文提要：** 一种常见流程是同步地从大语言模型策略生成、用奖励模型标注，再根据模型自身输出上的反馈来学习。这种范式虽然有效，计算上却并不高效。
- **关键词：** DPO, RLHF, instruction-following, reward-model, fine-tuning

### A Theoretical Framework for Partially-Observed Reward States in RLHF

- **作者：** Chinmaya Kausik, Mirco Mutti, Aldo Pacchiano, Ambuj Tewari
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=OjAU0LLDbe
- **中文提要：** RLHF 的部署不断扩大，需要对其底层模型做更深入的理论考察。流行模型既没有纳入有神经科学依据、会影响人类反馈的部分可观测内部状态，也不容纳交互过程中的中间反馈。
- **关键词：** RLHF, alignment

### Automated Filtering of Human Feedback Data for Aligning Text-to-Image Diffusion Models

- **作者：** Yongjin Yang, Sihyeon Kim, Hojung Jung, Sangmin Bae, SangMook Kim, Se-Young Yun, Kimin Lee
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=8jvVNPHtVJ
- **中文提要：** 用人类反馈微调文生图扩散模型，能有效把模型行为对齐到人的意图。人类反馈数据体量大且含有噪声，对齐过程因此常常收敛缓慢。
- **关键词：** DPO, preference-optimization, reward-model, alignment, fine-tuning

### Better autoregressive regression with LLMs via regression-aware fine-tuning

- **作者：** Michal Lukasik, Zhao Meng, Harikrishna Narasimhan, Yin-Wen Chang, Aditya Krishna Menon, Felix Yu, Sanjiv Kumar
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=xGs7Ch3Vyo
- **中文提要：** 基于解码器的大语言模型用途很广，即便在看似远离传统语言生成的问题上也有突出表现。回归就是一例：目标是实数，而不是文本词元。
- **关键词：** fine-tuning

### Better Instruction-Following Through Minimum Bayes Risk

- **作者：** Ian Wu, Patrick Fernandes, Amanda Bertsch, Seungone Kim, Sina Pakazad, Graham Neubig
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=7xCSK9BLPy
- **中文提要：** 达到人类水平的通用大模型评判器，既能可扩展又准确地评估指令跟随模型，也为监督和改进其表现开辟了途径。最小贝叶斯风险解码是其中一条路，它用基于参考的评估器从一组候选里选出高质量输出。
- **关键词：** instruction-following

### Beyond Content Relevance: Evaluating Instruction Following in Retrieval Models

- **作者：** Jianqun Zhou, Yuanlei Zheng, Wei Chen, Qianqian Zheng, Shang Zeyuan, Wei Zhang, Rui Meng, Xiaoyu Shen
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=OlRjxSuSwl
- **中文提要：** 大语言模型的指令跟随进步明显，详细提示能够支持更复杂的用户交互。检索系统大多还停留在传统的词法与语义匹配，跟不上这些进展，也难以充分捕捉用户意图。
- **关键词：** instruction-following, fine-tuning

### Bi-Factorial Preference Optimization: Balancing Safety-Helpfulness in Language Models

- **作者：** Wenxuan Zhang, Philip Torr, Mohamed Elhoseiny, Adel Bibi
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=GjM61KRiTG
- **中文提要：** 借助 RLHF 在人类偏好上微调大语言模型，已被证明能够增强其能力。微调期间如何保证安全仍然关键，而在 RLHF 中缓解安全与有用性之间的潜在冲突代价很高。
- **关键词：** RLHF, preference-optimization, fine-tuning

### BOND: Aligning LLMs with Best-of-N Distillation

- **作者：** Pier Giuseppe Sessa, Robert Dadashi, Léonard Hussenot-Desenonges, Johan Ferret, Nino Vieillard, Alexandre Rame, Bobak Shahriari, Sarah Perrin, Abram Friesen, Geoffrey Cideron, Sertan Girgin, Piotr Stanczyk, Andrea Michi, Danila Sinopalnikov, Sabela Ramos Garea, Amélie Héliou, Aliaksei Severyn, Matthew Hoffman, Nikola Momchev, Olivier Bachem
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=0tAXMiSufG
- **中文提要：** RLHF 是前沿大语言模型质量与安全的重要推动；推理时的 Best-of-N 采样也很强，它从多名候选中选出最佳生成。BOND 是一种试图模拟 Best-of-N、同时避开其显著计算开销的 RLHF 算法。
- **关键词：** RLHF, alignment

### Booster: Tackling Harmful Fine-tuning for Large Language Models via Attenuating Harmful Perturbation

- **作者：** Tiansheng Huang, Sihao Hu, Fatih Ilhan, Selim Tekin, Ling Liu
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=tTPHgb0EtV
- **中文提要：** 有害微调攻击给大语言模型的微调即服务带来严重安全隐患。已有防御的效果仍远未令人满意，问题的根因也还没有被充分揭示。
- **关键词：** alignment, fine-tuning

### Boosting the visual interpretability of CLIP via adversarial fine-tuning

- **作者：** Shizhan Gong, Haoyu LEI, Qi Dou, Farzan Farnia
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=khuIvzxPRp
- **中文提要：** CLIP 在视觉表示学习上很成功，并成为 LLaVA、DALL-E 等大型多模态模型的重要插件。图像编码器的复杂结构与训练过程造成可解释性不足，限制了它在高风险决策中的更广使用。
- **关键词：** alignment, fine-tuning

### Bootstrapping Language Models with DPO Implicit Rewards

- **作者：** Changyu Chen, Zichen Liu, Chao Du, Tianyu Pang, Qian Liu, Arunesh Sinha, Pradeep Varakantham, Min Lin
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=dliIIodM6b
- **中文提要：** 大语言模型的人类对齐是一个活跃的研究方向。DPO 绕过 RLHF 中的奖励学习阶段，大幅简化了以往基于人类反馈强化学习的流程。
- **关键词：** DPO, RLHF, preference-optimization, reward-model, alignment

### Bridging and Modeling Correlations in Pairwise Data for Direct Preference Optimization

- **作者：** Yuxin Jiang, Bo Huang, Yufei Wang, Xingshan Zeng, Liangyou Li, Yasheng Wang, Xin Jiang, Lifeng Shang, Ruiming Tang, Wei Wang
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=hRwxZmcvW9
- **中文提要：** DPO 是广泛采用的离线偏好优化算法，用成对偏好数据把大语言模型对齐到人所期望的行为。成对数据中胜出回答与落败回答的生成通常彼此隔离，相关性弱，对齐效果也不理想。
- **关键词：** DPO, instruction-following, preference-optimization, alignment

### Cached Multi-Lora Composition for Multi-Concept Image Generation

- **作者：** Xiandong Zou, Mingzhu Shen, Christos-Savvas Bouganis, Yiren Zhao
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=4iFSBgxvIO
- **中文提要：** 文生图模型广泛采用 LoRA，以便在多概念图像中精确呈现角色、风格等不同元素。把多份 LoRA 组合使用时，数量一增加生成质量就会下降，现有组合方法在这里遇到明显困难。
- **关键词：** LoRA

### CHiP: Cross-modal Hierarchical Direct Preference Optimization for Multimodal LLMs

- **作者：** Jinlan Fu, Shenzhen Huangfu, Hao Fei, Xiaoyu Shen, Bryan Hooi, Xipeng Qiu, See-Kiong Ng
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=7lpDn2MhM2
- **中文提要：** 多模态大语言模型能力虽强，幻觉问题仍然突出。近期研究尝试把 DPO 用到多模态场景，并以来自文本回答的偏好对作为训练信号。
- **关键词：** DPO, preference-optimization

### Collab: Controlled Decoding using Mixture of Agents for LLM Alignment

- **作者：** Souradip Chakraborty, Sujay Bhatt, Udari Sehwag, Soumya Suvra Ghosal, Jiahao Qiu, Mengdi Wang, Dinesh Manocha, Furong Huang, Alec Koppel, Sumitra Ganesh
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=7ohlQUbTpp
- **中文提要：** 大语言模型需要经过对齐，才能安全、可信地部署到应用中。RLHF 能把模型拉向人类偏好和更广的用途，但必须更新模型参数，计算代价很高。
- **关键词：** RLHF, alignment

### ComLoRA: A Competitive Learning Approach for Enhancing LoRA

- **作者：** Qiushi Huang, Tom Ko, Lilian Tang, Yu Zhang
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=jFcNXJGPGh
- **中文提要：** ComLoRA 用竞争性低秩适应来缓解 LoRA 的两难：单个低秩模块容量不足，单纯加大秩又容易低效并过拟合。它初始化多组彼此不同、秩相同的 LoRA 分量，并让它们在训练中相互竞争。
- **关键词：** LoRA

### Computational Limits of Low-Rank Adaptation (LoRA) Fine-Tuning for Transformer Models

- **作者：** Jerry Yao-Chieh Hu, Maojiang Su, En-Jui Kuo, Zhao Song, Han Liu
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Lf5znhZmFu
- **中文提要：** 作者用细粒度复杂度理论研究 LoRA 微调 Transformer 的计算极限。梯度计算中存在低秩分解，因而可能带来算法加速，并据此讨论效率在强指数时间假设下的相变。
- **关键词：** LoRA, fine-tuning

### Context-Parametric Inversion: Why Instruction Finetuning May Not Actually Improve Context Reliance

- **作者：** Sachin Goyal, Christina Baek, Zico Kolter, Aditi Raghunathan
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=SPS6HzVzyt
- **中文提要：** 指令微调旨在让大语言模型更好地遵循用户指令、理解输入上下文。当上下文与模型自身的参数化知识相矛盾时，模型仍然常常无法跟上上下文。
- **关键词：** instruction-tuning, fine-tuning

### Correcting the Mythos of KL-Regularization: Direct Alignment without Overoptimization via Chi-Squared Preference Optimization

- **作者：** Audrey Huang, Wenhao Zhan, Tengyang Xie, Jason Lee, Wen Sun, Akshay Krishnamurthy, Dylan Foster
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=hXm0Wu2U9K
- **中文提要：** RLHF 等对齐方法提升了语言模型能力，却受到过度优化的限制，对齐过程中模型质量会下降。模型在离线奖励模型上持续优化时，会过拟合其中的不准确之处。
- **关键词：** DPO, RLHF, preference-optimization, reward-model, alignment

### Correlating instruction-tuning (in multimodal models) with vision-language processing (in the brain)

- **作者：** SUBBA REDDY OOTA, Akshett Rai Jindal, Ishani Mondal, Khushbu Pahwa, Satya Sai Srinath Namburi GNVV, Manish Shrivastava, Maneeesh Singh, Raju Surampudi Bapi, Manish Gupta
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=xkgfLXZ4e0
- **中文提要：** 基于 Transformer 的语言模型并未被专门训练去拟合脑记录，却与大脑活动呈现出对齐。模型规模、指令微调与多模态方面的进展，进一步改善了表征和神经数据之间的对应。
- **关键词：** instruction-tuning, alignment

### CREAM: Consistency Regularized Self-Rewarding Language Models

- **作者：** Zhaoyang Wang, Weilei He, Zhiyuan Liang, Xuchao Zhang, Chetan Bansal, Ying Wei, Weitong Zhang, Huaxiu Yao
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Vf6RDObyEF
- **中文提要：** 自奖励大语言模型借助 LLM-as-a-Judge 迭代改进对齐，而不需要人工标注的偏好数据。这类方法通常让同一个模型同时担任生成回答的策略模型，以及给回答打分排序的奖励模型。
- **关键词：** DPO, reward-model, alignment, self-rewarding, fine-tuning

### Ctrl-U: Robust Conditional Image Generation via Uncertainty-aware Reward Modeling

- **作者：** Guiyu Zhang, Huan-ang Gao, Zijian Jiang, Hao Zhao, Zhedong Zheng
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=eC2ICbECNM
- **中文提要：** 条件图像生成要根据用户指令合成图像。关键难点在于同时保证生成图像的保真度，以及与给定条件在语义上的对齐。
- **关键词：** reward-model, alignment, fine-tuning

### Data Distillation for extrapolative protein design through exact preference optimization

- **作者：** Mostafa Karimi, Sharmi Banerjee, Tommi Jaakkola, Bella Dubrov, Shang Shang, Ron Benson
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ua5MHdsbck
- **中文提要：** 蛋白质设计常常希望把适应度外推到训练分布之外，例如更高的稳定性或更强的结合亲和力。现有先进方法假定只从成对样本学习，就能安全地把蛋白质导向这些外推区域。
- **关键词：** preference-optimization, alignment

### dEBORA: Efficient Bilevel Optimization-based low-Rank Adaptation

- **作者：** Emanuele Zangrando, Sara Venturini, Francesco Rinaldi, Francesco Tudisco
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=5M0ic2RxQZ
- **中文提要：** 低秩适应是大规模神经网络做参数高效微调的常用路线。为每一层选择合适的秩仍然困难，而且会同时影响性能和效率。
- **关键词：** LoRA, PEFT, fine-tuning

### Decoupling Angles and Strength in Low-rank Adaptation

- **作者：** Massimo Bini, Leander Girrbach, Zeynep Akata
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=X1U74IwuxG
- **中文提要：** 大规模预训练模型普及后，PEFT 迅速受到关注。这类方法能以很低的计算代价，把模型较快地适配到下游任务。
- **关键词：** instruction-tuning, LoRA, PEFT, fine-tuning

### DELIFT: Data Efficient Language model Instruction Fine-Tuning

- **作者：** Ishika Agarwal, Krishnateja Killamsetty, Lucian Popa, Marina Danilevsky
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Fty0wTcemV
- **中文提要：** 微调对大语言模型的任务专门化很重要，但冗余或信息量低的数据会让资源消耗很高。已有的数据选择要么依赖计算昂贵的梯度指标，要么使用无法随模型状态动态调整的静态嵌入。
- **关键词：** instruction-tuning, fine-tuning

### Differentially Private Steering for Large Language Model Alignment

- **作者：** Anmol Goel, Yaxi Hu, Iryna Gurevych, Amartya Sanyal
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=lLkgj7FEtZ
- **中文提要：** 让大语言模型贴近人类价值、远离幻觉等不良行为正变得更加重要。通过在推理时编辑激活来引导模型，已被用来抑制有害生成。
- **关键词：** alignment

### Diffusion-NPO: Negative Preference Optimization for Better Preference Aligned Generation of Diffusion Models

- **作者：** Fu-Yun Wang, Yunhao Shui, Jingtan Piao, Keqiang Sun, Hongsheng Li
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=iJi7nz5Cxc
- **中文提要：** 扩散模型大幅推进了图像生成，但在庞大且未经过滤的数据上训练时，输出常常偏离人类偏好。已有不少方法通过微调预训练扩散模型，来改善生成结果与人类偏好的对齐。
- **关键词：** preference-optimization, alignment, fine-tuning

### Directional Gradient Projection for Robust Fine-Tuning of Foundation Models

- **作者：** Chengyue Huang, Junjiao Tian, Brisa Maneechotesuwan, Shivang Chopra, Zsolt Kira
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=goBaGHLAdP
- **中文提要：** 稳健微调希望把基础模型适配到下游任务，同时保住对分布偏移的鲁棒性。已有方法多按微调权重与预训练权重的幅度，把当前模型约束并投影回预训练起点，往往要大量调参，有时还会欠拟合。
- **关键词：** fine-tuning

### Direct Post-Training Preference Alignment for Multi-Agent Motion Generation Model Using Implicit Feedback from Pre-training Demonstrations

- **作者：** Thomas Tian, Kratarth Goel
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=8UFG9D8xeU
- **中文提要：** 大语言模型的进展改变了自动驾驶、机器人操作等具身场景里的运动生成。自回归运动模型虽能随训练扩展，其词元预测目标与人类偏好之间仍然存在落差。
- **关键词：** preference-optimization, post-training, alignment

### Do as I do (Safely): Mitigating Task-Specific Fine-tuning Risks in Large Language Models

- **作者：** Francisco Eiras, Aleksandar Petrov, Philip Torr, M. Pawan Kumar, Adel Bibi
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=lXE5lB6ppV
- **中文提要：** 在良性的指令跟随数据上微调，也可能无意间破坏安全对齐，使模型更愿意配合有害请求。另一类任务型微调则在答案明确的数据上训练，例如选择题，用来提升相应任务上的表现。
- **关键词：** instruction-following, alignment, fine-tuning

### Do LLMs estimate uncertainty well in instruction-following?

- **作者：** Juyeon Heo, Miao Xiong, Christina Heinze-Deml, Jaya Narain
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=IHp3vOVQO2
- **中文提要：** 若大语言模型能精确遵循用户指令，就有望充当跨领域的个人智能体。近期研究却表明其指令跟随能力存在明显局限，从而牵动高风险应用中的可靠性。
- **关键词：** instruction-following

### DSPO: Direct Score Preference Optimization for Diffusion Model Alignment

- **作者：** Huaisheng Zhu, Teng Xiao, Vasant Honavar
- **会议：** ICLR 2025 · Main · Oral
- **官方论文页：** https://openreview.net/forum?id=2025-Oral--7413-9cefb21d
- **中文提要：** 基于扩散的文生图模型已能根据文本提示生成高质量图像。语言模型可以借助 DPO 在人类偏好数据上微调且不必另建奖励模型，扩散模型在这一方向上还较少被充分探索。
- **关键词：** DPO, preference-optimization, reward-model, alignment, fine-tuning

### Earlier Tokens Contribute More: Learning Direct Preference Optimization From Temporal Decay Perspective

- **作者：** Ruichen Shao, Bei Li, Gangao Liu, Yang Chen, Xiang Zhou, Jingang Wang, Xunliang Cai, Peng Li
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=OspqtLVUN5
- **中文提要：** DPO 作为 RLHF 的高效替代，被用于把大语言模型对齐到人类偏好。它却存在长度偏差，生成的回答往往比参考模型更长。
- **关键词：** DPO, SimPO, RLHF, preference-optimization, alignment

### Efficiently Learning at Test-Time: Active Fine-Tuning of LLMs

- **作者：** Jonas Hübotter, Sascha Bongni, Ido Hakimi, Andreas Krause
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=NS1G1Uhny3
- **中文提要：** 语言模型微调中的自动选数据，常见做法是从大规模集合里做近邻检索。理论上这容易选到冗余样本，从而限制效果甚至损害性能；为此提出 SIFT，用来降低给定条件下模型对回答的不确定性。
- **关键词：** fine-tuning

### Efficient Model Editing with Task-Localized Sparse Fine-tuning

- **作者：** Leonardo Iurada, Marco Ciccone, Tatiana Tommasi
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=TDyE2iuvyc
- **中文提要：** 任务算术把特定任务的知识表示成可组合的任务向量，用来编辑模型。现有做法依赖网络线性化来得到这些向量，训练和推理阶段都会形成计算瓶颈。
- **关键词：** fine-tuning

### Emerging Safety Attack and Defense in Federated Instruction Tuning of Large Language Models

- **作者：** Rui Ye, Jingyi Chai, Xiangrui Liu, Yaodong Yang, Yanfeng Wang, Siheng Chen
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=sYNWqQYJhz
- **中文提要：** 联邦学习让多方在不直接共享数据的情况下协同微调大语言模型。理想情形下，若去中心化数据符合人类偏好与安全原则，联邦指令微调可以得到既有帮助又安全的模型。
- **关键词：** instruction-tuning, alignment, fine-tuning

### Enhancing Zeroth-order Fine-tuning for Language Models with Low-rank Structures

- **作者：** Yiming Chen, Yuan Zhang, Liyuan Cao, Kun Yuan, Zaiwen Wen
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=9BiVepgmWW
- **中文提要：** PEFT 能明显降低把大语言模型适配到下游应用时的显存开销。传统一阶微调在计算梯度时必须保存激活以做反向传播，长上下文微调中这一显存负担尤其重。
- **关键词：** PEFT, fine-tuning

### Examining Alignment of Large Language Models through Representative Heuristics: the case of political stereotypes

- **作者：** Sullam Jeoung, Yubin Ge, Haohan Wang, Jana Diesner
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=7LGmXXZXtP
- **中文提要：** 当大语言模型未能按预期运作时，检验其对齐就尤为重要。这项研究把考察放在政治领域，看模型是否与人类价值对齐。
- **关键词：** alignment

### Exploratory Preference Optimization: Harnessing Implicit Q*-Approximation for Sample-Efficient RLHF

- **作者：** Tengyang Xie, Dylan Foster, Akshay Krishnamurthy, Corby Rosset, Ahmed H Awadallah, Alexander Rakhlin
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=QYigQ6gXNw
- **中文提要：** 文章从理论角度追问 RLHF 中的一个基本问题：在偏好反馈和一般函数逼近下，如何高效地进行在线探索。作为理解该问题的第一步，作者提出探索性偏好优化算法 XPO。
- **关键词：** DPO, RLHF, preference-optimization

### Facilitating Multi-turn Function Calling for LLMs via Compositional Instruction Tuning

- **作者：** Mingyang Chen, sunhaoze, Tianpeng Li, Fan Yang, Hao Liang, KeerLu, Bin CUI, Wentao Zhang, Zenan Zhou, Weipeng Chen
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=owP2mymrTD
- **中文提要：** 大语言模型可以调用函数或外部工具来增强能力，但相关研究主要集中在单轮交互。该工作转向多轮函数调用，认为这对处理需要组合的任务至关重要。
- **关键词：** instruction-tuning

### Fine-tuning can cripple your foundation model; preserving features may be the solution

- **作者：** Philip Torr, Puneet Dokania, Jishnu Mukhoti, Yarin Gal
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://iclr.cc/virtual/2025/poster/31485
- **中文提要：** 预训练基础模型容量大，又在预训练阶段接触过大量数据，因而学到许多现实世界中的概念。要让这些模型在下游任务上真正有效，还需要在相关数据上继续微调。
- **关键词：** fine-tuning

### Fine-tuning can Help Detect Pretraining Data from Large Language Models

- **作者：** Hengxiang Zhang, Songxin Zhang, Bingyi Jing, Hongxin Wei
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=X8dzvdkQwO
- **中文提要：** 检测大语言模型是否在预训练中见过某些数据，因评测公平和伦理风险而越来越重要。现有方法通过设计打分函数区分成员与非成员，例如困惑度和 Min-k。
- **关键词：** fine-tuning

### Fine-Tuning Discrete Diffusion Models via Reward Optimization with Applications to DNA and Protein Design

- **作者：** Chenyu Wang, Masatoshi Uehara, Yichun He, Amy Wang, Avantika Lal, Tommi Jaakkola, Sergey Levine, Aviv Regev, Hanchen Wang, Tommaso Biancalani
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=G328D1xt4W
- **中文提要：** 离散扩散模型在自然语言和生物序列等离散序列生成上已有较强的经验表现。以蛋白质逆折叠为例，条件扩散模型要根据给定骨架生成蛋白质序列，并已取得突出结果。
- **关键词：** reward-model, fine-tuning

### FlexCAD: Unified and Versatile Controllable CAD Generation with Fine-tuned Large Language Models

- **作者：** Zhanwei Zhang, Shizhao Sun, Wenxiao Wang, Deng Cai, Jiang Bian
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Z0eiiV3Yyh
- **中文提要：** 按用户意图生成 CAD 模型、即可控 CAD 生成，正受到更多关注。已有工作的可控性有限，而且不同控制类型往往要各自单独建模，效率和实用性都会下降。
- **关键词：** fine-tuning

### From Artificial Needles to Real Haystacks: Improving Retrieval Capabilities in LLMs by Finetuning on Synthetic Data

- **作者：** Zheyang Xiong, Vasilis Papageorgiou, Kangwook Lee, Dimitris Papailiopoulos
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=8m7p4k6Zeb
- **中文提要：** 大语言模型在处理长上下文时，既难准确检索信息，也难保持推理能力。为此提出在精心设计的合成数据上微调，这些数据由数值键值检索任务构成。
- **关键词：** fine-tuning

### GenARM: Reward Guided Generation with Autoregressive Reward Model for Test-Time Alignment

- **作者：** Yuancheng Xu, Udari Sehwag, Alec Koppel, Sicheng Zhu, Bang An, Furong Huang, Sumitra Ganesh
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=J0qTpmbSbh
- **中文提要：** 大语言模型表现出色，但仍需要与人类偏好仔细对齐。训练阶段用人类偏好数据做微调的传统做法成本很高，而且面对不同用户偏好往往要反复重训。
- **关键词：** reward-model, alignment, fine-tuning

### Generative Representational Instruction Tuning

- **作者：** Niklas Muennighoff, Hongjin SU, Liang Wang, Nan Yang, Furu Wei, Tao Yu, Amanpreet Singh, Douwe Kiela
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=BC4lIvfSzv
- **中文提要：** 一切基于文本的语言问题都可以归结为生成或嵌入二者之一。现有模型通常只在其中一边表现好。
- **关键词：** instruction-tuning

### Generative Verifiers: Reward Modeling as Next-Token Prediction

- **作者：** Lunjun Zhang, Arian Hosseini, Hritik Bansal, Seyed Mehran Kazemi, Aviral Kumar, Rishabh Agarwal
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Ccwp4tFEtE
- **中文提要：** 验证器或奖励模型常被用来提升大语言模型的推理表现。常见的 Best-of-N 先生成多个候选解答，再由验证器排序并选出最好的一个。
- **关键词：** DPO, instruction-tuning, reward-model

### GeoLoRA: Geometric integration for parameter efficient fine-tuning

- **作者：** Steffen Schotthöfer, Emanuele Zangrando, Gianluca Ceruti, Francesco Tudisco, Jonas Kusch
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=bsFWJ0Kget
- **中文提要：** LoRA 已成为大规模预训练网络进行参数高效微调的常用方法。它及其扩展仍要面对秩的自适应、稳健性，以及微调过程中的计算效率等挑战。
- **关键词：** LoRA, PEFT, fine-tuning

### GROOT-2: Weakly Supervised Multimodal Instruction Following Agents

- **作者：** Shaofei Cai, Bowei Zhang, Zihao Wang, Haowei Lin, Xiaojian Ma, Anji Liu, Yitao Liang
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=S9GyQUXzee
- **中文提要：** 让智能体遵循多模态指令，仍是机器人与人工智能中的基础难题。在无标注数据上做大规模预训练可以学到多样行为，但这些智能体往往仍不擅长按指令行动。
- **关键词：** instruction-following, alignment

### HERO: Human-Feedback Efficient Reinforcement Learning for Online Diffusion Model Finetuning

- **作者：** Ayano Hiranaka, Shang-Fu Chen, Chieh-Hsin Lai, Dongjun Kim, Naoki Murata, Takashi Shibuya, WeiHsiang Liao, Shao-Hua Sun, Yuki Mitsufuji
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=yMHe9SRvxk
- **中文提要：** 通过微调 Stable Diffusion 做可控生成，目标是提高保真度、安全性以及对人类引导的对齐。现有 RLHF 方法多依赖预先设定的启发式奖励，或建在大规模数据上的预训练奖励模型，在这类数据难以收集时就不适用。
- **关键词：** RLHF, reward-model, alignment, fine-tuning

### HMoRA: Making LLMs More Effective with Hierarchical Mixture of LoRA Experts

- **作者：** Mengqi Liao, Wei Chen, Junfeng Shen, Shengnan Guo, Huaiyu Wan
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=lTkHiXeuDl
- **中文提要：** 把 MoE 与 PEFT 结合起来微调大语言模型，有望在多任务场景里兼顾效果与资源开销。现有 MoE 方法仍有局限，例如没有顾及不同层所捕捉特征的粒度并不相同。
- **关键词：** LoRA, PEFT, fine-tuning

### How to Evaluate Reward Models for RLHF

- **作者：** Evan Frick, Tianle Li, Connor Chen, Wei-Lin Chiang, Anastasios Angelopoulos, Jiantao Jiao, Banghua Zhu, Joseph E Gonzalez, Ion Stoica
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=cbttLtO94Q
- **中文提要：** 作者提出一套新的奖励模型基准，用来衡量它们经由 RLHF 产出强语言模型的能力。完整跑通 RLHF 再直接考察下游表现虽是金标准，却过于昂贵，于是转而建立对下游表现的预测。
- **关键词：** RLHF, reward-model

### Improving Instruction-Following in Language Models through Activation Steering

- **作者：** Alessandro Stolfo, Vidhisha Balachandran, Safoora Yousefi, Eric Horvitz, Besmira Nushi
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=wozhdnRCtw
- **中文提要：** 遵循指令的能力对语言模型的许多实际应用都很关键。该工作从模型中提取针对特定指令的向量表示，并用来引导模型。
- **关键词：** instruction-tuning, instruction-following

### Inference-Aware Fine-Tuning for Best-of-N Sampling in Large Language Models

- **作者：** Yinlam Chow, Guy Tennenholtz, Izzeddin Gur, Vincent Zhuang, Bo Dai, Aviral Kumar, Rishabh Agarwal, Sridhar Thiagarajan, Craig Boutilier, Aleksandra Faust
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=77gQUdQhE7
- **中文提要：** 用好推理阶段的计算，对发挥大语言模型的性能很重要。Best-of-N 让模型生成多个回答，再由验证器选出其中最好的一个，经验上已经表现较强。
- **关键词：** fine-tuning

### Instruct-SkillMix: A Powerful Pipeline for LLM Instruction Tuning

- **作者：** Simran Kaur, Simon Park, Anirudh Goyal, Sanjeev Arora
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=44z7HL4mfX
- **中文提要：** INSTRUCT-SKILLMIX 用自动化流程为指令跟随构造多样且高质量的 SFT 数据。流程分两个阶段，各自借助已有的强语言模型；技能抽取阶段通过直接提示模型，抽出指令跟随所需的核心技能。
- **关键词：** DPO, SFT, instruction-tuning, instruction-following

### Interpreting Language Reward Models via Contrastive Explanations

- **作者：** Junqi Jiang, Tom Bewley, Saumitra Mishra, Freddy Lecue, Manuela Veloso
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=i8IwcQBi74
- **中文提要：** 奖励模型是把大语言模型输出对齐到人类价值的关键部件。它们对同一提示下的不同回答预测并比较奖励分数，以此来近似人类偏好。
- **关键词：** reward-model, alignment

### Inverse Constitutional AI: Compressing Preferences into Principles

- **作者：** Arduin Findeis, Timo Kaufmann, Eyke Hüllermeier, Samuel Albanie, Robert Mullins
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=9FRwkPw3Cn
- **中文提要：** 反馈数据被广泛用于微调和评测先进的人工智能模型。成对文本偏好尤其常见：由人或模型在两个选项中选出更好的一个。
- **关键词：** reward-model, fine-tuning

### Is In-Context Learning Sufficient for Instruction Following in LLMs?

- **作者：** Hao Zhao, Maksym Andriushchenko, francesco croce, Nicolas Flammarion
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=STEEDDv3zI
- **中文提要：** 上下文学习允许大语言模型不更新权重，只从示例中学习，对能容纳许多示例的长上下文模型尤其有潜力。文中随后提及 Lin 等人的近期工作。
- **关键词：** instruction-following, alignment, fine-tuning

### Iterative Label Refinement Matters More than Preference Optimization under Weak Supervision

- **作者：** Yaowen Ye, Cassidy Laidlaw, Jacob Steinhardt
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=q5EZ7gKcnW
- **中文提要：** 常见流程是先用任务演示做 SFT，再用偏好比较进行 RLHF。随着语言模型能力变强，分配给它们的任务也变得更难监督。
- **关键词：** DPO, RLHF, SFT, instruction-following, preference-optimization, post-training, fine-tuning

### Iterative Nash Policy Optimization: Aligning LLMs with General Preferences via No-Regret Learning

- **作者：** Yuheng Zhang, Dian Yu, Baolin Peng, Linfeng Song, Ye Tian, Mingyue Huo, Nan Jiang, Haitao Mi, Dong Yu
- **会议：** ICLR 2025 · Main · Oral
- **官方论文页：** https://openreview.net/forum?id=2025-Oral--11848-c8ca9413
- **中文提要：** RLHF 在把大语言模型对齐到人类偏好上已经取得很大成功。主流的基于奖励的做法遵循 Bradley-Terry 模型假设，而这未必能充分刻画人类偏好的复杂性。
- **关键词：** RLHF, SFT, alignment

### Joint Fine-tuning and Conversion of Pretrained Speech and Language Models towards Linear Complexity

- **作者：** Mutian He, Philip N. Garner
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=90Db4RUBc7
- **中文提要：** Linformer 和 Mamba 等架构已成为 Transformer 在线性时间复杂度上有竞争力的替代。对应的大规模预训练模型却常常缺失，非文本领域尤其如此。
- **关键词：** fine-tuning

### Joint Reward and Policy Learning with Demonstrations and Human Feedback Improves Alignment

- **作者：** Chenliang Li, Siliang Zeng, Zeyi Liao, Jiaxiang Li, Dongyeop Kang, Alfredo Garcia, Mingyi Hong
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=VCbqXtS5YY
- **中文提要：** 对齐人类偏好或意图，是当代基础模型的一项重要要求。常见的 RLHF 把过程拆成三个阶段，已经写明的前两步是：用大量演示数据做 SFT，再根据人类反馈估计奖励模型。
- **关键词：** RLHF, SFT, reward-model, alignment, fine-tuning

### JudgeLM: Fine-tuned Large Language Models are Scalable Judges

- **作者：** Lianghui Zhu, Xinggang Wang, Xinlong Wang
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=xsELpEPn4A
- **中文提要：** 在开放式场景中评测大语言模型很困难，现有基准和指标无法全面衡量。JudgeLM 把大语言模型微调成可扩展的评判者，以便在开放式基准上高效地评测其他模型。
- **关键词：** fine-tuning

### Knowledge Graph Finetuning Enhances Knowledge Manipulation in Large Language Models

- **作者：** Hanzhu Chen, Xu Shen, Jie Wang, Zehao Wang, Qitan Lv, Junjie He, Rong Wu, Feng Wu, Jieping Ye
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=oMFOKjwaRS
- **中文提要：** 通用大语言模型表现突出，但在低数据、知识密集等特定领域的应用仍然困难。SFT 在少量标注数据上继续训练，已被用来把通用模型适配到具体任务或领域。
- **关键词：** SFT, fine-tuning

### Language Model Alignment in Multilingual Trolley Problems

- **作者：** Zhijing Jin, Max Kleiman-Weiner, Giorgio Piatti, Sydney Levine, Jiarui Liu, Fernando Gonzalez Adauto, Francesco Ortu, András Strausz, Mrinmaya Sachan, Rada Mihalcea, Yejin Choi, Bernhard Schölkopf
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=VEqPDZIDAh
- **中文提要：** 这项工作在多语言电车难题上评估大语言模型的道德对齐是否符合人类偏好。它基于 Moral Machine 实验中的人类判断，构建了名为 MultiTP 的跨语言道德困境语料。
- **关键词：** alignment

### Language Models Learn to Mislead Humans via RLHF

- **作者：** Jiaxin Wen, Ruiqi Zhong, Akbir Khan, Ethan Perez, Jacob Steinhardt, Minlie Huang, Sam Bowman, He He, Shi Feng
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=xJljiPE6dg
- **中文提要：** 语言模型会产出人类难以察觉的错误，任务复杂时尤其如此。RLHF 可能加剧这一现象：为了获得更高奖励，模型即使答错也会更擅长说服人自己是对的；作者在标准 RLHF 流程下研究该现象，并称之为 U-Sophistry。
- **关键词：** RLHF, post-training

### Learning Dynamics of LLM Finetuning

- **作者：** YI REN, Danica Sutherland
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=tPNHOoZFl9
- **中文提要：** 学习动态描述某个训练样本的学习如何影响模型对其他样本的预测。该工作通过逐步分解影响在不同潜在回答之间如何累积，考察大语言模型在各类微调中的学习动态。
- **关键词：** DPO, instruction-tuning, preference-optimization, alignment, fine-tuning

### Learning LLM-as-a-Judge for Preference Alignment

- **作者：** Ziyi Ye, Xiangsheng Li, Qiuchi Li, Qingyao Ai, Yujia Zhou, Wei Shen, Dong Yan, Yiqun LIU
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=HZVIQE1MsJ
- **中文提要：** 从偏好反馈中学习，是把大语言模型对齐到人类价值的常见做法。传统上会把偏好编码进标量奖励模型：在语言模型上接一个价值头，输出分数作为偏好。
- **关键词：** DPO, preference-optimization, reward-model, alignment

### LiNeS: Post-training Layer Scaling Prevents Forgetting and Enhances Model Merging

- **作者：** Ke Wang, Nikos Dimitriadis, Alessandro Favero, Guillermo Ortiz-Jimenez, François Fleuret, Pascal Frossard
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=J5sUOvlLbQ
- **中文提要：** 微调预训练模型以注入专门知识已成为常规做法，但会带来两方面困难：目标领域上的改进常常造成灾难性遗忘，损害其他任务的泛化；合并来自不同任务的微调检查点也可能带来明显的性能损失。
- **关键词：** RLHF, post-training, fine-tuning

### LoCA: Location-Aware Cosine Adaptation for Parameter-Efficient Fine-Tuning

- **作者：** Zhekai Du, Yinjie Min, Jingjing Li, Ke Lu, Changliang Zou, Liuhua Peng, Tingjin Chu, Mingming Gong
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=4NRjdISWby
- **中文提要：** LoRA 是把预训练大语言模型适配到下游任务的主流低秩方法。其简单的低秩分解形式可能会限制优化的灵活性。
- **关键词：** LoRA, PEFT, fine-tuning

### LongPO: Long Context Self-Evolution of Large Language Models through Short-to-Long Preference Optimization

- **作者：** Guanzheng Chen, Xin Li, Michael Qizhe Shieh, Lidong Bing
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=qTrEq31Shm
- **中文提要：** 短上下文上很强的大语言模型，到了长上下文里仍可能因为对齐不足而变差。LongPO 把这种落差归结为长上下文对齐不够。
- **关键词：** DPO, SFT, preference-optimization, alignment

### LoRA Done RITE: Robust Invariant Transformation Equilibration for LoRA Optimization

- **作者：** Jui-Nan Yen, Si Si, Zhao Meng, Felix Yu, Venkata Sai Surya Subramanyam Duvvuri, Inderjit Dhillon, Cho-Jui Hsieh, Sanjiv Kumar
- **会议：** ICLR 2025 · Main · Oral
- **官方论文页：** https://openreview.net/forum?id=2025-Oral--8978-bbd1c7a8
- **中文提要：** 作为降低显存的参数高效微调，LoRA 的现有优化器缺少变换不变性：两个低秩因子如何缩放或旋转，会直接改变更新。
- **关键词：** LoRA, PEFT, fine-tuning

### LoRA Learns Less and Forgets Less

- **作者：** Jonathan Frankle, Jose Javier Gonzalez Ortiz, Cody Blakeney, Mansheej Paul, Philip Greengard, Dan Biderman, Jacob Portes, Connor Jennings, Daniel King, Sam Havens, Vitaliy Chiley, John Cunningham
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://iclr.cc/virtual/2025/poster/31465
- **中文提要：** 参数高效微调里，LoRA 只更新选定权重矩阵上的低秩扰动，从而把显存开销降下来。
- **关键词：** LoRA, PEFT, continued-pretraining, fine-tuning

### LoRA-Pro: Are Low-Rank Adapters Properly Optimized?

- **作者：** Zhengbo Wang, Jian Liang, Ran He, Zilei Wang, Tieniu Tan
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=gTwRMU3lJ5
- **中文提要：** 计算更省并不等于效果更好，LoRA 的表现仍常落后于全量微调。作者先指出两者的优化过程存在根本联系：用 LoRA 做优化在数学上等价于全量微调中的某种对应过程。
- **关键词：** LoRA, PEFT, fine-tuning

### LoRA-X: Bridging Foundation Models with Training-Free Cross-Model Adaptation

- **作者：** Farzad Farhadzadeh, Debasmit Das, Shubhankar Borse, Fatih Porikli
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=6cQ6cBqzV3
- **中文提要：** 少量针对特定基座的额外参数，就能让 LoRA 接近全量微调的效果。基座一旦被弃用并替换，配套的 LoRA 模块就都必须重新训练。
- **关键词：** LoRA, PEFT, fine-tuning

### MACPO: Weak-to-Strong Alignment via Multi-Agent Contrastive Preference Optimization

- **作者：** Yougang Lyu, Lingyong Yan, Zihan Wang, Dawei Yin, Pengjie Ren, Maarten de Rijke, Zhaochun Ren
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=x1Okv4kbVR
- **中文提要：** 模型在特定任务上已经接近人类之后，对齐变得更紧迫。此时要用弱教师产生的弱监督去对齐更强的学生模型，也就是弱到强对齐。
- **关键词：** RLHF, preference-optimization, alignment, fine-tuning

### Magnetic Preference Optimization: Achieving Last-iterate Convergence for Language Model Alignment

- **作者：** Mingzhi Wang, Chengdong Ma, Qizhi Chen, Linjian Meng, Yang Han, Jiancong Xiao, Zhaowei Zhang, Jing Huo, Weijie Su, Yaodong Yang
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=PDnEDS244P
- **中文提要：** 自博弈在多个领域都提升了模型能力。放到 RLHF 中，它不仅提高大模型表现，还通过寻找基于偏好的双人常和设定下的纳什均衡，来摆脱传统 Bradley-Terry 假设。
- **关键词：** RLHF, preference-optimization, alignment, fine-tuning

### Maintaining Structural Integrity in Parameter Spaces for Parameter Efficient Fine-tuning

- **作者：** Chongjie Si, Xuehui Wang, Xue Yang, Zhengqin Xu, Qingyun Li, Jifeng Dai, Yu Qiao, Xiaokang Yang, Wei Shen
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=OALIb8oNfl
- **中文提要：** 下游任务数量大、成本高，把预训练基础模型的全部参数都调整一遍并不可行，因而需要转向参数高效微调。
- **关键词：** PEFT, fine-tuning

### MallowsPO: Fine-Tune Your LLM with Preference Dispersions

- **作者：** Haoxian Chen, Hanyang Zhao, Henry Lam, David Yao, Wenpin Tang
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=d8cnezVcaW
- **中文提要：** DPO 近来常被用来改进 RLHF，从而更好地微调大模型。它的弱点在于无法刻画人类偏好的多样性。
- **关键词：** DPO, RLHF, preference-optimization, fine-tuning

### MambaPEFT: Exploring Parameter-Efficient Fine-Tuning for Mamba

- **作者：** Masakazu Yoshimura, Teruaki Hayashi, Yota Maeda
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=UAKnJMIBwf
- **中文提要：** 大规模数据堆出的 Transformer 模型已经形成生态。要把它们低成本部署到下游并保持效果，PEFT 是关键技术。
- **关键词：** PEFT, fine-tuning

### MA-RLHF: Reinforcement Learning from Human Feedback with Macro Actions

- **作者：** Yekun Chai, Haoran Sun, Huang Fang, Shuohuan Wang, Yu Sun, hua wu
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=WWXjMYZxfH
- **中文提要：** 词元级 RLHF 在长序列上遇到信用分配问题：奖励延迟到达，模型很难分辨哪些动作促成了被偏好的结果。
- **关键词：** RLHF, alignment

### Mask-DPO: Generalizable Fine-grained Factuality Alignment of LLMs

- **作者：** Yuzhe Gu, Wenwei Zhang, Chengqi Lyu, Dahua Lin, Kai Chen
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=d2H1oTNITn
- **中文提要：** 大模型充当助手时会产生幻觉，而且幻觉总是和真实内容混在同一回复里。以往按整条回复做事实性偏好学习，训练过程中难免带入噪声。
- **关键词：** DPO, preference-optimization, alignment

### MathCoder2: Better Math Reasoning from Continued Pretraining on Model-translated Mathematical Code

- **作者：** Zimu Lu, Aojun Zhou, Ke Wang, Houxing Ren, Weikang Shi, Junting Pan, Mingjie Zhan, Hongsheng Li
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=1Iuw1jcIrf
- **中文提要：** 代码的精确性有助于增强大模型的数学推理。既有数学继续预训练所包含的代码，却多用数学相关软件包去服务工程、机器学习、信号处理或模块测试。
- **关键词：** continued-pretraining

### MAVIS: Mathematical Visual Instruction Tuning with an Automatic Data Engine

- **作者：** Renrui Zhang, Xinyu Wei, Dongzhi Jiang, Ziyu Guo, Yichi Zhang, Chengzhuo Tong, Jiaming Liu, Aojun Zhou, Shanghang Zhang, Gao Peng, Hongsheng Li
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=MnJzJ2gvuf
- **中文提要：** 多模态大模型在一般视觉场景中已经表现出色，数学能力仍有三处待补：数学图示的视觉编码、图与语言的对齐，以及思维链推理。
- **关键词：** DPO, instruction-tuning, preference-optimization, alignment, fine-tuning

### Measuring memorization in RLHF for code completion

- **作者：** Jamie Hayes, I Shumailov, Billy Porter, Aneesh Pappu
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Tg8RLxpMDu
- **中文提要：** 微调数据的记忆已有不少研究，RLHF 对齐过程会怎样影响或引入记忆却不清楚。弄清这一点很重要，因为真实用户数据可能被收集并用于对齐大模型。
- **关键词：** DPO, RLHF, preference-optimization, reward-model, alignment, fine-tuning

### Merging LoRAs like Playing LEGO: Pushing the Modularity of LoRA to Extremes Through Rank-Wise Clustering

- **作者：** Ziyu Zhao, tao shen, Didi Zhu, Zexi Li, Jing Su, Xuwu Wang, Fei Wu
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=j6fsbpAllN
- **中文提要：** 凭借模块化设计以及在 Hugging Face 等平台上的广泛可得，LoRA 成为把大模型微调到不同领域的常用技术。这种模块化也促使人们把多个 LoRA 组合起来，以增强模型能力。
- **关键词：** LoRA, fine-tuning

### MeteoRA: Multiple-tasks Embedded LoRA for Large Language Models

- **作者：** Jingwei Xu, Junyu Lai, Yunpeng Huang
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=yOOJwR15xg
- **中文提要：** 预训练再微调，是把大模型部署到各类下游应用的基础范式。在这一框架中，LoRA 以 PEFT 的方式产生大量可复用的任务专用适配器。
- **关键词：** LoRA, PEFT, fine-tuning

### MIA-Bench: Towards Better Instruction Following Evaluation of Multimodal LLMs

- **作者：** Yusu Qian, Hanrong Ye, Jean-Philippe Fauconnier, Peter Grasch, Yinfei Yang, Zhe Gan
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=7EhS3YBxjY
- **中文提要：** 评测多模态大模型，是理解其能力与局限的前提。MIA-Bench 专门考察这些模型能否严格遵守复杂指令。
- **关键词：** DPO, SFT, instruction-following, preference-optimization, fine-tuning

### MIA-DPO: Multi-Image Augmented Direct Preference Optimization For Large Vision-Language Models

- **作者：** Ziyu Liu, Yuhang Zang, Xiaoyi Dong, Pan Zhang, Yuhang Cao, Haodong Duan, Conghui He, Yuanjun Xiong, Dahua Lin, Jiaqi Wang
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=f7WBRSuf9l
- **中文提要：** 视觉偏好对齐要训练大型视觉语言模型，在视觉输入之间预测人类偏好，通常依靠标注的选择/拒绝样本对以及 DPO 等算法。现有方法主要按单图场景设计，一离开这一设定就难以应对。
- **关键词：** DPO, preference-optimization, alignment

### Mitigating Reward Over-Optimization in RLHF via Behavior-Supported Regularization

- **作者：** Juntao Dai, Taiye Chen, Yaodong Yang, Qian Zheng, Gang Pan
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=PNMv4r7s1i
- **中文提要：** 用 RLHF 把大模型对齐到人类价值是有效的，奖励过优化却仍是开放难题。它会让模型在奖励模型下的表现偏离真实的人类目标。
- **关键词：** RLHF, reward-model, alignment

### MM1.5: Methods, Analysis & Insights from Multimodal LLM Fine-tuning

- **作者：** Haotian Zhang, Mingfei Gao, Zhe Gan, Philipp Dufter, Nina Wenzel, Forrest Huang, Dhruti Shah, Xianzhi Du, Bowen Zhang, Yanghao Li, Sam Dodge, Keen You, Zhen Yang, Aleksei Timofeev, Mingze Xu, Hong-You Chen, Jean-Philippe Fauconnier, Zhengfeng Lai, Haoxuan You, Zirui Wang, Afshin Dehghan, Peter Grasch, Yinfei Yang
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=HVtu26XDAA
- **中文提要：** MM1.5 是一系列新的多模态大模型，面向富文本图像理解、视觉指代与定位以及多图推理。它在 MM1 架构上采取以数据为中心的训练，系统考察整个训练周期里不同数据混合的影响。
- **关键词：** SFT, instruction-tuning, continued-pretraining, fine-tuning

### Model Editing as a Robust and Denoised variant of DPO: A Case Study on Toxicity

- **作者：** Rheeya Uppaal, Apratim Dey, Yiting He, Yiqiao Zhong, Junjie Hu
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=lOi6FtIwR8
- **中文提要：** 为提升安全性，DPO 等对齐算法训练大模型去匹配偏好数据所体现的人类行为。这些方法计算开销大，可控性和透明度也不足，因而难以广泛使用。
- **关键词：** DPO, preference-optimization, alignment

### More RLHF, More Trust? On The Impact of Preference Alignment On Trustworthiness

- **作者：** Aaron J. Li, Satyapriya Krishna, Hima Lakkaraju
- **会议：** ICLR 2025 · Main · Oral
- **官方论文页：** https://openreview.net/forum?id=2025-Oral--4767-82bde516
- **中文提要：** 可信度衡量的是输出在多大程度上可靠、安全并符合伦理，其重要性已与认知表现并列。RLHF 虽被广泛用于按标注的人类偏好做对齐，它对可信度究竟有何影响仍未说完。
- **关键词：** RLHF, preference-optimization, alignment, fine-tuning

### MoS: Unleashing Parameter Efficiency of Low-Rank Adaptation with Mixture of Shards

- **作者：** Sheng Wang, Liheng Chen, Pengan CHEN, Jingwei DONG, Boyang XUE, Jiyue Jiang, Lingpeng Kong, Chuan Wu
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=1uLW9eYNJB
- **中文提要：** 大模型快速放大后，众多定制模型同时服务会带来剧烈的显存开销，微调必须更轻。面向更省参数的 LoRA，参数共享是一条有希望的途径；对高层共享原则的考察表明，区分化不可或缺。
- **关键词：** LoRA, PEFT, fine-tuning

### MrSteve: Instruction-Following Agents in Minecraft with What-Where-When Memory

- **作者：** Junyeong Park, Junmo Cho, Sungjin Ahn
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=CjXaMI2kUH
- **中文提要：** 借助大模型增强的分层方法，Minecraft 等环境中的通用具身智能已有明显进展。高层规划器加低层控制器虽有潜力，低层控制器却常因反复失败成为性能瓶颈。
- **关键词：** instruction-following

### MTSAM: Multi-Task Fine-Tuning for Segment Anything Model

- **作者：** Xuehao Wang, Zhan ZHUANG, Feiyang YE, Yu Zhang
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=6N4QMbeVaO
- **中文提要：** SAM 凭借突出的零样本能力，有潜力成为多任务学习的基础模型。迁到多任务时却有两处障碍：难以生成通道数不同的任务专用输出，以及如何同时微调以适应多个下游任务仍未解决。
- **关键词：** LoRA, fine-tuning

### Multiagent Finetuning: Self Improvement with Diverse Reasoning Chains

- **作者：** Vighnesh Subramaniam, Yilun Du, Joshua B Tenenbaum, Antonio Torralba, Shuang Li, Igor Mordatch
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=JtGPIZpOrz
- **中文提要：** 近年来大模型表现突出，根本上仍受训练数据限制。为超出这些数据，已有工作探索让模型生成合成数据，从而实现自主的自我改进。
- **关键词：** fine-tuning

### Multi-objective antibody design with constrained preference optimization

- **作者：** Milong Ren, ZaiKai He, Haicang Zhang
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=4ktJJBvvUd
- **中文提要：** 抗体设计对癌症和病毒感染等疾病的疗法开发至关重要。深度生成模型已经显著推进计算抗体设计，尤其是增强与目标抗原的结合亲和力。
- **关键词：** preference-optimization, fine-tuning

### Multiview Equivariance Improves 3D Correspondence Understanding with Minimal Feature Finetuning

- **作者：** Yang You, Yixin Li, Congyue Deng, Yue Wang, Leonidas Guibas
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=CNO4rbSV6v
- **中文提要：** ViT 一族视觉基础模型以丰富的语义特征改变了图像理解。它们在二维理解上的成功并不说明已经把握三维空间关系；这项工作评估并增强基于 ViT 的模型的三维感知。
- **关键词：** fine-tuning

### Neural ODE Transformers: Analyzing Internal Dynamics and Adaptive Fine-tuning

- **作者：** Anh Tong, Thanh Nguyen-Tang, Dongeun Lee, Duc Nguyen, Toan Tran, David Hall, Cheongwoong Kang, Jaesik Choi
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=XnDyddPcBT
- **中文提要：** Transformer 大模型的内部运作正受到越来越多的关注。这里用高度灵活的非自治神经常微分方程来建模 Transformer 架构。
- **关键词：** fine-tuning

### No Preference Left Behind: Group Distributional Preference Optimization

- **作者：** Binwei Yao, Zefan Cai, Yun-Shiuan Chuang, Shanglin Yang, Ming Jiang, Diyi Yang, Junjie Hu
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=bgpNJBD6Va
- **中文提要：** 一群人的偏好并不是单一值，而是服从某个分布。DPO 等对齐方法试图让模型反映人类偏好，却难以捕捉群体内部这种呈分布的多元偏好。
- **关键词：** DPO, preference-optimization, alignment

### On a Connection Between Imitation Learning and RLHF

- **作者：** Teng Xiao, Yige Yuan, Mingxiao Li, Zhengyu Chen, Vasant Honavar
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=2QdsjiNXgj
- **中文提要：** 从模仿学习的视角研究用偏好数据对齐大模型。理论上，RLHF 与模仿学习联系紧密：前者实际上是在偏好数据分布上做模仿学习。
- **关键词：** RLHF, alignment

### Online Preference Alignment for Language Models via Count-based Exploration

- **作者：** Chenjia Bai, Yang Zhang, Shuang Qiu, Qiaosheng Zhang, Kang Xu, Xuelong Li
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=cfKZ5VrhXt
- **中文提要：** RLHF 在把大模型微调到人类偏好方面潜力很大。现有做法多在固定数据集上做偏好对齐，数据覆盖有限，得到的奖励模型也难以泛化到分布外回复。
- **关键词：** DPO, RLHF, instruction-following, preference-optimization, reward-model, alignment, fine-tuning

### On-the-fly Preference Alignment via Principle-Guided Decoding

- **作者：** Mingye Zhu, Yi Liu, Lei Zhang, Junbo Guo, Zhendong Mao
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=cfn2O1qvxp
- **中文提要：** 大模型版图迅速扩大，把生成结果对齐到人类价值与偏好越来越重要。以人类反馈强化学习为代表的流行对齐方法，已经能以更强的控制来引导模型。
- **关键词：** RLHF, preference-optimization, alignment, fine-tuning

### OpenPRM: Building Open-domain Process-based Reward Models with Preference Trees

- **作者：** Kaiyan Zhang, Jiayuan Zhang, Haoxin Li, Xuekai Zhu, Ermo Hua, Xingtai Lv, Ning Ding, Biqing Qi, Bowen Zhou
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=fGIqGfmgkW
- **中文提要：** 扩大推理时的计算量，正被视为大模型缩放定律的下一前沿。数学和编程方面的已有工作，已经显示出推理时缩放的可观潜力。
- **关键词：** instruction-following, reward-model

### Open Problems and Fundamental Limitations of Reinforcement Learning from Human Feedback

- **作者：** Javier Rando, Tony Wang, Stewart Slocum, Dmitrii Krasheninnikov, Usman Anwar, Micah Carroll, Xander Davies, Claudia Shi, Thomas Gilbert, Rachel Freedman, Charbel-Raphael Segerie, Phillip Christoffersen, Jacob Pfau, Tomek Korbak, Xin Chen, Lauro Langosco, Samuel Marks, Erdem Bıyık, Dorsa Sadigh, David Krueger, Pedro Freire, Mehul Damani, Jérémy Scheurer, David Lindner, Anca Dragan, Anand Siththaranjan, Dylan Hadfield-Menell, Max Nadeau, Stephen Casper, Peter Hase 等（共 32 人）
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://iclr.cc/virtual/2025/poster/31506
- **中文提要：** 作为一种让 AI 系统对齐人类目标的训练技术，RLHF 已成为微调前沿大模型的核心方法。
- **关键词：** RLHF, fine-tuning

### PaCA: Partial Connection Adaptation for Efficient Fine-Tuning

- **作者：** Sunghyeon Woo, Sol Namkung, SunWoo Lee, Inho Jeong, Beomseok Kim, Dongsuk Jeon
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=iYkhxre0In
- **中文提要：** 以往 PEFT 只训练少量额外的适配器参数，而不是整个大网络，从而降低显存和计算成本。计算成本降下来，训练时间却不一定缩短，尽管适配器层本身的计算量要小得多。
- **关键词：** instruction-tuning, LoRA, PEFT, fine-tuning

### PAL: Sample-Efficient Personalized Reward Modeling for Pluralistic Alignment

- **作者：** Daiwei Chen, Yi Chen, Aniket Rege, Zhi Wang, Ramya Vinayak
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=1kFDrYCuSu
- **中文提要：** 互联网规模数据上训练的基础模型，在部署前受益于充分的人类偏好对齐。现有方法通常假设所有人共享同一种偏好，忽略了人类价值固有的多样性。
- **关键词：** reward-model, alignment

### Param$\Delta$ for Direct Mixing: Post-Train Large Language Model At Zero Cost

- **作者：** Sheng Cao, Mingrui Wu, Karthik Prasad, Yuandong Tian, Zechun Liu
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=vqbd2OQnGp
- **中文提要：** 后训练对指令遵循、推理以及与人类偏好对齐都不可少。它却需要大量高质量数据，并伴随过拟合等风险；每次基座模型更新后还要重复后训练和评估，计算代价很高。
- **关键词：** instruction-following, post-training, alignment

### Personality Alignment of Large Language Models

- **作者：** Minjun Zhu, Yixuan Weng, Linyi Yang, Yue Zhang
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=0DZEs8NpUH
- **中文提要：** 对齐大模型通常旨在反映普遍的人类价值与行为，却往往抓不住单个用户的独特特点与偏好。针对这一缺口，提出了人格对齐这一概念。
- **关键词：** DPO, alignment

### Personalized Visual Instruction Tuning

- **作者：** Renjie Pi, Jianshu Zhang, Tianyang Han, Jipeng Zhang, Rui Pan, Tong Zhang
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=sAxdIJ4l6z
- **中文提要：** 多模态大模型进步明显，却存在一种被称为“脸盲”的局限：可以进行一般对话，却无法针对特定个人开展个性化对话。这妨碍了它们在个性化场景中的应用。
- **关键词：** instruction-tuning, fine-tuning

### Preference Optimization for Reasoning with Pseudo Feedback

- **作者：** Fangkai Jiao, Geyang Guo, Xingxing Zhang, Nancy F Chen, Shafiq Joty, Furu Wei
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=jkUp3lybXf
- **中文提要：** 在监督微调之后，DPO 等偏好优化常被用来增强大模型在数学推理和编程等领域的推理能力。构造偏好对依赖高质量标签，而所需推理数据集的可得性仍是未写完的前提。
- **关键词：** DPO, SFT, preference-optimization, fine-tuning

### Preserving Diversity in Supervised Fine-Tuning of Large Language Models

- **作者：** Ziniu Li, Congliang Chen, Tian Xu, Zeyu Qin, Jiancong Xiao, Zhi-Quan Luo, Ruoyu Sun
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=NQEe7B7bSw
- **中文提要：** 大模型专攻下游任务时通常依赖 SFT，交叉熵损失几乎是默认选择。交叉熵只最大化已观测数据的似然，并不计入其他可能的输出。
- **关键词：** SFT, fine-tuning

### Process Reward Model with Q-value Rankings

- **作者：** Wendi Li, Yixuan Li
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=wQEdh2cgEk
- **中文提要：** 在中间步骤的对错会显著影响最终结果的复杂推理和决策中，过程奖励建模很关键。现有做法多把它当作分类问题，用交叉熵损失独立判断每一步是否正确。
- **关键词：** PRM, reward-model

### Progress or Regress? Self-Improvement Reversal in Post-training

- **作者：** Ting Wu, Xuefeng Li, Pengfei Liu
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=RFqeoVfLHa
- **中文提要：** 迭代偏好学习等后训练自我改进，被认为能在没有人工介入的情况下增强大模型的解题能力，例如数学推理。随着探索深入，需要审视这些提升究竟是全面进步，还是会带来意外后果。
- **关键词：** post-training

### Q-SFT: Q-Learning for Language Models via Supervised Fine-Tuning

- **作者：** Joey Hong, Anca Dragan, Sergey Levine
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=v4MTnPiYXY
- **中文提要：** 基于价值的强化学习原则上可以学会多种多轮问题的有效策略，从游戏、对话到机器人控制，也包括利用先前收集的静态数据做离线学习。策略梯度虽已广泛用于问答等单轮任务，多轮场景中的价值方法仍待展开。
- **关键词：** RFT, SFT, fine-tuning

### Quantum-PEFT: Ultra parameter-efficient fine-tuning

- **作者：** Toshiaki Koike-Akino, Francesco Tonin, Yongtao Wu, Frank Zhengqing Wu, Leyla Naz Candogan, Volkan Cevher
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=dgR6i4TSng
- **中文提要：** Quantum-PEFT 借助量子计算实现参数高效微调。与 LoRA 等加性 PEFT 不同，它利用一种底层的量子酉参数化：该参数化是满秩的，参数量却仍然很少。
- **关键词：** LoRA, PEFT, fine-tuning

### RAFT: Reward rAnked FineTuning for Generative Foundation Model Alignment

- **作者：** Jipeng Zhang, Hanze Dong, Tong Zhang, Wei Xiong, Deepanshu Goyal, Yihan Zhang, Winnie Chow, KaShun SHUM, Shizhe Diao, Rui Pan
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://iclr.cc/virtual/2025/poster/31508
- **中文提要：** 大规模无监督训练数据会给生成式基础模型带上隐性偏差。这些偏差可能产生次优样本、偏斜的结果和不公平，后果有时很严重。
- **关键词：** RLHF, reward-model, alignment, fine-tuning

### RainbowPO: A Unified Framework for Combining Improvements in Preference Optimization

- **作者：** Hanyang Zhao, Genta Winata, Anirban Das, Shi-Xiong Zhang, David Yao, Wenpin Tang, Sambit Sahu
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=trKee5pIFv
- **中文提要：** DPO 家族近来出现了许多作为扩展的偏好优化算法。它们虽然成功地把模型对齐到人类偏好，额外组件各自贡献了什么却仍缺乏理解。
- **关键词：** DPO, preference-optimization

### RandLoRA: Full rank parameter-efficient fine-tuning of large models

- **作者：** Paul Albert, Frederic Zhang, Hemanth Saratchandran, Cristian Rodriguez-Opazo, Anton Hengel, Ehsan Abbasnejad
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Hn5eoTunHN
- **中文提要：** LoRA 及其变体明显减少了大型 Transformer 的可训练参数和显存需求，同时维持微调表现。权重更新本身是低秩的，这限制了微调后模型的表示能力，复杂任务上的表现可能因此受损。
- **关键词：** LoRA, PEFT, fine-tuning

### RaSA: Rank-Sharing Low-Rank Adaptation

- **作者：** Zhiwei He, Zhaopeng Tu, Xing Wang, Xingyu Chen, Zhijie Wang, Jiahao Xu, Tian Liang, Wenxiang Jiao, Zhuosheng Zhang, Rui Wang
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=GdXI5zCoAt
- **中文提要：** 大模型的参数高效微调广泛采用 LoRA。低秩约束限制了表达能力，这一瓶颈在代码生成和数学推理这类要求严格的任务上尤为突出。
- **关键词：** LoRA, PEFT, fine-tuning

### Reconstructive Visual Instruction Tuning

- **作者：** Haochen Wang, Anlin Zheng, Yucheng Zhao, Tiancai Wang, Zheng Ge, Xiangyu Zhang, Zhaoxiang Zhang
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=8q9NOMzRDg
- **中文提要：** 重构式视觉指令微调（ROSS）是一类依靠以视觉为中心的监督信号的大型多模态模型。常规做法只监督文本输出，ROSS 则让模型通过重建输入图像来监督视觉输出。
- **关键词：** instruction-tuning

### Regressing the Relative Future: Efficient Policy Optimization for Multi-turn RLHF

- **作者：** Zhaolin Gao, Wenhao Zhan, Jonathan Chang, Gokul Swamy, Kianté Brantley, Jason Lee, Wen Sun
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=cVyELMpMRS
- **中文提要：** 摘要这类只需单轮交互的任务上，大模型已经很成功。对话等多轮任务需要长期规划，模型仍然容易吃力。
- **关键词：** DPO, RLHF, fine-tuning

### Re-Imagining Multimodal Instruction Tuning: A Representation View

- **作者：** Yiyang Liu, James Liang, Ruixiang Tang, Yugyung Lee, MAJID RABBANI, Sohail Dianat, Raghuveer Rao, Lifu Huang, Dongfang Liu, Qifan Wang, Cheng Han
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=zxg6601zoc
- **中文提要：** 用指令跟随数据微调预训练的大型多模态模型，多模态指令微调已被证明有助于零样本泛化。模型规模继续增大后，全量微调的参数开销变得很高。
- **关键词：** instruction-tuning, instruction-following, PEFT, fine-tuning

### Relaxed Recursive Transformers: Effective Parameter Sharing with Layer-wise LoRA

- **作者：** Sangmin Bae, Adam Fisch, Hrayr Harutyunyan, Ziwei Ji, Seungyeon Kim, Tal Schuster
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=WwpYSOkkCt
- **中文提要：** 部署大模型的代价很高。参数共享有望减小规模和成本，但它在现代大模型中的效果仍然相当有限。
- **关键词：** LoRA

### Rethinking Reward Model Evaluation: Are We Barking up the Wrong Tree?

- **作者：** xueru wen, Jie Lou, Yaojie Lu, Hongyu Lin, XingYu, Xinyu Lu, Ben He, Xianpei Han, Debing Zhang, Le Sun
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Cnwz9jONi5
- **中文提要：** 奖励模型是把语言模型对齐到人类偏好的关键，目前多靠在人工标注的偏好验证集上测准确率来评测。这一做法直接且常用，准确率与下游策略表现的关系却仍不清楚；该项工作在合成设定中做了实验。
- **关键词：** reward-model, alignment

### Rethinking Reward Modeling in Preference-based Large Language Model Alignment

- **作者：** Hao Sun, Yunyi Shen, Jean-Francois Ton
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=rfdblE10qm
- **中文提要：** 奖励建模里，Bradley-Terry 模型是把成对回复比较转换成奖励值并做预测的常见成功做法。它原本用于多人随机博弈的匹配，为何能被这样借用，原因仍不清楚。
- **关键词：** reward-model, alignment

### REvolve: Reward Evolution with Large Language Models using Human Feedback

- **作者：** RISHI HAZRA, Alkis Sygkounas, Andreas Persson, Amy Loutfi, Pedro Zuidberg Dos Martires
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=cJPUpL8mOw
- **中文提要：** 训练强化学习算法离不开有效的奖励函数。由于某些任务主观、难以显式量化，即便领域专家也很难把奖励设计出来。
- **关键词：** instruction-tuning

### RMB: Comprehensively benchmarking reward models in LLM alignment

- **作者：** Enyu Zhou, Guodong Zheng, Binghai Wang, Zhiheng Xi, Shihan Dou, Rong Bao, Wei Shen, Limao Xiong, Jessica Fan, Yurong Mou, Rui Zheng, Tao Gui, Qi Zhang, Xuanjing Huang
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=kmgrlG9TR0
- **中文提要：** 奖励模型把大模型的对齐导向人类更偏好的行为。要把对齐做得更好，关键在于如何评测这些奖励模型。
- **关键词：** reward-model, alignment

### RM-Bench: Benchmarking Reward Models of Language Models with Subtlety and Style

- **作者：** Yantao Liu, Zijun Yao, Rui Min, Yixin Cao, Lei Hou, Juanzi Li
- **会议：** ICLR 2025 · Main · Oral
- **官方论文页：** https://openreview.net/forum?id=2025-Oral--13985-6ab6c0d8
- **中文提要：** 在 RLHF 和推理缩放中，奖励模型负责引导语言模型对齐并挑选更优回复。现有基准却常常只要求模型区分由能力强弱不同的模型所生成的回复。
- **关键词：** RLHF, reward-model, alignment

### RRM: Robust Reward Model Training Mitigates Reward Hacking

- **作者：** Tianqi Liu, Wei Xiong, Jie Ren, Lichang Chen, Junru Wu, Rishabh Joshi, Yang Gao, Jiaming Shen, Zhen Qin, Tianhe Yu, Daniel Sohn, Anastasia Makarova, Jeremiah Zhe Liu, Yuan Liu, Bilal Piot, Abe Ittycheriah, Aviral Kumar, Mohammad Saleh
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=88AS5MQnmC
- **中文提要：** 奖励模型在把大语言模型对齐到人类偏好时处于关键位置，但传统训练依赖绑定特定提示的回复对，很难把提示驱动的偏好与回复长度、格式这类与提示无关的痕迹分开。RRM 针对这种混淆来训练更稳健的奖励模型。
- **关键词：** DPO, reward-model, alignment

### SaLoRA: Safety-Alignment Preserved Low-Rank Adaptation

- **作者：** Mingjie Li, Wai Man Si, Michael Backes, Yang Zhang, Yisen Wang
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=GOoVzE9nSj
- **中文提要：** 个性化需求上升后，LoRA 等 PEFT 方法因能降低计算成本而变得必要，但近期研究警告，LoRA 微调可能破坏大语言模型已有的安全对齐并带来明显风险。SaLoRA 关注在低秩适应中保住这份安全对齐。
- **关键词：** LoRA, PEFT, alignment, fine-tuning

### Scaling Autonomous Agents via Automatic Reward Modeling And Planning

- **作者：** Zhenfang Chen, Delin Chen, Rui Sun, Wenjun Liu, Chuang Gan
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=womU9cEwcO
- **中文提要：** 大语言模型在各类文本生成上已经很强，却仍不擅长需要多步决策和环境反馈的问题，例如网购、科学推理和数学解题。把自主智能体做大的途径被放在自动奖励建模与规划上。
- **关键词：** reward-model, fine-tuning

### Scaling Instruction-tuned LLMs to Million-token Contexts via Hierarchical Synthetic Data Generation

- **作者：** Linda He, Jue Wang, Maurice Weber, Shang Zhu, Ben Athiwaratkun, Ce Zhang
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=BkwCrIsTbR
- **中文提要：** 长上下文推理同时受困于序列变长带来的二次计算复杂度，以及长上下文标注既稀缺又昂贵。开源工作里几乎没有对长上下文数据的系统消融，也缺少上下文极长的公开指令微调数据；分层合成数据被用来把指令微调模型扩展到百万词元级上下文。
- **关键词：** instruction-tuning, post-training

### SD-LoRA: Scalable Decoupled Low-Rank Adaptation for Class Incremental Learning

- **作者：** Yichen Wu, Hongming Piao, Long-Kai Huang, Renzhen Wang, Wanhua Li, Hanspeter Pfister, Deyu Meng, Kede Ma, Ying Wei
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=5U1rlpX68A
- **中文提要：** 用基础模型做持续学习时，现有基于提示或 LoRA 的方法往往要不断扩大提示或 LoRA 池，或留存以往任务的样本，任务一多就难以扩展。SD-LoRA 以可扩展的解耦低秩适应处理类别增量学习。
- **关键词：** LoRA

### SEAL: Safety-enhanced Aligned LLM Fine-tuning via Bilevel Data Selection

- **作者：** Han Shen, Pin-Yu Chen, Payel Das, Tianyi Chen
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=VHguhvcoM5
- **中文提要：** 在任务数据上微调能提升下游表现，但已有研究表明，在少量对抗样本甚至良性数据上微调，也可能严重削弱模型预先具备的对齐与安全能力。SEAL 借助双层数据选择，在微调中加强安全对齐。
- **关键词：** alignment, fine-tuning

### Second-Order Fine-Tuning without Pain for LLMs: A Hessian Informed Zeroth-Order Optimizer

- **作者：** Yanjun Zhao, Sizhe Dang, Haishan Ye, Guang Dai, Yi Qian, Ivor Tsang
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=bEqI61iBue
- **中文提要：** 下游任务需要微调大语言模型，但经典一阶优化器因反向传播而占用过高显存。MeZO 等零阶优化器改用前向传播来降低显存，这里进一步引入 Hessian 信息，做负担更轻的二阶微调。
- **关键词：** fine-tuning

### Selective Aggregation for Low-Rank Adaptation in Federated Learning

- **作者：** Pengxin Guo, Shuang Zeng, Yanran Wang, Huijie Fan, Feifei Wang, Liangqiong Qu
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=iX3uESGdsO
- **中文提要：** 作者从学到的 A、B 矩阵不对称性考察联邦学习中的 LoRA，发现 A 矩阵负责通用知识，B 矩阵更专注客户端特有知识。选择性聚合顺着这一分工来做低秩适应。
- **关键词：** LoRA

### Self-Boosting Large Language Models with Synthetic Preference Data

- **作者：** Qingxiu Dong, Li Dong, Xingxing Zhang, Zhifang Sui, Furu Wei
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=7visV100Ms
- **中文提要：** 与人类偏好对齐后，大语言模型在诚实、无害且有帮助的回复上进步明显，但收集高质量偏好数据既耗资源又很考验创造力，持续改进时尤其如此。合成偏好数据被用来让模型自我提升。
- **关键词：** instruction-following, alignment

### Self-Improving Robust Preference Optimization

- **作者：** Eugene Choi, Arash Ahmadian, Matthieu Geist, Olivier Pietquin, Mohammad Gheshlaghi Azar
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=ZSdubdbOoi
- **中文提要：** 在线与离线 RLHF（如 PPO 和 DPO）在对齐人类偏好上很成功，却存在根本局限：经 RLHF 训练的模型会通过强化学习机制或对比损失，在训练中从错误或负例里学习。后续讨论转向更稳健、可自我改进的偏好优化。
- **关键词：** DPO, RLHF, preference-optimization, alignment

### Self-Play Preference Optimization for Language Model Alignment

- **作者：** Yue Wu, Zhiqing Sun, Rina Hughes, Kaixuan Ji, Yiming Yang, Quanquan Gu
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=a3PmRgAB5T
- **中文提要：** 依赖 Bradley-Terry 等参数模型的标准 RLHF，难以捕捉人类偏好中的不可传递性与非理性。直接使用偏好概率有望更准确地反映这些偏好，从而使语言模型对齐更灵活；自博弈偏好优化沿这条思路展开。
- **关键词：** DPO, RLHF, preference-optimization, alignment, fine-tuning

### Self-play with Execution Feedback: Improving Instruction-following Capabilities of Large Language Models

- **作者：** Guanting Dong, Keming Lu, Chengpeng Li, Tingyu Xia, Bowen Yu, Chang Zhou, Jingren Zhou
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=cRR0oDFEBC
- **中文提要：** 遵循自然语言指令是大语言模型的核心能力，但如何不靠人工标注、自动构造高质量数据来增强复杂指令遵循，仍然没有解决。带执行反馈的自博弈被用来改进这项能力。
- **关键词：** DPO, RLHF, SFT, instruction-following, alignment, fine-tuning

### SimPER: A Minimalist Approach to Preference Alignment without Hyperparameters

- **作者：** Teng Xiao, Yige Yuan, Zhengyu Chen, Mingxiao Li, Shangsong Liang, Zhaochun Ren, Vasant Honavar
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=jfwe9qNqRi
- **中文提要：** 现有偏好优化目标要额外引入超参并大量调参，才能把大语言模型对齐好，微调的复杂度和耗时都因此上升。SimPER 给出一种简单、且不含超参的偏好对齐算法。
- **关键词：** preference-optimization, alignment, fine-tuning

### SMT: Fine-Tuning Large Language Models with Sparse Matrices

- **作者：** Haoze He, Juncheng Li, Xuan Jiang, Heather Miller
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=GbgCRJedQ7
- **中文提要：** LoRA 及其变体等 PEFT 方法因能降低计算成本而流行，但它们与全量微调之间常常存在精度差距，这一差距尚未被系统考察。SMT 改为用稀疏矩阵微调大语言模型。
- **关键词：** LoRA, PEFT, fine-tuning

### SPaR: Self-Play with Tree-Search Refinement to Improve Instruction-Following in Large Language Models

- **作者：** Jiale Cheng, Xiao Liu, Cunxiang Wang, Xiaotao Gu, Yida Lu, Dan Zhang, Yuxiao Dong, Jie Tang, Hongning Wang, Minlie Huang
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=9chRqsPOGL
- **中文提要：** 指令遵循要求模型识别指令里极细微的要求并准确反映到输出中，偏好学习很适合优化这种能力。现有方法构造偏好对时往往直接独立采样多条回复，SPaR 则用带树搜索精炼的自博弈来改进指令遵循。
- **关键词：** instruction-following

### Spread Preference Annotation: Direct Preference Judgment for Efficient LLM Alignment

- **作者：** Dongyoung Kim, Kimin Lee, Jinwoo Shin, Jaehyung Kim
- **会议：** ICLR 2025 · Main · Oral
- **官方论文页：** https://openreview.net/forum?id=2025-Oral--12928-d445222a
- **中文提要：** 对齐人类偏好已成为取得强表现的关键环节，但构建大规模人工标注偏好数据代价很高。SPA 以直接偏好判断做偏好标注的扩散，试图只依靠很少的人工标注来推动大语言模型对齐。
- **关键词：** reward-model, alignment

### STAFF: Speculative Coreset Selection for Task-Specific Fine-tuning

- **作者：** Xiaoyu Zhang, Juan Zhai, Shiqing Ma, Chao Shen, Tianlin Li, Weipeng Jiang, Yang Liu
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=FAfxvdv1Dy
- **中文提要：** 任务专用微调对部署大语言模型必不可少，却很耗计算资源和时间。已有核心集选择虽想提高数据效率、减轻训练开销，但在高剪枝率下会漏掉有价值样本并拉低核心集表现；STAFF 用推测式核心集选择来做任务专用微调。
- **关键词：** fine-tuning

### SV-RAG: LoRA-Contextualizing Adaptation of MLLMs for Long Document Understanding

- **作者：** Jian Chen, Ruiyi Zhang, Yufan Zhou, Tong Yu, Franck Dernoncourt, Jiuxiang Gu, Ryan Rossi, Changyou Chen, Tong Sun
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=FDaHjwInXO
- **中文提要：** 多模态大语言模型已较擅长富文本图像，但对复杂、多页且视觉信息密集的文档仍然吃力：解析器式检索增强受性能与效率限制，把所有页面直接输入在长文档上也不经济。SV-RAG 通过 LoRA 情境化适应来理解这类长文档。
- **关键词：** LoRA

### Synthetic continued pretraining

- **作者：** Zitong Yang, Neil Band, Shuangping Li, Emmanuel Candes, Tatsunori Hashimoto
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=07yvxWDSla
- **中文提要：** 大规模非结构化互联网文本上的预训练让语言模型学到大量世界知识，但学到一个事实需要许多不同表述，数据效率不高。把预训练模型适配到规模较小的领域文档时，这种低效成为挑战，合成持续预训练针对这一问题。
- **关键词：** continued-pretraining

### T2V-Turbo-v2: Enhancing Video Model Post-Training through Data, Reward, and Conditional Guidance Design

- **作者：** Jiachen Li, Qian Long, Jian (Skyler) Zheng, Xiaofeng Gao, Robinson Piramuthu, Wenhu Chen, William Wang
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=BZwXMqu4zG
- **中文提要：** 后训练阶段的重点是增强基于扩散的文生视频模型，从预训练文生视频模型蒸馏出能力较强的一致性模型。T2V-Turbo-v2 把高质量训练数据、奖励模型反馈和条件引导等监督信号整合进这一一致性蒸馏。
- **关键词：** reward-model, post-training, alignment

### Taming Overconfidence in LLMs: Reward Calibration in RLHF

- **作者：** Jixuan Leng, Chengsong Huang, Banghua Zhu, Jiaxin Huang
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=l0tg0jzsdL
- **中文提要：** 校准衡量的是模型置信度与回复实际表现是否相符。先前工作已表明大语言模型存在过度自信，RLHF 还会让输出概率更尖锐、过度自信加重；本研究继续追究 RLHF 的这一倾向，并从奖励校准入手。
- **关键词：** RLHF, reward-model, alignment

### TaskGalaxy: Scaling Multi-modal Instruction Fine-tuning with Tens of Thousands Vision Task Types

- **作者：** Jiankang Chen, Tianke Zhang, Changyi Liu, Haojie Ding, Yaya Shi, cheng.feng, Huihui Xiao, Bin Wen, Fan Yang, Tingting Gao, Di ZHANG
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=JXgnnUC0PH
- **中文提要：** 多模态视觉语言模型受益于架构、训练方法和高质量数据，在开放世界应用中越来越受关注，但任务专用数据不足常常限制表现，造成泛化差和输出偏差。TaskGalaxy 用大量视觉任务类型来扩展多模态指令微调。
- **关键词：** fine-tuning

### Teaching LLMs How to Learn with Contextual Fine-Tuning

- **作者：** Younwoo Choi, Muhammad Adil Asif, Ziwen Han, John Willes, Rahul G. Krishnan
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=FS2nukC2jv
- **中文提要：** 训练完成后，用提示或给出期望运作方式的上下文，能有效把大语言模型的输出引向人类想要的结果。在快速变化的领域里仍常需要微调，以更新记忆中的知识种类或加强新领域的开放式推理；上下文微调被用来教模型如何学习。
- **关键词：** instruction-tuning, fine-tuning

### The Crucial Role of Samplers in Online Direct Preference Optimization

- **作者：** Ruizhe Shi, Runlong Zhou, Simon Du
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=F6z3utfcYw
- **中文提要：** DPO 已成为稳定、可扩展且高效的语言模型对齐方案，但采样器如何影响其收敛速率等优化性质仍少有研究。文中在精确梯度设定下，严格分析不同采样策略对应的 DPO 收敛速率。
- **关键词：** DPO, RLHF, preference-optimization, alignment

### ThinkBot: Embodied Instruction Following with Thought Chain Reasoning

- **作者：** Guanxing Lu, Ziwei Wang, Changliu Liu, Jiwen Lu, Yansong Tang
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=tFDTHA3odg
- **中文提要：** 具身指令遵循要求智能体在复杂环境中与物体交互来完成人类指令。传统方法直接根据稀疏指令生成动作计划，却常因动作描述与指令脱节而达不到人类目标；ThinkBot 用思维链推理来做具身指令遵循。
- **关键词：** instruction-following

### TIS-DPO: Token-level Importance Sampling for Direct Preference Optimization With Estimated Weights

- **作者：** Aiwei Liu, Haoping Bai, Zhiyun Lu, Yanchao Sun, Xiang Kong, Xiaoming Wang, Jiulong Shan, Albin Madappally Jose, Xiaojiang Liu, Lijie Wen, Philip Yu, Meng Cao
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=oF6e2WwxX0
- **中文提要：** DPO 因简单有效而被广泛用于大语言模型的偏好对齐，但它把整条回复当作赌博机的一条臂，忽略词元之间的重要性差别，可能影响优化效率并难以得到更优结果。TIS-DPO 在词元级别做重要性采样，并用估计权重进行直接偏好优化。
- **关键词：** DPO, preference-optimization, alignment

### TLDR: Token-Level Detective Reward Model for Large Vision Language Models

- **作者：** Deqing Fu, Tong Xiao, Rui Wang, Wang Zhu, Pengchuan Zhang, Guan Pang, Robin Jia, Lawrence Chen
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=Zy2XgaGpDw
- **中文提要：** 奖励模型已经能改进多模态大语言模型，但奖励模型本身仍然粗糙、携带的信息很少。现有做法只是模仿人类标注，无论文本多长都只给一个反馈；TLDR 提出面向大型视觉语言模型的词元级侦探式奖励模型。
- **关键词：** reward-model

### TODO: Enhancing LLM Alignment with Ternary Preferences

- **作者：** Yuxiang Guo, Lu Yin, Bo Jiang, Jiaqi Zhang
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=utkGLDSNOk
- **中文提要：** 对齐人类意图对提升大语言模型在多种任务上的表现很关键，但 DPO 等标准技术常依赖二元 Bradley-Terry 模型，在标签有噪声、不一致或经常打平时很难抓住偏好的复杂性。TODO 改用三元偏好来增强对齐。
- **关键词：** DPO, preference-optimization, alignment

### Towards a Theoretical Understanding of Synthetic Data in LLM Post-Training: A Reverse-Bottleneck Perspective

- **作者：** Zeyu Gan, Yong Liu
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=UxkznlcnHf
- **中文提要：** 高质量且针对性强的数据稀缺，使合成数据成为大语言模型后训练的重要资源。生成方法已经很多，合成数据的实际效果与理论理解之间仍有明显空隙；反向瓶颈视角被用来理解后训练中的合成数据。
- **关键词：** post-training

### Towards Federated RLHF with Aggregated Client Preference for LLMs

- **作者：** Feijie Wu, Xiaoze Liu, Haoyu Wang, Xingchen Wang, Lu Su, Jing Gao
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=mqNKiEB6pd
- **中文提要：** RLHF 用用户偏好数据微调预训练大语言模型，使其生成更符合人类偏好的内容。出于隐私顾虑，用户往往不愿分享敏感偏好数据，因而需要走向聚合客户端偏好的联邦 RLHF。
- **关键词：** RLHF, fine-tuning

### Towards Robust Alignment of Language Models: Distributionally Robustifying Direct Preference Optimization

- **作者：** Junkang Wu, Yuexiang Xie, Zhengyi Yang, Jiancan Wu, Jiawei Chen, Jinyang Gao, Bolin Ding, Xiang Wang, Xiangnan He
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=CbfsKHiWEn
- **中文提要：** DPO 的训练数据存在噪声，这妨碍把大语言模型稳健地对齐到人类偏好。噪声被分为包含低质量数据点的逐点噪声，以及错误配对、会扰乱偏好排序的成对噪声，分布鲁棒化被用来加固 DPO。
- **关键词：** DPO, preference-optimization, alignment, fine-tuning

### TPO: Aligning Large Language Models with Multi-branch & Multi-step Preference Trees

- **作者：** Weibin Liao, Xu Chu, Yasha Wang
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=O0sQ9CPzai
- **中文提要：** 在数学推理等复杂任务上，近期工作用 DPO 抑制不受偏好的回复以增强长链推理，并让大语言模型经思维树生成偏好树再采样成对数据。TPO 把对齐建立在多分支、多步骤的偏好树上。
- **关键词：** DPO, preference-optimization, alignment, fine-tuning

### Train Small, Infer Large: Memory-Efficient LoRA Training for Large Language Models

- **作者：** Jun Zhang, Jue Wang, Huan Li, Shou, Ke Chen, Yang You, Guiming Xie, Xuejian Gong, Kunlong Zhou
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=s7DkcgpRxL
- **中文提要：** 大语言模型以出色的任务泛化推动了自然语言处理。LoRA 冻结原参数、只训练轻量低秩适配矩阵，从而以较低成本完成微调；进一步的目标是让这种训练更省显存，并做到小规模训练、大规模推理。
- **关键词：** LoRA, continued-pretraining, fine-tuning

### Uncertainty and Influence aware Reward Model Refinement for Reinforcement Learning from Human Feedback

- **作者：** Zexu Sun, Yiju Guo, Yankai Lin, Xu Chen, Qi Qi, Xing Tang, xiuqiang He, Ji-Rong Wen
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=iamWnRpMuQ
- **中文提要：** RLHF 已成为用人类偏好训练大语言模型的常用有效方法。其中学得的奖励模型近似人类偏好并指导策略优化，因此奖励模型是否准确十分关键；细化奖励模型时会同时考虑不确定性与影响力。
- **关键词：** RLHF, reward-model

### Unintentional Unalignment: Likelihood Displacement in Direct Preference Optimization

- **作者：** Noam Razin, Sadhika Malladi, Adithya Bhaskar, Danqi Chen, Sanjeev Arora, Boris Hanin
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=uaMSBJDnRv
- **中文提要：** DPO 及其变体越来越多地用于对齐人类偏好，设计目标是让偏好回复相对非偏好回复更常出现。已有观察却发现，训练过程中偏好回复的似然常常下降；这种现象被称为似然位移，并与非故意的失对齐联系在一起。
- **关键词：** DPO, preference-optimization, alignment

### Unleashing the Power of Task-Specific Directions in Parameter Efficient Fine-tuning

- **作者：** Chongjie Si, Zhiyi Shi, Shifan Zhang, Xiaokang Yang, Hanspeter Pfister, Wei Shen
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=RYrJqz44p4
- **中文提要：** 大语言模型在下游任务上表现出色，但全参数微调消耗大量资源。LoRA 等 PEFT 策略被用来减轻这一负担，任务特定方向在参数高效微调中的作用则被进一步挖掘。
- **关键词：** LoRA, PEFT, fine-tuning

### Unlocking Efficient, Scalable, and Continual Knowledge Editing with Basis-Level Representation Fine-Tuning

- **作者：** Tianci Liu, Ruirui Li, Yunzhe Qi, Hui Liu, Xianfeng Tang, Tianqi Zheng, Qingyu Yin, Monica Cheng, Jun Huan, Haoyu Wang, Jing Gao
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=PITFO1ddeh
- **中文提要：** 大语言模型在多种自然语言任务上表现出色，但训练于静态语料，知识在快速变化的世界里很容易过时。基级表示微调被用来寻求高效、可扩展且可持续的知识编辑。
- **关键词：** fine-tuning

### Unlocking the Power of Function Vectors for Characterizing and Mitigating Catastrophic Forgetting in Continual Instruction Tuning

- **作者：** Gangwei Jiang, caigao jiang, Zhaoyi Li, Siqiao Xue, JUN ZHOU, Linqi Song, Defu Lian, Ying Wei
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=gc8QAQfXv6
- **中文提要：** 灾难性遗忘指模型学习新任务时丢掉先前信息，是机器学习中的突出难题。能力已经很强的大语言模型在持续学习里仍会遇到它；函数向量被用来刻画并缓解持续指令微调中的这种遗忘。
- **关键词：** instruction-tuning

### Unveiling the Secret Recipe: A Guide For Supervised Fine-Tuning Small LLMs

- **作者：** Aldo Pareja, Nikhil Shivakumar Nayak, Hao Wang, Krishnateja Killamsetty, Shivchander Sudalairaj, Wenlong Zhao, Seungwook Han, Abhishek Bhandwaldar, Guangxuan Xu, Kai Xu, Ligong Han, Luke Inglis, Akash Srivastava
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=eENHKMTOfW
- **中文提要：** 工业实验室凭算力、专家团队和基础设施能够有效微调大语言模型，个人开发者和小型组织却因资源有限，难以充分探索实验空间。面向小型大语言模型的监督微调指南被用来缩小这一差距。
- **关键词：** SFT, instruction-tuning, fine-tuning

### Value-Incentivized Preference Optimization: A Unified Approach to Online and Offline RLHF

- **作者：** Shicong Cen, Jincheng Mei, Katayoon Goshvadi, Hanjun Dai, Tong Yang, Sherry Yang, Dale Schuurmans, Yuejie Chi, Bo Dai
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=SQnitDuow6
- **中文提要：** RLHF 在对齐大语言模型与人类偏好方面已显示出很大潜力。偏好数据是否可得，使在线与离线 RLHF 都仍是活跃方向；价值激励的偏好优化试图把这两条路线统一起来。
- **关键词：** DPO, RLHF, preference-optimization, reward-model, alignment

### Varying Shades of Wrong: Aligning LLMs with Wrong Answers Only

- **作者：** Jihan Yao, Wenxuan Ding, Shangbin Feng, Lucy Lu Wang, Yulia Tsvetkov
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=p74CpDzw1Y
- **中文提要：** 在困难任务和情境缺少充足可靠标注时，如何借助可能错误的答案拓展大语言模型的能力边界成为一个问题。其中要回答的一点是：模型能否在错误选项之间形成可靠偏好。
- **关键词：** preference-optimization, alignment, fine-tuning

### Video-STaR: Self-Training Enables Video Instruction Tuning with Any Supervision

- **作者：** Orr Zohar, Xiaohan Wang, Yonatan Bitton, Idan Szpektor, Serena Yeung
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=JYV2hrtFSv
- **中文提要：** 大型多模态模型的表现和推理能力取决于训练数据的规模与质量，而收集能支持思维链指令微调的数据非常困难。Video-STaR 借助自训练，使视频指令微调可以接受任意形式的监督。
- **关键词：** instruction-tuning, fine-tuning

### Weak-to-Strong Preference Optimization: Stealing Reward from Weak Aligned Model

- **作者：** Wenhong Zhu, Zhiwei He, Xiaofeng Wang, Pengfei Liu, Rui Wang
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=f7KxfUrRSb
- **中文提要：** 让语言模型对齐人类偏好，有助于更好满足多样的用户需求。弱到强泛化表明，用较弱模型生成的标签微调更强模型后，强模型可以稳定超过其弱监督者；这一想法被延伸到偏好优化与模型对齐。
- **关键词：** preference-optimization, alignment, fine-tuning

### Weighted-Reward Preference Optimization for Implicit Model Fusion

- **作者：** Ziyi Yang, Fanqi Wan, Longguang Zhong, Tianyuan Shi, Xiaojun Quan
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=fq24pEb8SL
- **中文提要：** 融合架构与规模各异的开源大语言模型有望集中不同模型的长处，但现有融合要处理词表对齐和合并分布矩阵，步骤复杂且容易引入噪声与错误。加权奖励偏好优化被用于隐式模型融合。
- **关键词：** preference-optimization, alignment, fine-tuning

### Zeroth-Order Fine-Tuning of LLMs with Transferable Static Sparsity

- **作者：** Wentao Guo, Jikai Long, Yimeng Zeng, Zirui Liu, Xinyu Yang, Yide Ran, Jacob Gardner, Osbert Bastani, Christopher De Sa, Xiaodong Yu, Beidi Chen, Zhaozhuo Xu
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=myYzr50xBh
- **中文提要：** 零阶优化只靠前向传播，是一种省显存的大语言模型微调策略。手机和笔记本等显存受限场景通常还要做权重量化，而零阶方法需要全精度扰动和更新，因而仍然困难；可迁移的静态稀疏被用来做这种零阶微调。
- **关键词：** fine-tuning

### Zeroth-Order Policy Gradient for Reinforcement Learning from Human Feedback without Reward Inference

- **作者：** Qining Zhang, Lei Ying
- **会议：** ICLR 2025 · Main · Poster
- **官方论文页：** https://openreview.net/forum?id=cmYScmfu4Q
- **中文提要：** 从人类偏好学习奖励模型这一奖励推断步骤，是 RLHF 微调大语言模型的关键中间环节。实际中 RLHF 还面临分布偏移、奖励模型过拟合和问题设定不当等根本挑战；零阶策略梯度被用来在不做奖励推断的情况下完成 RLHF。
- **关键词：** DPO, RLHF, preference-optimization, reward-model, fine-tuning
