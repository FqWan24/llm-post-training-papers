# 2024 · EMNLP

共 149 篇。Main 90，Findings 59，其他赛道 0。其中 3 篇来源题录无摘要，提要标明「仅根据标题概括」。

检索窗口为 2024-11-13 至 2026-11-13。题录信息来自官方列表，不在此增补作者、链接或实验数字。

## Main

### Adapters Mixup: Mixing Parameter-Efficient Adapters to Enhance the Adversarial Robustness of Fine-tuned Pre-trained Text Classifiers

- **作者：** Tuc Van Nguyen, Thai Le
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.1180/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.1180.pdf)
- **中文提要：** 用干净样本与对抗样本扩充数据，再以 PEFT 微调预训练语言模型做分类，已被证明能增强对抗攻击下的稳健性，但这种对抗训练常让干净输入上的表现变差，并且需要频繁重训。
- **关键词：** PEFT, fine-tuning

### AdaZeta: Adaptive Zeroth-Order Tensor-Train Adaption for Memory-Efficient Large Language Models Fine-Tuning

- **作者：** Yifan Yang, Kai Zhen, Ershad Banijamali, Athanasios Mouchtaris, Zheng Zhang
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.56/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.56.pdf)
- **中文提要：** AdaZeta 关注大语言模型微调的显存开销，沿仅做前向、不建反向图的零阶路线，用自适应张量列来做参数适应。
- **关键词：** fine-tuning

### ADELIE: Aligning Large Language Models on Information Extraction

- **作者：** Yunjia Qi, Hao Peng, Xiaozhi Wang, Bin Xu, Lei Hou, Juanzi Li
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.419/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.419.pdf)
- **中文提要：** 仅根据标题概括：该工作讨论如何让大语言模型在信息抽取上对齐。官方题录没有摘要，此处不补充具体做法或实验结果。
- **关键词：** alignment

### Aligning Language Models to Explicitly Handle Ambiguity

- **作者：** Hyuhng Joon Kim, Youna Kim, Cheonbok Park, Junyeob Kim, Choonghyun Park, Kang Min Yoo, Sang-goo Lee, Taeuk Kim
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.119/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.119.pdf)
- **中文提要：** 用户话语常为求效率而省略成分或说得不够精确，使同一输入在不同假设或背景知识下产生多种解读。
- **关键词：** alignment

### Aligning Large Language Models with Diverse Political Viewpoints

- **作者：** Dominik Stammbach, Philine Widmer, Eunjung Cho, Caglar Gulcehre, Elliott Ash
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.412/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.412.pdf)
- **中文提要：** ChatGPT 一类大语言模型带有明显政治偏见，用户询问政治信息时，它们往往采取规范性立场。
- **关键词：** alignment

### AlphaLoRA: Assigning LoRA Experts Based on Layer Training Quality

- **作者：** Peijun Qing, Chongyang Gao, Yefan Zhou, Xingjian Diao, Yaoqing Yang, Soroush Vosoughi
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.1141/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.1141.pdf)
- **中文提要：** LoRA 等参数高效微调能提高大语言模型训练效率；由于 LoRA 可调参数有限，近期研究试图将其与混合专家（MoE）结合，以提升多项任务上的表现。
- **关键词：** LoRA, PEFT, fine-tuning

### ApiQ: Finetuning of 2-Bit Quantized Large Language Model

- **作者：** Baohao Liao, Christian Herold, Shahram Khadivi, Christof Monz
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.1168/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.1168.pdf)
- **中文提要：** 显存限制推动了大语言模型的高效微调，但 QLoRA 等策略在不同位宽上表现并不一致。
- **关键词：** QLoRA, LoRA, fine-tuning

### ARES: Alternating Reinforcement Learning and Supervised Fine-Tuning for Enhanced Multi-Modal Chain-of-Thought Reasoning Through Diverse AI Feedback

- **作者：** Ju-Seung Byun, Jiyun Chun, Jihyung Kil, Andrew Perrault
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.252/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.252.pdf)
- **中文提要：** 大型多模态模型擅长理解人类指令并在多种任务上表现突出；RLHF 与基于 AI 反馈的 RLAIF 则进一步按特定偏好对齐语言模型。
- **关键词：** RLHF, RLAIF, RFT, SFT, alignment, fine-tuning

### BEEAR: Embedding-based Adversarial Removal of Safety Backdoors in Instruction-tuned Language Models

- **作者：** Yi Zeng, Weiyu Sun, Tran Huynh, Dawn Song, Bo Li, Ruoxi Jia
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.732/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.732.pdf)
- **中文提要：** 大语言模型中的安全后门能在正常交互里躲过检测，再被隐蔽触发有害行为；触发搜索空间维度很高，潜在恶意行为又多种多样，因此这仍是一个关键的开放问题。
- **关键词：** instruction-tuning, fine-tuning

### BPO: Staying Close to the Behavior LLM Creates Better Online LLM Alignment

- **作者：** Wenda Xu, Jiachen Li, William Yang Wang, Lei Li
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.623/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.623.pdf)
- **中文提要：** 直接偏好对齐（DAP）借助预先收集的离线偏好数据，把大语言模型对齐到人类期望；已有研究表明离线方法也能直接受益于在线样本，但仍需要专门的在线 DAP 算法，才能充分发挥在线训练的作用。
- **关键词：** preference-optimization, alignment

### Breaking Language Barriers: Cross-Lingual Continual Pre-Training at Scale

- **作者：** Wenzhen Zheng, Wenbo Pan, Xu Xu, Libo Qin, Li Yue, Ming Zhou
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.441/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.441.pdf)
- **中文提要：** 从零训练大语言模型需要可观的计算资源与大量文本，尽管这类模型近年已有明显进展。
- **关键词：** continued-pretraining

### CMR Scaling Law: Predicting Critical Mixture Ratios for Continual Pre-training of Language Models

- **作者：** Jiawei Gu, Zacc Yang, Chuanghao Ding, Rui Zhao, Fei Tan
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.903/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.903.pdf)
- **中文提要：** 大语言模型在多样任务上表现出色，但在专业领域常因缺少领域或专有语料而不足；持续预训练通过写入新的领域或专有知识，并回放通用语料来避免灾难性遗忘。
- **关键词：** continued-pretraining

### CoBa: Convergence Balancer for Multitask Finetuning of Large Language Models

- **作者：** Zi Gong, Hang Yu, Cong Liao, Bingchang Liu, Chaoyu Chen, Jianguo Li
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.459/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.459.pdf)
- **中文提要：** 多任务学习能让一个大语言模型同时提升多项任务的表现与泛化，从而不必为每个任务单独建模；现有策略要么计算开销大，要么无法保证各任务同时收敛。
- **关键词：** fine-tuning

### CoEvol: Constructing Better Responses for Instruction Finetuning through Multi-Agent Cooperation

- **作者：** Renhao Li, Minghuan Tan, Derek F. Wong, Min Yang
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.271/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.271.pdf)
- **中文提要：** 指令微调近年来被用来提升大语言模型在未见任务上的表现，并已有工作尝试自动构造与有效筛选这类数据。
- **关键词：** instruction-following, fine-tuning

### CommonIT: Commonality-Aware Instruction Tuning for Large Language Models via Data Partitions

- **作者：** Jun Rao, Xuebo Liu, Lian Lian, Shengjun Cheng, Yunjie Liao, Min Zhang
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.561/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.561.pdf)
- **中文提要：** 不同于多数着眼于数据混合的研究，这项工作从训练阶段的数据采样入手，以增强大语言模型遵循命令的能力。
- **关键词：** instruction-tuning, instruction-following

### Community-Cross-Instruct: Unsupervised Instruction Generation for Aligning Large Language Models to Online Communities

- **作者：** Zihao He, Minh Duc Chu, Rebecca Dorn, Siyi Guo, Kristina Lerman
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.945/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.945.pdf)
- **中文提要：** 社会调查能探查人群的意见与信念，但缓慢、昂贵且容易产生偏差；大语言模型则可用于构建人群的计算表征或“数字孪生”，生成模仿其语言、风格与态度的回答。
- **关键词：** alignment, fine-tuning

### Contrastive Policy Gradient: Aligning LLMs on sequence-level scores in a supervised-friendly fashion

- **作者：** Yannis Flet-Berliac, Nathan Grinsztajn, Florian Strub, Eugene Choi, Bill Wu, Chris Cremer, Arash Ahmadian, Yash Chandak, Mohammad Gheshlaghi Azar, Olivier Pietquin, Matthieu Geist
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.1190/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.1190.pdf)
- **中文提要：** 强化学习常借助由偏好数据训练的奖励模型来微调大语言模型，使之更符合人类判断；更新的直接对齐方法往往更简单、更稳定、计算更轻，也能更直接地达成这一目标。
- **关键词：** preference-optimization, reward-model, alignment, fine-tuning

### Controllable Preference Optimization: Toward Controllable Multi-Objective Alignment

- **作者：** Yiju Guo, Ganqu Cui, Lifan Yuan, Ning Ding, Zexu Sun, Bowen Sun, Huimin Chen, Ruobing Xie, Jie Zhou, Yankai Lin, Zhiyuan Liu, Maosong Sun
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.85/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.85.pdf)
- **中文提要：** 人工智能中的对齐追求模型回复与人类偏好及价值观一致，但偏好的多面性会带来对齐税：在无害性等单一目标上的改进，可能削弱有用性等其他方面。
- **关键词：** preference-optimization, alignment

### Dancing in Chains: Reconciling Instruction Following and Faithfulness in Language Models

