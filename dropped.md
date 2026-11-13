# 已剔除的误收条目

从来源清单 3541 篇中剔除 **44** 篇。这些条目的标题关键词与 LLM / 基础模型微调或后训练撞车，或摘要表明核心贡献不在该范围。题录本身仍来自来源文件，没有改写作者、会议或链接。

### OneNet: A Fine-Tuning Free Framework for Few-Shot Entity Linking via Large Language Model Prompting

- **作者：** Xukai Liu, Ye Liu, Kai Zhang, Kehang Wang, Qi Liu, Enhong Chen
- **会议：** EMNLP 2024
- **官方论文页：** https://aclanthology.org/2024.emnlp-main.756/
- **剔除原因：** 免微调的提示式实体链接，核心不是微调方法。

### 3D Structure Prediction of Atomic Systems with Flow-based Direct Preference Optimization

- **作者：** Rui Jiao, Xiangzhe Kong, Wenbing Huang, Yang Liu
- **会议：** NeurIPS 2024
- **官方论文页：** https://proceedings.neurips.cc/paper_files/paper/2024/hash/c6fdc94aeb2cb3a426d510d970045dab-Abstract-Conference.html
- **剔除原因：** 流模型 DPO 用于原子体系三维结构，不是 LLM/基础模型后训练。

### VQ4DiT: Efficient Post-Training Vector Quantization for Diffusion Transformers

- **作者：** Juncan Deng, Shuaiting Li, Zeyu Wang, Hong Gu, Kedong Xu, Kejie Huang
- **会议：** AAAI 2025
- **官方论文页：** https://doi.org/10.1609/aaai.v39i15.33782
- **剔除原因：** Post-training 指扩散 Transformer 的训练后向量量化，不是 SFT/RLHF 后训练。

### AIM-Fair: Advancing Algorithmic Fairness via Selectively Fine-Tuning Biased Models with Contextual Synthetic Data

- **作者：** Zengqun Zhao, Ziquan Liu, Yu Cao, Shaogang Gong, Ioannis Patras
- **会议：** CVPR 2025
- **官方论文页：** https://cvpr.thecvf.com/virtual/2025/poster/34203
- **剔除原因：** 用合成数据选择性微调有偏模型以做公平性，摘要未涉及 LLM/基础模型后训练。

### Attend to Not Attended: Structure-then-Detail Token Merging for Post-training DiT Acceleration

- **作者：** Haipeng Fang, Sheng Tang, Juan Cao, Enshuo Zhang, Fan Tang, Tong-yee Lee
- **会议：** CVPR 2025
- **官方论文页：** https://cvpr.thecvf.com/virtual/2025/poster/35120
- **剔除原因：** Post-training 指 DiT 推理加速中的 token 合并。

### Dora: Sampling and Benchmarking for 3D Shape Variational Auto-Encoders

- **作者：** Rui Chen, Jianfeng Zhang, Yixun Liang, Guan Luo, Weiyu Li, Jiarui Liu, Xiu Li, Xiaoxiao Long, Jiashi Feng, Ping Tan
- **会议：** CVPR 2025
- **官方论文页：** https://cvpr.thecvf.com/virtual/2025/poster/34804
- **剔除原因：** 标题中的 Dora 是三维形状变分自编码器（Dora-VAE），不是 DoRA/LoRA。

### Thin-Shell-SfT: Fine-Grained Monocular Non-rigid 3D Surface Tracking with Neural Deformation Fields

- **作者：** Navami Kairanda, Marc Habermann, Shanthika Shankar Naik, Christian Theobalt, Vladislav Golyanik
- **会议：** CVPR 2025
- **官方论文页：** https://cvpr.thecvf.com/virtual/2025/poster/33446
- **剔除原因：** SfT 指 Shape-from-Template，不是监督微调（SFT）。

### EvolvingGrasp: Evolutionary Grasp Generation via Efficient Preference Alignment

- **作者：** Yufei Zhu, Yiming Zhong, Zemin Yang, Peishan Cong, Jingyi Yu, Xinge Zhu, Yuexin Ma
- **会议：** ICCV 2025
- **官方论文页：** https://iccv.thecvf.com/virtual/2025/poster/1466
- **剔除原因：** 偏好对齐用于灵巧抓取，摘要未涉及语言模型或基础模型微调。

