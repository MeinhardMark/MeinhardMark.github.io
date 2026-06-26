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

- 第一个实证性调研 MLLMs 解码期间多模态分隔符行为。
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
          <li><strong>智能体开发：</strong> 设计了智能体工作流架构，实现了 RAG、工具调用、结构化用户画像和业务系统集成。</li>
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
      <li><strong>Project Goal:</strong> Explainable multimodal conversational recommendation systems by addressing semantic alignment, user intent understanding, multimodal knowledge representation, and reasoning over heterogeneous data sources (e.g., text and images).</li>
      <li><strong>Project Results:</strong> Developed the UniTranSeR framework and FAIR intent reasoner for multimodal conversational recommendation, significantly enhancing cross-modal semantic understanding and fine-grained user intent reasoning</li>
      <li><strong>Personal Work:</strong> 
        <ul>
          <li>Led the research on fine-grained semantic alignment and unified semantic modeling.</li>
          <li>Delivered <strong>UniTranSeR</strong>, a cross-modal feature alignment and fusion framework that projects heterogeneous multimodal representations into a unified semantic space. Developed a Feature Alignment and Intent Reasoning (FAIR) module for cross-modal entity alignment and fine-grained key-value reasoning.</li>
          <li>Conducted model implementation, training, and evaluations.</li>
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
    <h3>中国教育部联合基金 &mdash; 脑启发的xxx自适应视觉感知技术 （2023 年 7 月 ~ 至今）</h3>
    <ul>
      <li><strong>Project Goal:</strong> .</li>
      <li><strong>Project Results:</strong> </li>
      <li><strong>Personal Work:</strong> 
        <ul>
          <li>line 1.</li>
          <li>line 2.</li>
          <li>line 3.</li>
        </ul>
      </li>
    </ul>
  </div>
</div>



# 🏆 Competetion Experiences

<div class="logo-row">
  <div class="logo-row__logo"><img src="{{ '/images/logos/com-logo.svg' | relative_url }}" alt="HuaweiCup"></div>
  <div class="logo-row__body">
    <h3>Huawei Cup &mdash; China Graduate AI Innovation Competition (Nov. 2024 ~ Mar. 2025)</h3>
    <ul>
      <li><strong>Project Goal:</strong> domain LLM and agent system for foreign language education consultation scenarios, improving dialogue quality through data construction, model fine-tuning, and agent architecture design.</li>
      <li><strong>Project Results:</strong> Established a supporting data management pipeline for continuous iteration and a high-quality dataset of 20,000 multi-turn dialogues; Delivered a model fine-tuning &amp; evaluation across multiple mainstream LLMs (Qwen, Doubao, GPT-4o); Deployed a RAG-based Agent system integrating tool calling, user profiling, and business APIs, achieving a full end-to-end cycle from demo to production.</li>
      <li><strong>Personal Work:</strong> 
        <ul>
          <li><strong>Data Construction:</strong> Built, cleaned, and quality-controlled 20,000 multi-turn dialogue samples (100–600 turns each).</li>
          <li><strong>Model Selection &amp; Fine-tuning:</strong> Benchmarked multiple models across three approaches (direct use, prompt optimization, and supervised fine-tuning) to determine the optimal solution.</li>
          <li><strong>Agent Development:</strong> Designed the Agent Workflow architecture, implementing retrieval-augmented generation, tool calling, structured user profiling, and business system integration.</li>
          <li><strong>Collaboration &amp; Operations:</strong> Partnered with frontline consulting teams on requirements analysis, performance evaluation, and iterative deployment; produced documentation and built a pipeline for continuous data collection and model updates</li>
        </ul>
      </li>
    </ul>
  </div>
</div>


# 📝 最新博客

{% assign zh_posts = site.posts | where_exp: "post", "post.path contains '_posts/CN/'" | sort: 'date' | reverse %}
{% if zh_posts.size > 0 %}
{% for post in zh_posts limit:2 %}
<div class="paper-box" style="margin-bottom: 24px;">
  <h3 style="margin: 0 0 6px 0;"><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
  <p class="page__meta" style="margin: 0 0 8px 0;">{{ post.date | date: "%Y 年 %m 月 %d 日" }}</p>
  <div class="archive__item-excerpt">
    {{ post.excerpt | strip_html | truncate: 220 }}
  </div>
</div>
{% endfor %}

<p style="text-align: right;"><a href="{{ '/zh/blog/' | relative_url }}">查看全部博客 →</a></p>
{% else %}
<p>暂无博客内容，敬请期待。</p>
{% endif %}

# 🌱 关于我

性格开朗乐观，喜欢迎接有挑战性的任务。生活中热爱**围棋**、**电子游戏**和**足球**。

- **围棋：**野狐围棋业余 7 段水平。
- **游戏：**长期挚爱《星际争霸 II》，曾经达到**国服（中国）大师段位**。
- **足球：**铁杆**多特蒙德**球迷，最喜欢的球员是**马尔科·罗伊斯（Marco Reus）**。

人生的一个巧合是：我喜欢的几乎所有东西——围棋、星际争霸、足球——都先后成为了 DeepMind 的研究对象。这个巧合也是我深信 AI 力量的原因之一。我的目标是基于大语言模型，通过 **强化学习、博弈论与多智能体系统** 的结合，在研究与产业落地两个维度推进 AGI 的前沿。
