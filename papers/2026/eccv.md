# 2026 · ECCV

共 65 篇。Main 65，Findings 0，其他赛道 0。其中 0 篇来源题录无摘要，提要标明「仅根据标题概括」。

检索窗口为 2024-11-13 至 2026-11-13。题录信息来自官方列表，不在此增补作者、链接或实验数字。

## Main

### ADAPT: Attention Dynamics Alignment with Preference Tuning for Faithful MLLMs

- **作者：** Zhiyuan Yao, Zheren Fu, Zhixiao Zheng, Jiajun Li, Yi Tu, Zhendong Mao
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/5033
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/8529.pdf)
- **中文提要：** 多模态大语言模型受到幻觉严重制约，会生成与给定图像不一致的内容。这里指出一种内部征象：生成过程中文本到图像的交叉注意力逐步退化，并表现为注意力失焦或偏向等失败模式。
- **关键词：** DPO, preference-optimization, alignment

### AnyStyle: A Single LoRA is Sufficient for Image-Guided Style Transfer

- **作者：** Yongwen Lai, Chaoqun Wang
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/4851
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/7704.pdf)
- **中文提要：** 图像引导的风格迁移要把风格图的艺术特征用到内容图上，同时保住语义结构与布局。基于扩散的方法虽有进展，但把各自优化的适配器简单拼在一起时，内容与风格仍难解开，适配器会互相冲突并限制可控性。
- **关键词：** LoRA

### Beyond Linear Shortcuts: Rectifying Diffusion Preference Optimization with Intrinsic Generative Geometry

- **作者：** Pin Wang, Huaibo Huang, Jiayang Sun, Hongbo Wang, Wentao Jiang, Tiezheng Ge, Jie Cao, Ran He
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/5151
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/9113.pdf)
- **中文提要：** DPO 已被证明能有效把扩散模型对齐到人类偏好。现有微调只依赖端点监督，因而忽略了预训练生成过程中弯曲的轨迹。
- **关键词：** DPO, preference-optimization, alignment, fine-tuning

### Beyond Where to Look: Trajectory-Guided Reinforcement Learning for Multimodal RLVR

- **作者：** Jinda Lu, Junkang Wu, Jinghan Li, Kexin Huang, Shuo Yang, Mingzhu Chen, Jiancan Wu, Kuien Liu, Xiang Wang
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/5594
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/11587.pdf)
- **中文提要：** 面向多模态大语言模型的 RLVR 近期主要提升最终答案正确性并加强视觉定位。瓶颈仍在：模型即便能注意到相关视觉区域，也常常无法把视觉证据有效纳入后续推理，推理链因此受影响。
- **关键词：** RLVR

### COLA: Continual Orthogonal Low-Rank Adaptation for Class-Incremental Learning

- **作者：** Monu Nagar, Debasis Das
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/5464
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/10799.pdf)
- **中文提要：** 持续学习近期采用带 LoRA 或提示微调的基础模型，借助预训练表示来学得更高效、更可适应。这些方法面临两项挑战，其一是为每个任务学习专用适配器，任务序列变长时参数会无界膨胀，摘要只写到这一点。
- **关键词：** LoRA, PEFT

### CollectionLoRA: Collecting 50 Effects in 1 LoRA for Deployment

- **作者：** Fangtai Wu, Hailong Guo, Shijie Huang, Jiayi Song, Yubo Huang, Mushui Liu, Zhao Wang, Yunlong Yu, Jiaming Liu, Ruihua Huang
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/4163
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/4751.pdf)
- **中文提要：** 定制图像编辑通常用 LoRA，在有限成对数据上给扩散模型装上特定视觉变换。推理时把加速类与效果类 LoRA 合在一起，却常互相干扰，导致概念渗漏、语义漂移和风格保真下降。
- **关键词：** LoRA

### Context Blindness in DPO: Mitigating Object Hallucination in MLLMs via Context-Calibrated Preference Optimization

- **作者：** Byungoh Ko, Jinyoung Park, Jongha Kim, Jeehye Na, Jaewon Cho, Hyunwoo Kim
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/5807
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/13197.pdf)
- **中文提要：** 多模态大语言模型进步很快，仍会出现物体幻觉，写出看似合理但与视觉输入不符的描述。DPO 通过让模型更偏好非幻觉回答来缓解这一点，近期工作还用相关上下文来丰富偏好数据。
- **关键词：** DPO, preference-optimization

### DA-MergeLoRA: Hypernetwork-Based LoRA Merging for Few-Shot Test-Time Domain Adaptation

- **作者：** Siobhan Reid, Zhixiang Chi, Li Gu, Omid Heidari, Ziqiang Wang, Yang Wang
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/4515
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/6303.pdf)
- **中文提要：** 少样本测试时域适应只用少量无标签目标样本，就把模型适配到新域，比训练阶段就能看到目标数据的典型设定更接近实际。已有方法却难以有效利用源域特有知识，多依赖浅层的批归一化更新。
- **关键词：** LoRA, fine-tuning

