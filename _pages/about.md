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

I am a D.Eng student at Wuhan University. 

I graduated from School of Remote Sensing and Information Engineering, Wuhan University with a bachelor’s degree and from the State Key Laboratory of Remote Sensing for Surveying and Mapping, Wuhan University with a master’s degree.

My research focuses on remote sensing image processing and computer vision, with particular interests in domain adaptation, object detection, and image segmentation.

# 📝 Publications

<!-- 第一条论文 -->
<div class='paper-box'>
  <div class='paper-box-text' markdown="1">
    **[Multi-level domain perturbation for source-free object detection in remote sensing images](https://www.tandfonline.com/doi/full/10.1080/10095020.2024.2378920)**  
    Weixing Liu, Jun Liu, Xin Su, Han Nie, and Bin Luo  
    **Geo-Spatial Information Science 2024** \| [\[arXiv\]](https://arxiv.org/abs/2401.17916)  
    [![GitHub](https://img.shields.io/badge/GitHub-Visit%20GitHub-blue?logo=github)](https://github.com/weix-liu/AFSP)
  </div>
</div>

---

<!-- 第二条论文 -->
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">synthetic vehicle dataset</div>
      <img src='images/vehicle.png' alt="vehicle" width="300">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
    **[Unsupervised Domain Adaptation for Remote-Sensing Vehicle Detection Using Domain-Specific Channel Recalibration](https://ieeexplore.ieee.org/abstract/document/10247619)**  
    Weixing Liu, Jun Liu, Bin Luo  
    **IEEE Geoscience and Remote Sensing Letters 2023** \| [\[synthetic vehicle dataset\]](https://drive.google.com/drive/folders/1pADL1uT4TDAEqbCrB5VISFdU7NqaaV4c?usp=drive_link)  
    [![GitHub](https://img.shields.io/badge/GitHub-Visit%20GitHub-blue?logo=github)](https://github.com/weix-liu/DSCR)
  </div>
</div>

---

<!-- 第三条论文 -->
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">synthetic airplane dataset</div>
      <img src='images/airplane.png' alt="airplane" width="300">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
    **[Synthetic data augmentation using multiscale attention CycleGAN for aircraft detection in remote sensing images](https://ieeexplore.ieee.org/abstract/document/9337932)**  
    Weixing Liu, Bin Luo, Jun Liu  
    **IEEE Geoscience and Remote Sensing Letters 2021** \| [\[arXiv\]](https://arxiv.org/abs/2006.05015) \| [\[synthetic airplane dataset\]](https://drive.google.com/drive/folders/1BxG4C2iJHaIHaIpiKwewef1cM5TuPIt-?usp=drive_link)  
    [![GitHub](https://img.shields.io/badge/GitHub-Visit%20GitHub-blue?logo=github)](https://github.com/weix-liu/MACGAN)
  </div>
</div>






