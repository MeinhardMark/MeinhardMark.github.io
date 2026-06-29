---
permalink: /zh/
title: ""
excerpt: ""
author_profile: true
lang: zh
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# 📖 教育经历

<div class="logo-row">
  <div class="logo-row__logo"><img src="{{ '/images/logos/hust.png' | relative_url }}" alt="华中科技大学"></div>
  <div class="logo-row__body">
    <h4>华中科技大学 &mdash; 武汉</h4>
    <p><em>2023 年 6 月 - 2027 年 6 月</em>，博士，计算机科学与技术学院，师从李国徽教授、李剑军教授。</p>
    <p>研究方向：多模态大模型、自然语言处理、高效推理。</p>
  </div>
</div>


# 📝 学术论文

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">KDD 2026 Oral</div><img src='/images/MMSep.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
MMSep: Efficient Multimodal Long-Generation Reasoning via Multimodal Separator Compression \\
**Mingjie Ma**, Yichao Ma, Jiannan Cao, Changhong Li, Chuhang Hong, Zhong Yang, Guohui Li

- 首次实证性调研 MLLMs 解码期间多模态分隔符行为。
- 提出的 MMSep 架构针对预填充与解码两个阶段进行计算效率联合优化。
- 长生成和标准基准测试中，在生成质量的下降幅度极小的情况下，实现了显著的加速。
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='/images/SLoFo.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
Seeing What Matters: A Training-Free Self-Guided Framework for Multimodal Detail Perception and Reasoning \\
**Mingjie Ma**, Yichao Ma, Zhong Yang, Guohui Li

- 利用 MLLM 固有特性实现稳健的关键视觉区域选择，提升细节敏感推理表现。
- 视觉标记减少以提高信噪比并降低开销。
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICASSP 2025</div><img src='/images/EL.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
EventLens: Enhancing Visual Commonsense Reasoning by Leveraging Event-Aware Pretraining and Cross-modal Linking \\
**Mingjie Ma**, Zhihuan Yu, Yichao Ma, Guohui Li, Zhong Yang

- 提出事件感知预训练阶段，使 MLLM 能够理解复杂的视觉场景，并推断正在发生的事件和角色意图。
- 细粒度链接机制可以改善跨模态对齐。
- EventLens 首次提交时在全球排行榜上排名第3。
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI 2025</div><img src='/images/EDMs.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
Efficient Diffusion Models: A Comprehensive Survey from Principles to Practices \\
Zhiyuan Ma, Yuzhu Zhang, Guoli Jia, Liangliang Zhao, Yichao Ma, **Mingjie Ma**, Gaofeng Liu, Kaiyan Zhang, Ning Ding, Jianjun Li, Bowen Zhou

- 首次对扩散模型高效性进行全面调查
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2026</div><img src='/images/prico.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
PriCo: Prior-Guided Bidirectional Branch Cooperation in ControlNet for Fine-Grained Pose Generation \\
Yichao Ma, Guohui Li, Zhong Yang, **Mingjie Ma** (第二学生作者)

- 提出无需训练的 PriCo 框架，实现了结构一致性与细粒度动作保真的人体图像生成
</div>
</div>



# 💻 实习经历

<div class="logo-row">
  <div class="logo-row__logo"><img src="{{ '/images/BohrDuck.png' | relative_url }}" alt="Bohr Duck AI"></div>
  <div class="logo-row__body">
    <h3>上海波尔鸭人工智能科技有限公司 &mdash; 垂域模型与智能体系统 (2024 年 11 月 ~ 2025 年 3 月)</h3>
    <ul>
      <li><strong>项目目标：</strong> 针对外语教育咨询场景的领域，微调垂域大模型，构建咨询辅导智能体。</li>
      <li><strong>项目结果：</strong> 建立了支持持续迭代的数据管理管道和包含 20,000 个多轮对话的高质量数据集；实现了跨多个主流大模型的微调和评估；部署了基于 RAG 的智能体系统，集成了工具调用、用户画像和业务 API，实现产品完整端到端周期。</li>
      <li><strong>个人工作：</strong> 
        <ul>
          <li><strong>数据构建：</strong> 构建、清理和质量控制 2 万个多轮对话样本（每个样本 100-600 轮）.</li>
          <li><strong>选型与微调：</strong> 对 直接使用、快速优化和监督微调 三种情况下的多个模型进行基准测试，以确定最佳解决方案。</li>
          <li><strong>智能体开发：</strong> 设计了智能体工作流架构，基于 LlamaIndex 实现了 RAG、工具调用、结构化用户画像和业务系统集成。</li>
          <li><strong>协作与运营：</strong> 与合作方一线教师合作，持续反馈分析、性能评估和迭代部署；编写文档并构建长期数据清洗和模型更新的流程。</li>
        </ul>
      </li>
    </ul>
  </div>
</div>

# 💻 项目经历

