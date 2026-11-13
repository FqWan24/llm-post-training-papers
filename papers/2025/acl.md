# 2025 · ACL

共 236 篇。Main 145，Findings 91，其他赛道 0。其中 0 篇来源题录无摘要，提要标明「仅根据标题概括」。

检索窗口为 2024-11-13 至 2026-11-13。题录信息来自官方列表，不在此增补作者、链接或实验数字。

## Main

### AdaDHP: Fine-Grained Fine-Tuning via Dual Hadamard Product and Adaptive Parameter Selection

- **作者：** Han Liu, Changya Li, Xiaotong Zhang, Feng Zhang, Fenglong Ma, Wei Wang, Hong Yu
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.467/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.467.pdf)
- **中文提要：** 参数持续扩大之后，在资源有限的条件下把大模型高效适配到下游任务变得关键。为此已经出现多种参数高效微调方法。
- **关键词：** LoRA, PEFT, fine-tuning

### Adapt Once, Thrive with Updates: Transferable Parameter-Efficient Fine-Tuning on Evolving Base Models

- **作者：** Naibin Gu, Peng Fu, Xiyu Liu, Ke Ma, Zheng Lin, Weiping Wang
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.719/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.719.pdf)
- **中文提要：** 参数高效微调已很常用：基座模型通过切换不同模块服务多个用户。要继续改善使用体验，基座本身还需要周期性更新。
- **关键词：** PEFT, fine-tuning

### Advancing Zero-shot Text-to-Speech Intelligibility across Diverse Domains via Preference Alignment

- **作者：** Xueyao Zhang, Yuancheng Wang, Chaoren Wang, Ziniu Li, Zhuo Chen, Zhizheng Wu
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.598/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.598.pdf)
- **中文提要：** 现代零样本语音合成尽管经过大规模预训练，在绕口令、重复词语、语码转换和跨语言合成等场景中仍会出现可懂度问题。该工作借助偏好对齐，以便有针对地构造落在预训练分布之外的数据。
- **关键词：** DPO, preference-optimization, alignment

### Agentic Reward Modeling: Integrating Human Preferences with Verifiable Correctness Signals for Reliable Reward Systems

- **作者：** Hao Peng, Yunjia Qi, Xiaozhi Wang, Zijun Yao, Bin Xu, Lei Hou, Juanzi Li
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.775/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.775.pdf)
- **中文提要：** 奖励模型对大模型的训练以及推理时扩展都很关键。现有奖励模型主要关注人类偏好，较少利用已显示出较强潜力的可验证正确性信号。
- **关键词：** DPO, instruction-following, reward-model

### Agent-RewardBench: Towards a Unified Benchmark for Reward Modeling across Perception, Planning, and Safety in Real-World Multimodal Agents

- **作者：** Tianyi Men, Zhuoran Jin, Pengfei Cao, Yubo Chen, Kang Liu, Jun Zhao
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.857/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.857.pdf)
- **中文提要：** 随着多模态大模型的进展，多模态智能体在网页导航和具身智能等真实任务上显示出潜力。由于缺少外部反馈，这些智能体在自我纠正和泛化上仍然吃力。
- **关键词：** reward-model

### AgentRM: Enhancing Agent Generalization with Reward Modeling

- **作者：** Yu Xia, Jingru Fan, Weize Chen, Siyu Yan, Xin Cong, Zhong Zhang, Yaxi Lu, Yankai Lin, Zhiyuan Liu, Maosong Sun
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.945/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.945.pdf)
- **中文提要：** 现有基于大模型的智能体在见过的任务上表现已经很强，但对未见任务的泛化仍然差。近期一些工作转而用更多样的任务去微调策略模型，以改善泛化。
- **关键词：** reward-model, fine-tuning

### AlignDistil: Token-Level Language Model Alignment as Adaptive Policy Distillation

- **作者：** Songming Zhang, Xue Zhang, Tong Zhang, Bojie Hu, Yufeng Chen, Jinan Xu
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.972/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.972.pdf)
- **中文提要：** 大模型对齐通常依靠 RLHF 或直接偏好优化（DPO）来完成。现有方法里，回答中的每个词元往往都由稀疏的整句级奖励或偏好标注来优化。
- **关键词：** DPO, RLHF, preference-optimization, reward-model, alignment

### Aligning Large Language Models to Follow Instructions and Hallucinate Less via Effective Data Filtering

- **作者：** Shuzheng Si, Haozhe Zhao, Gang Chen, Cheng Gao, Yuzhuo Bai, Zhitong Wang, Kaikai An, Kangyang Luo, Chen Qian, Fanchao Qi, Baobao Chang, Maosong Sun
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.804/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.804.pdf)
- **中文提要：** 指令微调若使用含有模型不熟悉知识的数据，会鼓励幻觉。NOVA 用来识别与模型已学知识更一致的高质量数据，从而减少幻觉。
- **关键词：** instruction-tuning, reward-model, alignment

### Aligning Large Language Models with Implicit Preferences from User-Generated Content

- **作者：** Zhaoxuan Tan, Zheng Li, Tianyi Liu, Haodong Wang, Hyokun Yun, Ming Zeng, Pei Chen, Zhihan Zhang, Yifan Gao, Ruijie Wang, Priyanka Nigam, Bing Yin, Meng Jiang
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.384/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.384.pdf)
- **中文提要：** 从偏好反馈中学习，对让大模型贴合人类价值、提高生成质量都很必要。现有偏好学习却严重依赖人工或更强模型整理的数据，成本高且难以扩展。
- **关键词：** DPO, alignment

### Align-SLM: Textless Spoken Language Models with Reinforcement Learning from AI Feedback

- **作者：** Guan-Ting Lin, Prashanth Gurunath Shivakumar, Aditya Gourav, Yile Gu, Ankur Gandhe, Hung-yi Lee, Ivan Bulyko
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.997/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.997.pdf)
- **中文提要：** 无文本的口语语言模型已能做端到端的语音到语音建模，但在语义连贯性和相关性上仍落后于文本大模型。Align-SLM 借鉴 RLHF 式的偏好优化来加强其语义理解。
- **关键词：** DPO, RLHF, RLAIF, preference-optimization

### A Modular Approach for Clinical SLMs Driven by Synthetic Data with Pre-Instruction Tuning, Model Merging, and Clinical-Tasks Alignment

- **作者：** Jean-Philippe Corbeil, Amin Dada, Jean-Michel Attendu, Asma Ben Abacha, Alessandro Sordoni, Lucas Caccia, Francois Beaulieu, Thomas Lin, Jens Kleesiek, Paul Vozila
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.950/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.950.pdf)
- **中文提要：** 大语言模型的计算成本与延迟限制了临床部署。小语言模型是更省成本的替代，但容量有限，生物医学领域适配仍然困难。
- **关键词：** DPO, SFT, instruction-tuning, preference-optimization, alignment, fine-tuning

### Analyzing the Rapid Generalization of SFT via the Perspective of Attention Head Activation Patterns

- **作者：** Yang Zhao, Li Du, Xiao Ding, Kai Xiong, Ting Liu, Bing Qin
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.831/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.831.pdf)
- **中文提要：** 大模型在复杂任务上的表现仍不理想。一个关键原因是学习高度依赖数据，而这些复杂任务的指令既稀缺，又难以收集或构造。
- **关键词：** SFT

### An Efficient and Precise Training Data Construction Framework for Process-supervised Reward Model in Mathematical Reasoning

- **作者：** Wei Sun, Qianlong Du, Fuwei Cui, Jiajun Zhang
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.216/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.216.pdf)
- **中文提要：** 增强大模型的数学推理兼具科学意义和实用价值。研究者通常用过程监督奖励模型引导推理过程，从而提升模型的推理能力。
- **关键词：** PRM, reward-model

### A Survey of Post-Training Scaling in Large Language Models

- **作者：** Hanyu Lai, Xiao Liu, Junjie Gao, Jiale Cheng, Zehan Qi, Yifan Xu, Shuntian Yao, Dan Zhang, Jinhua Du, Zhenyu Hou, Xin Lv, Minlie Huang, Yuxiao Dong, Jie Tang
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.140/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.140.pdf)
- **中文提要：** 大模型之所以擅长理解和生成自然语言，主要得益于在语言建模损失、参数量与预训练词元之间建立缩放关系。高质量互联网语料趋于耗尽、计算需求又在上升，预训练缩放能否持续就成了问题。
- **关键词：** SFT, post-training, alignment, fine-tuning

### AutoMixAlign: Adaptive Data Mixing for Multi-Task Preference Optimization in LLMs

- **作者：** Nicholas E. Corrado, Julian Katz-Samuels, Adithya M Devraj, Hyokun Yun, Chao Zhang, Yi Xu, Yi Pan, Bing Yin, Trishul Chilimbi
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.990/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.990.pdf)
- **中文提要：** 对齐大模型时，有帮助、无害、诚实等各项表现很大程度受训练数据组成的影响。究竟怎样混合数据才能让所有任务都强，却很难确定。
- **关键词：** DPO, preference-optimization, alignment

### Balancing the Budget: Understanding Trade-offs Between Supervised and Preference-Based Finetuning

- **作者：** Mohit Raghavendra, Junmo Kang, Alan Ritter
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.1248/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.1248.pdf)
- **中文提要：** 大模型后训练常常先做监督微调，再用直接偏好优化等方法做偏好微调。两个阶段都需要标注数据，但数据的结构和成本差别很大。
- **关键词：** DPO, SFT, preference-optimization, post-training, fine-tuning

### BeamLoRA: Beam-Constraint Low-Rank Adaptation

- **作者：** Naibin Gu, Zhenyu Zhang, Xiyu Liu, Peng Fu, Zheng Lin, Shuohuan Wang, Yu Sun, Hua Wu, Weiping Wang, Haifeng Wang
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.582/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.582.pdf)
- **中文提要：** 出于高效微调大模型的需要，低秩适配（LoRA）已成为广泛采用的参数高效方法之一。它提升了效率，精度上仍有改进余地。
- **关键词：** LoRA, PEFT, fine-tuning

### Beware of Your Po! Measuring and Mitigating AI Safety Risks in Role-Play Fine-Tuning of LLMs

- **作者：** Weixiang Zhao, Yulin Hu, Yang Deng, Jiahe Guo, Xingyu Sui, Xinyang Han, An Zhang, Yanyan Zhao, Bing Qin, Tat-Seng Chua, Ting Liu
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.544/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.544.pdf)
- **中文提要：** 角色扮演让大模型能做沉浸、个性化的交互，同时也带来显著的安全风险。现有角色扮演微调提高了角色适应能力，却可能损害安全性，反派角色上尤其明显。
- **关键词：** LoRA, fine-tuning

### Beyond Demographics: Fine-tuning Large Language Models to Predict Individuals' Subjective Text Perceptions

- **作者：** Matthias Orlikowski, Jiaxin Pei, Paul R{\"o}ttger, Philipp Cimiano, David Jurgens, Dirk Hovy
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.104/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.104.pdf)
- **中文提要：** 人们对主观问题的标注本来就有差异，其中一部分被认为来自社会人口特征。用这些属性去提示大模型做标注时效果很差，说明模型自带的相关知识有限。
- **关键词：** fine-tuning

### Beyond Similarity: A Gradient-based Graph Method for Instruction Tuning Data Selection

- **作者：** Yang Zhao, Li Du, Xiao Ding, Yangou Ouyang, Hepeng Wang, Kai Xiong, Jinglong Gao, Zhouhao Sun, Dongliang Xu, Qing Yang, Dongchen Li, Bing Qin, Ting Liu
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.1189/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.1189.pdf)
- **中文提要：** 大模型凭借指令微调展现出跨行业泛化的潜力。领域专用数据不足，却会明显限制它们在专业任务上的表现。
- **关键词：** instruction-tuning

### Binary Classifier Optimization for Large Language Model Alignment

- **作者：** Seungjae Jung, Gunsoo Han, Daniel Wontae Nam, Kyoung-Woon On
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.93/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.93.pdf)
- **中文提要：** 在 ChatGPT 这类真实服务中，按用户反馈做对齐对提升模型表现很重要。由于反馈要简单方便，用户通常只给出点赞或点踩这类基本二元信号。
- **关键词：** DPO, preference-optimization, alignment

### Call for Rigor in Reporting Quality of Instruction Tuning Data

- **作者：** Hyeonseok Moon, Jaehyung Seo, Heuiseok Lim
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-short.9/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-short.9.pdf)
- **中文提要：** 指令微调对让大模型贴合用户意图至关重要。不少研究强调指令微调数据的质量，并揭示它与大模型的对齐表现密切相关。
- **关键词：** instruction-tuning, alignment

### CC-Tuning: A Cross-Lingual Connection Mechanism for Improving Joint Multilingual Supervised Fine-Tuning

- **作者：** Yangfan Ye, Xiaocheng Feng, Zekun Yuan, Xiachong Feng, Libo Qin, Lei Huang, Weitao Ma, Yichong Huang, Zhirui Zhang, Yunfei Lu, Xiaohui Yan, Duyu Tang, Dandan Tu, Bing Qin
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.933/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.933.pdf)
- **中文提要：** 英语语料为主，使当前大模型的多语言能力并不均衡。数据层面的微调，例如数据增强或蒸馏，通常只带来隐含的跨语言对齐，而忽略更深层的隐表示交互。
- **关键词：** SFT, alignment, fine-tuning

### Cheems: A Practical Guidance for Building and Evaluating Chinese Reward Models from Scratch

- **作者：** Xueru Wen, Jie Lou, Zichao Li, Yaojie Lu, Xing Yu, Yuqiu Ji, Guohai Xu, Hongyu Lin, Ben He, Xianpei Han, Le Sun, Debing Zhang
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.737/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.737.pdf)
- **中文提要：** 奖励模型是让大模型对齐人类偏好的关键组件。相关工作大多以英语为中心并依赖合成资源，中文可用的数据和评测因而有限且不够可靠。
- **关键词：** reward-model, alignment

### CheXalign: Preference fine-tuning in chest X-ray interpretation models without human feedback

- **作者：** Dennis Hein, Zhihong Chen, Sophie Ostmeier, Justin Xu, Maya Varma, Eduardo Pontes Reis, Arne Edward Michalson, Christian Bluethgen, Hyun Joo Shin, Curtis Langlotz, Akshay S Chaudhari
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.1342/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.1342.pdf)
- **中文提要：** 放射科医生负责把医学影像转成可执行的报告。这一领域同时面临人员短缺和工作量不断上升。
- **关键词：** SFT, post-training, fine-tuning

### CodeTool: Enhancing Programmatic Tool Invocation of LLMs via Process Supervision

- **作者：** Yifei Lu, Fanghua Ye, Jian Li, Qiang Gao, Cheng Liu, Haibo Luo, Nan Du, Xiaolong Li, Feiliang Ren
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.895/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.895.pdf)
- **中文提要：** 工具调用能显著增强大模型，复杂任务场景中却仍然困难。指令增强推理和监督微调常常走出不必要的长推理路径，也难以核验中间步骤是否正确。
- **关键词：** SFT, PRM, fine-tuning

### Condor: Enhance LLM Alignment with Knowledge-Driven Data Synthesis and Refinement

- **作者：** Maosong Cao, Taolin Zhang, Mo Li, Chuyu Zhang, Yunxin Liu, Haodong Duan, Songyang Zhang, Kai Chen
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.1091/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.1091.pdf)
- **中文提要：** 监督微调数据的质量对提升大模型的对话能力至关重要。高质量人工标注日益成为瓶颈，训练因此更需要依靠合成数据。
- **关键词：** RLHF, SFT, post-training, alignment, fine-tuning

### Continual Gradient Low-Rank Projection Fine-Tuning for LLMs