### DC-Gen: Post-Training Diffusion Acceleration with Deeply Compressed Latent Space

- **作者：** Wenkun He, Yuchao Gu, Junyu Chen, Junyi Wu, Wenhang Ge, Dongyun Zou, Yujun Lin, Zhekai Zhang, Haocheng Xi, Muyang Li, Ligeng Zhu, Jincheng YU, Junsong Chen, Enze Xie, Song Han, Han Cai
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/4727
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/7216.pdf)
- **中文提要：** 现有潜空间扩散模型借助自编码器把图像和视频投到潜空间，在视觉生成与编辑上表现突出。低压缩的潜变量却产生冗余、过多的视觉词元，限制了向高分辨率内容扩展。
- **关键词：** post-training, alignment, fine-tuning

### Diffusion-SDPO: Safeguarded Direct Preference Optimization for Diffusion Models

- **作者：** Minghao Fu, Guo-Hua Wang, Tianyu Cui, Qing-Guo Chen, Zhao Xu, Weihua Luo, Kaifu Zhang
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/5042
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/8573.pdf)
- **中文提要：** 文生图扩散模型虽能给出高质量图像，与人类偏好对齐仍然困难。该工作重访面向这类模型的扩散 DPO，指出拉大偏好间隔并不必然提升生成质量。
- **关键词：** DPO, preference-optimization, alignment

### Direct Diffusion Score Preference Optimization via Stepwise Contrastive Policy-Pair Supervision

- **作者：** Dohyun Kim, Seungwoo Lyu, Seung Kim, Paul Hongsuck Seo
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/4303
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/5313.pdf)
- **中文提要：** 扩散模型在文生图等任务上表现突出，却往往难以贴合细微用户意图并保持稳定审美。扩散直接偏好优化一类方法有助于缓解，但其监督目标取自前向过程。
- **关键词：** DPO, preference-optimization, reward-model

### Direct Preference Optimization for Perceptual Alignment via Vision-Language Consistency

- **作者：** Seungyeon Lee, Donggyu Lee
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/4769
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/7388.pdf)
- **中文提要：** 大视觉语言模型带动了对 DPO 等对齐方法的兴趣：它不必依赖昂贵监督或显式奖励建模，就能改善多模态指令跟随。此前借助数据增强和偏好排序改进 DPO 的尝试，仍不足以弥合视觉与语言的感知差距。
- **关键词：** DPO, instruction-following, preference-optimization, reward-model, alignment

### DisRM: Reward Modeling as Discriminative Prediction

- **作者：** Runtao Liu, Jiahao Zhan, Yuxuan GUO, Yingqing He, Chen Wei, Alan Yuille, Qifeng Chen
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/5189
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/9282.pdf)
- **中文提要：** 奖励模型是视觉生成模型后训练与测试时优化的核心，现有做法通常要么依赖大规模成对偏好标注，要么依赖重度工程化的多指标打分流程，两者都昂贵且费力。DisRM 把奖励建模做成判别式预测框架。
- **关键词：** DPO, SFT, reward-model, post-training, alignment

### Don't Let the Video Speak: Audio-Contrastive Preference Optimization for Audio-visual Language Models

- **作者：** Ami Baid, Zihui Xue, Kristen Grauman
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/4991
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/8339.pdf)
- **中文提要：** 音视频语言模型进展显著，可靠性却被跨模态幻觉卡住。一种普遍情形是视频驱动的音频幻觉：模型惯于借用视觉捷径编造预期声音，丢掉真实听觉证据，为对抗这种根深蒂固的视觉主导。
- **关键词：** preference-optimization

### DroneFINE: Domain-Aware Parameter-Efficient Fine-Tuning of Vision-Language Detectors for Drone Images

- **作者：** Wu Ke, Yanan Zhang, Yingjie Gao, Wenhao Li, Chenyu Zhou, Xinzhu Ma, Jiaxin Chen, Di Huang
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/4719
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/7179.pdf)
- **中文提要：** 开放动态环境中的无人机目标检测非常困难。视觉语言模型为通用检测提供了有力方案，但预训练数据与航拍影像之间的领域差距使适配并不容易。
- **关键词：** PEFT, fine-tuning

### Dual-Generalization-aware Minimization for Continual Fine-Tuning of Vision-Language Models

- **作者：** Yanan Chen, Tieliang Gong, Yanle Lyu, Yuanhong Zhang, Weizhan Zhang
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/3400
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/1281.pdf)
- **中文提要：** 持续微调 CLIP 等大型视觉语言模型，是让基础模型适应不断变化的真实分布的关键。这种适配却常常扰乱预训练表征，并严重损害零样本泛化。
- **关键词：** fine-tuning

### Finite Difference Flow Optimization for RL Post-Training of Text-to-Image Models

