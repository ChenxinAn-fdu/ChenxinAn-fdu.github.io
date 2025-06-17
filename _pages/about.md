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



I am a second-year Ph.D. candidate at HKU, supervised by [Lingpeng Kong](https://ikekonglp.github.io/). I obtained my bachelor's and master's degrees from the Department of Computer Science at Fudan University, advised by Prof. [Xipeng Qiu](https://xpqiu.github.io/en.html). My current research focuses on building effective long-context LLMs, including:
(1) Fully utilizing the training context.
(2) Efficient inference on over 1 million tokens.
(3) Developing better evaluation tasks for current long-context LLMs.

<aside style="background-color: #f5f5f5; padding: 1em; border-radius: 8px;">
  <p>
    We are thrilled to unveil our latest breakthroughs, <code>POLARIS-7B-Preview</code> and <code>POLARIS-4B-Preview</code>, which mark a new frontier in open‐recipe reasoning models developed using academic‐level resources. 
    <br>
    <code>POLARIS-4B-Preview</code> is fine-tuned from <code>Qwen3-4B</code> and <code>POLARIS-7B-Preview</code> is fine-tuned from <code>Deepseek-R1-Distill-Qwen-7B</code>.
    <br>
    Our 4B model achieves an impressive <strong>81.2% Pass@1 accuracy on AIME24</strong> and <strong>79.4% Pass@1 accuracy on AIME25</strong>, outperforming state-of-the-art commercial models like <code>Claude-4-Opus</code>, <code>Grok-3-Beta</code>, and <code>o3-mini-high(2025/01/31)</code> via scaling reinforcement learning on open-source data. On AIME25, POLARIS astonishingly achieves comparable performance to <code>Qwen3-235B-A22B</code> while using less than <strong>2%</strong> of its parameters and can be deployed on consumer-grade GPUs.
  </p>
  <p>
    To foster progress in scaling RL on advanced reasoning models, we are open-sourcing our dataset, code, and training details for the research community.
  </p>
  <p>
    👨‍💻 <a href="https://github.com/agentica-project/deepscaler">Github</a> | 🤗 <a href="https://huggingface.co/POLARIS-HKU/Polaris-4B-Preview">HF Model</a> | 🤗 <a href="https://huggingface.co/datasets/agentica-org/DeepScaleR-Preview-Dataset">HF Dataset</a> | 📖 <a href="comming soon">paper</a> | 🔎 <a href="https://github.com/HKUNLP/POLARIS">Evaluation results</a>
  </p>
</aside>

{% include_relative includes/pubs.md %}

{% include_relative includes/honors.md %}