- **作者：** Chenxu Wang, Yilin Lyu, Zicheng Sun, Liping Jing
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.721/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.721.pdf)
- **中文提要：** 大模型的持续微调受困于效率与表达能力之间的权衡。LoRA 提供了效率，但低秩特性以及对参数的显式约束，限制了学习新任务和迁移知识。
- **关键词：** LoRA, fine-tuning

### Controlled Low-Rank Adaptation with Subspace Regularization for Continued Training on Large Language Models

- **作者：** Yuheng Lu, Bingshuo Qian, Caixia Yuan, Huixing Jiang, Xiaojie Wang
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.940/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.940.pdf)
- **中文提要：** 大模型学习新任务时会出现灾难性遗忘：适应新领域后，先前任务上的表现大幅下降。CLoRA 在 LoRA 结构上引入子空间正则，用来控制这种继续训练。
- **关键词：** LoRA, PEFT, fine-tuning

### CrafText Benchmark: Advancing Instruction Following in Complex Multimodal Open-Ended World

- **作者：** Zoya Volovikova, Gregory Gorbov, Petr Kuderov, Aleksandr Panov, Alexey Skrynnik
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.1267/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.1267.pdf)
- **中文提要：** 真实条件下遵循指令，要适应动态难测的环境、用词多样的复杂指令，以及数量庞大的可能目标。尽管这一方向已有不少研究，多数工作仍在静态环境和简单指令中进行。
- **关键词：** instruction-following

### Curiosity-Driven Reinforcement Learning from Human Feedback

- **作者：** Haoran Sun, Yekun Chai, Shuohuan Wang, Yu Sun, Hua Wu, Haifeng Wang
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.1146/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.1146.pdf)
- **中文提要：** 用人类反馈做强化学习（RLHF）能把大语言模型对齐到人类偏好，却常常压低输出多样性。多样性与对齐质量之间的取舍，仍然是一个突出难题。
- **关键词：** RLHF, instruction-following, alignment

### Data Whisperer: Efficient Data Selection for Task-Specific LLM Fine-Tuning via Few-Shot In-Context Learning

- **作者：** Shaobo Wang, Xiangqi Jin, Ziming Wang, Jize Wang, Jiajun Zhang, Kaixin Li, Zichen Wen, Zhong Li, Conghui He, Xuming Hu, Linfeng Zhang
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.1135/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.1135.pdf)
- **中文提要：** 任务数据上的微调关系到大语言模型能否真正落地；数据规模变大之后，选出合适子集以兼顾效果与计算成本就变得关键。
- **关键词：** fine-tuning

### Debiasing the Fine-Grained Classification Task in LLMs with Bias-Aware PEFT

- **作者：** Daiying Zhao, Xinyu Yang, Hang Chen
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.717/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.717.pdf)
- **中文提要：** 借助大语言模型做细粒度分类时，标签偏差比传统分类更复杂。重训练、事后调整和 PEFT 主要对付刻板印象这类简单偏差，对预测倾向和判别能力上的偏差仍然不够。
- **关键词：** LoRA, PEFT, fine-tuning

### DenseLoRA: Dense Low-Rank Adaptation of Large Language Models

- **作者：** Lin Mu, Xiaoyu Wang, Li Ni, Yang Li, Zhize Wu, Peiquan Jin, Yiwen Zhang
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.503/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.503.pdf)
- **中文提要：** LoRA 只微调两个低秩矩阵来适配大语言模型，从而减少可训练参数。已有研究指出这些矩阵中不少权重是冗余的，参数利用因此不够充分。
- **关键词：** LoRA, fine-tuning

### DiffPO: Diffusion-styled Preference Optimization for Inference Time Alignment of Large Language Models

- **作者：** Ruizhe Chen, Wenhao Chai, Zhifei Yang, Xiaotian Zhang, Ziyang Wang, Tony Quek, Joey Tianyi Zhou, Soujanya Poria, Zuozhu Liu
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.926/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.926.pdf)
- **中文提要：** 推理阶段对齐为大语言模型提供了一条更省事的对齐途径。它仍受限于与特定策略绑定的价值函数，可扩展性不足，推理过程中还会产生延迟。
- **关键词：** RLHF, preference-optimization, alignment

### DoMIX: An Efficient Framework for Exploiting Domain Knowledge in Fine-Tuning

- **作者：** Dohoon Kim, Donghun Kang, Taesup Moon
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.710/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.710.pdf)
- **中文提要：** 领域自适应预训练（DAP）因有助于微调预训练模型而受到关注。在此之上，持续 DAP 被用来让模型逐步纳入不同领域的数据。
- **关键词：** LoRA, PEFT, fine-tuning

### Don't Half-listen: Capturing Key-part Information in Continual Instruction Tuning

- **作者：** Yongquan He, Wenyuan Zhang, Xuancheng Huang, Peng Zhang, Lingxun Meng, Xiang Zhou, Ke Zeng, Xunliang Cai
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.1153/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.1153.pdf)
- **中文提要：** 指令微调可以推动大语言模型在特定下游任务上给出符合人类目标的结果。持续指令微调（CIT）却可能带来灾难性遗忘，使先前学会的能力退化。
- **关键词：** instruction-tuning, instruction-following

### Don't Reinvent the Wheel: Efficient Instruction-Following Text Embedding based on Guided Space Transformation

- **作者：** Yingchaojie Feng, Yiqun Sun, Yandong Sun, Minfeng Zhu, Qiang Huang, Anthony Kum Hoe Tung, Wei Chen
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.1196/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.1196.pdf)
- **中文提要：** 指令跟随式文本嵌入会随用户指令生成动态向量，并突出文本的某些属性。现有方法每来一条新指令就要把整个语料重新编码，计算开销很大。
- **关键词：** instruction-following

### DualGuard: A Parameter Space Transformation Approach for Bidirectional Defense in Split-Based LLM Fine-Tuning

- **作者：** Zihan Liu, Yizhen Wang, Rui Wang, Sai Wu
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.835/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.835.pdf)
- **中文提要：** 将分割学习与大语言模型微调结合，可信的本地客户端可以和算力更充足的远端服务器协作，但传输中的激活与梯度容易遭到数据重建攻击。对激活或梯度加噪的防御，在严格条件下往往要牺牲任务相关的模型表现。
- **关键词：** fine-tuning

### Dynamic and Generalizable Process Reward Modeling

- **作者：** Zhangyue Yin, Qiushi Sun, Zhiyuan Zeng, Qinyuan Cheng, Xipeng Qiu, Xuanjing Huang
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.212/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.212.pdf)
- **中文提要：** 过程奖励模型（PRM）通过稠密奖励信号，引导大语言模型应对复杂场景。现有 PRM 主要依赖启发式方法，跨领域泛化比较困难。
- **关键词：** PRM, reward-model

### Dynamic Scaling of Unit Tests for Code Reward Modeling

- **作者：** Zeyao Ma, Xiaokang Zhang, Jing Zhang, Jifan Yu, Sijia Luo, Jie Tang
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.343/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.343.pdf)
- **中文提要：** 代码生成这类复杂推理上，大语言模型往往难以一次就答对。先前研究的办法是生成多个候选解答，再用模型写出的单元测试来校验。
- **关键词：** reward-model

### EAGLE: Expert-Guided Self-Enhancement for Preference Alignment in Pathology Large Vision-Language Model

- **作者：** Meidan Ding, Jipeng Zhang, Wenxuan Wang, Haiqin Zhong, Xiaoqin Wang, Xinheng Lyu, Wenting Chen, Linlin Shen
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.711/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.711.pdf)
- **中文提要：** 大视觉语言模型在病理诊断上展现出潜力，临床落地却面临多模态幻觉和带有偏向的回答。偏好对齐在一般领域有效，但专家资源有限，再加上领域方面的制约，高质量病理偏好数据仍然难求。
- **关键词：** SFT, preference-optimization, alignment, fine-tuning

### Efficient Domain Continual pretraining by Mitigating the Stability Gap

- **作者：** Yiduo Guo, Jie Fu, Huishuai Zhang, Dongyan Zhao
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.1578/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.1578.pdf)
- **中文提要：** 持续预训练使大语言模型能够适应医学、法律等专门领域。不同模型规模和领域上都能看到同一现象：过程一开始性能会暂时下降，随后才进入恢复阶段。
- **关键词：** instruction-tuning, continued-pretraining

### Efficient Ensemble for Fine-tuning Language Models on Multiple Datasets

- **作者：** Dongyue Li, Ziniu Zhang, Lu Wang, Hongyang R. Zhang
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.1231/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.1231.pdf)
- **中文提要：** 这项工作提出一种集成方法，让语言模型同时面向多个数据集做微调。QLoRA 等现有方法在适配单一数据集时比较高效。
- **关键词：** QLoRA, LoRA, fine-tuning

### Efficient Safety Alignment of Large Language Models via Preference Re-ranking and Representation-based Reward Modeling

- **作者：** Deng Qiyuan, Xuefeng Bai, Kehai Chen, Yaowei Wang, Liqiang Nie, Min Zhang
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.1504/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.1504.pdf)
- **中文提要：** 以 DPO 为代表的强化学习算法在做安全对齐时会遇到分布偏移。现有处理方式通常从目标策略在线采样，计算开销很大。
- **关键词：** DPO, preference-optimization, reward-model, alignment

### Emergent Abilities of Large Language Models under Continued Pre-training for Language Adaptation

- **作者：** Ahmed Elhady, Eneko Agirre, Mikel Artetxe
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.1547/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.1547.pdf)
- **中文提要：** 把已有大语言模型适配到新语言时，持续预训练（CPT）是常用途径。混合语料里通常会放入一部分英语数据，但其作用至今缺少仔细研究。
- **关键词：** continued-pretraining

### Enhancing Chain-of-Thought Reasoning with Critical Representation Fine-tuning

- **作者：** Chenxi Huang, Shaotian Yan, Liang Xie, Binbin Lin, Sinan Fan, Yue Xin, Deng Cai, Chen Shen, Jieping Ye
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.1129/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.1129.pdf)
- **中文提要：** 表征微调（ReFT）是一种 PEFT 方法，只编辑表征空间就能明显提高参数效率。该工作考察如何把 ReFT 用到复杂推理任务上。
- **关键词：** PEFT, fine-tuning

### Enhancing Multimodal Continual Instruction Tuning with BranchLoRA

- **作者：** Duzhen Zhang, Yong Ren, Zhong-Zhi Li, Yahan Yu, Jiahua Dong, Chenxing Li, Zhilong Ji, Jinfeng Bai
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.287/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.287.pdf)
- **中文提要：** 多模态持续指令微调（MCIT）旨在让多模态大语言模型在相继的任务中持续对齐人类意图。现有方法常依靠混合专家（MoE）形式的 LoRA 来保留先前的指令对齐。
- **关键词：** instruction-tuning, LoRA, fine-tuning

### Enhancing Safe and Controllable Protein Generation via Knowledge Preference Optimization

- **作者：** Yuhao Wang, Keyan Ding, Kehua Feng, Zeyuan Wang, Ming Qin, Xiaotong Li, Qiang Zhang, Huajun Chen
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.616/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.616.pdf)
- **中文提要：** 蛋白质语言模型已成为序列生成的有力工具，在功能优化和从头设计上优势明显。它们也可能生成有害蛋白序列，例如增强病毒传播力或逃避免疫反应的序列。
- **关键词：** preference-optimization

### Exploring the Impact of Instruction-Tuning on LLM's Susceptibility to Misinformation

- **作者：** Kyubeen Han, Junseo Jang, Hongjin Kim, Geunyeong Jeong, Harksoo Kim
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.1295/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.1295.pdf)
- **中文提要：** 指令微调让大语言模型更准确地听从用户指令，可用性上升，有害输出下降。这个过程也可能加深对用户输入的依赖，从而不加筛选地接受错误信息并生成幻觉。
- **关键词：** instruction-tuning

### FedEx-LoRA: Exact Aggregation for Federated and Efficient Fine-Tuning of Large Language Models

- **作者：** Raghav Singhal, Kaustubh Ponkshe, Praneeth Vepakomma
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.67/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.67.pdf)
- **中文提要：** LoRA 是基础模型高效微调的常用技术。一旦放到联邦学习环境、数据分散在多个客户端上，就会出现特有的挑战。
- **关键词：** LoRA, fine-tuning

### Finding the Sweet Spot: Preference Data Construction for Scaling Preference Optimization

- **作者：** Yao Xiao, Hai Ye, Linyao Chen, Hwee Tou Ng, Lidong Bing, Xiaoli Li, Roy Ka-Wei Lee
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.615/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.615.pdf)
- **中文提要：** 迭代生成数据并重新训练，被广泛用于对齐大语言模型：通常由策略模型产生在策略回答，再由奖励模型指导训练数据的挑选。DPO 进一步把选中回答与拒绝回答组成偏好对。
- **关键词：** DPO, preference-optimization, reward-model, alignment

### Fine-grained Video Dubbing Duration Alignment with Segment Supervised Preference Optimization

- **作者：** Chaoqun Cui, Liangbin Huang, Shijing Wang, Zhe Tong, Zhaolong Huang, Xiao Zeng, Xiaofeng Liu
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.227/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.227.pdf)
- **中文提要：** 视频配音要把视听节目中的原语言语音译成目标语言，依赖神经机器翻译和语音合成。各语言信息密度不同，目标语音时长常常与源语音不符，造成音画不同步，明显影响观看体验。
- **关键词：** preference-optimization, alignment

### Fine-Tuning on Diverse Reasoning Chains Drives Within-Inference CoT Refinement in LLMs

- **作者：** Haritz Puerto, Tilek Chubakov, Xiaodan Zhu, Harish Tayyar Madabushi, Iryna Gurevych
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.191/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.191.pdf)
- **中文提要：** 要求大语言模型写出中间推理步骤，也就是思维链（CoT），已被证明能有效提升表现。以往方法着重生成多条相互独立的思维链，再用集成或其他事后策略加以合并。
- **关键词：** fine-tuning

### Flexora: Flexible Low-Rank Adaptation for Large Language Models

- **作者：** Chenxing Wei, Yao Shu, Ying Tiffany He, Fei Yu
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.713/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.713.pdf)
- **中文提要：** 大语言模型虽推动了人工智能，但在具体任务上常被知识边界限制。LoRA 等微调想突破这一限制，却可能出现过拟合。
- **关键词：** LoRA, fine-tuning

### FocalPO: Enhancing Preference Optimizing by Focusing on Correct Preference Rankings

- **作者：** Tong Liu, Xiao Yu, Wenxuan Zhou, Jindong Gu, Volker Tresp
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-short.21/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-short.21.pdf)
- **中文提要：** DPO 这类高效偏好优化算法，已成为对齐大语言模型与人类偏好的常用方法。它们把模型隐式当作奖励模型，训练时专注于纠正那些排错的偏好对。
- **关键词：** DPO, preference-optimization, reward-model, alignment

### Focus on What Matters: Enhancing Medical Vision-Language Models with Automatic Attention Alignment Tuning

- **作者：** Aofei Chang, Le Huang, Alex James Boyd, Parminder Bhatia, Taha Kass-Hout, Cao Xiao, Fenglong Ma
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.460/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.460.pdf)
- **中文提要：** 医学大视觉语言模型对视觉输入的注意力分配常常不理想，从而产生幻觉或不准确的输出。现有方法主要在推理时进行干预，注意力适应有限，或者还需要额外监督。
- **关键词：** alignment, fine-tuning

### Forward Knows Efficient Backward Path: Saliency-Guided Memory-Efficient Fine-tuning of Large Language Models

- **作者：** Yeachan Kim, SangKeun Lee
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.459/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.459.pdf)
- **中文提要：** 微调被普遍视为让大语言模型对齐人类意图的关键过程。随之而来的大量显存需求，成为扩大其适用范围的显著障碍。
- **关键词：** PEFT, alignment, fine-tuning

### From English to Second Language Mastery: Enhancing LLMs with Cross-Lingual Continued Instruction Tuning