### From Enhancement to Understanding: Build a Generalized Bridge for Low-light Vision via Semantically Consistent Unsupervised Fine-tuning

- **作者：** Sen Wang, Shao Zeng, Tianjun Gu, zhizhong zhang, Ruixin Zhang, Shouhong Ding, Jingyun Zhang, Jun Wang, Xin TAN, Yuan Xie, Lizhuang Ma
- **会议：** ICCV 2025
- **官方论文页：** https://iccv.thecvf.com/virtual/2025/poster/102
- **剔除原因：** 低光视觉的无监督微调。

### SPA: Efficient User-Preference Alignment against Uncertainty in Medical Image Segmentation

- **作者：** Jiayuan Zhu, Junde Wu, Cheng Ouyang, Konstantinos Kamnitsas, Alison Noble
- **会议：** ICCV 2025
- **官方论文页：** https://iccv.thecvf.com/virtual/2025/poster/1018
- **剔除原因：** 医学分割标注偏好，不是语言模型偏好对齐。

### ViM-VQ: Efficient Post-Training Vector Quantization for Visual Mamba

- **作者：** Juncan Deng, Shuaiting Li, Zeyu Wang, Kedong Xu, Hong Gu, Kejie Huang
- **会议：** ICCV 2025
- **官方论文页：** https://iccv.thecvf.com/virtual/2025/poster/1569
- **剔除原因：** Post-training 指视觉 Mamba 的训练后向量量化。

### A Distributional Approach to Uncertainty-Aware Preference Alignment Using Offline Demonstrations

- **作者：** Sheng Xu, Bo Yue, Hongyuan Zha, Guiliang Liu
- **会议：** ICLR 2025
- **官方论文页：** https://openreview.net/forum?id=RKOAU5ti1y
- **剔除原因：** 离线偏好强化学习，摘要未涉及语言模型。

### Effective post-training embedding compression via temperature control in contrastive training

- **作者：** georgiana dinu, Corey Barrett, Yi Xiang, Miguel Romero Calvo, Anna Currey, Xing Niu
- **会议：** ICLR 2025
- **官方论文页：** https://openreview.net/forum?id=szRmEM8Kx5
- **剔除原因：** Post-training 指对比学习嵌入压缩。

### Forget the Data and Fine-Tuning! Just Fold the Network to Compress

- **作者：** Dong Wang, Haris Šikić, Lothar Thiele, Olga Saukh
- **会议：** ICLR 2025
- **官方论文页：** https://openreview.net/forum?id=W2Wkp9MQsF
- **剔除原因：** 方法是无数据网络折叠压缩，标题明确不做微调。

### Indirect Alignment and Relationship Preservation for Domain Generalization

- **作者：** Wei Wei, Zixiong Li, Jing Yan, Mingwen Shao, Lin Li
- **会议：** IJCAI 2025
- **官方论文页：** https://doi.org/10.24963/ijcai.2025/229
- **剔除原因：** 来源无摘要。标题是域泛化中的对齐，不是语言模型对齐。

### Reward Models in Deep Reinforcement Learning: A Survey

- **作者：** Rui Yu, Shenghua Wan, Yucen Wang, Chen-Xiao Gao, Le Gan, Zongzhang Zhang, De-Chuan Zhan
- **会议：** IJCAI 2025
- **官方论文页：** https://doi.org/10.24963/ijcai.2025/1199
- **剔除原因：** 来源无摘要。深度强化学习奖励模型综述，标题未指向语言模型。

### DriveDPO: Policy Learning via Safety DPO For End-to-End Autonomous Driving

- **作者：** Shuyao Shang, Yuntao Chen, Yuqi Wang, Yingyan Li, ZHAO-XIANG ZHANG
- **会议：** NeurIPS 2025
- **官方论文页：** https://openreview.net/forum?id=eIf9GNcA5n
- **剔除原因：** DPO 用于端到端驾驶轨迹，摘要未涉及语言模型或生成式基础模型。

