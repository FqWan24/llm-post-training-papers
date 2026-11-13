# 2026 · EACL

共 37 篇。Main 16，Findings 21，其他赛道 0。其中 0 篇来源题录无摘要，提要标明「仅根据标题概括」。

检索窗口为 2024-11-13 至 2026-11-13。题录信息来自官方列表，不在此增补作者、链接或实验数字。

## Main

### ARC: Argument Representation and Coverage Analysis for Zero-Shot Long Document Summarization with Instruction Following LLMs

- **作者：** Mohamed Elaraby, Diane Litman
- **会议：** EACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.eacl-long.167/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.eacl-long.167.pdf)
- **中文提要：** ARC 是一套自下而上的评估框架，用来衡量摘要是否保住结构化的关键论点，尤其面向法律等高风险领域。它按待覆盖的信息类型加以区分，并把遗漏与事实错误分开，从而提供可解释的视角。
- **关键词：** instruction-following

### CONGRAD: Conflicting Gradient Filtering for Multilingual Preference Alignment

- **作者：** Jiangnan Li, Thuy-Trang Vu, Christian Herold, Amirhossein Tebbifakhr, Shahram Khadivi, Gholamreza Haffari
- **会议：** EACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.eacl-long.299/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.eacl-long.299.pdf)
- **中文提要：** 多语言偏好对齐若把多种语言简单联合训练，容易因目标冲突产生负干扰，并拉低整体表现。摘要只点出这一多语言训练中的已知问题。
- **关键词：** preference-optimization, alignment, self-rewarding

### Deconstructing Instruction-Following: A New Benchmark for Granular Evaluation of Large Language Model Instruction Compliance Abilities

- **作者：** Alberto Purpura, Li Wang, Sahil Badyal, Gene Beaufrand, Adam Faulkner
- **会议：** EACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.eacl-long.62/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.eacl-long.62.pdf)
- **中文提要：** 可靠地让大语言模型遵循复杂指令仍很难，现有基准往往既不像真实使用，也难以把遵从与任务成败分开。MOSAIC 用模块化框架和动态生成的数据，配合面向应用的生成约束来做更细粒度的评估。
- **关键词：** instruction-following

### Exploring Fine-Tuning for In-Context Retrieval and Efficient KV-Caching in Long-Context Language Models