- **作者：** Linjuan Wu, Hao-Ran Wei, Baosong Yang, Weiming Lu
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.1121/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.1121.pdf)
- **中文提要：** 用翻译得到的指令数据做监督微调（SFT），能有效把大语言模型从英语适配到非英语。跨语言持续指令微调（X-CIT）则充分利用这类基于翻译的平行指令数据，以增强跨语言适应能力。
- **关键词：** SFT, instruction-tuning, alignment, fine-tuning

### From Outcomes to Processes: Guiding PRM Learning from ORM for Inference-Time Alignment

- **作者：** Bin Xie, Bingbing Xu, Yige Yuan, Shengmao Zhu, Huawei Shen
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.946/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.946.pdf)
- **中文提要：** 推理时对齐因效率与效果而受到广泛关注。主流的奖励引导搜索（RGS）主要依赖结果奖励模型（ORM），但两者粒度并不匹配：ORM 只为完整回答提供结果层面的奖励。
- **关键词：** PRM, reward-model, alignment

### GainRAG: Preference Alignment in Retrieval-Augmented Generation through Gain Signal Synthesis

- **作者：** Yi Jiang, Sendong Zhao, Jianbo Li, Haochun Wang, Bing Qin
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.527/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.527.pdf)
- **中文提要：** 检索增强生成（RAG）用检索模块把检索信息动态注入大语言模型的输入上下文，已在多种自然语言任务上取得成功。检索器与语言模型之间存在偏好差距，限制了系统继续提升。
- **关键词：** preference-optimization, alignment

### Generative Reward Modeling via Synthetic Criteria Preference Learning

- **作者：** Xiaobo Liang, Haoke Zhang, Juntao Li, Kehai Chen, Qiaoming Zhu, Min Zhang
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.1297/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.1297.pdf)
- **中文提要：** 生成式奖励模型（GenRM）利用合成的思维链（CoT）来减少对大规模标注数据的需求，但这些思维链的正确性无法保证，因而带来过度优化的风险。要在合成思维链里识别并优化意外行为仍然困难，因为这高度依赖对中间行为的精确标注。
- **关键词：** PRM, reward-model

### GiFT: Gibbs Fine-Tuning for Code Generation

- **作者：** Haochen Li, Wanjin Feng, Xin Zhou, Zhiqi Shen
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.599/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.599.pdf)
- **中文提要：** 在代码生成中，用合成数据训练大语言模型是常见做法。一种关键途径是自训练：模型在自己生成的正确代码片段上反复训练。
- **关键词：** fine-tuning

### GIFT-SW: Gaussian noise Injected Fine-Tuning of Salient Weights for LLMs

- **作者：** Maxim Zhelnin, Viktor Moskvoretskii, Egor Shvetsov, Maria Krylova, Venediktov Egor, Zuev Aleksandr, Evgeny Burnaev
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.324/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.324.pdf)
- **中文提要：** 参数高效微调（PEFT）已经普及，并降低了使用大语言模型的门槛。近期研究表明，只有一小部分权重会显著影响性能。
- **关键词：** PEFT, fine-tuning

### Gradient-Adaptive Policy Optimization: Towards Multi-Objective Alignment of Large Language Models

- **作者：** Chengao Li, Hanyu Zhang, Yunkun Xu, Hongyan Xue, Xiang Ao, Qing He
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.549/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.549.pdf)
- **中文提要：** 人类反馈强化学习（RLHF）已成为对齐大语言模型与人类偏好的有力技术。当人类偏好多样、尤其彼此冲突时，有效对齐仍然是一大挑战。
- **关键词：** RLHF, alignment, fine-tuning

### GRAT: Guiding Retrieval-Augmented Reasoning through Process Rewards Tree Search

- **作者：** Xianshu Peng, Wei Wei
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.1352/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.1352.pdf)
- **中文提要：** 提升大模型处理复杂多跳问答的能力，已成为检索增强生成（RAG）中的研究重点。许多方法让大模型逐步进行检索增强生成，以模仿人类的思考过程。
- **关键词：** SFT, PRM, fine-tuning

### HAF-RM: A Hybrid Alignment Framework for Reward Model Training

- **作者：** Shujun Liu, Xiaoyu Shen, Yuhang Lai, Siyuan Wang, Shengbin Yue, Zengfeng Huang, Xuanjing Huang, Zhongyu Wei
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.924/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.924.pdf)
- **中文提要：** 奖励模型在大语言模型的对齐、评估和数据构建中日益重要。多数研究遵循直接优化预测奖励的常规训练框架，主要通过改进数据来加强奖励模型；文中提出了混合对齐框架 HAF-RM。
- **关键词：** reward-model, alignment

### HFT: Half Fine-Tuning for Large Language Models

- **作者：** Tingfeng Hui, Zhenyu Zhang, Shuohuan Wang, Weiran Xu, Yu Sun, Hua Wu
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.626/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.626.pdf)
- **中文提要：** 经过一轮或多轮微调，大语言模型才能解锁跟随自然语言指令、对齐人类偏好等能力。顺序训练中存在灾难性遗忘的风险，先前阶段学到的参数知识或能力可能被后续数据淹没。
- **关键词：** DPO, SFT, preference-optimization, fine-tuning

### HiDe-LLaVA: Hierarchical Decoupling for Continual Instruction Tuning of Multimodal Large Language Model

- **作者：** Haiyang Guo, Fanhu Zeng, Ziwei Xiang, Fei Zhu, Da-Han Wang, Xu-Yao Zhang, Cheng-Lin Liu
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.666/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.666.pdf)
- **中文提要：** 指令微调常被用来在精选的任务数据上训练预训练多模态大语言模型，使其理解并遵循人类指令。现实中无法一次性收集所有可能的指令数据集。
- **关键词：** instruction-tuning, alignment

### Hierarchical-Task-Aware Multi-modal Mixture of Incremental LoRA Experts for Embodied Continual Learning

- **作者：** Ziqi Jia, Anmin Wang, Xiaoyang Qu, Xiaowen Yang, Jianzong Wang
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.1379/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.1379.pdf)
- **中文提要：** 以往面向具身智能的持续学习设置，主要按人类指令执行低层动作，忽略了高层规划与多层知识的学习。分层具身持续学习设置（HEC）把智能体的持续学习分成高层指令和低层动作两层。
- **关键词：** LoRA

### InSerter: Speech Instruction Following with Unsupervised Interleaved Pre-training

- **作者：** Dingdong Wang, Jin Xu, Ruihang Chu, Zhifang Guo, Xiong Wang, Jincenzi Wu, Dongchao Yang, Shengpeng Ji, Junyang Lin
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.882/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.882.pdf)
- **中文提要：** 语音大语言模型近来的进展引起了较多关注。现有方法在遵循语音指令方面的表现仍然不理想。
- **关键词：** instruction-following, post-training, alignment

### Instruction Tuning on Public Government and Cultural Data for Low-Resource Language: a Case Study in Kazakh

- **作者：** Nurkhan Laiyk, Daniil Orel, Rituraj Joshi, Maiya Goloburda, Yuxia Wang, Preslav Nakov, Fajri Koto
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.706/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.706.pdf)
- **中文提要：** 低资源语言上的指令微调研究不足，原因是文本数据有限，政务与文化领域尤其如此。该工作开源了一份大规模指令跟随数据集，覆盖与哈萨克斯坦相关的重要机构知识与文化知识。
- **关键词：** instruction-tuning, instruction-following, fine-tuning

### Introducing Graph Context into Language Models through Parameter-Efficient Fine-Tuning for Lexical Relation Mining

- **作者：** Jingwen Sun, Zhiyi Tian, Yu He, Jingwei Sun, Guangzhong Sun
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.511/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.511.pdf)
- **中文提要：** 词汇关系描述的是一种语言内部词语如何相互关联。已有工作表明，预训练语言模型可以有效挖掘词对之间的词汇关系。
- **关键词：** PEFT, fine-tuning

### Intuitive Fine-Tuning: Towards Simplifying Alignment into a Single Process

- **作者：** Ermo Hua, Biqing Qi, Kaiyan Zhang, Kai Tian, Xingtai Lv, Ning Ding, Bowen Zhou
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.6/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.6.pdf)
- **中文提要：** 预训练之后，监督微调（SFT）和偏好优化（PO）是让语言模型对齐人类偏好的两个关键过程。SFT 更突出效率，PO 更突出效果，二者常被先后串起来用，优化目标却没有被整合。
- **关键词：** SFT, preference-optimization, alignment, fine-tuning

### InvestAlign: Overcoming Data Scarcity in Aligning Large Language Models with Investor Decision-Making Processes Under Herd Behavior

- **作者：** Huisheng Wang, Zhuoshi Pan, Hangjing Zhang, Mingxiao Liu, Hanqing Gao, H. Vicky Zhao
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.495/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.495.pdf)
- **中文提要：** 让大语言模型对齐羊群行为下的投资者决策，是行为金融中的一个关键难题，瓶颈在于监督微调（SFT）缺少真实用户数据。SFT 能缩小模型输出与人类行为模式之间的差距，但对大量真实数据的依赖会带来很高的采集成本。
- **关键词：** SFT, alignment, fine-tuning

### IOPO: Empowering LLMs with Complex Instruction Following via Input-Output Preference Optimization

- **作者：** Xinghua Zhang, Haiyang Yu, Cheng Fu, Fei Huang, Yongbin Li
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.1079/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.1079.pdf)
- **中文提要：** 随着更多智能体和应用借助大语言模型来构建，准确遵循日益复杂的指令变得至关重要。一方面复杂指令的评测数据有限，另一方面还没有专门用于提升这一能力的算法。
- **关键词：** DPO, SFT, instruction-following, preference-optimization, alignment

### L4Q: Parameter Efficient Quantization-Aware Fine-Tuning on Large Language Models

- **作者：** Hyesung Jeon, Yulhwa Kim, Jae-Joon Kim
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.99/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.99.pdf)
- **中文提要：** 大语言模型的显存和计算成本很高，量化可以降低推理开销，LoRA 等参数高效微调（PEFT）可以降低训练开销。这一趋势带动了面向量化感知 PEFT 的研究。
- **关键词：** LoRA, PEFT, post-training, fine-tuning

### Language Model Fine-Tuning on Scaled Survey Data for Predicting Distributions of Public Opinions

- **作者：** Joseph Suh, Erfan Jahanparast, Suhong Moon, Minwoo Kang, Serina Chang
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.1028/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.1028.pdf)
- **中文提要：** 大语言模型为舆论研究带来新机会：可以在问卷设计早期预先预测调查回答。先前方法把子群体描述写进提示来引导模型，但这种提示工程难以忠实预测真人调查回答的分布。
- **关键词：** fine-tuning

### LIFBench: Evaluating the Instruction Following Performance and Stability of Large Language Models in Long-Context Scenarios

- **作者：** Xiaodong Wu, Minhao Wang, Yichen Liu, Xiaoming Shi, He Yan, Lu Xiangju, Junmin Zhu, Wei Zhang
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.803/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.803.pdf)
- **中文提要：** 随着大语言模型在自然语言处理中的发展，在长上下文输入里稳定遵循指令对真实应用变得关键。现有基准很少关注长上下文场景下的指令遵循，也很少考察不同输入上的稳定性。
- **关键词：** instruction-following

### LLaVA Steering: Visual Instruction Tuning with 500x Fewer Parameters through Modality Linear Representation-Steering

- **作者：** Jinhe Bi, Yujun Wang, Haokun Chen, Xun Xiao, Artur Hecker, Volker Tresp, Yunpu Ma
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.739/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.739.pdf)
- **中文提要：** 多模态大语言模型把视觉表征接入大语言模型，从而加强视觉任务。继承自语言模型的文本模态支持指令遵循和上下文学习，视觉模态则凭借丰富语义、空间信息和定位能力提升下游表现。
- **关键词：** instruction-tuning, instruction-following, LoRA, PEFT, fine-tuning

### LPOI: Listwise Preference Optimization for Vision Language Models

- **作者：** Fatemeh Pesaran Zadeh, Yoojin Oh, Gunhee Kim
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.1302/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.1302.pdf)
- **中文提要：** 让大型视觉语言模型对齐人类偏好很有挑战，RLHF 和 DPO 常常过拟合文本信息，或进一步加重幻觉。增加负向图像样本只能部分缓解这些缺陷；由于构造列表式图像样本既复杂又昂贵，此前没有工作在视觉语言模型上使用列表式偏好优化。
- **关键词：** DPO, RLHF, preference-optimization, alignment

### MAmmoTH-VL: Eliciting Multimodal Reasoning with Instruction Tuning at Scale

- **作者：** Jiawei Guo, Tianyu Zheng, Yizhi Li, Yuelin Bai, Bo Li, Yubo Wang, King Zhu, Graham Neubig, Wenhu Chen, Xiang Yue
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.680/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.680.pdf)
- **中文提要：** 开源多模态大语言模型在广泛任务上已显示出可观潜力。其推理能力仍受现有指令微调数据制约，这些数据大多由视觉问答、科学图表问答一类学术数据集改造而来。
- **关键词：** instruction-tuning

### Marco-Bench-MIF: On Multilingual Instruction-Following Capability of Large Language

- **作者：** Bo Zeng, Chenyang Lyu, Sinuo Liu, Mingyan Zeng, Minghao Wu, Xuanfan Ni, Tianqi Shi, Yu Zhao, Yefeng Liu, Chenyu Zhu, Ruizhe Li, Jiahui Geng, Qing Li, Yu Tong, Longyue Wang, Weihua Luo, Kaifu Zhang
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.1172/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.1172.pdf)
- **中文提要：** 指令遵循能力已成为评测大语言模型时的一项主要能力。IFEval 等现有数据集要么以英语为中心、基本上是单语，要么只是机器翻译到其他语言，限制了在多语环境中的适用性。
- **关键词：** instruction-following

### MaXIFE: Multilingual and Cross-lingual Instruction Following Evaluation

- **作者：** Yile Liu, Ziwei Ma, Xiu Jiang, Jinglu Hu, Chang Jing, Liang Li
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.698/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.698.pdf)
- **中文提要：** 遵循指令的能力，已成为衡量大语言模型实用性的关键指标。现有评测方法常常只覆盖单语场景，忽略了多语和跨语情境中的挑战与差异。
- **关键词：** instruction-following

### MDCure: A Scalable Pipeline for Multi-Document Instruction-Following

- **作者：** Gabrielle Kaili-May Liu, Bowen Shi, Avi Caciularu, Idan Szpektor, Arman Cohan
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.1418/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.1418.pdf)
- **中文提要：** 多文档处理对大语言模型完成摘要、以及跨大量文档问答等真实任务至关重要。模型处理长输入的能力已有提高，多文档上下文仍有独特困难，包括文档之间的依赖、冗余和结构不连贯。
- **关键词：** instruction-following, reward-model, fine-tuning

### Measuring Data Diversity for Instruction Tuning: A Systematic Analysis and A Reliable Metric

- **作者：** Yuming Yang, Yang Nan, Junjie Ye, Shihan Dou, Xiao Wang, Shuo Li, Huijie Lv, Tao Gui, Qi Zhang, Xuanjing Huang
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.908/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.908.pdf)
- **中文提要：** 数据多样性对大语言模型的指令微调至关重要。已有研究探索了多种考虑多样性的数据选择方法，用以构建高质量数据集并提升模型表现。
- **关键词：** instruction-tuning, fine-tuning

### Middle-Layer Representation Alignment for Cross-Lingual Transfer in Fine-Tuned LLMs

- **作者：** Danni Liu, Jan Niehues
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.778/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.778.pdf)
- **中文提要：** 微调让大语言模型在特定任务上展现出很强能力，把这种收益延伸到多种语言对广泛可及性很重要。语言之间的性能差距，以及许多语言缺少微调数据，阻碍了有效的跨语言迁移。
- **关键词：** alignment, fine-tuning