- **作者：** David McAllister, Miika Aittala, Tero Karras, Janne Hellsten, Angjoo Kanazawa, Timo Aila, Samuli Laine
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/5335
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/10054.pdf)
- **中文提要：** 强化学习已成为扩散式图像合成的常规后训练技术，因为它能从奖励信号学习，直接改进画质和提示对齐等期望属性。文中给出一种在线强化学习变体，靠采样成对轨迹并沿某一方向拉动流速度来降低更新方差。
- **关键词：** post-training, alignment

### From Sparse to Dense: Multi-View GRPO for Flow Models via Augmented Condition Space

- **作者：** Jiazi Bu, Pengyang Ling, Yujie Zhou, Yibin Wang, Yuhang Zang, Tianyi Wei, Xiaohang Zhan, Jiaqi Wang, Tong Wu, Xingang Pan, Dahua Lin
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/3460
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/1535.pdf)
- **中文提要：** GRPO 已成为文生图流模型偏好对齐的有力框架。标准范式只把一组生成样本对照单一条件来评估，对样本间关系探索不足，因而限制了对齐效果和性能上限。
- **关键词：** GRPO, preference-optimization, alignment

### Geo-DPO: Aligning Semantic Intent with Geometry for 3D Affordance Segmentation

- **作者：** Ziqian Yang, Xiaolei Wang, Xianglin Qiu, Weiguang Zhao, Quan Zhang, Jimin Xiao
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/5931
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/14357.pdf)
- **中文提要：** 三维序列可供性推理要求模型按语言指令定位一连串合乎逻辑的功能部件。当前多模态大语言模型的做法是生成一个特殊标记，用来引导最终的掩码预测。
- **关键词：** DPO, preference-optimization, alignment

### GeoSolver: Scaling Test-Time Reasoning in Remote Sensing with Fine-Grained Process Supervision

- **作者：** Sun Lang, Ronghao Fu, Zhuoran Duan, Haoran Liu, Xueyan Liu, Bo Yang
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/3860
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/3434.pdf)
- **中文提要：** 视觉语言模型显著推进了遥感解译，要完成复杂的逐步推理仍然很难。把思维链引入这一领域已显出潜力，如何保证这些中间步骤在视觉上忠实，仍是关键瓶颈。
- **关键词：** GRPO, PRM, reward-model

### GR-GRPO: Graph-Diffused Credit for Autoregressive Image RL Alignment

- **作者：** Zheyu Zhang, Peng-Tao Jiang, Tianyi Zheng, Jian Zhang, Jinwei Chen, Bo Li
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/4453
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/6006.pdf)
- **中文提要：** 自回归图像生成的强化学习对齐受昂贵采样展开制约：GRPO 式分组优化里，每个提示多采几条轨迹能改善探索和组内信用估计，却使采样成本成倍增加。向量量化分词会放大这一困难，因为嵌入空间中邻近码本标识可以局部替换。
- **关键词：** GRPO, alignment

### ID-LoRA: Identity-Driven Audio-Video Personalization with In-Context LoRA

- **作者：** Aviad Dahan, Moran Yanuka, Noa Kraicer, Lior Wolf, RAJA GIRYES
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/3277
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/743.pdf)
- **中文提要：** 现有视频个性化方法能保住视觉相貌，却把视频和音频分开处理。音频模型看不到画面就无法让声音与屏幕动作同步；经典声音克隆只以参考录音为条件，文本提示也无法改写说话风格或声学环境。
- **关键词：** LoRA, PEFT

### In-Context Sync-LoRA for Portrait Video Editing

- **作者：** Sagi Polaczek, Or Patashnik, Ali Mahdavi-Amiri, Danny Cohen-Or
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/4473
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/6099.pdf)
- **中文提要：** 人像视频编辑需要在改外观、改表情或添加物体等广泛修改上既灵活又精确。难点在于保住人物原有的时间行为，使每一帧编辑结果都与对应源帧精确同步。
- **关键词：** LoRA

### Learning Active Perception for Pixel-Space Reasoning via Visual-Intent Stratified GRPO

- **作者：** Mingkang Zhu, Xi Chen, Senqiao Yang, Bei Yu, Hengshuang ZHAO, Jiaya Jia
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/3757
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/2965.pdf)
- **中文提要：** 像素空间推理让视觉语言模型做主动感知：不必只凭单一全局视图作答，而可以放大到高分辨率区域收集细粒度证据。这对应于人类解视觉问题时先广泛寻找线索、再局部核对细节。
- **关键词：** GRPO, alignment

### Learning Consistency in Reward Modeling for Multi-Modal Reasoning

- **作者：** Chen Li, Bolin Ni, Boxin Zhang, Ke Ye, Jinnian Zhang, Houwen Peng, Han Hu, Nanning Zheng
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/5859
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/13629.pdf)
- **中文提要：** 多模态推理中的强化学习需要可靠奖励，现有方法却有明显短板：基于偏好的模型在复杂任务上常误判对错，基于规则的方法又难以处理语义等价答案，从而限制可用强化学习数据的规模。一致性奖励模型 CRM 用来评估某种吻合程度。
- **关键词：** reward-model