- **作者：** Francesco Maria Molfese, Momchil Hardalov, Rexhina Blloshmi, Bill Byrne, Adri{\`a} de Gispert
- **会议：** EACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.eacl-short.44/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.eacl-short.44.pdf)
- **中文提要：** 长上下文语言模型可以把整套文档编进上下文，从而成为传统检索增强生成之外的一条路线。尚不清楚微调策略能否提升长上下文表现，并在 KV 缓存压缩下转化为更强的稳健性。
- **关键词：** fine-tuning

### Exploring Generative Process Reward Modeling for Semi-Structured Data: A Case Study of Table Question Answering

- **作者：** Lei Tang, Wei Zhou, Mohsen Mesgar
- **会议：** EACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.eacl-short.30/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.eacl-short.30.pdf)
- **中文提要：** 过程奖励模型逐步给候选解答打分，再按汇总的步骤分数选出答案，以改进大语言模型的复杂推理。数学等领域已经见效，但它们对表格问答这类半结构化数据是否适用仍未探明。
- **关键词：** PRM, reward-model

### GRAVITY: A Framework for Personalized Text Generation via Profile-Grounded Synthetic Preferences

- **作者：** Priyanka Dey, Daniele Rosa, Wenqing Zheng, Daniel Barcklow, Jieyu Zhao, Emilio Ferrara
- **会议：** EACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.eacl-long.348/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.eacl-long.348.pdf)
- **中文提要：** 大语言模型的个性化常依赖昂贵的人类反馈或交互日志，既难扩展，也忽略更深的用户属性。GRAVITY 生成基于用户画像的合成偏好数据，以刻画兴趣、价值观等属性。
- **关键词：** fine-tuning

### Instruction Tuning with and without Context: Behavioral Shifts and Downstream Impact

- **作者：** Hyunji Lee, Seunghyun Yoon, Yunjae Won, Hanseok Oh, Geewook Kim, Trung Bui, Franck Dernoncourt, Elias Stengel-Eskin, Mohit Bansal, Minjoon Seo
- **会议：** EACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.eacl-long.320/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.eacl-long.320.pdf)
- **中文提要：** 指令微调被广泛用来提升大语言模型遵循指令的能力。所用数据通常混有带上下文与无上下文的例子，以往工作多把两类直接合并，并未分开考察各自的影响。
- **关键词：** instruction-tuning, instruction-following

### Investigating the Multilingual Calibration Effects of Language Model Instruction Tuning

- **作者：** Jerry Huang, Peng Lu, Qiuhao Zeng, Yusuke Iwasawa, Yutaka Matsuo, Sarath Chandar, Edison Marrese-Taylor, Irene Li
- **会议：** EACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.eacl-short.1/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.eacl-short.1.pdf)
- **中文提要：** 预测不确定性是否校准，关系到深度学习模型是否可信可靠；基础模型进展很快，大语言模型与校准的关系仍是开放问题。这项工作关注语言模型校准中的一处关键空白。
- **关键词：** SFT, instruction-tuning

### Offline Preference Optimization via Maximum Marginal Likelihood Estimation

- **作者：** Saeed Najafi, Alona Fyshe
- **会议：** EACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.eacl-long.318/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.eacl-long.318.pdf)
- **中文提要：** 把大语言模型对齐到人类偏好很重要，但 RLHF 一类标准方法往往复杂且不稳定。这里改从最大边际似然估计来重新表述对齐，以期得到更简单的做法。
- **关键词：** RLHF, preference-optimization, reward-model, alignment

### Out of Distribution, Out of Luck: Process Rewards Misguide Reasoning Models

- **作者：** Alexey Dontsov, Anton Korznikov, Andrey V. Galichin, Elena Tutubalina
- **会议：** EACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.eacl-short.31/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.eacl-short.31.pdf)
- **中文提要：** 过程奖励模型在推理时给出步骤级反馈，用来引导大语言模型的多步推理。评估却显示一种失效：它们能提升指令式数学模型的表现，但对推理模型既难增强，有时还会使其变差。
- **关键词：** PRM, reward-model

### PaperSearchQA: Learning to Search and Reason over Scientific Papers with RLVR

- **作者：** James Burgess, Jan N. Hansen, Duo Peng, Yuhui Zhang, Alejandro Lozano, Min Woo Sun, Emma Lundberg, Serena Yeung-Levy
- **会议：** EACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.eacl-long.88/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.eacl-long.88.pdf)
- **中文提要：** 搜索智能体用语言模型边推理边检索知识库或网页来回答问题，近期做法多用 RLVR 只监督最终答案是否正确。多数这类智能体面向通用问答，因而与科学、工程和医学中的技术系统关联有限。
- **关键词：** RLVR

### PEFT-Bench: A Parameter-Efficient Fine-Tuning Methods Benchmark

- **作者：** Robert Belanec, Branislav Pecher, Ivan Srba, Maria Bielikova
- **会议：** EACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.eacl-long.140/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.eacl-long.140.pdf)
- **中文提要：** 大语言模型在许多任务上表现突出，但规模带来很高的计算与环境成本，限制了可及性。PEFT 通过减少可训练参数来应对这一挑战，同时仍希望保持较强的下游表现。
- **关键词：** PEFT, fine-tuning

### Persistent Personas? Role-Playing, Instruction Following, and Safety in Extended Interactions

- **作者：** Pedro Henrique Luz de Araujo, Michael A. Hedderich, Ali Modarressi, Hinrich Schuetze, Benjamin Roth
- **会议：** EACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.eacl-long.246/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.eacl-long.246.pdf)
- **中文提要：** 被赋予人设的大语言模型用于教育、医疗和社会人口学模拟等领域。现有评估却多停留在短程、单轮设定，难以反映真实使用。
- **关键词：** instruction-following

### RoZO: Geometry-Aware Zeroth-Order Fine-Tuning on Low-Rank Adapters for Black-Box Large Language Models

- **作者：** Zichen Song, Weijia Li
- **会议：** EACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.eacl-long.80/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.eacl-long.80.pdf)
- **中文提要：** 在黑盒或显存受限条件下高效微调大语言模型仍然困难。LoRA 一类 PEFT 把更新限制在低秩适配器上以减轻显存，零阶优化则靠估计梯度来避免反向传播。
- **关键词：** LoRA, PEFT, fine-tuning

### Spotlight Your Instructions: Instruction-following with Dynamic Attention Steering

- **作者：** Praveen Venkateswaran, Danish Contractor
- **会议：** EACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.eacl-long.174/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.eacl-long.174.pdf)
- **中文提要：** 许多实际应用靠自然语言指令引导大语言模型完成各种任务。这些指令往往复杂、多样，而且会频繁变化。
- **关键词：** instruction-following, alignment

### Unintended Memorization of Sensitive Information in Fine-Tuned Language Models

- **作者：** Marton Szep, Jorge Marin Ruiz, Georgios Kaissis, Paulina Seidl, R{\"u}diger von Eisenhart-Rothe, Florian Hinterwimmer, Daniel Rueckert
- **会议：** EACL 2026 · Main
- **官方论文页：** https://aclanthology.org/2026.eacl-long.304/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.eacl-long.304.pdf)
- **中文提要：** 在敏感数据上微调大语言模型，可能无意记住并泄露个人身份信息，既可能违反隐私规定，也危及个人安全。这项研究系统考察一个较少被关注的漏洞：只出现在模型输入、而不出现在训练目标中的身份信息被暴露。
- **关键词：** preference-optimization, post-training, alignment, fine-tuning

## Findings

### Attribute-Controlled Translation with Preference Optimization

- **作者：** Inigo Jauregi Unanue, Najmeh Sadoughi, Vimal Bhat, Zhu Liu, Massimo Piccardi
- **会议：** EACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-eacl.209/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-eacl.209.pdf)
- **中文提要：** 属性可控翻译要求译文满足特定的语言与风格约束。精心设计的提示可以让大语言模型在该任务上表现较强，但效果主要限于规模很大的模型。
- **关键词：** preference-optimization

### Benchmarking Direct Preference Optimization for Medical Large Vision--Language Models

- **作者：** Dain Kim, Jiwoo Lee, Jaehoon Yun, Yong Hoe Koo, Qingyu Chen, Hyunjae Kim, Jaewoo Kang
- **会议：** EACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-eacl.267/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-eacl.267.pdf)
- **中文提要：** 大型视觉语言模型正用于诊断辅助、报告生成和医学问答等临床任务。后训练里的 DPO 有望把输出对齐到人类偏好，但它在高风险医学场景中是否有效仍少有研究。
- **关键词：** DPO, SFT, preference-optimization, post-training, alignment, fine-tuning

### Best-of-L: Cross-Lingual Reward Modeling for Mathematical Reasoning

- **作者：** Sara Rajaee, Rochelle Choenni, Ekaterina Shutova, Christof Monz
- **会议：** EACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-eacl.99/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-eacl.99.pdf)
- **中文提要：** 大语言模型的推理能力持续提升，但多语言模型中这种能力如何随语言变化、不同语言是否走出不同推理路径，仍少有研究。不同语言生成的推理轨迹常常为数学推理提供互补信号。
- **关键词：** reward-model

### Causal Direct Preference Optimization for Language Model Alignment

- **作者：** Uyen Le, Thin Nguyen, Toan Nguyen, Toan Doan, Trung Le, Bac Le
- **会议：** EACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-eacl.58/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-eacl.58.pdf)
- **中文提要：** DPO 把偏好学习写成对成对人工标注输出的监督分类，从而较稳定、高效地把大语言模型对齐到人类偏好。它也会继承影响数据生成的混杂因素（如话题、风格、用户目标）所带来的偏差。
- **关键词：** DPO, preference-optimization, alignment, fine-tuning

### Completely Modular Fine-tuning for Dynamic Language Adaptation

- **作者：** Zhe Cao, Yusuke Oda, Qianying Liu, Akiko Aizawa, Taro Watanabe
- **会议：** EACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-eacl.252/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-eacl.252.pdf)
- **中文提要：** 多语言微调已明显推进大语言模型的机器翻译。现有研究多停留在语言集合固定的传统微调设定，缺少对新语言的动态适应。
- **关键词：** LoRA, fine-tuning

### Complexity-aware fine-tuning

- **作者：** Andrey Goncharov, Daniil Vyazhev, Petr Sychev, Edvard Khalafyan, Alexey Zaytsev
- **会议：** EACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-eacl.34/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-eacl.34.pdf)
- **中文提要：** 通用大语言模型常靠 SFT 提升特定领域表现；蒸馏更大模型的思维链可以更好，但调用昂贵且所需数据多得多。这里提出一种高效微调蓝图，只对识别出的复杂数据使用推理。
- **关键词：** SFT, fine-tuning

### Conformal Feedback Alignment: Quantifying Answer-Level Reliability for Robust LLM Alignment

- **作者：** Tiejin Chen, Xiaoou Liu, Vishnu Nandam, Kuan-Ru Liou, Hua Wei
- **会议：** EACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-eacl.184/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-eacl.184.pdf)
- **中文提要：** RLHF 一类基于偏好的对齐从成对偏好中学习，但标签常常嘈杂且不一致。已有的不确定性方法会对偏好加权，却忽略更根本的一点：被比较的答案本身是否可靠。
- **关键词：** DPO, RLHF, alignment

### Continual Pretraining on Encrypted Synthetic Data for Privacy-Preserving LLMs

- **作者：** Honghao Liu, Xuhui Jiang, Chengjin Xu, Cehao Yang, Yiran Cheng, Lionel Ni, Jian Guo
- **会议：** EACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-eacl.21/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-eacl.21.pdf)
- **中文提要：** 在小规模领域语料上预训练大语言模型时，既要用敏感数据又要保住隐私很难。这项工作朝隐私保护的持续预训练做了探索，提出基于实体的框架，合成加密训练数据以保护个人身份信息。
- **关键词：** instruction-following, continued-pretraining

### DS2-Instruct: Domain-Specific Data Synthesis for Large Language Models Instruction Tuning

- **作者：** Ruiyao Xu, Noelle I. Samia, Han Liu
- **会议：** EACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-eacl.176/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-eacl.176.pdf)
- **中文提要：** 把大语言模型适配到专业领域需要高质量指令微调数据，人工标注成本很高。现有数据合成多面向通用任务，难以抓住领域术语和推理模式。
- **关键词：** instruction-tuning, fine-tuning

### Event Detection with a Context-Aware Encoder and LoRA for Improved Performance on Long-Tailed Classes

- **作者：** Abdullah Al Monsur, Nitesh Vamshi Bommisetty, Gene Louis Kim
- **会议：** EACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-eacl.314/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-eacl.314.pdf)
- **中文提要：** 事件检测研究中反复出现两项局限，这项工作加以考察。其一是仅解码器的大语言模型只能单向建模，对依赖丰富双向上下文的自然语言理解构成架构瓶颈，摘要只写到这一点。
- **关键词：** LoRA, fine-tuning

### Feature Drift: How Fine-Tuning Repurposes Representations in LLMs

- **作者：** Andrey V. Galichin, Anton Korznikov, Alexey Dontsov, Oleg Rogov, Elena Tutubalina, Ivan Oseledets
- **会议：** EACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-eacl.96/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-eacl.96.pdf)
- **中文提要：** 微调会给大语言模型带来指令遵循、安全对齐等重要行为。因此有必要弄清微调如何改变模型的内部机制。
- **关键词：** instruction-tuning, instruction-following, alignment, fine-tuning

### HARM: Learning Hate-Aware Reward Model for Evaluating Natural Language Explanations of Offensive Content

- **作者：** Lorenzo Puppi Vecchi, Alceu de Souza Britto Jr, Emerson Cabrera Paraiso, Rafael Menelau Cruz
- **会议：** EACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-eacl.230/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-eacl.230.pdf)
- **中文提要：** 用自然语言解释内容为何具有仇恨性，有助于提升自动内容审核的透明度。如何评价这类解释的质量仍是未解问题。
- **关键词：** reward-model

### Imbalanced Gradients in RL Post-Training of Multi-Task LLMs

- **作者：** Runzhe Wu, Ankur Samanta, Ayush Jain, Scott Fujimoto, Jeongyeol Kwon, Ben Kretzu, Youliang Yu, Kaveh Hassani, Boris Vidolov, Yonathan Efroni
- **会议：** EACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-eacl.164/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-eacl.164.pdf)
- **中文提要：** 多任务后训练通常把不同任务的数据混合后联合优化。这暗中假设各任务贡献的梯度量级相近；一旦不成立，优化就会偏向梯度更大的任务。
- **关键词：** post-training

### Intention-Adaptive LLM Fine-Tuning for Text Revision Generation

- **作者：** Zhexiong Liu, Diane Litman
- **会议：** EACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-eacl.65/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-eacl.65.pdf)
- **中文提要：** 大语言模型在摘要、推理等基于上下文的文本生成上已经很强，基于意图的生成仍少有探索。文本修订生成就是一例，它要求生成结果明确体现写作者的真实意图。
- **关键词：** PEFT, fine-tuning

### IRPO: Implicit Policy Regularized Preference Optimization

- **作者：** Youngsoo Jang, Yu Jin Kim, Geon-Hyeong Kim, Honglak Lee, Moontae Lee
- **会议：** EACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-eacl.281/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-eacl.281.pdf)
- **中文提要：** 大语言模型的训练复杂度常随超参数空间变大而上升。DPO 通过重参数化奖励函数带来学习稳定性，但参考策略本身并非最优时，对它的正则可能得到次优结果。
- **关键词：** DPO, preference-optimization, fine-tuning

### Joint Multimodal Preference Optimization for Fine-Grained Visual-Textual Alignment

- **作者：** Jiwon Kim, Hyunsoo Yoon
- **会议：** EACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-eacl.5/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-eacl.5.pdf)
- **中文提要：** 近期工作把 DPO 扩展到视觉偏好监督，以缓解大型视觉语言模型的多模态幻觉。这些方法往往缺少细粒度的视觉对比机制，并且依赖单一边界的优化。
- **关键词：** DPO, preference-optimization, alignment

### LogToP: Logic Tree-of-Program with Table Instruction-tuned LLMs for Controlled Logical Table-to-Text Generation

- **作者：** Yupian Lin, Guangya Yu, Cheng Yuan, Huan Du, Hui Luo, Yuang Bian, Jingping Liu, Zhidong He, Wen Du, Tong Ruan
- **会议：** EACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-eacl.280/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-eacl.280.pdf)
- **中文提要：** 逻辑表格到文本生成要求自然语言既流畅又精确，并在表层和逻辑层都忠实于给定表格。大语言模型处理纯文本很强，解读和推理表格数据仍然有限。
- **关键词：** instruction-tuning

### Parameter-Efficient Routed Fine-Tuning: Mixture-of-Experts Demands Mixture of Adaptation Modules

- **作者：** Yilun Liu, Yunpu Ma, Yuetian Lu, Shuo Chen, Zifeng Ding, Volker Tresp
- **会议：** EACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-eacl.232/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-eacl.232.pdf)
- **中文提要：** 混合专家模型靠专门专家之间的动态路由获益，现有 PEFT 往往用不上这一机制。因此需要考察适配模块本身是否也应引入路由，以贴合多专家架构。
- **关键词：** PEFT, fine-tuning

### PIRA: Preference-Oriented Instruction-Tuned Reward Models with Dual Aggregation

- **作者：** Yongfu Xue
- **会议：** EACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-eacl.117/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-eacl.117.pdf)
- **中文提要：** 奖励模型是把大语言模型对齐到人类偏好的关键。现有做法的一项主要局限是：判别式奖励模型需要大规模标注，因为它们无法利用生成式奖励模型所能借助的偏好指令遵循能力。
- **关键词：** instruction-tuning, instruction-following, reward-model, alignment

### RB-LoRA: Rank-Balanced Aggregation for Low-Rank Adaptation with Federated Fine-Tuning

- **作者：** Sihyeon Ha, Yongjeong Oh, Yo-Seb Jeon
- **会议：** EACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-eacl.88/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-eacl.88.pdf)
- **中文提要：** 联邦微调基础模型受阻于需要传输规模庞大的参数。LoRA 只更新紧凑的适配器矩阵，从而减轻这一通信负担。
- **关键词：** LoRA, fine-tuning

### We Are What We Repeatedly Do: Improving Long Context Instruction Following

- **作者：** Preston K Robinette, Andrew Hard, Swaroop Ramaswamy, Ehsan Amid, Rajiv Mathews, Taylor T Johnson
- **会议：** EACL 2026 · Findings
- **官方论文页：** https://aclanthology.org/2026.findings-eacl.254/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2026.findings-eacl.254.pdf)
- **中文提要：** 大语言模型的上下文长度近年增长很快。更长的窗口让模型能依据更多输入作条件，从而对部分用户提示给出更高质量的回复。
- **关键词：** instruction-following
