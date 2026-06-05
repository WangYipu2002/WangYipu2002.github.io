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

Hi, I am Yipu Wang. I am currently a Ph.D. candidate jointly supervised by the Institute of Automation, Chinese Academy of Sciences (CASIA), and the School of Advanced Interdisciplinary Sciences, University of Chinese Academy of Sciences. I am fortunate to be advised by [Prof. Xiaolong Zheng](https://people.ucas.edu.cn/~xlzheng). 
My research focuses on vision-language models and spatial intelligence.


<!-- # 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📝 Publications 

## 📋 Technical Reports

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2026</div><img src='images/KimiK2.5.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Kimi K2.5: Visual Agentic Intelligence](https://arxiv.org/abs/2602.02276)

Kimi Team (including **Yipu Wang**)

- Kimi K2.5 is a frontier visual agentic model that achieves state-of-the-art performance on computer-use and multimodal reasoning benchmarks, advancing open-source visual agentic intelligence.
</div>
</div>

## ✍️ First Author / Co-First Author Papers

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2025</div><img src='images/CrossPoint.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Towards Cross-View Point Correspondence in Vision-Language Models](https://arxiv.org/abs/2512.04686)

**Yipu Wang**<sup>*</sup>, Yuheng Ji<sup>*</sup>, Yuyang Liu<sup>*</sup>, Enshen Zhou, Ziqiang Yang, Yuxuan Tian, Ziheng Qin, Yue Liu, Huajie Tan, Cheng Chi, Zhiyuan Ma, Daniel Dajun Zeng, Xiaolong Zheng

- Cross-view correspondence is a fundamental capability for spatial understanding and embodied AI. We propose the Cross-View Point Correspondence (CVPC) task and CrossPoint-Bench, a comprehensive benchmark with hierarchical design. Our evaluation shows state-of-the-art models still fall far behind humans. We construct CrossPoint-378K, a dataset with 378K question-answering pairs across 900 scenes, and propose CroPond that achieves state-of-the-art performance on CrossPoint-Bench, surpassing Gemini-2.5-Pro by 39.7% accuracy.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2025</div><img src='images/VisualTrans.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[VisualTrans: A Benchmark for Real-World Visual Transformation Reasoning](https://arxiv.org/abs/2508.04043)

Yuheng Ji<sup>*</sup>, **Yipu Wang**<sup>*</sup>, Yuyang Liu, Xiaoshuai Hao, Yue Liu, Yuting Zhao, Huaihai Lyu, Xiaolong Zheng

- VisualTrans is the first real-world benchmark for Visual Transformation Reasoning (VTR), evaluating spatial, procedural and quantitative reasoning across 12 human-object interaction tasks. While current models perform well on static tasks, they show significant limitations in dynamic, multi-step reasoning, revealing critical gaps in temporal and causal understanding for intelligent systems.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JES 2023</div><img src='images/WAPHF.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Wavelet attention-powered neural network framework with hierarchical dynamic frequency learning for lithium-ion battery state of health prediction](https://www.sciencedirect.com/science/article/abs/pii/S2352152X23000944)

**Yipu Wang**, Huan Wang

- We propose WAPHF, a wavelet attention-powered hierarchical dynamic frequency learning framework for lithium battery SOH prediction. By integrating CNN with wavelet transform and dynamic frequency-focused attention, our method effectively addresses frequency aliasing issues and outperforms state-of-the-art approaches across three datasets.
</div>
</div>

## 🤝 Collaborative Papers

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025 (Spotlight)</div><img src='images/OpenCUA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[OpenCUA: Open Foundations for Computer-Use Agents](https://arxiv.org/abs/2508.09123)

Xinyuan Wang<sup>*</sup>, Bowen Wang<sup>*</sup>, Dunjie Lu<sup>*</sup>, Junlin Yang<sup>*</sup>, Tianbao Xie<sup>*</sup>, Junli Wang<sup>*</sup>, et al., **Yipu Wang**, Heng Wang, Diyi Yang, Victor Zhong, Y.Charles, Zhilin Yang, Tao Yu

- We present OpenCUA, a comprehensive open-source framework for scaling CUA data and foundation models which includes an annotation infrastructure, the first large-scale computer-use task dataset and a scalable pipeline that transforms demonstrations into state–action pairs with reflective long Chain-of-Thought reasoning. Our end-to-end agent model, OpenCUA-32B achieves an average success rate of 32.5% on OSWorld-Verified, establishing a new state-of-the-art (SOTA) among open-source models and surpassing OpenAI CUA (GPT-4o).
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/ScalingUp.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Scaling Up AI-Generated Image Detection with Generator-Aware Prototypes](https://arxiv.org/abs/2512.12982)

Ziheng Qin, Yuheng Ji, Renshuai Tao, Yuxuan Tian, Yuyang Liu, **Yipu Wang**, Xiaolong Zheng

- We propose a generator-aware prototype framework for scalable AI-generated image detection that leverages generator-specific knowledge to improve generalization across diverse generative models, achieving state-of-the-art performance on large-scale benchmarks.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2026</div><img src='images/SpatialSurvey.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Spatial Intelligence from a Cognitive Map Perspective: A Survey

Yuxuan Tian, Yuheng Ji, Xiaolong Zheng, Ziheng Qin, **Yipu Wang**, Xiao Zheng, Yuyang Liu, Shiming Bai, Zhiyuan Li, Liwei Wang, et al.

- A comprehensive survey on spatial intelligence in AI systems from a cognitive map perspective, covering spatial reasoning, scene understanding, and embodied AI with systematic categorization of current methods and future directions.
</div>
</div>

 


<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Educations
- *2025.09 - Present*, University of Chinese Academy of Sciences, Computer Science and Technology.
- *2021.09 - 2025.06*, University of Electronic Science and Technology of China, Electrical and Electronic Engineering.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2026.03 - Present*, <img src='images/xiaohongshu.png' style='height: 1em; vertical-align: middle;'> Xiaohongshu (小红书), supervised by [Feilong Chen](https://phellonchen.github.io/).
- *2025.02 - 2025.07*, <img src='images/moonshot.png' style='height: 1em; vertical-align: middle;'> Moonshot AI (Kimi), Multimodal Team, supervised by [Yujun Chen](https://openreview.net/profile?id=~Y.Charles2).
