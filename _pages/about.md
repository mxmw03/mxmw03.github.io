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

I am Mingwei Xu, an M.S. student in Electrical and Computer Engineering at the University of Washington. Before joining UW, I received my B.S. in Automation from Zhejiang University of Technology.

My research focuses on large language model post-training, reinforcement learning, multimodal large models, and agent systems. I am especially interested in improving reasoning, alignment, and tool-augmented decision making in complex real-world environments. I am currently working on agentic systems for the OfficeQA benchmark, with an emphasis on document understanding, retrieval-augmented reasoning, and enterprise-facing workflow automation.


# 🔥 News
- *2026.05*: [ICML'26] POPO is accepted by ICML 2026 Workshop DEMO.


# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"><a href="https://arxiv.org/abs/2605.06650">arXiv:2605.06650</a> · <a href="https://github.com/momo1443/colm2026-POPO">Code</a></div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Beyond Negative Rollouts: Positive-Only Policy Optimization with Implicit Negative Gradients**](https://arxiv.org/abs/2605.06650)

**Mingwei Xu**, Hao Fang \| <a href="https://github.com/momo1443/colm2026-POPO"><i class="fab fa-fw fa-github" aria-hidden="true"></i> GitHub</a>


# 🎖 Honors and Awards
- *2025* Meritorious Winner, Mathematical Contest in Modeling / Interdisciplinary Contest in Modeling (MCM/ICM)
- *2025* Outstanding Graduate, Zhejiang University of Technology
- *2021 - 2025* Zhejiang Provincial Government Scholarship, First-Class Outstanding Student Scholarship, and Innovation and Entrepreneurship Scholarship

# 📖 Educations
- *2025.09 - Present*, University of Washington, M.S. in Electrical and Computer Engineering, College of Electrical and Computer Engineering
- *2021.09 - 2025.06*, Zhejiang University of Technology, B.S. in Automation, College of Information Engineering

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2025.11 - 2026.05*, Paul G. Allen Center for Computer Science & Engineering, University of Washington, LLM Training Researcher
- *2024.07 - 2024.09*, Hangzhou Denghong Technology Co., Ltd., Automation Software Engineer

# 🚀 Selected Projects
- **FinTech Agentic QA** \| [GitHub](https://github.com/mxmw03/fintech-agentic-qa): Designed single-agent and multi-agent financial QA systems with an orchestrator that coordinates market, fundamentals, and sentiment agents. Integrated yfinance, local SQLite databases, Streamlit, and LLM-as-judge evaluation.
- **OfficeQA Agent System**: Built agentic workflows for enterprise document parsing, retrieval-augmented generation, and reasoning over long documents, tables, and tool-use scenarios.

# 🛠 Skills
- **Languages**: Python, C++, C, Java
- **ML / AI**: PyTorch, Hugging Face, TRL, verl, LoRA, DeepSpeed, FSDP, vLLM, LangChain, agent systems
- **Tools / Platforms**: Git, Linux, Docker, MATLAB, STM32, Raspberry Pi, Infineon TC264, embedded systems