### Linguistically-Aligned and Visually-Grounded Preference Optimization for Clinically-Augmented Medical Report Generation

- **作者：** Qiang Hu, Yuxuan Luo, Yingjie Guo, Hao Wang, Qimei Wang, Qiang Li, Zhiwei Wang
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/5952
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/14605.pdf)
- **中文提要：** 医学报告生成虽有明显进展，可靠性仍受事实错误制约。DPO 被用作有希望的后训练范式来提升经过 SFT 的报告生成模型，但现有基于 DPO 的方法通常用朴素方式构造偏好，直接把模型生成内容配对。
- **关键词：** DPO, SFT, preference-optimization, post-training, alignment, fine-tuning

### Low-Rank Ternary Adaptation for Fine-Tuning Transformers

- **作者：** Alexandru-Dragos Manolache, Yunqiang Li, Jan van Gemert
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/5924
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/14318.pdf)
- **中文提要：** 三值 Transformer 在存储和计算上极为省，现有低比特 LoRA 方法却不能直接微调三值权重。当前做法要么先反量化、把低比特基座权重恢复到更高精度再与适配权重合并，要么只更新量化参数，因而得不到合并后仍保持三值的模型。
- **关键词：** LoRA, PEFT, fine-tuning

### Mechanistic Finetuning of Vision-Language-Action Models via Few-Shot Demonstrations

- **作者：** Chancharik Mitra, Yusen Luo, Raj Saravanan, Dantong Niu, Anirudh Pai, Jesse Thomason, Trevor Darrell, Abrar Anwar, Deva Ramanan, Roei Herzig
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/5828
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/13378.pdf)
- **中文提要：** 视觉-语言-动作模型有望把视觉语言模型的成功延伸到机器人。与视觉语言领域不同，面向机器人的这类模型必须微调，才能应对机器人本体、环境特性以及每项任务空间关系等变化的物理因素。
- **关键词：** LoRA, fine-tuning

### MixGRPO: Unlocking Flow-based GRPO Efficiency with Mixed ODE-SDE

- **作者：** Junzhe Li, Yutao Cui, Tao Huang, Chuxuan Zeng, Weijie Kong, Yinping Ma, Chun Fan, Miles Yang, Zhao Zhong, Liefeng Bo
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/5603
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/11626.pdf)
- **中文提要：** GRPO 明显改善了流匹配模型在视觉生成中的人类偏好对齐，DanceGRPO 等主流方法却在马尔可夫决策过程的全部时间步上做全局随机微分方程采样，计算仍然低效。MixGRPO 利用混合采样的灵活性。
- **关键词：** GRPO, preference-optimization, alignment

### MoGAN: Improving Motion Quality in Video Diffusion via Few-Step Motion Adversarial Post-Training

- **作者：** Haotian Xue, Qi Chen, Zhonghao Wang, Xun Huang, Eli Shechtman, Jinrong Xie, Yongxin Chen
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/3966
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/3892.pdf)
- **中文提要：** 视频扩散模型的单帧保真较强，运动连贯性、动态和真实感仍然不足，常出现抖动、重影或不合理的动态。标准去噪均方误差目标不直接监督时间一致性，模型可以损失很低却仍生成糟糕的运动。
- **关键词：** reward-model, post-training

### Multi-dimensional Preference Alignment by Conditioning Reward Itself

- **作者：** JIHO JANG, Jin-Young Kim, Kyungjune Baek, Nojun Kwak
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/3625
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/2257.pdf)
- **中文提要：** 人类反馈强化学习已成为对齐扩散模型的常规途径。标准 DPO 在优化多维偏好时有根本限制：它依赖 Bradley-Terry 模型，把审美质量、语义对齐等异质评价轴压成单一标量奖励。
- **关键词：** DPO, RLHF, preference-optimization, reward-model, alignment

### Omni-RRM: Advancing Omni Reward Modeling via Automatic Rubric-Grounded Preference Synthesis

- **作者：** Zicheng Kong, Dehua Ma, Zhenbo Xu, Anwen Yang, Yiwei Ru, Haoran Wang, Zixuan Zhou, Fuqing Bie, Liuyu Xiang, Huijia Wu, Jian Zhao, Zhaofeng He
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/4833
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/7646.pdf)
- **中文提要：** 多模态大语言模型难以对齐，因为现有奖励模型多以视觉为中心、依赖昂贵人工标注，并给出无法刻画细微推理的不透明标量分数，使对齐很脆弱。Omni-RRM 是以量规为依托的全模态奖励模型，会在文本等通道上产生多维奖励信号。
- **关键词：** GRPO, RLHF, SFT, reward-model, alignment

