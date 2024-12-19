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

My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).


# 🔥 News
- *2024.12*: &nbsp;🎉🎉 New stage of career! I joined the College of Computer and Control Engineering at **Northeast Forestry University**!
- *2024.10*: &nbsp;🎉🎉 One journal paper about oriented remote sensing object detection has been accepted by **IEEE JSTARS** ([link](https://ieeexplore.ieee.org/document/10745646))!
- *2024.04*: &nbsp;🎉🎉 One conference paper about unpaired image despeckling has been accepted by **IEEE ICME 2024** ([link](https://ieeexplore.ieee.org/document/10687879))!
- *2024.04*: &nbsp;🎉🎉 One conference paper about adversarial attack for SAM has been accepted by **IEEE ICME 2024** ([link](https://ieeexplore.ieee.org/document/10687491))!
- *2023.12*: &nbsp;🎉🎉 Completed the defense of my PhD thesis (**Research on deep learning based denoising methods for SAR images**) and **received my PhD degree**!
- *2023.09*: &nbsp;🎉🎉 One journal paper about self-supervised SAR image denoising has been accepted by **IEEE TGRS** ([link](https://ieeexplore.ieee.org/document/10285521))!

# 📝 Research Spotlight 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TGRS 2023</div><img src='images/IEEE_TGRS_2023_SARDeSeg.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Segmentation-Guided Semantic-Aware Self-Supervised Denoising for SAR Image](https://ieeexplore.ieee.org/document/10285521)

**Ye Yuan**, Yanxia Wu*, Pengming Feng, Yan Fu, Yulei Wu

- We propose a segmentation-guided semantic-aware self-supervised denoising method for SAR images, namely, SARDeSeg, where a segmentation network is incorporated with a denoising network and guides it to learn and be aware of the semantic information of the input noisy SAR images. The proposed SARDeSeg outperforms state-of-the-art (SOTA) denoising methods for SAR images, particularly in preserving detailed edge features.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE ICME 2024</div><img src='images/IEEE_ICME_2024_CP-FND.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Cross-Point Adversarial Attack Based on Feature Neighborhood Disruption Against Segment Anything Model](https://ieeexplore.ieee.org/document/10687491)

Yan Jiang; Guisheng Yin; **Ye Yuan** *; Jingjing Chen; Zhipeng Wei

- We propose a cross-point adversarial attack method based on feature neighborhood disruption against SAM, called CP-FND attack. CP-FND aims to generate adversarial examples capable of effectively deceiving SAM under different user-specified point prompts. Specifically, CP-FND can disrupt the continuity and relevance of contextual features, thereby fooling SAM and suppressing its predicted masks.
</div>
</div>

# 📄 Publications

# 2025

- Xue Zhang, Yanxia Wu*, Guoyin Zhang, **Ye Yuan**, Guangliang Cheng and Yulei Wu, "Shape-Dependent Dynamic Label Assignment for Oriented Remote Sensing Object Detection," IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing, vol. 18, pp. 132-146, 2025. [[link](https://ieeexplore.ieee.org/document/10745646/authors#authors)]

# 2024

- Xu Wang, Yanxia Wu, **Ye Yuan**, Yan Fu and Xue Zhang, "Unpaired Image Despeckling Based on Adversarial Speckle Generation," in Proceedings of IEEE International Conference on Multimedia and Expo (ICME), 2024, pp. 1-6. [[link](https://ieeexplore.ieee.org/document/10687879)]
- Yan Jiang, Guisheng Yin, **Ye Yuan**, Jingjing Chen and Zhipeng Wei, "Cross-Point Adversarial Attack Based on Feature Neighborhood Disruption Against Segment Anything Model," in Proceedings of IEEE International Conference on Multimedia and Expo (ICME), 2024, pp. 1-6. [[link](https://ieeexplore.ieee.org/document/10687491)]
- Xu Wang, Yanxia Wu, Changting Shi*, **Ye Yuan** and Xue Zhang, "ANED-Net: Adaptive Noise Estimation and Despeckling Network for SAR Image," IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing, vol. 17, pp. 4036-4051, 2024. [[link](https://ieeexplore.ieee.org/document/10401972)]
- Yan Jiang, Guisheng Yin, Weipeng Jing, Linda Mohaisen, Mahmoud Emam and **Ye Yuan***, "Box-Spoof Attack Against Single Object Tracking," Applied Intelligence, vol. 54, no. 2, pp. 1585-1601, 2024. [[link](https://link.springer.com/article/10.1007/s10489-023-05264-2)]
  
# 2023

- **Ye Yuan**, Yanxia Wu*, Pengming Feng, Yan Fu and Yulei Wu, "Segmentation-Guided Semantic-Aware Self-Supervised Denoising for SAR Image," IEEE Transactions on Geoscience and Remote Sensing, vol. 61, pp. 1-16, 2023, Art no. 5218416. [[link](https://ieeexplore.ieee.org/document/10285521)]

# 2022

- **Ye Yuan**, Yanxia Wu, Chuheng Tang, Yan Fu*, Yulei Wu, Yan Jiang and Yize Zhao, "Self-calibrated dilated convolutional neural networks for SAR image despeckling," International Journal of Remote Sensing, vol. 43, no. 17, pp. 6483-6508, 2022. [[link](https://www.tandfonline.com/doi/full/10.1080/01431161.2022.2142076)]
- **Ye Yuan**, Jian Guan*, Pengming Feng and Yanxia Wu, "A Practical Solution for SAR Despeckling With Adversarial Learning Generated Speckled-to-Speckled Images," IEEE Geoscience and Remote Sensing Letters, vol. 19, pp. 1-5, 2022, Art no. 4004705. [[link](https://ieeexplore.ieee.org/document/9274511)]


# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Education and Work Experience
- *2024.12 - now*, Associate Professor, College of Computer and Control Engineering, Northeast Forestry University


- *2018.09 - 2023.12*, Ph.D, College of Computer Science and Technology, Harbin Engineering University
- *2017.09 - 2018.06*, M.S. transfer to Ph.D, College of Computer Science and Technology, Harbin Engineering University
- *2013.09 - 2017.06*, B.S., College of Computer Science and Technology, Harbin Engineering University

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
