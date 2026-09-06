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

I am a third-year Ph.D. student at [USTC](https://www.ustc.edu.cn/) and a Research Intern at [Qwen, Alibaba Group](https://qwen.ai/). I am co-supervised by [Feng Zhao](https://en.auto.ustc.edu.cn/2021/0616/c26828a513169/page.htm), [Bo Dai](https://daibo.info/), and [Dahua Lin](http://dahua.site/). Previously, I conducted research at [Shanghai AI Laboratory](https://www.shlab.org.cn/) and received my B.Eng. from Wuhan University in 2023.

<div class="focus-topics" markdown="1">
**Some topics that I currently focus on include:**

- **Controllable image generation and editing:** [Qwen-Image-3.0](https://qwen.ai/blog?id=qwen-image-3.0), [Qwen-Image-2.0](https://arxiv.org/abs/2605.10730)
- **3D reconstruction and scalable neural rendering:** [AnySplat](https://city-super.github.io/anysplat/), [Horizon-GS](https://city-super.github.io/horizon-gs/), [Octree-GS](https://city-super.github.io/octree-gs/), [MatrixCity](https://city-super.github.io/matrixcity/)
</div>


# 🔥 News
<div class="news-list" markdown="1">
- **2026.08** &emsp; Two papers were accepted to the main track of [EMNLP 2026](https://2026.emnlp.org/).
- **2026.08** &emsp; We’re excited to celebrate the release of [Qwen-Image-3.0](https://qwen.ai/blog?id=qwen-image-3.0)! Congratulations to the whole team, and I’m delighted to work with so many talented people. Many thanks to [Arena.ai](https://x.com/arena) for featuring Qwen-Image-3.0-Pro at **#5 with 1,263 points** on the Text-to-Image Arena, up from #15 and 1,191 points for Qwen-Image-2.0-Pro. [[**Leaderboard**]](https://arena.ai/leaderboard)
- **2026.05** &emsp; We released the [Qwen-Image-2.0](https://arxiv.org/abs/2605.10730) Technical Report.
- **2026.02** &emsp; One paper was accepted to [CVPR 2026](https://cvpr.thecvf.com/Conferences/2026).
- **2025.09** &emsp; One paper was accepted to [NeurIPS 2025](https://neurips.cc/Conferences/2025/).
- **2025.08** &emsp; One paper was accepted to [SIGGRAPH Asia 2025 (ACM TOG)](https://asia.siggraph.org/2025/).

<details class="news-archive">
<summary>Earlier news</summary>
<div markdown="1">

- **2025.06** &emsp; One paper was accepted to [ICCV 2025](https://iccv.thecvf.com/Conferences/2025).
- **2025.05** &emsp; One paper was accepted to [SIGGRAPH 2025](https://s2025.siggraph.org/).
- **2025.05** &emsp; One paper was accepted to [TPAMI 2025](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=34).
- **2025.02** &emsp; Two papers were accepted to [CVPR 2025](https://cvpr.thecvf.com/Conferences/2025).
- **2024.09** &emsp; One paper was accepted to [NeurIPS 2024](https://neurips.cc/Conferences/2024).
- **2023.09** &emsp; One paper was accepted to [NeurIPS 2023 D&B Track](https://nips.cc/Conferences/2023/CallForDatasetsBenchmarks).
- **2023.07** &emsp; Our [LandMark System](https://landmark.intern-ai.org.cn/) was released.
- **2023.07** &emsp; One paper was accepted to [ICCV 2023](https://iccv2023.thecvf.com/).
- **2023.06** &emsp; Graduated from Wuhan University.

</div>
</details>
</div>

# 🔖 Technical Reports

<!-- Qwen-Image-3.0 -->
<div class='paper-box paper-box--featured'><div class='paper-box-image'><div><div class="badge">Technical Report</div><img src='../images/qwen-image-3.jpg' alt="Qwen-Image-3.0 release visual" width="100%" loading="lazy"></div></div>
<div class='paper-box-text' markdown="1">
**Qwen-Image-3.0: Rich Content, Authentic Details, Deep Knowledge**

Qwen Team · **Core Contributor**

Built for useful visual work with prompts up to 4.5K tokens, legible text down to 10 px, native rendering in 12 languages, knowledge-rich generation, and realistic interfaces.

[[**Blog**]](https://qwen.ai/blog?id=qwen-image-3.0)&nbsp;
[[**Try Qwen**]](https://chat.qwen.ai/?inputFeature=t2i)&nbsp;
[[**API**]](https://www.alibabacloud.com/help/en/model-studio/qwen-image-generation-and-editing-api-reference)

</div>
</div>
<!-- Qwen-Image-3.0 -->

<!-- Qwen-Image-2.0-RL -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Technical Report</div><img src='../images/qwen-image-2.0-RL.png' alt="Qwen-Image-2.0-RL training pipeline" width="100%" loading="lazy"></div></div>
<div class='paper-box-text' markdown="1">
**Qwen-Image-2.0-RL Technical Report**

Qwen Team

A post-training pipeline combining task-specific reward models, GRPO-based reinforcement learning, and on-policy distillation to improve visual quality, instruction following, editing accuracy, and face identity preservation.

[[**Paper**]](https://arxiv.org/abs/2606.27608)

</div>
</div>
<!-- Qwen-Image-2.0-RL -->

<!-- Qwen-Image-Agent -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Technical Report</div><img src='../images/qwen-image-agent.png' alt="Qwen-Image-Agent capabilities and examples" width="100%" loading="lazy"></div></div>
<div class='paper-box-text' markdown="1">
**Qwen-Image-Agent: Bridging the Context Gap in Real-World Image Generation**

Qwen Team

A context-centric image generation agent that plans for missing information and grounds requests through reasoning, search, memory, and feedback, turning underspecified user intent into reliable generation context.

[[**Paper**]](https://arxiv.org/abs/2606.26907)

</div>
</div>
<!-- Qwen-Image-Agent -->

<!-- Qwen-RobotWorld -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Technical Report</div><img src='../images/qwen-robotworld.png' alt="Qwen-RobotWorld model architecture" width="100%" loading="lazy"></div></div>
<div class='paper-box-text' markdown="1">
**Qwen-RobotWorld Technical Report: Unifying Embodied World Modeling through Language-Conditioned Video Generation**

Qwen Team

A language-conditioned video world model that predicts physically grounded future trajectories across robotic manipulation, autonomous driving, indoor navigation, and human-to-robot transfer.

[[**Paper**]](https://arxiv.org/abs/2606.17030)&nbsp;
[[**Blog**]](https://qwen.ai/blog?id=qwen-robotworld)

</div>
</div>
<!-- Qwen-RobotWorld -->

<!-- Qwen-Image-Flash -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Technical Report</div><img src='../images/qwen-image-flash.png' alt="Qwen-Image-Flash generation and editing examples" width="100%" loading="lazy"></div></div>
<div class='paper-box-text' markdown="1">
**Qwen-Image-Flash: Beyond Objective Design**

Qwen Team

A unified 4-NFE model for fast text-to-image generation and instruction-guided editing, developed through a systematic study of data composition, multi-teacher guidance, and generation-editing task mixtures.

[[**Paper**]](https://arxiv.org/abs/2606.03746)

</div>
</div>
<!-- Qwen-Image-Flash -->

<!-- Qwen-Image-VAE-2.0 -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Technical Report</div><img src='../images/qwen-image-vae.png' alt="Qwen-Image-VAE-2.0 text reconstruction comparison" width="100%" loading="lazy"></div></div>
<div class='paper-box-text' markdown="1">
**Qwen-Image-VAE-2.0 Technical Report**

Qwen Team

A high-compression VAE suite designed for strong reconstruction fidelity and diffusion-friendly latent representations, with particular gains on text-rich imagery and efficient encoding.

[[**Paper**]](https://arxiv.org/abs/2605.13565)&nbsp;
[[**Benchmark Code**]](https://github.com/alibaba/OmniDoc-TokenBench)&nbsp;
<a class="github-stars" href="https://github.com/alibaba/OmniDoc-TokenBench" aria-label="GitHub stars for OmniDoc-TokenBench"><img src="https://img.shields.io/github/stars/alibaba/OmniDoc-TokenBench?style=social&amp;label=Stars" alt="GitHub stars for OmniDoc-TokenBench" loading="lazy"></a>

</div>
</div>
<!-- Qwen-Image-VAE-2.0 -->

<!-- Qwen-Image-2.0 -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Technical Report</div><img src='../images/qwen-image-2.png' alt="Qwen-Image-2.0 generation and editing examples" width="100%" loading="lazy"></div></div>
<div class='paper-box-text' markdown="1">
**Qwen-Image-2.0 Technical Report**

Qwen Team · **Core Contributor**

Qwen-Image-2.0 is an omni-capable image generation foundation model that integrates high-fidelity image creation and precise image editing into a single unified framework.

[[**Paper**]](https://arxiv.org/abs/2605.10730)

</div>
</div>
<!-- Qwen-Image-2.0 -->

# 📝 Research Papers

(† corresponding author; * equal contribution)

<!-- Qwen-Image-Bench -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2026</div><img src='../images/qwen-image-bench.png' alt="sym" width="100%" loading="lazy"></div></div>
<div class='paper-box-text' markdown="1">
**Qwen-Image-Bench: From Generation to Creation in Text-to-Image Evaluation**

Qwen Team

Qwen-Image-Bench is a creator-centric benchmark for evaluating text-to-image models with fine-grained, expert-aligned scoring.

[[**Paper**]](https://arxiv.org/abs/2605.28091)&nbsp;
[[**Code**]](https://github.com/QwenLM/Qwen-Image-Bench)&nbsp;
<a class="github-stars" href="https://github.com/QwenLM/Qwen-Image-Bench" aria-label="GitHub stars for Qwen-Image-Bench"><img src="https://img.shields.io/github/stars/QwenLM/Qwen-Image-Bench?style=social&amp;label=Stars" alt="GitHub stars for Qwen-Image-Bench" loading="lazy"></a>

</div>
</div>
<!-- Qwen-Image-Bench -->

<!-- G2VLM -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='../images/g2vlm_demo_2s.gif' alt="G2VLM demo gif" width="100%" loading="lazy"></div></div>
<div class='paper-box-text' markdown="1">
**G²VLM: Geometry Grounded Vision Language Model with Unified 3D Reconstruction and Spatial Reasoning**

[Wenbo Hu](https://gordonhu608.github.io/g2vlm.github.io/)\*,
[Jingli Lin](https://openreview.net/profile?id=~Jingli_Lin1)\*,
[Yilin Long](https://openreview.net/profile?id=~Yilin_Long1)\*,
[Yunlong Ran](https://openreview.net/profile?id=~Yunlong_Ran1),
**Lihan Jiang**,
[Yifan Wang](https://github.com/wangyf2001),
[Chenming Zhu](https://zcmax.github.io/),
[Runsen Xu](https://runsenxu.com/),
[Tai Wang<sup>†</sup>](https://tai-wang.github.io/),
[Jiangmiao Pang<sup>†</sup>](https://oceanpang.github.io/)

[[**Project**]](https://gordonhu608.github.io/g2vlm.github.io/)&nbsp;
[[**Paper**]](https://arxiv.org/abs/2511.21688)&nbsp;
[[**Code**]](https://github.com/InternRobotics/G2VLM)&nbsp;
<a class="github-stars" href="https://github.com/InternRobotics/G2VLM" aria-label="GitHub stars for G2VLM"><img src="https://img.shields.io/github/stars/InternRobotics/G2VLM?style=social&amp;label=Stars" alt="GitHub stars for G2VLM" loading="lazy"></a>

</div>
</div>
<!-- G2VLM -->

<!-- AnySplat -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGGRAPH Asia 2025 (ACM TOG)</div><img src='../images/anysplat.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**AnySplat: Feed-forward 3D Gaussian Splatting from Unconstrained Views**

**Lihan Jiang\***,
[Yucheng Mao*](https://myc634.github.io/yuchengmao/),
[Linning Xu](https://eveneveno.github.io/lnxu),
[Tao Lu](https://inspirelt.github.io/),
[Kerui Ren](https://cskrren.github.io/),
Yichen Jin,
[Xudong Xu](https://scholar.google.com.hk/citations?user=D8VMkA8AAAAJ&hl=en),
[Mulin Yu](https://scholar.google.com/citations?user=w0Od3hQAAAAJ),
[Jiangmiao Pang](https://oceanpang.github.io/),
[Feng Zhao](https://scholar.google.co.uk/citations?user=r6CvuOUAAAAJ&hl=en),
[Dahua Lin](http://dahua.site/),
[Bo Dai<sup>†</sup>](https://daibo.info/)

[[**Project**]](https://city-super.github.io/anysplat/)&nbsp;
[[**Paper**]](https://arxiv.org/pdf/2505.23716)&nbsp;
[[**Code**]](https://github.com/OpenRobotLab/AnySplat)&nbsp;
<a class="github-stars" href="https://github.com/OpenRobotLab/AnySplat" aria-label="GitHub stars for AnySplat"><img src="https://img.shields.io/github/stars/OpenRobotLab/AnySplat?style=social&amp;label=Stars" alt="GitHub stars for AnySplat" loading="lazy"></a>

</div>
</div>
<!-- AnySplat -->


<!-- MVColight -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='../images/mvcolight.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**MV-CoLight: Efficient Object Compositing with Consistent Lighting and Shadow Generation**


[Kerui Ren](https://cskrren.github.io/),
[Jiayang Bai](https://scholar.google.com/citations?user=VmPQ6akAAAAJ&hl=zh-CN),
[Linning Xu](https://eveneveno.github.io/lnxu),
**Lihan Jiang**,
[Jiangmiao Pang](https://oceanpang.github.io/),
[Mulin Yu<sup>†</sup>](https://scholar.google.com/citations?user=w0Od3hQAAAAJ),
[Bo Dai<sup>†</sup>](https://daibo.info/)

[[**Project**]](https://city-super.github.io/mvcolight/)&nbsp;
[[**Paper**]](https://arxiv.org/pdf/2505.21483v1)

</div>
</div>

<!-- MVColight -->


<!-- ObjectGS -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='../images/objectgs.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**ObjectGS: Object-aware Scene Reconstruction and Scene Understanding via Gaussian Splatting**

[Ruijie Zhu](https://ruijiezhu94.github.io/ruijiezhu/),
[Mulin Yu](https://scholar.google.com/citations?user=w0Od3hQAAAAJ),
[Linning Xu](https://eveneveno.github.io/lnxu),
**Lihan Jiang**,
[Yixuan Li](https://yixuanli98.github.io/),
[Tianzhu Zhang](https://staff.ustc.edu.cn/~tzzhang/),
[Jiangmiao Pang](https://oceanpang.github.io/), 
[Bo Dai<sup>†</sup>](https://daibo.info/), 

[[**Project**]](https://ruijiezhu94.github.io/ObjectGS_page/)&nbsp;
[[**Paper**]](https://arxiv.org/pdf/2507.15454.pdf)&nbsp;
[[**Code**]](https://github.com/RuijieZhu94/ObjectGS)&nbsp;
<a class="github-stars" href="https://github.com/RuijieZhu94/ObjectGS" aria-label="GitHub stars for ObjectGS"><img src="https://img.shields.io/github/stars/RuijieZhu94/ObjectGS?style=social&amp;label=Stars" alt="GitHub stars for ObjectGS" loading="lazy"></a>

</div>
</div>
<!-- ObjectGS -->

<!-- V3DG -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGGRAPH 2025</div><img src='../images/V3DG.jpeg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**Virtualized 3D Gaussians: Flexible Cluster-based Level-of-Detail System for Real-Time Rendering of Composed Scenes**

[Xijie Yang](https://yang-xijie.github.io/),
[Linning Xu](https://eveneveno.github.io/lnxu),
**Lihan Jiang**,
[Dahua Lin](http://dahua.site/), 
[Bo Dai<sup>†</sup>](https://daibo.info/), 

[[**Project**]](https://xijie-yang.github.io/V3DG/)&nbsp;
[[**Paper**]](https://arxiv.org/pdf/2505.06523)&nbsp;
[[**Code**]](https://github.com/city-super/V3DG)&nbsp;
<a class="github-stars" href="https://github.com/city-super/V3DG" aria-label="GitHub stars for V3DG"><img src="https://img.shields.io/github/stars/city-super/V3DG?style=social&amp;label=Stars" alt="GitHub stars for V3DG" loading="lazy"></a>

</div>
</div>
<!-- V3DG -->


<!-- Scene4U -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='../images/Scene4U.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**Scene4U: Hierarchical Layered 3D Scene Reconstruction from Single Panoramic Image for Your Immerse Exploration**

[Zilong Huang](https://openreview.net/profile?id=~Zilong_Huang2),
[Jun He](https://scholar.google.com/citations?user=ktFT40UAAAAJ&hl=zh-CN),
[Junyan Ye](https://scholar.google.com/citations?user=6IbGkd4AAAAJ&hl=en), 
**Lihan Jiang**,
[Weijia Li](https://liweijia.github.io/), 
[Yiping Chen](https://scholar.google.com/citations?user=e9lv2fUAAAAJ&hl=en), 
[Ting Han](https://scholar.google.com/citations?user=IVWx-jwAAAAJ&hl=zh-CN)

[[**Paper**]](https://arxiv.org/pdf/2504.00387)

</div>
</div>
<!-- Scene4U -->

<!-- Horizon-GS -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='../images/horizon-gs.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**Horizon-GS: Unified 3D Gaussian Splatting for Large-Scale Aerial-to-Ground Scenes**

**Lihan Jiang\***,
[Kerui Ren*](https://cskrren.github.io/),
[Mulin Yu](https://scholar.google.com/citations?user=w0Od3hQAAAAJ),
[Linning Xu](https://eveneveno.github.io/lnxu),
[Junting Dong](https://jtdong.com/),
[Tao Lu](https://inspirelt.github.io/),
[Feng Zhao](https://scholar.google.co.uk/citations?user=r6CvuOUAAAAJ&hl=en),
[Dahua Lin](http://dahua.site/),
[Bo Dai<sup>†</sup>](https://daibo.info/)

[[**Project**]](https://city-super.github.io/horizon-gs/)&nbsp;
[[**Paper**]](https://arxiv.org/pdf/2412.01745)&nbsp;
[[**Code**]](https://github.com/OpenRobotLab/HorizonGS)&nbsp;
<a class="github-stars" href="https://github.com/OpenRobotLab/HorizonGS" aria-label="GitHub stars for Horizon-GS"><img src="https://img.shields.io/github/stars/OpenRobotLab/HorizonGS?style=social&amp;label=Stars" alt="GitHub stars for Horizon-GS" loading="lazy"></a>

</div>
</div>
<!-- Horizon-GS -->

<!-- Octree-GS -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI 2025</div><img src='../images/octree-gs.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**Octree-GS: Towards Consistent Real-time Rendering with LOD-Structured 3D Gaussians**

[Kerui Ren*](https://cskrren.github.io/),
**Lihan Jiang\***,
[Tao Lu](https://inspirelt.github.io/),
[Mulin Yu](https://scholar.google.com/citations?user=w0Od3hQAAAAJ),
[Linning Xu](https://eveneveno.github.io/lnxu),
[Zhangkai Ni](https://eezkni.github.io/),
[Bo Dai<sup>†</sup>](https://daibo.info/)

[[**Project**]](https://city-super.github.io/octree-gs/)&nbsp;
[[**Paper**]](https://arxiv.org/abs/2403.17898)&nbsp;
[[**Code**]](https://github.com/city-super/Octree-GS)&nbsp;
<a class="github-stars" href="https://github.com/city-super/Octree-GS" aria-label="GitHub stars for Octree-GS"><img src="https://img.shields.io/github/stars/city-super/Octree-GS?style=social&amp;label=Stars" alt="GitHub stars for Octree-GS" loading="lazy"></a>

</div>
</div>
<!-- Octree-GS -->

<!-- GSDF -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='../images/GSDF.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**GSDF: 3DGS Meets SDF for Improved Rendering and Reconstruction**

[Mulin Yu\*](https://scholar.google.com/citations?user=w0Od3hQAAAAJ),
[Tao Lu*](https://inspirelt.github.io/),
[Linning Xu](https://eveneveno.github.io/lnxu),
**Lihan Jiang**,
[Yuanbo Xiangli<sup>†</sup>](https://kam1107.github.io/),
[Bo Dai](https://daibo.info/)

[[**Project**]](https://city-super.github.io/GSDF/)&nbsp;
[[**Paper**]](https://arxiv.org/abs/2403.16964)&nbsp;
[[**Code**]](https://github.com/city-super/GSDF)&nbsp;
<a class="github-stars" href="https://github.com/city-super/GSDF" aria-label="GitHub stars for GSDF"><img src="https://img.shields.io/github/stars/city-super/GSDF?style=social&amp;label=Stars" alt="GitHub stars for GSDF" loading="lazy"></a>

</div>
</div>
<!-- GSDF -->


<!-- PAD -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2023 D&B Track </div><img src='../images/pad.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


**PAD: A Dataset and Benchmark for Pose-agnostic Anomaly Detection**

[Qiang Zhou\*](https://scholar.google.com/citations?user=CMYTxUEAAAAJ&hl=en),
[Weize Li\*](https://ericlee0224.github.io/),
**Lihan Jiang**,
[Guoliang Wang](https://github.com/Cross-ZBuild),
[Guyue Zhou](https://air.tsinghua.edu.cn/en/info/1046/1196.htm),
[Shanghang Zhang](https://www.shanghangzhang.com/),
[Hao Zhao<sup>†</sup>](https://sites.google.com/view/fromandto)

[[**Project**]](https://github.com/EricLee0224/PAD)&nbsp;
[[**Paper**]](https://arxiv.org/pdf/2310.07716.pdf)&nbsp;
[[**Code**]](https://github.com/EricLee0224/PAD)&nbsp;
<a class="github-stars" href="https://github.com/EricLee0224/PAD" aria-label="GitHub stars for PAD"><img src="https://img.shields.io/github/stars/EricLee0224/PAD?style=social&amp;label=Stars" alt="GitHub stars for PAD" loading="lazy"></a>

</div>
</div>
<!-- PAD -->


<!-- MatrixCity -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='../images/matrixcity.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**MatrixCity: A Large-scale City Dataset for City-scale Neural Rendering and Beyond** 

[Yixuan Li*](https://yixuanli98.github.io/),
**Lihan Jiang\***,
[Linning Xu](https://eveneveno.github.io/lnxu/),
[Yuanbo Xiangli](https://kam1107.github.io/),
[Zhengzhi Wang](https://zhenzhiwang.github.io/),
[Dahua Lin](http://dahua.me/),
[Bo Dai<sup>†</sup>](http://daibo.info/)

[[**Project**]](https://city-super.github.io/matrixcity/)&nbsp;
[[**Paper**]](https://arxiv.org/pdf/2309.16553v1.pdf)&nbsp;
[[**Code**]](https://github.com/city-super/MatrixCity)&nbsp;
<a class="github-stars" href="https://github.com/city-super/MatrixCity" aria-label="GitHub stars for MatrixCity"><img src="https://img.shields.io/github/stars/city-super/MatrixCity?style=social&amp;label=Stars" alt="GitHub stars for MatrixCity" loading="lazy"></a>

</div>
</div>
<!-- MatrixCity -->

# 🎖 Honors and Awards
- Outstanding Graduate Student, WHU, 2023
- China National Scholarships, 2021
- China National Scholarships, 2020
- The First Prize Scholarship, WHU, 2021
- The First Prize Scholarship, WHU, 2020

# 📖 Education
- Ph.D. in Control Science and Engineering, [University of Science and Technology of China](https://www.ustc.edu.cn/), Sep 2023 - Jun 2028 (expected)
- B.Eng. in Geodesy and Geomatics Engineering, [Wuhan University](https://www.whu.edu.cn/), Sep 2019 - Jun 2023
  - GPA: 3.95/4.00, Rank: 1/225

# 🧐 Academic Service

**Reviewer**

- NeurIPS: 2024, 2025
- ICLR: 2025, 2026
- ICML: 2025, 2026
- CVPR: 2025, 2026
- EuroGraphics: 2025
- SIGGRAPH: 2025, 2026
  
# 💻 Research Experience

<style>
  .internship-list {
    position: relative;
    margin-top: 1rem;
  }

  .internship-list::before {
    content: "";
    position: absolute;
    left: 36px;
    top: 12px;
    bottom: 12px;
    width: 2px;
    background: linear-gradient(180deg, #0f3d91 0%, #6d94d7 100%);
    opacity: 0.22;
  }

  .internship-card {
    position: relative;
    display: flex;
    gap: 18px;
    align-items: flex-start;
    margin-bottom: 22px;
    padding: 20px 22px;
    border-radius: 8px;
    background: #ffffff;
    border: 1px solid #dfe5ea;
    box-shadow: 0 6px 18px rgba(24, 51, 68, 0.06);
  }

  .internship-logo-wrap {
    position: relative;
    z-index: 1;
    flex-shrink: 0;
    width: 72px;
    height: 72px;
    display: flex;
    align-items: center;
    justify-content: center;
    border-radius: 8px;
    background: #ffffff;
    border: 1px solid rgba(15, 61, 145, 0.12);
    box-shadow: 0 8px 18px rgba(0, 0, 0, 0.08);
  }

  .internship-logo {
    width: 52px;
    height: 52px;
    object-fit: contain;
  }

  .internship-content {
    min-width: 0;
    flex: 1;
  }

  .internship-title-row {
    display: flex;
    flex-wrap: wrap;
    gap: 10px 14px;
    align-items: center;
    margin-bottom: 10px;
  }

  .internship-title {
    margin: 0;
    font-size: 1.12em;
    font-weight: 700;
    letter-spacing: 0.01em;
  }

  .internship-title a {
    color: #0f3d91;
    text-decoration: none;
  }

  .internship-title a:hover {
    color: #1f5ed6;
    text-decoration: underline;
  }

  .internship-badge {
    display: inline-flex;
    align-items: center;
    padding: 0.22rem 0.65rem;
    border-radius: 999px;
    background: rgba(15, 61, 145, 0.08);
    color: #0f3d91;
    font-size: 0.82em;
    font-weight: 600;
    white-space: nowrap;
  }

  .internship-meta {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
  }

  .internship-meta-item {
    display: inline-flex;
    align-items: center;
    gap: 8px;
    padding: 0.42rem 0.78rem;
    border-radius: 12px;
    background: rgba(15, 61, 145, 0.05);
    color: #4b5563;
    font-size: 0.92em;
    line-height: 1.4;
  }

  .internship-meta-item i {
    color: #0f3d91;
  }

  @media (max-width: 768px) {
    .internship-list::before {
      left: 28px;
    }

    .internship-card {
      gap: 14px;
      padding: 16px;
      border-radius: 8px;
    }
    
    .internship-logo-wrap {
      width: 56px;
      height: 56px;
      border-radius: 8px;
    }
    
    .internship-logo {
      width: 40px;
      height: 40px;
    }
  }
</style>

<div class="internship-list">
  <div class="internship-card">
    <div class="internship-logo-wrap">
      <img class="internship-logo" src="../images/qwen.png" alt="Qwen official logo">
    </div>
    <div class="internship-content">
      <div class="internship-title-row">
        <h3 class="internship-title"><a href="https://qwen.ai/">Qwen</a>, Alibaba Group</h3>
        <span class="internship-badge">Research Intern</span>
      </div>
      <div class="internship-meta">
        <span class="internship-meta-item"><i class="far fa-calendar-alt"></i>Mar 2026 - Present</span>
        <span class="internship-meta-item"><i class="far fa-user"></i>Supervised by <a href="https://chenfei-wu.github.io/">Chenfei Wu</a></span>
      </div>
    </div>
  </div>

  <div class="internship-card">
    <div class="internship-logo-wrap">
      <img class="internship-logo" src="../images/shlab.jpeg" alt="Shanghai AI Laboratory official logo">
    </div>
    <div class="internship-content">
      <div class="internship-title-row">
        <h3 class="internship-title"><a href="https://www.shlab.org.cn/">Shanghai AI Laboratory</a></h3>
        <span class="internship-badge">Research Intern</span>
      </div>
      <div class="internship-meta">
        <span class="internship-meta-item"><i class="far fa-calendar-alt"></i>Dec 2022 - Mar 2026</span>
        <span class="internship-meta-item"><i class="far fa-user"></i>Supervised by <a href="https://daibo.info/">Bo Dai</a></span>
      </div>
    </div>
  </div>

  <div class="internship-card">
    <div class="internship-logo-wrap">
      <img class="internship-logo" src="../images/air.jpeg" alt="AIR official logo">
    </div>
    <div class="internship-content">
      <div class="internship-title-row">
        <h3 class="internship-title"><a href="https://air.tsinghua.edu.cn/en/">AIR, Tsinghua University</a></h3>
        <span class="internship-badge">Research Intern</span>
      </div>
      <div class="internship-meta">
        <span class="internship-meta-item"><i class="far fa-calendar-alt"></i>May 2022 - Nov 2022</span>
        <span class="internship-meta-item"><i class="far fa-user"></i>Supervised by <a href="https://sites.google.com/view/fromandto">Hao Zhao</a></span>
      </div>
    </div>
  </div>
</div>