- **作者：** Zhengxuan Wu, Yuhao Zhang, Peng Qi, Yumo Xu, Rujun Han, Yian Zhang, Jifan Chen, Bonan Min, Zhiheng Huang
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.229/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.229.pdf)
- **中文提要：** 语言模型需要同时遵循人类指令并忠实于给定上下文，但两者经常难以兼得；在按这些目标训练时，开放式指令遵循与依据上下文作答之间存在权衡。
- **关键词：** instruction-tuning, instruction-following, alignment, fine-tuning

### DEFT-UCS: Data Efficient Fine-Tuning for Pre-Trained Language Models via Unsupervised Core-Set Selection for Text-Editing

- **作者：** Devleena Das, Vivek Khetan
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.1132/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.1132.pdf)
- **中文提要：** 可用的预训练语言模型已经很多，但下游任务微调究竟需要多少数据仍不清楚，DEFT-UCS 借助无监督核心集选择，找出更小且更具代表性的数据来微调文本生成。
- **关键词：** fine-tuning

### Democratizing Large Language Models via Personalized Parameter-Efficient Fine-tuning

- **作者：** Zhaoxuan Tan, Qingkai Zeng, Yijun Tian, Zheyuan Liu, Bing Yin, Meng Jiang
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.372/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.372.pdf)
- **中文提要：** 大语言模型的个性化希望让交互、内容与推荐贴合个人偏好；近期工作通过检索行为历史和文本画像，用非参数知识充实用户查询，从而改进提示设计。
- **关键词：** PEFT, fine-tuning

### Direct Multi-Turn Preference Optimization for Language Agents

- **作者：** Wentao Shi, Mengqi Yuan, Junkang Wu, Qifan Wang, Fuli Feng
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.138/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.138.pdf)
- **中文提要：** 让大语言模型适应智能体任务，对构建语言智能体至关重要；DPO 有望完成这种适配并缓解误差累积，从而直接优化强化学习目标。
- **关键词：** DPO, preference-optimization

### Dissecting Fine-Tuning Unlearning in Large Language Models

- **作者：** Yihuai Hong, Yuelin Zou, Lijie Hu, Ziqian Zeng, Di Wang, Haiqin Yang
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.228/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.228.pdf)
- **中文提要：** 基于微调的遗忘方法试图清除大语言模型中的有害、敏感或受版权保护信息，同时保住整体能力，但这些方法是否真正有效仍不明确。
- **关键词：** fine-tuning

### Does Fine-Tuning LLMs on New Knowledge Encourage Hallucinations?

- **作者：** Zorik Gekhman, Gal Yona, Roee Aharoni, Matan Eyal, Amir Feder, Roi Reichart, Jonathan Herzig
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.444/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.444.pdf)
- **中文提要：** 监督微调对齐时，大语言模型可能碰到预训练阶段未曾获得的新事实；一种常见猜想是，模型会被训练去生成并未扎根于已有知识的事实，从而学会幻觉式作答。
- **关键词：** SFT, fine-tuning

### DogeRM: Equipping Reward Models with Domain Knowledge through Model Merging

- **作者：** Tzu-Han Lin, Chen-An Li, Hung-yi Lee, Yun-Nung Chen
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.868/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.868.pdf)
- **中文提要：** 用人类反馈强化学习（RLHF）对齐大语言模型是常见做法，而奖励建模是其中的关键步骤。
- **关键词：** RLHF, reward-model, alignment

### Don't Forget Your Reward Values: Language Model Alignment via Value-based Calibration

- **作者：** Xin Mao, Feng-Lin Li, Huimin Xu, Wei Zhang, Wang Chen, Anh Tuan Luu
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.976/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.976.pdf)
- **中文提要：** RLHF 虽能明显提升大语言模型的生成质量，PPO 的复杂与不稳定促使一系列基于排序的对齐方法成为替代，该文着手深入这些方法并尝试统一。
- **关键词：** RLHF, alignment

### Don't Just Say ``I don't know''! Self-aligning Large Language Models for Responding to Unknown Questions with Explanations

- **作者：** Yang Deng, Yong Zhao, Moxin Li, See-Kiong Ng, Tat-Seng Chua
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.757/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.757.pdf)
- **中文提要：** 大语言模型即便面对没有确定答案的问题也常常过度自信；为避免给出幻觉式回答，已有研究通常探讨如何拒绝回答这类未知问题。
- **关键词：** alignment, fine-tuning

### Dynamic Rewarding with Prompt Optimization Enables Tuning-free Self-Alignment of Language Models

- **作者：** Somanshu Singla, Zhen Wang, Tianyang Liu, Abdullah Ashfaq, Zhiting Hu, Eric P. Xing
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.1220/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.1220.pdf)
- **中文提要：** 把大语言模型对齐到人类偏好，传统上依赖代价很高的监督微调（SFT）与 RLHF；为避开大量调参和昂贵标注，作者提出一种免微调的自对齐方法，称为动态奖励与提示优化（DRPO）。
- **关键词：** RLHF, SFT, alignment, fine-tuning

### Eliminating Biased Length Reliance of Direct Preference Optimization via Down-Sampled KL Divergence

- **作者：** Junru Lu, Jiazheng Li, Siyu An, Meng Zhao, Yulan He, Di Yin, Xing Sun
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.60/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.60.pdf)
- **中文提要：** DPO 提供了比复杂的 RLHF 更直接的对齐途径，用来把大语言模型与人类偏好对齐；但它会陷入啰嗦这一过度优化现象，而该现象在 RLHF 中也同样常见。
- **关键词：** DPO, RLHF, preference-optimization, alignment

### Enhancing Language Model Alignment: A Confidence-Based Approach to Label Smoothing

- **作者：** Baihe Huang, Hiteshi Sharma, Yi Mao
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.1189/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.1189.pdf)
- **中文提要：** 近年来大语言模型在多个领域展现出突出能力，而训练流程中的 RLHF 阶段对对齐人类偏好与价值观至关重要。
- **关键词：** RLHF, alignment

### EPO: Hierarchical LLM Agents with Environment Preference Optimization

- **作者：** Qi Zhao, Haotian Fu, Chen Sun, George Konidaris
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.367/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.367.pdf)
- **中文提要：** 长时程决策对基于大语言模型的智能体很困难，因为需要在多个步骤上做大量规划；文中提出分层框架，把复杂任务分解为可处理的子目标，并分别用不同的语言模型预测子目标与生成底层动作。
- **关键词：** preference-optimization, reward-model

### Evaluating the Instruction-Following Robustness of Large Language Models to Prompt Injection

- **作者：** Zekun Li, Baolin Peng, Pengcheng He, Xifeng Yan
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.33/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.33.pdf)
- **中文提要：** 大语言模型在遵循指令上表现突出，因而越来越多地进入各类应用，但这也带来提示注入风险：恶意指令可被嵌入输入，从而触发非预期的动作或内容。
- **关键词：** instruction-following

### Filtered Direct Preference Optimization

- **作者：** Tetsuro Morimura, Mitsuki Sakamoto, Yuu Jinnai, Kenshi Abe, Kaito Ariu
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.1266/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.1266.pdf)
- **中文提要：** RLHF 在按人类偏好对齐语言模型中作用关键；数据质量的重要性虽被普遍认可，但在 RLHF 框架内对其影响的明确研究仍然有限。
- **关键词：** DPO, RLHF, preference-optimization, reward-model, alignment

### Fine-Tuning and Prompt Optimization: Two Great Steps that Work Better Together

- **作者：** Dilara Soylu, Christopher Potts, Omar Khattab
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.597/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.597.pdf)
- **中文提要：** 自然语言处理系统日益采用复杂的模块化流水线，例如检索增强生成（RAG），各模块可能对应不同的语言模型与提示模板；这类复合系统往往缺少中间标签或梯度通路，端到端优化因此很困难。
- **关键词：** fine-tuning

### Fine-Tuning Large Language Models to Translate: Will a Touch of Noisy Data in Misaligned Languages Suffice?

- **作者：** Dawei Zhu, Pinzhen Chen, Miaoran Zhang, Barry Haddow, Xiaoyu Shen, Dietrich Klakow
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.24/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.24.pdf)
- **中文提要：** 多语言机器翻译的成功传统上归功于训练数据的大体量、翻译方向多样以及高质量；在把大语言模型微调用于翻译的现有实践中，作者重新审视这些因素的重要性。
- **关键词：** fine-tuning

### Fine-Tuning or Retrieval? Comparing Knowledge Injection in LLMs

- **作者：** Oded Ovadia, Menachem Brief, Moshik Mishaeli, Oren Elisha
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.15/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.15.pdf)
- **中文提要：** 大语言模型能回答不同领域的问题，说明其预训练权重中蕴含大量事实；这些知识却受训练数据特性所限。
- **关键词：** SFT, fine-tuning

### FlipGuard: Defending Preference Alignment against Update Regression with Constrained Optimization

- **作者：** Mingye Zhu, Yi Liu, Quan Wang, Junbo Guo, Zhendong Mao
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.960/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.960.pdf)
- **中文提要：** 仅根据标题概括：该工作讨论如何用约束优化来防御偏好对齐在更新后出现的回退。官方题录没有摘要，此处不补充具体做法或实验结果。
- **关键词：** preference-optimization, alignment

### From Bottom to Top: Extending the Potential of Parameter Efficient Fine-Tuning

- **作者：** Jihao Gu, Zelin Wang, Yibo Zhang, Ziji Zhang, Ping Gong
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.204/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.204.pdf)
- **中文提要：** 随着大语言模型增多，只微调少量任务参数、冻结预训练参数的 PEFT 愈发重要；以往做法多在各层施加统一操作，却忽略 Transformer 不同层所存储的信息并不相同。
- **关键词：** LoRA, PEFT, fine-tuning

