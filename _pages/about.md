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
    <p><em>Sep. 2023 - Jun. 2027</em>, Ph.D., School of Computer Science and Technology, advised by Prof. Guohui Li.</p>
    <p>Research areas: Multimodal Large Language Models, Efficient Reasoning, Reinforcement Learning.</p>
  </div>
</div>


# 📑 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGKDD 2026 Oral</div><img src='images/fs.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
MMSep: Efficient Multimodal Long-Generation Reasoning via Multimodal Separator Compression \\
**Mingjie Ma**, Yichao Ma, Jiannan Cao, Changhong Li, Chuhang Hong, Zhong Yang, Guohui Li

- paper intro line 1
- paper intro line 2
- paper intro line 3
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/fs.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
Seeing What Matters: A Training-Free Self-Guided Framework for Multimodal Detail Perception and Reasoning \\
**Mingjie Ma**, Yichao Ma, Zhong Yang, Guohui Li

- paper intro line 1
- paper intro line 2
- paper intro line 3
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICASSP 2025</div><img src='images/fs.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
EventLens: Enhancing Visual Commonsense Reasoning by Leveraging Event-Aware Pretraining and Cross-modal Linking \\
**Mingjie Ma**, Zhihuan Yu, Yichao Ma, Guohui Li, Zhong Yang

- paper intro line 1
- paper intro line 2
- paper intro line 3
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI 2025</div><img src='images/fs.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
Efficient Diffusion Models: A Comprehensive Survey from Principles to Practices \\
Zhiyuan Ma, Yuzhu Zhang, Guoli Jia, Liangliang Zhao, Yichao Ma, **Mingjie Ma**, Gaofeng Liu, Kaiyan Zhang, Ning Ding, Jianjun Li, Bowen Zhou

- paper intro line 1
- paper intro line 2
- paper intro line 3
</div>
</div>

# 👨‍💻 Internship Experiences

<div class="logo-row">
  <div class="logo-row__logo"><img src="{{ '/images/logos/ByteDance.png' | relative_url }}" alt="ByteDance Seed"></div>
  <div class="logo-row__body">
    <h3>ByteDance Seed &mdash; LLM Post-training Based on Games (Jun. 2025 ~ Oct. 2025)</h3>
    <ul>
      <li><strong>Project Goal:</strong> integrate game-theoretic problems into LLM post-training to enhance LLM capabilities.</li>
      <li><strong>Project Results:</strong> delivered game-oriented LLM evaluation &amp; training frameworks; trained an LLM Texas Hold'em AI that outperformed GPT-o3, Grok-4, etc., with improved instruction following.</li>
      <li><strong>Personal Work:</strong> proposed a novel algorithm with an "LLM Reflection" mechanism that outperforms traditional RL methods in game scenarios; built the game-oriented LLM evaluation framework (integrated into the team's system) and a training framework based on Verl.</li>
    </ul>
  </div>
</div>

<div class="logo-row">
  <div class="logo-row__logo"><img src="{{ '/images/logos/Vivo.png' | relative_url }}" alt="vivo"></div>
  <div class="logo-row__body">
    <h3>vivo &mdash; SD Model Fine-Tuning via Reinforcement Learning (Feb. 2025 ~ Apr. 2025)</h3>
    <ul>
      <li><strong>Project Goal:</strong> fine-tune Stable Diffusion with reinforcement learning to improve generation quality and prompt alignment.</li>
      <li><strong>Project Results:</strong> early results show clear improvements in image quality, textual relevance and human preference alignment; ongoing work on reward design and distributed training scale-up.</li>
      <li><strong>Personal Work:</strong> designed a composite reward model combining aesthetics, textual relevance, diversity and human feedback; tuned the RL training pipeline for SD.</li>
    </ul>
  </div>
</div>

### Fen AI &mdash; Texas Hold'em AI (Sep. 2023 ~ Jan. 2024)

- **Project Goal:** create an AI that matches the performance of Pluribus, a renowned Texas Hold'em AI.
- **Project Results:** the final AI reached the level of professional players in two-player Texas Hold'em; the multi-player version is still under development.
- **Personal Work:** contributed to key algorithms (MCCFR, MCCFR pruning), built foundational components such as strategy storage and result visualization, and handled algorithm parameter tuning and testing.

<div class="logo-row">
  <div class="logo-row__logo"><img src="{{ '/images/logos/ByteDance.png' | relative_url }}" alt="ByteDance Nuverse"></div>
  <div class="logo-row__body">
    <h3>ByteDance Nuverse &mdash; Reinforcement Learning Internship (Jul. 2021 ~ Mar. 2022)</h3>
    <ul>
      <li><strong>Project Goal:</strong> design multi-style AI companion NPCs for the game <em>One Piece: Burning Blood</em>.</li>
      <li><strong>Project Results:</strong> added a style evolution module on top of the previous AI training framework, leading to an 80–120% improvement in key indicators and clear style differentiation in play; several AIs reached deployable quality.</li>
      <li><strong>Personal Work:</strong> served as the main executor of the project. Under my advisor's guidance, I implemented the multi-style AI algorithm and explored the integration of human preferences into reinforcement learning, which culminated in a research paper summarizing the findings and potential applications.</li>
    </ul>
  </div>
</div>

### China Resources Group &mdash; Land Auction (Feb. 2021 ~ Jun. 2021)

- **Project Goal:** design a bidding strategy for China Resources Group in the "first/last" land auction.
- **Project Results:** the strategy was approved by China Resources Land Group and deployed in dozens of land auctions (each over $100M). The algorithm outperformed the group's expert approach, boosting bid accuracy 3–4× and winning probability by ~5%, and was adopted as their standard land auction strategy.
- **Personal Work:** built a simulator of the "first/last" land auction from historical data and applied the Fictitious Play algorithm to develop strategies. Participated in three real auctions involving a total bidding scale of $1B, and refined the model based on real-world outcomes.

# 📝 Latest Blog Posts

{% assign en_posts = site.posts | where_exp: "post", "post.path contains '_posts/EN/'" | sort: 'date' | reverse %}
{% if en_posts.size > 0 %}
{% for post in en_posts limit:2 %}
<div class="paper-box" style="margin-bottom: 24px;">
  <h3 style="margin: 0 0 6px 0;"><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
  <p class="page__meta" style="margin: 0 0 8px 0;">{{ post.date | date: "%B %d, %Y" }}</p>
  <div class="archive__item-excerpt">
    {{ post.excerpt | strip_html | truncate: 220 }}
  </div>
</div>
{% endfor %}

<p style="text-align: right;"><a href="{{ '/blog/' | relative_url }}">View all posts →</a></p>
{% else %}
<p>No blog posts yet. Check back soon!</p>
{% endif %}

# 🌱 About Me

Cheerful, optimistic, and thrives on tackling challenging tasks. Passionate about **Go (WeiQi)**, **gaming**, and **football**.

- **Go (WeiQi):** roughly 7 dan amateur on Fox Weiqi (野狐围棋).
- **Gaming:** my long-time favorite is *StarCraft II* — I once reached **Master league on the China server**.
- **Football:** lifelong fan of **Borussia Dortmund**, with **Marco Reus** being my favorite player.

One funny coincidence I cannot help noticing: almost everything I happen to love — Go, StarCraft II, football — has at some point become a research target of DeepMind. That coincidence is part of why I deeply believe in the power of AI. My goal is to push the frontier of AGI through **reinforcement learning, game theory, and multi-agent systems on top of large language models**, on both the research side and real-world applications.
