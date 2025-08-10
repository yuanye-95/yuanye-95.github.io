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
I am a Associate Professor in the College of Computer and Control Engineering, Northeast Forestry University, where I worked on deep learning-based image processing methods and vision applications for remote sensing. I received my Ph.D. from College of Computer Science and Technology, Harbin Engineering University, China in December 2023, advised by Prof. Wu Yanxia. Before that, I received my B.S. from College of Computer Science and Technology, Harbin Engineering University in June 2017.

<!--
My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).
-->

# 🔥 News
- *2024.12*: &nbsp;🎉🎉 New stage of career! I joined the College of Computer and Control Engineering at **Northeast Forestry University**!
- *2025.08*: &nbsp;🎉🎉 One journal paper about multimodal remote sensing semantic segmentation has been accepted by **GIScience & Remote Sensing** ([link](https://ieeexplore.ieee.org/document/11036683))!
- *2025.06*: &nbsp;🎉🎉 One journal paper about unsupervised SAR despeckling has been accepted by **IEEE JSTARS** ([link](https://ieeexplore.ieee.org/document/11036683))!
- *2024.10*: &nbsp;🎉🎉 One journal paper about oriented remote sensing object detection has been accepted by **IEEE JSTARS** ([link](https://ieeexplore.ieee.org/document/10745646))!
- *2024.04*: &nbsp;🎉🎉 One conference paper about unpaired image despeckling has been accepted by **IEEE ICME 2024** ([link](https://ieeexplore.ieee.org/document/10687879))!
- *2024.04*: &nbsp;🎉🎉 One conference paper about adversarial attack for SAM has been accepted by **IEEE ICME 2024** ([link](https://ieeexplore.ieee.org/document/10687491))!
- *2023.12*: &nbsp;🎉🎉 Completed the defense of my PhD thesis (**Research on deep learning based denoising methods for SAR images**) and **received my PhD degree**!
- *2023.09*: &nbsp;🎉🎉 One journal paper about self-supervised SAR image denoising has been accepted by **IEEE TGRS** ([link](https://ieeexplore.ieee.org/document/10285521))!

  
# 📖 Experience
- *2024.12 - now*, Associate Professor, College of Computer and Control Engineering, Northeast Forestry University


- *2018.09 - 2023.12*, Ph.D, College of Computer Science and Technology, Harbin Engineering University
- *2017.09 - 2018.06*, M.S. transfer to Ph.D, College of Computer Science and Technology, Harbin Engineering University
- *2013.09 - 2017.06*, B.S., College of Computer Science and Technology, Harbin Engineering University

  
# 📝 Research Spotlight 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TGRS 2023</div><img src='images/IEEE_TGRS_2023_SARDeSeg.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Segmentation-Guided Semantic-Aware Self-Supervised Denoising for SAR Image](https://ieeexplore.ieee.org/document/10285521)

**Ye Yuan**, Yanxia Wu\*, Pengming Feng, Yan Fu, Yulei Wu

- We propose a segmentation-guided semantic-aware self-supervised denoising method for SAR images, namely, SARDeSeg, where a segmentation network is incorporated with a denoising network and guides it to learn and be aware of the semantic information of the input noisy SAR images. The proposed SARDeSeg outperforms state-of-the-art (SOTA) denoising methods for SAR images, particularly in preserving detailed edge features.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE ICME 2024</div><img src='images/IEEE_ICME_2024_CP-FND.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Cross-Point Adversarial Attack Based on Feature Neighborhood Disruption Against Segment Anything Model](https://ieeexplore.ieee.org/document/10687491)

Yan Jiang; Guisheng Yin; **Ye Yuan**\*; Jingjing Chen; Zhipeng Wei

- We propose a cross-point adversarial attack method based on feature neighborhood disruption against SAM, called CP-FND attack. CP-FND aims to generate adversarial examples capable of effectively deceiving SAM under different user-specified point prompts. Specifically, CP-FND can disrupt the continuity and relevance of contextual features, thereby fooling SAM and suppressing its predicted masks.
</div>
</div>

# 📄 Publications (<a href='https://scholar.google.com/citations?user=p0z29tMAAAAJ'>google scholar citations <strong><span id='total_cit'>+</span></strong></a>)
\* Corresponding author           $\dagger$ Equal contribution
# 2025

- Chao Li, Haitao Lyu, Weipeng Jing, **Ye Yuan**\*, Guangliang Cheng, "MFFNet: a wavelet transform-based multimodal frequency fusion network for remote sensing semantic segmentation," *GIScience & Remote Sensing*, 2025. [[link](https://www.tandfonline.com/doi/full/10.1080/15481603.2025.2534740)] <span style="color:blue">[JCR Q1, 中科院一区 Top, IF: 6.9]</span>
- Xu Wang$\dagger$, Yanxia Wu$\dagger$, **Ye Yuan**\*, Guangliang Cheng and Yulei Wu, "SAR-ASGOUT: Adversarial Speckle Generation and Offline Unpaired Training for Unsupervised SAR Despeckling," *IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing*, 2025. [[link](https://ieeexplore.ieee.org/document/11036683/authors#authors)] <span style="color:blue">[JCR Q1, 中科院二区 Top, IF: 4.7]</span>
- Xue Zhang$\dagger$, Yanxia Wu$\dagger$, Guoyin Zhang, **Ye Yuan**\*, Guangliang Cheng and Yulei Wu, "Shape-Dependent Dynamic Label Assignment for Oriented Remote Sensing Object Detection," *IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing*, vol. 18, pp. 132-146, 2025. [[link](https://ieeexplore.ieee.org/document/10745646/authors#authors)] <span style="color:blue">[JCR Q1, 中科院二区 Top, IF: 4.7]</span>

# 2024

- Xu Wang$\dagger$, Yanxia Wu$\dagger$, **Ye Yuan**\*, Yan Fu and Xue Zhang, "Unpaired Image Despeckling Based on Adversarial Speckle Generation," in *Proceedings of IEEE International Conference on Multimedia and Expo (ICME)*, 2024, pp. 1-6. [[link](https://ieeexplore.ieee.org/document/10687879)] <span style="color:blue">[CCF-B会议]</span>
- Yan Jiang, Guisheng Yin, **Ye Yuan**\*, Jingjing Chen and Zhipeng Wei, "Cross-Point Adversarial Attack Based on Feature Neighborhood Disruption Against Segment Anything Model," in *Proceedings of IEEE International Conference on Multimedia and Expo (ICME)*, 2024, pp. 1-6. [[link](https://ieeexplore.ieee.org/document/10687491)] <span style="color:blue">[CCF-B会议]</span>
- Xu Wang, Yanxia Wu, Changting Shi\*, **Ye Yuan** and Xue Zhang, "ANED-Net: Adaptive Noise Estimation and Despeckling Network for SAR Image," *IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing*, vol. 17, pp. 4036-4051, 2024. [[link](https://ieeexplore.ieee.org/document/10401972)] <span style="color:blue">[JCR Q1, 中科院二区 Top, IF: 4.7]</span>
- Yan Jiang, Guisheng Yin, Weipeng Jing, Linda Mohaisen, Mahmoud Emam and **Ye Yuan**\*, "Box-Spoof Attack Against Single Object Tracking," *Applied Intelligence*, vol. 54, no. 2, pp. 1585-1601, 2024. [[link](https://link.springer.com/article/10.1007/s10489-023-05264-2)] <span style="color:blue">[JCR Q2, 中科院二区, CCF-C, IF: 3.4]</span>
  
# 2023

- **Ye Yuan**, Yanxia Wu\*, Pengming Feng, Yan Fu and Yulei Wu, "Segmentation-Guided Semantic-Aware Self-Supervised Denoising for SAR Image," *IEEE Transactions on Geoscience and Remote Sensing*, vol. 61, pp. 1-16, 2023, Art no. 5218416. [[link](https://ieeexplore.ieee.org/document/10285521)] <span style="color:blue">[JCR Q1, 中科院一区, CCF-B, IF: 7.5]</span>

# 2022

- **Ye Yuan**$\dagger$, Yanxia Wu$\dagger$, Chuheng Tang, Yan Fu\*, Yulei Wu, Yan Jiang and Yize Zhao, "Self-calibrated dilated convolutional neural networks for SAR image despeckling," *International Journal of Remote Sensing*, vol. 43, no. 17, pp. 6483-6508, 2022. [[link](https://www.tandfonline.com/doi/full/10.1080/01431161.2022.2142076)] <span style="color:blue">[JCR Q2, 中科院三区, IF: 3.0]</span>
- **Ye Yuan**, Jian Guan\*, Pengming Feng and Yanxia Wu, "A Practical Solution for SAR Despeckling With Adversarial Learning Generated Speckled-to-Speckled Images," *IEEE Geoscience and Remote Sensing Letters*, vol. 19, pp. 1-5, 2022, Art no. 4004705. [[link](https://ieeexplore.ieee.org/document/9274511)] <span style="color:blue">[JCR Q1, 中科院二区, CCF-C, IF: 4.0]</span>

# 2021

- **Ye Yuan**, Yanxia Wu\*, Yan Fu, Yulei Wu, Lidan Zhang and Yan Jiang, "An Advanced SAR Image Despeckling Method by Bernoulli-Sampling-Based Self-Supervised Deep Learning," *Remote Sensing*, vol. 13, no. 18, pp. 3636, 2021. [[link](https://www.mdpi.com/2072-4292/13/18/3636)] <span style="color:blue">[JCR Q1, 中科院二区 Top, IF: 4.2]</span>
- **Ye Yuan**, Yan Jiang, Yanxia Wu\* and Richard Jiang, "Self-Calibrated Convolutional Neural Network for SAR Image Despeckling," in *Proceddings of IEEE International Geoscience and Remote Sensing Symposium (IGARSS)*, 2021, pp. 399-402. [[link](https://ieeexplore.ieee.org/document/9554769)] <span style="color:blue">[EI会议]</span>

# 2020 and before

- Yanxia Wu\*, **Ye Yuan**, Jian Guan, Libo Yin, Jinyong Chen and Ge Zhang, "Joint Convolutional Neural Network for Small-Scale Ship Classification in SAR Images," in *Proceedings of IEEE International Geoscience and Remote Sensing Symposium (IGARSS)*, 2019, pp. 2619-2622. [[link](https://ieeexplore.ieee.org/document/8897831)] <span style="color:blue">[EI会议]</span>
- **Ye Yuan**\*, Shouzheng Li, Xingjian Zhang and Jianguo Sun, "A Comparative Analysis of SVM, Naive Bayes and GBDT for Data Faults Detection in WSNs," in *Proceedings of IEEE International Conference on Software Quality, Reliability and Security Companion (QRS-C)*, 2018, pp. 394-399. [[link](https://ieeexplore.ieee.org/document/8432003)] <span style="color:blue">[CCF-B会议]</span>

# 💠 Fundings

- 哈尔滨工程大学-计算机科学与技术学院, 博士研究生科研创新基金, 语义感知型SAR图像自监督去噪方法研究, 2022-2023, 主持

# 📑 Services
Invited Reviewer for conferences:
- 2024,2025 IEEE International Conference on Multimedia and Expo (ICME)
  
Invited Reviewer for journals:
- IEEE Transactions on Geoscience and Remote Sensing
- ISPRS Journal of Photogrammetry and Remote Sensing
- International Journal of Applied Earth Observation and Geoinformation
- IEEE Geoscience and Remote Sensing Letters
- Knowledge-Based Systems
- Signal Processing
- Pattern recognition letters
- Computers and Electrical Engineering
- Computers and Electronics in Agriculture
- International Journal of Communication Systems

  
<!--

# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.

-->