### GPT vs RETRO: Exploring the Intersection of Retrieval and Parameter-Efficient Fine-Tuning

- **作者：** Aleksander Ficek, Jiaqi Zeng, Oleksii Kuchaiev
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.1081/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.1081.pdf)
- **中文提要：** PEFT 与检索增强生成已成为在控制计算需求的同时适配大语言模型的常用途径；文中将 P-tuning、Adapters 与 LoRA 用于改动后的 RETRO，并与作为基线的 GPT 对照。
- **关键词：** instruction-tuning, LoRA, PEFT, fine-tuning

### Heterogeneous LoRA for Federated Fine-tuning of On-Device Foundation Models

- **作者：** Yae Jee Cho, Luyang Liu, Zheng Xu, Aldi Fahrezi, Gauri Joshi
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.717/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.717.pdf)
- **中文提要：** 基础模型经微调后往往能很好地适应下游任务，但巨大的参数空间使其无法在资源受限的端侧设备上训练。
- **关键词：** LoRA, fine-tuning

### HiFT: A Hierarchical Full Parameter Fine-Tuning Strategy

- **作者：** YongKang Liu, Yiqun Zhang, Qian Li, Tong Liu, Shi Feng, Daling Wang, Yifei Zhang, Hinrich Schuetze
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.1015/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.1015.pdf)
- **中文提要：** 全参数微调因效果好，成为把语言模型适配到下游任务的常用选择；模型规模增大后，更新全部参数所需的 GPU 显存变得难以承受。
- **关键词：** PEFT, fine-tuning

### How Do Your Code LLMs perform? Empowering Code Instruction Tuning with Really Good Data

- **作者：** Yejie Wang, Keqing He, Dayuan Fu, Zhuoma GongQue, Heyang Xu, Yanxu Chen, Zhexu Wang, Yujia Fu, Guanting Dong, Muxi Diao, Jingang Wang, Mengdi Zhang, Xunliang Cai, Weiran Xu
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.777/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.777.pdf)
- **中文提要：** 如何构造更好的代码指令微调数据正受到更多关注；用这些数据训练的代码模型在 HumanEval 上表现较高，但在 LiveCodeBench 等其他基准上更差。
- **关键词：** instruction-tuning, fine-tuning

### I Learn Better If You Speak My Language: Understanding the Superior Performance of Fine-Tuning Large Language Models with LLM-Generated Responses

- **作者：** Xuan Ren, Biao Wu, Lingqiao Liu
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.571/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.571.pdf)
- **中文提要：** 用大语言模型生成的回答来微调大语言模型，在推理任务上往往优于使用人类撰写的回答；作者对此开展了深入考察，以理解这一现象为何出现。
- **关键词：** fine-tuning

### Improving Discriminative Capability of Reward Models in RLHF Using Contrastive Learning

- **作者：** Lu Chen, Rui Zheng, Binghai Wang, Senjie Jin, Caishuang Huang, Junjie Ye, Zhihao Zhang, Yuhao Zhou, Zhiheng Xi, Tao Gui, Qi Zhang, Xuanjing Huang
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.852/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.852.pdf)
- **中文提要：** RLHF 是把语言模型对齐到人类价值与意图的重要途径，其基本挑战在于让奖励模型准确理解并评估人类偏好。
- **关键词：** RLHF, reward-model, alignment

### Improving Spoken Language Modeling with Phoneme Classification: A Simple Fine-tuning Approach

- **作者：** Maxime Poli, Emmanuel Chemla, Emmanuel Dupoux
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.302/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.302.pdf)
- **中文提要：** 口语语言建模的进展表明，直接从语音学习语言是可行的；经由文本层流水线生成语音时，细微差别、语调和非语言发声通常会丢失。
- **关键词：** fine-tuning

### InferAligner: Inference-Time Alignment for Harmlessness through Cross-Model Guidance

- **作者：** Pengyu Wang, Dong Zhang, Linyang Li, Chenkun Tan, Xinghao Wang, Mozhi Zhang, Ke Ren, Botian Jiang, Xipeng Qiu
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.585/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.585.pdf)
- **中文提要：** 大语言模型正通过微调被定制到不同应用的具体需求，而对齐要保证这些模型以符合人类价值与期望的方式完成任务。
- **关键词：** DPO, RLHF, preference-optimization, alignment, fine-tuning

### Instruction Matters: A Simple yet Effective Task Selection for Optimized Instruction Tuning of Specific Tasks

- **作者：** Changho Lee, Janghoon Han, Seonghyeon Ye, Stanley Jungkyu Choi, Honglak Lee, Kyunghoon Bae
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.1036/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.1036.pdf)
- **中文提要：** 指令微调既能提升跨任务的零样本泛化，也能改进特定任务的表现；若针对特定任务，需要有选择地训练那些能提供有效监督的相关任务，这样更有效率，也能避免学习无关任务导致表现下降。
- **关键词：** instruction-tuning, alignment

### Investigating Multilingual Instruction-Tuning: Do Polyglot Models Demand for Multilingual Instructions?

- **作者：** Alexander Arno Weber, Klaudia Thellmann, Jan Ebert, Nicolas Flores-Herr, Jens Lehmann, Michael Fromm, Mehdi Ali
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.1159/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.1159.pdf)
- **中文提要：** 把多语言预训练大模型变成流畅且有帮助的助手，对其在不同语言地区落地很重要，作者在平行的指令微调基准上，系统考察了以不同语言构成做指令微调后的表现。
- **关键词：** instruction-tuning, instruction-following, alignment

### Is It Good Data for Multilingual Instruction Tuning or Just Bad Multilingual Evaluation for Large Language Models?

- **作者：** Pinzhen Chen, Simon Yu, Zhicheng Guo, Barry Haddow
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.542/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.542.pdf)
- **中文提要：** 作者假设当前的微调与评测并不完全符合多语言模型服务多种语言使用者的目标，因为它们严重依赖翻译，既覆盖不了语言特有知识，又可能引入翻译缺陷。
- **关键词：** instruction-tuning, fine-tuning

### Jellyfish: Instruction-Tuning Local Large Language Models for Data Preprocessing

- **作者：** Haochen Zhang, Yuyang Dong, Chuan Xiao, Masafumi Oyamada
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.497/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.497.pdf)
- **中文提要：** 作者探索用大语言模型完成数据挖掘中的数据预处理，把原始数据转成干净格式；他们指令微调可在本地单块低价 GPU 上运行的模型，使其成为通用的预处理任务求解器，以保障数据安全并便于进一步定制。
- **关键词：** instruction-tuning

### KnowTuning: Knowledge-aware Fine-tuning for Large Language Models

- **作者：** Yougang Lyu, Lingyong Yan, Shuaiqiang Wang, Haibo Shi, Dawei Yin, Pengjie Ren, Zhumin Chen, Maarten de Rijke, Zhaochun Ren
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.805/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.805.pdf)
- **中文提要：** 大语言模型在许多自然语言任务上已经成功，但在知识密集型任务中仍难以有效运用知识，会给出不完整、不符合事实或不合逻辑的答案；这些局限来自普通微调时知识意识不足。
- **关键词：** fine-tuning

### Layer by Layer: Uncovering Where Multi-Task Learning Happens in Instruction-Tuned Large Language Models

- **作者：** Zheng Zhao, Yftah Ziser, Shay B. Cohen
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.847/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.847.pdf)
- **中文提要：** 在多样任务上微调预训练大语言模型，是构建能处理多种自然语言任务的模型的常见做法；这些模型在何处、以及在多大程度上保留任务特定知识，仍基本没有被探明。
- **关键词：** instruction-tuning, PEFT, fine-tuning

### Learning Planning-based Reasoning by Trajectories Collection and Process Reward Synthesizing

- **作者：** Fangkai Jiao, Chengwei Qin, Zhengyuan Liu, Nancy F. Chen, Shafiq Joty
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.20/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.20.pdf)
- **中文提要：** 大语言模型能通过逐步生成理由来处理复杂推理，但近期研究对其推理过程中的幻觉与缺陷提出了担忧。
- **关键词：** DPO, preference-optimization, PRM

### Let the Expert Stick to His Last: Expert-Specialized Fine-Tuning for Sparse Architectural Large Language Models

- **作者：** Zihan Wang, Deli Chen, Damai Dai, Runxin Xu, Zhuoshu Li, Yu Wu
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.46/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.46.pdf)
- **中文提要：** 在资源受限时用 PEFT 定制大语言模型很重要；稠密架构已有多种 PEFT 方法，稀疏架构上的 PEFT 仍研究不足。
- **关键词：** PEFT, fine-tuning

### LLaMA-MoE: Building Mixture-of-Experts from LLaMA with Continual Pre-Training

- **作者：** Tong Zhu, Xiaoye Qu, Daize Dong, Jiacheng Ruan, Jingqi Tong, Conghui He, Yu Cheng
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.890/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.890.pdf)
- **中文提要：** 混合专家（MoE）作为扩展大语言模型的框架越来越受关注，但从零开始的大规模训练仍然受困于数据需求高和不稳定。
- **关键词：** continued-pretraining

### LoRA-Guard: Parameter-Efficient Guardrail Adaptation for Content Moderation of Large Language Models

