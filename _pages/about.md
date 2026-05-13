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

I am currently a third-year Ph.D. student at [USTC](https://www.ustc.edu.cn/) and [Shanghai AI Laboratory](https://www.shlab.org.cn/). I am co-supervised by [Feng Zhao](https://en.auto.ustc.edu.cn/2021/0616/c26828a513169/page.htm), [Bo Dai](https://daibo.info/), and [Dahua Lin](http://dahua.site/). Previously, I obtained my B.Eng. degree at [SGG](http://main.sgg.whu.edu.cn/) of Wuhan University in 2023. 

My research interest lies in the field of 3D Computer Vision, particularly neural rendering for large-scale scenes and feed-forward reconstruction.


# 🔥 News
- 2026.05: 🚀 We release [Qwen-Image-2.0](https://arxiv.org/abs/2605.10730) technical report.
- 2026.02: 🚀 one papers got accepted to [CVPR 2026](https://cvpr.thecvf.com/Conferences/2026). 
- 2025.09: 🎉 one paper got accepted to [NeurIPS 2025](https://neurips.cc/Conferences/2025/). 
- 2025.08: 🎉 one paper got accepted to [SIGGRAPH Asia 2025 (ACM TOG)](https://asia.siggraph.org/2025/). 
- 2025.06: 🎉 one paper got accepted to [ICCV 2025](https://iccv.thecvf.com/Conferences/2025). 
- 2025.05: 🎉 one paper got accepted to [SIGGRAPH 2025](https://s2025.siggraph.org/). 
- 2025.05: 🎉 one paper got accepted to [TPAMI 2025](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=34). 
- 2025.02: 🎉 two papers got accepted to [CVPR 2025](https://cvpr.thecvf.com/Conferences/2025). 
- 2024.09: 🎉 one paper got accepted to [NeurIPS 2024](https://neurips.cc/Conferences/2024). 
- 2023.09: 🎉 one paper got accepted to [NeurIPS 2023 D&B Track](https://nips.cc/Conferences/2023/CallForDatasetsBenchmarks). 
- 2023.07: 🎉 our [LandMark System](https://landmark.intern-ai.org.cn/) was released.
- *2023.07*: 🎉 one paper got accepted to [ICCV 2023](https://iccv2023.thecvf.com/). 
- 2023.06: 🎓 Graduated from Wuhan University.

# 📝 Publications 

(†: corresponding author; * :equal contribution)


<!-- Qwen-Image-2.0 -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Technical Report</div><img src='../images/qwen-image-2.png' alt="sym" width="100%" loading="lazy"></div></div>
<div class='paper-box-text' markdown="1">
**Qwen-Image-2.0 Technical Report**

Qwen Team (As the core contributor to this project)

[[**Paper**]](https://arxiv.org/abs/2511.21688)

</div>
</div>

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
[[**Code**]](https://github.com/InternRobotics/G2VLM)

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
[Yichen Jin](),
[Xudong Xu](https://scholar.google.com.hk/citations?user=D8VMkA8AAAAJ&hl=en),
[Mulin Yu](https://scholar.google.com/citations?user=w0Od3hQAAAAJ),
[Jiangmiao Pang](https://oceanpang.github.io/)
[Feng Zhao](https://scholar.google.co.uk/citations?user=r6CvuOUAAAAJ&hl=en),
[Dahua Lin](http://dahua.site/),
[Bo Dai<sup>†</sup>](https://daibo.info/)

[[**Project**]](https://city-super.github.io/anysplat/)&nbsp;
[[**Paper**]](https://arxiv.org/pdf/2505.23716)&nbsp;
[[**Code**]](https://github.com/OpenRobotLab/AnySplat)

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
[Jiangmiao Pang](https://oceanpang.github.io/)
[Mulin Yu<sup>†</sup>](https://scholar.google.com/citations?user=w0Od3hQAAAAJ),
[Bo Dai<sup>†</sup>](https://daibo.info/)

[[**Project**]](https://city-super.github.io/mvcolight/)&nbsp;
[[**Paper**]](https://arxiv.org/pdf/2505.21483v1)&nbsp;
[[**Code**]]()

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
[[**Code**]](https://github.com/RuijieZhu94/ObjectGS)

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
[[**Code**]](https://github.com/city-super/V3DG)

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

[[**Project**]]()&nbsp;
[[**Paper**]](https://arxiv.org/pdf/2504.00387)&nbsp;
[[**Code**]]()

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
[[**Code**]](https://github.com/OpenRobotLab/HorizonGS)

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
[[**Code**]](https://github.com/city-super/Octree-GS)

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
[[**Code**]](https://github.com/city-super/GSDF)

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
[[**Code**]](https://github.com/EricLee0224/PAD)

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
[[**Code**]](https://github.com/city-super/MatrixCity)

</div>
</div>
<!-- MatrixCity -->

# 🎖 Honors and Awards
- Outstanding Graduate Student, WHU, 2023
- China National Scholarships, 2021
- China National Scholarships, 2020
- The First Prize Scholarship, WHU, 2021
- The First Prize Scholarship, WHU, 2020

# 📖 Educations
- Ph.D. in Control Science and Engineering of [University of Science and Technology of China](https://www.ustc.edu.cn/), 2023.09 - present
- B.S. in Geodesy and Geomatics Engineering of [Wuhan University](https://www.whu.edu.cn/), 2019.09 - 2023.06
  - GPA: 3.95/4.00, Rank: 1/225

# 🧐 Community Services

**Reviewer**

- NeurIPS: 2024, 2025
- ICLR: 2025, 2026
- ICML: 2025, 2026
- CVPR: 2025, 2026
- EuroGraphics: 2025
- SIGGRAPH: 2025, 2026
  
# 💻 Internships

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
    border-radius: 18px;
    background: linear-gradient(135deg, #ffffff 0%, #f6f9ff 100%);
    border: 1px solid rgba(15, 61, 145, 0.1);
    box-shadow: 0 12px 28px rgba(15, 61, 145, 0.08);
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
    border-radius: 20px;
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
      border-radius: 16px;
    }
    
    .internship-logo-wrap {
      width: 56px;
      height: 56px;
      border-radius: 16px;
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
        <h3 class="internship-title"><a href="https://qwen.ai/">Qwen</a></h3>
        <span class="internship-badge">Alibaba Group</span>
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
      </div>
      <div class="internship-meta">
        <span class="internship-meta-item"><i class="far fa-calendar-alt"></i>May 2022 - Nov 2022</span>
        <span class="internship-meta-item"><i class="far fa-user"></i>Supervised by <a href="https://sites.google.com/view/fromandto">Hao Zhao</a></span>
      </div>
    </div>
  </div>
</div>