### One4D: Unified 4D Generation and Reconstruction via Decoupled LoRA Control

- **作者：** Zhenxing Mi, YUXIN WANG, Dan Xu
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/4290
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/5281.pdf)
- **中文提要：** One4D 用统一框架做四维生成与重建，把动态四维内容输出为同步的 RGB 帧和点图。它通过统一掩码条件机制处理不同稀疏程度的条件帧，从而在单图生成、完整视频重建以及生成与重建混合之间切换。
- **关键词：** LoRA, fine-tuning

### Personalized Reward Modeling for Text-to-Image Generation

- **作者：** Jeongeun Lee, Ryang Heo, Dongha Lee
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/4339
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/5468.pdf)
- **中文提要：** 近期文生图模型已能从文本提示生成语义连贯的图像，如何评估它们是否符合个人偏好仍是开放问题。通用奖励函数或基于相似度的常规评估，捕捉不到个人视觉口味的多样性与复杂性。
- **关键词：** reward-model, alignment

### PhyGDPO: Physics-Aware Groupwise Direct Preference Optimization for Physically Consistent Text-to-Video Generation

- **作者：** Yuanhao Cai, Kunpeng Li, Menglin Jia, Jialiang Wang, Junzhe Sun, Feng Liang, Weifeng Chen, Felix Juefei-Xu, Chu Wang, Ali Thabet, Xiaoliang Dai, Xuan JU, Alan Yuille, Ji Hou
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/4063
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/4366.pdf)
- **中文提要：** 文生视频的视觉质量已经较好，要合成真正遵守物理定律的视频仍是开放难题。主要依赖图形学或提示扩展的现有方法，难以推广到简单仿真环境之外，也难以学到隐含的物理推理。
- **关键词：** DPO, preference-optimization, LoRA

### PhysPO: Physics-Aware Local Preference Optimization for Physically Consistent Video Diffusion

- **作者：** Zhuoran Yang, Yanyong Zhang
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/3783
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/3096.pdf)
- **中文提要：** 视频扩散模型进步很快，保证语义遵循和物理常识仍是基本难题，即便先进系统也常违反动力学、热力学和光学等现实物理规律。DPO 已是对齐生成模型的常用后训练策略。
- **关键词：** DPO, preference-optimization, post-training, alignment

### POET: Preference Optimization for Enhanced Text-to-Image Generation

- **作者：** Ruibo Chen, Jiacheng Pan, Heng Huang, Zhenheng Yang
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/4253
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/5095.pdf)
- **中文提要：** 文生图近来结果突出，现有模型面对简单或欠指定的用户提示却常常吃力，因为这些提示与描述性训练字幕之间存在分布差距。这经常带来图文对齐、美感和整体视觉质量不佳。
- **关键词：** DPO, SFT, preference-optimization, alignment, fine-tuning

### Prompt2Effect: Training-Free LoRA Synthesis for Controllable Video Effects

- **作者：** Xiaomeng Yang, Yanyu Li, Gordon Qian, Ivan Skorokhodov, Viacheslav Ivanov, Avalon Vinella, Xuan Zhang, Yanzhi Wang, Sergey Tulyakov, Anil Kag
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/3453
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/1511.pdf)
- **中文提要：** 用特定视觉效果个性化图生视频扩散模型的需求在增加，现行做法却要为每种效果单独训练一个 LoRA，数据整理和迭代优化成本很高，妨碍交互控制。Prompt2Effect 用权重驱动的超网络来摊销这一开销。
- **关键词：** LoRA, alignment, fine-tuning

### REAL-OW: Rehearsal-free Open World Object Detection with Low-Rank Adaptation and Dual-Stage Objectness Modeling

- **作者：** Huazhong Zhang, Xiaowen Fu, Yang Zhang, Linlin Shen, Jinbao Wang
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/5205
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/9391.pdf)
- **中文提要：** 开放世界目标检测要求检测器把未见物体标为未知，并在保留已有知识的同时逐步纳入已知类别。现有框架主要靠样本回放缓解灾难性遗忘，但在部分实际应用中保存原始数据与访问限制冲突。
- **关键词：** LoRA

### RefReward-SR: LR-Conditioned Reward Modeling for Preference-Aligned Super-Resolution

- **作者：** Yushuai Song, Weize Quan, Weining Wang, Jiahui Sun, Jing Liu, Meng Li, Pengbin Yu, Zhentao Chen, Wei Shen, Lunxi Yuan, Dong-ming Yan
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/4797
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/7507.pdf)
- **中文提要：** 生成式超分辨率大幅提升了视觉真实感，现有评估与优化框架仍与人类感知不对齐。全参考和无参考指标常常反映不出感知偏好：像素错位时会惩罚语义上合理的细节，或者偏向看起来锐利却不一致的伪影。
- **关键词：** GRPO, reward-model, fine-tuning

### ReinDriveGen: Reinforcement Post-Training for Out-of-Distribution Driving Scene Generation