- **作者：** Hayder Elesedy, Pedro M Esperanca, Silviu Vlad Oprea, Mete Ozay
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.656/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.656.pdf)
- **中文提要：** 内容审核中，护栏成为安全对齐之外的一条途径；现有基于模型的护栏并未面向手机等算力有限、且越来越多在本地运行大模型应用的便携设备来设计。
- **关键词：** LoRA, PEFT, alignment

### mDPO: Conditional Preference Optimization for Multimodal Large Language Models

- **作者：** Fei Wang, Wenxuan Zhou, James Y. Huang, Nan Xu, Sheng Zhang, Hoifung Poon, Muhao Chen
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.460/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.460.pdf)
- **中文提要：** DPO 已被证明能有效对齐大语言模型；近期工作尝试将其用于多模态场景，但发现难以获得稳定的提升。
- **关键词：** DPO, preference-optimization, alignment

### Memory-Efficient Fine-Tuning of Transformers via Token Selection

- **作者：** Antoine Simoulin, Namyong Park, Xiaoyi Liu, Grey Yang
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.1202/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.1202.pdf)
- **中文提要：** 微调能让预训练模型适应各种下游任务，但对基于 Transformer 的大模型，尤其是大语言模型，显存开销往往很高。
- **关键词：** LoRA, fine-tuning

### Mitigating the Alignment Tax of RLHF

- **作者：** Yong Lin, Hangyu Lin, Wei Xiong, Shizhe Diao, Jianmeng Liu, Jipeng Zhang, Rui Pan, Haoxiang Wang, Wenbin Hu, Hanning Zhang, Hanze Dong, Renjie Pi, Han Zhao, Nan Jiang, Heng Ji, Yuan Yao, Tong Zhang
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.35/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.35.pdf)
- **中文提要：** 大语言模型在预训练中获得多种能力，但用 RLHF 做对齐可能导致遗忘这些预训练能力，也就是对齐税；作者用现有 RLHF 算法做了实验，在自然语言任务上观察到明显的对齐税。
- **关键词：** RLHF, alignment

### Mitigating Training Imbalance in LLM Fine-Tuning via Selective Parameter Merging

- **作者：** Yiming Ju, Ziyi Ni, Xingrun Xing, Zhixiong Zeng, Hanyu Zhao, Siqi Fan, Zheng Zhang
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.892/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.892.pdf)
- **中文提要：** 监督微调（SFT）对把大语言模型适配到特定任务很关键；训练数据的顺序会造成明显的训练不均衡，并可能使性能下降。
- **关键词：** SFT, fine-tuning

### Mixture-of-Skills: Learning to Optimize Data Usage for Fine-Tuning Large Language Models

- **作者：** Minghao Wu, Thuy-Trang Vu, Lizhen Qu, Reza Haf
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.787/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.787.pdf)
- **中文提要：** 微调大语言模型时，常用来源各异的数据同时培养写作、推理、对话、编程等技能，但各项技能特点不同，数据又异构且不均衡，微调因此很难处理。
- **关键词：** fine-tuning

### Mixture-of-Subspaces in Low-Rank Adaptation

- **作者：** Taiqiang Wu, Jiahao Wang, Zhe Zhao, Ngai Wong
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.450/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.450.pdf)
- **中文提要：** 这项工作提出一种受子空间启发的 LoRA，计算上更省、实现也直接，可用于大语言、多模态和扩散模型：先把 LoRA 权重等价拆成两个子空间，再将二者混合。
- **关键词：** instruction-tuning, LoRA

### Model Balancing Helps Low-data Training and Fine-tuning

- **作者：** Zihang Liu, Yuanzhe Hu, Tianyu Pang, Yefan Zhou, Pu Ren, Yaoqing Yang
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.78/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.78.pdf)
- **中文提要：** 基础模型需要用小规模、经过整理的数据对齐到专门领域，相关研究因此把低数据训练和微调放在更重要的位置。
- **关键词：** fine-tuning

### Model-based Preference Optimization in Abstractive Summarization without Human Feedback

- **作者：** Jaepill Choi, Kyubyung Chae, Jiwoo Song, Yohan Jo, Taesup Kim
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.1048/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.1048.pdf)
- **中文提要：** 生成式摘要要在源文档的大量信息里写出简短且准确的概述；大语言模型虽然行文流畅，却常常编造原文中并不存在的内容。
- **关键词：** DPO, SFT, preference-optimization, fine-tuning

### MoDULA: Mixture of Domain-Specific and Universal LoRA for Multi-Task Learning

- **作者：** Yufei Ma, Zihan Liang, Huangyu Dai, Ben Chen, Dehong Gao, Zhuoran Ran, Wang Zihan, Linbo Jin, Wen Jiang, Guannan Zhang, Xiaoyan Cai, Libin Yang
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.161/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.161.pdf)
- **中文提要：** 更大规模的语言模型在有限算力下很难高效训练，传统微调在多任务学习里又容易不稳定，并且严重依赖大量训练资源。
- **关键词：** LoRA, PEFT, fine-tuning

### Neeko: Leveraging Dynamic LoRA for Efficient Multi-Character Role-Playing Agent

- **作者：** Xiaoyan Yu, Tongxu Luo, Yifan Wei, Fangyu Lei, Yiming Huang, Hao Peng, Liehuang Zhu
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.697/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.697.pdf)
- **中文提要：** 开放域对话代理虽已因大语言模型而改观，多角色扮演场景仍然困难；Neeko 被提出来，作为高效模仿多个角色的框架。
- **关键词：** LoRA

### Not Everything is All You Need: Toward Low-Redundant Optimization for Large Language Model Alignment

- **作者：** Zhipeng Chen, Kun Zhou, Wayne Xin Zhao, Jingyuan Wang, Ji-Rong Wen
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.857/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.857.pdf)
- **中文提要：** 复杂任务和场景中，大语言模型对齐人类偏好仍不顺利，容易过拟合训练数据里意料之外的模式或表面风格。
- **关键词：** reward-model, alignment

### ORPO: Monolithic Preference Optimization without Reference Model

- **作者：** Jiwoo Hong, Noah Lee, James Thorne
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.626/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.626.pdf)
- **中文提要：** 偏好对齐算法已有进展，但要顺利收敛仍离不开监督微调（SFT）；该文回看偏好对齐里的 SFT，强调对不被偏好的风格施加轻微惩罚就足以完成对齐。
- **关键词：** ORPO, SFT, preference-optimization, alignment, fine-tuning

### Parameter-Efficient Sparsity Crafting from Dense to Mixture-of-Experts for Instruction Tuning on General Tasks

- **作者：** Haoyuan Wu, Haisheng Zheng, Zhuolun He, Bei Yu
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.43/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.43.pdf)
- **中文提要：** 大语言模型在通用自然语言处理任务上已经相当熟练，指令微调进一步帮助模型遵循自然语言指令，并在一般任务上表现得更稳健。
- **关键词：** instruction-tuning, PEFT

### Preference-Guided Reflective Sampling for Aligning Language Models

- **作者：** Hai Ye, Hwee Tou Ng
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.1206/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.1206.pdf)
- **中文提要：** 通过反复生成数据并重新训练，可以把大语言模型对齐到人类偏好，而数据如何采样会明显左右策略改进能否成功。
- **关键词：** alignment

### Rethinking Pragmatics in Large Language Models: Towards Open-Ended Evaluation and Preference Tuning

- **作者：** Shengguang Wu, Shusheng Yang, Zhenglun Chen, Qi Su
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.1258/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.1258.pdf)
- **中文提要：** 社会语用推理在大语言模型上既难评估也难加强：基于准确率的选择题不足以衡量这类推理，作者改为直接评估模型的自由形式回答。
- **关键词：** SFT, preference-optimization, fine-tuning

### Rethinking the Role of Proxy Rewards in Language Model Alignment

- **作者：** Sungdong Kim, Minjoon Seo
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.1150/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.1150.pdf)
- **中文提要：** 借助代理奖励建模从人类反馈中学习，是对齐大语言模型的一条路径，但靠这个代理奖励模型做可靠训练并不容易，其行为仍像黑箱。
- **关键词：** reward-model, alignment

### Reuse Your Rewards: Reward Model Transfer for Zero-Shot Cross-Lingual Alignment

- **作者：** Zhaofeng Wu, Ananth Balashankar, Yoon Kim, Jacob Eisenstein, Ahmad Beirami
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.79/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.79.pdf)
- **中文提要：** 用人工标注的偏好数据对齐语言模型，对做出实用系统至关重要，可是多语言人类偏好数据难以大规模取得，这一框架也就很难扩展到多种语言。
- **关键词：** SFT, reward-model, alignment, fine-tuning

### RLHF Can Speak Many Languages: Unlocking Multilingual Preference Optimization for LLMs

- **作者：** John Dang, Arash Ahmadian, Kelly Marchisio, Julia Kreutzer, Ahmet {\"U}st{\"u}n, Sara Hooker
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.729/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.729.pdf)
- **中文提要：** 偏好优化已成为训练前沿大语言模型的常规收尾阶段，不过迄今绝大多数工作只覆盖英语、中文这类高资源语言。
- **关键词：** RLHF, preference-optimization, alignment

### RoseLoRA: Row and Column-wise Sparse Low-rank Adaptation of Pre-trained Language Model for Knowledge Editing and Fine-tuning

- **作者：** Haoyu Wang, Tianci Liu, Ruirui Li, Monica Xiao Cheng, Tuo Zhao, Jing Gao
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.57/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.57.pdf)
- **中文提要：** 大规模语料训练出的预训练语言模型跨任务泛化很强，但面向具体任务微调时通常要更新全部参数，资源开销很大。
- **关键词：** LoRA, PEFT, fine-tuning

