---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>


# 🎓 Educations

<div class="logo-row">
  <div class="logo-row__logo"><img src="{{ '/images/logos/hust.png' | relative_url }}" alt="HUST"></div>
  <div class="logo-row__body">
    <h4>Huazhong University of Science and Technology &mdash; Wuhan, China</h4>
    <p><em>Sep. 2023 - Jun. 2027</em>, Ph.D., School of Computer Science and Technology, advised by Prof. Guohui Li and Prof. Jianjun Li.</p>
    <p>Research areas: Multimodal Large Language Models, Efficient Reasoning, Reinforcement Learning.</p>
  </div>
</div>


# 📑 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">KDD 2026 Oral</div><img src='images/MMSep.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
MMSep: Efficient Multimodal Long-Generation Reasoning via Multimodal Separator Compression \\
**Mingjie Ma**, Yichao Ma, Jiannan Cao, Changhong Li, Chuhang Hong, Zhong Yang, Guohui Li

- 1st empirical investigation of multimodal separator behavior during MLLM decoding.
- Our MMSep framework jointly optimizes prefilling and decoding stages.
- Achieving substantial acceleration with minimal degradation in generation quality on both long-generation and standard benchmarks.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/SLoFo.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
Seeing What Matters: A Training-Free Self-Guided Framework for Multimodal Detail Perception and Reasoning \\
**Mingjie Ma**, Yichao Ma, Zhong Yang, Guohui Li

- An MLLM-intrinsic, robust region selection mechanism
- Visual token reduction to enhance signal-to-noise ratio and reduce overhead
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICASSP 2025</div><img src='images/EL.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
EventLens: Enhancing Visual Commonsense Reasoning by Leveraging Event-Aware Pretraining and Cross-modal Linking \\
**Mingjie Ma**, Zhihuan Yu, Yichao Ma, Guohui Li, Zhong Yang

- Proposing an Event-Aware pretraining stage, enabling MLLMs to understand complex visual scenes and to infer ongoing events and character intentions.
- A fine-grained Linking Mechanism improves cross-modal alignment.
- EventLens ranked 3rd on Global Leaderboard when first submitted.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI 2025</div><img src='images/EDMs.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
Efficient Diffusion Models: A Comprehensive Survey from Principles to Practices \\
Zhiyuan Ma, Yuzhu Zhang, Guoli Jia, Liangliang Zhao, Yichao Ma, **Mingjie Ma**, Gaofeng Liu, Kaiyan Zhang, Ning Ding, Jianjun Li, Bowen Zhou

- 1st comprehensive survey on Efficient Diffusion Models
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2026</div><img src='images/prico.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
PriCo: Prior-Guided Bidirectional Branch Cooperation in ControlNet for Fine-Grained Pose Generation \\
Yichao Ma, Guohui Li, Zhong Yang, **Mingjie Ma** (Rank 2nd in students)

</div>
</div>


# 👨‍💻 Internship Experiences

<div class="logo-row">
  <div class="logo-row__logo"><img src="{{ '/images/BohrDuck.png' | relative_url }}" alt="Bohr Duck AI"></div>
  <div class="logo-row__body">
    <h3>Bohr Duck AI &mdash; Domain LLM application and agent system (Nov. 2024 ~ Mar. 2025)</h3>
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


# 💻 Project Experiences

<div class="logo-row">
  <div class="logo-row__logo"><img src="{{ '/images/NSFC.png' | relative_url }}" alt="NSFC"></div>
  <div class="logo-row__body">
    <h3>NSFC &mdash; Conversational Recommendation with Multimodal Data Fusion and Explainability (Jun. 2022 ~ Jun. 2025)</h3>
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
  <div class="logo-row__logo"><img src="{{ '/images/logos/Vivo.png' | relative_url }}" alt="NSFC"></div>
  <div class="logo-row__body">
    <h3>CSSC &mdash; Multimodal Reasoning Methodology (Aug. 2023 ~ Mar. 2026)</h3>
    <ul>
      <li><strong>Project Goal:</strong> To provide decision support based on large-scale model semantic perception and complex reasoning in multimodal scenarios.</li>
      <li><strong>Project Results:</strong> Delivered EventLens, a framework for MLLM data collection, cleaning, model fine-tuning, and evaluation for multimodal decision support scenarios; compatible with multiple language models and data modalities.</li>
      <li><strong>Personal Work:</strong> Proposing the EventLens model, systematically constructing an Event-Aware Pre-training task and a cross-modal linking module; proposing a domain adapter fine-tuning method based on routing mechanism, and designing a hybrid-adaptor structure, gating mechanism, and KL divergence consistency regularization strategy.
      </li>
    </ul>
  </div>
</div>


<div class="logo-row">
  <div class="logo-row__logo"><img src="{{ '/images/logos/Vivo.png' | relative_url }}" alt="NSFC"></div>
  <div class="logo-row__body">
    <h3>China Ministry of Education Joint Fund &mdash; Brain-Inspired Adaptive Visual Perception (Jul. 2023 - Present)</h3>
    <ul>
      <li><strong>Project Goal:</strong> To research brain-inspired adaptive visual perception technology, including core components such as multi-object detection, survey description generation, and multi-object visual tracking..</li>
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



<!--[//]: #  📝 Latest Blog Posts

[//]: # {% assign en_posts = site.posts | where_exp: "post", "post.path contains '_posts/EN/'" | sort: 'date' | reverse %}
[//]: # {% if en_posts.size > 0 %}
[//]: # {% for post in en_posts limit:2 %}
[//]: # <div class="paper-box" style="margin-bottom: 24px;">
[//]: #   <h3 style="margin: 0 0 6px 0;"><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
[//]: #   <p class="page__meta" style="margin: 0 0 8px 0;">{{ post.date | date: "%B %d, %Y" }}</p>
[//]: #   <div class="archive__item-excerpt">
[//]: #     {{ post.excerpt | strip_html | truncate: 220 }}
[//]: #   </div>
[//]: # </div>
[//]: # {% endfor %}

[//]: # <p style="text-align: right;"><a href="{{ '/blog/' | relative_url }}">View all posts →</a></p>
[//]: # {% else %}
[//]: # <p>No blog posts yet. Check back soon!</p>
[//]: # {% endif %} -->

# 🌱 About Me

Cheerful, optimistic, and thrives on tackling challenging tasks. Passionate about **Sudoku (ShuDu)**, **gaming**, and **football**.

- **Sudoku (ShuDu):**
- **Gaming:** my long-time favorite is *MineCraft* and *Subnautica*.
- **Football:**

<!-- One funny coincidence I cannot help noticing: almost everything I happen to love — Go, StarCraft II, football — has at some point become a research target of DeepMind. That coincidence is part of why I deeply believe in the power of AI. My goal is to push the frontier of AGI through **reinforcement learning, game theory, and multi-agent systems on top of large language models**, on both the research side and real-world applications. -->