### Beyond Training-time Poisoning: Component-level and Post-training Backdoors in Deep Reinforcement Learning

- **作者：** Sanyam Vyas, Alberto Caron, Chris Hicks, Pete Burnap, Vasilios Mavroudis
- **会议：** AAAI 2026
- **官方论文页：** https://doi.org/10.1609/aaai.v40i31.39809
- **剔除原因：** 通用深度强化学习后门；post-training 指训练之后，不是 LLM 后训练。

### FD-MAGRPO: Functionality-Driven Multi-Agent Group Relative Policy Optimization for Analog-LDO Sizing

- **作者：** Haoning Jiang, Han Wu, Zhuoli Ouyang, Ziheng Wang, Tinghuan Chen, Junmin Jiang
- **会议：** AAAI 2026
- **官方论文页：** https://doi.org/10.1609/aaai.v40i27.39388
- **剔除原因：** GRPO 用于模拟 LDO 电路尺寸，不是语言模型后训练。

### FlowAnyTime: Efficient Fine-tuning with Intra-Inter Frame Distillation for All-Weather Optical Flow Estimation

- **作者：** Zixu Wang, Hongye Chen, Xiaochun Zou, Congxuan Zhang, Zhen Chen, Xinbo Zhao
- **会议：** AAAI 2026
- **官方论文页：** https://doi.org/10.1609/aaai.v40i13.38019
- **剔除原因：** 微调对象是光流估计网络。

### Small but Mighty: Dynamic Wavelet Expert-Guided Fine-Tuning of Large-Scale Models for Optical Remote Sensing Object Segmentation

- **作者：** Yanguang Sun, Chao Wang, Jian Yang, Lei Luo
- **会议：** AAAI 2026
- **官方论文页：** https://doi.org/10.1609/aaai.v40i11.37880
- **剔除原因：** 微调用于光学遥感分割，摘要未涉及 LLM 或视觉语言基础模型。

### WorldRFT: Latent World Model Planning with Reinforcement Fine-Tuning for Autonomous Driving

- **作者：** Pengxuan Yang, Ben Lu, Zhongpu Xia, Chao Han, Yinfeng Gao, Teng Zhang, Kun Zhan, Xianpeng Lang, Yupeng Zheng, Qichao Zhang
- **会议：** AAAI 2026
- **官方论文页：** https://doi.org/10.1609/aaai.v40i14.38149
- **剔除原因：** 强化微调对象是自动驾驶潜世界模型。

### AFT-Tab: Adversarial Fine-Tuning for Tabular Data Synthesis with Long Text Columns

- **作者：** Yuhao Zhang, Liang Yan, Shaoming Duan, Xinyu Zha, Jinhang Su, Peiyi Han, Chuanyi Liu
- **会议：** ACL 2026
- **官方论文页：** https://aclanthology.org/2026.acl-long.209/
- **剔除原因：** 对抗微调用于表格数据合成，摘要未涉及语言模型微调。

### LinVideo: A Post-Training Framework towards O(n) Attention in Efficient Video Generation

- **作者：** Yushi Huang, Xingtong Ge, Ruihao Gong, Chengtao Lv, Jun Zhang
- **会议：** CVPR 2026
- **官方论文页：** https://openaccess.thecvf.com/content/CVPR2026/html/Huang_LinVideo_A_Post-Training_Framework_towards_On_Attention_in_Efficient_Video_CVPR_2026_paper.html
- **剔除原因：** 来源无摘要。标题目标是高效视频生成的线性注意力，不是 SFT/RL 后训练。

### Post-training Feature Pruning for Fundus Images Classification

- **作者：** Van-Nguyen Pham, Duc-Tai Le, Junghyun Bum, Hyunseung Choo
- **会议：** CVPR 2026
- **官方论文页：** https://openaccess.thecvf.com/content/CVPR2026/html/Pham_Post-training_Feature_Pruning_for_Fundus_Images_Classification_CVPR_2026_paper.html
- **剔除原因：** 眼底图像分类的训练后特征剪枝；来源无摘要。

### Indelible Backdoors: On the Limits of Post-Training Defenses