### Safety Arithmetic: A Framework for Test-time Safety Alignment of Language Models by Steering Parameters and Activations

- **作者：** Rima Hazra, Sayan Layek, Somnath Banerjee, Soujanya Poria
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.1212/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.1212.pdf)
- **中文提要：** 大语言模型进入翻译、问答等应用后，与人类价值做安全对齐变得关键；现有对齐难以应付动态的用户意图和复杂目标，模型仍可能生成有害内容。
- **关键词：** SFT, alignment, fine-tuning

### Self-Refine Instruction-Tuning for Aligning Reasoning in Language Models

- **作者：** Leonardo Ranaldi, Andre Freitas
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.139/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.139.pdf)
- **中文提要：** 小模型与大模型之间的推理对齐，多靠用强模型生成的示范做监督微调；这样能得到更强的模型，但训练只依赖给定示范，泛化仍然不够强。
- **关键词：** DPO, SFT, instruction-tuning, preference-optimization, alignment, fine-tuning

### Simultaneous Masking, Not Prompting Optimization: A Paradigm Shift in Fine-tuning LLMs for Simultaneous Translation

- **作者：** Matthew Raffel, Victor Agostinelli, Lizhong Chen
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.1017/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.1017.pdf)
- **中文提要：** 多种语言处理任务上的领先表现，促使大语言模型被用于同声传译；现有微调把重点放在提示优化上，具体靠数据增强或修改提示结构。
- **关键词：** fine-tuning

### Speechworthy Instruction-tuned Language Models

- **作者：** Hyundong Justin Cho, Nicolaas Paul Jedema, Leonardo F. R. Ribeiro, Karishma Sharma, Pedro Szekely, Alessandro Moschitti, Ruben Janssen, Jonathan May
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.595/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.595.pdf)
- **中文提要：** 现有指令微调语言模型完全用文本偏好数据训练，未必契合语音模态的要求；作者探索依据广播行业实践设计提示，以及用语音偏好数据做偏好学习。
- **关键词：** instruction-tuning

### Standardize: Aligning Language Models with Expert-Defined Standards for Content Generation

- **作者：** Joseph Marvin Imperial, Gail Forey, Harish Tayyar Madabushi
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.94/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.94.pdf)
- **中文提要：** 工程、医疗和教育领域的专家撰写技术手册、用药说明和儿童读物时要遵守严格标准，而现有可控文本生成还没有把这些标准当作控制时的参照。
- **关键词：** alignment

### Tag-grounded Visual Instruction Tuning with Retrieval Augmentation

- **作者：** Daiqing Qi, Handong Zhao, Zijun Wei, Sheng Li
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.120/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.120.pdf)
- **中文提要：** 多模态大语言模型即便具备一般的视觉指令跟随能力，在需要精确而细致的回答时仍会认不出新的物体或实体、提到不存在的物体，或忽略物体的属性细节。
- **关键词：** instruction-tuning, instruction-following

### Text2Chart31: Instruction Tuning for Chart Generation with Automatic Feedback

- **作者：** Fatemeh Pesaran Zadeh, Juyeon Kim, Jin-Hwa Kim, Gunhee Kim
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.640/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.640.pdf)
- **中文提要：** 指令微调让大语言模型在各类语言任务上很强，但要把复杂的真实世界数据画成图表，模型仍然面临困难。
- **关键词：** SFT, instruction-tuning, fine-tuning

### The Accuracy Paradox in RLHF: When Better Reward Models Don't Yield Better Language Models

- **作者：** Yanjun Chen, Dawei Zhu, Yirong Sun, Xinghao Chen, Wei Zhang, Xiaoyu Shen
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.174/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.174.pdf)
- **中文提要：** 从人类反馈中强化学习把语言模型对齐到人类期望，从而加强自然语言处理，而训练所用奖励模型的强弱是这一对齐的关键因素。
- **关键词：** RLHF, reward-model, alignment

### Towards Aligning Language Models with Textual Feedback

- **作者：** Sa{\"u}c Abadal Lloret, Shehzaad Dhuliawala, Keerthiram Murugesan, Mrinmaya Sachan
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.1129/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.1129.pdf)
- **中文提要：** ALT 用写成文字的用户偏好来对齐语言模型；相比简单的比较式偏好，文本表达更丰富，作者认为这种反馈能让对齐更高效。
- **关键词：** alignment

### Towards Tool Use Alignment of Large Language Models

- **作者：** Zhi-Yuan Chen, Shiqi Shen, Guangyao Shen, Gong Zhi, Xu Chen, Yankai Lin
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.82/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.82.pdf)
- **中文提要：** 让大语言模型使用工具，有助于生成真实且有帮助的回答；已有研究主要集中在增强模型的工具调用能力。
- **关键词：** SFT, instruction-tuning, alignment, fine-tuning

### VideoScore: Building Automatic Metrics to Simulate Fine-grained Human Feedback for Video Generation

- **作者：** Xuan He, Dongfu Jiang, Ge Zhang, Max Ku, Achint Soni, Sherman Siu, Haonan Chen, Abhranil Chandra, Ziyan Jiang, Aaran Arulraj, Kai Wang, Quy Duc Do, Yuansheng Ni, Bohan Lyu, Yaswanth Narsupalli, Rongqi Fan, Zhiheng Lyu, Bill Yuchen Lin, Wenhu Chen
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.127/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.127.pdf)
- **中文提要：** 视频生成近年来进步很快，自动视频评价指标的发展却明显落后。
- **关键词：** RLHF

### Vision-Language Model Fine-Tuning via Simple Parameter-Efficient Modification

- **作者：** Ming Li, Jike Zhong, Chenxin Li, Liuzhuozheng Li, Nie Lin, Masashi Sugiyama
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.797/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.797.pdf)
- **中文提要：** 视觉语言模型的微调近来在提示调参和适配器上见效，直接更新模型固有参数反而被忽略；一种看法是，用少量样本微调这些参数会破坏预训练知识。
- **关键词：** PEFT, fine-tuning

### Weak Reward Model Transforms Generative Models into Robust Causal Event Extraction Systems

- **作者：** Italo Luis Da Silva, Hanqi Yan, Lin Gui, Yulan He
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.816/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.816.pdf)
- **中文提要：** 因果边界本身含糊，使因果事件抽取很难评价；Exact Match 和 BertScore 等传统指标不能很好反映模型表现，作者因而训练评测模型去逼近人工评价。
- **关键词：** reward-model

### WPO: Enhancing RLHF with Weighted Preference Optimization

- **作者：** Wenxuan Zhou, Ravi Agrawal, Shujian Zhang, Sathish Reddy Indurthi, Sanqiang Zhao, Kaiqiang Song, Silei Xu, Chenguang Zhu
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.475/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.475.pdf)
- **中文提要：** 从人类反馈中强化学习（RLHF）有望让大语言模型更贴近人类价值；离策略偏好优化使用其他模型产生的偏好数据，因成本和可扩展性而被广泛采用。
- **关键词：** DPO, RLHF, instruction-following, preference-optimization

### Zero-shot Cross-domain Dialogue State Tracking via Context-aware Auto-prompting and Instruction-following Contrastive Decoding

- **作者：** Xiaoyu Dong, Yujie Feng, Zexin Lu, Guangyuan Shi, Xiao-Ming Wu
- **会议：** EMNLP 2024 · Main
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.485/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.emnlp-main.485.pdf)
- **中文提要：** 零样本跨域对话状态跟踪可以在不采集域内数据的情况下处理未见领域的任务型对话；以往用模式描述、问答格式等改进槽位输入，对已见槽位仍有负迁移，对未见槽位的迁移也不够有效。
- **关键词：** instruction-following

## Findings

### AfriInstruct: Instruction Tuning of African Languages for Diverse Tasks

- **作者：** Kosei Uemura, Mahe Chen, Alex Pejovic, Chika Maduabuchi, Yifei Sun, En-Shiun Annie Lee
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.793/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.793.pdf)
- **中文提要：** 非洲语言上的大语言模型不如在高资源语言上表现好，AfriInstruct 因而针对多种非洲语言、覆盖各类任务做指令微调。
- **关键词：** instruction-tuning, continued-pretraining, fine-tuning

### AlignSum: Data Pyramid Hierarchical Fine-tuning for Aligning with Human Summarization Preference

- **作者：** Yang Han, Yiming Wang, Rui Wang, Lu Chen, Kai Yu
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.498/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.498.pdf)
- **中文提要：** 文本摘要常用预训练语言模型去拟合各种标准数据集；这些模型在自动评测里往往出色，人工评测却经常落后，说明生成摘要偏离了人类的摘要偏好。
- **关键词：** preference-optimization, alignment, fine-tuning

### An Instruction Tuning-Based Contrastive Learning Framework for Aspect Sentiment Quad Prediction with Implicit Aspects and Opinions

- **作者：** Hao Zhang, Yu-N Cheah, Congqing He, Feifan Yi
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.453/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.453.pdf)
- **中文提要：** 方面情感四元组预测在方面级情感分析中很关键，需要从文本里同时识别方面、情感、观点和类别。
- **关键词：** instruction-tuning

### A Study of Parameter Efficient Fine-tuning by Learning to Efficiently Fine-Tune

- **作者：** Taha Ceritli, Savas Ozkan, Jeongwon Min, Eunchung Noh, Cho Jung Min, Mete Ozay
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.929/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.929.pdf)
- **中文提要：** 大语言模型规模持续增大，适配新任务需要参数高效微调（PEFT）；LoRA 等方法通常靠训练这些 PEFT 参数来完成模型适应。
- **关键词：** LoRA, PEFT, fine-tuning