- **作者：** Hao ZHANG, Lue Fan, Weikang Bian, Zehuan Wu, Lewei Lu, Zhaoxiang Zhang, Hongsheng LI
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/3685
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/2585.pdf)
- **中文提要：** ReinDriveGen 让动态驾驶场景完全可控，用户可自由编辑参与者轨迹，以模拟前车碰撞、车辆漂移或失控旋转、行人乱穿以及骑行者横穿车道等安全关键情形。其做法从多帧激光雷达数据构建动态三维点云场景。
- **关键词：** post-training

### Reinforcing Vision-Language Models for Image Quality Assessment with Grounding Process Rewards

- **作者：** Jingwei Liu, Hongyan Li, Bo Liu, Tianlin Zhang, Yifei Qian, Congyang Zhao, Junhong Liu, Yang Cai, Ling Yang
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/5542
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/11291.pdf)
- **中文提要：** 图像质量评价要求模型输出与人类感知对齐。视觉语言模型虽有潜力，现有方法因缺少细粒度推理对齐而难以泛化。
- **关键词：** PRM, alignment

### Rethinking Reward Signals in Video GRPO: When Scores Become Targets

- **作者：** Rui Li, Yuanzhi Liang, Ziqi Ni, Haibin Huang, Chi Zhang, Xuelong Li
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/5060
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/8655.pdf)
- **中文提要：** GRPO 通过对视频生成做组内比较，支持稳定且面向偏好的后训练更新。它直接优化由奖励诱导的优势，摘要到此为止。
- **关键词：** GRPO, post-training, alignment

### Reward Modeling for Computer-Using Agent from Video Execution

- **作者：** Linxin Song, Jieyu Zhang, Huanxin Sheng, Taiwei Shi, Rahul Gupta, Yang Liu, Ranjay Krishna, Jian Kang, Jieyu Zhao
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/5001
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/8378.pdf)
- **中文提要：** 计算机使用智能体的能力在增强，要规模化判断一条轨迹是否真正完成用户指令仍然困难。这项研究从执行视频做奖励建模，所用材料是智能体轨迹中的关键帧序列，且与智能体内部推理或动作无关。
- **关键词：** reward-model, fine-tuning

### SAM+D: Parameter-Efficient Dimensional Lifting of SAM-Family Models via Depth-Routed LoRA and Depth Shifting

- **作者：** YU SONG, Hao Sun, TENG SHIYU, Ikuko Nishikawa, Yen-wei Chen
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/3465
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/1557.pdf)
- **中文提要：** 把 SAM 这类二维基础模型适配到三维体数据时，现有方法要么逐切片独立处理而忽略切片间上下文，要么需要大幅改架构并重新训练。SAM+D 以参数高效的方式把 SAM 系列模型沿一个空间维度抬升，从而用二维 SAM 做三维体分割。
- **关键词：** LoRA, PEFT, fine-tuning

### Self-Improving Diffusion Classifiers with Minority Preference Optimization

- **作者：** Hyunsoo Kim, Jungmyung Wi, Soobin Um, Donghyun Kim, Suhyun Kim
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/5692
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/12311.pdf)
- **中文提要：** 已有研究表明扩散分类器能取得稳健的零样本分类表现。其效果却强依赖预训练数据分布：在数据流形的多数、高密度区域表现好，在少数、低密度区域则明显更不准。
- **关键词：** GRPO, preference-optimization, reward-model, LoRA, fine-tuning

### Shared LoRA Subspaces for almost Strict Continual Learning

- **作者：** Prakhar Kaushik, Ankit Vaidya, Shravan Sunil Chaudhari, Rama Chellappa, Alan Yuille
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/3502
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/1734.pdf)
- **中文提要：** 高效且持续地把大型预训练模型适配到新任务对实际部署很重要，灾难性遗忘和重新训练的高成本使这件事仍然困难。LoRA 等参数高效微调降低了计算需求，却缺少在不靠数据回放、多适配器或 MoE 的情况下实现严格持续学习与知识整合的机制。
- **关键词：** LoRA, fine-tuning

### SHIFT: Motion Alignment in Video Diffusion Models with Adversarial Hybrid Fine-Tuning

- **作者：** Xi Ye, Wenjia Yang, Yangyang Xu, Xiaoyang Liu, Duo Su, Mengfei Xia, Jun Zhu
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/3988
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/3992.pdf)
- **中文提要：** 图像条件的视频扩散模型视觉真实感很强，运动保真却常变弱，例如动态减弱或长期时间连贯性下降，微调之后尤其明显。该研究关注视频扩散模型后训练中的运动对齐。
- **关键词：** post-training, alignment, fine-tuning

### SiGMA: Sign-Guided Merging and Adaptation framework for Multimodal Continual Instruction Tuning

