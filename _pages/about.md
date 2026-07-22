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

Welcome to my homepage! 👋🏻 I am Mingwei Xu, an M.S. student in Electrical and Computer Engineering at the University of Washington.

Before joining UW, I received my B.S. in Automation from Zhejiang University of Technology, where I was advised by [Prof. Fanghong Guo](https://scholar.google.com/citations?user=M-dHZGIAAAAJ&hl=en) and worked on automatic control and hardware design. After graduation, I was advised by [Prof. Yina Wei](https://scholar.google.com/citations?user=o6NB0FwAAAAJ&hl=en) at Zhejiang Lab, contributing to research on EEG signal analysis and Brain-Inspired Intelligence.

My research focuses on **large language model post-training**, **reinforcement learning**, **multimodal large models**, and **agent systems**. I am especially interested in improving reasoning, alignment, and tool-augmented decision making in complex real-world environments. 

<span style="color: red;">I am actively seeking 27 Fall PhD opportunities!</span>


# 🔥 News
- *2026.05* 🎉: [ICML 26] *Improve Reasoning Ability by Reinforcing Only from Positive Rollouts （POPO）* is accepted by **ICML 2026 Workshop DEMO**.
- *2025.12* 🎉: [JCR Q2] *Task-Dependent Cortical Oscillatory Dynamics in Functional Constipation* is accepted by **Sensors**.

# 📖 Educations
- *2025.09 - Present*, University of Washington, M.S. in Electrical and Computer Engineering, College of Electrical and Computer Engineering
- *2021.09 - 2025.06*, Zhejiang University of Technology, B.S. in Automation, College of Information Engineering


# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><img src='images/POPO.png' alt="POPO" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Beyond Negative Rollouts: Positive-Only Policy Optimization with Implicit Negative Gradients**](https://arxiv.org/pdf/2605.06650)

**Mingwei Xu**, Hao Fang \| <a href="https://arxiv.org/abs/2605.06650"><i class="ai ai-fw ai-arxiv" aria-hidden="true"></i> arXiv</a> \| <a href="https://github.com/momo1443/colm2026-POPO"><i class="fab fa-fw fa-github" aria-hidden="true"></i> GitHub</a>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/Vedio.png' alt="AV-Phys" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Do Joint Audio-Video Generation Models Understand Physics?**](https://arxiv.org/pdf/2605.07061)

Zijun Cui, Xiulong Liu, Hao Fang, **Mingwei Xu**, Jiageng Liu，Zexin Xu，Weiguo Pian，Shijian Deng，Feiyu Du，Chenming Ge，Yapeng Tian \| <a href="https://arxiv.org/abs/2605.07061"><i class="ai ai-fw ai-arxiv" aria-hidden="true"></i> arXiv</a> \| <a href="https://zijuncui.com/AV-Phys/"><i class="fab fa-fw fa-github" aria-hidden="true"></i> GitHub</a>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/Brain.png' alt="POPO" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Task-Dependent Cortical Oscillatory Dynamics in Functional Constipation**](https://www.mdpi.com/1424-8220/26/1/211)

Jianhua Li, Hui Yang, **Mingwei Xu**, Yiman Wu，Xiaokai Shou，Zhihui Huang，Yan Hao，Fangchao Wu，Weishuyi Ruan，Ying Zhang，Zhengzhe Cui，Yina Wei \| <a href="https://www.mdpi.com/1424-8220/26/1/211"><i class="fas fa-fw fa-external-link-alt" aria-hidden="true"></i> Paper</a> \| <a href="https://github.com/mxmw03/EEG_Functional_constipation"><i class="fab fa-fw fa-github" aria-hidden="true"></i> GitHub</a>

</div>
</div>

# 🎖 Honors and Awards
- *2025* Meritorious Winner (International First Prize), Mathematical Contest in Modeling / Interdisciplinary Contest in Modeling (MCM/ICM)
- *2025* Outstanding Graduate, Zhejiang University of Technology
- *2024* National First Prize & National Runner-up, National Undergraduate Smart Car Competition
- *2024* National Third Prize, National Undergraduate Robot Competition (Underwater Robot Group)
- *2024* Provincial First Prize, Zhejiang Provincial Undergraduate Smart Car Competition
- *2023* National Third Prize, National Undergraduate Electronics Design Contest
- *2023* Provincial Third Prize, Zhejiang Provincial Undergraduate Electronics Design Contest
- *2023* Provincial Second Prize, Zhejiang Provincial Undergraduate Smart Car Competition
- *2022* National Second Prize, National Undergraduate Mathematics Competition (Non-Mathematics Category)
- *2022* Provincial Second Prize, Zhejiang Provincial Undergraduate Physics Competition
- *2021* National Third Prize, National Undergraduate Mathematics Competition (Non-Mathematics Category)
- *2021 - 2025* Zhejiang Provincial Government Scholarship, First-Class Outstanding Student Scholarship, and Innovation and Entrepreneurship Scholarship


# 💻 Internships
- *2025.11 - 2026.05*, Paul G. Allen Center for Computer Science & Engineering, University of Washington, LLM Training Researcher
- *2024.07 - 2024.09*, Hangzhou Denghong Technology Co., Ltd., Automation Software Engineer

# 🚀 Selected Projects
- **FinTech Agentic QA** \| [GitHub](https://github.com/mxmw03/fintech-agentic-qa): Designed single-agent and multi-agent financial QA systems with an orchestrator that coordinates market, fundamentals, and sentiment agents. Integrated yfinance, local SQLite databases, Streamlit, and LLM-as-judge evaluation.

# 🛠 Skills
- **Languages**: Python, C++, C, Java
- **ML / AI**: PyTorch, Hugging Face, TRL, verl, LoRA, DeepSpeed, FSDP, vLLM, LangChain, agent systems
- **Tools / Platforms**: Git, Linux, Docker, MATLAB, STM32, Raspberry Pi, Infineon TC264, embedded systems