- **作者：** Jingyi Guo, Thuy Dung Nguyen, Taylor T Johnson, Kevin Leach
- **会议：** ECCV 2026
- **官方论文页：** https://eccv.eventhosts.cc/virtual/2026/poster/5639
- **剔除原因：** 通用深度网络后门与微调式防御，不是语言模型后训练。

### HEAL: Latent Head Alignment for Post-Training Quantization of Large Language Models

- **作者：** Mingzhe Yang, Sihao Lin, Ruibo Zhang, Xinyuan Zhu, Lei Chen, Weidong Chen, Xiaojun Chang
- **会议：** EMNLP 2026
- **官方论文页：** https://aclanthology.org/2026.emnlp-main.326/
- **剔除原因：** 大模型训练后量化；Alignment 指潜在注意力头对齐。

### Advancing Multi-agent Traffic Simulation via R1-Style Reinforcement Fine-Tuning

- **作者：** Muleilan Pei, Shaoshuai Shi, Shaojie Shen
- **会议：** ICLR 2026
- **官方论文页：** https://openreview.net/forum?id=7BiQwV9Sic
- **剔除原因：** R1 式强化微调用于交通仿真，摘要未涉及语言模型。

### Quant-dLLM: Post-Training Extreme Low-Bit Quantization for Diffusion Large Language Models

- **作者：** Tianao Zhang, Zhiteng Li, Xianglong Yan, Haotong Qin, Yong Guo, Yulun Zhang
- **会议：** ICLR 2026
- **官方论文页：** https://openreview.net/forum?id=HD7tuVakmR
- **剔除原因：** 扩散大语言模型的极低比特训练后量化，不是微调或偏好优化。

### Steerable Adversarial Scenario Generation through Test-Time Preference Alignment

- **作者：** Tong Nie, Yuewen Mei, Yihong Tang, Junlin He, Jie Sun, Haotian Shi, Wei Ma, Jian Sun
- **会议：** ICLR 2026
- **官方论文页：** https://openreview.net/forum?id=lYNsZdKn5R
- **剔除原因：** 测试时偏好对齐用于驾驶对抗场景生成，不是模型后训练。

### Faster Activation Functions at the Edge for Post-Training Speedups

- **作者：** Anton Lydike, Jun Bi, Jackson Woodruff
- **会议：** ICML 2026
- **官方论文页：** https://openreview.net/forum?id=u2o6hPE8ik
- **剔除原因：** 端侧推理加速，不是模型后训练。

### GRPO-based Cluster Decision Agent for Unknown-$\boldsymbol{K}$ Multi-view Clustering

- **作者：** Xuqian Xue, Jun Zhang, Qi Cai, Zhizhong Huang, Hongming Shan, Junping Zhang
- **会议：** ICML 2026
- **官方论文页：** https://openreview.net/forum?id=bdUdhftaZz
- **剔除原因：** GRPO 用于多视图聚类。

### LithoGRPO: Fast Inverse Lithography via GRPO Reinforced Flow Matching

- **作者：** Yao Lai, Xuyuan Xiong, Zeyue Xue, Guojin Chen, Jing Wang, Xihui Liu, Rui Zhang, Robert Mullins, Bei Yu, Ping Luo
- **会议：** ICML 2026
- **官方论文页：** https://openreview.net/forum?id=stDqIrBoRO
- **剔除原因：** GRPO 与流匹配用于逆光刻。

### PsumQuant: In-line Post-training Partial Sum Quantizer for Energy Efficient NPU Inference

- **作者：** Sangwoo Hwang, Yeeun Hong, Jaeha Kung
- **会议：** ICML 2026
- **官方论文页：** https://openreview.net/forum?id=6Qbb6IcCVy
- **剔除原因：** NPU 上的训练后部分和量化器。

### SHARP-Q: Spectral Hessian Alignment and Rectification for Post-training Quantization

- **作者：** Menghao Lv, Huiqiong Wang, Li Sun, Mingli Song
- **会议：** ICML 2026
- **官方论文页：** https://openreview.net/forum?id=Xn9Eu2x7Hw
- **剔除原因：** 训练后量化；Alignment 指谱 Hessian 对齐，不是偏好对齐。