### MLAS-LoRA: Language-Aware Parameters Detection and LoRA-Based Knowledge Transfer for Multilingual Machine Translation

- **作者：** Tianyu Dong, Bo Li, Jinsong Liu, Shaolin Zhu, Deyi Xiong
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.762/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.762.pdf)
- **中文提要：** 大语言模型在多语言机器翻译上进步显著，即使平行数据有限也能有较强表现。针对翻译进行微调却很困难：不同语言对的需求互相冲突会带来参数干扰，还可能覆盖预训练知识。
- **关键词：** LoRA, PEFT, fine-tuning

### MobiLoRA: Accelerating LoRA-based LLM Inference on Mobile Devices via Context-aware KV Cache Optimization

- **作者：** Borui Li, Yitao Wang, Haoran Ma, Ligeng Chen, Jun Xiao, Shuai Wang
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.1140/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.1140.pdf)
- **中文提要：** 在移动设备上用低秩适配（LoRA）部署大语言模型很有前景，既能完成多样的领域任务，又能兼顾隐私与可及性。MobiLoRA 被用来加速这类基于 LoRA 的模型在移动端的推理。
- **关键词：** LoRA

### Modeling Complex Semantics Relation with Contrastively Fine-Tuned Relational Encoders

- **作者：** Na{\"i}m Es-sebbani, Esteban Marquer, Zied Bouraoui
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.991/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.991.pdf)
- **中文提要：** 概念与实体之间的关系建模对许多应用都很关键。大语言模型虽能有效捕捉关系知识与常识，但计算代价高，在关系归纳、抽取和信息检索等需要高效关系编码的任务上常常表现不足。
- **关键词：** fine-tuning

### M-RewardBench: Evaluating Reward Models in Multilingual Settings

- **作者：** Srishti Gureja, Lester James V. Miranda, Shayekh Bin Islam, Rishabh Maheshwary, Drishti Sharma, Gusti Winata, Nathan Lambert, Sebastian Ruder, Sara Hooker, Marzieh Fadaee
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.3/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.3.pdf)
- **中文提要：** 奖励模型把人类反馈纳入语言建模过程，支撑了当今大语言模型的先进表现。这些模型主要在英语上训练和评测，多语言环境下的能力仍缺少充分研究。
- **关键词：** reward-model

### MuSC: Improving Complex Instruction Following with Multi-granularity Self-Contrastive Training

- **作者：** Hui Huang, Jiaheng Liu, Yancheng He, Shilong Li, Bing Xu, Conghui Zhu, Muyun Yang, Tiejun Zhao
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.523/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.523.pdf)
- **中文提要：** 带精细约束的复杂指令跟随，是大语言模型必须面对的要求。现有复杂指令对齐数据的构建都依赖更强的模型，尤其是 GPT-4，因而限制了实际应用。
- **关键词：** instruction-following, preference-optimization, alignment

### Mutual-Taught for Co-adapting Policy and Reward Models

- **作者：** Tianyuan Shi, Canbin Huang, Fanqi Wan, Longguang Zhong, Ziyi Yang, Weizhou Shen, Xiaojun Quan, Ming Yan
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.794/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.794.pdf)
- **中文提要：** 偏好优化过程中，新生成的模型样本与训练奖励模型所用数据之间可能出现分布偏移。这种偏移会削弱奖励模型，并进一步拖累策略模型。
- **关键词：** preference-optimization, reward-model

### Neural Parameter Search for Slimmer Fine-Tuned Models and Better Transfer

- **作者：** Guodong Du, Zitao Fang, Jing Li, Junlin Li, Runhua Jiang, Shuyang Yu, Yifei Guo, Yangneng Chen, Sim Kuan Goh, Ho-Kin Tang, Daojing He, Honghai Liu, Min Zhang
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.1570/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.1570.pdf)
- **中文提要：** 基础模型及其检查点显著推动了深度学习在各类应用中的表现。微调后的模型却常常难以离开特定领域，并且存在相当明显的冗余。
- **关键词：** fine-tuning

### Nudging: Inference-time Alignment of LLMs via Guided Decoding

- **作者：** Yu Fei, Yasaman Razeghi, Sameer Singh
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.623/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.623.pdf)
- **中文提要：** 大语言模型需要经过对齐，才能有效且安全地遵循用户指令。若每个基座模型都要单独训练一个对齐版本，计算开销会很大。
- **关键词：** alignment

### One QuantLLM for ALL: Fine-tuning Quantized LLMs Once for Efficient Deployments

- **作者：** Ke Yi, Yuhui Xu, Heng Chang, Yuan Meng, Tong Zhang, Jia Li
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.1124/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.1124.pdf)
- **中文提要：** 大语言模型发展迅速，但内存需求很高。量化虽被看好，现有方法通常仍需长时间训练，才能缓解量化损失造成的性能下降。
- **关键词：** fine-tuning

### On the Relation Between Fine-Tuning, Topological Properties, and Task Performance in Sense-Enhanced Embeddings

- **作者：** Deniz Ekin Yavas, Timoth{\'e}e Bernard, Beno{\^i}t Crabb{\'e}, Laura Kallmeyer
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.1151/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.1151.pdf)
- **中文提要：** 各向同性、均匀性等嵌入拓扑性质与表达能力密切相关，改善这些性质有助于捕捉更细微的语义差别。微调却可能降低语言模型嵌入的表达能力。
- **关键词：** alignment, fine-tuning

### Open-World Attribute Mining for E-Commerce Products with Multimodal Self-Correction Instruction Tuning

- **作者：** Jiaqi Li, Yanming Li, Xiaoli Shen, Chuanyi Zhang, Guilin Qi, Sheng Bi
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.85/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.85.pdf)
- **中文提要：** 电商场景中，有效的商品属性挖掘有助于完善商品特征并辅助消费者决策。当前方法多从单模态文本中抽取属性，对多模态数据利用不足。
- **关键词：** instruction-tuning

### Optimal Transport-Based Token Weighting scheme for Enhanced Preference Optimization

- **作者：** Meng Li, Guangda Huzhang, Haibo Zhang, Xiting Wang, Anxiang Zeng
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.1035/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.1035.pdf)
- **中文提要：** DPO 通过直接优化入选回答与落选回答之间的对数似然差，把大语言模型对齐到人类偏好。现有方法给回答中的全部词元同等重要性，而人会把注意力放在更有意义的部分。
- **关键词：** DPO, instruction-following, preference-optimization, alignment

### P$^2$ Law: Scaling Law for Post-Training After Model Pruning

- **作者：** Xiaodong Chen, Yuxuan Hu, Xiaokang Zhang, Yanling Wang, Cuiping Li, Hong Chen, Jing Zhang
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.283/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.283.pdf)
- **中文提要：** 剪枝已被广泛用来降低大语言模型的硬件需求。为减轻剪枝带来的性能下降，后训练常被用来恢复模型表现。
- **关键词：** post-training

### Plug-in and Fine-tuning: Bridging the Gap between Small Language Models and Large Language Models

- **作者：** Kyeonghyun Kim, Jinhee Jang, Juhwan Choi, Yoonji Lee, Kyohoon Jin, YoungBin Kim
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.271/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.271.pdf)
- **中文提要：** 大语言模型以丰富的语言知识和较强泛化著称，但计算需求高，不适合资源受限的环境。小语言模型更省计算，却往往缺少大模型那种广泛的泛化能力。
- **关键词：** fine-tuning

### PRMBench: A Fine-grained and Challenging Benchmark for Process-Level Reward Models

- **作者：** Mingyang Song, Zhaochen Su, Xiaoye Qu, Jiawei Zhou, Yu Cheng
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.1230/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.1230.pdf)
- **中文提要：** 过程级奖励模型对复杂推理和决策至关重要，因为中间每一步都会影响推理过程。语言模型在推理时容易出现多种错误，因此这类模型需要具备识别真实场景中各类隐性错误的细致能力。
- **关键词：** PRM, reward-model

### Quaff: Quantized Parameter-Efficient Fine-Tuning under Outlier Spatial Stability Hypothesis

- **作者：** Hong Huang, Dapeng Wu
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.325/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.325.pdf)
- **中文提要：** 面向任务的微调在计算和内存上开销过大，阻碍大语言模型部署到资源受限的个人设备。量化提供了提效途径，但现有方法仍难平衡性能与开销，常见情形是计算或内存成本偏高。
- **关键词：** PEFT, fine-tuning

### Qwen2.5-xCoder: Multi-Agent Collaboration for Multilingual Code Instruction Tuning

- **作者：** Jian Yang, Wei Zhang, Yibo Miao, Shanghaoran Quan, Zhenhe Wu, Qiyao Peng, Liqun Yang, Tianyu Liu, Zeyu Cui, Binyuan Hui, Junyang Lin
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.642/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.642.pdf)
- **中文提要：** 在高质量指令数据上微调的代码大模型，能够应对范围广泛的代码相关任务。以往方法大多把每种编程语言孤立看待，忽略了不同语言之间的知识迁移。
- **关键词：** instruction-tuning, fine-tuning

### Re$^3$Syn: A Dependency-Based Data Synthesis Framework for Long-Context Post-training

- **作者：** Zhiyang Zhang, Ziqiang Liu, Huiming Wang, Renke Shan, Li Kuang, Lu Wang, De Wen Soh
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.1518/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.1518.pdf)
- **中文提要：** 更长的上下文窗口是大语言模型发展中的一个重要趋势。要让模型有效建模很长的输入，训练却常常受阻于自然长上下文数据的稀缺。
- **关键词：** post-training

### RecLM: Recommendation Instruction Tuning

- **作者：** Yangqin Jiang, Yuhao Yang, Lianghao Xia, Da Luo, Kangyi Lin, Chao Huang
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.751/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.751.pdf)
- **中文提要：** 现代推荐系统希望借助历史交互深入理解用户的复杂偏好。基于图神经网络的深度协同过滤擅长捕捉用户与物品的关系，但在稀疏数据或零样本场景中效果有限，主要受制于基于 ID 的嵌入函数。
- **关键词：** instruction-tuning

### Refining Salience-Aware Sparse Fine-Tuning Strategies for Language Models

- **作者：** Xinxin Liu, Aaron Thomas, Cheng Zhang, Jianyi Cheng, Yiren Zhao, Xitong Gao
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.1541/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.1541.pdf)
- **中文提要：** 以 LoRA 为代表的低秩适应，使参数高效微调（PEFT）受到广泛关注。这里转向稀疏式 PEFT（SPEFT），在权重矩阵上引入可训练的稀疏适应，从而比低秩方法更灵活地选择要微调的参数。
- **关键词：** LoRA, PEFT, fine-tuning

### Rethinking Reward Model Evaluation Through the Lens of Reward Overoptimization

- **作者：** Sunghwan Kim, Dongjin Kang, Taeyoon Kwon, Hyungjoo Chae, Dongha Lee, Jinyoung Yeo
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.649/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.649.pdf)
- **中文提要：** 奖励模型在 RLHF 中负责把模型行为对齐到人类偏好。现有奖励模型基准与优化后策略的表现相关性较弱，说明它们难以准确衡量奖励模型的真实能力。
- **关键词：** RLHF, reward-model, alignment

### Retrieval-Augmented Fine-Tuning With Preference Optimization For Visual Program Generation

- **作者：** Deokhyung Kang, Jeonghun Cho, Yejin Jeon, Sunbin Jang, Minsub Lee, Jawoon Cho, Gary Lee
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.1106/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.1106.pdf)
- **中文提要：** 可视化编程语言让用户通过图形界面创建程序，降低了使用门槛，并在多个领域得到广泛应用。为进一步提升这种可及性，近期研究开始用大语言模型根据用户指令生成可视化程序代码。
- **关键词：** DPO, SFT, preference-optimization, fine-tuning

### Revisiting Compositional Generalization Capability of Large Language Models Considering Instruction Following Ability

- **作者：** Yusuke Sakai, Hidetaka Kamigaito, Taro Watanabe
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.1508/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.1508.pdf)
- **中文提要：** 在 CommonGen 这类生成式常识推理中，大语言模型要写出包含全部给定概念的句子。一旦提示规定了概念顺序，生成结果也必须遵守该顺序。
- **关键词：** instruction-following

### RoCoFT: Efficient Finetuning of Large Language Models with Row-Column Updates

- **作者：** Md Kowsher, Tara Esmaeilbeig, Chun-Nam Yu, Chen Chen, Mojtaba Soltanalian, Niloofar Yousefi
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.1293/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.1293.pdf)
- **中文提要：** RoCoFT 是一种面向大语言模型的参数高效微调方法，只更新 Transformer 权重矩阵中的少量行和列。
- **关键词：** PEFT, fine-tuning

### RPO: Retrieval Preference Optimization for Robust Retrieval-Augmented Generation

- **作者：** Shi-Qi Yan, Quan Liu, Zhen-Hua Ling
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.261/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.261.pdf)
- **中文提要：** 检索增强生成虽能利用外部知识，其生成过程却高度依赖检索上下文的质量与准确性。当外部检索到的非参数知识与内部记忆不一致时，大语言模型难以判断其正确性，回答中就会出现知识冲突。
- **关键词：** preference-optimization, reward-model, alignment

### SCAR: Data Selection via Style Consistency-Aware Response Ranking for Efficient Instruction-Tuning of Large Language Models

- **作者：** Zhuang Li, Yuncheng Hua, Thuy-Trang Vu, Haolan Zhan, Lizhen Qu, Gholamreza Haffari
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.625/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.625.pdf)
- **中文提要：** 有研究强调，人工保证回答风格一致并维持较高的数据质量，可以提升微调后大语言模型的表现，同时减少所需训练样本。但风格的确切定义，以及风格、数据质量与模型表现之间的关系，仍然不清楚。
- **关键词：** instruction-tuning, fine-tuning

### SDD: Self-Degraded Defense against Malicious Fine-tuning

- **作者：** ZiXuan Chen, Weikai Lu, Xin Lin, Ziqian Zeng
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.1412/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.1412.pdf)
- **中文提要：** 开源大语言模型常用安全对齐来抵御有害指令。近期研究显示，在有害数据上做恶意微调就能轻易绕过这些防护。
- **关键词：** alignment, fine-tuning

### SDPO: Segment-Level Direct Preference Optimization for Social Agents

- **作者：** Aobo Kong, Wentao Ma, Shiwan Zhao, Yongbin Li, Yuchuan Wu, Ke Wang, Xiaoqian Liu, Qicheng Li, Yong Qin, Fei Huang
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.607/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.607.pdf)
- **中文提要：** 由大语言模型驱动的社会智能体能模拟人类社交行为，但处理复杂社会对话仍然不足。DPO 已在多种智能体任务中表现出把模型行为对齐到人类偏好的效果。
- **关键词：** DPO, preference-optimization, alignment

### SIFT-50M: A Large-Scale Multilingual Dataset for Speech Instruction Fine-Tuning

- **作者：** Prabhat Pandey, Rupak Vignesh Swaminathan, K V Vijay Girish, Arunasish Sen, Jian Xie, Grant P. Strimel, Andreas Schwarz
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.681/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.681.pdf)
- **中文提要：** SIFT（语音指令微调）是面向语音–文本大语言模型指令微调与预训练的数据集。它由公开语音语料构建，并借助大语言模型与现成的专家模型。
- **关键词：** instruction-following, fine-tuning

### SoRFT: Issue Resolving with Subtask-oriented Reinforced Fine-Tuning

- **作者：** Zexiong Ma, Chao Peng, Pengfei Gao, Xiangxin Meng, Yanzhen Zou, Bing Xie
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.559/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.559.pdf)
- **中文提要：** 主流问题修复框架主要依赖商业模型，带来高成本与隐私顾虑。现有的问题修复训练泛化较差，也未能充分利用开源开发资源。
- **关键词：** SFT, fine-tuning