- **作者：** Keonhee Park, Gunhee Kim
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/5258
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/9629.pdf)
- **中文提要：** 多模态持续指令微调用于让多模态大语言模型适应一连串不断变化的下游任务。先前方法多用混合专家或先扩展再合并，主要针对灾难性遗忘，推理时仍有负干扰：新学到的更新会覆盖有用的旧知识并造成退化。
- **关键词：** instruction-tuning

### SRUM: Fine-Grained Self-Rewarding for Unified Multimodal Models

- **作者：** Weiyang Jin, Yuwei Niu, Jiaqi Liao, Chengqi Duan, Aoxue Li, Shenghua Gao, Xihui Liu
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/4190
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/4870.pdf)
- **中文提要：** 统一多模态模型把视觉语言的生成与理解放进同一框架，进展显著。较强的视觉理解常常迁移不到视觉生成：模型可以正确判断提示与图像是否对齐，却无法根据同一提示生成忠实图像。
- **关键词：** reward-model, post-training, alignment, self-rewarding

### Steering 3D Generations: Preference Alignment via Direct Reward and Preference Optimization

- **作者：** Yuanhang Wang, Lizhe Qi, Wenqiang Zhang
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/5670
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/12161.pdf)
- **中文提要：** 从单张图像生成高保真且可控的三维资产仍然很难。这里提出把偏好优化接入基于矫正流的扩散模型，并在潜在集合表示上运作。
- **关键词：** DPO, preference-optimization, LoRA, PEFT, alignment, fine-tuning

### STEP: Spatial Thinking and Egocentric Pointing for Embodied Instruction Following

- **作者：** Hanxuan Li, Bin Fu, Zeyuan Lin, Ruiping Wang, Xilin CHEN
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/5165
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/9146.pdf)
- **中文提要：** 具身指令跟随要求智能体靠整体感知和合理规划来执行自然语言任务。当前由大语言模型驱动的智能体有两个主要瓶颈：有限的自我中心视角妨碍全局拓扑理解，规划又在缺乏可解释性的低效原子动作与含糊子目标之间两极分化。
- **关键词：** instruction-following

### StochasT: Learning with Stochastic Turn Depth for Visual Instruction Tuning

- **作者：** Yuan Qing, Chengzhi Mao, Boqing Gong
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/5503
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/11024.pdf)
- **中文提要：** 大型视觉语言模型大量依赖视觉指令微调来激发多模态推理。训练与评测并不一致：微调常把同一图像上的多项语言任务打包成对话式多轮训练，现有基准却在孤立的单轮场景中评估这些模型。
- **关键词：** instruction-tuning

### SupGRPO: Enhancing GRPO with Matching-based Online SFT for Text Spotting

- **作者：** Xudong Xie, Yuzhe Li, Jing Shi, Zhifei Zhang, Curtis Wigington, Zhaowen Wang
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/5729
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/12571.pdf)
- **中文提要：** 文本定位既要准确识别文字，也要精确给出空间位置。专用定位器擅长在自然场景中预测紧框，面对复杂或艺术字会失手；多模态大语言模型识别能力强，定位却仍然弱。
- **关键词：** GRPO, SFT, fine-tuning

### Swap the Right Identity: Spatio-Temporal Preference Optimization for Identity Swapping

- **作者：** Hongdeng Shen, Xiongzheng Li, Jikang Cheng, Duo Li, Yunlong FENG, Jing Li
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/5784
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/13022.pdf)
- **中文提要：** 角色替换希望忠实迁移目标身份，同时保住源场景的布局和姿态，得到视觉上无缝的合成。现有通用图像编辑方法往往难以同时做到身份一致、背景保留以及姿态或结构稳定。
- **关键词：** DPO, preference-optimization

### Syn-GRPO: Self-Evolving Data Synthesis for MLLM Perception Reasoning

- **作者：** Qihan Huang, Haofei Zhang, Rong Wei, Yi Wang, Rui Tang, Mingli Song, Jie Song
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/5711
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/12450.pdf)
- **中文提要：** 以 GRPO 为例的强化学习方法因泛化突出，被广泛用于提升多模态大语言模型的感知能力。现有方法仍受数据质量低的困扰：样本难以引出多样化回答，从而限制强化学习的探索范围。
- **关键词：** GRPO

### Towards Reliable Medical Large Vision-Language Models via Counterfactual Preference Optimization

- **作者：** Xiaoguang Zhu, NaipengWang NaipengWang, Kartik Patwari, Lianlong Sun, Chen-Nee Chuah, ChengxinPang ChengxinPang
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/4374
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/5657.pdf)
- **中文提要：** 医学大型视觉语言模型已成为理解医学图像和自动写报告的有力工具。现有模型常有模态偏差：背景上下文与诊断标签的相关会让模型依赖虚假先验而非病灶证据，从而产生与临床无关或幻觉式输出。
- **关键词：** DPO, preference-optimization

### UrbanAlign: Post-hoc Semantic Calibration for VLM-Human Preference Alignment