### STLA: Spatiotemporal Lookahead Alignment for Post-Training Quantization

- **作者：** Zuqi Zhang, Chenghe Sun, Xiangyi Chu, Wei-Han Yu, Ka-Fai Un, Rui Martins, Pui-In Mak, Jiawei Xu
- **会议：** ICML 2026
- **官方论文页：** https://openreview.net/forum?id=d3RFDLBw01
- **剔除原因：** 训练后量化；Alignment 指 lookahead 舍入对齐。

### Amortized Molecular Optimization via Group Relative Policy Optimization

- **作者：** Muhammad Bin Javaid, Hasham Hussain, Ashima Khanna-Reiter, Berke Kisin, Jonathan Pirnay, Alexander Mitsos, Dominik G Grimm, Martin Grohe
- **会议：** NeurIPS 2026
- **官方论文页：** https://openreview.net/forum?id=BueyrCFsnx
- **剔除原因：** GRPO 用于分子优化搜索，摘要未涉及语言模型或生成式基础模型后训练。

### CRAFT: Counterfactual-to-Interactive Reinforcement Fine-Tuning for Driving Policies

- **作者：** Keyu Chen, Nanfei Ye, Yida Wang, Wenchao Sun, Danqi Zhao, Hao Cheng, Sifa Zheng
- **会议：** NeurIPS 2026
- **官方论文页：** https://openreview.net/forum?id=jvYypWtfPg
- **剔除原因：** 强化微调对象是驾驶策略。

### D$^2$Quant: Accurate Low-bit Post-Training Weight Quantization for LLMs

- **作者：** Xianglong Yan, chengzhu bao, Zhiteng Li, Tianao Zhang, Shaoqiu Zhang, Ruobing Xie, Xingwu Sun, Yulun Zhang
- **会议：** NeurIPS 2026
- **官方论文页：** https://openreview.net/forum?id=Zx81NVkpZ2
- **剔除原因：** 低比特训练后权重量化（PTQ）。

### Learning Process Rewards via Visitation Matching for Efficient RL

- **作者：** Raymond Tsao, Andrew Wagenmaker, Sergey Levine
- **会议：** NeurIPS 2026
- **官方论文页：** https://openreview.net/forum?id=hKhu9x83el
- **剔除原因：** 通用稀疏奖励强化学习，摘要未涉及语言模型。

### MixNLQ: An Effective Post-Training Nonlinear Low-Bit Quantization Method for Large Language Models

- **作者：** Yirong Xiong, Mingrui Cai, Gene Wen, Yuxing Han
- **会议：** NeurIPS 2026
- **官方论文页：** https://openreview.net/forum?id=NAj1slTG0T
- **剔除原因：** 非线性低比特训练后量化。

### Region-Normalized DPO for Medical Image Segmentation

- **作者：** Hamza Kalisch, Constantin Seibold, Jens Kleesiek, Ken Herrmann, Frederic Jonske
- **会议：** NeurIPS 2026
- **官方论文页：** https://openreview.net/forum?id=L4rTdhTV8w
- **剔除原因：** DPO 用于医学图像分割掩码，不是 LLM/基础模型后训练。

### Spike-SFT: Selective Parameter Enhancement and Fusion for Efficient Spiking Neural Networks

- **作者：** Xiubo Liang, Jinxing Han, Yuke Li, Haoqi Zhu, Zhenxing Li, Hongyi Duan, Yu Zhao, Hongzhi Wang
- **会议：** NeurIPS 2026
- **官方论文页：** https://openreview.net/forum?id=3Td9h2rVyH
- **剔除原因：** 对象是脉冲神经网络，SFT 不是大模型监督微调。

### When Policies Cannot Be Retrained: A Unified Closed-Form View of Post-Training Steering in Offline Reinforcement Learning

- **作者：** Elias Hossain, Mohammad J Basher, Ivan Garibay, Ozlem Garibay, Niloofar Yousefi
- **会议：** NeurIPS 2026
- **官方论文页：** https://openreview.net/forum?id=OnU82otbDI
- **剔除原因：** 离线强化学习中冻结策略的事后引导。