### SOTOPIA-\ensuremath\Omega: Dynamic Strategy Injection Learning and Social Instruction Following Evaluation for Social Agents

- **作者：** Wenyuan Zhang, Tianyun Liu, Mengxiao Song, Xiaodong Li, Tingwen Liu
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.1203/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.1203.pdf)
- **中文提要：** 人类已有丰富的社交策略，但把这些策略迁移并整合进社会智能体的研究仍然很少。SOTOPIA-Ω 框架试图弥补这一缺口，并着重提升语言智能体的社交能力。
- **关键词：** instruction-following

### Symmetrical Visual Contrastive Optimization: Aligning Vision-Language Models with Minimal Contrastive Images

- **作者：** Shengguang Wu, Fan-Yun Sun, Kaiyue Wen, Nick Haber
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.1462/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.1462.pdf)
- **中文提要：** 大型视觉语言模型容易忽略图像内容、过度依赖语言模型先验，从而在需要视觉依据的任务上出错并产生幻觉。一种假设认为，原因在于现有模型没有被明确训练去生成准确依托细粒度图像细节的文本。
- **关键词：** alignment, fine-tuning

### SynthesizeMe! Inducing Persona-Guided Prompts for Personalized Reward Models in LLMs

- **作者：** Michael J. Ryan, Omar Shaikh, Aditri Bhagirath, Daniel Frees, William Held, Diyi Yang
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.397/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.397.pdf)
- **中文提要：** 多元对齐呼吁让大语言模型适应多样化的用户偏好。已有的个性化奖励模型却大多严重依赖额外身份信息，例如人口统计细节或预先划定的偏好类别。
- **关键词：** reward-model, alignment

### Synthesizing Post-Training Data for LLMs through Multi-Agent Simulation

- **作者：** Shuo Tang, Xianghe Pang, Zexi Liu, Bohan Tang, Rui Ye, Tian Jin, Xiaowen Dong, Yanfeng Wang, Siheng Chen
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.1136/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.1136.pdf)
- **中文提要：** 后训练对让大语言模型遵循人类指令必不可少，其效果取决于高质量指令数据。隐私顾虑、数据稀缺和标注成本，使这类数据在现实中很难获得。
- **关键词：** post-training

### TableLoRA: Low-rank Adaptation on Table Structure Understanding for Large Language Models

- **作者：** Xinyi He, Yihao Liu, Mengyu Zhou, Yeye He, Haoyu Dong, Shi Han, Zejian Yuan, Dongmei Zhang
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.1090/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.1090.pdf)
- **中文提要：** 在高参数效率设定下让大语言模型理解表格数据十分重要。直接把 PEFT 用于表格任务面临明显困难，尤其是更好的表格序列化，以及如何在一维表示中容纳二维结构信息。
- **关键词：** LoRA, PEFT, fine-tuning

### TaxoAdapt: Aligning LLM-Based Multidimensional Taxonomy Construction to Evolving Research Corpora

- **作者：** Priyanka Kargupta, Nan Zhang, Yunyi Zhang, Rui Zhang, Prasenjit Mitra, Jiawei Han
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.1442/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.1442.pdf)
- **中文提要：** 科学领域快速演进，给文献的组织与检索带来挑战。专家编撰的分类体系传统上用来满足这一需求，但过程耗时且昂贵。
- **关键词：** alignment

### Teaching an Old LLM Secure Coding: Localized Preference Optimization on Distilled Preferences

- **作者：** Mohammad Saqib Hasan, Saikat Chakraborty, Santu Karmaker, Niranjan Balasubramanian
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.1263/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.1263.pdf)
- **中文提要：** 大语言模型生成的代码经常包含安全问题。该研究着手处理改进安全代码生成时的两个关键挑战。
- **关键词：** DPO, SimPO, preference-optimization, alignment

### TeamLoRA: Boosting Low-Rank Adaptation with Expert Collaboration and Competition

- **作者：** Tianwei Lin, Jiang Liu, Wenqiao Zhang, Yang Dai, Haoyuan Li, Zhelun Yu, Wanggui He, Juncheng Li, Jiannan Guo, Hao Jiang, Siliang Tang, Yueting Zhuang
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.669/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.669.pdf)
- **中文提要：** LoRA 等 PEFT 方法能缓解微调时的资源约束，但性能常常不足，在多维任务场景中尤其明显。一种直接思路是把特定任务的 LoRA 当作领域专家，并利用对专家多种能力的建模。
- **关键词：** LoRA, PEFT, fine-tuning

### Think\&Cite: Improving Attributed Text Generation with Self-Guided Tree Search and Progress Reward Modeling

- **作者：** Junyi Li, Hwee Tou Ng
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.490/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.490.pdf)
- **中文提要：** 尽管能力突出，大语言模型仍容易产生幻觉和事实性错误。带归属的文本生成因此受到推动，它要求模型在生成内容时给出支持性证据。
- **关键词：** reward-model

### Towards Better Value Principles for Large Language Model Alignment: A Systematic Evaluation and Enhancement

- **作者：** Bingbing Xu, Jing Yao, Xiaoyuan Yi, Aishan Maoliniyazi, Xing Xie, Xiaofeng Meng
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.1408/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.1408.pdf)
- **中文提要：** 大语言模型要负责任地发展，就需要与人类价值对齐，而价值原则是澄清对齐目标的基础。已经提出了多套原则，例如有用、诚实、无害（HHH），以及 RLAIF 中用于数据合成的指令。
- **关键词：** RLAIF, alignment

### Towards Context-Robust LLMs: A Gated Representation Fine-tuning Approach

- **作者：** Shenglai Zeng, Pengfei He, Kai Guo, Tianqi Zheng, Hanqing Lu, Yue Xing, Hui Liu
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.506/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.506.pdf)
- **中文提要：** 通过 RAG 等方式引入外部上下文后，大语言模型常常难以应对不完美的证据。它们倾向于过度依赖外部知识，因而容易受到误导性或无帮助上下文的影响。
- **关键词：** fine-tuning

### Towards Effective and Efficient Continual Pre-training of Large Language Models

- **作者：** Jie Chen, Zhipeng Chen, Jiapeng Wang, Kun Zhou, Yutao Zhu, Jinhao Jiang, Yingqian Min, Wayne Xin Zhao, Zhicheng Dou, Jiaxin Mao, Yankai Lin, Ruihua Song, Jun Xu, Xu Chen, Rui Yan, Zhewei Wei, Di Hu, Wenbing Huang, Ji-Rong Wen
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.289/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.289.pdf)
- **中文提要：** 持续预训练是把语言模型适配到特定领域或任务的重要途径。该研究全面考察其关键设计，以求在获得新能力的同时保留原有能力，并提出一种能够提升大语言模型中文能力与科学推理能力的方法。
- **关键词：** continued-pretraining

### Towards Objective Fine-tuning: How LLMs' Prior Knowledge Causes Potential Poor Calibration?

- **作者：** Ziming Wang, Zeyu Shi, Haoyi Zhou, Shiqi Gao, Qingyun Sun, Jianxin Li
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.722/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.722.pdf)
- **中文提要：** 微调后的大语言模型常常校准不佳，置信分数与实际表现对不齐。校准在从头训练的模型上已被大量研究，但微调期间先验知识如何影响校准仍缺少探讨。
- **关键词：** fine-tuning

### Towards Reward Fairness in RLHF: From a Resource Allocation Perspective

- **作者：** Sheng Ouyang, Yulan Hu, Ge Chen, Qingyang Li, Fuzheng Zhang, Yong Liu
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.163/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.163.pdf)
- **中文提要：** 奖励充当人类偏好的代理，在 RLHF 中起着关键作用。若奖励本身不完美并带有各种偏差，就会对大语言模型的对齐产生不利影响。
- **关键词：** RLHF, reward-model, alignment

### Towards Robust and Efficient Federated Low-Rank Adaptation with Heterogeneous Clients

- **作者：** Jabin Koo, Minwoo Jang, Jungseul Ok
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.19/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.19.pdf)
- **中文提要：** 联邦微调受到关注，是因为传输大规模模型更新会带来沉重的通信开销。LoRA 被用来减轻这一负担，但它在联邦学习中的应用又因聚合不一致而变得复杂。
- **关键词：** LoRA, fine-tuning

### TRACT: Regression-Aware Fine-tuning Meets Chain-of-Thought Reasoning for LLM-as-a-Judge

- **作者：** Cheng-Han Chiang, Hung-yi Lee, Michal Lukasik
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.147/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.147.pdf)
- **中文提要：** 把大语言模型当作评审时，模型会依据评分细则为输入打分。现有微调方法使用交叉熵损失，忽略了分数预测的数值性质。
- **关键词：** fine-tuning

### T-REG: Preference Optimization with Token-Level Reward Regularization

- **作者：** Wenxuan Zhou, Shujian Zhang, Lingxiao Zhao, Tao Meng
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.1353/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.1353.pdf)
- **中文提要：** RLHF 借助人类偏好数据，使大语言模型能够遵循指令并形成有意义的对齐。传统做法是针对查询生成回答，再用单独的奖励模型为整段完成打分。
- **关键词：** RLHF, instruction-following, preference-optimization, reward-model, alignment

### Two Intermediate Translations Are Better Than One: Fine-tuning LLMs for Document-level Translation Refinement

- **作者：** Yichen Dong, Xinglin Lyu, Junhui Li, Daimeng Wei, Min Zhang, Shimin Tao, Hao Yang
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.726/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.726.pdf)
- **中文提要：** 近期研究表明，大语言模型可以通过自我修正来提升翻译质量。这里把修正从句子级延伸到文档级，并具体关注文档到文档的翻译修正。
- **关键词：** fine-tuning

### Uncertainty-Aware Iterative Preference Optimization for Enhanced LLM Reasoning

- **作者：** Lei Li, Hehuan Liu, Yaxin Zhou, ZhaoYang Gui, Xudong Weng, Yi Yuan, Zheng Wei, Zang Li
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.1169/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.1169.pdf)
- **中文提要：** DPO 近来成为把大语言模型对齐到人类偏好的一种高效方法。构建高质量偏好数据仍然困难，常常需要昂贵的人工标注或强大语言模型的标注。
- **关键词：** DPO, preference-optimization, alignment

### Uncovering the Impact of Chain-of-Thought Reasoning for Direct Preference Optimization: Lessons from Text-to-SQL

- **作者：** Hanbing Liu, Haoyang Li, Xiaokang Zhang, Ruotong Chen, Haiyong Xu, Tian Tian, Qi Qi, Jing Zhang
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.1031/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.1031.pdf)
- **中文提要：** 在数学应用题和代码生成等复杂推理任务上，DPO 已被证明有效。用到 Text-to-SQL 数据时，它却常常无法提升表现，甚至会使表现下降。
- **关键词：** DPO, preference-optimization

### Understanding Impact of Human Feedback via Influence Functions

- **作者：** Taywon Min, Haeone Lee, Yongchan Kwon, Kimin Lee
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.1333/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.1333.pdf)
- **中文提要：** 要从人类反馈中学到合适的奖励模型，才能在 RLHF 里把大语言模型对齐到人的意图。人类反馈却常常嘈杂、不一致或带有偏见，在评价复杂回答时尤其如此。
- **关键词：** RLHF, reward-model

### Unraveling LoRA Interference: Orthogonal Subspaces for Robust Model Merging

- **作者：** Haobo Zhang, Jiayu Zhou
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.1284/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.1284.pdf)
- **中文提要：** 按单个任务微调语言模型能取得较强表现，但部署和存储代价高。近期工作探索模型合并，把多个任务专用模型合成一个多任务模型，且无需额外训练。
- **关键词：** LoRA, fine-tuning

### UORA: Uniform Orthogonal Reinitialization Adaptation in Parameter Efficient Fine-Tuning of Large Models

- **作者：** Xueyan Zhang, Jinman Zhao, Zhifei Yang, Yibo Zhong, Shuhao Guan, Linbo Cao, Yining Wang
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.575/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.575.pdf)
- **中文提要：** UoRA 是一种面向大语言模型的参数高效微调（PEFT）方法。它借助低秩近似减少可训练参数，并力求在此过程中不牺牲性能。
- **关键词：** instruction-tuning, LoRA, PEFT, fine-tuning

### Upcycling Instruction Tuning from Dense to Mixture-of-Experts via Parameter Merging

- **作者：** Tingfeng Hui, Zhenyu Zhang, Shuohuan Wang, Yu Sun, Hua Wu, Sen Su
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.637/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.637.pdf)
- **中文提要：** 混合专家结构在大语言模型以及大量自然语言处理任务中表现突出。把稠密模型转为混合专家的现有方法数据需求很大，通常还依赖大规模后训练。
- **关键词：** instruction-tuning, post-training

### Velocitune: A Velocity-based Dynamic Domain Reweighting Method for Continual Pre-training

- **作者：** Zheheng Luo, Xin Zhang, Xiao Liu, Haoling Li, Yeyun Gong, Qi Chen, Peng Cheng
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.813/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.813.pdf)
- **中文提要：** 多样化语料对训练大语言模型至关重要，这类语料通常由多个领域混合而成。以往要么按静态比例从不同领域抽样，要么在训练过程中动态调整这些比例，以优化预训练表现。
- **关键词：** continued-pretraining

### WAFFLE: Fine-tuning Multi-Modal Model for Automated Front-End Development

- **作者：** Shanchao Liang, Nan Jiang, Shangshu Qian, Lin Tan
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.1208/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.1208.pdf)
- **中文提要：** 网页开发要把界面设计变成可用网页，HTML 的层级结构与样式使这件事对新手和有经验的开发者都不容易。大语言模型在生成源代码上已有潜力，但界面到 HTML 的生成仍有挑战，其中已写明的一点是如何有效表示 HTML 的层级结构。
- **关键词：** fine-tuning

### Whose Boat Does it Float? Improving Personalization in Preference Tuning via Inferred User Personas

- **作者：** Nishant Balepur, Vishakh Padmakumar, Fumeng Yang, Shi Feng, Rachel Rudinger, Jordan Boyd-Graber
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.168/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.168.pdf)
- **中文提要：** 大语言模型通过学习用户对同一提示下两条回答的偏好来遵循指令。这类偏好数据并不说明用户为何接受或拒绝某条回答，因此训练出的模型难以按不同用户需求调整回复。
- **关键词：** preference-optimization, alignment

### World Modeling Makes a Better Planner: Dual Preference Optimization for Embodied Task Planning

- **作者：** Siyin Wang, Zhaoye Fei, Qinyuan Cheng, Shiduo Zhang, Panpan Cai, Jinlan Fu, Xipeng Qiu
- **会议：** ACL 2025 · Main
- **官方论文页：** https://aclanthology.org/2025.acl-long.1044/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.acl-long.1044.pdf)
- **中文提要：** 大型视觉语言模型在具身任务规划上已显示出潜力，但仍难以应对依赖约束和效率问题。现有做法要么只优化动作选择，要么在推理时直接把预训练模型当作世界模型，忽略了学会建模世界对增强规划的好处。
- **关键词：** preference-optimization

## Findings

### AceMath: Advancing Frontier Math Reasoning with Post-Training and Reward Modeling

- **作者：** Zihan Liu, Yang Chen, Mohammad Shoeybi, Bryan Catanzaro, Wei Ping
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.206/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.206.pdf)
- **中文提要：** AceMath 是一套面向复杂数学问题的模型，并配有奖励模型来评估生成的解答、识别其中正确的结果。指令微调采用 SFT，先在通用领域取得有竞争力的表现。
- **关键词：** SFT, instruction-tuning, reward-model, post-training, fine-tuning

### A Comprehensive Graph Framework for Question Answering with Mode-Seeking Preference Alignment

