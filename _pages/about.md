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
Hi, I'm Zhipeng Yang (杨致芃). I received my Bachelor's degree in Robot Engineering from Southeast University, China. My research interests lie in Explainable and Trustworthy AI, with a particular focus on the Mechanistic Interpretability of Large Language Models (LLMs). I am especially interested in the following directions:
- **Planning and Reasoning in LLMs**: As LLMs are increasingly used for decision-making in real-world agents, it is crucial to uncover their underlying reasoning mechanisms. Understanding how they plan and decompose tasks can help ensure the safety, transparency, and accountability of their decisions. My recent works include: *LLM-based Robot Task Planning* ([arXiv](https://arxiv.org/abs/2405.15646)) and *Internal Chain-of-Thought in LLMs* (EMNLP 2025, [arXiv](https://arxiv.org/abs/2505.14530)).
- **Safety and Behavioral Alignment of LLMs**: Despite their impressive knowledge capabilities, LLMs remain vulnerable to generating harmful content, misinformation, or inappropriate refusals. Currently, I am working on a project addressing the phenomenon of Over-Refusal, where models reject benign prompts due to excessive safety alignment.

I entered the field of Interpretability in 2024 Summer, motivated by a growing realization that the rapid development of deep learning has often been driven in a blind manner, with progress measured primarily by input–output performance metrics while the models themselves remain black boxes. My research is guided by the conviction that advancing interpretability is not only critical for the trustworthiness and safety of AI systems, but also indispensable for restoring the scientific rigor and transparency that should underlie the future of machine learning.


<span class='anchor' id='-news'></span>
# 🔥 News
<font color=red>I am currently seeking PhD or RA positions. If you are interested, please feel free to contact me via email: <yangzp135@outlook.com>.</font>



<span class='anchor' id='-publications'></span>
# 📝 Publications
\* indicates equal contribution. 
- **Yang, Z.**, Li, J., Xia, S., & Hu, X.. Internal Chain-of-Thought: Empirical Evidence for Layer‑wise Subtask Scheduling in LLMs. In *Proceedings of the 2025 Conference on Empirical Methods in Natural Language Processing (EMNLP).* [arXiv](https://arxiv.org/abs/2505.14530) [code](https://github.com/yzp11/Internal-Chain-of-Thought)
- Wang, R.\*, **Yang, Z.\***, Zhao, Z., Tong, X., Hong, Z., & Qian, K.. LLM-based Robot Task Planning with Exceptional Handling for General Purpose Service Robots. In *2024 43rd Chinese Control Conference (CCC).* (**Oral**) [arXiv](https://arxiv.org/abs/2405.15646)
- **Yang, Z.\***, Wang, R.\*, Tan, Y., & Xie, L.. MALT: Multi-scale Action Learning Transformer for Online Action Detection. In *2024 International Joint Conference on Neural Networks (IJCNN).* (**Oral**) [arXiv](https://arxiv.org/abs/2405.20892)


<span class='anchor' id='-educations'></span>
# 📖 Educations
- *2021.08 - 2025.06*, Bachelor in Robot Engineering, Southeast University.


<span class='anchor' id='-internship'></span>
# 💻 Internship
- *2024.10 - 2025.5*, HKUST GZ, supervised by Prof. Xuming Hu.
- *2025.6 - now*, MBZUAI, supervised by Prof. Lijie Hu.