- **作者：** Yecheng Zhang, RONG ZHAO, Zhizhou Sha, Yong Li, Lei Wang, Ce Hou, Wen Ji, HUANG HAO, yunshan wan, Jian Yu, Junhao Xia, Yuru Zhang, Chunlei Shi
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/4316
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/5364.pdf)
- **中文提要：** 视觉语言模型能细致描述城市场景，却在安全评估、美学评价等特定任务上始终给不出可靠的人类偏好标签。常规补救是微调或 RLHF，而这需要大规模标注并重新训练模型。
- **关键词：** RLHF, preference-optimization, alignment, fine-tuning

### VD-LoRA: Adaptive Reuse of Low-Rank Directions for Continual Learning

- **作者：** Luqiong Ding, Jiayao Tan, Chenggong Ni, Fuyuan Hu, Fan Lyu
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/5333
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/10036.pdf)
- **中文提要：** 类增量学习要在持续获得新类别的同时保住已学知识，也就是稳定性与可塑性的两难。大型预训练模型出现后，LoRA 等参数高效微调把适配限制在低秩权重更新上，成为无回放类增量学习的实用范式。
- **关键词：** LoRA, PEFT, fine-tuning

### VERTIGO: Visual Preference Optimization for Cinematic Camera Generation

- **作者：** Mengtian Li, Yuwei Lu, Feifei Li, Chenqi Gan, Zhifeng Xie, Xi WANG
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/4222
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/4999.pdf)
- **中文提要：** 电影镜头控制依赖导演与摄影师之间紧密的反馈回路，运镜和构图被不断审看和修改。近期生成式相机系统能产生多样的文本条件轨迹，但缺少这种导演在环，也没有对镜头是否在视觉上可取的显式监督。
- **关键词：** DPO, preference-optimization, post-training, fine-tuning

### VisCritic: Visual State Comparison as Process Reward for GUI Agents

- **作者：** Jiachen Qian
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/4958
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/8192.pdf)
- **中文提要：** 由视觉语言模型驱动的图形界面智能体有望自动完成数字任务，但因缺少步骤级校验，在长程场景中经常失败。现有过程奖励模型只靠文本推理核验动作，忽略了界面状态变化本身是视觉的。
- **关键词：** PRM

### VisNec: Measuring and Leveraging Visual Necessity for Multimodal Instruction Tuning

- **作者：** Mingkang Dong, Hongyi Cai, jie li, Sifan Zhou, Bin Ren, Kunyu Peng, Yuqian Fu
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/4167
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/4773.pdf)
- **中文提要：** 多模态指令微调是否有效，不只取决于数据规模，还取决于训练样本是否真的需要视觉推理。现有指令数据里常有大量仅凭文本就能解答的视觉冗余样本，以及可能损害学习的多模态错位监督。
- **关键词：** instruction-tuning

### WearWow: Native 2K Multi-Garment Virtual Try-On via Adaptive Token Packing and Preference Alignment

- **作者：** Xujie Zhang, Runyan Du, Song Chang, Jiang Li, Dongliang Shao, Liping Wu, Luo Wei, Xiaochao Qu, Luoqi Liu, Xiaodan Liang
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/4590
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/6589.pdf)
- **中文提要：** 合成原生高分辨率、多服装的虚拟试穿是数字时尚中的难题，主要卡在两处：高分辨率条件带来的内存急剧膨胀，以及扩散模型的频谱偏差会过度平滑织物的高频细节。WearWow 是端到端、无需掩码的生成框架，面向超高分辨率试穿。
- **关键词：** preference-optimization, alignment

### When Rubrics Fail: Error Enumeration as Reward for Reference-Free RL Post-Training

- **作者：** Wisdom Ikezogwo, Mehmet Saygin Seyfioglu, Ranjay Krishna, Karim Bouyarmane
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/5549
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/11343.pdf)
- **中文提要：** 可验证奖励的强化学习，以及从理想参考答案合成评价标准的量规奖励，在有明确对错信号的领域乃至主观领域都带来明显进展。许多真实任务却允许多个合理输出，并不存在量规生成所依赖的唯一理想答案。
- **关键词：** RLVR, post-training

### Your Data Manifold is Secretly a Reward Model: Shell-LCC for Text-to-Video Generation

- **作者：** Shihao Zhang, Yunzhi Li, Yuguang Yan, Junzhe Zhang, WEI ZHAO, Bohan Wang, Hanwang Zhang
- **会议：** ECCV 2026 · Main · Poster
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/5650
- **PDF / arXiv：** [PDF](https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/12011.pdf)
- **中文提要：** 近期文生视频扩散模型严重依赖奖励模型或 DPO 等辅助奖励信号，以使生成内容贴近人类审美并提高真实感。这些信号计算开销大、需要昂贵的人工标注，而且对细粒度局部细节的改进往往有限。
- **关键词：** DPO, SFT, reward-model, fine-tuning