- **作者：** Quanwei Tang, Sophia Yat Mei Lee, Junshuang Wu, Dong Zhang, Shoushan Li, Erik Cambria, Guodong Zhou
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.1108/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.1108.pdf)
- **中文提要：** 检索增强生成通过整合外部知识，提升了大语言模型的问答能力。要形成全局理解，并把回答对齐到人类的伦理与质量偏好，挑战仍然存在。
- **关键词：** preference-optimization, alignment

### Adaptive LoRA Merge with Parameter Pruning for Low-Resource Generation

- **作者：** Ryota Miyano, Yuki Arase
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.990/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.990.pdf)
- **中文提要：** 为把大语言模型适配到低资源语言生成，这项研究提出一种简单有效的 LoRA 合并方法。LoRA 合并将在不同任务上训练的多个 LoRA 模块整合起来，作为适配目标任务的高效途径而受到关注。
- **关键词：** LoRA, fine-tuning

### Adversarial Preference Learning for Robust LLM Alignment

- **作者：** Yuanfu Wang, Pengyu Wang, Chenyang Xi, Bo Tang, Junyi Zhu, Wenqiang Wei, Chen Chen, Chao Yang, Jingfeng Zhang, Chaochao Lu, Yijun Niu, Keming Mao, Zhiyu Li, Feiyu Xiong, Jie Hu, Mingchuan Yang
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.1126/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.1126.pdf)
- **中文提要：** 安全行为常靠 RLHF 来鼓励，但语言模型仍容易遭受对抗攻击。原因包括人工标注低效且成本高、潜在攻击形态极多，以及反馈偏差和奖励黑客风险。
- **关键词：** RLHF, alignment

### Align$^2$LLaVA: Cascaded Human and Large Language Model Preference Alignment for Multi-modal Instruction Curation

- **作者：** Hongzhe Huang, Jiang Liu, Zhewen Yu, Li Cai, Dian Jiao, Wenqiao Zhang, Siliang Tang, Juncheng Li, Hao Jiang, Haoyuan Li, Yueting Zhuang
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.458/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.458.pdf)
- **中文提要：** LLaVA 系列等多模态大模型的进展，主要依赖海量机器生成的指令跟随数据来微调。自动采集指令的流水线却会在无意中带来明显的数据质量差异。
- **关键词：** instruction-following, preference-optimization, reward-model, alignment

### Alleviating Hallucinations in Large Language Models via Truthfulness-driven Rank-adaptive LoRA

- **作者：** Jiahao Li, Zhendong Mao, Quan Wang
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.103/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.103.pdf)
- **中文提要：** 提升真实性以减轻幻觉，对大语言模型的实际部署已经变得关键。现有微调方法忽略内部各模块与真实性的关联并不一致，却把它们同等对待，这可能反过来削弱真实性改进的效果。
- **关键词：** LoRA, fine-tuning

### All That Glitters is Not Gold: Improving Robust Retrieval-Augmented Language Models with Fact-Centric Preference Alignment

- **作者：** Jia Hao, Chunhong Zhang, Jiarun Liu, Haiyu Zhao, Zhiqiang Zhan, Zheng Hu
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.588/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.588.pdf)
- **中文提要：** 检索增强语言模型靠外部检索知识生成回答，因此面对含噪声文档的检索结果时很脆弱。先前工作额外加入过滤器，或微调大语言模型以学习自适应检索，从而减轻噪声文档对性能的损害。
- **关键词：** preference-optimization, alignment, fine-tuning

### AMoPO: Adaptive Multi-objective Preference Optimization without Reward Models and Reference Models

- **作者：** Qi Liu, Jingqing Ruan, Hao Li, Haodong Zhao, Desheng Wang, Jiansong Chen, Wan Guanglu, Xunliang Cai, Zhi Zheng, Tong Xu
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.462/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.462.pdf)
- **中文提要：** 现有多目标偏好对齐难以有效平衡不同偏好维度，还依赖辅助奖励模型或参考模型，从而增加计算复杂度。AMoPO 被提出来应对这些限制，并寻求动态平衡。
- **关键词：** preference-optimization, reward-model, alignment

### ArgInstruct: Specialized Instruction Fine-Tuning for Computational Argumentation

- **作者：** Maja Stahl, Timon Ziegenbein, Joonsuk Park, Henning Wachsmuth
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.579/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.579.pdf)
- **中文提要：** 让大语言模型学会遵循指令，明显增强了它们处理未见任务的能力。即便泛化较强，这类指令跟随模型在需要领域知识的任务上仍然会遇到困难。
- **关键词：** instruction-following, fine-tuning

### A Semantic-Aware Layer-Freezing Approach to Computation-Efficient Fine-Tuning of Language Models

- **作者：** Jian Gu, Aldeida Aleti, Chunyang Chen, Hongyu Zhang
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.420/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.420.pdf)
- **中文提要：** 微调对让语言模型适应下游数据与任务至关重要。全量微调通常代价高昂。
- **关键词：** PEFT, fine-tuning

### ASPO: Adaptive Sentence-Level Preference Optimization for Fine-Grained Multimodal Reasoning

- **作者：** Yeyuan Wang, Dehong Gao, Rujiao Long, Lei Yi, Linbo Jin, Libin Yang, Xiaoyan Cai
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.267/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.267.pdf)
- **中文提要：** DPO 因简单且计算高效，在对齐大语言模型时受到广泛关注。近期工作已把它扩展到多模态场景，并取得较强表现。
- **关键词：** DPO, preference-optimization, alignment

### Asymmetric Conflict and Synergy in Post-training for LLM-based Multilingual Machine Translation

- **作者：** Tong Zheng, Yan Wen, Huiwen Bao, Junfeng Guo, Heng Huang
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.944/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.944.pdf)
- **中文提要：** 大语言模型推动了多语言机器翻译，多语言诅咒却仍是主要挑战。现有工作通常靠扩大训练与计算预算来缓解，并由此追问这种扩规模对高质量翻译是否真正必要。
- **关键词：** SFT, post-training, fine-tuning

### A Unified Taxonomy-Guided Instruction Tuning Framework for Entity Set Expansion and Taxonomy Expansion

- **作者：** Yanzhen Shen, Yu Zhang, Yunyi Zhang, Jiawei Han
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.167/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.167.pdf)
- **中文提要：** 实体集扩展、分类体系扩展和种子引导的分类构建，是用新兴概念自动充实已有分类体系的三类代表性任务。以往研究把它们视为三个彼此独立的任务。
- **关键词：** instruction-tuning

### Better Process Supervision with Bi-directional Rewarding Signals

- **作者：** Wenxiang Chen, Wei He, Zhiheng Xi, Honglin Guo, Boyang Hong, Jiazheng Zhang, Nijun Li, Tao Gui, Yun Li, Qi Zhang, Xuanjing Huang
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.747/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.747.pdf)
- **中文提要：** 过程监督逐一评估每一步，对复杂推理以及增加推理计算的测试时搜索都很关键。以过程奖励模型为代表的现有方法主要奖励截至当前步的信号，呈单向特点，缺少刻画距最终目标距离的机制。
- **关键词：** PRM, reward-model

### Beyond Reactive Safety: Risk-Aware LLM Alignment via Long-Horizon Simulation

- **作者：** Chenkai Sun, Denghui Zhang, ChengXiang Zhai, Heng Ji
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.332/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.332.pdf)
- **中文提要：** 语言智能体正越来越多地影响从公共政策到医疗的高风险社会决策，要让其建议真正有益，就得理解这些建议的长远后果。作者提出一个概念验证框架，在宏观尺度上随时间推演模型生成的建议如何在社会系统中传播。
- **关键词：** alignment

### Boosting Policy and Process Reward Models with Monte Carlo Tree Search in Open-Domain QA

- **作者：** Chi-Min Chan, Chunpu Xu, Junqi Zhu, Jiaming Ji, Donghai Hong, Pengcheng Wen, Chunyang Jiang, Zhen Ye, Yaodong Yang, Wei Xue, Sirui Han, Yike Guo
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.388/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.388.pdf)
- **中文提要：** 强推理能力的一个重要进展，是在测试阶段投入更多计算预算，使大语言模型有机会探索更准确、质量更高的解答。
- **关键词：** instruction-tuning, PRM, reward-model

### Boosting Vulnerability Detection of LLMs via Curriculum Preference Optimization with Synthetic Reasoning Data

- **作者：** Xin-Cheng Wen, Yijun Yang, Cuiyun Gao, Yang Xiao, Deheng Ye
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.467/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.467.pdf)
- **中文提要：** 不少编程相关任务上大语言模型已经相当熟练，检测软件漏洞的能力却仍然有限。原因之一是缺少与漏洞相关的推理数据，难以抓住底层漏洞模式；另一点是学习重心偏向语义。
- **关键词：** SFT, preference-optimization, fine-tuning

### CARMO: Dynamic Criteria Generation for Context Aware Reward Modelling

- **作者：** Taneesh Gupta, Shivam Shandilya, Xuchao Zhang, Rahul Madhavan, Supriyo Ghosh, Chetan Bansal, Huaxiu Yao, Saravan Rajmohan
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.114/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.114.pdf)
- **中文提要：** 奖励建模容易掉进奖励黑客：模型会抓住爱写列表或把回答无谓拉长这类表面特征。在 RLHF 以及更一般的后训练里，有缺陷的奖励信号常让输出去优化这些虚假相关，而不是真正的质量或正确性。
- **关键词：** RLHF, reward-model, post-training, alignment

### CodePRM: Execution Feedback-enhanced Process Reward Model for Code Generation

- **作者：** Qingyao Li, Xinyi Dai, Xiangyang Li, Weinan Zhang, Yasheng Wang, Ruiming Tang, Yong Yu
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.428/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.428.pdf)
- **中文提要：** 代码生成是大语言模型的一项关键推理任务。近期工作着重优化代码生成的思考过程，并取得了明显改进。
- **关键词：** PRM, reward-model

### Code-SPA: Style Preference Alignment to Large Language Models for Effective and Robust Code Debugging

- **作者：** Tengfei Wen, Xuanang Chen, Ben He, Le Sun
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.912/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.912.pdf)
- **中文提要：** 代码生成和调试等编程任务上，大语言模型已经表现突出。真实用户的代码却常常风格不佳，夹杂结构不一致、风格偏离以及有缺陷的测试用例等噪声。
- **关键词：** preference-optimization, alignment

### CoLA: Collaborative Low-Rank Adaptation

- **作者：** Yiyun Zhou, Chang Yao, Jingyuan Chen
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.726/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.726.pdf)
- **中文提要：** 缩放律表明大语言模型的性能与规模呈幂律关系，规模继续增大时收益递减。从头训练代价很高，针对具体任务微调预训练模型因此成为更实际的选择。
- **关键词：** LoRA, PEFT, fine-tuning

### Communication-Efficient and Tensorized Federated Fine-Tuning of Large Language Models

- **作者：** Sajjad Ghiasvand, Yifan Yang, Zhiyu Xue, Mahnoosh Alizadeh, Zheng Zhang, Ramtin Pedarsani
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.1241/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.1241.pdf)
- **中文提要：** PEFT 通常假定大语言模型使用单一设备或客户端上的数据来训练。现实中却常常需要在分散于多台设备的私有数据上做微调。
- **关键词：** PEFT, fine-tuning

### Comparing Bad Apples to Good Oranges Aligning Large Language Models via Joint Preference Optimization

- **作者：** Hritik Bansal, Ashima Suvarna, Gantavya Bhatt, Nanyun Peng, Kai-Wei Chang, Aditya Grover
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.39/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.39.pdf)
- **中文提要：** 对齐大语言模型的常见做法，是在固定上下文下比较多次生成来获取人类偏好。这种比较只在完全相同的上下文里做配对评估。
- **关键词：** DPO, preference-optimization, alignment

### Context-DPO: Aligning Language Models for Context-Faithfulness

- **作者：** Baolong Bi, Shaohan Huang, Yiwei Wang, Tianchi Yang, Zihan Zhang, Haizhen Huang, Lingrui Mei, Junfeng Fang, Zehao Li, Furu Wei, Weiwei Deng, Feng Sun, Qi Zhang, Shenghua Liu
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.536/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.536.pdf)
- **中文提要：** 可靠回答要求大语言模型同时遵守用户指令和检索到的信息。对齐有助于模型贴近人类意图与价值，但通过对齐提高对上下文的忠实程度仍较少被探索。
- **关键词：** DPO, preference-optimization, alignment

### Continued Pretraining and Interpretability-Based Evaluation for Low-Resource Languages: A Galician Case Study

- **作者：** Pablo Rodr{\'i}guez, Silvia Paniagua Su{\'a}rez, Pablo Gamallo, Susana Sotelo Docio
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.240/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.240.pdf)
- **中文提要：** 语言理解与文本生成已随大语言模型明显进步，弱势语言上的性能、持续学习时如何避免灾难性遗忘，以及如何建立稳健评测，却仍然是挑战。
- **关键词：** continued-pretraining

### CRPO: Confidence-Reward Driven Preference Optimization for Machine Translation

- **作者：** Guofeng Cui, Pichao Wang, Yang Liu, Zemian Ke, Zhu Liu, Vimal Bhat
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.31/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.31.pdf)
- **中文提要：** 机器翻译对大语言模型仍然困难：预训练以英语为中心，RLHF 本身也较复杂。DPO 被当作更简单、更高效的替代，但其表现对所依赖的条件非常敏感。
- **关键词：** DPO, RLHF, preference-optimization, fine-tuning

### daDPO: Distribution-Aware DPO for Distilling Conversational Abilities

- **作者：** Zhengze Zhang, Shiqi Wang, Yiqun Shen, Simin Guo, Dahua Lin, Xiaoliang Wang, Cam Tu Nguyen, Fei Tan
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.796/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.796.pdf)
- **中文提要：** 模型规模变小后，对话能力会急剧下降，给资源受限环境下的部署造成障碍。借助 DPO 做知识蒸馏，被视为增强小模型对话能力的一条有希望的路线。
- **关键词：** DPO, preference-optimization

### Debate, Reflect, and Distill: Multi-Agent Feedback with Tree-Structured Preference Optimization for Efficient Language Model Enhancement

- **作者：** Xiaofeng Zhou, Heyan Huang, Lizi Liao
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.475/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.475.pdf)
- **中文提要：** 知识密集与复杂推理任务上，大语言模型不断刷新表现，高计算需求却限制了推广。把大模型蒸馏成小模型更可持续，但静态知识蒸馏、耗费资源的 RLHF 以及有限的自我反思等现有技术仍然难以胜任。
- **关键词：** DPO, RLHF, preference-optimization

### Disentangling Reasoning Tokens and Boilerplate Tokens For Language Model Fine-tuning

- **作者：** Ziang Ye, Zhenru Zhang, Yang Zhang, Jianxin Ma, Junyang Lin, Fuli Feng
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.1078/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.1078.pdf)
- **中文提要：** 用智能体任务数据增强大语言模型时，现有做法常把样本里的全部词元同等对待。推理词元与控制输出格式等套话词元在重要性和学习难度上差别很大，因此需要把二者拆开。
- **关键词：** RFT, SFT, fine-tuning

### DPO Kernels: A Semantically-Aware, Kernel-Enhanced, and Divergence-Rich Paradigm for Direct Preference Optimization

- **作者：** Amitava Das, Suranjana Trivedy, Danush Khanna, Yaswanth Narsupalli, Basab Ghosh, Rajarshi Roy, Gurpreet Singh, Vinija Jain, Vasu Sharma, Aishwarya Naresh Reganti, Aman Chadha
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.1143/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.1143.pdf)
- **中文提要：** 大语言模型快速进入众多应用的同时，如何对齐多样的人类价值、伦理标准和具体用户偏好成为突出难题。DPO 虽是偏好对齐的基石，却受限于固定的散度度量以及有限的特征变换。
- **关键词：** DPO, instruction-following, preference-optimization, alignment

### Eeyore: Realistic Depression Simulation via Expert-in-the-Loop Supervised and Preference Optimization