### BAPO: Base-Anchored Preference Optimization for Overcoming Forgetting in Large Language Models Personalization

- **作者：** Gihun Lee, Minchan Jeong, Yujin Kim, Hojung Jung, Jaehoon Oh, SangMook Kim, Se-Young Yun
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.398/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.398.pdf)
- **中文提要：** 把大语言模型对齐到多样的用户偏好时，保留已有知识会遇到进一步的困难；该文考察个性化偏好优化的影响，指出知识损失程度会随偏好异质性明显变化。
- **关键词：** preference-optimization, alignment

### BIPEFT: Budget-Guided Iterative Search for Parameter Efficient Fine-Tuning of Large Pretrained Language Models

- **作者：** Aofei Chang, Jiaqi Wang, Han Liu, Parminder Bhatia, Cao Xiao, Ting Wang, Fenglong Ma
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.437/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.437.pdf)
- **中文提要：** 参数高效微调（PEFT）为大型预训练语言模型的下游适配提供了高效途径，但大多数策略靠手工设计，效果常常不够理想。
- **关键词：** PEFT, fine-tuning

### Breaking the Script Barrier in Multilingual Pre-Trained Language Models with Transliteration-Based Post-Training Alignment

- **作者：** Orgest Xhelili, Yihong Liu, Hinrich Schuetze
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.659/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.659.pdf)
- **中文提要：** 仅根据标题概括：该工作讨论用基于转写的后训练对齐，打破多语言预训练语言模型的文字系统障碍。官方题录没有摘要，此处不补充具体做法或实验结果。
- **关键词：** post-training, alignment

### Calibrating LLMs with Preference Optimization on Thought Trees for Generating Rationale in Science Question Scoring

- **作者：** Jiazheng Li, Hainiu Xu, Zhaoyue Sun, Yuxiang Zhou, David West, Cesare Aloisi, Yulan He
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.313/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.313.pdf)
- **中文提要：** 为评分决定生成解释性理由，有助于提高自动评分系统的可解释性，但现有方法在准确率上仍达不到基于分类器的做法。
- **关键词：** SFT, preference-optimization, fine-tuning

### CantTalkAboutThis: Aligning Language Models to Stay on Topic in Dialogues

- **作者：** Traian Rebedea, Makesh Sreedhar, Shaona Ghosh, Jiaqi Zeng, Christopher Parisien
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.713/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.713.pdf)
- **中文提要：** 近来的指令微调数据多集中在数学或逻辑推理等特定任务，缺少让语言模型在对话中保持话题相关的数据，而这对话机器人投入实际使用十分关键。
- **关键词：** instruction-tuning, instruction-following, alignment, fine-tuning

### Conditional Language Policy: A General Framework For Steerable Multi-Objective Finetuning

- **作者：** Kaiwen Wang, Rahul Kidambi, Ryan Sullivan, Alekh Agarwal, Christoph Dann, Andrea Michi, Marco Gelmi, Yunxuan Li, Raghav Gupta, Kumar Avinava Dubey, Alexandre Rame, Johan Ferret, Geoffrey Cideron, Le Hou, Hongkun Yu, Amr Ahmed, Aranyak Mehta, Leonard Hussenot, Olivier Bachem, Edouard Leurent
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.118/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.118.pdf)
- **中文提要：** 基于奖励的微调对把语言策略对齐到创造性、安全性等预期行为至关重要，难点在于做出可调控的语言模型，以便灵活且高效地权衡多个相互冲突的目标。
- **关键词：** PEFT, alignment, fine-tuning

### Data Diversity Matters for Robust Instruction Tuning

- **作者：** Alexander Bukharin, Shiyang Li, Zhengyang Wang, Jingfeng Yang, Bing Yin, Xian Li, Chao Zhang, Tuo Zhao, Haoming Jiang
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.195/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.195.pdf)
- **中文提要：** 整理出高质量且多样的指令微调数据，能够明显提升指令跟随能力，但构建这类数据很难，多数工作依赖人工整理或专有语言模型。
- **关键词：** instruction-tuning, instruction-following

### Distilling Instruction-following Abilities of Large Language Models with Task-aware Curriculum Planning

- **作者：** Yuanhao Yue, Chengyu Wang, Jun Huang, Peng Wang
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.350/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.350.pdf)
- **中文提要：** 指令微调旨在让大语言模型对齐开放域指令和人类更偏好的回答；从强专有模型自动蒸馏并标注指令的做法，常常忽略任务的分布与特点，也忽略训练中指令难度的差异。
- **关键词：** instruction-tuning, instruction-following

### DLoRA: Distributed Parameter-Efficient Fine-Tuning Solution for Large Language Model

- **作者：** Chao Gao, Sai Qian Zhang
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.802/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.802.pdf)
- **中文提要：** 要提升大语言模型在下游任务上的表现，可以只微调一部分参数，使其更贴合训练数据的特点，这一过程通常称为参数高效微调（PEFT）。
- **关键词：** PEFT, fine-tuning

### Eliciting Instruction-tuned Code Language Models' Capabilities to Utilize Auxiliary Function for Code Generation

- **作者：** Seonghyeon Lee, Suyeon Kim, Joonwon Jang, HeeJae Chon, Dongha Lee, Hwanjo Yu
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.100/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.100.pdf)
- **中文提要：** 该研究考察建立在代码预训练模型上的指令微调模型：当它们可以借助辅助函数来实现目标函数时如何生成代码，并把辅助函数写入查询或作为回答前缀，以便把利用辅助函数的能力与指令跟随结合起来。
- **关键词：** instruction-tuning, instruction-following

### Evolutionary Contrastive Distillation for Language Model Alignment

- **作者：** Julian Katz-Samuels, Zheng Li, Hyokun Yun, Priyanka Nigam, Yi Xu, Vaclav Petricek, Bing Yin, Trishul Chilimbi
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.307/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.307.pdf)
- **中文提要：** 执行复杂指令的能力对大语言模型的实际应用必不可少，但近期多项研究表明，模型面对有挑战的指令时仍然吃力。
- **关键词：** DPO, instruction-following, alignment

### Exploring the Relationship between In-Context Learning and Instruction Tuning

- **作者：** Hanyu Duan, Yixuan Tang, Yi Yang, Ahmed Abbasi, Kar Yan Tam
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.182/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.182.pdf)
- **中文提要：** 上下文学习与指令微调是把大语言模型用于下游应用的两种主要范式，二者的差别相当大。
- **关键词：** instruction-tuning

### FactAlign: Long-form Factuality Alignment of Large Language Models

- **作者：** Chao-Wei Huang, Yun-Nung Chen
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.955/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.955.pdf)
- **中文提要：** 大语言模型有潜力成为下一代信息获取引擎，但幻觉和非事实内容削弱了其可靠性。
- **关键词：** KTO, alignment

### Fighting Randomness with Randomness: Mitigating Optimisation Instability of Fine-Tuning using Delayed Ensemble and Noisy Interpolation

- **作者：** Branislav Pecher, Jan Cegin, Robert Belanec, Jakub Simko, Ivan Srba, Maria Bielikova
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.644/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.644.pdf)
- **中文提要：** 微调预训练语言模型有助于缓解标注样本不足，同时也会带来性能不稳定，而这种不稳定主要来自初始化或数据打乱中的随机性。
- **关键词：** PEFT, fine-tuning

### From Complex to Simple: Enhancing Multi-Constraint Complex Instruction Following Ability of Large Language Models

- **作者：** Qianyu He, Jie Zeng, Qianxi He, Jiaqing Liang, Yanghua Xiao
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.637/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.637.pdf)
- **中文提要：** 大语言模型必须能够遵循带有细致要求的指令，也就是复杂指令跟随。
- **关键词：** instruction-following

### How Reliable Are Automatic Evaluation Methods for Instruction-Tuned LLMs?

- **作者：** Ehsan Doostmohammadi, Oskar Holmstr{\"o}m, Marco Kuhlmann
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.367/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.367.pdf)
- **中文提要：** 指令微调大语言模型的研究常把基于文本重合和模型评判的自动方法当作人工评测的低成本替代；该研究对这些方法做元评估，并在广泛任务上考察其可靠性。
- **关键词：** instruction-tuning

### Improving Argument Effectiveness Across Ideologies using Instruction-tuned Large Language Models

- **作者：** Roxanne El Baff, Khalid Al Khatib, Milad Alshomary, Kai Konen, Benno Stein, Henning Wachsmuth
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.265/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.265.pdf)
- **中文提要：** 自由派与保守派等不同政治意识形态持有不同世界观，在控枪等问题上立场对立，从而加剧社会极化；论辩能否拉近这些视角，取决于它能在多大程度上传达到受众。
- **关键词：** instruction-tuning

### Improving Factual Consistency of News Summarization by Contrastive Preference Optimization

- **作者：** Huawen Feng, Yan Fan, Xiong Liu, Ting-En Lin, Zekun Yao, Yuchuan Wu, Fei Huang, Yongbin Li, Qianli Ma
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.648/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.648.pdf)
- **中文提要：** 大语言模型推进了新闻摘要，却仍常写出与原文事实不一致的内容；相比以往较小的模型，当前模型较少犯低级错误，但更多出现强加因果、添加虚假细节或过度概括这类更隐蔽的问题。
- **关键词：** preference-optimization

### Improving Multilingual Instruction Finetuning via Linguistically Natural and Diverse Datasets

