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

<aside>
We are thrilled to unveil our latest breakthroughs, **`POLARIS-7B-Preview`** and **`POLARIS-4B-Preview`**, which mark a new frontier in open-recipe reasoning models developed using academic-level resources.  **`POLARIS-4B-Preview`** is fine-tuned from **`Qwen3-4B`** and **`POLARIS-7B-Preview`** is fine-tuned from **`Deepseek-R1-Distill-Qwen-7B`** **.**  Our 4B model achieves an impressive **81.2%** Pass@1 ****accuracy on AIME24 and **79.4%** Pass@1 ****accuracy on AIME25, outperforming state-of-the-art commercial models like **`Claude-4-Opus`**, **`Grok-3-Beta`**, and **`o3-mini-high(2025/01/31)`** via scaling reinforcement learning on open-source data. On AIME25, POLARIS astonishingly achieves comparable performance to **`Qwen3-235B-A22B`**  while using less than **2%** of its parameters and can be deployed on consumer-grade GPUs.

To foster progress in scaling RL on advanced reasoning models, we are open-sourcing our dataset, code, and training details for the research community.

👨‍💻 [Github](https://github.com/agentica-project/deepscaler), 🤗 [HF Model](https://huggingface.co/POLARIS-HKU/Polaris-4B-Preview), 🤗 [HF Dataset](https://huggingface.co/datasets/agentica-org/DeepScaleR-Preview-Dataset), 📖 [paper](comming soon), 🔎 [Evaluation results](https://github.com/HKUNLP/POLARIS)

</aside>

{% include_relative includes/pubs.md %}

{% include_relative includes/honors.md %}