- **作者：** Siyang Liu, Bianca Brie, Wenda Li, Laura Biester, Andrew Lee, James Pennebaker, Rada Mihalcea
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.707/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.707.pdf)
- **中文提要：** 心理健康培训和治疗来访者模拟已经尝试过语言模型，但多样的来访者特质与心理状况仍难以被真实捕捉。Eeyore 通过结构化对齐框架做更真实的抑郁模拟，并在每个阶段纳入专家输入。
- **关键词：** instruction-tuning, preference-optimization, alignment

### Expectation Confirmation Preference Optimization for Multi-Turn Conversational Recommendation Agent

- **作者：** Xueyang Feng, Jingsen Zhang, Jiakai Tang, Wei Li, Guohao Cai, Xu Chen, Quanyu Dai, Yue Zhu, Zhenhua Dong
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.307/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.307.pdf)
- **中文提要：** 对话推荐智能体得益于大语言模型的进展，却经常生成短视回复，既难以持续引导用户，也达不到对方预期。
- **关键词：** preference-optimization, alignment

### Exploiting Instruction-Following Retrievers for Malicious Information Retrieval

- **作者：** Parishad BehnamGhader, Nicholas Meade, Siva Reddy
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.673/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.673.pdf)
- **中文提要：** 指令跟随检索器已与大语言模型一起广泛用于实际场景，但其搜索能力增强带来的安全风险少有人研究。这项实证工作考察检索器满足恶意查询的能力，既包括直接使用，也包括放在检索增强生成流程中。
- **关键词：** instruction-following

### FedDQC: Data Quality Control in Federated Instruction-tuning of Large Language Models

- **作者：** Yaxin Du, Rui Ye, Fengting Yuchi, Wanru Zhao, Jingjing Qu, Yanfeng Wang, Siheng Chen
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.791/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.791.pdf)
- **中文提要：** 联邦学习借助大规模分布式数据，让大语言模型能在保护隐私的前提下协作做指令微调。去中心化却加剧数据质量问题：本地客户端缺少全局视野，训练前难以滤掉噪声或低质量样本。
- **关键词：** instruction-tuning, alignment, fine-tuning

### Federated Data-Efficient Instruction Tuning for Large Language Models

- **作者：** Zhen Qin, Zhaomin Wu, Bingsheng He, Shuiguang Deng
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.803/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.803.pdf)
- **中文提要：** 指令微调是让预训练大语言模型更好响应人类指令的关键步骤。联邦学习能利用客户端大量私有指令数据，并因提高数据多样性而成为大模型微调的常用途径。
- **关键词：** instruction-tuning

### FinRipple: Aligning Large Language Models with Financial Market for Event Ripple Effect Awareness

- **作者：** Yuanjian Xu, Jianing Hao, Kunsheng Tang, Jingnan Chen, Anxian Liu, Peng Liu, Guang Zhang
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.489/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.489.pdf)
- **中文提要：** 金融市场里，局部事件会在不同主体之间引发涟漪效应。以往事件研究多停留在静态的单公司分析并采用简化假设，捕捉不到这种连锁影响。
- **关键词：** alignment

### Focused-DPO: Enhancing Code Generation Through Focused Preference Optimization on Error-Prone Points

- **作者：** Kechi Zhang, Ge Li, Jia Li, Yihong Dong, Jia Li, Zhi Jin
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.498/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.498.pdf)
- **中文提要：** 代码生成模型在自动化编程上已显示出可观潜力。由于任务高度复杂且推理链很长，生成准确可靠的代码仍然困难。
- **关键词：** DPO, preference-optimization

### Full-Step-DPO: Self-Supervised Preference Optimization with Step-wise Rewards for Mathematical Reasoning

- **作者：** Huimin Xu, Xin Mao, Feng-Lin Li, Xiaobao Wu, Wang Chen, Wei Zhang, Anh Tuan Luu
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.1249/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.1249.pdf)
- **中文提要：** 长链条数学推理常常让 DPO 难以应付。Step-DPO 等现有改进通常把注意力放在推理链里第一个出错的步骤上。
- **关键词：** DPO, preference-optimization, PRM, reward-model

### GSQ-Tuning: Group-Shared Exponents Integer in Fully Quantized Training for LLMs On-Device Fine-tuning

- **作者：** Sifan Zhou, Shuo Wang, Zhihang Yuan, Mingjia Shi, Yuzhang Shang, Dawei Yang
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.1178/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.1178.pdf)
- **中文提要：** 微调大语言模型已经取得突出效果，传统做法却需要大量浮点计算，处理敏感数据时引发隐私顾虑，也不适合资源受限的边缘设备。
- **关键词：** LoRA, PEFT, fine-tuning

### How Do LLMs Acquire New Knowledge? A Knowledge Circuits Perspective on Continual Pre-Training

- **作者：** Yixin Ou, Yunzhi Yao, Ningyu Zhang, Hui Jin, Jiacheng Sun, Shumin Deng, Zhenguo Li, Huajun Chen
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.1021/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.1021.pdf)
- **中文提要：** 知识密集任务上的出色表现，并不意味着人们已经弄清大语言模型如何内化新知识，尤其是新知识如何在结构上嵌入神经计算。该研究从知识回路的演化入手，识别有助于存储和处理知识的计算子图。
- **关键词：** continued-pretraining

### Implicit Cross-Lingual Rewarding for Efficient Multilingual Preference Alignment

- **作者：** Wen Yang, Junhong Wu, Chen Wang, Chengqing Zong, Jiajun Zhang
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.1088/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.1088.pdf)
- **中文提要：** DPO 已成为对齐人类偏好的重要方法，并让英语大语言模型取得明显进展。多语言偏好对齐则受到数据稀缺的制约。
- **关键词：** DPO, instruction-following, preference-optimization, reward-model, alignment, fine-tuning

### Improving Continual Pre-training Through Seamless Data Packing

- **作者：** Ruicheng Yin, Xuan Gao, Changze Lv, Xiaohua Wang, Xiaoqing Zheng, Xuanjing Huang
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.777/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.777.pdf)
- **中文提要：** 持续预训练在提升模型表现上潜力很大，领域场景尤其明显。持续预训练之前最常见的数据打包，是把输入文本拼接后再切成固定长度的序列。
- **关键词：** continued-pretraining

### Instruction-Tuning Data Synthesis from Scratch via Web Reconstruction

- **作者：** Yuxin Jiang, Yufei Wang, Chuhan Wu, Xinyi Dai, Yan Xu, Weinan Gan, Yasheng Wang, Xin Jiang, Lifeng Shang, Ruiming Tang, Wei Wang
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.343/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.343.pdf)
- **中文提要：** 指令跟随能力能否提高，关键在于有没有高质量的指令与回答配对。现有自动合成减轻了人工整理负担，却往往严重依赖种子数据的质量，或对网页文档的结构和内容作很强的假设。
- **关键词：** instruction-tuning, instruction-following

### Instruction-Tuning LLMs for Event Extraction with Annotation Guidelines

- **作者：** Saurabh Srivastava, Sweta Pati, Ziyu Yao
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.677/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.677.pdf)
- **中文提要：** 这项研究考察标注指南，也就是对事件类型和论元的文字说明，在把大语言模型指令微调用于事件抽取时起什么作用。实验同时使用人工编写与机器生成的指南，并覆盖全量数据与低资源两种设定。
- **关键词：** instruction-tuning

### InternLM-XComposer2.5-Reward: A Simple Yet Effective Multi-Modal Reward Model

- **作者：** Yuhang Zang, Xiaoyi Dong, Pan Zhang, Yuhang Cao, Ziyu Liu, Shengyuan Ding, Shenxi Wu, Yubo Ma, Haodong Duan, Wenwei Zhang, Kai Chen, Dahua Lin, Jiaqi Wang
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.340/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.340.pdf)
- **中文提要：** 大型视觉语言模型在视觉理解上已有不错表现，仍会偶尔生成错误输出。奖励模型配合强化学习或测试时扩展有望改善生成质量，但面向这类模型、可以公开获得的多模态奖励模型仍然稀缺。
- **关键词：** instruction-tuning, instruction-following, reward-model

### JARVIS-VLA: Post-Training Large-Scale Vision Language Models to Play Visual Games with Keyboards and Mouse

- **作者：** Muyao Li, Zihao Wang, Kaichen He, Xiaojian Ma, Yitao Liang
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.920/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.920.pdf)
- **中文提要：** 开放世界环境里基于动作的决策近来受到很多关注。在大规模网页数据上预训练的视觉语言动作模型，已在决策任务中显示出潜力。
- **关键词：** post-training

### JsonTuning: Towards Generalizable, Robust, and Controllable Instruction Tuning

- **作者：** Chang Gao, Wenxuan Zhang, Guizhen Chen, Wai Lam
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.1232/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.1232.pdf)
- **中文提要：** 指令微调对提升大语言模型很重要，但被称为 TextTuning 的文本到文本做法缺少显式任务结构，在泛化、稳健性和可控性上吃力。JsonTuning 改为结构到结构，用 JSON 结构来表示任务。
- **关键词：** instruction-tuning

### KaFT: Knowledge-aware Fine-tuning for Boosting LLMs' Domain-specific Question-Answering Performance

- **作者：** Qihuang Zhong, Liang Ding, Xiantao Cai, Juhua Liu, Bo Du, Dacheng Tao
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.1235/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.1235.pdf)
- **中文提要：** SFT 常被用来提升大语言模型的领域问答表现。由于内部知识与训练数据里的上下文知识会发生冲突，用完整问答训练集做普通 SFT 通常并非最优。
- **关键词：** SFT, fine-tuning

### Know the Unknown: An Uncertainty-Sensitive Method for LLM Instruction Tuning

- **作者：** Jiaqi Li, Yixuan Tang, Yi Yang
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.153/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.153.pdf)
- **中文提要：** 幻觉往往源于知识或上下文不足。让模型以“我不知道”承认知识边界看似可行，但模型实际上一直很难承认自己的知识缺口。
- **关键词：** instruction-tuning, fine-tuning

### K-order Ranking Preference Optimization for Large Language Models

- **作者：** Shihao Cai, Chongming Gao, Yang Zhang, Wentao Shi, Jizhi Zhang, Keqin Bao, Qifan Wang, Fuli Feng
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.250/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.250.pdf)
- **中文提要：** 为让大语言模型适应排序任务，列表式 DPO 等方法着重优化偏序或全序层面的列表一致性。作者认为，面向真实应用，优化排名靠前部分的一致性更为合适。
- **关键词：** DPO, preference-optimization

### Massively Multilingual Instruction-Following Information Extraction

- **作者：** Thang Le, Huy Huu Nguyen, Anh Tuan Luu, Thien Huu Nguyen
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.182/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.182.pdf)
- **中文提要：** 信息抽取文献长期集中在少数语言上，限制了在多语言语料中的应用。MASSIE 是一套面向指令跟随式多语言信息抽取的综合集合，把大量人工标注数据加以标准化和统一，覆盖类型差异明显的多种语言和语系。
- **关键词：** instruction-following

### Matina: A Culturally-Aligned Persian Language Model Using Multiple LoRA Experts

- **作者：** Sara Bourbour Hosseinbeigi, MohammadAli SeifKashani, Javad Seraj, Fatemeh Taherinezhad, Ali Nafisi, Fatemeh Nadi, Iman Barati, Hosein Hasani, Mostafa Amiri, Mostafa Masoudi
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.1074/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.1074.pdf)
- **中文提要：** 要与用户有效交互，大语言模型需要贴合其文化价值和语言上的细微差别。现有模型往往难以充分刻画波斯语这类代表性不足的语言与文化，从而限制了适用性和接受度。
- **关键词：** LoRA, fine-tuning

### MEIT: Multimodal Electrocardiogram Instruction Tuning on Large Language Models for Report Generation

- **作者：** Zhongwei Wan, Che Liu, Xin Wang, Chaofan Tao, Hui Shen, Jing Xiong, Rossella Arcucci, Huaxiu Yao, Mi Zhang
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.749/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.749.pdf)
- **中文提要：** 心电图是监测心脏状况的主要无创诊断手段，对辅助临床至关重要。近期研究多集中于用心电图数据做病情分类，却较少关注既耗时又依赖临床专业知识的报告生成。
- **关键词：** instruction-tuning, alignment

### MELABenchv1: Benchmarking Large Language Models against Smaller Fine-Tuned Models for Low-Resource Maltese NLP

- **作者：** Kurt Micallef, Claudia Borg
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.1053/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.1053.pdf)
- **中文提要：** 多种自然语言处理任务上，大语言模型表现突出，很大程度上靠的是泛化能力以及不必额外训练就能完成任务。低资源语言上的效果却仍然有限。
- **关键词：** instruction-tuning, fine-tuning

### MeMoTune: A Measure and Moment-Driven Fine-Tuning Framework for Quantized Large Language Models

- **作者：** Yun Zhang, Xue Geng, Lizi Liao, Jintong Sun, Minghe Yu, Ge Yu
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.208/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.208.pdf)
- **中文提要：** 量化对降低大语言模型的显存和计算成本很必要。现有方法把量化与 PEFT 结合起来，却常常达不到实际性能要求。
- **关键词：** PEFT, fine-tuning

### MIG: Automatic Data Selection for Instruction Tuning by Maximizing Information Gain in Semantic Space

- **作者：** Yicheng Chen, Yining Li, Kai Hu, Ma Zerun, Haochen Ye, Kai Chen
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.515/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.515.pdf)
- **中文提要：** 质量和多样性是构建有效指令微调数据的关键。开源指令数据越来越多，从海量数据中自动选出高质量且多样的子集就更有价值。
- **关键词：** SFT, instruction-tuning, fine-tuning

### Mitigating Hallucination in Multimodal Large Language Model via Hallucination-targeted Direct Preference Optimization

- **作者：** Yuhan Fu, Ruobing Xie, Xingwu Sun, Zhanhui Kang, Xirong Li
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.850/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.850.pdf)
- **中文提要：** 多模态大语言模型会产生幻觉，因而限制了实际应用。近期有工作用 DPO 来提升这类模型，但在抑制幻觉上的改进并不稳定。
- **关键词：** DPO, preference-optimization

### Mosaic-IT: Cost-Free Compositional Data Synthesis for Instruction Tuning

- **作者：** Ming Li, Pei Chen, Chenguang Wang, Hongyu Zhao, Yijun Liang, YuPeng Hou, Fuxiao Liu, Tianyi Zhou
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.1297/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.1297.pdf)
- **中文提要：** 用多样的指令与回答配对做微调，增强了大语言模型理解并遵循指令的能力。当前主要靠教师模型或人工来生成并打磨这些训练数据，成本高、难以持续，多样性也可能不足。
- **关键词：** instruction-tuning, instruction-following, fine-tuning

### Order Matters: Investigate the Position Bias in Multi-constraint Instruction Following

- **作者：** Jie Zeng, Qianyu He, Qingyu Ren, Jiaqing Liang, Weikang Zhou, Zeye Sun, Fei Yu, Yanghua Xiao
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.646/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.646.pdf)
- **中文提要：** 带有多重约束的真实指令对现有大语言模型是很大挑战。一旦打乱这些约束的顺序，模型表现就会出现剧烈波动。
- **关键词：** instruction-following

### Outlier-weighed Layerwise Sampling for LLM Fine-tuning

- **作者：** Pengxiang Li, Lu Yin, Xiaowei Gao, Shiwei Liu
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.996/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.996.pdf)
- **中文提要：** 大语言模型的快速进步改变了多种自然语言处理任务，其巨大规模却给训练和微调带来显著困难。
- **关键词：** LoRA, PEFT, fine-tuning

### Packing Analysis: Packing Is More Appropriate for Large Models or Datasets in Supervised Fine-tuning