- **作者：** Sathish Reddy Indurthi, Wenxuan Zhou, Shamil Chollampatt, Ravi Agrawal, Kaiqiang Song, Lingxiao Zhao, Chenguang Zhu
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.128/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.128.pdf)
- **中文提要：** 指令跟随能力随着大语言模型的发展明显增强，然而大多数指令微调数据集以英语为主，限制了模型在其他语言上的表现。
- **关键词：** instruction-following, fine-tuning

### Inference-Time Language Model Alignment via Integrated Value Guidance

- **作者：** Zhixuan Liu, Zhanhui Zhou, Yuanfu Wang, Chao Yang, Yu Qiao
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.242/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.242.pdf)
- **中文提要：** 把大语言模型微调到符合人类偏好，计算开销大且过程复杂；Integrated Value Guidance（IVG）分别用隐式与显式价值函数，在词元级和片段级引导解码，从而只在推理时完成对齐。
- **关键词：** instruction-following, alignment, fine-tuning

### Interpretable Preferences via Multi-Objective Reward Modeling and Mixture-of-Experts

- **作者：** Haoxiang Wang, Wei Xiong, Tengyang Xie, Han Zhao, Tong Zhang
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.620/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.620.pdf)
- **中文提要：** 从人类反馈中强化学习（RLHF）已成为对齐大语言模型与人类偏好的主要方法，流程通常先用人类偏好数据训练奖励模型。
- **关键词：** RLHF, reward-model, alignment

### Inverse-Q*: Token Level Reinforcement Learning for Aligning Large Language Models Without Preference Data

- **作者：** Han Xia, Songyang Gao, Qiming Ge, Zhiheng Xi, Qi Zhang, Xuanjing Huang
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.478/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.478.pdf)
- **中文提要：** 近端策略优化（PPO）一类方法虽常用于 RLHF，却需要大量超参调节，样本效率与稳定性也成问题，文中提出 Inverse-Q* 框架。
- **关键词：** DPO, RLHF, preference-optimization, alignment

### Knowledge Editing in Language Models via Adapted Direct Preference Optimization

- **作者：** Amit Rozner, Barak Battash, Lior Wolf, Ofir Lindenbaum
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.273/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.273.pdf)
- **中文提要：** 大语言模型会随时间过时，缺少更新后的世界知识，从而出现事实错误和知识空白；知识编辑希望用权重更新来应对，而不必付出昂贵的重新训练。
- **关键词：** DPO, preference-optimization, alignment

### LaMDA: Large Model Fine-Tuning via Spectrally Decomposed Low-Dimensional Adaptation

- **作者：** Seyedarmin Azizi, Souvik Kundu, Massoud Pedram
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.563/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.563.pdf)
- **中文提要：** LoRA 因大幅减少可训练参数，已成为微调大语言模型的默认途径；可训练参数的需求却随嵌入维度增大而上升，计算成本仍然很高。
- **关键词：** LoRA, fine-tuning

### Layer-wise Importance Matters: Less Memory for Better Performance in Parameter-efficient Fine-tuning of Large Language Models

- **作者：** Kai Yao, Penglei Gao, Lichun Li, Yuan Zhao, Xiaofeng Wang, Wei Wang, Jianke Zhu
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.109/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.109.pdf)
- **中文提要：** 参数高效微调（PEFT）能降低显存和计算开销，因而被广泛用于把预训练大语言模型适配到下游任务；多数方法的共同局限是在所有层上采用统一的结构设计。
- **关键词：** PEFT, fine-tuning

### Learning to Ask Informative Questions: Enhancing LLMs with Preference Optimization and Expected Information Gain

- **作者：** Davide Mazzaccara, Alberto Testoni, Raffaella Bernardi
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.291/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.291.pdf)
- **中文提要：** 提问是完成信息寻求任务的基本手段，但大语言模型、尤其是开源模型，在以期望信息增益（EIG）衡量的信息性提问上往往表现不佳。
- **关键词：** DPO, preference-optimization

### Leveraging Web-Crawled Data for High-Quality Fine-Tuning

- **作者：** Jing Zhou, Chenglin Jiang, Wei Shen, Xiao Zhou, Xiaonan He
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.660/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.660.pdf)
- **中文提要：** 多数大语言模型的微调要么依赖昂贵的人工标注，要么依赖 GPT-4 生成的数据，而后者在某些领域并不能保证效果。作者认为，网页爬取数据虽常有格式错误并造成语义不准，仍可作为特定领域高质量监督微调的来源，而不必依赖 GPT-4 这类先进模型。
- **关键词：** SFT, alignment, fine-tuning

### LongAlign: A Recipe for Long Context Alignment of Large Language Models

- **作者：** Yushi Bai, Xin Lv, Jiajie Zhang, Yuze He, Ji Qi, Lei Hou, Jie Tang, Yuxiao Dong, Juanzi Li
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.74/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.74.pdf)
- **中文提要：** 要让大语言模型有效处理长上下文，需要在长度相近的输入序列上做指令微调。LongAlign 给出一套长上下文对齐的做法，涵盖指令数据、训练与评测。
- **关键词：** SFT, instruction-following, alignment, fine-tuning

### LongForm: Effective Instruction Tuning with Reverse Instructions

- **作者：** Abdullatif K{\"o}ksal, Timo Schick, Anna Korhonen, Hinrich Schuetze
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.414/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.414.pdf)
- **中文提要：** 指令微调能让语言模型更好地泛化并遵循用户意图，但指令数据的获取既贵又难。
- **关键词：** instruction-tuning, alignment

### LoRAN: Improved Low-Rank Adaptation by a Non-Linear Transformation

- **作者：** Yinqiao Li, Linqi Song, Hanxu Hou
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.177/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.177.pdf)
- **中文提要：** 针对大型预训练模型的参数高效微调，LoRAN 在 LoRA 中引入非线性变换，以缓解受约束适配器带来的性能损失。
- **关键词：** LoRA, PEFT, fine-tuning

### LoRASC: Expressive and Generalizable Low-rank Adaptation for Large Models via Slow Cascaded Learning

- **作者：** Siwei Li, Yifan Yang, Yifei Shen, Fangyun Wei, Zongqing Lu, Lili Qiu, Yuqing Yang
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.748/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.748.pdf)
- **中文提要：** 高效微调对现代大模型至关重要，低秩适应是其中较有前景的路线。现有 LoRA 变体却受限于表达能力不足、容易过拟合，并且对超参数设置敏感。
- **关键词：** LoRA, fine-tuning

### Margin Matching Preference Optimization: Enhanced Model Alignment with Granular Feedback

- **作者：** Kyuyoung Kim, Ah Jeong Seo, Hao Liu, Jinwoo Shin, Kimin Lee
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.792/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.792.pdf)
- **中文提要：** 经过 RLHF 等对齐技术微调的大语言模型，支撑了一批迄今能力很强的人工智能系统。现有方法通常只使用成对偏好里的简单二元标签，难以捕捉相对质量上的细微差别。
- **关键词：** RLHF, preference-optimization, reward-model, alignment, fine-tuning

### MELT: Materials-aware Continued Pre-training for Language Model Adaptation to Materials Science

- **作者：** Junho Kim, Yeachan Kim, Jun-Hyung Park, Yerim Oh, Suho Kim, SangKeun Lee
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.627/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.627.pdf)
- **中文提要：** 为把预训练语言模型高效适配到材料科学，MELT 提出一种材料感知的持续预训练。它不像以往只着眼于构建领域语料，而是同时考虑语料和训练策略。
- **关键词：** continued-pretraining

### MiLoRA: Efficient Mixture of Low-Rank Adaptation for Large Language Models Fine-tuning

- **作者：** Jingfan Zhang, Yi Zhao, Dan Chen, Xing Tian, Huanran Zheng, Wei Zhu
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.994/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.994.pdf)
- **中文提要：** LoRA 及其混合专家变体是很有效的 PEFT 方法。但在多租户环境中，加到 Transformer 层多个线性模块上的 LoRA 模块和混合专家路由会带来明显延迟。
- **关键词：** LoRA, PEFT, fine-tuning

### Negating Negatives: Alignment with Human Negative Samples via Distributional Dispreference Optimization

- **作者：** Shitong Duan, Xiaoyuan Yi, Peng Zhang, Yan Liu, Zheng Liu, Tun Lu, Xing Xie, Ning Gu
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.56/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.56.pdf)
- **中文提要：** 大语言模型改变了人工智能的角色，同时也带来潜在的社会风险。为把模型导向人类偏好，对齐技术被引入并受到越来越多关注。
- **关键词：** DPO, preference-optimization, alignment

### On Diversified Preferences of Large Language Model Alignment

- **作者：** Dun Zeng, Yong Dai, Pengyu Cheng, Longyue Wang, Tianhao Hu, Wanshun Chen, Nan Du, Zenglin Xu
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.538/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.538.pdf)
- **中文提要：** 将大语言模型与人类偏好对齐，已被视为提升交互质量的关键。在多元社会里，标注者口味不同会使偏好发生分化，从而妨碍对齐方法发挥作用。
- **关键词：** reward-model, alignment

### On the Limited Generalization Capability of the Implicit Reward Model Induced by Direct Preference Optimization

- **作者：** Yong Lin, Skyler Seto, Maartje Ter Hoeve, Katherine Metcalf, Barry-John Theobald, Xuan Wang, Yizhe Zhang, Chen Huang, Tong Zhang
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.940/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.940.pdf)
- **中文提要：** 用人类反馈的强化学习可以把语言模型对齐到人类偏好。这一流程的核心，是学习一个能为人类偏好打分的奖励函数。
- **关键词：** DPO, RLHF, preference-optimization, reward-model, alignment