<div class="logo-row">
  <div class="logo-row__logo"><img src="{{ '/images/NSFC.png' | relative_url }}" alt="NSFC"></div>
  <div class="logo-row__body">
    <h3>国家自然科学基金 &mdash; 融合多模态数据的对话式推荐及其可解释性研究 （2022 年 6 月 ~ 2025 年 6 月）</h3>
    <ul>
      <li><strong>项目目标：</strong> 减少多模态对话式推荐中语义理解不确定性，理解用户细粒度意图，构建可解释的多模态对话式推荐系统。</li>
      <li><strong>项目结果：</strong> 形成了融合多模态数据的对话式推荐原型系统，在统一模态的对话语义嵌入模型、多方面细粒度意图感知与平衡框架、考虑知识图谱高异配性的智能推荐策略以及基于注意力的可解释路径推理等方面取得理论突破。</li>
      <li><strong>个人工作：</strong> 
        <ul>
          <li>主导了细粒度语义对齐与统一语义空间的代码开发与实验。</li>
          <li>提交了跨模态特征对齐与融合框架 <strong>UniTranSeR</strong>；开发了细粒度意图推理模块 FAIR。</li>
          <li>完成了模型的实现、训练，参与实现自动及人工评估。</li>
        </ul>
      </li>
    </ul>
  </div>
</div>

<div class="logo-row">
  <div class="logo-row__logo"><img src="{{ '/images/CSSC.png' | relative_url }}" alt="CSSC"></div>
  <div class="logo-row__body">
    <h3>中船七〇九所开放基金 &mdash; 多模态场景下的大语言模型推理方法研究 （2023 年 8 月 ~ 2026 年 3 月）</h3>
    <ul>
      <li><strong>项目目标：</strong> 多模态场景下，基于大模型语义感知和复杂推理的辅助决策。</li>
      <li><strong>项目结果：</strong> 交付了面向多模态辅助决策场景的 MLLM 数据收集、清洗、模型微调与评估框架；可兼容多种语言模型和数据模态</li>
      <li><strong>个人工作：</strong> 提出 EventLens 模型，系统构建了事件感知预训练任务和跨模态语义链接模块；提出基于随机路由的域适配器微调方法，设计多适配器混合结构、门控机制与KL散度一致性正则化策略。</li>
    </ul>
  </div>
</div>


<div class="logo-row">
  <div class="logo-row__logo"><img src="{{ '/images/jyb.png' | relative_url }}" alt="JYB"></div>
  <div class="logo-row__body">
    <h3>中国教育部联合基金 &mdash; 脑启发的自适应视觉感知技术 （2023 年 7 月 ~ 至今）</h3>
    <ul>
      <li><strong>项目目标：</strong> 研究基于脑启发的自适应视觉感知技术，包括多目标检测、勘察描述生成与多目标视觉追踪等核心环节</li>
      <li><strong>项目结果：</strong> 推进中，已完成多尺度多目标检测模型与小样本目标检测模型，已完成图像事件描述模型及多模态预训练方案;正在开展原型系统集成与性能评测</li>
      <li><strong>个人工作：</strong> 设计了模拟大脑皮层多感受野特性的多分支块网络结构，实现多分支路由选择和多尺度感受野覆盖；设计动态神经通路模型，通过密集跨层连接与路由函数动态激活以灵活适配下游任务。</li>
    </ul>
  </div>
</div>


# 🏆 竞赛经历

<div class="logo-row">
  <div class="logo-row__logo"><img src="{{ '/images/logos/com-logo.svg' | relative_url }}" alt="HuaweiCup"></div>
  <div class="logo-row__body">
    <h3>华为杯 &mdash; 中国研究生人工智能创新大赛 (2024 年 11 月 ~ 2025 年 3 月)</h3>
    <ul>
      <li><strong>赛题目标：</strong> 企业赛题 — 细粒度猫/狗识别要求模型不超过 50 MB ，实现宠物猫/狗的品种分类和个体识别。</li>
      <li><strong>竞赛结果：</strong> 提交大小约 40 MB 的 PetXNet 模型；通过构建数据集、数据增强、困难样本挖掘、多粒度特征提取算法和分阶段式训练策略，在品种分类和个体识别准确率分别达到 <strong>92.65%</strong> 和 <strong>93.64%</strong>；获得<strong>全国三等奖</strong>。</li>
      <li><strong>个人工作：</strong> 队长；负责项目整体规划、进度把控、技术调研；确定模型选型与技术路线调整；部分代码实施；参与全部代码评审；项目文档撰写；决赛展示汇报。</li>
    </ul>
  </div>
</div>

# 🌱 关于我

性格开朗乐观，行动力强，喜欢迎接有挑战性的任务。生活中热爱**数独**、**电子游戏**和**足球**。

- **数独：**长期喜欢逻辑推理类谜题，享受通过分析、排除与搜索找到解的过程
- **游戏：**热爱**我的世界**和**深海迷航**，着迷于探索、建造、资源管理。
- **足球：**长期参与球类运动，最喜欢的是足球，曾加入学院足球队，最喜欢的球员是禁区之王范尼斯特鲁伊（Van Nistelrooij）。

我喜欢的这些事物都与人工智能高度相关：逻辑推理；开放环境智能体和强化学习；多智能体协作、对抗博弈和实时决策。正因为这些兴趣，我逐渐意识到 AI 不只是技术工具，更是一种理解复杂世界和创造智能行为的方式。未来我希望围绕**大模型、强化学习与多智能体系统**，不断探索 AGI 的前沿和更多可能性。
