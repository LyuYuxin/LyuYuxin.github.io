---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
-----
**我曾经是一位自动驾驶感知算法工程师，就职于某头部自动驾驶重卡公司,年薪超过45万，目前正在积极寻求3D感知/BEV方向相关的读博/研究助理/实习交流的机会。**

我在2023年6月硕士毕业于东南大学软件学院，导师为路小波教授。读研期间，我曾连续两年获得研究生学业奖学金，并被评为“东南大学三好研究生”。我曾出于兴趣参加过华为软件精英挑战赛，solo取得江山赛区二等奖。此前，我于2020年毕业于电子科技大学计算机学院。

已经有一份高薪工作，为什么又想做研究？
-----
几方面原因：
1. *对科研工作的向往。*由于导师培养方式等原因，我从研一上完课的暑假开始，长期呆在公司里（事实上，我几乎从未在实验室环境待过，受到的科研指导较少），但**我依然希望从事一份更能发挥创造性 or 更加“研究”而非“工程”的工作，希望可以关注最新方案，解决前沿问题**。（算法工程师不够创造性吗？算法工程师需要一定的创造性，但要做的事情太多，不够聚焦）。
2. *个人逻辑与公司逻辑的冲突。*公司面临市场竞争，生存逻辑决定了它一定是产品导向而非技术导向的，由于软硬件的成本资源限制，工业界多采用稳定、可靠的技术方案。而作为技术方案的构建者/实现者/螺丝钉，一位算法工程师的主要注意力集中在经过测试的线上方案上，解决该方案落地时存在的各种问题。然而，**我个人其实对解决某一象子领域的问题，而非某一具象单一业务功能问题这件事情更感兴趣，换句话说，我更希望能对某一领域的基础算法做出提升，而非增量式工程调优。**
3. *在公司里技术积累需要额外精力。*随着自驾量产业务的爆发，我认为大部分算法工程师的工作内容事实上会变成体力劳动，如不少公司存在专门的issue团队等。而**技术积累通常需要在干完活后完成，时间上不允许有更多投入，因此我希望专门花时间进行深造**。

我的研究兴趣是什么？
-----
包括但不限于：Representation learning、3D Perception(including camera-based/Lidar-based or fusion)、Knowledge distillation，etc. 
之所以列举这些，只是因为我有一定的前置知识，有相关经验，对于研究领域我是开放的，**有用、有价值**的研究我都愿意做，看具体情况。

做研究这件事，我有哪些基础？我有哪些相关科研及工程项目经历？
-----
### 我对计算机视觉的基础任务（如分类、检测、分割等）有一定认识。曾有多种独立项目经验及科研经历：
- 在研二暑假，基于个人兴趣，我进入某头部自动驾驶重卡公司进行实习，开展**基于Lidar的3D感知**相关工作，与当时的mentor Chunming Wang一起设计了一种基于时序数据前融合及cross-frame axial-attention的PointPillars改进方案，并获得了一定的性能提升。
  硕士毕业后，我以**special offer**正式加入该公司，在车道线组从事自动驾驶量产相关工作，包括Event Mining、道路场景建模等。在leader Chao Wang的带领下，**独立负责**高速护栏建模功能，经过不断试错，最终采用了一种基于前视双目的深度估计方案，并**一人完成了从场景定义、标注guideline设计、样本采集、模型构建、模型训练、模型测试、推理时转化、后处理等上下游全链路工作。并在实车路测取得了预期效果。**

- 进入自动驾驶行业之前，从研一暑假开始，我在导师合作企业南京恩博科技有限公司独立开展“野生动物识别”的项目工作，基于此项目完成了毕业论文《基于深度学习的野生动物识别算法研究》,并顺手发表EI会议论文一篇。通过对相关领域的文献调研，结合数据集实际情况，我基于YOLOX设计了一种兼具速度和性能的单目识别方案。相比于基准方法，该方案包括三点创新：
1. 基于RepVGG、RepLKNet等方法引入的结构重参数技术，我**手工设计**了一个浅而宽的特征提取主干BroadNet，相比于baseline网络DarkNet，该网络有效感受野更大，并大幅减少了推理时参数量、计算量，在公司的野生动物数据集上表现出优异性能。
2. 对空间-通道混合注意力CBAM进行了结构上的改进，并将其引入到特征融合网络FPN中，进一步提升性能。
3. 对模型整体网络进行轻量化，并设计了一种注意力引导的混合蒸馏方法，以降低轻量化过程中的性能损失。

*总体来说，我享受按自己的思路手工构建一个神经网络，并通过实验证明它有效的过程。由于长期一人做项目，我具备较强的快速学习能力，可以基本无障碍进行英文文献调研及复现，有独立解决大部分工程问题的能力。我对深度学习环境配置很熟悉，已经掌握了很多常用开发工具，包括但不限于：linux、k8s、docker、git、ssh、conda、python、pdb、pytorch、opencv、numpy、tensorboard等。*

我想从读博做研究这件事中得到什么？
-----
1. 我的最终目标是通过4-5年的时间，成为一位感知（子）领域的技术专家，既拥有前沿的学术视野及研究品味，也有解决实际问题的能力。
2. **做一些对业界有价值的研究。**我看好自动驾驶行业的长期发展，希望自己能够给为这个行业做出一些贡献，有一些影响力。我对自己日后工作的期望：**简单优雅的，而非晦涩难懂的**，**有实用价值的，而非空中楼阁的**。
3. **在一个科研氛围良好的课题组，发表顶级论文。**由于研究生读了专硕，导师让我长期呆在公司实习，写论文方面投入精力不多，也未受过太多科研指导。除了学位论文及研三随手写的一篇EI，用来满足专硕的毕业条件外，没有顶会顶刊的投稿、rebuttal、录用经历。所以**我希望到相关方向的前沿课题组做研究，初期形式上可以是实习/研究助理，目的是培养自己的科研嗅觉及写作能力，后期希望读博**。