### Pedagogical Alignment of Large Language Models

- **作者：** Shashank Sonkar, Kangqi Ni, Sapana Chaudhary, Richard Baraniuk
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.797/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.797.pdf)
- **中文提要：** 大语言模型若未经面向教学的微调就用于教育，往往直接给出答案，而不是引导学生完成解题过程。这种做法偏离教学上较好的实践，也限制了它们作为教育工具的效果。
- **关键词：** SFT, alignment, fine-tuning

### Preference Tuning For Toxicity Mitigation Generalizes Across Languages

- **作者：** Xiaochen Li, Zheng Xin Yong, Stephen Bach
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.784/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.784.pdf)
- **中文提要：** 多语言大语言模型的全球使用不断增加，去毒因此变得关键。该研究探索偏好调优在大模型去毒上的零样本跨语言泛化。
- **关键词：** DPO, preference-optimization

### Promoting Data and Model Privacy in Federated Learning through Quantized LoRA

- **作者：** Zhu JianHao, Changze Lv, Xiaohua Wang, Muling Wu, Wenhao Liu, Tianlong Li, Zixuan Ling, Cenyuan Zhang, Xiaoqing Zheng, Xuanjing Huang
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.615/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.615.pdf)
- **中文提要：** 常规联邦学习主要想保护分布在多个边缘设备上的数据隐私，学习过程中会把全局模型下发到边缘设备做参数更新。大语言模型的开发需要大量数据和计算资源，模型因而成为开发者与所有者的宝贵知识产权。
- **关键词：** LoRA, PEFT, fine-tuning

### PURE: Aligning LLM via Pluggable Query Reformulation for Enhanced Helpfulness

- **作者：** Wenjin Yao, Yidong Wang, Zhuohao Yu, Rui Xie, Shikun Zhang, Wei Ye
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.509/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.509.pdf)
- **中文提要：** 让大语言模型对齐人类价值与偏好是一项重大挑战。RLHF 和 DPO 这类基于训练的方法资源需求高，对只能经 API 调用的模型并不现实。
- **关键词：** DPO, RLHF, preference-optimization, alignment

### QEFT: Quantization for Efficient Fine-Tuning of LLMs

- **作者：** Changhun Lee, Jun-gyu Jin, YoungHyun Cho, Eunhyeok Park
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.811/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.811.pdf)
- **中文提要：** 微调大语言模型的使用增长很快，如何在优化微调的同时保持推理高效变得非常重要。这件事很难，因为推理速度、微调速度、内存占用以及模型质量都需要改进。
- **关键词：** PEFT, fine-tuning

### Reward Difference Optimization For Sample Reweighting In Offline RLHF

- **作者：** Shiqi Wang, Zhengze Zhang, Rui Zhao, Fei Tan, Cam Tu Nguyen
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.115/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.115.pdf)
- **中文提要：** 随着大语言模型被广泛部署，使其对齐人类价值越来越重要。RLHF 虽然被证明有效，但过程复杂且非常耗费资源。
- **关键词：** RLHF, alignment

### Reward Modeling Requires Automatic Adjustment Based on Data Quality

- **作者：** Binghai Wang, Rui Zheng, Lu Chen, Zhiheng Xi, Wei Shen, Yuhao Zhou, Dong Yan, Tao Gui, Qi Zhang, Xuanjing Huang
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.234/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.234.pdf)
- **中文提要：** RLHF 里的奖励模型对把语言模型输出对齐到人类价值起着关键作用。训练所用的人类偏好数据包含一个提示和一对回答，由人标注哪一条更符合价值偏好。
- **关键词：** RLHF, reward-model, alignment

### RoLoRA: Fine-tuning Rotated Outlier-free LLMs for Effective Weight-Activation Quantization

- **作者：** Xijie Huang, Zechun Liu, Shih-Yang Liu, Kwang-Ting Cheng
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.444/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.444.pdf)
- **中文提要：** 作为代表性 PEFT 方法，LoRA 只更新大语言模型中一小部分权重，从而显著提高训练效率。近期也有仅权重量化被用到 LoRA 上，以减小微调的内存占用。
- **关键词：** LoRA, PEFT, post-training, fine-tuning

### Scalable Fine-tuning from Multiple Data Sources: A First-Order Approximation Approach

- **作者：** Dongyue Li, Ziniu Zhang, Lu Wang, Hongyang R. Zhang
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.321/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.321.pdf)
- **中文提要：** 问题在于如何最优利用多个辅助任务中的信息，把语言模型微调到目标任务。这一设定在自然语言处理中用途很广，例如针对性指令微调，以及思维链微调里的数据选择。
- **关键词：** instruction-tuning, fine-tuning

### Self-Evolution Fine-Tuning for Policy Optimization

- **作者：** Ruijun Chen, Jiehao Liang, Shiping Gao, Fanqi Wan, Xiaojun Quan
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.238/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.238.pdf)
- **中文提要：** 大语言模型对齐不仅关系到释放特定任务上的潜力，也关系到回答是否符合人类预期并遵守安全与伦理原则。自演化微调 SEFT 针对当前对齐方法的困难，试图在对齐中取消对标注样本的依赖。
- **关键词：** SFT, alignment, fine-tuning

### Self-supervised Preference Optimization: Enhance Your Language Model with Preference Degree Awareness

- **作者：** Jian Li, Haojing Huang, Yujia Zhang, Pengfei Xu, Xi Chen, Rui Song, Lida Shi, Jingwen Wang, Hao Xu
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.845/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.845.pdf)
- **中文提要：** 近来很多人希望用 DPO 及其变体取代 RLHF 中的奖励模型。这些方法通常在成对样本上采用二元交叉熵，按偏好或非偏好回答分别减小或增大损失。
- **关键词：** DPO, RLHF, preference-optimization, reward-model, alignment

### Semi-Supervised Reward Modeling via Iterative Self-Training

- **作者：** Yifei He, Haoxiang Wang, Ziyan Jiang, Alexandros Papangelis, Han Zhao
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.434/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.434.pdf)
- **中文提要：** 奖励模型刻画人类的价值与偏好，并在 RLHF 中居于核心，用来对齐预训练大语言模型。传统训练依赖大量人工标注的偏好数据，在可扩展性和成本上都很困难。
- **关键词：** RLHF, SFT, reward-model, fine-tuning

### Step-level Value Preference Optimization for Mathematical Reasoning

- **作者：** Guoxin Chen, Minpeng Liao, Chengxi Li, Kai Fan
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.463/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.463.pdf)
- **中文提要：** 使用隐式奖励模型的 DPO，已被证明是 RLHF 之外、用于微调偏好对齐大语言模型的有效替代。然而，回答的整体偏好标注并不能充分反映复杂多步推理（如数学推理）中输出的细粒度质量。
- **关键词：** DPO, RLHF, preference-optimization, reward-model, fine-tuning

### Suri: Multi-constraint Instruction Following in Long-form Text Generation

- **作者：** Chau Minh Pham, Simeng Sun, Mohit Iyyer
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.94/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.94.pdf)
- **中文提要：** 已有的指令遵循研究大多关注指令简单、回答较短的任务。这里转而探索长文本生成中的多约束指令遵循。
- **关键词：** DPO, ORPO, SFT, instruction-following, alignment, fine-tuning

### The SIFo Benchmark: Investigating the Sequential Instruction Following Ability of Large Language Models

- **作者：** Xinyi Chen, Baohao Liao, Jirui Qi, Panagiotis Eustratiadis, Christof Monz, Arianna Bisazza, Maarten de Rijke
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.92/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.92.pdf)
- **中文提要：** 同时遵循多条指令是大语言模型的一项关键能力，但评测它并不容易：多条指令之间往往缺乏连贯性，指令顺序会带来位置偏差，而且缺少可以客观验证的任务。
- **关键词：** instruction-following

### Towards Pareto-Efficient RLHF: Paying Attention to a Few High-Reward Samples with Reward Dropout

- **作者：** Changhun Lee, Chiehyeon Lim
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.489/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.489.pdf)
- **中文提要：** 借助强化学习、以人类反馈微调语言模型（即 RLHF）近来成为重要研究方向。理论上仍不清楚 RLHF 如何运作、在什么条件下成功或失败，以及它能否同时优化似然与奖励两类目标。
- **关键词：** RLHF, fine-tuning

### TS-Align: A Teacher-Student Collaborative Framework for Scalable Iterative Finetuning of Large Language Models

- **作者：** Chen Zhang, Chengguang Tang, Dading Chong, Ke Shi, Guohua Tang, Feng Jiang, Haizhou Li
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.521/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.521.pdf)
- **中文提要：** 主流的大语言模型对齐高度依赖人类偏好数据，尤其是在模型需要周期性更新时。迭代对齐的标准流程，是每次更新都重新收集人类反馈。
- **关键词：** instruction-following, reward-model, alignment, fine-tuning

### V-DPO: Mitigating Hallucination in Large Vision Language Models via Vision-Guided Direct Preference Optimization

- **作者：** Yuxi Xie, Guanzhen Li, Xiao Xu, Min-Yen Kan
- **会议：** EMNLP 2024 · Findings
- **官方论文页：** https://aclanthology.org/2024.findings-emnlp.775/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2024.findings-emnlp.775.pdf)
- **中文提要：** 大型视觉语言模型会幻觉，使输出文本与输入视觉内容错位。近期研究认为，过度依赖语言模型骨干是原因之一，语言先验会由此带入偏差，导致对视觉输入的上下文关注不足。
- **关键词：** DPO, preference-optimization