- **作者：** Shuhe Wang, Guoyin Wang, Yizhong Wang, Jiwei Li, Eduard Hovy, Chen Guo
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.256/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.256.pdf)
- **中文提要：** 打包最早用于预训练，把不同训练序列拼到模型的最大输入长度，以提高硬件利用率。它在预训练中已经有效，但 SFT 阶段对打包是否适用等问题仍缺少全面分析。
- **关键词：** SFT, fine-tuning

### Parameter-Efficient Fine-Tuning via Circular Convolution

- **作者：** Aochuan Chen, Jiashun Cheng, Zijing Liu, Ziqi Gao, Fugee Tsung, Yu Li, Jia Li
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.102/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.102.pdf)
- **中文提要：** LoRA 用低秩矩阵 A 和 B 表示权重变化，以此来微调大型基础模型并减少可训练参数。它让 A 与 B 依次和激活相乘，从而避开完整增量矩阵带来的高显存占用。
- **关键词：** LoRA, PEFT, fine-tuning

### Persona-judge: Personalized Alignment of Large Language Models via Token-level Self-judgment

- **作者：** Xiaotian Zhang, Ruizhe Chen, Yang Feng, Zuozhu Liu
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.260/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.260.pdf)
- **中文提要：** 对齐人类偏好时，如何在不过高计算成本下实现个性化是一大难点。现有方法依赖奖励信号和额外标注数据，限制了可扩展性，也难以适应多样的人类价值。
- **关键词：** alignment

### PGPO: Enhancing Agent Reasoning via Pseudocode-style Planning Guided Preference Optimization

- **作者：** Zouying Cao, Runze Wang, Yifei Yang, Xinbei Ma, Xiaoyong Zhu, Bo Zheng, Hai Zhao
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.774/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.774.pdf)
- **中文提要：** 处理复杂交互问题时，大语言模型智能体已经表现出很强能力。现有智能体主要靠自然语言计划引导推理，这种计划冗长且效率不高。
- **关键词：** preference-optimization

### P-React: Synthesizing Topic-Adaptive Reactions of Personality Traits via Mixture of Specialized LoRA Experts

- **作者：** Yuhao Dan, Jie Zhou, Qin Chen, Junfeng Tian, Liang He
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.328/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.328.pdf)
- **中文提要：** 个性化大语言模型在情感支持和角色扮演等应用中很受关注。现有工作主要刻画显式的人物设定，却忽略真正塑造行为与决策的底层人格特质，从而妨碍更拟人、更有心理学依据的系统。
- **关键词：** LoRA

### Probability-Consistent Preference Optimization for Enhanced LLM Reasoning

- **作者：** Yunqiao Yang, Houxing Ren, Zimu Lu, Ke Wang, Weikang Shi, Aojun Zhou, Junting Pan, Mingjie Zhan, Hongsheng Li
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.333/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.333.pdf)
- **中文提要：** 偏好优化在提升大语言模型数学推理上已显示出潜力，但现有做法多按答案正确性或一致性这类结果标准使用成对偏好，却忽略回答内部的逻辑连贯性。
- **关键词：** preference-optimization

### Process-based Self-Rewarding Language Models

- **作者：** Shimao Zhang, Xiao Liu, Xin Zhang, Junxiao Liu, Zheheng Luo, Shujian Huang, Yeyun Gong
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.930/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.930.pdf)
- **中文提要：** 大语言模型已在多种下游任务中表现突出并被广泛使用，进一步训练仍依赖人工标注的偏好数据，而这类数据受限于人类表现的上限。
- **关键词：** preference-optimization, self-rewarding

### Progressive LoRA for Multimodal Continual Instruction Tuning

- **作者：** Yahan Yu, Duzhen Zhang, Yong Ren, Xuanle Zhao, Xiuyi Chen, Chenhui Chu
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.143/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.143.pdf)
- **中文提要：** 多模态持续指令微调让多模态大语言模型适应不断变化的需求，而不必持续付出高昂的重训成本，但减轻灾难性遗忘和加强知识迁移仍然困难。
- **关键词：** instruction-tuning, LoRA, alignment

### RAG-RewardBench: Benchmarking Reward Models in Retrieval Augmented Generation for Preference Alignment

- **作者：** Zhuoran Jin, Hongbang Yuan, Tianyi Men, Pengfei Cao, Yubo Chen, Jiexin Xu, Huaijun Li, Xiaojian Jiang, Kang Liu, Jun Zhao
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.877/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.877.pdf)
- **中文提要：** 检索增强语言模型在给出可追溯来源的可信回答上已有明显进展，却常常忽视与人类偏好的有效对齐；对齐过程中，奖励模型被当作人类价值的代理来引导优化。
- **关键词：** preference-optimization, reward-model, alignment

### Removing Prompt-template Bias in Reinforcement Learning from Human Feedback

- **作者：** Chaojie Wang, Haonan Shi, Long Tian, Bo An, Shuicheng Yan
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.1237/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.1237.pdf)
- **中文提要：** RLHF 被用来增强预训练大语言模型，使其回答更符合人类偏好与社会价值；奖励模型训练仍面临 reward hacking，相关研究因而试图阻止奖励模型寻找捷径。
- **关键词：** RLHF, RFT, reward-model, fine-tuning

### Rethinking Table Instruction Tuning

- **作者：** Naihao Deng, Rada Mihalcea
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.1120/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.1120.pdf)
- **中文提要：** 表格理解的近期工作主要是对大语言模型做面向表格任务的指令微调，但超参数选择的影响、域外表格理解能力以及这些表格模型的通用能力都缺少全面考察。
- **关键词：** instruction-tuning

### Retrieval-Augmented Process Reward Model for Generalizable Mathematical Reasoning

- **作者：** Jiachen Zhu, Congmin Zheng, Jianghao Lin, Kounianhua Du, Ying Wen, Yong Yu, Jun Wang, Weinan Zhang
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.444/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.444.pdf)
- **中文提要：** 大语言模型显著推进了数学推理，过程奖励模型则被用来评估推理步骤在逻辑上是否成立，不过它们面对分布外情形仍然困难。
- **关键词：** PRM, reward-model

### Reverse Preference Optimization for Complex Instruction Following

- **作者：** Xiang Huang, Ting-En Lin, Feiteng Fang, Yuchuan Wu, Hangyu Li, Yuzhong Qu, Fei Huang, Yongbin Li
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.1064/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.1064.pdf)
- **中文提要：** 指令遵循是大语言模型的关键能力，可一旦指令带有多重约束，处理起来仍然不容易。
- **关键词：** DPO, instruction-following, preference-optimization, alignment

### Revisiting LoRA through the Lens of Parameter Redundancy: Spectral Encoding Helps

- **作者：** Jiashun Cheng, Aochuan Chen, Nuo Chen, Ziqi Gao, Yuhan Li, Jia Li, Fugee Tsung
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.139/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.139.pdf)
- **中文提要：** LoRA 已成为微调大型基础模型的突出技术，但显著的参数冗余限制了它的容量与效率，并被视作瓶颈。
- **关键词：** LoRA, fine-tuning

### Reward Generalization in RLHF: A Topological Perspective

- **作者：** Tianyi Alex Qiu, Fanzhi Zeng, Jiaming Ji, Dong Yan, Kaile Wang, Jiayi Zhou, Yang Han, Josef Dai, Xuehai Pan, Yaodong Yang
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.820/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.820.pdf)
- **中文提要：** 现有对齐方法共享同一套信息流拓扑：奖励信息来自人类，经偏好学习建模后用于调整语言模型；这一拓扑尚未被系统刻画，替代方案也缺少充分探索，数据效率低和泛化不可靠的问题因而仍在。
- **关键词：** RLHF, reward-model, alignment

### Robust Preference Optimization via Dynamic Target Margins

- **作者：** Jie Sun, Junkang Wu, Jiancan Wu, Zhibo Zhu, Xingyu Lu, Jun Zhou, Lintao Ma, Xiang Wang
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.282/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.282.pdf)
- **中文提要：** 大语言模型对齐关系到实际应用中的安全与可靠，DPO 则以偏好对直接优化模型，从而降低资源需求。
- **关键词：** DPO, preference-optimization, alignment

### RoleMRC: A Fine-Grained Composite Benchmark for Role-Playing and Instruction-Following

- **作者：** Junru Lu, Jiazheng Li, Guodong Shen, Lin Gui, Siyu An, Yulan He, Di Yin, Xing Sun
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.1082/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.1082.pdf)
- **中文提要：** 角色扮演要求大语言模型在遵循多样指令的同时保持角色身份及其预设能力边界；现有数据集多用于控制角色风格和知识边界，却较少覆盖指令遵循场景中的角色扮演。
- **关键词：** instruction-following, fine-tuning

### RoseRAG: Robust Retrieval-augmented Generation with Small-scale LLMs via Margin-aware Preference Optimization

- **作者：** Tianci Liu, Haoxiang Jiang, Tianze Wang, Ran Xu, Yue Yu, Linjun Zhang, Tuo Zhao, Haoyu Wang
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.676/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.676.pdf)
- **中文提要：** 大语言模型性能突出，但计算开销和延迟限制了资源受限场景下的部署；小规模模型更高效，却难以跟上不断变化的现实知识。
- **关键词：** preference-optimization

### Sci-LoRA: Mixture of Scientific LoRAs for Cross-Domain Lay Paraphrasing

- **作者：** Ming Cheng, Jiaying Gong, Hoda Eldardiry
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.953/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.953.pdf)
- **中文提要：** 面向非专业读者的通俗改写希望让科学信息更易懂，但现有研究大多只覆盖生物医学等单一领域。
- **关键词：** LoRA, fine-tuning

### Self-Rewarding Large Vision-Language Models for Optimizing Prompts in Text-to-Image Generation

- **作者：** Hongji Yang, Yucheng Zhou, Wencheng Han, Jianbing Shen
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.383/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.383.pdf)
- **中文提要：** 文生图模型能按给定提示产出高质量图像，但撰写这类提示往往需要专门词汇；已有改写模型则依赖大量人工标注和训练好的美学评估模型来做监督。
- **关键词：** reward-model, alignment, self-rewarding

### Self-Steering Optimization: Autonomous Preference Optimization for Large Language Models

- **作者：** Hao Xiang, Bowen Yu, Hongyu Lin, Keming Lu, Yaojie Lu, Xianpei Han, Ben He, Le Sun, Jingren Zhou, Junyang Lin
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.473/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.473.pdf)
- **中文提要：** 有效对齐依赖高质量偏好数据，近期研究因而转向人工介入尽量少的自动对齐系统。
- **关键词：** preference-optimization, alignment

### Separate the Wheat from the Chaff: A Post-Hoc Approach to Safety Re-Alignment for Fine-Tuned Language Models

- **作者：** Di Wu, Xin Lu, Yanyan Zhao, Bing Qin
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.66/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.66.pdf)
- **中文提要：** 大语言模型在发布时往往已经做过有效的安全对齐，微调却常常削弱这种对齐，并带来新的安全问题。
- **关键词：** LoRA, alignment, fine-tuning

### SGDPO: Self-Guided Direct Preference Optimization for Language Model Alignment

- **作者：** Wenqiao Zhu, Ji Liu, Lulu Wang, Jun Wu, Yulun Zhang
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.639/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.639.pdf)
- **中文提要：** DPO 因灵活而被广泛用于把大语言模型对齐到人类价值，但其生成人类更偏好回答的能力有限，结果也远不够稳健。
- **关键词：** DPO, preference-optimization, alignment

### StructFlowBench: A Structured Flow Benchmark for Multi-turn Instruction Following

- **作者：** Jinnan Li, Jinzhe Li, Yue Wang, Yi Chang, Yuan Wu
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.486/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.486.pdf)
- **中文提要：** 多轮指令遵循是大语言模型在真实应用中的核心能力；现有评测多看细粒度约束满足和领域能力，却忽略区分多轮与单轮的轮次间结构依赖。
- **关键词：** instruction-following

### SuLoRA: Subspace Low-Rank Adaptation for Parameter-Efficient Fine-Tuning

- **作者：** Chenhao Ding, Jiangyang Li, SongLin Dong, Xinyuan Gao, Yuhang He, Yihong Gong
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.278/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.278.pdf)
- **中文提要：** 随着大语言模型规模扩大、任务更加多样，PEFT 已成为微调的常规范式；其中 LoRA 因不增加推理开销而被广泛采用。
- **关键词：** LoRA, PEFT, fine-tuning

### TableDreamer: Progressive and Weakness-guided Data Synthesis from Scratch for Table Instruction Tuning

- **作者：** Mingyu Zheng, Zhifan Feng, Jia Wang, Lanrui Wang, Zheng Lin, Hao Yang, Weiping Wang
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.381/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.381.pdf)
- **中文提要：** 基于大语言模型的数据合成已有进展，但生成表格指令微调数据时仍有局限，首先是难以充分探索表格理解任务的广阔输入空间，数据多样性因此受限。
- **关键词：** instruction-tuning, fine-tuning

### The Lessons of Developing Process Reward Models in Mathematical Reasoning

- **作者：** Zhenru Zhang, Chujie Zheng, Yangzhen Wu, Beichen Zhang, Runji Lin, Bowen Yu, Dayiheng Liu, Jingren Zhou, Junyang Lin
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.547/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.547.pdf)
- **中文提要：** 过程奖励模型用来识别并缓解大语言模型数学推理中的中间错误，有效构建却受数据标注和评估方法制约；文中以实验讨论常用的蒙特卡洛估计数据。
- **关键词：** PRM, reward-model

### The Right Time Matters: Data Arrangement Affects Zero-Shot Generalization in Instruction Tuning

- **作者：** Bingxiang He, Ning Ding, Cheng Qian, Jia Deng, Ganqu Cui, Lifan Yuan, Haiwen Hong, Huan-ang Gao, Longtao Huang, Hui Xue, Huimin Chen, Zhiyuan Liu, Maosong Sun
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.13/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.13.pdf)
- **中文提要：** 理解对齐要从指令微调带来的零样本泛化入手，但其机制所知甚少；已有研究多停在任务层面，没有把任务看成人为划分、对模型而言只是词元与表示。
- **关键词：** instruction-tuning, alignment

### TUBA: Cross-Lingual Transferability of Backdoor Attacks in LLMs with Instruction Tuning

- **作者：** Xuanli He, Jun Wang, Qiongkai Xu, Pasquale Minervini, Pontus Stenetorp, Benjamin I. P. Rubinstein, Trevor Cohn
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.848/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.848.pdf)
- **中文提要：** 针对以英语为中心的大语言模型，后门可在训练中嵌入恶意行为，并在特定条件下触发有害输出；开源与专有模型的多语言支持正在增强，后门攻击对这类系统的影响随之被提出。
- **关键词：** instruction-tuning

### Weed Out, Then Harvest: Dual Low-Rank Adaptation is an Effective Noisy Label Detector for Noise-Robust Learning

- **作者：** Bo Yuan, Yulin Chen, Yin Zhang
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.792/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.792.pdf)
- **中文提要：** 用 PEFT 微调大语言模型在多种下游任务上表现突出，但许多真实场景里收集到的训练数据不可避免地带有噪声标签。
- **关键词：** LoRA, PEFT, fine-tuning

### Well Begun is Half Done: Low-resource Preference Alignment by Weak-to-Strong Decoding

- **作者：** Feifan Song, Shaohang Wei, Wen Luo, Yuxuan Fan, Tianyu Liu, Guoyin Wang, Houfeng Wang
- **会议：** ACL 2025 · Findings
- **官方论文页：** https://aclanthology.org/2025.findings-acl.655/
- **PDF / arXiv：** [PDF](https://aclanthology.org/2025.findings-acl.655.pdf)
- **中文提要：** 大语言模型需要对齐人类偏好，以免生成冒犯、虚假或无意义的内容；低资源对齐方法近来受到关注，但要同时得到高质量且已对齐的内容仍然困难。
- **关键词：** preference-optimization, alignment, fine-tuning
